---
layout: default
title: "Horizon Summary: 2026-05-18 (EN)"
date: 2026-05-18
lang: en
---

> From 30 items, 9 important content pieces were selected

---

1. [Semble: Code search for AI agents with 98% fewer tokens](#item-1) ⭐️ 8.0/10
2. [KelpDAO $293M hack forces DeFi to mature](#item-2) ⭐️ 8.0/10
3. [Verus-Ethereum Bridge Exploit Drains $11.6 Million](#item-3) ⭐️ 8.0/10
4. [Turning $80 RK3562 Android Tablet into Debian Workstation](#item-4) ⭐️ 7.0/10
5. [Tesla Solar Roof Falters, Pivots to Panels](#item-5) ⭐️ 7.0/10
6. [GitHub List of CUDA Books Sparks Critical Reviews](#item-6) ⭐️ 6.0/10
7. [Jump Crypto's Firedancer Takes Cautious Approach to Solana Rollout](#item-7) ⭐️ 6.0/10
8. [Circle Unveils Arc: A Layer-1 Blockchain for Stablecoins](#item-8) ⭐️ 6.0/10
9. [AI Jailbreaking: A Beginner's Guide to the Cat-and-Mouse Game](#item-9) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Semble: Code search for AI agents with 98% fewer tokens](https://github.com/MinishLab/semble) ⭐️ 8.0/10

Semble is an open-source code search tool that combines static Model2Vec embeddings with BM25, achieving 98% fewer tokens than grep+read while maintaining 99% of the retrieval quality of a 137M-parameter transformer. It runs entirely on CPU with no GPU or API keys required. This addresses a critical bottleneck for AI coding agents: excessive token usage when searching large codebases. By drastically reducing token consumption, Semble can lower costs and improve response times for tools like Claude Code, Cursor, and Codex. Semble indexes a typical repo in ~250ms and queries in ~1.5ms on CPU, using a custom static embedding model (potion-code-16M) with only 16M parameters. It fuses BM25 and embedding scores via Reciprocal Rank Fusion (RRF) and applies code-aware reranking.

hackernews · Bibabomas · May 17, 15:37 · [Discussion](https://news.ycombinator.com/item?id=48169874)

**Background**: AI coding agents often use grep to find relevant code, which reads entire files and consumes many tokens. Traditional semantic search tools rely on transformer-based embeddings that require GPUs and are slow to index. Semble uses static embeddings (Model2Vec) that are precomputed and fast, combined with BM25 for keyword matching.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.weaviate.io/weaviate/model-providers/model2vec/embeddings">Text Embeddings | Weaviate Documentation</a></li>
<li><a href="https://en.wikipedia.org/wiki/Okapi_BM25">Okapi BM 25 - Wikipedia</a></li>
<li><a href="https://medium.com/@devalshah1619/mathematical-intuition-behind-reciprocal-rank-fusion-rrf-explained-in-2-mins-002df0cc5e2a">Reciprocal Rank Fusion ( RRF ) explained in 4 mins — How... | Medium</a></li>

</ul>
</details>

**Discussion**: Community comments raised concerns about AI agents potentially becoming 'dumber' by relying on such tools, and whether agents trust results from non-grep tools. Some users compared Semble to existing solutions like Cursor's workspace indexing and noted the need for agent benchmarks to validate real-world token savings.

**Tags**: `#code search`, `#AI agents`, `#token efficiency`, `#open source`, `#retrieval`

---

<a id="item-2"></a>
## [KelpDAO $293M hack forces DeFi to mature](https://www.coindesk.com/tech/2026/05/16/the-usd293-million-kelpdao-hack-shows-why-defi-is-finally-being-forced-to-grow-up) ⭐️ 8.0/10

On April 18, 2026, attackers linked to North Korea's Lazarus Group stole approximately $293 million (116,500 rsETH) from KelpDAO's LayerZero bridge, exploiting off-chain infrastructure rather than smart contract bugs. This incident highlights that DeFi's biggest vulnerabilities are shifting from smart contract bugs to infrastructure, governance, and operational security, as protocols become deeply interconnected through bridges. The attack was not a smart contract exploit but a sophisticated attack on off-chain infrastructure, tricking the bridge into releasing tokens that should not have been released.

rss · CoinDesk · May 16, 13:00

**Background**: DeFi (Decentralized Finance) protocols often use bridges to transfer assets between different blockchains. These bridges are critical infrastructure but can be vulnerable to attacks on their off-chain components, such as validators or relayers. The KelpDAO hack is one of the largest DeFi exploits, underscoring the need for improved security practices across the ecosystem.

<details><summary>References</summary>
<ul>
<li><a href="https://www.chainalysis.com/blog/kelpdao-bridge-exploit-april-2026/">Inside the KelpDAO Bridge Exploit</a></li>
<li><a href="https://www.coindesk.com/tech/2026/05/16/the-usd293-million-kelpdao-hack-shows-why-defi-is-finally-being-forced-to-grow-up">Ethereum news (ETH): The $293 million KelpDAO hack shows why DeFi is finally being forced to grow up</a></li>
<li><a href="https://www.galaxy.com/insights/research/kelpdao-layerzero-exploit-defi">KelpDAO/LayerZero Hack: $290m Exploit Exposes DeFi’s Hidden Risks | Galaxy</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#security`, `#hack`, `#KelpDAO`, `#cryptocurrency`

---

<a id="item-3"></a>
## [Verus-Ethereum Bridge Exploit Drains $11.6 Million](https://www.theblock.co/post/401571/verus-ethereum-bridge-exploit?utm_source=rss&utm_medium=rss) ⭐️ 8.0/10

An ongoing exploit has drained approximately $11.6 million from the Verus-Ethereum bridge, as flagged by blockchain security firms Peckshield and Blockaid. The attacker stole 103.6 tBTC, 1,625 ETH, and 147,000 USDC. This incident highlights the ongoing security vulnerabilities in cross-chain bridges, which are critical infrastructure for DeFi interoperability. The loss adds to a growing list of bridge exploits, undermining user trust in cross-chain solutions. The attacker's address has been identified as 0x5aBb…D5777 by Blockaid. The exploit is ongoing, meaning further losses may occur before the vulnerability is patched.

rss · The Block · May 18, 02:54

**Background**: Cross-chain bridges allow users to transfer assets between different blockchains, such as moving Bitcoin to Ethereum via wrapped tokens like tBTC. However, these bridges are complex and often become targets for hackers due to security flaws. tBTC is a token fully backed by Bitcoin, enabling BTC holders to use their assets on Ethereum-based DeFi protocols.

<details><summary>References</summary>
<ul>
<li><a href="https://beincrypto.com/verus-bridge-exploit-may-defi-hacks/">Crypto Hack Wave Hits Verus Bridge as May DeFi Losses Mount</a></li>
<li><a href="https://www.coindesk.com/markets/2026/05/18/yet-another-crypto-bridge-falls-victim-to-an-usd11-million-hack">Verus-Ethereum bridge loses $11 million as hackers keep ...</a></li>
<li><a href="https://www.theblock.co/post/401571/verus-ethereum-bridge-exploit">Ongoing exploit drains $11.6 million from Verus-Ethereum ...</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#security`, `#exploit`, `#cryptocurrency`

---

<a id="item-4"></a>
## [Turning $80 RK3562 Android Tablet into Debian Workstation](https://github.com/tech4bot/rk3562deb) ⭐️ 7.0/10

A hobbyist published a guide to install a pre-release Debian 12 image on an $80 Android tablet powered by the Rockchip RK3562, enabling Linux boot without modifying internal storage. This demonstrates the potential to repurpose cheap Android hardware into functional Linux devices, expanding access to Linux for hobbyists and reducing e-waste. The tablet has only 4GB RAM, which may limit multitasking; the guide uses Debian Bookworm (12) rather than Trixie (13) for stability, and the boot process does not require unlocking the bootloader.

hackernews · tech4bot · May 17, 13:16 · [Discussion](https://news.ycombinator.com/item?id=48168668)

**Background**: Rockchip RK3562 is a quad-core Cortex-A55 processor often used in low-cost Android tablets. Installing a full Linux distribution on such devices typically requires custom firmware or bootloader modifications, but this method bypasses those steps.

<details><summary>References</summary>
<ul>
<li><a href="https://techtrendtrove.com/tablets/i-turned-a-80-rk3562-android-tablet-into-a-debian-linux-workstation-2/">I turned a $80 RK3562 Android tablet into a Debian Linux workstation</a></li>
<li><a href="https://bestcadpapers.com/tips-hacks-miscellaneous/i-turned-a-80-rk3562-android-tablet-into-a-debian-linux-workstation/">I turned a $80 RK3562 Android tablet into a Debian Linux workstation</a></li>

</ul>
</details>

**Discussion**: Commenters debated the usability of 4GB RAM, with some noting it's sufficient for lightweight tasks like terminal-based development or emulation, while others expressed concern about limited multitasking. There was also interest in using AI to reverse-engineer similar devices for broader porting efforts.

**Tags**: `#Linux`, `#Embedded Systems`, `#Hardware Hacking`, `#Debian`, `#Tablet`

---

<a id="item-5"></a>
## [Tesla Solar Roof Falters, Pivots to Panels](https://electrek.co/2026/05/14/tesla-solar-roof-promise-vs-reality-pivot-panels/) ⭐️ 7.0/10

Tesla is reportedly pivoting away from its Solar Roof product due to high costs and execution challenges, refocusing on traditional solar panels. The Solar Roof costs about $106,000 before incentives, compared to $60,000 for a roof plus panels, with a payback period of 15-25 years versus 7-12 years. This shift highlights the difficulty of integrating solar into building materials at scale, and may reshape the residential solar market by reinforcing the dominance of conventional panels. It also raises questions about Tesla's broader energy strategy and its ability to execute on ambitious product visions. The Solar Roof's premium of $46,000 over a traditional roof plus panels made it economically unviable for most homeowners. Tesla's execution issues included underestimating the importance of service and long-term support, as noted in community comments.

hackernews · celsoazevedo · May 17, 04:09 · [Discussion](https://news.ycombinator.com/item?id=48165980)

**Background**: Tesla's Solar Roof was introduced as a premium product that replaces traditional roofing tiles with solar-generating tiles, aiming to combine aesthetics with energy production. However, the rooftop solar market has grown through low-cost, quick-installation systems, making expensive integrated solutions less competitive.

**Discussion**: Community comments express disappointment but note that the failure stems from execution and economics, not the concept itself. Some point out that visible solar panels are becoming more socially acceptable, reducing the aesthetic advantage of the Solar Roof.

**Tags**: `#Tesla`, `#solar energy`, `#business strategy`, `#renewable energy`

---

<a id="item-6"></a>
## [GitHub List of CUDA Books Sparks Critical Reviews](https://github.com/alternbits/awesome-cuda-books) ⭐️ 6.0/10

A GitHub repository called 'awesome-cuda-books' curates a list of CUDA programming books, but community comments highlight that many older books are outdated and recommend modern alternatives like Warp and a video by CUDA architect Stephen Jones. This discussion helps learners avoid investing time in outdated resources and points them toward up-to-date, effective learning materials for GPU programming, which is critical for fields like AI and high-performance computing. The repository lists books such as 'CUDA by Example' and 'Programming Massively Parallel Processors', but commenters note that these books contain errors or are too simplistic. Modern alternatives include NVIDIA's Warp for writing CUDA kernels in Python and a comprehensive video by a CUDA architect.

hackernews · dariubs · May 17, 12:52 · [Discussion](https://news.ycombinator.com/item?id=48168485)

**Background**: CUDA is NVIDIA's parallel computing platform and programming model for GPUs. Learning CUDA traditionally involves reading books, but the field evolves rapidly with new hardware architectures. The GitHub list serves as a starting point, but community feedback is essential for identifying current best practices.

<details><summary>References</summary>
<ul>
<li><a href="https://www.amazon.com/CUDA-Example-Introduction-General-Purpose-Programming/dp/0131387685">CUDA by Example: An Introduction to General-Purpose GPU...</a></li>
<li><a href="https://bookauthority.org/books/best-selling-cuda-books">7 Best-Selling CUDA Books Millions Love - BookAuthority</a></li>
<li><a href="https://shop.elsevier.com/books/cuda-programming/cook/978-0-12-415933-4">CUDA Programming - 1st Edition | Elsevier Shop</a></li>

</ul>
</details>

**Discussion**: Commenters generally agree that older CUDA books are outdated and recommend newer resources. One user praises 'CUDA Programming: A Developer's Guide' as the best intro, while another points to a video by CUDA architect Stephen Jones. A third user highlights Warp as a modern Python-based alternative.

**Tags**: `#CUDA`, `#GPU Programming`, `#Parallel Computing`, `#Books`

---

<a id="item-7"></a>
## [Jump Crypto's Firedancer Takes Cautious Approach to Solana Rollout](https://www.coindesk.com/tech/2026/05/16/jump-crypto-s-firedancer-is-taking-a-slow-and-steady-approach-to-its-long-awaited-solana-infrastructure-rollout) ⭐️ 6.0/10

Jump Crypto's Firedancer, a new Solana validator client written in C, is proceeding with a slow and steady rollout to mainnet, prioritizing reliability and security over speed. The lead engineer stated in a CoinDesk interview that the team is taking a cautious approach to ensure network stability. Firedancer aims to significantly improve Solana's transaction processing efficiency and network resilience, potentially enabling over 1 million TPS. Its cautious rollout reflects the importance of infrastructure reliability for a high-performance blockchain like Solana, and its eventual full deployment could enhance the network's competitiveness. Firedancer is written entirely in C and uses a highly parallel, tiled architecture to achieve high throughput. An intermediate milestone has been released to enable testing before full implementation, and a security audit by Neodyme has been completed.

rss · CoinDesk · May 16, 15:00

**Background**: Solana is a high-performance blockchain that relies on validator clients to process transactions. Currently, the primary client is written in Rust, and Firedancer is a new third-party client designed to improve performance and decentralization. Jump Crypto, the crypto arm of trading firm Jump Trading, has been developing Firedancer for several years.

<details><summary>References</summary>
<ul>
<li><a href="https://jumpcrypto.com/build/firedancer">Firedancer - jumpcrypto.com</a></li>
<li><a href="https://www.coindesk.com/tech/2026/05/16/jump-crypto-s-firedancer-is-taking-a-slow-and-steady-approach-to-its-long-awaited-solana-infrastructure-rollout">Solana news (SOL): Jump Crypto’s ‘Firedancer’ is taking a ...</a></li>
<li><a href="https://www.kraken.com/learn/what-is-firedancer-solana">What is Firedancer , and why is it big for Solana ? | Kraken</a></li>

</ul>
</details>

**Tags**: `#Solana`, `#blockchain`, `#infrastructure`, `#crypto`

---

<a id="item-8"></a>
## [Circle Unveils Arc: A Layer-1 Blockchain for Stablecoins](https://decrypt.co/resources/what-is-arc-the-stablecoin-blockchain-from-usdc-issuer-circle) ⭐️ 6.0/10

Circle, the issuer of USDC, announced Arc, a new EVM-compatible layer-1 blockchain that uses USDC as the native gas token for transaction fees. Arc could reshape stablecoin finance by eliminating reliance on third-party blockchains, potentially reducing costs and improving efficiency for USDC-based transactions and tokenized assets. Arc is designed specifically for stablecoin-native finance and tokenized assets, and Circle has raised $222 million from investors including BlackRock and a16z at a $3 billion valuation for the project.

rss · Decrypt · May 17, 20:32

**Background**: Stablecoins like USDC are typically issued on existing blockchains such as Ethereum or Solana, relying on those networks for transaction processing. Arc is a dedicated layer-1 blockchain that integrates USDC natively, meaning USDC is used for gas fees and is not a bridged token. This approach aims to create a more efficient and integrated ecosystem for stablecoin-based financial applications.

<details><summary>References</summary>
<ul>
<li><a href="https://news.bitcoin.com/circle-unveils-arc-blockchain-with-usdc-as-native-gas/">Circle Unveils Arc Blockchain With USDC as Native Gas</a></li>
<li><a href="https://www.okx.com/en-ae/learn/arc-blockchain-regulation-circle-layer1">Arc Blockchain Regulation: How Circle ’s New... | OKX UAE</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#stablecoin`, `#Circle`, `#layer-1`

---

<a id="item-9"></a>
## [AI Jailbreaking: A Beginner's Guide to the Cat-and-Mouse Game](https://decrypt.co/resources/what-is-ai-jailbreaking-explained) ⭐️ 6.0/10

This article provides a beginner-friendly overview of AI jailbreaking, explaining how techniques like prompt injection bypass safety filters in large language models (LLMs). It traces the concept from iPhone jailbreaking via Cydia to modern LLM exploits. Understanding AI jailbreaking is crucial for AI safety, as these exploits can cause LLMs to generate harmful or restricted content. This arms race between attackers and developers affects trust and security in AI applications used by millions. Common jailbreaking methods include role-playing prompts, encoding requests in base64, and using narrative framing to trick the model. Indirect prompt injection can also occur when LLMs browse the web and process adversarial content embedded in websites.

rss · Decrypt · May 16, 13:01

**Background**: AI jailbreaking refers to techniques that manipulate large language models (LLMs) to bypass their built-in safety and ethical restrictions. It originated from the concept of jailbreaking iPhones to remove software restrictions, popularized by tools like Cydia. In the AI context, attackers craft special prompts that cause the model to ignore its training safeguards and produce prohibited outputs.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_jailbreaking">AI jailbreaking</a></li>
<li><a href="https://www.promptfoo.dev/blog/how-to-jailbreak-llms/">Jailbreaking LLMs: A Comprehensive Guide... | Promptfoo</a></li>
<li><a href="https://www.lakera.ai/blog/jailbreaking-large-language-models-guide">Jailbreaking Large Language Models: Techniques, Examples...</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#jailbreaking`, `#LLM`, `#security`

---