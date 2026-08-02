# Di's Career Manager Plan

> 定位：2026 年底 6+ YOE；目标 Senior，按 Staff 深度准备 back up strong SDE2
> 概率为基于履历匹配、目标级别、岗位供给和面试门槛的规划区间，并非公司公开录取率。Package 为市场参考值，实际随地点、团队、股价和 Offer 变化。

## 目录 / Table of Contents

1. [目标公司 / Target Companies](#1-目标公司--target-companies)
2. [技术准备工作量](#2-技术准备工作量)
3. [求职 Pipeline 时间线](#3-求职-pipeline-时间线)
4. [每周固定安排](#4-每周固定安排)
5. [公司专项准备](#5-公司专项准备)
6. [面试启动标准](#6-面试启动标准)

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

**为什么是 A：** 这些公司的 Senior Band 同时符合你的 6+ YOE 和当前 Scope；要么经历匹配度最高，要么 Package 与长期成长回报更好，值得投入主要精力。

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

**为什么是 B：** 不是公司或岗位不好，而是需要更精准地选 Team。有些属于高回报冲刺，但存在 ML Systems、CUDA/HPC 等专项缺口；另一些更适合作为校准或保底。

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

**为什么是 C：** 这些可以作为最终 Fallback，但不应成为最初目标。你的默认市场定位应当是 Senior。

## 2.High Level Plan

前 8 周高强度冲刺，第 9 周后由面试逐步替代训练
### By Week

| 时间段 | 日历预留 | 用途 | 说明 |
|---|---:|---|---|
| **Week 1–4** | **34h/周，共 136h** | Coding 第一轮；SD 基础；Project/BQ 骨架 | 周一至周四平均 3.5h、周五 5h、周六 8h、周日 7h |
| **Week 5–8** | **34h/周，共 136h** | 完成 Coding 第一轮；推进二刷；SD 完整题与 Mock；Calibration | Technical Round 使用同一时间池，不能额外叠加 |
| **Week 9–12** | **28h/周，共 112h** | Coding 二/三刷；公司专项 SD；主面试窗口 | Onsite 或 Technical Round 替换当周对应训练块 |
| **12 周核心窗口** | **384h 日历容量** | 预计形成约 **340–370h** 的实际准备 | 差额用于面试、任务超时、状态波动和复盘 |
| **Week 13–16** | **18h/周，共 72h** | 面试维护、Targeted Remediation、Finals | 不是继续扩展题库 |
| **Week 17–20** | **8–12h/周，按需** | 招聘流程延迟与 Holiday Buffer | Pipeline 活跃才维持；否则休整并准备 1 月窗口 |

### By components

| Component | 预计投入 | 目标 |
|---|---:|---|
| **Coding** | **190–205h** | 150 道题完成首轮和二刷；第三轮优先完整重写 50–75 道弱题，其余做限时复述/关键代码；若坚持 150 道全部三次完整实现，使用 Week 13–16 的维护时段补齐 |
| **System Design** | **95–110h** | 完成 Hello Interview 指定板块；10–12 个完整 Design；至少 6 个限时完成；至少 3 个 Infra/Control Plane Design |
| **Infra Specialty** | **25–30h** | Kubernetes、Control Loop、Scheduling、Reconciliation、GPU/Fleet Lifecycle 和 Failure Handling |
| **Project Deep Dive + BQ** | **25–30h** | 3 个项目分别准备 2/10/30 分钟版本；10 个可复用的 Senior-level Story |
| **Mock + Review** | **20–25h，已包含在 Coding / SD 时数中** | 至少 3 次 Coding、3 次 SD 和 1 次 BQ/Project Mock；每次只形成 1–2 个修正动作 |

- **求职运营单独统计：** Resume Tailoring、投递、Networking、查面经和 Recruiter Logistics 预留 **5h/周**，不计入技术准备时数。
- **但求职运营仍占用真实精力：** Week 1–8 的总负荷约为 **34h 技术/面试日历 + 5h 求职运营**，相当于本职工作之外的第二份工作，只适合作为阶段性冲刺。
- **正式面试单独记录结果，但共享技术时间池：** 1 小时 Technical Round 连同热身和复盘通常会替换 2–3 小时训练；半天 Onsite 替换当天或当周 5–7 小时训练。

#### Hello Interview 使用方法

- **Week 1–6：** 先读当周指定的 Core Concepts / Key Technologies / Common Patterns，再独立完成 Question Breakdown；不要先读题目答案。
- 每个新技术先回答五件事：它属于哪类组件、解决什么问题、放在架构的哪里、请求怎样经过它、失败或不用它会怎样。
- 对照答案时只记录三类差距：不认识的术语、遗漏的 Pattern、说不清的 Trade-off；不要抄写整篇标准答案。
- **Week 7 以后：** 停止顺序通读，只根据 Mock、真实面试和公司专项暴露出的缺口回查对应板块。
- 完整 Design 必须独立覆盖 Requirements、API / Data Model、High-Level Design 和至少两个 Deep Dive；只阅读答案不计为完成。

### By Timeline

本节只安排投递和面试流程；技术总时数见第 2 节，每周执行见第 4 节。

| 日期 | Pipeline 动作 | 面试容量与限制 |
|---|---|---|
| **Jul 27–Aug 23 · Week 1–4** | Resume 立即投递；建立首批 Pipeline；完成 Recruiter/HM Call | 原则上不打 A 组 Technical；高匹配 fast-track 例外 |
| **Aug 24–Sep 6 · Week 5–6** | 达到 Calibration Gate 后开始 2–3 家 B 组 Technical | 每周最多 2 场 Technical Session；面试替换训练时间 |
| **Sep 7–20 · Week 7–8** | 根据 Calibration 反馈启动 A Wave 1 | A 组 Recruiter/HM 可以提前完成；Technical 受 A Gate 限制 |
| **Sep 21–Oct 18 · Week 9–12** | 推进 A Wave 1/2 Technical 和首批 Onsite | 每周最多 3 场 Technical Session，或 1 场 Onsite + 1 场 Screen |
| **Oct 19–Nov 15 · Week 13–16** | A 组 Onsite、Final、Team Match 和 Offer 同步；Pipeline 薄时才补新流程 | 通常每周最多 1 场完整 Onsite；重要 Onsite 间隔 2–3 个工作日 |
| **Nov 16–Dec 13 · Week 17–20** | 接住慢回复、Holiday 排期和审批延迟 | 不用低质量面试填满日历；有活跃流程才专项维护 |
| **2027 年 1–2 月** | 若仍无合适 Offer，利用新 HC 启动第二窗口 | 继续使用已有题库和复盘记录，不从头准备 |

- **开始投递：Week 1。**招聘回复可能滞后，不能等到 Week 8“完全准备好”才建立 Pipeline。
- **开始 B 组技术面：目标 Week 5–6。**实际日期由第 6 节的 Calibration Gate 决定。
- **开始 A 组技术面：目标 Week 7–8。**若 Coding/SD 门槛未达到，就顺延 1–2 周，不按日历硬上。
- **主 Onsite 窗口：Week 9–16。**这比原来只押注 10 月更能容纳投递到面试之间的延迟。
- A 组拆成两个 Wave，不要同时启动所有公司；高匹配岗位尽量在发布后 **7–10 天内**投递。
- 每次面试后复盘最多 **30 分钟**；只记录问题、错误、信号和 1–2 个修正动作。

## 3. Weekly Plan

### Weekly Goal

| Week | Coding | System Design | Project |
|---|---|---|---|
| **1 · 07/27 - 08/02** | **24–28 道新题**；按 Array/String、Hash、Two Pointers 聚类 | **High-level：** Delivery Framework、API Design、Data Modeling<br>**Target：** 首次尝试 Bitly；记录知识缺口，不要求完成 Deep Dive | Resume 可投递；列出 3 个 Project Deep Dive 骨架；只安排 Recruiter Call |
| **2 · 08/03 - 08/09** | **22–26 道新题 + 8–12 道复习**；加入 Sliding Window、Stack/Queue | **High-level：** Database Indexing、Caching、Redis、PostgreSQL<br>**Target：** 完成 Bitly；隔天闭卷重讲请求链路和两个 Deep Dive | 完成第 1 个 Project 的 2/10/30 分钟版本；整理 3 个 BQ Story |
| **3 · 08/10 - 08/16** | **20–24 道新题 + 15–20 道复习**；Tree/BFS/DFS | **High-level：** Networking Essentials、Handling Large Blobs<br>**Target：** 完成 Dropbox | 第 1 次 Coding Mock；完成第 2 个 Project Deep Dive；开始精选投递和 Recruiter/HM Screen |
| **4 · 08/17 - 08/23** | **18–22 道新题 + 20–25 道复习**；Heap、Interval、Binary Search | **High-level：** CAP Theorem、Dealing with Contention<br>**Target：** 完成 Ticketmaster；重点练 Transaction、Lock 和并发冲突 | 第 1 次 SD Mock；3 个 Project Deep Dive 骨架齐全；累计 8–10 个 BQ Story |
| **5 · 08/24 - 08/30** | **15–18 道新题 + 25–30 道复习**；Graph、Topological Sort | **High-level：** Kafka、Long-Running Tasks、Multi-Step Processes<br>**Target：** 完成 Job Scheduler；重点练 Queue、Retry 和 Idempotency | Kubernetes / Control Loop 专项；达到 Calibration Gate 后开始 B 组 Technical |
| **6 · 08/31 - 09/06** | **15–18 道新题 + 25–30 道复习**；DP 基础和高频弱项 | **High-level：** Sharding、Consistent Hashing、Numbers to Know、Scaling Reads/Writes<br>**Target：** 完成 News Feed | 第 2 次 Coding Mock 和第 2 次 SD Mock；Scheduler、Retry、Idempotency 专项 |
| **7 · 09/07 - 09/13** | **10–15 道新题 + 25–35 道复习**；补齐首轮缺口 | **High-level：** ZooKeeper、Redis Coordination、Reconciliation、Contention<br>**Target：** 完成 Control Plane / Reconciliation Design | 根据 Calibration 修正；若达到 A Gate，启动 A Wave 1 |
| **8 · 09/14 - 09/20** | 完成 **150 道首轮**；二刷聚焦核心 Pattern 和 Error Log | **High-level：** Scaling Writes、Dealing with Contention；回看 Job Scheduler<br>**Target：** 完成 GPU/Fleet Scheduler Design | 第 3 次 Coding Mock、第 3 次 SD Mock 和第 1 次 BQ/Project Mock；3 个 Project Deep Dive 定稿 |
| **9 · 09/21 - 09/27** | 二刷；每天以限时重写和 Follow-up 为主 | **High-level：** Distributed Cache 或 Metrics Monitoring；回查关联 Concepts/Technologies<br>**Target：** 完成 Metadata、Quota 或 Compute Orchestration Design | A Wave 1 Technical；每场面试只提取 1–2 个修正动作 |
| **10 · 09/28 - 10/04** | 二刷接近完成；开始第三轮弱题 | **High-level：** 与下一家公司最相关的 Guided Practice<br>**Target：** 完成 45–60 分钟限时 Mock；只补暴露出的两个板块 | A Wave 2 启动；安排一次半天 Onsite Simulation |
| **11 · 10/05 - 10/11** | 第三轮弱题；只练 Error Log 和目标公司形式 | **High-level：** 下一场最相关的 Question Breakdown、Pattern 和 Technology<br>**Target：** 闭卷重做一题；不新增主题 | 主 Technical / Onsite；Project/BQ 改为公司专项版本 |
| **12 · 10/12 - 10/18** | 全量二刷完成为目标；第三轮继续 | **High-level：** Guided Practice / Question Breakdowns Review<br>**Target：** 完成最后一次通用限时 Design；复习 Bitly、Contention 和 Infra/Control Plane | Readiness Audit；停止增加通用题库和 SD 主题 |
| **13 · 10/19 - 10/25** | Maintenance：2 次限时 Coding + 弱题 | **High-level：** 下一场相关的 Breakdown、Pattern 和 Technology<br>**Target：** 完成 1 个完整 Design 或 2 个 Deep Dive Drill | A 组 Onsite；只修正下一场最高风险项 |
| **14 · 10/26 - 11/01** | Maintenance；不追数量 | **High-level：** 下一家公司相关架构<br>**Target：** 完成 1 个完整 Design 或 2 个 Deep Dive Drill | Onsite / Final；同步不同公司的流程速度 |
| **15 · 11/02 - 11/08** | Maintenance；根据真实错误选择题目 | **High-level：** 真实面试暴露的板块<br>**Target：** 完成 1 个完整 Design 或 2 个 Deep Dive Drill | Final / Team Match；准备 Level 和 Scope 讨论 |
| **16 · 11/09 - 11/15** | Maintenance 或暂停 | **High-level：** 下一场需要的 Design<br>**Target：** 完成 1 个完整 Design 或 2 个 Deep Dive Drill；无活跃流程则暂停 | Offer、Team Match、Reference 或仍在进行的 Final；Pipeline 薄才补投 |
| **17 · 11/16 - 11/22** | 每周 2 次轻量练习 | **High-level：** Pipeline-dependent Review<br>**Target：** 有活跃流程时复述 1 个 Design | 仅维护活跃流程；不重启大规模题库 |
| **18 · 11/23 - 11/29** | Holiday Maintenance | **High-level：** Holiday Maintenance<br>**Target：** 有面试时复述 1 个 Design；否则不强制学习 | Thanksgiving 周默认降载；有面试再专项准备 |
| **19 · 11/30 - 12/06** | 按 Pipeline 选择弱项 | **High-level：** Pipeline-dependent Review<br>**Target：** 围绕下一场面试复述 1 个 Design | 推进延迟流程；评估是否需要 1 月第二窗口 |
| **20 · 12/07 - 12/13** | 轻量保持手感 | **High-level：** 通用 Design + Infra Design<br>**Target：** 各复述 1 次，形成下一窗口的 Error List | 关闭 2026 主窗口；形成 1 月继续或停止的明确决定 |

### 时间统计规则

- 求职运营的 **5h/周** 不写入上述每日技术表，可放在通勤、午休、零散晚间和低精力时段；它不应挤占 Coding/SD 深度训练块。
- 面试结果单独记录，但面试占用的时间必须从当周技术/面试日历中扣除。

## 5. 公司专项准备

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

## 6. 面试启动标准

投递和 Recruiter/HM Call 从 **Week 1** 开始，不需要等待技术准备完成。技术面分成两个门槛：达到 Calibration Gate 后用 B 组校准；达到 A Gate 后再启动价值最高的 A 组 Technical。判断依据是稳定表现，不是累计小时或题目数量。

### Calibration Gate · 目标 Week 5–6

#### Coding

- 能在 **30–35 分钟**内独立完成一道典型 Medium，并留出时间测试和讨论 Follow-up。
- 最近 5 次限时训练至少 **3 次**达到标准。
- 能边写边解释，不依赖看过答案后的短期记忆。

#### System Design

- 至少独立完成 **4 个完整 Design**，其中 2 个做过隔天闭卷复述。
- 能在 45–60 分钟内覆盖 Requirements、API / Data Model、High-level Architecture 和至少两个 Deep Dive。
- 遇到 Redis、Database、Queue 或 Cache 时，能解释为什么用、放在哪里、失败后怎样处理；不要求已经掌握所有高级细节。

#### Project / BQ

- 至少 1 个核心项目具备完整的 2/10/30 分钟版本。
- 至少 5 个 BQ Story 可在 2–3 分钟内讲清 Situation、Action、Trade-off 和 Result。

### A Gate · 目标 Week 7–8

#### Coding

- 在 **45–50 分钟**内完成两道难度合适的 Medium。
- 5 次限时训练中至少 **4 次**达到标准。
- 能边写边解释思路，不是写完以后再补讲。
- 能处理 Follow-up、测试、Edge Case 和需求变化。

#### System Design

- 完成 **6 次限时完整设计**。
- 至少包含 **2 个 Control Plane** 和 **1 个 GPU/Fleet/Scheduler** Design。
- 覆盖 Requirements、估算、API/Data Model 和 High-level Architecture。
- 能主动讨论 Scaling、Consistency、Failure Handling、Observability 和 Trade-off。

#### Project Deep Dive

- 准备 **3 个核心项目**。
- 每个项目都有 **2 分钟、10 分钟、30 分钟**版本。
- 能讲清 Alternative、Failure、Metrics 和个人贡献。
- 能为主要 Architecture Decision 和 Trade-off 辩护。

#### Behavioral Questions

- 准备 **10 个可复用 Story**。
- 覆盖 Conflict、Leadership、Failure、Ambiguity 和 Influence。
- 包含 Incident Response、Mentoring、困难取舍和 Measurable Impact。

#### Mocks

- 至少完成 **3 次 Coding Mock**。
- 至少完成 **3 次 System Design Mock**。
- 至少完成 **1 次 BQ / Project Deep Dive Mock**。
- 启动 A 组前，修正 Mock 暴露出的主要问题。

#### Pipeline

- 理想情况下先完成 **2 个 B 组 Calibration Technical Round**；若回复慢，可用严格 Mock 代替其中 1 个，不让高匹配机会无限等待。
- 根据真实反馈调整后续准备重点。
- 不要把价值最高的 A 公司 Onsite 当作第一套完整面试流程。
- A 组 Recruiter/HM Screen 可以更早完成；Gate 限制的是 Technical / Onsite，不是建立 Pipeline。
