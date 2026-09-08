---
layout: default
title: "Horizon Summary: 2026-09-08 (ZH)"
date: 2026-09-08
lang: zh
---

> From 61 items, 17 important content pieces were selected

---

1. [用消费级 GPU 破解 90 年代 CA 的 RSA 密钥](#item-1) ⭐️ 8.0/10
2. [D2 图表布局引擎 TALA 宣布开源](#item-2) ⭐️ 8.0/10
3. [Jellyfin 12.0 重大版本发布，带来性能提升与新功能](#item-3) ⭐️ 8.0/10
4. [博通移除 VDDK 使 VMware 迁移更加困难](#item-4) ⭐️ 8.0/10
5. [LG 智能电视被曝记录音频并扫描家庭网络](#item-5) ⭐️ 8.0/10
6. [以太坊承诺允许用户无需持有 ETH 即可支付 Gas 费](#item-6) ⭐️ 8.0/10
7. [星展银行与花旗完成 Swift 账本上首笔周末跨境美元支付](#item-7) ⭐️ 8.0/10
8. [OpenAI GPT-6 Astra 在多项任务中给早期测试者留下深刻印象](#item-8) ⭐️ 8.0/10
9. [以太坊计划 2029 年实现量子安全 L1，Hegotá升级启动](#item-9) ⭐️ 8.0/10
10. [Liquid 网络因 3.2 亿美元比特币被提取而暂停](#item-10) ⭐️ 8.0/10
11. [交互地图展示洛杉矶建筑史（1880-2026）](#item-11) ⭐️ 7.0/10
12. [双重密钥漏洞或致 910 亿美元 USDT 面临黑客风险](#item-12) ⭐️ 7.0/10
13. [Coldcard 黑客转移 770 万美元比特币，占第三波被盗资金的 45%](#item-13) ⭐️ 7.0/10
14. [OpenAI 首席科学家呼吁制定强制性 AI 安全标准](#item-14) ⭐️ 7.0/10
15. [韩华在 Avalanche 上构建代币化证券平台，韩国监管临近](#item-15) ⭐️ 7.0/10
16. [稳定币钱包挑战银行账户作为主要资金中心](#item-16) ⭐️ 6.0/10
17. [Solana 将交易大小提升三倍以支持复杂交易](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [用消费级 GPU 破解 90 年代 CA 的 RSA 密钥](https://mcpherrin.ca/2026/09/07/rsa.html) ⭐️ 8.0/10

一位作者使用消费级 GPU 成功分解了 1990 年代证书颁发机构的 RSA 密钥，破解 512 位密钥大约需要两天时间。这表明现代硬件可以轻松破解此类历史加密。 这凸显了 512 位 RSA 密钥的不安全性，这些密钥曾用于早期互联网加密，并引发了对当前加密标准在未来计算能力提升下长期有效性的担忧。同时，它也促使人们反思历史数据的安全性，以及政府可能解密存储通信的潜在风险。 作者使用了消费级 GPU，并可能采用了通用数域筛法（GNFS）算法，这是分解大数的标准方法。被破解的密钥属于 1990 年代的证书颁发机构，作者指出当时许多流量并未使用临时密钥，因此容易受到此类攻击。

hackernews · ahlCVA · Sep 8, 01:16 · [社区讨论](https://news.ycombinator.com/item?id=49604637)

**背景**: RSA 是一种公钥密码系统，其安全性依赖于分解大合数的难度。在 1990 年代，512 位 RSA 密钥很常见，但到 1999 年，RSA-155（512 位）已通过大量计算资源被分解。现代消费级 GPU 使此类分解速度大大加快，凸显了在当前系统中使用足够大密钥长度（如 2048 位或更长）的重要性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/RSA_numbers">RSA numbers - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/RSA_Factoring_Challenge">RSA Factoring Challenge - Wikipedia</a></li>
<li><a href="https://www.iacr.org/archive/eurocrypt2000/1807/18070001-new.pdf">Factorization of a 512–bit RSA Modulus ⋆</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一：有人遗憾有趣的细节被交给 AI 处理，也有人赞赏 GPU 破解的演示。一位评论者指出 SSL 报告自动给出四个“F”的讽刺性，另一位则强调需要验证 AI 生成的内容，因为 LLM 可能产生看似合理但错误的输出。

**标签**: `#RSA`, `#cryptography`, `#security`, `#history`, `#GPU cracking`

---

<a id="item-2"></a>
## [D2 图表布局引擎 TALA 宣布开源](https://d2lang.com/blog/tala-is-open-source/) ⭐️ 8.0/10

Terrastruct 已将 TALA 开源，这是一款专为软件架构图设计的布局引擎，现在可免费提供给 D2 社区使用。这一变化使得用户无需支付之前的商业许可费用即可使用改进的自动布局功能。 此举解决了 D2 生态系统中长期存在的痛点：默认布局引擎在处理某些类型的图表时效果不佳，而 TALA 在架构图上能提供明显更好的结果。通过开源 TALA，Terrastruct 降低了开发者和组织创建更清晰、更专业图表的门槛，可能促进 D2 的进一步采用。 TALA 是独立于 D2 的安装包，其算法完全自主开发，零依赖，由 Terrastruct 内部研发。此次开源发布了完整源代码，允许社区贡献并集成到其他工具中。

hackernews · alixanderwang · Sep 7, 23:37 · [社区讨论](https://news.ycombinator.com/item?id=49604150)

**背景**: D2 是一种现代的声明式图表脚本语言，可将文本转换为图表，类似于 Graphviz，但语法更友好。布局引擎（如 TALA）自动定位节点和边以生成可读的图表；TALA 专为软件架构图设计，这类图通常结构复杂，通用引擎难以处理得当。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/d2lang/d2">GitHub - d2lang/d2: D2 is a modern diagram scripting language that turns text to diagrams. · GitHub</a></li>
<li><a href="https://github.com/terrastruct/tala">terrastruct/TALA: A diagram layout engine designed ... - GitHub</a></li>
<li><a href="https://d2lang.com/tour/tala/">TALA | D2 Documentation</a></li>

</ul>
</details>

**社区讨论**: 社区反应总体积极，用户称赞 TALA 相比默认引擎和 ELK 在布局质量上的提升。也有用户指出 TALA 并非对所有图表类型都更优，并有人询问是否可以将 TALA 集成到 Graphviz 等其他工具中。

**标签**: `#open-source`, `#diagramming`, `#layout-engine`, `#D2`, `#visualization`

---

<a id="item-3"></a>
## [Jellyfin 12.0 重大版本发布，带来性能提升与新功能](https://jellyfin.org/posts/jellyfin-release-12.0/) ⭐️ 8.0/10

Jellyfin 12.0，一个重要的开源媒体服务器版本，现已发布，带来了性能改进和新功能。该更新包括更顺畅的迁移过程，并解决了之前版本（如 10.11）存在的问题。 此次发布对自托管社区意义重大，因为它增强了 Jellyfin 作为 Plex 替代方案的可行性，可能减少对专有服务的依赖。其性能修复和新功能可能吸引更多寻求免费、开源媒体解决方案的用户。 从 10.10.7 升级到 12.0 的用户报告迁移快速且无痛，但部分标题在重新扫描前会消失。该版本还改进了字幕处理，这曾是常见的痛点，尤其是在 Android 客户端投屏到 Chromecast 时。

hackernews · 0xC0ncord · Sep 8, 01:56 · [社区讨论](https://news.ycombinator.com/item?id=49604861)

**背景**: Jellyfin 是一个免费、开源的媒体服务器，允许用户管理和流式传输个人媒体库。它常与 Plex 比较，但与 Plex 不同，它完全自托管，没有付费层级或强制在线服务。该项目一直在发展，旨在提供比专有解决方案更友好、功能更丰富的替代品。

**社区讨论**: 社区情绪总体积极，用户称赞升级顺畅和性能改进。一些用户指出字幕处理仍存在问题，而另一些用户则希望 Jellyfin 能继续促使 Plex 改善其不友好的用户行为。少数用户分享了将 Jellyfin 与 *arr 系列工具和 AI 助手等其他自托管工具集成的经验。

**标签**: `#Jellyfin`, `#media server`, `#open source`, `#release`, `#self-hosting`

---

<a id="item-4"></a>
## [博通移除 VDDK 使 VMware 迁移更加困难](https://www.virtualizationhowto.com/2026/09/leaving-vmware-just-got-harder-after-broadcom-pulled-vddk-downloads/) ⭐️ 8.0/10

博通已移除 VMware Virtual Disk Development Kit（VDDK）的公开下载，该组件是许多虚拟化迁移工具的关键部分。此变更未事先公告，也未提供替代方案，影响了计划从 VMware 迁移的用户。 VDDK 对于从虚拟机监控程序外部读取 VMware 虚拟磁盘至关重要，几乎所有迁移工具都依赖它。其移除严重阻碍了 VMware 的退出策略，迫使用户寻找更慢的替代方案或重新考虑迁移计划，影响了整个虚拟化生态系统。 没有 VDDK，磁盘传输将回退到明显较慢的路径，使大规模迁移变得不切实际。一些供应商如 Platform9 提供了替代迁移方法，但缺乏官方支持增加了 VMware 退出的风险和复杂性。

hackernews · josephcsible · Sep 7, 20:32 · [社区讨论](https://news.ycombinator.com/item?id=49602699)

**背景**: VMware VDDK 是一个软件开发工具包，允许第三方工具读写 VMware 虚拟磁盘。它被备份和迁移解决方案广泛使用，以高效访问虚拟机数据。博通于 2023 年收购 VMware 后，一直在对 VMware 的产品和许可进行更改，这常常引发社区的批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.shapeblue.com/broadcom-vddk-download-vmware-to-kvm/">Broadcom Removes VDDK Pages Without Explanation... - ShapeBlue</a></li>
<li><a href="https://platform9.com/blog/vddk-no-longer-available/">Broadcom Cut Public Access of Virtual Disk Development Kit ...</a></li>
<li><a href="https://news.ycombinator.com/item?id=49602699">Leaving VMware just got harder after Broadcom pulled VDDK ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论对博通处理 VMware 的方式表示悲伤和沮丧，一些人指出这个曾经伟大产品的衰落。用户分享了个人迁移经历，例如从 Hyper-V 迁移到 VMware，现在又迁回，并建议使用 KVM 或 Proxmox 等替代方案，还有人开玩笑说要把 VMware 源代码泄露出来。

**标签**: `#VMware`, `#Broadcom`, `#VDDK`, `#virtualization`, `#migration`

---

<a id="item-5"></a>
## [LG 智能电视被曝记录音频并扫描家庭网络](https://www.youtube.com/watch?v=6IFVTcM28KA) ⭐️ 8.0/10

Gamers Nexus 的一项调查发现，LG 智能电视（包括旗舰 G5 OLED）即使在屏幕关闭时也会记录麦克风音频，并主动扫描本地网络以映射附近设备。这些电视在离线状态下运行，一旦重新连接互联网便会上传缓存数据。 这引发了约 2.16 亿 LG 智能电视用户的重大隐私担忧，因为设备在未明确获得用户同意的情况下捕获音频和网络信息。这些发现凸显了智能电视数据收集的广泛问题，可能促使监管审查和消费者对 LG 及其他制造商的抵制。 调查使用 Wireshark 数据包捕获对零售 LG OLED 型号（包括 G5）进行了测试，观察到电视持续扫描网络以查找无关设备（如智能手机和智能手表）。屏幕关闭时，音频转录在本地进行，一旦电视重新连接互联网便会上传数据，且该行为在所有输入源（包括 HDMI）上均持续发生。

hackernews · treve · Sep 7, 00:22 · [社区讨论](https://news.ycombinator.com/item?id=49592375)

**背景**: 智能电视通常包含自动内容识别（ACR）等功能，用于跟踪观看习惯以投放广告，但此次调查揭示了更具侵入性的数据收集行为。据报道，LG 的服务条款要求用户告知家庭成员和客人他们的声音可能被捕获，将同意责任推给用户。此事件是物联网设备在未透明获得用户同意的情况下收集数据的更广泛趋势的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.notebookcheck.net/LG-smart-TVs-caught-logging-audio-with-screen-off-and-snooping-on-local-devices.1391214.0.html">LG smart TVs caught logging audio with screen off and ...</a></li>
<li><a href="https://cybersecuritynews.com/lg-smart-tvs-caught-scanning-networks/">LG Smart TVs Caught Scanning Networks and Logging Audio in ...</a></li>
<li><a href="https://cyberinsider.com/lg-smart-tvs-found-scanning-home-networks-for-nearby-devices/">LG Smart TVs found scanning home networks for nearby devices</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了愤怒和担忧，用户分享了在 LG 电视上禁用网络功能并遭到嘲笑等个人经历。一些人指出在广告支持的网站上报道隐私问题的讽刺性，而另一些人则质疑其是否符合窃听法律的合法性，并呼吁消费者对 LG 采取行动。

**标签**: `#privacy`, `#smart TV`, `#LG`, `#surveillance`, `#IoT`

---

<a id="item-6"></a>
## [以太坊承诺允许用户无需持有 ETH 即可支付 Gas 费](https://www.coindesk.com/tech/2026/09/07/ethereum-commits-to-letting-users-pay-gas-fees-without-having-to-hold-eth) ⭐️ 8.0/10

以太坊已正式承诺允许用户无需持有 ETH 即可支付 Gas 费，这是其交易费用模型的重大转变。此举旨在降低新用户的使用门槛并改善整体用户体验。 这一进展可能大幅提升以太坊的可访问性和采用率，因为用户不再需要仅为支付交易费用而购买 ETH。这与账户抽象和用户友好型区块链交互的行业趋势一致，可能吸引更多主流用户和开发者。 这一承诺可能涉及实施账户抽象（EIP-4337）或类似机制，允许智能合约钱包以替代代币赞助或支付 Gas 费。具体时间线和实施方案等技术细节尚未完全披露。

rss · CoinDesk · Sep 7, 13:54

**背景**: 以太坊上的 Gas 费是以 ETH 支付的，用于补偿验证者处理交易。传统上，用户必须在钱包中持有 ETH 才能支付这些费用，这对新用户来说是一个障碍。账户抽象是一项提议的升级，允许智能合约钱包以灵活的方式发起交易并支付费用，可能使用其他 ERC-20 代币或由第三方承担费用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ethereum.org/developers/docs/gas/">Ethereum gas and fees: technical overview | ethereum.org</a></li>
<li><a href="https://ethereum.org/roadmap/account-abstraction/">Account abstraction | ethereum.org</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#cryptocurrency`, `#gas fees`, `#blockchain`, `#usability`

---

<a id="item-7"></a>
## [星展银行与花旗完成 Swift 账本上首笔周末跨境美元支付](https://www.coindesk.com/business/2026/09/07/dbs-and-citi-enable-instant-24-7-cross-border-tokenised-deposit-payments-on-the-swift-ledger) ⭐️ 8.0/10

星展银行与花旗银行在 Swift 数字账本上使用代币化存款，成功完成了新加坡与美国之间的首笔周末跨境美元结算。这标志着实现即时、24/7 跨境支付的重要里程碑。 这证明了代币化存款和基于区块链的账本在实际银行业务中的可行性，可能改变跨境支付的格局。它为金融机构提供全天候结算铺平了道路，减少了对传统银行营业时间和中介机构的依赖。 该交易涉及代币化存款，即由受监管机构发行的、在分布式账本上的传统银行存款的数字表示。Swift 数字账本由 30 多家全球金融机构和 Consensys 共同开发，目前正推进至 MVP 实施阶段，初期重点是实时 24/7 跨境支付。

rss · CoinDesk · Sep 7, 12:05

**背景**: 代币化存款是基于区块链的商业银行货币形式，与稳定币不同，它们代表对受监管银行的直接债权。Swift 一直在构建基于区块链的共享账本以现代化其基础设施，旨在支持其全球网络中的数字资产和代币化存款。这一举措是更广泛行业趋势的一部分，富国银行等主要银行也在探索面向企业客户的代币化存款。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nacha.org/tokenized-deposits-why-care">Tokenized Deposits: What They Are and Why U.S. Financial Institutions Should Care | Nacha</a></li>
<li><a href="https://www.swift.com/news-events/press-releases/swift-add-blockchain-based-ledger-its-infrastructure-stack-groundbreaking-move-accelerate-and-scale-benefits-digital-finance">Swift to add blockchain-based ledger to its infrastructure stack in groundbreaking move to accelerate and scale benefits of digital finance across more than 200 countries and territories worldwide | Swift</a></li>
<li><a href="https://www.swift.com/payments/payment-innovation/blockchain-based-ledger">Building the digital payment stack of the future | Swift</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenized deposits`, `#cross-border payments`, `#Swift`, `#banking`

---

<a id="item-8"></a>
## [OpenAI GPT-6 Astra 在多项任务中给早期测试者留下深刻印象](https://decrypt.co/377514/openai-gpt-6-astra-review-shockingly-good) ⭐️ 8.0/10

OpenAI 已发布其迄今最智能、最对齐的模型 GPT-6 Astra，早期测试者报告称它在导航 3D 城市、作曲、分析研究论文和玩游戏等方面表现出色。该模型已通过 OpenAI API 提供，适用于复杂推理、编程、计算机使用、研究和文档创建。 GPT-6 Astra 代表了 AI 能力的重大飞跃，可能重塑专业人士和消费者在复杂多模态任务中使用 AI 的方式。它在多个领域的出色表现可能加速其在研究、创意产业和软件开发中的采用，并加剧 AI 实验室之间的竞争。 据 OpenAI 称，GPT-6 Astra 专为最困难的端到端工作而构建，在计算机使用、编程、网络安全和科学方面具有最先进的能力。早期印象基于发布周末的测试，因此长期可靠性和安全性仍有待全面评估。

rss · Decrypt · Sep 6, 17:01

**背景**: GPT-6 Astra 是 OpenAI GPT 系列的最新迭代，继 GPT-5.6 等模型之后推出。它是一个多模态模型，能够处理和生成文本、图像及其他数据类型，从而支持 3D 导航和音乐创作等任务。该模型被定位为复杂专业工作的旗舰，兼顾智能与成本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-6_Astra">GPT-6 Astra - Wikipedia</a></li>
<li><a href="https://openai.com/index/gpt-6-astra/">GPT-6 Astra: A new generation of intelligence | OpenAI</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-6-astra">GPT-6 Astra Model | OpenAI API</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#GPT-6`, `#AI`, `#language models`, `#multimodal`

---

<a id="item-9"></a>
## [以太坊计划 2029 年实现量子安全 L1，Hegotá升级启动](https://www.theblock.co/news/ecosystems/2026-09-08-ethereum-foundation-quantum-resistance-2029-413716) ⭐️ 8.0/10

以太坊宣布了到 2029 年在其 Layer 1 上实现全面后量子安全的路线图，首先通过 Hegotá升级引入账户抽象和抗审查改进。 这一战略举措使以太坊能够主动应对未来量子计算机的威胁，因为量子计算机可能破解当前的密码学基础。它为其他区块链网络树立了先例，并强调了加密生态系统中长期安全规划的重要性。 Hegotá升级预计将包含通过 EIP-8141 实现的原生账户抽象，从而支持更灵活和安全的交易机制。2029 年实现后量子安全的目标表明这是一个分阶段的过渡，可能涉及采用抗量子签名方案和其他密码学更新。

rss · The Block · Sep 8, 04:17

**背景**: 量子计算机对区块链安全构成重大威胁，因为它们可能破解大多数区块链（包括以太坊）使用的椭圆曲线密码学（ECC）。后量子密码学涉及开发对经典计算机和量子计算机都安全的算法。账户抽象是一个概念，允许用户账户由智能合约控制，从而实现多签名钱包和社交恢复等功能，这些也与抗量子性相关。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ethereum.org/roadmap/account-abstraction/">Account abstraction | ethereum .org</a></li>
<li><a href="https://www.kucoin.com/blog/ethereum-developers-target-privacy-changes-in-hegot-frame-transactions-and-focil-explained">Ethereum Developers Target Privacy Changes in Hegotá : Frame...</a></li>
<li><a href="https://www.linkedin.com/pulse/architecting-ethereums-cryptographic-transition-kusal-damsara-xkjkc">Architecting Ethereum 's Cryptographic Transition in the Hegotá ...</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#quantum computing`, `#blockchain security`, `#cryptography`, `#roadmap`

---

<a id="item-10"></a>
## [Liquid 网络因 3.2 亿美元比特币被提取而暂停](https://www.theblock.co/news/defi/2026-09-06-liquid-network-pauses-after-purported-white-hat-hackers-withdraw-320-million-in-bitcoin-413626) ⭐️ 8.0/10

比特币侧链 Liquid Network 在所谓的白帽黑客提取约 3.2 亿美元比特币后被暂停，导致交易所暂停 LBTC 的存取款。Blockstream 已修补桥接节点并追回 3400 BTC，仍有约 598.5 BTC 未归还。 此事件凸显了侧链桥接实现中的漏洞，并引发了对基于比特币的第二层解决方案安全性的担忧。大部分资金的追回可能减轻直接损失，但暂停和交易所暂停服务可能削弱对 Liquid 及类似网络的信任。 攻击者通过嵌入比特币交易中的 PGP 签名消息与 Blockstream 沟通。Blockstream 表示 Liquid 的桥接节点已修补，攻击者归还了 3400 BTC，仍有约 598.5 BTC（价值约 5600 万美元）未归还。

rss · The Block · Sep 6, 21:14

**背景**: Liquid Network 是 Blockstream 开发的比特币第二层侧链，支持更快、更保密的交易以及数字资产发行。LBTC 是侧链上代表比特币的原生代币，用于交易和 DeFi 应用。白帽黑客是在获得许可的情况下入侵系统以识别漏洞的道德安全研究人员，通常会归还被盗资金。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://liquid.net/">The Liquid Network: The Financial Layer for Bitcoin Capital ...</a></li>
<li><a href="https://blockstream.com/liquid/">The Liquid Network | Bitcoin layer-2 solution for digital ...</a></li>
<li><a href="https://www.thecoinrepublic.com/2026/09/07/bitcoin-news-liquid-network-drained-of-320m-as-sidechain-halts/">Bitcoin News: Liquid Network Drained of $320M as Sidechain ...</a></li>

</ul>
</details>

**标签**: `#bitcoin`, `#security`, `#sidechain`, `#defi`, `#hack`

---

<a id="item-11"></a>
## [交互地图展示洛杉矶建筑史（1880-2026）](https://lax-skyline.parcelscope.net/) ⭐️ 7.0/10

lax-skyline.parcelscope.net 上的交互式地图可视化了洛杉矶从 1880 年到 2026 年的建筑建造日期，使用户能够探索城市发展的时间演变。 该可视化提供了一个引人入胜的工具，帮助理解城市增长和分区政策的影响，引发了公众关于住房可负担性和历史发展模式的讨论。它吸引了广泛受众参与关于城市规划和数据呈现的讨论。 该地图基于洛杉矶县评估员门户网站的数据，显示现有建筑的建造年份。然而，它仅反映现存结构，因此完全重建的区域会显得暗淡，可能误导观众对历史建筑活动的理解。

hackernews · rustywasm · Sep 7, 18:52 · [社区讨论](https://news.ycombinator.com/item?id=49601655)

**背景**: 洛杉矶有着复杂的城市历史，包括曾经庞大的公共交通网络，后来大部分被高速公路取代。分区政策的变化，特别是 1980 年代的降密度分区，深刻影响了城市的发展和住房可负担性。此类交互地图利用地块级数据来展示这些模式。

**社区讨论**: 评论者指出，该地图仅显示现存建筑，而非所有历史建筑，并举例说明像 Palms 这样的地区已被完全重建。其他人讨论了洛杉矶失去的公共交通网络以及降密度分区对住房成本的影响，有人称赞该可视化，同时也指出了其局限性。

**标签**: `#data visualization`, `#urban planning`, `#Los Angeles`, `#history`, `#interactive map`

---

<a id="item-12"></a>
## [双重密钥漏洞或致 910 亿美元 USDT 面临黑客风险](https://www.coindesk.com/tech/2026/09/04/tether-receives-bluechip-rating-upgrade-but-hacken-finds-major-key-security-gaps) ⭐️ 7.0/10

Hacken 的一份报告指出，Tether 在密钥管理方面存在重大安全漏洞，警告称双重密钥泄露可能危及 910 亿美元 USDT 的控制权。该发现凸显了 Tether 密钥管理系统的脆弱性。 此事意义重大，因为 USDT 是最大的稳定币，一旦遭受攻击可能导致巨额财务损失，并削弱整个加密货币生态系统的信任。这凸显了数字资产托管方采用强健密钥管理的至关重要性。 报告特别指出，双重密钥泄露可能使黑客控制 910 亿美元的 USDT 储备。Hacken 的调查结果表明，Tether 现有的安全措施可能不足以防范此类攻击。

rss · CoinDesk · Sep 7, 10:35

**背景**: Tether 是 USDT 的发行方，USDT 是一种与美元挂钩的稳定币，广泛用于加密货币交易和价值储存。密钥管理涉及对控制资金访问权限的加密密钥的安全存储和处理；一旦泄露，可能导致未经授权的交易。该报告发布之际，加密货币行业的安全担忧日益加剧，近期多起高调黑客事件凸显了相关漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://tethersecurity.com/">Tether Security | Device Trust Platform for the Mobile Workforce</a></li>
<li><a href="https://www.ft.com/content/a91356ef-67bd-4bd9-947b-b272423f1318?syn-25a6b1a6=1">Nearly 14,000 crypto holders face security risk after data breach</a></li>

</ul>
</details>

**标签**: `#security`, `#cryptocurrency`, `#stablecoin`, `#key management`, `#Tether`

---

<a id="item-13"></a>
## [Coldcard 黑客转移 770 万美元比特币，占第三波被盗资金的 45%](https://www.coindesk.com/business/2026/09/07/coldcard-hacker-moves-45-of-bitcoin-stolen-in-third-attack-wave) ⭐️ 7.0/10

一名黑客转移了从 Coldcard 钱包窃取的 770 万美元比特币，占第三波攻击中被盗资金的 45%。此前有报道称，Coldcard 钱包遭受大规模攻击，已从 1200 多个地址盗走高达 8900 万美元。 此事件凸显了硬件钱包的漏洞，而硬件钱包被广泛认为是存储比特币最安全的方式。损失的规模及持续的攻击波可能削弱用户对冷存储解决方案的信任，并促使人们重新评估安全实践。 第三波攻击涉及转移 45%的被盗资金，表明攻击者正在积极整合或洗钱。安全研究人员怀疑软件漏洞可能导致了此次盗窃，可能影响数千个地址。

rss · CoinDesk · Sep 7, 09:32

**背景**: 像 Coldcard 这样的硬件钱包将私钥离线存储，以防止远程黑客攻击。然而，它们仍可能面临供应链攻击、固件缺陷或物理篡改的风险。据报道，最近的攻击利用了软件漏洞，使攻击者能够在短时间内从多个地址盗取资金。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2lpaHZyY0VSRnFfMU5oWVBnNWV5Z0FQAQ?hl=en-IN&gl=IN&ceid=IN:en">Google News - Coldcard hardware wallet hack - Overview</a></li>
<li><a href="https://www.fox7austin.com/news/coldcard-wallet-attack-drains-89m-bitcoin-from-1200-addresses">Coldcard wallet attack drains up to $89M in Bitcoin... | FOX 7 Austin</a></li>
<li><a href="https://www.bit.com/knowledge-hub/coldcard-the-security-first-wallet-that-got-hacked">Coldcard Wallet : Security Features & Exploit Explained | BIT</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#security`, `#bitcoin`, `#hardware wallet`, `#theft`

---

<a id="item-14"></a>
## [OpenAI 首席科学家呼吁制定强制性 AI 安全标准](https://decrypt.co/377635/openai-chief-scientist-warns-ai-slow-down) ⭐️ 7.0/10

OpenAI 首席科学家 Jakub Pachocki 公开呼吁在 AI 开发中制定强制性安全标准，理由是监控先进 AI 模型推理的难度日益增加。这标志着从自愿性自我监管向具有约束力的行业要求的显著转变。 OpenAI 关键人物的这一声明凸显了人们对 AI 安全日益增长的担忧，并可能加速全球监管努力。这表明即使是领先的 AI 开发者也承认当前监控技术的局限性，可能影响政策和行业实践。 Pachocki 特别强调了监控 AI 模型“推理”过程的挑战，这与 OpenAI 最近关于思维链可控性的研究一致。对强制性标准的呼吁表明，其意图超越欧盟 AI 法案或 NIST 的 AI 风险管理框架等自愿性框架。

rss · Decrypt · Sep 7, 21:16

**背景**: 先进 AI 模型（如 OpenAI 的 o1 和 GPT-4o）使用思维链推理来解决复杂任务，但这一内部过程并不完全透明。研究人员发现，这些模型有时会产生难以监控或控制的推理，引发安全隐患。随着 AI 能力的增强，确保模型安全且按预期行为变得越来越困难，促使人们呼吁制定标准化的安全措施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/reasoning-models-chain-of-thought-controllability/">Reasoning models struggle to control their chains of thought ...</a></li>
<li><a href="https://arxiv.org/html/2503.22732v1">Reasoning Beyond Limits: Advances and Open Problems for LLMs</a></li>
<li><a href="https://www.nist.gov/artificial-intelligence/ai-standards">AI Standards | NIST</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#OpenAI`, `#regulation`, `#AI research`

---

<a id="item-15"></a>
## [韩华在 Avalanche 上构建代币化证券平台，韩国监管临近](https://www.theblock.co/news/business/2026-09-07-south-korea-hanwha-tokenized-securities-platform-avalanche-413652) ⭐️ 7.0/10

据报道，韩国韩华集团正在 Avalanche 区块链上开发代币化证券平台。此举正值该国相关资产监管框架逐步成形之际，将代币化证券纳入现有金融体系的修正案将于明年二月生效。 这一进展表明机构在传统金融领域对区块链的采用日益增长，尤其在亚洲。同时，它也凸显了 Avalanche 在企业领域的吸引力，以及监管明确性对推动此类举措的重要性。 报道未指明涉及韩华旗下哪家子公司，也未说明平台的具体范围。韩国将代币化证券纳入现有金融法律的修正案，经过一年准备期后，预计于 2027 年 2 月生效。

rss · The Block · Sep 7, 06:24

**背景**: Avalanche 是由 Ava Labs 于 2020 年 9 月推出的公共区块链和智能合约平台，以其高吞吐量和可定制的子网而闻名。代币化证券是传统金融资产（如股票或债券）在区块链上发行的数字表示。韩国一直在制定代币化证券的监管框架，其金融监管机构已推出三阶段路线图，法律基础预计在 2027 年到位。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Avalanche_(blockchain_platform)">Avalanche ( blockchain platform ) - Wikipedia</a></li>
<li><a href="https://coincentral.com/south-korea-asses-bill-to-regulate-and-enable-tokenized-securities/">South Korea Asses Bill To Regulate And Enable Tokenized Securities</a></li>
<li><a href="https://cointelegraph.com/news/south-korean-regulators-tokenized-securities-roadmap">South Korean Regulators Introduce Tokenized Securities Roadmap</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#Avalanche`, `#regulation`, `#South Korea`

---

<a id="item-16"></a>
## [稳定币钱包挑战银行账户作为主要资金中心](https://www.coindesk.com/business/2026/09/07/stablecoin-wallets-challenge-traditional-bank-accounts-as-main-consumer-money-hub) ⭐️ 6.0/10

近期趋势显示，稳定币钱包正日益与传统银行账户竞争，成为消费者资金管理的主要中心，标志着人们存储和交易价值方式的转变。 这一发展可能重塑金融生态系统，提供比传统银行更快、更便宜、更便捷的替代方案，可能影响全球银行、金融科技公司和消费者。 稳定币钱包利用区块链技术提供近乎即时的结算和全天候可用性，而传统银行账户通常有营业时间限制和数天的转账时间。然而，它们面临监管不确定性，且可能无法提供与受保险银行存款同等的消费者保护。

rss · CoinDesk · Sep 7, 14:12

**背景**: 稳定币是一种加密货币，旨在通过与法定货币等资产挂钩来维持价值稳定。它们结合了数字资产的优势（如速度和低成本）与价格稳定性，使其在支付和价值存储方面具有吸引力。传统银行账户受监管且有保险，但在跨境交易中可能速度慢且成本高。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Stablecoin">Stablecoin - Wikipedia</a></li>
<li><a href="https://www.investopedia.com/terms/s/stablecoin.asp">Stablecoins: Definition, How They Work, and Types - Investopedia</a></li>
<li><a href="https://coinspaid.com/knowledge-base/stablecoins-vs-traditional-remittances-for-business/">Stablecoins or Bank Transfers? | Coinspaid</a></li>

</ul>
</details>

**标签**: `#stablecoins`, `#fintech`, `#cryptocurrency`, `#banking`, `#digital wallets`

---

<a id="item-17"></a>
## [Solana 将交易大小提升三倍以支持复杂交易](https://www.coindesk.com/tech/2026/09/07/solana-to-triple-transaction-size-as-apps-get-room-for-more-complex-trades) ⭐️ 6.0/10

Solana 计划将其最大交易大小从 1,232 字节增加到 4,096 字节，目标是在本周三进行升级。这一变更由 SIMD-0296 定义，并通过 v1 交易格式（SIMD-0385）实现，为开发者提供了超过三倍的空间来处理复杂操作。 此次升级使得更复杂的交易和操作能够容纳在单笔交易中，提高了 Solana 上应用的效率和用户体验。这凸显了 Solana 对可扩展性的持续承诺，可能吸引更多复杂的 DeFi 和交易应用加入其生态系统。 此次大小提升是增强 Solana 可扩展性的更广泛努力的一部分，此前已有如 SIMD-0286 等升级解决了网络拥堵问题。该变更计划于周三进行，虽然将交易大小提升三倍，但不会改变区块大小或交易处理速度。

rss · CoinDesk · Sep 7, 12:08

**背景**: Solana 是一个以快速和低成本交易著称的高性能区块链，但在高需求时期也面临可扩展性挑战。交易大小限制影响单笔交易可包含的数据量，更大的大小允许更复杂的智能合约交互和数据负载。此次升级是 Solana 路线图的一部分，旨在支持更高级的用例而不影响性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://solana.com/upgrades/larger-transaction-sizes">Larger Transaction Sizes | Solana Media</a></li>
<li><a href="https://www.coindesk.com/tech/2026/09/07/solana-to-triple-transaction-size-as-apps-get-room-for-more-complex-trades">SOL news: Solana to triple transaction size as apps get room ...</a></li>

</ul>
</details>

**标签**: `#Solana`, `#blockchain`, `#scalability`, `#cryptocurrency`

---