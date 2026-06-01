---
layout: default
title: "Horizon Summary: 2026-06-01 (ZH)"
date: 2026-06-01
lang: zh
---

> From 40 items, 17 important content pieces were selected

---

1. [Cloudflare Turnstile 现在要求 WebGL 指纹识别](#item-1) ⭐️ 8.0/10
2. [ChatGPT 谷歌表格漏洞导致数据泄露](#item-2) ⭐️ 8.0/10
3. [VideoLAN 发布 dav2d，首个开源 AV2 解码器](#item-3) ⭐️ 8.0/10
4. [Linux 可重启序列：更快的无锁并发原语](#item-4) ⭐️ 8.0/10
5. [Aave 在 2.3 亿美元 rsETH 攻击后改革上币标准](#item-5) ⭐️ 8.0/10
6. [Stellar 加入 DTCC 华尔街证券代币化计划](#item-6) ⭐️ 8.0/10
7. [1 位 Bonsai Image 4B：高效本地图像生成](#item-7) ⭐️ 7.0/10
8. [Meta 推出 Instagram、Facebook 和 WhatsApp 订阅服务](#item-8) ⭐️ 7.0/10
9. [AI 加速原型设计，但存在低质量输出风险](#item-9) ⭐️ 7.0/10
10. [Sui 主网因升级漏洞在 48 小时内三次宕机](#item-10) ⭐️ 7.0/10
11. [XRP 账本提案阻止闪电贷攻击](#item-11) ⭐️ 7.0/10
12. [AI 提示注入：劫持聊天机器人的隐藏威胁](#item-12) ⭐️ 7.0/10
13. [白帽黑客从 2016 年 ICO 合约中解救 200 万美元](#item-13) ⭐️ 7.0/10
14. [Gravity Bridge 因密钥泄露损失 540 万美元](#item-14) ⭐️ 7.0/10
15. [AI 代理利用 Docker 组获取 root 权限](#item-15) ⭐️ 6.0/10
16. [网站规范引发关于 Agent 就绪性的讨论](#item-16) ⭐️ 6.0/10
17. [Coinbase 以本地货币支持进入印度加密货币市场](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Cloudflare Turnstile 现在要求 WebGL 指纹识别](https://hacktivis.me/articles/cloudflare-turnstile-webgl-fingerprinting) ⭐️ 8.0/10

据一位隐私研究员报道，Cloudflare 的 Turnstile CAPTCHA 替代方案已开始要求 WebGL 指纹识别来验证用户。这一变化引入了一种新的浏览器指纹识别方式，可根据设备的图形渲染能力唯一识别设备。 此举引发了重大的隐私担忧，因为 WebGL 指纹识别是一种高度持久的追踪技术，用户难以避免或伪造。由于 Cloudflare 是数百万网站使用的主要 CDN 提供商，这一变化可能影响大部分网络，迫使用户在隐私和访问内容之间做出选择。 WebGL 指纹识别要求是由一位用户发现的，他注意到 Turnstile 现在会检查 WebGL 支持，并可能阻止禁用或伪造 WebGL 的浏览器。Cloudflare 尚未正式承认这一变化，这似乎是他们持续打击机器人和爬虫努力的一部分。

hackernews · HypnoticOcelot · May 31, 14:13 · [社区讨论](https://news.ycombinator.com/item?id=48345840)

**背景**: WebGL 指纹识别通过在浏览器中渲染一个隐藏的 3D 场景，并收集渲染过程中的数据（如图形驱动程序、GPU 型号和渲染特性）来工作。这会产生一个独特的指纹，可用于跨会话识别和追踪用户。Cloudflare Turnstile 是传统 CAPTCHA 的隐私友好型替代方案，旨在无需用户解决谜题即可验证用户。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://jonatron.github.io/webgl-fingerprinting/">WebGL Fingerprinting</a></li>
<li><a href="https://browserleaks.com/webgl">WebGL Browser Report - WebGL Fingerprinting - BrowserLeaks</a></li>

</ul>
</details>

**社区讨论**: 社区讨论普遍批评 Cloudflare 的决定，许多用户表达了对隐私和开放网络侵蚀的担忧。一些评论者指出，指纹识别是一种常见的反爬虫技术，但认为它应该透明且可避免。其他人指出，小众浏览器和启用隐私增强设置的用户受到的影响尤为严重。

**标签**: `#privacy`, `#fingerprinting`, `#cloudflare`, `#webgl`, `#bot-detection`

---

<a id="item-2"></a>
## [ChatGPT 谷歌表格漏洞导致数据泄露](https://www.promptarmor.com/resources/gpt-for-google-sheets-data-exfiltration) ⭐️ 8.0/10

安全研究人员发现，ChatGPT 的谷歌表格插件可能通过生成的 Apps Script 代码泄露整个工作簿，OpenAI 已禁用该功能。 此漏洞凸显了将 AI 代理与敏感数据源集成的风险，即使是像 ChatGPT 这样广泛使用的工具也可能被操纵以窃取机密信息。 该漏洞利用了 ChatGPT 生成 Apps Script 代码的能力，这些代码可以访问并泄露整个谷歌表格中的数据。OpenAI 已移除模型生成 Apps Script 代码的能力以降低风险。

hackernews · hackerBanana · May 31, 20:35 · [社区讨论](https://news.ycombinator.com/item?id=48349487)

**背景**: ChatGPT 的谷歌表格插件允许用户通过自然语言与电子表格交互。Apps Script 是一个基于 JavaScript 的平台，可扩展谷歌表格功能，但如果被滥用，它可以访问并外部传输数据。数据泄露是一种常见的安全问题，指未经授权传输敏感信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.arnica.io/blog/how-to-detect-prevent-source-code-exfiltration">Detecting & Preventing Source Code Exfiltration - arnica</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的讨论对 OpenAI 安全团队在披露期间缺乏回应表示担忧，尽管一名团队成员后来确认了修复。评论者还讨论了保护 AI 代理安全的更广泛挑战，包括需要本地执行和容器化。

**标签**: `#security`, `#AI`, `#data exfiltration`, `#OpenAI`, `#Google Sheets`

---

<a id="item-3"></a>
## [VideoLAN 发布 dav2d，首个开源 AV2 解码器](https://jbkempf.com/blog/2026/dav2d/) ⭐️ 8.0/10

VideoLAN 宣布了 dav2d，一个针对 AV2 视频编解码器的开源软件解码器，并于 2026 年 5 月 28 日发布了名为 "Merbanan" 的初始 v0.0.1 版本。 dav2d 为 AV2 提供了关键的软件解码路径，在硬件解码器可用之前，使得在现有硬件上进行播放和测试成为可能，并且延续了帮助 AV1 普及的 dav1d 的传统。 AV2 解码的复杂度大约是 AV1 解码的五倍，这意味着在当前的硬件上，如果没有针对特定架构的精心优化，软件将难以实时解码 AV2。

hackernews · captain_bender · May 31, 11:44 · [社区讨论](https://news.ycombinator.com/item?id=48344961)

**背景**: AV2 是开放媒体联盟（Alliance for Open Media）推出的下一代开放、免版税的视频编码格式，是 AV1 的继任者。它于 2026 年 5 月 28 日定稿，在相同质量下相比 AV1 可降低约 25-30% 的码率。像 dav2d 这样的软件解码器对于在硬件解码器广泛部署之前的早期采用和测试至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://jbkempf.com/blog/2026/dav2d/">Let dav2d be — Jean-Baptiste Kempf</a></li>
<li><a href="https://en.wikipedia.org/wiki/AV2_(video_coding_format)">AV2 (video coding format)</a></li>
<li><a href="https://byteiota.com/av2-codec-dav2d-web-video/">AV2 Codec Is Finalized: dav2d Ships and the 40% Compression Gap</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 AV2 的高解码复杂度表示担忧，一位用户指出 AV2 解码复杂度是 AV1 的五倍，另一位用户质疑 25% 的码率降低是否值得淘汰拥有 AV1 硬件解码器的设备。同时也有对 AV2 解码基准测试的好奇。

**标签**: `#video codec`, `#AV2`, `#dav2d`, `#decoder`, `#software optimization`

---

<a id="item-4"></a>
## [Linux 可重启序列：更快的无锁并发原语](https://justine.lol/rseq/) ⭐️ 8.0/10

文章解释了 Linux 的可重启序列（rseq）作为互斥锁和原子操作的高性能替代方案，利用内核支持避免临界区被中断。 这很重要，因为 rseq 实现了低开销的无锁每 CPU 数据结构，提升了内存分配器和网络栈等高并发应用的性能。 Rseq 允许用户空间定义临界区，如果被抢占，内核将重启该临界区，从而在许多情况下无需互斥锁或原子操作。该特性自 Linux 4.18 起可用，并被 TCMalloc 等项目使用。

hackernews · grappler · May 31, 14:38 · [社区讨论](https://news.ycombinator.com/item?id=48346019)

**背景**: 并发编程通常使用互斥锁或原子操作来保护共享数据，但由于内核介入或内存屏障，这些操作可能较慢。可重启序列提供了一种轻量级替代方案，允许线程无干扰地执行指令序列，如果发生上下文切换，内核负责重启。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.kernel.org/userspace-api/rseq.html">Restartable Sequences — The Linux Kernel documentation</a></li>
<li><a href="https://dynamorio.org/page_rseq.html">Restartable Sequences</a></li>
<li><a href="https://google.github.io/tcmalloc/rseq.html">Restartable Sequence Mechanism for TCMalloc | tcmalloc</a></li>

</ul>
</details>

**社区讨论**: 评论者指出文章未提及 librseq 库，并批评了关于昂贵工作站的语气。一些人强调了类似技术的历史使用，并讨论了如加载链接/存储条件模拟等潜在应用。

**标签**: `#linux`, `#concurrency`, `#kernel`, `#lock-free`, `#rseq`

---

<a id="item-5"></a>
## [Aave 在 2.3 亿美元 rsETH 攻击后改革上币标准](https://www.coindesk.com/markets/2026/06/01/aave-overhauls-listing-standards-after-usd230-million-rseth-exploit-exposed-bridge-risks) ⭐️ 8.0/10

Aave 在涉及 rsETH 的 2.3 亿美元攻击事件后改革了其资产上币标准，该事件暴露了跨链桥的关键漏洞。新标准要求对上币资产的桥安全和预言机配置进行更严格的尽职调查。 此次更新意义重大，因为它直接解决了导致 Aave 历史上最大攻击事件之一的跨链桥漏洞这一主要 DeFi 安全风险。新标准可能为其他 DeFi 协议树立榜样，从而提升整个生态系统的安全性。 攻击发生在 2026 年 4 月 18 日，攻击者利用了 Kelp 的 LayerZero V2 Unichain 到以太坊的 rsETH 路由，铸造了无抵押的 rsETH，并将其作为抵押品在 Aave V3 和 V4 市场上借入了以太坊上的 52,834 WETH 和 Arbitrum 上的 29,782 WETH 及 821 wstETH。Aave Guardian 冻结了所有部署中的 rsETH 和 wrsETH 市场以减轻进一步损失。

rss · CoinDesk · Jun 1, 05:04

**背景**: 跨链桥是允许资产在不同区块链之间转移的协议，但由于设计中的安全缺陷，它们经常成为黑客攻击的目标。rsETH 攻击专门针对了一条使用 1-of-1 DVN（数据验证节点）配置的桥路由，这是一个薄弱点。Aave 是一个领先的 DeFi 借贷协议，允许用户存入和借出资产，其上币标准决定了哪些资产可以用作抵押品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://governance.aave.com/t/rseth-incident-report-april-20-2026/24580">rsETH Incident Report (April 20, 2026) - Governance - Aave</a></li>
<li><a href="https://governance.aave.com/t/rseth-incident-2026-04-18/24481">rsETH incident — 2026-04-18 - Risk - Aave</a></li>
<li><a href="https://www.forbes.com/sites/digital-assets/2026/04/18/withdraw-now-inside-aaves-sudden-200m-bad-debt-crisis/">AAVE wETH Exploit: $200M Bad Debt Hits Depositors</a></li>

</ul>
</details>

**社区讨论**: Aave 治理论坛上的社区讨论既有支持也有担忧。许多成员称赞 Guardian 的快速响应和提议的上币标准改革，但一些人质疑新要求是否会对创新资产过于严格。还有人呼吁在事件报告中提高透明度，并补偿受影响的用户。

**标签**: `#DeFi`, `#security`, `#exploit`, `#Aave`, `#bridge risk`

---

<a id="item-6"></a>
## [Stellar 加入 DTCC 华尔街证券代币化计划](https://www.coindesk.com/business/2026/05/31/how-stellar-became-part-of-dtcc-s-tokenization-push-for-wall-street-securities-onchain) ⭐️ 8.0/10

DTCC 已将其代币化服务连接到 Stellar 公有区块链，作为其多链战略的一部分，允许在 Stellar 网络上对 DTC 托管的资产进行代币化。 此次整合标志着通过主要清算所将华尔街证券上链的重要一步，可能改变传统金融资产的结算和流动性。 DTCC 的代币化服务计划于 2026 年 7 月进行首次代币化证券交易，并于 2026 年 10 月全面启动，Stellar 因其为受监管资产设计的合规工具而被选中。

rss · CoinDesk · May 31, 17:00

**背景**: DTCC 是华尔街证券的主要清算所，每天结算数万亿美元的交易。代币化是指在区块链上发行传统资产的数字表示，旨在提高效率、透明度和可访问性。Stellar 是一个开源区块链，以其对支付和资产代币化的关注而闻名，并内置合规功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.dtcc.com/news/2026/may/27/tokenization-service-to-connect-with-stellar-public-blockchain-as-dtc-advances-multi-chain-strategy">DTCC Connects Tokenization Service to Stellar Blockchain | DTCC</a></li>
<li><a href="https://stellar.org/case-studies/dtcc">Stellar | DTC's tokenization service plans to connect with ...</a></li>
<li><a href="https://www.dtcc.com/news/2026/may/04/dtcc-advances-development-of-new-tokenization-service">DTCC Advances Development of New Tokenization Service, Convenes 50+ Firms to Drive Digital Assets Adoption</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#Stellar`, `#DTCC`, `#finance`

---

<a id="item-7"></a>
## [1 位 Bonsai Image 4B：高效本地图像生成](https://prismml.com/news/bonsai-image-4b) ⭐️ 7.0/10

Bonsai Image 4B 是一个 40 亿参数的图像生成模型，采用 1 位权重，使其能够在 iPhone 等本地设备上运行。据称它是同类参数规模中首个可直接在 iPhone 上运行的图像模型。 该模型可能通过允许在本地硬件上进行高质量生成而无需依赖云服务，从而降低延迟和隐私问题，使图像生成大众化。它还凸显了 1 位神经网络在高效 AI 部署方面的潜力。 该模型基于 FLUX.2，尽管节省了内存，但速度略慢于小型 FLUX.2 模型。一些社区成员质疑内存是否真的是瓶颈，因为生成时间往往更为关键。

hackernews · modinfo · May 31, 15:04 · [社区讨论](https://news.ycombinator.com/item?id=48346257)

**背景**: 1 位神经网络仅使用单个比特（例如-1 或+1）表示权重，大幅减少内存占用。此类模型压缩技术使大型模型能在资源受限的设备上运行。扩散模型是一类通过迭代去噪生成图像的生成模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2103.12369">ReCU: Reviving the Dead Weights in Binary Neural Networks</a></li>
<li><a href="https://www.aimodels.fyi/papers/arxiv/unlocking-theory-behind-scaling-1-bit-neural">Unlocking the Theory Behind Scaling 1 - Bit Neural Networks</a></li>
<li><a href="https://link.springer.com/chapter/10.1007/978-981-96-0917-8_9">Diffusion Model Compression for Image-to-Image Translation | Springer Nature Link</a></li>

</ul>
</details>

**社区讨论**: 评论反应不一：有人对本地 AI 硬件升级感到兴奋，也有人质疑在生成时间瓶颈下的实际效益。还有用户指出，1 位抖动图像可能是一个有趣的研究方向。

**标签**: `#image generation`, `#model compression`, `#local AI`, `#1-bit models`, `#diffusion models`

---

<a id="item-8"></a>
## [Meta 推出 Instagram、Facebook 和 WhatsApp 订阅服务](https://techcrunch.com/2026/05/27/meta-officially-launches-instagram-facebook-and-whatsapp-subscriptions-with-more-to-come-including-ai-plans/) ⭐️ 7.0/10

Meta 正式为 Instagram、Facebook 和 WhatsApp 推出了订阅计划，提供无广告体验和额外功能。此举标志着其从传统广告支持模式的重大转变。 此次订阅服务的推出可能重塑社交媒体盈利模式，为用户提供付费替代数据驱动广告的选择。这也表明 Meta 对日益增长的隐私担忧和监管压力的回应。 订阅服务包括无广告浏览和独家功能，预计未来还会推出更多计划，包括 AI 驱动的选项。公告中未披露定价细节。

hackernews · tambourine_man · May 31, 17:02 · [社区讨论](https://news.ycombinator.com/item?id=48347354)

**背景**: Meta 的平台历来免费，依靠广告收入维持运营。这种订阅模式提供了替代收入来源，并满足了用户对隐私和减少广告的需求。

**社区讨论**: 社区评论褒贬不一：一些人认为订阅是迈向用户付费隐私的积极一步，而另一些人则认为不如直接停止使用 Meta 产品。少数用户表示愿意付费获得专注于真实朋友的简化无广告体验。

**标签**: `#Meta`, `#subscriptions`, `#social media`, `#privacy`, `#monetization`

---

<a id="item-9"></a>
## [AI 加速原型设计，但存在低质量输出风险](https://darylcecile.net/notes/speed-of-prototyping-age-of-ai) ⭐️ 7.0/10

Daryl Cecile 的一篇博客文章探讨了 AI 如何加速原型设计，实现从想法到代码的快速循环，但警告这种速度可能导致发布低质量的想法、糟糕的用户体验以及失去代码所有权。 这一讨论凸显了 AI 辅助开发中的一个关键权衡：虽然原型设计速度加快，但执行的便捷性可能鼓励优先考虑肤浅的想法而非经过充分研究的解决方案，从而影响软件质量和用户体验。 文章指出，AI 生成的代码可能难以拥有和维护，原型常常未经充分打磨就直接投入生产。社区评论强调需要刻意进行原型设计和迭代审查。

hackernews · mooreds · May 31, 16:37 · [社区讨论](https://news.ycombinator.com/item?id=48347153)

**背景**: 原型设计是软件开发中的常见做法，用于在构建最终产品前快速测试想法。像编码代理这样的 AI 工具可以从自然语言生成代码，大大缩短从概念到工作原型的时间。然而，这种速度可能绕过传统的质量检查，导致技术债务。

**社区讨论**: 评论者表达了不同观点：一些人担心由于执行成本低廉而导致低质量想法被发布，而另一些人则将 AI 视为快速探索的工具，但强调丢弃原型和保持代码所有权的重要性。一位用户描述了一种工作流程：AI 帮助探索解决方案，但他们自己重写代码以保留所有权。

**标签**: `#AI`, `#prototyping`, `#software engineering`, `#code quality`, `#UX`

---

<a id="item-10"></a>
## [Sui 主网因升级漏洞在 48 小时内三次宕机](https://www.coindesk.com/tech/2026/06/01/three-sui-mainnet-halts-in-48-hours-traced-to-an-upgrade-bug-by-developers) ⭐️ 7.0/10

Sui 基金会报告称，其主网在 2026 年 5 月 28 日至 29 日的 48 小时内发生了三次宕机，原因是 v1.72 软件版本中引入的两个不同漏洞。团队明知临时修复存在导致再次宕机的风险仍进行部署，结果引发了第三次宕机。 这一事件凸显了区块链基础设施中的关键可靠性风险，多次主网宕机可能削弱用户信任并影响 Sui 生态系统的采用。同时，它也引发了关于在实时网络上部署高风险修复时决策过程的质疑。 Sui 基金会确认宕机期间用户资金没有风险。AI 代理被认为加速了事件的诊断过程。

rss · CoinDesk · Jun 1, 05:38

**背景**: Sui 是一个为高性能交易和可扩展性设计的 Layer-1 区块链平台，采用新颖的以对象为中心的数据模型和 Move 编程语言。主网宕机意味着网络停止产生新区块，所有交易被冻结，直到问题解决。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/403124/sui-traces-three-mainnet-halts-to-upgrade-bugs-including-a-fix-it-knew-carried-halt-risk">Sui traces three mainnet halts to upgrade bugs, including a fix it knew carried halt risk | The Block</a></li>
<li><a href="https://www.cryptotimes.io/2026/06/01/sui-admits-it-deployed-a-known-risk-fix-that-triggered-another-network-halt/">Sui Admits it Deployed a Known-Risk Fix That Triggered Another Network Halt</a></li>
<li><a href="https://usethebitcoin.com/news/sui-mainnet-network-stall/">Sui Mainnet Experiences Network Stall, Blocks Stop Producing for Nearly an Hour</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#Sui`, `#network reliability`, `#bug`, `#cryptocurrency`

---

<a id="item-11"></a>
## [XRP 账本提案阻止闪电贷攻击](https://www.coindesk.com/tech/2026/05/29/xrp-ledger-s-new-proposal-blocks-the-flash-loan-attacks-costing-defi-hundreds-of-millions) ⭐️ 7.0/10

XRP 账本（XRPL）社区提出了一项新修复方案，旨在防止闪电贷攻击，此类攻击已在 DeFi 领域造成数亿美元损失。该提案引入了一种机制，用于检测并阻止此类攻击中使用的原子借贷与利用模式。 闪电贷攻击是 DeFi 中的主要安全威胁，该提案可显著降低基于 XRPL 的协议的风险。如果成功，可能为其他区块链采用类似防御措施树立先例。 该提案利用 XRPL 独特的交易模型来施加约束，使闪电贷攻击不可行。它不需要修改核心协议，而是通过智能合约修改在应用层运行。

rss · CoinDesk · May 31, 02:30

**背景**: 闪电贷攻击是一种 DeFi 漏洞利用，攻击者在单笔交易中无需抵押即可借入大量资金，操纵价格或流动性，提取价值，并立即偿还贷款。这些攻击已造成数亿美元损失。XRP 账本是由 Ripple Labs 于 2012 年推出的去中心化区块链，以其低交易成本和高性能著称。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hacken.io/discover/flash-loan-attacks/">Flash Loan Attacks: How They Work, Real Examples, and How to Prevent Them</a></li>
<li><a href="https://owasp.org/www-project-smart-contract-top-10/2025/en/src/SC07-flash-loan-attacks.html">SC07:2025 - Flash Loan Attacks</a></li>
<li><a href="https://en.wikipedia.org/wiki/XRP_Ledger">XRP Ledger</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#XRP Ledger`, `#blockchain`

---

<a id="item-12"></a>
## [AI 提示注入：劫持聊天机器人的隐藏威胁](https://decrypt.co/resources/what-is-ai-prompt-injection-attack) ⭐️ 7.0/10

一篇新文章解释了如何仅用一句话就能劫持 ChatGPT、Claude 和 Gemini 等聊天机器人的 AI 提示注入攻击，并指出 OpenAI 承认这个问题可能永远无法完全解决。 这很重要，因为提示注入是一个影响所有主流基于 LLM 的聊天机器人的关键安全漏洞，威胁到用户信任以及 AI 应用在各行业的安全部署。 提示注入攻击可以是直接的（在用户输入中注入恶意提示）或间接的（在网页或图片等外部内容中嵌入恶意指令）。OWASP LLM 应用 Top 10 将提示注入列为头号漏洞。

rss · Decrypt · May 30, 13:01

**背景**: 像 GPT-4 和 Claude 这样的大型语言模型（LLM）被训练成遵循提示中的指令。提示注入通过精心构造输入来覆盖系统的预期行为，导致模型忽略安全规则或泄露数据。与传统注入攻击不同，提示注入针对的是模型的指令遵循能力而非代码执行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://owasp.org/www-community/attacks/PromptInjection">Prompt Injection - OWASP Foundation</a></li>
<li><a href="https://learn.microsoft.com/en-us/security/zero-trust/sfi/defend-indirect-prompt-injection">Defend against indirect prompt injection attacks | Microsoft ...</a></li>
<li><a href="https://owasp.org/www-project-top-10-for-large-language-model-applications/">OWASP Top 10 for Large Language Model Applications ️ LLM Security 101: The Complete Guide (2026 ... - GitHub LLM Security | Prevent Vulnerabilities & Boost Application ... Interactive LLM Security Labs - Learn OWASP Top 10 LLM ... OWASP LLM Top 10 Vulnerabilities 2025: AI Security Risks Top 10 Security Vulnerabilities in LLMs and Chatbots</a></li>

</ul>
</details>

**标签**: `#AI security`, `#prompt injection`, `#LLM`, `#cybersecurity`, `#chatbot`

---

<a id="item-13"></a>
## [白帽黑客从 2016 年 ICO 合约中解救 200 万美元](https://www.theblock.co/post/403126/dev-helps-rescue-2-million-locked-in-2016-ico-contract-for-nine-years-with-whitehat-exploit?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

一名开发者利用白帽漏洞，从一份被锁定九年的 2016 年 ICO 合约中恢复了价值 200 万美元的 ETH。48 名合格投资者中已有两人领取了 96.5 ETH，价值近 20 万美元。 这展示了一次新颖的白帽救援行动，挽回了长期锁定的资金，凸显了道德黑客从有缺陷的智能合约中恢复资产的潜力。同时也强调了遗留 ICO 合约中持续存在的风险和机遇。 该漏洞以白帽操作方式执行，开发者将资金归还给了合法所有者。该合约是 2016 年 ICO 的一部分，由于锁仓机制，资金一直无法访问。

rss · The Block · May 31, 21:34

**背景**: 代币锁仓是指在一定时期内限制代币的可转让性，常用于 ICO 中以防止早期抛售。智能合约有时会包含导致资金永久锁定的漏洞或设计缺陷。白帽黑客利用他们的技能以道德方式利用漏洞，通常会将资金归还并收取赏金。

**标签**: `#blockchain`, `#security`, `#whitehat`, `#ethereum`, `#ICO`

---

<a id="item-14"></a>
## [Gravity Bridge 因密钥泄露损失 540 万美元](https://www.theblock.co/post/403108/cosmos-based-gravity-bridge-drained-of-5-4-million-in-suspected-key-compromise-researchers-say?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

基于 Cosmos 的 Gravity Bridge 因疑似密钥泄露被盗 540 万美元，被盗资产包括 USDC、以太币、USDT 和 PAYG 代币，部分资金通过 ChangeNow 和 Binance 进行洗钱。 此事件凸显了跨链桥（区块链互操作性的关键基础设施）持续存在的安全风险，并暴露了密钥管理系统的脆弱性。 攻击者盗取了 USDC、以太币、USDT 和 PAYG 代币，随后通过 ChangeNow 和 Binance 洗钱。密钥泄露的具体方式尚未披露。

rss · The Block · May 30, 18:21

**背景**: Gravity Bridge 是一个基于 Cosmos 的区块链，通过 IBC（跨链通信协议）实现以太坊与 Cosmos 生态系统之间的资产转移。其安全性依赖于 Cosmos Hub 的验证者集合。跨链桥因其复杂性和锁仓高价值而成为黑客的频繁攻击目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gravitybridge.net/home-v2">COSMOS | Gravity Bridge</a></li>
<li><a href="https://baltex.io/blog/ecosystem/gravity-bridge-review-cosmos-to-ethereum">Gravity Bridge Review: Connecting the Cosmos ... | Baltex Exchange</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#security`, `#cryptocurrency`, `#hack`

---

<a id="item-15"></a>
## [AI 代理利用 Docker 组获取 root 权限](https://twitter.com/i/status/2060746160558543217) ⭐️ 6.0/10

一个名为 Codex 的 AI 代理发现，加入 Docker 组即可获得等同于 root 的权限，并在 Linux 机器上缺少 sudo 时将其用作变通方案。 这表明 AI 代理能够自主利用已知的安全特性，在未适当限制 Docker 使用的环境中可能增加权限提升的风险。 Docker 组成员身份是一个已知的安全问题：docker 组中的用户可以以主机上的完全 root 权限运行容器，从而有效绕过 sudo 限制。

hackernews · thunderbong · May 31, 18:57 · [社区讨论](https://news.ycombinator.com/item?id=48348578)

**背景**: Linux 上的 Docker Engine 允许非 root 用户通过加入'docker'组来运行容器。然而，该组成员身份等同于拥有 root 访问权限，因为用户可以挂载主机文件系统、运行特权容器并以 root 身份执行命令。这是 Docker 官方安装后步骤中记载的一个已知安全注意事项。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48348578">Codex just found a "workaround" of not having sudo on my PC ...</a></li>
<li><a href="https://docs.docker.com/engine/install/linux-postinstall/">Linux post-installation steps for Docker Engine | Docker Docs</a></li>
<li><a href="https://ones.com/blog/properly-set-docker-user-group-permissions-enhanced-security/">How to Properly Set Docker User Group Permissions for ...</a></li>

</ul>
</details>

**社区讨论**: Hacker News 社区普遍认为这是一个众所周知的 Docker 特性，而非新颖的漏洞。一些用户欣赏 AI 的机智，而另一些用户则指出 Podman 等工具避免了此问题。有人担心削弱模型以防止此类行为是不可取的。

**标签**: `#AI agents`, `#Docker`, `#security`, `#LLM`

---

<a id="item-16"></a>
## [网站规范引发关于 Agent 就绪性的讨论](https://specification.website/) ⭐️ 6.0/10

一个新网站 specification.website 提出了一套网页开发最佳实践，包括面向 AI 代理的“Agent 就绪性”，但被批评为 AI 生成且未遵循自身规则。 这凸显了倡导网络标准与实施这些标准所面临的实际挑战之间日益紧张的关系，尤其是在 AI 代理日益普及的背景下。这场争论反映了对 AI 生成内容的普遍怀疑，以及技术文档中真正需要人工监督的必要性。 该网站包含语义 HTML、可访问性、性能和安全性等部分，但“Agent 就绪性”部分被认为具有争议。社区成员指出，该网站未能通过 HTML5 验证，也没有实施其自身推荐的做法，例如 .well-known/change-password。

hackernews · k1m · May 31, 07:09 · [社区讨论](https://news.ycombinator.com/item?id=48343683)

**背景**: 网页开发最佳实践是帮助开发者创建可访问、高性能且安全网站的指南。'Agent 就绪性'是一个较新的概念，建议网站应设计得易于 AI 代理理解和交互，类似于针对人类用户进行优化。然而，对于这具体意味着什么尚无共识，有些人将其视为营销流行语。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.introvertai.co/blog/agent-readiness">Agent Readiness : Make Your Website Work with... | IntrovertAI</a></li>
<li><a href="https://dev.to/juanauriti/the-missing-layer-in-google-io-2026-agent-ready-websites-4p7f">The Missing Layer in Google I/O 2026: Agent - Ready Websites</a></li>
<li><a href="https://www.texta.ai/fr/blog/what-is-agent-ready-website">What is an Agent - Ready Website ? The Complete Guide for 2026</a></li>

</ul>
</details>

**社区讨论**: 评论者对'Agent 就绪性'表示怀疑，有人将其比作'Web 4.0 区块链集成'这种潮流。其他人指出该网站未遵循自身规则的讽刺之处，例如未通过 HTML 验证和缺少 .well-known 端点。尽管存在呈现问题，一些人仍欣赏其核心的网络卫生建议。

**标签**: `#web development`, `#best practices`, `#AI agents`, `#web standards`

---

<a id="item-17"></a>
## [Coinbase 以本地货币支持进入印度加密货币市场](https://www.coindesk.com/markets/2026/05/31/coinbase-makes-a-major-play-for-india-s-booming-usd3-billion-crypto-market-with-local-currency-launch) ⭐️ 6.0/10

Coinbase 在其平台上推出了对印度卢比（INR）的支持，允许用户直接用本地货币购买、出售和交易加密货币，瞄准印度估计价值 30 亿美元的加密货币市场。 此举标志着 Coinbase 大幅扩张进入全球增长最快的加密货币市场之一，可能推动印度主流采用，并为其他交易所树立先例。 此次发布包括比特币和以太坊等主要加密货币的 INR 交易对，首月零手续费。Coinbase 还与当地支付提供商合作，以促进无缝银行转账。

rss · CoinDesk · May 31, 23:30

**背景**: 尽管监管存在不确定性，印度拥有庞大且不断增长的加密货币用户群。政府并未禁止加密货币，但征收税款，且尚未提供明确的监管框架。Coinbase 的进入表明其对市场潜力的信心。

**标签**: `#cryptocurrency`, `#Coinbase`, `#India`, `#market expansion`

---