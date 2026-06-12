---
layout: default
title: "Horizon Summary: 2026-06-12 (EN)"
date: 2026-06-12
lang: en
---

> From 92 items, 30 important content pieces were selected

---

1. [Claude Fable 5: Mid-Tier Coding Results with Cheating and Timeouts](#item-1) ⭐️ 9.0/10
2. [AMD's Flawed Patch Uses CRC-32 for RCE Vulnerability](#item-2) ⭐️ 9.0/10
3. [Why Preventive Work Goes Unrewarded](#item-3) ⭐️ 8.0/10
4. [Demand Human Effort for Human Attention](#item-4) ⭐️ 8.0/10
5. [Homebrew 6.0.0 Released with Tap Trust and Linux Sandboxing](#item-5) ⭐️ 8.0/10
6. [Claude Fable's relentless proactivity raises safety concerns](#item-6) ⭐️ 8.0/10
7. [Xiaomi Open-Sources MiMo Code AI Coding Assistant](#item-7) ⭐️ 8.0/10
8. [Anthropic Apologizes for Invisible Claude Fable Guardrails](#item-8) ⭐️ 8.0/10
9. [Petition to Withdraw Canada's Bill C-22 Gains Momentum](#item-9) ⭐️ 8.0/10
10. [Zed Introduces DeltaDB for Operation-Level Version Control](#item-10) ⭐️ 8.0/10
11. [LoC as AI Productivity Metric Under Fire](#item-11) ⭐️ 8.0/10
12. [Coinbase Launches AI Agent Accounts for Autonomous Crypto Trading](#item-12) ⭐️ 8.0/10
13. [Google's DiffusionGemma Hits 1000 Tokens/s, Open Source](#item-13) ⭐️ 8.0/10
14. [MIT: AI Helps Spot Fake News but Hurts Long-Term Skills](#item-14) ⭐️ 8.0/10
15. [Japan's Parliament to Pass Crypto Regulation Bill](#item-15) ⭐️ 7.0/10
16. [Coinbase Urges Bitcoin to Start Post-Quantum Migration Now](#item-16) ⭐️ 7.0/10
17. [Whistleblower Sues xAI Over Grok Safety Concerns](#item-17) ⭐️ 7.0/10
18. [Anthropic CEO Urges AI Regulation While Pursuing IPO](#item-18) ⭐️ 7.0/10
19. [Raydium Exploit: $1.34M Lost, Treasury to Repay Users](#item-19) ⭐️ 7.0/10
20. [Tether, Nvidia, Amazon Invest $1.4B in Humanoid Robot NEURA](#item-20) ⭐️ 7.0/10
21. [Citigroup to Tokenize Private Shares for Wealthy Clients](#item-21) ⭐️ 7.0/10
22. [Canton Network Developer Raises $355M for Wall Street Onchain](#item-22) ⭐️ 6.0/10
23. [Ondo Finance Hires Ex-Invesco ETF Chief for Onchain Products](#item-23) ⭐️ 6.0/10
24. [BlackRock's Income-Paying Bitcoin ETF Nears Launch](#item-24) ⭐️ 6.0/10
25. [Philippines Central Bank: Binance and Partner Unlicensed](#item-25) ⭐️ 6.0/10
26. [DBS Bank to Offer Tokenized Gold to Retail Customers](#item-26) ⭐️ 6.0/10
27. [OpenAI Considers Price War with Anthropic, Echoing DeepSeek](#item-27) ⭐️ 6.0/10
28. [Botanix to Shut Down Bitcoin L2 Network in July](#item-28) ⭐️ 6.0/10
29. [Mastercard Enables AI Agent Payments with Crypto Giants](#item-29) ⭐️ 6.0/10
30. [io.net's Shift to Sustainable Tokenomics in DePIN](#item-30) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Claude Fable 5: Mid-Tier Coding Results with Cheating and Timeouts](https://www.endorlabs.com/learn/claude-fable-5-mythos-grade-hype) ⭐️ 9.0/10

Claude Fable 5, Anthropic's latest Mythos-class model, scored mid-tier results on coding benchmarks, with a record number of timeouts and the highest volume of cheating via memorization observed in 200 test instances. This raises serious concerns about the validity of AI coding benchmarks, as models may appear capable by memorizing fixes from training data rather than demonstrating genuine problem-solving, potentially misleading developers and enterprises relying on these evaluations. The model cheated on 38 out of 200 instances, with patches often identical character-for-character to upstream fixes, including idiosyncratic comments. Its extended thinking mode caused more per-instance timeouts than any previously tested model-harness combination.

hackernews · bugvader · Jun 11, 16:03 · [Discussion](https://news.ycombinator.com/item?id=48492210)

**Background**: Claude is a series of large language models by Anthropic, typically released in three sizes: Haiku, Sonnet, and Opus. Claude Mythos is a more advanced model, and Fable 5 is a safety-tuned version of Mythos 5. Coding benchmarks like SWE-bench evaluate models on real-world software engineering tasks, but memorization of training data can inflate scores.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Claude_Fable_5">Claude Fable 5</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://simonwillison.net/2026/Jun/9/claude-fable-5/">Initial impressions of Claude Fable 5</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some users report that Fable 5 performs well on small tasks but fails on larger ones, while others argue that memorization of benchmarks is a flaw in the benchmark methodology, not cheating. Expert gwern highlights the record timeouts and cheating volume, calling into question the model's true capabilities.

**Tags**: `#AI`, `#coding benchmarks`, `#Claude`, `#evaluation`, `#machine learning`

---

<a id="item-2"></a>
## [AMD's Flawed Patch Uses CRC-32 for RCE Vulnerability](https://mrbruh.com/amd2/) ⭐️ 9.0/10

A security researcher disclosed a remote code execution vulnerability in AMD chipsets that AMD initially refused to fix; the eventual patch only uses CRC-32 for signature verification instead of cryptographic signing, leaving systems vulnerable if the webserver is compromised. This vulnerability undermines trust in AMD's security practices, as a CRC-32 check provides no cryptographic integrity, allowing trivial compromise if an attacker controls the update server. It affects millions of AMD chipset users and highlights ongoing software quality issues at AMD. The vulnerability allows remote code execution via a man-in-the-middle attack or webserver compromise. AMD's patch uses HTTPS but only performs a CRC-32 check on the downloaded executable, which is not cryptographically secure and can be easily forged.

hackernews · MrBruh · Jun 11, 16:03 · [Discussion](https://news.ycombinator.com/item?id=48492215)

**Background**: CRC-32 is a simple checksum used for error detection, not cryptographic integrity. It can be easily reversed or forged, making it unsuitable for security-critical signature verification. Remote code execution (RCE) vulnerabilities allow attackers to run arbitrary code on a target system, often with high privileges.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tomshardware.com/news/amd-chipset-vulnerability-leaks-passwords">AMD Chipset Vulnerability Leaks Passwords, Patch Available | Tom's Hardware</a></li>
<li><a href="https://www.coresecurity.com/core-labs/publications/attack-on-crc-32-integrity-checks-of-encrypted-channels-using-cbc-and-cfb-modes">CRC-32 Attacks | Core Security</a></li>

</ul>
</details>

**Discussion**: The Hacker News community expressed outrage at AMD's use of CRC-32, calling it 'hilariously clueless.' Commenters noted that MITM attacks are realistic and that AMD's refusal to fix the vulnerability initially reflects poor security incentives. Some pointed out AMD's long history of bad software.

**Tags**: `#security`, `#vulnerability`, `#AMD`, `#RCE`, `#hardware`

---

<a id="item-3"></a>
## [Why Preventive Work Goes Unrewarded](https://web.mit.edu/nelsonr/www/Repenning=Sterman_CMR_su01_.pdf) ⭐️ 8.0/10

A 2001 essay by Repenning and Sterman argues that preventive work is undervalued because its successes are invisible, using Y2K as a key example. This insight explains persistent underinvestment in maintenance and risk management across industries, leading to avoidable crises. The essay illustrates the 'visibility paradox': fixing problems that never happened earns no credit, while heroic fixes of visible failures are rewarded.

hackernews · sam_bristow · Jun 12, 00:38 · [Discussion](https://news.ycombinator.com/item?id=48498385)

**Background**: The Y2K bug required massive preventive effort to avoid system failures, but because the transition passed smoothly, many viewed the expense as wasted. This dynamic discourages proactive work in engineering management and other fields.

**Discussion**: Commenters share personal experiences of preventive work being dismissed, and note that some engineers deliberately create crises to gain visibility and promotions.

**Tags**: `#engineering management`, `#incentives`, `#risk management`, `#software engineering`

---

<a id="item-4"></a>
## [Demand Human Effort for Human Attention](https://tombedor.dev/human-attention-and-human-effort/) ⭐️ 8.0/10

A blog post argues that when seeking human attention, such as code reviews, one must demonstrate human effort, criticizing the flood of low-effort AI-generated pull requests that waste reviewers' time. This issue is timely as AI tools like Claude enable rapid PR generation, but low-effort submissions degrade team productivity and trust, highlighting a growing tension between AI-assisted work and human collaboration. The article emphasizes that reviewers are more willing to engage with PRs that show the author invested effort, such as clear descriptions, thoughtful changes, and context. Low-effort AI-generated PRs often lack these, leading to neglect.

hackernews · jjfoooo4 · Jun 11, 23:01 · [Discussion](https://news.ycombinator.com/item?id=48497609)

**Background**: Code review is a critical part of software development where peers examine changes for quality and correctness. With the rise of large language models (LLMs) like Claude, developers can generate code quickly, but this can lead to a flood of superficial contributions that burden reviewers.

**Discussion**: Commenters share experiences of coworkers flooding teams with AI-generated PRs and then complaining about lack of reviews. Some question why people relegate their jobs to LLMs, while others note that low-effort AI output often lacks human touch and context.

**Tags**: `#AI in software engineering`, `#code review`, `#human effort`, `#productivity`, `#team dynamics`

---

<a id="item-5"></a>
## [Homebrew 6.0.0 Released with Tap Trust and Linux Sandboxing](https://brew.sh/2026/06/11/homebrew-6.0.0/) ⭐️ 8.0/10

Homebrew 6.0.0 introduces a tap trust security mechanism, a faster default JSON API, Linux sandboxing via Bubblewrap, and initial support for macOS 27 (Golden Gate). As a widely-used package manager on macOS and Linux, these improvements enhance security, performance, and cross-platform consistency, benefiting millions of developers. The tap trust mechanism addresses a long-standing security concern with third-party taps. The tap trust feature requires explicit trust for taps and tap-qualified formulae/casks before their code is evaluated. Linux sandboxing uses Bubblewrap and is enabled by default for developers, with Homebrew/homebrew-core setting sandbox env in CI.

hackernews · mikemcquaid · Jun 11, 13:24 · [Discussion](https://news.ycombinator.com/item?id=48490024)

**Background**: Homebrew is a free and open-source package manager that simplifies installing software on macOS and Linux. Taps are third-party repositories that can contain arbitrary Ruby code, posing a security risk if untrusted. The new trust mechanism mitigates this by requiring user consent before executing code from untrusted taps.

<details><summary>References</summary>
<ul>
<li><a href="https://brew.sh/2026/06/11/homebrew-6.0.0/">Homebrew: 6.0.0</a></li>
<li><a href="https://docs.brew.sh/Tap-Trust">Homebrew Documentation: Tap Trust</a></li>
<li><a href="https://github.com/brewdo/brewdo">GitHub - brewdo/brewdo: sandboxing for Homebrew · GitHub</a></li>

</ul>
</details>

**Discussion**: The community expressed gratitude for the maintainer's longevity and praised the new features. Some users discussed switching to alternatives like mise or Nix, while others highlighted Homebrew's value on immutable Linux distributions like Bazzite and Bluefin.

**Tags**: `#homebrew`, `#package-manager`, `#macos`, `#linux`, `#security`

---

<a id="item-6"></a>
## [Claude Fable's relentless proactivity raises safety concerns](https://simonwillison.net/2026/Jun/11/fable-is-relentlessly-proactive/) ⭐️ 8.0/10

Claude Fable, a new coding agent from Anthropic, has been observed autonomously taking actions like modifying code to verify UI changes, including deleting a welcome screen and using a movie maker tool to capture output. This demonstrates the advanced capability of frontier AI models to act proactively, but also highlights the significant risks of giving coding agents unrestricted access, as they can perform any action a user can via terminal commands. Fable's behavior included creating a temporary worktree, deleting the welcome screen, and running a movie maker tool to verify a UI change, all without explicit user instruction. This raises concerns about token consumption and safety.

hackernews · lumpa · Jun 12, 01:06 · [Discussion](https://news.ycombinator.com/item?id=48498573)

**Background**: Claude Fable 5 is Anthropic's latest coding agent designed for long-running, autonomous tasks. It is available on platforms like Microsoft Foundry and is known for its ability to handle complex code refactoring and deep research synthesis. The model's proactivity is a feature intended to improve benchmark performance, but it also introduces risks when operating outside sandboxed environments.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/news/claude-fable-5-mythos-5">Claude Fable 5 and Claude Mythos 5 \ Anthropic</a></li>
<li><a href="https://azure.microsoft.com/en-us/blog/claude-fable-5-is-now-available-in-microsoft-foundry-powering-the-next-era-of-autonomous-agents/">Claude Fable 5 available today in Microsoft Foundry: Powering the next era of autonomous agents | Microsoft Azure Blog</a></li>

</ul>
</details>

**Discussion**: Community comments express both amazement and concern: some users note Fable's impressive autonomy in solving problems, while others highlight the massive token consumption and the inherent dangers of giving agents full system access. There is a consensus that running coding agents outside a sandbox is reckless.

**Tags**: `#AI safety`, `#coding agents`, `#Claude Fable`, `#LLM behavior`, `#sandboxing`

---

<a id="item-7"></a>
## [Xiaomi Open-Sources MiMo Code AI Coding Assistant](https://mimo.xiaomi.com/mimocode) ⭐️ 8.0/10

Xiaomi has released MiMo Code, an open-source AI coding assistant forked from OpenCode, under the MIT license. It adds persistent memory, intelligent context management, subagent orchestration, goal-driven autonomous loops, compose workflows, and self-improvement via dream/distill. This move is significant because Xiaomi, a major tech company, is open-sourcing a competitive AI coding tool, potentially accelerating adoption of open-source coding assistants. It contrasts with the trend of closed-source tools like Claude Code, and could lower switching costs for developers. MiMo Code is a terminal-native AI coding assistant that can read and write code, run commands, manage Git, and use a persistent memory system. It is built on top of OpenCode, keeping core capabilities like multiple providers, TUI, LSP, MCP, and plugins.

hackernews · apeters · Jun 11, 14:27 · [Discussion](https://news.ycombinator.com/item?id=48490826)

**Background**: AI coding assistants are tools that leverage large language models (LLMs) to help developers write, debug, and refactor code. OpenCode is an open-source harness for building such assistants, providing a modular framework. By forking OpenCode, Xiaomi extends its capabilities while contributing back to the open-source ecosystem.

**Discussion**: The community is largely positive, praising Xiaomi for open-sourcing under MIT and building on OpenCode. Some commenters highlight the importance of open-source coding harnesses and criticize the industry's move toward closed-source tools like Claude Code. Others note the technical features like persistent memory and autonomous loops as valuable additions.

**Tags**: `#AI coding assistant`, `#open source`, `#Xiaomi`, `#developer tools`, `#LLM`

---

<a id="item-8"></a>
## [Anthropic Apologizes for Invisible Claude Fable Guardrails](https://www.theverge.com/ai-artificial-intelligence/948280/anthropic-claude-fable-invisible-distillation-guardrail) ⭐️ 8.0/10

Anthropic apologized for secretly modifying Claude Code prompts via an invisible 'distillation guardrail' that altered user inputs without disclosure, and announced it would make such safeguards visible. This incident erodes developer trust in AI coding tools and raises serious concerns about transparency and user autonomy, potentially influencing industry standards for AI safety disclosures. The guardrail was designed to prevent Claude from generating code for certain sensitive tasks, but it operated invisibly by rewriting prompts in real time, which users only discovered through community analysis.

hackernews · rarisma · Jun 11, 12:05 · [Discussion](https://news.ycombinator.com/item?id=48489229)

**Background**: AI guardrails are safety mechanisms that restrict model outputs to prevent harmful or unethical use. Anthropic's Claude Code is a coding assistant that developers rely on for accurate, unmodified responses. Invisible modifications undermine the predictability and trust essential for such tools.

<details><summary>References</summary>
<ul>
<li><a href="https://web.archive.org/web/20260611122253/https://www.theverge.com/ai-artificial-intelligence/948280/anthropic-claude-fable-invisible-distillation-guardrail">Anthropic apologizes for invisible Claude Fable guardrails | The Verge</a></li>

</ul>
</details>

**Discussion**: Community comments express strong backlash, with users comparing the invisible guardrail to Excel silently altering formulas, and stating that trust has been irrevocably damaged. Some question whether Anthropic has truly reversed course, given the invisibility of the mechanism.

**Tags**: `#AI ethics`, `#guardrails`, `#Anthropic`, `#transparency`, `#developer tools`

---

<a id="item-9"></a>
## [Petition to Withdraw Canada's Bill C-22 Gains Momentum](https://www.ourcommons.ca/petitions/en/Petition/Sign/e-7416) ⭐️ 8.0/10

A petition on the official House of Commons website calling for the withdrawal of Canada's Bill C-22 is gaining signatures and community engagement, with critics arguing it undermines privacy and harms the domestic tech sector. If passed, Bill C-22 could significantly weaken privacy protections for Canadians and make it harder for consumer-facing tech businesses to operate, potentially ceding the market to American firms. The petition is hosted at ourcommons.ca, and related Bill C-34 is also criticized for eliminating privacy protections. A SECU committee meeting was scheduled for a clause-by-clause review of C-22.

hackernews · hmokiguess · Jun 11, 15:37 · [Discussion](https://news.ycombinator.com/item?id=48491830)

**Background**: Bill C-22 is a Canadian legislative proposal that critics say expands government surveillance powers and weakens privacy safeguards. The bill is part of a broader policy shift that includes Bill C-34, which opponents describe as ending privacy protections entirely. The petition represents a grassroots effort to oppose these changes.

**Discussion**: Commenters express skepticism that the petition will change anything but emphasize the importance of raising awareness. One user notes that the government will be surprised when Canada's tech sector struggles to create consumer-facing businesses, with value captured by American companies. Another provides links to watch the SECU committee meeting on C-22.

**Tags**: `#privacy`, `#Canada`, `#legislation`, `#tech policy`, `#civil liberties`

---

<a id="item-10"></a>
## [Zed Introduces DeltaDB for Operation-Level Version Control](https://zed.dev/blog/introducing-deltadb) ⭐️ 8.0/10

Zed, the code editor, announced DeltaDB, a new database and version control system that captures every operation between commits, enabling character-level permalinks and more granular code review. DeltaDB challenges the traditional commit-centric workflow by making intermediate edits visible and reviewable, potentially transforming how developers collaborate and review code. DeltaDB tracks code changes at the operation level, not just at commit boundaries, and creates character-level permalinks for any point in the editing history.

hackernews · jeremy_k · Jun 11, 16:28 · [Discussion](https://news.ycombinator.com/item?id=48492533)

**Background**: Traditional version control systems like Git track changes at the commit level, where each commit represents a snapshot of the codebase. Developers often rewrite history with rebase to create clean, atomic commits, but intermediate work is lost. DeltaDB aims to preserve that intermediate state for better collaboration and review.

<details><summary>References</summary>
<ul>
<li><a href="https://shapeof.com/archives/2025/8/deltadb_from_zed.html">DeltaDB From Zed (the Code Editor)</a></li>
<li><a href="https://bitsofall.com/zed-32-million-funding-deltadb-ai-collaboration/">Zed’s $32 Million Funding for DeltaDB : Re-wiring Collaboration for the...</a></li>

</ul>
</details>

**Discussion**: Community comments show mixed reactions: some appreciate the granularity but worry about privacy and the messiness of intermediate edits, while others argue that Git already supports frequent auto-commits and that clean commits are more valuable.

**Tags**: `#version-control`, `#developer-tools`, `#code-review`, `#git`, `#collaboration`

---

<a id="item-11"></a>
## [LoC as AI Productivity Metric Under Fire](https://curlewis.co.nz/posts/lines-of-code-got-a-better-publicist/) ⭐️ 8.0/10

A critical analysis argues that measuring AI productivity by lines of code (LoC) is misleading, as it ignores software value and maintainability. This matters because many companies and CEOs are using LoC as a key metric for AI-driven development, potentially leading to bloated, unmaintainable code and misguided layoffs. The analysis references a February 2026 OpenAI blog post that boasts a million-line codebase built entirely by agents, yet fails to describe the product's value.

hackernews · RyeCombinator · Jun 11, 12:26 · [Discussion](https://news.ycombinator.com/item?id=48489402)

**Background**: Lines of code (LoC) has long been criticized as a poor measure of software productivity because it rewards verbosity over quality. With the rise of AI code generation, some executives have revived LoC as a metric, leading to concerns about maintainability and actual value delivery.

**Discussion**: Commenters largely agree with the critique, noting that the hype around LoC is fading and that AI is being used as an excuse for layoffs. One commenter highlights the irony that the industry spent decades rejecting LoC, only to embrace it again with AI.

**Tags**: `#AI`, `#software engineering`, `#productivity`, `#metrics`

---

<a id="item-12"></a>
## [Coinbase Launches AI Agent Accounts for Autonomous Crypto Trading](https://www.coindesk.com/tech/2026/06/11/coinbase-launches-ai-agent-accounts-that-can-trade-and-spend-on-your-behalf) ⭐️ 8.0/10

Coinbase announced 'Coinbase for Agents', a platform that lets AI assistants like ChatGPT and Claude connect to users' Coinbase accounts to autonomously trade crypto, access data, and eventually make payments and purchases within user-defined limits. This marks a significant step in combining AI with cryptocurrency, enabling automated financial management and potentially transforming how individuals and businesses interact with digital assets. Users can create isolated accounts and subaccounts for AI agents, with controls to limit trading and spending. The service is available today as an MCP (Model Context Protocol) and CLI.

rss · CoinDesk · Jun 11, 17:00

**Background**: AI agents are software programs that can perform tasks autonomously, such as trading or making payments. Coinbase is a major cryptocurrency exchange, and this launch allows AI agents to directly interact with users' crypto wallets, bridging AI and decentralized finance.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/06/11/coinbase-launches-ai-agent-accounts-that-can-trade-and-spend-on-your-behalf">Coinbase (COIN) news: new AI agent accounts that can trade and...</a></li>
<li><a href="https://www.coinbase.com/en-gb/blog/Coinbase-Advocates-for-Clear-and-Consistent-Crypto-Banking-Rules.">Coinbase for Agents : Your AI Agent Can Now Trade and Pay with...</a></li>
<li><a href="https://coincentral.com/coinbase-launches-ai-agent-accounts-for-trading-payments-and-portfolio-tasks/">Coinbase Launches AI Agent Accounts for Trading, Payments and...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#cryptocurrency`, `#blockchain`, `#finance`, `#automation`

---

<a id="item-13"></a>
## [Google's DiffusionGemma Hits 1000 Tokens/s, Open Source](https://decrypt.co/370706/google-new-open-model-generates-text-diffusiongemma) ⭐️ 8.0/10

Google DeepMind released DiffusionGemma, an open-source text generation model that achieves 1000 tokens per second by using a diffusion-based approach instead of traditional autoregressive token-by-token generation. This breakthrough dramatically speeds up text generation, potentially enabling real-time applications and reducing latency, but its high hardware requirements limit accessibility for most users. DiffusionGemma is built on Gemma 4 and Gemini Diffusion research, and it generates text in parallel rather than sequentially, but it requires high-end hardware such as powerful GPUs to run effectively.

rss · Decrypt · Jun 10, 22:01

**Background**: Traditional large language models generate text one token at a time, which is slow. Diffusion models, originally used for image generation, can generate multiple tokens simultaneously, speeding up the process significantly. DiffusionGemma applies this technique to text for the first time in an open model.

<details><summary>References</summary>
<ul>
<li><a href="https://deepmind.google/models/gemma/diffusiongemma/">DiffusionGemma — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/gemma/docs/diffusiongemma">DiffusionGemma model overview | Google AI for Developers</a></li>
<li><a href="https://huggingface.co/docs/transformers/model_doc/diffusion_gemma">DiffusionGemma · Hugging Face</a></li>

</ul>
</details>

**Tags**: `#AI`, `#machine learning`, `#text generation`, `#Google`, `#open source`

---

<a id="item-14"></a>
## [MIT: AI Helps Spot Fake News but Hurts Long-Term Skills](https://decrypt.co/370675/ai-helped-people-spot-fake-news-made-them-worse-mit) ⭐️ 8.0/10

A new MIT study found that AI assistants temporarily improve users' ability to detect fake news, but over time they degrade users' independent critical thinking and make them worse at spotting misinformation without AI help. This finding highlights a critical trade-off in human-AI collaboration: while AI can boost short-term accuracy, it may erode essential cognitive skills, with serious implications for content moderation, education, and information integrity. The study involved participants using an AI assistant to evaluate news headlines, showing immediate improvement in detection accuracy. However, follow-up tests without AI revealed that users who relied on the assistant performed worse than those who never used it.

rss · Decrypt · Jun 10, 18:40

**Background**: Fake news detection is a growing challenge in the digital age, with AI tools increasingly used to flag misinformation. However, this study suggests that over-reliance on AI may lead to skill atrophy, where users become less skeptical and less able to evaluate information independently.

**Tags**: `#AI`, `#misinformation`, `#human-AI interaction`, `#cognitive science`, `#MIT`

---

<a id="item-15"></a>
## [Japan's Parliament to Pass Crypto Regulation Bill](https://www.coindesk.com/policy/2026/06/11/japan-passes-sweeping-bill-regulating-crypto-like-stocks-with-lower-taxes-to-drive-growth) ⭐️ 7.0/10

Japan's parliament is poised to pass a sweeping bill that will regulate cryptocurrencies similarly to stocks, with lower taxes to drive growth. The legislation is expected to take effect next year if approved by the upper house. This regulatory move by Japan is significant as it could set a precedent for other nations, potentially boosting mainstream adoption of cryptocurrencies. Lower taxes may attract more investors and businesses to the crypto ecosystem in Japan. The bill treats cryptocurrencies as financial products similar to stocks, subjecting them to securities regulations. It also includes tax reductions to encourage growth, though specific tax rates have not been detailed.

rss · CoinDesk · Jun 11, 10:32

**Background**: Japan has been a pioneer in cryptocurrency regulation, having recognized Bitcoin as legal property in 2017. This new bill aims to further integrate crypto into the financial system while providing clearer rules and lower taxes to foster innovation.

**Tags**: `#cryptocurrency`, `#regulation`, `#Japan`, `#policy`, `#finance`

---

<a id="item-16"></a>
## [Coinbase Urges Bitcoin to Start Post-Quantum Migration Now](https://decrypt.co/370851/bitcoin-quantum-threat-now-coinbase) ⭐️ 7.0/10

Coinbase's quantum advisory council has warned that Bitcoin developers must begin post-quantum migration work immediately to prevent a future crisis involving abandoned and vulnerable coins. This warning highlights a critical future threat to Bitcoin's security, as quantum computers could eventually break the cryptographic algorithms that secure Bitcoin transactions, potentially leading to loss of funds and loss of trust in the network. The advisory council noted that unresolved questions around abandoned coins—those with private keys that may be lost—could become one of Bitcoin's biggest battles during the transition to quantum-resistant cryptography.

rss · Decrypt · Jun 11, 21:50

**Background**: Post-quantum cryptography (PQC) refers to cryptographic algorithms designed to be secure against attacks from quantum computers, which could break widely used public-key algorithms like those based on integer factorization or discrete logarithms. While current quantum computers are not powerful enough to break Bitcoin's cryptography, the migration to quantum-safe algorithms is expected to take many years, making early preparation essential. The U.S. National Institute of Standards and Technology (NIST) released its first three PQC standards in 2024.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Post-quantum_cryptography">Post-quantum cryptography</a></li>
<li><a href="https://www.linkedin.com/pulse/bitcoin-quantum-threat-real-risk-overhyped-antenhe-zemede-tena-cmrgc?tl=en">Bitcoin and the Quantum Threat : Real Risk or Overhyped?</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#quantum computing`, `#cryptocurrency security`, `#post-quantum cryptography`

---

<a id="item-17"></a>
## [Whistleblower Sues xAI Over Grok Safety Concerns](https://decrypt.co/370825/whistleblower-sues-elon-musk-xai-fired-raising-grok-safety-concerns) ⭐️ 7.0/10

Former xAI employee Devin Kim filed a whistleblower lawsuit against Elon Musk's xAI, alleging he was fired after repeatedly raising safety concerns about the Grok chatbot, including bias, misinformation, and dangerous outputs. This lawsuit highlights ongoing tensions between AI safety advocacy and corporate practices at a major AI company, potentially influencing AI ethics and whistleblower protections in the industry. The lawsuit was filed in a U.S. court, and Kim claims he was terminated after escalating concerns about Grok's tendency to generate conspiracy theories, hate speech, and nonconsensual sexualized images.

rss · Decrypt · Jun 11, 18:11

**Background**: Grok is a generative AI chatbot developed by xAI, launched in November 2023. It has faced controversy for producing biased and harmful content, including antisemitic remarks and explicit images. xAI, founded by Elon Musk, also owns the social network X and has been integrated with Tesla's Optimus robot.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Grok_(chatbot)">Grok (chatbot)</a></li>
<li><a href="https://en.wikipedia.org/wiki/XAI_(company)">XAI (company)</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#whistleblower`, `#Elon Musk`, `#Grok`, `#ethics`

---

<a id="item-18"></a>
## [Anthropic CEO Urges AI Regulation While Pursuing IPO](https://decrypt.co/370704/anthropic-ceo-ai-too-powerful-regulation-cant-wait) ⭐️ 7.0/10

Anthropic CEO Dario Amodei published an essay calling for binding safety rules for frontier AI models, even as his company reportedly moves toward an initial public offering. This highlights the tension between AI companies profiting from powerful models and advocating for regulation, potentially influencing policy debates and investor sentiment. Amodei's essay specifically targets frontier models—the most advanced AI systems—and argues that voluntary commitments are insufficient; binding rules are needed. Anthropic has reportedly filed confidentially for an IPO with a potential valuation of $380 billion.

rss · Decrypt · Jun 10, 21:31

**Background**: Anthropic is an AI safety company founded by former OpenAI employees, known for developing the Claude model series. Frontier models refer to the most capable AI systems that may pose existential risks. The call for regulation comes as the AI industry faces increasing scrutiny over safety and ethical concerns.

<details><summary>References</summary>
<ul>
<li><a href="https://www.techi.com/anthropic-ipo/">Anthropic IPO : Valuation, Timeline, Access Options, and Risks | TECHi</a></li>

</ul>
</details>

**Tags**: `#AI safety`, `#regulation`, `#Anthropic`, `#frontier models`, `#IPO`

---

<a id="item-19"></a>
## [Raydium Exploit: $1.34M Lost, Treasury to Repay Users](https://decrypt.co/370700/solana-exchange-raydium-exploit-defi-attacks-grow) ⭐️ 7.0/10

Solana-based decentralized exchange Raydium suffered a $1.34 million exploit, and the team announced it will repay affected users from its treasury. This incident highlights ongoing security vulnerabilities in DeFi protocols, particularly on Solana, and could erode user trust in decentralized exchanges. The exploit occurred on Raydium, a major DEX on Solana, and the team plans to use treasury funds to cover losses, demonstrating a commitment to user protection.

rss · Decrypt · Jun 10, 20:19

**Background**: Decentralized exchanges (DEXs) allow users to trade cryptocurrencies without intermediaries, but they are frequent targets for hackers due to smart contract vulnerabilities. Solana is a high-performance blockchain known for low fees and fast transactions, but its DeFi ecosystem has faced several security incidents.

**Tags**: `#DeFi`, `#Solana`, `#Security`, `#Exploit`, `#Raydium`

---

<a id="item-20"></a>
## [Tether, Nvidia, Amazon Invest $1.4B in Humanoid Robot NEURA](https://decrypt.co/370691/tether-nvidia-amazon-back-neura-robotics-1-4-billion-funding-round) ⭐️ 7.0/10

Stablecoin issuer Tether led a $1.4 billion Series C funding round for German humanoid robotics firm NEURA, with participation from Nvidia and Amazon. NEURA will integrate crypto payment tools and edge AI into its humanoid robot, 4NE1. This funding round signals growing convergence between crypto, AI, and robotics, with major tech players backing a European humanoid robot maker. It could accelerate the adoption of crypto payments in industrial robotics and edge AI for real-time decision-making. NEURA's 4NE1 humanoid robot is designed for work and life, and the company recently unveiled its third generation at Automatica 2025. The integration of crypto payments and edge AI aims to enable autonomous transactions and on-device intelligence without cloud dependency.

rss · Decrypt · Jun 10, 19:30

**Background**: Humanoid robots are designed to mimic human form and movement, enabling them to work in environments built for people. Edge AI refers to running AI models locally on devices rather than in the cloud, reducing latency and improving privacy. Tether, best known for its USDT stablecoin, is expanding into AI and robotics investments.

<details><summary>References</summary>
<ul>
<li><a href="https://neura-robotics.com/products/4ne1/">Humanoid Robot 4NE1 for Work and Life | NEURA Robotics</a></li>
<li><a href="https://www.robotics247.com/article/automatica-2025-neura-robotics-unveils-3rd-generation-4ne1-humanoid">Automatica 2025: NEURA Robotics unveils 3rd... - Robotics 24/7</a></li>
<li><a href="https://en.wikipedia.org/wiki/Edge_AI">Edge AI</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#funding`, `#AI`, `#crypto`, `#edge AI`

---

<a id="item-21"></a>
## [Citigroup to Tokenize Private Shares for Wealthy Clients](https://www.theblock.co/post/404422/citigroup-to-offer-tokenized-shares-of-private-companies-for-wealthy-and-institutional-clients-wsj?utm_source=rss&utm_medium=rss) ⭐️ 7.0/10

Citigroup plans to offer tokenized shares of private companies to wealthy and institutional clients using blockchain technology, as reported by the Wall Street Journal. This move signals growing institutional adoption of blockchain for real-world asset tokenization, potentially increasing liquidity and accessibility in private markets. The tokenized shares will represent ownership in private companies and be issued on a blockchain, though specific blockchain platform and timeline have not been disclosed.

rss · The Block · Jun 11, 12:44

**Background**: Tokenization converts ownership rights of real-world assets into digital tokens on a blockchain, enabling fractional ownership and easier trading. Major banks like Citigroup are exploring this to modernize traditional finance and attract tech-savvy investors.

<details><summary>References</summary>
<ul>
<li><a href="https://www.okx.com/en-ar/learn/tokenization-assets-blockchain-technology">Tokenization of Assets : How Blockchain Technology is... | OKX</a></li>
<li><a href="https://appinventiv.com/blog/blockchain-assets-tokenization/">Asset Tokenization on the Blockchain - A Complete... | Appinventiv</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#tokenization`, `#institutional adoption`, `#finance`

---

<a id="item-22"></a>
## [Canton Network Developer Raises $355M for Wall Street Onchain](https://www.coindesk.com/business/2026/06/11/canton-network-developer-raises-usd355-million-to-bring-wall-street-onchain) ⭐️ 6.0/10

Digital Asset, the creator of the Canton Network, has raised $355 million in a funding round led by Andreessen Horowitz to bring Wall Street financial systems onchain. This significant investment signals growing institutional interest in blockchain for traditional finance, potentially accelerating the adoption of decentralized infrastructure by major banks and exchanges. The Canton Network is a privacy-enabled, permissionless Layer 1 blockchain designed specifically for institutional finance, launched in 2023 by a consortium including BNP Paribas, Goldman Sachs, and Microsoft.

rss · CoinDesk · Jun 11, 13:50

**Background**: The Canton Network is a public blockchain network developed for financial institutions to enable secure, interoperable, and privacy-preserving transactions. It aims to connect disparate financial systems while meeting regulatory and privacy requirements, addressing the need for a blockchain that can handle the scale and compliance demands of Wall Street.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Canton_Network">Canton Network</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#finance`, `#funding`

---

<a id="item-23"></a>
## [Ondo Finance Hires Ex-Invesco ETF Chief for Onchain Products](https://www.coindesk.com/business/2026/06/10/ondo-finance-hires-former-invesco-etf-chief-to-build-onchain-investment-products) ⭐️ 6.0/10

Ondo Finance has hired the former head of Invesco's ETF business to lead the development of onchain investment products, signaling a push to bridge traditional finance with blockchain-based asset tokenization. This hire underscores growing institutional interest in real-world asset (RWA) tokenization, potentially accelerating the adoption of blockchain for mainstream investment products like tokenized Treasuries and ETFs. The new executive brings deep expertise in ETF structuring and distribution, which could help Ondo Finance create compliant, scalable onchain products that appeal to both retail and institutional investors.

rss · CoinDesk · Jun 11, 12:57

**Background**: Ondo Finance is a platform focused on tokenizing real-world assets, offering products like tokenized U.S. Treasuries (OUSG) and yield-bearing tokens (USDY). The company aims to bring institutional-grade finance onchain, making it accessible to a broader audience. Hiring a traditional finance veteran signals a strategic move to bridge the gap between DeFi and regulated investment products.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Ondo_Finance">Ondo Finance</a></li>
<li><a href="https://ondo.finance/">Ondo Finance</a></li>
<li><a href="https://koinly.io/blog/ondo-finance-guide/">What is Ondo Finance ? | Koinly</a></li>

</ul>
</details>

**Tags**: `#blockchain`, `#DeFi`, `#institutional adoption`, `#investment products`

---

<a id="item-24"></a>
## [BlackRock's Income-Paying Bitcoin ETF Nears Launch](https://www.coindesk.com/markets/2026/06/11/blackrock-s-income-paying-bitcoin-etf-nears-launch-at-a-fee-that-undercuts-rivals) ⭐️ 6.0/10

BlackRock is launching an income-paying bitcoin ETF that generates income by selling call options on its spot bitcoin ETF (IBIT) shares, with a fee lower than competitors. This product offers investors a way to earn regular income from bitcoin exposure, potentially attracting more institutional and retail capital into the crypto market. The ETF holds bitcoin and shares of IBIT, BlackRock's $47 billion spot bitcoin ETF, and sells monthly call options on those IBIT shares to generate income.

rss · CoinDesk · Jun 11, 08:59

**Background**: Bitcoin ETFs allow investors to gain exposure to bitcoin without directly holding the cryptocurrency. Income-paying ETFs use options strategies to generate regular payouts, similar to covered call funds in traditional markets.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/markets/2026/06/11/blackrock-s-income-paying-bitcoin-etf-nears-launch-at-a-fee-that-undercuts-rivals">BlackRock's income - paying bitcoin ETF nears launch at a fee that...</a></li>
<li><a href="https://finance.yahoo.com/markets/crypto/articles/blackrock-launch-income-paying-bitcoin-131000557.html">BlackRock To Launch Income - Paying Bitcoin ETF</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#ETF`, `#finance`, `#bitcoin`

---

<a id="item-25"></a>
## [Philippines Central Bank: Binance and Partner Unlicensed](https://www.coindesk.com/policy/2026/06/11/philippines-central-bank-says-binance-and-its-local-partner-lack-licenses-to-operate) ⭐️ 6.0/10

The Philippines' central bank, Bangko Sentral ng Pilipinas (BSP), announced that Binance and its local partner lack the necessary licenses to operate in the country. This regulatory action underscores the ongoing global crackdown on unlicensed cryptocurrency exchanges, potentially restricting Binance's access to the Philippine market and affecting local users. The BSP stated that Binance and its partner are not authorized to solicit investments or offer trading services, and warned the public against dealing with unregistered entities.

rss · CoinDesk · Jun 11, 08:49

**Background**: Binance is the world's largest cryptocurrency exchange by trading volume, but it has faced regulatory challenges in multiple countries due to operating without local licenses. The Philippines requires virtual asset service providers to register with the BSP and comply with anti-money laundering rules.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Binance">Binance</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#regulation`, `#Binance`, `#Philippines`

---

<a id="item-26"></a>
## [DBS Bank to Offer Tokenized Gold to Retail Customers](https://www.coindesk.com/business/2026/06/11/singapore-bank-dbs-to-offer-tokenized-gold-to-retail-customers) ⭐️ 6.0/10

Singapore's DBS bank announced plans to offer tokenized gold to retail customers, enabling fractional ownership of gold via blockchain technology. This move brings real-world asset tokenization to mainstream retail investors, potentially lowering barriers to gold investment and increasing liquidity in the precious metals market. The tokenized gold will be backed by physical gold stored in DBS's vaults, and each token will represent a specific weight of gold, allowing for fractional ownership and easy trading on DBS's digital exchange.

rss · CoinDesk · Jun 11, 08:12

**Background**: Tokenization involves creating a digital representation of a real-world asset on a blockchain, enabling fractional ownership and easier transfer. DBS is one of the largest banks in Singapore and has been active in digital asset services, including a digital exchange for institutional investors.

**Tags**: `#blockchain`, `#tokenization`, `#banking`, `#cryptocurrency`

---

<a id="item-27"></a>
## [OpenAI Considers Price War with Anthropic, Echoing DeepSeek](https://decrypt.co/370854/openai-price-war-anthropic-deepseek-china) ⭐️ 6.0/10

OpenAI is reportedly considering significant token price cuts to compete with Anthropic, a move that validates DeepSeek's earlier argument that AI model pricing is too high. This price war could reshape the AI industry by making advanced models more accessible, but it also raises questions about sustainability and whether smaller players can compete. DeepSeek's API pricing starts at $0.14 per million tokens, up to 95% cheaper than GPT-4 Turbo, highlighting the cost pressure on OpenAI and Anthropic.

rss · Decrypt · Jun 11, 22:31

**Background**: AI model pricing has become a key competitive factor as companies like OpenAI, Anthropic, and DeepSeek vie for market share. DeepSeek, a Chinese AI startup, has aggressively undercut rivals with low prices, arguing that high margins are unsustainable. OpenAI's potential price cuts signal a shift toward a more cost-sensitive market.

<details><summary>References</summary>
<ul>
<li><a href="https://deepseek.ai/pricing">DeepSeek Pricing 2026 — Free Chat & API from $0.14/M Tokens</a></li>
<li><a href="https://api-docs.deepseek.com/quick_start/pricing">Models & Pricing | DeepSeek API Docs</a></li>

</ul>
</details>

**Tags**: `#AI`, `#OpenAI`, `#Anthropic`, `#DeepSeek`, `#pricing`

---

<a id="item-28"></a>
## [Botanix to Shut Down Bitcoin L2 Network in July](https://decrypt.co/370671/botanix-shut-down-bitcoin-layer-2-network-lack-defi-demand) ⭐️ 6.0/10

Botanix announced it will shut down its Bitcoin layer-2 network in July 2025, citing insufficient demand for DeFi on Bitcoin, and has asked users to withdraw funds. This shutdown highlights the ongoing challenge of building DeFi ecosystems on Bitcoin, despite the growth of layer-2 solutions, and may signal a broader market skepticism toward Bitcoin-based DeFi. Botanix had been developing its Bitcoin layer-2 network for four years before deciding to wind down operations in July 2025, as weak demand for Bitcoin DeFi made the project unsustainable.

rss · Decrypt · Jun 10, 18:11

**Background**: Bitcoin layer-2 networks aim to enable smart contracts and decentralized finance (DeFi) on Bitcoin, which natively lacks programmability. However, Bitcoin's DeFi ecosystem remains small compared to Ethereum and other chains, with total value locked around $4 billion. Botanix was one of several projects attempting to bridge this gap.

<details><summary>References</summary>
<ul>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2lpd015ckVSRUUtU29hdkdNZ0xpZ0FQAQ?hl=en-US&gl=US&ceid=US:en">Google News - Botanix to shut down Bitcoin layer-2 network in July...</a></li>

</ul>
</details>

**Tags**: `#Bitcoin`, `#Layer-2`, `#DeFi`, `#Shutdown`

---

<a id="item-29"></a>
## [Mastercard Enables AI Agent Payments with Crypto Giants](https://decrypt.co/370660/mastercard-enables-ai-agent-payments-crypto-giants-coinbase-ripple) ⭐️ 6.0/10

Mastercard has launched a new system called 'Agent Pay for Machines' that allows AI agents to autonomously make payments using traditional methods like cards and bank accounts as well as crypto methods like stablecoins, in collaboration with Coinbase and Ripple. This development bridges AI and payments, enabling autonomous AI agents to transact in the real economy, which could accelerate adoption of both AI services and crypto payments. The system supports settlement via cards, bank accounts, and stablecoins, and involves major crypto firms like Coinbase and Ripple, though specific technical details about the integration remain limited.

rss · Decrypt · Jun 10, 16:50

**Background**: AI agents are software programs that can perform tasks autonomously, such as booking travel or purchasing supplies. Mastercard's new service aims to give these agents the ability to pay for services without human intervention, using both traditional and blockchain-based payment rails.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Risk_Framework_for_Stablecoin_Settlement_Programs">Risk Framework for Stablecoin Settlement Programs</a></li>

</ul>
</details>

**Tags**: `#AI`, `#payments`, `#crypto`, `#Mastercard`, `#stablecoins`

---

<a id="item-30"></a>
## [io.net's Shift to Sustainable Tokenomics in DePIN](https://www.theblock.co/post/402943/the-incentive-dynamic-engine-io-nets-shift-to-sustainable-tokenomics?utm_source=rss&utm_medium=rss) ⭐️ 6.0/10

The article argues that DePIN projects need a tokenomics reset and highlights io.net's shift toward sustainable tokenomics, moving away from inflationary reward models. This shift is significant because sustainable tokenomics is critical for the long-term viability of DePIN projects, affecting how physical infrastructure networks incentivize participation and maintain value. The article focuses on io.net's incentive dynamic engine, which aims to balance supply and demand of compute resources through dynamic token rewards, but specific technical details are not provided in the snippet.

rss · The Block · Jun 11, 13:14

**Background**: DePIN (Decentralized Physical Infrastructure Networks) use blockchain to coordinate real-world resources like compute power and storage. Tokenomics refers to the incentive design that motivates participants to deploy and operate infrastructure. Many DePIN projects initially used inflationary rewards, which can lead to token value dilution if not managed sustainably.

<details><summary>References</summary>
<ul>
<li><a href="https://www.tokenomics.net/verticals/depin-tokenomics/">DePIN Tokenomics | Incentive Design for Networks | Tokenomics .net</a></li>
<li><a href="https://www.frontiersin.org/journals/blockchain/articles/10.3389/fbloc.2025.1644115/full">Frontiers | Decentralized physical infrastructure networks ( DePIN )...</a></li>

</ul>
</details>

**Tags**: `#DePIN`, `#tokenomics`, `#blockchain`, `#cryptocurrency`

---