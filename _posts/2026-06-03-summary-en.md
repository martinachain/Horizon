---
layout: default
title: "Horizon Summary: 2026-06-03 (EN)"
date: 2026-06-03
lang: en
---

> From 92 items, 21 important content pieces were selected

---

1. [VSCode Bug Enables 1-Click GitHub Token Theft](#item-1) ⭐️ 9.0/10
2. [Cost-Effective Image Indexing for RAG](#item-2) ⭐️ 8.0/10
3. [Anthropic Files for IPO Near $1 Trillion Valuation](#item-3) ⭐️ 8.0/10
4. [Microsoft Launches MAI-Code-1-Flash, a 137B Coding Model](#item-4) ⭐️ 7.0/10
5. [CT Scans Reveal High Build Quality of BYD Car Parts](#item-5) ⭐️ 7.0/10
6. [AI beats law professors in Stanford study](#item-6) ⭐️ 7.0/10
7. [HP Re-releases Classic HP-16C Programmer's Calculator](#item-7) ⭐️ 7.0/10
8. [Hyperliquid Predicted 80% of Oil Move Before Traditional Exchanges](#item-8) ⭐️ 7.0/10
9. [Microsoft Reveals '1,000x More Reliable' Quantum Chip, Raising Bitcoin Concerns](#item-9) ⭐️ 7.0/10
10. [Microsoft Turns OpenClaw Into Enterprise AI Agent Scout](#item-10) ⭐️ 7.0/10
11. [Nvidia Nemotron 3 Ultra: Best US Open Model, Still Trails China](#item-11) ⭐️ 7.0/10
12. [DuckDuckGo's 'No AI' Feature Gains Popularity](#item-12) ⭐️ 7.0/10
13. [Use Nvidia GPU VRAM as swap space on Linux](#item-13) ⭐️ 6.0/10
14. [Developer Shares First Month with Clojure](#item-14) ⭐️ 6.0/10
15. [US Treasury Sanctions Iranian Crypto Exchange Nobitex](#item-15) ⭐️ 6.0/10
16. [Trump Signs AI Executive Order with Voluntary Review](#item-16) ⭐️ 6.0/10
17. [Bitcoin Miner Hive Reports Revenue Surge, Bets on AI Boom](#item-17) ⭐️ 6.0/10
18. [Florida Sues OpenAI and Sam Altman Over ChatGPT Safety Claims](#item-18) ⭐️ 6.0/10
19. [Whitehat Recovers $2M in ETH Stuck Since 2016 ICO](#item-19) ⭐️ 6.0/10
20. [Galaxy Digital Launches OTC Prediction Market for Institutions](#item-20) ⭐️ 6.0/10
21. [Backpack Launches Hybrid Securities Platform](#item-21) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [VSCode Bug Enables 1-Click GitHub Token Theft](https://blog.ammaraskar.com/github-token-stealing/) ⭐️ 9.0/10

A critical vulnerability in VSCode's embedded web editor allows a malicious extension to steal a user's GitHub authentication token with a single click, as detailed in a comprehensive exploit writeup by security researcher Ammar Askar. This vulnerability exposes a significant attack surface for the millions of developers using VSCode's web editor, potentially leading to unauthorized access to private repositories and supply chain attacks. It also highlights ongoing challenges in securing integrated development environments against malicious extensions. The exploit bypasses VSCode's publisher trust system by using local workspace extensions, which are not subject to publisher screening, and circumvents Content Security Policy (CSP) restrictions by binding a shortcut to install extensions without publisher checks. The researcher reported the bug to Microsoft Security Response Center (MSRC) but described the experience as 'horrible', with the bug being silently fixed without proper acknowledgment.

hackernews · ammar2 · Jun 2, 15:29 · [Discussion](https://news.ycombinator.com/item?id=48371562)

**Background**: VSCode is a popular code editor with a rich extension ecosystem. The web editor version runs in a browser and is often signed into GitHub for seamless integration. Extensions can be installed from the marketplace or locally, with varying security checks. GitHub tokens grant access to repositories and are a high-value target for attackers.

<details><summary>References</summary>
<ul>
<li><a href="https://code.visualstudio.com/docs/configure/extensions/extension-runtime-security">Extension runtime security - Visual Studio Code</a></li>
<li><a href="https://blog.palantir.com/managing-and-securing-vs-code-extensions-at-scale-b75b2cf72b02">Managing and Securing VS Code Extensions at Scale</a></li>
<li><a href="https://blog.gitguardian.com/how-hackers-used-stolen-github-oauth-tokens/">How Hackers Used Stolen GitHub Tokens to Access Private Source Code</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights frustration with MSRC's handling of the report, with one commenter noting that MSRC has 'figured out that researchers will report for free regardless'. Another user shared a personal experience of token theft, emphasizing the importance of damage segregation and assuming tokens will eventually leak. A technical commenter sought clarification on the exploit chain, particularly how the shortcut trick bypasses CSP.

**Tags**: `#security`, `#vscode`, `#github`, `#vulnerability`, `#token-theft`

---

<a id="item-2"></a>
## [Cost-Effective Image Indexing for RAG](https://www.kapa.ai/blog/how-we-index-images-for-rag) ⭐️ 8.0/10

Kapa.ai proposes indexing images by generating text descriptions with a cheap vision model at indexing time, rather than using multimodal models at query time. This approach significantly reduces query-time latency and cost, making RAG systems more practical for applications with many images. The method stores image descriptions as text chunks, enabling retrieval alongside ordinary text without sending images to the model at query time.

hackernews · mooreds · Jun 2, 16:13 · [Discussion](https://news.ycombinator.com/item?id=48372239)

**Background**: Retrieval-Augmented Generation (RAG) combines retrieval of relevant documents with a language model to generate answers. Multimodal RAG extends this to images, but using multimodal models at query time is expensive and slow. Indexing-time description generation offers a cheaper alternative.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@nay1228/data-indexing-in-rag-architecture-implementation-applications-a35394660658">RAG & Data Indexing: A Deep Dive | Medium</a></li>
<li><a href="https://developer.nvidia.com/blog/an-easy-introduction-to-multimodal-retrieval-augmented-generation/">An Easy Introduction to Multimodal Retrieval-Augmented Generation | NVIDIA Technical Blog</a></li>

</ul>
</details>

**Discussion**: Commenters generally agree with the approach, noting they have used similar strategies. Concerns include non-determinism of LLMs causing new models to reveal different information, and the need for authors to update captions.

**Tags**: `#RAG`, `#image indexing`, `#LLM`, `#cost optimization`, `#retrieval`

---

<a id="item-3"></a>
## [Anthropic Files for IPO Near $1 Trillion Valuation](https://decrypt.co/369641/ai-giant-anthropic-files-go-public-nearing-1-trillion-valuation) ⭐️ 8.0/10

AI company Anthropic, creator of the Claude model, has confidentially filed for an initial public offering (IPO) in the United States after nearing a $1 trillion valuation. This IPO filing marks a major milestone for the AI industry, signaling strong market validation and potentially influencing AI development, regulation, and investment trends globally. The filing is confidential under the U.S. JOBS Act, meaning financial details are not yet public. Anthropic recently completed another large funding round that pushed its valuation toward $1 trillion.

rss · Decrypt · Jun 1, 16:09

**Background**: Anthropic is an AI safety and research company founded by former OpenAI employees. Its flagship product, Claude, is a large language model competing with OpenAI's GPT and Google's Gemini. An IPO would provide Anthropic with public capital to scale operations and compete in the rapidly growing AI market.

**Tags**: `#Anthropic`, `#IPO`, `#AI`, `#funding`, `#industry news`

---

<a id="item-4"></a>
## [Microsoft Launches MAI-Code-1-Flash, a 137B Coding Model](https://microsoft.ai/news/introducingmai-code-1-flash/) ⭐️ 7.0/10

Microsoft has released MAI-Code-1-Flash, a 137B parameter Mixture-of-Experts (MoE) coding model with a 256K token context window, trained on over 10 trillion tokens. It is now available in GitHub Copilot for Visual Studio Code. This model represents Microsoft's push to compete in the AI coding assistant space, but community benchmarks suggest it only matches or slightly outperforms much smaller models like Qwen3.6-35B-A3B, raising questions about its efficiency and cost-effectiveness. The launch also signals Microsoft's strategy to build a model ecosystem beyond Azure, with availability on third-party platforms like Fireworks AI and OpenRouter. MAI-Code-1-Flash uses adaptive solution length control to adjust response depth based on task complexity. It achieves 51% on SWE-bench Pro, compared to 49.5% for Qwen3.6-35B-A3B, but the community notes that Claude Haiku, which it benchmarks against, is not a strong competitor.

hackernews · EvanZhouDev · Jun 2, 18:47 · [Discussion](https://news.ycombinator.com/item?id=48374466)

**Background**: Large language models for code generation have become a key battleground for AI companies, with models like GPT-4, Claude, and Qwen competing. Mixture-of-Experts (MoE) architectures allow models to have a large total parameter count while activating only a subset per token, enabling faster inference and lower cost. GitHub Copilot is a popular AI coding assistant that integrates with IDEs like VS Code.

<details><summary>References</summary>
<ul>
<li><a href="https://microsoft.ai/news/introducingmai-code-1-flash/">Introducing MAI-Code-1-Flash | Microsoft AI</a></li>
<li><a href="https://microsoft.ai/pdf/MAI-Code-1-Flash-Model-Card.PDF">PDF MAI-Code-1-Flash model card - microsoft.ai</a></li>
<li><a href="https://dev.to/akaranjkar08/microsoft-mai-thinking-1-mai-code-1-flash-developer-guide-to-7-new-mai-models-k4m">Microsoft MAI-Thinking-1 & MAI-Code-1-Flash: Developer Guide ...</a></li>

</ul>
</details>

**Discussion**: Community comments are largely critical: users point out that the 137B model barely outperforms a 35B model on SWE-bench Pro, and question the value of such a large model for coding tasks. Some express frustration with Microsoft's pricing changes for Copilot and the perceived gap between marketing claims and actual performance.

**Tags**: `#AI`, `#coding`, `#Microsoft`, `#model`, `#benchmark`

---

<a id="item-5"></a>
## [CT Scans Reveal High Build Quality of BYD Car Parts](https://www.lumafield.com/scan-of-the-month/byd) ⭐️ 7.0/10

Lumafield published industrial CT scans of BYD car components, showing detailed internal structures that indicate high build quality and challenging the stereotype that Chinese cars are poorly made. This analysis provides objective evidence that BYD, the world's largest plug-in electric vehicle manufacturer, produces components with quality comparable to or exceeding traditional automakers, potentially shifting consumer perceptions and competitive dynamics in the automotive industry. The CT scans reveal robust construction in control arms, subframes, and powertrain components, and include a detailed view of a key fob with a mechanical backup key. The scans were performed by Lumafield, a company specializing in industrial CT scanning for manufacturing quality.

hackernews · viasfo · Jun 2, 20:30 · [Discussion](https://news.ycombinator.com/item?id=48375824)

**Background**: Industrial CT scanning uses X-rays to create 3D images of a component's internal and external structures without damaging it, allowing engineers to inspect hidden defects and assess build quality. BYD is a vertically integrated Chinese conglomerate that produces over 75% of its vehicle components in-house, including batteries, motors, and electronics, a level of integration not seen since early Ford.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/BYD_Company">BYD Company</a></li>
<li><a href="https://www.lumafield.com/article/what-industrial-ct-scanning-does-for-manufacturing-quality">What Industrial CT Scanning Does for Manufacturing Quality</a></li>

</ul>
</details>

**Discussion**: Community comments largely agree with the positive assessment, with a master technician noting the heavy-duty construction of BYD parts. One user corrected a detail about the key fob design, while others highlighted BYD's vertical integration and scale, comparing it favorably to Ford and Tesla.

**Tags**: `#BYD`, `#automotive`, `#CT scan`, `#manufacturing`, `#electric vehicles`

---

<a id="item-6"></a>
## [AI beats law professors in Stanford study](https://law.stanford.edu/press/ai-outperforms-law-professors-in-stanford-law-study/) ⭐️ 7.0/10

A Stanford Law study found that law professors preferred AI-generated answers to student contract law questions 75% of the time over human-written ones. This suggests AI could serve as an effective tutor for law students, potentially lowering the cost of legal education, but also raises concerns about over-reliance on AI in legal training and practice. The study involved only 16 law professors, leading to criticism about statistical power and high variance in the results.

hackernews · berlianta · Jun 2, 23:43 · [Discussion](https://news.ycombinator.com/item?id=48377761)

**Background**: Large language models (LLMs) like GPT-4 are increasingly used in legal contexts for drafting documents and answering questions. This study specifically tested whether AI could generate answers that law professors would judge as better than those written by students, with implications for using AI as a tutoring tool.

<details><summary>References</summary>
<ul>
<li><a href="https://www.forbes.com/sites/aliciapark/2026/06/02/stanford-study-finds-ai-beats-law-professors-75-of-the-time/">AI Beat Law Professors At Answering Questions, Study Finds—And It...</a></li>
<li><a href="https://news.ycombinator.com/item?id=48377761">AI outperforms law professors in Stanford Law study | Hacker News</a></li>

</ul>
</details>

**Discussion**: Community comments were critical of the study's methodology, noting the small sample size (16 professors) and high variance, which undermines statistical significance. Some commenters pointed out that the study focuses on AI as a tutor, not as a replacement for lawyers, and that the results could still be socially positive for legal education.

**Tags**: `#AI`, `#legal`, `#education`, `#LLM`, `#research`

---

<a id="item-7"></a>
## [HP Re-releases Classic HP-16C Programmer's Calculator](https://hpcalcs.com/product/hp-16c-collectors-edition/) ⭐️ 7.0/10

HP has re-released the HP-16C programmer's calculator as a Collector's Edition, featuring the classic Voyager design with modern programming functions. This re-release revives a beloved tool for retro computing enthusiasts and programmers, sparking discussions about nostalgia, build quality, and modern alternatives like SwissMicros. The HP-16C Collector's Edition is available for pre-order at $129.99, while the original model was produced from 1982 to 1989. Some community members express concerns about build quality based on issues with the previous 15C Collector's Edition.

hackernews · dm319 · Jun 2, 19:02 · [Discussion](https://news.ycombinator.com/item?id=48374685)

**Background**: The HP-16C Computer Scientist is a programmable pocket calculator designed for computer programmers, featuring bitwise operations like AND, OR, NOT, shifts, and rotates. It uses Reverse Polish Notation (RPN) and is part of the HP Voyager series. SwissMicros produces modern clones like the DM16L that emulate the original HP-16C.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HP-16C">HP-16C - Wikipedia</a></li>
<li><a href="https://hpcalcs.com/product/hp-16c-collectors-edition/">HP 16c Collector's Edition - HP Calc</a></li>
<li><a href="https://en.wikipedia.org/wiki/SwissMicros">SwissMicros</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: some users express excitement and nostalgia, while others question the build quality and recommend SwissMicros alternatives. One commenter notes that the reissue is a good deal compared to inflation-adjusted original prices.

**Tags**: `#HP calculators`, `#retro computing`, `#hardware`, `#programmer tools`

---

<a id="item-8"></a>
## [Hyperliquid Predicted 80% of Oil Move Before Traditional Exchanges](https://www.coindesk.com/markets/2026/06/02/hyperliquid-predicted-80-of-an-oil-market-move-before-traditional-exchanges-even-opened-says-td-securities) ⭐️ 7.0/10

A TD Securities report claims that Hyperliquid's prediction market accurately forecast 80% of an oil price movement before traditional exchanges opened, demonstrating the platform's potential for price discovery in real-world assets. This marks a significant validation of crypto prediction markets for traditional finance, suggesting they can provide earlier and more accurate price signals than conventional exchanges, potentially influencing how institutions approach market analysis. The report from TD Securities, a major investment bank, specifically highlights Hyperliquid's performance in predicting oil price moves, though the exact methodology and timeframe of the prediction were not disclosed.

rss · CoinDesk · Jun 2, 16:02

**Background**: Prediction markets allow users to trade on the outcome of future events, using financial incentives to aggregate information. Hyperliquid is a decentralized platform that launched prediction markets for off-chain events like CPI data and Fed rate decisions via its HIP-4 proposal. These markets are increasingly seen as tools for real-time price discovery, often outperforming traditional polling and surveys.

<details><summary>References</summary>
<ul>
<li><a href="https://www.mexc.com/learn/article/what-are-hyperliquid-prediction-markets-hip-4-offchain-event-contracts-explained/1">What Are Hyperliquid Prediction Markets ? HIP-4 Offchain Event...</a></li>
<li><a href="https://crypto.com/us/research/prediction-markets-oct-2025">Prediction Markets: The Rise of Event-Driven Finance - Crypto.com</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#prediction markets`, `#oil`, `#price discovery`, `#DeFi`

---

<a id="item-9"></a>
## [Microsoft Reveals '1,000x More Reliable' Quantum Chip, Raising Bitcoin Concerns](https://decrypt.co/369811/microsoft-1000x-more-reliable-quantum-chip-bitcoin-threat-draws-nearer) ⭐️ 7.0/10

Microsoft announced Majorana 2, a quantum chip with topological qubits that are 1,000 times more reliable, and accelerated its roadmap to a practical quantum computer by 2029. This advancement brings quantum computing closer to breaking Bitcoin's cryptographic security, as recent research suggests quantum computers could threaten Bitcoin sooner than expected. Microsoft used AI to accelerate the development of Majorana 2, but some physicists have expressed skepticism about the chip's performance due to a lack of published evidence.

rss · Decrypt · Jun 3, 03:31

**Background**: Quantum computers use quantum mechanics to solve certain problems exponentially faster than classical computers. Bitcoin's security relies on cryptographic algorithms that are believed to be secure against classical attacks but could be broken by sufficiently powerful quantum computers. The timeline for such a threat remains uncertain, but recent papers from Google and others suggest it may arrive sooner than previously thought.

<details><summary>References</summary>
<ul>
<li><a href="https://quantum.microsoft.com/en-us/insights/blogs/majorana-2-scalable-quantum-processor">Microsoft Quantum | Majorana 2 – Microsoft's Scalable Quantum ...</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/quantum-computing/microsoft-announces-majorana-2-quantum-computing-chip-claims-a-practical-machine-will-come-in-2029">Microsoft announces Majorana 2 quantum computing chip ...</a></li>
<li><a href="https://www.forbes.com/sites/digital-assets/2026/03/31/google-finds-quantum-computers-could-break-bitcoin-sooner-than-expected/">Google Finds Quantum Computers Could Break Bitcoin Sooner ...</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#cryptography`, `#Bitcoin`, `#Microsoft`, `#security`

---

<a id="item-10"></a>
## [Microsoft Turns OpenClaw Into Enterprise AI Agent Scout](https://decrypt.co/369781/microsoft-scout-openclaw-enterprise-ai-agent) ⭐️ 7.0/10

Microsoft has launched Scout, an enterprise AI agent powered by the open-source OpenClaw, integrated into Microsoft 365. This brings autonomous task automation to 1.4 billion Windows users without requiring technical expertise. This move significantly expands the reach of OpenClaw, which already has 310k+ GitHub stars, by embedding it into the world's most widely used productivity suite. It could accelerate enterprise adoption of AI agents and set a precedent for open-source AI integration in mainstream software. Scout lives inside Microsoft 365, leveraging identity, credential, and access controls for enterprise safety. It automates tasks like meeting preparation, email management, and document review, accessible to non-technical users.

rss · Decrypt · Jun 2, 20:25

**Background**: OpenClaw is a free, open-source AI assistant that runs locally and can automate tasks across messaging platforms like WhatsApp, Telegram, and Discord using large language models. It has gained significant popularity among developers for its flexibility and autonomy. Microsoft's Scout adapts this capability for enterprise environments, adding security and compliance features.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/369781/microsoft-scout-openclaw-enterprise-ai-agent">Microsoft Turns OpenClaw Into an Enterprise AI Agent With Scout</a></li>
<li><a href="https://www.microsoft.com/en-us/microsoft-365/blog/2026/06/02/introducing-microsoft-scout-your-always-on-personal-agent/">Introducing Microsoft Scout : Your always-on personal agent</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenClaw">OpenClaw - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Microsoft`, `#AI Agents`, `#Enterprise`, `#OpenClaw`, `#Windows`

---

<a id="item-11"></a>
## [Nvidia Nemotron 3 Ultra: Best US Open Model, Still Trails China](https://decrypt.co/369689/nvidia-open-ai-model-nemotron-3-ultra) ⭐️ 7.0/10

Nvidia released Nemotron 3 Ultra, a 550B-parameter open-weight AI model with hybrid Mamba-Transformer MoE architecture, achieving top scores among American open models but lagging behind Chinese frontier models. This release marks Nvidia's strongest open-weight AI model, challenging the dominance of closed models and highlighting the competitive gap between US and Chinese AI development. The model has 550B total parameters with 55B active per token, uses a hybrid Mamba-Transformer mixture-of-experts architecture, and scores 48 on the Artificial Analysis Intelligence Index, serving over 300 tokens per second on a pre-release endpoint.

rss · Decrypt · Jun 1, 22:46

**Background**: Open-weight AI models have publicly available trained parameters, allowing developers to download and run them locally. Nvidia's Nemotron series competes with other open models like Llama and DeepSeek, while Chinese models such as DeepSeek have recently achieved frontier-level performance.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.nvidia.com/nemotron/nightly/usage-cookbook/Nemotron-3-Ultra-Base/README.html">NVIDIA Nemotron 3 Ultra — Base Model</a></li>
<li><a href="https://x.com/ArtificialAnlys/status/2061304911565144230">Nemotron 3 Ultra scores 48 on the Artificial Analysis Intelligence Index. This is well ahead of ...</a></li>
<li><a href="https://allthings.how/what-is-an-open-weight-ai-model-and-how-to-use-one/">What is an Open Weight AI Model and How to Use One</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Nvidia`, `#open-source`, `#model comparison`, `#Nemotron`

---

<a id="item-12"></a>
## [DuckDuckGo's 'No AI' Feature Gains Popularity](https://decrypt.co/369688/duckduckgo-no-ai-google) ⭐️ 7.0/10

DuckDuckGo launched Duck AI, but its 'No AI' feature, which returns traditional search results without AI-generated answers, has become unexpectedly popular among users. This trend signals growing user backlash against AI integration in search engines, highlighting a demand for simpler, privacy-focused search experiences. The 'No AI' option allows users to opt out of AI-generated summaries and see only organic web results, reflecting DuckDuckGo's commitment to user choice and privacy.

rss · Decrypt · Jun 1, 22:16

**Background**: Major search engines like Google have increasingly integrated AI-generated answers into search results, sometimes pushing organic links further down. DuckDuckGo, known for its privacy-first approach, initially introduced Duck AI but now sees stronger demand for a non-AI mode.

**Tags**: `#AI`, `#search engines`, `#user experience`, `#privacy`, `#DuckDuckGo`

---

<a id="item-13"></a>
## [Use Nvidia GPU VRAM as swap space on Linux](https://github.com/c0dejedi/nbd-vram) ⭐️ 6.0/10

A new open-source tool called nbd-vram allows Linux users to use Nvidia GPU VRAM as swap space, targeting laptops with soldered, non-upgradable memory. This provides a practical workaround for users stuck with limited RAM on laptops, leveraging idle GPU VRAM to improve system responsiveness under memory pressure. The tool uses NBD (Network Block Device) to create a swap device backed by VRAM, with sequential throughput around 1.3 GB/s on an RTX 3070 Laptop GPU. It automatically reduces VRAM allocation if the GPU is busy.

hackernews · tanelpoder · Jun 2, 22:55 · [Discussion](https://news.ycombinator.com/item?id=48377404)

**Background**: Swap space is a portion of storage used as an extension of RAM when memory is full. Using GPU VRAM as swap is niche because VRAM is typically reserved for graphics tasks, but on systems with abundant VRAM and limited RAM, it can offer lower latency than SSD swap.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/c0dejedi/nbd-vram">GitHub - c0deJedi/nbd-vram: Use your NVIDIA GPU's VRAM as swap space on Linux. Built for laptops with soldered memory and no upgrade path. If you have an RTX card sitting there with 8GB of VRAM and you're getting swapped to SSD, this puts that VRAM to work · GitHub</a></li>
<li><a href="https://wiki.archlinux.org/title/Swap_on_video_RAM">Swap on video RAM - ArchWiki</a></li>

</ul>
</details>

**Discussion**: Commenters noted that sequential throughput is slower than NVMe SSDs, but latency may be lower. Some raised concerns about Wayland dynamic VRAM allocation causing desktop crashes, while others saw value for machines with idle VRAM.

**Tags**: `#Linux`, `#GPU`, `#swap`, `#VRAM`, `#performance`

---

<a id="item-14"></a>
## [Developer Shares First Month with Clojure](https://www.acdw.net/clojure/) ⭐️ 6.0/10

A developer published a blog post detailing their initial impressions after using Clojure for about a month, including building a static site generator to power their own website. This personal account highlights Clojure's appeal for functional programming and its unique approach to simplicity, which may encourage other developers to explore the language and its ecosystem. The developer used Clojure to create a static site generator from scratch, leveraging macros for a custom templating engine, but noted challenges in optimizing output and supporting advanced features like scoped CSS.

hackernews · speckx · Jun 2, 19:56 · [Discussion](https://news.ycombinator.com/item?id=48375393)

**Background**: Clojure is a modern Lisp dialect that runs on the Java Virtual Machine (JVM) and emphasizes functional programming, immutability, and concurrency. Static site generators (SSGs) are tools that compile content files (e.g., Markdown) into static HTML pages, simplifying web hosting and improving security.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Clojure">Clojure - Wikipedia</a></li>
<li><a href="https://clojure.org/">Clojure</a></li>
<li><a href="https://en.wikipedia.org/wiki/Static_site_generator">Static site generator</a></li>

</ul>
</details>

**Discussion**: Commenters noted that writing a static site generator is a rite of passage for Lisp enthusiasts, and highlighted Clojure's portability across platforms like JavaScript (ClojureScript) and Python (Basilisp). Some expressed that the runtime and concurrency model matter more than syntax, comparing Java's runtime unfavorably to Erlang's.

**Tags**: `#Clojure`, `#Programming Languages`, `#Static Site Generator`, `#Lisp`

---

<a id="item-15"></a>
## [US Treasury Sanctions Iranian Crypto Exchange Nobitex](https://decrypt.co/369816/us-treasury-sanctions-iranian-crypto-exchanges-nobitex-terrorist-financing) ⭐️ 6.0/10

The US Treasury's Office of Foreign Assets Control (OFAC) sanctioned Iranian cryptocurrency exchange Nobitex and other platforms for allegedly enabling illicit finance and terrorist financing activities. This action highlights the US government's increasing focus on cryptocurrency as a tool for sanctions evasion and terrorist financing, potentially impacting global crypto regulation and compliance standards. According to the US Treasury, Nobitex handled more than half of Iran's crypto inflows last year, underscoring its central role in Iran's crypto ecosystem.

rss · Decrypt · Jun 2, 22:55

**Background**: OFAC is a US Treasury agency that enforces economic sanctions against targeted countries, regimes, and entities. Iran has been under extensive US sanctions, and cryptocurrency exchanges have been scrutinized for potential use in bypassing these restrictions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Office_of_Foreign_Assets_Control">Office of Foreign Assets Control - Wikipedia</a></li>
<li><a href="https://www.trmlabs.com/resources/blog/understanding-nobitex-irans-largest-crypto-exchange">Understanding Nobitex: Iran’s Largest Crypto Exchange | TRM Labs</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#sanctions`, `#regulation`, `#Iran`, `#terrorist financing`

---

<a id="item-16"></a>
## [Trump Signs AI Executive Order with Voluntary Review](https://decrypt.co/369740/president-trump-signs-ai-executive-order-delaying-china-concerns) ⭐️ 6.0/10

President Trump signed an executive order establishing a voluntary framework for reviewing advanced AI models and expanding AI-powered cybersecurity initiatives. This order sets a precedent for AI regulation in the U.S., emphasizing voluntary compliance over mandatory licensing, which could shape future policy debates and impact how AI companies approach safety and security. The executive order includes a 30-day review period for new AI models, but participation is voluntary and there are no mandatory licensing or preclearance requirements.

rss · Decrypt · Jun 2, 18:08

**Background**: AI executive orders are presidential directives that guide federal agencies on AI policy. The voluntary review framework contrasts with mandatory approaches proposed by some lawmakers, reflecting ongoing debates about balancing innovation with safety.

<details><summary>References</summary>
<ul>
<li><a href="https://rollcall.com/2026/06/02/executive-order-sets-voluntary-cyber-reviews-for-advanced-ai/">Executive order sets voluntary cyber reviews for advanced AI</a></li>
<li><a href="https://deadline.com/2026/06/trump-ai-executive-order-1236938859/">Trump Signs AI Executive Order That Includes Review Period ...</a></li>
<li><a href="https://www.govinfosecurity.com/trump-signs-voluntary-ai-cyber-review-order-a-31833">Trump Signs Voluntary AI Cyber Review Order - GovInfoSecurity</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#executive order`, `#cybersecurity`, `#regulation`

---

<a id="item-17"></a>
## [Bitcoin Miner Hive Reports Revenue Surge, Bets on AI Boom](https://decrypt.co/369735/bitcoin-miner-hive-reports-revenue-surge-powering-ai-boom) ⭐️ 6.0/10

Hive Digital Technologies reported a revenue surge after mining nearly 2,900 Bitcoin last year, and announced plans to build Canada's largest private AI data center, a 320-megawatt gigafactory in the Greater Toronto Area with a CAD $3.5 billion investment. This marks a significant pivot from Bitcoin mining to AI infrastructure, highlighting the growing convergence of crypto mining and high-performance computing for AI workloads, and could set a precedent for other miners to diversify into AI data centers. Hive mined nearly 2,900 Bitcoin in the past year and has already purchased a $58 million plot in Toronto for the AI facility, with the company raising $115 million to expand its global AI data center footprint.

rss · Decrypt · Jun 2, 17:11

**Background**: Bitcoin mining requires vast amounts of energy and specialized hardware, which can be repurposed for AI computing tasks. Hive operates data centers powered by clean energy across Canada, Sweden, and Paraguay, and its dual-engine infrastructure now includes both Bitcoin mining and GPU-based AI computing.

<details><summary>References</summary>
<ul>
<li><a href="https://www.hivedigitaltechnologies.com/">HIVE Digital Technologies Ltd</a></li>
<li><a href="https://cryptobriefing.com/hive-digital-ai-gigafactory-canada/">HIVE Digital Technologies plans CAD $3.5 billion AI ...</a></li>
<li><a href="https://www.coindesk.com/business/2026/05/18/hive-buys-usd58-million-toronto-plot-for-ai-facility-shares-climb">HIVE buys $58 million Toronto plot for AI facility; shares climb</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#AI`, `#Data Center`, `#Crypto Mining`

---

<a id="item-18"></a>
## [Florida Sues OpenAI and Sam Altman Over ChatGPT Safety Claims](https://decrypt.co/369656/florida-lawsuit-openai-sam-altman-chatgpt-safety) ⭐️ 6.0/10

Florida Attorney General James Uthmeier filed a first-in-the-nation state-led lawsuit against OpenAI and CEO Sam Altman, alleging they knowingly released and marketed ChatGPT while concealing serious risks and suppressing internal safety warnings. This lawsuit could set a precedent for holding AI companies and their executives personally liable for alleged safety failures, potentially reshaping AI regulation and corporate accountability. The lawsuit seeks damages, restrictions on ChatGPT, and personal liability for Sam Altman, citing risks to children and lack of safety safeguards. Florida claims OpenAI faces potential billions in damages.

rss · Decrypt · Jun 1, 18:28

**Background**: AI safety has become a major public concern as generative AI products like ChatGPT are widely adopted. Lawsuits against AI companies have typically targeted the corporation, not individual executives; this case seeks to extend liability to the CEO personally.

<details><summary>References</summary>
<ul>
<li><a href="https://www.myfloridalegal.com/newsrelease/attorney-general-james-uthmeier-files-first-nation-state-led-lawsuit-against-openai-ceo">Attorney General James Uthmeier Files First-in-the-Nation ...</a></li>
<li><a href="https://www.cnbc.com/2026/06/01/florida-ag-open-ai-altman-lawsuit.html">Florida AG sues OpenAI, seeks to hold Altman liable for ...</a></li>
<li><a href="https://www.foxbusiness.com/media/florida-ag-says-openai-exposed-billions-potential-damages-cites-evidence-uncovered-investigation">Florida sues OpenAI over ChatGPT risks to children, seeks ...</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#regulation`, `#lawsuit`, `#OpenAI`

---

<a id="item-19"></a>
## [Whitehat Recovers $2M in ETH Stuck Since 2016 ICO](https://decrypt.co/369623/whitehat-helps-recover-2m-in-eth-stuck-since-2016-ico) ⭐️ 6.0/10

A whitehat developer exploited a preserved integer overflow bug in HongCoin's 2016 ICO smart contract to recover 1,003.62 ETH (worth about $2 million) that had been frozen for nine years. This recovery demonstrates that old smart contract vulnerabilities can persist for years, and whitehat interventions can rescue funds that were thought lost forever, benefiting the original 48 investors. The bug was an integer overflow in the refund function that allowed the whitehat to call an admin function to reopen refunds; the recovered ETH was returned to the original multisig wallet for distribution to investors.

rss · Decrypt · Jun 1, 15:32

**Background**: HongCoin launched an ICO in August 2016, collecting ETH from 48 participants. The ICO failed to meet its target, and the smart contract was designed to automatically refund contributors, but a bug prevented refunds from being processed. The funds remained stuck until a whitehat developer discovered the vulnerability and exploited it to recover the ETH.

<details><summary>References</summary>
<ul>
<li><a href="https://cryptorank.io/news/feed/cb600-failed-ethereum-ico-from-2016-just-unlocked-1003-eth-by-exploiting-itself">Failed Ethereum ICO from 2016 just unlocked 1,003 ETH by exploiting...</a></li>
<li><a href="https://cryptobriefing.com/hongcoin-investors-recover-locked-eth-nine-years/">HongCoin investors recover $2M in locked ETH after nine years</a></li>
<li><a href="https://www.coindesk.com/tech/2026/06/01/whitehat-developer-unlocks-usd2-million-stuck-in-a-2016-ethereum-ico-contract-for-nine-years">Whitehat developer unlocks $2 million stuck in a 2016 Ethereum ICO contract for nine years</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#whitehat`, `#smart contract`, `#recovery`

---

<a id="item-20"></a>
## [Galaxy Digital Launches OTC Prediction Market for Institutions](https://www.theblock.co/post/403338/galaxy-digital-opens-otc-prediction-market-trading-for-institutions-kicks-off-with-10-million-kalshi-trade?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Galaxy Digital has launched an institutional over-the-counter (OTC) prediction market trading desk, executing a $10 million trade with Arca on Kalshi tied to the passage of the Clarity Act. This development opens prediction market liquidity to hedge funds and family offices at institutional scale, potentially increasing market depth and legitimacy for event-driven contracts. Galaxy's OTC desk acts as principal counterparty, enabling bilateral trades at sizes not available on retail interfaces, and covers contracts on Kalshi and Polymarket with plans to expand.

rss · The Block · Jun 2, 13:12

**Background**: Prediction markets allow trading on the outcome of real-world events like elections or legislation. Kalshi is a regulated U.S. exchange for such contracts, while OTC trading enables large, discreet transactions between institutions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.prnewswire.com/news-releases/galaxy-launches-institutional-otc-prediction-markets-trading-302788206.html">Galaxy Launches Institutional OTC Prediction Markets Trading</a></li>
<li><a href="https://www.theblock.co/post/403338/galaxy-digital-opens-otc-prediction-market-trading-for-institutions-kicks-off-with-10-million-kalshi-trade">Galaxy Digital opens OTC prediction market trading for institutions, kicks off with $10 million Kalshi trade | The Block</a></li>
<li><a href="https://coinpedia.org/news/clarity-act-new-update-bill-officially-placed-on-senate-calendar-as-galaxy-bets-10m-on-2026-passage/">CLARITY Act New Update: Bill Officially Placed on Senate Calendar as Galaxy Bets $10M on 2026 Passage</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#institutional trading`, `#crypto`, `#finance`

---

<a id="item-21"></a>
## [Backpack Launches Hybrid Securities Platform](https://www.theblock.co/post/403328/backpack-launches-securities-platform-blending-traditional-and-tokenized-stock-trading?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Backpack has launched Backpack Securities, a platform that combines a U.S.-regulated brokerage for traditional equities with a tokenization platform on Solana's Sunrise protocol. This integration bridges traditional finance and blockchain, enabling investors to trade tokenized stocks alongside conventional equities, potentially increasing liquidity and accessibility in both markets. The platform offers real U.S. stock ownership through a regulated brokerage and allows tokenization of those stocks via the Sunrise protocol on Solana, competing with exchanges like Coinbase and Robinhood.

rss · The Block · Jun 2, 13:05

**Background**: Tokenized stocks are digital representations of traditional equities issued on a blockchain, enabling 24/7 trading and fractional ownership. Backpack, backed by $17 million in Series A funding, operates a regulated crypto exchange and now extends into securities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.prnewswire.com/news-releases/backpack-launches-securities-platform-bridging-traditional-and-digital-asset-markets-302788563.html">Backpack Launches Securities Platform Bridging Traditional ...</a></li>
<li><a href="https://tradersunion.com/news/cryptocurrency-news/show/2205360-backpack-tokenized-stock-trading-platform/">Backpack launches tokenized stock trading platform for U.S ...</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenization`, `#fintech`, `#securities trading`

---