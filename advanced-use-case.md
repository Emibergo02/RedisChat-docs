# 🎓 Advanced use-case

Since RedisChat doesn't rely on the proxy (but behaves like it is), the plugin has a lot of applications:

Multi-proxy - use RedisChat to sync chats through different proxy servers. Ex. proxy 1 has spigot1 server and proxy2 has spigot2 server. You can sync those 2 spigot servers simply by setting the same Redis server address/URI

Multiple multi-spigot servers - You have a skyblock with 200 spigot instances and a survival with 4 instances. You can synchronize skyblock server's chats by setting the same cluster-id (todo) and the same with survival instances

Single spigot - the simpler setup is to use it on a single instance. Remember that the plugin doesn't work without a Redis server for structural reasons&#x20;
