---
layout: default
title: "Horizon Summary: 2026-05-31 (ZH)"
date: 2026-05-31
lang: zh
---

> From 66 items, 20 important content pieces were selected

---

1. [微软将把 Office 2019/2021 Mac 版转为只读模式](#item-1) ⭐️ 8.0/10
2. [Voxel Space 算法详解](#item-2) ⭐️ 8.0/10
3. [Zig ELF 链接器改进提升迭代速度](#item-3) ⭐️ 8.0/10
4. [OpenRouter 完成 1.13 亿美元 B 轮融资](#item-4) ⭐️ 8.0/10
5. [研究显示 AI 模型在 67%的事实上存在分歧](#item-5) ⭐️ 8.0/10
6. [CFTC 批准 Kalshi 推出比特币永续期货](#item-6) ⭐️ 8.0/10
7. [领域专业知识仍是真正的竞争优势](#item-7) ⭐️ 7.0/10
8. [Shantell Sans：一款带有形式感滑块的变量字体](#item-8) ⭐️ 7.0/10
9. [埃森哲以 12 亿美元收购 Ookla，加强网络智能](#item-9) ⭐️ 7.0/10
10. [OpenBSD 的 openrsync：一个安全的 rsync 实现](#item-10) ⭐️ 7.0/10
11. [XRP 账本提案阻止闪电贷攻击](#item-11) ⭐️ 7.0/10
12. [CertiK CEO 警告大规模部署 AI 代理可能引发灾难](#item-12) ⭐️ 7.0/10
13. [Paxos 获 SEC 批准，用区块链清算美股](#item-13) ⭐️ 7.0/10
14. [TrapDoor 攻击瞄准 Solana、Sui 和 Aptos 钱包](#item-14) ⭐️ 7.0/10
15. [AI 提示注入：劫持聊天机器人的隐藏威胁](#item-15) ⭐️ 7.0/10
16. [Cosmos 生态 Gravity Bridge 因密钥泄露损失 540 万美元](#item-16) ⭐️ 7.0/10
17. [Base 在主网上启动 Azul 升级，提升去中心化](#item-17) ⭐️ 7.0/10
18. [比特币的量子风险可能超出钱包密钥](#item-18) ⭐️ 6.0/10
19. [Kalshi 因预测市场禁令起诉明尼苏达州](#item-19) ⭐️ 6.0/10
20. [法院冻结 Zama cUSDC 合约中 1260 万美元](#item-20) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [微软将把 Office 2019/2021 Mac 版转为只读模式](https://consumerrights.wiki/w/Microsoft_Office_2019_and_2021_for_Mac_view-only_conversion_(2026)) ⭐️ 8.0/10

微软计划将永久授权的 Office 2019 和 2021 Mac 版转换为只读模式，用户在特定日期后将无法编辑或创建文档。 此举削弱了永久软件所有权的概念，可能迫使用户转向订阅制，引发广泛的消费者抵制和法律担忧。 该变更影响 Office 2019 和 2021 Mac 版，这些版本以永久许可证形式销售。转换后，用户只能查看文档，无法编辑、保存或创建新文档。

hackernews · antipurist · May 30, 23:26 · [社区讨论](https://news.ycombinator.com/item?id=48341578)

**背景**: 永久许可证允许用户一次性购买后无限期使用软件，而订阅制则需要持续付费。微软一直在推动订阅制 Office 365，此举进一步施压用户迁移。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://talk.tidbits.com/t/office-2019-switching-to-view-only-mode-what-to-do/33495">Office 2019 switching to view - only mode —what to do? - TidBITS Talk</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了愤怒，呼吁抵制并转向 LibreOffice 等免费替代品。一些人根据澳大利亚消费者法提出法律担忧，另一些人推测这一变化是微软为了防止 AI 代理使用离线许可证。

**标签**: `#Microsoft`, `#software licensing`, `#consumer rights`, `#Office`, `#digital ownership`

---

<a id="item-2"></a>
## [Voxel Space 算法详解](https://s-macke.github.io/VoxelSpace/) ⭐️ 8.0/10

一篇关于 1992 年游戏《Comanche》中使用的 Voxel Space 渲染算法的详细技术解释已发布，包含在线演示和源代码。 该算法在当时具有开创性，能在有限硬件上实现逼真的地形渲染，其解释有助于保存和理解复古图形技术。 该算法使用高度图和颜色图，通过从后向前绘制垂直线（画家算法）来高效渲染地形。

hackernews · davikr · May 30, 14:25 · [社区讨论](https://news.ycombinator.com/item?id=48336564)

**背景**: Voxel Space 是 NovaLogic 为 1992 年游戏《Comanche: Maximum Overkill》开发的专有体素引擎。与真正将 3D 空间等分的体素不同，它采用高度图方法，将地形渲染为一组棱柱。该引擎完全用汇编语言编写，是首批使用体素技术的商业飞行模拟器之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://s-macke.github.io/VoxelSpace/">Voxel Space | VoxelSpace</a></li>
<li><a href="https://en.wikipedia.org/wiki/Comanche_(video_game_series)">Comanche (video game series) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Voxel">Voxel - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者指出该算法在技术上属于高度图而非真正的体素，但称赞其历史意义。一些人分享了个人实现和受该游戏启发的测试方法。

**标签**: `#voxel rendering`, `#game development`, `#retro computing`, `#algorithms`, `#graphics`

---

<a id="item-3"></a>
## [Zig ELF 链接器改进提升迭代速度](https://ziglang.org/devlog/2026/#2026-05-30) ⭐️ 8.0/10

Zig 的最新开发日志详细介绍了其自托管 ELF 链接器的重大改进，专注于更快的增量链接以实现快速开发迭代。 这一进展使 Zig 更接近成为可行的 C 语言替代品，使开发者能够以接近解释型语言的速度进行迭代，同时保持类似 C 的性能。 这些改进是 Zig 自托管链接器的一部分，该链接器与自托管编译器紧密耦合，并处理多种输出格式，包括 ELF、Mach-O、COFF 和 WebAssembly。

hackernews · kristoff_it · May 30, 17:29 · [社区讨论](https://news.ycombinator.com/item?id=48338673)

**背景**: Zig 是一种系统编程语言，旨在通过提供编译时代码执行和无隐藏控制流等现代特性来取代 C。ELF（可执行与可链接格式）是 Linux 及类 Unix 系统上可执行文件的常见二进制格式。链接器将编译后的目标文件组合成最终的可执行文件，而增量链接通过仅重新链接更改的部分来加速开发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Executable_and_Linkable_Format">Executable and Linkable Format - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language) - Wikipedia</a></li>
<li><a href="https://ziglang.org/">Home ⚡ Zig Programming Language</a></li>

</ul>
</details>

**社区讨论**: 社区成员对 Zig 作为 C 语言替代品的潜力表示兴奋，一些人指出改进后的链接器实现了与 JavaScript 或 Python 相当的迭代速度。其他人则讨论了将 Zig 用作内存安全语言的转译目标，或将 Raku 的 MOARVM 等运行时移植到 Zig。

**标签**: `#Zig`, `#linker`, `#compiler`, `#systems programming`, `#ELF`

---

<a id="item-4"></a>
## [OpenRouter 完成 1.13 亿美元 B 轮融资](https://openrouter.ai/announcements/series-b) ⭐️ 8.0/10

OpenRouter，一个统一的大语言模型 API 代理，宣布完成 1.13 亿美元的 B 轮融资。该公司计划利用这笔资金继续通过单一接口提供对多个 LLM 的低摩擦访问。 此次融资验证了 OpenRouter 在快速发展的 LLM 生态系统中作为关键基础设施的角色，开发者需要便捷地访问多个模型。这也表明投资者对代理模式作为可持续业务的信心，尤其是在模型提供商不断涌现的背景下。 据联合创始人兼 COO numlocked 称，融资后 OpenRouter 仍由创始人领导和控制。该公司对其代理服务收取少量附加费（例如，对 Claude Opus 等昂贵模型收取 5%），一些社区成员认为这种便利性可以接受。

hackernews · freeCandy · May 30, 17:27 · [社区讨论](https://news.ycombinator.com/item?id=48338660)

**背景**: OpenRouter 是一项提供统一 API 以访问来自不同提供商的数十种大语言模型的服务，消除了开发者需要与每个提供商的独特 API 集成的需求。它还提供账单上限等功能，帮助用户在生产环境中运行 AI 应用时控制成本。LLM 领域碎片化严重，存在许多竞争模型和提供商，这使得 OpenRouter 等工具对于实验和部署非常有价值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Aculeasis/openrouter-proxy">GitHub - Aculeasis/openrouter-proxy · GitHub</a></li>
<li><a href="https://github.com/nexon33/Openrouter-Proxy-Server">GitHub - nexon33/Openrouter-Proxy-Server · GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞 OpenRouter 的低摩擦模型访问和账单上限功能，simonw 指出这些是重要的附加值。然而，一些人质疑其商业模式，minimaxir 指出了对昂贵模型的附加费问题，tom1337 则询问缺乏开源代码的情况，认为“OpenRouter”这个名称可能具有误导性。

**标签**: `#AI`, `#funding`, `#LLM`, `#API`, `#infrastructure`

---

<a id="item-5"></a>
## [研究显示 AI 模型在 67%的事实上存在分歧](https://decrypt.co/369480/ai-models-disagree-fact-checking-two-thirds-study) ⭐️ 8.0/10

一项新研究让五个领先的 AI 模型对 1000 个真实世界的事实主张进行核查，发现它们在 67%的主张上存在分歧，凸显了事实核查能力的严重不一致性。 这一发现削弱了人们对 AI 系统在需要事实准确性的任务（如新闻、教育和研究）中的信任，并引发了对在高风险环境中部署这些模型的担忧。 该研究使用了来自不同领域的 1000 个主张，评估了包括 GPT-4、Claude 和 Gemini 在内的模型，分歧定义为任何判决（真、假或不确定）上的差异。

rss · Decrypt · May 29, 17:26

**背景**: 前沿 AI 模型是最先进的通用模型，经过巨大的计算预算训练，能够在多个领域超越现有技术水平。事实核查是一个关键应用，一致性对于可靠性至关重要。此前的研究也显示 AI 驱动的搜索引擎存在高错误率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wired.com/story/fact-checking-ai/">I’m a Professional Fact-Checker. AI Is Wrong More Often Than You Think | WIRED</a></li>

</ul>
</details>

**标签**: `#AI reliability`, `#fact-checking`, `#large language models`, `#AI research`

---

<a id="item-6"></a>
## [CFTC 批准 Kalshi 推出比特币永续期货](https://decrypt.co/369465/cftc-approves-bitcoin-perpetual-futures-kalshi) ⭐️ 8.0/10

美国商品期货交易委员会（CFTC）已发布命令，允许受监管的预测市场 Kalshi 向美国客户提供比特币永续期货合约。 这标志着美国加密货币衍生品的监管里程碑，可能为更广泛的机构采用和更多受监管的加密交易产品铺平道路。 Kalshi 将从与比特币价格挂钩的合约开始，该批准也为 Coinbase 等其他平台提供类似产品打开了大门。

rss · Decrypt · May 29, 15:00

**背景**: 永续期货合约是一种没有到期日的金融衍生品，允许交易者利用杠杆对价格变动进行投机。与传统期货不同，它们不需要在固定日期结算。Kalshi 是一个受联邦监管的预测市场平台，主要专注于事件合约，但此次批准将其业务扩展至加密货币衍生品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kalshi">Kalshi - Wikipedia</a></li>
<li><a href="https://www.kraken.com/hu/learn/trading/perpetual-futures-contracts">What are perpetual futures contracts ? | Kraken</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#derivatives`, `#bitcoin`, `#CFTC`

---

<a id="item-7"></a>
## [领域专业知识仍是真正的竞争优势](https://www.brethorsting.com/blog/2026/05/domain-expertise-has-always-been-the-real-moat/) ⭐️ 7.0/10

一篇博客文章指出，领域专业知识才是真正的护城河，而非 AI 工具，并通过 vibe coding 失败的例子说明缺乏领域知识会导致有缺陷的应用。 随着 AI 编码工具的普及，这一讨论重新聚焦于深度领域知识不可替代的价值，影响开发者和公司对技能和工具的投资方式。 文章强调，vibe coding（不加理解地接受 AI 生成的代码）可能产生看似功能正常但在数据库设计或逻辑上存在严重缺陷的应用，只有领域专家才能发现这些问题。

hackernews · aaronbrethorst · May 30, 20:40 · [社区讨论](https://news.ycombinator.com/item?id=48340411)

**背景**: Vibe coding 是近期的一种趋势，开发者用自然语言向 AI 描述任务，AI 自动生成代码，开发者往往不进行完整审查或理解。随着 GPT-4 和 Claude 等强大 LLM 的兴起，这种方法变得流行。然而，批评者认为，当用户缺乏领域专业知识时，这种方法可能导致脆弱或不正确的软件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/vibe-coding">What is Vibe Coding? | IBM</a></li>

</ul>
</details>

**社区讨论**: 评论者大多同意领域专业知识至关重要，有些人指出软件工程本身就是一个领域。其他人则对 AI 时代关于开发者价值何在的不断变化的说法表示沮丧。

**标签**: `#AI`, `#software engineering`, `#domain expertise`, `#vibe coding`

---

<a id="item-8"></a>
## [Shantell Sans：一款带有形式感滑块的变量字体](https://shantellsans.com/process) ⭐️ 7.0/10

Shantell Sans 是一款新设计的变量字体，具有独特的“形式感”轴，用户可平滑调整字体外观从随意到正式。该字体已在 Google Fonts 上发布，并因其设计和可访问性而广受好评。 这款字体展示了变量字体技术的创意潜力，特别是形式感滑块，提供了前所未有的排版控制。其积极反响，尤其是来自阅读障碍用户的反馈，凸显了包容性设计在字体排印中的重要性。 形式感轴是一个连续范围，在非正式和正式字形之间插值，使其成为设计师的多功能工具。该字体以单个变量字体文件提供，减小了文件大小并提高了网页性能。

hackernews · aleda145 · May 30, 22:06 · [社区讨论](https://news.ycombinator.com/item?id=48341062)

**背景**: 变量字体是一种字体格式，可在单个文件中存储多种设计变体（如字重、字宽或倾斜度），允许在样式之间平滑插值。形式感轴是一项创新，可调整字体的正式程度，这一概念在变量字体中很少见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Variable_font">Variable font</a></li>
<li><a href="https://fonts.google.com/knowledge/introducing_type/introducing_variable_fonts">Introducing variable fonts – Fonts Knowledge - Google Fonts</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞形式感滑块是变量字体轴最酷的用途之一，许多人注意到字体的美观性和可访问性优势，尤其是对阅读障碍读者。一些人表示希望有等宽版本。

**标签**: `#typography`, `#variable fonts`, `#design`, `#accessibility`

---

<a id="item-9"></a>
## [埃森哲以 12 亿美元收购 Ookla，加强网络智能](https://newsroom.accenture.com/news/2026/accenture-to-acquire-ookla-to-strengthen-network-intelligence-and-experience-with-data-and-ai-for-enterprises) ⭐️ 7.0/10

埃森哲于 2026 年 3 月 3 日宣布以 12 亿美元收购 Ookla，后者旗下拥有 Speedtest、Downdetector、Ekahau 和 RootMetrics 等产品。 此次收购增强了埃森哲为电信和企业提供的网络智能与数据驱动服务，使其能够端到端优化对 AI 转型至关重要的 5G 和 Wi-Fi 网络。 Ookla 的数据平台每月处理超过 2.5 亿次消费者发起的测试，并辅以驾车、步行和嵌入式测试，为网络优化提供宝贵洞察。

hackernews · Garbage · May 30, 16:28 · [社区讨论](https://news.ycombinator.com/item?id=48337987)

**背景**: Ookla 以 Speedtest.net（广泛使用的网速测试工具）和 Downdetector（追踪服务中断的平台）而闻名。该公司还提供网络智能解决方案，电信运营商用以基准测试和改善网络。埃森哲是一家全球 IT 服务和咨询公司，此前已通过收购 Umlaut 等举措扩展其电信能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://newsroom.accenture.com/news/2026/accenture-to-acquire-ookla-to-strengthen-network-intelligence-and-experience-with-data-and-ai-for-enterprises">Accenture to Acquire Ookla to Strengthen Network Intelligence and Experience with Data and AI For Enterprises</a></li>
<li><a href="https://www.ookla.com/solutions/competitive-network-intelligence">Competitive Benchmarking & Network Intelligence Solutions | Ookla®</a></li>
<li><a href="https://en.wikipedia.org/wiki/Downdetector">Downdetector - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，这笔交易本质上是一次数据收购，Ookla 的真正价值在于向电信运营商出售网络性能数据，年费可达六位数。有人对高价表示惊讶，也有人强调 Ookla 在面向消费者的工具之外拥有深厚的业务。

**标签**: `#acquisition`, `#network intelligence`, `#telecom`, `#data monetization`, `#accenture`

---

<a id="item-10"></a>
## [OpenBSD 的 openrsync：一个安全的 rsync 实现](https://github.com/kristapsdz/openrsync) ⭐️ 7.0/10

OpenBSD 团队开发了 openrsync，这是一个可移植的 rsync 文件同步工具实现，因其安全特性以及在 RPKI 验证中的应用而受到关注。 openrsync 为广泛使用的 Samba rsync 提供了一个更安全的替代方案，尤其适用于注重安全的用户和关键基础设施（如 RPKI 验证器），它利用了 OpenBSD 的 pledge 和 unveil 安全机制。 openrsync 设计为可移植，并在 OpenBSD 上包含 pledge(2) 和 unveil(2) 等安全特性，这些特性限制系统调用和文件系统访问，以减轻潜在漏洞的利用。

hackernews · sph · May 30, 10:51 · [社区讨论](https://news.ycombinator.com/item?id=48334854)

**背景**: rsync 是一种广泛使用的工具，用于跨系统高效传输和同步文件，通常通过 SSH 进行。OpenBSD 是一个注重安全的类 Unix 操作系统，以其主动安全特性（如 pledge 和 unveil）而闻名，这些特性可以对进程进行沙盒化。RPKI（资源公钥基础设施）是一种安全框架，使用加密证书来验证 BGP 路由通告，防止 IP 地址劫持。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.arin.net/resources/manage/rpki/">Resource Public Key Infrastructure (RPKI) - American Registry for Internet Numbers</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenBSD_security_features">OpenBSD security features - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员报告称，openrsync 随着时间的推移有所改进，但与 Samba rsync 相比仍缺少某些功能，例如处理某些路径行为。其他人则强调其作为 RPKI 验证器的一部分进行开发，并指出 Gokrazy 团队存在一个基于 Go 的 rsync 实现。

**标签**: `#rsync`, `#OpenBSD`, `#security`, `#file synchronization`, `#open source`

---

<a id="item-11"></a>
## [XRP 账本提案阻止闪电贷攻击](https://www.coindesk.com/tech/2026/05/29/xrp-ledger-s-new-proposal-blocks-the-flash-loan-attacks-costing-defi-hundreds-of-millions) ⭐️ 7.0/10

一项针对 XRP 账本的新提案旨在阻止闪电贷攻击，这类攻击已在 DeFi 协议中造成数亿美元的损失。 如果实施，该提案可以通过消除一种常见的攻击向量来显著增强 DeFi 安全性，可能节省数百万美元并恢复用户信心。 该提案引入了一种机制，防止在单笔交易中原子性地借入和偿还大额资金，而这正是闪电贷攻击的核心。

rss · CoinDesk · May 31, 02:30

**背景**: 闪电贷攻击通过在没有抵押品的情况下借入大量加密货币，并在单笔交易中操纵价格或耗尽流动性来利用 DeFi 协议。这些攻击已使 DeFi 生态系统损失数亿美元。XRP 账本是一个专为支付和去中心化应用设计的区块链。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://web3.okx.com/fi/learn/flash-loan-attack-explained">What is a Flash Loan Attack ? | OKX Wallet</a></li>
<li><a href="https://coinmarketcap.com/academy/article/what-are-flash-loan-attacks">What Are Flash Loan Attacks ? | CoinMarketCap</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#XRP Ledger`, `#blockchain`

---

<a id="item-12"></a>
## [CertiK CEO 警告大规模部署 AI 代理可能引发灾难](https://www.coindesk.com/tech/2026/05/29/mass-deployment-of-ai-agents-is-a-disaster-waiting-to-happen-says-certik-ceo) ⭐️ 7.0/10

区块链安全公司 CertiK 的 CEO 顾荣辉警告称，在没有适当隔离和测试的情况下大规模部署 AI 代理可能导致灾难性后果，包括未经授权访问个人数据和数字资产。 随着 AI 代理变得更加自主并被广泛使用，大规模危害的可能性显著增加，影响个人用户和整个数字生态系统。这一警告凸显了制定强有力安全措施和监管框架的紧迫性。 顾荣辉特别建议在测试期间隔离 AI 代理，以防止它们访问关键个人信息或数字资产。他还指出，攻击者越来越多地利用 AI 在资源上超越防御者，使安全形势更加严峻。

rss · CoinDesk · May 29, 15:31

**背景**: AI 代理是能够代表用户执行任务的自主软件程序，例如管理财务或做出决策。与传统聊天机器人不同，它们可以直接访问系统和数据，因此一旦失败或被攻破，后果更为严重。CertiK 是一家知名的区块链安全公司，以审计智能合约和去中心化应用而闻名。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://coinspectator.com/other/2026/05/29/mass-deployment-of-ai-agents-is-a-disaster-waiting-to-happen-says-certik-ceo/">Mass deployment of AI agents is a disaster waiting to happen, says CertiK CEO – CoinSpectator – Real-time Cryptocurrency News</a></li>
<li><a href="https://www.theblock.co/post/401280/unfair-game-certik-ceo-defi-attackers-using-ai-outspend-defenders">'It's an unfair game': CertiK CEO says DeFi attackers using AI to outspend defenders | The Block</a></li>
<li><a href="https://toolwise.ai/news/ai-agents-testing-business-deployment-risks">AI Agent Testing Risks for Small Business | ToolWise | ToolWise</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#AI agents`, `#risk management`, `#deployment`

---

<a id="item-13"></a>
## [Paxos 获 SEC 批准，用区块链清算美股](https://www.coindesk.com/policy/2026/05/29/paxos-is-first-blockchain-firm-to-provide-settlement-and-clearing-services-following-sec-approval) ⭐️ 7.0/10

Paxos 成为首家获得 SEC 批准注册为清算机构的区块链原生公司，从而能够在区块链基础设施上清算和结算美股交易。 这一里程碑标志着加密货币与传统金融的重大融合，有望通过消除中介和自动化流程来降低资本市场成本并提高效率。 此次批准结束了始于 2019 年无异议函的七年监管马拉松，Paxos 现已根据 SEC 的 17A 框架注册。

rss · CoinDesk · May 29, 12:28

**背景**: 清算和结算是确保证券交易正确完成的交易后流程。传统上，这些功能由 DTCC 等中心化实体处理。区块链技术提供了一种去中心化的替代方案，可以降低成本、加快结算速度并提高透明度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://coinmarketcap.com/academy/article/+sec-approves-paxos-blockchain-clearing-agency">SEC Approves Paxos as First Blockchain Clearing Agency</a></li>
<li><a href="https://www.binance.com/en/square/post/05-29-2026-paxos-gains-sec-approval-to-clear-u-s-stocks-on-blockchain-328386303699970">Paxos Gains SEC Approval to Clear U.S. Stocks on Blockchain</a></li>
<li><a href="https://phemex.com/academy/paxos-sec-approval-google-trends-analysis">Paxos Crypto SEC Approval: Smart Money Moves After Breakout</a></li>

</ul>
</details>

**社区讨论**: 社区反应极为积极，许多人称这是现实世界资产代币化的“重大”一步。一些人好奇 Paxos 将使用何种具体区块链基础设施以及如何与现有市场系统集成。

**标签**: `#blockchain`, `#SEC`, `#fintech`, `#regulation`, `#Paxos`

---

<a id="item-14"></a>
## [TrapDoor 攻击瞄准 Solana、Sui 和 Aptos 钱包](https://www.coindesk.com/tech/2026/05/29/solana-sui-and-aptos-wallet-data-targeted-in-trapdoor-package-attack) ⭐️ 7.0/10

一个名为 TrapDoor 的供应链攻击活动被发现，在 npm、PyPI 和 Crates.io 上部署了 34 个以上的恶意包，针对 Solana、Sui 和 Aptos 网络上的钱包数据和凭证。 此次攻击威胁到三个主要区块链生态系统中加密开发者和用户的安全，可能导致资金被盗和云凭证泄露。 这些恶意包伪装成合法的开发者工具，如'wallet-security-checker'和'defi-risk-scanner'，该活动已被 Socket Security 标记。

rss · CoinDesk · May 29, 08:19

**背景**: 供应链攻击涉及将恶意代码注入开发者无意中下载的软件包中。在加密领域，此类攻击可能窃取私钥或钱包凭证，导致资产被盗。Solana、Sui 和 Aptos 是高性能区块链，深受开发者欢迎。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://socket.dev/blog/trapdoor-crypto-stealer-npm-pypi-crates">TrapDoor Crypto Stealer Supply Chain Attack Hits 34 Packages...</a></li>
<li><a href="https://thehackernews.com/2026/05/trapdoor-supply-chain-attack-spreads.html">TrapDoor Supply Chain Attack Spreads Credential-Stealing Malware via npm, PyPI, and CratesIO</a></li>
<li><a href="https://www.kucoin.com/news/flash/trapdoor-malware-targets-solana-sui-and-aptos-wallet-data-via-supply-chain-attack">TrapDoor Malware Targets Solana , Sui , and Aptos Wallet ... | KuCoin</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#security`, `#supply chain attack`, `#cryptocurrency`, `#wallet`

---

<a id="item-15"></a>
## [AI 提示注入：劫持聊天机器人的隐藏威胁](https://decrypt.co/resources/what-is-ai-prompt-injection-attack) ⭐️ 7.0/10

本文解释了什么是 AI 提示注入攻击、其工作原理以及为何难以防范，并指出 OpenAI 承认该问题可能永远无法完全解决。 提示注入攻击对 ChatGPT、Claude 和 Gemini 等广泛使用的 AI 聊天机器人构成严重安全风险，可能使攻击者绕过安全措施并窃取敏感数据。 提示注入是一种通过精心构造的输入来操纵 AI 模型指令的代码注入攻击，常被称为“越狱”。该攻击于 2022 年 5 月由 Jonathan Cefalu 首次确认为安全漏洞。

rss · Decrypt · May 30, 13:01

**背景**: 像 GPT-4 这样的大型语言模型（LLM）被训练为遵循提示中的指令。提示注入利用这一点，插入恶意指令覆盖原始意图，导致模型执行意外操作，如泄露私人数据或执行未授权命令。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>
<li><a href="https://owasp.org/www-community/attacks/PromptInjection">Prompt Injection | OWASP Foundation</a></li>
<li><a href="https://d2lvhbqifib4zm.cloudfront.net/blog/prompt-injection-attack/">What is a prompt injection attack , and how to prevent it</a></li>

</ul>
</details>

**标签**: `#AI security`, `#prompt injection`, `#chatbots`, `#LLM vulnerabilities`

---

<a id="item-16"></a>
## [Cosmos 生态 Gravity Bridge 因密钥泄露损失 540 万美元](https://www.theblock.co/post/403108/cosmos-based-gravity-bridge-drained-of-5-4-million-in-suspected-key-compromise-researchers-say?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

基于 Cosmos 的 Gravity Bridge 疑似因密钥泄露被盗 540 万美元，攻击者窃取了 USDC、以太币、USDT 和 PAYG 代币，并通过 ChangeNow 和 Binance 洗钱。 此事件凸显了区块链桥中密钥泄露的持续风险，而桥是跨链互操作性的关键基础设施，可能削弱用户对 Cosmos 生态系统的信任。 据研究人员称，攻击者针对 USDC、以太币、USDT 和 PAYG 代币，并通过 ChangeNow 和 Binance 清洗了部分资金。

rss · The Block · May 30, 18:21

**背景**: Gravity Bridge 是一个基于 Cosmos 的桥，通过 IBC（跨链通信）将以太坊连接到 Cosmos 生态系统。密钥泄露是指控制桥资金的私钥被盗，通常是由于将密钥存储在云服务等不安全做法所致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gravitybridge.net/home-v2">COSMOS | Gravity Bridge</a></li>
<li><a href="https://github.com/cosmos/gravity-bridge">GitHub - cosmos / gravity - bridge : A CosmosSDK application for...</a></li>
<li><a href="https://www.halborn.com/blog/post/top-7-ways-your-private-keys-get-hacked">Top 7 Ways Your Private Keys Get Hacked</a></li>

</ul>
</details>

**标签**: `#security`, `#blockchain`, `#Cosmos`, `#bridge hack`, `#cryptocurrency`

---

<a id="item-17"></a>
## [Base 在主网上启动 Azul 升级，提升去中心化](https://www.theblock.co/post/403003/base-launches-azul-on-mainnet-pushing-coinbases-ethereum-l2-toward-full-decentralization?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Base 已在主网上部署 Azul 升级，引入了结合 TEE 和 ZK 证明的多证明系统，以及新的客户端堆栈。这是 Base 首次完全独立的升级，使其更接近 Stage 2 去中心化。 Azul 通过允许 TEE 或 ZK 证明独立完成状态最终确认，并在必要时让 ZK 证明覆盖 TEE 证明，增强了 Base 的安全性和抗审查能力。这将提款最终确认时间缩短至一天，并显著提高了网络可靠性。 该升级将 Base 整合到单一执行客户端 base-reth-node 上，并引入了基于 OP Kona 构建的新共识客户端 base-consensus。它已将空块数量减少约 99%，从每天约 200 个降至约两个，并持续支持每秒 5,000 笔交易的多次爆发。

rss · The Block · May 29, 09:31

**背景**: 像 Base 这样的以太坊 Layer 2 网络旨在扩展以太坊，同时继承其安全性。去中心化程度按阶段衡量：Stage 1 需要单一证明系统，而 Stage 2 要求多个独立证明系统以实现信任最小化。Azul 的多证明设计和新客户端堆栈是迈向 Stage 2 的关键步骤。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/403003/base-launches-azul-on-mainnet-pushing-coinbases-ethereum-l2-toward-full-decentralization">Base launches Azul on mainnet, pushing Coinbase's Ethereum L2 toward full decentralization | The Block</a></li>
<li><a href="https://thedefiant.io/news/blockchains/base-announces-azul-upgrade">Base Pushes Toward Final L2 Stage with First Independent Upgrade - "The Defiant"</a></li>
<li><a href="https://blog.base.dev/next-chapter-for-base-chain-1">A new, unified stack for Base Chain - Base Engineering Blog</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#Layer 2`, `#Decentralization`, `#Base`, `#Azul`

---

<a id="item-18"></a>
## [比特币的量子风险可能超出钱包密钥](https://www.coindesk.com/tech/2026/05/30/bitcoin-s-biggest-quantum-risk-may-not-be-wallet-keys-an-early-investor-fears-something-bigger) ⭐️ 6.0/10

一位早期比特币投资者警告称，量子计算可能威胁比特币的共识机制，而不仅仅是钱包密钥，甚至可能引发 51%攻击。 如果量子计算机能够破解比特币的工作量证明共识，整个网络的安全性可能受到损害，影响所有用户和加密货币市场。 该投资者指出，量子计算机可能更快地解决挖矿难题，使攻击者能够控制区块链。这一风险与众所周知的私钥威胁不同。

rss · CoinDesk · May 30, 05:27

**背景**: 比特币使用称为工作量证明（PoW）的共识机制，矿工竞争解决加密难题以验证交易。一旦量子计算机足够强大，它们可以更快地解决这些难题，可能使单一实体控制大部分算力，从而发动 51%攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gate.com/learn/glossary/bitcoin-consensus-mechanism">Bitcoin Consensus Mechanism : PoW Explained | Gate Glossary</a></li>
<li><a href="https://medium.com/thecapital/the-difference-between-general-and-specific-consensus-in-bitcoin-538ed8dfe696">The Difference Between General And Specific Consensus In Bitcoin</a></li>
<li><a href="https://cryptoslate.com/bitcoin-consensus-mechanisms-explained/">Bitcoin consensus mechanisms explained: Byzantine fault-tolerance</a></li>

</ul>
</details>

**标签**: `#bitcoin`, `#quantum computing`, `#cryptocurrency`, `#security`

---

<a id="item-19"></a>
## [Kalshi 因预测市场禁令起诉明尼苏达州](https://www.coindesk.com/policy/2026/05/29/kalshi-follows-cftc-in-suing-minnesota-over-law-criminalizing-prediction-markets) ⭐️ 6.0/10

受监管的预测市场交易所 Kalshi 对明尼苏达州提起诉讼，反对一项将预测市场定为犯罪的州法律，此前 CFTC 已对多个州提起类似诉讼。 这起诉讼凸显了联邦与州当局之间关于预测市场监管的持续法律斗争，可能为美国该行业的未来树立先例。 CFTC 根据《商品交易法》主张对预测市场拥有专属管辖权，并已起诉罗德岛州及其他州以阻止其执法行动。Kalshi 的诉讼与 CFTC 的立场一致。

rss · CoinDesk · May 29, 09:59

**背景**: 预测市场允许交易未来事件的结果，例如选举或经济指标。一些政府将其视为赌博，并在某些司法管辖区被禁止。CFTC 将这些市场作为商品衍生品进行监管。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cftc.gov/PressRoom/PressReleases/9206-26">CFTC Sues Trio of States to Reaffirm its Exclusive Jurisdiction Over Prediction Markets | CFTC</a></li>
<li><a href="https://www.cnbc.com/2026/05/28/cftc-sues-rhode-island-over-actions-against-prediction-markets.html">CFTC sues Rhode Island over actions against prediction markets</a></li>
<li><a href="https://www.cftc.gov/PressRoom/PressReleases/9230-26">CFTC Reaffirms Exclusive Jurisdiction Over Prediction Markets in Sixth Circuit Amicus Brief | CFTC</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#regulation`, `#crypto`, `#legal`

---

<a id="item-20"></a>
## [法院冻结 Zama cUSDC 合约中 1260 万美元](https://www.theblock.co/post/403091/court-ordered-circle-freeze-traps-12-6-million-in-zama-cusdc-contract-amid-overnight-finance-suit?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

美国法院命令 Circle 冻结 Zama 部署的 cUSDC 智能合约，锁定了 1260 万美元的用户资金，此事与针对 Overnight Finance 的诉讼有关。 这一事件凸显了 DeFi 中的法律和监管风险，法院命令可以直接影响智能合约和用户资金，可能为未来的干预开创先例。 冻结发生在 2025 年 5 月 30 日，此前美国加州北区地方法院于 5 月 29 日发布了一项仅文本的法院命令。该 cUSDC 合约已公开部署约 154 天，存款地址在存款时未显示任何制裁标记。

rss · The Block · May 30, 12:30

**背景**: cUSDC 是 USDC 的机密版本，使用加密技术隐藏交易金额。USDC 发行方 Circle 有权根据法院命令将地址或合约列入黑名单。Overnight Finance 是一个 DeFi 协议，因涉及民事诉讼导致了此次冻结。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gncrypto.news/news/circle-blacklists-zama-cusdc-freezes-12-6m-usdc/">Circle Blacklists Zama cUSDC , Freezes $12.6M USDC</a></li>
<li><a href="https://www.kucoin.com/news/flash/circle-freezes-zama-s-cusdc-contract-locking-12-6m-in-user-funds">Circle Freezes Zama's cUSDC Contract , Locking $12.6M in... | KuCoin</a></li>
<li><a href="https://thecoinomist.com/news/court-orders-circle-freeze-12-6m-zama-cusdc/">Court Orders Circle to Freeze $12.6M in Zama cUSDC</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#crypto`, `#legal`, `#smart contracts`

---