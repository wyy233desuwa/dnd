---
id: system-maintenance-backup
type: guide
status: active
agent_may_modify: false
---

# 维护与备份（Maintenance & Backup）

## 推荐做法

- 使用 Git 管理整个资料库；
- 每个场景、战斗或会话结束后提交一次；
- 定期复制 ZIP 备份到其他位置；
- 不把唯一存档只放在 Agent 的对话记录中；
- 避免同时让多个 Agent 修改同一文件。

## 推荐提交信息

```text
save: session-003 scene-end at loc-old-mine
combat: resolve combat-004 and sync resources
lore: add npc-mira and faction relationship
fix: correct hp sync after evt-20260710-0021
```

## 定期整理

每 5～10 次会话：

1. 清理 INDEX 中的失效引用；
2. 将旧内容移入归档；
3. 检查未完成事项和日历是否存在过期条目；
4. 合并重复 NPC、地点或物品；
5. 验证核心真相没有被临场内容改变；
6. 生成新的完整 ZIP 备份。
