---
layout: default
title: "Horizon Summary: 2026-07-21 (EN)"
date: 2026-07-21
lang: en
---

> From 64 items, 18 important content pieces were selected

---

1. [Hacker wipes Romania's entire land registry database](#item-1) ⭐️ 9.0/10
2. [Cursor's Agent Swarm Hits 1000 Commits/s, New VCS Built](#item-2) ⭐️ 9.0/10
3. [Chinese Open-Source AI Models Threaten Western Pricing](#item-3) ⭐️ 8.0/10
4. [AI Outpaces Humans in Generating Counterexamples](#item-4) ⭐️ 8.0/10
5. [Zcash Unveils Node Targeting Visa-Scale Privacy at 50K TPS](#item-5) ⭐️ 8.0/10
6. [Jellyfin Founder Steps Down Due to Burnout](#item-6) ⭐️ 7.0/10
7. [ACLU Report Accuses Flock Safety of Repeated Deception](#item-7) ⭐️ 7.0/10
8. [China's open-weights AI strategy gains strategic advantage](#item-8) ⭐️ 7.0/10
9. [LEDs Can Be Designed to Save Night Skies](#item-9) ⭐️ 7.0/10
10. [Allbridge halts after $1.65M flash loan exploit](#item-10) ⭐️ 7.0/10
11. [Jelly UI: Soft-body physics for native HTML form controls](#item-11) ⭐️ 6.0/10
12. [Immersive 3D Tour of Grace Cathedral via Gaussian Splatting](#item-12) ⭐️ 6.0/10
13. [Bank of Korea to launch live CBDC transactions in September](#item-13) ⭐️ 6.0/10
14. [Bitcoin quantum recovery tool emerges, but Satoshi's coins remain vulnerable](#item-14) ⭐️ 6.0/10
15. [Russia's Crypto Law Nears Passage, Bypasses Sanctions](#item-15) ⭐️ 6.0/10
16. [Cardano Triggers First Community-Voted Hard Fork](#item-16) ⭐️ 6.0/10
17. [NEAR co-founder warns AI hacking outpaces code reviews](#item-17) ⭐️ 6.0/10
18. [Hut 8 and IREN Secure Billions in AI Data Center Leases](#item-18) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Hacker wipes Romania's entire land registry database](https://news.risky.biz/risky-bulletin-hacker-wipes-romanias-entire-land-registry-database/) ⭐️ 9.0/10

A hacker deleted Romania's entire land registry database after a failed extortion attempt, paralyzing the real estate market and halting all property transactions nationwide. This incident threatens the legal foundation of property ownership in Romania, potentially causing chaos in land sales, mortgages, and inheritance if backups fail. It highlights the vulnerability of critical government infrastructure to cyberattacks. The hacker, identified as Zakaria Mahdjoub from Algeria, claimed to have deleted backups, but Romanian authorities reportedly had an offline copy. The agency is migrating systems to the government cloud with help from the Special Telecommunications Service.

hackernews · speckx · Jul 20, 13:28 · [Discussion](https://news.ycombinator.com/item?id=48978605)

**Background**: Romania's land registry (ANCPI) is the national database that records property ownership, boundaries, and legal claims. Without it, notaries cannot authenticate sales or register mortgages, effectively freezing the real estate market. Offline backups are stored separately from the main network to protect against ransomware and other attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://cybernews.com/security/hacker-deletes-romanian-land-registry-database/">Hacker deletes country’s entire land registry database ... | Cybernews</a></li>
<li><a href="https://www.newsdirectory3.com/romania-land-registry-paralysed-by-major-cyberattack/">Romania Land Registry Paralysed by Major... - News Directory 3</a></li>

</ul>
</details>

**Discussion**: Commenters expressed concern about corruption in government IT contracts, suggesting cronies neglect security. Some noted the hacker's Algerian origin and extradition treaty with Romania, while others praised the apparent existence of offline backups as a critical safeguard.

**Tags**: `#cybersecurity`, `#data breach`, `#critical infrastructure`, `#ransomware`, `#Romania`

---

<a id="item-2"></a>
## [Cursor's Agent Swarm Hits 1000 Commits/s, New VCS Built](https://cursor.com/blog/agent-swarm-model-economics) ⭐️ 9.0/10

Cursor's blog reports that their new agent swarm system achieves a peak rate of 1,000 commits per second, a dramatic increase from the previous 1,000 commits per hour. To support this throughput, they built a custom version control system (VCS) from scratch. This experiment demonstrates the potential for massive parallel AI agent collaboration, pushing the boundaries of software development automation. It also raises important questions about LLM training data contamination, as the swarm successfully rebuilt SQLite from scratch in Rust using only documentation. The new VCS was built not only for throughput but also to make collisions visible and implement coordination mechanisms. The swarm's task was to build SQLite from scratch in Rust using only its documentation, a task the previous swarm had struggled with.

hackernews · jlaneve · Jul 20, 18:06 · [Discussion](https://news.ycombinator.com/item?id=48982535)

**Background**: Agent swarms are multi-agent systems where multiple AI agents work together on complex tasks. Version control systems like Git track changes in code, but traditional VCS cannot handle the extreme commit rates generated by large agent swarms. LLM training data contamination occurs when test data appears in training data, potentially inflating performance metrics.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/lyy1994/awesome-data-contamination">GitHub - lyy1994/awesome-data-contamination: The Paper List on Data Contamination for Large Language Models Evaluation. · GitHub</a></li>
<li><a href="https://www.holisticai.com/blog/overview-of-data-contamination">An Overview of Data Contamination: The Causes, Risks, Signs, and Defenses</a></li>

</ul>
</details>

**Discussion**: Commenters expressed excitement about the experiment's futuristic implications, with one noting it's like 'glimpses into the future' similar to early coding agents in 2023. However, several raised concerns about LLM memorization, questioning whether the models were trained on SQLite's source code, making the achievement less impressive.

**Tags**: `#agent swarms`, `#LLM`, `#version control`, `#AI engineering`, `#software development`

---

<a id="item-3"></a>
## [Chinese Open-Source AI Models Threaten Western Pricing](https://stratechery.com/2026/whos-afraid-of-chinese-models/) ⭐️ 8.0/10

Chinese AI labs are releasing high-quality open-source models that undercut the premium API pricing of Western labs like Anthropic and OpenAI, threatening their billion-dollar valuations. This could force Western frontier labs to lower prices or compete on features, reshaping the AI industry's economics and potentially reducing the dominance of US-based AI companies. Anthropic is valued at $1.2 trillion and OpenAI at $850 billion, with valuations built on premium API pricing; Chinese open-source models are free, creating a race to the bottom.

hackernews · mfiguiere · Jul 20, 11:05 · [Discussion](https://news.ycombinator.com/item?id=48977128)

**Background**: Open-source AI models are publicly available and can be freely used, modified, and distributed. Chinese labs like DeepSeek have released competitive models that rival Western ones, raising concerns about geopolitical influence and data security.

**Discussion**: Commenters are divided: some fear Chinese models as a Trojan horse for propaganda and data theft, while others note low switching costs between coding assistants and argue that open-source competition benefits users.

**Tags**: `#AI`, `#Chinese AI`, `#Open Source`, `#Valuation`, `#Geopolitics`

---

<a id="item-4"></a>
## [AI Outpaces Humans in Generating Counterexamples](https://xenaproject.wordpress.com/2026/07/20/human-mathematicians-are-being-outcounterexampled/) ⭐️ 8.0/10

AI systems are now generating counterexamples to mathematical conjectures, potentially reshaping how mathematicians work and saving time by disproving false hypotheses early. This development could dramatically accelerate mathematical research by quickly eliminating false conjectures, allowing mathematicians to focus on promising directions. It also raises questions about the future role of human intuition in mathematics. The blog post from the Xena Project discusses how AI models like Sol and Fable are being used to find counterexamples, with graduate students paying $200 per month for access. A notable anecdote involves Yitang Zhang, whose career was impacted by an incorrect corollary in his thesis.

hackernews · artninja1988 · Jul 20, 19:03 · [Discussion](https://news.ycombinator.com/item?id=48983382)

**Background**: Automated theorem proving (ATP) is a subfield of computer science that uses programs to prove mathematical theorems automatically. Counterexample generation is a related task where AI systems produce specific examples that disprove conjectures. Recent advances in large language models have enabled formal counterexample generation with verification in theorem provers like Lean 4.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Automated_theorem_proving">Automated theorem proving</a></li>
<li><a href="https://arxiv.org/abs/2603.19514">[2603.19514] Learning to Disprove: Formal Counterexample Generation with Large Language Models</a></li>
<li><a href="https://www.newscientist.com/article/2278276-an-ai-has-disproved-five-mathematical-conjectures-with-no-human-help/">An AI has disproved five mathematical conjectures with no human help | New Scientist</a></li>

</ul>
</details>

**Discussion**: Commenters generally view AI counterexample generation positively, noting it saves time and prevents wasted effort on false conjectures. Some express nostalgia for human-centric mathematics, comparing it to the folk tale of John Henry. The anecdote about Yitang Zhang highlights the real-world consequences of undetected errors.

**Tags**: `#AI`, `#mathematics`, `#research methodology`, `#automated theorem proving`

---

<a id="item-5"></a>
## [Zcash Unveils Node Targeting Visa-Scale Privacy at 50K TPS](https://www.coindesk.com/tech/2026/07/16/inside-zcash-s-new-node-that-targets-visa-scale-privacy-at-50-000-transactions-per-second) ⭐️ 8.0/10

Zcash announced a new node capable of processing 50,000 transactions per second while preserving privacy, aiming to compete with Visa-scale throughput. This milestone could significantly advance blockchain scalability and privacy, potentially driving broader cryptocurrency adoption by addressing key limitations of existing networks. The node leverages advanced zero-knowledge proofs to achieve high throughput without compromising privacy, though specific technical details and release timeline have not been fully disclosed.

rss · CoinDesk · Jul 19, 05:37

**Background**: Zcash is a privacy-focused cryptocurrency that uses zero-knowledge proofs (zk-SNARKs) to enable shielded transactions. Scalability has been a challenge for privacy coins, as privacy features often increase computational overhead. Visa processes around 1,700 transactions per second on average, so 50,000 TPS would far exceed current blockchain capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://zcash.readthedocs.io/en/latest/rtd_pages/zcashd.html">Zcash Full Node and CLI — Zcash Documentation...</a></li>
<li><a href="https://github.com/ZcashFoundation/zebra">GitHub - ZcashFoundation/zebra: Zcash - Financial Privacy in Rust</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-knowledge_proof">Zero-knowledge proof - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#privacy`, `#scalability`, `#cryptocurrency`, `#Zcash`

---

<a id="item-6"></a>
## [Jellyfin Founder Steps Down Due to Burnout](https://forum.jellyfin.org/t-project-leadership-changes) ⭐️ 7.0/10

Andrew, the founder of the open-source media server Jellyfin, has stepped down from the project leadership due to severe burnout, as announced on the Jellyfin forum. This event highlights the ongoing challenge of burnout in open-source communities and underscores Jellyfin's importance as a free alternative to proprietary media servers like Plex, especially after Plex's recent price hike. Andrew cited severe burnout and risks to his mental health as reasons for leaving, noting he could no longer meet the role's demands. The transition appears peaceful, with the project continuing under new leadership.

hackernews · swat535 · Jul 20, 23:15 · [Discussion](https://news.ycombinator.com/item?id=48986091)

**Background**: Jellyfin is a free and open-source media server that allows users to host and stream their own media libraries to various devices. It emerged as a fork of Emby in 2018 and has grown as a popular alternative to proprietary solutions like Plex, which recently increased its lifetime Plex Pass price to $750.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jellyfin">Jellyfin - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community members expressed gratitude for Andrew's contributions and sympathy for his burnout, while also reflecting on the broader issue of FLOSS sustainability. Some noted that Jellyfin works well for their needs, especially as a Plex alternative.

**Tags**: `#open-source`, `#media-server`, `#burnout`, `#FLOSS`, `#community`

---

<a id="item-7"></a>
## [ACLU Report Accuses Flock Safety of Repeated Deception](https://www.aclu.org/news/privacy-technology/tracking-alpr-cameras/flock-safety-credibility-lost-as-it-repeatedly-lies-to-city-councils-police-departments-and-public-across-the-country) ⭐️ 7.0/10

The ACLU published a report detailing how Flock Safety, a license plate recognition company, has repeatedly misled city councils, police departments, and the public about its technology's capabilities and privacy protections. This report undermines Flock Safety's credibility and raises serious concerns about the deployment of surveillance technology without transparent and honest communication, potentially affecting public trust and privacy rights. The report highlights that Flock Safety released a misleading blog post to confuse the public and create a false sense of security among government customers, rather than addressing data security and control issues on their merits.

hackernews · StatsAreFun · Jul 21, 00:33 · [Discussion](https://news.ycombinator.com/item?id=48986731)

**Background**: Flock Safety is a manufacturer of automated license plate recognition (ALPR) cameras used by law enforcement and communities to solve crimes. The ACLU and other privacy advocates have long raised concerns about the potential for mass surveillance and data misuse. This report adds to a growing body of criticism about the company's practices.

<details><summary>References</summary>
<ul>
<li><a href="https://www.aclu.org/news/privacy-technology/tracking-alpr-cameras/flock-safety-credibility-lost-as-it-repeatedly-lies-to-city-councils-police-departments-and-public-across-the-country">Flock Safety Credibility Lost as it Repeatedly Lies to City Councils, Police Departments, and Public Across the Country | American Civil Liberties Union</a></li>
<li><a href="https://en.wikipedia.org/wiki/Flock_Safety">Flock Safety - Wikipedia</a></li>
<li><a href="https://www.aclu-wy.org/news/flock-safety-credibility-lost-as-it-repeatedly-lies-to-city-councils-police-departments-and-public-across-the-country/">Flock Lied About its ALPR technology. What Else Has It Lied About?</a></li>

</ul>
</details>

**Discussion**: Comments on the news reflect skepticism about Flock Safety's credibility, with one user noting the company makes no effort to install poles complying with highway safety standards. Another commenter doubts the surveillance state will disappear soon, while a third suggests the behavior is symptomatic of a society that celebrates winners who lie.

**Tags**: `#privacy`, `#surveillance`, `#ethics`, `#law enforcement`, `#technology`

---

<a id="item-8"></a>
## [China's open-weights AI strategy gains strategic advantage](https://werd.io/american-ai-is-locked-down-and-proprietary-its-losing/) ⭐️ 7.0/10

An opinion article argues that China's open-weights AI models are winning over proprietary US models, citing historical trends where open and low-end solutions dominate. This shift could reshape the global AI landscape, making advanced AI more accessible and affordable, and challenging the dominance of US proprietary AI companies. The article notes that 80% of startups are using Chinese models, though some commenters dispute this figure. Open-weights models are not fully open-source, as they allow download and customization but may have usage restrictions.

hackernews · benwerd · Jul 20, 14:21 · [Discussion](https://news.ycombinator.com/item?id=48979269)

**Background**: Open-weights AI models are models whose core components are publicly released, allowing anyone to download and run them. This contrasts with proprietary models like OpenAI's GPT-4, which are only accessible via API. China has been aggressively releasing open-weights models at low cost, aiming to capture market share from Western companies.

<details><summary>References</summary>
<ul>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://www.forbes.com/sites/sylvainduranton/2025/07/07/what-leaders-need-to-know-about-open-source-vs-proprietary-models/">What Leaders Need To Know About Open-Source Vs. Proprietary Models</a></li>

</ul>
</details>

**Discussion**: Commenters are divided: some agree that open-weights will eventually dominate, while others question the claim that 80% of startups use Chinese models and note that enterprises prioritize data retention over openness. One commenter points out that Meta's Llama, a leading open-weight model, has not brought success to Meta.

**Tags**: `#AI`, `#open-source`, `#China`, `#strategy`, `#LLM`

---

<a id="item-9"></a>
## [LEDs Can Be Designed to Save Night Skies](https://spectrum.ieee.org/led-light-pollution) ⭐️ 7.0/10

The article discusses how LED lighting can be engineered to reduce light pollution, preserving night skies while maintaining safety and functionality. This matters because light pollution affects astronomy, ecosystems, and human health; better LED design offers a practical path to balance urban needs with environmental preservation. Key details include using shielded fixtures, warmer color temperatures, and adaptive controls to minimize skyglow and glare while meeting illumination standards.

hackernews · defrost · Jul 20, 13:07 · [Discussion](https://news.ycombinator.com/item?id=48978350)

**Background**: Light pollution is the excessive or misdirected artificial light that brightens the night sky, obscuring stars and disrupting wildlife. LEDs, while energy-efficient, can worsen light pollution if poorly designed, but proper engineering can mitigate these effects.

**Discussion**: Commenters highlight trade-offs between security and light reduction, with some noting that lighting can deter crime. Others share innovative solutions like motion-activated park lights and call for better engineering standards to reduce glare.

**Tags**: `#light pollution`, `#LED lighting`, `#environmental impact`, `#urban planning`, `#astronomy`

---

<a id="item-10"></a>
## [Allbridge halts after $1.65M flash loan exploit](https://www.coindesk.com/business/2026/07/20/cross-chain-protocol-allbridge-halts-after-usd1-65-million-flash-loan-exploit) ⭐️ 7.0/10

Cross-chain protocol Allbridge paused operations after a flash loan exploit resulted in a loss of approximately $1.65 million. Security firms PeckShield and CertiK reported that the attacker bridged the stolen funds from Solana to Ethereum. This incident highlights persistent security vulnerabilities in cross-chain bridges, which are critical infrastructure for DeFi interoperability. Such exploits erode user trust and underscore the need for more robust security measures in bridging protocols. The attacker used a flash loan to manipulate the price of Allbridge's Solana stablecoin pools before draining funds. The exploit occurred on July 20, 2026, and the protocol was halted shortly after detection.

rss · CoinDesk · Jul 20, 09:31

**Background**: Flash loans are uncollateralized loans that must be repaid within a single transaction, often used in DeFi exploits to manipulate prices. Cross-chain bridges like Allbridge enable token transfers between different blockchains but have been frequent targets for hackers due to their complexity and large liquidity pools.

<details><summary>References</summary>
<ul>
<li><a href="https://denntech.io/glossary/flash-loan-attack-vectors">Flash Loan Attack Vectors and DeFi Protocol Defences... | DennTech</a></li>
<li><a href="https://medium.com/@footprintofficial/what-are-cross-chain-bridges-and-why-do-they-matter-53815fa2dbea">What are cross - chain bridges and why do they matter? | Medium</a></li>
<li><a href="https://defillama.com/protocol/allbridge">Allbridge TVL, Fees, Revenue & Volume</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#flash loan`, `#blockchain`, `#exploit`

---

<a id="item-11"></a>
## [Jelly UI: Soft-body physics for native HTML form controls](https://jelly-ui.com/) ⭐️ 6.0/10

Jelly UI is a library that adds soft-body physics animations to native HTML form controls, such as buttons and checkboxes, using a requestAnimationFrame loop running every 8ms. This library demonstrates a creative use of physics in UI, but raises concerns about performance and usability, highlighting the trade-off between visual delight and standard UX practices. The library uses a shared animation frame that steps every live component and parks when idle, with delta capped to avoid large jumps after background tabs. However, it causes full document repaints, leading to lag on some systems.

hackernews · baldvinmar · Jul 20, 17:07 · [Discussion](https://news.ycombinator.com/item?id=48981620)

**Background**: Soft-body physics simulates deformable objects using spring-mass systems, commonly used in games and simulations. Jelly UI applies this concept to HTML form controls, making them behave like jelly when interacted with. The library respects prefers-reduced-motion for accessibility.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/salty-max/jelly">GitHub - salty-max/ jelly : A minimalistic UI components library · GitHub</a></li>
<li><a href="https://worksetuplab.com/accessibility-inclusive-workspaces/jelly-ui-soft-body-physics-for-native-html-form-controls/">Jelly UI : Soft-body Physics For Native HTML Form... - WorkSetupLab</a></li>

</ul>
</details>

**Discussion**: Community feedback is mixed: some find it cute and appreciate the reduced-motion support, while others criticize performance issues and inconsistent click behavior. One user noted it causes full document repaints, and another pointed out that clicking and dragging away should not register as a click.

**Tags**: `#UI`, `#animation`, `#web development`, `#physics`

---

<a id="item-12"></a>
## [Immersive 3D Tour of Grace Cathedral via Gaussian Splatting](https://vincentwoo.com/3d/grace_cathedral/) ⭐️ 6.0/10

A developer created an immersive 3D tour of Grace Cathedral in San Francisco using Gaussian splatting from drone photographs, showcasing the technology's ability to produce detailed, navigable models from images. This demo highlights Gaussian splatting's potential for accessible, high-quality photogrammetry, enabling virtual tourism and architectural documentation without expensive equipment or complex workflows. The tour runs in a web browser using WebGPU, but some users on Firefox encounter errors where buffer binding sizes exceed the `max_*_buffer_binding_size` limit, causing the experience to stop after a few seconds.

hackernews · akanet · Jul 20, 20:10 · [Discussion](https://news.ycombinator.com/item?id=48984254)

**Background**: Gaussian splatting is a volume rendering technique that represents 3D scenes using collections of anisotropic Gaussian primitives, enabling real-time novel view synthesis from photographs. Photogrammetry extracts 3D measurements from images, and WebGPU is a modern web API for GPU acceleration, superseding WebGL.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Gaussian_splatting">Gaussian splatting</a></li>
<li><a href="https://en.wikipedia.org/wiki/Photogrammetry">Photogrammetry</a></li>
<li><a href="https://en.wikipedia.org/wiki/WebGPU">WebGPU</a></li>

</ul>
</details>

**Discussion**: Commenters praised the immersive experience on mobile and noted its similarity to early VRML demos. However, several users reported WebGPU errors on Firefox, and one comment referenced the developer's prior work scanning Sutro Tower.

**Tags**: `#3D rendering`, `#Gaussian splatting`, `#photogrammetry`, `#WebGPU`

---

<a id="item-13"></a>
## [Bank of Korea to launch live CBDC transactions in September](https://www.coindesk.com/business/2026/07/20/bank-of-korea-prepares-for-live-cbdc-transactions-with-nine-banks-in-september) ⭐️ 6.0/10

The Bank of Korea will begin live central bank digital currency (CBDC) transactions with nine commercial banks in September 2025, moving from Phase 1 of Project Hangang to Phase 2, which involves real government money. This marks a significant step in practical CBDC adoption, as it tests real-value transactions with government funds, potentially influencing other central banks' digital currency strategies. Phase 1 of Project Hangang opened 81,000 wallets with 42% active usage; Phase 2 expands the pilot to include nine banks and moves real government money, building on earlier retail tests with 100,000 participants and 70,000 merchants.

rss · CoinDesk · Jul 20, 11:10

**Background**: Project Hangang is the Bank of Korea's CBDC pilot program, initially testing retail payments from April to June 2025 with 100,000 participants and merchants like 7-Eleven. CBDCs are digital currencies issued by central banks, designed to complement cash and enhance payment efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/testing-central-bank-digital-currency-cbdc-project-hangang-future-m8wvc">Testing Central Bank Digital Currency ( CBDC ): Project Hangang and...</a></li>
<li><a href="https://dzilla.com/south-koreas-hangang-cbdc-pilot-pioneering-retail-digital-won-adoption/">South Korea’s Hangang CBDC Pilot: Pioneering Retail Digital Won...</a></li>
<li><a href="https://www.chosun.com/english/market-money-en/2025/03/19/XOUS2TBB2ZAPRJ7R57QJEYM7IE/">Bank of Korea to launch CBDC pilot for real-world payments</a></li>

</ul>
</details>

**Tags**: `#CBDC`, `#central bank digital currency`, `#blockchain`, `#finance`, `#South Korea`

---

<a id="item-14"></a>
## [Bitcoin quantum recovery tool emerges, but Satoshi's coins remain vulnerable](https://www.coindesk.com/tech/2026/07/19/bitcoin-s-quantum-problem-gets-a-recovery-tool-but-not-for-satoshi-s-1-1-million-coin) ⭐️ 6.0/10

A new tool has been developed that can recover Bitcoin funds lost due to quantum attacks, but it cannot recover the 1.1 million Bitcoins attributed to Satoshi Nakamoto. This tool addresses a growing concern about quantum computing's threat to Bitcoin's cryptography, but its limitation highlights the irreversible loss of Satoshi's coins and the need for broader quantum-resistant solutions. The recovery tool works by exploiting a vulnerability in the quantum attack itself, but it cannot recover coins from addresses that were never spent or have no known private key, such as Satoshi's early wallets.

rss · CoinDesk · Jul 19, 10:00

**Background**: Quantum computers could potentially break the elliptic curve cryptography used in Bitcoin, allowing attackers to steal funds. While large-scale quantum attacks are not yet feasible, researchers are developing countermeasures. Satoshi Nakamoto, Bitcoin's pseudonymous creator, holds an estimated 1.1 million Bitcoins in early wallets that have never been moved.

<details><summary>References</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2plcm96OEVCRU51X1VTaGhvcU5pZ0FQAQ?hl=en-US&gl=US&ceid=US:en">Google News - Quantum attack on Bitcoin - Overview</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#quantum computing`, `#cryptography`, `#blockchain`

---

<a id="item-15"></a>
## [Russia's Crypto Law Nears Passage, Bypasses Sanctions](https://decrypt.co/373880/russia-first-comprehensive-crypto-law) ⭐️ 6.0/10

Russia's comprehensive crypto law is two votes away from passing, which would license exchanges, cap retail investments at about $3,800 per year, and create a legal pathway for Russian companies to pay foreign partners in cryptocurrency, bypassing Western sanctions. This law marks a major shift in Russia's stance on crypto, potentially enabling sanctioned entities to evade financial restrictions and impacting global crypto regulation dynamics. The bill also obliges crypto miners to report digital currency holdings to state authorities, and the government can ban or restrict crypto transactions to maintain monetary stability.

rss · Decrypt · Jul 20, 20:02

**Background**: Russia has faced increasing Western sanctions since its invasion of Ukraine, prompting it to explore alternative payment systems. Cryptocurrency offers a potential workaround, but experts doubt its effectiveness due to traceability and liquidity issues.

<details><summary>References</summary>
<ul>
<li><a href="https://advertising.industriesnews.net/news/274479555/russian-upper-house-approves-crypto-law">Russian Upper House approves crypto law</a></li>
<li><a href="https://www.chainalysis.com/blog/russias-cryptocurrency-legislated-sanctions-evasion/">Russia’s Cryptocurrency Pivot: Legislated Sanctions ... - Chainalysis</a></li>
<li><a href="https://news.bitcoin.com/crypto-payments-may-not-help-russia-bypass-sanctions-experts-say/">Crypto Payments May Not Help Russia Bypass Sanctions , Experts...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#Russia`, `#sanctions`

---

<a id="item-16"></a>
## [Cardano Triggers First Community-Voted Hard Fork](https://decrypt.co/373858/cardano-van-rossem-hard-fork-live-community-upgrade) ⭐️ 6.0/10

Cardano executed its first hard fork triggered entirely by a community vote, with no company or central authority initiating the upgrade. This milestone demonstrates a shift toward decentralized governance in Cardano, potentially setting a precedent for other blockchain networks to adopt community-driven upgrade mechanisms. The hard fork was activated through Cardano's on-chain governance system, where ADA holders voted directly on the proposal. No specific technical details about the upgrade's features were disclosed in the news item.

rss · Decrypt · Jul 20, 18:50

**Background**: Cardano is a proof-of-stake blockchain platform that emphasizes peer-reviewed research and formal verification. Hard forks are protocol upgrades that require network-wide consensus; previously, such upgrades were initiated by the development company IOHK (now Input Output Global). This event marks the first time the community voted directly to trigger a hard fork, reflecting Cardano's transition to a fully decentralized governance model as outlined in its Voltaire era.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Hornan7/Cardano-Constitution-MVG">GitHub - Hornan7/ Cardano -Constitution-MVG</a></li>
<li><a href="https://coinlaw.io/ethereum-vs-cardano-statistics/">Ethereum vs. Cardano Statistics 2026: DeFi, NFTs, etc. • CoinLaw</a></li>
<li><a href="https://forum.cardano.org/t/cardano-community-the-clock-is-ticking/154340">Cardano community — the clock is ticking... - Cardano Forum</a></li>

</ul>
</details>

**Tags**: `#Cardano`, `#blockchain`, `#governance`, `#hard fork`

---

<a id="item-17"></a>
## [NEAR co-founder warns AI hacking outpaces code reviews](https://www.theblock.co/post/408943/ai-assisted-hacking-outpacing-traditional-code-reviews-near-co-founder-says?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

NEAR co-founder Illia Polosukhin stated that AI-assisted hacking is outpacing traditional code reviews, and called for formal verification to secure blockchain code. This highlights a growing security gap in blockchain development, where AI-powered attacks can exploit vulnerabilities faster than humans can review code, potentially leading to more frequent and severe exploits. Polosukhin specifically advocated for formal verification, a mathematical method to prove code correctness, as a necessary shift to counter AI-assisted hacking threats.

rss · The Block · Jul 20, 18:20

**Background**: Formal verification uses mathematical proofs to ensure smart contracts behave as intended under all conditions, eliminating entire classes of bugs. NEAR Protocol is a layer-1 blockchain that uses sharding and proof-of-stake to support decentralized applications. Traditional code reviews rely on human auditors, which can be slower and less exhaustive than automated AI attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/NEAR_Protocol">NEAR Protocol</a></li>
<li><a href="https://hashlock.pages.dev/services/formal-verification">Blockchain Formal Verification | Hashlock</a></li>

</ul>
</details>

**Tags**: `#AI`, `#blockchain`, `#security`, `#code review`

---

<a id="item-18"></a>
## [Hut 8 and IREN Secure Billions in AI Data Center Leases](https://www.theblock.co/post/408920/hut-8-fully-commercializes-1-gw-texas-ai-campus-with-second-9-8b-lease-as-iren-signs-2-8b-in-contracts-shares-climb-double-digits?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Hut 8 fully commercialized its 1 GW Texas AI campus with a second $9.8 billion lease, while IREN signed $2.8 billion in AI infrastructure contracts, sending both stocks up double digits. These deals underscore the accelerating pivot from bitcoin mining to AI infrastructure, as miners leverage their energy assets and land for high-value AI compute contracts. Hut 8's second lease fully commercializes its Texas campus, and IREN's contracts include deals with Microsoft and Nvidia, with IREN also securing a $9.7 billion Microsoft contract for AI cloud using Nvidia GB300 GPUs.

rss · The Block · Jul 20, 14:12

**Background**: Bitcoin miners like Hut 8 and IREN have been pivoting to AI infrastructure, repurposing their energy and land assets to host AI data centers. This shift is driven by the higher and more stable revenue from AI compute compared to volatile mining rewards.

<details><summary>References</summary>
<ul>
<li><a href="https://247wallst.com/investing/2026/07/20/hut-8-jumps-10-on-9-8b-ai-data-center-lease-mara-riot-platforms-rally-in-sympathy/">Hut 8 Jumps 10% on $9.8B AI Data Center Lease... - 24/7 Wall St.</a></li>
<li><a href="https://www.cryptobreaking.com/hut-8-and-iren-updates/">Hut 8 and IREN Updates Boost AI -Focused Bitcoin Mining Stocks</a></li>
<li><a href="https://parameter.io/iren-stock-australian-data-center-operator-lands-9-7-billion-microsoft-contract/">IREN Stock: Australian Data Center Operator Lands... - Parameter</a></li>

</ul>
</details>

**Tags**: `#AI infrastructure`, `#data centers`, `#bitcoin mining`, `#finance`

---