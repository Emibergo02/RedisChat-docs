# ⛓ Keep chat (1.20.2+)

From version 1.20.2, the Minecraft client deletes chat when&#x20;

switching servers inside a proxy (during reconfiguration phase)

### Resend chat on join

```yaml
# Since 1.20.2 client's chat is cleared when switching servers
# This feature is to prevent chat clearing. RedisChat will send the last N received messages to the player
# Set it to 0 to disable this feature
keepChatMessages: 15
```

