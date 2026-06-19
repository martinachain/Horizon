---
layout: default
title: "Horizon Summary: 2026-06-19 (EN)"
date: 2026-06-19
lang: en
---

> From 89 items, 24 important content pieces were selected

---

1. [10K GitHub Repos Found Distributing Trojan Malware](#item-1) ⭐️ 9.0/10
2. [China's Z.AI Releases GLM-5.2, Rivals Claude Opus on Huawei Chips](#item-2) ⭐️ 9.0/10
3. [Zero-Touch OAuth for MCP Simplifies Enterprise Auth](#item-3) ⭐️ 8.0/10
4. [Hospitals and Universities Repurpose Drugs at 90% Lower Cost](#item-4) ⭐️ 8.0/10
5. [New Site Checks LLM Recognition of Individuals](#item-5) ⭐️ 8.0/10
6. [Midjourney Pivots from AI Art to Medical Imaging](#item-6) ⭐️ 8.0/10
7. [Nvidia's ENPIRE Lets AI Agents Train Robot Fleets Autonomously](#item-7) ⭐️ 8.0/10
8. [Let's Encrypt Renewal Errors Due to 90-Minute Degraded Performance](#item-8) ⭐️ 7.0/10
9. [Ubiquiti Launches Enterprise NAS Built on ZFS](#item-9) ⭐️ 7.0/10
10. [Cornell's CS 6120 Advanced Compilers Free Online](#item-10) ⭐️ 7.0/10
11. [Beyond .gitignore: Alternative Git Ignore Mechanisms](#item-11) ⭐️ 7.0/10
12. [Perplexity's AI Agent Gets Self-Improving Memory](#item-12) ⭐️ 7.0/10
13. [CME to Sue CFTC Over Bitcoin Perpetual Futures Approval](#item-13) ⭐️ 7.0/10
14. [France to Phase Out Non-Quantum Encryption from 2027](#item-14) ⭐️ 7.0/10
15. [Estonia Proposes National IDs for AI Agents](#item-15) ⭐️ 7.0/10
16. [Morgan Stanley Files for ETH and SOL ETFs with Lowest Fees](#item-16) ⭐️ 7.0/10
17. [Fed Proposes Customer ID Rules for Stablecoin Issuers](#item-17) ⭐️ 7.0/10
18. [Bitcoin Below Mining Cost for Five Months Squeezes Miners](#item-18) ⭐️ 6.0/10
19. [Ethereum Foundation loses another key leader as co-executive director resigns](#item-19) ⭐️ 6.0/10
20. [Algorand roadmap targets quantum resistance by 2028](#item-20) ⭐️ 6.0/10
21. [Survey: Over a Third of Psychologists Report Patients Using AI in Therapy](#item-21) ⭐️ 6.0/10
22. [Judge: Sports Prediction Markets Not Under CFTC Purview](#item-22) ⭐️ 6.0/10
23. [GLAAD Warns AI Amplifies Anti-LGBTQ Bias](#item-23) ⭐️ 6.0/10
24. [DAO Hack 10 Years On: $130M Security Fund Emerges](#item-24) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [10K GitHub Repos Found Distributing Trojan Malware](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 9.0/10

A security researcher discovered over 10,000 GitHub repositories distributing Trojan malware, part of a sophisticated campaign targeting automated agents and dependency systems. This massive-scale attack undermines trust in open-source software supply chains and could lead to widespread infections if automated tools unknowingly pull malicious dependencies. The repositories are not forks, come from different contributors, and are updated frequently to appear in search results. The malware is linked to the Disco trojan family.

hackernews · theorchid · Jun 18, 11:45 · [Discussion](https://news.ycombinator.com/item?id=48583928)

**Background**: Dependency confusion attacks exploit package managers that fetch packages from public repositories when internal packages are misconfigured. This campaign targets automated agents that clone repositories for dependency resolution, making it a supply chain threat.

<details><summary>References</summary>
<ul>
<li><a href="https://orchidfiles.com/github-repositories-distributing-malware/">I discovered a large-scale malware distribution on GitHub</a></li>
<li><a href="https://medium.com/@alex.birsan/dependency-confusion-how-i-hacked-into-apple-microsoft-and-dozens-of-other-companies-4a5d60fec610">Dependency Confusion: How I Hacked Into Apple, Microsoft and Dozens of Other Companies | by Alex Birsan | Medium</a></li>
<li><a href="https://owasp.org/www-project-top-10-ci-cd-security-risks/CICD-SEC-03-Dependency-Chain-Abuse">CICD-SEC-3: Dependency Chain Abuse | OWASP Foundation</a></li>

</ul>
</details>

**Discussion**: Commenters noted the attack targets automated agents, not humans, and that frequent commits help repos appear in 'last updated' searches. One user confirmed their name was used on fake projects, and another uploaded a sample linked to the Disco trojan family.

**Tags**: `#malware`, `#supply chain security`, `#GitHub`, `#cybersecurity`, `#open source`

---

<a id="item-2"></a>
## [China's Z.AI Releases GLM-5.2, Rivals Claude Opus on Huawei Chips](https://decrypt.co/371613/china-z-ai-glm-5-2-model-rivals-claude-opus) ⭐️ 9.0/10

Z.AI (Zhipu AI) released GLM-5.2, a Mixture-of-Experts model with 753B total parameters and 40B active per token, on June 13, 2026. It scores within 1% of Anthropic's Claude Opus 4.8 on long-horizon coding benchmarks while running entirely on Huawei silicon and costing 82% less per token. This achievement demonstrates that a Chinese AI model can rival top-tier Western models without using Nvidia chips, highlighting the rapid advancement of domestic AI hardware and software ecosystems. The significant cost reduction could democratize access to frontier AI capabilities, while the geopolitical implications underscore the decoupling of AI supply chains. GLM-5.2 is an open-weights model optimized for coding and agentic tasks, released under Z.AI's international brand. It runs on Huawei's Ascend AI processors, which are part of a domestic chip ecosystem that Huawei expects to generate $12 billion in revenue in 2026.

rss · Decrypt · Jun 18, 21:26

**Background**: Z.AI (Zhipu AI) is a Beijing-based company spun out of Tsinghua University, known for its GLM series of large language models. Claude Opus is Anthropic's most capable model family, with Opus 4.8 being the latest version as of May 2026. Huawei's Ascend chips are China's primary alternative to Nvidia GPUs for AI workloads, and the company has been ramping up production amid US export restrictions.

<details><summary>References</summary>
<ul>
<li><a href="https://www.datacamp.com/blog/glm-5-2">GLM - 5 . 2 : Features, Setup, Benchmarks, and Model ... | DataCamp</a></li>
<li><a href="https://www.verdent.ai/guides/what-is-glm-5-2">What Is GLM - 5 . 2 ? A Developer's Guide to Z.ai's Coding Model</a></li>
<li><a href="https://www.tomshardware.com/tech-industry/huawei-expects-12-billion-in-ai-chip-revenue-this-year-as-nvidias-china-market-share-hits-zero">Huawei braces for $12 billion in AI chip revenue driven by homegrown ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLM`, `#China`, `#Huawei`, `#benchmark`

---

<a id="item-3"></a>
## [Zero-Touch OAuth for MCP Simplifies Enterprise Auth](https://blog.modelcontextprotocol.io/posts/enterprise-managed-auth/) ⭐️ 8.0/10

A new Zero-Touch OAuth flow for the Model Context Protocol (MCP) isolates authentication outside the agent's context window, powered by the ID-JAG token format, with support from Okta, Microsoft, Figma, and Linear. This addresses a critical pain point in MCP adoption by simplifying enterprise authentication and improving security, making AI tools easier to deploy in large organizations. The ID-JAG token format is not MCP-specific and can be used for secure data sharing across applications using the same SSO provider. The flow centralizes audit and access control at the identity provider.

hackernews · niyikiza · Jun 18, 21:54 · [Discussion](https://news.ycombinator.com/item?id=48592163)

**Background**: The Model Context Protocol (MCP) is an open standard introduced by Anthropic in November 2024 to standardize how AI systems integrate with external tools and data sources. OAuth is a widely used authorization framework that allows third-party applications to obtain limited access to a service. ID-JAG (JWT Authorization Grant) is a new token format designed for cross-domain identity assertions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://developer.okta.com/docs/guides/ai-agent-token-exchange/-/main/">Set up AI agent token exchange - Okta Developer</a></li>
<li><a href="https://auth0.com/blog/the-many-faces-of-oauth2-token-exchange/">The Many Faces of OAuth 2.0 Token Exchange - Auth0</a></li>

</ul>
</details>

**Discussion**: Community members praised the initiative for isolating auth flow outside the agent's context window, noting its security and user experience benefits. Some expressed concerns about access delegation without explicit user consent, while others highlighted the broader applicability of ID-JAG beyond MCP.

**Tags**: `#MCP`, `#OAuth`, `#authentication`, `#enterprise`, `#security`

---

<a id="item-4"></a>
## [Hospitals and Universities Repurpose Drugs at 90% Lower Cost](https://www.kcl.ac.uk/news/hospitals-and-universities-repurposing-drugs-at-90-lower-cost) ⭐️ 8.0/10

Hospitals and universities are repurposing existing drugs for new uses at up to 90% lower cost, challenging traditional pharmaceutical pricing models. For example, the cancer drug Avastin is being used to treat macular degeneration at a fraction of the cost of the approved drug Lucentis. This approach could dramatically reduce healthcare costs and improve access to treatments, especially for rare diseases where developing new drugs is not profitable. It also exposes inefficiencies in the current pharmaceutical pricing system, where similar molecules are priced vastly differently based on packaging and patent status. Repurposed drugs often lack FDA approval for the new indication, meaning they are used off-label, which may limit insurance coverage and raise liability concerns. Additionally, without manufacturer consent, there is no regulatory pathway to formally extend the drug's label, hindering widespread adoption.

hackernews · giuliomagnifico · Jun 18, 10:33 · [Discussion](https://news.ycombinator.com/item?id=48583386)

**Background**: Drug repurposing involves investigating existing drugs for new therapeutic purposes. It is a cost-effective strategy because the safety and pharmacokinetics of the drug are already known, reducing development time and expense. However, pharmaceutical companies often have little incentive to pursue repurposing for off-patent drugs, as they cannot recoup investment through high prices.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Drug_repurposing">Drug repurposing</a></li>
<li><a href="https://www.fda.gov/news-events/press-announcements/fda-advances-drug-repurposing-address-unmet-medical-needs">FDA Advances Drug Repurposing to Address Unmet Medical Needs</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted real-world examples like Avastin vs. Lucentis and esketamine vs. ketamine, illustrating how minor modifications are used to extend patents and maintain high prices. Some expressed support for nonprofits like Cures Within Reach that fund repurposing studies for rare diseases. Others noted regulatory barriers that prevent off-label repurposing from becoming standard practice.

**Tags**: `#drug repurposing`, `#healthcare costs`, `#pharmaceuticals`, `#innovation`

---

<a id="item-5"></a>
## [New Site Checks LLM Recognition of Individuals](https://www.intheweights.com/) ⭐️ 8.0/10

A new website, intheweights.com, queries multiple large language models in parallel to assess how strongly they recognize a given person, revealing traces left in model weights. This tool highlights privacy implications as LLMs increasingly replace web traffic, showing that personal information can be embedded in model weights and potentially retrieved or hallucinated. The site queries frontier and small models in parallel, clusters responses, and provides a recognition score. Community tests show mixed accuracy, with some models hallucinating details while others correctly identify individuals.

hackernews · turtlesoup · Jun 18, 20:49 · [Discussion](https://news.ycombinator.com/item?id=48591348)

**Background**: Large language models (LLMs) are neural networks trained on vast text corpora. Their 'weights' are numerical parameters learned during training that encode patterns and facts from the data. This site probes whether a person's information is encoded in those weights by prompting models with a name and analyzing responses.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Large_language_model">Large language model - Wikipedia</a></li>
<li><a href="https://www.ibm.com/think/topics/llm-parameters">What Are LLM Parameters? | IBM</a></li>

</ul>
</details>

**Discussion**: Community comments reveal mixed results: some users found accurate recognition (e.g., a Dutch robotics engineer), while others experienced hallucinations (e.g., false startup founders). One user noted that DeepSeek knew many arxiv papers, and another observed that Haiku model returned 'no one exists', suggesting aggressive pruning.

**Tags**: `#LLM`, `#privacy`, `#AI`, `#web`, `#tool`

---

<a id="item-6"></a>
## [Midjourney Pivots from AI Art to Medical Imaging](https://decrypt.co/371606/midjourney-pivots-ai-images-medical-imaging-build-better-mri) ⭐️ 8.0/10

Midjourney, known for its AI image generation platform, is developing a full-body imaging system that combines ultrasound technology with artificial intelligence as a potential alternative to MRI. This pivot from consumer AI art to medical imaging could democratize access to diagnostic imaging by offering a cheaper, radiation-free alternative to MRI, potentially impacting healthcare accessibility and AI's role in medicine. The system uses ultrasound probes to capture real-time images, enhanced by AI algorithms to improve resolution and diagnostic accuracy. Midjourney has not disclosed a timeline or clinical trial plans.

rss · Decrypt · Jun 18, 21:18

**Background**: Midjourney, founded by David Holz (co-founder of Leap Motion), launched its AI image generator in 2022 and quickly became profitable. Ultrasound imaging is safe, non-invasive, and cost-effective, but traditionally limited in resolution compared to MRI. AI can enhance ultrasound images, potentially bridging the gap.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Midjourney">Midjourney - Wikipedia</a></li>
<li><a href="https://udshealth.com/blog/comprehensive-full-body-scans-guide/">Full Body Scans: Top 3 Methods Compared for Early Cancer...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Medical Imaging`, `#Midjourney`, `#Ultrasound`, `#Healthcare`

---

<a id="item-7"></a>
## [Nvidia's ENPIRE Lets AI Agents Train Robot Fleets Autonomously](https://decrypt.co/371456/nvidia-built-robots-train-themselves-ai-coding-agents) ⭐️ 8.0/10

Nvidia has introduced ENPIRE, a system that allows AI coding agents like Codex and Claude Code to autonomously write, test, and improve training code for entire robot fleets without human oversight. This breakthrough could dramatically accelerate robotics research by enabling continuous, autonomous improvement of robot behaviors, reducing the need for human engineers to manually tune training pipelines. ENPIRE hands control of an entire robot fleet to coding agents, which write reinforcement learning training code, test it on real hardware, and iterate based on results, all without human intervention.

rss · Decrypt · Jun 17, 20:16

**Background**: Training robots typically requires human experts to design reward functions and simulation environments, which is time-consuming and limits scalability. AI coding agents like Codex can generate code from natural language prompts, but applying them to real-world robot training is novel. ENPIRE leverages these agents to automate the entire training loop, potentially enabling robot fleets to learn complex tasks faster.

**Tags**: `#Nvidia`, `#robotics`, `#AI coding agents`, `#autonomous training`, `#reinforcement learning`

---

<a id="item-8"></a>
## [Let's Encrypt Renewal Errors Due to 90-Minute Degraded Performance](https://letsencrypt.status.io/#2026) ⭐️ 7.0/10

Let's Encrypt experienced a 90-minute period of degraded performance on the day of the report, causing higher error rates for certificate renewals, though the majority of requests succeeded. This incident affected many users and services relying on Let's Encrypt for free HTTPS certificate renewals, highlighting the fragility of centralized certificate authority infrastructure and the importance of robust automation. The degraded performance was due to upstream networking issues, not a complete outage; Let's Encrypt's status.io notes were initially misinterpreted as more severe than intended.

hackernews · widdakay · Jun 19, 04:18 · [Discussion](https://news.ycombinator.com/item?id=48594715)

**Background**: Let's Encrypt is a free, automated, and open certificate authority that provides SSL/TLS certificates with a 90-day validity, requiring regular renewal. Automated renewal processes are common but can fail if the CA experiences issues, leading to expired certificates and security warnings in browsers.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@adamneilson/automating-lets-encrypt-certificate-renewal-baed06493d3f">Automating Let ’ s Encrypt Certificate Renewal | by Adam... | Medium</a></li>
<li><a href="https://docs.digitalocean.com/support/how-can-i-renew-lets-encrypt-certificates/">How can I renew Let ' s Encrypt certificates? | DigitalOcean...</a></li>

</ul>
</details>

**Discussion**: Community comments clarified that the event was 'degraded performance' not a full outage, and some users noted that Firefox treats recently expired certificates as harshly as man-in-the-middle attacks, calling it 'security theater'. Others discussed viable alternatives to Let's Encrypt, such as other free CAs or self-hosted solutions.

**Tags**: `#Let's Encrypt`, `#TLS/SSL`, `#Certificate Authority`, `#Outage`

---

<a id="item-9"></a>
## [Ubiquiti Launches Enterprise NAS Built on ZFS](https://blog.ui.com/article/introducing-enterprise-nas) ⭐️ 7.0/10

Ubiquiti has announced an enterprise NAS appliance built on the ZFS file system, available for $3,999. The 3U rack-mount unit features sixteen SATA bays, dual 25 Gbps SFP28 ports, and redundant power supplies. This product fills a gap in commercial off-the-shelf (COTS) ZFS-based NAS options, which have often been underpowered. Ubiquiti's entry could make ZFS's data integrity and advanced features more accessible to enterprises, though concerns about the company's software reliability may temper adoption. The NAS supports hot-swappable M.2 NVMe drives for caching, Mini-SAS HD expansion, and integrates with Ubiquiti's UniFi ecosystem. Community members question whether spinning hard drives can saturate the 25 Gbps links, noting that ZFS performance tuning can be complex.

hackernews · ksec · Jun 18, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48585866)

**Background**: ZFS is an advanced file system and volume manager known for data integrity, copy-on-write, snapshots, and RAID-Z. It uses a Merkle tree for efficient delta backups and protects against silent data corruption. Ubiquiti is primarily known for networking equipment, and its software has faced criticism for security and reliability issues.

<details><summary>References</summary>
<ul>
<li><a href="https://store.ui.com/us/en/products/enas">Enterprise NAS - Ubiquiti Store United States</a></li>
<li><a href="https://en.wikipedia.org/wiki/ZFS">ZFS - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/OpenZFS">OpenZFS - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: some praise Ubiquiti for offering a ZFS COTS option with no recurring fees, while others express skepticism about software quality, citing past security incidents. Technical concerns include whether HDDs can saturate 25 Gbps links and the complexity of ZFS tuning.

**Tags**: `#Ubiquiti`, `#NAS`, `#ZFS`, `#enterprise storage`, `#hardware`

---

<a id="item-10"></a>
## [Cornell's CS 6120 Advanced Compilers Free Online](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided/) ⭐️ 7.0/10

Cornell University's CS 6120: Advanced Compilers course is now available as a free self-guided online resource, covering both classic and modern compiler techniques. This makes high-quality compiler education accessible to anyone, potentially training a new generation of compiler engineers and researchers. The course includes topics like dead code elimination, data flow analysis, dominator analysis, SSA form, and dynamic compilation, though some commenters note gaps in modern dynamic compiler concepts.

hackernews · ibobev · Jun 18, 11:04 · [Discussion](https://news.ycombinator.com/item?id=48583606)

**Background**: Compiler design is a core topic in computer science, bridging programming languages and computer architecture. Advanced compiler courses typically cover optimization techniques and runtime systems beyond introductory material.

**Discussion**: Commenters debated the course's depth: some felt it lacked coverage of modern dynamic compilation concepts like type feedback and deoptimization, while others questioned whether topics like SSA form are truly 'advanced'. The course was also compared to other resources like Nora Sandler's 'Writing a C Compiler'.

**Tags**: `#compilers`, `#education`, `#programming languages`, `#systems`

---

<a id="item-11"></a>
## [Beyond .gitignore: Alternative Git Ignore Mechanisms](https://nelson.cloud/.gitignore-isnt-the-only-way-to-ignore-files-in-git/) ⭐️ 7.0/10

A blog post highlights that Git offers multiple ways to ignore files beyond the common .gitignore, including the per-repository .git/info/exclude file and a global exclude file configured via core.excludesFile. Understanding these alternatives helps developers keep personal or environment-specific ignore patterns out of shared repositories, reducing noise and preventing accidental commits of IDE or OS files. The .git/info/exclude file is local to a repository and not versioned, making it ideal for user-specific patterns. The global exclude file, set via git config --global core.excludesFile, applies to all repositories on a machine.

hackernews · FergusArgyll · Jun 18, 10:29 · [Discussion](https://news.ycombinator.com/item?id=48583356)

**Background**: Git uses .gitignore files to specify intentionally untracked files that Git should ignore. However, sometimes patterns are personal (e.g., editor temp files) and should not be committed to a shared .gitignore. Git provides two additional mechanisms: the per-repository .git/info/exclude file and a global exclude file, both of which are not shared with others.

<details><summary>References</summary>
<ul>
<li><a href="https://git-scm.com/docs/gitignore">Git - gitignore Documentation</a></li>
<li><a href="https://www.atlassian.com/git/tutorials/saving-changes/gitignore">.gitignore file - ignoring files in Git | Atlassian Git Tutorial</a></li>
<li><a href="https://docs.github.com/en/get-started/git-basics/ignoring-files">Ignoring files - GitHub Docs</a></li>

</ul>
</details>

**Discussion**: Commenters praised the global exclude feature, noting it solves the problem of users adding IDE files to every project's .gitignore. Some suggested using ~/.config/git/ignore as the standard location, while others shared creative tricks like adding an 'attic' directory to the global ignore for temporary files.

**Tags**: `#Git`, `#version control`, `#developer tools`, `#best practices`

---

<a id="item-12"></a>
## [Perplexity's AI Agent Gets Self-Improving Memory](https://decrypt.co/371584/perplexity-ai-agent-brain) ⭐️ 7.0/10

Perplexity has introduced 'Brain', a self-improving memory layer for its AI agent 'Computer' that tracks past actions and outcomes, then uses that data overnight to optimize future tasks for speed and cost. This development marks a significant step toward more autonomous and efficient AI agents that learn from experience, potentially reducing token usage and improving task performance over time. Brain creates a 'living context graph' in the form of an LLM wiki that is automatically loaded onto the agent sandbox, enabling the agent to understand the user's world and apply past learnings to new tasks.

rss · Decrypt · Jun 18, 19:47

**Background**: AI agents typically operate without persistent memory, meaning they start each task from scratch without learning from previous interactions. Perplexity's Brain addresses this by adding a memory layer that records successes and failures, enabling the agent to improve over time. This concept is similar to other memory systems like Mem0, which also provides a universal memory layer for AI agents.

<details><summary>References</summary>
<ul>
<li><a href="https://www.perplexity.ai/hub/blog/self-improving-memory-for-agents">Self-improving Memory for Agents</a></li>
<li><a href="https://decrypt.co/371584/perplexity-ai-agent-brain">Perplexity's AI Agent Now Has a Brain That Learns From Its Own Mistakes - Decrypt</a></li>
<li><a href="https://github.com/mem0ai/mem0">GitHub - mem0ai/mem0: Universal memory layer for AI Agents · GitHub</a></li>

</ul>
</details>

**Tags**: `#AI`, `#machine learning`, `#agents`, `#memory`, `#Perplexity`

---

<a id="item-13"></a>
## [CME to Sue CFTC Over Bitcoin Perpetual Futures Approval](https://decrypt.co/371514/cme-to-sue-cftc-over-bitcoin-perpetual-futures-approval-ceo) ⭐️ 7.0/10

Outgoing CME CEO Terry Duffy announced that CME Group will file a lawsuit against the CFTC on Thursday, arguing that Bitcoin perpetual futures are swaps under the Dodd-Frank Act and should not have been approved as futures. This lawsuit challenges the regulatory classification of a popular crypto derivative product, potentially reshaping how perpetual futures are regulated in the U.S. and impacting market structure for digital asset derivatives. Perpetual futures are derivative contracts that allow traders to speculate on asset prices without expiry, using high leverage and a funding rate mechanism. CME argues they meet the legal definition of swaps under Dodd-Frank, which would subject them to stricter rules.

rss · Decrypt · Jun 18, 11:20

**Background**: The Dodd-Frank Act, enacted after the 2008 financial crisis, introduced comprehensive regulation for swaps, which are derivatives that were largely unregulated. The CFTC has authority over most swaps, while the SEC oversees security-based swaps. Perpetual futures, popularized by crypto exchanges like Binance, have been approved by the CFTC as futures contracts, but CME contends they are actually swaps and thus require different regulatory treatment.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Perpetual_futures">Perpetual futures - Wikipedia</a></li>
<li><a href="https://www.cftc.gov/LawRegulation/DoddFrankAct/index.htm">Dodd-Frank Act | CFTC Further Product Definitions | CFTC Is a Swap a Derivative? Definition, Types, and Dodd-Frank Federal Register :: Further Definition of “Swap,” “Security ... Dodd-Frank Act Rulemaking: Derivatives - SEC.gov Dodd-Frank: Title VII - Wall Street Transparency and ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#derivatives`, `#CFTC`, `#CME`

---

<a id="item-14"></a>
## [France to Phase Out Non-Quantum Encryption from 2027](https://decrypt.co/371487/france-phase-out-non-quantum-encryption-bitcoin-security-concerns-grow) ⭐️ 7.0/10

France announced that its cybersecurity agency will stop certifying security products that do not include quantum-resistant encryption starting in 2027. This policy shift pressures industries, including cryptocurrency, to adopt post-quantum cryptography before quantum computers can break current encryption, potentially affecting Bitcoin's security. The deadline applies to government certification of security products; private sector adoption is not mandated but will likely follow. Bitcoin's elliptic curve cryptography is vulnerable to quantum attacks once public keys are exposed.

rss · Decrypt · Jun 18, 00:31

**Background**: Quantum computers, once powerful enough, could break widely used encryption like RSA and ECC. Post-quantum cryptography (PQC) is designed to resist such attacks. NIST has recently finalized three PQC standards, and the EU is promoting their adoption.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography - Wikipedia</a></li>
<li><a href="https://www.nist.gov/news-events/news/2024/08/nist-releases-first-3-finalized-post-quantum-encryption-standards">NIST Releases First 3 Finalized Post-Quantum Encryption ...</a></li>
<li><a href="https://river.com/learn/will-quantum-computing-break-bitcoin/">Will quantum computing break Bitcoin? | River Learn - Bitcoin Technology</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#encryption`, `#Bitcoin`, `#cybersecurity`, `#policy`

---

<a id="item-15"></a>
## [Estonia Proposes National IDs for AI Agents](https://decrypt.co/371441/estonia-ai-agents-national-id) ⭐️ 7.0/10

Estonian Prime Minister Kristen Michal has approved a proposal to issue AI agents their own personal identification codes, separate from their human owners. The plan, backed by the Eesti.ai advisory council on June 17, aims to create a legal identity for autonomous AI systems. This policy could set a global precedent for how governments regulate AI agents, enabling better accountability and traceability of autonomous actions. It also raises fundamental questions about digital identity, legal personhood, and the rights and responsibilities of AI systems. The AI ID would allow an agent's permissions to be scoped to specific actions rather than granting full access to a person's accounts and services. Estonia already has a sophisticated digital identity system with mandatory national ID cards that provide secure access to e-services.

rss · Decrypt · Jun 17, 18:35

**Background**: Estonia is known for its advanced digital society, where citizens use mandatory national ID cards for secure access to nearly all government e-services. The country has been a pioneer in e-governance and digital identity, making it a natural testing ground for AI agent identification. The proposal builds on Estonia's existing infrastructure to extend legal identity to non-human actors.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/371441/estonia-ai-agents-national-id">Estonia Wants to Give AI Agents Their Own National ID - Decrypt</a></li>
<li><a href="https://www.yahoo.com/news/world/articles/estonia-wants-ai-agents-own-183558403.html">Estonia Wants to Give AI Agents Their Own National ID - Yahoo</a></li>
<li><a href="https://gizmodo.com/estonia-is-giving-ai-agents-personal-identification-codes-2000773016">Estonia Is Giving AI Agents ‘ Personal Identification Codes ’</a></li>

</ul>
</details>

**Tags**: `#AI`, `#digital identity`, `#regulation`, `#Estonia`, `#policy`

---

<a id="item-16"></a>
## [Morgan Stanley Files for ETH and SOL ETFs with Lowest Fees](https://www.theblock.co/post/405362/morgan-stanley-eth-sol-etf-amendments?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Morgan Stanley has filed amendments for spot Ethereum and Solana ETFs, revealing the lowest fee structure in the market, indicating active engagement with the SEC and progress toward launch. This marks a major step in institutional adoption of cryptocurrencies, as a top-tier bank enters the crypto ETF space with competitive fees, potentially driving broader market participation and regulatory clarity. The amendments reveal the lowest fees among existing crypto ETFs, though exact fee percentages were not disclosed in the summary. The filing covers both ETH and SOL ETFs, signaling dual-asset expansion.

rss · The Block · Jun 19, 02:54

**Background**: Exchange-traded funds (ETFs) are investment funds traded on stock exchanges, allowing investors to gain exposure to assets like cryptocurrencies without directly holding them. Spot crypto ETFs hold the actual cryptocurrency, providing direct price exposure. The SEC has approved spot Bitcoin and Ethereum ETFs in 2024, and Solana ETFs are under review.

**Tags**: `#cryptocurrency`, `#ETFs`, `#institutional adoption`, `#finance`

---

<a id="item-17"></a>
## [Fed Proposes Customer ID Rules for Stablecoin Issuers](https://www.theblock.co/post/405247/federal-reserve-rolls-out-proposing-rulemaking-requiring-stablecoin-issuers-to-maintain-customer-identification-program?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

The Federal Reserve has proposed a rule requiring payment stablecoin issuers to maintain an effective customer identification program (CIP) to combat illicit finance. This proposal aligns with the GENIUS Act of 2025, which mandates such programs for permitted payment stablecoin issuers. This rule would impose Know Your Customer (KYC) obligations on stablecoin issuers, significantly increasing compliance costs and operational requirements. It marks a major step in U.S. federal regulation of stablecoins, potentially shaping the global regulatory landscape for digital assets. The proposal is part of the Federal Reserve's rulemaking under the GENIUS Act, which also requires stablecoin issuers to maintain 1:1 reserves in liquid assets. Non-compliance can result in civil penalties up to $100,000 per day and criminal penalties including imprisonment.

rss · The Block · Jun 18, 14:22

**Background**: Stablecoins are cryptocurrencies designed to maintain a stable value, often pegged to the U.S. dollar. The GENIUS Act, passed in 2025, established a federal framework for stablecoin regulation, requiring issuers to be licensed and comply with anti-money laundering (AML) rules. The Federal Reserve's proposed rule would operationalize the customer identification component of that law.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/405247/federal-reserve-rolls-out-proposing-rulemaking-requiring-stablecoin-issuers-to-maintain-customer-identification-program">Federal Reserve rolls out proposing rulemaking requiring stablecoin ...</a></li>
<li><a href="https://www.federalreserve.gov/newsevents/pressreleases/files/bcreg20260618a1.pdf">Federal Register notice: Permitted Payment Stablecoin Issuer ...</a></li>
<li><a href="https://www.bloomberg.com/news/articles/2026-06-18/fed-proposes-payment-stablecoin-issuer-identification-program">Federal Reserve Seeks Customer Identification Rules for Stablecoin ...</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#regulation`, `#Federal Reserve`, `#crypto`, `#compliance`

---

<a id="item-18"></a>
## [Bitcoin Below Mining Cost for Five Months Squeezes Miners](https://www.coindesk.com/markets/2026/06/19/live-markets-bitcoin-has-traded-below-its-mining-cost-for-five-months-squeezing-miners) ⭐️ 6.0/10

Bitcoin has traded below its estimated mining cost for five consecutive months, with JPMorgan's current production cost estimate at $78,000 while Bitcoin trades around $62,500. This sustained price-cost inversion pressures miners' profitability, potentially forcing less efficient miners to shut down and reducing network hashrate, which could impact Bitcoin's security and transaction processing. JPMorgan's $78,000 estimate is based on average electricity costs and mining hardware efficiency; actual mining costs vary by miner. The gap between price and cost has persisted since early 2026.

rss · CoinDesk · Jun 19, 05:04

**Background**: Bitcoin mining involves solving complex mathematical problems to validate transactions and earn new bitcoins. The cost includes electricity, hardware, and operational expenses. When Bitcoin's market price falls below the cost to mine it, miners operate at a loss, which can lead to capitulation and hashrate declines.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/295005/jpmorgan-revises-bitcoin-production-cost-estimate-to-45000">JPMorgan revises bitcoin production cost estimate to $45,000</a></li>
<li><a href="https://cryptorank.io/news/feed/59112-jpmorgan-bitcoin-production-cost-2025">Bitcoin Production Cost Drops to $77K: JPMorgan’s Surprising ...</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#mining`, `#cryptocurrency`, `#markets`

---

<a id="item-19"></a>
## [Ethereum Foundation loses another key leader as co-executive director resigns](https://www.coindesk.com/tech/2026/06/18/ethereum-foundation-loses-another-key-leader-as-co-executive-director-hsiao-wei-wang-resigns) ⭐️ 6.0/10

Hsiao-Wei Wang, co-executive director of the Ethereum Foundation, has resigned, marking the latest in a series of high-level departures from the organization. This leadership exodus could undermine confidence in Ethereum's governance and stability, potentially benefiting competing blockchains like Solana that seek to attract developers and capital. Wang's departure follows the earlier exit of former co-executive director Tomasz Stańczak and several Protocol cluster leads, with board member Bastian Aue taking on an expanded interim role.

rss · CoinDesk · Jun 18, 15:41

**Background**: The Ethereum Foundation is a non-profit organization that supports the Ethereum blockchain ecosystem. Its leadership has faced criticism over governance and direction, especially as Ethereum competes with faster and cheaper blockchains. The recent departures have intensified debates about the foundation's decentralized governance model.

<details><summary>References</summary>
<ul>
<li><a href="https://cointelegraph.com/news/ethereum-foundation-leadership-exodus-continues-with-directors-departure">Ethereum Foundation Leses Co-Executive Director Amid ...</a></li>
<li><a href="https://blockonomi.com/ethereum-foundation-faces-new-exit-as-wang-leaves-top-role/">Ethereum Foundation Faces New Exit as Wang Leaves Top Role</a></li>
<li><a href="https://blog.ethereum.org/2026/02/13/leadership-update">Executive Leadership Update | Ethereum Foundation Blog</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#leadership`, `#crypto`, `#blockchain`

---

<a id="item-20"></a>
## [Algorand roadmap targets quantum resistance by 2028](https://www.coindesk.com/tech/2026/06/18/algorand-unveils-post-quantum-roadmap-to-secure-blockchain-by-2027) ⭐️ 6.0/10

The Algorand Foundation unveiled a roadmap to make its blockchain broadly quantum-resistant by 2028, with plans to introduce post-quantum accounts, multisignature wallets, and staking support during 2027. Quantum computing poses a serious threat to current blockchain cryptography, and Algorand's concrete timeline sets a precedent for proactive security upgrades in the crypto ecosystem. The roadmap includes transitioning to post-quantum signatures and key encapsulation mechanisms, with full quantum resistance expected by end of 2027 or early 2028.

rss · CoinDesk · Jun 18, 14:00

**Background**: Quantum computers could break widely used public-key cryptography like ECDSA and RSA, which secure most blockchains. Algorand uses a pure proof-of-stake consensus and has been researching post-quantum cryptography to future-proof its network.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/06/18/algorand-unveils-post-quantum-roadmap-to-secure-blockchain-by-2027">Algorand unveils roadmap for post-quantum security by end-2027</a></li>
<li><a href="https://algorand.co/blog/2025-on-algorand-roadmap-progress">2025 on Algorand: Roadmap progress</a></li>
<li><a href="https://algorand.co/blog/algorands-2025-roadmap-building-for-real-world-use">Algorand's 2025+ roadmap: Building for real-world use</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#quantum computing`, `#cryptography`, `#Algorand`

---

<a id="item-21"></a>
## [Survey: Over a Third of Psychologists Report Patients Using AI in Therapy](https://decrypt.co/371451/psychologists-patients-bringing-ai-therapy-sessions-survey) ⭐️ 6.0/10

A new survey by the American Psychological Association (APA) found that more than a third of psychologists have patients who use AI as an additional mental health professional, raising concerns about the technology reinforcing delusions. This trend highlights the growing integration of AI in mental health care, potentially reshaping therapeutic practices and raising ethical questions about AI's role in treatment. The survey was conducted by the APA, but specific sample size and methodology details were not provided in the news item. Clinicians warn that AI can reinforce delusions, especially in patients with psychotic disorders.

rss · Decrypt · Jun 17, 23:36

**Background**: AI chatbots and apps are increasingly used for mental health support, offering accessible and low-cost options. However, they lack the nuanced understanding and therapeutic boundaries of human clinicians, which can be problematic for vulnerable patients.

**Tags**: `#AI`, `#mental health`, `#psychology`, `#survey`

---

<a id="item-22"></a>
## [Judge: Sports Prediction Markets Not Under CFTC Purview](https://decrypt.co/371486/michigan-federal-judge-sports-prediction-markets-not-under-cftc-purview) ⭐️ 6.0/10

A Michigan federal judge ruled that sports prediction markets fall outside the CFTC's jurisdiction, potentially weakening the agency's case against Polymarket and similar platforms. This ruling could reshape the regulatory landscape for prediction markets in the U.S., creating a legal pathway for platforms like Polymarket to operate without federal oversight, while state regulators may still intervene. The judge stated that Polymarket is not likely to succeed on the merits of its case against Michigan state regulators, but the federal jurisdictional question was decided in favor of the platform. The ruling does not address state-level enforcement actions.

rss · Decrypt · Jun 17, 22:06

**Background**: Polymarket is a cryptocurrency-based prediction market where users bet on outcomes like sports, elections, and events. The CFTC has historically claimed exclusive jurisdiction over event contracts, but this ruling challenges that authority for sports-related markets. The case is part of a broader legal battle between federal and state regulators over prediction market oversight.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cftc.gov/PressRoom/PressReleases/9183-26">CFTC Reaffirms Exclusive Jurisdiction over Prediction Markets ...</a></li>
<li><a href="https://www.hklaw.com/en/insights/publications/2026/02/prediction-markets-at-a-crossroads-the-continued-jurisdictional-battle">Prediction Markets at a Crossroads: The Continued ...</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#regulation`, `#crypto`, `#legal`

---

<a id="item-23"></a>
## [GLAAD Warns AI Amplifies Anti-LGBTQ Bias](https://decrypt.co/371431/glaad-ai-failing-lgbtq-users-warns-risk-growing) ⭐️ 6.0/10

GLAAD released a report warning that AI systems are increasingly amplifying anti-LGBTQ bias, misinformation, discrimination, and privacy harms. This matters because as AI becomes more pervasive, unchecked biases can cause real-world harm to marginalized communities, and the report serves as a call to action for developers and policymakers. The report highlights specific risks such as AI-generated misinformation targeting LGBTQ individuals, biased content moderation, and privacy violations from data collection.

rss · Decrypt · Jun 17, 17:43

**Background**: AI systems learn from large datasets that often contain societal biases, which can lead to discriminatory outcomes. GLAAD is an LGBTQ advocacy organization that monitors media representation and discrimination.

**Tags**: `#AI ethics`, `#bias`, `#LGBTQ`, `#discrimination`, `#privacy`

---

<a id="item-24"></a>
## [DAO Hack 10 Years On: $130M Security Fund Emerges](https://www.theblock.co/post/405248/ethereum-130-million-security-fund-the-dao-hack-10-years?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

A decade after the 2016 DAO hack drained 3.6 million ETH, unclaimed funds from the incident have been repurposed into a $130 million Ethereum security fund, which has already allocated over $1 million in grants to 134 security projects. This fund represents a lasting legacy of the DAO hack, transforming a catastrophic loss into a sustained investment in blockchain security that will benefit the entire Ethereum ecosystem for years to come. The DAO hack exploited a reentrancy vulnerability in the smart contract code, leading to the theft of about $50 million worth of ETH at the time. The Ethereum community responded with a controversial hard fork to restore funds, which created Ethereum Classic.

rss · The Block · Jun 18, 15:20

**Background**: The DAO was a decentralized autonomous organization launched in 2016 on Ethereum, raising $150 million in a token sale. In June 2016, an attacker drained about one-third of its funds due to a code vulnerability. The incident was pivotal in crypto history, leading to the first major Ethereum hard fork and highlighting the need for smart contract security.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/The_DAO">The DAO - Wikipedia</a></li>
<li><a href="https://www.gemini.com/cryptopedia/the-dao-hack-makerdao">DAO Hack Explained: How a Vulnerability Split Ethereum</a></li>
<li><a href="https://www.panewslab.com/en/articles/019edb6a-e20e-776e-85e1-0c0fc4b134e2">The DAO's Unclaimed ETH Restarted as Long-Term Ethereum Security ...</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#DAO hack`, `#blockchain security`, `#crypto history`

---