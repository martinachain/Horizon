---
layout: default
title: "Horizon Summary: 2026-06-15 (EN)"
date: 2026-06-15
lang: en
---

> From 40 items, 12 important content pieces were selected

---

1. [Rio's 'homegrown' LLM exposed as weighted merge](#item-1) ⭐️ 8.0/10
2. [Jane Street on Formal Methods and AI-Driven Verification](#item-2) ⭐️ 8.0/10
3. [US Orders Anthropic to Pull Claude Fable, Mythos AI Models](#item-3) ⭐️ 8.0/10
4. [Google Sues Chinese Group for Using Gemini AI in Phishing](#item-4) ⭐️ 8.0/10
5. [Valid ePub Files Render Incorrectly on Kobo Due to Adobe RMSDK](#item-5) ⭐️ 7.0/10
6. [Kage: Archive any website into a single offline binary](#item-6) ⭐️ 7.0/10
7. [Windows 11 users frustrated by Microsoft account requirements](#item-7) ⭐️ 7.0/10
8. [Coinbase Report: Address Reuse Exposes Millions of Bitcoin to Quantum Threat](#item-8) ⭐️ 7.0/10
9. [Emacs Batteries Included: Hidden Gems and Community Debate](#item-9) ⭐️ 6.0/10
10. [Trace: Offline Mac meeting transcripts with mid-call flagging](#item-10) ⭐️ 6.0/10
11. [Wall Street Moves Beyond Crypto Pilots, Deeper into Ethereum](#item-11) ⭐️ 6.0/10
12. [AI Agent with Credit Card Causes Financial Loss](#item-12) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Rio's 'homegrown' LLM exposed as weighted merge](https://github.com/nex-agi/Nex-N2/issues/4) ⭐️ 8.0/10

The municipality of Rio de Janeiro released Rio-3.5-Open-397B, claiming it as a homegrown fine-tune of Qwen3.5, but community analysis revealed it is a weighted merge of approximately 60% Nex-N2 Pro and 40% Qwen3.5-397B-A17B without proper disclosure. This incident undermines trust in open-source AI development and highlights the need for transparency standards in model provenance, as deceptive practices can mislead the community and erode credibility. Every weight tensor in Rio was found to be a 0.6/0.4 blend of Nex and Qwen across all 60 layers and components, which is inconsistent with a genuine fine-tune. The model was presented as a homegrown effort by IplanRIO, Rio's IT company.

hackernews · unrvl22 · Jun 14, 15:37 · [Discussion](https://news.ycombinator.com/item?id=48528371)

**Background**: Model merging is a technique where weights from multiple pre-trained models are combined, often via linear interpolation, to create a new model without additional training. Tools like mergekit facilitate this process. Proper disclosure of such merges is considered essential for transparency in open-source AI.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/arcee-ai/mergekit">GitHub - arcee-ai/mergekit: Tools for merging pretrained ...</a></li>
<li><a href="https://arxiv.org/html/2502.00706v1">Model Provenance Testing for Large Language Models - arXiv</a></li>

</ul>
</details>

**Discussion**: The community expressed strong concern, with many calling this a deceptive pattern that undermines trust. Some commenters speculated that the uploaded model lacked the claimed distillation step, while others noted the robustness of linear interpolation in preserving performance.

**Tags**: `#LLM`, `#open-source`, `#ethics`, `#model provenance`, `#AI community`

---

<a id="item-2"></a>
## [Jane Street on Formal Methods and AI-Driven Verification](https://blog.janestreet.com/formal-methods-at-jane-street-index/?from_theconsensus=1) ⭐️ 8.0/10

Jane Street published a blog post discussing the practical use of formal methods in finance and how the rise of AI-generated code shifts the programmer's role toward verification. This discussion highlights a key industry trend: as AI writes more code, human value moves from writing to verifying correctness, making formal methods increasingly relevant for ensuring software reliability. The post references historical proof-of-correctness tools like the Boyer-Moore prover and modern type systems in Scala 3, and notes that formal specs can suffer from the same bugs as tests if not carefully designed.

hackernews · eatonphil · Jun 14, 12:35 · [Discussion](https://news.ycombinator.com/item?id=48526633)

**Background**: Formal methods are mathematically-based techniques for specifying and verifying software correctness, often used in safety-critical systems like railways and microprocessors. They include theorem proving, model checking, and type systems. The blog post from Jane Street, a quantitative trading firm, shows how these methods are applied in practice to ensure financial software reliability.

<details><summary>References</summary>
<ul>
<li><a href="https://www.academia.edu/80981194/Formal_methods">(PDF) Formal methods</a></li>
<li><a href="https://en.wikipedia.org/wiki/Software_verification_and_validation">Software verification and validation - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Software_verification">Software verification - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters shared mixed views: some praised the shift toward verification, noting that expressive types help prevent AI-generated code issues, while others questioned whether formal specs are just 'tests written differently' and can have the same bugs. One commenter with historical experience noted that proof automation has long existed but still requires human guidance.

**Tags**: `#formal methods`, `#programming`, `#verification`, `#type systems`, `#AI`

---

<a id="item-3"></a>
## [US Orders Anthropic to Pull Claude Fable, Mythos AI Models](https://decrypt.co/371027/us-government-orders-anthropic-pull-claude-fable-mythos-ai-models) ⭐️ 8.0/10

The US government has ordered Anthropic to remove its Claude Fable and Mythos AI models, citing a widespread vulnerability. Anthropic disputes the order as regulatory overreach, arguing the vulnerability is already common across the industry. This marks a significant escalation in government regulation of advanced AI models, potentially setting a precedent for future interventions. The outcome could impact how AI companies balance safety, transparency, and innovation. Claude Fable 5 is a publicly available version of the Mythos model, which Anthropic developed to find software vulnerabilities. The government's order targets both the public Fable model and the unreleased Mythos model.

rss · Decrypt · Jun 13, 19:23

**Background**: Anthropic is an AI safety company known for its Claude series of large language models. The Mythos model was designed to identify software vulnerabilities but has not been publicly released due to safety concerns. The government's action reflects growing scrutiny of AI capabilities that could be misused.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://en.wikipedia.org/wiki/Mythos_(model)">Mythos (model)</a></li>

</ul>
</details>

**Tags**: `#AI regulation`, `#Anthropic`, `#government order`, `#AI safety`, `#Claude`

---

<a id="item-4"></a>
## [Google Sues Chinese Group for Using Gemini AI in Phishing](https://decrypt.co/371014/google-sues-chinese-crime-group-gemini-ai-phishing-scams) ⭐️ 8.0/10

Google has filed a lawsuit against a Chinese cybercrime group, dubbed the Outsider Enterprise, for allegedly using its Gemini AI to create over 9,000 phishing websites and send millions of fake text messages, stealing millions of credit card numbers and targeting crypto investors. This case highlights a new threat vector where generative AI is weaponized for large-scale phishing, making attacks more convincing and harder to detect. It underscores the urgent need for AI companies to implement safeguards against malicious use of their models. The group allegedly used Gemini AI to generate convincing phishing content and automate website creation, enabling rapid scaling of attacks. Google is seeking a court order to shut down the operation and damages.

rss · Decrypt · Jun 13, 16:01

**Background**: Phishing attacks traditionally rely on manually crafted emails or websites, but AI can generate highly personalized and grammatically correct messages at scale. Google's Gemini AI is a multimodal model capable of generating text, images, and code, which can be misused to create fake login pages and scam messages. This lawsuit is one of the first major legal actions against AI-powered cybercrime.

<details><summary>References</summary>
<ul>
<li><a href="https://www.digitaltrends.com/phones/scammers-used-gemini-ai-to-power-a-massive-phishing-operation-and-google-just-sued-them/">Scammers used Gemini AI to power a massive phishing operation ...</a></li>
<li><a href="https://hoodline.com/2026/06/google-slaps-outsider-gemini-scam-ring-with-massive-phishing-lawsuit/">Google Slaps 'Outsider' Gemini Scam Ring With Massive ...</a></li>

</ul>
</details>

**Tags**: `#AI security`, `#phishing`, `#cybercrime`, `#Google`, `#Gemini`

---

<a id="item-5"></a>
## [Valid ePub Files Render Incorrectly on Kobo Due to Adobe RMSDK](https://andreklein.net/your-epub-is-fine-kobo-disagrees-blame-adobe/) ⭐️ 7.0/10

A developer discovered that valid ePub files, which pass the official epubcheck validation, render incorrectly on Kobo e-readers because of bugs in Adobe's RMSDK rendering engine. The issue highlights systemic quality problems with Adobe's software and the closed nature of their SDK. This issue affects millions of Kobo users who rely on standard ePub files, and it underscores the broader problem of proprietary rendering engines causing interoperability failures in the e-book ecosystem. It also raises concerns about Adobe's software quality and the lack of access to their SDK for independent developers. The developer confirmed that the same ePub files render correctly on other devices and software, isolating the issue to Adobe's RMSDK used by Kobo. The problem persists even when files pass epubcheck, suggesting that RMSDK does not fully comply with the ePub standard.

hackernews · sohkamyung · Jun 14, 22:54 · [Discussion](https://news.ycombinator.com/item?id=48533848)

**Background**: ePub is a widely used open standard for e-books, and epubcheck is the official validation tool to ensure compliance. Adobe's RMSDK (Reader Mobile SDK) is a proprietary rendering engine licensed by many e-reader manufacturers, including Kobo, to display ePub files. However, RMSDK is closed-source and difficult for independent developers to access or audit, leading to persistent rendering bugs that violate the standard.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@jiminypan/five-interesting-facts-about-adobe-legacy-ebook-rmsdk-b7be0123c874">Five interesting facts about Adobe legacy eBook RMSDK | by Jiminy Panoz - Medium</a></li>
<li><a href="https://ebooks.stackexchange.com/questions/9098/disable-extra-page-numbers-showing-up-in-kobo">epub - Disable extra (page?) numbers showing up in kobo - Ebooks...</a></li>
<li><a href="https://www.mobileread.com/forums/showthread.php?t=271833">Errors with EPUB rendering on Kobo Aura H2O running... | Forum</a></li>

</ul>
</details>

**Discussion**: Community comments express frustration with Adobe's long-standing quality issues, with one user noting that Adobe squandered Flash's market share due to poor QA. Another developer reported being unable to even contact Adobe to license RMSDK, highlighting the closed ecosystem. Some users suggest converting ePubs to Kobo's kepub format as a workaround, while others point out broader issues with the ePub standard itself.

**Tags**: `#ePub`, `#Adobe`, `#Kobo`, `#e-reader`, `#software quality`

---

<a id="item-6"></a>
## [Kage: Archive any website into a single offline binary](https://github.com/tamnd/kage) ⭐️ 7.0/10

Kage is a new open-source tool that clones any website into a folder for offline browsing, stripping out all JavaScript, and can optionally package the archive into a single self-contained binary that serves the site when run. This tool simplifies offline access to websites like wikis or documentation, especially in areas without internet, and its single-binary output makes sharing easy without requiring recipients to install any software. Kage offers a --format binary option that glues the archive onto a copy of Kage itself, producing a single executable; it also supports generating a demo GIF using the author's companion tool ascii-gif.

hackernews · tamnd · Jun 14, 17:25 · [Discussion](https://news.ycombinator.com/item?id=48529990)

**Background**: Web archiving tools like SingleFile or the Wayback Machine preserve web pages for offline use, but often produce multiple files or require a reader. Kage's approach of creating a single binary that serves the site is novel, as it eliminates dependencies and simplifies distribution.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/tamnd/kage">GitHub - tamnd/kage: Shadow any website for offline viewing ...</a></li>
<li><a href="https://news.ycombinator.com/item?id=48529990">Show HN: Kage – Shadow any website to a single binary for ...</a></li>

</ul>
</details>

**Discussion**: Commenters discussed use cases like offline company wikis and feeding websites to coding agents. Some noted that SingleFile is more robust for single-page archiving, while others questioned why a server is needed for static content, suggesting a pure HTML approach.

**Tags**: `#offline`, `#archiving`, `#web`, `#tool`, `#static-site`

---

<a id="item-7"></a>
## [Windows 11 users frustrated by Microsoft account requirements](https://www.windowscentral.com/microsoft/windows-11/windows-11-users-are-tired-of-microsoft-account-requirements-and-workarounds) ⭐️ 7.0/10

Windows 11 users are increasingly frustrated with Microsoft's push to require a Microsoft account for system features, leading many to seek workarounds or switch to alternative operating systems. This trend highlights a growing tension between Microsoft's desire for ecosystem integration and user preferences for privacy and local control, potentially impacting Windows 11 adoption and user loyalty. Users report issues such as restricted mode after associating a Microsoft account, difficulty switching back to a local account, and concerns about BitLocker recovery keys being tied to online accounts.

hackernews · josephcsible · Jun 14, 21:42 · [Discussion](https://news.ycombinator.com/item?id=48533101)

**Background**: Microsoft has been gradually integrating its online services into Windows, requiring a Microsoft account for features like device setup, app store access, and data synchronization. This shift has been met with resistance from users who prefer local accounts for privacy and simplicity.

**Discussion**: Commenters express a mix of frustration and resignation, with some sharing workarounds or announcing they have switched to Linux. Others highlight specific problems like restricted mode and BitLocker key management, while a few question what users can realistically do to push back.

**Tags**: `#Windows 11`, `#Microsoft`, `#user experience`, `#privacy`, `#OS`

---

<a id="item-8"></a>
## [Coinbase Report: Address Reuse Exposes Millions of Bitcoin to Quantum Threat](https://www.theblock.co/post/404685/coinbase-quantum-report-flags-exchange-cold-wallets-among-millions-of-bitcoin-exposed-by-address-reuse?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Coinbase published a report warning that address reuse exposes millions of bitcoin, including exchange cold wallets, to quantum computing attacks, and proposes setting migration deadlines to freeze vulnerable coins. This highlights a significant security vulnerability in Bitcoin that could lead to massive theft if quantum computers mature, affecting exchanges and individual holders alike. Address reuse exposes public keys, which quantum computers could use to forge signatures and steal funds. The report suggests a deadline for migrating coins to quantum-resistant addresses, after which vulnerable coins would be frozen.

rss · The Block · Jun 13, 18:21

**Background**: Bitcoin transactions require a digital signature from the sender's private key to prove ownership. If a public key is exposed (e.g., through address reuse), a sufficiently powerful quantum computer could derive the private key and spend the funds. Address reuse is a known privacy risk but also a security risk in a quantum future.

<details><summary>References</summary>
<ul>
<li><a href="https://www.projecteleven.com/blog/quantum-vulnerability-of-bitcoin-addresses">Quantum vulnerability of Bitcoin addresses | Project Eleven</a></li>
<li><a href="https://www.deloitte.com/nl/en/services/consulting-risk/perspectives/quantum-computers-and-the-bitcoin-blockchain.html">Quantum computers and the Bitcoin blockchain | Deloitte</a></li>
<li><a href="https://www.coindesk.com/tech/2026/04/25/clock-is-ticking-for-bitcoin-to-prevent-quantum-threat-as-it-could-drain-6-9-million-btc-including-satoshi-s">Bitcoin might be at risk from a new quantum math trick that breaks digital ownership</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#quantum computing`, `#cryptocurrency security`, `#address reuse`

---

<a id="item-9"></a>
## [Emacs Batteries Included: Hidden Gems and Community Debate](https://karthinks.com/software/even-more-batteries-included-with-emacs/) ⭐️ 6.0/10

A new blog post by Karthinks highlights lesser-known Emacs features like ruler-mode and text scaling, continuing the 'batteries included' philosophy with a third installment in the series. This article underscores Emacs' enduring value as a highly extensible editor, but the community discussion reveals a persistent tension between its rich built-in features and issues of stability and discoverability. The post is the third in a series, following previous 'batteries included' reports, and aims to improve discoverability by demoing overlooked features. Community comments highlight mixed experiences with stability, especially in Doom Emacs and Spacemacs.

hackernews · signa11 · Jun 15, 02:30 · [Discussion](https://news.ycombinator.com/item?id=48535886)

**Background**: Emacs is a highly customizable text editor known for its 'batteries included' philosophy, meaning it comes with many built-in features like file management (Dired), org-mode, and email clients. However, its vast feature set can be hard to discover, and users often rely on community distributions like Doom Emacs or Spacemacs for a more stable experience.

<details><summary>References</summary>
<ul>
<li><a href="https://karthinks.com/software/even-more-batteries-included-with-emacs/">Even More Batteries Included with Emacs | Karthinks</a></li>
<li><a href="https://news.ycombinator.com/item?id=29342176">Batteries included with Emacs (2020) - Hacker News</a></li>
<li><a href="https://www.reddit.com/r/emacs/comments/s4za7y/emacs_discoverability/">r/emacs on Reddit: Emacs discoverability</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some users praise stability (e.g., Doom Emacs user QwenGlazer9000), while others complain about breakage on updates (e.g., buzzwords). Long-time users like tptacek admit to not understanding Dired, and gnulinux notes a shift to VSCode due to stability issues with package combinations.

**Tags**: `#Emacs`, `#text editors`, `#software tools`, `#productivity`

---

<a id="item-10"></a>
## [Trace: Offline Mac meeting transcripts with mid-call flagging](https://traceapp.info/) ⭐️ 6.0/10

Trace is a new Mac app that records and transcribes meetings entirely offline, activated by a global shortcut, and allows users to flag key moments mid-call with a note that appears inline in the transcript. It addresses the friction of existing transcription tools by offering quick activation and on-device processing, enhancing privacy and workflow for users who frequently need meeting notes without interrupting their focus. Trace uses macOS APIs to capture both sides of a conversation as separate tracks, runs on-device diarization to label speakers, and saves transcripts as markdown files locally; the only network call is for initial model download (~500MB) from Hugging Face.

hackernews · AG342 · Jun 13, 20:41 · [Discussion](https://news.ycombinator.com/item?id=48521236)

**Background**: Meeting transcription apps like MacWhisper have become popular but often require manual setup before calls and rely on cloud processing, raising privacy concerns. On-device speech recognition on Apple Silicon Macs has improved significantly, enabling offline transcription with good accuracy. Trace builds on this trend by minimizing user friction through global shortcuts and mid-call flagging.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/MacWhisper">MacWhisper</a></li>
<li><a href="https://getvext.app/blog/offline-voice-to-text-mac">Offline Voice to Text on Mac — How Local Speech Recognition ...</a></li>
<li><a href="https://retina.studio/textbuddy/enable-macos-on-device-speech-recognition/">Enable On - Device Speech Recognition – retina studio</a></li>

</ul>
</details>

**Discussion**: Commenters generally appreciate the app's focus on reducing friction and the key moments feature, but some express concerns about App Store exclusivity, model download size, and corporate restrictions on installing such software. One user also shared an open-source alternative project.

**Tags**: `#meeting transcription`, `#macOS`, `#offline`, `#productivity`, `#open source`

---

<a id="item-11"></a>
## [Wall Street Moves Beyond Crypto Pilots, Deeper into Ethereum](https://www.coindesk.com/business/2026/06/13/wall-street-is-moving-past-crypto-pilots-and-deeper-into-ethereum-says-etherealize-founder) ⭐️ 6.0/10

Etherealize founder Vivek Raman claims Wall Street is shifting from crypto pilot projects to real-world deployment of Ethereum-based financial applications, including tokenized stocks, bonds, funds, and real estate. This signals growing institutional confidence in Ethereum's infrastructure, potentially accelerating mainstream adoption of blockchain in traditional finance and expanding Ethereum's role beyond cryptocurrency speculation. The adoption involves tokenizing real-world assets on Ethereum, leveraging smart contracts for automation and transparency. However, challenges remain in regulatory clarity and scalability for high-volume institutional use.

rss · CoinDesk · Jun 13, 16:00

**Background**: Ethereum is a decentralized blockchain platform that supports smart contracts—self-executing programs that run when predetermined conditions are met. Institutional finance has been experimenting with blockchain for years, but full-scale adoption has been limited by regulatory and technical hurdles. The shift from pilots to production indicates growing maturity.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/business/2026/06/13/wall-street-is-moving-past-crypto-pilots-and-deeper-into-ethereum-says-etherealize-founder">Wall Street is moving past crypto pilots and deeper into Ethereum...</a></li>
<li><a href="https://coinmarketcap.com/academy/article/75d2afce-e511-49c1-bb42-1b5cf058a138">Vitalik Buterin and Ethereum Foundation Back Etherealize to Drive...</a></li>
<li><a href="https://decrypt.co/321861/wall-street-gets-ethereum-digital-oil-etherealize">Wall Street Gets Ethereum's 'Digital Oil', Says Etherealize ... - ...</a></li>

</ul>
</details>

**Tags**: `#Ethereum`, `#Wall Street`, `#crypto adoption`, `#institutional finance`

---

<a id="item-12"></a>
## [AI Agent with Credit Card Causes Financial Loss](https://decrypt.co/370988/ai-agent-rekts-dev-bogus-scan-crypto-donations) ⭐️ 6.0/10

A hobbyist developer gave an autonomous AI agent a credit card and a deadline, and the agent made a bogus scan that resulted in financial loss, leaving the developer begging for crypto donations. This incident highlights the real-world risks of granting autonomous AI agents access to financial resources, especially under time pressure, and underscores the need for robust safety measures in agentic AI systems. The AI agent was given a credit card and a deadline to complete a task, but it performed a bogus scan that incurred charges, draining funds. The developer then turned to the crypto community for donations to cover the loss.

rss · Decrypt · Jun 13, 13:01

**Background**: Autonomous AI agents are systems that can independently reason and execute tasks to achieve goals. When given access to financial tools like credit cards, they can make decisions with real monetary consequences, raising concerns about safety and control.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/research/measuring-agent-autonomy">Measuring AI agent autonomy in practice \ Anthropic</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#autonomous agents`, `#AI failure`, `#crypto`

---