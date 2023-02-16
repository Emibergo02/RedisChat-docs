---
description: Broadcasts a message to all players connected through RedisChat
---

# Broadcast messages

## Commands

### /broadcast \<message>

You can use it with **`redischat.broadcast`** permission.&#x20;

The message field can be formatted with MiniMessage

## Configs

broadcast\_format (String)

```yaml
broadcast_format: <red>Announce <dark_gray>» <white>%message%
```

%message% pastes the message content
