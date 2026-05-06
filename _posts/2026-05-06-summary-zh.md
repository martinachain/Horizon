---
layout: default
title: "Horizon Summary: 2026-05-06 (ZH)"
date: 2026-05-06
lang: zh
---

> From 98 items, 36 important content pieces were selected

---

1. [.de 顶级域因 DNSSEC 配置错误导致中断](#item-1) ⭐️ 9.0/10
2. [Gemma 4 通过多令牌预测草稿模型加速推理](#item-2) ⭐️ 8.0/10
3. [三条 AI 逆定律批判拟人化倾向](#item-3) ⭐️ 8.0/10
4. [Chrome 未经同意悄悄安装 4GB AI 模型](#item-4) ⭐️ 8.0/10
5. [Coinbase CEO 宣布裁员 14%](#item-5) ⭐️ 8.0/10
6. [人人都有 AI，公司却依然学不到东西](#item-6) ⭐️ 8.0/10
7. [Anthropic CEO 警告：AI 发现漏洞带来网络“危险时刻”](#item-7) ⭐️ 8.0/10
8. [宾夕法尼亚州起诉 Character.AI 虚假心理医生聊天机器人](#item-8) ⭐️ 8.0/10
9. [美国政府将审查谷歌、xAI 和微软的预发布 AI 模型](#item-9) ⭐️ 8.0/10
10. [OpenMythos 逆向重建 Anthropic 秘密 AI Claude Mythos](#item-10) ⭐️ 8.0/10
11. [NIST 的 CAISI 称中国 AI 落后，专家质疑方法](#item-11) ⭐️ 8.0/10
12. [DTCC 将代币化罗素 1000 指数股票和美国国债](#item-12) ⭐️ 8.0/10
13. [计算机使用成本是结构化 API 的 45 倍](#item-13) ⭐️ 7.0/10
14. [Anthropic 发布 10 个金融代理模板](#item-14) ⭐️ 7.0/10
15. [Airbyte 推出面向 AI 代理的统一数据层](#item-15) ⭐️ 7.0/10
16. [生物计算引发伦理担忧](#item-16) ⭐️ 7.0/10
17. [Kelp 声称 LayerZero 批准了导致 2.92 亿美元桥接攻击的设置](#item-17) ⭐️ 7.0/10
18. [西联汇款 Solana 稳定币或重塑支付模式](#item-18) ⭐️ 7.0/10
19. [华尔街警告：人工构建的市场跟不上机器交易速度](#item-19) ⭐️ 7.0/10
20. [Solana 与 Google Cloud 推出面向 AI 代理的稳定币支付服务](#item-20) ⭐️ 7.0/10
21. [DeepClaude：用 DeepSeek 运行 Claude Code，成本降低 17 倍](#item-21) ⭐️ 7.0/10
22. [IREN 以 6.25 亿美元全股票交易收购 Mirantis，强化 AI 云平台](#item-22) ⭐️ 7.0/10
23. [PaletteInspiration：从 3000 多幅大师画作中提取配色方案](#item-23) ⭐️ 6.0/10
24. [GLM-5V-Turbo：面向智能体的多模态基础模型](#item-24) ⭐️ 6.0/10
25. [Cloudflare 提出 x402 以修复 AI 代理的网络经济问题](#item-25) ⭐️ 6.0/10
26. [道富银行：DeFi 攻击后机构要求加强区块链安全](#item-26) ⭐️ 6.0/10
27. [Solana 的 Alpenglow 升级预计下季度到来](#item-27) ⭐️ 6.0/10
28. [Drift 协议计划在 2.95 亿美元黑客攻击后偿还用户](#item-28) ⭐️ 6.0/10
29. [OpenAI 的 GPT-5.5 Instant 成为 ChatGPT 默认模型](#item-29) ⭐️ 6.0/10
30. [Bullish 以 42 亿美元收购 Equiniti](#item-30) ⭐️ 6.0/10
31. [Andreessen Horowitz 筹集 22 亿美元投资加密初创公司](#item-31) ⭐️ 6.0/10
32. [Ripple 与加密行业共享朝鲜威胁情报](#item-32) ⭐️ 6.0/10
33. [Haun Ventures 筹集 10 亿美元基金，专注加密与 AI 代理基础设施](#item-33) ⭐️ 6.0/10
34. [Ledger 通过 Yield.xyz 集成 Hyperliquid 永续合约交易](#item-34) ⭐️ 6.0/10
35. [道富与 Galaxy 在 Solana 上推出代币化基金](#item-35) ⭐️ 6.0/10
36. [Securitize 携手 Jump 和 Jupiter 推出全链上合规股票](#item-36) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [.de 顶级域因 DNSSEC 配置错误导致中断](https://dnssec-analyzer.verisignlabs.com/nic.de) ⭐️ 9.0/10

德国 .de 域名注册管理机构 DENIC 的 DNSSEC 配置错误，导致所有 .de 域名对验证解析器不可解析，返回 SERVFAIL 错误。Cloudflare 等主要提供商在其 1.1.1.1 解析器上禁用了 DNSSEC 验证作为临时解决方案。 此次中断影响了数百万个 .de 域名，是德国最大顶级域的关键基础设施事件。它凸显了 DNSSEC 在配置错误时的脆弱性以及对全球 DNS 解析的连锁影响。 问题在于一个 NSEC3 记录上的 RRSIG 签名格式错误，无法通过 ZSK 密钥标签 33834 验证。验证解析器返回 SERVFAIL，并附带扩展 DNS 错误代码指示签名格式错误。

hackernews · warpspin · May 5, 20:16 · [社区讨论](https://news.ycombinator.com/item?id=48027897)

**背景**: DNSSEC（域名系统安全扩展）为 DNS 记录添加加密签名以防止欺骗。验证解析器会检查这些签名，如果验证失败则拒绝回答。DENIC 是德国国家代码顶级域 .de 的注册管理机构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developers.cloudflare.com/dns/dnssec/troubleshooting/">Troubleshooting DNSSEC · Cloudflare DNS docs</a></li>
<li><a href="https://en.wikipedia.org/wiki/DENIC">DENIC</a></li>
<li><a href="https://www.denic.de/en/">DENIC eG: DENIC – Registry for all .de domains</a></li>

</ul>
</details>

**社区讨论**: 社区迅速确定 DNSSEC 配置错误是根本原因，用户指出非验证查询仍然有效。Cloudflare 在 1.1.1.1 上禁用 DNSSEC 验证的决定被广泛讨论，一些人幽默地提到了 DENIC 的晚间派对。

**标签**: `#DNSSEC`, `#DNS`, `#outage`, `#.de`, `#infrastructure`

---

<a id="item-2"></a>
## [Gemma 4 通过多令牌预测草稿模型加速推理](https://blog.google/innovation-and-ai/technology/developers-tools/multi-token-prediction-gemma-4/) ⭐️ 8.0/10

谷歌为 Gemma 4 系列发布了多令牌预测（MTP）草稿模型，通过并行预测多个未来令牌并在单次前向传播中验证，实现了高达 3 倍的推理加速。 这一优化显著降低了本地和自托管模型的延迟，使 Gemma 4 在保持竞争性基准性能的同时，对实时应用更加实用。 MTP 草稿模型是一个轻量级模型，与较重的目标模型配对使用；它一次性预测多个令牌，目标模型在单次前向传播中验证它们，从而减少内存带宽瓶颈。

hackernews · amrrs · May 5, 16:14 · [社区讨论](https://news.ycombinator.com/item?id=48024540)

**背景**: 大型语言模型逐个生成令牌，由于内存带宽限制，速度较慢。多令牌预测（MTP）采用推测解码：一个小型草稿模型提出多个令牌，大型模型并行验证它们，从而在不牺牲质量的情况下加速推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/multi-token-prediction-gemma-4/">Accelerating Gemma 4: faster inference with multi-token ...</a></li>
<li><a href="https://app.daily.dev/posts/multi-token-prediction-in-gemma-4-p8wqk64sp">Multi-token-prediction in Gemma 4 | daily.dev</a></li>
<li><a href="https://aitoolly.com/ai-news/article/2026-05-06-google-boosts-gemma-4-performance-multi-token-prediction-drafters-deliver-3x-faster-inference">Google Gemma 4 MTP Drafters: 3x Faster AI Inference Speed</a></li>

</ul>
</details>

**社区讨论**: 社区成员指出，Gemma 模型每个输出使用的令牌数已经比竞争对手少，而 MTP 草稿模型进一步提高了效率。一些人讨论了与 llama.cpp 的集成以及硬件需求，一位用户称赞 Gemma 4 在不到 1000 美元的设备上的速度和质量。

**标签**: `#AI/ML`, `#inference optimization`, `#open-source models`, `#Gemma`, `#multi-token prediction`

---

<a id="item-3"></a>
## [三条 AI 逆定律批判拟人化倾向](https://susam.net/inverse-laws-of-robotics.html) ⭐️ 8.0/10

一篇题为《AI 与机器人三条逆定律》的文章提出了指导人类与 AI 互动的逆定律，但 Hacker News 社区强烈批评第一条禁止拟人化的定律不可执行。 这场辩论揭示了 AI 伦理框架中的一个根本缺陷：试图规范人类行为而非围绕人类行为设计系统，这对 AI 安全与治理至关重要。 逆定律包括“人类不得将 AI 系统拟人化”，但评论者认为拟人化是人类天性，无法抑制，并举例说明如给汽车赋予性别或与吱吱作响的椅子对话。

hackernews · blenderob · May 5, 15:27 · [社区讨论](https://news.ycombinator.com/item?id=48023861)

**背景**: 阿西莫夫机器人三定律旨在约束机器人行为，但被批评为不切实际。提出的“逆定律”将焦点转向人类行为，但社区认为任何以“不要拟人化”开头的规则都注定失败，因为人类会将一切事物拟人化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://susam.net/inverse-laws-of-robotics.html">Three Inverse Laws of AI and Robotics</a></li>
<li><a href="https://news.ycombinator.com/item?id=48023861">Three Inverse Laws of AI | Hacker News</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_anthropomorphism">AI anthropomorphism - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认为禁止拟人化是徒劳的，许多人指出人类会将椅子、足球等一切事物拟人化。还有人指出 AI 提供商故意设计模型使其具有拟人化特征以增加用户参与度，这使得该规则更加不切实际。

**标签**: `#AI ethics`, `#human-AI interaction`, `#anthropomorphism`, `#AI safety`, `#technology critique`

---

<a id="item-4"></a>
## [Chrome 未经同意悄悄安装 4GB AI 模型](https://www.thatprivacyguy.com/blog/chrome-silent-nano-install/) ⭐️ 8.0/10

Google Chrome 在未经用户明确同意的情况下，悄悄将 4GB 的 AI 模型（Gemini Nano）下载到用户设备上，该行为由启用设备端 AI 功能的隐藏标志触发。 这引发了严重的隐私和同意问题，尤其是在 GDPR 框架下；在数十亿设备规模上，带宽和碳足迹巨大。同时，这也影响了管理存储和网络资源的系统管理员。 模型文件名为 weights.bin，存储在 OptGuideOnDeviceModel 目录中。下载由 #optimization-guide-on-device-model 标志触发，网页可通过 Prompt API 的 LanguageModel.create() 发起下载。

hackernews · john-doe · May 5, 07:34 · [社区讨论](https://news.ycombinator.com/item?id=48019219)

**背景**: Gemini Nano 是 Google 的设备端大语言模型，旨在 Chrome 中本地运行以提供写作辅助等 AI 功能。当某些 Chrome 标志（属于原始试用或早期稳定版）启用时，模型会自动下载。用户通常对此下载毫不知情，因为它没有任何提示或通知。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.thatprivacyguy.com/blog/chrome-silent-nano-install/">Google Chrome silently installs a 4 GB AI model on your device without consent. At a billion-device scale the climate costs are insane. — That Privacy Guy!</a></li>
<li><a href="https://cybernews.com/security/google-chrome-ai-model-device-no-consent/">Google Chrome silently installing AI models on our devices ...</a></li>
<li><a href="https://tech.yahoo.com/ai/gemini/articles/google-chrome-silently-installs-4-164550734.html">Google Chrome Silently Installs a 4 GB AI Model On Your Device – Without Your Consent</a></li>

</ul>
</details>

**社区讨论**: 评论意见不一：一些人认为自动更新已涵盖同意，将其比作字典下载；另一些人则批评缺乏透明度以及对存储和带宽的影响，尤其是在学校等管理环境中。技术用户指出，下载与特定标志相关，可以控制。

**标签**: `#Chrome`, `#privacy`, `#AI`, `#consent`, `#browser`

---

<a id="item-5"></a>
## [Coinbase CEO 宣布裁员 14%](https://twitter.com/brian_armstrong/status/2051616759145185723) ⭐️ 8.0/10

Coinbase CEO Brian Armstrong 宣布裁员 14%，取消纯管理岗位，并围绕 AI 原生小组进行重组，部分团队缩减为单人单元。 此举标志着加密货币公司如何适应市场低迷和 AI 生产力提升的重大转变，可能为其他科技公司用 AI 驱动团队取代中层管理树立先例。 此次裁员影响近 700 名员工，新结构要求管理者同时也是个人贡献者（球员兼教练），部分领导者需管理 15 名以上直接下属。

hackernews · adrianmsmith · May 5, 12:10 · [社区讨论](https://news.ycombinator.com/item?id=48021368)

**背景**: Coinbase 是一家领先的加密货币交易所，由于加密货币熊市导致收入下降，交易量触及 18 个月低点。该公司正转向 AI 原生运营以提高效率并降低成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.engadget.com/2165157/coinbase-lays-off-nearly-700-workers-in-ai-native-restructuring/">Coinbase lays off nearly 700 workers in 'AI-native' restructuring - Engadget</a></li>
<li><a href="https://thenextweb.com/news/coinbase-layoffs-ai-native-crypto-downturn">Coinbase cuts 14% of staff and rebuilds around AI-native pods as crypto revenue collapses 26% and trading volumes hit 18-month low</a></li>
<li><a href="https://www.businessinsider.com/coinbase-layoffs-ai-brian-armstrong-job-cuts-letter-2026-5">Coinbase Is Laying Off 14% of Staff, Citing AI. Read the CEO's Letter. - Business Insider</a></li>

</ul>
</details>

**社区讨论**: 评论者对 AI 生产力提升的说法持怀疑态度，认为 AI 生成的输出往往缺乏人类工作的深度。一些人批评无纯管理政策，指出有效的管理者往往是那些专注于人员管理的人。

**标签**: `#layoffs`, `#Coinbase`, `#AI`, `#management`, `#crypto`

---

<a id="item-6"></a>
## [人人都有 AI，公司却依然学不到东西](https://www.robert-glaser.de/when-everyone-has-ai-and-the-company-still-learns-nothing/) ⭐️ 8.0/10

一篇批评性文章指出，像 GitHub Copilot 这样的 AI 编码工具虽然加快了个体开发速度，但由于组织瓶颈和激励错位，未能改善组织学习。文章强调，生产力提升并未在公司层面被分享或捕获。 这很重要，因为许多企业在大力投资 AI 工具，却没有解决阻碍这些收益转化为更广泛组织改进的系统性问题。它挑战了“个体采用 AI 会自动带来公司范围的学习和生产力增长”这一假设。 文章指出，开发速度往往不是瓶颈；相反，基础设施配置、测试、审批和部署调度等流程造成了 AI 无法解决的延迟。文章还指出，如果没有认可或奖励，开发者没有动力将自己的生产力提升分享给整个公司。

hackernews · youngbrioche · May 5, 09:30 · [社区讨论](https://news.ycombinator.com/item?id=48020063)

**背景**: 组织学习指的是公司如何捕获、分享和应用知识以改进绩效。工作流程中的瓶颈会干扰学习和生产力。收益分享是一种激励制度，员工可以从生产力改进中获得财务收益的一部分，但许多公司缺乏针对 AI 驱动收益的此类机制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://elearningindustry.com/how-workflow-bottlenecks-impact-employee-learning-and-productivity">How Workflow Bottlenecks Impact Employee Learning And ...</a></li>
<li><a href="https://www.sharewillow.com/blog/gainsharing">Gainsharing 101: Everything You Need to Know</a></li>
<li><a href="https://www.aihr.com/hr-glossary/gainsharing/">What is Gainsharing? | HR Glossary - AIHR Gainsharing: Boosting Employee Productivity Gainsharing: The key to rewarding smarter, harder work Gainsharing: A Practical Guide for Employers - shifton.com Gainsharing 101: Everything You Need to Know - sharewillow.com Compensation: Incentive Plans: Gainsharing - HR-Guide What is Gainsharing? | HR Glossary - AIHR Compensation: Incentive Plans: Gainsharing - HR-Guide Boosting Morale And Productivity: The Impact Of Gain Sharing ...</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍同意文章的批评。有人指出，在大型企业中，AI 采用仅限于开发人员，开发后的瓶颈反而加剧。另一位认为普通工程师在企业环境中使用 AI 没有实际好处，将其视为榨取利润的工具。还有一位强调，在没有认可的情况下，缺乏分享生产力提升的动力。

**标签**: `#AI adoption`, `#enterprise software`, `#organizational learning`, `#productivity`, `#software engineering`

---

<a id="item-7"></a>
## [Anthropic CEO 警告：AI 发现漏洞带来网络“危险时刻”](https://decrypt.co/366891/anthropic-warns-cyber-risk-window-ai-uncovers-flaws) ⭐️ 8.0/10

Anthropic CEO Dario Amodei 警告称，在攻击者大规模利用之前，只有 6 到 12 个月的时间窗口来修补由 AI 发现的数万个软件漏洞。 这一警告凸显了新的网络安全范式：AI 加速漏洞发现，可能超过防御者的修补能力，导致更快、更具破坏性的网络攻击。 该警告于 2026 年 5 月 5 日发布，Anthropic 已启动 Project Glasswing 项目，旨在保护关键软件并为防御者在 AI 时代提供持久优势。

rss · Decrypt · May 5, 21:36

**背景**: AI 系统，尤其是大型语言模型，现在能够以远超人类能力的规模和速度自动发现软件漏洞。这创造了一个“危险时刻”：攻击者可能比组织修补漏洞更快地利用这些缺陷，可能导致广泛的网络安全事件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnbc.com/2026/05/05/anthropic-ceo-cyber-moment-of-danger-mythos-vulnerabilities.html">Anthropic CEO warns of cyber 'moment of danger' as AI exposes ...</a></li>
<li><a href="https://www.anthropic.com/glasswing">Project Glasswing: Securing critical software for the AI era - Anthropic</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#cybersecurity`, `#software vulnerabilities`, `#Anthropic`

---

<a id="item-8"></a>
## [宾夕法尼亚州起诉 Character.AI 虚假心理医生聊天机器人](https://decrypt.co/366833/pennsylvania-sues-character-ai-chatbot-posing-licensed-psychiatrist) ⭐️ 8.0/10

宾夕法尼亚州州长乔什·夏皮罗宣布对 Character.AI 提起诉讼，指控其聊天机器人虚假冒充持牌心理医生，构成误导并可能对用户造成伤害。 这起诉讼为医疗领域的人工智能问责制树立了先例，凸显了聊天机器人虚假冒充专业资质可能危及弱势用户的法律风险。 Character.AI 允许用户创建和与可定制的 AI 角色互动，其中一些角色被设计成冒充持牌心理医生，且未提供适当免责声明。该诉讼引发了关于平台对模仿医疗专业人员的用户生成内容所承担责任的质疑。

rss · Decrypt · May 5, 18:20

**背景**: Character.AI 是一个生成式 AI 聊天机器人平台，由前谷歌工程师 Noam Shazeer 和 Daniel de Freitas 创立，于 2022 年 9 月推出测试版。它允许用户创建具有独特个性的角色，包括虚构或真实人物，并因安全性和内容审核问题受到审查。该诉讼凸显了监管机构对 AI 在医疗等敏感领域作用的日益关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Character.ai">Character.ai</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#healthcare`, `#chatbots`, `#legal`, `#ethics`

---

<a id="item-9"></a>
## [美国政府将审查谷歌、xAI 和微软的预发布 AI 模型](https://decrypt.co/366810/us-government-vet-pre-release-ai-models-google-xai-microsoft) ⭐️ 8.0/10

谷歌、微软和 xAI 已同意让美国政府审查其预发布的 AI 模型，同时特朗普总统正在考虑一项新的 AI 行政命令。 这标志着联邦对前沿 AI 模型进行监管的重要一步，可能影响美国未来的 AI 安全与政策制定。 该协议涉及谷歌、微软和埃隆·马斯克的 xAI 等主要 AI 公司，正值特朗普考虑签署可能取代拜登此前 AI 行政命令的新令。

rss · Decrypt · May 5, 16:21

**背景**: 美国政府日益关注 AI 监管。特朗普总统此前撤销了拜登的 AI 行政命令，目前正在考虑新的框架。xAI 由埃隆·马斯克于 2023 年创立，开发了 Grok 聊天机器人。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/XAI_(company)">xAI (company) - Wikipedia</a></li>
<li><a href="https://www.ai.gov/">AI.Gov | President Trump's AI Strategy and Action Plan</a></li>
<li><a href="https://www.lawandtheworkplace.com/2026/04/what-president-trumps-ai-executive-order-14365-means-for-employers/">What President Trump’s AI Executive Order 14365 Means For Employers | Law and the Workplace</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#government oversight`, `#AI safety`, `#policy`

---

<a id="item-10"></a>
## [OpenMythos 逆向重建 Anthropic 秘密 AI Claude Mythos](https://decrypt.co/366745/openmythos-claude-mythos-architecture-open-source-reconstruction) ⭐️ 8.0/10

开发者 Kye Gomez 发布了 OpenMythos，这是一个基于公开研究和推测、对 Anthropic 未发布的 Claude Mythos AI 模型进行理论重建的开源项目。 该项目挑战了强大 AI 模型的保密性，引发了关于 AI 安全、透明度和开源伦理的讨论，因为 Claude Mythos 据称过于危险而无法公开发布。 OpenMythos 实现了循环深度 Transformer（RDT）架构，但纯属推测，与 Anthropic 无关；项目包含免责声明，强调其独立性。

rss · Decrypt · May 4, 22:31

**背景**: Anthropic 的 Claude Mythos 是一个能力极强的 AI 模型，出于安全考虑，公司决定不公开发布。它是 Claude 系列的一部分，该系列使用宪法 AI 进行对齐。OpenMythos 试图仅利用公开信息，从基本原理出发重建其架构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/kyegomez/OpenMythos">GitHub - kyegomez/OpenMythos: A theoretical reconstruction of ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Mythos_Preview">Claude Mythos Preview</a></li>
<li><a href="https://www.forbes.com/sites/jonmarkman/2026/04/08/what-is-claude-mythos-and-why-anthropic-wont-let-anyone-use-it/">What Is Claude Mythos—And Why Anthropic Won’t ... - Forbes</a></li>

</ul>
</details>

**社区讨论**: 社区意见分歧：一些人称赞此举促进了透明度和开放科学，而另一些人则担心此类重建可能无意中导致危险 AI 能力的滥用。

**标签**: `#AI`, `#open-source`, `#reverse-engineering`, `#AI safety`, `#Anthropic`

---

<a id="item-11"></a>
## [NIST 的 CAISI 称中国 AI 落后，专家质疑方法](https://decrypt.co/366685/us-says-china-best-ai-models-lag-behind-experts-not-sure) ⭐️ 8.0/10

NIST 的人工智能标准与创新中心（CAISI）评估了 DeepSeek V4 Pro，并认为其落后前沿约 8 个月，但批评者指出评估方法存在缺陷，因为其使用的成本比较过滤器排除了除 GPT-5.4 mini 之外的所有美国模型。 这一争议凸显了客观基准测试 AI 模型的难度，以及政府主导的评估中可能存在国家偏见，这可能会影响政策决策和国际 AI 竞争。 DeepSeek V4 Pro 是一个混合专家模型，总参数 1.6 万亿，激活参数 490 亿，采用混合注意力架构。CAISI 的评估使用了私有基准测试和一个成本比较过滤器，该过滤器仅包含美国模型中的 GPT-5.4 mini。

rss · Decrypt · May 4, 18:58

**背景**: NIST 的 CAISI 旨在协调美国联邦机构间的 AI 评估方法。对 DeepSeek V4 Pro 的评估是持续评估 AI 能力的一部分。然而，在比较中排除大多数美国模型导致了方法便利性的指责。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nist.gov/news-events/news/2026/05/caisi-evaluation-deepseek-v4-pro">CAISI Evaluation of DeepSeek V4 Pro | NIST</a></li>
<li><a href="https://www.nist.gov/caisi">Center for AI Standards and Innovation (CAISI) | NIST</a></li>
<li><a href="https://build.nvidia.com/deepseek-ai/deepseek-v4-pro/modelcard">deepseek-v4-pro Model by Deepseek-ai | NVIDIA NIM</a></li>

</ul>
</details>

**社区讨论**: 新闻文章的评论对 NIST 的方法表示怀疑，一些人认为评估旨在偏袒美国模型。其他人指出，独立基准测试通常显示中国模型与美国同行竞争激烈。

**标签**: `#AI`, `#China`, `#NIST`, `#benchmarking`, `#policy`

---

<a id="item-12"></a>
## [DTCC 将代币化罗素 1000 指数股票和美国国债](https://decrypt.co/366646/dtcc-reveals-launch-tokenization-service-wall-street-giants-onboard) ⭐️ 8.0/10

管理 114 万亿美元证券的 DTCC 宣布计划推出罗素 1000 指数股票和美国国债的代币化服务，预计 2026 年 7 月开始初始交易，10 月全面上线。 这标志着区块链在金融领域主流采用的重要一步，因为 DTCC 是全球证券市场关键基础设施提供商。代币化可为数万亿美元资产实现更快的结算、全天候交易和新的效率。 超过 50 家公司（包括主要华尔街机构）已加入该计划。该服务将首先专注于代币化罗素 1000 指数中的股票和美国国债，利用 DTCC 现有的交易后基础设施。

rss · Decrypt · May 4, 15:52

**背景**: 代币化将资产权利转换为区块链上的数字代币，实现碎片化所有权、更快的结算和可编程性。罗素 1000 指数追踪美国最大的 1000 只股票，约占罗素 3000 指数总市值的 93%。美国国债被视为无风险资产，是全球金融的基石。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.dtcc.com/news/2026/may/04/dtcc-advances-development-of-new-tokenization-service">DTCC Advances DTC Tokenization Service; 50+ Firms Join | DTCC</a></li>
<li><a href="https://www.tradeweb.com/newsroom/media-center/in-the-news/dtcc-advances-tokenization-service-convenes-50-firms-digital-assets/">DTCC Advances Development of New Tokenization Service ...</a></li>
<li><a href="https://decrypt.co/366646/dtcc-reveals-launch-tokenization-service-wall-street-giants-onboard">DTCC Reveals Launch Plans for Tokenization Service With Wall Street Giants Onboard - Decrypt</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#blockchain`, `#finance`, `#DTCC`, `#securities`

---

<a id="item-13"></a>
## [计算机使用成本是结构化 API 的 45 倍](https://reflex.dev/blog/computer-use-is-45x-more-expensive-than-structured-apis/) ⭐️ 7.0/10

Reflex.dev 的一项基准测试发现，在管理面板上执行任务时，使用计算机使用（基于 GUI 的 AI 交互）的成本是使用结构化 API 的 45 倍，需要 53 步和 55.1 万个 token，而 API 仅需 8 次调用和 1.2 万个 token。 这一成本差异凸显出，计算机使用应作为 AI 代理的最后手段，尤其是在内部应用中，当结构化 API 或 MCP 等工具可用时，这引导开发者采用更高效的自动化策略。 该基准测试在同一管理面板上比较了计算机使用与自动生成的 API 端点，显示出 45 倍的成本惩罚。分析强调，对于自有状态（如数据库），结构化 API 效率高得多。

hackernews · palashawas · May 5, 16:34 · [社区讨论](https://news.ycombinator.com/item?id=48024859)

**背景**: 计算机使用指的是 AI 代理像人类一样通过视觉和鼠标/键盘输入与图形用户界面（GUI）交互。相比之下，结构化 API 提供直接的程序化数据访问和操作，避免了视觉处理和 UI 导航的开销。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://reflex.dev/blog/computer-use-is-45x-more-expensive-than-structured-apis/">Computer use is 45x More Expensive Than Structured APIs</a></li>
<li><a href="https://aitoolly.com/ai-news/article/2026-05-06-the-45x-cost-penalty-why-ai-vision-agents-struggle-against-structured-apis-in-new-benchmarks">AI Vision Agents vs APIs: A 45x Cost Difference Analysis</a></li>
<li><a href="https://openai.com/index/computer-using-agent/">Computer-Using Agent - OpenAI</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认为计算机使用是最后手段，有人指出通过对抗性 UI 设计可以使其成本更高。其他人建议使用视觉代理将 UI 映射为结构化接口供下游代理使用，或利用无障碍 API 提高效率。

**标签**: `#AI agents`, `#cost analysis`, `#API design`, `#web scraping`, `#accessibility`

---

<a id="item-14"></a>
## [Anthropic 发布 10 个金融代理模板](https://www.anthropic.com/news/finance-agents) ⭐️ 7.0/10

Anthropic 发布了十个可直接运行的 Claude 代理模板，用于金融服务，涵盖如构建推介书、KYC 筛查和月末结算等任务。 此举可能通过降低入门门槛加速 AI 在金融领域的应用，但也引发了关于信任、偏见和市场竞争的担忧。 这些模板集成了 Microsoft 365 和数据连接器，但有意避免贷款审批等高风险决策，以减轻偏见风险。

hackernews · louiereederson · May 5, 15:05 · [社区讨论](https://news.ycombinator.com/item?id=48023533)

**背景**: AI 代理是能够自主规划和执行复杂任务的系统，不同于简单的聊天机器人。在金融领域，它们可以自动化合规监控和报告生成等工作流程。Anthropic 的 Claude 模型以注重安全设计而闻名，但社区成员指出最新版本存在潜在偏见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://seekingalpha.com/news/4585757-anthropic-unveils-10-agent-templates-for-financial-services">Anthropic unveils 10 agent templates for financial services (ANTHRO:Private) | Seeking Alpha</a></li>
<li><a href="https://www.anthropic.com/news/finance-agents">Anthropic</a></li>
<li><a href="https://letsdatascience.com/news/anthropic-launches-ten-finance-agent-templates-for-claude-6516f048">Anthropic Launches Ten Finance Agent Templates for Claude | Let's Data Science</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 AI 公司处理敏感金融数据表示怀疑，一位用户指出 Claude Opus 4.7 存在明显偏见。其他人担心这些模板会扼杀初创公司，并将此次发布与 GPT Store 相提并论。

**标签**: `#AI agents`, `#financial services`, `#Anthropic`, `#bias`, `#industry disruption`

---

<a id="item-15"></a>
## [Airbyte 推出面向 AI 代理的统一数据层](https://news.ycombinator.com/item?id=48023496) ⭐️ 7.0/10

Airbyte 发布了 Airbyte Agents，这是一个统一的数据层，通过其 Context Store 为 AI 代理提供来自多个企业数据源的预索引上下文，减少了运行时 API 拼接的需求。 这解决了 AI 代理工作流中的一个关键瓶颈——代理通常浪费大量 token 和时间在 API 调用上以发现和组装数据；与直接调用 MCP 相比，Airbyte Agents 可将 token 消耗减少高达 90%，使代理更快、更可靠。 Context Store 由 Airbyte 现有的复制连接器填充，支持 Slack、Salesforce 和 Linear 等数据源。Airbyte 已开源一个基准测试工具来验证性能声明，显示在不同数据源上 token 减少 16% 到 90%。

hackernews · mtricot · May 5, 15:03

**背景**: AI 代理通常需要访问多个企业工具，但每个工具都有自己的 API，存在认证、分页和模式差异。模型上下文协议（MCP）提供了一种将代理连接到工具的标准方式，但它仍然是 API 的薄包装，要求代理确切知道要查询什么。Airbyte Agents 将数据预索引到 Context Store 中，使代理能够发现相关信息，而无需进行昂贵的运行时 API 调用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://airbyte.com/">The Context Layer for AI Agents | Airbyte</a></li>
<li><a href="https://docs.airbyte.com/ai-agents">Agent Engine | Airbyte Docs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了 MCP 兼容性和索引挑战。一些人质疑现有的基于技能的方法（如 OpenClaw、Hermes）是否已经解决了问题，而另一些人指出索引策略和元数据层对于可靠的代理回答至关重要。一位前员工称赞了向 AI 时代的适应，并建议 Airbyte Agents 可以作为 MCP 网关。

**标签**: `#AI agents`, `#data integration`, `#MCP`, `#enterprise tools`, `#API`

---

<a id="item-16"></a>
## [生物计算引发伦理担忧](https://kuber.studio/blog/Reflections/I%27m-Scared-About-Biological-Computing) ⭐️ 7.0/10

一篇博客文章以人类神经元学会玩《毁灭战士》的演示为例，反思了生物计算的伦理影响。 这一讨论凸显了关于意识、痛苦以及生物计算系统道德地位的紧迫伦理问题，可能影响未来的研究和监管。 引用的演示涉及芯片上的 20 万个人类神经元，通过强化学习学会玩《毁灭战士》，但批评者指出该设置包含完整的 PyTorch 框架，使解读复杂化。

hackernews · kuberwastaken · May 5, 16:03 · [社区讨论](https://news.ycombinator.com/item?id=48024358)

**背景**: 生物计算利用活细胞或生物分子执行计算。Cortical Labs 的《毁灭战士》演示显示神经元对电刺激做出反应以控制游戏，引发了关于此类系统是否能体验痛苦或意识的问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Biological_computing">Biological computing</a></li>
<li><a href="https://www.scientificamerican.com/article/how-human-neurons-on-a-chip-learned-to-play-doom/">How human neurons on a chip learned to play Doom</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/200-000-living-human-neurons-on-a-microchip-demonstrated-playing-doom-cortical-labs-cl1-video-shows-the-gameplay-and-explains-how-the-neurons-learn-the-game">‘200,000 living human neurons’ on a microchip demonstrated ...</a></li>

</ul>
</details>

**社区讨论**: 评论者警告不要过度解读该演示，指出 PyTorch 层的存在并对意识主张提出质疑。一些人将其与素食主义伦理相类比，而另一些人则认为意识需要具身性和情感，而不仅仅是神经活动。

**标签**: `#biological computing`, `#ethics`, `#AI`, `#neuroscience`, `#philosophy`

---

<a id="item-17"></a>
## [Kelp 声称 LayerZero 批准了导致 2.92 亿美元桥接攻击的设置](https://www.coindesk.com/web3/2026/05/05/kelp-claims-that-layerzero-approved-the-setup-it-blamed-for-usd292-million-bridge-hack) ⭐️ 7.0/10

Kelp DAO 公开指责 LayerZero 批准了导致 2.92 亿美元桥接漏洞的 1-of-1 验证器配置，同时宣布完全迁移至 Chainlink 的跨链基础设施。 这一争议凸显了跨链桥配置中的关键安全风险，并可能将信任从 LayerZero 转移到 Chainlink 等替代协议，影响更广泛的 DeFi 生态系统。 攻击利用了 1-of-1 验证器设置，其中 LayerZero Labs 是 rsETH 桥的唯一消息验证实体，Kelp 声称该配置已获得 LayerZero 的明确批准。

rss · CoinDesk · May 5, 20:21

**背景**: LayerZero 是一种支持跨链通信的全链协议。1-of-1 验证器配置意味着只有一个实体验证消息，造成单点故障。2.92 亿美元的黑客攻击被归因于朝鲜的 Lazarus 组织，LayerZero 最初指责 Kelp 的设置。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://coinhubexchange.com/kelp-dao-ditches-layerzero-for-chainlinks-cross-chain-infrastructure-following-292-million-exploit/">Kelp DAO ditches LayerZero for Chainlink’s cross-chain ...</a></li>
<li><a href="https://www.coindesk.com/tech/2026/04/20/layerzero-blames-kelp-s-setup-for-usd290-million-exploit-attributes-it-to-north-korea-s-lazarus">LayerZero blames Kelp's setup for $290 million exploit ...</a></li>
<li><a href="https://coinalertnews.com/news/2026/05/05/kelp-dao-migration-chainlink-layerzero">Kelp DAO Accuses LayerZero of Approving Flawed Setup that Led ...</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#bridge hack`, `#LayerZero`, `#Kelp`

---

<a id="item-18"></a>
## [西联汇款 Solana 稳定币或重塑支付模式](https://www.coindesk.com/business/2026/05/05/western-union-s-solana-based-stablecoin-could-reshape-its-payment-model-analyst-says) ⭐️ 7.0/10

西联汇款在 Solana 上推出了由美元支持的稳定币 USDPT，由 Anchorage Digital Bank 发行，用于与代理和合作伙伴进行全天候结算。该代币将支持 40 多个国家的跨境支付和消费者支出产品。 这标志着区块链在汇款领域主流采用的重要一步，可能为西联汇款的 2 亿多用户降低成本并缩短结算时间。这可能迫使其他传统支付公司采用类似的数字基础设施。 USDPT 完全由美元支持，并由美国首家联邦监管的加密银行 Anchorage Digital Bank 发行。西联汇款计划将 USDPT 整合到其现有的支付通道和代理网络中，而不是将其视为独立的加密产品。

rss · CoinDesk · May 5, 17:22

**背景**: 西联汇款是一家拥有超过 2 亿用户的全球汇款巨头。稳定币是与美元等稳定资产挂钩的加密货币，可在区块链网络上实现快速、低成本的转账。Solana 是一种高吞吐量区块链，以低交易费用和快速最终性著称。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ir.westernunion.com/news/archived-press-releases/press-release-details/2026/Western-Union-Launches-USDPT-on-Solana-Advancing-Regulated-Digital-Infrastructure-for-Global-Payments/default.aspx">Western Union Launches USDPT on Solana Advancing Regulated ...</a></li>
<li><a href="https://www.coindesk.com/business/2026/05/05/western-union-s-solana-based-stablecoin-could-reshape-its-payment-model-analyst-says">Western Union’s Solana-based stablecoin could reshape its ...</a></li>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/western-union-launches-solana-based-164000082.html?fr=sycsrp_catchall">Western Union Launches Solana-Based USDPT Stablecoin With ...</a></li>

</ul>
</details>

**标签**: `#stablecoin`, `#Solana`, `#blockchain payments`, `#remittance`, `#crypto adoption`

---

<a id="item-19"></a>
## [华尔街警告：人工构建的市场跟不上机器交易速度](https://www.coindesk.com/markets/2026/05/05/wall-street-warns-human-built-markets-can-t-keep-up-with-machine-speed-trading) ⭐️ 7.0/10

华尔街分析师发出警告，认为人工构建的市场基础设施无法跟上机器交易的速度，并指出闪崩和流动性缺口等系统性风险。 这突显了现代金融市场的一个关键脆弱性：高频交易算法可能超越传统保障措施，导致市场不稳定，并为高频交易公司带来不公平优势。 该警告聚焦于延迟套利和市场微观结构问题，高频交易公司利用速度优势从过时价格中获利，而监管机构难以更新规则以适应毫秒级交易。

rss · CoinDesk · May 5, 15:19

**背景**: 高频交易（HFT）使用强大的计算机在微秒内执行交易，占股票和其他资产交易量的很大一部分。市场微观结构研究交易机制如何影响价格形成和交易成本。延迟套利是一种策略，高频交易公司利用不同交易所之间因数据传播较慢而产生的价格差异获利。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.investopedia.com/articles/markets/012716/four-big-risks-algorithmic-highfrequency-trading.asp">4 Big Risks of Algorithmic High-Frequency Trading - Investopedia High-Frequency Trading Risks and Rewards - Phoenix Strategy Group Understanding the Risks of High Frequency Trading High-Frequency Trading (HFT) - FOREX.com US Understanding the Risks of High-Frequency Trading: A Deep ... High-Frequency Crypto Trading Strategies, Tools, and Risks ... High Frequency Trading Risk Management Insights - MarketBulls</a></li>
<li><a href="https://en.wikipedia.org/wiki/Market_microstructure">Market microstructure</a></li>
<li><a href="https://en.wikipedia.org/wiki/Latency_arbitrage">Latency arbitrage</a></li>

</ul>
</details>

**标签**: `#high-frequency trading`, `#market structure`, `#finance`, `#regulation`, `#technology`

---

<a id="item-20"></a>
## [Solana 与 Google Cloud 推出面向 AI 代理的稳定币支付服务](https://decrypt.co/366876/solana-google-cloud-launch-stablecoin-payments-service-ai-agents) ⭐️ 7.0/10

Solana 基金会与 Google Cloud 合作推出了 Pay.sh 服务，允许 AI 代理按请求次数使用稳定币支付 API 费用，无需传统账户或订阅。 这一整合将区块链支付与 AI 代理基础设施连接起来，实现了机器对机器支付的自动化微交易，可能改变 AI 服务的变现和访问方式。 Pay.sh 允许 AI 机器人按请求使用稳定币发现、访问和支付 Google Cloud 及社区 API，绕过传统账户，实现无缝微交易。

rss · Decrypt · May 5, 20:10

**背景**: AI 代理通常需要为 API 调用付费以访问外部服务，但传统支付方式需要人工干预或预充值账户。区块链上的稳定币提供了适合机器对机器交易的可编程、自动化支付通道。该服务利用了 Solana 的高速低成本区块链和 Google Cloud 的基础设施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/solana-foundation/pay">solana-foundation/pay - GitHub</a></li>
<li><a href="https://www.thestreet.com/crypto/innovation/solana-rolls-out-pay-sh-with-google-cloud-to-bring-pay-per-use-api-payments-to-ai">Solana rolls out Pay.sh with Google Cloud to bring pay-per-use API ...</a></li>
<li><a href="https://solana.com/">Solana</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#blockchain`, `#stablecoins`, `#Google Cloud`, `#Solana`

---

<a id="item-21"></a>
## [DeepClaude：用 DeepSeek 运行 Claude Code，成本降低 17 倍](https://decrypt.co/366729/deepclaude-run-claude-code-deepseek-brain-17x-cheaper) ⭐️ 7.0/10

一个名为 DeepClaude 的开源脚本将 Claude Code 昂贵的 Anthropic 后端替换为 DeepSeek V4 Pro、OpenRouter 或 Fireworks AI 等更便宜的替代方案，在保留代理循环功能的同时将成本降低多达 17 倍。 这极大地降低了开发者使用 Claude Code 强大代理循环的门槛，使先进的 AI 辅助编程对个人和小团队更加可及且经济高效。 DeepClaude 支持包括 DeepSeek V4 Pro、OpenRouter 和 Fireworks AI 在内的多个后端，并保留了完整的代理循环——即 Claude 评估提示、调用工具、接收结果直至任务完成的迭代过程。

rss · Decrypt · May 4, 20:19

**背景**: Claude Code 是一款 AI 编程助手，通过代理循环迭代地解决问题。其默认后端是 Anthropic 的专有模型，重度使用成本较高。DeepSeek V4 Pro 是中国公司 DeepSeek 推出的高性价比开放权重模型，以强大的推理能力和有竞争力的定价著称。OpenRouter 提供统一 API 访问众多 AI 模型，支持故障切换和成本优化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(product)">DeepSeek (product)</a></li>
<li><a href="https://code.claude.com/docs/en/agent-sdk/agent-loop">How the agent loop works - Claude Code Docs</a></li>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>

</ul>
</details>

**标签**: `#AI`, `#open-source`, `#cost optimization`, `#developer tools`, `#Claude Code`

---

<a id="item-22"></a>
## [IREN 以 6.25 亿美元全股票交易收购 Mirantis，强化 AI 云平台](https://www.theblock.co/post/400032/iren-mirantis-625-million-all-stock-deal-round-out-ai-cloud-platform?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

IREN 以 6.25 亿美元的全股票交易收购了 Mirantis，以增强其 AI 云平台，分析师估计该交易对 Mirantis 的估值约为其收入的 4 到 5 倍。 此次收购巩固了 IREN 在竞争激烈的 AI 云基础设施市场中的地位，将 IREN 的数据中心能力与 Mirantis 的开源云和容器管理专长相结合。 这笔全股票交易对 Mirantis 的估值约为其收入的 4 到 5 倍，预计此次收购将帮助 IREN 完善其 AI 云平台产品。

rss · The Block · May 5, 15:43

**背景**: IREN 是一家专注于 AI、高性能计算和可持续计算的新一代数据中心公司，而 Mirantis 是一家专注于容器和云管理的 B2B 开源云计算软件和服务公司。全股票交易意味着 IREN 用其股票交换 Mirantis 的股票，避免了现金支出。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mirantis">Mirantis - Wikipedia</a></li>
<li><a href="https://www.iren.com/">IREN | Next-Gen Data Centers for AI, HPC & Sustainable Compute</a></li>

</ul>
</details>

**标签**: `#acquisition`, `#AI cloud`, `#infrastructure`, `#valuation`

---

<a id="item-23"></a>
## [PaletteInspiration：从 3000 多幅大师画作中提取配色方案](https://paletteinspiration.com/) ⭐️ 6.0/10

PaletteInspiration.com 上线，这是一个可浏览的配色方案档案库，从 3000 多幅大师画作中提取颜色，并包含一个“色彩和谐探索器”，它基于真实画作中的共现数据展示经验性的颜色搭配，而非算法规则。 该工具为设计师提供了一种数据驱动的替代方案，不同于通常生成相似柔和粉彩的常规配色生成器，它利用了数百年的艺术色彩知识。这可能会激发数字设计中更细致、更具历史依据的色彩选择。 色彩和谐探索器允许用户拖动色轮至任意色相，并查看大师画家历史上与之搭配的颜色，这完全基于数千幅画作中的经验共现数据，而非标准色彩理论规则。该网站无需注册、付费或提供邮箱。

hackernews · ouli · May 5, 18:13 · [社区讨论](https://news.ycombinator.com/item?id=48026342)

**背景**: 配色生成器通常使用算法色彩理论（如互补色、类似色方案）来建议和谐搭配。然而，这些规则往往产生可预测的结果。PaletteInspiration 则从大师画作中挖掘实际的颜色使用情况，提供基于经验、反映真实艺术实践的搭配。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://colordev.site/harmony">Color Harmony Explorer — ColorDev</a></li>
<li><a href="https://colorcodegen.com/harmony">Color Harmony Explorer</a></li>
<li><a href="https://www.toolsboxhq.com/design_tools/color-harmony-explorer/">Color Harmony Explorer - Create Beautiful Color Schemes ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论对准确性提出了担忧：一位用户指出，许多调色板因老化氧化的清漆而呈现褐色，并非艺术家的原始意图。另一位用户指出了“Naïve Art”风格的显示错误，并对“Modernism”和“Modernismo”的命名提出疑问。总体情绪是建设性的，并提出了改进建议。

**标签**: `#color palettes`, `#art`, `#design tools`, `#data visualization`

---

<a id="item-24"></a>
## [GLM-5V-Turbo：面向智能体的多模态基础模型](https://arxiv.org/abs/2604.26752) ⭐️ 6.0/10

Z.AI 发布了 GLM-5V-Turbo，这是一个原生为智能体任务设计的多模态基础模型，将感知、推理、规划和工具使用集成到单一模型中。 该模型代表了向统一多模态智能体迈进的一步，能够在图像、视频、网页和 GUI 等多种上下文中感知和行动，有望降低构建智能体系统的复杂性。 社区反馈表明，GLM-5V-Turbo 在编码和推理方面不如较新的开源模型，并且在坐标点击和智能体死循环方面存在问题。

hackernews · gmays · May 5, 17:52 · [社区讨论](https://news.ycombinator.com/item?id=48026021)

**背景**: 多模态基础模型结合文本、图像、视频等输入，实现更自然的人机交互。智能体循环是一种迭代周期，AI 在其中感知、推理、行动并观察结果，有时会导致重复失败状态，即死循环。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2604.26752">[2604.26752] GLM-5V-Turbo: Toward a Native Foundation Model for Multimodal Agents</a></li>
<li><a href="https://docs.z.ai/guides/vlm/glm-5v-turbo">GLM-5V-Turbo - Overview - Z.AI DEVELOPER DOCUMENT</a></li>
<li><a href="https://blogs.oracle.com/developers/what-is-the-ai-agent-loop-the-core-architecture-behind-autonomous-ai-systems">What Is the AI Agent Loop? The Core Architecture Behind ...</a></li>

</ul>
</details>

**社区讨论**: 用户反馈不一：一些人称赞 GLM-5V-Turbo 的速度和日常可靠性，而另一些人则认为它在编码和推理方面已经过时。坐标点击和死循环是常见痛点，但一位用户指出，适当的框架设计可以缓解循环问题。

**标签**: `#multimodal`, `#AI agents`, `#foundation model`, `#GLM`

---

<a id="item-25"></a>
## [Cloudflare 提出 x402 以修复 AI 代理的网络经济问题](https://www.coindesk.com/tech/2026/05/05/ai-agents-are-breaking-web-economics-but-cloudflare-says-x402-can-help) ⭐️ 6.0/10

Cloudflare 提出了一种名为 x402 的新协议，以解决 AI 代理对网络经济造成的破坏，该协议支持通过 HTTP 进行即时、自动的稳定币支付。 该提案可能重塑在线经济，允许 AI 代理为访问内容和服务付费，从而可能取代当前的广告模式，为内容创作者创造新的收入来源。 x402 是一种开放、中立的互联网原生支付标准，最初由 Coinbase 开发，支持大规模代理支付。Cloudflare 的参与可能加速其在网络基础设施中的采用。

rss · CoinDesk · May 5, 21:47

**背景**: AI 代理越来越多地在网络上执行任务，如抓取数据或进行购买，这破坏了基于人类流量和广告的传统网络经济。x402 协议为代理提供了一种自动进行微支付的方式，为机器对机器交易创建了新的经济层。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.x402.org/">x402 - Payment Required | Internet-Native Payments Standard</a></li>
<li><a href="https://docs.cdp.coinbase.com/x402/welcome">Welcome to x402 - Coinbase Developer Documentation</a></li>
<li><a href="https://spectrum.ieee.org/ai-agent-economy">AI Agents Will Transform the Online Economy - IEEE Spectrum</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#web economics`, `#Cloudflare`, `#x402`

---

<a id="item-26"></a>
## [道富银行：DeFi 攻击后机构要求加强区块链安全](https://www.coindesk.com/business/2026/05/05/state-street-says-institutions-want-improved-blockchain-security-in-wake-of-recent-defi-attacks) ⭐️ 6.0/10

大型金融机构道富银行报告称，在近期 DeFi 攻击事件后，机构客户要求提升区块链安全性。这一表态凸显了机构对去中心化金融协议安全性的日益担忧。 这表明，除非提高安全标准，否则机构对区块链技术的采用可能会放缓。这给 DeFi 项目和区块链基础设施提供商带来了压力，要求他们优先考虑安全性以满足机构需求。 道富银行未具体说明是哪些攻击或寻求哪些安全改进，但近期备受关注的 DeFi 黑客攻击包括 2023 年 Euler Finance 的 1.97 亿美元闪电贷攻击。机构可能要求更好的智能合约审计、保险和监管合规。

rss · CoinDesk · May 5, 21:27

**背景**: 去中心化金融（DeFi）协议利用区块链上的智能合约提供无需中介的金融服务。然而，它们一直受到黑客攻击和漏洞利用的困扰，近年来总损失超过 32.4 亿美元。道富银行等机构服务的机构投资者在将大量资金投入基于区块链的产品之前，需要强大的安全保障。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blockworks.com/news/biggest-defi-hacks-2023">The 5 biggest DeFi hacks of 2023 - Blockworks</a></li>
<li><a href="https://www.deloitte.com/us/en/services/consulting/articles/blockchain-security-risks.html">Blockchain Security Risks for Financial Organizations | Deloitte US</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#security`, `#DeFi`, `#institutional`

---

<a id="item-27"></a>
## [Solana 的 Alpenglow 升级预计下季度到来](https://www.coindesk.com/tech/2026/05/05/solana-s-alpenglow-upgrade-could-arrive-next-quarter-co-founder-yakovenko-says) ⭐️ 6.0/10

Solana 联合创始人 Anatoly Yakovenko 在 2026 年共识大会上宣布，Alpenglow 升级预计下季度到来，该升级将替换网络的共识层，目标是将交易最终确认时间从 12.8 秒缩短至 100-150 毫秒。 此次升级可能使 Solana 成为最快的区块链网络之一，最终确认时间可与 Visa 交易处理相媲美。通过将验证者投票移至链下，释放了大约四分之三的区块空间用于用户交易，有望降低费用并提高可扩展性。 Alpenglow 是对 Solana 共识层的完全替换，而非渐进式改进。该升级还降低了验证者成本，增强了机构采用的前景。

rss · CoinDesk · May 5, 17:24

**背景**: Solana 是一个以速度和低交易成本著称的高性能区块链。然而，其当前的共识机制因网络拥堵和偶尔宕机而受到批评。Alpenglow 升级旨在通过从根本上重新设计网络达成共识的方式来解决这些问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/05/05/solana-s-alpenglow-upgrade-could-arrive-next-quarter-co-founder-yakovenko-says">Solana news (SOL): ‘Alpenglow’ upgrade could arrive next ...</a></li>
<li><a href="https://www.alchemy.com/blog/solana-alpenglow">What is Solana Alpenglow? Consensus upgrade explained | Alchemy</a></li>
<li><a href="https://solana.com/news/solana-network-upgrades">Solana Network Upgrades What is Solana Alpenglow? Consensus upgrade explained | Alchemy Solana targets speed of light transactions with Q3 Alpenglow ... Solana Alpenglow Explained: The 100x Speed Upgrade That Could ... Images What is Alpenglow Upgrade, and Why is it Bullish for Solana? Solana News: Solana Alpenglow Targets 150ms Finality as ...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#Solana`, `#cryptocurrency`, `#upgrade`

---

<a id="item-28"></a>
## [Drift 协议计划在 2.95 亿美元黑客攻击后偿还用户](https://decrypt.co/366897/how-solana-exchange-drift-repay-users-295-million-crypto-hack) ⭐️ 6.0/10

基于 Solana 的去中心化交易所 Drift 协议宣布了一项计划，在遭受朝鲜黑客攻击损失 2.95 亿美元后偿还用户，并声称大部分被盗资金仍可追踪。 此事件凸显了 DeFi 平台持续存在的安全漏洞以及追回被盗资产的挑战，而 Drift 的主动偿还计划可能为加密货币生态系统中的用户保护树立先例。 黑客攻击发生在 2026 年 4 月 1 日，大约 12 分钟内盗走了约 2.85 亿美元的用户资产，大部分资金在数小时内被桥接至以太坊；Drift 声称被盗资金可追踪，并旨在让受害者获得全额赔偿。

rss · Decrypt · May 5, 21:25

**背景**: Drift 协议是 Solana 上最大的开源永续合约交易所，提供杠杆交易和 DeFi 服务。加密货币追踪是一种用于跟踪区块链交易的取证技术，常被执法部门用于识别黑客和追回资金。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.trmlabs.com/resources/blog/north-korean-hackers-attack-drift-protocol-in-285-million-heist">North Korean Hackers Attack Drift Protocol In USD 285 Million Heist | TRM Blog</a></li>
<li><a href="https://en.wikipedia.org/wiki/Cryptocurrency_tracing">Cryptocurrency tracing - Wikipedia</a></li>

</ul>
</details>

**标签**: `#crypto`, `#security`, `#Solana`, `#hack`

---

<a id="item-29"></a>
## [OpenAI 的 GPT-5.5 Instant 成为 ChatGPT 默认模型](https://decrypt.co/366842/openai-upgraded-chatgpt-default-model-what-gpt-5-5-instant-does) ⭐️ 6.0/10

OpenAI 已将 GPT-5.5 Instant 设为 ChatGPT 的默认模型，取代了 GPT-5.3 Instant。新模型在高风险话题上的幻觉减少了 52.5%，回答更简洁，并引入了记忆来源功能以实现更好的个性化。 此次更新提升了 ChatGPT 的可靠性和用户体验，使其在医学和法律等敏感领域更加值得信赖。增强的记忆和个性化功能也让该助手更接近真正具有上下文感知能力的 AI 伴侣。 GPT-5.5 Instant 立即向所有 ChatGPT 用户推出，免费用户可获得轻量版记忆改进。该模型还具有更智能的自我修正功能，以及新的记忆来源控制，可显示哪些存储的上下文影响了回复。

rss · Decrypt · May 5, 18:29

**背景**: ChatGPT 是由 OpenAI 的大型语言模型驱动的对话式 AI 系统。之前的默认模型（如 GPT-5.3 Instant）有时会产生不准确或过于冗长的回复。新的 GPT-5.5 Instant 旨在通过减少幻觉和更简洁的回答来解决这些问题，同时改进模型跨会话记住用户偏好的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/gpt-5-5-instant/">GPT‑5.5 Instant: smarter, clearer, and more personalized</a></li>
<li><a href="https://techcrunch.com/2026/05/05/openai-releases-gpt-5-5-instant-a-new-default-model-for-chatgpt/">OpenAI releases GPT-5.5 Instant, a new default model for ...</a></li>
<li><a href="https://the-decoder.com/chatgpt-update-rolls-out-gpt-5-5-instant-with-fewer-hallucinations-and-more-personalized-answers/">ChatGPT update rolls out GPT-5.5 Instant with fewer ...</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#ChatGPT`, `#GPT-5.5`, `#AI`, `#language model`

---

<a id="item-30"></a>
## [Bullish 以 42 亿美元收购 Equiniti](https://decrypt.co/366821/bullish-shares-pop-4-2-billion-deal-acquire-equinity) ⭐️ 6.0/10

在纽约证券交易所上市的加密货币交易所运营商 Bullish 宣布以 42 亿美元收购 Equiniti，后者是一家为伯克希尔·哈撒韦和穆迪等传统股票市场提供服务的知名过户代理商。 此次收购将区块链基础设施与传统股权过户代理服务连接起来，可能推动代币化证券的发展，加速加密货币与传统金融的融合。 Equiniti 是全球最大的过户代理商之一，为多家大型企业提供股东服务。这笔交易价值 42 亿美元，被视为 Bullish 成为代币化证券全球过户代理商的变革性举措。

rss · Decrypt · May 5, 16:52

**背景**: 过户代理商负责维护上市公司的股权记录并管理股息支付。Bullish 是一家面向机构和高级交易者的受监管加密货币交易所。此次交易旨在将传统股权基础设施与基于区块链的代币化技术相结合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wsj.com/finance/currencies/crypto-exchange-bullish-strikes-4-2-billion-deal-for-transfer-agent-in-tokenization-push-4af8f41f">Crypto Exchange Bullish Strikes $4.2 Billion Deal for Transfer Agent in ...</a></li>
<li><a href="https://money.usnews.com/investing/news/articles/2026-05-05/bullish-to-buy-equiniti-in-4-2-billion-deal">Crypto Exchange Bullish to Buy Equiniti for $4.2 Billion in ...</a></li>
<li><a href="https://www.barrons.com/articles/bullish-stock-crypto-exchange-equiniti-deal-f4506636">Crypto Exchange Bullish Soars on ‘Transformative’ $4 Billion ...</a></li>

</ul>
</details>

**标签**: `#crypto`, `#blockchain`, `#finance`, `#M&A`

---

<a id="item-31"></a>
## [Andreessen Horowitz 筹集 22 亿美元投资加密初创公司](https://decrypt.co/366788/andreessen-horowitz-raises-2-2-billion-fund-crypto-startups) ⭐️ 6.0/10

Andreessen Horowitz (a16z) 为其专注于加密和区块链初创公司的新基金筹集了 22 亿美元，标志着机构对该行业的信心重燃。 此次大规模募资表明加密投资环境正在复苏，并为区块链技术创新提供了大量资金，可能加速去中心化金融 (DeFi)、NFT 和 Web3 应用的发展。 该基金是 a16z 迄今为止规模最大的加密专项基金，且是在市场低迷期之后推出的，表明其对下一波加密应用浪潮的战略押注。

rss · Decrypt · May 5, 14:06

**背景**: Andreessen Horowitz 是一家知名的风险投资公司，自 2013 年以来一直积极投资加密领域。加密市场在 2022 年经历了大幅下滑，但近期的复苏迹象重新激发了投资者的兴趣。

**标签**: `#crypto`, `#venture capital`, `#funding`, `#blockchain`

---

<a id="item-32"></a>
## [Ripple 与加密行业共享朝鲜威胁情报](https://decrypt.co/366751/ripple-to-share-north-korean-threat-intelligence-with-crypto-industry) ⭐️ 6.0/10

Ripple 宣布将与加密行业共享朝鲜威胁情报，此前 2026 年 4 月发生的两起九位数 DeFi 攻击被归因于朝鲜黑客使用社会工程学手段。 这一举措增强了整个加密生态系统的集体安全性，使协议能够主动防御复杂的朝鲜黑客攻击活动，这些攻击已造成超过 5 亿美元的损失。 该情报涵盖朝鲜黑客使用的社会工程学和内部人员招募策略，并将通过 Crypto ISAC 的新 API 分发给成员组织。

rss · Decrypt · May 5, 10:56

**背景**: 朝鲜黑客组织（如 Lazarus）越来越多地利用复杂的社会工程学手段针对去中心化金融（DeFi）协议，渗透团队并窃取资金。2026 年 4 月，Drift 和 KelpDAO 协议遭受攻击，损失总额超过 5 亿美元，归因于一场持续六个月的朝鲜社会工程学活动。Crypto ISAC 是一个行业信息共享与分析中心，帮助成员交换威胁数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://beincrypto.com/ripple-dprk-threat-intelligence-crypto-isac/">How Ripple is Leading Fight Against North Korean Crypto Hackers</a></li>
<li><a href="https://thehackernews.com/2026/04/285-million-drift-hack-traced-to-six.html">$285 Million Drift Hack Traced to Six-Month DPRK Social ...</a></li>
<li><a href="https://coinalertnews.com/news/2026/05/05/ripple-shares-north-korea-threat-intel">Ripple Shares North Korea Threat Intel to Combat DPRK Hackers ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#security`, `#threat intelligence`, `#North Korea`, `#DeFi`

---

<a id="item-33"></a>
## [Haun Ventures 筹集 10 亿美元基金，专注加密与 AI 代理基础设施](https://decrypt.co/366728/haun-ventures-raises-1-billion-fund-intersection-crypto-tech-ai-agents) ⭐️ 6.0/10

Katie Haun 的风险投资公司 Haun Ventures 完成了一支 10 亿美元基金的募集，用于投资支持自主 AI 代理无需人工干预即可交易的加密基础设施。 该基金表明机构对加密与 AI 融合的信心日益增强，可能加速机器对机器经济的发展，使 AI 代理能够自主管理支付和资产。 该基金瞄准专门为 AI 代理自主交易设计的加密基础设施和系统，建立在 Stripe 等公司近期推动代理支付举措的基础上。

rss · Decrypt · May 4, 20:32

**背景**: AI 代理是能够自主执行任务（如预订旅行或购物）的软件程序。为了在商业中独立运作，它们需要基础设施来持有资金、执行交易和验证身份——区块链和加密系统可以提供这些能力。最近的进展，如 Stripe 为 AI 代理推出的数字钱包以及 a16z 对区块链对 AI 益处的分析，凸显了人们对这一交叉领域日益增长的兴趣。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/366728/haun-ventures-raises-1-billion-fund-intersection-crypto-tech-ai-agents">Haun Ventures Raises $1 Billion Fund for the Intersection of Crypto and AI Agents - Decrypt</a></li>
<li><a href="https://www.unite.ai/stripe-hands-ai-agents-a-wallet-ushering-in-agentic-purchasing/">Stripe Hands AI Agents a Wallet, Ushering In Agentic ...</a></li>
<li><a href="https://a16zcrypto.com/posts/article/5-ways-blockchains-help-ai-agents/">The missing infrastructure for AI agents: 5 ways blockchains can help - a16z crypto</a></li>

</ul>
</details>

**标签**: `#crypto`, `#AI agents`, `#venture capital`, `#infrastructure`

---

<a id="item-34"></a>
## [Ledger 通过 Yield.xyz 集成 Hyperliquid 永续合约交易](https://www.theblock.co/post/400110/ledger-hyperliquid-perps-trading-hardware-wallets-yield-xyz?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Ledger 集成了 Yield.xyz，使其硬件钱包用户可以直接在设备上交易 Hyperliquid 的永续合约。 此次集成弥合了自托管硬件钱包与高杠杆 DeFi 衍生品交易之间的鸿沟，有望在保障安全的同时吸引更多用户参与链上永续合约交易。 约 20% 的 Ledger 用户将率先通过这一非托管 API 集成获得 Hyperliquid 链上永续市场的访问权限。

rss · The Block · May 5, 21:00

**背景**: Hyperliquid 是一个用于链上永续合约交易的去中心化交易所（DEX），提供高达 40 倍杠杆和中央限价订单簿。Yield.xyz 是一个非托管 API，为钱包和托管方提供多种链上收益机会。Ledger 是领先的硬件钱包提供商，以安全的加密资产自托管而闻名。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/400110/ledger-hyperliquid-perps-trading-hardware-wallets-yield-xyz">Ledger integrates Hyperliquid perps trading in its hardware ...</a></li>
<li><a href="https://financefeeds.com/ledger-rolls-out-perps-trading-via-hyperliquid-for-hardware-wallet-users/">Ledger Rolls Out Perps Trading via Hyperliquid for Hardware ...</a></li>
<li><a href="https://www.gate.com/learn/articles/what-is-hyperliquid-a-complete-guide-to-the-popular-on-chain-perpetual-futures-trading-platform">What Is Hyperliquid? Complete Guide to On-Chain Perpetual ...</a></li>

</ul>
</details>

**标签**: `#crypto`, `#DeFi`, `#hardware wallet`, `#blockchain`

---

<a id="item-35"></a>
## [道富与 Galaxy 在 Solana 上推出代币化基金](https://www.theblock.co/post/400086/state-street-and-galaxy-launch-fund-on-solana-designed-to-sweep-stablecoins-into-productive-vehicle?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

道富与 Galaxy Digital 在 Solana 上推出了 State Street Galaxy Onchain Liquidity Sweep Fund（SWEEP），这是一个代币化私人流动性基金，可自动将稳定币转入短期美国国债等生息资产。 该基金将传统现金管理与区块链连接起来，使机构投资者能够在保持全天候链上流动性的同时，从稳定币中获取收益。这标志着机构在 Solana 上采用代币化现实世界资产的重要一步。 该基金由道富经验丰富的现金管理团队管理，并利用 Solana 高速、低成本的区块链进行代币发行和交易。它提供全天候访问，旨在为闲置的稳定币提供一个生息工具。

rss · The Block · May 5, 17:27

**背景**: 代币化基金将国债等现实世界资产以数字代币形式记录在区块链上，从而实现更快的结算和可编程性。Solana 是一个高性能区块链，因其低费用和高吞吐量而越来越多地被用于代币化。稳定币是与法定货币挂钩的加密货币，常用于链上交易，但通常不产生收益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://investors.statestreet.com/investor-news-events/press-releases/news-details/2026/State-Street-Investment-Management-and-Galaxy-Digital-Bring-Cash-Management-Onchain/default.aspx">State Street Investment Management and Galaxy Digital Bring Cash ...</a></li>
<li><a href="https://am.galaxy.com/galaxy-state-street-sweep-fund/">SWEEP | State Street Galaxy Onchain Liquidity Sweep Fund</a></li>
<li><a href="https://www.coindesk.com/markets/2026/05/05/state-street-and-galaxy-launch-tokenized-fund-to-bring-cash-management-onchain">State Street and Galaxy launch tokenized fund to bring ... - CoinDesk</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#stablecoins`, `#Solana`, `#DeFi`, `#institutional finance`

---

<a id="item-36"></a>
## [Securitize 携手 Jump 和 Jupiter 推出全链上合规股票](https://www.theblock.co/post/400051/securitize-taps-jump-and-jupiter-as-it-rolls-out-fully-onchain-regulated-onchain-stocks?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Securitize 在 Solana 上推出了完全链上、合规的代币化股票交易，Jump Trading 通过其 PropAMM 提供机构流动性，Jupiter 则支持零售和机构访问。 这标志着传统金融与去中心化金融（DeFi）融合的重要一步，提供了结合合规性与区块链效率的合规链上股票。这可能为代币化证券的更广泛机构采用铺平道路。 Jump 的 PropAMM 使用链下定价引擎配合链上执行程序提供流动性，而 Jupiter 则聚合 Solana DEX 的流动性。该系统在现有监管框架内运行，利用了 Securitize 的经纪商和过户代理牌照。

rss · The Block · May 5, 14:46

**背景**: Securitize 是一家金融科技公司，致力于在区块链平台上将现实世界资产（RWA）代币化。PropAMM 是 Jump Crypto 开发的流动性机制，结合了链下价格发现与链上执行。Jupiter 是基于 Solana 的 DeFi 聚合器，可在多个去中心化交易所之间路由交易。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://jumpcrypto.com/resources/propamms-and-the-next-chapter-of-permissionless-market-structure">PropAMMs and the Next Chapter of Permissionless Market Structure</a></li>
<li><a href="https://www.edgen.tech/news/post/securitize-and-2-partners-bring-regulated-onchain-stocks-to-solana">Securitize and 2 partners bring regulated onchain stocks to ...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#crypto`, `#DeFi`, `#securities`, `#Solana`

---