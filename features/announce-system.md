---
description: Recurrent announces
---

# 📢 Announce system

## Commands

### /announce \<start/stop> \<announceName>

You can use it with **`redischat.announce`** permission.&#x20;

"start" - starts the clock to send the announcement defined in the config section

"stop" - stops the clock

"announceName" - the name of the announce to start/stop defined in the config section

## Configs

announces (list)

````yaml
```yaml
# Announcer configurations
# delay and interval are in seconds
# If you want to disable an announce, remove it from the list (announces: [])
# Remember that in yaml [] is an empty list
# If you specify a permission, only players with that permission will see the announce. Keep it empty to make it public
announces:
- announceName: default
  message: '<red>RedisChat Announce: <br><white>lorem ipsum dolor sit amet'
  permission: ''
  delay: 5
  interval: 300
```
````
