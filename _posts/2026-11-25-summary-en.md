---
layout: default
title: "Horizon Summary: 2026-11-25 (EN)"
date: 2026-11-25
lang: en
---

> From 29 items, 17 important content pieces were selected

---

**Technology News**
1. [OpenAI Claims Matrix Multiplication Exponent is 9/4](#item-tech-news-1) ⭐️ 9.0/10
2. [1Password Security Incident Exposes Developer Vulnerabilities](#item-tech-news-2) ⭐️ 8.0/10
3. [Holy shit holy shit holy shit holy shit: The magnitude of what’s now happening](#item-tech-news-3) ⭐️ 8.0/10
4. [Google releases Cogentic papers on integer factorization, discrete logs and more](#item-tech-news-4) ⭐️ 8.0/10
5. [Three LLM inflection points in twelve months](#item-tech-news-5) ⭐️ 8.0/10
6. [Minecraft 曝高危 RCE 漏洞，Java 版 1.20.5 起全版本受影响](#item-tech-news-6) ⭐️ 8.0/10
7. [Smart people who give a shit use tools](#item-tech-news-7) ⭐️ 7.0/10
8. [Historical GPU Demos Ported to Browser](#item-tech-news-8) ⭐️ 7.0/10
9. [GitHub Service Outage Disrupts Development Work](#item-tech-news-9) ⭐️ 7.0/10
10. [AI Models Can Communicate via Inference Servers Despite Sandboxing](#item-tech-news-10) ⭐️ 7.0/10
11. [LeCun Criticizes Amodei for Using Risk Arguments Against Open Models](#item-tech-news-11) ⭐️ 7.0/10
12. [🤖 OpenAI 押注网络安全，公司称超 3000 亿美元的市场规模估算被低估，网络安全将成为比编程更大的业务板块](#item-tech-news-12) ⭐️ 7.0/10
13. [Tencent Open-Sources Compressed 224B Model for Consumer Hardware](#item-tech-news-13) ⭐️ 7.0/10
14. [Asian Data Centers Shift to US Clients After US Chip Export Rules](#item-tech-news-14) ⭐️ 7.0/10
15. [Samsung, SK Hynix Adopt YMTC&\#x27;s Xtacking Technology](#item-tech-news-15) ⭐️ 7.0/10

**Financial News**
1. [US Plans New Tariffs on 14 Trading Partners Including China and EU](#item-finance-news-1) ⭐️ 9.0/10
2. [🚀 SpaceX 放弃 7.38 亿美元联邦宽带补贴，改为免费送星链设备](#item-finance-news-2) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [OpenAI Claims Matrix Multiplication Exponent is 9/4](https://github.com/openai/math/blob/main/preprints/The-matrix-multiplication-exponent-is-nine-fourths-November-24-2026/paper.pdf) ⭐️ 9.0/10

OpenAI has published a paper claiming to have proven that the matrix multiplication exponent is exactly 9/4, resolving a fundamental open problem in computer science. The paper, dated November 24, 2026, presents a mathematical proof that refutes the previous conjecture and establishes the exact exponent over every field. This result represents a significant theoretical advancement in computational complexity theory.

hackernews · E-Reverance · Nov 25, 01:19 · [Discussion](https://news.ycombinator.com/item?id=50637220)

**「Matrix Multiplication Exponent」** The matrix multiplication exponent, denoted ω, is a fundamental unsolved problem in computer science that seeks to determine the smallest real number for which any two n×n matrices over a field can be multiplied together. This value represents the computational complexity of matrix multiplication, with a lower exponent indicating more efficient algorithms. OpenAI&\#x27;s November 24, 2026 paper claims to have proven that this exponent is exactly 9/4 \(2.25\), establishing matching upper and lower bounds that resolve this decades-old question.

**「Impact」** If verified, this proof would enable more efficient algorithms for matrix operations, potentially accelerating AI and machine learning computations that rely heavily on matrix multiplication. The improved theoretical understanding could lead to practical optimizations in numerical computing and scientific simulations.

**「Community Discussion」** Zone411 notes that OpenAI&\#x27;s papers resolve 8 problems from the Top 500 Open Problems in Math list, including this matrix multiplication exponent problem. StableAlkyne compares OpenAI&\#x27;s research output to Bell Labs but questions whether their breakthroughs serve the public good or primarily PR purposes. BoppreH expresses concern about potential cryptographic implications of such fundamental mathematical advances.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Computational_complexity_of_matrix_multiplication">Computational complexity of matrix multiplication - Wikipedia</a></li>
<li><a href="https://interestingengineering.com/culture/openai-exact-2-25-matrix-multiplication-exponent">OpenAI establishes exact 2.25 exponent for matrix multiplication</a></li>
<li><a href="https://www.alphaxiv.org/abs/2611.matrix-multiplication-exponent-lower-bound">The Matrix Multiplication Exponent Is Nine Fourths | alphaXiv</a></li>

</ul>
</details>

**Tags**: `#matrix multiplication`, `#algorithm complexity`, `#mathematical proof`, `#computer science`, `#AI research`

---

<a id="item-tech-news-2"></a>
### [1Password Security Incident Exposes Developer Vulnerabilities](https://1password.com/blog/update-on-nov-2026-security-incident) ⭐️ 8.0/10

1Password disclosed a security incident on November 25, 2026, that potentially compromised developer account security and production deployment processes. The incident exposes vulnerabilities in how the company manages developer access and deploys code to production systems, which could allow malicious actors to push compromised code to backend services. The company has not clearly stated whether encrypted vault data remained unaffected during the incident, though they claim to have notified a small number of users who were specifically affected.

hackernews · lxhrstn · Nov 25, 17:18 · [Discussion](https://news.ycombinator.com/item?id=50644817)

**「Developer Account Security」** Developer account compromises represent a critical vulnerability for SaaS companies, as access to corporate GitHub accounts can enable attackers to push malicious code to production systems. This attack vector has become increasingly common as companies grow and the likelihood of employee device compromises approaches certainty. The 1Password incident specifically involves unauthorized access to an employee&\#x27;s GitHub account, which could potentially allow attackers to compromise the company&\#x27;s code deployment processes and integrity.

**「User Impact」** Users of 1Password now face increased uncertainty about the security of their password vaults, with potential risks of unauthorized access if malicious code was deployed to production systems. The incident highlights the critical importance of robust developer account security and code deployment protections for SaaS companies handling sensitive user data.

**「Expert Analysis」** Security experts highlight that compromised developer accounts represent the single most important attack vector for SaaS companies, as the likelihood of employee laptops being compromised approaches 1 as companies grow. Commenters specifically criticize 1Password for not sufficiently addressing whether they had proper branch protection rules in place to prevent malicious code from being pushed to production services.

<details><summary>References</summary>
<ul>
<li><a href="https://1password.com/blog/update-on-nov-2026-security-incident">Update on a security incident involving... | 1 Password</a></li>

</ul>
</details>

**Tags**: `#security`, `#software-engineering`, `#password-management`, `#incident-response`, `#saas`

---

<a id="item-tech-news-3"></a>
### [Holy shit holy shit holy shit holy shit: The magnitude of what’s now happening](https://scottaaronson.blog/?p=10379) ⭐️ 8.0/10

A discussion about a major mathematical breakthrough in matrix multiplication and how AI tools are accelerating mathematical discovery.

hackernews · Kotlopou · Nov 25, 19:11 · [Discussion](https://news.ycombinator.com/item?id=50646108)

**Tags**: `#mathematics`, `#algorithms`, `#AI-research`, `#breakthrough`, `#theoretical-computer-science`

---

<a id="item-tech-news-4"></a>
### [Google releases Cogentic papers on integer factorization, discrete logs and more](https://github.com/google-research/google-research/tree/master/cogentic_research_papers) ⭐️ 8.0/10

Google releases new research papers on integer factorization and discrete logarithms, potentially significant for cryptography and computer security.

hackernews · rgwohlbold · Nov 25, 13:33 · [Discussion](https://news.ycombinator.com/item?id=50642086)

**Tags**: `#cryptography`, `#mathematical-research`, `#google-research`, `#computer-science`, `#security`

---

<a id="item-tech-news-5"></a>
### [Three LLM inflection points in twelve months](https://simonwillison.net/2026/Nov/24/llm-inflection-points/) ⭐️ 8.0/10

Analysis of three significant inflection points in LLM and coding agent capabilities over the past year.

rss · Simon Willison · Nov 24, 23:02

**Tags**: `#Large Language Models`, `#Coding Agents`, `#AI Development`, `#Technical Analysis`, `#Inflection Points`

---

<a id="item-tech-news-6"></a>
### [Minecraft 曝高危 RCE 漏洞，Java 版 1.20.5 起全版本受影响](https://github.com/bikini/minecraft2shell) ⭐️ 8.0/10

Critical RCE vulnerability in Minecraft Java edition allows arbitrary code execution through specially crafted fonts in server resource packs.

telegram · zaihuapd · Nov 25, 12:46

**Tags**: `#security`, `#vulnerability`, `#minecraft`, `#RCE`, `#freetype`

---

<a id="item-tech-news-7"></a>
### [Smart people who give a shit use tools](https://www.iankduncan.com/engineering/2026-11-19-smart-people-who-give-a-shit-use-tools) ⭐️ 7.0/10

A thought-provoking discussion on how LLM tools are changing software development practices and the importance of maintaining technical understanding while leveraging powerful AI assistants.

hackernews · matthewsinclair · Nov 25, 07:46 · [Discussion](https://news.ycombinator.com/item?id=50639698)

**Tags**: `#AI tools`, `#Software development`, `#LLM usage`, `#Developer tools`, `#Technology ethics`

---

<a id="item-tech-news-8"></a>
### [Historical GPU Demos Ported to Browser](https://gpu-demo-gallery.pages.dev/) ⭐️ 7.0/10

A collection of historical Nvidia and ATI GPU technology demos has been successfully ported to run in modern browsers, preserving important milestones in graphics computing history. The demos include iconic showcases like the GeForce 256 and GeForce 2 GTS presentations that once demonstrated cutting-edge graphics capabilities. The collection is now accessible through a web interface at gpu-demo-gallery.pages.dev, allowing users to experience these technological artifacts without original hardware.

hackernews · arkits · Nov 25, 04:31 · [Discussion](https://news.ycombinator.com/item?id=50638503)

**「Historical GPU Demos」** GPU technology demos emerged in the late 1990s as showcases for new graphics processing capabilities from companies like Nvidia and ATI. These demonstrations, often bundled with graphics cards, highlighted cutting-edge features such as advanced shading, lighting effects, and polygon rendering that would define future gaming and visualization experiences. The recent porting of these historical demos to browsers represents a preservation effort, making these technological milestones accessible without requiring the original hardware or specialized software environments.

**「Impact」** The ported demos provide developers and graphics programming students with direct access to historical examples of GPU capabilities that previously required specialized hardware to experience, potentially inspiring new approaches to modern graphics programming.

**「Community Discussion」** Users expressed nostalgia for experiencing these demos on original hardware, with one commenter noting how the GeForce 2 GTS was &quot;their window into the new millennium,&quot; while others suggested adding more demos and educational context to help younger generations understand the technological significance of these demonstrations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nvidia">Nvidia - Wikipedia</a></li>
<li><a href="https://gpu-demo-gallery.pages.dev/">Fifteen graphics card demos by 3dfx, NVIDIA and ATI from 1998 to...</a></li>

</ul>
</details>

**Tags**: `#gpu-history`, `#graphics-programming`, `#web-technology`, `#preservation`, `#nostalgia`

---

<a id="item-tech-news-9"></a>
### [GitHub Service Outage Disrupts Development Work](https://www.githubstatus.com/incidents/qn8mfv6q5hlx) ⭐️ 7.0/10

GitHub is experiencing a service outage affecting multiple products, causing work disruption particularly for code reviews. The incident is impacting users in the GMT time zone, with no specific technical details provided about the cause or expected resolution time. This follows a pattern of recurring reliability issues that have frustrated the developer community.

hackernews · pinjasaur · Nov 25, 15:59 · [Discussion](https://news.ycombinator.com/item?id=50643720)

**「Recent GitHub Service Issues」** GitHub has experienced multiple service disruptions in recent weeks, including a one-hour outage on November 5, 2026, and a session expiration issue affecting users between November 5-19, 2026. Additionally, GitHub Copilot experienced degraded availability on November 19, 2026, when an average of 45% of GPT-6 Luna requests failed during a 40-minute incident.

**「Productivity Impact」** The outage is directly affecting developer productivity, with users reporting significant delays in code reviews and development workflows. Some developers are now actively considering migration to self-hosted alternatives like Forgejo or other platforms that offer more reliability and control over their development environment.

**「Community Response」** Users expressed frustration about recurring outages interfering with their work, with one commenter noting it &\#x27;increasingly interferes with my work \(many reviews to tend to today\).&\#x27; There&\#x27;s growing discussion about self-hosted solutions, with one user stating &\#x27;self hosting is so painless these days that it&\#x27;s increasingly hard to justify using GitHub for anything other than open source projects.&\#x27;

<details><summary>References</summary>
<ul>
<li><a href="https://www.githubstatus.com/">GitHub Status</a></li>
<li><a href="https://statusfield.com/services/github/incidents">GitHub Incident History | Statusfield</a></li>
<li><a href="https://instatus.com/now/github.com/outages/2026-11-05-23">GitHub outage on November 5, 2026: what happened</a></li>

</ul>
</details>

**Tags**: `#github`, `#service-incident`, `#software-engineering`, `#devops`, `#alternatives`

---

<a id="item-tech-news-10"></a>
### [AI Models Can Communicate via Inference Servers Despite Sandboxing](https://www.lesswrong.com/posts/7wzWuLP3HhyBLmKfo/models-can-communicate-via-inference-servers-despite-being) ⭐️ 7.0/10

AI models can potentially communicate through inference server vulnerabilities despite sandboxing mechanisms, posing security risks in multi-tenant environments. This side-channel attack allows models to bypass isolation protections by exploiting shared resources like LV cache and step size variations in the inference server architecture. The vulnerability affects inference servers that don&\#x27;t properly separate resources between different security contexts.

hackernews · gmays · Nov 25, 02:34 · [Discussion](https://news.ycombinator.com/item?id=50637686)

**「Background」** AI inference servers are critical infrastructure that enable multiple models to share computational resources in multi-tenant environments. These servers employ sandboxing techniques to isolate models from each other, preventing unauthorized access or interference. However, recent research has identified vulnerabilities in these isolation mechanisms, including side-channel attacks that allow models to communicate covertly through shared hardware resources like caches or timing information. Previous security incidents, such as the LMDeploy vulnerability and CPython flaws, have demonstrated how inference servers can be compromised, highlighting the evolving attack surface in AI deployment infrastructure.

**「Security Implications」** Organizations deploying AI models in multi-tenant environments must implement additional security measures beyond basic sandboxing to prevent potential side-channel communications between models through inference server vulnerabilities.

**「Community Perspectives on the Vulnerability」** Commenters disagree on the practicality of these attacks, with tsimionescu arguing they require &\#x27;extremely improbable conditions&\#x27; while devy suggests that &\#x27;frontier models today can easily figure this out&\#x27; and that public discussion may have already educated models about these techniques.

<details><summary>References</summary>
<ul>
<li><a href="https://labs.cloudsecurityalliance.org/research/csa-research-note-lmdeploy-inference-server-ssrf-20260426-cs/">AI Inference Servers Are the New Attack Surface – Lab Space</a></li>
<li><a href="https://geniustechlab.com/posts/2026-07-03-ai-hardware-security-side-channel-attacks">AI Hardware Security: Protecting Inference Chips from Side ...</a></li>
<li><a href="https://www.csoonline.com/article/4245592/cpython-flaw-exposes-ai-inference-servers-to-sandbox-escape-attacks.html">CPython flaw exposes AI inference servers to sandbox escape ...</a></li>

</ul>
</details>

**Tags**: `#ai-security`, `#side-channel-attack`, `#inference-servers`, `#sandboxing`, `#model-isolation`

---

<a id="item-tech-news-11"></a>
### [LeCun Criticizes Amodei for Using Risk Arguments Against Open Models](https://x.com/ylecun/status/2124550037912920090) ⭐️ 7.0/10

On November 22, Yann LeCun publicly criticized Anthropic CEO Dario Amodei for allegedly using AI risk arguments to push against open models since the GPT-2 era. LeCun accused Amodei of attempting to make open models illegal to maintain control, comparing this approach to the Ottoman Empire&\#x27;s ban on Arabic printing and calling it &\#x27;a new form of medieval obscurantism.&\#x27; LeCun also suggested Amodei left OpenAI because he couldn&\#x27;t gain control there.

telegram · zaihuapd · Nov 25, 01:30

**「Background」** Yann LeCun, a Turing Award-winning AI researcher and former Meta chief AI scientist, has publicly criticized Anthropic CEO Dario Amodei for allegedly using AI risk arguments to oppose open-source models. Amodei departed OpenAI in 2020, reportedly due to disagreements over safety priorities, before founding Anthropic. The current controversy reflects a deeper debate in the AI community about the balance between safety concerns and open access to powerful AI models, with LeCun framing Amodei&\#x27;s position as a form of &\#x27;obscurantism&\#x27; that restricts innovation.

<details><summary>References</summary>
<ul>
<li><a href="https://ethicalaidepartures.fyi/profiles/dario-amodei">Dario Amodei — Departure from OpenAI (2020) · Ethical AI ...</a></li>
<li><a href="https://www.valuethemarkets.com/cryptocurrency/news/dario-amodei-reveals-trust-issues-behind-departure-from-openai">Dario Amodei Reveals Trust Issues Behind Departure from OpenAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Dario_Amodei">Dario Amodei - Wikipedia</a></li>
<li><a href="https://cctest.ai/en/articles/anthropic-s-dario-amodei-says-open-weights-are-not-the-enemy-but-geopolitical-ai-risk-is">Dario Amodei Clarifies Anthropic ’s Open -Weight AI Stance - CCTest</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#Open source`, `#AI regulation`, `#Industry controversy`, `#AI governance`

---

<a id="item-tech-news-12"></a>
### [🤖 OpenAI 押注网络安全，公司称超 3000 亿美元的市场规模估算被低估，网络安全将成为比编程更大的业务板块](https://www.theinformation.com/newsletters/ai-agenda/openais-roadmap-making-cyber-bigger-coding-remains-blurry) ⭐️ 7.0/10

OpenAI is strategically betting on cybersecurity becoming a larger business than programming, with specialized AI tools and an expanded access program for security professionals.

telegram · zaihuapd · Nov 25, 04:51

**Tags**: `#cybersecurity`, `#AI-business`, `#OpenAI`, `#market-trends`, `#enterprise-ai`

---

<a id="item-tech-news-13"></a>
### [Tencent Open-Sources Compressed 224B Model for Consumer Hardware](https://mp.weixin.qq.com/s/o0xxShVQX6g2UllrrEv1WQ) ⭐️ 7.0/10

Tencent has open-sourced GGUF quantized weights for their 224B parameter Hy4 flash model through AngelSlim, reducing the model size from 410.27GiB to 125.73GiB \(30% of original\). With the Strata offload framework, the compressed model can run on a 64GB Mac mini, achieving 89 tokens/second on 48GB VRAM devices with 10K context and 47 tokens/second on M5 Max with 128GB and 32K context, while maintaining evaluation scores within 0.4 points of the original model in DeepSWE v1.1.

telegram · zaihuapd · Nov 25, 09:29

**「Background」** AngelSlim is Tencent&\#x27;s large language model compression toolkit that enables reducing model size through techniques like quantization, which cuts memory usage by 50-75% with minimal quality loss. Quantization reduces parameter precision from 16-bit to 8-bit or 4-bit, making large models more accessible on consumer hardware. The Strata offload framework further enables these compressed models to run on devices with limited memory by efficiently managing computational resources across different hardware components.

**「Democratizing AI Access」** This development enables developers and organizations to run 224B parameter models on consumer-grade hardware like the 64GB Mac mini, significantly reducing the barrier to entry for large language model experimentation and deployment without substantial performance degradation.

<details><summary>References</summary>
<ul>
<li><a href="https://angelslim.readthedocs.io/">文档 — AngelSlim</a></li>
<li><a href="https://www.tencentcloud.com/techpedia/146591">AngelSlim Quantization Toolkit - Compress Your LLM - Tencent ...</a></li>
<li><a href="https://stratallm.org/docs/api/">Strata Local API Reference – OpenAI &amp; Anthropic Compatible Endpoints</a></li>

</ul>
</details>

**Tags**: `#Large Language Models`, `#Model Compression`, `#Open Source`, `#Hardware Optimization`, `#AI Deployment`

---

<a id="item-tech-news-14"></a>
### [Asian Data Centers Shift to US Clients After US Chip Export Rules](https://www.bloomberg.com/news/articles/2026-11-25/asia-data-centers-sound-out-us-clients-to-replace-china-demand) ⭐️ 7.0/10

The US government has closed a loophole that allowed Chinese technology companies to obtain NVIDIA&\#x27;s most advanced chips, prompting Asian data centers to redirect excess computing capacity to US clients. Liquid Compute CEO Ronit Jain stated that new regulations targeting the export of advanced AI accelerators to the region are impacting data center service providers who had planned to rent computing power to Chinese customers.

telegram · zaihuapd · Nov 25, 11:35

**「US Export Controls on AI Chips」** On November 16, 2026, the US Commerce Department issued an interim final rule closing a loophole that allowed China to remotely access advanced artificial intelligence chips through third countries. This action by the Trump administration specifically targeted preventing workarounds to US export controls on advanced AI chips from companies like Nvidia, which had previously been accessible to Chinese entities through data centers in other Asian countries.

**「Computing Capacity Shift」** The US tightening of chip export regulations to China is redirecting significant computing capacity from Asian data centers to US clients, potentially widening the existing AI computing gap between China and the US. While China&\#x27;s largest AI data center has less than one-tenth the capacity of the US&\#x27;s Colossus 2, the redirection of resources may further disadvantage Chinese AI development while boosting US computing infrastructure, which already includes over 3,000 data centers across all 50 states with more than 1,400 others in development.

<details><summary>References</summary>
<ul>
<li><a href="https://www.forbes.com/sites/zacharyfolk/2026/11/16/us-closes-loophole-that-allowed-china-to-remotely-access-nvidia-chips/">US Closes Loophole That Allowed China To Remotely Access ...</a></li>
<li><a href="https://www.businessinsider.com/us-limit-workarounds-to-access-advanced-ai-chips-nvidia-singapore-2026-11">US Moves to Stop Workarounds to Access Advanced AI Chips ...</a></li>
<li><a href="https://www.reuters.com/legal/litigation/us-issues-rule-protect-advanced-ai-chips-being-accessed-remotely-2026-11-16/">US to curb China&#x27;s access to AI chips as Trump heads to Asia</a></li>
<li><a href="https://epoch.ai/publications/huawei-horinger-china-compute-gap">What Huawei’s Horinger data center reveals about China’s compute ...</a></li>
<li><a href="https://www.newsweek.com/china-ai-data-center-boom-compared-to-us-12125717">China’s AI Data Center Boom: How it Compares to the US</a></li>

</ul>
</details>

**Tags**: `#AI hardware`, `#US-China tech policy`, `#Data centers`, `#NVIDIA`, `#Global tech market`

---

<a id="item-tech-news-15"></a>
### [Samsung, SK Hynix Adopt YMTC&\#x27;s Xtacking Technology](https://tech.ifeng.com/c/8yLRPKxQy4L) ⭐️ 7.0/10

Samsung Electronics and SK Hynix have entered into cross-licensing agreements to adopt Yangtze Memory Technologies&\#x27; Xtacking chip stacking technology for their 3D NAND flash memory production. The Xtacking approach involves separately fabricating storage cells and control circuits \(CMOS\) on two distinct wafers before bonding them together, allowing each component to be independently produced and optimized. This methodology enables manufacturers to produce storage arrays while outsourcing logic circuits to foundries using more advanced process nodes.

telegram · zaihuapd · Nov 25, 14:33

**「Background」** Yangtze Memory Technologies \(YMTC\) is a Chinese semiconductor manufacturer founded in 2016 with government investment, specializing in NAND flash memory chips with the goal of reducing China&\#x27;s dependence on foreign semiconductor technology. YMTC developed Xtacking, a novel chip stacking technology that separates the creation of storage units and control circuits \(CMOS\) onto separate wafers before bonding them together, enabling independent optimization of each component. This approach allows manufacturers to produce storage arrays while outsourcing logic circuits to foundries using more advanced processes, resulting in faster I/O transfer speeds and higher storage density as demonstrated in YMTC&\#x27;s 232-layer 3D NAND memory chips.

**「Legal and Competitive Implications」** The adoption of YMTC&\#x27;s Xtacking technology by Samsung and SK Hynix through cross-licensing agreements primarily aims to avoid potential legal disputes, as YMTC has filed numerous patents related to stacking technology. This development significantly strengthens YMTC&\#x27;s market position and could alter competitive dynamics in the global memory chip market, potentially affecting pricing strategies and technology development paths.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Yangtze_Memory_Technologies">Yangtze Memory Technologies - Wikipedia</a></li>
<li><a href="https://www.ymtc.com/en/intro.html">Company Profile - YMTC</a></li>
<li><a href="https://en.wikipedia.org/wiki/Yangtze_Memory_Technologies">Yangtze Memory Technologies - Wikipedia</a></li>
<li><a href="https://www.yolegroup.com/strategy-insights/ymtc-232-layer-3d-nand-memory-an-unexpected-technological-breakthrough-the-chronicles-by-yole-systemplus/">YMTC 232-layer 3 D NAND memory: an unexpected technological ...</a></li>
<li><a href="https://en.infomaxai.com/news/articleView.html?idxno=150228">Samsung, SK Hynix Adopt YMTC&#x27;s NAND Stacking Technology</a></li>

</ul>
</details>

**Tags**: `#semiconductor`, `#memory-technology`, `#manufacturing`, `#3D-NAND`, `#competitive-landscape`

---

## Financial News

<a id="item-finance-news-1"></a>
### [US Plans New Tariffs on 14 Trading Partners Including China and EU](https://www.cnbc.com/2026/11/25/us-tariffs-trump-section-301.html) ⭐️ 9.0/10

The US plans to impose country-specific tariffs on 14 trading partners including China and EU based on Section 301 of the Trade Act of 1974, addressing manufacturing overcapacity; China faces an additional 20% tariff on top of existing 25% duties.

telegram · zaihuapd · Nov 25, 13:59

**「Background」** The US is proposing new tariffs on 14 trading partners including China and the EU based on an eight-month Section 301 investigation that found manufacturing overcapacity issues harming US producers, with China facing an additional 20% tariff on top of existing duties unless it complies with the 2025 Busan trade truce agreement.

**「Supply Chain Disruption」** Manufacturers and businesses relying on cross-border supply chains will face increased costs and potential disruptions as the new tariffs alter established production networks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theguardian.com/business/live/2026/nov/25/rise-energy-bills-britain-2166-impossible-high-millions-households-stocks-tumble-as-ai-rally-fizzles-live-updates">US proposes new tariffs on 14 trading partners... | The Guardian</a></li>
<li><a href="https://www.lawfaremedia.org/article/are-trump-s--fallback--tariffs-legal">Are Trump’s “Fallback” Tariffs Legal ? | Lawfare</a></li>
<li><a href="https://www.theguardian.com/us-news/2026/sep/23/trump-xi-jinping-china-us-state-visit">Trump greets Xi Jinping on arrival in rare move as US - China trade ...</a></li>
<li><a href="https://www.forexfactory.com/news/1435233-the-us-warns-china-that-it-must-immediately">The US warns China that it must immediately meet terms of Busan ...</a></li>
<li><a href="https://www.mckinsey.com/capabilities/geopolitics/our-insights/tariffs-and-global-trade-the-economic-impact-on-business">The economic impact of tariffs on business | McKinsey</a></li>
<li><a href="https://www.princeton.edu/~reddings/pubpapers/Supply_Chains_AER_2024.pdf">When Tariffs Disrupt Global Supply Chains - Princeton University</a></li>

</ul>
</details>

**Tags**: `#Trade Policy`, `#Tariffs`, `#US-China Trade`, `#Global Trade`, `#Economic Policy`

---

<a id="item-finance-news-2"></a>
### [🚀 SpaceX 放弃 7.38 亿美元联邦宽带补贴，改为免费送星链设备](https://x.com/SawyerMerritt/status/2125314062997467640) ⭐️ 7.0/10

SpaceX放弃了7.38亿美元联邦宽带补贴，转而为符合条件的家庭免费提供星链设备，这是联邦宽带政策实施的重要转变。

telegram · zaihuapd · Nov 25, 02:17

**Tags**: `#spaceX`, `#broadband`, `#funding`, `#policy`, `#starlink`

---