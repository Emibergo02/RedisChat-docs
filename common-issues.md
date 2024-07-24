# Common issues

For RedisChat to work, you need to <mark style="color:red;">**`disable CMI and EssentialsX chats`**</mark> by disabling chat commands such as:

* ignore
* msg
* mail
* reply
* channel/channels
* staffchat
* mutechat
* broadcast
* broadcastraw

### Disable CMI chat formatting

To deactivate the CMI chat, the values for ModifyChatFormat and&#x20;

ClickHoverMessages **must be set to false** in `cmi/Settings/Chat.yml`

## Chat message validation failure

<figure><img src=".gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

If you get this error you probably didn't install any Anti-Encryption plugins such as\
&#x20;                                                                     \
&#x20;                                                                        \-> [**`SignedVelocity`**](https://modrinth.com/plugin/signedvelocity) <-\
