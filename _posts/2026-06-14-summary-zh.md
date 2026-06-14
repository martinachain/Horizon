---
layout: default
title: "Horizon Summary: 2026-06-14 (ZH)"
date: 2026-06-14
lang: zh
---

> From 67 items, 16 important content pieces were selected

---

1. [本田思域车机更新使用 AOSP 测试密钥签名](#item-1) ⭐️ 8.0/10
2. [人口普查局禁止在统计产品中使用噪声注入](#item-2) ⭐️ 8.0/10
3. [GLM 5.2 作为完全开放的前沿模型发布](#item-3) ⭐️ 8.0/10
4. [对 UI 动画不完美帧的批评](#item-4) ⭐️ 8.0/10
5. [胰腺癌治疗或揭示癌症总开关](#item-5) ⭐️ 8.0/10
6. [亚马逊 CEO 谈话引发美国对 Anthropic AI 的打击](#item-6) ⭐️ 8.0/10
7. [谷歌起诉利用 Gemini AI 进行钓鱼诈骗的中国犯罪团伙](#item-7) ⭐️ 8.0/10
8. [AI 代理仍易受提示注入攻击](#item-8) ⭐️ 8.0/10
9. [密码学家对比特币量子威胁意见分歧](#item-9) ⭐️ 7.0/10
10. [Coinbase 报告警告地址重用使数百万比特币面临量子风险](#item-10) ⭐️ 7.0/10
11. [失传 28 年的 Game Boy WorkBoy 配件重见天日](#item-11) ⭐️ 6.0/10
12. [华尔街从加密试点转向深入以太坊](#item-12) ⭐️ 6.0/10
13. [美国政府押注 20 亿美元于量子计算，国防领域落后](#item-13) ⭐️ 6.0/10
14. [月之暗面推出 Kimi Work，将 300 个 AI 代理带到桌面](#item-14) ⭐️ 6.0/10
15. [Exodus 与 Ondo 在 Solana 上推出代币化股票和 ETF](#item-15) ⭐️ 6.0/10
16. [韩国：代币化股票属于证券，非加密资产](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [本田思域车机更新使用 AOSP 测试密钥签名](https://juniperspring.org/posts/honda-evil-valet/) ⭐️ 8.0/10

安全研究人员发现，第十代本田思域车机的固件更新使用公开的 AOSP 测试密钥签名，通过 USB 物理访问即可执行任意代码。 该漏洞影响一款热门消费车型，并凸显了汽车行业在软件安全方面的系统性弱点，制造商往往缺乏严格的固件签名实践。 这些更新本质上是 Android 4.2.2rc1 恢复包，带有可被伪造的本田特定版本检查，使用 AOSP 测试密钥意味着无需 root 权限即可刷入自定义包。

hackernews · librick · Jun 14, 00:49 · [社区讨论](https://news.ycombinator.com/item?id=48523080)

**背景**: AOSP 测试密钥是 Android 开源项目中仅用于开发的默认签名密钥，绝不应在生产设备中使用。本田第十代思域车机运行基于 Android 的自定义系统，通过特殊格式的 USB 驱动器接受固件更新。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/wfairclough/android_aosp_keys">wfairclough/android_aosp_keys: The platform keys that are used as test ...</a></li>
<li><a href="https://stackoverflow.com/questions/57959598/aosp-building-replace-my-own-keys-with-default-test-keys">AOSP building: replace my own keys with default test-keys - Stack Overflow</a></li>
<li><a href="https://xdaforums.com/t/security-test-keys-vs-release-keys.1937469/">Security: Test keys vs Release Keys - XDA Forums</a></li>

</ul>
</details>

**社区讨论**: 评论者反应不一：一些人批评本田的软件实践，而另一些人指出这实际上给了车主更多控制权。少数人指出了固件更新签名验证被忽视的行业普遍问题。

**标签**: `#automotive security`, `#Android`, `#firmware`, `#vulnerability`, `#Honda`

---

<a id="item-2"></a>
## [人口普查局禁止在统计产品中使用噪声注入](https://desfontain.es/blog/banning-noise.html) ⭐️ 8.0/10

美国人口普查局根据商务部新的行政命令，禁止在其统计产品中使用噪声注入（一种差分隐私技术）。 这一政策变化削弱了人口普查数据的隐私保护，可能导致个人身份被重新识别，并侵蚀公众对政府数据收集的信任。 该禁令适用于人口普查局和经济分析局，迫使它们依赖聚合和四舍五入等替代方法，而非噪声注入。

hackernews · nl · Jun 13, 13:54 · [社区讨论](https://news.ycombinator.com/item?id=48517377)

**背景**: 噪声注入通过向数据添加微小的随机变化来防止个人身份识别，同时保持统计准确性。差分隐私是一种正式的隐私保护框架，自 2020 年人口普查以来，人口普查局一直使用它来防范重建攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bea.gov/help/faq/1490">Why didn't BEA use noise infusion as its statistical disclosure ...</a></li>
<li><a href="https://www.npr.org/2026/06/12/nx-s1-5855734/census-bureau-data-differential-privacy">Trump privacy restrictions may reduce Census Bureau data : NPR</a></li>
<li><a href="https://www.census.gov/about/policies/privacy/statistical_safeguards.html">Statistical Safeguards</a></li>

</ul>
</details>

**社区讨论**: 评论者担心该禁令削弱了人们对人口普查数据处理的信任，一些人指出，强大的行为者可能已经在从汇总统计数据中重建个人数据。其他人则认为，破坏数据收集基础设施是一个错误，将损害政策制定。

**标签**: `#privacy`, `#census`, `#differential privacy`, `#data policy`, `#statistics`

---

<a id="item-3"></a>
## [GLM 5.2 作为完全开放的前沿模型发布](https://twitter.com/jietang/status/2065784751345287314) ⭐️ 8.0/10

Z.ai（原智谱 AI）于 2026 年 6 月 2 日发布了 GLM 5.2，这是一个完全开放的前沿模型，拥有 100 万 token 的上下文窗口，采用 MIT 许可证。 此次发布挑战了美国对 AI 模型的限制，表明开放权重模型可以保持可访问性和竞争力，对 AI 发展具有重要的地缘政治意义。 GLM 5.2 是一个以编码为先的模型，拥有 100 万可用上下文窗口（相比 GLM 5.1 的 20 万提升了 5 倍），其权重采用宽松的 MIT 开源许可证发布。

hackernews · aloknnikhil · Jun 13, 16:18 · [社区讨论](https://news.ycombinator.com/item?id=48518684)

**背景**: 前沿模型是最先进的通用 AI 模型，通常需要巨大的计算资源。Z.ai 是一家中国 AI 公司，开发 GLM 系列大语言模型。此次发布正值美国政府限制某些前沿模型（如“Fable 5”事件）之际，引发了关于开放科学和 AGI 可及性的讨论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://codersera.com/blog/glm-5-2-release-1m-context-coding-2026/">GLM 5.2 Release — 1M Context, Coding-First (June 2026)</a></li>
<li><a href="https://github.com/47thtechcorner/RayCodes_GLM_5.2">47thtechcorner/RayCodes_GLM_5.2 - GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Z.ai">Z.ai - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区赞扬 Z.ai 公开发布 GLM 5.2，并将其与美国对 Fable 等模型的审查进行对比。评论者注意到发布时间（与 Anthropic 受限同日），并强调了开放权重模型对于确保战略 AI 能力可及性的价值。

**标签**: `#AI`, `#open source`, `#GLM`, `#geopolitics`, `#frontier models`

---

<a id="item-4"></a>
## [对 UI 动画不完美帧的批评](https://tonsky.me/blog/every-frame-perfect/) ⭐️ 8.0/10

一篇题为《Every Frame Perfect》的博客文章详细批评了 UI 动画中的不完美帧，以 macOS 为例，认为即使是微小的瑕疵也会降低用户体验。 这很重要，因为它挑战了容忍微小动画瑕疵的常见做法，可能影响 UI/UX 设计标准，并提高软件质量的门槛。 作者提供了 macOS 中的具体例子，如抖动的保存对话框和故障的按钮动画，并认为每一帧在视觉上都应合理，即使在过渡期间也是如此。

hackernews · ravenical · Jun 13, 11:40 · [社区讨论](https://news.ycombinator.com/item?id=48516251)

**背景**: UI 动画用于在软件界面中提供视觉反馈和平滑过渡。然而，由于性能限制或实现问题，某些帧可能看起来不正确或不协调，这会降低用户体验。

**社区讨论**: 评论反应不一：一些人同意批评但质疑前提，认为运动感知与静态分析不同；另一些人指出许多动画是不必要的，可以用即时过渡代替。

**标签**: `#UI/UX`, `#animation`, `#macOS`, `#software engineering`

---

<a id="item-5"></a>
## [胰腺癌治疗或揭示癌症总开关](https://economist.com/science-and-technology/2026/06/12/treating-pancreatic-tumours-may-have-revealed-cancers-master-switch) ⭐️ 8.0/10

一种针对此前被认为不可成药的 KRAS 突变的新型胰腺癌靶向疗法，在临床试验中显示出令人鼓舞的早期结果。该疗法专门针对存在于约 90%胰腺癌中的 KRAS G12D 突变。 这一突破可能改变胰腺癌的治疗格局，胰腺癌是最致命的癌症之一，五年生存率低于 10%。它还表明，像 KRAS 这样此前被认为“不可成药”的靶点可以被攻克，为其他难治性癌症的疗法打开了大门。 该疗法适用于约 20%携带 KRAS 突变的肿瘤，而非所有癌症。所引用的研究是一项临床试验（NCT06625320），评估 KRAS G12D 抑制剂或降解剂，早期研究显示安全性可控且疗效有前景。

hackernews · andsoitis · Jun 13, 13:34 · [社区讨论](https://news.ycombinator.com/item?id=48517199)

**背景**: KRAS 是一种基因，其产生的蛋白质参与细胞生长信号传导。KRAS 突变存在于多种癌症中，包括胰腺癌、肺癌和结直肠癌，但几十年来它一直被认为是“不可成药的”，因为其表面光滑且对 GTP 具有高亲和力，难以用传统药物靶向。最近在药物设计方面的进展，如共价抑制剂和靶向蛋白降解剂，使得开发能够结合突变 KRAS 并阻断其活性的疗法成为可能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41392-021-00780-4">KRAS mutation: from undruggable to druggable in cancer - Nature</a></li>
<li><a href="https://www.mskcc.org/news/new-kras-targeted-therapy-shows-promise-against-pancreatic">New KRAS Targeted Therapy Shows Promise Against Pancreatic Cancer</a></li>

</ul>
</details>

**社区讨论**: 评论者指出标题有些夸张，因为该发现仅适用于 20%的肿瘤，但承认这是一项重要进展。一位用户强调 KRAS 长期以来被认为不可成药，这一突破为未来治疗拓宽了视野。另一位用户分享了一位家人因胰腺癌去世的个人经历，强调了改进诊断和早期检测的必要性。

**标签**: `#cancer research`, `#KRAS`, `#pancreatic cancer`, `#drug discovery`, `#biotechnology`

---

<a id="item-6"></a>
## [亚马逊 CEO 谈话引发美国对 Anthropic AI 的打击](https://www.wsj.com/tech/ai/amazon-ceos-talks-with-u-s-officials-triggered-crackdown-on-anthropic-models-dcc90578?st=Yct6gx&reflink=desktopwebshare_permalink) ⭐️ 8.0/10

在亚马逊 CEO 安迪·贾西向美国官员提出安全担忧后，特朗普政府暂停了 Anthropic 最强大 AI 模型在国外的使用。 这引发了关于企业利益对 AI 监管影响的质疑，并凸显了国家安全与开放 AI 发展之间的紧张关系。 Anthropic 对政府的行动表示反对，称其越权。受影响的特定模型以及具体的安全担忧尚未公开详细说明。

hackernews · ls612 · Jun 13, 16:57 · [社区讨论](https://news.ycombinator.com/item?id=48519092)

**背景**: Anthropic 是一家以 Claude 系列大语言模型闻名的 AI 安全公司。亚马逊对 Anthropic 进行了大量投资，并是其关键合作伙伴。特朗普政府在 AI 监管方面采取了更激进的立场，特别是在外国访问先进模型方面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.wsj.com/tech/ai/amazon-ceos-talks-with-u-s-officials-triggered-crackdown-on-anthropic-models-dcc90578">Amazon CEO's Talks With U.S. Officials Triggered Crackdown on ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者对这一理由表示怀疑，指出所有大语言模型都可被越狱，并质疑该行动是否出于商业利益而非真正的安全担忧。一些人指出亚马逊与 Anthropic 的财务关系，暗示此举可能不像看起来那么险恶。

**标签**: `#AI regulation`, `#Anthropic`, `#Amazon`, `#government policy`, `#LLM safety`

---

<a id="item-7"></a>
## [谷歌起诉利用 Gemini AI 进行钓鱼诈骗的中国犯罪团伙](https://decrypt.co/371014/google-sues-chinese-crime-group-gemini-ai-phishing-scams) ⭐️ 8.0/10

谷歌对一中国犯罪团伙提起诉讼，指控其利用 Gemini AI 自动化大规模钓鱼攻击，创建了超过 9000 个虚假网站并窃取了数百万张信用卡信息。 此案凸显了生成式 AI 被用于网络犯罪的日益严重的威胁，并为追究 AI 提供商对其技术被滥用的责任树立了法律先例。 诈骗者使用 Gemini 生成虚假礼品兑换和品牌冒充页面的代码，然后将这些代码加载到钓鱼平台中，针对美国受害者，包括加密货币投资者。

rss · Decrypt · Jun 13, 16:01

**背景**: 钓鱼攻击是一种网络攻击，攻击者通过虚假消息或网站诱骗受害者泄露敏感信息。AI 驱动的钓鱼利用生成式模型创建更具说服力和可扩展的攻击，降低了低技能操作者的门槛。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/371014/google-sues-chinese-crime-group-gemini-ai-phishing-scams">Google Sues Chinese Crime Group for Allegedly Using Gemini AI for Mass Phishing Scams - Decrypt</a></li>
<li><a href="https://www.digitaltrends.com/phones/scammers-used-gemini-ai-to-power-a-massive-phishing-operation-and-google-just-sued-them/">Scammers used Gemini AI to power a massive phishing operation and Google just sued them - Digital Trends</a></li>
<li><a href="https://www.techtimes.com/articles/318273/20260612/google-sues-scam-ring-that-used-gemini-ai-flood-phones-fake-texts.htm">Google Sues Scam Ring That Used Gemini AI to Flood Phones With Fake Texts</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#cybersecurity`, `#phishing`, `#Google`, `#generative AI`

---

<a id="item-8"></a>
## [AI 代理仍易受提示注入攻击](https://decrypt.co/370972/ai-agents-prompt-injection-attacks-research) ⭐️ 8.0/10

一项新的基准测试研究表明，尽管 AI 代理技术正越来越多地公开部署，但它们仍然容易受到提示注入攻击。 随着 AI 代理被集成到更多应用中，这一持续存在的漏洞带来了重大安全风险，可能使攻击者能够操纵代理行为并访问敏感数据。 提示注入攻击利用了模型无法区分可信指令和不可信用户输入的弱点，从而导致意外行为。该研究强调，当前的防御措施仍不足以应对这些攻击。

rss · Decrypt · Jun 12, 19:22

**背景**: 提示注入是一种针对大型语言模型（LLM）的网络安全利用手段，通过构造恶意输入导致模型产生意外行为。AI 代理使用 LLM 执行自主任务，因此特别容易受到攻击，因为它们通常可以访问外部工具和数据。随着公司公开部署 AI 代理，保护它们免受此类攻击变得至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI security`, `#prompt injection`, `#AI agents`, `#vulnerability`

---

<a id="item-9"></a>
## [密码学家对比特币量子威胁意见分歧](https://www.coindesk.com/tech/2026/06/13/top-cryptographers-can-t-agree-on-bitcoin-s-biggest-quantum-question) ⭐️ 7.0/10

据 Coindesk 最近一篇文章报道，顶级密码学家在量子计算是否对比特币的密码学基础构成迫在眉睫的威胁上公开存在分歧。争论焦点在于潜在攻击比特币椭圆曲线数字签名算法（ECDSA）的时间线和严重性。 这一分歧对比特币的未来安全性和更广泛的加密货币生态系统具有重大影响，因为量子计算最终可能破解保护数十亿美元资产的密码学原语。这场辩论的结果将影响比特币网络何时以及如何升级到抗量子算法。 谷歌于 2026 年 3 月 31 日发表了一篇论文，指出量子计算机可能比预期更早破解比特币的密码学，而其他专家则认为威胁仍需数十年。比特币改进提案 BIP-360 和后量子标准正在被讨论作为潜在对策。

rss · CoinDesk · Jun 13, 06:07

**背景**: 比特币的安全性依赖于密码学算法，如用于工作量证明的 SHA-256 和用于数字签名的 ECDSA，这些算法被认为对经典计算机是安全的。量子计算机利用量子力学，理论上可以更快地解决这些算法背后的数学问题，从而可能允许攻击者伪造签名或逆转交易。构建足够强大的量子计算机的时间表仍不确定，导致了当前的争论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.forbes.com/sites/digital-assets/2026/03/31/google-finds-quantum-computers-could-break-bitcoin-sooner-than-expected/">Google Finds Quantum Computers Could Break Bitcoin Sooner ...</a></li>
<li><a href="https://www.btcpolicy.org/articles/state-of-play-quantum-computing-and-bitcoins-path-forward">State of Play: Quantum Computing and Bitcoin's Path Forward</a></li>
<li><a href="https://postquantum.com/post-quantum/quantum-cryptocurrencies-bitcoin/">Quantum Computing Risks to Cryptocurrencies – Bitcoin ...</a></li>

</ul>
</details>

**标签**: `#cryptography`, `#quantum computing`, `#Bitcoin`, `#blockchain security`

---

<a id="item-10"></a>
## [Coinbase 报告警告地址重用使数百万比特币面临量子风险](https://www.theblock.co/post/404685/coinbase-quantum-report-flags-exchange-cold-wallets-among-millions-of-bitcoin-exposed-by-address-reuse?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Coinbase 量子咨询委员会发布报告指出，地址重用使数百万比特币（包括交易所冷钱包）面临量子计算威胁。报告提出了设定迁移截止日期和冻结易受攻击的硬币等解决方案。 这很重要，因为量子计算机可能破解比特币的椭圆曲线加密，使攻击者能够从暴露公钥的地址窃取资金。报告中的提议可能影响未来的比特币安全标准，并影响交易所和用户管理钱包的方式。 报告估计，由于地址重用，多达 700 万枚 BTC 可能面临风险，其中大量存放在知名交易所的冷钱包中。报告指出，量子攻击最早可能在 2029 年成为可行。

rss · The Block · Jun 13, 18:21

**背景**: 比特币中的地址重用是指对多个交易使用同一地址，这会将公钥暴露在区块链上。这种做法因降低隐私和安全性而不被鼓励；在量子计算下，暴露的公钥可能被用来推导私钥。比特币的安全性依赖于椭圆曲线加密，而该加密在足够强大的量子计算机上运行 Shor 算法时容易受到攻击。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/404685/coinbase-quantum-report-flags-exchange-cold-wallets-among-millions-of-bitcoin-exposed-by-address-reuse">Coinbase quantum report flags exchange cold wallets among millions of bitcoin exposed by address reuse | The Block</a></li>
<li><a href="https://cryptobriefing.com/coinbase-bitcoin-quantum-risk-cold-wallets/">Coinbase report flags Bitcoin cold wallets exposed to quantum risks</a></li>
<li><a href="https://fortune.com/crypto/2026/04/06/quantum-computing-satoshi-nakamoto-bitcoin-freeze-wallets/">A quantum threat to Bitcoin has some asking the unthinkable: Is it time to freeze old wallets belonging to Satoshi Nakamoto? | Fortune</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#quantum computing`, `#bitcoin security`, `#address reuse`

---

<a id="item-11"></a>
## [失传 28 年的 Game Boy WorkBoy 配件重见天日](https://tcrf.net/Workboy) ⭐️ 6.0/10

未发布的 Game Boy WorkBoy 硬件附件及其生产力软件已被保存者找回并记录，揭示了一款在 1990 年代被取消的类似 PDA 的配件。 这一发现填补了电子游戏历史的空白，展示了任天堂早期将 Game Boy 从游戏扩展到生产力的尝试，对后来的手持设备产生了影响。 WorkBoy 包括地址簿、约会提醒和财务管理应用，旨在通过卡带插槽连接。该软件是从原型卡带中恢复的。

hackernews · tosh · Jun 13, 17:43 · [社区讨论](https://news.ycombinator.com/item?id=48519552)

**背景**: Game Boy 是任天堂于 1989 年发布的一款流行手持游戏机。WorkBoy 是一款未发布的附件，本可将其转变为个人数字助理（PDA），类似于 Palm Pilot 等设备。直到 2020 年发现原型机之前，其存在仅通过旧杂志广告为人所知。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Game_Boy_accessories">List of Game Boy accessories - Wikipedia</a></li>
<li><a href="https://www.ign.com/articles/a-lost-game-boy-add-on-called-the-workboy-has-been-found-after-28-years">A Lost Game Boy Add-On Called the WorkBoy Has Been Found After 28 Years - IGN</a></li>
<li><a href="https://gameluster.com/game-historian-finds-lost-game-boy-add-on-workboy/">Game Historian Finds Lost Game Boy Add-on, "WorkBoy" | GameLuster</a></li>

</ul>
</details>

**社区讨论**: 社区评论包括一个关于 WorkBoy 的 YouTube 视频链接，以及一条关于网站屏蔽 VPN 用户的说明，但没有对新闻本身的深入讨论。

**标签**: `#retro computing`, `#game boy`, `#hardware`, `#preservation`

---

<a id="item-12"></a>
## [华尔街从加密试点转向深入以太坊](https://www.coindesk.com/business/2026/06/13/wall-street-is-moving-past-crypto-pilots-and-deeper-into-ethereum-says-etherealize-founder) ⭐️ 6.0/10

Etherealize 创始人 Vivek Raman 表示，华尔街正在超越加密试点，深化与以太坊的接触，稳定币成为首个机构用例，讨论已扩展到代币化股票、债券和房地产。 这标志着大型金融机构从实验转向实际使用公共区块链，可能加速基于以太坊的资产和基础设施的主流采用。 Etherealize 是以太坊的机构营销和产品部门，于 2025 年 9 月从 Electric Capital 和 Paradigm 筹集了 4000 万美元，此前还获得了 Vitalik Buterin 和以太坊基金会的资助。

rss · CoinDesk · Jun 13, 16:00

**背景**: Etherealize 由 Vivek Raman 于 2024 年底创立，旨在推动金融机构采用以太坊。该公司专注于向华尔街营销以太坊在代币化、稳定币和去中心化金融方面的能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://fortune.com/crypto/2025/09/03/etherealize-vivek-raman-ethereum-40-million-paradigm-electric-capital/">Exclusive: Etherealize raises $40 million to expand Wall ...</a></li>
<li><a href="https://www.etherealize.com/about">About - etherealize.com</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#Wall Street`, `#crypto adoption`, `#finance`

---

<a id="item-13"></a>
## [美国政府押注 20 亿美元于量子计算，国防领域落后](https://www.coindesk.com/opinion/2026/06/12/the-u-s-government-is-betting-usd2-billion-on-quantum-computing-and-the-defense-side-can-t-keep-up) ⭐️ 6.0/10

美国政府已承诺投入 20 亿美元用于量子计算计划，但国防领域的应用进展难以跟上这一投资步伐。 这项投资标志着量子技术成为国家优先事项，但国防领域的落后可能造成国家安全和战略优势方面的漏洞。 这篇发表在 CoinDesk 上的文章指出了政府资金与国防准备之间的差距，但未详细说明具体项目或时间表。

rss · CoinDesk · Jun 12, 15:31

**背景**: 量子计算利用叠加和纠缠等量子力学原理，解决超越经典计算机的问题。全球各国政府将其视为具有密码学、模拟和国防应用的双重用途技术。美国一直在大力投资以保持技术领先地位。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Quantum_computing">Quantum computing - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/quantum-computing">What is quantum computing? - IBM</a></li>
<li><a href="https://www.congress.gov/crs_external_products/IF/PDF/IF11836/IF11836.13.pdf">Updated November 4, 2024 Defense Primer: Quantum Technology</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#government funding`, `#defense`, `#technology policy`

---

<a id="item-14"></a>
## [月之暗面推出 Kimi Work，将 300 个 AI 代理带到桌面](https://decrypt.co/370954/moonshot-ai-kimi-work-300-agents-desktop) ⭐️ 6.0/10

月之暗面推出了 Kimi Work，这是一个桌面 AI 代理，可以在本地文件、浏览器和日程上运行，无需依赖云端处理。 这标志着向本地 AI 代理的重大转变，增强了知识工作者的隐私和离线能力，可能挑战依赖云的生产力工具。 Kimi Work 由 Kimi K2.6 模型驱动，拥有 300 个子代理集群，并配备用于浏览器集成的 WebBridge。

rss · Decrypt · Jun 12, 18:40

**背景**: 月之暗面是一家位于北京的人工智能公司，被称为中国“AI 四小龙”之一，专注于大语言模型。桌面 AI 代理是一个新兴趋势，优先考虑本地数据处理而非依赖云端，提供更好的隐私和离线功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Moonshot_AI">Moonshot AI - Wikipedia</a></li>
<li><a href="https://lushbinary.com/blog/kimi-work-local-ai-agent-knowledge-workers-guide/">Kimi Work: Moonshot's Local AI Agent Guide | Lushbinary</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#desktop`, `#local AI`, `#productivity`

---

<a id="item-15"></a>
## [Exodus 与 Ondo 在 Solana 上推出代币化股票和 ETF](https://www.theblock.co/post/404622/exodus-launches-tokenized-markets-200-plus-stocks-etfs-on-solana?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Exodus 与 Ondo Finance 合作，在 Solana 区块链上直接推出超过 200 种股票和 ETF 的代币化交易。 这通过区块链扩大了传统股票的可及性，实现 24/7 交易和部分所有权，可能加速 Solana 上代币化现实世界资产的采用。 这些代币化资产由美国注册托管人持有的证券支持，并通过 Exodus 在 Solana 上的钱包界面提供服务。

rss · The Block · Jun 12, 13:26

**背景**: 代币化股票在区块链上代表传统股票，实现更快的结算和全球访问。Ondo Finance 专注于现实世界资产的代币化，Solana 提供适合交易的低费用和高吞吐量。其他平台如 xStocks 也在 Solana 上提供类似服务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://solana.com/news/case-study-xstocks">xStocks: Tokenizing Equities on Solana | Solana Media</a></li>
<li><a href="https://www.coindesk.com/business/2025/09/03/ondo-finance-rolls-out-tokenized-u-s-stocks-etfs-as-equity-tokenization-ramps-up">RWA News: Ondo Finance Rolls Out Tokenized U.S ... - CoinDesk</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#Solana`, `#DeFi`, `#stocks`, `#blockchain`

---

<a id="item-16"></a>
## [韩国：代币化股票属于证券，非加密资产](https://www.theblock.co/post/404580/south-korea-finance-ministry-says-tokenized-stocks-are-securities-not-crypto-assets-opening-door-to-taxes-report?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

韩国战略财政部将代币化股票归类为现有法律下的证券，如果监管机构同意，最早可能在 2026 年下半年开始征税。 这一监管澄清为韩国如何处理代币化资产树立了先例，将其与加密货币区分开来，并为征收资本利得税打开了大门。它可能影响其他正在处理类似分类问题的司法管辖区。 这一分类意味着代币化股票将受证券法和税收约束，可能于 2026 年下半年实施。此举与韩国更广泛的代币化证券监管推进相一致，最终指南预计于 2027 年 2 月发布。

rss · The Block · Jun 12, 11:38

**背景**: 代币化股票是在区块链上发行的传统股票的数字表示，允许部分所有权和更快的结算。韩国一直在制定代币化证券的法律框架，监管机构于 2026 年 7 月发布了指南，最终实施将于 2027 年 2 月完成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.europesays.com/korea/51588/">South Korea’s Finance Ministry Classifies Tokenized Stocks as ...</a></li>
<li><a href="https://cointelegraph.com/news/south-korea-announce-tokenized-securities-laws-july">South Korea to Announce Tokenized Securities Laws in July</a></li>
<li><a href="https://www.hokanews.com/2026/06/south-korea-classifies-tokenized-stocks.html">South Korea Classifies Tokenized Stocks as Securities ...</a></li>

</ul>
</details>

**标签**: `#crypto regulation`, `#tokenized securities`, `#South Korea`, `#taxation`

---