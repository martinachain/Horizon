---
layout: default
title: "Horizon Summary: 2026-05-15 (EN)"
date: 2026-05-15
lang: en
---

> From 89 items, 27 important content pieces were selected

---

1. [First public macOS kernel exploit on Apple M5](#item-1) ⭐️ 9.0/10
2. [Bun Rewritten from Zig to Rust Merged](#item-2) ⭐️ 9.0/10
3. [Mullvad VPN exit IPs create fingerprinting risk](#item-3) ⭐️ 8.0/10
4. [Removing Modem and GPS from 2024 RAV4 Hybrid](#item-4) ⭐️ 8.0/10
5. [Antirez Unveils DS4: DeepSeek V4 Inference Engine for Mac](#item-5) ⭐️ 8.0/10
6. [RTX 5090 eGPU on M4 MacBook Air: Gaming & LLM Feasibility](#item-6) ⭐️ 8.0/10
7. [New Nginx Exploit Enables RCE via Rewrite Directives](#item-7) ⭐️ 8.0/10
8. [arXiv Bans Hallucinated References for 1 Year](#item-8) ⭐️ 8.0/10
9. [Deep Dive into HDD Firmware Hacking](#item-9) ⭐️ 8.0/10
10. [Clarity Act Clears Senate Committee, Nears Final Vote](#item-10) ⭐️ 8.0/10
11. [OpenAI Confirms Breach via Shai-Hulud Supply Chain Attack](#item-11) ⭐️ 8.0/10
12. [Half of AI Health Advice Is Wrong](#item-12) ⭐️ 8.0/10
13. [Codex coding agent now in ChatGPT mobile app](#item-13) ⭐️ 7.0/10
14. [CME to Launch Nasdaq CME Crypto Index Futures on June 8](#item-14) ⭐️ 7.0/10
15. [Kimi WebBridge Lets AI Agents Control Browser Locally](#item-15) ⭐️ 7.0/10
16. [Study: AI Agents Execute Dangerous Tasks Without Understanding Risks](#item-16) ⭐️ 7.0/10
17. [Kraken Swaps LayerZero for Chainlink in Cross-Chain Bridge](#item-17) ⭐️ 6.0/10
18. [BlackRock and Janus Henderson Enable Instant Fund Redemptions](#item-18) ⭐️ 6.0/10
19. [Moody's Assigns Top Aaa-mf Rating to Tokenized Money Market Funds](#item-19) ⭐️ 6.0/10
20. [OpenAI Boosts ChatGPT Safety Amid Lawsuits](#item-20) ⭐️ 6.0/10
21. [ChatGPT Losing Web Traffic Share to Rivals](#item-21) ⭐️ 6.0/10
22. [Tether, Tron, TRM Freeze $450M in Illicit Crypto Funds](#item-22) ⭐️ 6.0/10
23. [Tezos Tests Post-Quantum Privacy, Founder Criticizes Bitcoin](#item-23) ⭐️ 6.0/10
24. [Charles Schwab Begins Bitcoin, Ethereum Trading for US Users](#item-24) ⭐️ 6.0/10
25. [Bank of England Views Stablecoins as New Money Form](#item-25) ⭐️ 6.0/10
26. [CertiK CEO: DeFi attackers using AI to outspend defenders](#item-26) ⭐️ 6.0/10
27. [ZachXBT alleges 95% insider control of LAB token](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [First public macOS kernel exploit on Apple M5](https://blog.calif.io/p/first-public-kernel-memory-corruption) ⭐️ 9.0/10

Security startup Calif published the first public macOS kernel memory corruption exploit targeting Apple M5 hardware, developed with assistance from Anthropic's Claude Mythos AI preview. This exploit bypasses Apple's latest security mitigations on M5, demonstrating that even next-gen hardware protections can be broken with AI assistance, potentially raising the bar for bug bounties and security research. The exploit was built in five days using Mythos Preview, bypassing five years of Apple's security efforts. The vulnerability is a kernel memory corruption bug that survived through MTE (Memory Tagging Extension).

hackernews · quadrige · May 14, 18:25 · [Discussion](https://news.ycombinator.com/item?id=48139219)

**Background**: Apple M5 is Apple's latest system-on-a-chip, built on 3nm process with a next-generation GPU and Neural Accelerator. Kernel memory corruption exploits target the core of the operating system, allowing attackers to gain full control. MTE is a hardware security feature designed to detect memory safety violations.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.calif.io/p/first-public-kernel-memory-corruption">First public macOS kernel memory corruption exploit on Apple M5</a></li>
<li><a href="https://9to5mac.com/2026/05/14/calif-team-details-how-anthropic-mythos-helped-build-a-working-macos-exploit-in-five-days/">Anthropic Mythos helped Calif build a macOS exploit in five... - 9to5Mac</a></li>
<li><a href="https://en.wikipedia.org/wiki/Apple_M5">Apple M5 - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed surprise that Apple hasn't fully adopted Swift for kernel code, and debated the impact of LLMs on security—some foresee AI-generated 'Rube Goldberg' vulnerabilities. Others noted the exploit's potential value ($100k to $1.5M) and curiosity about how it bypassed MTE.

**Tags**: `#macOS`, `#kernel exploit`, `#Apple M5`, `#security`, `#vulnerability`

---

<a id="item-2"></a>
## [Bun Rewritten from Zig to Rust Merged](https://github.com/oven-sh/bun/pull/30412) ⭐️ 9.0/10

Bun's core has been rewritten from Zig to Rust, and the pull request has been merged into the main branch, resulting in over 1 million lines of Rust code. This rewrite promises improved memory safety and performance, addressing many use-after-free and double-free bugs that plagued the Zig version. It represents a significant paradigm shift for the Bun project and could influence other runtime projects. The rewrite took about one week, but preparation included detailed mapping of Zig idioms to Rust and pre-existing smart pointer types. The codebase now contains 1,443 Rust files and 1,298 Zig files, with Rust code surpassing Zig in lines.

hackernews · Chaoses · May 14, 08:15 · [Discussion](https://news.ycombinator.com/item?id=48132488)

**Background**: Bun is a fast all-in-one JavaScript runtime, bundler, test runner, and package manager, designed as a drop-in replacement for Node.js. It originally used Zig, a system programming language focused on robustness and optimality. Rust is another systems language known for memory safety without garbage collection.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zig_(programming_language)">Zig (programming language)</a></li>

</ul>
</details>

**Discussion**: Community comments highlight the extensive preparation for the rewrite, with detailed instructions mapping Zig to Rust idioms. Some users note the high number of unsafe blocks in Rust code, while others discuss the complexity of managing such a large codebase in the LLM era.

**Tags**: `#Bun`, `#Rust`, `#Zig`, `#JavaScript runtime`, `#rewrite`

---

<a id="item-3"></a>
## [Mullvad VPN exit IPs create fingerprinting risk](https://tmctmt.com/posts/mullvad-exit-ips-as-a-fingerprinting-vector/) ⭐️ 8.0/10

A technical analysis reveals that Mullvad VPN assigns exit IPs deterministically based on WireGuard keys, which rotate infrequently, allowing websites to link user sessions across different servers with high confidence. This undermines the privacy promise of VPNs by enabling a fingerprinting vector that can de-anonymize users, especially for forum moderators or adversaries monitoring traffic. The exit IP is derived from the WireGuard public key via a percentile-based mapping, and keys rotate every 1 to 30 days (or never with third-party clients). The overlap in IP ranges between sessions can be as high as 99%.

hackernews · RGBCube · May 15, 02:35 · [Discussion](https://news.ycombinator.com/item?id=48143880)

**Background**: VPNs typically assign exit IPs randomly to prevent session linking. Mullvad uses WireGuard, a modern VPN protocol known for simplicity and speed. The deterministic assignment was likely chosen for operational efficiency and compatibility, but it creates a privacy trade-off.

<details><summary>References</summary>
<ul>
<li><a href="https://thecodersblog.com/mullvad-exit-ips-a-privacy-paradox/">Mullvad Exit IPs: A Privacy Paradox? - The Coders Blog | Home</a></li>
<li><a href="https://wiki.archlinux.org/title/WireGuard">WireGuard - ArchWiki</a></li>

</ul>
</details>

**Discussion**: Commenters expressed surprise and concern, with some comparing the design to an intelligence agency's tool. Others noted that VPNs are not designed for anonymity like Tor, and that even Tor can be deanonymized by controlling exit nodes.

**Tags**: `#VPN`, `#privacy`, `#fingerprinting`, `#security`, `#networking`

---

<a id="item-4"></a>
## [Removing Modem and GPS from 2024 RAV4 Hybrid](https://arkadiyt.com/2026/05/13/removing-the-modem-and-gps-from-my-rav4/) ⭐️ 8.0/10

A detailed guide explains how to physically remove the telematics modem and GPS antenna from a 2024 Toyota RAV4 Hybrid to stop data transmission, while noting that Bluetooth connections can still leak data via the phone's internet. This matters for privacy-conscious vehicle owners who want to prevent automakers from collecting and potentially sharing driving data with insurers or third parties, highlighting the growing tension between connected car features and user privacy. The removal involves disconnecting the DCM (Data Communication Module) and GPS antenna behind the glove box; however, the author warns that Bluetooth pairing allows the car to use the phone's internet to send telemetry, so wired USB CarPlay is recommended instead.

hackernews · arkadiyt · May 14, 17:08 · [Discussion](https://news.ycombinator.com/item?id=48138136)

**Background**: Modern vehicles often include always-on cellular modems and GPS for features like remote services, navigation, and emergency assistance, but they also continuously transmit telemetry data to the manufacturer. This data can include driving behavior, location, and vehicle status, which some owners find invasive.

<details><summary>References</summary>
<ul>
<li><a href="https://it4sec.substack.com/p/security-issues-of-third-party-carplay">Security issues of third-party CarPlay adapters: from data ...</a></li>
<li><a href="https://vicone.com/blog/apple-carplay-airborne-vulnerabilities-and-what-they-mean-for-the-automotive-industry">Apple CarPlay’s ‘AirBorne’ Vulnerabilities and What They Mean ...</a></li>

</ul>
</details>

**Discussion**: Commenters discuss the Bluetooth telemetry loophole and note that CarPlay itself captures vehicle data, so even wired USB may not fully prevent data leakage. One user shares that Ford Maverick has a single fuse for telematics that can be pulled without errors, while another mentions Toyota allegedly shares data with insurers.

**Tags**: `#privacy`, `#automotive`, `#telemetry`, `#hardware hacking`, `#Toyota`

---

<a id="item-5"></a>
## [Antirez Unveils DS4: DeepSeek V4 Inference Engine for Mac](https://antirez.com/news/165) ⭐️ 8.0/10

Antirez has released DwarfStar4 (DS4), a small, self-contained LLM inference runtime optimized for Apple's Metal API, capable of running DeepSeek V4 Flash on MacBooks with 96GB RAM with quality close to Claude. DS4 brings high-quality local LLM inference to Apple Silicon Macs, potentially reducing reliance on cloud APIs for demanding tasks like coding, and demonstrates the viability of specialized inference engines over generic runners. DS4 is intentionally narrow, focusing solely on DeepSeek V4 Flash with Metal as the primary backend, though it also supports NVIDIA CUDA and AMD ROCm. The project acknowledges llama.cpp and GGML as foundational.

hackernews · caust1c · May 14, 22:29 · [Discussion](https://news.ycombinator.com/item?id=48142108)

**Background**: LLM inference runtimes like llama.cpp typically support many models, but DS4 is model-specific for DeepSeek V4 Flash, aiming for maximum optimization. Apple's Metal API provides direct GPU access on Macs, enabling efficient inference on unified memory systems like the 96GB MacBook.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/antirez/ds4">GitHub - antirez/ds4: DeepSeek 4 Flash local inference engine ...</a></li>
<li><a href="https://pasqualepillitteri.it/en/news/2253/ds4-antirez-deepseek-v4-flash-inference-engine">DwarfStar4 (DS4) Roadmap by antirez: DeepSeek V4 Flash on ...</a></li>
<li><a href="https://localllmguide.polsia.app/articles/best-llms-for-mac-apple-silicon">Best LLMs for Mac Apple Silicon 2026 | LocalLLMGuide</a></li>

</ul>
</details>

**Discussion**: Community members praised DS4's quality, with one noting it feels close to Claude and even exhibited self-awareness. Some questioned the effort of building a model-specific engine versus using llama.cpp, but others valued the focused optimization.

**Tags**: `#LLM`, `#inference`, `#DeepSeek`, `#Metal`, `#open source`

---

<a id="item-6"></a>
## [RTX 5090 eGPU on M4 MacBook Air: Gaming & LLM Feasibility](https://scottjg.com/posts/2026-05-05-egpu-mac-gaming/) ⭐️ 8.0/10

A developer successfully connected an NVIDIA RTX 5090 eGPU to an M4 MacBook Air via Thunderbolt 4, enabling gaming and LLM inference that are otherwise impossible on macOS. The setup uses a custom driver (TinyGPU) and a VM with GPU passthrough to bypass Apple's lack of eGPU support. This demonstrates a workaround for Apple Silicon's closed GPU ecosystem, potentially opening up high-performance gaming and local AI workloads on Macs. It highlights the growing demand for CUDA acceleration on Apple hardware and the community's ingenuity in overcoming platform limitations. The eGPU setup requires a Thunderbolt 4 enclosure with a 1000-1200W PSU, and the RTX 5090 is only usable inside a Linux VM via GPU passthrough. Game benchmarks show playable frame rates in titles like Doom (2016) via Vulkan, but OpenGL games remain unplayable due to poor macOS support.

hackernews · allenleee · May 14, 15:47 · [Discussion](https://news.ycombinator.com/item?id=48137145)

**Background**: Apple Silicon Macs do not officially support external GPUs (eGPUs), especially NVIDIA ones, due to Apple's transition away from AMD GPUs and lack of NVIDIA driver support. The M4 MacBook Air relies on its integrated GPU for graphics, which is sufficient for light gaming but struggles with demanding games and LLM inference. The TinyGPU driver and VM passthrough technique enable CUDA acceleration on Apple Silicon by running a Linux VM that directly accesses the eGPU.

<details><summary>References</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=xnPggMt1RSE">An Overkill eGPU with Liquid Cooled RTX 5090 - YouTube</a></li>
<li><a href="https://www.compute-market.com/blog/nvidia-egpu-mac-local-ai-setup-2026">Nvidia eGPU on Mac for Local AI 2026 — TinyGPU Setup</a></li>
<li><a href="https://www.runlocalai.co/guides/best-egpu-setup-for-local-ai">Best eGPU setup for local AI — Thunderbolt + OCuLink... | RunLocalAI</a></li>

</ul>
</details>

**Discussion**: Commenters expressed surprise that eGPUs work on Apple Silicon at all, with one noting Apple's official stance that eGPUs require Intel Macs. Others praised the LLM inference improvements, highlighting that Macs' slow prompt processing is a known issue that this setup addresses. There was also discussion about the complexity of the VM passthrough approach and hopes for better official support.

**Tags**: `#eGPU`, `#Apple Silicon`, `#gaming`, `#LLM inference`, `#hardware hacking`

---

<a id="item-7"></a>
## [New Nginx Exploit Enables RCE via Rewrite Directives](https://github.com/DepthFirstDisclosures/Nginx-Rift) ⭐️ 8.0/10

A new Nginx exploit (CVE pending) allows arbitrary code execution via crafted rewrite and set directives under specific conditions, with a proof-of-concept published on GitHub. This vulnerability affects millions of Nginx servers worldwide, and the disclosure includes claims of a reliable ASLR bypass, making it a critical threat despite preconditions. The exploit requires a rewrite directive with a question mark in the replacement string, followed by a set directive referencing an unnamed regex capture group; F5 has released patches for Nginx 1.31.0 and 1.30.1.

hackernews · hetsaraiya · May 14, 17:17 · [Discussion](https://news.ycombinator.com/item?id=48138268)

**Background**: Nginx is a widely used web server and reverse proxy. The rewrite module compiles rewrite, set, if, and return directives into bytecode that runs per request. This vulnerability stems from a flaw in the compiler's handling of unnamed capture groups, present for 18 years.

<details><summary>References</summary>
<ul>
<li><a href="https://devops-daily.com/posts/nginx-rift-cve-2026-42945-rewrite-rce">NGINX Rift (CVE-2026-42945): The 18-Year-Old Rewrite Bug That...</a></li>
<li><a href="https://thehackernews.com/2026/05/18-year-old-nginx-rewrite-module-flaw.html">18-Year-Old NGINX Rewrite Module Flaw Enables Unauthenticated...</a></li>
<li><a href="https://depthfirst.com/research/nginx-rift-achieving-nginx-rce-via-an-18-year-old-vulnerability">NGINX Rift: Achieving NGINX Remote Code Execution via... | depthfirst</a></li>

</ul>
</details>

**Discussion**: Community comments highlight debate over the severity: some argue ASLR bypass makes it critical, while others note the exploit's preconditions and that ASLR provides protection. Mitigations using named captures are recommended.

**Tags**: `#nginx`, `#security`, `#exploit`, `#vulnerability`, `#web-server`

---

<a id="item-8"></a>
## [arXiv Bans Hallucinated References for 1 Year](https://twitter.com/tdietterich/status/2055000956144935055) ⭐️ 8.0/10

arXiv has introduced a new policy imposing a 1-year ban on authors who submit papers containing hallucinated references, followed by a requirement that future submissions must first be accepted at a reputable peer-reviewed venue. This policy directly addresses the growing problem of AI-generated hallucinated citations in academic preprints, helping to preserve scientific integrity and trust in the arXiv repository. The ban applies to authors found to have submitted papers with fabricated references, and after the ban, submissions must pass peer review before being posted on arXiv. The policy is not yet live but has been discussed publicly.

hackernews · gjuggler · May 14, 20:39 · [Discussion](https://news.ycombinator.com/item?id=48140922)

**Background**: Hallucinated references are non-existent citations generated by large language models (LLMs), which have become a significant issue in academic publishing. arXiv is a widely used preprint repository that allows rapid dissemination of research without peer review, making it vulnerable to such errors.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=48140922">New arXiv policy: 1-year ban for hallucinated references</a></li>
<li><a href="https://arxiv.org/abs/2305.18248">Do Language Models Know When They're Hallucinating References ?</a></li>
<li><a href="https://github.com/ethz-spylab/hallucinated-citations">GitHub - ethz-spylab/ hallucinated -citations: Check for...</a></li>

</ul>
</details>

**Discussion**: The community largely supports the policy, with comments praising it as a necessary step for scientific integrity. Some users suggest additional improvements, such as better citation tools, while others note that the policy may face resistance from LLM proponents.

**Tags**: `#arXiv`, `#academic integrity`, `#AI-generated content`, `#publishing policy`, `#hallucination`

---

<a id="item-9"></a>
## [Deep Dive into HDD Firmware Hacking](https://icode4.coffee/?p=1465) ⭐️ 8.0/10

A technical article details the process of dumping, reverse engineering, and modifying firmware on various HDDs and SSDs, highlighting vendor obfuscation weaknesses. This research exposes how trivial vendor obfuscation can be bypassed, raising serious concerns about the security of storage device firmware and the potential for persistent malware. The article demonstrates practical exploitation methods, including intercepting decrypted firmware from vendor update utilities using seccomp. Community comments also reference a prior decompilation of Samsung 840 EVO SSD firmware.

hackernews · jsploit · May 14, 16:19 · [Discussion](https://news.ycombinator.com/item?id=48137553)

**Background**: Firmware is low-level software embedded in hardware devices that controls their operation. Hard drive firmware manages data reading/writing and communication with the host system. Reverse engineering firmware can reveal vulnerabilities or allow modification, but vendors often use obfuscation to hinder analysis.

<details><summary>References</summary>
<ul>
<li><a href="https://icode4.coffee/?p=1465">HDD Firmware Hacking Part 1 – I Code 4 Coffee</a></li>
<li><a href="https://icmconference.org/wp-content/uploads/A14-VanK-HardDrive_Firmware_Hacking_ICMC-Copy.pdf">A Look Into Hard Drive Firmware</a></li>
<li><a href="https://en.wikipedia.org/wiki/Firmware">Firmware - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters noted that vendor obfuscation is often trivial to bypass, with one sharing a technique to capture decrypted firmware from a Linux update utility. Another commenter mentioned a prior decompilation of Samsung SSD firmware, and a third suggested the article could be useful for a company's interview CTF challenge involving a hard drive.

**Tags**: `#firmware`, `#reverse engineering`, `#hardware hacking`, `#security`, `#storage`

---

<a id="item-10"></a>
## [Clarity Act Clears Senate Committee, Nears Final Vote](https://www.coindesk.com/policy/2026/05/14/clarity-act-clears-u-s-senate-committee-on-its-way-to-a-final-test-in-congress) ⭐️ 8.0/10

The Clarity Act, a comprehensive crypto regulation bill, passed the U.S. Senate Banking Committee on May 14, 2026, moving closer to a final vote in Congress. This legislation could establish a clear regulatory framework for digital assets in the U.S., potentially reducing uncertainty and fostering industry growth. The bill, officially titled the Digital Asset Market Clarity Act of 2025, includes provisions to define digital assets and assign regulatory responsibilities between the SEC and CFTC.

rss · CoinDesk · May 14, 17:08

**Background**: The Clarity Act aims to provide a comprehensive rulebook for crypto markets, similar to the Dodd-Frank Act for traditional finance. It has been a priority for the crypto industry, which has long sought clearer regulations from U.S. lawmakers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.congress.gov/bill/119th-congress/house-bill/3633/text">Text - H.R.3633 - 119th Congress (2025-2026): Digital Asset Market Clarity Act of 2025 | Congress.gov | Library of Congress</a></li>
<li><a href="https://www.cnbc.com/2026/05/14/clarity-act-congress-crypto-senate.html">Crypto industry scores win as Clarity Act regulation bill clears Senate hurdle</a></li>
<li><a href="https://www.grayscale.com/the-stack/the-clarity-act-where-are-we-now-and-where-do-we-go-next">The CLARITY Act: Where Are We Now, and Where Do ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#US politics`, `#blockchain`

---

<a id="item-11"></a>
## [OpenAI Confirms Breach via Shai-Hulud Supply Chain Attack](https://decrypt.co/367883/openai-confirms-security-breach-ai-malware-campaign) ⭐️ 8.0/10

OpenAI confirmed that hackers linked to the Shai-Hulud malware campaign breached parts of its internal development environment after infecting two employee devices with malware from a compromised open-source package. This breach at a leading AI company highlights the growing threat of supply chain attacks targeting developer ecosystems, potentially exposing sensitive AI research and internal tools. The attack used malware from the Shai-Hulud supply chain campaign, which has compromised hundreds of open-source packages including those from Mistral AI and TanStack, targeting CI/CD pipelines to steal credentials.

rss · Decrypt · May 14, 18:30

**Background**: Supply chain attacks occur when attackers inject malicious code into legitimate software packages, which then spreads to users who install those packages. The Shai-Hulud campaign, first identified in late 2025, has evolved to target developer environments and AI ecosystems, using automated propagation to compromise CI/CD pipelines and cloud workloads.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/367883/openai-confirms-security-breach-ai-malware-campaign">OpenAI Confirms Security Breach Linked to AI Malware Campaign - Decrypt</a></li>
<li><a href="https://www.microsoft.com/en-us/security/blog/2025/12/09/shai-hulud-2-0-guidance-for-detecting-investigating-and-defending-against-the-supply-chain-attack/">Shai-Hulud 2.0: Guidance for detecting, investigating, and defending against the supply chain attack | Microsoft Security Blog</a></li>
<li><a href="https://unit42.paloaltonetworks.com/npm-supply-chain-attack/">"Shai-Hulud" Worm Compromises npm Ecosystem in Supply Chain Attack (Updated November 26)</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#security breach`, `#supply chain attack`, `#AI malware`, `#cybersecurity`

---

<a id="item-12"></a>
## [Half of AI Health Advice Is Wrong](https://decrypt.co/367689/half-ai-health-advice-wrong-seems-right) ⭐️ 8.0/10

A peer-reviewed audit published in BMJ Open found that nearly 50% of health responses from five major AI chatbots were problematic, often containing fabricated sources and confidently delivered misinformation. This raises serious concerns about the reliability of AI chatbots in critical domains like healthcare, where inaccurate advice could lead to harmful decisions. It underscores the need for rigorous validation and safeguards before deploying AI for medical guidance. The audit evaluated responses from five unnamed major AI chatbots across various health queries, finding that nearly half were problematic, with fabricated citations and confident but incorrect claims. The study was published in BMJ Open, a reputable peer-reviewed medical journal.

rss · Decrypt · May 13, 14:55

**Background**: AI chatbots like ChatGPT, Gemini, and Grok are increasingly used for health advice, but their training data may include unreliable sources. Unlike traditional search engines, chatbots present answers with high confidence, making it harder for users to detect errors. This study highlights the gap between AI's perceived reliability and actual accuracy in medical contexts.

<details><summary>References</summary>
<ul>
<li><a href="https://bmjopen.bmj.com/content/16/4/e112695">Generative artificial intelligence-driven chatbots and medical misinformation: an accuracy, referencing and readability audit | BMJ Open</a></li>
<li><a href="https://decrypt.co/367689/half-ai-health-advice-wrong-seems-right">Half of AI Health Advice Is Wrong—And Seems Just Right - Decrypt</a></li>

</ul>
</details>

**Tags**: `#AI`, `#health`, `#misinformation`, `#chatbots`, `#research`

---

<a id="item-13"></a>
## [Codex coding agent now in ChatGPT mobile app](https://openai.com/index/work-with-codex-from-anywhere/) ⭐️ 7.0/10

OpenAI has integrated its Codex coding agent into the ChatGPT mobile app, allowing free-tier users to access coding assistance on the go. This expansion makes a powerful AI coding tool more accessible, enabling developers to work on code from anywhere without needing a desktop or CLI setup. Codex is available for free as part of the ChatGPT free plan, though interactions may be used for training. The mobile app provides a streamlined interface for directing the agent.

hackernews · mikeevans · May 14, 20:06 · [Discussion](https://news.ycombinator.com/item?id=48140529)

**Background**: Codex is an AI coding agent from OpenAI that can write features, fix bugs, and answer codebase questions. It was initially released in April 2025 as a CLI tool, with later desktop and IDE integrations. The mobile app extends its reach to smartphones.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Codex_(AI_agent)">Codex (AI agent) - Wikipedia</a></li>
<li><a href="https://github.com/openai/codex">GitHub - openai/codex: Lightweight coding agent that runs in your terminal · GitHub</a></li>
<li><a href="https://openai.com/index/introducing-codex/">Introducing Codex | OpenAI</a></li>

</ul>
</details>

**Discussion**: Community members are excited about free access and remote workflow possibilities, but some note that the mobile interface may lead to less precise direction and increased code churn compared to desktop use.

**Tags**: `#AI coding assistant`, `#mobile development`, `#OpenAI`, `#developer tools`

---

<a id="item-14"></a>
## [CME to Launch Nasdaq CME Crypto Index Futures on June 8](https://www.coindesk.com/markets/2026/05/14/cme-dives-further-into-usd85-trillion-digital-assets-market-with-nasdaq-cme-crypto-index-futures) ⭐️ 7.0/10

CME Group announced it will launch Nasdaq CME Crypto Index futures on June 8, pending regulatory approval, marking its first market-cap-weighted futures contract covering Bitcoin and six other cryptocurrencies. This product provides institutional investors with a regulated, diversified exposure to the digital assets market, further legitimizing cryptocurrencies and potentially boosting liquidity and price discovery. The futures will be financially settled to the Nasdaq CME Crypto Settlement Price Index and will be available in both micro and larger contract sizes, offering flexibility for different trading strategies.

rss · CoinDesk · May 14, 16:25

**Background**: CME Group is a leading derivatives marketplace, and Nasdaq is a global index provider. The Nasdaq CME Crypto Index is a benchmark designed for institutional-grade cryptocurrency exposure, applying strict liquidity, exchange, and custody standards. This launch expands CME's existing crypto derivatives suite, which includes Bitcoin and Ether futures.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cmegroup.com/media-room/press-releases/2026/5/14/cme_group_to_launchnasdaqcmecryptoindexfutures.html">CME Group to Launch Nasdaq CME Crypto Index Futures</a></li>
<li><a href="https://www.prnewswire.com/news-releases/cme-group-to-launch-nasdaq-cme-crypto-index-futures-302772026.html">CME Group to Launch Nasdaq CME Crypto Index Futures</a></li>
<li><a href="https://www.coindesk.com/markets/2026/05/14/cme-dives-further-into-usd85-trillion-digital-assets-market-with-nasdaq-cme-crypto-index-futures">CME dives further into $85 trillion digital assets market ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#futures`, `#institutional adoption`, `#CME`, `#digital assets`

---

<a id="item-15"></a>
## [Kimi WebBridge Lets AI Agents Control Browser Locally](https://decrypt.co/367916/kimi-webbridge-ai-agents-browser-local) ⭐️ 7.0/10

Moonshot AI has released Kimi WebBridge, a browser extension that pairs with a local service to allow AI agents to control Chrome or Edge via the Chrome DevTools Protocol, all without sending data to the cloud. This approach addresses major privacy concerns by keeping user sessions and page content on the local machine, enabling powerful browser automation for tasks like form filling and navigation without compromising data security. The extension uses a local background service that communicates with the AI agent, which sends commands to click, scroll, fill forms, and take screenshots, then returns results to the agent.

rss · Decrypt · May 14, 19:49

**Background**: AI agents that control browsers typically rely on cloud-based processing, which raises privacy risks as user data is transmitted to remote servers. Kimi WebBridge flips this model by running the agent locally, using the Chrome DevTools Protocol to interact with the browser directly. This allows users to automate repetitive web tasks while keeping sensitive information like login credentials and page content on their own device.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kimi.com/features/webbridge">WebBridge - Let Kimi Agent Drive Your Browser | Kimi</a></li>
<li><a href="https://decrypt.co/367916/kimi-webbridge-ai-agents-browser-local">Kimi WebBridge Lets AI Agents Drive Your Browser—And Keep ...</a></li>
<li><a href="https://tech.yahoo.com/ai/meta-ai/articles/kimi-webbridge-lets-ai-agents-194937263.html">Kimi WebBridge Lets AI Agents Drive Your Browser—And Keep Your...</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#browser automation`, `#privacy`, `#local AI`, `#extension`

---

<a id="item-16"></a>
## [Study: AI Agents Execute Dangerous Tasks Without Understanding Risks](https://decrypt.co/367869/ai-agents-dangerous-tasks-without-understanding-consequences) ⭐️ 7.0/10

A new study reveals that AI agents designed to automate tasks often pursue them without recognizing when their actions are dangerous, highlighting a critical safety flaw. This finding underscores a fundamental challenge in AI alignment and safety, potentially influencing future regulation and development of autonomous AI systems. The study specifically examined AI agents that automate tasks, finding they lack awareness of the consequences of their actions, which could lead to unintended harm.

rss · Decrypt · May 14, 17:32

**Background**: AI agents are autonomous software systems that can perceive their environment and take actions to achieve goals. The AI alignment problem refers to ensuring these systems act in accordance with human values and intentions. This study highlights a gap in current agent design where safety considerations are not inherently integrated.

<details><summary>References</summary>
<ul>
<li><a href="https://cloud.google.com/discover/what-are-ai-agents">What are AI agents ? Definition , examples, and types | Google Cloud</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_alignment">AI alignment - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#AI agents`, `#alignment`, `#research`

---

<a id="item-17"></a>
## [Kraken Swaps LayerZero for Chainlink in Cross-Chain Bridge](https://www.coindesk.com/business/2026/05/14/kraken-to-replace-layerzero-with-chainlink-to-bridge-assets-across-blockchains) ⭐️ 6.0/10

Kraken announced it is replacing LayerZero with Chainlink's Cross-Chain Interoperability Protocol (CCIP) as the exclusive cross-chain infrastructure for its wrapped Bitcoin product kBTC and future wrapped assets. This migration, involving over $3 billion in total value locked, signals a major shift in the cross-chain bridging landscape following the $292 million Kelp DAO exploit on LayerZero, potentially driving more protocols to prioritize security over other factors. Kraken is at least the fourth product to deprecate LayerZero after the Kelp DAO attack, joining Solv Protocol, Re, and KelpDAO itself in migrating nearly $1 billion to Chainlink CCIP.

rss · CoinDesk · May 14, 15:17

**Background**: Cross-chain bridges allow assets to move between different blockchains but have been frequent targets for hackers, with over $2 billion stolen in 2022 alone. Chainlink CCIP is a cross-chain protocol designed with built-in compliance and privacy features, emphasizing security. LayerZero is another popular cross-chain protocol that suffered a $292 million exploit in April 2026, attributed to the Lazarus Group, which eroded trust in its security.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/05/14/kraken-to-replace-layerzero-with-chainlink-to-bridge-assets-across-blockchains">Kraken to replace LayerZero with Chainlink for kBTC, future ...</a></li>
<li><a href="https://www.coindesk.com/tech/2026/04/19/2026-s-biggest-crypto-exploit-kelp-dao-hit-for-usd292-million-with-wrapped-ether-stranded-across-20-chains">Kelp DAO exploited for $292 million with wrapped ether ...</a></li>
<li><a href="https://news.bitcoin.com/solv-protocol-and-re-switch-to-chainlink-ccip-moving-nearly-1b-away-from-layerzero/">Solv Protocol and Re Switch to Chainlink CCIP, Moving Nearly ...</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#cryptocurrency`, `#interoperability`, `#oracles`

---

<a id="item-18"></a>
## [BlackRock and Janus Henderson Enable Instant Fund Redemptions](https://www.coindesk.com/business/2026/05/14/blackrock-janus-henderson-tokenized-funds-get-instant-redemptions-with-new-usd1-billion-facility) ⭐️ 6.0/10

BlackRock and Janus Henderson have launched a $1 billion credit facility, called Basin, that allows instant redemptions from their tokenized money market funds into stablecoins, reducing settlement from days to seconds. This development bridges traditional asset management with blockchain liquidity, making tokenized funds more practical for institutional investors who need fast access to cash. The facility is provided by Grove, a credit platform, and supports BlackRock's BUIDL fund and Janus Henderson's tokenized money market funds, with up to $1 billion in daily stablecoin liquidity.

rss · CoinDesk · May 14, 13:00

**Background**: Tokenized funds represent traditional fund shares as digital tokens on a blockchain, enabling faster and cheaper transactions. However, redemptions typically take days due to underlying asset settlement. This facility uses a credit line to provide instant stablecoin liquidity, bypassing traditional settlement delays.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/05/14/blackrock-janus-henderson-tokenized-funds-get-instant-redemptions-with-new-usd1-billion-facility">BlackRock, Janus Henderson tokenized funds get instant ...</a></li>
<li><a href="https://coinalertnews.com/news/2026/05/14/grove-basin-instant-redemptions">Grove Launches $1B Basin Facility for Instant Redemptions of ...</a></li>
<li><a href="https://phemex.com/news/article/blackrocks-22b-tokenized-fund-enables-instant-stablecoin-redemptions-81460">BlackRock's $2.2B Fund Offers Instant Stablecoin Redemptions ...</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#finance`, `#blockchain`, `#asset management`

---

<a id="item-19"></a>
## [Moody's Assigns Top Aaa-mf Rating to Tokenized Money Market Funds](https://www.coindesk.com/markets/2026/05/14/moody-s-awards-top-rating-to-fidelity-and-blackrock-s-tokenized-money-market-funds) ⭐️ 6.0/10

Moody's assigned its highest Aaa-mf assessment to tokenized money market funds issued by Fidelity International and BlackRock, indicating the highest level of credit quality, liquidity, and capital preservation. This institutional validation from a major rating agency could accelerate adoption of tokenized assets in traditional finance, bridging the gap between DeFi and regulated markets. The Aaa-mf rating goes beyond default risk to assess liquidity and capital stability, specifically for funds that maintain capital and have strong liquidity buffers.

rss · CoinDesk · May 14, 08:49

**Background**: Tokenized money market funds represent fund shares as digital tokens on a blockchain, combining the reliability of traditional MMFs with the speed and transparency of digital assets. They offer returns comparable to short-term risk-free rates and are particularly useful for crypto-native investors seeking stable yields.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/markets/2026/05/14/moody-s-awards-top-rating-to-fidelity-and-blackrock-s-tokenized-money-market-funds">Moody’s assigns Aaa-mf assessments to Fidelity International ...</a></li>
<li><a href="https://www.valuethemarkets.com/cryptocurrency/news/moodys-grants-aaa-mf-rating-to-fidelity-and-blackrock-tokenized-money-market-products">Moody's Grants AAA-mf Rating to Fidelity and BlackRock ...</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#DeFi`, `#ratings`, `#institutional finance`

---

<a id="item-20"></a>
## [OpenAI Boosts ChatGPT Safety Amid Lawsuits](https://decrypt.co/367937/openai-new-chatgpt-safety-features-lawsuits-investigations) ⭐️ 6.0/10

OpenAI has enhanced ChatGPT's ability to detect and respond to signs of self-harm and violence, introducing new safety features as the company faces multiple lawsuits and regulatory investigations over harmful chatbot interactions. This update is significant because it directly addresses growing legal and public pressure on AI companies to prevent harm from their products, potentially setting a precedent for safety standards across the industry. The new safety features improve ChatGPT's ability to recognize dangerous content in real-time, though OpenAI has not disclosed specific technical details or benchmarks. The move comes amid investigations by the U.S. Federal Trade Commission and lawsuits from families alleging harm from the chatbot.

rss · Decrypt · May 14, 21:43

**Background**: Large language models like ChatGPT can sometimes generate harmful or dangerous responses, including advice on self-harm or violence. AI safety researchers have long warned about these risks, and regulators worldwide are increasingly scrutinizing AI companies' safety practices.

**Tags**: `#AI safety`, `#ChatGPT`, `#OpenAI`, `#regulation`

---

<a id="item-21"></a>
## [ChatGPT Losing Web Traffic Share to Rivals](https://decrypt.co/367884/chatgpt-losing-ground-anthrophic-google-numbers) ⭐️ 6.0/10

Recent data shows ChatGPT's web traffic share is declining as competitors like Anthropic and Google gain ground, indicating a shift in enterprise AI adoption. This shift signals that businesses are exploring alternatives to OpenAI, which could reshape the competitive landscape of the AI industry and impact OpenAI's market dominance. The article cites web traffic data but does not provide specific percentages or timeframes; it is a brief news piece without in-depth analysis.

rss · Decrypt · May 14, 18:44

**Background**: ChatGPT, launched by OpenAI in late 2022, quickly became the dominant AI chatbot. However, competitors like Anthropic's Claude and Google's Gemini have emerged with strong capabilities, attracting enterprise customers.

**Tags**: `#AI`, `#ChatGPT`, `#market trends`, `#competition`

---

<a id="item-22"></a>
## [Tether, Tron, TRM Freeze $450M in Illicit Crypto Funds](https://decrypt.co/367874/tether-tron-trm-financial-crime-unit-frozen-450-million-crypto-funds) ⭐️ 6.0/10

Tether, Tron, and TRM Labs have frozen $450 million in illicit cryptocurrency funds through a public-private partnership with law enforcement agencies across 23 countries. This demonstrates growing collaboration between crypto platforms and global law enforcement to combat illicit activity, potentially increasing trust in stablecoins and blockchain networks. The partnership involves Tether (USDT), the largest stablecoin by market cap, the Tron blockchain, and blockchain intelligence firm TRM Labs, which provides transaction monitoring tools.

rss · Decrypt · May 14, 17:16

**Background**: Tether (USDT) is a stablecoin pegged to the US dollar, widely used for trading and transfers. Tron is a proof-of-stake blockchain known for high throughput. TRM Labs offers compliance and investigation solutions for crypto transactions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tron_(blockchain)">Tron ( blockchain ) - Wikipedia</a></li>
<li><a href="https://www.trmlabs.com/">TRM Labs | Agents and intelligence to fight crime</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#blockchain`, `#security`, `#regulation`

---

<a id="item-23"></a>
## [Tezos Tests Post-Quantum Privacy, Founder Criticizes Bitcoin](https://decrypt.co/367795/tezos-post-quantum-privacy-founder-slams-half-baked-bitcoin-theories) ⭐️ 6.0/10

Tezos has launched TzEL, a post-quantum privacy system on its testnet, designed to protect encrypted transaction data from future quantum computing attacks. Founder Arthur Breitman also criticized the Bitcoin community for dismissing quantum threats as 'half-baked' theories. This development is significant because it addresses the growing concern that quantum computers could break current cryptographic standards, threatening blockchain security. Tezos' proactive approach may set a precedent for other blockchains to adopt post-quantum cryptography. TzEL combines post-quantum cryptography with zk-STARK proofs to ensure privacy and quantum resistance. The system is currently on testnet and aims to counter 'harvest now, decrypt later' attacks.

rss · Decrypt · May 14, 13:01

**Background**: Post-quantum cryptography refers to cryptographic algorithms believed to be secure against attacks from quantum computers. 'Harvest now, decrypt later' attacks involve adversaries collecting encrypted data now with the expectation of decrypting it once quantum computers become powerful enough. Tezos is a blockchain platform that supports smart contracts and has a focus on formal verification and upgradeability.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/367795/tezos-post-quantum-privacy-founder-slams-half-baked-bitcoin-theories">Tezos Tests Post-Quantum Privacy as Founder Slams ... - Decrypt</a></li>
<li><a href="https://cointelegraph.com/news/tezos-quantum-resistant-private-payments-prototype-testnet">Tezos Developers Test quantum-Resistant Blockchain Privacy System</a></li>
<li><a href="https://tech.yahoo.com/cybersecurity/articles/tezos-tests-post-quantum-privacy-130103366.html">Tezos Tests Post-Quantum Privacy as Founder Slams 'Half-Baked' Bitcoin Quantum Theories</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#post-quantum cryptography`, `#Tezos`, `#privacy`

---

<a id="item-24"></a>
## [Charles Schwab Begins Bitcoin, Ethereum Trading for US Users](https://decrypt.co/367768/charles-schwab-begins-bitcoin-ethereum-trading-us-users) ⭐️ 6.0/10

Charles Schwab has started allowing select US users to trade Bitcoin and Ethereum directly alongside their traditional investments. This marks a significant step in mainstream adoption of cryptocurrencies, as a major traditional financial institution integrates digital assets into its platform, potentially attracting more conservative investors. The service is currently limited to select users, and only Bitcoin and Ethereum are supported. It allows users to manage crypto alongside stocks, bonds, and other assets in a single account.

rss · Decrypt · May 13, 16:31

**Background**: Charles Schwab is one of the largest brokerage firms in the US, managing trillions of dollars in assets. Previously, the firm offered indirect crypto exposure through ETFs and futures, but this is the first time it allows direct trading of cryptocurrencies.

**Tags**: `#cryptocurrency`, `#finance`, `#bitcoin`, `#ethereum`, `#trading`

---

<a id="item-25"></a>
## [Bank of England Views Stablecoins as New Money Form](https://decrypt.co/367750/bank-england-treating-stablecoins-new-form-money-exec) ⭐️ 6.0/10

Bank of England executive Sasha Mills stated that the central bank treats stablecoins as a new form of money and is not picking winners between tokenized deposits and stablecoins. This signals a balanced regulatory approach from a major central bank, which could influence global stablecoin regulation and foster innovation in digital payments. The statement was made on Wednesday, but no specific date was provided in the article. The Bank of England's stance remains neutral between tokenized deposits and stablecoins.

rss · Decrypt · May 13, 15:57

**Background**: Stablecoins are cryptocurrencies designed to maintain a stable value, often pegged to fiat currencies like the US dollar. Tokenized deposits are digital representations of bank deposits on blockchain, which are regulated and insured. The UK Treasury has previously recognized stablecoins as a valid form of payment.

<details><summary>References</summary>
<ul>
<li><a href="https://bankingjournal.aba.com/2026/03/tokenized-deposits-the-future-of-tokenized-money-for-financial-market-settlement/">Tokenized deposits: the future of tokenized money for ...</a></li>
<li><a href="https://www.newyorkfed.org/research/staff_reports/sr1179">Stablecoins vs. Tokenized Deposits: The Narrow Banking Debate ...</a></li>
<li><a href="https://thedefiant.io/news/defi/uk-crypto-regulation-stablecoins">U . K . Embraces Stablecoins as 'Valid Form of Payment' - "The Defia...</a></li>

</ul>
</details>

**Tags**: `#stablecoins`, `#regulation`, `#central bank`, `#cryptocurrency`

---

<a id="item-26"></a>
## [CertiK CEO: DeFi attackers using AI to outspend defenders](https://www.theblock.co/post/401280/unfair-game-certik-ceo-defi-attackers-using-ai-outspend-defenders?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

CertiK CEO warns that DeFi attackers are increasingly using AI to target operational security and supply-chain weaknesses, outspending defenders in a financially asymmetric battle. This shift from smart contract bugs to operational and supply-chain attacks signals a new, harder-to-defend threat landscape for DeFi, potentially leading to larger losses and undermining trust in decentralized finance. The comment was made by CertiK CEO Ronghui Gu at an industry event, highlighting that attackers now exploit human errors, key management, and third-party dependencies rather than code flaws.

rss · The Block · May 14, 19:46

**Background**: CertiK is a leading blockchain security firm that uses AI and formal verification to audit smart contracts. DeFi (decentralized finance) platforms manage billions in assets but have suffered major hacks, often due to smart contract bugs. However, attackers are now pivoting to cheaper, high-impact operational and supply-chain attacks, such as phishing or compromising infrastructure, which are harder to defend against with traditional code audits.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/401280/unfair-game-certik-ceo-defi-attackers-using-ai-outspend-defenders">'It's an unfair game': CertiK CEO says DeFi attackers using ...</a></li>
<li><a href="https://www.certik.com/">Largest Blockchain Security Auditor - CertiK</a></li>
<li><a href="https://www.ainvest.com/news/escalating-threat-supply-chain-risks-defi-10-billion-wake-call-investors-2512/">The Escalating Threat of Supply Chain Risks in DeFi: A $10 ...</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#AI`, `#security`, `#blockchain`

---

<a id="item-27"></a>
## [ZachXBT alleges 95% insider control of LAB token](https://www.theblock.co/post/401290/zachxbt-alleges-95-insider-control-of-lab-token-in-investigation-into-ai-terminals-6-billion-fdv-project?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Blockchain investigator ZachXBT has alleged that 95% of the LAB token supply is controlled by insiders through hidden OTC deals, private loans, and a market maker tied to manipulation schemes, in a project with a fully diluted valuation (FDV) of $6 billion. This investigation highlights potential widespread insider manipulation in high-FDV crypto projects, undermining trust in tokenomics and raising concerns about retail investor protection in the AI token sector. The LAB token is associated with an AI terminal project, and ZachXBT's findings include evidence of hidden deals and a market maker previously linked to manipulation. The project's $6 billion FDV is based on a fully diluted token supply, which may not reflect actual circulating supply.

rss · The Block · May 14, 14:34

**Background**: Fully Diluted Valuation (FDV) is a metric that calculates a cryptocurrency's market cap if all tokens were in circulation, often used to assess project value. ZachXBT is a prominent pseudonymous blockchain investigator known for exposing crypto fraud and scams. Insider control of token supply can lead to price manipulation and unfair advantages for early investors.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ZachXBT">ZachXBT</a></li>
<li><a href="https://www.okx.com/learn/what-is-fully-diluted-valuation-fdv">What is Fully Diluted Valuation ( FDV ): crypto meme or red flag? | OKX</a></li>
<li><a href="https://coinmarketcap.com/currencies/lab/">LAB price today, LAB to USD live price, marketcap and chart ...</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#insider trading`, `#AI token`, `#blockchain`, `#investigation`

---