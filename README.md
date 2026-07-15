# Agent Resume Panel — 用户文档

Languages: [简体中文](#简体中文) | [English](#english)

在 VS Code / VSCodium 侧边栏中统一浏览、搜索、恢复 **Codex / Claude Code / Antigravity / Grok Build / OpenCode / Pi / Alma** 历史会话；支持 **ACP Chat** 实时对话、**GTD** 状态管理、**多条 Markdown 笔记**，以及摘要 / 重命名 / Handoff 等辅助能力。

> **无云端 · 纯本机存储（Local-first）**  
> 本插件不提供、也不依赖自有云端服务。会话索引、笔记、ACP 聊天等数据均保存在你的电脑上。  
> 默认数据目录：**`~/.agent-resume-panel`**（可在设置中修改「Panel home」）。  
> （可选）LLM Assist 仅在你自行配置第三方 API 时才会访问该 API。

---

## 简体中文

### 功能一览

| 能力 | 说明 |
|------|------|
| **Sessions** | 按 Recent / Favorites / Projects 浏览 CLI 历史，点击恢复 |
| **ACP Chats** | 基于 [ACP](https://agentclientprotocol.com) 的编辑器旁聊天（Codex / Claude / Grok / OpenCode / Pi） |
| **GTD** | 为 CLI 会话打 `@inbox` / `@next` / `@waiting` / `@someday` / `@reference` 标签 |
| **Notes** | 每个 session / project 可有多条 Markdown 笔记，支持图片附件 |
| **搜索 / Manager** | 按项目、GTD、provider 筛选；批量浏览与 **Export** 备份 |
| **LLM Assist** | Summarize、Auto Rename、Handoff Brief（需配置 OpenAI 兼容 API） |
| **恢复目标** | 集成终端、官方插件面板（Claude / 实验性 Codex）、Ghostty、Codex App、Alma 客户端 |

### 快速开始

1. 在活动栏打开 **Agent Resume**。
2. 使用四个视图：**Sessions**、**ACP Chats**、**GTD**、**Notes**。
3. 在 **Sessions** 中点击会话即可恢复。
4. 列表过期时：各视图标题栏点 **Refresh**。

### 数据与备份

面板数据默认在 **`~/.agent-resume-panel`**，主要包括：

- 会话索引与 GTD 标记
- Markdown 笔记与图片附件
- ACP 聊天记录

各 Agent 的**完整对话原文**仍保存在各自的本机目录（如 `~/.codex`、`~/.claude`）。换机时请自行备份上述文件夹。

**Export 备份**：在 **Session Manager** 中可导出选中会话的对话备份。

### 设置

通过 **Sessions** 视图齿轮图标，或命令面板 **Agent Resume: Open Settings** 打开设置。  
扩展就地升级后若菜单显示异常，在命令面板执行 **Developer: Reload Window**（侧栏 Refresh 无法刷新菜单配置）。

### 反馈与支持

- **Bug 报告 / 功能建议**：[GitHub Issues](https://github.com/lucacicii/agent-resume-panel-doc/issues)
- 提交 Issue 时请勿粘贴 API Key、完整对话内容或敏感路径。

### 相关链接

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
| **Notes** | Multiple Markdown notes per session or project, with image attachments |
| **Search / Manager** | Filter, bulk browse, **Export** backup |
| **LLM Assist** | Summarize, Auto Rename, Handoff Brief (optional OpenAI-compatible API) |
| **Resume targets** | Integrated terminal, Claude/Codex panels, Ghostty, Codex App, Alma |

### Quick start

1. Open **Agent Resume** in the activity bar.
2. Use **Sessions**, **ACP Chats**, **GTD**, and **Notes** views.
3. Click a session in **Sessions** to resume.
4. Use **Refresh** in each view title bar when lists are stale.

### Data & backup

Panel data lives under **`~/.agent-resume-panel`** by default (session index, notes, ACP chats). Full transcripts remain in each agent's native home directory. Use **Session Manager → Export** for conversation backups.

### Settings

Open via the **Sessions** gear or **Agent Resume: Open Settings**. After an in-place upgrade, run **Developer: Reload Window** if menus look wrong.

### Feedback & support

- **Bugs / feature requests**: [GitHub Issues](https://github.com/lucacicii/agent-resume-panel-doc/issues)
- Do not paste API keys, full transcripts, or sensitive paths in issues.

### Related links

- [Desktop App documentation](https://github.com/lucacicii/agent-resume-desktop-doc)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=lucacicii.agent-resume-panel-v2)