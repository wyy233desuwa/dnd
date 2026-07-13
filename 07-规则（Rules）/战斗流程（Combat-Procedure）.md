---
id: rules-combat-procedure
type: rules
status: active
revision: 0
agent_may_modify: false
---

# 战斗流程（Combat Procedure）

## 开始战斗

1. 确认位置、视野、惊袭和战斗目标。
2. 创建 `combat_id`，将当前战斗设为 `active`。
3. 读取所有参战实体的权威状态。
4. 掷先攻并建立顺序。
5. 记录地形、出口、危险和可交互元素。

## 每个回合

1. 宣布当前行动者与可见局面。
2. 等待玩家决定其角色行动。
3. 结算移动、动作、附赠动作、反应和资源。
4. 更新 HP、状态、集中和持续效果。
5. 追加关键事件。
6. 检查战斗结束条件。

## 结束战斗

严格执行 [[02-当前状态（State）/当前战斗（Current-Combat）]] 中的结束清单。
