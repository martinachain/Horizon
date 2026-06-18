---
layout: default
title: "Horizon Summary: 2026-06-18 (ZH)"
date: 2026-06-18
lang: zh
---

> From 86 items, 23 important content pieces were selected

---

1. [Epic Games 发布开源版本控制系统 Lore](#item-1) ⭐️ 8.0/10
2. [美国推迟将 DeepSeek 等 100 多家中国企业列入黑名单](#item-2) ⭐️ 8.0/10
3. [Adam (YC W25) 发布开源 AI CAD 平台](#item-3) ⭐️ 8.0/10
4. [在 EC2 上运行 Firecracker 虚拟机实现亚秒级浏览器启动](#item-4) ⭐️ 8.0/10
5. [RFC 10008 定义新的 HTTP QUERY 方法](#item-5) ⭐️ 8.0/10
6. [英伟达 ENPIRE 让机器人通过 AI 编码代理自我训练](#item-6) ⭐️ 8.0/10
7. [法国计划 2027 年前淘汰非量子加密](#item-7) ⭐️ 7.0/10
8. [爱沙尼亚计划为 AI 代理发放国民身份证](#item-8) ⭐️ 7.0/10
9. [阿里巴巴打造机器人操作系统 Qwen-Robot](#item-9) ⭐️ 7.0/10
10. [ChatGPT 市场份额跌破 50%，竞争对手崛起](#item-10) ⭐️ 7.0/10
11. [首个机密 DeFi 收益金库在以太坊上线](#item-11) ⭐️ 7.0/10
12. [面包袋夹的戏仿分类学](#item-12) ⭐️ 6.0/10
13. [《有故事的颜色》：带历史文化的色彩目录](#item-13) ⭐️ 6.0/10
14. [CME 首席执行官计划起诉 CFTC 批准永续期货](#item-14) ⭐️ 6.0/10
15. [FIFA 用 Avalanche 区块链反黄牛效果有限](#item-15) ⭐️ 6.0/10
16. [伊利诺伊州提议对持有数字资产征税](#item-16) ⭐️ 6.0/10
17. [穆迪在 Solana 上推出代币化资产信用评级](#item-17) ⭐️ 6.0/10
18. [加密货币安全审计远远不够](#item-18) ⭐️ 6.0/10
19. [调查发现患者将 AI 用于治疗](#item-19) ⭐️ 6.0/10
20. [GLAAD 报告：AI 放大反 LGBTQ 偏见与伤害](#item-20) ⭐️ 6.0/10
21. [币安可能被拒欧盟牌照](#item-21) ⭐️ 6.0/10
22. [Coinbase 计划推出代币化股票和期权交易](#item-22) ⭐️ 6.0/10
23. [澳大利亚高等法院裁定 Block Earner 需持金融牌照](#item-23) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Epic Games 发布开源版本控制系统 Lore](https://lore.org/) ⭐️ 8.0/10

Epic Games 宣布了 Lore，一个专为游戏开发设计的开源版本控制系统，旨在通过更好地处理大型二进制文件和独占锁来与 Perforce 竞争。 Lore 解决了游戏开发中 Git 在处理大型二进制资源和独占文件锁定方面的不足，为专有的 Perforce 提供了一个现代、可扩展的替代方案。 Lore 已经是 Unreal Editor for Fortnite (UEFN) 的内置版本控制系统，但由于专有的压缩格式，开源工具目前无法与 UEFN 通信。

hackernews · regnerba · Jun 17, 14:30 · [社区讨论](https://news.ycombinator.com/item?id=48571081)

**背景**: 像 Git 这样的版本控制系统针对文本文件进行了优化，但在处理游戏开发中常见的大型二进制文件（纹理、3D 模型、音频）时表现不佳。Perforce 因其对大型文件和独占文件锁定的支持而成为游戏行业的标配，但它是专有的且管理复杂。Lore 旨在将 Perforce 的可扩展性和锁定功能与 Git 的开放性和现代设计相结合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://epicgames.github.io/lore/explanation/system-design/">The Lore Version Control System - Lore Developer Documentation</a></li>
<li><a href="https://github.com/EpicGames/lore">GitHub - EpicGames/ lore : Lore is a next-generation, open source...</a></li>
<li><a href="https://www.phoronix.com/news/Epic-Games-Lore-VCS">Epic Games Announces Lore Open-Source Version Control System</a></li>

</ul>
</details>

**社区讨论**: 社区普遍欢迎 Lore，认为它是 Perforce 的急需替代品，尤其是对于 Unreal Engine 开发。一些评论者指出 Git 的用户界面不友好，而 Perforce 虽然占主导地位，但已显老旧。其他人强调，Lore 的成功将取决于主要游戏工作室的采用和工具支持。

**标签**: `#version control`, `#game development`, `#open source`, `#scalability`, `#Perforce alternative`

---

<a id="item-2"></a>
## [美国推迟将 DeepSeek 等 100 多家中国企业列入黑名单](https://www.reuters.com/world/china/us-holds-off-blacklisting-chinas-deepseek-more-than-100-firms-deemed-security-2026-06-17/) ⭐️ 8.0/10

美国商务部推迟将 DeepSeek 及其他 100 多家中国企业列入实体清单，该清单会以国家安全为由限制美国对它们的出口。 这一决定影响全球 AI 格局，因为 DeepSeek 是领先的中国 AI 公司，以成本效益高、开源权重的模型著称，可与美国同行竞争。推迟表明关于技术贸易限制及其对 AI 发展影响的争论仍在继续。 实体清单要求美国公司向清单实体出口时需获得政府许可，申请通常面临重大限制。由于现有出口管制，DeepSeek 的模型是开源权重的，并使用较弱的 AI 芯片进行训练。

hackernews · giuliomagnifico · Jun 17, 03:55 · [社区讨论](https://news.ycombinator.com/item?id=48565498)

**背景**: DeepSeek 是一家成立于 2023 年的中国 AI 初创公司，开发大型语言模型。其 2025 年 1 月发布的 R1 模型以极低的成本实现了与 OpenAI 的 GPT-4 相当的性能，采用了混合专家等技术，并在较不先进的芯片上进行训练。实体清单是美国贸易限制工具，此前曾针对华为、海康威视等中国科技公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://slguardian.org/us-delays-blacklisting-deepseek-and-more-than-100-chinese-firms-flagged-as-security-risks/">US Delays Blacklisting DeepSeek and More Than 100 Chinese Firms...</a></li>

</ul>
</details>

**社区讨论**: 评论者观点不一：有人称赞 DeepSeek 的性价比和实用性，也有人批评美国的虚伪并质疑执行可行性。少数人指出，中国 AI 公司已面临 GPU 出口限制，因此黑名单的实际影响有限。

**标签**: `#AI`, `#geopolitics`, `#trade policy`, `#DeepSeek`, `#security`

---

<a id="item-3"></a>
## [Adam (YC W25) 发布开源 AI CAD 平台](https://github.com/Adam-CAD/CADAM) ⭐️ 8.0/10

Adam (YC W25) 推出了 CADAM，这是一个开源文本转 CAD 网页应用，能够根据自然语言提示和图像参考生成参数化 3D 模型，输出带有交互式滑块的 OpenSCAD 代码，方便调整尺寸。 该项目旨在让机械 CAD 创作变得像 AI 生成代码一样便捷，有望降低爱好者和工程师快速原型设计的门槛。其开源性质和 YC 的支持可能加速 CAD-AI 领域的采用和社区贡献。 CADAM 使用一个代理端点，支持两种模式：参数化模式（编写/编辑 OpenSCAD）和网格模式（生成 3D 纹理网格）。它通过 WebAssembly 编译的 OpenSCAD 和 Three.js 渲染完全在浏览器中运行，并支持多种 LLM，包括 Claude、Gemini 和 OpenAI。

hackernews · zachdive · Jun 17, 16:14 · [社区讨论](https://news.ycombinator.com/item?id=48572553)

**背景**: 传统的 CAD 软件如 Fusion 360 或 SolidWorks 需要大量学习和手动建模。文本转 CAD 工具旨在通过使用 AI 将自然语言描述解释为 3D 模型来简化这一过程。CADAM 建立在代码即 CAD 的概念上，即通过编程方式（如 OpenSCAD）定义模型，使其具有参数化和可编辑性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Adam-CAD/CADAM">GitHub - Adam-CAD/CADAM: CADAM is the open source text-to-CAD web application · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/CADAM">CADAM - Wikipedia</a></li>
<li><a href="https://sourceforge.net/projects/cadam.mirror/">CADAM download | SourceForge.net</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一：一些工程师对实际效用持怀疑态度，认为对于精确的机械零件，手动建模更快更可靠。其他人则报告了复杂提示的成功测试，称赞其速度和参数化编辑。还有人对照片转 CAD 功能以及与类似项目的比较感兴趣。

**标签**: `#AI`, `#CAD`, `#open-source`, `#YC`, `#mechanical-design`

---

<a id="item-4"></a>
## [在 EC2 上运行 Firecracker 虚拟机实现亚秒级浏览器启动](https://browser-use.com/posts/firecracker-browser-infra) ⭐️ 8.0/10

Browser-use.com 描述了一种在 EC2 实例内运行 Firecracker 微虚拟机的方法，可在 1 秒内启动浏览器，并以 81%的规避率实现高隐蔽性，对抗反机器人检测。 该方法显著提升了浏览器自动化的隐蔽性，对网页抓取和测试至关重要，并展示了嵌套虚拟化在高密度、快速启动环境中的创新应用。 常规 EC2 实例上的嵌套虚拟化直到 2026 年 2 月才得到支持；此前需要裸金属实例才能运行 Firecracker。该方案使用 Chromium，但像 Lightpanda 这样的替代方案可能提供更好的资源效率。

hackernews · gregpr07 · Jun 16, 15:15 · [社区讨论](https://news.ycombinator.com/item?id=48556561)

**背景**: Firecracker 是 AWS 开发的开源虚拟化技术，可创建轻量级微虚拟机，兼具硬件虚拟化的安全性和容器的速度。反机器人措施通过各种指纹检测无头浏览器；规避它们需要复杂的技术，如 TLS 指纹欺骗和行为模拟。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/firecracker-microvm/firecracker">GitHub - firecracker-microvm/firecracker: Secure and fast ...</a></li>
<li><a href="https://firecracker-microvm.github.io/">GitHub Pages - Firecracker</a></li>
<li><a href="https://www.zenrows.com/blog/bypass-bot-detection">Bypass Bot Detection : 5 Best Methods - ZenRows</a></li>

</ul>
</details>

**社区讨论**: 评论者提出了关于规避反机器人措施的伦理问题，指出 AWS 最近对嵌套虚拟化的支持，并建议使用 Lightpanda 等替代浏览器以获得更好的性能。一些用户询问是否可以在没有 AI 的情况下使用该设置进行简单的数据检索。

**标签**: `#Firecracker`, `#EC2`, `#browser automation`, `#anti-bot`, `#virtualization`

---

<a id="item-5"></a>
## [RFC 10008 定义新的 HTTP QUERY 方法](https://www.rfc-editor.org/info/rfc10008/) ⭐️ 8.0/10

RFC 10008 正式引入了 HTTP QUERY 方法，这是一种安全且幂等的请求方法，允许包含请求体，解决了 GET 和 POST 在复杂查询上的限制。 这一新方法提供了一种标准化的方式来进行复杂查询，避免了 GET 的 URI 长度限制和 POST 的非幂等性，有利于 GraphQL 和高级搜索端点等 API。 QUERY 方法是安全且幂等的，意味着它不会改变服务器状态，重复请求具有相同效果。缓存是可选的，RFC 并未强制要求。

hackernews · schappim · Jun 17, 10:51 · [社区讨论](https://news.ycombinator.com/item?id=48568502)

**背景**: HTTP 传统上使用 GET 进行安全、幂等的数据检索，但 GET 不能包含请求体，限制了复杂查询。POST 可以包含请求体，但不是幂等的，会导致重新提交警告等问题。QUERY 方法通过结合安全性和幂等性与请求体，填补了这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://httpwg.org/http-extensions/draft-ietf-httpbis-safe-method-w-body.html">The HTTP QUERY Method</a></li>
<li><a href="https://news.ycombinator.com/item?id=48568502">RFC 10008 : The new HTTP Query Method | Hacker News</a></li>
<li><a href="https://http.dev/query">QUERY - Expert Guide to HTTP methods</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的评论讨论了缓存策略，一些人质疑如何缓存带有任意请求体的请求。其他人则欢迎该方法，认为它可以避免表单中 POST 的重新提交警告，并注意到达到了五位数的 RFC 编号里程碑。

**标签**: `#HTTP`, `#RFC`, `#protocol`, `#web standards`, `#caching`

---

<a id="item-6"></a>
## [英伟达 ENPIRE 让机器人通过 AI 编码代理自我训练](https://decrypt.co/371456/nvidia-built-robots-train-themselves-ai-coding-agents) ⭐️ 8.0/10

英伟达的 ENPIRE 框架让机器人能够自主训练，通过使用 Codex 和 Claude Code 等 AI 编码代理在真实硬件上编写和测试训练代码，无需人工干预。 这一进展可能通过自动化编写和调试训练代码的繁琐过程，显著加速机器人研究，从而可能带来更强大、更适应性强的机器人。 在测试中，使用 ENPIRE 的八台机器人舰队在包括 GPU 安装和剪扎带等任务上实现了高达 99%的成功率，证明了该系统的有效性。

rss · Decrypt · Jun 17, 20:16

**背景**: 传统的机器人训练需要人类工程师为每个任务手动编写和调整代码，这既耗时又限制了可扩展性。AI 编码代理是经过微调以生成代码的大型语言模型，ENPIRE 利用它们自动化从代码生成到硬件测试的整个训练流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arstechnica.com/ai/2026/06/ai-coding-agents-can-autonomously-direct-robot-training/">AI coding agents taught robots how to install GPUs and cut zip ties</a></li>
<li><a href="https://the-decoder.com/nvidia-research-shows-robots-that-train-themselves-through-ai-coding-agents/">Nvidia research shows robots that train themselves through AI coding agents</a></li>
<li><a href="https://startupfortune.com/nvidias-enpire-lets-ai-coding-agents-train-robots-to-install-the-gpus-that-run-ai/">Nvidia's ENPIRE lets AI coding agents train robots to install the GPUs ...</a></li>

</ul>
</details>

**标签**: `#Nvidia`, `#robotics`, `#AI agents`, `#self-training`, `#coding agents`

---

<a id="item-7"></a>
## [法国计划 2027 年前淘汰非量子加密](https://decrypt.co/371487/france-phase-out-non-quantum-encryption-bitcoin-security-concerns-grow) ⭐️ 7.0/10

法国宣布从 2027 年起将停止认证缺乏抗量子加密的安全产品，理由是担心未来量子计算机对比特币等系统构成威胁。 这一政策转变标志着向抗量子加密的重大迈进，可能影响全球网络安全标准，并迫使区块链等行业在量子计算机可行之前升级其安全性。 该淘汰政策适用于政府安全产品认证；官员警告了“先收集、后解密”攻击，即今天窃取的加密数据未来可能被量子计算机解密。

rss · Decrypt · Jun 18, 00:31

**背景**: 一旦量子计算机足够强大，就可能破解 RSA 和 ECC 等广泛使用的加密方法。抗量子加密旨在抵御经典和量子攻击。法国的举措是全球为量子时代做准备的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/371487/france-phase-out-non-quantum-encryption-bitcoin-security-concerns-grow">France to Phase Out Non-Quantum Encryption as Bitcoin ...</a></li>
<li><a href="https://cointelegraph.com/news/france-to-stop-certifying-products-lacking-quantum-resistant-encryption">France to Stop Certifying Non-Quantum-Resistant Products</a></li>
<li><a href="https://thesheffieldpress.com/france-to-phase-out-non-quantum-safe-security-products-by">France to phase out non-quantum-safe security products by 2027</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#encryption`, `#cybersecurity`, `#Bitcoin`, `#policy`

---

<a id="item-8"></a>
## [爱沙尼亚计划为 AI 代理发放国民身份证](https://decrypt.co/371441/estonia-ai-agents-national-id) ⭐️ 7.0/10

爱沙尼亚总理克里斯滕·米哈尔批准了一项提案，将为 AI 代理发放独立的个人识别码，与其人类所有者或运营者区分开。 这一举措可能为 AI 问责和数字身份树立全球先例，使当局能够追踪 AI 行为并明确责任归属，对 AI 治理和法律问责至关重要。 该识别码是一种数字身份，使当局能够追踪 AI 代理在互联网上的行为，并确定责任人或公司，同时代理的权限由所有者授权并受到限制。

rss · Decrypt · Jun 17, 18:35

**背景**: 爱沙尼亚以其先进的数字身份系统闻名，公民拥有电子居民身份和数字 ID 用于在线服务。该提案将这一概念扩展到 AI 代理，旨在为自主系统带来法律清晰度。AI 咨询委员会 Eesti.ai 建议此举，以解决 AI 代理日益自主化带来的问责空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/371441/estonia-ai-agents-national-id">Estonia Wants to Give AI Agents Their Own National ID</a></li>
<li><a href="https://gizmodo.com/estonia-is-giving-ai-agents-personal-identification-codes-2000773016">Estonia Is Giving AI Agents 'Personal Identification Codes'</a></li>
<li><a href="https://www.theregister.com/ai-and-ml/2026/06/18/estonia-intends-to-recognize-ai-agents-with-digital-ids/5258087">Estonia intends to recognize AI agents with digital IDs</a></li>

</ul>
</details>

**标签**: `#AI`, `#Digital Identity`, `#Estonia`, `#Regulation`

---

<a id="item-9"></a>
## [阿里巴巴打造机器人操作系统 Qwen-Robot](https://decrypt.co/371357/alibaba-qwen-robot-operating-system-robot-economy) ⭐️ 7.0/10

阿里巴巴发布了 Qwen-Robot 套件，包含三个 AI 基础模型——Qwen-RobotNav、Qwen-RobotManip 和 Qwen-RobotWorld，共同构成机器人操作系统，支持导航、操作和世界预测。 这标志着阿里巴巴在具身 AI 领域的重大战略举措，可能像 Android 对智能手机那样标准化机器人软件，并通过提供统一软件栈加速机器人经济发展。 这三个模型独立工作，但共同构成完整的操作系统：Qwen-RobotNav 处理导航，Qwen-RobotManip 处理操作，Qwen-RobotWorld 处理世界预测。该系统面向企业客户。

rss · Decrypt · Jun 16, 22:32

**背景**: 具身 AI 指通过物理身体与环境交互的人工智能，结合感知、认知和行动。阿里巴巴的 Qwen-Robot 旨在为这类机器人提供软件基础，类似于操作系统管理硬件资源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cryptobriefing.com/alibaba-qwen-robot-operating-system/">Alibaba builds Qwen - Robot , an operating system for the robot...</a></li>
<li><a href="https://decrypt.co/371357/alibaba-qwen-robot-operating-system-robot-economy">Alibaba Is Building Qwen - Robot : The Operating System for... - Decrypt</a></li>
<li><a href="https://www.gncrypto.news/news/alibaba-qwen-robot-os-navigation-control/">Alibaba Launches Qwen - Robot OS for Robot Navigation & Control</a></li>

</ul>
</details>

**标签**: `#embodied AI`, `#robotics`, `#Alibaba`, `#operating system`, `#AI industry`

---

<a id="item-10"></a>
## [ChatGPT 市场份额跌破 50%，竞争对手崛起](https://decrypt.co/371318/chatgpt-ai-market-share-claude-gemini-grok) ⭐️ 7.0/10

Sensor Tower 的《2026 年人工智能现状》报告显示，ChatGPT 的用户份额首次跌破 50%，而 Google Gemini 和 Anthropic Claude 正在迅速追赶。 这一转变标志着 ChatGPT 在 AI 聊天机器人市场近乎垄断地位的终结，可能导致更具竞争力的定价、更快的创新以及 AI 助手的多样化。 Gemini 受益于成为 Android 设备的默认助手，而 Claude 的增长部分得益于一份 2 亿美元的五角大楼合同，不过该合同因伦理争议已被终止。

rss · Decrypt · Jun 16, 19:59

**背景**: ChatGPT 由 OpenAI 于 2022 年底推出，迅速主导了生成式 AI 市场。然而，Google Gemini 和 Anthropic Claude 等竞争对手随后推出了各自的聊天机器人，利用平台集成和企业信任等独特优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sensortower.com/report/state-of-ai-2026">State of AI 2026 | The Industry-Defining Report</a></li>
<li><a href="https://sensortower.com/press/sensor-tower-state-of-ai-2026-report-global-time-spent-on-generative-ai-apps-projected-to-more-than-double-year-over-year">Sensor Tower State of AI 2026: Usage and Revenue Surge</a></li>
<li><a href="https://www.axios.com/2026/02/15/claude-pentagon-anthropic-contract-maduro">Pentagon threatens to cut off Anthropic in AI safeguards dispute</a></li>

</ul>
</details>

**标签**: `#AI`, `#Chatbots`, `#Market Share`, `#ChatGPT`, `#Gemini`

---

<a id="item-11"></a>
## [首个机密 DeFi 收益金库在以太坊上线](https://www.theblock.co/post/404992/zama-morpho-steakhouse-launch-first-confidential-defi-yield-vault-ethereum?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Zama、Morpho 和 Steakhouse 在以太坊上推出了首个机密 DeFi 收益金库，使机构能够在无需暴露余额的情况下赚取 USDC 收益。 该金库解决了机构 DeFi 参与者的关键隐私需求，有望释放此前因链上可见性而犹豫的大量资本。 该金库使用 Zama 的全同态加密（FHE）技术，在保持余额机密的同时与 Morpho 借贷协议交互，且 Steakhouse 现有的金库基础设施保持不变。

rss · The Block · Jun 17, 10:00

**背景**: 传统 DeFi 协议完全透明，所有存款、取款和仓位都在区块链上可见。这种缺乏隐私的状况阻碍了需要保密策略的机构投资者。使用 FHE 的机密计算可以在不解密的情况下处理数据，从而在公共区块链上实现私有交易。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.thirdweb.com/confidential-defi-is-here-how-fhe-is-bringing-private-yield-vaults-to-ethereum/">Confidential DeFi on Ethereum: FHE Yield Vaults Explained | 2026</a></li>
<li><a href="https://www.zama.org/post/morpho-zama-steakhouse-launch-confidential-usdc-vault">The First DeFi Yield Venue for Confidential USDC (cUSDC) in...</a></li>
<li><a href="https://cryptobriefing.com/confidential-defi-yield-vault-ethereum/">Zama, Morpho, and Steakhouse launch first confidential DeFi yield ...</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#privacy`, `#Ethereum`, `#confidential computing`, `#blockchain`

---

<a id="item-12"></a>
## [面包袋夹的戏仿分类学](https://www.horg.com/horg/?page_id=921) ⭐️ 6.0/10

全型面包夹研究组（HORG）将面包夹视为生物有机体，提出了详细的分类学，将其归入 Occlupanida 纲。 这个幽默项目凸显了网络文化对戏仿科学的热爱，并引起了社区的一定兴趣，引发了关于日常物品的轻松讨论。 该分类学将面包夹归入 Microsynthera 界、Plasticae 门，并使用伪生物学术语描述其触须和标签等特征。

hackernews · beatthatflight · Jun 17, 23:20 · [社区讨论](https://news.ycombinator.com/item?id=48578388)

**背景**: 面包夹，也称为 occlupanids，是用于密封面包袋的小型塑料装置。HORG 是一个戏仿研究组织，受其可能被误食的危险启发，将它们当作生物物种进行编目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Occlupanid">Occlupanid</a></li>
<li><a href="https://en.wikipedia.org/wiki/Holotypic_Occlupanid_Research_Group">Holotypic Occlupanid Research Group - Wikipedia</a></li>
<li><a href="https://www.horg.com/horg/?page_id=921">Taxonomy | HORG</a></li>

</ul>
</details>

**社区讨论**: 评论显示，不熟悉面包夹的欧洲用户感到困惑，而其他人则幽默地推测“触须”的功能，并指出该页面在 Hacker News 上被频繁重新提交。

**标签**: `#humor`, `#bread tags`, `#taxonomy`, `#satire`, `#internet culture`

---

<a id="item-13"></a>
## [《有故事的颜色》：带历史文化的色彩目录](https://storiedcolors.com/) ⭐️ 6.0/10

《有故事的颜色》是一个精心策划的在线目录，它展示了带有名称的颜色，并讲述了每种色调背后的历史和文化故事。 该资源通过将颜色名称与其起源联系起来，丰富了设计和色彩社区，成为设计师、艺术家和历史学家的宝贵参考。 该目录包括诸如 VanDyke Brown 等颜色，并引用了社区喜爱的颜色，如 Rebecca Purple——一种为纪念 Eric Meyer 的女儿而添加的 CSS 颜色。

hackernews · susiecambria · Jun 17, 21:49 · [社区讨论](https://news.ycombinator.com/item?id=48577374)

**背景**: 命名颜色在艺术、设计和文化中有着悠久的历史，常常承载着故事或象征意义。该目录整理了这些故事，提供了超越简单十六进制代码的背景信息。

**社区讨论**: 评论者分享了额外资源，如 Chromatopia 一书和 Kory Stamper 的《True Color》，并提到了 Rebecca Purple 的情感意义。一些人讨论了颜色准确性，比如 VanDyke Brown 看起来更像 Burnt Sienna。

**标签**: `#design`, `#color`, `#culture`, `#reference`

---

<a id="item-14"></a>
## [CME 首席执行官计划起诉 CFTC 批准永续期货](https://www.coindesk.com/policy/2026/06/17/cme-chief-executive-says-company-plans-to-sue-cftc-after-perpetual-futures-approval) ⭐️ 6.0/10

CME 集团首席执行官 Terry Duffy 宣布公司计划起诉美国商品期货交易委员会（CFTC）批准永续期货，认为根据《多德-弗兰克法案》，永续期货应被归类为掉期合约。 这起诉讼可能重塑美国加密货币衍生品的监管格局，可能迫使 CFTC 重新分类永续期货，并对交易所施加更严格的掉期类要求。 永续期货是无到期日的现金结算合约，在加密货币市场广泛使用。Duffy 声称 CFTC 的批准违反了《多德-弗兰克法案》，该法案对掉期的定义较为宽泛。

rss · CoinDesk · Jun 18, 03:44

**背景**: 永续期货，也称为永续掉期，由经济学家 Robert Shiller 于 1992 年首次提出。它们允许交易者无限期地投机资产价格而无需展期合约，因其灵活性和杠杆在加密货币领域广受欢迎。《多德-弗兰克法案》在 2008 年金融危机后颁布，扩大了 CFTC 对掉期的监管以降低系统性风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Perpetual_futures">Perpetual futures</a></li>
<li><a href="https://www.cftc.gov/LawRegulation/DoddFrankAct/index.htm">Dodd-Frank Act | CFTC</a></li>

</ul>
</details>

**标签**: `#crypto`, `#regulation`, `#derivatives`, `#CFTC`, `#CME`

---

<a id="item-15"></a>
## [FIFA 用 Avalanche 区块链反黄牛效果有限](https://www.coindesk.com/tech/2026/06/17/fifa-wanted-avalanche-s-blockchain-to-help-curb-world-cup-ticket-scalping-here-s-how-it-s-going) ⭐️ 6.0/10

FIFA 采用 Avalanche 区块链发行世界杯门票，通过链上追踪来防止倒票，但该举措在遏制高价转售方面效果有限。 此案例凸显了将区块链应用于现实反黄牛面临的挑战，因为仅靠技术方案无法消除市场需求或执法漏洞。 该系统利用 Avalanche 的智能合约发行不可转让且需身份验证的门票，但黄牛通过出售账户或使用代理服务找到了绕过控制的方法。

rss · CoinDesk · Jun 17, 19:08

**背景**: Avalanche 是 2020 年推出的 Layer-1 区块链平台，以高吞吐量和低费用著称。区块链票务旨在使门票防篡改且可追溯，但采用面临可用性和监管障碍。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Avalanche_(blockchain_platform)">Avalanche (blockchain platform) - Wikipedia</a></li>
<li><a href="https://timechainlabs.io/blog/how-blockchain-is-revolutionizing-ticketing:-solving-scalping,-fraud,-and-unfair-distribution">How Blockchain is Revolutionizing Ticketing: Solving Scalping ...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#ticketing`, `#scalping`, `#Avalanche`, `#FIFA`

---

<a id="item-16"></a>
## [伊利诺伊州提议对持有数字资产征税](https://www.coindesk.com/policy/2026/06/17/crypto-industry-aghast-at-illinois-new-tax-on-holding-or-transferring-digital-assets-in-state-budget) ⭐️ 6.0/10

伊利诺伊州在其州预算中提议对持有或转移数字资产征收新税，引发了加密货币行业的强烈反对。 这可能为其他州对加密资产征税开创先例，从而抑制数字资产领域的投资和创新。 该税适用于持有和转移数字资产，但具体税率和门槛尚未详细说明。该提案是更广泛的州预算谈判的一部分。

rss · CoinDesk · Jun 17, 16:50

**背景**: 在美国，加密货币目前被视为财产，交易需缴纳资本利得税。但对单纯持有征税并不常见，并因可能惩罚长期投资者而受到批评。

**标签**: `#cryptocurrency`, `#regulation`, `#taxation`, `#policy`

---

<a id="item-17"></a>
## [穆迪在 Solana 上推出代币化资产信用评级](https://www.coindesk.com/business/2026/06/17/moody-s-rolls-out-credit-ratings-on-solana-in-tokenized-asset-push) ⭐️ 6.0/10

穆迪已在 Solana 区块链上为代币化现实世界资产推出机器可读的信用评级，这标志着主要信用评级机构首次直接在公共区块链上发布评级。 此举标志着传统金融工具对区块链技术的机构采用日益增长，可能提高代币化资产市场的透明度和效率。 这些评级通过 Alphaledger 基础设施集成，使 Solana 成为首个支持穆迪链上评级的公共区块链。该计划专注于债券和基金等代币化现实世界资产。

rss · CoinDesk · Jun 17, 16:13

**背景**: Solana 是一种高性能区块链，以低费用和高吞吐量著称，常用于去中心化应用和代币化资产。代币化资产在区块链上代表债券或房地产等现实世界资产，可实现部分所有权和更快的结算。信用评级评估这些资产的信用度，传统上由穆迪等机构发布。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tradingview.com/news/cointelegraph:d328f19ab094b:0-moody-s-brings-credit-ratings-onchain-via-solana-explained/">Moody ’ s brings credit ratings onchain via... — TradingView News</a></li>
<li><a href="https://blockonomi.com/moodys-credit-ratings-go-live-on-solana-as-institutional-rwa-push-expands/">Moody ’ s Credit Ratings Go Live on Solana as... - Blockonomi</a></li>
<li><a href="https://en.wikipedia.org/wiki/Solana_(blockchain_platform)">Solana (blockchain platform)</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#Solana`, `#tokenization`, `#credit ratings`, `#DeFi`

---

<a id="item-18"></a>
## [加密货币安全审计远远不够](https://www.coindesk.com/opinion/2026/06/17/crypto-s-security-nightmare-won-t-be-solved-by-ordinary-audits) ⭐️ 6.0/10

一篇评论文章指出，标准安全审计不足以保障加密货币项目安全，呼吁采用形式化验证等更严格的方法。 这很重要，因为加密货币黑客攻击持续造成数十亿美元损失，依赖普通审计可能给投资者和用户带来虚假的安全感。 文章建议采用形式化验证——通过数学方法证明代码正确性——作为传统审计的更强替代方案，传统审计仅检查已知漏洞。

rss · CoinDesk · Jun 17, 14:12

**背景**: 安全审计在加密货币领域很常见，用于审查智能合约中的漏洞，但往往遗漏复杂或新型攻击。形式化验证使用数学证明来保证行为，提供更高水平的保障，但需要更多时间和专业知识。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.blockchain-council.org/cryptocurrency/auditing-cryptocurrencies/">What to Consider While Auditing Cryptocurrencies?</a></li>
<li><a href="https://hashlock.pages.dev/services/formal-verification">Blockchain Formal Verification | Hashlock</a></li>
<li><a href="https://medium.com/reach-sh/formal-verification-for-the-blockchain-749ef947a0e2">Formal verification for the blockchain | by Christopher... | Medium</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#security`, `#audits`, `#blockchain`

---

<a id="item-19"></a>
## [调查发现患者将 AI 用于治疗](https://decrypt.co/371451/psychologists-patients-bringing-ai-therapy-sessions-survey) ⭐️ 6.0/10

美国心理学会（APA）的一项新调查发现，超过三分之一的心理学家有患者将 AI 用作额外的心理健康资源。 这表明 AI 正日益融入心理健康护理，可能改善可及性，但也引发了对强化妄想或提供不准确建议的担忧。 临床医生警告说，AI 可能强化精神病患者的妄想，调查强调了制定 AI 在治疗中使用指南的必要性。

rss · Decrypt · Jun 17, 23:36

**背景**: 像 ChatGPT 这样的 AI 聊天机器人越来越多地被用于心理健康支持，但它们缺乏持证治疗师的培训和问责制。APA 调查强调了这带来的伦理和临床挑战。

**标签**: `#AI`, `#mental health`, `#psychology`, `#survey`

---

<a id="item-20"></a>
## [GLAAD 报告：AI 放大反 LGBTQ 偏见与伤害](https://decrypt.co/371431/glaad-ai-failing-lgbtq-users-warns-risk-growing) ⭐️ 6.0/10

GLAAD 发布报告警告，AI 系统正在日益放大反 LGBTQ 的偏见、错误信息、歧视和隐私伤害。 这很重要，因为 AI 正被部署在招聘、医疗和内容审核等关键领域，有偏见的系统可能对 LGBTQ 群体造成实际伤害。 报告指出，AI 可能生成恐同和恐跨性别内容、错误称呼用户性别、泄露隐私数据，且随着 AI 应用扩展，风险日益增加。

rss · Decrypt · Jun 17, 17:43

**背景**: AI 系统从包含社会偏见的大型数据集中学习，这些偏见可能被延续或放大。GLAAD 是一个 LGBTQ 倡导组织，负责监测媒体呈现和歧视问题。

**标签**: `#AI ethics`, `#bias`, `#LGBTQ`, `#privacy`, `#misinformation`

---

<a id="item-21"></a>
## [币安可能被拒欧盟牌照](https://decrypt.co/371343/binance-rejected-eu-regulatory-license-reuters) ⭐️ 6.0/10

路透社报道，币安很可能因《加密资产市场法规》（MiCA）下的牌照申请被拒而失去在欧盟运营的许可。 这将阻止币安服务欧盟客户这一重要市场，并标志着 MiCA 规则的严格执法，可能重塑欧洲加密货币交易所的竞争格局。 若无牌照，币安将从 2026 年 7 月起无法在欧盟运营。据报道决定即将做出，消息人士称相关当局以保密规则为由不予置评。

rss · Decrypt · Jun 16, 20:25

**背景**: 欧盟的 MiCA 法规自 2024-2025 年生效，要求加密货币交易所在欧盟提供服务必须获得牌照，旨在保护投资者并确保市场诚信。币安作为全球最大加密货币交易所，此前已在全球（包括美国和欧洲）面临监管挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.reuters.com/business/finance/binance-set-lose-eu-licence-bid-permission-offer-services-bloc-sources-say-2026-06-16/">Exclusive: Binance set to lose permission to operate in EU ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Markets_in_Crypto-Assets">Markets in Crypto -Assets - Wikipedia</a></li>
<li><a href="https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica">Markets in Crypto -Assets Regulation (MiCA)</a></li>

</ul>
</details>

**标签**: `#crypto`, `#regulation`, `#Binance`, `#EU`

---

<a id="item-22"></a>
## [Coinbase 计划推出代币化股票和期权交易](https://decrypt.co/371293/coinbase-launch-tokenized-stock-trading-crypto-equities-options) ⭐️ 6.0/10

Coinbase 宣布计划推出代币化股票交易以及加密货币/股票期权交易，旨在成为连接传统金融与加密货币的“全能交易所”。 此举标志着传统市场与加密货币市场融合的重要一步，可能吸引更多机构投资者并扩大 Coinbase 的收入来源。 代币化股票是基于区块链的数字资产，代表对真实股票的所有权；股票期权则是从标的股票中衍生价值的衍生品。Coinbase 尚未公布具体上线日期或提供哪些股票/期权。

rss · Decrypt · Jun 16, 19:00

**背景**: 代币化股票允许投资者在区块链平台上交易传统股票的部分份额，提供全天候交易和更低门槛。股票期权赋予在设定价格买入或卖出股票的权利，常用于对冲或投机。作为领先的加密货币交易所，Coinbase 正在向传统金融产品扩展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gemini.com/cryptopedia/what-are-tokenized-stocks-and-how-do-they-work">What Are Tokenized Stocks and How Do They Work? | Gemini</a></li>
<li><a href="https://www.coingecko.com/learn/what-are-tokenized-stocks">What Are Tokenized Stocks and Top Platforms to Get... | CoinGecko</a></li>
<li><a href="https://www.ig.com/en-ch/glossary-trading-terms/equity-options-definition">Equity Options Definition | What Does Equity Options Mean</a></li>

</ul>
</details>

**标签**: `#Coinbase`, `#tokenized stocks`, `#crypto exchange`, `#equities options`

---

<a id="item-23"></a>
## [澳大利亚高等法院裁定 Block Earner 需持金融牌照](https://www.theblock.co/post/405048/australia-high-court-block-earner-crypto-yield-case?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

澳大利亚高等法院一致裁定，Block Earner 的固定收益加密产品需要金融服务牌照，推翻了 2025 年有利于该公司的上诉裁决。 该裁决确立了具有约束力的先例，即加密收益产品可能被归类为澳大利亚法律下的金融产品，提高了澳大利亚加密公司的监管清晰度和合规义务。 Block Earner 于 2022 年 11 月自愿关闭了 Earner 产品，随后在 2026 年 5 月获得澳大利亚信贷牌照后转向加密抵押住房贷款业务。

rss · The Block · Jun 17, 09:45

**背景**: 根据澳大利亚法律，金融产品需要获得 ASIC 颁发的澳大利亚金融服务牌照（AFSL）。该案的核心是 Block Earner 的固定收益产品是否构成金融产品。澳大利亚最近于 2026 年 4 月通过了全面的数字资产立法，要求加密交易所和托管提供商获得牌照。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://financefeeds.com/block-earner-loses-high-court-fight-over-crypto-yield-product/">Block Earner Loses High Court Fight Over Crypto Yield Product</a></li>
<li><a href="https://www.businessnewsaustralia.com/articles/high-court-rules-against-block-earner-finding-crypto-yield-product-was-a-financial-product.html">High Court rules against Block Earner over crypto product</a></li>
<li><a href="https://www.coindesk.com/policy/2026/04/01/australia-passes-crypto-licensing-bill-as-ausd24-billion-opportunity-comes-into-focus">Australia passes crypto regulation requiring exchanges to ...</a></li>

</ul>
</details>

**标签**: `#crypto regulation`, `#Australia`, `#legal`, `#Block Earner`

---