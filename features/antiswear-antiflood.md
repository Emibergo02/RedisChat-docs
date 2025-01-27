---
description: Filter words
---

# 🤬 ANTISWEAR/ANTIFLOOD

Censor bad words in chat replacing them with asterisk

## Configs

regex\_blacklist

```yaml
regex_blacklist:
- (?i)whatever
- (?i)you
- (?i)want
- (?i)Napoli
- (?i)Naples
- (?i)Nap0l1
- (?i)N4poli
```

[https://regexr.com/](https://regexr.com/) - This could be useful. Select PCRE as Regex Engine (top right of the page)

### Rate limit or cooldown

{% code title="config.yml" %}
```yaml
# Here you can set the number of messages that a player can send without being rate limited
rate_limit: 1
# Here you can set the time in seconds that a player can send the number of messages specified in rate_limit
rate_limit_time_seconds: 2
```
{% endcode %}

