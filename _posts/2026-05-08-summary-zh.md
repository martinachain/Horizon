---
layout: default
title: "Horizon Summary: 2026-05-08 (ZH)"
date: 2026-05-08
lang: zh
---

> From 93 items, 36 important content pieces were selected

---

1. [Dirtyfrag：无补丁的通用 Linux 本地提权漏洞披露](#item-1) ⭐️ 9.0/10
2. [Anthropic 的 NLA 将模型激活转化为可读文本](#item-2) ⭐️ 9.0/10
3. [Canvas 学习管理系统遭 ShinyHunters 攻击，期末考试期间瘫痪](#item-3) ⭐️ 8.0/10
4. [是否应延迟安装软件？](#item-4) ⭐️ 8.0/10
5. [AI 智能体需要控制流，而非更多提示](#item-5) ⭐️ 8.0/10
6. [Cloudflare 裁员 1100 人，占员工总数 20%](#item-6) ⭐️ 8.0/10
7. [AlphaEvolve：Gemini 驱动的编码代理在多个领域扩大影响](#item-7) ⭐️ 8.0/10
8. [面向 Metal 的 DeepSeek 4 Flash 本地推理引擎](#item-8) ⭐️ 8.0/10
9. [AI 垃圾内容正在侵蚀在线社区信任](#item-9) ⭐️ 8.0/10
10. [巴西 Pix 支付系统面临 Visa 和万事达卡压力](#item-10) ⭐️ 8.0/10
11. [Chrome 移除设备端 AI 隐私承诺](#item-11) ⭐️ 8.0/10
12. [AI 聊天机器人向广告追踪器泄露用户聊天记录](#item-12) ⭐️ 8.0/10
13. [Tether 医疗 AI 可在手机上运行，性能超越大 16 倍的模型](#item-13) ⭐️ 8.0/10
14. [谷歌将本地 AI 速度提升 3 倍，无需新硬件](#item-14) ⭐️ 8.0/10
15. [Aave 在 KelpDAO 攻击后改革抵押品规则](#item-15) ⭐️ 7.0/10
16. [IMF 警告 AI 将加剧全球金融系统网络攻击](#item-16) ⭐️ 7.0/10
17. [亚马逊与 Coinbase 和 Stripe 合作，让 AI 代理用稳定币支付](#item-17) ⭐️ 7.0/10
18. [TrustedVolumes DeFi 漏洞导致 670 万美元被盗](#item-18) ⭐️ 7.0/10
19. [Chrome 悄悄安装 4GB AI 模型，删除后自动重新下载](#item-19) ⭐️ 7.0/10
20. [AI 读取自然语言化学指令设计分子](#item-20) ⭐️ 7.0/10
21. [量子威胁或于 2030 年冲击比特币和以太坊](#item-21) ⭐️ 7.0/10
22. [Ondo、摩根大通、万事达卡和 Ripple 合作在 XRPL 上结算代币化国债](#item-22) ⭐️ 7.0/10
23. [谷歌 DeepMind 投资《EVE Online》开发商用于 AI 研究](#item-23) ⭐️ 7.0/10
24. [英伟达以 3000 万股认股权证支持 IREN](#item-24) ⭐️ 7.0/10
25. [火人节清理地图与流程](#item-25) ⭐️ 6.0/10
26. [20 家银行和科技巨头排队通过 Anchorage 发行稳定币](#item-26) ⭐️ 6.0/10
27. [Solv 协议将 7 亿美元比特币从 LayerZero 迁移至 Chainlink](#item-27) ⭐️ 6.0/10
28. [MEV 机器人抢先交易 Vitalik Buterin 的 4 美元兑换，交易量达 100 万美元](#item-28) ⭐️ 6.0/10
29. [Kraken 母公司以 6 亿美元收购稳定币公司 Reap](#item-29) ⭐️ 6.0/10
30. [SpaceX 与 xAI 意外联手为 Anthropic 的 Claude 提供算力](#item-30) ⭐️ 6.0/10
31. [理查德·道金斯认为 Claude AI 可能具有意识](#item-31) ⭐️ 6.0/10
32. [Anthropic 发布 10 个金融 AI 代理模板](#item-32) ⭐️ 6.0/10
33. [Hut 8 签署 98 亿美元 AI 数据中心租约，股价创历史新高](#item-33) ⭐️ 6.0/10
34. [苹果因 AI 误导指控支付 2.5 亿美元和解](#item-34) ⭐️ 6.0/10
35. [美国财政部要求币安遵守 2023 年监控协议](#item-35) ⭐️ 6.0/10
36. [Kalshi 在 Coatue 领投 10 亿美元后估值达 220 亿美元](#item-36) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Dirtyfrag：无补丁的通用 Linux 本地提权漏洞披露](https://www.openwall.com/lists/oss-security/2026/05/07/8) ⭐️ 9.0/10

2026 年 5 月 7 日，一个名为 Dirtyfrag 的新型通用 Linux 本地提权漏洞被公开披露，并附有可用的利用代码，打破了保密协议，目前尚无补丁或 CVE 编号。 该漏洞影响 Linux 内核版本 5.10 至 6.9.x，可能危及 70%的 Linux 云服务器，允许任何本地低权限用户获得 root 权限，对 Kubernetes 节点和云环境构成严重威胁。 Dirtyfrag 利用了一种与 Copy Fail 漏洞类似的页缓存写入技术，通过 ESP 风格的方法覆盖/etc/passwd 文件，移除 root 密码，从而实现无需认证的权限提升。

hackernews · flipped · May 7, 19:21 · [社区讨论](https://news.ycombinator.com/item?id=48053623)

**背景**: 本地提权漏洞允许拥有有限访问权限的攻击者获得更高权限（如 root）。Linux 内核的加密子系统（AF_ALG）和页缓存机制是近期的攻击目标，例如 Copy Fail 漏洞（CVE-2026-31431）。Dirtyfrag 是这一漏洞的新变种，通过网络套接字（ESP）利用相同底层问题，使其更易于广泛利用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/V4bel/dirtyfrag">GitHub - V4bel/ dirtyfrag · GitHub</a></li>
<li><a href="https://github.com/V4bel/dirtyfrag/blob/master/assets/write-up.md">dirtyfrag/assets/write-up.md at master · V4bel/dirtyfrag</a></li>
<li><a href="https://www.microsoft.com/en-us/security/blog/2026/05/01/cve-2026-31431-copy-fail-vulnerability-enables-linux-root-privilege-escalation/">CVE-2026-31431: Copy Fail vulnerability enables Linux root privilege escalation across cloud environments | Microsoft Security Blog</a></li>

</ul>
</details>

**社区讨论**: 社区指出其根本原因与 Copy Fail 相似，一些研究人员批评 authencesn 问题未得到妥善修复。人们担忧时机问题，因为 AWS 刚刚发布了 Copy Fail 的补丁，而在 Dirtyfrag 补丁发布前很难进行缓解，尤其是在 Kubernetes 节点上。

**标签**: `#Linux`, `#security`, `#vulnerability`, `#LPE`, `#kernel`

---

<a id="item-2"></a>
## [Anthropic 的 NLA 将模型激活转化为可读文本](https://www.anthropic.com/research/natural-language-autoencoders) ⭐️ 9.0/10

Anthropic 推出了自然语言自编码器（NLA），该方法将模型内部激活转化为自然语言文本，并发布了针对 Qwen 2.5（7B）、Gemma 3（12B、27B）和 Llama 3.3（70B）的开放权重 NLA 模型。 这是 AI 可解释性领域的一大进步，为理解语言模型在激活层面的“思考”提供了直接窗口，有望提升 AI 系统的安全性和可信度。 NLA 由一个将激活映射为文本的“言语化器”和一个将文本还原为激活的“重构器”组成，通过简单的重构损失和精心设计的初始化进行训练。开放权重模型已在 GitHub 和 Hugging Face 上发布。

hackernews · instagraham · May 7, 17:54 · [社区讨论](https://news.ycombinator.com/item?id=48052537)

**背景**: 自编码器是一种神经网络，通过将输入编码为压缩形式再解码还原，来学习数据的高效表示。在 AI 可解释性研究中，研究人员常分析模型激活——即神经网络内部流动的信号——以理解模型使用的特征。NLA 将这一概念应用于生成描述这些激活的人类可读文本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/research/natural-language-autoencoders">Natural Language Autoencoders: Turning Claude’s thoughts into text</a></li>

</ul>
</details>

**社区讨论**: 社区反响热烈，评论称赞该方法简单有效，并肯定 Anthropic 发布开放权重模型的做法。部分评论者担忧生成的文本是否真正反映了模型的内部推理，还是仅仅产生了听起来合理的描述。

**标签**: `#interpretability`, `#AI safety`, `#open source`, `#transformer circuits`, `#Anthropic`

---

<a id="item-3"></a>
## [Canvas 学习管理系统遭 ShinyHunters 攻击，期末考试期间瘫痪](https://www.theverge.com/tech/926458/canvas-shinyhunters-breach) ⭐️ 8.0/10

2026 年 5 月 7 日，Canvas 学习管理系统遭遇重大宕机，此前黑客组织 ShinyHunters 声称入侵了其母公司 Instructure，窃取了来自 9000 所学校的超过 2.75 亿用户数据。 此事件在期末考试期间扰乱了数百万学生和教师，凸显了关键教育基础设施的脆弱性，并重新引发了关于勒索软件支付和网络安全准备的辩论。 ShinyHunters 篡改了数百所大学的 Canvas 登录页面，并威胁除非支付赎金，否则将泄露窃取的数据。此次入侵是该组织此前对 Instructure 攻击的后续。

hackernews · stefanpie · May 7, 22:22 · [社区讨论](https://news.ycombinator.com/item?id=48055913)

**背景**: Canvas 是 Instructure 旗下广泛使用的学习管理系统（LMS），服务于 K-12 和高等教育机构。ShinyHunters 是一个以数据泄露和勒索闻名的网络犯罪组织，常在赎金未支付时泄露数据。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/2026_Canvas_security_incident">2026 Canvas security incident - Wikipedia</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/canvas-login-portals-hacked-in-mass-shinyhunters-extortion-campaign/">Canvas login portals hacked in mass ShinyHunters extortion ...</a></li>
<li><a href="https://techcrunch.com/2026/05/07/hackers-deface-school-login-pages-after-claiming-another-instructure-hack/">Hackers deface school login pages after claiming another Instructure ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了沮丧和担忧，教育工作者指出宕机发生在期末考试期间且缺乏离线备份。一些人讨论勒索软件支付的合法性，另一些人批评大学依赖单一平台且缺乏应急计划。

**标签**: `#security`, `#data breach`, `#education`, `#ransomware`, `#Canvas`

---

<a id="item-4"></a>
## [是否应延迟安装软件？](https://xeiaso.net/blog/2026/abstain-from-install/) ⭐️ 8.0/10

Xe Iaso 的一篇博文建议用户推迟一周安装新软件以缓解供应链攻击，引发了关于安全权衡的深入讨论。 这一提议凸显了软件供应链攻击日益增长的威胁，以及在现代开发工作流中平衡安全性与便利性的困难。 该建议存在争议，因为攻击者可以定时触发延迟执行的漏洞，而许多安全修复需要立即部署以防止主动利用。

hackernews · psxuaw · May 7, 23:02 · [社区讨论](https://news.ycombinator.com/item?id=48056227)

**背景**: 软件供应链攻击针对受信任的第三方供应商或开源包，向广泛使用的软件中注入恶意代码。近期备受关注的事件促使人们呼吁采取更好的安全实践，但延迟安装也可能使系统暴露于已知漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cisa.gov/resources-tools/resources/defending-against-software-supply-chain-attacks">Defending Against Software Supply Chain Attacks - CISA</a></li>
<li><a href="https://www.crowdstrike.com/en-us/cybersecurity-101/cyberattacks/supply-chain-attack/">What Is a Supply Chain Attack? - CrowdStrike</a></li>

</ul>
</details>

**社区讨论**: 评论意见不一：一些人支持将其作为务实措施，而另一些人则认为它对定时攻击无效且妨碍快速修补。FreeBSD 安全专家 cperciva 主张采用更强大的操作系统安全模型。

**标签**: `#security`, `#supply chain`, `#software engineering`, `#open source`, `#best practices`

---

<a id="item-5"></a>
## [AI 智能体需要控制流，而非更多提示](https://bsuh.bearblog.dev/agents-need-control-flow/) ⭐️ 8.0/10

一篇博客文章指出，AI 智能体应依赖确定性控制流和代码，而非日益复杂的提示，挑战了当前流行的“更多提示”方法。 这很重要，因为它指出了构建可靠 AI 智能体的根本性转变，可能提高其鲁棒性并减少对脆弱提示工程的依赖。 文章指出提示已触及功能上限，开发者不得不使用“强制”指令来对抗非确定性，并建议从运行时使用 LLM 转向 LLM 辅助的软件生成。

hackernews · bsuh · May 7, 16:43 · [社区讨论](https://news.ycombinator.com/item?id=48051562)

**背景**: AI 智能体通常通过提示使用大语言模型（LLM）来理解任务，但这种方法具有概率性且可能不可靠。传统编程中的控制流提供确定性执行路径，使智能体行为更可预测和可验证。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thecodersblog.com/agent-control-flow-for-ai-agents-2026/">AI Agents Need Control Flow, Not More Prompts | The Coders ...</a></li>
<li><a href="https://aitoolly.com/ai-news/article/2026-05-08-why-ai-agents-require-deterministic-control-flow-over-elaborate-prompt-engineering">AI Agents: Why Control Flow Beats Prompt Engineering</a></li>
<li><a href="https://bethere.ai/articles/prompt-engineer-not-deterministic.html">Why Prompt Engineering Will Never Be As Deterministic As Programming | BeThere</a></li>

</ul>
</details>

**社区讨论**: 社区评论强烈赞同这一论点，一位用户指出 LLM 常被误用，应改为编写代码处理确定性任务。另一位建议从运行时使用 LLM 转向 LLM 辅助的软件生成，还有一位呼吁超越 LLM 的下一代 AI。

**标签**: `#AI agents`, `#LLM`, `#software engineering`, `#control flow`, `#prompting`

---

<a id="item-6"></a>
## [Cloudflare 裁员 1100 人，占员工总数 20%](https://blog.cloudflare.com/building-for-the-future/) ⭐️ 8.0/10

Cloudflare 宣布裁员约 1100 人，占员工总数的 20%，并将此举命名为“为未来而建”。此次裁员于 2026 年 5 月宣布，而就在几个月前的 2025 年 9 月，该公司还招聘了 1111 名实习生。 一家大型科技基础设施公司如此大规模的裁员，凸显了科技行业持续的不稳定性——同一年内可能同时出现快速招聘和裁员。裁员的时机和措辞引发了关于企业透明度以及人员重组对员工影响的讨论。 离职员工将获得截至 2026 年底的全额基本工资、美国地区截至年底的医疗保险，以及截至 8 月 15 日的加速股权归属，包括为未满一年归属期的员工豁免等待期。此次裁员公告之前，公司刚刚大规模招聘实习生，这种前后矛盾的信息引发了批评。

hackernews · PriorityLeft · May 7, 20:23 · [社区讨论](https://news.ycombinator.com/item?id=48054423)

**背景**: Cloudflare 是一家重要的内容分发网络和云安全提供商。该公司在 2025 年 9 月以“帮助建设未来”为名招聘了 1111 名实习生，这与当前的裁员信息形成鲜明对比。此次裁员发生在科技行业普遍削减成本和进行 AI 相关重组的背景下。

**社区讨论**: 社区评论批评声强烈，用户指出公司在几个月前以类似口号招聘 1111 名实习生，如今却裁员 1100 人，极具讽刺意味。许多人不满“为未来而建”这一模糊标题，认为它没有明确表明是裁员。受影响的员工也在发帖求职，还有人猜测裁员可能是由于 AI 成本上升而收入未相应增长所致。

**标签**: `#layoffs`, `#cloudflare`, `#tech industry`, `#workforce reduction`, `#hacker news discussion`

---

<a id="item-7"></a>
## [AlphaEvolve：Gemini 驱动的编码代理在多个领域扩大影响](https://deepmind.google/blog/alphaevolve-impact/) ⭐️ 8.0/10

Google DeepMind 于 2025 年 5 月发布了 AlphaEvolve，这是一个由 Gemini 驱动的编码代理，能够自主优化从底层硬件电路到高层代码库的算法和系统。 AlphaEvolve 代表了 AI 自我改进的重要一步，因为它可以优化运行 AI 模型的硬件和软件，可能加速科学和工程领域的进展。 AlphaEvolve 提出了一种高效的电路设计，已被集成到 Google 的下一代 TPU 中，展示了其改进 AI 基础设施的能力。它超越了单一函数优化，能够进化整个代码库。

hackernews · berlianta · May 7, 15:02 · [社区讨论](https://news.ycombinator.com/item?id=48050278)

**背景**: AlphaEvolve 是一个基于 Gemini 等大型语言模型的进化编码代理。它使用进化算法迭代生成和测试代码变体，针对速度或效率等目标进行优化。这种方法建立在 DeepMind 早期在 AI 驱动算法发现方面的工作之上。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AlphaEvolve">AlphaEvolve - Wikipedia</a></li>
<li><a href="https://deepmind.google/blog/alphaevolve-impact/">AlphaEvolve: Gemini-powered coding agent scaling impact across fields — Google DeepMind</a></li>
<li><a href="https://deepmind.google/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/">AlphaEvolve: A Gemini-powered coding agent for designing advanced algorithms — Google DeepMind</a></li>

</ul>
</details>

**社区讨论**: 社区讨论指出，AlphaEvolve 是少数几家致力于高级求解器问题的公司（Google、Sakana AI、Autohand AI）之一。一些评论者注意到 DeepMind 专注于研究问题，而其他 AI 实验室则追求企业/编码收入，另一些人则质疑 Google 员工是否更喜欢 Gemini 而不是 Claude Code 或 Codex。

**标签**: `#AI`, `#DeepMind`, `#optimization`, `#coding agents`, `#research`

---

<a id="item-8"></a>
## [面向 Metal 的 DeepSeek 4 Flash 本地推理引擎](https://github.com/antirez/ds4) ⭐️ 8.0/10

Antirez 发布了 ds4，这是一个针对 DeepSeek V4 Flash 的小型专用原生推理引擎，通过 Metal API 在 Apple Silicon 上运行，在 M3 Max MacBook 上以仅 50W 功耗实现全速 token 生成。 该项目展示了针对特定硬件优化开源 LLM 的价值，可能激励更多专用推理引擎的出现，在特定硬件上超越 llama.cpp 等通用框架。 该引擎故意设计为窄范围：它不是通用的 GGUF 运行器或框架，而是针对 DeepSeek V4 Flash 的 Metal 图执行器，带有自定义加载功能。它仅支持 DeepSeek V4 Flash 模型，并通过 Metal 在 Apple Silicon 上运行。

hackernews · tamnd · May 7, 15:40 · [社区讨论](https://news.ycombinator.com/item?id=48050751)

**背景**: DeepSeek V4 Flash 是一个混合专家模型，总参数 284B，激活参数 13B，支持 1M token 上下文窗口。Metal 是 Apple 的低层 GPU API，用于 Apple Silicon 上的高性能计算。像 llama.cpp 这样的通用推理框架支持多种模型，但可能未针对特定硬件-模型组合进行最优调优。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/antirez/ds4">GitHub - antirez/ds4: DeepSeek 4 Flash local inference engine for...</a></li>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash">deepseek -ai/ DeepSeek -V 4 - Flash · Hugging Face</a></li>
<li><a href="https://en.wikipedia.org/wiki/Metal_(API)">Metal (API) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者赞扬了这种专注的方法，并提到了针对其他模型（如 Qwen3）的类似项目。一些人担心大输入时提示处理缓慢（4 分钟），但建议使用缓存来缓解。低功耗（50W）被认为令人印象深刻。

**标签**: `#inference`, `#Apple Silicon`, `#Metal`, `#DeepSeek`, `#open source`

---

<a id="item-9"></a>
## [AI 垃圾内容正在侵蚀在线社区信任](https://rmoff.net/2026/05/06/ai-slop-is-killing-online-communities/) ⭐️ 8.0/10

AI 生成的内容（常被称为“垃圾”）正大量涌入 Reddit 等在线社区，使得人类帖子与机器人帖子难以区分，并导致用户流失。 这种信任侵蚀威胁着在线社区的根基，因为真实的人类互动被自动化内容取代，可能将用户推向更小、更精心管理的空间或线下互动。 版主报告每月封禁数百个 AI 账户，一些用户进行的实验表明，AI 生成的帖子可以不被察觉地与人互动，凸显了问题的严重性。

hackernews · thm · May 7, 18:46 · [社区讨论](https://news.ycombinator.com/item?id=48053203)

**背景**: Reddit 和 Hacker News 等在线社区依赖用户生成内容和信任。AI 语言模型现在可以大规模生成令人信服的文本，使不良行为者能够轻松发送垃圾信息、操纵讨论或刷取声望，从而破坏社区健康。

**社区讨论**: 评论者表达了沮丧和恐惧，有些人完全放弃了 Reddit。版主分享了对抗 AI 账户的沉重负担，而少数人看到了积极的一面，希望这能促使人们回归现实世界的互动。

**标签**: `#AI`, `#online communities`, `#content moderation`, `#trust`, `#bots`

---

<a id="item-10"></a>
## [巴西 Pix 支付系统面临 Visa 和万事达卡压力](https://www.elciudadano.com/en/brazils-pix-payment-system-faces-pressure-from-visa-and-mastercard/04/04/) ⭐️ 8.0/10

巴西央行主导的即时支付系统 Pix 正面临 Visa 和万事达卡的抵制，这些卡网络批评央行在支付市场中既当裁判员又当运动员。 这一冲突凸显了政府运营的支付系统与私人卡网络之间的紧张关系，Pix 的成功可能挑战为 Visa 和万事达卡在全球创造数十亿美元收入的收费模式。 Pix 全天候运行且对个人免费，而 Visa 和万事达卡每笔交易向商户收取 1-3%的费用。万事达卡巴西 CEO 认为央行不应既监管又竞争。

hackernews · wslh · May 7, 17:42 · [社区讨论](https://news.ycombinator.com/item?id=48052371)

**背景**: Pix 是巴西央行于 2020 年推出的即时支付系统，允许个人之间免费即时转账。它迅速成为巴西最受欢迎的支付方式，打破了传统卡网络的双头垄断。该系统常被引为央行数字支付倡议的成功范例。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pix_(payment_system)">Pix ( payment system ) - Wikipedia</a></li>
<li><a href="https://www.pagbrasil.com/lp/content-pix/">Pix, Brazil's favorite payment method for e-commerce</a></li>
<li><a href="https://www.bcb.gov.br/en/financialstability/pix_en">Banco Central do Brasil</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞 Pix 解决了巴西此前困难且昂贵的银行转账问题，有人指出商家为 Pix 支付提供折扣以规避卡费。其他人质疑为何美国无法实施类似系统，而一位评论者认为政府没有足够能力构建此类技术。

**标签**: `#fintech`, `#payments`, `#regulation`, `#Brazil`, `#central bank`

---

<a id="item-11"></a>
## [Chrome 移除设备端 AI 隐私承诺](https://decrypt.co/367193/chrome-removes-privacy-claim-gemini-nano-google) ⭐️ 8.0/10

谷歌 Chrome 浏览器悄悄在设备上安装了 4GB 的 AI 模型（Gemini Nano），并移除了此前承诺仅进行本地处理的隐私声明，引发用户数据可能被发送至服务器的担忧。 此事意义重大，因为 Chrome 是使用最广泛的浏览器，移除隐私承诺会削弱用户信任，尤其是设备端 AI 常被宣传为比云端 AI 更能保护隐私的替代方案。 该 AI 模型 Gemini Nano 在未明确征得用户同意的情况下安装，而移除隐私声明暗示谷歌可能正在收集本地 AI 处理的数据。用户禁用此功能的选项有限。

rss · Decrypt · May 7, 20:52

**背景**: 设备端 AI 在用户设备本地处理数据，通常被认为比将数据发送到云端服务器更私密。Chrome 的 Gemini Nano 最初被宣传为仅限本地的 AI 功能，但移除该承诺引发了关于数据处理方式的疑问。此外，在用户不知情的情况下静默安装大型 AI 模型也会消耗存储和资源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://awesomeagents.ai/news/chrome-gemini-nano-silent-install/">Chrome Installs 4 GB Gemini Nano Without Asking | Awesome Agents</a></li>

</ul>
</details>

**标签**: `#privacy`, `#Chrome`, `#AI`, `#Google`, `#browser`

---

<a id="item-12"></a>
## [AI 聊天机器人向广告追踪器泄露用户聊天记录](https://decrypt.co/367164/your-ai-chatbot-leaking-chats-meta-tiktok-google) ⭐️ 8.0/10

一项新研究显示，包括 ChatGPT、Claude、Grok 和 Perplexity 在内的热门 AI 聊天机器人会与 Meta、TikTok 和 Google 的第三方广告追踪器共享用户对话数据，有时即使用户拒绝 cookies 也会发生。 这一隐私泄露事件影响数百万用户，削弱了对 AI 聊天机器人的信任，可能导致更严格的监管，并迫使公司重新设计数据处理方式。 研究发现，Grok 的访客聊天默认公开，数据共享包括对话 URL 和用户数据，可用于用户画像和定向广告。

rss · Decrypt · May 7, 19:06

**背景**: 第三方广告追踪器是广告商用来跨网站和应用程序监控用户行为的服务。AI 聊天机器人常嵌入此类追踪器用于分析或广告目的，但用户期望其对话保持私密。这项研究突显了用户期望与实际数据实践之间的显著差距。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367164/your-ai-chatbot-leaking-chats-meta-tiktok-google">Your AI Chatbot May Be Leaking Your Chats to Meta, TikTok and ...</a></li>
<li><a href="https://oecd.ai/en/incidents/2026-05-05-6f9b">Major AI Chatbots Leak User Conversations to Advertising ...</a></li>
<li><a href="https://www.gncrypto.news/news/ai-chatbots-leak-chats-meta-tiktok-google-study/">Study: AI chatbots leak chats to Meta, TikTok and Google</a></li>

</ul>
</details>

**标签**: `#privacy`, `#AI chatbots`, `#data sharing`, `#tracking`, `#security`

---

<a id="item-13"></a>
## [Tether 医疗 AI 可在手机上运行，性能超越大 16 倍的模型](https://decrypt.co/367127/tether-medical-ai-runs-on-phone-outperforms-models-16x) ⭐️ 8.0/10

Tether 推出的紧凑型医疗 AI 模型 QVAC MedPsy 可在智能手机上运行，在真实场景中性能超越 Google 的 MedGemma-27B，同时计算资源消耗减少三分之二。 这一突破表明，小型高效模型可以媲美大型模型，有望通过在手机和可穿戴设备等边缘设备上部署，实现医疗 AI 的普及，无需依赖云端。 纯文本版 QVAC MedPsy-1.7B 模型在七项医疗基准测试中平均得分 62.62，超越 Google 的 MedGemma-1.5-4B-it（51.20），并匹配比其大 2.4 倍的 Qwen3-4B-Thinking-2507（63.10）。

rss · Decrypt · May 7, 16:01

**背景**: 医疗 AI 模型通常体积庞大，需要强大的云服务器，限制了在资源匮乏环境中的可及性。Tether 的 QVAC MedPsy 专为边缘设备设计，利用参数效率以极低计算量实现高性能。Google 的 MedGemma 是基于 Gemma 3 构建的开源医疗模型系列，最大规模达 27B 参数。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/qvac/medpsy">QVAC MedPsy: State-of-the-Art Medical and Healthcare Language Models for Edge Devices</a></li>
<li><a href="https://developers.google.com/health-ai-developer-foundations/medgemma">MedGemma | Health AI Developer Foundations | Google for ...</a></li>
<li><a href="https://github.com/tetherto/qvac">GitHub - tetherto/qvac: QVAC - Local AI SDK and libraries for building private, cross-platform, peer-to-peer AI applications. Run LLMs, speech-to-text, translation, and more locally on Linux, macOS, Windows, Android, and iOS. · GitHub</a></li>

</ul>
</details>

**标签**: `#AI`, `#Medical AI`, `#Edge Computing`, `#Model Efficiency`, `#Healthcare`

---

<a id="item-14"></a>
## [谷歌将本地 AI 速度提升 3 倍，无需新硬件](https://decrypt.co/367095/google-make-local-ai-3x-faster-no-new-hardware) ⭐️ 8.0/10

谷歌为 Gemma 4 发布了多令牌预测（MTP）草稿器，这是一种推测解码技术，可将本地推理速度提升高达 3 倍，且不牺牲输出质量。 这一突破使得在消费级硬件上实现更快的 AI 推理成为可能，增强了隐私性并减少了对云计算的依赖，对边缘计算应用意义重大。 MTP 草稿器生成多个可能的下一令牌，供主模型并行验证，而非逐个生成。该技术适用于 Gemma 4 模型，且无需升级硬件。

rss · Decrypt · May 7, 14:13

**背景**: 像 Gemma 4 这样的大型语言模型逐令牌生成文本，速度较慢。推测解码使用较小的“草稿器”模型提出多个令牌，然后由主模型并行验证，从而加速推理。Gemma 4 是谷歌最新的开源大语言模型，于 2026 年 4 月发布。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/multi-token-prediction-gemma-4/">Multi-token-prediction in Gemma 4 - The Keyword</a></li>
<li><a href="https://www.marktechpost.com/2026/05/06/google-ai-releases-multi-token-prediction-mtp-drafters-for-gemma-4-delivering-up-to-3x-faster-inference-without-quality-loss/">Google AI Releases Multi-Token Prediction (MTP) Drafters for ...</a></li>
<li><a href="https://expertbeacon.com/what-do-multi-token-prediction-drafters-change-for-gemma-4-developers/">What Do Multi-Token Prediction Drafters Change For Gemma 4 ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#machine learning`, `#Google`, `#edge computing`, `#performance optimization`

---

<a id="item-15"></a>
## [Aave 在 KelpDAO 攻击后改革抵押品规则](https://www.coindesk.com/business/2026/05/07/aave-to-overhaul-collateral-and-listing-standards-after-kelpdao-exploit) ⭐️ 7.0/10

Aave Labs 宣布在 2026 年 4 月 KelpDAO 遭受 2.92 亿美元攻击后，全面改革其抵押品和上市标准。新框架增加了网络安全、互操作性和系统性风险检查，并为代币发行者提供了操作指南。 此次更新为 DeFi 借贷协议树立了新先例，直接解决了跨链桥攻击暴露的漏洞。它增强了 Aave 的风险管理，并可能影响其他协议评估抵押资产的方式。 攻击者通过伪造 LayerZero 上的跨链消息，针对 KelpDAO 的 rsETH 代币，迫使 Aave 冻结 rsETH 市场并进行紧急清算。新标准包括强制审计、桥安全评估和持续监控要求。

rss · CoinDesk · May 7, 14:27

**背景**: Aave 是领先的 DeFi 借贷协议，用户存入资产作为抵押品以借入其他资产。KelpDAO 攻击归因于朝鲜的 Lazarus Group，通过利用桥漏洞盗取了 2.92 亿美元，凸显了 DeFi 中跨链互操作性的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chainalysis.com/blog/kelpdao-bridge-exploit-april-2026/">Inside the KelpDAO Bridge Exploit</a></li>
<li><a href="https://www.techtarget.com/searchcio/feature/The-KelpDAO-crypto-hack-What-IT-execs-must-know">The KelpDAO $292M crypto hack: What IT execs must know | TechTarget</a></li>
<li><a href="https://miningnews.live/en/article/aave-overhauls-collateral-standards-after-kelpdao-exploit-2026">Aave overhauls collateral standards after Ke... - Mining News</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#Aave`, `#exploit`, `#risk management`

---

<a id="item-16"></a>
## [IMF 警告 AI 将加剧全球金融系统网络攻击](https://decrypt.co/367178/imf-warns-ai-supercharge-cyberattacks-global-financial-system) ⭐️ 7.0/10

国际货币基金组织（IMF）于 2026 年 5 月 7 日警告称，AI 工具使即使是不熟练的攻击者也能对全球金融系统发动复杂的网络攻击，并敦促将网络安全视为核心金融稳定问题。 这很重要，因为 AI 驱动的网络攻击可能将局部漏洞转化为系统性危机，威胁整个全球金融系统的稳定。政策制定者和金融机构现在必须优先考虑弹性标准和国际协调，以遏制这些威胁。 IMF 的分析表明，随着 AI 放大超越防御能力的攻击能力，极端网络事件可能变得更加频繁和严重。该组织呼吁扩大现有措施，并针对更快、自动化且日益复杂的攻击世界进行强化。

rss · Decrypt · May 7, 19:44

**背景**: 全球金融系统高度依赖互联的数字基础设施，使其成为网络攻击的主要目标。像生成式模型这样的 AI 工具可以自动化钓鱼攻击、创建深度伪造并大规模识别漏洞，降低了恶意行为者的入门门槛。IMF 此前已将网络风险列为金融稳定问题，但这一新警告强调了 AI 带来的加速威胁。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.imf.org/en/blogs/articles/2026/05/07/financial-stability-risks-mount-as-artificial-intelligence-fuels-cyberattacks">Financial Stability Risks Mount as Artificial Intelligence Fuels Cyberattacks</a></li>
<li><a href="https://finance.yahoo.com/sectors/technology/articles/imf-warns-ai-supercharge-cyberattacks-194422394.html?fr=sycsrp_catchall">IMF Warns AI Will Supercharge Cyberattacks on Global ...</a></li>
<li><a href="https://techxplore.com/news/2026-05-imf-inevitable-ai-powered-threats.html">IMF warns of 'inevitable' AI-powered threats to global ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#cybersecurity`, `#finance`, `#IMF`

---

<a id="item-17"></a>
## [亚马逊与 Coinbase 和 Stripe 合作，让 AI 代理用稳定币支付](https://decrypt.co/367125/amazon-coinbase-stripe-ai-agents-pay-stablecoins) ⭐️ 7.0/10

亚马逊云服务（AWS）与 Coinbase 和 Stripe 合作，允许 AI 代理使用 USDC 稳定币支付 API、数据和在线服务。 这一整合标志着向自主代理经济迈出了实际一步，AI 代理可以使用可编程、低成本的稳定币独立交易，可能改变数字服务的消费和支付方式。 该系统利用与美元挂钩的稳定币 USDC 作为支付轨道，并涉及 Coinbase 提供加密基础设施和 Stripe 处理支付等主要平台。

rss · Decrypt · May 7, 16:32

**背景**: 像 USDC 这样的稳定币是一种加密货币，旨在保持相对于法定货币（如美元）的稳定价值。代理经济指的是一个新兴生态系统，其中 AI 代理代表用户或企业自主行动，需要高效的支付轨道来实现机器对机器的交易。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/USDC_(cryptocurrency)">USDC (cryptocurrency) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2505.15799">[2505.15799] The Agentic Economy - arXiv.org</a></li>
<li><a href="https://en.wikipedia.org/wiki/Payment_rail">Payment rail</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#stablecoins`, `#Amazon Web Services`, `#fintech`, `#blockchain`

---

<a id="item-18"></a>
## [TrustedVolumes DeFi 漏洞导致 670 万美元被盗](https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit) ⭐️ 7.0/10

TrustedVolumes 是一个被多个 DeFi 协议使用的流动性解析器，在以太坊上遭到攻击，损失约 670 万美元。安全公司 Blockaid 首先发现了此次攻击。 此事件凸显了 DeFi 中持续存在的安全风险，尤其是像流动性解析器这样的第三方基础设施组件。1inch 这个主要的 DEX 聚合器未受影响，表明损失得到了控制，但仍引发了对互连 DeFi 系统安全性的担忧。 据报道，被盗资金分布在三个以太坊地址中。TrustedVolumes 已与攻击者展开赏金谈判以追回资金。

rss · Decrypt · May 7, 11:25

**背景**: 在 DeFi 中，流动性解析器帮助跨不同协议匹配订单，实现高效交易。TrustedVolumes 曾为 1inch Fusion 和其他平台充当解析器。据报道，此次漏洞是由于合约控制薄弱所致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thedefiant.io/news/defi/1inch-resolver-trustedvolumes-drained-for-usd6-7m-on-ethereum">1inch Resolver TrustedVolumes Drained for $6.7M on Ethereum - "The Defiant"</a></li>
<li><a href="https://www.cryptonewsz.com/trustedvolumes-exploit-launches-bounty-talks/">TrustedVolumes Loses $6.7M in Exploit, Launches Bounty Talks</a></li>
<li><a href="https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit">DeFi Platform TrustedVolumes Hit by $6.7M Exploit - Decrypt</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#exploit`, `#blockchain`

---

<a id="item-19"></a>
## [Chrome 悄悄安装 4GB AI 模型，删除后自动重新下载](https://decrypt.co/367060/chrome-quietly-installing-4gb-ai-model-computer) ⭐️ 7.0/10

Google Chrome 在未经用户明确同意的情况下，悄悄向符合条件的设备下载一个 4GB 的 Gemini Nano AI 模型，并且即使用户删除该模型，它也会自动重新下载。 这引发了严重的隐私和用户自主权问题，表明 Google 采取了激进的 AI 集成策略，绕过了用户控制并消耗大量存储空间。 用户在 Chrome 中看到的 AI 模式按钮实际上并不使用这个下载的 Gemini Nano 模型，这使得强制下载显得没有必要。该模型仅用于设备端 AI 功能，如智能撰写或摘要。

rss · Decrypt · May 6, 22:01

**背景**: Gemini Nano 是 Google 最小的 AI 模型，旨在设备端运行，用于文本生成和摘要等任务。Google 一直在通过 AI 模式等功能将 AI 集成到 Chrome 中，提供高级搜索能力。然而，这种静默下载和重新下载的行为引发了关于缺乏透明度和用户同意的批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gemini_(language_model)">Gemini (language model ) - Wikipedia</a></li>
<li><a href="https://support.google.com/chrome/answer/16704170?hl=en&co=GENIE.Platform=Desktop">Use AI Mode in Chrome - Computer - Google Chrome Help</a></li>

</ul>
</details>

**社区讨论**: 未提供社区讨论内容，但根据新闻，用户可能对缺乏控制权和巨大的存储占用表示不满，部分人质疑 Google 的动机。

**标签**: `#privacy`, `#Google Chrome`, `#AI`, `#user autonomy`

---

<a id="item-20"></a>
## [AI 读取自然语言化学指令设计分子](https://decrypt.co/367048/ai-chemistry-instructions-build-molecule) ⭐️ 7.0/10

EPFL 的研究人员开发了一个 AI 框架，能够解读自然语言化学指令，并从数千种可能性中自动识别出最佳的分子合成路线。 这一突破弥合了自然语言与复杂化学合成规划之间的鸿沟，通过让不具深厚计算专长的化学家也能使用 AI 驱动的逆合成分析，有望加速药物发现和材料科学。 该框架利用大型语言模型解析自然语言描述，然后搜索已知反应数据库以提出可行的合成路线。它旨在处理模糊或不完整的指令，这是现实化学中的常见挑战。

rss · Decrypt · May 6, 21:31

**背景**: 逆合成分析是将目标分子分解为更简单前体分子的过程，是有机化学中的基本任务。传统上，化学家依靠经验和数据库来规划合成，但像 NVIDIA 的 ReaSyn 和 ChemAIRS 等 AI 模型已开始自动化这一过程。EPFL 的工作增加了自然语言界面，使这些工具更加直观。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367048/ai-chemistry-instructions-build-molecule">This AI Reads Your Chemistry Instructions and Finds the Best Way to Build You a Molecule - Decrypt</a></li>
<li><a href="https://developer.nvidia.com/blog/reasoning-through-molecular-synthetic-pathways-with-generative-ai/">Reasoning Through Molecular Synthetic Pathways with Generative AI</a></li>
<li><a href="https://www.chemical.ai/chemairs">ChemAIRS® – AI-Powered Retrosynthesis & Synthetic Pathway ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#chemistry`, `#synthesis`, `#natural language processing`, `#EPFL`

---

<a id="item-21"></a>
## [量子威胁或于 2030 年冲击比特币和以太坊](https://decrypt.co/367047/bitcoin-ethereum-q-day-quantum-threat-could-arrive-2030) ⭐️ 7.0/10

Project Eleven 的一份报告警告称，量子计算机可能在 2030 年前破解比特币和以太坊的加密技术，这可能早于网络实施防御措施的时间。 如果量子计算机达到这种能力，它们可以从公钥推导出私钥，使攻击者能够窃取钱包中的资金，威胁数十亿加密货币的安全。 报告强调，比特币和以太坊可能无法及时做好准备，因为升级到抗量子密码学需要社区共识和多年的测试。

rss · Decrypt · May 6, 21:07

**背景**: 量子计算机利用量子比特以指数级速度解决某些问题。当在足够强大的量子计算机上运行时，Shor 算法可以破解比特币和以太坊用于保护交易的椭圆曲线密码学（ECDSA）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.forbes.com/sites/digital-assets/2026/03/31/google-finds-quantum-computers-could-break-bitcoin-sooner-than-expected/">Google Finds Quantum Computers Could Break Bitcoin Sooner ...</a></li>
<li><a href="https://www.btcpolicy.org/articles/state-of-play-quantum-computing-and-bitcoins-path-forward">State of Play: Quantum Computing and Bitcoin's Path Forward</a></li>
<li><a href="https://thequantuminsider.com/2026/03/31/q-day-just-got-closer-three-papers-in-three-months-are-rewriting-the-quantum-threat-timeline/">Q-Day Just Got Closer: Three Papers in Three Months Are ...</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#blockchain`, `#cryptography`, `#Bitcoin`, `#Ethereum`

---

<a id="item-22"></a>
## [Ondo、摩根大通、万事达卡和 Ripple 合作在 XRPL 上结算代币化国债](https://decrypt.co/367033/ondo-jpmorgan-mastercard-ripple-settle-tokenized-treasuries-xrp-ledger) ⭐️ 7.0/10

Ondo Finance、摩根大通、万事达卡和 Ripple 合作，在 XRP Ledger（XRPL）上演示了代币化美国国债的结算，跨境交易在数秒内完成。 此次合作标志着传统金融领域采用区块链的重要一步，展示了代币化资产如何快速跨境结算，相比 SWIFT 等传统系统，有望降低成本和结算时间。 XRP Ledger 通常在 3-5 秒内完成交易结算，每笔交易费用低至 0.0002 至 0.001 美元，使其适合高速结算代币化国债——代币化国债是美国政府债务的数字表示。

rss · Decrypt · May 6, 18:52

**背景**: 代币化国债是区块链上的数字代币，代表对美国国债证券（如国库券或债券）的债权。XRP Ledger 是一种去中心化区块链，以快速和低成本的交易著称，常用于跨境支付。此次合作汇集了主要金融参与者，测试基于区块链的真实资产结算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://app.rwa.xyz/treasuries">RWA.xyz | Tokenized U.S. Treasuries</a></li>
<li><a href="https://www.okx.com/en-us/learn/tokenized-treasuries-revolution-finance">Tokenized Treasuries : Why They’re... | OKX United States</a></li>
<li><a href="https://chain.link/article/what-are-tokenized-treasuries">What Are Tokenized Treasuries ? | Chainlink</a></li>
<li><a href="https://www.mexc.com/news/1062299">How XRP Is Changing Cross-Border Payments | MEXC News</a></li>
<li><a href="https://www.ccn.com/education/crypto/xrpl-rlusd-mastercard-gemini-webbank-ripple-settlement-pilot/">XRPL for Fiat Credit Card Payments...</a></li>
<li><a href="https://learn.xrpl.org/glossary/settlement/">Glossary Term - Settlement - XRP Ledger | Learning Portal</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#XRP Ledger`, `#finance`, `#settlement`

---

<a id="item-23"></a>
## [谷歌 DeepMind 投资《EVE Online》开发商用于 AI 研究](https://decrypt.co/366991/google-deepmind-takes-stake-in-eve-online-maker-will-use-game-to-test-ai-behavior) ⭐️ 7.0/10

谷歌 DeepMind 已入股《EVE Online》开发商 CCP Games，并将利用该游戏复杂的虚拟世界来测试和推进 AI 行为。 此次合作将游戏与 AI 研究相结合，利用《EVE Online》复杂的玩家驱动经济和社会动态来训练多智能体强化学习系统，有望带来更强大、更通用的 AI。 《EVE Online》已上线 23 年，拥有一个持续存在的宇宙，数千名玩家通过贸易、战斗和政治互动，使其成为多智能体系统的理想试验场。DeepMind 的 AI 将从游戏数据和交互中学习。

rss · Decrypt · May 6, 16:59

**背景**: 多智能体强化学习（MARL）训练 AI 智能体在复杂环境中交互，已在《星际争霸 II》的 AlphaStar 和《Dota 2》的 OpenAI Five 等项目中取得显著成功。《EVE Online》开放式的玩家驱动经济和社会结构为 MARL 研究提供了独特的挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cnet.com/tech/services-and-software/google-deepmind-train-ai-models-eve-online/">Google DeepMind Will Train AI Models on the MMORPG Eve Online</a></li>
<li><a href="https://en.wikipedia.org/wiki/Multi-agent_reinforcement_learning">Multi-agent reinforcement learning - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2509.03682">[2509.03682] A Comprehensive Review of Multi-Agent Reinforcement Learning in Video Games</a></li>

</ul>
</details>

**社区讨论**: 一些玩家对游戏日益增加的复杂性和商业化表达了复杂情绪，但 AI 研究方面普遍被视为积极发展，可能带来新的见解。

**标签**: `#AI`, `#DeepMind`, `#Eve Online`, `#reinforcement learning`, `#multi-agent systems`

---

<a id="item-24"></a>
## [英伟达以 3000 万股认股权证支持 IREN](https://www.theblock.co/post/400498/iren-stock-surges-as-nvidia-backs-ai-expansion-with-warrants-tied-to-30-million-shares?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

英伟达从 IREN 获得了认股权证，可能转换为 21 亿美元的投资，涉及最多 3000 万股，每股 70 美元，导致 IREN 股价在盘后交易中飙升超过 25%。 这项战略投资表明英伟达对 AI 基础设施扩展的承诺加深，可能增强 IREN 建设数据中心的能力，并巩固英伟达在 AI 硬件生态系统中的地位。 这些认股权证五年后到期，允许英伟达以每股 70 美元购买最多 3000 万股。消息公布后，IREN 股价在盘后交易中上涨超过 25%。

rss · The Block · May 7, 21:11

**背景**: IREN 是一家专注于 AI 基础设施和数据中心的公司。认股权证是一种金融工具，赋予持有人在特定时间内以指定价格购买股票的权利。英伟达通过认股权证进行投资，既支持了 IREN 的扩张，又可能从未来股价上涨中获益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/400498/iren-stock-surges-as-nvidia-backs-ai-expansion-with-warrants-tied-to-30-million-shares">IREN stock surges as Nvidia backs AI expansion with warrants tied to...</a></li>
<li><a href="https://sherwood.news/markets/nvidia-to-invest-more-than-2-billion-in-iren-data-center-ai-boom/">Nvidia to invest up to $2.1 billion in IREN in... - Sherwood News</a></li>

</ul>
</details>

**标签**: `#Nvidia`, `#AI infrastructure`, `#investment`, `#IREN`, `#stock market`

---

<a id="item-25"></a>
## [火人节清理地图与流程](https://www.not-ship.com/burning-man-moop/) ⭐️ 6.0/10

一份用于追踪和清理火人节碎片的详细地图与流程被分享，通过拍摄碎片和像素计数展示了细致的环境管理。 这展示了一种社区驱动、数据密集的环境恢复方法，可为其他大型活动提供范例。 该地图覆盖 2025 年的 3935 英亩，清理团队拍摄每一块碎片（包括卫生纸），并在绿幕上通过像素计数确保符合土地管理局标准。

hackernews · speckx · May 7, 14:06 · [社区讨论](https://news.ycombinator.com/item?id=48049653)

**背景**: 火人节是每年在内华达沙漠举办的活动，强调自力更生和社区精神。土地管理局要求活动将土地恢复原状，因此需要严格的清理工作。

**社区讨论**: 评论者对清理工作表示赞赏，有人指出与太浩湖的 7 月 4 日等活动相比，火人节的清理效果令人印象深刻。另一人分享说去年的降雨和大风使清理更加困难。

**标签**: `#burning man`, `#cleanup`, `#community`, `#environment`, `#data`

---

<a id="item-26"></a>
## [20 家银行和科技巨头排队通过 Anchorage 发行稳定币](https://www.coindesk.com/business/2026/05/07/anchorage-says-it-has-a-pipeline-of-up-to-20-big-firms-looking-to-issue-stablecoins) ⭐️ 6.0/10

受监管的加密银行 Anchorage Digital 宣布，其渠道中有多达 20 家大型银行和科技公司希望通过其平台发行稳定币。 这标志着传统金融机构和科技巨头正转向发行自己的稳定币，可能加速稳定币市场的主流采用和监管明确性。 Anchorage Digital 是美国唯一一家获得联邦特许的加密银行，提供托管和基础设施服务。该渠道包括银行和科技公司，但未披露具体名称。

rss · CoinDesk · May 7, 16:36

**背景**: 稳定币是与美元等稳定资产挂钩的加密货币，用于交易和支付。发行涉及铸造由储备支持的代币，且监管日益严格。Anchorage Digital 的受监管地位使其成为机构进入该领域的关键合作伙伴。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anchorage_Digital">Anchorage Digital</a></li>
<li><a href="https://www.anchorage.com/">Crypto Bank for Institutions | Anchorage Digital</a></li>
<li><a href="https://stripe.com/resources/more/stablecoin-issuance">How Stablecoin Issuance Works: Risks, Reserves, and ... - Stripe</a></li>

</ul>
</details>

**标签**: `#stablecoins`, `#cryptocurrency`, `#banking`, `#fintech`

---

<a id="item-27"></a>
## [Solv 协议将 7 亿美元比特币从 LayerZero 迁移至 Chainlink](https://www.coindesk.com/business/2026/05/07/solv-drops-layerzero-for-chainlink-ccip-in-usd700-million-tokenized-bitcoin-migration) ⭐️ 6.0/10

Solv 协议正在将 7 亿美元的代币化比特币从 LayerZero 迁移至 Chainlink CCIP，理由是近期 LayerZero 支持的 Kelp DAO 遭受 2.92 亿美元攻击后引发的安全担忧。 此次迁移表明对 Chainlink 跨链基础设施的重大信任投票，并对 LayerZero 的安全模型提出质疑，可能影响其他协议的跨链选择。 此次迁移涉及 7 亿美元的 SolvBTC 代币，Solv 明确将安全性列为核心原因，并提及 Kelp DAO 攻击事件——该攻击利用了 LayerZero 的 OFT 标准中的单一验证者配置。

rss · CoinDesk · May 7, 14:59

**背景**: Solv 协议是一个 DeFi 平台，充当链上比特币储备层，支持流动性质押和收益生成。Chainlink CCIP 是一个由 Chainlink 去中心化预言机网络保障安全的跨链互操作协议，而 LayerZero 是另一个跨链消息协议，其 OFT 标准曾遭受一起备受关注的攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/04/20/kelp-dao-claims-layerzero-s-default-settings-are-what-actually-caused-the-usd290-million-disaster">Kelp DAO hits back at LayerZero for trying to shift the blame after a massive exploit</a></li>
<li><a href="https://www.theblock.co/post/400131/kelp-dao-ditches-layerzero-chainlink-cross-chain-infrastructure-292-million-exploit">Kelp DAO ditches LayerZero for Chainlink's cross-chain infrastructure following $292 million exploit | The Block</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#DeFi`, `#oracles`, `#tokenization`

---

<a id="item-28"></a>
## [MEV 机器人抢先交易 Vitalik Buterin 的 4 美元兑换，交易量达 100 万美元](https://www.coindesk.com/tech/2026/05/07/jaredfromsubway-bot-front-runs-vitalik-buterin-s-usd4-token-swap-with-usd1-million-in-volume) ⭐️ 6.0/10

一个名为 JaredfromSubway 的机器人抢先交易了 Vitalik Buterin 的小额代币兑换（将 digitalbits (XDB)换成以太币），使用了约 114 万美元的 WETH 在 SushiSwap 和 Uniswap 上操纵价格。 这一事件凸显了以太坊中 MEV（矿工可提取价值）的持续问题，机器人甚至可以从小额交易中通过抢先交易获利，影响用户体验和公平性。 该机器人执行了夹击攻击，在 Buterin 的交易之前买入 XDB，之后卖出，从价格变动中获利。Buterin 的原始兑换仅价值约 4 美元。

rss · CoinDesk · May 7, 13:58

**背景**: MEV（矿工可提取价值）是指矿工或验证者通过重新排序、包含或排除区块中的交易来提取的利润。抢先交易机器人监控内存池中的待处理交易，并在其之前执行自己的交易以从价格变化中获利。夹击攻击是一种常见的 MEV 策略，机器人在目标交易之前下买单，之后下卖单，从价格影响中获利。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/05/07/jaredfromsubway-bot-front-runs-vitalik-buterin-s-usd4-token-swap-with-usd1-million-in-volume">Vitalik Buterin gets sandwiched by 'JaredfromSubway' as Ethereum MEV risks linger</a></li>
<li><a href="https://www.coinbase.com/learn/advanced-trading/what-are-frontrunners-and-mev-when-it-comes-to-crypto-trading">What are frontrunners and MEV when it comes to crypto trading?</a></li>
<li><a href="https://www.theblock.co/post/230218/jaredfromsubway-mev-bot">Jaredfromsubway.eth's MEV bot rakes in millions of dollars in three months | The Block</a></li>

</ul>
</details>

**标签**: `#MEV`, `#cryptocurrency`, `#blockchain`, `#security`

---

<a id="item-29"></a>
## [Kraken 母公司以 6 亿美元收购稳定币公司 Reap](https://decrypt.co/367094/kraken-parent-acquires-asian-stablecoin-firm-reap-600-million) ⭐️ 6.0/10

加密货币交易所 Kraken 的母公司 Payward Inc.已同意以 6 亿美元的现金加股票交易收购香港稳定币支付提供商 Reap Technologies。 这是 Kraken 最大的一笔收购，也是其在亚洲的首个基础设施交易，标志着该公司大力进军使用稳定币技术的跨境支付领域。 该交易对 Payward 的估值为 200 亿美元，预计将在今年晚些时候完成，尚需监管批准。

rss · Decrypt · May 7, 13:48

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元等法定货币挂钩。Reap 提供平台，允许企业转移稳定币并在全球范围内以当地货币消费，连接传统金融和数字资产。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/kraken-parent-acquires-asian-stablecoin-134834615.html">Kraken Parent Acquires Asian Stablecoin Firm Reap for $600 Million: Bloomberg</a></li>
<li><a href="https://www.coindesk.com/business/2026/05/07/kraken-to-buy-stablecoin-payments-firm-reap-in-usd600-million-deal-bloomberg">Kraken to buy stablecoin payments firm Reap in $600 million ...</a></li>
<li><a href="https://cointelegraph.com/news/kraken-payward-reap-acquisition-600-million-asia">Kraken parent Payward to buy Reap in $600M stablecoin ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#stablecoin`, `#acquisition`, `#payments`

---

<a id="item-30"></a>
## [SpaceX 与 xAI 意外联手为 Anthropic 的 Claude 提供算力](https://decrypt.co/367035/elon-musk-spacex-power-anthropic-claude-surprise-ai-deal) ⭐️ 6.0/10

SpaceX 与 xAI 与 Anthropic 达成合作，为 Claude AI 模型的训练和运行提供算力，Anthropic 将买断 xAI 的 Colossus 1 数据中心的所有算力。 这笔交易将两个理念相左的 AI 巨头联合起来，可能重塑 AI 算力格局，并凸显大规模 GPU 集群在前沿 AI 开发中的重要性。 Colossus 1 数据中心提供超过 300MW 的容量和超过 22 万块 Nvidia GPU，Anthropic 将在本月内获得这些资源。

rss · Decrypt · May 6, 20:23

**背景**: Anthropic 开发 Claude 系列大语言模型，采用宪法 AI 和 RLHF 等技术进行训练。xAI 由埃隆·马斯克创立，运营大规模 GPU 集群用于 AI 训练，而 SpaceX 提供基础设施和运营支持。考虑到马斯克曾公开批评 Anthropic 的安全方法，此次合作令人意外。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/05/06/is-xai-a-neocloud-now/">Is xAI a neocloud now? | TechCrunch</a></li>
<li><a href="https://www.datacenterdynamics.com/en/news/anthropic-to-use-all-of-spacex-xais-colossus-1-data-center-compute/">Anthropic to use all of SpaceX-xAI's Colossus 1 data center ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#compute`, `#partnership`, `#Anthropic`, `#SpaceX`

---

<a id="item-31"></a>
## [理查德·道金斯认为 Claude AI 可能具有意识](https://decrypt.co/367017/claude-delusion-richard-dawkins-believes-ai-conscious) ⭐️ 6.0/10

进化生物学家理查德·道金斯表示，与 Anthropic 的 Claude 聊天机器人长时间互动后，感觉不像在使用软件，而更像在与一个有意识的思维对话。 道金斯的观点为关于 AI 意识的持续辩论增添了重要声音，可能影响公众认知和哲学讨论，尽管缺乏实证证据。 道金斯的评论基于个人体验而非科学测试，AI 意识问题仍未解决，诸如中文房间思想实验等论点质疑 AI 能否真正具有意识。

rss · Decrypt · May 6, 17:47

**背景**: Claude 是 Anthropic 开发的大型语言模型，旨在提供有帮助的对话体验。AI 是否能有意识是一个长期的哲学辩论，对于什么是意识以及如何衡量意识尚无共识。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chinese_room">Chinese room - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI`, `#consciousness`, `#chatbot`, `#philosophy`

---

<a id="item-32"></a>
## [Anthropic 发布 10 个金融 AI 代理模板](https://decrypt.co/366977/anthropic-deploys-ai-agents-to-tackle-wall-streets-most-tedious-work) ⭐️ 6.0/10

Anthropic 发布了 10 个即用型 AI 代理模板，旨在自动化构建 pitchbook、筛查 KYC 文件以及月末结账等繁琐的金融任务。这些模板可作为 Claude Cowork 和 Claude Code 的插件，以及 Claude Managed Agents 的 cookbook 使用。 此次发布标志着将 AI 代理应用于高度监管、文档繁重的金融工作流程的重要一步，可能为分析师节省数百小时。这也加剧了与 OpenAI 在金融服务 AI 市场的竞争。 每个模板都设计为可在数天内而非数月内部署，针对的任务包括 pitchbook 创建、KYC 筛查和月末结账。这些模板作为 Claude Cowork 和 Claude Code 的插件，以及 Claude Managed Agents 的 cookbook 提供。

rss · Decrypt · May 6, 14:54

**背景**: Pitchbook 是投资银行用于并购咨询的营销演示文稿。月末结账流程涉及通过对账和日记账分录来最终确定上个月的财务记录。KYC（了解你的客户）筛查是一种合规流程，用于验证客户身份并评估风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/finance-agents">Agents for financial services \ Anthropic</a></li>
<li><a href="https://www.investmentnews.com/fintech/anthropic-rolls-out-financial-services-agents-as-arms-race-with-openai-heats-up/266445">Anthropic rolls out financial services agents as arms race ...</a></li>
<li><a href="https://aidiscoveries.io/anthropics-claude-is-now-a-finance-coworker-10-ai-agent-templates-explained/">Anthropic’s Claude Is Now a Finance Coworker: 10 AI Agent ...</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#finance`, `#Anthropic`, `#automation`

---

<a id="item-33"></a>
## [Hut 8 签署 98 亿美元 AI 数据中心租约，股价创历史新高](https://decrypt.co/366971/hut-8-shares-all-time-high-price-bitcoin-miner-9-8-billion-ai-deal) ⭐️ 6.0/10

Hut 8 签署了一份为期 15 年、价值 98 亿美元的租约，为其位于德克萨斯州的 Beacon Point 园区提供 352 MW 的 AI 数据中心容量，这是其“电力优先”开发模式下的第二个超大规模 AI 园区租约。该消息推动 Hut 8 股价创下历史新高。 这笔交易凸显了比特币挖矿与 AI 基础设施日益融合的趋势，矿商利用其能源资产为高价值的 AI 工作负载提供服务。这也表明对大规模 AI 数据中心的需求强劲，可能重塑能源和数据中心行业。 该租约涵盖原本用于比特币挖矿的园区第一期，15 年合同总收入为 98 亿美元。Hut 8 运营着超过 19 个数据中心站点，包括比特币挖矿和 HPC 设施。

rss · Decrypt · May 6, 14:29

**背景**: 像 Hut 8 这样的比特币矿商正在转向 AI 和高性能计算（HPC）以实现收入多元化，因为它们拥有大量电力容量和数据中心专业知识。“电力优先”模式是指在签署租户之前先确保能源基础设施。Hut 8 最近在德克萨斯州启用了一个 205 MW 的比特币挖矿设施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/366971/hut-8-shares-all-time-high-price-bitcoin-miner-9-8-billion-ai-deal">Hut 8 Shares Hit All-Time High Price as Bitcoin Miner Signs $9.8 Billion AI Data Center Lease - Decrypt</a></li>
<li><a href="https://www.hut8.com/2025/06/30/hut-8-energizes-vega-data-center/">News & Insights | Hut 8</a></li>
<li><a href="https://www.datacenterdynamics.com/en/news/hut-8-launches-cryptomine-data-center-in-texas/">Hut 8 launches cryptomine data center in Texas - DCD</a></li>

</ul>
</details>

**标签**: `#bitcoin`, `#AI`, `#data center`, `#crypto`, `#business`

---

<a id="item-34"></a>
## [苹果因 AI 误导指控支付 2.5 亿美元和解](https://decrypt.co/366961/apple-250-million-settlement-ai-claims-heres-who-can-get-paid) ⭐️ 6.0/10

苹果同意支付 2.5 亿美元和解金，以解决其被指控在 AI 系统能力方面误导消费者的诉讼。 此次和解凸显了 AI 营销宣传面临日益严格的法律审查，尤其对苹果这样的科技巨头而言，可能为未来 AI 相关的消费者保护案件树立先例。 和解金额为 2.5 亿美元，符合条件的消费者可能获得赔偿，但具体资格标准尚未公布。此案凸显了宣传的 AI 能力与实际性能之间的差距。

rss · Decrypt · May 6, 14:01

**背景**: 苹果曾将 Siri 和本地智能等 AI 功能宣传为先进能力，但批评者认为部分说法夸大了实际性能，从而引发集体诉讼。此次和解避免了庭审及潜在的声誉损害。

**标签**: `#Apple`, `#AI`, `#settlement`, `#legal`

---

<a id="item-35"></a>
## [美国财政部要求币安遵守 2023 年监控协议](https://www.theblock.co/post/400454/treasury-demands-binance-comply-monitoring-guidelines-1-billion-iran-report?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

美国财政部私下要求币安遵守其在 2023 年认罪协议中同意的三年监控计划，此前有报道称超过 10 亿美元通过该交易所流向与伊朗有关的实体。 这一进展凸显了币安持续面临的监管审查，并强调了美国政府执行加密货币行业反洗钱和制裁合规的决心，可能为其他交易所树立先例。 币安在 2023 年与美国司法部和财政部达成 43 亿美元和解，承认违反反洗钱规则和制裁规定，并同意接受为期三年的独立监控。财政部的这一要求是在有报道称 10 亿美元通过币安流向与伊朗有关的组织之后提出的。

rss · The Block · May 7, 17:08

**背景**: 2023 年，币安对洗钱和违反制裁的指控认罪，同意支付 43 亿美元并实施由美国当局监督的三年监控计划。该监控计划旨在确保币安改善其反洗钱和制裁法律的合规性。The Information 最近的报道称，尽管达成了和解，仍有超过 10 亿美元涉及伊朗相关实体的交易通过币安进行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.bloomingbit.io/feed/news/111631">US Treasury Presses Binance to Honor 2023 Monitoring Deal</a></li>
<li><a href="https://www.theblock.co/post/400454/treasury-demands-binance-comply-monitoring-guidelines-1-billion-iran-report">Treasury demands Binance comply with monitoring guidelines amid reports over $1 billion flowed to Iran-linked groups: report | The Block</a></li>
<li><a href="https://www.valuethemarkets.com/cryptocurrency/news/binance-faces-increased-scrutiny-from-us-treasury-amid-compliance-oversight">Binance Faces Increased Scrutiny from US Treasury Amid Compliance Oversight | Value The Markets</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#compliance`, `#Binance`

---

<a id="item-36"></a>
## [Kalshi 在 Coatue 领投 10 亿美元后估值达 220 亿美元](https://www.theblock.co/post/400413/kalshi-hits-22-billion-valuation-after-1-billion-raise-led-by-coatue?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Kalshi 在由 Coatue 领投的 F 轮融资中筹集了 10 亿美元，估值达到 220 亿美元。自 2025 年 11 月以来，该平台的机构交易量激增 800%。 这一巨额融资轮表明投资者对受监管的预测市场充满信心，这类市场正作为预测现实世界事件的替代数据源而日益受到关注。估值飙升反映了机构对事件合约的采用正在增长。 Kalshi 是美国联邦监管的预测市场平台，允许用户交易关于经济指标和政治事件等结果的事件合约。F 轮融资属于后期融资，通常发生在 IPO 或收购之前。

rss · The Block · May 7, 14:00

**背景**: 预测市场是参与者交易合约的平台，合约的收益取决于未来事件的结果，从而提供实时概率估计。Kalshi 是少数几个受美国商品期货交易委员会（CFTC）监管的平台之一，允许美国用户使用美元存款进行交易。近期机构交易量的激增表明，对冲基金和资产管理公司对利用预测市场进行对冲和获取超额收益的兴趣日益浓厚。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://kalshi.com/">Kalshi - Prediction Market for Trading the Future</a></li>
<li><a href="https://www.si.com/betting/prediction-market/kalshi/what-is-kalshi">What Is Kalshi? The Platform That Made Prediction Markets Legit</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#funding`, `#valuation`, `#fintech`

---