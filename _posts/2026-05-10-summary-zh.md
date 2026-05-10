---
layout: default
title: "Horizon Summary: 2026-05-10 (ZH)"
date: 2026-05-10
lang: zh
---

> From 75 items, 23 important content pieces were selected

---

1. [数学家实测 ChatGPT 5.5 Pro 解决研究问题](#item-1) ⭐️ 9.0/10
2. [Bun 的 Rust 重写达到 99.8% 测试兼容性](#item-2) ⭐️ 8.0/10
3. [互联网档案馆瑞士分部作为独立组织成立](#item-3) ⭐️ 8.0/10
4. [FreeBSD execve() 因缺少括号导致权限提升漏洞](#item-4) ⭐️ 8.0/10
5. [Let-go：用 Go 实现的类 Clojure 语言，启动仅需 7 毫秒](#item-5) ⭐️ 8.0/10
6. [LLM 在委托任务中会损坏文档](#item-6) ⭐️ 8.0/10
7. [Mac 软件分发令开发者沮丧](#item-7) ⭐️ 7.0/10
8. [CPanel 在 4.4 万台服务器遭攻击后修补 3 个漏洞](#item-8) ⭐️ 7.0/10
9. [贝莱德推出新链上基金，深化代币化布局](#item-9) ⭐️ 7.0/10
10. [LayerZero 承认在 2.92 亿美元 Kelp 攻击中犯错](#item-10) ⭐️ 7.0/10
11. [SEC 主席阿特金斯暗示将出台链上市场与 AI 金融新规](#item-11) ⭐️ 7.0/10
12. [Kraken 母公司申请 OCC 联邦银行牌照](#item-12) ⭐️ 7.0/10
13. [比特币矿企 IREN 与英伟达达成 34 亿美元 AI 交易](#item-13) ⭐️ 7.0/10
14. [Zcash 计划在 2027 年前实现后量子密码学里程碑](#item-14) ⭐️ 7.0/10
15. [网页开发者提议禁止查询字符串](#item-15) ⭐️ 6.0/10
16. [Zed 编辑器推出可视化主题构建器](#item-16) ⭐️ 6.0/10
17. [比特币量子迁移可能为时已晚](#item-17) ⭐️ 6.0/10
18. [法官允许 Aave 转移与朝鲜黑客有关的 7100 万美元 ETH](#item-18) ⭐️ 6.0/10
19. [欧央行行长拉加德警告不要照搬美国稳定币模式](#item-19) ⭐️ 6.0/10
20. [AUSTRAC 启动加密货币监管行动](#item-20) ⭐️ 6.0/10
21. [英国央行贝利警告与美国的稳定币监管冲突](#item-21) ⭐️ 6.0/10
22. [TeraWulf 的 HPC 收入首次超过比特币挖矿](#item-22) ⭐️ 6.0/10
23. [Arbitrum DAO 批准释放 7000 万美元 ETH 用于 Kelp DAO 恢复](#item-23) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [数学家实测 ChatGPT 5.5 Pro 解决研究问题](https://gowers.wordpress.com/2026/05/08/a-recent-experience-with-chatgpt-5-5-pro/) ⭐️ 9.0/10

数学家 Timothy Gowers 报告称，ChatGPT 5.5 Pro 是首个能够可靠解决温和研究问题的大语言模型，展示了改进的推理和自我修正能力。 这一进展对博士培养的未来提出了关键问题，因为传统上用于训练学生的温和研究问题可能不再可行，并挑战了人类产生想法的价值。 Gowers 指出，虽然该模型仍会犯很多错误，但它能追踪自身推理并自我修正，远优于之前的模型。然而，ChatGPT 5.5 Pro 的高 token 成本是一个显著缺点。

hackernews · _alternator_ · May 9, 02:41 · [社区讨论](https://news.ycombinator.com/item?id=48071262)

**背景**: 像 GPT-4 这样的大语言模型展示了令人印象深刻的能力，但通常在复杂推理和自我修正方面存在困难。OpenAI 于 2026 年 4 月 23 日发布的 ChatGPT 5.5 Pro 在这些领域迈出了重要一步，基准测试分数的提高证明了这一点。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-5.5">GPT-5.5 - Wikipedia</a></li>
<li><a href="https://epoch.ai/frontiermath">FrontierMath: LLM Benchmark for Advanced AI Math... | Epoch AI</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍同意 Gowers 的评价，指出模型自我修正能力提升但成本高昂。一些人讨论了这对思想价值的哲学影响，John Baez 认为价值可能来自效用而非稀缺性。

**标签**: `#LLM`, `#AI`, `#mathematics`, `#research`, `#education`

---

<a id="item-2"></a>
## [Bun 的 Rust 重写达到 99.8% 测试兼容性](https://twitter.com/jarredsumner/status/2053047748191232310) ⭐️ 8.0/10

Bun 团队通过 AI 辅助将代码从 Zig 移植到 Rust，在 Linux x64 glibc 上达到了 99.8% 的测试兼容性，团队成员 Jarred Sumner 在 Twitter 上宣布了这一进展。 这一里程碑证明了 AI 辅助大规模语言移植的可行性，可能影响 JavaScript 运行时及其他系统软件的开发方式。同时，它也重新引发了关于语言安全性和 Bun 项目方向的讨论。 该重写是实验性的，尚未提交，代码有很大可能被丢弃。移植工作大约在 6 天内借助 AI 工具完成，99.8% 的兼容性仅针对 Linux x64 glibc 平台。

hackernews · heldrida · May 9, 10:12 · [社区讨论](https://news.ycombinator.com/item?id=48073680)

**背景**: Bun 是一个快速的全能 JavaScript 运行时、打包器和包管理器，最初用 Zig 编写。Rust 是一种系统编程语言，以无需垃圾回收的内存安全著称。AI 辅助移植利用大型语言模型在语言间转换代码，可加速迁移但可能引入细微错误。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://techplanet.today/post/buns-bold-experiment-porting-from-zig-to-rust-using-ai-assisted-code-generation">Bun's Bold Experiment: Porting from Zig to Rust Using AI-Assisted Code Generation | TechPlanet</a></li>
<li><a href="https://dev.to/maverickjkp/ladybird-browser-rust-migration-ai-assisted-porting-risks-k83">Ladybird Browser Rust Migration: AI-Assisted Porting Risks - DEV Community</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些人称赞速度和 Rust 的潜在安全性优势，而另一些人则因 AI 参与表示不信任，并质疑项目方向。Bun 团队成员指出该代码是实验性的，可能被丢弃。

**标签**: `#Bun`, `#Rust`, `#JavaScript runtime`, `#AI-assisted development`, `#software engineering`

---

<a id="item-3"></a>
## [互联网档案馆瑞士分部作为独立组织成立](https://blog.archive.org/2026/05/06/internet-archive-switzerland-expanding-a-global-mission-to-preserve-knowledge/) ⭐️ 8.0/10

互联网档案馆瑞士分部作为独立组织在圣加仑成立，由执行董事 Roman Griesfelder 领导，旨在加强全球数字保存并增强应对法律挑战的韧性。 此次扩张创建了一个由独立档案馆组成的分布式网络（与互联网档案馆、互联网档案馆加拿大分部和欧洲分部并列），使数字保存在面对单一司法管辖区的法律威胁时更具韧性。 该组织在法律上独立于美国互联网档案馆，但 Brewster Kahle 及其他董事会成员在其董事会任职。网站最初包含占位文本，社区已注意到这一点。

hackernews · hggh · May 9, 12:00 · [社区讨论](https://news.ycombinator.com/item?id=48074265)

**背景**: 互联网档案馆由 Brewster Kahle 创立，是一个非营利数字图书馆，提供对存档网页、书籍和媒体的免费访问。它曾面临法律挑战，包括出版商因其受控数字借阅项目提起的版权诉讼。在不同国家建立独立组织有助于保护档案馆的使命免受特定司法管辖区法律风险的影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://internetarchive.ch/">Internet Archive Switzerland</a></li>
<li><a href="https://www.heise.de/en/news/Humanity-s-Memory-Internet-Archive-Takes-Root-in-Switzerland-11288180.html">Humanity's Memory: Internet Archive Takes Root in Switzerland</a></li>
<li><a href="https://www.linkedin.com/posts/internet-archive_announcing-the-launch-of-internet-archive-activity-7458530433530482688-xJl3">Announcing the launch of Internet Archive Switzerland 🇨🇭 Thirty...</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了需要类似 Usenet 的去中心化点对点模型来分发内容并抵制删除请求。一些人指出，互联网档案馆加拿大分部尽管独立，但运作上类似于子公司，并质疑瑞士实体真正的独立性。其他人指出网站上的占位文本，暗示其仓促上线。

**标签**: `#digital preservation`, `#Internet Archive`, `#decentralization`, `#open access`, `#libraries`

---

<a id="item-4"></a>
## [FreeBSD execve() 因缺少括号导致权限提升漏洞](https://www.freebsd.org/security/advisories/FreeBSD-SA-26:13.exec.asc) ⭐️ 8.0/10

FreeBSD 的 execve() 系统调用中发现了一个本地权限提升漏洞（CVE-2026-7270），原因是 memmove() 调用中缺少一个括号，导致内存复制错误。该漏洞允许非特权用户以内核权限执行任意代码并获得 root 访问权限。 该漏洞影响广泛使用的操作系统内核，允许本地攻击者完全控制系统。它凸显了在安全关键代码中谨慎编码的重要性，尤其是 C 语言中的运算符优先级问题。 该漏洞出现在 memmove() 调用中，其大小参数计算为 'args->endp - args->begin_argv + consume'，而非正确的 'args->endp - (args->begin_argv + consume)'，导致复制了错误的内存区域。该漏洞已在 FreeBSD 15.0R-p7 及后续更新中修复。

hackernews · Deeg9rie9usi · May 9, 20:31 · [社区讨论](https://news.ycombinator.com/item?id=48077971)

**背景**: execve() 系统调用用于在类 Unix 操作系统中执行程序。它处理参数和环境字符串，其内存管理中的错误可能允许攻击者覆盖内核内存。权限提升漏洞非常关键，因为它允许普通用户获得完全的管理员控制权。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.opennet.ru/opennews/art.shtml?num=65408">Уязвимость в системном вызове execve, предоставляющая root-доступ во FreeBSD</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出根本原因是 memmove() 调用中缺少括号，一些开发者主张在混合运算符表达式中强制使用括号。发现者（Calif.io）发布了详细的分析文章和 AI 生成的漏洞利用代码，安全专家 tptacek 对他们的工作表示赞赏。

**标签**: `#security`, `#FreeBSD`, `#CVE`, `#privilege escalation`, `#kernel`

---

<a id="item-5"></a>
## [Let-go：用 Go 实现的类 Clojure 语言，启动仅需 7 毫秒](https://github.com/nooga/let-go) ⭐️ 8.0/10

Let-go 是一个用纯 Go 实现的新型类 Clojure 语言，冷启动时间约 7 毫秒，比 JVM 上的 Clojure 快约 50 倍，比 Babashka 快 3 倍。它与 JVM Clojure 的兼容性约为 90%，并包含 nREPL 服务器，可与 Calva、CIDER 等 Clojure IDE 配合使用。 该项目弥合了 Clojure 的表达力与 Go 的性能和可移植性之间的差距，提供了一个快速启动、可嵌入的 Lisp，适用于 CLI、Web 服务器和脚本编写。它为需要原生二进制文件和快速启动而又不牺牲语言核心特性的 Clojure 开发者提供了一个可行的替代方案。 Let-go 以约 10MB 的静态二进制文件形式发布，包含自定义编译器和栈式虚拟机，支持 AOT 编译为可移植字节码或独立二进制文件。它可以嵌入到 Go 程序中，实现函数、结构体和通道的无缝互操作，但不加载 JAR 文件，也不提供完整的 Java API 兼容性。

hackernews · marcingas · May 9, 17:52 · [社区讨论](https://news.ycombinator.com/item?id=48076815)

**背景**: Clojure 是一种动态、函数式的 Lisp 方言，运行在 Java 虚拟机 (JVM) 上，以其不可变性和并发支持而闻名。然而，JVM 启动时间较慢，这促使了像 Babashka（使用 GraalVM 的原生 Clojure 解释器）以及现在的 Let-go 等替代方案的出现，后者利用 Go 运行时实现更快的启动和更小的二进制文件。nREPL 是一种网络 REPL 协议，在 Clojure 生态系统中广泛用于交互式开发。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nrepl.org/nrepl/index.html">nREPL :: nREPL</a></li>
<li><a href="https://babashka.org/">Babashka</a></li>
<li><a href="https://en.wikipedia.org/wiki/GraalVM">GraalVM</a></li>

</ul>
</details>

**社区讨论**: 评论者对项目表示赞赏，一些人提到了 Janet、Fennel 和 Joker 等替代方案。一位用户指出 README 中关于启动时间（7ms 与 6ms）的小不一致，另一位用户则对 Go 核心库和通道抽象表示兴奋。还提到了 Glojure 和 Gloat 等相关项目。

**标签**: `#Clojure`, `#Go`, `#programming language`, `#Lisp`, `#performance`

---

<a id="item-6"></a>
## [LLM 在委托任务中会损坏文档](https://arxiv.org/abs/2604.15597) ⭐️ 8.0/10

一项新研究引入了 DELEGATE-52 基准测试，模拟跨 52 个专业领域的长期委托工作流程，发现每次 LLM 处理都会降低文档的意图和精度，类似于反复 JPEG 压缩。 这凸显了 LLM 在自动化文档处理中的关键局限性，削弱了对委托任务的信任，并促使设计最小化 LLM 往返次数的智能体。 该研究测试了包含文件读写和代码执行工具的基本智能体框架，但发现工具使用无法防止损坏。这种现象被称为“语义消融”——即从文本中移除真实的高熵信号。

hackernews · rbanffy · May 9, 08:44 · [社区讨论](https://news.ycombinator.com/item?id=48073246)

**背景**: LLM 常被用于委托工作流程中编辑或重写文档。然而，每次处理往往会移除罕见词汇、生动隐喻和精确细节，这种减法偏差被称为语义消融。这类似于反复保存 JPEG 图像，质量会逐渐下降。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/papers/2604.15597">LLMs Corrupt Documents in Delegation</a></li>
<li><a href="https://ubos.tech/news/semantic-ablation-in-ai-generated-text-implications-for-marketers-and-developers/">Semantic Ablation in AI-Generated Text: Implications for... - UBOS</a></li>
<li><a href="https://en.wikipedia.org/wiki/Ablation_(artificial_intelligence)">Ablation (artificial intelligence) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员普遍认同这一发现，指出经常使用 LLM 的用户已经避免对长内容进行往返处理。一些人建议将 LLM 用作薄薄的翻译层以减少损坏，而另一些人则对工具使用的有效性存在争议。

**标签**: `#LLM`, `#document corruption`, `#semantic ablation`, `#AI limitations`, `#research`

---

<a id="item-7"></a>
## [Mac 软件分发令开发者沮丧](https://blog.kronis.dev/blog/apple-is-increasing-my-cortisol-levels) ⭐️ 7.0/10

一位开发者发表博客文章，抱怨分发 Mac 软件的复杂性和成本不断增加，并指出苹果的守门行为和向后兼容性问题。 这反映了独立 Mac 开发者长期面临的痛点，他们必须应对强制代码签名和公证等日益增高的门槛，这可能扼杀创新并导致开发者离开该平台。 作者指出，苹果的代码签名证书每年需 99 美元（Apple Developer Program）外加额外的公证步骤，而且向后兼容性很差，旧版应用在最新 macOS 上经常无法运行。

hackernews · LorenDB · May 9, 14:40 · [社区讨论](https://news.ycombinator.com/item?id=48075366)

**背景**: 苹果要求所有在 App Store 之外分发的 Mac 应用必须使用开发者 ID 证书签名，并通过苹果的公证以通过 Gatekeeper 安全检查。此过程旨在保护用户免受恶意软件侵害，但给开发者增加了摩擦。用户可以通过终端命令禁用 Gatekeeper，但这会降低安全性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://support.apple.com/guide/security/app-code-signing-process-sec3ad8e6e53/web">App code signing process in macOS - Apple Support</a></li>
<li><a href="https://developer.apple.com/documentation/security/notarizing-macos-software-before-distribution?language=objc">Notarizing macOS software before distribution | Apple Developer...</a></li>
<li><a href="https://www.hexnode.com/blogs/mac-notarization-everything-mac-admins-need-to-know/">Mac notarization : Everything Mac admins need to know</a></li>

</ul>
</details>

**社区讨论**: 评论者大多对作者表示同情，有人指出苹果对向后兼容性的轻视是一个主要问题。一位用户建议不喜欢 Gatekeeper 的用户可以禁用它，但其他人认为这样做过于粗暴。作者还将成本与 Windows 代码签名进行了比较，指出两者同样昂贵。

**标签**: `#macOS`, `#developer experience`, `#software distribution`, `#Apple`, `#code signing`

---

<a id="item-8"></a>
## [CPanel 在 4.4 万台服务器遭攻击后修补 3 个漏洞](https://www.copahost.com/blog/cpanels-black-week-three-new-vulnerabilities-patched-after-ransomware-attack-on-44000-servers/) ⭐️ 7.0/10

CPanel 在勒索软件攻击导致约 4.4 万台服务器被入侵后，发布了针对三个新漏洞的补丁。 此事件凸显了广泛使用的网页托管控制面板中遗留代码的安全风险，影响了数百万台服务器及其用户。 这些漏洞包括一个跨站脚本（XSS）漏洞（CVE-2023-29489），允许攻击者注入恶意脚本。勒索软件攻击针对未修补的系统，强调了及时更新的必要性。

hackernews · ggallas · May 9, 17:06 · [社区讨论](https://news.ycombinator.com/item?id=48076465)

**背景**: CPanel 是一个流行的网页托管控制面板，许多托管提供商用它来管理服务器。遗留代码通常缺乏现代安全特性，使其成为攻击者的诱人目标。勒索软件攻击会加密数据并要求支付赎金以解密。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://nvd.nist.gov/vuln/detail/CVE-2023-29489">CVE-2023-29489 Detail - NVD</a></li>
<li><a href="https://www.acunetix.com/vulnerabilities/web/cpanel-xss-cve-2023-29489/">cPanel XSS (CVE-2023-29489) - Vulnerabilities - Acunetix</a></li>
<li><a href="https://about.gitlab.com/the-source/security/why-legacy-code-is-a-security-risk-and-how-ai-can-help/">Why legacy code is a security risk — and how AI can help</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 CPanel 老化的代码库和缺乏沙箱机制表示担忧，一些用户回忆起过去的黑客攻击，另一些则主张使用自托管替代方案。人们对 CPanel 的安全实践持怀疑态度。

**标签**: `#security`, `#cpanel`, `#vulnerability`, `#ransomware`, `#web hosting`

---

<a id="item-9"></a>
## [贝莱德推出新链上基金，深化代币化布局](https://www.coindesk.com/business/2026/05/09/blackrock-deepens-tokenization-push-with-new-onchain-fund-offerings) ⭐️ 7.0/10

贝莱德向 Securitize 提交了新的代币化国债储备基金申请，并提议为其 70 亿美元货币市场基金创建链上份额。 此举标志着机构对区块链在传统金融中应用的接受度日益提高，可能通过实现碎片化所有权和全天候交易来改变资产管理行业。 代币化国债储备基金通过数字资产证券平台 Securitize 提交，而货币市场基金的链上份额将代表将大规模传统基金引入区块链的重要一步。

rss · CoinDesk · May 9, 13:57

**背景**: 代币化是将现实世界资产（如债券或房地产）的所有权表示为区块链上的数字代币的过程，从而实现碎片化所有权和更便捷的转移。作为全球最大的资产管理公司，贝莱德一直在探索利用区块链提高基金管理的效率和可及性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/05/09/blackrock-deepens-tokenization-push-with-new-onchain-fund-offerings">BlackRock deepens tokenization push with new onchain fund offerings</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tokenized_real-world_asset">Tokenized real-world asset - Wikipedia</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#blockchain`, `#institutional finance`, `#asset management`, `#BlackRock`

---

<a id="item-10"></a>
## [LayerZero 承认在 2.92 亿美元 Kelp 攻击中犯错](https://www.coindesk.com/tech/2026/05/09/layerzero-says-it-made-a-mistake-in-usd292-million-kelp-exploit) ⭐️ 7.0/10

LayerZero 承认，一名多重签名签署者使用生产硬件钱包进行个人交易，导致 Kelp DAO 遭受 2.92 亿美元攻击，这是 2026 年最大的 DeFi 黑客事件。 这一事件凸显了跨链基础设施中关键的操作安全风险，一次人为失误就可能危及数十亿美元的用户资金，动摇了人们对 LayerZero 及类似协议的信任。 攻击发生在 2026 年 4 月 18 日，从 Kelp DAO 盗走了 2.937 亿美元的 rsETH。LayerZero 披露了一起此前未报告的事件，一名多重签名签署者使用其生产硬件钱包执行个人交易，这很可能暴露了私钥。

rss · CoinDesk · May 9, 13:53

**背景**: LayerZero 是一个跨链互操作协议，通过超轻节点实现区块链间的安全消息传递。多重签名钱包需要多个签署者授权交易，但如果一个签署者的私钥被泄露，整个钱包就可能被盗。Kelp DAO 是一个流动性再质押协议，将用户存入的 ETH 通过 EigenLayer 路由以获取额外收益。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.blockhead.co/2026/04/20/kelp-dao-loses-292m-in-largest-defi-exploit-of-2026-layerzero-attributes-attack-to-lazarus-group/">Kelp DAO Loses $292M in Largest DeFi Exploit of 2026, LayerZero...</a></li>
<li><a href="https://www.dlnews.com/articles/defi/kelp-dao-defi-protocol-hacked-for-300-million/">Hackers target DeFi protocol Kelp DAO in massive $300m exploit</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#LayerZero`, `#exploit`, `#cross-chain`

---

<a id="item-11"></a>
## [SEC 主席阿特金斯暗示将出台链上市场与 AI 金融新规](https://www.coindesk.com/policy/2026/05/08/sec-chair-atkins-signals-new-rules-for-onchain-markets-ai-driven-finance) ⭐️ 7.0/10

SEC 主席保罗·阿特金斯宣布，SEC 正在考虑对链上交易系统、区块链结算基础设施、自动化金融应用和加密托管库进行正式规则制定，标志着监管方式的转变。 这标志着重大政策转变，可能重塑美国对基于区块链的金融系统和 AI 驱动金融的监管方式，影响加密和 AI 行业的创新与合规。 阿特金斯指出，现有证券规则围绕经纪商、交易所等传统中介设计，而新型区块链系统常将这些功能整合到单一软件协议中，因此需要新规则。

rss · CoinDesk · May 8, 18:32

**背景**: SEC（美国证券交易委员会）是监管证券市场的美国机构。链上市场指基于区块链技术的交易和结算系统，而 AI 驱动金融则利用人工智能实现自动化金融服务。现行规则未能明确涵盖这些新兴技术。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/policy/2026/05/08/sec-chair-atkins-signals-new-rules-for-onchain-markets-ai-driven-finance">SEC chair Paul Atkins signals rule changes for onchain markets and AI-driven finance</a></li>

</ul>
</details>

**标签**: `#SEC`, `#regulation`, `#blockchain`, `#AI`, `#finance`

---

<a id="item-12"></a>
## [Kraken 母公司申请 OCC 联邦银行牌照](https://www.coindesk.com/policy/2026/05/08/kraken-parent-goes-for-the-occ-charter-in-big-to-become-a-federal-crypto-bank) ⭐️ 7.0/10

Kraken 的母公司 Payward 已向美国货币监理署（OCC）申请联邦银行牌照，拟成立 Payward National Trust Company（PNTC），这是一家专注于数字资产受托托管及相关服务的联邦监管实体。 如果获批，这将标志着加密服务融入美国传统银行体系的重要一步，为机构和零售客户提供联邦监管下的银行级托管保护，并可能推动数字资产的主流采用。 该申请补充了 Kraken 现有的怀俄明州特殊目的存管机构（SPDI）牌照，该牌照已允许其在州法律下托管数字资产并接受法币存款。PNTC 将主要服务于寻求 OCC 监管下增强托管保护的机构和客户。

rss · CoinDesk · May 8, 17:00

**背景**: OCC 是美国负责颁发和监管国家银行的联邦机构。近年来，它对数字资产表现出开放态度，有条件地批准了 Erebor Bank 等加密公司的国家信托银行牌照。怀俄明州的 SPDI 框架旨在允许加密企业作为州特许银行运营，Kraken Financial 于 2020 年成为首家获得该牌照的加密交易所。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/policy/2026/05/08/kraken-parent-goes-for-the-occ-charter-in-big-to-become-a-federal-crypto-bank">Kraken parent goes for the OCC charter in bid to become a federal crypto bank</a></li>
<li><a href="https://www.kraken.com/learn/finance/spdi-bank-charter">What is the SPDI Charter? | SPDI Framework | Kraken</a></li>
<li><a href="https://www.coindesk.com/policy/2025/10/15/crypto-bank-erebor-approved-for-conditional-federal-bank-charter-by-occ">Crypto Bank Erebor Approved for Conditional Federal Bank Charter by OCC</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#banking`, `#Kraken`, `#OCC`

---

<a id="item-13"></a>
## [比特币矿企 IREN 与英伟达达成 34 亿美元 AI 交易](https://decrypt.co/367289/bitcoin-miner-iren-secures-3-4-billion-nvidia-ai-deal) ⭐️ 7.0/10

IREN Limited 宣布与英伟达达成 34 亿美元的云服务协议，计划利用英伟达 DSX 架构部署高达 5 吉瓦的 AI 基础设施，英伟达获得五年内以每股 70 美元购买最多 3000 万股 IREN 股票的选择权，潜在投资额达 21 亿美元。 这笔交易标志着加密货币挖矿与 AI 基础设施的重大融合，比特币矿企将其能源和数据中心专业知识重新用于高性能 AI 计算。同时凸显了英伟达通过与专业基础设施提供商合作来锁定长期 AI 计算容量的战略。 该协议涉及利用英伟达 DSX 架构部署高达 5 吉瓦的 AI 基础设施，英伟达的股票选择权可在五年内以每股 70 美元行使。IREN 股价在盘后交易中飙升，但随后因公司财报不及预期而回落。

rss · Decrypt · May 8, 17:02

**背景**: IREN（前身为 Iris Energy）是一家比特币挖矿公司，正转向 AI 计算服务，利用其现有的数据中心基础设施和能源合同。英伟达的 DSX（数据中心 GPU 超级计算）架构专为大规模 AI 工作负载设计。这笔交易反映了比特币矿企向 AI 领域多元化的更广泛趋势，因为加密挖矿行业面临日益增长的能源成本和监管审查。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367289/bitcoin-miner-iren-secures-3-4-billion-nvidia-ai-deal">Bitcoin Miner IREN Secures $3.4 Billion Nvidia AI Deal, With $2.1 Billion Share Option - Decrypt</a></li>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/bitcoin-miner-iren-secures-3-170238176.html">Bitcoin Miner IREN Secures $3.4 Billion Nvidia AI Deal, With $2.1 Billion Share Option</a></li>
<li><a href="https://bitcoinethereumnews.com/bitcoin/bitcoin-miner-iren-secures-3-4-billion-nvidia-ai-deal-with-2-1-billion-share-option/">Bitcoin Miner IREN Secures $3.4 Billion Nvidia AI Deal, With $2.1 Billion Share Option</a></li>

</ul>
</details>

**标签**: `#AI`, `#Nvidia`, `#Bitcoin mining`, `#infrastructure`, `#finance`

---

<a id="item-14"></a>
## [Zcash 计划在 2027 年前实现后量子密码学里程碑](https://decrypt.co/367250/zcash-targeting-post-quantum-crypto-milestone-by-2027) ⭐️ 7.0/10

Zcash 宣布了到 2027 年实现完全后量子安全性的路线图，首先将在一个月内（2026 年 6 月）推出量子可恢复钱包。 这对注重隐私的加密货币来说是一个重要步骤，因为量子计算机对当前的密码系统构成了生存威胁。Zcash 的积极时间表可能为其他区块链项目树立先例。 量子可恢复钱包充当安全和迁移层，允许用户在密钥因量子攻击而泄露时恢复资金。Zcash 计划在 12 到 18 个月内完全实现后量子化，同时将吞吐量扩展到 Visa 和 Mastercard 级别。

rss · Decrypt · May 8, 13:15

**背景**: 后量子密码学是指能够抵御量子计算机攻击的密码算法。当前的区块链系统依赖椭圆曲线密码学，而足够强大的量子机器可能破解它。Zcash 是一种注重隐私的加密货币，使用零知识证明来隐藏交易细节。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367250/zcash-targeting-post-quantum-crypto-milestone-by-2027">Zcash Targeting Post-Quantum Crypto Milestone by 2027 - Decrypt</a></li>
<li><a href="https://www.coindesk.com/tech/2026/05/08/zcash-to-roll-out-quantum-recoverable-wallets-within-a-month-go-quantum-proof-by-2027">Zcash to add quantum-recoverable wallets within a month, go post-quantum by 2027</a></li>
<li><a href="https://coinjournal.net/news/zcash-plans-quantum-resistant-upgrade-as-crypto-braces-for-future-risks/">Zcash plans quantum-resistant upgrade as crypto braces for future risks - CoinJournal</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#post-quantum cryptography`, `#privacy`, `#blockchain`, `#Zcash`

---

<a id="item-15"></a>
## [网页开发者提议禁止查询字符串](https://chrismorgan.info/no-query-strings) ⭐️ 6.0/10

Chris Morgan 发表了一篇观点文章，主张在其个人网站上全面禁止 URL 中的查询字符串，对任何包含查询字符串的请求返回 414 错误。 这引发了关于网络最佳实践的讨论，因为查询字符串广泛用于跟踪、分析和动态内容，但也会导致缓存问题和安全担忧。 该网站对任何带有查询字符串的 URL 返回 HTTP 414（URI 过长），从而有效阻止所有此类请求。作者以缓存、安全和美观为由实施禁令。

hackernews · susam · May 9, 16:28 · [社区讨论](https://news.ycombinator.com/item?id=48076173)

**背景**: 查询字符串是 URL 中 '?' 之后的部分，常用于传递跟踪代码或搜索查询等参数。它们可能干扰缓存，因为不同的查询字符串会为同一资源创建不同的 URL，并且可能被用于跟踪或注入攻击。

**社区讨论**: 评论者讨论了实际影响，一些人指出查询字符串对于分析和动态内容至关重要，而另一些人同意它们可能被滥用。有人指出返回 414 错误是一种激进的措施，会惩罚用户。

**标签**: `#web development`, `#URLs`, `#caching`, `#security`, `#best practices`

---

<a id="item-16"></a>
## [Zed 编辑器推出可视化主题构建器](https://zed.dev/theme-builder) ⭐️ 6.0/10

Zed 编辑器于 2026 年 2 月 12 日发布了主题构建器工具，用户无需编辑 JSON 文件即可可视化地自定义编辑器主题。 该工具降低了创建和分享自定义主题的门槛，增强了 Zed 用户的个性化体验，并可能吸引更多开发者使用该编辑器。 主题构建器是一个可视化编辑器，用户可以从现有主题开始，实时调整各种 UI 和语法元素的颜色。

hackernews · cuechan · May 9, 17:30 · [社区讨论](https://news.ycombinator.com/item?id=48076651)

**背景**: Zed 是由创建 Atom 和 Tree-sitter 的同一团队开发的高性能代码编辑器。此前，创建自定义主题需要手动编辑 JSON 配置文件并重新加载编辑器才能看到更改。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zed.dev/theme-builder">Theme Builder — Zed</a></li>
<li><a href="https://zed.dev/blog/theme-builder">Introducing Theme Builder — Zed's Blog</a></li>
<li><a href="https://zed.dev/docs/themes">Themes | Themes - Zed</a></li>

</ul>
</details>

**社区讨论**: 社区成员对该工具表示赞赏，一些人指出它终于让他们能够创建高对比度主题。其他人则希望增加悬停预览受影响元素等功能，以及更细粒度的 UI 调整。

**标签**: `#zed`, `#editor`, `#theme`, `#developer-tools`

---

<a id="item-17"></a>
## [比特币量子迁移可能为时已晚](https://www.coindesk.com/business/2026/05/09/it-might-be-too-late-for-bitcoin-s-quantum-migration-project-eleven-report-argues) ⭐️ 6.0/10

Project Eleven 的一份报告指出，比特币可能来不及在量子计算机成为威胁之前迁移到抗量子密码学。 如果属实，这可能意味着比特币的密码学安全性面临风险，可能动摇整个加密货币生态系统的信任。 比特币目前使用 ECDSA 进行交易签名，该算法易受 Shor 算法的量子攻击。报告指出，迁移过程复杂且需要社区协调行动。

rss · CoinDesk · May 9, 16:00

**背景**: 后量子密码学（PQC）旨在开发能够抵御量子计算机攻击的算法。虽然当前量子计算机尚不足以破解现有密码，但专家警告称，由于迁移需要时间，必须尽早开始。比特币的去中心化特性使得协调升级尤为困难。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Quantum-resistant_cryptography">Quantum-resistant cryptography</a></li>
<li><a href="https://www.coindesk.com/tech/2026/03/28/watch-out-bitcoin-devs-google-says-post-quantum-migration-needs-to-happen-by-2029">Watch out Bitcoin devs. Google says post- quantum migration needs...</a></li>

</ul>
</details>

**标签**: `#bitcoin`, `#quantum computing`, `#cryptography`, `#blockchain`

---

<a id="item-18"></a>
## [法官允许 Aave 转移与朝鲜黑客有关的 7100 万美元 ETH](https://www.coindesk.com/policy/2026/05/09/judge-clears-path-for-aave-to-move-usd71-million-in-eth-linked-to-north-korea-hack) ⭐️ 6.0/10

美国法官裁定，Aave 可以转移因与朝鲜黑客组织 Lazarus 有关联而被冻结的 7100 万美元以太坊（ETH）。这一决定允许该 DeFi 协议重新控制这些资金，并可能将其返还给受影响的用户。 这一裁决为 DeFi 中如何处理与非法活动相关的冻结加密资产树立了法律先例，可能影响未来类似案件。它也凸显了去中心化金融与传统法律体系之间日益紧密的交集，对治理和资产追回产生影响。 这些资金最初于 2022 年 6 月被 Lazarus Group 从 Harmony 的 Horizon 跨链桥盗走，后因智能合约交互而卡在 Aave 中。法院命令特别允许 Aave 执行一项治理提案来转移 ETH，但并未确定最终所有权。

rss · CoinDesk · May 9, 04:16

**背景**: Aave 是一个去中心化金融（DeFi）协议，允许用户在没有中介的情况下借贷加密货币。Lazarus Group 是一个朝鲜国家支持的黑客组织，以大规模加密货币盗窃闻名，包括 1 亿美元的 Harmony 跨链桥攻击。DeFi 中的冻结资产通常需要复杂的法律和治理流程才能解锁。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Aave">Aave - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lazarus_Group">Lazarus Group - Wikipedia</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#crypto`, `#legal`, `#Aave`, `#security`

---

<a id="item-19"></a>
## [欧央行行长拉加德警告不要照搬美国稳定币模式](https://www.coindesk.com/business/2026/05/08/ecb-s-lagarde-warns-tether-and-circle-stablecoins-risk-digital-dollarisation-in-europe) ⭐️ 6.0/10

欧洲央行行长克里斯蒂娜·拉加德警告称，在欧洲采用美国稳定币模式可能导致数字美元化，并敦促推进数字欧元的开发。 这一警告凸显了依赖外国发行的稳定币所带来的地缘政治和货币主权风险，可能影响欧洲对数字货币的监管方式，并加速数字欧元项目。 拉加德认为，以欧元计价的稳定币可能破坏金融稳定和货币政策，并强调数字欧元（一种央行数字货币）是更安全的选择。

rss · CoinDesk · May 8, 16:11

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元等法定货币挂钩。数字欧元是欧洲央行的央行数字货币项目，旨在提供由央行支持的数字支付方式，与私人稳定币不同。数字美元化是指外国稳定币可能主导一国数字支付、削弱其货币主权的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Central_bank_digital_currency">Central bank digital currency - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Digital_euro">Digital euro</a></li>
<li><a href="https://www.tandfonline.com/doi/full/10.1080/2329194X.2025.2552378">The digital dollarization dilemma: Stablecoins and monetary subordination: The Japanese Political Economy: Vol 51 , No 1-2 - Get Access</a></li>

</ul>
</details>

**标签**: `#digital currency`, `#regulation`, `#stablecoins`, `#ECB`, `#finance`

---

<a id="item-20"></a>
## [AUSTRAC 启动加密货币监管行动](https://decrypt.co/367236/austrac-launches-supervision-campaigns-as-australias-crypto-regulatory-reforms-kick-in) ⭐️ 6.0/10

澳大利亚金融情报机构 AUSTRAC 启动了两项针对性监管行动，覆盖 63 家加密货币公司，包括场外交易商和交易所，以评估其在新的监管改革下反洗钱和反恐融资的合规情况。 这标志着澳大利亚在扩大加密货币监管框架后的首次重大执法行动，新框架现已涵盖托管和经纪服务，表明对不合规公司的审查和潜在处罚将更加严格。 这些行动评估了 36 家场外交易商和 27 家交易所，重点关注对 2026 年 7 月 1 日生效的旅行规则的合规情况，该规则要求虚拟资产服务提供商共享交易信息。

rss · Decrypt · May 8, 10:13

**背景**: 澳大利亚一直在更新其反洗钱法律，将加密资产纳入与传统金融相同的监管框架。2025 年《公司法修正案（数字资产框架）法案》于 2026 年 4 月通过，要求数字资产平台持有澳大利亚金融服务牌照。AUSTRAC 的监管行动是这一更广泛监管推动的一部分，旨在确保加密货币公司实施强有力的反洗钱和反恐融资措施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367236/austrac-launches-supervision-campaigns-as-australias-crypto-regulatory-reforms-kick-in">AUSTRAC Launches Supervision Campaigns as... - Decrypt</a></li>
<li><a href="https://www.binance.com/en/square/post/05-08-2026-austrac-initiates-supervisory-campaigns-in-australia-s-crypto-sector-320898607363938">AUSTRAC Initiates Supervisory Campaigns in Australia's Crypto...</a></li>
<li><a href="https://bytewit.co/news/austrac-launches-supervisory-campaigns-for-australian-crypto-reforms">AUSTRAC Supervisory Campaigns Target 63 Crypto... | Bytewit</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#Australia`, `#AML`

---

<a id="item-21"></a>
## [英国央行贝利警告与美国的稳定币监管冲突](https://www.theblock.co/post/400639/boes-bailey-warns-of-looming-wrestle-with-us-over-stablecoin-rules-flags-run-risk-for-uk?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

英国央行行长安德鲁·贝利警告称，英国可能面临与美国在稳定币规则上的监管“角力”，并指出稳定币挤兑风险可能影响英国金融稳定。 这凸显了加密货币监管方面日益加剧的国际紧张局势，以及稳定币不稳定性可能跨境蔓延，威胁英国等司法管辖区的金融体系。 担任金融稳定委员会主席的贝利警告称，难以赎回的美国稳定币可能在危机期间涌入英国等司法管辖区，加剧挤兑风险。

rss · The Block · May 9, 19:56

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元等法定货币 1:1 挂钩。然而，它们存在挤兑风险，因为其基础资产可能不透明或缺乏流动性，尤其是在市场压力时期。金融稳定委员会是一个监测全球金融体系的国际机构，一直在制定加密货币监管提案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.investopedia.com/hidden-risks-of-widespread-adoption-of-stablecoin-11747043">Stablecoins: Understanding the Hidden Run Risk and Financial Stability Challenges</a></li>
<li><a href="https://www.bis.org/publ/work905.pdf">BIS Working Papers No 905 Stablecoins: risks, potential and regulation</a></li>
<li><a href="https://www.fsb.org/">Financial Stability Board - Promoting global financial stability ...</a></li>

</ul>
</details>

**标签**: `#stablecoins`, `#regulation`, `#financial stability`, `#UK`, `#crypto`

---

<a id="item-22"></a>
## [TeraWulf 的 HPC 收入首次超过比特币挖矿](https://www.theblock.co/post/400578/terawulfs-21-million-hpc-revenue-surpasses-bitcoin-mining-first-time-q1?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

TeraWulf 报告 2026 年第一季度总收入为 3400 万美元，其中 HPC 租赁收入达到 2100 万美元，首次超过比特币挖矿收入（不到 1300 万美元）。 这一里程碑标志着比特币挖矿行业的重大转变，矿工们正在向 AI 和高性能计算领域多元化发展，以减少对波动性加密货币市场的依赖。 总收入同比基本持平，为 3400 万美元，而 HPC 收入跃升至总收入的 62%，远高于此前几个季度的占比。

rss · The Block · May 8, 15:37

**背景**: TeraWulf 是一家美国数字基础设施公司，最初专注于使用可持续能源进行比特币挖矿。近年来，许多比特币矿商开始将其数据中心改造用于 AI 和 HPC 工作负载，以获取更高且更稳定的收入来源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/400578/terawulfs-21-million-hpc-revenue-surpasses-bitcoin-mining-first-time-q1">TeraWulf’s $21 million HPC revenue surpasses bitcoin mining for first time in Q1 | The Block</a></li>
<li><a href="https://www.spglobal.com/market-intelligence/en/news-insights/research/2026/02/bitcoin-miners-pivot-to-ai-and-hpc-as-cryptocurrency-market-slumps">Bitcoin miners pivot to AI and HPC as cryptocurrency market slumps | S&P Global</a></li>
<li><a href="https://en.wikipedia.org/wiki/TeraWulf">TeraWulf - Wikipedia</a></li>

</ul>
</details>

**标签**: `#bitcoin mining`, `#HPC`, `#AI`, `#revenue diversification`

---

<a id="item-23"></a>
## [Arbitrum DAO 批准释放 7000 万美元 ETH 用于 Kelp DAO 恢复](https://www.theblock.co/post/400527/arbitrum-dao-approves-eth-release?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Arbitrum DAO 已批准释放价值 7000 万美元的 ETH，以帮助 Kelp DAO 从一次攻击中恢复，但法院命令和 Aave 的紧急动议使该过程复杂化。 这一决定凸显了去中心化治理与法律体系的交叉，因为 DAO 的链上投票可能受到链外法院命令的挑战。它也强调了 DeFi 恢复工作中的风险和复杂性。 5 月 1 日的法院命令限制 Arbitrum DAO 转移已追回的资金，促使 Aave 提交紧急动议以撤销限制通知。这些资金来自 Kelp DAO 攻击中被冻结的资产。

rss · The Block · May 8, 07:25

**背景**: Arbitrum DAO 是一个去中心化自治组织，管理 Arbitrum One 和 Nova 链，其金库可通过社区投票分配。Kelp DAO 是以太坊上的一个流动性再质押协议，曾遭受攻击导致资金被冻结。Aave 是一个主要的 DeFi 借贷协议，在纽约法院提交了紧急动议，以挑战针对 Arbitrum DAO 的限制通知。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thedefiant.io/newsletter/defi-daily/aave-challenges-restraining-notice">Aave Challenges Restraining Notice - "The Defiant"</a></li>
<li><a href="https://investincryptonews.com/ethereum-freeze-battle-intensifies-as-aave-seeks-restraining-notice-lift/">Ethereum Freeze Battle Intensifies As Aave ... - Invest In Crypto News</a></li>
<li><a href="https://ethdaily.io/939">#939 - Aave Fights Restraint On Kelp Funds, Glamsterdam Targets...</a></li>

</ul>
</details>

**标签**: `#Arbitrum`, `#DAO`, `#DeFi`, `#governance`, `#legal`

---