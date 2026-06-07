---
layout: default
title: "Horizon Summary: 2026-06-07 (ZH)"
date: 2026-06-07
lang: zh
---

> From 67 items, 15 important content pieces were selected

---

1. [谷歌每月向 SpaceX 支付 9.2 亿美元获取 xAI 算力](#item-1) ⭐️ 9.0/10
2. [重新思考进程创建：超越 fork()+exec()](#item-2) ⭐️ 8.0/10
3. [Meta 确认数千 Instagram 账户因 AI 聊天机器人漏洞被黑](#item-3) ⭐️ 8.0/10
4. [Zeroserve：可用 eBPF 脚本化的零配置 Web 服务器](#item-4) ⭐️ 8.0/10
5. [Claude Code 提示注入可窃取 GitHub 凭证](#item-5) ⭐️ 8.0/10
6. [ZCash Orchard 漏洞允许不可检测的伪造](#item-6) ⭐️ 8.0/10
7. [Ntsc-rs：开源模拟电视与 VHS 伪影仿真工具](#item-7) ⭐️ 7.0/10
8. [英伟达为 Windows PC 提出强大 CPU 系统方案](#item-8) ⭐️ 7.0/10
9. [Anthropic 协助 NSA 进攻性网络行动，同时呼吁暂停 AI](#item-9) ⭐️ 7.0/10
10. [摩根士丹利通过借贷实现实物加密 ETF 转换](#item-10) ⭐️ 7.0/10
11. [OpenAI 的 Codex 智能体优先工程文章引发质疑](#item-11) ⭐️ 6.0/10
12. [美国大银行构建数字货币网络以阻止存款流失](#item-12) ⭐️ 6.0/10
13. [中本聪时代比特币钱包在 14 年后移动，涉及 2850 亿美元诉讼](#item-13) ⭐️ 6.0/10
14. [交易公司招聘潮表明 Polymarket 走向主流](#item-14) ⭐️ 6.0/10
15. [国会提出 7 项新的加密货币税收法案](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [谷歌每月向 SpaceX 支付 9.2 亿美元获取 xAI 算力](https://www.cnbc.com/2026/06/05/google-to-pay-spacex-920-million-a-month-for-xai-compute-capacity.html) ⭐️ 9.0/10

谷歌已同意每月向 SpaceX 支付 9.2 亿美元，以获取 xAI 数据中心的算力，该交易使 SpaceX 的年收入增加 110 亿美元。 这笔交易展示了 AI 基础设施市场中一种新的金融工程形式，通过收入乘数效应可能为 SpaceX 增加 1 万亿美元估值，并凸显了主要科技公司之间日益增长的相互依赖关系。 SpaceX 的估值是收入的 94 倍，谷歌持有 SpaceX 约 5%的股份，因此这笔交易可能使谷歌的持股价值增加 500 亿美元。算力可能来自 xAI 位于田纳西州孟菲斯的 Colossus 2 千兆瓦级数据中心。

hackernews · toephu2 · Jun 5, 20:06 · [社区讨论](https://news.ycombinator.com/item?id=48417490)

**背景**: xAI 是埃隆·马斯克的人工智能公司，运营着像 Colossus 2 这样的大型数据中心用于训练 AI 模型。金融工程指利用金融技术提升估值，例如利用高收入乘数。这笔交易就是一个例子，通过收入协议在不改变运营的情况下大幅提升公司估值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://newsletter.semianalysis.com/p/xais-colossus-2-first-gigawatt-datacenter">xAI's Colossus 2 - First Gigawatt Datacenter In The World, Unique RL ...</a></li>
<li><a href="https://techstartups.com/2025/10/08/elon-musks-xai-is-raising-20-billion-to-build-one-of-the-worlds-largest-ai-data-centers-with-nvidia/">Elon Musk's xAI is raising $20 billion to build one of the world's ...</a></li>

</ul>
</details>

**社区讨论**: 评论者指出这笔交易是巧妙的金融工程，有人估计它使 SpaceX 估值增加 1 万亿美元。其他人则调侃科技巨头之间的资金循环流动，一些人对复杂的公司间安排表示困惑。

**标签**: `#AI infrastructure`, `#cloud computing`, `#financial engineering`, `#SpaceX`, `#Google`

---

<a id="item-2"></a>
## [重新思考进程创建：超越 fork()+exec()](https://lwn.net/SubscriberLink/1076018/16f01bbbb8e0d1f0/) ⭐️ 8.0/10

一篇 LWN 文章探讨了传统 fork()+exec() 进程创建模型的替代方案，认为该模型已过时，并提出了 posix_spawn() 和 vfork() 等现代替代方案。 这一讨论意义重大，因为 fork()+exec() 是 Unix 的基础机制，影响性能、安全性和跨平台兼容性；转向现代 API 可以提高效率并减少系统编程中的错误。 文章指出 fork() 开销大，因为它复制整个进程状态，而 exec() 通常会立即丢弃这些状态；写时复制（copy-on-write）缓解了这一问题，但并未消除开销。像 posix_spawn() 这样的现代替代方案完全避免了复制。

hackernews · jwilk · Jun 6, 14:34 · [社区讨论](https://news.ycombinator.com/item?id=48425528)

**背景**: 在类 Unix 操作系统中，fork() 通过复制父进程来创建子进程，exec() 则用新程序替换子进程的内存。这种两步模型是为 1970 年代的硬件设计的，因其复杂性和低效而受到批评。现代操作系统提供了 spawn 类 API，通过一次调用创建进程，更简单且通常更快。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.baeldung.com/linux/fork-vfork-exec-clone">The Difference Between fork (), vfork (), exec () and clone () Process Creation in OS: Fork, Exec and Process Spawning ... What is the Closest Equivalent to fork() in Windows? How to ... The difference between fork (), vfork (), exec () and clone () Linux 2026: Modern Process Creation Techniques Replacing fork ... The Difference Between Fork(), Vfork(), Exec(), and Clone ... New alternative for fork ()/exec () and posix_spawn ...</a></li>
<li><a href="https://codelucky.com/process-creation-fork-exec/">Process Creation in OS: Fork, Exec and Process Spawning ...</a></li>
<li><a href="https://www.codegenes.net/blog/what-is-the-closest-thing-windows-has-to-fork/">What is the Closest Equivalent to fork() in Windows? How to ...</a></li>

</ul>
</details>

**社区讨论**: 评论者引用了有影响力的论文《A fork() in the road》，并分享了实践经验：有人指出 fork 后需要关闭文件描述符会导致 bug，另有人则认为 fork 的优雅之处在于能使用现有 API 进行配置。讨论还强调写时复制使 fork 的成本低于通常的假设。

**标签**: `#operating systems`, `#process creation`, `#fork`, `#exec`, `#systems programming`

---

<a id="item-3"></a>
## [Meta 确认数千 Instagram 账户因 AI 聊天机器人漏洞被黑](https://this.weekinsecurity.com/meta-confirms-thousands-of-instagram-accounts-were-hacked-by-abusing-its-ai-chatbot/) ⭐️ 8.0/10

Meta 确认，黑客利用其 AI 聊天机器人的密码重置流程漏洞，入侵了数千个 Instagram 账户，影响超过 2 万名用户。攻击始于 2026 年 4 月 17 日左右，持续至 6 月初。 此事件凸显了将 AI 聊天机器人用于密码重置等敏感账户管理功能的安全风险。它强调了在 AI 驱动的客户支持系统中需要强大的验证机制。 黑客诱骗 AI 聊天机器人向受害者账户添加新邮箱地址，然后重置密码，将原主人锁定。Meta 表示，漏洞出现在一个单独的代码路径中，系统未能验证提供的邮箱是否与账户邮箱匹配。

hackernews · speckx · Jun 6, 18:35 · [社区讨论](https://news.ycombinator.com/item?id=48427643)

**背景**: Meta 于 2026 年 3 月扩展了其 Facebook 和 Instagram 的 AI 客户支持，允许 AI 处理密码重置等核心账户管理功能。此事件是首批利用 AI 聊天机器人权限进行客户支持的重大安全漏洞之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chosun.com/english/industry-en/2026/06/02/G6WOPNGUNFC3POYK3VXNMRW7P4/">Obama's Instagram Hacked via Meta's AI Chatbot Flaw</a></li>
<li><a href="https://www.nospinnetwork.com/meta-ai-chatbot-exploit-led-to-instagram-account-hijackings/">Instagram AI chatbot hack</a></li>
<li><a href="https://otontechnology.com/meta-ai-chatbot-instagram-account-hijack-exploit/">Meta AI Chatbot Tricked Into Hijacking Instagram Logins</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 Meta 声称该工具“正常工作”表示怀疑，并批评将 AI 用于客户支持。用户还指出，Meta 的自动化系统禁用合法账户，而黑客却利用聊天机器人，这具有讽刺意味。

**标签**: `#security`, `#AI`, `#Meta`, `#Instagram`, `#hacking`

---

<a id="item-4"></a>
## [Zeroserve：可用 eBPF 脚本化的零配置 Web 服务器](https://su3.io/posts/introducing-zeroserve) ⭐️ 8.0/10

Zeroserve 是一款新的零配置 Web 服务器，允许用户用 C 语言编写 eBPF 程序来处理 HTTP 请求路由和响应生成，为传统声明式配置提供了一种新颖的替代方案。 这种方法通过 eBPF 将请求处理逻辑移至内核，可能显著提升 Web 服务器的性能和灵活性，相比 nginx 和 Caddy 等用户态服务器有望降低开销。 Zeroserve 用 Rust 编写，目前是单线程的，但通过 SO_REUSEPORT 实现多进程扩展。在静态文件服务基准测试中已超越 nginx，但缺少成熟服务器的许多功能。

hackernews · losfair · Jun 6, 14:59 · [社区讨论](https://news.ycombinator.com/item?id=48425723)

**背景**: eBPF（扩展的伯克利数据包过滤器）是一种 Linux 内核技术，允许在内核空间安全地执行用户定义的程序，常用于网络、可观测性和安全领域。Zeroserve 利用 eBPF 运行用户提供的 C 程序来处理请求，取代传统配置文件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/EBPF">EBPF</a></li>
<li><a href="https://ebpf.io/">eBPF - Introduction, Tutorials & Community Resources</a></li>

</ul>
</details>

**社区讨论**: 评论者对这一概念表示兴趣，但担忧安全性以及需要基于 Rust 的 eBPF 脚本。一些人将其性能与 nginx 和 Caddy 进行了有利比较，而另一些人则质疑内核级请求处理的实用性。

**标签**: `#eBPF`, `#web server`, `#Rust`, `#performance`, `#networking`

---

<a id="item-5"></a>
## [Claude Code 提示注入可窃取 GitHub 凭证](https://decrypt.co/370238/claude-code-vulnerability-attackers-steal-credentials-github-microsoft) ⭐️ 8.0/10

微软研究人员发现，提示注入攻击可利用 Anthropic 的 Claude Code AI 编码代理窃取存储在 GitHub CI/CD 流水线中的凭证。 这一漏洞凸显了 AI 辅助开发工具中的新型攻击向量，可能危及使用 AI 编码代理的数百万开发者和组织的敏感凭证。 该攻击利用提示注入操纵 Claude Code 访问 GitHub Actions 中的环境变量或密钥，绕过常规安全控制。微软已向 Anthropic 报告此问题，预计将发布修复。

rss · Decrypt · Jun 6, 18:08

**背景**: 提示注入是一种网络安全利用方式，恶意输入会导致 AI 模型产生意外行为。Claude Code 是一种代理式编码工具，可以读取代码库、编辑文件和运行命令。像 Claude Code 这样的 AI 编码代理越来越多地集成到开发流水线中，使其成为凭证窃取的诱人目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>
<li><a href="https://code.claude.com/docs/en/overview">Overview - Claude Code Docs</a></li>
<li><a href="https://cheatsheetseries.owasp.org/cheatsheets/AI_Agent_Security_Cheat_Sheet.html">AI Agent Security - OWASP Cheat Sheet Series</a></li>

</ul>
</details>

**社区讨论**: 输入中未提供社区评论。

**标签**: `#AI security`, `#prompt injection`, `#Claude Code`, `#GitHub`, `#vulnerability`

---

<a id="item-6"></a>
## [ZCash Orchard 漏洞允许不可检测的伪造](https://decrypt.co/370112/morning-minute-massive-zcash-exploit-found-by-claude-extent-unknown) ⭐️ 8.0/10

一名受雇黑客使用 Claude 发现了 ZCash Orchard 隐私池中的一个严重漏洞，该漏洞允许在四年内不可检测地伪造 ZEC 代币。 此漏洞破坏了用户对 ZCash 核心隐私功能的信任，并凸显了隐私币的权衡问题，可能影响用户信心及更广泛的加密货币生态系统。 该漏洞在 Orchard 隐私池中存在四年，可能实现无限代币铸造而不被检测；披露后 ZCash 价格下跌近 50%。

rss · Decrypt · Jun 5, 12:49

**背景**: ZCash 是一种注重隐私的加密货币，使用隐私池隐藏交易细节。Orchard 池是其最新的隐私协议。为防止类似漏洞，正在考虑采用形式化验证方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bitmex.com/blog/zec-crash-2026">Why Zcash Crashed Nearly 50% in 48 Hours | BitMEX Blog</a></li>
<li><a href="https://www.tftc.io/zcash-orchard-vulnerability-privacy-inflation-bug/">Zcash Orchard Bug: Three People Froze Privacy Pool | TFTC</a></li>
<li><a href="https://cointelegraph.com/news/zcash-new-shielded-pool-orchard-counterfeiting-bug">Zcash weighs new shielded pool after counterfeiting flaw</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#security`, `#ZCash`, `#exploit`, `#blockchain`

---

<a id="item-7"></a>
## [Ntsc-rs：开源模拟电视与 VHS 伪影仿真工具](https://ntsc.rs/) ⭐️ 7.0/10

Ntsc-rs 是一款免费开源视频特效工具，能够实时精确模拟模拟电视和 VHS 伪影，支持高分辨率，并可作为视频编辑器的插件使用。 该工具使创作者能够实现真实的复古视频美学，无需依赖简单的颜色查找表，为艺术和怀旧目的保留了模拟介质的细微缺陷。 Ntsc-rs 使用模拟 NTSC 传输和 VHS 编码过程的算法，而非表面叠加，并支持 JSON 配置文件以实现预设共享。

hackernews · gregsadetsky · Jun 6, 19:17 · [社区讨论](https://news.ycombinator.com/item?id=48428025)

**背景**: NTSC（国家电视系统委员会）是第一个美国模拟电视标准，于 1941 年采用，后于 1953 年更新以支持彩色。模拟电视和 VHS 录像容易产生颜色渗色、重影和噪点等伪影，这些现在常被仿真用于复古效果。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ntsc.rs/">ntsc-rs - an accurate VHS video effect</a></li>
<li><a href="https://en.wikipedia.org/wiki/NTSC">NTSC</a></li>
<li><a href="https://news.ycombinator.com/item?id=48428025">Ntsc-rs – open-source video emulation of analog TV and VHS artifacts | Hacker News</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞其技术深度，有人指出缺少垂直振荡器漂移和 PAL/Hanover 条等特性。一位用户分享了 OpenEmulator 中 NTSC 仿真的详细分析，另一位则提到了自己更简单的 LED 仿真项目。

**标签**: `#video emulation`, `#analog TV`, `#signal processing`, `#retro computing`, `#open source`

---

<a id="item-8"></a>
## [英伟达为 Windows PC 提出强大 CPU 系统方案](https://twitter.com/lemire/status/2062880075117113739) ⭐️ 7.0/10

英伟达最近提出了一种面向 Windows PC 的新 CPU 系统方案，可能基于其 Grace CPU 架构，采用统一内存和高性能 Arm 核心，相关讨论出现在一条推文和社区帖子中。 该方案可能挑战 PC 中传统的 CPU/GPU 架构，通过统一内存提升游戏和本地 AI 工作负载的性能，并可能影响未来 PC 硬件设计。 据报道，该系统采用 20 个 Armv9 核心的 Grace CPU 和 Blackwell GPU，共享统一内存池，但目前仍属推测，并非确认产品。社区评论质疑其游戏性能与独立 GPU 相比如何。

hackernews · tosh · Jun 6, 12:52 · [社区讨论](https://news.ycombinator.com/item?id=48424605)

**背景**: 统一内存允许 CPU 和 GPU 共享同一物理内存池，无需在独立内存之间复制数据，从而降低延迟和功耗。苹果 M 系列芯片在消费设备中普及了这种架构。英伟达的 Grace CPU 最初为数据中心设计，是一款基于 Arm 的处理器，可通过 NVLink-C2C 互连与英伟达 GPU 配对。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/data-center/grace-cpu/">NVIDIA Grace CPU and Arm Architecture | NVIDIA</a></li>
<li><a href="https://prism.sustainability-directory.com/learn/what-are-the-benefits-of-unified-memory-architectures/">What Are the Benefits of Unified Memory Architectures? → Learn</a></li>

</ul>
</details>

**社区讨论**: 评论者意见不一：一些人认为统一内存对 AI 和游戏是颠覆性的，而另一些人则怀疑其在游戏方面相比独立 GPU 的优势。有用户指出，高通骁龙 X2 Elite 已在当前笔记本电脑中提供类似功能。

**标签**: `#Nvidia`, `#CPU`, `#GPU`, `#unified memory`, `#AI`

---

<a id="item-9"></a>
## [Anthropic 协助 NSA 进攻性网络行动，同时呼吁暂停 AI](https://decrypt.co/370207/anthropic-helping-nsa-hack-china-also-wants-everyone-pause-ai) ⭐️ 7.0/10

Anthropic 将工程师派驻 NSA，协助使用其 Claude Mythos 模型进行进攻性网络行动，同时发布报告警告 AI 可能很快实现无需人类参与的递归自我改进。 这种双重角色暴露了 Anthropic 在 AI 安全倡导中的矛盾，可能削弱其可信度，并影响关于 AI 监管以及 AI 在国家安全中伦理问题的辩论。 NSA 正在使用 Anthropic 专注于网络安全的 Mythos 模型进行进攻性网络行动，并有六名 Anthropic 工程师派驻该机构。同时，Anthropic 最近的报告详细介绍了递归自我改进的进展，即 AI 系统在最少人类监督下自我开发。

rss · Decrypt · Jun 5, 19:18

**背景**: Anthropic 是一家以 Claude 模型闻名的 AI 安全公司。NSA 是美国负责信号情报和网络安全的情报机构。进攻性网络行动涉及入侵对手系统，而递归自我改进是指 AI 系统能够自主提升自身能力，可能导致超出人类控制的快速进步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/nsa-using-clause-mythos-for-offensive-cyber-operations-report-claims-says-half-a-dozen-anthropic-engineers-embedded-inside-the-agency">NSA using Claude Mythos for ' offensive cyber operations ,' report...</a></li>
<li><a href="https://www.anthropic.com/institute/recursive-self-improvement">When AI builds itself \ Anthropic</a></li>
<li><a href="https://fortune.com/2026/06/05/anthropic-ai-pause-development-recursive-self-improvement/">Anthropic warns AI could soon build itself without human ...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#cybersecurity`, `#ethics`, `#Anthropic`, `#NSA`

---

<a id="item-10"></a>
## [摩根士丹利通过借贷实现实物加密 ETF 转换](https://www.theblock.co/post/403825/morgan-stanley-clients-lend-bitcoin-in-kind-spot-crypto-etf-conversions?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

摩根士丹利财富管理与 Galaxy Digital 合作，允许符合条件的客户借出比特币及其他加密资产，以换取实物现货加密 ETF 份额。 这标志着机构采用加密货币的重要一步，顶级银行推动实物 ETF 转换，可能为大型投资者提高流动性和税务效率。 实物创建流程允许授权参与者将基础加密资产直接交付给 ETF 发行方以换取新份额，从而绕过现金交易。

rss · The Block · Jun 5, 15:06

**背景**: 实物创建和赎回是传统 ETF 的标准机制，但直到最近才被 SEC 允许用于美国现货加密 ETF。此次合作利用 Galaxy Digital 在加密市场的专业知识，为摩根士丹利的富裕客户提供该服务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://theccpress.com/morgan-stanley-clients-lend-bitcoin-in-kind-spot-crypto-etf-conversions/">Morgan Stanley to Let Clients Lend Bitcoin for Spot Crypto ...</a></li>
<li><a href="https://coinunited.io/en/pulse/2026-06-05/morgan-stanley-launches-msbt-spot-bitcoin-etf-what-in-kind-conversion-access-means-for-btc-leverage-traders">Morgan Stanley Launches MSBT Spot Bitcoin ETF — What In-Kind ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#finance`, `#institutional adoption`, `#ETF`, `#bitcoin`

---

<a id="item-11"></a>
## [OpenAI 的 Codex 智能体优先工程文章引发质疑](https://openai.com/index/harness-engineering/) ⭐️ 6.0/10

OpenAI 发布了一篇博客文章，描述了三名工程师在五个月内使用 Codex 以智能体优先的开发工作流生成了百万行代码，并合并了 1500 个拉取请求。 这个案例研究展示了 AI 智能体在软件工程中的实际应用，但由于缺乏具体细节且强调代码量而非质量而受到批评，凸显了 AI 炒作与实际工程价值之间的差距。 该仓库包含应用逻辑、基础设施、工具、文档和开发者工具，所有代码都针对 Codex 的可读性而非人类可读性进行了优化。团队平均每位工程师每天提交 3.5 个拉取请求。

hackernews · pramodbiligiri · Jun 5, 18:20 · [社区讨论](https://news.ycombinator.com/item?id=48416264)

**背景**: 智能体优先开发是一种范式，其中 AI 智能体是编写代码的主要执行者，人类提供指导和审查。Codex 是 OpenAI 的编码智能体，可以根据自然语言描述生成代码。这篇文章是 2026 年“智能体工程”更广泛趋势的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/harness-engineering/">Harness engineering: leveraging Codex in an agent-first world</a></li>
<li><a href="https://www.shiplight.ai/blog/agent-first-development">What Is Agent-First Development? A Guide for Engineering ...</a></li>
<li><a href="https://openai.com/codex/">Codex | AI Coding Partner from OpenAI | OpenAI</a></li>

</ul>
</details>

**社区讨论**: 社区评论非常批评，用户认为文章模糊且充满炒作。批评者认为强调代码行数作为指标是误导性的，他们要求提供具体的操作指南和演示，而不是空洞的声明。

**标签**: `#AI-assisted development`, `#Codex`, `#agent-first engineering`, `#software engineering`

---

<a id="item-12"></a>
## [美国大银行构建数字货币网络以阻止存款流失](https://www.coindesk.com/business/2026/06/06/america-s-largest-banks-are-building-a-new-digital-currency-network-to-stop-a-massive-deposit-drain) ⭐️ 6.0/10

包括摩根大通、花旗和美国银行在内的美国大型银行正在合作开发基于区块链的数字货币网络，使用代币化存款，计划于 2027 年推出。 此举旨在与稳定币竞争，防止五年内存款流失导致银行收益减少 3-5%，可能重塑区块链网络上的资金流动方式。 该系统将使用代币化存款实现全天候即时银行间结算，并保持在受监管的银行轨道内，而非使用去中心化加密货币。

rss · CoinDesk · Jun 6, 15:59

**背景**: 稳定币（如 USDC 和 USDT）快速增长，提供了基于区块链的现金替代方案，绕过了传统银行。这导致银行存款外流，威胁其资金基础。代币化存款是银行在区块链上发行的存款数字表示，结合了区块链效率与监管合规的优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://invezz.com/news/2026/06/05/jpmorgan-citi-and-bofa-plan-blockchain-deposit-network-for-2027/">JPMorgan, Citi and BofA plan blockchain deposit network for 2027</a></li>
<li><a href="https://cryptonews.net/news/finance/32976776/">America’s largest banks are building a new digital currency network to stop a massive deposit drain</a></li>
<li><a href="https://coinspectator.com/other/2026/06/06/americas-largest-banks-are-building-a-new-digital-currency-network-to-stop-a-massive-deposit-drain/">America’s largest banks are building a new digital currency network to stop a massive deposit drain – CoinSpectator – Real-time Cryptocurrency News</a></li>

</ul>
</details>

**标签**: `#digital currency`, `#banking`, `#blockchain`, `#finance`

---

<a id="item-13"></a>
## [中本聪时代比特币钱包在 14 年后移动，涉及 2850 亿美元诉讼](https://www.coindesk.com/markets/2026/06/06/satoshi-era-bitcoin-at-center-of-usd285-billion-lawsuit-moves-after-14-years) ⭐️ 6.0/10

一个自 2011 年 3 月以来一直休眠的比特币地址（1LwWt）本周移动了 35.55 BTC，这是所罗门兄弟公司提起的 2850 亿美元诉讼中，被告首次在链上作出回应。 此次移动可能为声称拥有 380 万 BTC 的诉讼提供证据，可能为休眠加密货币持有量的法律索赔开创先例。 1LwWt 地址于 2025 年 7 月通过比特币的 OP_RETURN 字段收到法律通知，要求其在 2025 年 11 月 5 日前证明所有权。该钱包将币转移至币安，暗示可能出售。

rss · CoinDesk · Jun 6, 13:30

**背景**: “中本聪时代”指的是 2009 年至 2011 年期间，比特币的匿名创造者中本聪活跃的时期。来自那个时代的休眠钱包偶尔会变得活跃，常常引发关于中本聪身份或遗产的猜测。所罗门兄弟公司的诉讼声称拥有大量早期开采的比特币的所有权。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/markets/2026/06/06/satoshi-era-bitcoin-at-center-of-usd285-billion-lawsuit-moves-after-14-years">Satoshi-era BTC at center of $285 billion bitcoin lawsuit ...</a></li>
<li><a href="https://www.tradingview.com/news/cointelegraph:cda82ef5f094b:0-satoshi-era-bitcoin-wallet-wakes-up-after-14-years-sends-50-btc-to-binance/">Satoshi era Bitcoin wallet wakes up after 14... — TradingView News</a></li>
<li><a href="https://www.binance.com/en/square/post/06-07-2026-satoshi-era-bitcoin-at-center-of-285b-lawsuit-moves-after-14-years-331318688076817">Satoshi-era bitcoin at center of $285B lawsuit ... - Binance</a></li>

</ul>
</details>

**标签**: `#bitcoin`, `#cryptocurrency`, `#lawsuit`, `#satoshi-era`

---

<a id="item-14"></a>
## [交易公司招聘潮表明 Polymarket 走向主流](https://www.coindesk.com/business/2026/06/06/a-massive-hiring-wave-reveals-trading-firms-are-no-longer-viewing-polymarket-as-a-niche-betting-tool) ⭐️ 6.0/10

交易公司正掀起一波大规模招聘潮，专门招聘与 Polymarket 相关的职位，表明它们不再将该平台视为小众博彩工具，而是视为一种严肃的金融工具。 这一转变可能会推动预测市场获得更大的流动性、机构参与和监管关注，从而可能改变金融市场对不确定事件进行定价和对冲的方式。 Polymarket 是一个基于加密货币的预测市场，用户可以对选举和体育等事件交易二元期权；0.1%的账户赚取了 67%的利润，而超过 70%的用户亏损。

rss · CoinDesk · Jun 6, 13:00

**背景**: 预测市场允许交易未来事件的结果，价格反映人群的概率估计。Polymarket 于 2020 年推出，是最大的此类平台，但已在一些国家面临监管禁令，并因内幕交易和虚假信息而受到批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prediction_market">Prediction market</a></li>

</ul>
</details>

**标签**: `#Polymarket`, `#prediction markets`, `#crypto`, `#trading firms`, `#hiring`

---

<a id="item-15"></a>
## [国会提出 7 项新的加密货币税收法案](https://decrypt.co/370197/congress-7-crypto-tax-bills) ⭐️ 6.0/10

国会提出了七项新的加密货币税收法案，这是首批由国会领导层审议的法案，将于周二在众议院听证会上讨论。 这些法案可能显著影响美国加密货币的征税方式，影响区块链开发者、金融科技公司和个人投资者。它们标志着向正式化加密货币税收政策迈出的重要一步。 这些法案是首批提交国会领导层审议的加密货币税收立法，表明政治关注度提高。众议院听证会将为辩论和可能的修正提供平台。

rss · Decrypt · Jun 5, 18:13

**背景**: 加密货币税收是一个复杂的领域，因为比特币和以太坊等数字资产在税收上被视为财产，这意味着每笔交易都可能触发资本收益或损失。美国一直在努力澄清加密货币的税收规则，IRS 发布了指导并要求对某些交易进行报告。这些法案旨在解决漏洞并提供更清晰的框架。

**标签**: `#cryptocurrency`, `#tax`, `#regulation`, `#blockchain`, `#policy`

---