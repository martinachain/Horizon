---
layout: default
title: "Horizon Summary: 2026-06-21 (ZH)"
date: 2026-06-21
lang: zh
---

> From 40 items, 15 important content pieces were selected

---

1. [Loupe iOS 应用揭示原生应用隐藏的数据访问](#item-1) ⭐️ 8.0/10
2. [Epoll 与 io_uring：性能与安全性的权衡](#item-2) ⭐️ 8.0/10
3. [即使 AI 代码能运行，我为何仍拒绝它](#item-3) ⭐️ 8.0/10
4. [SMPTE 免费开放其标准](#item-4) ⭐️ 8.0/10
5. [慢呼吸调节大脑与风险行为](#item-5) ⭐️ 7.0/10
6. [UHF X11 将 X11 带到 Apple Vision Pro](#item-6) ⭐️ 7.0/10
7. [OpenRouter Fusion 以低成本击败顶级 AI 模型](#item-7) ⭐️ 7.0/10
8. [Secret Network 的 Axelar 桥遭遇 467 万美元无限铸币攻击](#item-8) ⭐️ 7.0/10
9. [以太坊核心开发资金危机警告](#item-9) ⭐️ 7.0/10
10. [F-15 Strike Eagle II 逆向工程招募测试员](#item-10) ⭐️ 6.0/10
11. [嘉信理财将推出标普 500 事件期权，进军预测市场](#item-11) ⭐️ 6.0/10
12. [富兰克林坦伯顿提议将股息转换为比特币的 ETF](#item-12) ⭐️ 6.0/10
13. [微软发现通过 USB 传播的加密钱包恶意软件](#item-13) ⭐️ 6.0/10
14. [动漫壁纸恶意软件瞄准 Steam 玩家](#item-14) ⭐️ 6.0/10
15. [Base Beryl 升级与 B20 代币标准将于 6 月 25 日上线](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Loupe iOS 应用揭示原生应用隐藏的数据访问](https://github.com/mysk-research/loupe) ⭐️ 8.0/10

Loupe 是一款 iOS 应用，展示了原生 Apple 应用无需用户权限即可访问的数据，包括卷创建日期、已安装应用探测和剪贴板更改计数。 这凸显了用户未意识到的重大 iOS 隐私漏洞，可能促使 Apple 限制此类数据访问并改进隐私保护。 该应用将数据泄露分为被动、权限和高级三类，并显示即使没有权限，应用也能通过 URL scheme 探测推断已安装应用，并访问文件创建日期。

hackernews · Cider9986 · Jun 20, 12:08 · [社区讨论](https://news.ycombinator.com/item?id=48608645)

**背景**: iOS 应用通常需要用户权限才能访问位置或通讯录等敏感数据。然而，一些系统级数据，如文件创建日期和已注册的 URL scheme 列表，无需明确同意即可访问。Loupe 揭示了这些隐藏的数据点以提高用户意识。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/danielamitay/iHasApp">GitHub - danielamitay/iHasApp: The iHasApp iOS Framework allows you to detect installed apps on a user's device.</a></li>
<li><a href="https://www.danielamitay.com/blog/2011/2/16/how-to-detect-installed-ios-apps">How To Detect Installed iOS Apps - Daniel Amitay</a></li>
<li><a href="https://www.hackingwithswift.com/example-code/system/how-to-check-whether-your-other-apps-are-installed">How to check whether your other apps are installed - free Swift example code and tips</a></li>

</ul>
</details>

**社区讨论**: 评论者对卷创建日期和已安装应用探测泄露感到惊讶，一些人认为这比 Android 的现状要好。他们赞赏这种教育性分组，并呼吁操作系统层面模糊化此类数据。

**标签**: `#iOS`, `#privacy`, `#security`, `#app development`

---

<a id="item-2"></a>
## [Epoll 与 io_uring：性能与安全性的权衡](https://sibexi.co/posts/epoll-vs-io_uring/) ⭐️ 8.0/10

一篇技术文章对比了 Linux 中的 epoll 和 io_uring，指出 io_uring 的性能优势（例如每秒请求数提升 20%），但同时提到由于内核需手动启用以及过往的漏洞利用，其安全性问题限制了广泛采用。 这一对比很重要，因为 io_uring 可以显著提升高吞吐量应用的 I/O 性能，但其安全性缺陷阻碍了广泛部署，影响了 Go 运行时和高性能代理等系统的决策。 io_uring 使用内核与用户空间之间的共享内存来减少系统调用开销，但这种设计导致了多次安全漏洞。由于 epoll 的成熟度和安全记录，它仍是大多数生产系统的默认选择。

hackernews · Sibexico · Jun 20, 23:07 · [社区讨论](https://news.ycombinator.com/item?id=48613872)

**背景**: Epoll 是 Linux 内核 2.5.44 引入的 I/O 事件通知机制，广泛用于可扩展的网络服务器。io_uring 是内核 5.1 引入的较新的异步 I/O 接口，旨在减少系统调用开销并提升存储和网络 I/O 性能。然而，io_uring 的共享内存模型带来了安全风险，过去曾因此被利用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Io_uring">io _ uring - Wikipedia</a></li>
<li><a href="https://kernel-internals.org/io-uring/io-uring-vs-epoll/">io _ uring vs epoll - Linux Kernel Internals</a></li>
<li><a href="https://devmindset.dev/en/epoll-vs-io_uring-when-the-event-loop-isnt-enough/">epoll vs io _ uring : When the Event Loop Isn't Enough | Devmindset</a></li>

</ul>
</details>

**社区讨论**: 评论者指出 io_uring 在每秒请求数上可提升 20%，但常因安全原因被禁用。建议包括使用 CPU 绑定、并发工具包、mimalloc 和 eBPF 进行进一步优化。有人推荐使用 Boost.Asio 进行 C++ 异步网络编程。

**标签**: `#Linux`, `#I/O`, `#performance`, `#security`, `#networking`

---

<a id="item-3"></a>
## [即使 AI 代码能运行，我为何仍拒绝它](https://vinibrasil.com/when-i-reject-ai-code-even-if-it-works/) ⭐️ 8.0/10

一位开发者发表文章，解释为何即使 AI 生成的代码能运行，他们仍会拒绝，原因包括过度工程化和缺乏可维护性，这引发了关于 AI 辅助开发中人类判断力的深入讨论。 这很重要，因为它凸显了 AI 生成代码的微妙权衡，提醒开发者代码能运行还不够——可维护性和简洁性对软件的长期健康至关重要。 作者指出，AI 即使对简单任务也常生成复杂的抽象和企业级模式，导致代码更难维护。社区评论将拒绝 AI 代码比作因类似原因拒绝同事的代码，强调软件工程是关于选择正确的解决方案，而不仅仅是任何能运行的方案。

hackernews · vnbrs · Jun 21, 00:58 · [社区讨论](https://news.ycombinator.com/item?id=48614631)

**背景**: 像 GitHub Copilot 和 Cursor 这样的 AI 辅助编码工具能根据自然语言提示生成代码，但它们常产生过于复杂或模板化的代码。开发者必须在生产力提升与代码质量之间取得平衡，因为可维护性和简洁性是项目长期成功的关键。

**社区讨论**: 评论者大多同意作者的观点，有人指出拒绝 AI 代码就像因同样原因拒绝同事的代码——不应有双重标准。另有人指出，随着问题复杂度增加，AI 倾向于生成企业级模式，使得在完全使用 AI 和完全不使用之间难以找到中间地带。

**标签**: `#AI-assisted coding`, `#code quality`, `#software engineering`, `#developer experience`, `#LLM tools`

---

<a id="item-4"></a>
## [SMPTE 免费开放其标准](https://www.smpte.org/blog/smpte-makes-its-standards-freely-accessible-openingstandards-library-to-the-global-media-technology-community) ⭐️ 8.0/10

SMPTE 宣布其超过 800 项媒体技术标准现已免费向公众开放，无需付费或成为会员。 此举消除了媒体制作和分发领域创新的主要障碍，使初创公司、研究人员和全球开发者能够更广泛地参与。 该举措包括通过基于 GitHub 的工作流程、基于 HTML 的编写以及集成发布管道来现代化标准开发，以实现更快的更新。

hackernews · zdw · Jun 20, 17:01 · [社区讨论](https://news.ycombinator.com/item?id=48610827)

**背景**: SMPTE（电影与电视工程师协会）是一个全球标准组织，已发布了 800 多项媒体技术标准。此前，获取这些标准需要购买单个文档或机构订阅。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Category:SMPTE_standards">Category: SMPTE standards - Wikipedia</a></li>
<li><a href="https://www.smpte.org/standards/overview">Standards Overview | Society of Motion Picture & Television ...</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍称赞这一举措，有人指出法国等国家的法律要求标准必须免费提供。其他人则强调了这对开放标准采纳的积极影响，并将其与 IETF 免费模式的成功相提并论。

**标签**: `#open standards`, `#media technology`, `#SMPTE`, `#standards bodies`

---

<a id="item-5"></a>
## [慢呼吸调节大脑与风险行为](https://www.cell.com/neuron/fulltext/S0896-6273(26)00339-9) ⭐️ 7.0/10

一项发表在《Neuron》上的研究表明，慢呼吸能调节大脑功能并增加冒险行为，其中延长呼气时间特别增强了奖赏反应。 这项研究揭示了呼吸与冒险行为之间的神经机制，并通过身体到大脑的自下而上调节，为管理焦虑、恐慌症和公开演讲提供了实际应用价值。 研究发现，延长呼气的慢呼吸能选择性影响奖赏处理，这可能对具有不同自主神经特征的临床情境（如焦虑和抑郁）有益。

hackernews · croes · Jun 20, 22:22 · [社区讨论](https://news.ycombinator.com/item?id=48613555)

**背景**: 慢呼吸是一种常见的镇静神经的技巧，常在公开演讲前被推荐。本研究探讨了它如何通过副交感神经系统的激活来影响大脑功能和行为，特别是冒险行为。

**社区讨论**: 社区评论强调了慢呼吸在公开演讲中的实际应用，并指出副交感神经激活与冒险行为之间的有趣联系。有人指出瑜伽早已倡导这种做法，而另一些人则提醒恐惧可能是适应性的，呼吸只应针对非理性恐惧。

**标签**: `#neuroscience`, `#breathing`, `#risk behavior`, `#anxiety`, `#psychology`

---

<a id="item-6"></a>
## [UHF X11 将 X11 带到 Apple Vision Pro](https://www.lispm.net/apps/uhf-x11/) ⭐️ 7.0/10

UHF X11 是一款新应用，它将经典的 X11 窗口系统移植到 Apple 的 visionOS 上，使用户能够在 Apple Vision Pro 头显中运行 2D 和 3D X11 应用程序。 这弥合了传统 Unix/Linux 图形环境与现代混合现实之间的鸿沟，使开发者和爱好者能够在 VR 空间中使用熟悉的 X11 工具。同时，它也展示了 visionOS 运行非原生窗口系统的灵活性。 该应用支持 OpenGL 客户端的 GLX 渲染，但兼容性有所不同。它采用 2D 嵌入 3D 的方式，将 X11 窗口显示为 3D 环境中的平面。

hackernews · zdw · Jun 20, 17:04 · [社区讨论](https://news.ycombinator.com/item?id=48610853)

**背景**: X11 是类 Unix 操作系统的窗口系统，最初于 1987 年发布。visionOS 是 Apple 为其 Apple Vision Pro 头显开发的混合现实操作系统，于 2024 年推出。UHF X11 由 Ian Finder 开发，可在 App Store 获取。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://apps.apple.com/us/app/uhf-x11/id6772673274">UHF X11 App - App Store</a></li>
<li><a href="https://news.ycombinator.com/item?id=48610853">UHF X11: X11 Built for VisionOS and Apple Vision Pro | Hacker News</a></li>
<li><a href="https://en.wikipedia.org/wiki/X_Windowing_System">X Windowing System</a></li>

</ul>
</details>

**社区讨论**: 评论者认为该项目有趣且富有创意，有人指出“3D 中的 2D 中的 3D”的讽刺意味。一些人将其与 Linux 上的 WayVR 进行比较，而另一些人则推测 X11 可能比 visionOS 更长寿。还有用户询问支持处方镜片的 Linux AR 头显推荐。

**标签**: `#X11`, `#VisionOS`, `#Apple Vision Pro`, `#VR/AR`, `#retrocomputing`

---

<a id="item-7"></a>
## [OpenRouter Fusion 以低成本击败顶级 AI 模型](https://decrypt.co/371711/openrouter-fusion-claude-fable-level-ai-cheap) ⭐️ 7.0/10

OpenRouter 推出了 Fusion API，通过堆叠多个低成本 AI 模型，在基准测试中超越了 GPT-5.5 和 Claude Opus 4.8，且成本极低。与此同时，Anthropic 的高端模型 Fable 5 因美国当局要求被暂停使用。 这一进展为昂贵的专有模型提供了高性价比的替代方案，使高性能 AI 更加普及。同时，Fable 5 的突然下线也凸显了依赖单一模型提供商的风险。 Fusion API 采用多模型审议流程：一组模型生成回答，一个评判模型选出最佳结果，最终通过一次 API 调用返回。OpenRouter 声称其性能与 Fable 5 相当，但成本仅为其一半。

rss · Decrypt · Jun 20, 18:01

**背景**: OpenRouter 是一个提供统一 API 的平台，可访问来自不同提供商的多种 AI 模型。模型堆叠（即集成方法）通过组合多个模型的输出来提高准确性和鲁棒性。Fable 5 是 Anthropic 最先进的模型，近期因美国出口管制问题被暂停使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/fusion">Model Fusion | OpenRouter</a></li>
<li><a href="https://openrouter.ai/docs/guides/routing/routers/fusion-router">Fusion Router | Multi-model AI Deliberation with OpenRouter | OpenRouter | Documentation</a></li>
<li><a href="https://www.mindstudio.ai/blog/what-is-openrouter-fusion-multi-model-api">What Is OpenRouter Fusion? The Multi-Model API That Matches Claude Fable 5 at Half the Cost | MindStudio</a></li>

</ul>
</details>

**标签**: `#AI`, `#benchmarking`, `#model stacking`, `#OpenRouter`, `#cost efficiency`

---

<a id="item-8"></a>
## [Secret Network 的 Axelar 桥遭遇 467 万美元无限铸币攻击](https://www.theblock.co/post/405459/secret-networks-axelar-bridge-drained-for-4-67-million-in-infinite-mint-exploit-that-went-unnoticed-for-seven-days?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

攻击者利用 Secret Network 智能合约中缺失的验证检查，铸造了 467 万美元无担保的 Axelar 桥接代币，并从托管中盗取了真实资产。该漏洞在七天内未被发现，约 77 万美元被盗资金仍留在攻击者的 Axelar 钱包中。 此事件凸显了跨链桥基础设施中的关键漏洞，而跨链桥对于 DeFi 互操作性至关重要。七天的未被发现期以及关于冻结资金的争议，凸显了保护此类系统和跨链协调响应的挑战。 该漏洞自 2023 年 3 月起就存在于已部署的代码中，攻击者利用了连接 Axelar 和 Secret Network 的修改版 IBC 桥合约。Axelar 拒绝了 Secret Network 冻结攻击者钱包中剩余 77 万美元的请求。

rss · The Block · Jun 20, 21:57

**背景**: 像 Axelar 这样的跨链桥通过在一链锁定资产并在另一链铸造包装代币来实现代币在不同区块链之间的转移。无限铸币攻击发生在智能合约未能验证铸造的代币是否有锁定资产支持时，从而允许攻击者创建无担保代币并耗尽真实储备。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/405459/secret-networks-axelar-bridge-drained-for-4-67-million-in-infinite-mint-exploit-that-went-unnoticed-for-seven-days">Secret Network ’s Axelar bridge drained for $4.67 million... | The Block</a></li>
<li><a href="https://www.cryptopolitan.com/axelar-bridged-tokens-worth-4-67-million-drained-in-secret-network-contract-exploit/">Axelar - bridged tokens worth $4.67 million drained in Secret Network ...</a></li>
<li><a href="https://www.binance.com/en/square/post/06-20-2026-axelar-disables-secret-network-ibc-links-after-4-67-million-token-theft-335967137697025">Axelar Disables Secret Network ... | Binance News on Binance Square</a></li>

</ul>
</details>

**标签**: `#security`, `#exploit`, `#DeFi`, `#cross-chain bridge`, `#Axelar`

---

<a id="item-9"></a>
## [以太坊核心开发资金危机警告](https://www.theblock.co/post/405404/ethereum-could-face-core-development-funding-crisis-within-nine-months-says-former-ef-contributor?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

前以太坊基金会贡献者 VanEpps 警告称，在社区激励计划（CIP）到期后的 3 到 9 个月内，以太坊的核心开发可能面临资金危机。 这一警告突显了以太坊核心开发和生态系统健康面临的潜在威胁，资金短缺可能会减缓协议升级和客户端维护。 CIP 于 2021 年启动，旨在为客户端团队提供长期支持，其到期可能导致核心开发者缺乏足够资金。VanEpps 建议，像大型质押者这样的营利性实体可能需要介入以填补缺口。

rss · The Block · Jun 19, 10:11

**背景**: 以太坊基金会（EF）历来通过拨款和 CIP 等项目资助核心开发。然而，EF 的国库资金正在减少，其资助模式已从开放申请转向更主动、需求驱动的结构。一些人认为，随着以太坊成熟，依赖网络的营利性实体将自然为其维护提供资金。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.ethereum.org/2021/12/13/client-incentive-program">Announcing the Client Incentive Program - Ethereum Foundation Blog</a></li>
<li><a href="https://www.studioglobal.ai/discover/answers/searching-with-cited-sources-for-given-that-6a36ac941c610f3e5345dd90">The $30 Million Question: Is Ethereum's Core Development Facing a ...</a></li>
<li><a href="https://ethereum.org/community/grants">Ethereum Foundation & community grant programs | ethereum.org</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#funding crisis`, `#core development`, `#blockchain`

---

<a id="item-10"></a>
## [F-15 Strike Eagle II 逆向工程招募测试员](https://neuviemeporte.github.io/f15-se2/2026/06/20/needyou.html) ⭐️ 6.0/10

一位开发者正在将 DOS 游戏 F-15 Strike Eagle II 从汇编语言逆向工程为 C 语言，以便移植到现代平台，并请求测试人员帮助查找当前版本中的错误。 该项目保留了一款经典飞行模拟游戏，使其无需模拟即可在现代系统上运行，惠及复古游戏爱好者，并展示了一种严谨的逆向工程方法。 该过程首先完全逆向为汇编语言，然后将汇编代码转换为二进制等效的编译 C 代码，所有代码仍在 DOS 上运行，直到没有汇编代码残留，之后开始移植到 Linux 和 Windows。

hackernews · LowLevelMahn · Jun 20, 15:10 · [社区讨论](https://news.ycombinator.com/item?id=48609766)

**背景**: F-15 Strike Eagle II 是 MicroProse 于 1989 年发布的飞行模拟游戏，最初运行于 DOS。逆向工程将机器代码转换回高级源代码，以理解和修改游戏。移植则使软件适应不同平台，通常需要大量重写。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=40347662">DOS game “ F - 15 Strike Eagle II ” reverse engineering /reconstruction...</a></li>
<li><a href="https://de.wikipedia.org/wiki/F-15_Strike_Eagle">F - 15 Strike Eagle – Wikipedia</a></li>
<li><a href="https://maniacsvault.net/articles/dosporting">Porting Games from DOS to Modern Platforms - Blzut3's Weblog</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了反编译相对于模拟的动机，有人指出使用现代 API 移植的便利性。其他人分享了怀旧之情，并询问 AI 辅助逆向工程，而开发者则澄清了多步骤过程和对测试人员的需求。

**标签**: `#reverse engineering`, `#DOS games`, `#retro computing`, `#porting`

---

<a id="item-11"></a>
## [嘉信理财将推出标普 500 事件期权，进军预测市场](https://www.coindesk.com/markets/2026/06/19/schwab-to-join-prediction-markets-race-with-s-and-p-500-event-based-options-wsj) ⭐️ 6.0/10

据《华尔街日报》报道，嘉信理财计划推出标普 500 事件期权，从而进入预测市场领域。 这一由大型金融机构采取的行动可能使预测市场合法化，并吸引传统投资者，从而可能扩大事件衍生品的市场。 这些期权将基于标普 500 指数并与特定事件挂钩，但具体事件类型和推出日期尚未披露。

rss · CoinDesk · Jun 19, 17:51

**背景**: 预测市场允许交易未来事件的结果，价格反映人群的概率估计。事件期权是一种衍生品，根据特定事件是否发生进行支付。嘉信理财是一家以经纪和银行服务闻名的全球金融机构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prediction_market">Prediction market</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#finance`, `#options trading`, `#S&P 500`

---

<a id="item-12"></a>
## [富兰克林坦伯顿提议将股息转换为比特币的 ETF](https://www.coindesk.com/daybook-us/2026/06/19/franklin-templeton-proposes-new-funds-that-turn-corporate-dividends-into-bitcoin) ⭐️ 6.0/10

富兰克林坦伯顿已申请两只新的 ETF，即“比特币 DRIP”基金，这些基金将持有美国股票，并将其股息再投资于比特币，预计最早生效日期为 2026 年 9 月 1 日。 这一创新连接了传统金融与加密货币，为投资者提供了一种通过股息再投资获得比特币敞口的方式，而无需直接购买加密货币。这可能为大型资产管理公司推出更多混合金融产品铺平道路。 这些基金将追踪 VettaFi 美国大盘 500 比特币 DRIP 和 VettaFi 美国创新 100 比特币 DRIP 指数，投资组合为 95%股票和 5%比特币，比特币敞口上限为 20%。DRIP 代表股息再投资计划，这是一个在此处为加密货币改编的传统概念。

rss · CoinDesk · Jun 19, 11:27

**背景**: 股息再投资计划（DRIP）允许投资者自动使用现金股息购买更多同一股票的股份。富兰克林坦伯顿提议的 ETF 将这一概念应用于比特币，即用美国股票的股息购买与比特币挂钩的投资，从而随着时间的推移系统性地建立加密货币敞口。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.benzinga.com/etfs/new-etfs/26/06/60002555/franklin-templeton-files-bitcoin-drip-etfs-that-reinvest-stock-dividends-into-crypto">Franklin Templeton Files Bitcoin ETFs That Reinvest... - Benzinga</a></li>
<li><a href="https://cointelegraph.com/news/franklin-templeton-bitcoin-drip-etfs-reinvest-stock-dividends-btc-exposure">Franklin Templeton files ETFs that turn stock dividends into Bitcoin ...</a></li>
<li><a href="https://cryptobriefing.com/franklin-bitcoin-drip-etfs-dividends/">Franklin Templeton files two Bitcoin DRIP ETFs that funnel stock ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#ETFs`, `#finance`, `#bitcoin`

---

<a id="item-13"></a>
## [微软发现通过 USB 传播的加密钱包恶意软件](https://www.coindesk.com/tech/2026/06/19/microsoft-found-malware-that-hijacks-crypto-wallets-and-spreads-through-usb-sticks) ⭐️ 6.0/10

微软发现了一种名为“加密剪贴器”的新型恶意软件，它通过替换复制的钱包地址来劫持加密货币钱包，并自 2026 年 2 月起通过受感染的 USB 驱动器传播。 这种恶意软件对加密货币用户构成重大威胁，因为它可以在交易过程中悄悄地将资金重定向到攻击者手中，而其 USB 传播方式增加了在共享环境中广泛感染的风险。 该恶意软件是一种剪贴板劫持程序，监控剪贴板中的加密货币地址并将其替换为攻击者的地址。它利用 Windows 自动运行功能通过 USB 驱动器传播，当插入驱动器时感染新机器。

rss · CoinDesk · Jun 19, 08:48

**背景**: 剪贴板劫持恶意软件（即“加密剪贴器”）在加密货币领域已是已知威胁，通常通过钓鱼或受感染网站传播。基于 USB 的传播增加了物理攻击途径，使得传统网络防御更难检测和阻止。微软的发现凸显了针对数字资产持有者的网络犯罪分子不断演变的策略。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/06/19/microsoft-found-malware-that-hijacks-crypto-wallets-and-spreads-through-usb-sticks">Microsoft identifies malware 'worm' that hijacks crypto wallets ...</a></li>
<li><a href="https://cncintel.com/clipboard-hijacking/">Clipboard Hijacking Malware Removal - CNC Intelligence</a></li>
<li><a href="https://ophtek.com/viruses-on-usb-thumb-drives/">Spreading Viruses on USB Thumb Drives</a></li>

</ul>
</details>

**标签**: `#malware`, `#cryptocurrency`, `#security`, `#USB`

---

<a id="item-14"></a>
## [动漫壁纸恶意软件瞄准 Steam 玩家](https://decrypt.co/371632/anime-girls-steal-crypto-wallpaper-malware-targets-steam-gamers) ⭐️ 6.0/10

卡巴斯基研究人员发现，Steam Workshop 上有数十个恶意的 Wallpaper Engine 下载，这些下载分发信息窃取器、后门和账户劫持恶意软件。 该活动利用受信任的平台（Steam）和流行的应用（Wallpaper Engine）感染玩家，可能导致凭证窃取、账户劫持和财务损失。 恶意壁纸属于“应用程序”类型，可以执行任意代码，该活动主要针对中国用户。部分壁纸已被下载数万次。

rss · Decrypt · Jun 19, 14:39

**背景**: Wallpaper Engine 是一款 Steam 应用，允许用户创建和分享动画或交互式桌面壁纸。部分壁纸是可执行的 Windows 应用程序，可能被滥用来运行恶意软件。信息窃取器是一种恶意软件，用于窃取登录凭证和财务数据等个人信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kaspersky.com/about/press-releases/kaspersky-discovered-a-malware-campaign-targeting-steam-users-through-infected-wallpaper">Kaspersky discovered a malware campaign targeting Steam users through infected wallpaper</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/steam-workshop-abused-to-spread-malware-via-wallpaper-engine-app/">Steam Workshop abused to spread malware via Wallpaper Engine app</a></li>
<li><a href="https://steamcommunity.com/app/431960/discussions/2/569289424252266099/">Malware in wallpapers? :: Wallpaper Engine General Discussions</a></li>

</ul>
</details>

**社区讨论**: Steam 上的社区评论指出，该问题仅限于应用程序类型的壁纸，主要针对中国用户，许多用户表示庆幸自己未受影响。一些用户建议使用杀毒软件扫描下载内容。

**标签**: `#cybersecurity`, `#malware`, `#steam`, `#infostealer`, `#wallpaper engine`

---

<a id="item-15"></a>
## [Base Beryl 升级与 B20 代币标准将于 6 月 25 日上线](https://www.theblock.co/post/405410/base-targets-june-25-mainnet-launch-for-beryl-upgrade-and-new-b20-token-standard?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Base 的 Beryl 升级引入了 B20 原生代币标准，并将提款延迟缩短至 5 天，将于 2026 年 6 月 25 日在主网上激活。 B20 标准将合规工具直接嵌入协议层，使 Base 对受监管的稳定币和现实世界资产更具吸引力，同时更快的提款改善了桥接资金的用户体验。 B20 是 Base 自有的 ERC-20 版本，内置转账策略、冻结与没收、基于角色的访问控制、备注和供应上限。节点运营商必须在切换前升级到 base-reth-node v1.1.1+ 或 base-consensus v1.1.1+。

rss · The Block · Jun 19, 10:48

**背景**: Base 是由 Coinbase 开发的基于以太坊的 Layer-2 区块链。像 ERC-20 这样的代币标准定义了代币在区块链上的行为方式。B20 标准旨在原生提供监管合规功能，这对于数字资产的机构采用非常重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.base.org/base-chain/specs/upgrades/beryl/b20">B 20 Native Token Standard - Base Documentation</a></li>
<li><a href="https://cryptobriefing.com/base-b20-token-standard-stablecoins-rwas/">Base 's Jesse Pollak unveils B 20 token standard for stablecoins and...</a></li>
<li><a href="https://www.spotedcrypto.com/base-beryl-upgrade-june-25-2026-b20-token-standard/">Base Beryl Upgrade June 25 2026: B20 Token Standard, Faster</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#cryptocurrency`, `#token standard`, `#Base`, `#upgrade`

---