# GTD

[← Back to README](README.md)

Languages: [English](#english) | [简体中文](#简体中文)

---

## English

### What it is

**GTD** status labels on **CLI sessions** help you triage work without leaving the IDE. Labels are stored in the shared catalog (`catalog.db` under panel home) and stay in sync with Desktop when both use the same panel home.

ACP chats are **not** GTD-tagged.

### Statuses

| Status | Typical meaning |
|--------|-----------------|
| `@inbox` | Captured, not yet sorted |
| `@next` | Next actions |
| `@waiting` | Blocked on someone / something else |
| `@someday` | Deferred / maybe later |
| `@reference` | Keep for lookup, not actionable |

### Main workflows

1. Open the **GTD** sidebar view (sessions grouped by status).  
2. Or set status from a session’s context menu / **set GTD status** command.  
3. **Refresh** the GTD view after bulk changes.  
4. Filter by GTD in **Search** / Session Manager when hunting a queue of work.

### With Desktop

- Desktop **Report** can propose GTD updates from weekly/monthly digests (preview → apply).  
- Labels applied on Desktop appear in the extension GTD tree after sync/refresh, and vice versa.  
- Desktop may also maintain project `todolist.md` content as part of the report GTD workflow — the extension focuses on session-level GTD in the sidebar.

### Tips

1. Use GTD on **sessions**, Notes for longer prose.  
2. Prefer few `@next` items so the view stays actionable.  
3. Hiding a session removes it from the panel; clear GTD first if you still need it elsewhere.

### Related

- [Sessions](sessions.md) · [Notes](notes.md)  
- [Desktop Report docs](https://github.com/lucacicii/agent-resume-desktop-doc) (digests → GTD)  
- [Settings & data](settings-and-data.md)

---

## 简体中文

### 是什么

**GTD** 状态标签打在 **CLI 会话**上，便于在 IDE 内分流任务。标签保存在共用目录数据库（面板数据目录下的 `catalog.db`），与 Desktop 在同一 `panel home` 时会同步。

ACP 聊天 **不会** 打 GTD 标签。

### 状态含义

| 状态 | 常见含义 |
|------|----------|
| `@inbox` | 已捕获，尚未整理 |
| `@next` | 下一步行动 |
| `@waiting` | 等待他人 / 外部条件 |
| `@someday` | 以后再说 |
| `@reference` | 参考资料，非行动项 |

### 主要流程

1. 打开 **GTD** 侧边栏（按状态分组）。  
2. 或在会话右键 / **set GTD status** 命令中设置。  
3. 批量修改后 **Refresh** GTD 视图。  
4. 在 **Search** / Session Manager 中按 GTD 筛选。

### 与 Desktop 配合

- Desktop **Report** 可从周报/月报生成 GTD 建议（预览 → 应用）。  
- Desktop 上的标签在扩展刷新后可见，反之亦然。  
- Desktop 还可能维护项目 `todolist.md`；扩展侧重点是侧边栏会话级 GTD。

### 提示

1. 会话用 GTD，长文用 Notes。  
2. `@next` 不宜过多，便于行动。  
3. 隐藏会话会从面板移除；若仍需在他处使用，可先理清 GTD。

### 相关文档

- [会话 Sessions](sessions.md) · [Notes](notes.md)  
- [Desktop Report 文档](https://github.com/lucacicii/agent-resume-desktop-doc)（报告 → GTD）  
- [设置与数据](settings-and-data.md)
