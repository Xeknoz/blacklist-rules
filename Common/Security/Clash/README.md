# 📜 CommonRules Collection - Security Series  
**🌐 Select your Language: English | [简体中文](README_CN.md)**  
## Type Ⅰ - DOMAIN ONLY  
🔗 **If you would like to use `AnonymityService_DomainOnly.yaml`, you can get it with following links:**  
- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Security/Clash/AnonymityService_DomainOnly.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Security/Clash/AnonymityService_DomainOnly.yaml)
### ℹ️ Note  
**To use `AnonymityService_DomainOnly.yaml`, `behavior` property should be `domain`.**  
### 📝 Example  
```yaml
rule-providers:
  blacklistrules-security_domain:
    {
      type: http,
      interval: 86400,
      format: yaml,
      behavior: domain,
      url: "https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Clash/AnonymityService_DomainOnly.yaml",
      path: "./ruleset/Xeknoz/anonymityservice_domainonly.yaml",
    }
```  
## Type Ⅱ - PROCESS NAME ONLY  
🔗 **If you would like to use `AnonymityService_ProcessNameOnly.yaml`, you can get it with following links:**  
- Original: [View or Download](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Security/Clash/AnonymityService_ProcessNameOnly.yaml)  
- CDN(maybe 24-hour-delaying sync): [View or Download](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Security/Clash/AnonymityService_ProcessNameOnly.yaml)  
### ℹ️ Note  
**To use `AnonymityService_ProcessNameOnly.yaml`, `behavior` property should be `classical`.**  
### 📝 Example  
```yaml
rule-providers:
  blacklistrules-security_process:
    {
      type: http,
      interval: 86400,
      format: yaml,
      behavior: classical,
      url: "https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Clash/AnonymityService_ProcessNameOnly.yaml",
      path: "./ruleset/Xeknoz/anonymityservice_processnameonly.yaml",
    }
```
