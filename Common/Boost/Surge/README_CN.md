# 📜 通用规则合集 - 加速系列

**🌐 语言选择：[English](README.md)  | 简体中文**

## 类型 Ⅰ - 排除游戏且仅域名

🔗 **如果您需要使用 `SlowDomains_NoGame_DomainOnly.list` 文件，您可以通过如下超链接进行获取：**

- 原始链接：[查看或下载](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Boost/Surge/SlowDomains_NoGame_DomainOnly.list)
- 镜像链接（可能会有24小时的延迟）：[查看或下载](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Surge/SlowDomains_NoGame_DomainOnly.list)

### ℹ️ 注意事项

**为了能够正常调用 `SlowDomains_NoGame_DomainOnly.list` 文件，`behavior` 属性应为 `DOMAIN-SET` 字项。**

### 📝 示例代码

```list
[Rule]
# > blacklistrules-boost_nogame
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Surge/SlowDomains_NoGame_DomainOnly.list, Proxy, update-interval=86400
```

## 类型 Ⅱ - 仅游戏且仅域名

🔗 **如果您需要使用 `SlowDomains_GameOnly_DomainOnly.list` 文件，您可以通过如下超链接进行获取：**

- 原始链接：[查看或下载](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Boost/Surge/SlowDomains_GameOnly_DomainOnly.list)
- 镜像链接（可能会有24小时的延迟）：[查看或下载](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Surge/SlowDomains_GameOnly_DomainOnly.list)

### ℹ️ 注意事项

**为了能够正常调用 `SlowDomains_GameOnly_DomainOnly.list` 文件，`behavior` 属性应为 `DOMAIN-SET` 字项。**

### 📝 示例代码

```list
[Rule]
# > blacklistrules-boost_game
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Boost/Surge/SlowDomains_GameOnly_DomainOnly.list, Game Boosting, update-interval=86400
```
