---
description: Write messages to players nearby
---

# 🔖 Local "Proximity" chat

To create a local chat use

### <mark style="color:orange;">**`/channel create local 3 5 true <distance>`**</mark>

**local** would be the name of the local channel

[**3** and 5 are the rate-limit and rate-limit-seconds parameters](channels.md#channel-create-less-than-channelname-greater-than-less-than-rate-limit-greater-than-less-than-rate-l)

**true** is the filter parameter (if the chat should be filtered through the regex-blacklist list inside config.yml)

**\<distance>** is the maximum distance for a local message to reach the recipient

A distance equal to or lower than 0 would disable the proximity feature.

#### If you want to have a chat for the whole server/world set distance to the world size (like 2 million)

