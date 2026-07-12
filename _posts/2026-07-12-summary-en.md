---
layout: default
title: "Horizon Summary: 2026-07-12 (EN)"
date: 2026-07-12
lang: en
---

> From 57 items, 17 important content pieces were selected

---

1. [Nvidia's Circular Financing in GPU Boom](#item-1) ⭐️ 8.0/10
2. [Grok Build CLI Uploads Entire Repos to xAI](#item-2) ⭐️ 8.0/10
3. [UPI Architecture Deep Dive: Design, Scalability, Impact](#item-3) ⭐️ 8.0/10
4. [Bonzo Loses 77% TVL in $9M Oracle Exploit on Hedera](#item-4) ⭐️ 8.0/10
5. [AI Discovers Ethereum Bug That Could Knock Validators Offline](#item-5) ⭐️ 8.0/10
6. [Mesh LLM: Distributed AI Computing on Iroh](#item-6) ⭐️ 7.0/10
7. [ClickHouse Scales PgBouncer 4x with Peering](#item-7) ⭐️ 7.0/10
8. [US Housing Law Bans Federal Reserve CBDC Until 2030](#item-8) ⭐️ 7.0/10
9. [Apple Sues OpenAI Over Stolen Trade Secrets](#item-9) ⭐️ 7.0/10
10. [Cambridge: 31% of Ethereum nodes in US, third offline could stall finalization](#item-10) ⭐️ 7.0/10
11. [Laser Attack Resets Tangem Wallet Passwords](#item-11) ⭐️ 7.0/10
12. [Ant: A New All-in-One JavaScript Runtime and Ecosystem](#item-12) ⭐️ 6.0/10
13. [Crypto Giants Back Dispute Resolution Court for AI Agents](#item-13) ⭐️ 6.0/10
14. [Robinhood Chain: Ethereum L2 for Tokenized Stocks](#item-14) ⭐️ 6.0/10
15. [Xbox CEO Joins Fed AI Task Force Amid Layoffs](#item-15) ⭐️ 6.0/10
16. [Circle Wins Final OCC Approval for National Trust Bank](#item-16) ⭐️ 6.0/10
17. [Revolut X Integrates AI Assistants for Crypto Trading](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Nvidia's Circular Financing in GPU Boom](https://io-fund.com/ai-stocks/nvidia-coreweave-nebius-circular-financing-gpu-boom) ⭐️ 8.0/10

An analysis reveals that Nvidia's investments in cloud providers CoreWeave and Nebius may constitute circular financing, where Nvidia funds customers who then buy its GPUs, but the practice is also a strategic hedge against hyperscalers. This matters because circular financing could inflate demand for Nvidia's GPUs, creating systemic risk if the AI infrastructure buildout proves unprofitable. It also highlights Nvidia's strategy to reduce dependence on hyperscalers like AWS and Azure. Nvidia invested $2 billion in CoreWeave for a 9% equity stake, while CoreWeave plans $35 billion in CapEx in 2026, making Nvidia's investment only 5.7% of that year's spending. Nebius, another Nvidia-backed cloud, recently secured a $17.4 billion contract with Microsoft.

hackernews · adletbalzhanov · Jul 11, 17:21 · [Discussion](https://news.ycombinator.com/item?id=48873836)

**Background**: Circular financing is a loop where an investor provides capital to a company, which then spends that money on the investor's own products. In the AI boom, Nvidia, CoreWeave, and Nebius exemplify this: Nvidia invests in cloud providers, who use the funds to buy Nvidia GPUs. This dynamic raises questions about genuine demand versus artificial stimulation.

<details><summary>References</summary>
<ul>
<li><a href="https://builtin.com/articles/ai-circular-financing">How Circular Financing Is Fueling the AI Boom | Built In</a></li>
<li><a href="https://blogs.cuit.columbia.edu/gjb2124/circular-financing/">The Hidden Risk in AI's Circular Financing Ecosystem</a></li>
<li><a href="https://en.wikipedia.org/wiki/CoreWeave">CoreWeave - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters debate whether the circular financing claim is overblown, noting Nvidia's $2B investment is small relative to CoreWeave's $35B CapEx. Others focus on economic viability, suggesting metrics like ROI per token and enterprise token budgets are more important than financing structure.

**Tags**: `#Nvidia`, `#GPU`, `#cloud computing`, `#financing`, `#AI infrastructure`

---

<a id="item-2"></a>
## [Grok Build CLI Uploads Entire Repos to xAI](https://gist.github.com/cereblab/dc9a40bc26120f4540e4e09b75ffb547) ⭐️ 8.0/10

An analysis reveals that xAI's Grok Build CLI uploads the entire repository contents, including .env files and git history, to xAI servers, regardless of what the agent reads. This raises serious privacy and security concerns for developers using the tool, as sensitive data like API keys and secrets may be transmitted without explicit consent, potentially enabling mass surveillance. The CLI transmits file contents verbatim and unredacted, including .env secrets files, and the upload is independent of what the agent reads, meaning the entire repository is sent even if only a subset is needed.

hackernews · jhoho · Jul 12, 01:09 · [Discussion](https://news.ycombinator.com/item?id=48877371)

**Background**: Grok Build is a terminal-native AI coding agent launched by xAI in May 2026, designed to assist developers with coding tasks. It is part of the Grok chatbot ecosystem developed by Elon Musk's xAI. The CLI tool is intended to improve productivity but has raised privacy concerns due to its data handling practices.

<details><summary>References</summary>
<ul>
<li><a href="https://x.ai/cli">Grok Build Beta | SpaceXAI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Grok_(chatbot)">Grok (chatbot) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community expressed shock and concern, with users noting that this behavior is extremely concerning and reminiscent of mass surveillance. Some suggested sandboxing tools like bubblewrap to mitigate risks, while others argued that proprietary coding agents are inherently dangerous for privacy.

**Tags**: `#privacy`, `#security`, `#AI tools`, `#xAI`, `#developer tools`

---

<a id="item-3"></a>
## [UPI Architecture Deep Dive: Design, Scalability, Impact](https://timeseriesofindia.com/economy/reads/upi-architecture/) ⭐️ 8.0/10

A detailed article explores the architecture of India's Unified Payments Interface (UPI), covering its design principles, scalability, and impact on digital payments. This analysis helps developers and architects understand how UPI handles billions of transactions reliably, offering lessons for building large-scale payment systems globally. The article notes UPI processes 22 billion transactions annually, averaging ~700 QPS at the NPCI switch, with peak loads much higher. It also discusses the trade-offs of a centralized, KYC-based system.

hackernews · prtk25 · Jul 11, 16:33 · [Discussion](https://news.ycombinator.com/item?id=48873457)

**Background**: UPI is a real-time payment system developed by the National Payments Corporation of India (NPCI) that facilitates inter-bank transactions through mobile phones. It uses a unique identifier called a UPI ID and supports both push (pay) and pull (collect) transactions. The system has been widely adopted in India, enabling digital payments even among non-tech-savvy users.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Unified_Payments_Interface">Unified Payments Interface - Wikipedia</a></li>
<li><a href="https://medium.com/@avinashkariya05910/deep-dive-system-design-of-upi-unified-payments-interface-eff3b0334b0d">Deep Dive: System Design of UPI (Unified Payments Interface) | by Avinash Kariya | Medium</a></li>
<li><a href="https://razorpay.com/blog/what-is-upi-and-how-it-works/">What is UPI?: Unified Payments Interface Features and How UPI Works?</a></li>

</ul>
</details>

**Discussion**: Commenters praised the article's quality and the crore/billion toggle feature. Some expressed concerns about centralization and KYC, while others marveled at UPI's success in onboarding elderly users. A comparison with US/European payment systems was also requested.

**Tags**: `#UPI`, `#payment systems`, `#architecture`, `#India`, `#digital payments`

---

<a id="item-4"></a>
## [Bonzo Loses 77% TVL in $9M Oracle Exploit on Hedera](https://www.coindesk.com/web3/2026/07/11/lending-protocol-bonzo-loses-77-of-value-locked-as-usd9-million-oracle-exploit-rattles-hedera) ⭐️ 8.0/10

Bonzo Lend, the largest lending protocol on Hedera, lost approximately $9.05 million after an attacker exploited a flaw in Supra's oracle verifier to manipulate the price of SAUCE tokens, causing a 77% drop in total value locked. This incident highlights critical vulnerabilities in DeFi oracle systems, especially on emerging blockchains like Hedera, and underscores the need for robust security measures to protect user funds. The exploit involved a second wallet that borrowed about $1 million but identified itself as a white hat hacker and promised to return the funds. Bonzo is powered by Aave v2 smart contracts adapted to Hedera.

rss · CoinDesk · Jul 11, 18:06

**Background**: Bonzo Finance is a decentralized lending protocol built on Hedera, using Aave v2 smart contracts. Oracles like Supra provide price feeds to DeFi protocols; if manipulated, attackers can exploit price discrepancies to drain funds. The SAUCE token is a native asset on Hedera.

<details><summary>References</summary>
<ul>
<li><a href="https://cointelegraph.com/news/bonzo-lend-9m-oracle-exploit-hedera">Oracle Exploit Drains $9M From Bonzo Lend on Hedera</a></li>
<li><a href="https://bitcoinworld.co.in/bonzo-lend-oracle-exploit-hedera/">Bonzo Lend Loses $9M In Oracle Exploit On Hedera Blockchain</a></li>
<li><a href="https://blockonomi.com/hederas-largest-lending-protocol-bonzo-loses-9m-in-oracle-exploit/">Hedera ’s Largest Lending Protocol, Bonzo, Loses $9M in Oracle Exploit</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#oracle exploit`, `#Hedera`, `#security`, `#lending protocol`

---

<a id="item-5"></a>
## [AI Discovers Ethereum Bug That Could Knock Validators Offline](https://www.coindesk.com/tech/2026/07/10/ai-found-an-ethereum-bug-that-could-take-validators-offline-but-humans-had-to-prove-it) ⭐️ 8.0/10

AI agents coordinated by the Ethereum Foundation discovered a critical vulnerability in Ethereum's libp2p gossipsub implementation that could force validators offline, but human researchers had to manually verify and confirm the exploit before it was assigned CVE-2026-34219. This marks a real-world demonstration of AI's potential in blockchain security, while also highlighting its current limitations—AI can flag issues, but human expertise remains essential for validation. The bug could have caused staking penalties and operational risks for node operators if exploited. The vulnerability resides in the networking layer's gossipsub protocol, which Ethereum nodes use to communicate. While isolated validator downtime is tolerated by Ethereum's consensus, the bug becomes more dangerous if remotely triggerable or present in widely used client implementations, increasing the risk of correlated outages.

rss · CoinDesk · Jul 11, 12:00

**Background**: Ethereum validators are nodes that stake ETH to participate in consensus and secure the network. The gossipsub protocol is part of libp2p, a modular network stack used by Ethereum clients to propagate messages. AI agents were deployed by the Ethereum Foundation to automatically hunt for bugs in critical software, but they still require human oversight to confirm real exploits.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/07/10/ai-found-an-ethereum-bug-that-could-take-validators-offline-but-humans-had-to-prove-it">AI found an Ethereum bug that could take validators offline ...</a></li>
<li><a href="https://cryptobriefing.com/ethereum-foundation-ai-protocol-bugs-cve/">Ethereum Foundation says AI found real protocol bugs, but ...</a></li>
<li><a href="https://www.crowdfundinsider.com/2026/07/290812-ethereum-foundation-highlights-ais-role-in-bug-detection-while-emphasizing-human-oversight-in-security-audits/">Ethereum Foundation Highlights AI's Role In Bug Detection ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Ethereum`, `#blockchain security`, `#bug detection`, `#validators`

---

<a id="item-6"></a>
## [Mesh LLM: Distributed AI Computing on Iroh](https://www.iroh.computer/blog/mesh-llm) ⭐️ 7.0/10

Mesh LLM is a new distributed inference system that splits large language models across multiple nodes using the iroh networking library, enabling collaborative AI computation. The project is open-source and experimental, with a contributor actively answering community questions. This approach democratizes access to large models by allowing users with modest hardware to pool resources for inference, potentially reducing reliance on expensive centralized infrastructure. It also explores peer-to-peer AI, which could enable new applications in privacy-sensitive or offline environments. The system uses a custom 'skippy' engine to split models across nodes, and performance numbers show Qwen 235B MoE achieving 16 tokens per second across 2 nodes. However, community members note that consumer network speeds are significantly slower than local memory, raising concerns about latency.

hackernews · tionis · Jul 11, 22:38 · [Discussion](https://news.ycombinator.com/item?id=48876505)

**Background**: Distributed inference splits AI model computations across multiple devices to handle models too large for a single machine. Iroh is a networking library that simplifies peer-to-peer connections, making it easier to build distributed applications. Mesh LLM leverages iroh to coordinate model sharding and inference across nodes.

<details><summary>References</summary>
<ul>
<li><a href="https://www.iroh.computer/blog/mesh-llm">Mesh LLM: distributed AI computing on iroh - Iroh</a></li>
<li><a href="https://github.com/Mesh-LLM/mesh-llm">GitHub - Mesh-LLM/mesh-llm: Distributed AI/LLM for the people ...</a></li>
<li><a href="https://www.iroh.computer/">iroh</a></li>

</ul>
</details>

**Discussion**: Community members expressed interest in using distributed inference for small, purpose-built models rather than large coding LLMs. Performance concerns were raised, with one user noting that even 10 Gbit Ethernet is slow compared to local RAM, but the contributor provided a benchmark of 16 tok/s for Qwen 235B across 2 nodes.

**Tags**: `#distributed computing`, `#LLM`, `#inference`, `#iroh`, `#AI`

---

<a id="item-7"></a>
## [ClickHouse Scales PgBouncer 4x with Peering](https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres) ⭐️ 7.0/10

ClickHouse detailed how they scaled PgBouncer to 4x throughput by implementing a peering mechanism that forwards query cancellation requests to the correct process. This allows multiple PgBouncer processes to share a single port via so_reuseport and coordinate cancellations. This innovation turns PgBouncer from a bottleneck into a scalable component, enabling higher throughput for PostgreSQL connection pooling on multi-core machines. It directly benefits users running large-scale PostgreSQL deployments who need efficient query cancellation across multiple pooler processes. The peering mechanism ensures that a cancel request landing on the wrong process is forwarded to the one owning the session. ClickHouse runs a fleet of PgBouncer processes using so_reuseport and peering, achieving a 4x throughput improvement.

hackernews · saisrirampur · Jul 11, 15:28 · [Discussion](https://news.ycombinator.com/item?id=48872874)

**Background**: PgBouncer is a lightweight, single-threaded connection pooler for PostgreSQL. Its single-threaded nature limits performance on multi-core machines, and query cancellation can fail when multiple processes share a port because the cancel request may land on a process that doesn't own the session.

<details><summary>References</summary>
<ul>
<li><a href="https://clickhouse.com/blog/pgbouncer-clickhouse-managed-postgres">How we scale PgBouncer in ClickHouse Managed Postgres</a></li>
<li><a href="https://www.pgbouncer.org/">PgBouncer - lightweight connection pooler for PostgreSQL</a></li>
<li><a href="https://www.pgbouncer.org/config.html">PgBouncer config</a></li>

</ul>
</details>

**Discussion**: Commenters suggested alternative solutions like Odyssey and pgdog, and discussed practical Kubernetes considerations such as running multiple PgBouncer processes per pod or across pods. One user asked whether peering works in Kubernetes where separate pods have independent pools.

**Tags**: `#PostgreSQL`, `#PgBouncer`, `#connection pooling`, `#scalability`, `#ClickHouse`

---

<a id="item-8"></a>
## [US Housing Law Bans Federal Reserve CBDC Until 2030](https://www.coindesk.com/policy/2026/07/10/u-s-government-digital-dollar-set-to-be-banned-tonight-under-housing-law-s-cbdc-limit) ⭐️ 7.0/10

A provision in the 21st Century ROAD to Housing Act, which became law without the president's signature, prohibits the Federal Reserve from issuing a central bank digital currency (CBDC) until December 31, 2030. This ban halts U.S. CBDC development for years, potentially ceding leadership in digital currency innovation to other countries like China. It also signals strong political opposition to government-issued digital currencies, affecting fintech and crypto markets. The ban applies to the Federal Reserve and prohibits issuing CBDCs or similar assets through 2030. The provision was included in a housing bill and passed without President Trump's signature, reflecting bipartisan support for the restriction.

rss · CoinDesk · Jul 10, 16:02

**Background**: A central bank digital currency (CBDC) is a digital form of a country's fiat currency issued and backed by its central bank. Unlike cryptocurrencies, CBDCs are centralized and subject to the same monetary policies as traditional money. Many countries, including China, are actively developing CBDCs, while the U.S. has debated their potential benefits and risks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cryptopolitan.com/house-republicans-cbdc-ban-housing-bill/">House Republicans insist on a permanent CBDC ban... - Cryptopolitan</a></li>
<li><a href="https://www.kucoin.com/news/flash/us-cbdc-ban-takes-effect-as-housing-bill-passes-without-trump-signature">US CBDC Ban Takes Effect as Housing Bill Passes Without... | KuCoin</a></li>
<li><a href="https://www.pymnts.com/cbdc/2026/us-cbdc-ban-set-to-become-law-at-midnight/">PYMNTS | US CBDC Ban Set to Become Law at Midnight</a></li>

</ul>
</details>

**Tags**: `#CBDC`, `#digital currency`, `#regulation`, `#US policy`

---

<a id="item-9"></a>
## [Apple Sues OpenAI Over Stolen Trade Secrets](https://decrypt.co/373339/apple-sues-openai-claims-former-employees-stole-trade-secrets) ⭐️ 7.0/10

Apple has filed a lawsuit against OpenAI, alleging that former employees stole trade secrets, including confidential designs and supplier information, before joining the AI company. This legal action between two tech giants could reshape intellectual property practices in the AI industry and set a precedent for how companies protect trade secrets when employees move to competitors. The lawsuit claims that former Apple employees took confidential designs, supplier information, and engineering files before joining OpenAI, though specific details of the stolen materials have not been publicly disclosed.

rss · Decrypt · Jul 10, 21:50

**Background**: Trade secret lawsuits are common in the tech industry when employees move between competing firms. Apple and OpenAI are both major players in AI, with Apple developing its own AI models and OpenAI known for ChatGPT. This case highlights the tension between talent mobility and intellectual property protection.

**Tags**: `#Apple`, `#OpenAI`, `#trade secrets`, `#lawsuit`, `#AI`

---

<a id="item-10"></a>
## [Cambridge: 31% of Ethereum nodes in US, third offline could stall finalization](https://www.theblock.co/post/407909/cambridge-research-puts-ethereum-node-activity-in-us-where-third-offline-can-stall-finalization?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

New research from the Cambridge Centre for Alternative Finance reveals that 31% of Ethereum node activity is concentrated in the United States, and if a third of those nodes go offline, it could stall network finalization. This concentration raises serious concerns about Ethereum's decentralization and jurisdictional risks, as a single country's infrastructure issues could disrupt the entire network, undermining its core value proposition. The nodes are heavily clustered on cloud providers like AWS, Hetzner, and OVH, and the research notes that roughly 39% of node activity is in the EU excluding the UK.

rss · The Block · Jul 10, 16:07

**Background**: Ethereum nodes are computers that run the Ethereum software, validating transactions and maintaining the blockchain. Finalization is the process by which blocks become irreversible; if too many nodes go offline, the network cannot finalize new blocks, halting operations. Centralization of nodes in a single jurisdiction creates a single point of failure.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/407909/cambridge-research-puts-ethereum-node-activity-in-us-where-third-offline-can-stall-finalization">Cambridge research puts 31% of Ethereum node activity... | The Block</a></li>
<li><a href="https://massachain.medium.com/ethereums-node-centralization-challenge-and-how-massa-can-help-2744e22160ca">Ethereum ’s Node Centralization Challenge — and how... | Medium</a></li>
<li><a href="https://www.ainvest.com/news/ethereum-decentralization-risk-implications-long-term-investment-strategy-2601/">Ethereum 's Decentralization at Risk : Implications for Long-Term Value...</a></li>

</ul>
</details>

**Discussion**: The community has long debated node centralization, with Vitalik Buterin previously highlighting it as a key challenge. Some argue that geographic diversity is improving, while others worry about cloud provider dominance and regulatory risks.

**Tags**: `#Ethereum`, `#decentralization`, `#blockchain`, `#node centralization`, `#research`

---

<a id="item-11"></a>
## [Laser Attack Resets Tangem Wallet Passwords](https://www.theblock.co/post/407871/ledger-researchers-disclose-tangem-card-flaw-tangem-says-risk-to-everyday-users-is-virtually-non-existent?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Ledger Donjon researchers disclosed a laser fault injection attack that can reset the password on Tangem hardware wallet cards by bypassing a firmware recovery-state check. Tangem responded that the risk to everyday users is virtually non-existent due to the need for physical access and expensive equipment. This vulnerability highlights the ongoing security challenges in hardware wallets, especially card-based designs that may lack active countermeasures. It could erode trust in Tangem products and reignite debates on hardware wallet security standards. The attack requires physical access to the card and a laser setup costing around $250,000, making it impractical for most attackers. Tangem claims the firmware vulnerability has been addressed in newer card versions.

rss · The Block · Jul 10, 11:08

**Background**: Hardware wallets store cryptocurrency private keys offline to protect against remote hacks. Tangem cards are a type of hardware wallet that resemble credit cards and use a secure chip. Laser fault injection is a physical attack technique where a laser is used to induce errors in a chip's operation, potentially bypassing security checks.

<details><summary>References</summary>
<ul>
<li><a href="https://thehackernews.com/2026/07/laser-attack-resets-tangem-wallet.html">Laser Attack Resets Tangem Wallet Passwords on Cards That Can ...</a></li>
<li><a href="https://coinalertnews.com/news/2026/07/10/tangem-wallet-laser-attack">Tangem Hardware Wallets Vulnerable to Laser Attacks, No ...</a></li>
<li><a href="https://financefeeds.com/ledger-finds-laser-attack-that-can-reset-tangem-card-passwords/">Ledger Finds Laser Attack That Can Reset Tangem Card ...</a></li>

</ul>
</details>

**Tags**: `#security`, `#hardware wallet`, `#vulnerability`, `#cryptocurrency`, `#Tangem`

---

<a id="item-12"></a>
## [Ant: A New All-in-One JavaScript Runtime and Ecosystem](https://antjs.org/) ⭐️ 6.0/10

Ant is a new JavaScript runtime with its own engine, package manager (ants.land), hosting platform, and desktop app builder (Ant Desktop), aiming to provide a coherent end-to-end alternative to existing JavaScript stacks. This project challenges the dominance of Node.js and Deno by offering a tightly integrated ecosystem that promises smaller size, fast startup, and sandboxing, potentially lowering the barrier for developers to build and deploy JavaScript applications. Ant is built from scratch and claims near-V8 speeds from a single 9 MB binary, but community comments reveal that early versions relied on an existing AGPL codebase (Elk), which the author says has since been rewritten.

hackernews · theMackabu · Jul 11, 20:07 · [Discussion](https://news.ycombinator.com/item?id=48875377)

**Background**: JavaScript runtimes like Node.js and Deno execute JavaScript outside the browser. Ant introduces its own engine and ecosystem, similar to how Node.js uses V8 and npm, but aims for tighter integration and smaller footprint. The name "Ant" conflicts with Apache Ant, a build tool.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/themackabu/ant">GitHub - theMackabu/ ant : javascript for 's, a tiny runtime with big...</a></li>
<li><a href="https://zeli.app/en/story/48875377">Ant - Lightweight JavaScript runtime with near-V8 speeds... | Zeli</a></li>
<li><a href="https://eucloudservers.com/architecture-reliability/show-hn-ant-a-javascript-runtime-and-ecosystem/">Show HN: Ant – A JavaScript Runtime And... - EU Cloud Servers</a></li>

</ul>
</details>

**Discussion**: Community comments raise concerns about the project's originality, noting that early versions used an existing AGPL codebase (Elk) despite claims of being built from scratch. There is also criticism about the naming conflict with Apache Ant, and skepticism about achieving performance advantages over mature runtimes like Node.js.

**Tags**: `#JavaScript`, `#runtime`, `#ecosystem`, `#web development`

---

<a id="item-13"></a>
## [Crypto Giants Back Dispute Resolution Court for AI Agents](https://www.coindesk.com/business/2026/07/10/okx-metamask-matter-labs-back-dispute-resolution-court-for-ai-agents) ⭐️ 6.0/10

A consortium of 27 crypto and Web3 firms, including OKX, MetaMask, and Matter Labs, has launched the "Internet Court" protocol for resolving disputes between AI agents. The initiative is led by the Genlayer Foundation. As AI agents increasingly transact autonomously, a dedicated dispute resolution mechanism is critical for trust and scalability in the decentralized economy. This marks a significant step toward infrastructure for agent-to-agent commerce. The protocol handles AI-based payments, escrow, and dispute resolution, and is backed by 27 firms. No technical details about the arbitration process or smart contract implementation have been disclosed yet.

rss · CoinDesk · Jul 10, 12:29

**Background**: AI agents are autonomous programs that can execute transactions like buying, selling, or committing funds without human approval. As they interact on blockchains, disputes may arise (e.g., one agent defaults on a deal), requiring a neutral third party to adjudicate. The Internet Court aims to fill this gap by providing a decentralized dispute resolution layer.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/10/okx-metamask-matter-labs-back-dispute-resolution-court-for-ai-agents">OKX, MetaMask, Matter Labs back dispute resolution court for ...</a></li>
<li><a href="https://en.cryptonomist.ch/2026/07/10/ai-agent-dispute-resolution/">AI Agent Dispute Resolution Powers Internet Court Protocol</a></li>
<li><a href="https://financefeeds.com/okx-metamask-and-matter-labs-back-internet-court-for-ai-agents/">OKX, MetaMask and Matter Labs Back Internet Court for AI Agents</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#AI agents`, `#dispute resolution`, `#crypto`

---

<a id="item-14"></a>
## [Robinhood Chain: Ethereum L2 for Tokenized Stocks](https://decrypt.co/resources/what-robinhood-chain-ethereum-layer-2-network-tokenized-stocks) ⭐️ 6.0/10

Robinhood Chain is a new Ethereum layer-2 network built with Arbitrum technology, designed to support tokenized stocks, crypto apps, and on-chain financial products. This development bridges traditional finance and DeFi by enabling tokenized stocks on a scalable, low-cost L2, potentially increasing accessibility and liquidity for real-world assets on blockchain. Robinhood Chain uses Arbitrum's Optimistic Rollup technology to batch transactions off-chain, reducing fees and latency while inheriting Ethereum's security. It targets tokenized equities and on-chain finance applications.

rss · Decrypt · Jul 11, 16:21

**Background**: Ethereum layer-2 solutions like Arbitrum scale the network by processing transactions off-chain and posting compressed data to the main chain. Tokenized stocks are digital representations of traditional equities on a blockchain, enabling fractional ownership and 24/7 trading. Robinhood Chain combines these concepts to offer a dedicated platform for on-chain finance.

<details><summary>References</summary>
<ul>
<li><a href="https://blockspot.io/what-is-arbitrum-ethereum-layer-2/">What Is Arbitrum ? Ethereum Layer - 2 for Faster Transactions</a></li>
<li><a href="https://www.coingecko.com/learn/what-are-tokenized-stocks">What Are Tokenized Stocks and Top Platforms to Get Started</a></li>
<li><a href="https://zipmex.com/blog/what-is-arbitrum/">What Is Arbitrum (ARB)? Complete 2026 Guide</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#Layer-2`, `#DeFi`, `#Tokenized Assets`, `#Arbitrum`

---

<a id="item-15"></a>
## [Xbox CEO Joins Fed AI Task Force Amid Layoffs](https://decrypt.co/373277/xbox-ceo-fed-ai-jobs-task-force-days-after-layoffs) ⭐️ 6.0/10

Xbox CEO Asha Sharma has joined the Federal Reserve's AI task force to advise on AI's impact on jobs and productivity, just days after Microsoft announced 3,200 layoffs in its gaming division. This highlights the tension between AI adoption and workforce displacement, as a major gaming executive participates in policy discussions while overseeing significant layoffs. It underscores the need for balanced AI policies that consider both innovation and job impacts. The layoffs are part of Microsoft's largest restructuring in Xbox history, affecting 3,200 employees. Sharma's role on the Fed task force involves advising on how AI might reshape labor markets and productivity.

rss · Decrypt · Jul 10, 18:02

**Background**: The Federal Reserve has formed an AI task force to study the economic implications of artificial intelligence, including its effects on employment and productivity. Xbox, a division of Microsoft, has been undergoing significant restructuring amid broader tech industry layoffs.

**Tags**: `#AI`, `#policy`, `#gaming`, `#layoffs`

---

<a id="item-16"></a>
## [Circle Wins Final OCC Approval for National Trust Bank](https://decrypt.co/373227/circle-stock-jumps-stablecoin-issuer-final-federal-banking-charter) ⭐️ 6.0/10

Circle has received final approval from the Office of the Comptroller of the Currency (OCC) to establish a national trust bank, bringing its $73.2 billion USDC stablecoin under a unified federal regulatory framework. This milestone marks the first time a major stablecoin issuer has secured a federal banking charter, potentially setting a precedent for regulatory compliance in the crypto industry and increasing institutional confidence in stablecoins. The charter approval is for a national trust bank named First National Digital Currency Bank, with USDC reserve management planned for a later phase. Circle joins approximately 60 other national trust banks supervised by the OCC.

rss · Decrypt · Jul 10, 14:54

**Background**: A national trust bank is a federally chartered financial institution that can hold assets in trust, but cannot accept deposits or make loans. The OCC has been gradually approving crypto-related trust charters, including conditional approvals for five entities in December 2025. USDC is a stablecoin fully backed by U.S. Treasuries and cash, with reserves held ~80% in Treasuries and ~20% in cash.

<details><summary>References</summary>
<ul>
<li><a href="https://www.occ.gov/news-issuances/news-releases/2025/nr-occ-2025-125.html">OCC Announces Conditional Approvals for Five National Trust ...</a></li>
<li><a href="https://www.circle.com/blog/how-the-usdc-reserve-is-structured-and-managed">How the USDC Reserve is Structured and Managed - Circle</a></li>
<li><a href="https://usdc.org/tools/reserves">USDC Reserves & Transparency - Proof of Backing | USDC.org</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#regulation`, `#cryptocurrency`, `#banking`

---

<a id="item-17"></a>
## [Revolut X Integrates AI Assistants for Crypto Trading](https://www.theblock.co/post/407865/revolut-integrates-its-crypto-exchange-with-ai-assistants-as-agentic-trading-spreads?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Revolut X, the crypto exchange from Revolut, now connects with AI assistants including Claude, Gemini, OpenClaw, and Cursor, enabling users to analyze, backtest, and execute trades via natural language prompts. This integration marks a step toward agentic trading, where AI agents assist in decision-making and execution, potentially making crypto trading more accessible and efficient for retail users. Revolut X supports over 210 cryptocurrencies with low fees (0% maker, 0.09% taker max), and the AI integration allows users to perform complex tasks like backtesting strategies without coding.

rss · The Block · Jul 10, 10:04

**Background**: Revolut X is an advanced crypto trading platform by Revolut, a UK-based fintech with over 50 million customers. Agentic trading refers to the use of autonomous AI agents to monitor markets and generate signals, often requiring human approval for execution.

<details><summary>References</summary>
<ul>
<li><a href="https://www.revolut.com/revolut-x/">Revolut X Advanced Crypto Exchange | Cryptocurrency Trading ...</a></li>
<li><a href="https://wundertrading.com/journal/en/agentic-trading">Agentic Trading Explained: How Autonomous AI Agents Are ...</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#AI`, `#trading`, `#integration`

---