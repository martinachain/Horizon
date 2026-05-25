---
layout: default
title: "Horizon Summary: 2026-05-25 (ZH)"
date: 2026-05-25
lang: zh
---

> From 34 items, 16 important content pieces were selected

---

1. [翼面微粗糙度可减阻，推翻光滑表面教条](#item-1) ⭐️ 9.0/10
2. [Hotz 称 AI 编程陷入“永恒九月”](#item-2) ⭐️ 8.0/10
3. [内存占 AI 芯片成本三分之二](#item-3) ⭐️ 8.0/10
4. [约束衰减：LLM 智能体在后端代码生成中的脆弱性](#item-4) ⭐️ 8.0/10
5. [微软开源已知最早的 DOS 源代码](#item-5) ⭐️ 8.0/10
6. [专家警告：AI 加速量子威胁，加密货币面临风险](#item-6) ⭐️ 8.0/10
7. [StablR 的 EURR 和 USDR 因 1350 万美元多签漏洞脱钩](#item-7) ⭐️ 8.0/10
8. [Audiomass：免费开源的多轨网页音频编辑器](#item-8) ⭐️ 7.0/10
9. [DeepSeek Reasonix：高缓存原生编码代理](#item-9) ⭐️ 7.0/10
10. [从 Go 迁移到 Rust 的指南引发热议](#item-10) ⭐️ 7.0/10
11. [诈骗者滥用微软内部账户发送垃圾邮件](#item-11) ⭐️ 7.0/10
12. [纽约时报：CFTC 清除反对与特朗普有关联的加密公司的工作人员](#item-12) ⭐️ 7.0/10
13. [《掌握 Dyalog APL》现以 Jupyter 笔记本形式发布](#item-13) ⭐️ 6.0/10
14. [Greg Brockman 接受《知识项目》播客采访](#item-14) ⭐️ 6.0/10
15. [加密支付轨道成为 AI 代理默认支付层](#item-15) ⭐️ 6.0/10
16. [Firefox Nova 重新设计包含 AI 关闭开关](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [翼面微粗糙度可减阻，推翻光滑表面教条](https://www.wired.com/story/a-fundamental-principle-of-aeronautical-engineering-has-been-overturned/) ⭐️ 9.0/10

一项新研究表明，在翼型表面施加微粗糙度可以降低空气阻力，推翻了长期以来认为表面越光滑阻力越小的观点。 这一发现可能通过一种简单、低成本的减阻技术，显著提高飞机、汽车和高速列车的燃油效率。 研究发现，边界层过渡区的微粗糙度改善了阻力系数，但整个翼型的净改进幅度尚未量化。

hackernews · littlexsparkee · May 24, 19:10 · [社区讨论](https://news.ycombinator.com/item?id=48260117)

**背景**: 空气阻力是高速行驶的主要障碍，几十年来工程师们认为光滑表面能最小化阻力。这一原则指导了飞机机翼、汽车车身和火车车头的设计。新研究挑战了这一假设，表明可控粗糙度实际上可以减阻，类似于高尔夫球凹坑通过促进湍流来减阻。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sciencedirect.com/science/article/abs/pii/S2214785322007313">Effect of surface roughness on aerodynamic performance of the wing with NACA 4412 airfoil at Reynolds number 1.7 × 105 - ScienceDirect</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，竞技帆船运动员早已在水下表面使用细砂纸以减少摩擦，质疑为何翼型领域此前未知。有人提到高尔夫球凹坑的类比。其他人则关心实际净改进幅度以及通过喷砂改造现有飞机的可行性。

**标签**: `#aeronautical engineering`, `#aerodynamics`, `#drag reduction`, `#fluid dynamics`, `#engineering breakthrough`

---

<a id="item-2"></a>
## [Hotz 称 AI 编程陷入“永恒九月”](https://geohot.github.io//blog/jekyll/update/2026/05/24/the-eternal-sloptember.html) ⭐️ 8.0/10

George Hotz 发表博客文章，认为 AI 编程助手陷入了“永恒九月”式的渐进改进，无法处理真正新颖或复杂的软件任务。 这一批评挑战了当前围绕 AI 编程工具的炒作，表明基于 LLM 的助手仅限于重复现有解决方案，无法在创新问题上取代人类的创造力。 Hotz 将 AI 编程助手比作以英语为输入的编译器，认为英语在描述程序时不够精确且具有非确定性。他认为这些工具的表面价值恰恰反映了现有编程实践的糟糕程度。

hackernews · razin · May 25, 03:47 · [社区讨论](https://news.ycombinator.com/item?id=48263238)

**背景**: GitHub Copilot 和 Cursor 等 AI 编程助手使用大语言模型从自然语言提示生成代码。它们在自动化重复性任务方面变得流行，但批评者认为它们缺乏推理新颖架构或复杂系统设计的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://geohot.spicytakes.org/post/2025-09-12-ai-coding">AI Coding - George Hotz</a></li>
<li><a href="https://digg.com/ai/19volbvw">George Hotz says AI coding agents bypass problem ... - Digg</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍同意 Hotz 的判断，一些人指出 AI 最好被视为对现有知识的搜索而非创造性问题解决者。其他人则争论增加 token 预算或使用自动研究循环是否最终能克服这些限制。

**标签**: `#AI`, `#programming`, `#LLMs`, `#software engineering`

---

<a id="item-3"></a>
## [内存占 AI 芯片成本三分之二](https://epoch.ai/data-insights/ai-chip-component-cost-shares) ⭐️ 8.0/10

Epoch AI 报告显示，内存现在占 AI 芯片组件成本的近三分之二（63%），高于 2024 年第一季度的 52%，原因是 DRAM 供需失衡。 这一变化凸显了内存成为 AI 硬件的主要成本驱动因素，对推理和训练成本有影响，并表明 DRAM 供应缓解可能大幅降低 AI 系统总成本。 高带宽内存（HBM）是主要贡献者，逻辑芯片不再是主导成本组件。据多个行业消息来源，DRAM 供需失衡预计至少持续到 2028 年。

hackernews · intelkishan · May 24, 16:31 · [社区讨论](https://news.ycombinator.com/item?id=48258684)

**背景**: AI 加速器（如 GPU）需要大量高带宽内存（HBM）来向计算核心提供数据。DRAM 制造产能未能跟上 AI 需求的激增，导致价格上涨和供应限制，影响从数据中心到消费电子产品的各个领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://epoch.ai/data-insights/ai-chip-component-cost-shares">AI Chip Component Costs: Memory at 63% | Epoch AI</a></li>
<li><a href="https://www.astutegroup.com/news/memory-shortages/memory-supply-constraints-stretch-toward-2030-as-ai-demand-reshapes-dram-production/">Memory Supply Constraints Stretch Toward 2030 as AI Demand Reshapes DRAM Production - Astute Group</a></li>
<li><a href="https://finance.biggo.com/news/202604211251_DRAM_Shortage_to_Last_Years_Due_to_AI_Demand">DRAM Shortage to Persist Until 2028, With AI Demand Consuming 40% of Global Supply — BigGo Finance</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，如果 DRAM 供应跟上，AI 推理和训练成本可能实现约 3 倍的硬件成本降低，但有人担心内存容量增长（每年 20-25%）可能不足以满足需求。其他人则哀叹 PC 爱好者和游戏玩家面临高 RAM 价格的影响。

**标签**: `#AI hardware`, `#memory`, `#DRAM`, `#cost analysis`, `#semiconductors`

---

<a id="item-4"></a>
## [约束衰减：LLM 智能体在后端代码生成中的脆弱性](https://arxiv.org/abs/2605.06445) ⭐️ 8.0/10

一项新的系统性研究揭示了 LLM 智能体存在“约束衰减”现象——随着架构约束的累积，其性能显著下降，使其在生产级后端代码生成中不可靠。 这一发现挑战了 LLM 智能体已准备好用于生产级软件开发的假设，凸显了无约束原型开发与真实后端工程之间的关键差距。 该研究在 100 个后端任务上评估了 10 种语言模型和 8 种 Web 框架，发现随着约束增加，能力较强的智能体正确率平均下降 30 个百分点。

hackernews · wek · May 24, 12:55 · [社区讨论](https://news.ycombinator.com/item?id=48256912)

**背景**: LLM 智能体是基于自然语言提示自主生成代码的 AI 系统。虽然它们在原型设计等开放式任务中表现出色，但生产级后端代码需要严格遵守架构规则、数据库模式和其他非功能约束，而现有基准测试往往忽略这些约束。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2605.06445">Constraint Decay: The Fragility of LLM Agents in Backend Code Generation</a></li>
<li><a href="https://news.ycombinator.com/item?id=48256912">Constraint Decay: The Fragility of LLM Agents in Back End Code Generation</a></li>
<li><a href="https://byteiota.com/llm-agent-constraint-decay-backend-code/">LLM Agent Constraint Decay: Why Real Backends Break AI Code</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认同这一发现，一些人分享了类似的个人经验。一位用户指出，逐步而非一次性加入约束会有所帮助；另一位则指出该研究因成本原因未测试前沿模型的局限性。

**标签**: `#LLM`, `#code generation`, `#software engineering`, `#AI reliability`, `#backend development`

---

<a id="item-5"></a>
## [微软开源已知最早的 DOS 源代码](https://arstechnica.com/gadgets/2026/04/microsoft-open-sources-the-earliest-dos-source-code-discovered-to-date/) ⭐️ 8.0/10

微软开源了已知最早的 MS-DOS 源代码，该代码由 Yufeng Gao 和 Rich Cini 领导的保存团队从纸质打印件中恢复。 此次发布为理解开启个人电脑革命的操作系统起源提供了前所未有的视角，也彰显了微软对保护计算历史的承诺。 源代码是通过 OCR 从几十年前的纸质打印件转录而来，OCR 因打印质量不佳而困难重重，随后由 DOS 反汇编小组手动验证。

hackernews · DamnInteresting · May 24, 01:21 · [社区讨论](https://news.ycombinator.com/item?id=48253386)

**背景**: MS-DOS 是微软在 1981 年授权给 IBM 用于原始 IBM PC 的操作系统。早期版本的源代码因从未以数字形式存储而长期被认为已丢失。此次恢复工作涉及对原始开发者 Tim Paterson 提供的纸质打印件进行扫描和转录。

**社区讨论**: 评论者对微软表示感谢，有人指出同时开源的早期 BASIC 代码同样重要。其他人惊叹于早期软件的简洁，还有用户成功在 DOSBox 中运行了该代码。

**标签**: `#Microsoft`, `#DOS`, `#open source`, `#history`, `#preservation`

---

<a id="item-6"></a>
## [专家警告：AI 加速量子威胁，加密货币面临风险](https://www.coindesk.com/tech/2026/05/24/ai-is-speeding-up-the-quantum-threat-to-crypto-security-experts-warn) ⭐️ 8.0/10

安全专家警告，人工智能正在加速量子计算机破解当前加密系统的时间表，对加密货币和数据安全构成紧迫威胁。 这一进展可能迫使业界更早迁移到后量子密码学，影响区块链网络、金融交易以及所有加密通信的安全性。 Shor 算法能够高效分解大整数和求解离散对数，是对公钥密码学的主要量子威胁；AI 可能帮助优化量子纠错或算法实现，从而减少所需的量子比特数量。

rss · CoinDesk · May 24, 14:00

**背景**: 当前的公钥密码学依赖于分解大数或求解离散对数的难度，而运行 Shor 算法的量子计算机可以破解这些难题。后量子密码学（PQC）旨在开发能够抵抗量子攻击的算法，NIST 已经发布了首批标准。然而，足够强大的量子计算机出现的时间表一直不确定，估计范围在 10 到 20 年之间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography</a></li>
<li><a href="https://en.wikipedia.org/wiki/Shor's_algorithm">Shor's algorithm</a></li>
<li><a href="https://www.justsecurity.org/113733/quantum-computing-crytopography/">Military Response: Quantum Computing Threat to Cryptography</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#cryptography`, `#AI`, `#cybersecurity`, `#blockchain`

---

<a id="item-7"></a>
## [StablR 的 EURR 和 USDR 因 1350 万美元多签漏洞脱钩](https://www.theblock.co/post/402429/stablrs-eurr-and-usdr-depeg-after-attacker-mints-13-5-million-in-unbacked-tokens-through-multisig-exploit?utm_source=rss&utm_medium=rss) ⭐️ 8.0/10

攻击者利用多签漏洞铸造了 1350 万美元的无抵押代币，导致 StablR 的 EURR 和 USDR 稳定币脱钩。攻击者在去中心化交易所抛售了约 1040 万美元面值的代币后，EURR 跌至 0.85 美元，USDR 最低跌至 0.40 美元。 此事件凸显了稳定币发行中的关键安全风险，尤其是对于由 Tether 和 Kraken 等主要机构支持的项目。它削弱了对稳定币挂钩的信任，并展示了多签漏洞对 DeFi 市场的毁灭性影响。 攻击者通过多签漏洞铸造了 1350 万美元的无抵押代币，随后在去中心化交易所抛售了 1040 万美元面值的代币。剩余的 310 万美元无抵押代币可能仍由攻击者持有，构成进一步风险。

rss · The Block · May 24, 15:08

**背景**: StablR 是一家由 Tether 和 Kraken 支持的稳定币发行商，发行 EURR（与欧元挂钩）和 USDR（与美元挂钩）。多签钱包需要多个私钥才能授权交易，这增加了安全性，但如果多签机制被攻破，也会引入潜在的攻击向量。稳定币脱钩是指代币市场价格显著偏离其目标挂钩，通常是由于信心丧失或安全事件导致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://x.com/WuBlockchain/status/2058571844597194847">StablR Stablecoins Depeg After $13.5M Multisig Exploit According ...</a></li>

</ul>
</details>

**社区讨论**: 社区对该漏洞表示震惊和担忧，许多人质疑 StablR 的安全实践以及多签设置的有效性。一些用户呼吁对稳定币发行商进行更严格的审计和更好的保护机制。

**标签**: `#DeFi`, `#security`, `#stablecoin`, `#exploit`, `#blockchain`

---

<a id="item-8"></a>
## [Audiomass：免费开源的多轨网页音频编辑器](https://audiomass.co/?multitrack=1) ⭐️ 7.0/10

Audiomass 是一款完全在网页浏览器中运行的免费开源多轨音频编辑器，支持 FLAC 文件，并拥有直观的用户界面。 该项目为桌面 DAW 提供了一个高质量、易访问的替代方案，降低了音频编辑的门槛，并支持直接在浏览器中进行协作。 代码库使用了较老的 JavaScript 模式，如安全闭包和顺序 var 声明，一些开发者对此感到怀旧。该仓库目前缺少明确的开源许可证，可能需要澄清。

hackernews · pantelisk · May 24, 15:25 · [社区讨论](https://news.ycombinator.com/item?id=48258015)

**背景**: 多轨音频编辑器允许用户在独立轨道上排列和混合多个音频片段，类似于数字音频工作站（DAW）。FLAC（自由无损音频编解码器）是一种无损压缩格式，能在减小文件大小的同时保留音频质量，因此受到发烧友的青睐。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/FLAC">FLAC - Wikipedia</a></li>
<li><a href="https://xiph.org/flac/">FLAC - What is FLAC?</a></li>
<li><a href="https://www.audacityteam.org/">Audacity ® | Free Audio editor, recorder, music making and more!</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞其直观的用户体验，将其与 Adobe 收购前的 Cool Edit Pro 相提并论。有人对基于云的协作功能表示兴趣，并指出该项目缺少许可证文件。

**标签**: `#audio editing`, `#open source`, `#web app`, `#multitrack`, `#UX`

---

<a id="item-9"></a>
## [DeepSeek Reasonix：高缓存原生编码代理](https://esengine.github.io/DeepSeek-Reasonix/) ⭐️ 7.0/10

一款名为 Reasonix 的 DeepSeek 原生编码代理被推出，它利用 DeepSeek 的高缓存能力来降低成本，同时 DeepSeek V4 Pro 也获得了永久价格折扣。 这种缓存优化的编码代理与永久降价的结合，可能使 DeepSeek 成为其他 AI 编码工具更具成本效益的替代品，从而加速开发者的采用。 该代理旨在最大化前缀缓存命中率，从而显著降低输入令牌成本；然而，一些社区成员质疑其新颖性，指出简单的桥接已经可以实现高缓存命中率。

hackernews · Alifatisk · May 24, 13:02 · [社区讨论](https://news.ycombinator.com/item?id=48256953)

**背景**: DeepSeek V4 Pro 提供高达 100 万令牌的上下文窗口和前缀缓存机制，可降低重复输入前缀的成本。像 DeepSeek TUI 这样的编码代理已经利用这种缓存来降低费用。Reasonix 似乎是另一个此类代理，但其相对于现有工具的具体优势存在争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/adrianlerer/deepseek-tui">GitHub - adrianlerer/deepseek-tui: Coding agent for DeepSeek ...</a></li>
<li><a href="https://deepseek-tui.com/en">DeepSeek TUI · 深度求索 终端</a></li>
<li><a href="https://pyshine.com/DeepSeek-TUI-Terminal-Native-Coding-Agent/">DeepSeek-TUI: Terminal-Native Coding Agent with 1M-Token ...</a></li>

</ul>
</details>

**社区讨论**: 评论褒贬不一：一些用户认为页面用户体验差（例如，动画打字导致布局移动），而另一些用户则认为简单的桥接无需专用代理即可实现类似的缓存优势。还有人质疑为了更好的结果而破坏前缀缓存是否合理。

**标签**: `#DeepSeek`, `#AI coding agent`, `#caching`, `#cost optimization`, `#LLM`

---

<a id="item-10"></a>
## [从 Go 迁移到 Rust 的指南引发热议](https://corrode.dev/learn/migration-guides/go-to-rust/) ⭐️ 7.0/10

一篇详细的从 Go 迁移到 Rust 的指南在 corrode.dev 上发布，重点讨论了两者在 Web 后端开发中的实际权衡。 该指南及随后的社区讨论反映了关于 Rust 的安全性和性能是否值得其复杂性，以及 Go 的简单性和托管运行时在服务端应用中的优势的持续辩论。 该指南比较了错误处理（Rust 的?操作符 vs Go 的显式错误返回）、包管理（Rust 的 Cargo vs Go 的标准库覆盖）以及托管运行时的作用，社区成员如 Animats 和 tptacek 发表了重要评论。

hackernews · jabits · May 24, 18:31 · [社区讨论](https://news.ycombinator.com/item?id=48259808)

**背景**: Go 和 Rust 都是现代系统编程语言，但理念不同：Go 优先考虑简单性和快速编译，带有垃圾回收器；而 Rust 提供零成本抽象和内存安全，无需运行时。两者之间的选择通常取决于应用领域，Go 在 Web 后端中流行，而 Rust 则用于性能关键型系统。

**社区讨论**: 社区讨论非常热烈，Animats 指出对于 Web 后端，Go 是很好的选择，Rust 的复杂性可能不值得。tptacek 认为决定归结于你是否想要托管运行时，而 Rust 倡导者常常夸大运行时的缺点。另一位评论者 amusingimpala75 抱怨 Rust 的包管理不如 Go 的标准库，而 nemo1618 指出指南中有 LLM 写作痕迹。

**标签**: `#Rust`, `#Go`, `#programming languages`, `#web development`, `#error handling`

---

<a id="item-11"></a>
## [诈骗者滥用微软内部账户发送垃圾邮件](https://techcrunch.com/2026/05/21/scammers-are-abusing-an-internal-microsoft-account-to-send-spam/) ⭐️ 7.0/10

诈骗者正在利用一个通常用于发送合法账户提醒（如双因素认证码）的微软内部账户，来发送垃圾邮件和钓鱼链接。这一漏洞使得邮件看起来像是来自受信任的微软域名。 这种滥用行为削弱了用户对微软邮件基础设施的信任，可能导致钓鱼成功率上升，因为收件人不太会质疑来自官方微软地址的邮件。这也凸显了大型科技公司在域名管理和身份验证实践方面的更广泛问题。 该内部账户被微软用于发送真实通知，但诈骗者找到了滥用它来发送恶意链接的方法。具体技术机制尚未完全披露，但它绕过了传统的电子邮件安全过滤器。

hackernews · spike021 · May 24, 00:51 · [社区讨论](https://news.ycombinator.com/item?id=48253186)

**背景**: 微软为其服务使用大量域名，管理这些域名的复杂性可能导致安全漏洞。诈骗者经常利用受信任的域名来绕过垃圾邮件过滤器并欺骗收件人。此事件是内部或官方账户被武器化用于钓鱼的更广泛趋势的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/05/21/scammers-are-abusing-an-internal-microsoft-account-to-send-spam/">Scammers are abusing an internal Microsoft account to send spam ...</a></li>
<li><a href="https://mashable.com/tech/scammers-weaponizing-official-microsoft-email-address">Internal Microsoft account being used to send scams ... - Mashable</a></li>
<li><a href="https://sesamedisk.com/microsoft-internal-account-abuse-2026-cybersecurity/">Microsoft Internal Account Abuse in 2026: Cybersecurity Threats and ...</a></li>

</ul>
</details>

**社区讨论**: 评论者对微软的域名管理表示不满，指出即使是内部团队也可能没有完整的自有域名列表，导致用户难以验证邮件合法性。一些人分享了相关经历，例如收到来自微软和谷歌的看似官方的邮件，但账户从未创建过，或者利用类似域名混淆的钓鱼尝试。

**标签**: `#security`, `#Microsoft`, `#spam`, `#phishing`, `#authentication`

---

<a id="item-12"></a>
## [纽约时报：CFTC 清除反对与特朗普有关联的加密公司的工作人员](https://www.theblock.co/post/402442/nyt-investigation-alleges-cftc-purged-staff-who-questioned-trump-tied-crypto-firms?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

《纽约时报》的一项调查指控，美国商品期货交易委员会（CFTC）清除了那些反对批准与唐纳德·特朗普有关联的加密公司的工作人员，而两名曾干预帮助这些公司的官员后来在 MoonPay 和 Gemini Titan 任职。 这引发了对美国加密货币监管中监管俘获和政治干预的严重担忧，可能损害市场诚信和公众对 CFTC 作为公正监管机构的信任。 这两名官员否决了工作人员反对意见，帮助三家公司获得批准，随后在 MoonPay 和 Gemini Titan 任职，这两家加密公司均从这些批准中受益。

rss · The Block · May 24, 20:42

**背景**: CFTC 是负责监管衍生品市场（包括加密货币衍生品）的美国联邦机构。MoonPay 是一家加密货币支付基础设施提供商，Gemini Titan 是一个衍生品平台，最近获得了 CFTC 批准，可以在美国提供受监管的预测市场和其他衍生品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.moonpay.com/">MoonPay : Buy and sell Bitcoin, Ethereum, and other cryptos</a></li>
<li><a href="https://www.coindesk.com/markets/2025/12/11/gemini-becomes-first-crypto-exchange-approved-by-cftc-to-offer-u-s-prediction-markets">$GEMI News: Winklevoss-Backed Gemini Wins CFTC ... - CoinDesk</a></li>

</ul>
</details>

**标签**: `#crypto regulation`, `#CFTC`, `#conflict of interest`, `#politics`, `#investigation`

---

<a id="item-13"></a>
## [《掌握 Dyalog APL》现以 Jupyter 笔记本形式发布](https://mastering.dyalog.com/README.html) ⭐️ 6.0/10

经典教材《掌握 Dyalog APL》现已推出基于 Jupyter 笔记本的交互式版本，读者可直接在浏览器中运行和修改代码示例。 这种现代格式降低了学习 APL（一种简洁的面向数组的语言）的门槛，通过提供对其独特符号语法的动手实践，可能吸引更多程序员探索这门小众但强大的语言。 交互式书籍托管在 mastering.dyalog.com，包含所有改编为 Jupyter 格式的原始内容。无需本地安装，用户可通过 Binder 等云服务直接运行笔记本。

hackernews · tosh · May 24, 11:42 · [社区讨论](https://news.ycombinator.com/item?id=48256475)

**背景**: APL 是 20 世纪 60 年代开发的一种编程语言，使用特殊符号表示操作，代码极其简洁。Dyalog APL 是其现代专有实现，广泛应用于金融和数据分析领域。Jupyter 笔记本是结合代码、文本和可视化的交互式文档，在数据科学和教育中很受欢迎。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dyalog_APL">Dyalog APL</a></li>
<li><a href="https://en.wikipedia.org/wiki/APL_(programming_language)">APL (programming language) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Jupyter_notebook">Jupyter notebook</a></li>

</ul>
</details>

**社区讨论**: 评论者赞赏交互式格式，认为它有助于建立 APL 符号的肌肉记忆。一些人讨论了 Dyalog APL 的许可（企业版，非开源），并分享了 LearnAPL 等替代学习资源。一位用户描述了使用 LLM 将 GNU APL 工具适配到 Dyalog 的经验。

**标签**: `#APL`, `#programming languages`, `#education`, `#Jupyter`

---

<a id="item-14"></a>
## [Greg Brockman 接受《知识项目》播客采访](https://fs.blog/knowledge-project-podcast/greg-brockman/) ⭐️ 6.0/10

OpenAI 关键人物 Greg Brockman 做客《知识项目》播客讨论人工智能，但该期节目没有提供文字稿，并因过于关注企业层面和内容浅显而受到批评。 作为 OpenAI 的联合创始人，Brockman 的见解备受期待，但该访谈被认为缺乏深度且偏向企业视角，可能让那些寻求 AI 开发技术或战略细节的人感到失望。 该播客节目仅有音频形式，未提供文字稿，社区评论指出听众希望获得更实质性的讨论，例如 Ilya Sutskever 在近期事件中的作用。

hackernews · prakashqwerty · May 24, 08:29 · [社区讨论](https://news.ycombinator.com/item?id=48255593)

**背景**: Greg Brockman 是领先的人工智能研究机构 OpenAI 的总裁兼联合创始人。《知识项目》是一档采访专家关于决策和学习的播客。本次访谈涵盖了 AI 行业趋势，但因缺乏技术深度而受到批评。

**社区讨论**: 社区评论对访谈过于关注企业层面表示失望，将其比作科技真人秀。一些用户指出 Musk 诉讼中公开的 Brockman 个人日记更具揭示性，另一些人则希望采访者能问及 Ilya Sutskever 被解雇及随后的声援信。

**标签**: `#OpenAI`, `#interview`, `#AI industry`, `#podcast`

---

<a id="item-15"></a>
## [加密支付轨道成为 AI 代理默认支付层](https://www.coindesk.com/business/2026/05/21/crypto-rails-are-becoming-the-default-payment-layer-for-ai-agents-report-says) ⭐️ 6.0/10

一份来自加密领域媒体的报告称，加密货币支付轨道正成为 AI 代理进行交易的默认方式，无需中介即可实现直接价值转移。 AI 代理与加密支付的融合可能实现机器对机器商业的自动化和简化，从而降低自动化经济中的成本和摩擦。这也可能加速区块链支付在新兴 AI 驱动市场中的采用。 该报告来自加密领域媒体，可能具有宣传性质；未提供具体数据或方法。加密支付轨道利用区块链网络直接结算价值，绕过了传统金融中介。

rss · CoinDesk · May 24, 13:00

**背景**: 加密支付轨道指基于区块链的系统，无需银行等中介即可直接转移价值。AI 代理是能够代表用户执行任务的自主程序，包括支付。两者的结合使 AI 代理能够使用加密货币或稳定币无缝交易。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://info.arkm.com/research/payment-rails-guide-crypto-money-moving-blockchain-stablecoin">A Guide to Crypto Payment Rails (2026) - info.arkm.com</a></li>
<li><a href="https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol">Announcing Agent Payments Protocol (AP2) | Google Cloud Blog</a></li>
<li><a href="https://www.imf.org/en/publications/imf-notes/issues/2026/04/22/how-agentic-ai-will-reshape-payments-575560">How Agentic AI Will Reshape Payments - IMF</a></li>

</ul>
</details>

**标签**: `#crypto`, `#AI agents`, `#payments`, `#blockchain`

---

<a id="item-16"></a>
## [Firefox Nova 重新设计包含 AI 关闭开关](https://decrypt.co/368867/firefox-redesign-kill-ai-button-project-nova) ⭐️ 6.0/10

Mozilla 宣布了 Project Nova，这是 Firefox 今年晚些时候的一次重大重新设计，具有更简洁的外观、紧凑模式以及一个可以完全禁用所有 AI 功能的开关。 这为用户提供了对主流浏览器中 AI 集成的前所未有的控制，解决了隐私问题，并迎合了偏好最少 AI 干扰的用户。 从 Firefox 148 版本开始，AI 开关位于设置中的 AI 控制下，允许用户阻止所有 AI 增强功能或单独管理它们。

rss · Decrypt · May 23, 17:01

**背景**: Mozilla 一直在将可选的 AI 功能集成到 Firefox 中，例如 AI 驱动的翻译和标签管理，但遭到了注重隐私的用户的反对。Project Nova 旨在使浏览器的 UI 现代化，同时尊重用户的选择。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.mozilla.org/en/firefox/new-firefox-design/">Designing Firefox for the future - The Mozilla Blog</a></li>
<li><a href="https://www.theverge.com/tech/935631/firefox-project-nova-redesign">Firefox is working on a rounded redesign with easy-to-find controls ...</a></li>
<li><a href="https://support.mozilla.org/en-US/kb/firefox-ai-controls">Block generative AI features with Firefox AI controls</a></li>

</ul>
</details>

**社区讨论**: Reddit 用户对垂直标签和 AI 开关表示兴奋，但有些人质疑重新设计是否会减慢浏览器速度或引入臃肿功能。

**标签**: `#Firefox`, `#browser`, `#AI`, `#redesign`, `#privacy`

---