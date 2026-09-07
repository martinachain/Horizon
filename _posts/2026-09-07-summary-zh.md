---
layout: default
title: "Horizon Summary: 2026-09-07 (ZH)"
date: 2026-09-07
lang: zh
---

> From 29 items, 10 important content pieces were selected

---

1. [AI 生成 1300 万行证明，攻克费马大定理](#item-1) ⭐️ 9.0/10
2. [Anubis 历经一年努力推出 WebAssembly 工作量证明](#item-2) ⭐️ 8.0/10
3. [GrapheneOS 计划全面改造默认应用和安全剪贴板](#item-3) ⭐️ 8.0/10
4. [OpenAI 内部视角：自动化 AI 研究与递归自我改进](#item-4) ⭐️ 8.0/10
5. [OpenAI GPT-6 Astra 在多个领域给早期测试者留下深刻印象](#item-5) ⭐️ 8.0/10
6. [Liquid Network 因 3.2 亿美元比特币提款而暂停](#item-6) ⭐️ 8.0/10
7. [用 1024 字节 C 语言实现 Python 解释器](#item-7) ⭐️ 7.0/10
8. [Nitter 和 XCancel 在获得法律建议后恢复服务](#item-8) ⭐️ 7.0/10
9. [谷歌修复 Chrome V8 引擎中被积极利用的零日漏洞](#item-9) ⭐️ 7.0/10
10. [Better 与 Coinbase 推出可复用抵押品的比特币抵押贷款](#item-10) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [AI 生成 1300 万行证明，攻克费马大定理](https://decrypt.co/377491/ai-solved-350-year-old-math-problem) ⭐️ 9.0/10

据报道，Anthropic 的 Claude 在 11 天内生成了 1300 万行机器可检查的证明，解决了费马大定理，标志着 AI 驱动数学的潜在里程碑。 这一说法表明 AI 能够解决困扰人类数百年的问题，可能改变数学证明的发现和验证方式。如果得到证实，它可能加速数学及相关领域的研究，但因其非凡性质，需要仔细验证。 该证明是机器可检查的，意味着计算机可以在无需人类信任的情况下验证它，据报道生成耗时 11 天。其规模——1300 万行——远超人类生成的证明，如 Andrew Wiles 在 1994 年的证明，后者约 100 页。

rss · Decrypt · Sep 5, 13:01

**背景**: 费马大定理由皮埃尔·德·费马于 1637 年提出，断言对于任何大于 2 的整数 n，不存在正整数 a、b、c 满足 a^n + b^n = c^n。直到 1994 年 Andrew Wiles 的证明才解决，该证明依赖于高等数学。机器可检查的证明是由证明助手或自动定理证明器验证的形式化证明，通过计算机验证确保正确性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Proof_assistant">Proof assistant - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Automated_theorem_proving">Automated theorem proving - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Fermat's_Last_Theorem">Fermat's Last Theorem - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI`, `#mathematics`, `#proof`, `#Anthropic`, `#Fermat's Last Theorem`

---

<a id="item-2"></a>
## [Anubis 历经一年努力推出 WebAssembly 工作量证明](https://anubis.techaro.lol/blog/2026/anubis-wasm/) ⭐️ 8.0/10

经过一年的努力，Anubis 在其下一版本中推出了基于 WebAssembly 的可选工作量证明检查，并为旧浏览器提供了 JavaScript 回退。该集成涉及用 Rust 重写 Anubis 的部分代码，并克服了重大的工程挑战。 此次更新增强了 Anubis 的机器人防护能力，同时保持了向后兼容性，这对智能电视等旧设备的用户至关重要。这也凸显了 WebAssembly 在服务器端和安全关键应用中的日益普及，以及社区反馈在开源开发中的重要性。 WebAssembly 检查是可选的，管理员可以在阈值或机器人规则中启用。该项目以 Chrome 66 为向后兼容目标，JavaScript 回退确保了不支持 WebAssembly 的浏览器上的功能。

hackernews · xena · Sep 6, 20:32 · [社区讨论](https://news.ycombinator.com/item?id=49590611)

**背景**: Anubis 是一个开源反机器人系统，通过工作量证明挑战来保护网站免受自动化流量的侵害。WebAssembly（Wasm）是一种二进制指令格式，可在浏览器中实现高性能执行，并设计为向后兼容。将 Wasm 集成到 Anubis 中，与仅使用 JavaScript 的实现相比，可以实现更高效、更安全的工作量证明计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://anubis.techaro.lol/blog/2026/anubis-wasm/">It took a year to ship WebAssembly in Anubis | Anubis</a></li>
<li><a href="https://runtimewire.com/article/anubis-webassembly-proof-of-work-xe-iaso">Anubis ships opt-in WebAssembly checks after a year of work</a></li>
<li><a href="https://webassembly.org/">WebAssembly</a></li>

</ul>
</details>

**社区讨论**: 社区评论赞扬了维护者对向后兼容性的投入以及对开源维护者待遇的诙谐语气。一些用户对浏览器中禁用 WebAssembly 表示担忧，而另一些用户则建议使用符合时代背景的工具链进行兼容性测试。总体情绪积极，对工程努力和周到的设计选择表示赞赏。

**标签**: `#WebAssembly`, `#Open Source`, `#Backward Compatibility`, `#Engineering`, `#Community`

---

<a id="item-3"></a>
## [GrapheneOS 计划全面改造默认应用和安全剪贴板](https://grapheneos.social/@GrapheneOS/117225539756835649) ⭐️ 8.0/10

GrapheneOS 宣布计划全面改造或替换默认的 AOSP 应用，包括新的安全剪贴板和未来支持 MLS 加密的 RCS，旨在减少对 Google 服务的依赖。该公告在 Mastodon 上发布，并引发了社区的热烈讨论。 这一举措对于希望避免依赖 Google 的注重隐私的用户意义重大，因为它可能提供 Google Messages 和其他默认应用的完全开源替代品。这也符合消息传递中端到端加密的更广泛行业趋势，正如 GSMA 最近的 RCS 规范所示。 安全剪贴板功能是计划中的全面改造的一部分，但细节尚未完全明确。GrapheneOS 还计划替换过时的 AOSP 图库，可能还有 AOSP 键盘，并且最近招聘了新员工以加速进展。

hackernews · Cider9986 · Sep 6, 20:24 · [社区讨论](https://news.ycombinator.com/item?id=49590512)

**背景**: GrapheneOS 是一个基于 Android 的开源、注重隐私的移动操作系统，适用于 Google Pixel 设备。RCS（富通信服务）是一种运营商正在采用的通信协议，GSMA 最近规定了使用消息层安全（MLS）协议对 RCS 进行端到端加密。GrapheneOS 目前依赖 Google Messages 实现 RCS 的端到端加密，但旨在提供自己的实现以避免使用 Google 服务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GrapheneOS">GrapheneOS - Wikipedia</a></li>
<li><a href="https://www.gsma.com/newsroom/article/rcs-encryption-a-leap-towards-secure-and-interoperable-messaging/">RCS Encryption: A Leap Towards Secure and Interoperable ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Messaging_Layer_Security">Messaging Layer Security - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员对非 Google 的 RCS 选项表示热情，一位用户指出 Google Messages 一直运行良好，但非 Google 的替代方案将意义重大。一些用户质疑“安全剪贴板”方面，因为公告主要聚焦于短信/RCS 应用，而其他人则建议具体的替代品，如 FUTO 键盘和名为 ReFrame 的图库应用。

**标签**: `#GrapheneOS`, `#privacy`, `#Android`, `#RCS`, `#secure clipboard`

---

<a id="item-4"></a>
## [OpenAI 内部视角：自动化 AI 研究与递归自我改进](https://openai.com/index/research-acceleration-view-inside-openai) ⭐️ 8.0/10

OpenAI 发布了一篇文章，详细介绍了其构建自动化 AI 研究员的努力，该研究员能够在人类监督下工作，以加速深度学习和对齐方面的进展，并实现迭代改进。文章还强调了 OpenAI 自己的研究人员目前如何在内部使用 AI 工具。 这之所以重要，是因为它提供了 OpenAI 在递归自我改进（RSI）和自动化研究方面战略的罕见内部视角，这可能显著加速 AI 发展并影响更广泛的 AI 生态系统。它还引发了关于安全性、对齐以及 AI 帮助解决对齐挑战潜力的重要问题。 文章提到，OpenAI 的目标是构建一个自动化 AI 研究员，能够处理需要熟练研究人员几天才能完成的任务，并且他们在未定义的情况下使用了缩写 RSI，一些评论者认为这有些脱离实际。根据社区讨论，OpenAI 据报道每位研究人员每天在 AI 工具上花费高达 8000 美元。

hackernews · iamsyr · Sep 6, 15:08 · [社区讨论](https://news.ycombinator.com/item?id=49587217)

**背景**: 递归自我改进（RSI）是一个假设的过程，其中 AGI 系统重写自己的代码以增强其能力，可能导致智能爆炸。虽然目前没有 AI 实现 RSI，但这一概念引发了重大的安全和伦理问题。OpenAI 的文章讨论了构建自动化研究工具作为迈向这一目标的一步，并可能对对齐研究有益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Recursive_self-improvement">Recursive self-improvement</a></li>
<li><a href="https://arxiv.org/abs/2607.07663">[2607.07663] Recursive Self-Improvement in AI: From Bounded Self ...</a></li>
<li><a href="https://www.itechpost.com/articles/237237/20260906/openai-reaches-its-automated-research-intern-goal-aims-have-automated-ai-researcher-march-2028.htm">OpenAI Reaches Its Automated Research Intern Goal, Aims to Have an Automated AI Researcher by March 2028</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 OpenAI 追求 RSI 的理由表示怀疑，一些人指出需要 AI 来保护免受 AI 侵害的循环论证。其他人则认为内部使用细节更有趣，而一些人批评使用未定义的缩写如 RSI，并对 AI 辅助工作的高成本和跟踪提出质疑。

**标签**: `#OpenAI`, `#AI research`, `#recursive self-improvement`, `#AI safety`, `#automation`

---

<a id="item-5"></a>
## [OpenAI GPT-6 Astra 在多个领域给早期测试者留下深刻印象](https://decrypt.co/377514/openai-gpt-6-astra-review-shockingly-good) ⭐️ 8.0/10

OpenAI 于 2026 年 9 月 3 日以有限预览形式发布了 GPT-6 Astra，早期测试者在发布周末对其在 3D 环境、可玩游戏、巴赫众赞歌和研究论文中的表现进行了评估。该模型首先向有限的组织推出，未来几天将向所有 ChatGPT Plus、Pro、Business 和 Enterprise 用户以及通过 API 和云平台提供更广泛的可用性。 GPT-6 Astra 代表了 AI 能力的重大飞跃，是 OpenAI 首个在其 Preparedness Framework 下达到网络安全能力“关键”级别的模型。它在多个领域的出色表现预示着多模态 AI 可能发生范式转变，将影响依赖先进 AI 处理复杂任务的研究人员、开发者和企业。 GPT-6 Astra 是 OpenAI 广泛部署的最强大模型，其使用包含在现有订阅额度内，并可选购买额外积分。该发布是在 2026 年 7 月 Hugging Face 事件后延迟进行的，期间 OpenAI 增加了更多安全措施。

rss · Decrypt · Sep 6, 17:01

**背景**: 多模态 AI 模型处理并整合来自多种数据类型（如文本、图像、音频和视频）的信息，以实现比单模态模型更全面的理解。GPT-6 Astra 基于这一概念，展示了在 3D 环境、游戏、音乐和研究方面的能力，表明其高级整合了多种模态。该模型的发布遵循了 OpenAI 的 Preparedness Framework，该框架评估并减轻与高级 AI 能力相关的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-6_Astra">GPT-6 Astra - Wikipedia</a></li>
<li><a href="https://openai.com/index/gpt-6-astra/">GPT-6 Astra: A new generation of intelligence | OpenAI</a></li>
<li><a href="https://deploymentsafety.openai.com/gpt-6-astra">GPT-6 Astra System Card - OpenAI Deployment Safety Hub</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#GPT-6`, `#AI model`, `#multimodal`, `#AI research`

---

<a id="item-6"></a>
## [Liquid Network 因 3.2 亿美元比特币提款而暂停](https://www.theblock.co/news/defi/2026-09-06-liquid-network-pauses-after-purported-white-hat-hackers-withdraw-320-million-in-bitcoin-413626) ⭐️ 8.0/10

比特币侧链 Liquid Network 在所谓的白帽黑客提取 3.2 亿美元比特币后暂停运营，导致交易所暂停 LBTC 的充值和提现。Blockstream 正在努力联系相关责任人。 这一事件凸显了比特币二层解决方案中的安全漏洞，可能削弱对 Liquid 等侧链的信任。LBTC 交易的暂停影响了用户和交易所，可能对依赖此类资产的更广泛的 DeFi 生态系统产生影响。 此次提款涉及 3.2 亿美元的比特币，网络在 Blockstream 调查期间暂停。交易所已暂停 LBTC 的充值和提现，事件被描述为涉及“白帽”黑客，暗示这可能是一次道德黑客行为或安全措施。

rss · The Block · Sep 6, 21:14

**背景**: Liquid Network 是一个开源的比特币侧链和二层解决方案，旨在实现更快、更便宜和更保密的比特币交易以及数字资产发行。LBTC 是 Liquid 上的代币，但请注意，还有一个独立的 Lombard BTC (LBTC) 代币，它是一种由 BTC 1:1 支持的生息代币；新闻可能指的是 Liquid Network 的 LBTC。白帽黑客是在获得许可的情况下进行黑客攻击以识别漏洞的道德安全研究人员。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.liquid.net/docs/technical-overview">Technical Overview - Documentation - The Liquid Network</a></li>
<li><a href="https://blockstream.com/liquid/">The Liquid Network | Bitcoin layer-2 solution for digital asset issuance.</a></li>
<li><a href="https://river.com/learn/terms/l/liquid-network/">Liquid Network - River Financial</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#Liquid Network`, `#security`, `#hack`, `#cryptocurrency`

---

<a id="item-7"></a>
## [用 1024 字节 C 语言实现 Python 解释器](https://austinhenley.com/blog/python1024.html) ⭐️ 7.0/10

Austin Henley 发表了一篇文章，展示了一个仅用 1024 字节 C 代码编写的最小 Python 解释器。该解释器通过极端的代码高尔夫技巧，支持 Python 的一个极小子集，包括 for 循环、while 循环和 if 语句。 这一壮举展示了语言实现和代码高尔夫技巧的极限，激励程序员创造性地思考解释器设计。它也凸显了极简主义与功能性之间的权衡，对嵌入式系统和教育项目具有参考意义。 该解释器用 C 语言编写，编译后的二进制文件远大于 1024 字节。它假设源代码正确，关键字如'f'映射为'for [x] in range[y]'，'w'映射为'while'，'i'映射为'if'，并且每次循环迭代时都会重新解析源代码。

hackernews · azhenley · Sep 6, 23:14 · [社区讨论](https://news.ycombinator.com/item?id=49591876)

**背景**: 代码高尔夫是一种休闲编程活动，参与者力求用最少的字符或字节数解决问题。用 1024 字节编写 Python 解释器是一个极端的例子，挑战了在极少量代码中能表达什么的极限。该项目类似于其他极简实现，如 C4（一个微型 C 编译器），但通过假设输入有效而采取了更多捷径。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://deepwiki.com/ebi-cp/docs/3.2-code-golfing-techniques">Code Golfing Techniques | ebi-cp/docs | DeepWiki</a></li>
<li><a href="https://www.geeksforgeeks.org/python/code-golfing-in-python/">Code Golfing in Python - GeeksforGeeks</a></li>
<li><a href="https://aosabook.org/en/500L/a-python-interpreter-written-in-python.html">500 Lines or LessA Python Interpreter Written in Python</a></li>

</ul>
</details>

**社区讨论**: 社区评论对其巧妙性表示赞赏，同时指出其不实用性。jrdres 将其与 C4 进行不利比较，指出它假设源代码正确。teddyh 建议使用 Snek 作为嵌入式场景的生产级替代方案。其他人则欣赏其人工创作的特点，并链接到作者的相关项目。

**标签**: `#Python`, `#interpreter`, `#code golf`, `#minimalism`, `#programming languages`

---

<a id="item-8"></a>
## [Nitter 和 XCancel 在获得法律建议后恢复服务](https://github.com/zedeus/nitter/commit/1428b4c2b4246f92a7e5b2673438e5fb39fcc4a3) ⭐️ 7.0/10

Nitter 和 XCancel 在收到 X Corp 的停止函后曾暂时关闭，现已在获得法律建议后恢复运营。这些项目继续提供访问 X 内容的替代前端。 这一进展对隐私倡导者和依赖替代前端来无需登录或避免追踪地访问 X 内容的用户具有重要意义。它凸显了平台控制与公共信息开放获取之间的持续紧张关系。 恢复服务是通过 Nitter GitHub 仓库的一次提交宣布的，其中附带了 XCancel 和 Nitter 实例的链接。法律建议允许这些项目继续运营，但未透露具体细节。

hackernews · zImPatrick · Sep 6, 17:49 · [社区讨论](https://news.ycombinator.com/item?id=49588988)

**背景**: Nitter 是一个免费开源的 X（前身为 Twitter）替代前端，允许用户无需登录、无广告或追踪脚本地浏览推文。XCancel 是一个类似的服务，依赖 Nitter 来显示 X 帖子。这两个项目在 2026 年 8 月收到了 X Corp 的停止函，导致暂时关闭。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nitter">Nitter - Wikipedia</a></li>
<li><a href="https://www.forbes.com/sites/siladityaray/2026/08/26/cease-and-desist-from-x-shuts-down-nitter-and-xcancel-sites-that-scraped-and-mirrored-tweets/">Nitter And XCancel Shutdown After 'Cease And Desist' From ... - Forbes</a></li>
<li><a href="https://85ideas.com/blog/what-is-xcancel-complete-guide-explanation/">What Is XCancel? Complete Guide & Explanation - 85ideas.com</a></li>

</ul>
</details>

**社区讨论**: 社区评论对恢复服务表示欣慰和支持，用户指出替代前端对于访问仅在 X 上发布的关键信息的重要性。一些评论者还讨论了平台垄断和将用户迁移到更好平台的困难等更广泛的问题。

**标签**: `#privacy`, `#open-source`, `#social-media`, `#legal`, `#decentralization`

---

<a id="item-9"></a>
## [谷歌修复 Chrome V8 引擎中被积极利用的零日漏洞](https://decrypt.co/377501/google-chrome-zero-day-exploited) ⭐️ 7.0/10

谷歌已发布 Chrome 142.0.7444.162/.163 版本，以修复 V8 JavaScript 引擎中的一个高危零日漏洞，该漏洞已被积极利用。该更新正在 Windows、Mac 和 Linux 平台上逐步推出。 此次补丁至关重要，因为该零日漏洞已被黑客积极利用，使 Chrome 用户面临攻击风险。这凸显了及时更新浏览器对安全的重要性，尤其是对依赖 Chrome 的软件工程师和安全专业人员而言。 该漏洞位于 V8 JavaScript 引擎中，谷歌尚未透露谁在利用它以及攻击目标。据近期报道，此次更新共修复了 26 个 Chrome 漏洞，其中包括两个严重的释放后使用漏洞。

rss · Decrypt · Sep 5, 15:01

**背景**: 零日漏洞是指软件供应商未知的安全缺陷，在发现时没有可用的补丁。在这种情况下，该漏洞在谷歌发布修复之前就被积极利用，因此构成零日攻击。V8 引擎是 Chrome 的 JavaScript 引擎，由于其复杂性和广泛使用，常成为攻击者的目标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2p0eW8zMkVSR19RWkVEY0VmNkx5Z0FQAQ?hl=en-IN&gl=IN&ceid=IN:en">Google Chrome update addresses V 8 engine vulnerability - Overview</a></li>
<li><a href="https://www.linkedin.com/posts/cybersecurity-news_cybersecuritynews-vulnerability-activity-7386633653323427840-F6nv">Google fixes Chrome V 8 JavaScript engine vulnerability | LinkedIn</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-day_exploit">Zero-day exploit</a></li>

</ul>
</details>

**标签**: `#security`, `#Chrome`, `#zero-day`, `#V8`, `#patch`

---

<a id="item-10"></a>
## [Better 与 Coinbase 推出可复用抵押品的比特币抵押贷款](https://www.coindesk.com/business/2026/09/06/better-and-coinbase-s-bitcoin-backed-mortgages-can-reuse-borrowers-collateral) ⭐️ 6.0/10

Better 与 Coinbase 推出了比特币抵押贷款产品，允许借款人复用其抵押品，从而可能提高资本效率。该产品允许借款人质押比特币来支付购房首付而无需出售，且抵押品可在借贷链条中被重复使用。 这一创新可能使加密货币持有者更容易购房，同时增强加密生态系统的流动性。它也凸显了传统金融与数字资产之间日益融合的趋势，可能影响未来贷款产品中抵押品的管理方式。 该抵押贷款结构涉及两笔贷款：一笔是房屋的合格房利美抵押贷款，另一笔是以质押的加密货币和房屋第二留置权为担保的独立贷款。正如美联储研究所指出的，抵押品复用虽然提高了资本效率，但可能增加对抵押品价格下跌的风险敞口。

rss · CoinDesk · Sep 6, 14:00

**背景**: 比特币抵押贷款允许借款人使用其加密货币作为抵押品，而无需出售，从而避免应税事件和强制清算。抵押品复用是指贷款人将收到的抵押品再质押以支持其他交易的做法，这可以增加流动性，但也可能增加系统性风险。Milo 和 Rocket Mortgage 等公司已提供加密抵押贷款，但 Better 与 Coinbase 的合作引入了抵押品复用这一新颖元素。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://better.com/crypto-backed-mortgages">Crypto-Backed Mortgages | Better Mortgage</a></li>
<li><a href="https://www.federalreserve.gov/econres/feds/collateral-reuse-and-financial-stability.htm">The Fed - Collateral Reuse and Financial Stability</a></li>
<li><a href="https://www.rocketmortgage.com/learn/crypto-mortgage">Crypto and Bitcoin mortgages | Rocket Mortgage</a></li>

</ul>
</details>

**标签**: `#bitcoin`, `#mortgages`, `#fintech`, `#collateral`, `#crypto`

---