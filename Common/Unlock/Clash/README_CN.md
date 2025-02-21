# 📜 通用规则合集 - 解锁系列

**🌐 语言选择：[English](README.md)  | 简体中文**

## 类型 Ⅰ - 排除游戏且仅域名

🔗 **如果您需要使用 `BlockedDomains_NoGame_DomainOnly.yaml`文件，您可以通过如下超链接进行获取：**

- 原始链接：[查看或下载](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Unlock/Clash/BlockedDomains_NoGame_DomainOnly.yaml)
- 镜像链接（可能会有24小时的延迟）：[查看或下载](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Clash/BlockedDomains_NoGame_DomainOnly.yaml)

### ℹ️ 注意事项

**为了能够正常调用 `BlockedDomains_NoGame_DomainOnly.yaml`文件，`behavior`属性应为 `domain`字项。**

### 📝 示例代码

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

## 类型 Ⅱ - 仅游戏且仅域名

🔗 **如果您需要使用 `BlockedGames_DomainOnly.yaml`文件，您可以通过如下超链接进行获取：**

- 原始链接：[查看或下载](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Unlock/Clash/BlockedGames_DomainOnly.yaml)
- 镜像链接（可能会有24小时的延迟）：[查看或下载](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Clash/BlockedGames_DomainOnly.yaml)

### ℹ️ 注意事项

**为了能够正常调用 `BlockedGames_DomainOnly.yaml`文件，`behavior`属性应为 `domain`字项。**

### 📝 示例代码

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
