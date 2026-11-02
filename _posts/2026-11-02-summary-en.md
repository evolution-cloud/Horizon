---
layout: default
title: "Horizon Summary: 2026-11-02 (EN)"
date: 2026-11-02
lang: en
---

> From 29 items, 5 important content pieces were selected

---

**Technology News**
1. [vLLM v0.33.0rc3: New Models, PyTorch 2.14, CUDA 13.0 Only](#item-tech-news-1) ⭐️ 8.0/10
2. [400+ AI Apps Hide Pornographic Deepfake Features](#item-tech-news-2) ⭐️ 8.0/10
3. [LongCat-2.5: 1.6 Trillion Parameter Native Multimodal Model](#item-tech-news-3) ⭐️ 7.0/10
4. [ChatGPT Share Link Vulnerability Allowed Account Takeover](#item-tech-news-4) ⭐️ 7.0/10

**Financial News**
1. [Anthropic Reports Explosive Revenue Growth but Massive Losses in IPO Filing](#item-finance-news-1) ⭐️ 7.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [vLLM v0.33.0rc3: New Models, PyTorch 2.14, CUDA 13.0 Only](https://github.com/vllm-project/vllm/releases/tag/v0.33.0rc3) ⭐️ 8.0/10

vLLM v0.33.0rc3 introduces significant updates including support for new large models like Reflection Beam-1.0 \(501B MoE\) and Yandex AliceAI-Foundation-80B-A3B, an upgrade to PyTorch 2.14.0 with torchvision 0.29.0 and Triton 3.8.0, and a major compatibility change to CUDA 13.0-only support. The release also features speculative decoding improvements, faster NVIDIA decode capabilities, AMD ROCm enhancements, and API serving updates, with 927 commits from 389 contributors.

github · khluu · Nov 2, 10:10

**「Background」** vLLM is a high-throughput and memory-efficient inference and serving engine for Large Language Models \(LLMs\) that utilizes PagedAttention for efficient memory management and supports continuous batching of incoming requests. The project enables fast and cost-efficient deployment of AI models with state-of-the-art performance through features like chunked prefill, prefix caching, and flexible model execution with CUDA/HIP graphs.

**「Impact」** Users upgrading to v0.33.0rc3 will need to adapt to the CUDA 13.0-only requirement, dropping support for CUDA 12.9, which may require infrastructure changes for existing deployments. The new AWS EFA image enables multi-node serving on EFA-enabled EC2 instances, providing improved scalability for large-scale deployments.

<details><summary>References</summary>
<ul>
<li><a href="https://vllm.ai/">vLLM</a></li>
<li><a href="https://github.com/vllm-project/vllm">GitHub - vllm - project / vllm : A high-throughput and memory-efficient...</a></li>
<li><a href="https://awesome.ecosyste.ms/projects/github.com/vllm-project/vllm">https://github.com/ vllm - project / vllm | Ecosyste.ms: Awesome</a></li>

</ul>
</details>

**Tags**: `#LLM serving`, `#PyTorch`, `#CUDA`, `#vLLM`, `#AI infrastructure`

---

<a id="item-tech-news-2"></a>
### [400+ AI Apps Hide Pornographic Deepfake Features](https://www.wired.com/story/hundreds-of-mundane-ai-apps-are-hiding-abusive-deepfake-features/) ⭐️ 8.0/10

WIRED investigation discovered a network of over 400 AI applications and websites that disguise pornographic deepfake capabilities behind legitimate tools like pet portrait generators and language learning apps. These apps, which had collectively been downloaded over 350,000 times from Google Play alone, would load explicit interfaces under specific conditions allowing users to upload photos of others to generate non-consensual explicit content. Apple removed 19 apps and Google removed most others after being notified, while Meta blocked 209 related apps from advertising.

telegram · zaihuapd · Nov 2, 12:45

**「Deepfake Technology Ethics」** Deepfake technology, which uses AI to create realistic but fake images and videos, has raised significant ethical concerns since its emergence. As noted in research from September 2025, the technology presents both potential benefits and substantial risks, particularly when used for non-consensual explicit content creation. Earlier ethical frameworks have emphasized the need for international regulations and detection technologies to minimize abuse while supporting legitimate innovation, making the discovery of this widespread network of deceptive apps particularly concerning.

**「Regulatory Response」** This discovery of widespread deepfake abuse apps contributes to growing regulatory pressure, as evidenced by India&\#x27;s new IT rules mandating 3-hour takedown for deepfake content and Indonesia&\#x27;s temporary blocking of an AI tool over pornographic content risks, forcing platforms to implement stricter content moderation and AI usage transparency measures.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sciencenewstoday.org/the-ethics-of-deepfake-technology">The Ethics of Deepfake Technology - sciencenewstoday.org</a></li>
<li><a href="https://link.springer.com/chapter/10.1007/978-3-032-01429-0_46">Deepfake Manipulation and Ethical Dilemmas: A Comprehensive ...</a></li>
<li><a href="https://link.springer.com/article/10.1007/s43681-024-00542-2">Decent deepfakes? Professional deepfake developers’ ethical ...</a></li>
<li><a href="https://beeble.com/en/blog/india-mandates-3-hour-deepfake-takedown-new-it-rules-demand-swift-platform-action-and-ai-content-labeling">India Mandates 3-Hour Deepfake Takedown: New IT Rules Demand...</a></li>
<li><a href="https://www.techpolicy.press/tracking-regulator-responses-to-the-grok-undressing-controversy/">Tracking Regulator Responses to the Grok... | TechPolicy.Press</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#deepfake technology`, `#app security`, `#privacy concerns`, `#tech regulation`

---

<a id="item-tech-news-3"></a>
### [LongCat-2.5: 1.6 Trillion Parameter Native Multimodal Model](https://longcat.ai/blog/longcat-2.5/) ⭐️ 7.0/10

LongCat-2.5 introduces a native multimodal model with 1.6 trillion total parameters and approximately 480 billion activated parameters per token. Building on LongCat-2.0, this model enhances visual understanding and agentic coding capabilities by encoding visual signals into multi-level discrete tokens that are processed uniformly with text. The model is currently available for trial use and API access, though GitHub and HuggingFace versions remain unavailable.

telegram · zaihuapd · Nov 2, 03:08

**「Background」** LongCat is a series of large language models developed by the LongCat team, with LongCat-2.0 being the previous version that established the foundation for this native multimodal approach. Multimodal AI models process and integrate information from multiple types of data, such as text and images, enabling more comprehensive understanding and interaction capabilities. The &\#x27;agentic coding&\#x27; capabilities refer to the model&\#x27;s enhanced ability to understand and generate code, particularly in contexts that involve visual programming or task automation.

**「Impact」** The model&\#x27;s enhanced visual understanding and agentic coding capabilities could significantly advance AI applications in visual programming and complex task automation, potentially enabling more sophisticated AI agents that can interpret and manipulate visual information alongside text-based reasoning.

**Tags**: `#Large Language Models`, `#Multimodal AI`, `#Computer Vision`, `#AI Agents`, `#Software Engineering`

---

<a id="item-tech-news-4"></a>
### [ChatGPT Share Link Vulnerability Allowed Account Takeover](https://www.parameter.ai/labs/we-found-a-gap-at-openai) ⭐️ 7.0/10

Parameter researchers discovered a security vulnerability in ChatGPT that allowed attackers to take over user accounts through malicious sharing links. The vulnerability exploited a message processing defect between the preview function and chart components, enabling attackers to execute code, read private conversations, and send data to external servers when users clicked the links. OpenAI patched the vulnerability on October 26, classified it as P1 severity, and paid the research team a $5,000 bounty.

telegram · zaihuapd · Nov 2, 10:24

**「Background」** ChatGPT sharing links allow users to share conversations with others by generating a unique URL that provides read-only access to the conversation. Account takeover vulnerabilities occur when attackers can gain unauthorized control of a user&\#x27;s account, often through exploiting security flaws in how applications handle user sessions or process inputs. The vulnerability in question exploited a defect in how the preview function and chart components processed messages, allowing malicious code execution when a user clicked on a specially crafted link.

**「User Impact」** Users who clicked malicious ChatGPT sharing links before the patch could have had their private conversations accessed and their accounts compromised, though OpenAI has since fixed the issue.

**Tags**: `#security`, `#ai`, `#vulnerability`, `#chatgpt`, `#account-takeover`

---

## Financial News

<a id="item-finance-news-1"></a>
### [Anthropic Reports Explosive Revenue Growth but Massive Losses in IPO Filing](https://www.cnbc.com/2026/11/02/anthropic-ant-s-1-quarter-financials.html) ⭐️ 7.0/10

Anthropic filed its IPO prospectus showing $33.2 billion revenue in the first three quarters of 2026, a 1200% increase from the previous year, while reporting a net loss of $104 billion due to investments in AI infrastructure.

telegram · zaihuapd · Nov 2, 15:12

**「Background」** Anthropic, an AI company known for its Constitutional AI framework and Claude model, is investing heavily in AI infrastructure to support its rapid growth.

**「Market Impact」** The IPO filing will significantly impact investors evaluating Anthropic&\#x27;s valuation amid extraordinary growth and substantial infrastructure investments in the competitive AI sector.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/most-important-ai-company-youre-fully-paying-attention-sahil-ansari-vgese">The most important AI company you&#x27;re not fully paying attention to just...</a></li>
<li><a href="https://www.youtube.com/watch?v=ugvHCXCOmm4">Dario Amodei: Anthropic CEO on Claude, AGI &amp; the Future of AI ...</a></li>

</ul>
</details>

**Tags**: `#IPO`, `#AI`, `#Revenue Growth`, `#Financial Losses`, `#Tech Investment`

---