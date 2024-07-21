# ☄️ Components

With components, it is easier to configure [chat-formats.md](chat-formats.md "mention")

```yaml
formats:
- permission: redischat.default
  format: '{time} {ignorebtn} {mailbtn} {player} <dark_gray> » %redischat_chatcolor%
    {message}'
  private_format: '<white>✉<green>⬆</green></white> <dark_aqua>MSG <grey>(Me ➺ <green>%receiver%<grey>):
    <white>{message}'
  receive_private_format: '<white>✉<green>⬇</green></white> <dark_aqua>MSG <grey>(<green>%sender%<grey>
    ➺ Me): <white>{message}'
  mention_format: <aqua>@%player%</aqua>
  link_format: <aqua><click:open_url:%link%>[Open web page <red>(be careful)</red>]</aqua>
  join_format: <green>%player_name% joined the server
  quit_format: <red>%player_name% is no longer online
components:
  ignorebtn: <click:run_command:/ignore %player_name%><hover:show_text:'<red>Ignore
    %player_name%</red>'>[<red>✖</red>]</click>
  mailbtn: <click:suggest_command:/mail send %player_name%><hover:show_text:'<green>Send
    a mail to %player_name%</green>'>[<green>✉</green>]</click>
  player: '<click:suggest_command:/msg %player_name%><hover:show_text:''<gray>Info|</gray>
    <white>%player_displayname%</white> <br>↪ <gold>Money</gold>: <white>%vault_eco_balance%$</white><br>↪
    <green>Server</green>: <white>%server_name%</white> <br><br><gray>Clickto send
    a private message</gray>''>%vault_prefix% %player_name%</click>'
  time: '[<gray>%localtime_time_HH:mm%</gray>]'
```

Components are identified by the <mark style="color:orange;">`{ }`</mark> brackets

They contain a MiniMessage component to be replaced inside all the formats provided inside\
[chat-formats.md](chat-formats.md "mention") sections

There is a special component <mark style="color:orange;">`{message}`</mark>\
This placeholder will be replaced with the actual content of the message\
