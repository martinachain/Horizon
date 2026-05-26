---
layout: default
title: "Horizon Summary: 2026-05-26 (EN)"
date: 2026-05-26
lang: en
---

> From 50 items, 20 important content pieces were selected

---

1. [Using AI to Write Better Code More Slowly](#item-1) ⭐️ 8.0/10
2. [California proposes exempting Linux from age-verification law](#item-2) ⭐️ 8.0/10
3. [CVE-2026-28952: macOS kernel bug found by Claude AI](#item-3) ⭐️ 8.0/10
4. [AI Accelerates Quantum Threat to Crypto, Experts Warn](#item-4) ⭐️ 8.0/10
5. [George Hotz Warns AI Coding Agents Create Undetectable Slop](#item-5) ⭐️ 8.0/10
6. [Pope Leo XIV's AI Encyclical Declares Data a Common Good](#item-6) ⭐️ 8.0/10
7. [TrapDoor malware targets crypto dev environments](#item-7) ⭐️ 8.0/10
8. [How Shamir's Secret Sharing Works](#item-8) ⭐️ 7.0/10
9. [Norway's 2 PB Huawei flash storage for sovereign LLM training](#item-9) ⭐️ 7.0/10
10. [Mullvad Rolls Out Mitigation for Exit IP Fingerprinting](#item-10) ⭐️ 7.0/10
11. [Programming book sales decline as online learning rises](#item-11) ⭐️ 7.0/10
12. [Ethereum Foundation to Shrink, Sell Less ETH, Focus on CROPS](#item-12) ⭐️ 7.0/10
13. [Perplexity Open-Sources Bumblebee Malware Scanner](#item-13) ⭐️ 7.0/10
14. [NYT: CFTC Purged Staff Who Opposed Trump-Tied Crypto Firms](#item-14) ⭐️ 7.0/10
15. [StablR's EURR and USDR Depeg After $13.5M Multisig Exploit](#item-15) ⭐️ 7.0/10
16. [Walking Boosts Creativity More Than Sitting, Study Finds](#item-16) ⭐️ 6.0/10
17. [What We Lost When We Stopped Letting Kids Leave the Front Yard](#item-17) ⭐️ 6.0/10
18. [Crypto rails become default payment layer for AI agents](#item-18) ⭐️ 6.0/10
19. [Georgia to Launch Official Stablecoin with Tether](#item-19) ⭐️ 6.0/10
20. [EIP-8182 Proposed for Ethereum Hegota Upgrade](#item-20) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Using AI to Write Better Code More Slowly](https://nolanlawson.com/2026/05/25/using-ai-to-write-better-code-more-slowly/) ⭐️ 8.0/10

Nolan Lawson argues that AI coding tools should be used for careful iteration and review to produce higher-quality code, rather than rushing to generate low-quality output quickly. This challenges the prevailing narrative that AI's main value in coding is speed, emphasizing quality and thoughtful engineering practices instead. The article suggests using slower but better AI models (e.g., Claude 4.7 Max) for implementation and faster models (e.g., Codex GPT 5.5) for review, with multiple rounds of iteration.

hackernews · signa11 · May 25, 23:16 · [Discussion](https://news.ycombinator.com/item?id=48272984)

**Background**: AI-assisted coding tools like GitHub Copilot and Claude have become popular for generating code quickly, but often produce buggy or low-quality output. The article advocates for a workflow that prioritizes code review and iterative refinement over raw speed.

**Discussion**: Commenters share mixed experiences: some find AI review loops time-consuming but valuable, while others note that AI often produces poor initial code requiring extensive correction. There is agreement that careful review is essential.

**Tags**: `#AI-assisted coding`, `#code quality`, `#software engineering`, `#LLM workflows`, `#code review`

---

<a id="item-2"></a>
## [California proposes exempting Linux from age-verification law](https://www.tomshardware.com/software/linux/california-moves-to-exempt-linux-from-its-upcoming-age-verification-law-after-backlash-over-forcing-operating-systems-to-collect-users-ages-amendment-proposed-by-the-same-lawmaker-who-wrote-the-original-law) ⭐️ 8.0/10

California has proposed an amendment to its age-verification law (AB 2273) to exempt Linux and other open-source operating systems from requiring age verification during account setup, following backlash from the open-source community. This exemption is significant because it prevents open-source operating systems from being burdened with costly and privacy-invasive age-verification mandates, which could have stifled innovation and adoption. It also sets a precedent for how internet regulation can accommodate open-source ecosystems. The amendment was proposed by the same lawmaker who authored the original law, and it specifically targets operating systems like Linux and SteamOS. The original law required age verification during OS account setup, which critics argued was technically infeasible for open-source distributions.

hackernews · rbanffy · May 25, 18:19 · [Discussion](https://news.ycombinator.com/item?id=48269961)

**Background**: California's Age-Appropriate Design Code Act (AB 2273) was signed into law in 2022 and took effect in July 2024, aiming to protect children's privacy online. It initially required all operating systems to verify user age during account setup, which raised concerns about privacy and feasibility for open-source projects. Similar debates have occurred in the EU with the Cyber Resilience Act, which also carved out exemptions for open-source software.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Social_media_age_verification_laws_in_the_United_States">Social media age verification laws in the United States - Wikipedia</a></li>
<li><a href="https://transcend.io/blog/age-appropriate-design-code-ab-2273">California Age Appropriate Design Code Act ( AB 2273 ): What You...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Cyber_Resilience_Act">Cyber Resilience Act - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a mix of relief and skepticism. Some users argue that the law was poorly drafted and that the exemption is a necessary fix, while others suspect the exemption may be a strategic move to deprive Linux developers of standing to challenge the law on First Amendment grounds. There is also broader criticism that such laws shift the burden from companies to consumers.

**Tags**: `#Linux`, `#age verification`, `#California law`, `#open source`, `#regulation`

---

<a id="item-3"></a>
## [CVE-2026-28952: macOS kernel bug found by Claude AI](https://support.apple.com/en-us/127115) ⭐️ 8.0/10

A kernel vulnerability in Apple macOS 26.5 and other OS versions, tracked as CVE-2026-28952, was discovered using Anthropic's Claude AI and reported by Calif.io in collaboration with Anthropic Research. This marks a significant milestone in AI-assisted vulnerability discovery, demonstrating that AI can help find critical kernel bugs in widely used operating systems, potentially improving security but also raising concerns about dual-use risks. The vulnerability is an integer overflow in the macOS kernel that could allow an app to cause unexpected system termination. It affects macOS Tahoe 26.5, iOS 18.7.9, iPadOS 18.7.9, macOS Sequoia 15.7.7, and macOS Sonoma 14.8.7.

hackernews · dragonsenseiguy · May 25, 23:40 · [Discussion](https://news.ycombinator.com/item?id=48273169)

**Background**: Kernel vulnerabilities are critical because they can allow attackers to gain full control of a system. AI-assisted vulnerability discovery is an emerging field where large language models like Claude are used to analyze code and find security flaws. Apple has not yet deployed such internal tooling as extensively as Google, according to community observations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.vulncheck.com/blog/ai-assisted-vulnerability-discovery">The First CVE Wave: Signs That AI - Assisted Vulnerability Discovery ...</a></li>
<li><a href="https://cyberunit.com/insights/ai-vulnerability-discovery-opus-46-zero-day-findings/">AI -Powered Vulnerability Discovery : What Opus... | Cyber Unit</a></li>

</ul>
</details>

**Discussion**: Community members noted that the bug is unrelated to a recent MIE attack and that Apple's update size (13.2 GB for a 64GB device) is a concern. Some praised the AI-assisted discovery but questioned Apple's internal security tooling compared to Google's.

**Tags**: `#security`, `#macOS`, `#AI-assisted vulnerability discovery`, `#kernel`, `#Apple`

---

<a id="item-4"></a>
## [AI Accelerates Quantum Threat to Crypto, Experts Warn](https://www.coindesk.com/tech/2026/05/24/ai-is-speeding-up-the-quantum-threat-to-crypto-security-experts-warn) ⭐️ 8.0/10

Security experts warn that advancements in artificial intelligence are accelerating the timeline for quantum computers to break current cryptographic standards, posing an urgent threat to cryptocurrency and data security. This matters because the convergence of AI and quantum computing could bring forward the 'Q-Day' when widely used encryption (e.g., RSA, ECDSA) becomes vulnerable, potentially compromising the security of cryptocurrencies, financial transactions, and all digital communications. The article highlights that AI can optimize quantum error correction and algorithm design, reducing the number of qubits needed to run Shor's algorithm effectively. Current estimates suggest a quantum computer with millions of qubits could break RSA-2048, but AI may lower that threshold.

rss · CoinDesk · May 24, 14:00

**Background**: Quantum computers leverage qubits to perform calculations that are infeasible for classical computers. Shor's algorithm, a quantum algorithm, can efficiently factor large integers and solve discrete logarithms, threatening public-key cryptography like RSA and ECC. Post-quantum cryptography (PQC) aims to develop algorithms resistant to quantum attacks; NIST has already released initial PQC standards in 2024.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography</a></li>
<li><a href="https://en.wikipedia.org/wiki/Shor's_algorithm">Shor's algorithm</a></li>
<li><a href="https://www.justsecurity.org/113733/quantum-computing-crytopography/">Military Response: Quantum Computing Threat to Cryptography</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#cryptography`, `#AI`, `#cybersecurity`, `#blockchain`

---

<a id="item-5"></a>
## [George Hotz Warns AI Coding Agents Create Undetectable Slop](https://decrypt.co/368964/george-hotz-vibe-coding-ai-slop-warning) ⭐️ 8.0/10

George Hotz, the famed hacker known for jailbreaking iPhones and Sony PlayStation, warned that AI coding agents produce undetectable low-quality code after six months of testing on real projects. This warning from a respected security and AI figure challenges the current hype around AI coding agents, suggesting that large organizations may face hidden costs and security risks from accumulating undetectable bugs. Hotz found that AI coding agents deliver fast prototypes but fall apart on details, producing bugs that become increasingly harder to spot as codebases grow.

rss · Decrypt · May 25, 19:06

**Background**: AI coding agents are tools that use large language models (LLMs) to automatically generate or modify code. They have gained popularity for speeding up development, but critics argue they often produce 'slop'—code that works superficially but contains subtle errors. George Hotz is the founder of comma.ai and a well-known figure in both hacking and AI communities.

<details><summary>References</summary>
<ul>
<li><a href="https://the-decoder.com/george-hotz-says-coding-agents-will-be-one-of-the-most-costly-mistakes-in-software-development/">George Hotz says coding agents will be "one of the most costly..."</a></li>
<li><a href="https://digg.com/ai/19volbvw">George Hotz says AI coding agents bypass problem-solving by...</a></li>
<li><a href="https://www.creativeainews.com/blog/george-hotz-ai-agents-slop-eternal-sloptember-2026/">George Hotz : AI Agents Produce Eternal Slop</a></li>

</ul>
</details>

**Discussion**: The article did not include community comments, but the topic is likely to generate debate between AI proponents who emphasize productivity gains and skeptics who worry about code quality and maintainability.

**Tags**: `#AI`, `#software engineering`, `#code quality`, `#security`, `#George Hotz`

---

<a id="item-6"></a>
## [Pope Leo XIV's AI Encyclical Declares Data a Common Good](https://decrypt.co/368933/pope-leo-xiv-ai-encyclical-2026) ⭐️ 8.0/10

Pope Leo XIV released a 245-paragraph encyclical on artificial intelligence, declaring data a common good and rejecting the moral neutrality of technology, presented alongside Anthropic co-founder Christopher Olah. This marks the first papal encyclical specifically on AI, signaling a major religious authority's stance on AI ethics and data governance, which could influence global policy debates and public discourse. The encyclical was presented alongside Anthropic co-founder Christopher Olah, whose company is suing the Trump administration over military AI use, highlighting the intersection of religious ethics and legal battles.

rss · Decrypt · May 25, 15:02

**Background**: An encyclical is a formal papal letter addressing doctrine or important issues. Pope Leo XIV's document enters the growing debate on AI ethics, where questions of data ownership, algorithmic bias, and military use are contentious. Anthropic, co-founded by Olah, is an AI safety company known for its Claude models and legal action against military AI.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anthropic">Anthropic - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Christopher_Olah">Christopher Olah</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#religion and technology`, `#data governance`, `#Anthropic`, `#policy`

---

<a id="item-7"></a>
## [TrapDoor malware targets crypto dev environments](https://www.theblock.co/post/402458/researchers-flag-trapdoor-malware-campaign-targeting-crypto-developer-environments-including-aptos-sui-and-solana?utm_source=rss&utm_medium=rss) ⭐️ 8.0/10

Researchers have uncovered the TrapDoor malware campaign, which distributes credential-stealing malware through over 34 malicious packages across npm, PyPI, and Crates.io, targeting developer environments for blockchains like Aptos, Sui, and Solana. This supply chain attack poses a significant threat to crypto and DeFi developers, as compromised packages can lead to credential theft and unauthorized access to critical infrastructure, potentially causing financial losses and security breaches. The campaign spans more than 34 malicious packages and 384 versions, with attackers repeatedly pushing new updates to evade detection; it was discovered by Socket on Friday and reported on Sunday.

rss · The Block · May 25, 09:52

**Background**: Software supply chain attacks involve injecting malicious code into legitimate software packages hosted on public registries like npm, PyPI, and Crates.io. Developers unknowingly download these packages, which then execute malicious payloads, such as stealing credentials or installing backdoors. Crypto developer environments are particularly attractive targets because they often hold private keys and access to blockchain networks.

<details><summary>References</summary>
<ul>
<li><a href="https://thehackernews.com/2026/05/trapdoor-supply-chain-attack-spreads.html">TrapDoor Supply Chain Attack Spreads Credential-Stealing Malware via npm, PyPI, and CratesIO</a></li>
<li><a href="https://www.banklesstimes.com/articles/2026/05/25/crypto-and-ai-developers-hit-by-trapdoor-malware-supply-chain-attack/">Crypto and AI Developers Hit by TrapDoor Malware Supply Chain Attack | BanklessTimes</a></li>
<li><a href="https://www.tradingview.com/news/cointelegraph:e10ce1fa3094b:0-trapdoor-malware-targets-crypto-dev-tools-in-supply-chain-attack/">‘TrapDoor’ malware targets crypto dev tools in supply chain attack</a></li>

</ul>
</details>

**Tags**: `#malware`, `#supply chain security`, `#cryptocurrency`, `#npm`, `#PyPI`

---

<a id="item-8"></a>
## [How Shamir's Secret Sharing Works](https://ente.com/blog/how-shamirs-secret-sharing-works/) ⭐️ 7.0/10

A blog post from Ente provides a clear, accessible explanation of Shamir's Secret Sharing using polynomial interpolation, complete with a live demo and discussion of trade-offs. This technique is foundational in cryptography for securely distributing secrets, and the article helps demystify it for a broader audience, including potential use in DNS key management. Shamir's Secret Sharing uses polynomial interpolation to split a secret into n shares, requiring at least k shares to reconstruct it, achieving information-theoretic security.

hackernews · subract · May 25, 22:37 · [Discussion](https://news.ycombinator.com/item?id=48272715)

**Background**: Shamir's Secret Sharing (SSS) is a cryptographic threshold scheme developed by Adi Shamir in 1979. It divides a secret into parts (shares) such that the secret can only be reconstructed when a sufficient number of shares are combined. The scheme is based on the fact that a polynomial of degree k-1 is uniquely determined by k points.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Shamir's_secret_sharing">Shamir's secret sharing</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lagrange_polynomial">Lagrange polynomial - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised the explanation and discussed real-world applications, such as root DNS key management, and compared Shamir's scheme with Reed-Solomon error correction, noting trade-offs in security and payload handling.

**Tags**: `#cryptography`, `#secret sharing`, `#security`, `#tutorial`

---

<a id="item-9"></a>
## [Norway's 2 PB Huawei flash storage for sovereign LLM training](https://www.blocksandfiles.com/flash/2026/05/22/norways-2-petabytes-of-huawei-flash-storage-and-llm-training/5244910) ⭐️ 7.0/10

Norway's National Library (Nasjonalbiblioteket) is deploying 2 petabytes of Huawei flash storage and an HPE Cray Supercomputing EX system with 448 GPUs to train a sovereign Norwegian LLM, as announced at Huawei's ID Forum 2026 in Paris. This project highlights the growing trend of sovereign AI, where nations invest in independent AI infrastructure to preserve language, culture, and data control. It also underscores the challenges of training LLMs for smaller languages, as commercial providers often neglect them. The HPE Cray system, named Olivia, has 448 GPUs and 64,512 CPU cores, which some commenters consider insufficient for training a fully fledged LLM. The storage is Huawei's flash-based solution, providing 2 PB capacity for the massive datasets required.

hackernews · rbanffy · May 25, 19:37 · [Discussion](https://news.ycombinator.com/item?id=48270770)

**Background**: Sovereign AI refers to national efforts to develop independent AI capabilities, including infrastructure, data, and models, to reduce reliance on foreign providers. Norway's initiative is driven by the need for a Norwegian-language LLM that understands local history, news, and culture, which global English-centric models may miss. The National Library holds extensive Norwegian texts, making it a key data source.

<details><summary>References</summary>
<ul>
<li><a href="https://www.hpe.com/us/en/collaterals/collateral.a00094635enw.html">HPE Cray Supercomputing EX QuickSpecs | HPE</a></li>
<li><a href="https://en.wikipedia.org/wiki/Sovereign_AI_Fund">Sovereign AI Fund</a></li>
<li><a href="https://www.mckinsey.com/featured-insights/mckinsey-explainers/what-is-sovereign-ai">What is sovereign AI? | McKinsey</a></li>

</ul>
</details>

**Discussion**: Commenters debated the necessity of a sovereign LLM, with some questioning whether global models already cover Norwegian data. Others criticized the hardware as inadequate for full LLM training, suggesting a LoRA approach on an open-source model would be more practical. A Norwegian user praised the library's search interface, indicating strong local support for the project.

**Tags**: `#LLM`, `#sovereign AI`, `#storage`, `#HPC`, `#Norway`

---

<a id="item-10"></a>
## [Mullvad Rolls Out Mitigation for Exit IP Fingerprinting](https://mullvad.net/en/help/exit-ip-vpn-servers-mitigation-rollout) ⭐️ 7.0/10

Mullvad has begun rolling out a mitigation against exit IP fingerprinting attacks on its VPN servers, addressing a privacy vulnerability that could allow services to probabilistically correlate users across different VPN connections. This proactive response is significant for privacy-conscious users, as it closes a novel attack vector that could undermine the anonymity provided by VPNs. It also sets a positive example for the VPN industry in handling security vulnerabilities promptly. The mitigation is being deployed across Mullvad's server fleet, with testing already underway. The fix addresses the issue where exit IP addresses assigned to WireGuard connections could be used to fingerprint users.

hackernews · Cider9986 · May 25, 17:45 · [Discussion](https://news.ycombinator.com/item?id=48269580)

**Background**: Exit IP fingerprinting is a technique where an attacker observes the IP address assigned to a user's VPN connection and uses it to track the user across different sessions or servers. Mullvad's relatively small server pool (578 servers) made this attack more feasible. The vulnerability was disclosed by a researcher and confirmed by Mullvad earlier this month.

<details><summary>References</summary>
<ul>
<li><a href="https://cyberinsider.com/mullvad-vpn-exit-ip-patterns-could-enable-user-fingerprinting/">Mullvad VPN exit IP patterns could enable user fingerprinting</a></li>
<li><a href="https://www.techradar.com/vpn/vpn-services/mullvad-to-patch-vpn-fingerprinting-issue-to-stop-your-activity-from-being-tracked-across-servers">Mullvad to patch VPN fingerprinting issue to stop your... | TechRadar</a></li>

</ul>
</details>

**Discussion**: Community members expressed surprise and appreciation for Mullvad's prompt reaction, with one user noting it was refreshing to see a company act before bureaucracy sets in. Some users suggested additional privacy measures, such as using Mullvad Browser with its built-in proxies and random IP mode, while others pointed out that Asian servers were excluded from the initial rollout.

**Tags**: `#VPN`, `#privacy`, `#fingerprinting`, `#security`, `#Mullvad`

---

<a id="item-11"></a>
## [Programming book sales decline as online learning rises](https://unix.foo/posts/nobody-cracks-open-a-programming-book/) ⭐️ 7.0/10

A blog post and discussion highlight that programming book sales have significantly declined, with author Jon Bodner reporting monthly paperback sales of his O'Reilly book 'Learning Go' dropping from 367 in March 2025 to 124 in March 2026. This shift reflects a broader move from comprehensive, deep learning via books to quick, fragmented online resources, which may reduce depth of understanding but enables more complex languages to thrive. The decline removed a constraint on language complexity, as seen with Java's six-volume book set and C++'s bloated specification; online search and Stack Overflow now allow programmers to manage complexity without memorizing everything.

hackernews · zdw · May 25, 23:21 · [Discussion](https://news.ycombinator.com/item?id=48273030)

**Background**: Programming books were once the primary way to learn languages, providing structured, comprehensive knowledge. The rise of online tutorials, documentation, and Q&A sites like Stack Overflow has made learning faster and more accessible, but often shallower.

**Discussion**: Commenters note that while book sales are down, some still find deep learning from books essential, especially for complex languages like Rust. Others argue that online resources enable more complex languages but reduce the incentive for deep understanding.

**Tags**: `#programming education`, `#software engineering`, `#language complexity`, `#book sales`

---

<a id="item-12"></a>
## [Ethereum Foundation to Shrink, Sell Less ETH, Focus on CROPS](https://www.coindesk.com/web3/2026/05/25/buterin-says-ethereum-foundation-will-shrink-sell-less-eth-and-focus-on-crops) ⭐️ 7.0/10

Vitalik Buterin announced that the Ethereum Foundation will downsize its team, reduce ETH sales, and exclusively focus on Ethereum's CROPS properties—censorship resistance, open source, privacy, and security. This strategic shift signals a move toward long-term sustainability and decentralization, potentially reducing market sell pressure on ETH and redefining the Foundation's role in the ecosystem. The downsizing follows a 2025 restructuring that laid off some R&D staff, and the CROPS mandate was formally published in March 2026, treating these properties as non-negotiable for protocol decisions.

rss · CoinDesk · May 25, 15:51

**Background**: The Ethereum Foundation is a non-profit organization that supports the Ethereum network. CROPS is a framework introduced in 2025-2026 that defines core properties: censorship resistance, open source, privacy, and security. The Foundation has faced criticism for its spending and ETH sales, leading to this strategic pivot.

<details><summary>References</summary>
<ul>
<li><a href="https://www.mexc.com/news/939082">Ethereum News: Ethereum Foundation Reveals New ‘CROPS’ Mandate for Network’s Future | MEXC News</a></li>
<li><a href="https://unchainedcrypto.com/ethereum-foundation-publishes-crops-mandate-for-network-stewardship/">Ethereum Foundation Codifies Its Own Obsolescence in New Mandate - Unchained</a></li>
<li><a href="https://www.coindesk.com/tech/2025/06/02/ethereum-foundation-lays-off-some-staff-amid-rd-restructuring">Ethereum Foundation Lays Off Some Staff Amid R&D Restructuring</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#cryptocurrency`, `#blockchain`, `#Vitalik Buterin`

---

<a id="item-13"></a>
## [Perplexity Open-Sources Bumblebee Malware Scanner](https://decrypt.co/368944/perplexity-open-source-bumblebee-ai-scanner-mcp-infection-malware) ⭐️ 7.0/10

Perplexity has open-sourced Bumblebee, a read-only scanner that checks developer machines for compromised packages and AI tool configurations without executing any code. This tool addresses a critical gap in software supply-chain security by avoiding the risk of triggering malware during scanning, which is a common problem with traditional scanners that execute package install scripts. Bumblebee is designed as a read-only endpoint scanner that analyzes on-disk metadata of packages, extensions, and developer tools, and it is built to check exposure to known software supply-chain compromises.

rss · Decrypt · May 25, 17:08

**Background**: Software supply-chain attacks often spread through malicious packages that execute postinstall scripts when installed. Traditional scanners that invoke package managers like npm can inadvertently trigger these scripts, activating the malware. Bumblebee avoids this by never executing any code, instead relying on static analysis of metadata.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/perplexityai/bumblebee">GitHub - perplexityai/bumblebee: Read-only developer endpoint scanner for on-disk package, extension, and developer-tool metadata, built to check exposure to known software supply-chain compromises. · GitHub</a></li>
<li><a href="https://www.perplexity.ai/hub/blog/perplexity-is-open-sourcing-bumblebee">Perplexity Is Open-Sourcing Bumblebee</a></li>
<li><a href="https://www.marktechpost.com/2026/05/23/perplexity-open-sources-bumblebee-a-read-only-supply-chain-scanner-for-developer-endpoints/">Perplexity Open-Sources Bumblebee: A Read-Only Supply-Chain Scanner for Developer Endpoints - MarkTechPost</a></li>

</ul>
</details>

**Tags**: `#security`, `#open-source`, `#malware`, `#supply chain`, `#AI`

---

<a id="item-14"></a>
## [NYT: CFTC Purged Staff Who Opposed Trump-Tied Crypto Firms](https://www.theblock.co/post/402442/nyt-investigation-alleges-cftc-purged-staff-who-questioned-trump-tied-crypto-firms?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

A New York Times investigation alleges that the Commodity Futures Trading Commission (CFTC) removed staff who objected to approvals for three crypto firms with ties to President Trump, and the officials who intervened later took jobs at MoonPay and Gemini Titan. This raises serious concerns about political influence undermining regulatory integrity in the crypto space, potentially eroding public trust in market oversight and fair enforcement. The three firms that won approvals over staff objections are not named in the summary, but the officials involved have since taken jobs at MoonPay and Gemini Titan, both crypto firms with ties to the Trump administration.

rss · The Block · May 24, 20:42

**Background**: The CFTC is a U.S. federal agency that regulates derivatives markets, including certain crypto assets. MoonPay is a fintech company that facilitates crypto purchases, while Gemini Titan is a CFTC-regulated exchange for prediction markets, founded by the Winklevoss twins. The NYT investigation suggests that political pressure may have influenced regulatory decisions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MoonPay">MoonPay - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Gemini_(company)">Gemini (cryptocurrency exchange) - Wikipedia</a></li>
<li><a href="https://www.coindesk.com/markets/2025/12/11/gemini-becomes-first-crypto-exchange-approved-by-cftc-to-offer-u-s-prediction-markets">$GEMI News: Winklevoss-Backed Gemini Wins CFTC Approval to Offer U.S. Prediction Markets</a></li>

</ul>
</details>

**Tags**: `#crypto regulation`, `#CFTC`, `#political influence`, `#crypto firms`

---

<a id="item-15"></a>
## [StablR's EURR and USDR Depeg After $13.5M Multisig Exploit](https://www.theblock.co/post/402429/stablrs-eurr-and-usdr-depeg-after-attacker-mints-13-5-million-in-unbacked-tokens-through-multisig-exploit?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

An attacker exploited a 1-of-3 multisig configuration on StablR's minting contract to mint $13.5 million in unbacked EURR and USDR tokens, causing EURR to drop to $0.85 and USDR to $0.40 after the attacker dumped roughly $10.4 million face value on decentralized exchanges. This incident highlights critical security risks in poorly configured multisig governance systems, especially for stablecoin issuers, and demonstrates how a single compromised key can lead to massive depegging and financial losses, undermining trust in DeFi protocols. The minting multisig had a 1-of-3 threshold, meaning a single compromised key was sufficient for full control. The attacker added themselves as an owner, minted unbacked tokens, and profited an estimated $2.8 million from the exploit.

rss · The Block · May 24, 15:08

**Background**: Stablecoins are cryptocurrencies designed to maintain a fixed value relative to a reference asset, such as the US dollar or euro. A depeg occurs when the market price deviates significantly from this target, often due to a loss of confidence or a security breach. Multisig (multi-signature) wallets require multiple private keys to authorize transactions, but a low threshold like 1-of-3 reduces security.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cryptotimes.io/2026/05/25/can-mica-prevent-multisig-hacks-stablrs-10m-exploit-exposes-the-gap/">Can MiCA Prevent Multisig Hacks? StablR's $10M Exploit Exposes the Gap</a></li>
<li><a href="https://coinpedia.org/crypto-live-news/stablr-stablecoins-depeg-after-multisig-exploit-mints-millions-in-fake-tokens/">StablR Stablecoins Depeg After Multisig Exploit Mints Millions in Fake Tokens</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#stablecoin`, `#exploit`, `#cryptocurrency`

---

<a id="item-16"></a>
## [Walking Boosts Creativity More Than Sitting, Study Finds](https://www.apa.org/news/press/releases/2014/04/creativity-walk) ⭐️ 6.0/10

A 2014 study published by the American Psychological Association found that walking significantly improves creative thinking compared to sitting, with effects lasting even after returning to a seated position. This finding provides empirical support for a common intuition and offers a simple, accessible method for boosting creativity in work and daily life, relevant to professionals in creative fields and anyone seeking cognitive enhancement. The study involved four experiments comparing participants' creativity while walking versus sitting, using tasks like generating alternative uses for objects. Walking on a treadmill indoors produced similar benefits to walking outdoors.

hackernews · bilsbie · May 25, 22:30 · [Discussion](https://news.ycombinator.com/item?id=48272670)

**Background**: Creativity is often associated with divergent thinking, the ability to generate many ideas. Previous research had linked physical activity to cognitive benefits, but this study specifically isolated the effect of walking on creative ideation.

**Discussion**: Commenters shared personal anecdotes confirming the finding, noting that walking, showering, sleeping, and biking help with problem-solving and code debugging. Some emphasized the need for distraction-free environments during such activities.

**Tags**: `#creativity`, `#psychology`, `#productivity`, `#walking`

---

<a id="item-17"></a>
## [What We Lost When We Stopped Letting Kids Leave the Front Yard](https://stevemagness.substack.com/p/the-cost-of-safetyism) ⭐️ 6.0/10

A Substack article argues that the decline in children's independent mobility is primarily due to urban design, reduced community, and traffic dangers, not stranger danger. This matters because it challenges common safety narratives and highlights how urban planning and social changes affect child development and community cohesion. The article cites factors like fewer front-yard social spaces, longer distances to destinations, and increased traffic from larger vehicles as key barriers to children's freedom.

hackernews · obscurette · May 25, 14:29 · [Discussion](https://news.ycombinator.com/item?id=48267290)

**Background**: In past decades, children commonly played outside and walked to school independently. Over time, fears of abduction and traffic led to more supervised, indoor childhoods. This shift has been linked to reduced physical activity and social skills.

**Discussion**: Commenters largely agree with the article, sharing personal experiences of lost independence and noting that traffic danger, especially from SUVs and pickup trucks, is a major concern. Some also point to the lack of destinations and community spaces as key factors.

**Tags**: `#urban planning`, `#sociology`, `#child development`, `#community`, `#safety`

---

<a id="item-18"></a>
## [Crypto rails become default payment layer for AI agents](https://www.coindesk.com/business/2026/05/21/crypto-rails-are-becoming-the-default-payment-layer-for-ai-agents-report-says) ⭐️ 6.0/10

A report from CoinDesk claims that cryptocurrency payment rails are becoming the default payment method for AI agents, enabling automated, trustless transactions between autonomous software entities. This trend could revolutionize machine-to-machine payments, reducing friction and costs for AI agents performing tasks like booking travel or purchasing services, and may accelerate the integration of crypto into mainstream commerce. The report highlights that crypto rails offer lower fees, faster settlement, and global accessibility compared to traditional payment systems, making them ideal for AI agents that operate 24/7 across borders.

rss · CoinDesk · May 24, 13:00

**Background**: Payment rails are the infrastructure that moves money between parties. Traditional rails like ACH and credit cards are slow or costly for automated microtransactions. Crypto rails, especially stablecoins on blockchain networks, enable instant, low-cost transfers without intermediaries, which is critical for AI agents that need to make frequent small payments autonomously.

<details><summary>References</summary>
<ul>
<li><a href="https://plaid.com/resources/payments/payment-rails/">What are payment rails and how are they evolving? | Plaid</a></li>
<li><a href="https://stripe.com/resources/more/what-are-payment-rails">What are payment rails? A guide | Stripe</a></li>
<li><a href="https://info.arkm.com/research/payment-rails-guide-crypto-money-moving-blockchain-stablecoin">A Guide to Crypto Payment Rails (2026)</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#AI agents`, `#payments`, `#blockchain`

---

<a id="item-19"></a>
## [Georgia to Launch Official Stablecoin with Tether](https://decrypt.co/368961/central-bank-georgia-tether-stablecoin) ⭐️ 6.0/10

Tether announced plans to issue a government-backed stablecoin called GELT, pegged to the Georgian lari, with the blessing of Georgia's central bank. This marks one of the first instances of a central bank endorsing a private stablecoin issuer for a national digital currency, potentially setting a precedent for other countries and boosting stablecoin adoption. The stablecoin, named GELT, will be a digital representation of the Georgian lari and is described as among the first joint efforts to place a national currency directly onto digital asset rails.

rss · Decrypt · May 25, 18:06

**Background**: Tether (USDT) is the world's largest stablecoin by market capitalization, pegged 1:1 to the US dollar. Georgia has been exploring central bank digital currencies (CBDCs), previously partnering with Ripple for a CBDC pilot. This new initiative with Tether represents a different approach, leveraging a private stablecoin issuer.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/368961/central-bank-georgia-tether-stablecoin">With Central Bank’s Blessing, Georgia Taps Tether for 'Official' Stablecoin - Decrypt</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tether_(cryptocurrency)">Tether (cryptocurrency) - Wikipedia</a></li>
<li><a href="https://www.ledgerinsights.com/georgia-central-bank-ripple-cbdc/">Georgia central bank names Ripple as CBDC technology partner - Ledger Insights - blockchain for enterprise</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#cryptocurrency`, `#regulation`, `#Tether`

---

<a id="item-20"></a>
## [EIP-8182 Proposed for Ethereum Hegota Upgrade](https://www.theblock.co/post/402464/facet-co-founder-pitches-eip-8182-private-transfers-for-inclusion-in-ethereums-hegota-upgrade?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Facet co-founder Tom Lehman has proposed EIP-8182 for inclusion in Ethereum's upcoming Hegota upgrade, which would enable native private transfers of ETH and ERC-20 tokens via a shielded-pool system contract. If accepted, EIP-8182 would bring privacy directly to Ethereum's base layer, reducing reliance on third-party mixers and potentially enhancing user privacy across the ecosystem. The shielded pool does not mandate a single spend-authorization method; each user can register their own, such as ECDSA signature or passkey. The Hegota upgrade is targeted for late 2026 and will also include Verkle Trees and FOCIL.

rss · The Block · May 25, 10:38

**Background**: Ethereum's Hegota upgrade is the next major network upgrade after Glamsterdam, expected in late 2026. It aims to introduce Verkle Trees to reduce node storage requirements and FOCIL to hardwire censorship resistance. EIP-8182 proposes a protocol-level privacy system, which is a departure from current privacy solutions that rely on layer-2 or external tools.

<details><summary>References</summary>
<ul>
<li><a href="https://eips.ethereum.org/EIPS/eip-8182">EIP-8182: Private ETH and ERC-20 Transfers</a></li>
<li><a href="https://www.coindesk.com/tech/2025/12/28/ethereum-s-hegota-upgrade-slated-for-late-2026-as-devs-accelerate-roadmap">ETH News: Ethereum’s ‘Hegota’ upgrade slated for late 2026 as devs accelerate roadmap</a></li>
<li><a href="https://phemex.com/blogs/ethereum-hegota-upgrade-explained">Ethereum Hegota Upgrade Explained | Verkle Trees, FOCIL, Smart Accounts | 2026</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#EIP`, `#privacy`, `#cryptocurrency`

---