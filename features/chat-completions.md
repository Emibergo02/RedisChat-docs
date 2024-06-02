# ⌨️ Chat completions

### Enable the feature

{% code title="config.yml" %}
```yaml
# Enable to complete chat suggestions with player names from RedisChat's shared player list
completeChatSuggestion: true
```
{% endcode %}

### What it does

When you're typing in chat, you can press `TAB` to complete your text with player names.

By default, the game completes with the player names present on the "sender" server.

With `completeChatSuggestion: true` the player will complete the chat with player names from all servers using RedisChat
