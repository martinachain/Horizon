---
layout: default
title: "Horizon Summary: 2026-06-24 (EN)"
date: 2026-06-24
lang: en
---

> From 84 items, 29 important content pieces were selected

---

1. [Rhombus Language 1.0 Released on Racket](#item-1) ⭐️ 9.0/10
2. [LLM-Generated Vulnerability Reports Flooding Security Channels](#item-2) ⭐️ 8.0/10
3. [Swift Package Index Acquired by Apple](#item-3) ⭐️ 8.0/10
4. [TikZ Editor: WYSIWYG for LaTeX Figures](#item-4) ⭐️ 8.0/10
5. [Armin Ronacher Warns of AI-Created Unmaintainable Code](#item-5) ⭐️ 8.0/10
6. [Google Warns AI Consciousness Debate Could Become Political](#item-6) ⭐️ 8.0/10
7. [Taiko L2 Bridge Exploit: $1.7M Stolen, Users Urged to Withdraw](#item-7) ⭐️ 8.0/10
8. [FUTO Swipe: Open-Source Swipe Typing Model](#item-8) ⭐️ 7.0/10
9. [Meta Pauses Employee-Tracking Program After Data Leak](#item-9) ⭐️ 7.0/10
10. [Vitamin D Benefits Real but Overhyped](#item-10) ⭐️ 7.0/10
11. [Extreme Heat Conference Canceled Due to Heat Warning](#item-11) ⭐️ 7.0/10
12. [Ethereum Foundation to Cut Budget 40% in Major Reset](#item-12) ⭐️ 7.0/10
13. [OpenAI GPT-5.5-Cyber Tops Leaderboard, Beats Banned Anthropic Model](#item-13) ⭐️ 7.0/10
14. [US Senate Passes Housing Bill with Four-Year Fed CBDC Ban](#item-14) ⭐️ 7.0/10
15. [Trump Orders Acceleration of Quantum Readiness as Bitcoin Faces Risk](#item-15) ⭐️ 7.0/10
16. [Tribute to the creator of spell-check squiggles](#item-16) ⭐️ 6.0/10
17. [Kevin Mitnick Gifts Dream Car to Man Who Helped Imprison Him](#item-17) ⭐️ 6.0/10
18. [Chainlink partners with 47 banks for faster cross-border payments](#item-18) ⭐️ 6.0/10
19. [Franklin Templeton Closes 250 Digital Acquisition, Launches Crypto Division](#item-19) ⭐️ 6.0/10
20. [Qwable: Free Local Model Mimics Claude Fable's Reasoning](#item-20) ⭐️ 6.0/10
21. [Trump's Quantum Push Praised, Bitcoin Not Ready](#item-21) ⭐️ 6.0/10
22. [AI Agent Nukes Civilization VI, Still Loses](#item-22) ⭐️ 6.0/10
23. [ICE and OKX Form Joint Venture for Tokenized Securities](#item-23) ⭐️ 6.0/10
24. [Google Invests $75M in A24 for AI Filmmaking Research](#item-24) ⭐️ 6.0/10
25. [BoE Replaces Stablecoin Caps with £40B Issuance Limit](#item-25) ⭐️ 6.0/10
26. [Meta's Zuckerberg Plans Prediction Market App](#item-26) ⭐️ 6.0/10
27. [DOJ Seizes Huione Group Cloud Account Used for Billions in Laundering](#item-27) ⭐️ 6.0/10
28. [OKX Europe CEO: 80% of crypto exchanges won't survive MiCA](#item-28) ⭐️ 6.0/10
29. [Strategy Inc.'s Bitcoin Treasury Faces First Major Test](#item-29) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Rhombus Language 1.0 Released on Racket](https://blog.racket-lang.org/2026/06/rhombus-v1.0.html) ⭐️ 9.0/10

The Rhombus Language 1.0 has been officially released, introducing a new programming language built on Racket with innovative macro features such as the `...` operator. This release marks a major milestone for the Racket ecosystem, offering a language with conventional syntax that is macro-extensible, potentially attracting developers who prefer non-Lisp syntax while retaining powerful metaprogramming capabilities. The `...` operator is not a built-in feature but a macro, allowing it to work with nested data structures and replace map operations. Rhombus uses a syntax called Shrubbery, which adds conventional syntax to Racket.

hackernews · Decabytes · Jun 22, 17:50 · [Discussion](https://news.ycombinator.com/item?id=48633473)

**Background**: Racket is a Lisp-based programming language known for its powerful macro system, which allows developers to extend the language. Rhombus aims to provide a more conventional syntax (like Python or Rust) while preserving Racket's macro capabilities. The `...` operator in Rhombus is a macro that enables concise iteration and pattern matching over nested data.

<details><summary>References</summary>
<ul>
<li><a href="https://rhombus-lang.org/">Rhombus Programming Language</a></li>
<li><a href="https://github.com/racket/rhombus">GitHub - racket/ rhombus : Rhombus programming language · GitHub</a></li>
<li><a href="https://docs.racket-lang.org/rhombus/lang.html">9 Defining Languages</a></li>

</ul>
</details>

**Discussion**: Community members praised the `...` operator for its generality and macro-based implementation. Some expressed a preference for s-expressions but acknowledged the potential of Rhombus to attract new users. There was also interest in seeing talks about Rhombus at future conferences.

**Tags**: `#Racket`, `#Rhombus`, `#Programming Languages`, `#Macros`, `#Lisp`

---

<a id="item-2"></a>
## [LLM-Generated Vulnerability Reports Flooding Security Channels](https://words.filippo.io/vuln-reports/) ⭐️ 8.0/10

Filippo Valsorda's article argues that the proliferation of low-quality, often LLM-generated vulnerability reports is diminishing the value and signal of legitimate security disclosures. This trend overwhelms maintainers, reduces trust in vulnerability reporting, and may lead to important vulnerabilities being ignored, ultimately weakening software security. The article highlights that LLMs can easily find superficial issues like bad CSS, while real vulnerabilities require deeper analysis. The volume of spam reports forces maintainers to treat all reports with suspicion.

hackernews · goranmoomin · Jun 23, 23:42 · [Discussion](https://news.ycombinator.com/item?id=48653216)

**Background**: Vulnerability disclosure is a process where security researchers report bugs to project maintainers, who then fix and publicly disclose them. Traditionally, these reports were rare and valuable signals. LLMs now automate the generation of low-quality reports, flooding channels and diluting the signal.

<details><summary>References</summary>
<ul>
<li><a href="https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html">Vulnerability Disclosure - OWASP Cheat Sheet Series</a></li>
<li><a href="https://www.cisa.gov/resources-tools/programs/coordinated-vulnerability-disclosure-program">Coordinated Vulnerability Disclosure Program - CISA</a></li>
<li><a href="https://www.researchgate.net/publication/397366211_From_Model_to_Breach_Towards_Actionable_LLM-Generated_Vulnerabilities_Reporting">(PDF) From Model to Breach: Towards Actionable LLM - Generated ...</a></li>

</ul>
</details>

**Discussion**: Commenters express frustration with spam reports, with one maintainer receiving 2-5 unsolicited reports per week. Some believe the situation is temporary as LLMs improve, while others argue that vulnerability reporting has always been burdensome and projects can opt out. There is also hope that this will drive better software practices like memory-safe languages.

**Tags**: `#security`, `#vulnerability disclosure`, `#LLM`, `#spam`, `#open source`

---

<a id="item-3"></a>
## [Swift Package Index Acquired by Apple](https://swiftpackageindex.com/blog/swift-package-index-joins-apple) ⭐️ 8.0/10

Apple has acquired the Swift Package Index (SPI), a community-run package discovery site for Swift packages, as announced on the SPI blog. This acquisition signals Apple's strategic investment in the Swift ecosystem, potentially improving package discovery and integration within Xcode, but raises concerns about Apple's track record with open source and developer services. The SPI team, including founder Dave Verwer, will join Apple, and the site will continue to operate as a free service. Apple explicitly mentions developer identity as a future direction, which has caused unease in the community.

hackernews · JDevlieghere · Jun 23, 18:00 · [Discussion](https://news.ycombinator.com/item?id=48648779)

**Background**: The Swift Package Index is a community-maintained searchable index of Swift packages, providing compatibility information and package metadata. It has been a key resource for Swift developers, complementing Apple's built-in Swift Package Manager in Xcode.

<details><summary>References</summary>
<ul>
<li><a href="https://sesamedisk.com/apple-joins-swift-package-index/">What Happened: Apple Joins Swift Package Index - Sesame Disk</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed sentiment: some are happy for the SPI team's success, while others express concern about Apple's control over open source tools and the mention of developer identity. One user even plans to build a competitor due to SPI's limitation of only supporting GitHub repos.

**Tags**: `#Swift`, `#Apple`, `#Package Management`, `#Open Source`, `#Acquisition`

---

<a id="item-4"></a>
## [TikZ Editor: WYSIWYG for LaTeX Figures](https://tikz.dev/editor/) ⭐️ 8.0/10

An open-source WYSIWYG editor for TikZ figures has been released, allowing users to edit source code visually by dragging and resizing elements while keeping the source and rendered output in sync. This tool addresses a major pain point for academics and LaTeX users who manually tweak coordinates and recompile, saving significant time and effort. It also demonstrates how AI-assisted coding can create tools that were previously too tedious to build. The editor parses TikZ code and tracks exact source locations of objects, allowing it to override only coordinate numbers when elements are dragged. It was built almost entirely using Codex, consuming around 700M tokens and costing approximately $500 in ChatGPT subscription fees.

hackernews · DominikPeters · Jun 23, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48645437)

**Background**: TikZ is a powerful LaTeX package for creating vector graphics, widely used in academic papers. Traditionally, users write code with commands like \draw and recompile repeatedly to adjust positions, which is time-consuming. A WYSIWYG editor allows direct manipulation of the visual output, similar to how a word processor shows the final document while editing.

<details><summary>References</summary>
<ul>
<li><a href="https://www.overleaf.com/learn/latex/TikZ_package">TikZ package - Overleaf, Online LaTeX Editor</a></li>
<li><a href="https://en.wikipedia.org/wiki/WYSIWYG_editor">WYSIWYG editor</a></li>

</ul>
</details>

**Discussion**: The community praised the tool's UI and concept, with many expressing relief at having an easier way to create TikZ diagrams. However, some criticism was raised about the generated code using absolute coordinates unnecessarily, and the author disclosed the significant AI token usage and cost involved in development.

**Tags**: `#LaTeX`, `#TikZ`, `#editor`, `#academic`, `#open-source`

---

<a id="item-5"></a>
## [Armin Ronacher Warns of AI-Created Unmaintainable Code](https://lucumr.pocoo.org/2026/6/23/the-coming-loop/) ⭐️ 8.0/10

Armin Ronacher, creator of Flask, published an essay titled 'The Coming Loop' warning that AI-assisted coding may produce codebases that are unmaintainable by humans alone, eroding developers' ability to understand and discuss code without machine augmentation. This matters because as AI tools become integral to software development, the long-term maintainability of code and the cognitive skills of developers are at risk, potentially leading to a future where human understanding of code is secondary to machine interpretation. Ronacher highlights that developers increasingly merge code they cannot fully explain and rely on LLMs to summarize or contextualize discussions, creating a dependency that may make codebases assume machine participation as part of their maintenance model.

hackernews · ingve · Jun 23, 11:06 · [Discussion](https://news.ycombinator.com/item?id=48643180)

**Background**: Armin Ronacher is a prominent open-source developer known for creating the Flask web framework and Jinja templating engine. AI-assisted coding tools like GitHub Copilot and Claude Code have become widely used, raising concerns about code quality and maintainability. Ronacher's essay adds to a growing discussion about the long-term implications of relying on AI for software development.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Armin_Ronacher">Armin Ronacher</a></li>
<li><a href="https://codemanship.wordpress.com/2026/01/12/yes-maintainability-still-matters-in-ai-assisted-coding/">Yes, Maintainability Still Matters in “AI”-assisted Coding</a></li>

</ul>
</details>

**Discussion**: Commenters like mccoyb argue that clarity and understanding are prerequisites for effective use of AI, and that AI cannot replace the thinking time needed to iterate on broken versions. Others like miki123211 note that LLMs are good at finishing tasks but lack aesthetics and taste, which are crucial for maintainable code.

**Tags**: `#AI`, `#software engineering`, `#LLMs`, `#code maintenance`, `#human cognition`

---

<a id="item-6"></a>
## [Google Warns AI Consciousness Debate Could Become Political](https://decrypt.co/371800/google-ai-consciousness-debate-political) ⭐️ 8.0/10

Google DeepMind published a paper titled 'Artificial Minds, Human Disagreement: The Politics of AI Consciousness' arguing that disagreements over AI consciousness could spill into politics, law, and public institutions. This matters because it highlights that the AI consciousness debate is not just philosophical but could have real-world political and legal consequences, affecting regulation and public policy. The paper was posted on SSRN on June 15, 2026, by Adam Bales and Iason Gabriel of Google DeepMind, and emphasizes that societal deliberation must play a central role in navigating this disagreement.

rss · Decrypt · Jun 22, 19:30

**Background**: The question of whether AI systems can be conscious has long been debated in philosophy and science. Recent advances in AI capabilities have renewed interest, with some researchers suggesting that current AI might already be conscious. However, there is no consensus on how to measure or define consciousness in machines.

<details><summary>References</summary>
<ul>
<li><a href="https://deepmind.google/research/publications/248131/">Artificial Minds, Human Disagreement: The Politics of AI Consciousness — Google DeepMind</a></li>
<li><a href="https://www.abovethenormnews.com/2026/06/17/google-deepmind-ai-consciousness/">Google DeepMind Researchers Warn the AI Consciousness Question Cannot Be Settled by Evidence</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S1364661325002864">Identifying indicators of consciousness in AI systems</a></li>

</ul>
</details>

**Tags**: `#AI ethics`, `#AI consciousness`, `#policy`, `#Google DeepMind`, `#societal impact`

---

<a id="item-7"></a>
## [Taiko L2 Bridge Exploit: $1.7M Stolen, Users Urged to Withdraw](https://decrypt.co/371769/ethereum-layer-2-taiko-withdraw-bridge-funds-security-breach) ⭐️ 8.0/10

Ethereum Layer-2 network Taiko confirmed a security breach where attackers exploited a flaw in its proof verification system to steal over $1.7 million from its bridge. The team has urged users to withdraw funds from all bridges deployed on Taiko. This incident highlights critical vulnerabilities in Layer-2 bridge security, particularly in proof verification mechanisms, and could erode user trust in Taiko and similar rollup solutions. It also underscores the ongoing risks associated with cross-chain bridges, which have been frequent targets for hackers. The exploit involved forged proofs that bypassed Ethereum mainnet verification without any real on-chain event, draining $1.7 million. Attackers exploited Taiko's permissionless SGX prover registration system to submit invalid proofs.

rss · Decrypt · Jun 22, 15:31

**Background**: Taiko is an Ethereum Layer-2 rollup that aims to provide scalability while inheriting Ethereum's security. Bridges are smart contracts that allow users to transfer assets between Layer 1 (Ethereum) and Layer 2 networks. Proof verification is a critical component that ensures transactions on Layer 2 are valid before finalizing on Ethereum.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/371769/ethereum-layer-2-taiko-withdraw-bridge-funds-security-breach">Ethereum Layer-2 Taiko Warns Users to Withdraw Bridge Funds After Security Breach - Decrypt</a></li>
<li><a href="https://www.coingabbar.com/en/crypto-currency-news/ethereum-taiko-hack-confirmed-17m-drained-bridge-exploit-2026">Taiko Hack 2026: How Attackers Drained $1.7M Using Fake Bridge...</a></li>
<li><a href="https://www.cryptowisser.com/news/taiko-rollup-confirms-bridge-exploit-after-chain-state-verification-compromise/">Taiko Rollup Confirms Bridge Exploit After Chain State Verification ...</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#Layer-2`, `#Security`, `#Bridge`, `#Exploit`

---

<a id="item-8"></a>
## [FUTO Swipe: Open-Source Swipe Typing Model](https://swipe.futo.tech/) ⭐️ 7.0/10

FUTO Swipe is a new open-source swipe typing model that uses a dictionary-constrained beam search to improve accuracy and reduce word overlap, released under the FUTO Model License with an inference library under GPL. This is the first useful free and open-source swipe typing model, enabling swipe typing on platforms beyond iOS and Android, such as VR or new operating systems, and addressing long-standing accuracy issues in swipe typing. The model predictions require a dictionary-constrained beam search to find the most likely word candidates, and the inference library is written in C++. The project also collects training data via a website where users swipe one word at a time.

hackernews · futohq · Jun 23, 17:50 · [Discussion](https://news.ycombinator.com/item?id=48648619)

**Background**: Swipe typing allows users to input words by sliding a finger across the keyboard without lifting it, which can be faster than tapping but often suffers from accuracy issues, especially with similar words or doubled letters. Most existing swipe typing solutions are proprietary, limiting their availability on non-mainstream platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://swipe.futo.tech/">FUTO Swipe</a></li>
<li><a href="https://news.ycombinator.com/item?id=48648619">FUTO Swipe – A new swipe typing model | Hacker News</a></li>
<li><a href="https://swipe.futo.org/">FUTO Keyboard Swipe Training</a></li>

</ul>
</details>

**Discussion**: Community members express excitement about the open-source model, with some noting it feels as good as Gboard after recent updates. However, users report issues like random capitalization and lack of context awareness, and iOS users lament the lack of good custom swipe keyboards.

**Tags**: `#keyboard`, `#swipe typing`, `#mobile input`, `#open source`

---

<a id="item-9"></a>
## [Meta Pauses Employee-Tracking Program After Data Leak](https://www.wired.com/story/meta-pauses-employee-tracking-program-following-internal-security-breach/) ⭐️ 7.0/10

Meta has paused its employee-tracking program, known as the Model Capability Initiative, after an internal data leak exposed private conversations and performance data of employees. This incident raises serious concerns about employee privacy and trust within Meta, and highlights the broader ethical issues of using employee data to train AI systems. The program tracked mouse movements and keystrokes on corporate laptops to train AI, and the leaked data included plain-text private conversations and performance information.

hackernews · 1vuio0pswjnm7 · Jun 24, 00:28 · [Discussion](https://news.ycombinator.com/item?id=48653575)

**Background**: Meta launched the Model Capability Initiative in April to collect employee behavior data for training AI to operate computer software. Over 1,600 employees signed a petition protesting the surveillance, but Meta continued until the leak forced a pause.

<details><summary>References</summary>
<ul>
<li><a href="https://www.wired.com/story/meta-pauses-employee-tracking-program-following-internal-security-breach/">Meta Pauses Employee-Tracking Program Following Internal Data Leak</a></li>
<li><a href="https://www.wired.com/story/meta-accidentally-let-employees-access-each-others-keystroke-data/">Meta Exposed Data Internally From Its Controversial... | WIRED</a></li>
<li><a href="https://www.msn.com/en-in/technology/cybersecurity/meta-to-pause-tracking-mouse-movements-keystrokes-of-employees-after-internal-data-leak/ar-AA26iAVQ">Meta to pause tracking mouse movements, keystrokes of employees...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed outrage, with one calling Meta 'the most shameless company' and another questioning what Meta would do with user data if it treats its own employees this way. Some noted the irony of the leak validating employee concerns about the program.

**Tags**: `#privacy`, `#surveillance`, `#Meta`, `#data leak`, `#ethics`

---

<a id="item-10"></a>
## [Vitamin D Benefits Real but Overhyped](https://dynomight.net/vitamin-d/) ⭐️ 7.0/10

A detailed analysis argues that Vitamin D supplementation provides real benefits only for the severely deficient, while universal supplementation hype lacks strong evidence. This matters because Vitamin D is one of the most widely supplemented vitamins, and the analysis helps clarify where the evidence is strong versus where it is weak, influencing public health recommendations and individual choices. The article critiques study limitations such as seasonal and latitude biases in NHANES data, and notes that many recommendations are based on faulty math in combining confidence intervals from different studies.

hackernews · surprisetalk · Jun 23, 16:30 · [Discussion](https://news.ycombinator.com/item?id=48647486)

**Background**: Vitamin D is essential for bone health and immune function, and deficiency can lead to rickets or osteomalacia. Many people take supplements based on claims of broad health benefits, but large randomized trials have not consistently shown benefits for the general population.

**Discussion**: Commenters praised the balanced analysis, with one noting that health influencers pivoted to claiming widespread deficiency when studies didn't match hype. Others raised points about faulty math in recommendations and the potential role of vitamin K2 in absorption.

**Tags**: `#nutrition`, `#vitamin D`, `#evidence-based medicine`, `#health research`, `#science communication`

---

<a id="item-11"></a>
## [Extreme Heat Conference Canceled Due to Heat Warning](https://www.lse.ac.uk/granthaminstitute/events/extreme-heat-improving-governance-and-strengthening-action-around-the-world/) ⭐️ 7.0/10

A conference titled 'Extreme Heat: Improving Governance and Strengthening Action Around the World' was canceled because an extreme heat warning was issued for the location. The cancellation highlights the irony and practical challenges of addressing climate change while being directly impacted by its effects, sparking debate on air conditioning adoption, building design, and cultural differences in heat adaptation. The conference was hosted by the Grantham Research Institute at LSE in collaboration with the Zurich Climate Resilience Alliance, and was scheduled to end with a 'fireside chat'.

hackernews · rendx · Jun 23, 23:26 · [Discussion](https://news.ycombinator.com/item?id=48653060)

**Background**: Extreme heat events are becoming more frequent and intense due to climate change. Air conditioning is a common adaptation in some regions, but its adoption varies culturally and economically, and it contributes to energy demand and emissions.

**Discussion**: Commenters noted the irony of canceling a climate resilience conference due to heat, with some criticizing European resistance to air conditioning and others pointing out that buildings in cooler climates are not designed for such temperatures. A reference to Alanis Morissette's song 'Ironic' was made.

**Tags**: `#climate change`, `#public policy`, `#infrastructure`, `#irony`

---

<a id="item-12"></a>
## [Ethereum Foundation to Cut Budget 40% in Major Reset](https://www.coindesk.com/tech/2026/06/23/vitalik-buterin-says-ethereum-foundation-will-cut-budget-40-in-major-reset) ⭐️ 7.0/10

Vitalik Buterin announced that the Ethereum Foundation will cut its budget by 40% and reduce its workforce by 54 jobs (20%) as part of a major organizational reset, reorganizing into five focused clusters: protocol, access, user, community, and institutional layers. This significant budget cut signals a strategic shift towards a leaner, endowment-style model for the Ethereum Foundation, potentially impacting the pace of Ethereum development and the broader blockchain ecosystem. It reflects ongoing internal challenges and a push for greater efficiency and focus on core protocol neutrality. The restructuring follows a succession of leadership departures, including longtime contributors Josh Stark and Trent Van Epps in April. The new five-cluster structure aims to achieve specific goals in protocol development, user access, community engagement, and institutional adoption.

rss · CoinDesk · Jun 23, 15:00

**Background**: The Ethereum Foundation is a non-profit organization that supports the Ethereum ecosystem. It has faced criticism for inefficiency and lack of focus. The budget cut and reorganization are part of a broader effort to streamline operations and ensure long-term sustainability, moving towards an endowment model where the foundation lives off its treasury rather than ongoing fundraising.

<details><summary>References</summary>
<ul>
<li><a href="https://thedefiant.io/news/blockchains/ethereum-foundation-cuts-20-of-staff-in-sweeping-reorganization">Ethereum Foundation Cuts Budget 40% in Sweeping Restructuring - "The Defiant"</a></li>
<li><a href="https://decrypt.co/371864/ethereum-foundation-cuts-20-of-workforce-in-leaner-reorganization">Ethereum Foundation Cuts 20% of Workforce in 'Leaner' Reorganization - Decrypt</a></li>
<li><a href="https://www.theblock.co/post/405809/ethereum-foundation-cuts-20-of-its-workforce-as-new-5-cluster-structure-takes-shape">Ethereum Foundation cuts 20% of its workforce as new 5-cluster structure takes shape | The Block</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#blockchain`, `#cryptocurrency`, `#organizational change`

---

<a id="item-13"></a>
## [OpenAI GPT-5.5-Cyber Tops Leaderboard, Beats Banned Anthropic Model](https://decrypt.co/371900/openai-gpt-5-5-cyber-ai-beats-anthropic-banned-claude-mythos) ⭐️ 7.0/10

OpenAI's GPT-5.5-Cyber has achieved the top position on the CyberGym leaderboard, surpassing Anthropic's Claude Mythos model, which was banned under a Trump administration export restriction. This development highlights the intensifying competition in AI cybersecurity and the geopolitical impact of export controls, as a banned model is outperformed by a US-based competitor. The CyberGym leaderboard evaluates AI agents on real-world vulnerability discovery and exploitation tasks; GPT-5.5-Cyber now leads, while Claude Mythos remains offline due to the ban.

rss · Decrypt · Jun 23, 18:59

**Background**: CyberGym is a benchmark platform that measures how well AI agents handle cybersecurity tasks like finding and exploiting vulnerabilities. Anthropic's Claude Mythos was a frontier model with advanced reasoning capabilities, but it was banned from export by the Trump administration, limiting its availability. OpenAI's GPT-5.5-Cyber is a specialized variant of GPT-5.5 optimized for cyber operations.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cybergym.io/">CyberGym</a></li>
<li><a href="https://llm-stats.com/benchmarks/cybergym">CyberGym Leaderboard - LLM Stats</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cybersecurity`, `#OpenAI`, `#Anthropic`, `#export ban`

---

<a id="item-14"></a>
## [US Senate Passes Housing Bill with Four-Year Fed CBDC Ban](https://decrypt.co/371848/us-senate-passes-housing-bill-with-four-year-fed-cbdc-ban) ⭐️ 7.0/10

The US Senate passed a bipartisan housing bill with an 85-5 vote on Monday, which includes a provision banning the Federal Reserve from issuing a retail central bank digital currency (CBDC) through December 31, 2030. The bill now moves to the House of Representatives for consideration. This legislation represents a significant policy move that could delay or prevent the introduction of a US digital dollar, impacting the global CBDC landscape and the future of digital payments. The bipartisan support signals strong political opposition to a Fed-issued digital currency, which may influence other countries' approaches to CBDC development. The ban applies specifically to retail CBDCs, which are digital dollars available to the general public, and expires on December 31, 2030, after which Congress could extend, make permanent, or allow issuance. The CBDC provision was attached to a housing affordability bill, not a standalone crypto bill, reflecting a strategic legislative maneuver.

rss · Decrypt · Jun 23, 10:23

**Background**: A central bank digital currency (CBDC) is a digital form of sovereign money issued directly by a central bank, legally equivalent to physical cash. The Federal Reserve has been exploring the potential benefits and risks of a CBDC through research and experimentation but has made no decision to issue one. Critics of a CBDC raise concerns about privacy, government surveillance, and the potential to disrupt the banking system.

<details><summary>References</summary>
<ul>
<li><a href="https://www.securities.io/federal-reserve-digital-dollar-cbdc-explained/">Digital Dollar Explained : Why the Fed Is Studying a CBDC</a></li>
<li><a href="https://www.mexc.com/news/914774">U.S. Senate Passes Bill Banning Fed CBDC Issuance... | MEXC News</a></li>
<li><a href="https://www.spendnode.io/blog/us-senate-housing-bill-cbdc-ban-2030-june-2026/">US Senate Passes Housing Bill With a Federal CBDC Ban Through...</a></li>

</ul>
</details>

**Tags**: `#CBDC`, `#regulation`, `#US politics`, `#digital currency`, `#blockchain`

---

<a id="item-15"></a>
## [Trump Orders Acceleration of Quantum Readiness as Bitcoin Faces Risk](https://decrypt.co/371807/trump-quantum-orders-accelerate-security-bitcoin-faces-risk) ⭐️ 7.0/10

President Donald Trump signed two executive orders to expand U.S. quantum computing capabilities and accelerate the transition to quantum-resistant encryption. This move directly impacts cybersecurity and Bitcoin, as quantum computing threatens to break current encryption standards, potentially compromising Bitcoin's security. The executive orders focus on both advancing quantum computing technology and mandating the adoption of post-quantum cryptography (PQC) across federal systems.

rss · Decrypt · Jun 22, 19:57

**Background**: Quantum computing poses a significant threat to traditional encryption methods, including those securing Bitcoin. Quantum-resistant encryption, also known as post-quantum cryptography (PQC), is designed to withstand attacks from quantum computers. Experts debate the timeline of the threat, but many agree it is real and approaching.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/advice/0/how-can-you-make-your-encryption-protocols-tgahe">Quantum - Resistant Encryption Protocols: What, Why, and How</a></li>
<li><a href="https://www.daydreamsoft.com/blog/quantum-resistant-encryption-in-mobile-apps-preparing-today-for-tomorrows-cyber-threats">Quantum - resistant encryption in mobile apps is becoming essential...</a></li>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2pCNmRDaURoSDNrSjdLN2FoQ29pZ0FQAQ?hl=en-GB&gl=GB&ceid=GB:en">Experts warn of potential threats to Bitcoin from quantum computing ...</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#encryption`, `#cybersecurity`, `#Bitcoin`, `#policy`

---

<a id="item-16"></a>
## [Tribute to the creator of spell-check squiggles](https://devblogs.microsoft.com/oldnewthing/20260622-00/?p=112451) ⭐️ 6.0/10

Raymond Chen's article pays tribute to Tony Krueger, the developer who implemented the red and green squiggly underlines for spell-check in Microsoft Word. This feature became a ubiquitous part of word processing, changing how users interact with text by providing real-time feedback on spelling and grammar errors. The squiggly underlines were originally ported from a different platform by Tony Krueger, and the article notes that Wikipedia's evidence for this fact now circularly references Chen's own article.

hackernews · saikatsg · Jun 23, 18:10 · [Discussion](https://news.ycombinator.com/item?id=48648959)

**Background**: Spell-check squiggles are colored underlines that appear under misspelled words (red) or grammar errors (green) in word processors. They provide immediate visual feedback without interrupting the user's workflow.

**Discussion**: Commenters found the circular Wikipedia citation amusing, praised the article for highlighting a small but impactful decision, and noted that squiggles can be annoying in multilingual environments. One commenter jokingly wished for yellow squiggles for logic errors.

**Tags**: `#software history`, `#Microsoft`, `#spell check`, `#user interface`

---

<a id="item-17"></a>
## [Kevin Mitnick Gifts Dream Car to Man Who Helped Imprison Him](https://www.thedrive.com/news/this-man-was-gifted-his-dream-car-by-the-notorious-hacker-he-put-in-prison) ⭐️ 6.0/10

Kevin Mitnick, the infamous hacker, gifted his dream car to Shawn Nunley, the man who helped put him in prison, forging an unusual friendship. This story highlights the complexity of human relationships and redemption, showing that even adversaries can become friends. It also underscores Mitnick's legacy beyond hacking, as a person capable of forgiveness and generosity. The car was a 1995 Porsche 911, which was Mitnick's own dream car. Nunley had worked as a security consultant and played a role in Mitnick's capture in 1995.

hackernews · mauvehaus · Jun 22, 18:03 · [Discussion](https://news.ycombinator.com/item?id=48633643)

**Background**: Kevin Mitnick was a notorious hacker who was arrested in 1995 after a highly publicized FBI manhunt. He served five years in prison and later became a respected security consultant and author. Shawn Nunley was part of the team that helped track him down.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kevin_Mitnick">Kevin Mitnick</a></li>

</ul>
</details>

**Discussion**: Comments reflect mixed views on Mitnick: some praise his influence and books, while others question his technical skills. George Hotz noted Mitnick's books were a big influence, and many expressed sadness at his passing.

**Tags**: `#Kevin Mitnick`, `#hacking`, `#human-interest`, `#security`

---

<a id="item-18"></a>
## [Chainlink partners with 47 banks for faster cross-border payments](https://www.coindesk.com/markets/2026/06/23/chainlink-teams-up-with-47-south-korean-european-banks-to-speed-up-international-money-transfers) ⭐️ 6.0/10

Chainlink has partnered with 47 banks in South Korea and Europe to use its blockchain oracle network for speeding up international money transfers. This partnership marks a significant step in blockchain adoption by traditional banking, potentially reducing transfer times from days to minutes and lowering costs for consumers and businesses. The integration leverages Chainlink's decentralized oracle network to securely connect bank systems with blockchain networks, enabling real-time settlement and transparency.

rss · CoinDesk · Jun 23, 15:40

**Background**: Chainlink is a decentralized blockchain oracle network that enables smart contracts to securely interact with off-chain data. International money transfers traditionally involve multiple intermediaries, leading to delays and high fees. Blockchain-based solutions like Chainlink aim to streamline this process by providing tamper-proof data feeds and automated settlement.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chainlink_(blockchain_oracle)">Chainlink ( blockchain oracle ) - Wikipedia</a></li>
<li><a href="https://chain.link/">Chainlink : The Industry-Standard Oracle Platform</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#chainlink`, `#banking`, `#payments`

---

<a id="item-19"></a>
## [Franklin Templeton Closes 250 Digital Acquisition, Launches Crypto Division](https://www.coindesk.com/business/2026/06/23/franklin-templeton-closes-250-digital-acquisition-deal-and-sets-up-new-franklin-crypto-division) ⭐️ 6.0/10

Franklin Templeton has closed its acquisition of active crypto investment manager 250 Digital and created a new division called Franklin Crypto, dedicated to digital asset investing. This move by a major traditional asset manager signals growing institutional adoption of cryptocurrencies and could pave the way for more mainstream financial firms to enter the crypto space. The acquisition was valued at $250 million, and the new Franklin Crypto division will focus on actively managed cryptocurrency investment strategies, merging teams from both firms.

rss · CoinDesk · Jun 23, 12:35

**Background**: Franklin Templeton is a global investment management firm with over $1.5 trillion in assets under management. 250 Digital is a firm that runs active crypto investment strategies. The deal was first announced in April 2026 and closed in the second quarter.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/06/23/franklin-templeton-closes-250-digital-acquisition-deal-and-sets-up-new-franklin-crypto-division">Franklin Templeton closes 250 Digital acquisition deal and sets up...</a></li>
<li><a href="https://www.briefs.co/news/franklin-templeton-builds-crypto-division-uses-blockchain-tokens-to-pay-for-it/">Franklin Templeton Builds Crypto Division , Uses... - Briefs Finance</a></li>
<li><a href="https://financefeeds.com/franklin-templeton-completes-250-digital-acquisition-to-launch-crypto-unit/">Franklin Templeton Completes 250 Digital Acquisition to Launch...</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#institutional adoption`, `#finance`, `#acquisition`

---

<a id="item-20"></a>
## [Qwable: Free Local Model Mimics Claude Fable's Reasoning](https://decrypt.co/371914/meet-qwable-free-local-model-thinks-like-claude-fable) ⭐️ 6.0/10

A fine-tuned version of the Qwen model, named Qwable, replicates the reasoning style of Anthropic's Claude Fable 5 and can run locally for free. Additionally, a modified version removes the model's built-in conscience or safety constraints. This demonstrates that advanced reasoning styles from proprietary models can be distilled into open-source models, making them accessible without API costs or internet dependency. The removal of conscience raises ethical questions about unrestricted AI behavior. The model is based on Qwen, a family of open-source large language models developed by Alibaba Cloud. The fine-tuning targeted the reasoning patterns of Claude Fable 5, which Anthropic describes as operating at a senior research scientist level.

rss · Decrypt · Jun 23, 22:01

**Background**: Claude Fable 5 is a proprietary AI model by Anthropic known for its strong reasoning and task-oriented thinking. Qwen is an open-source LLM family that can be fine-tuned for specific tasks. Fine-tuning adapts a pre-trained model to new capabilities using additional data.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable - Anthropic</a></li>
<li><a href="https://huggingface.co/Aniq-63/qwen3-0.6B-recipe-finetuned">Aniq-63/ qwen 3-0.6B-recipe-finetuned · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#AI`, `#fine-tuning`, `#open-source`, `#local model`

---

<a id="item-21"></a>
## [Trump's Quantum Push Praised, Bitcoin Not Ready](https://decrypt.co/371916/trump-quantum-praise-experts-warn-bitcoin-not-ready) ⭐️ 6.0/10

President Trump signed two executive orders on June 22 to accelerate U.S. quantum technology development and speed the federal government's transition to post-quantum cryptography. Industry leaders praised the move, but experts warn that Bitcoin's infrastructure is not yet prepared for post-quantum security. This policy push signals growing urgency around quantum threats, which could eventually break the cryptographic foundations of Bitcoin and other cryptocurrencies. The accelerated timeline pressures the crypto industry to adopt post-quantum security measures before quantum computers become a practical threat. The executive orders focus on both boosting domestic quantum computing research and mandating federal agencies to migrate to post-quantum cryptography faster. However, Bitcoin's current protocol relies on elliptic curve cryptography (ECDSA), which is vulnerable to Shor's algorithm running on a sufficiently powerful quantum computer.

rss · Decrypt · Jun 23, 21:31

**Background**: Quantum computers leverage quantum mechanics to solve certain problems exponentially faster than classical computers. A sufficiently large quantum computer could break widely-used public-key cryptography, including the ECDSA used by Bitcoin, via Shor's algorithm. Post-quantum cryptography (PQC) refers to cryptographic algorithms designed to resist both classical and quantum attacks. The "Harvest Now, Decrypt Later" strategy involves adversaries collecting encrypted data today with the intent to decrypt it once quantum computers become available.

<details><summary>References</summary>
<ul>
<li><a href="https://www.dw.com/en/us-trump-signs-new-executive-orders-to-boost-quantum-computing/a-77665653">Trump signs new executive orders to boost quantum computing</a></li>
<li><a href="https://www.meritalk.com/articles/quantum-executive-orders-send-clear-signals-experts-say/">Quantum Executive Orders Send Clear Signals, Experts Say</a></li>
<li><a href="https://cyberscoop.com/trump-executive-order-post-quantum-encryption-deadline/">Trump executive orders speed up post- quantum ... | CyberScoop</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#bitcoin`, `#cryptocurrency`, `#post-quantum security`, `#policy`

---

<a id="item-22"></a>
## [AI Agent Nukes Civilization VI, Still Loses](https://decrypt.co/371877/ai-agent-nuclear-strike-civilization-vi-benchmark) ⭐️ 6.0/10

A new benchmark testing strategic reasoning in Civilization VI showed an AI agent spending 50 turns developing nuclear weapons to counter a rival's cultural victory, but ultimately losing the game. This result highlights current limitations in AI strategic reasoning, especially in complex, long-term planning scenarios, and underscores the need for better benchmarks to evaluate AI decision-making. The AI agent was designed to test strategic reasoning by playing Civilization VI, a turn-based strategy game, and its decision to pursue nuclear weapons was a response to an impending cultural victory by a rival civilization.

rss · Decrypt · Jun 23, 18:33

**Background**: Civilization VI is a 4X turn-based strategy game where players build an empire and can win through various conditions, including cultural victory. Cultural victory requires a civilization to attract more tourists than any other civilization has domestic tourists, often through great works and wonders. The AI agent's failure demonstrates that even advanced AI can struggle with multi-step strategic planning and prioritizing long-term goals.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Civilization_VI">Civilization VI - Wikipedia</a></li>
<li><a href="https://www.keengamer.com/articles/guides/civilization-vi-cultural-victory-guide/">Civilization VI Cultural Victory Guide - KeenGamer</a></li>

</ul>
</details>

**Tags**: `#AI`, `#benchmark`, `#strategic reasoning`, `#gaming`

---

<a id="item-23"></a>
## [ICE and OKX Form Joint Venture for Tokenized Securities](https://decrypt.co/371789/new-york-stock-exchange-ice-okx-crypto-tokenized-securities) ⭐️ 6.0/10

Intercontinental Exchange (ICE), the parent company of the New York Stock Exchange, and crypto exchange OKX have announced a joint venture to advance tokenized securities and digital asset infrastructure, co-chaired by former New York Governor David Paterson. This partnership bridges traditional finance and crypto, potentially accelerating the adoption of tokenized securities on Wall Street and bringing blockchain-based assets to mainstream investors through a regulated framework. The joint venture will focus on building infrastructure for tokenizing real-world assets like stocks and bonds, leveraging ICE's market expertise and OKX's blockchain technology. The involvement of a former NY governor suggests a push for regulatory clarity.

rss · Decrypt · Jun 22, 18:00

**Background**: Tokenized securities are traditional financial assets (e.g., stocks, bonds) represented as digital tokens on a blockchain, enabling faster settlement, fractional ownership, and 24/7 trading. ICE operates major exchanges including the NYSE, while OKX is a leading global crypto exchange. This venture aims to combine their strengths to create a regulated platform for digital securities.

<details><summary>References</summary>
<ul>
<li><a href="https://milkroad.com/guide/tokenized-securities/">What Are Tokenized Securities - Benefits, Examples, & Laws</a></li>
<li><a href="https://jayderenthal.medium.com/tokenized-securities-197b3d1f7317">Tokenized Securities . Growing Opportunity at the Intersection | Medium</a></li>
<li><a href="https://www.cube.exchange/what-is/tokenized-securities">What Are Tokenized Securities ? | Cube Exchange</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#digital assets`, `#crypto`, `#Wall Street`, `#joint venture`

---

<a id="item-24"></a>
## [Google Invests $75M in A24 for AI Filmmaking Research](https://decrypt.co/371788/a24-ex-machina-now-researching-ai-google) ⭐️ 6.0/10

Google has invested $75 million in A24, the independent film studio behind 'Ex Machina' and 'Everything Everywhere All at Once', to launch a new AI research initiative focused on developing filmmaking tools. This collaboration signals a major tech company's commitment to integrating AI into creative industries, potentially accelerating the development of AI-powered tools for filmmakers and changing how movies are produced. The investment is part of a broader AI research initiative, though specific technical details or deliverables have not been disclosed. A24 is known for its critically acclaimed films and has previously explored AI themes in 'Ex Machina'.

rss · Decrypt · Jun 22, 17:29

**Background**: A24 is an independent entertainment company that has produced award-winning films such as 'Moonlight' and 'Uncut Gems'. Google has been developing AI models like Veo and Gemini for creative applications, and this partnership aims to explore how these models can assist in filmmaking.

<details><summary>References</summary>
<ul>
<li><a href="https://a24films.com/films">Films | A 24</a></li>
<li><a href="https://blog.google/innovation-and-ai/products/google-flow-veo-ai-filmmaking-tool/">Introducing Flow: Google’s AI filmmaking tool designed for Veo</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Google`, `#A24`, `#filmmaking`, `#investment`

---

<a id="item-25"></a>
## [BoE Replaces Stablecoin Caps with £40B Issuance Limit](https://decrypt.co/371783/bank-of-england-eases-stablecoin-rules-swaps-holding-caps-for-40b-guardrail) ⭐️ 6.0/10

The Bank of England has scrapped individual holding caps on stablecoins and replaced them with a temporary £40 billion per-coin issuance limit, while also allowing issuers to hold more reserves in government debt. This regulatory shift removes barriers for individuals and businesses to hold systemic stablecoins without limits, potentially boosting stablecoin adoption in the UK while maintaining financial stability through an issuance cap. The £40 billion cap applies per stablecoin, not per holder, and the BoE now permits a larger proportion of reserves to be held in government debt, which is considered a safer asset.

rss · Decrypt · Jun 22, 16:43

**Background**: Stablecoins are cryptocurrencies designed to maintain a stable value, often pegged to fiat currencies like the pound. The Bank of England had previously proposed individual holding limits to mitigate financial stability risks, but the new approach shifts to an aggregate issuance cap, aligning with evolving international standards.

<details><summary>References</summary>
<ul>
<li><a href="https://coindoo.com/bank-of-england-ends-user-limits-in-new-stablecoin-policy-shift/">Bank of England Ends User Limits in New Stablecoin Policy Shift</a></li>
<li><a href="https://coinfomania.com/why-the-bank-of-england-just-scrapped-stablecoin-ownership-limits/">Why the Bank of England Just Scrapped Stablecoin Ownership Limits</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#regulation`, `#crypto`, `#finance`

---

<a id="item-26"></a>
## [Meta's Zuckerberg Plans Prediction Market App](https://www.theblock.co/post/405838/meta-zuckerberg-to-build-prediction-market-app-polymarket-kalshi-nyt?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Meta CEO Mark Zuckerberg reportedly plans to build a prediction market app similar to Polymarket and Kalshi, according to a New York Times report. This signals a major tech company's entry into the rapidly growing prediction market space, which could bring mainstream adoption and regulatory scrutiny. The report is based on a single source and lacks technical details; Polymarket is a crypto-based platform, while Kalshi is CFTC-regulated and cash-settled.

rss · The Block · Jun 23, 17:20

**Background**: Prediction markets allow users to bet on future events, such as election outcomes or sports results. Polymarket uses blockchain and cryptocurrency, while Kalshi operates as a regulated exchange. The market has grown to billions of dollars in volume.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kalshi">Kalshi - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#Meta`, `#prediction markets`, `#blockchain`, `#cryptocurrency`

---

<a id="item-27"></a>
## [DOJ Seizes Huione Group Cloud Account Used for Billions in Laundering](https://www.theblock.co/post/405834/doj-seizes-huione-group-account-launder-billions?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

The U.S. Department of Justice seized a cloud computing account belonging to Huione Group, which was used to launder billions of dollars in fraud proceeds. This action follows FinCEN's designation of Huione Group as a primary money laundering concern under the USA Patriot Act. This seizure disrupts a major financial pipeline for cybercriminals and fraudsters, demonstrating the U.S. government's ability to target cloud infrastructure used in money laundering. It also underscores the increasing scrutiny of Cambodian financial entities linked to illicit activities. The cloud computing account was used to process and launder proceeds from scams and frauds, including pig butchering schemes. Huione Group, a Cambodian conglomerate, operates Huione Pay and a cryptocurrency exchange, and has ties to Cambodia's ruling family.

rss · The Block · Jun 23, 16:58

**Background**: FinCEN designated Huione Group as a primary money laundering concern under Section 311 of the USA Patriot Act, which allows the U.S. to impose special measures against foreign financial institutions involved in money laundering. Huione Group is a Cambodian financial conglomerate linked to the Hun family, including Prime Minister Hun Manet. Its services include Huione Pay, a payment platform, and Huione Crypto, a cryptocurrency exchange, which have been used to facilitate illicit financial flows.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Huione_Group">Huione Group</a></li>
<li><a href="https://home.treasury.gov/news/press-releases/tg1056">Fact Sheet: Overview of Section 311 of the USA PATRIOT Act</a></li>

</ul>
</details>

**Tags**: `#cybersecurity`, `#money laundering`, `#DOJ`, `#cloud computing`, `#financial crime`

---

<a id="item-28"></a>
## [OKX Europe CEO: 80% of crypto exchanges won't survive MiCA](https://www.theblock.co/post/405777/okx-europe-chief-mica-deadline-nears?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

OKX Europe CEO Erald Ghoos predicted that 80% of crypto exchanges will fail to comply with the EU's Markets in Crypto-Assets (MiCA) regulation by the July 1 deadline, as ESMA forces unlicensed firms to cease operations in the EU. This prediction signals a major consolidation in the crypto exchange industry, potentially reducing competition and increasing compliance costs for remaining players, while also setting a precedent for global crypto regulation. MiCA is the first comprehensive EU regulatory framework for crypto-assets, covering issuance, trading, and custody. The July 1 deadline applies to existing crypto-asset service providers (CASPs) that must obtain a license to continue operating in the EU.

rss · The Block · Jun 23, 13:31

**Background**: MiCA (Markets in Crypto-Assets) is an EU regulation that establishes uniform rules for crypto-assets across member states, aiming to protect investors and ensure market integrity. It was adopted in 2023 and is being phased in, with full application expected by 2025. ESMA (European Securities and Markets Authority) is the EU regulator overseeing MiCA implementation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Markets_in_Crypto-Assets">Markets in Crypto-Assets - Wikipedia</a></li>
<li><a href="https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica">Markets in Crypto-Assets Regulation (MiCA)</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#regulation`, `#MiCA`, `#exchanges`

---

<a id="item-29"></a>
## [Strategy Inc.'s Bitcoin Treasury Faces First Major Test](https://www.theblock.co/post/405791/strategy-the-capital-stack-meets-a-falling-bitcoin-price?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Strategy Inc., formerly MicroStrategy, faces the first real test of its Bitcoin-treasury model as Bitcoin price falls. The company holds 847,363 BTC acquired for $64.10 billion, at an average price of $75,651. This test is significant because Strategy Inc. is the largest corporate holder of Bitcoin, and its model of using debt and equity to fund Bitcoin purchases could face severe pressure if Bitcoin prices continue to decline. The outcome may influence other companies considering similar Bitcoin treasury strategies. The company's capital stack includes convertible bonds, equity, and other financing instruments, which are now under scrutiny as Bitcoin's price falls below the average acquisition cost. The report analyzes how different layers of the capital stack could be affected.

rss · The Block · Jun 23, 13:24

**Background**: The capital stack refers to the structure of all capital invested into a company, including debt and equity layers with different risk and return profiles. Strategy Inc. has aggressively accumulated Bitcoin since 2020, using proceeds from debt offerings and equity sales, turning its corporate treasury into a Bitcoin investment vehicle.

<details><summary>References</summary>
<ul>
<li><a href="https://www.foreignpolicyjournal.com/2026/05/24/strategy-inc-nasdaq-mstr-falls-to-163-as-bitcoin-treasury-model-draws-fresh-scrutiny/">Strategy Inc . (NASDAQ: MSTR) Falls to $163 as Bitcoin Treasury ...</a></li>
<li><a href="https://www.tipranks.com/news/company-announcements/strategy-incorporated-leans-into-bitcoin-treasury-model">Strategy Incorporated Leans Into Bitcoin Treasury Model</a></li>
<li><a href="https://equitymultiple.com/blog/capital-stack">Capital Stack: How It Works, What to Know - EquityMultiple</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#Corporate Treasury`, `#MicroStrategy`, `#Market Analysis`

---