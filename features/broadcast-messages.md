---
description: Broadcasts a message to all players connected through RedisChat
---

# 🔊 Broadcast messages

## Commands

### /broadcast \<message>

You can use it with **`redischat.broadcast`** permission.&#x20;

The message field can be formatted with MiniMessage

### /broadcastraw \<message>

You can use it with **`redischat.broadcastraw`** permission.&#x20;

The same as /broadcast but without `broadcast_format`

## Configs

broadcast\_format (String)

```yaml
broadcast_format: <red>Announce <dark_gray>» <white>%message%
```

%message% pastes the message content
