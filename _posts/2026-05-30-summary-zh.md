---
layout: default
title: "Horizon Summary: 2026-05-30 (ZH)"
date: 2026-05-30
lang: zh
---

> From 87 items, 25 important content pieces were selected

---

1. [死经济理论](#item-1) ⭐️ 8.0/10
2. [Tiny-vLLM：用 C++和 CUDA 实现的高性能 LLM 推理引擎](#item-2) ⭐️ 8.0/10
3. [加州大学教师要求恢复 SAT 用于 STEM 招生](#item-3) ⭐️ 8.0/10
4. [Paxos 获 SEC 批准进行区块链股票清算](#item-4) ⭐️ 8.0/10
5. [前沿 AI 模型在三分之二的事实上存在分歧](#item-5) ⭐️ 8.0/10
6. [Anthropic 融资 650 亿美元，估值逼近万亿美元](#item-6) ⭐️ 8.0/10
7. [苹果 iOS 27 泄露：Siri 将获类 ChatGPT 改造并集成 Gemini](#item-7) ⭐️ 8.0/10
8. [SQLite 作为持久化工作流的足够后端](#item-8) ⭐️ 7.0/10
9. [Mistral AI Now 峰会：面向受监管行业的本地部署策略](#item-9) ⭐️ 7.0/10
10. [MCP 并未消亡：社区力挺该协议](#item-10) ⭐️ 7.0/10
11. [初创公司 Shift 提供免费家庭清洁以训练机器人](#item-11) ⭐️ 7.0/10
12. [Framework 12：可维修性与性能的权衡](#item-12) ⭐️ 7.0/10
13. [Liquid AI 发布 8B-A1B MoE 模型，训练于 38T 令牌](#item-13) ⭐️ 7.0/10
14. [Bijou64：一种新的变长整数编码](#item-14) ⭐️ 7.0/10
15. [John Gruber 创造“Dickover”一词指代烦人网页覆盖层](#item-15) ⭐️ 7.0/10
16. [CFTC 首次批准受监管的加密货币永续期货](#item-16) ⭐️ 7.0/10
17. [TrapDoor 包攻击瞄准 Solana、Sui 和 Aptos 钱包](#item-17) ⭐️ 7.0/10
18. [Kalshi 起诉阻止明尼苏达州预测市场禁令](#item-18) ⭐️ 7.0/10
19. [Anthropic 发布 Claude Opus 4.8：编码和安全提升，价格不变](#item-19) ⭐️ 7.0/10
20. [Base 在主网上启动 Azul 升级](#item-20) ⭐️ 7.0/10
21. [CertiK CEO 警告大规模部署 AI 代理可能引发灾难](#item-21) ⭐️ 6.0/10
22. [AI 智能体学会在用户提问前预测需求](#item-22) ⭐️ 6.0/10
23. [Sui 网络数月内再次遭遇重大宕机](#item-23) ⭐️ 6.0/10
24. [AI 将人类烹饪压缩至 2MB](#item-24) ⭐️ 6.0/10
25. [Aave Labs 获得英国双重加密支付牌照](#item-25) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [死经济理论](https://www.owenmcgrann.com/p/the-dead-economy-theory) ⭐️ 8.0/10

该理论挑战了人工智能将创造新就业的乐观观点，揭示了效率可能摧毁自身市场的宏观经济悖论，引发对人工智能驱动资本主义可持续性的辩论。 论文使用多轮场景：公司为节省成本解雇工人，却发现客户正是这些工人，导致收入崩溃。它提出了极端结果，如完全非人类的人工智能经济或分离主义。

hackernews · WillDaSilva · May 29, 15:46 · [社区讨论](https://news.ycombinator.com/item?id=48324712)

**背景**: “死经济”理论建立在技术性失业的概念之上，即自动化取代工人的速度快于新就业岗位的创造速度。它将这一想法扩展到系统层面，认为如果所有工人都被取代，将没有消费者购买商品和服务，导致经济崩溃。

**社区讨论**: 评论者讨论了科技人才过剩、效率摧毁市场的悖论，以及全民基本收入或退休式自由是否能缓解问题。一些人质疑人工智能公司的财务状况是否可持续。

**标签**: `#AI`, `#economics`, `#automation`, `#job displacement`, `#macroeconomic theory`

---

<a id="item-2"></a>
## [Tiny-vLLM：用 C++和 CUDA 实现的高性能 LLM 推理引擎](https://github.com/jmaczan/tiny-vllm) ⭐️ 8.0/10

Tiny-vLLM 是一个用 C++和 CUDA 编写的新型开源 LLM 推理引擎，其教育性 README 逐步拆解了推理过程。 它为开发者提供了理解和复现 LLM 推理的宝贵学习资源，弥合了高级框架与底层 GPU 编程之间的差距。 该项目托管在 GitHub 上，包含一份详细的 README，解释了 LLM 推理背后的心智模型，即使没有 CUDA 经验的开发者也能理解。

hackernews · yu3zhou4 · May 29, 19:38 · [社区讨论](https://news.ycombinator.com/item?id=48328184)

**背景**: 像 vLLM 这样的 LLM 推理引擎优化了在 GPU 上运行大型语言模型的过程，处理内存管理和调度。Tiny-vLLM 是一个专注于教育的极简实现，类似于早期版本的 llama.cpp。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/vllm-project/vllm">GitHub - vllm-project/vllm: A high-throughput and memory-efficient inference and serving engine for LLMs · GitHub</a></li>
<li><a href="https://andrewkchan.dev/posts/yalm.html">⭐️ Fast LLM Inference From Scratch - andrewkchan.dev</a></li>
<li><a href="https://learnaivisually.com/tracks/llm-serving/inference-engine">LLM Inference Engine Internals Explained Visually | Learn AI Visually</a></li>

</ul>
</details>

**社区讨论**: 社区称赞 README 是最有趣的部分，评论强调其教程式风格和易理解性。一位用户指出它让人想起最初的 llama.cpp，但文档更完善。

**标签**: `#LLM`, `#inference`, `#C++`, `#CUDA`, `#open-source`

---

<a id="item-3"></a>
## [加州大学教师要求恢复 SAT 用于 STEM 招生](https://www.latimes.com/california/story/2026-05-27/uc-math-professors-demand-return-of-sat-for-stem-admissions) ⭐️ 8.0/10

一群加州大学教师正式要求恢复 SAT 成绩用于 STEM 招生，理由是新生数学基础严重不足，导致教授不得不重教初中数学。 这场政策辩论可能重塑美国大学招生格局，在公平性与 STEM 领域学术准备之间形成张力，可能影响大学如何平衡标准化考试与全面审查。 SAT 总分为 400 至 1600 分，由数学和循证阅读与写作两部分组成，是传统的大学准备度指标。加州大学于 2020 年因公平问题取消 SAT 要求，但教师现在认为缺乏标准化数学基准导致 STEM 课程中出现准备不足的学生。

hackernews · brandonb · May 28, 14:13 · [社区讨论](https://news.ycombinator.com/item?id=48309233)

**背景**: SAT（学术评估测试）是美国大学招生中广泛使用的标准化考试，旨在评估学生是否具备大学水平学习的能力。STEM（科学、技术、工程和数学）领域需要较强的定量技能，数学能力是这些学科成功的关键预测指标。关于标准化考试的争论通常集中在它是否提供了公平的能力衡量标准，还是加剧了社会经济差距。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SAT">SAT - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Science,_technology,_engineering,_and_mathematics">Science, technology, engineering, and mathematics - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者观点不一：一些人支持教师对数学基础不足的担忧，并质疑为何不使用分班考试；另一些人则批评数字化学习的推广，并指出其他国家通过严格的考试制度培养出优秀毕业生，而无需标准化入学考试。

**标签**: `#education`, `#STEM`, `#SAT`, `#admissions`, `#math`

---

<a id="item-4"></a>
## [Paxos 获 SEC 批准进行区块链股票清算](https://www.coindesk.com/policy/2026/05/29/paxos-is-first-blockchain-firm-to-provide-settlement-and-clearing-services-following-sec-approval) ⭐️ 8.0/10

Paxos 成为首家获得 SEC 批准注册为清算机构的区块链原生公司，从而能够在区块链上清算和结算美国股票。 这一里程碑为传统资本市场实现当日结算铺平了道路，有望降低交易后流程的成本和低效率。 Paxos Securities Settlement Company 现在是唯一一家在 SEC 注册为清算机构和中央证券存管机构的区块链原生公司。

rss · CoinDesk · May 29, 12:28

**背景**: 清算和结算是确保证券交易正确完成的关键交易后流程。传统上，这些过程需要数天并涉及多个中介机构。区块链技术承诺实现更快、更透明的结算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/paxos-wins-sec-clearing-agency-140600011.html">Paxos Wins SEC Clearing Agency Approval for Blockchain Settlement Business</a></li>
<li><a href="https://www.banklesstimes.com/articles/2026/05/29/sec-approves-paxos-to-clear-and-settle-u-s-securities-on-blockchain-as-registered-agency/">SEC Approves Paxos for Blockchain-Based Securities Settlement | BanklessTimes</a></li>
<li><a href="https://news.bitcoin.com/sec-grants-paxos-historic-approval-to-clear-and-settle-us-equities-on-blockchain/">SEC Grants Paxos Historic Approval to Clear and Settle US Equities on Blockchain</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#finance`, `#regulation`, `#fintech`, `#securities`

---

<a id="item-5"></a>
## [前沿 AI 模型在三分之二的事实上存在分歧](https://decrypt.co/369480/ai-models-disagree-fact-checking-two-thirds-study) ⭐️ 8.0/10

一项新研究让五个前沿 AI 模型对 1000 个真实世界的事实性主张进行验证，发现它们在 67%的主张上存在分歧，揭示了 AI 事实核查的严重不一致性。 这一发现削弱了人们对 AI 作为可靠事实信息来源的信任，并对将 LLM 部署到事实核查和内容审核等关键任务中提出了担忧。 该研究使用了来自不同领域的 1000 个主张，评估了包括 GPT-4、Claude、Gemini 等在内的模型；分歧率为 67%，意味着模型对同一主张经常给出相互矛盾的判断。

rss · Decrypt · May 29, 17:26

**背景**: 前沿 AI 模型是最先进的大型语言模型（LLM），能够进行复杂推理。事实核查是一个常见的提议用例，但这项研究表明它们缺乏一致性，而一致性是可信赖性的关键。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/html/2503.01902v2">How LLMs Fail to Support Fact-Checking</a></li>

</ul>
</details>

**标签**: `#AI reliability`, `#fact-checking`, `#LLM evaluation`, `#AI safety`

---

<a id="item-6"></a>
## [Anthropic 融资 650 亿美元，估值逼近万亿美元](https://decrypt.co/369434/anthropic-nears-1-trillion-valuation-topping-openai-65-billion-raise) ⭐️ 8.0/10

Claude AI 模型的开发商 Anthropic 完成了 650 亿美元的新一轮融资，估值逼近 1 万亿美元，超越 OpenAI。该公司还报告年化收入超过 470 亿美元。 这轮融资标志着 Anthropic 的快速增长以及 AI 行业竞争的加剧，可能重塑领先 AI 实验室之间的力量平衡。巨额估值反映了投资者对 Anthropic 技术和商业模式的信心。 650 亿美元的融资和 1 万亿美元的估值基于 470 亿美元的年化收入，这是将短期收入推算至全年得出的数字。Anthropic 一直在扩大其云和计算合作伙伴关系以支持增长。

rss · Decrypt · May 28, 20:51

**背景**: Anthropic 是一家由前 OpenAI 员工创立的 AI 安全公司，以其 Claude 系列大语言模型而闻名。该公司专注于构建可靠且可解释的 AI 系统。年化收入是一种将短期收入推算至全年的指标，常被初创公司用来展示增长轨迹。

**标签**: `#AI`, `#funding`, `#Anthropic`, `#valuation`, `#industry news`

---

<a id="item-7"></a>
## [苹果 iOS 27 泄露：Siri 将获类 ChatGPT 改造并集成 Gemini](https://decrypt.co/369415/apple-ios-27-leaks-siri-redesign-chatgpt) ⭐️ 8.0/10

在 2026 年 WWDC 之前泄露的渲染图显示，Siri 将拥有专用应用、动态岛集成，并以 Google Gemini 为骨干，这是近 15 年来 Siri 最大的一次改造。 这一转变标志着苹果战略性地转向集成 Gemini 等第三方 AI 模型，可能使 Siri 与 ChatGPT 等先进助手竞争，影响整个 AI 助手市场。 重新设计包括专用 Siri 应用和动态岛集成，并以 Google Gemini 作为底层 AI 骨干，表明苹果正放弃仅依赖自有 AI 模型的策略。

rss · Decrypt · May 28, 19:50

**背景**: Siri 于 2011 年作为语音助手推出，但在能力上已落后于 ChatGPT 和 Google Assistant 等竞争对手。动态岛于 2022 年随 iPhone 14 Pro 推出，是一个将摄像头挖孔扩展为交互式通知区域的 UI 元素。Google Gemini 是 2023 年 12 月发布的多模态 AI 模型系列，能够处理文本、图像、音频和视频。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/Dynamic_Island">Dynamic Island</a></li>
<li><a href="https://grokipedia.com/page/google_gemini">Google Gemini</a></li>

</ul>
</details>

**标签**: `#Apple`, `#iOS`, `#Siri`, `#AI`, `#ChatGPT`

---

<a id="item-8"></a>
## [SQLite 作为持久化工作流的足够后端](https://obeli.sk/blog/sqlite-is-all-you-need-for-durable-workflows/) ⭐️ 7.0/10

一篇博客文章认为 SQLite 可以作为构建持久化工作流系统的足够后端，挑战了对更复杂数据库服务器（如 Postgres 或 MySQL）的需求。 这一讨论意义重大，因为它质疑了生产级工作流系统需要完整数据库服务器的默认假设，可能简化架构并降低许多应用的运营成本。 文章强调了 SQLite 的嵌入式特性、零配置以及在单进程或有限并发场景下的可靠性，但承认它可能不适合高并发或分布式环境。

hackernews · tomasol · May 29, 17:54 · [社区讨论](https://news.ycombinator.com/item?id=48326802)

**背景**: 持久化工作流是确保长时间运行的过程在故障后仍能可靠继续执行的系统。它们通常依赖数据库后端来持久化状态。SQLite 是一个轻量级的嵌入式 SQL 数据库引擎，将数据存储在单个文件中，而像 Postgres 这样的数据库服务器则处理来自网络中多个客户端的并发访问。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.hatchet.run/v1/durable-workflows-overview">Durable Workflows - Hatchet Documentation</a></li>
<li><a href="https://www.sqliteforum.com/p/integrating-sqlite-with-a-web-application">Integrating SQLite with Web Apps: Backend Connection Guide</a></li>
<li><a href="https://aandresalvarez.github.io/flujo/advanced/sqlite_backend_comprehensive_guide/">SQLite Backend - Flujo</a></li>

</ul>
</details>

**社区讨论**: 评论呈现分歧：一些用户分享了用 Go + SQLite 替换多个 SaaS 工具的成功案例，而另一些人则认为 SQLite 不适合管理生产环境中的并发，建议使用专用数据库服务器。

**标签**: `#SQLite`, `#Workflows`, `#Database`, `#Backend Development`, `#Software Architecture`

---

<a id="item-9"></a>
## [Mistral AI Now 峰会：面向受监管行业的本地部署策略](https://koenvangilst.nl/lab/mistral-ai-now-summit) ⭐️ 7.0/10

Mistral AI 举办了 Now 峰会，强调为受监管行业提供本地部署和欧洲托管的模型，合作伙伴如法国巴黎银行和 Abanca 展示了实际部署案例。 这使 Mistral 成为处理敏感数据时美国超大规模云服务商的重要欧洲替代方案，但社区对其技术落后于 DeepSeek 和 Qwen 等中国实验室的担忧可能削弱其长期竞争力。 Mistral 的小模型约有 1200 亿参数，而 Gemma4 和 Qwen3.6 等竞品在四分之一大小下表现更好。Mistral Large 3（总参数 6750 亿，活跃参数 410 亿）和 Ministral 3（30 亿、70 亿、140 亿）于 2025 年 12 月发布。

hackernews · vnglst · May 29, 16:22 · [社区讨论](https://news.ycombinator.com/item?id=48325340)

**背景**: Mistral AI 是一家成立于 2023 年的法国公司，专注于开源权重的大语言模型。本地部署允许组织在自己的基础设施上运行 AI 模型，确保敏感数据安全。DeepSeek 和 Qwen 是中国 AI 实验室，已发布极具竞争力的开源权重模型，且成本更低。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mistral_AI">Mistral AI - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek">DeepSeek</a></li>
<li><a href="https://mistral.ai/models">Models - from cloud to edge - Mistral AI</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：有人称赞 Mistral 面向受监管行业的本地部署策略，也有人认为 Mistral 在推理能力和效率上已落后于中国实验室。一位与会者指出，企业出席率高，合作伙伴活动活跃。

**标签**: `#AI`, `#Mistral`, `#European Tech`, `#On-Premise`, `#Regulation`

---

<a id="item-10"></a>
## [MCP 并未消亡：社区力挺该协议](https://www.quandri.io/engineering-blog/mcp-is-dead) ⭐️ 7.0/10

一篇题为“MCP 已死”的挑衅性博文声称模型上下文协议无关紧要，但包括 OpenAI 团队负责人在内的社区成员反驳称，MCP 作为超越 CLI 的集成层已被广泛采用，许多公司正在构建 MCP 服务器。 这场辩论凸显了 MCP 作为 LLM 工具集成标准日益增长的作用，它减少了自定义连接器的需求，并实现了 AI 对外部数据和服务的无缝访问。 该文章没有日期，但引用了 2025 年 11 月添加的延迟工具加载功能，使其数据至少过时七个月。MCP 本质上是带有服务发现的 JSON-RPC，它解决了仅靠 CLI 无法解决的集成问题。

hackernews · nadis · May 29, 22:56 · [社区讨论](https://news.ycombinator.com/item?id=48330436)

**背景**: 模型上下文协议 (MCP) 是一种开放协议，它标准化了 LLM 连接外部工具和数据源的方式，充当 AI 的通用遥控器。如果没有 MCP，将每个 AI 模型与每个工具集成都需要自定义连接器，导致高度复杂性。MCP 使用主机/客户端/服务器架构来简化这一过程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.descope.com/learn/post/mcp">What Is the Model Context Protocol (MCP) and How It Works</a></li>
<li><a href="https://github.com/modelcontextprotocol">Model Context Protocol · GitHub</a></li>
<li><a href="https://www.firecrawl.dev/blog/mcp-vs-cli">MCP vs CLI for AI Agents: Which One Should You Use in 2026?</a></li>

</ul>
</details>

**社区讨论**: 社区评论强烈支持 MCP，指出其广泛采用和作为集成层的实用性。一位 OpenAI 团队成员表示，几乎每家公司都在构建 MCP 服务器，批评者指出该文章的数据过时且过于关注 CLI。

**标签**: `#MCP`, `#LLM`, `#AI tools`, `#protocols`, `#OpenAI`

---

<a id="item-11"></a>
## [初创公司 Shift 提供免费家庭清洁以训练机器人](https://www.theverge.com/ai-artificial-intelligence/939765/ai-training-data-startup-shift-free-cleaning) ⭐️ 7.0/10

一家名为 Shift 的初创公司提供免费家庭清洁服务，以收集真实世界数据来训练家用机器人。该公司派遣配备摄像头的清洁工记录工作过程，利用这些视频教会机器人如何做家务。 这种方法可以通过提供大规模、真实的训练数据来加速家用机器人的开发，这是机器人技术的主要瓶颈。然而，它引发了重大的隐私担忧和商业模式可持续性的问题，让人联想到类似过去企业如 Homejoy 的命运。 Shift 的清洁工佩戴摄像头，捕捉吸尘、除尘和拖地等任务的第一人称视频。该公司计划利用这些数据训练 AI 模型，以控制未来的机器人硬件，但商用机器人产品的时间表仍不明确。

hackernews · evilsimon · May 29, 19:16 · [社区讨论](https://news.ycombinator.com/item?id=48327962)

**背景**: 训练机器人完成复杂的家务任务需要大量真实世界的演示数据，这既昂贵又难以收集。传统方法包括雇佣演员或使用脚本化环境，但这些往往缺乏真实家庭的多样性。Shift 的模式通过提供免费清洁来换取数据，旨在大规模解决数据稀缺问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.tessra.tech/">Tessra - Accelerating Home Robotics Training</a></li>
<li><a href="https://unidata.pro/datasets/robotic-household-activities/">Robotic Household Activities Dataset | 1,000 Hours — Unidata</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了复杂的感受：一些人认为这是一种巧妙的数据收集策略，而另一些人则提出隐私担忧并质疑商业模式，提到了 Homejoy 的失败。一位用户建议，与酒店合作可能是更实际且隐私问题更少的方法。

**标签**: `#robotics`, `#AI training data`, `#startup`, `#privacy`, `#data collection`

---

<a id="item-12"></a>
## [Framework 12：可维修性与性能的权衡](https://www.jeffgeerling.com/blog/2026/its-hard-to-justify-framework-12/) ⭐️ 7.0/10

Jeff Geerling 发表博客文章，认为 Framework 12 笔记本电脑虽然可维修性和 Linux 支持出色，但很难与 Apple Silicon 等更强大的替代品竞争。 这凸显了笔记本电脑市场中可维修性/道德价值观与原始性能之间的持续矛盾，影响了那些优先考虑可持续性和开源软件而非基准测试分数的消费者。 Framework 12 DIY 版起价 549 美元，预装版 799 美元，将于 2025 年第三季度发货，而 Apple Silicon MacBook 性能更强、续航更长，但可维修性较差。

hackernews · watermelon0 · May 29, 14:55 · [社区讨论](https://news.ycombinator.com/item?id=48323869)

**背景**: Framework 是一家以设计模块化、可维修笔记本电脑而闻名的公司，用户可以轻松升级组件。Apple Silicon 指苹果自研的基于 ARM 的芯片（M1、M2 等），性能高、能效好，但其设备难以维修和升级。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.pcgamer.com/hardware/gaming-laptops/ifixit-awards-the-framework-12-laptop-a-10-10-for-repairability-respects-your-time-your-budget-and-your-ability-to-make-repairs/">iFixit awards the Framework 12 laptop a 10/10 for repairability ...</a></li>
<li><a href="https://community.frame.work/t/introducing-the-framework-laptop-12/65009">Introducing the Framework Laptop 12 - Blog - Framework Community</a></li>
<li><a href="https://dev.to/arjun98k/from-x86-to-arm-how-apple-silicon-is-destroying-the-competition-1ima">From x86 to ARM: How Apple Silicon is Destroying the Competition - DEV Community</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了不同观点：一些人优先考虑可维修性和 Linux 支持而非原始规格，而另一些人则看重苹果的性能和生态系统。少数人指出 Framework 12 对他们的需求来说“足够好”，并且符合他们的价值观。

**标签**: `#Framework`, `#repairability`, `#Linux`, `#laptop`, `#Apple Silicon`

---

<a id="item-13"></a>
## [Liquid AI 发布 8B-A1B MoE 模型，训练于 38T 令牌](https://www.liquid.ai/blog/lfm2-5-8b-a1b) ⭐️ 7.0/10

Liquid AI 发布了 LFM2.5-8B-A1B，这是一个混合专家（MoE）语言模型，总参数量为 83 亿，激活参数量为 15 亿，训练于 38 万亿个令牌。 该模型专为设备端部署设计，在笔记本电脑和手机上实现强大的 AI 能力，支持离线工具调用和指令遵循，可能使先进 AI 更易获取。 该架构使用 24 层，其中 18 层为双门控 LIV 卷积块，6 层为 GQA 层，每次前向传播仅激活 15 亿参数以提高效率。

hackernews · simjnd · May 29, 16:19 · [社区讨论](https://news.ycombinator.com/item?id=48325306)

**背景**: 混合专家（MoE）模型使用多个专门的子网络（专家）和门控机制，每次输入仅激活一部分，以平衡性能和计算成本。对于 80 亿参数的模型，训练 38 万亿个令牌异常庞大，引发了过度训练的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.marktechpost.com/2026/05/28/liquid-ai-releases-lfm2-5-8b-a1b-an-on-device-moe-model-with-8-3b-total-and-1-5b-active-parameters/">Liquid AI Releases LFM2.5- 8 B - A 1 B : An On-Device MoE Model With...</a></li>
<li><a href="https://www.communeify.com/en/blog/liquid-ai-lfm-2-5-8b-moe-model-local-deployment-guide/">Powerful AI in Your Pocket! Deep Dive into Liquid AI's Edge Model ...</a></li>

</ul>
</details>

**社区讨论**: 社区反馈不一：一位用户发现该模型在修复 bug 的基准测试中表现不如一个更小的旧模型，而另一位用户则对其在视觉-语言-动作模型中的潜在应用表示兴奋。一些评论者对高令牌数量提出质疑，认为可能存在过度训练。

**标签**: `#AI`, `#machine learning`, `#MoE`, `#language model`, `#open source`

---

<a id="item-14"></a>
## [Bijou64：一种新的变长整数编码](https://www.inkandswitch.com/tangents/bijou64/) ⭐️ 7.0/10

Ink & Switch 推出了 Bijou64，一种变长整数编码，能够覆盖完整的 uint64 范围而无需额外字节，而 LEB128 在表示最大值时需要第 10 个字节。 Bijou64 提供了与 LEB128 不同的尺寸权衡，可能在像 CRDT 同步协议这类小整数常见的应用中提升性能，但对于用作标识符或消息长度的较大值可能效率较低。 Bijou64 使用 6 位前缀来编码长度和首数据位，最多用 9 个字节表示 2^64-1 以内的数，而 LEB128 使用带延续位的 7 位组，表示相同范围需要 10 个字节。

hackernews · justinweiss · May 29, 15:03 · [社区讨论](https://news.ycombinator.com/item?id=48323992)

**背景**: 像 LEB128 这样的变长整数编码被用于 DWARF 和 WebAssembly 等格式中，以紧凑地存储整数。它们用编码大小换取简单性，但通常存在过编码或某些范围大小不优等限制。Bijou64 旨在解决其中一些问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.inkandswitch.com/tangents/bijou64/">bijou64 - Ink & Switch</a></li>
<li><a href="https://en.m.wikipedia.org/wiki/LEB128">LEB128 - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区评论指出，Bijou64 可能不便于 SIMD 处理，且其非规范编码在编译器链接时可能带来问题。但一些用户认为，由于无需额外字节即可支持完整 uint64 范围，它在长度前缀场景中更优。

**标签**: `#encoding`, `#data serialization`, `#performance`, `#compression`

---

<a id="item-15"></a>
## [John Gruber 创造“Dickover”一词指代烦人网页覆盖层](https://daringfireball.net/2026/05/what_is_a_dickover) ⭐️ 7.0/10

John Gruber 创造了“dickover”一词，用来描述那些破坏用户体验的侵入式网页覆盖层，例如 Cookie 同意横幅和新闻通讯弹窗。该词迅速在 Hacker News 上流行，引发了对这一常见反模式的讨论。 这个术语命名了一个每天让用户感到沮丧的普遍 UX 反模式，为设计师和开发者提供了共同的语言来识别和解决该问题。它还凸显了对更好网络体验日益增长的需求，例如 Kagi Small Web 等倡议明确禁止此类覆盖层。 Gruber 通过让自己的网站在读者点击链接时显示一个标题为“This is a Dickover”的弹窗来演示这一概念。Hacker News 社区指出，开发者和经理们通常看不到这些覆盖层，因为他们已经接受过，导致用户体验存在盲点。

hackernews · tambourine_man · May 29, 23:54 · [社区讨论](https://news.ycombinator.com/item?id=48330882)

**背景**: 网页覆盖层，如 Cookie 同意弹窗、新闻通讯注册提示和应用安装横幅，很常见但经常干扰用户的主要任务。这些元素通常由法律要求（例如 GDPR 对 Cookie 的要求）或用于商业目标，但其实现可能过于激进。Kagi Small Web 是一个精心策划的网站列表，避免此类反模式，旨在提供更干净的浏览体验。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kagi_(search_engine)">Kagi (search engine)</a></li>

</ul>
</details>

**社区讨论**: Hacker News 社区普遍接受了这个术语，许多人分享了个人烦恼，并指出开发者常常因为已经关闭了覆盖层而意识不到问题。一些评论者认为这些覆盖层对于法律合规或业务可持续性是必要的，而另一些人则指出了像 Kagi Small Web 这样的替代方案，该方案排除了有此类做法的网站。

**标签**: `#UX`, `#web design`, `#anti-pattern`, `#user experience`, `#Kagi`

---

<a id="item-16"></a>
## [CFTC 首次批准受监管的加密货币永续期货](https://www.coindesk.com/policy/2026/05/28/u-s-cftc-opens-crypto-perp-door-with-approval-of-first-regulated-firm) ⭐️ 7.0/10

美国商品期货交易委员会（CFTC）于 2026 年 5 月 28 日（周五）首次批准 Kalshi 和 Coinbase 开展受监管的加密货币永续期货交易。 这标志着监管的重大转变，为美国市场打开了一种此前仅在离岸市场流行的杠杆交易产品，可能推动机构采用并重塑加密货币衍生品交易格局。 Kalshi 将提供比特币永续期货，而 Coinbase 可让美国客户交易离岸加密货币永续期货。永续期货是一种高风险杠杆衍生品，追踪基础加密货币价格且无到期日。

rss · CoinDesk · May 29, 14:00

**背景**: 永续期货是一种衍生品合约，允许交易者全天候以杠杆方式对加密货币价格进行投机，且无到期日。它们在离岸交易所广泛使用，但此前无法通过美国受监管实体获得。CFTC 负责监管美国期货市场，并逐步扩大对加密货币衍生品的监管范围。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ecos.am/en/blog/perpetual-futures-crypto-guide">Perpetual Futures Explained: What Crypto Perpetuals Are</a></li>
<li><a href="https://www.investopedia.com/terms/c/cftc.asp">investopedia.com/terms/c/ cftc .asp</a></li>
<li><a href="https://markets.financialcontent.com/wral/article/marketminute-2025-9-29-cryptocom-secures-landmark-cftc-approval-ushering-in-a-new-era-for-us-crypto-derivatives">Crypto .com Secures Landmark CFTC Approval, Ushering in a New...</a></li>

</ul>
</details>

**标签**: `#crypto`, `#regulation`, `#CFTC`, `#perpetual futures`, `#DeFi`

---

<a id="item-17"></a>
## [TrapDoor 包攻击瞄准 Solana、Sui 和 Aptos 钱包](https://www.coindesk.com/tech/2026/05/29/solana-sui-and-aptos-wallet-data-targeted-in-trapdoor-package-attack) ⭐️ 7.0/10

一个名为 TrapDoor 的恶意包攻击被发现，目标是 Solana、Sui 和 Aptos 区块链网络上的钱包数据。 此次攻击对多个区块链生态系统的用户和开发者构成直接安全威胁，可能导致加密资产和私钥被盗。 该攻击是一种供应链攻击，通过恶意包危害钱包数据，影响 Solana、Sui 和 Aptos 网络上的钱包。

rss · CoinDesk · May 29, 08:19

**背景**: 供应链攻击是指恶意代码被插入到开发者和用户无意中安装的软件包中。钱包数据包括私钥和助记词，这些是访问和控制加密货币资产的关键。Solana、Sui 和 Aptos 是支持去中心化应用的高性能区块链，拥有不断增长的用户群。

**标签**: `#security`, `#blockchain`, `#wallet`, `#supply chain attack`

---

<a id="item-18"></a>
## [Kalshi 起诉阻止明尼苏达州预测市场禁令](https://decrypt.co/369408/kalshi-sues-stop-minnesota-enforcing-prediction-market-ban) ⭐️ 7.0/10

受监管的预测市场平台 Kalshi 已向联邦法院提起诉讼，要求阻止明尼苏达州执行全国首个州级预测市场禁令，该禁令原定于 8 月生效。 这一法律挑战可能为各州如何监管预测市场树立先例，影响整个行业，并可能影响 CFTC 的联邦监管。 该诉讼是在明尼苏达州州长 Tim Walz 签署明确禁止预测市场的法律之后提起的，并且发生在 CFTC 就类似问题对 Kalshi 提起诉讼之后。

rss · Decrypt · May 28, 19:07

**背景**: 预测市场允许用户基于未来事件（如选举或体育赛事）的结果交易合约。Kalshi 是一个受联邦监管的此类合约交易所，但像明尼苏达州这样的州级禁令带来了法律不确定性。CFTC 负责监管衍生品市场，包括预测市场，并一直在积极审查 Kalshi 等平台。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kalshi">Kalshi - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/United_States_Commodity_Futures_Trading_Commission">United States Commodity Futures Trading Commission</a></li>

</ul>
</details>

**标签**: `#prediction markets`, `#regulation`, `#legal`, `#Kalshi`, `#Minnesota`

---

<a id="item-19"></a>
## [Anthropic 发布 Claude Opus 4.8：编码和安全提升，价格不变](https://decrypt.co/369384/anthropic-claude-opus-4-8-better-ai-coding-smarter-safety-huge-price) ⭐️ 7.0/10

Anthropic 发布了 Claude Opus 4.8，这是其旗舰 Opus 系列模型的升级版，在编码、代理任务和安全对齐方面有所改进，同时保持相同的高价格。 此次发布巩固了 Anthropic 在竞争激烈的 AI 市场中的地位，为开发者和企业提供了更好的性能，但不变的价格可能会限制小型团队的采用。 Claude Opus 4.8 可以执行更长的自主运行、更深入的推理，并在编辑前像工程师一样阅读代码库。它可通过 AWS 和 Anthropic 的 API 使用。

rss · Decrypt · May 28, 18:45

**背景**: Claude 是 Anthropic 开发的一系列大型语言模型，使用“宪法 AI”进行训练以提高伦理合规性。Opus 层级是功能最强的，而较小的 Haiku 和 Sonnet 层级可用于较轻的任务。Anthropic 还有一个有争议的模型 Claude Mythos，用于漏洞检测但未公开发布。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/news/claude-opus-4-8">Introducing Claude Opus 4.8 - anthropic.com</a></li>
<li><a href="https://aws.amazon.com/about-aws/whats-new/2026/05/claude-opus-4.8-aws/">Claude Opus 4.8 is now available on AWS - AWS</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Opus_4">Claude Opus 4</a></li>

</ul>
</details>

**标签**: `#AI`, `#Anthropic`, `#Claude`, `#LLM`, `#machine learning`

---

<a id="item-20"></a>
## [Base 在主网上启动 Azul 升级](https://www.theblock.co/post/403003/base-launches-azul-on-mainnet-pushing-coinbases-ethereum-l2-toward-full-decentralization?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Base 已在其主网上部署 Azul 升级，引入多重证明和新的客户端堆栈，以推进去中心化。 此次升级推动 Coinbase 的以太坊 L2 迈向完全去中心化，增强了安全性和去信任化，这对 L2 的竞争力至关重要。 Azul 采用最新的以太坊执行层规范（Osaka），并要求迁移到 Base 原生客户端（base-reth-node 和 base-consensus）。多重证明系统结合了 TEE 和 ZK 证明，以减少对单一证明系统的依赖。

rss · The Block · May 29, 09:31

**背景**: Base 是由 Coinbase 构建的以太坊 Layer 2（L2）扩容解决方案。去中心化程度按阶段衡量，Stage 2 代表完全去中心化。Azul 是 Base 的首次独立网络升级，旨在提高安全性、性能和去中心化程度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.base.dev/introducing-base-azul">Introducing Base Azul</a></li>
<li><a href="https://blog.base.dev/multiproofs-on-base">Multiproofs on Base - Base Engineering Blog</a></li>
<li><a href="https://www.kucoin.com/blog/en-what-does-base-azul-mean-for-ethereum-layer-2-competitiveness-in-2026">What Does Base Azul Mean for Ethereum Layer-2 Competitiveness in 2026? - KuCoin</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#Layer 2`, `#Decentralization`, `#Base`, `#Azul`

---

<a id="item-21"></a>
## [CertiK CEO 警告大规模部署 AI 代理可能引发灾难](https://www.coindesk.com/tech/2026/05/29/mass-deployment-of-ai-agents-is-a-disaster-waiting-to-happen-says-certik-ceo) ⭐️ 6.0/10

区块链安全公司 CertiK 联合创始人兼 CEO 顾荣辉警告称，在缺乏适当隔离和安全审查的情况下，大规模快速部署自主 AI 代理正在网络和应用中积累危险的“安全债务”。 这一警告凸显了 AI 代理采用速度与安全实践成熟度之间的关键差距，可能导致灾难性后果，如未经授权访问敏感数据或金融系统。它强调了为 AI 代理制定全行业安全标准的紧迫性。 顾荣辉特别指出，许多 AI 代理被授予访问本地文件、凭证和金融工具的权限而未进行隔离，使其容易被利用。他建议在测试期间隔离 AI 代理，以防止它们访问关键个人信息或数字资产。

rss · CoinDesk · May 29, 15:31

**背景**: AI 代理是能够代表用户执行任务的自主软件程序，例如管理财务或与其他系统交互。随着其使用迅速增长，安全问题随之出现，因为这些代理通常以高权限运行，可能成为攻击者的目标。CertiK 是一家知名的区块链安全公司，此前曾审计智能合约和去中心化应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/05/29/mass-deployment-of-ai-agents-is-a-disaster-waiting-to-happen-says-certik-ceo">Mass deployment of AI agents is a disaster waiting to happen, says CertiK CEO - CoinDesk</a></li>
<li><a href="https://en.cryptonomist.ch/2026/05/29/ai-agents-security-risks-certik/">AI agents security risks: CertiK warns on isolation and scans</a></li>
<li><a href="https://www.binance.com/en/square/post/05-29-2026-certik-ceo-warns-of-risks-from-unisolated-ai-agents-328408366007377">CertiK CEO Warns of Risks from Unisolated AI Agents</a></li>

</ul>
</details>

**标签**: `#AI safety`, `#AI agents`, `#blockchain`, `#security`

---

<a id="item-22"></a>
## [AI 智能体学会在用户提问前预测需求](https://decrypt.co/369382/ai-agents-learning-predict-what-users-want-before-ask) ⭐️ 6.0/10

中国研究人员开发了一种模型，利用 AI 的空闲时间预测并准备用户的下一个问题，在用户提问之前就做好准备。 这种主动方法可以显著降低延迟并改善对话式 AI 的用户体验，使交互感觉更流畅、更直观。 该模型利用空闲时间（AI 未积极处理请求的时段）预先计算可能的响应，从而有效预测用户意图。

rss · Decrypt · May 28, 20:24

**背景**: 传统的 AI 助手在用户说出或输入查询后才做出反应，这会引入微小但明显的延迟。预测模型旨在通过基于上下文和用户历史预先准备答案来消除这种滞后。

**标签**: `#AI`, `#machine learning`, `#predictive models`, `#research`

---

<a id="item-23"></a>
## [Sui 网络数月内再次遭遇重大宕机](https://decrypt.co/369414/sui-network-down-hours-months-after-last-downtime) ⭐️ 6.0/10

Sui 网络在 2026 年 5 月再次经历重大宕机，距离 2026 年 1 月的上一次网络停滞仅五个月。 这种反复的宕机引发了对 Sui 可靠性和验证者共识稳定性的担忧，可能削弱去中心化应用和用户对区块链的信任。 此次宕机由验证者共识处理内部分歧导致，阻止了验证者认证新的检查点，并导致交易超时。

rss · Decrypt · May 28, 20:09

**背景**: Sui 是一个为全球规模去中心化应用设计的高性能区块链。网络停滞发生在验证者无法达成共识时，导致交易处理暂停。这是 Sui 在 2026 年第三次重大中断，此前在 1 月和更早发生过类似事件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.sui.io/sui-mainnet-network-stall-resolution/">Sui Mainnet Network Stall Resolution</a></li>
<li><a href="https://coinlaw.io/sui-mainnet-stalls-third-network-disruption-2026/">Sui Mainnet Stalls Again, Marking Third Network Disruption of 2026</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#downtime`, `#Sui`

---

<a id="item-24"></a>
## [AI 将人类烹饪压缩至 2MB](https://decrypt.co/369304/ai-compressed-all-human-cooking-2-megabytes) ⭐️ 6.0/10

一家伦敦初创公司用 410 万份食谱（涵盖七种语言）训练了一个 AI，并将整个模型压缩到仅 2 兆字节，比一首典型的歌曲文件还小。 这展示了极端模型压缩的潜力，可能使 AI 在智能手机或嵌入式系统等低资源设备上运行，让 AI 驱动的烹饪辅助变得广泛可用。 该模型在七种语言的 410 万份食谱上训练，但压缩后的模型仅有 2 MB。报道未披露所使用的具体压缩技术。

rss · Decrypt · May 28, 15:07

**背景**: 模型压缩技术（如剪枝、量化和知识蒸馏）可以在保持精度的同时减小 AI 模型的大小。这使得大型模型能够在内存和计算能力有限的设备（如手机或物联网设备）上运行。

**标签**: `#AI`, `#model compression`, `#machine learning`, `#startup`

---

<a id="item-25"></a>
## [Aave Labs 获得英国双重加密支付牌照](https://www.theblock.co/post/403014/aave-labs-secures-dual-uk-licenses-for-regulated-crypto-payments-infrastructure-through-local-subsidiary?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Aave Labs 已为其 Push 子公司获得英国金融行为监管局（FCA）的加密资产注册，从而能够提供零费用的法币入金通道，用于受监管的加密支付。 这标志着主流 DeFi 协议在受监管框架内运营的重要一步，可能桥接传统金融与去中心化借贷。它可能为其他寻求在英国合规的 DeFi 项目树立先例。 这些牌照涵盖两家 Push 子公司，使 Aave 能够提供受监管的加密支付服务。零费用法币入金通道旨在降低用户成本并提高可访问性。

rss · The Block · May 29, 10:18

**背景**: Aave 是一个领先的去中心化金融（DeFi）协议，允许用户借贷加密货币。英国金融行为监管局（FCA）要求加密资产公司注册并遵守反洗钱法规。获得 FCA 注册是一个严格的过程，表明对监管标准的承诺。

**标签**: `#DeFi`, `#regulation`, `#crypto`, `#payments`, `#Aave`

---