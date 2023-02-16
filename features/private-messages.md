---
description: Send private messages to other players
---

# Private messages

## Commands

### /msg \<playername> \<message>

You can use it with **`redischat.message`** permission.&#x20;

The playername field is suggested by RedisChat starting from all the playernames saved on RedisChat on every instance of it

The message field can be formatted with MiniMessage but you need **`redischat.useformatting`** to use MiniMessage tags

### &#x20;/reply \<message>

Reply to the last received message. It has the same permission as /msg

The message field can be formatted with MiniMessage but you need **`redischat.useformatting`** to use MiniMessage tags

## Configs

formats (list) -> private\_format - **when sending a message**

```yaml
  private_format: '<dark_aqua>MSG <white>(<reset>You <white>to <green>%receiver%<white>)<reset>:
    <white>%message%'
```

formats (list) -> receive\_private\_format - **when receiving a message**

```yaml
  receive_private_format: '<dark_aqua>MSG <white>(<green>%sender% <white>to <reset>You<white>)<reset>:
    <white>%message%'
```

%receiver% is the name of the receiver

%sender% is the name of the sender

%message% pastes the message content
