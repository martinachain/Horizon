---
layout: default
title: "Horizon Summary: 2026-07-04 (EN)"
date: 2026-07-04
lang: en
---

> From 75 items, 22 important content pieces were selected

---

1. [GLM5.2 on AMD MI355X: 2626 tok/s at 2x lower cost than Blackwell](#item-1) ⭐️ 8.0/10
2. [Guide to Running SOTA LLMs Locally Sparks Cost Debate](#item-2) ⭐️ 8.0/10
3. [EU Parliament Spyware Investigator Hacked with Pegasus](#item-3) ⭐️ 8.0/10
4. [OpenAI Offers US Government $42 Billion Stake](#item-4) ⭐️ 8.0/10
5. [Mistral Releases Leanstral 1.5 for Lean 4 Proofs](#item-5) ⭐️ 7.0/10
6. [SearXNG: A Free, Self-Hosted Metasearch Engine](#item-6) ⭐️ 7.0/10
7. [Costco's Warehouse Model Avoids Costly Last-Mile Delivery](#item-7) ⭐️ 7.0/10
8. [Factories Are Just Rooms: A Mindset Shift](#item-8) ⭐️ 7.0/10
9. [Securitize Tokenizes $295M Stock on Solana and Avalanche](#item-9) ⭐️ 7.0/10
10. [SBI Crypto Shuts Down Mining Pool with 2% of Bitcoin Hashrate](#item-10) ⭐️ 7.0/10
11. [Ondo Finance Launches SEC-Aligned Tokenized Stocks](#item-11) ⭐️ 7.0/10
12. [Claude Fable 5 Performance Drop Blamed on Paranoid Router](#item-12) ⭐️ 7.0/10
13. [New Jailbreak Trick Bypasses AI Safety Guardrails](#item-13) ⭐️ 7.0/10
14. [Standard Chartered First Global Bank to Offer Direct USDC Access](#item-14) ⭐️ 7.0/10
15. [Steam Controller Auto-Charge via CV and Haptics](#item-15) ⭐️ 6.0/10
16. [Sanctioned Russian stablecoin's billion-dollar claims disputed](#item-16) ⭐️ 6.0/10
17. [eToro Invests in Onchain Derivatives Platform Extended](#item-17) ⭐️ 6.0/10
18. [US Treasury Sanctions Over 100 ISIS-K Crypto Addresses](#item-18) ⭐️ 6.0/10
19. [Europe reconsiders MiCA crypto regulation three years on](#item-19) ⭐️ 6.0/10
20. [Q-Day: The Quantum Threat to Bitcoin Explained](#item-20) ⭐️ 6.0/10
21. [Spotify Demands Kalshi, Polymarket Remove Branding Over Stream Fraud](#item-21) ⭐️ 6.0/10
22. [Institutional Bitcoin Adoption Post-ETF Launch](#item-22) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [GLM5.2 on AMD MI355X: 2626 tok/s at 2x lower cost than Blackwell](https://www.wafer.ai/blog/glm52-amd) ⭐️ 8.0/10

GLM5.2 achieves 2626 tokens per second per node on AMD MI355X GPUs, claiming over 2x lower cost compared to NVIDIA Blackwell GPUs for LLM inference. This demonstrates AMD's growing competitiveness in LLM inference, potentially offering a cost-effective alternative to NVIDIA's dominant Blackwell lineup, especially for non-US data centers facing NVIDIA supply constraints. The performance is achieved using FP4 quantization, which community members note may cause significant accuracy degradation compared to FP8 or higher precision. The MI355X features 288GB HBM3E memory and 8TB/s bandwidth.

hackernews · latchkey · Jul 3, 21:49 · [Discussion](https://news.ycombinator.com/item?id=48780417)

**Background**: LLM inference speed is measured in tokens per second (tok/s), and cost efficiency is critical for deployment. AMD's MI355X is built on CDNA 4 architecture, while NVIDIA's Blackwell GPUs (e.g., RTX 5090) support native FP4 (NVFP4) inference. Quantization reduces model precision to accelerate inference but can degrade output quality.

<details><summary>References</summary>
<ul>
<li><a href="https://www.amd.com/en/products/accelerators/instinct/mi350/mi355x.html">AMD Instinct™ MI355X GPUs</a></li>
<li><a href="https://arxiv.org/html/2601.09527v1">Private LLM Inference on Consumer Blackwell GPUs:</a></li>
<li><a href="https://docs.vllm.ai/projects/llm-compressor/en/0.8.1/examples/quantization_w4a4_fp4/">fp4 Quantization - LLM Compressor Docs - vLLM Documentation</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism about FP4 quantization's accuracy, with users noting that models may be 'functionally lobotomized' and no longer frontier quality. Some request performance-per-watt metrics and suggest that quantization type should be mandatory in headlines.

**Tags**: `#AMD`, `#LLM inference`, `#GPU comparison`, `#quantization`, `#cost efficiency`

---

<a id="item-2"></a>
## [Guide to Running SOTA LLMs Locally Sparks Cost Debate](https://github.com/jamesob/local-llm) ⭐️ 8.0/10

Jamesob published a guide on GitHub detailing how to run state-of-the-art large language models locally using high-end hardware, including a $40K+ build with four $12K GPUs. This guide highlights the extreme cost and hardware requirements for local SOTA LLM inference, challenging the practicality of local deployment for most users and sparking debate on whether cloud services offer better value. The recommended build costs around $50K-$55K, not $40K as stated, and relies on quantization and pruning techniques to fit models like GLM-5.2 onto consumer hardware, which may degrade quality.

hackernews · livestyle · Jul 3, 15:03 · [Discussion](https://news.ycombinator.com/item?id=48775921)

**Background**: State-of-the-art large language models (LLMs) like GPT-4 and Claude Opus typically require massive cloud infrastructure. Running them locally demands high-end GPUs with large VRAM, often costing tens of thousands of dollars. Quantization reduces model precision to fit into available memory but can impact output quality.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.stackademic.com/local-llms-for-self-hosters-what-theyre-good-for-what-they-re-bad-for-and-the-minimum-hardware-57b21315fc29">Local LLMs for self-hosters: what’s worth running at home | Stackademic</a></li>
<li><a href="https://medium.com/data-science-collective/what-is-the-best-hardware-for-running-local-llms-in-2026-mac-vs-5090-vs-cloud-ff023b660442">What Is The Best Hardware for Running Local LLMs in 2026... | Medium</a></li>

</ul>
</details>

**Discussion**: Community comments emphasize that the $40K build is actually $50K+, and that cost could cover 16+ years of cloud subscriptions. Users also note that quantized models may underperform and that cheaper alternatives like 2x RTX 3090s or unified memory systems exist.

**Tags**: `#LLM`, `#local inference`, `#hardware`, `#cost analysis`, `#open-source`

---

<a id="item-3"></a>
## [EU Parliament Spyware Investigator Hacked with Pegasus](https://citizenlab.ca/research/member-of-committee-investigating-spyware-hacked-with-pegasus/) ⭐️ 8.0/10

Citizen Lab confirmed that a European Parliament member investigating spyware was infected with Pegasus spyware on multiple occasions in 2022 and 2023, indicating a state actor with cross-border surveillance capabilities. This breach directly targets EU democratic processes and security, as the infected member was part of a committee investigating spyware abuse. It underscores the threat of commercial spyware to democratic institutions and the need for stronger safeguards. The first infection occurred on or around October 21, 2022, and subsequent infections on March 6 and 7, 2023. The attack overlaps with a known Pegasus campaign targeting Russian and Belarusian-speaking exiled journalists in Europe.

hackernews · ledoge · Jul 3, 20:38 · [Discussion](https://news.ycombinator.com/item?id=48779683)

**Background**: Pegasus is a powerful spyware developed by Israeli company NSO Group, capable of remotely compromising mobile devices and extracting data, messages, and even activating microphones and cameras. Citizen Lab is a leading research group that investigates digital espionage and has exposed multiple Pegasus abuses worldwide.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Pegasus_(spyware)">Pegasus (spyware)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Citizen_Lab">Citizen Lab</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the attack may be linked to Greece's ongoing Pegasus scandal, where the prime minister's office allegedly orchestrated surveillance. Others highlighted that some EU countries have abused Pegasus so severely that Israeli firms cut ties, raising questions about internal EU state-sponsored espionage.

**Tags**: `#cybersecurity`, `#spyware`, `#Pegasus`, `#European Parliament`, `#surveillance`

---

<a id="item-4"></a>
## [OpenAI Offers US Government $42 Billion Stake](https://decrypt.co/372715/openai-offers-us-government-42-billion-slice) ⭐️ 8.0/10

OpenAI CEO Sam Altman has proposed selling a 5% equity stake to the U.S. government, reportedly valued at $42 billion, and wants other major AI companies to follow suit. This move could set a precedent for public-private partnerships in AI governance, potentially reshaping how AI companies are regulated and funded, and giving the government a direct stake in the industry's future. The proposal reportedly values OpenAI at over $800 billion, and the 5% stake would be worth around $42 billion. Altman envisions a model where all major AI companies offer similar equity to the government.

rss · Decrypt · Jul 2, 21:39

**Background**: OpenAI is a leading AI research and deployment company, known for ChatGPT and GPT-4. The U.S. government has been exploring ways to regulate AI while maintaining competitiveness. Equity stakes could align incentives between public interests and private innovation.

**Tags**: `#OpenAI`, `#AI governance`, `#public-private partnership`, `#regulation`, `#equity`

---

<a id="item-5"></a>
## [Mistral Releases Leanstral 1.5 for Lean 4 Proofs](https://mistral.ai/news/leanstral-1-5/) ⭐️ 7.0/10

Mistral AI has released Leanstral 1.5, a fine-tuned language model specialized for Lean 4 formal verification, claiming improved proof generation and bug detection capabilities. This release advances the use of LLMs in formal verification, a field critical for ensuring software correctness, and could make Lean 4 more accessible to developers. The model is fine-tuned from Mistral's base model and is open-weight, with a context length of 256k tokens and a Mixture of Experts architecture (119B parameters, 6.5B active per token).

hackernews · programLyrique · Jul 3, 22:33 · [Discussion](https://news.ycombinator.com/item?id=48780801)

**Background**: Lean 4 is an interactive theorem prover and programming language used for formal verification, where mathematical theorems and software properties are proved with machine-checked rigor. Leanstral is a family of LLMs designed to assist with writing Lean 4 proofs, automating parts of the verification process.

<details><summary>References</summary>
<ul>
<li><a href="https://mistral.ai/news/leanstral/">Leanstral : Open-Source foundation for trustworthy... | Mistral AI</a></li>
<li><a href="https://huggingface.co/mistralai/Leanstral-2603">mistralai/ Leanstral -2603 · Hugging Face</a></li>
<li><a href="https://lean-lang.org/">Lean Programming Language</a></li>

</ul>
</details>

**Discussion**: Some commenters questioned the bug-finding example, noting that the overflow edge case is a classic boundary condition that testing typically catches. Others pointed out that the model comparisons used older models, making the results less impressive.

**Tags**: `#LLM`, `#formal verification`, `#Lean 4`, `#AI`, `#Mistral`

---

<a id="item-6"></a>
## [SearXNG: A Free, Self-Hosted Metasearch Engine](https://github.com/searxng/searxng) ⭐️ 7.0/10

SearXNG is a free, open-source metasearch engine that aggregates results from multiple search services without tracking or profiling users. It is actively maintained and supports self-hosting, with a strong community following. SearXNG provides a privacy-respecting alternative to mainstream search engines, which is increasingly important as concerns over data collection grow. It also enables integration with local AI models and agents, making it a key tool for privacy-conscious developers and users. SearXNG supports multiple categories including Web, Images, Videos, News, and more, and can output results in JSON format for programmatic use. It is a fork of Searx, offering faster development and fewer bugs, with features like anonymous metrics and improved engine reliability.

hackernews · theanonymousone · Jul 3, 20:15 · [Discussion](https://news.ycombinator.com/item?id=48779454)

**Background**: A metasearch engine sends user queries to multiple search engines (e.g., Google, Bing, DuckDuckGo) and aggregates the results, providing a single unified interface. Unlike traditional search engines, metasearch engines do not maintain their own index, which can reduce privacy risks if configured properly. SearXNG is self-hosted, meaning users run it on their own servers, giving them full control over their data.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SearXNG">SearXNG - Wikipedia</a></li>
<li><a href="https://github.com/searxng/searxng">GitHub - searxng/searxng: SearXNG is a free internet metasearch engine which aggregates results from various search services and databases. Users are neither tracked nor profiled. · GitHub</a></li>
<li><a href="https://en.wikipedia.org/wiki/Searx">Searx - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community discussion highlights SearXNG's role in providing search to local AI models, with users sharing setups for tool calling on GPUs like the 4070 Ti Super. The original creator of Searx noted limitations of the metasearch concept and pointed to his new project, Hister. Some users mentioned downsides like slower speed and occasional CAPTCHA blocks, but overall sentiment is positive.

**Tags**: `#search engine`, `#privacy`, `#open source`, `#self-hosted`, `#AI integration`

---

<a id="item-7"></a>
## [Costco's Warehouse Model Avoids Costly Last-Mile Delivery](https://phenomenalworld.org/analysis/the-anti-amazon/) ⭐️ 7.0/10

An article argues that Costco's warehouse club model inherently avoids the expensive last-mile delivery problem by having customers pick up bulk goods themselves, contrasting it with Amazon's home delivery system that bears high logistical costs. This analysis highlights a fundamental trade-off in retail logistics: centralized self-pickup versus decentralized home delivery, with implications for consumer behavior, urban planning, and environmental impact. It challenges the assumption that home delivery is always more convenient or efficient. Costco's model uses freight trucks to deliver pallets to warehouses, where customers drive to pick up goods in bulk, eliminating per-stop delivery costs. In contrast, Amazon's last-mile delivery involves individual packages to each home, which is the most expensive and complex part of logistics.

hackernews · bookofjoe · Jul 3, 15:14 · [Discussion](https://news.ycombinator.com/item?id=48776044)

**Background**: The last-mile delivery problem refers to the final step of the delivery process from a distribution center to the end customer, which is often the most costly and inefficient due to factors like traffic, failed deliveries, and low package density. Costco's warehouse model shifts the burden of the last mile to the customer, reducing the retailer's logistics expenses. This trade-off is especially relevant as e-commerce grows and cities grapple with delivery congestion.

<details><summary>References</summary>
<ul>
<li><a href="https://onfleet.com/blog/last-mile-problem/">The Last Mile Delivery Problem : Here's How to Solve it</a></li>
<li><a href="https://fourweekmba.com/costco-business-model/">Costco Business Model: How They Made $269.9B in 2025</a></li>
<li><a href="https://supplychain360.io/logistics/costco-warehouse-model-checkout-shift/">Costco refits its warehouse operating model - supplychain360.io</a></li>

</ul>
</details>

**Discussion**: Commenters praised the article's insight, with one noting the engineering wisdom of avoiding problems rather than solving them. Another highlighted Costco's role in car-centric suburban culture, while a UK commenter added that Costco's membership is technically restricted to certain professions, and the store is also known for non-food items like electronics and tires.

**Tags**: `#business`, `#logistics`, `#e-commerce`, `#retail`, `#engineering`

---

<a id="item-8"></a>
## [Factories Are Just Rooms: A Mindset Shift](https://interconnected.org/home/2026/07/03/factories) ⭐️ 7.0/10

An essay argues that factories can be as simple as a room with the right mindset, challenging assumptions about manufacturing complexity. This perspective democratizes production by lowering the perceived barrier to entry, encouraging more people to consider small-scale manufacturing. The essay is tagged with manufacturing, systems thinking, and maker culture, and has high community engagement with 210 points and 81 comments.

hackernews · arbesman · Jul 3, 15:13 · [Discussion](https://news.ycombinator.com/item?id=48776035)

**Background**: Traditional manufacturing often involves complex supply chains, specialized machinery, and large facilities. The essay challenges this by suggesting that a simple room with the right tools and mindset can function as a factory, emphasizing creativity and adaptability over capital-intensive setups.

**Discussion**: Commenters share personal experiences: one ran a small factory in the UK and found it enjoyable, while another notes that a fast-food kitchen is essentially a factory. However, a commenter from a machine-building company warns that a 'just a room' attitude may not sustain consistent business.

**Tags**: `#manufacturing`, `#systems thinking`, `#maker culture`, `#essay`

---

<a id="item-9"></a>
## [Securitize Tokenizes $295M Stock on Solana and Avalanche](https://www.coindesk.com/business/2026/07/02/securitize-tokenizes-usd295-million-of-its-own-stock-on-solana-and-avalanche-amid-nyse-debut) ⭐️ 7.0/10

Securitize, a BlackRock-backed tokenization firm, tokenized $295 million of its own NYSE-listed stock on Solana and Avalanche on its first day as a public company. This marks a significant step in bridging traditional finance with blockchain, as a major regulated entity issues tokenized equities on public blockchains, potentially paving the way for wider adoption of real-world asset tokenization. The tokenized shares are issuer-sponsored and represent the same common stock trading on the NYSE, available to eligible U.S. investors through regulated infrastructure. Securitize President Brett Redfearn indicated the firm is in discussions to tokenize other IPOs within the next year.

rss · CoinDesk · Jul 2, 19:00

**Background**: Securitize is a leading tokenization platform that helps asset managers and companies issue digital securities on blockchain networks. Real-world asset tokenization involves creating blockchain-based tokens that represent ownership of traditional assets like stocks, bonds, or real estate, aiming to improve liquidity, accessibility, and efficiency.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/02/securitize-tokenizes-usd295-million-of-its-own-stock-on-solana-and-avalanche-amid-nyse-debut">Securitize (SECZ) takes $295M of its own tokenized stock to Solana, Avalanche amid NYSE debut</a></li>
<li><a href="https://decrypt.co/372689/securitize-trading-nyse-tokenized-shares-solana-avalanche">Securitize Begins Trading on NYSE as Tokenized Shares Land on Solana, Avalanche - Decrypt</a></li>
<li><a href="https://blockonomi.com/securitize-secz-makes-nyse-debut-while-tokenizing-shares-on-solana-and-avalanche/">Securitize (SECZ) Makes NYSE Debut While Tokenizing Shares on Solana and Avalanche - Blockonomi</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#blockchain`, `#Solana`, `#Avalanche`, `#finance`

---

<a id="item-10"></a>
## [SBI Crypto Shuts Down Mining Pool with 2% of Bitcoin Hashrate](https://www.coindesk.com/business/2026/07/02/sbi-crypto-to-shut-down-mining-pool-that-holds-roughly-2-of-bitcoin-s-hashrate) ⭐️ 7.0/10

SBI Crypto, a subsidiary of Japanese financial giant SBI Holdings, announced it will shut down its Bitcoin mining pool, which accounts for roughly 2% of the network's total hashrate. The shutdown reduces mining centralization risks but also removes a significant portion of hashrate, potentially impacting network security and transaction processing speed. It signals ongoing consolidation in the mining industry. The mining pool contributed about 2% of Bitcoin's total hashrate, which as of 2023 was around 300 exahashes per second. SBI Crypto did not disclose the exact reason for the shutdown but cited a strategic review.

rss · CoinDesk · Jul 2, 14:44

**Background**: Bitcoin mining uses proof-of-work, where miners compete to solve cryptographic puzzles. Hashrate measures the total computational power of the network. Mining pools combine resources from many miners to increase the chance of earning rewards, which are then shared proportionally.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hashrate">Hashrate</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mining_pool">Mining pool</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#mining`, `#cryptocurrency`, `#hashrate`

---

<a id="item-11"></a>
## [Ondo Finance Launches SEC-Aligned Tokenized Stocks](https://www.coindesk.com/business/2026/07/01/ondo-finance-debuts-sec-aligned-tokenized-stock-model-with-blackrock-etf-micron-shares) ⭐️ 7.0/10

Ondo Finance has launched tokenized versions of BlackRock's iShares Core S&P 500 ETF (IVV) and Micron Technology (MU) shares on Ethereum, using a custodial model aligned with SEC guidance. This marks the first live implementation of the SEC's custodial tokenization model, bridging traditional securities with blockchain settlement and potentially paving the way for broader institutional adoption of tokenized real-world assets. The tokenized securities are issued by a third-party custodian that holds the underlying assets, with settlement occurring on Ethereum. Holders gain indirect exposure to the securities but also face counterparty risks such as custodian bankruptcy.

rss · CoinDesk · Jul 2, 14:16

**Background**: Tokenization involves creating a blockchain-based token that represents ownership of a real-world asset, such as a stock or ETF. The SEC's custodial model allows a third party to hold the underlying security and issue tokens representing entitlements, operating within existing securities laws. Ondo Finance's launch is the first to put this model into practice with major assets like BlackRock's IVV ETF.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/01/ondo-finance-debuts-sec-aligned-tokenized-stock-model-with-blackrock-etf-micron-shares">Ondo debuts SEC-aligned tokenized stock model with BlackRock ETF, Micron shares</a></li>
<li><a href="https://genfinity.io/2026/07/02/ondo-broadridge-first-custodial-tokenized-securities-us/">Ondo Debuts First U.S. Custodial Tokenized Securities on Ethereum with BlackRock IVV and Micron - Genfinity</a></li>
<li><a href="https://www.sec.gov/newsroom/speeches-statements/corp-fin-statement-tokenized-securities-012826-statement-tokenized-securities">SEC.gov | Statement on Tokenized Securities</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#DeFi`, `#SEC`, `#BlackRock`, `#real-world assets`

---

<a id="item-12"></a>
## [Claude Fable 5 Performance Drop Blamed on Paranoid Router](https://decrypt.co/372750/claude-fable-5-not-nerfed-router-paranoid) ⭐️ 7.0/10

An article argues that apparent performance drops in Claude Fable 5 are caused by a paranoid routing layer that sends some sensitive requests to a weaker model, not by a model nerf. This explanation resolves conflicting benchmark results and has practical implications for users and developers relying on consistent AI model performance. The routing layer automatically sends a small slice of sensitive requests to Opus 4.8, leaving everything else at full Fable 5 capability without changing cost.

rss · Decrypt · Jul 3, 21:06

**Background**: AI models are often evaluated using benchmarks, but discrepancies can arise due to factors like routing layers that dynamically assign requests to different models. The Claude Fable 5 model includes a safety safeguard that routes sensitive queries to a more conservative model, which can cause inconsistent benchmark results.

<details><summary>References</summary>
<ul>
<li><a href="https://decrypt.co/372750/claude-fable-5-not-nerfed-router-paranoid">Claude Fable 5 Isn't Nerfed. The Router Is Just Paranoid - Decrypt</a></li>
<li><a href="https://apidog.com/blog/claude-fable-5-safety-safeguards/">How Claude Fable 5's Safety Safeguards Work (Routing ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#benchmarks`, `#Claude`, `#routing`, `#model evaluation`

---

<a id="item-13"></a>
## [New Jailbreak Trick Bypasses AI Safety Guardrails](https://decrypt.co/372688/ai-researchers-chatbots-share-cocaine-recipes-wild-trick) ⭐️ 7.0/10

Researchers discovered a jailbreak technique that tricks AI models into treating attacker-written text as their own reasoning, bypassing safety guardrails and exposing a fundamental security flaw. This vulnerability undermines the core safety mechanisms of large language models, potentially allowing malicious actors to generate harmful content like drug recipes, and highlights the need for more robust AI alignment research. The technique, known as 'sockpuppeting' or similar prompt injection methods, exploits the model's tendency toward self-consistency by injecting fake acceptance into the assistant-role message. It has been shown to work on multiple models, including GPT, Gemini, and DeepSeek.

rss · Decrypt · Jul 2, 19:36

**Background**: Large language models (LLMs) are trained with safety guardrails to refuse harmful requests. Jailbreaking refers to crafting prompts that bypass these guardrails, often by manipulating context, instructions, or hidden tokens. This new method is particularly concerning because it tricks the model into believing the harmful content is its own reasoning, making detection harder.

<details><summary>References</summary>
<ul>
<li><a href="https://slowlow999.github.io/The_Jailbreak_Index/">THE JAILBREAK INDEX</a></li>
<li><a href="https://www.cyberark.com/resources/threat-research-blog/jailbreaking-every-llm-with-one-simple-click">Jailbreaking Every LLM With One Simple Click - CyberArk</a></li>
<li><a href="https://www.trendaisecurity.com/en/resources-insights/research/sockpuppeting-how-a-single-line-can-bypass-llm-safety-guardrails">Sockpuppeting: How a Single Line Can Bypass LLM Safety Guardrails | TrendAI</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#jailbreak`, `#security`, `#LLM`, `#vulnerability`

---

<a id="item-14"></a>
## [Standard Chartered First Global Bank to Offer Direct USDC Access](https://decrypt.co/372674/standard-chartered-first-global-bank-direct-usdc-access) ⭐️ 7.0/10

Standard Chartered has become the first Global Systemically Important Bank authorized to allow institutional clients to mint and redeem Circle's USDC stablecoin directly. This marks a significant step in bridging traditional banking with the crypto ecosystem, potentially accelerating institutional adoption of stablecoins for payments and settlements. USDC is a fully reserved stablecoin pegged 1:1 to the US dollar, backed by cash and short-term US Treasury bonds. Direct minting and redemption typically require KYC/KYB and AML compliance.

rss · Decrypt · Jul 2, 13:58

**Background**: Global Systemically Important Banks (G-SIBs) are large banks whose failure could trigger a financial crisis, subject to stricter regulations. Stablecoins like USDC are designed to maintain a stable value, facilitating crypto-to-fiat conversions. Standard Chartered's move could set a precedent for other G-SIBs to offer similar services.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/USDC_(cryptocurrency)">USDC (cryptocurrency) - Wikipedia</a></li>
<li><a href="https://www.circle.com/usdc">USDC | Powering global finance. Issued by Circle.</a></li>
<li><a href="https://en.wikipedia.org/wiki/Global_Systemically_Important_Bank">Global Systemically Important Bank</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#stablecoin`, `#banking`, `#institutional finance`, `#USDC`

---

<a id="item-15"></a>
## [Steam Controller Auto-Charge via CV and Haptics](https://github.com/FossPrime/Steam-Controller-Auto-Charge) ⭐️ 6.0/10

A GitHub project uses computer vision to guide a Steam Controller to a magnetic charging puck by vibrating the controller across a table using its haptic feedback motors. This project demonstrates a novel, low-cost approach to automated charging for devices with haptic feedback, potentially inspiring similar hacks for other peripherals. The controller crawls along a tabletop using only its built-in haptic motors, with a camera providing visual feedback for alignment to the magnetic charging puck.

hackernews · zdw · Jul 3, 22:39 · [Discussion](https://news.ycombinator.com/item?id=48780865)

**Background**: The Steam Controller is a gamepad with dual trackpads and haptic feedback motors that can produce vibrations. Computer vision (CV) involves using a camera and algorithms to interpret visual data. Magnetic charging pucks use magnets to align and wirelessly charge devices.

<details><summary>References</summary>
<ul>
<li><a href="https://www.scan.co.uk/products/nda-23-08-razer-mouse-dock-pro-with-wireless-charging-puck-magnetic-charging-hyperpolling-receiver-c">Razer Mouse Dock Pro + Razer Wireless Charging Puck ... | SCAN UK</a></li>
<li><a href="https://www.elecboy.com.hk/en/products/courant-mag-1-magnetic-charging-puck">Courant MAG:1 Magnetic Charging Puck | Wireless Charger | ElecBoy</a></li>

</ul>
</details>

**Discussion**: Comments are light and humorous, with one user noting the neighbors might find the nightly vibrations odd. Another user compared it to the Cycloramic app for iPhone, which used vibration to rotate a phone on a table.

**Tags**: `#computer vision`, `#hardware hack`, `#Steam Controller`, `#haptic feedback`

---

<a id="item-16"></a>
## [Sanctioned Russian stablecoin's billion-dollar claims disputed](https://www.coindesk.com/business/2026/07/03/this-sanctioned-russian-stablecoin-claims-it-processes-billions-but-blockchain-analysts-disagree) ⭐️ 6.0/10

A CoinDesk investigation reveals that the sanctioned Russian ruble-backed stablecoin A7A5 claims to have processed over $110 billion in on-chain transactions, but blockchain analysts argue that the actual volume is significantly lower due to inflated data from wash trading and self-transfers. This matters because it highlights the challenges of enforcing sanctions in the crypto space, where opaque on-chain activity can be used to evade restrictions, and underscores the need for more accurate blockchain analytics to distinguish genuine economic activity from manipulation. A7A5, which is under EU and UK sanctions, captured 43% of the non-dollar stablecoin market by claimed volume, but analysts point out that a large portion of transactions involve circular trading between a small number of wallets, inflating the figures.

rss · CoinDesk · Jul 3, 19:18

**Background**: Stablecoins are cryptocurrencies designed to maintain a stable value, often pegged to a fiat currency like the US dollar or the Russian ruble. On-chain analysis involves examining public blockchain data to verify transaction volumes and identify patterns, but it can be complicated by techniques like wash trading, where the same asset is repeatedly traded to create false volume.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/03/this-sanctioned-russian-stablecoin-claims-it-processes-billions-but-blockchain-analysts-disagree">This sanctioned Russian stablecoin claims it processes ...</a></li>
<li><a href="https://www.dlnews.com/articles/regulation/how-ruble-stablecoin-a7a5-drove-a-surge-in-sanction-dodging/">How a Russian stablecoin drove a 400% surge in sanction ...</a></li>
<li><a href="https://www.edgen.tech/news/post/russian-stablecoin-a7a5-hits-110b-as-sanctions-evasion-shifts-to-crypto">Russian stablecoin A7A5 hits $110B as sanctions evasion ...</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#stablecoin`, `#sanctions`, `#blockchain analysis`

---

<a id="item-17"></a>
## [eToro Invests in Onchain Derivatives Platform Extended](https://www.coindesk.com/business/2026/07/02/etoro-invests-in-onchain-derivatives-platform-extended-as-brokers-race-into-defi) ⭐️ 6.0/10

eToro has invested in Extended, an onchain derivatives platform built on Arbitrum, and plans to integrate perpetual futures into the Zengo wallet while expanding DeFi products to its core platform. This signals a growing trend of traditional brokers entering DeFi, potentially bridging the gap between centralized finance and decentralized derivatives trading for mainstream users. Extended uses a unified margin system allowing users to trade crypto and TradFi assets with up to 50x leverage from self-custodied wallets, and eToro's move follows rivals like Robinhood expanding onchain offerings.

rss · CoinDesk · Jul 2, 17:00

**Background**: Onchain derivatives are financial contracts (like perpetual futures) that trade on blockchain-based platforms, offering transparency and self-custody. Traditional brokers like eToro are increasingly investing in DeFi to offer these products to their users, as decentralized exchanges gain popularity.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/07/02/etoro-invests-in-onchain-derivatives-platform-extended-as-brokers-race-into-defi">EToro invests in onchain derivatives platform Extended as ...</a></li>
<li><a href="https://extended.exchange/">Extended Exchange | One Margin for All Markets</a></li>
<li><a href="https://defishills.com/product/extended-exchange/">Extended Exchange – Decentralized Perpetuals | DeFiShills</a></li>

</ul>
</details>

**Tags**: `#DeFi`, `#derivatives`, `#crypto`, `#investment`

---

<a id="item-18"></a>
## [US Treasury Sanctions Over 100 ISIS-K Crypto Addresses](https://www.coindesk.com/policy/2026/07/02/us-treasury-sanctions-over-100-isis-k-crypto-addresses-in-latest-enforcement-action) ⭐️ 6.0/10

The US Treasury sanctioned over 130 Tron wallet addresses linked to ISIS-K, which collectively moved over $1.4 million, and Tether froze the associated funds. This action demonstrates the US government's increasing ability to track and disrupt terrorist financing through cryptocurrencies, particularly on the Tron network, which has been criticized for enabling illicit activity. All sanctioned addresses are on the Tron blockchain, and the stablecoin USDT issued by Tether was frozen. The action targets ISIS-K, a Central Asian affiliate of ISIS responsible for numerous attacks.

rss · CoinDesk · Jul 2, 14:49

**Background**: ISIS-K (Islamic State – Khorasan Province) is a militant group active in Afghanistan, Pakistan, and Central Asia. Tron is a proof-of-stake blockchain that has been widely used for USDT transfers due to low fees, but also criticized for facilitating money laundering and terrorist financing.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/ISIS-K">ISIS-K</a></li>
<li><a href="https://en.wikipedia.org/wiki/Tron_(blockchain)">Tron (blockchain)</a></li>
<li><a href="https://grokipedia.com/page/Tether_cryptocurrency">Tether (cryptocurrency)</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#terrorism financing`, `#blockchain`

---

<a id="item-19"></a>
## [Europe reconsiders MiCA crypto regulation three years on](https://www.coindesk.com/policy/2026/07/02/three-years-after-mica-became-law-europe-s-crypto-framework-is-undergoing-a-rethink) ⭐️ 6.0/10

Three years after the Markets in Crypto-Assets (MiCA) regulation became law in the EU, policymakers are now reconsidering the framework, potentially leading to amendments or new rules. This rethink could reshape the regulatory landscape for crypto in Europe, affecting how exchanges, stablecoin issuers, and other service providers operate in one of the world's largest economic blocs. MiCA's stablecoin rules took effect in June 2024, and rules for crypto asset service providers followed in December 2024; the review may address implementation challenges or market developments since then.

rss · CoinDesk · Jul 2, 11:55

**Background**: MiCA is the EU's comprehensive regulatory framework for crypto assets not covered by existing financial laws. It was passed in 2022 after 18 months of debate, aiming to provide legal clarity and consumer protection while fostering innovation. The regulation covers stablecoins, crypto exchanges, and wallet providers, with phased implementation starting in 2024.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Markets_in_Crypto-Assets">Markets in Crypto -Assets - Wikipedia</a></li>
<li><a href="https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica">Markets in Crypto -Assets Regulation ( MiCA )</a></li>
<li><a href="https://web3.okx.com/learn/what-is-mica">What is MiCA ? A regulatory leap forward for crypto | OKX Wallet</a></li>

</ul>
</details>

**Tags**: `#crypto regulation`, `#MiCA`, `#Europe`, `#policy`

---

<a id="item-20"></a>
## [Q-Day: The Quantum Threat to Bitcoin Explained](https://decrypt.co/resources/what-q-day-quantum-threat-bitcoin-explained) ⭐️ 6.0/10

Experts warn that future quantum computers could forge Bitcoin's digital signatures, enabling unauthorized transactions and potentially breaking Bitcoin's security model. If realized, this threat could undermine the trust and value of Bitcoin, the largest cryptocurrency, and force a fundamental upgrade to its cryptographic infrastructure. The threat stems from Shor's algorithm, which can efficiently solve the discrete logarithm problem underlying Bitcoin's ECDSA signatures, but practical quantum computers capable of this are likely years away.

rss · Decrypt · Jul 3, 15:40

**Background**: Bitcoin uses the Elliptic Curve Digital Signature Algorithm (ECDSA) to secure transactions. Quantum computers, leveraging principles of quantum mechanics, could theoretically break this cryptography by solving the underlying mathematical problems exponentially faster than classical computers.

<details><summary>References</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2pyOElieEVCRWlSM1BNemd6dWdpZ0FQAQ?hl=en-IN&gl=IN&ceid=IN:en">Google News - Quantum computing threat to Bitcoin - Overview</a></li>
<li><a href="https://cryptorank.io/news/feed/1fbdc-the-quantum-computing-threat-bitcoin-cant-ignore">The quantum computing threat Bitcoin can’t ignore</a></li>

</ul>
</details>

**Tags**: `#quantum computing`, `#Bitcoin`, `#cryptography`, `#security`

---

<a id="item-21"></a>
## [Spotify Demands Kalshi, Polymarket Remove Branding Over Stream Fraud](https://www.theblock.co/post/407134/spotify-asks-kalshi-polymarket-to-remove-branding-after-manipulated-streams-used-to-settle-music-bets-bloomberg?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Spotify has asked prediction markets Kalshi and Polymarket to remove its branding after 500,000 fake streams were used to manipulate a $3 million music betting market, as reported by Bloomberg. This incident highlights the vulnerability of prediction markets to manipulation via real-world data, and raises concerns about the integrity of music streaming charts and the platforms that rely on them. The fake streams were for Malcolm Todd's track 'Earrings,' which briefly reached No. 1 on Spotify's charts. Spotify removed the fraudulent streams and is adding additional checks to charts before publication.

rss · The Block · Jul 3, 11:57

**Background**: Kalshi and Polymarket are prediction markets where users bet on real-world outcomes, such as music chart positions. Spotify's charts are used as data sources for these markets. The manipulation involved artificially inflating streams to influence chart positions and settle bets.

<details><summary>References</summary>
<ul>
<li><a href="https://finance.biggo.com/news/9be1a98e-fa96-40b5-b699-ef328a19e4d6">Spotify Detects 500,000 Manipulated Streams in Scheme ...</a></li>
<li><a href="https://www.hollywoodreporter.com/music/music-industry-news/spotify-pulls-streams-over-kalshi-betting-fraud-1236636212/">Spotify Pulls Streams From Song After Alleged Kalshi Betting ...</a></li>
<li><a href="https://www.ibtimes.sg/spotify-removes-500000-fake-streams-after-chart-manipulation-roils-3-million-prediction-market-89027">Spotify Removes 500,000 Fake Streams After Chart Manipulation ...</a></li>

</ul>
</details>

**Tags**: `#prediction markets`, `#fraud`, `#music streaming`, `#blockchain`

---

<a id="item-22"></a>
## [Institutional Bitcoin Adoption Post-ETF Launch](https://www.theblock.co/learn/407111/institutional-bitcoin-adoption-explained-how-blackrock-fidelity-and-others-embraced-btc?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

Institutional adoption of Bitcoin accelerated sharply after spot Bitcoin ETFs launched in January 2024, with asset managers, corporations, banks, and pension funds now actively investing in or building services around Bitcoin. This marks a major shift from retail-dominated crypto markets to regulated institutional participation, potentially increasing market stability and mainstream acceptance of Bitcoin as an asset class. Spot Bitcoin ETFs provide direct exposure to Bitcoin's price and trade on traditional exchanges, making them accessible to institutional investors who previously faced regulatory or custody hurdles.

rss · The Block · Jul 3, 06:26

**Background**: Institutional adoption refers to organizations like asset managers, corporations, hedge funds, banks, pension funds, and insurers engaging with crypto. Before spot ETFs, institutions faced barriers such as custody challenges and regulatory uncertainty. The launch of spot Bitcoin ETFs in January 2024 removed many of these obstacles, enabling regulated entities to gain Bitcoin exposure through familiar investment vehicles.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/posts/midchains_the-crypto-industry-needs-to-stop-calling-activity-7460643391865901056-wvag">Institutional Adoption of Crypto Beyond Buzzwords | LinkedIn</a></li>
<li><a href="https://news.bitcoin.com/institutional-crypto-adoption-happening-now-ripple-executive-says-real-world-use-cases-taking-hold/">Institutional Crypto Adoption 'Happening Now': Ripple Executive...</a></li>
<li><a href="https://www.ainvest.com/news/crypto-institutional-adoption-107b-signal-mainstream-validation-2509/">Crypto Institutional Adoption : A $107B Signal for Mainstream...</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#Institutional Adoption`, `#ETFs`, `#Crypto`

---