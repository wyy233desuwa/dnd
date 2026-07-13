---
id: system-metadata-schema
type: specification
status: canonical
version: 1.0.0
agent_may_modify: false
---

# 元数据规范（Metadata Schema）

## 通用字段

| 字段 | 含义 | 说明 |
|---|---|---|
| `id` | 稳定唯一标识 | 创建后不修改 |
| `type` | 文档/实体类型 | 使用英文小写短语 |
| `status` | 当前状态 | 依类型定义 |
| `revision` | 修订号 | 每次成功修改加 1 |
| `updated_at` | 最后更新时间 | ISO 8601，带时区 |
| `last_event_id` | 最近导致变化的事件 | 保持跨文件事务一致 |
| `visibility` | 信息可见性 | `public / mixed / gm` |
| `agent_may_modify` | Agent 修改权限 | `true / false / partial` |

## 状态建议

- 通用：`draft / active / inactive / archived`
- 任务：`available / active / completed / failed / abandoned`
- 战斗：`inactive / active / resolved`
- 会话：`active / paused / completed`
- 线索：`undiscovered / available / discovered / misunderstood / invalidated`

## 时间格式

- 现实时间：`2026-07-10T21:35:00+08:00`
- 游戏时间：可使用世界内纪年，但应在游戏日历中定义。
