# 🥅 Filters

### Filters are made to modify or block messages with malicious content or to apply certain RedisChat features

To disable a filter for a user set the permission <mark style="color:orange;">**`redischat.bypassfilter.filterName`**</mark>

{% code title="filters.yml" %}
```yaml
ignorePlayer:
  enabled: true
  priority: 4
  audienceWhitelist:
  - CHANNEL
  - PLAYER
  channelWhitelist:
  - public
  ignorePublicMessages: true
  sendWarnWhenIgnoring: true
```
{% endcode %}

## Priority

Filters will be applied to messages in order of priority starting from 1

## Audience Whitelist

There are 3 audiences inside RedisChat:

* CHANNEL -> Messages with a channel as receiver
* PLAYER -> Messages with a player as receiver (private messages)
* DISCORD -> Messages sent to Discord

#### If audienceWhitelist is empty the filter will be applied to all 3 the audiences

## Channel Whitelist

If the message is sent to a channel audience, the filter will work only for channels specified\
inside channelWhitelist

If channelWhitelist is empty, the filter will be applied to all channels

Remember: the "global" channel is called "public"

## Additional parameters

Every filter can have additional configuration
