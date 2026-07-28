# 2026 Senior SWE 面试时间线

本文将日历安排和招聘流程，与底层准备方案分开整理。

## 12 周时间线

| 周次 | 日期 | 时长 | 准备重点 | 求职 / 面试行动 |
|---|---|---:|---|---|
| **第 1 周** | 7 月 27 日–8 月 2 日 | **14h** | 准备三版简历；选出 3 个旗舰项目；测试 Coding 基线；确定目标职级 | 回复 CoreWeave；完成 Recruiter 沟通；不要立刻安排技术面 |
| **第 2 周** | 8 月 3–9 日 | **14h** | 准备项目故事的 2/10/30 分钟版本；完成 10 道 Coding 题；建立 System Design 框架 | 将 CoreWeave 技术面安排在 8 月底或 9 月初 |
| **第 3 周** | 8 月 10–16 日 | **14h** | 完成 10–12 道 Coding 题；设计 Job Scheduler 和 Workflow Engine；复习 Kubernetes/调度 | 精选并申请 5–7 个岗位；开始 Microsoft/Bloomberg/Crusoe 初筛 |
| **第 4 周** | 8 月 17–23 日 | **14h** | 提升 Coding 速度；设计 Fleet 生命周期/Control Plane；进行一次 Coding Mock 和一次 BQ Mock | 安排 2–3 场校准技术面，时间放在 8 月 24 日–9 月 11 日 |
| **第 5 周** | 8 月 24–30 日 | **14h** | 修复 Mock 暴露的短板；准备可靠性/故障设计；进行公司专项准备 | 参加第一批校准面试；技术面不超过两场 |
| **第 6 周** | 8 月 31 日–9 月 6 日 | **14h** | 复习 CoreWeave 调度/Kubernetes；第二次 Coding Mock；第二次 Design Mock | 参加 CoreWeave 技术面；累计完成 3–4 家校准公司 |
| **第 7 周** | 9 月 7–13 日 | **13h** | 定稿 A 类公司叙事；保持 Coding 手感；重复练习 3 个核心 Design | 启动 A 类第一波：CoreWeave、Stripe、TikTok、Snowflake |
| **第 8 周** | 9 月 14–20 日 | **13h** | 公司专项训练；Meta/TikTok 速度型 Coding；Stripe 正确性和运维 | 集中参加第一批 A 类公司技术面 |
| **第 9 周** | 9 月 21–27 日 | **12h** | 深挖 Google/Databricks Design；Storage、Metadata、Consistency 和故障 | 启动 A 类第二波：Google、Databricks、Meta；补充精选 NVIDIA/OpenAI 岗位 |
| **第 10 周** | 9 月 28 日–10 月 4 日 | **10h** | 只做针对性补弱；保持 Coding 和 Design 节奏 | Onsite 高峰期；最多安排 1–2 场 Onsite |
| **第 11 周** | 10 月 5–11 日 | **9h** | 团队专项准备；统一 Offer 阶段的故事口径；调研谈薪 | 完成剩余 Onsite、Team Match 和时间线同步 |
| **第 12 周** | 10 月 12–18 日 | **9h** | 最后复习薄弱点；不再展开大范围新内容 | Final、Team Match、必要时准备 Reference，并开始谈薪布局 |
|  | **总计** | **150h** |  |  |

## 招聘阶段时间线

| 日期 | 准备 / 面试占比 | 行动 |
|---|---:|---|
| **7 月 27 日–8 月 9 日** | **90% / 10%** | 准备简历、项目故事、Coding 和 Design 基线；立即与 CoreWeave Recruiter 沟通 |
| **8 月 10–23 日** | **75% / 25%** | 开始定向申请和 Recruiter/HM Screen；安排校准面试 |
| **8 月 24 日–9 月 11 日** | **55% / 45%** | 总共用 **3–4 家公司**做校准；认真对待 CoreWeave，不要把它当成可随意消耗的练手机会 |
| **9 月 14 日–10 月 9 日** | **35% / 65%** | A 类第一波主流程：CoreWeave、Stripe、TikTok 和 Snowflake |
| **9 月 28 日–10 月 30 日** | **25% / 75%** | A 类第二波主流程：Google、Databricks 和 Meta；加入高度匹配的 NVIDIA/OpenAI/Anthropic/Netflix 岗位 |
| **10 月 26 日–11 月 13 日** | 以面试和谈薪为主 | Final、Team Match、Offer 时间同步和谈薪 |
| **11 月中旬以后** | 只做精选申请 | Thanksgiving/年底前后避免开启大量进展缓慢的流程，除非岗位已确认有 HC |
| **2027 年 1–2 月** | 第二个招聘窗口 | 如有需要，等新年度预算和 HC 开放后重新启动 |

# 2026 Senior SWE 面试准备计划

本文包含准备时间分配、每周固定节奏、启动正式面试的标准，以及工作量上限。

## 150 小时准备时间分配

