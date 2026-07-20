---
layout: default
title: "Horizon Summary: 2026-07-20 (EN)"
date: 2026-07-20
lang: en
---

> From 33 items, 13 important content pieces were selected

---

1. [Bowling Center Owner Replaces $120k System with $1,600 ESP32s](#item-1) ⭐️ 9.0/10
2. [Claude Fable Produces Counterexample to Jacobian Conjecture](#item-2) ⭐️ 9.0/10
3. [Claude Code Now Uses Bun, Rewritten in Rust](#item-3) ⭐️ 8.0/10
4. [Alibaba Announces Qwen 3.8, 2.4T Parameter Open-Weights LLM](#item-4) ⭐️ 8.0/10
5. [Zcash Unveils Node Targeting Visa-Scale Privacy at 50K TPS](#item-5) ⭐️ 8.0/10
6. [Allbridge Core pauses after $1.65M flash loan exploit](#item-6) ⭐️ 8.0/10
7. [Hardware Is Not So Hard: Lessons from Selling 2,500 MIDI Recorders](#item-7) ⭐️ 7.0/10
8. [Minecraft: Java Edition Switches to SDL3](#item-8) ⭐️ 7.0/10
9. [Orion Browser by Kagi: Mixed Reviews on Bugs and Polish](#item-9) ⭐️ 6.0/10
10. [Developer Shares IndieWeb Journey and Lessons Learned](#item-10) ⭐️ 6.0/10
11. [Bitcoin Quantum Recovery Tool Excludes Satoshi's Coins](#item-11) ⭐️ 6.0/10
12. [France Orders ISPs to Block Polymarket](#item-12) ⭐️ 6.0/10
13. [Trump Targets Brazil's Pix as Stablecoins Gain Ground](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Bowling Center Owner Replaces $120k System with $1,600 ESP32s](https://news.ycombinator.com/item?id=48968606) ⭐️ 9.0/10

A bowling center owner built a fully functional scoring and control system for 8 lanes using ESP32 microcontrollers, costing only $1,600 compared to the $80k–$120k commercial replacement. The open-source project, called OpenLaneLink, uses ESPNow mesh networking, Redis event streaming, and a React frontend. This demonstrates a massive cost reduction (75x) for retrofitting legacy industrial systems with modern embedded hardware, challenging vendor lock-in in niche markets. It could inspire similar DIY replacements in bowling alleys and other industries with expensive proprietary systems. The system uses ESP32 nodes with ESPNow star-topology mesh and RS485 wired fallback, connected to a Raspberry Pi running Redis and a state machine. Each lane pair costs about $200 in hardware, and repairs can be done in under 10 minutes by swapping a pre-flashed controller.

hackernews · section33 · Jul 19, 14:41

**Background**: Commercial bowling scoring systems are proprietary, expensive, and often require vendor support for repairs and upgrades. The ESP32 is a low-cost microcontroller with built-in Wi-Fi and Bluetooth, widely used in IoT projects. Retrofitting legacy equipment with modern embedded systems is a growing trend to reduce costs and increase flexibility.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ESP32">ESP32 - Wikipedia</a></li>
<li><a href="https://sesamedisk.com/diy-bowling-system-esp32-replacement/">Replacing $120K Bowling System with $1,600 - Sesame Disk</a></li>
<li><a href="https://promwad.com/news/retrofit-industrial-equipment-iot-security">Retrofitting Legacy Industrial Equipment with IoT: Protocol Bridges and Security Pitfalls</a></li>

</ul>
</details>

**Discussion**: Commenters shared similar experiences retrofitting old machine tools and mechanical bowling lanes, praising the project's cost savings and open-source approach. Some discussed adding LED lighting, DMX control, and kiosk payment integration, showing enthusiasm for further innovation.

**Tags**: `#embedded systems`, `#retrofit`, `#ESP32`, `#cost reduction`, `#legacy systems`

---

<a id="item-2"></a>
## [Claude Fable Produces Counterexample to Jacobian Conjecture](https://xcancel.com/__alpoge__/status/2079028340955197566) ⭐️ 9.0/10

Anthropic's Claude Fable model reportedly generated a counterexample to the Jacobian Conjecture, a long-standing unsolved problem in algebraic geometry, as shared by a user on X (formerly Twitter). This marks a significant milestone in AI-assisted mathematical research, demonstrating that large language models can contribute to solving or disproving open problems. It could accelerate progress in automated theorem proving and inspire new approaches to longstanding conjectures. The Jacobian Conjecture states that if a polynomial map has a constant non-zero Jacobian determinant, then it has a polynomial inverse. The counterexample was reportedly produced by Claude Fable 5, the latest model in Anthropic's Claude series, which is known for its strong capabilities in long-horizon tasks.

hackernews · loubbrad · Jul 20, 02:51 · [Discussion](https://news.ycombinator.com/item?id=48973869)

**Background**: The Jacobian Conjecture is a famous problem in algebraic geometry and commutative algebra, first stated in 1884 for two variables and generalized in 1939. It is notorious for many flawed proofs. Claude Fable 5 is a state-of-the-art large language model developed by Anthropic, released after a more powerful but restricted version called Claude Mythos.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Jacobian_conjecture">Jacobian conjecture</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable">Claude Fable</a></li>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism, with one user noting that the Jacobian Conjecture has many flawed proofs and suggesting the LLM might have synthesized a counterexample from prior erroneous work. Another comment humorously hopes the LLM could settle the Collatz conjecture next, saving many wasted efforts.

**Tags**: `#LLM`, `#mathematics`, `#AI research`, `#Jacobian conjecture`, `#automated theorem proving`

---

<a id="item-3"></a>
## [Claude Code Now Uses Bun, Rewritten in Rust](https://simonwillison.net/2026/Jul/19/claude-code-in-bun-in-rust/) ⭐️ 8.0/10

Claude Code, Anthropic's AI coding agent, now uses the Bun JavaScript runtime, which has been rewritten from Zig to Rust. This change was merged as a massive pull request in less than a month. This shift impacts the JavaScript runtime ecosystem and highlights the growing role of AI in large-scale software rewrites. It also raises questions about project governance and engineering maturity, as Bun is now owned by Anthropic. The rewritten Bun is not yet publicly released; Claude Code ships a preview of Bun v1.4.0, while the latest public release is v1.3.14. The rewrite was motivated by the need to automate memory management, which Rust handles automatically compared to Zig.

hackernews · tosh · Jul 19, 10:03 · [Discussion](https://news.ycombinator.com/item?id=48966569)

**Background**: Bun is a fast all-in-one JavaScript runtime, bundler, test runner, and package manager, designed as a drop-in replacement for Node.js. Claude Code is Anthropic's agentic coding tool that lives in the terminal and helps developers write code faster. The original Bun was written in Zig, a low-level systems programming language.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bun_(software)">Bun (software) - Wikipedia</a></li>
<li><a href="https://github.com/oven-sh/bun">GitHub - oven-sh/bun: Incredibly fast JavaScript runtime, bundler, test runner, and package manager – all in one</a></li>
<li><a href="https://docs.anthropic.com/en/docs/claude-code/overview">Claude Code overview - Anthropic</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some praise the technical rationale for switching to Rust, while others criticize the communication and governance around the rewrite. There is also skepticism about using a JavaScript runtime for a terminal UI, and concern that Bun as an open-source project may be effectively abandoned.

**Tags**: `#Bun`, `#Rust`, `#Claude Code`, `#JavaScript runtime`, `#AI-assisted development`

---

<a id="item-4"></a>
## [Alibaba Announces Qwen 3.8, 2.4T Parameter Open-Weights LLM](https://twitter.com/Alibaba_Qwen/status/2078759124914098291) ⭐️ 8.0/10

Alibaba has announced Qwen 3.8, a 2.4 trillion parameter open-weights large language model, in direct response to Moonshot AI's recently unveiled 2.8T parameter Kimi K3 model. This announcement intensifies competition in the open-weights LLM space, potentially accelerating innovation and providing developers with more powerful, accessible models. The rivalry between Alibaba and Moonshot AI could lead to better performance and lower costs for end users. Qwen 3.8 has 2.4 trillion parameters, while Kimi K3 has 2.8 trillion parameters; both are open-weights models. Alibaba plans to release Qwen 3.8's weights publicly, though the exact date is not yet specified.

hackernews · nh43215rgb · Jul 19, 08:44 · [Discussion](https://news.ycombinator.com/item?id=48966120)

**Background**: Large language models (LLMs) are AI systems trained on vast text data to generate human-like text. Parameters are the internal weights learned during training; more parameters generally indicate greater capacity and potential performance. Open-weights models allow developers to download and fine-tune the model weights, offering more control and customization than closed APIs.

<details><summary>References</summary>
<ul>
<li><a href="https://platform.kimi.ai/docs/guide/kimi-k3-quickstart">Kimi K 3 - Kimi API Platform</a></li>
<li><a href="https://www.bbc.com/news/articles/cy9w4q8pgp0o">China's Moonshot AI claims Kimi K 3 can rival OpenAI and Anthropic</a></li>
<li><a href="https://galileo.ai/blog/llm-parameters-model-evaluation">Essential LLM Parameters Every AI Team Needs | Galileo</a></li>

</ul>
</details>

**Discussion**: The community is excited about the competition, with many users hoping for smaller model variants for local use. However, some users report poor experiences with previous Qwen models, citing usability issues and high cost compared to DeepSeek. Others anticipate upcoming releases from DeepSeek as well.

**Tags**: `#LLM`, `#open-weights`, `#Alibaba`, `#Qwen`, `#AI competition`

---

<a id="item-5"></a>
## [Zcash Unveils Node Targeting Visa-Scale Privacy at 50K TPS](https://www.coindesk.com/tech/2026/07/16/inside-zcash-s-new-node-that-targets-visa-scale-privacy-at-50-000-transactions-per-second) ⭐️ 8.0/10

Zcash announced a new node capable of processing 50,000 transactions per second while preserving privacy, aiming to rival Visa's transaction throughput. This milestone demonstrates that blockchain privacy and scalability can coexist at Visa-scale levels, potentially enabling private payments for mainstream adoption. The node leverages advanced zero-knowledge proof techniques to achieve high throughput without compromising privacy, though specific implementation details remain undisclosed.

rss · CoinDesk · Jul 19, 05:37

**Background**: Zcash is a privacy-focused cryptocurrency that uses zero-knowledge proofs (zk-SNARKs) to shield transaction details. Historically, privacy coins have struggled with scalability, often processing far fewer transactions per second than centralized payment systems like Visa, which handles thousands of TPS. This announcement suggests a breakthrough in combining privacy with high throughput.

<details><summary>References</summary>
<ul>
<li><a href="https://zcash.readthedocs.io/en/latest/rtd_pages/zcashd.html">Zcash Full Node and CLI — Zcash Documentation...</a></li>
<li><a href="https://github.com/ZcashFoundation/zebra">GitHub - ZcashFoundation/zebra: Zcash - Financial Privacy in Rust</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-knowledge_proof">Zero-knowledge proof - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#privacy`, `#scalability`, `#Zcash`, `#cryptocurrency`

---

<a id="item-6"></a>
## [Allbridge Core pauses after $1.65M flash loan exploit](https://www.theblock.co/post/408855/allbridge-core-exploit?utm_source=rss&utm_medium=rss) ⭐️ 8.0/10

Allbridge Core, a cross-chain stablecoin bridge, has paused its protocol after a flash loan exploit resulted in a loss of approximately $1.65 million. Security firms PeckShield and CertiK reported that the attacker bridged the stolen funds from Solana to Ethereum. This incident highlights ongoing security vulnerabilities in cross-chain bridges, which are critical infrastructure in DeFi. The rapid response from security firms underscores the importance of monitoring and quick action to mitigate further damage. The attacker used a flash loan to manipulate the protocol's liquidity pools, draining $1.65 million. The stolen funds were then bridged from Solana to Ethereum, making them harder to trace.

rss · The Block · Jul 20, 03:33

**Background**: Flash loan attacks are a type of DeFi exploit where an attacker borrows large amounts of cryptocurrency without collateral within a single transaction, using the borrowed funds to manipulate prices or exploit protocol weaknesses. Allbridge Core is a cross-chain bridge that facilitates native stablecoin transfers between blockchains without wrapping tokens, relying on native liquidity pools.

<details><summary>References</summary>
<ul>
<li><a href="https://hacken.io/discover/flash-loan-attacks/">Flash Loan Attacks: How They Work, Real Examples, and How to Prevent Them</a></li>
<li><a href="https://docs-core.allbridge.io/">What is Allbridge Core? | Allbridge Core</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#flash loan`, `#blockchain`, `#exploit`

---

<a id="item-7"></a>
## [Hardware Is Not So Hard: Lessons from Selling 2,500 MIDI Recorders](https://chipweinberger.com/articles/20260719-hardware-is-not-so-hard) ⭐️ 7.0/10

A hardware entrepreneur shares lessons from successfully selling 2,500 units of a simple MIDI recorder, arguing that hardware development is not as difficult as commonly perceived if the product is kept simple. This article provides practical, counterintuitive insights for aspiring hardware entrepreneurs, challenging the prevailing narrative that hardware is inherently hard and offering a blueprint for low-risk hardware product development. The author emphasizes keeping the bill of materials low (25 components) and using off-the-shelf parts to minimize complexity and cost. The product is a simple MIDI recorder that records to a microSD card, avoiding certification requirements by not including wireless radios.

hackernews · chipweinberger · Jul 19, 10:34 · [Discussion](https://news.ycombinator.com/item?id=48966713)

**Background**: MIDI (Musical Instrument Digital Interface) is a standard protocol that allows electronic musical instruments, computers, and audio devices to communicate and synchronize with each other. A MIDI recorder captures MIDI data (note events, control changes) rather than audio, enabling musicians to edit and replay performances. Hardware product development typically involves design, prototyping, testing, certification (e.g., FCC for wireless devices), and manufacturing, which can be costly and complex.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/MIDI">MIDI - Wikipedia</a></li>
<li><a href="https://learn.sparkfun.com/tutorials/midi-tutorial/all">MIDI Tutorial - SparkFun Learn</a></li>

</ul>
</details>

**Discussion**: Commenters generally appreciate the article's practical advice but raise important caveats: certification (FCC, CE) is a major cost and hurdle for products with radios, and scaling from hundreds to millions of units introduces new challenges. Some also note that the simplicity of this specific product (25 components, no radio) is not representative of most hardware projects.

**Tags**: `#hardware`, `#entrepreneurship`, `#product design`, `#MIDI`

---

<a id="item-8"></a>
## [Minecraft: Java Edition Switches to SDL3](https://www.minecraft.net/en-us/article/minecraft-26-3-snapshot-4) ⭐️ 7.0/10

Minecraft: Java Edition has adopted SDL3, the latest major version of the Simple DirectMedia Layer library, in its latest snapshot. This change replaces the previous SDL2-based input and windowing system. This update improves cross-platform compatibility and performance for one of the world's most popular games. It also demonstrates SDL3's readiness for large-scale production use, encouraging other developers to migrate. The migration was made possible by LWJGL bindings contributed by a member of the GTNH modpack team. Known issues include crashes in exclusive fullscreen mode on Windows with multiple monitors and on Wayland.

hackernews · ObviouslyFlamer · Jul 19, 11:48 · [Discussion](https://news.ycombinator.com/item?id=48967256)

**Background**: SDL (Simple DirectMedia Layer) is a cross-platform library that provides low-level access to audio, keyboard, mouse, and graphics hardware. SDL3, released in January 2025, is a major update with improved APIs and better performance. Minecraft: Java Edition uses LWJGL (Lightweight Java Game Library) to bind native libraries like SDL.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SDL_library">SDL library</a></li>
<li><a href="https://wiki.libsdl.org/">SDL Wiki: SDL3/FrontPage</a></li>
<li><a href="https://www.phoronix.com/news/SDL3-Built-In-Snake-Game">SDL 3 Library Adds A Built-In Snake Game - Phoronix</a></li>

</ul>
</details>

**Discussion**: Community members shared migration experiences, with one developer noting a mostly painless refactor from GLFW to SDL3 but encountering issues with fullscreen modes. Another commenter expressed concern that known exclusive fullscreen crashes on Windows and Wayland could be blocking bugs for a snapshot release.

**Tags**: `#Minecraft`, `#SDL3`, `#game development`, `#open source`

---

<a id="item-9"></a>
## [Orion Browser by Kagi: Mixed Reviews on Bugs and Polish](https://orionbrowser.com/) ⭐️ 6.0/10

Orion Browser by Kagi offers built-in ad-blocking and vertical tabs, but user feedback highlights significant bugs and lack of polish, especially on mobile and Linux beta. Orion represents a privacy-focused alternative to mainstream browsers, but its current instability may hinder adoption among users seeking a reliable daily driver. The browser uses WebKit rendering engine and is available on macOS, iOS, and Linux beta. Some users report broken settings pages and missing features like 'Search for...' on text selection.

hackernews · sebjones · Jul 19, 19:13 · [Discussion](https://news.ycombinator.com/item?id=48970894)

**Background**: Kagi is a paid ad-free search engine company that also develops Orion Browser. Orion aims to provide a fast, private browsing experience with built-in ad blocking and vertical tabs, competing with browsers like Safari and Firefox.

<details><summary>References</summary>
<ul>
<li><a href="https://orionbrowser.com/">Orion Browser by Kagi</a></li>
<li><a href="https://blog.kagi.com/orion-features">Kagi Blog - Orion browser features</a></li>
<li><a href="https://en.wikipedia.org/wiki/Kagi_(search_engine)">Kagi (search engine)</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed: some users praise Orion's ad-blocking and tab management, while others report persistent bugs and lack of polish. A few users have abandoned Orion due to issues, but some daily drivers find it stable enough.

**Tags**: `#web browser`, `#Kagi`, `#ad-blocking`, `#privacy`, `#beta software`

---

<a id="item-10"></a>
## [Developer Shares IndieWeb Journey and Lessons Learned](https://en.andros.dev/blog/0b8e451e/i-joined-the-indieweb-heres-what-i-learned/) ⭐️ 6.0/10

A developer documented their experience joining the IndieWeb movement, covering the technical setup and philosophical motivations behind owning their own content. This personal account highlights the practical challenges and rewards of adopting IndieWeb principles, which could inspire more people to take control of their online presence and reduce reliance on centralized platforms. The article discusses using static site generators, webmentions, and POSSE (Publish on Your Own Site, Syndicate Elsewhere) to integrate with social media, but notes the technical complexity involved.

hackernews · andros · Jul 19, 11:14 · [Discussion](https://news.ycombinator.com/item?id=48966984)

**Background**: The IndieWeb is a community-driven movement that advocates for individuals to own their own data and identity on personal websites, rather than relying on corporate platforms like Facebook or Twitter. Key concepts include POSSE and webmentions for cross-site interactions. The movement emphasizes user control and content ownership.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/IndieWeb">IndieWeb - Wikipedia</a></li>
<li><a href="https://indieweb.org/">IndieWeb</a></li>

</ul>
</details>

**Discussion**: Comments highlight usability concerns: one user argues the technical complexity makes IndieWeb unworkable for most people, while others praise the approach and suggest alternatives like Nostr or Indiekit. Another comment reflects on the appeal of self-expression versus platform convenience.

**Tags**: `#IndieWeb`, `#decentralization`, `#web development`, `#social media`

---

<a id="item-11"></a>
## [Bitcoin Quantum Recovery Tool Excludes Satoshi's Coins](https://www.coindesk.com/tech/2026/07/19/bitcoin-s-quantum-problem-gets-a-recovery-tool-but-not-for-satoshi-s-1-1-million-coin) ⭐️ 6.0/10

Bitcoin developers have proposed a commit/reveal recovery tool using zero-knowledge proofs to protect wallets from quantum attacks, but it cannot recover Satoshi Nakamoto's 1.1 million bitcoins due to their unique address format lacking a derivation path. This tool represents a significant step toward quantum-resistant security for Bitcoin, but the exclusion of Satoshi's coins raises questions about the long-term safety of the oldest addresses and the broader implications for Bitcoin's security model. The recovery tool relies on a derivation path that is absent in Satoshi's early addresses (starting with '1'), making them incompatible. The tool uses zero-knowledge proofs to allow users to prove ownership and recover funds without exposing private keys.

rss · CoinDesk · Jul 19, 10:00

**Background**: Quantum computers, once powerful enough, could break Bitcoin's elliptic curve cryptography, threatening private key security. Bitcoin addresses have evolved over time, with newer formats like SegWit (starting with '3' or 'bc1') supporting more advanced features. Satoshi's coins are stored in old Pay-to-Public-Key-Hash (P2PKH) addresses that lack a derivation path, making them incompatible with modern recovery mechanisms.

<details><summary>References</summary>
<ul>
<li><a href="https://cryptobriefing.com/bitcoin-quantum-attack-recovery-tool/">Bitcoin introduces recovery tool for quantum attack vulnerabilities</a></li>
<li><a href="https://www.hokanews.com/2026/07/bitcoin-quantum-recovery-tool-offers.html">Bitcoin Quantum Recovery Tool Offers Hope for Vulnerable Wallets - HOKANEWS.COM</a></li>
<li><a href="https://cryptonews.net/news/bitcoin/33171555/">Bitcoin Quantum Recovery Tool Proves Feasible—but Satoshi’s 1.1 Million BTC Still Lack Protection</a></li>

</ul>
</details>

**Discussion**: The community is divided: some see the tool as a necessary precaution, while others debate whether Satoshi's coins should be considered a donation to the quantum future or a ticking clock for Bitcoin's security. Core developers regularly discuss the implications of leaving those coins unprotected.

**Tags**: `#Bitcoin`, `#quantum computing`, `#cryptography`, `#blockchain`

---

<a id="item-12"></a>
## [France Orders ISPs to Block Polymarket](https://www.coindesk.com/policy/2026/07/18/france-orders-country-s-internet-service-providers-to-block-polymarket) ⭐️ 6.0/10

France has ordered its internet service providers to block access to Polymarket, a cryptocurrency-based prediction market platform, citing violations of national gambling laws. This action highlights increasing regulatory scrutiny on decentralized prediction markets, especially as Polymarket's World Cup markets are among the largest event contracts in history. It may set a precedent for other countries considering similar bans. The order takes effect ahead of the World Cup final, which will settle Polymarket's largest event markets. Polymarket has already been banned in several jurisdictions, including Brazil and Italy, and was previously blocked in the United States.

rss · CoinDesk · Jul 18, 21:52

**Background**: Polymarket is an American-founded, Panama-domiciled platform that allows users to bet on outcomes using cryptocurrency on the Polygon blockchain. It has faced criticism for enabling gambling on sensitive events like military conflicts and for instances of insider trading. The platform is not labeled as sports betting, yet 63% of trades are sports-related.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Polymarket">Polymarket</a></li>

</ul>
</details>

**Tags**: `#regulation`, `#cryptocurrency`, `#blockchain`, `#France`

---

<a id="item-13"></a>
## [Trump Targets Brazil's Pix as Stablecoins Gain Ground](https://www.coindesk.com/business/2026/07/18/trump-targets-brazil-s-payments-system-while-dollar-stablecoins-quietly-dominate-country-s-payments) ⭐️ 6.0/10

Dollar stablecoins are increasingly used for payments in Brazil, even as political actions target the local Pix payment system. This trend could undermine Brazil's sovereign payment system and challenge U.S. dollar dominance in digital finance, affecting global payments and geopolitics. Pix processes 8.6 times more transaction value than credit and debit cards combined, with over 200 million monthly active users. Stablecoins offer a programmable, dollar-pegged alternative.

rss · CoinDesk · Jul 18, 16:09

**Background**: Pix is Brazil's instant payment system launched by the central bank, widely adopted with mandatory participation and zero pricing. Dollar stablecoins are cryptocurrencies pegged to the U.S. dollar, used for payments and value storage, especially in countries with currency instability.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pix_(payment_system)">Pix (payment system) - Wikipedia</a></li>
<li><a href="https://www.okx.com/en-ae/learn/stablecoins-dollar-global-finance">Stablecoins and the Dollar : How They’re Reshaping... | OKX UAE</a></li>
<li><a href="https://www.cfr.org/articles/why-china-spooked-dollar-stablecoins-and-how-it-will-respond">Why China Is Spooked by Dollar Stablecoins and How It Will Respond</a></li>

</ul>
</details>

**Tags**: `#stablecoins`, `#payments`, `#geopolitics`, `#cryptocurrency`

---