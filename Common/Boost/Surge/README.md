# 📜 CommonRules Collection - Boost Series

**🌐 Select your Language: English | [简体中文](README_CN.md)**

## Type Ⅰ - NO GAME & DOMAIN ONLY

🔗 **If you would like to use `SlowDomains_NoGame_DomainOnly.list`, you can get it with following links:**

- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Boost/Surge/SlowDomains_NoGame_DomainOnly.list)
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Surge/SlowDomains_NoGame_DomainOnly.list)

### ℹ️ Note

**To use `SlowDomains_NoGame_DomainOnly.list`, `behavior` property should be `DOMAIN-SET`.**

### 📝 Example

```list
[Rule]
# > blacklistrules-boost_nogame
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Surge/SlowDomains_NoGame_DomainOnly.list, Proxy, update-interval=86400
```

## Type Ⅱ - GAME ONLY & DOMAIN ONLY

🔗 **If you would like to use `SlowDomains_GameOnly_DomainOnly.list`, you can get it with following links:**

- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Boost/Surge/SlowDomains_GameOnly_DomainOnly.list)
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Surge/SlowDomains_GameOnly_DomainOnly.list)

### ℹ️ Note

**To use `SlowDomains_GameOnly_DomainOnly.list`, `behavior` property should be `DOMAIN-SET`.**

### 📝 Example

```list
[Rule]
# > blacklistrules-boost_game
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Surge/SlowDomains_GameOnly_DomainOnly.list, Game Boosting, update-interval=86400
```
