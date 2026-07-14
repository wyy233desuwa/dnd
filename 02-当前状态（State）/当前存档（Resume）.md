---
id: state-resume
type: state
status: active
save_id: save-0002
revision: 88
updated_at: 2026-07-13T20:29:00+08:00
last_event_id: evt-20260713-0212
session_id: session-001
scene_id: scene-drainage-corridor-pursuit
active_refs:
  - pc-alen
  - loc-old-quarry
  - npc-captive-hunter
  - npc-hunter-mara
  - npc-hunter-tobin
  - enemy-maintenance-guard-west
  - npc-keykeeper
  - faction-red-scale
  - quest-investigate-monsters
  - quest-missing-hunters
  - quest-anchor-one
agent_may_modify: true
---

# 当前存档（Resume）

> 这是恢复游戏的第一入口，只保存“现在发生到哪里”。完整历史以会话事件日志及其续卷为准。

## 当前现场

- 当前地点：废弃采石场地下，下层控制室主平台下方排水廊的服务梯底
- 游戏内日期：王国历742年，收获月第13天，晚上
- 游戏内时间：约20:29
- 当前光照：老德雷克已将打开的遮光提灯带到梯底，照亮排水廊入口及约30尺范围；左转弯后仍为黑暗
- 当前场景：艾伦在快速滑降受伤后选择原地等待队友。玛拉、托宾与老德雷克用两个回合赶到并依次下梯，与艾伦在排水廊入口会合
- 当前模式：combat-20260713-005处于`active`；第21轮司钥官已行动，当前轮到艾伦
- 艾伦：3/14 HP、AC18，无异常状态；位于梯底，盾牌完好，右手尚未拔出武器；本轮移动、动作与附赠动作全部可用；标枪2支、神圣感知1/2、调谐钥匙完好
- 玛拉：10/11 HP、AC12，携短弓、10箭与短剑，位于艾伦身旁
- 托宾：10/11 HP、AC12，持短剑，位于梯底入口
- 老德雷克：10/11 HP、AC12，持短刀与打开的遮光提灯，位于梯底入口
- 司钥官：连续两个回合疾走，当前据声音估计位于前方约80尺，接近排水廊与地下河相连、水声更强的区段；没有隐匿，但脚步与器材碰撞声已被水声部分掩盖
- 凯尔·丹恩：留在远处核心操作台旁，重伤、清醒、未被捆绑；艾伦标枪仍扎在其身上；等待期间没有呼喊或追赶
- 核心：已接地、隔离并解除耦合；蓝色刻度归零、电弧熄灭、下层封库关闭

## 最近发生

1. 艾伦突破维护岩廊防线并重新开启青铜栅门，队伍进入下层控制室
2. 艾伦无声制服凯尔并获知司钥官、停机顺序、旁路及地下河撤退路线
3. 艾伦察觉总值17，安全完成核心紧急停机，封库保持关闭
4. 司钥官转向服务梯撤退，艾伦放开凯尔并追至梯口
5. 第19轮司钥官疾走进入排水廊；艾伦快速滑降失败，受到6点钝击，HP降至3/14
6. 艾伦原地等待队友，放弃继续独自追击
7. 玛拉、托宾与德雷克依次疾走到达并下梯，在第20轮结束前与艾伦会合
8. 司钥官在第20与第21轮继续疾走，将距离拉开到约80尺并接近地下河连接段

## 正在等待玩家

第21轮轮到艾伦。队伍已经会合，但司钥官距离约80尺、处于困难地形与弯折通道之后。艾伦可以带队继续追击，也可以结束追逐、返回处理凯尔和停机核心。

## 未结算内容

- 待掷骰：无
- 待选择：继续带队追击司钥官，或停止追逐返回控制室
- 待同步文件：无

## 活跃引用（Active References）

- 角色：pc-alen → [[05-角色（Characters）/艾伦·褐石（Alen-Brownstone）]]
- NPC：
  - npc-captive-hunter → [[03-战役（Campaign）/01-NPC（NPCs）/老德雷克（Old-Drake）]]
  - npc-hunter-mara → [[03-战役（Campaign）/01-NPC（NPCs）/玛拉（Mara）]]
  - npc-hunter-tobin → [[03-战役（Campaign）/01-NPC（NPCs）/托宾（Tobin）]]
  - npc-keykeeper → [[03-战役（Campaign）/01-NPC（NPCs）/司钥官（Keykeeper）]]
- 地点：loc-old-quarry → [[03-战役（Campaign）/03-地点（Locations）/废弃采石场（Old-Quarry）]]
- 当前战斗：[[02-当前状态（State）/当前战斗（Current-Combat）]]（第21轮艾伦行动中）
- 当前事件续卷：[[06-会话记录（Sessions）/session-001/事件日志续卷-02（Events-Continuation-02）]]
- 任务：quest-investigate-monsters、quest-missing-hunters、quest-anchor-one（实体文件待建立）

## 恢复说明

- 艾伦：梯底，3/14 HP、AC18；第21轮当前行动者，全部行动可用
- 司钥官：前方约80尺，接近地下河连接段，未隐匿但声音部分被水声掩盖
- 玛拉：梯底，10/11 HP，短弓10箭
- 托宾：梯底，10/11 HP，持短剑
- 德雷克：梯底，10/11 HP，持打开的遮光提灯与短刀
- 凯尔：远处核心操作台旁重伤倒地，未捆绑
- 核心：紧急停机稳定，封库关闭
- 当前关键：继续追击意味着在困难地形中追赶约80尺领先的司钥官；停止追逐则可能让她携资料逃脱
