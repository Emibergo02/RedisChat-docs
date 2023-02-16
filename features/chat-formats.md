---
description: Permission-based formats for your chat
---

# Chat formats

Every player have a chat formatting based on his permissions.

You can use MiniMessage tags and PlaceholderAPI placeholders

## Configs

formats (list)

````yaml
  ```yaml
# The format of the chat
# Permission format is overridden on descending order
# (if a player has default and vip, if default is the first element, vip will be ignored)
formats:
- permission: redischat.default
  format: '<click:suggest_command:/msg %player_name%><hover:show_text:''<reset>Information
    | <white>%player_displayname%<br><gold><bold>➧</bold> Money<reset>: <white>%vault_eco_balance%
    <gold>✵<br><br><reset><underlined>Click to send a message''><white><gradient:yellow:blue>RGB</gradient>
    - %player_name% </click> <dark_gray>» <reset>%message%'
  private_format: '<dark_aqua>MSG <white>(<reset>You <white>to <green>%receiver%<white>)<reset>:
    <white>%message%'
  receive_private_format: '<dark_aqua>MSG <white>(<green>%sender% <white>to <reset>You<white>)<reset>:
    <white>%message%'
  inventory_format: <click:run_command:%command%>[Open the inventory of %player%]</click>
  item_format: <click:run_command:%command%>[%item_name% of %player%]</click>
  enderchest_format: <click:run_command:%command%>[Open the enderchest of %player%]</click>
  mention_format: <aqua>@%player%</aqua>
  link_format: <green><click:open_url:%link%>%link%</green> <- Click here
```
````

#### Permission format is overridden on descending order

example: If i have `redischat.admin` and `redischat.default` i need to put the "admin" formatting under the "default" one in the **`formats`** key list

#### format - is the normal chat formatting

%player\_name% - is the sender's name

%message% - the message content (formattable with Minimessage with **`redischat.useformatting`** permission

#### private\_format - private chat formatting

Covered in [private-messages.md](private-messages.md "mention")

#### receive\_private\_format - private chat receiving formatting

Covered in [private-messages.md](private-messages.md "mention")

```
redischat.useformatting
```
