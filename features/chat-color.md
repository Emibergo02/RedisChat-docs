# 🎨 Chat color

## **/chatcolor \<color>**

You need to have the permission `redischat.chatcolorcommand` to execute it

**/chatcolor** will create a placeholder named `%redischat_chat_color%` containing a color component

Take a look at [custom-placeholderapi-placeholders.md](../unique-features/custom-placeholderapi-placeholders.md "mention") section to know more about RedisChat PAPI placeholders

You can put it before %message% inside formats section to color the text that follows

#### You'll need to have&#x20;

```yaml
enablePlaceholderGlitch: true
```

To make it work

