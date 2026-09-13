---
layout: default
title: "Horizon Summary: 2026-09-13 (ZH)"
date: 2026-09-13
lang: zh
---

> From 51 items, 16 important content pieces were selected

---

1. [Real-SWE 在私有企业代码库上评测 AI 模型](#item-1) ⭐️ 8.0/10
2. [《经济学人》：英伟达是 AI 的中央银行](#item-2) ⭐️ 8.0/10
3. [Revolut 因伪造政府请求泄露比特币活动与护照数据](#item-3) ⭐️ 8.0/10
4. [讽刺文章嘲讽呼吁放缓 AI 的 AI 领袖](#item-4) ⭐️ 7.0/10
5. [Anthropic CEO 呼吁放缓 AI 竞赛，马斯克与 Altman 表示认同](#item-5) ⭐️ 7.0/10
6. [OpenAI 请求国会澄清放缓 AI 发展是否合法](#item-6) ⭐️ 7.0/10
7. [印度 SEBI Demat 2.0 试点以代币化债券募资 1.07 亿美元](#item-7) ⭐️ 7.0/10
8. [JOSM 插件向导帮助新手完成首次 OpenStreetMap 编辑](#item-8) ⭐️ 6.0/10
9. [英国改革党 24 小时内获两位加密富豪 9700 万美元捐款](#item-9) ⭐️ 6.0/10
10. [印度最富裕邦探索资产代币化以筹集基建资金](#item-10) ⭐️ 6.0/10
11. [GPT-6 Astra 用户称 OpenAI 最新模型变笨了](#item-11) ⭐️ 6.0/10
12. [ChatGPT Images 2.5 对决 Nano Banana 2：六大维度横向评测](#item-12) ⭐️ 6.0/10
13. [2025 年律师事务所网络攻击近乎翻倍，被盗文件流入暗网](#item-13) ⭐️ 6.0/10
14. [Blockstream 拒绝为 Liquid 网络被盗的 4700 万美元比特币支付赎金](#item-14) ⭐️ 6.0/10
15. [欧盟监管机构警告预测市场存在内幕交易](#item-15) ⭐️ 6.0/10
16. [阿尔伯克基禁止比特币 ATM，要求运营商 45 天内拆除](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Real-SWE 在私有企业代码库上评测 AI 模型](https://withspecific.com/benchmarks/real-swe) ⭐️ 8.0/10

Specific Labs 发布了 Real-SWE 基准，用从真实公司授权的私有生产代码库来评测前沿 AI 模型，涵盖八种模型与工具链配置、十项任务以及 640 次评分运行。这标志着评测重心从 SWE-bench 这类公开 GitHub issue 基准，转向在模型很可能从未见过的专有企业代码上进行测试。 大多数 AI 编程基准依赖公开仓库，而这些代码可能早已进入模型训练数据，因此容易高估模型的真实能力；在私有企业代码上测试，能更诚实地反映这些工具在真实公司维护的杂乱专有代码库上的表现。评测结果以及 99 条激烈讨论，可能影响企业选择编程助手的方式，以及厂商宣传其模型的方式。 该基准包含八种模型与工具链配置、十项任务和 640 次评分运行，但评论者指出，推理等级和所用具体工具链等关键方法学细节缺失。社区成员还警告，许多所谓“私有”代码库可能早已被训练数据污染，而且 token 用量的差异会扭曲模型之间的成本比较。

hackernews · theanonymousone · Sep 12, 20:25 · [社区讨论](https://news.ycombinator.com/item?id=49676820)

**背景**: SWE-bench 是目前最知名的 AI 编程智能体基准，基于真实的 GitHub issue 和 pull request 构建，其排行榜被广泛引用。但由于数据是公开的，模型可能已经“记住”了答案，这就是所谓的数据污染问题，会削弱基准的有效性。Real-SWE 试图通过从公司授权私有生产代码来解决这一问题，使评测任务真正未被模型见过。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://withspecific.com/benchmarks/real-swe">Real-SWE Benchmark — Specific Labs</a></li>
<li><a href="https://github.com/swe-bench/SWE-bench">GitHub - SWE-bench/SWE-bench: SWE-bench: Can Language Models Resolve Real-world Github Issues? · GitHub</a></li>
<li><a href="https://www.technologyreview.com/2025/05/08/1116192/how-to-build-a-better-ai-benchmark/">How to build a better AI benchmark | MIT Technology Review</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍持怀疑态度：有人质疑私有代码库是否被分享给了 OpenAI 和 Anthropic，也有人警告许多“私有”仓库很可能已被污染，基准应每次都检测污染情况。多位从业者表示约 30% 的成功率与他们自身经验相符，即模型仍不可靠；还有人批评推理等级和工具链选择等方法学细节缺失，使跨模型比较难以令人信服。

**标签**: `#AI benchmarks`, `#software engineering`, `#enterprise codebases`, `#model evaluation`, `#code generation`

---

<a id="item-2"></a>
## [《经济学人》：英伟达是 AI 的中央银行](https://www.economist.com/interactive/briefing/2026/09/03/nvidia-is-the-central-bank-of-ai) ⭐️ 8.0/10

2026 年 9 月 3 日《经济学人》的一篇简报文章提出，英伟达已成为事实上的“AI 中央银行”，依据是它向自身客户提供的约 3000 亿美元担保、兜底和采购承诺，以及其 5.4 万亿美元的市值。该文在 Hacker News 上引发热议，成为最受关注的 AI 话题之一，数百条评论将英伟达的角色与美联储相类比。 这一框架凸显出一家私营企业如今正在履行传统上属于公共货币机构的职能，实际上为 AI 产业的大部分扩张提供融资和信用背书。这种经济权力的集中引发了关于系统性风险、公司治理以及 AI 热潮降温时由谁承担代价的疑问。 据估计，英伟达的投资与承诺总额超过 5000 亿美元，有评论者指出这超过了美联储近期的宽松规模，不过据报道英伟达并未以股票为抵押来为这些承诺融资。文章还提到，英伟达在 2026 年夏季从财报中取消了独立的游戏业务营收披露，引发外界对其战略重心转移的猜测。

hackernews · tolugenius · Sep 12, 15:08 · [社区讨论](https://news.ycombinator.com/item?id=49673098)

**背景**: 英伟达设计驱动当今大多数 AI 训练与推理的 GPU，其芯片使其成为全球市值最高的公司。随着 AI 算力需求激增，英伟达开始投资并向购买其硬件的云服务商和 AI 初创公司提供融资，形成了一张相互依赖的网络。“中央银行”这一比喻指的是，英伟达像货币当局一样，为 AI 经济的运转提供流动性和信用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.economist.com/interactive/briefing/2026/09/03/nvidia-is-the-central-bank-of-ai">Nvidia is the central bank of AI - The Economist</a></li>
<li><a href="https://www.explainx.ai/blog/nvidia-central-bank-of-ai-vendor-financing-2026">Nvidia Central Bank of AI: $300B Backstops Explained (2026 ...</a></li>
<li><a href="https://www.economist.com/leaders/2026/09/03/nvidia-is-driving-the-ai-boom-good">Nvidia is driving the AI boom. Good - The Economist</a></li>

</ul>
</details>

**社区讨论**: 评论者就与美联储的类比展开辩论，指出英伟达超过 5000 亿美元的承诺规模超过美联储近期的宽松，同时对其未以股票抵押借款表示认可。也有人将之比作企业扮演公共机构角色，质疑在 OpenAI 和 Anthropic 呼吁放缓之际 AI 进展是否正在见顶，并猜测英伟达何时会退出游戏市场。

**标签**: `#Nvidia`, `#AI`, `#Economics`, `#Central Banking`, `#Industry Analysis`

---

<a id="item-3"></a>
## [Revolut 因伪造政府请求泄露比特币活动与护照数据](https://www.coindesk.com/tech/2026/09/12/bitcoin-activity-passports-exposed-after-revolut-falls-for-fake-government-request) ⭐️ 8.0/10

Revolut 于 2026 年 9 月 12 日确认，在收到从某政府机构官方邮件域名发出的伪造请求后，将敏感客户数据——包括身份证件、自拍照和完整的比特币交易历史——泄露给了未经授权的第三方。此次事件影响了“有限”数量的用户，链上调查员 ZachXBT 推测攻击可能针对高净值人士。 此次泄露凸显了金融科技公司在核实政府数据请求方面的关键漏洞，可能使用户面临身份盗窃和基于其加密资产持仓的定向攻击风险。这引发了关于 KYC 数据保护和用户对中心化金融平台信任的严重监管与行业性问题。 该伪造请求因来自有效的政府机构邮件域名而通过了 Revolut 的安全检查，泄露的数据包括 KYC 文件、自拍照和比特币交易历史。ZachXBT 的推测表明攻击者可能专门针对富裕用户，但 Revolut 尚未确认受影响客户的具体数量。

rss · CoinDesk · Sep 12, 10:11

**背景**: Revolut 是一家主要的英国金融科技公司，为全球数百万客户提供银行、加密货币交易及其他金融服务。KYC（了解你的客户）程序要求金融机构收集身份文件和个人数据，以遵守反洗钱法规。比特币交易记录在公共区块链上，这意味着任何获得钱包地址的人都可以追踪其完整交易历史，因此泄露的加密活动尤为敏感。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/09/12/revolut-confirms-customer-data-breach-through-fake-government-requests/">Revolut confirms customer data breach through fake government ...</a></li>
<li><a href="https://securityaffairs.com/198922/data-breach/revolut-exposed-kyc-data-after-fraudulent-government-email-passed-security-checks.html">Revolut Exposed KYC Data After Fraudulent Government Email ...</a></li>
<li><a href="https://www.expressvpn.com/blog/is-bitcoin-anonymous/">Is Bitcoin Traceable? How to Stay Anonymous | ExpressVPN</a></li>

</ul>
</details>

**社区讨论**: 链上调查员 ZachXBT 推测此次事件可能针对高净值用户，表明攻击者对 Revolut 的客户群体有特定情报。加密社区对中心化平台同时持有身份和交易数据的风险表示担忧。

**标签**: `#security breach`, `#fintech`, `#privacy`, `#bitcoin`, `#identity theft`

---

<a id="item-4"></a>
## [讽刺文章嘲讽呼吁放缓 AI 的 AI 领袖](https://xeiaso.net/notes/2026/everyone-slowdown-but-me/) ⭐️ 7.0/10

Xe Iaso 发表了一篇讽刺博客文章《所有人都应该放缓 AI 发展，除了我》，批评 AI 领袖公开呼吁放缓 AI 发展却继续推进自家系统的虚伪行为。该文章在 Hacker News 上引发了热烈讨论，获得 318 分和 175 条评论，涉及 AI 安全、监管和权力动态。 这篇评论凸显了人们对行业领袖 AI 安全言论日益增长的怀疑，批评者认为这些言论往往自私自利，旨在实现监管俘获。讨论反映了关于谁应控制 AI 发展以及如何平衡创新与安全的更广泛社会紧张关系。 该文章并非技术突破，而是对 AI 安全言论的尖锐讽刺，Hacker News 讨论串包含了对监管俘获和地缘政治动态的多样化批判观点。评论者争论 AI 末日论是否已成为道德恐慌，并质疑萨姆·奥尔特曼和达里奥·阿莫代伊等领袖的动机。

hackernews · xena · Sep 13, 00:30 · [社区讨论](https://news.ycombinator.com/item?id=49678683)

**背景**: AI 安全是一个跨学科领域，专注于防止 AI 系统引发事故、滥用或有害后果，包括对齐和监控。AI 监管涉及制定公共政策和法律来治理 AI，近期如 2024 年欧盟 AI 法案等努力。随着生成式 AI 快速发展，关于放缓 AI 发展的辩论愈演愈烈，一些领袖呼吁暂停，而另一些则继续推进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_safety">AI safety</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_regulation">AI regulation</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认为 AI 安全言论虚伪且自私，一些人预测这将被视为道德恐慌。其他人指出，放缓公共 AI 发展可能让民族国家制造能力差距，而股东和地缘政治竞争使得放缓不太可能。

**标签**: `#AI safety`, `#AI regulation`, `#tech ethics`, `#Hacker News`, `#AI policy`

---

<a id="item-5"></a>
## [Anthropic CEO 呼吁放缓 AI 竞赛，马斯克与 Altman 表示认同](https://www.coindesk.com/tech/2026/09/12/anthropic-ceo-calls-for-ai-race-to-slow-down-musk-and-openai-s-altman-agrees) ⭐️ 7.0/10

Anthropic CEO Dario Amodei 公开呼吁对 AI 发展进行“前沿节奏控制”（pacing the frontier），主张出于安全考虑应放缓行业步伐，Elon Musk 与 OpenAI CEO Sam Altman 均对此表示认同。 三家主要竞争性 AI 实验室的负责人公开就放缓达成一致实属罕见，这可能改变华盛顿的政策辩论方向，并迫使其他实验室做出类似的安全承诺。 这一呼吁出现在监管真空之中：美国国会虽经辩论但未通过任何全面的 AI 监管立法，白宫也尚未确定由哪个机构负责监管该技术；与此同时，批评者认为在企业与国家间激烈竞争下，放缓几乎不可能实现。

rss · CoinDesk · Sep 12, 18:43

**背景**: Anthropic 由 Dario Amodei 等前 OpenAI 研究人员于 2021 年创立，他们离开 OpenAI 的部分原因是对安全优先事项存在分歧，公司也以“安全优先”理念和《负责任扩展政策》（Responsible Scaling Policy）树立品牌。关于放缓 AI 发展的争论核心在于：若缺乏足够的对齐技术，前沿模型是否会变得危险，以及实验室与国家之间的“军备竞赛动态”是否会让任何单方面放缓都变得徒劳。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/responsible-scaling-policy">Anthropic’s Responsible Scaling Policy</a></li>
<li><a href="https://www.cnn.com/2026/09/12/tech/anthropic-ceo-essay-ai">Anthropic CEO calls for ‘pacing the frontier’ of AI race ... | CNN Business</a></li>
<li><a href="https://time.com/article/2026/08/16/ai-race-slowdown-data-center-verification/">time.com/article/2026/08/16/ ai - race - slowdown -data-center-verification</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者普遍持怀疑态度：有人认为 Amodei 的呼吁实际上是承认 Anthropic 未能解决对齐问题，真正目的是保护市场地位；也有人指责该公司以伦理为名行监管俘获和反竞争之实；少数人支持前沿节奏控制，但怀疑能否达成广泛共识。

**标签**: `#AI safety`, `#AI regulation`, `#Anthropic`, `#OpenAI`, `#industry news`

---

<a id="item-6"></a>
## [OpenAI 请求国会澄清放缓 AI 发展是否合法](https://decrypt.co/377990/openai-congress-ai-slowdown-legal) ⭐️ 7.0/10

OpenAI 正式请求美国国会澄清，在现行反垄断规则下，协调放缓 AI 发展是否合法。这一请求正值研究人员呼吁克制、专家警告激烈竞争会促使企业忽视安全风险之际。 这一问题的答案可能决定前沿 AI 实验室能否合法协调发展节奏，从而影响整个 AI 行业的安全实践与竞争格局。这也表明领先的 AI 公司日益担忧反垄断法可能阻碍自愿克制。 参议员 Adam Schiff 和 Jim Banks 已提出 S.5105 法案，允许企业达成协议以缓解某些 AI 模型风险，而不触发反垄断责任；该法案仍在参议院司法委员会审议中，尚未进行投票。

rss · Decrypt · Sep 11, 18:16

**背景**: 反垄断法通常禁止竞争者协调限制产量或贸易，这可能使全行业自愿放缓 AI 发展面临法律风险。随着 AI 能力快速提升，一些研究人员和政策制定者主张有意识地控制节奏，但企业担心此类协调可能被视为非法串通。S.5105 法案旨在为出于安全动机的协议创建法律安全港。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thecurrencyanalytics.com/technology/openai-seeks-legal-path-to-slow-ai-without-antitrust-penalties-293004">OpenAI Seeks Legal Path to Slow AI Without Antitrust Penalties</a></li>
<li><a href="https://www.wired.com/story/openai-wants-to-know-if-an-ai-industry-slowdown-would-even-be-legal/">OpenAI Wants to Know if an AI Industry Slowdown Would... | WIRED</a></li>
<li><a href="https://techxplore.com/news/2026-06-competition-ai-firms-favor-safety.html">Competition may push AI firms to favor speed over safety , new study...</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#antitrust`, `#OpenAI`, `#AI regulation`, `#AI safety`

---

<a id="item-7"></a>
## [印度 SEBI Demat 2.0 试点以代币化债券募资 1.07 亿美元](https://www.theblock.co/news/regulation/2026-09-11-indias-sebi-demat-2-0-pilot-debuts-with-over-100-million-in-tokenized-bonds-414252) ⭐️ 7.0/10

印度证券交易委员会（SEBI）于 2026 年 9 月 11 日启动 Demat 2.0 试点，三家发行方通过代币化公司债券合计募资 1,025 亿卢比（约 1.072 亿美元），并通过印度储备银行的批发型 CBDC 完成结算。第一阶段聚焦发行环节，利用分布式账本技术进行持有与结算，实现原子化券款对付。 这是迄今为止规模最大的、以央行货币结算代币化公司债的真实案例之一，表明印度监管机构正将基于区块链的市场基础设施从概念推向实际试点。若实现规模化，可能重塑印度企业的债券发行与结算方式，并为其他探索批发型 CBDC 整合的司法辖区提供范本。 该试点使用分布式账本技术进行发行、持有和结算，代币化债券与印度储备银行的批发型数字卢比挂钩以实现原子化结算；第一阶段仅限于发行环节，二级市场交易尚未纳入范围。1,025 亿卢比的总规模来自三家发行方，该项目仍属早期试点，而非全面生产上线。

rss · The Block · Sep 11, 12:09

**背景**: 代币化债券是将所有权与结算记录在区块链或分布式账本上的固定收益工具，同时保留票息、期限和信用风险等传统特征。批发型 CBDC 是仅用于银行及金融机构之间交易的央行数字货币，与面向公众的零售型 CBDC 不同。SEBI 的 Demat 2.0 建立在印度现有的证券无纸化（Demat）体系之上——该体系已以电子形式持有股票和债券——并新增了基于分布式账本技术的发行与结算功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/news/regulation/2026-09-11-indias-sebi-demat-2-0-pilot-debuts-with-over-100-million-in-tokenized-bonds-414252">India 's SEBI Demat 2 . 0 pilot debuts with over $100 million... | The Block</a></li>
<li><a href="https://coin360.com/news/india-demat-2-tokenized-bonds">India 's Demat 2 . 0 Tokenizes Corporate Bonds</a></li>
<li><a href="https://www.weforum.org/stories/2024/02/wholesale-retail-cbdcs-difference/">Wholesale and retail CBDCs – what exactly is the difference ...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#CBDC`, `#financial-regulation`, `#capital-markets`

---

<a id="item-8"></a>
## [JOSM 插件向导帮助新手完成首次 OpenStreetMap 编辑](https://high5apps.github.io/josm-plugin-website-wizard/) ⭐️ 6.0/10

JOSM（Java OpenStreetMap 编辑器）的一款新网站向导插件已发布，它提供分步指引，帮助新手通过快速为地点添加网站标签来完成对 OpenStreetMap 的首次编辑。相关讨论帖获得了 393 分和 92 条评论，经验丰富的制图者就 JOSM 是否适合作为新手入门工具展开了争论。 降低新贡献者的入门门槛对 OpenStreetMap 至关重要，因为其由志愿者维护的数据库需要与 Google Maps 和 Apple Maps 等专有服务竞争。如果初学者觉得编辑过于吓人或令人困惑，该项目就可能失去那些能让地图数据保持准确和最新的本地新知识。 该插件专门设计用于尽可能快速、轻松地为 OpenStreetMap 中的地点添加网站标签，但社区成员指出，JOSM 是一款功能强大的桌面编辑器，拥有默认 iD 编辑器所不具备的高级功能，因此对首次编辑来说可能过于复杂。被提及的替代新手友好工具包括：用于基于任务的 Android 编辑的 StreetComplete、用于中级智能手机编辑的 Every Door，以及用于网页编辑的 Rapid。

hackernews · juliantigler · Sep 12, 16:25 · [社区讨论](https://news.ycombinator.com/item?id=49674050)

**背景**: OpenStreetMap 是一张由志愿者构建的免费、可编辑的世界地图，其精神类似于维基百科，但针对的是地理数据。贡献者通过描摹航拍影像、记录 GPS 轨迹或实地勘察来添加数据，由此产生的数据库被无数应用和导航服务使用。JOSM 是一款历史悠久的、用 Java 编写的 OSM 桌面编辑器，而 iD 则是直接嵌入 OpenStreetMap 网站的更简单的编辑器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenStreetMap">OpenStreetMap</a></li>
<li><a href="https://en.wikipedia.org/wiki/JOSM">JOSM - Wikipedia</a></li>
<li><a href="https://github.com/High5Apps/josm-plugin-website-wizard">GitHub - High5Apps/ josm - plugin -website- wizard : JOSM plugin to...</a></li>

</ul>
</details>

**社区讨论**: 社区普遍认为 JOSM 不适合作为首次编辑的工具，一位用户表示"绝对不推荐"，并建议改用内置的 iD 编辑器。其他人推荐 StreetComplete、Every Door 和 Rapid 作为更温和的入门选择，而一位新手则分享了积极体验：他绘制了一条新自行车道，并看到自己的贡献传播到了 Google 和 Apple 所忽略的应用中。还有人提出了更广泛的担忧：OSM 让大多数编辑变得太难，应该优先绘制商店及其类型和营业时间。

**标签**: `#OpenStreetMap`, `#mapping`, `#JOSM`, `#tutorial`, `#community`

---

<a id="item-9"></a>
## [英国改革党 24 小时内获两位加密富豪 9700 万美元捐款](https://www.coindesk.com/business/2026/09/12/nigel-farage-s-reform-uk-lands-usd97-million-donations-from-two-crypto-billionaires-in-24-hours) ⭐️ 6.0/10

据媒体报道，奈杰尔·法拉奇领导的英国改革党在 24 小时内从两位加密富豪处获得了合计 7200 万英镑（约 9750 万美元）的捐款。该党坚称捐赠者并不期望获得任何回报。 这笔巨额捐款凸显了加密货币财富日益增长的政治影响力，并加剧了关于英国政治是否应禁止加密货币捐款的争论。此事正值上议院审议一项法案之际，该法案拟将海外捐款上限设为每年 10 万英镑，并全面禁止加密资产捐款。 上议院拟对《人民代表法案》提出的修正案将把海外选民的所有捐款和受监管交易限制在每年 10 万英镑，并彻底禁止加密货币捐款。改革党还因未申报捐款以及有高层成员涉嫌策划规避政治捐款规则的指控而面临独立审查。

rss · CoinDesk · Sep 12, 18:51

**背景**: 英国政党受到捐款规则的约束，包括要求大额捐款必须来自合法来源并如实申报。加密货币捐款因难以追踪且可能来自海外而成为争议焦点，促使各方提出限制或禁止此类捐款的建议。由奈杰尔·法拉奇领导的改革党影响力上升，并吸引了包括加密货币行业人士在内的富有捐赠者的大量资金支持。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gov.uk/government/news/cap-on-donations-from-overseas-electors-and-ban-on-crypto-donations-to-protect-democracy">Cap on donations from overseas electors and ban on crypto ...</a></li>
<li><a href="https://www.onebullex.com/news/articles/reform-uk-accepts-72-million-from-crypto-billionaires-as-lords-push-100-000-donation-cap">Reform UK Accepts £72 Million From Crypto Billionaires As ...</a></li>
<li><a href="https://www.yahoo.com/news/politics/articles/reform-uk-says-crypto-billionaires-041839986.html?fr=sycsrp_catchall">Reform UK says crypto-billionaires want 'nothing' for £72m ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#politics`, `#campaign-finance`, `#UK`, `#regulation`

---

<a id="item-10"></a>
## [印度最富裕邦探索资产代币化以筹集基建资金](https://www.coindesk.com/markets/2026/09/11/india-s-richest-state-is-exploring-tokenizing-its-own-assets-to-fund-new-infrastructure) ⭐️ 6.0/10

据 CoinDesk 2026 年 9 月 11 日报道，印度最富裕的邦正在探索将自身资产代币化，以此为新的基础设施项目筹集资金。该举措目前仍处于探索阶段，尚未公布具体的技术框架或发行时间表。 这表明地方政府对利用基于区块链的资产代币化作为替代性公共融资工具的兴趣日益增长，可能为现实世界资产（RWA）基础设施开辟新市场。如果成功，它可能成为印度其他邦以及寻求不单纯依赖传统债务或多边贷款来为基建融资的新兴市场政府的范本。 该报道未说明将代币化哪些资产、使用哪条区块链，也未提及如何满足印度证券法和税法的监管合规要求。公共基础设施资产代币化通常涉及在区块链上创建所有权或收益权的数字表示，这会引发关于托管、投资者资格和法律可执行性的问题。

rss · CoinDesk · Sep 11, 15:17

**背景**: 资产代币化是指将资产所有权登记在区块链基础设施上，使其能够受益于更高效的结算以及与智能合约的交互。各国政府和金融机构越来越多地探索代币化债券和现实世界资产，美联储和普华永道等机构已研究此类工具的透明度与可行性。印度一直是数字公共基础设施的主要采用者，尽管其对加密资产的态度历来较为谨慎。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://chainscorelabs.com/guides/blockchain-for-government-and-public-services/transparent-procurement/how-to-implement-asset-tokenization-for-public-infrastructure-procurement">How to Implement Asset Tokenization for Public Infrastructure</a></li>
<li><a href="https://www.federalreserve.gov/econres/notes/feds-notes/tokenized-assets-on-public-blockchains-how-transparent-is-the-blockchain-20240403.html">The Fed - Tokenized Assets on Public Blockchains: How ...</a></li>
<li><a href="https://research.grayscale.com/reports/public-blockchains-and-the-tokenization-revolution">Public Blockchains and the Tokenization Revolution | Grayscale</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#infrastructure`, `#public finance`, `#India`

---

<a id="item-11"></a>
## [GPT-6 Astra 用户称 OpenAI 最新模型变笨了](https://decrypt.co/378101/gpt-6-astra-openai-model-dumber-nerfed) ⭐️ 6.0/10

OpenAI 发布 GPT-6 Astra 一周后，用户纷纷抱怨该模型被“削弱”（nerfed），即其质量相比刚发布时似乎出现了下降。这与 OpenAI 上一款模型在 7 月经历的类似周期如出一辙，当时用户也在发布后不久报告了性能下滑。 这种发布后模型性能下降的反复出现，引发了人们对 AI 开发透明度和一致性的担忧，既影响依赖这些模型的普通用户，也影响在其之上构建应用的开发者。它凸显了一个更广泛的行业问题：AI 实验室在周期中静默更新模型，却没有清晰记录所涉及的权衡。 这些抱怨集中在感知到的质量退步上，尤其是在边缘案例以及需要在大上下文中进行持续多步推理的任务上。OpenAI、Anthropic 和 Google 都承认模型行为会随时间变化，但大多数实验室对周期中的更新提供的文档极少，让用户只能自行猜测发生了什么变化。

rss · Decrypt · Sep 12, 16:01

**背景**: 模型退化指的是 AI 模型在部署后观察到的准确性、一致性或推理能力下降。在大语言模型的语境中，“nerfing”（削弱）是用户用来形容他们认为模型能力被有意或无意降低的通俗说法。这一现象与“模型崩溃”不同，后者描述的是因使用 AI 生成数据训练而导致的理论上的长期退化。围绕“削弱”的争议主要在于透明度：用户想知道变化何时发生以及做出了哪些权衡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://3zebras.com/tech/are-ai-labs-secretly-nerfing-their-models-the-data-behind-the-claims/15561/">Are AI Labs Nerfing Models? Data Behind the Claims</a></li>
<li><a href="https://grokipedia.com/page/AI_model_performance_degradation">AI model performance degradation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Model_collapse">Model collapse - Wikipedia</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#GPT-6`, `#model degradation`, `#AI news`, `#user complaints`

---

<a id="item-12"></a>
## [ChatGPT Images 2.5 对决 Nano Banana 2：六大维度横向评测](https://decrypt.co/377998/chatgpt-images-2-5-vs-nano-banana-2-review) ⭐️ 6.0/10

Decrypt 发布了一篇横向评测，将 OpenAI 最新推出的 ChatGPT Images 2.5 与 Google 的 Nano Banana 2 放在一起，从六个维度进行对比。OpenAI 将 ChatGPT Images 2.5 称为其全新的最先进图像模型，主打更锐利的细节、更精准的编辑和更快的生成速度。 这两款模型都处于 AI 图像生成的前沿，因此直接对比能帮助开发者、设计师和内容创作者判断哪款工具更适合自己的工作流。这次评测也反映出 OpenAI 与 Google 在多模态生成领域日益激烈的竞争，画质、编辑精度和速度正是关键的差异化因素。 此次对比涵盖六个评测维度，但摘要并未逐一列出；评测侧重实际使用场景的基准测试，而非单一的核心指标。Nano Banana 2 基于 Google 的 Gemini 3.1 Flash 图像模型，主打快速生成、准确的文字渲染以及出色的人物一致性。

rss · Decrypt · Sep 12, 13:01

**背景**: AI 图像生成模型可以把文字提示转化为图片，正越来越多地用于设计、营销和创意工作。OpenAI 的 ChatGPT Images 系列是 ChatGPT 内置的图像生成能力，而 Google 的 Nano Banana 则是其基于 Gemini 的图像模型的昵称。此类横向评测很常见，因为每次新版本发布都会宣称在细节、编辑和速度上有所提升，用户需要实用的选型参考。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/introducing-chatgpt-images-2-5/">Introducing ChatGPT Images 2.5 | OpenAI</a></li>
<li><a href="https://kie.ai/nano-banana-2">Nano Banana 2 API - Gemini 3.1 Flash 4K Image from $0.04 | Kie AI</a></li>
<li><a href="https://www.medeo.app/models/nano-banana-2">Nano Banana 2 AI Image Generator Online | Medeo</a></li>

</ul>
</details>

**标签**: `#AI image generation`, `#model comparison`, `#OpenAI`, `#Google`, `#benchmarking`

---

<a id="item-13"></a>
## [2025 年律师事务所网络攻击近乎翻倍，被盗文件流入暗网](https://decrypt.co/378094/cyberattacks-law-firms-stolen-documents-dark-web) ⭐️ 6.0/10

Greenberg Traurig 表示有被盗文件被发布到暗网上，而 BakerHostetler 记录显示，2025 年针对律师事务所的网络事件数量较上一年近乎翻倍。 律师事务所掌握着最敏感的客户信息，包括诉讼策略和企业交易数据，因此数据泄露激增会威胁客户机密与律师-客户保密特权，并可能在法律行业引发监管处罚和集体诉讼。 被盗资料被发布在暗网上，即只能通过 Tor 等工具访问的互联网加密部分，而且这些数据来自两家律师事务所各自的报告，而非统一的集中统计。

rss · Decrypt · Sep 11, 21:45

**背景**: 暗网是托管在 Tor 等覆盖网络上的网络内容，需要特殊软件或授权才能访问，常被用于匿名交易被盗数据。律师事务所因汇集众多企业客户的机密文件而成为有吸引力的攻击目标，近年来大型律所及其法律科技供应商屡屡发生数据泄露事件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dark_web">Dark web</a></li>
<li><a href="https://proton.me/blog/what-is-dark-web">What the dark web is and how you can access it | Proton</a></li>
<li><a href="https://www.law.com/americanlawyer/2026/09/09/data-breaches-at-mcdermott-quinn-cap-cyber-siege-summer-/">Data Breaches at McDermott, Quinn Cap Cyber-Siege Summer</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#law firms`, `#data breach`, `#dark web`, `#cyberattacks`

---

<a id="item-14"></a>
## [Blockstream 拒绝为 Liquid 网络被盗的 4700 万美元比特币支付赎金](https://decrypt.co/377959/blockstream-refuses-ransom-for-return-of-47m-in-bitcoin-from-liquid-hack-it-is-theft) ⭐️ 6.0/10

Blockstream 拒绝为归还 Liquid 网络黑客事件中仍未追回的 598.5 枚比特币（约 4700 万美元）支付赎金，称该事件属于盗窃，并威胁若资金未归还将采取执法行动。Liquid 网络在漏洞被利用后已恢复交易，但作为恢复工作的一部分，peg-out（锚定转出）功能仍处于禁用状态。 这是影响比特币二层网络的最大安全事件之一，Blockstream 拒绝谈判为加密基础设施运营商如何应对攻击者树立了先例。peg-out 功能仍被禁用意味着用户无法自由将 L-BTC 转回比特币主链，这引发了人们对联邦侧链模型信任度的担忧。 该漏洞源于 Blockstream 的 Elements 代码库中的一个软件缺陷，使攻击者凭空铸造了近 4000 枚无背书的 L-BTC，并将其 peg-out 换成真实的比特币，耗尽了 Liquid 联邦储备约 95% 的资金。经谈判后约 3400 枚 BTC 被归还，仍有 598.5 枚 BTC 未追回，据称攻击者留下了一条声称对此负责的链上消息。

rss · Decrypt · Sep 11, 14:17

**背景**: Liquid 是由 Blockstream 运营的比特币二层侧链，允许用户将 BTC 作为 L-BTC 转移到联邦网络上，以实现更快、更保密的交易。peg-in/peg-out 机制由一个持有真实 BTC 的联邦钱包支撑，因此一个能铸造无背书 L-BTC 的漏洞可以被兑换成真实的比特币。此次事件凸显了联邦侧链相较于比特币基础层的安全假设差异。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bitrue.com/blog/liquid-network-hack-320m-bitcoin-explained">Liquid Network Hack Explained: What Happened to $320M?</a></li>
<li><a href="https://cryptobriefing.com/liquid-network-exploit-slowmist-analysis/">SlowMist details Liquid Network exploit, attacker mints 3,998 ...</a></li>
<li><a href="https://blockonomi.com/liquid-network-hack-attackers-return-270m-in-bitcoin-after-320m-exploit/">Liquid Network Hack: Attackers Return $270M in Bitcoin After ...</a></li>

</ul>
</details>

**标签**: `#bitcoin`, `#blockchain-security`, `#hacking`, `#ransomware`, `#cryptocurrency`

---

<a id="item-15"></a>
## [欧盟监管机构警告预测市场存在内幕交易](https://decrypt.co/377947/eu-regulator-says-prediction-markets-are-rife-with-inside-trading) ⭐️ 6.0/10

欧洲证券和市场管理局（ESMA）提出担忧，认为预测市场“充斥着内幕交易”，并质疑 Kalshi 和 Polymarket 等平台为何封锁部分欧盟国家却不封锁其他国家，同时指出 VPN 可以绕过这些封锁。ESMA 还表示，主要预测平台缺乏欧盟授权。 这标志着欧盟对预测市场的监管审查日益加强，可能导致更严格的规则或执法行动，从而影响 Kalshi 和 Polymarket 等平台在欧洲市场的运营方式。这也凸显了快速增长的事件驱动交易平台与旨在保护投资者和维护市场完整性的现有金融法规之间的紧张关系。 ESMA 特别指出，Kalshi 和 Polymarket 封锁了部分欧盟国家的用户，但没有封锁其他国家，而且 VPN 可用于绕过这些地理限制。监管机构还指出，这些主要预测平台缺乏欧盟授权，这引发了对其在欧盟金融规则下法律地位的质疑。

rss · Decrypt · Sep 11, 12:06

**背景**: 预测市场是用户就未来事件结果（如选举、经济指标或体育赛事）交易合约的平台。Kalshi 是一家受美国监管的交易所，而 Polymarket 是一个基于加密货币的平台，增长迅速。ESMA 是负责证券监管和投资者保护的欧盟机构，它与各国监管机构协调，确保欧盟金融法律的统一适用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/European_Securities_and_Markets_Authority">European Securities and Markets Authority - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket - Wikipedia</a></li>
<li><a href="https://kalshi.com/">Kalshi - Prediction Market for Trading the Future</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#regulation`, `#insider trading`, `#EU`, `#ESMA`

---

<a id="item-16"></a>
## [阿尔伯克基禁止比特币 ATM，要求运营商 45 天内拆除](https://decrypt.co/377939/albuquerque-bans-bitcoin-atms-giving-operators-45-days-to-remove-them) ⭐️ 6.0/10

阿尔伯克基市已通过一项针对比特币 ATM 及其他加密货币自助终端的禁令，要求运营商在 45 天内将这些机器从该市移除。一位市议员表示，阿尔伯克基 90%的加密货币终端交易与欺诈有关，并称这些机器是犯罪的渠道。 这是美国市政层面对加密货币自助终端采取的最严厉行动之一，随着对加密货币相关欺诈的审查加强，可能促使其他城市效仿。此举直接影响比特币 ATM 运营商及其用户，也加剧了关于如何在加密货币可及性与消费者保护之间取得平衡的争论。 该禁令针对加密货币自助终端，这类机器允许用户用现金或借记卡购买比特币及其他数字资产，部分还支持双向买卖功能。运营商仅有 45 天时间遵守规定，而该市给出的理由是基于当地 90%的终端交易与欺诈相关的说法。

rss · Decrypt · Sep 11, 10:10

**背景**: 比特币 ATM（也称 BTM 或加密货币 ATM）是一种实体自助终端，允许人们用现金兑换比特币，有时也可将加密货币卖出换取现金。由于这类交易往往相对匿名、不可逆且手续费较高，它们已成为诈骗分子针对受害者（尤其是老年人）的常用工具。各地对这些机器的监管差异很大，出于 KYC、反洗钱和消费者保护方面的担忧，许多地方的监管正在收紧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bitcoin_ATM">Bitcoin ATM</a></li>
<li><a href="https://www.activeintel.com/crypto-kiosk-scams-how-fraudsters-target-victims/">Crypto Kiosk Scams: How Fraudsters... - Active Intel Investigations</a></li>
<li><a href="https://www.gate.com/learn/articles/what-is-crypto-atm-regulation">What Is Crypto ATM Regulation ? KYC, AML and... | Gate Learn</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#bitcoin-atm`, `#fraud`, `#policy`

---