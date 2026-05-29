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
