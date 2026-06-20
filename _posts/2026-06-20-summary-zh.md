---
layout: default
title: "Horizon Summary: 2026-06-20 (ZH)"
date: 2026-06-20
lang: zh
---

> From 80 items, 24 important content pieces were selected

---

1. [Project Valhalla 的值类型在 JDK 28 中到来](#item-1) ⭐️ 9.0/10
2. [中国智谱 GLM-5.2 在华为芯片上媲美 Claude Opus](#item-2) ⭐️ 9.0/10
3. [ATProto 没有实例：Dan Abramov 的解释](#item-3) ⭐️ 8.0/10
4. [挪威禁止小学生使用人工智能](#item-4) ⭐️ 8.0/10
5. [互联网流量实名制：一项批判性分析](#item-5) ⭐️ 8.0/10
6. [EFF 主张 PACER 法院记录应免费](#item-6) ⭐️ 8.0/10
7. [现代汽车完全收购波士顿动力](#item-7) ⭐️ 7.0/10
8. [重新思考初级工程师招聘：超越任务完成](#item-8) ⭐️ 7.0/10
9. [Algorand 公布 2028 年实现量子抗性路线图](#item-9) ⭐️ 7.0/10
10. [Midjourney 从 AI 艺术转向医学影像](#item-10) ⭐️ 7.0/10
11. [Perplexity 的 AI 代理从自身错误中学习](#item-11) ⭐️ 7.0/10
12. [以太坊核心开发资金危机警告](#item-12) ⭐️ 7.0/10
13. [摩根士丹利提交 ETH 和 SOL ETF 申请，费率市场最低](#item-13) ⭐️ 7.0/10
14. [《毁灭战士》与《德军总部 3D》作曲家鲍比·普林斯去世](#item-14) ⭐️ 6.0/10
15. [Schwab 将推出标普 500 事件型期权](#item-15) ⭐️ 6.0/10
16. [富兰克林邓普顿提议将股息转换为比特币的 ETF](#item-16) ⭐️ 6.0/10
17. [微软发现通过 U 盘劫持加密货币钱包的恶意软件](#item-17) ⭐️ 6.0/10
18. [美国机构提议稳定币客户身份规则类似银行](#item-18) ⭐️ 6.0/10
19. [以太坊基金会再失一位核心领导人](#item-19) ⭐️ 6.0/10
20. [Steam 上的动漫壁纸恶意软件窃取加密货币和账户](#item-20) ⭐️ 6.0/10
21. [CME CEO 称交易所将起诉 CFTC 关于比特币永续期货](#item-21) ⭐️ 6.0/10
22. [Base Beryl 升级与 B20 代币标准 6 月 25 日上线](#item-22) ⭐️ 6.0/10
23. [CLARITY 法案：美国加密市场结构法案解读](#item-23) ⭐️ 6.0/10
24. [富达推出符合 GENIUS 法案的货币市场基金，面向稳定币发行商](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Project Valhalla 的值类型在 JDK 28 中到来](https://www.jvm-weekly.com/p/project-valhalla-explained-how-a) ⭐️ 9.0/10

经过十年的开发，Project Valhalla 的值类型（内联类）终于在 JDK 28 中交付，使得 JVM 可以在数组和字段中内联存储值，无需对象头或指针。 这是 Java 性能的范式转变，实现了紧凑的内存布局并减少了垃圾回收压力，有利于机器学习和大数据等数据密集型应用。 值类型是引用类型但具有内联存储；然而，堆扁平化仅限于表示不超过 64 位的对象，因此包含两个 32 位 int（65 位）的 Point 无法完全扁平化。

hackernews · philonoist · Jun 19, 06:35 · [社区讨论](https://news.ycombinator.com/item?id=48595511)

**背景**: Project Valhalla 是 OpenJDK 的一项努力，旨在将值类型引入 JVM，结合原始类型的性能和对象的表达能力。传统上，Java 对象在堆上分配，带有对象头和指针，导致内存开销和间接访问。值类型通过内联存储数据消除了这些开销。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Valhalla_(Java_language)">Project Valhalla (Java language) - Wikipedia</a></li>
<li><a href="https://dev.to/adaumircosta/understanding-value-types-project-valhalla-faf">Understanding Value Types (Project Valhalla) - DEV Community</a></li>
<li><a href="https://medium.com/@vishalpriyadarshi/project-valhalla-bringing-value-types-and-performance-efficiency-to-java-83b85e00b791">💡Project Valhalla: Bringing Value Types and Performance Efficiency to Java 🚀 | by Vishal Priyadarshi | Medium</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论（349 条评论）参与度很高，一些用户赞赏这项艰苦的工作，而另一些用户则争论空安全性和性能上限等权衡。一个普遍的观点是，许多批评者低估了现代 Java 的能力。

**标签**: `#Java`, `#JVM`, `#Project Valhalla`, `#performance`, `#value types`

---

<a id="item-2"></a>
## [中国智谱 GLM-5.2 在华为芯片上媲美 Claude Opus](https://decrypt.co/371613/china-z-ai-glm-5-2-model-rivals-claude-opus) ⭐️ 9.0/10

智谱 AI 发布了 GLM-5.2，这是一个大语言模型，在长周期编程基准测试中性能达到 Claude Opus 4.8 的 99%以内，同时完全运行在华为芯片上，每 token 成本降低高达 82%。 这表明无需英伟达芯片也能构建有竞争力的 AI 模型，减少了对西方硬件的依赖，并可能重塑全球 AI 供应链。这也标志着中国在国产 AI 芯片生态系统方面的能力不断增强。 GLM-5.2 支持 100 万 token 的上下文窗口，专为长周期任务设计。它已在 Hugging Face 和 Ollama 上发布，可用于将 Web 项目迁移到小程序。

rss · Decrypt · Jun 18, 21:26

**背景**: 英伟达的 H100 等高端 AI 芯片对华出口受限，促使中国企业开发替代方案。华为的昇腾 AI 芯片已成为领先的国产选择，尽管在效率和性能上仍有差距。智谱 AI 是中国知名的 AI 公司，以其 GLM 系列模型著称。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/GLM-5.2 · Hugging Face</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/huawei-expects-12-billion-in-ai-chip-revenue-this-year-as-nvidias-china-market-share-hits-zero">Huawei braces for $12 billion in AI chip revenue driven by homegrown AI model demand — Chinese fabs can barely keep up as Nvidia's market share craters within the region | Tom's Hardware</a></li>

</ul>
</details>

**标签**: `#AI`, `#China`, `#LLM`, `#Huawei`, `#geopolitics`

---

<a id="item-3"></a>
## [ATProto 没有实例：Dan Abramov 的解释](https://overreacted.io/there-are-no-instances-in-atproto/) ⭐️ 8.0/10

Dan Abramov 发表了一篇博文，解释 ATProto（Bluesky 背后的协议）没有像 Mastodon 那样的“实例”，并用 RSS 和电子邮件作类比来说明架构差异。 这一澄清解决了去中心化社交媒体领域的一个常见误解，帮助开发者和用户理解 ATProto 与 ActivityPub 之间的根本设计差异，这会影响审核、可扩展性和用户控制的方式。 在 ATProto 中，角色被分为个人数据服务器（PDS）、中继（Relay）和应用视图（AppView），这与 ActivityPub 的整体式实例不同。这种分离允许用户在不丢失数据或社交图谱的情况下切换提供商，并支持第三方进行可扩展的索引。

hackernews · danabramov · Jun 19, 15:10 · [社区讨论](https://news.ycombinator.com/item?id=48599515)

**背景**: ATProto（AT 协议）是由 Bluesky 开发的去中心化社交网络协议，旨在实现用户可移植性和可扩展的联邦。ActivityPub 是 Mastodon 和其他 Fediverse 平台使用的协议，其中每个服务器（实例）同时处理用户数据和内容分发。关键区别在于 ATProto 将数据存储、索引和呈现分离为独立服务，而 ActivityPub 将它们组合在一起。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://atproto.com/guides/overview">Protocol Overview - AT Protocol</a></li>
<li><a href="https://fediversereport.com/a-conceptual-model-of-atproto-and-activitypub/">A conceptual model of ATProto and ActivityPub – The Fediverse Report</a></li>
<li><a href="https://en.wikipedia.org/wiki/AT_Protocol">AT Protocol - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论（207 条评论）既有对清晰解释的赞扬，也有批评。一些评论者认为 RSS 类比有缺陷，因为 RSS 不依赖于像 Google Reader 这样的中央阅读器，而 ATProto 的中继运行成本高昂。其他人欣赏其模块化架构，但质疑 ATProto 如何解决实例通过去联邦化解决的审核问题。

**标签**: `#ATProto`, `#ActivityPub`, `#decentralization`, `#protocol design`, `#Bluesky`

---

<a id="item-4"></a>
## [挪威禁止小学生使用人工智能](https://www.reuters.com/technology/norway-imposes-near-ban-ai-elementary-school-2026-06-19/) ⭐️ 8.0/10

挪威政府宣布，从 2026 学年起，原则上禁止 6 至 13 岁学生使用人工智能，允许 14 至 16 岁学生在教师监督下有限使用。 该政策为教育领域的人工智能监管树立了先例，凸显了人们对人工智能削弱幼儿阅读、写作和批判性思维等基础技能的担忧。 禁令适用于 1 至 7 年级（6-13 岁），8 至 10 年级（14-16 岁）可在教师监督下谨慎使用；政府表示此举旨在保护儿童的认知发展。

hackernews · ilreb · Jun 19, 16:03 · [社区讨论](https://news.ycombinator.com/item?id=48600093)

**背景**: 像 ChatGPT 这样的生成式 AI 工具可以生成类似人类的文本，引发了教育界关于抄袭和学习投入减少的担忧。许多教育工作者认为，幼儿必须先掌握基本的读写和算术能力，然后才能使用 AI，这与推迟使用计算器的理由类似。

**社区讨论**: 评论普遍支持该禁令，用户将 AI 比作计算器，认为儿童需要先培养思考能力。有人质疑目前 AI 在课堂上的使用方式，也有人指出在不增加教师工作量的情况下执行此类禁令存在困难。

**标签**: `#AI policy`, `#education`, `#Norway`, `#generative AI`, `#children`

---

<a id="item-5"></a>
## [互联网流量实名制：一项批判性分析](https://nochan.net/b/Internet-Crap/20230829-Think-Of-The-Children/) ⭐️ 8.0/10

2023 年 NoChan 上的一篇文章批判性地分析了强制所有互联网流量使用实名 ID 的提案，探讨了技术、法律和社会影响。 这一讨论意义重大，因为强制身份验证可能从根本上改变互联网自由、隐私和审查动态，影响所有用户和内容平台。 文章引用了诸如“数字出版许可”等历史先例，并讨论了技术对策，如地下中继网络和基于无线电的网状网络。

hackernews · Bender · Jun 19, 20:19 · [社区讨论](https://news.ycombinator.com/item?id=48602817)

**背景**: 2005 年的《真实身份法案》标准化了美国驾照作为联邦身份证明，但将类似的身份验证应用于互联网流量引发了关于匿名和言论自由的担忧。正如 2025 年《纽约客》一篇文章所讨论的，年龄验证强制令可能会缩小成年人的互联网空间，并对边缘群体产生不成比例的影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Real_ID_Act">REAL ID Act - Wikipedia</a></li>
<li><a href="https://news.ycombinator.com/item?id=48602817">Think of the children: How to force real ID for all internet traffic (2023) | Hacker News</a></li>
<li><a href="https://www.newyorker.com/culture/infinite-scroll/the-internet-wants-to-check-your-id">The Internet Wants to Check Your I.D. | The New Yorker</a></li>

</ul>
</details>

**社区讨论**: 评论者提出了极端的技术对策，如地下无线电中继网络以绕过审查，并类比了 KYC/AML 法规，这些法规将责任转移并导致自我审查。一些人主张使用简单的路由器控制而非政府强制令。

**标签**: `#internet governance`, `#privacy`, `#censorship`, `#identity verification`, `#networking`

---

<a id="item-6"></a>
## [EFF 主张 PACER 法院记录应免费](https://www.eff.org/deeplinks/2026/06/court-records-should-be-free) ⭐️ 8.0/10

电子前哨基金会（EFF）发表文章，主张联邦法院记录系统 PACER 应免费开放，指出其造成的经济障碍。 这很重要，因为 PACER 费用限制了公众对法律文件的访问，损害了透明度和司法公正。免费开放将惠及记者、研究人员和诉讼当事人。 PACER 每页收费 0.10 美元，每份文件最高 3.00 美元，但频繁使用者可能承担高额费用。EFF 指出该系统收入远超运营成本，暗示收费过高。

hackernews · hn_acker · Jun 19, 17:34 · [社区讨论](https://news.ycombinator.com/item?id=48600946)

**背景**: PACER（公共法院电子记录访问系统）是一个提供联邦法院文件在线访问的系统。虽然法律要求公共访问，但 PACER 按页收费，批评者认为这造成了司法障碍。EFF 长期倡导免费访问，CourtListener 和 RECAP 等工具通过共享已购文件来缓解费用问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.eff.org/about">About EFF | Electronic Frontier Foundation</a></li>
<li><a href="https://pacer.uscourts.gov/register-account">Register for an Account | PACER : Federal Court Records</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了政府收费限制权利获取的普遍问题，有人指出州法院费用可能更高（例如爱达荷州每页 10 美元）。另有人强调了 CourtListener 和 RECAP 在免费提供文件方面的价值。

**标签**: `#access to justice`, `#PACER`, `#public records`, `#legal technology`, `#public policy`

---

<a id="item-7"></a>
## [现代汽车完全收购波士顿动力](https://startupfortune.com/hyundai-takes-full-control-of-boston-dynamics-as-softbank-exits-for-325-million/) ⭐️ 7.0/10

现代汽车集团行使看跌期权，从软银手中收购波士顿动力的剩余股份，完成对该机器人公司的完全控股。 此次收购使现代汽车在先进机器人领域占据领先地位，有望将人形和四足机器人整合到制造和物流中，同时应对韩国劳动年龄人口下降的问题。 现代汽车最初于 2020 年 12 月以 8.8 亿美元收购了 80%的股份，当时对波士顿动力的估值为 11 亿美元；此次以 3.25 亿美元收购剩余 9%的股份，估值有所下降。

hackernews · ck2 · Jun 19, 16:28 · [社区讨论](https://news.ycombinator.com/item?id=48600312)

**背景**: 波士顿动力以 Atlas（人形机器人）和 Spot（四足机器人）等先进机器人闻名。现代汽车作为大型汽车制造商，旨在将机器人技术应用于制造及其他领域，类似于特斯拉的做法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Atlas_(robot)">Atlas ( robot ) - Wikipedia</a></li>
<li><a href="https://spectrum.ieee.org/hyundai-buys-boston-dynamics">Hyundai Buys Boston Dynamics for Nearly $1 Billion. - IEEE Spectrum</a></li>
<li><a href="https://www.hyundaimotorgroup.com/en/story/CONT0000000000001671">[Op-ed] Robots Jump into the Mobility Industry | Hyundai Motor Group</a></li>

</ul>
</details>

**社区讨论**: 评论者就人形机器人与专用机器人的价值展开辩论，一些人质疑人形形态在制造中的实用性。另一些人则将此次收购与韩国的人口挑战及通用机器人的潜力联系起来。

**标签**: `#robotics`, `#acquisition`, `#Hyundai`, `#Boston Dynamics`, `#automation`

---

<a id="item-8"></a>
## [重新思考初级工程师招聘：超越任务完成](https://newsletter.kentbeck.com/p/hey-n00b-we-didnt-hire-you-to-complete) ⭐️ 7.0/10

Kent Beck 认为，公司招聘初级工程师不应仅仅是为了完成任务，而是为了将他们培养成长期的高影响力贡献者。 这一观点挑战了主流的任务导向型初级招聘观念，引发了关于软件工程中职业流动性、LLM 影响和公司文化的讨论。 Beck 根据影响力和成长潜力将初级工程师分为 A、B、C 三类，强调即使是 B 级初级工程师，通过适当的指导也能变得有价值。

hackernews · rrvsh · Jun 20, 00:11 · [社区讨论](https://news.ycombinator.com/item?id=48604851)

**背景**: 在许多科技公司，初级工程师通常被雇佣来处理低复杂度的任务，期望他们能立即产出。然而，Beck 认为这种短期视角忽视了人才发展的长期投资，而后者可能带来更高的回报。

**社区讨论**: 评论意见不一：一些人同意 Beck 的发展观点，而另一些人则认为公司招聘初级员工主要是为了完成初级任务。批评者还指出，文章的语气可能显得居高临下。

**标签**: `#software engineering`, `#career development`, `#hiring`, `#engineering culture`

---

<a id="item-9"></a>
## [Algorand 公布 2028 年实现量子抗性路线图](https://www.coindesk.com/tech/2026/06/18/algorand-unveils-post-quantum-roadmap-to-secure-blockchain-by-2027) ⭐️ 7.0/10

Algorand 宣布了一项路线图，计划在 2028 年前为其区块链实现后量子安全，将其加密原语过渡到抗量子算法。 这很重要，因为量子计算机可能破解当前的公钥密码学，而 Algorand 的主动路线图为区块链安全树立了先例，可能影响其他网络效仿。 该路线图可能涉及将 NIST 标准化的后量子算法（如 CRYSTALS-Kyber 和 CRYSTALS-Dilithium）集成到 Algorand 协议中，并在未来两年内分阶段升级。

rss · CoinDesk · Jun 18, 14:00

**背景**: 后量子密码学（PQC）是指设计用于抵御量子计算机攻击的加密算法。当前的公钥系统（如 RSA 和 ECDSA）依赖于量子计算机可通过 Shor 算法高效解决的数学问题。2024 年，NIST 发布了首批三个 PQC 标准，为迁移奠定了基础。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography</a></li>
<li><a href="https://en.wikipedia.org/wiki/Algorand">Algorand - Wikipedia</a></li>
<li><a href="https://csrc.nist.gov/projects/post-quantum-cryptography">Post - Quantum Cryptography | CSRC</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#quantum computing`, `#cryptography`, `#Algorand`, `#post-quantum`

---

<a id="item-10"></a>
## [Midjourney 从 AI 艺术转向医学影像](https://decrypt.co/371606/midjourney-pivots-ai-images-medical-imaging-build-better-mri) ⭐️ 7.0/10

以 AI 图像生成闻名的 Midjourney 正在开发一种结合超声技术与 AI 的全身体成像系统，有望成为 MRI 的替代方案。 这一转型可能通过提供比 MRI 更低成本、更便携的替代方案，使医学影像更普及，尤其是在医疗资源匮乏的地区。 该系统利用超声断层扫描（可对软组织和骨骼成像）并结合 AI 提升图像质量与解读能力，但开发时间表和临床验证细节尚不明确。

rss · Decrypt · Jun 18, 21:18

**背景**: Midjourney 是一家领先的 AI 图像生成公司。超声是一种安全、低成本的成像方式，但传统超声视野有限。全身体超声断层扫描是一种新兴技术，可捕获全身图像。AI 有助于重建和解读这些图像，有望达到 MRI 的质量水平。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11275691/">Whole-Body Human Ultrasound Tomography - PMC - NIH</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1076633223000338">Whole-Body Imaging Using Low Frequency Transmission Ultrasound</a></li>
<li><a href="https://www.hertzfoundation.org/impact-stories/the-first-handheld-whole-body-ultrasound-system/">The First Handheld Whole-body Ultrasound System - Hertz Foundation</a></li>

</ul>
</details>

**标签**: `#AI`, `#medical imaging`, `#Midjourney`, `#ultrasound`, `#healthcare`

---

<a id="item-11"></a>
## [Perplexity 的 AI 代理从自身错误中学习](https://decrypt.co/371584/perplexity-ai-agent-brain) ⭐️ 7.0/10

Perplexity 推出了“Brain”，这是一个用于其 AI 代理的自我改进记忆层，能够追踪过去的行动、成功和失败，并在夜间利用这些信息优化未来的任务，使其更快、更便宜。 这一发展标志着从以用户为中心的记忆向以代理为中心的记忆的转变，可能降低 AI 代理的运营成本并提高效率，从而加速在企业自动化中的应用。 Brain 构建了一个“LLM wiki”——一份整洁的、AI 可读的代理工作模式摘要——在每个新任务之前加载，从而实现无需人工干预的持续学习。

rss · Decrypt · Jun 18, 19:47

**背景**: 大多数 AI 记忆系统专注于记住用户偏好，但 Perplexity 的 Brain 记住的是代理自身的行动和结果。这与 Mem0 类似，Mem0 是一个为 AI 代理提供自我改进记忆的通用记忆层。通过从过去的错误中学习，代理可以避免重复错误并优化其工作流程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://findskill.ai/blog/perplexity-brain/">Perplexity Brain Learns Your Work Overnight ($200/mo) | FindSkill. ai ...</a></li>
<li><a href="https://www.marktechpost.com/2026/06/18/perplexity-launches-brain/">Perplexity Launches Brain , a Self-Improving Memory... - MarkTechPost</a></li>
<li><a href="https://perplexityaimagazine.com/ai-news/perplexity-brain-memory-system/">Perplexity Brain : Self-Improving AI Memory System 2026</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#self-improving systems`, `#memory layer`, `#Perplexity`

---

<a id="item-12"></a>
## [以太坊核心开发资金危机警告](https://www.theblock.co/post/405404/ethereum-could-face-core-development-funding-crisis-within-nine-months-says-former-ef-contributor?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

前以太坊基金会贡献者 VanEpps 警告称，在 CIP（核心改进提案）资金机制到期后的 3 到 9 个月内，以太坊可能面临核心开发资金危机。 这一警告凸显了以太坊核心开发可能面临的生存威胁，可能减缓协议升级和创新，影响整个以太坊生态系统及其用户。 该警告特别指出 CIP 到期是触发因素，危机将在 3 到 9 个月内显现。VanEpps 是前 EF 贡献者，增加了这一担忧的可信度。

rss · The Block · Jun 19, 10:11

**背景**: 以太坊基金会（EF）历来通过拨款和 CIP 机制资助核心开发。2025 年中，EF 从开放申请模式转向更主动、需求驱动的资金模式。CIP 到期可能导致关键协议工作出现资金缺口。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gitcoin.co/apps/ethereum-foundation-esp">Ethereum Foundation ESP | Gitcoin</a></li>
<li><a href="https://www.linkedin.com/pulse/how-get-ethereum-foundation-funding-after-grant-njfnf">How to Get Ethereum Foundation Funding After the Grant Pause</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#funding`, `#blockchain`, `#development`

---

<a id="item-13"></a>
## [摩根士丹利提交 ETH 和 SOL ETF 申请，费率市场最低](https://www.theblock.co/post/405362/morgan-stanley-eth-sol-etf-amendments?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

摩根士丹利已提交现货以太坊（ETH）和 Solana（SOL）交易所交易基金（ETF）的修正案，披露了市场上最低的费率结构，并表明正在与美国证券交易委员会（SEC）积极沟通。 这一由大型金融机构采取的行动标志着加密货币 ETF 的主流采用日益增长，可能迫使竞争对手降低费率，从而惠及投资者并加速监管进展。 这些修正案反映了与 SEC 的持续沟通，表明上市流程正在推进。提供的内容中未披露具体费率百分比，但被描述为市场最低。

rss · The Block · Jun 19, 02:54

**背景**: 现货加密货币 ETF 是持有实际加密货币（如 ETH 或 SOL）并在证券交易所交易的投资基金，为投资者提供无需直接持有资产即可获得敞口的机会。SEC 历来对此类产品的批准持谨慎态度，但近期比特币 ETF 的获批为其他加密货币打开了大门。

**标签**: `#crypto`, `#ETFs`, `#finance`, `#Morgan Stanley`, `#regulation`

---

<a id="item-14"></a>
## [《毁灭战士》与《德军总部 3D》作曲家鲍比·普林斯去世](https://www.legacy.com/legacy/robert-bobby-prince-lll) ⭐️ 6.0/10

传奇作曲家鲍比·普林斯去世，他曾为《毁灭战士》、《德军总部 3D》和《毁灭公爵 3D》创作标志性配乐。他的死讯通过 Legacy.com 上的讣告公布。 普林斯的音乐定义了早期第一人称射击游戏的氛围，并影响了一代游戏作曲家。他的去世标志着一位先驱的离去，其作品至今仍深受复古游戏爱好者的喜爱。 普林斯为《毁灭战士》、《德军总部 3D》和《毁灭公爵 3D》创作了配乐，并为《毁灭战士》贡献了音效。他为《毁灭战士》创作的音乐深受潘特拉和杀手等重金属乐队的影响。

hackernews · pgrote · Jun 19, 19:35 · [社区讨论](https://news.ycombinator.com/item?id=48602352)

**背景**: 鲍比·普林斯是 PC 游戏黄金时代的关键人物，以在 id Software 和 3D Realms 的工作而闻名。他的作品使用 MIDI 文件创作出令人难忘且富有氛围的曲目，增强了游戏体验。尤其是《毁灭战士》的配乐，被视为经典，因其强烈的情感和契合度而广受赞誉。

**社区讨论**: 社区评论表达了深切的悲伤和感激，许多人分享了普林斯的音乐如何影响他们的个人回忆。评论者强调了他作品的沉浸感，并指出他还为《毁灭战士》创作了音效，这进一步丰富了他的遗产。

**标签**: `#gaming`, `#music`, `#obituary`, `#retro gaming`

---

<a id="item-15"></a>
## [Schwab 将推出标普 500 事件型期权](https://www.coindesk.com/markets/2026/06/19/schwab-to-join-prediction-markets-race-with-s-and-p-500-event-based-options-wsj) ⭐️ 6.0/10

据《华尔街日报》报道，嘉信理财计划推出与标普 500 指数挂钩的事件型期权，从而进入预测市场领域。 这家大型券商此举可能使预测市场在传统金融领域合法化，为散户投资者提供一种受监管的押注经济事件的方式。 事件型期权是二元期权，根据特定事件是否发生（例如标普 500 指数在某个日期前达到某个水平）进行赔付。与不受监管的加密预测市场不同，Schwab 的产品将受美国证券交易委员会监管。

rss · CoinDesk · Jun 19, 17:51

**背景**: 预测市场是交易所交易的市场，参与者交易合约，其收益取决于未知的未来结果，价格反映人群的概率估计。传统例子包括政治博彩市场，而像 Polymarket 这样的新平台使用区块链技术。Schwab 的进入将传统期权交易与事件型投机联系起来。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prediction_market">Prediction market</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#finance`, `#options trading`, `#S&P 500`

---

<a id="item-16"></a>
## [富兰克林邓普顿提议将股息转换为比特币的 ETF](https://www.coindesk.com/daybook-us/2026/06/19/franklin-templeton-proposes-new-funds-that-turn-corporate-dividends-into-bitcoin) ⭐️ 6.0/10

富兰克林邓普顿已申请两只新 ETF，将美国股票的股息再投资于比特币，预计最早于 2026 年 9 月 1 日生效。 这一创新连接了传统金融与加密货币，为投资者提供了一种通过股息股票获得比特币敞口的新方式，可能吸引更多机构资金进入加密领域。 这些基金将持有约 95%的股票和 5%的比特币，比特币配置上限为 20%，追踪 VettaFi 美国大盘 500 比特币 DRIP 和 VettaFi 美国创新 100 比特币 DRIP 指数。

rss · CoinDesk · Jun 19, 11:27

**背景**: 股息再投资计划（DRIP）自动使用现金股息购买更多股票。富兰克林邓普顿提议的 ETF 将这一概念改编为将股息再投资于比特币而非额外股票，创建了一种结合股权收益与加密敞口的混合产品。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bitcoinfoundation.org/news/crypto-etfs-news/drip-etf-bitcoin/">DRIP ETFs : Franklin Templeton Turns Dividends Into Bitcoin</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#ETFs`, `#bitcoin`, `#finance`

---

<a id="item-17"></a>
## [微软发现通过 U 盘劫持加密货币钱包的恶意软件](https://www.coindesk.com/tech/2026/06/19/microsoft-found-malware-that-hijacks-crypto-wallets-and-spreads-through-usb-sticks) ⭐️ 6.0/10

微软发现了一种新型恶意软件，它能劫持加密货币钱包并通过 U 盘传播，CoinDesk 于 2026 年 6 月 19 日报道了此事。 这一发现凸显了加密货币用户面临的日益严重的威胁，因为 U 盘传播方式可在共享环境中快速离线扩散，可能导致广泛的财务损失。 该恶意软件可能使用剪贴板劫持技术，将复制的钱包地址替换为攻击者控制的地址，其 U 盘传播机制可感染隔离系统。

rss · CoinDesk · Jun 19, 08:48

**背景**: 剪贴板劫持恶意软件监控剪贴板中复制的加密货币地址，并将其替换为攻击者的地址，导致用户将资金发送到错误的目的地。基于 U 盘的恶意软件在插入其他计算机时会传播，用户往往毫无察觉。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cncintel.com/clipboard-hijacking/">Clipboard Hijacking Malware Removal - CNC Intelligence</a></li>
<li><a href="https://www.howtogeek.com/797290/how-usb-drives-can-be-a-danger-to-your-computer/">How USB Drives Can Be a Danger to Your Computer</a></li>

</ul>
</details>

**标签**: `#malware`, `#cryptocurrency`, `#security`, `#USB`

---

<a id="item-18"></a>
## [美国机构提议稳定币客户身份规则类似银行](https://www.coindesk.com/policy/2026/06/18/u-s-agencies-seek-stablecoin-customer-id-rules-akin-to-banks-in-new-genius-act-rule) ⭐️ 6.0/10

美国金融犯罪执法网络（FinCEN）、货币监理署（OCC）、美联储、联邦存款保险公司（FDIC）和国家信用合作社管理局（NCUA）等联邦机构联合提出一项规则，要求稳定币发行者实施与传统银行类似的客户身份识别计划（CIP），该规则基于《GENIUS 法案》。 该提案通过将类似银行的 KYC/AML 标准应用于稳定币发行者，填补了监管空白，可能增加合规成本，但也提升了稳定币生态系统的合法性和信任度。 发行者需要收集客户姓名、地址、出生日期和政府颁发的身份证号码。该规则是《GENIUS 法案》的一部分，该法案在颁布后 18 个月或最终法规发布后 120 天生效（以较早者为准）。

rss · CoinDesk · Jun 18, 17:17

**背景**: 《GENIUS 法案》是美国第一部为支付型稳定币（与货币价值挂钩的数字代币）建立全面监管框架的联邦法律。稳定币发展迅速，但面临各州监管不一致的问题，促使联邦采取行动使其与传统银行保障措施保持一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.lw.com/en/insights/the-genius-act-of-2025-stablecoin-legislation-adopted-in-the-us">The GENIUS Act of 2025 Stablecoin Legislation Adopted in the US</a></li>
<li><a href="https://www.ccn.com/news/crypto/us-regulators-stablecoin-customer-verification-rules-genius-act/">US Regulators Propose New Customer Verification Rules for...</a></li>
<li><a href="https://blockonomi.com/fed-targets-stablecoin-loopholes-with-customer-id-proposal/">Fed Targets Stablecoin Loopholes With Customer ID... - Blockonomi</a></li>

</ul>
</details>

**标签**: `#stablecoin`, `#regulation`, `#crypto policy`, `#GENIUS Act`

---

<a id="item-19"></a>
## [以太坊基金会再失一位核心领导人](https://www.coindesk.com/tech/2026/06/18/ethereum-foundation-loses-another-key-leader-as-co-executive-director-hsiao-wei-wang-resigns) ⭐️ 6.0/10

以太坊基金会联合执行董事王小薇（Hsiao-Wei Wang）已辞职，这是近期领导层离职潮中又一位知名人物的离开。 此次离职可能引发对以太坊基金会领导层稳定性的担忧，进而影响以太坊生态系统的战略方向和治理。 王小薇的辞职是在其他关键人物此前离职之后发生的，但具体原因尚未披露。以太坊基金会尚未宣布接替人选。

rss · CoinDesk · Jun 18, 15:41

**背景**: 以太坊基金会是一个支持以太坊区块链发展的非营利组织。联合执行董事与其他领导人共同负责运营和战略。近期的领导层变动引起了外界对基金会内部动态的关注。

**标签**: `#Ethereum`, `#blockchain`, `#leadership`, `#cryptocurrency`

---

<a id="item-20"></a>
## [Steam 上的动漫壁纸恶意软件窃取加密货币和账户](https://decrypt.co/371632/anime-girls-steal-crypto-wallpaper-malware-targets-steam-gamers) ⭐️ 6.0/10

研究人员发现，Steam Workshop 上伪装成动漫壁纸的恶意软件（针对 Wallpaper Engine）会窃取加密货币并劫持账户。自至少 2025 年底以来，这些恶意包已被下载数万次。 这凸显了通过 Steam 等合法平台传播恶意软件的趋势日益增长，使数百万玩家面临风险。该攻击利用用户对流行应用的信任，可能导致重大的财务和账户安全损失。 该恶意软件包括信息窃取器、后门和账户劫持功能，通过劫持 Steam 账户自我传播。Wallpaper Engine 是一款售价 4.99 美元的动态壁纸工具，拥有 9.3 万至 11.4 万同时在线用户和近百万条评论。

rss · Decrypt · Jun 19, 14:39

**背景**: Wallpaper Engine 是一款流行的 Steam 应用，允许用户通过 Steam Workshop 创建和分享动态壁纸。信息窃取恶意软件专门窃取密码、加密货币钱包和会话令牌等敏感信息。攻击者经常滥用受信任的平台以绕过安全措施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tomshardware.com/tech-industry/cyber-security/kaspersky-finds-malware-hidden-in-steam-wallpapers-that-hijacks-accounts-to-spread-itself">Kaspersky finds malware hidden in Steam Wallpaper Engine that...</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/steam-workshop-abused-to-spread-malware-via-wallpaper-engine-app/">Steam Workshop abused to spread malware via Wallpaper Engine app</a></li>
<li><a href="https://steamcommunity.com/app/431960/discussions/2/569289424252266099/">Malware in wallpapers ? :: Wallpaper Engine General Discussions</a></li>

</ul>
</details>

**标签**: `#malware`, `#cryptocurrency`, `#steam`, `#security`, `#infostealer`

---

<a id="item-21"></a>
## [CME CEO 称交易所将起诉 CFTC 关于比特币永续期货](https://decrypt.co/371514/cme-to-sue-cftc-over-bitcoin-perpetual-futures-approval-ceo) ⭐️ 6.0/10

CME 集团 CEO Terry Duffy 宣布，交易所将于周四对 CFTC 提起诉讼，认为比特币永续期货实际上属于《多德-弗兰克法案》定义的掉期合约，不应被批准。 这起诉讼可能重塑美国加密衍生品的监管格局，可能迫使 CFTC 重新考虑永续期货的分类，并影响交易所提供这些产品的方式。 永续期货是一种永不到期的衍生品，与传统期货合约不同。Duffy 声称它们的功能类似于掉期，因此应受 CFTC 的掉期监管，这需要不同的合规措施。

rss · Decrypt · Jun 18, 11:20

**背景**: 《多德-弗兰克法案》在 2008 年金融危机后颁布，授权 CFTC 监管掉期以增加透明度和降低风险。比特币永续期货在离岸交易所变得流行，但在美国面临监管不确定性。CFTC 此前已批准了一些比特币衍生品，但永续期货的分类仍存在争议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cftc.gov/LawRegulation/DoddFrankAct/index.htm">Dodd - Frank Act | CFTC</a></li>
<li><a href="https://www.investopedia.com/terms/d/dodd-frank-financial-regulatory-reform-bill.asp">investopedia.com/terms/d/ dodd - frank -financial-regulatory-reform-bill.asp</a></li>

</ul>
</details>

**标签**: `#crypto`, `#regulation`, `#derivatives`, `#bitcoin`

---

<a id="item-22"></a>
## [Base Beryl 升级与 B20 代币标准 6 月 25 日上线](https://www.theblock.co/post/405410/base-targets-june-25-mainnet-launch-for-beryl-upgrade-and-new-b20-token-standard?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Base 的 Beryl 升级将于 6 月 25 日在主网上线，引入 B20 原生代币标准，并将提款延迟缩短至 5 天。 此次升级将 Base 转变为稳定币和现实世界资产等受监管金融工具的一流发行平台，可能吸引机构采用并提高资本效率。 B20 代币以 Rust 预编译而非 EVM 智能合约实现，速度更快、成本更低，同时保持 ERC-20 兼容性，现有钱包和 dApp 无需改造。

rss · The Block · Jun 19, 10:48

**背景**: Base 是基于 OP Stack 构建的以太坊 Layer 2 区块链。Beryl 升级是其第二次网络升级，此前已在 Sepolia 测试网上部署。B20 是专为受监管金融工具设计的原生代币标准，可直接在 Base 节点软件中发行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.base.org/base-chain/specs/upgrades/beryl/b20">B 20 Native Token Standard - Base Documentation</a></li>
<li><a href="https://cryptobriefing.com/base-b20-token-standard-stablecoins-rwas/">Base's Jesse Pollak unveils B 20 token standard for stablecoins and...</a></li>
<li><a href="https://blog.base.dev/introducing-base-beryl">Introducing Base Beryl</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#Base`, `#token standard`, `#upgrade`, `#DeFi`

---

<a id="item-23"></a>
## [CLARITY 法案：美国加密市场结构法案解读](https://www.theblock.co/learn/404536/what-is-the-clarity-act?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

CLARITY 法案（2025 年数字资产市场清晰法案）是一项拟议的美国法案，旨在建立数字资产监管的联邦框架，明确加密公司如何遵守法律以及由哪些监管机构监督。 该法案可能用明确的联邦标准取代当前各州法规和执法行动的拼凑局面，为加密企业和投资者提供法律确定性。它被认为是迄今为止针对数字资产提出的最重要的联邦市场结构法案。 该法案侧重于澄清加密资产是证券还是商品，为交易所和经纪商制定规则，并将商品池运营商（CPO）和商品交易顾问（CTA）的定义扩展至包括数字资产管理人。它还旨在用明确的法定框架取代“执法式监管”。

rss · The Block · Jun 19, 06:48

**背景**: 目前，美国加密监管分散，SEC 和 CFTC 经常就数字资产的管辖权发生争议，这导致了不确定性以及对加密公司的执法行动。CLARITY 法案旨在提供一个统一的联邦框架，以解决这些管辖权模糊问题，在保护消费者的同时促进创新。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://emmer.house.gov/media-center/press-releases/emmer-s-securities-clarity-act-and-blockchain-regulatory-certainty-act-pass-house-financial-services-committee-markup">Emmer's Securities Clarity Act and Blockchain Regulatory Certainty Act ...</a></li>
<li><a href="https://www.reedsmith.com/articles/how-clarity-act-could-redefine-compliance-crypto-fund-managers-and-advisers/">How the CLARITY Act Could Redefine Compliance for Crypto…</a></li>
<li><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6484840">The Status of the CLARITY Act and the Future of U.S. Digital Asset ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#US policy`, `#digital assets`

---

<a id="item-24"></a>
## [富达推出符合 GENIUS 法案的货币市场基金，面向稳定币发行商](https://www.theblock.co/post/405357/fidelity-stablecoin-money-market-fund?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

富达推出了一款专为稳定币发行商设计的政府货币市场基金，该基金仅投资于 GENIUS 法案允许的合格储备资产。 这标志着大型金融机构直接与稳定币监管对齐，为稳定币发行商提供了合规的储备管理选项，并可能促进机构对稳定币的采用。 该基金仅投资于 GENIUS 法案定义的合格储备资产，该法案于 2025 年 7 月颁布，为支付稳定币提供了联邦监管框架。

rss · The Block · Jun 19, 01:58

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常由现金或政府证券等储备支持。GENIUS 法案是美国法律，为稳定币发行商制定了联邦要求，包括储备资产规则。富达的基金为发行商持有这些储备提供了合规工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/405357/fidelity-stablecoin-money-market-fund">Fidelity launches GENIUS-aligned money market fund for stablecoin ...</a></li>
<li><a href="https://www.congress.gov/bill/119th-congress/senate-bill/1582/text">Text - S.1582 - 119th Congress (2025-2026): GENIUS Act</a></li>
<li><a href="https://home.treasury.gov/news/press-releases/sb0435">Treasury Proposes Rule to Implement the GENIUS Act's Requirements to ...</a></li>

</ul>
</details>

**标签**: `#stablecoins`, `#finance`, `#cryptocurrency`, `#regulation`

---