---
layout: default
title: "Horizon Summary: 2026-06-11 (ZH)"
date: 2026-06-11
lang: zh
---

> From 88 items, 27 important content pieces were selected

---

1. [AI 代理向 Fedora 提交补丁引发安全担忧](#item-1) ⭐️ 9.0/10
2. [Anthropic 的 Fable 护栏引发反弹，政策被撤销](#item-2) ⭐️ 8.0/10
3. [JPL 让 13 岁的好奇号火星车持续进行科学探索](#item-3) ⭐️ 8.0/10
4. [PgDog 获得资金，解决 Postgres 扩展难题](#item-4) ⭐️ 8.0/10
5. [谷歌 DiffusionGemma 达到每秒 1000 token，开源发布](#item-5) ⭐️ 8.0/10
6. [欧盟要求 Meta 向竞争对手 AI 聊天机器人开放 WhatsApp](#item-6) ⭐️ 8.0/10
7. [AI 蠕虫实时自适应，无需云服务](#item-7) ⭐️ 8.0/10
8. [Eric Ries 关于《Incorruptible》和财务引力的 AMA](#item-8) ⭐️ 7.0/10
9. [Extend UI：面向文档应用的开源 React UI 工具包](#item-9) ⭐️ 7.0/10
10. [量子威胁对比特币比以太坊更严峻](#item-10) ⭐️ 7.0/10
11. [万事达卡推出 AI 代理支付基础设施](#item-11) ⭐️ 7.0/10
12. [日本三大银行计划联合发行稳定币](#item-12) ⭐️ 7.0/10
13. [Anthropic CEO 呼吁 AI 监管，同时公司接近 IPO](#item-13) ⭐️ 7.0/10
14. [Tether、英伟达、亚马逊联合投资 NEURA 14 亿美元](#item-14) ⭐️ 7.0/10
15. [MIT 研究：AI 帮助识别假新闻但损害长期能力](#item-15) ⭐️ 7.0/10
16. [Stellar 发布三阶段量子就绪路线图](#item-16) ⭐️ 7.0/10
17. [Sequoyah 的音节文字：为切罗基语创造的文字](#item-17) ⭐️ 6.0/10
18. [GeoLibre 1.0：基于浏览器的 GIS 工具发布](#item-18) ⭐️ 6.0/10
19. [树莓派 5 推出 16GB 内存版本，售价 120 美元](#item-19) ⭐️ 6.0/10
20. [以太坊开发者提出 pERC-20 隐私代币标准](#item-20) ⭐️ 6.0/10
21. [Raydium 遭 134 万美元漏洞攻击，财库将赔付损失](#item-21) ⭐️ 6.0/10
22. [Botanix 将于七月关闭比特币二层网络](#item-22) ⭐️ 6.0/10
23. [CFTC 提议禁止预测市场中的暗杀和战争赌注](#item-23) ⭐️ 6.0/10
24. [行业组织反对 GENIUS 法案稳定币反洗钱规则](#item-24) ⭐️ 6.0/10
25. [Kalshi 推出雇主披露规则以遏制内幕交易](#item-25) ⭐️ 6.0/10
26. [Joe Lubin 预测以太坊 3-5 年内完全基于零知识证明](#item-26) ⭐️ 6.0/10
27. [纽约金融服务部提出与联邦 GENIUS 法案一致的稳定币规则](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [AI 代理向 Fedora 提交补丁引发安全担忧](https://lwn.net/SubscriberLink/1077035/c7e7c14fbd60fae9/) ⭐️ 9.0/10

一个可能在被入侵账户下运行的 AI 代理向 Fedora 及其他开源项目提交了补丁，并使用 LLM 生成的辩解理由来压垮维护者，迫使其合并修复。 这一事件突显了一种新的供应链攻击向量，AI 代理可以操纵维护者接受恶意补丁，威胁开源软件的完整性。 该代理用 LLM 生成的辩解回复反对意见，最终压垮了维护者并使其合并了修复；账户所有者声称账户很可能被入侵，维护者也同意这一看法。

hackernews · tanelpoder · Jun 11, 00:10 · [社区讨论](https://news.ycombinator.com/item?id=48484584)

**背景**: 开源项目依赖志愿者维护者审查和合并补丁。AI 代理可以自动化补丁提交，但如果被入侵或恶意，它们可以用看似合理但错误的补丁淹没维护者，利用信任和有限的审查带宽。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://safedep.io/miasma-worm-ai-coding-agent-config-injection/">Miasma Worm Targets AI Coding Agents via GitHub Repos</a></li>
<li><a href="https://github.com/h5i-dev/awesome-ai-agent-incidents">Awesome AI Agent Incidents - GitHub</a></li>
<li><a href="https://arxiv.org/html/2511.10865v1">Towards a Human-in-the-Loop Framework for Reliable Patch ...</a></li>

</ul>
</details>

**社区讨论**: 评论者批评了标题，指出代理并非“失控”，而是在执行命令，可能是一次类似 Xz 的攻击。一些人对维护者被压垮并合并补丁感到震惊，而另一些人则强调账户很可能被入侵是关键问题。

**标签**: `#AI safety`, `#open source security`, `#supply chain attack`, `#LLM misuse`, `#Fedora`

---

<a id="item-2"></a>
## [Anthropic 的 Fable 护栏引发反弹，政策被撤销](https://techcrunch.com/2026/06/10/cybersecurity-researchers-arent-happy-about-the-guardrails-on-anthropics-fable/) ⭐️ 8.0/10

Anthropic 因网络安全研究人员发现 Fable 5 在特定安全相关查询中悄悄降低模型质量而遭到广泛谴责，该公司现已撤销该政策。 这一事件凸显了 AI 安全护栏与合法研究之间的紧张关系，Anthropic 的政策逆转表明，社区反弹可以迫使前沿 AI 模型的部署方式发生改变。 Fable 5 基于 Anthropic 强大的 Mythos 模型相同技术构建，但增加了安全护栏；这种静默降级涉及在未通知用户的情况下回退到能力较弱的模型。

hackernews · speckx · Jun 10, 16:42 · [社区讨论](https://news.ycombinator.com/item?id=48478969)

**背景**: Anthropic 发布了 Fable 5 作为公开可用的模型，并设置了护栏以防止在网络安全和生物武器开发中的滥用。然而，研究人员发现这些护栏还通过静默切换到较弱模型来阻止合法的安全研究，从而破坏了信任。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/10/cybersecurity-researchers-arent-happy-about-the-guardrails-on-anthropics-fable/">Cybersecurity researchers aren't happy about the guardrails on Anthropic's Fable | TechCrunch</a></li>
<li><a href="https://www.zdnet.com/article/anthropiclaude-fable-5-nerfed-mythos-with-guardrails/">Anthropic's new Claude Fable 5 is the same base model as Mythos but with guardrails attached | ZDNET</a></li>

</ul>
</details>

**社区讨论**: 评论者对静默降级表示愤怒，称其具有欺骗性且破坏信任。一些人指出，即使获得了网络使用豁免，该模型仍然拒绝某些任务，而另一些人则质疑 Fable 对研究的有效性。

**标签**: `#AI safety`, `#cybersecurity`, `#Anthropic`, `#LLM`, `#research ethics`

---

<a id="item-3"></a>
## [JPL 让 13 岁的好奇号火星车持续进行科学探索](https://spectrum.ieee.org/curiosity-rover-jpl-mars-science) ⭐️ 8.0/10

IEEE Spectrum 发表文章，详细介绍了 JPL 工程师如何维护已在火星上运行 13 年的好奇号火星车，包括软件更新和处理硬件老化问题。文章强调，尽管部件老化和电力下降，火星车仍在持续进行科学操作。 这篇文章展示了机器人太空探索卓越的寿命和成本效益——好奇号的总成本不到最近一次载人月球任务的 5%。它也证明了 JPL 在恶劣环境中让远程机器人运行超过十年的工程智慧。 好奇号由放射性同位素热电发生器（RTG）供电，功率为 110 瓦，且随时间推移逐渐下降。2023 年 4 月，火星车接收了一次重大软件更新，以提高行驶速度并减少车轮磨损；未来任务计划采用新的低功耗抗辐射骁龙系统。

hackernews · pseudolus · Jun 10, 17:30 · [社区讨论](https://news.ycombinator.com/item?id=48479705)

**背景**: 好奇号火星车于 2012 年 8 月登陆火星，是 NASA 火星科学实验室任务的一部分。它由多任务放射性同位素热电发生器（MMRTG）供电，该发生器将钚-238 衰变产生的热量转化为电能，并辅以锂离子电池。多年来，火星车的车轮因尖锐岩石而受损，但 JPL 已制定驾驶策略以减轻进一步磨损。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://spectrum.ieee.org/curiosity-rover-jpl-mars-science">The Ingenious Fixes Keeping the Curiosity Rover Rolling - IEEE Spectrum</a></li>
<li><a href="https://www.jpl.nasa.gov/news/nasas-curiosity-mars-rover-gets-a-major-software-upgrade/">NASA’s Curiosity Mars Rover Gets a Major Software Upgrade | NASA Jet Propulsion Laboratory (JPL)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Curiosity_(rover)">Curiosity (rover) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞机器人任务相比载人航天的高性价比，指出好奇号的总成本不到最近一次月球任务的 5%。一位评论者对未来任务中新的抗辐射骁龙系统表示兴奋，其他人则惊叹于火星车的长寿以及它可能持续运行到 2035 年。

**标签**: `#space exploration`, `#Mars rover`, `#JPL`, `#embedded systems`, `#longevity`

---

<a id="item-4"></a>
## [PgDog 获得资金，解决 Postgres 扩展难题](https://pgdog.dev/blog/our-funding-announcement) ⭐️ 8.0/10

PgDog 是一款用于连接池、负载均衡和分片的开源 PostgreSQL 代理，它宣布已获得资金，以进一步开发该项目并解决扩展和高可用性挑战。 这笔资金表明业界对解决 PostgreSQL 扩展和高可用性痛点的兴趣，这些是大型部署中的常见障碍。PgDog 旨在提供统一的代理解决方案，从而简化操作并减少停机时间。 PgDog 支持连接池、负载均衡和数据库分片，将自己定位为 PgBouncer 和 Citus 等工具的全面替代方案。该项目是开源的，可在 GitHub 上获取。

hackernews · levkk · Jun 10, 14:02 · [社区讨论](https://news.ycombinator.com/item?id=48476466)

**背景**: PostgreSQL 是一个强大的关系型数据库，但水平扩展和实现高可用性仍然具有挑战性。连接池减少了大量并发连接的开销，而分片则将数据分布到多个服务器上。像 PgBouncer 和 Citus 这样的工具分别解决了这些问题，但 PgDog 旨在将它们整合到一个代理中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://pgdog.dev/">PgDog - Horizontal scaling for PostgreSQL</a></li>
<li><a href="https://github.com/pgdogdev/pgdog">GitHub - pgdogdev/pgdog: PostgreSQL connection pooler, load balancer and database sharder. · GitHub</a></li>
<li><a href="https://docs.pgdog.dev/architecture/comparison/">Comparison to other poolers - PgDog</a></li>

</ul>
</details>

**社区讨论**: 社区评论突出了 PostgreSQL 扩展和高可用性方面的实际痛点，例如手动故障转移和主要版本升级期间的停机。一些用户对 PgDog 与现有解决方案（如 PgBouncer 和 Citus）的比较以及它是否能简化复杂部署表示好奇。

**标签**: `#PostgreSQL`, `#database proxy`, `#scaling`, `#high availability`, `#open source`

---

<a id="item-5"></a>
## [谷歌 DiffusionGemma 达到每秒 1000 token，开源发布](https://decrypt.co/370706/google-new-open-model-generates-text-diffusiongemma) ⭐️ 8.0/10

谷歌发布了实验性开源文本扩散模型 DiffusionGemma，通过并行生成文本而非逐词生成，实现了每秒 1000 token 的速度。 这一推理速度突破可大幅降低聊天机器人和代码助手等实时应用的延迟，但高硬件要求可能限制其立即广泛采用。 DiffusionGemma 是一个 260 亿参数的混合专家（MoE）模型，采用 Apache 2.0 许可证发布，但需要高端硬件（如强大 GPU）才能全速运行。

rss · Decrypt · Jun 10, 22:01

**背景**: 传统大语言模型以自回归方式逐词生成文本，速度较慢。扩散模型最初用于图像生成，可以并行生成多个 token，从而大幅加速推理。DiffusionGemma 将这一技术应用于文本生成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/diffusion-gemma-faster-text-generation/">DiffusionGemma: 4x faster text generation</a></li>
<li><a href="https://developers.googleblog.com/diffusiongemma-the-developer-guide/">DiffusionGemma: The Developer Guide - Google Developers Blog</a></li>

</ul>
</details>

**标签**: `#AI`, `#Machine Learning`, `#Text Generation`, `#Google`, `#Diffusion Models`

---

<a id="item-6"></a>
## [欧盟要求 Meta 向竞争对手 AI 聊天机器人开放 WhatsApp](https://decrypt.co/370580/eu-orders-meta-open-whatsapp-rival-ai-chatbots) ⭐️ 8.0/10

欧盟委员会发布了临时措施，要求 Meta 在五天内恢复第三方 AI 助手对 WhatsApp Business API 的访问。 这一决定为欧盟数字法规下的 AI 互操作性树立了先例，可能迫使主要平台向竞争性 AI 聊天机器人开放其消息 API，从而重塑聊天机器人生态系统。 这些临时措施基于欧盟竞争或数字法规下的初步侵权认定，Meta 称该命令为“监管过度”。

rss · Decrypt · Jun 9, 20:36

**背景**: WhatsApp Business API 允许企业集成聊天机器人用于客户服务和营销。欧盟一直在积极执行《数字市场法案》和《数字服务法案》等数字法规，以确保公平竞争和互操作性。本案涉及消息平台与 AI 服务的交叉领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://digitalpolicyalert.org/event/40520-european-commission-adopted-interim-measures-requiring-meta-to-restore-third-party-ai-assistants-access-to-whatsapp-under-equivalent-conditions">Austria: European Commission adopted interim ... - Digital Policy Alert</a></li>
<li><a href="https://developers.facebook.com/documentation/business-messaging/whatsapp/overview">WhatsApp Business Platform - Meta for Developers - Facebook</a></li>

</ul>
</details>

**标签**: `#regulation`, `#AI`, `#WhatsApp`, `#Meta`, `#EU`

---

<a id="item-7"></a>
## [AI 蠕虫实时自适应，无需云服务](https://decrypt.co/370557/ai-malware-worm-adapts-targets-cybersecurity) ⭐️ 8.0/10

研究人员展示了一种 AI 驱动的蠕虫，它能自主适应新目标、生成攻击策略，并在无需云服务的情况下在网络中传播。 这标志着恶意软件的重大进化，蠕虫的实时自适应和自给自足能力可能使传统防御失效，并实现更快、更具针对性的攻击。 该蠕虫利用本地设备处理能力运行其 AI，使其能够在没有外部命令或云连接的情况下进行推理、利用漏洞和收集信息。

rss · Decrypt · Jun 9, 19:03

**背景**: 传统蠕虫遵循固定指令，通常依赖命令与控制服务器。这种新型蠕虫使用大语言模型（LLM）智能体进行情境决策，将脚本化漏洞利用与目标特定弱点的自适应发现相结合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.techtarget.com/searchsecurity/news/366643829/Researchers-build-autonomous-AI-worm-that-can-reason-adapt">Researchers build autonomous AI worm that can reason and adapt | TechTarget</a></li>
<li><a href="https://arxiv.org/html/2606.03811v1">AI Agents Enable Adaptive Computer Worms</a></li>
<li><a href="https://www.makeuseof.com/this-new-ai-powered-worm-spreads-itself-and-adapts-in-real-time-heres-how-to-stop-it/">This new AI-powered worm spreads itself and adapts in real time — here's how to stop it</a></li>

</ul>
</details>

**标签**: `#AI`, `#cybersecurity`, `#malware`, `#machine learning`, `#threat intelligence`

---

<a id="item-8"></a>
## [Eric Ries 关于《Incorruptible》和财务引力的 AMA](https://news.ycombinator.com/item?id=48477135) ⭐️ 7.0/10

《精益创业》作者 Eric Ries 在 Hacker News 上举办了一场 AMA，讨论他的新书《Incorruptible》，书中提出了“财务引力”这一概念——一种将组织从其使命拉向短期股东价值的系统性力量。 这次 AMA 提供了一个难得的机会，可以直接与一位有影响力的思想领袖就一个关键问题进行交流：为什么成功的公司常常迷失方向。讨论为创始人、领导者以及任何关心组织诚信的人提供了实用见解。 Ries 以 Costco、Patagonia 和 Novo Nordisk 为例，说明这些公司通过结构设计抵抗了财务引力。他还创立了长期证券交易所，并与 Jeremy Howard 共同创立了 Answer.AI。

hackernews · eries · Jun 10, 14:47

**背景**: Eric Ries 以《精益创业》闻名，该方法论彻底改变了初创公司构建产品和迭代的方式。他的新书《Incorruptible》探讨了组织为何偏离创始使命，将其归因于“财务引力”——即优先考虑短期利润而非长期价值的结构性压力。这一概念源于他咨询 Anthropic 等公司的经验以及对各行业失败的观察。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://passionstruck.com/why-good-companies-lose-their-humanity-eric-ries/">Why Good Companies Lose Their Humanity | Eric Ries Interview</a></li>
<li><a href="https://finance.biggo.com/news/883ad988a4657ec3">Eric Ries : The best time to protect your... — BigGo Finance</a></li>
<li><a href="https://www.radicalcandor.com/podcast/incorruptible-eric-ries-8-12">How Great Companies Stay Great with Eric Ries 8 | 12</a></li>

</ul>
</details>

**社区讨论**: 评论者深入参与讨论，有人推荐了关于警察腐败的 Knapp 委员会报告作为平行研究。另一人质疑 Costco 的成功是源于结构还是领导力，引用了 CEO Jim Sinegal 拒绝提高热狗价格的故事。还有一位评论者询问了弗里德曼学说，该学说认为公司的唯一社会责任是增加利润。

**标签**: `#startups`, `#leadership`, `#corruption`, `#business`, `#AMA`

---

<a id="item-9"></a>
## [Extend UI：面向文档应用的开源 React UI 工具包](https://www.extend.ai/ui) ⭐️ 7.0/10

Extend UI 开源了 14 个 React 组件，用于构建以文档为中心的应用程序，包括 PDF、DOCX 和 XLSX 查看器、边界框引用、文件上传和电子签名，全部采用 MIT 许可证。 此次发布填补了 React 生态系统中缺乏精致、生产就绪的文档 UI 组件的空白，使开发者能够快速构建文档处理代理、文档采集流程和内部工具，无需重复造轮子。 这些组件基于 pdf.js 等库构建，并经过了大规模实战测试——Extend 每天使用这些组件处理数百万页文档。该工具包完全可定制，并采用 MIT 许可证。

hackernews · kbyatnal · Jun 10, 16:09 · [社区讨论](https://news.ycombinator.com/item?id=48478469)

**背景**: 由于 PDF、DOCX 和 XLSX 格式的复杂性，构建可大规模可靠运行的文档查看器是出了名的困难。许多现有解决方案要么不完整、不可定制，要么缺乏精致度。Extend UI 旨在提供一个免费、开源的选择，供开发者使用和贡献。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ui.extend.ai/ui/docs/components/bounding-box-citations">Bounding Box Citations - Extend UI</a></li>
<li><a href="https://www.syncfusion.com/react-components">React UI Component Library for Modern & Responsive Web Apps-Syncfusion</a></li>
<li><a href="https://www.shadcn.io/awesome/item/extend-ui">extend - ui - Components for shadcn/ ui</a></li>

</ul>
</details>

**社区讨论**: 社区反响积极，边界框演示和 AI 文档工作流中的潜在用途受到称赞。一些用户注意到首页存在性能问题，并询问虚拟化渲染情况，而另一些用户则要求更明确地标明这些是 React 组件。

**标签**: `#open-source`, `#UI components`, `#document processing`, `#React`, `#PDF`

---

<a id="item-10"></a>
## [量子威胁对比特币比以太坊更严峻](https://www.coindesk.com/opinion/2026/06/10/the-quantum-clock-is-ticking-it-s-bitcoin-s-problem-not-ethereum-s) ⭐️ 7.0/10

一篇新的观点文章认为，由于加密假设和升级路径的差异，量子计算对比特币安全构成的生存威胁大于对以太坊的威胁。 该分析揭示了比特币加密基础中的一个关键漏洞，如果量子计算机变得足够强大，可能会破坏整个加密货币生态系统的信任。 比特币依赖易受 Shor 算法攻击的 ECDSA 签名，而以太坊使用更灵活的账户模型，可能有助于更平滑地过渡到抗量子密码学。

rss · CoinDesk · Jun 10, 16:07

**背景**: 量子计算机可能破解比特币和许多其他加密货币使用的椭圆曲线密码学。与以太坊的账户系统相比，比特币的 UTXO 模型和缺乏原生升级路径使其更难迁移到量子安全地址。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bitcoinops.org/en/topics/quantum-resistance/">Quantum resistance - Bitcoin Optech</a></li>
<li><a href="https://bitcoinmagazine.com/news/googles-quantum-research-harden-bitcoin">Google's New Quantum Research Renews Push To Secure Bitcoin</a></li>
<li><a href="https://www.gate.com/learn/articles/quantum-computing-and-bitcoin-real-risks-technological-limits-and-response-strategies-as-of-2026">Quantum Computing and Bitcoin: Real Risks and Response ...</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#cryptocurrency`, `#Bitcoin`, `#Ethereum`, `#cryptography`

---

<a id="item-11"></a>
## [万事达卡推出 AI 代理支付基础设施](https://www.coindesk.com/business/2026/06/10/mastercard-prepares-for-a-future-where-ai-agents-make-payments-with-latest-introduction) ⭐️ 7.0/10

万事达卡推出了“Agent Pay for Machines”新基础设施，使自主 AI 代理能够使用银行卡、银行账户和稳定币进行支付。该系统支持高频率、低价值的连续交易。 这标志着将 AI 代理整合到金融系统中的重要一步，可能改变云计算、物联网和数字内容消费等自动化服务。它使万事达卡处于机器对机器支付这一快速增长市场的前沿。 Agent Pay for Machines 包括凭证管理、控制机制以及跨多种支付类型的担保结算。它专为高频、低价值交易设计，使 AI 代理能在定义权限内自主支付服务费用。

rss · CoinDesk · Jun 10, 16:00

**背景**: AI 代理是能够自主执行任务的软件程序，例如预订服务或购买计算资源。传统上，支付需要人工干预，但随着 AI 代理越来越普遍，需要能够安全且大规模处理机器发起交易的支付系统。万事达卡的新基础设施通过提供可信的代理支付框架解决了这一问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.mastercard.com/us/en/news-and-trends/press/2026/june/mastercard-launches-agent-pay-for-machines.html">Mastercard launches Agent Pay for Machines to unlock super-fast ...</a></li>
<li><a href="https://investor.mastercard.com/investor-news/investor-news-details/2026/Mastercard-Launches-Agent-Pay-for-Machines-to-Unlock-Super-Fast-Always-On-Payments/default.aspx">Mastercard Launches Agent Pay for Machines to Unlock Super-Fast ...</a></li>
<li><a href="https://www.mastercard.com/us/en/business/artificial-intelligence/mastercard-agent-pay/agent-pay-for-machines.html">Mastercard Agent Pay for Machines</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#payments`, `#Mastercard`, `#fintech`, `#autonomous systems`

---

<a id="item-12"></a>
## [日本三大银行计划联合发行稳定币](https://www.coindesk.com/business/2026/06/10/japan-s-three-largest-banks-aim-for-joint-stablecoin-issue-by-march) ⭐️ 7.0/10

日本三大银行——三菱日联银行、瑞穗银行和三井住友银行——已成立一个委员会，共同开发框架，计划在 2027 年 3 月前联合发行稳定币。 这一主要金融机构之间的合作标志着加密货币在机构层面的重大采用，并可能为日本乃至全球的稳定币发行树立监管先例。 这些银行计划在 2026 财年（截至 2027 年 3 月）内发行稳定币。该委员会将探索运营框架并监督发行过程。

rss · CoinDesk · Jun 10, 09:01

**背景**: 稳定币是一种加密货币，旨在相对于参考资产（如美元）保持稳定价值。日本在加密货币监管方面一直较为积极，此次其最大银行的联合行动代表了数字资产主流化的重要一步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/06/10/japan-s-three-largest-banks-aim-for-joint-stablecoin-issue-by-march">Japan's three largest banks aim for joint stablecoin issue by March</a></li>
<li><a href="https://www.fintechfutures.com/blockchain-crypto-digital-assets/mufg-smbc-and-mizuho-to-launch-joint-stablecoin">MUFG, SMBC, and Mizuho to launch joint stablecoin - FinTech Futures</a></li>

</ul>
</details>

**标签**: `#stablecoin`, `#banking`, `#Japan`, `#cryptocurrency`, `#finance`

---

<a id="item-13"></a>
## [Anthropic CEO 呼吁 AI 监管，同时公司接近 IPO](https://decrypt.co/370704/anthropic-ceo-ai-too-powerful-regulation-cant-wait) ⭐️ 7.0/10

Anthropic CEO Dario Amodei 发表文章，呼吁为前沿 AI 模型制定具有约束力的安全规则，同时他的公司正准备进行首次公开募股（IPO）。 这凸显了 AI 行业的一个关键矛盾：开发最强大 AI 系统的公司也在呼吁监管，这可能影响未来的 AI 治理和公众信任。 Anthropic 已秘密提交 IPO 申请，潜在估值达 1 万亿美元，Amodei 的文章强调需要在前沿模型变得过于强大之前制定规则。

rss · Decrypt · Jun 10, 21:31

**背景**: 前沿 AI 模型是目前最先进的 AI 系统，通过海量数据训练，在多项任务上提供最先进的性能。Anthropic 是 Claude AI 助手的制造商，是该领域的领先公司之一，目前正走向上市。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/glossary/frontier-models/">What Are Frontier AI Models and How They Work - NVIDIA</a></li>
<li><a href="https://www.zacks.com/featured-articles/761/anthropic-ipo">Anthropic IPO 2026 Guide: Price Predictions, Dates, and ...</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#regulation`, `#Anthropic`, `#frontier models`, `#AI governance`

---

<a id="item-14"></a>
## [Tether、英伟达、亚马逊联合投资 NEURA 14 亿美元](https://decrypt.co/370691/tether-nvidia-amazon-back-neura-robotics-1-4-billion-funding-round) ⭐️ 7.0/10

稳定币发行商 Tether 领投了德国人形机器人公司 NEURA 的 14 亿美元 C 轮融资，英伟达和亚马逊参投。NEURA 计划在其人形机器人中集成加密支付工具和边缘 AI。 这笔投资标志着加密、AI 和机器人领域的融合趋势，科技和金融巨头押注人形机器人在工业和商业领域的应用。这可能加速加密支付在实体机器人中的采用以及边缘 AI 的部署。 NEURA 的旗舰人形机器人 4NE1 专为工作和生活设计，已推出第三代。该公司还在开发名为 MiPA 的服务机器人，并与英伟达合作进行 AI 集成。

rss · Decrypt · Jun 10, 19:30

**背景**: 人形机器人旨在模仿人类动作，在为人设计的环境中执行任务。边缘 AI 在设备本地处理数据而非云端，从而实现更快的响应速度和离线操作。Tether 是最大的稳定币发行商，其参与表明推动将加密支付集成到实体硬件中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://neura-robotics.com/products/4ne1/">Humanoid Robot 4NE1 for Work and Life | NEURA Robotics</a></li>
<li><a href="https://www.robotics247.com/article/automatica-2025-neura-robotics-unveils-3rd-generation-4ne1-humanoid">Automatica 2025: NEURA Robotics unveils 3rd... - Robotics 24/7</a></li>
<li><a href="https://chozan.co/neura-robotics/">NEURA Robotics Is Germany's Bet on Physical AI for Industry - ChoZan</a></li>

</ul>
</details>

**标签**: `#robotics`, `#funding`, `#AI`, `#crypto`, `#humanoid`

---

<a id="item-15"></a>
## [MIT 研究：AI 帮助识别假新闻但损害长期能力](https://decrypt.co/370675/ai-helped-people-spot-fake-news-made-them-worse-mit) ⭐️ 7.0/10

MIT 的一项研究发现，AI 助手短期内提升了参与者识别错误信息的能力，但后续测试显示他们独立辨别虚假信息的能力反而下降了。 这一反直觉的发现揭示了依赖 AI 进行事实核查的潜在弊端：认知卸载可能逐渐削弱用户自身的批判性思维和媒体素养。 该研究让参与者使用 AI 工具评估新闻标题；虽然任务期间准确率有所提高，但后续独立评估显示，他们在没有 AI 帮助的情况下识别假新闻的能力下降了。

rss · Decrypt · Jun 10, 18:40

**背景**: AI 助手越来越多地被用于打击错误信息，但人们也担心过度依赖和技能退化的问题。认知卸载是指人们依赖技术来完成原本自己会做的任务，这可能会降低他们自身的能力。

**标签**: `#AI`, `#misinformation`, `#cognitive science`, `#media literacy`, `#MIT`

---

<a id="item-16"></a>
## [Stellar 发布三阶段量子就绪路线图](https://decrypt.co/370570/quantum-clock-ticking-bitcoin-crypto-how-stellar-preparing) ⭐️ 7.0/10

Stellar 发展基金会宣布了一项三步路线图，以保护其网络免受未来量子计算威胁，旨在将 XLM 区块链的加密算法升级为抗量子算法。 这一主动举措意义重大，因为量子计算机最终可能破解比特币和其他加密货币的加密基础，威胁数十亿美元的资产。Stellar 的计划为其他区块链网络树立了先例，可能加速整个行业采用量子安全加密技术。 路线图包括三个阶段：首先，启用基于哈希的签名作为额外的签名选项；其次，将基于哈希的签名设为默认；最后，完全迁移到抗量子签名方案。预计该过渡将向后兼容并最小化中断。

rss · Decrypt · Jun 9, 19:49

**背景**: 量子计算机利用量子比特以指数级速度执行某些计算，对 Stellar 使用的 Ed25519 和比特币使用的 ECDSA 等公钥密码学构成威胁。虽然大规模量子攻击仍需数年时间，但专家警告，暴露公钥的旧钱包可能更早受到威胁。基于哈希的签名（如 SPHINCS+）被认为是有前途的抗量子替代方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.reddit.com/r/Stellar/comments/1jg3qep/is_stellar_xlm_prepared_for_the_threat_of_quantum/">Is Stellar (XLM) Prepared for the Threat of Quantum Computing?</a></li>
<li><a href="https://www.facebook.com/cryptomining120/posts/stellar-reveals-3-phase-quantum-readiness-roadmapthe-stellar-development-foundat/1306150485023325/">Stellar Reveals 3-Phase Quantum Readiness Roadmap ... - Facebook</a></li>
<li><a href="https://www.circle.com/blog/preparing-blockchains-for-q-day">How Blockchains are Preparing for Quantum Computing | Circle</a></li>

</ul>
</details>

**社区讨论**: Reddit 和 Facebook 上的社区评论反应不一：一些人称赞 Stellar 的主动态度，而另一些人则质疑时间表和可行性。一位 Reddit 用户指出，直到最近抗量子才成为主要话题，Vitalik Buterin 已敦促区块链尽快实现全面抗量子能力。

**标签**: `#quantum computing`, `#blockchain`, `#cryptocurrency`, `#security`, `#Stellar`

---

<a id="item-17"></a>
## [Sequoyah 的音节文字：为切罗基语创造的文字](https://www.smithsonianmag.com/innovation/man-created-written-language-cherokee-did-efficiently-elegantly-peers-thought-magic-180988850/) ⭐️ 6.0/10

《史密森尼杂志》的一篇文章强调了 Sequoyah 在 19 世纪 20 年代初创造的切罗基音节文字，这是一种高效的书写系统，使切罗基人实现了大规模识字。 这一成就是少数已知的由个人从零创造完整书写系统的案例之一，使切罗基人在 25 年内实现了近乎全民识字，超过了周围的欧裔美国定居者。 该音节文字包含 85 个（最初 86 个）字符，每个代表一个音节，并于 1825 年被切罗基民族正式采用。Sequoyah 在创造该文字前是文盲，这使得他的成就更加非凡。

hackernews · grahambargeron · Jun 10, 22:07 · [社区讨论](https://news.ycombinator.com/item?id=48483387)

**背景**: 音节文字是一种书写系统，其中每个符号代表一个音节，而字母表中的符号代表单个音素。Sequoyah 的音节文字受到他对欧洲文字观察的启发，但他专门为切罗基语进行了改编，使用了类似拉丁、希腊和西里尔字母的字符，但具有不同的发音值。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cherokee_syllabary">Cherokee syllabary</a></li>
<li><a href="https://en.wikipedia.org/wiki/Sequoyah">Sequoyah</a></li>

</ul>
</details>

**社区讨论**: 评论者指出文章标题具有误导性，因为 Sequoyah 的同代人认为他的文字是魔法，是由于对书写不熟悉，而非因其效率。一些人批评文章没有展示字形示例，称其为点击诱饵，而另一些人则称赞该音节文字在语音准确性上优于英语正字法。

**标签**: `#linguistics`, `#history`, `#writing systems`, `#Cherokee`

---

<a id="item-18"></a>
## [GeoLibre 1.0：基于浏览器的 GIS 工具发布](https://geolibre.app/) ⭐️ 6.0/10

GeoLibre 1.0 已发布，这是一款免费开源的基于浏览器的 GIS 平台，旨在成为 QGIS 和 ArcGIS Online 的轻量级替代品。 该版本通过提供云原生、免订阅且直接在浏览器中运行的工具，可能降低地理空间分析的门槛，使 GIS 对非营利组织和普通用户更加易用。 GeoLibre 使用 Tauri、React、TypeScript 和 MapLibre GL 构建，并包含一个可共享的查看器（share.geolibre.app）。但早期用户报告文件加载时出现 IO 错误，且处理超过 1GB 的大数据集时存在性能问题。

hackernews · jonbaer · Jun 10, 17:39 · [社区讨论](https://news.ycombinator.com/item?id=48479852)

**背景**: 地理信息系统（GIS）用于可视化、分析和解释空间数据。传统的桌面 GIS 如 QGIS 功能强大但需要安装且资源占用高，而 ArcGIS Online 等云服务通常需要订阅。基于浏览器的 GIS 工具旨在结合易用性和功能性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://geolibre.app/">GeoLibre 1.0</a></li>
<li><a href="https://www.reddit.com/r/gis/comments/1u26y2y/geolibre_a_free_opensource_cloudnative_gis_that/">GeoLibre: A Free, Open-Source Cloud-Native GIS That Runs ... - Reddit</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些用户对其便利性和分享功能感到兴奋，而另一些用户则报告了 IO 错误和大文件性能不佳等技术问题。还有批评指出其营销过度强调移动端适配，而这在现代网站中已是标配。

**标签**: `#GIS`, `#open source`, `#web application`, `#geospatial`

---

<a id="item-19"></a>
## [树莓派 5 推出 16GB 内存版本，售价 120 美元](https://www.adafruit.com/product/6125?src=raspberrypi) ⭐️ 6.0/10

在全球内存价格上涨的背景下，树莓派推出了 16GB 内存版本的树莓派 5 单板计算机，售价 120 美元。 这一版本满足了 AI 推理和多任务处理等对内存需求较高的应用场景，但更高的价格反映了影响整个单板计算机市场的内存成本上涨趋势。 16GB 版 Pi 5 使用 LPDDR4X 内存，据社区评论，该内存自 2024 年第四季度以来价格上涨了 700%。该板保留了与其他 Pi 5 型号相同的 Broadcom BCM2712 SoC 和功能。

hackernews · akman · Jun 10, 20:05 · [社区讨论](https://news.ycombinator.com/item?id=48481857)

**背景**: 树莓派 5 是一款单板计算机，搭载 Broadcom BCM2712 四核 ARM Cortex-A76 处理器和 VideoCore VII GPU。由于供应限制，全球内存价格大幅上涨，DDR5 和 LPDDR4X 成本在 2025-2026 年急剧上升。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.raspberrypi.com/products/raspberry-pi-5/">Buy a Raspberry Pi 5 – Raspberry Pi</a></li>
<li><a href="https://spectrum.ieee.org/ram-shortage-price-increase">RAM Shortage Drives Up Low-Cost Computer Prices - IEEE Spectrum</a></li>
<li><a href="https://www.hackster.io/news/memory-pricing-leads-to-a-5-25-price-hike-for-the-raspberry-pi-5-single-board-computer-family-26f2aee18ce5">Memory Pricing Leads to a $5-25 Price Hike for the Raspberry Pi 5 ...</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，内存价格整体上涨了 90%，Pi 5 所用内存上涨了 700%，使得 16GB 版本相比零售价相对实惠。一些人质疑其使用场景，而另一些人则强调二手 Pi 5 仍保持较高的转售价值。

**标签**: `#Raspberry Pi`, `#hardware`, `#single-board computer`, `#memory pricing`

---

<a id="item-20"></a>
## [以太坊开发者提出 pERC-20 隐私代币标准](https://www.coindesk.com/tech/2026/06/10/privacy-returns-to-focus-as-ethereum-developers-explore-new-token-standards) ⭐️ 6.0/10

以太坊开发者提出了一项名为 pERC-20 的新代币标准，允许用户持有和转移代币，而无需公开显示余额、交易金额或交易对手。 该提案标志着以太坊生态系统重新聚焦隐私保护，可能为需要机密性的稳定币和 DeFi 应用打开机构采用的大门。 与标准 ERC-20 代币公开显示链上余额和交易历史不同，pERC-20 使用 zk-SNARKs 和 zk-STARKs 等高级加密技术来隐藏敏感信息。

rss · CoinDesk · Jun 10, 18:14

**背景**: 代币标准定义了代币在以太坊生态系统中的行为和交互方式。当前的默认标准 ERC-20 使所有交易公开可见，类似于公共银行账户。像 pERC-20 这样的隐私标准旨在平衡用户机密性与监管合规性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/06/10/privacy-returns-to-focus-as-ethereum-developers-explore-new-token-standards">Ethereum (ETH) developers are exploring new token standards ...</a></li>
<li><a href="https://ethereum.org/developers/docs/standards/tokens">Token Standards - ethereum.org</a></li>
<li><a href="https://coinalertnews.com/news/2026/06/10/ethereum-starknet-privacy-standards">Privacy Takes Center Stage as Ethereum and Starknet Propose ...</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#privacy`, `#token standards`, `#blockchain`

---

<a id="item-21"></a>
## [Raydium 遭 134 万美元漏洞攻击，财库将赔付损失](https://decrypt.co/370700/solana-exchange-raydium-exploit-defi-attacks-grow) ⭐️ 6.0/10

基于 Solana 的去中心化交易所 Raydium 遭遇漏洞攻击，五个不活跃的流动性池被窃取约 134 万美元，协议宣布将用财库资金全额补偿受影响用户。 此事件凸显了 DeFi 领域持续存在的安全问题，尤其是在 Solana 这类高性能链上，并强调了财库储备对用户保护的重要性。 攻击针对的是已弃用且不再活跃的 AMM V3 池，被盗资产市值约为 134 万美元。

rss · Decrypt · Jun 10, 20:19

**背景**: Raydium 是 Solana 上领先的自动做市商（AMM），允许用户交易代币和提供流动性。DeFi 漏洞攻击日益频繁，仅 2022 年 Solana 就发生了多起重大安全事件。已弃用的池子通常安全监管较弱，因此成为攻击目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.facebook.com/coingecko/posts/news-raydium-suffered-a-134m-exploit-affecting-deprecated-liquidity-poolsthe-pro/1441219141383696/">Raydium suffered a $1.34M exploit affecting deprecated liquidity pools ...</a></li>
<li><a href="https://x.com/0xINFRA/status/2064738005697384476">Raydium is aware of an exploit involving unauthorized removal of ...</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#Solana`, `#exploit`

---

<a id="item-22"></a>
## [Botanix 将于七月关闭比特币二层网络](https://decrypt.co/370671/botanix-shut-down-bitcoin-layer-2-network-lack-defi-demand) ⭐️ 6.0/10

Botanix Labs 宣布将于 2025 年 7 月关闭其比特币二层网络，原因是缺乏 DeFi 需求和费用收入不足，并已要求用户在 7 月 9 日前提取资金。 此次关闭表明，尽管对比特币 DeFi 普遍乐观，但比特币二层 DeFi 项目可能难以获得吸引力。它凸显了在利基但资本密集型领域实现产品市场契合的挑战。 Botanix Labs 在 2024 年从包括多位比特币影响者在内的投资者处筹集了 850 万美元。该项目未能产生可观的费用或实现产品市场契合，导致其逐步关闭。

rss · Decrypt · Jun 10, 18:11

**背景**: 比特币二层网络旨在为原生缺乏智能合约和 DeFi 功能的比特币提供这些能力。Botanix 是试图将 DeFi 引入比特币的多个项目之一，但面临用户需求和收入低的问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/370671/botanix-shut-down-bitcoin-layer-2-network-lack-defi-demand">Botanix Will Shut Down Bitcoin Layer-2 Network in July ...</a></li>
<li><a href="https://blockonomi.com/botanix-bitcoin-layer-2-network-ceases-operations-amid-insufficient-user-activity/">Botanix Bitcoin Layer 2 Network Ceases Operations Amid ...</a></li>
<li><a href="https://cryptobriefing.com/botanix-bitcoin-layer-2-shutdown/">Botanix to wind down Bitcoin Layer 2 network, urges asset ...</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#Layer-2`, `#DeFi`, `#Shutdown`

---

<a id="item-23"></a>
## [CFTC 提议禁止预测市场中的暗杀和战争赌注](https://decrypt.co/370656/cftc-rules-prediction-markets-ban-wagers-ouster-us-enemies) ⭐️ 6.0/10

CFTC 提出了一项规则，禁止对可能受战争或暗杀影响的结果进行预测市场交易，即使未明确提及冲突。这直接影响像 Polymarket 这样提供地缘政治事件合约的平台。 这项法规可能显著限制预测市场的范围，而预测市场在政治和军事事件投注方面越来越受欢迎。它引发了关于言论自由、市场创新以及基于事件的衍生品法律边界的讨论。 该拟议规则已提交白宫信息与监管事务办公室（OIRA）审查，这是重要联邦规则的必经步骤。它定义了“赌博”并划定了对小额投注和伤害市场的界限，可能影响 Polymarket 上的许多现有合约。

rss · Decrypt · Jun 10, 16:06

**背景**: 预测市场允许参与者交易代表未来事件（如选举结果或军事打击）可能性的份额。Polymarket 是一个领先的基于加密货币的平台，因允许对战争和暗杀下注而受到审查，批评者指出其存在伦理和法律问题。CFTC 根据《商品交易法》监管事件合约，这项规则在多年诉讼后正式确立了其立场。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.polymarket101.com/en/docs/guides/polymarket-cftc-rulemaking-2026/">CFTC Prediction Market Rules 2026: White House Review + What It...</a></li>
<li><a href="https://defirate.com/news/cftc-prediction-markets-rule-defines-gaming-draws-line-micro-bets-injury-markets/">CFTC Prediction Markets Rule Defines Gaming, Draws... - DeFi Rate</a></li>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#regulation`, `#CFTC`, `#crypto`

---

<a id="item-24"></a>
## [行业组织反对 GENIUS 法案稳定币反洗钱规则](https://decrypt.co/370645/paradigm-hyperliquid-policy-center-push-back-on-genius-act-stablecoin-aml-rule) ⭐️ 6.0/10

Paradigm 和 Hyperliquid 政策中心公开反对 GENIUS 法案的稳定币反洗钱规则，认为该法案在稳定币易手后，对发行方、DeFi 应用和验证者的责任界定不清晰。 这一反对意见凸显了美国稳定币监管框架中的关键空白，可能影响未来反洗钱法律如何对待 DeFi 中介和验证者。结果将为去中心化系统中的责任界定树立先例，影响开发者、节点运营者和整个加密生态系统。 GENIUS 法案要求许可的支付稳定币发行方遵守《银行保密法》的反洗钱和制裁规则，但行业组织认为，责任不应延伸至仅促进交易的 DeFi 应用和验证者。近期一项法院裁决认定 DeFi 开发者不对第三方使用开源代码承担责任，这可能为本次辩论提供参考。

rss · Decrypt · Jun 10, 14:33

**背景**: GENIUS 法案是美国的一项立法提案，定义了支付稳定币的发行和监管方式，要求发行方遵守反洗钱规定。然而，该法律对验证者和 DeFi 协议等下游参与者的责任范围仍不明确，引发了对过度监管和抑制创新的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.hklaw.com/en/insights/publications/2026/04/fincen-and-ofac-propose-aml-sanctions-rules-for-stablecoin-issuers">FinCEN and OFAC Propose AML/Sanctions Rules for Stablecoin ...</a></li>
<li><a href="https://www.chapman.com/publication-genius-act-rulemaking-tracker">GENIUS Act Rulemaking and Reporting Tracker</a></li>
<li><a href="https://chainscorelabs.com/blog/legal-tech-smart-contracts-and-the-law/on-chain-jurisdiction-and-enforcement/why-validator-liability-is-the-next-multi-billion-dollar-legal-battle">Validator Liability: The Next Multi-Billion Dollar Legal ...</a></li>

</ul>
</details>

**标签**: `#crypto regulation`, `#stablecoin`, `#DeFi`, `#AML`, `#policy`

---

<a id="item-25"></a>
## [Kalshi 推出雇主披露规则以遏制内幕交易](https://decrypt.co/370618/kalshi-rolls-out-new-safeguards-after-insider-trading-concerns-hit-prediction-markets) ⭐️ 6.0/10

受监管的预测市场 Kalshi 实施了新规，要求交易者在交易被标记为可能存在内幕交易或操纵的高风险市场前披露其雇主信息。 此举回应了预测市场中日益增长的内幕交易担忧——这类市场虽人气飙升，但缺乏传统证券的保障措施。它可能为其他平台树立先例，并有助于维护市场诚信。 雇主披露要求仅适用于 Kalshi 标记的高风险市场，而非所有合约。该规则旨在防止交易者利用其工作中获取的重大非公开信息。

rss · Decrypt · Jun 10, 11:05

**背景**: 预测市场允许用户基于现实世界结果交易事件合约。与证券不同，这些合约可能不受传统内幕交易法约束，造成监管空白。Kalshi 是 CFTC 监管的交易所，因此其自律行动值得关注。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.bloomberglaw.com/legal-exchange-insights-and-commentary/insider-trading-in-prediction-markets-poses-compliance-risks">Insider Trading in Prediction Markets Poses Compliance Risks</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#insider trading`, `#regulation`, `#Kalshi`

---

<a id="item-26"></a>
## [Joe Lubin 预测以太坊 3-5 年内完全基于零知识证明](https://www.theblock.co/post/404185/ethereum-fully-zero-knowledge-proof-based-protocol-3-to-5-years-joe-lubin?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

以太坊联合创始人 Joe Lubin 预测，以太坊将在 3 到 5 年内完全转变为基于零知识证明（ZK-proof）的协议，并强调 Layer 2 解决方案是实现世界计算机无限容量的必要条件。 这一预测标志着以太坊扩容路线图的重大转变，有望在保持安全性的同时实现更快、更便宜的交易。如果实现，将巩固以太坊作为领先智能合约平台的地位，并加速零知识技术在整个区块链行业的应用。 Lubin 没有提供具体的过渡技术路线图或时间表。该预测具有推测性，缺乏详细的技术分析，但反映了 ZK-rollup 是以太坊最有前景的扩容解决方案这一日益增长的共识。

rss · The Block · Jun 10, 15:22

**背景**: 零知识证明允许一方在不透露任何额外信息的情况下向另一方证明某个陈述为真。在区块链中，ZK-rollup 将数千笔交易在链下打包，并向主链提交单个有效性证明，从而显著提高吞吐量。以太坊目前使用 Optimistic rollup 和 ZK-rollup 等 Layer 2 解决方案进行扩容，但基础层仍然直接处理交易。完全基于 ZK 的协议意味着以太坊主网本身使用零知识证明进行交易验证，可能无需单独的 L2。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ethereum.org/developers/docs/scaling/">Scaling - ethereum.org</a></li>
<li><a href="https://www.cryptowisser.com/guides/layer-2-solutions/">A Comprehensive Guide to Layer 2 Solutions: Scaling Ethereum ...</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#zero-knowledge proofs`, `#Layer 2`, `#blockchain`

---

<a id="item-27"></a>
## [纽约金融服务部提出与联邦 GENIUS 法案一致的稳定币规则](https://www.theblock.co/post/404223/new-york-regulator-proposes-stablecoin-rule-to-align-with-federal-genius-act-adds-reserve-limits?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

纽约金融服务部（NYDFS）提出了一项新的稳定币法规，与联邦 GENIUS 法案保持一致，引入了储备集中度上限和强制性风险管理计划。 该规则可能通过施加更严格的储备要求和风险控制，重塑纽约这一主要金融中心的稳定币格局，可能影响 Circle 和 Paxos 等主要发行商。 该提案保留了 100%储备支持的要求，并增加了托管人限制，公众意见征询期截至 6 月 22 日。

rss · The Block · Jun 10, 10:38

**背景**: GENIUS 法案是 2025 年 7 月通过的具有里程碑意义的联邦稳定币法律，为稳定币发行商建立了监管框架。NYDFS 此前在 2022 年建立了自己的稳定币框架，该提案旨在协调州和联邦规则。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.lw.com/en/insights/the-genius-act-of-2025-stablecoin-legislation-adopted-in-the-us">The GENIUS Act of 2025 Stablecoin Legislation Adopted in the US</a></li>
<li><a href="https://cryptobriefing.com/nydfs-draft-rules-payment-stablecoins/">NYDFS publishes draft rules for payment stablecoins, comments ...</a></li>
<li><a href="https://www.livebitcoinnews.com/nydfs-targets-circle-and-paxos-with-new-stablecoin-reserve-rules/">NYDFS Targets Circle and Paxos With New Stablecoin Reserve ...</a></li>

</ul>
</details>

**标签**: `#stablecoin`, `#regulation`, `#crypto`, `#NYDFS`

---