---
layout: default
title: "Horizon Summary: 2026-09-13 (EN)"
date: 2026-09-13
lang: en
---

> From 51 items, 16 important content pieces were selected

---

1. [Real-SWE benchmarks AI models on private enterprise codebases](#item-1) ⭐️ 8.0/10
2. [Economist: Nvidia Is the Central Bank of AI](#item-2) ⭐️ 8.0/10
3. [Revolut Exposed Bitcoin Activity and Passports After Fake Government Request](#item-3) ⭐️ 8.0/10
4. [Satirical post mocks AI leaders who urge slowing down AI](#item-4) ⭐️ 7.0/10
5. [Anthropic CEO Urges Slowing AI Race; Musk and Altman Agree](#item-5) ⭐️ 7.0/10
6. [OpenAI Asks Congress Whether an AI Slowdown Would Be Legal](#item-6) ⭐️ 7.0/10
7. [India's SEBI Demat 2.0 Pilot Raises $107M in Tokenized Bonds](#item-7) ⭐️ 7.0/10
8. [JOSM Plugin Wizard Guides First OpenStreetMap Edits](#item-8) ⭐️ 6.0/10
9. [Reform UK Gets $97M From Two Crypto Billionaires in 24 Hours](#item-9) ⭐️ 6.0/10
10. [India's Richest State Explores Tokenizing Assets to Fund Infrastructure](#item-10) ⭐️ 6.0/10
11. [GPT-6 Astra Users Say OpenAI's Newest Model Got Dumber](#item-11) ⭐️ 6.0/10
12. [ChatGPT Images 2.5 vs Nano Banana 2: A Six-Category Comparison](#item-12) ⭐️ 6.0/10
13. [Law Firm Cyberattacks Nearly Double in 2025 as Stolen Files Hit Dark Web](#item-13) ⭐️ 6.0/10
14. [Blockstream Refuses Ransom for $47M in Bitcoin Stolen from Liquid Network](#item-14) ⭐️ 6.0/10
15. [EU Regulator Flags Insider Trading in Prediction Markets](#item-15) ⭐️ 6.0/10
16. [Albuquerque Bans Bitcoin ATMs, Gives Operators 45 Days to Remove Them](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Real-SWE benchmarks AI models on private enterprise codebases](https://withspecific.com/benchmarks/real-swe) ⭐️ 8.0/10

Specific Labs released Real-SWE, a benchmark that evaluates frontier AI models on private production codebases licensed from real companies, covering eight model and harness configurations, ten tasks, and 640 scored rollouts. It marks a shift from public GitHub-issue benchmarks like SWE-bench toward testing models on proprietary enterprise code that they have likely never seen. Most AI coding benchmarks rely on public repositories that may already be in model training data, so they can overstate real-world ability; testing on private enterprise code gives a more honest signal of how these tools perform on the messy, proprietary codebases companies actually maintain. The results and the heated 99-comment discussion could influence how enterprises choose coding assistants and how vendors market their models. The benchmark spans eight model and harness configurations, ten tasks, and 640 scored rollouts, but commenters note that crucial methodology details such as reasoning levels and the specific harness used are missing. Community members also warn that many supposedly 'private' codebases may already be contaminated in training data, and that token volume differences can skew cost comparisons between models.

hackernews · theanonymousone · Sep 12, 20:25 · [Discussion](https://news.ycombinator.com/item?id=49676820)

**Background**: SWE-bench is the best-known benchmark for AI coding agents, built from real GitHub issues and pull requests, and its leaderboards are widely cited. However, because its data is public, models may have memorized the answers, a problem known as data contamination, which undermines benchmark validity. Real-SWE tries to address this by licensing private production code from companies so the evaluation tasks are genuinely unseen.

<details><summary>References</summary>
<ul>
<li><a href="https://withspecific.com/benchmarks/real-swe">Real-SWE Benchmark — Specific Labs</a></li>
<li><a href="https://github.com/swe-bench/SWE-bench">GitHub - SWE-bench/SWE-bench: SWE-bench: Can Language Models Resolve Real-world Github Issues? · GitHub</a></li>
<li><a href="https://www.technologyreview.com/2025/05/08/1116192/how-to-build-a-better-ai-benchmark/">How to build a better AI benchmark | MIT Technology Review</a></li>

</ul>
</details>

**Discussion**: Commenters were broadly skeptical: some questioned whether private codebases were shared with OpenAI and Anthropic, others warned that many 'private' repos are likely already contaminated and that benchmarks should measure contamination every time. Several practitioners said the roughly 30% success rate matches their own experience that models remain unreliable, and others criticized missing methodology details like reasoning levels and harness choice that make cross-model comparisons hard to trust.

**Tags**: `#AI benchmarks`, `#software engineering`, `#enterprise codebases`, `#model evaluation`, `#code generation`

---

<a id="item-2"></a>
## [Economist: Nvidia Is the Central Bank of AI](https://www.economist.com/interactive/briefing/2026/09/03/nvidia-is-the-central-bank-of-ai) ⭐️ 8.0/10

A September 3, 2026 Economist briefing argues that Nvidia has become the de facto "central bank of AI," citing roughly $300 billion in guarantees, backstops, and purchase commitments it has extended to its own customers, alongside a $5.4 trillion market valuation. The piece sparked one of the most-discussed AI stories on Hacker News, drawing hundreds of comments comparing Nvidia's role to the Federal Reserve. The framing highlights how a single private company now performs functions traditionally associated with public monetary institutions, effectively financing and underwriting much of the AI industry's expansion. This concentration of economic power raises questions about systemic risk, corporate governance, and who bears the cost if the AI boom cools. Nvidia's commitments are estimated at over $500 billion in investments and commitments, which commenters note exceeds the Fed's recent easing, though Nvidia has reportedly not borrowed against its stock to fund them. The article also notes Nvidia removed its standalone gaming revenue reporting from financial reports in summer 2026, fueling speculation about its shifting priorities.

hackernews · tolugenius · Sep 12, 15:08 · [Discussion](https://news.ycombinator.com/item?id=49673098)

**Background**: Nvidia designs the GPUs that power most modern AI training and inference, and its chips have made it the world's most valuable company. As demand for AI compute surged, Nvidia began investing in and extending financing to cloud providers and AI startups that buy its hardware, creating a web of mutual dependencies. The "central bank" metaphor refers to how Nvidia, like a monetary authority, supplies the liquidity and credit that keep the AI economy running.

<details><summary>References</summary>
<ul>
<li><a href="https://www.economist.com/interactive/briefing/2026/09/03/nvidia-is-the-central-bank-of-ai">Nvidia is the central bank of AI - The Economist</a></li>
<li><a href="https://www.explainx.ai/blog/nvidia-central-bank-of-ai-vendor-financing-2026">Nvidia Central Bank of AI: $300B Backstops Explained (2026 ...</a></li>
<li><a href="https://www.economist.com/leaders/2026/09/03/nvidia-is-driving-the-ai-boom-good">Nvidia is driving the AI boom. Good - The Economist</a></li>

</ul>
</details>

**Discussion**: Commenters debated the Fed comparison, noting Nvidia's $500+ billion in commitments exceeds recent Fed easing while praising the absence of stock-backed borrowing. Others drew parallels to corporations acting like public institutions, questioned whether AI progress is plateauing as OpenAI and Anthropic call for slowdowns, and speculated about when Nvidia might exit the gaming market.

**Tags**: `#Nvidia`, `#AI`, `#Economics`, `#Central Banking`, `#Industry Analysis`

---

<a id="item-3"></a>
## [Revolut Exposed Bitcoin Activity and Passports After Fake Government Request](https://www.coindesk.com/tech/2026/09/12/bitcoin-activity-passports-exposed-after-revolut-falls-for-fake-government-request) ⭐️ 8.0/10

Revolut confirmed on September 12, 2026 that it disclosed sensitive customer data — including ID documents, selfies, and full Bitcoin transaction histories — to an unauthorized third party after receiving fraudulent requests sent from a legitimate government agency's own email domain. The breach affected a "limited" number of users, and onchain investigator ZachXBT speculated the attack may have targeted high-net-worth individuals. This breach highlights critical vulnerabilities in how fintech companies verify government data requests, potentially exposing users to identity theft and targeted attacks based on their crypto holdings. It raises serious regulatory and industry-wide questions about KYC data protection and the trust users place in centralized financial platforms. The fraudulent request passed Revolut's security checks because it came from a valid government agency email domain, and the exposed data included KYC documents, selfies, and Bitcoin transaction histories. ZachXBT's speculation suggests the attackers may have specifically targeted wealthy users, though Revolut has not confirmed the exact number of affected customers.

rss · CoinDesk · Sep 12, 10:11

**Background**: Revolut is a major British fintech company offering banking, crypto trading, and other financial services to millions of customers worldwide. KYC (Know Your Customer) procedures require financial institutions to collect identity documents and personal data to comply with anti-money laundering regulations. Bitcoin transactions are recorded on a public blockchain, meaning anyone with access to a wallet address can trace its full transaction history, making exposed crypto activity particularly sensitive.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/09/12/revolut-confirms-customer-data-breach-through-fake-government-requests/">Revolut confirms customer data breach through fake government ...</a></li>
<li><a href="https://securityaffairs.com/198922/data-breach/revolut-exposed-kyc-data-after-fraudulent-government-email-passed-security-checks.html">Revolut Exposed KYC Data After Fraudulent Government Email ...</a></li>
<li><a href="https://www.expressvpn.com/blog/is-bitcoin-anonymous/">Is Bitcoin Traceable? How to Stay Anonymous | ExpressVPN</a></li>

</ul>
</details>

**Discussion**: Onchain investigator ZachXBT speculated that the incident may have been targeting high-net-worth users, suggesting the attackers had specific intelligence about Revolut's customer base. The crypto community has raised concerns about the risks of centralized platforms holding both identity and transaction data.

**Tags**: `#security breach`, `#fintech`, `#privacy`, `#bitcoin`, `#identity theft`

---

<a id="item-4"></a>
## [Satirical post mocks AI leaders who urge slowing down AI](https://xeiaso.net/notes/2026/everyone-slowdown-but-me/) ⭐️ 7.0/10

A satirical blog post by Xe Iaso titled "Everyone should slow down AI development except for me" criticizes the hypocrisy of AI leaders who publicly advocate for slowing AI development while continuing to advance their own systems. The post sparked a robust Hacker News discussion with 318 points and 175 comments on AI safety, regulation, and power dynamics. This commentary highlights growing skepticism toward AI safety rhetoric from industry leaders, which critics argue is often self-serving and aimed at regulatory capture. The discussion reflects broader societal tensions over who should control AI development and how to balance innovation with safety. The post is not a technical breakthrough but a sharp satirical take on AI safety rhetoric, and the Hacker News thread includes diverse critical viewpoints on regulatory capture and geopolitical dynamics. Commenters debate whether AI doomerism has become a moral panic and question the motives of leaders like Sam Altman and Dario Amodei.

hackernews · xena · Sep 13, 00:30 · [Discussion](https://news.ycombinator.com/item?id=49678683)

**Background**: AI safety is an interdisciplinary field focused on preventing accidents, misuse, or harmful consequences from AI systems, including alignment and monitoring. AI regulation involves developing public policies and laws to govern AI, with recent efforts like the EU AI Act in 2024. The debate over slowing AI development has intensified as generative AI advances rapidly, with some leaders calling for moratoriums while others push forward.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_safety">AI safety</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_regulation">AI regulation</a></li>

</ul>
</details>

**Discussion**: Commenters largely agree that AI safety rhetoric is hypocritical and self-serving, with some predicting it will be seen as a moral panic. Others point out that slowing public AI development could allow nation-states to create a capabilities gap, and that shareholders and geopolitical competition make slowdowns unlikely.

**Tags**: `#AI safety`, `#AI regulation`, `#tech ethics`, `#Hacker News`, `#AI policy`

---

<a id="item-5"></a>
## [Anthropic CEO Urges Slowing AI Race; Musk and Altman Agree](https://www.coindesk.com/tech/2026/09/12/anthropic-ceo-calls-for-ai-race-to-slow-down-musk-and-openai-s-altman-agrees) ⭐️ 7.0/10

Anthropic CEO Dario Amodei publicly called for 'pacing the frontier' of AI development, arguing the industry should slow down due to safety concerns, and both Elon Musk and OpenAI CEO Sam Altman expressed agreement with the idea. It is rare for the leaders of three major competing AI labs to publicly align on the need to slow down, which could shift the policy debate in Washington and pressure other labs to adopt similar safety commitments. The call comes amid a regulatory vacuum: the US Congress has debated but passed no comprehensive AI regulation, and the White House has not settled on which agency should oversee the technology, while critics argue a slowdown is nearly impossible given intense company and country competition.

rss · CoinDesk · Sep 12, 18:43

**Background**: Anthropic was founded in 2021 by former OpenAI researchers, including Dario Amodei, who left partly over disagreements about safety priorities, and the company has built its brand around a safety-first approach and a Responsible Scaling Policy. The debate over slowing AI development centers on whether frontier models could become dangerous without adequate alignment techniques, and whether an 'arms-race dynamic' between labs and nations makes any unilateral slowdown self-defeating.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/responsible-scaling-policy">Anthropic’s Responsible Scaling Policy</a></li>
<li><a href="https://www.cnn.com/2026/09/12/tech/anthropic-ceo-essay-ai">Anthropic CEO calls for ‘pacing the frontier’ of AI race ... | CNN Business</a></li>
<li><a href="https://time.com/article/2026/08/16/ai-race-slowdown-data-center-verification/">time.com/article/2026/08/16/ ai - race - slowdown -data-center-verification</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were largely skeptical, with some arguing Amodei's call is an admission that Anthropic failed to solve alignment and is really about protecting market position, while others accused the company of regulatory capture and anti-competitive behavior disguised as ethics; a few supported pacing the frontier but doubted broad agreement is achievable.

**Tags**: `#AI safety`, `#AI regulation`, `#Anthropic`, `#OpenAI`, `#industry news`

---

<a id="item-6"></a>
## [OpenAI Asks Congress Whether an AI Slowdown Would Be Legal](https://decrypt.co/377990/openai-congress-ai-slowdown-legal) ⭐️ 7.0/10

OpenAI is formally asking Congress to clarify whether a coordinated slowdown in AI development would be legal under existing antitrust rules. The request comes as researchers call for restraint and experts warn that intensifying competition pushes companies to overlook safety risks. The answer could shape whether frontier AI labs can legally coordinate to pace development, affecting the entire AI industry's safety practices and competitive dynamics. It also signals that leading AI companies are increasingly worried that antitrust law may block voluntary restraint. Senators Adam Schiff and Jim Banks have introduced Bill S.5105, which would allow companies to enter agreements mitigating certain AI model risks without triggering antitrust liability; the bill is still under review by the Senate Judiciary Committee and has not been voted on.

rss · Decrypt · Sep 11, 18:16

**Background**: Antitrust law generally prohibits competitors from coordinating to limit output or restrain trade, which could make a voluntary industry-wide AI slowdown legally risky. As AI capabilities advance rapidly, some researchers and policymakers argue for deliberate pacing, but companies fear such coordination could be seen as illegal collusion. Bill S.5105 aims to create a legal safe harbor for safety-motivated agreements.

<details><summary>References</summary>
<ul>
<li><a href="https://thecurrencyanalytics.com/technology/openai-seeks-legal-path-to-slow-ai-without-antitrust-penalties-293004">OpenAI Seeks Legal Path to Slow AI Without Antitrust Penalties</a></li>
<li><a href="https://www.wired.com/story/openai-wants-to-know-if-an-ai-industry-slowdown-would-even-be-legal/">OpenAI Wants to Know if an AI Industry Slowdown Would... | WIRED</a></li>
<li><a href="https://techxplore.com/news/2026-06-competition-ai-firms-favor-safety.html">Competition may push AI firms to favor speed over safety , new study...</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#antitrust`, `#OpenAI`, `#AI regulation`, `#AI safety`

---

<a id="item-7"></a>
## [India's SEBI Demat 2.0 Pilot Raises $107M in Tokenized Bonds](https://www.theblock.co/news/regulation/2026-09-11-indias-sebi-demat-2-0-pilot-debuts-with-over-100-million-in-tokenized-bonds-414252) ⭐️ 7.0/10

India's Securities and Exchange Board (SEBI) launched its Demat 2.0 pilot on September 11, 2026, enabling three issuers to raise ₹1,025 crore ($107.2 million) through tokenized corporate bonds settled via the Reserve Bank of India's wholesale CBDC. The first phase focuses on issuance, using distributed ledger technology for holding and settlement with atomic delivery-versus-payment. This is one of the largest real-world demonstrations of tokenized corporate debt settled in central bank money, signaling that India's regulators are moving blockchain-based market infrastructure from concept to live pilot. If scaled, it could reshape how Indian corporates issue and settle debt, and serve as a template for other jurisdictions exploring wholesale CBDC integration. The pilot uses distributed ledger technology for issuance, holding and settlement, with tokenized bonds linked to the RBI's wholesale digital rupee for atomic settlement; the first phase is limited to issuance, so secondary trading is not yet in scope. The ₹1,025 crore total came from three issuers, and the program remains an early-stage pilot rather than a full production rollout.

rss · The Block · Sep 11, 12:09

**Background**: Tokenized bonds are fixed-income instruments whose ownership and settlement are recorded on a blockchain or distributed ledger, while retaining traditional features like coupons, maturity and credit risk. A wholesale CBDC is a central bank digital currency used only for transactions between banks and financial institutions, as opposed to a retail CBDC used by the general public. SEBI's Demat 2.0 builds on India's existing dematerialized (Demat) securities system, which already holds shares and bonds electronically, by adding DLT-based issuance and settlement.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/news/regulation/2026-09-11-indias-sebi-demat-2-0-pilot-debuts-with-over-100-million-in-tokenized-bonds-414252">India 's SEBI Demat 2 . 0 pilot debuts with over $100 million... | The Block</a></li>
<li><a href="https://coin360.com/news/india-demat-2-tokenized-bonds">India 's Demat 2 . 0 Tokenizes Corporate Bonds</a></li>
<li><a href="https://www.weforum.org/stories/2024/02/wholesale-retail-cbdcs-difference/">Wholesale and retail CBDCs – what exactly is the difference ...</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenization`, `#CBDC`, `#financial-regulation`, `#capital-markets`

---

<a id="item-8"></a>
## [JOSM Plugin Wizard Guides First OpenStreetMap Edits](https://high5apps.github.io/josm-plugin-website-wizard/) ⭐️ 6.0/10

A new website-wizard plugin for JOSM (the Java OpenStreetMap editor) has been published, offering a step-by-step guide to help newcomers make their first edit to OpenStreetMap by quickly adding a website tag to a place. The accompanying discussion thread drew 393 points and 92 comments, with experienced mappers debating whether JOSM is the right entry point for beginners. Lowering the barrier to entry for new contributors is critical for OpenStreetMap, whose volunteer-maintained database competes with proprietary services like Google Maps and Apple Maps. If beginners find editing too intimidating or confusing, the project risks losing the fresh local knowledge that keeps its map data accurate and up to date. The plugin is specifically designed to add a website tag to places in OpenStreetMap as quickly and easily as possible, but community members note that JOSM is a powerful desktop editor with advanced features not present in the default iD editor, making it potentially overwhelming for a first edit. Alternative beginner-friendly tools mentioned include StreetComplete for task-based Android editing, Every Door for intermediate smartphone editing, and Rapid for web-based editing.

hackernews · juliantigler · Sep 12, 16:25 · [Discussion](https://news.ycombinator.com/item?id=49674050)

**Background**: OpenStreetMap is a free, editable world map built by volunteers, similar in spirit to Wikipedia but for geographic data. Contributors add data by tracing aerial imagery, recording GPS tracks, or surveying on the ground, and the resulting database is used by countless apps and navigation services. JOSM is a long-standing desktop editor for OSM written in Java, while iD is the simpler editor embedded directly in the OpenStreetMap website.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenStreetMap">OpenStreetMap</a></li>
<li><a href="https://en.wikipedia.org/wiki/JOSM">JOSM - Wikipedia</a></li>
<li><a href="https://github.com/High5Apps/josm-plugin-website-wizard">GitHub - High5Apps/ josm - plugin -website- wizard : JOSM plugin to...</a></li>

</ul>
</details>

**Discussion**: The community largely agreed that JOSM is not ideal for a first edit, with one user stating it is "definitely not recommended" and recommending the built-in iD editor instead. Others suggested StreetComplete, Every Door, and Rapid as gentler entry points, while one newcomer shared a positive experience mapping a new bike trail and seeing their contribution propagate to apps that Google and Apple had ignored. A broader concern was raised that OSM makes most editing too hard and should prioritize mapping stores, their types, and opening hours.

**Tags**: `#OpenStreetMap`, `#mapping`, `#JOSM`, `#tutorial`, `#community`

---

<a id="item-9"></a>
## [Reform UK Gets $97M From Two Crypto Billionaires in 24 Hours](https://www.coindesk.com/business/2026/09/12/nigel-farage-s-reform-uk-lands-usd97-million-donations-from-two-crypto-billionaires-in-24-hours) ⭐️ 6.0/10

Nigel Farage's Reform UK party received a combined £72 million ($97.5 million) in donations from two crypto billionaires within a 24-hour period, according to reports. The party insists the donors want "nothing" in return for the gifts. The scale of these donations highlights the growing political influence of cryptocurrency wealth and intensifies debate over whether crypto donations should be banned in UK politics. It comes as the House of Lords considers legislation that would cap overseas giving at £100,000 a year and prohibit crypto asset donations entirely. The proposed House of Lords amendments to the Representation of the People Bill would cap all donations and regulated transactions from overseas electors at £100,000 annually and ban crypto donations outright. Reform UK has faced separate scrutiny over undeclared donations and allegations that senior members plotted to circumvent political donation rules.

rss · CoinDesk · Sep 12, 18:51

**Background**: UK political parties are subject to rules on donations, including requirements that large donations be from permissible sources and properly declared. Crypto donations have become a contentious issue because they can be difficult to trace and may originate from overseas, prompting proposals to restrict or ban them. Reform UK, led by Nigel Farage, has risen in prominence and has attracted significant financial backing from wealthy donors, including figures in the cryptocurrency industry.

<details><summary>References</summary>
<ul>
<li><a href="https://www.gov.uk/government/news/cap-on-donations-from-overseas-electors-and-ban-on-crypto-donations-to-protect-democracy">Cap on donations from overseas electors and ban on crypto ...</a></li>
<li><a href="https://www.onebullex.com/news/articles/reform-uk-accepts-72-million-from-crypto-billionaires-as-lords-push-100-000-donation-cap">Reform UK Accepts £72 Million From Crypto Billionaires As ...</a></li>
<li><a href="https://www.yahoo.com/news/politics/articles/reform-uk-says-crypto-billionaires-041839986.html?fr=sycsrp_catchall">Reform UK says crypto-billionaires want 'nothing' for £72m ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#politics`, `#campaign-finance`, `#UK`, `#regulation`

---

<a id="item-10"></a>
## [India's Richest State Explores Tokenizing Assets to Fund Infrastructure](https://www.coindesk.com/markets/2026/09/11/india-s-richest-state-is-exploring-tokenizing-its-own-assets-to-fund-new-infrastructure) ⭐️ 6.0/10

India's wealthiest state is reportedly exploring the tokenization of its own assets as a way to raise funds for new infrastructure projects, according to a CoinDesk report dated September 11, 2026. The initiative remains at an exploratory stage, with no concrete technical framework or issuance timeline disclosed. This signals growing interest among subnational governments in using blockchain-based asset tokenization as an alternative public financing tool, potentially opening a new market for real-world asset (RWA) infrastructure. If successful, it could serve as a template for other Indian states and emerging-market governments seeking to fund infrastructure without relying solely on traditional debt or multilateral loans. The report provides no specifics on which assets would be tokenized, what blockchain would be used, or how regulatory compliance with India's securities and tax laws would be handled. Tokenizing public infrastructure assets typically involves creating digital representations of ownership or revenue rights on a blockchain, which raises questions about custody, investor eligibility, and legal enforceability.

rss · CoinDesk · Sep 11, 15:17

**Background**: Asset tokenization refers to registering ownership of an asset on blockchain infrastructure, allowing it to benefit from more efficient settlement and interaction with smart contracts. Governments and financial institutions have increasingly explored tokenized bonds and real-world assets, with the U.S. Federal Reserve and firms like PwC studying the transparency and viability of such instruments. India has been a major adopter of digital public infrastructure, though its stance on crypto assets has historically been cautious.

<details><summary>References</summary>
<ul>
<li><a href="https://chainscorelabs.com/guides/blockchain-for-government-and-public-services/transparent-procurement/how-to-implement-asset-tokenization-for-public-infrastructure-procurement">How to Implement Asset Tokenization for Public Infrastructure</a></li>
<li><a href="https://www.federalreserve.gov/econres/notes/feds-notes/tokenized-assets-on-public-blockchains-how-transparent-is-the-blockchain-20240403.html">The Fed - Tokenized Assets on Public Blockchains: How ...</a></li>
<li><a href="https://research.grayscale.com/reports/public-blockchains-and-the-tokenization-revolution">Public Blockchains and the Tokenization Revolution | Grayscale</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenization`, `#infrastructure`, `#public finance`, `#India`

---

<a id="item-11"></a>
## [GPT-6 Astra Users Say OpenAI's Newest Model Got Dumber](https://decrypt.co/378101/gpt-6-astra-openai-model-dumber-nerfed) ⭐️ 6.0/10

A week after OpenAI launched GPT-6 Astra, users are complaining that the model has been 'nerfed' — meaning its quality appears to have degraded compared to its initial release. This mirrors a similar cycle that occurred with OpenAI's previous model in July, when users also reported a decline in performance shortly after launch. This recurring pattern of post-launch model degradation raises concerns about transparency and consistency in AI development, affecting both everyday users who rely on these models and developers who build applications on top of them. It highlights a broader industry issue where AI labs silently update models mid-cycle without clear documentation of the tradeoffs involved. The complaints center on perceived quality regression, particularly on edge cases and tasks requiring sustained multi-step reasoning across large contexts. OpenAI, Anthropic, and Google have all acknowledged that model behavior changes over time, but most labs provide minimal documentation about mid-cycle updates, leaving users to speculate about what changed.

rss · Decrypt · Sep 12, 16:01

**Background**: Model degradation refers to the observed decline in accuracy, consistency, or reasoning capabilities of AI models after deployment. In the context of large language models, 'nerfing' is a colloquial term users employ when they believe a model's capabilities have been deliberately or inadvertently reduced. This phenomenon is distinct from model collapse, which describes a theoretical long-term degradation caused by training on AI-generated data. The controversy around nerfing is primarily about transparency: users want to know when changes happen and what tradeoffs were made.

<details><summary>References</summary>
<ul>
<li><a href="https://3zebras.com/tech/are-ai-labs-secretly-nerfing-their-models-the-data-behind-the-claims/15561/">Are AI Labs Nerfing Models? Data Behind the Claims</a></li>
<li><a href="https://grokipedia.com/page/AI_model_performance_degradation">AI model performance degradation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Model_collapse">Model collapse - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#GPT-6`, `#model degradation`, `#AI news`, `#user complaints`

---

<a id="item-12"></a>
## [ChatGPT Images 2.5 vs Nano Banana 2: A Six-Category Comparison](https://decrypt.co/377998/chatgpt-images-2-5-vs-nano-banana-2-review) ⭐️ 6.0/10

Decrypt published a head-to-head review comparing OpenAI's newly released ChatGPT Images 2.5 against Google's Nano Banana 2, evaluating both image generation models across six categories. OpenAI describes ChatGPT Images 2.5 as its new state-of-the-art image model, offering sharper details, more precise editing, and faster generation. Both models sit at the frontier of AI image generation, so a direct comparison helps developers, designers, and content creators decide which tool fits their workflows. The review also reflects intensifying competition between OpenAI and Google in multimodal generation, where quality, editing precision, and speed are key differentiators. The comparison spans six evaluation categories, though the summary does not list them individually; the review focuses on practical benchmarks rather than a single headline metric. Nano Banana 2 is built on Google's Gemini 3.1 Flash image model, which emphasizes fast generation, accurate text rendering, and strong character consistency.

rss · Decrypt · Sep 12, 13:01

**Background**: AI image generation models turn text prompts into pictures and are increasingly used for design, marketing, and creative work. OpenAI's ChatGPT Images line is the image generation capability inside ChatGPT, while Google's Nano Banana is the nickname for its Gemini-based image model. Head-to-head reviews like this one are common because each new release claims improvements in detail, editing, and speed, and users want practical guidance on which to choose.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/introducing-chatgpt-images-2-5/">Introducing ChatGPT Images 2.5 | OpenAI</a></li>
<li><a href="https://kie.ai/nano-banana-2">Nano Banana 2 API - Gemini 3.1 Flash 4K Image from $0.04 | Kie AI</a></li>
<li><a href="https://www.medeo.app/models/nano-banana-2">Nano Banana 2 AI Image Generator Online | Medeo</a></li>

</ul>
</details>

**Tags**: `#AI image generation`, `#model comparison`, `#OpenAI`, `#Google`, `#benchmarking`

---

<a id="item-13"></a>
## [Law Firm Cyberattacks Nearly Double in 2025 as Stolen Files Hit Dark Web](https://decrypt.co/378094/cyberattacks-law-firms-stolen-documents-dark-web) ⭐️ 6.0/10

Greenberg Traurig reported that stolen documents were posted to the dark web, while BakerHostetler recorded a near-doubling of cyber incidents targeting law firms in 2025 compared with the prior year. Law firms hold some of the most sensitive client information, including litigation strategy and corporate deal data, so a surge in breaches threatens client confidentiality, attorney-client privilege, and could trigger regulatory and class-action fallout across the legal industry. The stolen material was published on the dark web, the encrypted portion of the internet accessible only through tools like Tor, and the figures come from two separate law firm reports rather than a single centralized tally.

rss · Decrypt · Sep 11, 21:45

**Background**: The dark web is web content hosted on overlay networks such as Tor that requires special software or authorization to reach, and it is often used to anonymously trade stolen data. Law firms have become attractive targets because they aggregate confidential documents for many corporate clients, and recent years have seen repeated breaches at major firms and their legal-tech vendors.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Dark_web">Dark web</a></li>
<li><a href="https://proton.me/blog/what-is-dark-web">What the dark web is and how you can access it | Proton</a></li>
<li><a href="https://www.law.com/americanlawyer/2026/09/09/data-breaches-at-mcdermott-quinn-cap-cyber-siege-summer-/">Data Breaches at McDermott, Quinn Cap Cyber-Siege Summer</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#law firms`, `#data breach`, `#dark web`, `#cyberattacks`

---

<a id="item-14"></a>
## [Blockstream Refuses Ransom for $47M in Bitcoin Stolen from Liquid Network](https://decrypt.co/377959/blockstream-refuses-ransom-for-return-of-47m-in-bitcoin-from-liquid-hack-it-is-theft) ⭐️ 6.0/10

Blockstream has refused to pay a ransom for the return of 598.5 BTC (about $47 million) still outstanding after a hack on its Liquid network, calling the incident theft and threatening law enforcement action if the funds are not returned. Liquid has resumed transactions following the exploit, though peg-outs remain disabled as recovery work continues. This is one of the largest security incidents affecting a Bitcoin layer-2 network, and Blockstream's refusal to negotiate sets a precedent for how crypto infrastructure operators respond to attackers. The still-disabled peg-outs mean users cannot freely move L-BTC back to the Bitcoin main chain, raising concerns about trust in federated sidechain models. The exploit stemmed from a single software bug in Blockstream's Elements codebase that let an attacker mint nearly 4,000 unbacked L-BTC out of thin air and peg them out for real Bitcoin, draining roughly 95% of the Liquid Federation's reserves. About 3,400 BTC were returned after negotiation, leaving 598.5 BTC outstanding, and the attackers reportedly left an on-chain message claiming responsibility.

rss · Decrypt · Sep 11, 14:17

**Background**: Liquid is a Bitcoin layer-2 sidechain operated by Blockstream that lets users move BTC onto a federated network as L-BTC for faster, more confidential transactions. The peg-in/peg-out mechanism is backed by a federation wallet holding real BTC, so a bug that mints unbacked L-BTC can be redeemed for genuine Bitcoin. This incident highlights the security assumptions of federated sidechains compared to Bitcoin's base layer.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bitrue.com/blog/liquid-network-hack-320m-bitcoin-explained">Liquid Network Hack Explained: What Happened to $320M?</a></li>
<li><a href="https://cryptobriefing.com/liquid-network-exploit-slowmist-analysis/">SlowMist details Liquid Network exploit, attacker mints 3,998 ...</a></li>
<li><a href="https://blockonomi.com/liquid-network-hack-attackers-return-270m-in-bitcoin-after-320m-exploit/">Liquid Network Hack: Attackers Return $270M in Bitcoin After ...</a></li>

</ul>
</details>

**Tags**: `#bitcoin`, `#blockchain-security`, `#hacking`, `#ransomware`, `#cryptocurrency`

---

<a id="item-15"></a>
## [EU Regulator Flags Insider Trading in Prediction Markets](https://decrypt.co/377947/eu-regulator-says-prediction-markets-are-rife-with-inside-trading) ⭐️ 6.0/10

The European Securities and Markets Authority (ESMA) has raised concerns that prediction markets are 'rife with inside trading' and questioned why platforms like Kalshi and Polymarket block some EU countries but not others, noting that VPNs can circumvent these restrictions. ESMA also stated that major prediction platforms lack EU authorization. This signals growing regulatory scrutiny of prediction markets in the EU, potentially leading to stricter rules or enforcement actions that could affect how platforms like Kalshi and Polymarket operate in European markets. It highlights the tension between fast-growing event-based trading platforms and existing financial regulations designed to protect investors and ensure market integrity. ESMA specifically pointed out that Kalshi and Polymarket block users in some EU countries but not others, and that VPNs can be used to bypass these geographic restrictions. The regulator also noted that these major prediction platforms lack EU authorization, raising questions about their legal status under EU financial rules.

rss · Decrypt · Sep 11, 12:06

**Background**: Prediction markets are platforms where users trade contracts on the outcome of future events, such as elections, economic indicators, or sports. Kalshi is a US-regulated exchange, while Polymarket is a cryptocurrency-based platform that has grown rapidly. ESMA is the EU agency responsible for securities regulation and investor protection, and it coordinates with national regulators to ensure consistent application of EU financial law.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/European_Securities_and_Markets_Authority">European Securities and Markets Authority - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket - Wikipedia</a></li>
<li><a href="https://kalshi.com/">Kalshi - Prediction Market for Trading the Future</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#regulation`, `#insider trading`, `#EU`, `#ESMA`

---

<a id="item-16"></a>
## [Albuquerque Bans Bitcoin ATMs, Gives Operators 45 Days to Remove Them](https://decrypt.co/377939/albuquerque-bans-bitcoin-atms-giving-operators-45-days-to-remove-them) ⭐️ 6.0/10

Albuquerque has passed a ban on Bitcoin ATMs and other cryptocurrency kiosks, giving operators 45 days to remove the machines from the city. A city councilor stated that 90% of crypto kiosk transactions in Albuquerque are tied to fraud, describing the machines as a conduit for crime. This is one of the most aggressive municipal actions against crypto kiosks in the United States and could encourage other cities to follow suit as scrutiny of crypto-related fraud grows. It directly affects Bitcoin ATM operators, their customers, and the broader debate over how to balance crypto access with consumer protection. The ban targets cryptocurrency kiosks, which allow users to buy Bitcoin and other digital assets with cash or debit cards, and some of which support two-way buy/sell functionality. Operators have only 45 days to comply, and the city's justification rests on the claim that 90% of local kiosk transactions are fraud-related.

rss · Decrypt · Sep 11, 10:10

**Background**: Bitcoin ATMs, also called BTMs or cryptocurrency ATMs, are physical kiosks that let people exchange cash for Bitcoin and sometimes sell crypto for cash. Because they often involve relatively anonymous, irreversible transactions and high fees, they have become a favored tool for scammers targeting victims, especially seniors. Regulation of these machines varies widely by jurisdiction and has been tightening in many places due to KYC, AML, and consumer-protection concerns.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bitcoin_ATM">Bitcoin ATM</a></li>
<li><a href="https://www.activeintel.com/crypto-kiosk-scams-how-fraudsters-target-victims/">Crypto Kiosk Scams: How Fraudsters... - Active Intel Investigations</a></li>
<li><a href="https://www.gate.com/learn/articles/what-is-crypto-atm-regulation">What Is Crypto ATM Regulation ? KYC, AML and... | Gate Learn</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#bitcoin-atm`, `#fraud`, `#policy`

---