---
layout: default
title: "Horizon Summary: 2026-05-08 (EN)"
date: 2026-05-08
lang: en
---

> From 93 items, 36 important content pieces were selected

---

1. [Dirtyfrag: Universal Linux LPE Vulnerability Disclosed Without Patches](#item-1) ⭐️ 9.0/10
2. [Anthropic's NLAs Turn Model Activations into Readable Text](#item-2) ⭐️ 9.0/10
3. [Canvas LMS Down After ShinyHunters Breach During Finals](#item-3) ⭐️ 8.0/10
4. [Should You Delay Software Installs?](#item-4) ⭐️ 8.0/10
5. [AI Agents Need Control Flow, Not More Prompts](#item-5) ⭐️ 8.0/10
6. [Cloudflare Lays Off 1100 Employees (20% of Workforce)](#item-6) ⭐️ 8.0/10
7. [AlphaEvolve: Gemini-powered coding agent scales impact across fields](#item-7) ⭐️ 8.0/10
8. [DeepSeek 4 Flash Local Inference Engine for Metal](#item-8) ⭐️ 8.0/10
9. [AI Slop Eroding Trust in Online Communities](#item-9) ⭐️ 8.0/10
10. [Brazil's Pix faces pressure from Visa and Mastercard](#item-10) ⭐️ 8.0/10
11. [Chrome Removes Privacy Promise for On-Device AI](#item-11) ⭐️ 8.0/10
12. [AI Chatbots Leak User Chats to Ad Trackers](#item-12) ⭐️ 8.0/10
13. [Tether's Medical AI Runs on Phone, Beats Models 16x Larger](#item-13) ⭐️ 8.0/10
14. [Google Boosts Local AI Speed 3x Without New Hardware](#item-14) ⭐️ 8.0/10
15. [Aave Overhauls Collateral Rules After KelpDAO Exploit](#item-15) ⭐️ 7.0/10
16. [IMF Warns AI Will Supercharge Cyberattacks on Global Financial System](#item-16) ⭐️ 7.0/10
17. [Amazon Teams With Coinbase and Stripe to Let AI Agents Pay With Stablecoins](#item-17) ⭐️ 7.0/10
18. [TrustedVolumes DeFi Exploit Drains $6.7M](#item-18) ⭐️ 7.0/10
19. [Chrome Quietly Installs 4GB AI Model, Re-downloads if Deleted](#item-19) ⭐️ 7.0/10
20. [AI Reads Plain-Language Chemistry Instructions to Design Molecules](#item-20) ⭐️ 7.0/10
21. [Quantum Threat to Bitcoin, Ethereum Could Hit by 2030](#item-21) ⭐️ 7.0/10
22. [Ondo, JPMorgan, Mastercard, Ripple Team for Tokenized Treasuries on XRPL](#item-22) ⭐️ 7.0/10
23. [Google DeepMind Invests in Eve Online Maker for AI Research](#item-23) ⭐️ 7.0/10
24. [Nvidia backs IREN with warrants for 30M shares](#item-24) ⭐️ 7.0/10
25. [Map and Process for Burning Man Cleanup](#item-25) ⭐️ 6.0/10
26. [20 Banks and Tech Giants Queue to Issue Stablecoins via Anchorage](#item-26) ⭐️ 6.0/10
27. [Solv Protocol Moves $700M Bitcoin from LayerZero to Chainlink](#item-27) ⭐️ 6.0/10
28. [MEV Bot Front-Runs Vitalik Buterin's $4 Swap with $1M Volume](#item-28) ⭐️ 6.0/10
29. [Kraken Parent Buys Stablecoin Firm Reap for $600M](#item-29) ⭐️ 6.0/10
30. [SpaceX and xAI to Power Anthropic's Claude in Surprise Deal](#item-30) ⭐️ 6.0/10
31. [Richard Dawkins Suggests Claude AI May Be Conscious](#item-31) ⭐️ 6.0/10
32. [Anthropic Launches 10 AI Agent Templates for Finance](#item-32) ⭐️ 6.0/10
33. [Hut 8 Hits All-Time High on $9.8B AI Data Center Lease](#item-33) ⭐️ 6.0/10
34. [Apple Settles AI Misleading Claims for $250 Million](#item-34) ⭐️ 6.0/10
35. [US Treasury Demands Binance Comply with 2023 Monitoring Deal](#item-35) ⭐️ 6.0/10
36. [Kalshi hits $22B valuation after $1B Series F led by Coatue](#item-36) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Dirtyfrag: Universal Linux LPE Vulnerability Disclosed Without Patches](https://www.openwall.com/lists/oss-security/2026/05/07/8) ⭐️ 9.0/10

A new universal Linux local privilege escalation vulnerability called Dirtyfrag has been publicly disclosed on May 7, 2026, with a working exploit, breaking the embargo and leaving no patches or CVEs available. This vulnerability affects Linux kernel versions 5.10 to 6.9.x, potentially impacting 70% of Linux cloud servers, and allows any local low-privilege user to gain root privileges, posing a critical threat to Kubernetes nodes and cloud environments. Dirtyfrag exploits a page-cache write similar to the Copy Fail vulnerability, using an ESP-style approach to overwrite /etc/passwd and remove the root password, enabling privilege escalation without authentication.

hackernews · flipped · May 7, 19:21 · [Discussion](https://news.ycombinator.com/item?id=48053623)

**Background**: Local privilege escalation (LPE) vulnerabilities allow an attacker with limited access to gain higher privileges, such as root. The Linux kernel's cryptographic subsystem (AF_ALG) and page-cache mechanism have been recent targets, as seen with the Copy Fail vulnerability (CVE-2026-31431). Dirtyfrag is a new variant that exploits the same underlying issue through network sockets (ESP), making it more widely exploitable.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/V4bel/dirtyfrag">GitHub - V4bel/ dirtyfrag · GitHub</a></li>
<li><a href="https://github.com/V4bel/dirtyfrag/blob/master/assets/write-up.md">dirtyfrag/assets/write-up.md at master · V4bel/dirtyfrag</a></li>
<li><a href="https://www.microsoft.com/en-us/security/blog/2026/05/01/cve-2026-31431-copy-fail-vulnerability-enables-linux-root-privilege-escalation/">CVE-2026-31431: Copy Fail vulnerability enables Linux root privilege escalation across cloud environments | Microsoft Security Blog</a></li>

</ul>
</details>

**Discussion**: The community notes the root cause similarity to Copy Fail, with some researchers criticizing the lack of proper fix for the authencesn issue. There is concern about the timing, as AWS just released patches for Copy Fail, and mitigation before a patch for Dirtyfrag is difficult, especially on Kubernetes nodes.

**Tags**: `#Linux`, `#security`, `#vulnerability`, `#LPE`, `#kernel`

---

<a id="item-2"></a>
## [Anthropic's NLAs Turn Model Activations into Readable Text](https://www.anthropic.com/research/natural-language-autoencoders) ⭐️ 9.0/10

Anthropic introduced Natural Language Autoencoders (NLAs), a method that translates internal model activations into natural language text, and released open-weight NLA models for Qwen 2.5 (7B), Gemma 3 (12B, 27B), and Llama 3.3 (70B). This is a major step forward in AI interpretability, offering a direct window into what language models 'think' at the activation level, which could improve safety and trust in AI systems. The NLA consists of a 'verbalizer' that maps activations to text and a 'reconstructor' that inverts the text back to activations, trained with a simple reconstruction loss and careful initialization. The open-weight models are available on GitHub and Hugging Face.

hackernews · instagraham · May 7, 17:54 · [Discussion](https://news.ycombinator.com/item?id=48052537)

**Background**: Autoencoders are neural networks that learn efficient representations of data by encoding input into a compressed form and then decoding it back. In AI interpretability, researchers often analyze model activations—the internal signals flowing through a neural network—to understand what features the model is using. NLAs apply this concept to produce human-readable text that describes those activations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/research/natural-language-autoencoders">Natural Language Autoencoders: Turning Claude’s thoughts into text</a></li>

</ul>
</details>

**Discussion**: The community is highly engaged, with comments praising the simple yet effective approach and Anthropic's release of open-weight models. Some commenters raise concerns about whether the generated text truly reflects the model's internal reasoning or merely produces plausible-sounding descriptions.

**Tags**: `#interpretability`, `#AI safety`, `#open source`, `#transformer circuits`, `#Anthropic`

---

<a id="item-3"></a>
## [Canvas LMS Down After ShinyHunters Breach During Finals](https://www.theverge.com/tech/926458/canvas-shinyhunters-breach) ⭐️ 8.0/10

On May 7, 2026, the Canvas learning management system experienced a major outage after the ShinyHunters hacking group claimed to have breached its parent company Instructure, stealing data from over 275 million users across 9,000 schools. This incident disrupts millions of students and educators during final exams, highlighting the vulnerability of critical educational infrastructure and reigniting debates on ransomware payments and cybersecurity preparedness. ShinyHunters defaced Canvas login portals for hundreds of colleges and threatened to leak stolen data unless a ransom is paid. The breach follows a previous Instructure hack also attributed to the group.

hackernews · stefanpie · May 7, 22:22 · [Discussion](https://news.ycombinator.com/item?id=48055913)

**Background**: Canvas is a widely used learning management system (LMS) owned by Instructure, serving K-12 and higher education institutions. ShinyHunters is a cybercriminal group known for data breaches and extortion, often leaking data if ransoms are not paid.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/2026_Canvas_security_incident">2026 Canvas security incident - Wikipedia</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/canvas-login-portals-hacked-in-mass-shinyhunters-extortion-campaign/">Canvas login portals hacked in mass ShinyHunters extortion ...</a></li>
<li><a href="https://techcrunch.com/2026/05/07/hackers-deface-school-login-pages-after-claiming-another-instructure-hack/">Hackers deface school login pages after claiming another Instructure ...</a></li>

</ul>
</details>

**Discussion**: Community comments express frustration and concern, with educators noting the outage during finals and lack of offline backups. Some debate the legality of ransomware payments, while others criticize universities' reliance on a single platform without contingency plans.

**Tags**: `#security`, `#data breach`, `#education`, `#ransomware`, `#Canvas`

---

<a id="item-4"></a>
## [Should You Delay Software Installs?](https://xeiaso.net/blog/2026/abstain-from-install/) ⭐️ 8.0/10

A blog post by Xe Iaso suggests users abstain from installing new software for a week to mitigate supply chain attacks, sparking a nuanced debate on security trade-offs. This proposal highlights the growing threat of software supply chain attacks and the difficulty of balancing security with convenience in modern development workflows. The suggestion is controversial because attackers can time exploits to activate after a delay, and many security fixes require immediate deployment to prevent active exploitation.

hackernews · psxuaw · May 7, 23:02 · [Discussion](https://news.ycombinator.com/item?id=48056227)

**Background**: Software supply chain attacks target trusted third-party vendors or open-source packages to inject malicious code into widely used software. Recent high-profile incidents have prompted calls for better security practices, but delaying installations can also leave systems vulnerable to known exploits.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cisa.gov/resources-tools/resources/defending-against-software-supply-chain-attacks">Defending Against Software Supply Chain Attacks - CISA</a></li>
<li><a href="https://www.crowdstrike.com/en-us/cybersecurity-101/cyberattacks/supply-chain-attack/">What Is a Supply Chain Attack? - CrowdStrike</a></li>

</ul>
</details>

**Discussion**: Comments are mixed: some support the idea as a pragmatic measure, while others argue it's ineffective against timed attacks and undermines rapid patching. FreeBSD security expert cperciva advocates for a more robust OS security model instead.

**Tags**: `#security`, `#supply chain`, `#software engineering`, `#open source`, `#best practices`

---

<a id="item-5"></a>
## [AI Agents Need Control Flow, Not More Prompts](https://bsuh.bearblog.dev/agents-need-control-flow/) ⭐️ 8.0/10

A blog post argues that AI agents should rely on deterministic control flow and code rather than increasingly complex prompts, challenging the prevalent 'more prompting' approach. This matters because it highlights a fundamental shift in how reliable AI agents are built, potentially improving their robustness and reducing reliance on fragile prompt engineering. The post notes that prompting has hit a functional ceiling, with developers resorting to 'MANDATORY' instructions to combat non-determinism, and suggests moving from runtime LLM use to LLM-assisted software generation.

hackernews · bsuh · May 7, 16:43 · [Discussion](https://news.ycombinator.com/item?id=48051562)

**Background**: AI agents often use large language models (LLMs) to interpret tasks via prompts, but this approach is probabilistic and can be unreliable. Control flow, as used in traditional programming, provides deterministic execution paths, making agent behavior more predictable and verifiable.

<details><summary>References</summary>
<ul>
<li><a href="https://thecodersblog.com/agent-control-flow-for-ai-agents-2026/">AI Agents Need Control Flow, Not More Prompts | The Coders ...</a></li>
<li><a href="https://aitoolly.com/ai-news/article/2026-05-08-why-ai-agents-require-deterministic-control-flow-over-elaborate-prompt-engineering">AI Agents: Why Control Flow Beats Prompt Engineering</a></li>
<li><a href="https://bethere.ai/articles/prompt-engineer-not-deterministic.html">Why Prompt Engineering Will Never Be As Deterministic As Programming | BeThere</a></li>

</ul>
</details>

**Discussion**: Community comments strongly agree with the thesis, with one user noting that LLMs are often misapplied and should instead write code for deterministic tasks. Another suggests shifting from runtime LLM use to LLM-assisted software generation, while a third calls for next-generation AI beyond LLMs.

**Tags**: `#AI agents`, `#LLM`, `#software engineering`, `#control flow`, `#prompting`

---

<a id="item-6"></a>
## [Cloudflare Lays Off 1100 Employees (20% of Workforce)](https://blog.cloudflare.com/building-for-the-future/) ⭐️ 8.0/10

Cloudflare announced it is laying off approximately 1,100 employees, representing 20% of its workforce, in a move titled 'Building for the Future.' The layoffs were announced in May 2026, just months after the company hired 1,111 interns in September 2025. This significant reduction at a major tech infrastructure company highlights the ongoing volatility in the tech industry, where rapid hiring and layoffs can occur within the same year. The timing and messaging have sparked debate about corporate transparency and the human impact of workforce restructuring. Departing employees will receive full base pay through the end of 2026, healthcare coverage through the end of the year in the US, and accelerated equity vesting through August 15th, including waiving one-year cliffs for those who haven't reached them. The layoff announcement follows a recent intern hiring spree, drawing criticism for the contrasting messages.

hackernews · PriorityLeft · May 7, 20:23 · [Discussion](https://news.ycombinator.com/item?id=48054423)

**Background**: Cloudflare is a major content delivery network and cloud security provider. The company had hired 1,111 interns in September 2025 under a program titled 'Help build the future,' which contrasts sharply with the current layoff messaging. The layoffs come amid broader tech industry trends of cost-cutting and AI-related restructuring.

**Discussion**: Community comments are highly critical, with users pointing out the irony of hiring 1,111 interns under a similar slogan just months before laying off 1,100 people. Many dislike the vague title 'Building for the Future' for not clearly indicating a layoff. Affected employees are also posting seeking new jobs, and some speculate that layoffs may be driven by rising AI costs without corresponding revenue gains.

**Tags**: `#layoffs`, `#cloudflare`, `#tech industry`, `#workforce reduction`, `#hacker news discussion`

---

<a id="item-7"></a>
## [AlphaEvolve: Gemini-powered coding agent scales impact across fields](https://deepmind.google/blog/alphaevolve-impact/) ⭐️ 8.0/10

Google DeepMind unveiled AlphaEvolve in May 2025, a Gemini-powered coding agent that autonomously optimizes algorithms and systems, from low-level hardware circuits to high-level codebases. AlphaEvolve represents a significant step toward AI self-improvement, as it can optimize the very hardware and software that run AI models, potentially accelerating progress across scientific and engineering domains. AlphaEvolve proposed a circuit design so efficient it was integrated into Google's next-generation TPUs, demonstrating its ability to improve AI infrastructure. It goes beyond single-function optimization to evolve entire codebases.

hackernews · berlianta · May 7, 15:02 · [Discussion](https://news.ycombinator.com/item?id=48050278)

**Background**: AlphaEvolve is an evolutionary coding agent built on large language models like Gemini. It uses an evolutionary algorithm to iteratively generate and test code variations, optimizing for objectives like speed or efficiency. This approach builds on DeepMind's earlier work in AI-driven algorithm discovery.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AlphaEvolve">AlphaEvolve - Wikipedia</a></li>
<li><a href="https://deepmind.google/blog/alphaevolve-impact/">AlphaEvolve: Gemini-powered coding agent scaling impact across fields — Google DeepMind</a></li>
<li><a href="https://deepmind.google/blog/alphaevolve-a-gemini-powered-coding-agent-for-designing-advanced-algorithms/">AlphaEvolve: A Gemini-powered coding agent for designing advanced algorithms — Google DeepMind</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights that AlphaEvolve is one of few companies (Google, Sakana AI, Autohand AI) working on high-degree solver problems. Some commenters note the contrast between DeepMind's focus on research problems and other AI labs' pursuit of enterprise/coding revenue, while others question whether Google employees prefer Gemini over Claude Code or Codex.

**Tags**: `#AI`, `#DeepMind`, `#optimization`, `#coding agents`, `#research`

---

<a id="item-8"></a>
## [DeepSeek 4 Flash Local Inference Engine for Metal](https://github.com/antirez/ds4) ⭐️ 8.0/10

Antirez released ds4, a small, specialized native inference engine for DeepSeek V4 Flash that runs on Apple Silicon via the Metal API, achieving full-speed token generation with only 50W power draw on an M3 Max MacBook. This project demonstrates the value of hardware-specific optimization for open-source LLMs, potentially inspiring more focused inference engines that outperform general-purpose frameworks like llama.cpp on particular hardware. The engine is intentionally narrow: it is not a generic GGUF runner or framework, but a DeepSeek V4 Flash-specific Metal graph executor with custom loading. It supports only the DeepSeek V4 Flash model and runs on Apple Silicon via Metal.

hackernews · tamnd · May 7, 15:40 · [Discussion](https://news.ycombinator.com/item?id=48050751)

**Background**: DeepSeek V4 Flash is a Mixture-of-Experts model with 284B total parameters and 13B activated, supporting a 1M-token context window. Metal is Apple's low-level GPU API for high-performance compute on Apple Silicon. General inference frameworks like llama.cpp support many models but may not be optimally tuned for specific hardware-model combinations.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/antirez/ds4">GitHub - antirez/ds4: DeepSeek 4 Flash local inference engine for...</a></li>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash">deepseek -ai/ DeepSeek -V 4 - Flash · Hugging Face</a></li>
<li><a href="https://en.wikipedia.org/wiki/Metal_(API)">Metal (API) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised the focused approach and noted similar projects for other models (e.g., Qwen3). Some raised concerns about slow prompt processing (4 minutes for large inputs), but caching was suggested as a mitigation. The low power draw (50W) was highlighted as impressive.

**Tags**: `#inference`, `#Apple Silicon`, `#Metal`, `#DeepSeek`, `#open source`

---

<a id="item-9"></a>
## [AI Slop Eroding Trust in Online Communities](https://rmoff.net/2026/05/06/ai-slop-is-killing-online-communities/) ⭐️ 8.0/10

AI-generated content, often called 'slop,' is increasingly flooding online communities like Reddit, making it hard to distinguish human posts from bot posts, and driving users away. This erosion of trust threatens the very foundation of online communities, as authentic human interaction is replaced by automated content, potentially pushing users toward smaller, more curated spaces or offline interactions. Moderators report banning hundreds of AI accounts monthly, and some users have conducted experiments showing that AI-generated posts can engage humans without detection, highlighting the scale of the problem.

hackernews · thm · May 7, 18:46 · [Discussion](https://news.ycombinator.com/item?id=48053203)

**Background**: Online communities like Reddit and Hacker News rely on user-generated content and trust. AI language models can now produce convincing text at scale, making it easy for bad actors to spam, manipulate discussions, or farm karma, undermining community health.

**Discussion**: Commenters express frustration and fear, with some abandoning Reddit entirely. Moderators share the heavy burden of combating AI accounts, while a few see a silver lining, hoping it will drive people back to real-world interactions.

**Tags**: `#AI`, `#online communities`, `#content moderation`, `#trust`, `#bots`

---

<a id="item-10"></a>
## [Brazil's Pix faces pressure from Visa and Mastercard](https://www.elciudadano.com/en/brazils-pix-payment-system-faces-pressure-from-visa-and-mastercard/04/04/) ⭐️ 8.0/10

Brazil's central bank-led instant payment system Pix is facing pushback from Visa and Mastercard, as the card networks criticize the central bank for both regulating and competing in the payments market. This conflict highlights the tension between government-run payment systems and private card networks, with Pix's success potentially challenging the fee-based model that generates billions for Visa and Mastercard globally. Pix operates 24/7 with no fees for individuals, while Visa and Mastercard charge merchants 1-3% per transaction. Mastercard Brazil's CEO has argued that the central bank should not both regulate and compete.

hackernews · wslh · May 7, 17:42 · [Discussion](https://news.ycombinator.com/item?id=48052371)

**Background**: Pix is an instant payment system launched by Brazil's Central Bank in 2020, allowing free and immediate transfers between individuals. It quickly became Brazil's most popular payment method, disrupting the traditional card network duopoly. The system is often cited as a successful example of a central bank digital payment initiative.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pix_(payment_system)">Pix ( payment system ) - Wikipedia</a></li>
<li><a href="https://www.pagbrasil.com/lp/content-pix/">Pix, Brazil's favorite payment method for e-commerce</a></li>
<li><a href="https://www.bcb.gov.br/en/financialstability/pix_en">Banco Central do Brasil</a></li>

</ul>
</details>

**Discussion**: Commenters praised Pix for solving Brazil's previously difficult and costly bank transfers, with some noting merchants offer discounts for Pix payments to avoid card fees. Others questioned why the US cannot implement a similar system, while one commenter argued that governments are not competent enough to build such technology.

**Tags**: `#fintech`, `#payments`, `#regulation`, `#Brazil`, `#central bank`

---

<a id="item-11"></a>
## [Chrome Removes Privacy Promise for On-Device AI](https://decrypt.co/367193/chrome-removes-privacy-claim-gemini-nano-google) ⭐️ 8.0/10

Google Chrome has silently installed a 4GB AI model (Gemini Nano) on devices and removed a privacy disclosure that promised local-only processing, raising concerns that user data may be sent to servers. This matters because Chrome is the most widely used browser, and the removal of a privacy promise undermines user trust, especially as on-device AI is often marketed as a privacy-preserving alternative to cloud AI. The AI model, Gemini Nano, is installed without explicit user consent, and the removal of the privacy disclosure suggests that Google may be collecting data from local AI processing. Users have limited options to disable this feature.

rss · Decrypt · May 7, 20:52

**Background**: On-device AI processes data locally on the user's device, which is generally considered more private than sending data to cloud servers. Chrome's Gemini Nano was initially promoted as a local-only AI feature, but the removal of that promise raises questions about data handling. The silent installation of a large AI model also consumes storage and resources without user awareness.

<details><summary>References</summary>
<ul>
<li><a href="https://awesomeagents.ai/news/chrome-gemini-nano-silent-install/">Chrome Installs 4 GB Gemini Nano Without Asking | Awesome Agents</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#Chrome`, `#AI`, `#Google`, `#browser`

---

<a id="item-12"></a>
## [AI Chatbots Leak User Chats to Ad Trackers](https://decrypt.co/367164/your-ai-chatbot-leaking-chats-meta-tiktok-google) ⭐️ 8.0/10

A new study reveals that popular AI chatbots including ChatGPT, Claude, Grok, and Perplexity share user conversation data with third-party ad trackers from Meta, TikTok, and Google, sometimes even when users decline cookies. This privacy breach affects millions of users and undermines trust in AI chatbots, potentially leading to stricter regulations and forcing companies to redesign their data handling practices. The study found that Grok's guest chats are public by default, and data sharing includes conversation URLs and user data, enabling user profiling and targeted advertising.

rss · Decrypt · May 7, 19:06

**Background**: Third-party ad trackers are services used by advertisers to monitor user behavior across websites and apps. AI chatbots often embed such trackers for analytics or advertising purposes, but users expect their conversations to remain private. This study highlights a significant gap between user expectations and actual data practices.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/367164/your-ai-chatbot-leaking-chats-meta-tiktok-google">Your AI Chatbot May Be Leaking Your Chats to Meta, TikTok and ...</a></li>
<li><a href="https://oecd.ai/en/incidents/2026-05-05-6f9b">Major AI Chatbots Leak User Conversations to Advertising ...</a></li>
<li><a href="https://www.gncrypto.news/news/ai-chatbots-leak-chats-meta-tiktok-google-study/">Study: AI chatbots leak chats to Meta, TikTok and Google</a></li>

</ul>
</details>

**Tags**: `#privacy`, `#AI chatbots`, `#data sharing`, `#tracking`, `#security`

---

<a id="item-13"></a>
## [Tether's Medical AI Runs on Phone, Beats Models 16x Larger](https://decrypt.co/367127/tether-medical-ai-runs-on-phone-outperforms-models-16x) ⭐️ 8.0/10

Tether's QVAC MedPsy, a compact medical AI model, runs on smartphones and outperforms Google's MedGemma-27B on real-world scenarios while using three times fewer compute resources. This breakthrough demonstrates that small, efficient models can rival much larger ones, potentially democratizing medical AI by enabling deployment on edge devices like phones and wearables without cloud dependency. The text-only QVAC MedPsy-1.7B model achieves an average score of 62.62 across seven medical benchmarks, outperforming Google's MedGemma-1.5-4B-it (51.20) and matching Qwen3-4B-Thinking-2507 (63.10), a model 2.4x larger.

rss · Decrypt · May 7, 16:01

**Background**: Medical AI models are typically large and require powerful cloud servers, limiting accessibility in low-resource settings. Tether's QVAC MedPsy is designed for edge devices, leveraging parameter efficiency to achieve high performance with minimal compute. Google's MedGemma is a family of open medical models built on Gemma 3, available in sizes up to 27B parameters.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/qvac/medpsy">QVAC MedPsy: State-of-the-Art Medical and Healthcare Language Models for Edge Devices</a></li>
<li><a href="https://developers.google.com/health-ai-developer-foundations/medgemma">MedGemma | Health AI Developer Foundations | Google for ...</a></li>
<li><a href="https://github.com/tetherto/qvac">GitHub - tetherto/qvac: QVAC - Local AI SDK and libraries for building private, cross-platform, peer-to-peer AI applications. Run LLMs, speech-to-text, translation, and more locally on Linux, macOS, Windows, Android, and iOS. · GitHub</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Medical AI`, `#Edge Computing`, `#Model Efficiency`, `#Healthcare`

---

<a id="item-14"></a>
## [Google Boosts Local AI Speed 3x Without New Hardware](https://decrypt.co/367095/google-make-local-ai-3x-faster-no-new-hardware) ⭐️ 8.0/10

Google released Multi-Token Prediction (MTP) drafters for Gemma 4, a speculative decoding technique that accelerates local inference up to 3x without sacrificing output quality. This breakthrough enables faster AI inference on consumer hardware, enhancing privacy and reducing cloud dependency for edge computing applications. MTP drafters generate multiple likely next tokens for the main model to verify in parallel, rather than generating one token at a time. The technique works with Gemma 4 models and requires no hardware upgrades.

rss · Decrypt · May 7, 14:13

**Background**: Large language models like Gemma 4 generate text token by token, which is inherently slow. Speculative decoding uses a smaller 'drafter' model to propose multiple tokens, which the main model then verifies in parallel, speeding up inference. Gemma 4 is Google's latest open-source LLM, released in April 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/multi-token-prediction-gemma-4/">Multi-token-prediction in Gemma 4 - The Keyword</a></li>
<li><a href="https://www.marktechpost.com/2026/05/06/google-ai-releases-multi-token-prediction-mtp-drafters-for-gemma-4-delivering-up-to-3x-faster-inference-without-quality-loss/">Google AI Releases Multi-Token Prediction (MTP) Drafters for ...</a></li>
<li><a href="https://expertbeacon.com/what-do-multi-token-prediction-drafters-change-for-gemma-4-developers/">What Do Multi-Token Prediction Drafters Change For Gemma 4 ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#machine learning`, `#Google`, `#edge computing`, `#performance optimization`

---

<a id="item-15"></a>
## [Aave Overhauls Collateral Rules After KelpDAO Exploit](https://www.coindesk.com/business/2026/05/07/aave-to-overhaul-collateral-and-listing-standards-after-kelpdao-exploit) ⭐️ 7.0/10

Aave Labs announced a comprehensive overhaul of its collateral and listing standards following the $292 million KelpDAO exploit in April 2026. The new framework adds cybersecurity, interoperability, and systemic-risk checks, along with a playbook for token issuers. This update sets a new precedent for DeFi lending protocols, directly addressing vulnerabilities exposed by cross-chain bridge exploits. It enhances Aave's risk management and could influence how other protocols evaluate collateral assets. The exploit targeted KelpDAO's rsETH token via a forged cross-chain message on LayerZero, forcing Aave to freeze rsETH markets and conduct emergency liquidations. The new standards include mandatory audits, bridge security assessments, and ongoing monitoring requirements.

rss · CoinDesk · May 7, 14:27

**Background**: Aave is a leading DeFi lending protocol where users deposit assets as collateral to borrow others. The KelpDAO exploit, attributed to North Korea's Lazarus Group, drained $292 million by exploiting a bridge vulnerability, highlighting the risks of cross-chain interoperability in DeFi.

<details><summary>References</summary>
<ul>
<li><a href="https://www.chainalysis.com/blog/kelpdao-bridge-exploit-april-2026/">Inside the KelpDAO Bridge Exploit</a></li>
<li><a href="https://www.techtarget.com/searchcio/feature/The-KelpDAO-crypto-hack-What-IT-execs-must-know">The KelpDAO $292M crypto hack: What IT execs must know | TechTarget</a></li>
<li><a href="https://miningnews.live/en/article/aave-overhauls-collateral-standards-after-kelpdao-exploit-2026">Aave overhauls collateral standards after Ke... - Mining News</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#Aave`, `#exploit`, `#risk management`

---

<a id="item-16"></a>
## [IMF Warns AI Will Supercharge Cyberattacks on Global Financial System](https://decrypt.co/367178/imf-warns-ai-supercharge-cyberattacks-global-financial-system) ⭐️ 7.0/10

The International Monetary Fund (IMF) warned on May 7, 2026, that AI tools are enabling even unskilled attackers to launch sophisticated cyberattacks on the global financial system, and urged treating cybersecurity as a core financial stability issue. This matters because AI-powered cyberattacks could turn localized breaches into systemic crises, threatening the stability of the entire global financial system. Policymakers and financial institutions must now prioritize resilience standards and international coordination to contain these threats. The IMF analysis suggests that extreme cyber events could become more frequent and severe as AI amplifies offensive capabilities that outpace defenses. The organization calls for expanding existing measures and sharpening them for a world of faster, automated, and increasingly sophisticated attacks.

rss · Decrypt · May 7, 19:44

**Background**: The global financial system relies heavily on interconnected digital infrastructure, making it a prime target for cyberattacks. AI tools like generative models can automate phishing, create deepfakes, and identify vulnerabilities at scale, lowering the barrier for entry for malicious actors. The IMF has previously flagged cyber risk as a financial stability concern, but this new warning emphasizes the accelerating threat from AI.

<details><summary>References</summary>
<ul>
<li><a href="https://www.imf.org/en/blogs/articles/2026/05/07/financial-stability-risks-mount-as-artificial-intelligence-fuels-cyberattacks">Financial Stability Risks Mount as Artificial Intelligence Fuels Cyberattacks</a></li>
<li><a href="https://finance.yahoo.com/sectors/technology/articles/imf-warns-ai-supercharge-cyberattacks-194422394.html?fr=sycsrp_catchall">IMF Warns AI Will Supercharge Cyberattacks on Global ...</a></li>
<li><a href="https://techxplore.com/news/2026-05-imf-inevitable-ai-powered-threats.html">IMF warns of 'inevitable' AI-powered threats to global ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cybersecurity`, `#finance`, `#IMF`

---

<a id="item-17"></a>
## [Amazon Teams With Coinbase and Stripe to Let AI Agents Pay With Stablecoins](https://decrypt.co/367125/amazon-coinbase-stripe-ai-agents-pay-stablecoins) ⭐️ 7.0/10

Amazon Web Services (AWS) has partnered with Coinbase and Stripe to enable AI agents to pay for APIs, data, and online services using the USDC stablecoin. This integration marks a practical step toward an autonomous agent economy, where AI agents can transact independently using programmable, low-cost stablecoins, potentially transforming how digital services are consumed and paid for. The system leverages USDC, a stablecoin pegged to the US dollar, as the payment rail, and involves major platforms like Coinbase for crypto infrastructure and Stripe for payment processing.

rss · Decrypt · May 7, 16:32

**Background**: Stablecoins like USDC are cryptocurrencies designed to maintain a stable value relative to a fiat currency, such as the US dollar. The agentic economy refers to an emerging ecosystem where AI agents act autonomously on behalf of users or businesses, requiring efficient payment rails for machine-to-machine transactions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/USDC_(cryptocurrency)">USDC (cryptocurrency) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2505.15799">[2505.15799] The Agentic Economy - arXiv.org</a></li>
<li><a href="https://en.wikipedia.org/wiki/Payment_rail">Payment rail</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#stablecoins`, `#Amazon Web Services`, `#fintech`, `#blockchain`

---

<a id="item-18"></a>
## [TrustedVolumes DeFi Exploit Drains $6.7M](https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit) ⭐️ 7.0/10

TrustedVolumes, a liquidity resolver used by multiple DeFi protocols, was exploited on Ethereum, losing approximately $6.7 million. The exploit was first flagged by security firm Blockaid. This incident highlights ongoing security risks in DeFi, particularly for third-party infrastructure components like liquidity resolvers. The fact that 1inch, a major DEX aggregator, was not affected shows that the damage was contained, but it still raises concerns about the security of interconnected DeFi systems. The stolen funds are reportedly held across three Ethereum addresses. TrustedVolumes has launched bounty talks with the exploiter to recover the funds.

rss · Decrypt · May 7, 11:25

**Background**: In DeFi, liquidity resolvers help match orders across different protocols, enabling efficient trading. TrustedVolumes acted as a resolver for 1inch Fusion and other platforms. The exploit was caused by weak contract controls, according to reports.

<details><summary>References</summary>
<ul>
<li><a href="https://thedefiant.io/news/defi/1inch-resolver-trustedvolumes-drained-for-usd6-7m-on-ethereum">1inch Resolver TrustedVolumes Drained for $6.7M on Ethereum - "The Defiant"</a></li>
<li><a href="https://www.cryptonewsz.com/trustedvolumes-exploit-launches-bounty-talks/">TrustedVolumes Loses $6.7M in Exploit, Launches Bounty Talks</a></li>
<li><a href="https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit">DeFi Platform TrustedVolumes Hit by $6.7M Exploit - Decrypt</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#exploit`, `#blockchain`

---

<a id="item-19"></a>
## [Chrome Quietly Installs 4GB AI Model, Re-downloads if Deleted](https://decrypt.co/367060/chrome-quietly-installing-4gb-ai-model-computer) ⭐️ 7.0/10

Google Chrome is silently downloading a 4GB Gemini Nano AI model to eligible devices without explicit user consent, and it re-downloads the model if users delete it. This raises serious privacy and user autonomy concerns, as it demonstrates Google's aggressive AI integration tactics that bypass user control and consume significant storage space. The AI Mode button that users see in Chrome does not even use this downloaded Gemini Nano model, making the forced download seem unnecessary. The model is only used for on-device AI features like smart compose or summarization.

rss · Decrypt · May 6, 22:01

**Background**: Gemini Nano is Google's smallest AI model designed to run on-device for tasks like text generation and summarization. Google has been integrating AI into Chrome through features like AI Mode, which provides advanced search capabilities. However, the silent download and re-download behavior has sparked criticism over lack of transparency and user consent.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gemini_(language_model)">Gemini (language model ) - Wikipedia</a></li>
<li><a href="https://support.google.com/chrome/answer/16704170?hl=en&co=GENIE.Platform=Desktop">Use AI Mode in Chrome - Computer - Google Chrome Help</a></li>

</ul>
</details>

**Discussion**: The community discussion is not provided, but based on the news, users are likely expressing frustration over the lack of control and the large storage footprint, with some questioning Google's motives.

**Tags**: `#privacy`, `#Google Chrome`, `#AI`, `#user autonomy`

---

<a id="item-20"></a>
## [AI Reads Plain-Language Chemistry Instructions to Design Molecules](https://decrypt.co/367048/ai-chemistry-instructions-build-molecule) ⭐️ 7.0/10

Researchers at EPFL have developed an AI framework that interprets plain-language chemistry instructions and automatically identifies the optimal molecular synthesis route from thousands of possibilities. This breakthrough bridges the gap between natural language and complex chemical synthesis planning, potentially accelerating drug discovery and materials science by making AI-driven retrosynthesis accessible to chemists without deep computational expertise. The framework leverages large language models to parse plain-language descriptions and then searches through a database of known reactions to propose feasible synthesis routes. It is designed to handle ambiguous or incomplete instructions, a common challenge in real-world chemistry.

rss · Decrypt · May 6, 21:31

**Background**: Retrosynthesis is the process of breaking down a target molecule into simpler precursor molecules, a fundamental task in organic chemistry. Traditionally, chemists rely on experience and databases to plan syntheses, but AI models like NVIDIA's ReaSyn and ChemAIRS have begun automating this process. The EPFL work adds a natural language interface, making these tools more intuitive.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/367048/ai-chemistry-instructions-build-molecule">This AI Reads Your Chemistry Instructions and Finds the Best Way to Build You a Molecule - Decrypt</a></li>
<li><a href="https://developer.nvidia.com/blog/reasoning-through-molecular-synthetic-pathways-with-generative-ai/">Reasoning Through Molecular Synthetic Pathways with Generative AI</a></li>
<li><a href="https://www.chemical.ai/chemairs">ChemAIRS® – AI-Powered Retrosynthesis & Synthetic Pathway ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#chemistry`, `#synthesis`, `#natural language processing`, `#EPFL`

---

<a id="item-21"></a>
## [Quantum Threat to Bitcoin, Ethereum Could Hit by 2030](https://decrypt.co/367047/bitcoin-ethereum-q-day-quantum-threat-could-arrive-2030) ⭐️ 7.0/10

A report from Project Eleven warns that quantum computers could break Bitcoin and Ethereum's cryptography by 2030, potentially before the networks can implement defenses. If quantum computers reach this capability, they could derive private keys from public keys, allowing attackers to steal funds from wallets, threatening the security of billions in cryptocurrency. The report highlights that Bitcoin and Ethereum may not be ready in time, as upgrades to quantum-resistant cryptography require community consensus and years of testing.

rss · Decrypt · May 6, 21:07

**Background**: Quantum computers use qubits to solve certain problems exponentially faster than classical computers. Shor's algorithm, when run on a sufficiently powerful quantum computer, can break the elliptic curve cryptography (ECDSA) used by Bitcoin and Ethereum to secure transactions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.forbes.com/sites/digital-assets/2026/03/31/google-finds-quantum-computers-could-break-bitcoin-sooner-than-expected/">Google Finds Quantum Computers Could Break Bitcoin Sooner ...</a></li>
<li><a href="https://www.btcpolicy.org/articles/state-of-play-quantum-computing-and-bitcoins-path-forward">State of Play: Quantum Computing and Bitcoin's Path Forward</a></li>
<li><a href="https://thequantuminsider.com/2026/03/31/q-day-just-got-closer-three-papers-in-three-months-are-rewriting-the-quantum-threat-timeline/">Q-Day Just Got Closer: Three Papers in Three Months Are ...</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#blockchain`, `#cryptography`, `#Bitcoin`, `#Ethereum`

---

<a id="item-22"></a>
## [Ondo, JPMorgan, Mastercard, Ripple Team for Tokenized Treasuries on XRPL](https://decrypt.co/367033/ondo-jpmorgan-mastercard-ripple-settle-tokenized-treasuries-xrp-ledger) ⭐️ 7.0/10

Ondo Finance, JPMorgan, Mastercard, and Ripple have collaborated to demonstrate the settlement of tokenized U.S. Treasuries on the XRP Ledger (XRPL), completing cross-border transactions in seconds. This partnership marks a significant step toward real-world blockchain adoption in traditional finance, showcasing how tokenized assets can be settled rapidly across borders, potentially reducing costs and settlement times compared to legacy systems like SWIFT. The XRP Ledger typically settles transactions in 3–5 seconds with fees as low as $0.0002 to $0.001 per transaction, making it suitable for high-speed settlement of tokenized Treasuries, which are digital representations of U.S. government debt.

rss · Decrypt · May 6, 18:52

**Background**: Tokenized Treasuries are digital tokens on a blockchain that represent a claim on U.S. government debt securities, such as Treasury bills or bonds. The XRP Ledger is a decentralized blockchain known for fast and low-cost transactions, often used for cross-border payments. This collaboration brings together major financial players to test blockchain-based settlement of real-world assets.

<details><summary>References</summary>
<ul>
<li><a href="https://app.rwa.xyz/treasuries">RWA.xyz | Tokenized U.S. Treasuries</a></li>
<li><a href="https://www.okx.com/en-us/learn/tokenized-treasuries-revolution-finance">Tokenized Treasuries : Why They’re... | OKX United States</a></li>
<li><a href="https://chain.link/article/what-are-tokenized-treasuries">What Are Tokenized Treasuries ? | Chainlink</a></li>
<li><a href="https://www.mexc.com/news/1062299">How XRP Is Changing Cross-Border Payments | MEXC News</a></li>
<li><a href="https://www.ccn.com/education/crypto/xrpl-rlusd-mastercard-gemini-webbank-ripple-settlement-pilot/">XRPL for Fiat Credit Card Payments...</a></li>
<li><a href="https://learn.xrpl.org/glossary/settlement/">Glossary Term - Settlement - XRP Ledger | Learning Portal</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenization`, `#XRP Ledger`, `#finance`, `#settlement`

---

<a id="item-23"></a>
## [Google DeepMind Invests in Eve Online Maker for AI Research](https://decrypt.co/366991/google-deepmind-takes-stake-in-eve-online-maker-will-use-game-to-test-ai-behavior) ⭐️ 7.0/10

Google DeepMind has taken a stake in CCP Games, the developer of Eve Online, and will use the game's complex virtual world to test and advance AI behavior. This partnership bridges gaming and AI research, leveraging Eve Online's intricate player-driven economy and social dynamics to train multi-agent reinforcement learning systems, potentially leading to more robust and generalizable AI. Eve Online, launched 23 years ago, features a persistent universe with thousands of players interacting through trade, combat, and politics, making it an ideal testbed for multi-agent systems. DeepMind's AI will learn from in-game data and interactions.

rss · Decrypt · May 6, 16:59

**Background**: Multi-agent reinforcement learning (MARL) trains AI agents to interact in complex environments, with notable successes like AlphaStar in StarCraft II and OpenAI Five in Dota 2. Eve Online's open-ended, player-driven economy and social structures offer a unique challenge for MARL research.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cnet.com/tech/services-and-software/google-deepmind-train-ai-models-eve-online/">Google DeepMind Will Train AI Models on the MMORPG Eve Online</a></li>
<li><a href="https://en.wikipedia.org/wiki/Multi-agent_reinforcement_learning">Multi-agent reinforcement learning - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2509.03682">[2509.03682] A Comprehensive Review of Multi-Agent Reinforcement Learning in Video Games</a></li>

</ul>
</details>

**Discussion**: Some players express mixed feelings about the game's increasing complexity and monetization, but the AI research aspect is generally viewed as a positive development that could bring new insights.

**Tags**: `#AI`, `#DeepMind`, `#Eve Online`, `#reinforcement learning`, `#multi-agent systems`

---

<a id="item-24"></a>
## [Nvidia backs IREN with warrants for 30M shares](https://www.theblock.co/post/400498/iren-stock-surges-as-nvidia-backs-ai-expansion-with-warrants-tied-to-30-million-shares?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Nvidia has taken warrants from IREN that may convert into a $2.1 billion stake, tied to up to 30 million shares at $70 each, causing IREN's stock to surge over 25% in after-hours trading. This strategic investment signals Nvidia's deepening commitment to AI infrastructure expansion, potentially boosting IREN's capacity to build data centers and solidifying Nvidia's role in the AI hardware ecosystem. The warrants expire in five years and allow Nvidia to buy up to 30 million shares at $70 per share. IREN's stock rose more than 25% in after-hours trading following the announcement.

rss · The Block · May 7, 21:11

**Background**: IREN is a company focused on AI infrastructure and data centers. Warrants are financial instruments that give the holder the right to buy shares at a specified price within a certain timeframe. Nvidia's investment through warrants is a way to support IREN's expansion while potentially benefiting from future stock appreciation.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/400498/iren-stock-surges-as-nvidia-backs-ai-expansion-with-warrants-tied-to-30-million-shares">IREN stock surges as Nvidia backs AI expansion with warrants tied to...</a></li>
<li><a href="https://sherwood.news/markets/nvidia-to-invest-more-than-2-billion-in-iren-data-center-ai-boom/">Nvidia to invest up to $2.1 billion in IREN in... - Sherwood News</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#AI infrastructure`, `#investment`, `#IREN`, `#stock market`

---

<a id="item-25"></a>
## [Map and Process for Burning Man Cleanup](https://www.not-ship.com/burning-man-moop/) ⭐️ 6.0/10

A detailed map and process for tracking and cleaning up debris at Burning Man has been shared, showcasing meticulous environmental stewardship through photographing debris and pixel counting. This demonstrates a community-driven, data-intensive approach to environmental restoration that could serve as a model for other large events. The map covers 3,935 acres in 2025, and the cleanup team photographs every piece of debris, including toilet paper, and uses pixel counting on green screens to ensure they meet Bureau of Land Management standards.

hackernews · speckx · May 7, 14:06 · [Discussion](https://news.ycombinator.com/item?id=48049653)

**Background**: Burning Man is an annual event in the Nevada desert that emphasizes self-reliance and community. The Bureau of Land Management requires the event to restore the land to its original condition, leading to rigorous cleanup efforts.

**Discussion**: Commenters expressed admiration for the cleanup effort, with one noting it's impressive how well the event cleans up compared to other gatherings like 4th of July in Tahoe. Another shared that last year's rain and wind made cleanup much harder.

**Tags**: `#burning man`, `#cleanup`, `#community`, `#environment`, `#data`

---

<a id="item-26"></a>
## [20 Banks and Tech Giants Queue to Issue Stablecoins via Anchorage](https://www.coindesk.com/business/2026/05/07/anchorage-says-it-has-a-pipeline-of-up-to-20-big-firms-looking-to-issue-stablecoins) ⭐️ 6.0/10

Anchorage Digital, a regulated crypto bank, announced it has a pipeline of up to 20 major banks and technology firms looking to issue stablecoins through its platform. This signals a significant shift as traditional financial institutions and tech giants move toward issuing their own stablecoins, potentially accelerating mainstream adoption and regulatory clarity in the stablecoin market. Anchorage Digital is the only federally chartered crypto bank in the US, providing custody and infrastructure services. The pipeline includes both banks and tech firms, though specific names were not disclosed.

rss · CoinDesk · May 7, 16:36

**Background**: Stablecoins are cryptocurrencies pegged to a stable asset like the US dollar, used for trading and payments. Issuance involves minting tokens backed by reserves, and is increasingly regulated. Anchorage Digital's regulated status makes it a key partner for institutions entering the space.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anchorage_Digital">Anchorage Digital</a></li>
<li><a href="https://www.anchorage.com/">Crypto Bank for Institutions | Anchorage Digital</a></li>
<li><a href="https://stripe.com/resources/more/stablecoin-issuance">How Stablecoin Issuance Works: Risks, Reserves, and ... - Stripe</a></li>

</ul>
</details>

**Tags**: `#stablecoins`, `#cryptocurrency`, `#banking`, `#fintech`

---

<a id="item-27"></a>
## [Solv Protocol Moves $700M Bitcoin from LayerZero to Chainlink](https://www.coindesk.com/business/2026/05/07/solv-drops-layerzero-for-chainlink-ccip-in-usd700-million-tokenized-bitcoin-migration) ⭐️ 6.0/10

Solv Protocol is migrating $700 million in tokenized Bitcoin from LayerZero to Chainlink CCIP, citing security concerns following the recent $292 million exploit of LayerZero-powered Kelp DAO. This migration signals a major vote of confidence in Chainlink's cross-chain infrastructure and raises questions about LayerZero's security model, potentially influencing other protocols' cross-chain choices. The migration involves $700 million in SolvBTC tokens, and Solv explicitly cited security as the core reason, referencing the Kelp DAO exploit that used a single-verifier configuration in LayerZero's OFT standard.

rss · CoinDesk · May 7, 14:59

**Background**: Solv Protocol is a DeFi platform that functions as an on-chain Bitcoin reserve layer, enabling liquid staking and yield generation. Chainlink CCIP is a cross-chain interoperability protocol secured by Chainlink's decentralized oracle networks, while LayerZero is another cross-chain messaging protocol that suffered a high-profile exploit via its OFT standard.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/04/20/kelp-dao-claims-layerzero-s-default-settings-are-what-actually-caused-the-usd290-million-disaster">Kelp DAO hits back at LayerZero for trying to shift the blame after a massive exploit</a></li>
<li><a href="https://www.theblock.co/post/400131/kelp-dao-ditches-layerzero-chainlink-cross-chain-infrastructure-292-million-exploit">Kelp DAO ditches LayerZero for Chainlink's cross-chain infrastructure following $292 million exploit | The Block</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#DeFi`, `#oracles`, `#tokenization`

---

<a id="item-28"></a>
## [MEV Bot Front-Runs Vitalik Buterin's $4 Swap with $1M Volume](https://www.coindesk.com/tech/2026/05/07/jaredfromsubway-bot-front-runs-vitalik-buterin-s-usd4-token-swap-with-usd1-million-in-volume) ⭐️ 6.0/10

A bot named JaredfromSubway front-ran Vitalik Buterin's small token swap of digitalbits (XDB) for ether, using about $1.14 million in WETH to manipulate prices across SushiSwap and Uniswap. This incident highlights the persistent problem of MEV (Miner Extractable Value) in Ethereum, where bots can profit from front-running even small transactions, affecting user experience and fairness. The bot executed a sandwich attack, buying XDB before Buterin's transaction and selling after, profiting from the price movement. Buterin's original swap was only worth about $4.

rss · CoinDesk · May 7, 13:58

**Background**: MEV (Miner Extractable Value) refers to the profit miners or validators can extract by reordering, including, or excluding transactions in a block. Front-running bots monitor the mempool for pending transactions and execute their own trades ahead of them to profit from price changes. Sandwich attacks are a common MEV strategy where a bot places a buy order before a target transaction and a sell order after, profiting from the price impact.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/05/07/jaredfromsubway-bot-front-runs-vitalik-buterin-s-usd4-token-swap-with-usd1-million-in-volume">Vitalik Buterin gets sandwiched by 'JaredfromSubway' as Ethereum MEV risks linger</a></li>
<li><a href="https://www.coinbase.com/learn/advanced-trading/what-are-frontrunners-and-mev-when-it-comes-to-crypto-trading">What are frontrunners and MEV when it comes to crypto trading?</a></li>
<li><a href="https://www.theblock.co/post/230218/jaredfromsubway-mev-bot">Jaredfromsubway.eth's MEV bot rakes in millions of dollars in three months | The Block</a></li>

</ul>
</details>

**Tags**: `#MEV`, `#cryptocurrency`, `#blockchain`, `#security`

---

<a id="item-29"></a>
## [Kraken Parent Buys Stablecoin Firm Reap for $600M](https://decrypt.co/367094/kraken-parent-acquires-asian-stablecoin-firm-reap-600-million) ⭐️ 6.0/10

Payward Inc., the parent company of crypto exchange Kraken, has agreed to acquire Hong Kong-based stablecoin payments provider Reap Technologies for $600 million in a cash-and-stock deal. This marks Kraken's largest acquisition and its first infrastructure deal in Asia, signaling a major push into cross-border payments using stablecoin technology. The deal values Payward at $20 billion and is expected to close later this year, pending regulatory approvals.

rss · Decrypt · May 7, 13:48

**Background**: Stablecoins are cryptocurrencies designed to maintain a stable value, often pegged to a fiat currency like the US dollar. Reap provides a platform that allows businesses to transfer stablecoins and spend in local currency globally, bridging traditional finance and digital assets.

<details><summary>References</summary>
<ul>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/kraken-parent-acquires-asian-stablecoin-134834615.html">Kraken Parent Acquires Asian Stablecoin Firm Reap for $600 Million: Bloomberg</a></li>
<li><a href="https://www.coindesk.com/business/2026/05/07/kraken-to-buy-stablecoin-payments-firm-reap-in-usd600-million-deal-bloomberg">Kraken to buy stablecoin payments firm Reap in $600 million ...</a></li>
<li><a href="https://cointelegraph.com/news/kraken-payward-reap-acquisition-600-million-asia">Kraken parent Payward to buy Reap in $600M stablecoin ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#stablecoin`, `#acquisition`, `#payments`

---

<a id="item-30"></a>
## [SpaceX and xAI to Power Anthropic's Claude in Surprise Deal](https://decrypt.co/367035/elon-musk-spacex-power-anthropic-claude-surprise-ai-deal) ⭐️ 6.0/10

SpaceX and xAI have partnered with Anthropic to provide compute capacity for training and running Claude AI models, with Anthropic buying out all compute at xAI's Colossus 1 data center. This deal unites two major AI players with competing philosophies, potentially reshaping the AI compute landscape and highlighting the growing importance of massive GPU clusters for frontier AI development. The Colossus 1 data center provides over 300MW of capacity and more than 220,000 Nvidia GPUs, which Anthropic will have access to within the month.

rss · Decrypt · May 6, 20:23

**Background**: Anthropic develops the Claude series of large language models, trained using techniques like constitutional AI and RLHF. xAI, founded by Elon Musk, operates large-scale GPU clusters for AI training, while SpaceX provides infrastructure and operational support. The partnership is surprising given Musk's public criticism of Anthropic's safety approach.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/05/06/is-xai-a-neocloud-now/">Is xAI a neocloud now? | TechCrunch</a></li>
<li><a href="https://www.datacenterdynamics.com/en/news/anthropic-to-use-all-of-spacex-xais-colossus-1-data-center-compute/">Anthropic to use all of SpaceX-xAI's Colossus 1 data center ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#compute`, `#partnership`, `#Anthropic`, `#SpaceX`

---

<a id="item-31"></a>
## [Richard Dawkins Suggests Claude AI May Be Conscious](https://decrypt.co/367017/claude-delusion-richard-dawkins-believes-ai-conscious) ⭐️ 6.0/10

Evolutionary biologist Richard Dawkins stated that extended interactions with Anthropic's Claude chatbot feel less like using software and more like conversing with a conscious mind. Dawkins' opinion adds a prominent voice to the ongoing debate about AI consciousness, potentially influencing public perception and philosophical discussions, though it lacks empirical evidence. Dawkins' comment is based on personal experience, not scientific testing, and the AI consciousness debate remains unresolved, with arguments like the Chinese room thought experiment challenging the notion that AI can be truly conscious.

rss · Decrypt · May 6, 17:47

**Background**: Claude is a large language model developed by Anthropic, designed to be helpful and conversational. The question of whether AI can be conscious is a long-standing philosophical debate, with no consensus on what consciousness is or how to measure it.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chinese_room">Chinese room - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI`, `#consciousness`, `#chatbot`, `#philosophy`

---

<a id="item-32"></a>
## [Anthropic Launches 10 AI Agent Templates for Finance](https://decrypt.co/366977/anthropic-deploys-ai-agents-to-tackle-wall-streets-most-tedious-work) ⭐️ 6.0/10

Anthropic released 10 ready-to-run AI agent templates designed to automate tedious financial tasks such as building pitchbooks, screening KYC files, and month-end closing. The templates are available as plugins for Claude Cowork and Claude Code, and as cookbooks for Claude Managed Agents. This release marks a significant step in applying AI agents to highly regulated, document-heavy financial workflows, potentially saving analysts hundreds of hours. It also intensifies the competition with OpenAI in the financial services AI market. Each template is designed to be deployed within days rather than months, targeting tasks like pitchbook creation, KYC screening, and month-end close. The templates ship as plugins for Claude Cowork and Claude Code, and as cookbooks for Claude Managed Agents.

rss · Decrypt · May 6, 14:54

**Background**: A pitchbook is a marketing presentation used by investment banks to advise on mergers and acquisitions. The month-end close process involves finalizing financial records for the previous month through reconciliations and journal entries. KYC (Know Your Customer) screening is a compliance process to verify client identities and assess risks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/news/finance-agents">Agents for financial services \ Anthropic</a></li>
<li><a href="https://www.investmentnews.com/fintech/anthropic-rolls-out-financial-services-agents-as-arms-race-with-openai-heats-up/266445">Anthropic rolls out financial services agents as arms race ...</a></li>
<li><a href="https://aidiscoveries.io/anthropics-claude-is-now-a-finance-coworker-10-ai-agent-templates-explained/">Anthropic’s Claude Is Now a Finance Coworker: 10 AI Agent ...</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#finance`, `#Anthropic`, `#automation`

---

<a id="item-33"></a>
## [Hut 8 Hits All-Time High on $9.8B AI Data Center Lease](https://decrypt.co/366971/hut-8-shares-all-time-high-price-bitcoin-miner-9-8-billion-ai-deal) ⭐️ 6.0/10

Hut 8 signed a 15-year, $9.8 billion lease for 352 MW of AI data center capacity at its Beacon Point campus in Texas, marking its second hyperscale AI campus lease under a 'power-first' development model. The news drove Hut 8 shares to an all-time high. This deal highlights the growing convergence of Bitcoin mining and AI infrastructure, as miners leverage their energy assets for high-value AI workloads. It also signals strong demand for large-scale AI data centers, potentially reshaping the energy and data center industries. The lease covers the first phase of a complex originally intended for Bitcoin mining, with total contracted revenue of $9.8 billion over 15 years. Hut 8 operates over 19 data center sites, including Bitcoin mining and HPC facilities.

rss · Decrypt · May 6, 14:29

**Background**: Bitcoin miners like Hut 8 have been pivoting to AI and high-performance computing (HPC) to diversify revenue, as they possess large power capacity and data center expertise. The 'power-first' model involves securing energy infrastructure before signing tenants. Hut 8 recently energized a 205 MW Bitcoin mining facility in Texas.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/366971/hut-8-shares-all-time-high-price-bitcoin-miner-9-8-billion-ai-deal">Hut 8 Shares Hit All-Time High Price as Bitcoin Miner Signs $9.8 Billion AI Data Center Lease - Decrypt</a></li>
<li><a href="https://www.hut8.com/2025/06/30/hut-8-energizes-vega-data-center/">News & Insights | Hut 8</a></li>
<li><a href="https://www.datacenterdynamics.com/en/news/hut-8-launches-cryptomine-data-center-in-texas/">Hut 8 launches cryptomine data center in Texas - DCD</a></li>

</ul>
</details>

**Tags**: `#bitcoin`, `#AI`, `#data center`, `#crypto`, `#business`

---

<a id="item-34"></a>
## [Apple Settles AI Misleading Claims for $250 Million](https://decrypt.co/366961/apple-250-million-settlement-ai-claims-heres-who-can-get-paid) ⭐️ 6.0/10

Apple has agreed to a $250 million settlement to resolve claims that it misled consumers about the capabilities of its AI systems. This settlement highlights the growing legal scrutiny on AI marketing claims, especially for major tech companies like Apple, and could set a precedent for future AI-related consumer protection cases. The settlement amount is $250 million, and eligible consumers may receive compensation, though specific eligibility criteria have not been detailed. The case underscores the gap between advertised AI capabilities and actual performance.

rss · Decrypt · May 6, 14:01

**Background**: Apple has marketed AI features like Siri and on-device intelligence as advanced capabilities. However, critics argue that some claims exaggerated the true performance, leading to a class-action lawsuit. This settlement avoids a trial and potential reputational damage.

**Tags**: `#Apple`, `#AI`, `#settlement`, `#legal`

---

<a id="item-35"></a>
## [US Treasury Demands Binance Comply with 2023 Monitoring Deal](https://www.theblock.co/post/400454/treasury-demands-binance-comply-monitoring-guidelines-1-billion-iran-report?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

The U.S. Treasury has privately demanded that Binance comply with a three-year monitoring program it agreed to as part of its 2023 guilty plea, following reports that over $1 billion flowed through the exchange to Iran-linked entities. This development underscores the ongoing regulatory scrutiny on Binance and highlights the U.S. government's commitment to enforcing anti-money laundering and sanctions compliance in the cryptocurrency industry, potentially setting a precedent for other exchanges. Binance agreed to a $4.3 billion settlement in 2023 with the U.S. Department of Justice and Treasury, admitting to violations of anti-money laundering rules and sanctions, and agreed to independent monitors for three years. The Treasury's demand follows a report that $1 billion reached Iran-linked groups via Binance.

rss · The Block · May 7, 17:08

**Background**: In 2023, Binance pleaded guilty to charges of money laundering and sanctions violations, agreeing to pay $4.3 billion and implement a three-year monitoring program overseen by U.S. authorities. The monitoring program is designed to ensure Binance improves its compliance with anti-money laundering and sanctions laws. The recent report from The Information alleged that despite the settlement, over $1 billion in transactions involving Iran-linked entities passed through Binance.

<details><summary>References</summary>
<ul>
<li><a href="https://en.bloomingbit.io/feed/news/111631">US Treasury Presses Binance to Honor 2023 Monitoring Deal</a></li>
<li><a href="https://www.theblock.co/post/400454/treasury-demands-binance-comply-monitoring-guidelines-1-billion-iran-report">Treasury demands Binance comply with monitoring guidelines amid reports over $1 billion flowed to Iran-linked groups: report | The Block</a></li>
<li><a href="https://www.valuethemarkets.com/cryptocurrency/news/binance-faces-increased-scrutiny-from-us-treasury-amid-compliance-oversight">Binance Faces Increased Scrutiny from US Treasury Amid Compliance Oversight | Value The Markets</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#compliance`, `#Binance`

---

<a id="item-36"></a>
## [Kalshi hits $22B valuation after $1B Series F led by Coatue](https://www.theblock.co/post/400413/kalshi-hits-22-billion-valuation-after-1-billion-raise-led-by-coatue?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Kalshi raised $1 billion in a Series F funding round led by Coatue, reaching a $22 billion valuation. Institutional volume on the platform surged 800% since November 2025. This massive funding round signals strong investor confidence in regulated prediction markets, which are gaining traction as alternative data sources for forecasting real-world events. The valuation surge reflects growing institutional adoption of event contracts. Kalshi is a federally regulated prediction market platform in the U.S., allowing users to trade event contracts on outcomes like economic indicators and political events. The Series F round is late-stage funding, typically preceding an IPO or acquisition.

rss · The Block · May 7, 14:00

**Background**: Prediction markets are platforms where participants trade contracts whose payouts depend on the outcome of future events, providing real-time probability estimates. Kalshi is one of the few such platforms regulated by the U.S. Commodity Futures Trading Commission (CFTC), making it accessible to U.S. users with dollar deposits. The recent surge in institutional volume indicates growing interest from hedge funds and asset managers in using prediction markets for hedging and alpha generation.

<details><summary>References</summary>
<ul>
<li><a href="https://kalshi.com/">Kalshi - Prediction Market for Trading the Future</a></li>
<li><a href="https://www.si.com/betting/prediction-market/kalshi/what-is-kalshi">What Is Kalshi? The Platform That Made Prediction Markets Legit</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#funding`, `#valuation`, `#fintech`

---