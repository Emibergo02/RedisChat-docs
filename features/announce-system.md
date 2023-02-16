---
description: Recurrent announces
---

# Announce system

## Commands

### /announce \<start/stop> \<announceName>

You can use it with **`redischat.announce`** permission.&#x20;

"start" - starts the clock to send the announce defined in the config section

"stop" - stops the clock

"announceName" - the name of the announce to start/stop defined in the config section

## Configs

announces (list)

````yaml
```yaml
# Announces configs
# delay and interval are in seconds
# If you want to disable an announce, just remove it from the list
announces: 
  - announceName: Golden Sunday
    message: <gold>100% discount of cookies</gold><br><aqua>Just kidding</aqua>
    delay: 10
    interval: 10
```
````
