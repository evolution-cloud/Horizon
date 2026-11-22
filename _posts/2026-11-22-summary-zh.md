---
layout: default
title: "Horizon Summary: 2026-11-22 (ZH)"
date: 2026-11-22
lang: zh
---

> 从 26 条内容中筛选出 10 条重要资讯。

---

**科技新闻**
1. [What Happened to Silicon Valley?](#item-tech-news-1) ⭐️ 7.0/10
2. [OpenAI 探讨困惑度作为 AI 智能衡量标准](#item-tech-news-2) ⭐️ 7.0/10
3. [Muru：基于 Rust 的 Python Web 应用服务器](#item-tech-news-3) ⭐️ 7.0/10
4. [🚘 特斯拉开始推送 FSD v15](#item-tech-news-4) ⭐️ 7.0/10
5. [Phison 发布 488TB 太空 SSD](#item-tech-news-5) ⭐️ 7.0/10
6. [摩尔线程庐山 GPU 将配备 64GB 显存](#item-tech-news-6) ⭐️ 7.0/10

**科技博客**
1. [避免错误，编写好代码](#item-tech-blog-1) ⭐️ 5.0/10

**财经新闻**
1. [英媒揭英伟达芯片走私网络：柬埔寨太子集团涉案人员被指参与对华走私](#item-finance-news-1) ⭐️ 7.0/10
2. [中国要求美国撤销电话号段接入限制](#item-finance-news-2) ⭐️ 7.0/10
3. [美股科技股遭血洗，亚洲股市严阵以待](#item-finance-news-3) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [What Happened to Silicon Valley?](https://www.oreilly.com/radar/what-happened-to-silicon-valley/) ⭐️ 7.0/10

An analysis of Silicon Valley&\#x27;s evolution, examining economic factors and market dynamics that have shaped the modern tech landscape.

hackernews · greenyouse · 11月22日 19:20 · [社区讨论](https://news.ycombinator.com/item?id=50602947)

**标签**: `#silicon-valley`, `#tech-industry`, `#market-dynamics`, `#capitalism`, `#web-evolution`

---

<a id="item-tech-news-2"></a>
### [OpenAI 探讨困惑度作为 AI 智能衡量标准](https://openai.com/index/perplexity-and-intelligence/) ⭐️ 7.0/10

OpenAI 发布了关于困惑度\(perplexity\)作为 AI 智能衡量标准的技术讨论，引发了社区广泛辩论。困惑度是衡量 AI 模型预测下一个令牌\(token\)能力的指标，范围从 1\(最佳预测\)到词汇表大小\(最差预测\)。OpenAI 提出困惑度可以作为评估 AI 模型智能水平的重要指标，但未明确说明其内部困惑度计算的具体方法和基准。

hackernews · acossta · 11月22日 17:06 · [社区讨论](https://news.ycombinator.com/item?id=50601525)

**「背景」** 困惑度（Perplexity）是信息理论中的一个概念，用于衡量概率模型预测样本的能力。在语言模型评估中，困惑度衡量模型基于前文预测下一个词的不确定性，困惑度值越低表示模型对实际序列的预测概率越高，表明在该评估数据上具有更好的预测性能。OpenAI 首席科学家 Jakub Pachocki 在 2026 年 11 月发布的文章中探讨了困惑度作为 AI 智能度量的应用，指出 OpenAI 模型的损失曲线在 2026 年出现急剧加速，这主要归因于长期研究和计算投资的成果。

**「影响」** 这一讨论可能影响 AI 行业对模型评估标准的理解，促使开发者更关注困惑度指标在模型训练和评估中的应用。然而，由于缺乏统一的困惑度计算标准，不同模型间的比较可能存在困难。

**「社区讨论」** 社区成员对困惑度作为 AI 智能衡量标准的有效性存在分歧，部分人质疑困惑度是否能真正反映模型能力，特别是当模型在特定领域\(如数学\)经过专门训练时。同时，有评论指出 OpenAI 在提出困惑度应更广泛共享的同时，并未充分分享其自身的困惑度计算方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Perplexity">Perplexity - Wikipedia</a></li>
<li><a href="https://www.geeksforgeeks.org/nlp/perplexity-for-llm-evaluation/">Perplexity for LLM Evaluation - GeeksforGeeks</a></li>
<li><a href="https://openai.com/index/perplexity-and-intelligence/">Perplexity and Intelligence | OpenAI</a></li>

</ul>
</details>

**标签**: `#AI metrics`, `#language models`, `#perplexity`, `#OpenAI`, `#evaluation`

---

<a id="item-tech-news-3"></a>
### [Muru：基于 Rust 的 Python Web 应用服务器](https://simonwillison.net/2026/Nov/21/muru/) ⭐️ 7.0/10

Muru 是由 mod\_wsgi 开发者 Graham Dumpleton 创建的新一代基于 Rust 的 Python Web 应用服务器，专为运行 ASGI 和 WSGI 应用而设计。该项目采用 AI 辅助开发方式，结合了二十年的 Web 服务器开发经验，旨在为 Python Web 应用在开发和生产环境中提供最佳工具。Dumpleton 在过去三周内发布了 19 篇详细博客文章，记录了 Muru 从概念到实现的全过程，展示了其独特的设计理念和技术实现。

rss · Simon Willison · 11月21日 23:56

**「背景」** Python Web 服务器生态经历了从同步 WSGI 到异步 ASGI 的重大转变，这一转变已成为 2026 年新项目的默认选择。Graham Dumpleton 作为 mod\_wsgi 的开发者，拥有 20 年的 Python Web 服务器开发经验，他的新项目 Muru 代表了这一演进的高峰，结合了 Rust 的性能优势与 Python 的灵活性，旨在解决现代 Python Web 应用在开发和生产环境中的部署挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.deployhq.com/blog/python-application-servers-wsgi-vs-asgi-guide">Python Application Servers in 2026: WSGI vs ASGI, Gunicorn to ...</a></li>
<li><a href="https://pyrastra.com/posts/python-web-development-evolution/">Python Web Development Evolution: From WSGI to ASGI and the ...</a></li>

</ul>
</details>

**标签**: `#Python`, `#Web Development`, `#Rust`, `#AI-assisted Development`, `#Server Technology`

---

<a id="item-tech-news-4"></a>
### [🚘 特斯拉开始推送 FSD v15](https://x.com/Tesla/status/2124222447855743019) ⭐️ 7.0/10

Tesla releases FSD v15 with substantial safety improvements and new visualization interface for autonomous driving.

telegram · zaihuapd · 11月22日 00:03

**标签**: `#autonomous-driving`, `#tesla`, `#ai-safety`, `#automotive-software`, `#fsd`

---

<a id="item-tech-news-5"></a>
### [Phison 发布 488TB 太空 SSD](https://videocardz.com/newz/phison-announces-488tb-of-ssd-storage-for-space-data-centers-pricing-expected-to-be-astronomical) ⭐️ 7.0/10

Phison 发布了 Pascari Space 太空 SSD 系列，专为航天器、卫星和在轨数据中心设计。该系列将用于 Lonestar Data Holdings 的 StarVault-001 轨道数据中心，计划 2027 年上半年发射，搭载 488TB 容量，入轨后可用容量约 370TB。产品包含 Flight Critical、Main Storage 与 Orbital Data Center 三类，最高容量 128TB，部分型号使用 pSLC 可将写入寿命提高至多 60 倍，目前已上市。

telegram · zaihuapd · 11月22日 10:31

**「轨道数据中心背景」** 轨道数据中心是将 AI 和计算需求的数据处理与存储系统部署在卫星中的新兴概念，旨在减少地球数据中心对土地、电力和水资源的需求。这一趋势在 2026 年引起行业广泛关注，多家公司已开始开发太空数据中心，但仍面临工程和经济部署障碍。Lonestar Data Holdings 的 StarVault 项目是这一趋势的代表，其计划于 2027 年上半年发射的轨道数据中心将搭载 Phison 的 488TB 太空 SSD，标志着太空存储技术的重要进展。

**「影响」** 这一高容量太空 SSD 技术将显著提升在轨数据处理能力，为低地球轨道上的数据中心提供前所未有的存储解决方案，可能促进太空计算和数据分析应用的发展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.datacenterdynamics.com/en/news/space-solar-agrees-to-host-lonestar-data-storage-aboard-orbital-power-stations/">Space Solar agrees to host Lonestar data storage aboard orbital ...</a></li>
<li><a href="https://www.gao.gov/products/gao-26-109012">Science &amp; Tech Spotlight: Data Centers in Space | U.S. GAO</a></li>

</ul>
</details>

**标签**: `#storage-technology`, `#space-technology`, `#hardware-innovation`, `#data-center`, `#satellite-technology`

---

<a id="item-tech-news-6"></a>
### [摩尔线程庐山 GPU 将配备 64GB 显存](https://www.tomshardware.com/pc-components/gpus/moore-threads-next-lushan-gaming-gpu-could-pack-a-record-64gb-of-vram-doubles-the-rtx-5090s-32gb-lofty-claims-of-15x-gaming-and-50x-ray-tracing-over-mtt-s80) ⭐️ 7.0/10

摩尔线程下一代庐山游戏 GPU 将配备 64GB 显存，是目前消费级显卡中最大的显存容量，是 RTX 5090（32GB 显存）的两倍。这一信息来自 MTT S80 产品经理，并非公司官方发布。庐山 GPU 的目标性能是相对于 S80 的 15 倍游戏性能、50 倍光追性能和 64 倍 AI 算力，公司计划在 2026 年 12 月 29-30 日的 MDC 2026 上由 CEO 张建中发布新旗舰产品。

telegram · zaihuapd · 11月22日 15:11

**「背景信息」** 摩尔线程是一家中国 GPU 制造商，其当前旗舰产品为 MTT S80，配备 16GB 显存。庐山 GPU 被宣传为其下一代游戏显卡产品，计划于 2026 年 12 月 29-30 日在北京举行的 MDC 2026 大会上由 CEO 张建中正式发布。VRAM\(显存\)容量是决定 GPU 性能的关键因素之一，目前消费级显卡中最高显存容量为 NVIDIA RTX 5090 的 32GB。

**「潜在影响」** 如果属实，64GB 显存将使庐山 GPU 成为消费级显卡中显存最大的产品，可能为高分辨率游戏、专业渲染和 AI 应用提供更强支持，满足高端用户对大显存的需求。

**标签**: `#GPUs`, `#VRAM`, `#Moore Thread`, `#Gaming hardware`, `#AI hardware`

---

## 科技博客

<a id="item-tech-blog-1"></a>
### [避免错误，编写好代码](https://seangoedecke.com/to-code-well-avoid-blunders/) ⭐️ 5.0/10

rss · Sean Goedecke · 11月22日 00:00

**「背景」** 许多工程师认为编程的关键在于产生 brilliant insights，但实际上避免灾难性错误才是编写好代码的核心。编程不同于篮球等运动，无法建立持久的优势，一个错误就可能使优雅的代码库变得混乱。

**「方案」** 作者指出编程中的主要错误包括引入并行系统、创建第二个数据源、将安全同步操作变为复杂异步操作、增加新的故障点和复杂化关键接口。最危险的错误是不一致性和引入不必要的需求。不一致会破坏信任，而不必要的需求则因其粘性和组合爆炸效应而危险。编写代码时应专注于将任务自然融入现有代码库，并将其缩减为最小的需求集，避免被&quot;聪明技巧&quot;分散注意力。

**「启示」** 优秀的编程工作不需要过于聪明，而是需要注重细节和专注于真正重要的事情：通过保持一致性和跳过不必要的需求来避免错误。

**标签**: `#code-quality`, `#software-engineering`, `#best-practices`, `#avoiding-mistakes`, `#technical-writing`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [英媒揭英伟达芯片走私网络：柬埔寨太子集团涉案人员被指参与对华走私](https://www.ft.com/content/f3ad8a81-3890-4a8a-8853-ff0a94b08ba9?syn-25a6b1a6=1) ⭐️ 7.0/10

英国《金融时报》报道称，柬埔寨太子集团涉嫌参与价值 46 亿美元的英伟达芯片走私网络，将芯片运入中国。该集团被指拥有涉及空壳公司和地下融资渠道的网络，并利用私人飞机走私货物。

telegram · zaihuapd · 11月22日 04:34

**「背景」** 美国财政部此前已将柬埔寨太子集团列为制裁对象，指控其参与网络诈骗活动，而此次芯片走私事件发生在全球加强对华半导体出口管制的背景下。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://novayagazeta.co/news/389269-u-s-treasury-imposes-sweeping-sanctions-on-cambodia-s-prince-group-over-alleged-cyber-scam-operations/">Cambodia ’s Prince Group targeted by sweeping U . S . Treasury ...</a></li>
<li><a href="https://www.straitstimes.com/singapore/courts-crime/spore-investigating-2-men-linked-to-prince-group-after-us-sanctions-600m-in-assets-seized-so-far">S’pore investigating 2 men linked to Prince Group hit by US sanctions ...</a></li>
<li><a href="https://cryptobriefing.com/taiwan-nvidia-chip-smuggling-china/">Taiwan suspects smuggling of Nvidia chips to China via Japan in...</a></li>

</ul>
</details>

**标签**: `#Semiconductor smuggling`, `#NVIDIA`, `#International trade`, `#Supply chain`, `#Allegations`

---

<a id="item-finance-news-2"></a>
### [中国要求美国撤销电话号段接入限制](https://www.bloomberg.com/news/articles/2026-11-22/china-objects-to-us-curbs-on-telecoms-access-to-phone-numbers) ⭐️ 7.0/10

中国商务部 11 月 22 日敦促美国撤销禁止三大中国电信运营商直接获取美国电话号码的措施，称此举违反公平竞争原则并可能导致两国在科技领域脱钩。

telegram · zaihuapd · 11月22日 06:44

**「背景」** 美国联邦通信委员会\(FCC\)于 11 月 19 日投票禁止中国三大电信运营商直接获取美国电话号码，理由是国家安全风险。中国商务部随后于 11 月 22 日敦促美国撤销这一措施，称其违反非歧视与公平竞争原则，并警告此举将导致两国在电信、通信及检测认证领域脱钩。

**「潜在影响」** 此举可能影响中美电信企业的国际业务拓展和跨境通信服务，加剧两国科技领域的竞争与脱钩趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.reuters.com/world/fcc-votes-ban-chinese-telecoms-direct-access-us-phone-numbers-2026-11-19/">FCC votes to ban Chinese telecoms from direct access to US ...</a></li>
<li><a href="https://journalrecord.com/2026/11/19/fcc-chinese-telecom-firms-us-phone-number-access-ban/">FCC blocks Chinese telecom firms from US phone number access</a></li>
<li><a href="https://www.jpost.com/international/article-915665">China slams US FCC ban on direct phone number access for Chinese ...</a></li>
<li><a href="https://www.foxbusiness.com/politics/fcc-bans-chinese-firms-direct-access-us-phone-numbers-bid-curb-robocalls">FCC regulators bar Chinese telecom giants from direct... | Fox Business</a></li>

</ul>
</details>

**标签**: `#telecom-regulation`, `#US-China-relations`, `#national-security`, `#trade-policy`, `#tech-sector`

---

<a id="item-finance-news-3"></a>
### [美股科技股遭血洗，亚洲股市严阵以待](https://news.bjd.com.cn/2026/11/22/12039852.shtml) ⭐️ 7.0/10

Major US tech stock decline prompts coordinated regulatory responses across Asian markets to stabilize financial conditions.

telegram · zaihuapd · 11月22日 13:24

**标签**: `#market volatility`, `#tech stocks`, `#regulatory response`, `#Asian markets`, `#short selling`

---