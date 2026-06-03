---
layout: default
title: "Horizon Summary: 2026-06-03 (ZH)"
date: 2026-06-03
lang: zh
---

> From 92 items, 21 important content pieces were selected

---

1. [VSCode 漏洞实现一键窃取 GitHub 令牌](#item-1) ⭐️ 9.0/10
2. [RAG 中经济高效的图像索引方法](#item-2) ⭐️ 8.0/10
3. [Anthropic 提交 IPO 申请，估值接近万亿美元](#item-3) ⭐️ 8.0/10
4. [微软发布 137B 参数编程模型 MAI-Code-1-Flash](#item-4) ⭐️ 7.0/10
5. [CT 扫描揭示比亚迪汽车零部件的高制造质量](#item-5) ⭐️ 7.0/10
6. [斯坦福研究：AI 击败法学教授](#item-6) ⭐️ 7.0/10
7. [HP 重新发布经典 HP-16C 程序员计算器](#item-7) ⭐️ 7.0/10
8. [Hyperliquid 在传统交易所开盘前预测了 80%的油价波动](#item-8) ⭐️ 7.0/10
9. [微软发布可靠性提升千倍的量子芯片，引发比特币安全担忧](#item-9) ⭐️ 7.0/10
10. [微软将 OpenClaw 转化为企业 AI 代理 Scout](#item-10) ⭐️ 7.0/10
11. [英伟达 Nemotron 3 Ultra：美国最佳开源模型，仍落后中国](#item-11) ⭐️ 7.0/10
12. [DuckDuckGo 的“无 AI”功能受欢迎](#item-12) ⭐️ 7.0/10
13. [在 Linux 上将 Nvidia GPU 显存用作交换空间](#item-13) ⭐️ 6.0/10
14. [开发者分享使用 Clojure 一个月的体验](#item-14) ⭐️ 6.0/10
15. [美国财政部制裁伊朗加密货币交易所 Nobitex](#item-15) ⭐️ 6.0/10
16. [特朗普签署 AI 行政令，建立自愿审查框架](#item-16) ⭐️ 6.0/10
17. [比特币矿商 Hive 收入激增，押注 AI 热潮](#item-17) ⭐️ 6.0/10
18. [佛罗里达州起诉 OpenAI 及 Sam Altman，指控 ChatGPT 安全声明不实](#item-18) ⭐️ 6.0/10
19. [白帽黑客帮助找回 2016 年 ICO 中卡住的 200 万美元 ETH](#item-19) ⭐️ 6.0/10
20. [Galaxy Digital 为机构推出场外预测市场交易](#item-20) ⭐️ 6.0/10
21. [Backpack 推出混合证券平台](#item-21) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [VSCode 漏洞实现一键窃取 GitHub 令牌](https://blog.ammaraskar.com/github-token-stealing/) ⭐️ 9.0/10

安全研究员 Ammar Askar 在一份详细的漏洞利用报告中指出，VSCode 嵌入式 Web 编辑器存在一个严重漏洞，恶意扩展程序只需一次点击即可窃取用户的 GitHub 身份验证令牌。 该漏洞为数百万使用 VSCode Web 编辑器的开发者暴露了巨大的攻击面，可能导致私有仓库被未授权访问以及供应链攻击。同时，它也凸显了在保护集成开发环境免受恶意扩展攻击方面持续存在的挑战。 该漏洞利用通过使用不受发布者审查限制的本地工作区扩展，绕过了 VSCode 的发布者信任系统，并通过绑定快捷键来安装未经发布者检查的扩展，从而规避了内容安全策略（CSP）的限制。研究人员向微软安全响应中心（MSRC）报告了该漏洞，但称体验“糟糕”，漏洞被悄悄修复而未得到适当认可。

hackernews · ammar2 · Jun 2, 15:29 · [社区讨论](https://news.ycombinator.com/item?id=48371562)

**背景**: VSCode 是一款流行的代码编辑器，拥有丰富的扩展生态系统。其 Web 编辑器版本在浏览器中运行，通常登录 GitHub 以实现无缝集成。扩展可以从市场或本地安装，安全检查级别不同。GitHub 令牌可授予对仓库的访问权限，是攻击者的高价值目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://code.visualstudio.com/docs/configure/extensions/extension-runtime-security">Extension runtime security - Visual Studio Code</a></li>
<li><a href="https://blog.palantir.com/managing-and-securing-vs-code-extensions-at-scale-b75b2cf72b02">Managing and Securing VS Code Extensions at Scale</a></li>
<li><a href="https://blog.gitguardian.com/how-hackers-used-stolen-github-oauth-tokens/">How Hackers Used Stolen GitHub Tokens to Access Private Source Code</a></li>

</ul>
</details>

**社区讨论**: 社区讨论中对 MSRC 处理报告的方式表示不满，有评论者指出 MSRC“已经意识到研究人员无论如何都会免费报告”。另一位用户分享了令牌被盗的个人经历，强调了隔离损害和假设令牌最终会泄露的重要性。一位技术评论者寻求对漏洞利用链的澄清，特别是快捷键技巧如何绕过 CSP。

**标签**: `#security`, `#vscode`, `#github`, `#vulnerability`, `#token-theft`

---

<a id="item-2"></a>
## [RAG 中经济高效的图像索引方法](https://www.kapa.ai/blog/how-we-index-images-for-rag) ⭐️ 8.0/10

Kapa.ai 提出在索引阶段使用廉价视觉模型生成文本描述来索引图像，而不是在查询阶段使用多模态模型。 这种方法显著降低了查询时的延迟和成本，使 RAG 系统在包含大量图像的应用中更加实用。 该方法将图像描述存储为文本块，使得在查询时无需将图像发送给模型即可与普通文本一起检索。

hackernews · mooreds · Jun 2, 16:13 · [社区讨论](https://news.ycombinator.com/item?id=48372239)

**背景**: 检索增强生成（RAG）结合了相关文档的检索和语言模型来生成答案。多模态 RAG 将其扩展到图像，但在查询时使用多模态模型成本高且速度慢。索引时生成描述提供了一种更便宜的替代方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@nay1228/data-indexing-in-rag-architecture-implementation-applications-a35394660658">RAG & Data Indexing: A Deep Dive | Medium</a></li>
<li><a href="https://developer.nvidia.com/blog/an-easy-introduction-to-multimodal-retrieval-augmented-generation/">An Easy Introduction to Multimodal Retrieval-Augmented Generation | NVIDIA Technical Blog</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍赞同该方法，并指出他们已使用过类似策略。担忧包括 LLM 的非确定性导致新模型可能揭示不同信息，以及需要作者更新标题。

**标签**: `#RAG`, `#image indexing`, `#LLM`, `#cost optimization`, `#retrieval`

---

<a id="item-3"></a>
## [Anthropic 提交 IPO 申请，估值接近万亿美元](https://decrypt.co/369641/ai-giant-anthropic-files-go-public-nearing-1-trillion-valuation) ⭐️ 8.0/10

AI 公司 Anthropic（Claude 模型的创造者）在估值接近万亿美元后，已向美国证券交易委员会秘密提交了首次公开募股（IPO）申请。 此次 IPO 申请标志着 AI 行业的一个重要里程碑，表明市场对 AI 的高度认可，并可能影响全球 AI 开发、监管和投资趋势。 根据美国《创业企业融资法案》（JOBS Act），此次申请为秘密提交，财务细节尚未公开。Anthropic 最近完成又一轮大规模融资，使其估值接近万亿美元。

rss · Decrypt · Jun 1, 16:09

**背景**: Anthropic 是一家由前 OpenAI 员工创立的 AI 安全与研究公司。其旗舰产品 Claude 是一个大型语言模型，与 OpenAI 的 GPT 和 Google 的 Gemini 竞争。IPO 将为 Anthropic 提供公开资本，以扩大运营规模并在快速增长的 AI 市场中竞争。

**标签**: `#Anthropic`, `#IPO`, `#AI`, `#funding`, `#industry news`

---

<a id="item-4"></a>
## [微软发布 137B 参数编程模型 MAI-Code-1-Flash](https://microsoft.ai/news/introducingmai-code-1-flash/) ⭐️ 7.0/10

微软发布了 MAI-Code-1-Flash，这是一个 137B 参数的混合专家（MoE）编程模型，拥有 256K token 的上下文窗口，并在超过 10 万亿 token 上进行了训练。该模型现已可在 Visual Studio Code 的 GitHub Copilot 中使用。 该模型代表了微软在 AI 编程助手领域的竞争努力，但社区基准测试表明，其性能仅与 Qwen3.6-35B-A3B 等小得多的模型相当或略优，这引发了对其效率和成本效益的质疑。此次发布也标志着微软构建超越 Azure 的模型生态系统的战略，该模型可在 Fireworks AI 和 OpenRouter 等第三方平台上使用。 MAI-Code-1-Flash 采用自适应解决方案长度控制，根据任务复杂度调整响应深度。它在 SWE-bench Pro 上达到 51%，而 Qwen3.6-35B-A3B 为 49.5%，但社区指出，其基准测试对象 Claude Haiku 并非强劲对手。

hackernews · EvanZhouDev · Jun 2, 18:47 · [社区讨论](https://news.ycombinator.com/item?id=48374466)

**背景**: 用于代码生成的大型语言模型已成为 AI 公司的关键战场，GPT-4、Claude 和 Qwen 等模型相互竞争。混合专家（MoE）架构允许模型拥有大量总参数，但每次只激活一部分，从而实现更快的推理和更低的成本。GitHub Copilot 是一款流行的 AI 编程助手，可与 VS Code 等 IDE 集成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://microsoft.ai/news/introducingmai-code-1-flash/">Introducing MAI-Code-1-Flash | Microsoft AI</a></li>
<li><a href="https://microsoft.ai/pdf/MAI-Code-1-Flash-Model-Card.PDF">PDF MAI-Code-1-Flash model card - microsoft.ai</a></li>
<li><a href="https://dev.to/akaranjkar08/microsoft-mai-thinking-1-mai-code-1-flash-developer-guide-to-7-new-mai-models-k4m">Microsoft MAI-Thinking-1 & MAI-Code-1-Flash: Developer Guide ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论大多持批评态度：用户指出，这个 137B 模型在 SWE-bench Pro 上仅略优于 35B 模型，并质疑如此大的模型在编程任务中的价值。一些用户对微软 Copilot 的定价变化以及营销宣传与实际性能之间的差距表示不满。

**标签**: `#AI`, `#coding`, `#Microsoft`, `#model`, `#benchmark`

---

<a id="item-5"></a>
## [CT 扫描揭示比亚迪汽车零部件的高制造质量](https://www.lumafield.com/scan-of-the-month/byd) ⭐️ 7.0/10

Lumafield 发布了比亚迪汽车零部件的工业 CT 扫描图像，展示了其内部结构的细节，表明制造质量很高，挑战了“中国汽车质量差”的刻板印象。 这一分析提供了客观证据，表明全球最大的插电式电动汽车制造商比亚迪生产的零部件质量可与传统汽车制造商媲美甚至超越，可能改变消费者认知和行业竞争格局。 CT 扫描显示控制臂、副车架和动力总成部件结构坚固，并包含一个带有机械备用钥匙的钥匙扣的详细视图。这些扫描由专注于制造质量工业 CT 扫描的公司 Lumafield 完成。

hackernews · viasfo · Jun 2, 20:30 · [社区讨论](https://news.ycombinator.com/item?id=48375824)

**背景**: 工业 CT 扫描利用 X 射线在不损坏部件的情况下创建其内部和外部结构的三维图像，使工程师能够检查隐藏的缺陷并评估制造质量。比亚迪是一家垂直整合的中国企业集团，超过 75%的汽车零部件（包括电池、电机和电子设备）由内部生产，这种整合程度自早期福特以来未曾见过。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/BYD_Company">BYD Company</a></li>
<li><a href="https://www.lumafield.com/article/what-industrial-ct-scanning-does-for-manufacturing-quality">What Industrial CT Scanning Does for Manufacturing Quality</a></li>

</ul>
</details>

**社区讨论**: 社区评论普遍赞同正面评价，一位高级技师指出比亚迪零部件结构坚固。一位用户纠正了关于钥匙扣设计的细节，其他人则强调了比亚迪的垂直整合和规模，将其与福特和特斯拉进行了有利比较。

**标签**: `#BYD`, `#automotive`, `#CT scan`, `#manufacturing`, `#electric vehicles`

---

<a id="item-6"></a>
## [斯坦福研究：AI 击败法学教授](https://law.stanford.edu/press/ai-outperforms-law-professors-in-stanford-law-study/) ⭐️ 7.0/10

斯坦福法学院的一项研究发现，法学教授在 75%的情况下更倾向于选择 AI 生成的学生合同法问题答案，而非人类写的答案。 这表明 AI 可以作为法学学生的有效辅导工具，可能降低法律教育成本，但也引发了对法律培训和实践过度依赖 AI 的担忧。 该研究仅涉及 16 名法学教授，导致对其统计效力和结果的高变异性提出批评。

hackernews · berlianta · Jun 2, 23:43 · [社区讨论](https://news.ycombinator.com/item?id=48377761)

**背景**: 像 GPT-4 这样的大型语言模型越来越多地被用于法律领域，用于起草文件和回答问题。该研究专门测试了 AI 是否能生成法学教授认为比学生写的更好的答案，这对将 AI 用作辅导工具有着重要意义。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.forbes.com/sites/aliciapark/2026/06/02/stanford-study-finds-ai-beats-law-professors-75-of-the-time/">AI Beat Law Professors At Answering Questions, Study Finds—And It...</a></li>
<li><a href="https://news.ycombinator.com/item?id=48377761">AI outperforms law professors in Stanford Law study | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 社区评论对该研究的方法论提出批评，指出样本量小（16 名教授）且方差高，削弱了统计显著性。一些评论者指出，该研究关注的是 AI 作为辅导工具，而非取代律师，且结果对法律教育仍可能具有积极的社会意义。

**标签**: `#AI`, `#legal`, `#education`, `#LLM`, `#research`

---

<a id="item-7"></a>
## [HP 重新发布经典 HP-16C 程序员计算器](https://hpcalcs.com/product/hp-16c-collectors-edition/) ⭐️ 7.0/10

HP 以收藏版形式重新发布了 HP-16C 程序员计算器，保留了经典的 Voyager 设计并加入了现代编程功能。 此次重新发布唤起了复古计算爱好者和程序员对经典工具的怀念，引发了关于怀旧情怀、制造质量以及 SwissMicros 等现代替代品的讨论。 HP-16C 收藏版预售价为 129.99 美元，而原版生产于 1982 年至 1989 年。部分社区成员基于之前 15C 收藏版的问题，对制造质量表示担忧。

hackernews · dm319 · Jun 2, 19:02 · [社区讨论](https://news.ycombinator.com/item?id=48374685)

**背景**: HP-16C Computer Scientist 是一款专为计算机程序员设计的可编程袖珍计算器，支持 AND、OR、NOT、移位和旋转等位运算。它使用逆波兰表示法（RPN），属于 HP Voyager 系列。SwissMicros 生产了像 DM16L 这样的现代克隆产品，模拟原版 HP-16C 的功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HP-16C">HP-16C - Wikipedia</a></li>
<li><a href="https://hpcalcs.com/product/hp-16c-collectors-edition/">HP 16c Collector's Edition - HP Calc</a></li>
<li><a href="https://en.wikipedia.org/wiki/SwissMicros">SwissMicros</a></li>

</ul>
</details>

**社区讨论**: 社区情绪复杂：一些用户感到兴奋和怀旧，而另一些则质疑制造质量并推荐 SwissMicros 的替代品。有评论者指出，与经通胀调整后的原版价格相比，这次重新发布很划算。

**标签**: `#HP calculators`, `#retro computing`, `#hardware`, `#programmer tools`

---

<a id="item-8"></a>
## [Hyperliquid 在传统交易所开盘前预测了 80%的油价波动](https://www.coindesk.com/markets/2026/06/02/hyperliquid-predicted-80-of-an-oil-market-move-before-traditional-exchanges-even-opened-says-td-securities) ⭐️ 7.0/10

TD Securities 的一份报告称，Hyperliquid 的预测市场在传统交易所开盘前准确预测了 80%的油价波动，展示了该平台在实物资产价格发现方面的潜力。 这标志着加密预测市场在传统金融领域的重要验证，表明它们能比传统交易所提供更早、更准确的价格信号，可能影响机构进行市场分析的方式。 这份来自大型投资银行 TD Securities 的报告特别强调了 Hyperliquid 在预测油价波动方面的表现，但未披露预测的具体方法和时间范围。

rss · CoinDesk · Jun 2, 16:02

**背景**: 预测市场允许用户交易未来事件的结果，通过经济激励来聚合信息。Hyperliquid 是一个去中心化平台，通过其 HIP-4 提案推出了针对 CPI 数据和美联储利率决定等链下事件的预测市场。这些市场越来越被视为实时价格发现的工具，通常优于传统的民意调查和调查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.mexc.com/learn/article/what-are-hyperliquid-prediction-markets-hip-4-offchain-event-contracts-explained/1">What Are Hyperliquid Prediction Markets ? HIP-4 Offchain Event...</a></li>
<li><a href="https://crypto.com/us/research/prediction-markets-oct-2025">Prediction Markets: The Rise of Event-Driven Finance - Crypto.com</a></li>

</ul>
</details>

**标签**: `#crypto`, `#prediction markets`, `#oil`, `#price discovery`, `#DeFi`

---

<a id="item-9"></a>
## [微软发布可靠性提升千倍的量子芯片，引发比特币安全担忧](https://decrypt.co/369811/microsoft-1000x-more-reliable-quantum-chip-bitcoin-threat-draws-nearer) ⭐️ 7.0/10

微软发布了 Majorana 2 量子芯片，该芯片采用拓扑量子比特，可靠性提升 1000 倍，并将实用量子计算机的路线图加速至 2029 年。 这一进展使量子计算更接近打破比特币的加密安全，因为最近的研究表明量子计算机可能比预期更早威胁到比特币。 微软利用 AI 加速了 Majorana 2 的开发，但一些物理学家因缺乏已发表的证据而对芯片的性能表示怀疑。

rss · Decrypt · Jun 3, 03:31

**背景**: 量子计算机利用量子力学，能以指数级速度解决某些经典计算机无法解决的问题。比特币的安全性依赖于被认为能抵御经典攻击的加密算法，但足够强大的量子计算机可能破解这些算法。这种威胁的时间线仍不确定，但谷歌等机构最近的论文表明它可能比之前认为的更早到来。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://quantum.microsoft.com/en-us/insights/blogs/majorana-2-scalable-quantum-processor">Microsoft Quantum | Majorana 2 – Microsoft's Scalable Quantum ...</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/quantum-computing/microsoft-announces-majorana-2-quantum-computing-chip-claims-a-practical-machine-will-come-in-2029">Microsoft announces Majorana 2 quantum computing chip ...</a></li>
<li><a href="https://www.forbes.com/sites/digital-assets/2026/03/31/google-finds-quantum-computers-could-break-bitcoin-sooner-than-expected/">Google Finds Quantum Computers Could Break Bitcoin Sooner ...</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#cryptography`, `#Bitcoin`, `#Microsoft`, `#security`

---

<a id="item-10"></a>
## [微软将 OpenClaw 转化为企业 AI 代理 Scout](https://decrypt.co/369781/microsoft-scout-openclaw-enterprise-ai-agent) ⭐️ 7.0/10

微软推出了 Scout，这是一个由开源 OpenClaw 驱动的企业 AI 代理，集成在 Microsoft 365 中。这为 14 亿 Windows 用户带来了自主任务自动化，无需技术专业知识。 此举通过将 OpenClaw 嵌入全球最广泛使用的生产力套件，显著扩大了其影响力（OpenClaw 已有超过 31 万 GitHub 星标）。这可能加速企业对 AI 代理的采用，并为开源 AI 集成到主流软件树立先例。 Scout 位于 Microsoft 365 内部，利用身份、凭证和访问控制确保企业安全。它自动化会议准备、邮件管理和文档审查等任务，非技术用户也可使用。

rss · Decrypt · Jun 2, 20:25

**背景**: OpenClaw 是一个免费、开源的 AI 助手，可在本地运行，并通过大型语言模型在 WhatsApp、Telegram 和 Discord 等消息平台上自动化任务。它因其灵活性和自主性在开发者中广受欢迎。微软的 Scout 将此能力适配到企业环境，增加了安全性和合规性功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/369781/microsoft-scout-openclaw-enterprise-ai-agent">Microsoft Turns OpenClaw Into an Enterprise AI Agent With Scout</a></li>
<li><a href="https://www.microsoft.com/en-us/microsoft-365/blog/2026/06/02/introducing-microsoft-scout-your-always-on-personal-agent/">Introducing Microsoft Scout : Your always-on personal agent</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenClaw">OpenClaw - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Microsoft`, `#AI Agents`, `#Enterprise`, `#OpenClaw`, `#Windows`

---

<a id="item-11"></a>
## [英伟达 Nemotron 3 Ultra：美国最佳开源模型，仍落后中国](https://decrypt.co/369689/nvidia-open-ai-model-nemotron-3-ultra) ⭐️ 7.0/10

英伟达发布了 Nemotron 3 Ultra，这是一个 550B 参数的开源权重 AI 模型，采用混合 Mamba-Transformer MoE 架构，在美国开源模型中得分最高，但仍落后于中国的前沿模型。 此次发布标志着英伟达最强的开源权重 AI 模型，挑战了闭源模型的主导地位，并凸显了中美 AI 发展之间的竞争差距。 该模型总参数 550B，每 token 激活 55B，采用混合 Mamba-Transformer 专家混合架构，在 Artificial Analysis Intelligence Index 上得分为 48，在预发布端点上每秒处理超过 300 个 token。

rss · Decrypt · Jun 1, 22:46

**背景**: 开源权重 AI 模型的训练参数公开可用，允许开发者下载并在本地运行。英伟达的 Nemotron 系列与 Llama、DeepSeek 等其他开源模型竞争，而中国的 DeepSeek 等模型近期已达到前沿性能水平。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.nvidia.com/nemotron/nightly/usage-cookbook/Nemotron-3-Ultra-Base/README.html">NVIDIA Nemotron 3 Ultra — Base Model</a></li>
<li><a href="https://x.com/ArtificialAnlys/status/2061304911565144230">Nemotron 3 Ultra scores 48 on the Artificial Analysis Intelligence Index. This is well ahead of ...</a></li>
<li><a href="https://allthings.how/what-is-an-open-weight-ai-model-and-how-to-use-one/">What is an Open Weight AI Model and How to Use One</a></li>

</ul>
</details>

**标签**: `#AI`, `#Nvidia`, `#open-source`, `#model comparison`, `#Nemotron`

---

<a id="item-12"></a>
## [DuckDuckGo 的“无 AI”功能受欢迎](https://decrypt.co/369688/duckduckgo-no-ai-google) ⭐️ 7.0/10

DuckDuckGo 推出了 Duck AI，但其“无 AI”功能（返回传统搜索结果，不含 AI 生成的答案）却意外受到用户欢迎。 这一趋势表明用户对搜索引擎中 AI 集成的反感日益增长，凸显了对更简单、注重隐私的搜索体验的需求。 “无 AI”选项允许用户选择退出 AI 生成的摘要，仅查看自然网页结果，体现了 DuckDuckGo 对用户选择和隐私的承诺。

rss · Decrypt · Jun 1, 22:16

**背景**: 谷歌等主流搜索引擎越来越多地将 AI 生成的答案整合到搜索结果中，有时会将自然链接推得更靠后。以隐私优先著称的 DuckDuckGo 最初推出了 Duck AI，但现在发现用户对非 AI 模式的需求更强烈。

**标签**: `#AI`, `#search engines`, `#user experience`, `#privacy`, `#DuckDuckGo`

---

<a id="item-13"></a>
## [在 Linux 上将 Nvidia GPU 显存用作交换空间](https://github.com/c0dejedi/nbd-vram) ⭐️ 6.0/10

一款名为 nbd-vram 的新开源工具允许 Linux 用户将 Nvidia GPU 显存用作交换空间，主要针对内存焊接、不可升级的笔记本电脑。 这为受限于笔记本电脑有限内存的用户提供了实用的解决方案，利用闲置的 GPU 显存来提升内存压力下的系统响应速度。 该工具使用 NBD（网络块设备）创建由显存支持的交换设备，在 RTX 3070 笔记本 GPU 上顺序吞吐量约为 1.3 GB/s。如果 GPU 繁忙，它会自动减少显存分配。

hackernews · tanelpoder · Jun 2, 22:55 · [社区讨论](https://news.ycombinator.com/item?id=48377404)

**背景**: 交换空间是内存满时用作 RAM 扩展的存储区域。将 GPU 显存用作交换空间较为小众，因为显存通常保留给图形任务，但在显存充裕而 RAM 有限的系统上，它比 SSD 交换延迟更低。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/c0dejedi/nbd-vram">GitHub - c0deJedi/nbd-vram: Use your NVIDIA GPU's VRAM as swap space on Linux. Built for laptops with soldered memory and no upgrade path. If you have an RTX card sitting there with 8GB of VRAM and you're getting swapped to SSD, this puts that VRAM to work · GitHub</a></li>
<li><a href="https://wiki.archlinux.org/title/Swap_on_video_RAM">Swap on video RAM - ArchWiki</a></li>

</ul>
</details>

**社区讨论**: 评论者指出顺序吞吐量比 NVMe SSD 慢，但延迟可能更低。有人担心 Wayland 动态显存分配会导致桌面崩溃，而其他人则认为这对拥有闲置显存的机器有价值。

**标签**: `#Linux`, `#GPU`, `#swap`, `#VRAM`, `#performance`

---

<a id="item-14"></a>
## [开发者分享使用 Clojure 一个月的体验](https://www.acdw.net/clojure/) ⭐️ 6.0/10

一位开发者发布博客文章，详细介绍了使用 Clojure 约一个月后的初步印象，包括构建一个静态网站生成器来驱动自己的网站。 这篇个人体验突出了 Clojure 在函数式编程方面的吸引力及其独特的简洁性理念，可能鼓励其他开发者探索该语言及其生态系统。 该开发者从头开始使用 Clojure 创建了一个静态网站生成器，利用宏实现了自定义模板引擎，但指出在优化输出和支持作用域 CSS 等高级功能方面存在挑战。

hackernews · speckx · Jun 2, 19:56 · [社区讨论](https://news.ycombinator.com/item?id=48375393)

**背景**: Clojure 是一种现代 Lisp 方言，运行在 Java 虚拟机（JVM）上，强调函数式编程、不可变性和并发。静态网站生成器（SSG）是将内容文件（如 Markdown）编译成静态 HTML 页面的工具，简化了网站托管并提高了安全性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Clojure">Clojure - Wikipedia</a></li>
<li><a href="https://clojure.org/">Clojure</a></li>
<li><a href="https://en.wikipedia.org/wiki/Static_site_generator">Static site generator</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，编写静态网站生成器是 Lisp 爱好者的必经之路，并强调了 Clojure 在 JavaScript（ClojureScript）和 Python（Basilisp）等平台上的可移植性。一些人认为运行时和并发模型比语法更重要，将 Java 的运行时与 Erlang 的进行了不利比较。

**标签**: `#Clojure`, `#Programming Languages`, `#Static Site Generator`, `#Lisp`

---

<a id="item-15"></a>
## [美国财政部制裁伊朗加密货币交易所 Nobitex](https://decrypt.co/369816/us-treasury-sanctions-iranian-crypto-exchanges-nobitex-terrorist-financing) ⭐️ 6.0/10

美国财政部外国资产控制办公室（OFAC）对伊朗加密货币交易所 Nobitex 及其他平台实施制裁，指控其协助非法金融和恐怖融资活动。 此举凸显了美国政府日益关注加密货币作为逃避制裁和恐怖融资工具，可能影响全球加密货币监管和合规标准。 据美国财政部称，Nobitex 去年处理了伊朗超过一半的加密货币流入，凸显了其在伊朗加密生态系统中的核心作用。

rss · Decrypt · Jun 2, 22:55

**背景**: OFAC 是美国财政部下属机构，负责对目标国家、政权和实体实施经济制裁。伊朗一直受到美国广泛制裁，加密货币交易所因可能被用于规避这些限制而受到审查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Office_of_Foreign_Assets_Control">Office of Foreign Assets Control - Wikipedia</a></li>
<li><a href="https://www.trmlabs.com/resources/blog/understanding-nobitex-irans-largest-crypto-exchange">Understanding Nobitex: Iran’s Largest Crypto Exchange | TRM Labs</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#sanctions`, `#regulation`, `#Iran`, `#terrorist financing`

---

<a id="item-16"></a>
## [特朗普签署 AI 行政令，建立自愿审查框架](https://decrypt.co/369740/president-trump-signs-ai-executive-order-delaying-china-concerns) ⭐️ 6.0/10

特朗普总统签署了一项行政令，建立了针对先进 AI 模型的自愿审查框架，并扩大了 AI 驱动的网络安全举措。 该行政令为美国 AI 监管树立了先例，强调自愿合规而非强制许可，可能影响未来的政策辩论，并改变 AI 公司处理安全与保障的方式。 该行政令包括对新 AI 模型的 30 天审查期，但参与是自愿的，没有强制许可或预审要求。

rss · Decrypt · Jun 2, 18:08

**背景**: AI 行政令是指导联邦机构 AI 政策的总统指令。自愿审查框架与一些立法者提出的强制要求形成对比，反映了在创新与安全之间寻求平衡的持续辩论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://rollcall.com/2026/06/02/executive-order-sets-voluntary-cyber-reviews-for-advanced-ai/">Executive order sets voluntary cyber reviews for advanced AI</a></li>
<li><a href="https://deadline.com/2026/06/trump-ai-executive-order-1236938859/">Trump Signs AI Executive Order That Includes Review Period ...</a></li>
<li><a href="https://www.govinfosecurity.com/trump-signs-voluntary-ai-cyber-review-order-a-31833">Trump Signs Voluntary AI Cyber Review Order - GovInfoSecurity</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#executive order`, `#cybersecurity`, `#regulation`

---

<a id="item-17"></a>
## [比特币矿商 Hive 收入激增，押注 AI 热潮](https://decrypt.co/369735/bitcoin-miner-hive-reports-revenue-surge-powering-ai-boom) ⭐️ 6.0/10

Hive Digital Technologies 报告收入激增，去年开采了近 2900 枚比特币，并宣布计划在大多伦多地区建设加拿大最大的私有 AI 数据中心，这是一个 320 兆瓦的超级工厂，投资额达 35 亿加元。 这标志着从比特币挖矿向 AI 基础设施的重大转变，凸显了加密货币挖矿与 AI 工作负载高性能计算的日益融合，并可能为其他矿商转向 AI 数据中心树立先例。 Hive 在过去一年开采了近 2900 枚比特币，并已斥资 5800 万美元在多伦多购买地块用于 AI 设施，该公司还筹集了 1.15 亿美元以扩大其全球 AI 数据中心布局。

rss · Decrypt · Jun 2, 17:11

**背景**: 比特币挖矿需要大量能源和专用硬件，这些硬件可被重新用于 AI 计算任务。Hive 在加拿大、瑞典和巴拉圭运营由清洁能源驱动的数据中心，其双引擎基础设施现在包括比特币挖矿和基于 GPU 的 AI 计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.hivedigitaltechnologies.com/">HIVE Digital Technologies Ltd</a></li>
<li><a href="https://cryptobriefing.com/hive-digital-ai-gigafactory-canada/">HIVE Digital Technologies plans CAD $3.5 billion AI ...</a></li>
<li><a href="https://www.coindesk.com/business/2026/05/18/hive-buys-usd58-million-toronto-plot-for-ai-facility-shares-climb">HIVE buys $58 million Toronto plot for AI facility; shares climb</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#AI`, `#Data Center`, `#Crypto Mining`

---

<a id="item-18"></a>
## [佛罗里达州起诉 OpenAI 及 Sam Altman，指控 ChatGPT 安全声明不实](https://decrypt.co/369656/florida-lawsuit-openai-sam-altman-chatgpt-safety) ⭐️ 6.0/10

佛罗里达州总检察长 James Uthmeier 提起了全美首个由州政府主导的诉讼，指控 OpenAI 及其 CEO Sam Altman 在明知存在严重风险的情况下发布并推广 ChatGPT，同时隐瞒风险并压制内部安全警告。 该诉讼可能为追究 AI 公司及其高管因安全失误的个人责任开创先例，从而重塑 AI 监管和企业问责制度。 该诉讼要求赔偿、对 ChatGPT 施加限制，并追究 Sam Altman 的个人责任，理由是对儿童构成风险且缺乏安全保障。佛罗里达州声称 OpenAI 可能面临数十亿美元的赔偿。

rss · Decrypt · Jun 1, 18:28

**背景**: 随着 ChatGPT 等生成式 AI 产品被广泛采用，AI 安全已成为公众关注的主要问题。针对 AI 公司的诉讼通常针对公司本身，而非个别高管；本案试图将责任延伸至 CEO 个人。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.myfloridalegal.com/newsrelease/attorney-general-james-uthmeier-files-first-nation-state-led-lawsuit-against-openai-ceo">Attorney General James Uthmeier Files First-in-the-Nation ...</a></li>
<li><a href="https://www.cnbc.com/2026/06/01/florida-ag-open-ai-altman-lawsuit.html">Florida AG sues OpenAI, seeks to hold Altman liable for ...</a></li>
<li><a href="https://www.foxbusiness.com/media/florida-ag-says-openai-exposed-billions-potential-damages-cites-evidence-uncovered-investigation">Florida sues OpenAI over ChatGPT risks to children, seeks ...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#regulation`, `#lawsuit`, `#OpenAI`

---

<a id="item-19"></a>
## [白帽黑客帮助找回 2016 年 ICO 中卡住的 200 万美元 ETH](https://decrypt.co/369623/whitehat-helps-recover-2m-in-eth-stuck-since-2016-ico) ⭐️ 6.0/10

一名白帽黑客利用 HongCoin 2016 年 ICO 智能合约中保留的整数溢出漏洞，恢复了被冻结九年的 1,003.62 ETH（价值约 200 万美元）。 此次找回表明，旧的智能合约漏洞可能持续存在多年，而白帽干预可以挽救那些被认为永远丢失的资金，使最初的 48 位投资者受益。 该漏洞是退款函数中的整数溢出，使得白帽能够调用管理员函数重新开启退款；找回的 ETH 被返还给原始多重签名钱包，以便分发给投资者。

rss · Decrypt · Jun 1, 15:32

**背景**: HongCoin 于 2016 年 8 月发起 ICO，从 48 名参与者那里收集了 ETH。该 ICO 未能达到目标，智能合约本应自动退款给贡献者，但一个漏洞阻止了退款处理。这些资金一直卡住，直到一名白帽开发者发现该漏洞并利用它找回了 ETH。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cryptorank.io/news/feed/cb600-failed-ethereum-ico-from-2016-just-unlocked-1003-eth-by-exploiting-itself">Failed Ethereum ICO from 2016 just unlocked 1,003 ETH by exploiting...</a></li>
<li><a href="https://cryptobriefing.com/hongcoin-investors-recover-locked-eth-nine-years/">HongCoin investors recover $2M in locked ETH after nine years</a></li>
<li><a href="https://www.coindesk.com/tech/2026/06/01/whitehat-developer-unlocks-usd2-million-stuck-in-a-2016-ethereum-ico-contract-for-nine-years">Whitehat developer unlocks $2 million stuck in a 2016 Ethereum ICO contract for nine years</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#whitehat`, `#smart contract`, `#recovery`

---

<a id="item-20"></a>
## [Galaxy Digital 为机构推出场外预测市场交易](https://www.theblock.co/post/403338/galaxy-digital-opens-otc-prediction-market-trading-for-institutions-kicks-off-with-10-million-kalshi-trade?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Galaxy Digital 推出了面向机构的场外预测市场交易平台，并与 Arca 在 Kalshi 上执行了一笔 1000 万美元的 Clarity Act 相关交易。 这一发展为对冲基金和家族办公室提供了机构级别的预测市场流动性，可能增加事件驱动合约的市场深度和合法性。 Galaxy 的场外交易台作为主要对手方，支持零售接口无法提供的规模的双边交易，覆盖 Kalshi 和 Polymarket 上的合约，并计划扩展。

rss · The Block · Jun 2, 13:12

**背景**: 预测市场允许交易真实世界事件（如选举或立法）的结果。Kalshi 是一个受监管的美国交易所，而场外交易允许机构之间进行大额、私密的交易。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.prnewswire.com/news-releases/galaxy-launches-institutional-otc-prediction-markets-trading-302788206.html">Galaxy Launches Institutional OTC Prediction Markets Trading</a></li>
<li><a href="https://www.theblock.co/post/403338/galaxy-digital-opens-otc-prediction-market-trading-for-institutions-kicks-off-with-10-million-kalshi-trade">Galaxy Digital opens OTC prediction market trading for institutions, kicks off with $10 million Kalshi trade | The Block</a></li>
<li><a href="https://coinpedia.org/news/clarity-act-new-update-bill-officially-placed-on-senate-calendar-as-galaxy-bets-10m-on-2026-passage/">CLARITY Act New Update: Bill Officially Placed on Senate Calendar as Galaxy Bets $10M on 2026 Passage</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#institutional trading`, `#crypto`, `#finance`

---

<a id="item-21"></a>
## [Backpack 推出混合证券平台](https://www.theblock.co/post/403328/backpack-launches-securities-platform-blending-traditional-and-tokenized-stock-trading?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Backpack 推出了 Backpack Securities 平台，该平台将美国监管的传统股票经纪业务与基于 Solana Sunrise 协议的代币化平台相结合。 这一整合连接了传统金融与区块链，使投资者能够同时交易代币化股票和传统股票，可能提高两个市场的流动性和可及性。 该平台通过受监管的经纪商提供真实的美国股票所有权，并允许通过 Solana 上的 Sunrise 协议对这些股票进行代币化，与 Coinbase 和 Robinhood 等交易所竞争。

rss · The Block · Jun 2, 13:05

**背景**: 代币化股票是在区块链上发行的传统股票的数字表示，支持 24/7 交易和部分所有权。Backpack 获得了 1700 万美元的 A 轮融资，运营受监管的加密货币交易所，现已扩展至证券领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.prnewswire.com/news-releases/backpack-launches-securities-platform-bridging-traditional-and-digital-asset-markets-302788563.html">Backpack Launches Securities Platform Bridging Traditional ...</a></li>
<li><a href="https://tradersunion.com/news/cryptocurrency-news/show/2205360-backpack-tokenized-stock-trading-platform/">Backpack launches tokenized stock trading platform for U.S ...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#fintech`, `#securities trading`

---