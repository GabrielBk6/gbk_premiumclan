# ⚔️ gbk_PremiumClan - Premium Clan System for Minecraft

## 🏆 Complete and Professional Clan System

**gbk_PremiumClan** is an advanced clan system for Minecraft Spigot/Paper servers, packed with innovative features that will transform your server's multiplayer experience!

---

## 📥 BUY NOW

### Purchase on official websites:

- **BuiltByBit**: [https://builtbybit.com/resources/premium-clan.106854/?preview=1](https://builtbybit.com/resources/premium-clan.106854/?preview=1)

---

## ✨ MAIN FEATURES

### 🎮 Clan System
- Create clans with **custom name and colored TAG**
- Customizable **banner colors** for each clan
- Complete **rank system**: Owner, Sub-Owner, Admin, Member
- **Member limit** system (expandable up to 20)
- **Friendly Fire** toggle option
- **Clan base/headquarters** with teleport system
- **Alliance** system between clans
- **Rival** system to track enemy clans

### 👥 Member Management
- Invite players via **private or public invitation**
- Accept/Decline invitations with **clickable messages**
- Promote/Demote members between ranks
- View member statistics (kills, online time, join date)
- **Player ranking** within the clan by performance

### 🏆 Ranking System
- **Global clan ranking** by score (kills + online time)
- **Top 3 clans** displayed with rewards
- **Individual member ranking** within the clan
- Weekly ranking reset with special rewards

### 🎁 Reward System
- **Daily rewards** with configurable cycles
- **Weekly rewards** for the #1 ranked clan
- Loop or linear cycle options
- Rewards include: items, commands, and money (Vault)
- Cooldown system with visual display

### 💰 Economy Integration (Vault)
- Clan creation cost
- Member slot expansion cost
- Money rewards for daily/weekly claims
- Full Vault economy support

### 🌍 PlaceholderAPI Support
Available placeholders:
- `%gbkpremiumclan_tag%` - Clan TAG with colors
- `%gbkpremiumclan_tag_plain%` - TAG without colors
- `%gbkpremiumclan_clan%` - Clan name
- `%gbkpremiumclan_cargo%` - Member rank
- `%gbkpremiumclan_kills%` - Member kills
- `%gbkpremiumclan_total_kills%` - Total clan kills
- `%gbkpremiumclan_membros%` - Number of members
- `%gbkpremiumclan_posicao%` - Clan ranking position
- `%gbkpremiumclan_rank1%`, `%gbkpremiumclan_rank2%`, `%gbkpremiumclan_rank3%` - Top clans
- And many more!

### 🖥️ Interactive GUI
- Complete clan management via **intuitive menus**
- Member list with detailed information
- Global ranking display
- Daily/Weekly reward menus
- Alliance and rival management
- Banner color picker
- Help/commands menu

### 📊 Statistics System
- Track **total kills** per member and clan
- Track **online time** per member and clan
- Advanced **score calculation** for ranking
- Persistent data storage (YAML files)

### 🛡️ Advanced Features
- **Teleport cooldown** for base teleportation
- **Anti-pvp** protection for allies
- **Friendly fire** control within the clan
- **Confirmation system** for important actions (leave, delete, transfer)
- **Update checker** with automatic notification
- **Discord webhook** integration for logs

---

## 📋 COMMANDS

### Portuguese Commands:
| Command | Description |
|---------|-------------|
| `/clan` | Open main menu |
| `/clan criar <nome> <tag>` | Create a new clan |
| `/clan convite <jogador>` | Invite player to clan |
| `/clan conviteall` | Public invitation to all online players |
| `/clan aceitar [id]` | Accept invitation |
| `/clan recusar` | Decline invitation |
| `/clan remover <jogador>` | Remove member from clan |
| `/clan alianca <clan>` | Send alliance request |
| `/clan desalianca <clan>` | Remove alliance |
| `/clan rival <clan>` | Add/remove rival |
| `/clan edit name <nome>` | Change clan name |
| `/clan edit tag <tag>` | Change clan tag |
| `/clan setbase` | Set clan headquarters |
| `/clan delbase` | Remove clan headquarters |
| `/clan base` | Teleport to clan base |
| `/clan deletar` | Delete clan (requires confirmation) |
| `/clan transferir <jogador>` | Transfer clan ownership |
| `/clan reload` | Reload configuration (OP only) |

### English Commands:
| Command | Description |
|---------|-------------|
| `/clan` | Open main menu |
| `/clan create <name> <tag>` | Create a new clan |
| `/clan invite <player>` | Invite player to clan |
| `/clan recruit` | Public invitation to all online players |
| `/clan accept [id]` | Accept invitation |
| `/clan deny` | Decline invitation |
| `/clan remove <player>` | Remove member from clan |
| `/clan ally <clan>` | Send alliance request |
| `/clan unally <clan>` | Remove alliance |
| `/clan rivals <clan>` | Add/remove rival |
| `/clan edit name <name>` | Change clan name |
| `/clan edit tag <tag>` | Change clan tag |
| `/clan setbase` | Set clan headquarters |
| `/clan delbase` | Remove clan headquarters |
| `/clan base` | Teleport to clan base |
| `/clan delete` | Delete clan (requires confirmation) |
| `/clan transfer <player>` | Transfer clan ownership |
| `/clan reload` | Reload configuration (OP only) |

---

## 🔧 CONFIGURATION

### config.yml
```yaml
# Language (pt/en)
language: en

# Clan creation cost
cost:
  create:
    enabled: true
    value: 100000
  expand: 15000

# Teleport settings
teleport:
  delay: 5

# Discord Webhooks
discord:
  webhooks:
    create: ""
    rewards: ""
    top1: ""
```








#
---

# 📢 gbk_betaclan - FREE Clan System

## 🎉 About BetaClan

**gbk_betaclan** is a completely **FREE** clan system for Minecraft servers. Developed to be lightweight, efficient, and easy to use - perfect for servers wanting to add a clan system at no cost!

---

## ✨ BetaClan Features

### 🏛️ Clan System
- ✅ **Create Clan** - Create your own clan with a unique name
- ✅ **Delete Clan** - Delete your clan (owner only)
- ✅ **Rename Clan** - Change your clan's name
- ✅ **Clan Tag** - Add a colored tag (up to 4 characters)
- ✅ **Transfer Ownership** - Pass the clan to another member

### 👥 Member System
- ✅ **Invite Members** - Invite players (up to 10 members)
- ✅ **Accept/Deny Invites** - Decide whether to join
- ✅ **Leave Clan** - Members can leave anytime
- ✅ **Member List** - View all members online/offline
- ✅ **Player Heads** - Visual interface with skins

### 🏠 Base System
- ✅ **Set Base** - Set your clan's base location
- ✅ **Teleport to Base** - Teleport to your clan base
- ✅ **Delete Base** - Remove your clan base

### 🎮 Graphical Interface (GUI)
- ✅ **Main Menu** - Intuitive interface with all options
- ✅ **Member List** - GUI with heads and online/offline status
- ✅ **Clan Rankings** - See the best clans on the server
- ✅ **Progress Bar** - Visualize how many members are needed

### 📊 Ranking System
- ✅ **Top Clans** - Ranking organized by member count
- ✅ **Detailed Information** - View owner, members, creation date
- ✅ **Page Navigation** - Interface with pages for many clans

### 💾 Storage
- ✅ **Data Persistence** - All data is automatically saved
- ✅ **YAML Files** - Easy editing and backup
- ✅ **Auto Reload** - Data loads on server startup

### 🎨 Style & Customization
- ✅ **Colored Messages** - Chat with colors using & (e.g., &a, &c, &6)
- ✅ **Colored Tags** - Use colors in clan tags
- ✅ **Visual Progress** - Progress bars in menus
- ✅ **Professional Design** - Beautiful and intuitive interface

---

## 📋 Available Commands

| Command | Description |
|---------|-------------|
| `/clan` or `/clan menu` | Opens the main GUI menu |
| `/clan create <name>` | Creates a new clan |
| `/clan invite <player>` | Invites a player to the clan |
| `/clan accept` | Accepts a pending invite |
| `/clan deny` | Declines a pending invite |
| `/clan leave` | Leaves your current clan |
| `/clan info` | Shows clan information |
| `/clan members` | Lists all clan members |
| `/clan setbase` | Sets the clan base at your location |
| `/clan base` | Teleports to the clan base |
| `/clan delbase` | Removes the clan base |
| `/clan top` | Shows the top clans ranking |
| `/clan tag <tag>` | Sets a clan tag (max 4 chars) |
| `/clan rename <new name>` | Renames the clan |
| `/clan transfer <player>` | Transfers clan ownership |
| `/clan delete confirm` | Permanently deletes the clan |
| `/clan premium` | Shows information about Premium version |
| `/clan help` | Shows all available commands |

---

## 🎯 FREE Version Limitations

| Feature | Limit |
|---------|-------|
| **Maximum Members** | 10 members per clan |
| **Who Can Invite** | Only clan owner |
| **Role System** | Only Owner and Member |
| **Reward System** | ❌ Not available |
| **Alliance System** | ❌ Not available |
| **PlaceholderAPI** | ❌ Not supported |
| **Discord Webhook** | ❌ Not integrated |
| **Kill Tracking** | ❌ Not tracked |

---

## 💎 Premium Version - Exclusive Features

### 🔥 Up to 30 members per clan
### 🎁 Daily & Weekly Reward System
### 🤝 Alliance System between Clans
### 👑 Advanced Roles (Sub-Owner, Admin)
### 📊 PlaceholderAPI Support
### 💬 Discord Webhook Integration
### 🎯 Kill Tracking & Statistics
### 🎨 Custom Banners & Colors
### ⚔️ War & Rival System
### 🖥️ Web Dashboard for Management
### ⭐ Priority Support

**Get the Premium Version:**
🔗 https://github.com/GabrielBk6/gbk_premiumclan

---

## 🚀 How to Get Started

1. **Place the plugin in the `plugins` folder**
2. **Restart your server**
3. **Use `/clan create <name>` to create your clan**
4. **Invite friends with `/clan invite <player>`**
5. **Have fun!**

---

## ⚙️ Configuration

`config.yml` file:
```yaml
max-members-free: 10
max-name-length: 16
max-tag-length: 4
prefix: "&8[&bBetaClan&8]"
```

---

## 📌 Requirements

- ✅ Spigot/Paper 1.13+
- ✅ Java 8 or higher
- ✅ No other plugins required

---

## 🎮 Plugin Interface

### Main Menu GUI:
```
[🔧 Clan Information] [👥 Members (5/10)] [🏠 Clan Base]
[🏆 Top Clans] [❌ Leave/Delete] [✨ Premium Upgrade]
```

### Members Menu:
- Player heads
- Online/Offline status
- Role (Owner/Member)
- Player information

### Top Clans Menu:
- Complete ranking
- Progress bars
- Detailed information
- Page navigation

---

## 📝 Usage Example

```yaml
# Creating a clan:
/clan create Warriors

# Result:
[BetaClan] Successfully created clan Warriors!
[Clan] Gabriel created a new clan: Warriors

# Inviting a player:
/clan invite John

# Result:
[BetaClan] Invite sent to John
[BetaClan] You were invited to join clan Warriors!
[BetaClan] Use /clan accept to accept or /clan deny to decline
```

---

## ❓ FAQ

**Q: How many members can I have?**  
A: The FREE version allows up to 10 members per clan.

**Q: How do I leave my clan?**  
A: Use `/clan leave` (members only; owners must transfer or delete).

**Q: Can I transfer my clan to another player?**  
A: Yes! Use `/clan transfer <player>`.

**Q: Is data saved?**  
A: Yes! All data is automatically saved to YAML files.

**Q: Does it work with PlaceholderAPI?**  
A: No in the FREE version. Premium version has full support.

**Q: How do I teleport to the base?**  
A: Set the base with `/clan setbase` and teleport with `/clan base`.

**Q: Can I change my clan name later?**  
A: Yes! Use `/clan rename <new name>` (owner only).

---

## 🏆 Why choose gbk_betaclan?

- ✅ **100% FREE** - No costs, no hidden fees
- ✅ **Easy to use** - Intuitive GUI interface
- ✅ **Lightweight & Fast** - No server lag
- ✅ **Open Source** - Transparent and trustworthy
- ✅ **Regular Updates** - Bug fixes and improvements
- ✅ **Clean Code** - Well organized and documented
- ✅ **Modern Design** - Beautiful GUI menus
- ✅ **Full Translation** - English language support

---

## 📞 Support

- **FREE Version:** Community support via GitHub Issues
- **Premium Version:** Priority support via Discord

---

## 📜 License

FREE version for non-commercial use.  
Premium version available for commercial servers.

---

## 🔗 Links

- **Premium Version:** https://github.com/GabrielBk6/gbk_premiumclan
- **Source Code:** Included in the plugin

---

**Made with ❤️ by GabrielBk**

*Support development by purchasing Premium!*

## 📂 Download [gbk_betaclan](https://github.com/GabrielBk6/gbk_premiumclan/releases)
