---
description: Send items in chat to flex muscles
---

# 🖥 Display items in chat

<figure><img src="../.gitbook/assets/redischat_showcase3.png" alt=""><figcaption><p>Click on the button in chat and a GUI will be opened for you</p></figcaption></figure>

## Tags

### \<item>

Shows the item in the main hand through a clickable GUI

### \<inv>

Shows your entire inventory (and your armor slots)

### \<ec>

Shows your enderchest content

## Configs

Edit the clickable buttons in the[ format section](chat-formats.md)

```yaml
  inventory_format: <click:run_command:%command%>[Open the inventory of %player%]</click>
  item_format: <click:run_command:%command%>[%item_name% of %player%]</click>
  enderchest_format: <click:run_command:%command%>[Open the enderchest of %player%]</click>
```

%player% is the player name

Edit GUI titles

```yaml
inv_title: Inventory of %player%
item_title: Item of %player%
ec_title: Enderchest of %player%
```
