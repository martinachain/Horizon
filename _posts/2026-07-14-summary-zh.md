---
layout: default
title: "Horizon Summary: 2026-07-14 (ZH)"
date: 2026-07-14
lang: zh
---

> From 64 items, 15 important content pieces were selected

---

1. [Git History 命令：交互式变基的更安全替代方案](#item-1) ⭐️ 7.0/10
2. [无需 Xcode，通过命令行构建 Mac/iOS 应用](#item-2) ⭐️ 7.0/10
3. [苹果 SpeechAnalyzer API 与 Whisper 基准测试对比](#item-3) ⭐️ 7.0/10
4. [加州法案拟禁止无限滚动等成瘾性 UX 设计](#item-4) ⭐️ 7.0/10
5. [Sega CD《Silpheed》的艺术与工程](#item-5) ⭐️ 7.0/10
6. [多家大型银行加入英国代币化工作组](#item-6) ⭐️ 7.0/10
7. [Claude 的个性因模型和语言而异](#item-7) ⭐️ 7.0/10
8. [Robinhood Chain 被 Memecoin 占领，背离代币化股票初衷](#item-8) ⭐️ 6.0/10
9. [玻利维亚考虑将 Tether 的 USDT 纳入国家支付系统](#item-9) ⭐️ 6.0/10
10. [SBI Holdings 转向 Solana 进行代币化和稳定币发行](#item-10) ⭐️ 6.0/10
11. [OpenAI GPT-5.6 指南：停止过度提示](#item-11) ⭐️ 6.0/10
12. [抗议者游行要求 AI 巨头暂停开发](#item-12) ⭐️ 6.0/10
13. [中国拟将加密货币混币器、隐私币视为洗钱迹象](#item-13) ⭐️ 6.0/10
14. [日本最大证券代币平台将 27 亿美元资产迁移至 Avalanche](#item-14) ⭐️ 6.0/10
15. [泰国央行审计大额稳定币交易](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Git History 命令：交互式变基的更安全替代方案](https://lalitm.com/post/git-history/) ⭐️ 7.0/10

一篇博文提倡使用 `git history` 命令作为交互式变基的更安全、更直观的替代方案，强调其能自动重写所有后代分支。 这很重要，因为许多开发者因交互式变基的复杂性和破坏仓库的风险而畏惧它，而 `git history` 提供了一种更不易出错的工作流来整理提交历史，可能改善团队协作和代码审查。 `git history` 命令会自动查找并重写从被编辑提交派生的所有本地分支，而 `git rebase --update-refs` 仅移动变基范围内的引用。但目前它不支持对修改后的提交进行签名，这对于需要加密验证的用户来说是一个限制。

hackernews · turbocon · Jul 14, 00:57 · [社区讨论](https://news.ycombinator.com/item?id=48901010)

**背景**: Git 历史编辑通常通过交互式变基（`git rebase -i`）完成，它允许压缩、重新排序或修改提交。但交互式变基可能令人生畏且容易出错，尤其是在处理多个分支时。`git history` 命令在 Git 2.23 中引入，提供了一个更高级的接口，自动处理分支重写，减少了手动步骤和潜在错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History">Git - Viewing the Commit History</a></li>
<li><a href="https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase">Git rebase | Atlassian Git Tutorial</a></li>
<li><a href="https://stackoverflow.com/questions/7435452/history-or-log-of-commands-executed-in-git">History or log of commands executed in Git - Stack Overflow</a></li>

</ul>
</details>

**社区讨论**: 社区讨论意见不一：一些用户称赞 `git history` 的安全性和便利性，而另一些用户则认为交互式变基并不像描述的那样可怕，并指出存在 `--abort` 和重置选项。提出的一个关键问题是 `git history` 缺乏提交签名支持，这对某些人来说是决定性的障碍。

**标签**: `#git`, `#version control`, `#developer tools`, `#workflow`

---

<a id="item-2"></a>
## [无需 Xcode，通过命令行构建 Mac/iOS 应用](https://scottwillsey.com/building-and-shipping-mac-and-ios-apps-without-ever-opening-xcode/) ⭐️ 7.0/10

一篇详细指南展示了如何完全通过命令行和自动化脚本构建、签名、公证并发布 Mac 和 iOS 应用，完全绕过 Xcode IDE。 这种方法使开发者能够将 Apple 应用开发集成到 CI/CD 流水线中，并利用基于 LLM 的编码代理，可能加速工作流程并减少对 Apple 重量级 IDE 的依赖。 该指南使用命令行工具如`xcodebuild`、`codesign`和`notarytool`，并建议使用 LLM 代理（如 Claude Code）生成自动化脚本。社区评论提到了替代工具如 xtool，可用于在 Linux 上构建 iOS 应用。

hackernews · speckx · Jul 13, 18:22 · [社区讨论](https://news.ycombinator.com/item?id=48896665)

**背景**: 传统上，开发和发布 Apple 平台应用需要 Xcode，即 Apple 的集成开发环境。然而，Xcode 体积庞大、仅限 macOS，且不适合自动化。Xcode 附带的命令行工具（如 xcodebuild）允许无需 GUI 构建应用，但签名和公证的完全自动化一直很复杂。本指南简化了这一过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://stackoverflow.com/questions/69315164/how-to-create-an-ios-app-build-using-command-line-tool-without-xcode/69315458">swift - How to create an iOS app build using command line tool...</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了对在主机上无沙箱运行 LLM 代理的安全担忧，引用了凭证泄露等风险。一些人分享了替代工具，如用于 Linux 上 iOS 开发的 xtool 和面向 LLM 的 Apple 开发工具 Axiom。总体情绪积极但谨慎。

**标签**: `#iOS development`, `#automation`, `#Xcode`, `#CLI`, `#security`

---

<a id="item-3"></a>
## [苹果 SpeechAnalyzer API 与 Whisper 基准测试对比](https://get-inscribe.com/blog/apple-speech-api-benchmark.html) ⭐️ 7.0/10

一项新的基准测试将苹果在 WWDC 2025 上推出的 SpeechAnalyzer API 与 OpenAI 的 Whisper 及苹果之前的语音框架进行了比较，结果显示其速度更快但准确率略低。 这一比较意义重大，因为苹果的设备端 API 可能会颠覆那些封装 Whisper 的付费应用，在 macOS 和 iOS 上提供原生、更快的转录功能，可能重塑语音转文字市场。 基准测试在数学讲座上对 SpeechAnalyzer 和 Whisper-Large-V2 进行了对比，发现前者速度显著更快，准确率仅略低。SpeechAnalyzer 还支持流式传输，这是相比许多需要先录制完整音频再转录的模型的一大用户体验改进。

hackernews · get-inscribe · Jul 13, 16:06 · [社区讨论](https://news.ycombinator.com/item?id=48894752)

**背景**: Whisper 是 OpenAI 开发的开源 ASR 模型，在 68 万小时数据上训练，以强大的多语言转录能力著称。苹果的 SpeechAnalyzer 在 WWDC 2025 上推出，是一个模块化的设备端语音识别 API，取代了旧框架，旨在实现低延迟性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.argmaxinc.com/blog/apple-and-argmax">Apple SpeechAnalyzer and Argmax WhisperKit - Argmax</a></li>
<li><a href="https://www.callstack.com/blog/on-device-speech-transcription-with-apple-speechanalyzer">On-Device Speech Transcription with Apple SpeechAnalyzer and AI SDK</a></li>
<li><a href="https://en.wikipedia.org/wiki/Whisper_(speech_recognition_system)">Whisper (speech recognition system)</a></li>

</ul>
</details>

**社区讨论**: 评论者指出 Whisper 已不再是业界最先进模型；Nvidia 的 Nemotron 和 Parakeet、Mistral 的 Voxtral 以及 Cohere Transcribe 等新模型提供了更高准确率。有人预测苹果的原生 API 将使付费的 Whisper 封装应用过时，而其他人则称赞流式支持是用户体验的重大胜利。

**标签**: `#speech recognition`, `#Apple`, `#Whisper`, `#benchmark`, `#ASR`

---

<a id="item-4"></a>
## [加州法案拟禁止无限滚动等成瘾性 UX 设计](https://www.sfgate.com/politics/article/meta-social-media-teenagers-22337724.php) ⭐️ 7.0/10

加州拟议的 SB 976 法案（《保护我们的孩子免受社交媒体成瘾法案》）可能禁止社交媒体平台向未成年人提供无限滚动等成瘾性功能。该法案已于 2024 年 9 月签署成为法律，规定向 18 岁以下用户提供成瘾性信息流和某些功能属于违法行为。 这项立法可能为监管广泛使用但被批评为促进强迫性使用的 UX 设计模式开创先例。如果实施，将迫使 Instagram、TikTok 和 Facebook 等平台为未成年人重新设计核心用户体验，可能重塑社交媒体格局。 该法案特别针对使用算法根据用户数据推荐内容的“成瘾性信息流”，以及消除自然停止点的无限滚动等功能。平台需要为未成年人提供非成瘾版本，默认使用时间线排序，并在特定时段限制通知。

hackernews · Stratoscope · Jul 13, 18:53 · [社区讨论](https://news.ycombinator.com/item?id=48897104)

**背景**: 无限滚动是一种 UX 设计技术，当用户滚动时自动加载新内容，消除了分页。社交媒体和内容平台广泛使用它来提高参与度，但批评者认为它利用心理脆弱性让用户上瘾。成瘾性设计模式是暗黑模式的一个子集，驱使强迫性行为，违背用户利益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/design-bootcamp/the-scroll-that-never-sleeps-how-ux-keeps-us-hooked-5bb86740e308">The Scroll That Never Sleeps — How UX Keeps Us Hooked | Medium</a></li>
<li><a href="https://builtin.com/articles/infinite-scroll">Infinite Scroll Advantages and Disadvantages | Built In</a></li>
<li><a href="https://oag.ca.gov/sb976">Protecting Our Kids from Social Media Addiction Act (SB 976) | State of California - Department of Justice - Office of the Attorney General</a></li>

</ul>
</details>

**社区讨论**: 评论者就良好 UX 与成瘾性设计之间的界限展开了辩论。一些人认为无限滚动显然是不必要的，旨在让用户更长时间停留在应用上；而另一些人则质疑媒体预览等功能是成瘾性还是仅仅方便。少数人建议禁止定向广告作为更根本的解决方案。

**标签**: `#UX design`, `#regulation`, `#social media`, `#addictive features`, `#California law`

---

<a id="item-5"></a>
## [Sega CD《Silpheed》的艺术与工程](https://fabiensanglard.net/silpheed/index.html) ⭐️ 7.0/10

Fabien Sanglard 发表了一篇技术深度分析文章，揭示了 Sega CD 游戏《Silpheed》如何利用全动态视频（FMV）模拟 3D 多边形图形，以及其令人印象深刻的视觉效果背后的工程技巧。 这篇文章罕见地揭示了 1990 年代早期游戏开发者如何在硬件限制下发挥创造力，并突出了 FMV 与 3D 模拟的结合对后来游戏设计的影响。 Sega CD 上的《Silpheed》是一款 FMV 游戏，利用预渲染视频营造 3D 空间的错觉，玩家飞船和敌人被合成到视频之上。文章详细介绍了实现这一效果所采用的视频压缩、调色板技巧和同步技术。

hackernews · ibobev · Jul 13, 14:52 · [社区讨论](https://news.ycombinator.com/item?id=48893639)

**背景**: 全动态视频（FMV）游戏使用预录制的视频文件而非实时渲染的图形来显示动作。Sega CD 是 Sega Genesis 的附加组件，3D 能力有限，因此开发者常使用 FMV 来创造电影化体验。《Silpheed》以将 FMV 与交互式游戏玩法融合而著称，使其感觉像一部可玩的电影。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://fabiensanglard.net/silpheed/index.html">The art and engineering of Sega CD Silpheed</a></li>
<li><a href="https://en.wikipedia.org/wiki/Silpheed">Silpheed - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/FMV_game">FMV game</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞了这篇文章，并分享了关于《Silpheed》的怀旧回忆，有人称其“与众不同”，感觉像在控制一部电影。其他人则提到了相关的演示场景成就，例如 Mega Drive 演示“Overdrive 2”，它以类似方式突破了硬件限制。

**标签**: `#retro gaming`, `#game development`, `#Sega CD`, `#technical deep-dive`, `#demoscene`

---

<a id="item-6"></a>
## [多家大型银行加入英国代币化工作组](https://www.coindesk.com/business/2026/07/13/uk-government-unveils-tokenization-taskforce-with-blackrock-goldman-jpmorgan-morgan-stanley) ⭐️ 7.0/10

英国政府成立了一个由 54 家公司组成的代币化工作组，成员包括贝莱德、高盛、摩根大通和摩根士丹利，旨在探索基于区块链的资产代币化在批发市场的实际应用场景。 这一举措标志着机构对代币化的强烈认可，可能加速监管框架的建立以及数字资产在传统金融中的主流整合。 该工作组既包括传统金融巨头，也包括 Ripple 和 Coinbase 等加密原生公司，旨在测试债券和回购协议等批发市场的代币化应用。

rss · CoinDesk · Jul 13, 11:40

**背景**: 资产代币化是指将现实世界资产（如债券、房地产）的所有权以数字代币形式记录在区块链上，从而实现部分所有权和更快的结算。英国一直积极将自己定位为对加密货币友好的中心，该工作组是更广泛地将区块链融入金融基础设施的努力的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://coincentral.com/uk-tokenization-taskforce-adds-ripple-blackrock-goldman-sachs-and-jpmorgan/">UK Tokenization Taskforce Adds Ripple, BlackRock, Goldman ...</a></li>
<li><a href="https://www.cryptopolitan.com/uk-tokenization-task-force-with-blackrock/">Circle, Ripple and Coinbase join UK tokenization task force ...</a></li>
<li><a href="https://coinfomania.com/blackrock-joins-uk-tokenization-taskforce-and-why-its-not-just-hype/">BlackRock Joins UK Tokenization Taskforce — And Why It's Not ...</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#blockchain`, `#finance`, `#regulation`

---

<a id="item-7"></a>
## [Claude 的个性因模型和语言而异](https://decrypt.co/373422/anthropic-claude-personality-changes-model-language) ⭐️ 7.0/10

Anthropic 的新研究发现，Claude 会根据模型变体和使用的语言持续表达不同的价值观，表明其在不同部署中缺乏价值观一致性。 这一发现引发了对 AI 对齐和安全性的担忧，尤其是在多语言 AI 系统中，不一致的价值观可能导致不同用户群体中出现不可预测或有害的行为。 该研究专门考察了 Claude 在不同模型版本（如 Claude 3、Claude 4）和语言（如英语、中文、西班牙语）中表达的价值观，发现了系统性变化而非随机噪声。

rss · Decrypt · Jul 13, 20:39

**背景**: AI 对齐研究旨在确保 AI 系统按照人类价值观和意图行事。像 Claude 这样的多语言 AI 系统使用多种语言的数据进行训练，但价值观对齐通常以英语进行，这可能无法完美迁移到其他语言。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/research/team/alignment">Alignment Research \ Anthropic</a></li>
<li><a href="https://arxiv.org/html/2402.18120v1">Exploring Multilingual Human Value Concepts in Large Language ...</a></li>

</ul>
</details>

**标签**: `#AI alignment`, `#Anthropic`, `#multilingual AI`, `#model behavior`

---

<a id="item-8"></a>
## [Robinhood Chain 被 Memecoin 占领，背离代币化股票初衷](https://www.coindesk.com/tech/2026/07/13/robinhood-built-a-blockchain-for-tokenized-stocks-memecoins-took-over) ⭐️ 6.0/10

Robinhood Chain 是一个于 2026 年 7 月 1 日推出的以太坊 Layer 2 区块链，其每周 DEX 交易量已达 31 亿美元，用户数达 6.5 万，但链上活动以 memecoin 交易为主，而非预期的代币化股票。 这凸显了将区块链应用引导至受监管金融资产的挑战，因为无许可环境自然会吸引投机性 memecoin 交易，可能削弱 Robinhood 代币化传统股票的目标。 Robinhood Chain 是一个以太坊 Layer 2 扩容方案，旨在支持代币化股票，但据 Bernstein 称，自上线以来，memecoin 交易占据了其每周 31 亿美元 DEX 交易量的大部分。

rss · CoinDesk · Jul 13, 15:17

**背景**: 代币化股票是传统股票的区块链表示形式，允许分式所有权和 24/7 交易。像 Robinhood Chain 这样的 Layer 2 区块链构建在以太坊之上，以提高交易速度并降低成本。Memecoin 是高度波动的加密货币，通常基于网络迷因，吸引投机交易者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cryptotimes.io/learn/what-is-robinhood-chain/">What Is Robinhood Chain ? Ethereum Layer 2 Explained</a></li>
<li><a href="https://www.coingecko.com/learn/what-are-tokenized-stocks">What Are Tokenized Stocks and Top Platforms to Get Started</a></li>
<li><a href="https://en.wikipedia.org/wiki/Layer-1_blockchain">Layer-1 blockchain</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#cryptocurrency`, `#memecoins`, `#Robinhood`, `#tokenization`

---

<a id="item-9"></a>
## [玻利维亚考虑将 Tether 的 USDT 纳入国家支付系统](https://www.coindesk.com/business/2026/07/13/bolivia-weighs-adding-tether-s-usdt-to-its-national-payments-system) ⭐️ 6.0/10

玻利维亚经济部长 José Gabriel Espinoza 于 2026 年 7 月 10 日宣布，政府正在技术评估是否可以将 Tether 的 USDT 稳定币与美元和玻利维亚诺一起纳入国家支付系统流通。 如果获批，这将标志着国家政府在加密货币采用方面迈出重要一步，可能使玻利维亚经济现代化，并在美元短缺的情况下提供稳定的数字替代方案。这也可能为其他国家探索稳定币整合树立先例。 该评估是初步的，尚未做出最终决定。USDT 是全球市值最大的稳定币，与美元 1:1 挂钩，不同于中央银行数字货币（CBDC）。

rss · CoinDesk · Jul 13, 14:47

**背景**: Tether（USDT）是 Tether Limited 于 2014 年推出的加密货币稳定币，旨在保持与美元的稳定价值。玻利维亚面临美元短缺，正在探索数字替代方案以实现支付系统现代化并增强进入全球市场的渠道。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tether_(cryptocurrency)">Tether (cryptocurrency) - Wikipedia</a></li>
<li><a href="https://coinlaw.io/bolivia-usdt-payments/">Bolivia Weighs Adding USDT to Its National Payment System</a></li>
<li><a href="https://www.cryptotimes.io/2026/07/13/bolivia-weighs-usdt-integration-into-national-payment-system/">Bolivia Weighs USDT Integration Into National Payment System</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#stablecoin`, `#payments`, `#regulation`, `#Bolivia`

---

<a id="item-10"></a>
## [SBI Holdings 转向 Solana 进行代币化和稳定币发行](https://www.coindesk.com/business/2026/07/13/sbi-holdings-blockchain-initiative-pivots-to-solana-for-tokenization-stablecoin-issuance) ⭐️ 6.0/10

SBI Holdings 与 Solana 基金会宣布战略合作，共同打造基于日本的链上金融市场，并将 SBI R3 Japan 更名为 SBI Solana Global。 这一转向表明机构对 Solana 在现实世界资产代币化和稳定币发行方面的采用日益增长，可能加速区块链在传统金融中的主流整合。 原本专注于 R3 Corda 的 SBI R3 Japan 将更名为 SBI Solana Global，Solana 基金会作为关键合作伙伴。SBI 此前已为机构客户推出 SOL 服务，并与 B2C2 合作在 Solana 上提供路由服务。

rss · CoinDesk · Jul 13, 11:40

**背景**: SBI Holdings 是日本大型金融集团，拥有加密货币交易所、Ripple 投资和区块链基金。Solana 是一种高性能区块链，以低费用和高吞吐量著称，越来越多地用于代币化和去中心化金融。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/408010/sbi-holdings-solana-foundation-partner-to-build-japan-based-onchain-financial-market">SBI Holdings, Solana Foundation partner to build... | The Block</a></li>
<li><a href="https://www.kucoin.com/news/flash/japanese-megabank-smfg-and-sbi-launch-onchain-finance-venture-on-solana">Japanese Megabank SMFG and SBI Launch Onchain... | KuCoin</a></li>
<li><a href="https://msbintel.com/articles/sbi-holdings-and-solana-foundation-partner-on-japan-onchain-fina">SBI Holdings and Solana Foundation partner on Japan... — MSB Intel</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#Solana`, `#tokenization`, `#stablecoin`, `#institutional adoption`

---

<a id="item-11"></a>
## [OpenAI GPT-5.6 指南：停止过度提示](https://decrypt.co/373439/openai-new-gpt-5-6-prompt-guide-chatgpt) ⭐️ 6.0/10

OpenAI 发布了针对 GPT-5.6 的新提示指南，建议用户明确目标、设置停止条件，并避免使用过多指令或 XML 块进行过度提示。 该指南标志着从复杂的提示工程向更简单的目标导向交互的转变，可能将 token 使用量减少高达 66%，使 AI 对日常用户更高效。 该指南引入了三种模型变体——Sol、Terra 和 Luna——具有不同的推理级别，并建议使用 Pro 模式和详细程度设置来控制输出长度和细节。

rss · Decrypt · Jul 13, 22:46

**背景**: 提示工程发展迅速，到 2024 年已识别出 50 多种不同技术。过度提示（用户提供过多指令）会增加认知负担，导致响应变慢且容易出错。OpenAI 的新方法强调简洁清晰的提示，让模型发挥自身推理能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/373439/openai-new-gpt-5-6-prompt-guide-chatgpt">Stop Over-Prompting: OpenAI’s New GPT-5.6 Guidelines Change ...</a></li>
<li><a href="https://felloai.com/gpt-5-6-prompting-guide/">GPT-5.6 Prompting Guide: 7 Tips for Better Answers</a></li>
<li><a href="https://signalwire.com/blogs/developers/why-over-prompting-kills-ai">Less Is More: Why Over-Prompting Kills Your AI Agent | SignalWire</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#GPT-5.6`, `#prompting`, `#AI guidelines`

---

<a id="item-12"></a>
## [抗议者游行要求 AI 巨头暂停开发](https://decrypt.co/373433/stop-ai-protest-openai-anthropic-google-deepmind) ⭐️ 6.0/10

周六，约 200 名抗议者在旧金山游行至 OpenAI、Anthropic 和 Google DeepMind 的办公室，要求出于安全、就业和环境考虑，暂停开发更强大的 AI 模型。 此次抗议凸显了公众对 AI 快速发展日益增长的不安，可能影响公众讨论和监管对 AI 安全、就业替代和能源消耗的关注。 抗议由组织“Stop AI”发起，约有 200 人参与，规模相对较小，但象征性地同时针对三家领先的 AI 公司。

rss · Decrypt · Jul 13, 22:11

**背景**: AI 开发迅速加速，OpenAI、Anthropic 和 Google DeepMind 等公司不断突破大型语言模型和其他 AI 系统的边界。人们担忧潜在风险，如工作自动化、高能耗数据中心对环境的影响，以及能力日益增强的 AI 的安全性。公众抗议反映了关于如何平衡创新与预防的更广泛社会辩论。

**标签**: `#AI safety`, `#protest`, `#public concern`, `#AI development`

---

<a id="item-13"></a>
## [中国拟将加密货币混币器、隐私币视为洗钱迹象](https://decrypt.co/373374/chinese-prosecutors-float-treating-crypto-mixer-privacy-coin-use-as-sign-of-money-laundering) ⭐️ 6.0/10

中国检察官提出新规，将使用加密货币混币器和隐私币视为洗钱迹象，同时提出新的区块链证据规则和用于出售被扣押加密货币的国家平台。 该提案标志着中国对加密货币监管的显著收紧，可能影响注重隐私的加密服务及用户，并为区块链证据在法庭上的处理开创先例。 该提案包括对使用混币器或隐私币的意图推定，并呼吁建立中央国家平台来拍卖被扣押的加密资产。它发表在最高检察官的刊物上，表明官方正在考虑。

rss · Decrypt · Jul 13, 10:43

**背景**: 加密货币混币器（又称 tumblers）是一种通过混合交易来模糊加密货币发送方和接收方之间联系的服务。像 Monero 这样的隐私币旨在增强交易匿名性。中国已禁止加密货币交易和挖矿，但该提案将使用隐私增强工具视为潜在的洗钱迹象。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coinbase.com/learn/your-crypto/what-is-a-bitcoin-mixer">What is a Bitcoin mixer? - Coinbase</a></li>
<li><a href="https://koinly.io/crypto-glossary/privacy-coin/">What is a Privacy Coin ? | Koinly</a></li>
<li><a href="https://www.frontiersin.org/journals/blockchain/articles/10.3389/fbloc.2024.1306058/full">Frontiers | Blockchain in the courtroom: exploring its evidentiary significance and procedural implications in U.S. judicial processes</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#money laundering`, `#blockchain`, `#privacy`

---

<a id="item-14"></a>
## [日本最大证券代币平台将 27 亿美元资产迁移至 Avalanche](https://www.theblock.co/post/408036/japans-largest-security-token-platform-moves-nearly-3-billion-to-avalanche-blockchain?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

日本最大的证券代币平台 Progmat 已完成迁移，将超过 4520 亿日元（约 27-33 亿美元）的代币化资产从私有 Corda 5 账本转移至专用的公共 Avalanche Layer 1 区块链。 此次迁移表明机构对公共区块链用于受监管证券代币的接受度日益提高，可能为日本及全球其他大规模代币化项目树立先例。 Progmat 此前运行在 Corda（一种企业分布式账本系统）上，现在使用通过 AvaCloud 部署的特定应用 Avalanche L1。该平台占日本证券代币市场总发行价值的 64.6%。

rss · The Block · Jul 13, 14:29

**背景**: 证券代币是传统金融资产（如债券或房地产）在区块链上的数字表示。Progmat 是日本发行和管理此类代币的领先基础设施提供商。Avalanche 是一个公共区块链平台，以其高吞吐量和可定制的子网而闻名，适合企业用例。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://financefeeds.com/progmat-moves-2-7-billion-token-platform-to-avalanche/">Progmat Moves $2.7 Billion Token Platform to... - FinanceFeeds</a></li>
<li><a href="https://cryip.co/progmat-452-billion-security-token-avalanche-l1/">Progmat Moves ¥452 Billion Security Token Platform to... | Cryip</a></li>
<li><a href="https://blockchain.news/news/progmat-avalanche-migration">Progmat Completes Avalanche Migration, ¥452B in... - Blockchain.News</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#security tokens`, `#Avalanche`, `#Japan`

---

<a id="item-15"></a>
## [泰国央行审计大额稳定币交易](https://www.theblock.co/post/407998/bank-of-thailand-audits-stablecoin?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

泰国央行和证券交易委员会已开始使用数据分析工具审计大额稳定币交易，重点关注 Tether 的 USDT，以打击非法金融活动。 这标志着泰国在稳定币监管方面迈出了重要一步，可能为其他国家监控稳定币流动以预防金融犯罪树立先例。 审计重点关注异常稳定币交易，尤其是 USDT——流通量超过 1870 亿美元的最大稳定币。央行和证交会正使用数据分析工具检测可疑模式。

rss · The Block · Jul 13, 08:19

**背景**: USDT 等稳定币是与法定货币挂钩的加密货币，常用于交易和支付。其高流动性和匿名性使其对洗钱等非法活动具有吸引力。泰国一直在制定稳定币监管框架，包括泰铢稳定币。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://coinalertnews.com/news/2026/06/27/thai-baht-stablecoin-framework">Thailand Central Bank Nears Thai Baht Stablecoin Regulation ...</a></li>
<li><a href="https://www.coindesk.com/markets/2026/01/12/tether-freezes-usd182-million-in-usdt-stablecoin-across-five-tron-blockchain-wallets">Stablecoin giant Tether freezes $182 million in USDT across five Tron...</a></li>

</ul>
</details>

**标签**: `#stablecoin`, `#regulation`, `#cryptocurrency`, `#financial crime`

---