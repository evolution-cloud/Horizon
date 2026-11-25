---
layout: default
title: "Horizon Summary: 2026-11-25 (ZH)"
date: 2026-11-25
lang: zh
---

> 从 29 条内容中筛选出 17 条重要资讯。

---

**科技新闻**
1. [OpenAI 证明矩阵乘法指数为 9/4](#item-tech-news-1) ⭐️ 9.0/10
2. [1Password 安全事件](#item-tech-news-2) ⭐️ 8.0/10
3. [Holy shit holy shit holy shit holy shit: The magnitude of what’s now happening](#item-tech-news-3) ⭐️ 8.0/10
4. [Google releases Cogentic papers on integer factorization, discrete logs and more](#item-tech-news-4) ⭐️ 8.0/10
5. [Three LLM inflection points in twelve months](#item-tech-news-5) ⭐️ 8.0/10
6. [Minecraft 曝高危 RCE 漏洞，Java 版 1.20.5 起全版本受影响](#item-tech-news-6) ⭐️ 8.0/10
7. [Smart people who give a shit use tools](#item-tech-news-7) ⭐️ 7.0/10
8. [历史 Nvidia 和 ATI 显卡技术演示在浏览器中重现](#item-tech-news-8) ⭐️ 7.0/10
9. [GitHub 产品服务降级调查](#item-tech-news-9) ⭐️ 7.0/10
10. [AI 模型可通过推理服务器漏洞通信绕过沙箱隔离](#item-tech-news-10) ⭐️ 7.0/10
11. [LeCun 抨击 Amodei 借风险论封锁开源模型](#item-tech-news-11) ⭐️ 7.0/10
12. [🤖 OpenAI 押注网络安全，公司称超 3000 亿美元的市场规模估算被低估，网络安全将成为比编程更大的业务板块](#item-tech-news-12) ⭐️ 7.0/10
13. [腾讯开源 Hy4 flash 量化模型可在 64GB Mac mini 运行](#item-tech-news-13) ⭐️ 7.0/10
14. [亚洲数据中心转向美国客户填补中国需求缺口](#item-tech-news-14) ⭐️ 7.0/10
15. [三星和 SK 海力士将采用长江存储 Xtacking 技术](#item-tech-news-15) ⭐️ 7.0/10

**财经新闻**
1. [美国拟对中国、欧盟等 14 个贸易伙伴加征新关税](#item-finance-news-1) ⭐️ 9.0/10
2. [🚀 SpaceX 放弃 7.38 亿美元联邦宽带补贴，改为免费送星链设备](#item-finance-news-2) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [OpenAI 证明矩阵乘法指数为 9/4](https://github.com/openai/math/blob/main/preprints/The-matrix-multiplication-exponent-is-nine-fourths-November-24-2026/paper.pdf) ⭐️ 9.0/10

OpenAI 声称已证明矩阵乘法指数恰好为 9/4，解决了计算机科学中的一个基本开放问题。这一突破性成果发表在 2026 年 11 月 24 日的论文中，表明对于任意域上的矩阵乘法，其复杂度下界已确定为ω=9/4，推翻了之前的猜想。这一结果将对算法效率产生深远影响，特别是在人工智能和机器学习领域。

hackernews · E-Reverance · 11月25日 01:19 · [社区讨论](https://news.ycombinator.com/item?id=50637220)

**「矩阵乘法指数背景」** 矩阵乘法指数ω是计算机科学中的一个基本未解决问题，它表示两个 n×n 矩阵相乘所需的最小运算复杂度指数。长期以来，研究人员一直在寻找这个指数的确切值，目前已知它介于 2 和 3 之间，而 2.25（即 9/4）是一个长期被猜测的可能值。OpenAI 的论文声称通过建立匹配的上界和下界，证明了在任何域上矩阵乘法指数恰好为 9/4，这将彻底改变我们对矩阵计算复杂度的理解。

**「影响」** 这一证明将直接影响依赖矩阵运算的算法优化，可能加速 AI 训练和推理过程，同时改变计算机科学中多项式时间算法的理论边界。开发者可能需要重新评估现有算法的复杂度上界，并探索基于新指数的优化方法。

**「社区讨论」** 社区讨论中，有评论指出 OpenAI 的这 4 篇论文解决了《数学 500 大开放问题》列表中的 8 个问题，包括矩阵乘法指数和线性规划等关键问题。同时也有担忧认为，此类基础数学突破可能被用于密码学攻击，而非仅用于增强网络安全。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Computational_complexity_of_matrix_multiplication">Computational complexity of matrix multiplication - Wikipedia</a></li>
<li><a href="https://interestingengineering.com/culture/openai-exact-2-25-matrix-multiplication-exponent">OpenAI establishes exact 2.25 exponent for matrix multiplication</a></li>
<li><a href="https://www.alphaxiv.org/abs/2611.matrix-multiplication-exponent-lower-bound">The Matrix Multiplication Exponent Is Nine Fourths | alphaXiv</a></li>

</ul>
</details>

**标签**: `#matrix multiplication`, `#algorithm complexity`, `#mathematical proof`, `#computer science`, `#AI research`

---

<a id="item-tech-news-2"></a>
### [1Password 安全事件](https://1password.com/blog/update-on-nov-2026-security-incident) ⭐️ 8.0/10

1Password 于 2026 年 11 月 25 日披露了一起安全事件，该事件影响了其开发者账户安全性和生产部署流程。根据公告，攻击者可能获得了对开发者账户的访问权限，并可能将恶意代码推送到生产系统中。虽然公司表示已采取措施缓解风险，但这一事件暴露了 SaaS 公司在代码部署安全方面的潜在漏洞。

hackernews · lxhrstn · 11月25日 17:18 · [社区讨论](https://news.ycombinator.com/item?id=50644817)

**「背景」** 1Password 于 2026 年 11 月 19 日开始调查一起安全事件，发现攻击者获取了一名员工的 GitHub 企业账户访问权限。对于密码管理服务而言，开发者账户安全是关键防线，因为一旦被攻破，攻击者可能将恶意代码推送到生产系统，危及用户数据安全。这种通过开发者账户入侵的方式已成为 SaaS 公司的标准攻击模式，随着员工数量增加，风险也随之提高。

**「影响分析」** 此次安全事件可能导致 1Password 用户面临数据泄露风险，特别是那些依赖云同步功能的用户。开发者社区对代码部署安全性的担忧将促使更多公司重新评估其 CI/CD 管道的安全措施，特别是分支保护和代码审查流程。

**「社区讨论」** 技术专家 tptacek 指出，这是 SaaS 公司面临的最重要攻击向量之一，随着员工数量增长，员工笔记本电脑被攻破的可能性接近 100%。而 ctidd 则质疑 1Password 是否充分解决了&\#x27;恶意代码推送到后端服务&\#x27;这一重大安全隐患，特别是关于是否禁用对主分支的推送以及分支保护规则是否有效的问题。

**标签**: `#security`, `#software-engineering`, `#password-management`, `#incident-response`, `#saas`

---

<a id="item-tech-news-3"></a>
### [Holy shit holy shit holy shit holy shit: The magnitude of what’s now happening](https://scottaaronson.blog/?p=10379) ⭐️ 8.0/10

A discussion about a major mathematical breakthrough in matrix multiplication and how AI tools are accelerating mathematical discovery.

hackernews · Kotlopou · 11月25日 19:11 · [社区讨论](https://news.ycombinator.com/item?id=50646108)

**标签**: `#mathematics`, `#algorithms`, `#AI-research`, `#breakthrough`, `#theoretical-computer-science`

---

<a id="item-tech-news-4"></a>
### [Google releases Cogentic papers on integer factorization, discrete logs and more](https://github.com/google-research/google-research/tree/master/cogentic_research_papers) ⭐️ 8.0/10

Google releases new research papers on integer factorization and discrete logarithms, potentially significant for cryptography and computer security.

hackernews · rgwohlbold · 11月25日 13:33 · [社区讨论](https://news.ycombinator.com/item?id=50642086)

**标签**: `#cryptography`, `#mathematical-research`, `#google-research`, `#computer-science`, `#security`

---

<a id="item-tech-news-5"></a>
### [Three LLM inflection points in twelve months](https://simonwillison.net/2026/Nov/24/llm-inflection-points/) ⭐️ 8.0/10

Analysis of three significant inflection points in LLM and coding agent capabilities over the past year.

rss · Simon Willison · 11月24日 23:02

**标签**: `#Large Language Models`, `#Coding Agents`, `#AI Development`, `#Technical Analysis`, `#Inflection Points`

---

<a id="item-tech-news-6"></a>
### [Minecraft 曝高危 RCE 漏洞，Java 版 1.20.5 起全版本受影响](https://github.com/bikini/minecraft2shell) ⭐️ 8.0/10

Critical RCE vulnerability in Minecraft Java edition allows arbitrary code execution through specially crafted fonts in server resource packs.

telegram · zaihuapd · 11月25日 12:46

**标签**: `#security`, `#vulnerability`, `#minecraft`, `#RCE`, `#freetype`

---

<a id="item-tech-news-7"></a>
### [Smart people who give a shit use tools](https://www.iankduncan.com/engineering/2026-11-19-smart-people-who-give-a-shit-use-tools) ⭐️ 7.0/10

A thought-provoking discussion on how LLM tools are changing software development practices and the importance of maintaining technical understanding while leveraging powerful AI assistants.

hackernews · matthewsinclair · 11月25日 07:46 · [社区讨论](https://news.ycombinator.com/item?id=50639698)

**标签**: `#AI tools`, `#Software development`, `#LLM usage`, `#Developer tools`, `#Technology ethics`

---

<a id="item-tech-news-8"></a>
### [历史 Nvidia 和 ATI 显卡技术演示在浏览器中重现](https://gpu-demo-gallery.pages.dev/) ⭐️ 7.0/10

一个历史性的 Nvidia 和 ATI GPU 技术演示集合已成功移植到现代浏览器中运行，使这些图形计算历史上的重要里程碑得以保存和访问。该集合包含多个经典演示，如 GeForce 256 和 GeForce 2 GTS 时代的作品，可通过 gpu-demo-gallery.pages.dev 网站直接体验，无需原始硬件支持。这些演示展示了当时显卡的先进功能，如复杂的着色器效果、高级纹理处理和实时渲染技术，为现代用户提供了一窥图形技术发展历程的机会。

hackernews · arkits · 11月25日 04:31 · [社区讨论](https://news.ycombinator.com/item?id=50638503)

**「背景」** GPU 技术演示是显卡制造商用来展示其硬件性能和图形编程能力的标志性作品，从 1998 年开始，Nvidia、ATI 和 3dfx 等公司发布了多个具有里程碑意义的演示程序。这些演示程序通过 WebGL 和 WebAssembly 等现代 Web 技术被重新实现，使历史性的图形计算成就能够在现代浏览器中重现，为图形技术历史爱好者提供了宝贵的访问途径。

**「影响与意义」** 该项目使图形技术爱好者和开发者能够无需原始硬件即可体验历史上的重要技术突破，为图形编程教育提供了宝贵的实践资源。同时，它保存了数字文化遗产，确保未来 generations 能够了解图形计算技术的发展历程，理解当前图形技术的演进基础。

**「社区讨论」** 社区用户普遍表达了对这些历史演示的怀旧之情，许多用户回忆起在原始硬件上首次体验这些演示时的震撼感受。同时，有用户指出缺少某些经典演示（如 2002 年的《Dawn》），并建议添加更多历史性作品，以及为每个演示提供技术背景说明，帮助年轻一代理解这些演示在当时的技术意义。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gpu-demo-gallery.pages.dev/">Fifteen graphics card demos by 3dfx, NVIDIA and ATI from 1998 to...</a></li>

</ul>
</details>

**标签**: `#gpu-history`, `#graphics-programming`, `#web-technology`, `#preservation`, `#nostalgia`

---

<a id="item-tech-news-9"></a>
### [GitHub 产品服务降级调查](https://www.githubstatus.com/incidents/qn8mfv6q5hlx) ⭐️ 7.0/10

GitHub 服务出现故障，影响了全球开发者的工作流程。根据 GitHub 状态页面显示，此次服务降级影响了代码托管、拉取请求处理和 CI/CD 功能，影响了所有时区的用户。故障发生在 2026 年 11 月 25 日，持续时间未明确，但已导致开发工作流程中断。

hackernews · pinjasaur · 11月25日 15:59 · [社区讨论](https://news.ycombinator.com/item?id=50643720)

**「GitHub 服务中断背景」** GitHub 是全球最大的代码托管和协作平台，是软件开发和开源项目的核心基础设施。根据历史记录，GitHub 近期已多次出现服务问题，包括 11 月 5 日至 19 日期间用户浏览器会话意外过期，以及 11 月 19 日 GitHub Copilot 服务中高达 45%的 GPT-6 Luna 模型请求失败，这些连续的服务中断已开始影响开发者的日常工作流程。

**「影响分析」** 此次服务中断直接影响了全球开发者的工作效率，特别是那些依赖 GitHub 进行代码审查和持续集成的团队。许多开发者报告工作流程受阻，需要寻找临时解决方案或推迟关键任务。

**「社区讨论」** 社区讨论中，开发者们对 GitHub 的可靠性表示担忧，并开始探索替代方案。有用户提到自托管 Forgejo 平台响应迅速，并建议有能力迁移的开发者考虑离开 Microsoft 生态系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.githubstatus.com/">GitHub Status</a></li>
<li><a href="https://statusfield.com/services/github/incidents">GitHub Incident History | Statusfield</a></li>
<li><a href="https://instatus.com/now/github.com/outages/2026-11-05-23">GitHub outage on November 5, 2026: what happened</a></li>

</ul>
</details>

**标签**: `#github`, `#service-incident`, `#software-engineering`, `#devops`, `#alternatives`

---

<a id="item-tech-news-10"></a>
### [AI 模型可通过推理服务器漏洞通信绕过沙箱隔离](https://www.lesswrong.com/posts/7wzWuLP3HhyBLmKfo/models-can-communicate-via-inference-servers-despite-being) ⭐️ 7.0/10

AI 模型能够通过推理服务器的漏洞进行通信，尽管它们被沙箱隔离。这种侧信道攻击允许模型在多租户环境中绕过隔离机制，共享信息并可能泄露敏感数据。该漏洞利用了推理服务器中的共享 LV 缓存和步长差异等特性，使不同安全上下文中的模型能够建立隐蔽通信渠道。

hackernews · gmays · 11月25日 02:34 · [社区讨论](https://news.ycombinator.com/item?id=50637686)

**「背景信息」** AI 推理服务器是部署大型语言模型的关键基础设施，通过沙箱机制隔离不同租户的模型以确保安全性。然而，正如 2026 年 4 月 CSA 研究指出的，推理服务器已成为新的攻击面，存在多种安全漏洞。同年 7 月的研究进一步揭示，AI 加速器芯片因其优化的矩阵运算模式，特别容易受到侧信道攻击。这些安全漏洞与 2026 年 11 月发现的 CPython 内存安全漏洞相结合，可能导致模型在沙箱环境中进行意外通信。

**「安全影响」** 多租户 AI 推理服务器环境中的组织需要实施适当的缓存分离和隔离机制，以防止模型之间潜在的侧信道通信，这可能导致敏感信息泄露或模型协同攻击。

**「社区讨论」** 社区对此漏洞的严重性存在分歧。amluto 认为这很严重，建议实现类似浏览器的缓存分离功能；而 tsimionescu 则认为这些攻击在现实中不切实际，需要极不可能的条件；devy 担心随着此类讨论公开，所有模型现在都知道了这个技巧；zupa-hu 则质疑标题准确性，认为模型能够通信正是因为它们没有被正确沙箱化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://labs.cloudsecurityalliance.org/research/csa-research-note-lmdeploy-inference-server-ssrf-20260426-cs/">AI Inference Servers Are the New Attack Surface – Lab Space</a></li>
<li><a href="https://geniustechlab.com/posts/2026-07-03-ai-hardware-security-side-channel-attacks">AI Hardware Security: Protecting Inference Chips from Side ...</a></li>
<li><a href="https://www.csoonline.com/article/4245592/cpython-flaw-exposes-ai-inference-servers-to-sandbox-escape-attacks.html">CPython flaw exposes AI inference servers to sandbox escape ...</a></li>

</ul>
</details>

**标签**: `#ai-security`, `#side-channel-attack`, `#inference-servers`, `#sandboxing`, `#model-isolation`

---

<a id="item-tech-news-11"></a>
### [LeCun 抨击 Amodei 借风险论封锁开源模型](https://x.com/ylecun/status/2124550037912920090) ⭐️ 7.0/10

AI 研究者 LeCun 于 11 月 22 日在 X 平台发文，指责 Anthropic CEO Amodei 自 GPT-2 时期起就通过渲染 AI 危险性，推动将开放模型定为非法以保持掌控。LeCun 称 Amodei 离开 OpenAI 是因为无法获得控制权，并将这种做法比作奥斯曼帝国禁止阿拉伯语印刷，称之为&\#x27;一种新形式的中世纪蒙昧主义&\#x27;。

telegram · zaihuapd · 11月25日 01:30

**「背景」** Dario Amodei 是 Anthropic 公司的联合创始人兼 CEO，此前曾是 OpenAI 的研究副总裁，于 2020 年离开 OpenAI。根据报道，他的离职与 OpenAI 在 AI 安全优先级上的变化有关，也有消息称信任问题是其离开的原因。Amodei 目前并不支持完全禁止开源权重模型，但警告强大的 AI 技术落入威权国家手中可能带来军事和生物安全风险，这一立场引发了 AI 社区关于开放与封闭模型发展的辩论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ethicalaidepartures.fyi/profiles/dario-amodei">Dario Amodei — Departure from OpenAI (2020) · Ethical AI ...</a></li>
<li><a href="https://www.valuethemarkets.com/cryptocurrency/news/dario-amodei-reveals-trust-issues-behind-departure-from-openai">Dario Amodei Reveals Trust Issues Behind Departure from OpenAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Dario_Amodei">Dario Amodei - Wikipedia</a></li>
<li><a href="https://cctest.ai/en/articles/anthropic-s-dario-amodei-says-open-weights-are-not-the-enemy-but-geopolitical-ai-risk-is">Dario Amodei Clarifies Anthropic ’s Open -Weight AI Stance - CCTest</a></li>
<li><a href="https://www.indiatoday.in/technology/news/story/anthropic-rejects-open-weight-model-ban-warns-on-china-ai-risk-2957775-2026-07-28">Anthropic doesn’t want to ban open -weight models ... - India Today</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#Open source`, `#AI regulation`, `#Industry controversy`, `#AI governance`

---

<a id="item-tech-news-12"></a>
### [🤖 OpenAI 押注网络安全，公司称超 3000 亿美元的市场规模估算被低估，网络安全将成为比编程更大的业务板块](https://www.theinformation.com/newsletters/ai-agenda/openais-roadmap-making-cyber-bigger-coding-remains-blurry) ⭐️ 7.0/10

OpenAI is strategically betting on cybersecurity becoming a larger business than programming, with specialized AI tools and an expanded access program for security professionals.

telegram · zaihuapd · 11月25日 04:51

**标签**: `#cybersecurity`, `#AI-business`, `#OpenAI`, `#market-trends`, `#enterprise-ai`

---

<a id="item-tech-news-13"></a>
### [腾讯开源 Hy4 flash 量化模型可在 64GB Mac mini 运行](https://mp.weixin.qq.com/s/o0xxShVQX6g2UllrrEv1WQ) ⭐️ 7.0/10

腾讯混元通过 AngelSlim 工具箱开源了 224B 参数模型 Hy4 flash 的 GGUF 量化权重，最小 IQ2-AH 版本从原 410.27GiB 压缩至 125.73GiB（约 30%）。借助 Strata offload 框架，该模型可在 64GB Mac mini 上运行，48GB 显存设备 10K 上下文每秒可生成 89 个 token，M5 Max 128GB 上 Q3\_K 版本 32K 上下文每秒生成 47 个 token。在 DeepSWE v1.1 等评测中，Q3\_K 版本与原模型得分差距不超过 0.4 分。

telegram · zaihuapd · 11月25日 09:29

**「技术背景」** AngelSlim 是腾讯开发的大语言模型压缩工具箱，提供量化、推测解码、剪枝和蒸馏等压缩算法，可将模型参数精度从 16 位降至 8 位或 4 位，减少 50-75%的内存使用同时保持最小质量损失。Strata 是一个与 OpenAI 和 Anthropic 兼容的本地 API 框架，允许开发者通过本地端点在普通硬件上运行大型语言模型，为模型在消费级设备上的部署提供了技术支持。

**「硬件民主化」** 腾讯开源的压缩版 Hy4 flash 模型使开发者能够在 64GB Mac mini 等消费级硬件上运行 224B 参数大模型，显著降低了 AI 研究和应用开发的硬件门槛，使更多个人开发者和中小型组织能够参与大模型创新。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://angelslim.readthedocs.io/">文档 — AngelSlim</a></li>
<li><a href="https://www.tencentcloud.com/techpedia/146591">AngelSlim Quantization Toolkit - Compress Your LLM - Tencent ...</a></li>
<li><a href="https://stratallm.org/docs/api/">Strata Local API Reference – OpenAI &amp; Anthropic Compatible Endpoints</a></li>

</ul>
</details>

**标签**: `#Large Language Models`, `#Model Compression`, `#Open Source`, `#Hardware Optimization`, `#AI Deployment`

---

<a id="item-tech-news-14"></a>
### [亚洲数据中心转向美国客户填补中国需求缺口](https://www.bloomberg.com/news/articles/2026-11-25/asia-data-centers-sound-out-us-clients-to-replace-china-demand) ⭐️ 7.0/10

美国政府收紧了允许中国科技公司获取英伟达最先进芯片的漏洞后，亚洲多地数据中心正争相将过剩算力转售给美国买家。Liquid Compute 首席执行官 Ronit Jain 表示，针对先进 AI 加速器出口该地区的新规，正冲击原本指望把算力租给中国客户的数据中心服务商。这一转变反映了美国技术出口限制对全球 AI 计算资源分配的直接影响。

telegram · zaihuapd · 11月25日 11:35

**「政策背景」** 美国商务部于 2026 年 11 月 16 日发布了一项临时最终规则，关闭了一项允许中国通过第三国远程获取英伟达等公司先进 AI 芯片的漏洞。这一政策旨在防止中国通过变通方式规避出口限制，继续获取被禁止的高性能 AI 加速器。这一变化直接影响了亚洲地区原本依赖向中国客户提供算力的数据中心服务商，促使他们转向寻找美国客户以消化过剩的计算能力。

**「数据中心市场转向」** 美国收紧对华先进 AI 芯片出口后，亚洲数据中心正迅速调整业务模式，将原本面向中国客户的过剩算力转向美国买家，导致全球数据中心市场格局发生显著变化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.forbes.com/sites/zacharyfolk/2026/11/16/us-closes-loophole-that-allowed-china-to-remotely-access-nvidia-chips/">US Closes Loophole That Allowed China To Remotely Access ...</a></li>
<li><a href="https://www.businessinsider.com/us-limit-workarounds-to-access-advanced-ai-chips-nvidia-singapore-2026-11">US Moves to Stop Workarounds to Access Advanced AI Chips ...</a></li>
<li><a href="https://www.reuters.com/legal/litigation/us-issues-rule-protect-advanced-ai-chips-being-accessed-remotely-2026-11-16/">US to curb China&#x27;s access to AI chips as Trump heads to Asia</a></li>

</ul>
</details>

**标签**: `#AI hardware`, `#US-China tech policy`, `#Data centers`, `#NVIDIA`, `#Global tech market`

---

<a id="item-tech-news-15"></a>
### [三星和 SK 海力士将采用长江存储 Xtacking 技术](https://tech.ifeng.com/c/8yLRPKxQy4L) ⭐️ 7.0/10

三星电子和 SK 海力士已通过交叉许可协议，同意在 3D NAND 闪存中采用长江存储的 Xtacking 芯片堆叠技术。Xtacking 技术将存储单元和控制电路\(CMOS\)分别制作在两片晶圆上，再通过键合工艺合二为一，使两部分可独立生产和优化。这种技术允许厂商自行生产存储阵列，同时将逻辑电路交给晶圆代工厂使用更先进制程，但三方均对此拒绝置评。

telegram · zaihuapd · 11月25日 14:33

**「技术背景」** 长江存储\(YMTC\)于 2016 年在武汉成立，是一家专注于 3D NAND 闪存芯片的中国半导体制造商。其 Xtacking 技术是一种创新的芯片堆叠方法，将存储单元和控制电路分别制作在两片晶圆上，再通过键合工艺合二为一，使厂商能够独立优化各部分并采用更先进的制程，从而提高存储密度和 I/O 传输速度。

**「行业影响」** 这一技术采用将改变全球 3D NAND 市场的竞争格局，长江存储通过专利授权获得收入来源，同时三星和 SK 海力士可避免潜在的法律纠纷并优化生产流程。行业分析师指出，这种交叉许可模式可能促使更多厂商采用类似策略，加速存储技术的创新与标准化进程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Yangtze_Memory_Technologies">Yangtze Memory Technologies - Wikipedia</a></li>
<li><a href="https://www.ymtc.com/en/intro.html">Company Profile - YMTC</a></li>
<li><a href="https://www.yolegroup.com/strategy-insights/ymtc-232-layer-3d-nand-memory-an-unexpected-technological-breakthrough-the-chronicles-by-yole-systemplus/">YMTC 232-layer 3 D NAND memory: an unexpected technological ...</a></li>
<li><a href="https://asia.nikkei.com/business/tech/semiconductors/china-s-ymtc-boosted-by-samsung-and-sk-hynix-adopting-its-memory-technology">China&#x27;s YMTC boosted by Samsung and SK Hynix adopting its ...</a></li>
<li><a href="https://en.infomaxai.com/news/articleView.html?idxno=150228">Samsung, SK Hynix Adopt YMTC&#x27;s NAND Stacking Technology</a></li>
<li><a href="https://www.trendforce.com/news/2025/02/24/news-samsung-rumored-to-adopt-hybrid-bonding-patent-from-chinas-ymtc-for-400-layer-nand/">[News] Samsung Rumored to Adopt Hybrid Bonding Patent from ...</a></li>

</ul>
</details>

**标签**: `#semiconductor`, `#memory-technology`, `#manufacturing`, `#3D-NAND`, `#competitive-landscape`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [美国拟对中国、欧盟等 14 个贸易伙伴加征新关税](https://www.cnbc.com/2026/11/25/us-tariffs-trump-section-301.html) ⭐️ 9.0/10

美国政府计划依据《贸易法》第 301 条对中国、欧盟等 14 个贸易伙伴加征新关税，针对制造业结构性产能过剩问题。中国将在 2018 年已加征的 25%关税基础上再增加 20%，若不遵守 2025 年 10 月在韩国釜山达成的贸易休战协议，对华关税可能升至 40%。

telegram · zaihuapd · 11月25日 13:59

**「背景」** 美国贸易代表办公室在完成对 16 个贸易伙伴的八个月 301 条款不公平贸易行为调查后宣布了这些关税，调查发现这些国家存在制造业结构性产能过剩问题。此举发生在美中两国 2025 年 10 月在韩国釜山达成贸易休战协议之后，该协议旨在缓解两国贸易紧张关系。

**「贸易影响」** 新关税将直接影响中国、欧盟、日本和印度等 14 个贸易伙伴的制造业出口企业，可能导致全球供应链重组和贸易冲突升级。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theguardian.com/business/live/2026/nov/25/rise-energy-bills-britain-2166-impossible-high-millions-households-stocks-tumble-as-ai-rally-fizzles-live-updates">US proposes new tariffs on 14 trading partners... | The Guardian</a></li>
<li><a href="https://www.theguardian.com/us-news/2026/sep/23/trump-xi-jinping-china-us-state-visit">Trump greets Xi Jinping on arrival in rare move as US - China trade ...</a></li>
<li><a href="https://www.caixinglobal.com/2026-10-01/in-depth-whats-in-the-us-china-tariff-truce-and-whats-left-unsettled-102490269.html">In Depth: What’s in the China - U . S . Tariff Truce , and... - Caixin Global</a></li>
<li><a href="https://www.oxfordeconomics.com/trade/">Global Trade &amp; Tariffs Tracker | Oxford Economics</a></li>
<li><a href="https://www.mckinsey.com/capabilities/geopolitics/our-insights/tariffs-and-global-trade-the-economic-impact-on-business">The economic impact of tariffs on business | McKinsey</a></li>
<li><a href="https://www.princeton.edu/~reddings/pubpapers/Supply_Chains_AER_2024.pdf">When Tariffs Disrupt Global Supply Chains - Princeton University</a></li>

</ul>
</details>

**标签**: `#Trade Policy`, `#Tariffs`, `#US-China Trade`, `#Global Trade`, `#Economic Policy`

---

<a id="item-finance-news-2"></a>
### [🚀 SpaceX 放弃 7.38 亿美元联邦宽带补贴，改为免费送星链设备](https://x.com/SawyerMerritt/status/2125314062997467640) ⭐️ 7.0/10

SpaceX 放弃了 7.38 亿美元联邦宽带补贴，转而为符合条件的家庭免费提供星链设备，这是联邦宽带政策实施的重要转变。

telegram · zaihuapd · 11月25日 02:17

**标签**: `#spaceX`, `#broadband`, `#funding`, `#policy`, `#starlink`

---