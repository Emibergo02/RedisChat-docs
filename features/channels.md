---
description: A system to reach a group of player ("multicast")
---

# 🎭 Channels

### How can I see messages from a specific channel?

You need to have the permission <mark style="color:orange;">**`redischat.channel.channel-name`**</mark> to **read and write** on the channel

If you want to give only **read** permission, it is <mark style="color:orange;">`redischat.channel.channel-name.read`</mark>

The same with **write** permission:                    <mark style="color:orange;">`redischat.channel.channel-name.write`</mark>

For example, to read and write on the "public" channel it's <mark style="color:orange;">`redischat.channel.public`</mark>

If you want to **hide** a channel from a player, use: <mark style="color:orange;">`redischat.hidechannel.channel-name`</mark>



## Commands

### <mark style="color:orange;">`/channel`</mark> or <mark style="color:orange;">`/channels`</mark> or <mark style="color:orange;">`/ch`</mark>

Opens the channels GUI

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>Channel GUI</p></figcaption></figure>

### <mark style="color:orange;">`/channel create <channelName> <rate-limit> <rate-limit-seconds> <filtered> [discordWebhook] [proximityDistance]`</mark>

Rate-limit is the message limit every "rate-limit-seconds" seconds

If you put filtered on true you will moderate the messages through the word-blacklist inside config.yml

[Proximity: how many blocks away from the sender the message will be sent](local-proximity-chat.md)



### <mark style="color:orange;">`/channel setformat <chat message format>`</mark>

You can use Minimessage Viewer to edit the format

### <mark style="color:orange;">`/channel force-listen <playerName> <channelName>`</mark>

Force a player to write inside a channel
