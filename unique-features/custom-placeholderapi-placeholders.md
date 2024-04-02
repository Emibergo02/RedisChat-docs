---
description: Use convenient commands to configure your placeholders!
---

# 🥡 Custom PlaceholderAPI placeholders

### Every player can have many different but unique PAPI placeholder with RedisChat!

To use this feature you'll need this command

### /setchatplaceholders \<player> \<placeholder> \<value>

* `<player>`: This is the player's username for whom you want to set the chat placeholders. This needs to be the exact name as it appears in-game.
* `<placeholder>`: This refers to the specific PlaceholderAPI identifier after %redischat\_\
  For example, if you set "blacktree" placeholder you can display it through the placeholder\
  %redischat\_blacktree%
* `<value>`: The value you wish to assign to the specified placeholder. This could be any string of text or numbers you want to display in place of the placeholder.

### Example

You know that the placeholder `%redischat_chat_color%` is the one used for chat color\
as shown in [chat-color.md](../features/chat-color.md "mention")

You need to set a particular chat color to the player named **John0101** to "blue"

To set a specific color component (using MiniMessage tags), use the following command:

```
/setchatplaceholders John0101 chat_color <blue>
```

You can also use hex colors in this example (like "<#ab778f>" instead of "\<blue>")
