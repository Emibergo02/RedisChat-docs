# 🔇 Ignore private messages

## Commands

### /ignore \<list,playerName>

You can use it with **`redischat.ignore`** permission

"list" - lists all ignored players

The player name field is suggested by RedisChat starting from all the player names saved on RedisChat on every instance of it

The command toggles the ignore of a player

## Configs

ignoring\_list, ignoring\_player, not\_ignoring\_player

```yaml
ignoring_list: <aqua>Player ignored</aqua><br><green>%list%</green>
ignoring_player: <green>Toggled ignoring of %player%</green>
not_ignoring_player: <green>Ignore removed for %player%</green>
```
