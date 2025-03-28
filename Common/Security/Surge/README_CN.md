# 📜 通用规则合集 - 安全系列

**🌐 语言选择：[English](README.md)  | 简体中文**

## 类型 Ⅰ - 仅域名

🔗 **如果您需要使用 `AnonymityService_DomainOnly.list` 文件，您可以通过如下超链接进行获取：**

- 原始链接：[查看或下载](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Security/Surge/AnonymityService_DomainOnly.list)
- 镜像链接（可能会有24小时的延迟）：[查看或下载](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Unlock/Surge/BlockedDomains_NoGame_DomainOnly.list)

### ℹ️ 注意事项

**为了能够正常调用 `AnonymityService_DomainOnly.list` 文件，`behavior` 属性应为 `DOMAIN-SET` 字项。**

### 📝 示例代码

```list
[Rule]
# > blacklistrules-security_domain
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Security/Surge/AnonymityService_DomainOnly.list, Safe Browse, update-interval=86400
```

## 类型 Ⅱ - 仅程序名

🔗 **如果您需要使用 `AnonymityService_ProcessNameOnly.list` 文件，您可以通过如下超链接进行获取：**

- 原始链接：[查看或下载](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Common/Security/Surge/AnonymityService_ProcessNameOnly.list)
- 镜像链接（可能会有24小时的延迟）：[查看或下载](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Security/Surge/AnonymityService_ProcessNameOnly.list)

### ℹ️ 注意事项

**为了能够正常调用 `AnonymityService_ProcessNameOnly.list` 文件，`behavior` 属性应为 `RULE-SET` 字项。**

### 📝 示例代码

```list
[Rule]
# > blacklistrules-security_process
RULE-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Common/Security/Surge/AnonymityService_ProcessNameOnly.list, Safe Browse, update-interval=86400
```
