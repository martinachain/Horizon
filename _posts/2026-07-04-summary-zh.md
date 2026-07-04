---
layout: default
title: "Horizon Summary: 2026-07-04 (ZH)"
date: 2026-07-04
lang: zh
---

> From 75 items, 22 important content pieces were selected

---

1. [GLM5.2 在 AMD MI355X 上达到 2626 tok/s，成本比 Blackwell 低 2 倍以上](#item-1) ⭐️ 8.0/10
2. [本地运行 SOTA 大模型指南引发成本讨论](#item-2) ⭐️ 8.0/10
3. [欧盟议会间谍软件调查员遭飞马间谍软件攻击](#item-3) ⭐️ 8.0/10
4. [OpenAI 向美国政府提供 420 亿美元股份](#item-4) ⭐️ 8.0/10
5. [Mistral 发布用于 Lean 4 证明的 Leanstral 1.5](#item-5) ⭐️ 7.0/10
6. [SearXNG：一款免费、自托管的元搜索引擎](#item-6) ⭐️ 7.0/10
7. [Costco 的仓储模式避免了昂贵的最后一公里配送](#item-7) ⭐️ 7.0/10
8. [工厂不过是一间房：思维转变](#item-8) ⭐️ 7.0/10
9. [Securitize 在 Solana 和 Avalanche 上代币化 2.95 亿美元股票](#item-9) ⭐️ 7.0/10
10. [SBI Crypto 关闭持有比特币 2%算力的矿池](#item-10) ⭐️ 7.0/10
11. [Ondo Finance 推出符合 SEC 规定的代币化股票](#item-11) ⭐️ 7.0/10
12. [Claude Fable 5 性能下降归咎于过度谨慎的路由器](#item-12) ⭐️ 7.0/10
13. [新型越狱技巧绕过 AI 安全护栏](#item-13) ⭐️ 7.0/10
14. [渣打银行成为首家提供直接 USDC 访问的全球银行](#item-14) ⭐️ 7.0/10
15. [利用计算机视觉和触觉反馈实现 Steam 手柄自动充电](#item-15) ⭐️ 6.0/10
16. [受制裁俄罗斯稳定币的数十亿美元交易量遭质疑](#item-16) ⭐️ 6.0/10
17. [eToro 投资链上衍生品平台 Extended](#item-17) ⭐️ 6.0/10
18. [美国财政部制裁逾 100 个 ISIS-K 加密货币地址](#item-18) ⭐️ 6.0/10
19. [欧洲三年后重新审视 MiCA 加密监管框架](#item-19) ⭐️ 6.0/10
20. [Q-Day：量子计算对比特币的威胁解析](#item-20) ⭐️ 6.0/10
21. [Spotify 要求 Kalshi 和 Polymarket 因流媒体欺诈移除品牌标识](#item-21) ⭐️ 6.0/10
22. [ETF 推出后机构比特币采用加速](#item-22) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [GLM5.2 在 AMD MI355X 上达到 2626 tok/s，成本比 Blackwell 低 2 倍以上](https://www.wafer.ai/blog/glm52-amd) ⭐️ 8.0/10

这展示了 AMD 在 LLM 推理领域日益增强的竞争力，可能为 NVIDIA 主导的 Blackwell 系列提供高性价比替代方案，尤其适用于面临 NVIDIA 供应限制的非美国数据中心。 该性能通过 FP4 量化实现，社区成员指出与 FP8 或更高精度相比可能导致显著的精度下降。MI355X 配备 288GB HBM3E 显存和 8TB/s 带宽。

hackernews · latchkey · Jul 3, 21:49 · [社区讨论](https://news.ycombinator.com/item?id=48780417)

**背景**: LLM 推理速度以每秒 token 数（tok/s）衡量，成本效率对部署至关重要。AMD MI355X 基于 CDNA 4 架构，而 NVIDIA Blackwell GPU（如 RTX 5090）支持原生 FP4（NVFP4）推理。量化降低模型精度以加速推理，但可能损害输出质量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.amd.com/en/products/accelerators/instinct/mi350/mi355x.html">AMD Instinct™ MI355X GPUs</a></li>
<li><a href="https://arxiv.org/html/2601.09527v1">Private LLM Inference on Consumer Blackwell GPUs:</a></li>
<li><a href="https://docs.vllm.ai/projects/llm-compressor/en/0.8.1/examples/quantization_w4a4_fp4/">fp4 Quantization - LLM Compressor Docs - vLLM Documentation</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 FP4 量化的准确性表示怀疑，用户指出模型可能被“功能性阉割”，不再具有前沿质量。有人要求提供每瓦性能指标，并建议在标题中强制注明量化类型。

**标签**: `#AMD`, `#LLM inference`, `#GPU comparison`, `#quantization`, `#cost efficiency`

---

<a id="item-2"></a>
## [本地运行 SOTA 大模型指南引发成本讨论](https://github.com/jamesob/local-llm) ⭐️ 8.0/10

Jamesob 在 GitHub 上发布了一份指南，详细介绍了如何使用高端硬件本地运行最先进的大语言模型，包括一个耗资 4 万多美元、配备四块单价 1.2 万美元 GPU 的配置。 该指南凸显了本地运行 SOTA 大语言模型的极高成本和硬件要求，对大多数用户而言本地部署的实用性受到质疑，并引发了关于云服务是否更具性价比的讨论。 推荐的配置实际花费约 5 万至 5.5 万美元，而非文中所述的 4 万美元，并且依赖量化和剪枝技术将 GLM-5.2 等模型适配到消费级硬件上，这可能会降低模型质量。

hackernews · livestyle · Jul 3, 15:03 · [社区讨论](https://news.ycombinator.com/item?id=48775921)

**背景**: 最先进的大语言模型（如 GPT-4 和 Claude Opus）通常需要庞大的云基础设施。本地运行它们需要高端 GPU 和大容量显存，往往耗资数万美元。量化技术通过降低模型精度来适配可用内存，但可能影响输出质量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.stackademic.com/local-llms-for-self-hosters-what-theyre-good-for-what-they-re-bad-for-and-the-minimum-hardware-57b21315fc29">Local LLMs for self-hosters: what’s worth running at home | Stackademic</a></li>
<li><a href="https://medium.com/data-science-collective/what-is-the-best-hardware-for-running-local-llms-in-2026-mac-vs-5090-vs-cloud-ff023b660442">What Is The Best Hardware for Running Local LLMs in 2026... | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出，4 万美元的配置实际花费超过 5 万美元，这笔钱足以支付 16 年以上的云订阅费用。用户还提到量化模型可能性能不佳，并且存在更便宜的替代方案，如双 RTX 3090 或统一内存系统。

**标签**: `#LLM`, `#local inference`, `#hardware`, `#cost analysis`, `#open-source`

---

<a id="item-3"></a>
## [欧盟议会间谍软件调查员遭飞马间谍软件攻击](https://citizenlab.ca/research/member-of-committee-investigating-spyware-hacked-with-pegasus/) ⭐️ 8.0/10

公民实验室确认，一名调查间谍软件的欧洲议会议员在 2022 年和 2023 年多次感染飞马间谍软件，表明存在具备跨境监控能力的国家行为者。 此次入侵直接针对欧盟的民主进程和安全，因为受害议员正参与调查间谍软件滥用问题。这凸显了商业间谍软件对民主机构的威胁，以及加强防护的必要性。 首次感染发生在 2022 年 10 月 21 日左右，后续感染发生在 2023 年 3 月 6 日和 7 日。此次攻击与已知的针对欧洲俄语和白俄罗斯语流亡记者的飞马间谍软件活动重叠。

hackernews · ledoge · Jul 3, 20:38 · [社区讨论](https://news.ycombinator.com/item?id=48779683)

**背景**: 飞马间谍软件是以色列 NSO 集团开发的强大间谍软件，能够远程入侵移动设备并提取数据、信息，甚至激活麦克风和摄像头。公民实验室是研究数字间谍活动的领先机构，曾曝光全球多起飞马间谍软件滥用事件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus (spyware)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Citizen_Lab">Citizen Lab</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，此次攻击可能与希腊持续的飞马间谍软件丑闻有关，据称总理办公室策划了监控活动。还有人强调，一些欧盟国家滥用飞马间谍软件的程度严重到以色列公司已切断联系，引发了对欧盟内部国家支持间谍活动的质疑。

**标签**: `#cybersecurity`, `#spyware`, `#Pegasus`, `#European Parliament`, `#surveillance`

---

<a id="item-4"></a>
## [OpenAI 向美国政府提供 420 亿美元股份](https://decrypt.co/372715/openai-offers-us-government-42-billion-slice) ⭐️ 8.0/10

OpenAI 首席执行官 Sam Altman 提议向美国政府出售 5%的股权，据报道价值 420 亿美元，并希望其他主要 AI 公司也这样做。 此举可能为 AI 治理中的公私合作伙伴关系树立先例，有可能重塑 AI 公司的监管和融资方式，并使政府直接参与该行业的未来。 据报道，该提议对 OpenAI 的估值超过 8000 亿美元，5%的股份价值约 420 亿美元。Altman 设想所有主要 AI 公司都向政府提供类似股权的模式。

rss · Decrypt · Jul 2, 21:39

**背景**: OpenAI 是一家领先的 AI 研究和部署公司，以 ChatGPT 和 GPT-4 闻名。美国政府一直在探索在保持竞争力的同时监管 AI 的方法。股权可以协调公共利益与私人创新之间的激励。

**标签**: `#OpenAI`, `#AI governance`, `#public-private partnership`, `#regulation`, `#equity`

---

<a id="item-5"></a>
## [Mistral 发布用于 Lean 4 证明的 Leanstral 1.5](https://mistral.ai/news/leanstral-1-5/) ⭐️ 7.0/10

Mistral AI 发布了 Leanstral 1.5，这是一个针对 Lean 4 形式化验证微调的语言模型，声称在证明生成和错误检测方面有所改进。 此次发布推动了 LLM 在形式化验证中的应用，该领域对确保软件正确性至关重要，并可能使 Lean 4 更易于开发者使用。 该模型基于 Mistral 的基础模型微调，采用开放权重，具有 256k 令牌的上下文长度和混合专家架构（119B 参数，每个令牌激活 6.5B）。

hackernews · programLyrique · Jul 3, 22:33 · [社区讨论](https://news.ycombinator.com/item?id=48780801)

**背景**: Lean 4 是一个交互式定理证明器和编程语言，用于形式化验证，即通过机器检查的严谨性证明数学定理和软件属性。Leanstral 是一系列 LLM，旨在协助编写 Lean 4 证明，自动化验证过程的部分环节。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://mistral.ai/news/leanstral/">Leanstral : Open-Source foundation for trustworthy... | Mistral AI</a></li>
<li><a href="https://huggingface.co/mistralai/Leanstral-2603">mistralai/ Leanstral -2603 · Hugging Face</a></li>
<li><a href="https://lean-lang.org/">Lean Programming Language</a></li>

</ul>
</details>

**社区讨论**: 一些评论者对错误发现示例提出质疑，指出溢出边界条件是测试通常能捕获的经典情况。其他人指出，模型比较使用了较旧的模型，使得结果不那么令人印象深刻。

**标签**: `#LLM`, `#formal verification`, `#Lean 4`, `#AI`, `#Mistral`

---

<a id="item-6"></a>
## [SearXNG：一款免费、自托管的元搜索引擎](https://github.com/searxng/searxng) ⭐️ 7.0/10

SearXNG 是一款免费、开源的元搜索引擎，它聚合多个搜索服务的结果，且不追踪或分析用户。该项目积极维护，支持自托管，拥有强大的社区支持。 SearXNG 提供了一种尊重隐私的主流搜索引擎替代方案，随着对数据收集的担忧加剧，这一点日益重要。它还能与本地 AI 模型和代理集成，使其成为注重隐私的开发者与用户的关键工具。 SearXNG 支持多个类别，包括网页、图片、视频、新闻等，并能以 JSON 格式输出结果以便程序化使用。它是 Searx 的一个分支，提供更快的开发速度和更少的错误，具有匿名指标和改进的引擎可靠性等功能。

hackernews · theanonymousone · Jul 3, 20:15 · [社区讨论](https://news.ycombinator.com/item?id=48779454)

**背景**: 元搜索引擎将用户查询发送到多个搜索引擎（如 Google、Bing、DuckDuckGo），并聚合结果，提供统一的界面。与传统搜索引擎不同，元搜索引擎不维护自己的索引，如果配置得当，可以降低隐私风险。SearXNG 是自托管的，意味着用户在自己的服务器上运行它，从而完全控制自己的数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SearXNG">SearXNG - Wikipedia</a></li>
<li><a href="https://github.com/searxng/searxng">GitHub - searxng/searxng: SearXNG is a free internet metasearch engine which aggregates results from various search services and databases. Users are neither tracked nor profiled. · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Searx">Searx - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区讨论强调了 SearXNG 在为本地 AI 模型提供搜索功能方面的作用，用户分享了在 4070 Ti Super 等 GPU 上进行工具调用的设置。Searx 的原始创建者指出了元搜索概念的局限性，并介绍了他的新项目 Hister。一些用户提到了速度较慢和偶尔出现验证码拦截等缺点，但总体情绪是积极的。

**标签**: `#search engine`, `#privacy`, `#open source`, `#self-hosted`, `#AI integration`

---

<a id="item-7"></a>
## [Costco 的仓储模式避免了昂贵的最后一公里配送](https://phenomenalworld.org/analysis/the-anti-amazon/) ⭐️ 7.0/10

一篇文章指出，Costco 的仓储会员制模式通过让顾客自行批量提货，从根本上避免了昂贵的最后一公里配送问题，并与承担高物流成本的亚马逊送货上门系统形成对比。 该分析揭示了零售物流中的根本权衡：集中自提与分散送货上门，这对消费者行为、城市规划及环境影响具有启示意义。它挑战了送货上门总是更便捷或更高效的假设。 Costco 的模式使用货运卡车将整托盘商品送至仓库，顾客驾车前往批量提货，从而消除了每站配送成本。相比之下，亚马逊的最后一公里配送涉及将单个包裹送至每家每户，这是物流中最昂贵、最复杂的环节。

hackernews · bookofjoe · Jul 3, 15:14 · [社区讨论](https://news.ycombinator.com/item?id=48776044)

**背景**: 最后一公里配送问题是指从配送中心到最终客户的最后一步，由于交通、配送失败和包裹密度低等因素，这通常是成本最高、效率最低的环节。Costco 的仓储模式将最后一公里的负担转移给顾客，从而降低了零售商的物流成本。随着电子商务的发展以及城市应对配送拥堵，这一权衡变得尤为重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://onfleet.com/blog/last-mile-problem/">The Last Mile Delivery Problem : Here's How to Solve it</a></li>
<li><a href="https://fourweekmba.com/costco-business-model/">Costco Business Model: How They Made $269.9B in 2025</a></li>
<li><a href="https://supplychain360.io/logistics/costco-warehouse-model-checkout-shift/">Costco refits its warehouse operating model - supplychain360.io</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞了文章的见解，其中一人指出避免问题而非解决问题的工程智慧。另一人强调了 Costco 在以汽车为中心的郊区文化中的作用，而一位英国评论者补充说，Costco 的会员资格在技术上仅限于某些职业，并且该店还以电子产品、轮胎等非食品商品闻名。

**标签**: `#business`, `#logistics`, `#e-commerce`, `#retail`, `#engineering`

---

<a id="item-8"></a>
## [工厂不过是一间房：思维转变](https://interconnected.org/home/2026/07/03/factories) ⭐️ 7.0/10

一篇文章提出，只要心态正确，工厂可以简单到只是一间房间，挑战了关于制造业复杂性的假设。 这种观点通过降低人们感知到的入门门槛，使生产民主化，鼓励更多人考虑小规模制造。 该文章被标记为制造业、系统思维和创客文化，社区参与度高，获得 210 个点赞和 81 条评论。

hackernews · arbesman · Jul 3, 15:13 · [社区讨论](https://news.ycombinator.com/item?id=48776035)

**背景**: 传统制造业通常涉及复杂的供应链、专用机械和大型设施。该文章对此提出挑战，认为只要工具和心态得当，一个简单的房间就能作为工厂运作，强调创造力和适应性而非资本密集型配置。

**社区讨论**: 评论者分享了个人经历：一位曾在英国经营小型工厂的人觉得这很有趣，另一位指出快餐厨房本质上就是工厂。然而，一位来自机械制造公司的评论者警告说，“只是一间房间”的态度可能无法维持稳定的业务。

**标签**: `#manufacturing`, `#systems thinking`, `#maker culture`, `#essay`

---

<a id="item-9"></a>
## [Securitize 在 Solana 和 Avalanche 上代币化 2.95 亿美元股票](https://www.coindesk.com/business/2026/07/02/securitize-tokenizes-usd295-million-of-its-own-stock-on-solana-and-avalanche-amid-nyse-debut) ⭐️ 7.0/10

贝莱德支持的代币化公司 Securitize 在其上市首日，将自身在纽交所上市的 2.95 亿美元股票在 Solana 和 Avalanche 上进行了代币化。 这标志着传统金融与区块链融合的重要一步，一家大型受监管实体在公共区块链上发行代币化股票，可能为现实世界资产代币化的更广泛采用铺平道路。 这些代币化股票由发行人赞助，代表在纽交所交易的同一普通股，通过受监管的基础设施向符合条件的美国投资者开放。Securitize 总裁 Brett Redfearn 表示，该公司正在讨论在未来一年内代币化其他 IPO。

rss · CoinDesk · Jul 2, 19:00

**背景**: Securitize 是一家领先的代币化平台，帮助资产管理公司和公司在区块链网络上发行数字证券。现实世界资产代币化涉及创建基于区块链的代币，代表股票、债券或房地产等传统资产的所有权，旨在提高流动性、可访问性和效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/02/securitize-tokenizes-usd295-million-of-its-own-stock-on-solana-and-avalanche-amid-nyse-debut">Securitize (SECZ) takes $295M of its own tokenized stock to Solana, Avalanche amid NYSE debut</a></li>
<li><a href="https://decrypt.co/372689/securitize-trading-nyse-tokenized-shares-solana-avalanche">Securitize Begins Trading on NYSE as Tokenized Shares Land on Solana, Avalanche - Decrypt</a></li>
<li><a href="https://blockonomi.com/securitize-secz-makes-nyse-debut-while-tokenizing-shares-on-solana-and-avalanche/">Securitize (SECZ) Makes NYSE Debut While Tokenizing Shares on Solana and Avalanche - Blockonomi</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#blockchain`, `#Solana`, `#Avalanche`, `#finance`

---

<a id="item-10"></a>
## [SBI Crypto 关闭持有比特币 2%算力的矿池](https://www.coindesk.com/business/2026/07/02/sbi-crypto-to-shut-down-mining-pool-that-holds-roughly-2-of-bitcoin-s-hashrate) ⭐️ 7.0/10

日本金融巨头 SBI Holdings 的子公司 SBI Crypto 宣布将关闭其比特币矿池，该矿池约占网络总算力的 2%。 此次关闭降低了挖矿中心化风险，但也移除了相当一部分算力，可能影响网络安全和交易处理速度。这标志着挖矿行业持续整合。 该矿池贡献了比特币总算力约 2%，截至 2023 年总算力约为 300 exahash/秒。SBI Crypto 未透露关闭的具体原因，但表示是战略评估的结果。

rss · CoinDesk · Jul 2, 14:44

**背景**: 比特币挖矿采用工作量证明机制，矿工竞争解决加密难题。算力衡量网络的总计算能力。矿池汇集众多矿工的资源以提高获得奖励的机会，然后按贡献比例分配奖励。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hashrate">Hashrate</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mining_pool">Mining pool</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#mining`, `#cryptocurrency`, `#hashrate`

---

<a id="item-11"></a>
## [Ondo Finance 推出符合 SEC 规定的代币化股票](https://www.coindesk.com/business/2026/07/01/ondo-finance-debuts-sec-aligned-tokenized-stock-model-with-blackrock-etf-micron-shares) ⭐️ 7.0/10

Ondo Finance 在以太坊上推出了贝莱德 iShares 核心标普 500 ETF (IVV) 和美光科技 (MU) 股票代币化版本，采用了符合 SEC 指引的托管模式。 这标志着 SEC 托管代币化模型的首次实际应用，将传统证券与区块链结算连接起来，可能为代币化现实世界资产的更广泛机构采用铺平道路。 代币化证券由持有基础资产的第三方托管人发行，结算在以太坊上进行。持有者获得对证券的间接敞口，但也面临托管人破产等交易对手风险。

rss · CoinDesk · Jul 2, 14:16

**背景**: 代币化是指创建基于区块链的代币，代表股票或 ETF 等现实世界资产的所有权。SEC 的托管模型允许第三方持有基础证券并发行代表权益的代币，在现有证券法框架内运作。Ondo Finance 的推出是首次将这一模型付诸实践，涉及贝莱德 IVV ETF 等主要资产。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/01/ondo-finance-debuts-sec-aligned-tokenized-stock-model-with-blackrock-etf-micron-shares">Ondo debuts SEC-aligned tokenized stock model with BlackRock ETF, Micron shares</a></li>
<li><a href="https://genfinity.io/2026/07/02/ondo-broadridge-first-custodial-tokenized-securities-us/">Ondo Debuts First U.S. Custodial Tokenized Securities on Ethereum with BlackRock IVV and Micron - Genfinity</a></li>
<li><a href="https://www.sec.gov/newsroom/speeches-statements/corp-fin-statement-tokenized-securities-012826-statement-tokenized-securities">SEC.gov | Statement on Tokenized Securities</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#DeFi`, `#SEC`, `#BlackRock`, `#real-world assets`

---

<a id="item-12"></a>
## [Claude Fable 5 性能下降归咎于过度谨慎的路由器](https://decrypt.co/372750/claude-fable-5-not-nerfed-router-paranoid) ⭐️ 7.0/10

一篇文章指出，Claude Fable 5 明显的性能下降是由一个过度谨慎的路由层导致的，该路由层将部分敏感请求发送给较弱的模型，而非模型被削弱。 这一解释解决了相互矛盾的基准测试结果，并对依赖稳定 AI 模型性能的用户和开发者具有实际意义。 该路由层自动将一小部分敏感请求发送给 Opus 4.8，其余请求保持 Fable 5 的完整能力，且不改变成本。

rss · Decrypt · Jul 3, 21:06

**背景**: AI 模型通常通过基准测试进行评估，但由于路由层等动态分配请求的因素，可能会出现差异。Claude Fable 5 模型包含一项安全保护机制，将敏感查询路由到更保守的模型，这可能导致基准测试结果不一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/372750/claude-fable-5-not-nerfed-router-paranoid">Claude Fable 5 Isn't Nerfed. The Router Is Just Paranoid - Decrypt</a></li>
<li><a href="https://apidog.com/blog/claude-fable-5-safety-safeguards/">How Claude Fable 5's Safety Safeguards Work (Routing ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#benchmarks`, `#Claude`, `#routing`, `#model evaluation`

---

<a id="item-13"></a>
## [新型越狱技巧绕过 AI 安全护栏](https://decrypt.co/372688/ai-researchers-chatbots-share-cocaine-recipes-wild-trick) ⭐️ 7.0/10

研究人员发现了一种越狱技术，能诱使 AI 模型将攻击者编写的文本视为自己的推理，从而绕过安全护栏，暴露出一个根本性的安全缺陷。 这一漏洞破坏了大型语言模型的核心安全机制，可能让恶意行为者生成毒品配方等有害内容，凸显了更强大的 AI 对齐研究的必要性。 该技术被称为“傀儡攻击”或类似的提示注入方法，通过向助手角色消息中注入虚假的“接受”来利用模型的自洽倾向。它已被证明对 GPT、Gemini 和 DeepSeek 等多种模型有效。

rss · Decrypt · Jul 2, 19:36

**背景**: 大型语言模型（LLM）经过训练，带有安全护栏以拒绝有害请求。越狱指的是精心设计提示词以绕过这些护栏，通常通过操纵上下文、指令或隐藏令牌来实现。这种新方法尤其令人担忧，因为它诱使模型相信有害内容是其自身的推理，从而更难检测。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://slowlow999.github.io/The_Jailbreak_Index/">THE JAILBREAK INDEX</a></li>
<li><a href="https://www.cyberark.com/resources/threat-research-blog/jailbreaking-every-llm-with-one-simple-click">Jailbreaking Every LLM With One Simple Click - CyberArk</a></li>
<li><a href="https://www.trendaisecurity.com/en/resources-insights/research/sockpuppeting-how-a-single-line-can-bypass-llm-safety-guardrails">Sockpuppeting: How a Single Line Can Bypass LLM Safety Guardrails | TrendAI</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#jailbreak`, `#security`, `#LLM`, `#vulnerability`

---

<a id="item-14"></a>
## [渣打银行成为首家提供直接 USDC 访问的全球银行](https://decrypt.co/372674/standard-chartered-first-global-bank-direct-usdc-access) ⭐️ 7.0/10

渣打银行成为首家获授权的全球系统重要性银行，允许机构客户直接铸造和赎回 Circle 的 USDC 稳定币。 这标志着传统银行业与加密生态系统融合的重要一步，可能加速机构采用稳定币进行支付和结算。 USDC 是一种完全储备的稳定币，与美元 1:1 挂钩，由现金和短期美国国债支持。直接铸造和赎回通常需要 KYC/KYB 和 AML 合规。

rss · Decrypt · Jul 2, 13:58

**背景**: 全球系统重要性银行（G-SIB）是指那些倒闭可能引发金融危机的超大型银行，受到更严格的监管。像 USDC 这样的稳定币旨在保持价值稳定，促进加密货币与法定货币的兑换。渣打银行的举措可能为其他 G-SIB 提供类似服务开创先例。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/USDC_(cryptocurrency)">USDC (cryptocurrency) - Wikipedia</a></li>
<li><a href="https://www.circle.com/usdc">USDC | Powering global finance. Issued by Circle.</a></li>
<li><a href="https://en.wikipedia.org/wiki/Global_Systemically_Important_Bank">Global Systemically Important Bank</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#stablecoin`, `#banking`, `#institutional finance`, `#USDC`

---

<a id="item-15"></a>
## [利用计算机视觉和触觉反馈实现 Steam 手柄自动充电](https://github.com/FossPrime/Steam-Controller-Auto-Charge) ⭐️ 6.0/10

一个 GitHub 项目利用计算机视觉，通过手柄的触觉反馈电机使 Steam 手柄在桌面上振动，引导其到达磁吸充电底座。 该项目展示了一种新颖、低成本的自动化充电方法，适用于带有触觉反馈的设备，可能为其他外设的类似改造提供灵感。 手柄仅利用内置的触觉电机在桌面上移动，摄像头提供视觉反馈以对准磁吸充电底座。

hackernews · zdw · Jul 3, 22:39 · [社区讨论](https://news.ycombinator.com/item?id=48780865)

**背景**: Steam 手柄是一款带有双触控板和触觉反馈电机的游戏手柄，可产生振动。计算机视觉（CV）利用摄像头和算法解释视觉数据。磁吸充电底座通过磁铁对准并无线充电设备。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.scan.co.uk/products/nda-23-08-razer-mouse-dock-pro-with-wireless-charging-puck-magnetic-charging-hyperpolling-receiver-c">Razer Mouse Dock Pro + Razer Wireless Charging Puck ... | SCAN UK</a></li>
<li><a href="https://www.elecboy.com.hk/en/products/courant-mag-1-magnetic-charging-puck">Courant MAG:1 Magnetic Charging Puck | Wireless Charger | ElecBoy</a></li>

</ul>
</details>

**社区讨论**: 评论轻松幽默，有用户指出邻居可能会觉得每晚的振动很奇怪。另一用户将其与 iPhone 上的 Cycloramic 应用相比较，该应用利用振动使手机在桌面上旋转。

**标签**: `#computer vision`, `#hardware hack`, `#Steam Controller`, `#haptic feedback`

---

<a id="item-16"></a>
## [受制裁俄罗斯稳定币的数十亿美元交易量遭质疑](https://www.coindesk.com/business/2026/07/03/this-sanctioned-russian-stablecoin-claims-it-processes-billions-but-blockchain-analysts-disagree) ⭐️ 6.0/10

CoinDesk 的一项调查显示，受制裁的俄罗斯卢布支持稳定币 A7A5 声称已处理超过 1100 亿美元的链上交易，但区块链分析师认为，由于刷量交易和自转账导致数据虚高，实际交易量要低得多。 这很重要，因为它凸显了在加密领域执行制裁的挑战——不透明的链上活动可用于规避限制，并强调了需要更准确的区块链分析来区分真实经济活动与操纵行为。 A7A5 受到欧盟和英国制裁，据称占据了非美元稳定币市场 43%的交易量，但分析师指出，大部分交易涉及少数钱包之间的循环交易，从而夸大了数据。

rss · CoinDesk · Jul 3, 19:18

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元或俄罗斯卢布等法定货币挂钩。链上分析涉及检查公共区块链数据以验证交易量并识别模式，但刷量交易（同一资产被反复交易以制造虚假交易量）等技术会使分析复杂化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/03/this-sanctioned-russian-stablecoin-claims-it-processes-billions-but-blockchain-analysts-disagree">This sanctioned Russian stablecoin claims it processes ...</a></li>
<li><a href="https://www.dlnews.com/articles/regulation/how-ruble-stablecoin-a7a5-drove-a-surge-in-sanction-dodging/">How a Russian stablecoin drove a 400% surge in sanction ...</a></li>
<li><a href="https://www.edgen.tech/news/post/russian-stablecoin-a7a5-hits-110b-as-sanctions-evasion-shifts-to-crypto">Russian stablecoin A7A5 hits $110B as sanctions evasion ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#stablecoin`, `#sanctions`, `#blockchain analysis`

---

<a id="item-17"></a>
## [eToro 投资链上衍生品平台 Extended](https://www.coindesk.com/business/2026/07/02/etoro-invests-in-onchain-derivatives-platform-extended-as-brokers-race-into-defi) ⭐️ 6.0/10

eToro 投资了基于 Arbitrum 的链上衍生品平台 Extended，并计划将永续合约引入 Zengo 钱包，同时向其核心平台扩展 DeFi 产品。 这标志着传统经纪商进入 DeFi 的趋势日益增长，可能为主流用户弥合中心化金融与去中心化衍生品交易之间的鸿沟。 Extended 采用统一保证金系统，允许用户从自托管钱包中以高达 50 倍杠杆交易加密货币和传统金融资产，eToro 此举紧随 Robinhood 等竞争对手扩展链上产品之后。

rss · CoinDesk · Jul 2, 17:00

**背景**: 链上衍生品是在区块链平台上交易的金融合约（如永续合约），提供透明度和自我托管。随着去中心化交易所日益流行，eToro 等传统经纪商正越来越多地投资 DeFi，以向其用户提供这些产品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/02/etoro-invests-in-onchain-derivatives-platform-extended-as-brokers-race-into-defi">EToro invests in onchain derivatives platform Extended as ...</a></li>
<li><a href="https://extended.exchange/">Extended Exchange | One Margin for All Markets</a></li>
<li><a href="https://defishills.com/product/extended-exchange/">Extended Exchange – Decentralized Perpetuals | DeFiShills</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#derivatives`, `#crypto`, `#investment`

---

<a id="item-18"></a>
## [美国财政部制裁逾 100 个 ISIS-K 加密货币地址](https://www.coindesk.com/policy/2026/07/02/us-treasury-sanctions-over-100-isis-k-crypto-addresses-in-latest-enforcement-action) ⭐️ 6.0/10

美国财政部制裁了 130 多个与 ISIS-K 相关的 Tron 钱包地址，这些地址共转移了超过 140 万美元，Tether 已冻结相关资金。 此举表明美国政府追踪和打击通过加密货币（尤其是 Tron 网络）进行恐怖融资的能力不断增强，而 Tron 网络此前因助长非法活动而受到批评。 所有被制裁的地址均位于 Tron 区块链上，Tether 发行的稳定币 USDT 已被冻结。此次行动针对 ISIS-K，该组织是 ISIS 在中亚的分支，曾发动多起袭击。

rss · CoinDesk · Jul 2, 14:49

**背景**: ISIS-K（伊斯兰国呼罗珊省）是一个活跃于阿富汗、巴基斯坦和中亚的武装组织。Tron 是一种权益证明区块链，因其低费用而被广泛用于 USDT 转账，但也因助长洗钱和恐怖融资而受到批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ISIS-K">ISIS-K</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tron_(blockchain)">Tron (blockchain)</a></li>
<li><a href="https://grokipedia.com/page/Tether_cryptocurrency">Tether (cryptocurrency)</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#terrorism financing`, `#blockchain`

---

<a id="item-19"></a>
## [欧洲三年后重新审视 MiCA 加密监管框架](https://www.coindesk.com/policy/2026/07/02/three-years-after-mica-became-law-europe-s-crypto-framework-is-undergoing-a-rethink) ⭐️ 6.0/10

在欧盟《加密资产市场》（MiCA）法规成为法律三年后，政策制定者现在正在重新审视该框架，可能导致修订或制定新规则。 这一重新思考可能重塑欧洲的加密监管格局，影响交易所、稳定币发行商及其他服务提供商在全球最大经济区之一的运营方式。 MiCA 的稳定币规则于 2024 年 6 月生效，加密资产服务提供商规则随后于 2024 年 12 月生效；此次审查可能解决自那以来的实施挑战或市场发展问题。

rss · CoinDesk · Jul 2, 11:55

**背景**: MiCA 是欧盟针对现有金融法律未涵盖的加密资产的全面监管框架。经过 18 个月的辩论，于 2022 年通过，旨在提供法律清晰度和消费者保护，同时促进创新。该法规涵盖稳定币、加密交易所和钱包提供商，自 2024 年起分阶段实施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Markets_in_Crypto-Assets">Markets in Crypto -Assets - Wikipedia</a></li>
<li><a href="https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica">Markets in Crypto -Assets Regulation ( MiCA )</a></li>
<li><a href="https://web3.okx.com/learn/what-is-mica">What is MiCA ? A regulatory leap forward for crypto | OKX Wallet</a></li>

</ul>
</details>

**标签**: `#crypto regulation`, `#MiCA`, `#Europe`, `#policy`

---

<a id="item-20"></a>
## [Q-Day：量子计算对比特币的威胁解析](https://decrypt.co/resources/what-q-day-quantum-threat-bitcoin-explained) ⭐️ 6.0/10

专家警告，未来的量子计算机可能伪造比特币的数字签名，实现未经授权的交易，从而可能打破比特币的安全模型。 如果这一威胁成为现实，将破坏最大加密货币比特币的信任和价值，并迫使其密码学基础设施进行根本性升级。 这一威胁源于 Shor 算法，该算法能高效解决比特币 ECDSA 签名背后的离散对数问题，但具备此能力的实用量子计算机可能还需数年才能实现。

rss · Decrypt · Jul 3, 15:40

**背景**: 比特币使用椭圆曲线数字签名算法（ECDSA）来保护交易安全。量子计算机利用量子力学原理，理论上可以通过比经典计算机指数级更快的速度解决底层数学问题，从而破解这一密码学。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2pyOElieEVCRWlSM1BNemd6dWdpZ0FQAQ?hl=en-IN&gl=IN&ceid=IN:en">Google News - Quantum computing threat to Bitcoin - Overview</a></li>
<li><a href="https://cryptorank.io/news/feed/1fbdc-the-quantum-computing-threat-bitcoin-cant-ignore">The quantum computing threat Bitcoin can’t ignore</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#Bitcoin`, `#cryptography`, `#security`

---

<a id="item-21"></a>
## [Spotify 要求 Kalshi 和 Polymarket 因流媒体欺诈移除品牌标识](https://www.theblock.co/post/407134/spotify-asks-kalshi-polymarket-to-remove-branding-after-manipulated-streams-used-to-settle-music-bets-bloomberg?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

据彭博社报道，Spotify 已要求预测市场 Kalshi 和 Polymarket 移除其品牌标识，此前有 50 万次虚假流媒体播放被用于操纵一个价值 300 万美元的音乐博彩市场。 这一事件凸显了预测市场通过现实世界数据被操纵的脆弱性，并引发了对音乐流媒体排行榜及其依赖平台诚信度的担忧。 虚假流媒体播放针对 Malcolm Todd 的歌曲《Earrings》，该歌曲曾短暂登上 Spotify 排行榜榜首。Spotify 已移除这些欺诈性流媒体，并将在排行榜发布前增加额外检查。

rss · The Block · Jul 3, 11:57

**背景**: Kalshi 和 Polymarket 是预测市场，用户对现实世界的结果（如音乐排行榜排名）下注。Spotify 的排行榜被用作这些市场的数据源。此次操纵涉及人为增加流媒体播放量以影响排行榜排名并结算赌注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.biggo.com/news/9be1a98e-fa96-40b5-b699-ef328a19e4d6">Spotify Detects 500,000 Manipulated Streams in Scheme ...</a></li>
<li><a href="https://www.hollywoodreporter.com/music/music-industry-news/spotify-pulls-streams-over-kalshi-betting-fraud-1236636212/">Spotify Pulls Streams From Song After Alleged Kalshi Betting ...</a></li>
<li><a href="https://www.ibtimes.sg/spotify-removes-500000-fake-streams-after-chart-manipulation-roils-3-million-prediction-market-89027">Spotify Removes 500,000 Fake Streams After Chart Manipulation ...</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#fraud`, `#music streaming`, `#blockchain`

---

<a id="item-22"></a>
## [ETF 推出后机构比特币采用加速](https://www.theblock.co/learn/407111/institutional-bitcoin-adoption-explained-how-blackrock-fidelity-and-others-embraced-btc?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

2024 年 1 月现货比特币 ETF 推出后，机构对比特币的采用急剧加速，资产管理公司、企业、银行和养老基金现在积极投资或围绕比特币构建服务。 这标志着加密货币市场从散户主导转向受监管的机构参与，可能提高市场稳定性并推动比特币作为资产类别的主流接受度。 现货比特币 ETF 提供对比特币价格的直接敞口，并在传统交易所交易，使之前面临监管或托管障碍的机构投资者能够轻松参与。

rss · The Block · Jul 3, 06:26

**背景**: 机构采用是指资产管理公司、企业、对冲基金、银行、养老基金和保险公司等组织参与加密货币。在现货 ETF 之前，机构面临托管挑战和监管不确定性等障碍。2024 年 1 月现货比特币 ETF 的推出消除了许多障碍，使受监管实体能够通过熟悉的投资工具获得比特币敞口。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/midchains_the-crypto-industry-needs-to-stop-calling-activity-7460643391865901056-wvag">Institutional Adoption of Crypto Beyond Buzzwords | LinkedIn</a></li>
<li><a href="https://news.bitcoin.com/institutional-crypto-adoption-happening-now-ripple-executive-says-real-world-use-cases-taking-hold/">Institutional Crypto Adoption 'Happening Now': Ripple Executive...</a></li>
<li><a href="https://www.ainvest.com/news/crypto-institutional-adoption-107b-signal-mainstream-validation-2509/">Crypto Institutional Adoption : A $107B Signal for Mainstream...</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#Institutional Adoption`, `#ETFs`, `#Crypto`

---