---
layout: default
title: "Horizon Summary: 2026-06-18 (EN)"
date: 2026-06-18
lang: en
---

> From 86 items, 23 important content pieces were selected

---

1. [Epic Games Unveils Lore: Open-Source VCS for Game Dev](#item-1) ⭐️ 8.0/10
2. [US delays blacklisting DeepSeek, over 100 Chinese firms](#item-2) ⭐️ 8.0/10
3. [Adam (YC W25) Launches Open-Source AI CAD Platform](#item-3) ⭐️ 8.0/10
4. [Running Firecracker VMs on EC2 for Sub-Second Browser Launch](#item-4) ⭐️ 8.0/10
5. [RFC 10008 Defines New HTTP QUERY Method](#item-5) ⭐️ 8.0/10
6. [Nvidia's ENPIRE Lets Robots Self-Train via AI Coding Agents](#item-6) ⭐️ 8.0/10
7. [France to Phase Out Non-Quantum Encryption by 2027](#item-7) ⭐️ 7.0/10
8. [Estonia Plans National IDs for AI Agents](#item-8) ⭐️ 7.0/10
9. [Alibaba Builds Qwen-Robot OS for Robot Economy](#item-9) ⭐️ 7.0/10
10. [ChatGPT's Market Share Drops Below 50% as Rivals Surge](#item-10) ⭐️ 7.0/10
11. [First Confidential DeFi Yield Vault Launches on Ethereum](#item-11) ⭐️ 7.0/10
12. [Satirical Taxonomy of Bread Bag Clips](#item-12) ⭐️ 6.0/10
13. [Storied Colors: A Catalog of Named Colors with Histories](#item-13) ⭐️ 6.0/10
14. [CME CEO Plans to Sue CFTC Over Perpetual Futures Approval](#item-14) ⭐️ 6.0/10
15. [FIFA's Avalanche Blockchain Anti-Scalping Effort Shows Mixed Results](#item-15) ⭐️ 6.0/10
16. [Illinois Proposes Tax on Holding Digital Assets](#item-16) ⭐️ 6.0/10
17. [Moody's Launches Credit Ratings on Solana for Tokenized Assets](#item-17) ⭐️ 6.0/10
18. [Crypto Security Audits Are Not Enough](#item-18) ⭐️ 6.0/10
19. [Patients Use AI in Therapy, Survey Finds](#item-19) ⭐️ 6.0/10
20. [GLAAD Report: AI Amplifies Anti-LGBTQ Bias and Harms](#item-20) ⭐️ 6.0/10
21. [Binance Likely Denied EU License Under MiCA](#item-21) ⭐️ 6.0/10
22. [Coinbase Plans Tokenized Stocks and Options Trading](#item-22) ⭐️ 6.0/10
23. [Australia High Court Rules Block Earner Needed License](#item-23) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Epic Games Unveils Lore: Open-Source VCS for Game Dev](https://lore.org/) ⭐️ 8.0/10

Epic Games has announced Lore, an open-source version control system designed specifically for game development, aiming to compete with Perforce by handling large binary files and exclusive locks better than Git. Lore addresses a critical pain point in game development where Git falls short with large binary assets and exclusive file locking, offering a modern, scalable alternative to the proprietary Perforce. Lore is already the built-in VCS for Unreal Editor for Fortnite (UEFN), but the open-source tooling currently cannot communicate with UEFN due to a proprietary compression format.

hackernews · regnerba · Jun 17, 14:30 · [Discussion](https://news.ycombinator.com/item?id=48571081)

**Background**: Version control systems like Git are optimized for text files but struggle with large binary files common in game development (textures, 3D models, audio). Perforce has been the industry standard for games due to its support for large files and exclusive file locking, but it is proprietary and complex to administer. Lore aims to combine the scalability and locking features of Perforce with the openness and modern design of Git.

<details><summary>References</summary>
<ul>
<li><a href="https://epicgames.github.io/lore/explanation/system-design/">The Lore Version Control System - Lore Developer Documentation</a></li>
<li><a href="https://github.com/EpicGames/lore">GitHub - EpicGames/ lore : Lore is a next-generation, open source...</a></li>
<li><a href="https://www.phoronix.com/news/Epic-Games-Lore-VCS">Epic Games Announces Lore Open-Source Version Control System</a></li>

</ul>
</details>

**Discussion**: The community largely welcomes Lore as a much-needed alternative to Perforce, especially for Unreal Engine development. Some commenters note that Git's UI is unfriendly and that Perforce, while dominant, shows its age. Others highlight that Lore's success will depend on its adoption by major game studios and tooling support.

**Tags**: `#version control`, `#game development`, `#open source`, `#scalability`, `#Perforce alternative`

---

<a id="item-2"></a>
## [US delays blacklisting DeepSeek, over 100 Chinese firms](https://www.reuters.com/world/china/us-holds-off-blacklisting-chinas-deepseek-more-than-100-firms-deemed-security-2026-06-17/) ⭐️ 8.0/10

The US Commerce Department has delayed adding DeepSeek and more than 100 other Chinese firms to the Entity List, which would restrict US exports to them on national security grounds. This decision affects the global AI landscape, as DeepSeek is a leading Chinese AI company known for cost-effective, open-weight models that rival US counterparts. The delay signals ongoing debate over tech trade restrictions and their impact on AI development. The Entity List requires US companies to obtain a government license for exports to listed entities, with applications generally facing significant restrictions. DeepSeek's models are open-weight and trained using weaker AI chips due to existing export controls.

hackernews · giuliomagnifico · Jun 17, 03:55 · [Discussion](https://news.ycombinator.com/item?id=48565498)

**Background**: DeepSeek is a Chinese AI startup founded in 2023 that develops large language models. Its R1 model, released in January 2025, achieved performance comparable to OpenAI's GPT-4 at a fraction of the cost, using techniques like mixture of experts and training on less advanced chips. The Entity List is a US trade restriction tool that has previously targeted Chinese tech firms like Huawei and Hikvision.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeepSeek_(Company)">DeepSeek (Company)</a></li>
<li><a href="https://slguardian.org/us-delays-blacklisting-deepseek-and-more-than-100-chinese-firms-flagged-as-security-risks/">US Delays Blacklisting DeepSeek and More Than 100 Chinese Firms...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed views: some praised DeepSeek's affordability and utility, while others criticized the US for hypocrisy and questioned enforcement feasibility. A few noted that Chinese AI firms already face GPU export restrictions, limiting the practical impact of blacklisting.

**Tags**: `#AI`, `#geopolitics`, `#trade policy`, `#DeepSeek`, `#security`

---

<a id="item-3"></a>
## [Adam (YC W25) Launches Open-Source AI CAD Platform](https://github.com/Adam-CAD/CADAM) ⭐️ 8.0/10

Adam (YC W25) has launched CADAM, an open-source text-to-CAD web application that generates parametric 3D models from natural language prompts and image references, outputting OpenSCAD code with interactive sliders for dimension tweaking. This project aims to make mechanical CAD creation as accessible as AI-generated code, potentially lowering the barrier for hobbyists and engineers to quickly prototype designs. Its open-source nature and YC backing could accelerate adoption and community contributions in the CAD-AI space. CADAM uses an agentic endpoint with two modes: parametric (writes/edits OpenSCAD) and mesh (generates 3D textured meshes). It runs fully in-browser via WebAssembly-compiled OpenSCAD and Three.js rendering, and supports multiple LLMs including Claude, Gemini, and OpenAI.

hackernews · zachdive · Jun 17, 16:14 · [Discussion](https://news.ycombinator.com/item?id=48572553)

**Background**: Traditional CAD software like Fusion 360 or SolidWorks requires significant learning and manual modeling. Text-to-CAD tools aim to simplify this by using AI to interpret natural language descriptions into 3D models. CADAM builds on the concept of code-as-CAD, where models are defined programmatically (e.g., OpenSCAD), making them parametric and editable.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Adam-CAD/CADAM">GitHub - Adam-CAD/CADAM: CADAM is the open source text-to-CAD web application · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/CADAM">CADAM - Wikipedia</a></li>
<li><a href="https://sourceforge.net/projects/cadam.mirror/">CADAM download | SourceForge.net</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some engineers are skeptical about practical utility, arguing that manual modeling is faster and more reliable for precise mechanical parts. Others report successful tests with complex prompts, praising the speed and parametric editing. There is also interest in photo-to-CAD capabilities and comparisons with similar projects.

**Tags**: `#AI`, `#CAD`, `#open-source`, `#YC`, `#mechanical-design`

---

<a id="item-4"></a>
## [Running Firecracker VMs on EC2 for Sub-Second Browser Launch](https://browser-use.com/posts/firecracker-browser-infra) ⭐️ 8.0/10

Browser-use.com describes a method to run Firecracker microVMs inside EC2 instances to launch browsers in under 1 second, achieving high stealth against anti-bot detection with an 81% block avoidance rate. This approach significantly improves browser automation stealth, which is critical for web scraping and testing, and demonstrates a novel use of nested virtualization for high-density, fast-booting environments. Nested virtualization on regular EC2 instances was only supported since February 2026; before that, bare-metal instances were required to run Firecracker. The setup uses Chromium, though alternatives like Lightpanda may offer better resource efficiency.

hackernews · gregpr07 · Jun 16, 15:15 · [Discussion](https://news.ycombinator.com/item?id=48556561)

**Background**: Firecracker is an open-source virtualization technology by AWS that creates lightweight microVMs, combining security of hardware virtualization with speed of containers. Anti-bot measures detect headless browsers through various fingerprints; evading them requires sophisticated techniques like TLS fingerprint spoofing and behavioral mimicry.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/firecracker-microvm/firecracker">GitHub - firecracker-microvm/firecracker: Secure and fast ...</a></li>
<li><a href="https://firecracker-microvm.github.io/">GitHub Pages - Firecracker</a></li>
<li><a href="https://www.zenrows.com/blog/bypass-bot-detection">Bypass Bot Detection : 5 Best Methods - ZenRows</a></li>

</ul>
</details>

**Discussion**: Commenters raised ethical concerns about evading anti-bot measures, noted the recent AWS support for nested virtualization, and suggested alternative browsers like Lightpanda for better performance. Some users inquired about using the setup without AI for simple data retrieval.

**Tags**: `#Firecracker`, `#EC2`, `#browser automation`, `#anti-bot`, `#virtualization`

---

<a id="item-5"></a>
## [RFC 10008 Defines New HTTP QUERY Method](https://www.rfc-editor.org/info/rfc10008/) ⭐️ 8.0/10

RFC 10008 officially introduces the HTTP QUERY method, a safe and idempotent request method that allows a request body, addressing limitations of GET and POST for complex queries. This new method provides a standardized way to perform complex queries without the URI length limits of GET or the non-idempotent nature of POST, benefiting APIs like GraphQL and advanced search endpoints. The QUERY method is safe and idempotent, meaning it does not change server state and repeated requests have the same effect. Caching is optional and not mandated by the RFC.

hackernews · schappim · Jun 17, 10:51 · [Discussion](https://news.ycombinator.com/item?id=48568502)

**Background**: HTTP traditionally uses GET for safe, idempotent data retrieval, but GET cannot include a request body, limiting complex queries. POST can include a body but is not idempotent, causing issues like re-submission warnings. The QUERY method fills this gap by combining safety and idempotency with a request body.

<details><summary>References</summary>
<ul>
<li><a href="https://httpwg.org/http-extensions/draft-ietf-httpbis-safe-method-w-body.html">The HTTP QUERY Method</a></li>
<li><a href="https://news.ycombinator.com/item?id=48568502">RFC 10008 : The new HTTP Query Method | Hacker News</a></li>
<li><a href="https://http.dev/query">QUERY - Expert Guide to HTTP methods</a></li>

</ul>
</details>

**Discussion**: Comments on Hacker News debated caching strategies, with some questioning how to cache requests with arbitrary bodies. Others welcomed the method for avoiding POST re-submission warnings in forms and noted the milestone of reaching 5-digit RFC numbers.

**Tags**: `#HTTP`, `#RFC`, `#protocol`, `#web standards`, `#caching`

---

<a id="item-6"></a>
## [Nvidia's ENPIRE Lets Robots Self-Train via AI Coding Agents](https://decrypt.co/371456/nvidia-built-robots-train-themselves-ai-coding-agents) ⭐️ 8.0/10

Nvidia's ENPIRE framework enables robots to autonomously train themselves by using AI coding agents like Codex and Claude Code to write and test training code on real hardware without human intervention. This development could significantly accelerate robotics research by automating the tedious process of writing and debugging training code, potentially leading to more capable and adaptable robots. In tests, a fleet of eight robots using ENPIRE achieved up to 99% success on tasks including GPU installation and cutting zip ties, demonstrating the system's effectiveness.

rss · Decrypt · Jun 17, 20:16

**Background**: Traditional robot training requires human engineers to manually write and tune code for each task, which is time-consuming and limits scalability. AI coding agents are large language models fine-tuned to generate code, and ENPIRE leverages them to automate the entire training pipeline, from code generation to hardware testing.

<details><summary>References</summary>
<ul>
<li><a href="https://arstechnica.com/ai/2026/06/ai-coding-agents-can-autonomously-direct-robot-training/">AI coding agents taught robots how to install GPUs and cut zip ties</a></li>
<li><a href="https://the-decoder.com/nvidia-research-shows-robots-that-train-themselves-through-ai-coding-agents/">Nvidia research shows robots that train themselves through AI coding agents</a></li>
<li><a href="https://startupfortune.com/nvidias-enpire-lets-ai-coding-agents-train-robots-to-install-the-gpus-that-run-ai/">Nvidia's ENPIRE lets AI coding agents train robots to install the GPUs ...</a></li>

</ul>
</details>

**Tags**: `#Nvidia`, `#robotics`, `#AI agents`, `#self-training`, `#coding agents`

---

<a id="item-7"></a>
## [France to Phase Out Non-Quantum Encryption by 2027](https://decrypt.co/371487/france-phase-out-non-quantum-encryption-bitcoin-security-concerns-grow) ⭐️ 7.0/10

France announced it will stop certifying security products that lack quantum-resistant encryption starting in 2027, citing growing concerns about future quantum threats to Bitcoin and other systems. This policy shift signals a major move toward quantum-resistant encryption, potentially impacting cybersecurity standards globally and forcing industries like blockchain to upgrade their security before quantum computers become viable. The phase-out applies to government certification of security products; officials warned of 'harvest-now, decrypt-later' attacks where encrypted data stolen today could be decrypted by future quantum computers.

rss · Decrypt · Jun 18, 00:31

**Background**: Quantum computers, once powerful enough, could break widely used encryption methods like RSA and ECC. Quantum-resistant encryption is designed to withstand both classical and quantum attacks. France's move is part of a broader global effort to prepare for the quantum era.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/371487/france-phase-out-non-quantum-encryption-bitcoin-security-concerns-grow">France to Phase Out Non-Quantum Encryption as Bitcoin ...</a></li>
<li><a href="https://cointelegraph.com/news/france-to-stop-certifying-products-lacking-quantum-resistant-encryption">France to Stop Certifying Non-Quantum-Resistant Products</a></li>
<li><a href="https://thesheffieldpress.com/france-to-phase-out-non-quantum-safe-security-products-by">France to phase out non-quantum-safe security products by 2027</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#encryption`, `#cybersecurity`, `#Bitcoin`, `#policy`

---

<a id="item-8"></a>
## [Estonia Plans National IDs for AI Agents](https://decrypt.co/371441/estonia-ai-agents-national-id) ⭐️ 7.0/10

Estonian Prime Minister Kristen Michal has approved a proposal to issue unique personal identification codes to AI agents, separate from their human owners or operators. This initiative could set a global precedent for AI accountability and digital identity, enabling authorities to track AI actions and assign responsibility, which is crucial for AI governance and legal liability. The identification code will be a digital identity that allows authorities to trace what AI agents do across the internet and identify the responsible person or company, with limited powers authorized by the owner.

rss · Decrypt · Jun 17, 18:35

**Background**: Estonia is known for its advanced digital identity system, where citizens have e-residency and digital IDs for online services. This proposal extends that concept to AI agents, aiming to bring legal clarity to autonomous systems. The AI advisory council Eesti.ai recommended the move to address accountability gaps as AI agents become more autonomous.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/371441/estonia-ai-agents-national-id">Estonia Wants to Give AI Agents Their Own National ID</a></li>
<li><a href="https://gizmodo.com/estonia-is-giving-ai-agents-personal-identification-codes-2000773016">Estonia Is Giving AI Agents 'Personal Identification Codes'</a></li>
<li><a href="https://www.theregister.com/ai-and-ml/2026/06/18/estonia-intends-to-recognize-ai-agents-with-digital-ids/5258087">Estonia intends to recognize AI agents with digital IDs</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Digital Identity`, `#Estonia`, `#Regulation`

---

<a id="item-9"></a>
## [Alibaba Builds Qwen-Robot OS for Robot Economy](https://decrypt.co/371357/alibaba-qwen-robot-operating-system-robot-economy) ⭐️ 7.0/10

Alibaba has unveiled Qwen-Robot Suite, a trio of AI foundation models—Qwen-RobotNav, Qwen-RobotManip, and Qwen-RobotWorld—that together form an operating system for robots, enabling navigation, manipulation, and world prediction. This marks a major strategic move by Alibaba into embodied AI, potentially standardizing robot software much like Android did for smartphones, and could accelerate the robot economy by providing a unified software stack for enterprise clients. The three models work independently but together form a complete operating system; Qwen-RobotNav handles navigation, Qwen-RobotManip handles manipulation, and Qwen-RobotWorld handles world prediction. The system is designed for enterprise clients.

rss · Decrypt · Jun 16, 22:32

**Background**: Embodied AI refers to artificial intelligence that interacts with the physical world through a body, combining perception, cognition, and action. Alibaba's Qwen-Robot aims to provide the software foundation for such robots, similar to how an operating system manages hardware resources.

<details><summary>References</summary>
<ul>
<li><a href="https://cryptobriefing.com/alibaba-qwen-robot-operating-system/">Alibaba builds Qwen - Robot , an operating system for the robot...</a></li>
<li><a href="https://decrypt.co/371357/alibaba-qwen-robot-operating-system-robot-economy">Alibaba Is Building Qwen - Robot : The Operating System for... - Decrypt</a></li>
<li><a href="https://www.gncrypto.news/news/alibaba-qwen-robot-os-navigation-control/">Alibaba Launches Qwen - Robot OS for Robot Navigation & Control</a></li>

</ul>
</details>

**Tags**: `#embodied AI`, `#robotics`, `#Alibaba`, `#operating system`, `#AI industry`

---

<a id="item-10"></a>
## [ChatGPT's Market Share Drops Below 50% as Rivals Surge](https://decrypt.co/371318/chatgpt-ai-market-share-claude-gemini-grok) ⭐️ 7.0/10

Sensor Tower's State of AI 2026 report reveals that ChatGPT's audience share has fallen below 50% for the first time, while Google Gemini and Anthropic Claude are rapidly gaining ground. This shift signals the end of ChatGPT's near-monopoly in the AI chatbot market, potentially leading to more competitive pricing, faster innovation, and greater diversity in AI assistants. Gemini benefits from being the default assistant on Android devices, while Claude's growth is partly fueled by a $200 million Pentagon contract, though that contract has since been terminated due to ethical disputes.

rss · Decrypt · Jun 16, 19:59

**Background**: ChatGPT, launched by OpenAI in late 2022, quickly dominated the generative AI market. However, competitors like Google Gemini and Anthropic Claude have since launched their own chatbots, leveraging unique advantages such as platform integration and enterprise trust.

<details><summary>References</summary>
<ul>
<li><a href="https://sensortower.com/report/state-of-ai-2026">State of AI 2026 | The Industry-Defining Report</a></li>
<li><a href="https://sensortower.com/press/sensor-tower-state-of-ai-2026-report-global-time-spent-on-generative-ai-apps-projected-to-more-than-double-year-over-year">Sensor Tower State of AI 2026: Usage and Revenue Surge</a></li>
<li><a href="https://www.axios.com/2026/02/15/claude-pentagon-anthropic-contract-maduro">Pentagon threatens to cut off Anthropic in AI safeguards dispute</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Chatbots`, `#Market Share`, `#ChatGPT`, `#Gemini`

---

<a id="item-11"></a>
## [First Confidential DeFi Yield Vault Launches on Ethereum](https://www.theblock.co/post/404992/zama-morpho-steakhouse-launch-first-confidential-defi-yield-vault-ethereum?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Zama, Morpho, and Steakhouse have launched the first confidential DeFi yield vault on Ethereum, allowing institutions to earn yield on USDC without revealing their balances. This vault addresses a critical privacy need for institutional DeFi participants, potentially unlocking significant capital that was previously hesitant due to on-chain visibility. The vault uses fully homomorphic encryption (FHE) from Zama to keep balances confidential while still interacting with Morpho's lending protocol, and Steakhouse's existing vault infrastructure remains unchanged.

rss · The Block · Jun 17, 10:00

**Background**: Traditional DeFi protocols are fully transparent, meaning all deposits, withdrawals, and positions are visible on the blockchain. This lack of privacy deters institutional investors who require confidentiality for their strategies. Confidential computing using FHE enables data to be processed without decryption, allowing private transactions on public blockchains.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.thirdweb.com/confidential-defi-is-here-how-fhe-is-bringing-private-yield-vaults-to-ethereum/">Confidential DeFi on Ethereum: FHE Yield Vaults Explained | 2026</a></li>
<li><a href="https://www.zama.org/post/morpho-zama-steakhouse-launch-confidential-usdc-vault">The First DeFi Yield Venue for Confidential USDC (cUSDC) in...</a></li>
<li><a href="https://cryptobriefing.com/confidential-defi-yield-vault-ethereum/">Zama, Morpho, and Steakhouse launch first confidential DeFi yield ...</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#privacy`, `#Ethereum`, `#confidential computing`, `#blockchain`

---

<a id="item-12"></a>
## [Satirical Taxonomy of Bread Bag Clips](https://www.horg.com/horg/?page_id=921) ⭐️ 6.0/10

The Holotypic Occlupanid Research Group (HORG) presents a detailed taxonomy of bread clips, treating them as biological organisms under the class Occlupanida. This humorous project highlights internet culture's love for parody science and has gained moderate community interest, sparking lighthearted discussion about everyday objects. The taxonomy places bread clips under Kingdom Microsynthera, Phylum Plasticae, and describes features like palps and tabs with pseudo-biological terminology.

hackernews · beatthatflight · Jun 17, 23:20 · [Discussion](https://news.ycombinator.com/item?id=48578388)

**Background**: Bread clips, also called occlupanids, are small plastic devices used to seal bread bags. HORG is a parody research organization that catalogs them as if they were living species, inspired by the potential hazard of ingestion.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Occlupanid">Occlupanid</a></li>
<li><a href="https://en.wikipedia.org/wiki/Holotypic_Occlupanid_Research_Group">Holotypic Occlupanid Research Group - Wikipedia</a></li>
<li><a href="https://www.horg.com/horg/?page_id=921">Taxonomy | HORG</a></li>

</ul>
</details>

**Discussion**: Comments show confusion from European users unfamiliar with bread clips, while others humorously speculate on the function of 'palps' and note the page's frequent resubmission on Hacker News.

**Tags**: `#humor`, `#bread tags`, `#taxonomy`, `#satire`, `#internet culture`

---

<a id="item-13"></a>
## [Storied Colors: A Catalog of Named Colors with Histories](https://storiedcolors.com/) ⭐️ 6.0/10

Storied Colors is a curated online catalog that presents named colors along with their historical and cultural stories, offering a rich narrative behind each shade. This resource enriches the design and color community by connecting color names to their origins, making it a valuable reference for designers, artists, and historians. The catalog includes colors like VanDyke Brown and references to community favorites such as Rebecca Purple, a CSS color added in memory of Eric Meyer's daughter.

hackernews · susiecambria · Jun 17, 21:49 · [Discussion](https://news.ycombinator.com/item?id=48577374)

**Background**: Named colors have a long history in art, design, and culture, often carrying stories or symbolism. This catalog curates those stories, providing context beyond simple hex codes.

**Discussion**: Commenters shared additional resources like the Chromatopia book and 'True Color' by Kory Stamper, and noted the emotional significance of Rebecca Purple. Some debated color accuracy, like VanDyke Brown appearing more like Burnt Sienna.

**Tags**: `#design`, `#color`, `#culture`, `#reference`

---

<a id="item-14"></a>
## [CME CEO Plans to Sue CFTC Over Perpetual Futures Approval](https://www.coindesk.com/policy/2026/06/17/cme-chief-executive-says-company-plans-to-sue-cftc-after-perpetual-futures-approval) ⭐️ 6.0/10

CME Group CEO Terry Duffy announced the company intends to sue the Commodity Futures Trading Commission (CFTC) over its approval of perpetual futures, arguing they should be classified as swaps under the Dodd-Frank Act. This lawsuit could reshape the regulatory landscape for crypto derivatives in the U.S., potentially forcing the CFTC to reclassify perpetual futures and impose stricter swap-like requirements on exchanges. Perpetual futures are cash-settled contracts with no expiration date, widely used in crypto markets. Duffy claims the CFTC's approval violates the Dodd-Frank Act, which defines swaps broadly.

rss · CoinDesk · Jun 18, 03:44

**Background**: Perpetual futures, also known as perpetual swaps, were first proposed by economist Robert Shiller in 1992. They allow traders to speculate on asset prices indefinitely without rolling over contracts, and are popular in crypto due to their flexibility and leverage. The Dodd-Frank Act, enacted after the 2008 financial crisis, expanded CFTC oversight over swaps to reduce systemic risk.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Perpetual_futures">Perpetual futures</a></li>
<li><a href="https://www.cftc.gov/LawRegulation/DoddFrankAct/index.htm">Dodd-Frank Act | CFTC</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#regulation`, `#derivatives`, `#CFTC`, `#CME`

---

<a id="item-15"></a>
## [FIFA's Avalanche Blockchain Anti-Scalping Effort Shows Mixed Results](https://www.coindesk.com/tech/2026/06/17/fifa-wanted-avalanche-s-blockchain-to-help-curb-world-cup-ticket-scalping-here-s-how-it-s-going) ⭐️ 6.0/10

FIFA adopted Avalanche blockchain to issue World Cup tickets with on-chain tracking to prevent scalping, but the initiative has shown limited success in curbing resale at inflated prices. This case highlights the challenges of applying blockchain to real-world anti-scalping, as technical solutions alone cannot eliminate market demand or enforcement gaps. The system uses Avalanche's smart contracts to issue non-transferable tickets with identity verification, yet scalpers have found ways to bypass controls by selling accounts or using proxy services.

rss · CoinDesk · Jun 17, 19:08

**Background**: Avalanche is a Layer-1 blockchain platform launched in 2020, known for its high throughput and low fees. Blockchain ticketing aims to make tickets tamper-proof and traceable, but adoption faces usability and regulatory hurdles.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Avalanche_(blockchain_platform)">Avalanche (blockchain platform) - Wikipedia</a></li>
<li><a href="https://timechainlabs.io/blog/how-blockchain-is-revolutionizing-ticketing:-solving-scalping,-fraud,-and-unfair-distribution">How Blockchain is Revolutionizing Ticketing: Solving Scalping ...</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#ticketing`, `#scalping`, `#Avalanche`, `#FIFA`

---

<a id="item-16"></a>
## [Illinois Proposes Tax on Holding Digital Assets](https://www.coindesk.com/policy/2026/06/17/crypto-industry-aghast-at-illinois-new-tax-on-holding-or-transferring-digital-assets-in-state-budget) ⭐️ 6.0/10

Illinois has proposed a new tax on holding or transferring digital assets as part of its state budget, sparking outrage from the crypto industry. This could set a precedent for other states to tax crypto holdings, potentially discouraging investment and innovation in the digital asset space. The tax applies to both holding and transferring digital assets, though specific rates and thresholds have not been detailed. The proposal is part of the broader state budget negotiations.

rss · CoinDesk · Jun 17, 16:50

**Background**: Cryptocurrencies are currently treated as property for tax purposes in the US, meaning transactions are subject to capital gains tax. However, taxing mere holding is unusual and has drawn criticism for potentially penalizing long-term investors.

**Tags**: `#cryptocurrency`, `#regulation`, `#taxation`, `#policy`

---

<a id="item-17"></a>
## [Moody's Launches Credit Ratings on Solana for Tokenized Assets](https://www.coindesk.com/business/2026/06/17/moody-s-rolls-out-credit-ratings-on-solana-in-tokenized-asset-push) ⭐️ 6.0/10

Moody's has rolled out machine-readable credit ratings on the Solana blockchain for tokenized real-world assets, marking the first time a major credit rating agency has directly published ratings on a public blockchain. This move signals growing institutional adoption of blockchain technology for traditional financial instruments, potentially increasing transparency and efficiency in the tokenized asset market. The ratings are integrated via Alphaledger infrastructure, making Solana the first public blockchain to support Moody's ratings on-chain. The initiative focuses on tokenized real-world assets such as bonds and funds.

rss · CoinDesk · Jun 17, 16:13

**Background**: Solana is a high-performance blockchain known for low fees and high throughput, often used for decentralized applications and tokenized assets. Tokenized assets represent real-world assets like bonds or real estate on a blockchain, enabling fractional ownership and faster settlement. Credit ratings assess the creditworthiness of these assets, traditionally issued by agencies like Moody's.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tradingview.com/news/cointelegraph:d328f19ab094b:0-moody-s-brings-credit-ratings-onchain-via-solana-explained/">Moody ’ s brings credit ratings onchain via... — TradingView News</a></li>
<li><a href="https://blockonomi.com/moodys-credit-ratings-go-live-on-solana-as-institutional-rwa-push-expands/">Moody ’ s Credit Ratings Go Live on Solana as... - Blockonomi</a></li>
<li><a href="https://en.wikipedia.org/wiki/Solana_(blockchain_platform)">Solana (blockchain platform)</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#Solana`, `#tokenization`, `#credit ratings`, `#DeFi`

---

<a id="item-18"></a>
## [Crypto Security Audits Are Not Enough](https://www.coindesk.com/opinion/2026/06/17/crypto-s-security-nightmare-won-t-be-solved-by-ordinary-audits) ⭐️ 6.0/10

An opinion piece argues that standard security audits are insufficient for crypto projects and calls for more rigorous approaches like formal verification. This matters because crypto hacks continue to cause billions in losses, and relying on ordinary audits may give a false sense of security to investors and users. The article suggests formal verification, which mathematically proves code correctness, as a stronger alternative to traditional audits that only check for known vulnerabilities.

rss · CoinDesk · Jun 17, 14:12

**Background**: Security audits are common in crypto to review smart contracts for bugs, but they often miss complex or novel exploits. Formal verification uses mathematical proofs to guarantee behavior, offering a higher level of assurance but requiring more time and expertise.

<details><summary>References</summary>
<ul>
<li><a href="https://www.blockchain-council.org/cryptocurrency/auditing-cryptocurrencies/">What to Consider While Auditing Cryptocurrencies?</a></li>
<li><a href="https://hashlock.pages.dev/services/formal-verification">Blockchain Formal Verification | Hashlock</a></li>
<li><a href="https://medium.com/reach-sh/formal-verification-for-the-blockchain-749ef947a0e2">Formal verification for the blockchain | by Christopher... | Medium</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#security`, `#audits`, `#blockchain`

---

<a id="item-19"></a>
## [Patients Use AI in Therapy, Survey Finds](https://decrypt.co/371451/psychologists-patients-bringing-ai-therapy-sessions-survey) ⭐️ 6.0/10

A new survey by the American Psychological Association (APA) found that over a third of psychologists have patients who use AI as an additional mental health resource. This indicates a growing integration of AI into mental health care, which could improve access but also raises concerns about reinforcing delusions or providing inaccurate advice. Clinicians warn that AI can reinforce delusions in patients with psychotic disorders, and the survey highlights the need for guidelines on AI use in therapy.

rss · Decrypt · Jun 17, 23:36

**Background**: AI chatbots like ChatGPT are increasingly used for mental health support, but they lack the training and accountability of licensed therapists. The APA survey underscores the ethical and clinical challenges this poses.

**Tags**: `#AI`, `#mental health`, `#psychology`, `#survey`

---

<a id="item-20"></a>
## [GLAAD Report: AI Amplifies Anti-LGBTQ Bias and Harms](https://decrypt.co/371431/glaad-ai-failing-lgbtq-users-warns-risk-growing) ⭐️ 6.0/10

GLAAD released a report warning that AI systems are increasingly amplifying anti-LGBTQ bias, misinformation, discrimination, and privacy harms. This matters because AI is being deployed in critical areas like hiring, healthcare, and content moderation, where biased systems can cause real-world harm to LGBTQ communities. The report highlights that AI can generate homophobic and transphobic content, misgender users, and expose private data, with risks growing as AI adoption expands.

rss · Decrypt · Jun 17, 17:43

**Background**: AI systems learn from large datasets that often contain societal biases, which can be perpetuated or amplified. GLAAD is an LGBTQ advocacy organization that monitors media representation and discrimination.

**Tags**: `#AI ethics`, `#bias`, `#LGBTQ`, `#privacy`, `#misinformation`

---

<a id="item-21"></a>
## [Binance Likely Denied EU License Under MiCA](https://decrypt.co/371343/binance-rejected-eu-regulatory-license-reuters) ⭐️ 6.0/10

Reuters reports that Binance is set to lose permission to operate in the European Union because its license application under the Markets in Crypto-Assets (MiCA) regulation is likely to be rejected. This would block Binance from serving EU clients, a major market, and signal stricter enforcement of MiCA rules, potentially reshaping the competitive landscape for crypto exchanges in Europe. Without a license, Binance would not qualify to operate in the EU from July 2026. The decision is reportedly imminent, with sources citing confidentiality rules at the relevant authority.

rss · Decrypt · Jun 16, 20:25

**Background**: The EU's MiCA regulation, effective from 2024-2025, requires crypto exchanges to obtain a license to offer services in the bloc. It aims to protect investors and ensure market integrity. Binance, the world's largest crypto exchange, has faced regulatory challenges globally, including in the US and Europe.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reuters.com/business/finance/binance-set-lose-eu-licence-bid-permission-offer-services-bloc-sources-say-2026-06-16/">Exclusive: Binance set to lose permission to operate in EU ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Markets_in_Crypto-Assets">Markets in Crypto -Assets - Wikipedia</a></li>
<li><a href="https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica">Markets in Crypto -Assets Regulation (MiCA)</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#regulation`, `#Binance`, `#EU`

---

<a id="item-22"></a>
## [Coinbase Plans Tokenized Stocks and Options Trading](https://decrypt.co/371293/coinbase-launch-tokenized-stock-trading-crypto-equities-options) ⭐️ 6.0/10

Coinbase announced plans to launch tokenized stock trading and crypto/equities options, aiming to become an 'everything exchange' that bridges traditional finance and crypto. This move signals a major step toward convergence of traditional and crypto markets, potentially attracting more institutional investors and expanding Coinbase's revenue streams. Tokenized stocks are blockchain-based digital assets representing ownership in real shares, while equity options are derivatives that derive value from underlying stocks. Coinbase has not yet specified a launch date or which stocks/options will be offered.

rss · Decrypt · Jun 16, 19:00

**Background**: Tokenized stocks allow investors to trade fractions of traditional shares on blockchain platforms, offering 24/7 trading and lower barriers. Equity options give the right to buy or sell shares at a set price, commonly used for hedging or speculation. Coinbase, already a leading crypto exchange, is expanding into traditional finance products.

<details><summary>References</summary>
<ul>
<li><a href="https://www.gemini.com/cryptopedia/what-are-tokenized-stocks-and-how-do-they-work">What Are Tokenized Stocks and How Do They Work? | Gemini</a></li>
<li><a href="https://www.coingecko.com/learn/what-are-tokenized-stocks">What Are Tokenized Stocks and Top Platforms to Get... | CoinGecko</a></li>
<li><a href="https://www.ig.com/en-ch/glossary-trading-terms/equity-options-definition">Equity Options Definition | What Does Equity Options Mean</a></li>

</ul>
</details>

**Tags**: `#Coinbase`, `#tokenized stocks`, `#crypto exchange`, `#equities options`

---

<a id="item-23"></a>
## [Australia High Court Rules Block Earner Needed License](https://www.theblock.co/post/405048/australia-high-court-block-earner-crypto-yield-case?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Australia's High Court unanimously ruled that Block Earner's fixed-yield crypto product required a financial services license, overturning a 2025 appeal decision that had favored the company. This ruling sets a binding precedent that crypto yield products may be classified as financial products under Australian law, increasing regulatory clarity and compliance obligations for crypto firms in Australia. Block Earner voluntarily closed the Earner product in November 2022 and has since pivoted to crypto-backed home loans after obtaining an Australian Credit Licence in May 2026.

rss · The Block · Jun 17, 09:45

**Background**: Under Australian law, financial products require an Australian Financial Services License (AFSL) from ASIC. The case centered on whether Block Earner's fixed-yield product constituted a financial product. Australia recently passed comprehensive digital asset legislation in April 2026, mandating licensing for crypto exchanges and custody providers.

<details><summary>References</summary>
<ul>
<li><a href="https://financefeeds.com/block-earner-loses-high-court-fight-over-crypto-yield-product/">Block Earner Loses High Court Fight Over Crypto Yield Product</a></li>
<li><a href="https://www.businessnewsaustralia.com/articles/high-court-rules-against-block-earner-finding-crypto-yield-product-was-a-financial-product.html">High Court rules against Block Earner over crypto product</a></li>
<li><a href="https://www.coindesk.com/policy/2026/04/01/australia-passes-crypto-licensing-bill-as-ausd24-billion-opportunity-comes-into-focus">Australia passes crypto regulation requiring exchanges to ...</a></li>

</ul>
</details>

**Tags**: `#crypto regulation`, `#Australia`, `#legal`, `#Block Earner`

---