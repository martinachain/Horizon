---
layout: default
title: "Horizon Summary: 2026-06-06 (EN)"
date: 2026-06-06
lang: en
---

> From 83 items, 17 important content pieces were selected

---

1. [Microsoft open-sources pg_durable for Postgres durable execution](#item-1) ⭐️ 8.0/10
2. [Google Releases Gemma 4 QAT Models for Mobile Efficiency](#item-2) ⭐️ 8.0/10
3. [Claude-3.5 Sonnet May Have Introduced Bugs in rsync](#item-3) ⭐️ 8.0/10
4. [Developers Share 'Oh Shit' Moments with GenAI](#item-4) ⭐️ 8.0/10
5. [Major US Banks Plan Shared Tokenized Deposit Network](#item-5) ⭐️ 8.0/10
6. [Zcash Plummets 38% After Critical Orchard Bug Found](#item-6) ⭐️ 8.0/10
7. [Anthropic Aids NSA Cyber Ops While Calling for AI Pause](#item-7) ⭐️ 8.0/10
8. [Anthropic: AI Now Writes Most of Its Own Code](#item-8) ⭐️ 8.0/10
9. [Solar desalination method avoids salt clogging](#item-9) ⭐️ 7.0/10
10. [UK Government Switches from Stripe to Adyen for Gov.uk Pay](#item-10) ⭐️ 7.0/10
11. [Teardown of Sigma 45mm Lens Reveals Modern Repair Challenges](#item-11) ⭐️ 6.0/10
12. [ISS Astronauts Shelter During Air Leak Repairs](#item-12) ⭐️ 6.0/10
13. [Custom Agent Skill for TDD Sparks Community Debate](#item-13) ⭐️ 6.0/10
14. [Congress Introduces 7 New Crypto Tax Bills](#item-14) ⭐️ 6.0/10
15. [British Teen Sanctioned by Russia Over Crypto Research](#item-15) ⭐️ 6.0/10
16. [Morgan Stanley enables in-kind crypto ETF conversions via lending](#item-16) ⭐️ 6.0/10
17. [Major Banks Plan Tokenized Deposit Network by 2027](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Microsoft open-sources pg_durable for Postgres durable execution](https://github.com/microsoft/pg_durable) ⭐️ 8.0/10

Microsoft has open-sourced pg_durable, a PostgreSQL extension that enables in-database durable execution by providing a SQL DSL for building function graphs and a background worker for reliable orchestration. This brings durable execution capabilities directly into PostgreSQL, allowing developers to build crash-proof workflows without external systems, which could simplify architectures for applications that require high reliability. The extension is built on two Rust libraries: duroxide for the durable task framework and another for orchestration; it is designed for workflows that primarily live inside Postgres, not for those spanning heterogeneous systems.

hackernews · coffeemug · Jun 5, 15:59 · [Discussion](https://news.ycombinator.com/item?id=48414367)

**Background**: Durable execution is a programming model where workflow state is automatically persisted so that execution can resume from the exact point of failure after a crash. Traditional approaches rely on external workflow engines like Temporal or Azure Durable Functions. pg_durable embeds this capability directly into PostgreSQL, reducing operational complexity for database-centric applications.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/microsoft/pg_durable">GitHub - microsoft/pg_durable: PostgreSQL in-database durable execution · GitHub</a></li>
<li><a href="https://temporal.io/blog/what-is-durable-execution">The definitive guide to Durable Execution | Temporal</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion shows mixed reactions: some appreciate the option of in-database queues, while others worry about lack of versioning, testability, and observability compared to external solutions. A user also notes that Azure PostgreSQL lags in supporting such extensions, limiting its practical use on that platform.

**Tags**: `#PostgreSQL`, `#durable execution`, `#open source`, `#Microsoft`, `#database`

---

<a id="item-2"></a>
## [Google Releases Gemma 4 QAT Models for Mobile Efficiency](https://blog.google/innovation-and-ai/technology/developers-tools/quantization-aware-training-gemma-4/) ⭐️ 8.0/10

Google has released quantization-aware training (QAT) models for the Gemma 4 family, optimized for efficient deployment on mobile devices and laptops. These models are available on Hugging Face and can be run locally with tools like LiteRT. This release enables powerful on-device AI inference with reduced memory and compute requirements, making advanced models accessible on consumer hardware. It also signals Google's commitment to open, efficient AI models, potentially accelerating adoption in mobile and edge applications. The QAT models include a 12B parameter version that fits in 6.7GB VRAM under Q4_0 quantization, comfortably within 16GB memory constraints. The models support multimodal inputs including audio and images, as demonstrated by community members running them on Macs.

hackernews · theanonymousone · Jun 5, 16:18 · [Discussion](https://news.ycombinator.com/item?id=48414653)

**Background**: Quantization-aware training (QAT) is a technique that integrates weight precision reduction into the training process, minimizing accuracy loss compared to post-training quantization. Gemma 4 is Google's latest open model family designed for advanced reasoning and agentic workflows, with architectures tailored for different hardware requirements.

<details><summary>References</summary>
<ul>
<li><a href="https://deepmind.google/models/gemma/gemma-4/">Gemma 4 — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/gemma/docs/core">Gemma 4 model overview | Google AI for Developers</a></li>
<li><a href="https://pytorch.org/blog/quantization-aware-training/">Quantization-Aware Training for Large Language Models with PyTorch – PyTorch</a></li>

</ul>
</details>

**Discussion**: The community is highly engaged, with users sharing practical deployment examples on Macs and comparing Google's QAT models with third-party alternatives like Unsloth's quants, which reportedly achieve near-100% accuracy relative to the unquantized BF16 model. Some speculate about potential integration with Apple's upcoming Siri improvements, while others note the rapid pace of Gemma ecosystem releases.

**Tags**: `#quantization`, `#Gemma`, `#on-device AI`, `#model compression`, `#Google`

---

<a id="item-3"></a>
## [Claude-3.5 Sonnet May Have Introduced Bugs in rsync](https://alexispurslane.github.io/rsync-analysis/) ⭐️ 8.0/10

An analysis of rsync commits suggests that Claude-3.5 Sonnet, an LLM, may have introduced bugs by incorrectly converting malloc() calls to calloc(), leading to memory issues in the rsync tool. This highlights the risks of using LLMs for critical open-source development, as subtle bugs can slip through review and affect performance and reliability for millions of users. The bug changed conditional malloc() to unconditional calloc(), forcing memory zeroing for large allocations, which increased memory usage and caused failures on low-memory systems. The commit was later reverted.

hackernews · logicprog · Jun 5, 12:43 · [Discussion](https://news.ycombinator.com/item?id=48411635)

**Background**: rsync is a widely-used open-source file synchronization tool. calloc() initializes allocated memory to zero, which is safer but slower and uses more memory than malloc(). The LLM likely assumed calloc() is always better without considering performance trade-offs.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/RsyncProject/rsync/issues/81">Memory increase in 3.2.2 · Issue #81 · RsyncProject/rsync</a></li>
<li><a href="https://www.anthropic.com/news/claude-3-5-sonnet">Introducing Claude 3.5 Sonnet \ Anthropic</a></li>
<li><a href="https://galileo.ai/blog/claude-3-5-sonnet-complete-guide-ai-capabilities-analysis">Claude 3.5 Sonnet Complete Guide: AI Capabilities & Limits | Galileo</a></li>

</ul>
</details>

**Discussion**: Commenters debated the statistical methodology of the analysis, with some pointing out insufficient statistical power and potential attribution errors. Others noted the irony of using AI to analyze AI-generated code bugs.

**Tags**: `#LLM`, `#code quality`, `#rsync`, `#open source`, `#AI safety`

---

<a id="item-4"></a>
## [Developers Share 'Oh Shit' Moments with GenAI](https://news.ycombinator.com/item?id=48406174) ⭐️ 8.0/10

A Hacker News thread asked developers to recount the moment generative AI shifted from a novelty to a powerful, sometimes alarming tool, with 232 points and 477 comments sharing personal anecdotes. This discussion highlights the real-world impact of generative AI on software engineering, including subtle bugs, over-reliance, and paradigm shifts, underscoring both its transformative potential and risks. Comments reveal specific 'oh shit' moments such as discovering subtle bugs in LLM-generated code weeks later, or realizing a local model could answer complex questions with confident inaccuracies.

hackernews · andrehacker · Jun 4, 23:42

**Background**: Generative AI, including models like DALL-E and ChatGPT, initially impressed with creative outputs but were often dismissed as flawed novelties. Over time, LLMs evolved to assist with coding, leading to both productivity gains and new risks like hidden bugs and over-reliance.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DALL-E">DALL - E - Wikipedia</a></li>
<li><a href="https://www.labellerr.com/blog/best-coding-llms/">5 Open-Source Coding LLMs You Can Run Locally in 2026</a></li>

</ul>
</details>

**Discussion**: Commenters shared varied experiences: one noted subtle bugs in LLM-generated code that only surfaced weeks later, another described running a leaked Meta model locally and being shocked by its confident yet incorrect answers. A third recounted using LLMs for complex data manipulation and later finding errors.

**Tags**: `#generative AI`, `#LLMs`, `#software engineering`, `#AI risks`, `#developer experience`

---

<a id="item-5"></a>
## [Major US Banks Plan Shared Tokenized Deposit Network](https://www.coindesk.com/markets/2026/06/05/jpmorgan-bank-of-america-and-citi-are-going-on-the-blockchain-offensive-with-a-shared-tokenized-network) ⭐️ 8.0/10

JPMorgan, Bank of America, Citi, and Wells Fargo are jointly building a shared tokenized deposit network through The Clearing House, targeting a launch in the first half of 2027. This marks a significant shift by major US banks toward adopting shared blockchain infrastructure for asset settlement, potentially accelerating the tokenization of traditional financial assets and reshaping the banking industry. The network will use tokenized deposits for real-time settlement of tokenized assets, such as stocks and Treasuries, and is expected to launch through The Clearing House by early 2027.

rss · CoinDesk · Jun 5, 09:16

**Background**: Tokenized deposits are digital representations of bank deposits on a blockchain, enabling programmable, real-time settlement. Wall Street firms have been exploring blockchain for years, with initiatives like JPMorgan's Tokenized Collateral Network and DTCC's multi-chain strategy. This shared network aims to create a common standard for interbank settlement of tokenized assets.

<details><summary>References</summary>
<ul>
<li><a href="https://www.blockhead.co/2026/06/05/jp-morgan-citi-us-banks-plan-shared-tokenized-deposit-network-for-2027/">JP Morgan, Citi, US Banks Plan Shared Tokenized Deposit Network ...</a></li>
<li><a href="https://genfinity.io/2026/06/05/jpmorgan-citi-bofa-tokenized-deposit-network-2027/">JPMorgan, Citi, and Bank of America Plan Shared Tokenized Deposit...</a></li>
<li><a href="https://www.jpmorgan.com/kinexys/digital-assets/tokenized-collateral-network">Tokenized Collateral Network on Kinexys Digital Assets | J.P. Morgan</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenization`, `#banking`, `#fintech`

---

<a id="item-6"></a>
## [Zcash Plummets 38% After Critical Orchard Bug Found](https://www.coindesk.com/markets/2026/06/05/zcash-plummets-30-as-developer-reveals-a-major-bug-that-went-undetected-for-four-years) ⭐️ 8.0/10

Shielded Labs disclosed a critical counterfeiting vulnerability in Zcash's Orchard shielded pool that had gone undetected for four years, causing ZEC to drop 38%. This bug could have allowed undetectable creation of unlimited counterfeit ZEC, undermining Zcash's fixed supply and trust in privacy coins. The vulnerability resided in two lines of code within the Orchard circuit and was fixed within days; exploitation is considered unlikely.

rss · CoinDesk · Jun 5, 05:43

**Background**: Zcash is a privacy-focused cryptocurrency based on Bitcoin's codebase, with a fixed total supply of 21 million units. Its Orchard shielded pool is a key privacy component that enables shielded transactions.

<details><summary>References</summary>
<ul>
<li><a href="https://coinpedia.org/price-analysis/zcash-orchard-vulnerability-is-fixed-but-a-trust-crisis-remains-as-supply-concerns-threaten-zec-recovery/">Zcash Orchard Vulnerability Is Fixed, but a Trust Crisis Remains as Supply Concerns Threaten ZEC Recovery</a></li>
<li><a href="https://decrypt.co/370105/zec-crashes-38-as-zcash-discloses-critical-counterfeiting-vulnerability">ZEC Crashes 38% as Zcash Discloses ‘Critical Counterfeiting ...</a></li>
<li><a href="https://news.bitcoin.com/zcash-orchard-counterfeiting-bug-patched/">Zcash Patches Critical Bug Enabling Unlimited Counterfeit ZEC...</a></li>

</ul>
</details>

**Discussion**: Community discussions on the Zcash forum expressed concern over the trust crisis and debated the trade-offs between privacy and security, though many acknowledged the quick fix.

**Tags**: `#cryptocurrency`, `#security`, `#blockchain`, `#bug`, `#Zcash`

---

<a id="item-7"></a>
## [Anthropic Aids NSA Cyber Ops While Calling for AI Pause](https://decrypt.co/370207/anthropic-helping-nsa-hack-china-also-wants-everyone-pause-ai) ⭐️ 8.0/10

Anthropic has embedded approximately six engineers at the NSA to deploy its Mythos AI model for offensive cyber operations, while simultaneously publishing a report warning that AI could soon build itself without human oversight. This reveals a stark contradiction in Anthropic's public stance on AI safety, undermining its moral authority to advocate for an AI pause and raising serious ethical and geopolitical concerns about the dual-use nature of AI. The Mythos model is specifically designed for cybersecurity tasks, and the embedded engineers are helping the NSA use it for offensive purposes. Anthropic's report warns that AI may soon be able to self-improve and operate without human intervention, a scenario it claims to want to prevent.

rss · Decrypt · Jun 5, 19:18

**Background**: Anthropic is an AI safety company founded by former OpenAI employees, known for its Claude model. The NSA is a U.S. intelligence agency responsible for signals intelligence and cybersecurity. Offensive cyber operations involve hacking into adversary systems, which contrasts with Anthropic's stated mission of developing safe and ethical AI.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tomshardware.com/tech-industry/artificial-intelligence/nsa-using-clause-mythos-for-offensive-cyber-operations-report-claims-says-half-a-dozen-anthropic-engineers-embedded-inside-the-agency">NSA using Claude Mythos for ' offensive cyber operations ,' report...</a></li>
<li><a href="https://digg.com/ai/1vgo2yxi">Anthropic embeds six engineers at the NSA to deploy its Mythos AI...</a></li>
<li><a href="https://cryptobriefing.com/anthropic-nsa-mythos-ai-cyber-operations/">Anthropic embeds engineers at NSA to deploy Mythos AI for cyber ...</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#ethics`, `#cybersecurity`, `#Anthropic`, `#NSA`

---

<a id="item-8"></a>
## [Anthropic: AI Now Writes Most of Its Own Code](https://decrypt.co/370089/ai-already-developing-ai-anthropic-humans-slowing-things-down) ⭐️ 8.0/10

Anthropic reports that AI systems now write most of their own code and manage increasingly complex research tasks, with humans primarily selecting which problems to solve. This marks a significant step toward recursive self-improvement, where AI can accelerate its own development, potentially outpacing human oversight and raising critical safety concerns. The shift means humans are increasingly becoming problem selectors rather than problem solvers, which could slow down AI progress if human decision-making becomes a bottleneck.

rss · Decrypt · Jun 4, 21:37

**Background**: Recursive self-improvement refers to AI systems that can improve their own capabilities without human intervention. Anthropic, a leading AI safety company, has been researching this area, noting that full recursive self-improvement could increase risks of losing control over AI systems.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/">Home \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/institute/recursive-self-improvement">Our progress toward recursive self - improvement , and its implications.</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Anthropic`, `#AI development`, `#automation`, `#AI safety`

---

<a id="item-9"></a>
## [Solar desalination method avoids salt clogging](https://www.rochester.edu/newscenter/what-is-desalination-definition-ocean-water-704732/) ⭐️ 7.0/10

Researchers at the University of Rochester have developed a solar-powered desalination method that uses capillary action to prevent salt clogging, but it remains at lab scale. This innovation could address water scarcity by providing a more sustainable desalination process that avoids the common problem of salt buildup, potentially reducing maintenance and energy costs. The system uses specially engineered black metal to absorb sunlight and capillary action to move salt away from the active area, but a mechanism to remove the accumulated salt is yet to be developed.

hackernews · speckx · Jun 5, 15:04 · [Discussion](https://news.ycombinator.com/item?id=48413500)

**Background**: Desalination removes salt from seawater to produce fresh water, but conventional methods often suffer from salt clogging, which reduces efficiency and requires frequent maintenance. Solar-powered desalination uses sunlight as an energy source, making it potentially more sustainable. Capillary action is the ability of a liquid to flow in narrow spaces without external forces, similar to how water moves through a plant stem.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Solar-powered_desalination_unit">Solar - powered desalination unit - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Capillary_action">Capillary action - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the method is still at lab scale and the salt removal mechanism needs demonstration. Some raised energy efficiency concerns, suggesting comparison with solar panels driving conventional desalination. Others referenced a similar article posted earlier.

**Tags**: `#desalination`, `#water`, `#solar energy`, `#research`

---

<a id="item-10"></a>
## [UK Government Switches from Stripe to Adyen for Gov.uk Pay](https://www.theregister.com/public-sector/2026/06/04/govuk-goes-dutch-on-payments-as-it-dumps-stripe/5250763) ⭐️ 7.0/10

The UK Government Digital Service (GDS) has replaced Stripe with Dutch payment provider Adyen as the payment services provider for GOV.UK Pay, citing cost and strategic reasons. This switch highlights the UK government's push for cost efficiency and strategic autonomy in critical digital infrastructure, potentially influencing other public sector payment decisions across Europe. The contract value was noted as surprisingly small in community comments, and Adyen is known for requiring a minimum transaction volume of around €1 million, which may limit its accessibility for smaller entities.

hackernews · toomuchtodo · Jun 5, 16:55 · [Discussion](https://news.ycombinator.com/item?id=48415217)

**Background**: GOV.UK Pay is a government-built online payment service that allows public sector organizations to accept payments securely. Stripe and Adyen are both major payment processors, but Adyen operates as a direct processor and also supports point-of-sale payments, while Stripe is known for its developer-friendly tools and marketing.

<details><summary>References</summary>
<ul>
<li><a href="https://www.adyen.com/press-and-media/adyen-payments-gov-uk">Adyen selected as payment services provider for GOV.UK Pay</a></li>
<li><a href="https://www.adyen.com/online-payments">Online payments | Making online payments easy - Adyen</a></li>
<li><a href="https://fitsmallbusiness.com/adyen-payments-review/">Adyen Review: Is It Right for Your Business?</a></li>

</ul>
</details>

**Discussion**: Community comments expressed surprise at the small contract size, with some noting that government contracts can be much smaller than corporate cloud bills. Others wished Adyen had better marketing like Stripe, while some praised the move away from 'hostile Americanism' and suggested passing transaction costs to users to encourage bank transfers.

**Tags**: `#fintech`, `#government`, `#payments`, `#Stripe`, `#Adyen`

---

<a id="item-11"></a>
## [Teardown of Sigma 45mm Lens Reveals Modern Repair Challenges](https://salvagedcircuitry.com/sigma-45mm.html) ⭐️ 6.0/10

A detailed teardown and repair of a Sigma 45mm camera lens was published, showcasing the complexity of modern lens construction and the techniques required for successful repair. This teardown highlights how modern lenses have become intricate electronic devices, making repair increasingly difficult for hobbyists and professionals alike, which impacts the right-to-repair movement and sustainability. The lens features a USB-C port for firmware updates, and the repair involved handling delicate flex cables, tiny screws, and surface-mount components. The author notes that JIS screwdrivers are essential to avoid stripping screws.

hackernews · transistor-man · Jun 6, 00:33 · [Discussion](https://news.ycombinator.com/item?id=48420148)

**Background**: Camera lenses have evolved from simple glass-and-metal assemblies to complex systems with autofocus motors, image stabilization, and electronic aperture control. Modern lenses often include firmware and digital communication, making them similar to miniature computers. Repairing them requires specialized tools and knowledge of both optics and electronics.

**Discussion**: Commenters praised the teardown as one of the best they've seen, and shared insights on fuses (noting they prevent fires, not protect components), the importance of JIS vs PH screwdrivers, and the growing trend of USB-C ports and firmware updates in modern lenses.

**Tags**: `#camera lens`, `#repair`, `#teardown`, `#electronics`, `#hardware`

---

<a id="item-12"></a>
## [ISS Astronauts Shelter During Air Leak Repairs](https://www.bbc.com/news/live/c4g44ew3g1kt) ⭐️ 6.0/10

Astronauts on the International Space Station were instructed to shelter in place for about two hours while Russian crew conducted repairs on an ongoing air leak in the Zvezda service module transfer tunnel (PrK). NASA later paused the repair efforts to assess additional data. This event highlights the persistent challenges of maintaining aging space infrastructure and the critical importance of leak detection and safety protocols for crew survival. The ongoing leak, first detected in 2019, underscores the need for robust repair techniques and contingency planning on the ISS. The leak is located in the Russian Orbital Segment's PrK tunnel, which connects the Zvezda module to docked spacecraft. Despite multiple repair attempts, the station loses about one pound of air pressure per day. NASA's Robotic External Leak Locator (RELL) uses a mass spectrometer and ion vacuum pressure gauge to detect ammonia leaks externally.

hackernews · janpot · Jun 5, 15:00 · [Discussion](https://news.ycombinator.com/item?id=48413464)

**Background**: The International Space Station (ISS) is a modular space station in low Earth orbit, hosting international crews for research and maintenance. Air leaks can occur due to micrometeoroid impacts or material degradation, and are detected via pressure sensors. The PrK tunnel is a known problem area, and repairs often involve applying sealants and monitoring pressure changes.

<details><summary>References</summary>
<ul>
<li><a href="https://www.usatoday.com/story/graphics/2026/06/05/iss-air-leak-nasa-graphics/90419828007/">Visuals show how an ISS air leak forced astronauts to briefly shelter</a></li>
<li><a href="https://www.theguardian.com/science/live/2026/jun/05/international-space-station-astronauts-evacuation-air-leak-latest-news-updates">Nasa tells astronauts to return to International Space Station as air ...</a></li>
<li><a href="https://www.scientificamerican.com/article/astronauts-take-shelter-on-the-international-space-station-due-to-air-leaks/">Astronauts take shelter on the International Space Station due to air ...</a></li>

</ul>
</details>

**Discussion**: Commenters discussed leak detection technology like NASA's RELL, questioned why astronauts needed to shelter if airlocks exist between modules, and wondered about escape pod availability. Some expressed confusion over the phrasing of repair outcomes, while others suggested simpler fixes like painting the module.

**Tags**: `#ISS`, `#space`, `#engineering`, `#leak detection`

---

<a id="item-13"></a>
## [Custom Agent Skill for TDD Sparks Community Debate](https://www.saturnci.com/my-agent-skill-for-test-driven-development.html) ⭐️ 6.0/10

A blog post on SaturnCI describes a custom agent skill for test-driven development (TDD) that instructs AI coding agents to follow the red-green-refactor cycle. The skill is designed to work with tools like Claude Code, Cursor, and Codex CLI. This approach aims to improve code quality by forcing AI agents to write tests before implementation, but community feedback highlights practical trade-offs. The discussion reflects broader tensions between ideal TDD practices and real-world constraints like token costs and test hallucination. The skill is available via PromptCreek and other repositories, and can be installed with a single npx command. Community members note that TDD can balloon token costs and slow velocity, especially in multi-agent setups, and that some generated tests may be superficial hallucinations.

hackernews · laxmena · Jun 4, 14:10 · [Discussion](https://news.ycombinator.com/item?id=48398925)

**Background**: Test-driven development (TDD) is a software development practice where tests are written before the code that makes them pass, following a red-green-refactor loop. AI agent skills are reusable instruction sets that guide large language models (LLMs) to perform specific tasks consistently. The concept of encoding TDD as a skill aims to automate this workflow within AI-assisted coding environments.

<details><summary>References</summary>
<ul>
<li><a href="https://www.promptcreek.com/skills/test-driven-development">Test Driven Development — Agent Skill | PromptCreek</a></li>
<li><a href="https://antigravity.codes/agent-skills/testing/test-driven-development">test - driven - development - Agent Skill for Claude Code, Cursor...</a></li>
<li><a href="https://www.aihero.dev/skills-tdd">tdd : Red, Green, Refactor for Agentic Coding</a></li>

</ul>
</details>

**Discussion**: Commenters express mixed opinions: some praise the structured approach and share their own workflows, while others warn about token cost increases and test hallucination. A few argue that direct instructions in AGENTS.md are more effective than a dedicated skill, and that TDD may not suit all agentic development scenarios.

**Tags**: `#TDD`, `#AI agents`, `#software engineering`, `#LLM`

---

<a id="item-14"></a>
## [Congress Introduces 7 New Crypto Tax Bills](https://decrypt.co/370197/congress-7-crypto-tax-bills) ⭐️ 6.0/10

The U.S. Congress has introduced seven new crypto tax bills, the first such legislation to be deliberated by congressional leadership, with a House hearing scheduled for Tuesday. These bills could significantly impact how cryptocurrencies are taxed in the U.S., affecting investors, developers, and businesses in the crypto ecosystem. The bills cover various aspects of crypto taxation, including reporting requirements, tax treatment of digital assets, and potential exemptions for small transactions.

rss · Decrypt · Jun 5, 18:13

**Background**: Cryptocurrency taxation has been a complex issue due to the decentralized and pseudonymous nature of digital assets. The U.S. government has been working to clarify tax rules for crypto transactions, and these bills represent a significant step toward formalizing regulations.

**Tags**: `#cryptocurrency`, `#tax`, `#regulation`, `#policy`

---

<a id="item-15"></a>
## [British Teen Sanctioned by Russia Over Crypto Research](https://decrypt.co/370002/british-teen-sanctioned-russia-alleging-crypto-evade-sanctions) ⭐️ 6.0/10

Russia imposed sanctions on a British teenager after he researched alleged Russian use of cryptocurrency to evade international sanctions. This incident highlights the growing geopolitical tensions surrounding cryptocurrency and its potential use in sanctions evasion, showing that even individual researchers can face retaliation. The teenager's research focused on Russia's alleged illicit crypto flows, which prompted Moscow's retaliatory sanctions. The specific details of the sanctions or the teenager's identity have not been disclosed.

rss · Decrypt · Jun 4, 14:27

**Background**: Cryptocurrencies can be used to evade sanctions because transactions are not processed by commercial banks and can be difficult to trace. Russia has been accused of using crypto to bypass Western sanctions imposed after its invasion of Ukraine. Several reports have documented Russian entities using Tether and other cryptocurrencies to move funds.

<details><summary>References</summary>
<ul>
<li><a href="https://www.csis.org/analysis/cryptocurrencies-and-us-sanctions-evasion-implications-russia">Cryptocurrencies and U.S. Sanctions Evasion: Implications for Russia</a></li>
<li><a href="https://www.chainalysis.com/blog/russias-cryptocurrency-legislated-sanctions-evasion/">Russia ’s Cryptocurrency Pivot: Legislated Sanctions Evasion</a></li>
<li><a href="https://finintegrity.org/russian-use-of-crypto-sanctions-evasion-on-rise/">Russian Use of Crypto for Sanctions Evasion on the Rise</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#geopolitics`, `#sanctions`, `#blockchain`

---

<a id="item-16"></a>
## [Morgan Stanley enables in-kind crypto ETF conversions via lending](https://www.theblock.co/post/403825/morgan-stanley-clients-lend-bitcoin-in-kind-spot-crypto-etf-conversions?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Morgan Stanley Wealth Management has partnered with Galaxy Digital to allow eligible clients to lend bitcoin and other cryptocurrencies in exchange for crypto ETP shares, enabling in-kind spot crypto ETF conversions. This service streamlines the process for institutional investors to gain exposure to crypto ETFs without needing to sell their holdings, potentially increasing liquidity and adoption in the crypto market. The partnership focuses on in-kind conversions, where clients lend crypto assets directly to create ETF shares, differing from cash-create models used in US spot Bitcoin ETFs.

rss · The Block · Jun 5, 15:06

**Background**: Spot crypto ETFs allow investors to gain exposure to cryptocurrencies without directly holding them. In-kind creation involves exchanging the underlying asset for ETF shares, which can be more tax-efficient and operationally simpler than cash creation. Morgan Stanley is a major wealth management firm, and Galaxy Digital is a crypto financial services company.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/403825/morgan-stanley-clients-lend-bitcoin-in-kind-spot-crypto-etf-conversions">Morgan Stanley lets clients lend bitcoin and other assets for in - kind ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#institutional finance`, `#ETF`, `#Morgan Stanley`, `#Galaxy Digital`

---

<a id="item-17"></a>
## [Major Banks Plan Tokenized Deposit Network by 2027](https://www.theblock.co/post/403701/jpmorgan-citi-major-banks-tokenized-deposit-network?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

A consortium of major banks including JPMorgan and Citi plans to launch a tokenized deposit network by early 2027, enabling instant and 24/7 settlement of tokenized deposits. This initiative could challenge stablecoins by offering a regulated, bank-backed digital payment method, potentially transforming how money moves in the financial system. The network will be operated by the Clearing House, a private-sector payments company owned by the consortium, and is referred to as 'the bridge' or 'the chain' by different banks.

rss · The Block · Jun 5, 02:57

**Background**: Tokenized deposits are traditional bank deposits represented as digital tokens on a blockchain, carrying the same credit risk and regulatory treatment as conventional deposits. Unlike stablecoins, which are often unregulated and backed by reserves, tokenized deposits keep funds within the banking system. This network aims to provide instant settlement, reducing reliance on slower traditional clearing systems.

<details><summary>References</summary>
<ul>
<li><a href="https://www.pymnts.com/blockchain/2026/big-banks-launch-tokenized-deposit-network-to-fight-off-stablecoin-threat/">Big Banks Launch Tokenized Deposit Network to Fight Off Stablecoin Threat | PYMNTS.com</a></li>
<li><a href="https://www.coingabbar.com/en/crypto-currency-news/us-banks-tokenized-deposit-network-jpmorgan-citi-stablecoin">US Banks Launch Tokenized Deposit Network to Challenge Stablecoins</a></li>
<li><a href="https://www.theblock.co/post/403701/jpmorgan-citi-major-banks-tokenized-deposit-network">JPMorgan, Citi-backed consortium plans to launch tokenized deposit network in early 2027: WSJ | The Block</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenization`, `#banking`, `#settlement`

---