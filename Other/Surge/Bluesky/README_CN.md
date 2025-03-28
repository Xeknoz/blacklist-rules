# 📜 其它规则 - Bluesky

**🌐 语言选择：[English](README.md)  | 简体中文**

## ⭐ 仅适用于 Surge 内核

🔗 **如果您需要使用 `Bluesky.list` 文件，您可以通过如下超链接进行获取：**

- 原始链接：[查看或下载](https://raw.githubusercontent.com/Xeknoz/blacklist-rules/main/Other/Surge/Bluesky/Bluesky.list)
- 镜像链接（可能会有24小时的延迟）：[查看或下载](https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Other/Surge/Bluesky/Bluesky.list)

### ℹ️ 注意事项

**为了能够正常调用 `Bluesky`.list 文件，`behavior` 属性应为 `DOMAIN-SET` 字项。**

### 📝 示例代码

```list
[Rule]
# > bluesky
DOMAIN-SET, https://fastly.jsdelivr.net/gh/Xeknoz/blacklist-rules@main/Other/Surge/Bluesky/Bluesky.list, Bluesky, update-interval=86400
```
