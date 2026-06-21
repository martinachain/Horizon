---
layout: default
title: "Horizon Summary: 2026-06-21 (EN)"
date: 2026-06-21
lang: en
---

> From 40 items, 15 important content pieces were selected

---

1. [Loupe iOS app reveals hidden data access by native apps](#item-1) ⭐️ 8.0/10
2. [Epoll vs io_uring: Performance vs Security Trade-off](#item-2) ⭐️ 8.0/10
3. [When I Reject AI Code Even If It Works](#item-3) ⭐️ 8.0/10
4. [SMPTE Makes Its Standards Freely Accessible](#item-4) ⭐️ 8.0/10
5. [Slow Breathing Modulates Brain and Risk Behavior](#item-5) ⭐️ 7.0/10
6. [UHF X11 Brings X11 to Apple Vision Pro](#item-6) ⭐️ 7.0/10
7. [OpenRouter Fusion Beats Top AI Models at Low Cost](#item-7) ⭐️ 7.0/10
8. [Secret Network's Axelar bridge drained in $4.67M infinite-mint exploit](#item-8) ⭐️ 7.0/10
9. [Ethereum core development funding crisis warning](#item-9) ⭐️ 7.0/10
10. [F-15 Strike Eagle II Reverse Engineering Seeks Testers](#item-10) ⭐️ 6.0/10
11. [Schwab to Enter Prediction Markets with S&P 500 Event Options](#item-11) ⭐️ 6.0/10
12. [Franklin Templeton Proposes ETFs Converting Dividends to Bitcoin](#item-12) ⭐️ 6.0/10
13. [Microsoft discovers crypto wallet malware spreading via USB](#item-13) ⭐️ 6.0/10
14. [Anime Wallpaper Malware Targets Steam Gamers](#item-14) ⭐️ 6.0/10
15. [Base Beryl Upgrade and B20 Token Standard Launch June 25](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Loupe iOS app reveals hidden data access by native apps](https://github.com/mysk-research/loupe) ⭐️ 8.0/10

Loupe is an iOS app that demonstrates what data native Apple apps can access without user permissions, including volume creation date, installed apps probe, and pasteboard change count. This highlights significant iOS privacy vulnerabilities that users are unaware of, potentially prompting Apple to restrict such data access and improve privacy protections. The app categorizes data leaks into passive, permission, and advanced groups, and shows that even without permissions, apps can infer installed apps via URL scheme probing and access file creation dates.

hackernews · Cider9986 · Jun 20, 12:08 · [Discussion](https://news.ycombinator.com/item?id=48608645)

**Background**: iOS apps typically require user permission to access sensitive data like location or contacts. However, some system-level data, such as file creation dates and the list of registered URL schemes, are accessible without explicit consent. Loupe exposes these hidden data points to raise awareness.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/danielamitay/iHasApp">GitHub - danielamitay/iHasApp: The iHasApp iOS Framework allows you to detect installed apps on a user's device.</a></li>
<li><a href="https://www.danielamitay.com/blog/2011/2/16/how-to-detect-installed-ios-apps">How To Detect Installed iOS Apps - Daniel Amitay</a></li>
<li><a href="https://www.hackingwithswift.com/example-code/system/how-to-check-whether-your-other-apps-are-installed">How to check whether your other apps are installed - free Swift example code and tips</a></li>

</ul>
</details>

**Discussion**: Commenters expressed surprise at the volume creation date and installed apps probe leaks, with some comparing it favorably to Android's current state. They appreciated the educational grouping and called for OS-level fudging of such data.

**Tags**: `#iOS`, `#privacy`, `#security`, `#app development`

---

<a id="item-2"></a>
## [Epoll vs io_uring: Performance vs Security Trade-off](https://sibexi.co/posts/epoll-vs-io_uring/) ⭐️ 8.0/10

A technical article compares epoll and io_uring in Linux, highlighting io_uring's performance gains (e.g., 20% faster requests per second) but noting security concerns that limit its adoption due to kernel opt-in and past exploits. This comparison matters because io_uring could significantly improve I/O performance for high-throughput applications, but its security drawbacks prevent widespread deployment, affecting decisions in systems like Go's runtime and high-performance proxies. io_uring uses shared memory between kernel and userspace to reduce syscall overhead, but this design has led to multiple security exploits. Epoll remains the default for most production systems due to its maturity and security track record.

hackernews · Sibexico · Jun 20, 23:07 · [Discussion](https://news.ycombinator.com/item?id=48613872)

**Background**: Epoll is a Linux I/O event notification facility introduced in kernel 2.5.44, widely used for scalable network servers. io_uring is a newer asynchronous I/O interface introduced in kernel 5.1, designed to reduce syscall overhead and improve performance for both storage and network I/O. However, io_uring's shared memory model introduces security risks that have been exploited in the past.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Io_uring">io _ uring - Wikipedia</a></li>
<li><a href="https://kernel-internals.org/io-uring/io-uring-vs-epoll/">io _ uring vs epoll - Linux Kernel Internals</a></li>
<li><a href="https://devmindset.dev/en/epoll-vs-io_uring-when-the-event-loop-isnt-enough/">epoll vs io _ uring : When the Event Loop Isn't Enough | Devmindset</a></li>

</ul>
</details>

**Discussion**: Commenters note that io_uring can be 20% faster in requests per second but is often disabled for security reasons. Suggestions include using CPU pinning, concurrency kit, mimalloc, and eBPF for further optimization. Some recommend Boost.Asio for C++ asynchronous networking.

**Tags**: `#Linux`, `#I/O`, `#performance`, `#security`, `#networking`

---

<a id="item-3"></a>
## [When I Reject AI Code Even If It Works](https://vinibrasil.com/when-i-reject-ai-code-even-if-it-works/) ⭐️ 8.0/10

A developer published an article explaining why they reject AI-generated code even when it works, citing over-engineering and lack of maintainability, which sparked a rich discussion on human judgment in AI-assisted development. This matters because it highlights the nuanced trade-offs of AI-generated code, reminding developers that working code is not enough—maintainability and simplicity are critical for long-term software health. The author notes that AI often produces complex abstractions and enterprise-level patterns even for simple tasks, leading to code that is harder to maintain. Community comments compare rejecting AI code to rejecting a coworker's code for similar reasons, emphasizing that software engineering is about choosing the right solution, not just any working solution.

hackernews · vnbrs · Jun 21, 00:58 · [Discussion](https://news.ycombinator.com/item?id=48614631)

**Background**: AI-assisted coding tools like GitHub Copilot and Cursor generate code based on natural language prompts, but they often produce overly complex or boilerplate-heavy code. Developers must balance productivity gains with code quality, as maintainability and simplicity are key to long-term project success.

**Discussion**: Commenters largely agree with the author, with one noting that rejecting AI code is like rejecting a coworker's code for the same reasons—there should be no double standard. Another points out that AI tends to produce enterprise-level patterns as problem complexity increases, making it hard to find a middle ground between using AI exclusively and not at all.

**Tags**: `#AI-assisted coding`, `#code quality`, `#software engineering`, `#developer experience`, `#LLM tools`

---

<a id="item-4"></a>
## [SMPTE Makes Its Standards Freely Accessible](https://www.smpte.org/blog/smpte-makes-its-standards-freely-accessible-openingstandards-library-to-the-global-media-technology-community) ⭐️ 8.0/10

SMPTE announced that its library of over 800 media technology standards is now freely accessible to the public, with no paywall or membership required. This move removes a major barrier to innovation in media production and distribution, enabling broader participation from startups, researchers, and global developers. The initiative includes modernizing standards development with GitHub-based workflows, HTML-based authoring, and an integrated publishing pipeline for faster updates.

hackernews · zdw · Jun 20, 17:01 · [Discussion](https://news.ycombinator.com/item?id=48610827)

**Background**: SMPTE (Society of Motion Picture and Television Engineers) is a global standards body that has published over 800 standards for media technology. Previously, accessing these standards required purchasing individual documents or an institutional subscription.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Category:SMPTE_standards">Category: SMPTE standards - Wikipedia</a></li>
<li><a href="https://www.smpte.org/standards/overview">Standards Overview | Society of Motion Picture & Television ...</a></li>

</ul>
</details>

**Discussion**: Commenters largely applauded the move, with some noting legal mandates in countries like France that require freely available standards. Others highlighted the positive impact on open standards adoption and compared it to the success of IETF's no-cost model.

**Tags**: `#open standards`, `#media technology`, `#SMPTE`, `#standards bodies`

---

<a id="item-5"></a>
## [Slow Breathing Modulates Brain and Risk Behavior](https://www.cell.com/neuron/fulltext/S0896-6273(26)00339-9) ⭐️ 7.0/10

A study published in Neuron reveals that slow breathing modulates brain function and increases risk-taking behavior, with prolonged exhalation specifically enhancing reward responsiveness. This research provides a neural mechanism linking breathing to risk-taking and has practical implications for managing anxiety, panic disorder, and public speaking by leveraging bottom-up regulation from body to brain. The study found that slow breathing with prolonged exhalation selectively impacts reward processing, which may be beneficial for clinical contexts with distinct autonomic signatures like anxiety and depression.

hackernews · croes · Jun 20, 22:22 · [Discussion](https://news.ycombinator.com/item?id=48613555)

**Background**: Slow breathing is a common technique to calm nerves, often recommended before public speaking. This study explores how it affects brain function and behavior, specifically risk-taking, through parasympathetic nervous system activation.

**Discussion**: Community comments highlight the practical use of slow breathing for public speaking and note the interesting link between parasympathetic activation and risk-taking. Some point out that yoga has long advocated this practice, while others caution that fear can be adaptive and breathing should only counter irrational fear.

**Tags**: `#neuroscience`, `#breathing`, `#risk behavior`, `#anxiety`, `#psychology`

---

<a id="item-6"></a>
## [UHF X11 Brings X11 to Apple Vision Pro](https://www.lispm.net/apps/uhf-x11/) ⭐️ 7.0/10

UHF X11 is a new app that ports the classic X11 windowing system to Apple's visionOS, allowing users to run 2D and 3D X11 applications inside the Apple Vision Pro headset. This bridges the gap between legacy Unix/Linux graphical environments and modern mixed reality, enabling developers and enthusiasts to use familiar X11 tools in a VR space. It also showcases the flexibility of visionOS for running non-native windowing systems. The app supports GLX rendering for OpenGL clients, though compatibility varies. It uses a 2D-in-3D approach, displaying X11 windows as flat surfaces within the 3D environment.

hackernews · zdw · Jun 20, 17:04 · [Discussion](https://news.ycombinator.com/item?id=48610853)

**Background**: X11 is the windowing system for Unix-like operating systems, first released in 1987. visionOS is Apple's mixed reality operating system for the Apple Vision Pro headset, launched in 2024. UHF X11 is developed by Ian Finder and is available on the App Store.

<details><summary>References</summary>
<ul>
<li><a href="https://apps.apple.com/us/app/uhf-x11/id6772673274">UHF X11 App - App Store</a></li>
<li><a href="https://news.ycombinator.com/item?id=48610853">UHF X11: X11 Built for VisionOS and Apple Vision Pro | Hacker News</a></li>
<li><a href="https://en.wikipedia.org/wiki/X_Windowing_System">X Windowing System</a></li>

</ul>
</details>

**Discussion**: Commenters found the project amusing and creative, with one noting the irony of "3D in 2D in 3D." Some compared it to WayVR for Linux, while others speculated that X11 might outlive visionOS. A user also asked for Linux AR headset recommendations with prescription lens support.

**Tags**: `#X11`, `#VisionOS`, `#Apple Vision Pro`, `#VR/AR`, `#retrocomputing`

---

<a id="item-7"></a>
## [OpenRouter Fusion Beats Top AI Models at Low Cost](https://decrypt.co/371711/openrouter-fusion-claude-fable-level-ai-cheap) ⭐️ 7.0/10

OpenRouter launched its Fusion API, which stacks multiple budget AI models to achieve benchmark scores surpassing GPT-5.5 and Claude Opus 4.8, all at a fraction of the cost. This comes as Anthropic's high-end Fable 5 model was suspended by US authorities. This development offers a cost-effective alternative to expensive proprietary models, democratizing access to high-performance AI. It also highlights the vulnerability of relying on a single model provider, as seen with Fable 5's sudden shutdown. The Fusion API uses a multi-model deliberation process: a panel of models generates responses, a judge model selects the best, and a final answer is returned in a single API call. OpenRouter claims it matches Fable 5's performance at half the cost.

rss · Decrypt · Jun 20, 18:01

**Background**: OpenRouter is a platform that provides a unified API to access many AI models from different providers. Model stacking, or ensemble methods, combine outputs from multiple models to improve accuracy and robustness. Fable 5 is Anthropic's most advanced model, recently suspended due to US export control concerns.

<details><summary>References</summary>
<ul>
<li><a href="https://openrouter.ai/fusion">Model Fusion | OpenRouter</a></li>
<li><a href="https://openrouter.ai/docs/guides/routing/routers/fusion-router">Fusion Router | Multi-model AI Deliberation with OpenRouter | OpenRouter | Documentation</a></li>
<li><a href="https://www.mindstudio.ai/blog/what-is-openrouter-fusion-multi-model-api">What Is OpenRouter Fusion? The Multi-Model API That Matches Claude Fable 5 at Half the Cost | MindStudio</a></li>

</ul>
</details>

**Tags**: `#AI`, `#benchmarking`, `#model stacking`, `#OpenRouter`, `#cost efficiency`

---

<a id="item-8"></a>
## [Secret Network's Axelar bridge drained in $4.67M infinite-mint exploit](https://www.theblock.co/post/405459/secret-networks-axelar-bridge-drained-for-4-67-million-in-infinite-mint-exploit-that-went-unnoticed-for-seven-days?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

An attacker exploited a missing validation check in a Secret Network smart contract to mint $4.67 million in unbacked Axelar-bridged tokens and drain the real assets from escrow. The exploit went unnoticed for seven days, and about $770,000 of the stolen funds still sits in the attacker's Axelar wallet. This incident highlights critical vulnerabilities in cross-chain bridge infrastructure, which are essential for DeFi interoperability. The seven-day undetected period and the dispute over fund freezing underscore the challenges in securing such systems and coordinating responses across multiple chains. The flaw had existed in the deployed code since March 2023, and the attacker exploited a modified IBC bridge contract connecting Axelar to Secret Network. Axelar declined Secret Network's request to freeze the remaining $770,000 in the attacker's wallet.

rss · The Block · Jun 20, 21:57

**Background**: Cross-chain bridges like Axelar allow tokens to be transferred between different blockchains by locking assets on one chain and minting wrapped tokens on another. The infinite-mint exploit occurs when a smart contract fails to validate that the minted tokens are backed by locked assets, allowing an attacker to create unbacked tokens and drain the real reserves.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/405459/secret-networks-axelar-bridge-drained-for-4-67-million-in-infinite-mint-exploit-that-went-unnoticed-for-seven-days">Secret Network ’s Axelar bridge drained for $4.67 million... | The Block</a></li>
<li><a href="https://www.cryptopolitan.com/axelar-bridged-tokens-worth-4-67-million-drained-in-secret-network-contract-exploit/">Axelar - bridged tokens worth $4.67 million drained in Secret Network ...</a></li>
<li><a href="https://www.binance.com/en/square/post/06-20-2026-axelar-disables-secret-network-ibc-links-after-4-67-million-token-theft-335967137697025">Axelar Disables Secret Network ... | Binance News on Binance Square</a></li>

</ul>
</details>

**Tags**: `#security`, `#exploit`, `#DeFi`, `#cross-chain bridge`, `#Axelar`

---

<a id="item-9"></a>
## [Ethereum core development funding crisis warning](https://www.theblock.co/post/405404/ethereum-could-face-core-development-funding-crisis-within-nine-months-says-former-ef-contributor?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Former Ethereum Foundation contributor VanEpps warned that Ethereum's core development could face a funding crisis within 3 to 9 months after the Community Incentive Program (CIP) expires. This warning highlights a potential threat to Ethereum's core development and ecosystem health, as funding shortages could slow down protocol upgrades and client maintenance. The CIP was launched in 2021 to provide long-term support for client teams, and its expiration could leave core developers without sufficient funding. VanEpps suggests that for-profit entities like large stakers may need to step in to fill the gap.

rss · The Block · Jun 19, 10:11

**Background**: The Ethereum Foundation (EF) has historically funded core development through grants and programs like the CIP. However, the EF's treasury has been drawn down, and its funding model has shifted from open applications to a more proactive, needs-driven structure. Some argue that as Ethereum matures, for-profit entities dependent on the network will naturally fund its maintenance.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.ethereum.org/2021/12/13/client-incentive-program">Announcing the Client Incentive Program - Ethereum Foundation Blog</a></li>
<li><a href="https://www.studioglobal.ai/discover/answers/searching-with-cited-sources-for-given-that-6a36ac941c610f3e5345dd90">The $30 Million Question: Is Ethereum's Core Development Facing a ...</a></li>
<li><a href="https://ethereum.org/community/grants">Ethereum Foundation & community grant programs | ethereum.org</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#funding crisis`, `#core development`, `#blockchain`

---

<a id="item-10"></a>
## [F-15 Strike Eagle II Reverse Engineering Seeks Testers](https://neuviemeporte.github.io/f15-se2/2026/06/20/needyou.html) ⭐️ 6.0/10

A developer is reversing the DOS game F-15 Strike Eagle II from assembly to C, aiming to port it to modern platforms, and is asking for testers to find bugs in the current version. This project preserves a classic flight simulator and makes it playable on modern systems without emulation, benefiting retro gaming enthusiasts and demonstrating a rigorous reverse engineering methodology. The process involves first fully reversing to assembler, then converting assembler to binary-equal compiled C code, all still running on DOS until no assembler code remains, after which porting to Linux and Windows begins.

hackernews · LowLevelMahn · Jun 20, 15:10 · [Discussion](https://news.ycombinator.com/item?id=48609766)

**Background**: F-15 Strike Eagle II is a 1989 flight simulator by MicroProse, originally for DOS. Reverse engineering translates machine code back into higher-level source code to understand and modify the game. Porting adapts software to run on different platforms, often requiring significant rework.

<details><summary>References</summary>
<ul>
<li><a href="https://news.ycombinator.com/item?id=40347662">DOS game “ F - 15 Strike Eagle II ” reverse engineering /reconstruction...</a></li>
<li><a href="https://de.wikipedia.org/wiki/F-15_Strike_Eagle">F - 15 Strike Eagle – Wikipedia</a></li>
<li><a href="https://maniacsvault.net/articles/dosporting">Porting Games from DOS to Modern Platforms - Blzut3's Weblog</a></li>

</ul>
</details>

**Discussion**: Commenters discussed the motivation for decompilation over emulation, with some noting the ease of porting with modern APIs. Others shared nostalgia and asked about AI-assisted reverse engineering, while the developer clarified the multi-step process and need for testers.

**Tags**: `#reverse engineering`, `#DOS games`, `#retro computing`, `#porting`

---

<a id="item-11"></a>
## [Schwab to Enter Prediction Markets with S&P 500 Event Options](https://www.coindesk.com/markets/2026/06/19/schwab-to-join-prediction-markets-race-with-s-and-p-500-event-based-options-wsj) ⭐️ 6.0/10

Charles Schwab plans to offer S&P 500 event-based options, entering the prediction markets space as reported by the Wall Street Journal. This move by a major financial institution could legitimize prediction markets and attract traditional investors, potentially expanding the market for event-based derivatives. The options will be based on the S&P 500 index and tied to specific events, though exact event types and launch dates have not been disclosed.

rss · CoinDesk · Jun 19, 17:51

**Background**: Prediction markets allow trading on the outcome of future events, with prices reflecting the crowd's probability estimate. Event-based options are a type of derivative that pays out based on whether a specific event occurs. Charles Schwab is a global financial institution known for brokerage and banking services.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prediction_market">Prediction market</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#finance`, `#options trading`, `#S&P 500`

---

<a id="item-12"></a>
## [Franklin Templeton Proposes ETFs Converting Dividends to Bitcoin](https://www.coindesk.com/daybook-us/2026/06/19/franklin-templeton-proposes-new-funds-that-turn-corporate-dividends-into-bitcoin) ⭐️ 6.0/10

Franklin Templeton has filed for two new ETFs, the 'Bitcoin DRIP' funds, which would hold U.S. stocks and reinvest their dividends into Bitcoin, with an expected effective date as early as September 1, 2026. This innovation bridges traditional finance and cryptocurrency, offering investors a way to gain Bitcoin exposure through dividend reinvestment without directly buying crypto. It could pave the way for more hybrid financial products from major asset managers. The funds will track the VettaFi US Large-Cap 500 Bitcoin DRIP and VettaFi US Innovation 100 Bitcoin DRIP indices, with a portfolio of 95% stocks and 5% Bitcoin, capped at 20% Bitcoin exposure. DRIP stands for Dividend Reinvestment Plan, a traditional concept adapted here for crypto.

rss · CoinDesk · Jun 19, 11:27

**Background**: A Dividend Reinvestment Plan (DRIP) allows investors to automatically use cash dividends to purchase additional shares of the same stock. Franklin Templeton's proposed ETFs apply this concept to Bitcoin, where dividends from U.S. stocks are used to buy Bitcoin-linked investments, systematically building crypto exposure over time.

<details><summary>References</summary>
<ul>
<li><a href="https://www.benzinga.com/etfs/new-etfs/26/06/60002555/franklin-templeton-files-bitcoin-drip-etfs-that-reinvest-stock-dividends-into-crypto">Franklin Templeton Files Bitcoin ETFs That Reinvest... - Benzinga</a></li>
<li><a href="https://cointelegraph.com/news/franklin-templeton-bitcoin-drip-etfs-reinvest-stock-dividends-btc-exposure">Franklin Templeton files ETFs that turn stock dividends into Bitcoin ...</a></li>
<li><a href="https://cryptobriefing.com/franklin-bitcoin-drip-etfs-dividends/">Franklin Templeton files two Bitcoin DRIP ETFs that funnel stock ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#ETFs`, `#finance`, `#bitcoin`

---

<a id="item-13"></a>
## [Microsoft discovers crypto wallet malware spreading via USB](https://www.coindesk.com/tech/2026/06/19/microsoft-found-malware-that-hijacks-crypto-wallets-and-spreads-through-usb-sticks) ⭐️ 6.0/10

Microsoft has identified a new malware strain, dubbed a 'crypto clipper,' that hijacks cryptocurrency wallets by replacing copied wallet addresses with attacker-controlled ones and spreads via infected USB drives since February 2026. This malware poses a significant threat to cryptocurrency users, as it can silently redirect funds to attackers during transactions, and its USB propagation method increases the risk of widespread infection in shared environments. The malware is a clipboard hijacker that monitors the clipboard for cryptocurrency addresses and replaces them with the attacker's address. It spreads through USB drives using the Windows AutoRun feature, infecting new machines when the drive is plugged in.

rss · CoinDesk · Jun 19, 08:48

**Background**: Clipboard hijacking malware, or 'crypto clippers,' have been a known threat in the cryptocurrency space, often distributed via phishing or compromised websites. USB-based propagation adds a physical vector, making it harder to detect and block with traditional network defenses. Microsoft's discovery highlights the evolving tactics of cybercriminals targeting digital asset holders.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/06/19/microsoft-found-malware-that-hijacks-crypto-wallets-and-spreads-through-usb-sticks">Microsoft identifies malware 'worm' that hijacks crypto wallets ...</a></li>
<li><a href="https://cncintel.com/clipboard-hijacking/">Clipboard Hijacking Malware Removal - CNC Intelligence</a></li>
<li><a href="https://ophtek.com/viruses-on-usb-thumb-drives/">Spreading Viruses on USB Thumb Drives</a></li>

</ul>
</details>

**Tags**: `#malware`, `#cryptocurrency`, `#security`, `#USB`

---

<a id="item-14"></a>
## [Anime Wallpaper Malware Targets Steam Gamers](https://decrypt.co/371632/anime-girls-steal-crypto-wallpaper-malware-targets-steam-gamers) ⭐️ 6.0/10

Kaspersky researchers discovered dozens of malicious Wallpaper Engine downloads on Steam Workshop that distribute infostealers, backdoors, and account-hijacking malware. This campaign exploits a trusted platform (Steam) and a popular app (Wallpaper Engine) to infect gamers, potentially leading to credential theft, account takeover, and financial loss. The malicious wallpapers are of the 'Application' type, which can execute arbitrary code, and the campaign primarily targets Chinese users. Some wallpapers have been downloaded tens of thousands of times.

rss · Decrypt · Jun 19, 14:39

**Background**: Wallpaper Engine is a Steam application that allows users to create and share animated or interactive desktop wallpapers. Some wallpapers are executable Windows applications, which can be abused to run malware. Infostealers are malware that steal personal information like login credentials and financial data.

<details><summary>References</summary>
<ul>
<li><a href="https://www.kaspersky.com/about/press-releases/kaspersky-discovered-a-malware-campaign-targeting-steam-users-through-infected-wallpaper">Kaspersky discovered a malware campaign targeting Steam users through infected wallpaper</a></li>
<li><a href="https://www.bleepingcomputer.com/news/security/steam-workshop-abused-to-spread-malware-via-wallpaper-engine-app/">Steam Workshop abused to spread malware via Wallpaper Engine app</a></li>
<li><a href="https://steamcommunity.com/app/431960/discussions/2/569289424252266099/">Malware in wallpapers? :: Wallpaper Engine General Discussions</a></li>

</ul>
</details>

**Discussion**: Community comments on Steam indicate that the issue is limited to Application-type wallpapers and mainly targets Chinese users, with many users expressing relief that they are not affected. Some users advise scanning downloads with antivirus software.

**Tags**: `#cybersecurity`, `#malware`, `#steam`, `#infostealer`, `#wallpaper engine`

---

<a id="item-15"></a>
## [Base Beryl Upgrade and B20 Token Standard Launch June 25](https://www.theblock.co/post/405410/base-targets-june-25-mainnet-launch-for-beryl-upgrade-and-new-b20-token-standard?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Base's Beryl upgrade introduces the B20 native token standard and reduces withdrawal delays to 5 days, activating on mainnet June 25, 2026. The B20 standard bakes compliance tooling directly into the protocol layer, making Base more attractive for regulated stablecoins and real-world assets, while faster withdrawals improve user experience for bridged funds. B20 is Base's own version of ERC-20 with built-in transfer policies, freeze-and-seize, role-based access control, memos, and supply caps. Node operators must upgrade to base-reth-node v1.1.1+ or base-consensus v1.1.1+ before the cutover.

rss · The Block · Jun 19, 10:48

**Background**: Base is a layer-2 blockchain built on Ethereum, developed by Coinbase. Token standards like ERC-20 define how tokens behave on a blockchain. The B20 standard aims to provide regulatory compliance features natively, which is important for institutional adoption of digital assets.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.base.org/base-chain/specs/upgrades/beryl/b20">B 20 Native Token Standard - Base Documentation</a></li>
<li><a href="https://cryptobriefing.com/base-b20-token-standard-stablecoins-rwas/">Base 's Jesse Pollak unveils B 20 token standard for stablecoins and...</a></li>
<li><a href="https://www.spotedcrypto.com/base-beryl-upgrade-june-25-2026-b20-token-standard/">Base Beryl Upgrade June 25 2026: B20 Token Standard, Faster</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#cryptocurrency`, `#token standard`, `#Base`, `#upgrade`

---