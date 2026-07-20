---
layout: default
title: "Horizon Summary: 2026-07-20 (ZH)"
date: 2026-07-20
lang: zh
---

> From 33 items, 13 important content pieces were selected

---

1. [保龄球馆老板用 1600 美元的 ESP32 替代 12 万美元系统](#item-1) ⭐️ 9.0/10
2. [Claude Fable 给出雅可比猜想的反例](#item-2) ⭐️ 9.0/10
3. [Claude Code 改用 Rust 重写的 Bun](#item-3) ⭐️ 8.0/10
4. [阿里巴巴发布 Qwen 3.8，2.4 万亿参数开源权重大模型](#item-4) ⭐️ 8.0/10
5. [Zcash 发布新节点，目标实现 Visa 级别隐私与 5 万 TPS](#item-5) ⭐️ 8.0/10
6. [Allbridge Core 因 165 万美元闪电贷攻击暂停运行](#item-6) ⭐️ 8.0/10
7. [硬件并不难：销售 2500 台 MIDI 录音机的经验教训](#item-7) ⭐️ 7.0/10
8. [Minecraft: Java 版切换至 SDL3](#item-8) ⭐️ 7.0/10
9. [Kagi 的 Orion 浏览器：关于 Bug 和精致度的褒贬不一的评价](#item-9) ⭐️ 6.0/10
10. [开发者分享加入 IndieWeb 的旅程与心得](#item-10) ⭐️ 6.0/10
11. [比特币量子恢复工具排除中本聪的币](#item-11) ⭐️ 6.0/10
12. [法国命令 ISP 封锁 Polymarket](#item-12) ⭐️ 6.0/10
13. [特朗普瞄准巴西 Pix，稳定币悄然崛起](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [保龄球馆老板用 1600 美元的 ESP32 替代 12 万美元系统](https://news.ycombinator.com/item?id=48968606) ⭐️ 9.0/10

一位保龄球馆老板使用 ESP32 微控制器为 8 条球道构建了功能完整的计分和控制系统，成本仅 1600 美元，而商业替换方案需 8 万至 12 万美元。这个名为 OpenLaneLink 的开源项目采用了 ESPNow 网状网络、Redis 事件流和 React 前端。 这展示了用现代嵌入式硬件改造传统工业系统可实现 75 倍的成本降低，挑战了利基市场的供应商锁定。它可能激励保龄球馆和其他拥有昂贵专有系统的行业进行类似的 DIY 替换。 该系统使用 ESP32 节点，采用 ESPNow 星形拓扑网状网络和 RS485 有线回退，连接到运行 Redis 和状态机的树莓派。每条球道对的硬件成本约 200 美元，通过更换预刷控制器可在 10 分钟内完成维修。

hackernews · section33 · Jul 19, 14:41

**背景**: 商业保龄球计分系统是专有的，价格昂贵，且通常需要供应商支持进行维修和升级。ESP32 是一款低成本微控制器，内置 Wi-Fi 和蓝牙，广泛用于物联网项目。用现代嵌入式系统改造传统设备是降低成本和提高灵活性的一个增长趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ESP32">ESP32 - Wikipedia</a></li>
<li><a href="https://sesamedisk.com/diy-bowling-system-esp32-replacement/">Replacing $120K Bowling System with $1,600 - Sesame Disk</a></li>
<li><a href="https://promwad.com/news/retrofit-industrial-equipment-iot-security">Retrofitting Legacy Industrial Equipment with IoT: Protocol Bridges and Security Pitfalls</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了改造旧机床和机械保龄球道的类似经验，称赞该项目的成本节约和开源方法。一些人讨论了添加 LED 照明、DMX 控制和自助支付集成，显示出对进一步创新的热情。

**标签**: `#embedded systems`, `#retrofit`, `#ESP32`, `#cost reduction`, `#legacy systems`

---

<a id="item-2"></a>
## [Claude Fable 给出雅可比猜想的反例](https://xcancel.com/__alpoge__/status/2079028340955197566) ⭐️ 9.0/10

据报道，Anthropic 的 Claude Fable 模型生成了雅可比猜想的一个反例，这是代数几何中一个长期未解的问题，该消息由一位用户在 X（原 Twitter）上分享。 这标志着人工智能辅助数学研究的一个重要里程碑，表明大型语言模型能够为解决或反驳开放问题做出贡献。它可能加速自动定理证明的进展，并激发对长期猜想的新方法。 雅可比猜想指出，如果一个多项式映射的雅可比行列式是非零常数，那么它有一个多项式逆。据报道，该反例由 Claude Fable 5 生成，这是 Anthropic 的 Claude 系列中的最新模型，以其在长周期任务中的强大能力而闻名。

hackernews · loubbrad · Jul 20, 02:51 · [社区讨论](https://news.ycombinator.com/item?id=48973869)

**背景**: 雅可比猜想是代数几何和交换代数中的一个著名问题，最初于 1884 年针对两个变量提出，并于 1939 年推广到一般形式。它以许多有缺陷的证明而臭名昭著。Claude Fable 5 是 Anthropic 开发的最先进的大型语言模型，在更强大但受限的 Claude Mythos 版本之后发布。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jacobian_conjecture">Jacobian conjecture</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable">Claude Fable</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区评论表达了怀疑，一位用户指出雅可比猜想有许多有缺陷的证明，并暗示 LLM 可能从先前的错误工作中综合出了一个反例。另一条评论幽默地希望 LLM 接下来能解决 Collatz 猜想，从而节省许多浪费的努力。

**标签**: `#LLM`, `#mathematics`, `#AI research`, `#Jacobian conjecture`, `#automated theorem proving`

---

<a id="item-3"></a>
## [Claude Code 改用 Rust 重写的 Bun](https://simonwillison.net/2026/Jul/19/claude-code-in-bun-in-rust/) ⭐️ 8.0/10

Anthropic 的 AI 编程代理 Claude Code 现在使用 Bun JavaScript 运行时，而 Bun 已从 Zig 重写为 Rust。这一变更以巨大的拉取请求在不到一个月内合并。 这一转变影响了 JavaScript 运行时生态系统，并凸显了 AI 在大规模软件重写中日益重要的作用。它还引发了关于项目治理和工程成熟度的质疑，因为 Bun 现在由 Anthropic 拥有。 重写后的 Bun 尚未公开发布；Claude Code 搭载的是 Bun v1.4.0 预览版，而最新公开版本是 v1.3.14。重写的动机是需要自动化内存管理，与 Zig 相比，Rust 可以自动处理。

hackernews · tosh · Jul 19, 10:03 · [社区讨论](https://news.ycombinator.com/item?id=48966569)

**背景**: Bun 是一个快速的全能 JavaScript 运行时、打包器、测试运行器和包管理器，旨在作为 Node.js 的直接替代品。Claude Code 是 Anthropic 的代理式编码工具，运行在终端中，帮助开发者更快地编写代码。最初的 Bun 是用 Zig 编写的，Zig 是一种底层系统编程语言。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些人赞扬转向 Rust 的技术理由，而另一些人则批评重写过程中的沟通和治理问题。还有人质疑使用 JavaScript 运行时来构建终端 UI，并担心 Bun 作为开源项目可能实际上已被放弃。

**标签**: `#Bun`, `#Rust`, `#Claude Code`, `#JavaScript runtime`, `#AI-assisted development`

---

<a id="item-4"></a>
## [阿里巴巴发布 Qwen 3.8，2.4 万亿参数开源权重大模型](https://twitter.com/Alibaba_Qwen/status/2078759124914098291) ⭐️ 8.0/10

阿里巴巴宣布推出 Qwen 3.8，这是一个拥有 2.4 万亿参数的开源权重大型语言模型，直接回应了 Moonshot AI 近期发布的 2.8 万亿参数 Kimi K3 模型。 这一公告加剧了开源权重大模型领域的竞争，可能加速创新，为开发者提供更强大、更易获取的模型。阿里巴巴与 Moonshot AI 之间的竞争有望为用户带来更好的性能和更低的成本。 Qwen 3.8 拥有 2.4 万亿参数，而 Kimi K3 拥有 2.8 万亿参数；两者均为开源权重模型。阿里巴巴计划公开发布 Qwen 3.8 的权重，但具体日期尚未确定。

hackernews · nh43215rgb · Jul 19, 08:44 · [社区讨论](https://news.ycombinator.com/item?id=48966120)

**背景**: 大型语言模型（LLM）是在海量文本数据上训练的人工智能系统，能够生成类似人类的文本。参数是训练过程中学习到的内部权重；通常参数越多，模型的容量和潜在性能越强。开源权重模型允许开发者下载并微调模型权重，相比封闭 API 提供了更多的控制权和定制能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K 3 - Kimi API Platform</a></li>
<li><a href="https://www.bbc.com/news/articles/cy9w4q8pgp0o">China's Moonshot AI claims Kimi K 3 can rival OpenAI and Anthropic</a></li>
<li><a href="https://galileo.ai/blog/llm-parameters-model-evaluation">Essential LLM Parameters Every AI Team Needs | Galileo</a></li>

</ul>
</details>

**社区讨论**: 社区对这场竞争感到兴奋，许多用户希望推出更小的模型版本以便本地使用。然而，一些用户反映此前 Qwen 模型的使用体验不佳，认为其可用性差且相比 DeepSeek 成本高昂。还有用户期待 DeepSeek 即将发布的新模型。

**标签**: `#LLM`, `#open-weights`, `#Alibaba`, `#Qwen`, `#AI competition`

---

<a id="item-5"></a>
## [Zcash 发布新节点，目标实现 Visa 级别隐私与 5 万 TPS](https://www.coindesk.com/tech/2026/07/16/inside-zcash-s-new-node-that-targets-visa-scale-privacy-at-50-000-transactions-per-second) ⭐️ 8.0/10

Zcash 宣布推出一种新节点，能够在保护隐私的同时每秒处理 5 万笔交易，目标是与 Visa 的交易吞吐量相媲美。 这一里程碑表明，区块链隐私和可扩展性可以在 Visa 级别共存，可能推动隐私支付的主流采用。 该节点利用先进的零知识证明技术实现高吞吐量而不牺牲隐私，但具体实现细节尚未公开。

rss · CoinDesk · Jul 19, 05:37

**背景**: Zcash 是一种注重隐私的加密货币，使用零知识证明（zk-SNARKs）来隐藏交易细节。历史上，隐私币在可扩展性方面一直面临挑战，每秒处理的交易量通常远低于 Visa 等中心化支付系统（后者处理数千 TPS）。这一公告表明在隐私与高吞吐量结合方面取得了突破。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zcash.readthedocs.io/en/latest/rtd_pages/zcashd.html">Zcash Full Node and CLI — Zcash Documentation...</a></li>
<li><a href="https://github.com/ZcashFoundation/zebra">GitHub - ZcashFoundation/zebra: Zcash - Financial Privacy in Rust</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-knowledge_proof">Zero-knowledge proof - Wikipedia</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#privacy`, `#scalability`, `#Zcash`, `#cryptocurrency`

---

<a id="item-6"></a>
## [Allbridge Core 因 165 万美元闪电贷攻击暂停运行](https://www.theblock.co/post/408855/allbridge-core-exploit?utm_source=rss&utm_medium=rss) ⭐️ 8.0/10

跨链稳定币桥 Allbridge Core 在一次闪电贷攻击中损失约 165 万美元后暂停了协议运行。安全公司 PeckShield 和 CertiK 报告称，攻击者已将盗取的资金从 Solana 桥接至以太坊。 此事件凸显了跨链桥（DeFi 中的关键基础设施）持续存在的安全漏洞。安全公司的快速响应凸显了监控和迅速行动以减轻进一步损害的重要性。 攻击者利用闪电贷操纵协议的流动性池，盗取了 165 万美元。被盗资金随后从 Solana 桥接至以太坊，增加了追踪难度。

rss · The Block · Jul 20, 03:33

**背景**: 闪电贷攻击是一种 DeFi 攻击方式，攻击者在单笔交易中无需抵押即可借入大量加密货币，利用借入的资金操纵价格或利用协议漏洞。Allbridge Core 是一个跨链桥，通过原生流动性池在不同区块链之间实现原生稳定币转移，无需包装代币。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://hacken.io/discover/flash-loan-attacks/">Flash Loan Attacks: How They Work, Real Examples, and How to Prevent Them</a></li>
<li><a href="https://docs-core.allbridge.io/">What is Allbridge Core? | Allbridge Core</a></li>

</ul>
</details>

**标签**: `#DeFi`, `#security`, `#flash loan`, `#blockchain`, `#exploit`

---

<a id="item-7"></a>
## [硬件并不难：销售 2500 台 MIDI 录音机的经验教训](https://chipweinberger.com/articles/20260719-hardware-is-not-so-hard) ⭐️ 7.0/10

一位硬件创业者分享了成功销售 2500 台简单 MIDI 录音机的经验，认为如果产品设计保持简单，硬件开发并不像通常认为的那样困难。 这篇文章为有志于硬件创业的人提供了实用且反直觉的见解，挑战了“硬件天生困难”的主流说法，并提供了一种低风险硬件产品开发的蓝图。 作者强调保持物料清单精简（25 个元件）并使用现成部件以最小化复杂性和成本。该产品是一款简单的 MIDI 录音机，可录制到 microSD 卡，通过不包含无线模块来避免认证要求。

hackernews · chipweinberger · Jul 19, 10:34 · [社区讨论](https://news.ycombinator.com/item?id=48966713)

**背景**: MIDI（乐器数字接口）是一种标准协议，允许电子乐器、计算机和音频设备相互通信和同步。MIDI 录音机捕获的是 MIDI 数据（音符事件、控制变化）而非音频，使音乐家能够编辑和重放演奏。硬件产品开发通常涉及设计、原型制作、测试、认证（例如无线设备的 FCC 认证）和制造，这些过程可能成本高昂且复杂。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MIDI">MIDI - Wikipedia</a></li>
<li><a href="https://learn.sparkfun.com/tutorials/midi-tutorial/all">MIDI Tutorial - SparkFun Learn</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍赞赏文章中的实用建议，但也提出了重要的注意事项：对于包含无线模块的产品，认证（FCC、CE）是主要的成本和障碍；从几百台扩展到数百万台会带来新的挑战。一些人还指出，这个特定产品（25 个元件，无无线模块）的简单性并不代表大多数硬件项目。

**标签**: `#hardware`, `#entrepreneurship`, `#product design`, `#MIDI`

---

<a id="item-8"></a>
## [Minecraft: Java 版切换至 SDL3](https://www.minecraft.net/en-us/article/minecraft-26-3-snapshot-4) ⭐️ 7.0/10

Minecraft: Java 版在其最新快照中采用了 SDL3，这是 Simple DirectMedia Layer 库的最新主版本。这一变化取代了之前基于 SDL2 的输入和窗口系统。 此次更新提升了这款全球最受欢迎游戏的跨平台兼容性和性能。它也证明了 SDL3 已准备好用于大规模生产环境，鼓励其他开发者进行迁移。 此次迁移得益于 GTNH 模组包团队成员贡献的 LWJGL 绑定。已知问题包括在 Windows 多显示器环境下和 Wayland 上使用独占全屏模式时可能崩溃。

hackernews · ObviouslyFlamer · Jul 19, 11:48 · [社区讨论](https://news.ycombinator.com/item?id=48967256)

**背景**: SDL（Simple DirectMedia Layer）是一个跨平台库，提供对音频、键盘、鼠标和图形硬件的底层访问。SDL3 于 2025 年 1 月发布，是一次重大更新，改进了 API 并提升了性能。Minecraft: Java 版使用 LWJGL（轻量级 Java 游戏库）来绑定 SDL 等原生库。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SDL_library">SDL library</a></li>
<li><a href="https://wiki.libsdl.org/">SDL Wiki: SDL3/FrontPage</a></li>
<li><a href="https://www.phoronix.com/news/SDL3-Built-In-Snake-Game">SDL 3 Library Adds A Built-In Snake Game - Phoronix</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享了迁移经验，一位开发者指出从 GLFW 迁移到 SDL3 基本顺利，但在全屏模式上遇到了一些问题。另一位评论者担心已知的 Windows 和 Wayland 上的独占全屏崩溃问题可能成为快照版本的阻塞性 bug。

**标签**: `#Minecraft`, `#SDL3`, `#game development`, `#open source`

---

<a id="item-9"></a>
## [Kagi 的 Orion 浏览器：关于 Bug 和精致度的褒贬不一的评价](https://orionbrowser.com/) ⭐️ 6.0/10

Kagi 的 Orion 浏览器提供内置广告拦截和垂直标签功能，但用户反馈指出存在大量 Bug 且缺乏精致度，尤其是在移动端和 Linux 测试版上。 Orion 代表了一种注重隐私的主流浏览器替代方案，但其当前的不稳定性可能阻碍用户将其作为可靠的日常浏览器使用。 该浏览器使用 WebKit 渲染引擎，支持 macOS、iOS 和 Linux 测试版。部分用户报告设置页面损坏以及缺少文本选择时的“搜索...”等功能。

hackernews · sebjones · Jul 19, 19:13 · [社区讨论](https://news.ycombinator.com/item?id=48970894)

**背景**: Kagi 是一家付费无广告搜索引擎公司，同时也开发 Orion 浏览器。Orion 旨在提供快速、私密的浏览体验，内置广告拦截和垂直标签功能，与 Safari 和 Firefox 等浏览器竞争。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://orionbrowser.com/">Orion Browser by Kagi</a></li>
<li><a href="https://blog.kagi.com/orion-features">Kagi Blog - Orion browser features</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kagi_(search_engine)">Kagi (search engine)</a></li>

</ul>
</details>

**社区讨论**: 社区意见不一：一些用户称赞 Orion 的广告拦截和标签管理功能，而另一些用户则报告存在持续性的 Bug 和缺乏精致度。部分用户因问题而放弃使用 Orion，但也有一些日常用户认为它足够稳定。

**标签**: `#web browser`, `#Kagi`, `#ad-blocking`, `#privacy`, `#beta software`

---

<a id="item-10"></a>
## [开发者分享加入 IndieWeb 的旅程与心得](https://en.andros.dev/blog/0b8e451e/i-joined-the-indieweb-heres-what-i-learned/) ⭐️ 6.0/10

一位开发者记录了自己加入 IndieWeb 运动的经历，涵盖了技术搭建和拥有自己内容背后的哲学动机。 这一亲身经历凸显了采用 IndieWeb 原则的实际挑战与回报，可能激励更多人掌控自己的在线存在，减少对中心化平台的依赖。 文章讨论了使用静态网站生成器、webmention 和 POSSE（在自己的网站上发布，在其他地方同步）来与社交媒体集成，但指出了所涉及的技术复杂性。

hackernews · andros · Jul 19, 11:14 · [社区讨论](https://news.ycombinator.com/item?id=48966984)

**背景**: IndieWeb 是一个社区驱动的运动，倡导个人在个人网站上拥有自己的数据和身份，而不是依赖 Facebook 或 Twitter 等企业平台。关键概念包括 POSSE 和用于跨站点交互的 webmention。该运动强调用户控制和内容所有权。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/IndieWeb">IndieWeb - Wikipedia</a></li>
<li><a href="https://indieweb.org/">IndieWeb</a></li>

</ul>
</details>

**社区讨论**: 评论中突出了可用性问题：一位用户认为技术复杂性使 IndieWeb 对大多数人不可行，而其他人则赞扬这种方法并建议替代方案如 Nostr 或 Indiekit。另一条评论反思了自我表达与平台便利性之间的吸引力。

**标签**: `#IndieWeb`, `#decentralization`, `#web development`, `#social media`

---

<a id="item-11"></a>
## [比特币量子恢复工具排除中本聪的币](https://www.coindesk.com/tech/2026/07/19/bitcoin-s-quantum-problem-gets-a-recovery-tool-but-not-for-satoshi-s-1-1-million-coin) ⭐️ 6.0/10

比特币开发者提出了一种使用零知识证明的提交/揭示恢复工具，以保护钱包免受量子攻击，但由于中本聪的 110 万枚比特币地址格式独特且缺乏派生路径，该工具无法恢复它们。 该工具是比特币迈向抗量子安全的重要一步，但排除中本聪的币引发了对最古老地址长期安全性的质疑，以及对比特币安全模型的更广泛影响。 该恢复工具依赖于派生路径，而中本聪的早期地址（以'1'开头）缺少该路径，因此不兼容。该工具使用零知识证明，允许用户在不暴露私钥的情况下证明所有权并恢复资金。

rss · CoinDesk · Jul 19, 10:00

**背景**: 量子计算机一旦足够强大，就可能破解比特币的椭圆曲线密码学，威胁私钥安全。比特币地址随时间演变，较新的格式如 SegWit（以'3'或'bc1'开头）支持更高级的功能。中本聪的币存储在旧的支付到公钥哈希（P2PKH）地址中，这些地址缺少派生路径，因此与现代恢复机制不兼容。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cryptobriefing.com/bitcoin-quantum-attack-recovery-tool/">Bitcoin introduces recovery tool for quantum attack vulnerabilities</a></li>
<li><a href="https://www.hokanews.com/2026/07/bitcoin-quantum-recovery-tool-offers.html">Bitcoin Quantum Recovery Tool Offers Hope for Vulnerable Wallets - HOKANEWS.COM</a></li>
<li><a href="https://cryptonews.net/news/bitcoin/33171555/">Bitcoin Quantum Recovery Tool Proves Feasible—but Satoshi’s 1.1 Million BTC Still Lack Protection</a></li>

</ul>
</details>

**社区讨论**: 社区意见分歧：一些人认为该工具是必要的预防措施，而另一些人则争论中本聪的币应被视为对量子未来的捐赠还是比特币安全模型的定时炸弹。核心开发者定期讨论让这些币不受保护的影响。

**标签**: `#Bitcoin`, `#quantum computing`, `#cryptography`, `#blockchain`

---

<a id="item-12"></a>
## [法国命令 ISP 封锁 Polymarket](https://www.coindesk.com/policy/2026/07/18/france-orders-country-s-internet-service-providers-to-block-polymarket) ⭐️ 6.0/10

法国已命令其互联网服务提供商封锁基于加密货币的预测市场平台 Polymarket，理由是违反国家赌博法。 此举凸显了监管机构对去中心化预测市场日益严格的审查，尤其是在 Polymarket 的世界杯市场成为历史上最大的事件合约之际。这可能为考虑类似禁令的其他国家树立先例。 该命令在世界杯决赛前生效，届时将结算 Polymarket 最大的事件市场。Polymarket 已在巴西、意大利等多个司法管辖区被禁，此前在美国也被封锁。

rss · CoinDesk · Jul 18, 21:52

**背景**: Polymarket 是一家美国创立、注册在巴拿马的平台，允许用户通过 Polygon 区块链使用加密货币对结果下注。该平台因允许对军事冲突等敏感事件赌博以及出现内幕交易案例而受到批评。该平台未被标记为体育博彩，但 63%的交易与体育相关。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket</a></li>

</ul>
</details>

**标签**: `#regulation`, `#cryptocurrency`, `#blockchain`, `#France`

---

<a id="item-13"></a>
## [特朗普瞄准巴西 Pix，稳定币悄然崛起](https://www.coindesk.com/business/2026/07/18/trump-targets-brazil-s-payments-system-while-dollar-stablecoins-quietly-dominate-country-s-payments) ⭐️ 6.0/10

美元稳定币在巴西支付领域的使用日益增长，与此同时，政治行动正针对当地 Pix 支付系统。 这一趋势可能削弱巴西的主权支付系统，并挑战美元在数字金融中的主导地位，影响全球支付和地缘政治。 Pix 处理的交易价值是信用卡和借记卡总和的 8.6 倍，月活跃用户超过 2 亿。稳定币提供了一种可编程、与美元挂钩的替代方案。

rss · CoinDesk · Jul 18, 16:09

**背景**: Pix 是巴西央行推出的即时支付系统，采用强制参与和零定价模式，已被广泛采用。美元稳定币是与美元挂钩的加密货币，用于支付和价值储存，尤其在货币不稳定的国家。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pix_(payment_system)">Pix (payment system) - Wikipedia</a></li>
<li><a href="https://www.okx.com/en-ae/learn/stablecoins-dollar-global-finance">Stablecoins and the Dollar : How They’re Reshaping... | OKX UAE</a></li>
<li><a href="https://www.cfr.org/articles/why-china-spooked-dollar-stablecoins-and-how-it-will-respond">Why China Is Spooked by Dollar Stablecoins and How It Will Respond</a></li>

</ul>
</details>

**标签**: `#stablecoins`, `#payments`, `#geopolitics`, `#cryptocurrency`

---