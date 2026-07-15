# Agent Resume Panel — User Documentation

Languages: [English](#english) | [简体中文](#简体中文)

Browse, search, and resume **Codex / Claude Code / Antigravity / Grok Build / OpenCode / Pi / Alma** CLI sessions from a VS Code / VSCodium sidebar — with **ACP Chat**, **GTD** tagging, **multi-note Markdown** files, and Summarize / Rename / Handoff assist.

> **No cloud · Local-first**  
> Session index, notes, and ACP chats are stored on your machine. Default data directory: **`~/.agent-resume-panel`** (change **Panel home** in settings).  
> Optional LLM Assist only contacts a third-party API you configure.

---

## English

### Features

| Feature | Description |
|---------|-------------|
| **Sessions** | Recent / Favorites / Projects; click to resume |
| **ACP Chats** | In-editor chat via [ACP](https://agentclientprotocol.com) (Codex / Claude / Grok / OpenCode / Pi) |
| **GTD** | `@inbox` / `@next` / `@waiting` / `@someday` / `@reference` on CLI sessions |
| **Notes** | Multiple Markdown notes per session or project, with image attachments |
| **Search / Manager** | Filter by project, GTD, provider; bulk browse and **Export** backup |
| **LLM Assist** | Summarize, Auto Rename, Handoff Brief (OpenAI-compatible API) |
| **Resume targets** | Integrated terminal, Claude/Codex panels, Ghostty, Codex App, Alma |

### Quick start

1. Open **Agent Resume** in the activity bar.
2. Use **Sessions**, **ACP Chats**, **GTD**, and **Notes** views.
3. Click a session in **Sessions** to resume.
4. Use **Refresh** in each view title bar when lists are stale.

### Data & backup

Panel data lives under **`~/.agent-resume-panel`** by default: session index, GTD labels, notes, and ACP chats. Full transcripts remain in each agent's native home directory (e.g. `~/.codex`, `~/.claude`). Back up those folders when moving machines.

Use **Session Manager → Export** for conversation backups.

### Settings

Open via the **Sessions** gear or **Agent Resume: Open Settings**. After an in-place upgrade, run **Developer: Reload Window** if menus look wrong (sidebar Refresh does not reload menu contributions).

### Feedback & support

- **Bugs / feature requests**: [GitHub Issues](https://github.com/lucacicii/agent-resume-panel-doc/issues)
- Do not paste API keys, full transcripts, or sensitive paths in issues.

### Related links

- [Desktop App documentation](https://github.com/lucacicii/agent-resume-desktop-doc)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=lucacicii.agent-resume-panel-v2)

---

## 简体中文

在 VS Code / VSCodium 侧边栏中统一浏览、搜索、恢复 **Codex / Claude Code / Antigravity / Grok Build / OpenCode / Pi / Alma** 历史会话；支持 **ACP Chat**、**GTD**、**多条 Markdown 笔记**，以及摘要 / 重命名 / Handoff 等辅助能力。

> **无云端 · 纯本机存储**  
> 数据默认目录 **`~/.agent-resume-panel`**（可在设置中修改 Panel home）。可选 LLM Assist 仅在你配置第三方 API 时使用。

### 功能一览

| 能力 | 说明 |
|------|------|
| **Sessions** | 按 Recent / Favorites / Projects 浏览 CLI 历史，点击恢复 |
| **ACP Chats** | 基于 [ACP](https://agentclientprotocol.com) 的编辑器旁聊天 |
| **GTD** | `@inbox` / `@next` / `@waiting` / `@someday` / `@reference` 标签 |
| **Notes** | 每个 session / project 可有多条 Markdown 笔记，支持图片附件 |
| **搜索 / Manager** | 按项目、GTD、provider 筛选；批量浏览与 Export 备份 |
| **LLM Assist** | Summarize、Auto Rename、Handoff Brief（需 OpenAI 兼容 API） |
| **恢复目标** | 集成终端、Claude / Codex 面板、Ghostty、Codex App、Alma |

### 快速开始

1. 在活动栏打开 **Agent Resume**。
2. 使用 **Sessions**、**ACP Chats**、**GTD**、**Notes** 四个视图。
3. 在 **Sessions** 中点击会话恢复；列表过期时点 **Refresh**。

### 数据与备份

面板数据默认在 **`~/.agent-resume-panel`**。完整对话原文仍在各 Agent 本机目录。换机请自行备份。**Session Manager → Export** 可导出对话备份。

### 设置

**Sessions** 齿轮或 **Agent Resume: Open Settings**。升级后菜单异常请执行 **Developer: Reload Window**。

### 反馈与支持

- [GitHub Issues](https://github.com/lucacicii/agent-resume-panel-doc/issues)
- 请勿粘贴 API Key、完整对话内容或敏感路径。

### 相关链接

- [Desktop App 用户文档](https://github.com/lucacicii/agent-resume-desktop-doc)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=lucacicii.agent-resume-panel-v2)