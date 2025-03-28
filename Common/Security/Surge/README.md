# 📜 CommonRules Collection - Unlock Series

**🌐 Select your Language: English | [简体中文](README_CN.md)**

## Type Ⅰ - DOMAIN ONLY

🔗 **If you would like to use `AnonymityService_DomainOnly.list`, you can get it with following links:**

- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Security/Surge/AnonymityService_DomainOnly.list)
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Surge/BlockedDomains_NoGame_DomainOnly.list)

### ℹ️ Note

**To use `AnonymityService_DomainOnly.list`, `behavior` property should be `DOMAIN-SET`.**

### 📝 Example

```list
[Rule]
# > blacklistrules-security_domain
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Security/Surge/AnonymityService_DomainOnly.list, Safe Browse, update-interval=86400
```

## Type Ⅱ - PROCESS NAME ONLY

🔗 **If you would like to use `AnonymityService_ProcessNameOnly.list`, you can get it with following links:**

- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Security/Surge/AnonymityService_ProcessNameOnly.list)
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Security/Surge/AnonymityService_ProcessNameOnly.list)

### ℹ️ Note

**To use `AnonymityService_ProcessNameOnly.list`, `behavior` property should be `RULE-SET`.**

### 📝 Example

```list
[Rule]
# > blacklistrules-security_process
RULE-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Security/Surge/AnonymityService_ProcessNameOnly.list, Safe Browse, update-interval=86400
```
