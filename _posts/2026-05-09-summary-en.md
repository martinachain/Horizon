---
layout: default
title: "Horizon Summary: 2026-05-09 (EN)"
date: 2026-05-09
lang: en
---

> From 94 items, 27 important content pieces were selected

---

1. [Google's new reCAPTCHA breaks de-googled Android](#item-1) ⭐️ 8.0/10
2. [OpenAI's WebRTC Problem: Complexity vs. AI Voice](#item-2) ⭐️ 8.0/10
3. [AI is breaking two vulnerability cultures](#item-3) ⭐️ 8.0/10
4. [AWS North Virginia Outage Disrupts Major Services](#item-4) ⭐️ 8.0/10
5. [Anthropic Teaches AI the 'Why' Behind Rules](#item-5) ⭐️ 8.0/10
6. [Mojo 1.0 Beta Released with Python-like Syntax and High Performance](#item-6) ⭐️ 8.0/10
7. [Zcash to Launch Quantum-Recoverable Wallets, Go Quantum-Proof by 2027](#item-7) ⭐️ 8.0/10
8. [Chrome Removes Privacy Promise for On-Device AI](#item-8) ⭐️ 8.0/10
9. [AI Chatbots Leak User Data to Ad Trackers](#item-9) ⭐️ 8.0/10
10. [Tether's Medical AI Runs on Phone, Beats 16x Larger Models](#item-10) ⭐️ 8.0/10
11. [Google Boosts Local AI Speed 3x Without New Hardware](#item-11) ⭐️ 8.0/10
12. [Meshtastic: Off-Grid LoRa Mesh Text Messaging](#item-12) ⭐️ 7.0/10
13. [Judge Clears Aave to Move $71M ETH Linked to North Korea Hack](#item-13) ⭐️ 7.0/10
14. [SEC Chair Atkins Signals New Rules for Onchain Markets and AI Finance](#item-14) ⭐️ 7.0/10
15. [Bitcoin Miner IREN Lands $3.4B Nvidia AI Deal](#item-15) ⭐️ 7.0/10
16. [IMF Warns AI Will Supercharge Cyberattacks on Global Financial System](#item-16) ⭐️ 7.0/10
17. [Amazon, Coinbase, Stripe Enable AI Agents to Pay with Stablecoins](#item-17) ⭐️ 7.0/10
18. [TrustedVolumes DeFi Exploit Drains $6.7M](#item-18) ⭐️ 7.0/10
19. [David Attenborough's 100th Birthday Celebrated](#item-19) ⭐️ 6.0/10
20. [io_uring ZCRX Freelist LPE Exploit](#item-20) ⭐️ 6.0/10
21. [Running a Website from RAM on Raspberry Pi Zero](#item-21) ⭐️ 6.0/10
22. [Kraken Parent Seeks OCC Charter for Federal Crypto Bank](#item-22) ⭐️ 6.0/10
23. [ECB's Lagarde warns against copying U.S. stablecoin model](#item-23) ⭐️ 6.0/10
24. [Senate Banking Committee to Vote on Crypto Bill](#item-24) ⭐️ 6.0/10
25. [TeraWulf's HPC Revenue Tops Bitcoin Mining for First Time](#item-25) ⭐️ 6.0/10
26. [Arbitrum DAO Approves $70M ETH Release for Kelp DAO Recovery](#item-26) ⭐️ 6.0/10
27. [Solv Protocol Switches from LayerZero to Chainlink for $700M BTC](#item-27) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Google's new reCAPTCHA breaks de-googled Android](https://reclaimthenet.org/google-broke-recaptcha-for-de-googled-android-users) ⭐️ 8.0/10

Google has updated reCAPTCHA to a new version that effectively requires remote attestation, breaking access for de-googled Android users who do not have Google Play Services. This change forces de-googled Android users to either accept privacy-invasive remote attestation or lose access to millions of websites that rely on reCAPTCHA, raising significant privacy and digital sovereignty concerns. The new reCAPTCHA uses remote attestation, which ties the device to a unique hardware key (EK) and logs conversions to ephemeral identity keys (AIK) on Google servers, potentially enabling user tracking. This breaks compatibility with custom ROMs and de-googled devices that lack Google's attestation infrastructure.

hackernews · anonymousiam · May 8, 18:45 · [Discussion](https://news.ycombinator.com/item?id=48067119)

**Background**: De-googled Android refers to Android operating systems stripped of Google services, such as Play Store and Play Services, often used for privacy reasons. Remote attestation is a cryptographic process that proves a device's software and hardware integrity to a remote server, but it can also be used to uniquely identify devices. Google's reCAPTCHA is a widely deployed bot detection service that now leverages this technology.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/DeGoogle">DeGoogle - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Remote_attestation">Remote attestation</a></li>
<li><a href="https://cloud.google.com/blog/products/identity-security/introducing-google-cloud-fraud-defense-the-next-evolution-of-recaptcha/">Introducing Google Cloud Fraud Defense, the next evolution of reCAPTCHA | Google Cloud Blog</a></li>

</ul>
</details>

**Discussion**: Community comments express strong frustration, with users comparing the new reCAPTCHA to KYC (Know Your Customer) requirements and criticizing Google for forcing remote attestation. Some users suggest alternatives like Private Access Tokens, while others share personal experiences of moving away from Google services entirely.

**Tags**: `#privacy`, `#Android`, `#reCAPTCHA`, `#remote attestation`, `#Google`

---

<a id="item-2"></a>
## [OpenAI's WebRTC Problem: Complexity vs. AI Voice](https://moq.dev/blog/webrtc-is-the-problem/) ⭐️ 8.0/10

A critical blog post argues that WebRTC is overly complex and unsuitable for real-time AI voice applications, proposing WebTransport and WebCodecs as better alternatives. This matters because WebRTC is widely used for real-time communication, but its complexity hinders the development of low-latency AI voice interfaces, which are critical for user experience. The post highlights WebRTC's cumbersome handshake involving SDP, ICE, STUN/TURN, and peer-to-peer protocols, while WebTransport offers simpler multiplexed streams over HTTP/3 and WebCodecs provides low-level codec control.

hackernews · atgctg · May 7, 17:11 · [Discussion](https://news.ycombinator.com/item?id=48051951)

**Background**: WebRTC is a set of protocols for real-time peer-to-peer communication in browsers, but it was designed for video/audio calls, not AI voice. WebTransport is a newer API for bidirectional streaming over HTTP/3, and WebCodecs gives direct access to media codecs, enabling more efficient processing.

<details><summary>References</summary>
<ul>
<li><a href="https://www.w3.org/TR/webtransport/">WebTransport</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/WebTransport">WebTransport - Web APIs | MDN</a></li>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/API/WebCodecs_API">WebCodecs API - Web APIs | MDN - MDN Web Docs</a></li>

</ul>
</details>

**Discussion**: Commenters share mixed experiences: some agree WebRTC is painful to implement, while others note that at scale, WebRTC works well for voice agents with proper tooling like Pipecat. One commenter describes a simpler approach used for Alexa, keeping a persistent HTTP/2-like connection.

**Tags**: `#WebRTC`, `#real-time communication`, `#AI voice`, `#WebTransport`, `#protocol design`

---

<a id="item-3"></a>
## [AI is breaking two vulnerability cultures](https://www.jefftk.com/p/ai-is-breaking-two-vulnerability-cultures) ⭐️ 8.0/10

AI is accelerating exploit generation, undermining the traditional divide between coordinated disclosure and full disclosure, forcing a reevaluation of vulnerability handling norms. This shift could render current disclosure practices obsolete, increasing the risk of zero-day attacks and pressuring organizations to adopt faster patching cycles. The article highlights that AI tools can now generate exploits from patch diffs, reducing the window for coordinated disclosure. Real-world examples like Log4Shell show how public commits can trigger attacks before an official announcement.

hackernews · speckx · May 8, 17:55 · [Discussion](https://news.ycombinator.com/item?id=48066524)

**Background**: Coordinated vulnerability disclosure (CVD) allows vendors time to patch before public disclosure, while full disclosure releases details immediately to pressure vendors. AI-powered exploit generation blurs this distinction by enabling attackers to weaponize vulnerabilities faster than ever.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure">Coordinated vulnerability disclosure - Wikipedia</a></li>
<li><a href="https://cyberdetectpro.com/coordinated-disclosure-vs-full-disclosure-comparison/">Coordinated Disclosure vs. Full Disclosure: Comparison</a></li>
<li><a href="https://www.csoonline.com/article/3819176/top-5-ways-attackers-use-generative-ai-to-exploit-your-systems.html">13 ways attackers use generative AI to exploit your systems | CSO Online</a></li>

</ul>
</details>

**Discussion**: Comments from security experts like tptacek note that the breakdown was predicted long before AI, driven by open-source transparency and improved reversing tools. Others argue AI is reframing an old problem, and shorter embargoes may not help slow patchers.

**Tags**: `#AI`, `#vulnerability disclosure`, `#security`, `#open source`, `#exploit generation`

---

<a id="item-4"></a>
## [AWS North Virginia Outage Disrupts Major Services](https://www.cnbc.com/2026/05/08/aws-outage-data-center-fanduel-coinbase.html) ⭐️ 8.0/10

On May 8, 2026, a cooling failure caused overheating in an AWS data center in the US-East-1 region, leading to a power loss that disrupted services for hours, affecting platforms like Coinbase and FanDuel. This outage highlights the fragility of the heavily used US-East-1 region, which has a history of major failures, and underscores the risks of relying on a single cloud region for critical services. The outage was caused by a thermal event in one Availability Zone (use1-az4) of US-East-1, leading to power loss and EC2 impairment. Recovery was expected to take hours, with some services still impacted the next day.

hackernews · christhecaribou · May 8, 03:31 · [Discussion](https://news.ycombinator.com/item?id=48058197)

**Background**: AWS US-East-1 is one of the oldest and most heavily used AWS regions, hosting a large number of critical internet services. It has experienced several major outages in the past, including in 2021 and October 2025, raising concerns about its reliability. AWS executives have stated the region is not inherently more fragile but operates at a larger scale, which can stress services.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theregister.com/off-prem/2026/05/08/aws-warns-of-ec2-impairment-as-power-loss-hits-notorious-us-east-1-region/5235509">AWS warns of EC2 'impairment' as power loss hits notorious US ...</a></li>
<li><a href="https://www.cnbc.com/2026/05/08/aws-outage-data-center-fanduel-coinbase.html">AWS data center outage hits trading on FanDuel, Coinbase — recovery to take hours</a></li>
<li><a href="https://www.networkworld.com/article/4168878/aws-hit-by-us-east-1-outage-after-data-center-thermal-event.html">AWS hit by US-East-1 outage after data center thermal event | Network World</a></li>

</ul>
</details>

**Discussion**: Community comments expressed frustration with US-East-1's repeated failures, with some questioning why it is more prone to outages than other regions. Others raised concerns about insider trading risks, as employees could potentially bet on outage outcomes. There was also discussion about whether AWS overbooks cooling capacity in its data centers.

**Tags**: `#AWS`, `#outage`, `#cloud`, `#reliability`, `#us-east-1`

---

<a id="item-5"></a>
## [Anthropic Teaches AI the 'Why' Behind Rules](https://www.anthropic.com/research/teaching-claude-why) ⭐️ 8.0/10

Anthropic has published research on a method to train AI models to understand and internalize the reasoning behind rules, aiming for more robust and generalizable alignment. The approach goes beyond simple rule-following by teaching models the underlying principles. This research addresses a key limitation in AI alignment: models often follow rules superficially and fail in novel situations. By teaching the 'why,' models may generalize better and resist adversarial manipulation, potentially leading to safer and more trustworthy AI systems. The research is related to Anthropic's Model Spec Midtraining work, which has been applied to open-weight models like Llama 3.1 8B and Qwen 2.5 32B. The method involves training models on reasoning traces that explain the rationale behind desired behaviors.

hackernews · pretext · May 8, 17:59 · [Discussion](https://news.ycombinator.com/item?id=48066592)

**Background**: AI alignment aims to steer AI systems toward human intentions and values. A common approach is to train models to follow explicit rules, but this can lead to brittle behavior when rules conflict or situations are novel. Teaching the reasoning behind rules may produce more robust alignment.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_alignment">AI alignment</a></li>
<li><a href="https://www.anthropic.com/research/team/interpretability">Interpretability Research \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Comments highlight concerns about the definition of alignment: one user questions whether a model that eliminates labor value can be considered aligned, suggesting current definitions are insufficient. Another notes the connection to pedagogical approaches, while a third draws parallels to philosophical debates about value systems.

**Tags**: `#AI alignment`, `#Anthropic`, `#machine learning`, `#interpretability`, `#safety`

---

<a id="item-6"></a>
## [Mojo 1.0 Beta Released with Python-like Syntax and High Performance](https://mojolang.org/) ⭐️ 8.0/10

Modular has released Mojo 1.0 Beta, a significant milestone for the language that combines Python-like syntax with a Rust-inspired ownership model, comptime, and first-class SIMD support. The beta version is available for Linux and macOS, with open-sourcing planned for Fall 2026. Mojo aims to bridge the gap between Python's ease of use and the performance of systems languages like C++ and Rust, targeting machine learning and systems programming. Its release could challenge established frameworks like CUDA and Triton by offering a unified language for CPU and GPU code. Mojo uses MLIR (Multi-Level Intermediate Representation) as its compiler infrastructure, enabling advanced optimizations beyond typical LLVM wrappers. The language features an ownership model similar to Rust, compile-time metaprogramming (comptime), and direct SIMD intrinsics for performance-critical code.

hackernews · sbt567 · May 8, 02:49 · [Discussion](https://news.ycombinator.com/item?id=48057901)

**Background**: Mojo is a proprietary programming language developed by Modular, founded by Chris Lattner (creator of LLVM and Swift). It aims to provide Python-like syntax with the performance of C++ or Rust, making it suitable for AI and high-performance computing. The language is not yet open source, but the company has committed to open-sourcing it in 2026.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mojo_(programming_language)">Mojo (programming language) - Wikipedia</a></li>
<li><a href="https://docs.modular.com/mojo/manual/values/ownership/">Ownership - Mojo - Modular docs</a></li>
<li><a href="https://www.guvi.in/blog/modulars-mojo-programming-language/">Getting Started with Modular's Mojo Programming Language ...</a></li>

</ul>
</details>

**Discussion**: Community members are excited about Mojo's features like ownership and comptime, but some express concerns about compatibility with existing Python code and the delayed open-source timeline. Others note competition from Nvidia's CuTile and Triton, questioning Mojo's adoption prospects.

**Tags**: `#Mojo`, `#programming language`, `#machine learning`, `#performance`, `#open source`

---

<a id="item-7"></a>
## [Zcash to Launch Quantum-Recoverable Wallets, Go Quantum-Proof by 2027](https://www.coindesk.com/tech/2026/05/08/zcash-to-roll-out-quantum-recoverable-wallets-within-a-month-go-quantum-proof-by-2027) ⭐️ 8.0/10

Zcash announced plans to roll out quantum-recoverable wallets within a month and achieve full post-quantum security by 2027, as part of a roadmap presented on May 8, 2026. This is a significant step in cryptocurrency security, addressing the future threat of quantum computers breaking current cryptographic systems. Zcash's proactive approach could set a precedent for other privacy-focused blockchains. The quantum-recoverable wallets will serve as a safety and migration layer, allowing users to recover funds if quantum attacks emerge. The full transition to quantum-resistant standards within the protocol is targeted for 2027, with backward compatibility maintained.

rss · CoinDesk · May 8, 09:08

**Background**: Quantum computers, once sufficiently powerful, could break the elliptic curve cryptography used by most blockchains, including Zcash. Post-quantum cryptography aims to develop algorithms resistant to such attacks. Zcash's roadmap includes scaling to Visa- and Mastercard-level throughput alongside quantum security upgrades.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/05/08/zcash-to-roll-out-quantum-recoverable-wallets-within-a-month-go-quantum-proof-by-2027">Zcash to add quantum-recoverable wallets within a month, go post-quantum by 2027</a></li>
<li><a href="https://coinjournal.net/news/zcash-plans-quantum-resistant-upgrade-as-crypto-braces-for-future-risks/">Zcash plans quantum-resistant upgrade as crypto braces for future risks - CoinJournal</a></li>
<li><a href="https://u.today/zcash-2027-analyzing-quantum-roadmap-aiming-to-turn-zec-into-privacy-first-mastercard">Zcash 2027: Analyzing Quantum Roadmap Aiming to Turn ZEC Into 'Privacy-First Mastercard' - U.Today</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#quantum computing`, `#blockchain security`, `#Zcash`

---

<a id="item-8"></a>
## [Chrome Removes Privacy Promise for On-Device AI](https://decrypt.co/367193/chrome-removes-privacy-claim-gemini-nano-google) ⭐️ 8.0/10

Google's Chrome browser is quietly installing a 4GB on-device AI model (Gemini Nano) and has removed a privacy disclosure in Chrome 148 that previously promised not to send user data to Google servers. This change undermines user trust and raises serious privacy concerns, as a major browser silently installs AI and removes transparency about data handling, potentially affecting billions of users. The removal was first spotted by users on the Chrome subreddit and quickly spread to Hacker News. The on-device AI feature, Gemini Nano, is not available on mobile devices and currently supports English, Spanish, and Japanese from Chrome 140.

rss · Decrypt · May 7, 20:52

**Background**: On-device AI runs locally on a user's device without sending data to external servers, which is generally considered more private. Google's Gemini Nano is a lightweight AI model designed for tasks like text summarization and smart reply. The removed disclosure had explicitly stated that the feature would work 'without sending your data to Google servers.'

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/367193/chrome-removes-privacy-claim-gemini-nano-google">Chrome Deleted Its Own Privacy Promise for Sneaky... - Decrypt</a></li>
<li><a href="https://developer.chrome.com/docs/ai/get-started">Get started with built-in AI | AI on Chrome | Chrome for Developers</a></li>
<li><a href="https://chainbull.net/crypto/google-chromes-local-ai-model-raises-privacy-red-flags-in-latest-update/">Google Chrome 's Local AI Model Raises Privacy Red... - Chainbull</a></li>

</ul>
</details>

**Discussion**: The community reaction has been largely negative, with users expressing distrust and concern over Google's handling of privacy. Many are discussing workarounds to disable the AI feature and questioning the company's motives.

**Tags**: `#privacy`, `#Chrome`, `#AI`, `#Google`, `#browser`

---

<a id="item-9"></a>
## [AI Chatbots Leak User Data to Ad Trackers](https://decrypt.co/367164/your-ai-chatbot-leaking-chats-meta-tiktok-google) ⭐️ 8.0/10

A new study reveals that popular AI chatbots including ChatGPT, Claude, Grok, and Perplexity share user data with third-party ad trackers, sometimes even when users decline cookies. This privacy breach affects millions of users and undermines trust in AI chatbots, highlighting the need for stricter data protection regulations and transparency from AI companies. The study found data sharing occurs even after users opt out of cookies, and the trackers belong to major ad platforms like Meta, TikTok, and Google.

rss · Decrypt · May 7, 19:06

**Background**: Third-party ad trackers are scripts or pixels embedded in websites to collect user data for targeted advertising. AI chatbots often integrate such trackers for analytics or monetization, but users expect their conversations to remain private. Data leakage in AI systems can expose sensitive information without traditional hacking.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cyberly.org/en/what-are-third-party-trackers-and-how-do-they-work/index.html">What Are Third-Party Trackers, And How Do They Work?</a></li>
<li><a href="https://www.knostic.ai/blog/ai-data-leakage">Data Leakage Happens with GenAI. Here’s How to Stop It.</a></li>

</ul>
</details>

**Discussion**: Community comments are not provided, but the topic likely sparks concerns about privacy and calls for regulation.

**Tags**: `#privacy`, `#AI chatbots`, `#data leakage`, `#ad trackers`, `#security`

---

<a id="item-10"></a>
## [Tether's Medical AI Runs on Phone, Beats 16x Larger Models](https://decrypt.co/367127/tether-medical-ai-runs-on-phone-outperforms-models-16x) ⭐️ 8.0/10

Tether Data's AI Research group released QVAC MedPsy, a family of medical language models that run on smartphones and outperform Google's MedGemma-27B on real-world scenarios while using three times fewer compute resources. This breakthrough enables high-quality clinical AI to be deployed on edge devices like smartphones, making medical AI more accessible, private, and cost-effective, especially in resource-limited settings. QVAC MedPsy-4B produces accurate answers using 3.2 times fewer tokens than backbone models, and the model family includes efficient quantized versions for edge deployment.

rss · Decrypt · May 7, 16:01

**Background**: Large language models (LLMs) for medical applications typically require significant computational resources, limiting their deployment to cloud servers. Edge AI aims to run models locally on devices, reducing latency and improving privacy. Tether's QVAC MedPsy achieves state-of-the-art performance on medical tasks while being small enough to run on a smartphone.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/blog/qvac/medpsy">QVAC MedPsy : State-of-the-Art Medical and Healthcare Language...</a></li>
<li><a href="https://qvac.tether.io/models/">Models - QVAC by Tether</a></li>
<li><a href="https://www.bitrue.com/blog/what-is-qvac-medpsy">What Is QVAC MedPsy ?</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Medical AI`, `#Edge Computing`, `#Model Efficiency`, `#Mobile AI`

---

<a id="item-11"></a>
## [Google Boosts Local AI Speed 3x Without New Hardware](https://decrypt.co/367095/google-make-local-ai-3x-faster-no-new-hardware) ⭐️ 8.0/10

Google released Multi-Token Prediction (MTP) drafters for its Gemma 4 family of open-weight models, enabling up to 3x faster local inference without quality loss. This breakthrough makes powerful AI models practical on everyday devices, reducing reliance on cloud services and enhancing privacy for edge AI applications. The MTP drafters use speculative decoding, where a smaller draft model predicts multiple tokens at once, which are then verified by the main model, accelerating inference significantly.

rss · Decrypt · May 7, 14:13

**Background**: Large language models like Gemma 4 typically generate one token at a time, which is slow on local hardware. Speculative decoding speeds this up by using a draft model to propose multiple tokens, which the main model then accepts or rejects. Google's MTP drafters are specifically optimized for Gemma 4, achieving up to 3x speedups on consumer GPUs and CPUs.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/technology/developers-tools/multi-token-prediction-gemma-4/">Multi-token-prediction in Gemma 4 - The Keyword</a></li>
<li><a href="https://ai.google.dev/gemma/docs/mtp/overview">Speed-up Gemma 4 with Multi-Token Prediction - ai.google.dev</a></li>
<li><a href="https://claypier.com/en/gemma-4-mtp-drafter-launch/">Google Releases MTP Drafters for Gemma 4, Boosting Inference ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#machine learning`, `#Google`, `#edge computing`, `#inference optimization`

---

<a id="item-12"></a>
## [Meshtastic: Off-Grid LoRa Mesh Text Messaging](https://meshtastic.org/docs/introduction/) ⭐️ 7.0/10

Meshtastic is an open-source, LoRa-based mesh networking protocol that enables text messaging and data exchange over license-free ISM bands without cellular or internet infrastructure. It provides a practical, decentralized communication solution for off-grid scenarios such as outdoor adventures, emergency response, and remote communities, with growing adoption and active community development. Meshtastic operates in license-free bands (e.g., 868 MHz in Europe, 915 MHz in North America) with low power consumption and long range (up to 10+ miles in rural areas). It supports encryption, which is typically restricted in amateur radio, making it accessible to non-licensed users.

hackernews · ColinWright · May 8, 11:22 · [Discussion](https://news.ycombinator.com/item?id=48061566)

**Background**: LoRa (Long Range) is a spread-spectrum radio technology designed for low-power, long-range IoT communications. Mesh networking allows devices to relay messages to extend coverage. Meshtastic was created by Kevin Hester in 2020 and has since grown into a community-driven open-source project with hundreds of contributors.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Meshtastic">Meshtastic</a></li>
<li><a href="https://meshtastic.org/">Off-Grid Communication For Everyone | Meshtastic</a></li>
<li><a href="https://en.wikipedia.org/wiki/LoRa">LoRa - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community members are enthusiastic about real-world applications, such as sailboat communication in the South Pacific, and appreciate the low barrier to entry. Some express surprise that the technology is still limited to text messaging, while others note that it encourages ham radio licensing and fosters local radio clubs.

**Tags**: `#mesh networking`, `#LoRa`, `#decentralized communication`, `#ham radio`, `#IoT`

---

<a id="item-13"></a>
## [Judge Clears Aave to Move $71M ETH Linked to North Korea Hack](https://www.coindesk.com/policy/2026/05/09/judge-clears-path-for-aave-to-move-usd71-million-in-eth-linked-to-north-korea-hack) ⭐️ 7.0/10

A U.S. judge ruled that Aave, a decentralized lending protocol, can move $71 million in Ethereum allegedly linked to North Korean hackers, resolving a legal standoff over the frozen funds. This decision sets a legal precedent for how DeFi protocols handle funds suspected of being stolen by state-sponsored hackers, impacting security practices and regulatory clarity in the crypto ecosystem. The funds were frozen after being traced to the Lazarus Group, a North Korean state-sponsored hacking group, and Aave sought court approval to move them to mitigate risk and comply with regulations.

rss · CoinDesk · May 9, 04:16

**Background**: Aave is a decentralized finance (DeFi) protocol that allows users to lend and borrow cryptocurrencies. The Lazarus Group is a notorious North Korean hacking collective responsible for numerous crypto thefts, including the $1.4 billion Bybit hack in 2025. Frozen funds in DeFi often create legal and operational challenges due to the lack of central authority.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Aave">Aave - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lazarus_Group">Lazarus Group - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#regulatory`, `#crypto`, `#hacking`

---

<a id="item-14"></a>
## [SEC Chair Atkins Signals New Rules for Onchain Markets and AI Finance](https://www.coindesk.com/policy/2026/05/08/sec-chair-atkins-signals-new-rules-for-onchain-markets-ai-driven-finance) ⭐️ 7.0/10

SEC Chair Paul Atkins indicated that the agency will clarify how its regulatory framework applies to onchain markets and AI-driven finance, signaling a significant policy shift from the previous administration. This signals a potential new era of regulatory clarity for blockchain-based financial markets and AI-powered financial applications, which could spur innovation while ensuring investor protection. Atkins specifically mentioned the need to address how securities laws apply to software applications, and the SEC is considering rulemaking for trading systems and broker-dealers operating onchain.

rss · CoinDesk · May 8, 18:32

**Background**: Paul Atkins, a former SEC commissioner under President George W. Bush, was confirmed as SEC chair in 2025, replacing Gary Gensler. He has advocated for transparency and cost-benefit analysis in regulation. Onchain markets refer to trading and settlement activities conducted on blockchain networks, while AI-driven finance includes algorithmic trading, robo-advisors, and fraud detection systems.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/policy/2026/05/08/sec-chair-atkins-signals-new-rules-for-onchain-markets-ai-driven-finance">SEC chair Paul Atkins signals rule changes for onchain markets and...</a></li>
<li><a href="https://news.bitcoin.com/sec-targets-onchain-trading-rules-and-crypto-vault-oversight/">SEC Targets Onchain Trading Rules and Crypto Vault Oversight</a></li>
<li><a href="https://www.sec.gov/newsroom/press-releases/2025-68">SEC .gov | Paul S. Atkins Sworn In as SEC Chairman</a></li>

</ul>
</details>

**Tags**: `#SEC`, `#regulation`, `#blockchain`, `#AI`, `#finance`

---

<a id="item-15"></a>
## [Bitcoin Miner IREN Lands $3.4B Nvidia AI Deal](https://decrypt.co/367289/bitcoin-miner-iren-secures-3-4-billion-nvidia-ai-deal) ⭐️ 7.0/10

Bitcoin miner IREN has secured a $3.4 billion AI infrastructure deal with Nvidia, which includes an option for Nvidia to invest up to $2.1 billion in IREN shares. This deal highlights the growing convergence of cryptocurrency mining and AI infrastructure, as bitcoin miners leverage their energy and data center assets to meet surging demand for AI compute capacity. The deal includes a $2.1 billion share option for Nvidia, and IREN plans to build up to 5 GW of AI infrastructure. IREN, formerly known as Iris Energy, has pivoted from bitcoin mining to AI factory operations.

rss · Decrypt · May 8, 17:02

**Background**: Bitcoin miners like IREN have large power contracts and data centers originally built for crypto mining. As AI demand grows, these assets are being repurposed for high-performance computing, making miners key players in the AI infrastructure race.

<details><summary>References</summary>
<ul>
<li><a href="https://finance.yahoo.com/news/microsofts-97-billion-deal-with-iren-shows-bitcoin-miners-ai-pivot-is-paying-off-165316526.html">Microsoft's $9.7 billion deal with IREN shows bitcoin miners ' AI pivot...</a></li>
<li><a href="https://awesomeagents.ai/news/nvidia-iren-5gw-ai-infrastructure-deal/">NVIDIA Bets $2.1B on IREN to Build 5 GW AI ... | Awesome Agents</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Nvidia`, `#Bitcoin Mining`, `#Infrastructure`, `#Deal`

---

<a id="item-16"></a>
## [IMF Warns AI Will Supercharge Cyberattacks on Global Financial System](https://decrypt.co/367178/imf-warns-ai-supercharge-cyberattacks-global-financial-system) ⭐️ 7.0/10

The International Monetary Fund (IMF) has issued a warning that AI tools are enabling even unskilled attackers to breach critical financial infrastructure, and urged that cybersecurity be treated as a core stability issue. This warning highlights a growing systemic risk to the global financial system, as AI lowers the barrier for cyberattacks, potentially leading to widespread disruptions and loss of trust in financial institutions. The IMF's call comes amid reports that threat actors are using AI tools like Gemini to enhance every phase of cyberattacks, and that adaptable AI malware can rewrite code on the fly to evade detection.

rss · Decrypt · May 7, 19:44

**Background**: Critical infrastructure, including financial services, is increasingly targeted by cyberattacks. AI tools are now being used by both cybercriminals and nation-states to automate and improve attack techniques, making them more effective and harder to defend against. The IMF's warning underscores the need for stronger cybersecurity measures across the financial sector.

<details><summary>References</summary>
<ul>
<li><a href="https://cybernews.com/ai-news/threat-actors-abuse-ai-tools-cyberattacks-google-intel-warns/">Threat actors use AI tools to enhance cyberattacks | Cybernews</a></li>
<li><a href="https://home.treasury.gov/about/offices/domestic-finance/financial-institutions">Financial Institutions | U.S. Department of the Treasury Securing U.S. Critical Infrastructure against Evolving Cyber ... Critical Infrastructure Protection: National Cybersecurity ... Cybersecurity and Financial System Resilience Report Cybersecurity considerations 2025: Financial services sector Cybersecurity Awareness | FFIEC</a></li>
<li><a href="https://www.cisa.gov/news-events/news/cisa-unveils-new-initiative-fortify-americas-critical-infrastructure">CISA Unveils New Initiative to Fortify America’s Critical ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cybersecurity`, `#finance`, `#IMF`

---

<a id="item-17"></a>
## [Amazon, Coinbase, Stripe Enable AI Agents to Pay with Stablecoins](https://decrypt.co/367125/amazon-coinbase-stripe-ai-agents-pay-stablecoins) ⭐️ 7.0/10

Amazon Web Services has partnered with Coinbase and Stripe to allow AI agents to pay for APIs, data, and online services using the USDC stablecoin. This integration marks a significant step toward autonomous AI agents conducting real-world financial transactions, potentially revolutionizing how AI services are monetized and accessed. The system leverages USDC, a stablecoin pegged to the US dollar, to provide price stability for transactions. It combines AWS's cloud infrastructure with Coinbase's crypto payment rails and Stripe's payment processing.

rss · Decrypt · May 7, 16:32

**Background**: Stablecoins like USDC are cryptocurrencies designed to maintain a stable value, typically pegged to a fiat currency like the US dollar. AI agents are software programs that can autonomously perform tasks, and enabling them to make payments opens up new possibilities for automated services and machine-to-machine commerce.

<details><summary>References</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/industries/agentic-payments-the-next-evolution-in-the-payments-value-chain/">Agentic Payments: The Next Evolution in the Payments Value ...</a></li>
<li><a href="https://blog.payai.network/agentic-payments/">Agentic Payments: How AI Agents Pay, Transact, and Power the ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#stablecoins`, `#AWS`, `#fintech`, `#blockchain`

---

<a id="item-18"></a>
## [TrustedVolumes DeFi Exploit Drains $6.7M](https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit) ⭐️ 7.0/10

TrustedVolumes, a liquidity resolver used by multiple DeFi protocols, suffered a $6.7 million exploit. DEX aggregator 1inch stated that its systems were not impacted. This incident highlights ongoing security risks in DeFi infrastructure, particularly for shared liquidity resolvers. It could erode trust in such middleware and prompt protocols to audit their dependencies. The exploit's root cause involved lax permissionless signer controls, a common vulnerability in resolver systems. The same attacker had reportedly targeted TrustedVolumes before.

rss · Decrypt · May 7, 11:25

**Background**: TrustedVolumes is a liquidity resolver that aggregates liquidity from various sources for DeFi protocols. DEX aggregators like 1inch rely on such resolvers to find the best swap routes. When a resolver is compromised, it can affect multiple protocols that depend on it.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/367070/defi-platform-trustedvolumes-hit-by-6-7m-exploit">DeFi Platform TrustedVolumes Hit by $6.7M Exploit - Decrypt</a></li>
<li><a href="https://coinalertnews.com/news/2026/05/07/trustedvolumes-hack-1inch-denies">TrustedVolumes Suffers $6.7M DeFi Exploit, 1inch Denies Any...</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#exploit`, `#blockchain`

---

<a id="item-19"></a>
## [David Attenborough's 100th Birthday Celebrated](https://www.bbc.com/news/articles/cp3pww9g0p5o) ⭐️ 6.0/10

David Attenborough turned 100 years old, prompting a wave of tributes from the community sharing personal stories and reflections on his profound influence. Attenborough's documentaries have inspired generations to appreciate nature and pursue science, making his centenary a moment to recognize his lasting cultural and educational impact. Community comments highlight anecdotes such as Attenborough living in Richmond Hill, his suggestion to use yellow tennis balls for TV visibility, and Google displaying a special tribute with animal drawings.

hackernews · defrost · May 8, 12:03 · [Discussion](https://news.ycombinator.com/item?id=48061884)

**Background**: David Attenborough is a renowned British broadcaster and natural historian, best known for writing and presenting nature documentaries like 'Life on Earth' and 'Planet Earth'. His work has been credited with raising environmental awareness and inspiring scientific curiosity worldwide.

**Discussion**: Commenters express admiration for Attenborough's longevity and humility, with one noting he still lives in Richmond and signs books. Another credits him for the yellow tennis ball innovation, while others reflect on his role in inspiring scientists and engineers.

**Tags**: `#David Attenborough`, `#tribute`, `#cultural impact`, `#nature documentaries`

---

<a id="item-20"></a>
## [io_uring ZCRX Freelist LPE Exploit](https://ze3tar.github.io/post-zcrx.html) ⭐️ 6.0/10

A local privilege escalation exploit for the Linux kernel has been published that leverages an out-of-bounds write in the io_uring zero-copy RX freelist, allowing an attacker to gain root access. This exploit highlights ongoing security challenges in the io_uring subsystem, a high-performance I/O interface, and underscores the importance of proper bounds checking in kernel code. The exploit requires both CAP_NET_ADMIN and CAP_SYS_ADMIN capabilities, which are already elevated privileges, and it may have been patched in recent stable kernels according to io_uring maintainer Jens Axboe.

hackernews · MrBruh · May 8, 19:40 · [Discussion](https://news.ycombinator.com/item?id=48067734)

**Background**: io_uring is a Linux kernel interface for asynchronous I/O that reduces system call overhead. Zero-copy RX allows network packets to be received directly into userspace memory, avoiding a copy. The freelist is a pool of buffers used for this purpose; a flaw in its management can lead to out-of-bounds writes.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.kernel.org/next/networking/iou-zcrx.html">io_uring zero copy Rx — The Linux Kernel documentation</a></li>
<li><a href="https://seclists.org/oss-sec/2026/q2/362">oss-sec: CVE request: io _ uring zcrx freelist OOB write</a></li>
<li><a href="https://www.man7.org/linux/man-pages/man7/capabilities.7.html">capabilities (7) - Linux manual page - man7.org</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the exploit requires already elevated capabilities, reducing its practical severity. Some questioned the novelty, pointing to a similar exploit from months prior. Others observed a recent surge in Linux LPE disclosures.

**Tags**: `#Linux`, `#kernel exploit`, `#io_uring`, `#LPE`, `#security`

---

<a id="item-21"></a>
## [Running a Website from RAM on Raspberry Pi Zero](https://btxx.org/posts/memory/) ⭐️ 6.0/10

A guide demonstrates serving a website entirely from RAM on a Raspberry Pi Zero, using Alpine Linux and offloading TLS termination to a cloud provider for improved performance. This approach reduces SD card wear and improves reliability for low-power self-hosting, though it relies on external TLS handling, which may limit full self-sufficiency. The Pi Zero has only 512MB of RAM, with about 40MB used by Alpine Linux, leaving enough for a small website. TLS is handled by a cloud provider, saving CPU cycles on the Pi.

hackernews · xngbuilds · May 8, 15:10 · [Discussion](https://news.ycombinator.com/item?id=48064312)

**Background**: Raspberry Pi Zero is a low-cost, low-power single-board computer often used for lightweight servers. Running from RAM (tmpfs) avoids SD card wear and improves speed, but data is lost on power loss. TLS offloading moves encryption overhead to a cloud service, which is common for reducing load on constrained devices.

<details><summary>References</summary>
<ul>
<li><a href="https://btxx.org/posts/memory/">Serving a Website on a Raspberry Pi Zero Running Entirely in RAM</a></li>
<li><a href="https://forums.raspberrypi.com/viewtopic.php?t=136771">Using RAM disk instead of a SD - Raspberry Pi Forums</a></li>
<li><a href="https://www.huntress.com/cybersecurity-101/topic/ssl-offloading">What is SSL Offloading ? Security Guide for IT Professionals | Huntress</a></li>

</ul>
</details>

**Discussion**: Commenters noted that offloading TLS to a cloud provider reduces CPU load but questioned the novelty, as similar setups are common. Some shared experiences with Alpine Linux on Pi Zero, highlighting its stability and low memory usage.

**Tags**: `#Raspberry Pi`, `#self-hosting`, `#RAM disk`, `#TLS`, `#embedded systems`

---

<a id="item-22"></a>
## [Kraken Parent Seeks OCC Charter for Federal Crypto Bank](https://www.coindesk.com/policy/2026/05/08/kraken-parent-goes-for-the-occ-charter-in-big-to-become-a-federal-crypto-bank) ⭐️ 6.0/10

Kraken's parent company has applied for a U.S. federal banking charter from the Office of the Comptroller of the Currency (OCC) to become a federal crypto bank, complementing its existing Wyoming Special Purpose Depository Institution (SPDI) subsidiary. If approved, this would mark a significant regulatory milestone, allowing Kraken to operate as a federally chartered bank with crypto custody and fiat deposit capabilities, potentially setting a precedent for other crypto firms seeking federal oversight. The OCC charter would provide Kraken with federal preemption over state laws and access to the Federal Reserve's payment system, while the Wyoming SPDI charter already allows it to custody digital assets and accept fiat deposits under state law.

rss · CoinDesk · May 8, 17:00

**Background**: The OCC charters and regulates national banks and federal savings associations in the U.S. A federal banking charter provides a single regulatory framework, preempting state-level requirements. Wyoming's SPDI framework is a state-level charter specifically designed for digital asset businesses, offering custody and deposit services but not full commercial banking powers.

<details><summary>References</summary>
<ul>
<li><a href="https://www.occ.gov/topics/charters-and-licensing/index-charters-licensing.html">Charters & Licensing | OCC</a></li>
<li><a href="https://www.kraken.com/learn/finance/spdi-bank-charter">What is the SPDI Charter? | SPDI Framework | Kraken</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#regulation`, `#banking`, `#Kraken`

---

<a id="item-23"></a>
## [ECB's Lagarde warns against copying U.S. stablecoin model](https://www.coindesk.com/business/2026/05/08/ecb-s-lagarde-warns-tether-and-circle-stablecoins-risk-digital-dollarisation-in-europe) ⭐️ 6.0/10

ECB President Christine Lagarde warned that adopting the U.S. stablecoin model in Europe could lead to digital dollarization, undermining the euro's monetary sovereignty. This highlights the ECB's strategic push for a digital euro as a sovereign alternative to private stablecoins, which could reshape Europe's payment landscape and financial autonomy. Lagarde specifically referenced Tether and Circle's stablecoins as examples of instruments that could facilitate digital dollarization if widely adopted in Europe.

rss · CoinDesk · May 8, 16:11

**Background**: Stablecoins are cryptocurrencies pegged to a stable asset like the U.S. dollar, often used for trading and payments. The digital euro is a central bank digital currency (CBDC) being developed by the ECB to provide a secure, state-backed digital payment option. Digital dollarization refers to the risk that foreign stablecoins could replace the euro in digital transactions, reducing monetary control.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tandfonline.com/doi/full/10.1080/2329194X.2025.2552378">The digital dollarization dilemma: Stablecoins and monetary ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Digital_euro">Digital euro</a></li>
<li><a href="https://www.investopedia.com/terms/s/stablecoin.asp">Stablecoins: Definition, How They Work, and Types - Investopedia</a></li>

</ul>
</details>

**Tags**: `#digital euro`, `#stablecoins`, `#ECB`, `#financial policy`, `#Europe`

---

<a id="item-24"></a>
## [Senate Banking Committee to Vote on Crypto Bill](https://www.theblock.co/post/400492/take-two-senate-banking-committee-sets-a-date-to-amend-and-vote-on-sweeping-crypto-legislation?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

The Senate Banking Committee has scheduled a hearing to amend and vote on comprehensive crypto legislation, marking a second attempt to advance the bill. This vote could shape the regulatory landscape for cryptocurrencies in the U.S., affecting how digital assets are classified and overseen. The legislation is described as sweeping, but specific provisions have not been detailed in the available content. The hearing is a procedural step toward potential enactment.

rss · The Block · May 8, 23:24

**Background**: The Senate Banking Committee oversees financial regulation, including digital assets. Previous attempts at crypto legislation have stalled, making this vote a key test of bipartisan support.

**Tags**: `#crypto`, `#regulation`, `#legislation`, `#Senate`

---

<a id="item-25"></a>
## [TeraWulf's HPC Revenue Tops Bitcoin Mining for First Time](https://www.theblock.co/post/400578/terawulfs-21-million-hpc-revenue-surpasses-bitcoin-mining-first-time-q1?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

TeraWulf reported Q1 2026 revenue of $21 million from high-performance computing (HPC) and AI hosting, surpassing its bitcoin mining revenue of under $13 million for the first time. This marks a significant industry shift as a former pure-play bitcoin miner successfully pivots to AI and HPC services, potentially inspiring other miners to diversify their revenue streams. The company's total Q1 revenue was $34 million, but it also reported a net loss of over $427 million, partly due to impairment charges. TeraWulf's pivot reflects a broader trend of bitcoin miners repurposing infrastructure for AI workloads.

rss · The Block · May 8, 15:37

**Background**: TeraWulf, founded in 2021 by energy sector veterans, initially focused on bitcoin mining using low-cost energy. As mining profitability declined and AI demand surged, many miners began retrofitting data centers for HPC and AI hosting. This quarter's results show the pivot is financially viable.

<details><summary>References</summary>
<ul>
<li><a href="https://crypto.news/terawulfs-hpc-revenue-tops-bitcoin-mining-for-first-time-as-ai-pivot-accelerates/">TeraWulf’s HPC revenue tops Bitcoin mining for first time as AI pivot...</a></li>
<li><a href="https://en.wikipedia.org/wiki/TeraWulf">TeraWulf - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#bitcoin mining`, `#HPC`, `#AI`, `#revenue`, `#industry trend`

---

<a id="item-26"></a>
## [Arbitrum DAO Approves $70M ETH Release for Kelp DAO Recovery](https://www.theblock.co/post/400527/arbitrum-dao-approves-eth-release?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Arbitrum DAO has approved the release of approximately $70 million in ETH to aid the recovery of Kelp DAO, which suffered a $292 million exploit in April 2026. However, a May 1 court order restricts the movement of these funds, and Aave has filed an emergency motion to lift the restraining notice. This decision highlights the complex interplay between decentralized governance (DAO votes) and legal systems, as a court order can override community-approved actions. It also underscores the challenges in recovering stolen funds in DeFi, where multiple protocols and jurisdictions are involved. The $70 million in ETH was frozen after the Kelp DAO exploit, and Arbitrum DAO voted to release it to victims. Aave's emergency motion argues that the restraining notice harms its users and seeks to unfreeze the funds, while the court order remains in place.

rss · The Block · May 8, 07:25

**Background**: Arbitrum is a Layer 2 scaling solution for Ethereum, and its DAO governs the protocol's treasury and upgrades. Kelp DAO is a liquid restaking protocol that was exploited for $292 million in April 2026, with funds stranded across multiple chains. Aave is a lending protocol that filed an emergency motion to protect its users' interests, as the frozen ETH includes funds deposited by Aave users.

<details><summary>References</summary>
<ul>
<li><a href="https://cointelegraph.com/news/aave-asks-court-to-lift-restraining-notice-on-frozen-kelp-exploit-ether">Aave files emergency motion to lift restraining notice on ...</a></li>
<li><a href="https://www.banklesstimes.com/articles/2026/05/05/aave-llc-files-emergency-bid-to-void-arbitrums-71m-eth-restraining-notice/">Aave Files Emergency Motion to Unfreeze $71M Arbitrum ETH</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#DAO`, `#Arbitrum`, `#Ethereum`, `#Governance`

---

<a id="item-27"></a>
## [Solv Protocol Switches from LayerZero to Chainlink for $700M BTC](https://www.theblock.co/post/400520/solv-protocol-layerzero-chainlink?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Solv Protocol is migrating its $700 million tokenized bitcoin from LayerZero to Chainlink CCIP, citing security concerns after a $290 million exploit on LayerZero-powered Kelp DAO. This migration signals growing distrust in LayerZero's security model among major DeFi protocols, potentially reshaping the cross-chain infrastructure landscape and driving adoption of Chainlink's CCIP. The decision follows a $290 million exploit of Kelp DAO in April 2026, where attackers compromised LayerZero's default single-verifier setup. Solv Protocol manages over $700 million in total value locked (TVL) of tokenized bitcoin.

rss · The Block · May 8, 02:17

**Background**: Solv Protocol is a DeFi platform that enables liquid staking and yield generation for idle Bitcoin across multiple blockchains. LayerZero is a cross-chain messaging protocol, while Chainlink CCIP is a competing interoperability standard. The Kelp DAO exploit highlighted risks in relying on LayerZero's default security configurations.

<details><summary>References</summary>
<ul>
<li><a href="https://layerzero.network/blog/kelpdao-incident-statement">KelpDAO Incident Statement | LayerZero</a></li>
<li><a href="https://daotimes.com/kelp-dao-abandons-layerzero-for-chainlink-after-a-292m-bridge-hack/">Kelp DAO Abandons LayerZero for Chainlink After a $292M ...</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#Blockchain`, `#Security`, `#Tokenization`

---