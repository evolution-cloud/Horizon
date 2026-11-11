---
layout: default
title: "Horizon Summary: 2026-11-11 (EN)"
date: 2026-11-11
lang: en
---

> From 39 items, 15 important content pieces were selected

---

**Technology News**
1. [Tim Peters has died](#item-tech-news-1) ⭐️ 8.0/10
2. [Linear Programming for ML Weight-Space Editing](#item-tech-news-2) ⭐️ 8.0/10
3. [Atuin Threads Syncs Terminal Sessions Across Machines](#item-tech-news-3) ⭐️ 8.0/10
4. [AWS Releases Official Emulator for Local Testing](#item-tech-news-4) ⭐️ 8.0/10
5. [Google AI Discovers Maya Pyramid with NASA Lidar](#item-tech-news-5) ⭐️ 7.0/10
6. [Voltage Glitching Unlocks NVIDIA A100 Features in Mining Cards](#item-tech-news-6) ⭐️ 7.0/10
7. [Anthropic&\#x27;s IPO roadshow video](#item-tech-news-7) ⭐️ 7.0/10
8. [AMD AI Memory Migration Cuts Server Costs](#item-tech-news-8) ⭐️ 7.0/10
9. [ByteDance Plans $700B Investment in AI Assistant to Compete with OpenAI](#item-tech-news-9) ⭐️ 7.0/10

**Technology Blog**
1. [vLLM&\#x27;s EPD Architecture for Multimodal Scaling](#item-tech-blog-1) ⭐️ 9.0/10
2. [AI Doesn&\#x27;t Make Glue Work Valuable](#item-tech-blog-2) ⭐️ 5.0/10

**Financial News**
1. [Fed Reacts to Higher-Than-Expected October Inflation](#item-finance-news-1) ⭐️ 7.0/10
2. [Alibaba Plans Hong Kong Listing for Semiconductor Unit T-Head](#item-finance-news-2) ⭐️ 7.0/10
3. [离岸信托收益征税过渡期结束，累计申报超 1600 亿元](#item-finance-news-3) ⭐️ 7.0/10
4. [Alleged $7.5B NVIDIA Chip Import Circumvention](#item-finance-news-4) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Tim Peters has died](https://discuss.python.org/t/in-memoriam-tim-peters-1952-2026/110028) ⭐️ 8.0/10

The death of Tim Peters, influential Python contributor and author of &\#x27;The Zen of Python,&\#x27; marks a significant loss for the software engineering community.

hackernews · ayhanfuat · Nov 11, 07:03 · [Discussion](https://news.ycombinator.com/item?id=50450488)

**Tags**: `#python`, `#programming-philosophy`, `#open-source`, `#memorial`, `#software-engineering`

---

<a id="item-tech-news-2"></a>
### [Linear Programming for ML Weight-Space Editing](https://nathan.rs/posts/weight-space-lp/) ⭐️ 8.0/10

A novel approach applies linear programming techniques to edit machine learning model weights with more precise control over model behavior. This method allows for enforcing strict constraints on model outputs through mathematical formulations rather than traditional reinforcement learning approaches. The technique could potentially make weight editing processes more efficient and targeted, particularly for models like Astra that need to modify specific behaviors while preserving others.

hackernews · emschwartz · Nov 11, 12:30 · [Discussion](https://news.ycombinator.com/item?id=50452655)

**「Background」** Weight-space programming is a novel approach introduced in November 2026 by MIT researchers that allows a general-purpose large language model to directly read and write the weights of another neural network without using gradient descent or training loops. This method represents a significant departure from traditional machine learning techniques that rely on iterative optimization processes. The current exploration of applying linear programming to weight-space programming builds on this emerging paradigm to potentially provide more precise control over model behavior.

**「Practical Impact」** This approach could significantly improve the precision and efficiency of model editing in AI safety applications, allowing developers to make targeted changes to model behavior without unintended side effects.

**「Community Insights」** Community members suggest this linear programming approach could be particularly valuable for weight-space distillation, where small models could be improved through sparse weight edits that target specific behaviors while minimizing unwanted changes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Weight-space_programming">Weight-space programming - Wikipedia</a></li>
<li><a href="https://rikiyat.github.io/blog/weight-space-programming/">Sparks of Weight-Space Programming: LLMs can natively read ...</a></li>
<li><a href="https://www.datacamp.com/blog/weight-space-programming">Weight-Space Programming: How LLMs Edit Network Weights</a></li>

</ul>
</details>

**Tags**: `#machine-learning`, `#linear-programming`, `#model-editing`, `#ai-safety`, `#optimization`

---

<a id="item-tech-news-3"></a>
### [Atuin Threads Syncs Terminal Sessions Across Machines](https://blog.atuin.sh/threads-agent-sessions/) ⭐️ 8.0/10

Atuin Threads enables developers to maintain their terminal command sessions across all machines, solving a common productivity challenge in software development. The feature allows users to seamlessly continue their work from any device by syncing command history and terminal sessions. This addresses a significant pain point for developers who frequently switch between workstations, laptops, and remote servers.

hackernews · linsomniac · Nov 11, 14:10 · [Discussion](https://news.ycombinator.com/item?id=50453637)

**「Background」** Atuin is a command-line tool that enhances terminal productivity by recording and searching shell history across multiple machines. The Threads feature extends this capability by maintaining complete terminal sessions, not just command history, allowing developers to seamlessly continue work from where they left off on any device. This builds upon Atuin&\#x27;s existing functionality of securely syncing terminal history, addressing a common pain point for developers who work across multiple computers.

**「Developer Productivity」** Developers can now maintain continuity across terminal sessions across multiple machines, eliminating the need to manually recreate command histories and working contexts when switching devices. This addresses a common productivity challenge for developers who work across different machines, potentially reducing context switching time and improving workflow efficiency.

**「Community Discussion」** Users have shared various approaches to session management, with nzoschke noting the challenge of deciding which sessions to save to avoid noise, while kristopolous described a &\#x27;unixy&\#x27; solution that integrates with existing terminal tools. However, hugmynutus reported a concerning issue with Atuin&\#x27;s handling of read-only file systems that broke their local shell after a drive failure.

<details><summary>References</summary>
<ul>
<li><a href="https://www.xda-developers.com/this-free-tool-syncs-terminal-history-between-pcs-belongs-every-developers-machine/">This free tool syncs your terminal history between PCs, and it...</a></li>
<li><a href="https://docs.atuin.sh/main/ai/mcp/">MCP Server - Atuin Docs</a></li>

</ul>
</details>

**Tags**: `#developer-tools`, `#terminal`, `#productivity`, `#workflow`, `#session-management`

---

<a id="item-tech-news-4"></a>
### [AWS Releases Official Emulator for Local Testing](https://simonwillison.net/2026/Nov/11/aws-emulator/) ⭐️ 8.0/10

AWS has released an official emulator called aws-emulator that allows developers to run tests against local clones of AWS services without requiring paid API keys. The emulator is written in Rust and has seen substantial development activity with 29,684 commits in its first three weeks. Currently, it requires Docker to run on macOS or Windows platforms.

rss · Simon Willison · Nov 11, 21:18

**「Background」** Prior to the official AWS emulator, developers faced challenges testing applications locally without either using third-party mocking tools or provisioning paid AWS credentials. This created barriers for testing during development and increased costs for small projects and individual developers. The release of an official emulator represents AWS&\#x27;s recognition of this developer pain point and their commitment to providing better testing tools within the ecosystem.

**「Development Acceleration」** The AWS Emulator enables developers to test applications against AWS services locally without requiring paid credentials, significantly reducing development costs and accelerating testing cycles. However, the current Docker requirement for macOS and Windows may limit accessibility across different development environments.

<details><summary>References</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/aws/test-your-applications-against-aws-locally-with-aws-emulator/">Test your applications against AWS locally with AWS Emulator</a></li>
<li><a href="https://www.infoworld.com/article/4247383/aws-unveils-local-emulator-service-to-help-enterprises-accelerate-app-development-and-testing.html">AWS unveils local emulator service to help enterprises ...</a></li>
<li><a href="https://github.com/aws/aws-emulator">GitHub - aws/aws-emulator: AWS Emulator is a local emulator ...</a></li>

</ul>
</details>

**Tags**: `#aws`, `#testing`, `#development-tools`, `#rust`, `#emulator`

---

<a id="item-tech-news-5"></a>
### [Google AI Discovers Maya Pyramid with NASA Lidar](https://pietromiotti.com/latest/maya-site/?maya) ⭐️ 7.0/10

Google software engineers deployed 48 AI agents to analyze NASA Lidar data, identifying a previously unmapped Maya pyramid in just 72 hours. The AI system processed aerial LiDAR scans to detect subtle topographical features indicative of ancient Mayan architecture. This discovery demonstrates the potential of AI to accelerate archaeological discoveries by rapidly analyzing large geospatial datasets.

hackernews · eyvindn · Nov 11, 12:05 · [Discussion](https://news.ycombinator.com/item?id=50452455)

**「Background」** LiDAR \(Light Detection And Ranging\) technology has revolutionized archaeology by using laser pulses to penetrate dense jungle canopies and reveal hidden ancient structures beneath the surface. Previous discoveries using this technology have uncovered numerous Mayan sites, including the &\#x27;Megalopolis&\#x27; below the Guatemalan jungle and iconic pyramids like Calakmul in Campeche, Mexico. The application of AI agents to analyze these massive Li datasets represents a new frontier in archaeological discovery, potentially accelerating the identification of previously unknown sites.

**「Archaeological Capacity Challenge」** The use of AI to rapidly analyze Lidar data is accelerating archaeological discoveries at an unprecedented pace, but creating a significant capacity challenge for archaeologists who must verify and protect these sites. As noted by TSiege, &\#x27;Finding discoveries like this is essentially as hard as doing the lidar mapping,&\#x27; and the ability to find dozens or hundreds of sites quickly may overwhelm available archaeological resources, potentially leaving newly discovered sites vulnerable.

**「Community Discussion」** Community members noted that while the AI discovery is exciting, there are concerns about human capacity to follow up on numerous potential sites, as TSiege pointed out that &\#x27;finding discoveries like this is essentially as hard as doing the lidar mapping.&\#x27; Additionally, chirau expressed skepticism about AI-generated discoveries without expert archaeological verification.

<details><summary>References</summary>
<ul>
<li><a href="https://education.nationalgeographic.org/resource/exclusive-laser-scans-reveal-maya-megalopolis-below-guatemalan-jungle/10th-grade/">Exclusive: Laser Scans Reveal Maya “Megalopolis” Below Guatemalan...</a></li>
<li><a href="https://www.tiktok.com/discover/mayan-pyramid-lidar-scan">Mayan Pyramid Lidar Scan | TikTok</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Archaeology`, `#Lidar`, `#Discovery`, `#Technology`

---

<a id="item-tech-news-6"></a>
### [Voltage Glitching Unlocks NVIDIA A100 Features in Mining Cards](https://blog.kate.land/posts/using-voltage-glitching-to-unlock-the-a100/) ⭐️ 7.0/10

A detailed technical guide demonstrates how to use voltage glitching to bypass manufacturer-imposed limitations on NVIDIA A100 GPUs within mining cards, effectively unlocking disabled features. The technique involves manipulating voltage levels to trigger hardware-level bypasses of fuses that normally restrict functionality, potentially transforming lower-cost mining cards into more capable enterprise-grade GPUs. The process requires specialized hardware knowledge and carries significant risk of permanent damage to the components.

hackernews · lae · Nov 11, 10:48 · [Discussion](https://news.ycombinator.com/item?id=50451903)

**「Background」** The NVIDIA A100 is a data center GPU built on NVIDIA&\#x27;s Ampere architecture, released in 2020, which became the standard for AI model training from 2020 through 2023. Voltage glitching is a hardware hacking technique that involves precisely timed fluctuations in a device&\#x27;s supply voltage to disrupt normal operation and potentially bypass security features or unlock disabled functionality. This technique is being applied to mining cards containing A100 GPUs that have certain features disabled, likely to differentiate them from more expensive enterprise versions.

**「Hardware Security Implications」** This voltage glitching technique voids manufacturer warranties and creates potential security vulnerabilities by bypassing hardware-level restrictions, while also raising concerns about compliance with GPU export controls that regulate powerful processors like the A100.

**「Community Insights」** Commenters noted the historical context of manufacturers disabling features on high-spec components, with one suggesting that NVIDIA may have disabled features due to fabrication faults rather than purely artificial segmentation. Others discussed alternative approaches including using external PCIe risers with separate power supplies to speed up the process, while some expressed concerns about the risks involved in hardware modification.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ampere_%28microarchitecture%29">Ampere (microarchitecture) - Wikipedia A100 40GB vs 80GB: VRAM, Bandwidth &amp; MIG Compared for GPU ... A100 PCIe vs SXM in 2026: Single-GPU vs Multi-GPU Scaling ... NVIDIA A100 GPU — Specs, MIG, NVLink &amp; Use Cases NVIDIA H100 Specs: PCIe vs SXM vs NVL Compared (2026) NVIDIA A100 PCIe vs SXM: Comprehensive Performance Comparison</a></li>
<li><a href="https://www.thundercompute.com/blog/nvidia-a100-specs-full-guide">NVIDIA A100 Specs: 40GB vs 80GB, PCIe vs SXM (2026)</a></li>
<li><a href="https://riverloopsecurity.com/blog/2020/10/hw-101-glitching/">Hardware Hacking 101: Glitching into Privileged Shells</a></li>
<li><a href="https://www.synacktiv.com/en/publications/how-to-voltage-fault-injection">How to voltage fault injection - Synacktiv</a></li>
<li><a href="https://laptopjudge.com/what-is-gpu-export-control-impact/">What Is GPU Export Control Impact? - LaptopJudge</a></li>
<li><a href="https://www.gtlaw.com/en/insights/2026/9/navigating-gpu-export-controls-and-ai-use-restrictions-in-data-center-operations">Navigating GPU Export Controls and AI Use Restrictions in ...</a></li>

</ul>
</details>

**Tags**: `#hardware-hacking`, `#gpu-modification`, `#voltage-glitching`, `#nvidia-a100`, `#hardware-security`

---

<a id="item-tech-news-7"></a>
### [Anthropic&\#x27;s IPO roadshow video](https://simonwillison.net/2026/Nov/11/anthropic-ipo-roadshow/) ⭐️ 7.0/10

Anthropic&\#x27;s IPO roadshow reveals their unconventional multi-chip strategy for training and serving Claude across AWS Trainium, Google TPUs, NVIDIA GPUs, and AMD GPUs.

rss · Simon Willison · Nov 11, 15:11

**Tags**: `#AI/ML`, `#Cloud Computing`, `#Hardware`, `#Business`, `#IPO`

---

<a id="item-tech-news-8"></a>
### [AMD AI Memory Migration Cuts Server Costs](https://www.theregister.com/systems/2026/11/11/amd-where-were-going-we-dont-need-as-much-dram/5308953) ⭐️ 7.0/10

AMD has introduced AI-powered memory page migration technology that moves cold memory pages from DRAM to NVMe flash storage, potentially reducing server costs by up to 83% while maintaining up to 99% performance. This technology, based on AMD&\#x27;s acquisition of Mext, requires purchasing Epyc servers with Mext licensing and operates transparently to the operating system or applications.

telegram · zaihuapd · Nov 11, 11:15

**「Memory Management Fundamentals」** Memory pages are fixed-size blocks of data that form the basic units of memory management in modern operating systems. DRAM \(Dynamic Random Access Memory\) is the primary server memory type that offers high speed but at a premium cost, while NVMe flash storage provides a more economical but slower alternative for data persistence. The concept of &\#x27;cold&\#x27; memory pages refers to memory blocks that haven&\#x27;t been accessed recently and are candidates for being moved to slower, less expensive storage without significantly impacting system performance.

**「Impact」** Organizations deploying AMD Epyc servers with this technology could significantly reduce their capital expenditure on memory while maintaining near-original performance levels, though the initial investment requires purchasing the specific licensed hardware.

**Tags**: `#memory-management`, `#server-optimization`, `#AI-hardware`, `#cost-reduction`, `#amd-technology`

---

<a id="item-tech-news-9"></a>
### [ByteDance Plans $700B Investment in AI Assistant to Compete with OpenAI](https://www.bloomberg.com/news/articles/2026-11-11/bytedance-prepares-muse-like-agent-in-push-to-close-ai-gap) ⭐️ 7.0/10

ByteDance plans to release a Meta Muse-like AI assistant in the coming weeks, investing up to $700 billion to develop the &\#x27;Seedance&\#x27; video AI platform. Co-founder Zhang Yiming announced the goal to catch up with Anthropic and OpenAI by 2029-2030 during an all-hands meeting with the AI team. The company aims to consolidate its leading position in AI video technology without relying on model distillation.

telegram · zaihuapd · Nov 11, 12:31

**「Background」** Meta Muse appears to be an existing AI assistant model that ByteDance aims to emulate with their new offering. The significant $700 billion investment indicates ByteDance&\#x27;s recognition of the substantial gap between their current AI capabilities and those of leading US research labs like OpenAI and Anthropic. This strategic move comes as ByteDance seeks to establish itself as a major player in the competitive AI landscape, particularly in video AI applications.

**「Industry Impact」** This unprecedented $700 billion investment represents the largest commitment to AI video technology development to date, positioning ByteDance as a major competitor to OpenAI and Anthropic in the race to advance AI assistants.

**Tags**: `#AI Strategy`, `#Large Tech Companies`, `#Video AI`, `#Investment`, `#Competitive Landscape`

---

## Technology Blog

<a id="item-tech-blog-1"></a>
### [vLLM&\#x27;s EPD Architecture for Multimodal Scaling](https://vllm.ai/blog/2026-11-11-encoder-disaggregation-epd) ⭐️ 9.0/10

rss · vLLM Blog · Nov 11, 00:00

**「Background」** Multimodal inference adds an encoding stage before language-model execution, where images, video, and audio must be processed into embeddings. The demand on this encoding stage varies independently of prefill and decode demand, making it challenging to scale efficiently with traditional monolithic architectures.

**「Solution」** vLLM&\#x27;s Encoder/Prefill/Decode \(EPD\) disaggregation separates these stages into independently deployed instances. Key innovations include metadata-only requests that avoid duplicate preprocessing by transferring structural information rather than raw media; a dedicated encoder execution path with Model Runner V2 that optimizes GPU usage; remote embedding transfer through NIXL and Mooncake; cross-encoder output reuse via Mooncake Store; and reduced orchestration overhead in the Python EPD proxy. This architecture supports two deployment patterns: E+PD \(separate encoder with combined prefill/decode\) and E/P/D \(all three stages separate\). In testing, EPD delivered 6.6-9.5% higher throughput per GPU and 44-47% lower P90 TTFT with DeepSeek V4.1 Flash at higher concurrency levels.

**「Takeaway」** EPD disaggregation enables independent scaling of multimodal encoding, prefill, and decode stages, allowing operators to optimize resource allocation based on workload characteristics and significantly improving performance for multimodal inference workloads.

**Tags**: `#multimodal-inference`, `#model-serving`, `#system-optimization`, `#encoder-disaggregation`, `#vllm`

---

<a id="item-tech-blog-2"></a>
### [AI Doesn&\#x27;t Make Glue Work Valuable](https://seangoedecke.com/glue-work-is-still-harmful-in-the-age-of-ai/) ⭐️ 5.0/10

rss · Sean Goedecke · Nov 11, 00:00

**「Background」** The author argues that glue work - unrewarded coordination tasks that sustain engineering processes - remains harmful even in the age of AI, contrary to expectations that AI might increase such work.

**「Solution」** The author presents four reasons why AI has actually reduced the importance of glue work: first, AI decreases coordination needs as single engineers can now handle projects that previously required teams; second, difficult engineers with outsized influence have been forced out or changed their attitudes; third, companies are hiring fewer juniors, reducing onboarding needs; and fourth, write-only reports can be automated with LLMs. However, the author cautions that not all glue work can be automated, as communication between engineers still requires human touch and delegating such interactions to AI would damage relationships.

**「Takeaway」** Engineers should still avoid becoming &\#x27;the glue work person,&\#x27; let bad processes fail, but be willing to do small amounts of tactical glue work when it contributes to project success, focusing most effort on code and directing AI agents.

**Tags**: `#software-engineering`, `#ai-impact`, `#team-dynamics`, `#productivity`, `#career-advice`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Fed Reacts to Higher-Than-Expected October Inflation](https://www.cnbc.com/2026/11/11/goolsbee-october-inflation-fed-rates-disturbing-distressing.html) ⭐️ 7.0/10

Chicago Fed President Goolsbee called the October inflation report &\#x27;borderline disturbing&\#x27; after the consumer price index rose 0.4%, higher than expected and marking the third straight month of outsized increases, with multiple Fed officials signaling potential for more aggressive rate hikes.

rss · CNBC Finance · Nov 11, 16:49

**「Background」** The Federal Reserve had raised rates by a quarter point in September to 3.75%-4% before holding steady in October, but the persistent inflation has led officials to consider further tightening.

**「Impact」** Higher interest rates would increase borrowing costs for consumers and businesses, potentially slowing economic activity but aiming to reduce inflationary pressures.

**Tags**: `#monetary-policy`, `#inflation`, `#interest-rates`, `#federal-reserve`, `#economic-data`

---

<a id="item-finance-news-2"></a>
### [Alibaba Plans Hong Kong Listing for Semiconductor Unit T-Head](https://www.cnbc.com/2026/11/11/alibaba-pr.html) ⭐️ 7.0/10

Alibaba announced plans to list its semiconductor subsidiary T-Head on the Hong Kong Stock Exchange, amid growing U.S. restrictions on China&\#x27;s access to advanced AI chips.

rss · CNBC Finance · Nov 11, 07:47

**「Background」** T-Head is Alibaba&\#x27;s semiconductor subsidiary founded in 2018 that designs processors and AI accelerators, with this listing coming amid China&\#x27;s broader efforts to develop homegrown chips amid U.S. restrictions on advanced technology access.

**「Impact」** The move could strengthen China&\#x27;s domestic semiconductor industry as Chinese companies face increasing U.S. limitations on accessing advanced chips.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/T-head">T-head - Wikipedia T-Head Semiconductor | nextomoro Pingtouge Semiconductor Co., Ltd（semiconductor company）_Baiduwi... T-Head Semiconductor Co., Ltd. (Pingtouge) — Company Profile ... T-Head - Wikiwand Alibaba T-Head | China Chip Stack</a></li>
<li><a href="https://nextomoro.com/alibaba-t-head/">T-Head Semiconductor | nextomoro</a></li>
<li><a href="https://baike.baidu.com/en/item/Pingtouge+Semiconductor+Co.,+Ltd/22993">Pingtouge Semiconductor Co., Ltd（semiconductor company）_Baiduwi...</a></li>

</ul>
</details>

**Tags**: `#Corporate Strategy`, `#Semiconductor Industry`, `#Chinese Tech`, `#IPO`, `#US-China Tech Tensions`

---

<a id="item-finance-news-3"></a>
### [离岸信托收益征税过渡期结束，累计申报超 1600 亿元](https://www.news.cn/20261111/9bcce99c779b4a6197ff45bbbc3e4c50/c.html) ⭐️ 7.0/10

China&\#x27;s offshore trust income tax transition period ended with over 160 billion yuan in declared taxes, significantly boosting government revenue.

telegram · zaihuapd · Nov 11, 10:35

**Tags**: `#Tax policy`, `#Offshore finance`, `#Wealth management`, `#Government revenue`, `#Regulatory compliance`

---

<a id="item-finance-news-4"></a>
### [Alleged $7.5B NVIDIA Chip Import Circumvention](https://www.tomshardware.com/tech-industry/policy/alice-huang-reportedly-instrumental-in-securing-over-usd7-5-billion-of-nvidia-ai-gpu-imports-during-three-year-relationship-with-jensen-huang-helped-move-240-000-banned-chips-into-china-mostly-h100-and-h200) ⭐️ 7.0/10

According to an investigation by The Information, Alice Huang allegedly helped import 240,000 banned NVIDIA AI chips worth $7.5 billion into China, potentially circumventing US export controls.

telegram · zaihuapd · Nov 11, 14:41

**「Background」** US export controls restrict advanced AI chips like NVIDIA&\#x27;s H100 and H200 from being sold to certain Chinese entities without special approval, which are typically denied for organizations linked to China&\#x27;s military.

**「Impact」** This alleged circumvention could significantly impact US-China tech trade relations and AI development capabilities in China.

<details><summary>References</summary>
<ul>
<li><a href="https://www.straitstimes.com/world/pla-linked-chinese-university-bought-nvidia-h200-chips-despite-us-blacklist-records-show">PLA-linked Chinese university bought Nvidia H 200 chips</a></li>
<li><a href="https://www.dailymotion.com/video/x9xq0ss">US Greenlights Nvidia H 200 AI Chip Sales to China , With Restrictions</a></li>

</ul>
</details>

**Tags**: `#US-China trade`, `#AI chips`, `#Export controls`, `#NVIDIA`, `#Tech policy`

---