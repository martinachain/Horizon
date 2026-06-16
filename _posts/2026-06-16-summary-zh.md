---
layout: default
title: "Horizon Summary: 2026-06-16 (ZH)"
date: 2026-06-16
lang: zh
---

> From 72 items, 14 important content pieces were selected

---

1. [领英工作邀请中的后门利用 npm prepare 脚本](#item-1) ⭐️ 9.0/10
2. [Iroh 1.0：点对点网络库发布](#item-2) ⭐️ 8.0/10
3. [HN 用户分享本地模型编程方案](#item-3) ⭐️ 8.0/10
4. [x86 模拟器团队在仿真中修复糟糕代码](#item-4) ⭐️ 7.0/10
5. [Wi-Fi 智能灯泡中的禁书图书馆](#item-5) ⭐️ 7.0/10
6. [自建 AI 开发平台：代理式 CI/CD 流水线](#item-6) ⭐️ 7.0/10
7. [探索完全自动化经济的技术可行性](#item-7) ⭐️ 7.0/10
8. [Hetzner 宣布大幅上调云服务器价格](#item-8) ⭐️ 7.0/10
9. [里约 AI 模型击败 DeepSeek，所有权争议浮现](#item-9) ⭐️ 7.0/10
10. [SEC 的 NMS 提案被称为今年最具影响力的美国加密规则](#item-10) ⭐️ 7.0/10
11. [一封写给计算机的怀旧情书](#item-11) ⭐️ 6.0/10
12. [我为什么给陌生人发邮件](#item-12) ⭐️ 6.0/10
13. [Anthropic 因涉嫌误导 Claude AI 定价被起诉](#item-13) ⭐️ 6.0/10
14. [菲律宾禁止隐私币，收紧加密货币上市规则](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [领英工作邀请中的后门利用 npm prepare 脚本](https://roman.pt/posts/linkedin-backdoor/) ⭐️ 9.0/10

一名安全研究员记录了一次社会工程攻击，其中领英上的虚假招聘人员发送了一个 GitHub 仓库，该仓库包含一个后门，在安装依赖项时通过 npm 的 prepare 脚本执行。 此次攻击突显了一种结合社会工程和供应链入侵的新型攻击途径，利用对招聘的信任渗透开发者机器，并暴露了网络犯罪报告和平台问责方面的漏洞。 后门隐藏在公共 GitHub 仓库中被注释掉的测试代码中，npm prepare 脚本在 npm install 后自动运行，执行来自远程服务器的任意命令。

hackernews · lwhsiao · Jun 15, 20:00 · [社区讨论](https://news.ycombinator.com/item?id=48546294)

**背景**: npm 的 prepare 脚本是一个生命周期钩子，在开发模式下 npm install 后自动运行，常用于构建步骤。通过领英上的虚假工作邀请进行的社会工程攻击变得越来越普遍，尤其针对加密货币和技术工作者。npm 的供应链攻击日益令人担忧，诸如 Sha1-Hulud 和 Axios 攻击等事件已危及广泛使用的软件包。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nodejs-security.com/blog/npm-ignore-scripts-best-practices-as-security-mitigation-for-malicious-packages">NPM Ignore Scripts Best Practices - Node.js Secure Coding</a></li>
<li><a href="https://cheatsheetseries.owasp.org/cheatsheets/NPM_Security_Cheat_Sheet.html">NPM Security - OWASP Cheat Sheet Series</a></li>
<li><a href="https://grokipedia.com/page/Sha1-Hulud_npm_supply_chain_attack">Sha1-Hulud npm supply chain attack</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，这类攻击在过去两年中频繁发生，被攻陷的知名安全研究员的 GitHub 账户被利用。尽管有报告，但领英和 GitHub 缺乏行动令人沮丧，并呼吁建立集中式的网络犯罪报告系统。

**标签**: `#security`, `#social engineering`, `#supply chain attack`, `#npm`, `#LinkedIn`

---

<a id="item-2"></a>
## [Iroh 1.0：点对点网络库发布](https://www.iroh.computer/blog/v1) ⭐️ 8.0/10

Iroh 1.0，一个用 Rust 编写的点对点网络库已发布，它允许应用实例之间通过 ed25519 密钥对进行身份验证和加密的直接 QUIC 连接。 该版本通过提供应用层网络模型简化了去中心化应用的构建，减少了对传统基于 IP 的基础设施的依赖，使开发者更容易实现点对点连接。 Iroh 目前开箱即支持 IPv4、IPv6 和中继传输，但现在允许为 WebRTC、BLE 或 LoRa 等协议实现自定义传输。

hackernews · chadfowler · Jun 15, 15:13 · [社区讨论](https://news.ycombinator.com/item?id=48542480)

**背景**: 点对点网络允许设备之间直接通信，无需中央服务器。Iroh 工作在应用层（OSI 模型的第 7 层），意味着它在应用内部处理连接，而不是在网络层，类似于 Tailscale 的工作方式，但嵌入在应用中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/BunsDev/iroh-p2p">GitHub - BunsDev/ iroh - p 2 p : peer-2-peer that just works</a></li>
<li><a href="https://fosdem.org/2026/events/attachments/T9ACNE-iroh_p2p_connections/slides/267568/iroh_2p2_bineq6t.pdf">iroh 2 p 2 connection - FOSDEM 2026</a></li>
<li><a href="https://biggo.com/news/202506260117_Iroh_Networking_Library_Gains_Developer_Interest">Iroh Networking Library Gains Traction as Developers... - BigGo News</a></li>

</ul>
</details>

**社区讨论**: 社区评论将 Iroh 比作应用层的 Tailscale，开发者赞赏其自定义传输的可扩展性。一些用户质疑在已有 IP 和 DNS 的情况下是否需要这样的库，而另一些用户则倡导去中心化。

**标签**: `#p2p`, `#networking`, `#rust`, `#library`, `#release`

---

<a id="item-3"></a>
## [HN 用户分享本地模型编程方案](https://news.ycombinator.com/item?id=48542100) ⭐️ 8.0/10

Hacker News 用户正在分享用 Qwen 和 Gemma 等本地模型替代 Claude 和 GPT 等云端编程助手的详细经验和配置，理由包括隐私和成本优势。 这一讨论凸显了本地 AI 用于编程的日益增长趋势，可能减少对昂贵订阅的依赖，并提高开发者的数据隐私。 用户报告使用 Pi 编程框架配合 Qwen3.6 35B 或 Gemma 4 26B 模型，在高内存 Mac 或双 RTX 3090 PC 上运行，达到约 150 tokens/s 的速度，但本地模型能力不及前沿模型。

hackernews · cloudking · Jun 15, 14:46

**背景**: 本地大语言模型（LLM）运行在用户自己的硬件上，提供隐私保护且无持续费用。Qwen（来自阿里巴巴）和 Gemma（来自谷歌）等模型是开放权重的，可通过 Ollama 或 LM Studio 等工具运行。Claude 和 GPT-4 等前沿模型基于云端，需要订阅。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/qwen">Qwen API and Models | OpenRouter</a></li>
<li><a href="https://lmstudio.ai/models/qwen/qwen3-coder-30b">A powerful 30B MoE coding model from Alibaba Qwen , joining its...</a></li>
<li><a href="https://www.aimadetools.com/blog/how-to-run-gemma-4-12b-locally/">How to Run Gemma 4 12B Locally: Complete Laptop Setup Guide ...</a></li>

</ul>
</details>

**社区讨论**: 社区意见分歧：一些用户成功用本地模型替代了云端模型完成大部分任务，理由是隐私和成本；另一些人则认为性能差距仍然太大，不值得投入精力。一位用户指出，不使用最佳模型的机会成本太高。

**标签**: `#local-llm`, `#coding-assistant`, `#privacy`, `#open-source-ai`, `#performance`

---

<a id="item-4"></a>
## [x86 模拟器团队在仿真中修复糟糕代码](https://devblogs.microsoft.com/oldnewthing/20260615-00/?p=112419) ⭐️ 7.0/10

微软的 x86 模拟团队遇到了编写极其糟糕的代码，他们通过二进制翻译在仿真过程中即时修复了它，而不是等待开发者发布补丁。 这个故事凸显了模拟和兼容层如何超越单纯的模仿，主动改进软件，为在现代系统中处理遗留或有缺陷的代码树立了先例。 该模拟器使用了动态二进制翻译，一种类似 JIT 的技术，将 x86-32 指令转换为本地代码，使得团队可以在翻译过程中插入修复。这种方法类似于 Wine/Proton 热修复在 Linux 上提升游戏性能的方式。

hackernews · paulmooreparks · Jun 16, 04:46 · [社区讨论](https://news.ycombinator.com/item?id=48550693)

**背景**: 二进制翻译是一种将一种指令集架构（ISA）的指令翻译为另一种的技术。动态二进制翻译在运行时进行，能够实现静态翻译无法做到的优化和修复。微软用于 ARM 或其他架构的 x86 模拟器很可能使用了这项技术来提升兼容性和性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://devblogs.microsoft.com/oldnewthing/20260615-00/?p=112419">The time the x86 emulator team found code so bad that they fixed it ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Dynamic_binary_translation">Dynamic binary translation</a></li>
<li><a href="https://en.wikipedia.org/wiki/X86_virtualization">x86 virtualization - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者将其与历史上的案例相类比，比如微软在 Windows 95 中修复 SimCity 的释放后使用漏洞，以及现代的例子如 Wine/Proton 为《艾尔登法环》提供热修复。有人猜测，糟糕的代码可能是 1980/90 年代激进的编译器优化所致。

**标签**: `#x86 emulation`, `#software history`, `#compatibility`, `#bug fixing`

---

<a id="item-5"></a>
## [Wi-Fi 智能灯泡中的禁书图书馆](https://www.richardosgood.com/posts/banned-book-library/) ⭐️ 7.0/10

开发者 Richard Osgood 将一款 Wi-Fi 智能灯泡改造成禁书图书馆，在灯泡内搭建了一个隐藏的 Web 服务器，通过本地网络提供书籍访问。 该项目展示了物联网设备在信息自由方面的创新用途，凸显了日常智能家居设备如何被改造以绕过审查、保留对受限知识的访问。 该智能灯泡在其 ESP32 芯片上运行轻量级 Web 服务器，将书籍存储在闪存中，并通过类似强制门户的界面在用户连接到灯泡的 Wi-Fi 网络时提供访问。

hackernews · sohkamyung · Jun 15, 22:37 · [社区讨论](https://news.ycombinator.com/item?id=48547985)

**背景**: 智能灯泡是连接 Wi-Fi 并可远程控制的物联网设备。许多智能灯泡包含 ESP32 等微控制器，可以重新编程用于自定义用途。将此类设备改造为数据存储或 Web 服务器是一种硬件破解形式，挑战了消费电子产品的预期用途。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cybersecuritynews.com/smart-bulbs-hacked/">Smart Bulbs can be Hacked to Steal Wi-Fi Passwords</a></li>
<li><a href="https://www.tomsguide.com/news/these-smart-bulbs-can-be-hacked-to-steal-your-wi-fi-password-what-you-need-to-know">These smart bulbs can be hacked to steal your Wi-Fi password — what you ...</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞了创意实现和其背后的意义，有人建议扩展为网状网络。少数怀疑论者对禁书的选择提出质疑，而其他人则将其与早期的 PirateBox 等项目相提并论。总体情绪积极，技术能力和传达的信息都受到赞赏。

**标签**: `#IoT`, `#censorship`, `#hacking`, `#free speech`, `#embedded systems`

---

<a id="item-6"></a>
## [自建 AI 开发平台：代理式 CI/CD 流水线](https://rsgm.dev/post/ai-dev-platform/) ⭐️ 7.0/10

一位开发者分享了他的自建 AI 开发平台，该平台利用 Forgejo、Argo workflows 和代理循环来自动化拉取请求的创建、测试、审查和合并。 这展示了一种实用的自托管方法，将 AI 代理集成到 CI/CD 流水线中，实现自动化的代码生成和审查，同时保持对开发过程的控制。 该平台使用 Forgejo 标签监听器触发 Argo workflows，协调问题标签、PR 编写、测试、审查-修改循环、防止合并风暴的合并互斥锁以及变基合并步骤。

hackernews · rsgm · Jun 15, 15:09 · [社区讨论](https://news.ycombinator.com/item?id=48542433)

**背景**: Forgejo 是一个自托管的 Git 协作开发平台，类似于 GitHub。Argo Workflows 是一个 Kubernetes 原生的工作流引擎，用于编排容器化任务。代理循环指的是 AI 代理通过迭代感知、行动和学习来自主完成任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Forgejo">Forgejo</a></li>
<li><a href="https://argo-workflows.readthedocs.io/en/latest/quick-start/">Quick Start - Argo Workflows - The workflow engine for Kubernetes</a></li>
<li><a href="https://likeone.ai/blog/what-are-agentic-loops-explained/">What Are Agentic Loops? Explained (2026) - Like One</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了类似的设置，例如使用 n8n 或 systemd 定时器替代 Argo，并讨论了代理身份和密钥管理等挑战。整体情绪积极，许多人感谢分享的经验和启发。

**标签**: `#homelab`, `#AI`, `#CI/CD`, `#agentic workflows`, `#Forgejo`

---

<a id="item-7"></a>
## [探索完全自动化经济的技术可行性](https://gmalandrakis.com/writings/ad-economicum.html) ⭐️ 7.0/10

G. Malandrakis 的一篇文章探讨了完全自动化、无人经济在技术上是否可行，引发了关于人工智能经济影响的高参与度讨论。 这场讨论挑战了关于工作、消费和经济激励的基本假设，随着人工智能的发展，对未来政策和社会结构具有深远影响。 该文章获得了 154 个点赞和 270 条评论，显示出社区的高度参与，其中包含了经济学家和软件工程师的批判性观点。

hackernews · l0new0lf-G · Jun 15, 21:10 · [社区讨论](https://news.ycombinator.com/item?id=48547062)

**背景**: “无人经济”的概念设想了一个由人工智能和机器人完成所有生产性劳动的系统，从而消除了人类工作的必要性。这引发了关于后工作社会中的收入分配、消费激励和社会目的等问题。

**社区讨论**: 评论者表达了怀疑：一些人认为必须先解决当前的经济问题（如高成本、住房短缺），而另一些人则争论经济学家还是工程师更适合分析人工智能的经济影响。一个关键观点是人类需求具有弹性，这阻碍了向完全自动化经济的简单过渡。

**标签**: `#AI`, `#economics`, `#automation`, `#future of work`

---

<a id="item-8"></a>
## [Hetzner 宣布大幅上调云服务器价格](https://docs.hetzner.com/general/infrastructure-and-availability/price-adjustment/#cloud-servers) ⭐️ 7.0/10

Hetzner 宣布大幅上调其云服务器价格，部分配置相比之前价格涨幅高达 3 倍。 此次价格调整反映了 AI 热潮和硬件稀缺带来的硬件成本上涨趋势，可能影响众多依赖 Hetzner 廉价云服务的中小企业。 新价格适用于云服务器，旧价格已存档以供对比；公司称此次调整是服务器产品标准化和价格调整的一部分。

hackernews · tuhtah · Jun 15, 13:19 · [社区讨论](https://news.ycombinator.com/item?id=48540844)

**背景**: Hetzner 是一家以价格竞争力著称的欧洲主要云服务商。AI 热潮增加了对 GPU 和内存等硬件的需求，推高了整个行业的成本。

**社区讨论**: 社区反应不一，许多人对高达 3 倍的涨幅表示不满，但也承认硬件成本压力普遍存在。部分用户建议 Hetzner 通过推出价格有竞争力的托管 Postgres 服务来赢回好感。

**标签**: `#cloud`, `#pricing`, `#hardware`, `#Hetzner`, `#AI`

---

<a id="item-9"></a>
## [里约 AI 模型击败 DeepSeek，所有权争议浮现](https://decrypt.co/371210/rio-ai-model-beat-deepseek-ownership-dispute-nex) ⭐️ 7.0/10

里约热内卢发布了一个前沿级 AI 模型，声称性能优于阿里巴巴的 DeepSeek，但 Nex AI 公司提出异议，并提供证据表明该模型基于他们的工作。 这一争议凸显了开源 AI 开发中归属和伦理的关键问题，可能影响 AI 研究社区的信任与合作。 据报道，里约模型在多项基准测试中击败了 DeepSeek，但 Nex 出示了收据，表明该模型未经许可源自他们的专有工作。

rss · Decrypt · Jun 15, 19:43

**背景**: DeepSeek 是一家成立于 2023 年的中国 AI 公司，以其大型语言模型如 DeepSeek-V3 而闻名。Nex AI 是一家专注于 AI 驱动的社交媒体自动化的公司。该事件引发了对模型所有权和开源重用边界的质疑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek - Wikipedia</a></li>
<li><a href="https://be.linkedin.com/company/nex-ai-be">Nex AI | LinkedIn</a></li>

</ul>
</details>

**标签**: `#AI`, `#open-source`, `#ethics`, `#controversy`, `#model ownership`

---

<a id="item-10"></a>
## [SEC 的 NMS 提案被称为今年最具影响力的美国加密规则](https://www.theblock.co/post/404768/benchmark-sec-nms-proposal-most-consequential-us-crypto-rule-this-year?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Benchmark 将 SEC 提议废除 Regulation NMS 中的规则 611 和 610(e)称为今年最具影响力的美国加密规则。 该提案可能通过取消订单保护和访问要求，从根本上重塑美国加密市场结构，可能增加交易场所之间的竞争和创新。 规则 611 和 610(e)是 Regulation NMS 的一部分，该法规管理证券的国家市场系统；废除它们将取消订单保护规则和某些报价访问要求。

rss · The Block · Jun 15, 15:33

**背景**: Regulation NMS（国家市场系统）由 SEC 于 2005 年通过，旨在现代化和加强美国股票市场。规则 611（订单保护规则）要求交易中心建立政策以防止交易穿透，而规则 610(e)涉及报价访问。SEC 于 2026 年 5 月宣布的提案旨在重新评估这些已实施二十年的规则。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sec.gov/newsroom/press-releases/2026-54-sec-proposes-rescission-regulation-nms-rules-611-610e">SEC Proposes Rescission of Regulation NMS Rules 611 ... - SEC.gov</a></li>
<li><a href="https://www.law.cornell.edu/cfr/text/17/242.611">17 CFR § 242.611 - Order protection rule. | Electronic Code ...</a></li>
<li><a href="https://www.law.cornell.edu/cfr/text/17/242.610">17 CFR § 242.610 - Access to quotations.</a></li>

</ul>
</details>

**标签**: `#crypto`, `#regulation`, `#SEC`, `#policy`

---

<a id="item-11"></a>
## [一封写给计算机的怀旧情书](https://michaelenger.com/blog/i-love-the-computer/) ⭐️ 6.0/10

Michael Enger 发表了一篇题为《我爱计算机》的个人散文，表达了对计算机的深厚感情，并感叹科技行业正在远离底层探索的转变。 这篇散文引起了许多开发者的共鸣，他们感到自己对计算机的热爱与当前行业对高层抽象和人工智能的专注之间存在脱节，引发了关于底层编程乐趣和 AI 角色的社区讨论。 该帖子评分为 6.0/10，表明它并非开创性内容，但情感上能引起共鸣。社区评论讨论了 AI 的实用性，有人称其为“蛇油”，也有人认为它在学习新领域时确实有用。

hackernews · speckx · Jun 15, 20:14 · [社区讨论](https://news.ycombinator.com/item?id=48546441)

**背景**: 这篇散文反映了对计算早期时代的怀旧，那时爱好者可以轻松摆弄硬件和底层代码。许多评论者分享了类似的经历，将过去与当今以云和 AI 为中心的行业进行对比。

**社区讨论**: 评论者表达了复杂的感受：有人怀念底层编程的简单，也有人为 AI 作为有用工具辩护。少数人分享了计算机如何为他们的生活提供稳定性的个人故事。

**标签**: `#nostalgia`, `#computing`, `#AI`, `#industry`, `#programming`

---

<a id="item-12"></a>
## [我为什么给陌生人发邮件](https://www.goodinternetmagazine.com/why-i-email-complete-strangers/) ⭐️ 6.0/10

一篇散文鼓励人们给陌生人发邮件以建立联系、学习和表达感激，并提供了低风险策略和真实案例。 这很重要，因为它推广了一种简单、低风险的方式，在日益数字化的世界中建立有意义的联系和分享知识。 文章建议从给博主发邮件感谢他们的帖子开始，因为这种方式风险低且常被感激，尤其是非主流作者。

hackernews · karakoram · Jun 15, 21:57 · [社区讨论](https://news.ycombinator.com/item?id=48547566)

**背景**: 给陌生人发邮件是一种冷接触方式，可能带来意想不到的联系和机会。文章认为，许多人对真诚、非交易性的信息持开放态度。

**社区讨论**: 评论者分享了积极经历，例如感谢博主或通过电子邮件、GitHub 或 Discord 讨论技术话题。有人指出，即使没有回复，这种举动也会受到感激。

**标签**: `#communication`, `#networking`, `#personal development`, `#email`

---

<a id="item-13"></a>
## [Anthropic 因涉嫌误导 Claude AI 定价被起诉](https://decrypt.co/371201/anthropic-lawsuit-allegedly-misleading-claude-ai-pricing) ⭐️ 6.0/10

一起集体诉讼已针对 Anthropic 提起，指控该公司在 Claude Max 订阅计划的使用限制和节省费用方面误导消费者。 此案可能为 AI 公司如何营销订阅层级树立先例，尤其是在使用限制和承诺节省方面，影响消费者信任和行业实践。 Claude Max 计划每月费用为 100-200 美元，提供比低层级高 5 倍或 20 倍的使用限制，但诉讼声称这些限制被夸大，节省费用具有误导性。

rss · Decrypt · Jun 15, 17:57

**背景**: Anthropic 通过多个订阅层级提供 Claude AI：免费版、Pro 版（每月 20 美元）、Max 版（每月 100-200 美元）、团队版和企业版。使用限制控制用户在一段时间内可以发送的消息数量。诉讼焦点在于 Anthropic 是否准确表述了这些限制以及 Max 计划的价值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://claude.com/pricing">Plans & Pricing | Claude by Anthropic</a></li>
<li><a href="https://intuitionlabs.ai/articles/claude-max-plan-pricing-usage-limits">Claude Max Plan Explained: Pricing, Limits & Features</a></li>
<li><a href="https://support.claude.com/en/articles/11647753-how-do-usage-and-length-limits-work">How do usage and length limits work? | Claude Help Center</a></li>

</ul>
</details>

**标签**: `#AI`, `#lawsuit`, `#Anthropic`, `#pricing`, `#ethics`

---

<a id="item-14"></a>
## [菲律宾禁止隐私币，收紧加密货币上市规则](https://decrypt.co/371124/philippines-issues-stricter-crypto-listing-rules-bans-privacy-coins) ⭐️ 6.0/10

菲律宾中央银行（BSP）发布新规，禁止虚拟资产服务提供商（VASP）上市隐私币，并对数字资产的上市、监控和退市提出更严格的要求。 此举标志着全球监管机构因洗钱和非法金融问题而打击隐私增强型加密货币的趋势，可能影响隐私币在菲律宾的采用和流动性，并对其他司法管辖区产生影响。 新规适用于所有受 BSP 监管的 VASP，要求其对上市资产实施强化尽职调查和交易监控。Monero 和 Zcash 等隐私币被明确禁止上市或交易。

rss · Decrypt · Jun 15, 11:27

**背景**: 隐私币是旨在隐藏交易细节（如发送方、接收方和金额）的加密货币，与比特币等透明区块链相比提供更强的匿名性。全球监管机构担心这些功能可能助长洗钱和其他非法活动。菲律宾一直在积极更新其加密货币监管框架，包括要求 VASP 在 BSP 注册并遵守反洗钱（AML）规则。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.binance.com/en/square/post/334364863652465">Philippine Central Bank Tightens Crypto Regulations: Complete ...</a></li>
<li><a href="https://coinpedia.org/cryptocurrency-regulation/cryptocurrency-regulations-in-philippines/">Crypto Regulations in the Philippines 2025 - Coinpedia Crypto Regulation in Philippines (2026 Guide) Philippine Central Bank Bans Crypto Exchanges From Listing ... Philippines Issues Stricter Crypto Listing Rules, Bans ... Philippines Bans Privacy Coins, Tightens Crypto Listing Rules Philippines' central bank tightens crypto rules... | Pluang ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#privacy coins`, `#Philippines`

---