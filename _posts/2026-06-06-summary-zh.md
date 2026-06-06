---
layout: default
title: "Horizon Summary: 2026-06-06 (ZH)"
date: 2026-06-06
lang: zh
---

> From 83 items, 17 important content pieces were selected

---

1. [微软开源 pg_durable，实现 Postgres 持久化执行](#item-1) ⭐️ 8.0/10
2. [谷歌发布 Gemma 4 QAT 模型，提升移动端效率](#item-2) ⭐️ 8.0/10
3. [Claude-3.5 Sonnet 可能在 rsync 中引入错误](#item-3) ⭐️ 8.0/10
4. [开发者分享与生成式 AI 的‘糟糕’时刻](#item-4) ⭐️ 8.0/10
5. [美国大型银行计划共建共享代币化存款网络](#item-5) ⭐️ 8.0/10
6. [Zcash 因 Orchard 严重漏洞暴跌 38%](#item-6) ⭐️ 8.0/10
7. [Anthropic 协助 NSA 网络攻击，同时呼吁暂停 AI](#item-7) ⭐️ 8.0/10
8. [Anthropic：AI 已能编写自身大部分代码](#item-8) ⭐️ 8.0/10
9. [太阳能海水淡化方法避免盐堵塞](#item-9) ⭐️ 7.0/10
10. [英国政府将 Gov.uk Pay 支付服务从 Stripe 切换至 Adyen](#item-10) ⭐️ 7.0/10
11. [适马 45mm 镜头拆解揭示现代维修挑战](#item-11) ⭐️ 6.0/10
12. [国际空间站宇航员因空气泄漏维修而避难](#item-12) ⭐️ 6.0/10
13. [自定义 TDD 代理技能引发社区热议](#item-13) ⭐️ 6.0/10
14. [国会提出 7 项新的加密货币税收法案](#item-14) ⭐️ 6.0/10
15. [英国少年因加密货币研究遭俄罗斯制裁](#item-15) ⭐️ 6.0/10
16. [摩根士丹利通过借贷实现实物加密货币 ETF 转换](#item-16) ⭐️ 6.0/10
17. [多家大银行计划 2027 年推出代币化存款网络](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [微软开源 pg_durable，实现 Postgres 持久化执行](https://github.com/microsoft/pg_durable) ⭐️ 8.0/10

微软开源了 pg_durable，这是一个 PostgreSQL 扩展，通过提供用于构建函数图的 SQL DSL 和用于可靠编排的后台工作进程，实现了数据库内的持久化执行。 这将持久化执行能力直接引入 PostgreSQL，使开发者无需外部系统即可构建防崩溃的工作流，从而简化需要高可靠性的应用架构。 该扩展基于两个 Rust 库构建：duroxide 提供持久化任务框架，另一个负责编排；它适用于主要驻留在 Postgres 内部的工作流，而非跨异构系统的工作流。

hackernews · coffeemug · Jun 5, 15:59 · [社区讨论](https://news.ycombinator.com/item?id=48414367)

**背景**: 持久化执行是一种编程模型，工作流状态会自动持久化，以便在崩溃后从故障点精确恢复执行。传统方法依赖外部工作流引擎如 Temporal 或 Azure Durable Functions。pg_durable 将这一能力直接嵌入 PostgreSQL，降低了以数据库为中心的应用程序的运维复杂性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/microsoft/pg_durable">GitHub - microsoft/pg_durable: PostgreSQL in-database durable execution · GitHub</a></li>
<li><a href="https://temporal.io/blog/what-is-durable-execution">The definitive guide to Durable Execution | Temporal</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的讨论反应不一：有人欣赏数据库内队列的选项，也有人担心与外部解决方案相比缺乏版本控制、可测试性和可观测性。还有用户指出 Azure PostgreSQL 在支持此类扩展方面滞后，限制了其在该平台上的实际使用。

**标签**: `#PostgreSQL`, `#durable execution`, `#open source`, `#Microsoft`, `#database`

---

<a id="item-2"></a>
## [谷歌发布 Gemma 4 QAT 模型，提升移动端效率](https://blog.google/innovation-and-ai/technology/developers-tools/quantization-aware-training-gemma-4/) ⭐️ 8.0/10

谷歌发布了针对 Gemma 4 系列的量化感知训练（QAT）模型，优化了在移动设备和笔记本电脑上的高效部署。这些模型已在 Hugging Face 上提供，并可通过 LiteRT 等工具在本地运行。 此次发布使得在设备端进行强大 AI 推理成为可能，同时降低了内存和计算需求，让先进模型能在消费级硬件上运行。这也表明谷歌致力于开放、高效的 AI 模型，可能加速在移动和边缘应用中的采用。 QAT 模型包括一个 120 亿参数的版本，在 Q4_0 量化下仅需 6.7GB 显存，轻松适配 16GB 内存限制。这些模型支持多模态输入，包括音频和图像，社区成员已在 Mac 上成功运行。

hackernews · theanonymousone · Jun 5, 16:18 · [社区讨论](https://news.ycombinator.com/item?id=48414653)

**背景**: 量化感知训练（QAT）是一种将权重精度降低融入训练过程的技术，相比训练后量化能减少精度损失。Gemma 4 是谷歌最新的开放模型系列，专为高级推理和智能体工作流设计，其架构针对不同硬件需求进行了定制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepmind.google/models/gemma/gemma-4/">Gemma 4 — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/gemma/docs/core">Gemma 4 model overview | Google AI for Developers</a></li>
<li><a href="https://pytorch.org/blog/quantization-aware-training/">Quantization-Aware Training for Large Language Models with PyTorch – PyTorch</a></li>

</ul>
</details>

**社区讨论**: 社区参与度很高，用户分享了在 Mac 上的实际部署示例，并将谷歌的 QAT 模型与 Unsloth 等第三方量化方案进行比较，后者据称能达到接近未量化 BF16 模型 100%的准确率。有人猜测这可能与苹果即将推出的 Siri 改进有关，也有人注意到 Gemma 生态系统发布节奏之快。

**标签**: `#quantization`, `#Gemma`, `#on-device AI`, `#model compression`, `#Google`

---

<a id="item-3"></a>
## [Claude-3.5 Sonnet 可能在 rsync 中引入错误](https://alexispurslane.github.io/rsync-analysis/) ⭐️ 8.0/10

对 rsync 提交的分析表明，Claude-3.5 Sonnet 这个大语言模型可能通过错误地将 malloc() 调用转换为 calloc() 而引入了错误，导致 rsync 工具出现内存问题。 这凸显了在关键开源开发中使用大语言模型的风险，因为微妙的错误可能通过审查，影响数百万用户的性能和可靠性。 该错误将有条件的 malloc() 改为无条件的 calloc()，强制对大内存分配进行清零，从而增加了内存使用并导致低内存系统故障。该提交后来被还原。

hackernews · logicprog · Jun 5, 12:43 · [社区讨论](https://news.ycombinator.com/item?id=48411635)

**背景**: rsync 是一个广泛使用的开源文件同步工具。calloc() 将分配的内存初始化为零，这更安全但比 malloc() 更慢且占用更多内存。大语言模型可能认为 calloc() 总是更好，而没有考虑性能权衡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/RsyncProject/rsync/issues/81">Memory increase in 3.2.2 · Issue #81 · RsyncProject/rsync</a></li>
<li><a href="https://www.anthropic.com/news/claude-3-5-sonnet">Introducing Claude 3.5 Sonnet \ Anthropic</a></li>
<li><a href="https://galileo.ai/blog/claude-3-5-sonnet-complete-guide-ai-capabilities-analysis">Claude 3.5 Sonnet Complete Guide: AI Capabilities & Limits | Galileo</a></li>

</ul>
</details>

**社区讨论**: 评论者就分析的统计方法进行了辩论，一些人指出统计效力不足和潜在的归属错误。其他人则注意到使用 AI 分析 AI 生成的代码错误具有讽刺意味。

**标签**: `#LLM`, `#code quality`, `#rsync`, `#open source`, `#AI safety`

---

<a id="item-4"></a>
## [开发者分享与生成式 AI 的‘糟糕’时刻](https://news.ycombinator.com/item?id=48406174) ⭐️ 8.0/10

Hacker News 上一个帖子询问开发者，生成式 AI 从新奇事物转变为强大、有时令人担忧的工具的那一刻，该帖子获得了 232 个点赞和 477 条评论，分享了个人轶事。 这次讨论凸显了生成式 AI 对软件工程的实际影响，包括细微错误、过度依赖和范式转变，强调了其变革潜力和风险。 评论揭示了具体的‘糟糕’时刻，例如几周后发现 LLM 生成的代码中存在细微错误，或者意识到本地模型能够以自信但不准确的方式回答复杂问题。

hackernews · andrehacker · Jun 4, 23:42

**背景**: 生成式 AI，包括 DALL-E 和 ChatGPT 等模型，最初以其创造性输出令人印象深刻，但常被视为有缺陷的新奇事物。随着时间的推移，LLM 发展到辅助编码，既带来了生产力提升，也带来了隐藏错误和过度依赖等新风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DALL-E">DALL - E - Wikipedia</a></li>
<li><a href="https://www.labellerr.com/blog/best-coding-llms/">5 Open-Source Coding LLMs You Can Run Locally in 2026</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了各种经历：有人指出 LLM 生成的代码中存在细微错误，几周后才显现；另一个人描述了在本地运行 Meta 泄露的模型，对其自信但不正确的回答感到震惊；还有一个人讲述了使用 LLM 进行复杂数据操作，后来发现错误。

**标签**: `#generative AI`, `#LLMs`, `#software engineering`, `#AI risks`, `#developer experience`

---

<a id="item-5"></a>
## [美国大型银行计划共建共享代币化存款网络](https://www.coindesk.com/markets/2026/06/05/jpmorgan-bank-of-america-and-citi-are-going-on-the-blockchain-offensive-with-a-shared-tokenized-network) ⭐️ 8.0/10

摩根大通、美国银行、花旗银行和富国银行正通过清算所共同建设一个共享代币化存款网络，目标是在 2027 年上半年推出。 这标志着美国大型银行在采用共享区块链基础设施进行资产结算方面迈出了重要一步，可能加速传统金融资产的代币化进程，并重塑银行业格局。 该网络将使用代币化存款对股票和国债等代币化资产进行实时结算，预计将于 2027 年初通过清算所推出。

rss · CoinDesk · Jun 5, 09:16

**背景**: 代币化存款是银行在区块链上的数字存款表示，可实现可编程的实时结算。华尔街公司多年来一直在探索区块链，例如摩根大通的代币化抵押品网络和 DTCC 的多链策略。这个共享网络旨在为代币化资产的银行间结算创建通用标准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.blockhead.co/2026/06/05/jp-morgan-citi-us-banks-plan-shared-tokenized-deposit-network-for-2027/">JP Morgan, Citi, US Banks Plan Shared Tokenized Deposit Network ...</a></li>
<li><a href="https://genfinity.io/2026/06/05/jpmorgan-citi-bofa-tokenized-deposit-network-2027/">JPMorgan, Citi, and Bank of America Plan Shared Tokenized Deposit...</a></li>
<li><a href="https://www.jpmorgan.com/kinexys/digital-assets/tokenized-collateral-network">Tokenized Collateral Network on Kinexys Digital Assets | J.P. Morgan</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#banking`, `#fintech`

---

<a id="item-6"></a>
## [Zcash 因 Orchard 严重漏洞暴跌 38%](https://www.coindesk.com/markets/2026/06/05/zcash-plummets-30-as-developer-reveals-a-major-bug-that-went-undetected-for-four-years) ⭐️ 8.0/10

Shielded Labs 披露了 Zcash 的 Orchard 屏蔽池中存在一个持续四年未被发现的严重伪造漏洞，导致 ZEC 价格暴跌 38%。 该漏洞可能允许无限量伪造 ZEC 且不被发现，破坏了 Zcash 的固定供应量以及用户对隐私币的信任。 该漏洞存在于 Orchard 电路的两行代码中，并在数天内被修复；专家认为实际被利用的可能性很低。

rss · CoinDesk · Jun 5, 05:43

**背景**: Zcash 是一种基于比特币代码库的隐私加密货币，总供应量固定为 2100 万枚。其 Orchard 屏蔽池是实现屏蔽交易的关键隐私组件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://coinpedia.org/price-analysis/zcash-orchard-vulnerability-is-fixed-but-a-trust-crisis-remains-as-supply-concerns-threaten-zec-recovery/">Zcash Orchard Vulnerability Is Fixed, but a Trust Crisis Remains as Supply Concerns Threaten ZEC Recovery</a></li>
<li><a href="https://decrypt.co/370105/zec-crashes-38-as-zcash-discloses-critical-counterfeiting-vulnerability">ZEC Crashes 38% as Zcash Discloses ‘Critical Counterfeiting ...</a></li>
<li><a href="https://news.bitcoin.com/zcash-orchard-counterfeiting-bug-patched/">Zcash Patches Critical Bug Enabling Unlimited Counterfeit ZEC...</a></li>

</ul>
</details>

**社区讨论**: Zcash 论坛上的社区讨论表达了对信任危机的担忧，并探讨了隐私与安全之间的权衡，不过许多人也认可了快速修复的做法。

**标签**: `#cryptocurrency`, `#security`, `#blockchain`, `#bug`, `#Zcash`

---

<a id="item-7"></a>
## [Anthropic 协助 NSA 网络攻击，同时呼吁暂停 AI](https://decrypt.co/370207/anthropic-helping-nsa-hack-china-also-wants-everyone-pause-ai) ⭐️ 8.0/10

Anthropic 已将大约六名工程师派驻美国国家安全局（NSA），部署其 Mythos AI 模型用于进攻性网络行动，同时发布报告警告 AI 可能很快在没有人类监督的情况下自行构建。 这揭示了 Anthropic 在 AI 安全公开立场上的明显矛盾，削弱了其倡导暂停 AI 的道德权威，并引发了关于 AI 双重用途性质的严重伦理和地缘政治担忧。 Mythos 模型专为网络安全任务设计，派驻的工程师正在帮助 NSA 将其用于进攻目的。Anthropic 的报告警告称，AI 可能很快能够自我改进并在没有人类干预的情况下运行，而该公司声称希望防止这种情况发生。

rss · Decrypt · Jun 5, 19:18

**背景**: Anthropic 是一家由前 OpenAI 员工创立的 AI 安全公司，以其 Claude 模型闻名。NSA 是美国负责信号情报和网络安全的间谍机构。进攻性网络行动涉及入侵对手系统，这与 Anthropic 宣称的开发安全、合乎道德的 AI 的使命形成对比。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/nsa-using-clause-mythos-for-offensive-cyber-operations-report-claims-says-half-a-dozen-anthropic-engineers-embedded-inside-the-agency">NSA using Claude Mythos for ' offensive cyber operations ,' report...</a></li>
<li><a href="https://digg.com/ai/1vgo2yxi">Anthropic embeds six engineers at the NSA to deploy its Mythos AI...</a></li>
<li><a href="https://cryptobriefing.com/anthropic-nsa-mythos-ai-cyber-operations/">Anthropic embeds engineers at NSA to deploy Mythos AI for cyber ...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#ethics`, `#cybersecurity`, `#Anthropic`, `#NSA`

---

<a id="item-8"></a>
## [Anthropic：AI 已能编写自身大部分代码](https://decrypt.co/370089/ai-already-developing-ai-anthropic-humans-slowing-things-down) ⭐️ 8.0/10

Anthropic 报告称，AI 系统现在能编写自身大部分代码并处理日益复杂的研究任务，人类主要负责选择要解决的问题。 这标志着向递归自我改进迈出了重要一步，AI 可以加速自身发展，可能超越人类监督，引发关键的安全问题。 这种转变意味着人类正越来越多地成为问题选择者而非解决者，如果人类决策成为瓶颈，可能会拖慢 AI 的进展。

rss · Decrypt · Jun 4, 21:37

**背景**: 递归自我改进指的是 AI 系统无需人类干预即可提升自身能力。领先的 AI 安全公司 Anthropic 一直在研究这一领域，指出完全的递归自我改进可能增加人类失去对 AI 系统控制的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/">Home \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/institute/recursive-self-improvement">Our progress toward recursive self - improvement , and its implications.</a></li>

</ul>
</details>

**标签**: `#AI`, `#Anthropic`, `#AI development`, `#automation`, `#AI safety`

---

<a id="item-9"></a>
## [太阳能海水淡化方法避免盐堵塞](https://www.rochester.edu/newscenter/what-is-desalination-definition-ocean-water-704732/) ⭐️ 7.0/10

罗切斯特大学的研究人员开发了一种太阳能驱动的海水淡化方法，利用毛细作用防止盐堵塞，但目前仍处于实验室规模。 这项创新可以通过提供更可持续的海水淡化工艺来解决水资源短缺问题，避免常见的盐积聚问题，从而可能降低维护和能源成本。 该系统使用特殊设计的黑色金属吸收阳光，并利用毛细作用将盐从活性区域移开，但去除积聚盐的机制尚待开发。

hackernews · speckx · Jun 5, 15:04 · [社区讨论](https://news.ycombinator.com/item?id=48413500)

**背景**: 海水淡化是从海水中去除盐分以生产淡水，但传统方法常因盐堵塞而降低效率并需要频繁维护。太阳能海水淡化利用阳光作为能源，使其更具可持续性。毛细作用是液体在狭窄空间中无需外力即可流动的能力，类似于水在植物茎中移动的方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Solar-powered_desalination_unit">Solar - powered desalination unit - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Capillary_action">Capillary action - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者指出该方法仍处于实验室规模，盐去除机制需要验证。一些人提出了能源效率方面的担忧，建议与太阳能电池板驱动传统海水淡化进行比较。其他人则提到了之前发布的类似文章。

**标签**: `#desalination`, `#water`, `#solar energy`, `#research`

---

<a id="item-10"></a>
## [英国政府将 Gov.uk Pay 支付服务从 Stripe 切换至 Adyen](https://www.theregister.com/public-sector/2026/06/04/govuk-goes-dutch-on-payments-as-it-dumps-stripe/5250763) ⭐️ 7.0/10

英国政府数字服务局（GDS）已将 Gov.uk Pay 的支付服务提供商从 Stripe 更换为荷兰支付公司 Adyen，理由是成本和战略考量。 此次更换凸显了英国政府在关键数字基础设施上追求成本效益和战略自主，可能影响欧洲其他公共部门的支付决策。 社区评论指出合同金额出奇地小，而 Adyen 以要求最低约 100 万欧元的交易量著称，这可能限制小型机构的接入。

hackernews · toomuchtodo · Jun 5, 16:55 · [社区讨论](https://news.ycombinator.com/item?id=48415217)

**背景**: Gov.uk Pay 是政府构建的在线支付服务，允许公共部门组织安全地收款。Stripe 和 Adyen 都是主要的支付处理商，但 Adyen 作为直接处理商，还支持实体店支付，而 Stripe 以其对开发者友好的工具和营销著称。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.adyen.com/press-and-media/adyen-payments-gov-uk">Adyen selected as payment services provider for GOV.UK Pay</a></li>
<li><a href="https://www.adyen.com/online-payments">Online payments | Making online payments easy - Adyen</a></li>
<li><a href="https://fitsmallbusiness.com/adyen-payments-review/">Adyen Review: Is It Right for Your Business?</a></li>

</ul>
</details>

**社区讨论**: 社区评论对合同金额之小表示惊讶，有人指出政府合同可能远小于企业云账单。还有人希望 Adyen 能有像 Stripe 那样好的营销，也有人称赞此举摆脱了“敌对的美国主义”，并建议将交易成本转嫁给用户以鼓励银行转账。

**标签**: `#fintech`, `#government`, `#payments`, `#Stripe`, `#Adyen`

---

<a id="item-11"></a>
## [适马 45mm 镜头拆解揭示现代维修挑战](https://salvagedcircuitry.com/sigma-45mm.html) ⭐️ 6.0/10

一篇关于适马 45mm 相机镜头的详细拆解与维修文章发布，展示了现代镜头结构的复杂性以及成功维修所需的技术。 此次拆解突显出现代镜头已演变为复杂的电子设备，使得业余爱好者和专业人士的维修难度增加，进而影响维修权运动和可持续性。 该镜头配备 USB-C 端口用于固件更新，维修过程涉及处理柔性排线、微小螺丝和表面贴装元件。作者指出，使用 JIS 螺丝刀对于避免螺丝滑丝至关重要。

hackernews · transistor-man · Jun 6, 00:33 · [社区讨论](https://news.ycombinator.com/item?id=48420148)

**背景**: 相机镜头已从简单的玻璃与金属组件演变为包含自动对焦马达、防抖系统和电子光圈控制的复杂系统。现代镜头通常包含固件和数字通信功能，类似于微型计算机。维修它们需要专用工具以及光学和电子学两方面的知识。

**社区讨论**: 评论者称赞这是他们见过的最好的拆解之一，并分享了关于保险丝（指出其用于防火而非保护元件）、JIS 与 PH 螺丝刀的重要性，以及现代镜头中 USB-C 端口和固件更新日益普及的趋势。

**标签**: `#camera lens`, `#repair`, `#teardown`, `#electronics`, `#hardware`

---

<a id="item-12"></a>
## [国际空间站宇航员因空气泄漏维修而避难](https://www.bbc.com/news/live/c4g44ew3g1kt) ⭐️ 6.0/10

国际空间站上的宇航员被指示就地避难约两小时，期间俄罗斯机组人员对星辰号服务舱转移通道（PrK）中持续存在的空气泄漏进行维修。NASA 随后暂停了维修工作以评估更多数据。 这一事件凸显了维护老化太空基础设施的持续挑战，以及泄漏检测和安全协议对机组人员生存的关键重要性。自 2019 年首次检测到的持续泄漏，强调了在 ISS 上需要强大的维修技术和应急计划。 泄漏位于俄罗斯轨道段的 PrK 通道，该通道连接星辰号模块与对接的航天器。尽管进行了多次维修尝试，空间站每天仍损失约一磅气压。NASA 的机器人外部泄漏定位器（RELL）使用质谱仪和离子真空压力计来外部检测氨泄漏。

hackernews · janpot · Jun 5, 15:00 · [社区讨论](https://news.ycombinator.com/item?id=48413464)

**背景**: 国际空间站（ISS）是一个位于近地轨道的模块化空间站，接待国际机组人员进行研究和维护。空气泄漏可能由微流星体撞击或材料退化引起，并通过压力传感器检测。PrK 通道是一个已知的问题区域，维修通常涉及涂抹密封剂并监测压力变化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.usatoday.com/story/graphics/2026/06/05/iss-air-leak-nasa-graphics/90419828007/">Visuals show how an ISS air leak forced astronauts to briefly shelter</a></li>
<li><a href="https://www.theguardian.com/science/live/2026/jun/05/international-space-station-astronauts-evacuation-air-leak-latest-news-updates">Nasa tells astronauts to return to International Space Station as air ...</a></li>
<li><a href="https://www.scientificamerican.com/article/astronauts-take-shelter-on-the-international-space-station-due-to-air-leaks/">Astronauts take shelter on the International Space Station due to air ...</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了 NASA 的 RELL 等泄漏检测技术，质疑如果模块之间存在气闸为何宇航员需要避难，并询问逃生舱的可用性。一些人对维修结果的表述感到困惑，而另一些人则提出了如粉刷模块等更简单的修复建议。

**标签**: `#ISS`, `#space`, `#engineering`, `#leak detection`

---

<a id="item-13"></a>
## [自定义 TDD 代理技能引发社区热议](https://www.saturnci.com/my-agent-skill-for-test-driven-development.html) ⭐️ 6.0/10

SaturnCI 上的一篇博客文章描述了一个用于测试驱动开发（TDD）的自定义代理技能，该技能指导 AI 编码代理遵循红-绿-重构循环。该技能旨在与 Claude Code、Cursor 和 Codex CLI 等工具配合使用。 这种方法旨在通过强制 AI 代理在实现之前编写测试来提高代码质量，但社区反馈凸显了实际权衡。这一讨论反映了理想 TDD 实践与 token 成本和测试幻觉等现实约束之间的广泛矛盾。 该技能可通过 PromptCreek 等仓库获得，并可通过单个 npx 命令安装。社区成员指出，TDD 可能会使 token 成本膨胀并降低开发速度，尤其是在多代理设置中，而且一些生成的测试可能是肤浅的幻觉。

hackernews · laxmena · Jun 4, 14:10 · [社区讨论](https://news.ycombinator.com/item?id=48398925)

**背景**: 测试驱动开发（TDD）是一种软件开发实践，要求在编写通过测试的代码之前先编写测试，遵循红-绿-重构循环。AI 代理技能是可重用的指令集，用于指导大型语言模型（LLM）一致地执行特定任务。将 TDD 编码为技能的概念旨在在 AI 辅助编码环境中自动化这一工作流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.promptcreek.com/skills/test-driven-development">Test Driven Development — Agent Skill | PromptCreek</a></li>
<li><a href="https://antigravity.codes/agent-skills/testing/test-driven-development">test - driven - development - Agent Skill for Claude Code, Cursor...</a></li>
<li><a href="https://www.aihero.dev/skills-tdd">tdd : Red, Green, Refactor for Agentic Coding</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了不同意见：一些人称赞这种结构化方法并分享自己的工作流程，而另一些人则警告 token 成本增加和测试幻觉。少数人认为 AGENTS.md 中的直接指令比专用技能更有效，并且 TDD 可能不适合所有代理开发场景。

**标签**: `#TDD`, `#AI agents`, `#software engineering`, `#LLM`

---

<a id="item-14"></a>
## [国会提出 7 项新的加密货币税收法案](https://decrypt.co/370197/congress-7-crypto-tax-bills) ⭐️ 6.0/10

美国国会提出了七项新的加密货币税收法案，这是首批由国会领导层审议的此类立法，众议院听证会定于周二举行。 这些法案可能显著影响美国加密货币的征税方式，从而影响加密生态系统中的投资者、开发者和企业。 这些法案涵盖加密货币税收的多个方面，包括报告要求、数字资产的税务处理以及小额交易的潜在豁免。

rss · Decrypt · Jun 5, 18:13

**背景**: 由于数字资产的去中心化和匿名性，加密货币税收一直是一个复杂的问题。美国政府一直在努力澄清加密交易的税收规则，这些法案是朝着正式化监管迈出的重要一步。

**标签**: `#cryptocurrency`, `#tax`, `#regulation`, `#policy`

---

<a id="item-15"></a>
## [英国少年因加密货币研究遭俄罗斯制裁](https://decrypt.co/370002/british-teen-sanctioned-russia-alleging-crypto-evade-sanctions) ⭐️ 6.0/10

俄罗斯对一名英国少年实施制裁，原因是他研究了俄罗斯涉嫌利用加密货币逃避国际制裁的行为。 这一事件凸显了围绕加密货币及其可能用于逃避制裁的地缘政治紧张局势日益加剧，表明即使是个人研究者也可能面临报复。 该少年的研究聚焦于俄罗斯涉嫌的非法加密货币流动，这引发了莫斯科的报复性制裁。制裁的具体细节或该少年的身份尚未披露。

rss · Decrypt · Jun 4, 14:27

**背景**: 加密货币可用于逃避制裁，因为交易不由商业银行处理且难以追踪。俄罗斯被指控使用加密货币绕过其在乌克兰入侵后遭受的西方制裁。多份报告记录了俄罗斯实体使用 Tether 等加密货币转移资金的情况。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.csis.org/analysis/cryptocurrencies-and-us-sanctions-evasion-implications-russia">Cryptocurrencies and U.S. Sanctions Evasion: Implications for Russia</a></li>
<li><a href="https://www.chainalysis.com/blog/russias-cryptocurrency-legislated-sanctions-evasion/">Russia ’s Cryptocurrency Pivot: Legislated Sanctions Evasion</a></li>
<li><a href="https://finintegrity.org/russian-use-of-crypto-sanctions-evasion-on-rise/">Russian Use of Crypto for Sanctions Evasion on the Rise</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#geopolitics`, `#sanctions`, `#blockchain`

---

<a id="item-16"></a>
## [摩根士丹利通过借贷实现实物加密货币 ETF 转换](https://www.theblock.co/post/403825/morgan-stanley-clients-lend-bitcoin-in-kind-spot-crypto-etf-conversions?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

摩根士丹利财富管理与 Galaxy Digital 合作，允许符合条件的客户借出比特币及其他加密货币，以换取加密 ETP 份额，从而实现实物现货加密 ETF 转换。 这项服务简化了机构投资者获取加密 ETF 敞口的流程，无需出售其持有的资产，可能提高加密市场的流动性和采用率。 该合作专注于实物转换，即客户直接借出加密资产以创建 ETF 份额，不同于美国现货比特币 ETF 使用的现金创建模式。

rss · The Block · Jun 5, 15:06

**背景**: 现货加密 ETF 允许投资者在不直接持有加密货币的情况下获得其敞口。实物创建涉及用基础资产交换 ETF 份额，相比现金创建可能更具税收效率和操作简便性。摩根士丹利是一家大型财富管理公司，Galaxy Digital 是一家加密金融服务公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/403825/morgan-stanley-clients-lend-bitcoin-in-kind-spot-crypto-etf-conversions">Morgan Stanley lets clients lend bitcoin and other assets for in - kind ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#institutional finance`, `#ETF`, `#Morgan Stanley`, `#Galaxy Digital`

---

<a id="item-17"></a>
## [多家大银行计划 2027 年推出代币化存款网络](https://www.theblock.co/post/403701/jpmorgan-citi-major-banks-tokenized-deposit-network?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

包括摩根大通和花旗在内的多家大银行组成的财团计划在 2027 年初推出代币化存款网络，实现代币化存款的即时和全天候结算。 这一举措可能通过提供受监管、由银行支持的数字支付方式来挑战稳定币，从而可能改变金融体系中资金的流动方式。 该网络将由财团拥有的私营支付公司 The Clearing House 运营，不同银行将其称为“桥梁”或“链”。

rss · The Block · Jun 5, 02:57

**背景**: 代币化存款是在区块链上表示为数字代币的传统银行存款，具有与传统存款相同的信用风险和监管待遇。与通常不受监管且由储备支持的稳定币不同，代币化存款将资金保留在银行体系内。该网络旨在提供即时结算，减少对较慢的传统清算系统的依赖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.pymnts.com/blockchain/2026/big-banks-launch-tokenized-deposit-network-to-fight-off-stablecoin-threat/">Big Banks Launch Tokenized Deposit Network to Fight Off Stablecoin Threat | PYMNTS.com</a></li>
<li><a href="https://www.coingabbar.com/en/crypto-currency-news/us-banks-tokenized-deposit-network-jpmorgan-citi-stablecoin">US Banks Launch Tokenized Deposit Network to Challenge Stablecoins</a></li>
<li><a href="https://www.theblock.co/post/403701/jpmorgan-citi-major-banks-tokenized-deposit-network">JPMorgan, Citi-backed consortium plans to launch tokenized deposit network in early 2027: WSJ | The Block</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#banking`, `#settlement`

---