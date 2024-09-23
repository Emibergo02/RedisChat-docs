---
description: Write messages to players nearby
---

# 🔖 Local "Proximity" chat

## Local public chat

With "local" we mean that the public channel will be visible and writable by the whole server

{% code title="config.yml" %}
```yaml
# Proximity chat settings
# Set to -1 to disable proximity chat (normal cross-server chat)
# Set to 0 to make it work for the whole local server
# Set to a positive number to check if a player is in the same server, same world and below the specified distance
# The number is the distance in blocks
publicProximityDistance: -1
```
{% endcode %}

Here you can set the public channel "mode"

## A second local channel

You can create a local channel unrelated to the public too

### <mark style="color:orange;">**`/channel create local 3 5 true <distance>`**</mark>

**local** would be the name of the local channel

[**3** and 5 are the rate-limit and rate-limit-seconds parameters](channels.md#channel-create-less-than-channelname-greater-than-less-than-rate-limit-greater-than-less-than-rate-l)

**true** is the filter parameter (if the chat should be filtered through the regex-blacklist list inside config.yml)

**\<distance>** is the maximum distance for a local message to reach the recipient

A distance equal to or lower than 0 would disable the proximity feature.

#### If you want to have a chat for the whole server/world set distance to the world size (like 2 million)

