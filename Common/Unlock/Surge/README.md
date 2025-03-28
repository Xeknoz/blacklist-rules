# 📜 CommonRules Collection - Unlock Series

**🌐 Select your Language: English | [简体中文](README_CN.md)**

## Type Ⅰ - NO GAME & DOMAIN ONLY

🔗 **If you would like to use `BlockedDomains_NoGame_DomainOnly.list`, you can get it with following links:**

- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Unlock/Surge/BlockedDomains_NoGame_DomainOnly.list)
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Surge/BlockedDomains_NoGame_DomainOnly.list)

### ℹ️ Note

**To use `BlockedDomains_NoGame_DomainOnly.list`, `behavior` property should be `DOMAIN-SET`.**

### 📝 Example

```list
[Rule]
# > blacklistrules-unlock_nogame
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Surge/BlockedDomains_NoGame_DomainOnly.list, Proxy, update-interval=86400
```

## Type Ⅱ - GAME ONLY & DOMAIN ONLY

🔗 **If you would like to use `BlockedGames_DomainOnly.list`, you can get it with following links:**

- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Unlock/Surge/BlockedGames_DomainOnly.list)
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Surge/BlockedGames_DomainOnly.list)

### ℹ️ Note

**To use `BlockedGames_DomainOnly.list`, `behavior` property should be `DOMAIN-SET`.**

### 📝 Example

```list
[Rule]
# > blacklistrules-unlock_game
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Surge/BlockedGames_DomainOnly.list, Game Unlocking, update-interval=86400
```
