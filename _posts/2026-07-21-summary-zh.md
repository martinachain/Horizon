---
layout: default
title: "Horizon Summary: 2026-07-21 (ZH)"
date: 2026-07-21
lang: zh
---

> From 64 items, 18 important content pieces were selected

---

1. [黑客清空罗马尼亚全部土地登记数据库](#item-1) ⭐️ 9.0/10
2. [Cursor 的智能体集群达到每秒 1000 次提交，构建全新版本控制系统](#item-2) ⭐️ 9.0/10
3. [中国开源 AI 模型威胁西方定价策略](#item-3) ⭐️ 8.0/10
4. [AI 在生成反例方面超越人类](#item-4) ⭐️ 8.0/10
5. [Zcash 推出目标 Visa 级隐私的节点，每秒 5 万笔交易](#item-5) ⭐️ 8.0/10
6. [Jellyfin 创始人因倦怠离职](#item-6) ⭐️ 7.0/10
7. [ACLU 报告指控 Flock Safety 多次欺骗](#item-7) ⭐️ 7.0/10
8. [中国开放权重 AI 战略取得战略优势](#item-8) ⭐️ 7.0/10
9. [LED 灯可设计以保护夜空](#item-9) ⭐️ 7.0/10
10. [Allbridge 因 165 万美元闪电贷攻击暂停运营](#item-10) ⭐️ 7.0/10
11. [Jelly UI：为原生 HTML 表单控件添加软体物理效果](#item-11) ⭐️ 6.0/10
12. [高斯泼溅技术打造旧金山恩典大教堂沉浸式 3D 游览](#item-12) ⭐️ 6.0/10
13. [韩国央行将于九月启动实时 CBDC 交易](#item-13) ⭐️ 6.0/10
14. [比特币量子恢复工具问世，但中本聪的币仍无法恢复](#item-14) ⭐️ 6.0/10
15. [俄罗斯加密货币法即将通过，规避制裁](#item-15) ⭐️ 6.0/10
16. [Cardano 触发首次社区投票硬分叉](#item-16) ⭐️ 6.0/10
17. [NEAR 联合创始人警告 AI 黑客攻击速度超过代码审查](#item-17) ⭐️ 6.0/10
18. [Hut 8 与 IREN 签署数十亿美元 AI 数据中心租约](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [黑客清空罗马尼亚全部土地登记数据库](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 9.0/10

一名黑客在勒索未遂后删除了罗马尼亚的全部土地登记数据库，导致全国房地产市场瘫痪，所有房产交易暂停。 此事件威胁到罗马尼亚财产所有权的法律基础，如果备份失效，可能导致土地买卖、抵押和继承陷入混乱。它凸显了关键政府基础设施面对网络攻击的脆弱性。 黑客被确认为来自阿尔及利亚的 Zakaria Mahdjoub，声称已删除备份，但据报道罗马尼亚当局拥有离线副本。该机构正在特种电信服务局的协助下将系统迁移至政府云。

hackernews · speckx · Jul 20, 13:28 · [社区讨论](https://news.ycombinator.com/item?id=48978605)

**背景**: 罗马尼亚土地登记局（ANCPI）是记录财产所有权、边界和法律权利的国家数据库。没有它，公证人无法认证销售或登记抵押，实际上冻结了房地产市场。离线备份独立于主网络存储，以防范勒索软件等攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cybernews.com/security/hacker-deletes-romanian-land-registry-database/">Hacker deletes country’s entire land registry database ... | Cybernews</a></li>
<li><a href="https://www.newsdirectory3.com/romania-land-registry-paralysed-by-major-cyberattack/">Romania Land Registry Paralysed by Major... - News Directory 3</a></li>

</ul>
</details>

**社区讨论**: 评论者对政府 IT 合同中的腐败表示担忧，认为关系户忽视了安全。有人注意到黑客的阿尔及利亚国籍及与罗马尼亚的引渡条约，而其他人则称赞离线备份的存在是关键的保障措施。

**标签**: `#cybersecurity`, `#data breach`, `#critical infrastructure`, `#ransomware`, `#Romania`

---

<a id="item-2"></a>
## [Cursor 的智能体集群达到每秒 1000 次提交，构建全新版本控制系统](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 9.0/10

Cursor 的博客报告称，其新的智能体集群系统达到了每秒 1000 次提交的峰值速率，相比之前每小时 1000 次提交有了巨大提升。为了支持这一吞吐量，他们从头构建了一个自定义版本控制系统（VCS）。 这一实验展示了大规模并行 AI 智能体协作的潜力，推动了软件开发自动化的边界。同时，它也引发了关于 LLM 训练数据污染的重要问题，因为该集群仅凭文档就用 Rust 从头重建了 SQLite。 新的 VCS 不仅是为了吞吐量而构建，还用于使冲突可见并实现协调机制。该集群的任务是仅凭文档用 Rust 从头构建 SQLite，这是之前的集群难以完成的任务。

hackernews · jlaneve · Jul 20, 18:06 · [社区讨论](https://news.ycombinator.com/item?id=48982535)

**背景**: 智能体集群是多智能体系统，其中多个 AI 智能体协作完成复杂任务。像 Git 这样的版本控制系统可以跟踪代码变更，但传统的 VCS 无法处理大型智能体集群产生的极高提交速率。LLM 训练数据污染是指测试数据出现在训练数据中，可能虚增性能指标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/lyy1994/awesome-data-contamination">GitHub - lyy1994/awesome-data-contamination: The Paper List on Data Contamination for Large Language Models Evaluation. · GitHub</a></li>
<li><a href="https://www.holisticai.com/blog/overview-of-data-contamination">An Overview of Data Contamination: The Causes, Risks, Signs, and Defenses</a></li>

</ul>
</details>

**社区讨论**: 评论者对这一实验的未来意义表示兴奋，有人指出这就像“瞥见未来”，类似于 2023 年早期的编码智能体。然而，也有几位评论者提出了对 LLM 记忆化的担忧，质疑模型是否在 SQLite 的源代码上训练过，从而使这一成就显得不那么令人印象深刻。

**标签**: `#agent swarms`, `#LLM`, `#version control`, `#AI engineering`, `#software development`

---

<a id="item-3"></a>
## [中国开源 AI 模型威胁西方定价策略](https://stratechery.com/2026/whos-afraid-of-chinese-models/) ⭐️ 8.0/10

中国 AI 实验室发布高质量开源模型，削弱了 Anthropic 和 OpenAI 等西方实验室的 API 高价策略，威胁其数十亿美元的估值。 这可能迫使西方前沿实验室降价或转向功能竞争，重塑 AI 行业的经济格局，并可能削弱美国 AI 公司的主导地位。 Anthropic 估值 1.2 万亿美元，OpenAI 目标 8500 亿美元，其估值基于 API 高价策略；而中国开源模型免费提供，引发价格战。

hackernews · mfiguiere · Jul 20, 11:05 · [社区讨论](https://news.ycombinator.com/item?id=48977128)

**背景**: 开源 AI 模型可公开获取、自由使用、修改和分发。DeepSeek 等中国实验室发布了与西方模型相竞争的开源模型，引发了对地缘政治影响和数据安全的担忧。

**社区讨论**: 评论者意见分歧：一些人担心中国模型是宣传和数据窃取的木马，而另一些人指出编码助手之间的切换成本低，并认为开源竞争对用户有利。

**标签**: `#AI`, `#Chinese AI`, `#Open Source`, `#Valuation`, `#Geopolitics`

---

<a id="item-4"></a>
## [AI 在生成反例方面超越人类](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 8.0/10

人工智能系统现在能够生成数学猜想的反例，可能重塑数学家的研究方式，并通过早期证伪错误假设来节省时间。 这一进展可能通过快速排除错误猜想，让数学家专注于有希望的方向，从而极大加速数学研究。同时也引发了关于人类直觉在数学中未来角色的思考。 Xena 项目的博客文章讨论了像 Sol 和 Fable 这样的 AI 模型如何被用于寻找反例，研究生每月支付 200 美元获取访问权限。一个著名的轶事涉及张益唐，他的职业生涯因论文中一个错误的推论而受到影响。

hackernews · artninja1988 · Jul 20, 19:03 · [社区讨论](https://news.ycombinator.com/item?id=48983382)

**背景**: 自动定理证明（ATP）是计算机科学的一个子领域，使用程序自动证明数学定理。反例生成是一项相关任务，AI 系统生成具体例子来证伪猜想。大型语言模型的最新进展使得在 Lean 4 等定理证明器中生成并验证形式化反例成为可能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Automated_theorem_proving">Automated theorem proving</a></li>
<li><a href="https://arxiv.org/abs/2603.19514">[2603.19514] Learning to Disprove: Formal Counterexample Generation with Large Language Models</a></li>
<li><a href="https://www.newscientist.com/article/2278276-an-ai-has-disproved-five-mathematical-conjectures-with-no-human-help/">An AI has disproved five mathematical conjectures with no human help | New Scientist</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍对 AI 生成反例持积极态度，认为这节省了时间，避免了在错误猜想上浪费精力。一些人表达了对以人为中心的数学的怀旧，将其比作约翰·亨利的民间传说。关于张益唐的轶事突显了未检测到的错误在现实世界中的后果。

**标签**: `#AI`, `#mathematics`, `#research methodology`, `#automated theorem proving`

---

<a id="item-5"></a>
## [Zcash 推出目标 Visa 级隐私的节点，每秒 5 万笔交易](https://www.coindesk.com/tech/2026/07/16/inside-zcash-s-new-node-that-targets-visa-scale-privacy-at-50-000-transactions-per-second) ⭐️ 8.0/10

Zcash 宣布推出一种新节点，能够在保持隐私的同时每秒处理 5 万笔交易，旨在与 Visa 级别的吞吐量竞争。 这一里程碑可能显著推动区块链的可扩展性和隐私保护，通过解决现有网络的关键限制，有望推动加密货币的更广泛采用。 该节点利用先进的零知识证明实现高吞吐量而不牺牲隐私，但具体技术细节和发布时间尚未完全披露。

rss · CoinDesk · Jul 19, 05:37

**背景**: Zcash 是一种注重隐私的加密货币，使用零知识证明（zk-SNARK）实现屏蔽交易。可扩展性一直是隐私币面临的挑战，因为隐私功能通常会增加计算开销。Visa 平均每秒处理约 1700 笔交易，因此 5 万 TPS 将远超当前区块链的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zcash.readthedocs.io/en/latest/rtd_pages/zcashd.html">Zcash Full Node and CLI — Zcash Documentation...</a></li>
<li><a href="https://github.com/ZcashFoundation/zebra">GitHub - ZcashFoundation/zebra: Zcash - Financial Privacy in Rust</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-knowledge_proof">Zero-knowledge proof - Wikipedia</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#privacy`, `#scalability`, `#cryptocurrency`, `#Zcash`

---

<a id="item-6"></a>
## [Jellyfin 创始人因倦怠离职](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 7.0/10

开源媒体服务器 Jellyfin 的创始人 Andrew 因严重倦怠而辞去项目领导职务，该消息已在 Jellyfin 论坛上公布。 这一事件凸显了开源社区中持续存在的倦怠问题，并强调了 Jellyfin 作为 Plex 等专有媒体服务器免费替代品的重要性，尤其是在 Plex 最近涨价之后。 Andrew 将严重倦怠和心理健康风险列为离职原因，并表示自己无法再满足该职位的要求。此次交接似乎平稳进行，项目将在新领导下继续发展。

hackernews · swat535 · Jul 20, 23:15 · [社区讨论](https://news.ycombinator.com/item?id=48986091)

**背景**: Jellyfin 是一个免费开源媒体服务器，允许用户托管并将自己的媒体库流式传输到各种设备。它于 2018 年作为 Emby 的分支诞生，并已发展成为 Plex 等专有解决方案的热门替代品，而 Plex 最近将其终身 Plex Pass 价格提高到了 750 美元。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jellyfin">Jellyfin - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员对 Andrew 的贡献表示感谢，并对他的倦怠表示同情，同时也反思了 FLOSS 可持续性的更广泛问题。一些人指出，Jellyfin 很好地满足了他们的需求，尤其是作为 Plex 的替代品。

**标签**: `#open-source`, `#media-server`, `#burnout`, `#FLOSS`, `#community`

---

<a id="item-7"></a>
## [ACLU 报告指控 Flock Safety 多次欺骗](https://www.aclu.org/news/privacy-technology/tracking-alpr-cameras/flock-safety-credibility-lost-as-it-repeatedly-lies-to-city-councils-police-departments-and-public-across-the-country) ⭐️ 7.0/10

ACLU 发布了一份报告，详细说明了车牌识别公司 Flock Safety 如何多次就技术能力和隐私保护措施误导市议会、警察局和公众。 这份报告削弱了 Flock Safety 的可信度，并引发了对在缺乏透明和诚实沟通的情况下部署监控技术的严重担忧，可能影响公众信任和隐私权。 报告指出，Flock Safety 发布了一篇误导性的博客文章，旨在混淆公众并在政府客户中制造虚假的安全感，而不是实事求是地解决数据安全和控制问题。

hackernews · StatsAreFun · Jul 21, 00:33 · [社区讨论](https://news.ycombinator.com/item?id=48986731)

**背景**: Flock Safety 是一家自动车牌识别（ALPR）摄像机制造商，执法部门和社区使用其设备破案。ACLU 和其他隐私倡导者长期以来一直对大规模监控和数据滥用的可能性表示担忧。这份报告增加了对该公司的批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.aclu.org/news/privacy-technology/tracking-alpr-cameras/flock-safety-credibility-lost-as-it-repeatedly-lies-to-city-councils-police-departments-and-public-across-the-country">Flock Safety Credibility Lost as it Repeatedly Lies to City Councils, Police Departments, and Public Across the Country | American Civil Liberties Union</a></li>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.aclu-wy.org/news/flock-safety-credibility-lost-as-it-repeatedly-lies-to-city-councils-police-departments-and-public-across-the-country/">Flock Lied About its ALPR technology. What Else Has It Lied About?</a></li>

</ul>
</details>

**社区讨论**: 新闻评论反映了对 Flock Safety 可信度的怀疑，一位用户指出该公司未努力安装符合公路安全标准的杆柱。另一位评论者怀疑监控国家不会很快消失，而第三位则认为这种行为是庆祝说谎赢家的社会的症状。

**标签**: `#privacy`, `#surveillance`, `#ethics`, `#law enforcement`, `#technology`

---

<a id="item-8"></a>
## [中国开放权重 AI 战略取得战略优势](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 7.0/10

一篇观点文章认为，中国的开放权重 AI 模型正在战胜美国专有模型，并引用历史趋势表明开放和低端解决方案最终会占据主导地位。 这一转变可能重塑全球 AI 格局，使先进 AI 更易获取且成本更低，并挑战美国专有 AI 公司的主导地位。 文章指出 80%的初创公司正在使用中国模型，但一些评论者对此数据表示质疑。开放权重模型并非完全开源，它们允许下载和定制，但可能带有使用限制。

hackernews · benwerd · Jul 20, 14:21 · [社区讨论](https://news.ycombinator.com/item?id=48979269)

**背景**: 开放权重 AI 模型是指核心组件公开发布、允许任何人下载和运行的模型。这与 OpenAI 的 GPT-4 等专有模型形成对比，后者仅能通过 API 访问。中国一直在积极低价发布开放权重模型，旨在从西方公司手中夺取市场份额。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://www.forbes.com/sites/sylvainduranton/2025/07/07/what-leaders-need-to-know-about-open-source-vs-proprietary-models/">What Leaders Need To Know About Open-Source Vs. Proprietary Models</a></li>

</ul>
</details>

**社区讨论**: 评论者意见不一：一些人同意开放权重最终将占据主导地位，而另一些人则质疑“80%初创公司使用中国模型”的说法，并指出企业更看重数据保留而非开放性。一位评论者指出，Meta 的 Llama 作为领先的开放权重模型并未给 Meta 带来成功。

**标签**: `#AI`, `#open-source`, `#China`, `#strategy`, `#LLM`

---

<a id="item-9"></a>
## [LED 灯可设计以保护夜空](https://spectrum.ieee.org/led-light-pollution) ⭐️ 7.0/10

文章讨论了如何通过工程设计 LED 照明来减少光污染，在保持安全性和功能性的同时保护夜空。 这很重要，因为光污染影响天文观测、生态系统和人类健康；更好的 LED 设计为平衡城市需求与环境保护提供了实用途径。 关键细节包括使用遮光灯具、更暖的色温和自适应控制，以在满足照明标准的同时最小化天光和眩光。

hackernews · defrost · Jul 20, 13:07 · [社区讨论](https://news.ycombinator.com/item?id=48978350)

**背景**: 光污染是指过度或方向不当的人造光使夜空变亮，遮蔽星光并干扰野生动物。LED 虽然节能，但如果设计不当会加剧光污染，但合理的工程可以减轻这些影响。

**社区讨论**: 评论者强调了安全与减少照明之间的权衡，一些人指出照明可以威慑犯罪。其他人分享了创新解决方案，如公园中的运动感应灯，并呼吁制定更好的工程标准以减少眩光。

**标签**: `#light pollution`, `#LED lighting`, `#environmental impact`, `#urban planning`, `#astronomy`

---

<a id="item-10"></a>
## [Allbridge 因 165 万美元闪电贷攻击暂停运营](https://www.coindesk.com/business/2026/07/20/cross-chain-protocol-allbridge-halts-after-usd1-65-million-flash-loan-exploit) ⭐️ 7.0/10

跨链协议 Allbridge 在遭受闪电贷攻击后暂停运营，损失约 165 万美元。安全公司 PeckShield 和 CertiK 报告称，攻击者将被盗资金从 Solana 桥接至以太坊。 此事件凸显了跨链桥中持续存在的安全漏洞，而跨链桥是 DeFi 互操作性的关键基础设施。此类攻击削弱了用户信任，并强调了在桥接协议中需要更强大的安全措施。 攻击者利用闪电贷操纵 Allbridge 的 Solana 稳定币池价格，然后盗取资金。该攻击发生于 2026 年 7 月 20 日，协议在检测到攻击后不久即暂停。

rss · CoinDesk · Jul 20, 09:31

**背景**: 闪电贷是一种无需抵押的贷款，必须在同一笔交易中偿还，常被用于 DeFi 攻击中以操纵价格。像 Allbridge 这样的跨链桥允许在不同区块链之间转移代币，但由于其复杂性和庞大的流动性池，已成为黑客的频繁攻击目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://denntech.io/glossary/flash-loan-attack-vectors">Flash Loan Attack Vectors and DeFi Protocol Defences... | DennTech</a></li>
<li><a href="https://medium.com/@footprintofficial/what-are-cross-chain-bridges-and-why-do-they-matter-53815fa2dbea">What are cross - chain bridges and why do they matter? | Medium</a></li>
<li><a href="https://defillama.com/protocol/allbridge">Allbridge TVL, Fees, Revenue & Volume</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#flash loan`, `#blockchain`, `#exploit`

---

<a id="item-11"></a>
## [Jelly UI：为原生 HTML 表单控件添加软体物理效果](https://jelly-ui.com/) ⭐️ 6.0/10

Jelly UI 是一个库，它通过每 8 毫秒运行一次的 requestAnimationFrame 循环，为原生 HTML 表单控件（如按钮和复选框）添加软体物理动画。 该库展示了物理在 UI 中的创造性应用，但也引发了关于性能和可用性的担忧，凸显了视觉愉悦与标准用户体验实践之间的权衡。 该库使用共享动画帧，每步更新所有活动组件，空闲时暂停，并限制增量以避免后台标签页恢复后的大跳跃。然而，它会导致整个文档重绘，在某些系统上造成卡顿。

hackernews · baldvinmar · Jul 20, 17:07 · [社区讨论](https://news.ycombinator.com/item?id=48981620)

**背景**: 软体物理通过弹簧-质量系统模拟可变形物体，常用于游戏和模拟。Jelly UI 将此概念应用于 HTML 表单控件，使其在交互时像果冻一样变形。该库尊重 prefers-reduced-motion 以实现无障碍访问。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/salty-max/jelly">GitHub - salty-max/ jelly : A minimalistic UI components library · GitHub</a></li>
<li><a href="https://worksetuplab.com/accessibility-inclusive-workspaces/jelly-ui-soft-body-physics-for-native-html-form-controls/">Jelly UI : Soft-body Physics For Native HTML Form... - WorkSetupLab</a></li>

</ul>
</details>

**社区讨论**: 社区反馈褒贬不一：一些人觉得有趣并赞赏对减少动效的支持，而另一些人则批评性能问题和不一致的点击行为。一位用户指出它会导致整个文档重绘，另一位用户指出点击并拖拽离开不应被注册为点击。

**标签**: `#UI`, `#animation`, `#web development`, `#physics`

---

<a id="item-12"></a>
## [高斯泼溅技术打造旧金山恩典大教堂沉浸式 3D 游览](https://vincentwoo.com/3d/grace_cathedral/) ⭐️ 6.0/10

一位开发者利用无人机拍摄的照片，通过高斯泼溅技术制作了旧金山恩典大教堂的沉浸式 3D 游览，展示了该技术从图像生成精细可导航模型的能力。 该演示凸显了高斯泼溅技术在实现便捷、高质量摄影测量方面的潜力，无需昂贵设备或复杂流程即可实现虚拟旅游和建筑记录。 该游览通过 WebGPU 在网页浏览器中运行，但部分 Firefox 用户遇到缓冲区绑定大小超过`max_*_buffer_binding_size`限制的错误，导致体验在几秒后停止。

hackernews · akanet · Jul 20, 20:10 · [社区讨论](https://news.ycombinator.com/item?id=48984254)

**背景**: 高斯泼溅是一种体渲染技术，通过各向异性高斯基元集合表示 3D 场景，实现从照片实时合成新视角。摄影测量从图像中提取 3D 测量数据，WebGPU 是取代 WebGL 的现代 Web GPU 加速 API。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gaussian_splatting">Gaussian splatting</a></li>
<li><a href="https://en.wikipedia.org/wiki/Photogrammetry">Photogrammetry</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebGPU">WebGPU</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞了移动端的沉浸式体验，并指出其与早期 VRML 演示的相似性。但多位用户报告了 Firefox 上的 WebGPU 错误，还有评论提到了开发者之前扫描苏特罗塔的工作。

**标签**: `#3D rendering`, `#Gaussian splatting`, `#photogrammetry`, `#WebGPU`

---

<a id="item-13"></a>
## [韩国央行将于九月启动实时 CBDC 交易](https://www.coindesk.com/business/2026/07/20/bank-of-korea-prepares-for-live-cbdc-transactions-with-nine-banks-in-september) ⭐️ 6.0/10

韩国央行将于 2025 年 9 月与九家商业银行启动实时央行数字货币（CBDC）交易，从汉江项目第一阶段进入第二阶段，涉及真实的政府资金。 这标志着 CBDC 实际应用的重要一步，因为该测试涉及政府资金的真实价值交易，可能影响其他央行的数字货币策略。 汉江项目第一阶段开设了 8.1 万个钱包，活跃使用率达 42%；第二阶段将试点扩展至九家银行并转移真实政府资金，此前的零售测试已有 10 万名参与者和 7 万家商户。

rss · CoinDesk · Jul 20, 11:10

**背景**: 汉江项目是韩国央行的 CBDC 试点计划，最初于 2025 年 4 月至 6 月测试零售支付，涉及 10 万名参与者和 7-Eleven 等商户。CBDC 是由央行发行的数字货币，旨在补充现金并提高支付效率。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/testing-central-bank-digital-currency-cbdc-project-hangang-future-m8wvc">Testing Central Bank Digital Currency ( CBDC ): Project Hangang and...</a></li>
<li><a href="https://dzilla.com/south-koreas-hangang-cbdc-pilot-pioneering-retail-digital-won-adoption/">South Korea’s Hangang CBDC Pilot: Pioneering Retail Digital Won...</a></li>
<li><a href="https://www.chosun.com/english/market-money-en/2025/03/19/XOUS2TBB2ZAPRJ7R57QJEYM7IE/">Bank of Korea to launch CBDC pilot for real-world payments</a></li>

</ul>
</details>

**标签**: `#CBDC`, `#central bank digital currency`, `#blockchain`, `#finance`, `#South Korea`

---

<a id="item-14"></a>
## [比特币量子恢复工具问世，但中本聪的币仍无法恢复](https://www.coindesk.com/tech/2026/07/19/bitcoin-s-quantum-problem-gets-a-recovery-tool-but-not-for-satoshi-s-1-1-million-coin) ⭐️ 6.0/10

一种新工具被开发出来，可以恢复因量子攻击而丢失的比特币资金，但无法恢复属于中本聪的 110 万枚比特币。 该工具解决了量子计算对比特币密码学威胁日益增长的担忧，但其局限性凸显了中本聪币的不可逆损失以及对更广泛的抗量子解决方案的需求。 该恢复工具通过利用量子攻击本身的漏洞来工作，但无法恢复从未被花费或没有已知私钥的地址中的币，例如中本聪的早期钱包。

rss · CoinDesk · Jul 19, 10:00

**背景**: 量子计算机有可能破解比特币使用的椭圆曲线密码学，从而使攻击者能够窃取资金。虽然大规模量子攻击目前尚不可行，但研究人员正在开发应对措施。比特币的匿名创造者中本聪在早期钱包中持有约 110 万枚比特币，这些币从未被移动过。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2plcm96OEVCRU51X1VTaGhvcU5pZ0FQAQ?hl=en-US&gl=US&ceid=US:en">Google News - Quantum attack on Bitcoin - Overview</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#quantum computing`, `#cryptography`, `#blockchain`

---

<a id="item-15"></a>
## [俄罗斯加密货币法即将通过，规避制裁](https://decrypt.co/373880/russia-first-comprehensive-crypto-law) ⭐️ 6.0/10

俄罗斯的全面加密货币法距离通过仅差两次投票，该法将许可交易所运营、将散户投资上限设为每年约 3800 美元，并为俄罗斯企业用加密货币向外国合作伙伴付款开辟合法途径，从而规避西方制裁。 该法律标志着俄罗斯对加密货币立场的重大转变，可能使受制裁实体规避金融限制，并影响全球加密货币监管格局。 该法案还要求加密货币矿工向国家授权机构报告持有的数字货币，政府有权禁止或限制加密货币交易以维护货币稳定。

rss · Decrypt · Jul 20, 20:02

**背景**: 自入侵乌克兰以来，俄罗斯面临西方日益加重的制裁，促使其探索替代支付系统。加密货币提供了一种潜在规避途径，但专家因其可追溯性和流动性问题对其有效性存疑。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://advertising.industriesnews.net/news/274479555/russian-upper-house-approves-crypto-law">Russian Upper House approves crypto law</a></li>
<li><a href="https://www.chainalysis.com/blog/russias-cryptocurrency-legislated-sanctions-evasion/">Russia’s Cryptocurrency Pivot: Legislated Sanctions ... - Chainalysis</a></li>
<li><a href="https://news.bitcoin.com/crypto-payments-may-not-help-russia-bypass-sanctions-experts-say/">Crypto Payments May Not Help Russia Bypass Sanctions , Experts...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#Russia`, `#sanctions`

---

<a id="item-16"></a>
## [Cardano 触发首次社区投票硬分叉](https://decrypt.co/373858/cardano-van-rossem-hard-fork-live-community-upgrade) ⭐️ 6.0/10

Cardano 执行了首次完全由社区投票触发的硬分叉，没有任何公司或中央机构发起此次升级。 这一里程碑标志着 Cardano 向去中心化治理的转变，可能为其他区块链网络采用社区驱动的升级机制树立先例。 该硬分叉通过 Cardano 的链上治理系统激活，ADA 持有者直接对提案进行了投票。新闻中未披露升级功能的具体技术细节。

rss · Decrypt · Jul 20, 18:50

**背景**: Cardano 是一个强调同行评审研究和形式化验证的权益证明区块链平台。硬分叉是需要全网共识的协议升级；此前，此类升级由开发公司 IOHK（现为 Input Output Global）发起。此次事件标志着社区首次直接投票触发硬分叉，反映了 Cardano 向完全去中心化治理模式的过渡，如其 Voltaire 时代所规划。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/Hornan7/Cardano-Constitution-MVG">GitHub - Hornan7/ Cardano -Constitution-MVG</a></li>
<li><a href="https://coinlaw.io/ethereum-vs-cardano-statistics/">Ethereum vs. Cardano Statistics 2026: DeFi, NFTs, etc. • CoinLaw</a></li>
<li><a href="https://forum.cardano.org/t/cardano-community-the-clock-is-ticking/154340">Cardano community — the clock is ticking... - Cardano Forum</a></li>

</ul>
</details>

**标签**: `#Cardano`, `#blockchain`, `#governance`, `#hard fork`

---

<a id="item-17"></a>
## [NEAR 联合创始人警告 AI 黑客攻击速度超过代码审查](https://www.theblock.co/post/408943/ai-assisted-hacking-outpacing-traditional-code-reviews-near-co-founder-says?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

NEAR 联合创始人 Illia Polosukhin 表示，AI 辅助的黑客攻击速度已超过传统代码审查，并呼吁采用形式化验证来保护区块链代码。 这凸显了区块链开发中日益扩大的安全鸿沟：AI 驱动的攻击能比人类审查代码更快地利用漏洞，可能导致更频繁和严重的攻击事件。 Polosukhin 特别提倡采用形式化验证——一种通过数学方法证明代码正确性的技术——作为应对 AI 辅助黑客攻击威胁的必要转变。

rss · The Block · Jul 20, 18:20

**背景**: 形式化验证使用数学证明来确保智能合约在所有条件下按预期运行，从而消除整类漏洞。NEAR Protocol 是一个采用分片技术和权益证明共识的 Layer-1 区块链，支持去中心化应用。传统代码审查依赖人工审计，速度较慢且不如自动化 AI 攻击全面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NEAR_Protocol">NEAR Protocol</a></li>
<li><a href="https://hashlock.pages.dev/services/formal-verification">Blockchain Formal Verification | Hashlock</a></li>

</ul>
</details>

**标签**: `#AI`, `#blockchain`, `#security`, `#code review`

---

<a id="item-18"></a>
## [Hut 8 与 IREN 签署数十亿美元 AI 数据中心租约](https://www.theblock.co/post/408920/hut-8-fully-commercializes-1-gw-texas-ai-campus-with-second-9-8b-lease-as-iren-signs-2-8b-in-contracts-shares-climb-double-digits?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Hut 8 通过第二份价值 98 亿美元的租约，将其位于德克萨斯州的 1 GW AI 园区完全商业化；同时 IREN 签署了 28 亿美元的 AI 基础设施合同，两家公司股价均上涨两位数。 这些交易凸显了从比特币挖矿向 AI 基础设施的加速转型，矿商正利用其能源资产和土地获取高价值的 AI 计算合同。 Hut 8 的第二份租约使其德克萨斯园区完全商业化；IREN 的合同包括与微软和英伟达的交易，其中 IREN 还获得了微软一份价值 97 亿美元的 AI 云合同，使用英伟达 GB300 GPU。

rss · The Block · Jul 20, 14:12

**背景**: 像 Hut 8 和 IREN 这样的比特币矿商正在转向 AI 基础设施，重新利用其能源和土地资产来托管 AI 数据中心。这一转变是由于 AI 计算相比波动的挖矿奖励能带来更高且更稳定的收入。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://247wallst.com/investing/2026/07/20/hut-8-jumps-10-on-9-8b-ai-data-center-lease-mara-riot-platforms-rally-in-sympathy/">Hut 8 Jumps 10% on $9.8B AI Data Center Lease... - 24/7 Wall St.</a></li>
<li><a href="https://www.cryptobreaking.com/hut-8-and-iren-updates/">Hut 8 and IREN Updates Boost AI -Focused Bitcoin Mining Stocks</a></li>
<li><a href="https://parameter.io/iren-stock-australian-data-center-operator-lands-9-7-billion-microsoft-contract/">IREN Stock: Australian Data Center Operator Lands... - Parameter</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#data centers`, `#bitcoin mining`, `#finance`

---