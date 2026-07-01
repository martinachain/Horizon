---
layout: default
title: "Horizon Summary: 2026-07-01 (EN)"
date: 2026-07-01
lang: en
---

> From 82 items, 22 important content pieces were selected

---

1. [US Lifts Export Controls on Claude Fable 5 and Mythos 5](#item-1) ⭐️ 9.0/10
2. [Anthropic Releases Claude Sonnet 5 with Agentic Focus](#item-2) ⭐️ 8.0/10
3. [Claude Code Steganographically Marks Requests](#item-3) ⭐️ 8.0/10
4. [Google DeepMind Releases Nano Banana 2 Lite](#item-4) ⭐️ 8.0/10
5. [Kubernetes Ported to the Browser via WebAssembly](#item-5) ⭐️ 8.0/10
6. [Claude Sonnet 5 Nears Opus 4.8 at Lower Cost](#item-6) ⭐️ 8.0/10
7. [Supreme Court Allows Trump to Fire SEC, CFTC Commissioners at Will](#item-7) ⭐️ 8.0/10
8. [Meta's Brain2Qwerty v2 Decodes Thoughts into Text Non-Invasively](#item-8) ⭐️ 8.0/10
9. [Google's Copybara: Moving Code Between Repositories](#item-9) ⭐️ 7.0/10
10. [Anthropic Launches Claude Science for Secure Data Science](#item-10) ⭐️ 7.0/10
11. [Mistral Releases Leanstral 1.5 for Lean 4 Theorem Proving](#item-11) ⭐️ 7.0/10
12. [CERN Bids Farewell to LHC, Enters Long Shutdown 3](#item-12) ⭐️ 7.0/10
13. [US Senators Propose Bill to Block AI Tech Transfer to Adversaries](#item-13) ⭐️ 7.0/10
14. [New York Life Launches Tokenized High-Yield Bond Fund](#item-14) ⭐️ 7.0/10
15. [Ornith: Open-Source Coding Model for AI Agents](#item-15) ⭐️ 7.0/10
16. [California Partners with Anthropic to Offer Claude AI to State Agencies](#item-16) ⭐️ 7.0/10
17. [Visa, Stripe, Coinbase Join Open USD Stablecoin with Revenue Sharing](#item-17) ⭐️ 7.0/10
18. [StarkWare unveils Starknet post-quantum roadmap](#item-18) ⭐️ 7.0/10
19. [Taiwan's Crypto Law Mandates Licensing, Reserves, Penalties](#item-19) ⭐️ 6.0/10
20. [UK to lower stablecoin capital buffers below EU MiCA](#item-20) ⭐️ 6.0/10
21. [UK FCA Finalizes Crypto Rules for 2027 Mandatory Regime](#item-21) ⭐️ 6.0/10
22. [China's Qihoo 360 and Z.ai Release AI Vulnerability-Hunting Tools](#item-22) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [US Lifts Export Controls on Claude Fable 5 and Mythos 5](https://twitter.com/AnthropicAI/status/2072106151890809341) ⭐️ 9.0/10

The US Department of Commerce has lifted export controls on Anthropic's Claude Fable 5 and Mythos 5, allowing their deployment with new classifiers that block cybersecurity tasks. The decision follows productive conversations between Anthropic and the US government. This marks a groundbreaking shift in AI regulation, as the US government directly intervenes in the deployment of frontier models, setting a precedent for future AI governance. The restrictions on cybersecurity capabilities raise concerns about business reliance on such models and the predictability of regulatory processes. Claude Fable 5 is a state-of-the-art vision model, while Mythos 5 is designed for cybersecurity vulnerability discovery. The new classifiers target and block cybersecurity tasks, causing some routine coding and debugging to fall back to Opus 4.8 in the near term.

hackernews · Pragmata · Jun 30, 23:55 · [Discussion](https://news.ycombinator.com/item?id=48740771)

**Background**: Claude Fable 5 and Mythos 5 were released on June 9, 2026, with Fable 5 being a general-purpose vision model and Mythos 5 a specialized model for finding software vulnerabilities. Export controls were initially imposed due to national security concerns, particularly around the potential misuse of Mythos 5's capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://platform.claude.com/docs/en/about-claude/models/introducing-claude-fable-5-and-claude-mythos-5">Introducing Claude Fable 5 and Claude Mythos 5 - Claude Platform Docs</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://www.bbc.com/news/articles/cdr42623e1do">Fable and Mythos : Anthropic says US lifts export ban on its advanced...</a></li>

</ul>
</details>

**Discussion**: Community comments express concern about the lack of predictability in AI regulation, with users noting that businesses cannot build critical functions on frontier models due to sudden policy changes. Some highlight the irony that Fable 5 cannot be used for coding, and others call for actual laws rather than ad hoc decisions.

**Tags**: `#AI regulation`, `#export controls`, `#Anthropic`, `#national security`, `#frontier models`

---

<a id="item-2"></a>
## [Anthropic Releases Claude Sonnet 5 with Agentic Focus](https://www.anthropic.com/news/claude-sonnet-5) ⭐️ 8.0/10

Anthropic has released Claude Sonnet 5, an upgrade to Sonnet 4.6 that improves coding, tool use, and agentic capabilities, making it the most agentic Sonnet model yet. This release pushes agentic AI capabilities into a more affordable and faster model class, enabling broader adoption of autonomous agents for development and professional tasks, though community debate highlights cost-performance trade-offs with Opus. Claude Sonnet 5 offers near-Opus intelligence at a lower cost and higher speed, but benchmarks show it underperforms Opus on complex tasks at higher effort levels, and safety evaluations reveal a CyberGym score of 0 with default mitigations.

hackernews · marinesebastian · Jun 30, 17:59 · [Discussion](https://news.ycombinator.com/item?id=48736605)

**Background**: Anthropic's Claude models are categorized into Haiku, Sonnet, and Opus tiers, with Sonnet balancing capability and cost for everyday use. Agentic capabilities refer to a model's ability to autonomously plan, use tools, and execute multi-step tasks. The community discussion centers on whether Sonnet 5's cost per task justifies its use over Opus at higher effort levels.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude-sonnet-5-system-card">Claude Sonnet 5 System Card - anthropic.com</a></li>
<li><a href="https://aws.amazon.com/blogs/machine-learning/introducing-claude-sonnet-5-on-aws-anthropics-most-capable-sonnet-model/">Introducing Claude Sonnet 5 on AWS: Anthropic’s most capable ...</a></li>

</ul>
</details>

**Discussion**: Community comments express mixed sentiment: some users question Sonnet 5's cost-effectiveness compared to Opus, noting that Opus performs better at similar cost for higher effort tasks. Others highlight safety regressions, with Sonnet 5 scoring 0 on CyberGym with safeguards enabled, and point out that Sonnet 5's agentic optimizations may reduce performance on non-agentic tasks.

**Tags**: `#AI`, `#LLM`, `#Anthropic`, `#Claude`, `#agentic`

---

<a id="item-3"></a>
## [Claude Code Steganographically Marks Requests](https://thereallo.dev/blog/claude-code-prompt-steganography) ⭐️ 8.0/10

A developer discovered that Anthropic's Claude Code tool embeds steganographic markers in API requests, using the API base URL and timezone to generate hidden system prompts that identify the user's region and network environment. This raises serious concerns about transparency and trust in AI developer tools, as users were not informed that their requests were being covertly fingerprinted. It could erode developer confidence in Anthropic and similar AI tool providers. The steganographic markers are based on the API base URL and the user's timezone, and are designed to detect usage by Chinese firms potentially conducting model distillation. The implementation was described as 'sloppy' by some commenters, who noted that more sophisticated underhanded coding techniques could have made detection harder.

hackernews · kirushik · Jun 30, 15:44 · [Discussion](https://news.ycombinator.com/item?id=48734373)

**Background**: Steganography is the practice of hiding information within other data, such as text or images, to avoid detection. In AI tools, steganographic markers can be used to watermark requests or track usage without user awareness. Claude Code is a command-line tool from Anthropic that allows developers to interact with Claude AI directly from the terminal.

<details><summary>References</summary>
<ul>
<li><a href="https://thereallo.dev/blog/claude-code-prompt-steganography">Claude Code Is Steganographically Marking Requests</a></li>
<li><a href="https://www.cosmicjs.com/blog/cosmic-rundown-claude-code-steganography-postgres-19-data-center-power">Cosmic Rundown: Claude Code Steganography, Postgres 19, and Data Center Power Struggles</a></li>
<li><a href="https://eu.36kr.com/en/p/3876461674917892">Confirmed: Claude Code Secretly Accesses User Data - Time Zones and Chinese AI Labs as Key Targets</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: some criticize Anthropic for lack of transparency and trust, while others downplay the severity, arguing the intent (detecting model distillation by Chinese firms) is clear and does not harm normal developers. Some commenters suggest using open-source alternatives like Codex CLI to avoid such practices.

**Tags**: `#steganography`, `#AI ethics`, `#developer tools`, `#Anthropic`, `#transparency`

---

<a id="item-4"></a>
## [Google DeepMind Releases Nano Banana 2 Lite](https://deepmind.google/models/gemini-image/flash-lite/) ⭐️ 8.0/10

Google DeepMind has released Nano Banana 2 Lite, a distilled image generation model that offers faster inference (under 5 seconds per image) and improved text rendering compared to its predecessor. This release makes high-quality image generation more accessible and faster, potentially enabling real-time applications and lowering costs for developers, while also sparking debate about misuse in real estate listings and accessibility barriers due to account restrictions. Nano Banana 2 Lite is a distilled version of the base Nano Banana 2 model, offering speed improvements but with reduced output quality for nuanced prompts. It lacks programmatic aspect ratio control and is only accessible via Google's AI Studio, which requires a Google One account, excluding Workspace users.

hackernews · minimaxir · Jun 30, 16:48 · [Discussion](https://news.ycombinator.com/item?id=48735444)

**Background**: Distilled image generation models use techniques like knowledge distillation to compress a larger, slower model into a smaller, faster one while retaining most of the quality. This trade-off between speed and fidelity is common in AI deployment. Nano Banana 2 Lite is positioned for rapid iteration and low-cost generation, suitable for prototyping and applications where speed is critical.

<details><summary>References</summary>
<ul>
<li><a href="https://nanobanana-2.ai/nanobanana2-lite">Nano Banana 2 Lite - AI Image Editor with Nano Banana 2 Lite ...</a></li>
<li><a href="https://nanobanana-2.com/nano-banana-2-lite">Nano Banana 2 Lite - Free to Use Fast AI Image Generator</a></li>
<li><a href="https://nanobanana-pro.studio/nano-banana-2-lite">Nano Banana 2 Lite AI Image Generator | Gemini 3.1 Flash Lite</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some praise the speed and text rendering, while others criticize the lack of aspect ratio control and account restrictions. One user expressed frustration over AI-generated real estate images, and another noted the omission of ChatGPT in comparison charts.

**Tags**: `#AI`, `#image generation`, `#Google DeepMind`, `#model release`, `#community discussion`

---

<a id="item-5"></a>
## [Kubernetes Ported to the Browser via WebAssembly](https://ngrok.com/blog/i-ported-kubernetes-to-the-browser) ⭐️ 8.0/10

A developer from ngrok has created Webernetes, a project that ports Kubernetes to run inside a web browser using custom connectors and WebAssembly, allowing users to explore Kubernetes concepts without needing a local cluster. This project makes Kubernetes education more accessible by eliminating the need for local cluster setup, and it also showcases a novel workflow for testing AI-generated code against real Kubernetes behavior rather than relying on superficial review. Wekubernetes does not run actual containers in the browser; instead, each service requires a custom connector, and the project currently focuses on conceptual and architectural education rather than full kubectl mastery.

hackernews · peterdemin · Jun 30, 20:48 · [Discussion](https://news.ycombinator.com/item?id=48738985)

**Background**: Kubernetes is an open-source container orchestration system for automating deployment, scaling, and management of containerized applications. WebAssembly (Wasm) is a universal bytecode technology originally designed for browsers but now also used server-side for lightweight, sandboxed execution. This project combines both to create a browser-based Kubernetes simulation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kubernetes">Kubernetes - Wikipedia</a></li>
<li><a href="https://www.cncf.io/blog/2024/03/12/webassembly-on-kubernetes-from-containers-to-wasm-part-01/">WebAssembly on Kubernetes: from containers to Wasm (part 01) | CNCF</a></li>

</ul>
</details>

**Discussion**: The community is excited about the educational potential, with comments praising it as a great tool for learning Kubernetes architecture. Some users note that it is not a full port since it doesn't run real containers, but they appreciate the innovative approach to testing AI-generated code against Kubernetes.

**Tags**: `#Kubernetes`, `#WebAssembly`, `#education`, `#cloud-native`, `#browser`

---

<a id="item-6"></a>
## [Claude Sonnet 5 Nears Opus 4.8 at Lower Cost](https://decrypt.co/372458/anthropic-claude-sonnet-5-close-opus-4-8) ⭐️ 8.0/10

Anthropic released Claude Sonnet 5, a mid-tier model that achieves performance within a few points of the flagship Opus 4.8 on most benchmarks, while being priced at $3/$15 per million tokens compared to Opus 4.8's $5/$25. This release significantly lowers the cost of near-frontier AI performance, making advanced capabilities more accessible to developers and businesses. It also marks the first time Sonnet and Opus models fall on a single cost-performance curve, blurring the line between tiers. On deep coding (SWE-bench Pro), Opus 4.8 still leads 69.2 vs 63.2, and on olympiad math (USAMO) 96.7 vs 79.5. However, Sonnet 5 beats Opus on knowledge work and ties on HLE with tools, while crushing its predecessor Sonnet 4.6 by double-digit margins.

rss · Decrypt · Jun 30, 20:51

**Background**: Anthropic's Claude model family includes tiers: Haiku (fast/cheap), Sonnet (balanced), and Opus (flagship). The release comes amid U.S. export restrictions on Anthropic's higher-end models Fable 5 and Mythos, which were recently lifted by the Trump administration. Sonnet 5's strong performance at lower cost may reduce demand for the restricted models.

<details><summary>References</summary>
<ul>
<li><a href="https://llm-stats.com/blog/research/claude-sonnet-5-vs-claude-opus-4-8">Claude Sonnet 5 vs Claude Opus 4.8: The Complete Comparison</a></li>
<li><a href="https://codingfleet.com/blog/claude-sonnet-5-vs-claude-opus-4-8/">Claude Sonnet 5 vs Claude Opus 4.8: 93% Power, 60% Price ...</a></li>
<li><a href="https://9to5mac.com/2026/06/30/claude-fable-5-cleared-to-return-as-us-lifts-anthropics-export-control-restriction/">Claude Fable 5 cleared to return as US lifts Anthropic’s ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Anthropic`, `#Claude`, `#language models`, `#machine learning`

---

<a id="item-7"></a>
## [Supreme Court Allows Trump to Fire SEC, CFTC Commissioners at Will](https://decrypt.co/372342/supreme-court-trump-fire-sec-cftc-commissioners-crucial-moment-crypto) ⭐️ 8.0/10

The U.S. Supreme Court overturned a 91-year precedent, ruling that President Trump can fire commissioners of independent agencies like the SEC and CFTC at will, without cause. This ruling gives the president unprecedented control over financial regulators, which could lead to abrupt changes in crypto regulation and enforcement priorities, creating uncertainty for the industry. The decision extends beyond the SEC and CFTC to other independent agencies like the NLRB, but the Federal Reserve is reportedly exempt. The case originated from a challenge to the FTC's structure.

rss · Decrypt · Jun 29, 19:29

**Background**: Since 1935, a precedent known as Humphrey's Executor had protected commissioners of independent agencies from being fired without cause, ensuring political independence. The SEC and CFTC are key regulators for crypto markets; the SEC oversees securities, while the CFTC regulates derivatives and commodities like Bitcoin.

<details><summary>References</summary>
<ul>
<li><a href="https://www.breitbart.com/economy/2026/06/29/justices-overturn-1935-precedent-backing-presidents-power-to-remove-agency-heads/">Justices Overturn 1935 Precedent , Backing President’s Power to...</a></li>
<li><a href="https://www.sec.gov/about/sec-commissioners">SEC.gov | SEC Commissioners</a></li>
<li><a href="https://www.cftc.gov/About/Commissioners/index.htm">Chairman & Commissioners | CFTC</a></li>

</ul>
</details>

**Tags**: `#Supreme Court`, `#crypto regulation`, `#SEC`, `#CFTC`, `#policy`

---

<a id="item-8"></a>
## [Meta's Brain2Qwerty v2 Decodes Thoughts into Text Non-Invasively](https://decrypt.co/372338/meta-brain2qwerty-ai-brain-activity-text) ⭐️ 8.0/10

Meta FAIR released Brain2Qwerty v2 on June 25, 2026, an AI system that decodes full typed sentences from magnetoencephalography (MEG) signals without requiring surgery or implants. This advancement significantly improves non-invasive brain-computer interfaces, potentially restoring communication for people with speech impairments and opening new avenues for human-computer interaction. The model was trained on 35 participants typing memorized sentences, using both EEG and MEG recordings, with MEG achieving higher accuracy. The system is a three-stage deep neural network that decodes text from brain signals.

rss · Decrypt · Jun 29, 18:47

**Background**: Brain-computer interfaces (BCIs) traditionally require invasive implants to achieve high decoding accuracy. Non-invasive methods like EEG and MEG are safer but less precise. Brain2Qwerty v2 leverages AI to improve non-invasive decoding, making it competitive with invasive approaches.

<details><summary>References</summary>
<ul>
<li><a href="https://explainx.ai/blog/meta-brain2qwerty-v2-non-invasive-brain-to-text-decoder-2026">Meta Brain2Qwerty v2: Reading Your Thoughts Without ...</a></li>
<li><a href="https://www.digitaltrends.com/cool-tech/metas-brain2qwerty-v2-turns-thoughts-into-text-and-it-doesnt-need-brain-implants/">Meta's Brain2Qwerty v2 turns thoughts into text, and it doesn't need brain implants - Digital Trends</a></li>
<li><a href="https://www.nature.com/articles/s41593-026-02303-2">Noninvasive decoding of typed sentences from human brain activity | Nature Neuroscience</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the improvement is incremental but statistically significant, and praised Meta for releasing code and datasets. Some expressed privacy concerns about neural tracking, while others discussed potential applications and comparisons to earlier technologies.

**Tags**: `#AI`, `#brain-computer interface`, `#neural decoding`, `#Meta`, `#non-invasive`

---

<a id="item-9"></a>
## [Google's Copybara: Moving Code Between Repositories](https://github.com/google/copybara) ⭐️ 7.0/10

Google has open-sourced Copybara, a tool for transforming and moving code between repositories, which is used internally at Google for tasks like exporting folders with full history or bidirectional syncing. Copybara simplifies the complex workflow of synchronizing code across multiple repositories, which is common in large projects that need to share code between internal and public repos or between different teams. Copybara is a declarative tool where users describe source and destination repositories and transformations in a configuration file. It supports both one-time export and bidirectional shipping, preserving commit history.

hackernews · reconnecting · Jun 30, 23:45 · [Discussion](https://news.ycombinator.com/item?id=48740698)

**Background**: Many organizations use a monorepo for internal development but need to publish subsets of code to public repositories. Copybara automates this process, handling history preservation and transformation, which is otherwise error-prone and time-consuming.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/google/copybara">GitHub - google/ copybara : Copybara : A tool for transforming and...</a></li>
<li><a href="https://stackfoss.medium.com/copybara-a-tool-for-transforming-and-moving-code-between-repositories-315a75502f6d">Copybara: A Tool for Transforming and Moving Code between Repositories | by StackFoss | Medium</a></li>
<li><a href="https://blog.kubesimplify.com/moving-code-between-git-repositories-with-copybara">Moving code between GIT repositories with Copybara | Kubesimplify</a></li>

</ul>
</details>

**Discussion**: Users report using Copybara for simple one-time exports with history preservation, finding it powerful but note that bidirectional shipping can be a hassle. Some compare it to alternatives like Josh (used by Rust) and the now-archived fbshipit from Meta.

**Tags**: `#version control`, `#code synchronization`, `#developer tools`, `#open source`

---

<a id="item-10"></a>
## [Anthropic Launches Claude Science for Secure Data Science](https://claude.com/product/claude-science) ⭐️ 7.0/10

Anthropic has launched Claude Science, a local server-based AI workbench for data science that integrates HPC clusters, databases, and over 60 domain-specific skills, targeting secure research environments like pharma. This launch addresses the critical need for secure, auditable AI-assisted data science in regulated industries, enabling researchers to work with sensitive data without cloud exposure. It also signals a shift toward local-server AI architectures for enterprise scientific computing. Claude Science runs a local server with a web-based UI, decoupled from the host machine, which allows secure connections to institutional data sources. It includes integrations with PubMed, Jupyter, R, and HPC clusters, and produces auditable artifacts for every analysis step.

hackernews · lebovic · Jun 30, 17:07 · [Discussion](https://news.ycombinator.com/item?id=48735770)

**Background**: Data science in regulated industries like pharmaceuticals often requires working with sensitive data on locked-down networks, making cloud-based AI tools impractical. Claude Science's local server architecture allows researchers to run AI-assisted analysis directly on their institutional infrastructure, maintaining compliance and security.

<details><summary>References</summary>
<ul>
<li><a href="https://claude.com/product/claude-science">Claude Science beta | Claude by Anthropic</a></li>
<li><a href="https://www.anthropic.com/news/claude-science-ai-workbench">Claude Science, an AI workbench for scientists \ Anthropic</a></li>
<li><a href="https://www.explainx.ai/blog/claude-science-ai-workbench-scientists-2026">Claude Science: Anthropic's AI Workbench for Scientists [2026]</a></li>

</ul>
</details>

**Discussion**: Community comments highlight the tool's practical value in secure environments, with one developer noting its HPC integration as a key differentiator. Another user tested it for RNAi biopesticide design and found it competent but naive, while others debated whether the focus on data science rather than pure science limits its impact.

**Tags**: `#AI`, `#data science`, `#Anthropic`, `#pharma`, `#HPC`

---

<a id="item-11"></a>
## [Mistral Releases Leanstral 1.5 for Lean 4 Theorem Proving](https://docs.mistral.ai/models/model-cards/leanstral-1-5-26-06) ⭐️ 7.0/10

Mistral has released Leanstral 1.5, a specialized language model for the Lean 4 theorem prover, improving upon the previous version. The model is available via Mistral's platform and supports automated theorem proving tasks. This release advances AI-assisted formal verification, making it easier for mathematicians and developers to prove theorems in Lean 4. It also integrates with new open-source tools like OpenATP, broadening access to automated theorem proving. Leanstral 1.5 is specialized for Lean 4 and does not support other theorem provers like Coq. The previous production model was deprecated on May 22, 2025, and the new model is accessible via Mistral's Vibe harness.

hackernews · vetronauta · Jun 30, 20:44 · [Discussion](https://news.ycombinator.com/item?id=48738938)

**Background**: Lean 4 is an interactive theorem prover and functional programming language used for formal verification of mathematical proofs and software. Automated theorem proving (ATP) uses computer programs to prove theorems automatically. Leanstral is a specialized AI model that assists users in writing Lean 4 proofs.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/henryrobbins/open-atp">GitHub - henryrobbins/open-atp: OpenATP is an open-source ...</a></li>
<li><a href="https://leanprover.github.io/theorem_proving_in_lean4/">Theorem Proving in Lean 4</a></li>

</ul>
</details>

**Discussion**: Community comments include a user reporting a poor customer support experience with Mistral's platform, which lowered the score. Another user released OpenATP, an open-source Python package that integrates with Leanstral, adding practical value. Some commenters noted the model's specialization for Lean 4 and expressed interest in broader support.

**Tags**: `#AI`, `#theorem proving`, `#Lean 4`, `#Mistral`, `#open-source`

---

<a id="item-12"></a>
## [CERN Bids Farewell to LHC, Enters Long Shutdown 3](https://home.cern/cern-bids-farewell-to-the-lhc-and-enters-long-shutdown-3/) ⭐️ 7.0/10

CERN has officially shut down the Large Hadron Collider (LHC) to begin Long Shutdown 3 (LS3), a multi-year upgrade phase that will dismantle 1.2 kilometers of the accelerator to install new equipment for the High-Luminosity LHC (HL-LHC) project. This upgrade will significantly increase the LHC's collision rate, allowing scientists to collect an order of magnitude more data and potentially discover new physics beyond the Standard Model. The HL-LHC is expected to operate from 2030 onward, extending the LHC's scientific reach. During LS3, teams will dismantle 1.2 kilometers of the LHC to install new focusing magnets and other components for the HL-LHC. The upgrade will increase the number of collisions per bunch crossing, enabling more precise measurements of rare processes.

hackernews · HelloUsername · Jun 29, 18:52 · [Discussion](https://news.ycombinator.com/item?id=48723484)

**Background**: The Large Hadron Collider (LHC) is the world's highest-energy particle accelerator, located at CERN near Geneva. It smashes protons together at near-light speeds to study fundamental particles and forces. The High-Luminosity LHC (HL-LHC) is a major upgrade that will increase the LHC's luminosity (collision rate) by a factor of 10, allowing scientists to study rare phenomena in greater detail.

<details><summary>References</summary>
<ul>
<li><a href="https://www.interactions.org/press-release/cern-bids-farewell-to-the-lhc-and-enters-long-shutdown-3">CERN bids farewell to the LHC and enters Long Shutdown 3</a></li>
<li><a href="https://project-hl-lhc-industry.web.cern.ch/content/hilumi-nutshell">HiLumi in a nutshell | HL- LHC Industry</a></li>
<li><a href="https://www.symmetrymagazine.org/article/explain-it-in-60-seconds-high-luminosity-lhc?language_content_entity=und">Explain it in 60 seconds: High - Luminosity LHC | symmetry magazine</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed sentiments: some noted the title was overdramatic since the LHC is being upgraded, not retired. Others shared technical details about detector upgrades, such as the ATLAS ITk with 5 billion channels, and historical context comparing the LHC to the canceled Superconducting Super Collider.

**Tags**: `#CERN`, `#LHC`, `#particle physics`, `#science`, `#upgrade`

---

<a id="item-13"></a>
## [US Senators Propose Bill to Block AI Tech Transfer to Adversaries](https://www.coindesk.com/policy/2026/06/30/u-s-senators-seek-to-block-foreign-adversaries-from-ai-technology-in-new-bill) ⭐️ 7.0/10

U.S. senators have introduced a new bill aimed at preventing foreign adversaries from accessing American artificial intelligence technology, citing national security concerns. This legislation could significantly impact the AI industry by restricting technology exports and collaboration with certain countries, potentially reshaping global AI development dynamics. The bill specifically targets foreign adversaries such as China and Russia, and includes provisions for export controls and investment screening in the AI sector.

rss · CoinDesk · Jun 30, 23:02

**Background**: The U.S. government has been increasingly concerned about the transfer of sensitive technologies to adversarial nations. AI is considered a critical technology for economic and military advantage, prompting legislative efforts to safeguard it.

**Tags**: `#AI policy`, `#national security`, `#legislation`, `#technology transfer`

---

<a id="item-14"></a>
## [New York Life Launches Tokenized High-Yield Bond Fund](https://www.coindesk.com/markets/2026/06/30/nasdaq-expands-distribution-of-its-market-data-into-blockchain-infrastructure) ⭐️ 7.0/10

New York Life Investment Management, in collaboration with Centrifuge, launched the NYLIM Anemoy U.S. High Yield Corporate Bond Segregated Portfolio (ticker: HYB), a tokenized fund that allows eligible investors to subscribe and redeem shares using Circle's USDC stablecoin. This marks a significant step in mainstream adoption of tokenized real-world assets, bringing institutional-grade high-yield bond strategies onto blockchain rails and potentially improving liquidity and accessibility for investors. The fund is a segregated portfolio managed by New York Life Investment Management, with subscriptions and redemptions settled in USDC. It leverages Centrifuge's infrastructure for tokenization and onchain asset management.

rss · CoinDesk · Jun 30, 13:00

**Background**: Tokenized funds represent a growing trend where traditional financial assets are represented as digital tokens on a blockchain, enabling faster settlement, fractional ownership, and programmability. Centrifuge is a platform specializing in tokenizing real-world assets, providing compliance and infrastructure for institutional use.

<details><summary>References</summary>
<ul>
<li><a href="https://thecoinomist.com/news/new-york-life-tokenized-high-yield-bond-fund-hyb/">New York Life Launches Tokenized High - Yield Bond Fund HYB</a></li>
<li><a href="https://www.mexc.com/news/1185798">New York Life Investment Management Debuts First Tokenized Bond ...</a></li>
<li><a href="https://www.binance.com/en-TR/square/post/06-30-2026-new-york-life-makes-tokenization-debut-with-onchain-high-yield-bond-fund-with-centrifuge-339680357583041">New York Life makes tokenization debut with onchain high - yield bond ...</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#financial technology`, `#market data`, `#Nasdaq`

---

<a id="item-15"></a>
## [Ornith: Open-Source Coding Model for AI Agents](https://decrypt.co/372361/ornith-open-source-coding-model-built-for-agents) ⭐️ 7.0/10

DeepReinforce has released Ornith-1.0, an open-source family of coding models specifically designed for AI agents to complete tasks autonomously, rather than just autocompleting code. The models range from a 9B dense model to a 397B mixture-of-experts model, all under the MIT license. This marks a shift from code autocompletion to agentic coding, where AI can independently plan and execute software engineering tasks. It addresses the growing need for open-source models that power AI agents in development workflows, potentially reducing reliance on proprietary solutions. Ornith-1.0 ships as a dense 9B model plus two Mixture-of-Experts models (35B, 397B), all with a 256K token context window and an OpenAI-compatible interface. The 9B model fits on a single 80GB GPU, making it accessible for local deployment.

rss · Decrypt · Jun 29, 21:27

**Background**: Traditional coding models like GitHub Copilot focus on autocompleting the next line or snippet. AI agents, however, require models that can understand complex tasks, plan steps, and execute multi-file changes. Ornith is built for this agentic paradigm, using self-scaffolding reinforcement learning to improve task completion.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/deepreinforce-ai/Ornith-1">GitHub - deepreinforce -ai/ Ornith -1 · GitHub</a></li>
<li><a href="https://deep-reinforce.com/ornith_1_0.html">Ornith -1.0: Self-Scaffolding LLMs... | DeepReinforce Blog | Jun. 2026</a></li>
<li><a href="https://www.marktechpost.com/2026/06/25/deepreinforce-releases-ornith-1-0-an-open-source-coding-model-family-that-learns-its-own-rl-scaffolds/">DeepReinforce Releases Ornith -1.0: An Open-Source Coding Model ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#open-source`, `#coding model`, `#agents`, `#software engineering`

---

<a id="item-16"></a>
## [California Partners with Anthropic to Offer Claude AI to State Agencies](https://decrypt.co/372301/california-strikes-deal-anthropic-bring-claude-ai-state-agencies) ⭐️ 7.0/10

California Governor Gavin Newsom announced a deal with Anthropic to make Claude the first AI tool available to all state agencies and local governments at half the standard price. This marks a significant step in government adoption of generative AI, potentially improving efficiency and service delivery while setting a precedent for public-sector AI procurement. The agreement provides a 50% discount on Claude for all California state agencies and local governments, making it the first such statewide AI deal in the U.S.

rss · Decrypt · Jun 29, 16:54

**Background**: Anthropic is an AI safety-focused company based in San Francisco that developed the Claude series of large language models. In 2023, Governor Newsom issued an executive order on generative AI policy, positioning California as a leader in responsible AI adoption.

<details><summary>References</summary>
<ul>
<li><a href="https://www.politico.com/news/2026/06/29/exclusive-newsom-anthropic-ink-deal-to-expand-government-use-00979584">Newsom, Anthropic ink deal to expand government use</a></li>
<li><a href="https://techcrunch.com/2026/06/29/anthropic-and-gov-newsom-forge-deal-allowing-california-government-to-use-claude-at-half-price/">Anthropic and Gov. Newsom forge deal allowing California ...</a></li>
<li><a href="https://www.inc.com/moses-jeanfrancois/californias-massive-ai-deal-promises-faster-government-critics-arent-buying-it/91367284">California’s Massive AI Deal Promises Faster Government—and ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Government`, `#Anthropic`, `#Claude`, `#Policy`

---

<a id="item-17"></a>
## [Visa, Stripe, Coinbase Join Open USD Stablecoin with Revenue Sharing](https://www.theblock.co/post/406736/visa-stripe-coinbase-join-open-usd-stablecoin-shares-reserve-revenue?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Visa, Stripe, and Coinbase have joined the Open USD stablecoin project, which will allow businesses to mint and redeem the stablecoin without fees or volume limits, and will share reserve revenue with participants. This marks a significant industry shift as major payment and crypto companies back a stablecoin that redistributes reserve income, potentially challenging dominant issuers like Tether and Circle. Open USD is expected to launch later this year, backed by over 140 partners including Visa, Stripe, and Coinbase, and will be the first stablecoin designed as open infrastructure with fee-free minting and redemption.

rss · The Block · Jun 30, 14:57

**Background**: Stablecoins are cryptocurrencies pegged to a stable asset like the US dollar, with issuers typically earning revenue from interest on reserve assets. Traditional stablecoin issuers keep this revenue, but Open USD proposes to share it with participants, aligning incentives across the ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://joinopenstandard.com/">Open USD (OUSD) Stablecoin | Open Standard</a></li>
<li><a href="https://genfinity.io/2026/06/30/open-standard-launches-open-usd-stablecoin-140-partners/">Open Standard Unveils Open USD : A 140-Partner Stablecoin Backed...</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#blockchain`, `#fintech`, `#cryptocurrency`, `#payments`

---

<a id="item-18"></a>
## [StarkWare unveils Starknet post-quantum roadmap](https://www.theblock.co/post/406677/starkware-unveils-starknet-post-quantum-roadmap-calling-it-cryptos-strongest-to-date?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

StarkWare has announced a three-phase roadmap to make Starknet quantum-resistant within months, claiming it is the strongest post-quantum plan in crypto. This roadmap positions Starknet as a leader in post-quantum security, potentially setting a standard for other blockchains and protecting assets against future quantum computing threats. The roadmap leverages STARK proofs and native account abstraction, which StarkWare says gives Starknet architectural advantages for a more straightforward and less costly migration compared to other blockchains.

rss · The Block · Jun 30, 12:30

**Background**: Post-quantum cryptography aims to secure systems against attacks from future quantum computers, which could break current cryptographic standards like ECDSA. Starknet is an Ethereum Layer 2 scaling solution that uses STARK proofs for validity. The roadmap responds to growing concerns and guidance from institutions like the White House and NIST.

<details><summary>References</summary>
<ul>
<li><a href="https://quantumzeitgeist.com/post-quantum-roadmap-starkware-maps-starknets/">StarkWare Maps Post-Quantum Roadmap for Starknet’s Future</a></li>
<li><a href="https://starkware.co/blog/the-architecture-advantage-starknets-quantum-readiness-roadmap/">The Architecture Advantage: Starknet's Post-Quantum Roadmap</a></li>
<li><a href="https://www.theblock.co/post/396987/starkware-quantum-safe-bitcoin">StarkWare researcher proposes ' quantum -safe' Bitcoin... | The Block</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#post-quantum cryptography`, `#Starknet`, `#scalability`

---

<a id="item-19"></a>
## [Taiwan's Crypto Law Mandates Licensing, Reserves, Penalties](https://www.coindesk.com/policy/2026/07/01/taiwan-s-sweeping-crypto-law-raises-the-bar-with-licensing-reserve-mandates-and-tough-penalties) ⭐️ 6.0/10

Taiwan has enacted a comprehensive cryptocurrency law requiring all crypto platforms to obtain licenses from the Financial Supervisory Commission (FSC), maintain reserve mandates, and face strict penalties for non-compliance. This regulation sets a high bar for crypto operations in Taiwan, potentially influencing other Asian markets and providing clearer legal frameworks for investors and businesses. The law mandates that crypto platforms must apply for FSC licenses before operating, and they are required to hold reserves to protect customer assets. Penalties for violations can be severe, including fines and imprisonment.

rss · CoinDesk · Jul 1, 05:04

**Background**: Cryptocurrency regulation has been a global focus, with many jurisdictions introducing licensing and reserve requirements to combat fraud and protect consumers. Taiwan's FSC is the primary financial regulator, overseeing securities, banking, and insurance sectors. This new law brings crypto under similar oversight.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Financial_Supervisory_Commission_(Taiwan)">Financial Supervisory Commission (Taiwan) - Wikipedia FSC Annual Report-Financial Supervisory Commission Banking Bureau, Financial Supervisory Commmission, R.O.C. Financial Examination Bureau, Financial Supervisory ... Financial Supervisory Commission, Taiwan 2024-2025 Annual Report Financial Supervisory Commission - Annual Report 2024-2025 ...</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#regulation`, `#Taiwan`, `#policy`

---

<a id="item-20"></a>
## [UK to lower stablecoin capital buffers below EU MiCA](https://www.coindesk.com/policy/2026/06/30/uk-to-lower-stablecoin-capital-buffers-undercutting-eu-s-mica-requirements) ⭐️ 6.0/10

The UK's Financial Conduct Authority (FCA) has proposed lowering capital buffer requirements for stablecoin issuers to 1% of reserves, undercutting the EU's MiCA regulation which mandates 2%. This regulatory divergence could make the UK a more attractive hub for stablecoin issuers compared to the EU, potentially shifting market dynamics and influencing global stablecoin regulation. The FCA's proposal follows industry pushback and the Bank of England's backtracking on limiting the value of stablecoins. The final rulebook is expected to be published later in 2026.

rss · CoinDesk · Jun 30, 10:08

**Background**: Stablecoins are cryptocurrencies designed to maintain a stable value, often pegged to fiat currency like the US dollar. Capital buffers are reserves that issuers must hold to cover potential losses, ensuring stability and protecting users. The EU's Markets in Crypto-Assets Regulation (MiCA) set a 2% capital buffer requirement for significant stablecoins, which the UK now plans to undercut.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/policy/2026/06/30/uk-to-lower-stablecoin-capital-buffers-undercutting-eu-s-mica-requirements">UK's FCA lowers stablecoin capital buffers to 1% ... - CoinDesk</a></li>
<li><a href="https://www.reuters.com/business/finance/uk-dilutes-stablecoin-capital-requirement-final-crypto-rulebook-2026-06-29/">UK dilutes stablecoin capital requirement in final crypto ...</a></li>

</ul>
</details>

**Tags**: `#crypto regulation`, `#stablecoins`, `#UK policy`, `#MiCA`

---

<a id="item-21"></a>
## [UK FCA Finalizes Crypto Rules for 2027 Mandatory Regime](https://decrypt.co/372394/fca-finalizes-landmark-crypto-rules-to-make-uk-a-global-hub) ⭐️ 6.0/10

The UK Financial Conduct Authority (FCA) has published its final rulebook for crypto firms, establishing a mandatory regulatory regime that will come fully into force on October 25, 2027. This landmark regulation positions the UK as a global crypto hub by providing legal clarity and investor protection, potentially attracting more crypto businesses to operate in the UK. The mandatory regime requires all crypto firms to relicense under the Financial Services and Markets Act (FSMA) by October 2027, with gradual implementation starting in 2025. The rules include specific capital requirements and stablecoin regulations.

rss · Decrypt · Jun 30, 10:58

**Background**: The UK has been developing a comprehensive crypto regulatory framework to replace the current anti-money laundering registration system. The FCA's final rules complete a multi-year roadmap and aim to balance innovation with consumer protection, making the UK a competitive destination for digital asset businesses.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/372394/fca-finalizes-landmark-crypto-rules-to-make-uk-a-global-hub">FCA Finalizes Landmark Crypto Rules to Make UK a 'Global... - Decrypt</a></li>
<li><a href="https://www.coingabbar.com/en/crypto-currency-news/uk-crypto-regulations-deadline-fca-final-framework-2027">UK Crypto Regulations 2027: FCA Sets Deadline for Firms</a></li>
<li><a href="https://www.mexc.com/news/1184560">UK crypto regulation overhaul forces every firm to relicense by 2027</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#regulation`, `#UK`, `#finance`

---

<a id="item-22"></a>
## [China's Qihoo 360 and Z.ai Release AI Vulnerability-Hunting Tools](https://decrypt.co/372345/china-has-own-mythos-now-one-version-free) ⭐️ 6.0/10

Qihoo 360 unveiled its homegrown vulnerability-hunting AI, Tulongfeng, and Z.ai released a comparable open-weight tool that anyone can download. This development challenges the US monopoly on AI-powered vulnerability hunting, as exemplified by Anthropic's Mythos, and could democratize cybersecurity capabilities. Qihoo 360 claims Tulongfeng has found 3,432 software vulnerabilities, including 105 confirmed by Chinese authorities, though Reuters could not independently verify these claims.

rss · Decrypt · Jun 29, 20:16

**Background**: AI vulnerability-hunting tools use large language models to automatically find security flaws in software. Anthropic's Mythos, a leading tool in this space, is subject to US export restrictions, prompting China to develop its own alternatives.

<details><summary>References</summary>
<ul>
<li><a href="https://www.techtimes.com/articles/319269/20260629/china-builds-ai-vulnerability-scanner-counter-mythos-every-zero-day-goes-beijing-law.htm">China Builds AI Vulnerability Scanner to Counter Mythos: Every...</a></li>
<li><a href="https://www.forbes.com/sites/the-wiretap/2026/06/30/qihoo-360-the-cyber-giant-behind-chinas-mythos-rival/">Qihoo 360 : The Cyber Giant Behind China’s Mythos Rival</a></li>
<li><a href="https://en.interaffairs.ru/article/reuters-chinas-360-says-it-has-developed-tools-to-match-anthropics-mythos/">Reuters: China’s 360 says it has developed tools to match...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cybersecurity`, `#open-source`, `#vulnerability-hunting`

---