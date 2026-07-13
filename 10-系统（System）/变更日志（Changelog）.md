---
id: system-changelog
type: append-only-log
status: active
revision: 0
agent_may_modify: true
---

# 变更日志（Changelog）

> 只记录资料库结构、规则或修复类变化；普通剧情变化写入会话事件日志。

## 格式

```markdown
### YYYY-MM-DD HH:mm

- 类型：create / migrate / repair / rule-change / archive
- 修改：
- 原因：
- 影响文件：
- 操作者：player / agent
```

---

### 2026-07-10 14:30

- 类型：repair
- 修改：批量同步 20+ 文件至 last_event_id evt-20260710-0055——补写会话摘要、关键骰点、未完成事项、关系到声誉、线索谜团、世界事件、一致性检查；更新 INDEX、所有 NPC/地点/角色/日历 frontmatter
- 原因：Session 001 已推进至 55 条事件，但多数状态文件停留在初始或过时状态
- 影响文件：Resume、Calendar、Open-Loops、Relationships、Consistency-Check、Summary、Key-Rolls、Combat-Log、Session-Index、Campaign-Index、NPCs-Index、Locations-Index、Character-Index、Party-Overview、Clues-and-Mysteries、World-Events、pc-alen、4 NPC 文件、4 地点文件
- 操作者：agent

### 初始版本

- 类型：create
- 修改：建立完整双语 D&D 本地 Agent 资料库模板。
- 操作者：template
