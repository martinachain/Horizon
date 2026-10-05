---
layout: default
title: "Horizon Summary: 2026-10-05 (ZH)"
date: 2026-10-05
lang: zh
---

> From 30 items, 16 important content pieces were selected

---

1. [Strata 让 Qwen 3.8 Flash Next（125B）在 RTX 4090 上以每秒 100+ token 运行](#item-1) ⭐️ 8.0/10
2. [苹果早期员工、科技纪录片人鲍勃·克林格利去世](#item-2) ⭐️ 8.0/10
3. [OKX 与纽交所母公司 ICE 申请成立合资企业，推出 24/7 代币化美股交易](#item-3) ⭐️ 8.0/10
4. [Tippett Studio 关闭后，其动画资料数字档案上线](#item-4) ⭐️ 7.0/10
5. [Zarf 博客探讨《Infidel》与内存损坏引发 HN 热议](#item-5) ⭐️ 7.0/10
6. [浏览器原生 VB6 IDE 重现经典 Visual Basic 6](#item-6) ⭐️ 7.0/10
7. [RemoveMacAI 脚本可从 macOS 27 移除 Apple Intelligence 并回收磁盘空间](#item-7) ⭐️ 7.0/10
8. [不当涂黑泄露谷歌数据中心用水与用电数据](#item-8) ⭐️ 7.0/10
9. [使用 SSH 和 Nginx 搭建自托管 HTTP 隧道](#item-9) ⭐️ 7.0/10
10. [伊尔库茨克实验室工作人员死于鼠疫，近 200 名接触者被隔离观察](#item-10) ⭐️ 7.0/10
11. [美国独立社区银行家协会起诉 OCC，指加密货币借“侧门”进入银行体系](#item-11) ⭐️ 7.0/10
12. [Zcash 25 秒出块提前上线公共测试网](#item-12) ⭐️ 6.0/10
13. [贝莱德揭示代币化将如何重塑投资组合](#item-13) ⭐️ 6.0/10
14. [特朗普任命曾起诉 Ripple 的 SEC 主席 Jay Clayton 领导 AI 推进工作](#item-14) ⭐️ 6.0/10
15. [Near Intents 发出 48 小时最后通牒后追回 380 万美元](#item-15) ⭐️ 6.0/10
16. [Chainalysis 利用 AI 将 3.87 亿美元 Bitget 黑客事件追踪至朝鲜](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Strata 让 Qwen 3.8 Flash Next（125B）在 RTX 4090 上以每秒 100+ token 运行](https://github.com/Niko1221/Strata) ⭐️ 8.0/10

一个名为 Strata 的 GitHub 项目（作者 Niko1221）展示了如何在单张消费级 RTX 4090 上运行 125B 参数的 Qwen 3.8 Flash Next 模型，速度约为每秒 100 个 token；有用户报告在 4090 搭配 128GB DDR5 和 Ryzen 7950X3D 的机器上达到 124 token/s。该项目引发社区高度关注（728 分、325 条评论），并促使用户对其进行了独立基准测试。 如果这些数据成立，就意味着一个前沿级别的 125B 稀疏 MoE 模型可以在几千美元级别的本地硬件上运行，而不再依赖数据中心 GPU，这可能会改变开发者和中小团队进行私有化、低成本推理的方式。同时，这也加剧了关于“为了把如此大的模型塞进 24GB 显存而把量化压到 4-bit 以下会损失多少质量”的争论。 Qwen 3.8 Flash Next 是一个稀疏混合专家（MoE）模型，总参数 125B，但每个 token 仅激活 6B 参数，另有 51B 参数的 n-gram 嵌入表放在加速器之外，这正是其低显存占用的关键。社区测试结果不一：有用户测得 Strata 在视觉定位任务上的中位误差为 154.8 像素，而同一 GGUF 与视觉适配器在 llama.cpp 上仅为 46.5 像素；也有用户在 32GB 的 R9700 上报告该方案比 Qwen-3.8-27B 快约两倍且更聪明。

hackernews · snehesht · Oct 4, 12:51 · [社区讨论](https://news.ycombinator.com/item?id=49953495)

**背景**: 量化（quantization）通过降低模型权重的数值精度（例如从 16-bit 降到 4-bit 甚至更低），让大模型能塞进有限的显存，但代价是精度损失。像 Qwen 3.8 Flash Next 这样的混合专家（MoE）架构每个 token 只激活一小部分参数，因此实际运行成本远低于其总参数量所暗示的水平。Strata 是一个推理项目，通过激进的量化与卸载（offloading）技术，让这类模型能在消费级 GPU 上运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/QwenLM/Qwen3.8-Flash-Next/">Qwen3.8-Flash-Next - GitHub</a></li>
<li><a href="https://arxiv.org/abs/2608.30320">[2608.30320] On the Design of Qwen3.8-Next Architecture ...</a></li>
<li><a href="https://arxiv.org/html/2411.02355">“Give Me BF16 or Give Me Death”? Accuracy-Performance Trade - Offs ...</a></li>

</ul>
</details>

**社区讨论**: 社区情绪总体热情，但对质量持怀疑态度：有评论者认为低于 4-bit 的量化不值得，宁愿在租用的 GPU 上用 4-bit 跑编码任务；也有基准对比显示，在相同权重下 Strata 的视觉定位误差约为 llama.cpp 的三倍。也有不少人持正面看法，报告在 4090 上达到 124 token/s，并称该方案对 32GB 的 R9700 是“游戏规则改变者”；还有用户希望把仓库中展示的 To Do 列表 TUI 移植到 Pi。

**标签**: `#LLM`, `#quantization`, `#consumer-hardware`, `#inference`, `#performance`

---

<a id="item-2"></a>
## [苹果早期员工、科技纪录片人鲍勃·克林格利去世](https://news.ycombinator.com/item?id=49949438) ⭐️ 8.0/10

据一位家族友人在 Hacker News 上发帖称，鲍勃·克林格利（真名马克·斯蒂芬斯，也写作 Stevens）于周六凌晨在睡梦中去世。他是苹果公司的早期员工，也是《书呆子的胜利》和《偶然的帝国》等颇具影响力的 PBS 纪录片的创作者。 克林格利的纪录片和写作塑造了一代人对个人电脑产业诞生过程的理解，他的去世在 Hacker News 上引发了数百条悼念。对于研究硅谷早期历史以及苹果、微软和 IBM 背后人物的人来说，他的作品仍是重要参考。 克林格利本名马克·斯蒂芬斯，出生于俄亥俄州苹果溪，据称是苹果公司的第 12 号员工；“Robert X. Cringely”最初是《InfoWorld》多位专栏作家共用的笔名。他 1996 年的纪录片《书呆子的胜利》由 John Gau Productions 和 Oregon Public Broadcasting 为 Channel 4 与 PBS 制作，目前可在 Internet Archive 上观看。

hackernews · paveworld · Oct 4, 00:50

**背景**: 《书呆子的胜利》是一部 1996 年的英美电视纪录片，追溯了从二战到 1995 年美国个人电脑的发展历程，采访了史蒂夫·鲍尔默和拉里·埃里森等人物。克林格利还撰写了讲述 PC 产业崛起的《偶然的帝国》，后来在 cringely.com 上撰写关于科技及个人困境的博客。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Triumph_of_the_Nerds">Triumph of the Nerds - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Robert_X._Cringely">Robert X. Cringely - Wikipedia</a></li>
<li><a href="https://www.wired.com/1998/12/cringely/">The Double Life of Robert X. Cringely | WIRED</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者分享了关于克林格利纪录片和写作的美好回忆，有人引用《书呆子的胜利》中的经典台词，并推荐在 Internet Archive 上观看。也有人提到他晚年的艰难处境——失去房子和儿子，还遭遇心脏病发作和中风；同时少数批评者指出，过去曾有指控称他误导读者并编造内容。

**标签**: `#Bob Cringely`, `#Apple`, `#tech history`, `#documentaries`, `#obituary`

---

<a id="item-3"></a>
## [OKX 与纽交所母公司 ICE 申请成立合资企业，推出 24/7 代币化美股交易](https://www.coindesk.com/markets/2026/10/05/okx-and-nyse-s-owner-file-for-round-the-clock-tokenized-trading-in-u-s-stocks) ⭐️ 8.0/10

大型加密货币交易所 OKX 与纽约证券交易所母公司洲际交易所（ICE）已提交申请，拟成立合资企业，提供 24/7 全天候的代币化美股交易服务。这一申请标志着将基于区块链的全天候股票交易引入美国受监管市场方面取得了实质性的监管进展。 这是加密货币与传统金融的一次重大融合：若获批，可能通过取消传统交易时段和结算限制，重塑美国股票的运作方式。这将影响散户和机构投资者、券商、交易所及更广泛的代币化生态，并可能迫使其他交易场所跟进。 该合资企业将支持代币化美股的 24/7 交易，即把股票表示为基于区块链的代币，从而可在标准交易时段之外进行交易。该申请只是监管流程中的一步，而非获批，因此时间表、具体架构和业务范围仍有待审查。

rss · CoinDesk · Oct 5, 04:45

**背景**: 代币化股票是区块链上代表上市公司股份的数字代币，相比传统券商账户，可实现 24/7 交易和更便捷的转让等功能。OKX 是成立于 2013 年的大型加密货币交易所，而 ICE 是一家美国跨国金融服务公司，运营包括纽交所在内的全球交易所。此举契合了加密公司与传统交易所探索代币化现实世界资产的更广泛趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OKX">OKX - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Intercontinental_Exchange">Intercontinental Exchange - Wikipedia</a></li>
<li><a href="https://traderverse.io/blog/stock-market-tokenization">Tokenization and 24/7 Trading : The Future of Stock ... | Traderverse</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#crypto`, `#traditional finance`, `#stock trading`, `#blockchain`

---

<a id="item-4"></a>
## [Tippett Studio 关闭后，其动画资料数字档案上线](https://filmstories.co.uk/news/tippett-studios-in-the-wake-of-its-closure-a-digital-archive-of-animated-materials-appears-online/) ⭐️ 7.0/10

在 Tippett Studio 伯克利办公室关闭后，该工作室动画资料的数字档案已被上传至互联网档案馆（archive.org/details/tippett-archive）。据社区讨论，约 90GB 的内容是从拍卖会上发现的一个 CD 活页夹中抢救出来，并由一位匿名人士完成保存。 Tippett Studio 是由 Phil Tippett 创立的传奇视觉特效与动画公司，这份档案保存了动画与视效史上极为重要的一部分内容，否则这些资料可能永远消失。这一行动也凸显了在工作室关闭后，社区驱动的数字保存在抢救重要文化媒体方面日益重要的作用。 该档案托管在互联网档案馆上，可通过社区成员分享的直接链接访问。评论者指出，这些资料是从拍卖会上发现的实体媒介（CD）中抢救出来的，还有用户提到相关内容也可以在 Discmaster（一个可搜索的老式 CD-ROM 索引）上找到。

hackernews · rdmuser · Oct 4, 21:01 · [社区讨论](https://news.ycombinator.com/item?id=49957812)

**背景**: Tippett Studio 是一家美国视觉特效与电脑动画公司，由动画师 Phil Tippett 及其妻子 Jules Roman 于 1984 年创立，以参与超过五十部电影以及开创性的定格动画和 CGI 技术而闻名。2026 年，在 Tippett 申请第 11 章破产保护后，伯克利办公室关闭，但多伦多分部仍在运营。互联网档案馆由 Brewster Kahle 于 1996 年创立，是一家非营利数字图书馆，免费向公众提供数字化媒体（包括软件、视听作品和网站）的访问。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tippett_Studio">Tippett Studio</a></li>
<li><a href="https://en.wikipedia.org/wiki/Internet_Archive">Internet Archive</a></li>

</ul>
</details>

**社区讨论**: 评论者高度赞扬这一保存行动，有人称这位匿名抢救者为“英雄”，也有人感叹世界上有太多资料因各种原因永远无法重见天日。几位用户建议标题中应包含 Phil Tippett 的名字，以让这份档案获得应有的关注，还有人提到 Discmaster 是一个相关资源。

**标签**: `#digital-preservation`, `#animation`, `#archives`, `#tippett-studios`, `#internet-archive`

---

<a id="item-5"></a>
## [Zarf 博客探讨《Infidel》与内存损坏引发 HN 热议](https://blog.zarfhome.com/2026/10/infidel-goes-wild) ⭐️ 7.0/10

Andrew Plotkin（Zarf）发表了一篇题为“Infidel goes wild”的博客文章，以经典 Infocom 游戏《Infidel》为案例，探讨了互动小说与内存损坏的交集。该文章在 Hacker News 上引发了怀旧且技术性强的讨论，获得了 121 分和 17 条评论。 这篇文章凸显了互动小说和复古计算的持久相关性，展示了经典游戏如何为现代内存安全和调试提供借鉴。它还强调了个人技术写作在促进社区参与和知识共享方面的价值。 讨论中提到了 Digital Antiquarian 的计算机游戏史、rec.arts.int-fiction 新闻组，以及 20 世纪 80 年代游戏开发中普遍存在的内存破坏漏洞。评论者还赞扬了 Zarf 对互动小说社区的持续贡献。

hackernews · tobr · Oct 3, 12:19 · [社区讨论](https://news.ycombinator.com/item?id=49943637)

**背景**: 互动小说（IF）是一种软件类型，玩家通过文本命令控制角色并影响模拟环境，通常被称为文字冒险游戏。《Infidel》是 Infocom 于 1983 年发行的互动小说游戏，由 Michael Berlyn 和 Patricia Fogleman 编写，以其有争议的结局而闻名。内存损坏是指程序意外修改内存，通常由缓冲区溢出等漏洞引起，导致崩溃或异常行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Interactive_fiction">Interactive fiction</a></li>
<li><a href="https://en.wikipedia.org/wiki/Memory_corruption">Memory corruption</a></li>
<li><a href="https://en.wikipedia.org/wiki/Infidel_(video_game)">Infidel (video game) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者对互动小说社区表达了怀旧之情，并分享了关于内存漏洞的个人轶事，其中一位指出 20 世纪 80 年代的每位游戏程序员可能都发布过内存破坏漏洞。另一位评论者询问如何基于个人经验撰写技术性有趣的文章，反映了对 Zarf 写作风格的赞赏。

**标签**: `#interactive fiction`, `#retro computing`, `#memory corruption`, `#game development`, `#Hacker News`

---

<a id="item-6"></a>
## [浏览器原生 VB6 IDE 重现经典 Visual Basic 6](https://wieslawsoltes.github.io/VB6/) ⭐️ 7.0/10

一位开发者发布了浏览器原生的经典 Visual Basic 6 IDE 复刻版，托管在 wieslawsoltes.github.io/VB6/，甚至可以将应用“编译”为独立的 HTML 文件。该项目在 Hacker News 上获得了 165 分和 62 条评论，用户称赞其功能，但也指出了界面上的视觉瑕疵。 该项目复兴了让 VB6 在 1990 年代大受欢迎的快速应用开发（RAD）工作流，评论者认为它可能为 AI 辅助编码代理提供蓝图，从而带回类似的拖拽式、属性驱动的体验。它也凸显了人们对完全在客户端运行、无需安装的浏览器原生 IDE 的持续兴趣。 该 IDE 完全在浏览器中运行，并能将 VB6 风格的应用导出为 HTML 文件，但评论者指出界面看起来杂乱、扭曲，窗口按钮歪斜且缺少斜面边缘。一位评论者推测该实现由 AI 生成，这可能解释了像素级的不准确。

hackernews · wiso · Oct 4, 18:49 · [社区讨论](https://news.ycombinator.com/item?id=49956681)

**背景**: Visual Basic 6（VB6）由微软于 1998 年发布，是经典 Visual Basic 产品线的最后一个版本，至今仍被企业广泛用于构建原生 32 位 Windows 应用。其拖拽式窗体设计器和属性网格使其成为快速应用开发（RAD）的典范。相比之下，浏览器原生 IDE 完全在网页浏览器中运行，使用 WebContainers 等技术，无需本地安装。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://winworldpc.com/product/microsoft-visual-bas/60">WinWorld: Microsoft Visual Basic 6 .0</a></li>
<li><a href="https://latticeide.com/">Lattice - The First Browser-Native Multi-Agent IDE</a></li>
<li><a href="https://stackoverflow.com/questions/8921324/need-to-convert-vb-6-forms-to-html-forms">Need to convert VB 6 forms to Html forms - Stack Overflow</a></li>

</ul>
</details>

**社区讨论**: 评论者大多怀旧且积极：badsectoracula 称赞了“编译”为 HTML 的能力，但批评了杂乱、扭曲的视觉效果；waldrews 称属性网格是“有史以来最伟大的通用 UI”。jit_tech 想知道 AI 编码代理能否带回 VB6 那种压缩的开发循环，其他人则分享了用 VB6 学习编程的回忆。

**标签**: `#visual-basic`, `#ide`, `#browser`, `#retro-computing`, `#rad`

---

<a id="item-7"></a>
## [RemoveMacAI 脚本可从 macOS 27 移除 Apple Intelligence 并回收磁盘空间](https://github.com/omlahore/RemoveMacAI) ⭐️ 7.0/10

一个名为 RemoveMacAI（omlahore/RemoveMacAI）的 GitHub 项目提供了一条命令，可在 macOS 27 上关闭 Apple Intelligence 并删除其已下载的端侧 AI 模型，且该操作被描述为完全可逆。该工具之所以出现，是因为 macOS 27 不再提供单一的系统级开关来禁用整套功能，而且即使用户关闭了各个 Apple Intelligence 功能，AI 模型文件据称仍会留在磁盘上。 该项目触及了用户日益增长的不满情绪：Apple 的 AI 功能占用磁盘空间且难以轻松禁用，这与长期以来与 Windows 相关的“去臃肿”文化如出一辙。该话题在 Hacker News 上获得 506 分和 317 条评论，讨论凸显了人们对 Apple 产品策略、用户控制权以及许多 Mac 默认小容量 SSD 的更广泛担忧。 该脚本的卖点是一条命令即可禁用 Apple Intelligence、删除已下载的模型并阻止 macOS 再次下载它们，并宣称完全可逆。另一个项目 minagishl/apple-intelligence-remover 提供类似功能，这表明回收与 AI 相关的存储空间已成为 macOS 上反复出现的需求。

hackernews · privacyisntdead · Oct 4, 19:42 · [社区讨论](https://news.ycombinator.com/item?id=49957116)

**背景**: macOS 27（又称 Golden Gate）是 Apple Mac 操作系统的第 23 个主要版本，于 2026 年 WWDC 上发布，并于 2026 年 9 月 14 日正式推出；它是首个仅能在 Apple 芯片上运行的 macOS 版本。Apple Intelligence 是 Apple 集成于各应用中的 AI 功能套件，部分依赖占用本地存储的端侧模型。由于 macOS 27 缺少针对这些功能的单一全局开关，用户转而使用第三方脚本来禁用它们并释放空间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/omlahore/RemoveMacAI">GitHub - omlahore/RemoveMacAI: Turn off Apple Intelligence on ...</a></li>
<li><a href="https://www.explainx.ai/blog/removemacai-turn-off-apple-intelligence-macos-27-reclaim-disk-2026">Turn Off Apple Intelligence on macOS 27 (RemoveMacAI ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/MacOs_Golden_Gate">macOS Golden Gate - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者将这一情况比作 Windows 上长期需要的“去臃肿”操作，有人称其“达到了 O&O ShutUp10 的水平”，并质疑 Apple 的产品策略。其他人抱怨 iOS 不再提供简单的开关来禁用 AI 功能，不像 Microsoft 和 Firefox 等竞争对手；也有人认为真正的问题在于 Apple 默认 SSD 容量太小，而非 AI 本身。

**标签**: `#macOS`, `#Apple Intelligence`, `#privacy`, `#disk space`, `#de-crufting`

---

<a id="item-8"></a>
## [不当涂黑泄露谷歌数据中心用水与用电数据](https://www.1011now.com/2026/09/30/more-questions-than-answers-about-lincolns-google-data-center-water-electricity-usage/) ⭐️ 7.0/10

一份被不当涂黑的公开文件泄露了谷歌位于内布拉斯加州林肯市数据中心的资源消耗数据，显示其每年用水约 1330 万加仑，并包含用电量信息。由于涂黑处理存在缺陷，被隐藏的数字得以被还原，这一信息才被曝光。 这一事件凸显了数据中心资源消耗方面日益严重的透明度问题，而随着 AI 基础设施的扩张，该话题正受到公众高度关注。它也表明，有缺陷的涂黑操作可能迫使企业和市政当局公开原本希望保密的信息。 林肯数据中心的 1330 万加仑用水约合 40.8 英亩英尺，与当地农业用水相比规模很小；同一篇文章还提到另一座数据中心用水超过 5 亿加仑。不当涂黑通常是因为仅在文字上覆盖黑框或高亮，而未真正永久删除底层内容，导致信息仍可被还原。

hackernews · sensanaty · Oct 4, 19:37 · [社区讨论](https://news.ycombinator.com/item?id=49957068)

**背景**: 数据中心消耗大量水资源，主要用于冷却，同时服务器和冷却系统也消耗大量电力；研究人员估计，2023 年美国数据中心用电约 176 太瓦时，约占全国用电量的 4.4%。涂黑是指在文件公开发布前遮蔽敏感信息的做法，而操作不当的案例已多次导致法律和政府文件中的机密细节外泄。由于数据中心的水耗和电耗往往不对外公开，记者和研究人员常常依赖此类文件来估算其对当地的影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://caseguard.com/articles/embarrassing-redaction-failures-how-to-prevent-them/">Common Redaction Mistakes: Real-World Examples & How You Can ...</a></li>
<li><a href="https://www.eesi.org/articles/view/data-centers-and-water-consumption">Data Centers and Water Consumption | Article | EESI</a></li>
<li><a href="https://www.congress.gov/crs-product/R48646">Data Centers and Their Energy Consumption: Frequently Asked ...</a></li>

</ul>
</details>

**社区讨论**: 评论者大多对用水数字引发的恐慌持保留态度，指出 1330 万加仑与内布拉斯加州普通农场每年约 3.9 亿加仑的用水量相比微不足道。一些人认为，真正应讨论的是社会是否想要 AI 数据中心，而不应纠结于水和电等次要成本；也有人指出另一座用水超过 5 亿加仑的数据中心才是更有意义的对比对象。

**标签**: `#Google`, `#data centers`, `#water usage`, `#transparency`, `#HN discussion`

---

<a id="item-9"></a>
## [使用 SSH 和 Nginx 搭建自托管 HTTP 隧道](https://vincent.bernat.ch/en/blog/2026-http-over-ssh) ⭐️ 7.0/10

Vincent Bernat 的一篇博客文章介绍了如何使用 SSH 远程端口转发结合 Nginx 反向代理来搭建自托管 HTTP 隧道，作为 ngrok 或 Cloudflare Tunnel 等商业隧道服务的替代方案。该文章在 Hacker News 上引发了 118 分、30 条评论的讨论，开发者们分享了 sish、iroh-webproxy 和 DNTLS 等相关开源项目。 这一点很重要，因为它为自托管和 DevOps 从业者提供了一种无需依赖第三方 SaaS 提供商即可将本地服务暴露到互联网的方法，回应了人们对供应商锁定、隐私以及“自托管”定义模糊的日益关注。社区讨论也凸显了向完全开放、无需中间商的隧道解决方案发展的更广泛趋势。 该方法使用 SSH 远程端口转发（反向隧道）将本地服务连接到远程服务器，并由 Nginx 作为反向代理将传入的 HTTP 请求路由到转发的端口。然而，评论者警告说，最初的 Nginx 配置可能允许攻击者将流量导向任意本地端口，从而可能绕过防火墙规则，因此需要仔细进行安全加固。

hackernews · renehsz · Oct 4, 22:25 · [社区讨论](https://news.ycombinator.com/item?id=49958569)

**背景**: HTTP 隧道通过代理服务器在两台计算机之间建立网络链接，使流量能够穿过防火墙、NAT 和其他限制。SSH 远程端口转发（也称为反向 SSH 隧道）允许本地机器通过向外发起加密连接，将服务暴露给远程服务器。Nginx 是一款流行的开源 Web 服务器和反向代理，可以将传入请求路由到后端服务，因此非常适合管理隧道流量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HTTP_tunnel_(software)">HTTP tunnel (software)</a></li>
<li><a href="https://www.ssh.com/academy/ssh/tunneling-example">SSH Tunneling: Client Command & Server Configuration</a></li>
<li><a href="https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/">NGINX Reverse Proxy</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了几个开源替代方案：antoniomika 提到了 sish，这是一个 MIT 许可的 SSH 隧道服务器，具有自动 TLS 和 Web 控制台；toomim 对 iroh-webproxy 表示兴奋，它通过 iroh 实现 HTTPS，无需端口转发或公网 IP；aliasxneo 讨论了 DNTLS，作为完全避免中间商的一种方式。jamiesonbecker 批评文章中的方法过于复杂且不安全，警告说 Nginx 配置可能让攻击者探测任意本地端口并绕过防火墙。

**标签**: `#self-hosting`, `#ssh`, `#nginx`, `#http-tunnels`, `#networking`

---

<a id="item-10"></a>
## [伊尔库茨克实验室工作人员死于鼠疫，近 200 名接触者被隔离观察](https://www.themoscowtimes.com/2026/10/02/nearly-200-people-under-observation-after-irkutsk-lab-worker-dies-from-plague-a93857) ⭐️ 7.0/10

西伯利亚伊尔库茨克抗鼠疫研究所的一名工作人员在采集样本时据称打破了一支装有活菌的试管，随后死于鼠疫；截至 2026 年 10 月 2 日，已确认至少 197 名接触者，其中 189 人被送往三家机构隔离观察。 这起实验室获得性感染事件凸显了处理危险病原体的现实风险，并引发了关于生物安全规程、应急响应以及鼠疫研究的收益是否值得承担潜在公共卫生威胁的紧迫问题。 197 名接触者包括社区和医院暴露者，其中 114 人在一家医疗机构、63 人在另一家、12 人在抗鼠疫研究所；截至 2026 年 10 月 2 日，无人出现症状，目前尚不清楚涉及的菌株是否对多西环素或环丙沙星等标准抗生素具有耐药性。

hackernews · ericmay · Oct 5, 02:31 · [社区讨论](https://news.ycombinator.com/item?id=49960084)

**背景**: 伊尔库茨克抗鼠疫研究所是俄罗斯抗鼠疫体系的一部分，负责监测和研究引起鼠疫的鼠疫耶尔森菌。鼠疫是一种严重的传染病，历史上曾引发大流行，实验室处理活菌需要严格的生物安全和生物安保措施以防止意外感染。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://beaconbio.org/en/report/?reportid=d9b0fb86-88c3-4883-9433-79f9caccb275&filtersOpen=false">RFI: Fatal laboratory-acquired infection in Irkutsk Region ...</a></li>
<li><a href="https://alexwasburne.substack.com/p/the-irkutsk-plague">The Irkutsk Plague - by Alex Washburne, PhD</a></li>
<li><a href="https://www.cdc.gov/safe-labs/php/biorisk-management/index.html">Biorisk Management | Safe Labs Portal | CDC</a></li>

</ul>
</details>

**社区讨论**: 评论者对实验室安全规程表示担忧，并质疑危险病原体研究是否值得冒此风险，有人指出这与最近一本关于意外释放鼠疫的书在时间上巧合。其他人则强调州长的应急管理背景，并询问该菌株是否可能具有抗生素耐药性。

**标签**: `#biosecurity`, `#public health`, `#lab safety`, `#plague`, `#risk assessment`

---

<a id="item-11"></a>
## [美国独立社区银行家协会起诉 OCC，指加密货币借“侧门”进入银行体系](https://decrypt.co/380017/banking-group-sues-block-crypto-side-door-banking) ⭐️ 7.0/10

美国独立社区银行家协会（ICBA）已对美国货币监理署（OCC）提起诉讼，要求阻止该机构向加密货币公司发放国家信托牌照，认为这些牌照为加密企业开辟了一条不受监管的“侧门”进入银行体系。ICBA 主张，国会从未打算将国家信托牌照作为加密公司获取联邦银行牌照信誉的后门，同时却无需承担传统银行所面临的义务。 这起诉讼可能重塑加密公司进入美国银行体系的途径，或会阻止或减缓加密企业通过获得联邦信托牌照来开展托管和稳定币业务的趋势。判决结果将对整个加密行业与传统金融的融合产生重大影响，并可能为联邦银行监管机构如何监管数字资产公司树立先例。 ICBA 认为，国家信托牌照使加密公司能够获得联邦银行牌照，却无需遵守《社区再投资法》义务、并表监管、资本和流动性标准以及适用于参保存款机构的联邦存款保险公司（FDIC）保险要求。OCC 近期已向 World Liberty Financial 等加密公司授予有条件批准，允许其组建国家信托银行，这一趋势正是 ICBA 试图扭转的。

rss · Decrypt · Oct 4, 16:01

**背景**: OCC 国家信托牌照是一种联邦银行执照，不允许吸收存款或发放贷款，历史上仅被少数公司受托人使用。2025 至 2026 年间，它成为加密和金融科技公司进入美国银行体系的热门途径，用于在联邦监管下开展托管和稳定币发行业务。ICBA 是一个代表约 5000 家美国中小型社区银行的行业组织，成立于 1930 年，长期倡导保护社区银行免受竞争劣势的政策。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://wiki.private.law/en/occ-trust-charter">OCC National Trust Charter : Bank Without Deposits</a></li>
<li><a href="https://en.wikipedia.org/wiki/Independent_Community_Bankers_of_America">Independent Community Bankers of America</a></li>
<li><a href="https://www.cutoday.info/Fresh-Today/ICBA-Takes-OCC-To-Court-Over-Side-Door-Into-Banking-System">ICBA Takes OCC To Court Over ‘Side Door’ Into Banking System</a></li>

</ul>
</details>

**标签**: `#crypto`, `#banking`, `#regulation`, `#OCC`, `#lawsuit`

---

<a id="item-12"></a>
## [Zcash 25 秒出块提前上线公共测试网](https://www.coindesk.com/tech/2026/10/05/zcash-s-25-second-blocks-go-live-on-public-testnet-ahead-of-schedule) ⭐️ 6.0/10

Zcash 已在公共测试网上激活 NU7 升级，将目标出块时间从 75 秒缩短至 25 秒，比原计划 11 月 5 日的主网部署提前完成。 更快的出块时间意味着交易确认更快、吞吐量更高，这可能使 Zcash 在日常支付场景中更实用，并增强其在隐私币和一层区块链中的竞争力。 该变更目前仅限公共测试网而非主网，主网部署目标日期为 11 月 5 日；出块时间是影响网络吞吐量和可扩展性的关键参数。

rss · CoinDesk · Oct 5, 04:41

**背景**: Zcash 是一种注重隐私的加密货币，使用零知识证明来隐藏交易细节。出块时间是指区块链上连续两个区块被添加之间的平均间隔，它直接影响交易确认速度以及网络能处理的交易数量。缩短出块时间是 Layer 1 网络为改善用户体验而常用的扩容策略。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/10/05/zcash-s-25-second-blocks-go-live-on-public-testnet-ahead-of-schedule">Zcash’s 25-second blocks go live on public testnet ahead of ...</a></li>
<li><a href="https://fastercapital.com/content/Block-Time--Block-Time-Breakdown--The-Pulse-of-Layer-1-Blockchain-Networks.html">Block Time : Block Time Breakdown: The Pulse of... - FasterCapital</a></li>
<li><a href="https://www.princewill.io/what-is-block-time-and-why-it-matters/">What Is Block Time and Why It Matters</a></li>

</ul>
</details>

**标签**: `#Zcash`, `#blockchain`, `#cryptocurrency`, `#scalability`, `#testnet`

---

<a id="item-13"></a>
## [贝莱德揭示代币化将如何重塑投资组合](https://www.coindesk.com/business/2026/10/03/blackrock-offers-a-glimpse-of-how-tokenization-may-change-your-investment-portfolio) ⭐️ 6.0/10

贝莱德就代币化如何改变投资组合提供了新的见解，表明机构对基于区块链的资产兴趣日益浓厚。该报告将代币化定位为通往更高效、更易进入市场的可行路径，而非纯粹实验性技术。 作为全球最大的资产管理公司，贝莱德的背书在传统金融领域具有分量，可能加速其他机构对代币化现实世界资产的采用。如果代币化规模扩大，可能改变投资者获取、交易和持有债券、基金及房地产等资产的方式。 代币化将传统资产转换为可在区块链上交易的数字代币，带来部分所有权、流动性提升和更易获取等好处。但它也伴随监管不确定性、技术复杂性和安全风险等机构必须应对的问题。

rss · CoinDesk · Oct 3, 13:00

**背景**: 资产代币化是将股票、债券、房地产或大宗商品等传统资产的所有权转换为基于区块链的数字代币的过程。贝莱德于 2024 年 3 月在以太坊网络上推出代币化基金，正式加入代币化竞赛，此前花旗、富兰克林邓普顿和摩根大通已有类似举措。该公司此前曾将代币化描述为现实世界资产领域数万亿美元级别的机遇。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/markets/2024/03/20/blackrock-enters-asset-tokenization-race-with-new-fund-on-the-ethereum-network">BlackRock Enters Asset Tokenization Race With New Fund on the...</a></li>
<li><a href="https://www.forbes.com/sites/nataliakarayaneva/2024/03/21/blackrocks-10-trillion-tokenization-vision-the-future-of-real-world-assets/">BlackRock 's $10 Trillion Tokenization Vision: The Future Of Real...</a></li>
<li><a href="https://www.britannica.com/money/real-world-asset-tokenization">What Is Asset Tokenization? Meaning, Examples, Pros, & Cons ...</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#blockchain`, `#investing`, `#fintech`, `#BlackRock`

---

<a id="item-14"></a>
## [特朗普任命曾起诉 Ripple 的 SEC 主席 Jay Clayton 领导 AI 推进工作](https://decrypt.co/380019/trump-jay-clayton-sec-ripple-ai-push-super-intelligence) ⭐️ 6.0/10

特朗普总统宣布成立新的“超级智能部队”（Super Intelligence Force）以协调联邦 AI 政策，并任命国家情报总监 Jay Clayton 领导该机构。Clayton 曾在 2017 年至 2020 年担任 SEC 主席，期间主导了 SEC 于 2020 年 12 月对 Ripple Labs 及其高管提起的诉讼。 这一任命表明特朗普政府希望由一位强有力的协调者统一领导 AI 政策，而 Clayton 在金融监管和加密货币执法方面的背景可能影响 AI 监管与数字资产的交叉方式。根据该机构对 AI 相关金融技术的态度，这可能让加密行业感到安心或担忧。 据 NBC 新闻报道，Clayton 预计还将被任命为 AI 沙皇（AI czar），而“超级智能部队”是在特朗普宣布另一个“AI Force”几周后成立的。该公告发布之际，人们对 AI 风险的担忧日益加剧，但该机构的具体职责和权限仍不明确。

rss · Decrypt · Oct 4, 17:01

**背景**: SEC 于 2020 年 12 月起诉 Ripple Labs，指控其出售 XRP 构成未经注册的证券发行；该案在 2023 年部分裁决后于 2024 年达成和解。Jay Clayton 于 2017 年 5 月至 2020 年担任 SEC 主席，后来被确认为国家情报总监。“超级智能部队”是一个新的联邦工作组，旨在协调美国政府的 AI 政策。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nbcnews.com/politics/trump-administration/trump-announces-members-ai-task-force-rcna601494">Trump announces members of ‘ Super Intelligence Force ’ to...</a></li>
<li><a href="https://www.sec.gov/enforcement-litigation/litigation-releases/lr-26306">SEC.gov | Ripple Labs, Inc., Bradley Garlinghouse, and ...</a></li>
<li><a href="https://www.sec.gov/about/sec-commissioners/sec-historical-summary-chairmen-commissioners/jay-clayton">SEC .gov | Jay Clayton</a></li>

</ul>
</details>

**标签**: `#AI policy`, `#regulation`, `#cryptocurrency`, `#government`, `#Trump administration`

---

<a id="item-15"></a>
## [Near Intents 发出 48 小时最后通牒后追回 380 万美元](https://decrypt.co/380014/near-intents-recovers-3-8-million-after-48-hour-ultimatum) ⭐️ 6.0/10

Near Intents 宣布，周四漏洞攻击中被盗的约 380 万美元已全部归还，而就在一天前，团队公开表示已锁定攻击者身份，并给出 48 小时归还资金的最后期限。事件发生后，该协议已暂停其跨链服务。 这是一起罕见的 DeFi 漏洞攻击最终全额追回资金的案例，表明链上溯源和公开施压有时能在纯技术防御失效时奏效。同时，它也凸显了 2026 年持续不断的加密货币黑客攻击浪潮，以及谈判作为追回手段正日益被采用。 该漏洞源于 Near Intents 的 Omni 充提基础设施与 Near Intents 智能合约相关的缺陷，导致团队暂停服务。攻击者在最后通牒发出一天后归还了全部被盗资产，但具体技术修复细节尚未披露。

rss · Decrypt · Oct 4, 13:01

**背景**: Near Intents 是构建在 NEAR 区块链上的多链交易协议，用户只需说明自己想要做什么（例如跨链兑换代币），第三方求解器便会竞争完成该请求。它利用链签名和求解器网络，实现一键跨链兑换，用户无需自行管理跨链桥。此次事件发生在加密货币安全形势严峻的一年，众多 DeFi 协议遭到漏洞攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/10/01/near-intents-hit-by-usd3-8-million-exploit-as-crypto-s-rough-year-of-hacks-continues">NEAR Intents hit by $3.8M exploit, pauses cross-chain ...</a></li>
<li><a href="https://coincodex.com/article/92975/near-intents-hit-by-38m-security-incident-services-halted/">NEAR Intents Hit by $3.8M Security Incident, Services Halted</a></li>
<li><a href="https://www.near.org/intents">intents | NEAR</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#security`, `#exploit`, `#DeFi`, `#blockchain`

---

<a id="item-16"></a>
## [Chainalysis 利用 AI 将 3.87 亿美元 Bitget 黑客事件追踪至朝鲜](https://decrypt.co/380005/chainalysis-ai-87m-bitget-hack-north-korea) ⭐️ 6.0/10

Chainalysis 宣布其利用内部 AI 工具将 9 月 24 日发生的 3.87 亿美元 Bitget 交易所黑客事件追踪至朝鲜，使该国 2026 年加密货币盗窃总额突破 10 亿美元。该公司详细说明了如何在四条不同区块链上追踪被盗资金，与攻击者展开赛跑。 此案凸显了 AI 正成为区块链取证的关键工具，能够更快地跨多条链追踪被盗资金，并加强对朝鲜等国家支持行为者的归因。同时，它也突显了朝鲜加密货币盗窃规模日益扩大——仅 2026 年就超过 10 亿美元，加大了对交易所和监管机构加强安全的压力。 黑客事件发生于 9 月 24 日，涉及在四条区块链上转移的资金，Chainalysis 利用其专有 AI 代理进行了追踪。Bitget 首席执行官 Gracy Chen 此前曾对全额追回表示怀疑，指出在此类事件中通常只有一小部分资金能被冻结或追回。

rss · Decrypt · Oct 3, 17:01

**背景**: Chainalysis 是一个区块链数据平台，将链上数据与 AI 结合，帮助政府机构、加密企业和金融机构调查非法活动。朝鲜曾与多起备受瞩目的加密货币黑客事件有关，包括 2019 年 UpBit 被盗（4100 万美元）和 2021 年 KuCoin 被盗（2.75 亿美元），该政权利用被盗资金资助其武器项目。Bitget 黑客事件被认为是 2026 年迄今为止最大的加密货币盗窃案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chainalysis.com/blockchain-intelligence/">Blockchain Intelligence - Chainalysis</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bitget">Bitget - Wikipedia</a></li>
<li><a href="https://www.euronews.com/2026/09/28/north-korean-hackers-suspected-in-3328m-crypto-heist-as-it-leads-global-hacks">North Korean hackers suspected in €332.8m crypto heist... | Euronews</a></li>

</ul>
</details>

**标签**: `#AI`, `#blockchain forensics`, `#cybersecurity`, `#North Korea`, `#cryptocurrency`

---