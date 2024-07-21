# 🥅 Filters

### Filters are made to modify or block messages with malicious content or to apply certain RedisChat features

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

### enabled

Used to enable or disable this specific filter

### priority

Filters will be applied to messages in order of priority starting from 1

### audienceWhitelist

There are 3 audiences inside RedisChat:

* CHANNEL -> Messages with a channel as receiver
* PLAYER -> Messages with a player as receiver (private messages)
* DISCORD -> Messages sent to Discord

#### If audienceWhitelist is empty the filter will be applied to all 3 the audiences

### channelWhitelist

If the message is sent to a channel audience, the filter will work only for channels specified\
inside channelWhitelist

If channelWhitelist is empty, the filter will be applied to all channels

Remember: the "global" channel is called "public"

## Additional parameters

Every filter can have additional configuration
