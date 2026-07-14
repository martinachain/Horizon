---
layout: default
title: "Horizon Summary: 2026-07-14 (EN)"
date: 2026-07-14
lang: en
---

> From 64 items, 15 important content pieces were selected

---

1. [Git History Command: A Safer Alternative to Interactive Rebase](#item-1) ⭐️ 7.0/10
2. [Building Mac/iOS Apps Without Xcode via CLI](#item-2) ⭐️ 7.0/10
3. [Apple SpeechAnalyzer API Benchmarked vs Whisper](#item-3) ⭐️ 7.0/10
4. [California Bill Could Ban Infinite Scroll and Addictive UX](#item-4) ⭐️ 7.0/10
5. [The Art and Engineering of Sega CD Silpheed](#item-5) ⭐️ 7.0/10
6. [Major Banks Join UK Tokenization Taskforce](#item-6) ⭐️ 7.0/10
7. [Claude's Personality Varies by Model and Language](#item-7) ⭐️ 7.0/10
8. [Robinhood Chain Overrun by Memecoins Despite Tokenized Stock Vision](#item-8) ⭐️ 6.0/10
9. [Bolivia Considers Adding Tether's USDT to National Payments](#item-9) ⭐️ 6.0/10
10. [SBI Holdings Pivots to Solana for Tokenization and Stablecoins](#item-10) ⭐️ 6.0/10
11. [OpenAI's GPT-5.6 Guide: Stop Over-Prompting](#item-11) ⭐️ 6.0/10
12. [Protesters March on AI Giants Demanding Development Pause](#item-12) ⭐️ 6.0/10
13. [China Proposes Crypto Mixer, Privacy Coins as Money Laundering Signs](#item-13) ⭐️ 6.0/10
14. [Japan's top security token platform moves $2.7B to Avalanche](#item-14) ⭐️ 6.0/10
15. [Bank of Thailand Audits High-Volume Stablecoin Trades](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Git History Command: A Safer Alternative to Interactive Rebase](https://lalitm.com/post/git-history/) ⭐️ 7.0/10

A blog post advocates for the `git history` command as a safer and more intuitive way to edit commit history compared to interactive rebase, highlighting its ability to automatically rewrite all descendant branches. This matters because many developers fear interactive rebase due to its complexity and risk of breaking the repository, and `git history` offers a less error-prone workflow for curating commit history, potentially improving team collaboration and code review. The `git history` command automatically finds and rewrites every local branch descended from the edited commit, unlike `git rebase --update-refs` which only moves refs inside the rebase range. However, it currently lacks support for signing modified commits, which is a limitation for users requiring cryptographic verification.

hackernews · turbocon · Jul 14, 00:57 · [Discussion](https://news.ycombinator.com/item?id=48901010)

**Background**: Git history editing is commonly done via interactive rebase (`git rebase -i`), which allows squashing, reordering, or amending commits. However, interactive rebase can be intimidating and error-prone, especially when dealing with multiple branches. The `git history` command, introduced in Git 2.23, provides a higher-level interface that automatically handles branch rewriting, reducing manual steps and potential mistakes.

<details><summary>References</summary>
<ul>
<li><a href="https://git-scm.com/book/en/v2/Git-Basics-Viewing-the-Commit-History">Git - Viewing the Commit History</a></li>
<li><a href="https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase">Git rebase | Atlassian Git Tutorial</a></li>
<li><a href="https://stackoverflow.com/questions/7435452/history-or-log-of-commands-executed-in-git">History or log of commands executed in Git - Stack Overflow</a></li>

</ul>
</details>

**Discussion**: The community discussion is mixed: some users praise `git history` for its safety and convenience, while others argue that interactive rebase is not as scary as portrayed, noting the existence of `--abort` and reset options. A key concern raised is the lack of commit signing support in `git history`, which is a dealbreaker for some.

**Tags**: `#git`, `#version control`, `#developer tools`, `#workflow`

---

<a id="item-2"></a>
## [Building Mac/iOS Apps Without Xcode via CLI](https://scottwillsey.com/building-and-shipping-mac-and-ios-apps-without-ever-opening-xcode/) ⭐️ 7.0/10

A detailed guide demonstrates how to build, sign, notarize, and ship Mac and iOS apps entirely from the command line and automation scripts, bypassing the Xcode IDE entirely. This approach enables developers to integrate Apple app development into CI/CD pipelines and leverage LLM-based coding agents, potentially accelerating workflows and reducing dependency on Apple's heavyweight IDE. The guide uses tools like `xcodebuild`, `codesign`, and `notarytool` from the command line, and suggests using LLM agents (e.g., Claude Code) to generate the automation scripts. Community comments highlight alternative tools like xtool for Linux-based iOS builds.

hackernews · speckx · Jul 13, 18:22 · [Discussion](https://news.ycombinator.com/item?id=48896665)

**Background**: Traditionally, developing and shipping Apple platform apps requires Xcode, Apple's integrated development environment. However, Xcode is large, macOS-only, and not ideal for automation. The command-line tools bundled with Xcode (e.g., xcodebuild) allow building apps without the GUI, but full automation of signing and notarization has been complex. This guide simplifies that process.

<details><summary>References</summary>
<ul>
<li><a href="https://stackoverflow.com/questions/69315164/how-to-create-an-ios-app-build-using-command-line-tool-without-xcode/69315458">swift - How to create an iOS app build using command line tool...</a></li>

</ul>
</details>

**Discussion**: Commenters express security concerns about running LLM agents on the host machine without sandboxing, citing risks like credential exposure. Some share alternative tools such as xtool for Linux-based iOS development and Axiom for LLM-friendly Apple development. Overall sentiment is positive but cautious.

**Tags**: `#iOS development`, `#automation`, `#Xcode`, `#CLI`, `#security`

---

<a id="item-3"></a>
## [Apple SpeechAnalyzer API Benchmarked vs Whisper](https://get-inscribe.com/blog/apple-speech-api-benchmark.html) ⭐️ 7.0/10

A new benchmark compares Apple's SpeechAnalyzer API (introduced at WWDC 2025) against OpenAI's Whisper and Apple's previous speech framework, showing faster performance with slightly lower accuracy. This comparison matters because Apple's on-device API could disrupt paid apps that wrap Whisper, offering native, faster transcription on macOS and iOS, potentially reshaping the speech-to-text market. The benchmark tested SpeechAnalyzer against Whisper-Large-V2 on a math lecture, finding it substantially faster and only slightly worse in accuracy. SpeechAnalyzer also supports streaming, a key UX improvement over many models that require full audio recording before transcription.

hackernews · get-inscribe · Jul 13, 16:06 · [Discussion](https://news.ycombinator.com/item?id=48894752)

**Background**: Whisper is an open-source ASR model by OpenAI, trained on 680,000 hours of data, known for robust multilingual transcription. Apple's SpeechAnalyzer, introduced at WWDC 2025, is a modular on-device speech recognition API that replaces older frameworks, aiming for low-latency performance.

<details><summary>References</summary>
<ul>
<li><a href="https://www.argmaxinc.com/blog/apple-and-argmax">Apple SpeechAnalyzer and Argmax WhisperKit - Argmax</a></li>
<li><a href="https://www.callstack.com/blog/on-device-speech-transcription-with-apple-speechanalyzer">On-Device Speech Transcription with Apple SpeechAnalyzer and AI SDK</a></li>
<li><a href="https://en.wikipedia.org/wiki/Whisper_(speech_recognition_system)">Whisper (speech recognition system)</a></li>

</ul>
</details>

**Discussion**: Commenters noted that Whisper is no longer state-of-the-art; newer models like Nvidia's Nemotron and Parakeet, Mistral's Voxtral, and Cohere Transcribe offer better accuracy. Some predicted Apple's native API will render paid Whisper wrapper apps obsolete, while others praised streaming support as a major UX win.

**Tags**: `#speech recognition`, `#Apple`, `#Whisper`, `#benchmark`, `#ASR`

---

<a id="item-4"></a>
## [California Bill Could Ban Infinite Scroll and Addictive UX](https://www.sfgate.com/politics/article/meta-social-media-teenagers-22337724.php) ⭐️ 7.0/10

A proposed California law, SB 976 (Protecting Our Kids from Social Media Addiction Act), could ban infinite scroll and other addictive features on social media platforms for minors. The bill was signed into law in September 2024 and makes it unlawful to provide addictive feeds and certain features to users under 18. This legislation could set a precedent for regulating UX design patterns that are widely used but criticized for promoting compulsive usage. If passed, it would force platforms like Instagram, TikTok, and Facebook to redesign core user experiences for minors, potentially reshaping the social media landscape. The bill specifically targets 'addictive feeds' that use algorithms to recommend content based on user data, and features like infinite scroll that eliminate natural stopping points. Platforms would need to provide a non-addictive version for minors, default to chronological feeds, and limit notifications during certain hours.

hackernews · Stratoscope · Jul 13, 18:53 · [Discussion](https://news.ycombinator.com/item?id=48897104)

**Background**: Infinite scroll is a UX design technique that automatically loads new content as the user scrolls, eliminating pagination. It is widely used by social media and content platforms to increase engagement, but critics argue it exploits psychological vulnerabilities to keep users hooked. Addictive design patterns are a subset of dark patterns that drive compulsive behavior against user interests.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/design-bootcamp/the-scroll-that-never-sleeps-how-ux-keeps-us-hooked-5bb86740e308">The Scroll That Never Sleeps — How UX Keeps Us Hooked | Medium</a></li>
<li><a href="https://builtin.com/articles/infinite-scroll">Infinite Scroll Advantages and Disadvantages | Built In</a></li>
<li><a href="https://oag.ca.gov/sb976">Protecting Our Kids from Social Media Addiction Act (SB 976) | State of California - Department of Justice - Office of the Attorney General</a></li>

</ul>
</details>

**Discussion**: Commenters debated where to draw the line between good UX and addictive design. Some argued infinite scroll is clearly unnecessary and intended to keep users on apps longer, while others questioned whether features like media previews are addictive or just convenient. A few suggested banning targeted advertising as a more fundamental solution.

**Tags**: `#UX design`, `#regulation`, `#social media`, `#addictive features`, `#California law`

---

<a id="item-5"></a>
## [The Art and Engineering of Sega CD Silpheed](https://fabiensanglard.net/silpheed/index.html) ⭐️ 7.0/10

Fabien Sanglard published a technical deep-dive article analyzing how the Sega CD game Silpheed used full-motion video (FMV) to simulate 3D polygon graphics, revealing the engineering tricks behind its impressive visuals. This article provides rare insight into the ingenuity of early 1990s game developers who worked around hardware limitations, and it highlights the intersection of FMV and 3D simulation that influenced later game design. Silpheed on Sega CD is an FMV game that uses pre-rendered video to create the illusion of 3D space, with the player's ship and enemies composited over the video. The article details the video compression, color palette tricks, and synchronization techniques that made this possible.

hackernews · ibobev · Jul 13, 14:52 · [Discussion](https://news.ycombinator.com/item?id=48893639)

**Background**: Full-motion video (FMV) games use pre-recorded video files instead of real-time rendered graphics to display action. The Sega CD, an add-on for the Sega Genesis, had limited 3D capabilities, so developers often used FMV to create cinematic experiences. Silpheed is notable for blending FMV with interactive gameplay, making it feel like a playable movie.

<details><summary>References</summary>
<ul>
<li><a href="https://fabiensanglard.net/silpheed/index.html">The art and engineering of Sega CD Silpheed</a></li>
<li><a href="https://en.wikipedia.org/wiki/Silpheed">Silpheed - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/FMV_game">FMV game</a></li>

</ul>
</details>

**Discussion**: Commenters praised the article and shared nostalgic memories of Silpheed, with one calling it 'unlike anything else' and noting how it felt like controlling a movie. Others pointed to related demoscene achievements, such as the Mega Drive demo 'Overdrive 2', which pushed hardware limits in similar ways.

**Tags**: `#retro gaming`, `#game development`, `#Sega CD`, `#technical deep-dive`, `#demoscene`

---

<a id="item-6"></a>
## [Major Banks Join UK Tokenization Taskforce](https://www.coindesk.com/business/2026/07/13/uk-government-unveils-tokenization-taskforce-with-blackrock-goldman-jpmorgan-morgan-stanley) ⭐️ 7.0/10

The UK government has launched a 54-firm tokenization taskforce including BlackRock, Goldman Sachs, JPMorgan, and Morgan Stanley to explore live wholesale market use cases for blockchain-based asset tokenization. This initiative signals strong institutional adoption of tokenization, potentially accelerating regulatory frameworks and mainstream integration of digital assets in traditional finance. The taskforce includes both traditional financial giants and crypto-native firms like Ripple and Coinbase, aiming to test tokenization in wholesale markets such as bonds and repurchase agreements.

rss · CoinDesk · Jul 13, 11:40

**Background**: Asset tokenization involves representing ownership of real-world assets (e.g., bonds, real estate) as digital tokens on a blockchain, enabling fractional ownership and faster settlement. The UK has been actively positioning itself as a crypto-friendly hub, and this taskforce is part of broader efforts to integrate blockchain into financial infrastructure.

<details><summary>References</summary>
<ul>
<li><a href="https://coincentral.com/uk-tokenization-taskforce-adds-ripple-blackrock-goldman-sachs-and-jpmorgan/">UK Tokenization Taskforce Adds Ripple, BlackRock, Goldman ...</a></li>
<li><a href="https://www.cryptopolitan.com/uk-tokenization-task-force-with-blackrock/">Circle, Ripple and Coinbase join UK tokenization task force ...</a></li>
<li><a href="https://coinfomania.com/blackrock-joins-uk-tokenization-taskforce-and-why-its-not-just-hype/">BlackRock Joins UK Tokenization Taskforce — And Why It's Not ...</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#blockchain`, `#finance`, `#regulation`

---

<a id="item-7"></a>
## [Claude's Personality Varies by Model and Language](https://decrypt.co/373422/anthropic-claude-personality-changes-model-language) ⭐️ 7.0/10

Anthropic's new research reveals that Claude consistently expresses different values depending on the model variant and the language used, indicating a lack of value consistency across deployments. This finding raises concerns for AI alignment and safety, especially for multilingual AI systems where inconsistent values could lead to unpredictable or harmful behavior across different user groups. The research specifically examined Claude's expressed values across different model versions (e.g., Claude 3, Claude 4) and languages (e.g., English, Chinese, Spanish), finding systematic variations rather than random noise.

rss · Decrypt · Jul 13, 20:39

**Background**: AI alignment research aims to ensure that AI systems behave in accordance with human values and intentions. Multilingual AI systems like Claude are trained on data from multiple languages, but value alignment is typically done in English, which may not transfer perfectly to other languages.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/research/team/alignment">Alignment Research \ Anthropic</a></li>
<li><a href="https://arxiv.org/html/2402.18120v1">Exploring Multilingual Human Value Concepts in Large Language ...</a></li>

</ul>
</details>

**Tags**: `#AI alignment`, `#Anthropic`, `#multilingual AI`, `#model behavior`

---

<a id="item-8"></a>
## [Robinhood Chain Overrun by Memecoins Despite Tokenized Stock Vision](https://www.coindesk.com/tech/2026/07/13/robinhood-built-a-blockchain-for-tokenized-stocks-memecoins-took-over) ⭐️ 6.0/10

Robinhood Chain, an Ethereum Layer 2 blockchain launched on July 1, 2026, has reached $3.1 billion in weekly DEX volume and 65,000 users, but memecoin trading dominates activity rather than the intended tokenized stocks. This highlights the challenge of steering blockchain adoption toward regulated financial assets, as permissionless environments naturally attract speculative memecoin trading, potentially undermining Robinhood's goal of tokenizing traditional equities. Robinhood Chain is an Ethereum Layer 2 scaling solution designed to support tokenized stocks, but since its launch, memecoin trading has accounted for the majority of its $3.1 billion weekly DEX volume, according to Bernstein.

rss · CoinDesk · Jul 13, 15:17

**Background**: Tokenized stocks are blockchain-based representations of traditional equities, allowing fractional ownership and 24/7 trading. Layer 2 blockchains like Robinhood Chain are built on top of Ethereum to increase transaction speed and reduce costs. Memecoins are highly volatile cryptocurrencies often based on internet memes, which attract speculative traders.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cryptotimes.io/learn/what-is-robinhood-chain/">What Is Robinhood Chain ? Ethereum Layer 2 Explained</a></li>
<li><a href="https://www.coingecko.com/learn/what-are-tokenized-stocks">What Are Tokenized Stocks and Top Platforms to Get Started</a></li>
<li><a href="https://en.wikipedia.org/wiki/Layer-1_blockchain">Layer-1 blockchain</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#cryptocurrency`, `#memecoins`, `#Robinhood`, `#tokenization`

---

<a id="item-9"></a>
## [Bolivia Considers Adding Tether's USDT to National Payments](https://www.coindesk.com/business/2026/07/13/bolivia-weighs-adding-tether-s-usdt-to-its-national-payments-system) ⭐️ 6.0/10

Bolivia's Economy Minister José Gabriel Espinoza announced on July 10, 2026, that the government is technically evaluating whether Tether's USDT stablecoin can circulate in the national payment system alongside the US dollar and the boliviano. If approved, this would mark a significant step in cryptocurrency adoption by a national government, potentially modernizing Bolivia's economy and providing a stable digital alternative amid dollar shortages. It could also set a precedent for other countries exploring stablecoin integration. The evaluation is preliminary and no final decision has been made. USDT is the world's largest stablecoin by market capitalization, pegged 1:1 to the US dollar, and is distinct from a central bank digital currency (CBDC).

rss · CoinDesk · Jul 13, 14:47

**Background**: Tether (USDT) is a cryptocurrency stablecoin launched in 2014 by Tether Limited, designed to maintain a stable value relative to the US dollar. Bolivia has faced dollar shortages and is exploring digital alternatives to modernize its payment system and enhance access to global markets.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tether_(cryptocurrency)">Tether (cryptocurrency) - Wikipedia</a></li>
<li><a href="https://coinlaw.io/bolivia-usdt-payments/">Bolivia Weighs Adding USDT to Its National Payment System</a></li>
<li><a href="https://www.cryptotimes.io/2026/07/13/bolivia-weighs-usdt-integration-into-national-payment-system/">Bolivia Weighs USDT Integration Into National Payment System</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#stablecoin`, `#payments`, `#regulation`, `#Bolivia`

---

<a id="item-10"></a>
## [SBI Holdings Pivots to Solana for Tokenization and Stablecoins](https://www.coindesk.com/business/2026/07/13/sbi-holdings-blockchain-initiative-pivots-to-solana-for-tokenization-stablecoin-issuance) ⭐️ 6.0/10

SBI Holdings and the Solana Foundation announced a strategic collaboration to build a Japan-based onchain financial market, with SBI R3 Japan rebranding as SBI Solana Global. This pivot signals growing institutional adoption of Solana for real-world asset tokenization and stablecoin issuance, potentially accelerating mainstream blockchain integration in traditional finance. SBI R3 Japan, originally focused on R3 Corda, will rebrand to SBI Solana Global, with the Solana Foundation as a key partner. SBI previously launched SOL services for institutional clients and partnered with B2C2 for routing on Solana.

rss · CoinDesk · Jul 13, 11:40

**Background**: SBI Holdings is a major Japanese financial conglomerate with a crypto exchange, Ripple investment, and blockchain funds. Solana is a high-performance blockchain known for low fees and high throughput, increasingly used for tokenization and decentralized finance.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theblock.co/post/408010/sbi-holdings-solana-foundation-partner-to-build-japan-based-onchain-financial-market">SBI Holdings, Solana Foundation partner to build... | The Block</a></li>
<li><a href="https://www.kucoin.com/news/flash/japanese-megabank-smfg-and-sbi-launch-onchain-finance-venture-on-solana">Japanese Megabank SMFG and SBI Launch Onchain... | KuCoin</a></li>
<li><a href="https://msbintel.com/articles/sbi-holdings-and-solana-foundation-partner-on-japan-onchain-fina">SBI Holdings and Solana Foundation partner on Japan... — MSB Intel</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#Solana`, `#tokenization`, `#stablecoin`, `#institutional adoption`

---

<a id="item-11"></a>
## [OpenAI's GPT-5.6 Guide: Stop Over-Prompting](https://decrypt.co/373439/openai-new-gpt-5-6-prompt-guide-chatgpt) ⭐️ 6.0/10

OpenAI has released a new prompting guide for GPT-5.6 that advises users to define clear goals, set stopping conditions, and avoid over-prompting with excessive instructions or XML blocks. This guide signals a shift from complex prompt engineering to simpler, goal-oriented interactions, potentially reducing token usage by up to 66% and making AI more efficient for everyday users. The guide introduces three model variants—Sol, Terra, and Luna—with different reasoning levels, and recommends using Pro Mode and verbosity settings to control output length and detail.

rss · Decrypt · Jul 13, 22:46

**Background**: Prompt engineering has evolved rapidly, with over 50 distinct techniques identified by 2024. Over-prompting, where users provide excessive instructions, can increase cognitive load and produce slower, error-prone responses. OpenAI's new approach emphasizes minimal, clear prompts that let the model leverage its own reasoning.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/373439/openai-new-gpt-5-6-prompt-guide-chatgpt">Stop Over-Prompting: OpenAI’s New GPT-5.6 Guidelines Change ...</a></li>
<li><a href="https://felloai.com/gpt-5-6-prompting-guide/">GPT-5.6 Prompting Guide: 7 Tips for Better Answers</a></li>
<li><a href="https://signalwire.com/blogs/developers/why-over-prompting-kills-ai">Less Is More: Why Over-Prompting Kills Your AI Agent | SignalWire</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#GPT-5.6`, `#prompting`, `#AI guidelines`

---

<a id="item-12"></a>
## [Protesters March on AI Giants Demanding Development Pause](https://decrypt.co/373433/stop-ai-protest-openai-anthropic-google-deepmind) ⭐️ 6.0/10

About 200 protesters marched on the offices of OpenAI, Anthropic, and Google DeepMind in San Francisco on Saturday, demanding a halt to the development of more powerful AI models due to safety, job, and environmental concerns. This protest highlights growing public unease about the rapid pace of AI development, potentially influencing public discourse and regulatory attention on AI safety, job displacement, and energy consumption. The protest was organized by the group 'Stop AI' and involved about 200 participants, a relatively small scale but symbolically targeting three leading AI companies simultaneously.

rss · Decrypt · Jul 13, 22:11

**Background**: AI development has accelerated rapidly, with companies like OpenAI, Anthropic, and Google DeepMind pushing the boundaries of large language models and other AI systems. Concerns have been raised about potential risks such as job automation, environmental impact from energy-hungry data centers, and the safety of increasingly capable AI. Public protests reflect a broader societal debate on how to balance innovation with precaution.

**Tags**: `#AI safety`, `#protest`, `#public concern`, `#AI development`

---

<a id="item-13"></a>
## [China Proposes Crypto Mixer, Privacy Coins as Money Laundering Signs](https://decrypt.co/373374/chinese-prosecutors-float-treating-crypto-mixer-privacy-coin-use-as-sign-of-money-laundering) ⭐️ 6.0/10

Chinese prosecutors have proposed new rules that treat the use of crypto mixers and privacy coins as indicators of money laundering, along with new blockchain evidence rules and a state platform for selling seized cryptocurrencies. This proposal signals a significant tightening of crypto regulation in China, potentially impacting privacy-focused crypto services and users, and setting a precedent for how blockchain evidence is handled in court. The proposal includes presumptions of intent for using mixers or privacy coins, and calls for a centralized state platform to auction seized crypto assets. It was published in the top prosecutors' paper, indicating official consideration.

rss · Decrypt · Jul 13, 10:43

**Background**: Crypto mixers, also known as tumblers, are services that obscure the link between cryptocurrency sender and recipient by mixing transactions. Privacy coins like Monero are designed to enhance transaction anonymity. China has already banned cryptocurrency trading and mining, but this proposal targets the use of privacy-enhancing tools as potential money laundering indicators.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coinbase.com/learn/your-crypto/what-is-a-bitcoin-mixer">What is a Bitcoin mixer? - Coinbase</a></li>
<li><a href="https://koinly.io/crypto-glossary/privacy-coin/">What is a Privacy Coin ? | Koinly</a></li>
<li><a href="https://www.frontiersin.org/journals/blockchain/articles/10.3389/fbloc.2024.1306058/full">Frontiers | Blockchain in the courtroom: exploring its evidentiary significance and procedural implications in U.S. judicial processes</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#money laundering`, `#blockchain`, `#privacy`

---

<a id="item-14"></a>
## [Japan's top security token platform moves $2.7B to Avalanche](https://www.theblock.co/post/408036/japans-largest-security-token-platform-moves-nearly-3-billion-to-avalanche-blockchain?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Progmat, Japan's largest security token platform, has completed the migration of over ¥452 billion (approximately $2.7-3.3 billion) in tokenized assets from a private Corda 5 ledger to a dedicated public Avalanche Layer 1 blockchain. This migration demonstrates growing institutional adoption of public blockchains for regulated security tokens, potentially setting a precedent for other large-scale tokenization projects in Japan and globally. Progmat previously operated on Corda, an enterprise distributed-ledger system, and now uses an application-specific Avalanche L1 deployed through AvaCloud. The platform accounts for 64.6% of Japan's security token market total issuance value.

rss · The Block · Jul 13, 14:29

**Background**: Security tokens are digital representations of traditional financial assets like bonds or real estate, issued on a blockchain. Progmat is a leading infrastructure provider in Japan for issuing and managing such tokens. Avalanche is a public blockchain platform known for its high throughput and customizable subnets, making it suitable for enterprise use cases.

<details><summary>References</summary>
<ul>
<li><a href="https://financefeeds.com/progmat-moves-2-7-billion-token-platform-to-avalanche/">Progmat Moves $2.7 Billion Token Platform to... - FinanceFeeds</a></li>
<li><a href="https://cryip.co/progmat-452-billion-security-token-avalanche-l1/">Progmat Moves ¥452 Billion Security Token Platform to... | Cryip</a></li>
<li><a href="https://blockchain.news/news/progmat-avalanche-migration">Progmat Completes Avalanche Migration, ¥452B in... - Blockchain.News</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#security tokens`, `#Avalanche`, `#Japan`

---

<a id="item-15"></a>
## [Bank of Thailand Audits High-Volume Stablecoin Trades](https://www.theblock.co/post/407998/bank-of-thailand-audits-stablecoin?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

The Bank of Thailand and the Securities and Exchange Commission have begun using data analytics tools to audit high-volume stablecoin trades, with a focus on Tether's USDT, to combat illicit finance. This marks a significant step in stablecoin regulation in Thailand, potentially setting a precedent for other countries in monitoring stablecoin flows for financial crime prevention. The audits focus on abnormal stablecoin trades, particularly USDT, which is the largest stablecoin with over $187 billion in circulation. The central bank and SEC are using data analytics tools to detect suspicious patterns.

rss · The Block · Jul 13, 08:19

**Background**: Stablecoins like USDT are cryptocurrencies pegged to a fiat currency, often used for trading and payments. Their high liquidity and pseudonymity make them attractive for illicit activities such as money laundering. Thailand has been developing a regulatory framework for stablecoins, including a Thai baht stablecoin.

<details><summary>References</summary>
<ul>
<li><a href="https://coinalertnews.com/news/2026/06/27/thai-baht-stablecoin-framework">Thailand Central Bank Nears Thai Baht Stablecoin Regulation ...</a></li>
<li><a href="https://www.coindesk.com/markets/2026/01/12/tether-freezes-usd182-million-in-usdt-stablecoin-across-five-tron-blockchain-wallets">Stablecoin giant Tether freezes $182 million in USDT across five Tron...</a></li>

</ul>
</details>

**Tags**: `#stablecoin`, `#regulation`, `#cryptocurrency`, `#financial crime`

---