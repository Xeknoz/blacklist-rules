# 📜 黑名单规则合集

**🌐 语言选择：[English](README.md)  | 简体中文**

## 类型 Ⅰ - 适用于 Clash 内核

🔗 **如果您需要使用 `BlacklistRules_DomainOnly.yaml` 文件，您可以通过如下超链接进行获取：**

- 原始链接：[查看或下载](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Clash/BlacklistRules_DomainOnly.yaml)
- 镜像链接（可能会有24小时的延迟）：[查看或下载](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Clash/BlacklistRules_DomainOnly.yaml)

### ℹ️ 注意事项

**为了能够正常调用 `BlacklistRules_DomainOnly.yaml` 文件，`behavior` 属性应为 `domain` 字项。**

### 📝 示例代码

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


## 类型 Ⅱ - 适用于 Surge 内核

🔗 **如果您需要使用 `BlacklistRules_DomainOnly.list` 文件，您可以通过如下超链接进行获取：**

- 原始链接：[查看或下载](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Surge/BlacklistRules_DomainOnly.yaml)
- 镜像链接（可能会有24小时的延迟）：[查看或下载](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Surge/BlacklistRules_DomainOnly.yaml)

### ℹ️ 注意事项

**为了能够正常调用 `BlacklistRules_DomainOnly.list` 文件，`behavior` 属性应为 `DOMAIN-SET` 字项。**

### 📝 示例代码

```list
[Rule]
# > blacklistrules
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Surge/BlockedDomains_NoGame_DomainOnly.list, Proxy, update-interval=86400

```
