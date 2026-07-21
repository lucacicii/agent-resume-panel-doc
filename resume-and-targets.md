# Resume & targets

[← Back to README](README.md)

Languages: [English](#english) | [简体中文](#简体中文)

---

## English

### What it is

Clicking a session (or choosing a resume action from the context menu) launches that agent session again through a **resume target**. Targets are **extension-side** conveniences; Desktop has its own Workbench terminal flow.

### Default resume

- Click a session in **Sessions** to resume with your configured default (terminal mode / provider-specific resume mode).  
- From the context menu you can also **copy the resume command** and run it yourself.

### Available targets

| Target | Description |
|--------|-------------|
| **Integrated terminal** | Open VS Code’s terminal and run the provider resume command |
| **Ghostty** | Launch [Ghostty](https://ghostty.org) with the resume command (path and launch mode configurable) |
| **Claude Code panel** | Resume inside the Claude Code IDE panel when available |
| **Codex IDE panel** | Resume inside the Codex IDE panel when available |
| **Codex App** | Open the standalone Codex app for that session |

Exact menu items depend on provider and your settings (e.g. Claude/Codex resume mode, Ghostty executable path).

### New sessions

From project or editor context you can start **new** sessions for Codex, Claude, Antigravity, Grok, OpenCode, Pi, or Codex App — without leaving the IDE. Editor “new session” default provider is configurable.

### Tips

1. Prefer **integrated terminal** when you want everything inside VS Code; use **Ghostty** or app/panel targets when you already work there.  
2. If a panel resume fails, fall back to terminal resume or copy the command.  
3. Terminal location (editor area vs panel) and image-hint options live under [Settings](settings-and-data.md).  
4. Desktop **Workbench** is a separate surface for multi-tab embedded terminals — see [Desktop docs](https://github.com/lucacicii/agent-resume-desktop-doc).

### Related

- [Sessions](sessions.md)  
- [ACP Chat](acp-chat.md) (live chat, not CLI history resume)  
- [Settings & data](settings-and-data.md)

---

## 简体中文

### 是什么

点击会话（或在右键菜单选择恢复操作）会通过某个 **恢复目标（resume target）** 再次启动该 Agent 会话。这些目标属于 **VS Code 扩展侧**；Desktop 另有 Workbench 终端流程。

### 默认恢复

- 在 **Sessions** 中点击会话，按配置的默认方式恢复（终端模式 / 各 Provider 的 resume mode）。  
- 也可从右键菜单 **复制恢复命令** 自行执行。

### 可用目标

| 目标 | 说明 |
|------|------|
| **集成终端** | 打开 VS Code 终端并执行 Provider 恢复命令 |
| **Ghostty** | 用 Ghostty 启动恢复命令（可配置路径与启动方式） |
| **Claude Code 面板** | 在可用时于 Claude Code IDE 面板中恢复 |
| **Codex IDE 面板** | 在可用时于 Codex IDE 面板中恢复 |
| **Codex App** | 在独立 Codex 应用中打开该会话 |

具体菜单项取决于 Provider 与设置（如 Claude/Codex resume mode、Ghostty 可执行文件路径）。

### 新建会话

可从项目或编辑器上下文新建 Codex、Claude、Antigravity、Grok、OpenCode、Pi 或 Codex App 会话。编辑器「新建会话」的默认 Provider 可配置。

### 提示

1. 希望全部留在 VS Code 内时用 **集成终端**；已有 Ghostty / App / 面板工作流时用对应目标。  
2. 面板恢复失败时，可回退到终端恢复或复制命令。  
3. 终端位置、图片提示等见 [设置](settings-and-data.md)。  
4. Desktop **Workbench** 是独立的多标签内嵌终端场景 — 见 [Desktop 文档](https://github.com/lucacicii/agent-resume-desktop-doc)。

### 相关文档

- [会话 Sessions](sessions.md)  
- [ACP Chat](acp-chat.md)（实时聊天，不是 CLI 历史恢复）  
- [设置与数据](settings-and-data.md)
