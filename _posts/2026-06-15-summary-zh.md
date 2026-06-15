---
layout: default
title: "Horizon Summary: 2026-06-15 (ZH)"
date: 2026-06-15
lang: zh
---

> From 40 items, 12 important content pieces were selected

---

1. [里约热内卢的“自研”大语言模型被曝是权重合并](#item-1) ⭐️ 8.0/10
2. [Jane Street 谈形式化方法与 AI 驱动的验证](#item-2) ⭐️ 8.0/10
3. [美国政府要求 Anthropic 撤回 Claude Fable 和 Mythos AI 模型](#item-3) ⭐️ 8.0/10
4. [谷歌起诉中国团伙利用 Gemini AI 进行钓鱼诈骗](#item-4) ⭐️ 8.0/10
5. [有效 ePub 文件因 Adobe RMSDK 在 Kobo 上显示异常](#item-5) ⭐️ 7.0/10
6. [Kage：将任意网站存档为单个离线二进制文件](#item-6) ⭐️ 7.0/10
7. [Windows 11 用户对微软账户要求感到不满](#item-7) ⭐️ 7.0/10
8. [Coinbase 报告：地址重用使数百万比特币面临量子威胁](#item-8) ⭐️ 7.0/10
9. [Emacs 电池已包含：隐藏功能与社区争论](#item-9) ⭐️ 6.0/10
10. [Trace：离线 Mac 会议转录，支持会议中标记重点](#item-10) ⭐️ 6.0/10
11. [华尔街超越加密货币试点，深入以太坊](#item-11) ⭐️ 6.0/10
12. [AI 代理持信用卡导致财务损失](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [里约热内卢的“自研”大语言模型被曝是权重合并](https://github.com/nex-agi/Nex-N2/issues/4) ⭐️ 8.0/10

里约热内卢市政府发布了 Rio-3.5-Open-397B，声称是自研的 Qwen3.5 微调模型，但社区分析发现它实际上是约 60% Nex-N2 Pro 和 40% Qwen3.5-397B-A17B 的权重合并，且未适当披露。 这一事件削弱了开源 AI 开发的信任，凸显了模型溯源透明度标准的必要性，因为欺骗性做法可能误导社区并损害公信力。 Rio 模型的每个权重张量在所有 60 层和组件中都是 Nex 和 Qwen 的 0.6/0.4 混合，这与真正的微调不一致。该模型由里约的 IT 公司 IplanRIO 作为自研成果发布。

hackernews · unrvl22 · Jun 14, 15:37 · [社区讨论](https://news.ycombinator.com/item?id=48528371)

**背景**: 模型合并是一种将多个预训练模型的权重通过线性插值等方式组合的技术，无需额外训练即可创建新模型。mergekit 等工具简化了这一过程。在开源 AI 中，适当披露此类合并被视为透明度的基本要求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/arcee-ai/mergekit">GitHub - arcee-ai/mergekit: Tools for merging pretrained ...</a></li>
<li><a href="https://arxiv.org/html/2502.00706v1">Model Provenance Testing for Large Language Models - arXiv</a></li>

</ul>
</details>

**社区讨论**: 社区表达了强烈担忧，许多人称这是一种破坏信任的欺骗模式。一些评论者推测上传的模型缺少所声称的蒸馏步骤，而另一些人则注意到线性插值在保持性能方面的鲁棒性。

**标签**: `#LLM`, `#open-source`, `#ethics`, `#model provenance`, `#AI community`

---

<a id="item-2"></a>
## [Jane Street 谈形式化方法与 AI 驱动的验证](https://blog.janestreet.com/formal-methods-at-jane-street-index/?from_theconsensus=1) ⭐️ 8.0/10

Jane Street 发表了一篇博客文章，讨论了形式化方法在金融领域的实际应用，以及 AI 生成代码的兴起如何将程序员的角色转向验证。 这一讨论凸显了一个关键行业趋势：随着 AI 编写更多代码，人类的价值从编写转向验证正确性，使得形式化方法在确保软件可靠性方面变得越来越重要。 该文章引用了历史上的正确性证明工具（如 Boyer-Moore 证明器）和 Scala 3 中的现代类型系统，并指出如果设计不当，形式化规范可能遭受与测试相同的错误。

hackernews · eatonphil · Jun 14, 12:35 · [社区讨论](https://news.ycombinator.com/item?id=48526633)

**背景**: 形式化方法是基于数学的技术，用于指定和验证软件的正确性，常用于铁路、微处理器等安全关键系统。它们包括定理证明、模型检查和类型系统。Jane Street 是一家量化交易公司，其博客文章展示了这些方法如何在实际中用于确保金融软件的可靠性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.academia.edu/80981194/Formal_methods">(PDF) Formal methods</a></li>
<li><a href="https://en.wikipedia.org/wiki/Software_verification_and_validation">Software verification and validation - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Software_verification">Software verification - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了不同的观点：一些人赞扬向验证的转变，指出表达性类型有助于防止 AI 生成的代码问题，而另一些人质疑形式化规范是否只是“以不同方式编写的测试”，并且可能存在相同的错误。一位有历史经验的评论者指出，证明自动化早已存在，但仍需要人类引导。

**标签**: `#formal methods`, `#programming`, `#verification`, `#type systems`, `#AI`

---

<a id="item-3"></a>
## [美国政府要求 Anthropic 撤回 Claude Fable 和 Mythos AI 模型](https://decrypt.co/371027/us-government-orders-anthropic-pull-claude-fable-mythos-ai-models) ⭐️ 8.0/10

美国政府以存在广泛漏洞为由，命令 Anthropic 撤回其 Claude Fable 和 Mythos AI 模型。Anthropic 反驳称该命令属于监管越权，并指出该漏洞已在行业内普遍存在。 这标志着政府对先进 AI 模型的监管显著升级，可能为未来的干预行动树立先例。结果将影响 AI 公司如何平衡安全性、透明度和创新。 Claude Fable 5 是 Mythos 模型的公开版本，Anthropic 开发该模型用于发现软件漏洞。政府的命令同时针对公开的 Fable 模型和未发布的 Mythos 模型。

rss · Decrypt · Jun 13, 19:23

**背景**: Anthropic 是一家以 Claude 系列大语言模型闻名的 AI 安全公司。Mythos 模型旨在识别软件漏洞，但因安全顾虑尚未公开发布。政府的行动反映了对可能被滥用的 AI 能力的日益关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mythos_(model)">Mythos (model)</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#Anthropic`, `#government order`, `#AI safety`, `#Claude`

---

<a id="item-4"></a>
## [谷歌起诉中国团伙利用 Gemini AI 进行钓鱼诈骗](https://decrypt.co/371014/google-sues-chinese-crime-group-gemini-ai-phishing-scams) ⭐️ 8.0/10

谷歌已对名为“Outsider Enterprise”的中国网络犯罪团伙提起诉讼，指控其利用谷歌的 Gemini AI 创建了超过 9000 个钓鱼网站，并发送了数百万条虚假短信，窃取了数百万个信用卡号，并针对加密货币投资者。 此案凸显了一种新的威胁途径，即生成式 AI 被武器化用于大规模钓鱼攻击，使攻击更具说服力且更难检测。它强调了 AI 公司迫切需要实施防护措施，以防止其模型被恶意使用。 该团伙据称利用 Gemini AI 生成令人信服的钓鱼内容并自动化网站创建，从而快速扩大攻击规模。谷歌正在寻求法院命令以关闭该行动并索赔损失。

rss · Decrypt · Jun 13, 16:01

**背景**: 传统的钓鱼攻击依赖于手动制作的电子邮件或网站，但 AI 可以大规模生成高度个性化且语法正确的消息。谷歌的 Gemini AI 是一种多模态模型，能够生成文本、图像和代码，可能被滥用于创建虚假登录页面和诈骗信息。这起诉讼是针对 AI 驱动的网络犯罪的首批重大法律行动之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.digitaltrends.com/phones/scammers-used-gemini-ai-to-power-a-massive-phishing-operation-and-google-just-sued-them/">Scammers used Gemini AI to power a massive phishing operation ...</a></li>
<li><a href="https://hoodline.com/2026/06/google-slaps-outsider-gemini-scam-ring-with-massive-phishing-lawsuit/">Google Slaps 'Outsider' Gemini Scam Ring With Massive ...</a></li>

</ul>
</details>

**标签**: `#AI security`, `#phishing`, `#cybercrime`, `#Google`, `#Gemini`

---

<a id="item-5"></a>
## [有效 ePub 文件因 Adobe RMSDK 在 Kobo 上显示异常](https://andreklein.net/your-epub-is-fine-kobo-disagrees-blame-adobe/) ⭐️ 7.0/10

一位开发者发现，通过官方 epubcheck 验证的有效 ePub 文件，由于 Adobe RMSDK 渲染引擎的 bug，在 Kobo 电子阅读器上显示异常。这一问题凸显了 Adobe 软件的系统性质量问题及其 SDK 的封闭性。 此问题影响数百万依赖标准 ePub 文件的 Kobo 用户，并凸显了专有渲染引擎导致电子书生态互操作性失败的更广泛问题。同时引发对 Adobe 软件质量及其 SDK 对独立开发者缺乏可访问性的担忧。 开发者确认，相同的 ePub 文件在其他设备和软件上显示正常，因此问题锁定在 Kobo 使用的 Adobe RMSDK 上。即使文件通过 epubcheck 验证，问题依然存在，表明 RMSDK 并未完全符合 ePub 标准。

hackernews · sohkamyung · Jun 14, 22:54 · [社区讨论](https://news.ycombinator.com/item?id=48533848)

**背景**: ePub 是广泛使用的开放电子书标准，epubcheck 是确保合规的官方验证工具。Adobe 的 RMSDK（Reader Mobile SDK）是一种专有渲染引擎，被包括 Kobo 在内的许多电子阅读器制造商授权使用，用于显示 ePub 文件。然而，RMSDK 是闭源的，独立开发者难以访问或审计，导致持续存在的违反标准的渲染错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@jiminypan/five-interesting-facts-about-adobe-legacy-ebook-rmsdk-b7be0123c874">Five interesting facts about Adobe legacy eBook RMSDK | by Jiminy Panoz - Medium</a></li>
<li><a href="https://ebooks.stackexchange.com/questions/9098/disable-extra-page-numbers-showing-up-in-kobo">epub - Disable extra (page?) numbers showing up in kobo - Ebooks...</a></li>
<li><a href="https://www.mobileread.com/forums/showthread.php?t=271833">Errors with EPUB rendering on Kobo Aura H2O running... | Forum</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 Adobe 长期存在的质量问题表示沮丧，一位用户指出 Adobe 因糟糕的 QA 浪费了 Flash 的市场份额。另一位开发者报告称甚至无法联系 Adobe 以获取 RMSDK 许可，凸显了封闭的生态系统。一些用户建议将 ePub 转换为 Kobo 的 kepub 格式作为变通方案，而另一些用户则指出 ePub 标准本身也存在更广泛的问题。

**标签**: `#ePub`, `#Adobe`, `#Kobo`, `#e-reader`, `#software quality`

---

<a id="item-6"></a>
## [Kage：将任意网站存档为单个离线二进制文件](https://github.com/tamnd/kage) ⭐️ 7.0/10

Kage 是一款新的开源工具，可将任意网站克隆到文件夹中供离线浏览，并去除所有 JavaScript，还可选择将存档打包为单个自包含二进制文件，运行后即可提供网站服务。 该工具简化了对维基或文档等网站的离线访问，尤其适用于无网络区域，其单二进制输出便于分享，接收方无需安装任何软件。 Kage 提供 --format binary 选项，将存档附加到 Kage 自身副本上，生成单个可执行文件；它还支持使用作者的配套工具 ascii-gif 生成演示 GIF。

hackernews · tamnd · Jun 14, 17:25 · [社区讨论](https://news.ycombinator.com/item?id=48529990)

**背景**: 像 SingleFile 或 Wayback Machine 这样的网页存档工具可保存网页供离线使用，但通常生成多个文件或需要阅读器。Kage 创建单个二进制文件来提供网站服务的方法很新颖，因为它消除了依赖关系并简化了分发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/tamnd/kage">GitHub - tamnd/kage: Shadow any website for offline viewing ...</a></li>
<li><a href="https://news.ycombinator.com/item?id=48529990">Show HN: Kage – Shadow any website to a single binary for ...</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了离线公司维基和向编码代理提供网站等用例。一些人指出 SingleFile 在单页存档方面更强大，而另一些人质疑为何静态内容需要服务器，建议采用纯 HTML 方式。

**标签**: `#offline`, `#archiving`, `#web`, `#tool`, `#static-site`

---

<a id="item-7"></a>
## [Windows 11 用户对微软账户要求感到不满](https://www.windowscentral.com/microsoft/windows-11/windows-11-users-are-tired-of-microsoft-account-requirements-and-workarounds) ⭐️ 7.0/10

Windows 11 用户对微软强制要求使用微软账户访问系统功能感到日益不满，许多人正在寻找变通方法或转向其他操作系统。 这一趋势凸显了微软对生态系统整合的渴望与用户对隐私和本地控制的偏好之间的日益紧张关系，可能影响 Windows 11 的采用率和用户忠诚度。 用户报告了诸如关联微软账户后进入受限模式、难以切换回本地账户，以及 BitLocker 恢复密钥与在线账户绑定等问题。

hackernews · josephcsible · Jun 14, 21:42 · [社区讨论](https://news.ycombinator.com/item?id=48533101)

**背景**: 微软一直在逐步将其在线服务整合到 Windows 中，要求使用微软账户进行设备设置、应用商店访问和数据同步等功能。这一转变遭到了偏好本地账户以保护隐私和简化操作的用户抵制。

**社区讨论**: 评论者表达了沮丧和无奈的情绪，一些人分享了变通方法或宣布已转向 Linux。其他人则指出了具体问题，如受限模式和 BitLocker 密钥管理，少数人质疑用户实际上能采取什么措施来抵制。

**标签**: `#Windows 11`, `#Microsoft`, `#user experience`, `#privacy`, `#OS`

---

<a id="item-8"></a>
## [Coinbase 报告：地址重用使数百万比特币面临量子威胁](https://www.theblock.co/post/404685/coinbase-quantum-report-flags-exchange-cold-wallets-among-millions-of-bitcoin-exposed-by-address-reuse?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Coinbase 发布报告警告，地址重用使数百万比特币（包括交易所冷钱包）面临量子计算攻击风险，并建议设定迁移截止日期以冻结易受攻击的币。 这凸显了比特币的一个重大安全漏洞，如果量子计算机成熟，可能导致大规模盗窃，影响交易所和个人持有者。 地址重用会暴露公钥，量子计算机可利用这些公钥伪造签名并窃取资金。报告建议设定迁移至抗量子地址的截止日期，之后易受攻击的币将被冻结。

rss · The Block · Jun 13, 18:21

**背景**: 比特币交易需要发送者用私钥生成数字签名以证明所有权。如果公钥暴露（例如通过地址重用），足够强大的量子计算机可能推导出私钥并花费资金。地址重用是已知的隐私风险，但在量子未来也是安全风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.projecteleven.com/blog/quantum-vulnerability-of-bitcoin-addresses">Quantum vulnerability of Bitcoin addresses | Project Eleven</a></li>
<li><a href="https://www.deloitte.com/nl/en/services/consulting-risk/perspectives/quantum-computers-and-the-bitcoin-blockchain.html">Quantum computers and the Bitcoin blockchain | Deloitte</a></li>
<li><a href="https://www.coindesk.com/tech/2026/04/25/clock-is-ticking-for-bitcoin-to-prevent-quantum-threat-as-it-could-drain-6-9-million-btc-including-satoshi-s">Bitcoin might be at risk from a new quantum math trick that breaks digital ownership</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#quantum computing`, `#cryptocurrency security`, `#address reuse`

---

<a id="item-9"></a>
## [Emacs 电池已包含：隐藏功能与社区争论](https://karthinks.com/software/even-more-batteries-included-with-emacs/) ⭐️ 6.0/10

Karthinks 的一篇新博客文章重点介绍了 Emacs 中鲜为人知的功能，如 ruler-mode 和文本缩放，延续了“电池已包含”理念，是该系列的第三篇。 这篇文章强调了 Emacs 作为高度可扩展编辑器的持久价值，但社区讨论揭示了其丰富的内置功能与稳定性和可发现性问题之间的持续紧张关系。 该文章是该系列的第三篇，延续了之前的“电池已包含”报告，旨在通过演示被忽视的功能来提高可发现性。社区评论显示了对稳定性的不同体验，尤其是在 Doom Emacs 和 Spacemacs 中。

hackernews · signa11 · Jun 15, 02:30 · [社区讨论](https://news.ycombinator.com/item?id=48535886)

**背景**: Emacs 是一款高度可定制的文本编辑器，以其“电池已包含”理念而闻名，即内置了许多功能，如文件管理（Dired）、org-mode 和电子邮件客户端。然而，其庞大的功能集可能难以被发现，用户通常依赖社区发行版（如 Doom Emacs 或 Spacemacs）以获得更稳定的体验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://karthinks.com/software/even-more-batteries-included-with-emacs/">Even More Batteries Included with Emacs | Karthinks</a></li>
<li><a href="https://news.ycombinator.com/item?id=29342176">Batteries included with Emacs (2020) - Hacker News</a></li>
<li><a href="https://www.reddit.com/r/emacs/comments/s4za7y/emacs_discoverability/">r/emacs on Reddit: Emacs discoverability</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些用户称赞稳定性（例如 Doom Emacs 用户 QwenGlazer9000），而另一些用户则抱怨更新后出现问题（例如 buzzwords）。长期用户如 tptacek 承认不理解 Dired，gnulinux 则指出由于包组合的稳定性问题而转向 VSCode。

**标签**: `#Emacs`, `#text editors`, `#software tools`, `#productivity`

---

<a id="item-10"></a>
## [Trace：离线 Mac 会议转录，支持会议中标记重点](https://traceapp.info/) ⭐️ 6.0/10

Trace 是一款全新的 Mac 应用，可通过全局快捷键激活，完全离线录制和转录会议，并允许用户在通话中标记关键时刻并添加备注，这些备注会内联显示在转录文本中。 它通过快速激活和设备端处理解决了现有转录工具的痛点，增强了隐私性并优化了工作流程，适合那些需要频繁记录会议笔记但又不希望打断专注的用户。 Trace 使用 macOS API 将对话双方分别录制为独立音轨，在设备端运行说话人分离以标记发言人，并将转录结果以 Markdown 文件形式保存在本地；唯一的网络调用是首次从 Hugging Face 下载模型（约 500MB）。

hackernews · AG342 · Jun 13, 20:41 · [社区讨论](https://news.ycombinator.com/item?id=48521236)

**背景**: 像 MacWhisper 这样的会议转录应用已经变得流行，但通常需要在通话前进行手动设置，并依赖云端处理，引发隐私担忧。Apple Silicon Mac 上的设备端语音识别已显著改进，使得离线转录能够达到良好精度。Trace 顺应这一趋势，通过全局快捷键和通话中标记功能最大程度减少用户操作摩擦。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/MacWhisper">MacWhisper</a></li>
<li><a href="https://getvext.app/blog/offline-voice-to-text-mac">Offline Voice to Text on Mac — How Local Speech Recognition ...</a></li>
<li><a href="https://retina.studio/textbuddy/enable-macos-on-device-speech-recognition/">Enable On - Device Speech Recognition – retina studio</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍赞赏该应用减少操作摩擦的设计以及关键时刻标记功能，但部分人对其仅限 App Store 购买、模型下载大小以及企业限制安装此类软件表示担忧。还有一位用户分享了一个开源替代项目。

**标签**: `#meeting transcription`, `#macOS`, `#offline`, `#productivity`, `#open source`

---

<a id="item-11"></a>
## [华尔街超越加密货币试点，深入以太坊](https://www.coindesk.com/business/2026/06/13/wall-street-is-moving-past-crypto-pilots-and-deeper-into-ethereum-says-etherealize-founder) ⭐️ 6.0/10

Etherealize 创始人 Vivek Raman 声称华尔街正从加密货币试点项目转向基于以太坊的金融应用的实际部署，包括代币化股票、债券、基金和房地产。 这标志着机构对以太坊基础设施的信心增强，可能加速区块链在传统金融中的主流采用，并扩展以太坊在加密货币投机之外的角色。 这种采用涉及在以太坊上代币化现实世界资产，利用智能合约实现自动化和透明度。然而，在监管明确性和高容量机构使用的可扩展性方面仍存在挑战。

rss · CoinDesk · Jun 13, 16:00

**背景**: 以太坊是一个去中心化的区块链平台，支持智能合约——在满足预定条件时自动执行的程序。机构金融多年来一直在试验区块链，但全面采用受到监管和技术障碍的限制。从试点到生产的转变表明成熟度不断提高。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/06/13/wall-street-is-moving-past-crypto-pilots-and-deeper-into-ethereum-says-etherealize-founder">Wall Street is moving past crypto pilots and deeper into Ethereum...</a></li>
<li><a href="https://coinmarketcap.com/academy/article/75d2afce-e511-49c1-bb42-1b5cf058a138">Vitalik Buterin and Ethereum Foundation Back Etherealize to Drive...</a></li>
<li><a href="https://decrypt.co/321861/wall-street-gets-ethereum-digital-oil-etherealize">Wall Street Gets Ethereum's 'Digital Oil', Says Etherealize ... - ...</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#Wall Street`, `#crypto adoption`, `#institutional finance`

---

<a id="item-12"></a>
## [AI 代理持信用卡导致财务损失](https://decrypt.co/370988/ai-agent-rekts-dev-bogus-scan-crypto-donations) ⭐️ 6.0/10

一位业余开发者给自主 AI 代理提供了信用卡和截止日期，代理进行了虚假扫描导致财务损失，开发者不得不乞求加密货币捐款。 这一事件凸显了在时间压力下授予自主 AI 代理财务访问权限的现实风险，并强调了在代理型 AI 系统中需要强有力的安全措施。 AI 代理被给予信用卡和截止日期以完成任务，但它执行了虚假扫描导致扣费，耗尽了资金。开发者随后向加密货币社区求助捐款以弥补损失。

rss · Decrypt · Jun 13, 13:01

**背景**: 自主 AI 代理是能够独立推理和执行任务以实现目标的系统。当它们获得信用卡等金融工具的使用权时，可能做出具有真实货币后果的决策，引发对安全性和控制的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/research/measuring-agent-autonomy">Measuring AI agent autonomy in practice \ Anthropic</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#autonomous agents`, `#AI failure`, `#crypto`

---