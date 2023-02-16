# 📩 Installation

### Requirements:

A Redis-server installed and ready to use [(Click here for a guide on how to install quickly redis)](https://github.com/Emibergo02/RedisEconomy/wiki/Install-redis)

Spigot/Paper server at least 1.16.x

PlaceholderAPI installed

### Step 1: Download jar from SpigotMC and put it into your server's plugins folder

### Step 2: Start/restart the server to load config.yml

### Step 3: Edit  `redisUri` field in config.yml with this formatting:

```yaml
redis[s]://username:password@hostname:port/database?param=value&param2=value
```

The default one is:

```yaml
redis://localhost:6379/0?timeout=1s&clientName=RedisChat
```

### Step 4: Restart the server to apply



Repeat for every instance that will share chat with this one
