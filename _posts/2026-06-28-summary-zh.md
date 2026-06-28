---
layout: default
title: "Horizon Summary: 2026-06-28 (ZH)"
date: 2026-06-28
lang: zh
---

> From 66 items, 19 important content pieces were selected

---

1. [Dan Luu 分析系统中的虚假不连续性](#item-1) ⭐️ 8.0/10
2. [Linux 基金会启动 Akrites 项目，抵御 AI 攻击保护开源](#item-2) ⭐️ 8.0/10
3. [OpenAI 推出 GPT-5.6，但访问受限](#item-3) ⭐️ 8.0/10
4. [AI 代理成功抵御 6000 次黑客攻击](#item-4) ⭐️ 8.0/10
5. [OpenRA 以现代平衡性重振经典 C&C](#item-5) ⭐️ 7.0/10
6. [实体媒体所有权的理由](#item-6) ⭐️ 7.0/10
7. [TownSquare：为网站添加轻量级在线状态层](#item-7) ⭐️ 7.0/10
8. [亚洲 AI 初创公司推出类似 Mythos 的模型](#item-8) ⭐️ 7.0/10
9. [稳定币使用与资金的地理错配](#item-9) ⭐️ 7.0/10
10. [匿名 GitHub 账号批量发布所谓 0day 漏洞](#item-10) ⭐️ 6.0/10
11. [公共 DNS 解析器选择指南](#item-11) ⭐️ 6.0/10
12. [金融科技工程手册引发争议](#item-12) ⭐️ 6.0/10
13. [罗宾·威廉姆斯独白被用来批评大语言模型](#item-13) ⭐️ 6.0/10
14. [以太坊基金会资金缺口警告](#item-14) ⭐️ 6.0/10
15. [SBI 控股以 2.89 亿美元收购 Bitbank](#item-15) ⭐️ 6.0/10
16. [Strategy 130 亿美元比特币浮亏超过数百种代币市值](#item-16) ⭐️ 6.0/10
17. [西班牙：加密企业 MiCA 牌照截止日期不延长](#item-17) ⭐️ 6.0/10
18. [Base 主网再次停摆，两天内第二次中断](#item-18) ⭐️ 6.0/10
19. [GENIUS 法案：美国首个联邦稳定币法律](#item-19) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Dan Luu 分析系统中的虚假不连续性](https://danluu.com/discontinuities/) ⭐️ 8.0/10

Dan Luu 在 2020 年的文章中探讨了税收等级、马拉松配速和考试分数等系统中的人为不连续性如何导致不正当激励和统计假象。 这一分析意义重大，因为它揭示了看似随意的阈值如何扭曲行为和数据，影响政策设计、绩效指标以及多个领域的决策。 文章涵盖的例子包括马拉松完赛时间因配速组而集中在整点附近，以及波兰语考试成绩因截断而在 100 分处出现尖峰，说明了不连续性如何产生误导性模式。

hackernews · tosh · Jun 27, 13:32 · [社区讨论](https://news.ycombinator.com/item?id=48698151)

**背景**: 人为不连续性是指系统输出中的突变，并非源于底层过程，而是由设计引入的，例如税收等级或评分截止线。这可能导致不正当激励，使个体优化阈值而非预期目标，并产生掩盖真实分布的统计假象。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Perverse_incentive">Perverse incentive - Wikipedia</a></li>
<li><a href="https://richardbakerauthor.com/2021/11/30/design-rule-perverse-incentives/">Design Rule: Perverse Incentives – Richard Baker</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了个人经历，例如努力在半程马拉松中跑进 2:30 以内，并指出英国税收和育儿福利中存在类似的断崖。一位评论者主张取消经济状况调查以避免此类不连续性。

**标签**: `#systems design`, `#statistics`, `#public policy`, `#behavioral economics`

---

<a id="item-2"></a>
## [Linux 基金会启动 Akrites 项目，抵御 AI 攻击保护开源](https://decrypt.co/372244/linux-foundation-tech-giants-akrites-defend-open-source-ai-attacks) ⭐️ 8.0/10

Linux 基金会联合亚马逊云服务、谷歌、微软、OpenAI 和摩根大通等 19 家组织，启动了 Akrites 项目，这是一个共享的安全事件响应团队，旨在协调关键开源软件的漏洞发现、修补和披露。 该举措应对了日益增长的 AI 驱动开源供应链攻击威胁——过去一年恶意软件包上传量增加了 156%。通过联合主要科技公司、AI 实验室和金融机构，Akrites 旨在主动保护广泛使用的开源项目，防止漏洞被利用。 Akrites 建立了一个协调的 SIRT，与上游维护者合作修复漏洞，创始承诺来自 19 个组织，包括 Anthropic 和 OpenAI 等 AI 实验室，以及花旗和摩根大通等银行。该项目专注于 AI 辅助漏洞发现时代的关键开源软件。

rss · Decrypt · Jun 26, 19:23

**背景**: 开源软件在各行业广泛使用，但其安全往往依赖资源有限的志愿者维护者。AI 驱动的攻击使得大规模发现和利用漏洞变得更加容易，近期针对 LiteLLM 等软件包的供应链攻击就是例证。Akrites 旨在提供开源维护者一直缺乏的专职安全团队。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.securityweek.com/linux-foundation-unveils-new-open-source-security-project-akrites/">Linux Foundation Unveils New Open Source Security Project Akrites - SecurityWeek</a></li>
<li><a href="https://www.linuxfoundation.org/press/linux-foundation-and-industry-leaders-launch-akrites-to-defend-critical-open-source-software-against-ai-enabled-cyber-threats">Linux Foundation and Industry Leaders Launch Akrites to Defend Critical Open Source Software Against AI-Enabled Cyber Threats</a></li>
<li><a href="https://thehackernews.com/2025/11/cisos-expert-guide-to-ai-supply-chain.html">CISO's Expert Guide To AI Supply Chain Attacks</a></li>

</ul>
</details>

**标签**: `#open source`, `#security`, `#AI`, `#Linux Foundation`, `#supply chain`

---

<a id="item-3"></a>
## [OpenAI 推出 GPT-5.6，但访问受限](https://decrypt.co/372238/openai-rolls-out-gpt-5-6-limited-access-trump-admin) ⭐️ 8.0/10

OpenAI 于周五发布了 GPT-5.6 系列 AI 模型，但由于美国政府的规定，仅限部分用户访问。 此次发布标志着领先 AI 实验室的重大更新，但政府限制削弱了其即时影响，并凸显了 AI 进步与国家安全关切之间日益紧张的关系。 此次限制访问是在特朗普政府限制 Anthropic 的 Fable 5 和 Mythos 5 模型之后采取的，据报道原因是 Mythos 5 在红队测试中能够攻破 NSA 的机密系统。

rss · Decrypt · Jun 26, 19:06

**背景**: Anthropic 的 Mythos 5 模型最初因其强大的网络安全能力而受到限制，但后来被批准更广泛使用。美国政府一直在审查先进 AI 模型的潜在国家安全风险，导致选择性访问政策。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/anthropics-powerful-mythos-ai-reportedly-breached-almost-all-nsa-classified-systems-within-a-few-hours-during-red-team-test-report-sheds-more-light-on-the-u-s-governments-sudden-ban-on-the-flagship-models">Anthropic’s powerful Mythos AI reportedly breached ‘almost all’ NSA classified systems within a few hours during red-team test — report sheds more light on the U.S. government's sudden ban on the flagship models | Tom's Hardware</a></li>
<li><a href="https://fortune.com/2026/06/27/anthropic-mythos-5-ai-model-us-commerce-department-clearance-fable/">Anthropic’s Mythos 5 AI model cleared by U.S. for wider use | Fortune</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#GPT-5.6`, `#AI models`, `#government regulation`

---

<a id="item-4"></a>
## [AI 代理成功抵御 6000 次黑客攻击](https://decrypt.co/372221/ai-agent-openclaw-6000-hack-attempts) ⭐️ 8.0/10

开发者 Fernando Irarrázaval 将其由 Claude Opus 4.6 驱动的 OpenClaw AI 助手公开到 Hacker News 上，该助手成功抵御了 6000 次黑客攻击，未被攻破。 这次真实世界的压力测试表明，先进的 AI 代理能够在对抗性条件下保持强大的安全性，为安全部署自主系统提供了实践参考。 该 OpenClaw 助手被授予了访问电子邮件、消息和其他个人服务的权限，但 Claude Opus 4.6 的推理能力使其能够拒绝恶意命令并保护敏感数据。

rss · Decrypt · Jun 26, 18:01

**背景**: OpenClaw 是一个开源的个人 AI 助手，运行在用户自己的设备上，处理电子邮件、提醒和语音通话等任务。Claude Opus 4.6 是 Anthropic 最强大的模型，在编码和代理工作流中具有更高的可靠性和精确性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-opus-4-6">Claude Opus 4.6 \ Anthropic</a></li>
<li><a href="https://github.com/openclaw/openclaw">GitHub - openclaw/openclaw: Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞</a></li>

</ul>
</details>

**社区讨论**: Hacker News 社区称赞这次演示是 AI 代理安全性的有力概念验证，但也有人质疑测试环境是否完全模拟了真实世界的攻击向量。

**标签**: `#AI security`, `#autonomous agents`, `#adversarial testing`, `#Claude Opus`

---

<a id="item-5"></a>
## [OpenRA 以现代平衡性重振经典 C&C](https://www.openra.net/) ⭐️ 7.0/10

OpenRA 是一个开源项目，重新实现了经典《命令与征服》系列游戏（包括《红色警戒》、《泰伯利亚黎明》和《沙丘 2000》），并提供了现代化的游戏体验、改进的平衡性和新功能。 该项目让经典即时战略游戏在现代系统上得以延续和可玩，吸引了怀旧玩家和新受众，同时展示了社区驱动开发如何增强经典游戏。 OpenRA 是免费开源的，拥有活跃的开发团队和社区。它采用自定义引擎，支持更高分辨率、改进的寻路和重新平衡的单位，使游戏玩法比原版更具策略性。

hackernews · tosh · Jun 27, 12:10 · [社区讨论](https://news.ycombinator.com/item?id=48697560)

**背景**: 《命令与征服：红色警戒》由 Westwood Studios 于 1996 年发布，是一款里程碑式的即时战略游戏，背景设定在盟军与苏联作战的架空历史中。艺电（EA）于 2008 年将该游戏转为免费软件，但并未开源原始代码。OpenRA 从头重建了游戏引擎，使其能在现代操作系统上运行，并融入了社区驱动的改进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenRA">OpenRA</a></li>

</ul>
</details>

**社区讨论**: 社区评论普遍非常正面，称赞 OpenRA 的平衡性改进和现代功能。用户指出游戏比原版更具策略性，一些人还感谢 EA 对该项目的容忍。少数人提到了其他类似项目如 OpenRA2，但总体态度是高度支持的。

**标签**: `#open-source`, `#gaming`, `#RTS`, `#game development`

---

<a id="item-6"></a>
## [实体媒体所有权的理由](https://dervis.de/physical/) ⭐️ 7.0/10

一篇文章认为实体媒体是唯一真正的所有权形式，指出许可和 DRM 限制可能撤销对数字购买的访问权限。 这场辩论影响所有数字消费者，近期如索尼从 PlayStation 库中移除已购买内容的例子凸显了数字所有权的脆弱性。 文章引用了失败的 Ultraviolet 服务和索尼 2026 年移除 Studio Canal 内容的例子，表明数字购买通常是可撤销的许可。

hackernews · cemdervis · Jun 27, 11:32 · [社区讨论](https://news.ycombinator.com/item?id=48697335)

**背景**: 数字媒体购买通常带有 DRM（数字版权管理），将访问权限绑定到特定平台或账户。与实体媒体不同，数字文件可以在许可协议变更时被远程禁用或移除。这导致了一场倡导消费者权利和真正所有权的运动。

**社区讨论**: 评论者大多同意文章的观点，有些人认为无 DRM 的数字购买（例如来自 GOG 或 Bandcamp）也构成真正的所有权。其他人则主张将盗版作为应对 DRM 限制的实用解决方案，并提到存在高质量、无限制的翻录版本。

**标签**: `#digital ownership`, `#DRM`, `#physical media`, `#piracy`, `#consumer rights`

---

<a id="item-7"></a>
## [TownSquare：为网站添加轻量级在线状态层](https://cauenapier.com/blog/townsquare_release/) ⭐️ 7.0/10

TownSquare 是一个轻量级、临时的网站在线状态层，显示还有谁在线，旨在重现共享空间的感觉，而无需社交网络的负担。 该项目解决了网络上偶然社交互动的缺失，提供了一种传统社交网络的最小化替代方案，优先考虑临时连接和社区建设。 TownSquare 没有账户、个人资料、关注者数量或永久聊天记录；消息仅在人们在场阅读时存在。它故意设计得小巧且健忘，专注于实时在线状态。

hackernews · eustoria · Jun 27, 17:11 · [社区讨论](https://news.ycombinator.com/item?id=48699928)

**背景**: 早期网络有许多显示谁在网站上的小工具，比如“My Blog Log”小部件，它们培养了社区感。随着时间的推移，这些被具有持久个人资料和数据的集中式社交网络所取代。TownSquare 复兴了这种更古老、更简单的在线状态方法。

**社区讨论**: 评论者对类似过去的项目如“My Blog Log”和 ff0000 表示怀旧，并希望有更多网站支持线下聚会。一些人觉得演示令人困惑，而另一些人则欣赏其极简主义和偶然连接的潜力。

**标签**: `#web development`, `#social software`, `#community`, `#presence`, `#minimalism`

---

<a id="item-8"></a>
## [亚洲 AI 初创公司推出类似 Mythos 的模型](https://techcrunch.com/2026/06/27/asian-ai-startups-launch-mythos-like-models-as-anthropics-export-ban-drags-on/) ⭐️ 7.0/10

包括 Sakana AI 在内的亚洲 AI 初创公司推出了类似 Fugu Ultra 的模型，旨在与 Anthropic 的 Mythos 竞争，此前 Anthropic 对某些地区实施了模型出口禁令。 这一发展凸显了亚洲日益增长的 AI 生态系统以及出口限制对全球 AI 可及性的影响，可能导致市场碎片化，模型质量和成本参差不齐。 Fugu Ultra 并非单一的整体模型，而是一个多智能体编排系统，可在多个底层模型之间路由任务，类似于 OpenRouter 的 Fusion。用户报告显示，Fugu Ultra 在实际任务中的表现不如 Opus，且成本更高、速度更慢。

hackernews · bogdiyan · Jun 27, 13:10 · [社区讨论](https://news.ycombinator.com/item?id=48697958)

**背景**: Anthropic 的 Mythos 是一款高性能 AI 模型，因出口禁令无法进入某些亚洲国家，促使当地初创公司开发替代品。Fugu Ultra 就是其中之一，但它依赖于多个模型的系统而非单一模型，这可能影响其效率和成本。

**社区讨论**: 社区评论显示体验不一：一位用户报告称 Fugu Ultra 比 Opus 更慢且更贵，迅速消耗了积分。另一位评论者指出 Fugu Ultra 是一个多智能体系统而非单一模型，这可能解释了其性能问题。一些人对比缺乏实际基准测试感到沮丧。

**标签**: `#AI`, `#startups`, `#export ban`, `#model comparison`, `#multi-agent systems`

---

<a id="item-9"></a>
## [稳定币使用与资金的地理错配](https://decrypt.co/371967/stablecoin-founder-map-doesnt-match-stablecoin-volume-map) ⭐️ 7.0/10

一项新分析显示，尽管新兴市场占据了稳定币实际使用的大部分份额，但这些项目背后的创始人和风险投资资金却 overwhelmingly 集中在美国和欧洲。 这种地理上的脱节凸显了加密行业资源与注意力的潜在错配，风险投资可能忽视了最需要和使用稳定币的地区，从而可能阻碍新兴市场的创新和采用。 文章提供了数据驱动的见解，显示稳定币交易量在通胀高、银行服务有限的国家最高，但大多数稳定币初创公司总部设在美国和欧洲。

rss · Decrypt · Jun 27, 17:01

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元等法定货币挂钩。它们在新兴市场被广泛用于储蓄、汇款和商业，作为对冲当地货币波动的手段。风险投资资金在开发和扩展这些项目中起着关键作用。

**标签**: `#stablecoins`, `#crypto`, `#venture capital`, `#emerging markets`

---

<a id="item-10"></a>
## [匿名 GitHub 账号批量发布所谓 0day 漏洞](https://github.com/bikini/exploitarium) ⭐️ 6.0/10

一个名为'bikini'的匿名 GitHub 账号创建了仓库'exploitarium'，批量发布了声称未公开的 0day 漏洞，涉及 Ghidra、Docker、nghttp2 和 PHP 等多个项目。 尽管'0day'一词在安全领域分量极重，但社区分析显示大多数提交并非关键漏洞，凸显了仔细核查的必要性，以及炒作可能掩盖真正威胁的风险。 社区专家审查了多个提交，发现许多需要预先拥有高级访问权限（例如能够覆盖二进制文件），或具有非确定性且难以利用，部分漏洞已在上游修复。

hackernews · binyu · Jun 27, 14:31 · [社区讨论](https://news.ycombinator.com/item?id=48698617)

**背景**: 0day 漏洞是指厂商未知且未修复的安全缺陷，因此极具危险性。该术语常被夸大使用。GitHub 是分享概念验证漏洞利用的常见平台，但匿名批量发布需要仔细审查。

**社区讨论**: 社区普遍持怀疑态度：Retr0id 和 dvt 等用户认为这些漏洞并不令人印象深刻或并非真正的 0day，有评论者建议为这种炒作设立新类别'0day 氛围漏洞'。另一用户指出有些似乎是已公开的 CVE。

**标签**: `#security`, `#0-day`, `#vulnerability`, `#GitHub`

---

<a id="item-11"></a>
## [公共 DNS 解析器选择指南](https://evilbit.de/dns-resolver-guide.html) ⭐️ 6.0/10

一份新指南比较了公共 DNS 解析器，涵盖隐私、过滤和性能，社区讨论了自托管替代方案。 这很重要，因为 DNS 选择影响用户隐私和安全；该指南帮助用户在日益增长的监控和审查环境中做出明智决策。 该指南列出了 Cloudflare、Quad9 和 NextDNS 等流行解析器，比较了过滤、日志记录和 DNSSEC 支持等功能。社区评论强调了使用 Unbound 和 DNSCryptProxy 进行自托管。

hackernews · pawal · Jun 27, 22:11 · [社区讨论](https://news.ycombinator.com/item?id=48702273)

**背景**: DNS（域名系统）将域名转换为 IP 地址。公共 DNS 解析器是处理此转换的第三方服务，通常提供增强的隐私或过滤功能。自托管涉及运行自己的解析器以获得完全控制。

**社区讨论**: 一些用户出于完全控制而偏好自托管，并引用数十年的经验。其他人推荐 NextDNS 等托管服务以方便使用。提出的一个实际问题是使用公共 DNS 时如何处理公共 Wi-Fi 的强制门户。

**标签**: `#DNS`, `#privacy`, `#networking`, `#self-hosting`

---

<a id="item-12"></a>
## [金融科技工程手册引发争议](https://w.pitula.me/fintech-engineering-handbook/) ⭐️ 6.0/10

一本金融科技工程手册发布，但被社区批评为内容浅薄且有时提供糟糕的建议，例如推荐使用非整数表示货币值。 这场争论凸显了金融科技中正确处理货币数据的重要性，这是一个错误可能导致财务损失的关键领域。它也显示了社区在维护工程最佳实践高标准方面的警惕性。 该手册涵盖多个金融科技工程主题，但因货币值表示的建议（特别是使用浮点数而非整数）而受到批评。讨论还涉及外汇汇率分辨率和事件溯源。

hackernews · signa11 · Jun 27, 10:28 · [社区讨论](https://news.ycombinator.com/item?id=48696982)

**背景**: 在金融科技中，准确表示货币值对于避免舍入误差和财务差异至关重要。最佳实践通常建议使用整数（例如分）或定点算术，而不是浮点数。事件溯源是用于审计追踪的另一种模式，但并非所有服务都需要它。

**社区讨论**: 像 xlii 和 lxgr 这样的评论者强烈批评手册中关于货币数据的建议，警告不要使用浮点数和次要单位精度策略。其他人如 jdw64 和 belmarca 则提供了更细致的观点，指出虽然有些建议有缺陷，但手册收集了有用的信息，并且上下文很重要。

**标签**: `#fintech`, `#software engineering`, `#monetary data`, `#best practices`

---

<a id="item-13"></a>
## [罗宾·威廉姆斯独白被用来批评大语言模型](https://jayacunzo.com/blog/your-move-chief) ⭐️ 6.0/10

Jay Acunzo 的一篇博客文章引用了电影《心灵捕手》中罗宾·威廉姆斯的独白，认为大语言模型缺乏真正的人类体验，引发了关于人工智能局限性的讨论。 这一讨论突显了人们对人工智能无法真实复制人类意识和生活经验的日益增长的哲学担忧，可能影响公众对 AI 技术的看法和监管。 该独白强调大语言模型可以流利地谈论它们无法拥有的体验，比如品尝草莓或失去亲人，但批评者认为人类故事讲述者也会写他们没有亲身经历的事情。

hackernews · herbertl · Jun 28, 01:28 · [社区讨论](https://news.ycombinator.com/item?id=48703452)

**背景**: 像 GPT-4 这样的大语言模型在大量文本数据上训练，可以生成类似人类的文本，但它们没有主观体验或意识。争论的焦点在于，没有生活经验的人工智能是否能够真正理解或传达意义。

**社区讨论**: 评论意见不一：一些人认为这段独白抓住了大语言模型令人不安的原因，而另一些人则认为人类作家也是通过想象而非个人经历进行创作。少数人觉得这段独白自以为是且居高临下。

**标签**: `#AI`, `#philosophy`, `#LLM`, `#human experience`

---

<a id="item-14"></a>
## [以太坊基金会资金缺口警告](https://www.coindesk.com/markets/2026/06/26/former-ethereum-foundation-leader-warns-of-funding-gap-as-governance-shifts) ⭐️ 6.0/10

一位前以太坊基金会负责人公开警告，在组织治理结构转变之际，存在资金缺口。 这一警告凸显了以太坊基金会潜在的财务不稳定，可能影响以太坊网络的开发和维护，而以太坊是区块链生态系统的基石。 该警告是在以太坊基金会更广泛的治理变革背景下发出的，但未披露资金缺口的具体规模或治理转变的性质。

rss · CoinDesk · Jun 26, 18:37

**背景**: 以太坊基金会是一个支持以太坊区块链的非营利组织。治理转变可能涉及决策流程或领导结构的改变，从而影响资金分配。

**标签**: `#Ethereum`, `#blockchain`, `#governance`, `#funding`

---

<a id="item-15"></a>
## [SBI 控股以 2.89 亿美元收购 Bitbank](https://www.coindesk.com/business/2026/06/26/japanese-financial-services-giant-sbi-holdings-to-buy-bitbank-for-usd289-million) ⭐️ 6.0/10

日本金融服务巨头 SBI 控股宣布以约 2.89 亿美元收购加密货币交易所 Bitbank，这标志着日本加密货币市场的一次重大整合。 此次收购凸显了机构对加密货币交易所日益增长的兴趣，并可能加速日本的主流采用，因为 SBI 控股将利用其广泛的金融网络整合数字资产。 该交易对 Bitbank 的估值为 2.89 亿美元，SBI 控股计划利用此次收购扩展其加密服务，包括托管和交易，同时受益于 Bitbank 的持牌交易所地位。

rss · CoinDesk · Jun 26, 08:31

**背景**: SBI 控股是一家日本大型金融集团，业务涵盖证券、银行和资产管理。Bitbank 是日本持牌加密货币交易所，受金融厅（FSA）监管。此次收购反映了传统金融机构进入加密领域的趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SBI_Holdings">SBI Holdings</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#acquisition`, `#finance`, `#Japan`

---

<a id="item-16"></a>
## [Strategy 130 亿美元比特币浮亏超过数百种代币市值](https://www.coindesk.com/markets/2026/06/26/too-big-to-fail-strategy-s-usd13-billion-bitcoin-paper-loss-alone-dwarfs-hundreds-of-prominent-tokens) ⭐️ 6.0/10

前身为 MicroStrategy 的 Strategy 公司报告其比特币持仓出现 130 亿美元的未实现亏损，这一数字本身就超过了数百种较小加密货币的市值。 这凸显了单一企业实体对加密货币市场的巨大影响，引发了对系统性风险和比特币所有权集中化的担忧。 该浮亏基于比特币价格从 Strategy 平均购买价的下跌计算；该公司持有超过 20 万枚 BTC，是最大的企业比特币持有者。

rss · CoinDesk · Jun 26, 06:37

**背景**: Strategy 是一家商业智能公司，自 2020 年开始积极购买比特币作为储备资产。其大量持仓使其财务状况与比特币价格紧密相关，而浮亏反映的是市场波动而非实际出售。

**标签**: `#bitcoin`, `#cryptocurrency`, `#finance`, `#strategy`

---

<a id="item-17"></a>
## [西班牙：加密企业 MiCA 牌照截止日期不延长](https://decrypt.co/372230/spanish-regulator-no-extensions-eu-crypto-deadline-binance) ⭐️ 6.0/10

西班牙监管机构确认不会延长 MiCA 牌照的截止日期，这意味着像 Binance 这样的未持牌公司必须在 7 月 1 日前停止在欧盟的运营。 这一执法为欧盟范围内的加密货币监管树立了严格先例，可能迫使主要交易所退出或合规，并加速行业整合。 MiCA（加密资产市场）法规要求所有加密资产服务提供商在 2025 年 7 月 1 日前获得牌照；Binance 尽管此前已注册，但在西班牙仍未获得牌照。

rss · Decrypt · Jun 26, 18:02

**背景**: MiCA 是欧盟针对加密资产的全面监管框架，旨在保护投资者并确保市场诚信。它于 2023 年生效，过渡期至 2025 年 7 月。未获得牌照的公司必须停止为欧盟客户提供服务。

**标签**: `#crypto`, `#regulation`, `#EU`, `#MiCA`, `#Binance`

---

<a id="item-18"></a>
## [Base 主网再次停摆，两天内第二次中断](https://www.theblock.co/post/406409/base-suffers-second-mainnet-stall-in-two-days?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Base 主网在两天内第二次出现停摆，区块生产于 UTC 时间 15:33 停止，并于当日 16:11 恢复。 像 Base 这样的主要 Layer 2 网络反复出现中断，引发了对区块链基础设施可靠性的担忧，可能影响用户对以太坊扩容解决方案的信任和采用。 此次停摆持续约 38 分钟，具体原因和影响细节尚未披露。

rss · The Block · Jun 26, 17:50

**背景**: Base 是基于以太坊构建的 Layer 2 区块链，旨在提供更快、更便宜的交易。主网停摆可能由多种技术问题引起，如排序器故障或网络拥堵。

**标签**: `#blockchain`, `#Base`, `#mainnet`, `#outage`

---

<a id="item-19"></a>
## [GENIUS 法案：美国首个联邦稳定币法律](https://www.theblock.co/learn/406286/what-is-the-genius-act?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

GENIUS 法案于 2025 年 7 月 18 日签署成为法律，建立了美国首个针对美元支持的稳定币的联邦监管框架，涵盖发行、储备支持、赎回和监管。 该法律为稳定币发行者和用户提供了法律明确性，可能促进稳定币的采用及其融入更广泛的金融体系，同时确保消费者保护和金融稳定。 该法律规定了谁可以发行支付稳定币、这些代币必须由哪些资产支持、持有者如何赎回以及哪些监管机构监督发行者。

rss · The Block · Jun 26, 06:19

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元等法定货币挂钩。在 GENIUS 法案之前，美国的稳定币监管在各州层面分散，给发行者和用户带来了不确定性。

**标签**: `#stablecoin`, `#regulation`, `#cryptocurrency`, `#fintech`, `#US law`

---