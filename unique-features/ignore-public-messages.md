---
description: Ignore annoying players even on public channel
---

# 🚫 Ignore public messages

This feature is connected to [ignore-private-messages.md](../features/ignore-private-messages.md "mention")\
To ignore a player you'll need to execute `/ignore <playername>`

First of all you'll need to enable those 2 parameters inside config.yml

<pre class="language-yaml" data-title="config.yml"><code class="lang-yaml"><strong># Do not send public messages to players who are ignoring the sender.
</strong>ignorePublicMessages: true
# Publicly Ignored Player Notification
sendWarnWhenIgnoring: true
</code></pre>

#### Configuration Parameters Explanation

* **ignorePublicMessages**: When set to `true`, it enables the feature
* **sendWarnWhenIgnoring**: When set to `true`, a notification will be sent to the player indicating that they have been ignored on public chat\
  This serves as a warning message to the player about their status\
  By default the warning message, when clicked, shows ignored players

### This is the graphical interface

<div align="left">

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p><strong>Player POV</strong></p></figcaption></figure>

</div>
