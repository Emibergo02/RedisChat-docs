---
description: A system to reach a group of player ("multicast")
---

# 🎭 Channels

## Commands

### /channel or /channels or /ch

Opens the channels GUI

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption><p>Channel GUI</p></figcaption></figure>

### /channel create \<channelName> \<rate-limit> \<rate-limit-seconds> \<filtered> \[discordWebhook] \[proximityDistance]

Rate-limit is the message limit every "rate-limit-seconds" seconds

If you put filtered on true you will moderate the messages through the word-blacklist inside config.yml

Proximity (to be implemented) : how many blocks away from the sender the message will be sent



### /channel setformat \<chat message format>

You can use Minimessage Viewer to edit the format



### /channel enable \<playerName> \<channelName>

Enables a channel for a player



### /channel disable \<playerName> \<channelName>

Disables a channel for a player
