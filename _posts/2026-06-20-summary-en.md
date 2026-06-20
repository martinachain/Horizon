---
layout: default
title: "Horizon Summary: 2026-06-20 (EN)"
date: 2026-06-20
lang: en
---

> From 80 items, 24 important content pieces were selected

---

1. [Project Valhalla's Value Types Arrive in JDK 28](#item-1) ⭐️ 9.0/10
2. [China's Z.AI GLM-5.2 Rivals Claude Opus on Huawei Chips](#item-2) ⭐️ 9.0/10
3. [ATProto Has No Instances: Dan Abramov Explains](#item-3) ⭐️ 8.0/10
4. [Norway Bans AI for Elementary School Students](#item-4) ⭐️ 8.0/10
5. [Real ID for Internet Traffic: A Critical Analysis](#item-5) ⭐️ 8.0/10
6. [EFF Argues PACER Court Records Should Be Free](#item-6) ⭐️ 8.0/10
7. [Hyundai Buys Full Control of Boston Dynamics](#item-7) ⭐️ 7.0/10
8. [Rethinking Junior Engineer Hiring: Beyond Task Completion](#item-8) ⭐️ 7.0/10
9. [Algorand unveils quantum resistance roadmap by 2028](#item-9) ⭐️ 7.0/10
10. [Midjourney Pivots from AI Art to Medical Imaging](#item-10) ⭐️ 7.0/10
11. [Perplexity's AI Agent Learns from Its Own Mistakes](#item-11) ⭐️ 7.0/10
12. [Ethereum core development funding crisis warning](#item-12) ⭐️ 7.0/10
13. [Morgan Stanley Files for ETH and SOL ETFs with Lowest Fees](#item-13) ⭐️ 7.0/10
14. [Bobby Prince, Composer for Doom and Wolfenstein 3D, Dies](#item-14) ⭐️ 6.0/10
15. [Schwab to Offer S&P 500 Event-Based Options](#item-15) ⭐️ 6.0/10
16. [Franklin Templeton Proposes ETFs Converting Dividends to Bitcoin](#item-16) ⭐️ 6.0/10
17. [Microsoft discovers malware hijacking crypto wallets via USB](#item-17) ⭐️ 6.0/10
18. [US Agencies Propose Stablecoin Customer ID Rules Like Banks](#item-18) ⭐️ 6.0/10
19. [Ethereum Foundation loses another key leader](#item-19) ⭐️ 6.0/10
20. [Anime Wallpaper Malware on Steam Steals Crypto and Accounts](#item-20) ⭐️ 6.0/10
21. [CME CEO Says Exchange Will Sue CFTC Over Bitcoin Perpetual Futures](#item-21) ⭐️ 6.0/10
22. [Base Beryl Upgrade and B20 Token Standard Launch June 25](#item-22) ⭐️ 6.0/10
23. [CLARITY Act: US Crypto Market Structure Bill Explained](#item-23) ⭐️ 6.0/10
24. [Fidelity Launches GENIUS-Aligned Money Market Fund for Stablecoin Issuers](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Project Valhalla's Value Types Arrive in JDK 28](https://www.jvm-weekly.com/p/project-valhalla-explained-how-a) ⭐️ 9.0/10

After a decade of development, Project Valhalla's value types (inline classes) are finally delivered in JDK 28, allowing the JVM to store values inline in arrays and fields without object headers or pointers. This is a paradigm shift for Java performance, enabling dense memory layouts and reducing garbage collection pressure, which benefits data-intensive applications like machine learning and big data. Value types are reference types but with inline storage; however, heap flattening is limited to objects with 64-bit or smaller representations, so a Point with two 32-bit ints (65 bits) cannot be fully flattened.

hackernews · philonoist · Jun 19, 06:35 · [Discussion](https://news.ycombinator.com/item?id=48595511)

**Background**: Project Valhalla is an OpenJDK effort to introduce value types to the JVM, aiming to combine the performance of primitives with the expressiveness of objects. Traditionally, Java objects are heap-allocated with headers and pointers, causing memory overhead and indirection. Value types eliminate this overhead by storing data inline.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Project_Valhalla_(Java_language)">Project Valhalla (Java language) - Wikipedia</a></li>
<li><a href="https://dev.to/adaumircosta/understanding-value-types-project-valhalla-faf">Understanding Value Types (Project Valhalla) - DEV Community</a></li>
<li><a href="https://medium.com/@vishalpriyadarshi/project-valhalla-bringing-value-types-and-performance-efficiency-to-java-83b85e00b791">💡Project Valhalla: Bringing Value Types and Performance Efficiency to Java 🚀 | by Vishal Priyadarshi | Medium</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (349 comments) shows high engagement, with some users appreciating the hard work while others debate trade-offs like null-safety and performance ceilings. A common sentiment is that many critics underestimate modern Java's capabilities.

**Tags**: `#Java`, `#JVM`, `#Project Valhalla`, `#performance`, `#value types`

---

<a id="item-2"></a>
## [China's Z.AI GLM-5.2 Rivals Claude Opus on Huawei Chips](https://decrypt.co/371613/china-z-ai-glm-5-2-model-rivals-claude-opus) ⭐️ 9.0/10

Z.AI released GLM-5.2, a large language model that achieves performance within 1% of Claude Opus 4.8 on long-horizon coding benchmarks, while running entirely on Huawei silicon and costing up to 82% less per token. This demonstrates that competitive AI models can be built without Nvidia chips, reducing reliance on Western hardware and potentially reshaping the global AI supply chain. It also signals China's growing capability in domestic AI chip ecosystems. GLM-5.2 supports a 1-million-token context window and is designed for long-horizon tasks. It is available on Hugging Face and Ollama, and can be used for migrating web projects to Mini Programs.

rss · Decrypt · Jun 18, 21:26

**Background**: Nvidia's high-end AI chips like H100 have been restricted for export to China, prompting Chinese firms to develop alternatives. Huawei's Ascend AI chips have emerged as a leading domestic option, though they lag in efficiency and performance. Z.AI (formerly Zhipu AI) is a prominent Chinese AI company known for its GLM series of models.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/GLM-5.2 · Hugging Face</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/huawei-expects-12-billion-in-ai-chip-revenue-this-year-as-nvidias-china-market-share-hits-zero">Huawei braces for $12 billion in AI chip revenue driven by homegrown AI model demand — Chinese fabs can barely keep up as Nvidia's market share craters within the region | Tom's Hardware</a></li>

</ul>
</details>

**Tags**: `#AI`, `#China`, `#LLM`, `#Huawei`, `#geopolitics`

---

<a id="item-3"></a>
## [ATProto Has No Instances: Dan Abramov Explains](https://overreacted.io/there-are-no-instances-in-atproto/) ⭐️ 8.0/10

Dan Abramov published a blog post explaining that ATProto, the protocol behind Bluesky, does not have 'instances' like Mastodon, using analogies to RSS and email to illustrate the architectural differences. This clarification addresses a common misconception in the decentralized social media space, helping developers and users understand the fundamental design differences between ATProto and ActivityPub, which affects how moderation, scalability, and user control are handled. In ATProto, the roles are split into Personal Data Servers (PDS), Relays, and AppViews, unlike ActivityPub's monolithic instances. This separation allows users to switch providers without losing data or social graph, and enables scalable indexing by third parties.

hackernews · danabramov · Jun 19, 15:10 · [Discussion](https://news.ycombinator.com/item?id=48599515)

**Background**: ATProto (AT Protocol) is a decentralized social networking protocol developed by Bluesky, designed to enable user portability and scalable federation. ActivityPub is the protocol used by Mastodon and other Fediverse platforms, where each server (instance) handles both user data and content delivery. The key difference is that ATProto separates data storage, indexing, and presentation into independent services, while ActivityPub combines them.

<details><summary>References</summary>
<ul>
<li><a href="https://atproto.com/guides/overview">Protocol Overview - AT Protocol</a></li>
<li><a href="https://fediversereport.com/a-conceptual-model-of-atproto-and-activitypub/">A conceptual model of ATProto and ActivityPub – The Fediverse Report</a></li>
<li><a href="https://en.wikipedia.org/wiki/AT_Protocol">AT Protocol - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion (207 comments) includes both praise for the clear explanation and criticism. Some commenters argue the RSS analogy is flawed because RSS doesn't depend on a central reader like Google Reader, while ATProto's Relays are expensive to run. Others appreciate the modular architecture but question how ATProto solves moderation problems that instances address via defederation.

**Tags**: `#ATProto`, `#ActivityPub`, `#decentralization`, `#protocol design`, `#Bluesky`

---

<a id="item-4"></a>
## [Norway Bans AI for Elementary School Students](https://www.reuters.com/technology/norway-imposes-near-ban-ai-elementary-school-2026-06-19/) ⭐️ 8.0/10

Norway's government announced a near-total ban on AI use for students aged 6-13, while allowing limited, supervised use for ages 14-16, effective from the 2026 school year. This policy sets a precedent for regulating AI in education, highlighting concerns about AI undermining foundational skills like reading, writing, and critical thinking in young children. The ban applies to grades 1-7 (ages 6-13), while grades 8-10 (ages 14-16) may use AI cautiously under teacher supervision; the government cited the need to protect children's cognitive development.

hackernews · ilreb · Jun 19, 16:03 · [Discussion](https://news.ycombinator.com/item?id=48600093)

**Background**: Generative AI tools like ChatGPT can produce human-like text, raising concerns in education about plagiarism and reduced effort in learning. Many educators argue that young children must first master basic literacy and numeracy before using AI, similar to the rationale for delaying calculator use.

**Discussion**: Comments largely support the ban, with users comparing AI to calculators and arguing that children need to develop thinking skills first. Some question how AI is currently used in classrooms, while others note the difficulty of enforcing such bans without increasing teacher workload.

**Tags**: `#AI policy`, `#education`, `#Norway`, `#generative AI`, `#children`

---

<a id="item-5"></a>
## [Real ID for Internet Traffic: A Critical Analysis](https://nochan.net/b/Internet-Crap/20230829-Think-Of-The-Children/) ⭐️ 8.0/10

A 2023 article on NoChan critically analyzes proposals to mandate real ID for all internet traffic, exploring technical, legal, and societal implications. This discussion is significant because mandatory identity verification could fundamentally alter internet freedom, privacy, and censorship dynamics, affecting all users and content platforms. The article references historical parallels like the Digital Imprimatur and discusses technical countermeasures such as underground relay networks and radio-based mesh networks.

hackernews · Bender · Jun 19, 20:19 · [Discussion](https://news.ycombinator.com/item?id=48602817)

**Background**: The REAL ID Act of 2005 standardized US driver's licenses for federal identification, but applying similar identity verification to internet traffic raises concerns about anonymity and free speech. Age-authentication mandates, as discussed in a 2025 New Yorker article, could shrink the internet for adults and disproportionately affect marginalized groups.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Real_ID_Act">REAL ID Act - Wikipedia</a></li>
<li><a href="https://news.ycombinator.com/item?id=48602817">Think of the children: How to force real ID for all internet traffic (2023) | Hacker News</a></li>
<li><a href="https://www.newyorker.com/culture/infinite-scroll/the-internet-wants-to-check-your-id">The Internet Wants to Check Your I.D. | The New Yorker</a></li>

</ul>
</details>

**Discussion**: Commenters propose extreme technical countermeasures like underground radio relay networks to bypass censorship, and draw parallels to KYC/AML regulations that shift responsibility and cause self-censorship. Some argue for simple router-based controls instead of government mandates.

**Tags**: `#internet governance`, `#privacy`, `#censorship`, `#identity verification`, `#networking`

---

<a id="item-6"></a>
## [EFF Argues PACER Court Records Should Be Free](https://www.eff.org/deeplinks/2026/06/court-records-should-be-free) ⭐️ 8.0/10

The Electronic Frontier Foundation (EFF) published an article arguing that PACER, the federal court records system, should be free to access, highlighting the financial barriers it creates for the public. This matters because PACER fees restrict public access to legal documents, undermining transparency and access to justice. Making records free would benefit journalists, researchers, and individuals involved in litigation. PACER charges $0.10 per page, with a maximum fee of $3.00 per document, but frequent users can incur significant costs. The EFF points out that the system generates far more revenue than its operating costs, suggesting the fees are excessive.

hackernews · hn_acker · Jun 19, 17:34 · [Discussion](https://news.ycombinator.com/item?id=48600946)

**Background**: PACER (Public Access to Court Electronic Records) is a system that provides online access to federal court documents. While the law requires public access, PACER charges per-page fees, which critics argue creates a barrier to justice. The EFF has long advocated for free access, and tools like CourtListener and RECAP help mitigate costs by sharing purchased documents.

<details><summary>References</summary>
<ul>
<li><a href="https://www.eff.org/about">About EFF | Electronic Frontier Foundation</a></li>
<li><a href="https://pacer.uscourts.gov/register-account">Register for an Account | PACER : Federal Court Records</a></li>

</ul>
</details>

**Discussion**: Commenters discussed the broader issue of government fees limiting access to rights, with one noting that state court fees can be even higher (e.g., $10 per page in Idaho). Another highlighted the value of CourtListener and RECAP in making documents freely available.

**Tags**: `#access to justice`, `#PACER`, `#public records`, `#legal technology`, `#public policy`

---

<a id="item-7"></a>
## [Hyundai Buys Full Control of Boston Dynamics](https://startupfortune.com/hyundai-takes-full-control-of-boston-dynamics-as-softbank-exits-for-325-million/) ⭐️ 7.0/10

Hyundai Motor Group exercised a put option to acquire the remaining stake in Boston Dynamics from SoftBank, completing full ownership of the robotics company. This acquisition positions Hyundai to lead in advanced robotics, potentially integrating humanoid and quadruped robots into manufacturing and logistics, while addressing South Korea's declining working-age population. Hyundai initially purchased an 80% stake in December 2020 for $880 million, valuing Boston Dynamics at $1.1 billion; the remaining 9% stake was acquired for $325 million, reflecting a lower valuation.

hackernews · ck2 · Jun 19, 16:28 · [Discussion](https://news.ycombinator.com/item?id=48600312)

**Background**: Boston Dynamics is known for advanced robots like Atlas (humanoid) and Spot (quadruped). Hyundai, a major automaker, aims to leverage robotics for manufacturing and beyond, similar to Tesla's approach.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Atlas_(robot)">Atlas ( robot ) - Wikipedia</a></li>
<li><a href="https://spectrum.ieee.org/hyundai-buys-boston-dynamics">Hyundai Buys Boston Dynamics for Nearly $1 Billion. - IEEE Spectrum</a></li>
<li><a href="https://www.hyundaimotorgroup.com/en/story/CONT0000000000001671">[Op-ed] Robots Jump into the Mobility Industry | Hyundai Motor Group</a></li>

</ul>
</details>

**Discussion**: Commenters debated the value of humanoid vs. purpose-built robots, with some questioning the practicality of humanoid forms for manufacturing. Others linked the acquisition to South Korea's demographic challenges and potential for general-purpose robotics.

**Tags**: `#robotics`, `#acquisition`, `#Hyundai`, `#Boston Dynamics`, `#automation`

---

<a id="item-8"></a>
## [Rethinking Junior Engineer Hiring: Beyond Task Completion](https://newsletter.kentbeck.com/p/hey-n00b-we-didnt-hire-you-to-complete) ⭐️ 7.0/10

Kent Beck argues that companies should hire junior engineers not merely to complete tasks, but to develop them into high-impact contributors over time. This perspective challenges the prevailing task-oriented view of junior hiring, prompting a debate on career mobility, LLM impact, and company culture in software engineering. Beck categorizes junior engineers into types A, B, and C based on their impact and growth potential, emphasizing that even B-level juniors can become valuable with proper mentorship.

hackernews · rrvsh · Jun 20, 00:11 · [Discussion](https://news.ycombinator.com/item?id=48604851)

**Background**: In many tech companies, junior engineers are often hired to handle lower-complexity tasks, with the expectation of immediate productivity. However, Beck suggests that this short-term view overlooks the long-term investment in talent development, which can yield higher returns.

**Discussion**: Comments are mixed: some agree with Beck's developmental view, while others argue that companies primarily hire juniors for junior-level tasks. Critics also note that the article's tone can come across as condescending.

**Tags**: `#software engineering`, `#career development`, `#hiring`, `#engineering culture`

---

<a id="item-9"></a>
## [Algorand unveils quantum resistance roadmap by 2028](https://www.coindesk.com/tech/2026/06/18/algorand-unveils-post-quantum-roadmap-to-secure-blockchain-by-2027) ⭐️ 7.0/10

Algorand has announced a roadmap to achieve post-quantum security for its blockchain by 2028, transitioning its cryptographic primitives to quantum-resistant algorithms. This is significant because quantum computers threaten to break current public-key cryptography, and Algorand's proactive roadmap sets a precedent for blockchain security, potentially influencing other networks to follow suit. The roadmap likely involves integrating NIST-standardized post-quantum algorithms, such as CRYSTALS-Kyber and CRYSTALS-Dilithium, into Algorand's protocol, with phased upgrades over the next two years.

rss · CoinDesk · Jun 18, 14:00

**Background**: Post-quantum cryptography (PQC) refers to cryptographic algorithms designed to be secure against attacks from quantum computers. Current public-key systems like RSA and ECDSA rely on mathematical problems that quantum computers could solve efficiently using Shor's algorithm. In 2024, NIST released the first three PQC standards, providing a foundation for migration.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography</a></li>
<li><a href="https://en.wikipedia.org/wiki/Algorand">Algorand - Wikipedia</a></li>
<li><a href="https://csrc.nist.gov/projects/post-quantum-cryptography">Post - Quantum Cryptography | CSRC</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#quantum computing`, `#cryptography`, `#Algorand`, `#post-quantum`

---

<a id="item-10"></a>
## [Midjourney Pivots from AI Art to Medical Imaging](https://decrypt.co/371606/midjourney-pivots-ai-images-medical-imaging-build-better-mri) ⭐️ 7.0/10

Midjourney, known for its AI image generation, is developing a full-body imaging system that combines ultrasound technology with AI to potentially serve as an alternative to MRI. This pivot could democratize medical imaging by offering a lower-cost, portable alternative to MRI, potentially expanding access to diagnostic imaging in underserved regions. The system uses ultrasound tomography, which can image soft tissues and bones, and AI to enhance image quality and interpretation. However, details on development timeline and clinical validation remain sparse.

rss · Decrypt · Jun 18, 21:18

**Background**: Midjourney is a leading AI image generation company. Ultrasound is a safe, low-cost imaging modality, but traditional ultrasound has limited field of view. Full-body ultrasound tomography is an emerging technique that can capture whole-body images. AI can help reconstruct and interpret these images, potentially matching MRI quality.

<details><summary>References</summary>
<ul>
<li><a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC11275691/">Whole-Body Human Ultrasound Tomography - PMC - NIH</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1076633223000338">Whole-Body Imaging Using Low Frequency Transmission Ultrasound</a></li>
<li><a href="https://www.hertzfoundation.org/impact-stories/the-first-handheld-whole-body-ultrasound-system/">The First Handheld Whole-body Ultrasound System - Hertz Foundation</a></li>

</ul>
</details>

**Tags**: `#AI`, `#medical imaging`, `#Midjourney`, `#ultrasound`, `#healthcare`

---

<a id="item-11"></a>
## [Perplexity's AI Agent Learns from Its Own Mistakes](https://decrypt.co/371584/perplexity-ai-agent-brain) ⭐️ 7.0/10

Perplexity has introduced 'Brain', a self-improving memory layer for its AI agent that tracks past actions, successes, and failures, then uses that information overnight to optimize future tasks, making them faster and cheaper. This development marks a shift from user-focused memory to agent-focused memory, potentially reducing operational costs and improving efficiency for AI agents, which could accelerate adoption in enterprise automation. Brain builds an 'LLM wiki' — a tidy, AI-readable summary of the agent's work patterns — that gets loaded before each new task, enabling continuous learning without manual intervention.

rss · Decrypt · Jun 18, 19:47

**Background**: Most AI memory systems focus on remembering user preferences, but Perplexity's Brain remembers the agent's own actions and outcomes. This is similar to Mem0, a universal memory layer for AI agents that also provides self-improving memory. By learning from past mistakes, the agent can avoid repeating errors and optimize its workflow.

<details><summary>References</summary>
<ul>
<li><a href="https://findskill.ai/blog/perplexity-brain/">Perplexity Brain Learns Your Work Overnight ($200/mo) | FindSkill. ai ...</a></li>
<li><a href="https://www.marktechpost.com/2026/06/18/perplexity-launches-brain/">Perplexity Launches Brain , a Self-Improving Memory... - MarkTechPost</a></li>
<li><a href="https://perplexityaimagazine.com/ai-news/perplexity-brain-memory-system/">Perplexity Brain : Self-Improving AI Memory System 2026</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#self-improving systems`, `#memory layer`, `#Perplexity`

---

<a id="item-12"></a>
## [Ethereum core development funding crisis warning](https://www.theblock.co/post/405404/ethereum-could-face-core-development-funding-crisis-within-nine-months-says-former-ef-contributor?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Former Ethereum Foundation contributor VanEpps warned that Ethereum could face a core development funding crisis within 3 to 9 months after the expiration of the CIP (Core Improvement Proposal) funding mechanism. This warning highlights a potential existential threat to Ethereum's core development, which could slow protocol upgrades and innovation, affecting the entire Ethereum ecosystem and its users. The warning specifically cites the expiration of CIP as the trigger, with a timeline of 3-9 months for the crisis to materialize. VanEpps is a former EF contributor, lending credibility to the concern.

rss · The Block · Jun 19, 10:11

**Background**: The Ethereum Foundation (EF) has historically funded core development through grants and the CIP mechanism. In mid-2025, the EF shifted from open grant applications to a more proactive, needs-driven funding model. The CIP expiration may leave a funding gap for critical protocol work.

<details><summary>References</summary>
<ul>
<li><a href="https://gitcoin.co/apps/ethereum-foundation-esp">Ethereum Foundation ESP | Gitcoin</a></li>
<li><a href="https://www.linkedin.com/pulse/how-get-ethereum-foundation-funding-after-grant-njfnf">How to Get Ethereum Foundation Funding After the Grant Pause</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#funding`, `#blockchain`, `#development`

---

<a id="item-13"></a>
## [Morgan Stanley Files for ETH and SOL ETFs with Lowest Fees](https://www.theblock.co/post/405362/morgan-stanley-eth-sol-etf-amendments?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Morgan Stanley has filed amendments for spot Ethereum (ETH) and Solana (SOL) exchange-traded funds (ETFs), revealing the lowest fee structures in the market and indicating active engagement with the SEC. This move by a major financial institution signals growing mainstream adoption of crypto ETFs and could pressure competitors to lower fees, benefiting investors and accelerating regulatory progress. The amendments reflect ongoing communication with the SEC, suggesting the launch process is advancing. Specific fee percentages were not disclosed in the provided content, but they are described as the lowest in the market.

rss · The Block · Jun 19, 02:54

**Background**: Spot crypto ETFs are investment funds that hold the actual cryptocurrency (e.g., ETH or SOL) and trade on stock exchanges, offering investors exposure without directly owning the asset. The SEC has historically been cautious about approving such products, but recent approvals for Bitcoin ETFs have opened the door for other cryptocurrencies.

**Tags**: `#crypto`, `#ETFs`, `#finance`, `#Morgan Stanley`, `#regulation`

---

<a id="item-14"></a>
## [Bobby Prince, Composer for Doom and Wolfenstein 3D, Dies](https://www.legacy.com/legacy/robert-bobby-prince-lll) ⭐️ 6.0/10

Bobby Prince, the legendary composer behind the iconic soundtracks of Doom, Wolfenstein 3D, and Duke Nukem 3D, has passed away. His death was announced via an obituary on Legacy.com. Prince's music defined the atmosphere of early first-person shooters and influenced a generation of game composers. His passing marks the loss of a pioneer whose work remains beloved by retro gaming enthusiasts. Prince composed the soundtracks for Doom, Wolfenstein 3D, and Duke Nukem 3D, and also contributed sound effects for Doom. His music for Doom was heavily inspired by heavy metal bands like Pantera and Slayer.

hackernews · pgrote · Jun 19, 19:35 · [Discussion](https://news.ycombinator.com/item?id=48602352)

**Background**: Bobby Prince was a key figure in the golden age of PC gaming, known for his work at id Software and 3D Realms. His compositions used MIDI files to create memorable, atmospheric tracks that enhanced gameplay. The Doom soundtrack, in particular, is considered a classic and has been widely praised for its intensity and fittingness.

**Discussion**: Community comments express deep sadness and gratitude, with many sharing personal memories of how Prince's music influenced them. Commenters highlight the immersive quality of his work and note that he also created sound effects for Doom, adding to his legacy.

**Tags**: `#gaming`, `#music`, `#obituary`, `#retro gaming`

---

<a id="item-15"></a>
## [Schwab to Offer S&P 500 Event-Based Options](https://www.coindesk.com/markets/2026/06/19/schwab-to-join-prediction-markets-race-with-s-and-p-500-event-based-options-wsj) ⭐️ 6.0/10

Charles Schwab plans to launch event-based options tied to the S&P 500, entering the prediction markets space as reported by the Wall Street Journal. This move by a major brokerage could legitimize prediction markets in traditional finance, offering retail investors a regulated way to bet on economic events. Event-based options are binary options that pay out based on whether a specific event occurs, such as the S&P 500 reaching a certain level by a date. Schwab's product would be regulated by the SEC, unlike unregulated crypto-based prediction markets.

rss · CoinDesk · Jun 19, 17:51

**Background**: Prediction markets are exchange-traded markets where participants trade contracts whose payoffs depend on unknown future outcomes, with prices reflecting the crowd's probability estimate. Traditional examples include political betting markets, while newer platforms like Polymarket use blockchain technology. Schwab's entry bridges traditional options trading with event-based speculation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prediction_market">Prediction market</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#finance`, `#options trading`, `#S&P 500`

---

<a id="item-16"></a>
## [Franklin Templeton Proposes ETFs Converting Dividends to Bitcoin](https://www.coindesk.com/daybook-us/2026/06/19/franklin-templeton-proposes-new-funds-that-turn-corporate-dividends-into-bitcoin) ⭐️ 6.0/10

Franklin Templeton has filed for two new ETFs that would reinvest dividends from U.S. stocks into Bitcoin, with an expected effective date as early as September 1, 2026. This innovation bridges traditional finance and cryptocurrency, offering investors a novel way to gain Bitcoin exposure through dividend-paying stocks, potentially attracting more institutional capital to crypto. The funds will hold approximately 95% stocks and 5% Bitcoin, with a 20% cap on Bitcoin allocation, tracking the VettaFi US Large-Cap 500 Bitcoin DRIP and VettaFi US Innovation 100 Bitcoin DRIP indices.

rss · CoinDesk · Jun 19, 11:27

**Background**: A dividend reinvestment plan (DRIP) automatically uses cash dividends to purchase more shares of the stock. Franklin Templeton's proposed ETFs adapt this concept by reinvesting dividends into Bitcoin instead of additional shares, creating a hybrid product that combines equity income with crypto exposure.

<details><summary>References</summary>
<ul>
<li><a href="https://bitcoinfoundation.org/news/crypto-etfs-news/drip-etf-bitcoin/">DRIP ETFs : Franklin Templeton Turns Dividends Into Bitcoin</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#ETFs`, `#bitcoin`, `#finance`

---

<a id="item-17"></a>
## [Microsoft discovers malware hijacking crypto wallets via USB](https://www.coindesk.com/tech/2026/06/19/microsoft-found-malware-that-hijacks-crypto-wallets-and-spreads-through-usb-sticks) ⭐️ 6.0/10

Microsoft has identified a new malware strain that hijacks cryptocurrency wallets and spreads through USB drives, as reported by CoinDesk on June 19, 2026. This discovery highlights a growing threat to cryptocurrency users, as the USB propagation method can lead to rapid, offline spread in shared environments, potentially causing widespread financial losses. The malware likely uses clipboard hijacking techniques to replace copied wallet addresses with attacker-controlled ones, and its USB spread mechanism allows it to infect air-gapped systems.

rss · CoinDesk · Jun 19, 08:48

**Background**: Clipboard hijacking malware monitors the clipboard for copied cryptocurrency addresses and swaps them with the attacker's address, causing users to send funds to the wrong destination. USB-based malware can spread when infected drives are plugged into other computers, often without user awareness.

<details><summary>References</summary>
<ul>
<li><a href="https://cncintel.com/clipboard-hijacking/">Clipboard Hijacking Malware Removal - CNC Intelligence</a></li>
<li><a href="https://www.howtogeek.com/797290/how-usb-drives-can-be-a-danger-to-your-computer/">How USB Drives Can Be a Danger to Your Computer</a></li>

</ul>
</details>

**Tags**: `#malware`, `#cryptocurrency`, `#security`, `#USB`

---

<a id="item-18"></a>
## [US Agencies Propose Stablecoin Customer ID Rules Like Banks](https://www.coindesk.com/policy/2026/06/18/u-s-agencies-seek-stablecoin-customer-id-rules-akin-to-banks-in-new-genius-act-rule) ⭐️ 6.0/10

U.S. federal agencies, including FinCEN, OCC, the Federal Reserve, FDIC, and NCUA, jointly proposed a rule requiring stablecoin issuers to implement customer identification programs (CIP) similar to those of traditional banks under the GENIUS Act. This proposal closes a regulatory gap by applying bank-like KYC/AML standards to stablecoin issuers, potentially increasing compliance costs but also enhancing legitimacy and trust in the stablecoin ecosystem. Issuers would need to collect customer names, addresses, birth dates, and government-issued ID numbers. The rule is part of the GENIUS Act, which takes effect 18 months after enactment or 120 days after final regulations are issued.

rss · CoinDesk · Jun 18, 17:17

**Background**: The GENIUS Act is the first U.S. federal law creating a comprehensive regulatory framework for payment stablecoins—digital tokens pegged to monetary value. Stablecoins have grown rapidly but faced inconsistent state-level oversight, prompting federal action to align them with traditional banking safeguards.

<details><summary>References</summary>
<ul>
<li><a href="https://www.lw.com/en/insights/the-genius-act-of-2025-stablecoin-legislation-adopted-in-the-us">The GENIUS Act of 2025 Stablecoin Legislation Adopted in the US</a></li>
<li><a href="https://www.ccn.com/news/crypto/us-regulators-stablecoin-customer-verification-rules-genius-act/">US Regulators Propose New Customer Verification Rules for...</a></li>
<li><a href="https://blockonomi.com/fed-targets-stablecoin-loopholes-with-customer-id-proposal/">Fed Targets Stablecoin Loopholes With Customer ID... - Blockonomi</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#regulation`, `#crypto policy`, `#GENIUS Act`

---

<a id="item-19"></a>
## [Ethereum Foundation loses another key leader](https://www.coindesk.com/tech/2026/06/18/ethereum-foundation-loses-another-key-leader-as-co-executive-director-hsiao-wei-wang-resigns) ⭐️ 6.0/10

Hsiao-Wei Wang, co-executive director of the Ethereum Foundation, has resigned, marking another high-profile departure in a recent wave of leadership exits. This departure could raise concerns about leadership stability at the Ethereum Foundation, potentially affecting the strategic direction and governance of the Ethereum ecosystem. Wang's resignation follows the earlier departure of other key figures, though the specific reasons for her exit have not been disclosed. The Ethereum Foundation has not yet announced a replacement.

rss · CoinDesk · Jun 18, 15:41

**Background**: The Ethereum Foundation is a non-profit organization that supports the development of the Ethereum blockchain. Co-executive directors oversee operations and strategy alongside other leaders. Recent leadership changes have drawn attention to the foundation's internal dynamics.

**Tags**: `#Ethereum`, `#blockchain`, `#leadership`, `#cryptocurrency`

---

<a id="item-20"></a>
## [Anime Wallpaper Malware on Steam Steals Crypto and Accounts](https://decrypt.co/371632/anime-girls-steal-crypto-wallpaper-malware-targets-steam-gamers) ⭐️ 6.0/10

Researchers discovered malware disguised as anime wallpaper on Steam Workshop for Wallpaper Engine that steals cryptocurrency and hijacks accounts. The malicious packages have been downloaded tens of thousands of times since at least late 2025. This highlights a growing trend of malware distribution through legitimate platforms like Steam, putting millions of gamers at risk. The attack exploits user trust in popular apps and can lead to significant financial and account security losses. The malware includes infostealers, backdoors, and account-hijacking capabilities, spreading itself by hijacking Steam accounts. Wallpaper Engine is a $4.99 live wallpaper tool with 93,000–114,000 concurrent users and nearly a million reviews.

rss · Decrypt · Jun 19, 14:39

**Background**: Wallpaper Engine is a popular Steam application that allows users to create and share animated wallpapers via the Steam Workshop. Infostealer malware specializes in stealing sensitive information like passwords, cryptocurrency wallets, and session tokens. Attackers often abuse trusted platforms to bypass security measures.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tomshardware.com/tech-industry/cyber-security/kaspersky-finds-malware-hidden-in-steam-wallpapers-that-hijacks-accounts-to-spread-itself">Kaspersky finds malware hidden in Steam Wallpaper Engine that...</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/steam-workshop-abused-to-spread-malware-via-wallpaper-engine-app/">Steam Workshop abused to spread malware via Wallpaper Engine app</a></li>
<li><a href="https://steamcommunity.com/app/431960/discussions/2/569289424252266099/">Malware in wallpapers ? :: Wallpaper Engine General Discussions</a></li>

</ul>
</details>

**Tags**: `#malware`, `#cryptocurrency`, `#steam`, `#security`, `#infostealer`

---

<a id="item-21"></a>
## [CME CEO Says Exchange Will Sue CFTC Over Bitcoin Perpetual Futures](https://decrypt.co/371514/cme-to-sue-cftc-over-bitcoin-perpetual-futures-approval-ceo) ⭐️ 6.0/10

CME Group CEO Terry Duffy announced that the exchange will file a lawsuit against the CFTC on Thursday, arguing that Bitcoin perpetual futures are actually swaps under the Dodd-Frank Act and should not have been approved. This lawsuit could reshape the regulatory landscape for crypto derivatives in the U.S., potentially forcing the CFTC to reconsider its classification of perpetual futures and impacting how exchanges offer these products. Perpetual futures are a type of derivative that never expires, unlike traditional futures contracts. Duffy claims they function like swaps and thus fall under CFTC's swap regulations, which require different compliance measures.

rss · Decrypt · Jun 18, 11:20

**Background**: The Dodd-Frank Act, enacted after the 2008 financial crisis, gave the CFTC authority to regulate swaps to increase transparency and reduce risk. Bitcoin perpetual futures have become popular on offshore exchanges but face regulatory uncertainty in the U.S. The CFTC has previously approved some Bitcoin derivatives, but the classification of perpetual futures remains contested.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cftc.gov/LawRegulation/DoddFrankAct/index.htm">Dodd - Frank Act | CFTC</a></li>
<li><a href="https://www.investopedia.com/terms/d/dodd-frank-financial-regulatory-reform-bill.asp">investopedia.com/terms/d/ dodd - frank -financial-regulatory-reform-bill.asp</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#regulation`, `#derivatives`, `#bitcoin`

---

<a id="item-22"></a>
## [Base Beryl Upgrade and B20 Token Standard Launch June 25](https://www.theblock.co/post/405410/base-targets-june-25-mainnet-launch-for-beryl-upgrade-and-new-b20-token-standard?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Base's Beryl upgrade will launch on mainnet June 25, introducing the B20 native token standard and reducing withdrawal delays to 5 days. This upgrade transforms Base into a first-class issuance platform for regulated financial instruments like stablecoins and RWAs, potentially attracting institutional adoption and improving capital efficiency. B20 tokens are implemented as Rust precompiles rather than EVM smart contracts, making them faster and cheaper, while remaining ERC-20 compatible for existing wallets and dApps.

rss · The Block · Jun 19, 10:48

**Background**: Base is an Ethereum Layer 2 blockchain built on the OP Stack. The Beryl upgrade is its second network upgrade, following the testnet deployment on Sepolia. B20 is a native token standard purpose-built for regulated financial instruments, issued directly within Base's node software.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.base.org/base-chain/specs/upgrades/beryl/b20">B 20 Native Token Standard - Base Documentation</a></li>
<li><a href="https://cryptobriefing.com/base-b20-token-standard-stablecoins-rwas/">Base's Jesse Pollak unveils B 20 token standard for stablecoins and...</a></li>
<li><a href="https://blog.base.dev/introducing-base-beryl">Introducing Base Beryl</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#Base`, `#token standard`, `#upgrade`, `#DeFi`

---

<a id="item-23"></a>
## [CLARITY Act: US Crypto Market Structure Bill Explained](https://www.theblock.co/learn/404536/what-is-the-clarity-act?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

The CLARITY Act (Digital Asset Market Clarity Act of 2025) is a proposed U.S. bill that would establish a federal framework for digital asset regulation, defining how crypto firms comply with law and which regulators oversee them. This bill could replace the current patchwork of state-level regulations and enforcement actions with a clear federal standard, providing legal certainty for crypto businesses and investors. It is considered the most important federal market structure bill yet proposed for digital assets. The bill focuses on clarifying whether crypto assets are securities or commodities, establishing rules for exchanges and brokers, and expanding definitions of commodity pool operator (CPO) and commodity trading advisor (CTA) to include digital asset managers. It also aims to replace 'regulation by enforcement' with a clear statutory framework.

rss · The Block · Jun 19, 06:48

**Background**: Currently, U.S. crypto regulation is fragmented, with the SEC and CFTC often disputing jurisdiction over digital assets. This has led to uncertainty and enforcement actions against crypto firms. The CLARITY Act seeks to provide a single, coherent federal framework to resolve these jurisdictional ambiguities and foster innovation while protecting consumers.

<details><summary>References</summary>
<ul>
<li><a href="https://emmer.house.gov/media-center/press-releases/emmer-s-securities-clarity-act-and-blockchain-regulatory-certainty-act-pass-house-financial-services-committee-markup">Emmer's Securities Clarity Act and Blockchain Regulatory Certainty Act ...</a></li>
<li><a href="https://www.reedsmith.com/articles/how-clarity-act-could-redefine-compliance-crypto-fund-managers-and-advisers/">How the CLARITY Act Could Redefine Compliance for Crypto…</a></li>
<li><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6484840">The Status of the CLARITY Act and the Future of U.S. Digital Asset ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#US policy`, `#digital assets`

---

<a id="item-24"></a>
## [Fidelity Launches GENIUS-Aligned Money Market Fund for Stablecoin Issuers](https://www.theblock.co/post/405357/fidelity-stablecoin-money-market-fund?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Fidelity has launched a government money market fund specifically designed for stablecoin issuers, which invests exclusively in eligible reserve assets permitted under the GENIUS Act. This marks a major financial institution's direct alignment with stablecoin regulation, providing a compliant reserve management option for stablecoin issuers and potentially increasing institutional adoption of stablecoins. The fund invests only in eligible reserve assets as defined by the GENIUS Act, which was enacted in July 2025 and provides a federal regulatory framework for payment stablecoins.

rss · The Block · Jun 19, 01:58

**Background**: Stablecoins are cryptocurrencies designed to maintain a stable value, often backed by reserves like cash or government securities. The GENIUS Act is a U.S. law that establishes federal requirements for stablecoin issuers, including rules on reserve assets. Fidelity's fund offers a compliant vehicle for issuers to hold these reserves.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/405357/fidelity-stablecoin-money-market-fund">Fidelity launches GENIUS-aligned money market fund for stablecoin ...</a></li>
<li><a href="https://www.congress.gov/bill/119th-congress/senate-bill/1582/text">Text - S.1582 - 119th Congress (2025-2026): GENIUS Act</a></li>
<li><a href="https://home.treasury.gov/news/press-releases/sb0435">Treasury Proposes Rule to Implement the GENIUS Act's Requirements to ...</a></li>

</ul>
</details>

**Tags**: `#stablecoins`, `#finance`, `#cryptocurrency`, `#regulation`

---