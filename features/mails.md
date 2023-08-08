---
description: Send permanent messages to your friends or your players
---

# 📧 Mails

{% code title="config.yml" %}
```yaml
# Enables /rmail /mail and the whole feature
enableMails: true
```
{% endcode %}

## Commands

### /rmail send playerName mailTitle (or /mail playerName mailTitle)

You can use it with `redischat.mail.write` permission.&#x20;

* After you execute this command there would be a clickable message in the chat
* That message links to a [**web editor**](https://webui.advntr.dev/) where you can modify your mail with MiniMessage format
* When you finished the editing click on the save button

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption><p>The save button</p></figcaption></figure>

* Clicking on that button will copy a command to be executed on chat/console

<figure><img src="../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption><p>Chat GUI on mail send</p></figcaption></figure>

* By clicking _Confirm_ you will send the mail to the recipient

### Public messages:

To send public messages use /rmail send \*public mailTitle

## /rmail

Executing only /rmail opens a GUI with all your mails

<figure><img src="../.gitbook/assets/bbMSOUt - Imgur.png" alt=""><figcaption><p>Mail GUI</p></figcaption></figure>

## /redischat-setitem \<item\_name>

Use this command to set the item you have in the main hand into the mail GUI selected slot

The available items are&#x20;

`backButton, forwardButton, mailItem, privateButton, publicButton`

