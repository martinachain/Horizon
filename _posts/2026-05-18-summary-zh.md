---
layout: default
title: "Horizon Summary: 2026-05-18 (ZH)"
date: 2026-05-18
lang: zh
---

> From 30 items, 9 important content pieces were selected

---

1. [Semble：为 AI 代理提供代码搜索，减少 98%的令牌](#item-1) ⭐️ 8.0/10
2. [KelpDAO 2.93 亿美元黑客事件迫使 DeFi 走向成熟](#item-2) ⭐️ 8.0/10
3. [Verus-Ethereum 桥接器遭攻击，损失 1160 万美元](#item-3) ⭐️ 8.0/10
4. [将 80 美元的 RK3562 安卓平板变成 Debian 工作站](#item-4) ⭐️ 7.0/10
5. [特斯拉太阳能屋顶受挫，转向传统面板](#item-5) ⭐️ 7.0/10
6. [GitHub 上 CUDA 书籍列表引发批评性评论](#item-6) ⭐️ 6.0/10
7. [Jump Crypto 的 Firedancer 对 Solana 部署采取谨慎态度](#item-7) ⭐️ 6.0/10
8. [Circle 推出专为稳定币设计的 Layer-1 区块链 Arc](#item-8) ⭐️ 6.0/10
9. [AI 越狱：新手必读的猫鼠游戏指南](#item-9) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Semble：为 AI 代理提供代码搜索，减少 98%的令牌](https://github.com/MinishLab/semble) ⭐️ 8.0/10

Semble 是一个开源代码搜索工具，结合了静态 Model2Vec 嵌入和 BM25，相比 grep+read 减少了 98% 的令牌，同时保持了 137M 参数 transformer 模型 99% 的检索质量。它完全在 CPU 上运行，无需 GPU 或 API 密钥。 这解决了 AI 编码代理的一个关键瓶颈：在搜索大型代码库时过度消耗令牌。通过大幅减少令牌消耗，Semble 可以降低使用 Claude Code、Cursor 和 Codex 等工具的成本并提高响应速度。 Semble 在 CPU 上索引一个典型仓库约需 250ms，查询约需 1.5ms，使用自定义的 16M 参数静态嵌入模型 (potion-code-16M)。它通过倒数排名融合 (RRF) 融合 BM25 和嵌入分数，并应用代码感知重排序。

hackernews · Bibabomas · May 17, 15:37 · [社区讨论](https://news.ycombinator.com/item?id=48169874)

**背景**: AI 编码代理通常使用 grep 查找相关代码，这会读取整个文件并消耗大量令牌。传统的语义搜索工具依赖基于 transformer 的嵌入，需要 GPU 且索引速度慢。Semble 使用静态嵌入 (Model2Vec)，这些嵌入是预计算且快速的，并结合 BM25 进行关键词匹配。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.weaviate.io/weaviate/model-providers/model2vec/embeddings">Text Embeddings | Weaviate Documentation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Okapi_BM25">Okapi BM 25 - Wikipedia</a></li>
<li><a href="https://medium.com/@devalshah1619/mathematical-intuition-behind-reciprocal-rank-fusion-rrf-explained-in-2-mins-002df0cc5e2a">Reciprocal Rank Fusion ( RRF ) explained in 4 mins — How... | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区评论担心 AI 代理依赖此类工具可能会变得更“笨”，以及代理是否信任非 grep 工具的结果。一些用户将 Semble 与 Cursor 的工作区索引等现有方案进行了比较，并指出需要代理基准测试来验证实际的令牌节省效果。

**标签**: `#code search`, `#AI agents`, `#token efficiency`, `#open source`, `#retrieval`

---

<a id="item-2"></a>
## [KelpDAO 2.93 亿美元黑客事件迫使 DeFi 走向成熟](https://www.coindesk.com/tech/2026/05/16/the-usd293-million-kelpdao-hack-shows-why-defi-is-finally-being-forced-to-grow-up) ⭐️ 8.0/10

2026 年 4 月 18 日，与朝鲜 Lazarus Group 有关的攻击者从 KelpDAO 的 LayerZero 桥中盗走了约 2.93 亿美元（116,500 rsETH），此次攻击利用了链下基础设施而非智能合约漏洞。 这一事件表明，随着协议通过桥接实现深度互联，DeFi 最大的漏洞正从智能合约漏洞转向基础设施、治理和运营安全。 此次攻击并非智能合约漏洞，而是一次针对链下基础设施的复杂攻击，诱骗桥释放了不应释放的代币。

rss · CoinDesk · May 16, 13:00

**背景**: DeFi（去中心化金融）协议通常使用桥在不同区块链之间转移资产。这些桥是关键基础设施，但其链下组件（如验证者或中继器）可能受到攻击。KelpDAO 黑客事件是最大的 DeFi 攻击之一，凸显了整个生态系统需要改进安全实践。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chainalysis.com/blog/kelpdao-bridge-exploit-april-2026/">Inside the KelpDAO Bridge Exploit</a></li>
<li><a href="https://www.coindesk.com/tech/2026/05/16/the-usd293-million-kelpdao-hack-shows-why-defi-is-finally-being-forced-to-grow-up">Ethereum news (ETH): The $293 million KelpDAO hack shows why DeFi is finally being forced to grow up</a></li>
<li><a href="https://www.galaxy.com/insights/research/kelpdao-layerzero-exploit-defi">KelpDAO/LayerZero Hack: $290m Exploit Exposes DeFi’s Hidden Risks | Galaxy</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#hack`, `#KelpDAO`, `#cryptocurrency`

---

<a id="item-3"></a>
## [Verus-Ethereum 桥接器遭攻击，损失 1160 万美元](https://www.theblock.co/post/401571/verus-ethereum-bridge-exploit?utm_source=rss&utm_medium=rss) ⭐️ 8.0/10

据区块链安全公司 Peckshield 和 Blockaid 报告，Verus-Ethereum 桥接器正在遭受攻击，已损失约 1160 万美元。攻击者盗取了 103.6 个 tBTC、1625 个 ETH 和 14.7 万个 USDC。 此事件凸显了跨链桥接器（DeFi 互操作性的关键基础设施）持续存在的安全漏洞。此次损失加剧了桥接器攻击的案例，削弱了用户对跨链解决方案的信任。 Blockaid 已将攻击者地址识别为 0x5aBb…D5777。攻击仍在进行中，意味着在漏洞修复前可能还会产生更多损失。

rss · The Block · May 18, 02:54

**背景**: 跨链桥接器允许用户在不同区块链之间转移资产，例如通过 tBTC 等封装代币将比特币转移到以太坊。然而，这些桥接器结构复杂，常因安全漏洞成为黑客攻击目标。tBTC 是一种完全由比特币支持的代币，使 BTC 持有者能够在基于以太坊的 DeFi 协议中使用其资产。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://beincrypto.com/verus-bridge-exploit-may-defi-hacks/">Crypto Hack Wave Hits Verus Bridge as May DeFi Losses Mount</a></li>
<li><a href="https://www.coindesk.com/markets/2026/05/18/yet-another-crypto-bridge-falls-victim-to-an-usd11-million-hack">Verus-Ethereum bridge loses $11 million as hackers keep ...</a></li>
<li><a href="https://www.theblock.co/post/401571/verus-ethereum-bridge-exploit">Ongoing exploit drains $11.6 million from Verus-Ethereum ...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#security`, `#exploit`, `#cryptocurrency`

---

<a id="item-4"></a>
## [将 80 美元的 RK3562 安卓平板变成 Debian 工作站](https://github.com/tech4bot/rk3562deb) ⭐️ 7.0/10

一位爱好者发布了一份指南，在搭载 Rockchip RK3562 的 80 美元安卓平板上安装预发布的 Debian 12 镜像，无需修改内部存储即可启动 Linux。 这展示了将廉价安卓硬件改造成功能型 Linux 设备的潜力，扩大了爱好者使用 Linux 的途径，并减少了电子垃圾。 该平板仅有 4GB 内存，可能限制多任务处理；指南使用 Debian Bookworm（12）而非 Trixie（13）以保持稳定性，且启动过程无需解锁引导加载程序。

hackernews · tech4bot · May 17, 13:16 · [社区讨论](https://news.ycombinator.com/item?id=48168668)

**背景**: Rockchip RK3562 是一款四核 Cortex-A55 处理器，常用于低成本安卓平板。在此类设备上安装完整 Linux 发行版通常需要自定义固件或修改引导加载程序，但该方法绕过了这些步骤。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techtrendtrove.com/tablets/i-turned-a-80-rk3562-android-tablet-into-a-debian-linux-workstation-2/">I turned a $80 RK3562 Android tablet into a Debian Linux workstation</a></li>
<li><a href="https://bestcadpapers.com/tips-hacks-miscellaneous/i-turned-a-80-rk3562-android-tablet-into-a-debian-linux-workstation/">I turned a $80 RK3562 Android tablet into a Debian Linux workstation</a></li>

</ul>
</details>

**社区讨论**: 评论者就 4GB 内存的可用性展开讨论，有人认为足以胜任终端开发或模拟等轻量任务，也有人担心多任务处理受限。此外，还有人提议利用 AI 逆向工程类似设备以扩大移植范围。

**标签**: `#Linux`, `#Embedded Systems`, `#Hardware Hacking`, `#Debian`, `#Tablet`

---

<a id="item-5"></a>
## [特斯拉太阳能屋顶受挫，转向传统面板](https://electrek.co/2026/05/14/tesla-solar-roof-promise-vs-reality-pivot-panels/) ⭐️ 7.0/10

据报道，特斯拉因高成本和执行难题正放弃其太阳能屋顶产品，重新聚焦于传统太阳能面板。太阳能屋顶安装前成本约 10.6 万美元，而屋顶加面板方案约 6 万美元，投资回收期分别为 15-25 年和 7-12 年。 这一转变凸显了将太阳能大规模集成到建筑材料中的难度，可能通过强化传统面板的主导地位来重塑住宅太阳能市场。同时也引发了对特斯拉整体能源战略及其执行雄心勃勃产品愿景能力的质疑。 太阳能屋顶比传统屋顶加面板方案贵 4.6 万美元，对大多数房主而言经济上不可行。社区评论指出，特斯拉的执行问题包括低估了服务与长期支持的重要性。

hackernews · celsoazevedo · May 17, 04:09 · [社区讨论](https://news.ycombinator.com/item?id=48165980)

**背景**: 特斯拉太阳能屋顶作为高端产品推出，用发电瓦片替代传统屋顶瓦片，旨在兼顾美观与能源生产。然而，屋顶太阳能市场通过低成本、快速安装的系统增长，使得昂贵的集成解决方案竞争力下降。

**社区讨论**: 社区评论表达了失望，但指出失败源于执行和经济性，而非概念本身。有人指出，可见的太阳能面板正变得更容易被社会接受，削弱了太阳能屋顶的美学优势。

**标签**: `#Tesla`, `#solar energy`, `#business strategy`, `#renewable energy`

---

<a id="item-6"></a>
## [GitHub 上 CUDA 书籍列表引发批评性评论](https://github.com/alternbits/awesome-cuda-books) ⭐️ 6.0/10

一个名为“awesome-cuda-books”的 GitHub 仓库整理了 CUDA 编程书籍列表，但社区评论指出许多旧书已过时，并推荐了 Warp 等现代替代方案以及 CUDA 架构师 Stephen Jones 的视频。 这一讨论帮助学习者避免在过时的资源上浪费时间，并引导他们获取最新、有效的 GPU 编程学习材料，这对人工智能和高性能计算等领域至关重要。 该仓库列出了《CUDA by Example》和《Programming Massively Parallel Processors》等书籍，但评论者指出这些书存在错误或过于简单。现代替代方案包括 NVIDIA 的 Warp（用于在 Python 中编写 CUDA 内核）以及一位 CUDA 架构师的全面视频。

hackernews · dariubs · May 17, 12:52 · [社区讨论](https://news.ycombinator.com/item?id=48168485)

**背景**: CUDA 是 NVIDIA 的 GPU 并行计算平台和编程模型。传统上学习 CUDA 需要阅读书籍，但该领域随着新硬件架构的演进而快速变化。GitHub 列表是一个起点，但社区反馈对于识别当前最佳实践至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.amazon.com/CUDA-Example-Introduction-General-Purpose-Programming/dp/0131387685">CUDA by Example: An Introduction to General-Purpose GPU...</a></li>
<li><a href="https://bookauthority.org/books/best-selling-cuda-books">7 Best-Selling CUDA Books Millions Love - BookAuthority</a></li>
<li><a href="https://shop.elsevier.com/books/cuda-programming/cook/978-0-12-415933-4">CUDA Programming - 1st Edition | Elsevier Shop</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认为较老的 CUDA 书籍已经过时，并推荐更新的资源。一位用户称赞《CUDA Programming: A Developer's Guide》是最好的入门书，另一位则推荐了 CUDA 架构师 Stephen Jones 的视频。还有一位用户强调 Warp 是基于 Python 的现代替代方案。

**标签**: `#CUDA`, `#GPU Programming`, `#Parallel Computing`, `#Books`

---

<a id="item-7"></a>
## [Jump Crypto 的 Firedancer 对 Solana 部署采取谨慎态度](https://www.coindesk.com/tech/2026/05/16/jump-crypto-s-firedancer-is-taking-a-slow-and-steady-approach-to-its-long-awaited-solana-infrastructure-rollout) ⭐️ 6.0/10

Jump Crypto 的 Firedancer（一个用 C 语言编写的全新 Solana 验证器客户端）正在以缓慢而稳定的方式部署到主网，优先考虑可靠性和安全性而非速度。首席工程师在 CoinDesk 采访中表示，团队正采取谨慎态度以确保网络稳定性。 Firedancer 旨在显著提升 Solana 的交易处理效率和网络弹性，可能实现超过 100 万 TPS。其谨慎部署反映了基础设施可靠性对于像 Solana 这样的高性能区块链的重要性，最终全面部署可能增强网络的竞争力。 Firedancer 完全用 C 语言编写，并采用高度并行的分片架构以实现高吞吐量。已发布一个中间里程碑以在完全实施前进行测试，并且 Neodyme 已完成安全审计。

rss · CoinDesk · May 16, 15:00

**背景**: Solana 是一个高性能区块链，依赖验证器客户端处理交易。目前主要客户端用 Rust 编写，而 Firedancer 是一个新的第三方客户端，旨在提高性能和去中心化程度。Jump Crypto（交易公司 Jump Trading 的加密部门）已开发 Firedancer 数年。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://jumpcrypto.com/build/firedancer">Firedancer - jumpcrypto.com</a></li>
<li><a href="https://www.coindesk.com/tech/2026/05/16/jump-crypto-s-firedancer-is-taking-a-slow-and-steady-approach-to-its-long-awaited-solana-infrastructure-rollout">Solana news (SOL): Jump Crypto’s ‘Firedancer’ is taking a ...</a></li>
<li><a href="https://www.kraken.com/learn/what-is-firedancer-solana">What is Firedancer , and why is it big for Solana ? | Kraken</a></li>

</ul>
</details>

**标签**: `#Solana`, `#blockchain`, `#infrastructure`, `#crypto`

---

<a id="item-8"></a>
## [Circle 推出专为稳定币设计的 Layer-1 区块链 Arc](https://decrypt.co/resources/what-is-arc-the-stablecoin-blockchain-from-usdc-issuer-circle) ⭐️ 6.0/10

USDC 发行商 Circle 宣布推出 Arc，这是一个兼容 EVM 的新 Layer-1 区块链，使用 USDC 作为交易手续费的本地 Gas 代币。 Arc 可能通过消除对第三方区块链的依赖来重塑稳定币金融，从而降低基于 USDC 的交易和代币化资产的成本并提高效率。 Arc 专为稳定币原生金融和代币化资产设计，Circle 已从 BlackRock 和 a16z 等投资者处筹集 2.22 亿美元，项目估值达 30 亿美元。

rss · Decrypt · May 17, 20:32

**背景**: 像 USDC 这样的稳定币通常发行在现有的区块链上（如以太坊或 Solana），依赖这些网络进行交易处理。Arc 是一个专用的 Layer-1 区块链，原生集成 USDC，意味着 USDC 用于 Gas 费用且不是桥接代币。这种方法旨在为基于稳定币的金融应用创建一个更高效、更集成的生态系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.bitcoin.com/circle-unveils-arc-blockchain-with-usdc-as-native-gas/">Circle Unveils Arc Blockchain With USDC as Native Gas</a></li>
<li><a href="https://www.okx.com/en-ae/learn/arc-blockchain-regulation-circle-layer1">Arc Blockchain Regulation: How Circle ’s New... | OKX UAE</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#stablecoin`, `#Circle`, `#layer-1`

---

<a id="item-9"></a>
## [AI 越狱：新手必读的猫鼠游戏指南](https://decrypt.co/resources/what-is-ai-jailbreaking-explained) ⭐️ 6.0/10

本文以通俗易懂的方式介绍了 AI 越狱，解释了如何通过提示注入等技术绕过大型语言模型（LLM）的安全过滤器。文章追溯了从通过 Cydia 越狱 iPhone 到现代 LLM 攻击的概念演变。 理解 AI 越狱对 AI 安全至关重要，因为这些攻击可能导致 LLM 生成有害或受限内容。攻击者与开发者之间的这场军备竞赛影响着数百万用户使用的 AI 应用的信任与安全。 常见的越狱方法包括角色扮演提示、将请求编码为 base64，以及使用叙事框架来欺骗模型。当 LLM 浏览网页并处理嵌入在网站中的对抗性内容时，还可能发生间接提示注入。

rss · Decrypt · May 16, 13:01

**背景**: AI 越狱指操纵大型语言模型（LLM）以绕过其内置安全和道德限制的技术。它源于越狱 iPhone 以解除软件限制的概念，Cydia 等工具曾使其流行。在 AI 语境中，攻击者精心构造特殊提示，使模型忽略其训练中的安全防护并生成被禁止的输出。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_jailbreaking">AI jailbreaking</a></li>
<li><a href="https://www.promptfoo.dev/blog/how-to-jailbreak-llms/">Jailbreaking LLMs: A Comprehensive Guide... | Promptfoo</a></li>
<li><a href="https://www.lakera.ai/blog/jailbreaking-large-language-models-guide">Jailbreaking Large Language Models: Techniques, Examples...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#jailbreaking`, `#LLM`, `#security`

---