# 📜 BlacklistRules Collection  
**🌐 Select your Language: English | [简体中文](README_CN.md)**  
## Type Ⅰ - DOMAIN ONLY  
🔗 **If you would like to use `BlacklistRules_DomainOnly.yaml`, you can get it with following links:**  
- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Clash/BlacklistRules_DomainOnly.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Clash/BlacklistRules_DomainOnly.yaml)
### ℹ️ Note  
**To use `BlacklistRules_DomainOnly.yaml`, `behavior` property should be `domain`.**  
### 📝 Example  
```yaml
rule-providers:
  blacklistrules:
    {
      type: http,
      interval: 86400,
      format: yaml,
      behavior: domain,
      url: "https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Clash/BlacklistRules_DomainOnly.yaml",
      path: "./ruleset/Xeknoz/blacklistrules_domainonly.yaml",
    }
```
## Type Ⅱ - CLASSICAL  
🔗 **If you would like to use `BlacklistRules.yaml`, you can get it with following links:**  
- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Clash/BlacklistRules.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Clash/BlacklistRules.yaml)  
### ℹ️ Note  
**To use `BlacklistRules.yaml`, `behavior` property should be `classical`.**  
### 📝 Example  
```yaml
rule-providers:
  blacklistrules:
    {
      type: http,
      interval: 86400,
      format: yaml,
      behavior: classical,
      url: "https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Clash/BlacklistRules.yaml",
      path: "./ruleset/Xeknoz/blacklistrules.yaml",
    }
```
