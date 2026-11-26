---
layout: default
title: "Horizon Summary: 2026-11-26 (EN)"
date: 2026-11-26
lang: en
---

> From 36 items, 16 important content pieces were selected

---

**Technology News**
1. [AMD Patches Boost Llama.cpp Performance on Older Cards](#item-tech-news-1) ⭐️ 8.0/10
2. [Lions&\#x27; Commentary on Unix: Why It Was Secretly Copied for 20 Years](#item-tech-news-2) ⭐️ 8.0/10
3. [Novel Approach to Quantizing Gravity Using Null Cones](#item-tech-news-3) ⭐️ 8.0/10
4. [Quoting Scott Aaronson](#item-tech-news-4) ⭐️ 8.0/10
5. [FCC Approves SpaceX&\#x27;s 1-Million-Satellite Starmind Data Center](#item-tech-news-5) ⭐️ 8.0/10
6. [Huawei Announces New HBM Chip with Doubled Data Pin Density](#item-tech-news-6) ⭐️ 8.0/10
7. [China Plans 2030 New Communication Network with 6G Development](#item-tech-news-7) ⭐️ 8.0/10
8. [Neuralink 脑机接口获 FDA 批准，将启动渐冻症关键临床试验](#item-tech-news-8) ⭐️ 8.0/10
9. [NVIDIA Halts AI Server Shipments to Four Southeast Asian Countries](#item-tech-news-9) ⭐️ 8.0/10
10. [阿斯麦 CEO：全面断供中国，只会逼中国自己造](#item-tech-news-10) ⭐️ 8.0/10
11. [Google Restricts AI Agents to MCP Servers, Gmail Agent Can&\#x27;t Send Email](#item-tech-news-11) ⭐️ 7.0/10
12. [NYT Warns Photographers Against Photoshop AI Updates](#item-tech-news-12) ⭐️ 7.0/10
13. [Evaluating Recent Model Releases on GDPx](#item-tech-news-13) ⭐️ 7.0/10
14. [🤖 Claude Opus 5.6 仅凭一段提示生成高质量演示文稿](#item-tech-news-14) ⭐️ 7.0/10
15. [Chinese AI Model Releases Delayed Due to Anti-Distillation Measures](#item-tech-news-15) ⭐️ 7.0/10

**Financial News**
1. [Dutch Opposes US ASML Sales Restrictions to China](#item-finance-news-1) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [AMD Patches Boost Llama.cpp Performance on Older Cards](https://devnull.land/amd-specific-llama-cpp) ⭐️ 8.0/10

AMD-specific patches significantly improve performance for running large language models on older, cost-effective AMD graphics cards. These circa 2018 gfx906 datacenter cards offer 32GB VRAM with 1TB/s bandwidth at a fraction of the cost of current alternatives, previously underutilized due to lack of tensor cores and native bf16 support. Users report processing speeds of 2400 tok/s and decoding at 150 tok/s with 4-bit quantized models, enabling 3 concurrent agent streams with 200k context entirely in VRAM.

hackernews · julianlam · Nov 26, 17:11 · [Discussion](https://news.ycombinator.com/item?id=50657265)

**「Background」** Llama.cpp is an open-source implementation of Meta&\#x27;s LLaMA language model that allows running large language models on consumer hardware. AMD&\#x27;s circa 2018 gfx906 datacenter series cards, while lacking modern features like tensor cores and native bf16 support, offer exceptional value with 32GB HBM2 memory providing 1TB/s bandwidth at approximately $200, making them attractive for cost-effective AI inference. The specific patches address the hardware&\#x27;s architectural limitations to optimize performance for these older AMD cards.

**「Democratizing AI Access」** These AMD-specific patches enable developers and researchers to run large language models with high performance on older, cost-effective AMD hardware, making advanced AI capabilities more accessible. Users have reported processing speeds of 2400 tokens/second and the ability to run multiple concurrent agent streams with large context sizes entirely in VRAM, democratizing access to powerful AI tools that were previously limited to expensive modern hardware.

**「User Experiences」** Users have developed a rich ecosystem of optimizations for these AMD cards, with one user reporting they doubled or tripled Claude&\#x27;s performance on Qwen3.8 by aggressively optimizing AMD code and porting Nvidia kernels to ROCm. Another user recommends the Radiance engine for r9700 cards, noting stability after a month of intensive agentic and coding work.

**Tags**: `#AI Optimization`, `#Hardware Acceleration`, `#Open Source`, `#Cost-Effective AI`, `#Llama.cpp`

---

<a id="item-tech-news-2"></a>
### [Lions&\#x27; Commentary on Unix: Why It Was Secretly Copied for 20 Years](https://fosscomics.com/posts/17.%20Lions%27%20Commentary%20on%20Unix/) ⭐️ 8.0/10

The article reveals the hidden history of John Lions&\#x27; Unix commentary, a document that secretly influenced computer science education for decades despite copyright restrictions.

hackernews · joonehur · Nov 26, 05:12 · [Discussion](https://news.ycombinator.com/item?id=50651719)

**Tags**: `#unix-history`, `#operating-systems`, `#software-heritage`, `#computer-science-education`, `#legal-tech`

---

<a id="item-tech-news-3"></a>
### [Novel Approach to Quantizing Gravity Using Null Cones](https://arxiv.org/abs/2611.34924) ⭐️ 8.0/10

The paper proposes a novel approach to background independent quantization of vacuum general relativity on four-dimensional Lorentzian spacetimes. The authors solve gravitational constraints on intersecting null cones of a bulk subregion to obtain a reduced phase space at finite GN, then promote canonical Poisson brackets to commutation relations. They use deformations of the reduced action to define an algebra of observables and employ Gaussian wavefunctions in their framework.

hackernews · hecmmm · Nov 26, 05:37 · [Discussion](https://news.ycombinator.com/item?id=50651863)

**「Background」** Quantum gravity aims to reconcile quantum mechanics with general relativity, two pillars of modern physics that describe different scales of the universe. Background independence is a fundamental principle in general relativity where spacetime geometry is dynamic rather than fixed, but quantizing gravity while preserving this principle has proven extremely challenging. The paper introduces a novel approach by solving gravitational constraints on intersecting null cones—light-like surfaces in spacetime—which may offer a path to a background-independent quantum theory of gravity.

**「Impact」** This approach could provide a mathematically rigorous path to quantizing gravity while maintaining background independence, potentially resolving long-standing issues in quantum gravity research.

**「Community Discussion」** The r/Physics subreddit moderators noted that while there&\#x27;s significant discussion about the paper, most comments focus on AI rather than the quantum gravity content itself, with much of it being hostile. They recommended waiting for field experts to review the paper before drawing conclusions.

**Tags**: `#quantum\_gravity`, `#theoretical\_physics`, `#mathematical\_physics`, `#research\_paper`, `#physics\_debate`

---

<a id="item-tech-news-4"></a>
### [Quoting Scott Aaronson](https://simonwillison.net/2026/Nov/25/scott-aaronson/) ⭐️ 8.0/10

Scott Aaronson describes a major breakthrough in complexity theory as opening up &\#x27;a whole new continent of mathematical truth&\#x27; with potentially revolutionary implications for mathematics and AI research.

rss · Simon Willison · Nov 25, 23:26

**Tags**: `#complexity-theory`, `#mathematics`, `#ai`, `#theoretical-computer-science`, `#breakthrough`

---

<a id="item-tech-news-5"></a>
### [FCC Approves SpaceX&\#x27;s 1-Million-Satellite Starmind Data Center](https://www.geekwire.com/2026/fcc-clears-spacex-million-satellites-starmind-data-center/) ⭐️ 8.0/10

The FCC has approved SpaceX&\#x27;s deployment of up to 1 million satellites for the Starmind in-orbit data processing network, marking the first approval of a space-based data center constellation in U.S. history. The satellites will operate at altitudes between 500 to 1,002 kilometers, with the first satellite required to be operational by 2033 and the entire constellation fully operational by 2040. The approval includes conditions for communication backup, regular progress reports, and detailed orbital debris mitigation plans, despite objections from Amazon, Viasat, and the American Astronomical Society.

telegram · zaihuapd · Nov 26, 04:45

**「Background」** Starmind is SpaceX&\#x27;s AI satellite constellation designed to function as orbital data centers, with each satellite featuring a compute payload of 175 kW on average and up to 250 kW. This approval follows SpaceX&\#x27;s January 2026 FCC authorization for its second-generation Starlink satellite system, which included plans to modify previously granted licenses to operate satellites at lower orbital altitudes. The American Astronomical Society had raised concerns about the potential impact of such a large constellation on astronomical observations, while Amazon and Viasat opposed the proposal on competitive grounds.

**「Potential Consequences」** This approval could revolutionize global data processing by enabling real-time computation in space, potentially reducing latency for data-intensive applications and creating new opportunities for distributed computing architectures that leverage orbital positions closer to end-users.

<details><summary>References</summary>
<ul>
<li><a href="https://aiwiki.ai/wiki/spacex_starmind">SpaceX Starmind | AI Wiki</a></li>
<li><a href="https://www.satellitetoday.com/connectivity/2026/11/25/fcc-approves-spacexs-1-million-satellite-orbital-data-center-constellation/">FCC Approves SpaceX ’s 1-Million Satellite Orbital Data Center ...</a></li>
<li><a href="https://www.notebookcheck.net/SpaceX-names-its-AI-Orbital-Data-Center-satellite-constellation.1328148.0.html">SpaceX names its AI Orbital Data Center satellite constellation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Starlink">Starlink - Wikipedia</a></li>
<li><a href="https://docs.fcc.gov/public/attachments/DOC-417881A1.pdf">FCC Approves Next-Gen Satellite Constellation</a></li>
<li><a href="https://www.fcc.gov/document/fcc-approves-next-gen-satellite-constellation">FCC Approves Next-Gen Satellite Constellation</a></li>
<li><a href="https://www.geekwire.com/2026/fcc-clears-spacex-million-satellites-starmind-data-center/">FCC clears SpaceX to put a million data center satellites in ...</a></li>
<li><a href="https://apnews.com/article/spacex-data-center-elon-musk-b9897fe06f851ffaf92fd304ae69075c">Trump administration approves SpaceX&#x27;s ambitious satellite ...</a></li>
<li><a href="https://aas.org/action-alert-provide-input-fcc-proposed-satellite-systems">Action Alert: Provide Input to the FCC on Proposed Satellite ...</a></li>

</ul>
</details>

**Tags**: `#satellite technology`, `#space infrastructure`, `#data processing`, `#telecommunications`, `#spaceX`

---

<a id="item-tech-news-6"></a>
### [Huawei Announces New HBM Chip with Doubled Data Pin Density](https://www.bloomberg.com/news/articles/2026-11-26/huawei-teases-next-gen-ai-memory-chip-to-take-on-samsung-hynix) ⭐️ 8.0/10

Huawei is set to announce details of a new high-bandwidth memory \(HBM\) chip that features data pin density double that of current Samsung Electronics and SK Hynix products. The company plans to publish research on this advancement at a conference in San Francisco next February. This development is particularly significant as Huawei pushes for localized production of HBM components in China, which are currently restricted by US sanctions.

telegram · zaihuapd · Nov 26, 05:30

**「Background on High Bandwidth Memory」** High Bandwidth Memory \(HBM\) is a computer memory interface for 3D-stacked synchronous dynamic random-access memory \(SDRAM\) that provides significantly higher bandwidth than traditional memory solutions. It was initially developed by Samsung, AMD, and SK Hynix and is commonly used in performance-oriented graphics accelerators, network devices, and AI applications. The HBM market is highly concentrated, with the top three companies \(SK Hynix, Samsung, and Micron\) controlling over 90% of the market, making Huawei&\#x27;s entry into this space particularly noteworthy.

**「Impact on AI Hardware」** Huawei&\#x27;s new HBM chip with doubled data pin density could enable more powerful AI systems with significantly higher memory bandwidth, addressing the critical &\#x27;memory wall&\#x27; challenge that limits AI performance. This development may provide organizations affected by US sanctions with an alternative high-performance memory solution, potentially reshaping the competitive landscape in the AI hardware market.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/High_Bandwidth_Memory">High Bandwidth Memory - Wikipedia</a></li>
<li><a href="https://www.linkedin.com/pulse/samsung-best-positioned-win-high-bandwidth-memory-race-jeff-morrison-utgpc">There&#x27;s Room for Three Horses in the HBM Memory Race...</a></li>
<li><a href="https://www.marketresearchfuture.com/reports/high-bandwidth-memory-market-21582">High Bandwidth Memory Market Report Size, Share and Trends 2035</a></li>
<li><a href="https://www.embedded.com/high-bandwidth-memory-hbm-options-for-demanding-compute/">High-bandwidth memory ( HBM ) options for demanding compute</a></li>
<li><a href="https://www.youtube.com/watch?v=q0sKjYba6gs">What Is HBM ? The Memory Behind AI - YouTube</a></li>

</ul>
</details>

**Tags**: `#semiconductors`, `#AI hardware`, `#memory technology`, `#geopolitics`, `#Huawei`

---

<a id="item-tech-news-7"></a>
### [China Plans 2030 New Communication Network with 6G Development](https://www.news.cn/politics/20261126/9fe827a2d98741acb60f62d36ba89cf7/c.html) ⭐️ 8.0/10

China&\#x27;s Ministry of Industry and Information Technology, Cyberspace Administration, and National Development and Reform Commission have jointly issued the &\#x27;Implementation Plan for New Generation Communication Network Construction&\#x27; with a goal to build a comprehensive, high-performance new generation communication network by 2030. The plan includes timely development of 6G networks, completion of low-orbit satellite internet systems, and large-scale development of industrial internet and vehicle internet networks. The plan also promotes 5G-A network coverage and accelerates standard development for 6G, satellite internet, and computing-network integration.

telegram · zaihuapd · Nov 26, 06:30

**「Background」** China has been actively developing its 6G strategy through established roadmaps and collaborative initiatives. In June 2026, China launched a ministry-provincial collaborative pilot program to advance 6G technical research, testing, and validation based on key scenarios and performance indicators defined by the International Telecommunication Union. The country has previously outlined a comprehensive 6G Development Roadmap that defines key stages and goals for technology research and development, standards formulation, and commercial deployment.

**「Strategic Implications」** This national commitment will likely accelerate China&\#x27;s technological leadership in next-generation communication technologies, potentially influencing global research priorities and creating new opportunities for domestic technology companies specializing in 6G, satellite communications, and AI integration.

<details><summary>References</summary>
<ul>
<li><a href="https://cn.ibtimes.com/china-6g-satellite-internet-roadmap-2030-1812837">China Unveils 2030 Roadmap for 6G Development and Nationwide ...</a></li>
<li><a href="http://english.scio.gov.cn/pressroom/2026-06/05/content_118532323.html">China launches ministry-provincial collaborative pilot ...</a></li>
<li><a href="https://baike.baidu.com/en/item/6G+Development+Roadmap/6536513">6G Development Roadmap_Baiduwiki - 百度百科</a></li>

</ul>
</details>

**Tags**: `#6G`, `#Communication Infrastructure`, `#Technology Policy`, `#Network Development`, `#China Tech Strategy`

---

<a id="item-tech-news-8"></a>
### [Neuralink 脑机接口获 FDA 批准，将启动渐冻症关键临床试验](https://www.bloomberg.com/news/articles/2026-11-25/neuralink-gets-clearance-for-brain-implant-trial-in-als-patients?srnd=phx-technology) ⭐️ 8.0/10

Neuralink receives FDA approval to conduct pivotal clinical trials of its brain-computer interface for ALS patients.

telegram · zaihuapd · Nov 26, 07:15

**Tags**: `#brain-computer-interface`, `#medical-technology`, `#neuralink`, `#FDA-approval`, `#ALS-research`

---

<a id="item-tech-news-9"></a>
### [NVIDIA Halts AI Server Shipments to Four Southeast Asian Countries](https://www.ft.com/content/7838a715-07d4-4605-aa60-21f5af2b2370) ⭐️ 8.0/10

NVIDIA has instructed manufacturing partners including Dell and Supermicro to suspend shipments of AI servers to Malaysia, Singapore, Thailand, and Indonesia due to new U.S. export controls. The freeze affects these countries which serve as transit points for Chinese AI companies to access NVIDIA&\#x27;s most advanced processors that cannot be directly exported to mainland China. The U.S. Department of Commerce introduced new regulations last week requiring regional cloud service providers to obtain export licenses within 90 days and verify customers do not include restricted Chinese entities.

telegram · zaihuapd · Nov 26, 07:38

**「Export Control Context」** The U.S. has implemented increasingly strict export controls on advanced AI chips to China, citing national security concerns. These controls have previously targeted direct shipments but have now expanded to include indirect routes through third countries. Southeast Asian nations have become critical transit points for Chinese companies seeking access to advanced NVIDIA processors, as these countries have less restrictive trade relationships with both the U.S. and China.

**「Impact」** Chinese AI companies and organizations relying on NVIDIA&\#x27;s advanced processors will face significant disruptions to their hardware supply chains, potentially slowing AI development and deployment in China as they seek alternative sources or workarounds for the restricted technology.

**Tags**: `#AI hardware`, `#International trade`, `#Geopolitics`, `#Supply chain`, `#NVIDIA`

---

<a id="item-tech-news-10"></a>
### [阿斯麦 CEO：全面断供中国，只会逼中国自己造](https://www.semafor.com/article/11/25/2026/asml-makes-the-case-for-selling-chips-to-china) ⭐️ 8.0/10

ASML CEO argues that completely cutting off China from semiconductor equipment would accelerate China&\#x27;s self-reliance efforts rather than maintain dependency.

telegram · zaihuapd · Nov 26, 12:19

**Tags**: `#semiconductors`, `#international-trade`, `#tech-policy`, `#hardware`, `#supply-chain`

---

<a id="item-tech-news-11"></a>
### [Google Restricts AI Agents to MCP Servers, Gmail Agent Can&\#x27;t Send Email](https://techstackups.com/articles/google-workspace-ai-agents-mcp/) ⭐️ 7.0/10

Google is restricting AI agents to use its MCP servers for Workspace integration, with the Gmail AI agent notably unable to send emails despite being designed for email management. This limitation applies to third-party AI agents accessing Google Workspace through the Model Context Protocol \(MCP\) servers, while Google&\#x27;s native Gemini integration maintains full functionality including email sending capabilities. The restriction appears to be a deliberate design choice rather than a technical limitation, as MCP already has primitives for user confirmation before executing sensitive actions.

hackernews · ritzaco · Nov 26, 09:44 · [Discussion](https://news.ycombinator.com/item?id=50653477)

**「Background」** The Model Context Protocol \(MCP\) is an emerging standard that enables AI systems to interact with external tools and data sources. Google&\#x27;s implementation of AI agents through MCP servers represents their approach to integrating AI capabilities into Workspace products, though with notable limitations such as the Gmail AI agent&\#x27;s inability to send emails. This approach has sparked discussion about whether these restrictions stem from genuine technical constraints or deliberate business decisions to control access to certain functionalities.

**「Impact」** Developers and organizations implementing AI agents with Google Workspace will face significant limitations in automation capabilities, particularly for email management tasks, potentially forcing them to work around restrictions through less efficient methods like browser automation.

**「Community Discussion」** The community debate centers on whether the email sending restriction is a safety measure or a business decision to protect Google&\#x27;s ecosystem, with perdy noting that MCP already has primitives for user confirmation that could safely enable email sending, suggesting this is more about creating a walled garden around Gemini as thorio speculates. Schnitz predicts users will resort to inefficient browser automation to bypass these restrictions, while physicsguy observes this trend of restricting API access through usage-based pricing is becoming widespread across tech companies.

**Tags**: `#AI integration`, `#Google Workspace`, `#MCP`, `#Email automation`, `#Enterprise AI`

---

<a id="item-tech-news-12"></a>
### [NYT Warns Photographers Against Photoshop AI Updates](https://simonwillison.net/2026/Nov/26/hn-50651685/) ⭐️ 7.0/10

The New York Times has established guidelines warning professional photographers against using AI features in Photoshop, emphasizing authenticity in photojournalism. According to the publication, photographers should only apply basic adjustments like cropping and color balancing, avoiding any AI-powered modifications that could alter the original image. This stance reflects the newspaper&\#x27;s commitment to presenting photographs as they were taken, with a NYT photographer previously stating they &\#x27;present photographs as they were taken, with cropping and balancing applied but no edits beyond that.&\#x27;

rss · Simon Willison · Nov 26, 05:08

**「Photojournalism Ethics」** Photojournalism has long adhered to strict ethical standards that prohibit significant manipulation of images to maintain authenticity and credibility. Publications like The New York Times historically allow only minimal adjustments such as cropping and color balancing, but forbid altering the actual content of photographs. The emergence of AI-powered features in tools like Photoshop introduces new ethical challenges, as these capabilities can potentially generate or modify image content in ways that undermine journalistic integrity and the trust between photographers and their audiences.

**「Impact」** Photographers working with or aspiring to contribute to The New York Times will need to avoid using Photoshop&\#x27;s AI features, potentially limiting their use of Adobe&\#x27;s latest tools and requiring them to maintain older versions of the software or switch to alternative editing applications that don&\#x27;t incorporate AI capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.psd-dude.com/tutorials/resources/photojournalism-and-ethics.aspx">Photojournalism and Ethics | PSDDude</a></li>
<li><a href="https://retouchinglabs.com/photojournalism-and-ethics/">Photojournalism and Ethics - Retouching Labs</a></li>

</ul>
</details>

**Tags**: `#ai-ethics`, `#photography`, `#adobe-photoshop`, `#media-ethics`, `#professional-practices`

---

<a id="item-tech-news-13"></a>
### [Evaluating Recent Model Releases on GDPx](https://newsletter.semianalysis.com/p/evaluating-recent-model-releases) ⭐️ 7.0/10

Introduction of GDPx, a new benchmark focusing on domains where frontier AI models will have the most significant impact.

rss · Semianalysis · Nov 26, 00:05

**Tags**: `#AI benchmarking`, `#Model evaluation`, `#Frontier intelligence`, `#AI research methodology`, `#Technology metrics`

---

<a id="item-tech-news-14"></a>
### [🤖 Claude Opus 5.6 仅凭一段提示生成高质量演示文稿](https://x.com/fluxxrider/status/2125622238481371372) ⭐️ 7.0/10

Claude Opus 5.6 demonstrates improved creative AI capabilities by generating complex presentations from minimal input.

telegram · zaihuapd · Nov 26, 04:10

**Tags**: `#AI`, `#Large Language Models`, `#Content Creation`, `#Productivity Tools`, `#Claude`

---

<a id="item-tech-news-15"></a>
### [Chinese AI Model Releases Delayed Due to Anti-Distillation Measures](https://www.reuters.com/world/china/us-chip-curbs-distillation-crackdown-threaten-chinese-ai-model-development-2026-11-26/) ⭐️ 7.0/10

Chinese AI companies Z.AI and Moonshot AI are facing significant delays in their flagship model releases due to increasingly effective anti-distillation measures and computing limitations. Z.AI&\#x27;s GLM-5.5, originally planned for this month with approximately 3 trillion parameters, may now be delayed until Q1 2027 or later. Moonshot AI estimates that without overseas computing power, their release cycle would extend from 6 months to over a year, potentially pushing Kimi K4 to mid-2027 as they shift from distilling Anthropic and OpenAI models to Google and Meta&\#x27;s models.

telegram · zaihuapd · Nov 26, 15:14

**「Background」** Distillation is a machine learning technique where developers train smaller models using outputs from larger, more capable models. Recently, U.S. companies like OpenAI and Anthropic have implemented anti-distillation measures to protect their proprietary models, while the U.S. government has accused several Chinese AI firms including Zhipu and Moonshot of &\#x27;illicit distillation&\#x27; - extracting capabilities from American models without authorization. These measures, combined with new U.S. chip curbs restricting China&\#x27;s access to advanced computing resources, have significantly disrupted China&\#x27;s AI development approach.

**「Development Consequences」** The delays will likely result in a slower pace of AI model innovation in China, potentially affecting competitive positioning against global AI leaders and creating uncertainty for enterprise customers who planned to integrate these models into their workflows.

<details><summary>References</summary>
<ul>
<li><a href="https://timewell.jp/en/columns/anthropic-distillation-report-moonshot-kimi-claude-relay-2026">Anthropic Names Seven Chinese Labs for &quot;Illicit Distillation &quot;</a></li>
<li><a href="https://qz.com/us-china-ai-distillation-deepseek-alibaba-intelligence-agencies-090926">U.S. accuses Chinese AI firms of stealing American AI model ...</a></li>
<li><a href="https://www.reuters.com/world/china/us-chip-curbs-distillation-crackdown-threaten-chinese-ai-model-development-2026-11-26/">US chip curbs, distillation crackdown threaten Chinese AI ...</a></li>
<li><a href="https://economictimes.indiatimes.com/tech/artificial-intelligence/us-chip-curbs-distillation-crackdown-threaten-chinese-ai-model-development-sources-say/articleshow/136182809.cms">US chip curbs, distillation crackdown threaten Chinese AI ...</a></li>

</ul>
</details>

**Tags**: `#AI development`, `#geopolitical impact`, `#model training`, `#Chinese AI`, `#technical challenges`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Dutch Opposes US ASML Sales Restrictions to China](https://www.bloomberg.com/news/articles/2026-11-26/netherlands-plans-to-fight-rollout-of-proposed-us-curbs-on-asml) ⭐️ 7.0/10

Dutch Minister Sjoerd Sjoerdsma announced on November 26 that the Netherlands will not accept US restrictions on ASML&\#x27;s sales to China, opposing the MATCH Act&\#x27;s extraterritorial jurisdiction and stating the country &\#x27;will not be pushed around.&\#x27; China accounts for approximately 20% of ASML&\#x27;s annual sales.

telegram · zaihuapd · Nov 26, 14:56

**「Background」** ASML is a Dutch company that manufactures photolithography machines essential for semiconductor production, with China accounting for about 20% of its annual sales. The US MATCH Act, enacted in April 2026, seeks to extend export controls to older-generation chipmaking equipment, targeting China&\#x27;s ability to acquire semiconductor technology.

**「Impact」** The Dutch opposition, coordinated with the EU and supported by Germany and France, could potentially disrupt US efforts to restrict China&\#x27;s access to advanced semiconductor technology and affect global supply chains.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ASML">ASML - Wikipedia</a></li>
<li><a href="https://www.scmp.com/tech/big-tech/article/3370904/asmls-chip-equipment-sales-china-soar-109-despite-us-export-curb-push">ASML’s chip equipment sales to China soar 109% despite US ...</a></li>
<li><a href="https://informedclearly.com/en/trade-war/58105/match-act-semiconductor-export-controls-2026">MATCH Act 2026: Semiconductor Export Controls Reach Critical ...</a></li>

</ul>
</details>

**Tags**: `#International trade`, `#Semiconductor industry`, `#US-China relations`, `#Dutch policy`, `#Export controls`

---