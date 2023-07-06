# 🎓 Advanced use-case

Since RedisChat doesn't rely on the proxy (but behave like it is), the plugin have a lot of applications:

Multi-proxy - use redischat to sync chats through different proxy servers. Ex. proxy 1 has spigot1 server and proxy2 has spigot2 server. You can sync those 2 spigot server simply by setting the same redis server address/uri

Multiple multi-spigot servers - You have a skyblock with 200 spigot instances and a survival with 4 instances. You can syncronize skyblock server's chats by setting the same cluster id (todo) and the same with survival instances

Single spigot - the simpler setup is to use it on a single instance. Remember that the plugin doesn't work without a Redis server for structural reasons&#x20;
