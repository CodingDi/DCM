# 2026 Senior SWE Interview Plan

> 定位：2026 年底 6+ YOE；目标 Senior，按 Staff 深度准备。
> 概率为基于履历匹配、目标级别、岗位供给和面试门槛的规划区间，并非公司公开录取率。Package 为市场参考值，实际随地点、团队、股价和 Offer 变化。

## 目录 / Table of Contents

1. [目标公司 / Target Companies](#1-目标公司--target-companies)
2. [150 小时时间分配](#2-150-小时时间分配)
3. [求职阶段与时间线](#3-求职阶段与时间线)
4. [12 周计划](#4-12-周计划)
5. [每周固定安排](#5-每周固定安排)
6. [公司专项准备](#6-公司专项准备)
7. [面试启动标准](#7-面试启动标准)

## 1. 目标公司 / Target Companies

### A — 主攻目标

| 公司 | Target Level | 进入面试概率 | 进 Loop 后 Offer 概率 | Package 参考 | 为什么合适 / 主要缺口 |
|---|---|---:|---:|---|---|
| **CoreWeave** | IC4 / Senior SWE II；Staff 冲刺 | **70–85%** | **25–40%** | $165–242K Base + Equity/Bonus | 最直接匹配：GPU Validation、Compute Lifecycle、Orchestration 和 Reliability；Recruiter 已主动联系。缺口是 Go、Kubernetes Controller 和 Scheduling 深度。 |
| **Stripe** | L3 / Senior SWE；L4 冲刺 | **20–35%** | **12–22%** | ~$235K Base + ~$184K Equity/年 | Distributed Infrastructure、Correctness、API 和 Operational Ownership 匹配。缺口是 Coding Bar、Linux/Resource Debugging 和金融系统严谨性。 |
| **TikTok / ByteDance** | 2-2 主目标；2-1 fallback | **30–45%** | **15–25%** | 2-2：~$300K Base + ~$91K Equity/年 | 6+ YOE 和 Architecture Ownership 足以争取 2-2。主要风险是 Coding Speed，以及能否证明独立承担 Senior Scope。 |
| **Databricks** | L5 Senior；L6 冲刺；L4 downlevel | **20–35%** | **10–20%** | Seattle：~$200K Base + ~$391K Equity/年 | Distributed Systems 和 Control Plane 高度匹配。缺口是 Storage/Database Internals、Spark/Scala/C++ 和更广泛的 Platform Adoption 证据。 |
| **Google** | L5 Senior；L6 冲刺；L4 downlevel | **25–40%** | **12–22%** | Seattle：~$214K Base + ~$165K Equity/年 | YOE、Infra Architecture 和 Cross-team Work 支持 L5。风险是算法稳定性，以及能否体现 Ambiguity 下的 L5 Leadership。 |
| **Meta** | E5 主目标；E4 downlevel | **25–40%** | **15–25%** | Seattle：~$215K Base + ~$193K Equity/年 | Architecture Ownership 和 Mentoring 支持 E5。风险是 Speed Coding，以及能否简洁说明个人 Impact。 |
| **Snowflake** | IC3 Senior；IC4 冲刺；IC2 downlevel | **25–40%** | **15–25%** | Seattle：~$251K Base + ~$229K Equity/年 | Control Plane、Metadata 和 Reliability Team 匹配度高。缺口是 Transaction、Concurrency 和 Database Internals。 |

**为什么是 A：**这些公司的 Senior Band 同时符合你的 6+ YOE 和当前 Scope；要么经历匹配度最高，要么 Package 与长期成长回报更好，值得投入主要精力。

### B — 选择性冲刺或备选

| 公司 | Target Level | 进入面试概率 | 进 Loop 后 Offer 概率 | Package 参考 | 为什么合适 / 主要缺口 |
|---|---|---:|---:|---|---|
| **NVIDIA** | Cloud/GPU Infra IC4；IC3 也合理 | **20–35%** | **12–20%** | IC4 Seattle：~$247K Base + ~$138K Equity/年 | GPU Infrastructure 直接相关，应只投 Orchestration/Fleet/Tooling 岗。缺口是 CUDA/C++、HPC 和底层 Performance 深度。 |
| **OpenAI** | L4 主目标；L3 可接受 | **8–18%** | **8–15%** | Seattle L4：~$255K Base + ~$300K Equity/年 | Compute Infrastructure 与 OCI 经历重叠明显。缺口是极强竞争、ML/HPC/Networking 和更底层的 Systems Depth。 |
| **Anthropic** | Senior SWE；Staff 只投高度匹配岗 | **5–15%** | **8–15%** | Senior：~$316K Base + ~$247K Equity/年 | Cluster Lifecycle、Kubernetes 和 Reliability 匹配。缺口是很多岗位偏 Staff+，或要求 Inference/Training Systems 深度。 |
| **Netflix** | L5 / SWE 5；L6 冲刺；L4 downlevel | **10–25%** | **10–20%** | L5：~$507K Cash | AWS 和 Distributed Systems 经历有帮助。缺口是岗位数量少、Team/Location 限制，以及很高的独立判断 Bar。 |
| **Crusoe** | L5 / Senior SWE | **25–40%** | **18–30%** | ~$210K Base + ~$75K Equity/年 | AI Cloud、Bare Metal 和 Orchestration 匹配。缺点是薪酬公开样本较少，Private Equity 风险更高。 |
| **Microsoft** | 64 主目标；65 冲刺；63 downlevel | **35–55%** | **20–35%** | Seattle 64：~$200K Base + ~$43K Equity/年 + Bonus | Azure Compute/AI Infra 对口，成功率相对友好；除非 Team/Offer 很好，否则 Package 上限低于 A 组头部公司。 |
| **Bloomberg** | Senior Software Engineer | **30–50%** | **20–35%** | ~$242K Base + ~$62K Bonus | 适合校准 Coding、Concurrency 和 Reliable Distributed Systems；AI Infra 匹配较弱，回报以现金为主。 |

**为什么是 B：**不是公司或岗位不好，而是需要更精准地选 Team。有些属于高回报冲刺，但存在 ML Systems、CUDA/HPC 等专项缺口；另一些更适合作为校准或保底。

### C — Downlevel 或低 ROI 结果

| 公司 | 可能的 Downlevel | 什么情况下仍可接受 |
|---|---|---|
| CoreWeave | IC3 / Senior SWE I | Exceptional GPU/Fleet Team、Strong Equity 和明确的 IC4 Path。 |
| TikTok | 2-1 | Team Scope 或 Compensation 明显超过正常 Band。 |
| Meta | E4 | 面试后 Downlevel，但 Package/Team 很强；初始目标仍是 E5。 |
| Google | L4 | 财务上可以接受，但初始目标仍是 L5。 |
| Databricks | L4 | Strong Equity 可以部分补偿，但应先争取 L5。 |
| Snowflake | IC2 | 高度相关的 Platform Role，且 Package 特别强。 |
| Stripe | L2 | 通常低于目标；仅在 Role Quality 特别好时考虑。 |
| Microsoft | 63 | 稳定 Fallback；初始目标仍是 64。 |
| Netflix | L4 | 仅当岗位仍提供明确 Senior Ownership 时接受。 |

**为什么是 C：**这些可以作为最终 Fallback，但不应成为最初目标。你的默认市场定位应当是 Senior。

## 2. 150 小时时间分配

| Component | 小时 | 占比 | 12 周目标 |
|---|---:|---:|---|
| Coding | **45h** | **30%** | 60–80 道 Curated Problems；重复 25–30 道核心题；为 Coding-heavy 公司提升速度 |
| System Design | **35h** | **23%** | 8 个完整 Design；6 个限时完成；至少 3 个 Infra/Control Plane Design |
| Project Deep Dive + BQ | **25h** | **17%** | 3 个项目分别准备 2/10/30 分钟版本；10 个可复用的 Senior-level Story |
| Infra Specialty | **18h** | **12%** | Kubernetes、Control Loop、Scheduling、Reconciliation、GPU/Fleet Lifecycle 和 Failure Handling |
| Mock + Review | **17h** | **11%** | 3 次 Coding、3 次 System Design 和 1 次 BQ/Project Mock；针对性修正 |
| Resume、Applications + Company Research | **10h** | **7%** | 3 版 Resume；Role Filtering；Company-specific Interview Research |
| **Total** | **150h** | **100%** | 稳定达到 Senior Interview Performance |

## 3. 求职阶段与时间线

### Phases / 阶段

| 阶段 | 每周准备时间 | 预计面试量 | 限制 |
|---|---:|---|---|
| Foundation · Jul 27–Aug 9 | **14h** | 仅 Recruiter Call | 最多 1 场实质性技术面 |
| Application Ramp · Aug 10–23 | **14–16h** | 每周 1–2 场 Screen | 每周最多 2 场 Technical Round |
| Calibration · Aug 24–Sep 13 | **13–16h** | 每周 2–3 场 Technical Round | 累计 3–4 家 Calibration Company 后停止 |
| Main Loops · Sep 14–Oct 30 | **9–14h** + Interviews | 每周 2–3 场 Technical Round，或 1–2 场 Onsite | 每周绝不超过 3 场 Technical Session 或 2 场 Onsite |
| Finals · Oct 26–Nov 13 | **6–10h** | Team Match 和 Final Round | 不再开始大范围新准备主题 |

- 重要 Onsite 之间至少留 **2–3 个工作日**。
- A 组拆成两个 Wave，不要同时启动所有公司。
- 每周预留 **20% Buffer**，处理 Recruiter 临时要求、本职工作和休息。
- 每次面试后复盘最多 **30 分钟**：记录问题、错误、信号和一个修正动作。
- 高匹配的新岗位尽量在发布后 **7–10 天内**投递。

### Timeline / 时间线

| 日期 | 准备 / 面试 | 主要动作 |
|---|---:|---|
| **Jul 27–Aug 9** | **95% / 5%** | Resume、Project Deep Dive、恢复 Coding 和建立 Design Framework；回复 CoreWeave 并完成 Recruiter Call |
| **Aug 10–23** | **80% / 20%** | 继续共用能力准备；精选投递；安排 Recruiter/HM Screen |
| **Aug 24–Sep 13** | **60% / 40%** | 用 3–4 家 B 公司做 Calibration；完成第一批 Technical Screen；CoreWeave 安排在 9 月上旬或中旬 |
| **Sep 14–Oct 4** | **45% / 55%** | A 公司过渡期：CoreWeave、Stripe、TikTok 和 Snowflake；根据 Calibration 结果补弱项 |
| **Oct 5–30** | **25% / 75%** | A 公司主战期：Databricks、Google 和 Meta；继续 Wave 1；只增加高度匹配的 OpenAI、NVIDIA、Anthropic 或 Netflix 岗位 |
| **Oct 26–Nov 13** | **10% / 90%** | Final Onsite、Team Match 和流程同步；只做 Company-specific Review |
| **11 月中旬以后** | 避免开启大量新流程 | Holiday 排期、HC 和审批延迟的概率提高 |
| **2027 年 1–2 月** | 第二窗口 | 重新启动未完成的目标，或申请新批准的 HC |

- **主要面试窗口：**2026 年 10 月 5–30 日。
- **CoreWeave 例外：**现在先完成 Recruiter/HM；准备 4–5 周后做技术面，最晚不要超过 9 月中旬。

## 4. 12 周计划

| 时间 | 每周小时 | 主要任务 | 面试安排 |
|---|---:|---|---|
| **Week 1–2** · Jul 27–Aug 9 | **14h** | Resume；3 个 Project Story；恢复 Coding；建立 System Design Framework | 回复 CoreWeave；仅安排 Recruiter/HM Call |
| **Week 3–4** · Aug 10–23 | **14h** | 提升 Coding Speed；Design Framework；Infra Basics；第一轮 Coding 和 BQ Mock | 精选投递；开始 Microsoft、Crusoe 和 Bloomberg Screen |
| **Week 5–6** · Aug 24–Sep 6 | **14h** | 重复核心题；前 4 个 Design；CoreWeave 专项；第二轮 Mock | 参加 2–3 家 B 公司 Technical Round；CoreWeave 安排在 Week 6 或 7 |
| **Week 7–8** · Sep 7–20 | **13h** | 修正 Calibration 暴露的问题；定稿 3 个 Project Deep Dive；Company-specific Prep | A Wave 1：CoreWeave、Stripe、TikTok 和 Snowflake |
| **Week 9–10** · Sep 21–Oct 4 | **11h** | 保持 Coding；Databricks/Google/Meta Design 和 BQ；完成剩余 Mock | A Wave 2：Databricks、Google 和 Meta；精选 NVIDIA/OpenAI 岗位 |
| **Week 11–12** · Oct 5–18 | **9h** | 只做公司专项 Review 和 Targeted Remediation；不再展开新内容 | 集中参加 A 公司 Onsite；每周最多 1–2 场 |
| **Total** | **150h** |  |  |

## 5. 每周固定安排

### Week 1–6：准备模式

| 日期 | 时间 | 内容 |
|---|---:|---|
| Monday | **1.5h** | 两道 Coding 题，或一道 Timed Medium 加 Review |
| Tuesday | **1.5h** | System Design Section 或 Half-design Drill |
| Wednesday | **1.5h** | Timed Coding，同时口头解释 |
| Thursday | **1.5h** | Project Deep Dive / BQ |
| Friday | **1h** | Error、Interview Report、Application 和 Logistics；不学重大新主题 |
| Saturday | **4h** | Coding Mock + System Design Mock/完整 Design |
| Sunday | **3h** | Infra Specialty + Weekly Review + 下周 Priority |
| **Total** | **14h** |  |

### Week 9–12：面试模式

| 日期 | 时间 | 内容 |
|---|---:|---|
| Monday | **1h** | Coding Maintenance |
| Tuesday | **1h** | System Design Maintenance |
| Wednesday | **1h** | 下一家公司的 Research |
| Thursday | **1h** | Project Deep Dive / BQ |
| Friday | **0.5h** | Interview Note 和 Error Classification |
| Saturday | **3h** | 针对下一场 Onsite 的 Mock |
| Sunday | **1.5h** | Infra/Company Specialty + Scheduling |
| **Total** | **9h** |  |

- Week 7–8 沿用相同结构，控制在 **12–13h/周**。
- 实际参加面试的时间另算。

## 6. 公司专项准备

| 公司 | 当前市场信号与匹配度 | 重点准备 |
|---|---|---|
| **CoreWeave** | 当前 Bellevue 岗位包括 Cluster Orchestration；Recruiter 主动联系是强信号。与 OCI GPU Validation 和 Fleet Workflow 最匹配。 | Go Concurrency；Kubernetes Controller；Reconciliation；Queue、Quota、Priority、Preemption 和 Backfilling；GPU Health/Fleet Lifecycle；OCI Deep Dive。 |
| **TikTok 2-2** | 6+ YOE 支持 2-2，但流程偏 Coding-heavy，Leveling 取决于独立 Scope。 | Graph、Heap、Sliding Window、Binary Search 和 DP；高 QPS 系统；Architecture Ownership；精炼 Impact Story。 |
| **Databricks** | Distributed Systems 匹配度高；Senior 岗位重视清晰、可扩展的 Implementation 和 Platform Depth。 | Metadata/Control Plane；Checkpointing；Consistency；Fault Tolerance；Storage/Compute Separation；Maintainable Coding；Spark Fundamentals。 |
| **Snowflake** | 与 Platform/Control Plane 岗位匹配；Coding 和 Distributed Data Systems 深度仍然重要。 | Metadata、Quota System、Transaction、Concurrency、Caching、Storage/Compute Separation 和 Distributed Execution。 |
| **Google L5** | YOE 和 Architecture 支持 L5；流程考查 Algorithm、Design、Role Knowledge 和 Leadership。 | 45 分钟完成一道 Complex Problem 及 Follow-up；通用 System Design；Capacity/Failure Analysis；Ambiguity 和跨团队 Influence。 |
| **Meta E5** | 如果个人 Impact 清晰，E5 定位合理；Coding Speed 仍是核心。 | 35–45 分钟完成两道 Medium；Graph/Tree/Heap/Interval；适用时准备 AI-assisted Code Review；Execution 和 Impact BQ。 |
| **NVIDIA** | 仅 Cloud/GPU Infra、Fleet、Orchestration 或 Tooling 岗位高度匹配。 | GPU Lifecycle；Kubernetes；Scheduler/Resource Management；Linux/C++ 基础；Benchmarking、Performance 和 Hardware/Software Debugging。 |
| **OpenAI** | Compute Infrastructure 工作覆盖 Provisioning、Scheduling、Kubernetes、Fleet Health、Reliability 和 Benchmarking，主题匹配度高。 | Compute Fleet Lifecycle；Hardware Bring-up；Scheduler/Control Plane；GPU Health；Observability；Capacity Bottleneck；Practical Concurrency/Debugging；Project Deep Dive。 |
| **Anthropic** | 相关岗位包括 ML Systems、Performance 和 Accelerator Infrastructure；很多岗位偏专项或 Senior+。 | Practical Coding；修改现有代码；Kubernetes/Cluster Lifecycle；Inference Capacity；Rollout Safety；Performance 和 Reliability。 |
| **Netflix** | Distributed Systems 和 AWS 经历相关；除 Design 外，也强调 Judgment、Ownership 和 Culture。 | 深度 Design；Failure Analysis；AWS Architecture；Simplification；独立决策；Culture Memo；Practical Coding。 |
| **Stripe** | 与 Reliable Distributed Infrastructure 和 API Correctness 匹配；常见 Practical、Multi-stage Coding。 | API Correctness；Idempotency；Critical Workflow Reliability；Production Debugging；Linux/Kubernetes/Networking；End-to-end Ownership。 |
| **Bloomberg** | 适合校准 DSA、Concurrency 和 System Reliability；具体语言深度取决于 Team。 | Graph/Cache Problem；HLD；根据 Team 准备 Java/C++/Python；Concurrency 和 Memory Model；Reliable Market Data Systems。 |
| **Microsoft 64** | Azure Compute/AI Infra 的合理 Calibration 和 Backup；Team 差异较大。 | Standard Coding；一个完整 Design；Azure/Compute Story；Collaboration 和 Customer-impact BQ。 |
| **Crusoe** | 高度相关的 AI Cloud Calibration Target，涉及 Kubernetes、Fleet 和 Infrastructure。 | Kubernetes；Go；Fleet Management；Observability；Capacity/Cost；Bare Metal 和 OCI Architecture Deep Dive。 |

## 7. 面试启动标准

达到下面的基础标准后，就可以开始用 B 组做真实 Calibration；A 组是否启动，应看表现是否稳定，而不是看“是否学满了 150 小时”。

### Coding

- 在 **45–50 分钟**内完成两道难度合适的 Medium。
- 5 次限时训练中至少 **4 次**达到标准。
- 能边写边解释思路，不是写完以后再补讲。
- 能处理 Follow-up、测试、Edge Case 和需求变化。

### System Design

- 完成 **6 次限时完整设计**。
- 至少包含 **2 个 Control Plane** 和 **1 个 GPU/Fleet/Scheduler** Design。
- 覆盖 Requirements、估算、API/Data Model 和 High-level Architecture。
- 能主动讨论 Scaling、Consistency、Failure Handling、Observability 和 Trade-off。

### Project Deep Dive

- 准备 **3 个核心项目**。
- 每个项目都有 **2 分钟、10 分钟、30 分钟**版本。
- 能讲清 Alternative、Failure、Metrics 和个人贡献。
- 能为主要 Architecture Decision 和 Trade-off 辩护。

### Behavioral Questions

- 准备 **10 个可复用 Story**。
- 覆盖 Conflict、Leadership、Failure、Ambiguity 和 Influence。
- 包含 Incident Response、Mentoring、困难取舍和 Measurable Impact。

### Mocks

- 至少完成 **3 次 Coding Mock**。
- 至少完成 **3 次 System Design Mock**。
- 至少完成 **1 次 BQ / Project Deep Dive Mock**。
- 启动 A 组前，修正 Mock 暴露出的主要问题。

### Pipeline

- 先完成 **2–3 个 Calibration Technical Round**。
- 根据真实反馈调整后续准备重点。
- 不要把价值最高的 A 公司 Onsite 当作第一套完整面试流程。
