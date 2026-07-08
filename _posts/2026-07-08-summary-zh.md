---
layout: default
title: "Horizon Summary: 2026-07-08 (ZH)"
date: 2026-07-08
lang: zh
---

> From 83 items, 27 important content pieces were selected

---

1. [Kokoro：本地、CPU 友好、高质量 TTS，支持 IPA 发音控制](#item-1) ⭐️ 8.0/10
2. [欧盟聊天控制提案威胁隐私与加密](#item-2) ⭐️ 8.0/10
3. [Anthropic 因隐私担忧移除 Claude 隐藏代码追踪器](#item-3) ⭐️ 8.0/10
4. [中国悄然制定类似美国的 AI 出口管制](#item-4) ⭐️ 8.0/10
5. [中国情感 AI 新规迫使字节跳动和阿里巴巴下架智能体功能](#item-5) ⭐️ 8.0/10
6. [Bonk DAO 金库遭治理攻击损失 2000 万美元](#item-6) ⭐️ 8.0/10
7. [以太坊计划自合并以来最大规模升级](#item-7) ⭐️ 8.0/10
8. [GAO：能源部过早排除更便宜的核清理方案](#item-8) ⭐️ 7.0/10
9. [StreetComplete：将 OpenStreetMap 贡献游戏化](#item-9) ⭐️ 7.0/10
10. [Davit：苹果容器的原生 macOS 界面](#item-10) ⭐️ 7.0/10
11. [欧盟强制要求所有新车安装驾驶员监控摄像头](#item-11) ⭐️ 7.0/10
12. [Rowboat：开源的本地优先 Claude Desktop 替代品](#item-12) ⭐️ 7.0/10
13. [TeraWulf 因与 Anthropic 签订 190 亿美元 AI 数据中心租约而飙升](#item-13) ⭐️ 7.0/10
14. [联合国秘书长警告：'我们不能用 Vibe Coding 来编码人类的未来'](#item-14) ⭐️ 7.0/10
15. [美国战略比特币储备解读](#item-15) ⭐️ 7.0/10
16. [30papers.com：以初学者友好格式呈现 Ilya 的机器学习论文](#item-16) ⭐️ 6.0/10
17. [K 和 Q 语言的新闭源运行时](#item-17) ⭐️ 6.0/10
18. [SEC 本月拟提出加密规则以简化初创企业融资](#item-18) ⭐️ 6.0/10
19. [Visa 数据显示 USDC 在稳定币交易量上超越 Tether](#item-19) ⭐️ 6.0/10
20. [研究警告：大学未跟上 AI 职场变革](#item-20) ⭐️ 6.0/10
21. [肯尼亚监管机构寻求区块链工具追踪加密犯罪](#item-21) ⭐️ 6.0/10
22. [英国警告：无安全保障将导致“AI 广岛”](#item-22) ⭐️ 6.0/10
23. [Coinbase AI 在比赛前虚构世界杯结果](#item-23) ⭐️ 6.0/10
24. [Strike 推出“抗波动”比特币贷款](#item-24) ⭐️ 6.0/10
25. [Zcash 接近防伪数学证明，ZEC 上涨 12%](#item-25) ⭐️ 6.0/10
26. [Galaxy 将比特币矿场转为 CoreWeave 的 AI 数据中心](#item-26) ⭐️ 6.0/10
27. [交易员起诉 Polymarket 关于比特币出售市场的裁决](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Kokoro：本地、CPU 友好、高质量 TTS，支持 IPA 发音控制](https://ariya.io/2026/03/local-cpu-friendly-high-quality-tts-text-to-speech-with-kokoro/) ⭐️ 8.0/10

Kokoro 是一个仅有 8200 万参数的开源权重 TTS 模型，现在可以在本地 CPU 上实现高质量语音合成，无需 GPU。 这使得 GPU 资源有限的用户和开发者也能使用先进的 TTS 技术，从而在无障碍、内容消费等领域实现保护隐私的离线应用。 Kokoro 支持手动添加 IPA 发音指南以实现精确控制，但在处理单个单词和同形异义词时存在困难。该模型可在 GitHub 的 hexgrad/kokoro 仓库中获取。

hackernews · speckx · Jul 7, 18:24 · [社区讨论](https://news.ycombinator.com/item?id=48821576)

**背景**: 文本转语音（TTS）将书面文字转换为语音音频。许多高质量的 TTS 模型需要强大的 GPU，限制了它们在普通硬件上的使用。Kokoro 的 8200 万参数设计在实现与更大模型相当的质量的同时，对 CPU 友好且速度快。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/hexgrad/kokoro">GitHub - hexgrad/kokoro: https://hf.co/hexgrad/Kokoro-82M · GitHub</a></li>
<li><a href="https://kokorottsai.com/">Kokoro TTS: Advanced AI Text-to-Speech Model with 82M parameters</a></li>

</ul>
</details>

**社区讨论**: 用户称赞 Kokoro 的质量和 CPU 效率，有开发者将其集成到无障碍产品中，还有人构建了播客流水线。但他们也指出该模型在单词语音和同形异义词消歧方面存在局限。

**标签**: `#TTS`, `#accessibility`, `#open-source`, `#machine learning`, `#CPU`

---

<a id="item-2"></a>
## [欧盟聊天控制提案威胁隐私与加密](https://fightchatcontrol.eu/chat-control-overview) ⭐️ 8.0/10

欧盟正在谈判聊天控制 1.0 和 2.0，要求对私人通信进行强制扫描以查找儿童性虐待材料（CSAM），包括加密消息。 如果通过，这些提案将破坏端到端加密，并对所有公民实施大规模监控，为全球数字隐私权树立危险先例。 聊天控制 1.0 允许提供商自愿扫描，即将到期，但谷歌和 Meta 等大公司计划继续扫描。聊天控制 2.0 将要求在加密通信上进行扫描，可能破坏加密。

hackernews · gasull · Jul 7, 14:23 · [社区讨论](https://news.ycombinator.com/item?id=48818311)

**背景**: 聊天控制是指欧盟旨在检测私人消息中 CSAM 的立法提案。聊天控制 1.0 是对 ePrivacy 指令的临时豁免，允许自愿扫描。聊天控制 2.0 提议强制扫描，包括在端到端加密平台上，引发了严重的隐私和安全担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>
<li><a href="https://eutechloop.com/double-threat/">Double threat to privacy: Chat Control 1.0 and 2.0 are back</a></li>
<li><a href="https://www.patrick-breyer.de/en/posts/chat-control/">Chat Control: The EU's CSAM scanner proposal</a></li>

</ul>
</details>

**社区讨论**: 评论者表示强烈反对，认为这些提案是以儿童保护为幌子的广泛监控措施。一些人强调了扫描加密消息的技术问题，指出这需要客户端扫描或破坏加密。

**标签**: `#privacy`, `#encryption`, `#EU legislation`, `#surveillance`, `#CSAM`

---

<a id="item-3"></a>
## [Anthropic 因隐私担忧移除 Claude 隐藏代码追踪器](https://decrypt.co/372977/anthropic-removes-hidden-claude-code-tracker-privacy) ⭐️ 8.0/10

在研究人员对未公开的监控行为提出隐私担忧后，Anthropic 从其 AI 助手 Claude 中移除了一个隐藏的代码追踪器。 这一事件凸显了 AI 工具在防止滥用与尊重用户隐私之间的张力，并可能影响其他公司如何处理监控功能的透明度。 该追踪器旨在防止滥用和 AI 模型提取，但批评者认为未公开的监控侵犯了用户信任。Anthropic 表示经过内部审查后已移除该工具。

rss · Decrypt · Jul 7, 22:31

**背景**: AI 模型提取是指通过大量查询来窃取或复制专有 AI 模型的行为。像 Anthropic 这样的公司使用监控工具来检测此类滥用，但隐私倡导者认为用户应被告知任何数据收集。这一争议呼应了关于 AI 服务中监控问题的更广泛辩论。

**标签**: `#AI`, `#privacy`, `#Anthropic`, `#Claude`, `#ethics`

---

<a id="item-4"></a>
## [中国悄然制定类似美国的 AI 出口管制](https://decrypt.co/372958/china-us-quiet-crackdown-ai-exports) ⭐️ 8.0/10

据报道，中国正在制定 AI 技术出口管制措施，效仿美国政府 2026 年 6 月暂时禁止 Anthropic 向外国用户提供其先进 AI 模型的指令。 此举标志着全球两大经济体之间 AI 贸易限制可能升级，可能导致全球 AI 供应链分裂，并阻碍前沿 AI 领域的国际合作。 美国对 Anthropic 的 Claude Fable 5 和 Mythos 5 模型的出口管制已于 2026 年 6 月 30 日解除，此前仅短暂暂停。中国据称的管制措施仍在制定中，其范围尚不明确。

rss · Decrypt · Jul 7, 19:51

**背景**: 2026 年 6 月，美国政府以国家安全为由，命令 Anthropic 暂停其最先进 AI 模型 Claude Fable 5 和 Mythos 5 的访问权限。该命令两周后被撤销。这一事件凸显了各国政府利用出口管制限制尖端 AI 技术获取的趋势，尤其是在中美之间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://therecord.media/us-lifts-export-controls-anthropic-cyber-models">US lifts export controls on Anthropic’s frontier cybersecurity AI models | The Record from Recorded Future News</a></li>
<li><a href="https://www.justsecurity.org/142745/law-anthropic-export-controls/">Legal Considerations Related to the Anthropic “Export Controls Directive”</a></li>
<li><a href="https://techjournal.org/us-ai-export-controls-anthropic-ban-2026">US AI Export Controls 2026: The Anthropic Ban Explained</a></li>

</ul>
</details>

**标签**: `#AI`, `#export controls`, `#geopolitics`, `#China`, `#US`

---

<a id="item-5"></a>
## [中国情感 AI 新规迫使字节跳动和阿里巴巴下架智能体功能](https://decrypt.co/372873/bytedance-alibaba-agent-features-china-cracks-down-humanlike-ai) ⭐️ 8.0/10

字节跳动和阿里巴巴正在其消费级 AI 应用豆包和通义千问中禁用自定义智能体功能，以应对中国针对类人情感 AI 互动的新规，该规定将于 2026 年 7 月 15 日生效。 这标志着中国首次直接监管情感 AI，可能为全球 AI 治理树立先例。此举可能重塑全球 AI 伴侣的设计和部署方式，尤其是在心理安全方面。 新规将“类人情感互动”定义为受监管领域，并要求企业实施心理安全控制。字节跳动和阿里巴巴以“产品功能调整”为由禁用相关功能。

rss · Decrypt · Jul 6, 21:37

**背景**: 中国一直在起草更严格的 AI 法规，包括防止聊天机器人以可能导致自杀或自残的方式影响情绪的规定。2025 年 12 月发布的草案针对情感交互式 AI 服务，将心理安全转化为合规义务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.scmp.com/tech/big-tech/article/3359482/bytedance-and-alibaba-disable-humanlike-ai-custom-agents-new-rules-loom">ByteDance and Alibaba to disable humanlike AI custom agents as new rules loom | South China Morning Post</a></li>
<li><a href="https://www.cnbc.com/2025/12/29/china-ai-chatbot-rules-emotional-influence-suicide-gambling-zai-minimax-talkie-xingye-zhipu.html">China to crack down on AI chatbots around suicide, gambling</a></li>
<li><a href="https://www.williamfry.com/knowledge/chinas-draft-framework-for-emotionally-interactive-ai-psychological-safety-rules-for-ai-companions/">China's Draft Framework for Emotionally Interactive AI: Psychological Safety Rules for AI Companions - WILLIAM FRY</a></li>

</ul>
</details>

**标签**: `#AI regulation`, `#China`, `#emotional AI`, `#ByteDance`, `#Alibaba`

---

<a id="item-6"></a>
## [Bonk DAO 金库遭治理攻击损失 2000 万美元](https://decrypt.co/372862/solana-meme-coin-bonk-treasury-drained-20-million) ⭐️ 8.0/10

攻击者利用 Bonk DAO 的链上治理系统通过了一项恶意提案，从金库中盗取了约 2000 万美元的 BONK 代币。 这一事件凸显了 DAO 治理系统的脆弱性，尤其是对于拥有庞大金库的 meme 币项目，可能会削弱整个 Solana 生态对去中心化治理机制的信任。 攻击者积累了约 400 万美元的 BONK 代币以获得主导投票权，然后提交了一项提案，该提案仅由七个地址投票，以 99.878% 的得票率通过。被盗代币正在被转移到交易所。

rss · Decrypt · Jul 6, 20:56

**背景**: 去中心化自治组织（DAO）是由智能合约管理的社区主导实体，代币持有者通过投票决定提案。治理攻击是指攻击者获得足够投票权以通过恶意提案，从而实际控制 DAO 的金库。此次攻击无需技术漏洞，仅需资金和薄弱的投票系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/bonk-dao-loses-20-million-180738851.html">BONK DAO Loses $20 Million in Governance Attack, Token Falls 10%</a></li>
<li><a href="https://www.coindesk.com/markets/2026/07/07/bonk-faces-usd20-million-treasury-drain-after-attacker-spends-usd4-million-to-pass-malicious-proposal">BONK faces $20 million treasury drain after attacker spends $4 million to pass malicious proposal</a></li>
<li><a href="https://crypto.news/what-is-a-governance-attack-how-bonkdao-lost-20m-in-a-single-vote/">What is a governance attack? How BonkDAO lost $20M in a single vote</a></li>

</ul>
</details>

**标签**: `#Solana`, `#DeFi`, `#security`, `#governance`, `#exploit`

---

<a id="item-7"></a>
## [以太坊计划自合并以来最大规模升级](https://decrypt.co/372803/ethereum-reinventing-itself-with-biggest-overhaul-since-the-merge-vitalik-buterin) ⭐️ 8.0/10

Vitalik Buterin 于 2026 年 7 月 4 日发布了更新的“精益以太坊”路线图，概述了一项为期 3-4 年的计划，旨在重建以太坊协议的几乎所有核心组件，重点聚焦量子安全和隐私保护。 此次升级是自 2022 年合并以来以太坊最重大的变革，可能重塑区块链的安全性、可扩展性以及抵御量子计算威胁的长期可行性。 关键变化包括：用递归 STARK 证明验证取代直接交易重执行，用量子安全密码学替代易受量子攻击的密码学，以及引入多维 gas 和一至两轮最终确定性。

rss · Decrypt · Jul 6, 12:51

**背景**: 2022 年 9 月的合并将以太坊从工作量证明过渡到权益证明，能耗降低超过 99%。新的“精益以太坊”路线图旨在通过应对量子计算等新兴威胁以及利用密码学证明提高效率，进一步演进协议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/372803/ethereum-reinventing-itself-with-biggest-overhaul-since-the-merge-vitalik-buterin">Ethereum 'Reinventing Itself' With Biggest Overhaul Since the Merge: Vitalik Buterin - Decrypt</a></li>
<li><a href="https://thedefiant.io/news/blockchains/vitalik-buterin-outlines-lean-ethereum-roadmap-a-three-to-four-year-protocol-overhaul">Vitalik Buterin Outlines 'Lean Ethereum' Roadmap, a Three-to-Four-Year Protocol Overhaul - "The Defiant"</a></li>
<li><a href="https://ethereum.org/roadmap/merge/">The Merge | ethereum.org</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#blockchain`, `#cryptocurrency`, `#protocol upgrade`, `#quantum safety`

---

<a id="item-8"></a>
## [GAO：能源部过早排除更便宜的核清理方案](https://www.gao.gov/products/gao-26-108193) ⭐️ 7.0/10

一份新的 GAO 报告（GAO-26-108193）指出，能源部（DOE）在大型核废料清理项目中过早排除了更便宜的方案，可能导致不必要的成本增加。 这很重要，因为 DOE 的清理任务是全球最大的环境修复工作之一，过早排除成本效益更高的替代方案可能浪费数十亿美元的纳税人资金，并推迟清理进度。 报告强调，DOE 需要改进数据和项目管理，以确保在采用昂贵方案之前考虑所有可行选项。GAO 此前已指出多个清理项目可能实现显著的成本和时间节约。

hackernews · Jimmc414 · Jul 7, 22:23 · [社区讨论](https://news.ycombinator.com/item?id=48824826)

**背景**: DOE 的环境管理办公室（EM）负责清理数十年来武器生产和能源研究产生的核废料。这包括退役设施、处理受污染的土壤和地下水，以及处置低放废物。GAO 定期审计这些项目以发现低效问题并提出改进建议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gao.gov/products/gao-26-108193">Nuclear Waste Cleanup: Changes Needed to Ensure DOE Is Not ...</a></li>
<li><a href="https://www.gao.gov/products/gao-26-107820">U.S. GAO - Nuclear Waste Cleanup: DOE Needs to Improve the ...</a></li>
<li><a href="https://www.gao.gov/products/gao-26-107957">U.S. GAO - Nuclear Waste Cleanup: Better Data and Project ...</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞 GAO 报告的清晰性和可操作的建议。有人指出，大多数超过 10 年的场外封存站点未能防止泄漏，质疑长期储存的可行性。另一个人则认为这是一个未来价值数十亿美元的产业。

**标签**: `#nuclear cleanup`, `#government accountability`, `#cost analysis`, `#policy`

---

<a id="item-9"></a>
## [StreetComplete：将 OpenStreetMap 贡献游戏化](https://streetcomplete.app/) ⭐️ 7.0/10

StreetComplete 是一款移动应用，通过向用户展示小型本地化任务来修复 OpenStreetMap 上缺失或过时的数据，使初学者也能轻松贡献。 通过降低参与门槛，StreetComplete 显著提高了社区对 OpenStreetMap 的参与度，而 OpenStreetMap 是一个为众多服务和应用提供支持的关键开放数据项目。 该应用使用地图视图，用标记指示不完整的数据；用户在现场回答简单问题，即可直接以自己的名义更新地图，无需使用其他编辑器。

hackernews · kls0e · Jul 7, 12:38 · [社区讨论](https://news.ycombinator.com/item?id=48816883)

**背景**: OpenStreetMap（OSM）是一个协作项目，旨在创建免费可编辑的世界地图。传统编辑需要了解标签方案，这可能令人望而生畏。StreetComplete 通过将贡献分解为简单任务来游戏化这一过程，类似于 Kort 或 Every Door 等其他游戏化的 OSM 工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/StreetComplete">StreetComplete - Wikipedia</a></li>
<li><a href="https://streetcomplete.app/">StreetComplete</a></li>
<li><a href="https://wiki.openstreetmap.org/wiki/Gamification?ref=warp-news">Gamification - OpenStreetMap Wiki</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍称赞 StreetComplete 的初学者友好界面和有趣的方式，但也有人指出其局限性，例如无法添加道路或小径。还有讨论提到谷歌可能使用 OSM 数据而不回报，以及建议使用 Every Door 等替代应用。

**标签**: `#OpenStreetMap`, `#crowdsourcing`, `#mobile app`, `#open data`, `#mapping`

---

<a id="item-10"></a>
## [Davit：苹果容器的原生 macOS 界面](https://davit.app/) ⭐️ 7.0/10

Davit 是一个面向 Apple Containers 的原生 macOS 前端，使用 Swift 和 ContainerAPIClient 库构建，提供了基于 Docker 工具的轻量级替代方案。 该应用为管理 Apple Containers 提供了一个原生、轻量且经过签名/公证的图形界面，填补了偏好原生工具而非基于 Electron 的替代方案（如 Orbstack）的 macOS 开发者的需求。 该应用仅 17 MB，直接使用 ContainerAPIClient 库，在 3 天内通过 28 次提交完成，所有提交均由 Claude Fable 5 共同编写。首次启动时会自动下载必要的容器运行时。

hackernews · xinit · Jul 7, 18:44 · [社区讨论](https://news.ycombinator.com/item?id=48821848)

**背景**: Apple Containers 是苹果公司于 2025 年推出的开源工具，用于在 macOS 上运行 Linux 容器，采用每容器一个虚拟机的架构以提高安全性。ContainerAPIClient 是一个 Swift 库，提供类型化的 API 用于容器操作，无需调用命令行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apple_container">Apple container</a></li>
<li><a href="https://opensource.apple.com/projects/container/">Apple Open Source</a></li>
<li><a href="https://github.com/tonycoco/ContainerApp/blob/main/README.md">ContainerApp/README.md at main - GitHub</a></li>

</ul>
</details>

**社区讨论**: 社区反响积极，用户称赞该应用的原生体验、小巧体积和流畅的首次运行体验。一些用户将其与 Orbstack 进行有利比较，并建议添加入门教程。

**标签**: `#macOS`, `#containers`, `#Swift`, `#developer-tools`, `#open-source`

---

<a id="item-11"></a>
## [欧盟强制要求所有新车安装驾驶员监控摄像头](https://allaboutcookies.org/eu-mandatory-distracted-driver-system) ⭐️ 7.0/10

欧盟《通用安全法规》现已要求所有在欧盟销售的新车必须配备驾驶员监控系统（DMS），该系统通过车内摄像头检测驾驶员分心和疲劳状态。 该法规旨在减少因驾驶员注意力不集中导致的事故，每年可能挽救数千人的生命，但也引发了驾驶员和汽车制造商对隐私和用户体验的严重担忧。 该系统使用红外摄像头和人工智能追踪眼球运动、头部姿态和眨眼模式，在检测到分心时发出警报；它必须与其他高级驾驶辅助系统（ADAS）集成，以便在驾驶员未响应时进行干预。

hackernews · nickslaughter02 · Jul 7, 20:50 · [社区讨论](https://news.ycombinator.com/item?id=48823557)

**背景**: 驾驶员监控系统（DMS）利用车内摄像头和红外传感器实时监控驾驶员的注意力状态。欧盟于 2019 年通过的《通用安全法规》（GSR）分阶段引入了多项安全技术，其中 DMS 自 2024 年 7 月起对所有新车型强制实施，自 2026 年 7 月起对所有新车强制实施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Driver_Monitoring_System">Driver monitoring system - Wikipedia</a></li>
<li><a href="https://smarteye.se/blog/the-general-safety-regulations-gsr-and-driver-monitoring-systems-dms/">How Driver Monitoring Systems (DMS) Are Being Made Mandatory ...</a></li>
<li><a href="https://smarteye.se/news/advanced-driver-distraction-warning-systems-now-mandatory-across-all-new-eu-vehicles/">Advanced Driver Distraction Warning Systems Now Mandatory ...</a></li>

</ul>
</details>

**社区讨论**: 社区评论呈现分歧：一些用户称赞系统在捕捉真实分心行为上的准确性，而另一些用户则批评现代汽车的整体用户体验，认为恼人的警报、侵入式的车道辅助以及设计不佳的界面反而造成了新的分心。

**标签**: `#automotive`, `#privacy`, `#regulation`, `#UX`, `#safety`

---

<a id="item-12"></a>
## [Rowboat：开源的本地优先 Claude Desktop 替代品](https://github.com/rowboatlabs/rowboat) ⭐️ 7.0/10

Rowboat 是一个开源、本地优先的工作应用，集成了邮件、会议记录、浏览器、并行编码和笔记功能到可定制的工作区中，所有功能均由支持任何 LLM（包括本地模型）的 AI 助手驱动。 这很重要，因为它提供了一个注重隐私、完全可定制的 Claude Desktop 替代方案，使用户能够在单个本地优先环境中构建自己的工作区并编排多个 AI 代理，可能减少对云端 AI 工具的依赖。 Rowboat 将所有数据以纯 Markdown 文件形式存储在用户机器上，采用 Apache-2.0 许可证，支持任何 LLM，包括通过 Ollama 或 LM Studio 运行的本地模型。它还包含一个 Agent Client Protocol (ACP)客户端，用于编排多个编码代理。

hackernews · segmenta · Jul 7, 16:10 · [社区讨论](https://news.ycombinator.com/item?id=48819808)

**背景**: Claude Desktop 是 Anthropic 的桌面应用，将 Claude 的 AI 能力带到用户电脑上，实现无缝工作流集成。本地优先软件优先将数据存储在用户设备上，增强隐私和离线功能。Rowboat 在这些概念基础上构建，提供了一个开源、可扩展的平台，用户可以在其中创建自定义工作区并集成各种 AI 工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://lofi.so/">Local-First Software</a></li>
<li><a href="https://blog.openreplay.com/beginners-guide-local-first-software-development/">A Beginner's Guide to Local-First Software Development</a></li>
<li><a href="https://claude.com/download">Download Claude | Claude by Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了对多用户支持以进行结对提示的兴趣，希望有插件式架构来自定义上下文格式，以及担心 AI 工具生成过多内容导致信息过载。一些用户还询问从现有 Claude Code 设置的迁移工作流。

**标签**: `#open-source`, `#AI tools`, `#local-first`, `#developer tools`, `#Claude alternative`

---

<a id="item-13"></a>
## [TeraWulf 因与 Anthropic 签订 190 亿美元 AI 数据中心租约而飙升](https://www.coindesk.com/markets/2026/07/06/bitcoin-miner-terawulf-soars-on-a-usd19-billion-ai-data-center-lease-with-anthropic) ⭐️ 7.0/10

比特币矿商 TeraWulf 宣布与 AI 公司 Anthropic（Claude 的开发商）签订价值 190 亿美元的数据中心租约后，股价飙升。这笔交易标志着加密货币挖矿与 AI 基础设施的重大交叉。 这笔交易凸显了比特币挖矿与 AI 基础设施日益融合的趋势，矿商将其能源和数据中心资产重新用于高性能计算。这可能为其他加密矿商转向 AI 服务树立先例。 该租约总价值 190 亿美元，但具体期限和容量细节未披露。TeraWulf 在纽约和宾夕法尼亚运营挖矿设施，并已开始扩展至 AI 和 HPC 托管业务。

rss · CoinDesk · Jul 6, 14:12

**背景**: 像 TeraWulf 这样的比特币矿商拥有大规模数据中心和廉价电力，使其成为需要大量计算资源的 AI 公司的理想合作伙伴。Anthropic 在 2026 年 5 月估值达 9650 亿美元，是开发 Claude 系列模型的领先 AI 安全公司。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/TeraWulf">TeraWulf - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Anthropic">Anthropic</a></li>
<li><a href="https://www.terawulf.com/">TeraWulf: Leading the Digital Energy Revolution</a></li>

</ul>
</details>

**标签**: `#Bitcoin mining`, `#AI infrastructure`, `#data centers`, `#Anthropic`, `#crypto-AI crossover`

---

<a id="item-14"></a>
## [联合国秘书长警告：'我们不能用 Vibe Coding 来编码人类的未来'](https://decrypt.co/372854/we-cannot-vibe-code-future-of-humanity-un-chief-warns-ai) ⭐️ 7.0/10

联合国秘书长安东尼奥·古特雷斯在一次人工智能峰会上借用“Vibe Coding”梗，呼吁全球 AI 监管并禁止致命自主武器。 这标志着一位全球主要领导人利用科技梗来推动具有约束力的 AI 治理，可能加速关于自主武器的国际条约。 古特雷斯特别呼吁对“杀手机器人”进行具有法律约束力的禁令——这些自主武器可以在没有人类判断的情况下做出生死决定。

rss · Decrypt · Jul 6, 19:58

**背景**: Vibe Coding 是由 OpenAI 联合创始人 Andrej Karpathy 创造的一个术语，描述依赖 AI 的编程方式，开发者使用 Cursor AI 等 LLM 助手生成代码。联合国自 2023 年以来一直在推动对致命自主武器系统（LAWS）的监管，许多国家和民间社会团体主张预防性禁令。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://knowyourmeme.com/memes/vibe-coding">Vibe Coding - Know Your Meme</a></li>
<li><a href="https://fiia.fi/wp-content/uploads/2026/05/BP437_Lethal-autonomous-weapon-systems.pdf">Lethal autonomous weapon systems: Regulatory momentum or ...</a></li>

</ul>
</details>

**标签**: `#AI governance`, `#autonomous weapons`, `#UN`, `#regulation`, `#ethics`

---

<a id="item-15"></a>
## [美国战略比特币储备解读](https://www.theblock.co/learn/407371/what-is-the-u-s-strategic-bitcoin-reserve?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

2025 年 3 月，美国政府通过第 14233 号行政令建立了战略比特币储备，将比特币指定为不可出售的长期储备资产。 这标志着主要政府首次正式将比特币作为战略储备资产，可能影响其他国家，并使加密货币作为主权财富工具合法化。 该储备将持有美国政府拥有的几乎所有比特币，各机构必须在 30 天内转移其持有的 BTC。该行政令将比特币的角色比作黄金在国家储备中的作用。

rss · The Block · Jul 7, 05:27

**背景**: 比特币是一种去中心化的数字货币，总供应量上限为 2100 万枚。历史上各国政府持有黄金和法定货币作为储备；该行政令将比特币视为类似资产，反映了其作为价值储存手段的日益接受度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.govinfo.gov/content/pkg/DCPD-202500335/pdf/DCPD-202500335.pdf">Executive Order 14233—Establishment of the Strategic Bitcoin ...</a></li>
<li><a href="https://www.whitehouse.gov/presidential-actions/2025/03/establishment-of-the-strategic-bitcoin-reserve-and-united-states-digital-asset-stockpile/">Establishment of the Strategic Bitcoin Reserve and United ...</a></li>
<li><a href="https://www.federalregister.gov/documents/2025/03/11/2025-03992/establishment-of-the-strategic-bitcoin-reserve-and-united-states-digital-asset-stockpile">Establishment of the Strategic Bitcoin Reserve and United ...</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#Cryptocurrency`, `#Government Policy`, `#Strategic Reserve`

---

<a id="item-16"></a>
## [30papers.com：以初学者友好格式呈现 Ilya 的机器学习论文](https://30papers.com/) ⭐️ 6.0/10

一个名为 30papers.com 的副项目以初学者友好的格式呈现了 Ilya Sutskever 精选的 30 篇机器学习重要论文，提供了简化解释和交互功能。 该项目降低了初学者理解机器学习基础论文的门槛，可能加速 AI 领域的学习，但论文列表的真实性受到质疑。 该网站包含动画和背景的开关以改善可用性，作者是一名计算机科学大一学生，将其作为副项目构建。论文列表的来源未经核实，与 Ilya Sutskever 没有直接联系。

hackernews · notmcrowley · Jul 7, 15:58 · [社区讨论](https://news.ycombinator.com/item?id=48819608)

**背景**: Ilya Sutskever 是 OpenAI 的联合创始人兼前首席科学家，据报道他曾与 John Carmack 分享了一份 30 篇机器学习重要论文的清单，并表示学习这些论文能覆盖现代 AI 中 90%的关键内容。30papers.com 旨在通过提供简化摘要和交互元素，使这些论文对初学者更易理解。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://rottenpanda.com/science-nature/30papers-com-ilya-s-30-essential-ml-papers-in-a-beginner-friendly-format/">30Papers.com – Ilya's 30 Essential ML Papers, In A Beginner ...</a></li>
<li><a href="https://aman.ai/primers/ai/top-30-papers/">Aman's AI Journal • Primers • Ilya Sutskever's Top 30</a></li>
<li><a href="https://nileshsarkar-ai.github.io/pages/sutskevers-list.html">Sutskever's List: Essential AI Research Papers | Nilesh Sarkar</a></li>

</ul>
</details>

**社区讨论**: 社区评论对论文列表的真实性表示怀疑，指出缺乏来源验证且与 Ilya 无关联。一些用户认可该项目的努力，但建议更好的组织方式，如逻辑阅读顺序。作者承认可用性问题，并已添加动画开关。

**标签**: `#machine learning`, `#research papers`, `#education`, `#curation`

---

<a id="item-17"></a>
## [K 和 Q 语言的新闭源运行时](https://lv1.sh/) ⭐️ 6.0/10

一个名为 'l' 的新闭源运行时已发布，用于 k 和 q 数组编程语言，在 lv1.sh 上宣布。该项目被描述为 'vibecoded'，且不是开源的。 该运行时在 niche 但具有影响力的数组语言家族中引入了一个新实现，可能提供性能改进。然而，其闭源性质可能限制采用和社区信任，尤其是在存在 BQN 和 Klong 等开源替代品的领域。 该运行时是闭源的，网站被描述为 'vibecoded'，意味着它快速拼凑而成，没有精致的设计。网站上没有提供与现有运行时（如 kdb+）的基准测试或比较。

hackernews · skruger · Jul 7, 18:08 · [社区讨论](https://news.ycombinator.com/item?id=48821378)

**背景**: K 和 Q 是 Arthur Whitney 开发的专有数组处理语言，主要用于金融数据分析，搭配 kdb+。APL 和 J 等数组语言以简洁、富有表现力的语法和高效的数组处理而闻名。社区中有多个开源实现，如 Klong 和 BQN。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/K_programming_language">K programming language</a></li>
<li><a href="https://en.wikipedia.org/wiki/Q_(programming_language_from_Kx_Systems)">Q (programming language from Kx Systems) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Array_programming">Array programming - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论褒贬不一：一些人认为尽管是闭源和 'vibecoded' 性质，但设计空间有趣；而另一些人批评缺乏开放性和与现有运行时的比较。少数用户提到了 KlongPy 和 BQN 等替代开源项目。

**标签**: `#k`, `#array languages`, `#runtime`, `#APL`, `#programming languages`

---

<a id="item-18"></a>
## [SEC 本月拟提出加密规则以简化初创企业融资](https://www.coindesk.com/policy/2026/07/07/u-s-sec-to-propose-crypto-rule-as-soon-as-this-month-to-ease-startups-fundraising) ⭐️ 6.0/10

美国证券交易委员会（SEC）计划最早于 2026 年 7 月提出一项名为“Regulation Crypto”的加密专项规则，根据其最新更新的监管议程。 该规则可能为加密初创企业提供更清晰的法律框架以进行融资，减少监管不确定性，并可能刺激区块链和数字资产领域的创新。 根据 SEC 声明和监管议程，拟议规则预计将包括代币发行的安全港条款，并涉及数字资产的经纪商和交易所监管。

rss · CoinDesk · Jul 7, 16:08

**背景**: SEC 历史上将现有证券法适用于加密资产，导致执法行动和初创企业的不确定性。此次新规则制定是 SEC 在主席 Paul Atkins 领导下 2026 年议程的一部分，旨在为加密领域创建量身定制的监管框架。此前委员 Hester Peirce 曾提出安全港概念，允许代币项目在无需立即注册的情况下实现去中心化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/policy/2026/07/07/u-s-sec-to-propose-crypto-rule-as-soon-as-this-month-to-ease-startups-fundraising">U.S. SEC to propose crypto rule as soon as this ... - CoinDesk</a></li>
<li><a href="https://www.sec.gov/newsroom/speeches-statements/atkins-remarks-regulation-crypto-assets-031726">Regulation Crypto Assets: A Token Safe Harbor - SEC.gov</a></li>

</ul>
</details>

**标签**: `#crypto`, `#regulation`, `#SEC`, `#startups`

---

<a id="item-19"></a>
## [Visa 数据显示 USDC 在稳定币交易量上超越 Tether](https://www.coindesk.com/business/2026/07/06/circle-s-usdc-is-leaving-tether-behind-in-the-stablecoin-volume-race) ⭐️ 6.0/10

根据 Visa 的链上分析仪表板，Circle 的 USDC 稳定币在月度交易量上首次超越 Tether 的 USDT，标志着稳定币使用格局的转变。 这一转变表明市场对像 USDC 这样受监管的稳定币的偏好日益增长，而 Tether 一直面临监管审查，这可能影响更广泛的加密货币市场和支付基础设施。 Visa 仪表板的数据追踪了多条区块链上法币支持的稳定币的链上交易量，这一里程碑发生在 2026 年 6 月，USDC 的交易量首次超过 USDT。

rss · CoinDesk · Jul 6, 16:00

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元等法定货币挂钩。USDC 由 Circle 发行，并完全由储备支持，而 Tether（USDT）是市值最大的稳定币，但曾因其储备问题面临争议。Visa 的链上分析仪表板提供了稳定币交易量的透明度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://visaonchainanalytics.com/transactions">Transactions | Visa Onchain Analytics Dashboard</a></li>
<li><a href="https://en.wikipedia.org/wiki/USDC_(cryptocurrency)">USDC (cryptocurrency) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tether_(cryptocurrency)">Tether (cryptocurrency) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#stablecoins`, `#cryptocurrency`, `#finance`, `#market data`

---

<a id="item-20"></a>
## [研究警告：大学未跟上 AI 职场变革](https://decrypt.co/372957/ai-changing-workplace-universities-not-keeping-up-study) ⭐️ 6.0/10

曼彻斯特大学的一位研究员警告，大学未能适应 AI 对职场的影响，呼吁将重点从作弊转向为毕业生应对自动化做好准备。 这很重要，因为进入 AI 驱动职场的毕业生可能缺乏关键技能，可能扩大教育与行业需求之间的差距。 该研究强调，应超越对 AI 辅助作弊的担忧，主动将 AI 素养和自动化准备纳入课程。

rss · Decrypt · Jul 7, 20:46

**背景**: 生成式 AI 等 AI 技术正通过自动化任务和创造新角色迅速改变职场。大学传统上关注学术诚信，但现在面临更新课程以反映实际 AI 应用的压力。

**标签**: `#AI`, `#education`, `#workplace`, `#automation`

---

<a id="item-21"></a>
## [肯尼亚监管机构寻求区块链工具追踪加密犯罪](https://decrypt.co/372932/kenyas-markets-regulator-seeks-blockchain-tool-to-track-crypto-crime) ⭐️ 6.0/10

肯尼亚资本市场管理局计划部署一款区块链监控工具，根据该国新加密法律，在 20 多个区块链上追踪欺诈、洗钱和逃避制裁行为。 此举标志着非洲新兴加密市场采取主动监管方式，可能为其他非洲国家树立先例，并增强肯尼亚对合规加密企业的吸引力。 该工具将监控 20 多个区块链上的非法活动，与 2025 年 10 月签署成为法律的肯尼亚《虚拟资产服务提供商法案》保持一致。

rss · Decrypt · Jul 7, 17:29

**背景**: 肯尼亚最近通过了首部全面的加密法规《VASP 法案》，旨在保护消费者并制定反洗钱规则。像 Chainalysis 这样的区块链监控工具常被政府用于分析链上交易并识别可疑活动。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.chainalysis.com/">The Blockchain Data Platform - Chainalysis</a></li>
<li><a href="https://tech-ish.com/2025/10/15/kenya-crypto-regulation-vasp-bill-law-2025/">Kenya's crypto scene now regulated after President Ruto signs ...</a></li>
<li><a href="https://biznakenya.com/kenya-adopts-landmark-crypto-law/">Kenya adopts landmark crypto law to attract investments and ...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#crypto regulation`, `#Kenya`, `#AML`

---

<a id="item-22"></a>
## [英国警告：无安全保障将导致“AI 广岛”](https://decrypt.co/372855/uk-foreign-secretary-warns-ai-hiroshima) ⭐️ 6.0/10

英国外交大臣伊薇特·库珀警告称，如果没有国际安全保障，前沿 AI 系统可能导致堪比广岛的灾难性后果，敦促政策制定者在这些系统改变战争、犯罪和社会之前采取行动。 来自主要政府的高层警告表明 AI 安全治理的紧迫性日益增加，可能加速关于前沿 AI 监管的国际协议，并影响全球政策辩论。 库珀的言论正值英国主导的 AI 安全努力持续推进之际，包括 2023 年布莱切利峰会和《国际 AI 安全报告》，该报告将前沿 AI 风险分为恶意使用、故障和系统性风险三类。

rss · Decrypt · Jul 6, 21:01

**背景**: 前沿 AI 指代最先进的通用 AI 模型，其能力达到或超越当今领先系统（如 GPT-4 和 Claude）。这些模型因可能被滥用、失控及造成社会危害而带来独特的安全风险，从而引发了国际监管呼声。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.gov.uk/government/publications/frontier-ai-capabilities-and-risks-discussion-paper/frontier-ai-capabilities-and-risks-discussion-paper">Frontier AI: capabilities and risks – discussion paper - GOV.UK What Are Frontier AI Models and How They Work - NVIDIA What Is Frontier AI? - Palo Alto Networks Frontier AI — Definition & Implications for AI Safety AI Glossary: What Is Frontier AI? Definition & Meaning | SEOFAI Frontier Models Explained: What Defines the Cutting Edge of AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_safety">AI safety - Wikipedia</a></li>
<li><a href="https://internationalaisafetyreport.org/publication/international-ai-safety-report-2025">International AI Safety Report 2025</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#policy`, `#risk`

---

<a id="item-23"></a>
## [Coinbase AI 在比赛前虚构世界杯结果](https://decrypt.co/372824/coinbase-ai-hallucinated-world-cup-result-before-match) ⭐️ 6.0/10

Coinbase 的 AI 系统在挪威对巴西的世界杯比赛开赛前生成了虚假警报，错误地报告了比赛结果，促使公司更新其系统。 此事件凸显了 AI 幻觉在金融应用中的现实风险，不准确的信息可能误导用户并造成潜在的经济损失。 该 AI 生成的警报通过 Coinbase 的预测市场推送，公司正在调查此错误以改进 AI 安全措施。

rss · Decrypt · Jul 6, 18:49

**背景**: AI 幻觉是指模型生成不基于输入或训练数据的错误或虚构输出。这种现象在大型语言模型中很常见，可能导致不可靠的结果，在交易或新闻等对准确性要求高的场景中尤其成问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)">Hallucination (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://blockonomi.com/coinbase-investigates-ai-error-after-false-world-cup-match-alert-sparks-backlash/">Coinbase Investigates AI Error After False World Cup Match ...</a></li>
<li><a href="https://oecd.ai/en/incidents/2026-07-06-d1c3">Coinbase AI System Sends False World Cup Result Notification</a></li>

</ul>
</details>

**标签**: `#AI`, `#hallucination`, `#machine learning`, `#reliability`

---

<a id="item-24"></a>
## [Strike 推出“抗波动”比特币贷款](https://www.theblock.co/post/407511/jack-maller-strike-launches-volatility-proof-bitcoin-loans-protect-against-liquidation?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

由 Jack Mallers 创立的 Strike 推出了“抗波动”比特币抵押贷款，只要借款人按时还款，就不会触发追加保证金或价格驱动的清算。 这一创新可能吸引更多比特币持有者将资产用作抵押品，而无需担心市场下跌时被强制清算，从而可能扩大加密货币借贷市场。 这些贷款利率较高，期限为六个月；但如果借款人错过利息或到期还款，且在宽限期内未能支付，仍可能发生部分清算。

rss · The Block · Jul 7, 20:48

**背景**: 传统的加密抵押贷款通常要求超额抵押，并在抵押品价值下跌时触发追加保证金或清算。“抗波动”贷款旨在为按时还款的借款人消除这一风险，将风险转移给贷方，以换取更高的费用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cointelegraph.com/news/strike-launches-volatility-proof-bitcoin-loans-amid-bear-market-but-at-what-cost">Strike Launches Volatility-Proof Bitcoin-Backed Loans</a></li>
<li><a href="https://strike.me/en/faq/what-are-volatility-proof-loans/">What are volatility-proof loans? - strike.me</a></li>
<li><a href="https://grafa.com/en/news/crypto/strike-launches-volatility-proof-bitcoin-loans">Strike launches volatility-proof Bitcoin loans | Grafa</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#DeFi`, `#crypto lending`, `#volatility`

---

<a id="item-25"></a>
## [Zcash 接近防伪数学证明，ZEC 上涨 12%](https://www.theblock.co/post/407495/zec-price-jumps-zcash-nears-mathematical-proof-hidden-counterfeit-bugs?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Zcash 的 ZEC 代币上涨 12%，此前 Project Tachyon 宣布在即将推出的 Ironwood 屏蔽池中，针对隐藏的伪造漏洞的数学证明取得进展。 这一进展意义重大，因为在 Orchard 屏蔽池中发现严重伪造漏洞后，它旨在恢复对 Zcash 供应验证的信任，可能增强加密货币的安全性和用户信心。 Project Tachyon 正在使用携带证明的数据和遗忘同步来扩展 Zcash 的屏蔽交易，同时保护隐私。Ironwood 池将使用 Orchard 协议，但通过形式化验证和额外审计来修复之前的漏洞。

rss · The Block · Jul 7, 18:12

**背景**: Zcash 是一种注重隐私的加密货币，使用零知识证明来隐藏交易细节。2026 年，其 Orchard 屏蔽池中发现了一个严重的伪造漏洞，导致紧急修补并提出了名为 Ironwood 的新池。Project Tachyon 是一项旨在改进 Zcash 密码学和可扩展性的研究项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/tachyon-zcash/">Project Tachyon - GitHub</a></li>
<li><a href="https://seanbowe.com/blog/tachyon-scaling-zcash-oblivious-synchronization/">Tachyon: Scaling Zcash with Oblivious Synchronization</a></li>
<li><a href="https://tachyon.z.cash/overview/">Overview — Project Tachyon</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#Zcash`, `#security`, `#blockchain`

---

<a id="item-26"></a>
## [Galaxy 将比特币矿场转为 CoreWeave 的 AI 数据中心](https://www.theblock.co/post/407396/galaxy-delivers-133-mw-of-critical-it-load-to-coreweave-as-helios-bitcoin-mine-turns-ai-hub?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Galaxy Digital 完成了将其位于西德克萨斯州的 Helios 比特币矿场改造为 AI 数据中心的第一阶段，向 CoreWeave 交付了 133 兆瓦的关键 IT 负载。 这标志着将高能耗的比特币挖矿基础设施重新用于 AI 工作负载的重要趋势，AI 需要巨大的计算能力和可靠的能源。它展示了如何将现有的电力和冷却资产重新用于日益增长的 AI 行业。 Helios 园区现在向 CoreWeave 提供 133 兆瓦的 IT 容量，CoreWeave 是一家专注于 AI 基础设施的 GPU 云提供商。此次改造可能利用了原本为挖矿建造的现有变电站和冷却系统。

rss · The Block · Jul 7, 09:45

**背景**: 比特币挖矿和 AI 训练都需要大量电力并产生大量热量。矿场通常能获得廉价电力并拥有强大的冷却基础设施，使其成为改造为 AI 数据中心的理想候选。CoreWeave 是为 AI 工作负载提供 GPU 计算的领先云提供商。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://coinalertnews.com/news/2026/07/07/galaxy-helio-ai-coreweave">Galaxy Digital Completes Helios Conversion, Former Bitcoin ...</a></li>
<li><a href="https://capwolf.com/galaxy-transforms-helios-bitcoin-mine-into-major-ai-data-center-hub/">Galaxy Transforms Helios Bitcoin Mine Into Major AI Data ...</a></li>
<li><a href="https://blockonomi.com/galaxys-helios-site-starts-ai-lease-after-bitcoin-mining-exit/">Galaxy’s Helios Site Starts AI Lease After Bitcoin Mining ...</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#data centers`, `#bitcoin mining`, `#energy`

---

<a id="item-27"></a>
## [交易员起诉 Polymarket 关于比特币出售市场的裁决](https://www.theblock.co/post/407368/two-traders-sue-polymarket-strategy-bitcoin-sale?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

两名交易员对 Polymarket 提起诉讼，指控该平台错误地将关于 Strategy 出售比特币的市场裁决为“否”，尽管 SEC 文件显示 Strategy 在 5 月 26 日至 31 日期间出售了 32 枚 BTC。 这起诉讼挑战了 Polymarket 去中心化裁决机制的完整性，可能为预测市场如何处理有争议的结果树立法律先例，影响用户信任和监管审查。 Polymarket 使用 UMA 乐观预言机进行裁决，任何人都可以提出结果，其他人可以在 2 小时的挑战期内提出异议。原告声称平台忽略了 SEC 文件证据。

rss · The Block · Jul 7, 08:34

**背景**: 像 Polymarket 这样的预测市场允许用户对事件结果下注，裁决决定哪些代币获得赔付。UMA 乐观预言机依赖基于保证金的争议系统；如果在 2 小时内无人对提议的结果提出异议，则结果成为最终结果。Strategy（前身为 MicroStrategy）是一家主要的公司比特币持有者，其在 2026 年 5 月 30 日的 SEC 文件中披露了自 2022 年以来的首次比特币出售。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.polymarket.com/concepts/resolution">Resolution - Polymarket Documentation</a></li>
<li><a href="https://www.sec.gov/Archives/edgar/data/1050446/000119312526249768/mstr-20260530.htm">8-K - SEC.gov</a></li>
<li><a href="https://coinpedia.org/news/breaking-strategy-sells-32-bitcoin-for-first-time-since-2022/">Breaking: Strategy Sells 32 Bitcoin for First Time Since 2022</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#legal`, `#cryptocurrency`, `#Polymarket`

---