---
name: gaokao-math-selfstudy
description: |
  高中数学自学系统（新高考Ⅰ卷）能力入口。用户提到高中数学学习进度规划、章节学习流程、
  某章前置/门槛/验收标准、压轴题方法选择、超纲判定或公式查询时使用。先按能力路由表分发到对应能力卡或章节知识卡，不直接长篇输出。
  覆盖：8 阶段自学进度（study-plan）、单章六步学习闭环（chapter-flow）、20 章知识卡导航
  （chapters/ch00-19，前置/门槛/教材定位/真题验收/高级方法）、八大板块压轴方法库
  （method-select）、课标红线与超纲判定（boundary-check）、15 部分公式速查（formula-lookup）。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: single
  cangjie.bundle-id: gaokao-math-selfstudy
  cangjie.capability-count: 5
  cangjie.entrypoint-count: 1
  fold-in.source: 高中数学自学系统电子版.html（2026-10-02 全面迭代版）
---
# 高中数学自学系统（新高考Ⅰ卷） — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 具体真题答案与题库（素材无题库）
- 教材全文讲解（以老教材/新教材原文为准）
- 依赖图象的公式证明细节（公式以《高中数学常用公式·修订版.md》为准）

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 用老教材学懂，用新教材对标，用真题验收
2. 每章门槛自测→出口检测，过关才解锁下一章
3. 先识别题型信号，再查方法卡按步骤执行
4. 超纲结论（选学·验证用）只用于小题与验证，不上答题卡

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 规划高中数学自学进度；定位当前学习阶段；制定每周学习计划；自查学习进度 | references/capabilities/study-plan.md | references/capabilities/chapter-flow.md |
| 按统一模板学习某一章；判断一章是否学完；获取每章学习清单 | references/capabilities/chapter-flow.md | references/capabilities/study-plan.md、references/capabilities/method-select.md |
| 查某一章的前置/门槛自测/教材定位/真题验收/过关标准/高级方法清单 | chapters/ 下按章号加载（ch00-学习工程总览.md 或 ch01-集合与常用逻辑.md … ch19-统计.md） | references/capabilities/chapter-flow.md、references/overview.md |
| 选择压轴题解题方法；获取某板块方法清单；请教导数/圆锥曲线/数列等压轴方法 | references/capabilities/method-select.md | references/capabilities/boundary-check.md、references/capabilities/formula-lookup.md |
| 判断方法/结论是否超纲；确认结论能否在大题直接使用；获取超纲方法的替代做法 | references/capabilities/boundary-check.md | references/capabilities/method-select.md |
| 查询数学公式；核对公式适用条件；获取某板块公式清单 | references/capabilities/formula-lookup.md | references/capabilities/boundary-check.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 某一章（00-19）的导航信息：前置/门槛/教材定位/真题验收/过关标准/高级方法 → chapters/ 下按章号加载（ch00-学习工程总览.md，ch01-集合与常用逻辑.md，…，ch19-统计.md）
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 用户要求直接计算单题答案时，直接计算，不硬套方法卡
- 无法识别题目板块时，先询问补充信息，不静默猜
- 检测到结论可能超纲时，必须给出课标内替代方案，不直接引用超纲结论
