---
layout: default
title: "Horizon Summary: 2026-09-08 (EN)"
date: 2026-09-08
lang: en
---

> From 61 items, 17 important content pieces were selected

---

1. [90s CA RSA Keys Factored on Consumer GPU](#item-1) ⭐️ 8.0/10
2. [TALA Layout Engine for D2 Diagrams Goes Open Source](#item-2) ⭐️ 8.0/10
3. [Jellyfin 12.0 Major Release Brings Performance and New Features](#item-3) ⭐️ 8.0/10
4. [Broadcom's VDDK removal complicates VMware exits](#item-4) ⭐️ 8.0/10
5. [LG Smart TVs Found Logging Audio and Scanning Home Networks](#item-5) ⭐️ 8.0/10
6. [Ethereum Commits to Gas Fee Payments Without Holding ETH](#item-6) ⭐️ 8.0/10
7. [DBS and Citi Complete First Weekend Cross-Border USD Payment on Swift Ledger](#item-7) ⭐️ 8.0/10
8. [OpenAI's GPT-6 Astra Impresses Early Testers Across Diverse Tasks](#item-8) ⭐️ 8.0/10
9. [Ethereum Aims for Quantum-Safe L1 by 2029 with Hegotá Upgrade](#item-9) ⭐️ 8.0/10
10. [Liquid Network Pauses After $320M Bitcoin Withdrawal](#item-10) ⭐️ 8.0/10
11. [Interactive Map Shows LA Building History 1880-2026](#item-11) ⭐️ 7.0/10
12. [Two-Key Breach Could Expose $91B USDT to Hackers](#item-12) ⭐️ 7.0/10
13. [Coldcard hacker moves $7.7M BTC, 45% of third-wave theft](#item-13) ⭐️ 7.0/10
14. [OpenAI Chief Scientist Calls for Mandatory AI Safety Standards](#item-14) ⭐️ 7.0/10
15. [Hanwha builds tokenized securities platform on Avalanche as South Korea regulation nears](#item-15) ⭐️ 7.0/10
16. [Stablecoin Wallets Challenge Bank Accounts as Primary Money Hub](#item-16) ⭐️ 6.0/10
17. [Solana to Triple Transaction Size for Complex Trades](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [90s CA RSA Keys Factored on Consumer GPU](https://mcpherrin.ca/2026/09/07/rsa.html) ⭐️ 8.0/10

An author successfully factored the RSA keys of a 1990s Certificate Authority using a consumer GPU, taking about two days to crack a 512-bit key. This demonstrates that modern hardware can easily break such historical encryption. This highlights the insecurity of 512-bit RSA keys, which were once used in early internet encryption, and raises concerns about the long-term viability of current encryption standards against future computational advances. It also prompts reflection on the security of historical data and the potential for governments to decrypt stored communications. The author used a consumer GPU and likely employed the General Number Field Sieve (GNFS) algorithm, which is the standard method for factoring large numbers. The cracked keys belonged to a Certificate Authority from the 1990s, and the author noted that much of the traffic back then did not use ephemeral keys, making it vulnerable to such attacks.

hackernews · ahlCVA · Sep 8, 01:16 · [Discussion](https://news.ycombinator.com/item?id=49604637)

**Background**: RSA is a public-key cryptosystem whose security relies on the difficulty of factoring large composite numbers. In the 1990s, 512-bit RSA keys were common, but by 1999, RSA-155 (512 bits) was factored using significant computational resources. Modern consumer GPUs have made such factorization much faster, demonstrating the importance of using sufficiently large key sizes (e.g., 2048 bits or more) in current systems.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/RSA_numbers">RSA numbers - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/RSA_Factoring_Challenge">RSA Factoring Challenge - Wikipedia</a></li>
<li><a href="https://www.iacr.org/archive/eurocrypt2000/1807/18070001-new.pdf">Factorization of a 512–bit RSA Modulus ⋆</a></li>

</ul>
</details>

**Discussion**: Community comments expressed mixed reactions: some lamented that interesting technical details were left to AI, while others appreciated the demonstration of GPU cracking. One commenter noted the irony of an SSL report with automatic 'F' grades, and another emphasized the need to verify AI-generated content, as LLMs can produce plausible but incorrect outputs.

**Tags**: `#RSA`, `#cryptography`, `#security`, `#history`, `#GPU cracking`

---

<a id="item-2"></a>
## [TALA Layout Engine for D2 Diagrams Goes Open Source](https://d2lang.com/blog/tala-is-open-source/) ⭐️ 8.0/10

Terrastruct has open-sourced TALA, its proprietary layout engine designed specifically for software architecture diagrams, making it freely available to the D2 community. This change allows users to access improved auto layout without the previous commercial licensing costs. This move addresses a long-standing pain point in the D2 ecosystem: the default layout engine often produces suboptimal diagrams, while TALA offers significantly better results for architecture diagrams. By open-sourcing TALA, Terrastruct lowers the barrier for developers and organizations to create clearer, more professional diagrams, potentially increasing D2's adoption. TALA is a separate install from D2, built from scratch with zero dependencies for its algorithms, and is developed in-house at Terrastruct. The open-source release includes the full source code, enabling community contributions and integration into other tools.

hackernews · alixanderwang · Sep 7, 23:37 · [Discussion](https://news.ycombinator.com/item?id=49604150)

**Background**: D2 is a modern declarative diagram scripting language that turns text into diagrams, similar to Graphviz but with a more human-friendly syntax. Layout engines like TALA automatically position nodes and edges to produce readable diagrams; TALA was specifically designed for software architecture diagrams, which often have complex structures that generic engines handle poorly.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/d2lang/d2">GitHub - d2lang/d2: D2 is a modern diagram scripting language that turns text to diagrams. · GitHub</a></li>
<li><a href="https://github.com/terrastruct/tala">terrastruct/TALA: A diagram layout engine designed ... - GitHub</a></li>
<li><a href="https://d2lang.com/tour/tala/">TALA | D2 Documentation</a></li>

</ul>
</details>

**Discussion**: Community reactions are largely positive, with users praising TALA's improved layout quality compared to default and ELK engines. Some users note that TALA may not always be better for every graph type, and there are questions about integrating TALA into other tools like Graphviz.

**Tags**: `#open-source`, `#diagramming`, `#layout-engine`, `#D2`, `#visualization`

---

<a id="item-3"></a>
## [Jellyfin 12.0 Major Release Brings Performance and New Features](https://jellyfin.org/posts/jellyfin-release-12.0/) ⭐️ 8.0/10

Jellyfin 12.0, a major open-source media server release, is now available with performance improvements and new features. The update includes a smoother migration process and addresses issues from previous versions like 10.11. This release is significant for the self-hosting community as it enhances the viability of Jellyfin as a Plex alternative, potentially reducing reliance on proprietary services. Its performance fixes and new features could attract more users seeking a free, open-source media solution. Users upgrading from 10.10.7 to 12.0 reported a quick and painless migration, though some titles disappeared until a rescan. The release also includes improvements to subtitle handling, which has been a common pain point, especially on Android clients casting to Chromecast.

hackernews · 0xC0ncord · Sep 8, 01:56 · [Discussion](https://news.ycombinator.com/item?id=49604861)

**Background**: Jellyfin is a free, open-source media server that allows users to manage and stream their personal media libraries. It is often compared to Plex, but unlike Plex, it is fully self-hosted without any paid tiers or mandatory online services. The project has been evolving to offer a more user-friendly and feature-rich alternative to proprietary solutions.

**Discussion**: Community sentiment is largely positive, with users praising the smooth upgrade and performance improvements. Some users highlight ongoing issues with subtitle handling, while others express hope that Jellyfin will continue to pressure Plex to improve its user-hostile behaviors. A few users share their experiences integrating Jellyfin with other self-hosted tools like the *arr stack and AI assistants.

**Tags**: `#Jellyfin`, `#media server`, `#open source`, `#release`, `#self-hosting`

---

<a id="item-4"></a>
## [Broadcom's VDDK removal complicates VMware exits](https://www.virtualizationhowto.com/2026/09/leaving-vmware-just-got-harder-after-broadcom-pulled-vddk-downloads/) ⭐️ 8.0/10

Broadcom has removed public downloads of the VMware Virtual Disk Development Kit (VDDK), a critical component for many virtualization migration tools. This change was made without prior announcement or documented alternative, affecting users planning to migrate away from VMware. VDDK is essential for reading VMware virtual disks from outside the hypervisor, and nearly all migration tools depend on it. Its removal significantly hampers VMware exit strategies, forcing users to find slower workarounds or reconsider their migration plans, impacting the broader virtualization ecosystem. Without VDDK, disk transfer falls back to a materially slower path, making large-scale migrations impractical. Some vendors like Platform9 offer alternative migration methods, but the lack of official support adds risk and complexity to VMware exits.

hackernews · josephcsible · Sep 7, 20:32 · [Discussion](https://news.ycombinator.com/item?id=49602699)

**Background**: VMware VDDK is a software development kit that allows third-party tools to read and write VMware virtual disks. It is widely used by backup and migration solutions to efficiently access VM data. Broadcom, which acquired VMware in 2023, has been making changes to VMware's product offerings and licensing, often drawing criticism from the community.

<details><summary>References</summary>
<ul>
<li><a href="https://www.shapeblue.com/broadcom-vddk-download-vmware-to-kvm/">Broadcom Removes VDDK Pages Without Explanation... - ShapeBlue</a></li>
<li><a href="https://platform9.com/blog/vddk-no-longer-available/">Broadcom Cut Public Access of Virtual Disk Development Kit ...</a></li>
<li><a href="https://news.ycombinator.com/item?id=49602699">Leaving VMware just got harder after Broadcom pulled VDDK ...</a></li>

</ul>
</details>

**Discussion**: Community comments express sadness and frustration over Broadcom's handling of VMware, with some noting the decline of a once-great product. Users share personal migration experiences, such as moving from Hyper-V to VMware and now back, and suggest alternatives like KVM or Proxmox, while others joke about exfiltrating VMware source code.

**Tags**: `#VMware`, `#Broadcom`, `#VDDK`, `#virtualization`, `#migration`

---

<a id="item-5"></a>
## [LG Smart TVs Found Logging Audio and Scanning Home Networks](https://www.youtube.com/watch?v=6IFVTcM28KA) ⭐️ 8.0/10

An investigation by Gamers Nexus revealed that LG smart TVs, including the flagship G5 OLED, log microphone audio even when the screen is off and actively scan local networks to map nearby devices. The TVs operate offline and upload cached data once reconnected to the internet. This raises significant privacy concerns for the estimated 216 million LG smart TV users, as the devices capture audio and network information without clear user consent. The findings highlight broader issues with smart TV data collection and could prompt regulatory scrutiny and consumer backlash against LG and other manufacturers. The investigation used Wireshark packet captures on retail LG OLED models, including the G5, and observed continuous network scanning for unrelated devices like smartphones and smartwatches. Audio transcription occurs locally when the screen is off, and data is uploaded once the TV reconnects to the internet, operating across all inputs including HDMI.

hackernews · treve · Sep 7, 00:22 · [Discussion](https://news.ycombinator.com/item?id=49592375)

**Background**: Smart TVs often include features like Automatic Content Recognition (ACR) to track viewing habits for advertising, but this investigation reveals more invasive data collection. LG's terms of service reportedly require users to notify household members and guests that their voices may be captured, placing the burden of consent on the user. This incident is part of a broader trend of IoT devices collecting data without transparent user consent.

<details><summary>References</summary>
<ul>
<li><a href="https://www.notebookcheck.net/LG-smart-TVs-caught-logging-audio-with-screen-off-and-snooping-on-local-devices.1391214.0.html">LG smart TVs caught logging audio with screen off and ...</a></li>
<li><a href="https://cybersecuritynews.com/lg-smart-tvs-caught-scanning-networks/">LG Smart TVs Caught Scanning Networks and Logging Audio in ...</a></li>
<li><a href="https://cyberinsider.com/lg-smart-tvs-found-scanning-home-networks-for-nearby-devices/">LG Smart TVs found scanning home networks for nearby devices</a></li>

</ul>
</details>

**Discussion**: Community comments express outrage and concern, with users sharing personal experiences of disabling network functions on LG TVs and facing ridicule. Some point out the irony of privacy concerns being reported on ad-supported websites, while others question the legality under wiretap laws and call for consumer action against LG.

**Tags**: `#privacy`, `#smart TV`, `#LG`, `#surveillance`, `#IoT`

---

<a id="item-6"></a>
## [Ethereum Commits to Gas Fee Payments Without Holding ETH](https://www.coindesk.com/tech/2026/09/07/ethereum-commits-to-letting-users-pay-gas-fees-without-having-to-hold-eth) ⭐️ 8.0/10

Ethereum has officially committed to enabling users to pay gas fees without needing to hold ETH, a significant shift in its transaction fee model. This move aims to lower the barrier for new users and improve overall user experience. This development could dramatically increase Ethereum's accessibility and adoption by removing the requirement to acquire ETH solely for transaction fees. It aligns with broader industry trends toward account abstraction and user-friendly blockchain interactions, potentially attracting more mainstream users and developers. The commitment likely involves implementing account abstraction (EIP-4337) or similar mechanisms that allow smart contract wallets to sponsor or pay gas fees in alternative tokens. Technical details, such as the exact timeline and implementation approach, have not been fully disclosed yet.

rss · CoinDesk · Sep 7, 13:54

**Background**: Gas fees on Ethereum are payments made in ETH to compensate validators for processing transactions. Traditionally, users must hold ETH in their wallets to pay these fees, which can be a barrier for newcomers. Account abstraction is a proposed upgrade that enables smart contract wallets to initiate transactions and pay fees in a flexible manner, potentially using other ERC-20 tokens or having a third party cover the costs.

<details><summary>References</summary>
<ul>
<li><a href="https://ethereum.org/developers/docs/gas/">Ethereum gas and fees: technical overview | ethereum.org</a></li>
<li><a href="https://ethereum.org/roadmap/account-abstraction/">Account abstraction | ethereum.org</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#cryptocurrency`, `#gas fees`, `#blockchain`, `#usability`

---

<a id="item-7"></a>
## [DBS and Citi Complete First Weekend Cross-Border USD Payment on Swift Ledger](https://www.coindesk.com/business/2026/09/07/dbs-and-citi-enable-instant-24-7-cross-border-tokenised-deposit-payments-on-the-swift-ledger) ⭐️ 8.0/10

DBS and Citi successfully completed the first weekend cross-border USD settlement between Singapore and the U.S. using tokenized deposits on Swift's Digital Ledger. This marks a significant milestone in enabling instant, 24/7 cross-border payments. This demonstrates the practical viability of tokenized deposits and blockchain-based ledgers for real-world banking operations, potentially transforming the cross-border payment landscape. It paves the way for financial institutions to offer round-the-clock settlement, reducing reliance on traditional banking hours and intermediaries. The transaction involved tokenized deposits, which are digital representations of traditional bank deposits on a distributed ledger, issued by regulated institutions. Swift's Digital Ledger, developed with input from over 30 global financial institutions and Consensys, is progressing to an MVP implementation, with initial focus on real-time 24/7 cross-border payments.

rss · CoinDesk · Sep 7, 12:05

**Background**: Tokenized deposits are a blockchain-based form of commercial bank money, distinct from stablecoins as they represent a direct claim on a regulated bank. Swift has been building a blockchain-based shared ledger to modernize its infrastructure, aiming to support digital assets and tokenized deposits across its global network. This initiative is part of a broader industry trend where major banks like Wells Fargo are also exploring tokenized deposits for corporate clients.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nacha.org/tokenized-deposits-why-care">Tokenized Deposits: What They Are and Why U.S. Financial Institutions Should Care | Nacha</a></li>
<li><a href="https://www.swift.com/news-events/press-releases/swift-add-blockchain-based-ledger-its-infrastructure-stack-groundbreaking-move-accelerate-and-scale-benefits-digital-finance">Swift to add blockchain-based ledger to its infrastructure stack in groundbreaking move to accelerate and scale benefits of digital finance across more than 200 countries and territories worldwide | Swift</a></li>
<li><a href="https://www.swift.com/payments/payment-innovation/blockchain-based-ledger">Building the digital payment stack of the future | Swift</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenized deposits`, `#cross-border payments`, `#Swift`, `#banking`

---

<a id="item-8"></a>
## [OpenAI's GPT-6 Astra Impresses Early Testers Across Diverse Tasks](https://decrypt.co/377514/openai-gpt-6-astra-review-shockingly-good) ⭐️ 8.0/10

OpenAI has launched GPT-6 Astra, its most intelligent and aligned model yet, and early testers report it excels at navigating 3D cities, composing music, analyzing research papers, and playing games. The model is available via the OpenAI API for complex reasoning, coding, computer use, research, and document creation. GPT-6 Astra represents a significant leap in AI capabilities, potentially reshaping how professionals and consumers use AI for complex, multimodal tasks. Its strong performance across diverse domains could accelerate adoption in research, creative industries, and software development, intensifying competition among AI labs. According to OpenAI, GPT-6 Astra is built for the hardest end-to-end work, with state-of-the-art capabilities in computer use, coding, cybersecurity, and science. Early impressions are based on launch weekend testing, so long-term reliability and safety remain to be fully evaluated.

rss · Decrypt · Sep 6, 17:01

**Background**: GPT-6 Astra is the latest iteration in OpenAI's GPT series, following models like GPT-5.6. It is a multimodal model capable of processing and generating text, images, and other data types, enabling tasks such as 3D navigation and music composition. The model is positioned as a flagship for complex professional work, balancing intelligence and cost.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-6_Astra">GPT-6 Astra - Wikipedia</a></li>
<li><a href="https://openai.com/index/gpt-6-astra/">GPT-6 Astra: A new generation of intelligence | OpenAI</a></li>
<li><a href="https://developers.openai.com/api/docs/models/gpt-6-astra">GPT-6 Astra Model | OpenAI API</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#GPT-6`, `#AI`, `#language models`, `#multimodal`

---

<a id="item-9"></a>
## [Ethereum Aims for Quantum-Safe L1 by 2029 with Hegotá Upgrade](https://www.theblock.co/news/ecosystems/2026-09-08-ethereum-foundation-quantum-resistance-2029-413716) ⭐️ 8.0/10

Ethereum has announced a roadmap to achieve full post-quantum security on its Layer 1 by 2029, beginning with the Hegotá upgrade that introduces account abstraction and censorship resistance improvements. This strategic move positions Ethereum to proactively address the future threat of quantum computers, which could break current cryptographic primitives. It sets a precedent for other blockchain networks and underscores the importance of long-term security planning in the crypto ecosystem. The Hegotá upgrade is expected to include native account abstraction via EIP-8141, which will enable more flexible and secure transaction mechanisms. The 2029 target for post-quantum security suggests a phased transition, likely involving the adoption of quantum-resistant signature schemes and other cryptographic updates.

rss · The Block · Sep 8, 04:17

**Background**: Quantum computers pose a significant threat to blockchain security because they could potentially break the elliptic curve cryptography (ECC) used in most blockchains, including Ethereum. Post-quantum cryptography involves developing algorithms that are secure against both classical and quantum computers. Account abstraction is a concept that allows user accounts to be controlled by smart contracts, enabling features like multi-signature wallets and social recovery, which are also relevant to quantum resistance.

<details><summary>References</summary>
<ul>
<li><a href="https://ethereum.org/roadmap/account-abstraction/">Account abstraction | ethereum .org</a></li>
<li><a href="https://www.kucoin.com/blog/ethereum-developers-target-privacy-changes-in-hegot-frame-transactions-and-focil-explained">Ethereum Developers Target Privacy Changes in Hegotá : Frame...</a></li>
<li><a href="https://www.linkedin.com/pulse/architecting-ethereums-cryptographic-transition-kusal-damsara-xkjkc">Architecting Ethereum 's Cryptographic Transition in the Hegotá ...</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#quantum computing`, `#blockchain security`, `#cryptography`, `#roadmap`

---

<a id="item-10"></a>
## [Liquid Network Pauses After $320M Bitcoin Withdrawal](https://www.theblock.co/news/defi/2026-09-06-liquid-network-pauses-after-purported-white-hat-hackers-withdraw-320-million-in-bitcoin-413626) ⭐️ 8.0/10

The Liquid Network, a Bitcoin sidechain, was paused after purported white-hat hackers withdrew approximately $320 million in bitcoin, leading to exchange suspensions of LBTC deposits and withdrawals. Blockstream has since patched the bridge nodes and recovered 3,400 BTC, leaving about 598.5 BTC outstanding. This incident highlights vulnerabilities in sidechain bridge implementations and raises concerns about the security of layer-2 solutions built on Bitcoin. The recovery of most funds may mitigate immediate losses, but the pause and exchange suspensions could undermine trust in Liquid and similar networks. The attackers communicated with Blockstream via PGP-signed messages embedded in Bitcoin transactions. Blockstream stated that Liquid's bridge nodes had been patched, and the attackers returned 3,400 BTC, leaving approximately 598.5 BTC (worth around $56 million) still outstanding.

rss · The Block · Sep 6, 21:14

**Background**: Liquid Network is a Bitcoin layer-2 sidechain developed by Blockstream, enabling faster and more confidential transactions and the issuance of digital assets. LBTC is the native token representing bitcoin on the sidechain, used for trading and DeFi applications. White-hat hackers are ethical security researchers who hack systems with permission to identify vulnerabilities, often returning stolen funds.

<details><summary>References</summary>
<ul>
<li><a href="https://liquid.net/">The Liquid Network: The Financial Layer for Bitcoin Capital ...</a></li>
<li><a href="https://blockstream.com/liquid/">The Liquid Network | Bitcoin layer-2 solution for digital ...</a></li>
<li><a href="https://www.thecoinrepublic.com/2026/09/07/bitcoin-news-liquid-network-drained-of-320m-as-sidechain-halts/">Bitcoin News: Liquid Network Drained of $320M as Sidechain ...</a></li>

</ul>
</details>

**Tags**: `#bitcoin`, `#security`, `#sidechain`, `#defi`, `#hack`

---

<a id="item-11"></a>
## [Interactive Map Shows LA Building History 1880-2026](https://lax-skyline.parcelscope.net/) ⭐️ 7.0/10

An interactive map at lax-skyline.parcelscope.net visualizes the construction dates of buildings in Los Angeles from 1880 to 2026, allowing users to explore urban development over time. This visualization provides a compelling tool for understanding urban growth and the impact of zoning policies, sparking public debate on housing affordability and historical development patterns. It engages a broad audience in discussions about city planning and data representation. The map is based on data from the Los Angeles County Assessor's portal, showing the construction year of existing buildings. However, it reflects only surviving structures, so areas with complete redevelopment appear dark, potentially misleading viewers about historical construction activity.

hackernews · rustywasm · Sep 7, 18:52 · [Discussion](https://news.ycombinator.com/item?id=49601655)

**Background**: Los Angeles has a complex urban history, including a once-extensive public transit network that was largely replaced by freeways. Zoning changes, particularly downzoning in the 1980s, have significantly shaped the city's development and housing affordability. Interactive maps like this use parcel-level data to illustrate these patterns.

**Discussion**: Commenters noted that the map shows only surviving buildings, not all historical construction, citing areas like Palms that have been completely rebuilt. Others discussed LA's lost public transit network and the effects of downzoning on housing costs, with some praising the visualization while pointing out its limitations.

**Tags**: `#data visualization`, `#urban planning`, `#Los Angeles`, `#history`, `#interactive map`

---

<a id="item-12"></a>
## [Two-Key Breach Could Expose $91B USDT to Hackers](https://www.coindesk.com/tech/2026/09/04/tether-receives-bluechip-rating-upgrade-but-hacken-finds-major-key-security-gaps) ⭐️ 7.0/10

A report by Hacken has identified major key security gaps at Tether, warning that a two-key breach could compromise control of $91 billion in USDT. The finding highlights vulnerabilities in Tether's key management system. This matters because USDT is the largest stablecoin, and a successful attack could lead to massive financial losses and undermine trust in the entire cryptocurrency ecosystem. It underscores the critical importance of robust key management for custodians of digital assets. The report specifically mentions that a two-key breach could grant hackers control over the $91 billion in USDT reserves. Hacken's findings suggest that Tether's current security measures may not be sufficient to prevent such an attack.

rss · CoinDesk · Sep 7, 10:35

**Background**: Tether is the issuer of USDT, a stablecoin pegged to the US dollar, widely used in cryptocurrency trading and as a store of value. Key management involves the secure storage and handling of cryptographic keys that control access to funds; a breach could allow unauthorized transactions. The report comes amid growing concerns about security in the crypto industry, with recent high-profile hacks highlighting vulnerabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://tethersecurity.com/">Tether Security | Device Trust Platform for the Mobile Workforce</a></li>
<li><a href="https://www.ft.com/content/a91356ef-67bd-4bd9-947b-b272423f1318?syn-25a6b1a6=1">Nearly 14,000 crypto holders face security risk after data breach</a></li>

</ul>
</details>

**Tags**: `#security`, `#cryptocurrency`, `#stablecoin`, `#key management`, `#Tether`

---

<a id="item-13"></a>
## [Coldcard hacker moves $7.7M BTC, 45% of third-wave theft](https://www.coindesk.com/business/2026/09/07/coldcard-hacker-moves-45-of-bitcoin-stolen-in-third-attack-wave) ⭐️ 7.0/10

A hacker moved $7.7 million in Bitcoin stolen from Coldcard wallets, representing 45% of funds taken in a third attack wave. This follows reports of a broader Coldcard wallet attack that has drained up to $89 million from over 1,200 addresses. This incident highlights vulnerabilities in hardware wallets, which are widely considered the most secure way to store Bitcoin. The scale of losses and the ongoing attack waves could undermine user trust in cold storage solutions and prompt a reevaluation of security practices. The third attack wave involved moving 45% of the stolen funds, indicating the attacker is actively consolidating or laundering the proceeds. Security researchers suspect a software flaw may have enabled the theft, potentially affecting thousands of addresses.

rss · CoinDesk · Sep 7, 09:32

**Background**: Hardware wallets like Coldcard store private keys offline to protect against remote hacks. However, they can still be vulnerable to supply chain attacks, firmware flaws, or physical tampering. The recent attack reportedly exploited a software flaw, allowing attackers to drain funds from multiple addresses in a short time.

<details><summary>References</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2lpaHZyY0VSRnFfMU5oWVBnNWV5Z0FQAQ?hl=en-IN&gl=IN&ceid=IN:en">Google News - Coldcard hardware wallet hack - Overview</a></li>
<li><a href="https://www.fox7austin.com/news/coldcard-wallet-attack-drains-89m-bitcoin-from-1200-addresses">Coldcard wallet attack drains up to $89M in Bitcoin... | FOX 7 Austin</a></li>
<li><a href="https://www.bit.com/knowledge-hub/coldcard-the-security-first-wallet-that-got-hacked">Coldcard Wallet : Security Features & Exploit Explained | BIT</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#security`, `#bitcoin`, `#hardware wallet`, `#theft`

---

<a id="item-14"></a>
## [OpenAI Chief Scientist Calls for Mandatory AI Safety Standards](https://decrypt.co/377635/openai-chief-scientist-warns-ai-slow-down) ⭐️ 7.0/10

OpenAI's chief scientist, Jakub Pachocki, has publicly called for mandatory safety standards in AI development, citing growing difficulties in monitoring the reasoning of advanced AI models. This marks a notable shift from voluntary self-regulation toward binding industry-wide requirements. This statement from a key OpenAI figure underscores escalating concerns about AI safety and could accelerate regulatory efforts worldwide. It signals that even leading AI developers acknowledge the limits of current monitoring techniques, potentially influencing policy and industry practices. Pachocki specifically highlighted challenges in monitoring AI models' 'reasoning' processes, which aligns with recent OpenAI research on chain-of-thought controllability. The call for mandatory standards suggests a move beyond voluntary frameworks like the EU AI Act or NIST's AI Risk Management Framework.

rss · Decrypt · Sep 7, 21:16

**Background**: Advanced AI models, such as OpenAI's o1 and GPT-4o, use chain-of-thought reasoning to solve complex tasks, but this internal process is not fully transparent. Researchers have found that these models can sometimes produce reasoning that is difficult to monitor or control, raising safety concerns. As AI capabilities grow, ensuring that models behave safely and as intended becomes increasingly challenging, prompting calls for standardized safety measures.

<details><summary>References</summary>
<ul>
<li><a href="https://openai.com/index/reasoning-models-chain-of-thought-controllability/">Reasoning models struggle to control their chains of thought ...</a></li>
<li><a href="https://arxiv.org/html/2503.22732v1">Reasoning Beyond Limits: Advances and Open Problems for LLMs</a></li>
<li><a href="https://www.nist.gov/artificial-intelligence/ai-standards">AI Standards | NIST</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#OpenAI`, `#regulation`, `#AI research`

---

<a id="item-15"></a>
## [Hanwha builds tokenized securities platform on Avalanche as South Korea regulation nears](https://www.theblock.co/news/business/2026-09-07-south-korea-hanwha-tokenized-securities-platform-avalanche-413652) ⭐️ 7.0/10

South Korea's Hanwha is developing a tokenized securities platform on the Avalanche blockchain, according to a report. This comes as the country's regulatory framework for such assets is taking shape, with amendments integrating tokenized securities into the existing financial system set to take effect next February. This development signals growing institutional adoption of blockchain for traditional finance, particularly in Asia. It also highlights Avalanche's traction in the enterprise sector and the importance of regulatory clarity in enabling such initiatives. The report does not specify which Hanwha subsidiary is involved or the exact scope of the platform. South Korea's amendments, which integrate tokenized securities into existing financial laws, are scheduled to take effect in February 2027, following a one-year preparation period.

rss · The Block · Sep 7, 06:24

**Background**: Avalanche is a public blockchain and smart-contract platform launched in September 2020 by Ava Labs, known for its high throughput and customizable subnets. Tokenized securities are digital representations of traditional financial assets, such as stocks or bonds, issued on a blockchain. South Korea has been working on a regulatory framework for tokenized securities, with a three-phase roadmap introduced by its financial regulator, and the legal basis is expected to be in place by 2027.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Avalanche_(blockchain_platform)">Avalanche ( blockchain platform ) - Wikipedia</a></li>
<li><a href="https://coincentral.com/south-korea-asses-bill-to-regulate-and-enable-tokenized-securities/">South Korea Asses Bill To Regulate And Enable Tokenized Securities</a></li>
<li><a href="https://cointelegraph.com/news/south-korean-regulators-tokenized-securities-roadmap">South Korean Regulators Introduce Tokenized Securities Roadmap</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenization`, `#Avalanche`, `#regulation`, `#South Korea`

---

<a id="item-16"></a>
## [Stablecoin Wallets Challenge Bank Accounts as Primary Money Hub](https://www.coindesk.com/business/2026/09/07/stablecoin-wallets-challenge-traditional-bank-accounts-as-main-consumer-money-hub) ⭐️ 6.0/10

A recent trend highlights that stablecoin wallets are increasingly competing with traditional bank accounts as the primary hub for consumer money management, signaling a shift in how people store and transact value. This development could reshape the financial ecosystem by offering faster, cheaper, and more accessible alternatives to traditional banking, potentially impacting banks, fintech companies, and consumers worldwide. Stablecoin wallets leverage blockchain technology to provide near-instant settlement and 24/7 availability, unlike traditional bank accounts which often have limited hours and multi-day transfer times. However, they face regulatory uncertainties and may not offer the same level of consumer protection as insured bank deposits.

rss · CoinDesk · Sep 7, 14:12

**Background**: Stablecoins are cryptocurrencies designed to maintain a stable value by pegging to assets like fiat currencies. They combine the benefits of digital assets—such as speed and low cost—with price stability, making them attractive for payments and as a store of value. Traditional bank accounts are regulated and insured, but can be slow and costly for cross-border transactions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Stablecoin">Stablecoin - Wikipedia</a></li>
<li><a href="https://www.investopedia.com/terms/s/stablecoin.asp">Stablecoins: Definition, How They Work, and Types - Investopedia</a></li>
<li><a href="https://coinspaid.com/knowledge-base/stablecoins-vs-traditional-remittances-for-business/">Stablecoins or Bank Transfers? | Coinspaid</a></li>

</ul>
</details>

**Tags**: `#stablecoins`, `#fintech`, `#cryptocurrency`, `#banking`, `#digital wallets`

---

<a id="item-17"></a>
## [Solana to Triple Transaction Size for Complex Trades](https://www.coindesk.com/tech/2026/09/07/solana-to-triple-transaction-size-as-apps-get-room-for-more-complex-trades) ⭐️ 6.0/10

Solana is set to increase its maximum transaction size from 1,232 bytes to 4,096 bytes, targeting Wednesday for the upgrade. This change, defined in SIMD-0296 and delivered via the v1 transaction format (SIMD-0385), gives developers more than three times the space for complex operations. This upgrade enables more complex trades and operations to fit within a single transaction, improving efficiency and user experience for applications on Solana. It underscores Solana's ongoing commitment to scalability, potentially attracting more sophisticated DeFi and trading applications to the ecosystem. The size increase is part of a broader effort to enhance Solana's scalability, following previous upgrades like SIMD-0286 that addressed network congestion. The change is scheduled for Wednesday, and while it triples transaction size, it does not alter the block size or transaction processing speed.

rss · CoinDesk · Sep 7, 12:08

**Background**: Solana is a high-performance blockchain known for its fast and low-cost transactions, but it has faced scalability challenges during periods of high demand. Transaction size limits affect how much data can be included in a single transaction, and larger sizes allow for more complex smart contract interactions and data payloads. This upgrade is part of Solana's roadmap to support more advanced use cases without compromising performance.

<details><summary>References</summary>
<ul>
<li><a href="https://solana.com/upgrades/larger-transaction-sizes">Larger Transaction Sizes | Solana Media</a></li>
<li><a href="https://www.coindesk.com/tech/2026/09/07/solana-to-triple-transaction-size-as-apps-get-room-for-more-complex-trades">SOL news: Solana to triple transaction size as apps get room ...</a></li>

</ul>
</details>

**Tags**: `#Solana`, `#blockchain`, `#scalability`, `#cryptocurrency`

---