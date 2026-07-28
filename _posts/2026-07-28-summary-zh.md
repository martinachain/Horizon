---
layout: default
title: "Horizon Summary: 2026-07-28 (ZH)"
date: 2026-07-28
lang: zh
---

> From 67 items, 18 important content pieces were selected

---

1. [Anthropic 阐明对开放权重模型的立场](#item-1) ⭐️ 8.0/10
2. [Python-build-standalone 驱动现代 Python 工具链](#item-2) ⭐️ 8.0/10
3. [Claude 聊天分享漏洞导致私密对话被谷歌公开](#item-3) ⭐️ 8.0/10
4. [男子因胁迫密码在边境擦除手机面临联邦指控](#item-4) ⭐️ 8.0/10
5. [Opus 5 在 SlopCodeBench 上的基准测试](#item-5) ⭐️ 7.0/10
6. [Lido 转移 165 亿美元质押 ETH 以减少验证者数量](#item-6) ⭐️ 7.0/10
7. [英伟达组建 37 家 AI 安全联盟，排除主要 AI 公司](#item-7) ⭐️ 7.0/10
8. [Circle 从 IBM 收购近 1000 项区块链专利](#item-8) ⭐️ 7.0/10
9. [专家警告：加密货币首当其冲面临量子威胁](#item-9) ⭐️ 7.0/10
10. [SparkKitty 恶意软件藏身应用商店窃取加密货币种子短语](#item-10) ⭐️ 7.0/10
11. [微软声称 MDASH 在网络安全测试中击败 Claude Mythos 和 GPT-5.6 Sol](#item-11) ⭐️ 7.0/10
12. [Mira Murati 的 Inkling AI 模型：西方最佳开放权重模型](#item-12) ⭐️ 7.0/10
13. [宇航员报告任务后持续存在“旁观者”感](#item-13) ⭐️ 6.0/10
14. [Kalshi 和 Polymarket 赢得明尼苏达州预测市场禁令暂停](#item-14) ⭐️ 6.0/10
15. [泰国 SEC 指控 Bitkub 隐瞒 5000 万美元黑客攻击](#item-15) ⭐️ 6.0/10
16. [Securitize 获得 SEC 顾问牌照，推动代币化发展](#item-16) ⭐️ 6.0/10
17. [Fanatics 收购 CFTC 注册交易所进军预测市场](#item-17) ⭐️ 6.0/10
18. [KB 国民银行将在摩根大通 Kinexys 上推出跨境支付](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Anthropic 阐明对开放权重模型的立场](https://www.anthropic.com/news/position-open-weights-models) ⭐️ 8.0/10

Anthropic 发布官方声明，阐明其对开放权重 AI 模型的立场，主张强制安全测试和出口管制，而非全面禁止。 这一立场影响全球 AI 政策辩论，因为 Anthropic 是领先的 AI 公司；其主张监管而非禁止可能影响各国政府对待开放权重模型的方式。 Anthropic CEO Dario Amodei 支持三项措施：禁止向中国出售芯片、打击走私、以及要求对所有有能力的模型进行安全测试。该公司否认主张禁止开放权重模型。

hackernews · surprisetalk · Jul 27, 22:03 · [社区讨论](https://news.ycombinator.com/item?id=49076057)

**背景**: 开放权重模型是指其训练参数（权重）公开发布的 AI 模型，允许任何人下载和使用。与完全开源模型不同，开放权重模型可能不包含训练代码或数据。争论焦点在于平衡创新与安全，担忧强大的开放权重模型可能被滥用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://opensource.org/ai/open-weights">Open Weights: not quite what you’ve been told</a></li>
<li><a href="https://www.stork.ai/blog/anthropics-trillion-dollar-warning">Anthropic CEO Dario Amodei Demands Stronger AI Regulation</a></li>

</ul>
</details>

**社区讨论**: 社区评论高度批评，指责 Anthropic 虚伪且出于自身利益。评论者认为强制安全测试通过设置高昂门槛实际上禁止了开放权重模型，并指出 Anthropic 在对待中国和出口管制立场上的不一致。

**标签**: `#AI policy`, `#open-weights`, `#Anthropic`, `#regulation`, `#geopolitics`

---

<a id="item-2"></a>
## [Python-build-standalone 驱动现代 Python 工具链](https://gregoryszorc.com/docs/python-build-standalone/main/) ⭐️ 8.0/10

Python-build-standalone 提供自包含、高度可移植的 Python 发行版，现由 Astral（uv 背后的公司）维护，并被 uv、pipx、Hatch 和 Poetry 等主要工具用于安装和打包 Python。 这些发行版简化了开发者和工具作者的 Python 分发工作，实现了无需系统依赖的可靠跨平台 Python 安装，这对现代 Python 工作流和应用打包至关重要。 这些发行版最小化运行时依赖，并设计为可再分发。Astral 接管了维护工作，姊妹项目 PyOxy 可通过 Rust 集成生成功能增强的单文件可执行程序。

hackernews · jcbhmr · Jul 27, 18:43 · [社区讨论](https://news.ycombinator.com/item?id=49073942)

**背景**: 传统上，Python 需要系统级安装并依赖特定系统库，导致难以打包或在不同平台上运行。Python-build-standalone 通过生成包含解释器和标准库的自包含构建来解决此问题，仅需 POSIX 兼容系统即可运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gregoryszorc.com/docs/python-build-standalone/main/">Python Standalone Builds — python-build-standalone documentation</a></li>
<li><a href="https://github.com/astral-sh/python-build-standalone">GitHub - astral-sh/python-build-standalone: Produce ...</a></li>
<li><a href="https://grokipedia.com/page/python-build-standalone">python-build-standalone</a></li>

</ul>
</details>

**社区讨论**: charliermarsh（uv 创建者）和 simonw 等开发者称赞了这些发行版，指出它们在 uv 及其他工具中的应用。评论者还提到了相关项目如 Cosmopolitan（跨平台二进制文件）和 PyOxy（单文件可执行程序），突显了生态系统的广度。

**标签**: `#python`, `#tooling`, `#portability`, `#distribution`, `#infrastructure`

---

<a id="item-3"></a>
## [Claude 聊天分享漏洞导致私密对话被谷歌公开](https://decrypt.co/374412/anthropic-share-button-quietly-publishing-claude-chats-google) ⭐️ 8.0/10

Anthropic 的 Claude 聊天分享功能中的一个漏洞导致通过链接分享的私密对话在谷歌上可被公开搜索，超过 11,000 条消息被抓取并发布在 GitHub 上。 这一隐私漏洞暴露了广泛使用的 AI 助手中的敏感用户数据，可能包括个人信息、工作文档和机密数据，削弱了对 AI 聊天服务的信任。 该漏洞由一行缺失的代码导致，使得“通过链接分享”等同于“任何人可搜索”；一名研究人员在 Anthropic 修复问题前已将 11,241 条消息保存到 GitHub。

rss · Decrypt · Jul 27, 18:24

**背景**: Claude 是 Anthropic 开发的流行 AI 聊天机器人，与 ChatGPT 和 Gemini 竞争。分享功能允许用户创建对话的公开链接，但一个漏洞使这些链接可被搜索引擎索引，从而暴露了私密对话。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bbc.com/news/articles/cly5qgjk5ywo">Some people's chats with Claude AI found publicly available online</a></li>
<li><a href="https://startupfortune.com/claude-shared-chats-have-been-indexed-by-google-and-anyone-with-a-search-bar-can-find-them/">Claude shared chats have been indexed by Google and anyone ...</a></li>

</ul>
</details>

**社区讨论**: 社区对隐私泄露表示愤怒和担忧，许多人批评 Anthropic 未能及早发现漏洞，并呼吁对共享数据采取更好的保护措施。

**标签**: `#privacy`, `#AI`, `#security`, `#Anthropic`, `#Claude`

---

<a id="item-4"></a>
## [男子因胁迫密码在边境擦除手机面临联邦指控](https://decrypt.co/374394/border-agents-phone-duress-passcode-grapheneos) ⭐️ 8.0/10

Samuel Tunick 在无证边境搜查中触发了 GrapheneOS 的胁迫密码，导致手机被恢复出厂设置。联邦检察官以破坏财产罪起诉他，而他的律师辩称这是行使数字权利。 这是美国首例涉及胁迫密码的案件，引发了关于第四修正案和边境数字隐私的新法律问题。判决结果可能为法院如何处理旨在防止未经授权访问数据的安全功能树立先例。 GrapheneOS 是一个注重隐私的基于 Android 的操作系统，包含胁迫密码功能；在强制解锁时输入该密码会触发恢复出厂设置。Tunick 的手机是运行 GrapheneOS 的 Google Pixel，事件发生在美国机场的一次无证搜查中。

rss · Decrypt · Jul 27, 17:40

**背景**: 根据边境搜查例外原则，美国海关人员可以在没有搜查令的情况下搜查旅客及其物品，包括电子设备。胁迫密码是一种安全功能，允许用户在胁迫下解锁设备，同时秘密触发数据销毁。此案测试了此类功能在妨碍司法法律下的法律边界。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/374394/border-agents-phone-duress-passcode-grapheneos">A Man Gave Border Agents His Phone Passcode . It Wiped... - Decrypt</a></li>
<li><a href="https://www.ibtimes.co.uk/us-federal-case-duress-passcodes-border-1810655">American Charged in First Known US Case Over Use of a ' Duress ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Border_search_exception">Border search exception - Wikipedia</a></li>

</ul>
</details>

**标签**: `#digital rights`, `#privacy`, `#GrapheneOS`, `#border search`, `#security`

---

<a id="item-5"></a>
## [Opus 5 在 SlopCodeBench 上的基准测试](https://github.com/humanlayer/advanced-context-engineering-for-coding-agents/blob/main/benchmarking-opus-5-on-slop-code-bench.md) ⭐️ 7.0/10

一项新基准测试 SlopCodeBench 评估了 Opus 5 与先前模型在生产代码质量上的表现，结果显示其相比 Opus 4.8 有渐进式改进。 该基准测试关注非功能性和纵向代码质量，这在模型能够解决即时问题但难以在迭代开发中保持可维护性的背景下至关重要。 SlopCodeBench 包含 36 个问题和 196 个检查点，要求智能体反复扩展自己的解决方案，从而测试架构决策和代码随时间的退化情况。

hackernews · dhorthy · Jul 27, 22:37 · [社区讨论](https://news.ycombinator.com/item?id=49076391)

**背景**: SlopCodeBench 是一个社区基准测试，用于评估编码智能体在长期迭代任务上的表现，模拟需求频繁变化的真实软件开发场景。Opus 5 是 Anthropic 于 2026 年 7 月发布的最新模型，在成本不变的情况下性能优于 Opus 4.8。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-opus-5">Introducing Claude Opus 5 \ Anthropic</a></li>
<li><a href="https://arxiv.org/abs/2603.24755">[2603.24755] SlopCodeBench: Benchmarking How Coding Agents Degrade Over Long-Horizon Iterative Tasks</a></li>
<li><a href="https://www.scbench.ai/">SlopCodeBench</a></li>

</ul>
</details>

**社区讨论**: 评论者指出 Opus 5 有不错的改进但并非革命性，有人对原始测试结果和可能的测试设计问题表示好奇。一位用户用 Opus 5 medium 替换了 Opus 4.8 xhigh 以提高效率。

**标签**: `#benchmarking`, `#LLM`, `#code generation`, `#software engineering`, `#AI evaluation`

---

<a id="item-6"></a>
## [Lido 转移 165 亿美元质押 ETH 以减少验证者数量](https://www.coindesk.com/tech/2026/07/27/lido-begins-moving-usd16-5-billion-in-staked-ether-to-cut-validator-count-by-a-third) ⭐️ 7.0/10

Lido 已开始将超过 800 万枚 ETH（价值 165 亿美元）从小型验证者转移到以太坊 Pectra 升级后新支持的更大的 0x02 验证者上，目标是将验证者数量减少三分之一。 此次整合提高了 Lido 的运营效率，并减少了以太坊的网络开销，可能降低 Lido 用户的成本并增加质押奖励。这也展示了 Pectra 升级新验证者功能的实际应用。 Pectra 升级将每个验证者的最大有效余额从 32 ETH 提高到 2,048 ETH，使 Lido 能够将许多小型验证者合并为更少但更大的验证者。Lido 目前运营着以太坊约 30%的验证者。

rss · CoinDesk · Jul 27, 14:00

**背景**: Lido 是一个流动性质押协议，允许用户质押任意数量的 ETH 并获得 stETH 代币。以太坊上的验证者负责提议和证明区块，每个验证者需要至少 32 ETH 才能激活。Pectra 升级于 2026 年 7 月在主网上线，引入了具有更高余额上限的 0x02 验证者，以提高质押效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kiln.fi/post/ethereum-pectra-upgrade---everything-you-need-to-know">Ethereum Pectra upgrade – everything you need to know</a></li>
<li><a href="https://beincrypto.com/ethereum-pectra-upgrade-live/">Ethereum Pectra Upgrade Hits Mainnet— Validator Caps Jump to...</a></li>
<li><a href="https://decrypt.co/resources/what-is-the-pectra-upgrade-inside-ethereums-future-roadmap">What Is the Pectra Upgrade ? Enhancing Ethereum ’s Flexibility</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#DeFi`, `#Staking`, `#Lido`

---

<a id="item-7"></a>
## [英伟达组建 37 家 AI 安全联盟，排除主要 AI 公司](https://www.coindesk.com/tech/2026/07/27/nvidia-forms-37-member-ai-security-alliance-without-openai-anthropic-or-google) ⭐️ 7.0/10

英伟达与 36 家合作伙伴共同成立了开放安全 AI 联盟，旨在开发开源 AI 安全工具和标准，值得注意的是，OpenAI、Anthropic 和谷歌未被纳入。 该联盟标志着 AI 安全治理的战略转变，可能绕过主要 AI 开发者创建行业标准，影响整个生态系统中 AI 安全工具的开发与采用。 该联盟已发布名为 NOOA（英伟达开放 AI 编排）的开源框架，但治理结构和联合交付成果尚未披露。排除 OpenAI、Anthropic 和谷歌表明 AI 安全领域的竞争态势。

rss · CoinDesk · Jul 27, 13:25

**背景**: 随着 AI 系统在敏感应用中的部署日益增多，AI 安全已成为关键问题。开源安全工具允许组织审计和定制防御措施，但标准碎片化可能阻碍互操作性。英伟达此举旨在为 AI 安全建立统一的开放生态系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thehackernews.com/2026/07/nvidia-forms-37-member-open-secure-ai.html">NVIDIA Forms 37-Member Open Secure AI Alliance and Open ...</a></li>
<li><a href="https://www.coindesk.com/tech/2026/07/27/nvidia-forms-37-member-ai-security-alliance-without-openai-anthropic-or-google">Nvidia forms 37-member AI security alliance without OpenAI ...</a></li>
<li><a href="https://blogs.nvidia.com/blog/open-secure-ai-alliance/">Industry Leaders Join Open Secure AI Alliance for AI Safety ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#security`, `#Nvidia`, `#alliance`, `#industry`

---

<a id="item-8"></a>
## [Circle 从 IBM 收购近 1000 项区块链专利](https://www.coindesk.com/business/2026/07/27/circle-buys-nearly-1-000-blockchain-patents-from-ibm) ⭐️ 7.0/10

USDC 发行商 Circle 从 IBM 收购了近 1000 项区块链专利，成为美国区块链专利持有量第一的公司。 此次收购大幅增强了 Circle 的知识产权组合，可能使其在区块链和数字资产领域获得竞争优势，尤其是面对仍由 IBM 支持的 USDC“最危险竞争对手”时。 该交易包括超过 680 个专利族和全球近 1000 项专利授权，约占 IBM 区块链专利组合的 70%。

rss · CoinDesk · Jul 27, 12:47

**背景**: 区块链专利授予对区块链技术相关特定发明的专有权。Circle 是 USDC 的发行商，USDC 是一种与美元挂钩的主要稳定币。IBM 一直是区块链领域的专利大户，此次出售标志着其战略转变。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.bitcoin.com/circle-acquires-1000-blockchain-patents-from-ibm-to-fuel-digital-asset-expansion/">Circle Acquires 1,000 Blockchain Patents From IBM to Fuel Digital...</a></li>
<li><a href="https://genfinity.io/2026/07/27/circle-acquires-ibm-blockchain-patent-portfolio-usa/">Circle Buys IBM's Blockchain Patents , Becoming the Top... - Genfinity</a></li>
<li><a href="https://decrypt.co/374388/circle-ibm-blockchain-patent-estate">Circle Buys IBM Blockchain Patent Estate—And Becomes... - Decrypt</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#patents`, `#Circle`, `#IBM`, `#intellectual property`

---

<a id="item-9"></a>
## [专家警告：加密货币首当其冲面临量子威胁](https://www.coindesk.com/markets/2026/07/27/crypto-is-the-canary-in-the-coal-mine-for-the-quantum-computing-threat-experts-say) ⭐️ 7.0/10

专家指出，由于加密货币系统依赖公钥密码学，它们将成为首批易受运行 Shor 算法的量子计算机攻击的主要系统。这种紧迫性正推动业界呼吁快速迁移到抗量子密码学。 如果量子计算机破解当前的密码学标准，整个加密货币生态系统（包括比特币和以太坊）可能被攻破，导致资金损失和信任崩塌。这使得加密货币成为更广泛的金融和数据保护领域量子安全转型的关键试验场。 Shor 算法可以高效求解支撑大多数加密货币安全的 ECDSA 背后的离散对数问题。虽然当前量子计算机还不够强大，但“先收集、后解密”攻击的风险意味着今天记录的数据未来可能被解密。

rss · CoinDesk · Jul 27, 06:37

**背景**: 当前大多数公钥密码学（包括 RSA 和椭圆曲线密码学）依赖于量子计算机可通过 Shor 算法高效求解的数学问题。后量子密码学（PQC）旨在开发抵抗此类攻击的算法。2024 年，NIST 发布了首批三个 PQC 标准，但迁移是一个漫长的过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Quantum-resistant_cryptography">Quantum-resistant cryptography</a></li>
<li><a href="https://postquantum.com/quantum-threat-crypto/quantum-threat-overview/">The Quantum Threat to Cryptocurrencies: What's Real</a></li>
<li><a href="https://synxcrypto.com/terms/shors-algorithm.php">Shor's Algorithm Explained: The Quantum Threat to Cryptocurrency</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#cryptography`, `#blockchain`, `#security`, `#cryptocurrency`

---

<a id="item-10"></a>
## [SparkKitty 恶意软件藏身应用商店窃取加密货币种子短语](https://decrypt.co/374450/sparkkitty-malware-mobile-apps-crypto-wallet) ⭐️ 7.0/10

Check Point 的安全研究人员详细介绍了 SparkKitty，这是一种新型恶意软件，通过隐藏在看似合法的移动应用中，侵入了苹果 App Store 和 Google Play，并扫描用户相册中的加密货币钱包恢复短语。 这一发现凸显了加密货币持有者面临的日益严重的威胁，恶意软件能够绕过官方应用商店的审查流程，窃取种子短语等敏感数据，可能导致资金不可逆转地损失。 SparkKitty 是早期 SparkCat 恶意软件的进化版本，它利用光学字符识别（OCR）从受感染设备存储的图片中提取种子短语。

rss · Decrypt · Jul 27, 20:09

**背景**: 加密货币钱包种子短语是一组单词，作为私钥的备份，允许用户在设备丢失或损坏时恢复其加密货币资产。窃取这些短语的恶意软件可以让攻击者完全控制受害者的资金。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cyberint.com/blog/dark-web/sparkkitty-malware-an-emerging-threat-to-mobile-users/">SparkKitty Malware: An Emerging Threat to Mobile Users - Cyberint</a></li>
<li><a href="https://zimperium.com/blog/mobile-threat-watch/sparkkitty-malware-sneaks-into-trusted-mobile-apps-to-harvest-sensitive-photos">SparkKitty Malware Sneaks into Trusted Mobile Apps to ... - Zimperium</a></li>
<li><a href="https://www.broadcom.com/support/security-center/protection-bulletin/new-mobile-crypto-stealing-malware-sparkkitty">New mobile crypto-stealing malware SparkKitty - Broadcom Inc.</a></li>

</ul>
</details>

**标签**: `#malware`, `#cryptocurrency`, `#security`, `#mobile`

---

<a id="item-11"></a>
## [微软声称 MDASH 在网络安全测试中击败 Claude Mythos 和 GPT-5.6 Sol](https://decrypt.co/374441/microsoft-mdash-beats-claude-mythos-gpt-5-6-sol-cybersecurity) ⭐️ 7.0/10

微软发布了其首个专用网络安全模型 MAI-Cyber-1-Flash，并将其集成到 MDASH 中，这是一个漏洞搜寻系统，能够驱动超过 100 个 AI 代理以之前最佳配置一半的成本发现软件缺陷。 这一声明表明自动化漏洞发现取得了重大飞跃，可能降低组织成本并提高安全性。如果得到验证，它可能改变 AI 驱动网络安全的竞争格局，挑战 Anthropic 的 Claude Mythos 和 OpenAI 的 GPT-5.6 Sol。 MDASH 被描述为一个用于软件漏洞识别和修复的多模型代理扫描框架。微软声称 MDASH 在网络安全测试中优于 Anthropic 的 Mythos 5 和 OpenAI 的 GPT-5.6 Sol，但尚未有独立验证。

rss · Decrypt · Jul 27, 19:01

**背景**: 大型语言模型（如 GPT-5.6 和 Claude）越来越多地用于网络安全任务，如代码分析和漏洞发现。微软的 MDASH 框架结合了多个 AI 模型，自动化发现和修复软件缺陷的过程，旨在减少误报并聚焦于可利用的漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/07/27/microsoft-launches-its-first-cyber-model-and-a-new-agentic-cybersecurity-system/">Microsoft launches its first cybersecurity model , plus... | TechCrunch</a></li>
<li><a href="https://www.zdnet.com/article/build-2026-mdash-security-ai-agents/">Build 2026: Microsoft 's MDASH exits preview with 100+... | ZDNET</a></li>
<li><a href="https://openai.com/index/gpt-5-6/">GPT‑5.6: Frontier intelligence that scales with your ambition</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#AI agents`, `#Microsoft`, `#software flaws`

---

<a id="item-12"></a>
## [Mira Murati 的 Inkling AI 模型：西方最佳开放权重模型](https://decrypt.co/373884/review-inkling-mira-murati-first-open-source-ai) ⭐️ 7.0/10

Mira Murati 的 Thinking Machines Lab 发布了其首个开放权重 AI 模型 Inkling，现已在 OpenRouter 上可用。该模型在 MCP 评分上表现强劲，并在 SWE-Bench Verified 上达到 77.6%，超过了 Nemotron 的 70.7%。 Inkling 是前 OpenAI CTO 领导的高调 AI 实验室的首次重大发布，标志着开放权重模型领域竞争再起。其强劲的基准测试表现可能挑战其他西方开源模型，但定价复杂性可能影响采用。 根据评测，该模型的 MCP 评分令人印象深刻，但其性价比较为复杂。Inkling 托管在 OpenRouter 上，该平台通过分布式基础设施提供多种 AI 模型的访问。

rss · Decrypt · Jul 26, 14:01

**背景**: 开放权重模型允许开发者访问和修改模型权重，比封闭模型更灵活。MCP（模型上下文协议）是连接 AI 模型与外部工具和数据的标准。SWE-Bench Verified 测试 AI 自主修复 GitHub bug 的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/373884/review-inkling-mira-murati-first-open-source-ai">Mira Murati’s Inkling AI Model Review: Best Open-Source... - Decrypt</a></li>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>

</ul>
</details>

**标签**: `#AI`, `#open-source`, `#model review`, `#Mira Murati`

---

<a id="item-13"></a>
## [宇航员报告任务后持续存在“旁观者”感](https://spacedaily.com/sd-v-astronauts-returning-from-six-month-missions-describe-a-persistent-observer-sensation-the-feeling-of-watching-their-own-lives-from-a-half-step-outside-the-frame-weeks-after-theyr/) ⭐️ 6.0/10

从为期六个月的国际空间站任务返回的宇航员描述了一种持续的“旁观者”感，感觉仿佛在返回地球后数周内从体外观看自己的生活。 这一现象引发了关于大脑如何适应长期太空飞行并重新融入地球引力的新问题，对未来深空任务具有影响。 飞行医生认为这种感觉是任务后调整的一部分，但缺乏强有力的科学证实，可能涉及虚构或解离。

hackernews · zdw · Jul 27, 23:19 · [社区讨论](https://news.ycombinator.com/item?id=49076900)

**背景**: 解离是一种心理现象，个体感到与自己的思想、情感或身体分离，常被描述为“出体”体验。它可能发生在太空或潜艇等极端环境中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.spacedaily.com/sd-v-astronauts-returning-from-six-month-missions-describe-a-persistent-observer-sensation-the-feeling-of-watching-their-own-lives-from-a-half-step-outside-the-frame-weeks-after-theyr/">Astronauts returning from six-month missions describe a ...</a></li>
<li><a href="https://www.argo.net/astronauts-returning-from-six-month-iss-missions-describe-an-observer-sensation-raising-new-questions-about-how-the-brain-rebuilds-daily-life-on-earth-after-long-duration-spaceflight/">Astronauts returning from six-month ISS missions describe an ...</a></li>

</ul>
</details>

**社区讨论**: 评论者指出这与潜艇船员中记录的解离现象相似，并因缺乏佐证来源质疑文章的有效性，认为可能是 AI 虚构。

**标签**: `#space`, `#psychology`, `#dissociation`, `#astronaut health`

---

<a id="item-14"></a>
## [Kalshi 和 Polymarket 赢得明尼苏达州预测市场禁令暂停](https://www.coindesk.com/policy/2026/07/27/kalshi-polymarket-win-pause-against-minnesota-s-prediction-market-ban) ⭐️ 6.0/10

Kalshi 和 Polymarket 获得了对明尼苏达州预测市场禁令的法律暂停，允许他们在案件审理期间继续在该州运营。 这一裁决为各州如何监管预测市场树立了先例，可能影响这些平台运营的更广泛的加密货币和区块链生态系统。 该暂停是临时性的，仅适用于明尼苏达州；法律挑战的最终结果将决定美国预测市场的长期监管格局。

rss · CoinDesk · Jul 27, 23:29

**背景**: 预测市场允许用户就未来事件（如选举或体育）的结果进行交易。Kalshi 是一个受联邦监管的交易所，而 Polymarket 是建立在区块链上的去中心化平台。明尼苏达州曾以赌博和市场诚信为由，试图禁止此类平台。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kalshi">Kalshi - Wikipedia</a></li>
<li><a href="https://polymarket.com/">Polymarket | The World's Largest Prediction Market™</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#regulation`, `#blockchain`, `#legal`

---

<a id="item-15"></a>
## [泰国 SEC 指控 Bitkub 隐瞒 5000 万美元黑客攻击](https://www.coindesk.com/policy/2026/07/27/thailand-s-sec-alleges-bitkub-concealed-cyberattack-that-led-to-usd50-million-hack) ⭐️ 6.0/10

泰国证券交易委员会（SEC）指控加密货币交易所 Bitkub 隐瞒了一起导致 5000 万美元被盗的网络攻击。 此案凸显了监管机构对加密货币交易所安全漏洞和透明度的日益关注，可能为泰国及其他地区的执法行动树立先例。 SEC 指控 Bitkub 未能及时披露网络攻击，违反了披露义务。此次 5000 万美元的黑客攻击是涉及泰国加密货币交易所的最大安全事件之一。

rss · CoinDesk · Jul 27, 13:32

**背景**: Bitkub 是一家成立于 2018 年的泰国加密货币交易所，并于 2019 年成为首批获得泰国 SEC 数字资产牌照的交易所之一。该交易所已发展成为泰国最大的交易所之一，处理大量交易。SEC 的指控凸显了网络安全和披露在加密行业中的重要性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bitkub">Bitkub</a></li>
<li><a href="https://legalbison.com/crypto-license/thailand/">Crypto License in Thailand | Expert Legal Consulting... - LegalBison</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#cybersecurity`, `#regulation`, `#Bitkub`

---

<a id="item-16"></a>
## [Securitize 获得 SEC 顾问牌照，推动代币化发展](https://www.coindesk.com/business/2026/07/27/securitize-builds-wall-street-credentials-with-sec-adviser-license-as-tokenization-expands) ⭐️ 6.0/10

领先的代币化平台 Securitize 获得了美国证券交易委员会（SEC）的投资顾问牌照，这标志着在现实世界资产代币化扩张之际，该公司在建立华尔街信誉方面迈出了重要一步。 该牌照允许 Securitize 提供受监管的咨询服务，弥合传统金融与基于区块链的代币化之间的差距。这标志着机构对代币化资产的接受度不断提高，并可能加速资产管理者与投资者的采用。 SEC 投资顾问牌照要求公司根据 1940 年《投资顾问法》进行注册并遵守相关法规，包括信托责任和披露义务。Securitize 的平台专门从事私募股权、房地产和风险投资基金等现实世界资产的代币化。

rss · CoinDesk · Jul 27, 13:00

**背景**: 代币化是指将资产权利转换为区块链上的数字代币，从而实现分式所有权和更便捷的交易。Securitize 是该领域的领先平台，提供发行、投资者管理和合规服务。SEC 监管投资顾问以保护投资者并确保市场诚信。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://securitize.io/">Securitize | The Leading Tokenization Platform</a></li>
<li><a href="https://www.gate.com/learn/articles/what-is-securitize">What Is Securitize ? A Comprehensive Understanding of... | Gate Learn</a></li>
<li><a href="https://smartasset.com/advisor-resources/registering-with-the-sec">How to Register With the SEC as an Investment Advisor</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#regulation`, `#blockchain`, `#finance`

---

<a id="item-17"></a>
## [Fanatics 收购 CFTC 注册交易所进军预测市场](https://decrypt.co/374449/fanatics-buys-cftc-registered-exchange-prediction-markets) ⭐️ 6.0/10

Fanatics 收购了 BGC 旗下的 Water Street Labs 和 CX Clearinghouse（一家 CFTC 注册交易所），以便在预测市场领域上市和结算自己的事件合约。 此举使 Fanatics 能够在快速增长的预测市场和体育博彩领域与 DraftKings 和 FanDuel 直接竞争，利用受监管的交易所提供事件合约。 此次收购包括一家 CFTC 注册的指定合约市场（DCM）和一家清算所，使 Fanatics 能够自行上市和清算事件合约，无需依赖第三方。

rss · Decrypt · Jul 27, 19:45

**背景**: 预测市场，也称为事件衍生品，允许交易者对特定事件（如选举或体育比赛结果）的结果进行投注。CFTC 注册交易所必须遵守《商品交易法》下的核心原则，接受监管监督。Fanatics 主要作为体育商品零售商而闻名，正在向体育博彩和预测市场领域扩张。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cftc.gov/IndustryOversight/TradingOrganizations/DCMs/index.htm">Designated Contract Markets (DCMs) | CFTC 17 CFR 3.12 -- Registration of associated persons of futures ... eCFR :: 17 CFR Part 40 -- Provisions Common to Registered ... SEC, CFTC-Registered Exchanges Receive Blessing to Facilitate ... Registration and Membership | NFA National Securities Exchanges - SEC.gov Top Stories</a></li>
<li><a href="https://www.investopedia.com/events-contracts-8601422">Event Contracts: What They Are and How They Are Used Free Event Contract Template For 2025 - getcone.io Free Event Contract Template - Event Planning & Venue ... Event Planning Contracts For Clients In Phoenix - US Legal Forms Free Customizable Event Venue Contract Template | LawDepot Understanding Prediction Markets and Event Contracts | CFTC Event Contract Best Practices: What to Include (and What to ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prediction_market">Prediction market</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#sports betting`, `#crypto`, `#regulation`, `#Fanatics`

---

<a id="item-18"></a>
## [KB 国民银行将在摩根大通 Kinexys 上推出跨境支付](https://www.theblock.co/post/409702/kb-kookmin-bank-payment-jpmorgans-kinexys?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

据韩联社报道，韩国最大银行 KB 国民银行计划下月在摩根大通的 Kinexys 平台上推出基于区块链的跨境企业支付服务。 这标志着大型传统银行在跨境支付中显著采用区块链，可能加速从传统代理银行模式向更快、更透明的结算系统的转变。 该服务最初将支持 10 个国家的美元结算，利用 Kinexys 的近实时结算能力，将转账时间从超过 24 小时缩短至几分钟。

rss · The Block · Jul 27, 06:38

**背景**: Kinexys（前身为 Onyx）是摩根大通的企业区块链平台，用于可编程支付、资产代币化和近实时结算。传统跨境支付依赖缓慢、多中介的代理银行网络。像 Kinexys 这样的区块链解决方案旨在通过实现直接、透明和更快的交易来简化这一流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.jpmorgan.com/kinexys/index">Kinexys : Enterprise Bank-Led Blockchain Solutions</a></li>
<li><a href="https://cointelegraph.com/news/south-korea-bank-payment-jpmorgans-kinexys">KB Kookmin Bank to Launch JPMorgan Kinexys Cross - Border ...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#cross-border payments`, `#banking`, `#South Korea`

---