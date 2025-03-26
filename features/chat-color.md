---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🎨 Chat color

**Permissions needed:**

* <mark style="color:orange;">`redischat.chatcolor`</mark> to execute /chatcolor and see the GUI\
  If you don't have this permission YOUR COLOR WILL BE RESET ON REJOIN \
  (make sure the players have this permission if they want to keep their chatcolor)\

* <mark style="color:orange;">`redischat.chatcolor.<chatcolor>`</mark> to use/see specific chat colors

### ChatColor GUI

{% code title="config.yml" %}
```yaml
# Enable or disable the chat color GUI
enableChatColorGUI: true
```
{% endcode %}

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

**The GUI layout is configurable inside** `guis.yml`!!

You need to have redischat.chatcolor

## **/chatcolor \<color>**

#### Examples

<mark style="color:orange;">`/chatcolor #FA8072`</mark> (format #RRGGBB)

<mark style="color:orange;">`/chatcolor white`</mark> (all colors available [here](https://docs.advntr.dev/minimessage/format.html#color))

**/chatcolor** will create a placeholder named `%redischat_chat_color%` containing a color component

Take a look at [custom-placeholderapi-placeholders.md](../unique-features/custom-placeholderapi-placeholders.md "mention") section to know more about RedisChat PAPI placeholders

You can put it before {message} inside formats section to color the text that follows



