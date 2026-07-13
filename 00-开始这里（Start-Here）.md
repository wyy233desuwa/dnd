---
id: doc-start-here
type: guide
status: active
version: 1.0.0
---

# 开始这里（Start Here）

这是一个面向**单人玩家 + 本地 Agent 主持人**的 D&D Markdown 资料库模板。它适合碎片化游玩：随时开始、随时暂停、换会话后继续，并允许 Agent 按规则读取和写入文件。

## 第一次使用

按顺序完成以下内容：

1. 填写 [[01-玩家偏好（Preferences）/游玩风格（Play-Style）]]。
2. 填写 [[01-玩家偏好（Preferences）/内容边界（Content-Boundaries）]]。
3. 在 [[07-规则（Rules）/系统版本（System-Version）]] 中选择规则版本。
4. 填写 [[03-战役（Campaign）/战役前提（Premise）]]。
5. 至少填写四份世界观文档：
   - [[04-世界观（Lore）/01-公开设定（Public-Lore）/世界总览（World-Overview）]]
   - [[04-世界观（Lore）/01-公开设定（Public-Lore）/当前地区（Current-Region）]]
   - [[04-世界观（Lore）/02-核心正史（Canon）/世界底层规则（World-Rules）]]
   - [[04-世界观（Lore）/03-主持秘密（GM-Secrets）/战役秘密（Campaign-Secrets）]]
6. 根据 [[08-模板（Templates）/玩家角色模板（Player-Character-Template）]] 创建角色文件。
7. 更新 [[05-角色（Characters）/队伍总览（Party-Overview）]]。
8. 将 [[10-系统（System）/本地Agent启动提示词（Agent-Launch-Prompt）]] 交给你的本地 Agent。
9. 让 Agent 执行一次“初始化检查”，再开始游戏。

## 每次继续游戏

Agent 固定先读取：

1. `AGENT（Agent-Protocol）.md`
2. `资料库清单（Vault-Manifest）.yaml`
3. `INDEX（Campaign-Index）.md`
4. `02-当前状态（State）/当前存档（Resume）.md`
5. 当前存档引用的角色、地点、NPC、任务和战斗文件

不要在每轮回复前读取全部会话历史和全部世界观。

## 常用口令

- **开始游戏**：读取当前存档并继续。
- **快速保存**：落盘当前状态，不结束会话。
- **暂停游戏**：完成一致性检查并写入检查点。
- **状态摘要**：只展示玩家可见的当前状态。
- **未完成事项**：展示玩家已知且尚未解决的事项。
- **回顾上次**：根据当前存档和上次会话摘要生成简短回顾。
- **检查存档**：检查引用、修订号和重复状态是否一致。

## 核心原则

- 当前状态必须写入文件，不能只存在于对话上下文。
- 历史事件日志尽量只追加，不回改。
- 玩家角色的决定只能由玩家作出。
- 主持秘密不能因为 Agent 读取到了就直接透露。
- 文件名可以改变，但实体 `id` 不应改变。
