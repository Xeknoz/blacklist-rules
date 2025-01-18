# 📜 CommonRules Collection - Boost Series  
**🌐 Select your Language: English | [简体中文](README_CN.md)**  
## Type Ⅰ - DOMAIN ONLY  
🔗 **If you would like to use `SlowDomains_DomainOnly.yaml`, you can get it with following links:**  
- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Boost/Clash/SlowDomains_DomainOnly.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Clash/SlowDomains_DomainOnly.yaml)
### ℹ️ Note  
**To use `SlowDomains_DomainOnly.yaml`, `behavior` property should be `domain`.**  
### 📝 Example  
```yaml
rule-providers:
  blacklistrules-boost:
    {
      type: http,
      interval: 86400,
      format: yaml,
      behavior: domain,
      url: "https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Clash/SlowDomains_DomainOnly.yaml",
      path: "./ruleset/Xeknoz/slowdomains_domainonly.yaml",
    }
```
