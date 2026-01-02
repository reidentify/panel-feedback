# 更新记录

## 1.4.11 (2026-01-02)
- 版本：`package.json` 升级到 `1.4.11`，新增开发依赖 `@vscode/vsce`，同步更新 `package-lock.json`。
- Markdown 渲染：增加 HTML 转义、代码块占位恢复、表格解析与行内格式渲染，避免 XSS 并提升显示效果。
- 输入体验：输入框仅纯 Enter 发送，Ctrl/Cmd/Shift+Enter 统一为换行。
- MCP 服务端：新增统一调试日志，解析响应时记录图片解析结果与内容类型，便于问题定位。
- 设置面板：新增“Open Logs”按钮，一键打开扩展日志目录。

