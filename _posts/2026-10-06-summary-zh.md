---
layout: default
title: "Horizon Summary: 2026-10-06 (ZH)"
date: 2026-10-06
lang: zh
---

> From 67 items, 23 important content pieces were selected

---

1. [Reflection 发布 501B 开源权重 MoE 模型 Beam](#item-1) ⭐️ 8.0/10
2. [Opus 5.5 AI 智能体发现两种室温磁性半导体候选材料](#item-2) ⭐️ 8.0/10
3. [Anthropic 将用户日记内容举报给警方，一名女性面临重罪指控](#item-3) ⭐️ 8.0/10
4. [ChatGPT 在伪造的《纽约客》漫画上添加真实漫画家签名](#item-4) ⭐️ 8.0/10
5. [OKX 与 ICE 申请设立 24/7 代币化美股交易平台](#item-5) ⭐️ 8.0/10
6. [FlattenSF 帮助用户找到旧金山最平坦的路线](#item-6) ⭐️ 7.0/10
7. [Dust 无需反向传播即可预训练 Transformer](#item-7) ⭐️ 7.0/10
8. [Cloudflare 推出面向 AI 智能体的 Web Search API](#item-8) ⭐️ 7.0/10
9. [FinCEN 撤销 1 万美元加密钱包报告规则](#item-9) ⭐️ 7.0/10
10. [Solana 基金会推出机构结算 DvP 计划，摩根大通参与建言](#item-10) ⭐️ 7.0/10
11. [Stripe 计划年底前将稳定币卡扩展至 100 多个国家](#item-11) ⭐️ 7.0/10
12. [ZachXBT 花费 35 万美元假扮 Lazarus 关联中国洗钱团伙客户](#item-12) ⭐️ 7.0/10
13. [CFTC 提出针对杠杆零售加密货币交易的新联邦监管框架](#item-13) ⭐️ 7.0/10
14. [Example.com 改版导致自动化测试失效，引发海勒姆定律讨论](#item-14) ⭐️ 6.0/10
15. [开发者从 Deno 回归 Node，引发运行时之争](#item-15) ⭐️ 6.0/10
16. [博客称 Common Lisp 是当下最适合 LLM 辅助编程的语言](#item-16) ⭐️ 6.0/10
17. [以太坊 Glamsterdam 测试网在容量跃升前获最后一刻修复](#item-17) ⭐️ 6.0/10
18. [超过 60 只美股（含英伟达和特斯拉）即将上链](#item-18) ⭐️ 6.0/10
19. [CFTC 加入 SEC 提出加密监管规则，现货市场监管缺口仍存](#item-19) ⭐️ 6.0/10
20. [美国财政部制裁为哈马斯筹集 200 万美元的加密货币网络](#item-20) ⭐️ 6.0/10
21. [以太坊质押队列延长至两周，150 万 ETH 排队等待](#item-21) ⭐️ 6.0/10
22. [美国 SEC 批准 3 倍杠杆比特币和以太坊基金](#item-22) ⭐️ 6.0/10
23. [美国独立社区银行家协会起诉 OCC，指加密货币借'侧门'进入银行体系](#item-23) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Reflection 发布 501B 开源权重 MoE 模型 Beam](https://reflection.ai/blog/introducing-beam) ⭐️ 8.0/10

Reflection 发布了 Beam，这是一个开放权重的稀疏混合专家（MoE）模型，总参数量 5010 亿，激活参数 230 亿，面向编程、推理和智能体（agentic）工作负载。该模型在 23.8 万亿 token 上完成预训练，并经过强化学习进一步调优，社区已将其与 DeepSeek V4.1 Flash 进行直接对比。 来自西方实验室的 501B 开放权重 MoE 模型是开放权重生态的重要补充，而该生态近期一直由中国模型（如 DeepSeek 和 Qwen）主导。它为开发者提供了又一个前沿规模的自托管与微调选择，也加剧了关于西方开放模型能否匹敌中国同行的争论。 Beam 在预填充（prefill）和解码（decode）阶段均使用 230 亿激活参数，没有独立的 N-gram/PLE 参数分支，训练 token 量约为 28 万亿，而 DeepSeek V4.1 Flash 为 45 万亿。在病毒式传播的 X 谜题泛化测试中，Beam 据称达到 95.5% 的覆盖率，介于 Opus 5（92.5%）与另一前沿模型之间。

hackernews · Philpax · Oct 5, 19:16 · [社区讨论](https://news.ycombinator.com/item?id=49969183)

**背景**: 稀疏混合专家（MoE）模型将参数拆分为多个专门的“专家”子网络，每个 token 只路由到其中一小部分，因此总参数量可以非常庞大，而单 token 计算量保持较低。“激活参数”指处理单个 token 时实际使用的权重，这正是 501B 模型能以 230 亿激活参数运行的原因。“开放权重”意味着训练好的权重可公开下载，支持自托管和微调，与仅提供 API 的闭源模型不同。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained - Hugging Face</a></li>
<li><a href="https://developer.nvidia.com/blog/dense-vs-moe-models-active-parameters-throughput-and-when-to-choose-each/">Dense vs. MoE Models: Active Parameters, Throughput, and When ...</a></li>
<li><a href="https://openai.com/index/introducing-gpt-oss/">Introducing gpt-oss | OpenAI</a></li>

</ul>
</details>

**社区讨论**: 评论者欢迎又一个开放权重模型的发布，但对基准测试结果持怀疑态度，有人指出病毒式传播的 X 谜题测试仅出现数天，因此是合理的泛化检验。其他人从 token 数量和激活参数角度将 Beam 与 DeepSeek V4.1 Flash 对比，认为 Beam 不占优势；还有人认为西方开放模型仍远落后于中国模型，希望出现更多竞争，并称赞 Google 的 Gemma 系列。

**标签**: `#open-weight models`, `#mixture-of-experts`, `#LLM release`, `#AI research`, `#benchmarking`

---

<a id="item-2"></a>
## [Opus 5.5 AI 智能体发现两种室温磁性半导体候选材料](https://www.vals.ai/blogs/room-temperature-magnetic-semiconductors) ⭐️ 8.0/10

一个由 Claude Opus 5.5 AI 智能体组成的团队通过运行量子力学密度泛函理论（DFT）模拟，在两种近似水平（PBE+U 和 HSE06）下自主发现了两种室温反铁磁半导体候选材料。该成果由 Vals AI 发布，是 AI 驱动材料发现的一个显著案例。 如果得到验证，室温磁性半导体可能催生新型计算机存储器和自旋电子器件，将逻辑运算与磁存储相结合。这项工作还凸显了 AI 智能体如何通过自主探索巨大的化学空间来加速材料发现，不过独立的实验验证仍有待进行。 智能体使用了 DFT 这一标准计算方法，并采用更精确的 HSE06 泛函来计算带隙和自旋窗口，但 DFT 在描述半导体带隙和铁磁性方面已知存在局限性。该发现尚未得到实验证实，社区成员对此表示怀疑，并将其与 LK-99 事件相提并论。

hackernews · outlier99 · Oct 5, 21:00 · [社区讨论](https://news.ycombinator.com/item?id=49970667)

**背景**: 磁性半导体是同时表现出铁磁性（或类似磁有序）和有用半导体特性的材料，可能允许通过磁场控制导电。密度泛函理论（DFT）是一种广泛使用的量子力学建模方法，用于计算材料的电子结构，但它通常难以准确预测半导体中的带隙和磁性。像 Claude Opus 5.5 这样的 AI 智能体是自主系统，可以在无需人工干预的情况下执行运行模拟和分析结果等复杂任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.vals.ai/blogs/room-temperature-magnetic-semiconductors">Two Room - Temperature Antiferromagnetic Semiconductor ... | Vals AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Magnetic_semiconductor">Magnetic semiconductor - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Density_functional_theory">Density functional theory</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的讨论（312 分，204 条评论）显示出兴奋与怀疑并存。一些评论者质疑其新颖性，指出当前半导体已在室温下工作，而其他人则将这一声明与 LK-99 事件相比较，并呼吁进行实验验证。关于磁性类型和 DFT 模拟作用的技术澄清也引发了辩论。

**标签**: `#AI for Science`, `#Materials Science`, `#Magnetic Semiconductors`, `#Density Functional Theory`, `#Autonomous Agents`

---

<a id="item-3"></a>
## [Anthropic 将用户日记内容举报给警方，一名女性面临重罪指控](https://www.techspot.com/news/114091-florida-woman-used-claude-diary-anthropic-reported-shoot.html) ⭐️ 8.0/10

据报道，Anthropic 将一名佛罗里达州女性写给其 Claude 聊天机器人的日记内容标记并举报给执法部门，导致她根据佛罗里达州法规 836.10 被控二级重罪，罪名是传播书面威胁。该事件引发了关于 AI 监控、用户隐私以及 AI 公司报告内容的法律义务的广泛争论。 此案凸显了 AI 公司预防伤害的义务与用户隐私期望之间的紧张关系，可能为 LLM 提供商如何处理敏感用户内容树立先例。它影响到所有使用 AI 聊天机器人进行个人表达的人，引发了关于与 AI 的私人对话是否真正保密的疑问。 佛罗里达州法规 836.10 规定，发送、发布或传播威胁杀害或伤害他人、实施大规模枪击或恐怖主义的书面或电子记录属于二级重罪，但该通信必须以他人可以查看的方式进行。社区成员指出，该日记内容并非意图公开，尽管最终被 Anthropic 工作人员审查。

hackernews · emptybits · Oct 5, 05:37 · [社区讨论](https://news.ycombinator.com/item?id=49961057)

**背景**: 像 Anthropic 和 OpenAI 这样的大型语言模型提供商拥有内容审核系统，会扫描用户交互以发现潜在威胁或非法活动。这些公司通常有法律义务向执法部门报告可信的威胁，但私人表达与可报告内容之间的界限模糊。此事件之前已有类似案例，AI 公司因过度报告或报告不足用户行为而受到批评。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://futurism.com/artificial-intelligence/anthropic-claude-ai-chatbot-police-violence-safety">Anthropic Reports User to the Police - Futurism</a></li>
<li><a href="https://www.commondreams.org/news/anthropic-pre-crime-surveillance">Anthropic Building a 'Pre-Crime' System to Surveil Anti-AI ...</a></li>

</ul>
</details>

**社区讨论**: 评论者对 Anthropic 的困境表示同情，指出 OpenAI 曾因在类似情况下未能报告枪手而受到批评，造成了“不做也错，做也错”的局面。一些人认为用户不应期望在与大型科技公司聊天时享有隐私，而另一些人则争论佛罗里达州法规的法律解释，并建议运行本地开源模型以避免监控。

**标签**: `#AI ethics`, `#privacy`, `#surveillance`, `#LLM`, `#law`

---

<a id="item-4"></a>
## [ChatGPT 在伪造的《纽约客》漫画上添加真实漫画家签名](https://www.niemanlab.org/2026/10/chatgpt-is-adding-real-cartoonists-signatures-to-fake-new-yorker-cartoons/) ⭐️ 8.0/10

据 Nieman Lab 报道，ChatGPT 的图像生成功能在生成伪造的《纽约客》风格漫画时，会自动加上真实在世漫画家的签名。用户只需输入“一幅《纽约客》风格的漫画”这样的提示词，输出结果就常常包含模仿真实艺术家笔迹的伪造签名。 这一事件凸显了一个具体的 AI 伦理与版权问题：生成模型不仅是在模仿风格，还在伪造作者身份归属，这可能使 OpenAI 面临法律责任，并损害被伪造签名漫画家的声誉。它还引发了更广泛的疑问：AI 公司应如何处理签名这类可识别个人标识的输出。 这些签名似乎是模型在《纽约客》漫画上训练后产生的涌现性产物，因为这类漫画通常在角落带有签名；AI 并不理解签名的含义，也不明白它构成了一种作者身份声明。漫画家兼研究者 Gwern Branwen 指出，他使用 Nano Banana Pro 和 ChatGPT 生成漫画时一直遇到这个问题，需要手动编辑来擦除虚假签名。

hackernews · rdmuser · Oct 5, 22:46 · [社区讨论](https://news.ycombinator.com/item?id=49971846)

**背景**: 《纽约客》以其单格漫画闻名，每幅漫画传统上都会在角落由艺术家签名。ChatGPT 的图像生成功能由 GPT-4o 等模型驱动，能够渲染文字并模仿训练数据中的视觉风格，但它缺乏对作者身份或抄袭等法律概念的语义理解。根据美国法律，视觉风格本身不受版权保护，但伪造签名以虚假归属作品是另一个法律问题，可能构成欺诈或类似商标的虚假陈述。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=49971846">ChatGPT is adding real cartoonists ' signatures to fake New Yorker ...</a></li>
<li><a href="https://openai.com/index/introducing-4o-image-generation/">Introducing 4o Image Generation | OpenAI</a></li>
<li><a href="https://lawreview.uchicago.edu/online-archive/plagiarism-copyright-and-ai">Plagiarism, Copyright, and AI | The University of Chicago Law ...</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者大多持批评态度，有人称其为“抄袭即服务”，还有人认为真正的问题在于 OpenAI 没有“被起诉到破产”。其他人指出了执法上的不对称——个人因盗版 MP3 或伪造签名会被罚款，而 AI 公司大规模这样做却毫无后果——也有人给出技术解释，指出模型只是把签名当作视觉元素，并不理解其含义。

**标签**: `#AI ethics`, `#copyright`, `#generative AI`, `#plagiarism`, `#OpenAI`

---

<a id="item-5"></a>
## [OKX 与 ICE 申请设立 24/7 代币化美股交易平台](https://www.coindesk.com/markets/2026/10/05/okx-and-nyse-s-owner-file-for-round-the-clock-tokenized-trading-in-u-s-stocks) ⭐️ 8.0/10

OKX 与纽约证券交易所母公司洲际交易所（ICE）已向美国证券交易委员会（SEC）提交通知，计划成立合资企业，提供 24 小时不间断的代币化美股交易服务。该申请依据 SEC 新出台的“创新豁免”机制提交，列出了包括英伟达和 SpaceX 在内的 60 多只股票，并与稳定币配对。 这是传统金融与区块链交汇处的一项里程碑式举措，因为它可能通过实现连续、代币化的市场，从根本上改变美股的交易方式。若获批，它将把主要的加密货币和传统交易所参与者联合起来，可能重塑市场结构并扩大散户和全球投资者的准入。 该申请依据 SEC 的“创新豁免”提交，这是一项于 2026 年 9 月 17 日宣布的五年期有限救济措施，旨在促进国家市场体系股票代币化版本的交易。通知特别将 60 多只股票与稳定币配对，表明结算将以稳定币形式而非传统法币进行。

rss · CoinDesk · Oct 5, 04:45

**背景**: 代币化证券是传统金融资产（如股票）在区块链上发行和交易的数字表示。SEC 于 2026 年 9 月宣布的“创新豁免”是一项为期五年的试点计划，允许某些代币化证券在放宽的监管要求下交易，旨在促进创新同时维护投资者保护。ICE 和 OKX 此前于 2026 年 6 月宣布成立合资企业，以连接传统和数字资产市场，而此次申请是朝着该目标迈出的具体一步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.sec.gov/newsroom/speeches-statements/uyeda-statement-innovation-exemption-091726">SEC .gov | Statement on the Innovation Exemption</a></li>
<li><a href="https://www.ashurstperkinscoie.com/en/insights/the-secs-innovation-exemption-for-tokenized/">The SEC ’s ' Innovation Exemption ' for tokenized stock: What public...</a></li>
<li><a href="https://www.businesswire.com/news/home/20260622653058/en/Intercontinental-Exchange-and-OKX-Establish-Joint-Venture-to-Bridge-Traditional-and-Digital-Asset-Markets">Intercontinental Exchange and OKX Establish Joint Venture to Bridge...</a></li>

</ul>
</details>

**标签**: `#blockchain`, `#tokenization`, `#stock-trading`, `#cryptocurrency`, `#financial-markets`

---

<a id="item-6"></a>
## [FlattenSF 帮助用户找到旧金山最平坦的路线](https://flattensf.com/) ⭐️ 7.0/10

一个名为 FlattenSF（flattensf.com）的新网页工具可以通过最小化海拔爬升而非距离，找到旧金山任意两点之间最平坦的骑行或步行路线。它在 Hacker News 上获得了 173 分和 58 条评论，用户们分享了相关项目并批评了该工具的海拔数据和路线准确性。 该工具凸显了城市骑行和步行中对海拔感知路线的日益增长的需求，在这种情况下，避开陡坡比走最短路径更重要。它还引发了关于海拔数据集质量以及路线算法如何处理坡度最小化的更广泛讨论，这会影响许多 GIS 和导航应用。 该工具的准确性存在争议：一位评论者指出它建议走 25 大道进行不必要的爬升，而不是平坦的 23 大道；另一位评论者建议，最小化总爬升量可能会产生技术上最平坦但不如稍长、坡度更缓的替代路线舒适的路线。海拔数据分辨率是关键因素，由于建筑和树木的影响，旧金山推荐使用 1 米 DTM 数据，而 Valhalla 目前仅支持 30 米分辨率。

hackernews · ishan0102 · Oct 5, 21:40 · [社区讨论](https://news.ycombinator.com/item?id=49971230)

**背景**: 海拔感知路线使用数字高程模型（DEM），如 DTM（数字地形模型），来计算道路和小径的坡度。像 Dijkstra 或 A* 这样的路线算法通常在图中寻找最短路径，但也可以调整为最小化海拔变化。在旧金山，陡峭的山丘和密集的城市特征使得高分辨率海拔数据对于准确的路线规划至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/taisenish/flattest-route-algorithm">GitHub - taisenish/ flattest - route - algorithm</a></li>

</ul>
</details>

**社区讨论**: 评论者分享了相关工具，如 Bikehopper（对旧金山使用 1 米 DTM 数据）和 Valhalla（支持海拔但仅 30 米分辨率）。一些人称赞了可视化效果，但批评了算法的准确性，一位用户报告了一条忽略平坦街道的错误路线。其他人建议增加一个选项来最小化坡度而非总爬升量，还有一位用户深情地提到了著名的“Wiggle”自行车路线。

**标签**: `#routing`, `#elevation-data`, `#gis`, `#cycling`, `#web-tools`

---

<a id="item-7"></a>
## [Dust 无需反向传播即可预训练 Transformer](https://qlabs.sh/research/dust) ⭐️ 7.0/10

qlabs.sh 的研究人员提出了 Dust，称其是首个在预训练 Transformer 语言模型时能与反向传播相媲美的零阶方法。据称在大规模种群设置下，Dust 在多个场景中超过了反向传播，并且比权重空间的进化策略高效数个数量级。 如果得到验证，这种无需反向传播的预训练方法可能重塑大语言模型的训练方式，有望实现异步学习或材料内学习，并减少对梯度计算的依赖。它也挑战了长期以来认为基于梯度的一阶方法是唯一可行的大规模神经网络训练路径的假设。 Dust 是一种零阶方法，它扰动 Transformer 的激活值，并利用损失变化来估计训练更新，而不是通过反向传播计算梯度。作者声称它比权重空间的进化策略高效数个数量级，但该方法仍是无导数的，因此其可扩展性和收敛性仍受到质疑。

hackernews · E-Reverance · Oct 5, 21:15 · [社区讨论](https://news.ycombinator.com/item?id=49970871)

**背景**: 反向传播是训练神经网络的标准算法，利用梯度来更新权重。零阶优化方法（也称为无导数优化）仅依赖函数评估，长期以来一直被探索作为替代方案，尤其适用于黑盒或不可微目标。Transformer 是大语言模型的主流架构，其预训练通常需要大量算力和反向传播。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://qlabs.sh/research/dust">Dust: Pretraining Transformers Without Backpropagation</a></li>
<li><a href="https://news.ycombinator.com/item?id=49970871">Dust: Pretraining Transformers Without Backpropagation ...</a></li>
<li><a href="https://astrophotographyhq.com/ai-tooling/dust-pretraining-transformers-without-backpropagation/">Dust: Pretraining Transformers Without... - Astro Photography HQ</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者大多持怀疑态度，有人指出无导数方法每隔几年就会被炒作一次，但从未产生实际影响，因为对于平滑的神经网络目标，梯度提供的信息要多得多。其他人质疑零阶方法是否真正解决了非凸性问题，而一位评论者指出反向传播受 Hessian 条件数限制，认为消除这一限制是积极的一步。

**标签**: `#machine-learning`, `#transformers`, `#optimization`, `#backpropagation`, `#research`

---

<a id="item-8"></a>
## [Cloudflare 推出面向 AI 智能体的 Web Search API](https://developers.cloudflare.com/changelog/post/2026-10-02-introducing-web-search-api/) ⭐️ 7.0/10

2026 年 10 月 2 日，Cloudflare 推出了 Web Search API，让 AI 智能体可以通过单一端点搜索网页，并将请求路由到 Ceramic.ai、Linkup 和 Exa 等提供商，按原价传递、不加价。 这一发布之所以重要，是因为它让本已是互联网主要守门人的 Cloudflare 成为智能体网页搜索的核心中间商，既可能简化开发者的提供商集成，也引发了关于成本、许可和平台集中化的担忧。 定价方面，Ceramic.ai 为每 1000 次请求 0.25 美元，Linkup 为 5 美元，Exa 为 7 美元，Cloudflare 不额外加价；该 API 通过 Cloudflare 的 AI Gateway 提供商代理端点对外提供。

hackernews · tosh · Oct 5, 10:47 · [社区讨论](https://news.ycombinator.com/item?id=49963171)

**背景**: Cloudflare 是一家主要的內容分发网络和互联网基础设施公司，其服务覆盖大量网站，使其对网络流量拥有显著影响力。AI 智能体越来越需要实时网页搜索来获取最新信息，Exa、Brave、Tavily 和 Firecrawl 等专用搜索 API 应运而生以满足这一需求。Cloudflare 此举将多个此类提供商聚合到一个端点之后，类似于其 AI Gateway 已经代理多家 AI 模型提供商的做法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.creativeainews.com/articles/cloudflare-web-search-api-agent-search-prices-2026/">Cloudflare Web Search API vs Exa, Brave, Tavily: Prices</a></li>
<li><a href="https://developers.cloudflare.com/ai-gateway/usage/web-search/">Web Search · Cloudflare AI Gateway docs</a></li>
<li><a href="https://securityexpress.info/cloudflare-web-search-api/">Cloudflare Web Search API : Real-Time Browsing for AI</a></li>

</ul>
</details>

**社区讨论**: Hacker News 的评论者提出了关于搜索结果能否根据条款存储和再分发的担忧，simonw 指出这类限制往往埋在细则里。其他人则比较了成本，指出 Gemini Flash Lite 2.5 每天仍提供 1000 次免费 Google 搜索，还有人质疑 Cloudflare 是否需要在一切事情中都插一脚，并对其日益增长的守门人角色发出警告。

**标签**: `#web-search`, `#cloudflare`, `#api`, `#ai-agents`, `#infrastructure`

---

<a id="item-9"></a>
## [FinCEN 撤销 1 万美元加密钱包报告规则](https://www.coindesk.com/policy/2026/10/06/u-s-scraps-proposed-usd10-000-reporting-rule-for-for-crypto-sent-to-private-wallets) ⭐️ 7.0/10

FinCEN 撤销了 2020 年提出的一项规则草案，该规则原本要求银行和货币服务企业报告向自托管钱包发送的超过 1 万美元的加密货币交易，同时还撤销了 2023 年将加密货币混币列为《爱国者法案》下“主要洗钱关注”的计划。这两项提案均从未生效。 此举消除了一个重大的合规负担，该规则原本会使加密货币交易相比传统金融面临双重标准，并表明美国加密政策正转向优先考虑隐私而非监控。这影响到交易所、钱包提供商以及将资金转入自托管的普通加密用户。 2020 年的规则原本要求报告超过 1 万美元的交易，或 24 小时内累计超过 1 万美元的多笔交易，并对超过 3000 美元的交易进行记录保存。2023 年的提案原本允许财政部根据《美国爱国者法案》第 311 条对美国金融机构施加特别措施。

rss · CoinDesk · Oct 6, 04:55

**背景**: 自托管钱包（也称非托管钱包）允许用户自行持有私钥，无需第三方中介即可直接控制区块链上的资金。FinCEN 是美国财政部负责执行反洗钱规则的机构。《美国爱国者法案》第 311 条赋予财政部将某些交易或机构指定为“主要洗钱关注”并施加特别措施的权力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.coindesk.com/policy/2026/10/06/u-s-scraps-proposed-usd10-000-reporting-rule-for-for-crypto-sent-to-private-wallets">U.S. scraps proposed $ 10 , 000 reporting rule for for crypto sent to...</a></li>
<li><a href="https://www.theblock.co/news/regulation/2026-10-05-fincen-drops-crypto-mixing-rule-self-hosted-wallet-proposal-417690">Treasury withdraws crypto mixing rule, citing concerns ... | The Block</a></li>
<li><a href="https://cryptonews.com/academy/what-is-self-custodial-wallet/">What Is a Self-Custodial Wallet? Definition - Crypto News</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#privacy`, `#policy`, `#blockchain`

---

<a id="item-10"></a>
## [Solana 基金会推出机构结算 DvP 计划，摩根大通参与建言](https://www.coindesk.com/markets/2026/10/06/solana-foundation-unveils-a-program-to-settle-institutional-trades-in-seconds-with-jpmorgan-s-inputs) ⭐️ 7.0/10

Solana 基金会宣布推出一项开源的“DvP”（券款对付）计划，该计划在摩根大通的参与建言下构建，使机构能够在 Solana 上以原子方式结算交易，最终确认时间从数天缩短至数秒。 摩根大通这类华尔街大型银行的参与，表明机构对使用公链进行证券结算的兴趣日益浓厚，这可能对传统的多日结算周期形成压力，并加速代币化资产的采用。 该计划是开源的，核心是原子化 DvP 结算，即证券交割与付款同时发生，整笔交易要么全部完成、要么全部失败；公告未披露技术规格、支持的资产类型或上线时间表。

rss · CoinDesk · Oct 6, 04:23

**背景**: 券款对付（DvP）是一种标准的证券结算方式，即证券过户与相应付款同时进行，从而降低一方违约的风险。原子化结算将这一概念引入区块链，单笔交易可以打包交割与付款两个环节，使其要么一起执行、要么都不执行。Solana 是一条高吞吐量的权益证明（PoS）一层区块链，以快速、低成本的交易著称，因此成为此类结算应用场景的候选平台。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Delivery_versus_payment">Delivery versus payment - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Solana_(blockchain_platform)">Solana (blockchain platform)</a></li>
<li><a href="https://algorand.co/learn/atomic-settlement-in-blockchain-what-it-takes-to-be-ready-for-modern-finance-and-why-algorand-is">Atomic settlement in blockchain : What it takes to be ready for...</a></li>

</ul>
</details>

**标签**: `#Solana`, `#JPMorgan`, `#institutional trading`, `#blockchain`, `#settlement`

---

<a id="item-11"></a>
## [Stripe 计划年底前将稳定币卡扩展至 100 多个国家](https://www.coindesk.com/business/2026/10/01/stripe-to-expand-stablecoin-cards-to-over-100-countries-by-the-end-of-the-year) ⭐️ 7.0/10

Stripe 宣布将在今年年底前把其由稳定币支持的卡片计划扩展到 100 多个国家，进一步推广允许企业发行以稳定币余额为资金的预付卡或借记卡的服务。此次扩展建立在 Stripe 的 Issuing 产品及其与稳定币基础设施公司 Bridge 的合作之上，Stripe 已于 2025 年收购 Bridge。 这标志着与加密货币挂钩的支付卡最大规模的主流推广之一，可能让数十个新市场的企业无需先兑换成当地法币即可持有和使用稳定币余额。它表明机构对稳定币作为结算渠道的接受度日益提高，并可能重塑开发者和平台集成跨境支付解决方案的方式。 Stripe Issuing 与 Bridge 合作支持以稳定币余额为资金的卡片计划，并可连接 Bridge 托管钱包、Privy 非托管钱包或其他第三方钱包。这些卡片以预付卡或借记卡形式发行，此次扩展旨在让平台更容易进入新市场。

rss · CoinDesk · Oct 5, 13:46

**背景**: 稳定币是一种旨在通过储备资产或算法机制，相对于某一参考资产（最常见的是美元）保持价值稳定的加密货币。USDT 和 USDC 等稳定币越来越多地用于支付和跨境转账，但它们并不总是完全稳定，且受到日益严格的监管。Stripe 的 Issuing 产品让平台能够创建和管理卡片计划，通过以稳定币余额为其提供资金，它在加密资产持有与传统卡网络之间架起了桥梁。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.stripe.com/issuing/stablecoin-cards">Stablecoin -backed card issuing | Stripe Documentation</a></li>
<li><a href="https://docs.stripe.com/issuing/bridge-stablecoin-cards">Stablecoin -backed cards for Bridge, Privy, or third-party wallets</a></li>
<li><a href="https://en.wikipedia.org/wiki/Stablecoin">Stablecoin</a></li>

</ul>
</details>

**标签**: `#fintech`, `#stablecoins`, `#payments`, `#cryptocurrency`, `#stripe`

---

<a id="item-12"></a>
## [ZachXBT 花费 35 万美元假扮 Lazarus 关联中国洗钱团伙客户](https://decrypt.co/380092/zachxbt-fronted-350k-pose-client-lazarus-chinese-crypto-launderers) ⭐️ 7.0/10

链上调查员 ZachXBT 披露，他垫付了 349,700 美元假扮一个与中国洗钱团伙有关联的客户，并按每笔订单支付 5% 的手续费，从而实时追踪 Lazarus 集团窃取的 Bybit 资金。这次行动使他能够监控从 Bybit 盗取的约 15 亿美元资金在洗钱网络中的流动。 这是区块链取证中一种新颖的卧底技术，超越了被动的链上分析，主动渗透到国家支持的黑客所使用的洗钱管道中。它可能为执法部门和交易所提供可操作的情报，揭示 Lazarus 如何将盗取的加密货币转换为法币，从而有可能破坏朝鲜未来的盗窃行动。 据 ZachXBT 所述，他为维持伪装，按每笔订单支付 5% 的佣金，并垫付了近 35 万美元的自有资金。此次行动针对的是与 Lazarus 集团 Bybit 盗窃案（估计超过 15 亿美元）具体关联的中国洗钱者。

rss · Decrypt · Oct 5, 18:46

**背景**: ZachXBT 是一位化名区块链调查员，以追踪加密货币骗局、黑客攻击和非法资金流动而闻名。Lazarus 集团是一个与朝鲜政府有关联的黑客组织（也被追踪为 APT38），被指责实施了多起备受瞩目的加密货币盗窃案，包括 2025 年 2 月盗取超过 15 亿美元的 Bybit 黑客事件。Bybit 是一家总部位于迪拜的中心化交易所，按交易量计算是全球最大的交易所之一。洗钱团伙通常位于中国，帮助此类组织将盗取的加密货币转换为干净资金。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.bleepingcomputer.com/news/security/north-korean-hackers-linked-to-15-billion-bybit-crypto-heist/">North Korean hackers linked to $1.5 billion ByBit crypto heist</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lazarus_Group">Lazarus Group - Wikipedia</a></li>

</ul>
</details>

**标签**: `#blockchain-forensics`, `#cryptocurrency`, `#cybercrime`, `#Lazarus Group`, `#money-laundering`

---

<a id="item-13"></a>
## [CFTC 提出针对杠杆零售加密货币交易的新联邦监管框架](https://www.theblock.co/news/markets/2026-10-05-cftc-rulemaking-leveraged-retail-crypto-trading-regulation-ctx-cam-417701) ⭐️ 7.0/10

美国商品期货交易委员会（CFTC）已启动规则制定程序，拟为杠杆和保证金零售加密货币交易建立联邦监管框架，提出《CTX 条例》和《CAM 条例》草案，并引入新的"加密资产市场"交易所认定类别。该机构正就该框架公开征求意见，该框架将为加密货币交易所设立一种新的联邦牌照，并以是否提供杠杆产品作为触发监管的门槛。 这是 CFTC 首次专门针对加密市场结构制定规则，可能将杠杆零售加密货币交易纳入注册交易所的监管范围，并重塑交易所在美国的运营方式。这对加密货币交易所、零售交易者以及更广泛的金融科技生态都具有重要意义，尤其是在 SEC 同步推进加密规则制定、多个机构竞相争取在 2027 年 1 月 18 日生效日期前完成规则的背景下。 《CTX 条例》和《CAM 条例》将为提供这些加密资产交易的 CFTC 注册交易所设定要求，且与《Clarity Act》不同，它们不会强制要求加密资产必须在 CFTC 注册平台上交易。值得注意的是，该框架刻意将现货市场排除在外，而现货市场是交易量最大的类别；此外，拟议规则旨在为从事比特币和以太坊交易的交易所建立一个自愿性的联邦框架。

rss · The Block · Oct 5, 16:09

**背景**: CFTC 是美国监管衍生品市场（包括期货和掉期）的联邦机构，而 SEC 则负责监管证券市场。杠杆交易允许交易者借入资金以放大头寸，从而同时增加潜在收益和风险，而零售加密货币杠杆在美国一直处于监管灰色地带。"加密资产市场"认定将创建一种新的注册交易场所类别，链上和离岸交易所都有可能寻求进入该类别。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.theblock.co/news/markets/2026-10-05-cftc-rulemaking-leveraged-retail-crypto-trading-regulation-ctx-cam-417701">CFTC proposes new federal framework for leveraged retail ...</a></li>
<li><a href="https://www.forexcrunch.com/blog/2026/10/06/cftc-ctx-cam-sec-parallel-crypto-rulebooks/">CFTC and SEC write parallel crypto rulebooks as CTX and CAM ...</a></li>
<li><a href="https://forkast.news/the-cftc-builds-its-first-crypto-market-structure-and-deliberately-leaves-the-spot-market-outside/">The CFTC Builds Its First Crypto Market Structure — And ...</a></li>

</ul>
</details>

**标签**: `#crypto regulation`, `#CFTC`, `#leveraged trading`, `#fintech`, `#policy`

---

<a id="item-14"></a>
## [Example.com 改版导致自动化测试失效，引发海勒姆定律讨论](https://www.debugbear.com/blog/example-dot-com-redesign-history) ⭐️ 6.0/10

长期被开发者用作测试占位符的 Example.com 域名，近日进行了数十年来首次重大改版，改变了其原本稳定的页面内容。这一变化导致大量依赖该网站经典设计的自动化测试失效，引发了社区关于测试脆弱性和变通方案的讨论。 这一事件凸显了海勒姆定律在现实中的影响：即使一个明确声明“非服务”的网站，也可能成为无数测试套件事实上的依赖。它提醒开发者应避免在自动化测试中依赖外部不可控资源，并考虑更健壮的测试策略。 据社区观察，此次改版移除了渐进的透明度过渡效果，现在直接显示所有语言且没有 CSS 动画。一位社区成员提供了一个公共测试服务器，可精确复现经典设计，开发者只需更新测试 URL 即可恢复功能。

hackernews · jgx0 · Oct 5, 22:55 · [社区讨论](https://news.ycombinator.com/item?id=49971921)

**背景**: Example.com 是由 IANA 维护的保留域名，旨在用于文档和示例中，无需申请许可。由于其内容多年保持静态，开发者常将其用作自动化测试中的可靠端点，尽管有警告称它并非一项服务。海勒姆定律指出，当用户足够多时，系统的所有可观察行为都会成为依赖，即使这些行为并非有意设计。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.hyrumslaw.com/">Hyrum ' s Law</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hyrum's_Law">Hyrum's Law</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了无奈与幽默交织的情绪，指出这是海勒姆定律的典型例证，并承认许多测试本就脆弱。一位用户分享了一个可复现旧设计的公共测试服务器作为变通方案，另一位则指出语言切换动画已被移除。还有人分享了此前 Hacker News 上的相关讨论链接。

**标签**: `#example.com`, `#redesign`, `#testing`, `#Hyrum's Law`, `#web development`

---

<a id="item-15"></a>
## [开发者从 Deno 回归 Node，引发运行时之争](https://dbushell.com/2026/10/03/deno-to-node/) ⭐️ 6.0/10

一位开发者发表了题为《与 Deno 的友谊结束了，现在 Node 是我最好的朋友》的博客文章，讲述了自己从 Deno 运行时迁回 Node.js 的个人经历。该文章在 Hacker News 上引发了细致讨论，涉及 Deno 的衰落迹象、Bun 的崛起以及三大 JavaScript 运行时之间的取舍。 这一迁移故事反映了 JavaScript 运行时格局的更大变化：Deno 在裁员后势头似乎停滞，而 Bun 作为快速的 Node.js 替代方案正在获得关注。对于正在为新项目选择运行时的开发者来说，这很重要，尤其是 Node.js 仍是主流且稳定的默认选择。 评论者指出，Deno 内置的测试运行器、代码检查器和类型检查器仍是很大的便利，其网络级权限沙箱也是 Bun 或 Node 无法比拟的。但也有人担忧 Deno 在裁员后缺乏清晰的路线图和对外沟通。

hackernews · ibobev · Oct 5, 22:30 · [社区讨论](https://news.ycombinator.com/item?id=49971719)

**背景**: Deno 是由 Node.js 原创者 Ryan Dahl 创建的 JavaScript、TypeScript 和 WebAssembly 运行时，基于 V8 引擎和 Rust 构建。它旨在修复 Dahl 所称的 Node.js 设计缺陷，提供安全默认值和内置工具。Bun 是较新的、基于 JavaScriptCore 的更快运行时，而 Node.js 仍是服务端 JavaScript 长期以来的标准。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Deno_(software)">Deno (software) - Wikipedia</a></li>
<li><a href="https://bun.sh/">Bun — A fast all-in-one JavaScript runtime</a></li>
<li><a href="https://betterstack.com/community/guides/scaling-nodejs/nodejs-vs-deno-vs-bun/">Node . js vs Deno vs Bun : Comparing ... | Better Stack Community</a></li>

</ul>
</details>

**社区讨论**: 讨论总体上对 Deno 表示同情，但对其方向提出批评：一位前承包商感叹裁员后缺乏路线图和沟通，而其他人则称赞 Deno 的沙箱机制在“智能体时代”至关重要，并看重其一体化工具链。多位评论者表示，除非涉及沙箱需求，否则现在更偏好 Bun 而非 Deno；还有人指出 TypeScript 源自微软，是一个理念上的症结。

**标签**: `#Deno`, `#Node.js`, `#Bun`, `#JavaScript`, `#TypeScript`

---

<a id="item-16"></a>
## [博客称 Common Lisp 是当下最适合 LLM 辅助编程的语言](https://www.vivienhenz.com/common-lisp) ⭐️ 6.0/10

Vivien Henz 的一篇博客文章提出，Common Lisp 如今是最佳编程语言，理由是 LLM 能够充分利用其宏（macros）和 REPL 驱动开发等独特特性。这一观点在 Hacker News 上引发了关于 LLM 时代语言选择的细致讨论。 这场争论反映出开发者评估编程语言的标准正在发生更广泛的转变：不再只看人类使用是否顺手，还要看 LLM 在该语言中编写、测试和迭代代码的效果如何。如果与 LLM 的契合度成为主要选择标准，未来几年语言的兴衰格局可能因此改变。 文章的核心论点建立在两大支柱上：Common Lisp 的异常系统允许在不展开调用栈的情况下从错误中恢复，以及其宏系统可用于构建领域特定语言（DSL）。评论者对此提出反驳，指出 Python 和 Node 同样支持在异常处暂停而不展开栈，而且前沿 LLM 在“宏生成宏”的场景下仍会严重出错。

hackernews · misterchocolat · Oct 6, 02:51 · [社区讨论](https://news.ycombinator.com/item?id=49973598)

**背景**: Common Lisp 是 Lisp 的一种方言，使用 S 表达式同时表示代码和数据结构，其宏系统允许程序员在编译期转换代码，从而有效扩展语言语法。REPL 驱动开发指程序员在运行中的环境里交互式地求值代码，获得即时反馈，而不必经历缓慢的编译—运行循环。LLM 指 GPT-4、Claude 等大语言模型，它们正越来越多地被用于生成和修改代码。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Common_Lisp">Common Lisp - Wikipedia</a></li>
<li><a href="https://lisp-docs.github.io/docs/tutorial/macros">Macros | Common Lisp Docs</a></li>
<li><a href="https://mikelevins.github.io/posts/2020-12-18-repl-driven/">On repl - driven programming - by mikel evins</a></li>

</ul>
</details>

**社区讨论**: 评论者普遍对“我的语言最适合 LLM”这类论调持怀疑态度，指出 Python、JavaScript、Rust、Julia 和 Clojure 的拥趸都能以不同理由提出类似主张。一些实践者分享了在 Julia 和 Clojure nREPL 工作流中使用 LLM 的良好体验，但也有人警告 LLM 在嵌套宏上可能灾难性失败，还有评论者认为文章把 DSL 的好处与 Common Lisp 本身的好处混为一谈。

**标签**: `#Common Lisp`, `#LLM`, `#Programming Languages`, `#Macros`, `#REPL`

---

<a id="item-17"></a>
## [以太坊 Glamsterdam 测试网在容量跃升前获最后一刻修复](https://www.coindesk.com/tech/2026/10/06/ethereum-s-glamsterdam-test-gets-last-minute-fix-before-major-capacity-jump) ⭐️ 6.0/10

以太坊 Glamsterdam 测试网在重大容量提升前获得了最后一刻的修复，这标志着网络在可扩展性改进方面取得了进展。该修复在升级的主要吞吐量提升激活之前被应用于测试网络。 Glamsterdam 是以太坊的下一个重大协议里程碑，预计在 2026 年上半年推出，旨在为下一代扩容扫清道路。测试网的顺利修复降低了主网升级延迟的风险，而主网升级将影响所有以太坊用户和二层网络。 该修复解决了在启用容量提升之前于测试网上发现的问题，不过现有内容未详细说明该漏洞的具体技术性质。Glamsterdam 之后预计将在 2026 年底推出 Hegota 升级。

rss · CoinDesk · Oct 6, 04:49

**背景**: 以太坊是一个去中心化的区块链平台，其日益增长的受欢迎程度不断触及容量上限，推高了交易成本并催生了对扩容方案的需求。测试网是用于在主网上线前试验协议变更的独立网络，因此在那里发现的问题可以在不危及真实资金的情况下得到修复。Glamsterdam 是以太坊即将推出的升级名称，旨在改善一层扩容及相关协议机制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://ethereum.org/roadmap/glamsterdam/">Glamsterdam | ethereum .org</a></li>
<li><a href="https://www.binance.com/en/ethereum-upgrade">What is the Ethereum Glamsterdam Upgrade ? | Binance</a></li>
<li><a href="https://ethereum.org/developers/docs/scaling/">Scaling - ethereum.org</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#blockchain`, `#scalability`, `#testnet`, `#cryptocurrency`

---

<a id="item-18"></a>
## [超过 60 只美股（含英伟达和特斯拉）即将上链](https://www.coindesk.com/markets/2026/10/05/more-than-60-u-s-stocks-including-nvidia-and-tesla-are-headed-onchain-here-s-how-it-works) ⭐️ 6.0/10

包括英伟达和特斯拉在内的 60 多只美国股票正在被代币化并带上链，文章解释了其背后的运作机制。这标志着现实世界资产代币化向主要美国股票的重要扩展。 这一发展连接了传统金融与去中心化金融（DeFi），可能使主要股票实现 24/7 交易、碎片化所有权和 DeFi 集成。它可能显著影响散户和机构投资者获取美国股票的方式。 代币化股票通常由托管人持有的真实股票 1:1 支持，在链上追踪股票价格，并支持碎片化所有权，但通常不附带投票权。该机制涉及资产选择、托管、代币发行和二级市场管理。

rss · CoinDesk · Oct 5, 17:18

**背景**: 代币化股票是代表传统股票的区块链代币，通过将真实股票转换为区块链上的数字代币而创建。这一过程被称为现实世界资产（RWA）代币化，旨在将区块链的优势——如 24/7 交易、更快结算和碎片化所有权——带给传统金融资产。将英伟达和特斯拉等主要美国股票代币化的举措反映了传统金融与 DeFi 融合的日益增长的趋势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://chain.link/article/onchain-stocks-tokenized-equities">Onchain Stocks: Tokenized Equities Explained | Chainlink</a></li>
<li><a href="https://debridge.com/learn/guides/tokenized-stocks-explained/">Tokenized Stocks Explained: How Equities Trade Onchain</a></li>
<li><a href="https://www.definitive.fi/blog/onchain-stock-trading-guide">Onchain Stock Trading: How It Works in 2026 — Definitive</a></li>

</ul>
</details>

**标签**: `#tokenization`, `#blockchain`, `#stocks`, `#DeFi`, `#traditional finance`

---

<a id="item-19"></a>
## [CFTC 加入 SEC 提出加密监管规则，现货市场监管缺口仍存](https://www.coindesk.com/policy/2026/10/05/u-s-cftc-joins-sec-in-proposing-crypto-regulations-though-spot-market-gap-lingers) ⭐️ 6.0/10

2026 年 10 月 5 日，美国商品期货交易委员会（CFTC）发布了一份拟议规则制定的预先通知，就依据《商品交易法》第 2(c)(2)(D)条对涉及加密资产的零售商品交易建立全面监管框架征求公众意见。此前，美国证券交易委员会（SEC）已于 2026 年 8 月 18 日提出“加密资产监管条例”，为加密资产创设量身定制的发行豁免和投资合同安全港。 两家机构并行推进，表明美国联邦层面正协调一致地将加密资产纳入现有监管框架，这可能降低交易所和代币发行方面临的法律不确定性。然而，由于 CFTC 的提案主要针对杠杆化的零售商品交易而非现金现货市场，加密现货交易仍存在显著的监管缺口。 CFTC 的通知属于早期征求意见阶段而非最终规则，且专门针对《商品交易法》第 2(c)(2)(D)条下涉及加密资产的零售商品交易。SEC 同步提出的“加密资产监管条例”包含《1933 年证券法》下的两项注册豁免以及投资合同安全港，但两项提案均未完全填补现货市场的监管缺口。

rss · CoinDesk · Oct 5, 15:54

**背景**: 在美国，加密监管长期由负责证券的 SEC 和负责商品及衍生品的 CFTC 分头管辖。CFTC 历来仅通过反欺诈和反操纵权限间接监管加密现货市场，而 SEC 则将许多代币发行认定为证券并主张管辖权。SEC 的“加密资产监管条例”和 CFTC 的最新通知，是厘清这一管辖边界并制定适用规则的最新尝试。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.cftc.gov/PressRoom/PressReleases/9307-26">CFTC Seeks Public Comment on Advanced Notice of Proposed ...</a></li>
<li><a href="https://www.sec.gov/newsroom/press-releases/2026-76-sec-proposes-new-regulation-crypto-assets">SEC Proposes New Regulation Crypto Assets</a></li>
<li><a href="https://www.reuters.com/world/us-commodities-regulator-proposes-new-federal-crypto-oversight-rules-2026-10-05/">US commodities regulator proposes new federal crypto ...</a></li>

</ul>
</details>

**标签**: `#crypto`, `#regulation`, `#CFTC`, `#SEC`, `#policy`

---

<a id="item-20"></a>
## [美国财政部制裁为哈马斯筹集 200 万美元的加密货币网络](https://www.coindesk.com/policy/2026/10/05/treasury-crackdown-exposes-crypto-s-role-in-usd2-million-hamas-fundraising-network) ⭐️ 6.0/10

据 CoinDesk 报道，美国财政部曝光并制裁了一个被哈马斯使用的加密货币筹款网络，该网络筹集了约 200 万美元。此次行动锁定了与这一巴勒斯坦武装组织数字资产筹款活动相关的具体链上钱包和中介机构。 这一执法行动凸显了数字资产已成为规避制裁和恐怖主义融资的主流渠道，推动区块链分析和合规工具进入国家安全政策的核心。它表明美国监管机构将日益把加密钱包和交易所视为受制裁执法约束的关键基础设施。 此次打击依赖区块链分析技术来追踪交易图谱、聚类地址并将资金归属到已知实体——这些技术被 Chainalysis、Elliptic 和 TRM Labs 等公司使用。相对有限的 200 万美元金额表明，即便是小规模的加密筹款网络如今也处于财政部制裁的范围之内。

rss · CoinDesk · Oct 5, 11:08

**背景**: 区块链分析是对比特币和以太坊等公共账本进行取证式检查，以追踪资金流向并识别交易背后的行为主体，被广泛用于加密合规和调查。加密货币制裁规避指的是通过跨境或中介转移价值以降低对制裁管控的可见性，这是受制裁团体越来越多使用的手段。联合国反恐怖主义委员会估计，加密货币可能为多达 20%的恐怖袭击提供资金，使其成为全球安全关注的活跃领域。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Blockchain_analysis">Blockchain analysis</a></li>
<li><a href="https://nhimg.org/glossary/cryptocurrency-sanctions-evasion/">What Is Cryptocurrency Sanctions Evasion? Definition</a></li>
<li><a href="https://www.youngausint.org.au/post/how-cryptocurrency-is-taking-terrorism-digital">How Cryptocurrency is Taking Terrorism Digital</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#national-security`, `#terrorism-financing`, `#blockchain-analytics`

---

<a id="item-21"></a>
## [以太坊质押队列延长至两周，150 万 ETH 排队等待](https://www.coindesk.com/tech/2026/10/05/ethereum-has-a-25-day-wait-to-start-staking-with-nearly-1-5-million-eth-in-line) ⭐️ 6.0/10

以太坊的质押退出队列已延长至约两周，而进入队列目前需要等待约 25 天才能开始质押，排队中的 ETH 接近 150 万枚。退出队列一度触及 2026 年高点，接近 80 万枚 ETH，主要由 MetaMask Staking 撤出约 1.7 万个验证者所推动。 这种拥堵凸显了以太坊受速率限制的验证者流动机制可能将价值数十亿美元的 ETH 锁定数周，影响投资者的流动性和质押经济。这也反映出需求动态的变化：进入队列已从 9 月初的约 200 万 ETH 降温，而退出压力则出现飙升。 以太坊对每个 epoch 可处理的 ETH 数量设有流动速率限制，这就是为什么尽管普通交易只需几秒即可确认，进入和退出队列仍会形成。在 MetaMask 验证者撤出后，退出队列已回落至约 767,349 枚 ETH，而 25 天的进入队列仍表明存在潜在的质押需求。

rss · CoinDesk · Oct 5, 06:40

**背景**: 以太坊的权益证明网络依赖验证者，每个验证者需锁定 32 枚 ETH 来维护链的安全，而协议刻意限制验证者加入或退出的速度，以保护网络稳定性。这一被称为 churn（流动速率）的限制意味着大量 ETH 的流动——无论是新质押者还是退出者——都会形成需要数天甚至数周才能消化的队列。Shanghai/Capella 升级启用了质押提款功能，使这些队列成为衡量网络健康和投资者情绪的可见且备受关注的指标。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.validatorqueue.com/">Ethereum Validator Queue</a></li>
<li><a href="https://ethereum.org/staking/withdrawals/">Staking withdrawals - ethereum.org</a></li>
<li><a href="https://cryptobriefing.com/ethereum-exit-queue-eases-metamask-exits/">Ethereum exit queue eases to 767,349 ETH after MetaMask exits</a></li>

</ul>
</details>

**标签**: `#Ethereum`, `#Staking`, `#Blockchain`, `#Cryptocurrency`, `#Network Congestion`

---

<a id="item-22"></a>
## [美国 SEC 批准 3 倍杠杆比特币和以太坊基金](https://decrypt.co/380108/sec-clears-3x-leveraged-bitcoin-ethereum-funds) ⭐️ 6.0/10

美国证券交易委员会（SEC）批准了 Cboe 的一项规则，允许六只 Volatility Shares 3 倍杠杆基金在美国交易所上市，追踪比特币、以太坊、黄金、白银、石油和天然气。其中比特币和以太坊基金将追踪受监管的期货合约，而非直接持有加密货币。 这标志着美国监管机构首次允许 3 倍杠杆加密货币基金，打破了此前 2 倍杠杆的上限，表明加密货币衍生品市场进一步成熟。它为交易者提供了一种受监管的方式来放大比特币和以太坊的每日敞口，可能吸引更多机构和散户参与。 这些基金的结构为商品信托，因此不受《1940 年投资公司法》中适用于传统 ETF 的规则约束。由于杠杆每日重置，3 倍敞口仅在一个交易日内有效，期货展期可能导致长期回报与标的资产出现偏差。

rss · Decrypt · Oct 5, 18:12

**背景**: 杠杆 ETF 利用金融衍生品和债务来放大标的指数或资产的回报，通常提供每日表现的多倍收益。Volatility Shares 于 2023 年在美国推出了首只追踪比特币期货的杠杆加密货币 ETF，而现货比特币 ETF 在经历了十年的拒绝后于 2024 年 1 月获批。SEC 批准 Cboe 规则是允许这些新的 3 倍产品上市交易的程序性步骤。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/sec-clears-3x-leveraged-bitcoin-181228022.html">SEC Clears 3 x Leveraged Bitcoin and Ethereum Funds for Trading</a></li>
<li><a href="https://coingape.com/sec-approves-first-3x-leveraged-bitcoin-and-ethereum-etfs-in-the-us/">SEC Approves First 3 x Leveraged Bitcoin and Ethereum ETFs in the...</a></li>
<li><a href="https://unchainedcrypto.com/sec-clears-cboe-to-list-volatility-shares-3x-bitcoin-and-ether-funds/">SEC Clears Cboe to List Volatility Shares’ 3x Bitcoin and ...</a></li>

</ul>
</details>

**标签**: `#cryptocurrency`, `#regulation`, `#leveraged funds`, `#bitcoin`, `#ethereum`

---

<a id="item-23"></a>
## [美国独立社区银行家协会起诉 OCC，指加密货币借'侧门'进入银行体系](https://decrypt.co/380017/banking-group-sues-block-crypto-side-door-banking) ⭐️ 6.0/10

美国独立社区银行家协会（ICBA）已对货币监理署（OCC）提起诉讼，要求阻止该机构向加密货币公司发放国家信托牌照。ICBA 认为，这些牌照为加密企业提供了进入银行体系的'侧门'，却无需遵守约束传统银行的保障措施。 这起诉讼可能决定加密货币公司能否在不承担与传统银行相同监管义务的情况下获得联邦银行资质，从而可能重塑加密行业进入美国银行体系的方式。判决结果将同时影响寻求合法地位的加密企业和担忧不公平竞争的社区银行。 ICBA 主张，国会设立国家信托牌照并非为了让加密公司获得联邦银行牌照的可信度，却规避《社区再投资法》义务、并表监管、资本与流动性标准以及适用于参保存款机构的 FDIC 保险。OCC 的国家信托牌照是一种不允许吸收存款或发放贷款的联邦银行执照，在 2025 至 2026 年间已成为加密行业进入美国银行体系的主要入场券。

rss · Decrypt · Oct 4, 16:01

**背景**: OCC 国家信托牌照是一种不允许吸收存款或发放贷款的联邦银行执照；几十年来它一直服务于企业信托这一小众领域，但近来已成为加密和金融科技行业进入美国银行体系的主要入场券。美国独立社区银行家协会（ICBA）是美国小型银行的主要行业组织，代表约 5000 家社区银行。Paxos 和 Kraken 母公司 Payward 等加密公司已寻求或获得此类牌照，引发了传统银行的担忧。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://wiki.private.law/en/occ-trust-charter">OCC National Trust Charter : Bank Without Deposits</a></li>
<li><a href="https://en.wikipedia.org/wiki/Independent_Community_Bankers_of_America">Independent Community Bankers of America</a></li>
<li><a href="https://www.icba.org/w/occ-release-oct-2026">ICBA Sues OCC Over National Trust Bank Charters for Crypto Firms</a></li>

</ul>
</details>

**标签**: `#crypto`, `#banking`, `#regulation`, `#OCC`, `#policy`

---