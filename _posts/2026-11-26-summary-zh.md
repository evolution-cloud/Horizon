---
layout: default
title: "Horizon Summary: 2026-11-26 (ZH)"
date: 2026-11-26
lang: zh
---

> 从 36 条内容中筛选出 16 条重要资讯。

---

**科技新闻**
1. [AMD 专用 Llama.cpp 补丁提升老旧显卡性能](#item-tech-news-1) ⭐️ 8.0/10
2. [Lions&\#x27; Commentary on Unix: Why It Was Secretly Copied for 20 Years](#item-tech-news-2) ⭐️ 8.0/10
3. [基于零锥的引力代数量化新方法](#item-tech-news-3) ⭐️ 8.0/10
4. [Quoting Scott Aaronson](#item-tech-news-4) ⭐️ 8.0/10
5. [SpaceX 获准部署百万颗 Starmind 数据中心卫星](#item-tech-news-5) ⭐️ 8.0/10
6. [华为拟公布新款 HBM 芯片 数据引脚密度翻倍](#item-tech-news-6) ⭐️ 8.0/10
7. [中国发布新一代通信网建设实施方案，2030 年建成并启动 6G 建设](#item-tech-news-7) ⭐️ 8.0/10
8. [Neuralink 脑机接口获 FDA 批准，将启动渐冻症关键临床试验](#item-tech-news-8) ⭐️ 8.0/10
9. [英伟达暂停对东南亚四国 AI 服务器出货](#item-tech-news-9) ⭐️ 8.0/10
10. [阿斯麦 CEO：全面断供中国，只会逼中国自己造](#item-tech-news-10) ⭐️ 8.0/10
11. [Google 限制 AI 代理使用其 MCP 服务器](#item-tech-news-11) ⭐️ 7.0/10
12. [纽约时报警告摄影师勿因 AI 功能更新 Photoshop](#item-tech-news-12) ⭐️ 7.0/10
13. [Evaluating Recent Model Releases on GDPx](#item-tech-news-13) ⭐️ 7.0/10
14. [🤖 Claude Opus 5.6 仅凭一段提示生成高质量演示文稿](#item-tech-news-14) ⭐️ 7.0/10
15. [中国 AI 公司模型发布受反蒸馏和算力限制影响延期](#item-tech-news-15) ⭐️ 7.0/10

**财经新闻**
1. [荷兰反对美国限制 ASML 对华销售](#item-finance-news-1) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [AMD 专用 Llama.cpp 补丁提升老旧显卡性能](https://devnull.land/amd-specific-llama-cpp) ⭐️ 8.0/10

AMD 为 Llama.cpp 项目开发的专用补丁显著提升了在 2018 年左右的 AMD 图形处理器上运行大型语言模型的性能。这些补丁针对具有 32GB 显存和 1TB/s 带宽的 gfx906 架构数据中心卡（如 MI100）进行了优化，使这些原本计算能力中等但内存带宽极高的老旧显卡能够高效运行大语言模型。用户报告显示，通过这些优化，单张 MI100 卡处理 Qwen3.8-27B 模型时预填充速度可达 2400 tok/s，解码速度达 150 tok/s，并支持 3 个并发代理流，每个都具有 200k 的上下文窗口。

hackernews · julianlam · 11月26日 17:11 · [社区讨论](https://news.ycombinator.com/item?id=50657265)

**「背景」** HBM\(高带宽内存\)是一种专为高性能计算设计的内存技术，提供比传统 GDDR 内存更高的带宽和能效。AMD 在 2018 年左右推出的 gfx906 数据中心系列显卡虽然计算能力一般，但配备了极快的 HBM2 内存，提供了 32GB VRAM 和 1TB/s 的带宽，使其成为运行大型语言模型的理想选择。Llama.cpp 作为一款开源的大语言模型推理框架，需要针对 AMD 硬件的特殊架构进行优化，以充分发挥这些老旧但高性价比显卡的潜力。

**「性能提升与成本效益」** 通过 AMD 特定优化，用户可以在老旧 AMD 显卡上实现大型语言模型性能的翻倍或三倍提升，同时支持 200k 上下文长度和多个并发代理流。这些优化使原本需要高端硬件才能运行的 AI 工作负载，现在能够以约 200 美元的成本（相比当前 3000 美元以上的替代方案）实现，显著降低了 AI 技术的使用门槛。

**「社区反馈」** 用户 malicz 分享了他使用 r9700 显卡和 Radiance 引擎的积极体验，能够高效运行 Qwen3.8-27B 模型，并支持多个并发代理流，这证明了这些 AMD 专用补丁在实际应用中的显著效果。另一位用户 fiddlerwoaroof 则通过优化 AMD 代码并移植部分 N 内核到 ROCm，成功将 Claude 的性能提升了两到三倍，进一步验证了这些补丁的有效性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://www.amd.com/en/products/software/rocm.html">AMD ROCm™ software empowers developers to optimize AI and...</a></li>

</ul>
</details>

**标签**: `#AI Optimization`, `#Hardware Acceleration`, `#Open Source`, `#Cost-Effective AI`, `#Llama.cpp`

---

<a id="item-tech-news-2"></a>
### [Lions&\#x27; Commentary on Unix: Why It Was Secretly Copied for 20 Years](https://fosscomics.com/posts/17.%20Lions%27%20Commentary%20on%20Unix/) ⭐️ 8.0/10

The article reveals the hidden history of John Lions&\#x27; Unix commentary, a document that secretly influenced computer science education for decades despite copyright restrictions.

hackernews · joonehur · 11月26日 05:12 · [社区讨论](https://news.ycombinator.com/item?id=50651719)

**标签**: `#unix-history`, `#operating-systems`, `#software-heritage`, `#computer-science-education`, `#legal-tech`

---

<a id="item-tech-news-3"></a>
### [基于零锥的引力代数量化新方法](https://arxiv.org/abs/2611.34924) ⭐️ 8.0/10

这篇论文提出了一种在四维洛伦兹时空背景下对真空广义相对论进行背景独立量化的新方法。研究从一阶引力理论出发，通过求解大区域子空间中相交零锥上的引力约束，在有限 GN 条件下获得约化相空间。该方法将规范泊松括号提升为对易关系，并通过约化作用的变形定义了可观测量的代数结构。

hackernews · hecmmm · 11月26日 05:37 · [社区讨论](https://news.ycombinator.com/item?id=50651863)

**「背景」** 量子引力理论是理论物理学中最具挑战性的问题之一，旨在将广义相对论与量子力学统一起来。背景无关性是量子引力研究的关键原则，意味着理论不应依赖于预先设定的时空背景。零锥\(null cone\)是广义相对论中的重要概念，表示光信号在时空中传播的边界，论文作者利用相交零锥上的引力约束来解决四维洛伦兹时空中的真空广义相对论问题，这是一种创新的方法。

**「影响」** 这一方法为解决量子引力中的背景独立性问题提供了新的数学框架，可能推动理论物理学在时空本质理解方面的突破，并为未来实验验证量子引力理论奠定基础。

**「社区讨论」** Reddit 物理学板块版主指出，当前讨论几乎完全集中在 AI 相关话题而非论文本身的物理内容，建议等待领域专家评审；同时有评论者质疑论文中 Type I 代数与通常引力理论中预期的 Type II 代数之间的差异。

**标签**: `#quantum\_gravity`, `#theoretical\_physics`, `#mathematical\_physics`, `#research\_paper`, `#physics\_debate`

---

<a id="item-tech-news-4"></a>
### [Quoting Scott Aaronson](https://simonwillison.net/2026/Nov/25/scott-aaronson/) ⭐️ 8.0/10

Scott Aaronson describes a major breakthrough in complexity theory as opening up &\#x27;a whole new continent of mathematical truth&\#x27; with potentially revolutionary implications for mathematics and AI research.

rss · Simon Willison · 11月25日 23:26

**标签**: `#complexity-theory`, `#mathematics`, `#ai`, `#theoretical-computer-science`, `#breakthrough`

---

<a id="item-tech-news-5"></a>
### [SpaceX 获准部署百万颗 Starmind 数据中心卫星](https://www.geekwire.com/2026/fcc-clears-spacex-million-satellites-starmind-data-center/) ⭐️ 8.0/10

美国联邦通信委员会\(FCC\)批准 SpaceX 部署最多 100 万颗 Starmind 数据中心卫星，这是美国历史上首次批准太空数据中心星座。这些卫星将在 500 至 1002 公里的轨道高度运行，首颗卫星须不晚于 2033 年投入运行，整个星座须在 2040 年前全部运行。FCC 在审批中驳回了亚马逊、Viasat 和美国天文学会的反对意见。

telegram · zaihuapd · 11月26日 04:45

**「背景」** SpaceX 此前已成功运营 Starlink 卫星互联网星座，并在 2026 年 1 月获得 FCC 对其第二代 Starlink 系统的批准。Starmind 项目代表了 SpaceX 从卫星通信向太空数据处理的重大扩展，旨在通过部署在轨 AI 数据中心卫星来克服地面数据中心的限制。这些卫星将配备平均 175 千瓦的计算载荷，采用可展开液体散热器技术，以应对太空环境中的散热挑战。

**「影响」** 这一批准将使 SpaceX 能够构建全球最大的在轨数据处理网络，可能彻底改变全球数据传输和处理方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aiwiki.ai/wiki/spacex_starmind">SpaceX Starmind | AI Wiki</a></li>
<li><a href="https://www.satellitetoday.com/connectivity/2026/11/25/fcc-approves-spacexs-1-million-satellite-orbital-data-center-constellation/">FCC Approves SpaceX ’s 1-Million Satellite Orbital Data Center ...</a></li>
<li><a href="https://docs.fcc.gov/public/attachments/DOC-417881A1.pdf">FCC Approves Next-Gen Satellite Constellation</a></li>
<li><a href="https://www.fcc.gov/document/fcc-approves-next-gen-satellite-constellation">FCC Approves Next-Gen Satellite Constellation</a></li>

</ul>
</details>

**标签**: `#satellite technology`, `#space infrastructure`, `#data processing`, `#telecommunications`, `#spaceX`

---

<a id="item-tech-news-6"></a>
### [华为拟公布新款 HBM 芯片 数据引脚密度翻倍](https://www.bloomberg.com/news/articles/2026-11-26/huawei-teases-next-gen-ai-memory-chip-to-take-on-samsung-hynix) ⭐️ 8.0/10

华为计划公布一款新型高带宽内存\(HBM\)芯片，其数据引脚密度是三星电子和 SK 海力士现有量产产品的两倍，理论上可大幅提升内存带宽。华为将于明年 2 月在旧金山的一场会议上发表相关研究论文，并推动 HBM 在中国本土投产，而这一部件目前受美国制裁限制。

telegram · zaihuapd · 11月26日 05:30

**「高带宽内存技术背景」** 高带宽内存\(HBM\)是一种 3D 堆叠同步动态随机存取存储器\(SDRAM\)的计算机内存接口，最初由三星、AMD 和 SK 海力士开发，常用于高性能图形加速器、网络和人工智能应用。当前 HBM 市场高度集中，由三星、SK 海力士和美光科技三大厂商主导，占据超过 90%的市场份额，这使得华为突破这一技术壁垒并实现数据引脚密度翻倍的成就具有重要意义。

**「技术影响」** 华为的新 HBM 芯片通过将数据引脚密度提高一倍，理论上可大幅提升内存带宽，这将直接影响 AI 计算性能。在当前美国制裁限制中国获取先进存储芯片的背景下，这一技术突破可能使华为减少对外国供应商的依赖，同时挑战三星和 SK 海力士在高端内存市场的地位。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://www.linkedin.com/pulse/samsung-best-positioned-win-high-bandwidth-memory-race-jeff-morrison-utgpc">There&#x27;s Room for Three Horses in the HBM Memory Race...</a></li>
<li><a href="https://www.marketresearchfuture.com/reports/high-bandwidth-memory-market-21582">High Bandwidth Memory Market Report Size, Share and Trends 2035</a></li>

</ul>
</details>

**标签**: `#semiconductors`, `#AI hardware`, `#memory technology`, `#geopolitics`, `#Huawei`

---

<a id="item-tech-news-7"></a>
### [中国发布新一代通信网建设实施方案，2030 年建成并启动 6G 建设](https://www.news.cn/politics/20261126/9fe827a2d98741acb60f62d36ba89cf7/c.html) ⭐️ 8.0/10

经国务院同意，工业和信息化部、国家网信办、国家发展改革委联合印发《新一代通信网建设实施方案》，提出到 2030 年建成覆盖完善、性能领先的新一代通信网，适时开展 6G 网络建设，低轨卫星互联网系统基本建成，工业互联网、车联网等融合网络实现规模化发展。方案统筹推进基础网络、空间网络、国际网络、融合网络建设，明确积极推进 5G-A 网络规模覆盖，并加快推进 6G、卫星互联网、算网融合等标准研制，深化脑机接口、具身智能、智能网联汽车与新一代通信网的融合发展。

telegram · zaihuapd · 11月26日 06:30

**「背景」** 中国此前已发布 6G 发展路线图，旨在定义 6G 技术研发、标准制定和商业部署的关键阶段和目标。2026 年 6 月，中国已启动部省协同试点，根据国际电信联盟为 6G 定义的关键场景和性能指标推进技术研究、测试和验证。此次三部门印发的实施方案是在前期工作基础上，进一步明确了到 2030 年建成新一代通信网络并适时开展 6G 建设的具体规划。

**「影响分析」** 该实施方案将加速中国通信技术自主创新进程，推动 5G-A、6G 等前沿技术研发与产业化，同时促进卫星互联网、工业互联网等新兴领域发展，有望提升中国在下一代通信技术标准制定中的国际话语权，并为相关产业链企业带来新的发展机遇。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cn.ibtimes.com/china-6g-satellite-internet-roadmap-2030-1812837">China Unveils 2030 Roadmap for 6G Development and Nationwide ...</a></li>
<li><a href="http://english.scio.gov.cn/pressroom/2026-06/05/content_118532323.html">China launches ministry-provincial collaborative pilot ...</a></li>
<li><a href="https://baike.baidu.com/en/item/6G+Development+Roadmap/6536513">6G Development Roadmap_Baiduwiki - 百度百科</a></li>

</ul>
</details>

**标签**: `#6G`, `#Communication Infrastructure`, `#Technology Policy`, `#Network Development`, `#China Tech Strategy`

---

<a id="item-tech-news-8"></a>
### [Neuralink 脑机接口获 FDA 批准，将启动渐冻症关键临床试验](https://www.bloomberg.com/news/articles/2026-11-25/neuralink-gets-clearance-for-brain-implant-trial-in-als-patients?srnd=phx-technology) ⭐️ 8.0/10

Neuralink receives FDA approval to conduct pivotal clinical trials of its brain-computer interface for ALS patients.

telegram · zaihuapd · 11月26日 07:15

**标签**: `#brain-computer-interface`, `#medical-technology`, `#neuralink`, `#FDA-approval`, `#ALS-research`

---

<a id="item-tech-news-9"></a>
### [英伟达暂停对东南亚四国 AI 服务器出货](https://www.ft.com/content/7838a715-07d4-4605-aa60-21f5af2b2370) ⭐️ 8.0/10

英伟达已要求主要制造伙伴暂停向马来西亚、新加坡、泰国和印度尼西亚四国发运 AI 服务器。戴尔、美超微等将英伟达芯片组装成整机的厂商已通知四国买家相关订单不能出厂。这一冻结与美国新一轮出口管制相关，旨在阻止中国 AI 公司通过东南亚中转获取英伟达先进芯片，美国商务部上周要求区域云服务商在 90 天内取得出口许可并核实客户不含受限的中国实体。

telegram · zaihuapd · 11月26日 07:38

**「背景」** 美国近年来持续加强对华先进技术出口管制，特别是人工智能芯片领域。此前已限制英伟达等公司向中国直接出口高端 AI 处理器，促使中国 AI 企业通过东南亚国家作为中转地获取这些技术。美国商务部上周出台新规，进一步堵住了这一漏洞，要求区域云服务商必须获得出口许可并核实客户不包含受限制的中国实体。

**「影响分析」** 此举将显著影响东南亚地区 AI 基础设施建设和中国 AI 企业的芯片获取渠道，可能导致相关 AI 项目延期或转向替代方案，同时增加全球 AI 供应链的不确定性。

**标签**: `#AI hardware`, `#International trade`, `#Geopolitics`, `#Supply chain`, `#NVIDIA`

---

<a id="item-tech-news-10"></a>
### [阿斯麦 CEO：全面断供中国，只会逼中国自己造](https://www.semafor.com/article/11/25/2026/asml-makes-the-case-for-selling-chips-to-china) ⭐️ 8.0/10

ASML CEO argues that completely cutting off China from semiconductor equipment would accelerate China&\#x27;s self-reliance efforts rather than maintain dependency.

telegram · zaihuapd · 11月26日 12:19

**标签**: `#semiconductors`, `#international-trade`, `#tech-policy`, `#hardware`, `#supply-chain`

---

<a id="item-tech-news-11"></a>
### [Google 限制 AI 代理使用其 MCP 服务器](https://techstackups.com/articles/google-workspace-ai-agents-mcp/) ⭐️ 7.0/10

Google 将限制 AI 代理仅使用其 MCP 服务器，特别是 Gmail AI 代理无法发送邮件，这一限制引发了关于技术局限性和商业动机的讨论。这一决定影响了使用 Google Workspace 的 AI 代理用户，特别是那些希望通过 AI 自动化邮件操作的用户。Google 声称这是出于安全考虑，但社区质疑这可能是一种商业策略，旨在将用户锁定在其生态系统内。

hackernews · ritzaco · 11月26日 09:44 · [社区讨论](https://news.ycombinator.com/item?id=50653477)

**「背景」** MCP（模型上下文协议）是一种技术标准，允许 AI 代理与外部系统和服务交互。Google 通过 MCP 服务器将 AI 代理与 Workspace 产品集成的做法代表了他们将 AI 功能融入生产力软件的方式，但存在明显限制，例如 Gmail AI 代理无法发送电子邮件。这种方法反映了在启用 AI 功能与保持对关键操作控制之间的平衡，可能更多是出于商业决策而非纯粹的技术限制。

**「影响」** 对于依赖 AI 代理进行邮件自动化的用户和企业来说，这一限制意味着他们需要寻找替代方案或接受手动确认步骤，从而降低了工作效率并可能增加运营成本。

**「社区讨论」** 社区成员 perdy 指出，MCP 协议本身已经包含了用户确认的机制\(elicitation\)，因此将发送邮件功能限制为仅合作伙伴可用更像是商业决策而非安全问题。同时，Schnitz 预测用户可能会通过浏览器操作来绕过这一限制，导致不必要的复杂性和资源浪费。

**标签**: `#AI integration`, `#Google Workspace`, `#MCP`, `#Email automation`, `#Enterprise AI`

---

<a id="item-tech-news-12"></a>
### [纽约时报警告摄影师勿因 AI 功能更新 Photoshop](https://simonwillison.net/2026/Nov/26/hn-50651685/) ⭐️ 7.0/10

纽约时报已建立指导方针，警告摄影师不要使用 Photoshop 中的 AI 功能，强调专业摄影中的真实性原则。该报摄影师表示，他们仅应用裁剪和平衡调整，不会进行其他编辑，以维护新闻摄影的完整性。这一立场反映了新闻机构对 AI 技术在图像处理中应用的谨慎态度，特别是在可能影响内容真实性的情况下。

rss · Simon Willison · 11月26日 05:08

**「新闻摄影伦理背景」** 新闻摄影长期以来遵循严格的伦理标准，强调图像的真实性和准确性，不允许进行可能改变事实的编辑。随着 AI 技术在图像处理软件中的普及，如 Photoshop 的 AI 功能，新闻机构面临新的挑战，需要在保持新闻真实性的同时适应技术变革。

**「影响」** 这一警告可能导致专业摄影师重新评估使用 Photoshop 等工具的 AI 功能，特别是在新闻摄影领域。摄影师可能需要在技术便利与职业伦理之间做出选择，而新闻机构可能会制定更明确的 AI 使用政策，以保持内容的可信度和真实性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://retouchinglabs.com/photojournalism-and-ethics/">Photojournalism and Ethics - Retouching Labs</a></li>

</ul>
</details>

**标签**: `#ai-ethics`, `#photography`, `#adobe-photoshop`, `#media-ethics`, `#professional-practices`

---

<a id="item-tech-news-13"></a>
### [Evaluating Recent Model Releases on GDPx](https://newsletter.semianalysis.com/p/evaluating-recent-model-releases) ⭐️ 7.0/10

Introduction of GDPx, a new benchmark focusing on domains where frontier AI models will have the most significant impact.

rss · Semianalysis · 11月26日 00:05

**标签**: `#AI benchmarking`, `#Model evaluation`, `#Frontier intelligence`, `#AI research methodology`, `#Technology metrics`

---

<a id="item-tech-news-14"></a>
### [🤖 Claude Opus 5.6 仅凭一段提示生成高质量演示文稿](https://x.com/fluxxrider/status/2125622238481371372) ⭐️ 7.0/10

Claude Opus 5.6 demonstrates improved creative AI capabilities by generating complex presentations from minimal input.

telegram · zaihuapd · 11月26日 04:10

**标签**: `#AI`, `#Large Language Models`, `#Content Creation`, `#Productivity Tools`, `#Claude`

---

<a id="item-tech-news-15"></a>
### [中国 AI 公司模型发布受反蒸馏和算力限制影响延期](https://www.reuters.com/world/china/us-chip-curbs-distillation-crackdown-threaten-chinese-ai-model-development-2026-11-26/) ⭐️ 7.0/10

智谱\(Z.AI\)原计划本月发布 3 万亿参数规模的 GLM-5.5 旗舰模型，但受反蒸馏防护措施日趋有效等因素影响，知情人士称其发布可能推迟至 2027 年第一季度或更晚。月之暗面\(Moonshot AI\)内部预计，若完全失去海外算力，其重大版本发布间隔将从 6 个月拉长到一年以上，下一代旗舰 Kimi K4 或推迟至 2027 年年中，目前该公司已转而蒸馏谷歌和 Meta 的模型。

telegram · zaihuapd · 11月26日 15:14

**「技术背景」** 蒸馏技术\(distillation\)是 AI 模型开发中的一种方法，开发者通过使用更强大模型的输出来训练较小模型，从而获取部分能力。然而，美国公司如 OpenAI 和 Anthropic 已实施反蒸馏措施，防止其模型被未经授权地提取能力。同时，美国对先进芯片出口的限制进一步制约了中国 AI 公司的算力获取。这些因素共同导致中国 AI 企业如智谱和月之暗面面临模型开发周期延长、训练数据获取困难等挑战。

**「影响」** 中国 AI 公司模型开发周期延长将导致国内 AI 技术迭代速度放缓，影响企业竞争力，并可能促使中国 AI 产业更加依赖自主研发的技术路线而非借鉴国外模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://timewell.jp/en/columns/anthropic-distillation-report-moonshot-kimi-claude-relay-2026">Anthropic Names Seven Chinese Labs for &quot;Illicit Distillation &quot;</a></li>
<li><a href="https://qz.com/us-china-ai-distillation-deepseek-alibaba-intelligence-agencies-090926">U.S. accuses Chinese AI firms of stealing American AI model ...</a></li>
<li><a href="https://www.bnnbloomberg.ca/tariffs/2026/09/09/china-hits-back-at-us-claims-of-malicious-ai-distillation-ahead-of-planned-trump-xi-talks/">China hits back at U.S. claims of ‘malicious’ AI distillation</a></li>
<li><a href="https://www.reuters.com/world/china/us-chip-curbs-distillation-crackdown-threaten-chinese-ai-model-development-2026-11-26/">US chip curbs, distillation crackdown threaten Chinese AI ...</a></li>
<li><a href="https://www.firstpost.com/tech/chip-curbs-and-distillation-restrictions-threaten-chinas-ai-development-delay-upcoming-model-launches-14062807.html">Chip curbs and distillation restrictions threaten China&#x27;s AI ...</a></li>
<li><a href="https://economictimes.indiatimes.com/tech/artificial-intelligence/us-chip-curbs-distillation-crackdown-threaten-chinese-ai-model-development-sources-say/articleshow/136182809.cms">US chip curbs, distillation crackdown threaten Chinese AI ...</a></li>

</ul>
</details>

**标签**: `#AI development`, `#geopolitical impact`, `#model training`, `#Chinese AI`, `#technical challenges`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [荷兰反对美国限制 ASML 对华销售](https://www.bloomberg.com/news/articles/2026-11-26/netherlands-plans-to-fight-rollout-of-proposed-us-curbs-on-asml) ⭐️ 7.0/10

荷兰外贸大臣 Sjoerd Sjoerdsma 表示荷兰不接受美国限制 ASML 对华销售的 MATCH 法案，该法案将影响 ASML20%的销售额。

telegram · zaihuapd · 11月26日 14:56

**「背景」** ASML 是荷兰半导体设备制造商，中国占其年销售额的 20%，美国通过 MATCH 法案试图限制中国获取半导体技术，但荷兰拒绝接受此类域外管辖。

**「潜在影响」** 中国占 ASML 年销售额 20%，美国限制可能冲击全球半导体供应链和荷兰经济。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ASML">ASML - Wikipedia</a></li>
<li><a href="https://www.scmp.com/tech/big-tech/article/3370904/asmls-chip-equipment-sales-china-soar-109-despite-us-export-curb-push">ASML’s chip equipment sales to China soar 109% despite US ...</a></li>
<li><a href="https://informedclearly.com/en/trade-war/58105/match-act-semiconductor-export-controls-2026">MATCH Act 2026: Semiconductor Export Controls Reach Critical ...</a></li>

</ul>
</details>

**标签**: `#International trade`, `#Semiconductor industry`, `#US-China relations`, `#Dutch policy`, `#Export controls`

---