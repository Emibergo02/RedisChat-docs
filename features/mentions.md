---
description: Mention other players
---

# @      Mentions

The mentioned player will receive a sound notification and a title _(todo)_

Just write in chat the name of an online player and it will be formatted as defined in the config section

<figure><img src="../.gitbook/assets/redischat_mentions (1).png" alt=""><figcaption></figcaption></figure>

## Configs

mentionSound ->

{% code title="config.yml" %}
```yaml
# Format id:volume:pitch
# You can find the list of sounds here: 
# https://jd.papermc.io/paper/1.20/org/bukkit/Sound.html
# Leave it empty "" to disable the sound
mentionSound: ENTITY_EXPERIENCE_ORB_PICKUP:1:1
```
{% endcode %}

[formats](chat-formats.md) (list) ->&#x20;

```yaml
mention_format: <aqua>@%player%</aqua>
```
