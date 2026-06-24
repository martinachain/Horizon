---
layout: default
title: "Horizon Summary: 2026-06-24 (ZH)"
date: 2026-06-24
lang: zh
---

> From 84 items, 29 important content pieces were selected

---

1. [Rhombus 语言 1.0 发布](#item-1) ⭐️ 9.0/10
2. [LLM 生成的漏洞报告淹没安全渠道](#item-2) ⭐️ 8.0/10
3. [Swift Package Index 被苹果收购](#item-3) ⭐️ 8.0/10
4. [TikZ 编辑器：LaTeX 图形的所见即所得工具](#item-4) ⭐️ 8.0/10
5. [Armin Ronacher 警告 AI 生成代码将导致不可维护](#item-5) ⭐️ 8.0/10
6. [谷歌警告 AI 意识辩论可能政治化](#item-6) ⭐️ 8.0/10
7. [Taiko L2 桥接漏洞：170 万美元被盗，用户被敦促撤资](#item-7) ⭐️ 8.0/10
8. [FUTO Swipe：开源滑行输入模型](#item-8) ⭐️ 7.0/10
9. [Meta 因数据泄露暂停员工追踪计划](#item-9) ⭐️ 7.0/10
10. [维生素 D 益处真实但被过度炒作](#item-10) ⭐️ 7.0/10
11. [极端高温会议因高温警告取消](#item-11) ⭐️ 7.0/10
12. [以太坊基金会将削减 40%预算进行重大重组](#item-12) ⭐️ 7.0/10
13. [OpenAI GPT-5.5-Cyber 登顶排行榜，击败被禁的 Anthropic 模型](#item-13) ⭐️ 7.0/10
14. [美国参议院通过住房法案，附带四年美联储 CBDC 禁令](#item-14) ⭐️ 7.0/10
15. [特朗普下令加速量子就绪，比特币面临风险](#item-15) ⭐️ 7.0/10
16. [致敬拼写检查波浪线的创造者](#item-16) ⭐️ 6.0/10
17. [凯文·米特尼克赠车给曾助其入狱者](#item-17) ⭐️ 6.0/10
18. [Chainlink 与 47 家银行合作加速跨境支付](#item-18) ⭐️ 6.0/10
19. [富兰克林坦伯顿完成 250 Digital 收购，成立加密部门](#item-19) ⭐️ 6.0/10
20. [Qwable：免费本地模型模仿 Claude Fable 的推理风格](#item-20) ⭐️ 6.0/10
21. [特朗普量子政策获赞，比特币尚未准备好](#item-21) ⭐️ 6.0/10
22. [AI 代理在《文明 VI》中造核弹仍输](#item-22) ⭐️ 6.0/10
23. [ICE 与 OKX 成立合资企业推动代币化证券](#item-23) ⭐️ 6.0/10
24. [谷歌投资 7500 万美元与 A24 合作 AI 电影制作研究](#item-24) ⭐️ 6.0/10
25. [英国央行用 400 亿英镑发行上限取代稳定币持有上限](#item-25) ⭐️ 6.0/10
26. [Meta 的扎克伯格计划推出预测市场应用](#item-26) ⭐️ 6.0/10
27. [美国司法部查封汇旺集团用于洗钱数十亿美元的云账户](#item-27) ⭐️ 6.0/10
28. [OKX 欧洲 CEO：80%的加密货币交易所将无法通过 MiCA](#item-28) ⭐️ 6.0/10
29. [Strategy Inc. 的比特币财库面临首次重大考验](#item-29) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Rhombus 语言 1.0 发布](https://blog.racket-lang.org/2026/06/rhombus-v1.0.html) ⭐️ 9.0/10

Rhombus 语言 1.0 正式发布，这是一种基于 Racket 构建的新编程语言，具有创新的宏特性，例如 `...` 运算符。 此次发布标志着 Racket 生态系统的一个重要里程碑，提供了一种具有常规语法且可宏扩展的语言，可能吸引那些偏好非 Lisp 语法但仍希望保留强大元编程能力的开发者。 `...` 运算符并非内置特性，而是一个宏，因此它可以处理嵌套数据结构并替代 map 操作。Rhombus 使用一种称为 Shrubbery 的语法，为 Racket 添加了常规语法。

hackernews · Decabytes · Jun 22, 17:50 · [社区讨论](https://news.ycombinator.com/item?id=48633473)

**背景**: Racket 是一种基于 Lisp 的编程语言，以其强大的宏系统而闻名，允许开发者扩展语言。Rhombus 旨在提供更常规的语法（如 Python 或 Rust），同时保留 Racket 的宏能力。Rhombus 中的 `...` 运算符是一个宏，可以实现对嵌套数据的简洁迭代和模式匹配。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://rhombus-lang.org/">Rhombus Programming Language</a></li>
<li><a href="https://github.com/racket/rhombus">GitHub - racket/ rhombus : Rhombus programming language · GitHub</a></li>
<li><a href="https://docs.racket-lang.org/rhombus/lang.html">9 Defining Languages</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞 `...` 运算符的通用性和基于宏的实现。一些人表示更喜欢 s-表达式，但承认 Rhombus 有潜力吸引新用户。还有人对在未来的会议上看到关于 Rhombus 的演讲感兴趣。

**标签**: `#Racket`, `#Rhombus`, `#Programming Languages`, `#Macros`, `#Lisp`

---

<a id="item-2"></a>
## [LLM 生成的漏洞报告淹没安全渠道](https://words.filippo.io/vuln-reports/) ⭐️ 8.0/10

Filippo Valsorda 的文章指出，大量低质量、通常由 LLM 生成的漏洞报告正在削弱合法安全披露的价值和信号。 这一趋势压垮了维护者，降低了对漏洞报告的信任，并可能导致重要漏洞被忽视，最终削弱软件安全性。 文章强调，LLM 可以轻易发现诸如不良 CSS 等表面问题，而真正的漏洞需要更深入的分析。大量垃圾报告迫使维护者对所有报告持怀疑态度。

hackernews · goranmoomin · Jun 23, 23:42 · [社区讨论](https://news.ycombinator.com/item?id=48653216)

**背景**: 漏洞披露是安全研究人员向项目维护者报告漏洞，然后修复并公开披露的过程。传统上，这些报告稀少且有价值。LLM 现在自动化生成低质量报告，淹没渠道并稀释信号。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html">Vulnerability Disclosure - OWASP Cheat Sheet Series</a></li>
<li><a href="https://www.cisa.gov/resources-tools/programs/coordinated-vulnerability-disclosure-program">Coordinated Vulnerability Disclosure Program - CISA</a></li>
<li><a href="https://www.researchgate.net/publication/397366211_From_Model_to_Breach_Towards_Actionable_LLM-Generated_Vulnerabilities_Reporting">(PDF) From Model to Breach: Towards Actionable LLM - Generated ...</a></li>

</ul>
</details>

**社区讨论**: 评论者对垃圾报告表示沮丧，一位维护者每周收到 2-5 份未经请求的报告。一些人认为随着 LLM 改进，这种情况是暂时的，而另一些人则认为漏洞报告一直很繁琐，项目可以选择退出。还有人希望这将推动更好的软件实践，如内存安全语言。

**标签**: `#security`, `#vulnerability disclosure`, `#LLM`, `#spam`, `#open source`

---

<a id="item-3"></a>
## [Swift Package Index 被苹果收购](https://swiftpackageindex.com/blog/swift-package-index-joins-apple) ⭐️ 8.0/10

苹果已收购 Swift Package Index (SPI)，这是一个由社区运营的 Swift 包发现网站，SPI 博客已宣布此消息。 此次收购表明苹果对 Swift 生态系统的战略投资，可能改善 Xcode 中的包发现和集成，但也引发了关于苹果在开源和开发者服务方面记录的担忧。 SPI 团队（包括创始人 Dave Verwer）将加入苹果，该网站将继续作为免费服务运营。苹果明确提到开发者身份是未来方向，这引起了社区的不安。

hackernews · JDevlieghere · Jun 23, 18:00 · [社区讨论](https://news.ycombinator.com/item?id=48648779)

**背景**: Swift Package Index 是一个由社区维护的可搜索 Swift 包索引，提供兼容性信息和包元数据。它一直是 Swift 开发者的关键资源，补充了 Xcode 中苹果内置的 Swift Package Manager。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sesamedisk.com/apple-joins-swift-package-index/">What Happened: Apple Joins Swift Package Index - Sesame Disk</a></li>

</ul>
</details>

**社区讨论**: 社区评论显示出复杂的情绪：有人为 SPI 团队的成功感到高兴，也有人对苹果控制开源工具以及提及开发者身份表示担忧。甚至有用户计划构建一个竞争对手，因为 SPI 仅支持 GitHub 仓库的限制。

**标签**: `#Swift`, `#Apple`, `#Package Management`, `#Open Source`, `#Acquisition`

---

<a id="item-4"></a>
## [TikZ 编辑器：LaTeX 图形的所见即所得工具](https://tikz.dev/editor/) ⭐️ 8.0/10

一个开源的 TikZ 图形所见即所得编辑器已发布，用户可以通过拖拽和调整元素来可视化编辑源代码，同时保持源代码与渲染输出同步。 该工具解决了学者和 LaTeX 用户手动调整坐标并重新编译的主要痛点，节省了大量时间和精力。它也展示了 AI 辅助编程如何创建以前因过于繁琐而无法构建的工具。 该编辑器解析 TikZ 代码并跟踪对象的精确源代码位置，从而在拖拽元素时仅覆盖坐标数字。它几乎完全使用 Codex 构建，消耗约 7 亿个 token，ChatGPT 订阅费用约 500 美元。

hackernews · DominikPeters · Jun 23, 14:24 · [社区讨论](https://news.ycombinator.com/item?id=48645437)

**背景**: TikZ 是一个强大的 LaTeX 包，用于创建矢量图形，广泛应用于学术论文。传统上，用户编写类似\draw 的命令并反复重新编译来调整位置，非常耗时。所见即所得编辑器允许直接操作视觉输出，类似于文字处理器在编辑时显示最终文档。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.overleaf.com/learn/latex/TikZ_package">TikZ package - Overleaf, Online LaTeX Editor</a></li>
<li><a href="https://en.wikipedia.org/wiki/WYSIWYG_editor">WYSIWYG editor</a></li>

</ul>
</details>

**社区讨论**: 社区称赞了该工具的界面和概念，许多人表示终于有更简单的方法来创建 TikZ 图表。但也有批评指出生成的代码不必要地使用了绝对坐标，作者则透露了开发中消耗的大量 AI token 和成本。

**标签**: `#LaTeX`, `#TikZ`, `#editor`, `#academic`, `#open-source`

---

<a id="item-5"></a>
## [Armin Ronacher 警告 AI 生成代码将导致不可维护](https://lucumr.pocoo.org/2026/6/23/the-coming-loop/) ⭐️ 8.0/10

Flask 框架的创建者 Armin Ronacher 发表了一篇题为《即将到来的循环》的文章，警告 AI 辅助编程可能产生人类无法单独维护的代码库，侵蚀开发者在不借助机器增强的情况下理解和讨论代码的能力。 这之所以重要，是因为随着 AI 工具成为软件开发不可或缺的一部分，代码的长期可维护性和开发者的认知能力面临风险，可能导致未来人类对代码的理解次于机器解释。 Ronacher 指出，开发者越来越多地合并他们无法完全解释的代码，并依赖 LLM 来总结或提供讨论背景，这种依赖可能使代码库将机器参与作为其维护模型的一部分。

hackernews · ingve · Jun 23, 11:06 · [社区讨论](https://news.ycombinator.com/item?id=48643180)

**背景**: Armin Ronacher 是著名的开源开发者，以创建 Flask Web 框架和 Jinja 模板引擎而闻名。像 GitHub Copilot 和 Claude Code 这样的 AI 辅助编程工具已被广泛使用，引发了对代码质量和可维护性的担忧。Ronacher 的文章为关于依赖 AI 进行软件开发的长期影响的讨论增添了新的视角。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Armin_Ronacher">Armin Ronacher</a></li>
<li><a href="https://codemanship.wordpress.com/2026/01/12/yes-maintainability-still-matters-in-ai-assisted-coding/">Yes, Maintainability Still Matters in “AI”-assisted Coding</a></li>

</ul>
</details>

**社区讨论**: 像 mccoyb 这样的评论者认为，清晰的理解是有效使用 AI 的前提，AI 无法替代迭代破碎版本所需的思考时间。其他人如 miki123211 指出，LLM 擅长完成任务，但缺乏美学和品味，而这对于可维护的代码至关重要。

**标签**: `#AI`, `#software engineering`, `#LLMs`, `#code maintenance`, `#human cognition`

---

<a id="item-6"></a>
## [谷歌警告 AI 意识辩论可能政治化](https://decrypt.co/371800/google-ai-consciousness-debate-political) ⭐️ 8.0/10

Google DeepMind 发表了一篇题为《人工心智，人类分歧：AI 意识的政治学》的论文，认为关于 AI 意识的分歧可能蔓延到政治、法律和公共机构。 这很重要，因为它表明 AI 意识辩论不仅是哲学问题，还可能产生现实的政治和法律后果，影响监管和公共政策。 该论文于 2026 年 6 月 15 日由 Google DeepMind 的 Adam Bales 和 Iason Gabriel 发布在 SSRN 上，并强调社会讨论必须在处理这一分歧中发挥核心作用。

rss · Decrypt · Jun 22, 19:30

**背景**: AI 系统是否能有意识的问题在哲学和科学界长期存在争议。近期 AI 能力的进步重新引发了兴趣，一些研究人员认为当前的 AI 可能已经具有意识。然而，对于如何衡量或定义机器意识尚无共识。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepmind.google/research/publications/248131/">Artificial Minds, Human Disagreement: The Politics of AI Consciousness — Google DeepMind</a></li>
<li><a href="https://www.abovethenormnews.com/2026/06/17/google-deepmind-ai-consciousness/">Google DeepMind Researchers Warn the AI Consciousness Question Cannot Be Settled by Evidence</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1364661325002864">Identifying indicators of consciousness in AI systems</a></li>

</ul>
</details>

**标签**: `#AI ethics`, `#AI consciousness`, `#policy`, `#Google DeepMind`, `#societal impact`

---

<a id="item-7"></a>
## [Taiko L2 桥接漏洞：170 万美元被盗，用户被敦促撤资](https://decrypt.co/371769/ethereum-layer-2-taiko-withdraw-bridge-funds-security-breach) ⭐️ 8.0/10

以太坊 Layer-2 网络 Taiko 确认发生安全漏洞，攻击者利用其证明验证系统的缺陷，从其桥接中盗取了超过 170 万美元。团队已敦促用户从 Taiko 上部署的所有桥接中提取资金。 此事件凸显了 Layer-2 桥接安全中的关键漏洞，尤其是在证明验证机制方面，可能会削弱用户对 Taiko 及类似 Rollup 解决方案的信任。它也强调了跨链桥接持续存在的风险，这些桥接一直是黑客的频繁攻击目标。 该漏洞涉及伪造的证明，绕过了以太坊主网验证，无需任何真实的链上事件，盗取了 170 万美元。攻击者利用了 Taiko 的无许可 SGX 证明者注册系统提交无效证明。

rss · Decrypt · Jun 22, 15:31

**背景**: Taiko 是一个以太坊 Layer-2 Rollup，旨在提供可扩展性同时继承以太坊的安全性。桥接是允许用户在 Layer 1（以太坊）和 Layer 2 网络之间转移资产的智能合约。证明验证是一个关键组件，确保 Layer 2 上的交易在最终确定到以太坊之前是有效的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/371769/ethereum-layer-2-taiko-withdraw-bridge-funds-security-breach">Ethereum Layer-2 Taiko Warns Users to Withdraw Bridge Funds After Security Breach - Decrypt</a></li>
<li><a href="https://www.coingabbar.com/en/crypto-currency-news/ethereum-taiko-hack-confirmed-17m-drained-bridge-exploit-2026">Taiko Hack 2026: How Attackers Drained $1.7M Using Fake Bridge...</a></li>
<li><a href="https://www.cryptowisser.com/news/taiko-rollup-confirms-bridge-exploit-after-chain-state-verification-compromise/">Taiko Rollup Confirms Bridge Exploit After Chain State Verification ...</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#Layer-2`, `#Security`, `#Bridge`, `#Exploit`

---

<a id="item-8"></a>
## [FUTO Swipe：开源滑行输入模型](https://swipe.futo.tech/) ⭐️ 7.0/10

FUTO Swipe 是一个新的开源滑行输入模型，采用字典约束的束搜索来提高准确率并减少单词重叠，模型以 FUTO 模型许可证发布，推理库采用 GPL 许可证。 这是第一个实用的免费开源滑行输入模型，使得在 iOS 和 Android 之外的平台（如 VR 或新操作系统）上实现滑行输入成为可能，并解决了滑行输入中长期存在的准确性问题。 模型预测需要字典约束的束搜索来找到最可能的单词候选，推理库用 C++ 编写。该项目还通过一个网站收集训练数据，用户每次滑动一个单词。

hackernews · futohq · Jun 23, 17:50 · [社区讨论](https://news.ycombinator.com/item?id=48648619)

**背景**: 滑行输入允许用户通过在键盘上滑动手指而不抬起手指来输入单词，这比点击更快，但经常存在准确性问题，尤其是在相似单词或双写字母方面。大多数现有的滑行输入解决方案是专有的，限制了它们在非主流平台上的可用性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://swipe.futo.tech/">FUTO Swipe</a></li>
<li><a href="https://news.ycombinator.com/item?id=48648619">FUTO Swipe – A new swipe typing model | Hacker News</a></li>
<li><a href="https://swipe.futo.org/">FUTO Keyboard Swipe Training</a></li>

</ul>
</details>

**社区讨论**: 社区成员对开源模型表示兴奋，一些人指出在最近的更新后它感觉和 Gboard 一样好。然而，用户报告了随机大写和缺乏上下文感知等问题，iOS 用户则感叹缺乏好的自定义滑行键盘。

**标签**: `#keyboard`, `#swipe typing`, `#mobile input`, `#open source`

---

<a id="item-9"></a>
## [Meta 因数据泄露暂停员工追踪计划](https://www.wired.com/story/meta-pauses-employee-tracking-program-following-internal-security-breach/) ⭐️ 7.0/10

Meta 已暂停其名为“模型能力倡议”的员工追踪计划，此前一次内部数据泄露暴露了员工的私人对话和绩效数据。 这一事件引发了对 Meta 内部员工隐私和信任的严重担忧，并凸显了使用员工数据训练 AI 系统所涉及的更广泛的伦理问题。 该计划通过追踪公司笔记本电脑上的鼠标移动和按键来训练 AI，泄露的数据包括明文形式的私人对话和绩效信息。

hackernews · 1vuio0pswjnm7 · Jun 24, 00:28 · [社区讨论](https://news.ycombinator.com/item?id=48653575)

**背景**: Meta 于今年四月启动了“模型能力倡议”，旨在收集员工行为数据以训练 AI 操作计算机软件。超过 1600 名员工签署请愿书抗议该监控行为，但 Meta 一直持续到数据泄露才被迫暂停。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wired.com/story/meta-pauses-employee-tracking-program-following-internal-security-breach/">Meta Pauses Employee-Tracking Program Following Internal Data Leak</a></li>
<li><a href="https://www.wired.com/story/meta-accidentally-let-employees-access-each-others-keystroke-data/">Meta Exposed Data Internally From Its Controversial... | WIRED</a></li>
<li><a href="https://www.msn.com/en-in/technology/cybersecurity/meta-to-pause-tracking-mouse-movements-keystrokes-of-employees-after-internal-data-leak/ar-AA26iAVQ">Meta to pause tracking mouse movements, keystrokes of employees...</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了愤怒，有人称 Meta 是“最无耻的公司”，还有人质疑如果 Meta 这样对待自己的员工，它会对用户数据做什么。一些人指出，这次泄露讽刺地证实了员工对该计划的担忧。

**标签**: `#privacy`, `#surveillance`, `#Meta`, `#data leak`, `#ethics`

---

<a id="item-10"></a>
## [维生素 D 益处真实但被过度炒作](https://dynomight.net/vitamin-d/) ⭐️ 7.0/10

一篇详细分析指出，维生素 D 补充剂仅对严重缺乏者有益，而普遍补充的炒作缺乏有力证据。 这很重要，因为维生素 D 是最广泛补充的维生素之一，该分析有助于厘清证据强弱的领域，从而影响公共卫生建议和个人选择。 文章批评了研究局限性，如 NHANES 数据中的季节和纬度偏差，并指出许多建议基于不同研究置信区间合并时的错误数学计算。

hackernews · surprisetalk · Jun 23, 16:30 · [社区讨论](https://news.ycombinator.com/item?id=48647486)

**背景**: 维生素 D 对骨骼健康和免疫功能至关重要，缺乏可导致佝偻病或骨软化症。许多人基于广泛健康益处的声称而补充维生素 D，但大型随机试验并未一致显示对普通人群有益。

**社区讨论**: 评论者称赞了平衡的分析，其中一位指出，当研究不符合炒作时，健康影响者转而声称普遍缺乏。其他人提出了关于建议中的错误数学计算以及维生素 K2 在吸收中的潜在作用。

**标签**: `#nutrition`, `#vitamin D`, `#evidence-based medicine`, `#health research`, `#science communication`

---

<a id="item-11"></a>
## [极端高温会议因高温警告取消](https://www.lse.ac.uk/granthaminstitute/events/extreme-heat-improving-governance-and-strengthening-action-around-the-world/) ⭐️ 7.0/10

一场名为“极端高温：改善治理和加强全球行动”的会议因举办地发布极端高温警告而被取消。 此次取消凸显了应对气候变化的同时直接受其影响的讽刺和实际挑战，引发了关于空调普及、建筑设计以及热适应文化差异的讨论。 该会议由伦敦政治经济学院格兰瑟姆研究所与苏黎世气候韧性联盟合作举办，原定以“炉边谈话”结束。

hackernews · rendx · Jun 23, 23:26 · [社区讨论](https://news.ycombinator.com/item?id=48653060)

**背景**: 由于气候变化，极端高温事件变得更加频繁和强烈。空调是一些地区常见的适应措施，但其普及程度因文化和经济而异，且会增加能源需求和排放。

**社区讨论**: 评论者指出，因高温取消气候韧性会议具有讽刺意味，有人批评欧洲对空调的抵制，也有人指出凉爽气候下的建筑并非为这种温度设计。还有人引用了 Alanis Morissette 的歌曲《Ironic》。

**标签**: `#climate change`, `#public policy`, `#infrastructure`, `#irony`

---

<a id="item-12"></a>
## [以太坊基金会将削减 40%预算进行重大重组](https://www.coindesk.com/tech/2026/06/23/vitalik-buterin-says-ethereum-foundation-will-cut-budget-40-in-major-reset) ⭐️ 7.0/10

Vitalik Buterin 宣布，以太坊基金会将削减 40%的预算并裁减 54 个工作岗位（占员工总数的 20%），作为重大组织重组的一部分，重组为五个专注的集群：协议层、接入层、用户层、社区层和机构层。 这一重大预算削减标志着以太坊基金会向更精简的捐赠基金模式进行战略转变，可能影响以太坊开发速度及更广泛的区块链生态系统。这反映了持续的内部挑战，以及提高效率并专注于核心协议中立性的努力。 此次重组是在一系列领导层离职之后进行的，包括长期贡献者 Josh Stark 和 Trent Van Epps 于 4 月离职。新的五集群结构旨在实现协议开发、用户接入、社区参与和机构采用方面的具体目标。

rss · CoinDesk · Jun 23, 15:00

**背景**: 以太坊基金会是一个支持以太坊生态系统的非营利组织。它曾因效率低下和缺乏重点而受到批评。预算削减和重组是精简运营、确保长期可持续性的更广泛努力的一部分，转向捐赠基金模式，即基金会依靠其资金库而非持续筹款来运营。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thedefiant.io/news/blockchains/ethereum-foundation-cuts-20-of-staff-in-sweeping-reorganization">Ethereum Foundation Cuts Budget 40% in Sweeping Restructuring - "The Defiant"</a></li>
<li><a href="https://decrypt.co/371864/ethereum-foundation-cuts-20-of-workforce-in-leaner-reorganization">Ethereum Foundation Cuts 20% of Workforce in 'Leaner' Reorganization - Decrypt</a></li>
<li><a href="https://www.theblock.co/post/405809/ethereum-foundation-cuts-20-of-its-workforce-as-new-5-cluster-structure-takes-shape">Ethereum Foundation cuts 20% of its workforce as new 5-cluster structure takes shape | The Block</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#blockchain`, `#cryptocurrency`, `#organizational change`

---

<a id="item-13"></a>
## [OpenAI GPT-5.5-Cyber 登顶排行榜，击败被禁的 Anthropic 模型](https://decrypt.co/371900/openai-gpt-5-5-cyber-ai-beats-anthropic-banned-claude-mythos) ⭐️ 7.0/10

OpenAI 的 GPT-5.5-Cyber 在 CyberGym 排行榜上取得第一名，超越了因特朗普政府出口禁令而被禁用的 Anthropic 的 Claude Mythos 模型。 这一进展凸显了 AI 网络安全领域日益激烈的竞争以及出口管制的 geopolitical 影响——一个被禁用的模型被美国本土的竞争对手超越。 CyberGym 排行榜评估 AI 代理在真实漏洞发现和利用任务上的表现；GPT-5.5-Cyber 目前领先，而 Claude Mythos 因禁令仍处于离线状态。

rss · Decrypt · Jun 23, 18:59

**背景**: CyberGym 是一个基准测试平台，用于衡量 AI 代理处理网络安全任务（如发现和利用漏洞）的能力。Anthropic 的 Claude Mythos 是一款具有高级推理能力的前沿模型，但因特朗普政府的出口禁令而被限制使用。OpenAI 的 GPT-5.5-Cyber 是 GPT-5.5 的专用变体，针对网络操作进行了优化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cybergym.io/">CyberGym</a></li>
<li><a href="https://llm-stats.com/benchmarks/cybergym">CyberGym Leaderboard - LLM Stats</a></li>

</ul>
</details>

**标签**: `#AI`, `#cybersecurity`, `#OpenAI`, `#Anthropic`, `#export ban`

---

<a id="item-14"></a>
## [美国参议院通过住房法案，附带四年美联储 CBDC 禁令](https://decrypt.co/371848/us-senate-passes-housing-bill-with-four-year-fed-cbdc-ban) ⭐️ 7.0/10

美国参议院周一以 85 票对 5 票通过了一项两党住房法案，其中包含一项条款，禁止美联储在 2030 年 12 月 31 日之前发行零售央行数字货币（CBDC）。该法案现已提交众议院审议。 这项立法是一项重大的政策举措，可能会推迟或阻止美国数字美元的推出，影响全球 CBDC 格局和数字支付的未来。两党的支持表明对美联储发行数字货币存在强烈的政治反对，这可能会影响其他国家发展 CBDC 的方式。 该禁令专门适用于零售 CBDC，即向公众开放的数字美元，有效期至 2030 年 12 月 31 日，之后国会可以延长、永久化或允许发行。CBDC 条款被附加在一项住房可负担性法案中，而非独立的加密货币法案，这反映了一种战略性的立法策略。

rss · Decrypt · Jun 23, 10:23

**背景**: 央行数字货币（CBDC）是由中央银行直接发行的数字形式的主权货币，在法律上等同于实物现金。美联储一直在通过研究和实验探索 CBDC 的潜在好处和风险，但尚未决定是否发行。CBDC 的批评者担心隐私、政府监控以及可能扰乱银行体系的问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.securities.io/federal-reserve-digital-dollar-cbdc-explained/">Digital Dollar Explained : Why the Fed Is Studying a CBDC</a></li>
<li><a href="https://www.mexc.com/news/914774">U.S. Senate Passes Bill Banning Fed CBDC Issuance... | MEXC News</a></li>
<li><a href="https://www.spendnode.io/blog/us-senate-housing-bill-cbdc-ban-2030-june-2026/">US Senate Passes Housing Bill With a Federal CBDC Ban Through...</a></li>

</ul>
</details>

**标签**: `#CBDC`, `#regulation`, `#US politics`, `#digital currency`, `#blockchain`

---

<a id="item-15"></a>
## [特朗普下令加速量子就绪，比特币面临风险](https://decrypt.co/371807/trump-quantum-orders-accelerate-security-bitcoin-faces-risk) ⭐️ 7.0/10

美国总统唐纳德·特朗普签署了两项行政命令，旨在扩大美国量子计算能力并加速向抗量子加密的过渡。 此举直接影响网络安全和比特币，因为量子计算可能破解现有加密标准，从而危及比特币的安全性。 这些行政命令既关注推进量子计算技术，也要求联邦系统采用后量子密码学（PQC）。

rss · Decrypt · Jun 22, 19:57

**背景**: 量子计算对传统加密方法（包括保护比特币的方法）构成重大威胁。抗量子加密，也称为后量子密码学（PQC），旨在抵御量子计算机的攻击。专家们对威胁的时间线存在争议，但许多人认为威胁是真实且正在逼近的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/advice/0/how-can-you-make-your-encryption-protocols-tgahe">Quantum - Resistant Encryption Protocols: What, Why, and How</a></li>
<li><a href="https://www.daydreamsoft.com/blog/quantum-resistant-encryption-in-mobile-apps-preparing-today-for-tomorrows-cyber-threats">Quantum - resistant encryption in mobile apps is becoming essential...</a></li>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2pCNmRDaURoSDNrSjdLN2FoQ29pZ0FQAQ?hl=en-GB&gl=GB&ceid=GB:en">Experts warn of potential threats to Bitcoin from quantum computing ...</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#encryption`, `#cybersecurity`, `#Bitcoin`, `#policy`

---

<a id="item-16"></a>
## [致敬拼写检查波浪线的创造者](https://devblogs.microsoft.com/oldnewthing/20260622-00/?p=112451) ⭐️ 6.0/10

Raymond Chen 的文章向 Tony Krueger 致敬，他是实现 Microsoft Word 中拼写检查红色和绿色波浪下划线的开发者。 这一功能成为文字处理中无处不在的一部分，通过实时反馈拼写和语法错误，改变了用户与文本交互的方式。 波浪下划线最初由 Tony Krueger 从另一个平台移植而来，文章指出维基百科对此事实的证据现在循环引用了 Chen 自己的文章。

hackernews · saikatsg · Jun 23, 18:10 · [社区讨论](https://news.ycombinator.com/item?id=48648959)

**背景**: 拼写检查波浪线是文字处理器中出现在拼写错误（红色）或语法错误（绿色）下方的彩色下划线。它们提供即时视觉反馈，而不中断用户的工作流程。

**社区讨论**: 评论者觉得维基百科的循环引用很有趣，称赞文章突出了一个小而影响深远的决定，并指出在多语言环境中波浪线可能令人烦恼。一位评论者开玩笑地希望有黄色波浪线来表示逻辑错误。

**标签**: `#software history`, `#Microsoft`, `#spell check`, `#user interface`

---

<a id="item-17"></a>
## [凯文·米特尼克赠车给曾助其入狱者](https://www.thedrive.com/news/this-man-was-gifted-his-dream-car-by-the-notorious-hacker-he-put-in-prison) ⭐️ 6.0/10

著名黑客凯文·米特尼克将他梦想的汽车赠予曾帮助将他送进监狱的肖恩·纳利，两人因此建立了非同寻常的友谊。 这个故事凸显了人际关系的复杂性和救赎的可能性，表明即使是曾经的对手也能成为朋友。它也强调了米特尼克在黑客身份之外的遗产——一个能够宽恕和慷慨的人。 这辆车是 1995 年的保时捷 911，也是米特尼克自己的梦想之车。纳利曾担任安全顾问，并在 1995 年米特尼克的抓捕中发挥了作用。

hackernews · mauvehaus · Jun 22, 18:03 · [社区讨论](https://news.ycombinator.com/item?id=48633643)

**背景**: 凯文·米特尼克是一名臭名昭著的黑客，在 1995 年经过一场高度公开的联邦调查局追捕后被逮捕。他服刑五年，后来成为受人尊敬的安全顾问和作家。肖恩·纳利是帮助追踪他的团队成员之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kevin_Mitnick">Kevin Mitnick</a></li>

</ul>
</details>

**社区讨论**: 评论反映了对米特尼克的复杂看法：一些人赞扬他的影响力和著作，而另一些人则质疑他的技术能力。George Hotz 指出米特尼克的书籍对他影响很大，许多人对其去世表示悲伤。

**标签**: `#Kevin Mitnick`, `#hacking`, `#human-interest`, `#security`

---

<a id="item-18"></a>
## [Chainlink 与 47 家银行合作加速跨境支付](https://www.coindesk.com/markets/2026/06/23/chainlink-teams-up-with-47-south-korean-european-banks-to-speed-up-international-money-transfers) ⭐️ 6.0/10

Chainlink 与韩国和欧洲的 47 家银行合作，利用其区块链预言机网络加速国际汇款。 此次合作标志着传统银行业在采用区块链方面迈出了重要一步，有望将转账时间从几天缩短到几分钟，并降低消费者和企业的成本。 该集成利用 Chainlink 的去中心化预言机网络，安全地将银行系统与区块链网络连接起来，实现实时结算和透明度。

rss · CoinDesk · Jun 23, 15:40

**背景**: Chainlink 是一个去中心化的区块链预言机网络，使智能合约能够安全地与链外数据交互。传统的国际汇款涉及多个中介，导致延迟和高额费用。像 Chainlink 这样的基于区块链的解决方案旨在通过提供防篡改的数据馈送和自动结算来简化这一过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chainlink_(blockchain_oracle)">Chainlink ( blockchain oracle ) - Wikipedia</a></li>
<li><a href="https://chain.link/">Chainlink : The Industry-Standard Oracle Platform</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#chainlink`, `#banking`, `#payments`

---

<a id="item-19"></a>
## [富兰克林坦伯顿完成 250 Digital 收购，成立加密部门](https://www.coindesk.com/business/2026/06/23/franklin-templeton-closes-250-digital-acquisition-deal-and-sets-up-new-franklin-crypto-division) ⭐️ 6.0/10

富兰克林坦伯顿已完成对主动加密投资管理公司 250 Digital 的收购，并成立了一个名为 Franklin Crypto 的新部门，专注于数字资产投资。 这家大型传统资产管理公司的举措标志着机构对加密货币的采用日益增长，并可能为更多主流金融公司进入加密领域铺平道路。 此次收购价值 2.5 亿美元，新的 Franklin Crypto 部门将专注于主动管理的加密货币投资策略，合并两家公司的团队。

rss · CoinDesk · Jun 23, 12:35

**背景**: 富兰克林坦伯顿是一家全球投资管理公司，管理资产超过 1.5 万亿美元。250 Digital 是一家运营主动加密投资策略的公司。该交易于 2026 年 4 月首次宣布，并在第二季度完成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/06/23/franklin-templeton-closes-250-digital-acquisition-deal-and-sets-up-new-franklin-crypto-division">Franklin Templeton closes 250 Digital acquisition deal and sets up...</a></li>
<li><a href="https://www.briefs.co/news/franklin-templeton-builds-crypto-division-uses-blockchain-tokens-to-pay-for-it/">Franklin Templeton Builds Crypto Division , Uses... - Briefs Finance</a></li>
<li><a href="https://financefeeds.com/franklin-templeton-completes-250-digital-acquisition-to-launch-crypto-unit/">Franklin Templeton Completes 250 Digital Acquisition to Launch...</a></li>

</ul>
</details>

**标签**: `#crypto`, `#institutional adoption`, `#finance`, `#acquisition`

---

<a id="item-20"></a>
## [Qwable：免费本地模型模仿 Claude Fable 的推理风格](https://decrypt.co/371914/meet-qwable-free-local-model-thinks-like-claude-fable) ⭐️ 6.0/10

一个名为 Qwable 的 Qwen 模型微调版本，复制了 Anthropic 的 Claude Fable 5 的推理风格，并且可以免费在本地运行。此外，还有一个修改版本移除了模型内置的良知或安全约束。 这表明专有模型的高级推理风格可以被蒸馏到开源模型中，使其无需 API 成本或互联网依赖即可使用。移除良知的做法引发了关于无限制 AI 行为的伦理问题。 该模型基于 Qwen，这是阿里云开发的开源大语言模型系列。微调针对的是 Claude Fable 5 的推理模式，Anthropic 称其达到高级研究科学家水平。

rss · Decrypt · Jun 23, 22:01

**背景**: Claude Fable 5 是 Anthropic 的专有 AI 模型，以其强大的推理和面向任务的思维而闻名。Qwen 是一个开源 LLM 系列，可以针对特定任务进行微调。微调是利用额外数据使预训练模型适应新能力的过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable - Anthropic</a></li>
<li><a href="https://huggingface.co/Aniq-63/qwen3-0.6B-recipe-finetuned">Aniq-63/ qwen 3-0.6B-recipe-finetuned · Hugging Face</a></li>

</ul>
</details>

**标签**: `#AI`, `#fine-tuning`, `#open-source`, `#local model`

---

<a id="item-21"></a>
## [特朗普量子政策获赞，比特币尚未准备好](https://decrypt.co/371916/trump-quantum-praise-experts-warn-bitcoin-not-ready) ⭐️ 6.0/10

特朗普总统于 6 月 22 日签署了两项行政命令，旨在加速美国量子技术发展并推动联邦政府向抗量子密码学过渡。行业领袖对此表示赞赏，但专家警告称，比特币的基础设施尚未为后量子安全做好准备。 这一政策推动表明量子威胁的紧迫性日益增加，量子计算机最终可能破坏比特币及其他加密货币的密码学基础。加速的时间表迫使加密行业在量子计算机成为实际威胁之前采用后量子安全措施。 这些行政命令既注重推动国内量子计算研究，也要求联邦机构更快地迁移到抗量子密码学。然而，比特币当前的协议依赖于椭圆曲线密码学（ECDSA），该算法易受在足够强大的量子计算机上运行的 Shor 算法攻击。

rss · Decrypt · Jun 23, 21:31

**背景**: 量子计算机利用量子力学原理，能够以指数级速度解决某些问题。足够强大的量子计算机可以通过 Shor 算法破解广泛使用的公钥密码学，包括比特币使用的 ECDSA。抗量子密码学（PQC）是指旨在抵抗经典和量子攻击的密码算法。“先收集，后解密”策略是指攻击者现在收集加密数据，意图在量子计算机可用时进行解密。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.dw.com/en/us-trump-signs-new-executive-orders-to-boost-quantum-computing/a-77665653">Trump signs new executive orders to boost quantum computing</a></li>
<li><a href="https://www.meritalk.com/articles/quantum-executive-orders-send-clear-signals-experts-say/">Quantum Executive Orders Send Clear Signals, Experts Say</a></li>
<li><a href="https://cyberscoop.com/trump-executive-order-post-quantum-encryption-deadline/">Trump executive orders speed up post- quantum ... | CyberScoop</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#bitcoin`, `#cryptocurrency`, `#post-quantum security`, `#policy`

---

<a id="item-22"></a>
## [AI 代理在《文明 VI》中造核弹仍输](https://decrypt.co/371877/ai-agent-nuclear-strike-civilization-vi-benchmark) ⭐️ 6.0/10

一项测试《文明 VI》中战略推理能力的新基准显示，AI 代理花费 50 回合研发核武器以对抗对手的文化胜利，但最终仍输掉了游戏。 这一结果凸显了当前 AI 在战略推理方面的局限性，尤其是在复杂的长期规划场景中，并强调了需要更好的基准来评估 AI 决策能力。 该 AI 代理旨在通过玩回合制策略游戏《文明 VI》来测试战略推理，其研发核武器的决定是为了应对对手文明即将取得的文化胜利。

rss · Decrypt · Jun 23, 18:33

**背景**: 《文明 VI》是一款 4X 回合制策略游戏，玩家建立帝国并通过多种条件获胜，包括文化胜利。文化胜利要求一个文明吸引的游客数量超过其他任何文明的国内游客，通常通过伟人和奇观实现。AI 代理的失败表明，即使是先进的 AI 也难以进行多步骤战略规划和长期目标优先级排序。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Civilization_VI">Civilization VI - Wikipedia</a></li>
<li><a href="https://www.keengamer.com/articles/guides/civilization-vi-cultural-victory-guide/">Civilization VI Cultural Victory Guide - KeenGamer</a></li>

</ul>
</details>

**标签**: `#AI`, `#benchmark`, `#strategic reasoning`, `#gaming`

---

<a id="item-23"></a>
## [ICE 与 OKX 成立合资企业推动代币化证券](https://decrypt.co/371789/new-york-stock-exchange-ice-okx-crypto-tokenized-securities) ⭐️ 6.0/10

纽约证券交易所母公司洲际交易所（ICE）与加密货币交易所 OKX 宣布成立合资企业，旨在推进代币化证券和数字资产基础设施，由前纽约州州长戴维·帕特森共同担任主席。 此次合作连接了传统金融与加密货币，可能加速代币化证券在华尔街的采用，并通过受监管框架将基于区块链的资产带给主流投资者。 该合资企业将专注于构建股票和债券等现实世界资产代币化的基础设施，利用 ICE 的市场专业知识和 OKX 的区块链技术。前纽约州州长的参与表明其致力于推动监管清晰度。

rss · Decrypt · Jun 22, 18:00

**背景**: 代币化证券是将股票、债券等传统金融资产以数字代币形式记录在区块链上，可实现更快的结算、部分所有权和全天候交易。ICE 运营包括纽交所在内的主要交易所，而 OKX 是全球领先的加密货币交易所。此次合资旨在结合双方优势，创建一个受监管的数字证券平台。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://milkroad.com/guide/tokenized-securities/">What Are Tokenized Securities - Benefits, Examples, & Laws</a></li>
<li><a href="https://jayderenthal.medium.com/tokenized-securities-197b3d1f7317">Tokenized Securities . Growing Opportunity at the Intersection | Medium</a></li>
<li><a href="https://www.cube.exchange/what-is/tokenized-securities">What Are Tokenized Securities ? | Cube Exchange</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#digital assets`, `#crypto`, `#Wall Street`, `#joint venture`

---

<a id="item-24"></a>
## [谷歌投资 7500 万美元与 A24 合作 AI 电影制作研究](https://decrypt.co/371788/a24-ex-machina-now-researching-ai-google) ⭐️ 6.0/10

谷歌向独立电影制片厂 A24（曾出品《机械姬》和《瞬息全宇宙》）投资 7500 万美元，启动一项专注于开发电影制作工具的人工智能研究计划。 此次合作标志着大型科技公司致力于将 AI 融入创意产业，可能加速面向电影制作人的 AI 工具开发，并改变电影制作方式。 该投资是一项更广泛 AI 研究计划的一部分，但具体技术细节或交付成果尚未披露。A24 以广受好评的电影闻名，并曾在《机械姬》中探讨过 AI 主题。

rss · Decrypt · Jun 22, 17:29

**背景**: A24 是一家独立娱乐公司，制作过《月光男孩》和《原钻》等获奖影片。谷歌一直在开发用于创意应用的 AI 模型，如 Veo 和 Gemini，此次合作旨在探索这些模型如何辅助电影制作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://a24films.com/films">Films | A 24</a></li>
<li><a href="https://blog.google/innovation-and-ai/products/google-flow-veo-ai-filmmaking-tool/">Introducing Flow: Google’s AI filmmaking tool designed for Veo</a></li>

</ul>
</details>

**标签**: `#AI`, `#Google`, `#A24`, `#filmmaking`, `#investment`

---

<a id="item-25"></a>
## [英国央行用 400 亿英镑发行上限取代稳定币持有上限](https://decrypt.co/371783/bank-of-england-eases-stablecoin-rules-swaps-holding-caps-for-40b-guardrail) ⭐️ 6.0/10

英国央行取消了针对稳定币的个人持有上限，取而代之的是每个稳定币 400 亿英镑的临时发行上限，并允许发行方持有更多政府债务作为储备。 这一监管转变取消了个人和企业持有系统性稳定币的限制，可能推动英国稳定币的采用，同时通过发行上限维护金融稳定。 400 亿英镑的上限适用于每个稳定币而非每个持有者，英国央行现在允许更大比例的储备以政府债务形式持有，后者被视为更安全的资产。

rss · Decrypt · Jun 22, 16:43

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与英镑等法定货币挂钩。英国央行此前曾提议个人持有上限以降低金融稳定风险，但新方法转向总量发行上限，与国际标准演变保持一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://coindoo.com/bank-of-england-ends-user-limits-in-new-stablecoin-policy-shift/">Bank of England Ends User Limits in New Stablecoin Policy Shift</a></li>
<li><a href="https://coinfomania.com/why-the-bank-of-england-just-scrapped-stablecoin-ownership-limits/">Why the Bank of England Just Scrapped Stablecoin Ownership Limits</a></li>

</ul>
</details>

**标签**: `#stablecoin`, `#regulation`, `#crypto`, `#finance`

---

<a id="item-26"></a>
## [Meta 的扎克伯格计划推出预测市场应用](https://www.theblock.co/post/405838/meta-zuckerberg-to-build-prediction-market-app-polymarket-kalshi-nyt?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

据《纽约时报》报道，Meta 首席执行官马克·扎克伯格计划开发一款类似 Polymarket 和 Kalshi 的预测市场应用。 这标志着一家大型科技公司进入快速增长的预测市场领域，可能带来主流采用和监管审查。 该报道基于单一来源，缺乏技术细节；Polymarket 是基于加密货币的平台，而 Kalshi 受 CFTC 监管并以现金结算。

rss · The Block · Jun 23, 17:20

**背景**: 预测市场允许用户对未来事件（如选举结果或体育赛事结果）下注。Polymarket 使用区块链和加密货币，而 Kalshi 作为受监管的交易所运营。该市场的交易量已增长至数十亿美元。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kalshi">Kalshi - Wikipedia</a></li>

</ul>
</details>

**标签**: `#Meta`, `#prediction markets`, `#blockchain`, `#cryptocurrency`

---

<a id="item-27"></a>
## [美国司法部查封汇旺集团用于洗钱数十亿美元的云账户](https://www.theblock.co/post/405834/doj-seizes-huione-group-account-launder-billions?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

美国司法部查封了汇旺集团的一个云计算账户，该账户被用于洗钱数十亿美元的欺诈所得。此举是在美国金融犯罪执法网络根据《爱国者法案》将汇旺集团列为首要洗钱关注对象之后采取的。 此次查封切断了网络犯罪分子和欺诈者的主要金融渠道，展示了美国政府打击用于洗钱的云基础设施的能力。这也凸显了对与非法活动相关的柬埔寨金融实体日益严格的审查。 该云计算账户被用于处理和清洗来自诈骗和欺诈（包括杀猪盘）的所得。汇旺集团是一家柬埔寨企业集团，运营汇旺支付和加密货币交易所，并与柬埔寨执政家族有关联。

rss · The Block · Jun 23, 16:58

**背景**: 美国金融犯罪执法网络根据《爱国者法案》第 311 条将汇旺集团列为首要洗钱关注对象，该条款允许美国对涉及洗钱的外国金融机构采取特殊措施。汇旺集团是一家与洪氏家族（包括首相洪玛奈）有关联的柬埔寨金融集团。其服务包括支付平台汇旺支付和加密货币交易所汇旺加密货币，这些服务被用于促进非法资金流动。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Huione_Group">Huione Group</a></li>
<li><a href="https://home.treasury.gov/news/press-releases/tg1056">Fact Sheet: Overview of Section 311 of the USA PATRIOT Act</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#money laundering`, `#DOJ`, `#cloud computing`, `#financial crime`

---

<a id="item-28"></a>
## [OKX 欧洲 CEO：80%的加密货币交易所将无法通过 MiCA](https://www.theblock.co/post/405777/okx-europe-chief-mica-deadline-nears?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

OKX 欧洲首席执行官 Erald Ghoos 预测，到 7 月 1 日截止日期前，80%的加密货币交易所将无法遵守欧盟的《加密资产市场法规》（MiCA），因为 ESMA 将迫使无牌公司停止在欧盟运营。 这一预测预示着加密货币交易所行业将出现重大整合，可能减少竞争并增加剩余参与者的合规成本，同时也为全球加密货币监管树立了先例。 MiCA 是欧盟首个针对加密资产的全面监管框架，涵盖发行、交易和托管。7 月 1 日的截止日期适用于现有的加密资产服务提供商（CASP），它们必须获得许可证才能继续在欧盟运营。

rss · The Block · Jun 23, 13:31

**背景**: MiCA（加密资产市场法规）是一项欧盟法规，旨在为各成员国的加密资产建立统一规则，以保护投资者并确保市场诚信。该法规于 2023 年通过，正在分阶段实施，预计 2025 年全面适用。ESMA（欧洲证券和市场管理局）是负责监督 MiCA 实施的欧盟监管机构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Markets_in_Crypto-Assets">Markets in Crypto-Assets - Wikipedia</a></li>
<li><a href="https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica">Markets in Crypto-Assets Regulation (MiCA)</a></li>

</ul>
</details>

**标签**: `#crypto`, `#regulation`, `#MiCA`, `#exchanges`

---

<a id="item-29"></a>
## [Strategy Inc. 的比特币财库面临首次重大考验](https://www.theblock.co/post/405791/strategy-the-capital-stack-meets-a-falling-bitcoin-price?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Strategy Inc.（前身为 MicroStrategy）在比特币价格下跌之际，其比特币财库模式面临首次真正考验。该公司持有 847,363 枚比特币，总购入成本为 641 亿美元，平均购入价格为 75,651 美元。 这一考验意义重大，因为 Strategy Inc. 是最大的企业比特币持有者，其通过债务和股权融资购买比特币的模式，若比特币价格持续下跌，可能面临严重压力。结果可能影响其他考虑类似比特币财库策略的公司。 该公司的资本堆栈包括可转换债券、股权及其他融资工具，随着比特币价格跌破平均购入成本，这些工具正受到审视。该报告分析了资本堆栈的不同层级可能受到的影响。

rss · The Block · Jun 23, 13:24

**背景**: 资本堆栈指投资于公司的所有资本结构，包括具有不同风险和回报特征的债务和股权层级。Strategy Inc. 自 2020 年以来积极积累比特币，利用债券发行和股权销售所得，将其公司财库转变为比特币投资工具。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.foreignpolicyjournal.com/2026/05/24/strategy-inc-nasdaq-mstr-falls-to-163-as-bitcoin-treasury-model-draws-fresh-scrutiny/">Strategy Inc . (NASDAQ: MSTR) Falls to $163 as Bitcoin Treasury ...</a></li>
<li><a href="https://www.tipranks.com/news/company-announcements/strategy-incorporated-leans-into-bitcoin-treasury-model">Strategy Incorporated Leans Into Bitcoin Treasury Model</a></li>
<li><a href="https://equitymultiple.com/blog/capital-stack">Capital Stack: How It Works, What to Know - EquityMultiple</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#Corporate Treasury`, `#MicroStrategy`, `#Market Analysis`

---