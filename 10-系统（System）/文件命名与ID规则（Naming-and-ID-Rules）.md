---
id: system-naming-id-rules
type: specification
status: canonical
version: 1.0.0
agent_may_modify: false
---

# 文件命名与 ID 规则（Naming & ID Rules）

## 文件名

采用：`中文名（English-Name）.md`

示例：

- `灰鸦酒馆（Grey-Raven-Inn）.md`
- `失踪矿工（Missing-Miners）.md`

英文部分建议只使用字母、数字和连字符，避免 `/ : * ? " < > |` 等 Windows 禁用字符。

## 稳定 ID

文件名和显示名称可以改变，但 `id` 不变：

- 玩家角色：`pc-alen`
- NPC：`npc-mira`
- 地点：`loc-grey-raven-inn`
- 任务：`quest-missing-miners`
- 势力：`faction-silver-ring`
- 物品：`item-black-key`
- 线索：`clue-ledger-entries`

## 时间与事件 ID

- 事件：`evt-YYYYMMDD-NNNN`
- 检查点：`checkpoint-YYYYMMDD-NNNN`
- 存档：`save-YYYYMMDD-NNNN`
- 会话：`session-001`

## 链接

人类导航可使用 Obsidian Wiki 链接。Agent 内部关系同时记录稳定 ID，不能只依赖文件名链接。
