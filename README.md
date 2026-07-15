# Agent Resume Panel — 用户文档

Languages: [简体中文](#简体中文) | [English](#english)

在 VS Code / VSCodium 侧边栏中统一浏览、搜索、恢复 **Codex / Claude Code / Antigravity / Grok Build / OpenCode / Pi / Alma** 历史会话；支持 **ACP Chat** 实时对话、**GTD** 状态管理、**多条 Markdown 笔记**（磁盘文件 + Catalog 索引），以及摘要 / 重命名 / Handoff 等辅助能力。

> **无云端 · 纯本机存储（Local-first）**  
> 本插件不提供、也不依赖自有云端服务。会话索引、笔记、ACP 聊天等面板数据均为纯本机存储。  
> 默认目录：**`~/.agent-resume-panel`**（可用 `agentResume.panelHome` 修改）。  
> （可选）LLM Assist 仅在你自行配置第三方 API 时才会访问该 API。

---

## 简体中文

### 功能一览

| 能力 | 说明 |
|------|------|
| **Sessions** | 按 Recent / Favorites / Projects 浏览 CLI 历史，点击恢复 |
| **ACP Chats** | 基于 [ACP](https://agentclientprotocol.com) 的编辑器旁聊天（Codex / Claude / Grok / OpenCode / Pi） |
| **GTD** | 为 CLI 会话打 `@inbox` / `@next` / `@waiting` / `@someday` / `@reference` 标签 |
| **Notes** | 每个 session / project **多条** Markdown 笔记；真实 `.md` + 图片 assets |
| **搜索 / Manager** | 按项目、GTD、provider 筛选；批量浏览与 **Export** 备份 |
| **LLM Assist** | Summarize、Auto Rename、Handoff Brief（需配置 OpenAI 兼容 API） |
| **恢复目标** | 集成终端、官方插件面板（Claude / 实验性 Codex）、Ghostty、Codex App、Alma 客户端 |

### 快速开始

1. 在活动栏打开 **Agent Resume**。
2. 使用四个视图：**Sessions**、**ACP Chats**、**GTD**、**Notes**。
3. 在 **Sessions** 中点击会话即可恢复。
4. 列表过期时：各视图标题栏 **Refresh**，或命令 **Agent Resume: Refresh**。

### 数据目录

```text
~/.agent-resume-panel/
  catalog.db    # 会话索引、GTD、笔记索引
  notes/        # Markdown 笔记正文与 assets
  acp/          # ACP 聊天数据
```

CLI 对话全文仍在各 Agent 本机原生存储（如 `~/.codex`、`~/.claude`）。换机请自行拷贝/同步上述目录。

### 设置

通过 **Sessions** 齿轮或命令 **Agent Resume: Open Settings** 打开设置 Webview。  
就地升级扩展后若菜单异常，执行 **Developer: Reload Window**（侧栏 Refresh 不能替代）。

### 反馈与支持

- **Bug 报告 / 功能建议**：[GitHub Issues](https://github.com/lucacicii/agent-resume-panel-doc/issues)
- 提交 Issue 时请勿粘贴 API Key、完整对话 transcript 或敏感路径。

### 相关链接

- [源代码仓库](https://github.com/lucacicii/agent-resume-panel)
- [Desktop App 用户文档](https://github.com/lucacicii/agent-resume-desktop-doc)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=lucacicii.agent-resume-panel-v2)

---

## English

### Overview

Browse, search, and resume CLI agent sessions from a VS Code sidebar — with ACP Chat, GTD tagging, multi-note Markdown files, LLM Assist, and Handoff.

### Features

| Feature | Description |
|---------|-------------|
| **Sessions** | Recent / Favorites / Projects; click to resume |
| **ACP Chats** | In-editor chat via [ACP](https://agentclientprotocol.com) |
| **GTD** | `@inbox` / `@next` / `@waiting` / `@someday` / `@reference` on CLI sessions |
| **Notes** | Multiple Markdown notes per session or project (disk + catalog index) |
| **Search / Manager** | Filter, bulk browse, **Export** backup |
| **LLM Assist** | Summarize, Auto Rename, Handoff Brief (optional OpenAI-compatible API) |
| **Resume targets** | Integrated terminal, Claude/Codex panels, Ghostty, Codex App, Alma |

### Quick start

1. Open **Agent Resume** in the activity bar.
2. Use **Sessions**, **ACP Chats**, **GTD**, and **Notes** views.
3. Click a session in **Sessions** to resume.
4. Use **Refresh** in each view title bar when lists are stale.

### Data storage

All panel data is stored locally under `~/.agent-resume-panel` by default. Full transcripts remain in each agent's native home directory.

### Settings

Open via the **Sessions** gear or **Agent Resume: Open Settings**. After an in-place upgrade, run **Developer: Reload Window** if menus look wrong.

### Feedback & support

- **Bugs / feature requests**: [GitHub Issues](https://github.com/lucacicii/agent-resume-panel-doc/issues)
- Do not paste API keys, full transcripts, or sensitive paths in issues.

### Related links

- [Source repository](https://github.com/lucacicii/agent-resume-panel)
- [Desktop App documentation](https://github.com/lucacicii/agent-resume-desktop-doc)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=lucacicii.agent-resume-panel-v2)