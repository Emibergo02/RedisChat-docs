---
description: A system to reach a group of player ("multicast")
---

# 🎭 Channels

### How can I see messages from a specific channel?

You need to have the permission `redischat.channel.channelName`&#x20;

For example, to see messages from the "public" channel it's`redischat.channel.public`

### How can I write in a channel?

You have to click on the channel button inside the GUI below

## Commands

### /channel or /channels or /ch

Opens the channels GUI

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>Channel GUI</p></figcaption></figure>

### /channel create \<channelName> \<rate-limit> \<rate-limit-seconds> \<filtered> \[discordWebhook] \[proximityDistance]

Rate-limit is the message limit every "rate-limit-seconds" seconds

If you put filtered on true you will moderate the messages through the word-blacklist inside config.yml

[Proximity: how many blocks away from the sender the message will be sent](local-proximity-chat.md)



### /channel setformat \<chat message format>

You can use Minimessage Viewer to edit the format



### /channel enable \<playerName> \<channelName>

Enables a channel for a player



### /channel disable \<playerName> \<channelName>

Disables a channel for a player



### /channel force-listen \<playerName> \<channelName>

Force a player to write inside a channel
