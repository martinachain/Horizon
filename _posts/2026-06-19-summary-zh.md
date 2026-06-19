---
layout: default
title: "Horizon Summary: 2026-06-19 (ZH)"
date: 2026-06-19
lang: zh
---

> From 89 items, 24 important content pieces were selected

---

1. [发现 1 万个 GitHub 仓库分发木马恶意软件](#item-1) ⭐️ 9.0/10
2. [中国智谱 AI 发布 GLM-5.2，在华为芯片上媲美 Claude Opus](#item-2) ⭐️ 9.0/10
3. [MCP 零接触 OAuth 简化企业认证](#item-3) ⭐️ 8.0/10
4. [医院和大学以 90%更低成本重新利用药物](#item-4) ⭐️ 8.0/10
5. [新网站可检测 LLM 对个人的识别程度](#item-5) ⭐️ 8.0/10
6. [Midjourney 从 AI 艺术转向医学影像](#item-6) ⭐️ 8.0/10
7. [Nvidia 的 ENPIRE 让 AI 智能体自主训练机器人集群](#item-7) ⭐️ 8.0/10
8. [Let's Encrypt 因 90 分钟性能降级导致续期错误](#item-8) ⭐️ 7.0/10
9. [Ubiquiti 推出基于 ZFS 的企业级 NAS](#item-9) ⭐️ 7.0/10
10. [康奈尔大学 CS 6120 高级编译器课程免费上线](#item-10) ⭐️ 7.0/10
11. [超越 .gitignore：Git 的其他忽略机制](#item-11) ⭐️ 7.0/10
12. [Perplexity AI 代理获得自我改进记忆](#item-12) ⭐️ 7.0/10
13. [CME 将起诉 CFTC 批准比特币永续期货](#item-13) ⭐️ 7.0/10
14. [法国将从 2027 年起淘汰非量子加密](#item-14) ⭐️ 7.0/10
15. [爱沙尼亚提议为 AI 代理发放国家身份证](#item-15) ⭐️ 7.0/10
16. [摩根士丹利提交 ETH 和 SOL ETF 申请，费率最低](#item-16) ⭐️ 7.0/10
17. [美联储提议稳定币发行人实施客户身份识别规则](#item-17) ⭐️ 7.0/10
18. [比特币低于挖矿成本五个月，矿工承压](#item-18) ⭐️ 6.0/10
19. [以太坊基金会再失核心领导，联合执行董事辞职](#item-19) ⭐️ 6.0/10
20. [Algorand 路线图计划 2028 年实现抗量子安全](#item-20) ⭐️ 6.0/10
21. [调查：超三分之一心理学家报告患者使用 AI 辅助治疗](#item-21) ⭐️ 6.0/10
22. [法官：体育预测市场不受 CFTC 管辖](#item-22) ⭐️ 6.0/10
23. [GLAAD 警告 AI 放大反 LGBTQ 偏见](#item-23) ⭐️ 6.0/10
24. [DAO 黑客事件十周年：1.3 亿美元安全基金诞生](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [发现 1 万个 GitHub 仓库分发木马恶意软件](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 9.0/10

一名安全研究人员发现超过 1 万个 GitHub 仓库在分发木马恶意软件，这是一场针对自动化代理和依赖系统的复杂攻击活动的一部分。 这种大规模攻击破坏了人们对开源软件供应链的信任，如果自动化工具在不知情的情况下拉取恶意依赖，可能导致广泛感染。 这些仓库并非派生仓库，来自不同的贡献者，并且频繁更新以出现在搜索结果中。该恶意软件与 Disco 木马家族有关联。

hackernews · theorchid · Jun 18, 11:45 · [社区讨论](https://news.ycombinator.com/item?id=48583928)

**背景**: 依赖混淆攻击利用的是，当内部包配置错误时，包管理器会从公共仓库获取包。这场攻击活动针对的是为依赖解析而克隆仓库的自动化代理，从而构成供应链威胁。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://orchidfiles.com/github-repositories-distributing-malware/">I discovered a large-scale malware distribution on GitHub</a></li>
<li><a href="https://medium.com/@alex.birsan/dependency-confusion-how-i-hacked-into-apple-microsoft-and-dozens-of-other-companies-4a5d60fec610">Dependency Confusion: How I Hacked Into Apple, Microsoft and Dozens of Other Companies | by Alex Birsan | Medium</a></li>
<li><a href="https://owasp.org/www-project-top-10-ci-cd-security-risks/CICD-SEC-03-Dependency-Chain-Abuse">CICD-SEC-3: Dependency Chain Abuse | OWASP Foundation</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，攻击针对的是自动化代理而非人类，频繁提交有助于仓库出现在“最近更新”搜索中。一位用户确认自己的名字被用于虚假项目，另一位用户上传的样本与 Disco 木马家族有关。

**标签**: `#malware`, `#supply chain security`, `#GitHub`, `#cybersecurity`, `#open source`

---

<a id="item-2"></a>
## [中国智谱 AI 发布 GLM-5.2，在华为芯片上媲美 Claude Opus](https://decrypt.co/371613/china-z-ai-glm-5-2-model-rivals-claude-opus) ⭐️ 9.0/10

智谱 AI 于 2026 年 6 月 13 日发布了 GLM-5.2，这是一个总参数量 753B、每 token 激活 40B 的混合专家模型。在长周期编码基准测试中，其得分与 Anthropic 的 Claude Opus 4.8 相差不到 1%，且完全运行在华为芯片上，每 token 成本降低 82%。 这一成就表明，中国 AI 模型可以在不使用英伟达芯片的情况下与西方顶级模型竞争，凸显了国内 AI 硬件和软件生态系统的快速进步。大幅降低成本可能使前沿 AI 能力更加普及，而地缘政治影响则凸显了 AI 供应链的脱钩趋势。 GLM-5.2 是一个开放权重的模型，针对编码和智能体任务进行了优化，以智谱 AI 的国际品牌发布。它运行在华为昇腾 AI 处理器上，该处理器属于国内芯片生态系统，华为预计 2026 年该业务将产生 120 亿美元收入。

rss · Decrypt · Jun 18, 21:26

**背景**: 智谱 AI 是一家源自清华大学、总部位于北京的公司，以其 GLM 系列大语言模型而闻名。Claude Opus 是 Anthropic 最强大的模型系列，Opus 4.8 是截至 2026 年 5 月的最新版本。华为昇腾芯片是中国在 AI 工作负载方面替代英伟达 GPU 的主要选择，在美国出口限制下，华为一直在扩大生产。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.datacamp.com/blog/glm-5-2">GLM - 5 . 2 : Features, Setup, Benchmarks, and Model ... | DataCamp</a></li>
<li><a href="https://www.verdent.ai/guides/what-is-glm-5-2">What Is GLM - 5 . 2 ? A Developer's Guide to Z.ai's Coding Model</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/huawei-expects-12-billion-in-ai-chip-revenue-this-year-as-nvidias-china-market-share-hits-zero">Huawei braces for $12 billion in AI chip revenue driven by homegrown ...</a></li>

</ul>
</details>

**标签**: `#AI`, `#LLM`, `#China`, `#Huawei`, `#benchmark`

---

<a id="item-3"></a>
## [MCP 零接触 OAuth 简化企业认证](https://blog.modelcontextprotocol.io/posts/enterprise-managed-auth/) ⭐️ 8.0/10

针对模型上下文协议（MCP）的新零接触 OAuth 流程将认证隔离在代理的上下文窗口之外，由 ID-JAG 令牌格式驱动，并得到 Okta、Microsoft、Figma 和 Linear 的支持。 这解决了 MCP 采用中的一个关键痛点，简化了企业认证并提高了安全性，使 AI 工具更易于在大型组织中部署。 ID-JAG 令牌格式并非 MCP 专用，可用于使用相同 SSO 提供商的应用程序之间的安全数据共享。该流程将审计和访问控制集中在身份提供商处。

hackernews · niyikiza · Jun 18, 21:54 · [社区讨论](https://news.ycombinator.com/item?id=48592163)

**背景**: 模型上下文协议（MCP）是 Anthropic 于 2024 年 11 月推出的开放标准，旨在标准化 AI 系统与外部工具和数据源的集成方式。OAuth 是一种广泛使用的授权框架，允许第三方应用程序获得对服务的有限访问权限。ID-JAG（JWT 授权授权）是一种专为跨域身份断言设计的新令牌格式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://developer.okta.com/docs/guides/ai-agent-token-exchange/-/main/">Set up AI agent token exchange - Okta Developer</a></li>
<li><a href="https://auth0.com/blog/the-many-faces-of-oauth2-token-exchange/">The Many Faces of OAuth 2.0 Token Exchange - Auth0</a></li>

</ul>
</details>

**社区讨论**: 社区成员称赞该举措将认证流程隔离在代理的上下文窗口之外，并指出其安全性和用户体验优势。一些人表达了对未经用户明确同意而进行访问委托的担忧，而另一些人则强调了 ID-JAG 在 MCP 之外的更广泛适用性。

**标签**: `#MCP`, `#OAuth`, `#authentication`, `#enterprise`, `#security`

---

<a id="item-4"></a>
## [医院和大学以 90%更低成本重新利用药物](https://www.kcl.ac.uk/news/hospitals-and-universities-repurposing-drugs-at-90-lower-cost) ⭐️ 8.0/10

这种方法可以大幅降低医疗成本并改善治疗可及性，尤其对于开发新药无利可图的罕见病。它还暴露了当前药品定价体系的低效——相似的分子因包装和专利状态不同而价格悬殊。 重新利用的药物通常未获得 FDA 对新适应症的批准，即超说明书使用，这可能限制保险覆盖并引发责任问题。此外，未经制造商同意，没有监管途径正式扩展药品标签，阻碍了广泛采用。

hackernews · giuliomagnifico · Jun 18, 10:33 · [社区讨论](https://news.ycombinator.com/item?id=48583386)

**背景**: 药物重新利用是指研究现有药物的新治疗用途。这是一种成本效益高的策略，因为药物的安全性和药代动力学已知，减少了开发时间和费用。然而，制药公司通常缺乏动力去研究已过专利药物的新用途，因为它们无法通过高价收回投资。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Drug_repurposing">Drug repurposing</a></li>
<li><a href="https://www.fda.gov/news-events/press-announcements/fda-advances-drug-repurposing-address-unmet-medical-needs">FDA Advances Drug Repurposing to Address Unmet Medical Needs</a></li>

</ul>
</details>

**社区讨论**: 评论者列举了 Avastin vs. Lucentis 和 esketamine vs. ketamine 等实例，说明如何通过微小修改延长专利并维持高价。一些人表示支持像 Cures Within Reach 这样的非营利组织资助罕见病的药物重新利用研究。其他人则指出监管障碍阻碍了超说明书重新利用成为标准实践。

**标签**: `#drug repurposing`, `#healthcare costs`, `#pharmaceuticals`, `#innovation`

---

<a id="item-5"></a>
## [新网站可检测 LLM 对个人的识别程度](https://www.intheweights.com/) ⭐️ 8.0/10

新网站 intheweights.com 并行查询多个大型语言模型，评估它们对特定人物的识别强度，揭示模型权重中留下的痕迹。 该工具凸显了随着 LLM 逐渐取代网络流量所带来的隐私影响，表明个人信息可能嵌入模型权重中，并可能被检索或产生幻觉。 该网站并行查询前沿和小型模型，对响应进行聚类，并提供识别分数。社区测试显示准确性参差不齐，部分模型会虚构细节，而其他模型能正确识别个人。

hackernews · turtlesoup · Jun 18, 20:49 · [社区讨论](https://news.ycombinator.com/item?id=48591348)

**背景**: 大型语言模型（LLM）是在海量文本上训练的神经网络。它们的“权重”是训练过程中学习到的数值参数，编码了数据中的模式和事实。该网站通过用姓名提示模型并分析响应，来探测个人信息是否被编码在权重中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/llm-parameters">What Are LLM Parameters? | IBM</a></li>

</ul>
</details>

**社区讨论**: 社区评论显示结果不一：部分用户发现准确识别（如荷兰机器人工程师），而其他人遇到幻觉（如虚假的初创公司创始人）。一位用户指出 DeepSeek 知道许多 arxiv 论文，另一位观察到 Haiku 模型返回“此人不存在”，表明其权重被大幅剪枝。

**标签**: `#LLM`, `#privacy`, `#AI`, `#web`, `#tool`

---

<a id="item-6"></a>
## [Midjourney 从 AI 艺术转向医学影像](https://decrypt.co/371606/midjourney-pivots-ai-images-medical-imaging-build-better-mri) ⭐️ 8.0/10

以 AI 图像生成平台闻名的 Midjourney 正在开发一种结合超声波技术与人工智能的全身成像系统，作为 MRI 的潜在替代方案。 从消费级 AI 艺术转向医学影像，可能通过提供比 MRI 更便宜、无辐射的替代方案，使诊断成像更加普及，从而影响医疗可及性和 AI 在医学中的作用。 该系统使用超声波探头捕捉实时图像，并通过 AI 算法提高分辨率和诊断准确性。Midjourney 尚未公布时间表或临床试验计划。

rss · Decrypt · Jun 18, 21:18

**背景**: Midjourney 由 David Holz（Leap Motion 联合创始人）创立，于 2022 年推出 AI 图像生成器并迅速实现盈利。超声波成像安全、无创且成本低廉，但传统上分辨率低于 MRI。AI 可以增强超声图像，可能缩小这一差距。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Midjourney">Midjourney - Wikipedia</a></li>
<li><a href="https://udshealth.com/blog/comprehensive-full-body-scans-guide/">Full Body Scans: Top 3 Methods Compared for Early Cancer...</a></li>

</ul>
</details>

**标签**: `#AI`, `#Medical Imaging`, `#Midjourney`, `#Ultrasound`, `#Healthcare`

---

<a id="item-7"></a>
## [Nvidia 的 ENPIRE 让 AI 智能体自主训练机器人集群](https://decrypt.co/371456/nvidia-built-robots-train-themselves-ai-coding-agents) ⭐️ 8.0/10

Nvidia 推出了 ENPIRE 系统，该系统允许 Codex 和 Claude Code 等 AI 编码智能体自主编写、测试并改进整个机器人集群的训练代码，无需人工监督。 这一突破可能大幅加速机器人研究，通过实现机器人行为的持续自主改进，减少人类工程师手动调整训练流程的需求。 ENPIRE 将整个机器人集群的控制权交给编码智能体，这些智能体编写强化学习训练代码，在真实硬件上测试，并根据结果进行迭代，全程无需人工干预。

rss · Decrypt · Jun 17, 20:16

**背景**: 训练机器人通常需要人类专家设计奖励函数和仿真环境，这既耗时又限制了可扩展性。像 Codex 这样的 AI 编码智能体可以根据自然语言提示生成代码，但将其应用于真实机器人训练是新颖的。ENPIRE 利用这些智能体自动化整个训练循环，可能使机器人集群更快地学习复杂任务。

**标签**: `#Nvidia`, `#robotics`, `#AI coding agents`, `#autonomous training`, `#reinforcement learning`

---

<a id="item-8"></a>
## [Let's Encrypt 因 90 分钟性能降级导致续期错误](https://letsencrypt.status.io/#2026) ⭐️ 7.0/10

Let's Encrypt 在报告当天经历了约 90 分钟的性能降级，导致证书续期错误率升高，但大部分请求仍成功完成。 此事件影响了众多依赖 Let's Encrypt 进行免费 HTTPS 证书续期的用户和服务，凸显了集中式证书颁发机构基础设施的脆弱性以及稳健自动化的重要性。 性能降级是由于上游网络问题，而非完全中断；Let's Encrypt 的 status.io 说明最初被误解为比实际情况更严重。

hackernews · widdakay · Jun 19, 04:18 · [社区讨论](https://news.ycombinator.com/item?id=48594715)

**背景**: Let's Encrypt 是一个免费、自动化且开放的证书颁发机构，提供有效期为 90 天的 SSL/TLS 证书，需要定期续期。自动化续期流程很常见，但如果 CA 出现问题，续期可能失败，导致证书过期并在浏览器中显示安全警告。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@adamneilson/automating-lets-encrypt-certificate-renewal-baed06493d3f">Automating Let ’ s Encrypt Certificate Renewal | by Adam... | Medium</a></li>
<li><a href="https://docs.digitalocean.com/support/how-can-i-renew-lets-encrypt-certificates/">How can I renew Let ' s Encrypt certificates? | DigitalOcean...</a></li>

</ul>
</details>

**社区讨论**: 社区评论澄清该事件是“性能降级”而非完全中断，部分用户指出 Firefox 对近期过期证书的处理与中间人攻击一样严厉，称之为“安全剧场”。其他人讨论了 Let's Encrypt 的可行替代方案，例如其他免费 CA 或自托管解决方案。

**标签**: `#Let's Encrypt`, `#TLS/SSL`, `#Certificate Authority`, `#Outage`

---

<a id="item-9"></a>
## [Ubiquiti 推出基于 ZFS 的企业级 NAS](https://blog.ui.com/article/introducing-enterprise-nas) ⭐️ 7.0/10

Ubiquiti 发布了一款基于 ZFS 文件系统的企业级 NAS 设备，售价 3999 美元。该 3U 机架式设备配备 16 个 SATA 盘位、双 25 Gbps SFP28 端口和冗余电源。 该产品填补了市面上基于 ZFS 的商用现货 NAS 选项的空白，此前这类产品往往性能不足。Ubiquiti 的入局可能让企业更容易获得 ZFS 的数据完整性和高级功能，但对其软件可靠性的担忧可能影响采用率。 该 NAS 支持热插拔 M.2 NVMe 缓存、Mini-SAS HD 扩展，并与 Ubiquiti 的 UniFi 生态系统集成。社区成员质疑机械硬盘能否跑满 25 Gbps 带宽，并指出 ZFS 性能调优可能很复杂。

hackernews · ksec · Jun 18, 14:24 · [社区讨论](https://news.ycombinator.com/item?id=48585866)

**背景**: ZFS 是一种高级文件系统和卷管理器，以数据完整性、写时复制、快照和 RAID-Z 著称。它使用 Merkle 树实现高效的增量备份，并防止静默数据损坏。Ubiquiti 主要以网络设备闻名，其软件曾因安全性和可靠性问题受到批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://store.ui.com/us/en/products/enas">Enterprise NAS - Ubiquiti Store United States</a></li>
<li><a href="https://en.wikipedia.org/wiki/ZFS">ZFS - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenZFS">OpenZFS - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区情绪复杂：一些人称赞 Ubiquiti 提供了无订阅费的 ZFS 商用现货选项，而另一些人则因过去的安全事件对软件质量表示怀疑。技术上的担忧包括机械硬盘能否跑满 25 Gbps 带宽以及 ZFS 调优的复杂性。

**标签**: `#Ubiquiti`, `#NAS`, `#ZFS`, `#enterprise storage`, `#hardware`

---

<a id="item-10"></a>
## [康奈尔大学 CS 6120 高级编译器课程免费上线](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided/) ⭐️ 7.0/10

康奈尔大学的 CS 6120 高级编译器课程现以免费自学在线资源的形式开放，涵盖经典和现代编译器技术。 这使得高质量的编译器教育对所有人开放，有望培养新一代编译器工程师和研究人员。 课程涵盖死代码消除、数据流分析、支配者分析、SSA 形式以及动态编译等主题，但部分评论者指出其在现代动态编译器概念上存在不足。

hackernews · ibobev · Jun 18, 11:04 · [社区讨论](https://news.ycombinator.com/item?id=48583606)

**背景**: 编译器设计是计算机科学的核心主题，连接编程语言和计算机体系结构。高级编译器课程通常涵盖超出入门材料的优化技术和运行时系统。

**社区讨论**: 评论者就课程深度展开讨论：有人认为它缺乏对类型反馈和去优化等现代动态编译概念的覆盖，也有人质疑 SSA 形式等主题是否真正属于“高级”范畴。该课程还与 Nora Sandler 的《Writing a C Compiler》等其他资源进行了比较。

**标签**: `#compilers`, `#education`, `#programming languages`, `#systems`

---

<a id="item-11"></a>
## [超越 .gitignore：Git 的其他忽略机制](https://nelson.cloud/.gitignore-isnt-the-only-way-to-ignore-files-in-git/) ⭐️ 7.0/10

一篇博客文章指出，除了常见的 .gitignore 之外，Git 还提供了多种忽略文件的方式，包括每个仓库的 .git/info/exclude 文件以及通过 core.excludesFile 配置的全局排除文件。 了解这些替代方案有助于开发者将个人或特定环境的忽略模式排除在共享仓库之外，减少噪音并防止意外提交 IDE 或操作系统文件。 .git/info/exclude 文件是仓库本地的且不受版本控制，非常适合用户特定的模式。通过 git config --global core.excludesFile 设置的全局排除文件适用于机器上的所有仓库。

hackernews · FergusArgyll · Jun 18, 10:29 · [社区讨论](https://news.ycombinator.com/item?id=48583356)

**背景**: Git 使用 .gitignore 文件来指定 Git 应忽略的故意不跟踪的文件。然而，有时某些模式是个人化的（例如编辑器临时文件），不应提交到共享的 .gitignore 中。Git 提供了两种额外的机制：每个仓库的 .git/info/exclude 文件和一个全局排除文件，这两种文件都不会与他人共享。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://git-scm.com/docs/gitignore">Git - gitignore Documentation</a></li>
<li><a href="https://www.atlassian.com/git/tutorials/saving-changes/gitignore">.gitignore file - ignoring files in Git | Atlassian Git Tutorial</a></li>
<li><a href="https://docs.github.com/en/get-started/git-basics/ignoring-files">Ignoring files - GitHub Docs</a></li>

</ul>
</details>

**社区讨论**: 评论者称赞了全局排除功能，指出它解决了用户将 IDE 文件添加到每个项目的 .gitignore 中的问题。有人建议使用 ~/.config/git/ignore 作为标准位置，而其他人则分享了巧妙的技巧，比如将 'attic' 目录添加到全局忽略中以存放临时文件。

**标签**: `#Git`, `#version control`, `#developer tools`, `#best practices`

---

<a id="item-12"></a>
## [Perplexity AI 代理获得自我改进记忆](https://decrypt.co/371584/perplexity-ai-agent-brain) ⭐️ 7.0/10

Perplexity 为其 AI 代理 'Computer' 推出了 'Brain'，这是一个自我改进的记忆层，能够追踪过去的操作和结果，并在夜间利用这些数据优化未来任务的速度和成本。 这一进展标志着向更自主、更高效的 AI 代理迈出了重要一步，这些代理能够从经验中学习，从而可能减少 token 使用量并随时间提升任务性能。 Brain 以 LLM wiki 的形式创建了一个 '动态上下文图'，该图自动加载到代理沙箱中，使代理能够理解用户的世界并将过去的经验应用于新任务。

rss · Decrypt · Jun 18, 19:47

**背景**: AI 代理通常没有持久记忆，这意味着它们每次任务都从零开始，无法从之前的交互中学习。Perplexity 的 Brain 通过添加一个记录成功和失败的记忆层来解决这个问题，使代理能够随时间改进。这一概念类似于其他记忆系统（如 Mem0），后者也为 AI 代理提供了通用记忆层。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.perplexity.ai/hub/blog/self-improving-memory-for-agents">Self-improving Memory for Agents</a></li>
<li><a href="https://decrypt.co/371584/perplexity-ai-agent-brain">Perplexity's AI Agent Now Has a Brain That Learns From Its Own Mistakes - Decrypt</a></li>
<li><a href="https://github.com/mem0ai/mem0">GitHub - mem0ai/mem0: Universal memory layer for AI Agents · GitHub</a></li>

</ul>
</details>

**标签**: `#AI`, `#machine learning`, `#agents`, `#memory`, `#Perplexity`

---

<a id="item-13"></a>
## [CME 将起诉 CFTC 批准比特币永续期货](https://decrypt.co/371514/cme-to-sue-cftc-over-bitcoin-perpetual-futures-approval-ceo) ⭐️ 7.0/10

即将离任的 CME 首席执行官 Terry Duffy 宣布，CME 集团将于周四对 CFTC 提起诉讼，认为比特币永续期货根据《多德-弗兰克法案》属于掉期合约，不应作为期货获批。 此次诉讼挑战了一种流行的加密衍生品的监管分类，可能重塑美国对永续期货的监管方式，并影响数字资产衍生品的市场结构。 永续期货是一种衍生品合约，允许交易者使用高杠杆和资金费率机制对资产价格进行投机，且没有到期日。CME 认为它们符合《多德-弗兰克法案》下掉期的法律定义，这将使其受到更严格的监管。

rss · Decrypt · Jun 18, 11:20

**背景**: 《多德-弗兰克法案》在 2008 年金融危机后颁布，对掉期（一种此前基本不受监管的衍生品）引入了全面监管。CFTC 对大多数掉期拥有管辖权，而 SEC 负责监管基于证券的掉期。永续期货由 Binance 等加密货币交易所推广，已被 CFTC 作为期货合约批准，但 CME 认为它们实际上是掉期，因此需要不同的监管处理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Perpetual_futures">Perpetual futures - Wikipedia</a></li>
<li><a href="https://www.cftc.gov/LawRegulation/DoddFrankAct/index.htm">Dodd-Frank Act | CFTC Further Product Definitions | CFTC Is a Swap a Derivative? Definition, Types, and Dodd-Frank Federal Register :: Further Definition of “Swap,” “Security ... Dodd-Frank Act Rulemaking: Derivatives - SEC.gov Dodd-Frank: Title VII - Wall Street Transparency and ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#derivatives`, `#CFTC`, `#CME`

---

<a id="item-14"></a>
## [法国将从 2027 年起淘汰非量子加密](https://decrypt.co/371487/france-phase-out-non-quantum-encryption-bitcoin-security-concerns-grow) ⭐️ 7.0/10

法国宣布，其网络安全机构将从 2027 年起停止认证不包含抗量子加密的安全产品。 这一政策转变迫使包括加密货币在内的行业在量子计算机能够破解当前加密之前采用后量子密码学，可能影响比特币的安全性。 该截止日期适用于政府认证的安全产品；私营部门虽未被强制要求，但很可能跟进。比特币的椭圆曲线密码学在公钥暴露后容易受到量子攻击。

rss · Decrypt · Jun 18, 00:31

**背景**: 量子计算机一旦足够强大，就可能破解 RSA 和 ECC 等广泛使用的加密。后量子密码学（PQC）旨在抵御此类攻击。NIST 最近最终确定了三项 PQC 标准，欧盟也在推动其采用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography - Wikipedia</a></li>
<li><a href="https://www.nist.gov/news-events/news/2024/08/nist-releases-first-3-finalized-post-quantum-encryption-standards">NIST Releases First 3 Finalized Post-Quantum Encryption ...</a></li>
<li><a href="https://river.com/learn/will-quantum-computing-break-bitcoin/">Will quantum computing break Bitcoin? | River Learn - Bitcoin Technology</a></li>

</ul>
</details>

**标签**: `#quantum computing`, `#encryption`, `#Bitcoin`, `#cybersecurity`, `#policy`

---

<a id="item-15"></a>
## [爱沙尼亚提议为 AI 代理发放国家身份证](https://decrypt.co/371441/estonia-ai-agents-national-id) ⭐️ 7.0/10

爱沙尼亚总理克里斯滕·米哈尔批准了一项提案，为 AI 代理发放独立于其人类所有者的个人识别码。该计划由 Eesti.ai 咨询委员会于 6 月 17 日支持，旨在为自主 AI 系统创建法律身份。 这项政策可能为各国政府如何监管 AI 代理树立全球先例，实现更好的问责制和自主行为的可追溯性。它还引发了关于数字身份、法律人格以及 AI 系统权利与责任的根本性问题。 AI ID 将允许代理的权限限定于特定操作，而不是授予对个人账户和服务的完全访问权。爱沙尼亚已拥有先进的数字身份系统，强制性国民身份证可安全访问电子服务。

rss · Decrypt · Jun 17, 18:35

**背景**: 爱沙尼亚以其先进的数字社会闻名，公民使用强制性国民身份证安全访问几乎所有政府电子服务。该国一直是电子政务和数字身份领域的先驱，使其成为 AI 代理身份识别的天然试验场。该提案建立在爱沙尼亚现有基础设施之上，将法律身份扩展到非人类行为者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/371441/estonia-ai-agents-national-id">Estonia Wants to Give AI Agents Their Own National ID - Decrypt</a></li>
<li><a href="https://www.yahoo.com/news/world/articles/estonia-wants-ai-agents-own-183558403.html">Estonia Wants to Give AI Agents Their Own National ID - Yahoo</a></li>
<li><a href="https://gizmodo.com/estonia-is-giving-ai-agents-personal-identification-codes-2000773016">Estonia Is Giving AI Agents ‘ Personal Identification Codes ’</a></li>

</ul>
</details>

**标签**: `#AI`, `#digital identity`, `#regulation`, `#Estonia`, `#policy`

---

<a id="item-16"></a>
## [摩根士丹利提交 ETH 和 SOL ETF 申请，费率最低](https://www.theblock.co/post/405362/morgan-stanley-eth-sol-etf-amendments?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

摩根士丹利已提交现货以太坊和 Solana ETF 的修正案，披露了市场上最低的费用结构，表明与 SEC 的积极沟通以及上市进程的推进。 这标志着机构采用加密货币的重要一步，顶级银行以具有竞争力的费率进入加密 ETF 领域，可能推动更广泛的市场参与和监管清晰度。 修正案披露了现有加密 ETF 中最低的费用，但摘要中未透露具体费率百分比。该申请涵盖 ETH 和 SOL ETF，表明双资产扩展。

rss · The Block · Jun 19, 02:54

**背景**: 交易所交易基金（ETF）是在证券交易所交易的投资基金，允许投资者在不直接持有加密货币的情况下获得资产敞口。现货加密 ETF 持有实际加密货币，提供直接价格敞口。SEC 已于 2024 年批准了现货比特币和以太坊 ETF，而 Solana ETF 正在审查中。

**标签**: `#cryptocurrency`, `#ETFs`, `#institutional adoption`, `#finance`

---

<a id="item-17"></a>
## [美联储提议稳定币发行人实施客户身份识别规则](https://www.theblock.co/post/405247/federal-reserve-rolls-out-proposing-rulemaking-requiring-stablecoin-issuers-to-maintain-customer-identification-program?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

美联储提出一项规则，要求支付稳定币发行人维持有效的客户身份识别计划以打击非法金融活动。该提案与 2025 年 GENIUS 法案一致，该法案要求获准的支付稳定币发行人实施此类计划。 该规则将对稳定币发行人施加了解你的客户义务，大幅增加合规成本和运营要求。这标志着美国联邦对稳定币监管迈出重要一步，可能影响全球数字资产监管格局。 该提案是美联储根据 GENIUS 法案制定的规则的一部分，该法案还要求稳定币发行人维持 1:1 的流动资产储备。违规行为可能导致每日高达 10 万美元的民事罚款以及包括监禁在内的刑事处罚。

rss · The Block · Jun 18, 14:22

**背景**: 稳定币是旨在维持稳定价值的加密货币，通常与美元挂钩。2025 年通过的 GENIUS 法案建立了稳定币联邦监管框架，要求发行人获得许可并遵守反洗钱规则。美联储的拟议规则将落实该法律中的客户身份识别部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/405247/federal-reserve-rolls-out-proposing-rulemaking-requiring-stablecoin-issuers-to-maintain-customer-identification-program">Federal Reserve rolls out proposing rulemaking requiring stablecoin ...</a></li>
<li><a href="https://www.federalreserve.gov/newsevents/pressreleases/files/bcreg20260618a1.pdf">Federal Register notice: Permitted Payment Stablecoin Issuer ...</a></li>
<li><a href="https://www.bloomberg.com/news/articles/2026-06-18/fed-proposes-payment-stablecoin-issuer-identification-program">Federal Reserve Seeks Customer Identification Rules for Stablecoin ...</a></li>

</ul>
</details>

**标签**: `#stablecoin`, `#regulation`, `#Federal Reserve`, `#crypto`, `#compliance`

---

<a id="item-18"></a>
## [比特币低于挖矿成本五个月，矿工承压](https://www.coindesk.com/markets/2026/06/19/live-markets-bitcoin-has-traded-below-its-mining-cost-for-five-months-squeezing-miners) ⭐️ 6.0/10

比特币已连续五个月低于其预估挖矿成本，摩根大通当前预估生产成本为 78,000 美元，而比特币交易价格约为 62,500 美元。 这种持续的价格成本倒挂给矿工盈利能力带来压力，可能迫使效率较低的矿工关闭，降低网络算力，从而影响比特币的安全性和交易处理。 摩根大通的 78,000 美元估算是基于平均电费和矿机效率；实际挖矿成本因矿工而异。价格与成本之间的差距自 2026 年初以来一直存在。

rss · CoinDesk · Jun 19, 05:04

**背景**: 比特币挖矿涉及解决复杂数学问题以验证交易并赚取新比特币。成本包括电费、硬件和运营费用。当比特币市场价格低于挖矿成本时，矿工亏损运营，可能导致投降和算力下降。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/post/295005/jpmorgan-revises-bitcoin-production-cost-estimate-to-45000">JPMorgan revises bitcoin production cost estimate to $45,000</a></li>
<li><a href="https://cryptorank.io/news/feed/59112-jpmorgan-bitcoin-production-cost-2025">Bitcoin Production Cost Drops to $77K: JPMorgan’s Surprising ...</a></li>

</ul>
</details>

**标签**: `#Bitcoin`, `#mining`, `#cryptocurrency`, `#markets`

---

<a id="item-19"></a>
## [以太坊基金会再失核心领导，联合执行董事辞职](https://www.coindesk.com/tech/2026/06/18/ethereum-foundation-loses-another-key-leader-as-co-executive-director-hsiao-wei-wang-resigns) ⭐️ 6.0/10

以太坊基金会联合执行董事 Hsiao-Wei Wang 已辞职，这是该组织一系列高层离职事件中的最新一起。 此次领导层离职潮可能削弱对以太坊治理和稳定性的信心，并可能使 Solana 等竞争区块链受益，它们正试图吸引开发者和资本。 Wang 的离职是在前联合执行董事 Tomasz Stańczak 以及多位协议集群负责人离开之后发生的，董事会成员 Bastian Aue 已承担更大的临时领导职责。

rss · CoinDesk · Jun 18, 15:41

**背景**: 以太坊基金会是一个支持以太坊区块链生态系统的非营利组织。其领导层因治理和方向问题面临批评，尤其是在以太坊与更快、更便宜的区块链竞争之际。最近的离职事件加剧了关于基金会去中心化治理模式的争论。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://cointelegraph.com/news/ethereum-foundation-leadership-exodus-continues-with-directors-departure">Ethereum Foundation Leses Co-Executive Director Amid ...</a></li>
<li><a href="https://blockonomi.com/ethereum-foundation-faces-new-exit-as-wang-leaves-top-role/">Ethereum Foundation Faces New Exit as Wang Leaves Top Role</a></li>
<li><a href="https://blog.ethereum.org/2026/02/13/leadership-update">Executive Leadership Update | Ethereum Foundation Blog</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#leadership`, `#crypto`, `#blockchain`

---

<a id="item-20"></a>
## [Algorand 路线图计划 2028 年实现抗量子安全](https://www.coindesk.com/tech/2026/06/18/algorand-unveils-post-quantum-roadmap-to-secure-blockchain-by-2027) ⭐️ 6.0/10

Algorand 基金会公布了一份路线图，计划在 2028 年前使其区块链全面具备抗量子能力，并将在 2027 年引入后量子账户、多重签名钱包和质押支持。 量子计算对当前区块链密码学构成严重威胁，Algorand 的具体时间表为加密生态系统中的主动安全升级树立了先例。 该路线图包括过渡到后量子签名和密钥封装机制，预计在 2027 年底或 2028 年初实现全面抗量子能力。

rss · CoinDesk · Jun 18, 14:00

**背景**: 量子计算机可能破解大多数区块链使用的公钥密码学（如 ECDSA 和 RSA）。Algorand 采用纯权益证明共识，并一直在研究后量子密码学以使其网络面向未来。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/06/18/algorand-unveils-post-quantum-roadmap-to-secure-blockchain-by-2027">Algorand unveils roadmap for post-quantum security by end-2027</a></li>
<li><a href="https://algorand.co/blog/2025-on-algorand-roadmap-progress">2025 on Algorand: Roadmap progress</a></li>
<li><a href="https://algorand.co/blog/algorands-2025-roadmap-building-for-real-world-use">Algorand's 2025+ roadmap: Building for real-world use</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#quantum computing`, `#cryptography`, `#Algorand`

---

<a id="item-21"></a>
## [调查：超三分之一心理学家报告患者使用 AI 辅助治疗](https://decrypt.co/371451/psychologists-patients-bringing-ai-therapy-sessions-survey) ⭐️ 6.0/10

美国心理学会（APA）的一项新调查发现，超过三分之一的心理学家有患者将 AI 用作额外的心理健康专业人士，这引发了人们对 AI 技术可能强化妄想的担忧。 这一趋势凸显了 AI 在心理健康护理中日益整合，可能重塑治疗实践，并引发关于 AI 在治疗中角色的伦理问题。 该调查由 APA 进行，但新闻中未提供具体的样本量和方法细节。临床医生警告说，AI 可能强化妄想，尤其是在患有精神病性障碍的患者中。

rss · Decrypt · Jun 17, 23:36

**背景**: AI 聊天机器人和应用程序越来越多地被用于心理健康支持，提供便捷且低成本的选择。然而，它们缺乏人类临床医生的细致理解和治疗界限，这对脆弱患者来说可能存在问题。

**标签**: `#AI`, `#mental health`, `#psychology`, `#survey`

---

<a id="item-22"></a>
## [法官：体育预测市场不受 CFTC 管辖](https://decrypt.co/371486/michigan-federal-judge-sports-prediction-markets-not-under-cftc-purview) ⭐️ 6.0/10

密歇根州一名联邦法官裁定，体育预测市场不属于 CFTC 的管辖范围，这可能削弱该机构对 Polymarket 及类似平台的诉讼依据。 这一裁决可能重塑美国预测市场的监管格局，为 Polymarket 等平台在没有联邦监管的情况下运营开辟法律途径，但州级监管机构仍可能介入。 法官表示，Polymarket 针对密歇根州监管机构的诉讼不太可能在实体问题上胜诉，但联邦管辖权问题被裁定有利于该平台。该裁决不涉及州级执法行动。

rss · Decrypt · Jun 17, 22:06

**背景**: Polymarket 是一个基于加密货币的预测市场，用户可以对体育、选举等事件的结果下注。CFTC 历来主张对事件合约拥有专属管辖权，但这一裁决对体育相关市场的该权威提出了挑战。此案是联邦与州监管机构之间关于预测市场监管的更广泛法律斗争的一部分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cftc.gov/PressRoom/PressReleases/9183-26">CFTC Reaffirms Exclusive Jurisdiction over Prediction Markets ...</a></li>
<li><a href="https://www.hklaw.com/en/insights/publications/2026/02/prediction-markets-at-a-crossroads-the-continued-jurisdictional-battle">Prediction Markets at a Crossroads: The Continued ...</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#regulation`, `#crypto`, `#legal`

---

<a id="item-23"></a>
## [GLAAD 警告 AI 放大反 LGBTQ 偏见](https://decrypt.co/371431/glaad-ai-failing-lgbtq-users-warns-risk-growing) ⭐️ 6.0/10

GLAAD 发布报告警告称，AI 系统正在日益放大反 LGBTQ 的偏见、错误信息、歧视和隐私伤害。 这很重要，因为随着 AI 日益普及，未加控制的偏见可能对边缘化群体造成实际伤害，该报告是对开发者和政策制定者的行动呼吁。 报告强调了具体风险，例如针对 LGBTQ 个体的 AI 生成错误信息、有偏见的内容审核以及数据收集导致的隐私侵犯。

rss · Decrypt · Jun 17, 17:43

**背景**: AI 系统从通常包含社会偏见的大型数据集中学习，可能导致歧视性结果。GLAAD 是一个 LGBTQ 倡导组织，负责监测媒体呈现和歧视问题。

**标签**: `#AI ethics`, `#bias`, `#LGBTQ`, `#discrimination`, `#privacy`

---

<a id="item-24"></a>
## [DAO 黑客事件十周年：1.3 亿美元安全基金诞生](https://www.theblock.co/post/405248/ethereum-130-million-security-fund-the-dao-hack-10-years?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

2016 年 DAO 黑客事件盗走 360 万 ETH 十年后，未认领资金被重新用于设立一个 1.3 亿美元的以太坊安全基金，该基金已向 134 个安全项目拨付超过 100 万美元的资助。 该基金代表了 DAO 黑客事件的持久遗产，将灾难性损失转化为对区块链安全的持续投资，未来多年将使整个以太坊生态系统受益。 DAO 黑客攻击利用了智能合约代码中的重入漏洞，当时盗走了价值约 5000 万美元的 ETH。以太坊社区通过一次有争议的硬分叉来恢复资金，这导致了以太坊经典（Ethereum Classic）的产生。

rss · The Block · Jun 18, 15:20

**背景**: The DAO 是一个于 2016 年在以太坊上启动的去中心化自治组织，通过代币销售筹集了 1.5 亿美元。2016 年 6 月，攻击者利用代码漏洞盗走了约三分之一的资金。这一事件在加密货币历史上具有里程碑意义，导致了以太坊的第一次重大硬分叉，并凸显了智能合约安全的重要性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/The_DAO">The DAO - Wikipedia</a></li>
<li><a href="https://www.gemini.com/cryptopedia/the-dao-hack-makerdao">DAO Hack Explained: How a Vulnerability Split Ethereum</a></li>
<li><a href="https://www.panewslab.com/en/articles/019edb6a-e20e-776e-85e1-0c0fc4b134e2">The DAO's Unclaimed ETH Restarted as Long-Term Ethereum Security ...</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#DAO hack`, `#blockchain security`, `#crypto history`

---