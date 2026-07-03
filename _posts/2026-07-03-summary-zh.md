---
layout: default
title: "Horizon Summary: 2026-07-03 (ZH)"
date: 2026-07-03
lang: zh
---

> From 82 items, 23 important content pieces were selected

---

1. [美团 LongCat-2.0 以 Owl Alpha 身份悄然登顶 OpenRouter](#item-1) ⭐️ 9.0/10
2. [crustc：将整个 Rust 编译器翻译为 C 语言](#item-2) ⭐️ 8.0/10
3. [美国禁止人口普查数据中的差分隐私](#item-3) ⭐️ 8.0/10
4. [Podman v6.0.0 发布，网络功能全面升级](#item-4) ⭐️ 8.0/10
5. [Immich 3.0 重大发布引发加密讨论](#item-5) ⭐️ 8.0/10
6. [Postgres 事务：分布式系统的超能力](#item-6) ⭐️ 8.0/10
7. [OpenAI 向美国政府提供 5%股权](#item-7) ⭐️ 8.0/10
8. [联合国小组警告 AI 可能导致灾难性危害](#item-8) ⭐️ 8.0/10
9. [弗吉尼亚州禁止出售精确地理位置数据](#item-9) ⭐️ 7.0/10
10. [CarPlay 是附加功能，而非替代品](#item-10) ⭐️ 7.0/10
11. [Linux 6.9 漏洞导致挂起时 LUKS 加密密钥留在内存中](#item-11) ⭐️ 7.0/10
12. [PeerTube：去中心化视频平台面临采用障碍](#item-12) ⭐️ 7.0/10
13. [如何有效向陌生人求助](#item-13) ⭐️ 7.0/10
14. [Securitize 在 Solana 和 Avalanche 上代币化 2.95 亿美元股票](#item-14) ⭐️ 7.0/10
15. [Ondo Finance 推出符合 SEC 规定的代币化股票](#item-15) ⭐️ 7.0/10
16. [Solana 启动链上治理，提案门槛为 10 万 SOL](#item-16) ⭐️ 7.0/10
17. [新越狱技巧绕过 AI 安全护栏](#item-17) ⭐️ 7.0/10
18. [渣打银行向机构提供直接 USDC 服务](#item-18) ⭐️ 7.0/10
19. [美国解除出口管制后，Anthropic 重新上线 Claude Fable 5](#item-19) ⭐️ 7.0/10
20. [台湾通过全面加密货币法案](#item-20) ⭐️ 7.0/10
21. [美国财政部制裁逾百个 ISIS-K 加密货币地址](#item-21) ⭐️ 6.0/10
22. [SBI Crypto 将关闭占比特币算力 2%的矿池](#item-22) ⭐️ 6.0/10
23. [Robinhood 推出公共区块链以扩展加密业务](#item-23) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [美团 LongCat-2.0 以 Owl Alpha 身份悄然登顶 OpenRouter](https://decrypt.co/372579/longcat-2-0-meituan-ai-stealth-model-openrouter) ⭐️ 9.0/10

美团披露，其 1.6 万亿参数的混合专家模型 LongCat-2.0 此前以“Owl Alpha”的化名在 OpenRouter 上秘密运行了两个月，并持续取得领先性能。该模型现在的定价远低于 GPT-5.5 和 Claude Sonnet 5。 这表明一家中国大型科技公司能够生产出与世界顶级西方模型性能相当、但价格更低的 AI 模型，从而重塑 AI 模型市场的竞争格局。 LongCat-2.0 采用混合专家架构，总参数量达 1.6 万亿，每个 token 仅激活部分参数以提高效率。它在 OpenRouter 上以“Owl Alpha”的身份运行，OpenRouter 是一个为数百个模型提供统一 API 访问的平台。

rss · Decrypt · Jul 1, 20:18

**背景**: 混合专家（MoE）模型使用多个专门的子网络（专家）和一个门控机制，只为每个输入激活相关的专家，从而在不成比例增加计算成本的情况下实现大参数量。OpenRouter 是一个市场，开发者可以通过单一 API 访问各种 AI 模型，并比较性能和定价。美团是一家中国电商和服务公司，一直在投资 AI 研究。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/openrouter/owl-alpha">Owl Alpha - API Pricing & Providers - OpenRouter</a></li>
<li><a href="https://www.reddit.com/r/SillyTavernAI/comments/1t38jfq/whatever_owl_alpha_is_can_impress/">Whatever Owl Alpha is can impress. : r/SillyTavernAI - Reddit</a></li>

</ul>
</details>

**社区讨论**: Reddit 上 r/LocalLLaMA 和 r/SillyTavernAI 的用户指出，Owl Alpha 在指令遵循和角色扮演方面表现出色，一些人对其实际上是美团的模型感到惊讶。这一发现引发了关于模型匿名性和 AI 市场竞争动态的讨论。

**标签**: `#AI`, `#large language model`, `#mixture-of-experts`, `#OpenRouter`, `#pricing`

---

<a id="item-2"></a>
## [crustc：将整个 Rust 编译器翻译为 C 语言](https://github.com/FractalFir/crustc) ⭐️ 8.0/10

经过三年的努力，crustc 项目成功将整个 rustc 编译器从 Rust 翻译为 C 语言，从而可以在没有 LLVM 或 GCC 支持的平台上进行引导。 这一成就使得 Rust 能够在缺乏 LLVM/GCC 后端的旧式或小众硬件上进行引导，有望将 Rust 的应用范围扩展到嵌入式系统和遗留系统。 该项目是已知的第 14 次将 Rust 编译为 C 的尝试，其目标是生成一个功能完整的基于 C 的 Rust 编译器，该编译器可由任何 C 编译器（包括 GCC 和 Clang）编译。

hackernews · Philpax · Jul 2, 22:57 · [社区讨论](https://news.ycombinator.com/item?id=48768464)

**背景**: 引导编译器意味着使用编译器自身的源代码来构建新版本。对于 Rust 来说，传统上需要现有的 Rust 编译器或 LLVM 后端。将 rustc 翻译为 C 消除了这一依赖，使得 Rust 可以在任何拥有 C 编译器的平台上从零开始构建。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/FractalFir/crustc">GitHub - FractalFir/crustc: Entirety of `rustc`, translated to C. · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bootstrapping_(compilers)">Bootstrapping (compilers)</a></li>

</ul>
</details>

**社区讨论**: 社区称赞了该项目的奉献精神和技术新颖性，评论指出其在引导和通过多样化双重编译（DDC）进行安全验证方面的潜力。一些人讨论了 LLVM C 后端作为替代方案，但承认 crustc 的独特方法。

**标签**: `#rust`, `#compiler`, `#bootstrapping`, `#transpilation`, `#systems programming`

---

<a id="item-3"></a>
## [美国禁止人口普查数据中的差分隐私](https://scottaaronson.blog/?p=9902) ⭐️ 8.0/10

2026 年 6 月 4 日，美国商务部长发布了 DAO 216-26 号指令，禁止人口普查局发布的所有统计产品中使用差分隐私和噪声注入。 该指令威胁到用于选区重划、资源分配和民权执法等关键决策的公共数据的准确性和实用性，可能削弱对联邦统计数据的信任。 该指令将披露避免限制为仅使用“粗化”（例如数据抑制或聚合），并明确禁止“噪声注入”，而噪声注入正是差分隐私的核心技术。

hackernews · flowercalled · Jul 3, 00:01 · [社区讨论](https://news.ycombinator.com/item?id=48768992)

**背景**: 差分隐私是一种数学框架，通过向数据中添加精心校准的噪声来保护个人隐私，同时保持统计准确性。人口普查局在 2020 年人口普查中采用了差分隐私，以现代化其披露避免方法，但批评者认为它降低了小地理区域的数据质量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.census.gov/programs-surveys/decennial-census/decade/2020/planning-management/process/disclosure-avoidance/differential-privacy.html">Understanding Differential Privacy</a></li>
<li><a href="https://www.ncsl.org/technology-and-communication/differential-privacy-census-data-and-redistricting">Differential Privacy for Census Data Explained</a></li>
<li><a href="https://www.bea.gov/help/faq/1490">Why didn’t BEA use noise infusion as its statistical disclosure limitation method in its June 10, 2026, news release on “New Foreign Direct Investment in the United States, 2025’’? | U.S. Bureau of Economic Analysis (BEA)</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了担忧，有人称该指令对统计数据产品是一场灾难。其他人质疑禁令背后的政治动机，而 Scott Aaronson 敦促读者联系立法者反对该指令。

**标签**: `#privacy`, `#differential privacy`, `#census`, `#data policy`, `#government regulation`

---

<a id="item-4"></a>
## [Podman v6.0.0 发布，网络功能全面升级](https://blog.podman.io/2026/07/introducing-podman-v6-0-0/) ⭐️ 8.0/10

Podman v6.0.0 带来了重大网络改进，包括在 Kernel 6.18+ 上实验性移除 rootless 暂停进程、确定性多网络排序以及默认启用网络隔离。Quadlet 的增强进一步简化了将容器作为 systemd 服务运行的过程。 此版本巩固了 Podman 作为领先的 Docker 替代品的地位，提升了安全性、性能和易用性。网络变更和 Quadlet 改进降低了企业采用和从 Docker 迁移的门槛。 导入路径已更改为 go.podman.io/podman/v6，作为迁移到 CNCF 的一部分。已完全移除 slirp4netns 等弃用组件，由 Pasta 替代。网络隔离现在默认启用，提高了与 Docker 的兼容性。

hackernews · soheilpro · Jul 2, 14:23 · [社区讨论](https://news.ycombinator.com/item?id=48762098)

**背景**: Podman 是一个无守护进程的容器引擎，提供与 Docker 兼容的 CLI。Quadlet 允许用户以简单的 unit 文件定义容器，由 systemd 管理。此版本是 CNCF 治理下的第一个主要版本。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/podman-container-tools/podman/releases/tag/v6.0.0">Release v6.0.0 · podman-container-tools/podman</a></li>
<li><a href="https://fedoraproject.org/wiki/Changes/Podman6">Changes/Podman6 - Fedora Project Wiki</a></li>
<li><a href="https://www.redhat.com/en/blog/quadlet-podman">Make systemd better for Podman with Quadlet</a></li>

</ul>
</details>

**社区讨论**: 社区情绪总体积极，用户称赞 Podman 优于 Docker 且迁移简便。部分 macOS 用户报告 Podman Machine 存在稳定性问题，而其他用户则分享了无需修改 docker-compose 文件即可成功迁移的经验。

**标签**: `#Podman`, `#containers`, `#Docker`, `#devops`, `#open source`

---

<a id="item-5"></a>
## [Immich 3.0 重大发布引发加密讨论](https://github.com/immich-app/immich/discussions/29439) ⭐️ 8.0/10

自托管照片管理平台 Immich 发布了 3.0 重大更新，引发了社区关于端到端加密和可用性等功能的广泛讨论。 此次发布凸显了用户对注重隐私的云服务（如 Google Photos）替代品的日益增长的需求，而关于加密与便利性的辩论将塑造自托管媒体管理的未来。 Immich 3.0 不包含端到端加密（E2EE），一些用户认为这是缺失的关键功能，而另一些人则认为服务器端加密已足够，E2EE 会使可用性复杂化。

hackernews · hashier · Jul 2, 14:13 · [社区讨论](https://news.ycombinator.com/item?id=48761944)

**背景**: Immich 是一个开源、自托管的照片和视频管理解决方案，允许用户在自己的服务器上备份、整理和访问媒体，保护隐私。自 2022 年启动以来，它发展迅速，到 2026 年初已获得超过 90,000 个 GitHub 星标。该平台与 Google Photos 和 Apple Photos 等服务竞争，提供自托管替代方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://immich.app/">Immich</a></li>
<li><a href="https://github.com/immich-app/immich">GitHub - immich-app/immich: High performance self-hosted photo and video management solution. · GitHub</a></li>
<li><a href="https://docs.immich.app/guides/remote-access/">Remote Access | Immich</a></li>

</ul>
</details>

**社区讨论**: 社区评论显示意见分歧：一些用户称赞 Immich 是云服务的无脑替代品，而另一些用户则因 E2EE 而选择了 Ente Photos 等替代方案。争论的焦点在于静态加密是否足够，或者 E2EE 是否对安全至关重要。

**标签**: `#self-hosting`, `#photo management`, `#open source`, `#privacy`, `#immich`

---

<a id="item-6"></a>
## [Postgres 事务：分布式系统的超能力](https://www.dbos.dev/blog/co-locating-workflow-state-with-your-data) ⭐️ 8.0/10

文章和讨论强调，通过使用 PostgreSQL 事务将工作流状态与数据共置，可以简化分布式工作流，减少对独立消息队列和发件箱模式的需求。 这种方法可能从根本上改变分布式系统架构，使 PostgreSQL 成为大规模高可用系统的更通用选择，简化开发并降低基础设施复杂性。 该技术将每个工作流步骤与数据库提交单元对齐，简化了发件箱模式，但使数据库与工作流紧密耦合。PostgreSQL 支持两阶段提交（2PC）以实现跨多个数据库的分布式事务。

hackernews · KraftyOne · Jul 2, 18:38 · [社区讨论](https://news.ycombinator.com/item?id=48765639)

**背景**: 在分布式系统中，发件箱模式通过将消息存储在数据库表中并与业务数据原子提交来确保可靠的消息传递。PostgreSQL 事务提供 ACID 保证，支持跨多个表的原子更新。两阶段提交协议允许协调不同数据库或系统之间的事务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://microservices.io/patterns/data/transactional-outbox.html">Microservices Pattern: Pattern: Transactional outbox</a></li>
<li><a href="https://nightlysolutions.com/trackers-data/postgres-transactions-are-a-distributed-systems-superpower/">Postgres Transactions Are A Distributed Systems ... - NightlySolutions</a></li>
<li><a href="https://postgrespro.com/docs/postgresql/current/two-phase">PostgreSQL : Documentation: 18: 67.4. Two-Phase Transactions</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了权衡：一些人赞扬原子性的好处，而另一些人质疑使用中央数据库是否真正构成分布式系统。一位评论者指出数据库与工作流的紧密耦合是潜在的架构问题，但承认在实践中很少成为问题。

**标签**: `#PostgreSQL`, `#distributed systems`, `#transactions`, `#workflow`, `#outbox pattern`

---

<a id="item-7"></a>
## [OpenAI 向美国政府提供 5%股权](https://decrypt.co/372715/openai-offers-us-government-42-billion-slice) ⭐️ 8.0/10

据报道，OpenAI CEO Sam Altman 提议向美国政府提供公司 5%的股权，并希望其他主要 AI 公司也采取类似做法。 该提议可能为政府参与 AI 公司树立先例，从而重塑 AI 治理和国家安全格局。 据称，基于 OpenAI 近期 840 亿美元的估值，该股权价值 420 亿美元，此举是推动全行业向政府提供股权的更广泛努力的一部分。

rss · Decrypt · Jul 2, 21:39

**背景**: 股权代表对公司的所有权，通常赋予持有人投票权和利润分配权。OpenAI 最初以非营利组织成立，但现在在非营利董事会下运营营利性部门，并正在转型为公益公司（PBC）。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://dictionary.cambridge.org/dictionary/english/equity-stake">EQUITY STAKE | English meaning - Cambridge Dictionary</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenAI">OpenAI - Wikipedia</a></li>
<li><a href="https://openai.com/our-structure/">Our structure | OpenAI</a></li>

</ul>
</details>

**标签**: `#AI`, `#OpenAI`, `#government`, `#policy`, `#investment`

---

<a id="item-8"></a>
## [联合国小组警告 AI 可能导致灾难性危害](https://decrypt.co/372543/un-ai-safety-panel-scientists-catastrophic-harm) ⭐️ 8.0/10

联合国任命的一个由 40 名科学家组成的小组得出结论，AI 能力的发展速度超过了科学理解和监管监督，他们不能排除灾难性危害的可能性。 这一来自全球机构的权威警告凸显了协调 AI 安全研究和治理的紧迫性，可能影响国际政策和资金优先事项。 该小组的报告强调，当前的 AI 系统带来了尚未完全理解的风险，现有的监督机制不足以防止潜在的大规模危害。

rss · Decrypt · Jul 1, 19:05

**背景**: 随着 GPT-4 和 Gemini 等先进模型展现出越来越强大的能力，AI 安全问题日益受到关注。联合国的介入标志着向全球治理讨论的转变，类似于过去在核武器或气候变化方面的努力。

**标签**: `#AI safety`, `#UN`, `#policy`, `#risk assessment`, `#governance`

---

<a id="item-9"></a>
## [弗吉尼亚州禁止出售精确地理位置数据](https://www.hunton.com/privacy-and-cybersecurity-law-blog/virginia-bans-sale-of-geolocation-data) ⭐️ 7.0/10

弗吉尼亚州通过了一项法律，禁止出售精确地理位置数据，该法律于 7 月 1 日生效，但模糊数据（无法在 1750 英尺内定位）除外。 该法律通过限制数据经纪人出售精确位置数据，为弗吉尼亚州居民提供了重要的隐私保护，并为其他州树立了先例。 该法律将精确地理位置数据定义为能在 1750 英尺内定位的数据，与联邦定义（通常使用 1000 米）一致。执法挑战包括州外公司以及通过位于弗吉尼亚州的云服务器收集数据的情况。

hackernews · toomuchtodo · Jul 2, 21:03 · [社区讨论](https://news.ycombinator.com/item?id=48767347)

**背景**: 精确地理位置数据是指能够高精度识别个人物理位置的信息，常用于定向广告和追踪。数据经纪人从应用和设备中收集此类数据，引发隐私担忧。弗吉尼亚州的法律是美国各州层面隐私立法大趋势的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.law.cornell.edu/cfr/text/28/202.242">28 CFR § 202.242 - Precise geolocation data. | Electronic Code of Federal Regulations (e-CFR) | US Law | LII / Legal Information Institute</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，该法律仅禁止出售精确数据，而非模糊数据，并对州外公司的执法提出质疑。一些人表达了谨慎乐观，希望该法律能像加州的类似立法一样具有实际效力。

**标签**: `#privacy`, `#geolocation`, `#legislation`, `#data protection`

---

<a id="item-10"></a>
## [CarPlay 是附加功能，而非替代品](https://www.caseyliss.com/2026/7/2/carplay-is-additive-you-dolts) ⭐️ 7.0/10

一篇新文章认为，CarPlay 是一种提供一致性的附加界面，尽管其导航和多点触控功能存在局限，但许多消费者仍视其为必备功能。 这场讨论突显了一个重要的消费者偏好趋势：79% 的美国购车者只会购买支持 CarPlay 的汽车，使其成为购车决策的关键因素。 CarPlay 在不同品牌和车型上提供一致的界面，并允许多个用户拥有个性化仪表盘。然而，一些用户认为其导航功能不如特斯拉等内置系统，且多点触控支持直到 iOS 26 才加入。

hackernews · sprawl_ · Jul 3, 01:02 · [社区讨论](https://news.ycombinator.com/item?id=48769397)

**背景**: CarPlay 是苹果的车载信息娱乐系统，将 iPhone 的界面镜像到汽车显示屏上，提供地图、音乐、信息等针对驾驶优化的应用。许多汽车制造商将 CarPlay 作为标准或可选功能，但特斯拉等公司使用自己的专有系统。

**社区讨论**: 评论者意见不一：一些人强烈认同 CarPlay 因其一致性而必不可少，而另一些人则认为特斯拉等内置系统在导航和易用性上更胜一筹。少数用户更看重稳定的蓝牙连接和手机支架，而非 CarPlay。

**标签**: `#CarPlay`, `#automotive UX`, `#consumer tech`, `#Apple ecosystem`

---

<a id="item-11"></a>
## [Linux 6.9 漏洞导致挂起时 LUKS 加密密钥留在内存中](https://mathstodon.xyz/@iblech/116769502749142438) ⭐️ 7.0/10

Linux 内核 6.9 版本中的一个回归问题导致 LUKS 挂起功能不再从内存中清除磁盘加密密钥，使得密钥在挂起到 RAM 期间暴露。 此漏洞削弱了 Linux 系统上全盘加密的安全性，因为拥有物理访问权限的攻击者可能在挂起期间从内存中提取主密钥，从而危及所有加密数据。 该问题影响 LUKS（Linux 统一密钥设置）挂起操作，该操作通常通过 Debian 系发行版中的 `cryptsetup luksSuspend` 等脚本使用。引入此回归的内核更改已被识别，并且存在自定义挂起脚本等变通方案。

hackernews · IngoBlechschmid · Jul 2, 15:25 · [社区讨论](https://news.ycombinator.com/item?id=48763035)

**背景**: LUKS 是 Linux 的磁盘加密规范，它使用存储在内存中的主密钥来加密/解密数据。在挂起到 RAM 期间，系统保持内存供电，因此主密钥仍留在 RAM 中。以前，LUKS 挂起过程会在挂起前清除此密钥，恢复时需要重新输入密码短语。Linux 6.9 内核的更改无意中禁用了此清除行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sesamedisk.com/linux-luks-suspend-regression-security/">Linux LUKS Suspend Regression: Keys Stay - Sesame Disk</a></li>
<li><a href="https://eucloudservers.com/security-encryption/since-linux-6-9-luks-suspend-stopped-wiping-disk-encryption-keys-from-memory/">Since Linux 6.9, LUKS Suspend Stopped Wiping ... - EU Cloud Servers</a></li>
<li><a href="https://dev.to/soytuber/linux-luks-vulnerability-android-developer-verification-threat-github-secret-scanning-guide-2hm6">Linux LUKS Vulnerability, Android Developer... - DEV Community</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：有人认为该漏洞被夸大，因为 LUKS 挂起并非官方支持，仅影响特定发行版；而另一些人则对其安全影响表示担忧。少数用户质疑此更改是否故意，但大多数人认为回归确实存在，应予以修复。

**标签**: `#Linux`, `#security`, `#kernel`, `#LUKS`, `#encryption`

---

<a id="item-12"></a>
## [PeerTube：去中心化视频平台面临采用障碍](https://github.com/Chocobozzz/PeerTube) ⭐️ 7.0/10

PeerTube 是一个免费、开源、去中心化的视频平台，利用 ActivityPub 联邦协议和点对点技术来分发视频播放负载。尽管技术上有优势，但由于缺乏盈利模式和内容多样性有限，该平台在采用上遇到困难。 PeerTube 代表了像 YouTube 这样的中心化平台的重要替代方案，提供了抗审查和数据隐私。然而，其可行性取决于解决盈利和内容发现挑战，这对吸引创作者和观众至关重要。 PeerTube 仅处理托管和播放，不涉及发现或盈利，并利用点对点广播来减少服务器负载。它基于 ActivityPub 构建，允许与其他实例联邦，但缺乏内置的广告或订阅模式。

hackernews · doener · Jul 2, 11:17 · [社区讨论](https://news.ycombinator.com/item?id=48759634)

**背景**: PeerTube 是一个免费开源的视频平台，利用 ActivityPub 联邦协议连接独立实例，实现去中心化视频共享。与 YouTube 不同，没有单一实体控制网络，降低了审查风险。然而，其点对点分发仅有助于播放负载，而非存储或发现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/PeerTube">PeerTube - Wikipedia</a></li>
<li><a href="https://joinpeertube.org/faq">FAQ | JoinPeerTube</a></li>
<li><a href="https://dailycoin.com/decentralized-video-streaming-platforms-best-alternatives-to-youtube/">Decentralized YouTube Alternatives: Video Streaming... - DailyCoin</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，PeerTube 缺乏盈利模式，这对需要覆盖高制作成本的专业创作者来说是一个主要障碍。一些用户欣赏它用于开源内容，但指出游戏和音乐等主流话题内容不足。其他人指出 PeerTube 仅处理托管和播放，不涉及发现或盈利。

**标签**: `#decentralization`, `#video hosting`, `#open source`, `#federation`, `#PeerTube`

---

<a id="item-13"></a>
## [如何有效向陌生人求助](https://pradyuprasad.com/writings/how-to-ask-for-help/) ⭐️ 7.0/10

一篇关于向陌生人求助的实用指南，强调展示前期努力（proof of work）并保持沟通简洁、尊重。 这些建议能帮助专业人士更高效地建立人脉和解决问题，尤其对处于职业早期或进行冷接触的人尤为重要。 关键点包括在求助前展示真实努力、个性化请求，以及尊重对方的时间。

hackernews · FigurativeVoid · Jul 2, 13:19 · [社区讨论](https://news.ycombinator.com/item?id=48761118)

**背景**: 在求职、寻求指导或合作等职业场景中，向陌生人求助很常见。由于没有既有关系，求助信息必须具有说服力且体贴，才能获得积极回应。

**社区讨论**: 评论者分享了个人经验，指出前期努力必须深入而非表面，主动提出付费可以体现诚意。还有人强调，展示自己已尽力尝试解决问题至关重要。

**标签**: `#career advice`, `#communication`, `#professional development`, `#networking`

---

<a id="item-14"></a>
## [Securitize 在 Solana 和 Avalanche 上代币化 2.95 亿美元股票](https://www.coindesk.com/business/2026/07/02/securitize-tokenizes-usd295-million-of-its-own-stock-on-solana-and-avalanche-amid-nyse-debut) ⭐️ 7.0/10

贝莱德支持的代币化公司 Securitize 在 Solana 和 Avalanche 区块链上将其 2.95 亿美元的股票代币化，同时该公司在纽约证券交易所上市。 这标志着现实世界资产代币化的一个重要里程碑，展示了传统金融与区块链如何融合，并可能为更多 IPO 在公共区块链上代币化铺平道路。 Securitize 总裁 Brett Redfearn 表示，该公司正在讨论在未来一年内将其他 IPO 代币化。代币化股票可在 Solana 和 Avalanche 网络上交易。

rss · CoinDesk · Jul 2, 19:00

**背景**: 代币化是指创建基于区块链的代币，代表对现实世界资产（如股票）的所有权。Securitize 是现实世界资产代币化的领先平台，专注于合规性并连接传统金融与区块链。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://securitize.io/">Securitize | The Leading Tokenization Platform</a></li>
<li><a href="https://www.okx.com/en-gb/learn/securitize-tokenization-investment-rwa">Securitize Tokenization Investment: Unlocking the Future of... | OKX</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#blockchain`, `#Solana`, `#Avalanche`, `#finance`

---

<a id="item-15"></a>
## [Ondo Finance 推出符合 SEC 规定的代币化股票](https://www.coindesk.com/business/2026/07/01/ondo-finance-debuts-sec-aligned-tokenized-stock-model-with-blackrock-etf-micron-shares) ⭐️ 7.0/10

Ondo Finance 已根据 SEC 的第三方托管代币化模型，将 BlackRock 的 IVV ETF 和 Micron 股票代币化，并在以太坊上结算。 这标志着 SEC 托管模型的首次生产部署，以监管清晰度连接传统金融和 DeFi，可能为代币化证券的更广泛机构采用铺平道路。 代币化证券根据美国法律作为证券权益发行，而非离岸结构，Ondo 的 Global Markets 平台已在 430 多只股票和 ETF 中代币化超过 10 亿美元。

rss · CoinDesk · Jul 2, 14:16

**背景**: 2026 年 1 月，SEC 工作人员发布了关于代币化证券的指南，概述了一种托管模型，即第三方持有基础证券并发行代表权益的代币。Ondo Finance 是首个在生产中实施该模型的公司，使用以太坊进行结算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/01/ondo-finance-debuts-sec-aligned-tokenized-stock-model-with-blackrock-etf-micron-shares">Ondo debuts SEC-aligned tokenized stock model with BlackRock...</a></li>
<li><a href="https://www.sec.gov/newsroom/speeches-statements/corp-fin-statement-tokenized-securities-012826-statement-tokenized-securities">Statement on Tokenized Securities - SEC.gov</a></li>
<li><a href="https://news.bitcoin.com/ondo-brings-blackrock-ivv-etf-and-micron-shares-onchain-in-us-regulatory-first/">Ondo Brings Blackrock IVV ETF and Micron Shares Onchain in US...</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#DeFi`, `#SEC`, `#BlackRock`, `#securities`

---

<a id="item-16"></a>
## [Solana 启动链上治理，提案门槛为 10 万 SOL](https://www.coindesk.com/markets/2026/07/02/solana-adds-onchain-governance-with-usd7-7-million-sol-needed-to-open-proposals) ⭐️ 7.0/10

Solana 已正式启动名为 Solana Governance Proposals (SGPs) 的链上治理系统，要求验证者至少质押 10 万 SOL 才能提交提案。 这标志着 Solana 向去中心化协议管理迈出了重要一步，赋予验证者和质押者直接对网络升级和变更的投票权，有望增强社区参与度和协议韧性。 提案需要获得活跃质押量 15% 的初始支持，并需获得投票质押量三分之二绝对多数通过，结果记录在链上。10 万 SOL（约 770 万美元）的高门槛旨在确保提案者具有重大利益关联。

rss · CoinDesk · Jul 2, 07:15

**背景**: 链上治理允许代币持有者直接对协议变更进行投票，取代链下决策。Solana 作为高性能区块链，此前缺乏正式的链上投票机制，依赖验证者协调和基金会指导。该系统使 Solana 与以太坊、Cosmos 等其他已拥有链上治理的主流网络保持一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/markets/2026/07/02/solana-adds-onchain-governance-with-usd7-7-million-sol-needed-to-open-proposals">Solana launches onchain governance and sets entry fee at 100,000...</a></li>
<li><a href="https://tokenmetrics.com/sol/news/solana-launches-onchain-governance-with-100k-sol-entry/">Solana Launches Onchain Governance — SOL... - Token Metrics Blog</a></li>
<li><a href="https://cryptobriefing.com/solana-on-chain-governance-proposals/">Solana Foundation launches on-chain governance proposals for...</a></li>

</ul>
</details>

**标签**: `#Solana`, `#blockchain`, `#governance`, `#DeFi`, `#cryptocurrency`

---

<a id="item-17"></a>
## [新越狱技巧绕过 AI 安全护栏](https://decrypt.co/372688/ai-researchers-chatbots-share-cocaine-recipes-wild-trick) ⭐️ 7.0/10

研究人员发现了一种越狱方法，通过欺骗 AI 模型将攻击者编写的文本视为自身的推理，从而绕过安全措施，暴露出更深层次的安全漏洞。 该技术揭示了 LLM 在处理推理时的根本性漏洞，可能使恶意行为者生成有害内容（如毒品配方）。这凸显了在 AI 系统中需要更强大的安全机制。 该越狱利用了模型信任自身推理过程的倾向，使得传统安全过滤器难以检测。该攻击适用于多个 LLM，表明存在系统性弱点。

rss · Decrypt · Jul 2, 19:36

**背景**: 像 ChatGPT 这样的大型语言模型（LLM）经过训练会拒绝有害请求，但越狱技术通过精心设计提示来绕过这些护栏。对抗性攻击操纵输入以欺骗 AI 系统产生非预期的输出。这种新方法尤其令人担忧，因为它利用了模型的内部推理，而不仅仅是提示措辞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cyberark.com/resources/threat-research-blog/jailbreaking-every-llm-with-one-simple-click">Jailbreaking Every LLM With One Simple Click - CyberArk</a></li>
<li><a href="https://www.confident-ai.com/blog/how-to-jailbreak-llms-one-step-at-a-time">How to Jailbreak LLMs One Step at a Time: Top Techniques and Strategies - Confident AI</a></li>
<li><a href="https://arxiv.org/html/2509.14297v1">A Simple and Efficient Jailbreak Method Exploiting LLMs' Helpfulness - arXiv</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#jailbreak`, `#security`, `#LLM`, `#adversarial attack`

---

<a id="item-18"></a>
## [渣打银行向机构提供直接 USDC 服务](https://decrypt.co/372674/standard-chartered-first-global-bank-direct-usdc-access) ⭐️ 7.0/10

渣打银行成为首家获授权允许机构直接铸造和赎回 Circle 的 USDC 稳定币的全球系统重要性银行（G-SIB）。 这标志着机构加密货币采用的重要里程碑，连接了传统银行与数字资产，可能增加 USDC 在大型金融机构中的流动性和信任度。 该服务使机构客户能够直接通过渣打银行铸造和赎回 USDC，无需单独开设 Circle 账户。USDC 始终可通过 Circle 按 1:1 兑换美元。

rss · Decrypt · Jul 2, 13:58

**背景**: USDC 是一种与美元 1:1 挂钩的稳定币，由 Circle 发行。只有授权机构才能直接铸造或赎回 USDC；个人必须通过交易所获取。全球系统重要性银行（G-SIB）是被监管机构视为“大到不能倒”的银行，需遵守更严格的资本要求。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.circle.com/circle-mint">Circle Mint | Mint USDC , Unlock Business Efficiency | Circle</a></li>
<li><a href="https://en.wikipedia.org/wiki/Global_Systemically_Important_Bank">Global Systemically Important Bank</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#banking`, `#stablecoin`, `#institutional adoption`

---

<a id="item-19"></a>
## [美国解除出口管制后，Anthropic 重新上线 Claude Fable 5](https://decrypt.co/372524/anthropic-bringing-claude-fable-5-back-online-us-lifts-export-controls) ⭐️ 7.0/10

Anthropic 在特朗普政府撤销关闭令并解除出口管制后，重新上线了其 Claude Fable 5 模型，并引入了包括安全分类器在内的新安全措施。 这一政策逆转标志着美国 AI 出口管制策略的转变，可能使先进 AI 模型获得更广泛的使用，同时也引发了关于安全性和滥用预防的讨论。 Claude Fable 5 是一款 Mythos 级模型，其能力超过 Anthropic 此前任何公开发布的模型，其回归与一种旨在防御越狱攻击的新型安全分类器相关联。

rss · Decrypt · Jul 1, 16:24

**背景**: Claude Fable 5 是 Anthropic 开发的大型语言模型，用于发现软件漏洞。此前因安全和滥用问题被关闭。美国的出口管制曾限制其可用性，但经过数周谈判，政府撤销了该命令。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable_5">Claude Fable 5</a></li>
<li><a href="https://www.anthropic.com/news/constitutional-classifiers">Constitutional Classifiers : Defending against universal jailbreaks</a></li>

</ul>
</details>

**标签**: `#AI`, `#Anthropic`, `#export controls`, `#AI safety`, `#policy`

---

<a id="item-20"></a>
## [台湾通过全面加密货币法案](https://decrypt.co/372505/taiwan-passes-sweeping-crypto-law-with-licensing-stablecoin-rules) ⭐️ 7.0/10

台湾通过了一项全面的加密货币法律，首次将虚拟资产公司纳入金融监督管理委员会（FSC）的监管，并为稳定币制定了储备和信托规则。 该法律标志着台湾数字资产监管框架迈出重要一步，可能增强投资者保护和市场稳定性，同时与全球加强加密货币监管的趋势保持一致。 该法律要求稳定币发行方持有高质量流动性资产作为储备，并遵守信托安排，类似于欧盟 MiCA 等框架。虚拟资产服务提供商必须获得 FSC 的许可。

rss · Decrypt · Jul 1, 12:00

**背景**: 金融监督管理委员会（FSC）是台湾负责监管证券、银行和保险的独立政府机构。在此之前，台湾的加密货币行业监管有限。稳定币是一种通过与储备资产挂钩来维持稳定价值的加密货币，储备规则确保其有充分支持以防止挤兑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Financial_Supervisory_Commission_(Taiwan)">Financial Supervisory Commission ( Taiwan ) - Wikipedia</a></li>
<li><a href="https://www.fsc.gov.tw/en/">Financial Supervisory Commission</a></li>
<li><a href="https://blog.tothemoon.com/articles/stablecoin-reserves-what-businesses-need-to-know">Stablecoin Reserves : What Businesses Need to Know</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#stablecoins`, `#Taiwan`, `#finance`

---

<a id="item-21"></a>
## [美国财政部制裁逾百个 ISIS-K 加密货币地址](https://www.coindesk.com/policy/2026/07/02/us-treasury-sanctions-over-100-isis-k-crypto-addresses-in-latest-enforcement-action) ⭐️ 6.0/10

美国财政部外国资产控制办公室（OFAC）制裁了与 ISIS-K 相关的 130 多个 Tron 钱包地址和 3 个 Monero 地址，这些地址共转移了超过 140 万美元。随后 Tether 冻结了被制裁 Tron 地址上的 USDT 资金。 此举表明美国政府日益关注通过加密货币切断恐怖主义融资，尤其是在被批评助长非法活动的 Tron 网络上。同时凸显了 Tether 等稳定币发行方在执行制裁中的作用。 被制裁地址包括 131 个 Tron 地址和 3 个 Monero 地址，Tether 已冻结 Tron 地址上的 USDT。据财政部称，通过这些地址转移的总价值超过 140 万美元。

rss · CoinDesk · Jul 2, 14:49

**背景**: ISIS-K（伊斯兰国呼罗珊省）是 ISIS 在中亚和南亚的地区分支，制造了多起恐怖袭击。Tron 是一种权益证明区块链，被批评为加密货币洗钱的首选渠道；而 Tether（USDT）是一种与美元挂钩的稳定币，常被用于非法金融活动。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chainalysis.com/blog/isis-designation-crypto-addresses-july-2026/">OFAC Sanctions 100+ ISIS - K Crypto Addresses</a></li>
<li><a href="https://en.wikipedia.org/wiki/ISIS-K">ISIS-K</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tron_(blockchain)">Tron (blockchain)</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#sanctions`, `#security`, `#regulation`

---

<a id="item-22"></a>
## [SBI Crypto 将关闭占比特币算力 2%的矿池](https://www.coindesk.com/business/2026/07/02/sbi-crypto-to-shut-down-mining-pool-that-holds-roughly-2-of-bitcoin-s-hashrate) ⭐️ 6.0/10

据 CoinDesk 2026 年 7 月 2 日报道，SBI Crypto 宣布将关闭其比特币矿池，该矿池约占比特币总算力的 2%。 此次关闭降低了挖矿算力的集中度，可能暂时影响网络稳定性，但也凸显了比特币挖矿行业持续的整合和运营挑战。 该矿池的算力约占比特币网络总算力的 2%，关闭的具体时间表尚未公布。

rss · CoinDesk · Jul 2, 14:44

**背景**: 比特币矿池汇集个体矿工的计算能力，以增加获得区块奖励的机会。算力衡量网络的总计算能力，拥有 2%算力的矿池是重要但非主导的参与者。SBI Crypto 是日本大型金融服务集团 SBI Holdings 的子公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hashrate">Hashrate</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#cryptocurrency`, `#mining`, `#SBI Crypto`

---

<a id="item-23"></a>
## [Robinhood 推出公共区块链以扩展加密业务](https://www.coindesk.com/business/2026/07/01/robinhood-rolls-out-public-blockchain-as-it-expands-deeper-into-crypto) ⭐️ 6.0/10

Robinhood 于 2026 年 7 月 1 日启动了其基于 Arbitrum 的以太坊二层网络 Robinhood Chain 的公共主网。 这标志着一家大型金融科技公司构建自己的区块链基础设施，可能降低费用并为数百万用户提供代币化现实世界资产等新金融服务。 Robinhood Chain 是一个基于 Arbitrum 构建的无许可二层区块链，专为金融服务和代币化现实世界资产设计。

rss · CoinDesk · Jul 1, 18:25

**背景**: Arbitrum 是以太坊的二层扩容解决方案，通过将交易在链下打包来处理交易，速度更快、费用更低。像 Arbitrum 这样的二层网络有助于减少以太坊主网的拥堵和高额费用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gate.com/learn/articles/what-is-arbitrum/3628">What Is Arbitrum ? Ethereum Layer 2 Scaling Solution... | Gate Learn</a></li>
<li><a href="https://robinhood.com/us/en/chain/">Robinhood Chain | Built for onchain finance</a></li>
<li><a href="https://bsc.news/news/robinhood-chain-mainnet-tokenized-stocks-defi">Robinhood just turned on its own blockchain | BSCN Breaking News</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#cryptocurrency`, `#fintech`, `#Robinhood`

---