---
description: Broadcasts a message to all players connected through RedisChat
---

# 🔊 Broadcast messages

## Commands

### /broadcast \<channelName> \<message>

You can use it with **`redischat.broadcast`** permission.

The message field can be formatted with MiniMessage

### /broadcastraw \<channelName> \<message>

You can use it with **`redischat.broadcastraw`** permission.&#x20;

It is the same as /broadcast but without `broadcast_format`

### Use "public" as a channel name if you want to send it to all players

## Configs

broadcast\_format (String)

```yaml
broadcast_format: <red>Announce <dark_gray>» <white>%message%
```

%message% pastes the message content
