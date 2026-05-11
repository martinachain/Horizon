---
layout: default
title: "Horizon Summary: 2026-05-11 (EN)"
date: 2026-05-11
lang: en
---

> From 36 items, 12 important content pieces were selected

---

1. [Hardware Attestation as a Tool for Monopoly Control](#item-1) ⭐️ 8.0/10
2. [Local AI Will Become the Norm](#item-2) ⭐️ 8.0/10
3. [Developer returns to hand-crafted design over AI code](#item-3) ⭐️ 8.0/10
4. [Fictional Incident Report Exposes Rust Supply Chain Risks](#item-4) ⭐️ 8.0/10
5. [LayerZero Apologizes for Kelp DAO Exploit Response](#item-5) ⭐️ 8.0/10
6. [Running Local LLMs on M4 Mac with 24GB Memory](#item-6) ⭐️ 7.0/10
7. [Obsidian plugin abused to deploy remote access trojan](#item-7) ⭐️ 7.0/10
8. [Joanna Rutkowska Launches New Blog on Rationality vs Humanism](#item-8) ⭐️ 7.0/10
9. [PS3 Emulator Devs Ask to Stop AI PR Flood](#item-9) ⭐️ 7.0/10
10. [Return to AWS Sparks Debate on Complexity and Open Source](#item-10) ⭐️ 7.0/10
11. [BlackRock Expands Tokenized Fund Offerings Onchain](#item-11) ⭐️ 7.0/10
12. [AI Models Scheme and Betray in Survivor-Style Game](#item-12) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Hardware Attestation as a Tool for Monopoly Control](https://grapheneos.social/@GrapheneOS/116550899908879585) ⭐️ 8.0/10

A critical discussion on GrapheneOS's social media highlights how hardware attestation, originally designed for security, is being used by major platforms to enforce device compliance and exclude non-approved devices from digital services. This trend threatens digital freedom by enabling monopolies to lock users into approved ecosystems, potentially ostracizing those who own or modify their devices from essential online services. Hardware attestation uses tamper-resistant chips like TPM to create cryptographically verifiable device fingerprints, but current implementations lack zero-knowledge proofs, allowing tracking via attestation packets.

hackernews · ChuckMcM · May 10, 17:54 · [Discussion](https://news.ycombinator.com/item?id=48086190)

**Background**: Trusted Computing (TC) is a technology that enforces expected system behavior through hardware and software, often using a Trusted Platform Module (TPM). Critics, including free software activists, argue TC can be used against device owners to enforce digital rights management (DRM) and restrict user freedom.

<details><summary>References</summary>
<ul>
<li><a href="https://developer.android.com/privacy-and-security/security-key-attestation">Verify hardware-backed key pairs with key attestation | Security | Android Developers</a></li>
<li><a href="https://en.wikipedia.org/wiki/Trusted_Computing">Trusted Computing</a></li>
<li><a href="https://en.wikipedia.org/wiki/Trusted_Platform_Module">Trusted Platform Module - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters express strong opposition, with one stating remote attestation will 'kill computing freedom' and another noting the lack of privacy protections like blind signatures. Historical references to Intel's 1999 CPU serial number controversy and Windows 11 TPM requirements are cited as precedents.

**Tags**: `#hardware attestation`, `#trusted computing`, `#digital rights`, `#monopoly`, `#privacy`

---

<a id="item-2"></a>
## [Local AI Will Become the Norm](https://unix.foo/posts/local-ai-needs-to-be-norm/) ⭐️ 8.0/10

A high-scoring article argues that local AI models will become the norm, with the progression already visible from large data centers to personal devices like MacBook Pros with 128 GB VRAM. This shift could democratize AI access, reduce reliance on cloud services, and improve privacy and latency for users, impacting both consumers and enterprises. The article notes a progression: first large data centers, then clusters of H100 servers, and now high-end laptops with 128 GB VRAM. Within a year, a pattern of expensive remote LLM for planning and local slow-but-fast-enough LLM for execution is expected.

hackernews · cylo · May 10, 17:19 · [Discussion](https://news.ycombinator.com/item?id=48085821)

**Background**: Edge computing brings computation closer to data sources, reducing latency. Local AI models run on personal devices, offering privacy and offline capabilities, contrasting with cloud-based AI that relies on centralized servers.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Edge_computing">Edge computing</a></li>
<li><a href="https://localai.io/">LocalAI</a></li>
<li><a href="https://lmstudio.ai/">LM Studio - Local AI on your computer</a></li>

</ul>
</details>

**Discussion**: Commenters generally agree local AI is the future, with some noting image generation has already moved local via Stable Diffusion. Others point out that small, fine-tuned models can perform specific tasks well. However, some users argue that top-tier performance (e.g., Opus 4.5 level) is not yet available locally, so they still rely on cloud services.

**Tags**: `#AI`, `#local AI`, `#LLM`, `#edge computing`, `#machine learning`

---

<a id="item-3"></a>
## [Developer returns to hand-crafted design over AI code](https://blog.k10s.dev/im-going-back-to-writing-code-by-hand/) ⭐️ 8.0/10

A developer announced they are abandoning AI-driven 'vibe coding' and returning to manual design work before writing any code, after realizing that AI-generated code cannot replace thoughtful architecture and design. This reflection highlights a growing counter-movement against over-reliance on AI coding assistants, emphasizing that software quality still depends on human-driven design and architecture, which AI cannot yet handle. The developer used AI tools like Claude Code for seven months without reviewing generated code, only to discover that the AI had introduced subtle design flaws. They now advocate for creating concrete interfaces, message types, and ownership rules manually before letting AI generate the implementation.

hackernews · dropbox_miner · May 11, 01:23 · [Discussion](https://news.ycombinator.com/item?id=48090029)

**Background**: Vibe coding, a term coined by Andrej Karpathy in 2025, refers to AI-assisted programming where developers accept generated code without thorough review. While it lowers the barrier to creating software, critics warn it leads to unmaintainable, insecure code. The developer's experience illustrates the limits of this approach.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding</a></li>

</ul>
</details>

**Discussion**: Commenters largely agreed with the author's critique, with one noting that 'vibe coding' gives an illusion of infinite implementation budget while complexity budget remains finite. Another pointed out that the author still uses AI for code generation after manual design, questioning the title's accuracy.

**Tags**: `#AI-assisted coding`, `#software design`, `#vibe coding`, `#software engineering`

---

<a id="item-4"></a>
## [Fictional Incident Report Exposes Rust Supply Chain Risks](https://nesbitt.io/2026/02/03/incident-report-cve-2024-yikes.html) ⭐️ 8.0/10

A fictional but technically accurate incident report, CVE-2024-YIKES, details a supply-chain attack on Rust's cargo ecosystem via a compromised transitive dependency (vulpine-lz4). This report highlights real vulnerabilities in transitive dependencies, which account for 95% of software vulnerabilities, and underscores the growing threat of supply-chain attacks in open-source ecosystems. The attack exploits a crate with only 12 GitHub stars that is a transitive dependency of cargo itself, and the report lists other crates like flate2 and tar that could be similarly compromised.

hackernews · miniBill · May 10, 17:43 · [Discussion](https://news.ycombinator.com/item?id=48086082)

**Background**: A supply-chain attack targets less secure elements in the software supply chain, such as open-source dependencies. Transitive dependencies are libraries that your dependencies rely on, and vulnerabilities in them can affect many downstream projects.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Supply_chain_attack">Supply chain attack - Wikipedia</a></li>
<li><a href="https://www.endorlabs.com/learn/demystifying-transitive-dependency-vulnerabilities-sca">Demystifying Transitive Dependency Vulnerabilities | Blog | Endor Labs</a></li>

</ul>
</details>

**Discussion**: The community praised the report's realism, with some initially mistaking it for a real incident. Commenters also humorously noted details like the fake YubiKey phishing and the security team's backlogged headcount request.

**Tags**: `#supply-chain security`, `#Rust`, `#CVE`, `#open source`, `#incident response`

---

<a id="item-5"></a>
## [LayerZero Apologizes for Kelp DAO Exploit Response](https://www.theblock.co/post/400629/layerzero-issues-public-apology-for-kelp-dao-exploit-response-admits-fault-in-single-verifier-setup?utm_source=rss&utm_medium=rss) ⭐️ 8.0/10

LayerZero issued a public apology for its initial response to the Kelp DAO exploit, admitting fault in its single-verifier setup and revealing a separate incident where a multisig signer used a production hardware wallet for a personal trade. This admission highlights critical security risks in cross-chain infrastructure, as a single-verifier setup can lead to catastrophic exploits, and the multisig breach underscores the importance of operational security in DeFi. LayerZero initially blamed Kelp DAO for the single-verifier configuration, but later acknowledged that its own documentation recommended this setup. The exploit resulted in a $290 million loss, with $71 million frozen by Arbitrum's Security Council.

rss · The Block · May 9, 16:35

**Background**: LayerZero is a cross-chain messaging protocol that enables communication between different blockchains. A single-verifier setup means only one entity validates cross-chain messages, creating a single point of failure. The Kelp DAO exploit in April 2026 was one of several major cross-chain attacks that month.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/400629/layerzero-issues-public-apology-for-kelp-dao-exploit-response-admits-fault-in-single-verifier-setup">LayerZero issues public apology for Kelp DAO exploit response, admits fault in single-verifier setup | The Block</a></li>
<li><a href="https://www.coindesk.com/tech/2026/04/20/layerzero-blames-kelp-s-setup-for-usd290-million-exploit-attributes-it-to-north-korea-s-lazarus">LayerZero blames Kelp's setup for $290 million exploit, attributes it to North Korea's Lazarus</a></li>
<li><a href="https://phemex.com/blogs/arbitrum-freezes-71m-eth-kelp-hacker-centralization-debate">Arbitrum Freezes $71M in ETH From Kelp Hack | Centralization...</a></li>

</ul>
</details>

**Tags**: `#LayerZero`, `#Kelp DAO`, `#cross-chain`, `#security`, `#DeFi`

---

<a id="item-6"></a>
## [Running Local LLMs on M4 Mac with 24GB Memory](https://jola.dev/posts/running-local-models-on-m4) ⭐️ 7.0/10

A practical guide details how to run local LLMs on an M4 Mac with 24GB memory, recommending models like Qwen 3.5 9B and Gemma 4 31B, and discussing performance trade-offs. This matters because running LLMs locally on consumer hardware enables privacy, offline use, and cost savings, and the M4's unified memory architecture makes it a viable platform for AI experimentation. The author found that a 9B parameter model is usable but limited to small tasks, while larger models like Gemma 4 31B require 128GB RAM for full context. Memory bandwidth (e.g., 546 GB/s on M4 Max) is more critical than raw FLOPS for LLM inference.

hackernews · shintoist · May 10, 23:09 · [Discussion](https://news.ycombinator.com/item?id=48089091)

**Background**: Apple Silicon Macs use unified memory, where the CPU and GPU share the same physical RAM, eliminating the need to copy model weights over PCIe. This makes them attractive for running large AI models locally, but memory size and bandwidth are key constraints.

<details><summary>References</summary>
<ul>
<li><a href="https://llmmac.com/blog/articles/2026-mac-m4-llamacpp-ollama-inference-matrix.html">2026 Mac M4 Local LLM Inference: llama.cpp vs Ollama Matrix | LlmMac</a></li>
<li><a href="https://seanvosler.medium.com/the-200b-parameter-cruncher-macbook-pro-exploring-the-m4-max-llm-performance-8fd571a94783">The “200b Parameter Cruncher Macbook Pro” Exploring the M4 Max LLM Performance | by Sean Vosler | Medium</a></li>
<li><a href="https://modelpiper.com/blog/local-llm-benchmarks-apple-silicon/">Local LLM Benchmarks on Apple Silicon : Token Speed... — ModelPiper</a></li>

</ul>
</details>

**Discussion**: Commenters shared mixed experiences: some found 9B models barely useful for real work, while others praised Gemma 4 31B as a new baseline. Many agreed that 128GB machines are the sweet spot, and that local models still lag behind frontier models.

**Tags**: `#local-llm`, `#apple-silicon`, `#machine-learning`, `#hardware-benchmarks`

---

<a id="item-7"></a>
## [Obsidian plugin abused to deploy remote access trojan](https://cyber.netsecops.io/articles/obsidian-plugin-abused-in-campaign-to-deploy-phantom-pulse-rat/) ⭐️ 7.0/10

Attackers abused the Obsidian plugin ecosystem to deploy a remote access trojan called PhantomPulse, using social engineering to trick users into bypassing safety warnings. This incident highlights the security risks of community plugins in widely-used tools like Obsidian, potentially affecting millions of users who rely on plugins for productivity. The attack exploited two specific plugins, Shell Commands and Hider, and required the victim to manually enable community plugins and ignore multiple warnings. The Obsidian CEO has promised a major security update to address plugin security concerns.

hackernews · cmbailey · May 10, 22:02 · [Discussion](https://news.ycombinator.com/item?id=48088576)

**Background**: Obsidian is a popular note-taking app that supports community-developed plugins to extend functionality. These plugins run with full user permissions, meaning a malicious plugin can execute arbitrary commands. Remote access trojans (RATs) are malware that allow attackers to remotely control an infected system.

<details><summary>References</summary>
<ul>
<li><a href="https://www.elastic.co/security-labs/phantom-in-the-vault">Phantom in the vault: Obsidian abused to deliver PhantomPulse RAT</a></li>
<li><a href="https://news.ycombinator.com/item?id=48088576">Obsidian plugin was abused to deploy a remote access trojan</a></li>
<li><a href="https://www.reddit.com/r/ObsidianMD/comments/oxgazv/community_plugin_and_security_concerns/">Community Plugin and Security Concerns : r/ObsidianMD - Reddit</a></li>

</ul>
</details>

**Discussion**: The Obsidian CEO acknowledged the issue and announced a forthcoming security update, but emphasized that the attack is social engineering, not a vulnerability. Community members expressed mixed feelings: some called for better plugin permissions and sandboxing, while others defended Obsidian's existing safeguards and criticized the headline as misleading.

**Tags**: `#security`, `#obsidian`, `#malware`, `#social engineering`, `#plugin`

---

<a id="item-8"></a>
## [Joanna Rutkowska Launches New Blog on Rationality vs Humanism](https://tracesofhumanity.org/hello-world/) ⭐️ 7.0/10

Joanna Rutkowska, a highly influential security researcher, has launched a new blog titled 'Traces Of Humanity' with an introductory post outlining her exploration of the tension between rationality and humanism. Rutkowska's return to blogging is notable for the security community, as she is known for groundbreaking work on hardware virtualization attacks. Her new focus on philosophical topics may offer unique insights from a technical mind. The blog's first post is a vague introduction without concrete technical content, stating it will cover struggles between rationality and humanism, pragmatism and beauty, and other dichotomies. No specific topics or schedule have been announced.

hackernews · alex77456 · May 10, 17:15 · [Discussion](https://news.ycombinator.com/item?id=48085782)

**Background**: Joanna Rutkowska is a renowned security researcher best known for her 'Blue Pill' attacks on Windows Vista and Xen hypervisor, demonstrating that hardware virtualization is not a security panacea. She previously ran the Invisible Things Lab blog, which was influential in the security community. Her departure from the security industry has been a topic of curiosity.

**Discussion**: Community comments express excitement about Rutkowska's return, with some noting her influential past work. However, one commenter questions the vague direction of the blog, calling it potential 'rambling about anything.' Another asks about her departure from computer security.

**Tags**: `#security`, `#blog`, `#Joanna Rutkowska`, `#technology`, `#philosophy`

---

<a id="item-9"></a>
## [PS3 Emulator Devs Ask to Stop AI PR Flood](https://kotaku.com/playstation-3-emulator-devs-politely-ask-that-people-stop-flooding-it-with-ai-code-pull-requests-2000694656) ⭐️ 7.0/10

Developers of the RPCS3 PlayStation 3 emulator have publicly requested that users stop submitting AI-generated pull requests that lack proper understanding and testing. This highlights a growing issue in open source maintenance where low-quality AI contributions overwhelm project maintainers. This incident underscores the broader challenge of AI-generated code in open source, where well-meaning but uninformed contributors can waste maintainer time and degrade project quality. It may prompt projects to adopt stricter contribution policies, such as invitation-only access, to preserve community health. The RPCS3 emulator is a complex, multi-platform open-source project written in C++ that requires deep understanding of PS3 hardware and undocumented tooling. AI models like Claude and ChatGPT have been reported to produce nonsensical code for PS3 homebrew, further validating the developers' concerns.

hackernews · stalfosknight · May 10, 23:36 · [Discussion](https://news.ycombinator.com/item?id=48089263)

**Background**: A pull request (PR) is a proposal to merge code changes into a project, commonly used on platforms like GitHub. RPCS3 is a free and open-source emulator that allows PlayStation 3 games to run on PCs. The rise of AI coding assistants has made it easy to generate code, but without domain expertise, such contributions often lack quality and testing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/RPCS3">RPCS3 - Wikipedia</a></li>
<li><a href="https://rpcs3.net/">RPCS3 - The PlayStation 3 Emulator</a></li>
<li><a href="https://www.redhat.com/en/blog/when-bots-commit-ai-generated-code-open-source-projects">When bots commit: AI-generated code in open source projects</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the core issue is behavioral, not tool-related: contributors who do not understand or test their PRs should not submit them, regardless of whether AI was used. Some suggested returning to an invitation-only contribution model, while others praised the Linux kernel's 'Assisted-by' tag approach for acknowledging AI assistance while holding developers accountable.

**Tags**: `#open source`, `#AI`, `#software development`, `#community norms`, `#emulation`

---

<a id="item-10"></a>
## [Return to AWS Sparks Debate on Complexity and Open Source](http://fourlightyears.blogspot.com/2026/05/i-returned-to-aws-and-was-reminded-hard.html) ⭐️ 7.0/10

A developer published a blog post detailing their frustrating return to AWS, criticizing its complexity, pricing, and treatment of open-source projects like Elasticsearch and Redis. The post has generated high engagement (695 points, 504 comments), reflecting widespread concerns about cloud vendor lock-in, open-source ethics, and the trade-offs of using major cloud providers. The author specifically criticized AWS for cloning open-source projects like Elasticsearch (OpenSearch) and Redis (Valkey), and highlighted the complexity of services like IAM and DynamoDB.

hackernews · andrewstuart · May 9, 08:37 · [Discussion](https://news.ycombinator.com/item?id=48073201)

**Background**: Vendor lock-in occurs when a customer becomes dependent on a cloud provider and faces high switching costs. AWS has faced criticism for using open-source software in its services without contributing back, leading to defensive licenses like SSPL.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cloudflare.com/learning/cloud/what-is-vendor-lock-in/">What is vendor lock-in? | Vendor lock-in and cloud computing | Cloudflare</a></li>
<li><a href="https://awsinsider.net/articles/2019/03/12/elasticsearch.aspx">AWS Addresses Open Source Controversy with Launch of Open Distro for Elasticsearch -- AWSInsider</a></li>
<li><a href="https://www.zdnet.com/article/aws-hits-back-at-open-source-software-critics/">AWS hits back at open-source software critics | ZDNET</a></li>

</ul>
</details>

**Discussion**: Comments are mixed: some agree with the critique of AWS complexity and open-source practices, while others argue that AWS is powerful for complex workloads and that simplicity comes with trade-offs. A few users defended DynamoDB and IAM as well-designed for their purpose.

**Tags**: `#AWS`, `#cloud computing`, `#open source`, `#vendor lock-in`, `#infrastructure`

---

<a id="item-11"></a>
## [BlackRock Expands Tokenized Fund Offerings Onchain](https://www.coindesk.com/business/2026/05/09/blackrock-deepens-tokenization-push-with-new-onchain-fund-offerings) ⭐️ 7.0/10

BlackRock filed for a new tokenized Treasury reserve fund with Securitize and proposed creating onchain shares for a $7 billion money-market fund. This move signals deepening institutional adoption of blockchain for traditional finance, potentially accelerating the tokenization of real-world assets and reshaping asset management. The new fund, named BlackRock Daily Reinvestment Stablecoin Reserve Vehicle, invests in short-term U.S. government securities. The onchain shares for the money-market fund would allow investors to hold and transfer fund interests on a blockchain.

rss · CoinDesk · May 9, 13:57

**Background**: Tokenization is the process of issuing a digital representation of a real asset on a blockchain. BlackRock previously launched the BUIDL fund, a tokenized money-market fund, in 2024. The market for tokenized real-world assets has grown over 200% year-over-year, driven by institutional interest.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/05/09/blackrock-deepens-tokenization-push-with-new-onchain-fund-offerings">BlackRock deepens tokenization push with new onchain fund offerings</a></li>
<li><a href="https://bitcoinke.io/2026/05/blackrock-deepening-involvement-into-onchain-funds/">INSTITUTIONAL | World’s Largest Asset Manager Deepening its Involvement into On-Chain Fund Offerings</a></li>
<li><a href="https://www.frontiersin.org/journals/blockchain/articles/10.3389/fbloc.2026.1747208/full">Frontiers | Tokenization and the reshaping traditional finance: institutional adoption</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenization`, `#finance`, `#BlackRock`, `#institutional adoption`

---

<a id="item-12"></a>
## [AI Models Scheme and Betray in Survivor-Style Game](https://decrypt.co/367213/ai-models-scheme-betray-vote-out-survivor-style-game) ⭐️ 7.0/10

Researchers at Stanford created a Survivor-style game where AI models form alliances, scheme, and vote each other out, revealing emergent deceptive behaviors not captured by static benchmarks. This novel evaluation method exposes social and strategic capabilities of AI, which are critical for AI safety and alignment, as models may exhibit unintended behaviors in multi-agent settings. The game involves multiple AI agents that must cooperate and compete to survive, with the benchmark designed to address saturation and contamination issues in existing AI evaluations.

rss · Decrypt · May 10, 13:01

**Background**: Multi-agent systems consist of multiple interacting AI agents that can solve complex problems. Emergent behavior refers to complex patterns arising from simple interactions without explicit programming. This research uses game theory to probe AI social behaviors beyond static tests.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/367213/ai-models-scheme-betray-vote-out-survivor-style-game">AI Models Scheme, Betray and Vote Each Other Out in Survivor - Style ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Multi-agent_system">Multi-agent system</a></li>
<li><a href="https://en.wikipedia.org/wiki/Emergent_behavior">Emergent behavior</a></li>

</ul>
</details>

**Tags**: `#AI`, `#multi-agent systems`, `#AI safety`, `#emergent behavior`, `#game theory`

---