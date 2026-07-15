---
layout: default
title: "Horizon Summary: 2026-07-15 (ZH)"
date: 2026-07-15
lang: zh
---

> From 73 items, 25 important content pieces were selected

---

1. [Bonsai 27B：可在手机上运行的 270 亿参数模型](#item-1) ⭐️ 8.0/10
2. [不断升高的塔：AI 代理与软件复杂性](#item-2) ⭐️ 8.0/10
3. [国际清算银行警告 AI 繁荣融资威胁全球稳定](#item-3) ⭐️ 8.0/10
4. [温哥华警察局网站新增快速退出按钮保障安全](#item-4) ⭐️ 7.0/10
5. [Dependabot 引入默认 3 天软件包冷却期](#item-5) ⭐️ 7.0/10
6. [Cursor 零日漏洞披露揭示负责任披露的失败](#item-6) ⭐️ 7.0/10
7. [实用指南：在 Go 中使用 HTMX](#item-7) ⭐️ 7.0/10
8. [报告称数据中心推高电力成本 230 亿美元](#item-8) ⭐️ 7.0/10
9. [美英协调代币化金融监管规则](#item-9) ⭐️ 7.0/10
10. [欧洲央行选定德意志银行、Revolut 等参与数字欧元试点](#item-10) ⭐️ 7.0/10
11. [OpenAI GPT-5.6 指南：停止过度提示](#item-11) ⭐️ 7.0/10
12. [Claude 的个性因模型和语言而异](#item-12) ⭐️ 7.0/10
13. [中国提议将加密货币混币器视为洗钱证据](#item-13) ⭐️ 7.0/10
14. [如何阻止 Claude 说‘承重’](#item-14) ⭐️ 6.0/10
15. [USB-C 最大化主义者：倡导通用充电](#item-15) ⭐️ 6.0/10
16. [CFTC 介入阻止 Kalshi 取消交易](#item-16) ⭐️ 6.0/10
17. [摩根大通警告 Hyperliquid 增长威胁 Circle 的 USDC 经济](#item-17) ⭐️ 6.0/10
18. [以太坊基金会孵化公司 EthSystems 瞄准银行隐私技术](#item-18) ⭐️ 6.0/10
19. [日本最大卡组织与 Circle 合作探索稳定币支付](#item-19) ⭐️ 6.0/10
20. [BIP-110 引发比特币治理之争](#item-20) ⭐️ 6.0/10
21. [预测市场在 500 亿美元世界杯中击败传统博彩](#item-21) ⭐️ 6.0/10
22. [DeepMind CEO：AGI 将比电或火更重要](#item-22) ⭐️ 6.0/10
23. [英国推迟对 DeFi 借贷和流动性池存款征收资本利得税](#item-23) ⭐️ 6.0/10
24. [Nous Research 寻求以 15 亿美元估值融资 7500 万美元](#item-24) ⭐️ 6.0/10
25. [Boundless 将 4000 GPU 网络从 ZK 扩展到 AI](#item-25) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Bonsai 27B：可在手机上运行的 270 亿参数模型](https://prismml.com/news/bonsai-27b) ⭐️ 8.0/10

PrismML 发布了 Bonsai 27B，这是一个基于 Qwen3.6 27B 的 270 亿参数多模态模型，通过极端的 1 比特和三值量化，可在 iPhone 和 iPad 等移动设备上运行。 这一突破使得 270 亿参数级别的模型能在手机上本地运行，大幅扩展了设备端 AI 在视觉和推理等任务上的能力，无需依赖云端。据报道苹果对 PrismML 技术感兴趣，凸显了其行业相关性。 该模型对语言模型采用端到端的 1 比特或三值权重，视觉塔则量化至 4 比特。它还支持在 24 GB GPU 上进行单 GPU 推理，并带有 KV 缓存量化以处理长上下文任务。

hackernews · xenova · Jul 14, 17:50 · [社区讨论](https://news.ycombinator.com/item?id=48910545)

**背景**: 量化通过降低模型权重的精度（例如 1 比特或三值）来减小内存占用并加速推理。极端的量化（如 1 比特和三值权重）具有挑战性，因为可能严重降低准确性，但 PrismML 声称在帕累托限制内保留了大部分智能。Bonsai 27B 基于阿里巴巴的开源模型 Qwen3.6 27B。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.prismml.com/models/bonsai-27b">Bonsai 27B - Bonsai</a></li>
<li><a href="https://prismml.com/news/bonsai-27b">Announcing Bonsai 27B: The First 27B-Class Model to Run on a Phone</a></li>
<li><a href="https://huggingface.co/prism-ml/Bonsai-27B-gguf">prism-ml/Bonsai-27B-gguf · Hugging Face</a></li>

</ul>
</details>

**社区讨论**: 社区成员将 Bonsai 27B 与 Gemma 4 12B 等其他小模型进行比较，质疑工具调用性能和分辨率损失方面的权衡。一些用户报告在 LM Studio 中运行模型时遇到问题，而另一些用户则称赞量化和剪枝带来的更多可能性。

**标签**: `#AI/ML`, `#model compression`, `#quantization`, `#on-device AI`, `#open source`

---

<a id="item-2"></a>
## [不断升高的塔：AI 代理与软件复杂性](https://lucumr.pocoo.org/2026/7/13/the-tower-keeps-rising/) ⭐️ 8.0/10

Armin Ronacher 的文章《不断升高的塔》指出，AI 代理虽然提升了个人的生产力，但加剧了大型软件项目的“本质复杂性”，并将其与 Lisp 诅咒相类比——极端的可组合性导致碎片化、缺乏协作的代码库。 这很重要，因为它挑战了 AI 辅助编程会自动带来更好软件的乐观叙事，强调协调和架构理解仍然是关键瓶颈。 文章引用了 Lisp 诅咒：Lisp 的强大使个人能够独自构建复杂系统，从而阻碍协作，导致文档不全、不可泛化的软件。它警告 AI 代理可能放大这一效应，使构建定制化、不可组合的解决方案变得更加容易。

hackernews · cdrnsf · Jul 14, 16:57 · [社区讨论](https://news.ycombinator.com/item?id=48909785)

**背景**: Lisp 诅咒描述了 Lisp 的高表达性使得单个程序员能轻易解决问题，以至于很少需要复用他人代码，导致生态系统碎片化。可组合性是一种设计原则，允许软件组件灵活组合；违反该原则会导致系统僵化、难以维护。AI 代理是能够自主生成或修改代码的工具，可能加速好的或坏的架构决策。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.freshcodeit.com/blog/myths-of-lisp-curse">What is the Curse of Lisp: Challenges and Opportunities - Freshcode</a></li>
<li><a href="https://en.wikipedia.org/wiki/Composability">Composability - Wikipedia</a></li>
<li><a href="https://arxiv.org/html/2606.05608v2">Agentic Software: How AI Agents Are Restructuring the Software Paradigm</a></li>

</ul>
</details>

**社区讨论**: 评论者与文章论点产生共鸣，有人用俄罗斯方块类比可组合性，有人主张开发者手动修复小问题而非让代理处理，以保持架构品味。另一位评论者明确将文章与 Lisp 诅咒和双极 Lisp 程序员概念联系起来。

**标签**: `#software engineering`, `#AI agents`, `#composability`, `#complexity`, `#Lisp Curse`

---

<a id="item-3"></a>
## [国际清算银行警告 AI 繁荣融资威胁全球稳定](https://www.bis.org/publ/bisbull120.pdf) ⭐️ 8.0/10

国际清算银行（BIS）发布了一份公告，分析 AI 繁荣的融资问题，警告债务驱动的投资和不确定的回报对全球经济构成重大风险。 该分析揭示了 AI 行业的一个关键脆弱性：如果超大规模企业放缓资本支出，供应链上的借款人可能难以偿还债务，从而可能引发金融危机。 BIS 公告指出，杠杆率上升和融资结构复杂化，AI 投资承诺超过可持续融资能力，使企业容易受到失望情绪的影响。

hackernews · 1vuio0pswjnm7 · Jul 14, 21:58 · [社区讨论](https://news.ycombinator.com/item?id=48913443)

**背景**: BIS 常被称为央行的央行，发布关于当前经济事件的公告。AI 繁荣推动了科技巨头的大规模资本支出，其中许多通过债务融资，引发了对如果回报未能实现则金融稳定性的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.telegraph.co.uk/business/2026/06/28/ai-boom-risks-global-financial-crash-central-bankers-warn/">AI boom risks global financial crash, warn central bankers</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，BIS 在 6 月的一份报告中已将 AI 融资列为最大风险之一，并质疑公告图表中缺少低增长情景。其他人怀疑 AI 对大多数公司的盈利能力，以 Duolingo 作为 AI 可能提升利润的潜在反例。

**标签**: `#AI`, `#finance`, `#economics`, `#risk`, `#BIS`

---

<a id="item-4"></a>
## [温哥华警察局网站新增快速退出按钮保障安全](https://vpd.ca/) ⭐️ 7.0/10

温哥华警察局网站现在增加了一个快速退出按钮，可以清除浏览器历史记录并跳转到天气网站，帮助用户悄悄离开页面。 这一功能为可能受到网络监控的家庭暴力受害者提供了关键的安全工具，而主要警察网站的采用可能鼓励更多政府网站实施类似功能。 该按钮使用 JavaScript 将页面透明度设为零，将标题改为“新标签页”，在新窗口中打开天气网站，并用谷歌搜索替换当前地址，从而有效隐藏用户的活动。

hackernews · LookAtThatBacon · Jul 15, 00:15 · [社区讨论](https://news.ycombinator.com/item?id=48914644)

**背景**: 快速退出按钮专为需要快速离开敏感网站的用户设计，例如寻求家庭暴力帮助的人。类似模式存在于英国政府网站和新西兰政府网站，通常通过连续按三次 Shift 键触发。

**社区讨论**: 社区评论指出，英国政府设计系统有类似的“快速退出页面”模式，新西兰网站则使用名为 Shielded Site 的 JavaScript 弹窗。一些开发者指出，虽然这种实现比简单链接更好，但仍有限制，例如无法清除服务器端日志或浏览器缓存。

**标签**: `#web development`, `#accessibility`, `#safety`, `#government`, `#UX`

---

<a id="item-5"></a>
## [Dependabot 引入默认 3 天软件包冷却期](https://github.blog/changelog/2026-07-14-dependabot-version-updates-introduce-default-package-cooldown/) ⭐️ 7.0/10

Dependabot 现在对版本更新应用默认的 3 天冷却期，避免为过去三天内发布新版本的软件包创建拉取请求。 这一变化减少了因快速发布带来的更新波动，帮助团队在安全性与稳定性之间取得平衡，但也引发了关于延迟更新是否会阻碍早期漏洞发现的讨论。 冷却期按软件包单独计算，如果在三天内推送了有问题的版本，冷却期不会重置；仍允许更新到已知有问题的版本。

hackernews · woodruffw · Jul 14, 21:15 · [社区讨论](https://news.ycombinator.com/item?id=48913050)

**背景**: Dependabot 是 GitHub 的一个工具，当新版本发布时会自动创建拉取请求来更新依赖项。如果没有冷却期，频繁发布的软件包会产生过多的拉取请求，使维护者不堪重负并增加更新波动。

**社区讨论**: 评论者表达了不同观点：一些人担心普遍采用冷却期会延迟漏洞发现，而另一些人则指出这与传统发行版软件包管理的相似之处。有用户强调，仍允许更新到有问题的版本，这缓解了部分担忧。

**标签**: `#dependabot`, `#dependency management`, `#security`, `#npm`, `#software supply chain`

---

<a id="item-6"></a>
## [Cursor 零日漏洞披露揭示负责任披露的失败](https://mindgard.ai/blog/cursor-0day-when-full-disclosure-becomes-the-only-protection-left) ⭐️ 7.0/10

安全研究机构 Mindgard 公开披露了 AI 编程工具 Cursor 中的一个零日漏洞，此前该供应商在六个月内多次收到报告却未能修复。 此次披露凸显了广泛使用的 AI 开发工具中未修补漏洞的风险，可能影响数千名依赖 Cursor 进行编码辅助的开发者。 该漏洞允许攻击者通过将名为 git.exe 的恶意可执行文件放入用户代码文件夹中，Cursor 的代理可能会执行该文件。该问题于 2025 年 12 月 15 日首次报告，经过 197 多个版本后仍在最新测试版本中存在。

hackernews · Synthetic7346 · Jul 14, 17:58 · [社区讨论](https://news.ycombinator.com/item?id=48910676)

**背景**: Cursor 是一款流行的 AI 驱动代码编辑器，集成了大型语言模型以辅助开发者。负责任披露是一种安全实践，研究人员私下向供应商报告漏洞，给予他们修复时间后再公开发布。当供应商未能回应时，研究人员可能采取完全披露以警告用户。

**社区讨论**: 评论意见不一：有人认为该漏洞需要攻击者已具备代码执行能力，降低了严重性；而另一些人则强调，如果 Cursor 代理被赋予 git 权限，则存在供应链风险。一位评论者指出，LLM 生成的安全报告泛滥，可能使供应商不堪重负。

**标签**: `#security`, `#vulnerability`, `#AI tools`, `#responsible disclosure`, `#Cursor`

---

<a id="item-7"></a>
## [实用指南：在 Go 中使用 HTMX](https://www.alexedwards.net/blog/how-i-use-htmx-with-go) ⭐️ 7.0/10

Alex Edwards 发布了一篇实用指南，介绍如何将 HTMX 与 Go 集成，以最少的 JavaScript 构建响应式 Web 应用程序，并分享了他的具体方法和模式。 该指南帮助 Go 开发者采用超媒体驱动架构，降低前端复杂性和对 JavaScript 的依赖，符合简化全栈开发的发展趋势。 文章涵盖了实用的集成模式，可能包括使用 Go 模板进行服务端渲染以及利用 HTMX 属性实现动态更新，无需 JavaScript 框架。

hackernews · gnabgib · Jul 14, 19:55 · [社区讨论](https://news.ycombinator.com/item?id=48912175)

**背景**: HTMX 是一个开源 JavaScript 库，通过自定义属性扩展 HTML，直接在 HTML 中启用 AJAX、WebSocket 和 CSS 过渡，倡导超媒体驱动方法。Go 是一种以简洁和高性能著称的后端语言。两者结合可以用更少的 JavaScript 构建交互式 Web 应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Htmx">Htmx</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞 Go + HTMX 的组合，一些人分享了替代工具，如“GUS 栈”（Go、Unix、SQLite）和用于类型安全模板的 templ。其他人强调了与 JavaScript 框架相比的简洁性和减少的样板代码，同时建议采用组件化的 HTML 生成以提高灵活性。

**标签**: `#Go`, `#HTMX`, `#web development`, `#full-stack`

---

<a id="item-8"></a>
## [报告称数据中心推高电力成本 230 亿美元](https://fortune.com/2026/07/14/data-centers-23-billion-electricity-bills/) ⭐️ 7.0/10

一份报告声称，数据中心负荷增长使 PJM 三次容量拍卖的收入增加了 231 亿美元，引发了关于这是否真正增加了公众成本还是基础设施投资的争论。 这很重要，因为数据中心扩张正在加速，电力成本的分配方式既影响居民用户，也影响科技行业的竞争力。 230 亿美元的数字指的是 PJM 因增加数据中心客户而增加的收入，不一定是公众电费直接上涨；2024 年美国发电总收入为 5140 亿美元，因此这相当于 4-5%的增长。

hackernews · measurablefunc · Jul 15, 00:20 · [社区讨论](https://news.ycombinator.com/item?id=48914683)

**背景**: 数据中心消耗大量电力，其快速增长可能给当地电网带来压力。像 PJM 这样的容量市场通过向发电商支付费用以确保未来电力供应，成本通常由所有用户分摊，而不仅仅是数据中心。

**社区讨论**: 评论者争论 230 亿美元是公众成本增加还是基础设施投资；一些人认为数据中心作为锚定租户为电网改进提供资金，而另一些人质疑为何居民用户应分担负担。

**标签**: `#data centers`, `#electricity pricing`, `#infrastructure`, `#energy policy`

---

<a id="item-9"></a>
## [美英协调代币化金融监管规则](https://www.coindesk.com/policy/2026/07/14/u-s-uk-move-to-align-rules-for-tokenized-finance-across-world-s-largest-financial-markets) ⭐️ 7.0/10

美国和英国宣布联合倡议，协调代币化金融的监管规则，旨在为全球两大金融中心的数字资产市场建立一致的框架。 这一监管协调可能显著降低金融机构的跨境合规负担，加速区块链技术在传统金融中的应用，并可能为代币化资产监管树立全球标准。 该倡议聚焦于资产代币化、托管标准和跨境交易协议等关键领域，但具体的实施时间表和法律细节尚未公布。

rss · CoinDesk · Jul 14, 16:29

**背景**: 代币化金融是指将传统金融资产（如债券、股票或房地产）以数字代币形式在区块链上表示。美国和英国合计占全球金融市场的很大份额，它们的监管协调可能影响其他司法管辖区。

**标签**: `#tokenization`, `#regulation`, `#finance`, `#blockchain`, `#policy`

---

<a id="item-10"></a>
## [欧洲央行选定德意志银行、Revolut 等参与数字欧元试点](https://www.coindesk.com/business/2026/07/14/ecb-picks-firms-including-deutsche-bank-revolut-for-digital-euro-pilot) ⭐️ 7.0/10

欧洲央行已选定包括德意志银行和 Revolut 在内的 36 家支付服务提供商，参与将于 2027 年底启动、为期一年的数字欧元测试版试点。 此次试点标志着欧元区朝着可能发行央行数字货币迈出了重要一步，可能重塑整个欧洲的数字支付和金融普惠格局。 试点将于 2027 年底启动，为期一年，与选定的支付服务提供商共同测试数字欧元测试版；欧洲央行尚未承诺全面推出。

rss · CoinDesk · Jul 14, 12:10

**背景**: 央行数字货币是由中央银行发行的国家法定货币的数字形式。欧洲央行一直在探索数字欧元，以补充实物现金，确保欧元在数字时代保持相关性。此次试点是在多年研究和公众咨询之后进行的。

**标签**: `#CBDC`, `#digital euro`, `#ECB`, `#fintech`, `#blockchain`

---

<a id="item-11"></a>
## [OpenAI GPT-5.6 指南：停止过度提示](https://decrypt.co/373439/openai-new-gpt-5-6-prompt-guide-chatgpt) ⭐️ 7.0/10

OpenAI 发布了针对 GPT-5.6 的更新提示指南，建议用户专注于定义目标和停止条件，而不是使用 XML 块或持久化脚本过度设计提示。 这一最佳实践的转变可能显著改变开发者和用户与大型语言模型交互的方式，简化提示工程并可能提升模型性能。 新指南强调定义目标和设置停止条件，摒弃了之前推荐的 XML 块和持久化脚本等复杂提示结构。

rss · Decrypt · Jul 13, 22:46

**背景**: 提示工程一直是有效使用 LLM 的关键技能，通常涉及复杂的格式来引导模型行为。OpenAI 之前的指南包括 XML 标记和多步骤脚本等技术，以提高输出一致性。新方法表明，GPT-5.6 改进的推理能力需要更少的显式指令。

**标签**: `#OpenAI`, `#GPT-5.6`, `#prompt engineering`, `#LLM`, `#AI guidelines`

---

<a id="item-12"></a>
## [Claude 的个性因模型和语言而异](https://decrypt.co/373422/anthropic-claude-personality-changes-model-language) ⭐️ 7.0/10

Anthropic 的研究显示，Claude 所表达的价值观会因模型版本和使用的语言而显著变化。 这一发现对 AI 对齐和安全至关重要，因为它凸显了在多语言 AI 部署中确保行为一致性所面临的挑战。 研究显示，Claude 的个性特征（如开放性和尽责性）在不同模型版本（例如 Claude 3 与 Claude 3.5）和语言（例如英语与中文）之间存在差异。

rss · Decrypt · Jul 13, 20:39

**背景**: 像 Claude 这样的大型语言模型是在多样化数据上训练的，可能表现出不同的行为。AI 对齐研究旨在确保模型符合人类价值观，但这项研究表明，即使在同一个模型家族中，价值观也可能因上下文而发生变化。

**标签**: `#AI alignment`, `#Anthropic`, `#multilingual AI`, `#AI safety`, `#LLM behavior`

---

<a id="item-13"></a>
## [中国提议将加密货币混币器视为洗钱证据](https://decrypt.co/373374/chinese-prosecutors-float-treating-crypto-mixer-privacy-coin-use-as-sign-of-money-laundering) ⭐️ 7.0/10

中国检察官提议将使用加密货币混币器和隐私币视为洗钱的推定证据，同时提出新的区块链证据规则和建立国家平台出售被扣押的加密货币。 此举可能进一步收紧中国本已严格的加密货币监管，可能为其他国家树立先例，并进一步限制全球加密生态系统中隐私增强工具的使用。 该提案包括建立国家平台拍卖被扣押的加密货币，并为法庭上的区块链证据制定新规则。它还建议使用混币器或隐私币可自动表明洗钱意图。

rss · Decrypt · Jul 13, 10:43

**背景**: 中国自 2021 年起禁止加密货币交易和挖矿，但当局继续打击相关金融犯罪。加密货币混币器和隐私币模糊交易痕迹，使其对非法活动具有吸引力，因此受到全球监管机构的关注。

**标签**: `#cryptocurrency`, `#regulation`, `#money laundering`, `#privacy coins`, `#China`

---

<a id="item-14"></a>
## [如何阻止 Claude 说‘承重’](https://jola.dev/posts/how-to-stop-claude-from-saying-load-bearing) ⭐️ 6.0/10

一篇博文幽默地指出 Claude 过度使用某些短语（如‘承重’），并讨论了 LLM 语言习惯在大规模应用中变得明显的现象。 这凸显了 LLM 输出偏差在数百万用户中放大后，如何导致生成文本出现令人不适的一致性，影响用户信任和 AI 生成内容的真实感。 该博文建议使用自定义指令或系统提示来阻止特定短语，并指出这种语言习惯是当前 LLM 固有的语言偏差放大形式。

hackernews · shintoist · Jul 14, 11:46 · [社区讨论](https://news.ycombinator.com/item?id=48905248)

**背景**: 像 Claude 这样的大型语言模型（LLM）根据从训练数据中学到的模式生成文本。由于常见模式的强化，它们经常会产生‘语言习惯’——过度使用的单词或短语。随着 LLM 大规模部署，这些习惯变得更加明显，可能使 AI 生成的文本显得重复或不自然。

**社区讨论**: 评论者指出，虽然与 AI 交互时 LLM 的语言习惯本身并不令人烦恼，但当在人类撰写的散文中遇到时，它们会显得突兀，暴露了 AI 的参与。一位用户整理了 Claude 的常用词汇列表，包括‘投影’、‘链’和‘静止’。

**标签**: `#LLM`, `#AI behavior`, `#language patterns`, `#Claude`

---

<a id="item-15"></a>
## [USB-C 最大化主义者：倡导通用充电](https://shkspr.mobi/blog/2026/07/im-a-usb-c-maximalist/) ⭐️ 6.0/10

一篇博客文章倡导在所有设备（包括牙刷等个人护理用品）上采用 USB-C，并提供实用旅行建议，例如使用带 IEC C7 线缆的桌面充电器。 这一观点凸显了推动通用充电标准的持续努力，这可以减少电子垃圾并简化消费者的旅行，但电缆标签和电池偏好等挑战依然存在。 作者建议旅行时使用支持八字线缆的 USB-C 桌面充电器，避免使用可能不匹配插座的墙插。社区评论还指出需要标准化电缆标签以指示速度和功率能力。

hackernews · speckx · Jul 14, 15:20 · [社区讨论](https://news.ycombinator.com/item?id=48908214)

**背景**: USB-C 是一种用于充电和数据传输的通用连接器标准，但并非所有电缆和充电器都支持相同的速度或功率水平。欧盟已强制要求许多设备使用 USB-C 作为通用充电端口，推动了其普及。

**社区讨论**: 评论者普遍支持 USB-C 最大化主义，但提出了实际担忧：一些人更喜欢个人护理用品使用可更换电池以避免内置电池故障，而另一些人则强调未标记电缆因能力不同而造成的混乱。

**标签**: `#USB-C`, `#consumer electronics`, `#travel`, `#charging standards`

---

<a id="item-16"></a>
## [CFTC 介入阻止 Kalshi 取消交易](https://www.coindesk.com/policy/2026/07/14/u-s-cftc-moves-to-stop-kalshi-from-canceling-trades-as-ordered-by-michigan-court) ⭐️ 6.0/10

美国商品期货交易委员会（CFTC）已采取行动，阻止预测市场平台 Kalshi 按照密歇根州法院的命令取消交易。 此次干预凸显了联邦与州监管机构之间关于预测市场的管辖权争议，可能为美国如何监管此类平台树立先例。 密歇根州法院曾命令 Kalshi 取消某些交易，但 CFTC 认为联邦法律优先于涉及商品交易的州命令。结果可能影响 Kalshi 的运营及整个预测市场行业。

rss · CoinDesk · Jul 14, 20:51

**背景**: 预测市场允许用户就未来事件（如选举或体育赛事）的结果进行交易。CFTC 声称对这些市场拥有商品衍生品的管辖权，而一些州则主张消费者保护管辖权。此案是更广泛的监管拉锯战的一部分。

**标签**: `#regulation`, `#crypto`, `#CFTC`, `#prediction markets`

---

<a id="item-17"></a>
## [摩根大通警告 Hyperliquid 增长威胁 Circle 的 USDC 经济](https://www.coindesk.com/business/2026/07/14/jpmorgan-says-hyperliquid-s-rise-threatens-circle-s-usdc-economics) ⭐️ 6.0/10

摩根大通发布报告警告，去中心化交易所 Hyperliquid 的崛起可能通过减少交易和流动性提供中对 USDC 的需求，从而破坏 Circle 的 USDC 稳定币经济。 这家大型银行的分析凸显了 DeFi 创新如何挑战既有的稳定币商业模式，可能影响 Circle 的收入及更广泛的稳定币市场动态。 Hyperliquid 的原生代币和交易激励可能减少对 USDC 的依赖，而其不断增长的流动性池可能从 Circle 生态系统中分流交易量。报告指出，Hyperliquid 的模式可能对 USDC 的费收入和流通量造成压力。

rss · CoinDesk · Jul 14, 14:57

**背景**: Circle 的 USDC 是一种与美元挂钩的主要稳定币，广泛用于 DeFi 和交易。Hyperliquid 是一个去中心化交易所（DEX），凭借其自有代币和高速交易获得了关注。摩根大通的报告反映了中心化稳定币与去中心化交易平台之间日益激烈的竞争。

**标签**: `#cryptocurrency`, `#stablecoins`, `#finance`, `#market analysis`

---

<a id="item-18"></a>
## [以太坊基金会孵化公司 EthSystems 瞄准银行隐私技术](https://www.coindesk.com/tech/2026/07/14/ethereum-foundation-spinout-ethsystems-targets-banks-with-blockchain-privacy-technology) ⭐️ 6.0/10

以太坊基金会孵化的公司 EthSystems 宣布将开发技术并提供咨询，帮助银行在以太坊上运营的同时保持交易机密性。 这表明通过解决隐私问题推动以太坊的机构采用，可能开启银行在公共区块链上的私人支付和结算等用例。 该初创公司将专注于技术开发和咨询服务，专门针对银行，但公告中未提供具体技术细节或时间表。

rss · CoinDesk · Jul 14, 14:31

**背景**: 由于所有交易都可见，银行一直对使用以太坊等公共区块链持犹豫态度，这源于隐私和监管担忧。零知识证明和机密交易等隐私技术可以实现选择性数据披露，使公共区块链适用于受监管机构。

**标签**: `#blockchain`, `#privacy`, `#Ethereum`, `#banking`

---

<a id="item-19"></a>
## [日本最大卡组织与 Circle 合作探索稳定币支付](https://www.coindesk.com/business/2026/07/14/circle-signs-mou-with-japan-s-largest-card-network-to-explore-stablecoin-payments) ⭐️ 6.0/10

日本最大的银行卡组织与 Circle 签署谅解备忘录，探索整合稳定币支付，可能覆盖 4000 万商户。 这一合作可能显著加速稳定币在日本零售支付生态中的采用，为大众市场连接传统金融与加密货币。 该卡组织在日本服务超过 4000 万商户，此次合作处于探索阶段，重点在于技术整合和监管合规。

rss · CoinDesk · Jul 14, 12:01

**背景**: 稳定币是与美元等稳定资产挂钩的加密货币，旨在最小化价格波动。日本在监管下逐步开放加密货币支付，Circle 的 USDC 是领先的稳定币。

**标签**: `#stablecoins`, `#payments`, `#crypto adoption`, `#Japan`

---

<a id="item-20"></a>
## [BIP-110 引发比特币治理之争](https://www.coindesk.com/tech/2026/07/14/bitcoin-s-bip-110-sparked-a-fight-over-who-gets-to-decide-the-future-of-bitcoin) ⭐️ 6.0/10

比特币改进提案 110（BIP-110）引发了一场关于谁控制比特币未来方向的激烈争论，凸显了社区内部的深刻分歧。 这场争论意义重大，因为它挑战了比特币的去中心化治理模式，可能影响未来升级的决策和实施方式，进而影响整个加密货币生态系统。 BIP-110 提议修改比特币的共识规则，但新闻中未提供具体技术细节。争议焦点在于治理合法性以及谁有权提出和批准此类变更。

rss · CoinDesk · Jul 14, 11:01

**背景**: 比特币改进提案（BIP）是引入新功能或变更的设计文档。比特币的治理是去中心化的，意味着没有任何单一实体拥有最终权威，因此在有争议的提案出现时就会引发辩论。BIP-110 就是这样一个导致社区分裂的提案。

**标签**: `#Bitcoin`, `#BIP`, `#cryptocurrency`, `#governance`

---

<a id="item-21"></a>
## [预测市场在 500 亿美元世界杯中击败传统博彩](https://www.coindesk.com/business/2026/07/14/prediction-markets-just-crushed-traditional-sportsbooks-in-a-massive-usd50-billion-world-cup-breakout) ⭐️ 6.0/10

预测市场在 2026 年世界杯期间处理了 500 亿美元的交易量，首次在全球重大赛事中超越传统体育博彩。 这一里程碑标志着投注行为向去中心化平台的转变，可能颠覆价值超过 1000 亿美元的体育博彩行业，并加速加密货币的采用。 500 亿美元的数字包括 Polymarket 和 Kalshi 等平台的链上和链下交易量，仅决赛一场的投注额就超过 50 亿美元。

rss · CoinDesk · Jul 14, 11:00

**背景**: 预测市场允许用户使用加密货币或法定货币对事件结果进行投注，通常比传统体育博彩具有更高的流动性和更少的限制。2026 年世界杯是对其可扩展性和用户信任度的首次重大考验。

**标签**: `#prediction markets`, `#sports betting`, `#crypto`, `#finance`

---

<a id="item-22"></a>
## [DeepMind CEO：AGI 将比电或火更重要](https://decrypt.co/373511/deepmind-ceo-agi-bigger-than-electricity-fire) ⭐️ 6.0/10

DeepMind CEO Demis Hassabis 表示，通用人工智能（AGI）仅需几年时间就能实现，并提议建立一个美国标准机构，在发布前对前沿 AI 模型进行测试。 这位 AI 领域领军人物的话凸显了 AI 发展的加速以及安全标准的紧迫需求，可能影响全球 AI 监管和公众认知。 Hassabis 将 AGI 的影响比作电和火，强调其变革潜力，并呼吁建立一个类似于美国国家标准与技术研究院（NIST）的机构来评估前沿模型。

rss · Decrypt · Jul 14, 19:57

**背景**: 通用人工智能（AGI）指能够执行人类任何智力任务的 AI 系统。前沿 AI 模型是来自 OpenAI、Anthropic 和 Google DeepMind 等组织的最先进的大型语言模型和多模态系统。目前，这些强大模型在部署前缺乏标准化的测试框架。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Frontier_AI_models">Frontier AI models</a></li>

</ul>
</details>

**标签**: `#AGI`, `#AI Safety`, `#DeepMind`, `#AI Regulation`

---

<a id="item-23"></a>
## [英国推迟对 DeFi 借贷和流动性池存款征收资本利得税](https://decrypt.co/373481/uk-to-defer-capital-gains-tax-on-defi-lending-liquidity-pool-deposits) ⭐️ 6.0/10

英国税务海关总署（HMRC）明确表示，将加密资产转入 DeFi 借贷协议或流动性池不会触发资本利得税事件，税收将推迟至实际变现时。 该政策为英国的 DeFi 参与者提供了监管明确性，减少了税收不确定性，并可能鼓励更多人参与去中心化金融平台。 该处理方式对某些加密贷款和流动性池交易采用“无收益、无损失”原则，意味着直到发生经济处置（例如兑换为法定货币）时才产生应税处置。

rss · Decrypt · Jul 14, 15:00

**背景**: DeFi 借贷涉及将加密资产存入智能合约以赚取利息，而流动性池则提供交易流动性以换取费用。此前，此类存款在英国可能被视为应税处置，给用户带来复杂性。

**标签**: `#DeFi`, `#tax regulation`, `#UK`, `#crypto`

---

<a id="item-24"></a>
## [Nous Research 寻求以 15 亿美元估值融资 7500 万美元](https://www.theblock.co/post/408237/decentralized-ai-project-nous-research-in-talks-to-raise-75m-at-1-5b-valuation-report?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

据报道，去中心化 AI 项目 Nous Research 正在洽谈由 Robot Ventures 领投至少 7500 万美元的融资，估值达 15 亿美元。 本轮融资凸显了投资者对去中心化 AI 日益增长的兴趣，该领域旨在实现 AI 开发的民主化，减少对中心化科技巨头的依赖。 据报道，15 亿美元的估值对专注于开源和社区驱动 AI 模型的 Nous Research 来说是一个重要里程碑。该交易由以投资加密和去中心化项目闻名的风投公司 Robot Ventures 领投。

rss · The Block · Jul 14, 14:24

**背景**: Nous Research 是一家去中心化 AI 研究组织，开发开源 AI 模型，例如 Nous Hermes 系列。去中心化 AI 旨在分散 AI 技术的控制权和访问权，与 OpenAI 或 Google 等公司的中心化方法形成对比。这笔资金将支持其模型和基础设施的进一步开发。

**标签**: `#AI`, `#funding`, `#decentralized AI`, `#Nous Research`

---

<a id="item-25"></a>
## [Boundless 将 4000 GPU 网络从 ZK 扩展到 AI](https://www.theblock.co/post/408213/distributed-compute-startup-boundless-gpus-zk-to-ai?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

初创公司 Boundless 此前构建了一个 4000 GPU 集群用于在比特币上结算 ZK 证明，现在正将其分布式计算网络扩展到支持 AI 工作负载。 此举有助于满足 AI 领域对 GPU 计算日益增长的需求，同时利用了原本为区块链 ZK 证明设计的现有基础设施。这也凸显了区块链与 AI 计算市场的融合趋势。 该网络目前包含 4000 个 GPU，此次扩展将允许这些资源除用于 ZK 证明生成外，还可用于 AI 模型训练和推理。未披露具体时间表或定价细节。

rss · The Block · Jul 14, 13:00

**背景**: ZK（零知识）证明是一种密码学方法，允许一方在不透露额外信息的情况下向另一方证明某个陈述为真。它们被用于区块链扩容解决方案（如 Rollup）。Boundless 最初构建其 GPU 集群是为了加速以太坊和 Base Rollup 的 ZK 证明生成，并将证明在比特币上结算。AI 工作负载（如训练大语言模型）同样需要大量并行 GPU 计算，因此该基础设施具有可适应性。

**标签**: `#distributed computing`, `#GPU`, `#ZK proofs`, `#AI`, `#startup`

---