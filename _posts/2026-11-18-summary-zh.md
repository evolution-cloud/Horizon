---
layout: default
title: "Horizon Summary: 2026-11-18 (ZH)"
date: 2026-11-18
lang: zh
---

> 从 40 条内容中筛选出 16 条重要资讯。

---

**科技新闻**
1. [Unauthenticated remote code execution in Nginx](#item-tech-news-1) ⭐️ 8.0/10
2. [基于能量的推理器：推理效率提升 385 倍](#item-tech-news-2) ⭐️ 8.0/10
3. [AI 编程代理外部沙箱模式](#item-tech-news-3) ⭐️ 8.0/10
4. [Xint 披露 nginx 漏洞可获取 root 权限](#item-tech-news-4) ⭐️ 8.0/10
5. [微软发布七款高性能价格比 AI 模型](#item-tech-news-5) ⭐️ 7.0/10
6. [AI 代理在审计质询中表现优于 KPMG 会计师](#item-tech-news-6) ⭐️ 7.0/10
7. [Curl 创建者讨论 Rust 重写进展](#item-tech-news-7) ⭐️ 7.0/10
8. [Java 曝高危远程代码执行漏洞](#item-tech-news-8) ⭐️ 7.0/10

**科技博客**
1. [FlyDSL MonoKernels 优化 vLLM 解码延迟](#item-tech-blog-1) ⭐️ 8.0/10

**财经新闻**
1. [美联储官员暗示将进一步加息，担忧 AI 对通胀影响](#item-finance-news-1) ⭐️ 7.0/10
2. [Fed’s Waller says central bank may need to ‘shock people’ with half-point rate hike](#item-finance-news-2) ⭐️ 7.0/10
3. [摩根大通与现代卡测试 AI 代理自主金融交易](#item-finance-news-3) ⭐️ 7.0/10
4. [📱 美国芯片新规致 4.8 亿美元字节跳动 GPU 贷款暂停](#item-finance-news-4) ⭐️ 7.0/10
5. [英国移民与庇护法案通过下议院审议](#item-finance-news-5) ⭐️ 7.0/10
6. [腾讯三季报：AI 支出大幅超预期，WorkBuddy Token 用量国内领先](#item-finance-news-6) ⭐️ 7.0/10
7. [中韩自贸协定服务投资谈判实质性结束](#item-finance-news-7) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Unauthenticated remote code execution in Nginx](https://www.wiz.io/blog/nginx-http2-rce-vulnerabilities) ⭐️ 8.0/10

Critical remote code execution vulnerability in Nginx&\#x27;s HTTP/2 implementation requires immediate attention from system administrators.

hackernews · speedping · 11月18日 15:19 · [社区讨论](https://news.ycombinator.com/item?id=50547374)

**标签**: `#security`, `#nginx`, `#http2`, `#vulnerability`, `#web-server`

---

<a id="item-tech-news-2"></a>
### [基于能量的推理器：推理效率提升 385 倍](https://energy-based-reasoners.github.io/) ⭐️ 8.0/10

基于能量的推理器\(Energy-Based Reasoners\)展示了在 AI 推理方面具有突破性的效率提升，推理速度提高了 385 倍。该技术通过学习一个为给定输入的候选预测分配能量的标量函数，在解决特定逻辑问题\(如数独\)方面表现出色，但训练难度大且应用领域较为专业化。

hackernews · frenchmajesty · 11月18日 09:29 · [社区讨论](https://news.ycombinator.com/item?id=50543989)

**「背景」** 能量模型\(Energy-Based Models, EBMs\)是一种学习将能量值分配给给定输入的候选预测的模型类别。与传统模型不同，EBMs 通过优化过程进行推理，而非简单的序列处理。这类模型特别适用于需要行为可证明正确而非仅统计可能的场景，如高级制造和能源系统。Logical Intelligence 等组织正在开发此类系统，Yann LeCun 也参与了相关工作。

**「能源效率影响」** Energy-Based Reasoners 的 385 倍推理效率提升可能显著降低 AI 系统的能源消耗，这对于应对 AI 行业预计到 2028 年可能消耗美国 12%电力的能源挑战具有重要意义。这种效率提升可能使 AI 应用更加可持续，并减少碳足迹，特别是在需要大量推理计算的场景中。

**「社区讨论」** 社区讨论指出，由 Yann LeCun 领导的 Logical Intelligence 项目正在探索 EBMs 的潜力，特别是在 LLMs 传统表现不佳的领域如小学数学和计数问题。然而，有评论指出 EBMs 训练极其困难，应用范围较为狭窄，而 LLMs 虽然不够精确但能帮助人们完成工作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://energy-based-model.github.io/">Energy - Based Models : Representation, Inference , and Composition</a></li>
<li><a href="https://www.linkedin.com/pulse/energy-based-models-reasoning-through-optimization-just-pourmandi-cae9f">Energy - Based Models : Reasoning Through Optimization, Not Just...</a></li>
<li><a href="https://www.businesswire.com/news/home/20260120751310/en/Logical-Intelligence-Introduces-First-Energy-Based-Reasoning-AI-Model-Signals-Early-Steps-Toward-AGI-Adds-Yann-LeCun-and-Patrick-Hillmann-to-Leadership">Logical Intelligence Introduces First Energy-Based Reasoning ...</a></li>
<li><a href="https://openaimaster.com/deepseek-upends-energy-industry/">DeepSeek Upends Energy Industry - Open AI Master</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Inference Efficiency`, `#Energy-Based Models`, `#Reasoning Systems`

---

<a id="item-tech-news-3"></a>
### [AI 编程代理外部沙箱模式](https://simonwillison.net/2026/Nov/17/external-sandboxes-for-coding-agents/) ⭐️ 8.0/10

Prime Radiant 研究实验室推出了外部沙箱模式，用于安全执行 AI 编程代理生成的代码。该模式提供了三种沙箱服务器实现：external-sandbox-v86（使用 WebAssembly 运行 Alpine Linux）、external-sandbox-container（使用 Apple Containers）和 external-sandbox-quicksand（使用 Microsoft 的 Quicksand 库）。这些沙箱通过 localhost API 与 Pi、Claude Code 或 Codex 等编程代理集成，并包含 HTTP/HTTPS 允许列表代理和凭证替换机制，以防止提示注入攻击。

rss · Simon Willison · 11月17日 22:52

**「背景信息」** 提示注入攻击是一种利用对抗性提示工程来操纵 AI 模型的代码注入攻击，已成为 OWASP 的顶级 LLM 安全漏洞。这类攻击利用了生成式 AI 系统的核心功能——响应用户自然语言指令的能力，可能导致 AI 代理执行恶意代码或对系统造成损害。Prime Radiant 作为一家专注于多代理软件应用的研究实验室，此前已开发了 Superpowers 等代理技能框架，此次与 Simon Willison 合作开发的&\#x27;外部沙箱&\#x27;模式正是为了解决 AI 编码代理在执行代码时的安全问题。

**「安全影响」** 外部沙箱模式通过将 AI 代理与执行环境分离，有效解决了提示注入攻击和未授权系统访问的安全问题，使开发者能够安全地实验本地模型。这种架构保持了网络访问、凭据和工具权限的控制权，显著降低了恶意代码执行或数据泄露的风险，为 AI 编码代理的安全使用提供了实质性保障。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.getradiant.ai/">Radiant Labs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>
<li><a href="https://atlan.com/know/prompt-injection-attacks-ai-agents/">How Prompt Injection Attacks Compromise AI Agents in 2026</a></li>
<li><a href="https://www.ibm.com/think/topics/prompt-injection">What is a prompt injection attack? - IBM</a></li>
<li><a href="https://dvnc.dev/blog/ai-coding-agent-sandbox-security-model">A Sandbox Is Not a Security Model for AI Coding Agents | DVNC Dev</a></li>
<li><a href="https://medium.com/@connect.hashblock/the-agent-sandbox-pattern-that-prevents-incidents-ccb3302ba3b7">The Agent Sandbox Pattern That Prevents Incidents | Medium</a></li>
<li><a href="https://dev.to/gitrs_5994/a-disposable-sandbox-pattern-for-testing-ai-coding-agents-safely-452j">A Disposable Sandbox Pattern for Testing AI Coding Agents Safely</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#coding agents`, `#security`, `#sandboxing`, `#software engineering`

---

<a id="item-tech-news-4"></a>
### [Xint 披露 nginx 漏洞可获取 root 权限](https://nginx2root.com/) ⭐️ 8.0/10

Xint 公开了 NGINX2Root 漏洞集，包含 5 个 nginx 漏洞和一个 Linux 内核缺陷，可串联实现从 nginx 访客获取主机 root 权限。其中 CVE-2026-123007 是 HTTP/2 流控内存破坏漏洞，未认证即可在 worker 进程中执行命令。nginx 1.30.7 与 1.31.9 已于 11 月 18 日修复了 10 个 CVE，Rapid7 已发布 PoC，目前无在野利用报告。

telegram · zaihuapd · 11月18日 16:21

**「漏洞背景」** 这些 nginx 漏洞包括 HTTP/2 流控中的整数下溢漏洞\(CVE-2026-123007\)，允许未经身份验证的攻击者在 worker 上下文中远程执行代码，CVSS 评分为 9.2，属于严重级别。这些漏洞是 nginx 本身的缺陷，即使网站和应用程序代码是安全的也可能受到影响。当这些漏洞与 Linux 内核 SCTP 子系统中的漏洞结合使用时，攻击者可以获得主机的 root 权限。

**「影响范围」** 无法及时升级 nginx 版本的服务器面临被远程攻击者获取 root 权限的风险，攻击者可通过 HTTP/2 连接执行任意代码。若无法升级，必须禁用对外 HTTP/2 服务以缓解风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wiz.io/blog/nginx-http2-rce-vulnerabilities">Unauthenticated Remote Code Execution in NGINX ... | Wiz Blog</a></li>
<li><a href="https://www.rapid7.com/blog/post/ve-cve-2026-123007-critical-nginx-http-2-integer-underflow-leads-to-rce-fixed/">Rapid7 discloses a critical vulnerability affecting NGINX HTTP / 2 that...</a></li>
<li><a href="https://xint.io/blog/nginx2root-remote-code-execution">NGINX 2 Root : New Remote Code Execution Vulnerabilities in nginx ...</a></li>
<li><a href="https://lwn.net/Articles/1108362/">NGINX 2 Root : Remote Code Execution vulnerabilities in nginx</a></li>

</ul>
</details>

**标签**: `#security`, `#web-server`, `#vulnerability`, `#nginx`, `#root-access`

---

<a id="item-tech-news-5"></a>
### [微软发布七款高性能价格比 AI 模型](https://microsoft.ai/news/microsoft-ignite-2026/) ⭐️ 7.0/10

微软在 2026 年 Ignite 大会上发布了七款新的 AI 模型，这些模型具有出色的价格性能比，直接挑战 Anthropic 和 OpenAI 等主要 AI 提供商的市场地位。这些新模型被设计为在保持竞争力的同时提供更好的成本效益，但尚未提供详细的技术规格或性能基准数据。此次发布标志着微软在 AI 领域的进一步扩张，旨在通过价格优势吸引更多企业和开发者采用其 AI 服务。

hackernews · gmays · 11月18日 16:08 · [社区讨论](https://news.ycombinator.com/item?id=50548021)

**「背景」** AI 模型市场近年来竞争激烈，Anthropic 和 OpenAI 一直处于领先地位，提供高性能但价格较高的模型。微软此前已通过 Azure AI 服务提供 AI 模型，但此次发布的七款新模型代表了其产品线的重大扩展，专注于价格性能比的优化，以在竞争日益激烈的市场中占据更有利的位置。

**「影响」** 对于企业和开发者而言，这些新模型可能降低 AI 应用的开发和部署成本，特别是在预算有限但需要高质量 AI 能力的场景中。然而，由于缺乏独立评测和详细技术规格，实际应用效果仍需验证，这可能影响组织在 AI 基础设施决策中的信心。

**「社区讨论」** 社区讨论中存在明显分歧，部分用户对微软新模型表示认可，认为其性能已可与 Anthropic 的 Opus 和 OpenAI 的 Sol 等顶级模型相媲美；而另一些用户则对微软的品牌声誉表示担忧，并质疑这些模型是否经过充分测试，同时建议微软应考虑开源部分模型以增加市场竞争力。

**标签**: `#AI models`, `#Microsoft`, `#Competitive landscape`, `#Price-performance`, `#Developer tools`

---

<a id="item-tech-news-6"></a>
### [AI 代理在审计质询中表现优于 KPMG 会计师](https://europeanbusinessmagazine.com/ai-agents-better-questions-kpmg/) ⭐️ 7.0/10

AI 代理在审计质询中展现出比 KPMG 会计师更强的问题生成能力。这项比较研究表明，在知识密集型专业服务领域，AI 增强技术具有显著潜力。该研究涉及审计过程中的问题生成环节，AI 代理能够提出更全面、更深入的问题，而这是审计工作的关键部分。这一发现表明 AI 技术正在专业服务领域展现出实际应用价值。

hackernews · Betelbuddy · 11月18日 15:49 · [社区讨论](https://news.ycombinator.com/item?id=50547777)

**「背景」** 审计是专业会计服务中的关键环节，涉及对财务报表的独立检查以确保其准确性和合规性。KPMG 此次进行的 AI 审计试验标志着人工智能技术在知识密集型专业服务领域的重要应用进展，展示了 AI 在复杂分析任务中的潜力。

**「影响」** 这一发现可能促使会计师事务所重新评估其工作流程，考虑将 AI 代理整合到审计团队中，以提高审计质量和效率。会计师可能需要发展新的技能，专注于与 AI 协作而非被 AI 替代。

**「社区讨论」** 社区讨论中，有观点认为 AI 的优势部分来自于其没有人类固有的惰性倾向，以及可以基于大量专业数据进行训练。同时也有声音指出，历史经验表明新技术如 Excel 和计算器并没有完全取代会计师，而是帮助他们完成更多工作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.business-standard.com/industry/news/kpmg-finds-ai-agents-ask-better-questions-than-human-auditors-in-trial-126111800471_1.html">KPMG finds AI agents ask better questions than human auditors ...</a></li>
<li><a href="https://europeanbusinessmagazine.com/ai-agents-better-questions-kpmg/">AI Agents Ask Better Questions Than KPMG Accountants</a></li>
<li><a href="https://www.afr.com/world/europe/ai-asked-better-questions-than-kpmg-accountants-in-first-audit-20261119-p61fdr">AI asked ‘better questions’ than KPMG accountants in first audit</a></li>

</ul>
</details>

**标签**: `#AI-applications`, `#professional-services`, `#audit-technology`, `#human-AI-comparison`, `#business-automation`

---

<a id="item-tech-news-7"></a>
### [Curl 创建者讨论 Rust 重写进展](https://simonwillison.net/2026/Nov/18/daniel-stenberg/) ⭐️ 7.0/10

Curl 的创建者 Daniel Stenberg 报告了将 curl 从 C 语言重写为 Rust 的进展，期间转换了 185,000 行 C 代码为 340,000 行 Rust 代码。在同一时期，原始 curl 项目合并了超过 300 个提交，实现了 200 多个 bug 修复和安全漏洞修复。Stenberg 质疑这些 Rust 克隆版本能否跟上原始项目的持续改进步伐。

rss · Simon Willison · 11月18日 15:58

**「背景」** curl 是一个广泛使用的命令行工具和库，用于传输数据，最初是用 C 语言编写的。近年来，社区出现了多个将 curl 重写为 Rust 语言的尝试，旨在利用 Rust 的内存安全特性提高安全性。Daniel Stenberg 作为 curl 的创建者，一直关注这些重写项目，并定期分享原始 curl 项目的进展和改进情况。

**「影响」** 对于依赖 curl 的开发者和组织而言，原始 C 版本持续的 bug 修复和安全更新可能比正在进行的 Rust 重写版本更可靠，特别是在关键安全问题上。

**标签**: `#curl`, `#rust`, `#software-engineering`, `#security`, `#programming-languages`

---

<a id="item-tech-news-8"></a>
### [Java 曝高危远程代码执行漏洞](https://censys.com/advisory/cve-2026-114938/) ⭐️ 7.0/10

Java 曝出无需认证远程代码执行高危漏洞 CVE-2026-114938，CVSS 4.0 评分 9.2，潜伏近 4 年。影响范围包括 Java 17（17.0.6 及之后全部 17 线）、21、25、27；标准 Java 8/11 通常不受影响，但 Oracle Java 8 Performance Pack 例外。该漏洞仅影响搭载 AVX-512 VBMI 指令集的 x86-64 服务器处理器，大致对应 2021 年及以后发布的 Intel 处理器（Ice Lake 及更新世代 Xeon）和 2022 年及以后发布的 AMD 处理器（Zen 4 及更新 EPYC/Ryzen）；ARM64 架构不受影响。

telegram · zaihuapd · 11月18日 03:55

**「技术背景」** AVX-512 是 Intel 于 2013 年提出的 x86 指令集架构的 512 位 SIMD 扩展指令集，首次实现于 2016 年的 Intel Xeon Phi x200 处理器，后来在 AMD 和其他 Intel CPU 中也有应用。Java4Shell 漏洞\(CVE-2026-114938\)源于 OpenJDK HotSpot 虚拟机中 AVX-512 VBMI Base 64 解码 intrinsic 的内存损坏问题，当处理特定 65 字节输入时会导致整数下溢，产生完整的 64 位写入掩码，从而可能允许远程代码执行。

**「影响与应对」** 受影响组织需立即评估其 Java 环境，特别是运行 Java 17、21、25 或 27 版本且使用支持 AVX-512 VBMI 指令集的 x86-64 处理器的系统。由于该漏洞允许无需认证的远程代码执行，攻击者可能完全控制受影响系统。组织应优先应用 Oracle 或 OpenJDK 的安全补丁，或实施 Microsoft Azure 网络安全团队建议的缓解措施，直到补丁可用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AVX-512">AVX - 512 - Wikipedia</a></li>
<li><a href="https://github.com/ikow/java4shell-poc">ikow/java4shell-poc: CVE-2026-114938 — OpenJDK AVX - 512 Base 64 ...</a></li>
<li><a href="https://www.malwarebytes.com/blog/bugs/2026/11/java4shell-a-critical-flaw-with-a-narrow-reach">Java4Shell: A critical flaw with a narrow reach | Malwarebytes</a></li>
<li><a href="https://techcommunity.microsoft.com/blog/azurenetworksecurityblog/addressing-java4shell-cve-2026-114938-upgrade-guidance-and-azure-waf-mitigations/4574305">Addressing Java4Shell CVE-2026-114938: upgrade guidance and ...</a></li>
<li><a href="https://pentestit.com/java4shell-cve-2026-114938-detection-mitigation/">Java4Shell (CVE-2026-114938): Exposure, Fixes and Detection ...</a></li>

</ul>
</details>

**标签**: `#security`, `#java`, `#vulnerability`, `#remote-code-execution`, `#hardware-specific`

---

## 科技博客

<a id="item-tech-blog-1"></a>
### [FlyDSL MonoKernels 优化 vLLM 解码延迟](https://vllm.ai/blog/2026-11-18-flydsl-monokernels) ⭐️ 8.0/10

rss · vLLM Blog · 11月18日 00:00

**「背景」** 交互式 LLM 应用依赖低解码延迟，但在小批量情况下，许多 GPU 内核执行少量工作却仍产生调度、启动和完成开销，这些开销可能占解码延迟的很大部分，同时少量并行工作导致 GPU 容量闲置。现有解决方案如 HIP 图表减少了 CPU 启动开销，但无法消除这些 GPU 端成本。

**「方案」** FlyDSL MonoKernels 通过将多个操作阶段合并到单个 GPU 内核启动中来减少解码延迟，使用显式设计的调度而非在每个操作边界单独启动。关键机制包括：跨阶段重用线程块减少重复 GPU 内核启动；在早期计算期间预取权重以重叠 HBM 流量与有用工作；使用标记邮箱按消费者需要的数据粒度传递数据。边界选择是模型特定的，而非通用模板。FlyDSL 作为 AMD 的 Python DSL 和 MLIR 编译器，提供了表达和编译这些设计所需的控制。在 vLLM 中，MonoKernels 作为专用解码路径集成，可选择启用，并与现有组件兼容。

**「启示」** FlyDSL MonoKernels 通过将多个操作阶段合并到单个内核启动中，显著提高了 AMD GPU 上 vLLM 交互式 LLM 应用的解码性能，将交互性提升了 1.20×至 2.26×，同时保持准确性不变。

**标签**: `#LLM inference optimization`, `#GPU kernel design`, `#AMD Instinct`, `#vLLM`, `#decode latency`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [美联储官员暗示将进一步加息，担忧 AI 对通胀影响](https://www.cnbc.com/2026/11/18/fed-minutes-october-2026.html) ⭐️ 7.0/10

美联储官员表示需要进一步加息以抑制通胀，特别关注人工智能对通胀的影响，10 月会议决定维持利率在 3.75%-4%不变但暗示未来可能加息。10 月消费者价格指数上涨 0.4%，核心指数上涨 0.3%，均高于预期。

rss · CNBC Finance · 11月18日 19:41

**「背景」** 美联储以 2%的通胀率为目标，但当前通胀率仍高于这一目标，促使官员们考虑进一步加息。

**「影响」** 加息预期将提高借贷成本，可能抑制消费和投资，同时科技行业特别是 AI 相关企业可能面临融资压力和估值调整。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Inflation_targeting">Inflation targeting - Wikipedia</a></li>
<li><a href="https://cryptobriefing.com/fed-barkin-2-percent-inflation-target/">Federal Reserve &#x27;s Barkin commits to 2 % inflation target , signals...</a></li>

</ul>
</details>

**标签**: `#Federal Reserve`, `#Interest Rates`, `#Inflation`, `#Artificial Intelligence`, `#Monetary Policy`

---

<a id="item-finance-news-2"></a>
### [Fed’s Waller says central bank may need to ‘shock people’ with half-point rate hike](https://www.cnbc.com/2026/11/18/federal-reserve-governor-christopher-waller.html) ⭐️ 7.0/10

Fed Governor Christopher Waller calls for a potentially aggressive half-point rate hike to combat inflation that&\#x27;s &\#x27;headed in the wrong direction.&\#x27;

rss · CNBC Finance · 11月18日 15:13

**标签**: `#Federal Reserve policy`, `#Interest rates`, `#Inflation`, `#Monetary policy`, `#Market expectations`

---

<a id="item-finance-news-3"></a>
### [摩根大通与现代卡测试 AI 代理自主金融交易](https://www.cnbc.com/2026/11/18/jpmorgan-hyundai-card-ai-agents-payments.html) ⭐️ 7.0/10

摩根大通与现代卡已完成 AI 代理自主金融交易的初步概念验证，计划在 2027 年上半年进行更复杂的测试阶段。

rss · CNBC Finance · 11月18日 06:18

**「背景」** AI 代理被视为金融支付领域的高潜力应用，可在无需直接人工干预的情况下处理财务交易。

**「影响」** 这项技术可能改变企业资金管理方式，但也带来了治理挑战和安全风险，特别是当 AI 代理在没有人工监督的情况下执行交易时。

**标签**: `#AI technology`, `#Financial innovation`, `#Corporate treasury`, `#Digital payments`, `#Risk management`

---

<a id="item-finance-news-4"></a>
### [📱 美国芯片新规致 4.8 亿美元字节跳动 GPU 贷款暂停](https://www.bloomberg.com/news/articles/2026-11-17/banks-pause-480-million-chip-loan-tied-to-china-s-bytedance) ⭐️ 7.0/10

US chip regulations cause major banks to pause a $480 million loan for ByteDance&\#x27;s GPU purchase, highlighting growing restrictions on technology financing.

telegram · zaihuapd · 11月18日 05:11

**标签**: `#US-China tech tensions`, `#Chip regulations`, `#International financing`, `#AI technology`, `#ByteDance`

---

<a id="item-finance-news-5"></a>
### [英国移民与庇护法案通过下议院审议](https://www.bloomberg.com/news/articles/2026-11-17/uk-s-house-of-commons-passes-controversial-immigration-bill) ⭐️ 7.0/10

The UK&\#x27;s Immigration and Asylum Bill, which passed the House of Commons with significant support, will substantially reshape immigration policy with economic implications for labor markets and public services.

telegram · zaihuapd · 11月18日 05:51

**标签**: `#immigration-policy`, `#uk-politics`, `#labor-market`, `#public-services`, `#legislative-change`

---

<a id="item-finance-news-6"></a>
### [腾讯三季报：AI 支出大幅超预期，WorkBuddy Token 用量国内领先](https://api3.cls.cn/share/article/2537922?os=android&amp;amp;sv=8.8.5&amp;amp;app=cailianpress&amp;amp;selected=) ⭐️ 7.0/10

腾讯 2026 年第三季度财报显示，资本开支达 814.33 亿元，远超市场预期的 554 亿元，同时 WorkBuddy 成为国内日均 Token 用量最高的 AI 产品，每日消耗超过 100 万亿。

telegram · zaihuapd · 11月18日 09:20

**「背景」** 腾讯在 2026 年第二季度资本支出同比增长 176%至 528 亿元，大力投资 AI 基础设施，而其传统业务为这一 AI 转型提供资金支持。WorkBuddy 作为腾讯推出的全场景 AI 办公工作台，自 2026 年 3 月发布以来，已发展成为国内大语言模型日均 Token 用量最高的 AI 产品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ithome.com/1/028/914.htm">腾讯 WorkBuddy 日活跃用户数超 1000 万，成为中国大语言模型日均 Tok...</a></li>
<li><a href="https://chinabizinsider.com/tencent-isolates-ai-costs-in-q1-2026-revealing-resilient-core-bankrolling-generative-pivot/">Tencent Q1 2026: Core Profits Bankroll AI Pivot</a></li>
<li><a href="https://www.nationpress.com/sciencetech/tencent-capex-triples-in-ai-push">Tencent capex surges 176% in Q2 2026 as AI push lifts revenue</a></li>

</ul>
</details>

**标签**: `#earnings-report`, `#ai-technology`, `#chinese-tech`, `#capital-expenditure`, `#tencent`

---

<a id="item-finance-news-7"></a>
### [中韩自贸协定服务投资谈判实质性结束](https://x.com/Jaemyung_Lee/status/2122988472994791476) ⭐️ 7.0/10

中韩于 11 月 18 日宣布自贸协定服务投资后续谈判实质性结束，中国将在电影、游戏等领域给予韩国最惠国待遇，并扩大旅游、法律、建筑、金融等领域市场开放。

telegram · zaihuapd · 11月18日 10:02

**「背景」** 中韩自贸协定谈判自 2018 年 3 月启动，历时 8 年 8 个月，此次服务与投资后续谈判的结束标志着两国经贸关系的重要进展。

**「影响」** 此次协议将促进中韩两国在文化、旅游、金融等多个领域的合作，为两国关系全面恢复奠定基础。

**标签**: `#Trade Agreement`, `#China-Korea Relations`, `#Market Access`, `#Cultural Exchange`, `#Diplomacy`

---