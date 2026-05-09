---
layout: default
title: "Horizon Summary: 2026-05-09 (ZH)"
date: 2026-05-09
lang: zh
---

> From 94 items, 27 important content pieces were selected

---

1. [谷歌新版 reCAPTCHA 导致去谷歌化安卓设备无法使用](#item-1) ⭐️ 8.0/10
2. [OpenAI 的 WebRTC 问题：复杂性与 AI 语音的冲突](#item-2) ⭐️ 8.0/10
3. [AI 正在打破两种漏洞披露文化](#item-3) ⭐️ 8.0/10
4. [AWS 弗吉尼亚北部数据中心宕机影响主要服务](#item-4) ⭐️ 8.0/10
5. [Anthropic 教 AI 理解规则背后的“为什么”](#item-5) ⭐️ 8.0/10
6. [Mojo 1.0 Beta 发布，兼具 Python 语法与高性能](#item-6) ⭐️ 8.0/10
7. [Zcash 将在一个月内推出量子可恢复钱包，2027 年实现量子安全](#item-7) ⭐️ 8.0/10
8. [Chrome 移除设备端 AI 隐私承诺](#item-8) ⭐️ 8.0/10
9. [AI 聊天机器人向广告追踪器泄露用户数据](#item-9) ⭐️ 8.0/10
10. [Tether 医疗 AI 在手机上运行，性能超越 16 倍大模型](#item-10) ⭐️ 8.0/10
11. [谷歌将本地 AI 速度提升 3 倍，无需新硬件](#item-11) ⭐️ 8.0/10
12. [Meshtastic：基于 LoRa 的离网网状网络短信系统](#item-12) ⭐️ 7.0/10
13. [法官批准 Aave 转移与朝鲜黑客有关的 7100 万美元 ETH](#item-13) ⭐️ 7.0/10
14. [SEC 主席阿特金斯暗示将为链上市场和 AI 金融制定新规](#item-14) ⭐️ 7.0/10
15. [比特币矿企 IREN 获英伟达 34 亿美元 AI 交易](#item-15) ⭐️ 7.0/10
16. [IMF 警告 AI 将加剧全球金融系统网络攻击](#item-16) ⭐️ 7.0/10
17. [亚马逊、Coinbase 和 Stripe 让 AI 代理用稳定币支付](#item-17) ⭐️ 7.0/10
18. [TrustedVolumes DeFi 漏洞损失 670 万美元](#item-18) ⭐️ 7.0/10
19. [大卫·爱登堡百岁诞辰庆祝活动](#item-19) ⭐️ 6.0/10
20. [io_uring ZCRX 空闲列表本地提权漏洞](#item-20) ⭐️ 6.0/10
21. [在树莓派 Zero 上从内存运行网站](#item-21) ⭐️ 6.0/10
22. [Kraken 母公司申请 OCC 特许状，欲建联邦加密银行](#item-22) ⭐️ 6.0/10
23. [欧洲央行拉加德警告不要照搬美国稳定币模式](#item-23) ⭐️ 6.0/10
24. [参议院银行委员会将对加密法案进行投票](#item-24) ⭐️ 6.0/10
25. [TeraWulf 的 HPC 收入首次超过比特币挖矿](#item-25) ⭐️ 6.0/10
26. [Arbitrum DAO 批准释放 7000 万美元 ETH 用于 Kelp DAO 恢复](#item-26) ⭐️ 6.0/10
27. [Solv Protocol 将 7 亿美元比特币从 LayerZero 迁移至 Chainlink](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [谷歌新版 reCAPTCHA 导致去谷歌化安卓设备无法使用](https://reclaimthenet.org/google-broke-recaptcha-for-de-googled-android-users) ⭐️ 8.0/10

谷歌将 reCAPTCHA 更新至新版本，该版本实质上要求远程证明，导致没有 Google Play Services 的去谷歌化安卓用户无法使用。 这一变化迫使去谷歌化安卓用户要么接受侵犯隐私的远程证明，要么失去对依赖 reCAPTCHA 的数百万网站的访问权限，引发了重大的隐私和数字主权担忧。 新版 reCAPTCHA 使用远程证明，将设备与唯一的硬件密钥（EK）绑定，并在谷歌服务器上记录到临时身份密钥（AIK）的转换，可能实现用户追踪。这破坏了与自定义 ROM 和缺乏谷歌证明基础设施的去谷歌化设备的兼容性。

hackernews · anonymousiam · May 8, 18:45 · [社区讨论](https://news.ycombinator.com/item?id=48067119)

**背景**: 去谷歌化安卓是指剥离了谷歌服务（如 Play Store 和 Play Services）的安卓操作系统，通常出于隐私原因使用。远程证明是一种加密过程，用于向远程服务器证明设备的软件和硬件完整性，但也可用于唯一标识设备。谷歌的 reCAPTCHA 是一种广泛部署的机器人检测服务，现在利用了这项技术。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeGoogle">DeGoogle - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Remote_attestation">Remote attestation</a></li>
<li><a href="https://cloud.google.com/blog/products/identity-security/introducing-google-cloud-fraud-defense-the-next-evolution-of-recaptcha/">Introducing Google Cloud Fraud Defense, the next evolution of reCAPTCHA | Google Cloud Blog</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了强烈不满，用户将新版 reCAPTCHA 比作 KYC（了解你的客户）要求，并批评谷歌强制推行远程证明。一些用户建议采用 Private Access Tokens 等替代方案，而另一些用户则分享了完全放弃谷歌服务的个人经历。

**标签**: `#privacy`, `#Android`, `#reCAPTCHA`, `#remote attestation`, `#Google`

---

<a id="item-2"></a>
## [OpenAI 的 WebRTC 问题：复杂性与 AI 语音的冲突](https://moq.dev/blog/webrtc-is-the-problem/) ⭐️ 8.0/10

一篇批评性博客文章指出，WebRTC 过于复杂，不适合实时 AI 语音应用，并提出 WebTransport 和 WebCodecs 作为更好的替代方案。 这很重要，因为 WebRTC 广泛用于实时通信，但其复杂性阻碍了低延迟 AI 语音界面的开发，而这对用户体验至关重要。 文章指出 WebRTC 繁琐的握手过程涉及 SDP、ICE、STUN/TURN 和对等协议，而 WebTransport 通过 HTTP/3 提供更简单的多路复用流，WebCodecs 则提供底层编解码器控制。

hackernews · atgctg · May 7, 17:11 · [社区讨论](https://news.ycombinator.com/item?id=48051951)

**背景**: WebRTC 是一组用于浏览器中实时点对点通信的协议，但它是为视频/音频通话设计的，而非 AI 语音。WebTransport 是一种较新的 API，用于通过 HTTP/3 进行双向流传输，而 WebCodecs 提供对媒体编解码器的直接访问，从而实现更高效的处理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.w3.org/TR/webtransport/">WebTransport</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/WebTransport">WebTransport - Web APIs | MDN</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API">WebCodecs API - Web APIs | MDN - MDN Web Docs</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了不同的经验：一些人同意 WebRTC 实现起来很痛苦，而另一些人指出，在规模上，使用 Pipecat 等适当工具，WebRTC 在语音代理中运行良好。一位评论者描述了 Alexa 使用的更简单方法，即保持类似 HTTP/2 的持久连接。

**标签**: `#WebRTC`, `#real-time communication`, `#AI voice`, `#WebTransport`, `#protocol design`

---

<a id="item-3"></a>
## [AI 正在打破两种漏洞披露文化](https://www.jefftk.com/p/ai-is-breaking-two-vulnerability-cultures) ⭐️ 8.0/10

AI 正在加速漏洞利用代码的生成，削弱了协调披露与完全披露之间的传统界限，迫使安全社区重新评估漏洞处理规范。 这一转变可能使当前的披露实践过时，增加零日攻击的风险，并迫使组织采用更快的补丁周期。 文章指出，AI 工具现在可以从补丁差异中生成漏洞利用代码，缩短了协调披露的时间窗口。像 Log4Shell 这样的真实案例表明，公开的提交可能在官方公告之前就引发攻击。

hackernews · speckx · May 8, 17:55 · [社区讨论](https://news.ycombinator.com/item?id=48066524)

**背景**: 协调漏洞披露（CVD）允许供应商在公开披露前有时间修补漏洞，而完全披露则立即发布细节以施压供应商。AI 驱动的漏洞利用生成使攻击者能够比以往更快地将漏洞武器化，从而模糊了这一区别。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure">Coordinated vulnerability disclosure - Wikipedia</a></li>
<li><a href="https://cyberdetectpro.com/coordinated-disclosure-vs-full-disclosure-comparison/">Coordinated Disclosure vs. Full Disclosure: Comparison</a></li>
<li><a href="https://www.csoonline.com/article/3819176/top-5-ways-attackers-use-generative-ai-to-exploit-your-systems.html">13 ways attackers use generative AI to exploit your systems | CSO Online</a></li>

</ul>
</details>

**社区讨论**: 安全专家如 tptacek 的评论指出，这种瓦解早在 AI 出现之前就被预测到了，其驱动力是开源透明度和逆向工具的改进。其他人则认为 AI 只是重新定义了一个老问题，缩短禁运期可能对补丁缓慢的组织帮助不大。

**标签**: `#AI`, `#vulnerability disclosure`, `#security`, `#open source`, `#exploit generation`

---

<a id="item-4"></a>
## [AWS 弗吉尼亚北部数据中心宕机影响主要服务](https://www.cnbc.com/2026/05/08/aws-outage-data-center-fanduel-coinbase.html) ⭐️ 8.0/10

2026 年 5 月 8 日，AWS 美国东部-1 区域的一个数据中心因冷却故障导致过热，进而引发电力中断，服务中断数小时，影响了 Coinbase 和 FanDuel 等平台。 此次宕机凸显了使用频繁的 US-East-1 区域的脆弱性，该区域有重大故障历史，并强调了关键服务依赖单一云区域的风险。 宕机由 US-East-1 区域一个可用区（use1-az4）的热事件引起，导致电力中断和 EC2 受损。恢复预计需要数小时，部分服务次日仍受影响。

hackernews · christhecaribou · May 8, 03:31 · [社区讨论](https://news.ycombinator.com/item?id=48058197)

**背景**: AWS US-East-1 是最古老且使用最频繁的区域之一，托管了大量关键互联网服务。它过去曾经历多次重大宕机，包括 2021 年和 2025 年 10 月，引发对其可靠性的担忧。AWS 高管表示该区域并非天生更脆弱，但规模更大，可能给服务带来压力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theregister.com/off-prem/2026/05/08/aws-warns-of-ec2-impairment-as-power-loss-hits-notorious-us-east-1-region/5235509">AWS warns of EC2 'impairment' as power loss hits notorious US ...</a></li>
<li><a href="https://www.cnbc.com/2026/05/08/aws-outage-data-center-fanduel-coinbase.html">AWS data center outage hits trading on FanDuel, Coinbase — recovery to take hours</a></li>
<li><a href="https://www.networkworld.com/article/4168878/aws-hit-by-us-east-1-outage-after-data-center-thermal-event.html">AWS hit by US-East-1 outage after data center thermal event | Network World</a></li>

</ul>
</details>

**社区讨论**: 社区评论对 US-East-1 的反复故障表示沮丧，有人质疑为何该区域比其他区域更容易宕机。其他人则担心内幕交易风险，因为员工可能押注宕机结果。还有讨论 AWS 是否在数据中心过度预订冷却容量。

**标签**: `#AWS`, `#outage`, `#cloud`, `#reliability`, `#us-east-1`

---

<a id="item-5"></a>
## [Anthropic 教 AI 理解规则背后的“为什么”](https://www.anthropic.com/research/teaching-claude-why) ⭐️ 8.0/10

Anthropic 发表了一项研究，提出一种训练 AI 模型理解并内化规则背后推理的方法，旨在实现更稳健、更具泛化能力的对齐。该方法通过教授模型底层原则，超越了简单的规则遵循。 这项研究解决了 AI 对齐的一个关键局限：模型往往表面遵循规则，在新情境下失败。通过教授“为什么”，模型可能更好地泛化并抵抗对抗性操纵，从而有望带来更安全、更可信的 AI 系统。 该研究与 Anthropic 的 Model Spec Midtraining 工作相关，后者已应用于 Llama 3.1 8B 和 Qwen 2.5 32B 等开放权重模型。该方法涉及在解释期望行为背后原理的推理轨迹上训练模型。

hackernews · pretext · May 8, 17:59 · [社区讨论](https://news.ycombinator.com/item?id=48066592)

**背景**: AI 对齐旨在引导 AI 系统符合人类意图和价值观。常见方法是训练模型遵循明确规则，但当规则冲突或情境新颖时，这可能导致行为脆弱。教授规则背后的推理可能产生更稳健的对齐。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_alignment">AI alignment</a></li>
<li><a href="https://www.anthropic.com/research/team/interpretability">Interpretability Research \ Anthropic</a></li>

</ul>
</details>

**社区讨论**: 评论中凸显了对对齐定义的担忧：一位用户质疑，一个消除劳动价值的模型是否还能被视为对齐，暗示当前定义不足。另一位指出与教学方法的联系，还有一位将其与关于价值体系的哲学辩论相类比。

**标签**: `#AI alignment`, `#Anthropic`, `#machine learning`, `#interpretability`, `#safety`

---

<a id="item-6"></a>
## [Mojo 1.0 Beta 发布，兼具 Python 语法与高性能](https://mojolang.org/) ⭐️ 8.0/10

Modular 发布了 Mojo 1.0 Beta，这是该语言的一个重要里程碑，它结合了类似 Python 的语法、受 Rust 启发的所有权模型、编译时计算和原生 SIMD 支持。Beta 版本现已支持 Linux 和 macOS，并计划于 2026 年秋季开源。 Mojo 旨在弥合 Python 易用性与 C++、Rust 等系统语言高性能之间的差距，主要面向机器学习和系统编程。它的发布可能通过提供统一的 CPU 和 GPU 代码语言，挑战 CUDA 和 Triton 等现有框架。 Mojo 使用 MLIR（多层中间表示）作为编译器基础设施，能够实现超越典型 LLVM 封装的高级优化。该语言具有类似 Rust 的所有权模型、编译时元编程（comptime）以及用于性能关键代码的直接 SIMD 内建函数。

hackernews · sbt567 · May 8, 02:49 · [社区讨论](https://news.ycombinator.com/item?id=48057901)

**背景**: Mojo 是由 Modular 公司开发的专有编程语言，该公司由 Chris Lattner（LLVM 和 Swift 的创建者）创立。它旨在提供类似 Python 的语法，同时具备 C++ 或 Rust 的性能，适用于 AI 和高性能计算。该语言目前尚未开源，但公司已承诺在 2026 年将其开源。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language) - Wikipedia</a></li>
<li><a href="https://docs.modular.com/mojo/manual/values/ownership/">Ownership - Mojo - Modular docs</a></li>
<li><a href="https://www.guvi.in/blog/modulars-mojo-programming-language/">Getting Started with Modular's Mojo Programming Language ...</a></li>

</ul>
</details>

**社区讨论**: 社区成员对 Mojo 的所有权和编译时计算等功能感到兴奋，但也有人担心与现有 Python 代码的兼容性以及延迟的开源时间表。其他人则指出来自 Nvidia 的 CuTile 和 Triton 的竞争，质疑 Mojo 的采用前景。

**标签**: `#Mojo`, `#programming language`, `#machine learning`, `#performance`, `#open source`

---

<a id="item-7"></a>
## [Zcash 将在一个月内推出量子可恢复钱包，2027 年实现量子安全](https://www.coindesk.com/tech/2026/05/08/zcash-to-roll-out-quantum-recoverable-wallets-within-a-month-go-quantum-proof-by-2027) ⭐️ 8.0/10

Zcash 宣布计划在一个月内推出量子可恢复钱包，并在 2027 年前实现完全的后量子安全，该路线图于 2026 年 5 月 8 日公布。 这是加密货币安全领域的重要一步，应对了量子计算机破解现有密码系统的未来威胁。Zcash 的主动举措可能为其他注重隐私的区块链树立先例。 量子可恢复钱包将作为安全与迁移层，允许用户在量子攻击出现时恢复资金。协议内完全过渡到抗量子标准的目标定在 2027 年，并保持向后兼容。

rss · CoinDesk · May 8, 09:08

**背景**: 量子计算机一旦足够强大，就可能破解大多数区块链（包括 Zcash）使用的椭圆曲线密码学。后量子密码学旨在开发能够抵御此类攻击的算法。Zcash 的路线图还包括在量子安全升级的同时，将吞吐量扩展到 Visa 和 Mastercard 级别。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/05/08/zcash-to-roll-out-quantum-recoverable-wallets-within-a-month-go-quantum-proof-by-2027">Zcash to add quantum-recoverable wallets within a month, go post-quantum by 2027</a></li>
<li><a href="https://coinjournal.net/news/zcash-plans-quantum-resistant-upgrade-as-crypto-braces-for-future-risks/">Zcash plans quantum-resistant upgrade as crypto braces for future risks - CoinJournal</a></li>
<li><a href="https://u.today/zcash-2027-analyzing-quantum-roadmap-aiming-to-turn-zec-into-privacy-first-mastercard">Zcash 2027: Analyzing Quantum Roadmap Aiming to Turn ZEC Into 'Privacy-First Mastercard' - U.Today</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#quantum computing`, `#blockchain security`, `#Zcash`

---

<a id="item-8"></a>
## [Chrome 移除设备端 AI 隐私承诺](https://decrypt.co/367193/chrome-removes-privacy-claim-gemini-nano-google) ⭐️ 8.0/10

谷歌的 Chrome 浏览器正在静默安装一个 4GB 的设备端 AI 模型（Gemini Nano），并在 Chrome 148 中移除了此前承诺不将用户数据发送到谷歌服务器的隐私声明。 这一变化削弱了用户信任并引发严重的隐私担忧，因为主流浏览器静默安装 AI 并移除了数据处理的透明度，可能影响数十亿用户。 这一移除最初由 Chrome subreddit 的用户发现并迅速传播到 Hacker News。设备端 AI 功能 Gemini Nano 在移动设备上不可用，从 Chrome 140 开始支持英语、西班牙语和日语。

rss · Decrypt · May 7, 20:52

**背景**: 设备端 AI 在用户设备本地运行，不将数据发送到外部服务器，通常被认为更私密。谷歌的 Gemini Nano 是一个轻量级 AI 模型，用于文本摘要和智能回复等任务。被移除的声明曾明确表示该功能“无需将数据发送到谷歌服务器”。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367193/chrome-removes-privacy-claim-gemini-nano-google">Chrome Deleted Its Own Privacy Promise for Sneaky... - Decrypt</a></li>
<li><a href="https://developer.chrome.com/docs/ai/get-started">Get started with built-in AI | AI on Chrome | Chrome for Developers</a></li>
<li><a href="https://chainbull.net/crypto/google-chromes-local-ai-model-raises-privacy-red-flags-in-latest-update/">Google Chrome 's Local AI Model Raises Privacy Red... - Chainbull</a></li>

</ul>
</details>

**社区讨论**: 社区反应普遍负面，用户对谷歌处理隐私的方式表示不信任和担忧。许多人正在讨论禁用该 AI 功能的变通方法，并质疑公司的动机。

**标签**: `#privacy`, `#Chrome`, `#AI`, `#Google`, `#browser`

---

<a id="item-9"></a>
## [AI 聊天机器人向广告追踪器泄露用户数据](https://decrypt.co/367164/your-ai-chatbot-leaking-chats-meta-tiktok-google) ⭐️ 8.0/10

一项新研究显示，包括 ChatGPT、Claude、Grok 和 Perplexity 在内的流行 AI 聊天机器人会与第三方广告追踪器共享用户数据，有时甚至在用户拒绝 cookie 时也会发生。 这一隐私泄露事件影响数百万用户，削弱了对 AI 聊天机器人的信任，凸显了加强数据保护法规和 AI 公司透明度的必要性。 研究发现，即使用户选择退出 cookie，数据共享仍然发生，这些追踪器属于 Meta、TikTok 和 Google 等主要广告平台。

rss · Decrypt · May 7, 19:06

**背景**: 第三方广告追踪器是嵌入网站中的脚本或像素，用于收集用户数据以进行定向广告。AI 聊天机器人通常集成此类追踪器用于分析或盈利，但用户期望他们的对话保持私密。AI 系统中的数据泄露可能在不涉及传统黑客手段的情况下暴露敏感信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cyberly.org/en/what-are-third-party-trackers-and-how-do-they-work/index.html">What Are Third-Party Trackers, And How Do They Work?</a></li>
<li><a href="https://www.knostic.ai/blog/ai-data-leakage">Data Leakage Happens with GenAI. Here’s How to Stop It.</a></li>

</ul>
</details>

**社区讨论**: 未提供社区评论，但该话题可能引发对隐私的担忧和加强监管的呼声。

**标签**: `#privacy`, `#AI chatbots`, `#data leakage`, `#ad trackers`, `#security`

---

<a id="item-10"></a>
## [Tether 医疗 AI 在手机上运行，性能超越 16 倍大模型](https://decrypt.co/367127/tether-medical-ai-runs-on-phone-outperforms-models-16x) ⭐️ 8.0/10

Tether Data 的 AI 研究团队发布了 QVAC MedPsy 系列医疗语言模型，该模型可在智能手机上运行，在真实场景中性能超越谷歌的 MedGemma-27B，同时计算资源消耗减少三倍。 这一突破使得高质量的临床 AI 能够部署在智能手机等边缘设备上，使医疗 AI 更易获取、更私密且更具成本效益，尤其在资源有限的环境中。 QVAC MedPsy-4B 生成准确答案所需的 token 数比骨干模型少 3.2 倍，该模型系列包含适用于边缘部署的高效量化版本。

rss · Decrypt · May 7, 16:01

**背景**: 用于医疗应用的大型语言模型通常需要大量计算资源，限制了其在云服务器上的部署。边缘 AI 旨在设备本地运行模型，减少延迟并提高隐私性。Tether 的 QVAC MedPsy 在医疗任务上实现了最先进的性能，同时体积足够小，可在智能手机上运行。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/qvac/medpsy">QVAC MedPsy : State-of-the-Art Medical and Healthcare Language...</a></li>
<li><a href="https://qvac.tether.io/models/">Models - QVAC by Tether</a></li>
<li><a href="https://www.bitrue.com/blog/what-is-qvac-medpsy">What Is QVAC MedPsy ?</a></li>

</ul>
</details>

**标签**: `#AI`, `#Medical AI`, `#Edge Computing`, `#Model Efficiency`, `#Mobile AI`

---

<a id="item-11"></a>
## [谷歌将本地 AI 速度提升 3 倍，无需新硬件](https://decrypt.co/367095/google-make-local-ai-3x-faster-no-new-hardware) ⭐️ 8.0/10

谷歌为其 Gemma 4 系列开放权重模型发布了多令牌预测（MTP）草稿器，使本地推理速度提升高达 3 倍，且质量无损。 这一突破使强大的 AI 模型在日常设备上变得实用，减少了对云服务的依赖，并增强了边缘 AI 应用的隐私性。 MTP 草稿器采用推测解码技术，由一个小型草稿模型一次性预测多个令牌，再由主模型验证，从而显著加速推理。

rss · Decrypt · May 7, 14:13

**背景**: 像 Gemma 4 这样的大型语言模型通常一次生成一个令牌，在本地硬件上速度较慢。推测解码通过使用草稿模型提出多个令牌，再由主模型接受或拒绝来加速。谷歌的 MTP 草稿器专门针对 Gemma 4 优化，在消费级 GPU 和 CPU 上实现了高达 3 倍的加速。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/multi-token-prediction-gemma-4/">Multi-token-prediction in Gemma 4 - The Keyword</a></li>
<li><a href="https://ai.google.dev/gemma/docs/mtp/overview">Speed-up Gemma 4 with Multi-Token Prediction - ai.google.dev</a></li>
<li><a href="https://claypier.com/en/gemma-4-mtp-drafter-launch/">Google Releases MTP Drafters for Gemma 4, Boosting Inference ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#machine learning`, `#Google`, `#edge computing`, `#inference optimization`

---

<a id="item-12"></a>
## [Meshtastic：基于 LoRa 的离网网状网络短信系统](https://meshtastic.org/docs/introduction/) ⭐️ 7.0/10

Meshtastic 是一个基于 LoRa 的开源网状网络协议，允许在无需许可的 ISM 频段上进行短信和数据交换，无需蜂窝网络或互联网基础设施。 它为户外探险、应急响应和偏远社区等离网场景提供了一种实用的去中心化通信解决方案，并且采用率不断增长，社区开发活跃。 Meshtastic 在无需许可的频段（例如欧洲的 868 MHz、北美的 915 MHz）上运行，功耗低、传输距离远（农村地区可达 10 英里以上）。它支持加密，这在业余无线电中通常受限，因此非许可用户也可使用。

hackernews · ColinWright · May 8, 11:22 · [社区讨论](https://news.ycombinator.com/item?id=48061566)

**背景**: LoRa（长距离）是一种扩频无线电技术，专为低功耗、长距离的物联网通信而设计。网状网络允许设备中继消息以扩展覆盖范围。Meshtastic 由 Kevin Hester 于 2020 年创建，现已发展成为一个由社区驱动的开源项目，拥有数百名贡献者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Meshtastic">Meshtastic</a></li>
<li><a href="https://meshtastic.org/">Off-Grid Communication For Everyone | Meshtastic</a></li>
<li><a href="https://en.wikipedia.org/wiki/LoRa">LoRa - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区成员对实际应用（如南太平洋帆船通信）充满热情，并赞赏其低门槛。一些人惊讶于该技术仍仅限于短信，而另一些人则指出它鼓励业余无线电执照的获取并促进了本地无线电俱乐部的形成。

**标签**: `#mesh networking`, `#LoRa`, `#decentralized communication`, `#ham radio`, `#IoT`

---

<a id="item-13"></a>
## [法官批准 Aave 转移与朝鲜黑客有关的 7100 万美元 ETH](https://www.coindesk.com/policy/2026/05/09/judge-clears-path-for-aave-to-move-usd71-million-in-eth-linked-to-north-korea-hack) ⭐️ 7.0/10

美国法官裁定，去中心化借贷协议 Aave 可以转移据称与朝鲜黑客有关的 7100 万美元以太坊，解决了关于冻结资金的法律僵局。 这一裁决为 DeFi 协议如何处理涉嫌被国家支持黑客窃取的资金树立了法律先例，影响了加密生态系统的安全实践和监管清晰度。 这些资金在被追踪到朝鲜国家支持的黑客组织 Lazarus Group 后被冻结，Aave 寻求法院批准转移资金以降低风险并遵守法规。

rss · CoinDesk · May 9, 04:16

**背景**: Aave 是一个去中心化金融（DeFi）协议，允许用户借贷加密货币。Lazarus Group 是一个臭名昭著的朝鲜黑客组织，负责多起加密货币盗窃案，包括 2025 年 14 亿美元的 Bybit 黑客事件。DeFi 中的冻结资金由于缺乏中央权威，常常带来法律和运营挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Aave">Aave - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lazarus_Group">Lazarus Group - Wikipedia</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#regulatory`, `#crypto`, `#hacking`

---

<a id="item-14"></a>
## [SEC 主席阿特金斯暗示将为链上市场和 AI 金融制定新规](https://www.coindesk.com/policy/2026/05/08/sec-chair-atkins-signals-new-rules-for-onchain-markets-ai-driven-finance) ⭐️ 7.0/10

SEC 主席保罗·阿特金斯表示，该机构将明确其监管框架如何适用于链上市场和 AI 驱动的金融，这标志着与前任政府相比的重大政策转变。 这标志着区块链金融市场和 AI 驱动的金融应用可能迎来监管清晰的新时代，有望在确保投资者保护的同时促进创新。 阿特金斯特别提到需要解决证券法如何适用于软件应用的问题，SEC 正在考虑对链上运营的交易系统和经纪自营商进行规则制定。

rss · CoinDesk · May 8, 18:32

**背景**: 保罗·阿特金斯曾在小布什总统时期担任 SEC 委员，于 2025 年确认出任 SEC 主席，接替加里·根斯勒。他主张在监管中注重透明度和成本效益分析。链上市场指在区块链网络上进行的交易和结算活动，而 AI 驱动金融包括算法交易、智能投顾和欺诈检测系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/policy/2026/05/08/sec-chair-atkins-signals-new-rules-for-onchain-markets-ai-driven-finance">SEC chair Paul Atkins signals rule changes for onchain markets and...</a></li>
<li><a href="https://news.bitcoin.com/sec-targets-onchain-trading-rules-and-crypto-vault-oversight/">SEC Targets Onchain Trading Rules and Crypto Vault Oversight</a></li>
<li><a href="https://www.sec.gov/newsroom/press-releases/2025-68">SEC .gov | Paul S. Atkins Sworn In as SEC Chairman</a></li>

</ul>
</details>

**标签**: `#SEC`, `#regulation`, `#blockchain`, `#AI`, `#finance`

---

<a id="item-15"></a>
## [比特币矿企 IREN 获英伟达 34 亿美元 AI 交易](https://decrypt.co/367289/bitcoin-miner-iren-secures-3-4-billion-nvidia-ai-deal) ⭐️ 7.0/10

比特币矿企 IREN 与英伟达达成了一项价值 34 亿美元的 AI 基础设施交易，其中英伟达有权选择向 IREN 投资高达 21 亿美元。 这笔交易凸显了加密货币挖矿与 AI 基础设施日益融合的趋势，比特币矿企正利用其能源和数据中心资产来满足对 AI 算力激增的需求。 该交易包括英伟达 21 亿美元的股票期权，IREN 计划建设高达 5 吉瓦的 AI 基础设施。IREN（原名 Iris Energy）已从比特币挖矿转向 AI 工厂运营。

rss · Decrypt · May 8, 17:02

**背景**: 像 IREN 这样的比特币矿企拥有大量电力合同和数据中心，最初是为加密货币挖矿而建。随着 AI 需求增长，这些资产正被重新用于高性能计算，使矿企成为 AI 基础设施竞赛中的关键参与者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.yahoo.com/news/microsofts-97-billion-deal-with-iren-shows-bitcoin-miners-ai-pivot-is-paying-off-165316526.html">Microsoft's $9.7 billion deal with IREN shows bitcoin miners ' AI pivot...</a></li>
<li><a href="https://awesomeagents.ai/news/nvidia-iren-5gw-ai-infrastructure-deal/">NVIDIA Bets $2.1B on IREN to Build 5 GW AI ... | Awesome Agents</a></li>

</ul>
</details>

**标签**: `#AI`, `#Nvidia`, `#Bitcoin Mining`, `#Infrastructure`, `#Deal`

---

<a id="item-16"></a>
## [IMF 警告 AI 将加剧全球金融系统网络攻击](https://decrypt.co/367178/imf-warns-ai-supercharge-cyberattacks-global-financial-system) ⭐️ 7.0/10

国际货币基金组织（IMF）发出警告，称 AI 工具使即使是无技能的 attackers 也能突破关键金融基础设施，并敦促将网络安全视为核心稳定问题。 这一警告凸显了全球金融体系面临的系统性风险日益增长，因为 AI 降低了网络攻击的门槛，可能导致广泛的混乱和对金融机构信任的丧失。 IMF 发出呼吁之际，有报告称威胁行为者正在使用像 Gemini 这样的 AI 工具来增强网络攻击的每个阶段，并且适应性 AI 恶意软件可以即时重写代码以逃避检测。

rss · Decrypt · May 7, 19:44

**背景**: 包括金融服务在内的关键基础设施正日益成为网络攻击的目标。网络犯罪分子和国家行为者现在都在使用 AI 工具来自动化和改进攻击技术，使其更有效且更难防御。IMF 的警告强调了在金融领域加强网络安全措施的必要性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cybernews.com/ai-news/threat-actors-abuse-ai-tools-cyberattacks-google-intel-warns/">Threat actors use AI tools to enhance cyberattacks | Cybernews</a></li>
<li><a href="https://home.treasury.gov/about/offices/domestic-finance/financial-institutions">Financial Institutions | U.S. Department of the Treasury Securing U.S. Critical Infrastructure against Evolving Cyber ... Critical Infrastructure Protection: National Cybersecurity ... Cybersecurity and Financial System Resilience Report Cybersecurity considerations 2025: Financial services sector Cybersecurity Awareness | FFIEC</a></li>
<li><a href="https://www.cisa.gov/news-events/news/cisa-unveils-new-initiative-fortify-americas-critical-infrastructure">CISA Unveils New Initiative to Fortify America’s Critical ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#cybersecurity`, `#finance`, `#IMF`

---

<a id="item-17"></a>
## [亚马逊、Coinbase 和 Stripe 让 AI 代理用稳定币支付](https://decrypt.co/367125/amazon-coinbase-stripe-ai-agents-pay-stablecoins) ⭐️ 7.0/10

亚马逊云服务（AWS）与 Coinbase 和 Stripe 合作，允许 AI 代理使用 USDC 稳定币支付 API、数据和在线服务。 这一整合标志着自主 AI 代理进行真实金融交易的重要一步，可能彻底改变 AI 服务的货币化和访问方式。 该系统利用与美元挂钩的稳定币 USDC 来提供交易价格稳定性，结合了 AWS 的云基础设施、Coinbase 的加密支付通道和 Stripe 的支付处理能力。

rss · Decrypt · May 7, 16:32

**背景**: 像 USDC 这样的稳定币是旨在保持价值稳定的加密货币，通常与美元等法定货币挂钩。AI 代理是能够自主执行任务的软件程序，让它们能够进行支付为自动化服务和机器对机器商业开辟了新的可能性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/industries/agentic-payments-the-next-evolution-in-the-payments-value-chain/">Agentic Payments: The Next Evolution in the Payments Value ...</a></li>
<li><a href="https://blog.payai.network/agentic-payments/">Agentic Payments: How AI Agents Pay, Transact, and Power the ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#stablecoins`, `#AWS`, `#fintech`, `#blockchain`

---

<a id="item-18"></a>
## [TrustedVolumes DeFi 漏洞损失 670 万美元](https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit) ⭐️ 7.0/10

被多个 DeFi 协议使用的流动性解析器 TrustedVolumes 遭遇漏洞攻击，损失 670 万美元。DEX 聚合器 1inch 表示其系统未受影响。 此事件凸显了 DeFi 基础设施中持续存在的安全风险，尤其是共享流动性解析器。它可能削弱对此类中间件的信任，并促使协议审计其依赖关系。 漏洞的根本原因是权限无许可签名者控制不严，这是解析器系统中的常见漏洞。据报道，同一攻击者此前曾攻击过 TrustedVolumes。

rss · Decrypt · May 7, 11:25

**背景**: TrustedVolumes 是一个流动性解析器，为 DeFi 协议聚合来自多个来源的流动性。像 1inch 这样的 DEX 聚合器依赖此类解析器来寻找最佳兑换路径。当解析器被攻破时，可能影响多个依赖它的协议。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit">DeFi Platform TrustedVolumes Hit by $6.7M Exploit - Decrypt</a></li>
<li><a href="https://coinalertnews.com/news/2026/05/07/trustedvolumes-hack-1inch-denies">TrustedVolumes Suffers $6.7M DeFi Exploit, 1inch Denies Any...</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#exploit`, `#blockchain`

---

<a id="item-19"></a>
## [大卫·爱登堡百岁诞辰庆祝活动](https://www.bbc.com/news/articles/cp3pww9g0p5o) ⭐️ 6.0/10

大卫·爱登堡迎来百岁生日，社区纷纷致敬，分享个人故事并反思其深远影响。 爱登堡的纪录片激励了几代人热爱自然、投身科学，他的百岁诞辰是认可其持久文化与教育影响的时刻。 社区评论中提到了爱登堡住在里士满山、他建议使用黄色网球以便电视转播，以及谷歌展示带有动物图案的特别致敬页面等轶事。

hackernews · defrost · May 8, 12:03 · [社区讨论](https://news.ycombinator.com/item?id=48061884)

**背景**: 大卫·爱登堡是英国著名播音员和自然历史学家，以撰写和主持《生命的故事》《地球脉动》等自然纪录片而闻名。他的作品被认为提高了全球环保意识，激发了科学好奇心。

**社区讨论**: 评论者表达了对爱登堡长寿和谦逊的钦佩，有人提到他仍住在里士满并签名售书。另有人将黄色网球的创新归功于他，其他人则反思他在激励科学家和工程师方面的作用。

**标签**: `#David Attenborough`, `#tribute`, `#cultural impact`, `#nature documentaries`

---

<a id="item-20"></a>
## [io_uring ZCRX 空闲列表本地提权漏洞](https://ze3tar.github.io/post-zcrx.html) ⭐️ 6.0/10

已发布一个针对 Linux 内核的本地提权漏洞利用，该漏洞利用 io_uring 零拷贝接收空闲列表中的越界写入，使攻击者能够获得 root 权限。 该漏洞利用凸显了 io_uring 子系统（一种高性能 I/O 接口）中持续存在的安全挑战，并强调了内核代码中正确边界检查的重要性。 该漏洞利用需要同时拥有 CAP_NET_ADMIN 和 CAP_SYS_ADMIN 权限，这些已经是提升的权限，并且根据 io_uring 维护者 Jens Axboe 的说法，该漏洞可能已在最新的稳定内核中被修补。

hackernews · MrBruh · May 8, 19:40 · [社区讨论](https://news.ycombinator.com/item?id=48067734)

**背景**: io_uring 是 Linux 内核中用于异步 I/O 的接口，可减少系统调用开销。零拷贝接收允许网络数据包直接接收至用户空间内存，避免了一次拷贝。空闲列表是用于此目的的缓冲区池；其管理中的缺陷可能导致越界写入。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.kernel.org/next/networking/iou-zcrx.html">io_uring zero copy Rx — The Linux Kernel documentation</a></li>
<li><a href="https://seclists.org/oss-sec/2026/q2/362">oss-sec: CVE request: io _ uring zcrx freelist OOB write</a></li>
<li><a href="https://www.man7.org/linux/man-pages/man7/capabilities.7.html">capabilities (7) - Linux manual page - man7.org</a></li>

</ul>
</details>

**社区讨论**: 评论者指出该漏洞利用需要已提升的权限，降低了其实际严重性。一些人质疑其新颖性，指出数月前已有类似漏洞利用。其他人则观察到近期 Linux 本地提权漏洞披露激增。

**标签**: `#Linux`, `#kernel exploit`, `#io_uring`, `#LPE`, `#security`

---

<a id="item-21"></a>
## [在树莓派 Zero 上从内存运行网站](https://btxx.org/posts/memory/) ⭐️ 6.0/10

一篇指南展示了如何在树莓派 Zero 上完全从内存运行网站，使用 Alpine Linux 并将 TLS 终止卸载到云提供商以提高性能。 这种方法减少了 SD 卡磨损并提高了低功耗自托管的可靠性，但依赖外部 TLS 处理，可能限制完全自给自足。 树莓派 Zero 只有 512MB 内存，其中约 40MB 被 Alpine Linux 占用，剩余空间足够运行一个小型网站。TLS 由云提供商处理，节省了 Pi 的 CPU 资源。

hackernews · xngbuilds · May 8, 15:10 · [社区讨论](https://news.ycombinator.com/item?id=48064312)

**背景**: 树莓派 Zero 是一款低成本、低功耗的单板计算机，常用于轻量级服务器。从内存（tmpfs）运行可避免 SD 卡磨损并提高速度，但断电后数据会丢失。TLS 卸载将加密开销转移到云服务，这在减轻受限设备负载方面很常见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://btxx.org/posts/memory/">Serving a Website on a Raspberry Pi Zero Running Entirely in RAM</a></li>
<li><a href="https://forums.raspberrypi.com/viewtopic.php?t=136771">Using RAM disk instead of a SD - Raspberry Pi Forums</a></li>
<li><a href="https://www.huntress.com/cybersecurity-101/topic/ssl-offloading">What is SSL Offloading ? Security Guide for IT Professionals | Huntress</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，将 TLS 卸载到云提供商减少了 CPU 负载，但质疑其新颖性，因为类似设置很常见。一些人分享了在 Pi Zero 上使用 Alpine Linux 的经验，强调其稳定性和低内存占用。

**标签**: `#Raspberry Pi`, `#self-hosting`, `#RAM disk`, `#TLS`, `#embedded systems`

---

<a id="item-22"></a>
## [Kraken 母公司申请 OCC 特许状，欲建联邦加密银行](https://www.coindesk.com/policy/2026/05/08/kraken-parent-goes-for-the-occ-charter-in-big-to-become-a-federal-crypto-bank) ⭐️ 6.0/10

Kraken 的母公司已向美国货币监理署（OCC）申请联邦银行特许状，旨在成为联邦加密银行，以补充其现有的怀俄明州特殊目的存款机构（SPDI）子公司。 如果获批，这将标志着一个重要的监管里程碑，使 Kraken 能够作为联邦特许银行运营，提供加密托管和法币存款服务，可能为其他寻求联邦监管的加密公司树立先例。 OCC 特许状将使 Kraken 获得联邦法律优先于州法律的权力，并接入美联储支付系统，而怀俄明州 SPDI 特许状已允许其根据州法律托管数字资产和接受法币存款。

rss · CoinDesk · May 8, 17:00

**背景**: OCC 负责在美国特许和监管国家银行及联邦储蓄协会。联邦银行特许状提供统一的监管框架，优先于州级要求。怀俄明州的 SPDI 框架是专为数字资产业务设计的州级特许状，提供托管和存款服务，但不具备完整的商业银行权限。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.occ.gov/topics/charters-and-licensing/index-charters-licensing.html">Charters & Licensing | OCC</a></li>
<li><a href="https://www.kraken.com/learn/finance/spdi-bank-charter">What is the SPDI Charter? | SPDI Framework | Kraken</a></li>

</ul>
</details>

**标签**: `#crypto`, `#regulation`, `#banking`, `#Kraken`

---

<a id="item-23"></a>
## [欧洲央行拉加德警告不要照搬美国稳定币模式](https://www.coindesk.com/business/2026/05/08/ecb-s-lagarde-warns-tether-and-circle-stablecoins-risk-digital-dollarisation-in-europe) ⭐️ 6.0/10

欧洲央行行长克里斯蒂娜·拉加德警告称，在欧洲采用美国稳定币模式可能导致数字美元化，削弱欧元的货币主权。 这凸显了欧洲央行推动数字欧元作为私人稳定币的主权替代品的战略意图，可能重塑欧洲的支付格局和金融自主权。 拉加德特别提到 Tether 和 Circle 的稳定币是如果被欧洲广泛采用可能促进数字美元化的工具例子。

rss · CoinDesk · May 8, 16:11

**背景**: 稳定币是与美元等稳定资产挂钩的加密货币，常用于交易和支付。数字欧元是欧洲央行正在开发的一种央行数字货币（CBDC），旨在提供安全、国家支持的数字支付选项。数字美元化指的是外国稳定币可能取代欧元进行数字交易，从而削弱货币控制的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tandfonline.com/doi/full/10.1080/2329194X.2025.2552378">The digital dollarization dilemma: Stablecoins and monetary ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Digital_euro">Digital euro</a></li>
<li><a href="https://www.investopedia.com/terms/s/stablecoin.asp">Stablecoins: Definition, How They Work, and Types - Investopedia</a></li>

</ul>
</details>

**标签**: `#digital euro`, `#stablecoins`, `#ECB`, `#financial policy`, `#Europe`

---

<a id="item-24"></a>
## [参议院银行委员会将对加密法案进行投票](https://www.theblock.co/post/400492/take-two-senate-banking-committee-sets-a-date-to-amend-and-vote-on-sweeping-crypto-legislation?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

参议院银行委员会已安排听证会，对全面的加密立法进行修订和投票，这是推动该法案的第二次尝试。 此次投票可能影响美国加密货币的监管格局，决定数字资产的分类和监管方式。 该立法被描述为全面的，但现有内容未提供具体条款。听证会是迈向潜在立法的程序性步骤。

rss · The Block · May 8, 23:24

**背景**: 参议院银行委员会负责金融监管，包括数字资产。此前加密立法的尝试均告停滞，因此本次投票是两党支持的关键考验。

**标签**: `#crypto`, `#regulation`, `#legislation`, `#Senate`

---

<a id="item-25"></a>
## [TeraWulf 的 HPC 收入首次超过比特币挖矿](https://www.theblock.co/post/400578/terawulfs-21-million-hpc-revenue-surpasses-bitcoin-mining-first-time-q1?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

TeraWulf 报告 2026 年第一季度来自高性能计算（HPC）和 AI 托管的收入为 2100 万美元，首次超过其比特币挖矿收入（低于 1300 万美元）。 这标志着行业重大转变，一家曾经的纯比特币矿商成功转向 AI 和 HPC 服务，可能激励其他矿商实现收入来源多元化。 该公司第一季度总收入为 3400 万美元，但净亏损超过 4.27 亿美元，部分原因是减值费用。TeraWulf 的转型反映了比特币矿商将基础设施重新用于 AI 工作负载的更广泛趋势。

rss · The Block · May 8, 15:37

**背景**: TeraWulf 由能源行业资深人士于 2021 年创立，最初专注于利用低成本能源进行比特币挖矿。随着挖矿盈利能力下降和 AI 需求激增，许多矿商开始改造数据中心用于 HPC 和 AI 托管。本季度的结果表明这一转型在财务上是可行的。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://crypto.news/terawulfs-hpc-revenue-tops-bitcoin-mining-for-first-time-as-ai-pivot-accelerates/">TeraWulf’s HPC revenue tops Bitcoin mining for first time as AI pivot...</a></li>
<li><a href="https://en.wikipedia.org/wiki/TeraWulf">TeraWulf - Wikipedia</a></li>

</ul>
</details>

**标签**: `#bitcoin mining`, `#HPC`, `#AI`, `#revenue`, `#industry trend`

---

<a id="item-26"></a>
## [Arbitrum DAO 批准释放 7000 万美元 ETH 用于 Kelp DAO 恢复](https://www.theblock.co/post/400527/arbitrum-dao-approves-eth-release?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Arbitrum DAO 已批准释放约 7000 万美元的 ETH，以帮助在 2026 年 4 月遭受 2.92 亿美元攻击的 Kelp DAO 进行恢复。然而，5 月 1 日的法院命令限制了这些资金的转移，Aave 已提交紧急动议要求解除该限制通知。 这一决定凸显了去中心化治理（DAO 投票）与法律体系之间的复杂互动，法院命令可以推翻社区批准的行动。这也凸显了在 DeFi 中追回被盗资金的挑战，因为涉及多个协议和司法管辖区。 这 7000 万美元的 ETH 在 Kelp DAO 被攻击后被冻结，Arbitrum DAO 投票决定将其释放给受害者。Aave 的紧急动议认为限制通知损害了其用户，并寻求解冻资金，而法院命令仍然有效。

rss · The Block · May 8, 07:25

**背景**: Arbitrum 是以太坊的 Layer 2 扩容解决方案，其 DAO 管理协议的金库和升级。Kelp DAO 是一个流动性质押协议，在 2026 年 4 月遭到 2.92 亿美元的攻击，资金分散在多个链上。Aave 是一个借贷协议，提交紧急动议以保护其用户利益，因为被冻结的 ETH 中包含 Aave 用户存入的资金。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cointelegraph.com/news/aave-asks-court-to-lift-restraining-notice-on-frozen-kelp-exploit-ether">Aave files emergency motion to lift restraining notice on ...</a></li>
<li><a href="https://www.banklesstimes.com/articles/2026/05/05/aave-llc-files-emergency-bid-to-void-arbitrums-71m-eth-restraining-notice/">Aave Files Emergency Motion to Unfreeze $71M Arbitrum ETH</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#DAO`, `#Arbitrum`, `#Ethereum`, `#Governance`

---

<a id="item-27"></a>
## [Solv Protocol 将 7 亿美元比特币从 LayerZero 迁移至 Chainlink](https://www.theblock.co/post/400520/solv-protocol-layerzero-chainlink?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Solv Protocol 正将其 7 亿美元代币化比特币从 LayerZero 迁移至 Chainlink CCIP，理由是 LayerZero 支持的 Kelp DAO 遭遇 2.9 亿美元攻击后引发安全担忧。 此次迁移表明主要 DeFi 协议对 LayerZero 安全模型的信任度下降，可能重塑跨链基础设施格局，并推动 Chainlink CCIP 的采用。 该决定源于 2026 年 4 月 Kelp DAO 遭遇的 2.9 亿美元攻击，攻击者利用了 LayerZero 默认的单验证器设置。Solv Protocol 管理着超过 7 亿美元锁仓量的代币化比特币。

rss · The Block · May 8, 02:17

**背景**: Solv Protocol 是一个 DeFi 平台，允许闲置比特币在多个区块链上进行流动性质押和收益生成。LayerZero 是一种跨链消息协议，而 Chainlink CCIP 是竞争性的互操作标准。Kelp DAO 攻击事件凸显了依赖 LayerZero 默认安全配置的风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://layerzero.network/blog/kelpdao-incident-statement">KelpDAO Incident Statement | LayerZero</a></li>
<li><a href="https://daotimes.com/kelp-dao-abandons-layerzero-for-chainlink-after-a-292m-bridge-hack/">Kelp DAO Abandons LayerZero for Chainlink After a $292M ...</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#Blockchain`, `#Security`, `#Tokenization`

---