---
description: Customize join and quit messages
---

# 😎 Join and quit messages

#### You can customize join and quit messages inside the config.yml based on permissions

{% code title="config.yml" %}
```yaml
# Use RedisChat for join and quit messages
# The quit message will be delayed because it might be an early reconnection to one of the servers using RedisChat
enableQuitJoinMessages: true

formats:
- permission: redischat.default
# The rest of the config section ...
  join_format: <green>%player_name% joined the server
  quit_format: <red>%player_name% is no longer online
```
{% endcode %}

If you're using a communication system based on PluginMessages (not recommended)

You will have problems with the quit message sending because of the limitation that PluginMessages have (they need at least a player online to work)

So please use Redis if you need this feature
