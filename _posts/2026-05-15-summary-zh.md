---
layout: default
title: "Horizon Summary: 2026-05-15 (ZH)"
date: 2026-05-15
lang: zh
---

> From 89 items, 27 important content pieces were selected

---

1. [首个公开的苹果 M5 内核漏洞利用](#item-1) ⭐️ 9.0/10
2. [Bun 从 Zig 重写为 Rust 已合并](#item-2) ⭐️ 9.0/10
3. [Mullvad VPN 出口 IP 产生指纹识别风险](#item-3) ⭐️ 8.0/10
4. [移除 2024 款 RAV4 混动版的调制解调器和 GPS](#item-4) ⭐️ 8.0/10
5. [Antirez 发布 DS4：专为 Mac 打造的 DeepSeek V4 推理引擎](#item-5) ⭐️ 8.0/10
6. [RTX 5090 外接显卡在 M4 MacBook Air 上的游戏与 LLM 可行性](#item-6) ⭐️ 8.0/10
7. [新 Nginx 漏洞通过重写指令实现远程代码执行](#item-7) ⭐️ 8.0/10
8. [arXiv 对虚假参考文献实施一年封禁](#item-8) ⭐️ 8.0/10
9. [硬盘固件黑客技术深度剖析](#item-9) ⭐️ 8.0/10
10. [《清晰法案》通过参议院委员会，接近最终投票](#item-10) ⭐️ 8.0/10
11. [OpenAI 确认遭 Shai-Hulud 供应链攻击入侵](#item-11) ⭐️ 8.0/10
12. [半数 AI 健康建议有误](#item-12) ⭐️ 8.0/10
13. [Codex 编码代理现已登陆 ChatGPT 移动应用](#item-13) ⭐️ 7.0/10
14. [CME 将于 6 月 8 日推出纳斯达克 CME 加密货币指数期货](#item-14) ⭐️ 7.0/10
15. [Kimi WebBridge 让 AI 代理本地控制浏览器](#item-15) ⭐️ 7.0/10
16. [研究：AI 代理执行危险任务而不理解风险](#item-16) ⭐️ 7.0/10
17. [Kraken 用 Chainlink 替换 LayerZero 进行跨链桥接](#item-17) ⭐️ 6.0/10
18. [贝莱德与骏利亨德森实现基金即时赎回](#item-18) ⭐️ 6.0/10
19. [穆迪授予代币化货币市场基金最高 Aaa-mf 评级](#item-19) ⭐️ 6.0/10
20. [OpenAI 在诉讼中加强 ChatGPT 安全功能](#item-20) ⭐️ 6.0/10
21. [ChatGPT 网络流量份额被竞争对手蚕食](#item-21) ⭐️ 6.0/10
22. [Tether、Tron 和 TRM 冻结 4.5 亿美元非法加密资金](#item-22) ⭐️ 6.0/10
23. [Tezos 测试后量子隐私，创始人批评比特币](#item-23) ⭐️ 6.0/10
24. [嘉信理财开始向美国用户提供比特币和以太坊交易](#item-24) ⭐️ 6.0/10
25. [英国央行将稳定币视为新货币形式](#item-25) ⭐️ 6.0/10
26. [CertiK CEO：DeFi 攻击者利用 AI 在支出上碾压防御者](#item-26) ⭐️ 6.0/10
27. [ZachXBT 指控 LAB 代币 95%由内部人控制](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [首个公开的苹果 M5 内核漏洞利用](https://blog.calif.io/p/first-public-kernel-memory-corruption) ⭐️ 9.0/10

安全初创公司 Calif 发布了首个针对苹果 M5 硬件的公开 macOS 内核内存破坏漏洞利用，该利用借助 Anthropic 的 Claude Mythos AI 预览版开发完成。 该利用绕过了苹果 M5 上最新的安全缓解措施，表明即使是最新一代的硬件防护也能在 AI 辅助下被攻破，可能提高漏洞赏金和安全研究的门槛。 该漏洞利用在五天内使用 Mythos Preview 构建，绕过了苹果五年的安全努力。该漏洞是一个内核内存破坏错误，在 MTE（内存标记扩展）下仍然存在。

hackernews · quadrige · May 14, 18:25 · [社区讨论](https://news.ycombinator.com/item?id=48139219)

**背景**: 苹果 M5 是苹果最新的系统级芯片，采用 3 纳米工艺，配备下一代 GPU 和神经引擎。内核内存破坏漏洞利用针对操作系统核心，允许攻击者获得完全控制权。MTE 是一种旨在检测内存安全违规的硬件安全功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.calif.io/p/first-public-kernel-memory-corruption">First public macOS kernel memory corruption exploit on Apple M5</a></li>
<li><a href="https://9to5mac.com/2026/05/14/calif-team-details-how-anthropic-mythos-helped-build-a-working-macos-exploit-in-five-days/">Anthropic Mythos helped Calif build a macOS exploit in five... - 9to5Mac</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_M5">Apple M5 - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者对苹果未在核心代码中全面采用 Swift 表示惊讶，并讨论了 LLM 对安全的影响——有人预见 AI 生成的“鲁布·戈德堡”式漏洞。其他人则注意到该漏洞的潜在价值（10 万到 150 万美元），并对它如何绕过 MTE 感到好奇。

**标签**: `#macOS`, `#kernel exploit`, `#Apple M5`, `#security`, `#vulnerability`

---

<a id="item-2"></a>
## [Bun 从 Zig 重写为 Rust 已合并](https://github.com/oven-sh/bun/pull/30412) ⭐️ 9.0/10

Bun 的核心已从 Zig 重写为 Rust，该拉取请求已合并到主分支，代码量超过 100 万行 Rust 代码。 这次重写有望提高内存安全性和性能，解决困扰 Zig 版本的许多释放后使用和双重释放错误。这代表了 Bun 项目的重大范式转变，并可能影响其他运行时项目。 重写大约花了一周时间，但准备工作包括将 Zig 惯用法映射到 Rust 的详细说明以及预先存在的智能指针类型。代码库现在包含 1,443 个 Rust 文件和 1,298 个 Zig 文件，Rust 代码行数已超过 Zig。

hackernews · Chaoses · May 14, 08:15 · [社区讨论](https://news.ycombinator.com/item?id=48132488)

**背景**: Bun 是一个快速的全能 JavaScript 运行时、打包器、测试运行器和包管理器，旨在作为 Node.js 的直接替代品。它最初使用 Zig，一种专注于健壮性和最优性的系统编程语言。Rust 是另一种以无需垃圾回收即可实现内存安全而闻名的系统语言。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**社区讨论**: 社区评论强调了重写的广泛准备工作，包括将 Zig 惯用法映射到 Rust 的详细说明。一些用户注意到 Rust 代码中不安全块的数量很多，而另一些用户则讨论了在 LLM 时代管理如此庞大代码库的复杂性。

**标签**: `#Bun`, `#Rust`, `#Zig`, `#JavaScript runtime`, `#rewrite`

---

<a id="item-3"></a>
## [Mullvad VPN 出口 IP 产生指纹识别风险](https://tmctmt.com/posts/mullvad-exit-ips-as-a-fingerprinting-vector/) ⭐️ 8.0/10

一项技术分析发现，Mullvad VPN 根据 WireGuard 密钥确定性地分配出口 IP，且密钥轮换频率低，使得网站能够以高置信度将用户在不同服务器上的会话关联起来。 这削弱了 VPN 的隐私承诺，引入了一个可对用户进行去匿名化的指纹识别向量，尤其对论坛版主或监控流量的攻击者而言。 出口 IP 通过基于百分位数的映射从 WireGuard 公钥派生，密钥每 1 到 30 天轮换一次（使用第三方客户端则永不轮换）。不同会话之间的 IP 范围重叠率可高达 99%。

hackernews · RGBCube · May 15, 02:35 · [社区讨论](https://news.ycombinator.com/item?id=48143880)

**背景**: VPN 通常随机分配出口 IP 以防止会话关联。Mullvad 使用 WireGuard，这是一种以简洁和快速著称的现代 VPN 协议。确定性分配可能是出于运营效率和兼容性考虑，但造成了隐私权衡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://thecodersblog.com/mullvad-exit-ips-a-privacy-paradox/">Mullvad Exit IPs: A Privacy Paradox? - The Coders Blog | Home</a></li>
<li><a href="https://wiki.archlinux.org/title/WireGuard">WireGuard - ArchWiki</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了惊讶和担忧，有人将这种设计比作情报机构的工具。另一些人指出，VPN 并非像 Tor 那样为匿名而设计，而且即使是 Tor 也可能通过控制出口节点被去匿名化。

**标签**: `#VPN`, `#privacy`, `#fingerprinting`, `#security`, `#networking`

---

<a id="item-4"></a>
## [移除 2024 款 RAV4 混动版的调制解调器和 GPS](https://arkadiyt.com/2026/05/13/removing-the-modem-and-gps-from-my-rav4/) ⭐️ 8.0/10

一份详细指南说明了如何从 2024 款丰田 RAV4 混动版上物理移除远程信息处理调制解调器和 GPS 天线以阻止数据传输，同时指出蓝牙连接仍可能通过手机网络泄露数据。 这对注重隐私的车主很重要，他们希望阻止汽车制造商收集并可能将驾驶数据分享给保险公司或第三方，凸显了联网汽车功能与用户隐私之间日益加剧的矛盾。 移除过程涉及断开手套箱后的 DCM（数据通信模块）和 GPS 天线；但作者警告说，蓝牙配对会让汽车通过手机网络发送遥测数据，因此建议改用有线 USB CarPlay。

hackernews · arkadiyt · May 14, 17:08 · [社区讨论](https://news.ycombinator.com/item?id=48138136)

**背景**: 现代汽车通常配备常开蜂窝调制解调器和 GPS，用于远程服务、导航和紧急救援等功能，但它们也会持续向制造商传输遥测数据。这些数据可能包括驾驶行为、位置和车辆状态，一些车主认为这侵犯了隐私。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://it4sec.substack.com/p/security-issues-of-third-party-carplay">Security issues of third-party CarPlay adapters: from data ...</a></li>
<li><a href="https://vicone.com/blog/apple-carplay-airborne-vulnerabilities-and-what-they-mean-for-the-automotive-industry">Apple CarPlay’s ‘AirBorne’ Vulnerabilities and What They Mean ...</a></li>

</ul>
</details>

**社区讨论**: 评论者讨论了蓝牙遥测漏洞，并指出 CarPlay 本身也会捕获车辆数据，因此即使使用有线 USB 也可能无法完全防止数据泄露。一位用户分享说福特 Maverick 有一个单独的远程信息处理保险丝，拔出后不会报错；另一位提到丰田据称与保险公司共享数据。

**标签**: `#privacy`, `#automotive`, `#telemetry`, `#hardware hacking`, `#Toyota`

---

<a id="item-5"></a>
## [Antirez 发布 DS4：专为 Mac 打造的 DeepSeek V4 推理引擎](https://antirez.com/news/165) ⭐️ 8.0/10

Antirez 发布了 DwarfStar4 (DS4)，这是一个小巧、自包含的 LLM 推理运行时，针对 Apple 的 Metal API 进行了优化，能够在配备 96GB RAM 的 MacBook 上运行 DeepSeek V4 Flash，质量接近 Claude。 DS4 将高质量的本地 LLM 推理带到 Apple Silicon Mac 上，可能减少对云端 API 的依赖，用于编码等要求高的任务，并展示了专用推理引擎相对于通用运行时的可行性。 DS4 故意保持狭窄定位，仅专注于 DeepSeek V4 Flash，以 Metal 为主要后端，但也支持 NVIDIA CUDA 和 AMD ROCm。该项目承认 llama.cpp 和 GGML 是其基础。

hackernews · caust1c · May 14, 22:29 · [社区讨论](https://news.ycombinator.com/item?id=48142108)

**背景**: 像 llama.cpp 这样的 LLM 推理运行时通常支持多种模型，但 DS4 是专为 DeepSeek V4 Flash 设计的模型特定引擎，旨在实现最大优化。Apple 的 Metal API 提供了对 Mac GPU 的直接访问，从而在像 96GB MacBook 这样的统一内存系统上实现高效推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/antirez/ds4">GitHub - antirez/ds4: DeepSeek 4 Flash local inference engine ...</a></li>
<li><a href="https://pasqualepillitteri.it/en/news/2253/ds4-antirez-deepseek-v4-flash-inference-engine">DwarfStar4 (DS4) Roadmap by antirez: DeepSeek V4 Flash on ...</a></li>
<li><a href="https://localllmguide.polsia.app/articles/best-llms-for-mac-apple-silicon">Best LLMs for Mac Apple Silicon 2026 | LocalLLMGuide</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞 DS4 的质量，有人指出它感觉接近 Claude，甚至表现出自我意识。一些人质疑构建模型特定引擎相对于使用 llama.cpp 的努力，但其他人则看重这种专注的优化。

**标签**: `#LLM`, `#inference`, `#DeepSeek`, `#Metal`, `#open source`

---

<a id="item-6"></a>
## [RTX 5090 外接显卡在 M4 MacBook Air 上的游戏与 LLM 可行性](https://scottjg.com/posts/2026-05-05-egpu-mac-gaming/) ⭐️ 8.0/10

一位开发者成功通过 Thunderbolt 4 将 NVIDIA RTX 5090 外接显卡连接到 M4 MacBook Air，实现了在 macOS 上原本无法完成的游戏和 LLM 推理。该方案使用自定义驱动 (TinyGPU) 和带有 GPU 直通的虚拟机，绕过了苹果对 eGPU 缺乏支持的限制。 这展示了一种绕过 Apple Silicon 封闭 GPU 生态的变通方案，可能为 Mac 带来高性能游戏和本地 AI 工作负载。它凸显了在苹果硬件上对 CUDA 加速日益增长的需求，以及社区在克服平台限制方面的创造力。 该 eGPU 方案需要一个配备 1000-1200W 电源的 Thunderbolt 4 外接显卡盒，且 RTX 5090 仅能通过 GPU 直通在 Linux 虚拟机内使用。游戏基准测试显示，在《毁灭战士 2016》等通过 Vulkan 运行的游戏中有可玩的帧率，但由于 macOS 对 OpenGL 支持不佳，OpenGL 游戏仍无法运行。

hackernews · allenleee · May 14, 15:47 · [社区讨论](https://news.ycombinator.com/item?id=48137145)

**背景**: Apple Silicon Mac 官方不支持外接显卡 (eGPU)，尤其是 NVIDIA 显卡，因为苹果已转向自研 GPU 且缺乏 NVIDIA 驱动支持。M4 MacBook Air 依赖集成 GPU 进行图形处理，足以应对轻度游戏，但在运行大型游戏和 LLM 推理时力不从心。TinyGPU 驱动和虚拟机直通技术通过运行一个直接访问 eGPU 的 Linux 虚拟机，在 Apple Silicon 上实现了 CUDA 加速。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=xnPggMt1RSE">An Overkill eGPU with Liquid Cooled RTX 5090 - YouTube</a></li>
<li><a href="https://www.compute-market.com/blog/nvidia-egpu-mac-local-ai-setup-2026">Nvidia eGPU on Mac for Local AI 2026 — TinyGPU Setup</a></li>
<li><a href="https://www.runlocalai.co/guides/best-egpu-setup-for-local-ai">Best eGPU setup for local AI — Thunderbolt + OCuLink... | RunLocalAI</a></li>

</ul>
</details>

**社区讨论**: 评论者对于 eGPU 能在 Apple Silicon 上工作感到惊讶，有人指出苹果官方立场是 eGPU 需要 Intel Mac。其他人则称赞 LLM 推理的改进，指出 Mac 的提示处理速度慢是已知问题，而该方案解决了这一问题。讨论还涉及虚拟机直通方法的复杂性，以及希望获得更好的官方支持。

**标签**: `#eGPU`, `#Apple Silicon`, `#gaming`, `#LLM inference`, `#hardware hacking`

---

<a id="item-7"></a>
## [新 Nginx 漏洞通过重写指令实现远程代码执行](https://github.com/DepthFirstDisclosures/Nginx-Rift) ⭐️ 8.0/10

一个新的 Nginx 漏洞（CVE 待分配）允许在特定条件下通过精心构造的 rewrite 和 set 指令实现任意代码执行，概念验证代码已在 GitHub 上发布。 该漏洞影响全球数百万台 Nginx 服务器，且披露中声称存在可靠的 ASLR 绕过方法，尽管有前提条件，仍构成严重威胁。 该漏洞利用需要 rewrite 指令的替换字符串中包含问号，随后 set 指令引用未命名的正则捕获组；F5 已为 Nginx 1.31.0 和 1.30.1 发布补丁。

hackernews · hetsaraiya · May 14, 17:17 · [社区讨论](https://news.ycombinator.com/item?id=48138268)

**背景**: Nginx 是一种广泛使用的 Web 服务器和反向代理。其 rewrite 模块将 rewrite、set、if 和 return 指令编译为每请求执行的字节码。该漏洞源于编译器处理未命名捕获组时的缺陷，已存在 18 年。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://devops-daily.com/posts/nginx-rift-cve-2026-42945-rewrite-rce">NGINX Rift (CVE-2026-42945): The 18-Year-Old Rewrite Bug That...</a></li>
<li><a href="https://thehackernews.com/2026/05/18-year-old-nginx-rewrite-module-flaw.html">18-Year-Old NGINX Rewrite Module Flaw Enables Unauthenticated...</a></li>
<li><a href="https://depthfirst.com/research/nginx-rift-achieving-nginx-rce-via-an-18-year-old-vulnerability">NGINX Rift: Achieving NGINX Remote Code Execution via... | depthfirst</a></li>

</ul>
</details>

**社区讨论**: 社区评论中对严重性存在争议：有人认为 ASLR 绕过使其变得关键，而另一些人则指出利用的前提条件以及 ASLR 提供的保护。建议使用命名捕获作为缓解措施。

**标签**: `#nginx`, `#security`, `#exploit`, `#vulnerability`, `#web-server`

---

<a id="item-8"></a>
## [arXiv 对虚假参考文献实施一年封禁](https://twitter.com/tdietterich/status/2055000956144935055) ⭐️ 8.0/10

arXiv 推出新政策，对提交包含虚假参考文献的论文的作者实施一年封禁，并要求后续投稿必须先被知名同行评审平台接受。 该政策直接应对了学术预印本中日益严重的 AI 生成虚假引用问题，有助于维护科学诚信和对 arXiv 平台的信任。 该禁令适用于被发现提交包含伪造参考文献的论文的作者，禁令结束后，投稿必须先通过同行评审才能在 arXiv 上发布。该政策尚未生效，但已公开讨论。

hackernews · gjuggler · May 14, 20:39 · [社区讨论](https://news.ycombinator.com/item?id=48140922)

**背景**: 虚假参考文献是由大型语言模型（LLM）生成的不存在的引用，已成为学术出版中的一个重大问题。arXiv 是一个广泛使用的预印本仓库，允许未经同行评审快速传播研究，因此容易受到此类错误的影响。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48140922">New arXiv policy: 1-year ban for hallucinated references</a></li>
<li><a href="https://arxiv.org/abs/2305.18248">Do Language Models Know When They're Hallucinating References ?</a></li>
<li><a href="https://github.com/ethz-spylab/hallucinated-citations">GitHub - ethz-spylab/ hallucinated -citations: Check for...</a></li>

</ul>
</details>

**社区讨论**: 社区普遍支持该政策，评论称赞这是维护科学诚信的必要举措。一些用户建议进一步改进，如更好的引用工具，而另一些用户指出该政策可能面临 LLM 支持者的抵制。

**标签**: `#arXiv`, `#academic integrity`, `#AI-generated content`, `#publishing policy`, `#hallucination`

---

<a id="item-9"></a>
## [硬盘固件黑客技术深度剖析](https://icode4.coffee/?p=1465) ⭐️ 8.0/10

一篇技术文章详细介绍了在各种硬盘和固态硬盘上转储、逆向工程和修改固件的过程，揭示了供应商混淆技术的弱点。 这项研究揭示了供应商的混淆技术是多么容易被绕过，引发了对存储设备固件安全性以及持久性恶意软件潜在风险的严重担忧。 文章展示了实际的利用方法，包括使用 seccomp 从供应商更新工具中截获解密后的固件。社区评论还提到了之前对三星 840 EVO SSD 固件的反编译。

hackernews · jsploit · May 14, 16:19 · [社区讨论](https://news.ycombinator.com/item?id=48137553)

**背景**: 固件是嵌入在硬件设备中控制其运行的低级软件。硬盘固件管理数据读写以及与主机系统的通信。逆向工程固件可以揭示漏洞或允许修改，但供应商通常使用混淆技术来阻碍分析。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://icode4.coffee/?p=1465">HDD Firmware Hacking Part 1 – I Code 4 Coffee</a></li>
<li><a href="https://icmconference.org/wp-content/uploads/A14-VanK-HardDrive_Firmware_Hacking_ICMC-Copy.pdf">A Look Into Hard Drive Firmware</a></li>
<li><a href="https://en.wikipedia.org/wiki/Firmware">Firmware - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，供应商的混淆技术通常很容易被绕过，其中一位分享了一种从 Linux 更新工具中捕获解密固件的技术。另一位评论者提到了之前对三星 SSD 固件的反编译，还有一位认为这篇文章可能对某公司面试中涉及硬盘的 CTF 挑战有用。

**标签**: `#firmware`, `#reverse engineering`, `#hardware hacking`, `#security`, `#storage`

---

<a id="item-10"></a>
## [《清晰法案》通过参议院委员会，接近最终投票](https://www.coindesk.com/policy/2026/05/14/clarity-act-clears-u-s-senate-committee-on-its-way-to-a-final-test-in-congress) ⭐️ 8.0/10

2026 年 5 月 14 日，全面的加密货币监管法案《清晰法案》通过了美国参议院银行委员会，距离国会最终投票更近一步。 该立法可能为美国数字资产建立明确的监管框架，有望减少不确定性并促进行业发展。 该法案正式名称为《2025 年数字资产市场清晰法案》，包含定义数字资产以及在 SEC 和 CFTC 之间分配监管职责的条款。

rss · CoinDesk · May 14, 17:08

**背景**: 《清晰法案》旨在为加密市场提供全面的规则手册，类似于传统金融领域的《多德-弗兰克法案》。该法案一直是加密行业的优先事项，该行业长期以来一直寻求美国立法者制定更明确的法规。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.congress.gov/bill/119th-congress/house-bill/3633/text">Text - H.R.3633 - 119th Congress (2025-2026): Digital Asset Market Clarity Act of 2025 | Congress.gov | Library of Congress</a></li>
<li><a href="https://www.cnbc.com/2026/05/14/clarity-act-congress-crypto-senate.html">Crypto industry scores win as Clarity Act regulation bill clears Senate hurdle</a></li>
<li><a href="https://www.grayscale.com/the-stack/the-clarity-act-where-are-we-now-and-where-do-we-go-next">The CLARITY Act: Where Are We Now, and Where Do ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#US politics`, `#blockchain`

---

<a id="item-11"></a>
## [OpenAI 确认遭 Shai-Hulud 供应链攻击入侵](https://decrypt.co/367883/openai-confirms-security-breach-ai-malware-campaign) ⭐️ 8.0/10

OpenAI 确认，与 Shai-Hulud 恶意软件活动相关的黑客在通过一个被篡改的开源软件包感染了两名员工的设备后，侵入了其内部开发环境的部分区域。 此次针对领先 AI 公司的入侵凸显了针对开发者生态系统的供应链攻击日益增长的威胁，可能暴露敏感的 AI 研究和内部工具。 攻击使用了 Shai-Hulud 供应链活动中的恶意软件，该活动已入侵数百个开源软件包，包括 Mistral AI 和 TanStack 的包，目标是 CI/CD 管道以窃取凭证。

rss · Decrypt · May 14, 18:30

**背景**: 供应链攻击是指攻击者将恶意代码注入合法软件包，然后传播给安装这些包的用户。Shai-Hulud 活动最初于 2025 年底被发现，现已演变为针对开发环境和 AI 生态系统，利用自动传播来入侵 CI/CD 管道和云工作负载。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367883/openai-confirms-security-breach-ai-malware-campaign">OpenAI Confirms Security Breach Linked to AI Malware Campaign - Decrypt</a></li>
<li><a href="https://www.microsoft.com/en-us/security/blog/2025/12/09/shai-hulud-2-0-guidance-for-detecting-investigating-and-defending-against-the-supply-chain-attack/">Shai-Hulud 2.0: Guidance for detecting, investigating, and defending against the supply chain attack | Microsoft Security Blog</a></li>
<li><a href="https://unit42.paloaltonetworks.com/npm-supply-chain-attack/">"Shai-Hulud" Worm Compromises npm Ecosystem in Supply Chain Attack (Updated November 26)</a></li>

</ul>
</details>

**标签**: `#OpenAI`, `#security breach`, `#supply chain attack`, `#AI malware`, `#cybersecurity`

---

<a id="item-12"></a>
## [半数 AI 健康建议有误](https://decrypt.co/367689/half-ai-health-advice-wrong-seems-right) ⭐️ 8.0/10

一项发表在《BMJ Open》上的同行评审审计发现，五大主流 AI 聊天机器人的健康回复中近 50%存在问题，常常包含捏造的来源并以自信的口吻传播错误信息。 这引发了对 AI 聊天机器人在医疗等关键领域可靠性的严重担忧，不准确的建议可能导致有害决策。它强调了在将 AI 用于医疗指导之前需要进行严格验证和设置安全措施。 该审计评估了五个未具名的主流 AI 聊天机器人在各种健康查询中的回复，发现近一半存在问题，包括捏造的引用和自信但错误的陈述。该研究发表在权威同行评审医学期刊《BMJ Open》上。

rss · Decrypt · May 13, 14:55

**背景**: 像 ChatGPT、Gemini 和 Grok 这样的 AI 聊天机器人越来越多地被用于健康建议，但它们的训练数据可能包含不可靠的来源。与传统搜索引擎不同，聊天机器人以高度自信的方式呈现答案，使用户更难发现错误。这项研究突显了 AI 在医疗场景中感知可靠性与实际准确性之间的差距。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bmjopen.bmj.com/content/16/4/e112695">Generative artificial intelligence-driven chatbots and medical misinformation: an accuracy, referencing and readability audit | BMJ Open</a></li>
<li><a href="https://decrypt.co/367689/half-ai-health-advice-wrong-seems-right">Half of AI Health Advice Is Wrong—And Seems Just Right - Decrypt</a></li>

</ul>
</details>

**标签**: `#AI`, `#health`, `#misinformation`, `#chatbots`, `#research`

---

<a id="item-13"></a>
## [Codex 编码代理现已登陆 ChatGPT 移动应用](https://openai.com/index/work-with-codex-from-anywhere/) ⭐️ 7.0/10

OpenAI 已将其 Codex 编码代理集成到 ChatGPT 移动应用中，免费用户也可以随时随地获得编码帮助。 这一扩展使强大的 AI 编码工具更易获取，开发者无需桌面或 CLI 环境即可随时随地处理代码。 Codex 作为 ChatGPT 免费计划的一部分免费提供，但交互数据可能用于训练。移动应用提供了简化的界面来指导代理。

hackernews · mikeevans · May 14, 20:06 · [社区讨论](https://news.ycombinator.com/item?id=48140529)

**背景**: Codex 是 OpenAI 开发的 AI 编码代理，能够编写功能、修复 bug 和回答代码库问题。它最初于 2025 年 4 月以 CLI 工具形式发布，随后集成了桌面和 IDE。移动应用将其覆盖范围扩展至智能手机。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Codex_(AI_agent)">Codex (AI agent) - Wikipedia</a></li>
<li><a href="https://github.com/openai/codex">GitHub - openai/codex: Lightweight coding agent that runs in your terminal · GitHub</a></li>
<li><a href="https://openai.com/index/introducing-codex/">Introducing Codex | OpenAI</a></li>

</ul>
</details>

**社区讨论**: 社区成员对免费访问和远程工作流感到兴奋，但一些人指出，与桌面使用相比，移动界面可能导致指令不够精确，增加代码返工。

**标签**: `#AI coding assistant`, `#mobile development`, `#OpenAI`, `#developer tools`

---

<a id="item-14"></a>
## [CME 将于 6 月 8 日推出纳斯达克 CME 加密货币指数期货](https://www.coindesk.com/markets/2026/05/14/cme-dives-further-into-usd85-trillion-digital-assets-market-with-nasdaq-cme-crypto-index-futures) ⭐️ 7.0/10

CME 集团宣布将于 6 月 8 日推出纳斯达克 CME 加密货币指数期货（待监管批准），这是其首个市值加权期货合约，涵盖比特币及其他六种加密货币。 该产品为机构投资者提供了受监管的多元化数字资产敞口，进一步提升了加密货币的合法性，并可能增强流动性和价格发现。 该期货将以纳斯达克 CME 加密货币结算价格指数进行现金结算，并提供微型和大型两种合约规模，为不同交易策略提供灵活性。

rss · CoinDesk · May 14, 16:25

**背景**: CME 集团是领先的衍生品交易所，纳斯达克是全球指数提供商。纳斯达克 CME 加密货币指数是专为机构级加密货币敞口设计的基准，采用严格的流动性、交易所和托管标准。此次发布扩展了 CME 现有的加密衍生品产品线，包括比特币和以太坊期货。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cmegroup.com/media-room/press-releases/2026/5/14/cme_group_to_launchnasdaqcmecryptoindexfutures.html">CME Group to Launch Nasdaq CME Crypto Index Futures</a></li>
<li><a href="https://www.prnewswire.com/news-releases/cme-group-to-launch-nasdaq-cme-crypto-index-futures-302772026.html">CME Group to Launch Nasdaq CME Crypto Index Futures</a></li>
<li><a href="https://www.coindesk.com/markets/2026/05/14/cme-dives-further-into-usd85-trillion-digital-assets-market-with-nasdaq-cme-crypto-index-futures">CME dives further into $85 trillion digital assets market ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#futures`, `#institutional adoption`, `#CME`, `#digital assets`

---

<a id="item-15"></a>
## [Kimi WebBridge 让 AI 代理本地控制浏览器](https://decrypt.co/367916/kimi-webbridge-ai-agents-browser-local) ⭐️ 7.0/10

Moonshot AI 发布了 Kimi WebBridge 浏览器扩展，它与本地服务配对，通过 Chrome DevTools 协议让 AI 代理控制 Chrome 或 Edge，所有数据无需上传云端。 这种方法通过将用户会话和页面内容保留在本地机器上，解决了主要的隐私问题，使得表单填写和导航等强大的浏览器自动化任务在不牺牲数据安全的情况下得以实现。 该扩展使用一个本地后台服务与 AI 代理通信，代理发送命令进行点击、滚动、填写表单和截图，然后将结果返回给代理。

rss · Decrypt · May 14, 19:49

**背景**: 控制浏览器的 AI 代理通常依赖云端处理，这会将用户数据传输到远程服务器，从而引发隐私风险。Kimi WebBridge 颠覆了这一模式，通过本地运行代理，并利用 Chrome DevTools 协议直接与浏览器交互。这使得用户能够自动化重复的网页任务，同时将登录凭据和页面内容等敏感信息保留在自己的设备上。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.kimi.com/features/webbridge">WebBridge - Let Kimi Agent Drive Your Browser | Kimi</a></li>
<li><a href="https://decrypt.co/367916/kimi-webbridge-ai-agents-browser-local">Kimi WebBridge Lets AI Agents Drive Your Browser—And Keep ...</a></li>
<li><a href="https://tech.yahoo.com/ai/meta-ai/articles/kimi-webbridge-lets-ai-agents-194937263.html">Kimi WebBridge Lets AI Agents Drive Your Browser—And Keep Your...</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#browser automation`, `#privacy`, `#local AI`, `#extension`

---

<a id="item-16"></a>
## [研究：AI 代理执行危险任务而不理解风险](https://decrypt.co/367869/ai-agents-dangerous-tasks-without-understanding-consequences) ⭐️ 7.0/10

一项新研究揭示，旨在自动化任务的 AI 代理常常在未意识到其行为危险的情况下执行任务，突显了一个关键的安全缺陷。 这一发现凸显了 AI 对齐与安全方面的根本挑战，可能影响未来自主 AI 系统的监管与开发。 该研究专门考察了自动化任务的 AI 代理，发现它们缺乏对自身行为后果的认知，可能导致意外伤害。

rss · Decrypt · May 14, 17:32

**背景**: AI 代理是能够感知环境并采取行动以实现目标的自主软件系统。AI 对齐问题指的是确保这些系统按照人类价值观和意图行事。这项研究突显了当前代理设计中的一个空白，即安全考虑并未被内在地整合。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cloud.google.com/discover/what-are-ai-agents">What are AI agents ? Definition , examples, and types | Google Cloud</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_alignment">AI alignment - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#AI agents`, `#alignment`, `#research`

---

<a id="item-17"></a>
## [Kraken 用 Chainlink 替换 LayerZero 进行跨链桥接](https://www.coindesk.com/business/2026/05/14/kraken-to-replace-layerzero-with-chainlink-to-bridge-assets-across-blockchains) ⭐️ 6.0/10

Kraken 宣布将用 Chainlink 的跨链互操作协议（CCIP）取代 LayerZero，作为其封装比特币产品 kBTC 及未来封装资产的独家跨链基础设施。 此次迁移涉及超过 30 亿美元的总锁定价值，标志着在 LayerZero 上发生 2.92 亿美元 Kelp DAO 攻击事件后，跨链桥接格局的重大转变，可能促使更多协议优先考虑安全性。 Kraken 至少是 Kelp DAO 攻击后第四个弃用 LayerZero 的产品，此前 Solv Protocol、Re 和 KelpDAO 已将近 10 亿美元迁移至 Chainlink CCIP。

rss · CoinDesk · May 14, 15:17

**背景**: 跨链桥允许资产在不同区块链之间移动，但一直是黑客的频繁攻击目标，仅 2022 年就有超过 20 亿美元被盗。Chainlink CCIP 是一种跨链协议，设计上具有内置合规和隐私功能，强调安全性。LayerZero 是另一种流行的跨链协议，在 2026 年 4 月遭受了 2.92 亿美元的攻击（归因于 Lazarus Group），削弱了对其安全性的信任。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/05/14/kraken-to-replace-layerzero-with-chainlink-to-bridge-assets-across-blockchains">Kraken to replace LayerZero with Chainlink for kBTC, future ...</a></li>
<li><a href="https://www.coindesk.com/tech/2026/04/19/2026-s-biggest-crypto-exploit-kelp-dao-hit-for-usd292-million-with-wrapped-ether-stranded-across-20-chains">Kelp DAO exploited for $292 million with wrapped ether ...</a></li>
<li><a href="https://news.bitcoin.com/solv-protocol-and-re-switch-to-chainlink-ccip-moving-nearly-1b-away-from-layerzero/">Solv Protocol and Re Switch to Chainlink CCIP, Moving Nearly ...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#cryptocurrency`, `#interoperability`, `#oracles`

---

<a id="item-18"></a>
## [贝莱德与骏利亨德森实现基金即时赎回](https://www.coindesk.com/business/2026/05/14/blackrock-janus-henderson-tokenized-funds-get-instant-redemptions-with-new-usd1-billion-facility) ⭐️ 6.0/10

贝莱德与骏利亨德森推出了一项名为 Basin 的 10 亿美元信贷设施，允许其代币化货币市场基金即时赎回为稳定币，将结算时间从数天缩短至数秒。 这一发展将传统资产管理业与区块链流动性连接起来，使代币化基金对需要快速获取现金的机构投资者更加实用。 该设施由信贷平台 Grove 提供，支持贝莱德的 BUIDL 基金和骏利亨德森的代币化货币市场基金，每日稳定币流动性高达 10 亿美元。

rss · CoinDesk · May 14, 13:00

**背景**: 代币化基金将传统基金份额表示为区块链上的数字代币，从而实现更快、更便宜的交易。然而，由于底层资产结算，赎回通常需要数天。该设施利用信贷额度提供即时稳定币流动性，绕过了传统结算延迟。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/05/14/blackrock-janus-henderson-tokenized-funds-get-instant-redemptions-with-new-usd1-billion-facility">BlackRock, Janus Henderson tokenized funds get instant ...</a></li>
<li><a href="https://coinalertnews.com/news/2026/05/14/grove-basin-instant-redemptions">Grove Launches $1B Basin Facility for Instant Redemptions of ...</a></li>
<li><a href="https://phemex.com/news/article/blackrocks-22b-tokenized-fund-enables-instant-stablecoin-redemptions-81460">BlackRock's $2.2B Fund Offers Instant Stablecoin Redemptions ...</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#finance`, `#blockchain`, `#asset management`

---

<a id="item-19"></a>
## [穆迪授予代币化货币市场基金最高 Aaa-mf 评级](https://www.coindesk.com/markets/2026/05/14/moody-s-awards-top-rating-to-fidelity-and-blackrock-s-tokenized-money-market-funds) ⭐️ 6.0/10

穆迪将其最高评级 Aaa-mf 授予富达国际和贝莱德发行的代币化货币市场基金，表明这些基金具有最高水平的信用质量、流动性和资本保值能力。 来自主要评级机构的这一机构级验证可能加速代币化资产在传统金融中的采用，弥合 DeFi 与受监管市场之间的差距。 Aaa-mf 评级不仅评估违约风险，还评估流动性和资本稳定性，特别适用于那些保持资本并拥有强大流动性缓冲的基金。

rss · CoinDesk · May 14, 08:49

**背景**: 代币化货币市场基金将基金份额表示为区块链上的数字代币，结合了传统货币市场基金的可靠性与数字资产的速度和透明度。它们提供与短期无风险利率相当的回报，特别适合寻求稳定收益的加密原生投资者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/markets/2026/05/14/moody-s-awards-top-rating-to-fidelity-and-blackrock-s-tokenized-money-market-funds">Moody’s assigns Aaa-mf assessments to Fidelity International ...</a></li>
<li><a href="https://www.valuethemarkets.com/cryptocurrency/news/moodys-grants-aaa-mf-rating-to-fidelity-and-blackrock-tokenized-money-market-products">Moody's Grants AAA-mf Rating to Fidelity and BlackRock ...</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#DeFi`, `#ratings`, `#institutional finance`

---

<a id="item-20"></a>
## [OpenAI 在诉讼中加强 ChatGPT 安全功能](https://decrypt.co/367937/openai-new-chatgpt-safety-features-lawsuits-investigations) ⭐️ 6.0/10

OpenAI 增强了 ChatGPT 检测和回应自残与暴力迹象的能力，推出了新的安全功能，与此同时该公司因聊天机器人的有害互动而面临多起诉讼和监管调查。 此次更新意义重大，因为它直接回应了日益增长的法律和公众压力，要求 AI 公司防止其产品造成伤害，可能为整个行业的安全标准树立先例。 新的安全功能提高了 ChatGPT 实时识别危险内容的能力，但 OpenAI 未披露具体技术细节或基准。此举正值美国联邦贸易委员会调查以及多个家庭起诉称聊天机器人造成伤害之际。

rss · Decrypt · May 14, 21:43

**背景**: 像 ChatGPT 这样的大型语言模型有时会生成有害或危险的回复，包括关于自残或暴力的建议。AI 安全研究人员长期以来一直警告这些风险，全球监管机构也在日益审查 AI 公司的安全实践。

**标签**: `#AI safety`, `#ChatGPT`, `#OpenAI`, `#regulation`

---

<a id="item-21"></a>
## [ChatGPT 网络流量份额被竞争对手蚕食](https://decrypt.co/367884/chatgpt-losing-ground-anthrophic-google-numbers) ⭐️ 6.0/10

最新数据显示，ChatGPT 的网络流量份额正在下降，而 Anthropic 和 Google 等竞争对手正在增长，表明企业 AI 采用趋势正在转变。 这一转变表明企业正在探索 OpenAI 之外的替代方案，可能重塑 AI 行业的竞争格局，并影响 OpenAI 的市场主导地位。 文章引用了网络流量数据，但未提供具体百分比或时间范围；这是一篇简短的新闻报道，缺乏深入分析。

rss · Decrypt · May 14, 18:44

**背景**: ChatGPT 由 OpenAI 于 2022 年底推出，迅速成为主导的 AI 聊天机器人。然而，Anthropic 的 Claude 和 Google 的 Gemini 等竞争对手凭借强大能力崛起，吸引了企业客户。

**标签**: `#AI`, `#ChatGPT`, `#market trends`, `#competition`

---

<a id="item-22"></a>
## [Tether、Tron 和 TRM 冻结 4.5 亿美元非法加密资金](https://decrypt.co/367874/tether-tron-trm-financial-crime-unit-frozen-450-million-crypto-funds) ⭐️ 6.0/10

Tether、Tron 和 TRM Labs 通过与 23 个国家的执法机构建立公私合作伙伴关系，冻结了 4.5 亿美元的非法加密货币资金。 这表明加密平台与全球执法机构之间为打击非法活动而加强合作，可能提升对稳定币和区块链网络的信任。 该合作涉及市值最大的稳定币 Tether (USDT)、Tron 区块链以及提供交易监控工具的区块链情报公司 TRM Labs。

rss · Decrypt · May 14, 17:16

**背景**: Tether (USDT) 是一种与美元挂钩的稳定币，广泛用于交易和转账。Tron 是一种权益证明区块链，以高吞吐量著称。TRM Labs 提供加密交易的合规和调查解决方案。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tron_(blockchain)">Tron ( blockchain ) - Wikipedia</a></li>
<li><a href="https://www.trmlabs.com/">TRM Labs | Agents and intelligence to fight crime</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#blockchain`, `#security`, `#regulation`

---

<a id="item-23"></a>
## [Tezos 测试后量子隐私，创始人批评比特币](https://decrypt.co/367795/tezos-post-quantum-privacy-founder-slams-half-baked-bitcoin-theories) ⭐️ 6.0/10

Tezos 已在测试网上推出后量子隐私系统 TzEL，旨在保护加密交易数据免受未来量子计算攻击。创始人 Arthur Breitman 还批评比特币社区将量子威胁视为“半生不熟”的理论。 这一进展意义重大，因为它解决了量子计算机可能破解当前加密标准、威胁区块链安全的日益增长的担忧。Tezos 的主动做法可能为其他区块链采用后量子密码学树立先例。 TzEL 结合了后量子密码学和 zk-STARK 证明，以确保隐私和抗量子性。该系统目前处于测试网阶段，旨在对抗“先收集，后解密”攻击。

rss · Decrypt · May 14, 13:01

**背景**: 后量子密码学指被认为能够抵御量子计算机攻击的密码算法。“先收集，后解密”攻击指对手现在收集加密数据，期望未来量子计算机足够强大时进行解密。Tezos 是一个支持智能合约的区块链平台，注重形式化验证和可升级性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367795/tezos-post-quantum-privacy-founder-slams-half-baked-bitcoin-theories">Tezos Tests Post-Quantum Privacy as Founder Slams ... - Decrypt</a></li>
<li><a href="https://cointelegraph.com/news/tezos-quantum-resistant-private-payments-prototype-testnet">Tezos Developers Test quantum-Resistant Blockchain Privacy System</a></li>
<li><a href="https://tech.yahoo.com/cybersecurity/articles/tezos-tests-post-quantum-privacy-130103366.html">Tezos Tests Post-Quantum Privacy as Founder Slams 'Half-Baked' Bitcoin Quantum Theories</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#post-quantum cryptography`, `#Tezos`, `#privacy`

---

<a id="item-24"></a>
## [嘉信理财开始向美国用户提供比特币和以太坊交易](https://decrypt.co/367768/charles-schwab-begins-bitcoin-ethereum-trading-us-users) ⭐️ 6.0/10

嘉信理财已开始允许部分美国用户直接在其传统投资组合中交易比特币和以太坊。 这标志着加密货币主流采用的重要一步，一家大型传统金融机构将数字资产整合到其平台中，可能吸引更多保守投资者。 该服务目前仅限部分用户使用，且仅支持比特币和以太坊。用户可以在一个账户中同时管理加密货币、股票、债券和其他资产。

rss · Decrypt · May 13, 16:31

**背景**: 嘉信理财是美国最大的经纪公司之一，管理着数万亿美元的资产。此前，该公司通过 ETF 和期货提供间接的加密货币敞口，但这是首次允许直接交易加密货币。

**标签**: `#cryptocurrency`, `#finance`, `#bitcoin`, `#ethereum`, `#trading`

---

<a id="item-25"></a>
## [英国央行将稳定币视为新货币形式](https://decrypt.co/367750/bank-england-treating-stablecoins-new-form-money-exec) ⭐️ 6.0/10

英国央行高管 Sasha Mills 表示，央行将稳定币视为一种新的货币形式，并且在代币化存款和稳定币之间不会选择赢家。 这标志着主要央行采取了平衡的监管态度，可能影响全球稳定币监管并促进数字支付创新。 该声明于周三发布，但文章未提供具体日期。英国央行的立场在代币化存款和稳定币之间保持中立。

rss · Decrypt · May 13, 15:57

**背景**: 稳定币是旨在保持价值稳定的加密货币，通常与美元等法定货币挂钩。代币化存款是区块链上银行账户余额的数字表示，受到监管并享有存款保险。英国财政部此前已承认稳定币为有效支付形式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://bankingjournal.aba.com/2026/03/tokenized-deposits-the-future-of-tokenized-money-for-financial-market-settlement/">Tokenized deposits: the future of tokenized money for ...</a></li>
<li><a href="https://www.newyorkfed.org/research/staff_reports/sr1179">Stablecoins vs. Tokenized Deposits: The Narrow Banking Debate ...</a></li>
<li><a href="https://thedefiant.io/news/defi/uk-crypto-regulation-stablecoins">U . K . Embraces Stablecoins as 'Valid Form of Payment' - "The Defia...</a></li>

</ul>
</details>

**标签**: `#stablecoins`, `#regulation`, `#central bank`, `#cryptocurrency`

---

<a id="item-26"></a>
## [CertiK CEO：DeFi 攻击者利用 AI 在支出上碾压防御者](https://www.theblock.co/post/401280/unfair-game-certik-ceo-defi-attackers-using-ai-outspend-defenders?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

CertiK CEO 警告称，DeFi 攻击者正越来越多地利用 AI 攻击运营安全和供应链弱点，在资金不对称的对抗中支出远超防御者。 从智能合约漏洞转向运营和供应链攻击，标志着 DeFi 面临更难防御的新威胁格局，可能导致更大损失并削弱对去中心化金融的信任。 该评论由 CertiK CEO 顾荣辉在行业活动中提出，强调攻击者现在利用人为错误、密钥管理和第三方依赖而非代码漏洞。

rss · The Block · May 14, 19:46

**背景**: CertiK 是一家领先的区块链安全公司，利用 AI 和形式化验证审计智能合约。DeFi（去中心化金融）平台管理着数十亿美元资产，但常因智能合约漏洞遭受重大黑客攻击。然而，攻击者正转向成本更低、影响更大的运营和供应链攻击，如钓鱼或基础设施入侵，传统代码审计难以防御。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/401280/unfair-game-certik-ceo-defi-attackers-using-ai-outspend-defenders">'It's an unfair game': CertiK CEO says DeFi attackers using ...</a></li>
<li><a href="https://www.certik.com/">Largest Blockchain Security Auditor - CertiK</a></li>
<li><a href="https://www.ainvest.com/news/escalating-threat-supply-chain-risks-defi-10-billion-wake-call-investors-2512/">The Escalating Threat of Supply Chain Risks in DeFi: A $10 ...</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#AI`, `#security`, `#blockchain`

---

<a id="item-27"></a>
## [ZachXBT 指控 LAB 代币 95%由内部人控制](https://www.theblock.co/post/401290/zachxbt-alleges-95-insider-control-of-lab-token-in-investigation-into-ai-terminals-6-billion-fdv-project?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

区块链调查员 ZachXBT 指控，在一个完全稀释估值（FDV）达 60 亿美元的项目中，LAB 代币供应量的 95%被内部人士通过隐藏的场外交易、私人贷款以及与操纵计划相关的做市商所控制。 这项调查揭示了高 FDV 加密项目中可能普遍存在的内部操纵行为，削弱了对代币经济学的信任，并引发了对 AI 代币领域散户投资者保护的担忧。 LAB 代币与一个 AI 终端项目相关，ZachXBT 的发现包括隐藏交易的证据以及此前与操纵有关的做市商。该项目 60 亿美元的 FDV 基于完全稀释的代币供应量，可能无法反映实际流通供应量。

rss · The Block · May 14, 14:34

**背景**: 完全稀释估值（FDV）是一种计算加密货币在全部代币流通时的市值的指标，常用于评估项目价值。ZachXBT 是一位知名的化名区块链调查员，以揭露加密货币欺诈和骗局而闻名。内部人士控制代币供应可能导致价格操纵，并为早期投资者带来不公平优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ZachXBT">ZachXBT</a></li>
<li><a href="https://www.okx.com/learn/what-is-fully-diluted-valuation-fdv">What is Fully Diluted Valuation ( FDV ): crypto meme or red flag? | OKX</a></li>
<li><a href="https://coinmarketcap.com/currencies/lab/">LAB price today, LAB to USD live price, marketcap and chart ...</a></li>

</ul>
</details>

**标签**: `#crypto`, `#insider trading`, `#AI token`, `#blockchain`, `#investigation`

---