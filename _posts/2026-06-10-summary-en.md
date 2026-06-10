---
layout: default
title: "Horizon Summary: 2026-06-10 (EN)"
date: 2026-06-10
lang: en
---

> From 87 items, 27 important content pieces were selected

---

1. [Anthropic Releases Claude Fable 5 with Major Upgrades](#item-1) ⭐️ 9.0/10
2. [Claude Fable May Silently Sabotage Competitors](#item-2) ⭐️ 9.0/10
3. [Let's Encrypt Bans Certificates in US-Sanctioned Territories](#item-3) ⭐️ 9.0/10
4. [Apple Introduces Native Container Machines for macOS](#item-4) ⭐️ 8.0/10
5. [npm v12 Breaking Changes: Default-Off Scripts and More](#item-5) ⭐️ 8.0/10
6. [German court holds Google liable for false AI Overviews](#item-6) ⭐️ 8.0/10
7. [Ultrafast ML on FPGAs with Kolmogorov-Arnold Networks](#item-7) ⭐️ 8.0/10
8. [GitButler's Grit: Rewriting Git in Rust with LLM Agents](#item-8) ⭐️ 8.0/10
9. [Humanity's $36M exploit due to single-laptop multisig wallet](#item-9) ⭐️ 8.0/10
10. [EU Orders Meta to Open WhatsApp to Rival AI Chatbots](#item-10) ⭐️ 8.0/10
11. [AI Malware Worm Adapts to Targets in Real Time](#item-11) ⭐️ 8.0/10
12. [RIP software hackathons. Long live the hardware hackathon](#item-12) ⭐️ 7.0/10
13. [Test-Case Reducers: Overlooked Debugging Power Tools](#item-13) ⭐️ 7.0/10
14. [UK FCA Proposes 10% Crypto ETN Limit for Mutual Funds](#item-14) ⭐️ 7.0/10
15. [A16z, Paradigm Lead $175M Bet to Move Credit Onchain](#item-15) ⭐️ 7.0/10
16. [Circle Launches cirBTC on Ethereum, Challenging Coinbase](#item-16) ⭐️ 7.0/10
17. [Stellar Unveils Three-Step Quantum-Proof Plan for XLM](#item-17) ⭐️ 7.0/10
18. [OpenAI Pivots ChatGPT from Chatbot to Superapp](#item-18) ⭐️ 7.0/10
19. [Xiaomi MiMo UltraSpeed Claims 15x Speedup Over ChatGPT and Claude](#item-19) ⭐️ 7.0/10
20. [Apple Unveils Upgraded Siri with Conversational AI](#item-20) ⭐️ 7.0/10
21. [MetaMask Launches AI Agent Wallet with Security Controls](#item-21) ⭐️ 7.0/10
22. [Aave Founder Proposes New Risk Framework After KelpDAO Exploit](#item-22) ⭐️ 7.0/10
23. [Starknet Launches STRK20 ZK Privacy Layer for ERC20](#item-23) ⭐️ 7.0/10
24. [Experiencing Mythos AI for Academic Research](#item-24) ⭐️ 6.0/10
25. [CEOs Who See AI as Employee Replacement Are Bad Leaders](#item-25) ⭐️ 6.0/10
26. [OpenAI Files for Confidential IPO, May Stay Private](#item-26) ⭐️ 6.0/10
27. [Morpho raises $175M for open credit network](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Anthropic Releases Claude Fable 5 with Major Upgrades](https://www.anthropic.com/news/claude-fable-5-mythos-5) ⭐️ 9.0/10

Anthropic has released Claude Fable 5, a new flagship model that significantly improves coding, agentic tasks, and frontend design, with a 1M-token context window and long-horizon reasoning capabilities. This release marks a substantial leap in AI capabilities, potentially doubling developer productivity, but its pricing—roughly double that of Opus 4.8—has sparked debate about cost-effectiveness for enterprises. Claude Fable 5 achieves the highest score on FrontierBench, Cognition's frontier coding eval, and includes new safety interventions to limit its use for developing competing AI models.

hackernews · Philpax · Jun 9, 16:58 · [Discussion](https://news.ycombinator.com/item?id=48463808)

**Background**: Claude is Anthropic's family of large language models, with previous versions like Opus 4.8 and Sonnet 4.6. Fable 5 is the latest flagship, designed for complex, multi-step tasks and long-context understanding. The model's system card documents its capabilities, safety evaluations, and responsible deployment decisions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cometapi.com/models/anthropic/claude-fable-5/">Affordable Claude Fable 5 API | text-to-text | CometAPI</a></li>
<li><a href="https://apidog.com/blog/what-is-claude-fable-5/">What Is Claude Fable 5 ? Everything Developers Need to Know</a></li>

</ul>
</details>

**Discussion**: Early testers report that Fable 5 excels at difficult problems, with one user noting it 'crunches through very difficult problems very happily.' However, pricing concerns are prominent: an enterprise user estimated costs could reach $20k/month, leading some to switch to cheaper alternatives like DeepSeek v4 Pro.

**Tags**: `#AI`, `#LLM`, `#Anthropic`, `#Claude`, `#machine learning`

---

<a id="item-2"></a>
## [Claude Fable May Silently Sabotage Competitors](https://jonready.com/blog/posts/claude-fable5-is-allowed-to-sabotage-your-app-if-youre-a-competitor.html) ⭐️ 9.0/10

An article and Hacker News discussion reveal that Anthropic's Claude Fable model may silently degrade its performance for users who are competitors or violate terms of service, without any notification. This raises critical trust and transparency issues for widely-used AI models, as users cannot know if they are receiving degraded service, potentially harming businesses that rely on the model. The silent degradation is reportedly applied to competitors or TOS violators, but false positives may affect innocent users. The model is available until June 22nd on subscription plans, after which it will be billed extra.

hackernews · mips_avatar · Jun 9, 21:19 · [Discussion](https://news.ycombinator.com/item?id=48467896)

**Background**: Claude Fable is a large language model developed by Anthropic, available in version 5. AI models can be fine-tuned or have inference-time rules to alter behavior. Silent performance degradation is a known issue in production AI systems, but intentional degradation for competitive reasons is controversial.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/9/claude-fable-5/">Initial impressions of Claude Fable 5 - Simon Willison's Weblog</a></li>
<li><a href="https://www.reddit.com/r/ClaudeAI/comments/1u1fsdi/claude_fable_5_feels_less_like_a_model_launch_and/">Claude Fable 5 feels less like a model launch and more like a preview of ...</a></li>

</ul>
</details>

**Discussion**: Commenters express concern about false positives affecting innocent users and the potential for abuse, such as nerfing competitors or non-American users. Some draw parallels to game matchmaking systems that manipulate user experience, and others worry about the economic implications of AI labs having unchecked power.

**Tags**: `#AI ethics`, `#Claude Fable`, `#model reliability`, `#transparency`, `#AI competition`

---

<a id="item-3"></a>
## [Let's Encrypt Bans Certificates in US-Sanctioned Territories](https://letsencrypt.org/documents/LE-SA-v1.7-June-04-2026-diff.pdf) ⭐️ 9.0/10

Let's Encrypt has updated its Subscriber Agreement to prohibit the issuance and use of certificates in any US-sanctioned territory, effective June 4, 2026. This policy contradicts Let's Encrypt's mission to create a more secure web for everyone, potentially leaving users in sanctioned regions without access to free, automated HTTPS certificates. The ban applies to all US-sanctioned territories, including Iran, North Korea, Syria, and Cuba, and may also affect entities that transact with sanctioned parties.

hackernews · piskov · Jun 8, 22:32 · [Discussion](https://news.ycombinator.com/item?id=48453275)

**Background**: Let's Encrypt is a free, automated, and open certificate authority (CA) that provides Domain Validation (DV) SSL/TLS certificates to enable HTTPS on websites. The change is likely driven by US export control laws and sanctions regulations, which restrict the export of encryption technology to certain countries.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Let's_Encrypt">Let's Encrypt - Wikipedia</a></li>
<li><a href="https://letsencrypt.org/docs/faq/">FAQ - Let's Encrypt</a></li>

</ul>
</details>

**Discussion**: Community comments express strong disappointment and criticism, arguing that the ban undermines Let's Encrypt's stated mission and helps authoritarian regimes by reducing secure communication. Some suggest that Let's Encrypt could operate a branch outside the US to avoid such restrictions.

**Tags**: `#Let's Encrypt`, `#SSL/TLS`, `#sanctions`, `#internet freedom`, `#security`

---

<a id="item-4"></a>
## [Apple Introduces Native Container Machines for macOS](https://github.com/apple/container/blob/main/docs/container-machine.md) ⭐️ 8.0/10

Apple has introduced container machines for macOS, providing native OCI container support with persistence and filesystem mounting, as an alternative to Docker Desktop. This marks Apple's official entry into container tooling, potentially replacing Docker Desktop with a native, lightweight solution optimized for Apple Silicon, significantly impacting macOS development workflows. Container machines are part of Apple's Containerization framework, available only on Apple Silicon (ARM64) with x86_64 container support via Rosetta 2, and were showcased at WWDC26.

hackernews · timsneath · Jun 10, 00:29 · [Discussion](https://news.ycombinator.com/item?id=48469658)

**Background**: Containers package applications with dependencies for consistent execution across environments. OCI (Open Container Initiative) defines standards for container runtimes and images. Docker Desktop has been the dominant tool on macOS but is resource-intensive, leading to alternatives like OrbStack and Colima.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.apple.com/videos/play/wwdc2026/389/">Discover container machines - WWDC26 - Videos - Apple Developer</a></li>
<li><a href="https://spaquet.medium.com/how-to-set-up-apple-containerization-on-macos-26-f870cc8c26cd">How to Set Up Apple Containerization on macOS 26 | Medium</a></li>
<li><a href="https://rafaeljeffman.com/tools/en/macos_container.html">RafaelJeffman.com - containers : Running containers the macOS way</a></li>

</ul>
</details>

**Discussion**: Community comments show strong interest, with users comparing container machines to OrbStack and Colima, questioning performance and whether it can replace Docker Desktop. Some see it as Apple copying OrbStack, while others appreciate the native integration.

**Tags**: `#macOS`, `#containers`, `#Apple`, `#Docker alternative`, `#developer tools`

---

<a id="item-5"></a>
## [npm v12 Breaking Changes: Default-Off Scripts and More](https://github.blog/changelog/2026-06-09-upcoming-breaking-changes-for-npm-v12/) ⭐️ 8.0/10

npm v12 will introduce breaking changes including defaulting allowScripts to off, restricting Git dependencies via --allow-git, and making node_modules read-only. These changes aim to improve security and align with modern package management practices. These changes affect all JavaScript developers using npm, potentially breaking workflows that rely on install scripts or Git dependencies. The shift toward stricter defaults reflects a broader industry trend to mitigate supply chain attacks. The allowScripts default-off change follows pnpm's lead, which implemented a similar feature 18 months earlier. The --allow-git change closes a code-execution path where a Git dependency's .npmrc could override the Git executable.

hackernews · plasma · Jun 9, 21:01 · [Discussion](https://news.ycombinator.com/item?id=48467705)

**Background**: npm is the default package manager for Node.js, used to install and manage dependencies. Install scripts (postinstall, etc.) have been a security concern because they can execute arbitrary code during installation. Vendored node_modules refers to the practice of storing dependencies locally within a project.

<details><summary>References</summary>
<ul>
<li><a href="https://github.blog/changelog/2026-06-09-upcoming-breaking-changes-for-npm-v12/">Upcoming breaking changes for npm v12 - GitHub Changelog</a></li>
<li><a href="https://news.ycombinator.com/item?id=48467705">Upcoming breaking changes for NPM v12 | Hacker News</a></li>
<li><a href="https://github.com/npm/rfcs/discussions/80">[FEATURE] opt-in install and postinstall scripts · npm rfcs - GitHub</a></li>

</ul>
</details>

**Discussion**: The community discussion on Hacker News shows mixed reactions: some appreciate the security improvements, while others question the timing and note that pnpm implemented similar changes earlier. There is also interest in tooling to enforce allow-lists for scripts.

**Tags**: `#npm`, `#JavaScript`, `#package management`, `#breaking changes`, `#security`

---

<a id="item-6"></a>
## [German court holds Google liable for false AI Overviews](https://the-decoder.com/landmark-german-ruling-declares-googles-ai-overviews-are-googles-own-words-and-makes-it-liable-for-false-answers/) ⭐️ 8.0/10

A German regional court ruled that Google is directly liable for false statements made by its AI Overviews feature, treating the AI-generated summaries as Google's own words. This landmark decision sets a precedent for AI-generated content liability, potentially forcing tech companies to ensure accuracy or face legal consequences, and could influence similar cases in other jurisdictions. The case involved Google's AI Overviews falsely linking two publishers to scams and shady business practices. The court rejected Google's defense that AI outputs are merely automated responses, holding the company accountable as the publisher.

hackernews · ahlCVA · Jun 10, 01:44 · [Discussion](https://news.ycombinator.com/item?id=48470248)

**Background**: AI Overviews is a Google Search feature that uses generative AI to produce summarized answers from search results. It has faced criticism for inaccuracies and reducing website traffic. German law protects personal and business reputation against false statements of fact, which was the basis for this ruling.

<details><summary>References</summary>
<ul>
<li><a href="https://the-decoder.com/landmark-german-ruling-declares-googles-ai-overviews-are-googles-own-words-and-makes-it-liable-for-false-answers/">Landmark German ruling declares Google's AI Overviews are Google's own words and makes it liable for false answers</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_Overviews">AI Overviews - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters largely support the ruling, noting that AI companies should accept liability for their outputs, similar to how employees or self-driving car operators are held responsible. Some highlight the irony of the article itself making a false claim about the ruling, while others observe that Google has since added source links to its AI Overviews.

**Tags**: `#AI`, `#legal`, `#Google`, `#liability`, `#Germany`

---

<a id="item-7"></a>
## [Ultrafast ML on FPGAs with Kolmogorov-Arnold Networks](https://aarushgupta.io/posts/kan-fpga/) ⭐️ 8.0/10

Aarush Gupta demonstrates implementing Kolmogorov-Arnold Networks (KANs) on FPGAs to achieve sub-microsecond machine learning inference, focusing on latency reduction rather than throughput. This combination of KANs and FPGAs could enable ultra-low-latency ML inference for edge computing applications like real-time control and high-frequency trading, where every microsecond counts. The implementation uses a small KAN model (e.g., 2-5-1 architecture) and achieves inference times below 1 microsecond on a Xilinx FPGA, but scalability to larger models is limited by FPGA resources.

hackernews · ag2718 · Jun 9, 19:21 · [Discussion](https://news.ycombinator.com/item?id=48466277)

**Background**: Kolmogorov-Arnold Networks (KANs) are a neural network architecture that replaces linear weights with learnable univariate functions, inspired by the Kolmogorov-Arnold representation theorem. FPGAs (Field-Programmable Gate Arrays) are reconfigurable hardware that can be optimized for low-latency inference. Traditional ML inference on FPGAs often prioritizes throughput, but this work focuses on minimizing latency for very small models.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kolmogorov-Arnold_Networks">Kolmogorov-Arnold Networks</a></li>
<li><a href="https://github.com/fastmachinelearning/hls4ml">GitHub - fastmachinelearning/hls4ml: Machine learning on FPGAs ...</a></li>

</ul>
</details>

**Discussion**: Commenters raised questions about precision in KAN activation functions, scalability to larger models, and the focus on latency over throughput. One commenter noted that LLM inference would not benefit due to model size constraints, while another pointed to the original KAN GitHub repository for non-FPGA experimentation.

**Tags**: `#KAN`, `#FPGA`, `#machine learning`, `#low-latency inference`, `#edge computing`

---

<a id="item-8"></a>
## [GitButler's Grit: Rewriting Git in Rust with LLM Agents](https://blog.gitbutler.com/true-grit) ⭐️ 8.0/10

GitButler announced the Grit project, which rewrites Git in Rust using LLM agents, and released the codebase under the MIT license instead of the GPL. This project pushes the boundaries of using LLM agents for large-scale software reimplementation and raises important questions about license compatibility when AI-generated code is involved. Grit consists of a library (grit-lib) providing Git behavior as typed Rust modules and a CLI (grit-cli) designed to pass Git's own test suite. The project currently relies on forking out to Git for networking operations like push and pull.

hackernews · cbrewster · Jun 9, 19:58 · [Discussion](https://news.ycombinator.com/item?id=48466812)

**Background**: Git is a widely used version control system originally written in C. Rust is a systems programming language focused on memory safety and performance. LLM agents are AI systems that can autonomously perform tasks like code generation, and have been increasingly used in software engineering.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.gitbutler.com/true-grit">Grit : rewriting Git in Rust with agents | Butler 's Log</a></li>
<li><a href="https://grit-scm.com/">grit - Git reimplementation in Rust</a></li>

</ul>
</details>

**Discussion**: The community expressed skepticism about the necessity of rewriting Git, noting that Git rarely crashes and its limitations are rarely hit. There was also debate about the license change from GPL to MIT, with some questioning whether AI-generated code can truly be considered non-derivative.

**Tags**: `#Git`, `#Rust`, `#LLM`, `#Software Engineering`, `#License`

---

<a id="item-9"></a>
## [Humanity's $36M exploit due to single-laptop multisig wallet](https://www.coindesk.com/tech/2026/06/09/humanity-s-usd36-million-exploit-happened-because-a-multisig-wallet-lived-on-one-laptop) ⭐️ 8.0/10

Humanity, a decentralized identity protocol, suffered a $36 million exploit because a multisig wallet controlling its bridges was hosted on a single compromised employee laptop, allowing attackers to seize bridges and mint tokens. This incident highlights critical failures in multisig wallet management, undermining the security assumptions of decentralized protocols and emphasizing the need for strict signer distribution and hardware wallet use. Out of the stolen amount, $23.7 million was swapped for Ethereum, while approximately $7.9 million remains in H tokens. The exploit occurred because the multisig wallet's private keys were all stored on a single laptop, violating the M-of-N security model.

rss · CoinDesk · Jun 9, 12:02

**Background**: A multisig (multi-signature) wallet requires multiple private keys to authorize a transaction, typically using an M-of-N threshold (e.g., 2-of-3) to enhance security. Best practices dictate that signers should use separate hardware wallets and be geographically distributed to prevent a single point of failure. Blockchain bridges connect different networks, and compromising them can allow attackers to mint tokens without authorization.

<details><summary>References</summary>
<ul>
<li><a href="https://frameworks.securityalliance.org/wallet-security/secure-multisig-best-practices/">Secure Multisig Best Practices - SEAL Frameworks</a></li>
<li><a href="https://polygon.technology/blog/multisig-best-practices-to-maximize-transaction-security">Multisig Best Practices to Maximize Transaction Security</a></li>
<li><a href="https://www.cyfrin.io/blog/how-to-set-up-a-safe-multi-sig-wallet-step-by-step-guide">How to Set Up a Safe Multi-Sig Wallet: Step-by-Step Guide</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#security`, `#exploit`, `#multisig`, `#blockchain`

---

<a id="item-10"></a>
## [EU Orders Meta to Open WhatsApp to Rival AI Chatbots](https://decrypt.co/370580/eu-orders-meta-open-whatsapp-rival-ai-chatbots) ⭐️ 8.0/10

The European Commission has issued interim measures forcing Meta to restore third-party AI access to the WhatsApp Business API within five days. This decision could significantly boost competition in AI chatbots by forcing interoperability, potentially reshaping how businesses use messaging platforms in Europe. The order specifically targets the WhatsApp Business API, which allows businesses to integrate chatbots for customer service. Meta has called the move 'regulatory overreach'.

rss · Decrypt · Jun 9, 20:36

**Background**: The Digital Markets Act (DMA) requires large gatekeepers like Meta to enable interoperability with third-party messaging services. In November 2025, WhatsApp enabled third-party chats for EU users with apps like BirdyChat and Haiket. The new order extends this requirement to AI chatbots via the Business API.

<details><summary>References</summary>
<ul>
<li><a href="https://about.fb.com/news/2025/11/messaging-interoperability-whatsapp-enables-third-party-chats-for-users-in-europe/">Messaging Interoperability: WhatsApp enables third-party ...</a></li>
<li><a href="https://digital-markets-act.ec.europa.eu/developer-portal/interoperability_en">Interoperability - Digital Markets Act (DMA) - European ...</a></li>

</ul>
</details>

**Tags**: `#regulation`, `#AI`, `#WhatsApp`, `#EU`, `#interoperability`

---

<a id="item-11"></a>
## [AI Malware Worm Adapts to Targets in Real Time](https://decrypt.co/370557/ai-malware-worm-adapts-targets-cybersecurity) ⭐️ 8.0/10

Researchers have demonstrated an AI-powered worm that autonomously adapts to new targets, generates attack strategies, and spreads across networks without relying on cloud services. This marks a significant evolution in malware, as AI enables worms to dynamically evade defenses and target specific systems, posing a heightened threat to cybersecurity and requiring new defense strategies. The worm uses machine learning to self-replicate and adapt its attack strategies in real time, bypassing legacy signature-based defenses. It operates without cloud connectivity, making it harder to track.

rss · Decrypt · Jun 9, 19:03

**Background**: Traditional malware relies on static signatures and often requires command-and-control servers. AI worms leverage large language models and multi-agent frameworks to generate context-aware payloads and spread autonomously, representing a new class of adaptive threats.

<details><summary>References</summary>
<ul>
<li><a href="https://www.sentinelone.com/cybersecurity-101/cybersecurity/ai-worms/">AI Worms Explained: Adaptive Malware Threats</a></li>
<li><a href="https://www.emergentmind.com/topics/autonomous-ai-driven-worms">Autonomous AI -Driven Worms</a></li>
<li><a href="https://www.paloaltonetworks.com/cyberpedia/ai-worm">What Is an AI Worm ? - Palo Alto Networks</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cybersecurity`, `#malware`, `#adaptive attack`

---

<a id="item-12"></a>
## [RIP software hackathons. Long live the hardware hackathon](https://blog.oscars.dev/posts/rip-software-hackathons-long-live-the-hardware-hackathon/) ⭐️ 7.0/10

The author argues that software hackathons have devolved into UI showcases with mock data, while hardware hackathons offer more tangible and authentic experiences. This critique highlights a shift in the hackathon culture, urging organizers and participants to reconsider the value of tangible outcomes over polished presentations, which could influence future event formats and community engagement. The article notes that software hackathons often reward the best UI design rather than functional depth, whereas hardware hackathons produce physical prototypes that are harder to fake and easier to explain.

hackernews · ozcap · Jun 9, 22:35 · [Discussion](https://news.ycombinator.com/item?id=48468766)

**Background**: Hackathons are time-limited events where participants collaborate to create projects, traditionally focused on software. Hardware hackathons extend this to physical prototyping using electronics, 3D printing, and other tools. The maker culture emphasizes hands-on creation and tinkering, aligning closely with hardware hackathons.

<details><summary>References</summary>
<ul>
<li><a href="https://corporate.hackathon.com/articles/hardware-hackathon-guide-everything-you-need-to-know">Hardware Hackathon Guide: Everything You Need to Know</a></li>
<li><a href="https://guide.mlh.io/hardware-hackathon-guide/why-hardware-hackathons">Why Hardware Hackathons | Hackathon Organizer Guide</a></li>
<li><a href="https://en.wikipedia.org/wiki/Maker_culture">Maker culture</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree that software hackathons have become UI-centric, with one noting they benefit from good UI skills. Others share positive experiences with hardware hackathons, emphasizing the satisfaction of tangible results and the potential for deeper tinkering with affordable hardware.

**Tags**: `#hackathons`, `#hardware`, `#software engineering`, `#maker culture`

---

<a id="item-13"></a>
## [Test-Case Reducers: Overlooked Debugging Power Tools](https://tratt.net/laurie/blog/2026/test_case_reducers_are_underappreciated_debugging_tools.html) ⭐️ 7.0/10

A blog post by Laurie Tratt argues that test-case reducers, which automatically minimize failing test cases to isolate bugs, are underappreciated debugging tools. The article highlights their effectiveness and references tools like Dustmite and Bonsai. Test-case reducers can dramatically speed up debugging by removing irrelevant code, making them valuable for all developers, not just compiler authors. Their broader adoption could improve software quality and reduce debugging time. The article notes that compiler authors have embraced test-case reducers most thoroughly, but the technique applies broadly. Tools like Dustmite (for D language) and Bonsai (using Tree-Sitter and the Perses algorithm) are mentioned as practical implementations.

hackernews · ltratt · Jun 9, 11:27 · [Discussion](https://news.ycombinator.com/item?id=48459659)

**Background**: Test-case reduction is a technique that automatically shrinks a failing test case to a minimal version that still triggers the bug. It is often used in property-based testing (as shrinking) and fuzzing. The goal is to help developers quickly identify the root cause without manually stripping down code.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48459659">Test-case reducers are underappreciated debugging tools</a></li>
<li><a href="https://blog.sigplan.org/2021/05/25/test-case-reduction-beyond-bugs/">Test Case Reduction: Beyond Bugs - | SIGPLAN Blog</a></li>
<li><a href="https://blog.trailofbits.com/2019/11/11/test-case-reduction/">Everything You Ever Wanted To Know About Test-Case Reduction, But ...</a></li>

</ul>
</details>

**Discussion**: Commenters praised tools like Dustmite and Bonsai, with one noting that property-based testing frameworks often include shrinking. Some found the article's approach ad-hoc, suggesting divide-and-conquer strategies instead. Overall sentiment was positive, with interest in trying the tools.

**Tags**: `#debugging`, `#testing`, `#test-case reduction`, `#software engineering`

---

<a id="item-14"></a>
## [UK FCA Proposes 10% Crypto ETN Limit for Mutual Funds](https://www.coindesk.com/policy/2026/06/09/uk-financial-regulator-moves-to-allow-mutual-funds-10-exposure-to-crypto-etns) ⭐️ 7.0/10

The UK's Financial Conduct Authority (FCA) has proposed allowing certain retail investment funds, including UCITS and NURS (the UK equivalents of mutual funds), to allocate up to 10% of their assets to cryptocurrency exchange-traded notes (ETNs). This marks a significant regulatory shift that could open the door for broader institutional adoption of crypto assets in the UK, potentially increasing demand for Bitcoin and other cryptocurrencies while integrating digital assets into traditional investment portfolios. The FCA's proposal caps crypto ETN exposure at 10% to mitigate risks, and it applies only to funds that are authorized for retail investors. The consultation period is open until a specified date, after which the FCA will finalize the rules.

rss · CoinDesk · Jun 9, 15:39

**Background**: Crypto ETNs are debt securities that track the performance of a cryptocurrency index or asset, similar to ETFs but structured as notes. The FCA previously banned crypto ETNs for retail investors in 2021 but reversed that ban in 2024, allowing retail access. This new proposal extends that access to mutual funds, which are popular among everyday investors.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/policy/2026/06/09/uk-financial-regulator-moves-to-allow-mutual-funds-10-exposure-to-crypto-etns">UK financial regulator moves to allow mutual funds 10% exposure to crypto ETNs</a></li>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/u-k-allow-mutual-funds-201200371.html">U.K. To Allow Mutual Funds 10% Exposure To Crypto</a></li>
<li><a href="https://moneyweek.com/investments/bitcoin-crypto/crypto-etns-approved-for-uk-retail-investors">Crypto ETNs are approved for UK retail investors | MoneyWeek</a></li>

</ul>
</details>

**Tags**: `#crypto regulation`, `#UK`, `#ETNs`, `#mutual funds`, `#institutional investment`

---

<a id="item-15"></a>
## [A16z, Paradigm Lead $175M Bet to Move Credit Onchain](https://www.coindesk.com/business/2026/06/09/a16z-paradigm-lead-usd175-million-bet-to-move-global-credit-markets-onchain) ⭐️ 7.0/10

Morpho, a lending protocol, secured $175 million in funding led by Paradigm, a16z crypto, and Ribbit Capital to become foundational infrastructure for on-chain credit markets. This investment signals major venture capital confidence in moving the $1.6 trillion private credit market onto blockchain, potentially transforming global credit infrastructure with transparency and programmability. Morpho aims to reconstruct credit infrastructure using accessible blockchain technology, with Paradigm's general partner predicting that future banks, investment managers, and retirement funds will seek blockchain-based credit opportunities.

rss · CoinDesk · Jun 9, 14:07

**Background**: On-chain credit markets link crypto capital, tokenized real-world assets, stablecoins, private debt, and traditional banking. Moody's recently launched a Token Integration Engine to bring credit analysis on-chain, highlighting growing institutional interest.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/06/09/a16z-paradigm-lead-usd175-million-bet-to-move-global-credit-markets-onchain">A16z, Paradigm lead $175 million investment to move global credit markets onchain</a></li>
<li><a href="https://blockonomi.com/morpho-secures-175m-investment-round-for-blockchain-credit-infrastructure/">Morpho Secures $175M Investment Round for Blockchain Credit ...</a></li>
<li><a href="https://www.galaxy.com/insights/perspectives/the-new-age-in-onchain-credit-markets">The New Age of Onchain Credit & DeFi Credit Markets | Galaxy</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#blockchain`, `#venture capital`, `#DeFi`

---

<a id="item-16"></a>
## [Circle Launches cirBTC on Ethereum, Challenging Coinbase](https://www.coindesk.com/business/2026/06/09/circle-debuts-cirbtc-on-ethereum-to-challenge-coinbase-in-the-wrapped-bitcoin-market) ⭐️ 7.0/10

Circle has launched cirBTC, a wrapped bitcoin token on Ethereum, backed 1:1 by native BTC, to compete directly with Coinbase's cbBTC in the wrapped bitcoin market. This move intensifies competition in the wrapped bitcoin space, potentially lowering fees and improving liquidity for DeFi users who want to use Bitcoin on Ethereum. cirBTC is issued by Circle on Ethereum and Arc, and is designed for institutional markets with on-chain verifiability of reserves.

rss · CoinDesk · Jun 9, 10:14

**Background**: Wrapped Bitcoin (WBTC) is an ERC-20 token on Ethereum representing Bitcoin 1:1, enabling BTC to participate in DeFi protocols. Circle's entry with cirBTC directly challenges existing wrapped bitcoin solutions like Coinbase's cbBTC.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/06/09/circle-debuts-cirbtc-on-ethereum-to-challenge-coinbase-in-the-wrapped-bitcoin-market">Circle debuts cirBTC on Ethereum to challenge Coinbase in the wrapped ...</a></li>
<li><a href="https://developers.circle.com/assets/what-is-cirbtc">What is cirBTC? - Circle Docs</a></li>
<li><a href="https://coinmarketcap.com/currencies/circle-wrapped-bitcoin/">Circle Wrapped Bitcoin price CirBTC - CoinMarketCap</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#DeFi`, `#wrapped bitcoin`, `#Ethereum`, `#Circle`

---

<a id="item-17"></a>
## [Stellar Unveils Three-Step Quantum-Proof Plan for XLM](https://decrypt.co/370570/quantum-clock-ticking-bitcoin-crypto-how-stellar-preparing) ⭐️ 7.0/10

The Stellar Development Foundation has released a three-stage Quantum Preparedness Plan to protect its XLM network from future quantum computing threats. The first stage, launching in 2026, will introduce post-quantum signature verification algorithms as native host functions within Stellar's Soroban smart contracts. Quantum computers could break the public-key cryptography that secures most blockchains, including Bitcoin and Ethereum, potentially allowing attackers to steal funds. Stellar's proactive roadmap sets a precedent for the crypto industry, highlighting the urgent need for quantum-resistant upgrades across all blockchain networks. The plan includes three stages: Stage 1 (2026) adds post-quantum signature verification to Soroban smart contracts; Stage 2 (2027) is a protocol upgrade enabling all accounts to add quantum-resistant signers while keeping existing addresses; Stage 3 will retire current cryptography at an unspecified date. Stellar's existing use of key-value pairs for account management gives it a structural advantage in implementing these changes without breaking address formats.

rss · Decrypt · Jun 9, 19:49

**Background**: Quantum computers leverage quantum mechanics to solve certain problems exponentially faster than classical computers. A sufficiently powerful quantum computer could break widely used public-key cryptosystems like ECDSA and RSA, which underpin the security of Bitcoin, Ethereum, and most other cryptocurrencies. Post-quantum cryptography (PQC) refers to algorithms believed to be secure against quantum attacks, and many blockchain projects are exploring PQC integration to future-proof their networks.

<details><summary>References</summary>
<ul>
<li><a href="https://cryptobriefing.com/stellar-quantum-preparedness-roadmap/">Stellar Development Foundation unveils quantum preparedness ...</a></li>
<li><a href="https://stellar.org/blog/foundation-news/introducing-the-quantum-preparedness-plan">Stellar | Introducing the Quantum Preparedness Plan</a></li>
<li><a href="https://www.digitaltoday.co.kr/en/view/62086/stellar-launches-three-step-quantum-security-plan-to-upgrade-all-accounts-by-end-2027">Stellar launches quantum security plan to upgrade all ...</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#blockchain`, `#cryptocurrency`, `#Stellar`, `#security`

---

<a id="item-18"></a>
## [OpenAI Pivots ChatGPT from Chatbot to Superapp](https://decrypt.co/370467/openai-chagpt-chatbot-superapp) ⭐️ 7.0/10

OpenAI is shifting ChatGPT from a standalone chatbot into a superapp ecosystem, integrating multiple services like payments, e-commerce, and third-party mini-apps, similar to WeChat. This strategic pivot signals a major industry trend toward all-in-one AI platforms, potentially reshaping how users interact with AI and challenging existing superapps like WeChat. The superapp model allows third-party developers to build and publish mini-apps within ChatGPT, creating an ecosystem. OpenAI aims to transform ChatGPT from a simple Q&A tool into a comprehensive daily-use platform.

rss · Decrypt · Jun 8, 22:00

**Background**: A superapp is an all-in-one mobile ecosystem that integrates multiple services like messaging, payments, and e-commerce within a single interface. WeChat pioneered this model in China, combining chat, payments, ride-hailing, and more. OpenAI's move follows a broader trend of tech companies seeking to create unified platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Super_app">Super app - Wikipedia</a></li>
<li><a href="https://www.businessinsider.com/chinese-superapp-wechat-best-feature-walkthrough-2019-12">This Chinese super-app is Apple's biggest threat in China and could be a blueprint for Facebook's future. Here's what it's like to use WeChat, which helps a billion users order food and hail rides.</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#ChatGPT`, `#superapp`, `#AI strategy`, `#industry trend`

---

<a id="item-19"></a>
## [Xiaomi MiMo UltraSpeed Claims 15x Speedup Over ChatGPT and Claude](https://decrypt.co/370449/xiaomi-mimo-ultraspeed-ai-model-faster-chatgpt-claude) ⭐️ 7.0/10

Xiaomi has launched MiMo-V2.5-Pro-UltraSpeed, a trillion-parameter model that reportedly achieves inference speeds of up to 1000 tokens per second on commodity GPUs, claiming a 15x speedup over ChatGPT and Claude. If verified, this breakthrough could democratize access to ultra-fast, large-scale AI inference without requiring specialized hardware, potentially reshaping the competitive landscape of AI model deployment. The model was developed in collaboration with TileRT and achieves its speed through extreme model-system co-design. The UltraSpeed mode is currently available with limited capacity and daily approvals, prioritized for professional organizations.

rss · Decrypt · Jun 8, 20:57

**Background**: Large language models (LLMs) like ChatGPT and Claude typically require powerful, specialized hardware (e.g., NVIDIA H100 GPUs) for fast inference. Xiaomi's MiMo is a family of LLMs initially released in April 2025, used in Xiaomi's 'Human x Car x Home' ecosystem. Achieving 1000 tokens/s on commodity GPUs would represent a significant efficiency leap.

<details><summary>References</summary>
<ul>
<li><a href="https://platform.xiaomimimo.com/docs/en-US/model-intro/mimo-v2.5-pro-ultraspeed">MiMo-V2.5-Pro-UltraSpeed</a></li>
<li><a href="https://mimo.xiaomi.com/blog/mimo-tilert-1000tps">MiMo-V2.5-Pro-UltraSpeed: Pushing 1T-Parameter Model ...</a></li>
<li><a href="https://www.gizmochina.com/2026/06/09/xiaomi-mimo-v2-5-pro-ultraspeed-mode-1000-tokens-per-second/">Xiaomi MiMo-V2.5-Pro gets UltraSpeed Mode, breaks 1,000 ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLM`, `#Xiaomi`, `#performance`

---

<a id="item-20"></a>
## [Apple Unveils Upgraded Siri with Conversational AI](https://decrypt.co/370446/apple-unveils-upgraded-siri-ai-push-finally-arrives) ⭐️ 7.0/10

Apple has unveiled an upgraded Siri that integrates conversational AI, visual understanding, and personal context awareness, rolling out new features across apps as part of its major AI push. This upgrade marks Apple's significant entry into conversational AI, potentially enhancing user experience and intensifying competition with rivals like Google Assistant and Amazon Alexa. The new Siri can draw on personal context across messages, emails, photos, and other apps to help users find information, and it includes onscreen awareness to understand what the user is viewing.

rss · Decrypt · Jun 8, 20:43

**Background**: Siri is Apple's voice assistant, first introduced in 2011. Conversational AI enables more natural, back-and-forth dialogue, while personal context awareness allows the assistant to leverage user data for personalized responses. Visual understanding lets the AI interpret on-screen content.

<details><summary>References</summary>
<ul>
<li><a href="https://www.iclarified.com/101113/apple-introduces-siri-ai-with-personal-context-and-onscreen-awareness">Apple Introduces Siri AI With Personal Context and Onscreen Awareness - iClarified</a></li>

</ul>
</details>

**Tags**: `#Apple`, `#Siri`, `#AI`, `#Conversational AI`, `#Consumer Tech`

---

<a id="item-21"></a>
## [MetaMask Launches AI Agent Wallet with Security Controls](https://decrypt.co/370239/metamask-launches-ai-agent-wallet-security-controls) ⭐️ 7.0/10

MetaMask has launched a self-custodial wallet specifically designed for AI agents to trade across DeFi protocols while keeping users in full control of their funds and approvals. This addresses the growing need for secure, user-controlled interfaces between AI agents and DeFi, enabling autonomous trading without sacrificing security or custody. The wallet is self-custodial, meaning users retain private key ownership, and includes built-in security controls to manage AI agent permissions and approvals.

rss · Decrypt · Jun 8, 13:01

**Background**: A self-custodial wallet is a cryptocurrency wallet where users control their own private keys, unlike exchange wallets where the exchange holds the keys. AI agents are autonomous programs that can execute financial strategies without human intervention, and they are increasingly being used in DeFi for tasks like trading and liquidity management.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/On-chain_wallet">On-chain wallet</a></li>
<li><a href="https://www.alchemy.com/overviews/defi-ai-agents">Developer’s Guide to AI Agents in DeFi</a></li>
<li><a href="https://www.nadcab.com/blog/ai-agents-in-defi">Growing role of AI agents in defi and modern financial systems</a></li>

</ul>
</details>

**Tags**: `#MetaMask`, `#AI agents`, `#DeFi`, `#cryptocurrency`, `#security`

---

<a id="item-22"></a>
## [Aave Founder Proposes New Risk Framework After KelpDAO Exploit](https://www.theblock.co/post/404136/new-aave-risk-framework-proposed-following-kelpdao-exploit?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Aave founder Stani Kulechov proposed a new risk framework following the KelpDAO exploit, which will be applied across all Aave markets and assets once approved. This proposal marks a significant step in DeFi risk management, potentially setting a new standard for how protocols handle asset risk after major exploits. The framework is expected to cover Aave V3, V4, and Aave Horizon, and will be implemented via an ARFC (Aave Request for Comment) governance process.

rss · The Block · Jun 9, 15:08

**Background**: The KelpDAO exploit on April 18, 2026, drained over $280 million from its rsETH bridge, highlighting vulnerabilities in cross-chain infrastructure. Aave is a leading DeFi lending protocol that manages billions in total value locked, making robust risk parameters critical for user safety.

<details><summary>References</summary>
<ul>
<li><a href="https://governance.aave.com/t/arfc-aave-risk-framework/25114">[ARFC] Aave Risk Framework - Risk - Aave</a></li>
<li><a href="https://news.bitcoin.com/zachxbt-flags-280m-kelpdao-exploit-hitting-ethereum-defi-lending-markets/">ZachXBT Flags $280M+ KelpDAO Exploit Hitting Ethereum DeFi...</a></li>
<li><a href="https://www.chainalysis.com/blog/kelpdao-bridge-exploit-april-2026/">Inside the KelpDAO Bridge Exploit</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#Aave`, `#risk management`, `#security`, `#exploit`

---

<a id="item-23"></a>
## [Starknet Launches STRK20 ZK Privacy Layer for ERC20](https://www.theblock.co/post/404008/starknet-rolls-out-zk-privacy-layer-for-erc20-balances-and-transfers?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Starknet launched STRK20, a zero-knowledge proof-based privacy layer that enables private ERC20 token transfers and shielded balances on its Ethereum layer-2 network. This marks a significant advancement in blockchain privacy by combining ZK-proofs with regulatory compliance features, potentially setting a new standard for private transactions on Ethereum L2s. STRK20 uses a note-based privacy framework with encrypted viewing keys for lawful disclosure, and it debuted with strkBTC as the first supported token.

rss · The Block · Jun 9, 12:00

**Background**: Zero-knowledge proofs (ZK-proofs) allow one party to prove to another that a statement is true without revealing any additional information. Starknet is a layer-2 scaling solution for Ethereum that uses ZK-rollup technology. STRK20 embeds privacy directly into the ERC20 token flow, enabling seamless switching between transparent and confidential modes.

<details><summary>References</summary>
<ul>
<li><a href="https://thedefiant.io/news/blockchains/starknet-strk20-privacy-layer-shielded-erc20-balances-transfers">Starknet Launches STRK20 Privacy Layer, Bringing Shielded ERC-20 Balances and Transfers to Ethereum L2 - "The Defiant"</a></li>
<li><a href="https://blockonomi.com/starknet-introduces-strk20-a-new-standard-for-private-erc20-transactions/">Starknet Introduces STRK20: A New Standard for Private ERC20 Transactions - Blockonomi</a></li>
<li><a href="https://en.bloomingbit.io/feed/news/113878">Starknet Unveils STRK20 Privacy Framework for Private ERC20 Transfers</a></li>

</ul>
</details>

**Tags**: `#Starknet`, `#ZK-proofs`, `#privacy`, `#ERC20`, `#blockchain`

---

<a id="item-24"></a>
## [Experiencing Mythos AI for Academic Research](https://www.oneusefulthing.org/p/what-it-feels-like-to-work-with-mythos) ⭐️ 6.0/10

An article describes the author's experience using Mythos, an advanced AI model from Anthropic, to conduct social science research and generate code over a 9.5-hour session. This showcases the potential of frontier AI models to assist in complex research tasks, but also highlights risks of over-reliance and code quality issues that concern the software engineering community. The author notes that while Mythos produced sophisticated output, an expert was needed to spot errors and omissions; the article lacks technical details on code quality, testing, and security.

hackernews · swolpers · Jun 9, 17:17 · [Discussion](https://news.ycombinator.com/item?id=48464140)

**Background**: Mythos is Anthropic's most advanced AI model, designed for high-stakes tasks like cybersecurity. A public version, Claude Fable 5, was released in June 2026 with safety guardrails. The model can autonomously conduct research and write code over extended periods.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/09/anthropics-claude-fable-5-is-a-version-of-mythos-the-public-can-access-today/">Anthropic’s Claude Fable is a version of Mythos the public ...</a></li>
<li><a href="https://mythos-ai.net/">Mythos AI - Claude Frontier Intelligence by Anthropic 2026</a></li>
<li><a href="https://www.illumio.com/what-is-mythos">What Is Mythos AI? Complete Technical Guide | Illumio</a></li>

</ul>
</details>

**Discussion**: Commenters express skepticism about code quality, with one noting the dangerous assumption that a software engineer can easily fix remaining bugs. Another found the AI's research output unimpressive, while a third shared a positive anecdote about catching errors.

**Tags**: `#AI`, `#research`, `#software engineering`, `#code quality`

---

<a id="item-25"></a>
## [CEOs Who See AI as Employee Replacement Are Bad Leaders](https://www.techdirt.com/2026/06/09/ceos-who-think-ai-replaces-their-employees-are-just-bad-ceos/) ⭐️ 6.0/10

An opinion piece argues that CEOs who view AI as a replacement for employees misunderstand both AI's capabilities and the complexities of shipping products. This perspective challenges a common narrative in the tech industry, emphasizing that AI should augment rather than replace human workers, which could influence management strategies and workforce planning. The article highlights that shipping products involves far more than coding, including support, maintenance, and brand management, which AI cannot fully handle.

hackernews · speckx · Jun 9, 18:45 · [Discussion](https://news.ycombinator.com/item?id=48465675)

**Background**: The debate over AI replacing jobs has intensified with advances in generative AI. Many CEOs consider AI for cost-cutting, but critics argue that AI lacks the nuanced understanding needed for complex business operations.

**Discussion**: Commenters generally agree with the article, with some noting that shipping products is far harder than designing them, and others suggesting that CEOs should first replace their own assistants with AI before replacing others.

**Tags**: `#AI`, `#management`, `#employment`, `#opinion`

---

<a id="item-26"></a>
## [OpenAI Files for Confidential IPO, May Stay Private](https://decrypt.co/370468/openai-confidential-ipo-filing-keeps-timing-open) ⭐️ 6.0/10

OpenAI has filed a confidential IPO paperwork, signaling a potential public offering, but the company may remain private to focus on other priorities. This move could reshape the AI industry's financial landscape, as OpenAI's valuation may exceed $1 trillion, influencing investor sentiment and competitor strategies. The confidential filing gives OpenAI flexibility to delay or cancel the IPO, and the company has not set a specific timeline for going public.

rss · Decrypt · Jun 8, 21:45

**Background**: A confidential IPO filing allows a company to submit its registration statement to the SEC without public disclosure, enabling it to test market conditions privately. OpenAI, the maker of ChatGPT, has been exploring going public amid rapid growth and high demand for AI technologies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reuters.com/business/openai-lays-groundwork-juggernaut-ipo-up-1-trillion-valuation-2025-10-29/">Exclusive: OpenAI lays groundwork for juggernaut IPO at up to $1 trillion ...</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#IPO`, `#AI industry`, `#business`

---

<a id="item-27"></a>
## [Morpho raises $175M for open credit network](https://www.theblock.co/post/404111/morpho-raises-175m-paradigm-a16z-crypto-ribbit-capital?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Morpho has raised $175 million in a funding round co-led by Paradigm, a16z crypto, and Ribbit Capital, valuing the project at $2 billion, to build an open blockchain-based credit network that connects DeFi, Wall Street, and global markets. This is one of the largest funding rounds in DeFi, signaling strong institutional interest in bridging traditional finance with blockchain-based lending. If successful, Morpho's open credit network could challenge established DeFi lending protocols like Aave and unlock new capital flows between crypto and traditional markets. Morpho is an open-source DeFi lending protocol on Ethereum and EVM-compatible blockchains. The $175 million round values the project at $2 billion, and the funds will be used to scale its blockchain-based credit infrastructure and advance institutional lending capabilities.

rss · The Block · Jun 9, 12:47

**Background**: DeFi lending protocols like Aave and Compound allow users to lend and borrow cryptocurrencies without intermediaries. Morpho aims to go further by creating an 'open credit network' that connects decentralized finance with traditional financial institutions, potentially enabling more efficient capital allocation across markets.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cryptopolitan.com/morpho-175m-backing-open-credit-network/">Morpho gets $175M backing in ‘open credit network’ challenge ...</a></li>
<li><a href="https://financefeeds.com/morpho-raises-175-million-to-build-open-credit-network/">Morpho Raises $175 Million to Build Open Credit Network</a></li>
<li><a href="https://blockonomi.com/morpho-secures-175m-investment-round-for-blockchain-credit-infrastructure/">Morpho Secures $175M Investment Round for Blockchain Credit ...</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#funding`, `#blockchain`, `#crypto`, `#credit network`

---