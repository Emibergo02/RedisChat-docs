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

<div align="center"><figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption><p>The send command</p></figcaption></figure></div>

### <mark style="color:orange;">`/rmail (or /mail) send <playerName/-Public> mail-title`</mark>

You can use it with <mark style="color:yellow;">`redischat.mail.write`</mark> permission\
<mark style="color:yellow;">`redischat.mail.writepublic`</mark> for public mails

* After you run this command, a clickable message will appear in the chat.
* That message links to a [**web editor**](https://webui.advntr.dev/) where you can modify your mail with MiniMessage format
* When you’re done editing, click the save button: **a command will be copied to your clipboard**

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>The save button</p></figcaption></figure>

* Then paste and execute the command in-game and choose one of the three options

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1).png" alt=""><figcaption><p>Chat GUI on mail send</p></figcaption></figure>

* By clicking _Confirm_ you will send the mail to the recipient

## <mark style="color:orange;">`/rmail`</mark>

Permission: <mark style="color:yellow;">`redischat.mail.read`</mark>

```
redischat.mail.read
```

Executing only /rmail opens a GUI with all your mails

<figure><img src="../.gitbook/assets/image (9).png" alt="" width="397"><figcaption><p>Mail window</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>Mail preview inside lore</p></figcaption></figure>

## Mail options

By right-clicking a mail you can delete it or mark it as unread

<figure><img src="../.gitbook/assets/image (11).png" alt="" width="415"><figcaption><p>Mail option preview</p></figcaption></figure>

### Mail options permissions

* `redischat.mail.delete` - With this perm you can delete your PRIVATE mails
* `redischat.mail.deletepublic` - With this perm you can delete your PUBLIC mails
* `redischat.mail.unread`- With this perm you can unread any mail

## /redischat-setitem \<item\_name>

Use this command to set the item you have in the main hand into the mail GUI selected slot

The available items are&#x20;

`backButton, forwardButton, mailItem, privateButton, publicButton`

