---
layout: default
title: "Horizon Summary: 2026-11-02 (ZH)"
date: 2026-11-02
lang: zh
---

> 从 29 条内容中筛选出 5 条重要资讯。

---

**科技新闻**
1. [vLLM 发布 v0.33.0rc3 版本，引入多项重大更新](#item-tech-news-1) ⭐️ 8.0/10
2. [WIRED 调查发现 400 多个 AI 应用暗藏色情深伪功能](#item-tech-news-2) ⭐️ 8.0/10
3. [LongCat-2.5 发布：1.6 万亿参数原生多模态模型](#item-tech-news-3) ⭐️ 7.0/10
4. [ChatGPT 分享链接漏洞已修复](#item-tech-news-4) ⭐️ 7.0/10

**财经新闻**
1. [Anthropic IPO 披露：前三季度营收 332 亿美元 净亏损 1040 亿美元](#item-finance-news-1) ⭐️ 7.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [vLLM 发布 v0.33.0rc3 版本，引入多项重大更新](https://github.com/vllm-project/vllm/releases/tag/v0.33.0rc3) ⭐️ 8.0/10

vLLM v0.33.0rc3 版本引入了重大更新，包括支持 501B MoE 规模的 Reflection Beam-1.0 等新模型，升级至 PyTorch 2.14.0，并转向仅支持 CUDA 13.0。此次更新包含 389 贡献者的 927 次提交，新增了 AWS EFA 支持、改进的推测解码功能、NVIDIA 和 AMD ROCm 性能优化，以及多项 API 和服务的增强。同时，该版本移除了对 CUDA 12.9 的支持，并包含一些破坏性更改。

github · khluu · 11月2日 10:10

**「背景」** vLLM 是一个高吞吐量和内存高效的推理和服务引擎，专为大型语言模型\(LLMs\)设计。它采用 PagedAttention 技术高效管理注意力键和值内存，支持连续批处理、分块预取和前缀缓存等特性，以实现快速灵活的模型执行。这些核心功能使 vLLM 成为部署 AI 模型的高性能解决方案。

**「影响分析」** 用户需要更新到 CUDA 13.0 才能使用此版本，现有的 CUDA 12.9 部署将无法获取新版本。同时，移除了 Medusa 和 MLP 推测器等组件，可能影响依赖这些功能的现有工作流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://vllm.ai/">vLLM</a></li>
<li><a href="https://github.com/vllm-project/vllm">GitHub - vllm - project / vllm : A high-throughput and memory-efficient...</a></li>
<li><a href="https://awesome.ecosyste.ms/projects/github.com/vllm-project/vllm">https://github.com/ vllm - project / vllm | Ecosyste.ms: Awesome</a></li>

</ul>
</details>

**标签**: `#LLM serving`, `#PyTorch`, `#CUDA`, `#vLLM`, `#AI infrastructure`

---

<a id="item-tech-news-2"></a>
### [WIRED 调查发现 400 多个 AI 应用暗藏色情深伪功能](https://www.wired.com/story/hundreds-of-mundane-ai-apps-are-hiding-abusive-deepfake-features/) ⭐️ 8.0/10

WIRED 调查显示，一个由 400 多个关联应用与网站组成的网络以普通 AI 工具为掩护，在特定条件下加载色情深度伪造功能。这些应用包括宠物画像、语言学习等看似合法的工具，允许用户上传他人照片生成露骨图像或视频；其中 27 款应用在 Google Play 上累计下载超过 35 万次，且多数被标为适合所有年龄。苹果已下架 19 款应用，谷歌已移除多数相关应用，Meta 则阻止了 209 款相关应用投放广告。研究人员通过代码分析、域名追踪和广告关联发现这些应用与中文开发者和香港注册公司有关联。

telegram · zaihuapd · 11月2日 12:45

**「深度伪造技术背景」** 深度伪造\(Deepfake\)技术是一种人工智能驱动的图像和视频处理方法，能够将一个人的面部特征替换到另一个人的视频中，或生成看似真实的虚假内容。随着 AI 技术的快速发展，深度伪造技术引发了严重的伦理和法律问题，包括非自愿色情内容制作、身份盗用和虚假信息传播等风险。2024 年至 2025 年间，学术界和行业专家已多次呼吁制定国际法规和技术检测手段，以减轻深度伪造技术的滥用风险。

**「监管响应」** 这一事件可能加速全球对 AI 生成色情内容的监管响应，如印度已实施的 3 小时深度伪造内容删除要求和 AI 内容声明规定，以及印度尼西亚因担心 AI 生成色情内容风险而阻止 AI 工具的做法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sciencenewstoday.org/the-ethics-of-deepfake-technology">The Ethics of Deepfake Technology - sciencenewstoday.org</a></li>
<li><a href="https://link.springer.com/chapter/10.1007/978-3-032-01429-0_46">Deepfake Manipulation and Ethical Dilemmas: A Comprehensive ...</a></li>
<li><a href="https://link.springer.com/article/10.1007/s43681-024-00542-2">Decent deepfakes? Professional deepfake developers’ ethical ...</a></li>
<li><a href="https://beeble.com/en/blog/india-mandates-3-hour-deepfake-takedown-new-it-rules-demand-swift-platform-action-and-ai-content-labeling">India Mandates 3-Hour Deepfake Takedown: New IT Rules Demand...</a></li>
<li><a href="https://www.techpolicy.press/tracking-regulator-responses-to-the-grok-undressing-controversy/">Tracking Regulator Responses to the Grok... | TechPolicy.Press</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#deepfake technology`, `#app security`, `#privacy concerns`, `#tech regulation`

---

<a id="item-tech-news-3"></a>
### [LongCat-2.5 发布：1.6 万亿参数原生多模态模型](https://longcat.ai/blog/longcat-2.5/) ⭐️ 7.0/10

LongCat 团队发布了 LongCat-2.5，这是一个面向长程 agent 任务的原生多模态模型，总参数量达 1.6 万亿，每 token 激活约 480 亿参数。该模型在 LongCat-2.0 基础上强化了视觉理解与 agentic coding 能力，将视觉信号编码为多级离散 token 与文本统一处理，可完成视觉编程等任务。目前模型已在官网开放试用并提供 API 接入，但 GitHub 与 HuggingFace 版本尚未开放。

telegram · zaihuapd · 11月2日 03:08

**「背景信息」** 多模态 AI 模型能够同时处理和理解多种类型的数据，如图像、文本和音频。LongCat 是一个专注于长程 agent 任务的原生多模态模型系列，其前代版本 LongCat-2.0 已经展示了基本的视觉理解和编程能力。参数规模是衡量大型语言模型能力的重要指标，1.6 万亿参数代表了当前 AI 模型技术的前沿水平。

**「影响分析」** 该模型通过统一处理视觉和文本信号，为开发者提供了更强大的视觉编程能力，可能加速多模态 AI 在软件开发领域的应用，但需注意其开源版本尚未发布，限制了研究者和开发者的深入使用与二次开发。

**标签**: `#Large Language Models`, `#Multimodal AI`, `#Computer Vision`, `#AI Agents`, `#Software Engineering`

---

<a id="item-tech-news-4"></a>
### [ChatGPT 分享链接漏洞已修复](https://www.parameter.ai/labs/we-found-a-gap-at-openai) ⭐️ 7.0/10

Parameter 研究团队发现 ChatGPT 存在一个安全漏洞，攻击者可通过恶意分享链接在已登录用户的会话中执行代码，读取私密对话并将数据发送至外部服务器。该漏洞利用了预览功能与图表组件之间的消息处理缺陷，OpenAI 已于 10 月 26 日修复此漏洞，并将其定级为 P1，同时向研究团队支付了 5000 美元赏金。

telegram · zaihuapd · 11月2日 10:24

**「背景信息」** ChatGPT 是由 OpenAI 开发的大型语言模型聊天机器人，拥有数亿用户，广泛应用于各种场景。账户接管漏洞是指攻击者能够获取用户账户控制权的安全缺陷，这类漏洞在在线服务中尤为危险，因为可能导致用户数据泄露和隐私侵犯。分享链接功能是现代 AI 平台常见的协作特性，允许用户轻松分享对话内容，但也可能成为安全风险点。

**「影响范围」** 该漏洞可能导致 ChatGPT 用户的私密对话内容被未授权访问，造成数据泄露风险，但用户只需打开链接即可触发漏洞，无需额外操作或安装应用。

**标签**: `#security`, `#ai`, `#vulnerability`, `#chatgpt`, `#account-takeover`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [Anthropic IPO 披露：前三季度营收 332 亿美元 净亏损 1040 亿美元](https://www.cnbc.com/2026/11/02/anthropic-ant-s-1-quarter-financials.html) ⭐️ 7.0/10

Anthropic 在 IPO 招股书中披露，2026 年前三季度营收达 332.4 亿美元，同比增长约 1200%，但同期净亏损达 1040 亿美元，主要受可转换债券及衍生负债公允价值变动影响。

telegram · zaihuapd · 11月2日 15:12

**「背景」** Anthropic 是一家专注于 AI 研发的公司，开发了 Claude 模型并采用 Constitutional AI 技术，目前正准备进行首次公开募股\(IPO\)。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/most-important-ai-company-youre-fully-paying-attention-sahil-ansari-vgese">The most important AI company you&#x27;re not fully paying attention to just...</a></li>
<li><a href="https://www.youtube.com/watch?v=ugvHCXCOmm4">Dario Amodei: Anthropic CEO on Claude, AGI &amp; the Future of AI ...</a></li>

</ul>
</details>

**标签**: `#IPO`, `#AI`, `#Revenue Growth`, `#Financial Losses`, `#Tech Investment`

---