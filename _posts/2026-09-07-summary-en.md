---
layout: default
title: "Horizon Summary: 2026-09-07 (EN)"
date: 2026-09-07
lang: en
---

> From 29 items, 10 important content pieces were selected

---

1. [AI Generates 13-Million-Line Proof of Fermat's Last Theorem](#item-1) ⭐️ 9.0/10
2. [Anubis Ships WebAssembly Proof-of-Work After Year-Long Effort](#item-2) ⭐️ 8.0/10
3. [GrapheneOS Plans Overhaul of Default Apps and Secure Clipboard](#item-3) ⭐️ 8.0/10
4. [OpenAI's Insider View on Automated AI Research and RSI](#item-4) ⭐️ 8.0/10
5. [OpenAI's GPT-6 Astra Impresses Early Testers Across Diverse Domains](#item-5) ⭐️ 8.0/10
6. [Liquid Network Pauses After $320M Bitcoin Withdrawal](#item-6) ⭐️ 8.0/10
7. [Python Interpreter Squeezed into 1024 Bytes of C](#item-7) ⭐️ 7.0/10
8. [Nitter and XCancel resume after legal advice](#item-8) ⭐️ 7.0/10
9. [Google Patches Actively Exploited Chrome Zero-Day in V8 Engine](#item-9) ⭐️ 7.0/10
10. [Better and Coinbase Enable Bitcoin-Backed Mortgages with Collateral Reuse](#item-10) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [AI Generates 13-Million-Line Proof of Fermat's Last Theorem](https://decrypt.co/377491/ai-solved-350-year-old-math-problem) ⭐️ 9.0/10

Anthropic's Claude reportedly solved Fermat's Last Theorem by generating a 13-million-line machine-checkable proof over 11 days, marking a potential milestone in AI-driven mathematics. This claim suggests AI can tackle problems that have stumped humans for centuries, potentially transforming how mathematical proofs are discovered and verified. If confirmed, it could accelerate research in mathematics and related fields, though the extraordinary nature demands careful verification. The proof is machine-checkable, meaning it can be verified by a computer without human trust, and reportedly took 11 days to generate. The scale—13 million lines—far exceeds human-generated proofs, such as Andrew Wiles's 1994 proof, which is around 100 pages.

rss · Decrypt · Sep 5, 13:01

**Background**: Fermat's Last Theorem, stated by Pierre de Fermat in 1637, asserts that no three positive integers a, b, c satisfy a^n + b^n = c^n for any integer n greater than 2. It remained unproven until Andrew Wiles's proof in 1994, which relied on advanced mathematics. Machine-checkable proofs are formal proofs verified by proof assistants or automated theorem provers, ensuring correctness through computer verification.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Proof_assistant">Proof assistant - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Automated_theorem_proving">Automated theorem proving - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Fermat's_Last_Theorem">Fermat's Last Theorem - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#AI`, `#mathematics`, `#proof`, `#Anthropic`, `#Fermat's Last Theorem`

---

<a id="item-2"></a>
## [Anubis Ships WebAssembly Proof-of-Work After Year-Long Effort](https://anubis.techaro.lol/blog/2026/anubis-wasm/) ⭐️ 8.0/10

After a year of work, Anubis has shipped an opt-in WebAssembly-based proof-of-work check in its next version, with a JavaScript fallback for older browsers. The integration involved rewriting part of Anubis in Rust and overcoming significant engineering challenges. This update enhances Anubis's bot protection while maintaining backward compatibility, which is crucial for users on older devices like smart TVs. It also highlights the growing adoption of WebAssembly for server-side and security-critical applications, and the importance of community feedback in open-source development. The WebAssembly checks are opt-in and can be enabled by admins in thresholds or bot rules. The project targeted Chrome 66 for backward compatibility, and the JavaScript fallback ensures functionality on browsers without WebAssembly support.

hackernews · xena · Sep 6, 20:32 · [Discussion](https://news.ycombinator.com/item?id=49590611)

**Background**: Anubis is an open-source anti-bot system that uses proof-of-work challenges to protect websites from automated traffic. WebAssembly (Wasm) is a binary instruction format that allows high-performance execution in browsers, and it is designed to be backward compatible. Integrating Wasm into Anubis allows for more efficient and secure proof-of-work calculations compared to JavaScript-only implementations.

<details><summary>References</summary>
<ul>
<li><a href="https://anubis.techaro.lol/blog/2026/anubis-wasm/">It took a year to ship WebAssembly in Anubis | Anubis</a></li>
<li><a href="https://runtimewire.com/article/anubis-webassembly-proof-of-work-xe-iaso">Anubis ships opt-in WebAssembly checks after a year of work</a></li>
<li><a href="https://webassembly.org/">WebAssembly</a></li>

</ul>
</details>

**Discussion**: Community comments praised the maintainer's dedication to backward compatibility and the wry tone regarding OSS maintainer treatment. Some users expressed concerns about WebAssembly being disabled in their browsers, while others suggested using period-correct toolchains for compatibility testing. Overall, the sentiment was positive, with appreciation for the engineering effort and thoughtful design choices.

**Tags**: `#WebAssembly`, `#Open Source`, `#Backward Compatibility`, `#Engineering`, `#Community`

---

<a id="item-3"></a>
## [GrapheneOS Plans Overhaul of Default Apps and Secure Clipboard](https://grapheneos.social/@GrapheneOS/117225539756835649) ⭐️ 8.0/10

GrapheneOS announced plans to overhaul or replace default AOSP apps, including a new secure clipboard and future RCS support with MLS encryption, aiming to reduce reliance on Google services. The announcement was made on Mastodon and generated significant community discussion. This move is significant for privacy-focused users who want to avoid Google dependencies, as it could provide a fully open-source alternative to Google Messages and other default apps. It also aligns with broader industry trends toward end-to-end encryption in messaging, as seen in the GSMA's recent RCS specifications. The secure clipboard feature is part of the planned overhaul, though details are not yet fully specified. GrapheneOS also plans to replace the outdated AOSP Gallery and possibly the AOSP Keyboard, and they have recently hired new staff to accelerate progress.

hackernews · Cider9986 · Sep 6, 20:24 · [Discussion](https://news.ycombinator.com/item?id=49590512)

**Background**: GrapheneOS is an open-source, privacy-focused mobile operating system based on Android, available for Google Pixel devices. RCS (Rich Communication Services) is a messaging protocol that carriers are adopting, and the GSMA has recently specified end-to-end encryption for RCS using the Messaging Layer Security (MLS) protocol. GrapheneOS currently relies on Google Messages for RCS with E2EE, but aims to provide its own implementation to avoid Google services.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GrapheneOS">GrapheneOS - Wikipedia</a></li>
<li><a href="https://www.gsma.com/newsroom/article/rcs-encryption-a-leap-towards-secure-and-interoperable-messaging/">RCS Encryption: A Leap Towards Secure and Interoperable ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Messaging_Layer_Security">Messaging Layer Security - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community members expressed enthusiasm for a non-Google RCS option, with one user noting that Google Messages has worked well but a non-Google alternative would be huge. Some users questioned the 'secure clipboard' aspect, as the announcement primarily focused on the SMS/RCS app, while others suggested specific replacements like the FUTO keyboard and a gallery app called ReFrame.

**Tags**: `#GrapheneOS`, `#privacy`, `#Android`, `#RCS`, `#secure clipboard`

---

<a id="item-4"></a>
## [OpenAI's Insider View on Automated AI Research and RSI](https://openai.com/index/research-acceleration-view-inside-openai) ⭐️ 8.0/10

OpenAI published an article detailing its efforts to build an automated AI researcher capable of working under human supervision to accelerate progress on deep learning and alignment, aiming for iterative improvements. The article also highlights how OpenAI's own researchers are currently using AI tools internally. This matters because it offers a rare insider perspective on OpenAI's strategy toward recursive self-improvement (RSI) and automated research, which could significantly accelerate AI development and impact the broader AI ecosystem. It also raises important questions about safety, alignment, and the potential for AI to help solve alignment challenges. The article mentions that OpenAI aims to build an automated AI researcher that can handle tasks that would take a skilled researcher a few days, and they use the acronym RSI without defining it, which some commenters found out of touch. OpenAI reportedly spends up to $8,000 per day per researcher on AI tools, according to community discussion.

hackernews · iamsyr · Sep 6, 15:08 · [Discussion](https://news.ycombinator.com/item?id=49587217)

**Background**: Recursive self-improvement (RSI) is a hypothesized process where an AGI system rewrites its own code to enhance its capabilities, potentially leading to an intelligence explosion. While no current AI has achieved RSI, the concept raises significant safety and ethical concerns. OpenAI's article discusses building automated research tools as a step toward this goal, with potential benefits for alignment research.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Recursive_self-improvement">Recursive self-improvement</a></li>
<li><a href="https://arxiv.org/abs/2607.07663">[2607.07663] Recursive Self-Improvement in AI: From Bounded Self ...</a></li>
<li><a href="https://www.itechpost.com/articles/237237/20260906/openai-reaches-its-automated-research-intern-goal-aims-have-automated-ai-researcher-march-2028.htm">OpenAI Reaches Its Automated Research Intern Goal, Aims to Have an Automated AI Researcher by March 2028</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism about OpenAI's justification for pursuing RSI, with some noting the circular reasoning of needing AI to protect against AI. Others find the internal usage details more interesting, while some criticize the use of undefined acronyms like RSI and question the high costs and tracking of AI-assisted work.

**Tags**: `#OpenAI`, `#AI research`, `#recursive self-improvement`, `#AI safety`, `#automation`

---

<a id="item-5"></a>
## [OpenAI's GPT-6 Astra Impresses Early Testers Across Diverse Domains](https://decrypt.co/377514/openai-gpt-6-astra-review-shockingly-good) ⭐️ 8.0/10

OpenAI released GPT-6 Astra as a limited preview on September 3, 2026, and early testers spent the launch weekend evaluating its performance in 3D environments, playable games, Bach chorales, and research papers. The model is rolling out to a limited set of organizations first, with broader availability to ChatGPT Plus, Pro, Business, and Enterprise users, as well as via API and cloud platforms, in the coming days. GPT-6 Astra represents a significant leap in AI capabilities, being OpenAI's first model to reach the Critical level of cybersecurity capability under its Preparedness Framework. Its exceptional performance across diverse domains suggests a potential paradigm shift in multimodal AI, affecting researchers, developers, and businesses that rely on advanced AI for complex tasks. GPT-6 Astra is the most capable model OpenAI has broadly deployed, and its usage is included within existing subscription allowances, with options to purchase additional credits. The release followed a delay after a Hugging Face incident in July 2026, during which OpenAI added more safeguards.

rss · Decrypt · Sep 6, 17:01

**Background**: Multimodal AI models process and combine information from multiple data types, such as text, images, audio, and video, to achieve a more comprehensive understanding than single-modality models. GPT-6 Astra builds on this concept, demonstrating capabilities across 3D environments, games, music, and research, indicating advanced integration of various modalities. The model's release follows OpenAI's Preparedness Framework, which assesses and mitigates risks associated with advanced AI capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/GPT-6_Astra">GPT-6 Astra - Wikipedia</a></li>
<li><a href="https://openai.com/index/gpt-6-astra/">GPT-6 Astra: A new generation of intelligence | OpenAI</a></li>
<li><a href="https://deploymentsafety.openai.com/gpt-6-astra">GPT-6 Astra System Card - OpenAI Deployment Safety Hub</a></li>

</ul>
</details>

**Tags**: `#OpenAI`, `#GPT-6`, `#AI model`, `#multimodal`, `#AI research`

---

<a id="item-6"></a>
## [Liquid Network Pauses After $320M Bitcoin Withdrawal](https://www.theblock.co/news/defi/2026-09-06-liquid-network-pauses-after-purported-white-hat-hackers-withdraw-320-million-in-bitcoin-413626) ⭐️ 8.0/10

The Liquid Network, a Bitcoin sidechain, has been paused after purported white-hat hackers withdrew $320 million in bitcoin, prompting exchanges to suspend LBTC deposits and withdrawals. Blockstream is working to contact those responsible. This incident highlights security vulnerabilities in Bitcoin layer-2 solutions and could undermine trust in sidechains like Liquid. The suspension of LBTC trading affects users and exchanges, potentially impacting the broader DeFi ecosystem that relies on such assets. The withdrawal involved $320 million in bitcoin, and the network has been paused while Blockstream investigates. Exchanges have suspended LBTC deposits and withdrawals, and the incident is described as involving 'white-hat' hackers, suggesting it may be an ethical hack or a security measure.

rss · The Block · Sep 6, 21:14

**Background**: The Liquid Network is an open-source Bitcoin sidechain and layer-2 solution designed for faster, more affordable, and confidential Bitcoin transactions, as well as digital asset issuance. LBTC is a token on Liquid, but note that there is also a separate Lombard BTC (LBTC) token, which is a liquid staking token backed 1:1 by BTC; the news likely refers to the Liquid Network's LBTC. White-hat hackers are ethical security researchers who hack with permission to identify vulnerabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.liquid.net/docs/technical-overview">Technical Overview - Documentation - The Liquid Network</a></li>
<li><a href="https://blockstream.com/liquid/">The Liquid Network | Bitcoin layer-2 solution for digital asset issuance.</a></li>
<li><a href="https://river.com/learn/terms/l/liquid-network/">Liquid Network - River Financial</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#Liquid Network`, `#security`, `#hack`, `#cryptocurrency`

---

<a id="item-7"></a>
## [Python Interpreter Squeezed into 1024 Bytes of C](https://austinhenley.com/blog/python1024.html) ⭐️ 7.0/10

Austin Henley published an article demonstrating a minimal Python interpreter written in just 1024 bytes of C code. The interpreter supports a tiny subset of Python, including for loops, while loops, and if statements, through extreme code golfing. This feat showcases the limits of language implementation and code golfing, inspiring programmers to think creatively about interpreter design. It also highlights the trade-offs between minimalism and functionality, relevant to embedded systems and educational projects. The interpreter is written in C and compiles to a binary much larger than 1024 bytes. It assumes source code correctness, with keywords like 'f' mapping to 'for [x] in range[y]', 'w' to 'while', and 'i' to 'if', and it reparses the source on each loop iteration.

hackernews · azhenley · Sep 6, 23:14 · [Discussion](https://news.ycombinator.com/item?id=49591876)

**Background**: Code golfing is a recreational programming activity where participants aim to solve a problem using the fewest characters or bytes possible. Writing a Python interpreter in 1024 bytes is an extreme example, pushing the limits of what can be expressed in a tiny amount of code. This project is similar to other minimal implementations like C4, a tiny C compiler, but takes even more shortcuts by assuming the input is valid.

<details><summary>References</summary>
<ul>
<li><a href="https://deepwiki.com/ebi-cp/docs/3.2-code-golfing-techniques">Code Golfing Techniques | ebi-cp/docs | DeepWiki</a></li>
<li><a href="https://www.geeksforgeeks.org/python/code-golfing-in-python/">Code Golfing in Python - GeeksforGeeks</a></li>
<li><a href="https://aosabook.org/en/500L/a-python-interpreter-written-in-python.html">500 Lines or LessA Python Interpreter Written in Python</a></li>

</ul>
</details>

**Discussion**: Community comments express admiration for the cleverness while noting its impracticality. jrdres compares it unfavorably to C4, pointing out that it assumes source correctness. teddyh suggests Snek as a production-ready alternative for embedded use. Others appreciate the human-made aspect and link to related projects by the author.

**Tags**: `#Python`, `#interpreter`, `#code golf`, `#minimalism`, `#programming languages`

---

<a id="item-8"></a>
## [Nitter and XCancel resume after legal advice](https://github.com/zedeus/nitter/commit/1428b4c2b4246f92a7e5b2673438e5fb39fcc4a3) ⭐️ 7.0/10

Nitter and XCancel have resumed operations after receiving legal advice, following a cease-and-desist letter from X Corp that had temporarily shut them down. The projects continue to provide alternative frontends for accessing X content. This development is significant for privacy advocates and users who rely on alternative frontends to access X content without logging in or being tracked. It highlights the ongoing tension between platform control and open access to public information. The resumption was announced via a commit on the Nitter GitHub repository, with links to XCancel and Nitter instances. The legal advice allowed the projects to continue, though specific details of the advice were not disclosed.

hackernews · zImPatrick · Sep 6, 17:49 · [Discussion](https://news.ycombinator.com/item?id=49588988)

**Background**: Nitter is a free and open-source alternative frontend for X (formerly Twitter) that allows users to browse tweets without logging in, ads, or tracking scripts. XCancel is a similar service that relies on Nitter to display X posts. Both projects received a cease-and-desist letter from X Corp in August 2026, leading to a temporary shutdown.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Nitter">Nitter - Wikipedia</a></li>
<li><a href="https://www.forbes.com/sites/siladityaray/2026/08/26/cease-and-desist-from-x-shuts-down-nitter-and-xcancel-sites-that-scraped-and-mirrored-tweets/">Nitter And XCancel Shutdown After 'Cease And Desist' From ... - Forbes</a></li>
<li><a href="https://85ideas.com/blog/what-is-xcancel-complete-guide-explanation/">What Is XCancel? Complete Guide & Explanation - 85ideas.com</a></li>

</ul>
</details>

**Discussion**: Community comments express relief and support for the resumption, with users noting the importance of alternative frontends for accessing crucial information posted exclusively on X. Some commenters also discuss broader issues like platform monopolies and the difficulty of moving users to better platforms.

**Tags**: `#privacy`, `#open-source`, `#social-media`, `#legal`, `#decentralization`

---

<a id="item-9"></a>
## [Google Patches Actively Exploited Chrome Zero-Day in V8 Engine](https://decrypt.co/377501/google-chrome-zero-day-exploited) ⭐️ 7.0/10

Google has released Chrome version 142.0.7444.162/.163 to address a high-severity zero-day vulnerability in the V8 JavaScript engine, which was actively exploited in the wild. The update is rolling out across Windows, Mac, and Linux platforms. This patch is critical because the zero-day was already being exploited by hackers, putting Chrome users at risk of attacks. It underscores the importance of timely browser updates for security, especially for software engineers and security professionals who rely on Chrome. The vulnerability is in the V8 JavaScript engine, and Google has not disclosed who is exploiting it or their targets. The update addresses a total of 26 Chrome vulnerabilities, including two critical use-after-free flaws, according to recent reports.

rss · Decrypt · Sep 5, 15:01

**Background**: A zero-day vulnerability is a security flaw unknown to the software vendor, leaving no patch available at the time of discovery. In this case, the flaw was actively exploited before Google could release a fix, making it a zero-day attack. The V8 engine is Chrome's JavaScript engine, which is a common target for attackers due to its complexity and widespread use.

<details><summary>References</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2p0eW8zMkVSR19RWkVEY0VmNkx5Z0FQAQ?hl=en-IN&gl=IN&ceid=IN:en">Google Chrome update addresses V 8 engine vulnerability - Overview</a></li>
<li><a href="https://www.linkedin.com/posts/cybersecurity-news_cybersecuritynews-vulnerability-activity-7386633653323427840-F6nv">Google fixes Chrome V 8 JavaScript engine vulnerability | LinkedIn</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-day_exploit">Zero-day exploit</a></li>

</ul>
</details>

**Tags**: `#security`, `#Chrome`, `#zero-day`, `#V8`, `#patch`

---

<a id="item-10"></a>
## [Better and Coinbase Enable Bitcoin-Backed Mortgages with Collateral Reuse](https://www.coindesk.com/business/2026/09/06/better-and-coinbase-s-bitcoin-backed-mortgages-can-reuse-borrowers-collateral) ⭐️ 6.0/10

Better and Coinbase have launched bitcoin-backed mortgages that allow borrowers to reuse their collateral, potentially increasing capital efficiency. This product lets borrowers pledge Bitcoin to fund a home down payment without selling it, and the collateral can be reused in lending chains. This innovation could make homeownership more accessible for crypto holders while enhancing liquidity in the crypto ecosystem. It also highlights growing integration between traditional finance and digital assets, potentially influencing how collateral is managed in future lending products. The mortgage structure involves two loans: a conforming Fannie Mae mortgage on the home and a separate loan secured by the pledged crypto and a second lien on the home. Collateral reuse, while improving capital efficiency, may increase exposure to drops in collateral prices, as noted in Federal Reserve research.

rss · CoinDesk · Sep 6, 14:00

**Background**: A bitcoin-backed mortgage allows borrowers to use their cryptocurrency as collateral instead of selling it, avoiding taxable events and forced liquidation. Collateral reuse is a practice where lenders repledge received collateral to back other transactions, which can increase liquidity but also systemic risk. Companies like Milo and Rocket Mortgage already offer crypto-backed mortgages, but the collaboration between Better and Coinbase introduces a novel element of collateral reuse.

<details><summary>References</summary>
<ul>
<li><a href="https://better.com/crypto-backed-mortgages">Crypto-Backed Mortgages | Better Mortgage</a></li>
<li><a href="https://www.federalreserve.gov/econres/feds/collateral-reuse-and-financial-stability.htm">The Fed - Collateral Reuse and Financial Stability</a></li>
<li><a href="https://www.rocketmortgage.com/learn/crypto-mortgage">Crypto and Bitcoin mortgages | Rocket Mortgage</a></li>

</ul>
</details>

**Tags**: `#bitcoin`, `#mortgages`, `#fintech`, `#collateral`, `#crypto`

---