| 模块 | 时长 | 占比 | 交付结果 |
|---|---:|---:|---|
| Coding | **45h** | **30%** | 精选完成 60–80 道题；重复最重要的 30 道；稳定达到两道 Medium 的表现 |
| System Design | **35h** | **23%** | 完成 8 个完整 Design；其中 6 个按 45 分钟面试条件重复演练 |
| Project Deep Dive + Behavioral | **25h** | **17%** | 3 个项目分别准备 2/10/30 分钟版本；10 个可复用的 Behavioral Story |
| AI / Cloud Infrastructure 专项 | **18h** | **12%** | Kubernetes Control Loop、调度、GPU/Fleet 生命周期、Reconciliation、SLO、容量和故障处理 |
| Mock Interview + 复盘 | **15h** | **10%** | 至少 2 次 Coding、2 次 System Design 和 1 次 Behavioral Mock；针对性补弱 |
| 简历、申请和公司调研 | **12h** | **8%** | 3 版简历；目标公司 Tracker；针对岗位定制申请 |
| **总计** | **150h** | **100%** | 达到 Senior 面试就绪状态 |

## 每周固定安排

### 准备为主的周：14 小时

| 星期 | 时长 | 任务 |
|---|---:|---|
| 周一 | **1.5h** | 两道 Coding 题，或一道计时 Medium 加复盘 |
| 周二 | **1.5h** | 一个 System Design 章节，或半套 Design 训练 |
| 周三 | **1.5h** | 计时 Coding 和表达练习 |
| 周四 | **1.5h** | Project Deep Dive 或 Behavioral Story |
| 周五 | **1h** | 复盘错误、处理申请和流程安排；不学重大新主题 |
| 周六 | **4h** | 完整 Coding Mock + System Design Mock，或完成一套完整 Design |
| 周日 | **3h** | 基础设施专项 + 每周复盘 + 下周优先事项 |
| **总计** | **14h** |  |

### 面试为主的周

- 两次短时 Coding 练习。
- 一次 System Design 演练。
- 一次 Project/BQ 演练。
- 一个公司专项准备时段。
- 每周用 30 分钟检查一次求职 Pipeline。

## 启动面试的标准

| 领域 | 达到校准面试标准 | 达到 A 类公司启动标准 |
|---|---|---|
| Coding | 能在 30–35 分钟内解出一道 Medium，并清楚讲解 | 至少连续 5 次计时训练中有 4 次能在 45–50 分钟内完成两道面试级 Medium |
| System Design | 在适当提示下完成一套结构清晰的 45 分钟 Design | 能独立覆盖需求、估算、API/Data Model、架构、扩展性、Consistency 和故障；至少重复练习 6 套 Design |
| Project Deep Dive | 一个旗舰项目可以连贯讲 10 分钟 | 三个项目均准备好 2/10/30 分钟版本，包含指标、决策、替代方案、失败经历和个人贡献 |
| Behavioral | 草拟 6 个 Story | 练熟 10 个 Story：Leadership、Conflict、Failure、Ambiguity、Influence、Mentoring、Incident 和 Delivery |
| 基础设施专项 | 能解释 Kubernetes Reconciliation 和基础调度 | 能讨论 Controller 故障模式、Idempotency、Quota/Preemption、Fleet Health、Rollout、Observability、Capacity 和 GPU 工作负载限制 |
| Mock Interview | 完成一次 Coding 或 Design Mock | 至少完成 2 次 Coding + 2 次 Design + 1 次 BQ Mock，并修复主要短板 |
| Pipeline | 已开始 Recruiter 沟通 | 在最重要的 A 类公司 Onsite 前，完成 2–3 场校准技术面 |

## 各阶段每周投入

| 阶段 | 每周准备时间 | 预计面试量 | 上限 |
|---|---:|---|---|
| 打基础：7 月 27 日–8 月 9 日 | **14h** | 只安排 Recruiter 沟通 | 最多 1 场实质性技术面 |
| 申请加速：8 月 10–23 日 | **14–16h** | 每周 1–2 场 Screen | 每周最多 2 场技术面 |
| 校准：8 月 24 日–9 月 11 日 | **13–16h** | 每周 2–3 场技术面 | 累计 3–4 家校准公司后停止 |
| 主流程：9 月 14 日–10 月 30 日 | **9–14h**，另加实际面试 | 每周 2–3 场技术面，或 1–2 场 Onsite | 每周绝不超过 3 场技术面或 2 场 Onsite |
| Final/谈薪：10 月 26 日–11 月 13 日 | **6–10h** | Team Match、Final、谈薪 | 不再开启大范围新准备主题 |

### 工作量限制

- 重点公司的 Onsite 之间保留 **2–3 个工作日**。
- 将 A 类公司拆成两波，不要同时启动所有流程。
- 每周预留约 **20% 的精力**，应对临时 Recruiter 请求、工作压力和恢复需求。
- 每场面试后的笔记限制在 **30 分钟**内：题目、错误、信号，以及一项改进行动。
- 不要因为一次面试失败，就触发连续几天没有结构的重新学习。
- 对优质的新发布岗位，尽量在 **7–10 天**内申请，因为具体岗位的 HC 可能早于公司整体招聘季结束。
