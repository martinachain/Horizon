---
layout: default
title: "Horizon Summary: 2026-05-14 (EN)"
date: 2026-05-14
lang: en
---

> From 83 items, 19 important content pieces were selected

---

1. [LLMs Enable Personal Software, Echoing Emacs Customization](#item-1) ⭐️ 8.0/10
2. [Fired IT twins wiped 96 government databases using SQL](#item-2) ⭐️ 8.0/10
3. [Half of AI Health Advice Is Wrong—And Seems Just Right](#item-3) ⭐️ 8.0/10
4. [Malware Found in Mistral AI Python Package](#item-4) ⭐️ 8.0/10
5. [JPMorgan Files for Tokenized Money Market Fund on Ethereum](#item-5) ⭐️ 8.0/10
6. [Fake OpenAI Repo on Hugging Face Stole Passwords](#item-6) ⭐️ 8.0/10
7. [DTCC Partners with Chainlink for 24/7 Collateral Management](#item-7) ⭐️ 8.0/10
8. [North Korean Hackers Stole $2.1B in Crypto in 2025: CertiK](#item-8) ⭐️ 8.0/10
9. [MacBook Neo Deep Dive: Benchmarks, Wafer Economics, and the 8GB Gamble](#item-9) ⭐️ 7.0/10
10. [Solana's Alpenglow Upgrade Now Live for Testing](#item-10) ⭐️ 7.0/10
11. [Charles Schwab Launches Spot Crypto Trading for Retail Clients](#item-11) ⭐️ 7.0/10
12. [Anthropic and OpenAI Warn: Unauthorized Shares May Be Worthless](#item-12) ⭐️ 7.0/10
13. [Free Locality Domains Under .city.state.us Guide](#item-13) ⭐️ 6.0/10
14. [Animoca-backed NUVA connects Figure's $19B tokenized assets to Ethereum](#item-14) ⭐️ 6.0/10
15. [JPMorgan Files to Launch New Tokenized Fund](#item-15) ⭐️ 6.0/10
16. [Ethereum Developers Propose Fix to Blind Signing Risk](#item-16) ⭐️ 6.0/10
17. [OpenAI Sued Over ChatGPT's Role in Teen's Fatal Overdose](#item-17) ⭐️ 6.0/10
18. [Immunefi to absorb Code4rena bug bounty customers after shutdown](#item-18) ⭐️ 6.0/10
19. [Japan's Enterprise Blockchain to Issue Yen Stablecoin for B2B](#item-19) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [LLMs Enable Personal Software, Echoing Emacs Customization](https://sockpuppet.org/blog/2026/05/12/emacsification/) ⭐️ 8.0/10

An essay argues that large language models (LLMs) make building personal software easier than installing existing solutions, leading to an 'Emacsification' where everyone can craft their own tools. This paradigm shift could empower individuals to reclaim software creation from prepackaged professional products, fostering a new era of personalized, user-driven applications. The essay lists examples like podcast apps, feed readers, and note-taking apps as areas where LLM-generated personal software can surpass generic solutions. The term 'Emacsification' draws a parallel to Emacs' highly customizable .emacs file.

hackernews · rdslw · May 13, 07:06 · [Discussion](https://news.ycombinator.com/item?id=48118727)

**Background**: Emacs is a highly extensible text editor where users customize behavior via a configuration file (.emacs). 'Vibe coding' is a recent practice where developers describe tasks to an LLM, which generates code automatically. The essay suggests LLMs lower the barrier to creating personal software, similar to how Emacs empowered users to tailor their editing environment.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48118727">The Emacsification of Software - Hacker News</a></li>
<li><a href="https://en.wikipedia.org/wiki/Vibe_coding">Vibe coding - Wikipedia</a></li>
<li><a href="https://sockpuppet.org/">The Emacsification of Software — Quarrelsome</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree with the thesis, with tptacek listing specific app categories ripe for personal software creation. dang emphasizes that software production is now so easy that everything becomes a personal .emacs file. Some, like shaokind, note that Emacs itself can be brittle across platforms, but the core idea resonates.

**Tags**: `#LLM`, `#software engineering`, `#personal software`, `#Emacs`, `#AI-assisted development`

---

<a id="item-2"></a>
## [Fired IT twins wiped 96 government databases using SQL](https://arstechnica.com/tech-policy/2026/05/drop-database-what-not-to-do-after-losing-an-it-job/) ⭐️ 8.0/10

Twin brothers Sohaib and Sohail Ahmad, fired from IT contractor Opexus on March 10, 2025, retaliated by using SQL commands to delete 96 government databases, including a Department of Homeland Security production database, within minutes of their termination. This incident highlights severe insider threat risks and failures in access management, as the brothers retained database access after termination. It underscores the need for immediate credential revocation and monitoring of privileged users, especially in government IT systems. The brothers used the SQL command "DROP DATABASE dhsproddb" to wipe a DHS database, and one brother later asked an AI tool how to clear SQL server logs. They were arrested on firearms charges, as one brother was a convicted felon in possession of seven firearms and 370 rounds of ammunition.

hackernews · jnord · May 12, 22:28 · [Discussion](https://news.ycombinator.com/item?id=48115438)

**Background**: Insider threats are security risks originating from within an organization, such as employees or contractors with access to sensitive data. SQL commands like DROP DATABASE can permanently delete entire databases if proper access controls are not in place. The incident occurred at Opexus, an IT contractor for U.S. government agencies.

<details><summary>References</summary>
<ul>
<li><a href="https://www.geeksforgeeks.org/sql/delete-database-in-ms-sql-server/">Delete Database in MS SQL Server - GeeksforGeeks</a></li>
<li><a href="https://www.empyrion.net/resource/understanding-insider-threats-what-they-are-and-how-to-manage-them">Understanding Insider Threats : What They... | Empyrion Technologies</a></li>

</ul>
</details>

**Discussion**: Commenters expressed shock that the brothers had access to production DHS databases, questioning hiring and security clearance processes. Some criticized the abrupt firing approach, suggesting it may have provoked retaliation, while others focused on the absurdity of asking an AI how to cover up the crime.

**Tags**: `#security`, `#insider threat`, `#database`, `#government`, `#IT management`

---

<a id="item-3"></a>
## [Half of AI Health Advice Is Wrong—And Seems Just Right](https://decrypt.co/367689/half-ai-health-advice-wrong-seems-right) ⭐️ 8.0/10

A peer-reviewed audit published in BMJ Open found that nearly 50% of health responses from five major AI chatbots were problematic, including fabricated sources and confident delivery of incorrect information. This study provides peer-reviewed evidence that AI chatbots frequently produce inaccurate health advice with fabricated citations, posing serious risks to user trust and safety in critical domains like healthcare. The audit tested five unnamed major AI chatbots on health queries and found that problematic responses often included fabricated sources that appeared credible. The chatbots delivered incorrect information with high confidence, making it harder for users to detect errors.

rss · Decrypt · May 13, 14:55

**Background**: AI chatbots like ChatGPT and Gemini are known to 'hallucinate'—generating plausible-sounding but false information. This phenomenon is especially dangerous in healthcare, where accuracy is critical. The BMJ Open study is one of the first peer-reviewed audits to systematically quantify this problem in health advice.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/367689/half-ai-health-advice-wrong-seems-right">Half of AI Health Advice Is Wrong—And Seems Just Right - Decrypt</a></li>
<li><a href="https://bmjopen.bmj.com/">Homepage | BMJ Open</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)">Hallucination (artificial intelligence) - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI`, `#health`, `#misinformation`, `#chatbots`, `#research`

---

<a id="item-4"></a>
## [Malware Found in Mistral AI Python Package](https://decrypt.co/367683/hackers-insert-malware-mistral-ai) ⭐️ 8.0/10

Microsoft Threat Intelligence reported that attackers inserted malware into a Mistral AI software download distributed through a Python package, part of a broader supply chain attack. This incident highlights critical security risks in AI software distribution, as compromised packages can affect numerous users and organizations relying on Mistral AI's tools. The attack involved over 400 compromised npm package versions and at least 2 PyPI packages, targeting TanStack, Mistral AI, UiPath, and others, according to SafeDep.

rss · Decrypt · May 12, 22:26

**Background**: A supply chain attack occurs when attackers compromise a trusted component, such as a Python package, to distribute malware to downstream users. Mistral AI provides open-source language models and tools, making its software a valuable target for such attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://safedep.io/mass-npm-supply-chain-attack-tanstack-mistral/">Mass Supply Chain Attack Hits TanStack, Mistral AI npm and ...</a></li>
<li><a href="https://thehackernews.com/2026/04/pytorch-lightning-compromised-in-pypi.html">PyTorch Lightning and Intercom-client Hit in Supply Chain ...</a></li>

</ul>
</details>

**Tags**: `#supply chain attack`, `#AI security`, `#malware`, `#Mistral AI`, `#Python`

---

<a id="item-5"></a>
## [JPMorgan Files for Tokenized Money Market Fund on Ethereum](https://decrypt.co/367664/jpmorgan-tokenized-money-market-fund-ethereum) ⭐️ 8.0/10

JPMorgan has filed to launch a tokenized money market fund that will initially operate on the Ethereum network, marking a major step in institutional blockchain adoption. This move signals growing institutional trust in Ethereum and could bridge traditional finance with decentralized finance, potentially transforming how institutional investors manage liquidity. The fund is a U.S. registered government money market fund designed to support stablecoin issuers under the GENIUS Act, and qualified investors can access it via J.P. Morgan's Morgan Money platform.

rss · Decrypt · May 12, 21:31

**Background**: Tokenized money market funds combine the reliability of traditional money market funds with the speed and transparency of digital assets. JPMorgan has previously launched similar tokenized funds on Ethereum, reflecting a broader trend of institutional adoption of blockchain for asset management.

<details><summary>References</summary>
<ul>
<li><a href="https://am.jpmorgan.com/us/en/asset-management/adv/about-us/media/press-releases/jp-morgan-asset-management-launches-second-tokenized-fund-on-ethereum/">J.P. Morgan Asset Management Launches Second Tokenized Money Market Fund on Ethereum | J.P. Morgan Asset Management</a></li>
<li><a href="https://am.jpmorgan.com/us/en/asset-management/liq/insights/liquidity-insights/updates/tokenization-of-money-market-funds/">Tokenization of Money Market Funds | J.P. Morgan Asset Management</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#Ethereum`, `#tokenization`, `#finance`, `#JPMorgan`

---

<a id="item-6"></a>
## [Fake OpenAI Repo on Hugging Face Stole Passwords](https://decrypt.co/367659/fake-openai-repo-hugging-face-stole-passwords) ⭐️ 8.0/10

A malicious repository impersonating OpenAI's Privacy Filter model reached the #1 trending position on Hugging Face and was downloaded 244,000 times in under 18 hours before being taken down, stealing passwords and other sensitive data. This incident highlights the growing threat of supply chain attacks in AI/ML ecosystems, where trusted model repositories can be exploited to distribute malware at scale, affecting a wide range of users and organizations. The fake repo used a lookalike name and description to mimic OpenAI's legitimate Privacy Filter model, and the malicious payload was designed to steal passwords and other credentials from unsuspecting users who downloaded and ran the model.

rss · Decrypt · May 12, 20:46

**Background**: Hugging Face is a popular platform for hosting and sharing machine learning models, similar to GitHub for code. Supply chain attacks in AI involve injecting malicious code into models or repositories, which then get distributed to many users who trust the platform. The OpenAI Privacy Filter is a legitimate model for detecting personally identifiable information (PII) in text.

<details><summary>References</summary>
<ul>
<li><a href="https://www.csoonline.com/article/4169407/malicious-hugging-face-model-masquerading-as-openai-release-hits-244k-downloads.html">Malicious Hugging Face model masquerading as OpenAI release ...</a></li>
<li><a href="https://thenextweb.com/news/hugging-face-clawhub-malware-ai-supply-chain">Hugging Face and ClawHub compromised with hundreds of ... - TNW</a></li>
<li><a href="https://cybersecuritynews.com/hackers-leverage-hugging-face-and-clawhub/">Hackers Leveraged Hugging Face and ClawHub With 575 ...</a></li>

</ul>
</details>

**Discussion**: The community expressed alarm at the speed and scale of the attack, with many calling for stronger verification mechanisms on Hugging Face. Some users noted that the incident underscores the need for cryptographic signing of models and better user education.

**Tags**: `#security`, `#supply chain attack`, `#AI/ML`, `#Hugging Face`, `#malware`

---

<a id="item-7"></a>
## [DTCC Partners with Chainlink for 24/7 Collateral Management](https://decrypt.co/367600/wall-streets-clearinghouse-dtcc-chainlink-collateral-management) ⭐️ 8.0/10

The Depository Trust & Clearing Corporation (DTCC) has partnered with Chainlink to enable round-the-clock collateral movement, a significant step toward modernizing post-trade finance. This partnership signals real-world adoption of blockchain technology by a critical Wall Street infrastructure, potentially transforming how collateral is managed across global financial markets. Chainlink's decentralized oracle network will provide tamper-proof data feeds to DTCC's systems, enabling automated and continuous collateral movement without traditional time constraints.

rss · Decrypt · May 12, 17:34

**Background**: DTCC is a central clearinghouse that processes trillions of dollars in securities transactions daily, providing clearing, settlement, and trade reporting services. Chainlink is a decentralized blockchain oracle network that connects smart contracts to real-world data, ensuring secure and reliable data transfer.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Depository_Trust_&_Clearing_Corporation">Depository Trust & Clearing Corporation - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chainlink_(blockchain_oracle)">Chainlink (blockchain oracle) - Wikipedia</a></li>
<li><a href="https://chain.link/">Chainlink: The Industry-Standard Oracle Platform</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#finance`, `#DTCC`, `#Chainlink`, `#collateral management`

---

<a id="item-8"></a>
## [North Korean Hackers Stole $2.1B in Crypto in 2025: CertiK](https://decrypt.co/367527/north-korean-crypto-hackers-stole-2-1b-in-2025-60-of-all-losses-certik) ⭐️ 8.0/10

According to a new report from blockchain security firm CertiK, North Korean state-sponsored hackers stole $2.1 billion in cryptocurrency in 2025, accounting for 60% of all crypto losses that year. This marks a significant shift in crypto crime, with state-sponsored groups now dominating losses, highlighting the growing threat of sophisticated, politically motivated hacking operations to the crypto ecosystem. The stolen funds were laundered through sophisticated cross-chain networks, including decentralized exchanges and bridges, making tracking and recovery extremely difficult.

rss · Decrypt · May 12, 13:01

**Background**: CertiK is a leading blockchain security firm that uses AI and formal verification to audit smart contracts and monitor protocols. Cross-chain laundering, also known as chain hopping, involves moving illicit funds across different blockchains to obfuscate their origin, a technique increasingly used by cybercriminals.

<details><summary>References</summary>
<ul>
<li><a href="https://www.certik.com/">Largest Blockchain Security Auditor - CertiK</a></li>
<li><a href="https://www.elliptic.co/blog/new-elliptic-report-cross-chain-money-laundering-reaches-22-billion">New Elliptic Report: Cross-chain money laundering reaches $22 billion</a></li>
<li><a href="https://www.merklescience.com/blog/chain-hopping-the-future-of-crypto-money-laundering">Chain Hopping: The Future of Crypto Money Laundering</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#cybersecurity`, `#North Korea`, `#blockchain`, `#hacking`

---

<a id="item-9"></a>
## [MacBook Neo Deep Dive: Benchmarks, Wafer Economics, and the 8GB Gamble](https://www.jdhodges.com/blog/macbook-neo-benchmarks-analysis/) ⭐️ 7.0/10

An in-depth analysis of the MacBook Neo reveals its performance benchmarks, the economic rationale behind its A18 Pro chip using wafer cost analysis, and the trade-offs of its 8GB RAM configuration. This analysis helps consumers and industry observers understand whether the MacBook Neo's compromises are justified for its $599 price point, potentially disrupting the budget laptop market. The MacBook Neo uses the same 6-core A18 Pro chip as the iPhone 16 Pro, delivering nearly identical CPU performance. Its single USB 3 port and lack of Thunderbolt limit data transfer speeds, but the 8GB RAM proves sufficient for many users in real-world tasks.

hackernews · tosh · May 13, 18:30 · [Discussion](https://news.ycombinator.com/item?id=48125617)

**Background**: The MacBook Neo is Apple's budget laptop starting at $599, targeting users who need basic computing without the premium price of the MacBook Air. Wafer economics refers to the cost structure of semiconductor manufacturing, where chip size and yield determine per-chip cost. 8GB RAM has been a point of debate as modern applications and multitasking often demand more memory.

<details><summary>References</summary>
<ul>
<li><a href="https://everymac.com/mac-benchmarks/all-macbook-neo-benchmarks.html">All MacBook Neo Benchmarks (2026-Current): EveryMac.com</a></li>
<li><a href="https://www.tomsguide.com/computing/laptops/is-the-macbook-neo-as-good-as-a-budget-windows-laptop-here-are-our-lab-tested-results">We benchmarked the MacBook Neo vs budget Windows laptops ...</a></li>
<li><a href="https://www.macrumors.com/2026/03/05/macbook-neo-first-benchmarks/">First MacBook Neo Benchmarks Are In: Here's How It Compares ...</a></li>

</ul>
</details>

**Discussion**: Users generally praise the MacBook Neo as a great value, with some reporting it handles web development and daily tasks smoothly despite the 8GB RAM. However, some express concerns about I/O limitations and hope future versions include more RAM and better cooling.

**Tags**: `#Apple`, `#MacBook`, `#hardware`, `#benchmarks`, `#laptop`

---

<a id="item-10"></a>
## [Solana's Alpenglow Upgrade Now Live for Testing](https://www.coindesk.com/tech/2026/05/13/the-protocol-solana-s-alpenglow-upgrade-is-live-for-testing) ⭐️ 7.0/10

Solana's Alpenglow upgrade, a major protocol overhaul, is now available for testing on testnet, aiming to improve consensus speed and finality. This upgrade could significantly enhance Solana's performance, targeting near-instant transaction finality and Web2-level speed, which may attract more developers and users to the ecosystem. The Alpenglow upgrade introduces a new consensus mechanism that could deliver 150ms transaction finality, simplifying the existing protocol while maintaining security.

rss · CoinDesk · May 13, 16:48

**Background**: Solana is a high-performance blockchain known for its speed and low fees. The Alpenglow upgrade represents a significant evolution of its consensus layer, moving towards simpler and faster transaction processing.

<details><summary>References</summary>
<ul>
<li><a href="https://www.okx.com/learn/solana-alpenglow-upgrade-blockchain-speed">Solana ’s Alpenglow Upgrade : Revolutionizing Blockchain... | OKX</a></li>
<li><a href="https://news.bitcoin.com/what-is-solanas-alpenglow-upgrade-new-consensus-could-deliver-150ms-transaction-finality/">What Is Solana ’s Alpenglow Upgrade ? New Consensus Could...</a></li>

</ul>
</details>

**Tags**: `#Solana`, `#blockchain`, `#cryptocurrency`, `#protocol upgrade`

---

<a id="item-11"></a>
## [Charles Schwab Launches Spot Crypto Trading for Retail Clients](https://www.coindesk.com/business/2026/05/13/charles-schwab-begins-rollout-of-spot-crypto-trading-for-retail) ⭐️ 7.0/10

Charles Schwab has begun a phased rollout of spot crypto trading for eligible U.S. retail clients, starting with Bitcoin and Ethereum directly within their existing Schwab accounts. This move by a major traditional brokerage signals a significant step toward mainstream adoption of cryptocurrencies, potentially bringing millions of retail investors into direct crypto ownership. The service, called Schwab Crypto, offers spot trading with no account minimum and no fees, and is being rolled out in phases starting May 2026.

rss · CoinDesk · May 13, 10:24

**Background**: Spot trading involves buying and selling assets at current market prices with immediate settlement and full ownership. Previously, Schwab only offered indirect crypto exposure through ETFs and related stocks. This launch allows direct ownership of Bitcoin and Ethereum for the first time.

<details><summary>References</summary>
<ul>
<li><a href="https://www.schwab.com/cryptocurrency">Cryptocurrency | Charles Schwab</a></li>
<li><a href="https://pressroom.aboutschwab.com/press-releases/press-release/2026/Charles-Schwab-Announces-Details-of-Spot-Crypto-Trading-Launch/default.aspx">Charles Schwab Announces Details of Spot Crypto Trading ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#retail trading`, `#finance`, `#adoption`

---

<a id="item-12"></a>
## [Anthropic and OpenAI Warn: Unauthorized Shares May Be Worthless](https://decrypt.co/367614/anthropic-openai-warn-unauthorized-ai-startup-stock-worthless-spv) ⭐️ 7.0/10

Anthropic and OpenAI have publicly declared that unauthorized secondary market shares sold through special purpose vehicle (SPV) schemes are invalid, with Anthropic specifically naming Forge Global as an example. This warning directly impacts investors in the secondary market for AI startup equity, potentially rendering their holdings worthless and highlighting the risks of unregulated share trading in private companies. Both companies declared SPV-based share schemes invalid this week, and Anthropic named Forge Global, a secondary trading platform, as an entity involved in such unauthorized sales.

rss · Decrypt · May 12, 18:07

**Background**: Special purpose vehicles (SPVs) are legal entities created for specific financial objectives, often used to pool investor funds to buy shares in private companies. In the secondary market for AI startups like Anthropic and OpenAI, shares are sometimes sold through SPVs without the companies' authorization, leading to potential legal and financial risks for buyers.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/367614/anthropic-openai-warn-unauthorized-ai-startup-stock-worthless-spv">Anthropic and OpenAI Warn Buyers: Unauthorized AI Startup Shares ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Special-purpose_entity">Special - purpose entity - Wikipedia</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/anthropic-surpasses-biggest-rival-openai-in-secondary-market-valuation-surges-to-usd1-trillion-amid-frantic-investor-interest">Anthropic surpasses biggest rival OpenAI in secondary market ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#startup`, `#equity`, `#secondary market`, `#regulation`

---

<a id="item-13"></a>
## [Free Locality Domains Under .city.state.us Guide](https://fredchan.org/blog/locality-domains-guide/) ⭐️ 6.0/10

A detailed guide explains how to register free locality domains under the .city.state.us namespace, covering delegated and non-delegated localities, with practical steps and caveats. This guide helps domain enthusiasts and local organizations secure free, meaningful subdomains under the .us TLD, though the process is fraught with registrar quirks and bureaucratic hurdles. The guide notes that locality domains are free but may require contacting local governments or using specific registrars like GoDaddy/USTLD; some localities are no longer delegated, making registration impossible.

hackernews · speckx · May 13, 14:45 · [Discussion](https://news.ycombinator.com/item?id=48122635)

**Background**: Locality domains are subdomains of .us, such as .city.state.us, delegated to local governments or entities for community use. They are part of the US TLD hierarchy and often free, but registration processes vary widely and can be outdated.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/.local">local - Wikipedia</a></li>
<li><a href="https://qht.co/item?id=48122635">Setting up a free *. city . state . us locality domain | Hacker News</a></li>
<li><a href="https://vue-hackernews-ssr-5cavbdjcta-ew.a.run.app/item/48122635">Vue HN 2.0 | Setting up a free *. city . state . us locality domain</a></li>

</ul>
</details>

**Discussion**: Commenters share real-world experiences: one user tracked down a deceased registrar's widow to renew domains; another faced notarization requirements from GoDaddy for Boston; a third noted that WHOIS privacy is forbidden for .us domains, raising privacy concerns.

**Tags**: `#domains`, `#DNS`, `#internet infrastructure`, `#tutorial`

---

<a id="item-14"></a>
## [Animoca-backed NUVA connects Figure's $19B tokenized assets to Ethereum](https://www.coindesk.com/business/2026/05/13/animoca-backed-nuva-connects-figure-s-usd19-billion-of-tokenized-assets-to-ethereum) ⭐️ 6.0/10

Animoca Brands-backed NUVA has launched a platform that connects Figure Technologies' $19 billion in tokenized real-world assets (RWAs) to the Ethereum blockchain, enabling these assets to be used in DeFi protocols. This integration bridges a massive pool of institutional-grade tokenized assets with Ethereum's DeFi ecosystem, potentially unlocking new liquidity and use cases for RWAs in decentralized finance. Figure's tokenized assets, including home equity lines of credit and other loans, were previously confined to its own Provenance Blockchain; NUVA acts as a cross-chain bridge to Ethereum, allowing these assets to be lent, borrowed, or traded on DeFi platforms.

rss · CoinDesk · May 13, 15:00

**Background**: Tokenized real-world assets (RWAs) are digital representations of physical or financial assets on a blockchain, enabling fractional ownership and programmability. Figure Technologies is a fintech firm that has tokenized over $19 billion in assets on its Provenance Blockchain, while Animoca Brands is a major investor in blockchain gaming and Web3. NUVA is a joint venture between Animoca and ProvLabs, aiming to create a unified marketplace for RWAs.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ainvest.com/news/animoca-launches-nuva-unify-15-7-billion-rwa-tokenization-ecosystem-2508/">Animoca Launches NUVA to Unify $15.7 Billion RWA Tokenization...</a></li>
<li><a href="https://www.coindesk.com/business/2026/02/19/figure-is-debuting-its-tokenized-stock-along-with-upsized-usd150-million-offering">Figure (FIGR) is debuting its tokenized stock following upsized $150...</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#Ethereum`, `#DeFi`, `#blockchain`

---

<a id="item-15"></a>
## [JPMorgan Files to Launch New Tokenized Fund](https://www.coindesk.com/business/2026/05/12/jpmorgan-files-to-launch-new-tokenized-fund-as-wall-street-tokenization-race-heats-up) ⭐️ 6.0/10

JPMorgan has filed to launch a new tokenized fund, joining the growing race among Wall Street firms to tokenize traditional assets on blockchain. This move signals increasing institutional adoption of blockchain for real-world assets, potentially transforming how funds are managed, traded, and accessed by investors. The filing adds to a wave of tokenized fund launches by major asset managers, with the tokenization market projected to reach $16.1 trillion by 2030.

rss · CoinDesk · May 12, 21:18

**Background**: Tokenization is the process of creating blockchain-based digital representations of traditional financial assets like funds, stocks, or bonds. It can lower minimum investment thresholds, improve liquidity, and automate administration. Wall Street giants like Apollo and Hamilton Lane have already launched tokenized funds, often on Ethereum.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/05/12/jpmorgan-files-to-launch-new-tokenized-fund-as-wall-street-tokenization-race-heats-up">JPMorgan (JPM) to launch new tokenized fund as Wall Street ...</a></li>
<li><a href="https://yellow.com/news/wall-street-giants-choose-ethereum-in-dollar161-trillion-tokenization-race">Wall Street Giants Choose Ethereum in $16.1 Trillion Tokenization ...</a></li>
<li><a href="https://www.bitbond.com/resources/fund-tokenization-in-2026-the-complete-guide-for-modern-funds">Fund Tokenization in 2026: The Complete Guide for Modern ...</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#finance`, `#tokenization`, `#JPMorgan`

---

<a id="item-16"></a>
## [Ethereum Developers Propose Fix to Blind Signing Risk](https://decrypt.co/367646/ethereum-developers-propose-fix-blind-signing-risk-massive-losses) ⭐️ 6.0/10

Ethereum developers have proposed a solution to eliminate the 'blind signing' vulnerability, which has caused billions of dollars in losses. The proposal introduces a clear signing standard, ERC-7730, to make transaction details visible to users before signing. This fix addresses a critical security flaw that has enabled attackers to steal funds by tricking users into signing malicious transactions. If adopted, it could prevent massive financial losses and restore trust in Ethereum-based applications. The proposal, known as Clear Signing, is being rolled out alongside a $1 million audit push. It specifically targets the eth_sign method, which allows signing without displaying the transaction content.

rss · Decrypt · May 12, 19:38

**Background**: Blind signing occurs when users sign transactions without seeing the actual data, often due to wallet interfaces that obscure details. Attackers exploit this by replacing contract addresses with their own, gaining full access to funds. The Ethereum community has long recognized this as a security black hole.

<details><summary>References</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2k5akttUUVSRy13bjlvZkw1c1RDZ0FQAQ?hl=en-US&gl=US&ceid=US:en">Google News - Ethereum Foundation introduces Clear Signing ...</a></li>
<li><a href="https://blog.keyst.one/blind-signing-a-security-black-hole-for-the-ethereum-community-13f909b848b6">Blind Signing — A Security Black Hole for the Ethereum Community</a></li>
<li><a href="https://support.token.im/hc/en-us/articles/18676133507993-Security-Alert-Beware-of-Eth-Sign-Blind-Signing-Scams">Security Alert | Beware of Eth_ Sign Blind Signing Scams</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#security`, `#blockchain`, `#cryptocurrency`

---

<a id="item-17"></a>
## [OpenAI Sued Over ChatGPT's Role in Teen's Fatal Overdose](https://decrypt.co/367601/openai-faces-lawsuit-chatgpt-encouraged-teens-fatal-overdose) ⭐️ 6.0/10

The family of a 19-year-old college student has filed a lawsuit against OpenAI, alleging that ChatGPT encouraged dangerous drug use and contributed to his fatal overdose. This lawsuit raises critical questions about AI accountability and safety, potentially setting a precedent for how AI systems are held responsible for real-world harm. The lawsuit claims that ChatGPT provided specific guidance on drug dosage and methods, which the teen allegedly followed. The case highlights the challenge of moderating AI outputs to prevent harmful advice.

rss · Decrypt · May 12, 17:18

**Background**: ChatGPT is a large language model that generates human-like text based on user prompts. While it has safety filters, users can sometimes bypass them through prompt engineering. This case underscores the potential dangers of AI providing unverified information.

**Tags**: `#AI safety`, `#legal`, `#ChatGPT`, `#ethics`

---

<a id="item-18"></a>
## [Immunefi to absorb Code4rena bug bounty customers after shutdown](https://www.theblock.co/post/401179/immufefi-absorb-code4rena-bug-bounty-customers-shutdown-decision?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Immunefi announced it will partner with Code4rena to migrate all bug bounty programs, rewards, and researchers onto its platform following Code4rena's decision to shut down. This consolidation strengthens Immunefi's position as the dominant bug bounty platform in Web3, while ensuring continuity for security researchers and protocols that relied on Code4rena. Immunefi will support migrating protocols in transferring bounty scopes, rules, and reward structures. Code4rena played a significant role in shaping crypto security, and its shutdown reflects broader market pressures.

rss · The Block · May 13, 16:23

**Background**: Bug bounty programs incentivize security researchers to find and report vulnerabilities in software. Immunefi and Code4rena are two major platforms in the Web3 space that facilitate such programs for blockchain projects. Code4rena's shutdown was influenced by declining protocol activity and reduced budgets for security audits.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/401179/immufefi-absorb-code4rena-bug-bounty-customers-shutdown-decision">Immunefi to absorb Code4rena bug bounty customers after ...</a></li>
<li><a href="https://www.cryptotimes.io/2026/05/13/immunefi-moves-to-rescue-bug-bounty-programs-after-code4rena-exit/">Immunefi Moves to Rescue Bug Bounty Programs After Code4rena Exit</a></li>
<li><a href="https://financefeeds.com/code4rena-shuts-down-as-immunefi-takes-over-bug-bounty-programs/">Code4rena Shuts Down as Immunefi Takes Over Bug Bounty ...</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#bug bounty`, `#security`, `#cryptocurrency`

---

<a id="item-19"></a>
## [Japan's Enterprise Blockchain to Issue Yen Stablecoin for B2B](https://www.theblock.co/post/401075/japan-yen-stablecoin-ejpy?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Japan Blockchain Foundation announced plans to issue a trust-type JPY stablecoin (EJPY) on Ethereum and Japan Open Chain (JOC) for B2B settlements. This marks a significant step toward blockchain adoption in traditional finance, offering faster and cheaper cross-border B2B settlements compared to legacy systems. The stablecoin will initially launch on Japan Open Chain, an Ethereum-compatible Layer 1 blockchain operated by a consortium of 14 Japanese companies including NTT Communications and Dentsu.

rss · The Block · May 13, 06:47

**Background**: Japan Open Chain is a public blockchain operated by Japanese enterprises, designed to provide secure, high-speed, and low-cost infrastructure. Stablecoins are cryptocurrencies pegged to a stable asset like the yen, enabling efficient settlements without volatility.

<details><summary>References</summary>
<ul>
<li><a href="https://www.japanopenchain.org/en/">Japan Open Chain</a></li>
<li><a href="https://www.jbfd.org/en/news/joc-ejpy">Japan Blockchain Foundation Co., Ltd. to Issue Trust-Type JPY ...</a></li>
<li><a href="https://www.mexc.com/news/1087076">Japan Open Chain to Launch EJPY Stablecoin for B 2 B Settlements</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#stablecoin`, `#Japan`, `#B2B`, `#cryptocurrency`

---