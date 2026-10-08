---
name: trader-jianghe-trading-system
description: |
  交易员江河（B站）公开直播与视频内容的完整交易决策体系，由 Trader_TX 转录整理，覆盖从"这段行情怎么看"到"这单该不该做""开多大仓""什么时候走""亏了怎么办"的全链路。当用户需要一套可执行的交易决策流程、风控规则或资金管理方法时使用；关键词：裸K、关键位、宽幅震荡、周期契约、以损定仓、动态离场、筹码分配、拆订单回测、连损熔断、交易系统构建。不适用于：行情预测与喊单、平台/出入金操作、法律合规判断、投资建议；方法可作决策流程参考，但不提供受监管市场的合规判断与下单执行建议。
---
<!-- BRAND:BEGIN -->
> **出处与许可**
> 原作：交易员江河（B站）　·　转录与蒸馏整理：Trader_TX
> 免费原版：https://space.bilibili.com/3707034000165448　·　许可：CC BY-NC 4.0：可自由传播，禁止商业使用与转售
<!-- BRAND:END -->
# 交易员江河 · 交易决策体系 — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 具体品种、点位、时点的行情预测与喊单（本体系只提供决策流程，不提供预测）
- 平台选择、出入金、对赌盘风控规避等操作（涉及合规与资金安全风险，不在范围内）
- 加密货币、外汇、CFD 等交易在中国大陆的法律合规判断
- 任何形式的投资建议；内容源自一位交易员在公开直播中的个人表述，不构成投资建议

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 市场看的是资金与多空力量对比，不是形态；形态只是逻辑的载体，同一逻辑可有多种形态表达。
2. 只做认知以内的机会——看不懂、有犹豫、需要问别人的，一律不做；空仓不是损失。
3. 周期是"拿什么成本换什么利润"的契约，不是方向；顺主周期即可，不存在"多周期全顺"。
4. 一笔订单只有两个出口：打止损，或赚钱离场；没有"没打止损就割肉"这第三种，也绝不留被套单。
5. 技术只能让你小亏小赚甚至不亏；从小做大靠的是筹码分配，且只做递减不做递增。
6. 心态问题用规则解决而非"修心"；亏损之后要做什么，必须在交易系统里写死。
7. 把感觉量化成数据：用拆订单回测从历史订单里拆出必要条件，砍掉高频亏损条件。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 判断自己适合什么模式；决定放大哪个指标；找主模式 | references/capabilities/advantage-amplification.md | references/capabilities/order-deconstruction-backtest.md、references/capabilities/position-allocation.md、references/capabilities/growth-path.md |
| 判断本金是否合适；决定留多少备用金 | references/capabilities/capital-and-reserve.md | references/capabilities/risk-budget-and-circuit-breaker.md |
| 做资金隔离；制定出金计划；规避平台风险 | references/capabilities/capital-isolation-and-withdrawal.md | references/capabilities/risk-budget-and-circuit-breaker.md、references/capabilities/capital-and-reserve.md、references/capabilities/compounding-static.md、references/capabilities/emotion-three-step.md |
| 设计复利方案；判断是否该放大仓位 | references/capabilities/compounding-static.md | references/capabilities/risk-budget-and-circuit-breaker.md、references/capabilities/capital-and-reserve.md、references/capabilities/position-allocation.md、references/capabilities/capital-isolation-and-withdrawal.md |
| 连损后怎么办；连损两次后是否还能做；判断是否该停手；设置连损限度 | references/capabilities/consecutive-loss-stop.md | references/capabilities/position-sizing-by-stop.md、references/capabilities/risk-budget-and-circuit-breaker.md、references/capabilities/trapped-order-triage.md |
| 下单前算成本；选择仓位管理方式；诊断高胜率仍亏损 | references/capabilities/controllable-cost-exchange.md | references/capabilities/position-sizing-by-stop.md |
| 从模拟盘转实盘；评估模拟盘数据可信度 | references/capabilities/demo-to-live-discount.md | references/capabilities/mentor-consistency-check.md、references/capabilities/capital-isolation-and-withdrawal.md |
| 判断何时离场；判断动能是否延续 | references/capabilities/dynamic-exit.md | references/capabilities/exit-choice-tradeoff.md、references/capabilities/stop-loss-mechanics.md、references/capabilities/order-exit-discipline.md |
| 判断行情处于哪一段；决定要不要追已经走远的趋势；判断什么算优质订单 | references/capabilities/early-trend-entry.md | references/capabilities/trend-definition.md、references/capabilities/true-false-breakout.md、references/capabilities/key-level-reading.md |
| 处理亏损后的情绪；亏损后该做什么；解决心态问题 | references/capabilities/emotion-three-step.md | references/capabilities/write-loss-action.md、references/capabilities/execution-root-cause.md、references/capabilities/rules-over-mindset.md |
| 判断进场位置属于哪个模型；区分左侧右侧；判断进场资格 | references/capabilities/entry-model-taxonomy.md | references/capabilities/key-level-reading.md、references/capabilities/trend-definition.md、references/capabilities/true-false-breakout.md、references/capabilities/range-market-playbook.md |
| 诊断管不住手；诊断执行力问题 | references/capabilities/execution-root-cause.md | references/capabilities/rules-over-mindset.md、references/capabilities/trade-system-build.md |
| 选择离场风格；解决拿不住单；定制离场方案 | references/capabilities/exit-choice-tradeoff.md | references/capabilities/advantage-amplification.md、references/capabilities/dynamic-exit.md |
| 纠正按形态名称下单；理解同一形态不同结果；把注意力从图形转向行为 | references/capabilities/forget-patterns.md | references/capabilities/kline-market-reading.md、references/capabilities/entry-model-taxonomy.md、references/capabilities/setup-gate.md、references/capabilities/necessary-conditions.md |
| 判断自己在哪个阶段；规划学习路径；新手该做什么 | references/capabilities/growth-path.md | references/capabilities/advantage-amplification.md、references/capabilities/trade-system-build.md |
| 判断订单是否健康；判断是否在包容劣质条件 | references/capabilities/healthy-order.md | references/capabilities/necessary-conditions.md、references/capabilities/no-binary-thinking.md、references/capabilities/setup-gate.md |
| 判断内部结构有没有用；大周期内部怎么做日内 | references/capabilities/internal-external-structure.md | references/capabilities/timeframe-contract.md、references/capabilities/trend-definition.md、references/capabilities/range-market-playbook.md、references/capabilities/kline-market-reading.md |
| 判断自己在投资还是投机；纠正"长期持有就是投资"的误解；判断被套不卖是否算投资 | references/capabilities/invest-vs-speculate.md | references/capabilities/growth-path.md |
| 识别关键位；区分交易位与参考位；判断关键位是否还有效 | references/capabilities/key-level-reading.md | references/capabilities/kline-market-reading.md、references/capabilities/true-false-breakout.md、references/capabilities/range-market-playbook.md、references/capabilities/necessary-conditions.md |
| 判断一段K线背后多空力量；把形态还原成参与者行为；判断方向是否仍然成立 | references/capabilities/kline-market-reading.md | references/capabilities/forget-patterns.md、references/capabilities/key-level-reading.md、references/capabilities/trend-definition.md |
| 评估交易博主；判断是否值得学；识别骗子 | references/capabilities/mentor-consistency-check.md | references/capabilities/demo-to-live-discount.md、references/capabilities/growth-path.md |
| 识别与标记N字形结构；判断突破前高是否有效；定位进攻位与防守位；决定突破式还是回踩式进场 | references/capabilities/n-structure.md | references/capabilities/trend-definition.md、references/capabilities/internal-external-structure.md、references/capabilities/key-level-reading.md |
| 判断必要条件是否齐备；组合判断方向位置节奏信号 | references/capabilities/necessary-conditions.md | references/capabilities/key-level-reading.md、references/capabilities/no-binary-thinking.md、references/capabilities/setup-gate.md |
| 拆解一笔订单的因子；纠正非黑即白判断 | references/capabilities/no-binary-thinking.md | references/capabilities/setup-gate.md、references/capabilities/necessary-conditions.md |
| 做回测；从历史订单找规律；砍掉亏损条件 | references/capabilities/order-deconstruction-backtest.md | references/capabilities/review-scope.md、references/capabilities/advantage-amplification.md、references/capabilities/trade-system-build.md |
| 判断离场方式；纠正割肉行为；纠正推保本 | references/capabilities/order-exit-discipline.md | references/capabilities/position-sizing-by-stop.md、references/capabilities/trapped-order-triage.md、references/capabilities/dynamic-exit.md |
| 分配仓位；给订单打分；判断是否加仓 | references/capabilities/position-allocation.md | references/capabilities/position-sizing-by-stop.md、references/capabilities/necessary-conditions.md、references/capabilities/healthy-order.md、references/capabilities/compounding-static.md |
| 计算仓位；确定止损位；判断止损该放哪 | references/capabilities/position-sizing-by-stop.md | references/capabilities/setup-gate.md、references/capabilities/position-allocation.md、references/capabilities/order-exit-discipline.md |
| 判断强势行情在哪进场；判断回调是否过深；使用ABC波段模型；理解二推不破的边界 | references/capabilities/pullback-continuation.md | references/capabilities/key-level-reading.md、references/capabilities/trend-definition.md、references/capabilities/range-market-playbook.md、references/capabilities/true-false-breakout.md |
| 判定是否宽幅震荡；在震荡里怎么参与；判断压缩震荡 | references/capabilities/range-market-playbook.md | references/capabilities/kline-market-reading.md、references/capabilities/key-level-reading.md、references/capabilities/trend-definition.md、references/capabilities/two-way-playbook.md |
| 复盘；判断亏损要不要复盘；统计交易结果 | references/capabilities/review-scope.md | references/capabilities/order-deconstruction-backtest.md、references/capabilities/emotion-three-step.md |
| 设定单笔风险；设定当日熔断；判断账户该放多少钱 | references/capabilities/risk-budget-and-circuit-breaker.md | references/capabilities/position-sizing-by-stop.md、references/capabilities/order-exit-discipline.md、references/capabilities/consecutive-loss-stop.md、references/capabilities/capital-isolation-and-withdrawal.md |
| 设定止盈位置；判断能否提前离场；理解高胜率为何不赚钱 | references/capabilities/rr-floor-one-to-one.md | references/capabilities/controllable-cost-exchange.md、references/capabilities/dynamic-exit.md、references/capabilities/exit-choice-tradeoff.md、references/capabilities/order-deconstruction-backtest.md |
| 解决自控力问题；判断是否该靠心态；建立规则约束 | references/capabilities/rules-over-mindset.md | references/capabilities/execution-root-cause.md、references/capabilities/emotion-three-step.md、references/capabilities/no-binary-thinking.md、references/capabilities/consecutive-loss-stop.md |
| 做剥头皮短线；判断品种平台是否适合；看动能变化决定进出；管理剥头皮的仓位与情绪 | references/capabilities/scalping-playbook.md | references/capabilities/two-way-playbook.md、references/capabilities/position-sizing-by-stop.md |
| 自检交易动机；判断是否过手瘾；判断是否假想稳定 | references/capabilities/self-check-overtrading.md | references/capabilities/trade-system-build.md、references/capabilities/review-scope.md、references/capabilities/advantage-amplification.md |
| 判断这单该不该做；判断自己是不是在硬做；评估下单资格 | references/capabilities/setup-gate.md | references/capabilities/no-binary-thinking.md、references/capabilities/healthy-order.md、references/capabilities/necessary-conditions.md |
| 判断今天能不能做；数据行情怎么处理；作息安排 | references/capabilities/state-and-event-guard.md | references/capabilities/setup-gate.md、references/capabilities/risk-budget-and-circuit-breaker.md |
| 决定何时推止损；止损给多大；处理浮盈回吐 | references/capabilities/stop-loss-mechanics.md | references/capabilities/position-sizing-by-stop.md、references/capabilities/dynamic-exit.md、references/capabilities/order-exit-discipline.md |
| 判断行情强弱；判断节奏；动能与结构冲突时怎么选 | references/capabilities/strength-and-momentum.md | references/capabilities/trend-definition.md、references/capabilities/dynamic-exit.md、references/capabilities/entry-model-taxonomy.md、references/capabilities/range-market-playbook.md |
| 配置主次周期；判断周期是否错配；判断是否顺势 | references/capabilities/timeframe-contract.md | references/capabilities/kline-market-reading.md、references/capabilities/internal-external-structure.md、references/capabilities/key-level-reading.md |
| 构建交易系统；判断系统是否完整；判断何时该做单 | references/capabilities/trade-system-build.md | references/capabilities/setup-gate.md、references/capabilities/entry-model-taxonomy.md、references/capabilities/order-deconstruction-backtest.md |
| 处理被套单；判断是否该扛；判断解套行为 | references/capabilities/trapped-order-triage.md | references/capabilities/position-sizing-by-stop.md、references/capabilities/order-exit-discipline.md、references/capabilities/consecutive-loss-stop.md |
| 判断当前趋势方向；判断方向是否改变；判断结构是否延续 | references/capabilities/trend-definition.md | references/capabilities/kline-market-reading.md、references/capabilities/timeframe-contract.md、references/capabilities/range-market-playbook.md、references/capabilities/strength-and-momentum.md |
| 判断突破是真是假；决定是否追单；判断二次突破 | references/capabilities/true-false-breakout.md | references/capabilities/key-level-reading.md、references/capabilities/range-market-playbook.md、references/capabilities/entry-model-taxonomy.md、references/capabilities/trend-definition.md |
| 做交易预案；纠正预测行为；不提前埋伏 | references/capabilities/two-way-playbook.md | references/capabilities/key-level-reading.md、references/capabilities/no-binary-thinking.md、references/capabilities/setup-gate.md |
| 写交易系统规则；亏损后动作规则化 | references/capabilities/write-loss-action.md | references/capabilities/trade-system-build.md、references/capabilities/emotion-three-step.md、references/capabilities/consecutive-loss-stop.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 用户要求预测方向/点位/时点时——停止，只交付预案与判定流程
- 用户要求带单、喊单、代下单或共享账号时——停止并提示该类行为在中国境内违法
- 用户描述的品种/平台在中国大陆不受法律保护且要求具体操作步骤时——停止，只作风险提示
- 关键输入缺失（如逻辑否认点、账户净值、单笔风险额度）且用户拒绝提供时——停止，不静默猜值

<!-- BRANDFOOT:BEGIN -->
---
*原作：交易员江河（B站）　·　转录与蒸馏整理：Trader_TX　·　免费原版：https://space.bilibili.com/3707034000165448　·　CC BY-NC 4.0：可自由传播，禁止商业使用与转售*
<!-- BRANDFOOT:END -->
