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









-------
# 🆓 gbk_betaclan - FREE Clan System

## 📋 Description

**gbk_betaclan** is a completely **FREE** clan system for Minecraft servers. Perfect for small servers or servers starting out! Lightweight, efficient, and easy to use with a beautiful GUI interface.

---

## ✨ FREE Features

### 🏛️ Clan System
- ✅ **Create clans** with custom names
- ✅ **Delete clans** (owner only)
- ✅ **Rename clans** anytime
- ✅ **Colored tags** (up to 4 characters)
- ✅ **Transfer ownership** to another member

### 👥 Member System
- ✅ **Invite players** to your clan
- ✅ **Accept/decline invites**
- ✅ **Leave clan** (members only)
- ✅ **View all members** with heads
- ✅ **Online/offline status** display

### 🏠 Base System
- ✅ **Set clan base** location
- ✅ **Teleport to base** instantly
- ✅ **Delete base** anytime

### 🎮 GUI System
- ✅ **Interactive main menu**
- ✅ **Member list with heads**
- ✅ **Top clans ranking** with pages
- ✅ **Progress bars** for member count
- ✅ **Beautiful design** with colors

### 📊 Ranking System
- ✅ **Top clans leaderboard** by member count
- ✅ **Detailed clan information**
- ✅ **Page navigation** for many clans

### 💾 Storage
- ✅ **YAML file storage** - Easy backup
- ✅ **Auto-save** on server shutdown
- ✅ **Individual clan files**

---

## 📋 Commands (FREE)

| Command | Description |
|---------|-------------|
| `/clan` or `/clan menu` | Open GUI menu |
| `/clan create <name>` | Create a clan |
| `/clan invite <player>` | Invite a player |
| `/clan accept` | Accept an invite |
| `/clan deny` | Decline an invite |
| `/clan leave` | Leave your clan |
| `/clan info` | View clan info |
| `/clan members` | List clan members |
| `/clan setbase` | Set clan base |
| `/clan base` | Teleport to base |
| `/clan delbase` | Delete clan base |
| `/clan top` | View top clans |
| `/clan tag <tag>` | Set clan tag |
| `/clan rename <name>` | Rename clan |
| `/clan transfer <player>` | Transfer ownership |
| `/clan delete confirm` | Delete clan |
| `/clan premium` | View Premium info |
| `/clan help` | Show help |

---

## 🎯 FREE Limitations

| Feature | FREE Version |
|---------|--------------|
| **Max Members** | 10 per clan |
| **Who Can Invite** | Owner only |
| **Roles** | Owner & Member only |
| **Rewards System** | ❌ Not available |
| **Alliance System** | ❌ Not available |
| **PlaceholderAPI** | ❌ Not supported |
| **Discord Webhook** | ❌ Not integrated |
| **Kill Tracking** | ❌ Not tracked |
| **GUI Menus** | ✅ Basic menus |
| **Data Storage** | ✅ YAML |

---

## 💎 Upgrade to PREMIUM

Get **gbk_premiumclan** for exclusive features!

### Premium Features:
- 🔥 **Up to 30 members** (FREE: 10)
- 🔥 **Advanced role system** (4 roles)
- 🔥 **Daily & Weekly rewards**
- 🔥 **Alliance system** between clans
- 🔥 **Kill tracking & statistics**
- 🔥 **PlaceholderAPI support**
- 🔥 **Discord webhook integration**
- 🔥 **Full GUI management**
- 🔥 **Custom banners & colors**
- 🔥 **War/Rival system**
- 🔥 **Priority support**

### 📥 Get Premium:
**https://github.com/GabrielBk6/gbk_premiumclan**

---

## 🚀 How to Install

1. **Download** `gbk_betaclan.jar`
2. **Place** in your server's `plugins/` folder
3. **Restart** your server
4. **Done!** No additional setup required

### Requirements:
- ✅ Spigot/Paper 1.13+
- ✅ Java 8 or higher
- ✅ No other plugins required

---

## ⚙️ Configuration

### config.yml
```yaml
# Clan Settings (FREE limits)
max-members-free: 10
max-name-length: 16
max-tag-length: 4

# Messages
prefix: "&8[&bBetaClan&8]"

# Premium Link
premium-link: "https://github.com/GabrielBk6/gbk_premiumclan"
```

---

## Download [gbk_betaclan](https://github.com/GabrielBk6/gbk_premiumclan/releases)
