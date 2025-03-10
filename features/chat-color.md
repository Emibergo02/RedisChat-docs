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

## **/chatcolor \<color>**

**Permissions needed:**\
<mark style="color:orange;">`redischat.chatcolor`</mark> to execute /chatcolor\
<mark style="color:orange;">`redischat.chatcolor.hex`</mark> to use hex colors\
<mark style="color:orange;">`redischat.chatcolor.<chatcolor>`</mark> to use specific chat colors

#### Examples

`/chatcolor #FA8072` (format #RRGGBB)

`/chatcolor white` (all colors available [here](https://docs.advntr.dev/minimessage/format.html#color))

**/chatcolor** will create a placeholder named `%redischat_chat_color%` containing a color component

Take a look at [custom-placeholderapi-placeholders.md](../unique-features/custom-placeholderapi-placeholders.md "mention") section to know more about RedisChat PAPI placeholders

You can put it before {message} inside formats section to color the text that follows

