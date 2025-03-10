---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🖇️ ALL permissions

* <mark style="color:orange;">`redischat.chatcolor`</mark> to execute /chatcolor\
  <mark style="color:orange;">`redischat.chatcolor.hex`</mark> to use hex colors\
  <mark style="color:orange;">`redischat.chatcolor.<chatcolor>`</mark> to use specific chat colors (Minimessage tags)
* <mark style="color:orange;">`redischat.useformatting`</mark> Allows to use minimessage formatting and PlaceholderAPI placeholders in chat. Some dangerous MiniMessage tags are denied. To allow the use of dangerous tags, use the permission below
* <mark style="color:orange;">`redischat.setitem`</mark> Allows to use the /setitem command.
* <mark style="color:orange;">`redischat.talkon`</mark> Allows to use the /talkon command.
* <mark style="color:orange;">`redischat.ignore`</mark> Allows to use the /ignore command.
* <mark style="color:orange;">`redischat.clearchat`</mark> Allows to use the /clearchat command.
* <mark style="color:orange;">`redischat.spycommand`</mark> Allows to use the /spychat command.
* <mark style="color:orange;">`redischat.spycommand.other`</mark> Allows to use the /spychat command others.
* <mark style="color:orange;">`redischat.setchatplaceholder`</mark> Allows to use[#setchatplaceholders-less-than-player-greater-than-less-than-placeholder-greater-than-less-than-value](unique-features/custom-placeholderapi-placeholders.md#setchatplaceholders-less-than-player-greater-than-less-than-placeholder-greater-than-less-than-value "mention")
* <mark style="color:orange;">`redischat.channelgui`</mark> Allows to open the /channel GUI.
* <mark style="color:orange;">`redischat.listchannel`</mark> Allows to list channels.
* <mark style="color:orange;">`redischat.mutechannel`</mark> Allows to mute channels.
* <mark style="color:orange;">`redischat.joinquit`</mark> Allows to see the join and quit messages.
* <mark style="color:orange;">`redischat.use_emoji`</mark> Allows to use [emoji-placeholders.md](unique-features/emoji-placeholders.md "mention")
* <mark style="color:orange;">`redischat.showitem`</mark> Allows to see the item tag in the chat.
* <mark style="color:orange;">`redischat.showinv`</mark> Allows to see the inventory in the chat.
* <mark style="color:orange;">`redischat.showenderchest`</mark> Allows to see \[ec] in the chat.
* <mark style="color:orange;">`redischat.spychat`</mark> If enabled, you'd be spying private messages
* <mark style="color:orange;">`redischat.usedangeroustags`</mark> Allows the use of potentially dangerous formatting tags in messages such as \<click:run\_command> tag
* <mark style="color:orange;">`redischat.broadcast`</mark> Allows to use the /broadcast command.
* <mark style="color:orange;">`redischat.broadcastraw`</mark> Allows to use the /broadcastraw command.
* <mark style="color:orange;">`redischat.chatas`</mark> Allows to use the /chatas command.
* <mark style="color:orange;">`redischat.message`</mark> Allows to use the /msg command.
* <mark style="color:orange;">`redischat.staffchat`</mark> Allows to use the /staffchat command.
* <mark style="color:orange;">`redischat.bypass_rate_limit`</mark> Bypasses the rate limit.
* <mark style="color:orange;">`redischat.bypassfilter.caps`</mark> Skips the caps filter.
* <mark style="color:orange;">`redischat.bypassfilter.duplicate`</mark>Skips the duplicate filter.
* <mark style="color:orange;">`redischat.bypassfilter.spam`</mark> Skips the spam (or rate-limit) filter \
  (It's better to use redischat.bypass\_rate\_limit)
* <mark style="color:orange;">`redischat.bypassfilter.discord`</mark> Allows to bypass the discord filter (Sends the message to Discord if the integration is enabled)
* <mark style="color:orange;">`redischat.bypassfilter.ignore_player`</mark> Skips the ignore\_player filter. This filter works when a player receives a private message. The filter handles warning messages if the player is ignoring the sender or hides public messages if `ignoreChannelMessages` is enabled in filters.yml
* <mark style="color:orange;">`redischat.bypassfilter.muted_channel`</mark> Allows to bypass the muted channel filter.
* <mark style="color:orange;">`redischat.bypassfilter.ignore`</mark> Skips the ignore filter. This filter doesn't send the private message if the player is ignoring the receiver because the message couldn't reach him.
* <mark style="color:orange;">`redischat.bypassfilter.tag`</mark> Skips the tag filter. This filter parses all minimessage tags and placeholders.
* <mark style="color:orange;">`redischat.bypassfilter.word_blacklist`</mark> Allows to bypass the word blacklist filter.
* <mark style="color:orange;">`redischat.bypassfilter.permission`</mark> Allows to bypass the permission filter.
* <mark style="color:orange;">`redischat.admin`</mark> Allows to use all admin commands[ List HERE](https://github.com/Emibergo02/RedisChat/blob/67006ef03163e46f87b581668c7f5b6641443b79/src/main/resources/plugin.yml#L162)
* <mark style="color:orange;">`redischat.default`</mark> Allows you to use default commands [List HERE](https://github.com/Emibergo02/RedisChat/blob/67006ef03163e46f87b581668c7f5b6641443b79/src/main/resources/plugin.yml#L184)
* <mark style="color:orange;">`redischat.mail.write`</mark> Allows a user to write and send mail messages within the RedisChat system.
* <mark style="color:orange;">`redischat.mail.writepublic`</mark> Permits writing public mails [#commands](unique-features/mails.md#commands "mention")
* <mark style="color:orange;">`redischat.mail`</mark> Grants permission to read mails A.K.A. open the mail GUI
* <mark style="color:orange;">`redischat.mail.delete`</mark> Allows deletion of received mail.
* <mark style="color:orange;">`redischat.mail.deletepublic`</mark> Permits deletion of public mail.
* <mark style="color:orange;">`redischat.mail.unread`</mark> Enables a user to mark a mail as unread
* <mark style="color:orange;">`redischat.ignore_whitelist`</mark> Allows the use of [ignore-whitelist.md](features/ignore-whitelist.md "mention")
* <mark style="color:orange;">`redischat.ignore_whitelist.other`</mark> Allows to toggle other players whitelist
* <mark style="color:orange;">`redischat.announcer`</mark> Allows the use of [#announcer-less-than-start-stop-greater-than-less-than-announcementname-greater-than](features/announcement-system.md#announcer-less-than-start-stop-greater-than-less-than-announcementname-greater-than "mention")
* <mark style="color:orange;">`redischat.createchannel`</mark> Allows the creation of new chat channels.
* <mark style="color:orange;">`redischat.infochannel`</mark> Permits viewing detailed information about a channel.
* <mark style="color:orange;">`redischat.changedisplayname`</mark> Allows changing a channel’s display name.
* <mark style="color:orange;">`redischat.deletechannel`</mark> Enables deletion of chat channels.
* <mark style="color:orange;">`redischat.playerchannel`</mark> Allows players to force another player's active channel [#channel-force-listen-less-than-playername-greater-than-less-than-channelname-greater-than](features/channels.md#channel-force-listen-less-than-playername-greater-than-less-than-channelname-greater-than "mention")
* <mark style="color:orange;">`redischat.hidechannel.<channelName>`</mark> Hides a channel from the GUI if the channel is displayed by default
* <mark style="color:orange;">`redischat.showchannel.<channelName>`</mark> Shows a channel in the GUI if it is hidden by default
* <mark style="color:orange;">`redischat.channel.public`</mark> Grants access to the public chat channel.
* <mark style="color:orange;">`redischat.channel.staffchat`</mark> Grants access to the staff chat channel.
* <mark style="color:orange;">`redischat.channel.<channelName>`</mark> Allows to read and write on a channel
* <mark style="color:orange;">`redischat.channel.<channelName>.read`</mark> Allows to read a channel
* <mark style="color:orange;">`redischat.channel.<channelName>.write`</mark> Allows to write on a channel
