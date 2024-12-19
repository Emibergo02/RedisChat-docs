---
description: Recurrent announcements
---

# 📢 Announcement system

## Commands

### /announcer \<start/stop> \<announcementName>

You can use it with **`redischat.announcer`** permission.&#x20;

"start" - starts the clock to send the announcement defined in the config section

"stop" - stops the clock

"announcementName" - the name of the announcer to start/stop defined in the config section

## Configs

announcer (list)

<pre class="language-yaml" data-title="config.yml"><code class="lang-yaml"><strong># Announcer configurations
</strong># delay is in seconds, how many seconds between each announcement
# channelName is the channel on which the announcement will be sent
# If you want to disable an announcement, just remove it from the list, 
# Remember that in yaml [] is an empty list
announcer:
- announcementName: default
  message: '&#x3C;yellow>RedisChat&#x3C;/yellow> &#x3C;gray>»&#x3C;/gray>&#x3C;red>To EssentialsX and CMI users:
    &#x3C;aqua>&#x3C;br>disable &#x3C;gold>/msg, /reply, /broadcast, /ignore, etc&#x3C;/gold> commands
    inside CMI and EssentialsX&#x3C;br>Or RedisChat commands &#x3C;red>will &#x3C;u>not&#x3C;/u> work&#x3C;/red>!!!&#x3C;/aqua>'
  channelName: public
  delay: 5
</code></pre>

To disable announcements set announcer to "\[]" (empty list)

<pre class="language-yaml"><code class="lang-yaml"><strong># Announcer configurations
</strong># If you want to disable an announce, just remove it from the list,
# remember that in yaml [] is an empty list
announcer: []
</code></pre>
