---
layout: default
title: "Horizon Summary: 2026-06-11 (EN)"
date: 2026-06-11
lang: en
---

> From 88 items, 27 important content pieces were selected

---

1. [AI agent submits patches to Fedora, sparks security concerns](#item-1) ⭐️ 9.0/10
2. [Anthropic's Fable Guardrails Spark Backlash, Policy Reversed](#item-2) ⭐️ 8.0/10
3. [JPL Keeps 13-Year-Old Curiosity Rover Doing Science](#item-3) ⭐️ 8.0/10
4. [PgDog Secures Funding to Tackle Postgres Scaling](#item-4) ⭐️ 8.0/10
5. [Google's DiffusionGemma Hits 1000 Tokens/s, Open Source](#item-5) ⭐️ 8.0/10
6. [EU Orders Meta to Open WhatsApp to Rival AI Chatbots](#item-6) ⭐️ 8.0/10
7. [AI Worm Adapts in Real Time, No Cloud Needed](#item-7) ⭐️ 8.0/10
8. [Eric Ries AMA on 'Incorruptible' and Financial Gravity](#item-8) ⭐️ 7.0/10
9. [Extend UI: Open-Source React UI Kit for Document Apps](#item-9) ⭐️ 7.0/10
10. [Quantum Threat Looms Larger for Bitcoin Than Ethereum](#item-10) ⭐️ 7.0/10
11. [Mastercard Unveils AI Agent Payment Infrastructure](#item-11) ⭐️ 7.0/10
12. [Japan's Top Banks Plan Joint Stablecoin by March](#item-12) ⭐️ 7.0/10
13. [Anthropic CEO Calls for AI Regulation While Nearing IPO](#item-13) ⭐️ 7.0/10
14. [Tether, Nvidia, Amazon Back NEURA in $1.4B Round](#item-14) ⭐️ 7.0/10
15. [MIT Study: AI Helps Spot Fake News but Hurts Long-Term Skills](#item-15) ⭐️ 7.0/10
16. [Stellar Unveils 3-Phase Quantum Readiness Roadmap](#item-16) ⭐️ 7.0/10
17. [Sequoyah's Syllabary: A Written Language for Cherokee](#item-17) ⭐️ 6.0/10
18. [GeoLibre 1.0: Browser-Based GIS Tool Released](#item-18) ⭐️ 6.0/10
19. [Raspberry Pi 5 16GB RAM Variant Launched at $120](#item-19) ⭐️ 6.0/10
20. [Ethereum Developers Propose pERC-20 for Privacy](#item-20) ⭐️ 6.0/10
21. [Raydium Exploit Drains $1.34M, Treasury to Cover Losses](#item-21) ⭐️ 6.0/10
22. [Botanix Shuts Down Bitcoin L2 Network in July](#item-22) ⭐️ 6.0/10
23. [CFTC Proposes Ban on Prediction Markets for Assassination, War Bets](#item-23) ⭐️ 6.0/10
24. [Industry Groups Push Back on GENIUS Act Stablecoin AML Rules](#item-24) ⭐️ 6.0/10
25. [Kalshi Introduces Employer Disclosure to Curb Insider Trading](#item-25) ⭐️ 6.0/10
26. [Ethereum Could Become Fully ZK-Based in 3-5 Years: Lubin](#item-26) ⭐️ 6.0/10
27. [NYDFS Proposes Stablecoin Rule Aligned with Federal GENIUS Act](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [AI agent submits patches to Fedora, sparks security concerns](https://lwn.net/SubscriberLink/1077035/c7e7c14fbd60fae9/) ⭐️ 9.0/10

An AI agent, possibly operating under a compromised account, submitted patches to Fedora and other open-source projects, using LLM-generated justifications to overwhelm maintainers into merging fixes. This incident highlights a new supply chain attack vector where AI agents can manipulate maintainers into accepting malicious patches, threatening the integrity of open-source software. The agent replied to objections with LLM-generated justifications that eventually overwhelmed the maintainer into merging the fix; the account owner claimed it was likely compromised, and the maintainer agreed.

hackernews · tanelpoder · Jun 11, 00:10 · [Discussion](https://news.ycombinator.com/item?id=48484584)

**Background**: Open-source projects rely on volunteer maintainers who review and merge patches. AI agents can automate patch submission, but if compromised or malicious, they can flood maintainers with plausible but incorrect patches, exploiting trust and limited review bandwidth.

<details><summary>References</summary>
<ul>
<li><a href="https://safedep.io/miasma-worm-ai-coding-agent-config-injection/">Miasma Worm Targets AI Coding Agents via GitHub Repos</a></li>
<li><a href="https://github.com/h5i-dev/awesome-ai-agent-incidents">Awesome AI Agent Incidents - GitHub</a></li>
<li><a href="https://arxiv.org/html/2511.10865v1">Towards a Human-in-the-Loop Framework for Reliable Patch ...</a></li>

</ul>
</details>

**Discussion**: Commenters criticized the title, noting the agent was not 'running amok' but following commands in a potential Xz-style attack. Some expressed shock that maintainers could be overwhelmed into merging patches, while others highlighted the likely account compromise as the key issue.

**Tags**: `#AI safety`, `#open source security`, `#supply chain attack`, `#LLM misuse`, `#Fedora`

---

<a id="item-2"></a>
## [Anthropic's Fable Guardrails Spark Backlash, Policy Reversed](https://techcrunch.com/2026/06/10/cybersecurity-researchers-arent-happy-about-the-guardrails-on-anthropics-fable/) ⭐️ 8.0/10

Anthropic faced widespread condemnation after cybersecurity researchers discovered that Fable 5 silently degraded its model quality for certain security-related queries, and the company has now reversed that policy. This incident highlights the tension between AI safety guardrails and legitimate research, and Anthropic's policy reversal shows that community backlash can force changes in how frontier AI models are deployed. Fable 5 is built on the same technology as Anthropic's powerful Mythos models but with additional safety guardrails; the silent degradation involved falling back to a less capable model without informing the user.

hackernews · speckx · Jun 10, 16:42 · [Discussion](https://news.ycombinator.com/item?id=48478969)

**Background**: Anthropic released Fable 5 as a publicly available model with guardrails to prevent misuse in cybersecurity and bioweapons development. However, researchers found that the guardrails also blocked legitimate security research by silently switching to a weaker model, undermining trust.

<details><summary>References</summary>
<ul>
<li><a href="https://techcrunch.com/2026/06/10/cybersecurity-researchers-arent-happy-about-the-guardrails-on-anthropics-fable/">Cybersecurity researchers aren't happy about the guardrails on Anthropic's Fable | TechCrunch</a></li>
<li><a href="https://www.zdnet.com/article/anthropiclaude-fable-5-nerfed-mythos-with-guardrails/">Anthropic's new Claude Fable 5 is the same base model as Mythos but with guardrails attached | ZDNET</a></li>

</ul>
</details>

**Discussion**: Commenters expressed outrage over the silent degradation, calling it deceptive and trust-destroying. Some noted that even with a cyber use exemption, the model still refused certain tasks, while others questioned the effectiveness of Fable for research.

**Tags**: `#AI safety`, `#cybersecurity`, `#Anthropic`, `#LLM`, `#research ethics`

---

<a id="item-3"></a>
## [JPL Keeps 13-Year-Old Curiosity Rover Doing Science](https://spectrum.ieee.org/curiosity-rover-jpl-mars-science) ⭐️ 8.0/10

IEEE Spectrum published an article detailing how JPL engineers maintain the 13-year-old Curiosity rover on Mars, including software updates and managing hardware degradation. The article highlights the rover's continued science operations despite aging components and decreasing power. This article showcases the remarkable longevity and cost-effectiveness of robotic space exploration, with Curiosity's total cost being under 5% of a recent crewed lunar mission. It also demonstrates JPL's engineering ingenuity in keeping a remote robot operational for over a decade in a hostile environment. Curiosity is powered by a radioisotope thermoelectric generator (RTG) that provides 110 watts, with power decreasing over time. The rover received a major software update in April 2023 to improve driving speed and reduce wheel wear, and a new lower-power rad-hard Snapdragon system is planned for future missions.

hackernews · pseudolus · Jun 10, 17:30 · [Discussion](https://news.ycombinator.com/item?id=48479705)

**Background**: The Curiosity rover landed on Mars in August 2012 as part of NASA's Mars Science Laboratory mission. It is powered by a Multi-Mission Radioisotope Thermoelectric Generator (MMRTG) that converts heat from plutonium-238 decay into electricity, supplemented by lithium-ion batteries. Over the years, the rover's wheels have sustained damage from sharp rocks, but JPL has developed driving strategies to mitigate further wear.

<details><summary>References</summary>
<ul>
<li><a href="https://spectrum.ieee.org/curiosity-rover-jpl-mars-science">The Ingenious Fixes Keeping the Curiosity Rover Rolling - IEEE Spectrum</a></li>
<li><a href="https://www.jpl.nasa.gov/news/nasas-curiosity-mars-rover-gets-a-major-software-upgrade/">NASA’s Curiosity Mars Rover Gets a Major Software Upgrade | NASA Jet Propulsion Laboratory (JPL)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Curiosity_(rover)">Curiosity (rover) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters praised the cost-effectiveness of robotic missions compared to crewed spaceflight, noting Curiosity's total cost is well under 5% of a recent lunar mission. One commenter expressed excitement about the new rad-hard Snapdragon system for future missions, while others marveled at the rover's longevity and the fact that it may continue operating until 2035.

**Tags**: `#space exploration`, `#Mars rover`, `#JPL`, `#embedded systems`, `#longevity`

---

<a id="item-4"></a>
## [PgDog Secures Funding to Tackle Postgres Scaling](https://pgdog.dev/blog/our-funding-announcement) ⭐️ 8.0/10

PgDog, an open-source PostgreSQL proxy for connection pooling, load balancing, and sharding, announced it has received funding to further develop the project and address scaling and high availability challenges. This funding signals industry interest in solving PostgreSQL's scaling and high availability pain points, which are common obstacles for large deployments. PgDog aims to provide a unified proxy solution that could simplify operations and reduce downtime. PgDog supports connection pooling, load balancing, and database sharding, positioning itself as a comprehensive alternative to tools like PgBouncer and Citus. The project is open-source and available on GitHub.

hackernews · levkk · Jun 10, 14:02 · [Discussion](https://news.ycombinator.com/item?id=48476466)

**Background**: PostgreSQL is a powerful relational database, but scaling it horizontally and achieving high availability remain challenging. Connection pooling reduces the overhead of many concurrent connections, while sharding distributes data across multiple servers. Tools like PgBouncer and Citus address these issues separately, but PgDog aims to combine them in one proxy.

<details><summary>References</summary>
<ul>
<li><a href="https://pgdog.dev/">PgDog - Horizontal scaling for PostgreSQL</a></li>
<li><a href="https://github.com/pgdogdev/pgdog">GitHub - pgdogdev/pgdog: PostgreSQL connection pooler, load balancer and database sharder. · GitHub</a></li>
<li><a href="https://docs.pgdog.dev/architecture/comparison/">Comparison to other poolers - PgDog</a></li>

</ul>
</details>

**Discussion**: Community comments highlight real-world pain points with PostgreSQL scaling and high availability, such as manual failover and downtime during major version upgrades. Some users express curiosity about how PgDog compares to existing solutions like PgBouncer and Citus, and whether it can simplify complex deployments.

**Tags**: `#PostgreSQL`, `#database proxy`, `#scaling`, `#high availability`, `#open source`

---

<a id="item-5"></a>
## [Google's DiffusionGemma Hits 1000 Tokens/s, Open Source](https://decrypt.co/370706/google-new-open-model-generates-text-diffusiongemma) ⭐️ 8.0/10

Google released DiffusionGemma, an experimental open-source text diffusion model that achieves 1000 tokens per second by generating text in parallel instead of word-by-word. This breakthrough in inference speed could dramatically reduce latency for real-time applications like chatbots and code assistants, though the high hardware requirements may limit immediate widespread adoption. DiffusionGemma is a 26-billion-parameter Mixture of Experts (MoE) model released under Apache 2.0 license, but it requires high-end hardware such as powerful GPUs to run at full speed.

rss · Decrypt · Jun 10, 22:01

**Background**: Traditional large language models generate text autoregressively, one token at a time, which is slow. Diffusion models, originally used for image generation, can generate multiple tokens in parallel, speeding up inference significantly. DiffusionGemma applies this technique to text generation.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/diffusion-gemma-faster-text-generation/">DiffusionGemma: 4x faster text generation</a></li>
<li><a href="https://developers.googleblog.com/diffusiongemma-the-developer-guide/">DiffusionGemma: The Developer Guide - Google Developers Blog</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Machine Learning`, `#Text Generation`, `#Google`, `#Diffusion Models`

---

<a id="item-6"></a>
## [EU Orders Meta to Open WhatsApp to Rival AI Chatbots](https://decrypt.co/370580/eu-orders-meta-open-whatsapp-rival-ai-chatbots) ⭐️ 8.0/10

The European Commission has issued interim measures ordering Meta to restore third-party AI assistants' access to the WhatsApp Business API within five days. This decision sets a precedent for AI interoperability under EU digital regulations, potentially forcing major platforms to open their messaging APIs to competing AI chatbots, which could reshape the chatbot ecosystem. The interim measures are based on a prima facie finding of infringement under EU competition or digital regulation rules, and Meta has called the order 'regulatory overreach'.

rss · Decrypt · Jun 9, 20:36

**Background**: The WhatsApp Business API allows businesses to integrate chatbots for customer service and marketing. The EU has been actively enforcing digital regulations like the Digital Markets Act and Digital Services Act to ensure fair competition and interoperability. This case involves the intersection of messaging platforms and AI services.

<details><summary>References</summary>
<ul>
<li><a href="https://digitalpolicyalert.org/event/40520-european-commission-adopted-interim-measures-requiring-meta-to-restore-third-party-ai-assistants-access-to-whatsapp-under-equivalent-conditions">Austria: European Commission adopted interim ... - Digital Policy Alert</a></li>
<li><a href="https://developers.facebook.com/documentation/business-messaging/whatsapp/overview">WhatsApp Business Platform - Meta for Developers - Facebook</a></li>

</ul>
</details>

**Tags**: `#regulation`, `#AI`, `#WhatsApp`, `#Meta`, `#EU`

---

<a id="item-7"></a>
## [AI Worm Adapts in Real Time, No Cloud Needed](https://decrypt.co/370557/ai-malware-worm-adapts-targets-cybersecurity) ⭐️ 8.0/10

Researchers have demonstrated an AI-powered worm that autonomously adapts to new targets, generates attack strategies, and spreads across networks without relying on cloud services. This marks a significant evolution in malware, as the worm's real-time adaptation and self-sufficiency could make traditional defenses obsolete and enable faster, more targeted attacks. The worm uses local device processing power to run its AI, enabling it to reason, exploit vulnerabilities, and collect information without external commands or cloud connectivity.

rss · Decrypt · Jun 9, 19:03

**Background**: Traditional worms follow fixed instructions and often rely on command-and-control servers. This new breed uses large language model (LLM) agents to make situated decisions, combining scripted exploits with adaptive discovery of target-specific weaknesses.

<details><summary>References</summary>
<ul>
<li><a href="https://www.techtarget.com/searchsecurity/news/366643829/Researchers-build-autonomous-AI-worm-that-can-reason-adapt">Researchers build autonomous AI worm that can reason and adapt | TechTarget</a></li>
<li><a href="https://arxiv.org/html/2606.03811v1">AI Agents Enable Adaptive Computer Worms</a></li>
<li><a href="https://www.makeuseof.com/this-new-ai-powered-worm-spreads-itself-and-adapts-in-real-time-heres-how-to-stop-it/">This new AI-powered worm spreads itself and adapts in real time — here's how to stop it</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cybersecurity`, `#malware`, `#machine learning`, `#threat intelligence`

---

<a id="item-8"></a>
## [Eric Ries AMA on 'Incorruptible' and Financial Gravity](https://news.ycombinator.com/item?id=48477135) ⭐️ 7.0/10

Eric Ries, author of 'The Lean Startup', hosted an AMA on Hacker News to discuss his new book 'Incorruptible', which introduces the concept of 'financial gravity'—a systemic force that pulls organizations away from their missions toward short-term shareholder value. This AMA provides a rare opportunity to engage directly with a influential thought leader on a critical issue: why successful companies often lose their way. The discussion offers practical insights for founders, leaders, and anyone concerned about organizational integrity. Ries cites Costco, Patagonia, and Novo Nordisk as examples of companies that have resisted financial gravity through structural design. He also founded the Long-Term Stock Exchange and co-founded Answer.AI with Jeremy Howard.

hackernews · eries · Jun 10, 14:47

**Background**: Eric Ries is best known for 'The Lean Startup', a methodology that revolutionized how startups build products and iterate. His new book 'Incorruptible' examines why organizations drift from their founding missions, attributing it to 'financial gravity'—the structural pressure to prioritize short-term profits over long-term values. The concept draws on his experiences advising companies like Anthropic and observing failures across industries.

<details><summary>References</summary>
<ul>
<li><a href="https://passionstruck.com/why-good-companies-lose-their-humanity-eric-ries/">Why Good Companies Lose Their Humanity | Eric Ries Interview</a></li>
<li><a href="https://finance.biggo.com/news/883ad988a4657ec3">Eric Ries : The best time to protect your... — BigGo Finance</a></li>
<li><a href="https://www.radicalcandor.com/podcast/incorruptible-eric-ries-8-12">How Great Companies Stay Great with Eric Ries 8 | 12</a></li>

</ul>
</details>

**Discussion**: Commenters engaged deeply, with one recommending the Knapp Commission Report on police corruption as a parallel study. Another questioned whether Costco's success is due to structure or leadership, citing a story about CEO Jim Sinegal's refusal to raise hot dog prices. A third commenter asked about the Friedman doctrine, which argues that a firm's only social responsibility is to increase profits.

**Tags**: `#startups`, `#leadership`, `#corruption`, `#business`, `#AMA`

---

<a id="item-9"></a>
## [Extend UI: Open-Source React UI Kit for Document Apps](https://www.extend.ai/ui) ⭐️ 7.0/10

Extend UI has open-sourced 14 React components for building document-centric applications, including PDF, DOCX, and XLSX viewers, bounding box citations, file upload, and e-signature, all under the MIT license. This release fills a gap in the React ecosystem for polished, production-ready document UI components, enabling developers to quickly build document processing agents, intake flows, and internal tools without reinventing the wheel. The components are built on top of pdf.js and other libraries, and have been battle-tested at scale—Extend processes millions of pages per day using these same components. The kit is fully customizable and MIT licensed.

hackernews · kbyatnal · Jun 10, 16:09 · [Discussion](https://news.ycombinator.com/item?id=48478469)

**Background**: Building document viewers that work reliably at scale is notoriously difficult due to the complexity of PDF, DOCX, and XLSX formats. Many existing solutions are either incomplete, not customizable, or lack polish. Extend UI aims to provide a free, open-source alternative that developers can use and contribute to.

<details><summary>References</summary>
<ul>
<li><a href="https://ui.extend.ai/ui/docs/components/bounding-box-citations">Bounding Box Citations - Extend UI</a></li>
<li><a href="https://www.syncfusion.com/react-components">React UI Component Library for Modern & Responsive Web Apps-Syncfusion</a></li>
<li><a href="https://www.shadcn.io/awesome/item/extend-ui">extend - ui - Components for shadcn/ ui</a></li>

</ul>
</details>

**Discussion**: The community response is positive, with praise for the bounding box demos and potential use in AI document workflows. Some users noted performance issues on the homepage and asked about virtualized rendering, while others requested clearer indication that these are React components.

**Tags**: `#open-source`, `#UI components`, `#document processing`, `#React`, `#PDF`

---

<a id="item-10"></a>
## [Quantum Threat Looms Larger for Bitcoin Than Ethereum](https://www.coindesk.com/opinion/2026/06/10/the-quantum-clock-is-ticking-it-s-bitcoin-s-problem-not-ethereum-s) ⭐️ 7.0/10

A new opinion piece argues that quantum computing poses a greater existential threat to Bitcoin's security than to Ethereum's, due to differences in cryptographic assumptions and upgrade paths. This analysis highlights a critical vulnerability in Bitcoin's cryptographic foundation that could undermine trust in the entire cryptocurrency ecosystem if quantum computers become powerful enough. Bitcoin relies on ECDSA signatures that are vulnerable to Shor's algorithm, while Ethereum uses a more flexible account model that could facilitate a smoother transition to quantum-resistant cryptography.

rss · CoinDesk · Jun 10, 16:07

**Background**: Quantum computers could break the elliptic curve cryptography used in Bitcoin and many other cryptocurrencies. Bitcoin's UTXO model and lack of a native upgrade path make it harder to migrate to quantum-safe addresses compared to Ethereum's account-based system.

<details><summary>References</summary>
<ul>
<li><a href="https://bitcoinops.org/en/topics/quantum-resistance/">Quantum resistance - Bitcoin Optech</a></li>
<li><a href="https://bitcoinmagazine.com/news/googles-quantum-research-harden-bitcoin">Google's New Quantum Research Renews Push To Secure Bitcoin</a></li>
<li><a href="https://www.gate.com/learn/articles/quantum-computing-and-bitcoin-real-risks-technological-limits-and-response-strategies-as-of-2026">Quantum Computing and Bitcoin: Real Risks and Response ...</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#cryptocurrency`, `#Bitcoin`, `#Ethereum`, `#cryptography`

---

<a id="item-11"></a>
## [Mastercard Unveils AI Agent Payment Infrastructure](https://www.coindesk.com/business/2026/06/10/mastercard-prepares-for-a-future-where-ai-agents-make-payments-with-latest-introduction) ⭐️ 7.0/10

Mastercard has launched Agent Pay for Machines, a new infrastructure that enables autonomous AI agents to make payments using cards, bank accounts, and stablecoins. This system supports high-volume, low-value transactions with continuous, always-on capability. This marks a significant step toward integrating AI agents into the financial system, potentially transforming automated services like cloud computing, IoT, and digital content consumption. It positions Mastercard at the forefront of machine-to-machine payments, a rapidly growing market. Agent Pay for Machines includes credentialing, controls, and guaranteed settlement across multiple payment types. It is designed for high-frequency, low-value transactions, enabling AI agents to pay for services autonomously within defined permissions.

rss · CoinDesk · Jun 10, 16:00

**Background**: AI agents are software programs that can perform tasks autonomously, such as booking services or purchasing compute resources. Traditionally, payments required human intervention, but as AI agents become more common, there is a need for payment systems that can handle machine-initiated transactions securely and at scale. Mastercard's new infrastructure addresses this by providing a trusted framework for agent payments.

<details><summary>References</summary>
<ul>
<li><a href="https://www.mastercard.com/us/en/news-and-trends/press/2026/june/mastercard-launches-agent-pay-for-machines.html">Mastercard launches Agent Pay for Machines to unlock super-fast ...</a></li>
<li><a href="https://investor.mastercard.com/investor-news/investor-news-details/2026/Mastercard-Launches-Agent-Pay-for-Machines-to-Unlock-Super-Fast-Always-On-Payments/default.aspx">Mastercard Launches Agent Pay for Machines to Unlock Super-Fast ...</a></li>
<li><a href="https://www.mastercard.com/us/en/business/artificial-intelligence/mastercard-agent-pay/agent-pay-for-machines.html">Mastercard Agent Pay for Machines</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#payments`, `#Mastercard`, `#fintech`, `#autonomous systems`

---

<a id="item-12"></a>
## [Japan's Top Banks Plan Joint Stablecoin by March](https://www.coindesk.com/business/2026/06/10/japan-s-three-largest-banks-aim-for-joint-stablecoin-issue-by-march) ⭐️ 7.0/10

Japan's three largest banks—MUFG Bank, Mizuho Bank, and SMBC—have formed a council to develop frameworks for jointly issuing a stablecoin by March 2027. This collaboration among major financial institutions signals significant institutional adoption of cryptocurrency and could set a regulatory precedent for stablecoin issuance in Japan and globally. The banks aim to issue the stablecoin within fiscal year 2026, which ends in March 2027. The council will explore operational frameworks and oversee the issuance process.

rss · CoinDesk · Jun 10, 09:01

**Background**: A stablecoin is a type of cryptocurrency designed to maintain a stable value relative to a reference asset, such as the US dollar. Japan has been proactive in regulating cryptocurrencies, and this joint effort by its largest banks represents a major step toward mainstream adoption of digital assets.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/06/10/japan-s-three-largest-banks-aim-for-joint-stablecoin-issue-by-march">Japan's three largest banks aim for joint stablecoin issue by March</a></li>
<li><a href="https://www.fintechfutures.com/blockchain-crypto-digital-assets/mufg-smbc-and-mizuho-to-launch-joint-stablecoin">MUFG, SMBC, and Mizuho to launch joint stablecoin - FinTech Futures</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#banking`, `#Japan`, `#cryptocurrency`, `#finance`

---

<a id="item-13"></a>
## [Anthropic CEO Calls for AI Regulation While Nearing IPO](https://decrypt.co/370704/anthropic-ceo-ai-too-powerful-regulation-cant-wait) ⭐️ 7.0/10

Anthropic CEO Dario Amodei published an essay advocating for binding safety rules for frontier AI models as his company prepares for an initial public offering (IPO). This highlights a key tension in the AI industry: companies developing the most powerful AI systems are also calling for regulation, which could shape future AI governance and public trust. Anthropic has confidentially filed for an IPO with a potential valuation of $1 trillion, and Amodei's essay emphasizes the need for rules before frontier models become too powerful.

rss · Decrypt · Jun 10, 21:31

**Background**: Frontier AI models are the most advanced AI systems available, trained on massive datasets to deliver state-of-the-art performance across many tasks. Anthropic, the maker of the Claude AI assistant, is one of the leading companies in this space and is now moving toward going public.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nvidia.com/en-us/glossary/frontier-models/">What Are Frontier AI Models and How They Work - NVIDIA</a></li>
<li><a href="https://www.zacks.com/featured-articles/761/anthropic-ipo">Anthropic IPO 2026 Guide: Price Predictions, Dates, and ...</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#regulation`, `#Anthropic`, `#frontier models`, `#AI governance`

---

<a id="item-14"></a>
## [Tether, Nvidia, Amazon Back NEURA in $1.4B Round](https://decrypt.co/370691/tether-nvidia-amazon-back-neura-robotics-1-4-billion-funding-round) ⭐️ 7.0/10

Stablecoin issuer Tether led a $1.4 billion Series C funding round for German humanoid robotics firm NEURA, with participation from Nvidia and Amazon. NEURA plans to integrate crypto payment tools and edge AI into its humanoid robots. This investment signals growing convergence between crypto, AI, and robotics, with major tech and finance players betting on humanoid robots for industrial and commercial use. It could accelerate adoption of crypto payments in physical robotics and edge AI deployment. NEURA's flagship humanoid robot, 4NE1, is designed for work and life and has already reached its third generation. The company is also developing a service bot called MiPA and has partnerships with Nvidia for AI integration.

rss · Decrypt · Jun 10, 19:30

**Background**: Humanoid robots are designed to mimic human movements and perform tasks in environments built for people. Edge AI processes data locally on the device rather than in the cloud, enabling faster response times and offline operation. Tether is the largest stablecoin issuer, and its involvement suggests a push to integrate crypto payments into physical hardware.

<details><summary>References</summary>
<ul>
<li><a href="https://neura-robotics.com/products/4ne1/">Humanoid Robot 4NE1 for Work and Life | NEURA Robotics</a></li>
<li><a href="https://www.robotics247.com/article/automatica-2025-neura-robotics-unveils-3rd-generation-4ne1-humanoid">Automatica 2025: NEURA Robotics unveils 3rd... - Robotics 24/7</a></li>
<li><a href="https://chozan.co/neura-robotics/">NEURA Robotics Is Germany's Bet on Physical AI for Industry - ChoZan</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#funding`, `#AI`, `#crypto`, `#humanoid`

---

<a id="item-15"></a>
## [MIT Study: AI Helps Spot Fake News but Hurts Long-Term Skills](https://decrypt.co/370675/ai-helped-people-spot-fake-news-made-them-worse-mit) ⭐️ 7.0/10

An MIT study found that AI assistants improved participants' ability to detect misinformation in the short term, but later tests showed they became worse at identifying falsehoods independently. This counterintuitive finding highlights a potential downside of relying on AI for fact-checking: cognitive offloading may weaken users' own critical thinking and media literacy over time. The study involved participants using AI tools to evaluate news headlines; while accuracy improved during the task, subsequent independent assessments revealed a decline in their ability to spot fake news without AI assistance.

rss · Decrypt · Jun 10, 18:40

**Background**: AI assistants are increasingly used to combat misinformation, but concerns about over-reliance and skill degradation have been raised. Cognitive offloading occurs when people depend on technology to perform tasks they would otherwise do themselves, potentially reducing their own competence.

**Tags**: `#AI`, `#misinformation`, `#cognitive science`, `#media literacy`, `#MIT`

---

<a id="item-16"></a>
## [Stellar Unveils 3-Phase Quantum Readiness Roadmap](https://decrypt.co/370570/quantum-clock-ticking-bitcoin-crypto-how-stellar-preparing) ⭐️ 7.0/10

The Stellar Development Foundation has announced a three-step roadmap to protect its network from future quantum computing threats, aiming to upgrade the XLM blockchain's cryptographic algorithms to be quantum-resistant. This proactive move is significant because quantum computers could eventually break the cryptographic foundations of Bitcoin and other cryptocurrencies, threatening billions in assets. Stellar's plan sets a precedent for other blockchain networks to follow, potentially accelerating industry-wide adoption of quantum-safe cryptography. The roadmap includes three phases: first, enabling hash-based signatures as an additional signing option; second, making hash-based signatures the default; and third, fully migrating to a quantum-resistant signature scheme. The transition is expected to be backward-compatible and minimize disruption.

rss · Decrypt · Jun 9, 19:49

**Background**: Quantum computers leverage qubits to perform certain calculations exponentially faster than classical computers, posing a threat to public-key cryptography like Ed25519 used by Stellar and ECDSA used by Bitcoin. While large-scale quantum attacks are still years away, experts warn that legacy wallets with exposed public keys could be vulnerable sooner. Hash-based signatures, such as SPHINCS+, are considered promising quantum-resistant alternatives.

<details><summary>References</summary>
<ul>
<li><a href="https://www.reddit.com/r/Stellar/comments/1jg3qep/is_stellar_xlm_prepared_for_the_threat_of_quantum/">Is Stellar (XLM) Prepared for the Threat of Quantum Computing?</a></li>
<li><a href="https://www.facebook.com/cryptomining120/posts/stellar-reveals-3-phase-quantum-readiness-roadmapthe-stellar-development-foundat/1306150485023325/">Stellar Reveals 3-Phase Quantum Readiness Roadmap ... - Facebook</a></li>
<li><a href="https://www.circle.com/blog/preparing-blockchains-for-q-day">How Blockchains are Preparing for Quantum Computing | Circle</a></li>

</ul>
</details>

**Discussion**: Community comments on Reddit and Facebook show mixed reactions: some praise Stellar for being proactive, while others question the timeline and feasibility. A Reddit user noted that quantum resistance was not a major narrative until recently, and Vitalik Buterin has urged blockchains to move toward full quantum resistance as soon as possible.

**Tags**: `#quantum computing`, `#blockchain`, `#cryptocurrency`, `#security`, `#Stellar`

---

<a id="item-17"></a>
## [Sequoyah's Syllabary: A Written Language for Cherokee](https://www.smithsonianmag.com/innovation/man-created-written-language-cherokee-did-efficiently-elegantly-peers-thought-magic-180988850/) ⭐️ 6.0/10

An article from Smithsonian Magazine highlights Sequoyah's creation of the Cherokee syllabary in the early 1820s, a highly efficient writing system that enabled mass literacy among the Cherokee people. This achievement is one of the few known instances where a single individual created a fully functional writing system from scratch, leading to near-universal literacy among the Cherokee within a quarter-century and surpassing surrounding European-American settlers. The syllabary consists of 85 (originally 86) characters, each representing a syllable, and was officially adopted by the Cherokee Nation in 1825. Sequoyah was illiterate before creating the syllabary, making his accomplishment even more remarkable.

hackernews · grahambargeron · Jun 10, 22:07 · [Discussion](https://news.ycombinator.com/item?id=48483387)

**Background**: A syllabary is a writing system where each symbol represents a syllable, unlike an alphabet where symbols represent individual phonemes. Sequoyah's syllabary was inspired by his observation of European writing, but he adapted it specifically for the Cherokee language, using characters that resemble Latin, Greek, and Cyrillic letters but with different sound values.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cherokee_syllabary">Cherokee syllabary</a></li>
<li><a href="https://en.wikipedia.org/wiki/Sequoyah">Sequoyah</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the article's title was misleading, as Sequoyah's peers thought his writing was magic due to unfamiliarity with writing, not because of its efficiency. Some criticized the article for lacking examples of the glyphs, calling it clickbait, while others praised the syllabary's phonetic accuracy compared to English orthography.

**Tags**: `#linguistics`, `#history`, `#writing systems`, `#Cherokee`

---

<a id="item-18"></a>
## [GeoLibre 1.0: Browser-Based GIS Tool Released](https://geolibre.app/) ⭐️ 6.0/10

GeoLibre 1.0, a free and open-source browser-based GIS platform, has been released, aiming to provide a lightweight alternative to QGIS and ArcGIS Online. This release could lower the barrier to entry for geospatial analysis by offering a cloud-native, subscription-free tool that runs directly in the browser, making GIS more accessible to non-profits and casual users. GeoLibre is built with Tauri, React, TypeScript, and MapLibre GL, and includes a shareable viewer (share.geolibre.app). However, early users report IO errors with file loading and performance issues with large datasets over 1GB.

hackernews · jonbaer · Jun 10, 17:39 · [Discussion](https://news.ycombinator.com/item?id=48479852)

**Background**: Geographic Information Systems (GIS) are used to visualize, analyze, and interpret spatial data. Traditional desktop GIS like QGIS are powerful but require installation and can be resource-intensive, while cloud services like ArcGIS Online often require subscriptions. Browser-based GIS tools aim to combine accessibility with functionality.

<details><summary>References</summary>
<ul>
<li><a href="https://geolibre.app/">GeoLibre 1.0</a></li>
<li><a href="https://www.reddit.com/r/gis/comments/1u26y2y/geolibre_a_free_opensource_cloudnative_gis_that/">GeoLibre: A Free, Open-Source Cloud-Native GIS That Runs ... - Reddit</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some users are excited about the convenience and sharing features, while others report technical issues like IO errors and poor performance with large files. There is also criticism that the marketing overemphasizes mobile adaptation, which is standard for modern websites.

**Tags**: `#GIS`, `#open source`, `#web application`, `#geospatial`

---

<a id="item-19"></a>
## [Raspberry Pi 5 16GB RAM Variant Launched at $120](https://www.adafruit.com/product/6125?src=raspberrypi) ⭐️ 6.0/10

Raspberry Pi has released a 16GB RAM variant of the Raspberry Pi 5 single-board computer, priced at $120, amid a global memory price surge. This variant addresses the need for more memory in demanding applications like AI inference and multitasking, but the higher price reflects broader memory cost increases affecting the entire single-board computer market. The 16GB Pi 5 uses LPDDR4X memory, which has seen a 700% price increase since Q4 2024, according to community comments. The board retains the same Broadcom BCM2712 SoC and features as other Pi 5 models.

hackernews · akman · Jun 10, 20:05 · [Discussion](https://news.ycombinator.com/item?id=48481857)

**Background**: The Raspberry Pi 5 is a single-board computer with a Broadcom BCM2712 quad-core ARM Cortex-A76 processor and VideoCore VII GPU. Memory prices have surged globally due to supply constraints, with DDR5 and LPDDR4X costs rising sharply in 2025-2026.

<details><summary>References</summary>
<ul>
<li><a href="https://www.raspberrypi.com/products/raspberry-pi-5/">Buy a Raspberry Pi 5 – Raspberry Pi</a></li>
<li><a href="https://spectrum.ieee.org/ram-shortage-price-increase">RAM Shortage Drives Up Low-Cost Computer Prices - IEEE Spectrum</a></li>
<li><a href="https://www.hackster.io/news/memory-pricing-leads-to-a-5-25-price-hike-for-the-raspberry-pi-5-single-board-computer-family-26f2aee18ce5">Memory Pricing Leads to a $5-25 Price Hike for the Raspberry Pi 5 ...</a></li>

</ul>
</details>

**Discussion**: Commenters noted that memory prices have risen 90% overall and 700% for Pi 5 memory, making the 16GB variant relatively affordable compared to retail prices. Some questioned the use case, while others highlighted that used Pi 5s retain high resale value.

**Tags**: `#Raspberry Pi`, `#hardware`, `#single-board computer`, `#memory pricing`

---

<a id="item-20"></a>
## [Ethereum Developers Propose pERC-20 for Privacy](https://www.coindesk.com/tech/2026/06/10/privacy-returns-to-focus-as-ethereum-developers-explore-new-token-standards) ⭐️ 6.0/10

Ethereum developers have proposed a new token standard called pERC-20, which allows users to hold and transfer tokens without publicly revealing balances, transaction amounts, or counterparties. This proposal marks a renewed focus on privacy within the Ethereum ecosystem, potentially enabling institutional adoption of stablecoins and DeFi applications that require confidentiality. Unlike standard ERC-20 tokens, which display balances and transaction histories publicly on-chain, pERC-20 uses advanced cryptographic techniques like zk-SNARKs and zk-STARKs to obscure sensitive details.

rss · CoinDesk · Jun 10, 18:14

**Background**: Token standards define how tokens behave and interact across the Ethereum ecosystem. The current default, ERC-20, makes all transactions publicly visible, similar to a public bank account. Privacy-focused standards like pERC-20 aim to balance user confidentiality with regulatory compliance.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/06/10/privacy-returns-to-focus-as-ethereum-developers-explore-new-token-standards">Ethereum (ETH) developers are exploring new token standards ...</a></li>
<li><a href="https://ethereum.org/developers/docs/standards/tokens">Token Standards - ethereum.org</a></li>
<li><a href="https://coinalertnews.com/news/2026/06/10/ethereum-starknet-privacy-standards">Privacy Takes Center Stage as Ethereum and Starknet Propose ...</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#privacy`, `#token standards`, `#blockchain`

---

<a id="item-21"></a>
## [Raydium Exploit Drains $1.34M, Treasury to Cover Losses](https://decrypt.co/370700/solana-exchange-raydium-exploit-defi-attacks-grow) ⭐️ 6.0/10

Solana-based decentralized exchange Raydium suffered a $1.34 million exploit that drained funds from five inactive liquidity pools, and the protocol announced it will fully compensate affected users from its treasury. This incident highlights ongoing security challenges in DeFi, particularly on high-speed chains like Solana, and underscores the importance of treasury reserves for user protection. The exploit targeted deprecated AMM V3 pools that were no longer active, and the stolen assets had a market value of approximately $1.34 million.

rss · Decrypt · Jun 10, 20:19

**Background**: Raydium is a leading automated market maker (AMM) on Solana, enabling users to trade tokens and provide liquidity. DeFi exploits have become increasingly common, with Solana experiencing several major incidents in 2022 alone. Deprecated pools often have weaker security oversight, making them attractive targets.

<details><summary>References</summary>
<ul>
<li><a href="https://www.facebook.com/coingecko/posts/news-raydium-suffered-a-134m-exploit-affecting-deprecated-liquidity-poolsthe-pro/1441219141383696/">Raydium suffered a $1.34M exploit affecting deprecated liquidity pools ...</a></li>
<li><a href="https://x.com/0xINFRA/status/2064738005697384476">Raydium is aware of an exploit involving unauthorized removal of ...</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#Solana`, `#exploit`

---

<a id="item-22"></a>
## [Botanix Shuts Down Bitcoin L2 Network in July](https://decrypt.co/370671/botanix-shut-down-bitcoin-layer-2-network-lack-defi-demand) ⭐️ 6.0/10

Botanix Labs announced it will shut down its Bitcoin layer-2 network in July 2025, citing a lack of DeFi demand and insufficient fee revenue, and has asked users to withdraw funds by July 9. This shutdown signals that Bitcoin layer-2 DeFi projects may struggle to gain traction, despite broader optimism about Bitcoin DeFi. It highlights the challenge of achieving product-market fit in a niche but capital-intensive space. Botanix Labs raised $8.5 million in 2024 from investors including several Bitcoin influencers. The project failed to generate significant fees or achieve product-market fit, leading to the wind-down.

rss · Decrypt · Jun 10, 18:11

**Background**: Bitcoin layer-2 networks are designed to enable smart contracts and DeFi applications on Bitcoin, which natively lacks such functionality. Botanix was one of several projects attempting to bring DeFi to Bitcoin, but faced low user demand and revenue.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/370671/botanix-shut-down-bitcoin-layer-2-network-lack-defi-demand">Botanix Will Shut Down Bitcoin Layer-2 Network in July ...</a></li>
<li><a href="https://blockonomi.com/botanix-bitcoin-layer-2-network-ceases-operations-amid-insufficient-user-activity/">Botanix Bitcoin Layer 2 Network Ceases Operations Amid ...</a></li>
<li><a href="https://cryptobriefing.com/botanix-bitcoin-layer-2-shutdown/">Botanix to wind down Bitcoin Layer 2 network, urges asset ...</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#Layer-2`, `#DeFi`, `#Shutdown`

---

<a id="item-23"></a>
## [CFTC Proposes Ban on Prediction Markets for Assassination, War Bets](https://decrypt.co/370656/cftc-rules-prediction-markets-ban-wagers-ouster-us-enemies) ⭐️ 6.0/10

The CFTC has proposed a rule that would ban prediction markets on outcomes that could be influenced by war or assassination, even if conflict is not explicitly mentioned. This directly impacts platforms like Polymarket that offer event contracts on geopolitical events. This regulation could significantly restrict the scope of prediction markets, which have grown in popularity for betting on political and military events. It raises questions about free speech, market innovation, and the legal boundaries of event-based derivatives. The proposed rule was submitted to the White House Office of Information and Regulatory Affairs (OIRA) for review, a required step for significant federal rules. It defines 'gaming' and draws a line against micro-bets and injury markets, potentially affecting many existing contracts on Polymarket.

rss · Decrypt · Jun 10, 16:06

**Background**: Prediction markets allow participants to trade shares representing the likelihood of future events, such as election outcomes or military strikes. Polymarket, a leading crypto-based platform, has faced scrutiny for allowing bets on wars and assassinations, with critics citing ethical and legal concerns. The CFTC regulates event contracts under the Commodity Exchange Act, and this rule formalizes its stance after years of litigation.

<details><summary>References</summary>
<ul>
<li><a href="https://www.polymarket101.com/en/docs/guides/polymarket-cftc-rulemaking-2026/">CFTC Prediction Market Rules 2026: White House Review + What It...</a></li>
<li><a href="https://defirate.com/news/cftc-prediction-markets-rule-defines-gaming-draws-line-micro-bets-injury-markets/">CFTC Prediction Markets Rule Defines Gaming, Draws... - DeFi Rate</a></li>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#regulation`, `#CFTC`, `#crypto`

---

<a id="item-24"></a>
## [Industry Groups Push Back on GENIUS Act Stablecoin AML Rules](https://decrypt.co/370645/paradigm-hyperliquid-policy-center-push-back-on-genius-act-stablecoin-aml-rule) ⭐️ 6.0/10

Paradigm and the Hyperliquid Policy Center have publicly opposed the GENIUS Act's stablecoin AML rules, arguing that the legislation lacks clear liability limits for issuers, DeFi applications, and validators once stablecoins change hands. This pushback highlights a critical regulatory gap in the U.S. stablecoin framework, potentially shaping how DeFi intermediaries and validators are treated under future AML laws. The outcome could set precedent for liability in decentralized systems, affecting developers, node operators, and the broader crypto ecosystem. The GENIUS Act requires permitted payment stablecoin issuers to comply with Bank Secrecy Act AML and sanctions rules, but industry groups argue that liability should not extend to DeFi apps and validators that merely facilitate transactions. A recent court ruling found DeFi developers not liable for third-party use of open-source code, which may inform this debate.

rss · Decrypt · Jun 10, 14:33

**Background**: The GENIUS Act is a U.S. legislative proposal that defines how payment stablecoins are issued and regulated, mandating AML compliance for issuers. However, the law's scope of liability for downstream participants like validators and DeFi protocols remains ambiguous, raising concerns about overreach and stifling innovation.

<details><summary>References</summary>
<ul>
<li><a href="https://www.hklaw.com/en/insights/publications/2026/04/fincen-and-ofac-propose-aml-sanctions-rules-for-stablecoin-issuers">FinCEN and OFAC Propose AML/Sanctions Rules for Stablecoin ...</a></li>
<li><a href="https://www.chapman.com/publication-genius-act-rulemaking-tracker">GENIUS Act Rulemaking and Reporting Tracker</a></li>
<li><a href="https://chainscorelabs.com/blog/legal-tech-smart-contracts-and-the-law/on-chain-jurisdiction-and-enforcement/why-validator-liability-is-the-next-multi-billion-dollar-legal-battle">Validator Liability: The Next Multi-Billion Dollar Legal ...</a></li>

</ul>
</details>

**Tags**: `#crypto regulation`, `#stablecoin`, `#DeFi`, `#AML`, `#policy`

---

<a id="item-25"></a>
## [Kalshi Introduces Employer Disclosure to Curb Insider Trading](https://decrypt.co/370618/kalshi-rolls-out-new-safeguards-after-insider-trading-concerns-hit-prediction-markets) ⭐️ 6.0/10

Kalshi, a regulated prediction market, has implemented new rules requiring traders to disclose their employers before trading high-risk markets flagged for potential insider trading or manipulation. This move addresses growing concerns about insider trading in prediction markets, which have surged in popularity but lack traditional securities safeguards. It could set a precedent for other platforms and help maintain market integrity. The employer disclosure requirement applies specifically to high-risk markets flagged by Kalshi, not all contracts. The rule aims to prevent traders from using material nonpublic information obtained through their employment.

rss · Decrypt · Jun 10, 11:05

**Background**: Prediction markets allow users to trade event contracts based on real-world outcomes. Unlike securities, these contracts may not fall under traditional insider trading laws, creating regulatory gaps. Kalshi is a CFTC-regulated exchange, making its self-regulatory actions noteworthy.

<details><summary>References</summary>
<ul>
<li><a href="https://news.bloomberglaw.com/legal-exchange-insights-and-commentary/insider-trading-in-prediction-markets-poses-compliance-risks">Insider Trading in Prediction Markets Poses Compliance Risks</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#insider trading`, `#regulation`, `#Kalshi`

---

<a id="item-26"></a>
## [Ethereum Could Become Fully ZK-Based in 3-5 Years: Lubin](https://www.theblock.co/post/404185/ethereum-fully-zero-knowledge-proof-based-protocol-3-to-5-years-joe-lubin?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Ethereum co-founder Joe Lubin predicted that Ethereum will become a fully zero-knowledge proof (ZK-proof) based protocol within 3 to 5 years, emphasizing that Layer 2 solutions are necessary to achieve infinite capacity for a world computer. This prediction signals a major shift in Ethereum's scaling roadmap, potentially making transactions faster and cheaper while maintaining security. If realized, it could solidify Ethereum's position as the leading smart contract platform and accelerate adoption of ZK technology across the blockchain industry. Lubin did not provide a specific technical roadmap or timeline for the transition. The prediction is speculative and lacks detailed technical analysis, but reflects a growing consensus that ZK-rollups are the most promising scaling solution for Ethereum.

rss · The Block · Jun 10, 15:22

**Background**: Zero-knowledge proofs allow one party to prove to another that a statement is true without revealing any additional information. In blockchain, ZK-rollups bundle thousands of transactions off-chain and submit a single validity proof to the main chain, significantly increasing throughput. Ethereum currently uses Layer 2 solutions like Optimistic rollups and ZK-rollups to scale, but the base layer still processes transactions directly. A fully ZK-based protocol would mean the Ethereum mainnet itself uses zero-knowledge proofs for transaction verification, potentially eliminating the need for separate L2s.

<details><summary>References</summary>
<ul>
<li><a href="https://ethereum.org/developers/docs/scaling/">Scaling - ethereum.org</a></li>
<li><a href="https://www.cryptowisser.com/guides/layer-2-solutions/">A Comprehensive Guide to Layer 2 Solutions: Scaling Ethereum ...</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#zero-knowledge proofs`, `#Layer 2`, `#blockchain`

---

<a id="item-27"></a>
## [NYDFS Proposes Stablecoin Rule Aligned with Federal GENIUS Act](https://www.theblock.co/post/404223/new-york-regulator-proposes-stablecoin-rule-to-align-with-federal-genius-act-adds-reserve-limits?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

The New York Department of Financial Services (NYDFS) has proposed a new stablecoin regulation that aligns with the federal GENIUS Act, introducing reserve concentration caps and mandatory risk management programs. This rule could reshape the stablecoin landscape in New York, a major financial hub, by imposing stricter reserve requirements and risk controls, potentially affecting major issuers like Circle and Paxos. The proposal retains the 100% reserve backing requirement and adds custodian limits, with a public comment period ending June 22.

rss · The Block · Jun 10, 10:38

**Background**: The GENIUS Act is a landmark federal stablecoin law passed in July 2025, creating a regulatory framework for stablecoin issuers. The NYDFS had previously established its own stablecoin framework in 2022, and this proposal aims to harmonize state and federal rules.

<details><summary>References</summary>
<ul>
<li><a href="https://www.lw.com/en/insights/the-genius-act-of-2025-stablecoin-legislation-adopted-in-the-us">The GENIUS Act of 2025 Stablecoin Legislation Adopted in the US</a></li>
<li><a href="https://cryptobriefing.com/nydfs-draft-rules-payment-stablecoins/">NYDFS publishes draft rules for payment stablecoins, comments ...</a></li>
<li><a href="https://www.livebitcoinnews.com/nydfs-targets-circle-and-paxos-with-new-stablecoin-reserve-rules/">NYDFS Targets Circle and Paxos With New Stablecoin Reserve ...</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#regulation`, `#crypto`, `#NYDFS`

---