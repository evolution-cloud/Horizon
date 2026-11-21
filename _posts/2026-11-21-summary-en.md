---
layout: default
title: "Horizon Summary: 2026-11-21 (EN)"
date: 2026-11-21
lang: en
---

> From 24 items, 9 important content pieces were selected

---

**Technology News**
1. [Lean verification of the Riemann Hypothesis](#item-tech-news-1) ⭐️ 9.0/10
2. [Critical GPGME Double Free Vulnerability Disclosed](#item-tech-news-2) ⭐️ 8.0/10
3. [🤖 OpenAI 加强反蒸馏防护，提取成功率降至 0.2%](#item-tech-news-3) ⭐️ 8.0/10
4. [TSMC Halts Advanced Chip Shipments to China Due to Export Controls](#item-tech-news-4) ⭐️ 8.0/10
5. [Microsoft Enables Multi-PC AI Model Sharing via USB4](#item-tech-news-5) ⭐️ 8.0/10
6. [Zhejiang University First to Implement QRAM on Quantum Chip](#item-tech-news-6) ⭐️ 8.0/10
7. [Monitor&\#x27;s USB Hub Causing 75% Network Speed Reduction](#item-tech-news-7) ⭐️ 7.0/10
8. [OpenRouter 警告 MiniMax 模型提示词疑遭第三方读取](#item-tech-news-8) ⭐️ 7.0/10

**Technology Blog**
1. [Why Output Caching Doesn&\#x27;t Work for LLMs](#item-tech-blog-1) ⭐️ 8.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Lean verification of the Riemann Hypothesis](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/) ⭐️ 9.0/10

A formal verification of the Riemann Hypothesis using Lean proof assistant, potentially representing a major breakthrough in mathematics and formal methods.

hackernews · g-b-r · Nov 21, 14:36 · [Discussion](https://news.ycombinator.com/item?id=50589618)

**Tags**: `#formal\_verification`, `#mathematics`, `#ai`, `#lean`, `#proof\_assistants`

---

<a id="item-tech-news-2"></a>
### [Critical GPGME Double Free Vulnerability Disclosed](https://lists.gnupg.org/pipermail/gnupg-announce/2026q4/000517.html) ⭐️ 8.0/10

A critical double free vulnerability in the GPGME library \(versions prior to 2.3.0\) has been disclosed, affecting numerous systems including GitLab, mail clients, XMPP clients, Samba, and Flatpack. The vulnerability, discovered by Johan Carlsson and initially scheduled for coordinated disclosure on 2026-11-25, was disclosed early on 2026-11-20 due to an unrelated update in GitLab. Red Hat reportedly fixed this issue five years ago, but the patch was not incorporated upstream.

hackernews · gdgghhhhh · Nov 21, 08:32 · [Discussion](https://news.ycombinator.com/item?id=50587208)

**「Background」** GPGME \(GnuPG Made Easy\) is a library designed to simplify the integration of GnuPG encryption and digital signature functionality into other applications. The critical vulnerability CVE-2026-129975 is a double free issue in the read\_status\(\) and read\_colon\_line\(\) routines that process status lines and key listings from GnuPG. This flaw can be exploited to exfiltrate data from applications through specially crafted signed data, and while remote code execution hasn&\#x27;t been confirmed, it cannot be ruled out, making this a serious security concern for all applications using affected versions of GPGME.

**「Potential Impact」** The vulnerability could potentially lead to remote code execution in contexts where signed commits or security-sensitive operations are performed, particularly affecting GitLab&\#x27;s signed commit feature which could allow attackers to execute code within the application environment.

**「Community Discussion」** There is debate in the community about whether this vulnerability actually enables remote code execution or is merely a double free bug, with mik1998 questioning if vulnerability reports are intentionally overstated while dehrmann suggests that C/C++ development requires better tooling to prevent such issues.

<details><summary>References</summary>
<ul>
<li><a href="https://thehackernews.com/2026/11/gnupg-warns-critical-gpgme-flaw-could.html">GnuPG Warns Critical GPGME Flaw Could Expose App Data via...</a></li>
<li><a href="https://lists.gnupg.org/pipermail/gnupg-announce/2026q4/000517.html">[Announce] GnuPG Security Advisory for GPGME ...</a></li>
<li><a href="https://techora.ru/news/v-gpgme-kriticheskaya-uyazvimost-utechka-dannykh-2026-11-21">В GPGME критическая уязвимость: утечка данных и RCE для...</a></li>

</ul>
</details>

**Tags**: `#security`, `#vulnerability`, `#gnupg`, `#gpgme`, `#software-engineering`

---

<a id="item-tech-news-3"></a>
### [🤖 OpenAI 加强反蒸馏防护，提取成功率降至 0.2%](https://openai.com/index/combatting-adversarial-distillation/) ⭐️ 8.0/10

OpenAI has enhanced protection against adversarial distillation, reducing extraction success rates from 54% to 0.2% in their latest models.

telegram · zaihuapd · Nov 21, 01:30

**Tags**: `#AI security`, `#model protection`, `#adversarial distillation`, `#OpenAI`, `#privacy protection`

---

<a id="item-tech-news-4"></a>
### [TSMC Halts Advanced Chip Shipments to China Due to Export Controls](https://appleinsider.com/articles/26/11/20/apple-supplier-tsmc-cuts-off-china-chip-orders-amid-tighter-export-controls) ⭐️ 8.0/10

TSMC has paused accepting orders for 16nm and below advanced process chips from Chinese companies due to tightened US semiconductor export regulations. Under the new rules, shipments require prior US export licenses or exemptions, which Chinese companies currently lack, forcing them to rely on older 28nm and 40nm processes. This restriction directly impacts AI data center capabilities that require high-bandwidth memory chips. Previously, TSMC could independently evaluate if customer designs qualified for exemptions, but now customers must proactively apply for approval.

telegram · zaihuapd · Nov 21, 02:01

**「Background」** The US Commerce Department implemented new export control regulations on November 19, 2026, that removed previous evaluation pathways for determining whether certain Chinese chip designs fell outside export restrictions. Previously, TSMC could independently assess the computing power and technical characteristics of Chinese chip designs to determine compliance, but the new policy requires customers to obtain US export licenses in advance for any 16nm and below advanced process chips. This 16nm threshold is particularly significant as it represents the cutting-edge node technology required for modern AI data centers and high-performance computing applications.

**「Impact on Chinese AI Development」** Chinese companies will be limited to older process nodes \(28nm, 40nm\) instead of advanced 16nm and below chips, directly affecting AI data center capabilities that require high-bandwidth memory. This restriction is prompting Chinese tech firms like Alibaba and Tencent to accelerate domestic semiconductor development and reassess their computing plans amid intensifying technology tensions.

<details><summary>References</summary>
<ul>
<li><a href="https://effectstory.com/en/articles/tsmc-halts-china-16nm-orders-new-us-chip-rule">TSMC reportedly halts China chip orders at 16nm and below</a></li>
<li><a href="https://www.reuters.com/world/china/tsmc-tightens-china-ai-chip-curbs-new-us-rules-close-manufacturing-loophole-2026-11-19/">TSMC tightens China AI chip curbs as new US rules close ...</a></li>
<li><a href="https://www.reuters.com/business/retail-consumer/us-ai-chip-curbs-hit-china-tech-stocks-spur-self-sufficiency-push-2026-11-20/">US AI chip curbs hit China tech stocks, spur self-sufficiency ...</a></li>
<li><a href="https://www.analyticsinsight.net/news/us-ai-chip-curbs-hit-china-tech-stocks-push-self-reliance-drive">US AI Chip Curbs Hit China Tech Stocks, Push Self-Reliance Drive</a></li>

</ul>
</details>

**Tags**: `#semiconductor-manufacturing`, `#ai-hardware`, `#geopolitics-tech`, `#supply-chain`, `#china-tech`

---

<a id="item-tech-news-5"></a>
### [Microsoft Enables Multi-PC AI Model Sharing via USB4](https://videocardz.com/newz/microsoft-brings-rdma-over-usb4-to-windows-allowing-multiple-pcs-to-run-one-local-ai-model) ⭐️ 8.0/10

Microsoft has released a developer preview of RDMA over USB4 for Windows, allowing multiple PCs to connect via standard USB4 cables to share memory and GPU compute power for running the same local large AI model without specialized networking equipment. Three AMD Ryzen AI Max+ 395 PCs achieved approximately 18.5 tokens/second when running a 4-bit quantized Qwen3-235B-A22B model, with this feature planned for release through Windows Insider.

telegram · zaihuapd · Nov 21, 06:13

**「Background」** RDMA \(Remote Direct Memory Access\) is a networking technology that allows computers to directly access each other&\#x27;s memory without involving the central processor, significantly reducing latency and improving performance for data-intensive applications. This capability is particularly valuable for distributed computing and AI workloads where efficient resource sharing between multiple machines is critical for processing large models that exceed the capacity of a single system.

**「Democratizing AI Computing」** Microsoft&\#x27;s RDMA over USB4 implementation democratizes distributed AI computing by enabling multiple standard PCs to collaboratively run large AI models without specialized networking equipment, significantly lowering the barrier to entry for organizations and researchers working with AI models that would otherwise require expensive infrastructure.

<details><summary>References</summary>
<ul>
<li><a href="https://habr.com/ru/articles/1110636/">Microsoft представила решение на базе USB 4 и RDMA для... / Хабр</a></li>
<li><a href="https://www.mdpi.com/2076-3417/14/18/8236">The Democratization of Artificial Intelligence: Theoretical ...</a></li>

</ul>
</details>

**Tags**: `#distributed-computing`, `#AI-inference`, `#hardware-innovation`, `#microsoft`, `#performance-optimization`

---

<a id="item-tech-news-6"></a>
### [Zhejiang University First to Implement QRAM on Quantum Chip](https://finance.sina.com.cn/stock/2026-11-21/doc-iniznhsk3530826.shtml) ⭐️ 8.0/10

Zhejiang University has achieved the world&\#x27;s first real-machine implementation of Quantum Random Access Memory \(QRAM\) on their &\#x27;Tianmu 2&\#x27; superconducting quantum chip, a breakthrough published in Nature Physics. The prototype successfully retrieved 4-bit and 8-bit data with accuracies of 80.9% and 60.4% respectively, while reducing circuit depth by over 30% compared to unoptimized solutions. The team also verified that the architecture possesses local noise resistance properties, with plans to advance QRAM research toward larger-scale implementations.

telegram · zaihuapd · Nov 21, 08:31

**「Background」** Quantum Random Access Memory \(QRAM\) is a critical component for quantum computing that enables efficient data access and retrieval in quantum systems. Unlike classical memory, QRAM allows quantum computers to access data in superposition states, which is essential for running complex quantum algorithms and processing large datasets in quantum machine learning applications.

**「Quantum Computing Advancement」** This real-machine QRAM implementation significantly advances practical quantum computing by providing a crucial memory component that was previously only theoretical, with demonstrated performance metrics \(80.9% and 60.4% accuracy for 4-bit and 8-bit data\) and 30%+ circuit depth reduction bringing quantum systems closer to handling real-world applications.

<details><summary>References</summary>
<ul>
<li><a href="https://interestingengineering.com/innovation/quantum-router-achieves-98-transmission-efficiency-in-chinas-wukong-tests">China’s quantum router breakthrough hits 98% transmission efficiency</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#hardware`, `#memory`, `#research`, `#breakthrough`

---

<a id="item-tech-news-7"></a>
### [Monitor&\#x27;s USB Hub Causing 75% Network Speed Reduction](https://blog.tymscar.com/posts/studiodisplayethernet/) ⭐️ 7.0/10

A detailed investigation revealed that a monitor&\#x27;s USB hub was causing a 75% reduction in network download speed due to packet acknowledgment latency. The extra delay from passing network traffic through the monitor prevented the laptop from acknowledging packets quickly enough, causing the ethernet adapter buffer to fill and packets to drop. The issue was resolved by using a different ethernet adapter that required less frequent acknowledgment.

hackernews · soheilpro · Nov 21, 10:36 · [Discussion](https://news.ycombinator.com/item?id=50587875)

**「USB Hub Network Performance」** USB hubs can introduce latency that significantly impacts network performance, particularly when handling packet acknowledgments. The technical relationship between USB hubs and network connectivity has been documented in various troubleshooting guides, with some users experiencing substantial bandwidth reductions due to the additional processing time required for data passing through hub chipsets. This issue becomes particularly noticeable with high-speed connections where packet acknowledgment timing is critical for maintaining throughput.

**「Network Performance Impact」** Users with high-speed internet connections who route their network through monitor USB hubs may experience significant speed reductions \(up to 75%\) due to packet acknowledgment latency issues. This occurs when the extra latency from the monitor&\#x27;s USB hub prevents the laptop from acknowledging packets quickly enough, causing the ethernet adapter buffer to fill and packets to drop. Users experiencing this issue should consider using a direct ethernet connection or an adapter that requires less frequent acknowledgment.

**「Technical Explanation」** User fancyfredbot clarified that the extra latency from going through the monitor meant the laptop couldn&\#x27;t acknowledge packets quickly enough, causing buffer fill and packet drops. They noted this is &\#x27;a nice post which gets to the bottom of incredibly opaque behaviour of USB hubs.&\#x27;

<details><summary>References</summary>
<ul>
<li><a href="https://www.anker.com/blogs/hubs-and-docks/do-usb-hubs-add-latency">Do USB Hubs Add Latency? How to Lessen It? - Anker US</a></li>
<li><a href="https://www.purplelec.com/info-detail/usb-hub-delay-optimization">Does a USB Hub Add Latency? Deep Dive into Performance &amp; 7 ...</a></li>
<li><a href="https://laptopjudge.com/monitor-usb-hub-ethernet-dropouts/">Monitor USB Hub Ethernet Dropouts (Bandwidth Fix) - LaptopJudge</a></li>

</ul>
</details>

**Tags**: `#network-performance`, `#usb-hub`, `#hardware-issues`, `#troubleshooting`, `#computer-systems`

---

<a id="item-tech-news-8"></a>
### [OpenRouter 警告 MiniMax 模型提示词疑遭第三方读取](https://news.ycombinator.com/item?id=50585962) ⭐️ 7.0/10

OpenRouter warns that prompts sent to MiniMax models may have been accessed by third parties due to a security vulnerability.

telegram · zaihuapd · Nov 21, 06:53

**Tags**: `#AI security`, `#data privacy`, `#API security`, `#prompt injection`, `#vulnerability`

---

## Technology Blog

<a id="item-tech-blog-1"></a>
### [Why Output Caching Doesn&\#x27;t Work for LLMs](https://seangoedecke.com/why-output-caching-doesnt-work/) ⭐️ 8.0/10

rss · Sean Goedecke · Nov 21, 00:00

**「Background」** While input caching is essential for LLM inference economics to prevent recomputing conversation history, the author explores why output caching might seem beneficial but ultimately proves ineffective.

**「Solution」** The author reveals that only about 6% of LLM output tokens are visible to users, with 50% being reasoning tokens and 44% being tool calls. Applying Amdahl&\#x27;s law, even an optimistic 67% reduction in visible output tokens would only yield 4% total savings. The real opportunity lies in reducing the 94% of invisible tokens, which depends on model intelligence - more expensive models can actually be cheaper to use as they require fewer tokens to reach correct answers.

**「Takeaway」** Output caching offers minimal benefits for LLMs because it optimizes only the small visible portion of output, while the substantial savings come from improving model intelligence to reduce reasoning and tool call tokens.

**Tags**: `#LLM optimization`, `#Token economics`, `#Caching strategies`, `#Model efficiency`, `#Cost analysis`

---