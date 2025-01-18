# 📜 CommonRules Collection - Unlock Series  
**🌐 Select your Language: English | [简体中文](README_CN.md)**  
## Type Ⅰ - NO GAME & DOMAIN ONLY  
🔗 **If you would like to use `BlockedDomains_NoGame_DomainOnly.yaml`, you can get it with following links:**  
- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Unlock/Clash/BlockedDomains_NoGame_DomainOnly.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Clash/BlockedDomains_NoGame_DomainOnly.yaml)  
### ℹ️ Note  
**To use `BlockedDomains_NoGame_DomainOnly.yaml`, `behavior` property should be `domain`.**  
### 📝 Example  
```yaml
rule-providers:
  blacklistrules-unlock_nogame:
    {
      type: http,
      interval: 86400,
      format: yaml,
      behavior: domain,
      url: "https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Clash/BlockedDomains_NoGame_DomainOnly.yaml",
      path: "./ruleset/Xeknoz/blockeddomains_nogame_domainonly.yaml",
    }
```  
## Type Ⅱ - GAME ONLY & DOMAIN ONLY  
🔗 **If you would like to use `BlockedGames_DomainOnly.yaml`, you can get it with following links:**  
- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Unlock/Clash/BlockedGames_DomainOnly.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Clash/BlockedGames_DomainOnly.yaml)  
### ℹ️ Note  
**To use `BlockedGames_DomainOnly.yaml`, `behavior` property should be `domain`.**  
### 📝 Example  
```yaml
rule-providers:
  blacklistrules-unlock_game:
    {
      type: http,
      interval: 86400,
      format: yaml,
      behavior: domain,
      url: "https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Clash/BlockedGames_DomainOnly.yaml",
      path: "./ruleset/Xeknoz/blockedgames_domainonly.yaml",
    }
```
