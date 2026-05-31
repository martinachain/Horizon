---
layout: default
title: "Horizon Summary: 2026-05-31 (EN)"
date: 2026-05-31
lang: en
---

> From 66 items, 20 important content pieces were selected

---

1. [Microsoft to Convert Office 2019/2021 for Mac to View-Only](#item-1) ⭐️ 8.0/10
2. [Voxel Space Algorithm Explained](#item-2) ⭐️ 8.0/10
3. [Zig ELF Linker Improvements Boost Iteration Speed](#item-3) ⭐️ 8.0/10
4. [OpenRouter Raises $113M Series B](#item-4) ⭐️ 8.0/10
5. [AI Models Disagree on 67% of Facts, Study Finds](#item-5) ⭐️ 8.0/10
6. [CFTC Approves Bitcoin Perpetual Futures on Kalshi](#item-6) ⭐️ 8.0/10
7. [Domain Expertise Remains the True Competitive Advantage](#item-7) ⭐️ 7.0/10
8. [Shantell Sans: A Variable Font with Formality Slider](#item-8) ⭐️ 7.0/10
9. [Accenture acquires Ookla for $1.2B to boost network intelligence](#item-9) ⭐️ 7.0/10
10. [OpenBSD's openrsync: A Secure Rsync Implementation](#item-10) ⭐️ 7.0/10
11. [XRP Ledger Proposal Blocks Flash Loan Attacks](#item-11) ⭐️ 7.0/10
12. [CertiK CEO warns mass AI agent deployment risks disaster](#item-12) ⭐️ 7.0/10
13. [Paxos Wins SEC Approval to Clear U.S. Stocks on Blockchain](#item-13) ⭐️ 7.0/10
14. [TrapDoor Attack Targets Solana, Sui, Aptos Wallets](#item-14) ⭐️ 7.0/10
15. [AI Prompt Injection: The Hidden Threat Hijacking Chatbots](#item-15) ⭐️ 7.0/10
16. [Gravity Bridge on Cosmos loses $5.4M in key compromise](#item-16) ⭐️ 7.0/10
17. [Base Launches Azul Upgrade on Mainnet, Boosting Decentralization](#item-17) ⭐️ 7.0/10
18. [Bitcoin's quantum risk may extend beyond wallet keys](#item-18) ⭐️ 6.0/10
19. [Kalshi Sues Minnesota Over Prediction Market Ban](#item-19) ⭐️ 6.0/10
20. [Court Freezes $12.6M in Zama cUSDC Contract](#item-20) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Microsoft to Convert Office 2019/2021 for Mac to View-Only](https://consumerrights.wiki/w/Microsoft_Office_2019_and_2021_for_Mac_view-only_conversion_(2026)) ⭐️ 8.0/10

Microsoft plans to convert perpetually-licensed Office 2019 and 2021 for Mac to view-only mode, preventing users from editing or creating documents after a certain date. This move undermines the concept of perpetual software ownership, potentially forcing users into subscriptions and sparking widespread consumer backlash and legal concerns. The change affects Office 2019 and 2021 for Mac, which were sold as perpetual licenses. After the conversion, users can only view documents but cannot edit, save, or create new ones.

hackernews · antipurist · May 30, 23:26 · [Discussion](https://news.ycombinator.com/item?id=48341578)

**Background**: Perpetual licenses allow users to use software indefinitely after a one-time purchase, unlike subscriptions which require ongoing payments. Microsoft has been shifting toward subscription-based Office 365, and this move further pressures users to migrate.

<details><summary>References</summary>
<ul>
<li><a href="https://talk.tidbits.com/t/office-2019-switching-to-view-only-mode-what-to-do/33495">Office 2019 switching to view - only mode —what to do? - TidBITS Talk</a></li>

</ul>
</details>

**Discussion**: Commenters express outrage, calling for boycotts and switching to free alternatives like LibreOffice. Some raise legal concerns under Australian consumer law, while others speculate the change is driven by Microsoft wanting to prevent AI agents from using offline licenses.

**Tags**: `#Microsoft`, `#software licensing`, `#consumer rights`, `#Office`, `#digital ownership`

---

<a id="item-2"></a>
## [Voxel Space Algorithm Explained](https://s-macke.github.io/VoxelSpace/) ⭐️ 8.0/10

A detailed technical explanation of the Voxel Space rendering algorithm used in the 1992 game Comanche has been published, including a live demo and source code. This algorithm was groundbreaking for its time, enabling realistic terrain rendering on limited hardware, and its explanation helps preserve and understand retro graphics techniques. The algorithm uses a height map and color map, rasterizing vertical lines from back to front (painter's algorithm) to render terrain efficiently.

hackernews · davikr · May 30, 14:25 · [Discussion](https://news.ycombinator.com/item?id=48336564)

**Background**: Voxel Space is a proprietary voxel engine developed by NovaLogic for the 1992 game Comanche: Maximum Overkill. Unlike true voxels that divide 3D space equally, it uses a height map approach, rendering terrain as a set of prisms. The engine was written entirely in assembly language and was one of the first commercial flight simulators to use voxel technology.

<details><summary>References</summary>
<ul>
<li><a href="https://s-macke.github.io/VoxelSpace/">Voxel Space | VoxelSpace</a></li>
<li><a href="https://en.wikipedia.org/wiki/Comanche_(video_game_series)">Comanche (video game series) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Voxel">Voxel - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the algorithm is technically a height map rather than true voxels, but praised its historical significance. Some shared personal implementations and testing methodologies inspired by the game.

**Tags**: `#voxel rendering`, `#game development`, `#retro computing`, `#algorithms`, `#graphics`

---

<a id="item-3"></a>
## [Zig ELF Linker Improvements Boost Iteration Speed](https://ziglang.org/devlog/2026/#2026-05-30) ⭐️ 8.0/10

Zig's latest devlog details significant improvements to its self-hosted ELF linker, focusing on faster incremental linking for rapid development iteration. This progress brings Zig closer to becoming a viable C replacement, enabling developers to iterate at speeds comparable to interpreted languages while retaining C-like performance. The improvements are part of Zig's self-hosted linker, which is tightly coupled with the self-hosted compiler and handles multiple output formats including ELF, Mach-O, COFF, and WebAssembly.

hackernews · kristoff_it · May 30, 17:29 · [Discussion](https://news.ycombinator.com/item?id=48338673)

**Background**: Zig is a systems programming language that aims to replace C by offering modern features like compile-time code execution and no hidden control flow. The ELF (Executable and Linkable Format) is a common binary format for executables on Linux and Unix-like systems. A linker combines compiled object files into a final executable, and incremental linking speeds up development by only re-linking changed parts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Executable_and_Linkable_Format">Executable and Linkable Format - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language) - Wikipedia</a></li>
<li><a href="https://ziglang.org/">Home ⚡ Zig Programming Language</a></li>

</ul>
</details>

**Discussion**: Community members expressed excitement about Zig's potential as a C replacement, with some noting that the improved linker enables iteration speeds comparable to JavaScript or Python. Others discussed using Zig as a transpilation target for memory-safe languages or porting runtimes like Raku's MOARVM to Zig.

**Tags**: `#Zig`, `#linker`, `#compiler`, `#systems programming`, `#ELF`

---

<a id="item-4"></a>
## [OpenRouter Raises $113M Series B](https://openrouter.ai/announcements/series-b) ⭐️ 8.0/10

OpenRouter, a unified API proxy for large language models, announced a $113 million Series B funding round. The company plans to use the capital to continue providing low-friction access to multiple LLMs through a single interface. This funding validates OpenRouter's role as critical infrastructure in the rapidly evolving LLM ecosystem, where developers need easy access to multiple models. It also signals investor confidence in the proxy model as a sustainable business, especially as model providers proliferate. OpenRouter remains founder-led and founder-controlled after the raise, according to co-founder and COO numlocked. The company charges a small surcharge (e.g., 5% on expensive models like Claude Opus) for its proxy service, which some community members find acceptable for the convenience.

hackernews · freeCandy · May 30, 17:27 · [Discussion](https://news.ycombinator.com/item?id=48338660)

**Background**: OpenRouter is a service that provides a unified API to access dozens of large language models from different providers, eliminating the need for developers to integrate with each provider's distinct API. It also offers features like billing caps, which help users control costs when running AI applications in production. The LLM landscape is fragmented, with many competing models and providers, making tools like OpenRouter valuable for experimentation and deployment.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Aculeasis/openrouter-proxy">GitHub - Aculeasis/openrouter-proxy · GitHub</a></li>
<li><a href="https://github.com/nexon33/Openrouter-Proxy-Server">GitHub - nexon33/Openrouter-Proxy-Server · GitHub</a></li>

</ul>
</details>

**Discussion**: Community members praised OpenRouter for its low-friction model access and billing caps, with simonw noting these as significant value adds. However, some questioned the business model, with minimaxir pointing out the surcharge on expensive models, and tom1337 asked about the lack of open-source code, noting the name 'OpenRouter' may be misleading.

**Tags**: `#AI`, `#funding`, `#LLM`, `#API`, `#infrastructure`

---

<a id="item-5"></a>
## [AI Models Disagree on 67% of Facts, Study Finds](https://decrypt.co/369480/ai-models-disagree-fact-checking-two-thirds-study) ⭐️ 8.0/10

A new study tested five leading AI models on 1,000 real-world factual claims and found they disagreed on 67% of them, highlighting severe inconsistency in fact-checking capabilities. This finding undermines trust in AI systems for tasks requiring factual accuracy, such as journalism, education, and research, and raises concerns about deploying these models in high-stakes environments. The study used 1,000 claims from diverse domains and evaluated models including GPT-4, Claude, and Gemini, with disagreement defined as any difference in verdict (true, false, or uncertain).

rss · Decrypt · May 29, 17:26

**Background**: Frontier AI models are the most advanced general-purpose models, trained on massive computational budgets and capable of exceeding state-of-the-art across multiple domains. Fact-checking is a critical application where consistency is essential for reliability. Previous studies have also shown high inaccuracy rates in AI-powered search engines.

<details><summary>References</summary>
<ul>
<li><a href="https://www.wired.com/story/fact-checking-ai/">I’m a Professional Fact-Checker. AI Is Wrong More Often Than You Think | WIRED</a></li>

</ul>
</details>

**Tags**: `#AI reliability`, `#fact-checking`, `#large language models`, `#AI research`

---

<a id="item-6"></a>
## [CFTC Approves Bitcoin Perpetual Futures on Kalshi](https://decrypt.co/369465/cftc-approves-bitcoin-perpetual-futures-kalshi) ⭐️ 8.0/10

The U.S. Commodity Futures Trading Commission (CFTC) has issued an order allowing Kalshi, a regulated prediction market, to offer Bitcoin perpetual futures contracts to U.S. customers. This marks a regulatory milestone for crypto derivatives in the U.S., potentially paving the way for broader institutional adoption and more regulated crypto trading products. Kalshi will start with contracts tied to Bitcoin's price, and the approval also opens the door for other platforms like Coinbase to offer similar products.

rss · Decrypt · May 29, 15:00

**Background**: Perpetual futures contracts are financial derivatives that have no expiration date, allowing traders to speculate on price movements with leverage. Unlike traditional futures, they do not require settlement on a fixed date. Kalshi is a federally regulated prediction market platform that primarily focuses on event contracts, but this approval expands its offerings into crypto derivatives.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kalshi">Kalshi - Wikipedia</a></li>
<li><a href="https://www.kraken.com/hu/learn/trading/perpetual-futures-contracts">What are perpetual futures contracts ? | Kraken</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#derivatives`, `#bitcoin`, `#CFTC`

---

<a id="item-7"></a>
## [Domain Expertise Remains the True Competitive Advantage](https://www.brethorsting.com/blog/2026/05/domain-expertise-has-always-been-the-real-moat/) ⭐️ 7.0/10

A blog post argues that domain expertise is the real moat, not AI tools, using examples of vibe coding failures where lack of domain knowledge led to flawed applications. As AI coding tools proliferate, this discussion refocuses attention on the irreplaceable value of deep domain knowledge, affecting how developers and companies invest in skills and tooling. The post highlights that vibe coding—accepting AI-generated code without full understanding—can produce apps that appear functional but have critical flaws in database design or logic, which only domain experts can catch.

hackernews · aaronbrethorst · May 30, 20:40 · [Discussion](https://news.ycombinator.com/item?id=48340411)

**Background**: Vibe coding is a recent trend where developers describe tasks in plain language to an AI, which generates code automatically, often without the developer fully reviewing or understanding it. This approach has gained popularity with the rise of powerful LLMs like GPT-4 and Claude. However, critics argue that it can lead to brittle or incorrect software when the user lacks domain expertise.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/vibe-coding">What is Vibe Coding? | IBM</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree that domain expertise is crucial, with some noting that software engineering itself is a domain. Others express frustration with shifting narratives about what makes a developer valuable in the AI era.

**Tags**: `#AI`, `#software engineering`, `#domain expertise`, `#vibe coding`

---

<a id="item-8"></a>
## [Shantell Sans: A Variable Font with Formality Slider](https://shantellsans.com/process) ⭐️ 7.0/10

Shantell Sans is a newly designed variable font that features a unique 'formality' axis, allowing users to smoothly adjust the font's appearance from casual to formal. The font has been released on Google Fonts and has received widespread acclaim for its design and accessibility. This font demonstrates the creative potential of variable font technology, particularly the formality slider, which offers unprecedented typographic control. Its positive reception, especially from users with dyslexia, highlights the importance of inclusive design in typography. The formality axis is a continuous range that interpolates between informal and formal letterforms, making it a versatile tool for designers. The font is available as a single variable font file, reducing file size and improving web performance.

hackernews · aleda145 · May 30, 22:06 · [Discussion](https://news.ycombinator.com/item?id=48341062)

**Background**: Variable fonts are a font format that stores multiple design variations (such as weight, width, or slant) within a single file, allowing smooth interpolation between styles. The formality axis is an innovative addition that adjusts the level of formality in the typeface, a concept rarely seen in variable fonts.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Variable_font">Variable font</a></li>
<li><a href="https://fonts.google.com/knowledge/introducing_type/introducing_variable_fonts">Introducing variable fonts – Fonts Knowledge - Google Fonts</a></li>

</ul>
</details>

**Discussion**: Community members praised the formality slider as one of the coolest uses of a variable font axis, and many noted the font's beauty and accessibility benefits, especially for dyslexic readers. Some expressed interest in a monospaced version.

**Tags**: `#typography`, `#variable fonts`, `#design`, `#accessibility`

---

<a id="item-9"></a>
## [Accenture acquires Ookla for $1.2B to boost network intelligence](https://newsroom.accenture.com/news/2026/accenture-to-acquire-ookla-to-strengthen-network-intelligence-and-experience-with-data-and-ai-for-enterprises) ⭐️ 7.0/10

Accenture announced on March 3, 2026, its acquisition of Ookla, the company behind Speedtest, Downdetector, Ekahau, and RootMetrics, for $1.2 billion. This acquisition strengthens Accenture's network intelligence and data-driven services for telecoms and enterprises, enabling end-to-end optimization of 5G and Wi-Fi networks critical for AI transformation. Ookla's data platform processes over 250 million consumer-initiated tests per month, complemented by drive, walk, and embedded testing, providing invaluable insights for network optimization.

hackernews · Garbage · May 30, 16:28 · [Discussion](https://news.ycombinator.com/item?id=48337987)

**Background**: Ookla is best known for Speedtest.net, a widely used internet speed testing tool, and Downdetector, which tracks service outages. The company also provides network intelligence solutions that telcos use to benchmark and improve their networks. Accenture, a global IT services and consulting firm, has been expanding its telecom capabilities, including through its prior acquisition of Umlaut.

<details><summary>References</summary>
<ul>
<li><a href="https://newsroom.accenture.com/news/2026/accenture-to-acquire-ookla-to-strengthen-network-intelligence-and-experience-with-data-and-ai-for-enterprises">Accenture to Acquire Ookla to Strengthen Network Intelligence and Experience with Data and AI For Enterprises</a></li>
<li><a href="https://www.ookla.com/solutions/competitive-network-intelligence">Competitive Benchmarking & Network Intelligence Solutions | Ookla®</a></li>
<li><a href="https://en.wikipedia.org/wiki/Downdetector">Downdetector - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the deal is primarily a data acquisition, as Ookla's real value lies in selling network performance data to telcos for six-figure annual fees. Some expressed surprise at the high price, while others highlighted the depth of Ookla's business beyond consumer-facing tools.

**Tags**: `#acquisition`, `#network intelligence`, `#telecom`, `#data monetization`, `#accenture`

---

<a id="item-10"></a>
## [OpenBSD's openrsync: A Secure Rsync Implementation](https://github.com/kristapsdz/openrsync) ⭐️ 7.0/10

The OpenBSD team has developed openrsync, a portable implementation of the rsync file synchronization tool, which is gaining traction for its security features and use in RPKI validation. openrsync provides a more secure alternative to the widely-used Samba rsync, especially for security-conscious users and critical infrastructure like RPKI validators, leveraging OpenBSD's pledge and unveil security mechanisms. openrsync is designed to be portable and includes security features like pledge(2) and unveil(2) on OpenBSD, which restrict system calls and file system access to mitigate potential exploits.

hackernews · sph · May 30, 10:51 · [Discussion](https://news.ycombinator.com/item?id=48334854)

**Background**: rsync is a widely-used utility for efficiently transferring and synchronizing files across systems, often over SSH. OpenBSD is a security-focused Unix-like operating system known for its proactive security features like pledge and unveil, which sandbox processes. RPKI (Resource Public Key Infrastructure) is a security framework that uses cryptographic certificates to validate BGP route announcements, preventing IP address hijacking.

<details><summary>References</summary>
<ul>
<li><a href="https://www.arin.net/resources/manage/rpki/">Resource Public Key Infrastructure (RPKI) - American Registry for Internet Numbers</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenBSD_security_features">OpenBSD security features - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community members report that openrsync has improved over time but still lacks some features compared to Samba rsync, such as handling certain path behaviors. Others highlight its development as part of an RPKI validator and note the existence of a Go-based rsync implementation by the Gokrazy team.

**Tags**: `#rsync`, `#OpenBSD`, `#security`, `#file synchronization`, `#open source`

---

<a id="item-11"></a>
## [XRP Ledger Proposal Blocks Flash Loan Attacks](https://www.coindesk.com/tech/2026/05/29/xrp-ledger-s-new-proposal-blocks-the-flash-loan-attacks-costing-defi-hundreds-of-millions) ⭐️ 7.0/10

A new proposal for the XRP Ledger aims to block flash loan attacks that have caused hundreds of millions of dollars in losses across DeFi protocols. If implemented, this proposal could significantly enhance DeFi security by eliminating a common attack vector, potentially saving millions and restoring user confidence. The proposal introduces a mechanism that prevents the atomic borrowing and repayment of large sums within a single transaction, which is the core of flash loan attacks.

rss · CoinDesk · May 31, 02:30

**Background**: Flash loan attacks exploit DeFi protocols by borrowing large amounts of cryptocurrency without collateral and manipulating prices or draining liquidity, all within one transaction. These attacks have cost the DeFi ecosystem hundreds of millions of dollars. The XRP Ledger is a blockchain designed for payments and decentralized applications.

<details><summary>References</summary>
<ul>
<li><a href="https://web3.okx.com/fi/learn/flash-loan-attack-explained">What is a Flash Loan Attack ? | OKX Wallet</a></li>
<li><a href="https://coinmarketcap.com/academy/article/what-are-flash-loan-attacks">What Are Flash Loan Attacks ? | CoinMarketCap</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#XRP Ledger`, `#blockchain`

---

<a id="item-12"></a>
## [CertiK CEO warns mass AI agent deployment risks disaster](https://www.coindesk.com/tech/2026/05/29/mass-deployment-of-ai-agents-is-a-disaster-waiting-to-happen-says-certik-ceo) ⭐️ 7.0/10

Ronghui Gu, CEO of blockchain security firm CertiK, warned that the mass deployment of AI agents without proper isolation and testing could lead to catastrophic failures, including unauthorized access to personal data and digital assets. As AI agents become more autonomous and widely used, the potential for large-scale harm increases significantly, affecting both individual users and the broader digital ecosystem. This warning highlights the urgent need for robust security measures and regulatory frameworks. Gu specifically recommended isolating AI agents during testing to prevent them from accessing critical personal information or digital assets. He also noted that attackers are increasingly using AI to outspend defenders, making the security landscape even more challenging.

rss · CoinDesk · May 29, 15:31

**Background**: AI agents are autonomous software programs that can perform tasks on behalf of users, such as managing finances or making decisions. Unlike traditional chatbots, they have direct access to systems and data, raising the stakes if they fail or are compromised. CertiK is a prominent blockchain security firm known for auditing smart contracts and decentralized applications.

<details><summary>References</summary>
<ul>
<li><a href="https://coinspectator.com/other/2026/05/29/mass-deployment-of-ai-agents-is-a-disaster-waiting-to-happen-says-certik-ceo/">Mass deployment of AI agents is a disaster waiting to happen, says CertiK CEO – CoinSpectator – Real-time Cryptocurrency News</a></li>
<li><a href="https://www.theblock.co/post/401280/unfair-game-certik-ceo-defi-attackers-using-ai-outspend-defenders">'It's an unfair game': CertiK CEO says DeFi attackers using AI to outspend defenders | The Block</a></li>
<li><a href="https://toolwise.ai/news/ai-agents-testing-business-deployment-risks">AI Agent Testing Risks for Small Business | ToolWise | ToolWise</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#AI agents`, `#risk management`, `#deployment`

---

<a id="item-13"></a>
## [Paxos Wins SEC Approval to Clear U.S. Stocks on Blockchain](https://www.coindesk.com/policy/2026/05/29/paxos-is-first-blockchain-firm-to-provide-settlement-and-clearing-services-following-sec-approval) ⭐️ 7.0/10

Paxos has become the first blockchain-native firm to receive SEC approval as a registered clearing agency, enabling it to clear and settle U.S. stock trades on blockchain infrastructure. This milestone marks a significant convergence of crypto and traditional finance, potentially reducing costs and increasing efficiency in capital markets by eliminating intermediaries and automating processes. The approval ends a seven-year regulatory marathon that began with a 2019 no-action letter, and Paxos is now registered under the SEC's 17A framework.

rss · CoinDesk · May 29, 12:28

**Background**: Clearing and settlement are post-trade processes that ensure securities transactions are completed correctly. Traditionally, these functions are handled by centralized entities like the DTCC. Blockchain technology offers a decentralized alternative that can reduce costs, speed up settlement, and increase transparency.

<details><summary>References</summary>
<ul>
<li><a href="https://coinmarketcap.com/academy/article/+sec-approves-paxos-blockchain-clearing-agency">SEC Approves Paxos as First Blockchain Clearing Agency</a></li>
<li><a href="https://www.binance.com/en/square/post/05-29-2026-paxos-gains-sec-approval-to-clear-u-s-stocks-on-blockchain-328386303699970">Paxos Gains SEC Approval to Clear U.S. Stocks on Blockchain</a></li>
<li><a href="https://phemex.com/academy/paxos-sec-approval-google-trends-analysis">Paxos Crypto SEC Approval: Smart Money Moves After Breakout</a></li>

</ul>
</details>

**Discussion**: The community reaction is overwhelmingly positive, with many calling it a 'massive' step for real-world asset tokenization. Some express curiosity about the specific blockchain infrastructure Paxos will use and how it will integrate with existing market systems.

**Tags**: `#blockchain`, `#SEC`, `#fintech`, `#regulation`, `#Paxos`

---

<a id="item-14"></a>
## [TrapDoor Attack Targets Solana, Sui, Aptos Wallets](https://www.coindesk.com/tech/2026/05/29/solana-sui-and-aptos-wallet-data-targeted-in-trapdoor-package-attack) ⭐️ 7.0/10

A supply-chain attack campaign named TrapDoor has been discovered, deploying 34+ malicious packages on npm, PyPI, and Crates.io that target wallet data and credentials on Solana, Sui, and Aptos networks. This attack threatens the security of crypto developers and users across three major blockchain ecosystems, potentially leading to stolen funds and compromised cloud credentials. The malicious packages are disguised as legitimate developer tools such as 'wallet-security-checker' and 'defi-risk-scanner', and the campaign has been flagged by Socket Security.

rss · CoinDesk · May 29, 08:19

**Background**: Supply-chain attacks involve injecting malicious code into software packages that developers unknowingly download. In the crypto space, such attacks can steal private keys or wallet credentials, leading to asset theft. Solana, Sui, and Aptos are high-performance blockchains popular among developers.

<details><summary>References</summary>
<ul>
<li><a href="https://socket.dev/blog/trapdoor-crypto-stealer-npm-pypi-crates">TrapDoor Crypto Stealer Supply Chain Attack Hits 34 Packages...</a></li>
<li><a href="https://thehackernews.com/2026/05/trapdoor-supply-chain-attack-spreads.html">TrapDoor Supply Chain Attack Spreads Credential-Stealing Malware via npm, PyPI, and CratesIO</a></li>
<li><a href="https://www.kucoin.com/news/flash/trapdoor-malware-targets-solana-sui-and-aptos-wallet-data-via-supply-chain-attack">TrapDoor Malware Targets Solana , Sui , and Aptos Wallet ... | KuCoin</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#security`, `#supply chain attack`, `#cryptocurrency`, `#wallet`

---

<a id="item-15"></a>
## [AI Prompt Injection: The Hidden Threat Hijacking Chatbots](https://decrypt.co/resources/what-is-ai-prompt-injection-attack) ⭐️ 7.0/10

This article explains what AI prompt injection attacks are, how they work, and why they are difficult to prevent, noting that OpenAI acknowledges the problem may never be fully solved. Prompt injection attacks pose a critical security risk to widely-used AI chatbots like ChatGPT, Claude, and Gemini, potentially allowing attackers to bypass safety measures and extract sensitive data. Prompt injection is a type of code injection that manipulates an AI model's instructions via crafted inputs, often referred to as 'jailbreaking.' The attack was first identified as a security vulnerability by Jonathan Cefalu in May 2022.

rss · Decrypt · May 30, 13:01

**Background**: Large language models (LLMs) like GPT-4 are trained to follow instructions from prompts. Prompt injection exploits this by inserting malicious instructions that override the original intent, causing the model to perform unintended actions such as leaking private data or executing unauthorized commands.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>
<li><a href="https://owasp.org/www-community/attacks/PromptInjection">Prompt Injection | OWASP Foundation</a></li>
<li><a href="https://d2lvhbqifib4zm.cloudfront.net/blog/prompt-injection-attack/">What is a prompt injection attack , and how to prevent it</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#prompt injection`, `#chatbots`, `#LLM vulnerabilities`

---

<a id="item-16"></a>
## [Gravity Bridge on Cosmos loses $5.4M in key compromise](https://www.theblock.co/post/403108/cosmos-based-gravity-bridge-drained-of-5-4-million-in-suspected-key-compromise-researchers-say?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

The Cosmos-based Gravity Bridge was drained of $5.4 million in a suspected key compromise, with the attacker stealing USDC, ether, tether, and PAYG tokens and laundering funds through ChangeNow and Binance. This incident highlights the persistent risk of key compromise in blockchain bridges, which are critical infrastructure for cross-chain interoperability, and could erode user trust in the Cosmos ecosystem. The attacker targeted USDC, ether, tether, and PAYG tokens, and laundered a portion of the funds through ChangeNow and Binance, according to researchers.

rss · The Block · May 30, 18:21

**Background**: Gravity Bridge is a Cosmos-based bridge that connects Ethereum to the Cosmos ecosystem via IBC (Inter-Blockchain Communication). Key compromises occur when private keys controlling bridge funds are stolen, often due to poor security practices like storing keys in cloud services.

<details><summary>References</summary>
<ul>
<li><a href="https://www.gravitybridge.net/home-v2">COSMOS | Gravity Bridge</a></li>
<li><a href="https://github.com/cosmos/gravity-bridge">GitHub - cosmos / gravity - bridge : A CosmosSDK application for...</a></li>
<li><a href="https://www.halborn.com/blog/post/top-7-ways-your-private-keys-get-hacked">Top 7 Ways Your Private Keys Get Hacked</a></li>

</ul>
</details>

**Tags**: `#security`, `#blockchain`, `#Cosmos`, `#bridge hack`, `#cryptocurrency`

---

<a id="item-17"></a>
## [Base Launches Azul Upgrade on Mainnet, Boosting Decentralization](https://www.theblock.co/post/403003/base-launches-azul-on-mainnet-pushing-coinbases-ethereum-l2-toward-full-decentralization?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Base has deployed the Azul upgrade on mainnet, introducing a multiproof system combining TEE and ZK proofs, along with a new client stack. This is Base's first fully independent upgrade, moving it closer to Stage 2 decentralization. Azul enhances Base's security and censorship resistance by allowing either TEE or ZK proofs to finalize state independently, with ZK proofs able to override TEE proofs if needed. This reduces withdrawal finality to as little as one day and significantly improves network reliability. The upgrade consolidates Base onto a single execution client, base-reth-node, and introduces a new consensus client, base-consensus, built on OP Kona. It has already reduced empty blocks by about 99%, from around 200 per day to approximately two, and sustained multiple bursts of 5,000 transactions per second.

rss · The Block · May 29, 09:31

**Background**: Ethereum Layer 2 networks like Base aim to scale Ethereum while inheriting its security. Decentralization is measured in stages: Stage 1 requires a single proof system, while Stage 2 demands multiple independent proof systems for trust-minimization. Azul's multiproof design and new client stack are key steps toward Stage 2.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/403003/base-launches-azul-on-mainnet-pushing-coinbases-ethereum-l2-toward-full-decentralization">Base launches Azul on mainnet, pushing Coinbase's Ethereum L2 toward full decentralization | The Block</a></li>
<li><a href="https://thedefiant.io/news/blockchains/base-announces-azul-upgrade">Base Pushes Toward Final L2 Stage with First Independent Upgrade - "The Defiant"</a></li>
<li><a href="https://blog.base.dev/next-chapter-for-base-chain-1">A new, unified stack for Base Chain - Base Engineering Blog</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#Layer 2`, `#Decentralization`, `#Base`, `#Azul`

---

<a id="item-18"></a>
## [Bitcoin's quantum risk may extend beyond wallet keys](https://www.coindesk.com/tech/2026/05/30/bitcoin-s-biggest-quantum-risk-may-not-be-wallet-keys-an-early-investor-fears-something-bigger) ⭐️ 6.0/10

An early Bitcoin investor warns that quantum computing could threaten Bitcoin's consensus mechanism, not just wallet keys, potentially enabling a 51% attack. If quantum computers can break Bitcoin's proof-of-work consensus, the entire network's security could be compromised, affecting all users and the cryptocurrency market. The investor suggests that quantum computers might solve mining puzzles faster, allowing an attacker to control the blockchain. This risk is separate from the well-known threat to private keys.

rss · CoinDesk · May 30, 05:27

**Background**: Bitcoin uses a consensus mechanism called Proof-of-Work (PoW), where miners compete to solve cryptographic puzzles to validate transactions. Quantum computers, once powerful enough, could solve these puzzles much faster, potentially enabling a 51% attack where a single entity controls the majority of mining power.

<details><summary>References</summary>
<ul>
<li><a href="https://www.gate.com/learn/glossary/bitcoin-consensus-mechanism">Bitcoin Consensus Mechanism : PoW Explained | Gate Glossary</a></li>
<li><a href="https://medium.com/thecapital/the-difference-between-general-and-specific-consensus-in-bitcoin-538ed8dfe696">The Difference Between General And Specific Consensus In Bitcoin</a></li>
<li><a href="https://cryptoslate.com/bitcoin-consensus-mechanisms-explained/">Bitcoin consensus mechanisms explained: Byzantine fault-tolerance</a></li>

</ul>
</details>

**Tags**: `#bitcoin`, `#quantum computing`, `#cryptocurrency`, `#security`

---

<a id="item-19"></a>
## [Kalshi Sues Minnesota Over Prediction Market Ban](https://www.coindesk.com/policy/2026/05/29/kalshi-follows-cftc-in-suing-minnesota-over-law-criminalizing-prediction-markets) ⭐️ 6.0/10

Kalshi, a regulated prediction market exchange, filed a lawsuit against Minnesota over a state law that criminalizes prediction markets, following a similar lawsuit by the CFTC against multiple states. This lawsuit highlights the ongoing legal battle between federal and state authorities over the regulation of prediction markets, which could set a precedent for the industry's future in the U.S. The CFTC has asserted exclusive jurisdiction over prediction markets under the Commodity Exchange Act, and has sued Rhode Island and other states to block their enforcement actions. Kalshi's lawsuit aligns with the CFTC's position.

rss · CoinDesk · May 29, 09:59

**Background**: Prediction markets allow trading on the outcome of future events, such as elections or economic indicators. They are considered gambling by some governments and are banned in certain jurisdictions. The CFTC regulates these markets as commodity derivatives.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cftc.gov/PressRoom/PressReleases/9206-26">CFTC Sues Trio of States to Reaffirm its Exclusive Jurisdiction Over Prediction Markets | CFTC</a></li>
<li><a href="https://www.cnbc.com/2026/05/28/cftc-sues-rhode-island-over-actions-against-prediction-markets.html">CFTC sues Rhode Island over actions against prediction markets</a></li>
<li><a href="https://www.cftc.gov/PressRoom/PressReleases/9230-26">CFTC Reaffirms Exclusive Jurisdiction Over Prediction Markets in Sixth Circuit Amicus Brief | CFTC</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#regulation`, `#crypto`, `#legal`

---

<a id="item-20"></a>
## [Court Freezes $12.6M in Zama cUSDC Contract](https://www.theblock.co/post/403091/court-ordered-circle-freeze-traps-12-6-million-in-zama-cusdc-contract-amid-overnight-finance-suit?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

A U.S. court ordered Circle to freeze the cUSDC smart contract deployed by Zama, locking $12.6 million in user funds, amid a lawsuit against Overnight Finance. This incident highlights the legal and regulatory risks in DeFi, where court orders can directly impact smart contracts and user funds, potentially setting a precedent for future interventions. The freeze occurred on May 30, 2025, following a text-only court order issued on May 29 by the U.S. District Court for the Northern District of California. The cUSDC contract had been publicly deployed for about 154 days, and the depositing address showed no sanctions flags at the time of deposit.

rss · The Block · May 30, 12:30

**Background**: cUSDC is a confidential version of USDC that uses encryption to hide transaction amounts. Circle, the issuer of USDC, has the ability to blacklist addresses or contracts under court orders. Overnight Finance is a DeFi protocol involved in a civil lawsuit that led to this freeze.

<details><summary>References</summary>
<ul>
<li><a href="https://www.gncrypto.news/news/circle-blacklists-zama-cusdc-freezes-12-6m-usdc/">Circle Blacklists Zama cUSDC , Freezes $12.6M USDC</a></li>
<li><a href="https://www.kucoin.com/news/flash/circle-freezes-zama-s-cusdc-contract-locking-12-6m-in-user-funds">Circle Freezes Zama's cUSDC Contract , Locking $12.6M in... | KuCoin</a></li>
<li><a href="https://thecoinomist.com/news/court-orders-circle-freeze-12-6m-zama-cusdc/">Court Orders Circle to Freeze $12.6M in Zama cUSDC</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#crypto`, `#legal`, `#smart contracts`

---