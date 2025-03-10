---
description: Create your tags to be used in chat
---

# #️⃣ #️⃣ Emoji placeholders

Create content with custom Minimessage tags

And use them with \<placeholder\_name>

<figure><img src="../.gitbook/assets/redischat_custom_placeholders.png" alt=""><figcaption><p>Cringe screenshot</p></figcaption></figure>

## Configs

placeholders (list) ->&#x20;

{% code title="config.yml" %}
```yaml
placeholders:
  discord: <click:open_url:https://discord.gg/C8d7EqQz>Click to join our discord server</click>
  position: <white><blue>Server:</blue> %server_name% <aqua>World:</aqua> %player_world%
    <gold>X:</gold> %player_x% <gold>Y:</gold> %player_y% <gold>Z:</gold> %player_z%</white>
  <3: <red>❤</red>
  '*caution*': ⚠
  '*check*': <green>✔</green>
  '*clock*': ⌚
  '*cross*': <red>✖</red>
  '*hazard*': ☣
  '*music*': ♫
  '*peace*': ☮
  '*pirate*': ☠
  '*radioactive*': ☢
  '*snow*': ❄
  '*star*': ★
  '*timer*': ⌛
  :(: ☹
  :): ☺
  
  <<: «
  '>>': »
  

```
{% endcode %}

Permission: `redischat.use_emoji`
