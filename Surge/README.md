# 📜 BlacklistRules Collection

**🌐 Select your Language: English | [简体中文](README_CN.md)**

## ⭐ For Surge Kernel

🔗 **If you would like to use `BlacklistRules_DomainOnly.list`, you can get it with following links:**

- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Surge/BlacklistRules_DomainOnly.list)
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Surge/BlacklistRules_DomainOnly.list)

### ℹ️ Note

**To use `BlacklistRules_DomainOnly.list`, `behavior` property should be `DOMAIN-SET`.**

### 📝 Example

```list
[Rule]
# > blacklistrules
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Surge/BlockedDomains_NoGame_DomainOnly.list, Proxy, update-interval=86400
```
