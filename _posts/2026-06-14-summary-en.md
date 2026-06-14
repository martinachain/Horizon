---
layout: default
title: "Horizon Summary: 2026-06-14 (EN)"
date: 2026-06-14
lang: en
---

> From 67 items, 16 important content pieces were selected

---

1. [Honda Civic Headunit Updates Signed with AOSP Test Keys](#item-1) ⭐️ 8.0/10
2. [Census Bureau Bans Noise Infusion for Statistical Products](#item-2) ⭐️ 8.0/10
3. [GLM 5.2 Released as Fully Open Frontier Model](#item-3) ⭐️ 8.0/10
4. [Critique of Imperfect UI Animation Frames](#item-4) ⭐️ 8.0/10
5. [Pancreatic cancer treatment may reveal cancer's master switch](#item-5) ⭐️ 8.0/10
6. [Amazon CEO's Talks Led to US Crackdown on Anthropic AI](#item-6) ⭐️ 8.0/10
7. [Google Sues Chinese Crime Group Over Gemini AI Phishing](#item-7) ⭐️ 8.0/10
8. [AI Agents Still Vulnerable to Prompt Injection Attacks](#item-8) ⭐️ 8.0/10
9. [Cryptographers Split on Bitcoin Quantum Threat](#item-9) ⭐️ 7.0/10
10. [Coinbase report warns address reuse exposes millions of BTC to quantum risk](#item-10) ⭐️ 7.0/10
11. [Lost Game Boy WorkBoy Add-On Recovered After 28 Years](#item-11) ⭐️ 6.0/10
12. [Wall Street Moves Beyond Crypto Pilots into Ethereum](#item-12) ⭐️ 6.0/10
13. [US Government Bets $2B on Quantum Computing, Defense Lags](#item-13) ⭐️ 6.0/10
14. [Moonshot AI's Kimi Work Brings 300 AI Agents to Your Desktop](#item-14) ⭐️ 6.0/10
15. [Exodus and Ondo Launch Tokenized Stocks & ETFs on Solana](#item-15) ⭐️ 6.0/10
16. [South Korea: Tokenized stocks are securities, not crypto](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Honda Civic Headunit Updates Signed with AOSP Test Keys](https://juniperspring.org/posts/honda-evil-valet/) ⭐️ 8.0/10

A security researcher discovered that firmware updates for 10th-generation Honda Civic headunits are signed with publicly-known AOSP test keys, enabling arbitrary code execution via USB with physical access. This vulnerability affects a popular consumer vehicle and highlights systemic software security weaknesses in the automotive industry, where manufacturers often lack rigorous firmware signing practices. The updates are essentially Android 4.2.2rc1 recovery packages with Honda-specific version checks that can be spoofed, and the use of AOSP test keys means no root access is needed to flash custom packages.

hackernews · librick · Jun 14, 00:49 · [Discussion](https://news.ycombinator.com/item?id=48523080)

**Background**: AOSP test keys are default signing keys included in the Android Open Source Project for development purposes only and should never be used in production devices. Honda's 10th-gen Civic headunit runs a custom Android-based system that accepts firmware updates via USB drives formatted with a special layout.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/wfairclough/android_aosp_keys">wfairclough/android_aosp_keys: The platform keys that are used as test ...</a></li>
<li><a href="https://stackoverflow.com/questions/57959598/aosp-building-replace-my-own-keys-with-default-test-keys">AOSP building: replace my own keys with default test-keys - Stack Overflow</a></li>
<li><a href="https://xdaforums.com/t/security-test-keys-vs-release-keys.1937469/">Security: Test keys vs Release Keys - XDA Forums</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed reactions: some criticized Honda's software practices, while others noted that this actually gives owners more control over their vehicles. A few pointed out the broader industry issue of firmware update signature verification being neglected.

**Tags**: `#automotive security`, `#Android`, `#firmware`, `#vulnerability`, `#Honda`

---

<a id="item-2"></a>
## [Census Bureau Bans Noise Infusion for Statistical Products](https://desfontain.es/blog/banning-noise.html) ⭐️ 8.0/10

The U.S. Census Bureau has banned the use of noise infusion, a differential privacy technique, in its statistical products, following a new Department of Commerce administrative order. This policy change weakens privacy protections for census data, potentially allowing re-identification of individuals and eroding public trust in government data collection. The ban applies to both the Census Bureau and the Bureau of Economic Analysis, forcing them to rely on alternative methods like aggregation and rounding instead of noise infusion.

hackernews · nl · Jun 13, 13:54 · [Discussion](https://news.ycombinator.com/item?id=48517377)

**Background**: Noise infusion adds small random variations to data to prevent identification of individuals while preserving statistical accuracy. Differential privacy, a formal framework for privacy protection, has been used by the Census Bureau since the 2020 Census to guard against reconstruction attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bea.gov/help/faq/1490">Why didn't BEA use noise infusion as its statistical disclosure ...</a></li>
<li><a href="https://www.npr.org/2026/06/12/nx-s1-5855734/census-bureau-data-differential-privacy">Trump privacy restrictions may reduce Census Bureau data : NPR</a></li>
<li><a href="https://www.census.gov/about/policies/privacy/statistical_safeguards.html">Statistical Safeguards</a></li>

</ul>
</details>

**Discussion**: Commenters expressed concern that the ban undermines trust in census data handling, with some noting that powerful actors may already be reconstructing individual data from aggregated statistics. Others argued that damaging data collection infrastructure is a mistake that will harm policy-making.

**Tags**: `#privacy`, `#census`, `#differential privacy`, `#data policy`, `#statistics`

---

<a id="item-3"></a>
## [GLM 5.2 Released as Fully Open Frontier Model](https://twitter.com/jietang/status/2065784751345287314) ⭐️ 8.0/10

Z.ai (formerly Zhipu AI) released GLM 5.2, a fully open frontier model with a 1-million-token context window, under an MIT license, on June 2, 2026. This release challenges US restrictions on AI models, demonstrating that open-weight models can remain accessible and competitive, with significant geopolitical implications for AI development. GLM 5.2 is a coding-first model with a 1M usable context window (5x jump from GLM 5.1's 200K), and its weights are released under a permissive MIT open-source license.

hackernews · aloknnikhil · Jun 13, 16:18 · [Discussion](https://news.ycombinator.com/item?id=48518684)

**Background**: Frontier models are the most advanced general-purpose AI models, often requiring enormous computational resources. Z.ai is a Chinese AI company that develops the GLM family of large language models. The release comes amid US government restrictions on certain frontier models, such as the 'Fable 5' incident, which have sparked debate about open science and AGI accessibility.

<details><summary>References</summary>
<ul>
<li><a href="https://codersera.com/blog/glm-5-2-release-1m-context-coding-2026/">GLM 5.2 Release — 1M Context, Coding-First (June 2026)</a></li>
<li><a href="https://github.com/47thtechcorner/RayCodes_GLM_5.2">47thtechcorner/RayCodes_GLM_5.2 - GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Z.ai">Z.ai - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community praised Z.ai for releasing GLM 5.2 openly, contrasting it with US censorship of models like Fable. Commenters noted the timing (same day as Anthropic's restriction) and highlighted the value of open-weight models for ensuring access to strategic AI capabilities.

**Tags**: `#AI`, `#open source`, `#GLM`, `#geopolitics`, `#frontier models`

---

<a id="item-4"></a>
## [Critique of Imperfect UI Animation Frames](https://tonsky.me/blog/every-frame-perfect/) ⭐️ 8.0/10

A blog post titled 'Every Frame Perfect' by Tonsky provides a detailed critique of imperfect frames in UI animations, using macOS examples to argue that even subtle glitches degrade user experience. This matters because it challenges the common practice of tolerating minor animation imperfections, potentially influencing UI/UX design standards and raising the bar for software quality. The author provides specific examples from macOS, such as shaky save dialogs and glitchy button animations, and argues that every frame should make sense visually, even during transitions.

hackernews · ravenical · Jun 13, 11:40 · [Discussion](https://news.ycombinator.com/item?id=48516251)

**Background**: UI animations are used to provide visual feedback and smooth transitions in software interfaces. However, due to performance constraints or implementation issues, some frames may appear incorrect or jarring, which can detract from the user experience.

**Discussion**: Comments show mixed reactions: some agree with the critique but question the premise, arguing that motion perception differs from static analysis; others note that many animations are unnecessary and could be replaced with instant transitions.

**Tags**: `#UI/UX`, `#animation`, `#macOS`, `#software engineering`

---

<a id="item-5"></a>
## [Pancreatic cancer treatment may reveal cancer's master switch](https://economist.com/science-and-technology/2026/06/12/treating-pancreatic-tumours-may-have-revealed-cancers-master-switch) ⭐️ 8.0/10

A new targeted therapy for pancreatic cancer, focusing on KRAS mutations previously considered undruggable, has shown promising early results in clinical trials. The treatment specifically targets KRAS G12D mutations, which are present in about 90% of pancreatic cancers. This breakthrough could transform treatment for pancreatic cancer, one of the deadliest cancers with a five-year survival rate below 10%. It also demonstrates that previously 'undruggable' targets like KRAS can be tackled, opening doors for therapies against other hard-to-treat cancers. The therapy applies to about 20% of all tumors that harbor KRAS mutations, not all cancers. The study referenced is a clinical trial (NCT06625320) evaluating a KRAS G12D inhibitor or degrader, with manageable safety profiles and promising efficacy in early-phase studies.

hackernews · andsoitis · Jun 13, 13:34 · [Discussion](https://news.ycombinator.com/item?id=48517199)

**Background**: KRAS is a gene that produces a protein involved in cell growth signaling. Mutations in KRAS are found in many cancers, including pancreatic, lung, and colorectal cancers, but for decades it was considered 'undruggable' due to its smooth surface and high affinity for GTP, making it difficult to target with conventional drugs. Recent advances in drug design, such as covalent inhibitors and targeted protein degraders, have enabled the development of therapies that can bind to mutant KRAS and block its activity.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41392-021-00780-4">KRAS mutation: from undruggable to druggable in cancer - Nature</a></li>
<li><a href="https://www.mskcc.org/news/new-kras-targeted-therapy-shows-promise-against-pancreatic">New KRAS Targeted Therapy Shows Promise Against Pancreatic Cancer</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the title is hyperbolic, as the discovery applies to only 20% of tumors, but acknowledged it as a significant step. One user emphasized that KRAS was long considered undruggable, and this breakthrough broadens horizons for future treatments. Another shared a personal story of losing a family member to pancreatic cancer, highlighting the need for better diagnostics and early detection.

**Tags**: `#cancer research`, `#KRAS`, `#pancreatic cancer`, `#drug discovery`, `#biotechnology`

---

<a id="item-6"></a>
## [Amazon CEO's Talks Led to US Crackdown on Anthropic AI](https://www.wsj.com/tech/ai/amazon-ceos-talks-with-u-s-officials-triggered-crackdown-on-anthropic-models-dcc90578?st=Yct6gx&reflink=desktopwebshare_permalink) ⭐️ 8.0/10

The Trump administration halted foreign use of Anthropic's most-capable AI models after Amazon CEO Andy Jassy raised security concerns with U.S. officials. This raises questions about the influence of corporate interests on AI regulation and highlights tensions between national security and open AI development. Anthropic pushed back against the government's action, calling it an overreach. The specific models affected and the exact security concerns have not been publicly detailed.

hackernews · ls612 · Jun 13, 16:57 · [Discussion](https://news.ycombinator.com/item?id=48519092)

**Background**: Anthropic is an AI safety company known for its Claude family of large language models. Amazon has invested heavily in Anthropic and is a key partner. The Trump administration has taken a more aggressive stance on AI regulation, particularly regarding foreign access to advanced models.

<details><summary>References</summary>
<ul>
<li><a href="https://www.wsj.com/tech/ai/amazon-ceos-talks-with-u-s-officials-triggered-crackdown-on-anthropic-models-dcc90578">Amazon CEO's Talks With U.S. Officials Triggered Crackdown on ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(language_model)">Claude (language model) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed skepticism about the rationale, noting that all LLMs are jailbreakable and questioning whether the action was motivated by business interests rather than genuine security concerns. Some pointed out Amazon's financial ties to Anthropic, suggesting the move may be less sinister than it appears.

**Tags**: `#AI regulation`, `#Anthropic`, `#Amazon`, `#government policy`, `#LLM safety`

---

<a id="item-7"></a>
## [Google Sues Chinese Crime Group Over Gemini AI Phishing](https://decrypt.co/371014/google-sues-chinese-crime-group-gemini-ai-phishing-scams) ⭐️ 8.0/10

Google filed a lawsuit against a Chinese crime group for allegedly using its Gemini AI to automate mass phishing campaigns, creating over 9,000 fake websites and stealing millions of credit card numbers. This case highlights the growing threat of generative AI being weaponized for cybercrime, and sets a legal precedent for holding AI providers accountable for misuse of their technology. The scammers used Gemini to generate code for fake gift redemption and brand impersonation pages, which were then loaded into a phishing platform to target U.S. victims, including crypto investors.

rss · Decrypt · Jun 13, 16:01

**Background**: Phishing is a cyberattack where attackers trick victims into revealing sensitive information via fake messages or websites. AI-powered phishing uses generative models to create more convincing and scalable attacks, lowering the barrier for low-skill operators.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/371014/google-sues-chinese-crime-group-gemini-ai-phishing-scams">Google Sues Chinese Crime Group for Allegedly Using Gemini AI for Mass Phishing Scams - Decrypt</a></li>
<li><a href="https://www.digitaltrends.com/phones/scammers-used-gemini-ai-to-power-a-massive-phishing-operation-and-google-just-sued-them/">Scammers used Gemini AI to power a massive phishing operation and Google just sued them - Digital Trends</a></li>
<li><a href="https://www.techtimes.com/articles/318273/20260612/google-sues-scam-ring-that-used-gemini-ai-flood-phones-fake-texts.htm">Google Sues Scam Ring That Used Gemini AI to Flood Phones With Fake Texts</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#cybersecurity`, `#phishing`, `#Google`, `#generative AI`

---

<a id="item-8"></a>
## [AI Agents Still Vulnerable to Prompt Injection Attacks](https://decrypt.co/370972/ai-agents-prompt-injection-attacks-research) ⭐️ 8.0/10

A new benchmark study reveals that AI agents remain susceptible to prompt injection attacks, despite increasing public deployment of the technology. This ongoing vulnerability poses significant security risks as AI agents are integrated into more applications, potentially allowing attackers to manipulate agent behavior and access sensitive data. Prompt injection attacks exploit the model's inability to distinguish between trusted instructions and untrusted user inputs, leading to unintended actions. The study highlights that current defenses remain insufficient against these attacks.

rss · Decrypt · Jun 12, 19:22

**Background**: Prompt injection is a cybersecurity exploit targeting large language models (LLMs) by crafting malicious inputs that cause unintended behavior. AI agents, which use LLMs to perform autonomous tasks, are particularly vulnerable because they often have access to external tools and data. As companies deploy AI agents publicly, securing them against such attacks becomes critical.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection">Prompt injection - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#prompt injection`, `#AI agents`, `#vulnerability`

---

<a id="item-9"></a>
## [Cryptographers Split on Bitcoin Quantum Threat](https://www.coindesk.com/tech/2026/06/13/top-cryptographers-can-t-agree-on-bitcoin-s-biggest-quantum-question) ⭐️ 7.0/10

Leading cryptographers are publicly disagreeing on whether quantum computing poses an imminent threat to Bitcoin's cryptographic foundations, as highlighted in a recent Coindesk article. The debate centers on the timeline and severity of potential attacks on Bitcoin's elliptic curve digital signature algorithm (ECDSA). This disagreement has significant implications for Bitcoin's future security and the broader cryptocurrency ecosystem, as quantum computing could eventually break the cryptographic primitives securing billions in assets. The outcome of this debate will influence when and how the Bitcoin network might need to upgrade to quantum-resistant algorithms. Google published a paper on March 31, 2026, suggesting quantum computers could break Bitcoin's cryptography sooner than expected, while other experts argue the threat is still decades away. The Bitcoin Improvement Proposal BIP-360 and post-quantum standards are being discussed as potential countermeasures.

rss · CoinDesk · Jun 13, 06:07

**Background**: Bitcoin's security relies on cryptographic algorithms like SHA-256 for proof-of-work and ECDSA for digital signatures, which are considered secure against classical computers. Quantum computers, leveraging quantum mechanics, could theoretically solve the mathematical problems underlying these algorithms much faster, potentially allowing an attacker to forge signatures or reverse transactions. The timeline for building a sufficiently powerful quantum computer remains uncertain, leading to the current debate.

<details><summary>References</summary>
<ul>
<li><a href="https://www.forbes.com/sites/digital-assets/2026/03/31/google-finds-quantum-computers-could-break-bitcoin-sooner-than-expected/">Google Finds Quantum Computers Could Break Bitcoin Sooner ...</a></li>
<li><a href="https://www.btcpolicy.org/articles/state-of-play-quantum-computing-and-bitcoins-path-forward">State of Play: Quantum Computing and Bitcoin's Path Forward</a></li>
<li><a href="https://postquantum.com/post-quantum/quantum-cryptocurrencies-bitcoin/">Quantum Computing Risks to Cryptocurrencies – Bitcoin ...</a></li>

</ul>
</details>

**Tags**: `#cryptography`, `#quantum computing`, `#Bitcoin`, `#blockchain security`

---

<a id="item-10"></a>
## [Coinbase report warns address reuse exposes millions of BTC to quantum risk](https://www.theblock.co/post/404685/coinbase-quantum-report-flags-exchange-cold-wallets-among-millions-of-bitcoin-exposed-by-address-reuse?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Coinbase's Quantum Advisory Council released a report highlighting that address reuse exposes millions of bitcoin, including exchange cold wallets, to quantum computing threats. The report proposes solutions such as setting a migration deadline and freezing vulnerable coins. This matters because quantum computers could potentially crack Bitcoin's elliptic curve cryptography, allowing attackers to steal funds from addresses with exposed public keys. The report's proposals could shape future Bitcoin security standards and affect how exchanges and users manage their wallets. The report estimates that up to 7 million BTC could be at risk due to address reuse, with large amounts sitting in cold wallets of known exchanges. It suggests that a quantum attack could become feasible as early as 2029.

rss · The Block · Jun 13, 18:21

**Background**: Address reuse in Bitcoin refers to using the same address for multiple transactions, which exposes the public key on the blockchain. This is discouraged because it reduces privacy and security; with quantum computing, exposed public keys could be used to derive private keys. Bitcoin's security relies on elliptic curve cryptography, which is vulnerable to Shor's algorithm run on a sufficiently powerful quantum computer.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/404685/coinbase-quantum-report-flags-exchange-cold-wallets-among-millions-of-bitcoin-exposed-by-address-reuse">Coinbase quantum report flags exchange cold wallets among millions of bitcoin exposed by address reuse | The Block</a></li>
<li><a href="https://cryptobriefing.com/coinbase-bitcoin-quantum-risk-cold-wallets/">Coinbase report flags Bitcoin cold wallets exposed to quantum risks</a></li>
<li><a href="https://fortune.com/crypto/2026/04/06/quantum-computing-satoshi-nakamoto-bitcoin-freeze-wallets/">A quantum threat to Bitcoin has some asking the unthinkable: Is it time to freeze old wallets belonging to Satoshi Nakamoto? | Fortune</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#quantum computing`, `#bitcoin security`, `#address reuse`

---

<a id="item-11"></a>
## [Lost Game Boy WorkBoy Add-On Recovered After 28 Years](https://tcrf.net/Workboy) ⭐️ 6.0/10

The unreleased Game Boy WorkBoy hardware add-on and its productivity software have been recovered and documented by preservationists, revealing a PDA-like accessory that was cancelled in the 1990s. This discovery fills a gap in video game history and showcases Nintendo's early attempt to expand the Game Boy beyond gaming into productivity, influencing later handheld devices. The WorkBoy included an address book, appointment reminder, and finance management app, and was intended to connect via a cartridge slot. The software was recovered from a prototype cartridge.

hackernews · tosh · Jun 13, 17:43 · [Discussion](https://news.ycombinator.com/item?id=48519552)

**Background**: The Game Boy was a popular handheld gaming console released by Nintendo in 1989. The WorkBoy was an unreleased add-on that would have turned it into a personal digital assistant (PDA), similar to devices like the Palm Pilot. Its existence was known only through old magazine ads until a prototype was found in 2020.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Game_Boy_accessories">List of Game Boy accessories - Wikipedia</a></li>
<li><a href="https://www.ign.com/articles/a-lost-game-boy-add-on-called-the-workboy-has-been-found-after-28-years">A Lost Game Boy Add-On Called the WorkBoy Has Been Found After 28 Years - IGN</a></li>
<li><a href="https://gameluster.com/game-historian-finds-lost-game-boy-add-on-workboy/">Game Historian Finds Lost Game Boy Add-on, "WorkBoy" | GameLuster</a></li>

</ul>
</details>

**Discussion**: Community comments include a link to a YouTube video about the WorkBoy and a note that the site blocks VPN users, but no deep discussion on the news itself.

**Tags**: `#retro computing`, `#game boy`, `#hardware`, `#preservation`

---

<a id="item-12"></a>
## [Wall Street Moves Beyond Crypto Pilots into Ethereum](https://www.coindesk.com/business/2026/06/13/wall-street-is-moving-past-crypto-pilots-and-deeper-into-ethereum-says-etherealize-founder) ⭐️ 6.0/10

Etherealize founder Vivek Raman stated that Wall Street is moving past crypto pilots and deepening engagement with Ethereum, with stablecoins as the first institutional use case and discussions expanding to tokenized stocks, bonds, and real estate. This signals a shift from experimentation to operational use of public blockchains by major financial institutions, potentially accelerating mainstream adoption of Ethereum-based assets and infrastructure. Etherealize, an institutional marketing and product arm for Ethereum, raised $40 million in September 2025 from Electric Capital and Paradigm, building on an earlier grant from Vitalik Buterin and the Ethereum Foundation.

rss · CoinDesk · Jun 13, 16:00

**Background**: Etherealize was founded in late 2024 by Vivek Raman to drive Ethereum adoption among financial institutions. The company focuses on marketing Ethereum's capabilities for tokenization, stablecoins, and decentralized finance to Wall Street.

<details><summary>References</summary>
<ul>
<li><a href="https://fortune.com/crypto/2025/09/03/etherealize-vivek-raman-ethereum-40-million-paradigm-electric-capital/">Exclusive: Etherealize raises $40 million to expand Wall ...</a></li>
<li><a href="https://www.etherealize.com/about">About - etherealize.com</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#Wall Street`, `#crypto adoption`, `#finance`

---

<a id="item-13"></a>
## [US Government Bets $2B on Quantum Computing, Defense Lags](https://www.coindesk.com/opinion/2026/06/12/the-u-s-government-is-betting-usd2-billion-on-quantum-computing-and-the-defense-side-can-t-keep-up) ⭐️ 6.0/10

The U.S. government has committed $2 billion to quantum computing initiatives, but defense sector adoption is struggling to keep pace with the investment. This investment signals a national priority in quantum technology, yet the defense lag could create vulnerabilities in national security and strategic advantage. The article, published on CoinDesk, highlights a gap between government funding and defense readiness, though specific programs or timelines are not detailed.

rss · CoinDesk · Jun 12, 15:31

**Background**: Quantum computing leverages quantum mechanics principles like superposition and entanglement to solve problems beyond classical computers. Governments worldwide view it as a dual-use technology with applications in cryptography, simulation, and defense. The U.S. has been investing heavily to maintain technological leadership.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Quantum_computing">Quantum computing - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/quantum-computing">What is quantum computing? - IBM</a></li>
<li><a href="https://www.congress.gov/crs_external_products/IF/PDF/IF11836/IF11836.13.pdf">Updated November 4, 2024 Defense Primer: Quantum Technology</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#government funding`, `#defense`, `#technology policy`

---

<a id="item-14"></a>
## [Moonshot AI's Kimi Work Brings 300 AI Agents to Your Desktop](https://decrypt.co/370954/moonshot-ai-kimi-work-300-agents-desktop) ⭐️ 6.0/10

Moonshot AI has launched Kimi Work, a desktop AI agent that operates on local files, browser, and schedule without relying on cloud processing. This marks a significant shift toward local AI agents, enhancing privacy and offline capabilities for knowledge workers, and could challenge cloud-dependent productivity tools. Kimi Work is powered by the Kimi K2.6 model and features a swarm of 300 sub-agents, along with a WebBridge for browser integration.

rss · Decrypt · Jun 12, 18:40

**Background**: Moonshot AI is a Beijing-based AI company known as one of China's 'AI Tiger' firms, focusing on large language models. Desktop AI agents are an emerging trend that prioritize local data processing over cloud dependency, offering improved privacy and offline functionality.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Moonshot_AI">Moonshot AI - Wikipedia</a></li>
<li><a href="https://lushbinary.com/blog/kimi-work-local-ai-agent-knowledge-workers-guide/">Kimi Work: Moonshot's Local AI Agent Guide | Lushbinary</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#desktop`, `#local AI`, `#productivity`

---

<a id="item-15"></a>
## [Exodus and Ondo Launch Tokenized Stocks & ETFs on Solana](https://www.theblock.co/post/404622/exodus-launches-tokenized-markets-200-plus-stocks-etfs-on-solana?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Exodus partnered with Ondo Finance to launch tokenized trading of over 200 stocks and ETFs directly on the Solana blockchain. This expands access to traditional equities through blockchain, enabling 24/7 trading and fractional ownership, and could accelerate the adoption of tokenized real-world assets on Solana. The tokenized assets are backed by securities held at U.S.-registered custodians, and the service is available through Exodus's wallet interface on Solana.

rss · The Block · Jun 12, 13:26

**Background**: Tokenized stocks represent traditional equities on a blockchain, allowing for faster settlement and global access. Ondo Finance specializes in tokenizing real-world assets, and Solana offers low fees and high throughput suitable for trading. Other platforms like xStocks also offer similar services on Solana.

<details><summary>References</summary>
<ul>
<li><a href="https://solana.com/news/case-study-xstocks">xStocks: Tokenizing Equities on Solana | Solana Media</a></li>
<li><a href="https://www.coindesk.com/business/2025/09/03/ondo-finance-rolls-out-tokenized-u-s-stocks-etfs-as-equity-tokenization-ramps-up">RWA News: Ondo Finance Rolls Out Tokenized U.S ... - CoinDesk</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#Solana`, `#DeFi`, `#stocks`, `#blockchain`

---

<a id="item-16"></a>
## [South Korea: Tokenized stocks are securities, not crypto](https://www.theblock.co/post/404580/south-korea-finance-ministry-says-tokenized-stocks-are-securities-not-crypto-assets-opening-door-to-taxes-report?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

South Korea's Ministry of Strategy and Finance has classified tokenized stocks as securities under existing law, potentially enabling taxation as early as the second half of 2026 if regulators agree. This regulatory clarification sets a precedent for how tokenized assets are treated in South Korea, distinguishing them from cryptocurrencies and opening the door to capital gains taxes. It could influence other jurisdictions grappling with similar classification issues. The classification means tokenized stocks will be subject to securities laws and taxation, with potential implementation in H2 2026. The move aligns with South Korea's broader push to regulate tokenized securities, with final guidelines expected in February 2027.

rss · The Block · Jun 12, 11:38

**Background**: Tokenized stocks are digital representations of traditional equities issued on a blockchain, allowing for fractional ownership and faster settlement. South Korea has been developing a legal framework for tokenized securities, with regulators releasing guidelines in July 2026 ahead of final implementation in February 2027.

<details><summary>References</summary>
<ul>
<li><a href="https://www.europesays.com/korea/51588/">South Korea’s Finance Ministry Classifies Tokenized Stocks as ...</a></li>
<li><a href="https://cointelegraph.com/news/south-korea-announce-tokenized-securities-laws-july">South Korea to Announce Tokenized Securities Laws in July</a></li>
<li><a href="https://www.hokanews.com/2026/06/south-korea-classifies-tokenized-stocks.html">South Korea Classifies Tokenized Stocks as Securities ...</a></li>

</ul>
</details>

**Tags**: `#crypto regulation`, `#tokenized securities`, `#South Korea`, `#taxation`

---