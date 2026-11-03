---
layout: default
title: "Horizon Summary: 2026-11-03 (EN)"
date: 2026-11-03
lang: en
---

> From 41 items, 18 important content pieces were selected

---

**Technology News**
1. [vLLM v0.33.0rc3 Released with New Models and CUDA 13.0 Transition](#item-tech-news-1) ⭐️ 8.0/10
2. [Astra Edits Neural Weights to Improve Qwen Math 5x](#item-tech-news-2) ⭐️ 8.0/10
3. [Ubuntu delays patch for critical Linux kernel RCE vulnerability](#item-tech-news-3) ⭐️ 8.0/10
4. [Show HN: Subvocal – Talk to your computer without making noise](#item-tech-news-4) ⭐️ 8.0/10
5. [LongCat-2.5: 1.6 Trillion Parameter Native Multimodal Model Released](#item-tech-news-5) ⭐️ 8.0/10
6. [400+ AI Apps Hide Pornographic Deepfake Features](#item-tech-news-6) ⭐️ 8.0/10
7. [SGLang v0.5.23 Adds 9 New Models with Performance Improvements](#item-tech-news-7) ⭐️ 7.0/10
8. [Updated Linux System Call Website Adds Architectures and API](#item-tech-news-8) ⭐️ 7.0/10
9. [WTF Ubuntu?](#item-tech-news-9) ⭐️ 7.0/10
10. [LLM 0.37 Release Adds New Models and Configuration Improvements](#item-tech-news-10) ⭐️ 7.0/10
11. [The U.S. Census Bureau and “Super Intelligence”](#item-tech-news-11) ⭐️ 7.0/10
12. [GDPx Benchmark Measures AI Capabilities in High-Value Domains](#item-tech-news-12) ⭐️ 7.0/10
13. [ChatGPT Sharing Link Vulnerability Patched](#item-tech-news-13) ⭐️ 7.0/10
14. [Tesla China App Shows FSD Statistics Page](#item-tech-news-14) ⭐️ 7.0/10

**Technology Blog**
1. [LLMs Not Superhuman at Neural Network Weight Manipulation](#item-tech-blog-1) ⭐️ 8.0/10
2. [Audience Capture](#item-tech-blog-2) ⭐️ 7.0/10

**Financial News**
1. [Anthropic Reports Massive Revenue Growth Despite Huge Losses](#item-finance-news-1) ⭐️ 7.0/10
2. [UK Proposes Extending Migrant Settlement Period to 10 Years](#item-finance-news-2) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [vLLM v0.33.0rc3 Released with New Models and CUDA 13.0 Transition](https://github.com/vllm-project/vllm/releases/tag/v0.33.0rc3) ⭐️ 8.0/10

vLLM v0.33.0rc3 is a major release candidate update featuring support for new large models including Reflection Beam-1.0, Yandex AliceAI-Foundation-80B-A3B, and Recursive Flint. The library has been upgraded to PyTorch 2.14.0 with torchvision 0.29.0 and Triton 3.8.0, and now requires CUDA 13.0 only, dropping support for CUDA 12.9. The release includes significant performance improvements in speculative decoding, NVIDIA decode optimization, and AMD ROCm support, along with breaking changes including the removal of Medusa and MLP speculator.

github · khluu · Nov 2, 10:10

**「Background」** vLLM is an open-source library designed for high-performance inference of large language models. This release candidate version 0.33.0 represents a significant update with substantial development activity, featuring 927 commits from 389 contributors, support for numerous new large models, major dependency upgrades including PyTorch 2.14, and important infrastructure changes such as transitioning to CUDA 13.0 only support.

**「CUDA Version Transition Required」** Organizations and developers using vLLM must upgrade from CUDA 12.9 to 13.0 as v0.33.0 no longer provides CUDA 12.9 wheels or images. This transition will require adjustments to existing infrastructure, particularly for production deployments that have been optimized for CUDA 12.9.

**Tags**: `#llm-inference`, `#pytorch-upgrade`, `#cuda-support`, `#model-support`, `#high-performance-computing`

---

<a id="item-tech-news-2"></a>
### [Astra Edits Neural Weights to Improve Qwen Math 5x](https://rikiyat.github.io/blog/weight-space-programming/) ⭐️ 8.0/10

Astra demonstrates the ability to directly edit neural network weights to significantly improve model performance, achieving 5x better math skills in Qwen. The technique, called weight-space programming, allows Astra to identify and modify specific weight directions that cause common failures in small reasoning models. Astra traced a looping behavior in Qwen to specific directions written by the MLPs of layers 15 and 19, then subtracted those directions from 64 output columns in each layer \(131,072 weights total\). This represents a shipped capability rather than just an announced plan, with concrete performance improvements demonstrated on actual model weights.

hackernews · dbreunig · Nov 2, 18:21 · [Discussion](https://news.ycombinator.com/item?id=50341174)

**「Weight-Space Programming」** Weight-Space Programming refers to the ability of AI models to directly read and modify neural network weights without traditional training loops or gradient-based optimization. This approach allows models to identify specific issues in their architecture and make targeted improvements. In the case of Qwen, a large language model that struggled with mathematical reasoning and tended to loop \(repeating text without reaching answers\), Astra was able to pinpoint the exact weights causing this problem and modify just 0.016% of them to achieve a 5x improvement in math skills.

**「Practical Implications」** This direct weight editing capability could fundamentally change how AI models are optimized and debugged, potentially allowing developers to surgically fix specific model failures without full retraining. The approach may enable more efficient model maintenance and targeted improvements to specialized capabilities like mathematical reasoning.

**「Community Reactions」** The community reaction ranges from shock to recognition of this as part of a broader pattern where LLMs demonstrate rapid comprehension of complex systems. Some commenters suggest this might be an emergent capability from training on neural weights data, potentially related to recursive self-improvement attempts, while others note it aligns with LLMs&\#x27; demonstrated ability to quickly understand and explain complex systems like legacy codebases.

<details><summary>References</summary>
<ul>
<li><a href="https://rikiyat.github.io/blog/weight-space-programming/">Sparks of Weight - Space Programming : LLMs can natively read...</a></li>
<li><a href="https://news.ycombinator.com/item?id=50341174">Astra can read and write weights to improve Qwen | Hacker News</a></li>

</ul>
</details>

**Tags**: `#neural-networks`, `#ai-optimization`, `#llm`, `#model-editing`, `#weight-space-programming`

---

<a id="item-tech-news-3"></a>
### [Ubuntu delays patch for critical Linux kernel RCE vulnerability](https://freenode.net/article/ubuntu-lts-kernels-still-unfixed-for-critical-cve-2026-98432) ⭐️ 8.0/10

Ubuntu has not yet released a patch for the critical CVE-2026-98432 Linux kernel remote code execution vulnerability affecting its LTS systems for nearly three weeks, leaving systems vulnerable to potential exploitation. The vulnerability was first reported on November 2, 2026, and affects Ubuntu&\#x27;s Long Term Support kernels, which are widely used in production environments. Despite the severity of the RCE vulnerability, Ubuntu has not provided an official patch or timeline for resolution, forcing system administrators to either implement temporary workarounds or remain exposed to the security risk.

hackernews · majorchord · Nov 2, 18:39 · [Discussion](https://news.ycombinator.com/item?id=50341462)

**「Background」** CVE-2026-98432 is a critical use-after-free vulnerability in the Linux kernel&\#x27;s IPv4 networking subsystem that allows remote, unauthenticated attackers to execute arbitrary code by exploiting a race condition during TCP connection request processing. The vulnerability affects kernel versions 4.4 and later and has been resolved in the upstream kernel by ensuring proper freeing of inet\_opt and ireq\_opt after an RCU grace period in the tcp\_v4\_syn\_recv\_sock\(\) function. Ubuntu has acknowledged the vulnerability on their security page but has not yet released a patch for their LTS systems despite the critical nature of the flaw.

**「Administrative Challenges」** System administrators relying on Ubuntu LTS systems face increased security risks and operational challenges, with some users already considering switching distributions due to the delayed response, as noted by community members who expressed shaken faith in Ubuntu&\#x27;s security practices.

**「Community Reactions」** The community discussion includes both technical workarounds, such as using iptables or nftables to block the vulnerability before kernel patching, and concerns about Ubuntu&\#x27;s delayed response, with users questioning the official reasons for the delay and some expressing loss of confidence in the distribution&\#x27;s security practices.

<details><summary>References</summary>
<ul>
<li><a href="https://access.redhat.com/security/vulnerabilities/RHSB-2026-016">RHSB-2026-016 Use-after-free - kernel IPv4 (CVE-2026-98432 ...</a></li>
<li><a href="https://aws.amazon.com/security/security-bulletins/2026-160-aws/">CVE-2026-98432 - Linux kernel IPv4 TCP use-after-free ...</a></li>
<li><a href="https://ubuntu.com/security/CVE-2026-98432">CVE-2026-98432 | Ubuntu</a></li>

</ul>
</details>

**Tags**: `#security`, `#linux-kernel`, `#ubuntu`, `#cve`, `#system-administration`

---

<a id="item-tech-news-4"></a>
### [Show HN: Subvocal – Talk to your computer without making noise](https://news.ycombinator.com/item?id=50340088) ⭐️ 8.0/10

YC-backed startup Subvocal has developed smart glasses that use RF technology to decode silently mouthed words into text at the speed of speech.

hackernews · aarushyadav · Nov 2, 17:16

**Tags**: `#human-computer interaction`, `#wearable technology`, `#input devices`, `#accessibility`, `#RF technology`

---

<a id="item-tech-news-5"></a>
### [LongCat-2.5: 1.6 Trillion Parameter Native Multimodal Model Released](https://longcat.ai/blog/longcat-2.5/) ⭐️ 8.0/10

LongCat-2.5 introduces a 1.6 trillion parameter native multimodal model designed for long-range agent tasks, building upon LongCat-2.0 with enhanced visual understanding and agentic coding capabilities. The model encodes visual signals into multi-level discrete tokens for unified processing with text, enabling tasks like visual programming. Currently available for trial on the official website and via API, with GitHub and HuggingFace versions not yet open.

telegram · zaihuapd · Nov 2, 03:08

**「Background」** LongCat-2.5 represents an evolution in multimodal AI systems, building upon its predecessor LongCat-2.0. Multimodal models integrate different types of data inputs, such as visual and textual information, to enable more comprehensive understanding and processing capabilities. The 1.6 trillion parameter scale of LongCat-2.5 positions it among the largest AI models currently available, with approximately 480 billion parameters activated per token during processing. Its approach of encoding visual signals into discrete tokens for unified text processing represents a technical advancement in how AI systems can handle diverse data types simultaneously.

**「Impact」** The release provides developers with a powerful multimodal tool that could advance AI applications requiring both visual and text processing, particularly in programming assistance and visual understanding tasks, though access is currently limited to the official platform.

**Tags**: `#large-language-models`, `#multimodal-ai`, `#software-engineering`, `#ai-agents`, `#parameter-scale`

---

<a id="item-tech-news-6"></a>
### [400+ AI Apps Hide Pornographic Deepfake Features](https://www.wired.com/story/hundreds-of-mundane-ai-apps-are-hiding-abusive-deepfake-features/) ⭐️ 8.0/10

WIRED investigation revealed a network of 400+ AI applications and websites that conceal pornographic deepfake functionality behind legitimate services like pet portrait generation and language learning. These apps, which had collectively been downloaded over 350,000 times from Google Play alone, allowed users to upload photos of others to create explicit images and videos. Apple removed 19 apps after WIRED provided evidence that developers were changing remote content after approval, while Google had already removed most of the apps before being contacted.

telegram · zaihuapd · Nov 2, 12:45

**「Background」** Deepfake technology uses artificial intelligence to create realistic but fake images, videos, or audio that can depict people saying or doing things they never did. This investigation highlights how such technology is being misused to create non-consensual explicit content, raising serious ethical concerns about the deployment of AI applications without proper safeguards. The widespread availability of these deceptive apps on major app stores demonstrates significant gaps in content moderation and vetting processes for AI-powered tools.

**「Regulatory and Platform Response」** The discovery of 400+ AI apps hiding pornographic deepfake features has prompted tech platforms to remove offending applications, with Apple removing 19 apps and Google removing most others before being contacted, while Meta blocked 209 related apps from advertising. This incident highlights critical gaps in app store vetting processes and underscores the urgent need for stronger regulatory frameworks to address the growing problem of non-consensual intimate deepfakes, which constitute 96% of publicly available deepfake content according to research.

<details><summary>References</summary>
<ul>
<li><a href="https://www.igap.in/wp-content/uploads/2025/10/Global-Legal-Responses-to-Deepfakes-A-Regulatory-Primer.pdf">Global Legal Responses to Deepfakes: A Regulatory Primer</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0267364922000632">Deepfakes: regulatory challenges for the synthetic society</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#deepfake`, `#app security`, `#privacy`, `#tech regulation`

---

<a id="item-tech-news-7"></a>
### [SGLang v0.5.23 Adds 9 New Models with Performance Improvements](https://github.com/sgl-project/sglang/releases/tag/v0.5.23) ⭐️ 7.0/10

SGLang v0.5.23 introduces support for 9 new models including Muse Spark Open, Beam-1.0, MiniMax-M3.1-Flash, MiniCPM-V 4.7, Kev, Cosmos3-Nano-Sim, FastH3 Omni, FLUX.3 Image Klein, HY-Nomas, and MOSS-Image across LLM/VLM and diffusion categories. The release brings significant performance improvements for DeepSeek-V4.1 with up to 1.5x more prefill throughput under load and 28% lower first-token latency on 32K to 64K prompts. New features include a low-latency mode with NVIDIA megakernel and AMD monokernel plugins offering up to 44% faster single-user decode, Paged Experts for running MoE models larger than GPU memory, and support for serving LoRA adapters on quantized MoE models.

github · Fridge003 · Nov 2, 22:14

**「Background」** SGLang is an open-source model serving framework designed for efficient deployment of large language models, vision-language models, and diffusion models. The framework specializes in optimizing performance through advanced techniques like speculative decoding, CUDA graphs, and specialized kernel implementations for different hardware platforms including NVIDIA GPUs, AMD GPUs, Intel processors, and now Google TPUs.

**「Impact」** The expanded model support and performance improvements will benefit developers and organizations deploying large language models and diffusion models, particularly those working with memory-intensive MoE models who can now leverage Paged Experts to run models larger than GPU memory with up to 30x faster performance than CPU offload.

**Tags**: `#model-serving`, `#llm`, `#diffusion-models`, `#release`, `#sglang`

---

<a id="item-tech-news-8"></a>
### [Updated Linux System Call Website Adds Architectures and API](https://syscall.sh/) ⭐️ 7.0/10

The author has updated their Linux System Call website and API, which was first released in 2020. The update includes expanded architecture support, a kernel selector, enhanced syscall descriptions, and improved mobile device compatibility. The API is now available at https://api.syscall.sh, and the author also mentioned plans to release a CLI tool that uses an embedded dataset.

hackernews · guitmz · Nov 2, 09:29 · [Discussion](https://news.ycombinator.com/item?id=50334704)

**「Background」** System calls form the fundamental interface between user space applications and the Linux kernel, allowing programs to request services from the operating system. They represent the mechanism through which applications access hardware resources and kernel functions, typically implemented through specific CPU instructions and register manipulation. The syscall.sh website provides a reference for these low-level interfaces, which are essential for systems programming but vary across different processor architectures.

**「Impact」** This updated resource provides developers with more comprehensive and accessible information about Linux system calls across different architectures, which can help in debugging, development, and understanding low-level Linux functionality.

**「Community Discussion」** The community discussed architecture-specific syscall implementations, with bkallus noting that on x86\_64 and x32, the syscall number goes in eax rather than rax, while wg0 questioned why syscalls vary per architecture if the Linux API is supposed to be the same.

<details><summary>References</summary>
<ul>
<li><a href="https://www.engineersgarage.com/kernel-programming/">Kernel Programming</a></li>
<li><a href="https://www.linkedin.com/posts/aymanalheraki_mastering-linux-system-calls-in-x86-64-assembly-activity-7474002357434036224-ufjw">Mastering Linux System Calls with x86-64 Assembly and... | LinkedIn</a></li>

</ul>
</details>

**Tags**: `#linux`, `#system-calls`, `#api`, `#developer-tools`, `#software-engineering`

---

<a id="item-tech-news-9"></a>
### [WTF Ubuntu?](https://chalmovsky.com/posts/wtf-ubuntu) ⭐️ 7.0/10

Community discussion about Ubuntu&\#x27;s handling of a security vulnerability with debate about its actual severity and appropriate priority level.

hackernews · chalmovsky · Nov 2, 14:52 · [Discussion](https://news.ycombinator.com/item?id=50337608)

**Tags**: `#security`, `#ubuntu`, `#linux`, `#cve`, `#open-source`

---

<a id="item-tech-news-10"></a>
### [LLM 0.37 Release Adds New Models and Configuration Improvements](https://simonwillison.net/2026/Nov/2/llm/) ⭐️ 7.0/10

Version 0.37 of the LLM CLI tool and Python library adds support for new models including gpt-6.1-sol and gpt-6.1-terra, introduces a new &\#x27;llm openai endpoint add&\#x27; command for configuring additional OpenAI-compatible models, and switches the default model to gpt-6-luna which is half the price of the previous default gpt-5.6-luna. The release also enhances embeddings functionality to support different content types for models like Gemini Embedding 2 that can process text, audio, images, and video.

rss · Simon Willison · Nov 2, 23:49

**「Background」** LLM is a CLI tool and Python library developed by Simon Willison for interacting with language models. The software provides a unified interface to various AI models, allowing developers to configure endpoints, manage different model options, and work with embeddings for processing diverse content types like text, audio, images, and video.

**「Impact」** Users will experience cost savings as the default model is now gpt-6-luna, which is half the price of the previous default model gpt-5.6-luna, potentially reducing API costs for users who haven&\#x27;t set their own default model.

**Tags**: `#llm-tools`, `#ai-development`, `#software-updates`, `#developer-tools`, `#language-models`

---

<a id="item-tech-news-11"></a>
### [The U.S. Census Bureau and “Super Intelligence”](https://simonwillison.net/2026/Nov/2/census-bureau-super-intelligence/) ⭐️ 7.0/10

U.S. Census Bureau&\#x27;s AI data collection affected by new &\#x27;Super Intelligence&\#x27; executive order.

rss · Simon Willison · Nov 2, 13:31

**Tags**: `#AI policy`, `#Data collection`, `#Government regulation`, `#Technology industry`, `#Executive orders`

---

<a id="item-tech-news-12"></a>
### [GDPx Benchmark Measures AI Capabilities in High-Value Domains](https://newsletter.semianalysis.com/p/gdpx-measuring-frontier-model-capabilities) ⭐️ 7.0/10

GDPx introduces a novel benchmark focused on measuring frontier AI model capabilities in high-value commercial domains including chip design, cybersecurity, biology, finance, legal, quant trading, recursive self-improvement, hardware design, materials science, alignment, and software engineering. The benchmark reveals that even the best models score just 12%, with OpenAI&\#x27;s Opus 5.5 and Anthropic&\#x27;s GPT-6 Astra leading rankings, though their scores are impacted by safety classifiers in domains like cybersecurity, biology, and alignment. Google&\#x27;s Gemini 4 Carbon is identified as a significant improvement that competes with top models, while Muse Wonder Full emerges as the best available cybersecurity model.

rss · Semianalysis · Nov 2, 01:51

**「GDPx Benchmark Overview」** GDPx is a novel benchmark designed to measure frontier AI model capabilities specifically in high-value domains where AI will have the most significant commercial impact. Unlike traditional benchmarks that might focus on broad economic measures or general capabilities, GDPx concentrates on 11 specific domains including chip design, cybersecurity, biology, finance, legal, and recursive self-improvement. This targeted approach reflects the belief that the first trillion dollars of AI revenue will be concentrated in sectors that can deploy frontier intelligence at high return on investment.

**「Impact on AI Model Selection」** The GDPx benchmark demonstrates that safety classifiers significantly impact model performance in certain domains, making Muse Wonder Full the best available cybersecurity model despite not leading overall rankings, which suggests organizations should consider both general capabilities and domain-specific safety mechanisms when selecting AI systems for critical applications.

**Tags**: `#AI benchmarking`, `#frontier models`, `#AI capabilities`, `#high-value domains`, `#AI evaluation`

---

<a id="item-tech-news-13"></a>
### [ChatGPT Sharing Link Vulnerability Patched](https://www.parameter.ai/labs/we-found-a-gap-at-openai) ⭐️ 7.0/10

Parameter research team discovered a ChatGPT vulnerability allowing attackers to execute code in logged-in user sessions through malicious sharing links, enabling private conversation data theft. OpenAI patched the flaw on October 26, classified it as P1 severity, and paid a $5,000 bounty to the researchers. The vulnerability exploited a message processing defect between preview functionality and chart components, requiring only link click without app installation.

telegram · zaihuapd · Nov 2, 10:24

**「Background」** ChatGPT&\#x27;s sharing feature allows users to collaborate by sending links to conversations, which normally operate within a secure sandboxed environment. The vulnerability exploited a cross-frame messaging defect that bypassed these security controls, allowing malicious code execution in a victim&\#x27;s browser session when they clicked a specially crafted link. This type of account takeover vulnerability represents a significant security risk as it requires no user interaction beyond clicking a link.

**「Security Impact」** Users who clicked on malicious ChatGPT sharing links could have their accounts completely compromised, with attackers accessing private conversations and exfiltrating sensitive data to external servers without any additional user interaction required.

<details><summary>References</summary>
<ul>
<li><a href="https://aicybr.com/blog/chatgpt-shared-link-session-takeover-parameter-labs-october-2026">ChatGPT Shared-Link Session Takeover: October 2026 Fix ...</a></li>
<li><a href="https://labs.cloudsecurityalliance.org/research/csa-research-note-chatgpt-share-link-session-hijack-20261031/">One Click Into Someone Else’s ChatGPT: Cross-Frame Messaging ...</a></li>
<li><a href="https://www.parameter.ai/labs/we-found-a-gap-at-openai">Do the Math: How We Took Over ChatGPT Accounts - Parameter</a></li>

</ul>
</details>

**Tags**: `#security`, `#ai`, `#vulnerability`, `#chatgpt`, `#account-takeover`

---

<a id="item-tech-news-14"></a>
### [Tesla China App Shows FSD Statistics Page](https://mp.weixin.qq.com/s/gW4mi-7y6vEN88L4wSiW6A) ⭐️ 7.0/10

Tesla&\#x27;s Chinese app has been updated to include a Full Self-Driving \(FSD\) statistics page in simplified Chinese, with some content featuring real Chinese locations. The page shows 0 km for mileage data as the feature is not yet fully available in China, though it indicates future support for smart parking and remote vehicle summoning functionality. Tesla&\#x27;s China website briefly displayed FSD domestic function information but later removed it, and the company has not officially confirmed a launch date for FSD in China.

telegram · zaihuapd · Nov 2, 10:55

**「Background」** FSD \(Full Self-Driving\) represents Tesla&\#x27;s advanced autonomous driving technology that aims to enable vehicles to navigate with minimal human intervention. Previously, Tesla&\#x27;s China website briefly featured FSD domestic function descriptions before being removed, indicating ongoing regulatory and technical adaptation challenges for these features in the Chinese market. The appearance of a localized FSD statistics page in Tesla&\#x27;s Chinese app suggests progress toward making these advanced autonomous capabilities available to Chinese users, though official confirmation and full deployment details are still pending.

**「Potential Impact on Chinese Autonomous Driving Market」** The appearance of this localized FSD page suggests Tesla is making progress toward regulatory and technical adaptation for autonomous driving features in China, one of the world&\#x27;s largest automotive markets, which could significantly impact the competitive landscape for self-driving technology in the region.

**Tags**: `#autonomous-driving`, `#tesla`, `#ai-ml`, `#china-tech`, `#automotive`

---

## Technology Blog

<a id="item-tech-blog-1"></a>
### [LLMs Not Superhuman at Neural Network Weight Manipulation](https://seangoedecke.com/llms-are-not-superhuman-at-reading-and-writing-neural-network-weights/) ⭐️ 8.0/10

rss · Sean Goedecke · Nov 3, 00:00

**「Background」** A recent paper claims that frontier LLMs like GPT-6 Astra can work directly with neural network weights in seemingly superhuman ways, including identifying training data and improving model performance through weight edits.

**「Solution」** The author argues these capabilities are actually achievable by competent human researchers. For identifying what games a small network was trained on, the author notes the input channels were labeled and directly connected to grid cells, making it straightforward to calculate which weight patterns corresponded to game elements - demonstrated by a simple Python implementation that creates heatmaps showing these patterns. For the more impressive task of fixing a 0.8B Qwen model&\#x27;s mathematics problem \(where it got stuck in loops after 32k tokens\), the author explains that a human researcher would use a &\#x27;steering&\#x27; approach: comparing looping vs. non-looping reasoning texts, identifying weights contributing to the looping behavior, and trimming those weights. This is exactly what Astra did, showing the technique is not revolutionary but rather an application of existing methods.

**「Takeaway」** While LLMs can directly manipulate neural network weights, these capabilities reflect techniques accessible to human researchers rather than superhuman intelligence, and the most effective approach to model improvement remains through traditional training processes rather than direct weight editing.

**Tags**: `#LLM evaluation`, `#neural networks`, `#AI capabilities`, `#technical analysis`, `#critical thinking`

---

<a id="item-tech-blog-2"></a>
### [Audience Capture](https://seangoedecke.com/audience-capture/) ⭐️ 7.0/10

rss · Sean Goedecke · Nov 3, 00:00

**「Background」** Audience capture occurs when optimizing for engagement metrics leads to attracting the wrong audience—superficial &\#x27;clickers&\#x27; rather than the thoughtful &\#x27;readers&\#x27; who actually engage with your ideas.

**「Solution」** The author explains that engagement metrics are valuable proxies but can diverge from actual value when over-optimized. Online platforms reward views and clicks, but these metrics can&\#x27;t distinguish between readers who engage deeply and those who merely scan content. This creates a dangerous incentive to create content that attracts superficial engagement rather than meaningful discussion. The author distinguishes between &\#x27;proxy games&\#x27; \(like getting views\) and &\#x27;real games&\#x27; \(like gaining respect from people you respect\), noting that it&\#x27;s sometimes acceptable to make tradeoffs but dangerous to &\#x27;sell out by habit&\#x27; when it doesn&\#x27;t serve your actual goals.

**「Takeaway」** Focusing on meaningful engagement with a valuable audience is more important than optimizing for proxy metrics like raw view counts, as the latter can lead to audience capture where you&\#x27;re performing for people who don&\#x27;t actually care about your work.

**Tags**: `#content-creation`, `#metrics`, `#audience-building`, `#professional-development`, `#writing-strategy`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Anthropic Reports Massive Revenue Growth Despite Huge Losses](https://www.cnbc.com/2026/11/02/anthropic-ant-s-1-quarter-financials.html) ⭐️ 7.0/10

Anthropic reported $33.24 billion revenue for the first three quarters of 2026, a 1200% increase year-over-year, while posting a net loss of $104 billion in its IPO filing.

telegram · zaihuapd · Nov 2, 15:12

**「Background」** Anthropic, an AI company founded in 2021 by former OpenAI members, is investing heavily in computing infrastructure to support its growth.

<details><summary>References</summary>
<ul>
<li><a href="https://penchan.co/en/market/ai/anthropic/dario-amodei-and-team/">Dario Amodei and the Anthropic Founding Team: Eight... | Penchan</a></li>

</ul>
</details>

**Tags**: `#AI companies`, `#Financial results`, `#IPO`, `#Revenue growth`, `#Losses`

---

<a id="item-finance-news-2"></a>
### [UK Proposes Extending Migrant Settlement Period to 10 Years](https://www.gov.uk/government/news/home-secretary-unveils-new-rules-for-migrants-settling-in-the-uk) ⭐️ 7.0/10

UK government proposes extending the settlement period for most migrants from 5 to 10 years, with exceptions for high-earners and public service workers who can still apply after 5 years.

telegram · zaihuapd · Nov 2, 23:50

**「Background」** The UK government is proposing to extend the standard settlement period for most migrants from the current 5 years to 10 years, with exceptions for high-earners and public service workers who can still qualify after 5 years.

**「Labor Market Effects」** The extended settlement period would likely slow workforce integration for most migrants, potentially affecting labor markets in sectors reliant on migrant workers and creating a more segmented workforce between high-earners/public service workers and other migrants.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bbc.com/news/articles/c6ly052pdx4no">What are the planned changes to immigration rules?</a></li>
<li><a href="https://www.migrationpolicy.org/sites/default/files/publications/Immigration-and-the-Labour-Market.pdf">Immigration</a></li>
<li><a href="https://factually.co/fact-checks/economy/uk-immigration-policy-economy-3ff902">Fact Check: How does the UK &#x27;s immigration policy affect its econom...</a></li>
<li><a href="https://www.economicshelp.org/blog/6399/economics/impact-of-immigration-on-uk-economy/">Impact of Immigration on UK Economy - Economics Help</a></li>

</ul>
</details>

**Tags**: `#Immigration policy`, `#Labor market`, `#Government regulation`, `#UK economy`, `#Public services`

---