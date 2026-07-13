---
id: guide-archive
type: guide
status: active
---

# 归档说明（Archive Guide）

以下内容可以归档：

- 已完成且短期内不会再引用的任务；
- 永久退场的 NPC；
- 已离开的旧地区详细状态；
- 旧检查点；
- 已结束的战斗临时文件；
- 被替代但需要保留审计记录的旧设定。

归档时：

1. 不改变实体 ID；
2. 在原索引中移动到“已归档”；
3. 在实体 frontmatter 中设置 `status: archived`；
4. 不删除仍被事件日志引用的文件。
