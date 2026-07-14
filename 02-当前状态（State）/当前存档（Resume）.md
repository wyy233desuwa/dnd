---
id: state-resume
type: state
status: active
save_id: save-0002
revision: 89
updated_at: 2026-07-13T20:29:10+08:00
last_event_id: evt-20260713-0213
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

- 当前地点：废弃采石场地下，主平台下方排水廊首个左转弯前
- 游戏内日期：王国历742年，收获月第13天，晚上
- 游戏内时间：约20:29
- 当前光照：老德雷克在纵队最后持打开的遮光提灯；灯光覆盖队伍、积水地面和前方左转弯，弯角后仍为黑暗
- 当前场景：艾伦决定继续追击，但改用安全纵队。托宾担任前卫，艾伦第二，玛拉第三，德雷克殿后负责提灯与追踪
- 当前模式：combat-20260713-005处于`active`；第22轮司钥官已行动，当前轮到艾伦
- 艾伦：3/14 HP、AC18，无异常状态；位于梯底前方约10尺、托宾后方5尺；本轮移动、动作与附赠动作全部可用；标枪2支、神圣感知1/2、调谐钥匙完好
- 托宾：10/11 HP、AC12，持短剑；位于前方约15尺、左转弯前约5尺，担任前卫保护
- 玛拉：10/11 HP、AC12，持短弓、10箭与短剑；位于艾伦后方5尺，等待出现直线射界
- 老德雷克：10/11 HP、AC12，持短刀与提灯；位于玛拉后方5尺，负责照明与追踪
- 德雷克追踪：感知（生存）1d20(18)+3=21，确认司钥官没有折返或进入前段侧沟；靴痕、扰动淤泥和红色粉末均继续越过左弯
- 司钥官：第22轮再次疾走，据估计领先艾伦约100尺并已抵达或进入地下河连接段；远处传来铁格栅震响，水流轰鸣正在掩盖她的脚步和器材声
- 凯尔·丹恩：留在远处核心操作台旁，重伤、清醒、未被捆绑；没有追赶
- 核心：已接地、隔离并解除耦合；蓝色刻度归零、电弧熄灭、下层封库关闭

## 最近发生

1. 艾伦审问凯尔并获知司钥官、停机顺序、旁路及地下河撤退路线
2. 艾伦安全完成核心紧急停机，封库保持关闭
3. 司钥官向服务梯与排水廊撤退；艾伦追击时滑降失败，HP降至3/14
4. 艾伦停下等待支援，玛拉、托宾与德雷克在梯底会合
5. 司钥官连续疾走，将领先扩大到约80尺
6. 艾伦指定托宾—艾伦—玛拉—德雷克的排水廊纵队
7. 托宾推进到首个左弯前，艾伦和玛拉依次跟进；德雷克追踪总值21，确认目标仍沿主排水廊前进
8. 第22轮司钥官继续疾走，领先约100尺并接近地下河连接段

## 正在等待玩家

第22轮轮到艾伦。队伍已经形成安全纵队，托宾距离左转弯约5尺。可以继续按当前队形谨慎推进，也可以命令全队疾走以尝试缩短距离；疾走会降低德雷克持续检查踪迹与前方危险的能力。

## 未结算内容

- 待掷骰：无
- 待选择：按当前队形谨慎推进，或改为全队疾走
- 待同步文件：无

## 活跃引用（Active References）

- 角色：pc-alen → [[05-角色（Characters）/艾伦·褐石（Alen-Brownstone）]]
- NPC：
  - npc-captive-hunter → [[03-战役（Campaign）/01-NPC（NPCs）/老德雷克（Old-Drake）]]
  - npc-hunter-mara → [[03-战役（Campaign）/01-NPC（NPCs）/玛拉（Mara）]]
  - npc-hunter-tobin → [[03-战役（Campaign）/01-NPC（NPCs）/托宾（Tobin）]]
  - npc-keykeeper → [[03-战役（Campaign）/01-NPC（NPCs）/司钥官（Keykeeper）]]
- 地点：loc-old-quarry → [[03-战役（Campaign）/03-地点（Locations）/废弃采石场（Old-Quarry）]]
- 当前战斗：[[02-当前状态（State）/当前战斗（Current-Combat）]]（第22轮艾伦行动中）
- 当前事件续卷：[[06-会话记录（Sessions）/session-001/事件日志续卷-02（Events-Continuation-02）]]
- 任务：quest-investigate-monsters、quest-missing-hunters、quest-anchor-one（实体文件待建立）

## 恢复说明

- 艾伦：纵队第二，3/14 HP、AC18；第22轮当前行动者，全部行动可用
- 托宾：前卫，左转弯前约5尺，10/11 HP
- 玛拉：艾伦后方5尺，10/11 HP，短弓10箭
- 德雷克：殿后持灯，10/11 HP；追踪总值21
- 司钥官：领先约100尺，地下河连接段附近，不在视线内
- 凯尔：远处核心操作台旁重伤倒地，未捆绑
- 核心：紧急停机稳定，封库关闭
- 当前关键：安全队形能维持追踪与防伏击，但正在继续失去距离
