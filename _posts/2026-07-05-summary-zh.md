---
layout: default
title: "Horizon Summary: 2026-07-05 (ZH)"
date: 2026-07-05
lang: zh
---

> From 55 items, 15 important content pieces were selected

---

1. [提示注入漏洞泄露 YouTube 创作者的私密视频](#item-1) ⭐️ 9.0/10
2. [GPT-5.5 Codex 因推理令牌聚类导致性能下降](#item-2) ⭐️ 8.0/10
3. [安娜档案悬赏 20 万美元获取谷歌图书扫描件](#item-3) ⭐️ 8.0/10
4. [更好的模型，更差的工具使用者](#item-4) ⭐️ 8.0/10
5. [LLM 实例间潜在的会话/缓存泄漏](#item-5) ⭐️ 8.0/10
6. [Zig 将包管理功能从编译器移至构建系统](#item-6) ⭐️ 8.0/10
7. [白帽黑客用 3000 美元服务器发现威胁 700 亿美元加密货币的漏洞](#item-7) ⭐️ 8.0/10
8. [《命令与征服：将军》借助 AI 工具 Fable 移植到苹果设备](#item-8) ⭐️ 7.0/10
9. [卫星与太空镜威胁夜空](#item-9) ⭐️ 7.0/10
10. [Perplexity 联合创始人：AI 安全被用作封锁前沿的借口](#item-10) ⭐️ 7.0/10
11. [Claude Fable 5 未被削弱，路由层引发困惑](#item-11) ⭐️ 7.0/10
12. [Linux htop/top 全面指南（2019）](#item-12) ⭐️ 6.0/10
13. [受制裁俄罗斯稳定币 A7A5 交易量遭质疑](#item-13) ⭐️ 6.0/10
14. [Q-Day：量子计算对比特币的威胁解析](#item-14) ⭐️ 6.0/10
15. [现货 ETF 推动机构比特币采用](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [提示注入漏洞泄露 YouTube 创作者的私密视频](https://javoriuski.com/post/youtube) ⭐️ 9.0/10

一名安全研究人员发现 YouTube Studio 的 AI 评论回复功能存在提示注入漏洞，攻击者可通过评论注入恶意提示，从而泄露创作者的私密视频。 该漏洞对 YouTube 创作者构成严重的隐私风险，可能未经同意泄露未列出或私密视频。它凸显了将 AI 集成到面向用户的功能中日益增长的安全挑战。 攻击原理是：当创作者点击 YouTube Studio 中的 AI 建议回复时，AI 会处理包含提示注入载荷的攻击者评论。注入的提示可指示 AI 在其回复中包含私密视频的标题。

hackernews · javxfps · Jul 4, 16:45 · [社区讨论](https://news.ycombinator.com/item?id=48786781)

**背景**: 提示注入是一种安全漏洞，攻击者通过精心构造输入，诱使 AI 语言模型忽略其预定指令而执行攻击者命令。YouTube Studio 的 AI 评论回复功能使用大型语言模型来建议回复，但未能正确清理用户输入，导致恶意提示得以执行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>
<li><a href="https://owasp.org/www-community/attacks/PromptInjection">Prompt Injection - OWASP Foundation</a></li>
<li><a href="https://support.google.com/youtube/answer/10357396?hl=en&co=GENIE.Platform=Android">Use comment reply suggestions - Android - YouTube Help</a></li>

</ul>
</details>

**社区讨论**: 社区讨论非常活跃，有 303 条评论，包括一位前谷歌员工解释内部处理此类漏洞的方式。一些用户报告称该漏洞在他们的测试中未成功，而另一些用户则称赞文章清晰、事实性的呈现方式。

**标签**: `#security`, `#prompt injection`, `#YouTube`, `#vulnerability`, `#AI`

---

<a id="item-2"></a>
## [GPT-5.5 Codex 因推理令牌聚类导致性能下降](https://github.com/openai/codex/issues/30364) ⭐️ 8.0/10

用户报告 GPT-5.5 Codex 的推理令牌聚类在固定值（516、1034、1552 等）上，导致复杂任务结果错误。这一可复现的性能退化已得到社区验证，并与 GitHub 问题相关联。 这一性能退化削弱了用户对 OpenAI 旗舰编程助手 Codex 的信任，影响了依赖其进行复杂推理任务的开发者。它凸显了在保持 LLM 质量一致性和透明度方面持续存在的挑战。 聚类现象显示推理令牌卡在 518 的倍数（如 516、1034、1552）上，与错误高度相关。当模型使用 6000-8000 个推理令牌时，结果正确，表明存在自适应思考问题。

hackernews · maille · Jul 4, 21:51 · [社区讨论](https://news.ycombinator.com/item?id=48789428)

**背景**: GPT-5.5 Codex 是一个针对代码生成和推理微调的大型语言模型。推理令牌代表模型在生成答案前的内部思维链。令牌数量聚类在固定值表明模型的自适应思考机制存在缺陷，可能是由于服务器端变更所致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/openai/codex/issues/30364">GPT-5.5 Codex reasoning-token clustering at 516/1034/1552 may ... - GitHub</a></li>
<li><a href="https://news.ycombinator.com/item?id=48789428">GPT-5.5 Codex reasoning-token clustering may be leading to degraded performance | Hacker News</a></li>
<li><a href="https://marginlab.ai/trackers/codex/">Codex gpt-5.5-xhigh Performance Tracker - marginlab.ai</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了对性能退化的不满，用户指出质量每日下降，并转向 Claude 等替代品。一些人将其与 4 月份 Claude Code 的类似退化相比较，而另一些人则赞赏 Codex 开源以便公开跟踪问题。

**标签**: `#AI`, `#Codex`, `#performance regression`, `#LLM`, `#debugging`

---

<a id="item-3"></a>
## [安娜档案悬赏 20 万美元获取谷歌图书扫描件](https://software.annas-archive.gl/AnnaArchivist/annas-archive/-/work_items/234) ⭐️ 8.0/10

安娜档案宣布悬赏 20 万美元，以获取谷歌图书的全部扫描件，旨在保存并提供对整个馆藏的开放访问。 这笔悬赏可能为服务不足的地区和研究人员解锁大量数字化图书，挑战当前的版权限制，推动开放知识的发展。 悬赏针对谷歌图书的完整扫描件集，其中包括来自合作图书馆的数百万册图书，许多已绝版或稀有。安娜档案是一个影子图书馆元搜索引擎，聚合了 Z-Library、Sci-Hub 和 LibGen 的记录。

hackernews · Cider9986 · Jul 4, 16:51 · [社区讨论](https://news.ycombinator.com/item?id=48786838)

**背景**: 谷歌图书于 2002 年开始扫描大学图书馆的图书，创建了一个庞大的数字存储库。然而，由于版权问题，完整扫描件的访问通常受到限制。安娜档案于 2022 年启动，旨在编录所有图书并使其免费可用，作为一个非营利的影子图书馆元搜索引擎运营。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anna's_Archive">Anna's Archive</a></li>
<li><a href="https://en.wikipedia.org/wiki/Google_Books">Google Books - Wikipedia</a></li>
<li><a href="https://support.google.com/websearch/answer/9690276?hl=en">About the Library Project - Google Search Help</a></li>

</ul>
</details>

**社区讨论**: 社区成员表达了对安娜档案的感激之情，分享了获取稀有图书的个人经历。一些人讨论了相关项目如 SourceLibrary.org，而另一些人则推测未来对互联网档案的悬赏。总体情绪是支持的，并对开放获取的使命表示赞赏。

**标签**: `#digital libraries`, `#book scanning`, `#open access`, `#bounty`, `#knowledge preservation`

---

<a id="item-4"></a>
## [更好的模型，更差的工具使用者](https://lucumr.pocoo.org/2026/7/4/better-models-worse-tools/) ⭐️ 8.0/10

Armin Ronacher 的一篇文章指出，随着大型语言模型（LLM）的改进，它们在使用外部工具方面变得更差，因为过度依赖学习到的模式，无法适应不熟悉的工具模式。 这个问题威胁到依赖工具使用的 AI 智能体的可靠性，可能限制它们在需要正确调用工具的实际应用中的部署。 文章建议更好的错误处理（例如在错误消息中提供有用的指导）可以缓解这个问题。文章还指出，使用 curl 命令等替代方法比 MCP 更可靠。

hackernews · leemoore · Jul 4, 20:16 · [社区讨论](https://news.ycombinator.com/item?id=48788599)

**背景**: LLM 越来越多地被用作通过 MCP（模型上下文协议）等协议调用外部工具的智能体。然而，随着模型在大量数据上训练，它们可能记住常见模式，并在面对新颖或不常见的工具接口时失败，导致错误调用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://medium.com/@elisowski/mcp-explained-the-new-standard-connecting-ai-to-everything-79c5a1c98288">MCP Explained: The New Standard Connecting AI to... | Medium</a></li>

</ul>
</details>

**社区讨论**: 评论者基本同意该分析，并提供了实用解决方案。有人建议改进错误消息以引导模型，另有人推荐在技能文件中使用 curl 命令以提高可靠性。还有评论者担心运行时成为模型接口的一部分，使其变得脆弱。

**标签**: `#LLM`, `#tool use`, `#AI agents`, `#error handling`, `#MCP`

---

<a id="item-5"></a>
## [LLM 实例间潜在的会话/缓存泄漏](https://github.com/anthropics/claude-code/issues/74066) ⭐️ 8.0/10

用户报告多个提供商的 LLM 实例（包括 Claude 和 GPT 模型）之间可能存在会话或缓存泄漏，导致返回的响应似乎属于其他用户。 如果得到确认，这可能表明共享 LLM 基础设施中存在严重的安全和隐私漏洞，可能导致跨租户的敏感数据泄露。 Claude Code 团队表示他们确信这是幻觉，但正在调查；一位用户报告称某提供商的事后分析指出 API 网关在处理 HTTP 100 状态码时存在错误。

hackernews · chatmasta · Jul 4, 14:03 · [社区讨论](https://news.ycombinator.com/item?id=48785485)

**背景**: LLM 提供商通常使用缓存和共享基础设施来降低成本和延迟。跨会话泄漏是指一个用户的上下文或缓存被无意中提供给另一个用户，可能导致数据泄露。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48785485">Potential session/cache leakage between workspace instances or consumer accounts | Hacker News</a></li>
<li><a href="https://www.giskard.ai/knowledge/cross-session-leak-when-your-ai-assistant-becomes-a-data-breach">Cross Session Leak: LLM security vulnerability & detection guide</a></li>
<li><a href="https://tianpan.co/blog/2026-04-10-cross-tenant-data-leakage-llm-infrastructure">Cross-Tenant Data Leakage in Shared LLM Infrastructure : The...</a></li>

</ul>
</details>

**社区讨论**: 社区意见分歧：一些用户报告在不同提供商处有类似经历，而另一些人则认为由于大上下文窗口，这很可能是幻觉。Claude Code 团队的一名成员确认了该报告并表示正在调查。

**标签**: `#LLM`, `#security`, `#privacy`, `#AI infrastructure`, `#cache leakage`

---

<a id="item-6"></a>
## [Zig 将包管理功能从编译器移至构建系统](https://ziglang.org/devlog/2026/#2026-06-30) ⭐️ 8.0/10

Zig 于 2026 年 6 月 30 日宣布，将所有包管理功能从编译器移至构建系统。这一变化将编译器与包解析解耦，优先考虑长期可维护性。 这一架构决策通过减少编译器的职责来提高其稳定性和安全性，并为未来基于 WebAssembly 的构建系统等创新铺平道路。然而，它牺牲了 @cImport 等功能的便利性，而 @cImport 曾是 Zig 的关键差异化特性。 此举的动机是为了在之前的更改导致 Zig 语言服务器 (ZLS) 故障后解除阻塞，并且它允许在包获取期间对网络操作启用安全检查 (ReleaseSafe)。构建系统现在作为一个独立的可执行文件来处理包管理。

hackernews · tosh · Jul 4, 16:30 · [社区讨论](https://news.ycombinator.com/item?id=48786638)

**背景**: Zig 是一种专注于简洁性和性能的系统编程语言。其构建系统是基于 DAG 的系统，用 Zig 自身编写，而编译器此前直接处理包解析。解耦这些组件是语言工具链中提高模块化和安全性的常见趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://codeberg.org/ziglang/zig/pulls/35917">move all package management functionality from compiler to build system</a></li>
<li><a href="https://news.ycombinator.com/item?id=48786638">Zig: All Package Management Functionality Moved from Compiler to Build ...</a></li>

</ul>
</details>

**社区讨论**: 社区情绪复杂：一些人哀叹 @cImport 便利性的丧失，但承认这是为了可维护性做出的正确决定。另一些人对未来计划（如 WebAssembly 构建系统）感到兴奋，还有少数人将这一变化比作“从油箱中移除散热液”，质疑为何当初要加入该功能。

**标签**: `#Zig`, `#package management`, `#compiler design`, `#build systems`, `#programming languages`

---

<a id="item-7"></a>
## [白帽黑客用 3000 美元服务器发现威胁 700 亿美元加密货币的漏洞](https://www.coindesk.com/tech/2026/07/04/how-ethical-hackers-with-just-a-usd3-000-server-found-a-flaw-that-could-ve-put-usd70-billion-in-crypto-at-risk) ⭐️ 8.0/10

白帽黑客使用一台 3000 美元的服务器，在以太坊信标链的 MEV-Boost 中继中发现了一个关键漏洞，该漏洞可能危及 700 亿美元的加密货币。 该漏洞可能允许攻击者操纵区块生产并窃取资金，突显了以太坊权益证明基础设施中的系统性风险以及白帽黑客的重要性。 该漏洞存在于 Flashbots 维护的开源 mev-boost-relay 实现中，验证者用它来外包区块生产。2023 年 4 月的一次类似漏洞利用导致从三明治机器人中窃取了 2000 万美元。

rss · CoinDesk · Jul 4, 18:00

**背景**: 以太坊信标链是以太坊权益证明系统的共识层，验证者在此提议和证明区块。MEV-Boost 是一种工具，允许验证者将区块生产外包给专门的构建者以最大化利润，但这引入了额外的信任假设和潜在攻击向量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ethereum.org/roadmap/beacon-chain/">The Beacon Chain - ethereum.org</a></li>
<li><a href="https://blog.solidityscan.com/mev-bot-hack-analysis-mev-boost-relay-attack-15bd4f84680/">MEV Bot hack analysis — MEV Boost Relay Attack – SolidityScan Blogs</a></li>
<li><a href="https://www.alchemy.com/overviews/mev-boost">What is MEV Boost ? | Alchemy</a></li>

</ul>
</details>

**标签**: `#security`, `#cryptocurrency`, `#ethical hacking`, `#vulnerability`

---

<a id="item-8"></a>
## [《命令与征服：将军》借助 AI 工具 Fable 移植到苹果设备](https://github.com/ammaarreshi/Generals-Mac-iOS-iPad/tree/main) ⭐️ 7.0/10

《命令与征服：将军》已通过 AI 辅助逆向工程工具 Fable 原生移植到 macOS、iPhone 和 iPad，基于 EA 的 GPL v3 源代码发布和 GeneralsX 分支。 这展示了大型语言模型（LLM）在游戏移植和逆向工程中的新颖应用，可能加速遗留游戏的跨平台保存和现代化。 该移植基于 GeneralsX 分支，该分支处理了 macOS/Linux 移植，而此分支增加了 iOS/iPadOS 支持和引擎修复。AI 工具 Fable 用于辅助转换过程。

hackernews · asronline · Jul 4, 19:41 · [社区讨论](https://news.ycombinator.com/item?id=48788283)

**背景**: 逆向工程涉及分析编译后的二进制文件以理解其结构并重新创建源代码。AI 辅助逆向工程利用机器学习来自动化部分过程，使其更快、更易用。Fable 是 Anthropic 的一款 AI 工具，可辅助代码分析和生成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.latent.space/p/ainews-fable-and-mythos-officially">[AINews] Fable and Mythos officially too dangerous to release</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI-assisted_reverse_engineering">AI-assisted reverse engineering</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，LLM 在游戏逆向工程中正变得有价值，一位用户分享了他们的 Ghidra + LLM 工作流程。一些人批评 AI 生成的文档风格令人不适，而另一些人则欣赏该项目低风险、可迭代的特性。

**标签**: `#game porting`, `#AI-assisted reverse engineering`, `#open source`, `#macOS`, `#iOS`

---

<a id="item-9"></a>
## [卫星与太空镜威胁夜空](https://www.eso.org/public/news/eso2607/) ⭐️ 7.0/10

欧洲南方天文台（ESO）警告称，SpaceX 和 Reflect Orbital 等公司计划中的卫星巨型星座和太空镜将通过增加光污染和卫星轨迹，对天文观测构成重大威胁。 这凸显了太空基础设施扩张与保护黑暗天空用于科学研究之间日益增长的冲突，可能影响地基天文学及我们对宇宙的理解。 SpaceX 计划发射多达一百万颗卫星用于太空数据中心，而 Reflect Orbital 则计划部署大型镜面卫星在夜间反射阳光，在地球表面形成至少五公里宽的光束。

hackernews · Breadmaker · Jul 4, 17:17 · [社区讨论](https://news.ycombinator.com/item?id=48787042)

**背景**: 卫星巨型星座是由数百至数千颗低地球轨道（LEO）卫星组成的大型网络，用于提供全球互联网覆盖。它们的反射表面会在天文图像中形成明亮轨迹，干扰观测。太空镜是一种新概念，通过轨道镜面反射阳光为地球提供夜间照明，进一步增加光污染。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Satellite_constellation">Satellite constellation - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Satellite_internet_constellation">Satellite internet constellation - Wikipedia</a></li>
<li><a href="https://www.nature.com/articles/s41586-025-09759-5">Satellite megaconstellations will threaten space-based astronomy | Nature</a></li>

</ul>
</details>

**社区讨论**: 评论显示社区意见分歧：有人认为进步更重要，卫星会自然离轨；而另一些人则担心对天文学的影响，建议先观望太空数据中心的实用性。还有人对太空镜的可行性表示怀疑，并担心监管可能巩固垄断。

**标签**: `#astronomy`, `#satellites`, `#space infrastructure`, `#environmental impact`

---

<a id="item-10"></a>
## [Perplexity 联合创始人：AI 安全被用作封锁前沿的借口](https://decrypt.co/372755/perplexity-co-founder-ai-safety-excuse-lock-down-frontier) ⭐️ 7.0/10

Perplexity 联合创始人 Andy Konwinski 指出，AI 安全问题正被 Anthropic 等私人实验室利用，以限制对前沿 AI 研究的访问，他引用了美国政府因安全担忧暂停 Anthropic 的 Fable 5 模型一事。 这一批评挑战了 AI 安全为集中控制提供正当性的主流叙事，可能影响关于开放与封闭 AI 研究及治理的辩论。 Konwinski 以 Anthropic 的 Fable 5 事件为例，美国政府下令暂停外国公民对该模型的访问，而 Anthropic 自称该模型“过于强大”。

rss · Decrypt · Jul 4, 16:07

**背景**: 前沿 AI 研究指的是最先进的 AI 模型，通常由 Anthropic 和 OpenAI 等私人实验室开发。AI 安全问题引发了监管和限制访问的呼声，但批评者认为这可能扼杀创新并集中权力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/fable-mythos-access">Statement on the US government directive to suspend access to Fable 5 and Mythos 5 \ Anthropic</a></li>
<li><a href="https://www.bbc.com/news/articles/c932g3v3e13o">Anthropic's Claude Fable 5 and Mythos 5 AI suspended over security fears</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#open source`, `#AI governance`, `#frontier AI`, `#Anthropic`

---

<a id="item-11"></a>
## [Claude Fable 5 未被削弱，路由层引发困惑](https://decrypt.co/372750/claude-fable-5-not-nerfed-router-paranoid) ⭐️ 7.0/10

文章揭示，Claude Fable 5 看似性能下降的原因是一个过度谨慎的路由层，该层有时会将任务重新路由到较弱的备用模型，而非模型本身退化。 这澄清了相互矛盾的基准测试结果，并凸显了路由层如何扭曲模型评估，从而影响对 AI 性能指标的信任。 例如，在部署更严格的安全分类器后，调试分数下降了 70%，但底层模型并未改变；只是路由器将复杂任务发送给了备用模型。

rss · Decrypt · Jul 3, 21:06

**背景**: Claude Fable 5 是 Anthropic 最强大的模型，专为长期异步任务设计。路由层是一个系统，它决定对给定请求使用哪个模型或版本，通常出于安全或成本考虑。当路由器过于谨慎时，它可能会将请求降级到较弱的模型，导致看似性能下降。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.techtimes.com/articles/319576/20260702/claude-fable-5-debugging-scores-drop-70-safety-classifier-reroutes-tasks-weaker-fallback-model.htm">Claude Fable 5 Debugging Scores Drop 70%: Safety Classifier...</a></li>
<li><a href="https://www.buildfastwithai.com/blogs/claude-fable-5-vs-claude-sonnet-5-comparison-2026">Claude Fable 5 vs Claude Sonnet 5: Which Should You Actually Use?</a></li>
<li><a href="https://openmark.ai/ai-model-routing">AI Model Routing Guide 2026: Benchmark-Driven... | OpenMark</a></li>

</ul>
</details>

**标签**: `#AI`, `#benchmarking`, `#model evaluation`, `#routing`, `#Claude`

---

<a id="item-12"></a>
## [Linux htop/top 全面指南（2019）](https://peteris.rocks/blog/htop/) ⭐️ 6.0/10

这篇文章详细解释了 htop 和 top 中可见的每一个指标和功能，涵盖 CPU、内存、进程等。 它作为一份有价值的参考资料，帮助 Linux 用户深入理解系统监控工具，但并未引入新技术。 该指南包含实用技巧，如在 htop 中禁用用户线程和启用树状视图，并指出虚拟内存可能具有误导性，而驻留大小更可靠。

hackernews · theanonymousone · Jul 4, 12:00 · [社区讨论](https://news.ycombinator.com/item?id=48784777)

**背景**: htop 和 top 是 Linux 上的命令行系统监控工具，用于显示进程和资源使用情况。理解它们的输出有助于用户诊断性能问题并有效管理系统资源。

**社区讨论**: 评论者称赞这篇文章是一份很好的参考资料，有人分享了使用 btop 作为现代替代方案以及调整 htop 设置以提高可用性的技巧。一位用户指出，即使使用了 Linux 20 年，他们仍然能学到新东西。

**标签**: `#Linux`, `#system monitoring`, `#htop`, `#top`

---

<a id="item-13"></a>
## [受制裁俄罗斯稳定币 A7A5 交易量遭质疑](https://www.coindesk.com/business/2026/07/03/this-sanctioned-russian-stablecoin-claims-it-processes-billions-but-blockchain-analysts-disagree) ⭐️ 6.0/10

CoinDesk 调查发现，受制裁的俄罗斯卢布挂钩稳定币 A7A5 声称处理数十亿美元交易，但区块链分析师发现链上数据显示交易量远低于此。 这一争议凸显了验证受制裁实体交易声明的难度，并对加密货币领域制裁执行的有效性提出质疑。 A7A5 去年因涉嫌帮助俄罗斯规避制裁而受到欧盟、英国和美国的制裁。该稳定币在 TRON 网络上发行，分析师使用 TRONSCAN 等区块链浏览器检查其实际转账量。

rss · CoinDesk · Jul 3, 19:18

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元或俄罗斯卢布等法定货币挂钩。区块链浏览器允许任何人查看公共账本上的交易数据，从而可以独立验证声称的交易量。制裁旨在限制资金流向目标实体，但加密货币的假名性可能使执行复杂化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/03/this-sanctioned-russian-stablecoin-claims-it-processes-billions-but-blockchain-analysts-disagree">Inside the fierce data dispute over whether a sanctioned Russian ...</a></li>
<li><a href="https://news.bitcoin.com/russian-ruble-stablecoin-gets-targeted-by-eu-sanctions/">Russian Ruble Stablecoin Gets Targeted by EU Sanctions</a></li>
<li><a href="https://tronscan.org/">TRONSCAN | TRON BlockChain Explorer | 波场区块链浏览器</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#stablecoin`, `#blockchain analysis`, `#geopolitics`

---

<a id="item-14"></a>
## [Q-Day：量子计算对比特币的威胁解析](https://decrypt.co/resources/what-q-day-quantum-threat-bitcoin-explained) ⭐️ 6.0/10

一篇新的解释性文章概述了量子计算机可能破解比特币 ECDSA 数字签名的潜在威胁，这一事件被称为 Q-Day。 如果量子计算机达到足够强大的能力，它们可能伪造比特币交易，破坏整个加密货币生态系统的安全性，并可能导致巨大的财务损失。 比特币目前使用椭圆曲线数字签名算法（ECDSA），该算法容易受到在足够大的量子计算机上运行的 Shor 算法的攻击。Q-Day 的时间表尚不确定，但专家敦促现在就开始准备。

rss · Decrypt · Jul 3, 15:40

**背景**: 量子计算机利用量子力学以指数级速度解决某些问题，远超经典计算机。特别是 Shor 算法可以高效地分解大数和计算离散对数，而这些是许多密码系统（如比特币使用的 ECDSA）的基础。如果建造出足够强大的量子计算机，它可以从公钥推导出私钥，从而实现未经授权的交易。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.paloaltonetworks.com.au/cyberpedia/what-is-q-day">What Is Q - Day ? Quantum Computing and Cyber Risk</a></li>
<li><a href="https://river.com/learn/how-bitcoin-uses-cryptography/">How Bitcoin Uses Cryptography | River</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#Bitcoin`, `#cryptography`, `#security`

---

<a id="item-15"></a>
## [现货 ETF 推动机构比特币采用](https://www.theblock.co/learn/407111/institutional-bitcoin-adoption-explained-how-blackrock-fidelity-and-others-embraced-btc?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

文章解释了 2024 年 1 月现货比特币 ETF 推出后，机构对比特币的采用如何加速，贝莱德和富达等主要公司纷纷进入该领域。 这标志着重大转变，因为受监管机构现在有了合规工具来获得比特币敞口，可能增加市场稳定性和主流接受度。 现货比特币 ETF 直接持有基础比特币，不同于期货 ETF，自获批以来吸引了数十亿美元资金流入，涵盖资产管理公司、对冲基金和养老基金。

rss · The Block · Jul 3, 06:26

**背景**: 机构采用是指资产管理公司、银行和养老基金等组织投资比特币或围绕其构建产品。2024 年 1 月获批的现货比特币 ETF 使这些机构能够通过受监管的交易所交易产品获得敞口，消除了此前托管和合规等障碍。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Grayscale_Investments">Grayscale Investments - Wikipedia</a></li>
<li><a href="https://www.coinglass.com/etf/bitcoin">Bitcoin ETF Fund Flows | Spot BTC Net Inflow & Holdings | CoinGlass</a></li>
<li><a href="https://www.ainvest.com/news/crypto-institutional-adoption-107b-signal-mainstream-validation-2509/">Crypto Institutional Adoption : A $107B Signal for Mainstream...</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#Institutional Adoption`, `#ETFs`, `#Crypto`

---