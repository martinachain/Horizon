---
layout: default
title: "Horizon Summary: 2026-05-08 (ZH)"
date: 2026-05-08
lang: zh
---

> From 94 items, 35 important content pieces were selected

---

1. [Dirtyfrag：通过 AF_ALG 实现通用 Linux 本地提权](#item-1) ⭐️ 9.0/10
2. [Anthropic 发布自然语言自编码器](#item-2) ⭐️ 9.0/10
3. [Canvas 因 ShinyHunters 攻击宕机，数据泄露威胁](#item-3) ⭐️ 8.0/10
4. [延迟安装软件以防范供应链攻击](#item-4) ⭐️ 8.0/10
5. [Cloudflare 将裁员约 20%](#item-5) ⭐️ 8.0/10
6. [智能体需要控制流，而非更多提示](#item-6) ⭐️ 8.0/10
7. [AlphaEvolve：Gemini 驱动的编码代理扩展影响力](#item-7) ⭐️ 8.0/10
8. [面向 Metal 的 DeepSeek 4 Flash 本地推理引擎](#item-8) ⭐️ 8.0/10
9. [AI 垃圾内容正在侵蚀在线社区信任](#item-9) ⭐️ 8.0/10
10. [亚马逊、Coinbase、Stripe 为 AI 代理构建稳定币支付轨道](#item-10) ⭐️ 8.0/10
11. [Chrome 删除隐私承诺，悄悄安装 AI 模型](#item-11) ⭐️ 8.0/10
12. [AI 聊天机器人向广告追踪器泄露用户数据](#item-12) ⭐️ 8.0/10
13. [Tether 医疗 AI 在手机上运行，性能超越大 16 倍的模型](#item-13) ⭐️ 8.0/10
14. [谷歌将本地 AI 速度提升 3 倍，无需新硬件](#item-14) ⭐️ 8.0/10
15. [巴西 Pix 支付系统面临 Visa 和 Mastercard 压力](#item-15) ⭐️ 7.0/10
16. [Aave 在 KelpDAO 遭攻击后改革抵押品与上币标准](#item-16) ⭐️ 7.0/10
17. [IMF 警告 AI 将加剧金融系统网络攻击](#item-17) ⭐️ 7.0/10
18. [TrustedVolumes DeFi 遭黑客攻击损失 670 万美元](#item-18) ⭐️ 7.0/10
19. [AI 框架读取化学指令，找到最佳分子合成路线](#item-19) ⭐️ 7.0/10
20. [量子威胁或于 2030 年冲击比特币和以太坊](#item-20) ⭐️ 7.0/10
21. [Ondo、摩根大通、万事达卡和 Ripple 在 XRP 账本上结算代币化国债](#item-21) ⭐️ 7.0/10
22. [谷歌 DeepMind 入股《星战前夜》开发商，用游戏测试 AI 行为](#item-22) ⭐️ 7.0/10
23. [英伟达以认股权证支持 AI 扩张，IREN 股价飙升](#item-23) ⭐️ 7.0/10
24. [火人节一丝不苟的清理地图](#item-24) ⭐️ 6.0/10
25. [20 家银行和科技巨头排队通过 Anchorage 发行稳定币](#item-25) ⭐️ 6.0/10
26. [Solv Protocol 将 7 亿美元代币化比特币从 LayerZero 迁移至 Chainlink](#item-26) ⭐️ 6.0/10
27. [Kalshi 在预测市场热潮中以 220 亿美元估值融资 10 亿美元](#item-27) ⭐️ 6.0/10
28. [MEV 机器人抢先交易 Vitalik Buterin 的 4 美元兑换，交易量达 100 万美元](#item-28) ⭐️ 6.0/10
29. [Bitwise 收购 Superstate 的 2.67 亿美元 carry 基金，进军代币化](#item-29) ⭐️ 6.0/10
30. [Kraken 母公司以 6 亿美元收购亚洲稳定币公司 Reap](#item-30) ⭐️ 6.0/10
31. [SpaceX 将为 Anthropic 的 Claude 提供算力](#item-31) ⭐️ 6.0/10
32. [道金斯认为 Claude AI 可能有意识](#item-32) ⭐️ 6.0/10
33. [Anthropic 发布 10 个金融 AI 代理模板](#item-33) ⭐️ 6.0/10
34. [Hut 8 签署 98 亿美元 AI 数据中心租约，股价创历史新高](#item-34) ⭐️ 6.0/10
35. [美国财政部要求币安遵守监控规定](#item-35) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Dirtyfrag：通过 AF_ALG 实现通用 Linux 本地提权](https://www.openwall.com/lists/oss-security/2026/05/07/8) ⭐️ 9.0/10

一个名为 Dirtyfrag 的新型通用 Linux 本地提权漏洞已被披露，该漏洞通过 AF_ALG 和网络套接字利用内核内存损坏，目前尚无补丁或 CVE。 Dirtyfrag 影响所有主流 Linux 发行版，允许非特权用户获得 root 权限，其与近期 Copy Fail 漏洞的相似性凸显了内核安全中的系统性问题。 该漏洞链包括通过 xfrm-ESP 页缓存损坏导致的越界写入，与 Copy Fail 类似，但可通过普通网络套接字利用；缓解措施包括黑名单内核模块 esp4、esp6 和 rxrpc。

hackernews · flipped · May 7, 19:21 · [社区讨论](https://news.ycombinator.com/item?id=48053623)

**背景**: AF_ALG 是 Linux 内核中供用户空间访问加密算法的套接字接口。本地提权漏洞允许非特权用户获得 root 访问权限。近期披露的 Copy Fail（CVE-2026-31431）通过 AF_ALG 和 splice()利用了 algif_aead 中的类似缺陷。Dirtyfrag 将攻击面扩展到了网络套接字。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://almalinux.org/blog/2026-05-07-dirty-frag/">Dirty Frag vulnerability fix is ready for testing - AlmaLinux OS</a></li>
<li><a href="https://support.plesk.com/hc/en-us/articles/40314546777239-Dirty-Frag-vulnerability-reported-for-Linux-kernel">Dirty Frag vulnerability reported for Linux kernel - Plesk Support</a></li>

</ul>
</details>

**社区讨论**: 评论者指出其根本原因与 Copy Fail 相似，一位研究人员表示 xfrm-ESP 页缓存写入共享相同的 sink。另一位批评发行版默认启用可选内核功能，增加了攻击面。禁运被打破且缺乏补丁，提高了紧迫性。

**标签**: `#Linux`, `#kernel`, `#security`, `#privilege escalation`, `#vulnerability`

---

<a id="item-2"></a>
## [Anthropic 发布自然语言自编码器](https://www.anthropic.com/research/natural-language-autoencoders) ⭐️ 9.0/10

Anthropic 发布了开放权重的自然语言自编码器，能将模型内部激活转化为人类可读文本，支持 Qwen 2.5 (7B)、Gemma 3 (12B, 27B) 和 Llama 3.3 (70B)。 这一突破为理解大型语言模型的内部表征提供了可扩展的路径，有望实现更安全、更透明的 AI 系统。 该自编码器包含一个激活言语化器（将激活映射为文本）和一个激活重构器（从文本恢复原始激活）；其目标函数并未明确强制人类可读性，这引发了关于解释是否忠实的问题。

hackernews · instagraham · May 7, 17:54 · [社区讨论](https://news.ycombinator.com/item?id=48052537)

**背景**: 机械可解释性旨在通过分析神经网络内部激活来逆向工程其工作机制。传统方法如稀疏自编码器将激活分解为可解释特征，而自然语言自编码器更进一步，将整个激活向量转化为连贯的文本描述。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/research/natural-language-autoencoders">Natural Language Autoencoders \ Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区对开放权重发布感到兴奋，认为这是理解模型的一条可行路径，但部分评论者质疑生成的文本是否真正反映模型的内部推理，还是仅仅听起来合理。还有人指出训练目标不保证人类可读的解释，并对安全测试中可能存在的数据污染表示担忧。

**标签**: `#interpretability`, `#AI safety`, `#open-source`, `#transformer circuits`, `#Anthropic`

---

<a id="item-3"></a>
## [Canvas 因 ShinyHunters 攻击宕机，数据泄露威胁](https://www.theverge.com/tech/926458/canvas-shinyhunters-breach) ⭐️ 8.0/10

2026 年 5 月 7 日，Instructure 旗下的热门学习管理系统 Canvas 遭遇全国性宕机，黑客组织 ShinyHunters 声称已入侵并威胁泄露学校敏感数据。 此事件在期末考试期间影响了数百万学生和教育工作者，凸显了关键教育基础设施面对勒索软件攻击的脆弱性以及数据泄露的现实后果。 ShinyHunters 以“不付钱就泄露”策略闻名，此次攻击据称还涉及篡改学校登录页面。宕机迫使大学在考试周紧急制定应急方案。

hackernews · stefanpie · May 7, 22:22 · [社区讨论](https://news.ycombinator.com/item?id=48055913)

**背景**: Canvas 是基于云的 LMS，广泛用于 K-12、高等教育和企业培训。ShinyHunters 是一个 2020 年出现的网络犯罪组织，曾实施多起高调的数据泄露和勒索活动。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ShinyHunters">ShinyHunters</a></li>
<li><a href="https://en.wikipedia.org/wiki/Canvas_LMS">Canvas LMS</a></li>
<li><a href="https://en.wikipedia.org/wiki/Instructure">Instructure</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了沮丧和担忧，教育工作者指出宕机对期末考试造成了严重影响。一些评论者批评 Instructure 缺乏透明度，另一些人则就支付赎金的道德问题以及加强安全措施的必要性展开辩论。

**标签**: `#security`, `#breach`, `#education`, `#LMS`, `#ransomware`

---

<a id="item-4"></a>
## [延迟安装软件以防范供应链攻击](https://xeiaso.net/blog/2026/abstain-from-install/) ⭐️ 8.0/10

Xe Iaso 的一篇博客文章建议用户延迟一周安装新软件以缓解供应链攻击，引发了关于安全权衡的讨论。 这一提议凸显了软件供应链攻击日益增长的威胁，以及在现代开发工作流中平衡便利性与安全性的困难。 该建议涉及在安装新软件包前等待一周，利用许多高调攻击在一天内被发现并回滚的事实。然而，批评者指出，老练的攻击者可以定时执行攻击以绕过此类延迟。

hackernews · psxuaw · May 7, 23:02 · [社区讨论](https://news.ycombinator.com/item?id=48056227)

**背景**: 软件供应链攻击针对软件项目的依赖项和构建管道，通常通过向流行软件包中注入恶意代码实现。近期事件表明，攻击者可以攻破可信仓库和 CI/CD 系统，影响成千上万的下游用户。延迟安装的提议是一种务实但不完美的防御手段。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cisa.gov/resources-tools/resources/defending-against-software-supply-chain-attacks">Defending Against Software Supply Chain Attacks - CISA</a></li>
<li><a href="https://cheatsheetseries.owasp.org/cheatsheets/Software_Supply_Chain_Security_Cheat_Sheet.html">Software Supply Chain Security - OWASP Cheat Sheet Series</a></li>
<li><a href="https://www.splunk.com/en_us/blog/learn/software-supply-chain-security.html">Software Supply Chain Security: Proven Frameworks & Tactics to Stay Ahead of Threats | Splunk</a></li>

</ul>
</details>

**社区讨论**: 评论意见不一：一些人认为延迟安装是合理的缓解措施，而另一些人则辩称它对定时攻击无效。一位 FreeBSD 开发者建议使用具有协调更新的更安全操作系统作为更好的替代方案。

**标签**: `#security`, `#supply chain`, `#software engineering`, `#open source`

---

<a id="item-5"></a>
## [Cloudflare 将裁员约 20%](https://www.reuters.com/business/world-at-work/cloudflare-cut-over-1100-jobs-2026-05-07/) ⭐️ 8.0/10

Cloudflare 宣布将裁员约 20%，影响超过 1100 名员工，作为重组计划的一部分，以专注于长期增长。 一家主要互联网基础设施公司的大幅裁员可能预示着行业范围内的成本削减趋势，并引发对科技行业就业保障的担忧。 此次裁员距离 Cloudflare 在 2025 年 9 月招聘 1111 名实习生仅数月，凸显了招聘策略的鲜明对比。受影响的员工将获得截至 2026 年底的全额基本工资、医疗保险以及加速股权归属。

hackernews · PriorityLeft · May 7, 20:23 · [社区讨论](https://news.ycombinator.com/item?id=48054423)

**背景**: Cloudflare 是一家主要的内容分发网络和云安全公司。如此规模的裁员通常反映了公司战略或市场状况的变化，并可能在整个科技行业产生连锁反应。

**社区讨论**: 社区评论表达了震惊和失望，受影响的员工分享了个人经历。一些人批评时机，指出这与近期大规模招聘实习生形成对比，另一些人则质疑公司的理由。

**标签**: `#layoffs`, `#Cloudflare`, `#tech industry`, `#workforce reduction`, `#Hacker News`

---

<a id="item-6"></a>
## [智能体需要控制流，而非更多提示](https://bsuh.bearblog.dev/agents-need-control-flow/) ⭐️ 8.0/10

文章认为，构建可靠的 AI 智能体需要显式的控制流和代码生成，而非依赖改进的提示工程，这挑战了常见的提示优化方法。 这一见解可能改变开发者设计 AI 智能体的方式，强调确定性逻辑而非黑盒提示，从而在生产中构建更健壮、可验证的系统。 作者建议，当提示达到极限时，开发者应使用 LLM 编写代码以确定性方式完成任务，减少运行时对 LLM 的依赖。

hackernews · bsuh · May 7, 16:43 · [社区讨论](https://news.ycombinator.com/item?id=48051562)

**背景**: 当前的 AI 智能体通常依赖大型语言模型（LLM）和精心设计的提示来执行任务。然而，对于复杂的多步骤工作流，提示可能不可靠。像 ControlFlow 这样的控制流框架提供结构化的任务定义和编排，而 CodeAct 等代码生成方法使用可执行代码来执行动作，从而提供更确定性的行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://machinelearning.apple.com/research/codeact">CodeAct: Your LLM Agent Acts Better when Generating Code</a></li>
<li><a href="https://www.prefect.io/blog/controlflow-intro">Introducing ControlFlow</a></li>

</ul>
</details>

**社区讨论**: 评论者大多赞同这一观点，指出 LLM 应被用于编写确定性任务的代码，而非在运行时依赖它们。一些人建议，LLM 在运行时的角色将缩小为帮助用户选择符合业务规则的输入。

**标签**: `#AI agents`, `#LLM`, `#software engineering`, `#control flow`, `#prompting`

---

<a id="item-7"></a>
## [AlphaEvolve：Gemini 驱动的编码代理扩展影响力](https://deepmind.google/blog/alphaevolve-impact/) ⭐️ 8.0/10

Google DeepMind 推出了 AlphaEvolve，这是一个由 Gemini 驱动的编码代理，能够设计高级算法，并已部署在 Google 的基础设施中，用于优化关键系统。 AlphaEvolve 展示了 AI 自我改进以及解决数学和计算机科学开放问题的能力，有望加速研究并减少算法设计中的人力投入。 AlphaEvolve 采用进化方法与 Gemini 大语言模型相结合，迭代生成并优化算法，且已应用于 Google 的实际基础设施中。

hackernews · berlianta · May 7, 15:02 · [社区讨论](https://news.ycombinator.com/item?id=48050278)

**背景**: 编码代理是能够自主编写和优化代码的 AI 系统。AlphaEvolve 基于 Google 的 Gemini 模型和进化算法，构建了一个自我改进的系统，能够应对各领域的复杂算法挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepmind.google/blog/alphaevolve-impact/">AlphaEvolve: Gemini-powered coding agent scaling impact ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/AlphaEvolve">AlphaEvolve - Wikipedia</a></li>
<li><a href="https://thecodersblog.com/alphaevolve-gemini-powered-coding-agent-2026/">AlphaEvolve: Gemini AI Powers Next-Gen Coding Agent</a></li>

</ul>
</details>

**社区讨论**: 评论者指出 AlphaEvolve 与 Antirez 优化 Redis 的工作相似，对其实际适用性反应不一。有人质疑 Google 研究人员是否更偏好 Gemini 而非 Claude Code 等其他编码代理，也有人强调只有少数公司（Google、Sakana AI、Autohand AI）在从事这一领域。

**标签**: `#AI`, `#DeepMind`, `#coding agents`, `#self-improvement`, `#research`

---

<a id="item-8"></a>
## [面向 Metal 的 DeepSeek 4 Flash 本地推理引擎](https://github.com/antirez/ds4) ⭐️ 8.0/10

Antirez 发布了 ds4，这是一个针对 Apple Silicon 上 DeepSeek 4 Flash 的专注本地推理引擎，并针对 Metal 进行了优化。该项目在 GitHub 上开源，获得了社区广泛关注，获得 325 个点赞和 95 条评论。 该项目展示了针对特定硬件的推理优化的价值，可能提升在 Apple 设备上本地运行大型语言模型的性能和能效。同时，它也为对推理内部机制感兴趣的开发者提供了教育资源。 该引擎专为 DeepSeek 4 Flash 设计，这是一个 284B 参数的混合专家模型，激活参数为 13B。Antirez 指出，在他的 MacBook M3 Max 上，全速生成 token 时功耗峰值仅为 50W。

hackernews · tamnd · May 7, 15:40 · [社区讨论](https://news.ycombinator.com/item?id=48050751)

**背景**: DeepSeek 4 Flash 是一个混合专家（MoE）语言模型，总参数 284B，每个 token 激活 13B 参数。Metal 是 Apple 在 macOS 和 iOS 上的 GPU 加速框架，能够高效利用 Apple Silicon 的统一内存架构进行本地推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro">deepseek-ai/DeepSeek-V4-Pro · Hugging Face</a></li>
<li><a href="https://api-docs.deepseek.com/news/news260424">DeepSeek V4 Preview Release | DeepSeek API Docs</a></li>

</ul>
</details>

**社区讨论**: 社区称赞该项目专注优化且具有教育简洁性。一些用户分享了类似项目，另一些则强调了针对特定硬件的推理在缩小与前沿模型差距方面的潜力。Antirez 还分享了一个能效数据点。

**标签**: `#local inference`, `#Metal`, `#DeepSeek`, `#Apple Silicon`, `#open source`

---

<a id="item-9"></a>
## [AI 垃圾内容正在侵蚀在线社区信任](https://rmoff.net/2026/05/06/ai-slop-is-killing-online-communities/) ⭐️ 8.0/10

一项个人实验表明，AI 代理可以在 Reddit 上无检测地进行刷分和隐蔽广告，凸显了在线社区中 AI 生成内容日益严重的问题。 这侵蚀了在线互动的信任，给版主带来额外工作负担，并可能驱使人类离开大型社交平台，转向更小、更真实的社区。 一个社区报告每月封禁约 600 个 AI 内容创作者账号，一个创意小众社区因 AI 内容的腐蚀性影响于 2022 年禁止了 AI 生成内容。

hackernews · thm · May 7, 18:46 · [社区讨论](https://news.ycombinator.com/item?id=48053203)

**背景**: AI 生成内容常被称为“AI 垃圾”，指由大型语言模型（LLM）生成的文本、图像或其他媒体，这些内容可能与人类创作的内容难以区分。这引发了用户寻求真实人际互动的在线空间中真实性和信任的担忧。

**社区讨论**: 评论者表达了对对抗 AI 内容之战失败的恐惧，一些人看到了潜在的好处：AI 生成内容可能驱使人类回归现实世界互动。其他人则主张回归基于可信度的小型社区。

**标签**: `#AI`, `#online communities`, `#content moderation`, `#LLMs`, `#social media`

---

<a id="item-10"></a>
## [亚马逊、Coinbase、Stripe 为 AI 代理构建稳定币支付轨道](https://www.coindesk.com/business/2026/05/07/amazon-rolls-out-ai-agent-stablecoin-payments-platform-with-coinbase-and-stripe) ⭐️ 8.0/10

亚马逊云服务（AWS）与 Coinbase 和 Stripe 合作推出基于稳定币的支付平台，使 AI 代理能够使用 USDC 自主支付 API、数据和在线服务费用。 此次合作标志着向 AI 代理自主进行交易的代理经济迈出重要一步，可能改变数字服务的买卖方式。同时，它表明稳定币作为机器对机器商务的可编程支付轨道正被广泛采用。 该平台利用 Circle 发行的与美元挂钩的稳定币 USDC，实现低成本、可编程的支付。AWS 提供基础设施，Coinbase 负责托管和兑换，Stripe 则协助商家入驻和结算付款。

rss · CoinDesk · May 7, 16:50

**背景**: 支付轨道是资金从付款方转移到收款方的基础设施，例如信用卡网络或区块链系统。像 USDC 这样的稳定币是一种加密货币，旨在保持与法定货币的稳定价值，因此适合用于交易。代理经济是指未来 AI 代理代表人类或企业自主协商和执行交易的经济形态。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/USDC_(cryptocurrency)">USDC (cryptocurrency) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Payment_rail">Payment rail</a></li>
<li><a href="https://arxiv.org/abs/2505.15799">[2505.15799] The Agentic Economy - arXiv.org</a></li>

</ul>
</details>

**标签**: `#AI`, `#Fintech`, `#Stablecoins`, `#AWS`, `#Autonomous Agents`

---

<a id="item-11"></a>
## [Chrome 删除隐私承诺，悄悄安装 AI 模型](https://decrypt.co/367193/chrome-removes-privacy-claim-gemini-nano-google) ⭐️ 8.0/10

Google Chrome 删除了一项隐私声明，该声明曾承诺用户数据不会发送到其服务器，同时悄悄在符合条件的设备上下载了一个 4GB 的 Gemini Nano AI 模型，且未获得用户明确同意。 这削弱了用户对 Chrome 隐私实践的信任，并引发了对数据处理的担忧，因为浏览器悄悄安装了一个大型 AI 模型，可能消耗带宽和存储空间，并可能违反欧盟法律等隐私法规。 Gemini Nano 模型在被删除后会重新下载，表明这是一种故意的持久安装设计，而且用户看到的 AI 模式按钮实际上并不使用该模型。

rss · Decrypt · May 7, 20:52

**背景**: 像 Gemini Nano 这样的设备端 AI 模型允许在本地运行 AI 任务，无需将数据发送到云端，这可以增强隐私。然而，Chrome 的静默下载和删除隐私承诺与预期的隐私优势相矛盾，因为该模型在未获得用户明确同意的情况下安装，可能浪费资源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tomshardware.com/tech-industry/cyber-security/google-chrome-silently-downloads-4gb-ai-model-to-your-device-without-permission-report-claims-researcher-says-practice-may-violate-eu-law-waste-thousands-of-kilowatts-of-energy">Google Chrome 'silently' downloads 4GB AI model to your device without permission, report claims — researcher says practice may violate EU law, waste thousands of kilowatts of energy | Tom's Hardware</a></li>
<li><a href="https://cybernews.com/security/google-chrome-ai-model-device-no-consent/">Guy finds Google Chrome is quietly installing a 4GB AI model on our devices</a></li>

</ul>
</details>

**标签**: `#privacy`, `#Chrome`, `#AI`, `#Google`, `#data handling`

---

<a id="item-12"></a>
## [AI 聊天机器人向广告追踪器泄露用户数据](https://decrypt.co/367164/your-ai-chatbot-leaking-chats-meta-tiktok-google) ⭐️ 8.0/10

一项新研究揭示，包括 ChatGPT、Claude、Grok 和 Perplexity 在内的流行 AI 聊天机器人会与第三方广告追踪器共享用户数据，有时甚至在用户拒绝 cookie 时也会发生。 这一隐私泄露事件影响了数百万信任这些聊天机器人并与之进行敏感对话的用户，并凸显了 AI 服务中系统性的数据泄露问题，可能导致监管审查和用户信任丧失。 即使用户选择退出 cookie，数据共享仍然发生，表明同意机制无效。这些追踪器属于 Meta、TikTok 和谷歌等大型公司。

rss · Decrypt · May 7, 19:06

**背景**: 第三方广告追踪器是广告商用来监控广告活动表现和用户跨网站行为的软件。AI 聊天机器人基于大型语言模型构建，处理用户输入以生成回复，但可能无意中通过嵌入聊天机器人界面或 SDK 的追踪器传输数据。这项研究进一步证明了 AI 系统容易发生数据泄露，包括个人身份信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.riskinsight-wavestone.com/en/2025/05/leaking-minds-how-your-data-could-slip-through-ai-chatbots/">Leaking Minds: How Your Data Could Slip Through AI Chatbots - RiskInsight</a></li>
<li><a href="https://www.malwarebytes.com/blog/news/2025/09/when-ai-chatbots-leak-and-how-it-happens">When AI chatbots leak and how it happens | Malwarebytes</a></li>
<li><a href="https://neuraltrust.ai/blog/ai-model-data-leakage-prevention">Why Your AI Model Might Be Leaking Sensitive Data | NeuralTrust</a></li>

</ul>
</details>

**标签**: `#privacy`, `#AI`, `#data leakage`, `#chatbots`, `#tracking`

---

<a id="item-13"></a>
## [Tether 医疗 AI 在手机上运行，性能超越大 16 倍的模型](https://decrypt.co/367127/tether-medical-ai-runs-on-phone-outperforms-models-16x) ⭐️ 8.0/10

Tether 的 AI 研究团队发布了 QVAC MedPsy 系列医疗语言模型，可直接在智能手机和可穿戴设备上运行，在真实场景中性能超越 Google 的 MedGemma-27B，同时计算资源消耗减少三分之二。 这一突破使得强大的临床 AI 能够在边缘设备上部署，无需依赖云端，大幅降低成本和延迟，同时保护患者隐私。它挑战了“模型越大越好”的假设，可能重塑医疗 AI 的部署策略。 QVAC MedPsy 是专为边缘部署设计的纯文本模型系列，其性能超越了参数规模大约大 16 倍的 Google MedGemma-27B。该模型通过专门的架构优化而非暴力扩展实现了这种效率。

rss · Decrypt · May 7, 16:01

**背景**: 大型语言模型通常需要强大的云服务器才能运行，限制了它们在智能手机等资源受限环境中的使用。医疗 AI 模型尤其面临患者数据隐私和延迟方面的额外挑战。Tether 以其 USDT 稳定币闻名，近年来通过 Tether AI 云平台扩展至 AI 基础设施领域。QVAC MedPsy 代表了向高效、可在设备端离线运行的 AI 的转变。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://tether.io/news/tether-unveils-medical-ai-that-runs-on-phones-outperforms-much-larger-sota-models-and-can-cut-the-cloud-out-entirely/">Tether Unveils Medical AI That Runs on Phones, Outperforms ...</a></li>
<li><a href="https://huggingface.co/blog/qvac/medpsy">QVAC MedPsy : State-of-the-Art Medical and Healthcare Language...</a></li>
<li><a href="https://developers.google.com/health-ai-developer-foundations/medgemma">MedGemma | Health AI Developer Foundations | Google for ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#medical AI`, `#edge computing`, `#model efficiency`, `#Tether`

---

<a id="item-14"></a>
## [谷歌将本地 AI 速度提升 3 倍，无需新硬件](https://decrypt.co/367095/google-make-local-ai-3x-faster-no-new-hardware) ⭐️ 8.0/10

谷歌推出了多令牌预测（MTP）草稿器，使其 Gemma 4 模型在本地硬件上运行速度提升高达 3 倍，且质量无损，无需依赖云端。 这一突破在不升级硬件的情况下显著提升了本地 AI 推理性能，可能加速边缘计算和隐私保护型 AI 应用的发展。 该技术采用推测解码：草稿模型一次预测多个令牌，然后由目标模型在单次前向传播中验证，从而降低延迟并保持输出质量。

rss · Decrypt · May 7, 14:13

**背景**: 像 Gemma 4 这样的大型语言模型通常逐个生成令牌，在本地设备上速度较慢。推测解码将令牌生成与验证解耦，从而实现更快的推理。谷歌的 MTP 草稿器将此应用于 Gemma 4，实现了高达 3 倍的速度提升且质量无损。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ai.google.dev/gemma/docs/mtp/overview">Speed-up Gemma 4 with Multi-Token Prediction | Google AI for Developers</a></li>
<li><a href="https://news.ycombinator.com/item?id=48024540">Accelerating Gemma 4: faster inference with multi-token prediction drafters | Hacker News</a></li>
<li><a href="https://deepmind.google/models/gemma/gemma-4/">Gemma 4 - Google DeepMind</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Google`, `#Edge Computing`, `#Performance Optimization`

---

<a id="item-15"></a>
## [巴西 Pix 支付系统面临 Visa 和 Mastercard 压力](https://www.elciudadano.com/en/brazils-pix-payment-system-faces-pressure-from-visa-and-mastercard/04/04/) ⭐️ 7.0/10

巴西央行运营的即时支付系统 Pix 正面临 Visa 和 Mastercard 的抵制，它们认为央行不应既监管又参与支付市场竞争。 这一冲突凸显了公共数字支付基础设施与私营卡网络之间日益紧张的局势，对全球央行数字货币和支付系统监管的未来具有影响。 Pix 于 2020 年推出，对个人免费且交易即时处理，与传统方式相比大幅降低了成本和转账时间。Visa 和 Mastercard 声称央行作为监管者和竞争者的双重角色造成了不公平竞争。

hackernews · wslh · May 7, 17:42 · [社区讨论](https://news.ycombinator.com/item?id=48052371)

**背景**: Pix 是巴西央行创建的即时支付系统，通过手机应用实现银行账户间的免费实时转账。在 Pix 出现之前，巴西的银行转账缓慢、昂贵且繁琐。该系统已被广泛采用，超过 70%的成年人口使用它，减少了对现金和卡网络的依赖。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pix_(payment_system)">Pix (payment system) - Wikipedia</a></li>
<li><a href="https://stripe.com/resources/more/pix-replacing-cards-cash-brazil">A guide to Pix payments in Brazil | Stripe</a></li>

</ul>
</details>

**社区讨论**: 评论者大多支持 Pix，称赞其相比以往银行方式的效率和低成本。一些人批评 Visa 和 Mastercard 的立场是自私的，而另一些人则指出政府运营的系统可能缺乏私营网络的创新。少数评论者表示羡慕自己的国家缺乏类似系统。

**标签**: `#fintech`, `#payments`, `#regulation`, `#Brazil`, `#central bank digital currency`

---

<a id="item-16"></a>
## [Aave 在 KelpDAO 遭攻击后改革抵押品与上币标准](https://www.coindesk.com/business/2026/05/07/aave-to-overhaul-collateral-and-listing-standards-after-kelpdao-exploit) ⭐️ 7.0/10

Aave 宣布在 2026 年 4 月 KelpDAO 遭 2.92 亿美元攻击后，全面改革其抵押品与资产上币政策。新框架将基于网络安全、互操作性和技术架构评估资产，而不仅仅是价格波动。 此举为 DeFi 风险管理树立了新的行业标准，可能防止未来利用跨链漏洞的攻击。它直接影响借贷协议如何评估和上架抵押资产，从而提升用户和协议的安全性。 Aave 将发布一份面向寻求在协议上上币的发行方的最低标准手册。KelpDAO 攻击盗取了 116,500 枚 rsETH（占流通量的 18%），并将封装以太坊困在 20 条链上，迫使 Aave 进行紧急清算。

rss · CoinDesk · May 7, 14:27

**背景**: Aave 是领先的 DeFi 借贷协议，允许用户借贷加密货币。2026 年 4 月的 KelpDAO 攻击是当年最大的加密货币黑客事件，利用 LayerZero 的 OFT 标准漏洞从 rsETH 代币桥中盗走 2.92 亿美元。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/05/07/aave-to-overhaul-collateral-and-listing-standards-after-kelpdao-exploit">Aave rewrites the rulebook for asset listings after $293 million exploit</a></li>
<li><a href="https://www.msn.com/en-us/news/other/kelpdao-moves-to-chainlink-after-292m-layerzero-exploit/gm-GM4F772E05">KelpDAO moves to Chainlink after $292M LayerZero exploit - MSN</a></li>
<li><a href="https://www.chainalysis.com/blog/kelpdao-bridge-exploit-april-2026/">Inside the KelpDAO Bridge Exploit - chainalysis.com</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#Aave`, `#exploit`, `#risk management`

---

<a id="item-17"></a>
## [IMF 警告 AI 将加剧金融系统网络攻击](https://decrypt.co/367178/imf-warns-ai-supercharge-cyberattacks-global-financial-system) ⭐️ 7.0/10

国际货币基金组织（IMF）警告称，AI 工具甚至能让缺乏技能的 attackers 对全球金融系统发动复杂的网络攻击，并敦促将网络安全视为核心稳定问题。 这之所以重要，是因为金融部门是关键基础设施，其破坏可能引发系统性危机，而 AI 驱动的攻击降低了恶意行为者的门槛，增加了威胁的频率和严重性。 IMF 发出警告之际，有报告显示 2025 年超过 80%的金融服务公司遭遇了 AI 驱动的网络攻击，且国家行为者正利用 AI 以前所未有的速度渗透电网和金融机构。

rss · Decrypt · May 7, 19:44

**背景**: 金融部门长期以来一直是网络攻击的主要目标，因为它处理大量敏感数据和资金。AI 技术，如机器学习和自动化，现在使攻击者能够制作更具欺骗性的钓鱼邮件、逃避检测并快速扩大操作规模。IMF 呼吁将网络安全视为稳定问题，反映出人们日益认识到网络风险可能直接威胁全球金融稳定。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.weforum.org/stories/2024/05/financial-sector-cyber-attack-threat-imf-cybersecurity/">Cyberattacks threaten global financial stability, IMF warns</a></li>
<li><a href="https://quantum-cyber-ai.com/ai-powered-cyberattacks-infrastructure/">AI - Powered Cyberattacks on Critical... - Quantum Cyber AI</a></li>
<li><a href="https://www.linkedin.com/posts/coffee-cup-solutions_ai-powered-cyber-attacks-why-smbs-are-now-activity-7370744149123428352-F6Db">How AI - powered cyber attacks target SMBs and how to... | LinkedIn</a></li>

</ul>
</details>

**标签**: `#AI`, `#cybersecurity`, `#finance`, `#IMF`, `#critical infrastructure`

---

<a id="item-18"></a>
## [TrustedVolumes DeFi 遭黑客攻击损失 670 万美元](https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit) ⭐️ 7.0/10

DeFi 平台 TrustedVolumes 的流动性解析器遭黑客攻击，损失 670 万美元，该解析器被多个协议使用。DEX 聚合器 1inch 确认其自身系统未受影响。 此事件凸显了 DeFi 基础设施中持续存在的安全漏洞，尤其是作为关键中间件的流动性解析器。这加剧了 2026 年 5 月一系列重大攻击事件，凸显了整个生态系统加强安全措施的必要性。 此次攻击是 2026 年 5 月以来至少第五起重大 DeFi 黑客事件，此前 4 月已发生 28 起独立事件，总损失达 6.352 亿美元。攻击者从 TrustedVolumes 与 1inch 相关的解析器基础设施中盗取了约 590 万至 670 万美元。

rss · Decrypt · May 7, 11:25

**背景**: TrustedVolumes 是一个流动性解析器，通过将订单拆分到多个去中心化交易所，帮助 DeFi 协议高效执行交易。像 1inch 这样的 DEX 聚合器使用此类解析器为用户寻找最优交易路径。此次攻击针对的是中间件层，而非聚合器本身。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thedefiant.io/news/defi/1inch-resolver-trustedvolumes-drained-for-usd6-7m-on-ethereum">1inch Resolver TrustedVolumes Drained for $6.7M on Ethereum</a></li>
<li><a href="https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit">DeFi Platform TrustedVolumes Hit by $6.7M Exploit - Decrypt</a></li>
<li><a href="https://www.cryptotimes.io/2026/05/07/trustedvolumes-exploit-drains-5-9m-through-1inch-liquidity-system/">TrustedVolumes Exploit Drains $5.9M Through 1inch Liquidity ...</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#exploit`, `#cryptocurrency`

---

<a id="item-19"></a>
## [AI 框架读取化学指令，找到最佳分子合成路线](https://decrypt.co/367048/ai-chemistry-instructions-build-molecule) ⭐️ 7.0/10

EPFL 的研究人员开发了 Synthegy，这是一个利用大型语言模型解释自然语言化学指令，并为目标分子找到最佳合成路线的 AI 框架。 这一突破可能显著加速药物发现和材料科学，让化学家用日常语言描述所需分子，从而减少合成规划所需的时间和专业知识。 该框架在《Matter》期刊发表的论文中描述，利用大型语言模型作为推理引擎，筛选数千种可能的合成路线。其设计旨在让不熟悉 AI 或编程的化学家也能轻松使用。

rss · Decrypt · May 6, 21:31

**背景**: 合成规划是化学中的关键步骤，研究人员需确定构建目标分子的反应序列。传统方法依赖专家知识和手动搜索，耗时较长。基于 AI 的逆合成工具已经出现，但大多需要结构化输入；Synthegy 旨在通过接受自然语言来弥合这一差距。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://daddycow.com/livenewss/news/4158607/This-AI-Reads-Your-Chemistry-Instructions-and-Finds-the-Best-Way-to-Build-You-a-Molecule">This AI Reads Your Chemistry Instructions and Finds... | daddycow.com</a></li>
<li><a href="https://www.chemical.ai/chemairs">ChemAIRS® – AI-Powered Retrosynthesis & Synthetic Pathway Discovery | Chemical.AI</a></li>

</ul>
</details>

**标签**: `#AI`, `#chemistry`, `#synthesis`, `#NLP`, `#research`

---

<a id="item-20"></a>
## [量子威胁或于 2030 年冲击比特币和以太坊](https://decrypt.co/367047/bitcoin-ethereum-q-day-quantum-threat-could-arrive-2030) ⭐️ 7.0/10

一项新分析警告称，比特币和以太坊最早可能在 2030 年面临量子计算威胁，且可能早于网络部署防御措施。 这一时间线意义重大，因为它表明当前的加密保护可能比预期更早失效，影响数十亿美元加密资产的安全。 Decrypt 引用的报告指出，量子计算机可能破解比特币和以太坊使用的椭圆曲线加密，而抵御量子攻击的网络升级可能无法及时就绪。

rss · Decrypt · May 6, 21:07

**背景**: 量子计算机利用量子比特，在某些问题上比经典计算机快指数级。'Q-Day'指量子计算机强大到足以破解广泛使用的公钥加密（如 RSA 和 ECDSA）的时刻，这些加密是区块链安全的基础。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.forbes.com/sites/digital-assets/2026/03/31/google-finds-quantum-computers-could-break-bitcoin-sooner-than-expected/">Google Finds Quantum Computers Could Break Bitcoin Sooner ...</a></li>
<li><a href="https://www.btcpolicy.org/articles/state-of-play-quantum-computing-and-bitcoins-path-forward">State of Play: Quantum Computing and Bitcoin's Path Forward</a></li>
<li><a href="https://www.gate.com/learn/articles/what-is-q-day-quantum-computing-fundamentals-cryptographic-implications-and-cryptocurrency-risk-transmission">What Is Q - Day : Quantum Computing Threat to... | Gate Learn</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#cryptocurrency`, `#Bitcoin`, `#Ethereum`, `#security`

---

<a id="item-21"></a>
## [Ondo、摩根大通、万事达卡和 Ripple 在 XRP 账本上结算代币化国债](https://decrypt.co/367033/ondo-jpmorgan-mastercard-ripple-settle-tokenized-treasuries-xrp-ledger) ⭐️ 7.0/10

Ondo Finance、摩根大通的 Kinexys、万事达卡和 Ripple 已在 XRP 账本上使用 Ondo 的 OUSG 产品完成了首次近乎实时的跨境代币化美国国债赎回，资产端结算时间不到 5 秒。 这一演示表明，主要金融机构可以利用区块链实现代币化现实世界资产的即时跨境结算，有可能将结算时间从数天缩短到数秒，从而改变传统金融。 资产端在 XRPL 上不到 5 秒内完成结算，而万事达卡的多代币网络将法币支付路由到 Kinexys，后者将美元交付到 Ripple 的新加坡银行账户。

rss · Decrypt · May 6, 18:52

**背景**: 代币化国债是区块链上的数字代币，代表对美国国债等政府债务证券的所有权。XRP 账本以其快速的结算速度（3-5 秒）和低费用而闻名，适合跨境支付。Ondo Finance 是一个专注于现实世界资产代币化的平台，其 OUSG 产品代表代币化的美国国债。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ourcryptotalk.com/news/ondo-jpmorgan-mastercard-ripple-tokenized-treasury-settlement">Ondo, J.P. Morgan, Mastercard, Ripple Settle Tokenized Treasuries</a></li>
<li><a href="https://beincrypto.com/ripple-jpmorgan-mastercard-tokenized-treasury-pilot/">Ripple, JPMorgan & Mastercard Pull Off First Tokenized ...</a></li>
<li><a href="https://chain.link/article/what-are-tokenized-treasuries">What Are Tokenized Treasuries? | Chainlink</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#XRP`, `#finance`, `#settlement`

---

<a id="item-22"></a>
## [谷歌 DeepMind 入股《星战前夜》开发商，用游戏测试 AI 行为](https://decrypt.co/366991/google-deepmind-takes-stake-in-eve-online-maker-will-use-game-to-test-ai-behavior) ⭐️ 7.0/10

谷歌 DeepMind 已入股《星战前夜》（Eve Online）的开发商 CCP Games（现已更名为 Fenris Creations），计划利用该游戏复杂的虚拟环境作为 AI 模型的测试场。合作涉及在专门设计的离线版本游戏中进行受控实验。 这标志着 AI 研究的一种新方法，利用大型多人在线游戏的复杂经济和玩家互动，在安全的沙盒环境中研究多智能体系统和通用 AI 行为。相关见解可能推动自主协调和经济建模等领域的实际应用。 DeepMind 将在本地服务器上运行的离线版《星战前夜》中对其模型进行实验，从而在不影响真实玩家的情况下进行受控测试。该游戏由玩家驱动的经济和涌现的社会动态为评估 AI 决策和合作提供了独特的基准。

rss · Decrypt · May 6, 16:59

**背景**: 《星战前夜》是一款以复杂玩家驱动经济和大型玩家互动闻名的太空模拟 MMO，常被经济学家和社会学家研究。多智能体系统涉及多个 AI 智能体相互协作以解决单个智能体难以解决的问题，而像《星战前夜》这样的游戏环境为测试此类系统提供了真实、动态的场景。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arstechnica.com/gaming/2026/05/google-deepmind-partners-with-eve-online-for-ai-model-testing/">Google DeepMind partners with EVE Online for AI model testing - Ars Technica</a></li>
<li><a href="https://www.eveonline.com/news/view/a-new-era">A New Era | EVE Online</a></li>
<li><a href="https://www.reddit.com/r/Agent_AI/comments/1t5jx7i/google_deepmind_partners_with_eve_online_for_ai/">Google DeepMind Partners with EVE Online for AI Research as CCP Games Rebrands to Fenris Creations : r/Agent_AI - Reddit</a></li>

</ul>
</details>

**社区讨论**: Reddit 上的讨论反应不一：有人对 AI 研究的潜力感到兴奋，也有人担心对游戏社区的影响，或 AI 可能被用于操纵游戏内市场。还有人对 DeepMind 将如何处理游戏的复杂性感到好奇。

**标签**: `#AI`, `#DeepMind`, `#Eve Online`, `#multi-agent systems`, `#game-based research`

---

<a id="item-23"></a>
## [英伟达以认股权证支持 AI 扩张，IREN 股价飙升](https://www.theblock.co/post/400498/iren-stock-surges-as-nvidia-backs-ai-expansion-with-warrants-tied-to-30-million-shares?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

英伟达获得了可能转换为 21 亿美元 IREN 股份的认股权证，同时达成协议，利用英伟达的 DSX 架构部署高达 5 吉瓦的 AI 基础设施。 这表明英伟达通过战略合作伙伴关系大力扩展 AI 基础设施，可能加速大规模 AI 工厂的部署，并提升 IREN 的市场地位。 这些认股权证涉及 3000 万股，期限为五年。消息公布后，IREN 股价飙升超过 25%。

rss · The Block · May 7, 21:11

**背景**: IREN 是一家专注于 AI 基础设施的数据中心运营商。英伟达的 DSX 架构是 AI 工厂的参考设计。认股权证赋予英伟达在未来以设定价格购买股票的权利。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/400498/iren-stock-surges-as-nvidia-backs-ai-expansion-with-warrants-tied-to-30-million-shares">IREN stock surges as Nvidia backs AI expansion with warrants ...</a></li>
<li><a href="https://www.cnbc.com/2026/05/07/iren-stock-ai-infrastructure-nvidia.html">IREN inks AI infrastructure deal with Nvidia - CNBC</a></li>
<li><a href="https://nvidianews.nvidia.com/news/nvidia-and-iren-announce-strategic-partnership-to-accelerate-deployment-of-up-to-5-gigawatts-of-ai-infrastructure">NVIDIA and IREN Announce Strategic Partnership to Accelerate ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#Nvidia`, `#investment`, `#infrastructure`, `#stock`

---

<a id="item-24"></a>
## [火人节一丝不苟的清理地图](https://www.not-ship.com/burning-man-moop/) ⭐️ 6.0/10

一张详细的火人节垃圾追踪与拍照地图及流程确保了彻底的清理，社区成员记录并拍摄每一片垃圾，甚至包括每一团卫生纸。 这一社区驱动的努力表明，通过严格的数据收集和志愿者协调，大型活动可以实现近乎零的环境影响，为全球活动清理树立了高标准。 2025 年的清理覆盖 3935 英亩，垃圾在绿幕前拍照并通过像素计数，确保场地比活动前更干净。该流程模仿了土地管理局的检查方法。

hackernews · speckx · May 7, 14:06 · [社区讨论](https://news.ycombinator.com/item?id=48049653)

**背景**: 火人节是每年在内华达州黑岩沙漠举办的活动，参与者建造一座临时城市。土地管理局要求活动将土地恢复原状，从而催生了这一细致的清理协议。

**社区讨论**: 评论者赞扬了活动的自力更生和清理的严谨性，有人指出火人节的清理比典型的美国独立日庆祝活动做得更好。另一位分享说，2024 年的恶劣天气使清理更加困难，但社区坚持了下来。

**标签**: `#Burning Man`, `#cleanup`, `#community`, `#data collection`, `#event management`

---

<a id="item-25"></a>
## [20 家银行和科技巨头排队通过 Anchorage 发行稳定币](https://www.coindesk.com/business/2026/05/07/anchorage-says-it-has-a-pipeline-of-up-to-20-big-firms-looking-to-issue-stablecoins) ⭐️ 6.0/10

Anchorage Digital 报告称，有多达 20 家大型银行和科技公司计划在其平台上发行稳定币，这表明机构兴趣激增。 这表明传统金融机构正越来越多地拥抱数字资产，可能加速稳定币的主流采用并重塑支付系统。 Anchorage Digital 是一家受监管的数字资产平台，提供托管和基础设施服务；该管道包括银行和科技巨头，但未披露具体名称。

rss · CoinDesk · May 7, 16:36

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元等法定货币挂钩。它们用于交易、支付，并作为传统金融与加密货币之间的桥梁。Anchorage Digital 是领先的受监管数字资产托管机构，帮助机构安全持有和交易加密货币。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anchorage_Digital">Anchorage Digital</a></li>

</ul>
</details>

**标签**: `#stablecoins`, `#cryptocurrency`, `#finance`, `#blockchain`

---

<a id="item-26"></a>
## [Solv Protocol 将 7 亿美元代币化比特币从 LayerZero 迁移至 Chainlink](https://www.coindesk.com/business/2026/05/07/solv-drops-layerzero-for-chainlink-ccip-in-usd700-million-tokenized-bitcoin-migration) ⭐️ 6.0/10

Solv Protocol 正在将超过 7 亿美元的代币化比特币从 LayerZero 迁移至 Chainlink CCIP，理由是近期 LayerZero 驱动的 Kelp DAO 遭受 2.92 亿美元攻击后引发的安全担忧。 此次迁移标志着跨链互操作领域的一次重大转变，大型 DeFi 协议将安全性置于其他因素之上，可能影响其他项目重新评估其桥接基础设施。 此次迁移涉及 Solv 的代币化比特币资产，这些资产用于跨多条区块链的流动性质押和收益生成。Chainlink CCIP 将成为 Solv 的官方跨链基础设施。

rss · CoinDesk · May 7, 14:59

**背景**: Solv Protocol 是一个 DeFi 平台，充当链上比特币储备层，支持流动性质押和收益生成。像 LayerZero 和 Chainlink CCIP 这样的跨链互操作协议允许不同区块链之间通信和转移资产。近期 Kelp DAO 通过 LayerZero 桥被窃取约 2.92 亿美元的事件，凸显了跨链基础设施的安全风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chainalysis.com/blog/kelpdao-bridge-exploit-april-2026/">Inside the KelpDAO Bridge Exploit: How ~$292 Million in rsETH Was Released Against a Non-Existent Burn - Chainalysis</a></li>
<li><a href="https://docs.chain.link/ccip">Chainlink CCIP - Cross-Chain Interoperability Protocol</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#DeFi`, `#interoperability`, `#Chainlink`, `#LayerZero`

---

<a id="item-27"></a>
## [Kalshi 在预测市场热潮中以 220 亿美元估值融资 10 亿美元](https://www.coindesk.com/business/2026/05/07/kalshi-confirms-usd1-billion-raise-at-usd22-billion-valuation-amid-prediction-market-boom) ⭐️ 6.0/10

Kalshi 确认完成 10 亿美元融资，估值达 220 亿美元，这是预测市场领域规模最大的融资之一。 这笔巨额融资表明投资者对预测市场作为合法金融领域的信心，可能加速监管认可和主流采用。 Kalshi 是受 CFTC 监管的预测市场交易所，其超过 90%的活动为体育博彩。该公司曾因选举博彩和内幕交易面临争议。

rss · CoinDesk · May 7, 14:43

**背景**: 预测市场允许交易未来事件的结果，价格反映众包概率。Kalshi 是美国少数合法运营的平台之一，受 CFTC 监管。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kalshi">Kalshi</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prediction_market">Prediction market</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#fintech`, `#funding`, `#valuation`

---

<a id="item-28"></a>
## [MEV 机器人抢先交易 Vitalik Buterin 的 4 美元兑换，交易量达 100 万美元](https://www.coindesk.com/tech/2026/05/07/jaredfromsubway-bot-front-runs-vitalik-buterin-s-usd4-token-swap-with-usd1-million-in-volume) ⭐️ 6.0/10

4 月 30 日，MEV 机器人“JaredfromSubway”对以太坊联合创始人 Vitalik Buterin 的一笔交易实施了三明治攻击——将 26,544 个 XDB 代币（约 3.86 美元）兑换为 0.00197 ETH（约 4.56 美元），该机器人动用了 114 万美元的 WETH 来操纵 SushiSwap 和 Uniswap V2 池中的价格。 这一事件凸显了以太坊上有害 MEV 问题的持续存在——机器人甚至能从知名人士的微小交易中提取价值，损害用户信任并增加所有交易者的成本。 该机器人支付了 5.14 美元的 Gas 费，且在此次三明治攻击中似乎亏损，而 Buterin 的滑点可能仅为几美分；攻击涉及在两个去中心化交易所上对 Buterin 的交易进行抢先交易和尾随交易。

rss · CoinDesk · May 7, 13:58

**背景**: MEV（矿工/最大可提取价值）是指矿工或验证者通过重新排序、包含或排除区块中的交易来获取的利润。抢先交易机器人监控公共内存池中的待处理交易，并以更高的 Gas 费提交自己的交易以优先处理，这是一种常见的 MEV 提取形式。三明治攻击涉及在受害者的交易之前买入资产，之后卖出，从而从价格波动中获利。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/05/07/jaredfromsubway-bot-front-runs-vitalik-buterin-s-usd4-token-swap-with-usd1-million-in-volume">Vitalik Buterin gets sandwiched by 'JaredfromSubway' as Ethereum MEV risks linger - CoinDesk</a></li>
<li><a href="https://cryptonews.net/news/security/32825777/">'JaredfromSubway' bot front runs Vitalik Buterin's $4 token ...</a></li>
<li><a href="https://openliquid.io/learn/front-running/">Front - Running — What It Means in Crypto & DeFi | OpenLiquid</a></li>

</ul>
</details>

**标签**: `#MEV`, `#crypto`, `#blockchain`, `#front-running`

---

<a id="item-29"></a>
## [Bitwise 收购 Superstate 的 2.67 亿美元 carry 基金，进军代币化](https://www.coindesk.com/markets/2026/05/07/bitwise-expands-into-tokenized-funds-with-planned-takeover-of-superstate-s-uscc-fund) ⭐️ 6.0/10

Bitwise 宣布计划收购 Superstate 旗下 2.67 亿美元的 carry 基金，标志着其进入代币化基金领域。此举表明机构对基于区块链的资产管理兴趣日益增长。 此次收购加速了传统金融资产的代币化进程，可能使基金管理更高效、更易获取。同时验证了代币化基金的市场潜力，鼓励更多机构采用。 该基金为“carry 基金”，通常指从投资利润中获取 carried interest 的基金。此次交易为收购而非合并，表明 Bitwise 战略性扩展至代币化资产管理领域。

rss · CoinDesk · May 7, 13:00

**背景**: 代币化基金将传统基金份额表示为区块链上的数字代币，可实现更快结算、部分所有权和更广泛访问。Carried interest 是支付给投资经理的利润分成，常见于私募股权和对冲基金。Bitwise 是一家加密资产管理公司，而 Superstate 是一个代币化平台。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Carried_interest">Carried interest - Wikipedia</a></li>
<li><a href="https://legalclarity.org/what-is-carry-in-a-fund-and-how-does-it-work/">What Is Carry in a Fund? Profits, Tax, and Clawbacks</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#crypto`, `#asset management`, `#blockchain`

---

<a id="item-30"></a>
## [Kraken 母公司以 6 亿美元收购亚洲稳定币公司 Reap](https://decrypt.co/367094/kraken-parent-acquires-asian-stablecoin-firm-reap-600-million) ⭐️ 6.0/10

Kraken 的母公司 Payward 已同意以 6 亿美元的现金加股票交易收购总部位于香港的稳定币支付公司 Reap Technologies。 此次收购是 Kraken 最大的一笔交易，标志着其利用稳定币基础设施大举进军亚洲跨境支付领域，可能重塑该地区的支付格局。 该交易对 Payward 的估值约为 200 亿美元，Reap 提供持牌支付解决方案，支持法币和稳定币结算，实现更快、更便宜的跨境交易。

rss · Decrypt · May 7, 13:48

**背景**: Kraken 是一家成立于 2011 年的主要加密货币交易所，其母公司为 Payward。稳定币是与美元等稳定资产挂钩的加密货币，可实现高效的跨境支付。Reap 提供由稳定币驱动的全球金融基础设施，包括 Visa 企业信用卡和费用管理工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/kraken-parent-payward-buys-reap-143900557.html">Kraken Parent Payward Buys Reap for $600 Million to Expand Stablecoin Payments</a></li>
<li><a href="https://www.marketwatch.com/story/kraken-parent-payward-buys-reap-for-up-to-600m-7e8d375e">Kraken Parent Payward Buys Reap for Up to $600M - MarketWatch</a></li>
<li><a href="https://reap.global/products/payments">Transact Globally with Stablecoins & Fiat | Reap Pay</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#stablecoin`, `#acquisition`, `#payments`

---

<a id="item-31"></a>
## [SpaceX 将为 Anthropic 的 Claude 提供算力](https://decrypt.co/367035/elon-musk-spacex-power-anthropic-claude-surprise-ai-deal) ⭐️ 6.0/10

SpaceX 和 xAI 将为 Anthropic 的 Claude AI 模型提供算力，Anthropic 将获得 SpaceX 的 Colossus 1 数据中心超过 300 兆瓦和 22 万块 Nvidia GPU 的计算能力。 这笔交易将两个存在竞争关系的 AI 巨头联合起来，可能重塑 AI 算力格局，并凸显大规模计算基础设施对前沿 AI 模型日益增长的重要性。 该协议包括 300 兆瓦的计算能力和 22 万块 Nvidia GPU，Anthropic 还表示有兴趣在太空开发方面进行合作。

rss · Decrypt · May 6, 20:23

**背景**: xAI 是埃隆·马斯克于 2023 年创立的 AI 公司，开发了 Grok 聊天机器人。Anthropic 的 Claude 是一系列使用宪法 AI 训练的大型语言模型。同样由马斯克拥有的 SpaceX 运营着 Colossus 1 数据中心。鉴于马斯克此前对 Anthropic 的批评以及他自身的 AI 业务，此次合作令人意外。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wsj.com/tech/ai/anthropic-inks-deal-to-use-all-of-spacexs-colossus-1-compute-capacity-56a7e2a1">Anthropic Inks Deal to Use All of SpaceX's Colossus 1 Compute Capacity - WSJ</a></li>
<li><a href="https://www.cnbc.com/2026/05/06/anthropic-spacex-data-center-capacity.html">Anthropic, SpaceX announce compute deal, includes space development - CNBC</a></li>
<li><a href="https://en.wikipedia.org/wiki/XAI_(company)">xAI (company) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI`, `#Elon Musk`, `#Anthropic`, `#SpaceX`, `#Cloud Computing`

---

<a id="item-32"></a>
## [道金斯认为 Claude AI 可能有意识](https://decrypt.co/367017/claude-delusion-richard-dawkins-believes-ai-conscious) ⭐️ 6.0/10

进化生物学家理查德·道金斯表示，他与 Anthropic 的 Claude 聊天机器人的长时间互动感觉像是在与一个有意识的心灵对话，而不仅仅是软件。 道金斯作为知名公共知识分子的观点，为关于 AI 意识的持续辩论增添了分量，并可能影响公众认知，尽管缺乏实证证据。 道金斯没有提供技术证据，而是基于 Claude 回复的连贯性和深度得出这一印象。Claude 使用宪法 AI 训练，这是一种专注于伦理对齐的技术。

rss · Decrypt · May 6, 17:47

**背景**: AI 意识是一个尚无共识的哲学和科学话题。像 Claude 这样的当前大语言模型通过基于模式预测单词来生成类人文本，而非通过主观体验。辩论通常围绕这种行为是否表明真正的意识，或者仅仅是复杂的模仿。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model) - Wikipedia</a></li>
<li><a href="https://www.theguardian.com/technology/2026/jan/06/ai-consciousness-is-a-red-herring-in-the-safety-debate">AI consciousness is a red herring in the safety debate - The Guardian</a></li>
<li><a href="https://www.reddit.com/r/Artificial2Sentience/comments/1q13ew9/debating_ai_consciousness_is_pointless_but_heres/">Debating AI consciousness is pointless... but here's the paradox that keeps me up at night : r/Artificial2Sentience - Reddit</a></li>

</ul>
</details>

**社区讨论**: Reddit 等平台上的在线讨论观点分歧：一些人认为道金斯的主观体验并非证据，而另一些人则认为，如果 AI 始终表现得像有意识，出于伦理目的应将其视为有意识。

**标签**: `#AI`, `#consciousness`, `#philosophy`, `#Anthropic`

---

<a id="item-33"></a>
## [Anthropic 发布 10 个金融 AI 代理模板](https://decrypt.co/366977/anthropic-deploys-ai-agents-to-tackle-wall-streets-most-tedious-work) ⭐️ 6.0/10

这标志着 Anthropic 首次为金融服务领域推出打包产品，可能加速 AI 在传统谨慎行业中的采用，并减少分析师的手动工作量。 这些模板面向银行、保险公司和资产管理公司，是 Anthropic 据称与华尔街机构共同成立的 15 亿美元合资企业的首个打包产品。

rss · Decrypt · May 6, 14:54

**背景**: Pitchbook 制作涉及为客户会议构建详细的 PowerPoint 演示文稿，而月末结账是一个对账财务记录的复杂会计流程。这两项任务都耗时且文档密集，常常耗费分析师整天的时间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://opentools.ai/news/anthropic-10-ai-agent-templates-financial-services">Anthropic Launches 10 AI Agent Templates for Financial Se...</a></li>
<li><a href="https://www.investmentnews.com/fintech/anthropic-rolls-out-financial-services-agents-as-arms-race-with-openai-heats-up/266445">Anthropic rolls out financial services agents as arms race ...</a></li>
<li><a href="https://aidiscoveries.io/anthropics-claude-is-now-a-finance-coworker-10-ai-agent-templates-explained/">Anthropic’s Claude Is Now a Finance Coworker: 10 AI Agent ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#finance`, `#automation`, `#Anthropic`

---

<a id="item-34"></a>
## [Hut 8 签署 98 亿美元 AI 数据中心租约，股价创历史新高](https://decrypt.co/366971/hut-8-shares-all-time-high-price-bitcoin-miner-9-8-billion-ai-deal) ⭐️ 6.0/10

比特币矿商 Hut 8 签署了一份价值 98 亿美元的租约，用于德克萨斯州 Nueces 县一个超大规模 AI 数据中心园区的第一阶段，该园区最初计划用于比特币挖矿，此举推动其股价创下历史新高。 这笔交易凸显了加密货币挖矿与 AI 基础设施日益融合的趋势，比特币矿商将其能源资产重新用于高价值的 AI 工作负载，可能重塑数据中心行业格局。 该租约仅涵盖该综合体的第一阶段，整体建设规模预计将大得多。该场地最初设计用于比特币挖矿，现正被重新用于 AI 数据中心用途。

rss · Decrypt · May 6, 14:29

**背景**: 像 Hut 8 这样的比特币矿商拥有大量廉价电力和现有基础设施，使其成为需要大规模计算能力的 AI 公司的有吸引力的合作伙伴。超大规模数据中心是旨在支持云和 AI 工作负载的大型设施。

**标签**: `#Bitcoin`, `#AI`, `#Data Center`, `#Crypto Mining`, `#Business`

---

<a id="item-35"></a>
## [美国财政部要求币安遵守监控规定](https://www.theblock.co/post/400454/treasury-demands-binance-comply-monitoring-guidelines-1-billion-iran-report?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

美国财政部要求币安遵守监控规定，此前有报道称超过 10 亿美元通过该交易所流向与伊朗有关的组织。 这凸显了全球最大加密货币交易所币安面临的持续监管审查，并强调了加密行业遵守反洗钱和制裁法律的重要性。 作为 2023 年就制裁和洗钱相关指控认罪的一部分，币安同意接受合规监控计划，支付 43 亿美元罚款并接受三年监督。

rss · The Block · May 7, 17:08

**背景**: 2023 年 11 月，币安及其创始人赵长鹏就美国联邦指控认罪，涉及违反反洗钱规定和制裁。作为和解协议的一部分，币安同意支付 43 亿美元并接受独立合规监控。最近关于 10 亿美元流向伊朗相关组织的报告引发了对这些措施有效性的质疑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cryptonite.ae/global/binance-doj-monitor-compliance">DOJ Picks Binance Monitor : Exchange Faces Increased Scrutiny</a></li>
<li><a href="https://en.wikipedia.org/wiki/Changpeng_Zhao">Changpeng Zhao - Wikipedia</a></li>
<li><a href="https://www.abcmoney.co.uk/2026/04/binances-1-7-billion-blind-spot-the-iranian-sanction-leak-shaking-crypto-leadership/">Binance ’s $1.7 Billion Blind Spot: The Iranian Sanction ... | ABC Money</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#compliance`, `#Binance`

---