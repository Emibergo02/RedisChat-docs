---
description: Link your discord channels with RedisChat channels
---

# 🐨 Discord hook

## Webhooks

Webhooks are a simple way to send messages to a Discord channel. However, remember that communication only takes place in the direction Minecraft -> discord with this method

You can create a webhook for a channel with the command&#x20;

`/channel link-discord-webook <channelName>`**`<webhook link>`**

The webhook link can be obtained in: Discord channel settings -> Integrations -> Create webhook

***

## Spicord hook

Spicord, unlike webhooks, allows two-way communication between Discord and Minecraft

To enable this feature you need to :

1. Enable Spicord inside RedisChat (enabled: true)

{% code title="config.yml" fullWidth="false" %}
```yaml
# botName is the botId associated to the bot inside the spicord configuration
# Every channel of RedisChat is linked with a channel on Discord
# The first element is a RedisChat channel, the second one is a Discord channel id
# You can find the Discord channel id by right clicking on the channel and clicking on 'Copy ID'
spicord:
  enabled: true
  chatFormat: '<blue>[Discord]</blue> %username% » %message%'
  discordFormat: '**%channel%** %sender% » %message%'
  spicordChannelLink:
    public: '502465727593447434'
```
{% endcode %}

2. Set up the Spicord bot as defined on [the SpigotMC page under Installation and below](https://www.spigotmc.org/resources/spicord.64918/)
3. Add "redischat" as an addon inside the Spicord bot configuration

{% code title="Spicord/config.toml" %}
```toml
[[bots]]
  name = "default"
  enabled = true
  token = "MTE*NjA1Nzc1Mz*DkwNTEzOA.******************************************"
  command_support = true #You need this to true to send messages from Discord to MC
  command_prefix = "-"
  addons = [
    "redischat",
    "otheraddon"
  ]
```
{% endcode %}

4. Link channels to discord channel ids:

{% code title="config.yml" %}
```yaml
  spicordChannelLink:
    public: '502465727593447434' 
 #The ID is obtained by right-clicking on the Discord channel and then Copy channel ID
```
{% endcode %}

5. Invite the bot to your discord server ([Follow this guide](https://github.com/Spicord/Spicord/blob/v5/tutorial/CREATE-A-BOT.md) taken from Spicord)
