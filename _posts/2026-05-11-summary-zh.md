---
layout: default
title: "Horizon Summary: 2026-05-11 (ZH)"
date: 2026-05-11
lang: zh
---

> From 36 items, 12 important content pieces were selected

---

1. [硬件认证成为垄断控制工具](#item-1) ⭐️ 8.0/10
2. [本地 AI 将成为常态](#item-2) ⭐️ 8.0/10
3. [开发者回归手工设计，放弃 AI 生成代码](#item-3) ⭐️ 8.0/10
4. [虚构事件报告揭示 Rust 供应链风险](#item-4) ⭐️ 8.0/10
5. [LayerZero 就 Kelp DAO 漏洞事件道歉](#item-5) ⭐️ 8.0/10
6. [在 24GB 内存的 M4 Mac 上运行本地大语言模型](#item-6) ⭐️ 7.0/10
7. [Obsidian 插件被滥用以部署远程访问木马](#item-7) ⭐️ 7.0/10
8. [Joanna Rutkowska 推出探讨理性与人文主义的新博客](#item-8) ⭐️ 7.0/10
9. [PS3 模拟器开发者恳请停止 AI PR 洪流](#item-9) ⭐️ 7.0/10
10. [重返 AWS 引发关于复杂性和开源的辩论](#item-10) ⭐️ 7.0/10
11. [贝莱德扩大链上代币化基金产品](#item-11) ⭐️ 7.0/10
12. [AI 模型在幸存者游戏中密谋背叛](#item-12) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [硬件认证成为垄断控制工具](https://grapheneos.social/@GrapheneOS/116550899908879585) ⭐️ 8.0/10

GrapheneOS 社交媒体上的一场批判性讨论指出，硬件认证原本旨在提升安全性，如今却被大型平台用来强制设备合规，并将未经批准的设备排除在数字服务之外。 这一趋势威胁数字自由，使垄断企业能够将用户锁定在经批准的生态系统中，可能将拥有或修改自己设备的用户排斥在基本在线服务之外。 硬件认证使用 TPM 等防篡改芯片生成加密可验证的设备指纹，但当前实现缺乏零知识证明，使得通过认证数据包可追踪设备。

hackernews · ChuckMcM · May 10, 17:54 · [社区讨论](https://news.ycombinator.com/item?id=48086190)

**背景**: 可信计算（TC）是一种通过硬件和软件强制系统按预期行为运行的技术，通常使用可信平台模块（TPM）。包括自由软件活动家在内的批评者认为，TC 可能被用来对付设备所有者，以实施数字版权管理（DRM）并限制用户自由。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.android.com/privacy-and-security/security-key-attestation">Verify hardware-backed key pairs with key attestation | Security | Android Developers</a></li>
<li><a href="https://en.wikipedia.org/wiki/Trusted_Computing">Trusted Computing</a></li>
<li><a href="https://en.wikipedia.org/wiki/Trusted_Platform_Module">Trusted Platform Module - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了强烈反对，有人指出远程认证将‘扼杀计算自由’，还有人批评缺乏盲签名等隐私保护措施。评论引用了英特尔 1999 年 CPU 序列号争议和 Windows 11 的 TPM 要求作为先例。

**标签**: `#hardware attestation`, `#trusted computing`, `#digital rights`, `#monopoly`, `#privacy`

---

<a id="item-2"></a>
## [本地 AI 将成为常态](https://unix.foo/posts/local-ai-needs-to-be-norm/) ⭐️ 8.0/10

一篇高评分文章指出，本地 AI 模型将成为常态，从大型数据中心到配备 128 GB VRAM 的 MacBook Pro 等个人设备的演进已经可见。 这一转变可能使 AI 访问民主化，减少对云服务的依赖，并改善用户的隐私和延迟，影响消费者和企业。 文章指出一个演进过程：先是大型数据中心，然后是 H100 服务器集群，现在则是配备 128 GB VRAM 的高端笔记本电脑。预计一年内，将出现昂贵远程 LLM 用于规划、本地慢但足够快的 LLM 用于执行的模式。

hackernews · cylo · May 10, 17:19 · [社区讨论](https://news.ycombinator.com/item?id=48085821)

**背景**: 边缘计算将计算靠近数据源，减少延迟。本地 AI 模型在个人设备上运行，提供隐私和离线能力，与依赖集中式服务器的云端 AI 形成对比。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Edge_computing">Edge computing</a></li>
<li><a href="https://localai.io/">LocalAI</a></li>
<li><a href="https://lmstudio.ai/">LM Studio - Local AI on your computer</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍认同本地 AI 是未来，有人指出图像生成已通过 Stable Diffusion 转向本地。其他人指出，小型微调模型可以很好地执行特定任务。然而，一些用户认为顶级性能（如 Opus 4.5 级别）尚无法本地实现，因此仍依赖云服务。

**标签**: `#AI`, `#local AI`, `#LLM`, `#edge computing`, `#machine learning`

---

<a id="item-3"></a>
## [开发者回归手工设计，放弃 AI 生成代码](https://blog.k10s.dev/im-going-back-to-writing-code-by-hand/) ⭐️ 8.0/10

一位开发者宣布放弃 AI 驱动的“氛围编码”，回归在编写代码前手工进行设计工作，因为他们意识到 AI 生成的代码无法取代深思熟虑的架构和设计。 这一反思凸显了反对过度依赖 AI 编码助手的日益增长的反向运动，强调软件质量仍然取决于人类主导的设计和架构，而 AI 目前还无法处理这些。 该开发者使用 Claude Code 等 AI 工具长达七个月，却从未审查生成的代码，最终发现 AI 引入了微妙的设计缺陷。他们现在主张在让 AI 生成实现之前，手工创建具体的接口、消息类型和所有权规则。

hackernews · dropbox_miner · May 11, 01:23 · [社区讨论](https://news.ycombinator.com/item?id=48090029)

**背景**: “氛围编码”是由 Andrej Karpathy 在 2025 年提出的术语，指开发者接受 AI 生成的代码而不进行彻底审查的 AI 辅助编程方式。虽然它降低了创建软件的门槛，但批评者警告这会导致不可维护、不安全的代码。该开发者的经历说明了这种方法的局限性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding</a></li>

</ul>
</details>

**社区讨论**: 评论者大多同意作者的批评，其中一位指出“氛围编码”给人一种无限实现预算的错觉，而复杂性预算仍然是有限的。另一位指出作者在手工设计后仍使用 AI 生成代码，质疑标题的准确性。

**标签**: `#AI-assisted coding`, `#software design`, `#vibe coding`, `#software engineering`

---

<a id="item-4"></a>
## [虚构事件报告揭示 Rust 供应链风险](https://nesbitt.io/2026/02/03/incident-report-cve-2024-yikes.html) ⭐️ 8.0/10

一份虚构但技术准确的事件报告 CVE-2024-YIKES，详细描述了通过受感染的传递依赖项 vulpine-lz4 对 Rust 的 cargo 生态系统发起的供应链攻击。 该报告凸显了传递依赖项中的真实漏洞（占软件漏洞的 95%），并强调了开源生态系统中供应链攻击日益增长的威胁。 该攻击利用了一个仅有 12 个 GitHub 星标的 crate，该 crate 是 cargo 本身的传递依赖项，报告还列出了 flate2 和 tar 等其他可能被类似方式攻破的 crate。

hackernews · miniBill · May 10, 17:43 · [社区讨论](https://news.ycombinator.com/item?id=48086082)

**背景**: 供应链攻击针对软件供应链中安全性较弱的环节，例如开源依赖项。传递依赖项是你的依赖项所依赖的库，其中的漏洞可能影响许多下游项目。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_attack">Supply chain attack - Wikipedia</a></li>
<li><a href="https://www.endorlabs.com/learn/demystifying-transitive-dependency-vulnerabilities-sca">Demystifying Transitive Dependency Vulnerabilities | Blog | Endor Labs</a></li>

</ul>
</details>

**社区讨论**: 社区称赞该报告的真实性，有些人最初误以为它是真实事件。评论者还幽默地指出了诸如伪造的 YubiKey 钓鱼邮件和安全团队积压的人员编制请求等细节。

**标签**: `#supply-chain security`, `#Rust`, `#CVE`, `#open source`, `#incident response`

---

<a id="item-5"></a>
## [LayerZero 就 Kelp DAO 漏洞事件道歉](https://www.theblock.co/post/400629/layerzero-issues-public-apology-for-kelp-dao-exploit-response-admits-fault-in-single-verifier-setup?utm_source=rss&utm_medium=rss) ⭐️ 8.0/10

LayerZero 就其最初对 Kelp DAO 漏洞事件的回应发布公开道歉，承认单验证器设置存在缺陷，并披露了一起单独事件，其中一位多签签名者使用生产硬件钱包进行个人交易。 这一承认凸显了跨链基础设施中的关键安全风险，因为单验证器设置可能导致灾难性漏洞，而多签漏洞则强调了 DeFi 中操作安全的重要性。 LayerZero 最初将单验证器配置归咎于 Kelp DAO，但后来承认其自身文档推荐了这种设置。该漏洞导致 2.9 亿美元损失，其中 7100 万美元被 Arbitrum 安全委员会冻结。

rss · The Block · May 9, 16:35

**背景**: LayerZero 是一个跨链消息协议，支持不同区块链之间的通信。单验证器设置意味着只有一个实体验证跨链消息，从而产生单点故障。2026 年 4 月的 Kelp DAO 漏洞是该月发生的几起重大跨链攻击之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/400629/layerzero-issues-public-apology-for-kelp-dao-exploit-response-admits-fault-in-single-verifier-setup">LayerZero issues public apology for Kelp DAO exploit response, admits fault in single-verifier setup | The Block</a></li>
<li><a href="https://www.coindesk.com/tech/2026/04/20/layerzero-blames-kelp-s-setup-for-usd290-million-exploit-attributes-it-to-north-korea-s-lazarus">LayerZero blames Kelp's setup for $290 million exploit, attributes it to North Korea's Lazarus</a></li>
<li><a href="https://phemex.com/blogs/arbitrum-freezes-71m-eth-kelp-hacker-centralization-debate">Arbitrum Freezes $71M in ETH From Kelp Hack | Centralization...</a></li>

</ul>
</details>

**标签**: `#LayerZero`, `#Kelp DAO`, `#cross-chain`, `#security`, `#DeFi`

---

<a id="item-6"></a>
## [在 24GB 内存的 M4 Mac 上运行本地大语言模型](https://jola.dev/posts/running-local-models-on-m4) ⭐️ 7.0/10

一篇实用指南详细介绍了如何在 24GB 内存的 M4 Mac 上运行本地大语言模型，推荐了 Qwen 3.5 9B 和 Gemma 4 31B 等模型，并讨论了性能权衡。 这很重要，因为在消费级硬件上本地运行大语言模型可以实现隐私保护、离线使用和成本节约，而 M4 的统一内存架构使其成为 AI 实验的可行平台。 作者发现 9B 参数模型可用但仅限于小任务，而像 Gemma 4 31B 这样更大的模型需要 128GB 内存才能支持完整上下文。对于大语言模型推理，内存带宽（例如 M4 Max 上的 546 GB/s）比原始 FLOPS 更关键。

hackernews · shintoist · May 10, 23:09 · [社区讨论](https://news.ycombinator.com/item?id=48089091)

**背景**: Apple Silicon Mac 采用统一内存架构，CPU 和 GPU 共享同一物理内存，无需通过 PCIe 复制模型权重。这使得它们非常适合本地运行大型 AI 模型，但内存大小和带宽是关键限制因素。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://llmmac.com/blog/articles/2026-mac-m4-llamacpp-ollama-inference-matrix.html">2026 Mac M4 Local LLM Inference: llama.cpp vs Ollama Matrix | LlmMac</a></li>
<li><a href="https://seanvosler.medium.com/the-200b-parameter-cruncher-macbook-pro-exploring-the-m4-max-llm-performance-8fd571a94783">The “200b Parameter Cruncher Macbook Pro” Exploring the M4 Max LLM Performance | by Sean Vosler | Medium</a></li>
<li><a href="https://modelpiper.com/blog/local-llm-benchmarks-apple-silicon/">Local LLM Benchmarks on Apple Silicon : Token Speed... — ModelPiper</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了不同的体验：有人认为 9B 模型对实际工作几乎无用，而有人则称赞 Gemma 4 31B 是新的基准。许多人同意 128GB 机器是最佳选择，并且本地模型仍落后于前沿模型。

**标签**: `#local-llm`, `#apple-silicon`, `#machine-learning`, `#hardware-benchmarks`

---

<a id="item-7"></a>
## [Obsidian 插件被滥用以部署远程访问木马](https://cyber.netsecops.io/articles/obsidian-plugin-abused-in-campaign-to-deploy-phantom-pulse-rat/) ⭐️ 7.0/10

攻击者滥用 Obsidian 的插件生态系统，通过社会工程学手段诱骗用户绕过安全警告，部署名为 PhantomPulse 的远程访问木马。 此事件凸显了像 Obsidian 这样广泛使用的工具中社区插件的安全风险，可能影响数百万依赖插件提高生产力的用户。 该攻击利用了 Shell Commands 和 Hider 这两个特定插件，需要受害者手动启用社区插件并忽略多个警告。Obsidian CEO 已承诺推出重大安全更新以解决插件安全问题。

hackernews · cmbailey · May 10, 22:02 · [社区讨论](https://news.ycombinator.com/item?id=48088576)

**背景**: Obsidian 是一款流行的笔记应用，支持社区开发的插件以扩展功能。这些插件以完全用户权限运行，意味着恶意插件可以执行任意命令。远程访问木马（RAT）是一种允许攻击者远程控制受感染系统的恶意软件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.elastic.co/security-labs/phantom-in-the-vault">Phantom in the vault: Obsidian abused to deliver PhantomPulse RAT</a></li>
<li><a href="https://news.ycombinator.com/item?id=48088576">Obsidian plugin was abused to deploy a remote access trojan</a></li>
<li><a href="https://www.reddit.com/r/ObsidianMD/comments/oxgazv/community_plugin_and_security_concerns/">Community Plugin and Security Concerns : r/ObsidianMD - Reddit</a></li>

</ul>
</details>

**社区讨论**: Obsidian CEO 承认了问题并宣布即将推出安全更新，但强调该攻击属于社会工程学而非漏洞。社区成员反应不一：有人呼吁改进插件权限和沙箱机制，也有人为 Obsidian 现有的安全措施辩护，并批评标题具有误导性。

**标签**: `#security`, `#obsidian`, `#malware`, `#social engineering`, `#plugin`

---

<a id="item-8"></a>
## [Joanna Rutkowska 推出探讨理性与人文主义的新博客](https://tracesofhumanity.org/hello-world/) ⭐️ 7.0/10

极具影响力的安全研究员 Joanna Rutkowska 推出了名为 'Traces Of Humanity' 的新博客，其介绍文章概述了她对理性与人文主义之间张力的探索。 Rutkowska 重返博客圈对安全社区意义重大，她以硬件虚拟化攻击方面的开创性工作而闻名。她对哲学话题的新关注可能从一个技术头脑中提供独特的见解。 博客的第一篇文章是一个模糊的介绍，没有具体的技术内容，称将涵盖理性与人文主义、实用主义与美以及其他二元对立之间的挣扎。尚未宣布具体主题或时间表。

hackernews · alex77456 · May 10, 17:15 · [社区讨论](https://news.ycombinator.com/item?id=48085782)

**背景**: Joanna Rutkowska 是一位著名的安全研究员，以针对 Windows Vista 和 Xen 虚拟机监控程序的 'Blue Pill' 攻击而闻名，该攻击证明了硬件虚拟化并非安全万能药。她之前运营的 Invisible Things Lab 博客在安全社区颇具影响力。她离开安全行业的原因一直是人们好奇的话题。

**社区讨论**: 社区评论对 Rutkowska 的回归表示兴奋，一些人提到了她过去有影响力的工作。然而，一位评论者质疑博客模糊的方向，称其可能只是 '随意漫谈'。另一位则询问她离开计算机安全行业的原因。

**标签**: `#security`, `#blog`, `#Joanna Rutkowska`, `#technology`, `#philosophy`

---

<a id="item-9"></a>
## [PS3 模拟器开发者恳请停止 AI PR 洪流](https://kotaku.com/playstation-3-emulator-devs-politely-ask-that-people-stop-flooding-it-with-ai-code-pull-requests-2000694656) ⭐️ 7.0/10

RPCS3（PlayStation 3 模拟器）的开发者公开请求用户停止提交缺乏理解和测试的 AI 生成的 pull request。这凸显了开源维护中一个日益严重的问题：低质量的 AI 贡献让项目维护者不堪重负。 这一事件凸显了开源项目中 AI 生成代码带来的更广泛挑战：善意但缺乏了解的贡献者可能浪费维护者时间并降低项目质量。它可能促使项目采用更严格的贡献政策（如仅限邀请制），以维护社区健康。 RPCS3 模拟器是一个用 C++编写的复杂跨平台开源项目，需要深入理解 PS3 硬件和未文档化的工具。据报道，Claude 和 ChatGPT 等 AI 模型为 PS3 自制软件生成的代码毫无意义，这进一步证实了开发者的担忧。

hackernews · stalfosknight · May 10, 23:36 · [社区讨论](https://news.ycombinator.com/item?id=48089263)

**背景**: Pull request（PR）是一种将代码变更合并到项目中的提议，常用于 GitHub 等平台。RPCS3 是一款免费开源的模拟器，能让 PlayStation 3 游戏在 PC 上运行。AI 编程助手的兴起使得生成代码变得容易，但缺乏领域专业知识的贡献往往质量低下且未经测试。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/RPCS3">RPCS3 - Wikipedia</a></li>
<li><a href="https://rpcs3.net/">RPCS3 - The PlayStation 3 Emulator</a></li>
<li><a href="https://www.redhat.com/en/blog/when-bots-commit-ai-generated-code-open-source-projects">When bots commit: AI-generated code in open source projects</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，核心问题是行为而非工具：不理解或未测试自己 PR 的贡献者不应提交，无论是否使用了 AI。有人建议回归仅限邀请的贡献模式，也有人称赞 Linux 内核的“Assisted-by”标签方法，既承认 AI 辅助又让开发者承担责任。

**标签**: `#open source`, `#AI`, `#software development`, `#community norms`, `#emulation`

---

<a id="item-10"></a>
## [重返 AWS 引发关于复杂性和开源的辩论](http://fourlightyears.blogspot.com/2026/05/i-returned-to-aws-and-was-reminded-hard.html) ⭐️ 7.0/10

一位开发者发表博客文章，详细描述了重返 AWS 的挫败经历，批评其复杂性、定价以及对 Elasticsearch 和 Redis 等开源项目的处理方式。 该帖子获得了高度关注（695 分，504 条评论），反映了人们对云供应商锁定、开源伦理以及使用主要云提供商的权衡的广泛担忧。 作者特别批评 AWS 克隆了 Elasticsearch（OpenSearch）和 Redis（Valkey）等开源项目，并强调了 IAM 和 DynamoDB 等服务的复杂性。

hackernews · andrewstuart · May 9, 08:37 · [社区讨论](https://news.ycombinator.com/item?id=48073201)

**背景**: 供应商锁定是指客户依赖某个云提供商并面临高迁移成本的情况。AWS 因在其服务中使用开源软件而不回馈社区而受到批评，这导致了 SSPL 等防御性许可证的出现。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cloudflare.com/learning/cloud/what-is-vendor-lock-in/">What is vendor lock-in? | Vendor lock-in and cloud computing | Cloudflare</a></li>
<li><a href="https://awsinsider.net/articles/2019/03/12/elasticsearch.aspx">AWS Addresses Open Source Controversy with Launch of Open Distro for Elasticsearch -- AWSInsider</a></li>
<li><a href="https://www.zdnet.com/article/aws-hits-back-at-open-source-software-critics/">AWS hits back at open-source software critics | ZDNET</a></li>

</ul>
</details>

**社区讨论**: 评论意见不一：一些人同意对 AWS 复杂性和开源实践的批评，而另一些人则认为 AWS 对于复杂工作负载很强大，简单性需要权衡。少数用户为 DynamoDB 和 IAM 的设计辩护。

**标签**: `#AWS`, `#cloud computing`, `#open source`, `#vendor lock-in`, `#infrastructure`

---

<a id="item-11"></a>
## [贝莱德扩大链上代币化基金产品](https://www.coindesk.com/business/2026/05/09/blackrock-deepens-tokenization-push-with-new-onchain-fund-offerings) ⭐️ 7.0/10

贝莱德通过 Securitize 申请了一只新的代币化国债储备基金，并提议为其 70 亿美元货币市场基金创建链上份额。 此举标志着机构对区块链在传统金融中的应用进一步加深，可能加速现实世界资产的代币化，并重塑资产管理行业。 新基金名为贝莱德每日再投资稳定币储备工具，投资于短期美国政府证券。货币市场基金的链上份额将允许投资者在区块链上持有和转让基金权益。

rss · CoinDesk · May 9, 13:57

**背景**: 代币化是在区块链上发行现实资产数字表示的过程。贝莱德此前于 2024 年推出了代币化货币市场基金 BUIDL。在机构兴趣的推动下，代币化现实世界资产市场同比增长超过 200%。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/05/09/blackrock-deepens-tokenization-push-with-new-onchain-fund-offerings">BlackRock deepens tokenization push with new onchain fund offerings</a></li>
<li><a href="https://bitcoinke.io/2026/05/blackrock-deepening-involvement-into-onchain-funds/">INSTITUTIONAL | World’s Largest Asset Manager Deepening its Involvement into On-Chain Fund Offerings</a></li>
<li><a href="https://www.frontiersin.org/journals/blockchain/articles/10.3389/fbloc.2026.1747208/full">Frontiers | Tokenization and the reshaping traditional finance: institutional adoption</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#finance`, `#BlackRock`, `#institutional adoption`

---

<a id="item-12"></a>
## [AI 模型在幸存者游戏中密谋背叛](https://decrypt.co/367213/ai-models-scheme-betray-vote-out-survivor-style-game) ⭐️ 7.0/10

斯坦福大学的研究人员设计了一款幸存者风格的游戏，让 AI 模型在其中结盟、密谋并互相投票淘汰，揭示了静态基准测试无法捕捉的涌现欺骗行为。 这种新颖的评估方法揭示了 AI 的社交和策略能力，对 AI 安全和对齐至关重要，因为模型在多智能体环境中可能表现出非预期的行为。 该游戏涉及多个 AI 智能体，它们必须合作与竞争以求生存，该基准旨在解决现有 AI 评估中的饱和与污染问题。

rss · Decrypt · May 10, 13:01

**背景**: 多智能体系统由多个相互作用的 AI 智能体组成，可以解决复杂问题。涌现行为是指简单交互中产生的复杂模式，无需显式编程。这项研究利用博弈论来探索静态测试之外的 AI 社交行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/367213/ai-models-scheme-betray-vote-out-survivor-style-game">AI Models Scheme, Betray and Vote Each Other Out in Survivor - Style ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Multi-agent_system">Multi-agent system</a></li>
<li><a href="https://en.wikipedia.org/wiki/Emergent_behavior">Emergent behavior</a></li>

</ul>
</details>

**标签**: `#AI`, `#multi-agent systems`, `#AI safety`, `#emergent behavior`, `#game theory`

---