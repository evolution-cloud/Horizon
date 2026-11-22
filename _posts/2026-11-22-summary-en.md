---
layout: default
title: "Horizon Summary: 2026-11-22 (EN)"
date: 2026-11-22
lang: en
---

> From 26 items, 10 important content pieces were selected

---

**Technology News**
1. [What Happened to Silicon Valley?](#item-tech-news-1) ⭐️ 7.0/10
2. [OpenAI&\#x27;s Perplexity as AI Intelligence Metric Sparks Debate](#item-tech-news-2) ⭐️ 7.0/10
3. [Muru: Rust-Based Python Server from mod\_wsgi Creator](#item-tech-news-3) ⭐️ 7.0/10
4. [🚘 特斯拉开始推送 FSD v15](#item-tech-news-4) ⭐️ 7.0/10
5. [Phison Launches 488TB Space-Optimized SSD for Orbital Data Center](#item-tech-news-5) ⭐️ 7.0/10
6. [Moore Thread Claims Lushan GPU Will Feature 64GB VRAM](#item-tech-news-6) ⭐️ 7.0/10

**Technology Blog**
1. [Avoiding Blunders Over Brilliant Insights](#item-tech-blog-1) ⭐️ 5.0/10

**Financial News**
1. [NVIDIA Chip Smuggling Network Allegedly Involving Cambodian Group](#item-finance-news-1) ⭐️ 7.0/10
2. [China Objects to US Telecom Access Restrictions](#item-finance-news-2) ⭐️ 7.0/10
3. [美股科技股遭血洗，亚洲股市严阵以待](#item-finance-news-3) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [What Happened to Silicon Valley?](https://www.oreilly.com/radar/what-happened-to-silicon-valley/) ⭐️ 7.0/10

An analysis of Silicon Valley&\#x27;s evolution, examining economic factors and market dynamics that have shaped the modern tech landscape.

hackernews · greenyouse · Nov 22, 19:20 · [Discussion](https://news.ycombinator.com/item?id=50602947)

**Tags**: `#silicon-valley`, `#tech-industry`, `#market-dynamics`, `#capitalism`, `#web-evolution`

---

<a id="item-tech-news-2"></a>
### [OpenAI&\#x27;s Perplexity as AI Intelligence Metric Sparks Debate](https://openai.com/index/perplexity-and-intelligence/) ⭐️ 7.0/10

OpenAI published an article discussing perplexity as a measure of AI intelligence, generating significant debate in the AI community. The article appears to propose that certain abilities &\#x27;emerge&\#x27; at specific perplexity thresholds, though it doesn&\#x27;t clearly define what perplexity metric is being used or on what tasks it&\#x27;s measured. The article notes that GPT-4.5 shows a discontinuity in perplexity metrics, suggesting a significant advancement in AI capabilities at that point.

hackernews · acossta · Nov 22, 17:06 · [Discussion](https://news.ycombinator.com/item?id=50601525)

**「Understanding Perplexity」** Perplexity is a statistical measure in information theory that evaluates how well a probability model predicts a sample. In the context of language models, perplexity measures a model&\#x27;s uncertainty when predicting the next token based on preceding context. A lower perplexity value indicates better predictive performance, as it means the model assigns higher probabilities to the actual tokens in the sequence. This metric has become increasingly relevant in evaluating AI intelligence, particularly as OpenAI and other researchers analyze model capabilities across different tasks and complexity levels.

**「Impact」** The article&\#x27;s focus on perplexity as a key metric for AI intelligence could shift industry evaluation standards, potentially leading to more emphasis on this metric over others like accuracy or task-specific benchmarks. However, without clear definitions of what perplexity is being measured on, this shift might be premature and could lead to misaligned evaluation priorities.

**「Community Discussion」** The community raised significant concerns about the article&\#x27;s lack of clarity regarding what perplexity metric is being used and on what tasks it&\#x27;s measured. One commenter noted that &\#x27;perplexity is a measure like accuracy, where the next question has to be &\#x27;accuracy at doing what&\#x27; or &\#x27;perplexity on what?&\#x27;&\#x27; Others questioned the claim that specific abilities &\#x27;emerge&\#x27; at given perplexity thresholds, pointing out that smaller models trained specifically on math might have higher general perplexity on other tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Perplexity">Perplexity - Wikipedia</a></li>
<li><a href="https://www.geeksforgeeks.org/nlp/perplexity-for-llm-evaluation/">Perplexity for LLM Evaluation - GeeksforGeeks</a></li>
<li><a href="https://www.statology.org/understanding-perplexity-statistical-measure-language-model-performance/">Understanding Perplexity as a Statistical Measure of Language ...</a></li>

</ul>
</details>

**Tags**: `#AI metrics`, `#language models`, `#perplexity`, `#OpenAI`, `#evaluation`

---

<a id="item-tech-news-3"></a>
### [Muru: Rust-Based Python Server from mod\_wsgi Creator](https://simonwillison.net/2026/Nov/21/muru/) ⭐️ 7.0/10

Graham Dumpleton, creator of mod\_wsgi, has launched Muru, a new Rust-based server designed to run ASGI and WSGI Python applications in both development and production environments. The project utilizes AI-assisted development and features extensive documentation published daily over a three-week period, covering topics from worker internals to Kubernetes integration. Dumpleton emphasizes that while AI assists in development, his 20 years of experience with mod\_wsgi guides the refinement process until the product achieves production-ready reliability.

rss · Simon Willison · Nov 21, 23:56

**「Background」** Graham Dumpleton, creator of mod\_wsgi, has developed Muru, a new Rust-based server for Python applications. The Python web server landscape has evolved significantly from synchronous WSGI to asynchronous ASGI, which is now the default for modern frameworks like FastAPI and Starlette. This shift represents a fundamental change in how Python web applications handle concurrency and performance, making a new server implementation that bridges both WSGI and ASGI potentially significant for the ecosystem.

**「Potential Performance Improvements for Python Web Deployment」** Muru could significantly impact Python web application deployment by leveraging Rust&\#x27;s performance characteristics while maintaining compatibility with existing WSGI and ASGI frameworks. Its approach of &\#x27;import once, fork many&\#x27; and canary deployment without a service mesh may offer more efficient resource utilization and zero-scaling capabilities compared to traditional Python servers.

**Tags**: `#Python`, `#Web Development`, `#Rust`, `#AI-assisted Development`, `#Server Technology`

---

<a id="item-tech-news-4"></a>
### [🚘 特斯拉开始推送 FSD v15](https://x.com/Tesla/status/2124222447855743019) ⭐️ 7.0/10

Tesla releases FSD v15 with substantial safety improvements and new visualization interface for autonomous driving.

telegram · zaihuapd · Nov 22, 00:03

**Tags**: `#autonomous-driving`, `#tesla`, `#ai-safety`, `#automotive-software`, `#fsd`

---

<a id="item-tech-news-5"></a>
### [Phison Launches 488TB Space-Optimized SSD for Orbital Data Center](https://videocardz.com/newz/phison-announces-488tb-of-ssd-storage-for-space-data-centers-pricing-expected-to-be-astronomical) ⭐️ 7.0/10

Phison has launched the Pascari Space SSD series, specialized for spacecraft, satellites, and in-orbit data centers, with the highest capacity reaching 488 TB. These SSDs will be deployed in Lonestar Data Holdings&\#x27; StarVault-001 orbital data center, scheduled for launch in the first half of 2027, providing approximately 370 TB of usable capacity in low Earth orbit. The series includes three categories: Flight Critical, Main Storage, and Orbital Data Center, with the highest individual capacity being 128 TB. Phison claims that using pSLC technology can increase write lifespan by up to 60 times in certain models, and the products are already available on the market.

telegram · zaihuapd · Nov 22, 10:31

**「Orbital Data Centers」** Orbital data centers represent an emerging trend in space technology, positioning AI data processing and storage systems in sun-synchronous orbits to potentially reduce the land, electricity, and water requirements of terrestrial data centers. Several companies, including Lonestar Data Holdings with its StarVault platform, have begun developing these space-based infrastructure solutions despite facing significant engineering and economic barriers to deployment.

**「Impact」** The availability of high-capacity, space-optimized SSDs will enable more sophisticated in-orbit data processing and storage capabilities for satellite operators and space agencies, potentially reducing dependency on ground stations for data processing and enabling real-time analysis of space-based data.

<details><summary>References</summary>
<ul>
<li><a href="https://www.gao.gov/products/gao-26-109012">Science &amp; Tech Spotlight: Data Centers in Space | U.S. GAO</a></li>
<li><a href="https://spectrum.ieee.org/orbital-data-center-hype">Orbital Data Centers: Why the Hype Outpaces Reality - IEEE ...</a></li>

</ul>
</details>

**Tags**: `#storage-technology`, `#space-technology`, `#hardware-innovation`, `#data-center`, `#satellite-technology`

---

<a id="item-tech-news-6"></a>
### [Moore Thread Claims Lushan GPU Will Feature 64GB VRAM](https://www.tomshardware.com/pc-components/gpus/moore-threads-next-lushan-gaming-gpu-could-pack-a-record-64gb-of-vram-doubles-the-rtx-5090s-32gb-lofty-claims-of-15x-gaming-and-50x-ray-tracing-over-mtt-s80) ⭐️ 7.0/10

According to a Moore Thread product manager, the upcoming Lushan gaming GPU will feature 64GB of VRAM, double the RTX 5090&\#x27;s 32GB. The claims, which are not official company announcements, also indicate performance targets of 15x gaming performance, 50x ray tracing, and 64x AI compute over the current MTT S80. The CEO is scheduled to announce the new flagship product at MDC 2026 on December 29-30 in Beijing.

telegram · zaihuapd · Nov 22, 15:11

**「Background」** Moore Thread is a Chinese GPU manufacturer that previously released the MTT S80, their current consumer graphics card with 16GB of VRAM. The company&\#x27;s upcoming Lushan GPU represents their next-generation product, with claims of significantly increased VRAM capacity and performance targets that would substantially exceed current consumer offerings if realized.

**「Impact」** If verified, the 64GB VRAM would make the Lushan GPU the highest memory capacity consumer GPU available, potentially enabling higher resolution textures and more complex AI workloads for professionals and enthusiasts.

**Tags**: `#GPUs`, `#VRAM`, `#Moore Thread`, `#Gaming hardware`, `#AI hardware`

---

## Technology Blog

<a id="item-tech-blog-1"></a>
### [Avoiding Blunders Over Brilliant Insights](https://seangoedecke.com/to-code-well-avoid-blunders/) ⭐️ 5.0/10

rss · Sean Goedecke · Nov 22, 00:00

**「Background」** The author challenges the common belief that good programming comes from brilliant insights, arguing instead that avoiding catastrophic mistakes is the true key to writing good code. This perspective shifts focus from creating clever solutions to maintaining consistency and minimizing unnecessary requirements in codebases.

**「Solution」** The author compares programming to chess and tennis, where avoiding mistakes \(like hanging pieces or unforced errors\) leads to victory more reliably than brilliant plays. In programming, specific blunders include introducing parallel systems, multiple sources of truth, unnecessary async operations, adding failure points, and complicating interfaces. These mistakes create dangerous inconsistency and unnecessary requirements that become sticky in codebases, forcing engineers to account for complex interactions. The author advises programmers to identify where tasks fit naturally into existing codebases and trim requirements to the minimum necessary, warning that &\#x27;clever&\#x27; solutions often distract from this primary goal. This approach prevents the combinatorial explosion that makes large codebases difficult to maintain.

**「Takeaway」** Exceptional programming comes not from brilliant insights but from meticulous attention to avoiding blunders through consistency and minimal requirements, as these prevent the small mistakes that can catastrophically undermine code quality.

**Tags**: `#code-quality`, `#software-engineering`, `#best-practices`, `#avoiding-mistakes`, `#technical-writing`

---

## Financial News

<a id="item-finance-news-1"></a>
### [NVIDIA Chip Smuggling Network Allegedly Involving Cambodian Group](https://www.ft.com/content/f3ad8a81-3890-4a8a-8853-ff0a94b08ba9?syn-25a6b1a6=1) ⭐️ 7.0/10

The Financial Times reports on an alleged $4.6 billion NVIDIA chip smuggling network involving Cambodia&\#x27;s Crown Prince Group with international trade implications.

telegram · zaihuapd · Nov 22, 04:34

**「Background」** The US Treasury has previously designated Cambodia&\#x27;s Prince Group and its members, including Hu Xiaowei as the &\#x27;second in command&\#x27;, with multiple countries including Singapore and the UK also imposing sanctions on the network over alleged criminal activities.

<details><summary>References</summary>
<ul>
<li><a href="https://novayagazeta.co/news/389269-u-s-treasury-imposes-sweeping-sanctions-on-cambodia-s-prince-group-over-alleged-cyber-scam-operations/">Cambodia ’s Prince Group targeted by sweeping U . S . Treasury ...</a></li>
<li><a href="https://www.straitstimes.com/singapore/courts-crime/spore-investigating-2-men-linked-to-prince-group-after-us-sanctions-600m-in-assets-seized-so-far">S’pore investigating 2 men linked to Prince Group hit by US sanctions ...</a></li>
<li><a href="https://repost.news/news/119371-the_u.k._imposes_sanctions_on_the_prince_group_network_due_to_suspected_connections_to_human_trafficking_activities">The U.K. imposes sanctions on the Prince Group network due to...</a></li>

</ul>
</details>

**Tags**: `#Semiconductor smuggling`, `#NVIDIA`, `#International trade`, `#Supply chain`, `#Allegations`

---

<a id="item-finance-news-2"></a>
### [China Objects to US Telecom Access Restrictions](https://www.bloomberg.com/news/articles/2026-11-22/china-objects-to-us-curbs-on-telecoms-access-to-phone-numbers) ⭐️ 7.0/10

China urged the US on November 22 to revoke restrictions preventing its three largest telecom operators from directly accessing US phone numbers, claiming the measures violate fair competition principles and lack factual national security justification.

telegram · zaihuapd · Nov 22, 06:44

**「Background」** The US Federal Communications Commission recently banned Chinese telecom firms including China Mobile, China Telecom, and China Unicom from direct access to US phone numbers on national security grounds, prompting China&\#x27;s formal diplomatic objection.

**「Impact」** The restrictions could lead to decoupling in telecom, communication, and certification sectors between the two largest economies, potentially affecting cross-border telecommunications services and international business operations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reuters.com/world/fcc-votes-ban-chinese-telecoms-direct-access-us-phone-numbers-2026-11-19/">FCC votes to ban Chinese telecoms from direct access to US ...</a></li>
<li><a href="https://journalrecord.com/2026/11/19/fcc-chinese-telecom-firms-us-phone-number-access-ban/">FCC blocks Chinese telecom firms from US phone number access</a></li>
<li><a href="https://www.jpost.com/international/article-915665">China slams US FCC ban on direct phone number access for Chinese ...</a></li>
<li><a href="https://www.foxbusiness.com/politics/fcc-bans-chinese-firms-direct-access-us-phone-numbers-bid-curb-robocalls">FCC regulators bar Chinese telecom giants from direct... | Fox Business</a></li>

</ul>
</details>

**Tags**: `#telecom-regulation`, `#US-China-relations`, `#national-security`, `#trade-policy`, `#tech-sector`

---

<a id="item-finance-news-3"></a>
### [美股科技股遭血洗，亚洲股市严阵以待](https://news.bjd.com.cn/2026/11/22/12039852.shtml) ⭐️ 7.0/10

Major US tech stock decline prompts coordinated regulatory responses across Asian markets to stabilize financial conditions.

telegram · zaihuapd · Nov 22, 13:24

**Tags**: `#market volatility`, `#tech stocks`, `#regulatory response`, `#Asian markets`, `#short selling`

---