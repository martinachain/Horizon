---
layout: default
title: "Horizon Summary: 2026-07-13 (ZH)"
date: 2026-07-13
lang: zh
---

> From 30 items, 12 important content pieces were selected

---

1. [Claude Code 在读取提示前发送 33k token，而 OpenCode 仅 7k](#item-1) ⭐️ 8.0/10
2. [将 AI 代理迁移至 GPT-5.6：速度提升 2.2 倍，成本降低 27%](#item-2) ⭐️ 8.0/10
3. [谷歌研究：更智能的路线规划可减少交通拥堵](#item-3) ⭐️ 8.0/10
4. [AI 自动化可能削弱人类监督能力](#item-4) ⭐️ 8.0/10
5. [AI 发现可导致以太坊验证者崩溃的漏洞](#item-5) ⭐️ 8.0/10
6. [8 位计算机的微型模拟器，采用引脚级模拟](#item-6) ⭐️ 7.0/10
7. [HN 用户提议为 AI 生成文章添加标记](#item-7) ⭐️ 7.0/10
8. [BIP 110 分叉截止日期临近，矿工支持率为零](#item-8) ⭐️ 7.0/10
9. [Bonzo 在 Hedera 上因预言机漏洞损失 77% 的 TVL，金额达 900 万美元](#item-9) ⭐️ 7.0/10
10. [LARP 网站讽刺创业公司收入基础设施](#item-10) ⭐️ 6.0/10
11. [在分心时代重新发现深度阅读](#item-11) ⭐️ 6.0/10
12. [Robinhood Chain：面向代币化股票的以太坊 L2 网络](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Claude Code 在读取提示前发送 33k token，而 OpenCode 仅 7k](https://systima.ai/blog/claude-code-vs-opencode-token-overhead) ⭐️ 8.0/10

一项新的实证研究发现，Claude Code 在读取用户提示前会发送约 33,000 个 token 的系统提示、工具模式和脚手架，而 OpenCode 仅发送 7,000 个 token，开销相差 4.7 倍。 这种 token 开销直接增加了成本、延迟，并减少了实际编码任务可用的上下文预算，使得 Claude Code 在类似工作上的运营成本远高于 OpenCode。 开销主要来自 Claude Code 的 27 个工具模式和注入的脚手架，且缓存不稳定导致相同任务下缓存写入次数是 OpenCode 的 5.9 到 54 倍。

hackernews · systima · Jul 12, 18:25 · [社区讨论](https://news.ycombinator.com/item?id=48883275)

**背景**: 像 Claude Code 和 OpenCode 这样的编码智能体使用大语言模型（LLM）来辅助软件开发。它们在每次用户请求前发送系统提示和工具定义来设置智能体的能力，这会消耗 token，并由 LLM 提供商计费。更高的 token 开销意味着更高的成本和更少的实际代码上下文。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://systima.ai/blog/claude-code-vs-opencode-token-overhead">Claude Code Sends 4.7x More Tokens Than OpenCode Before Reading Your Prompt | Systima Blog</a></li>
<li><a href="https://daily.dev/posts/claude-code-sends-4-7x-more-tokens-than-opencode-before-reading-your-prompt-9m02iom1z">Claude Code Sends 4.7x More Tokens Than OpenCode Before...</a></li>
<li><a href="https://www.explainx.ai/blog/claude-code-vs-opencode-token-overhead-systima-study-july-2026">Claude Code 33k vs OpenCode 7k Tokens — July 2026 - explainx.ai</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出，Claude Code 中的子智能体可能快速消耗预算，一些人怀疑 Anthropic 的商业动机导致了更高的 token 使用量。作者计划增加更深入的分析，包括定性结果。

**标签**: `#AI coding agents`, `#token efficiency`, `#LLM costs`, `#Claude Code`, `#OpenCode`

---

<a id="item-2"></a>
## [将 AI 代理迁移至 GPT-5.6：速度提升 2.2 倍，成本降低 27%](https://ploy.ai/blog/migrating-a-production-ai-agent-to-gpt-5-6) ⭐️ 8.0/10

一个生产环境中的 AI 代理被迁移至 OpenAI 的 GPT-5.6 模型，实现了 2.2 倍的速度提升和 27%的成本降低，同时任务质量保持或有所提高。 这表明升级到前沿模型能带来显著的现实性能和成本优势，鼓励更广泛地将 GPT-5.6 用于生产环境中的 AI 代理。 迁移需要在提供者边界进行模式转换，将可选属性重写为必需但可为空的属性（使用 anyOf: [T, null]），以提高模型合规性。

hackernews · brryant · Jul 12, 17:13 · [社区讨论](https://news.ycombinator.com/item?id=48882716)

**背景**: GPT-5.6 是 OpenAI 于 2026 年 7 月发布的一系列大型语言模型，包括 Luna、Terra 和 Sol 三个变体。它在编码、科学和网络安全方面取得了最先进的结果，同时使用的 token 数少于之前的模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.6">GPT-5.6</a></li>
<li><a href="https://openai.com/index/previewing-gpt-5-6-sol/">Previewing GPT-5.6 Sol: a next-generation model | OpenAI</a></li>
<li><a href="https://openai.com/index/gpt-5-6/">GPT-5.6: Frontier intelligence that scales with your ambition | OpenAI</a></li>

</ul>
</details>

**社区讨论**: 社区评论包括对 LLM 写作风格的质疑、关于模式转换的技术讨论，以及其他人观察到类似改进的验证。一些用户指出，对于他们的用例，GPT-5.6 Sol 与 Opus 4.6 基本相同。

**标签**: `#AI agents`, `#GPT-5.6`, `#performance optimization`, `#production migration`, `#cost efficiency`

---

<a id="item-3"></a>
## [谷歌研究：更智能的路线规划可减少交通拥堵](https://research.google/blog/the-power-of-collaboration-how-we-can-reduce-traffic-congestion/) ⭐️ 8.0/10

谷歌发布了一项研究，表明通过略微修改其地图路线规划算法，将交通分散到多条相似路线上，可以减少拥堵。该研究采用了为期六个月的全市范围切换实验设计。 这项研究展示了一种无需新建基础设施即可缓解城市交通拥堵的实用低成本方法，可能改善全球数百万驾驶者的通勤时间。 该实验在连续几天内交替使用修改后的算法和标准路线规划算法，结果显示拥堵显著减少，且未明显增加个人出行时间。

hackernews · raahelb · Jul 12, 15:35 · [社区讨论](https://news.ycombinator.com/item?id=48881967)

**背景**: 交通拥堵发生在需求超过道路容量时。像谷歌地图这样的路线规划算法通常为每位用户推荐最快路径，这可能会无意中将交通集中在某些道路上。将交通分散到多条相似路线（即负载均衡技术）可以缓解热点拥堵。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://scrap.io/google-maps-route-planning-technology-20-years">Google Maps Route Planning in 2026: The Technology Behind 2 Billion Daily Navigations | Scrap.io</a></li>
<li><a href="https://support.google.com/maps/thread/302082907/has-gmaps-changed-routing-algorithm-recently-getting-wierd-non-optimal-routes-lately?hl=en">Has GMaps changed routing algorithm, recently ? Getting wierd, non-optimal routes lately - Google Maps Community</a></li>

</ul>
</details>

**社区讨论**: 评论者提出了对耐久性较差道路磨损的担忧、谷歌地图自动重新规划路线功能的问题，并质疑为何不更早实施负载均衡。一些人认为，最终解决方案是更好的城市规划以减少对汽车的依赖。

**标签**: `#traffic congestion`, `#Google Maps`, `#routing algorithms`, `#urban planning`, `#experimental design`

---

<a id="item-4"></a>
## [AI 自动化可能削弱人类监督能力](https://arxiv.org/abs/2607.06377) ⭐️ 8.0/10

一篇题为《没有理解的自动化》的论文警告，随着 AI 系统自动化更多任务，人类可能失去检测和纠正 AI 错误所需的专业知识，导致未来无人理解我们所依赖的系统。 这突出了一个关键的 AI 安全风险：人类专业知识和监督能力的削弱可能使 AI 系统变得脆弱和危险，尤其是在医学、法律和工程等高风险领域。 该论文讨论了“可读性”概念——人类理解 AI 推理的能力——并认为当前的自动化趋势降低了可读性，使得人类在 AI 出错时更难干预。

hackernews · root-parent · Jul 12, 16:54 · [社区讨论](https://news.ycombinator.com/item?id=48882554)

**背景**: 随着 AI 系统能力增强，它们越来越多地被用于自动化以前需要人类专业知识的复杂任务。然而，这种自动化往往以减少人类练习和维持这些技能的机会为代价。该论文警告，如果没有刻意努力来保留人类的理解，我们就有可能创造出既强大又不透明的系统。

**社区讨论**: 社区评论对人类专业知识的丧失表达了深切担忧，一位用户指出 AI 可能会取代专家，但也会停止培养能够发现 AI 自信犯错的人。另一位建议强制 AI 通过形式化证明和执行轨迹展示其工作，以保持可读性。第三位评论者将其与奇点相类比，认为我们不是在推进 AI，而是将人类推回到理解阈值之外。

**标签**: `#AI safety`, `#automation`, `#epistemology`, `#human expertise`, `#critical thinking`

---

<a id="item-5"></a>
## [AI 发现可导致以太坊验证者崩溃的漏洞](https://www.coindesk.com/tech/2026/07/10/ai-found-an-ethereum-bug-that-could-take-validators-offline-but-humans-had-to-prove-it) ⭐️ 8.0/10

以太坊基金会宣布，协调的 AI 代理在以太坊验证者使用的 gossipsub 协议中发现了一个可远程触发的崩溃漏洞，该漏洞可能导致节点离线，直到手动重启。 这标志着 AI 辅助区块链安全的一个重要里程碑，表明 AI 可以加速关键基础设施中的漏洞发现，尽管人工验证仍然必不可少。 该漏洞被标识为 CVE-2026-34219，存在于 libp2p 实现的 gossipsub 中，可被远程利用以崩溃全节点，但在修复前没有验证者受到损害。

rss · CoinDesk · Jul 11, 12:00

**背景**: 以太坊验证者运行客户端软件，通过 gossipsub 协议传播交易和区块。该协议中的崩溃可能导致验证者失去共识参与，进而可能受到惩罚。以太坊基金会一直在测试 AI 代理，以自动化其协议代码的安全审计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/07/10/ai-found-an-ethereum-bug-that-could-take-validators-offline-but-humans-had-to-prove-it">ETH news: Ethereum Foundation says AI found bug that could take...</a></li>
<li><a href="https://blockchain.news/news/ethereum-ai-agents-protocol-security">Ethereum Tests AI Agents on Protocol Code, Finds Critical Bugs</a></li>
<li><a href="https://financefeeds.com/ethereum-foundation-tests-ai-agents-on-blockchain-software-bugs/">Ethereum Foundation Tests AI Agents on Blockchain Software Bugs</a></li>

</ul>
</details>

**标签**: `#AI`, `#Ethereum`, `#blockchain security`, `#bug discovery`, `#validators`

---

<a id="item-6"></a>
## [8 位计算机的微型模拟器，采用引脚级模拟](https://floooh.github.io/tiny8bit-preview/index.html) ⭐️ 7.0/10

发布了一个 8 位计算机的微型模拟器集合，采用模块化、引脚级模拟模型，可瞬间加载经典游戏。 该项目展示了一种新颖的模拟方法，可提高准确性和互操作性，可能影响未来的模拟器设计和复古计算保存。 这些模拟器由自包含的模块化组件构建，通过类似物理芯片引脚的薄而明确定义的接口进行通信。它们被编译为 WebAssembly，可在浏览器中瞬间加载。

hackernews · naves · Jul 12, 20:23 · [社区讨论](https://news.ycombinator.com/item?id=48884395)

**背景**: 引脚级模拟模拟芯片上每个物理引脚的精确行为，提供高精度。传统模拟器通常使用更高级别的抽象，可能会引入不准确性。模块化架构允许组件灵活地重用和组合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=dWll7HpGLOc">Z80 pin level emulation with python/tkinter - YouTube</a></li>
<li><a href="https://deepwiki.com/mamedev/mame/1.1-system-architecture">System Architecture | mamedev/mame | DeepWiki</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞了瞬间加载和引脚级模型的灵活性。一位用户指出某些游戏音量意外偏高，另一位用户请求支持 Oric 计算机。

**标签**: `#emulation`, `#retrocomputing`, `#software architecture`, `#webassembly`

---

<a id="item-7"></a>
## [HN 用户提议为 AI 生成文章添加标记](https://news.ycombinator.com/item?id=48886741) ⭐️ 7.0/10

一位 Hacker News 用户提议添加一个标记，用于标识 AI 生成的文章，让读者可以跳过而不影响排名。该建议引发了社区讨论，获得 214 分和 144 条评论，包括版主 dang 的官方回应。 这次讨论凸显了在 HN 这类重视社区信任和内容质量的平台上，AI 生成内容带来的日益严峻的挑战。其结果可能影响 HN 及类似社区如何适应生成式 AI 时代。 提议的标记不会降低文章排名，而是作为指示器，供偏好避免 AI 生成文本的用户使用。Dang 澄清说，HN 已经禁止在评论中使用 AI 生成文本，但对文章尚无类似规则，不过社区倾向于不重视此类内容。

hackernews · levkk · Jul 13, 01:24

**背景**: Hacker News 是一个专注于计算机科学和创业的社交新闻网站，以其严格的审核和社区驱动的内容策展而闻名。该网站的指南明确禁止在评论中使用 AI 生成文本，反映了对在线讨论中真实性和质量的广泛关注。

**社区讨论**: 评论显示出不同意见：一些用户支持添加标记以过滤 AI 内容，而另一些则质疑执行的可行性，或建议替代方案如标题标记或二维投票。少数人对 HN 是否愿意实施此功能表示怀疑，考虑到 YC 在 AI 领域的投资。

**标签**: `#AI-generated content`, `#Hacker News`, `#content moderation`, `#community discussion`, `#platform policy`

---

<a id="item-8"></a>
## [BIP 110 分叉截止日期临近，矿工支持率为零](https://www.coindesk.com/tech/2026/07/12/bitcoin-s-bip-110-fork-deadline-nears-with-miner-support-at-zero) ⭐️ 7.0/10

比特币的 BIP 110 是一项旨在限制交易中任意数据的软分叉提案，其强制信号窗口将于 2026 年 8 月初到来，但目前矿工支持率为零，没有主要矿池表示准备就绪。 矿工支持的缺失可能导致有争议的用户激活软分叉（UASF），可能分裂比特币网络并考验其治理模式，对生态系统的未来方向产生重大影响。 BIP 110 采用用户激活软分叉机制，仅需 55% 的节点支持即可强制执行新规则，绕过了传统上需要绝大多数矿工批准的要求；截止日期设定在 2026 年 8 月初。

rss · CoinDesk · Jul 12, 05:49

**背景**: BIP 110 于 2025 年 12 月提出，旨在暂时限制比特币交易中的任意数据（如 Ordinals 铭文），以维护其作为健全货币的用途。这是一项为期一年的软分叉，将 scriptPubKey 限制为 34 字节。该提案引发了关于比特币应保持简单还是容纳更多用例的争论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bip110.org/">BIP-110: Temporarily Limit Arbitrary Data in Bitcoin</a></li>
<li><a href="https://bips.dev/110/">BIP 110: Reduced Data Temporary Softfork - bips.dev</a></li>
<li><a href="https://www.coindesk.com/tech/2026/07/12/bitcoin-s-bip-110-fork-deadline-nears-with-miner-support-at-zero">BTC news: Bitcoin ’s BIP 110 fork deadline nears with miner support ...</a></li>

</ul>
</details>

**社区讨论**: 社区讨论两极分化：Michael Saylor 和 Adam Back 等支持者主张维护比特币的原始用途，而批评者则警告审查和效用降低。许多人认为零矿工支持表明该提案缺乏广泛共识。

**标签**: `#Bitcoin`, `#BIP 110`, `#fork`, `#miner support`, `#cryptocurrency`

---

<a id="item-9"></a>
## [Bonzo 在 Hedera 上因预言机漏洞损失 77% 的 TVL，金额达 900 万美元](https://www.coindesk.com/web3/2026/07/11/lending-protocol-bonzo-loses-77-of-value-locked-as-usd9-million-oracle-exploit-rattles-hedera) ⭐️ 7.0/10

基于 Hedera 的去中心化借贷协议 Bonzo 在一次预言机攻击中损失了 77% 的锁定总价值（TVL），金额达 900 万美元。另一个钱包借走了约 100 万美元，但自称是白帽黑客，并表示会归还资金。 此事件凸显了依赖价格预言机的 DeFi 协议存在严重漏洞，可能削弱用户对 Hedera 生态系统的信任。它强调了加强预言机安全措施的必要性，并可能促使借贷协议接受更严格的审计。 该攻击涉及价格预言机操纵，这是一种常见的攻击手段，攻击者通过人为改变资产价格来盗取资金。Bonzo 基于 Aave v2 的智能合约构建，并针对 Hedera 的原生服务进行了适配。

rss · CoinDesk · Jul 11, 18:06

**背景**: 价格预言机操纵攻击利用了智能合约估算代币价值时的漏洞，使攻击者能够通过不正确的估值盗取协议资金。Hedera 是一种使用哈希图共识的分布式账本技术，提供快速且节能的交易。Bonzo 是 Hedera 上基于流动性池的借贷协议，类似于 Aave。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Bonzo-Labs/bonzo-docs">GitHub - Bonzo-Labs/bonzo-docs: Welcome to the official Bonzo documentation repository. · GitHub</a></li>
<li><a href="https://bonzo.finance/">Bonzo Finance</a></li>
<li><a href="https://docs.bonzo.finance/hub">Bonzo Finance Overview | Bonzo Finance Documentation</a></li>
<li><a href="https://github.com/calvwang9/oracle-manipulation">GitHub - calvwang9/oracle-manipulation: Price oracle manipulation attacks in defi · GitHub</a></li>
<li><a href="https://www.chainalysis.com/blog/oracle-manipulation-attacks-rising/">Oracle Manipulation Attacks Rising: A Unique Concern for DeFi</a></li>
<li><a href="https://www.halborn.com/blog/post/what-are-price-oracle-manipulation-attacks-in-defi">What are Price Oracle Manipulation Attacks in DeFi?</a></li>
<li><a href="https://hedera.com/">Hedera is the trusted platform for building fast, secure, and compliant...</a></li>
<li><a href="https://www.okx.com/learn/what-is-hedera-token">What Is Hedera (HBAR)? | OKX</a></li>
<li><a href="https://gemwallet.com/learn/what-is-the-hedera-blockchain/">What Is The Hedera Blockchain ? | Gem Wallet</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#oracle exploit`, `#Hedera`, `#cryptocurrency`

---

<a id="item-10"></a>
## [LARP 网站讽刺创业公司收入基础设施](https://www.larp.website/) ⭐️ 6.0/10

一个名为 LARP（实景角色扮演）的讽刺网站上线，通过展示一个提供虚假收入基础设施的恶搞产品，嘲讽创业公司收入基础设施工具的泛滥。 该讽刺作品凸显了创业生态系统的荒谬之处——许多公司为其他初创企业构建工具，形成了可能不增加实际价值的循环经济，并引发了关于创业经济和风投动态的深思讨论。 该网站执行得很好，许多读者直到最后一段才确定这是个玩笑，表明这个恶搞作品非常贴近真实的创业推销。该网站在 Hacker News 上获得了 183 个点赞和 40 条评论。

hackernews · BerislavLopac · Jul 12, 16:56 · [社区讨论](https://news.ycombinator.com/item?id=48882569)

**背景**: 在创业领域，“收入基础设施”指帮助公司管理计费、订阅和收入运营的工具和服务。这类初创公司激增，且经常向其他初创公司销售，导致形成一种循环经济的看法——资金在初创公司之间流动，而没有到达最终客户。

**社区讨论**: 评论者们在意识到该网站是个玩笑后表达了有趣和释然，有人指出这个讽刺可能对目标对象来说过于隐晦。其他人讨论了创业浪费的更广泛影响，一位评论者认为多余的资金实际上通过资助工资和副项目而有益于社会。

**标签**: `#satire`, `#startup`, `#venture capital`, `#revenue infrastructure`

---

<a id="item-11"></a>
## [在分心时代重新发现深度阅读](https://substack.magazinenongrata.com/p/how-i-learned-to-read-again) ⭐️ 6.0/10

作者分享了自己在多年数字分心后重新学习深度阅读的个人经历，反思了持续注意力对长文本的丧失与恢复。 这篇文章与那些受屏幕成瘾和碎片化阅读习惯困扰的知识工作者及软件工程师产生共鸣，强调了深度阅读对批判性思维和写作的认知益处。 作者指出其阅读高峰期在十一二岁，并引用 Mortimer Adler 的观察：阅读教学很少在六年级后有所进步。文章包含社区讨论，将深度阅读与更好的思考和写作联系起来。

hackernews · georgex7 · Jul 12, 18:22 · [社区讨论](https://news.ycombinator.com/item?id=48883238)

**背景**: 深度阅读是指以专注、反思的方式阅读长而复杂的文本，而非略读或扫描数字内容。在通知不断和短媒体盛行的时代，许多人报告自己维持对书籍或长篇文章注意力的能力下降。这篇文章是更广泛文化对话的一部分，旨在重新夺回专注力和认知深度。

**社区讨论**: 评论者如 pseudonymidy 质疑区分阅读长文章和书籍的价值，而 sixtyj 引用 Paul Graham 的话，认为读者将是唯一能好好思考的人。loughnane 提到 Mortimer Adler 的《如何阅读一本书》作为解决方案，sam1r 则批评作者的父亲不重视教育。

**标签**: `#reading`, `#productivity`, `#personal-development`, `#attention`

---

<a id="item-12"></a>
## [Robinhood Chain：面向代币化股票的以太坊 L2 网络](https://decrypt.co/resources/what-robinhood-chain-ethereum-layer-2-network-tokenized-stocks) ⭐️ 6.0/10

Robinhood 宣布推出 Robinhood Chain，这是一个基于 Arbitrum 技术构建的以太坊二层网络，旨在支持代币化股票、加密应用和链上金融产品。 此举通过在可扩展的 L2 上实现代币化股票，将传统金融与 DeFi 连接起来，可能提高散户投资者的可及性和流动性。这也表明机构对链上资产代币化的兴趣日益增长。 Robinhood Chain 利用 Arbitrum 的 Optimistic Rollup 技术实现可扩展性和安全性，并专为代币化资产和链上金融而设计。目前尚未公布具体的发布日期或技术规格。

rss · Decrypt · Jul 11, 16:21

**背景**: 代币化股票是基于区块链的数字资产，代表传统股票的所有权，支持 24/7 交易和全球访问。Arbitrum 是一个领先的以太坊 L2 扩展解决方案，使用 Optimistic Rollup 在链下处理交易，同时保持以太坊的安全性。Robinhood 是一个受欢迎的零售交易平台，正通过这一 L2 计划扩展到加密和 DeFi 领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arbitrum.io/">Arbitrum - Powering the programmable economy</a></li>
<li><a href="https://docs.arbitrum.io/get-started/arbitrum-introduction">Arbitrum introduction | Arbitrum Docs</a></li>
<li><a href="https://www.gemini.com/cryptopedia/what-are-tokenized-stocks-and-how-do-they-work">What Are Tokenized Stocks and How Do They Work? | Gemini</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#Layer-2`, `#Tokenized Assets`, `#DeFi`, `#Robinhood`

---