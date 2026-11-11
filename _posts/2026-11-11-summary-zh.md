---
layout: default
title: "Horizon Summary: 2026-11-11 (ZH)"
date: 2026-11-11
lang: zh
---

> 从 39 条内容中筛选出 15 条重要资讯。

---

**科技新闻**
1. [Tim Peters has died](#item-tech-news-1) ⭐️ 8.0/10
2. [线性规划用于权重空间编程的新方法](#item-tech-news-2) ⭐️ 8.0/10
3. [Atuin Threads 实现跨设备终端会话同步](#item-tech-news-3) ⭐️ 8.0/10
4. [AWS 发布官方模拟器，支持本地测试服务](#item-tech-news-4) ⭐️ 8.0/10
5. [谷歌使用 AI 发现玛雅金字塔](#item-tech-news-5) ⭐️ 7.0/10
6. [电压故障解锁 A100 挖矿卡功能](#item-tech-news-6) ⭐️ 7.0/10
7. [Anthropic&\#x27;s IPO roadshow video](#item-tech-news-7) ⭐️ 7.0/10
8. [AMD 推出 AI 内存页迁移技术降低服务器成本](#item-tech-news-8) ⭐️ 7.0/10
9. [字节筹备类 Muse 智能体，欲 2030 年前追平 OpenAI](#item-tech-news-9) ⭐️ 7.0/10

**科技博客**
1. [vLLM 编码器解聚：EPD 实现多模态服务扩展](#item-tech-blog-1) ⭐️ 9.0/10
2. [AI 时代下的胶水工作依然有害](#item-tech-blog-2) ⭐️ 5.0/10

**财经新闻**
1. [美联储官员称通胀数据&\#x27;令人不安&\#x27;，暗示可能进一步加息](#item-finance-news-1) ⭐️ 7.0/10
2. [阿里巴巴计划在香港上市旗下芯片公司 T-Head](#item-finance-news-2) ⭐️ 7.0/10
3. [离岸信托收益征税过渡期结束，累计申报超 1600 亿元](#item-finance-news-3) ⭐️ 7.0/10
4. [黄乐被指协助 24 万颗英伟达 AI 芯片进入中国](#item-finance-news-4) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Tim Peters has died](https://discuss.python.org/t/in-memoriam-tim-peters-1952-2026/110028) ⭐️ 8.0/10

The death of Tim Peters, influential Python contributor and author of &\#x27;The Zen of Python,&\#x27; marks a significant loss for the software engineering community.

hackernews · ayhanfuat · 11月11日 07:03 · [社区讨论](https://news.ycombinator.com/item?id=50450488)

**标签**: `#python`, `#programming-philosophy`, `#open-source`, `#memorial`, `#software-engineering`

---

<a id="item-tech-news-2"></a>
### [线性规划用于权重空间编程的新方法](https://nathan.rs/posts/weight-space-lp/) ⭐️ 8.0/10

研究人员提出了一种使用线性编程编辑机器学习模型权重的新方法，可为模型行为提供更精确的控制。这种方法通过严格的约束条件来修改模型，相比传统的强化学习方法可能更高效。该技术可能对 AI 安全领域产生重要影响，特别是在需要精确控制模型行为的场景中。目前该方法仍处于研究阶段，其实际应用效果有待进一步验证。

hackernews · emschwartz · 11月11日 12:30 · [社区讨论](https://news.ycombinator.com/item?id=50452655)

**「权重空间编程概念」** 权重空间编程是 2026 年 11 月由 MIT 计算机科学与人工智能实验室研究人员引入的一种机器学习方法，它允许通用大型语言模型\(LLM\)直接读取、解释和修改另一个神经网络的权重，而无需使用传统的梯度下降或训练循环。这种方法使前沿 LLM 能够通过直接权重编辑来实现模型行为的改变，为模型编辑提供了新的技术路径。

**「影响」** 这种线性编程方法可能使模型编辑工具如 Astra 能够更有效地修改模型权重，通过消除不需要的行为并保留所需行为，从而实现对模型行为的更精确控制。这种方法可能替代或补充传统的强化学习循环，特别是在需要强制执行严格输出约束的多目标场景中。

**「社区讨论」** 社区讨论中，用户 mirekrusin 提出可以将此方法用于权重空间蒸馏，通过收集配对样本发现行为方向，并使用线性编程找到稀疏权重编辑来改进目标行为。用户 jsw97 进一步解释，线性规划求解器可能使 Astra 等工具在权重编辑方面更有效，通过消除不需要的行为并保留所需行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Weight-space_programming">Weight-space programming - Wikipedia</a></li>
<li><a href="https://rikiyat.github.io/blog/weight-space-programming/">Sparks of Weight-Space Programming: LLMs can natively read ...</a></li>
<li><a href="https://www.datacamp.com/blog/weight-space-programming">Weight-Space Programming: How LLMs Edit Network Weights</a></li>

</ul>
</details>

**标签**: `#machine-learning`, `#linear-programming`, `#model-editing`, `#ai-safety`, `#optimization`

---

<a id="item-tech-news-3"></a>
### [Atuin Threads 实现跨设备终端会话同步](https://blog.atuin.sh/threads-agent-sessions/) ⭐️ 8.0/10

Atuin Threads 是一个新功能，允许开发者在所有设备上维护终端命令会话，解决了多机器工作环境中的生产力挑战。该功能通过同步终端历史记录和会话状态，使开发者可以在不同设备间无缝切换工作流程，无需重新输入命令或重建上下文。Atuin Threads 目前已在最新版本中可用，支持主流操作系统和终端模拟器。

hackernews · linsomniac · 11月11日 14:10 · [社区讨论](https://news.ycombinator.com/item?id=50453637)

**「背景信息」** Atuin 是一款免费工具，允许开发者在多台 PC 之间同步终端历史记录，解决了开发者经常在不同机器上工作时的命令历史不连续问题。Atuin Threads 是该工具的新功能，通过 threads\_search、threads\_list 和 threads\_read 等命令，使用户能够跨设备访问和管理终端会话，从而提高开发效率和 workflow 连续性。

**「开发者影响」** Atuin Threads 解决了开发者在多台机器间工作时终端会话不连续的痛点，显著提升了工作流程的连贯性。然而，用户报告的 EFSRO（只读文件系统错误）处理问题可能导致本地 shell 崩溃，这在使用/home 挂载遇到 RAID 阵列故障时尤为突出。社区已出现多种替代方案，如 slivingdoc 的上下文摘要方法和 ctools 的类 Unix 工具集成，表明开发者对会话管理有不同需求。

**「社区讨论」** 社区中存在关于如何有效管理这些会话的讨论，nzoschke 指出保存所有机器上的每个会话可能会产生大量噪音，特别是许多编码实验性/临时会话并不需要保留。同时，kristopolous 分享了一个基于 Unix 哲学的替代方案，通过类似\`ctools resume ssh://laptop.local/code/project\`的命令在设备间恢复会话，强调工作流程的连贯性比功能炫酷更重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.xda-developers.com/this-free-tool-syncs-terminal-history-between-pcs-belongs-every-developers-machine/">This free tool syncs your terminal history between PCs, and it...</a></li>
<li><a href="https://docs.atuin.sh/main/ai/mcp/">MCP Server - Atuin Docs</a></li>

</ul>
</details>

**标签**: `#developer-tools`, `#terminal`, `#productivity`, `#workflow`, `#session-management`

---

<a id="item-tech-news-4"></a>
### [AWS 发布官方模拟器，支持本地测试服务](https://simonwillison.net/2026/Nov/11/aws-emulator/) ⭐️ 8.0/10

AWS 发布了官方的 aws-emulator，允许开发者在本地测试 AWS 服务而无需付费 API 密钥。该模拟器使用 Rust 编写，在项目前三周已有 29,684 次提交，显示出 AWS 对此工具的重视。目前该工具在 macOS 和 Windows 上运行需要 Docker 支持。

rss · Simon Willison · 11月11日 21:18

**「背景」** AWS 长期以来缺乏官方的本地测试工具，开发者需要付费 API 密钥来测试其服务，这成为开发过程中的一个显著痛点。AWS 现在发布的官方模拟器 aws-emulator 解决了这一问题，允许开发者在本地环境中测试 AWS 服务而无需消耗付费资源。该项目由 AWS 团队使用 Rust 语言开发，在短短三周内就积累了近 3 万次提交，显示了 AWS 对此工具的重视程度。

**「开发影响」** AWS Emulator 使开发者能够在本地测试应用程序，无需付费凭证或实际调用 AWS 服务，显著降低了开发成本并加速了测试周期。开发者现在可以在没有 AWS 账户的情况下进行离线测试，提高了开发效率并减少了意外产生费用的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/aws/test-your-applications-against-aws-locally-with-aws-emulator/">Test your applications against AWS locally with AWS Emulator</a></li>
<li><a href="https://github.com/aws/aws-emulator">GitHub - aws/aws-emulator: AWS Emulator is a local emulator ...</a></li>

</ul>
</details>

**标签**: `#aws`, `#testing`, `#development-tools`, `#rust`, `#emulator`

---

<a id="item-tech-news-5"></a>
### [谷歌使用 AI 发现玛雅金字塔](https://pietromiotti.com/latest/maya-site/?maya) ⭐️ 7.0/10

谷歌软件工程师使用 48 个 AI 代理分析 NASA 激光雷达数据，在 72 小时内发现了一座先前未被记录的玛雅金字塔。这一发现展示了 AI 技术在考古学中的高价值应用，证明机器学习能够高效分析大型数据集并做出重要发现。该技术突破为考古研究提供了新的方法论，加速了历史遗迹的发现过程。

hackernews · eyvindn · 11月11日 12:05 · [社区讨论](https://news.ycombinator.com/item?id=50452455)

**「背景」** LiDAR（激光雷达）是一种通过激光脉冲测量距离的技术，能够穿透茂密的丛林植被，揭示地表下的古代结构。近年来，这项技术已成功应用于多个玛雅遗址的发现，如墨西哥的卡拉克穆尔金字塔。Google 工程师开发的 AI 代理系统通过分析 NASA 的 LiDAR 数据，显著提高了考古学家处理和分析大量地理数据的能力，使发现古代遗址的过程从数月缩短至数小时。

**「影响」** AI 技术加速考古发现，使研究人员能在短时间内处理大量数据并识别重要遗址。Google 使用 48 个 AI 代理在 72 小时内分析 NASA 激光雷达数据发现玛雅金字塔，展示了 AI 在考古学中的实际应用价值，但也凸显了专家验证的重要性。

**「社区讨论」** 社区讨论中，用户 LordOmlette 和作者 miotts 指出，该遗址实际上已被先前发现，质疑了这一发现的原创性。同时，TSiege 提醒人们考虑人类处理能力问题，指出随着 AI 发现更多遗址，考古学家可能面临保护这些遗址的挑战，因为最好的保护方式往往是保持原状。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pietromiotti.com/latest/maya-site/">My AI Agents Found an Unmapped Maya Site</a></li>
<li><a href="https://education.nationalgeographic.org/resource/exclusive-laser-scans-reveal-maya-megalopolis-below-guatemalan-jungle/10th-grade/">Exclusive: Laser Scans Reveal Maya “Megalopolis” Below Guatemalan...</a></li>
<li><a href="https://pietromiotti.com/latest/maya-site/">My AI Agents Found an Unmapped Maya Site</a></li>
<li><a href="https://www.historica.org/blog/the-latest-ai-innovations-in-archaeology">AI Revolutionizes Archaeology: Discoveries &amp; Challenges</a></li>
<li><a href="https://journal.caa-international.org/articles/10.5334/jcaa.207">Artificial Intelligence in Archaeological Site Conservation ...</a></li>
<li><a href="https://www.mdpi.com/2227-7080/14/3/152">Reconstructing Archaeological Evidence with Digital ... - MDPI</a></li>

</ul>
</details>

**标签**: `#AI`, `#Archaeology`, `#Lidar`, `#Discovery`, `#Technology`

---

<a id="item-tech-news-6"></a>
### [电压故障解锁 A100 挖矿卡功能](https://blog.kate.land/posts/using-voltage-glitching-to-unlock-the-a100/) ⭐️ 7.0/10

一篇详细的技术指南介绍了如何使用电压故障技术解锁 NVIDIA A100 GPU 在挖矿卡中被禁用的功能。该技术通过硬件级别的电压干扰绕过制造商施加的限制，使原本被限制的 GPU 能够发挥全部性能。这种方法特别适用于那些被故意降级以用于加密货币挖矿的企业级 GPU，如 A100 8GB 型号，可以将其解锁为完整的 80GB 版本。

hackernews · lae · 11月11日 10:48 · [社区讨论](https://news.ycombinator.com/item?id=50451903)

**「技术背景」** NVIDIA A100 是基于 Ampere 架构的数据中心 GPU，于 2020 年发布，有 40GB 和 80GB 两种版本，内存带宽分别为 1.55 TB/s 和 2.04 TB/s。电压故障注入是一种硬件黑客技术，通过在精确的时间点改变设备供电电压，干扰系统正常工作流程，可能绕过硬件安全限制或解锁被禁用的功能。

**「市场影响」** 这种电压故障技术解锁 NVIDIA A100 GPU 的能力可能导致矿卡和二手 GPU 市场价值重估，特别是对于原本被视为低规格的 8GB 型号，现在可以解锁为 80GB 全功能版本，从而大幅提升其市场价值。同时，这种硬件级别的修改技术可能促使 NVIDIA 在未来的硬件设计中增加更严格的防篡改机制，以防止类似的功能解锁。

**「社区讨论」** 社区成员讨论了使用外部 PCIe 扩展器和独立电源供应替代 ACPI S3 状态的可能性，以加速解锁过程；同时也有人对使用熔断器方法的风险表示担忧，认为软件解锁方法可能更安全。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ampere_%28microarchitecture%29">Ampere (microarchitecture) - Wikipedia A100 40GB vs 80GB: VRAM, Bandwidth &amp; MIG Compared for GPU ... A100 PCIe vs SXM in 2026: Single-GPU vs Multi-GPU Scaling ... NVIDIA A100 GPU — Specs, MIG, NVLink &amp; Use Cases NVIDIA H100 Specs: PCIe vs SXM vs NVL Compared (2026) NVIDIA A100 PCIe vs SXM: Comprehensive Performance Comparison</a></li>
<li><a href="https://www.thundercompute.com/blog/nvidia-a100-specs-full-guide">NVIDIA A100 Specs: 40GB vs 80GB, PCIe vs SXM (2026)</a></li>
<li><a href="https://riverloopsecurity.com/blog/2020/10/hw-101-glitching/">Hardware Hacking 101: Glitching into Privileged Shells</a></li>
<li><a href="https://www.synacktiv.com/en/publications/how-to-voltage-fault-injection">How to voltage fault injection - Synacktiv</a></li>

</ul>
</details>

**标签**: `#hardware-hacking`, `#gpu-modification`, `#voltage-glitching`, `#nvidia-a100`, `#hardware-security`

---

<a id="item-tech-news-7"></a>
### [Anthropic&\#x27;s IPO roadshow video](https://simonwillison.net/2026/Nov/11/anthropic-ipo-roadshow/) ⭐️ 7.0/10

Anthropic&\#x27;s IPO roadshow reveals their unconventional multi-chip strategy for training and serving Claude across AWS Trainium, Google TPUs, NVIDIA GPUs, and AMD GPUs.

rss · Simon Willison · 11月11日 15:11

**标签**: `#AI/ML`, `#Cloud Computing`, `#Hardware`, `#Business`, `#IPO`

---

<a id="item-tech-news-8"></a>
### [AMD 推出 AI 内存页迁移技术降低服务器成本](https://www.theregister.com/systems/2026/11/11/amd-where-were-going-we-dont-need-as-much-dram/5308953) ⭐️ 7.0/10

AMD 推出了一项基于 AI 的内存页迁移技术，通过收购的 Mext 技术开发的软件，可在操作系统或应用程序察觉之前，将内存页面在 DRAM 与更便宜的 NVMe 闪存之间动态迁移。这项技术允许服务器减少 DRAM 使用量，AMD 声称用闪存替代一半 DRAM 仍能保留最高 99%的性能，并估算最多可降低企业服务器成本 83%。该方案需在购买 AMD Epyc 服务器时一并购买 Mext 授权。

telegram · zaihuapd · 11月11日 11:15

**「技术背景」** 在计算机系统中，内存页面是操作系统管理内存的基本单位，DRAM 作为主存速度快但成本高，而 NVMe 闪存虽然速度较慢但价格便宜得多。&\#x27;冷&\#x27;内存页面指的是那些不经常被访问的数据，将其迁移到闪存中可以显著降低服务器对昂贵 DRAM 的需求，从而大幅降低硬件成本。AMD 通过收购 Mext 技术，利用 AI 模型在操作系统或应用程序察觉之前智能地管理内存页面的位置，实现了这一创新性的内存管理方案。

**「影响分析」** 这项技术可能显著降低数据中心运营成本，使企业能够在不牺牲太多性能的情况下，大幅减少对昂贵 DRAM 的依赖，从而优化服务器投资回报率。

**标签**: `#memory-management`, `#server-optimization`, `#AI-hardware`, `#cost-reduction`, `#amd-technology`

---

<a id="item-tech-news-9"></a>
### [字节筹备类 Muse 智能体，欲 2030 年前追平 OpenAI](https://www.bloomberg.com/news/articles/2026-11-11/bytedance-prepares-muse-like-agent-in-push-to-close-ai-gap) ⭐️ 7.0/10

字节跳动计划在未来数周发布一款类似 Meta Muse 的 AI 助手，以巩固其在 AI 视频领域的领先地位。联合创始人 Zhang Yiming 在内部全员会上宣布，公司将最多投入 700 亿美元打造 Seedance 视频 AI 平台，目标是在 2029 或 2030 年前缩小与美国顶尖实验室如 OpenAI 和 Anthropic 的差距。

telegram · zaihuapd · 11月11日 12:31

**「背景信息」** Meta Muse 是 Meta 公司开发的 AI 助手，专注于视频内容生成和处理。当前 AI 领域由 OpenAI 和 Anthropic 等美国公司主导，它们在大型语言模型和 AI 助手方面处于领先地位。字节跳动此次大规模投资表明其正积极寻求在全球 AI 竞争中占据更有利的位置。

**标签**: `#AI Strategy`, `#Large Tech Companies`, `#Video AI`, `#Investment`, `#Competitive Landscape`

---

## 科技博客

<a id="item-tech-blog-1"></a>
### [vLLM 编码器解聚：EPD 实现多模态服务扩展](https://vllm.ai/blog/2026-11-11-encoder-disaggregation-epd) ⭐️ 9.0/10

rss · vLLM Blog · 11月11日 00:00

**「背景」** 多模态推理在语言模型执行前增加了编码阶段，而编码阶段的需求随媒体大小、模态和请求组合而变化，且与预填充和解码需求独立变化。传统方法无法独立调整这些阶段的资源分配，导致资源利用效率低下。

**「方案」** vLLM 通过 EPD（编码器/预填充/解码）解聚架构将这三个阶段分离为独立部署的实例，实现各自独立扩展。核心机制包括：元数据仅请求避免重复预处理，专用编码器执行路径通过 Model Runner V2 实现，远程嵌入传输通过 NIXL 和 Mooncake 集成，跨编码器输出重用通过 Mooncake Store，以及 Python EPD 代理中的编排开销降低。在音频评估中，元数据仅转发将吞吐量从 62.21 提升至 73.13 请求/秒，平均延迟从 980 降至 853 毫秒。在 DeepSeek V4.1 Flash 评估中，EPD 在并发 64-128 时实现了 6.6-9.5%的每 GPU 更高吞吐量，P90 TTFT 降低 44-47%。

**「启示」** 编码器解聚架构使多模态服务能够根据不同工作负载需求独立扩展各计算阶段，显著提高资源利用效率和整体系统性能。

**标签**: `#multimodal-inference`, `#model-serving`, `#system-optimization`, `#encoder-disaggregation`, `#vllm`

---

<a id="item-tech-blog-2"></a>
### [AI 时代下的胶水工作依然有害](https://seangoedecke.com/glue-work-is-still-harmful-in-the-age-of-ai/) ⭐️ 5.0/10

rss · Sean Goedecke · 11月11日 00:00

**「背景」** 作者反对胶水工作，认为那些只能依靠工程师无偿牺牲维持的流程应当消亡。问题是，随着大语言模型\(LLM\)编写大部分代码，这是否减轻了人类工程师做胶水工作的负担？

**「方案」** 作者认为 AI 实际上降低了胶水工作的重要性，原因有四：首先，AI 减少了协调需求，单个工程师现在可以处理原本需要团队的项目；其次，2020 年代的工程师需要更少&\#x27;小心处理&\#x27;，那些有影响力的守门人已被行业淘汰或改变态度；第三，公司雇佣更少的初级员工，减少了入职引导等胶水工作；第四，LLM 可以自动化仅用于展示的报告。然而，作者警告 LLM 无法自动化所有胶水工作，特别是工程师之间的沟通，这仍应亲自完成。

**「启示」** 我们基本仍处于 2024 年的状态：避免成为&\#x27;胶水工作者&\#x27;，让糟糕的流程失败以便改变，但在能促进项目成功时愿意做少量战术性胶水工作。大部分时间和精力仍应花在代码上：驱动 AI 代理并使其与公司价值观保持一致。

**标签**: `#software-engineering`, `#ai-impact`, `#team-dynamics`, `#productivity`, `#career-advice`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [美联储官员称通胀数据&\#x27;令人不安&\#x27;，暗示可能进一步加息](https://www.cnbc.com/2026/11/11/goolsbee-october-inflation-fed-rates-disturbing-distressing.html) ⭐️ 7.0/10

美联储官员对高于预期的 10 月通胀数据表示担忧，消费者价格指数\(CPI\)环比上涨 0.4%，连续第三个月出现大幅增长。

rss · CNBC Finance · 11月11日 16:49

**「背景」** 这是美联储在 9 月加息 0.25 个百分点后，连续第二个月维持利率不变后面临的通胀数据。

**「影响」** 市场目前预计 12 月会议将加息，15%的可能性是加息 0.5 个百分点，这将对消费者借贷成本和企业投资决策产生直接影响。

**标签**: `#monetary-policy`, `#inflation`, `#interest-rates`, `#federal-reserve`, `#economic-data`

---

<a id="item-finance-news-2"></a>
### [阿里巴巴计划在香港上市旗下芯片公司 T-Head](https://www.cnbc.com/2026/11/11/alibaba-pr.html) ⭐️ 7.0/10

中国电商巨头阿里巴巴宣布计划在香港上市其半导体子公司 T-Head，此举是中国科技公司在美国限制下发展本土芯片战略的一部分。

rss · CNBC Finance · 11月11日 07:47

**「背景」** 阿里巴巴于 2018 年成立了其半导体子公司 T-Head，专注于开发 AI 芯片和基于开源 RISC-V 架构的处理器，以应对美国对中国获取芯片技术的限制。

**「影响」** 此举可能影响中国半导体行业的发展轨迹，并可能加剧中美科技竞争，同时为投资者提供参与中国本土 AI 芯片发展的新机会。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/T-head">T-head - Wikipedia T-Head Semiconductor | nextomoro Pingtouge Semiconductor Co., Ltd（semiconductor company）_Baiduwi... T-Head Semiconductor Co., Ltd. (Pingtouge) — Company Profile ... T-Head - Wikiwand Alibaba T-Head | China Chip Stack</a></li>
<li><a href="https://nextomoro.com/alibaba-t-head/">T-Head Semiconductor | nextomoro</a></li>
<li><a href="https://baike.baidu.com/en/item/Pingtouge+Semiconductor+Co.,+Ltd/22993">Pingtouge Semiconductor Co., Ltd（semiconductor company）_Baiduwi...</a></li>

</ul>
</details>

**标签**: `#Corporate Strategy`, `#Semiconductor Industry`, `#Chinese Tech`, `#IPO`, `#US-China Tech Tensions`

---

<a id="item-finance-news-3"></a>
### [离岸信托收益征税过渡期结束，累计申报超 1600 亿元](https://www.news.cn/20261111/9bcce99c779b4a6197ff45bbbc3e4c50/c.html) ⭐️ 7.0/10

China&\#x27;s offshore trust income tax transition period ended with over 160 billion yuan in declared taxes, significantly boosting government revenue.

telegram · zaihuapd · 11月11日 10:35

**标签**: `#Tax policy`, `#Offshore finance`, `#Wealth management`, `#Government revenue`, `#Regulatory compliance`

---

<a id="item-finance-news-4"></a>
### [黄乐被指协助 24 万颗英伟达 AI 芯片进入中国](https://www.tomshardware.com/tech-industry/policy/alice-huang-reportedly-instrumental-in-securing-over-usd7-5-billion-of-nvidia-ai-gpu-imports-during-three-year-relationship-with-jensen-huang-helped-move-240-000-banned-chips-into-china-mostly-h100-and-h200) ⭐️ 7.0/10

The Information 调查称，黄乐借助与英伟达 CEO 黄仁勋的关系，协助约 24 万颗被禁 AI 芯片进入中国，涉及价值约 75 亿美元的 H100 和 H200 芯片。

telegram · zaihuapd · 11月11日 14:41

**「背景」** 美国对中国实施 AI 芯片出口限制，禁止英伟达 H100 和 H200 等高端 AI 芯片直接出口到中国，以限制中国的人工智能发展能力。

**「潜在影响」** The alleged circumvention of US export controls could significantly impact US-China tech trade relations and AI development capabilities in China.

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.straitstimes.com/world/pla-linked-chinese-university-bought-nvidia-h200-chips-despite-us-blacklist-records-show">PLA-linked Chinese university bought Nvidia H 200 chips</a></li>
<li><a href="https://www.dailymotion.com/video/x9xq0ss">US Greenlights Nvidia H 200 AI Chip Sales to China , With Restrictions</a></li>

</ul>
</details>

**标签**: `#US-China trade`, `#AI chips`, `#Export controls`, `#NVIDIA`, `#Tech policy`

---