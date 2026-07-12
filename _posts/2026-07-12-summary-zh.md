---
layout: default
title: "Horizon Summary: 2026-07-12 (ZH)"
date: 2026-07-12
lang: zh
---

> From 57 items, 17 important content pieces were selected

---

1. [英伟达在 GPU 热潮中的循环融资](#item-1) ⭐️ 8.0/10
2. [Grok Build CLI 将整个仓库上传至 xAI](#item-2) ⭐️ 8.0/10
3. [UPI 架构深度解析：设计、可扩展性与影响](#item-3) ⭐️ 8.0/10
4. [Bonzo 因预言机漏洞损失 900 万美元，TVL 暴跌 77%](#item-4) ⭐️ 8.0/10
5. [AI 发现以太坊漏洞，可能导致验证者离线](#item-5) ⭐️ 8.0/10
6. [Mesh LLM：基于 Iroh 的分布式 AI 计算](#item-6) ⭐️ 7.0/10
7. [ClickHouse 通过 Peering 机制将 PgBouncer 吞吐量提升 4 倍](#item-7) ⭐️ 7.0/10
8. [美国住房法禁止美联储发行 CBDC 至 2030 年](#item-8) ⭐️ 7.0/10
9. [苹果起诉 OpenAI 窃取商业机密](#item-9) ⭐️ 7.0/10
10. [剑桥研究：31%以太坊节点位于美国，三分之一离线可致最终性停滞](#item-10) ⭐️ 7.0/10
11. [激光攻击可重置 Tangem 钱包密码](#item-11) ⭐️ 7.0/10
12. [Ant：一个全新的 JavaScript 运行时与一体化生态系统](#item-12) ⭐️ 6.0/10
13. [加密巨头支持 AI 代理争议解决法庭](#item-13) ⭐️ 6.0/10
14. [Robinhood Chain：面向代币化股票的以太坊二层网络](#item-14) ⭐️ 6.0/10
15. [Xbox CEO 在裁员潮中加入美联储 AI 工作组](#item-15) ⭐️ 6.0/10
16. [Circle 获得 OCC 最终批准成立国家信托银行](#item-16) ⭐️ 6.0/10
17. [Revolut X 集成 AI 助手进行加密货币交易](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [英伟达在 GPU 热潮中的循环融资](https://io-fund.com/ai-stocks/nvidia-coreweave-nebius-circular-financing-gpu-boom) ⭐️ 8.0/10

一项分析揭示，英伟达对云提供商 CoreWeave 和 Nebius 的投资可能构成循环融资，即英伟达资助客户，客户再购买其 GPU，但这种做法也是对超大规模云厂商的战略对冲。 这很重要，因为循环融资可能人为推高对英伟达 GPU 的需求，如果 AI 基础设施建设被证明无利可图，将带来系统性风险。同时，这也凸显了英伟达减少对 AWS、Azure 等超大规模云厂商依赖的战略。 英伟达向 CoreWeave 投资 20 亿美元获得 9%股权，而 CoreWeave 计划 2026 年资本支出 350 亿美元，英伟达的投资仅占其当年支出的 5.7%。另一家英伟达支持的云公司 Nebius 最近与微软签订了 174 亿美元的合同。

hackernews · adletbalzhanov · Jul 11, 17:21 · [社区讨论](https://news.ycombinator.com/item?id=48873836)

**背景**: 循环融资是一种投资者向公司提供资金，然后该公司将资金用于购买投资者自身产品的循环。在 AI 热潮中，英伟达、CoreWeave 和 Nebius 就是典型例子：英伟达投资云提供商，云提供商再用这些资金购买英伟达 GPU。这种动态引发了关于真实需求与人为刺激的疑问。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://builtin.com/articles/ai-circular-financing">How Circular Financing Is Fueling the AI Boom | Built In</a></li>
<li><a href="https://blogs.cuit.columbia.edu/gjb2124/circular-financing/">The Hidden Risk in AI's Circular Financing Ecosystem</a></li>
<li><a href="https://en.wikipedia.org/wiki/CoreWeave">CoreWeave - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者争论循环融资的说法是否被夸大，指出英伟达 20 亿美元的投资相对于 CoreWeave 350 亿美元的资本支出很小。其他人则关注经济可行性，认为每 token ROI 和企业 token 预算等指标比融资结构更重要。

**标签**: `#Nvidia`, `#GPU`, `#cloud computing`, `#financing`, `#AI infrastructure`

---

<a id="item-2"></a>
## [Grok Build CLI 将整个仓库上传至 xAI](https://gist.github.com/cereblab/dc9a40bc26120f4540e4e09b75ffb547) ⭐️ 8.0/10

分析显示，xAI 的 Grok Build CLI 会将整个仓库内容（包括 .env 文件和 git 历史记录）上传至 xAI 服务器，无论代理读取了什么。 这引发了使用该工具的开发者对隐私和安全的严重担忧，因为 API 密钥和机密等敏感数据可能在未经明确同意的情况下被传输，可能助长大规模监控。 该 CLI 逐字且未脱敏地传输文件内容，包括 .env 机密文件，且上传与代理读取的内容无关，即使只需要子集，整个仓库也会被发送。

hackernews · jhoho · Jul 12, 01:09 · [社区讨论](https://news.ycombinator.com/item?id=48877371)

**背景**: Grok Build 是 xAI 于 2026 年 5 月推出的终端原生 AI 编码代理，旨在帮助开发者完成编码任务。它是 Elon Musk 的 xAI 开发的 Grok 聊天机器人生态系统的一部分。该 CLI 工具旨在提高生产力，但其数据处理方式引发了隐私担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://x.ai/cli">Grok Build Beta | SpaceXAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Grok_(chatbot)">Grok (chatbot) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区表达了震惊和担忧，用户指出这种行为极其令人担忧，让人联想到大规模监控。一些人建议使用 bubblewrap 等沙盒工具来降低风险，而另一些人则认为专有编码代理本质上对隐私构成危险。

**标签**: `#privacy`, `#security`, `#AI tools`, `#xAI`, `#developer tools`

---

<a id="item-3"></a>
## [UPI 架构深度解析：设计、可扩展性与影响](https://timeseriesofindia.com/economy/reads/upi-architecture/) ⭐️ 8.0/10

一篇详细文章探讨了印度统一支付接口（UPI）的架构，涵盖其设计原则、可扩展性及对数字支付的影响。 该分析帮助开发者和架构师理解 UPI 如何可靠地处理数十亿笔交易，为全球构建大规模支付系统提供经验。 文章指出 UPI 每年处理 220 亿笔交易，NPCI 交换机平均每秒约 700 笔，峰值负载更高。还讨论了中心化、基于 KYC 的系统的权衡。

hackernews · prtk25 · Jul 11, 16:33 · [社区讨论](https://news.ycombinator.com/item?id=48873457)

**背景**: UPI 是由印度国家支付公司（NPCI）开发的实时支付系统，通过手机实现银行间交易。它使用称为 UPI ID 的唯一标识符，支持推送（支付）和拉取（收款）交易。该系统在印度被广泛采用，即使是非技术用户也能进行数字支付。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Unified_Payments_Interface">Unified Payments Interface - Wikipedia</a></li>
<li><a href="https://medium.com/@avinashkariya05910/deep-dive-system-design-of-upi-unified-payments-interface-eff3b0334b0d">Deep Dive: System Design of UPI (Unified Payments Interface) | by Avinash Kariya | Medium</a></li>
<li><a href="https://razorpay.com/blog/what-is-upi-and-how-it-works/">What is UPI?: Unified Payments Interface Features and How UPI Works?</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞文章质量和千万/十亿切换功能。一些人对中心化和 KYC 表示担忧，而另一些人则惊叹于 UPI 在吸引老年用户方面的成功。还有人请求与美国/欧洲支付系统进行比较。

**标签**: `#UPI`, `#payment systems`, `#architecture`, `#India`, `#digital payments`

---

<a id="item-4"></a>
## [Bonzo 因预言机漏洞损失 900 万美元，TVL 暴跌 77%](https://www.coindesk.com/web3/2026/07/11/lending-protocol-bonzo-loses-77-of-value-locked-as-usd9-million-oracle-exploit-rattles-hedera) ⭐️ 8.0/10

Hedera 上最大的借贷协议 Bonzo Lend 因攻击者利用 Supra 预言机验证器的漏洞操纵 SAUCE 代币价格，损失约 905 万美元，导致总锁仓量暴跌 77%。 此事件凸显了 DeFi 预言机系统的关键漏洞，尤其是在 Hedera 等新兴区块链上，并强调了采取强有力安全措施保护用户资金的必要性。 该漏洞涉及一个第二个钱包，它借走了约 100 万美元，但自称是白帽黑客，并承诺归还资金。Bonzo 由适配 Hedera 的 Aave v2 智能合约驱动。

rss · CoinDesk · Jul 11, 18:06

**背景**: Bonzo Finance 是一个基于 Hedera 构建的去中心化借贷协议，使用 Aave v2 智能合约。像 Supra 这样的预言机为 DeFi 协议提供价格数据；如果被操纵，攻击者可以利用价格差异盗取资金。SAUCE 代币是 Hedera 上的原生资产。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cointelegraph.com/news/bonzo-lend-9m-oracle-exploit-hedera">Oracle Exploit Drains $9M From Bonzo Lend on Hedera</a></li>
<li><a href="https://bitcoinworld.co.in/bonzo-lend-oracle-exploit-hedera/">Bonzo Lend Loses $9M In Oracle Exploit On Hedera Blockchain</a></li>
<li><a href="https://blockonomi.com/hederas-largest-lending-protocol-bonzo-loses-9m-in-oracle-exploit/">Hedera ’s Largest Lending Protocol, Bonzo, Loses $9M in Oracle Exploit</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#oracle exploit`, `#Hedera`, `#security`, `#lending protocol`

---

<a id="item-5"></a>
## [AI 发现以太坊漏洞，可能导致验证者离线](https://www.coindesk.com/tech/2026/07/10/ai-found-an-ethereum-bug-that-could-take-validators-offline-but-humans-had-to-prove-it) ⭐️ 8.0/10

以太坊基金会协调的 AI 代理在以太坊的 libp2p gossipsub 实现中发现了一个严重漏洞，该漏洞可能导致验证者离线，但人类研究人员必须手动验证并确认该漏洞，之后才被分配了 CVE-2026-34219 编号。 这标志着 AI 在区块链安全领域的实际应用潜力，同时也凸显了其当前的局限性——AI 可以标记问题，但人类专业知识对于验证仍然至关重要。如果该漏洞被利用，可能会导致质押惩罚和节点运营者的操作风险。 该漏洞位于网络层的 gossipsub 协议中，以太坊节点使用该协议进行通信。虽然以太坊的共识机制容忍单个验证者的停机，但如果该漏洞可远程触发或存在于广泛使用的客户端实现中，则变得更加危险，增加了相关停机的风险。

rss · CoinDesk · Jul 11, 12:00

**背景**: 以太坊验证者是质押 ETH 以参与共识并保护网络的节点。gossipsub 协议是 libp2p 的一部分，libp2p 是以太坊客户端用于传播消息的模块化网络栈。以太坊基金会部署了 AI 代理来自动搜索关键软件中的漏洞，但仍需要人类监督来确认真正的漏洞。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/07/10/ai-found-an-ethereum-bug-that-could-take-validators-offline-but-humans-had-to-prove-it">AI found an Ethereum bug that could take validators offline ...</a></li>
<li><a href="https://cryptobriefing.com/ethereum-foundation-ai-protocol-bugs-cve/">Ethereum Foundation says AI found real protocol bugs, but ...</a></li>
<li><a href="https://www.crowdfundinsider.com/2026/07/290812-ethereum-foundation-highlights-ais-role-in-bug-detection-while-emphasizing-human-oversight-in-security-audits/">Ethereum Foundation Highlights AI's Role In Bug Detection ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#Ethereum`, `#blockchain security`, `#bug detection`, `#validators`

---

<a id="item-6"></a>
## [Mesh LLM：基于 Iroh 的分布式 AI 计算](https://www.iroh.computer/blog/mesh-llm) ⭐️ 7.0/10

Mesh LLM 是一个新的分布式推理系统，它利用 iroh 网络库将大型语言模型拆分到多个节点上，从而实现协作式 AI 计算。该项目是开源的且处于实验阶段，已有贡献者积极回答社区问题。 这种方法通过允许硬件配置一般的用户汇集资源进行推理，使大型模型的访问更加民主化，可能减少对昂贵集中式基础设施的依赖。它还探索了点对点 AI，这可能在隐私敏感或离线环境中催生新的应用。 该系统使用自定义的'skippy'引擎在节点间拆分模型，性能数据显示 Qwen 235B MoE 在 2 个节点上达到了每秒 16 个 token。然而，社区成员指出消费级网络速度远慢于本地内存，引发了延迟方面的担忧。

hackernews · tionis · Jul 11, 22:38 · [社区讨论](https://news.ycombinator.com/item?id=48876505)

**背景**: 分布式推理将 AI 模型的计算拆分到多个设备上，以处理单台机器无法容纳的大型模型。Iroh 是一个简化点对点连接的网络库，使构建分布式应用更加容易。Mesh LLM 利用 iroh 来协调跨节点的模型分片和推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.iroh.computer/blog/mesh-llm">Mesh LLM: distributed AI computing on iroh - Iroh</a></li>
<li><a href="https://github.com/Mesh-LLM/mesh-llm">GitHub - Mesh-LLM/mesh-llm: Distributed AI/LLM for the people ...</a></li>
<li><a href="https://www.iroh.computer/">iroh</a></li>

</ul>
</details>

**社区讨论**: 社区成员表示对将分布式推理用于小型专用模型而非大型编码 LLM 感兴趣。有人提出了性能担忧，指出即使 10 Gbit 以太网也比本地内存慢，但贡献者提供了 Qwen 235B 在 2 个节点上每秒 16 个 token 的基准测试结果。

**标签**: `#distributed computing`, `#LLM`, `#inference`, `#iroh`, `#AI`

---

<a id="item-7"></a>
## [ClickHouse 通过 Peering 机制将 PgBouncer 吞吐量提升 4 倍](https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres) ⭐️ 7.0/10

ClickHouse 详细介绍了他们如何通过实现一种 peering 机制，将查询取消请求转发到正确的进程，从而将 PgBouncer 的吞吐量提升 4 倍。这使得多个 PgBouncer 进程可以通过 so_reuseport 共享单个端口并协调取消操作。 这一创新将 PgBouncer 从瓶颈转变为可扩展组件，从而在多核机器上实现更高的 PostgreSQL 连接池吞吐量。它直接惠及运行大规模 PostgreSQL 部署的用户，这些用户需要在多个池化进程之间实现高效的查询取消。 Peering 机制确保落在错误进程上的取消请求被转发到拥有该会话的进程。ClickHouse 使用 so_reuseport 和 peering 运行一组 PgBouncer 进程，实现了 4 倍的吞吐量提升。

hackernews · saisrirampur · Jul 11, 15:28 · [社区讨论](https://news.ycombinator.com/item?id=48872874)

**背景**: PgBouncer 是一个轻量级、单线程的 PostgreSQL 连接池器。其单线程特性限制了在多核机器上的性能，并且当多个进程共享一个端口时，查询取消可能会失败，因为取消请求可能落在不拥有该会话的进程上。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres">How we scale PgBouncer in ClickHouse Managed Postgres</a></li>
<li><a href="https://www.pgbouncer.org/">PgBouncer - lightweight connection pooler for PostgreSQL</a></li>
<li><a href="https://www.pgbouncer.org/config.html">PgBouncer config</a></li>

</ul>
</details>

**社区讨论**: 评论者提出了替代方案，如 Odyssey 和 pgdog，并讨论了实际的 Kubernetes 注意事项，例如在每个 Pod 内或跨 Pod 运行多个 PgBouncer 进程。一位用户询问 peering 是否适用于 Kubernetes，因为独立的 Pod 拥有独立的池。

**标签**: `#PostgreSQL`, `#PgBouncer`, `#connection pooling`, `#scalability`, `#ClickHouse`

---

<a id="item-8"></a>
## [美国住房法禁止美联储发行 CBDC 至 2030 年](https://www.coindesk.com/policy/2026/07/10/u-s-government-digital-dollar-set-to-be-banned-tonight-under-housing-law-s-cbdc-limit) ⭐️ 7.0/10

《21 世纪住房法案》中的一项条款禁止美联储在 2030 年 12 月 31 日之前发行中央银行数字货币（CBDC），该法案已在未经总统签署的情况下成为法律。 这项禁令使美国 CBDC 开发停滞数年，可能将数字货币创新领导权拱手让给中国等国。这也表明政府对发行数字货币存在强烈政治反对，影响金融科技和加密货币市场。 该禁令适用于美联储，禁止其在 2030 年前发行 CBDC 或类似资产。该条款被纳入一项住房法案，并在未经特朗普总统签署的情况下通过，反映出两党对限制措施的支持。

rss · CoinDesk · Jul 10, 16:02

**背景**: 中央银行数字货币（CBDC）是由中央银行发行和支持的国家法定货币的数字形式。与加密货币不同，CBDC 是中心化的，并遵循与传统货币相同的货币政策。包括中国在内的许多国家正在积极开发 CBDC，而美国一直在讨论其潜在利益和风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cryptopolitan.com/house-republicans-cbdc-ban-housing-bill/">House Republicans insist on a permanent CBDC ban... - Cryptopolitan</a></li>
<li><a href="https://www.kucoin.com/news/flash/us-cbdc-ban-takes-effect-as-housing-bill-passes-without-trump-signature">US CBDC Ban Takes Effect as Housing Bill Passes Without... | KuCoin</a></li>
<li><a href="https://www.pymnts.com/cbdc/2026/us-cbdc-ban-set-to-become-law-at-midnight/">PYMNTS | US CBDC Ban Set to Become Law at Midnight</a></li>

</ul>
</details>

**标签**: `#CBDC`, `#digital currency`, `#regulation`, `#US policy`

---

<a id="item-9"></a>
## [苹果起诉 OpenAI 窃取商业机密](https://decrypt.co/373339/apple-sues-openai-claims-former-employees-stole-trade-secrets) ⭐️ 7.0/10

苹果已对 OpenAI 提起诉讼，指控前员工在加入这家 AI 公司前窃取了包括机密设计和供应商信息在内的商业机密。 这两家科技巨头之间的法律诉讼可能重塑 AI 行业的知识产权实践，并为公司如何保护员工跳槽到竞争对手时的商业机密树立先例。 诉讼称，前苹果员工在加入 OpenAI 前带走了机密设计、供应商信息和工程文件，但被盗材料的具体细节尚未公开。

rss · Decrypt · Jul 10, 21:50

**背景**: 商业机密诉讼在科技行业员工跳槽至竞争对手时很常见。苹果和 OpenAI 都是 AI 领域的主要参与者，苹果正在开发自己的 AI 模型，而 OpenAI 以 ChatGPT 闻名。此案凸显了人才流动与知识产权保护之间的紧张关系。

**标签**: `#Apple`, `#OpenAI`, `#trade secrets`, `#lawsuit`, `#AI`

---

<a id="item-10"></a>
## [剑桥研究：31%以太坊节点位于美国，三分之一离线可致最终性停滞](https://www.theblock.co/post/407909/cambridge-research-puts-ethereum-node-activity-in-us-where-third-offline-can-stall-finalization?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

剑桥替代金融中心的新研究显示，31%的以太坊节点活动集中在美国，如果其中三分之一的节点离线，可能会阻碍网络最终性。 这种集中引发了对以太坊去中心化和司法风险的严重担忧，因为单一国家的基础设施问题可能破坏整个网络，削弱其核心价值主张。 这些节点高度集中在 AWS、Hetzner 和 OVH 等云服务提供商上，研究还指出，约 39%的节点活动位于欧盟（不包括英国）。

rss · The Block · Jul 10, 16:07

**背景**: 以太坊节点是运行以太坊软件的计算机，负责验证交易和维护区块链。最终性是区块变得不可逆的过程；如果太多节点离线，网络无法最终确定新区块，导致运营停滞。节点集中在单一司法管辖区会造成单点故障。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/407909/cambridge-research-puts-ethereum-node-activity-in-us-where-third-offline-can-stall-finalization">Cambridge research puts 31% of Ethereum node activity... | The Block</a></li>
<li><a href="https://massachain.medium.com/ethereums-node-centralization-challenge-and-how-massa-can-help-2744e22160ca">Ethereum ’s Node Centralization Challenge — and how... | Medium</a></li>
<li><a href="https://www.ainvest.com/news/ethereum-decentralization-risk-implications-long-term-investment-strategy-2601/">Ethereum 's Decentralization at Risk : Implications for Long-Term Value...</a></li>

</ul>
</details>

**社区讨论**: 社区长期以来一直在讨论节点中心化问题，Vitalik Buterin 此前曾将其列为主要挑战。一些人认为地理多样性正在改善，而另一些人则担心云服务提供商的主导地位和监管风险。

**标签**: `#Ethereum`, `#decentralization`, `#blockchain`, `#node centralization`, `#research`

---

<a id="item-11"></a>
## [激光攻击可重置 Tangem 钱包密码](https://www.theblock.co/post/407871/ledger-researchers-disclose-tangem-card-flaw-tangem-says-risk-to-everyday-users-is-virtually-non-existent?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Ledger Donjon 研究人员披露了一种激光故障注入攻击，通过绕过固件恢复状态检查，可以重置 Tangem 硬件钱包卡的密码。Tangem 回应称，由于需要物理接触和昂贵设备，对日常用户的风险几乎不存在。 此漏洞凸显了硬件钱包（尤其是可能缺乏主动防护措施的卡片式设计）持续面临的安全挑战。它可能削弱对 Tangem 产品的信任，并重新引发关于硬件钱包安全标准的讨论。 该攻击需要物理接触卡片以及价值约 25 万美元的激光设备，对大多数攻击者而言不切实际。Tangem 声称该固件漏洞已在较新版本的卡片中得到修复。

rss · The Block · Jul 10, 11:08

**背景**: 硬件钱包离线存储加密货币私钥，以防止远程黑客攻击。Tangem 卡是一种类似信用卡的硬件钱包，使用安全芯片。激光故障注入是一种物理攻击技术，利用激光在芯片操作中诱发错误，从而可能绕过安全检查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thehackernews.com/2026/07/laser-attack-resets-tangem-wallet.html">Laser Attack Resets Tangem Wallet Passwords on Cards That Can ...</a></li>
<li><a href="https://coinalertnews.com/news/2026/07/10/tangem-wallet-laser-attack">Tangem Hardware Wallets Vulnerable to Laser Attacks, No ...</a></li>
<li><a href="https://financefeeds.com/ledger-finds-laser-attack-that-can-reset-tangem-card-passwords/">Ledger Finds Laser Attack That Can Reset Tangem Card ...</a></li>

</ul>
</details>

**标签**: `#security`, `#hardware wallet`, `#vulnerability`, `#cryptocurrency`, `#Tangem`

---

<a id="item-12"></a>
## [Ant：一个全新的 JavaScript 运行时与一体化生态系统](https://antjs.org/) ⭐️ 6.0/10

Ant 是一个全新的 JavaScript 运行时，拥有自己的引擎、包管理器（ants.land）、托管平台和桌面应用构建器（Ant Desktop），旨在为现有 JavaScript 技术栈提供一个连贯的端到端替代方案。 该项目通过提供紧密集成的生态系统，承诺更小的体积、更快的启动速度和沙箱机制，挑战 Node.js 和 Deno 的主导地位，可能降低开发者构建和部署 JavaScript 应用的门槛。 Ant 是从零构建的，声称单个 9 MB 的二进制文件即可实现接近 V8 的速度，但社区评论指出早期版本依赖现有的 AGPL 代码库（Elk），作者表示此后已重写。

hackernews · theMackabu · Jul 11, 20:07 · [社区讨论](https://news.ycombinator.com/item?id=48875377)

**背景**: JavaScript 运行时（如 Node.js 和 Deno）在浏览器之外执行 JavaScript。Ant 引入了自己的引擎和生态系统，类似于 Node.js 使用 V8 和 npm，但旨在实现更紧密的集成和更小的体积。名称“Ant”与 Apache Ant（一个构建工具）存在冲突。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/themackabu/ant">GitHub - theMackabu/ ant : javascript for 's, a tiny runtime with big...</a></li>
<li><a href="https://zeli.app/en/story/48875377">Ant - Lightweight JavaScript runtime with near-V8 speeds... | Zeli</a></li>
<li><a href="https://eucloudservers.com/architecture-reliability/show-hn-ant-a-javascript-runtime-and-ecosystem/">Show HN: Ant – A JavaScript Runtime And... - EU Cloud Servers</a></li>

</ul>
</details>

**社区讨论**: 社区评论对该项目的原创性提出质疑，指出早期版本使用了现有的 AGPL 代码库（Elk），尽管声称是从零构建。此外，还有关于与 Apache Ant 命名冲突的批评，以及对能否在性能上超越 Node.js 等成熟运行时的怀疑。

**标签**: `#JavaScript`, `#runtime`, `#ecosystem`, `#web development`

---

<a id="item-13"></a>
## [加密巨头支持 AI 代理争议解决法庭](https://www.coindesk.com/business/2026/07/10/okx-metamask-matter-labs-back-dispute-resolution-court-for-ai-agents) ⭐️ 6.0/10

包括 OKX、MetaMask 和 Matter Labs 在内的 27 家加密和 Web3 公司组成的联盟推出了“互联网法庭”协议，用于解决 AI 代理之间的争议。该倡议由 Genlayer 基金会领导。 随着 AI 代理越来越多地进行自主交易，专门的争议解决机制对于去中心化经济中的信任和可扩展性至关重要。这标志着向代理间商业基础设施迈出了重要一步。 该协议处理基于 AI 的支付、托管和争议解决，并得到 27 家公司的支持。关于仲裁过程或智能合约实施的技术细节尚未披露。

rss · CoinDesk · Jul 10, 12:29

**背景**: AI 代理是自主程序，可以在没有人类批准的情况下执行交易，如购买、出售或承诺资金。当它们在区块链上交互时，可能会产生争议（例如，一个代理违约），需要中立的第三方进行裁决。互联网法庭旨在通过提供去中心化的争议解决层来填补这一空白。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/10/okx-metamask-matter-labs-back-dispute-resolution-court-for-ai-agents">OKX, MetaMask, Matter Labs back dispute resolution court for ...</a></li>
<li><a href="https://en.cryptonomist.ch/2026/07/10/ai-agent-dispute-resolution/">AI Agent Dispute Resolution Powers Internet Court Protocol</a></li>
<li><a href="https://financefeeds.com/okx-metamask-and-matter-labs-back-internet-court-for-ai-agents/">OKX, MetaMask and Matter Labs Back Internet Court for AI Agents</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#AI agents`, `#dispute resolution`, `#crypto`

---

<a id="item-14"></a>
## [Robinhood Chain：面向代币化股票的以太坊二层网络](https://decrypt.co/resources/what-robinhood-chain-ethereum-layer-2-network-tokenized-stocks) ⭐️ 6.0/10

Robinhood Chain 是一个基于 Arbitrum 技术构建的新以太坊二层网络，旨在支持代币化股票、加密应用和链上金融产品。 这一发展通过在可扩展、低成本的二层网络上实现代币化股票，连接了传统金融与 DeFi，可能提高区块链上现实世界资产的可访问性和流动性。 Robinhood Chain 使用 Arbitrum 的 Optimistic Rollup 技术将交易在链下批量处理，降低费用和延迟，同时继承以太坊的安全性。它针对代币化股票和链上金融应用。

rss · Decrypt · Jul 11, 16:21

**背景**: 像 Arbitrum 这样的以太坊二层解决方案通过在链下处理交易并将压缩数据发布到主链来扩展网络。代币化股票是传统股票在区块链上的数字表示，支持部分所有权和全天候交易。Robinhood Chain 结合了这些概念，为链上金融提供专用平台。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blockspot.io/what-is-arbitrum-ethereum-layer-2/">What Is Arbitrum ? Ethereum Layer - 2 for Faster Transactions</a></li>
<li><a href="https://www.coingecko.com/learn/what-are-tokenized-stocks">What Are Tokenized Stocks and Top Platforms to Get Started</a></li>
<li><a href="https://zipmex.com/blog/what-is-arbitrum/">What Is Arbitrum (ARB)? Complete 2026 Guide</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#Layer-2`, `#DeFi`, `#Tokenized Assets`, `#Arbitrum`

---

<a id="item-15"></a>
## [Xbox CEO 在裁员潮中加入美联储 AI 工作组](https://decrypt.co/373277/xbox-ceo-fed-ai-jobs-task-force-days-after-layoffs) ⭐️ 6.0/10

Xbox CEO Asha Sharma 加入了美联储 AI 工作组，就人工智能对就业和生产力的影响提供建议，而就在几天前，微软宣布在其游戏部门裁员 3200 人。 这凸显了 AI 应用与劳动力替代之间的紧张关系，一位大型游戏高管在监督大规模裁员的同时参与政策讨论。这强调了需要平衡的 AI 政策，兼顾创新和就业影响。 此次裁员是微软 Xbox 历史上最大规模重组的一部分，影响 3200 名员工。Sharma 在美联储工作组的职责是就 AI 如何重塑劳动力市场和生产力提供建议。

rss · Decrypt · Jul 10, 18:02

**背景**: 美联储成立了一个 AI 工作组，研究人工智能的经济影响，包括其对就业和生产力的影响。作为微软旗下的部门，Xbox 在更广泛的科技行业裁员潮中正在进行重大重组。

**标签**: `#AI`, `#policy`, `#gaming`, `#layoffs`

---

<a id="item-16"></a>
## [Circle 获得 OCC 最终批准成立国家信托银行](https://decrypt.co/373227/circle-stock-jumps-stablecoin-issuer-final-federal-banking-charter) ⭐️ 6.0/10

Circle 已获得美国货币监理署（OCC）的最终批准，成立一家国家信托银行，将其 732 亿美元的 USDC 稳定币纳入统一的联邦监管框架。 这一里程碑标志着主要稳定币发行商首次获得联邦银行执照，可能为加密货币行业的合规监管树立先例，并增强机构对稳定币的信心。 该执照批准成立一家名为 First National Digital Currency Bank 的国家信托银行，USDC 储备管理计划将在后续阶段实施。Circle 加入了 OCC 监管的约 60 家国家信托银行之列。

rss · Decrypt · Jul 10, 14:54

**背景**: 国家信托银行是一种联邦特许金融机构，可以托管资产，但不能吸收存款或发放贷款。OCC 逐步批准了与加密货币相关的信托执照，包括 2025 年 12 月对五家实体的有条件批准。USDC 是一种完全由美国国债和现金支持的稳定币，其储备约 80% 为国债，约 20% 为现金。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.occ.gov/news-issuances/news-releases/2025/nr-occ-2025-125.html">OCC Announces Conditional Approvals for Five National Trust ...</a></li>
<li><a href="https://www.circle.com/blog/how-the-usdc-reserve-is-structured-and-managed">How the USDC Reserve is Structured and Managed - Circle</a></li>
<li><a href="https://usdc.org/tools/reserves">USDC Reserves & Transparency - Proof of Backing | USDC.org</a></li>

</ul>
</details>

**标签**: `#stablecoin`, `#regulation`, `#cryptocurrency`, `#banking`

---

<a id="item-17"></a>
## [Revolut X 集成 AI 助手进行加密货币交易](https://www.theblock.co/post/407865/revolut-integrates-its-crypto-exchange-with-ai-assistants-as-agentic-trading-spreads?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Revolut 旗下的加密货币交易所 Revolut X 现已与 Claude、Gemini、OpenClaw 和 Cursor 等 AI 助手连接，用户可以通过自然语言提示进行分析、回测和执行交易。 这一集成标志着向代理交易迈出一步，AI 代理协助决策和执行，可能使加密货币交易对零售用户更易用、更高效。 Revolut X 支持超过 210 种加密货币，费用低廉（挂单费 0%，吃单费最高 0.09%），AI 集成允许用户无需编码即可执行回测策略等复杂任务。

rss · The Block · Jul 10, 10:04

**背景**: Revolut X 是英国金融科技公司 Revolut（拥有超过 5000 万客户）推出的高级加密货币交易平台。代理交易是指使用自主 AI 代理监控市场并生成信号，通常需要人工批准才能执行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.revolut.com/revolut-x/">Revolut X Advanced Crypto Exchange | Cryptocurrency Trading ...</a></li>
<li><a href="https://wundertrading.com/journal/en/agentic-trading">Agentic Trading Explained: How Autonomous AI Agents Are ...</a></li>

</ul>
</details>

**标签**: `#crypto`, `#AI`, `#trading`, `#integration`

---