---
id: session-events-example
type: append-only-log
session_id: session-000
status: active
revision: 0
agent_may_modify: true
---

# 事件日志（Events）

## 事件格式

```markdown
### evt-YYYYMMDD-NNNN

- 游戏时间：
- 现实时间：
- 场景 ID：
- 类型：narrative / check / combat / state / correction
- 参与实体：
- 发生内容：
- 骰点或规则依据：
- 状态变更：
- 更新文件：
```

---

<!-- 从这里开始只追加事件，不覆盖旧事件。需要纠错时追加 correction 事件。 -->
