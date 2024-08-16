---
description: A system to reach a group of player ("multicast")
---

# 🎭 Channels

### How can I see messages from a specific channel?

You need to have read and/or write permission for the channel:\
<mark style="color:orange;">**`redischat.channel.channel-name`**</mark>                     ->  Read AND write\
<mark style="color:orange;">**`redischat.channel.channel-name.read`**</mark>          ->  Read\
<mark style="color:orange;">**`redischat.channel.channel-name.write`**</mark>        ->  Write

For example, to read and write on the "public" channel it's <mark style="color:orange;">`redischat.channel.public`</mark>

If you want to **hide** a channel from a player, use: <mark style="color:orange;">`redischat.hidechannel.channel-name`</mark>



## Commands

### <mark style="color:orange;">`/channel`</mark> or <mark style="color:orange;">`/channels`</mark> or <mark style="color:orange;">`/ch`</mark>

Opens the channels GUI

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>Channel GUI</p></figcaption></figure>

### <mark style="color:orange;">`/channel create <channelName> <rate-limit> <rate-limit-seconds> <filtered> [proximityDistance] [discordWebhook] [shown-by-default] [permission-required]`</mark>

<mark style="color:green;">Rate limit</mark> :   It's the message limit every "rate-limit-seconds" seconds

<mark style="color:green;">Filtered</mark> :   Whether to filter out swear words or not (**word-blacklist inside config.yml**)

<mark style="color:green;">Proximity</mark> : [local-proximity-chat.md](local-proximity-chat.md "mention")

<mark style="color:green;">Discord webhook</mark> : [#webhooks](discord-hook.md#webhooks "mention")

<mark style="color:green;">Shown by default</mark> :   If the channel is shown by default inside channels GUI or you need the \
&#x20;                                     permission <mark style="color:orange;">`redischat.showchannel.channelName`</mark>

<mark style="color:green;">Permission required</mark> :   Whether to apply permission requirements as specified at the start of the page\
&#x20;                                          or not



### <mark style="color:orange;">`/channel setformat <chat message format>`</mark>

You can use Minimessage Viewer to edit the format

### <mark style="color:orange;">`/channel force-listen <playerName> <channelName>`</mark>

Force a player to write inside a channel

### <mark style="color:orange;">`/channel setdisplayname <channelName> <displayName>`</mark>

Permission <mark style="color:orange;">`redischat.changedisplayname`</mark> is required
