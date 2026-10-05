---
layout: default
title: "Horizon Summary: 2026-10-05 (EN)"
date: 2026-10-05
lang: en
---

> From 30 items, 16 important content pieces were selected

---

1. [Strata Runs Qwen 3.8 Flash Next (125B) on an RTX 4090 at 100+ Tokens/s](#item-1) ⭐️ 8.0/10
2. [Bob Cringely, Early Apple Employee and Tech Documentarian, Dies](#item-2) ⭐️ 8.0/10
3. [OKX and NYSE Parent ICE File for 24/7 Tokenized U.S. Stock Trading](#item-3) ⭐️ 8.0/10
4. [Tippett Studio animation archive surfaces online after closure](#item-4) ⭐️ 7.0/10
5. [Zarf's Blog Post on Infidel and Memory Corruption Sparks HN Discussion](#item-5) ⭐️ 7.0/10
6. [Browser-native VB6 IDE recreates classic Visual Basic 6](#item-6) ⭐️ 7.0/10
7. [RemoveMacAI script strips Apple Intelligence from macOS 27 to reclaim disk space](#item-7) ⭐️ 7.0/10
8. [Improper Redaction Exposes Google Data Center Water and Power Use](#item-8) ⭐️ 7.0/10
9. [Self-hosted HTTP tunnels using SSH and Nginx](#item-9) ⭐️ 7.0/10
10. [Irkutsk lab worker dies from plague, nearly 200 contacts monitored](#item-10) ⭐️ 7.0/10
11. [ICBA Sues OCC Over Crypto's 'Side Door' Into Banking](#item-11) ⭐️ 7.0/10
12. [Zcash's 25-second blocks go live on public testnet ahead of schedule](#item-12) ⭐️ 6.0/10
13. [BlackRock Signals How Tokenization Could Reshape Investment Portfolios](#item-13) ⭐️ 6.0/10
14. [Trump Taps Jay Clayton, SEC Chair Who Sued Ripple, to Lead AI Push](#item-14) ⭐️ 6.0/10
15. [Near Intents Recovers $3.8M After 48-Hour Ultimatum to Attacker](#item-15) ⭐️ 6.0/10
16. [Chainalysis Uses AI to Trace $387M Bitget Hack to North Korea](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Strata Runs Qwen 3.8 Flash Next (125B) on an RTX 4090 at 100+ Tokens/s](https://github.com/Niko1221/Strata) ⭐️ 8.0/10

A GitHub project called Strata (by Niko1221) demonstrates running the 125B-parameter Qwen 3.8 Flash Next model on a single consumer RTX 4090 at roughly 100 tokens per second, with one user reporting 124 tokens/s on a 4090 paired with 128GB DDR5 and a Ryzen 7950X3D. The release drew heavy community attention (728 points, 325 comments) and prompted independent benchmarking of the approach. If the numbers hold up, it means a frontier-class 125B sparse MoE model can be served locally on hardware that costs a few thousand dollars instead of a datacenter GPU, which could shift how developers and small teams approach private, low-cost inference. It also intensifies the debate over how much quality is sacrificed when pushing quantization below 4-bit to fit such a large model into 24GB of VRAM. Qwen 3.8 Flash Next is a sparse mixture-of-experts model with 125B total parameters, only 6B activated per token, plus 51B parameters of n-gram embedding tables held off the accelerator, which is what makes the low memory footprint possible. Community testing is mixed: one user measured a median vision-grounding error of 154.8 pixels with Strata versus 46.5 pixels with the same GGUF and vision adapter on llama.cpp, while another reported the setup was about twice as fast as Qwen-3.8-27B on a 32GB R9700.

hackernews · snehesht · Oct 4, 12:51 · [Discussion](https://news.ycombinator.com/item?id=49953495)

**Background**: Quantization reduces the numerical precision of model weights (for example from 16-bit to 4-bit or lower) so that large models fit into limited GPU memory, at the cost of some accuracy. Mixture-of-experts (MoE) architectures like Qwen 3.8 Flash Next only activate a small subset of parameters per token, which makes them far cheaper to run than their total parameter count suggests. Strata is an inference project that combines aggressive quantization with offloading techniques to run such models on consumer GPUs.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/QwenLM/Qwen3.8-Flash-Next/">Qwen3.8-Flash-Next - GitHub</a></li>
<li><a href="https://arxiv.org/abs/2608.30320">[2608.30320] On the Design of Qwen3.8-Next Architecture ...</a></li>
<li><a href="https://arxiv.org/html/2411.02355">“Give Me BF16 or Give Me Death”? Accuracy-Performance Trade - Offs ...</a></li>

</ul>
</details>

**Discussion**: Sentiment is enthusiastic but skeptical on quality: one commenter doubts sub-4-bit quants are worth it and prefers 4-bit on rented GPUs for coding tasks, while a benchmark comparison showed Strata's vision grounding error was roughly three times worse than llama.cpp on identical weights. Others were positive, reporting 124 tokens/s on a 4090 and calling the setup game-changing for a 32GB R9700, and one user asked for the To Do list TUI shown in the repo to be ported to Pi.

**Tags**: `#LLM`, `#quantization`, `#consumer-hardware`, `#inference`, `#performance`

---

<a id="item-2"></a>
## [Bob Cringely, Early Apple Employee and Tech Documentarian, Dies](https://news.ycombinator.com/item?id=49949438) ⭐️ 8.0/10

Bob Cringely, whose real name was Mark Stephens (also spelled Stevens), passed away in his sleep early Saturday, according to a family friend posting on Hacker News. He was an early Apple employee and the creator of influential PBS documentaries such as 'Triumph of the Nerds' and 'Accidental Empires'. Cringely's documentaries and writing shaped how a generation understands the birth of the personal computer industry, and his death drew hundreds of tributes on Hacker News. His work remains a key reference for anyone studying Silicon Valley's early history and the personalities behind Apple, Microsoft, and IBM. Cringely was born Mark Stephens in Apple Creek, Ohio, and reportedly was Apple employee number 12; 'Robert X. Cringely' was originally a pen name used by a string of InfoWorld columnists. His 1996 documentary 'Triumph of the Nerds' was produced by John Gau Productions and Oregon Public Broadcasting for Channel 4 and PBS, and is now available on the Internet Archive.

hackernews · paveworld · Oct 4, 00:50

**Background**: 'Triumph of the Nerds' is a 1996 British/American television documentary that traces the development of the personal computer in the United States from World War II to 1995, featuring interviews with figures like Steve Ballmer and Larry Ellison. Cringely also wrote 'Accidental Empires', a book about the rise of the PC industry, and later blogged at cringely.com about technology and his personal struggles.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Triumph_of_the_Nerds">Triumph of the Nerds - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Robert_X._Cringely">Robert X. Cringely - Wikipedia</a></li>
<li><a href="https://www.wired.com/1998/12/cringely/">The Double Life of Robert X. Cringely | WIRED</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters shared fond memories of Cringely's documentaries and writing, with some quoting memorable lines from 'Triumph of the Nerds' and recommending it on the Internet Archive. Others noted his difficult final years—losing his house, his son, and suffering a heart attack and stroke—while a few critics pointed to past accusations that he misled readers and fabricated content.

**Tags**: `#Bob Cringely`, `#Apple`, `#tech history`, `#documentaries`, `#obituary`

---

<a id="item-3"></a>
## [OKX and NYSE Parent ICE File for 24/7 Tokenized U.S. Stock Trading](https://www.coindesk.com/markets/2026/10/05/okx-and-nyse-s-owner-file-for-round-the-clock-tokenized-trading-in-u-s-stocks) ⭐️ 8.0/10

OKX, a major cryptocurrency exchange, and Intercontinental Exchange (ICE), the parent company of the New York Stock Exchange, have filed for a joint venture to offer round-the-clock tokenized trading of U.S. stocks. The filing signals concrete regulatory progress toward bringing blockchain-based, 24/7 equity trading into the regulated U.S. market. This is a major convergence of crypto and traditional finance: if approved, it could reshape how U.S. equities are traded by removing traditional market hours and settlement constraints. It would affect retail and institutional investors, brokers, exchanges, and the broader tokenization ecosystem, potentially pressuring other venues to follow suit. The venture would enable 24/7 trading of tokenized U.S. stocks, meaning equities represented as blockchain-based tokens that can trade outside standard market hours. The filing is a regulatory step rather than an approval, so the timeline, exact structure, and scope of the offering remain subject to review.

rss · CoinDesk · Oct 5, 04:45

**Background**: Tokenized stocks are digital tokens on a blockchain that represent shares of publicly traded companies, allowing for features like 24/7 trading and easier transferability compared with traditional brokerage accounts. OKX is a major cryptocurrency exchange founded in 2013, while ICE is an American multinational financial services company that operates global exchanges including the NYSE. The move fits a broader trend of crypto firms and traditional exchanges exploring tokenized real-world assets.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OKX">OKX - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Intercontinental_Exchange">Intercontinental Exchange - Wikipedia</a></li>
<li><a href="https://traderverse.io/blog/stock-market-tokenization">Tokenization and 24/7 Trading : The Future of Stock ... | Traderverse</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#crypto`, `#traditional finance`, `#stock trading`, `#blockchain`

---

<a id="item-4"></a>
## [Tippett Studio animation archive surfaces online after closure](https://filmstories.co.uk/news/tippett-studios-in-the-wake-of-its-closure-a-digital-archive-of-animated-materials-appears-online/) ⭐️ 7.0/10

Following the closure of Tippett Studio's Berkeley office, a digital archive of the studio's animated materials has been uploaded to the Internet Archive at archive.org/details/tippett-archive. According to community discussion, roughly 90GB of content was rescued from a CD binder spotted at auction and preserved by an anonymous individual. Tippett Studio is a legendary visual effects and animation house founded by Phil Tippett, and this archive preserves a significant piece of animation and VFX history that might otherwise have been lost. The effort highlights the growing role of community-driven digital preservation in saving culturally important media after studios shut down. The archive is hosted on the Internet Archive and is accessible via a direct link shared by community members. Commenters note that the material was rescued from physical media (CDs) found at auction, and one user points out related content can also be found on Discmaster, a searchable index of vintage CD-ROMs.

hackernews · rdmuser · Oct 4, 21:01 · [Discussion](https://news.ycombinator.com/item?id=49957812)

**Background**: Tippett Studio is an American visual effects and computer animation company founded in 1984 by animator Phil Tippett and his wife Jules Roman, known for work on over fifty films and for pioneering stop-motion and CGI techniques. In 2026, the Berkeley office closed after Tippett filed for Chapter 11 bankruptcy, though the Toronto location continues to operate. The Internet Archive, founded in 1996 by Brewster Kahle, is a non-profit digital library that provides free public access to digitized media, including software, audiovisual works, and websites.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Tippett_Studio">Tippett Studio</a></li>
<li><a href="https://en.wikipedia.org/wiki/Internet_Archive">Internet Archive</a></li>

</ul>
</details>

**Discussion**: Commenters strongly praise the preservation effort, with one calling the anonymous rescuer a 'hero' and another noting it is a shame that so much material never sees the light of day. Several users suggest Phil Tippett's name should be in the headline to give the archive the attention it deserves, and one points to Discmaster as a related resource.

**Tags**: `#digital-preservation`, `#animation`, `#archives`, `#tippett-studios`, `#internet-archive`

---

<a id="item-5"></a>
## [Zarf's Blog Post on Infidel and Memory Corruption Sparks HN Discussion](https://blog.zarfhome.com/2026/10/infidel-goes-wild) ⭐️ 7.0/10

Andrew Plotkin (Zarf) published a blog post titled 'Infidel goes wild' that explores the intersection of interactive fiction and memory corruption, using the classic Infocom game Infidel as a case study. The post sparked a nostalgic and technically insightful discussion on Hacker News, earning 121 points and 17 comments. This post highlights the enduring relevance of interactive fiction and retro computing, showing how classic games can teach modern lessons about memory safety and debugging. It also underscores the value of personal technical writing in fostering community engagement and knowledge sharing. The discussion references the Digital Antiquarian's history of computer games, the rec.arts.int-fiction newsgroup, and the ubiquity of memory-trashing bugs in 1980s game development. Commenters also praised Zarf's ongoing contributions to the interactive fiction community.

hackernews · tobr · Oct 3, 12:19 · [Discussion](https://news.ycombinator.com/item?id=49943637)

**Background**: Interactive fiction (IF) is a genre of software where players use text commands to control characters and influence a simulated environment, often referred to as text adventures. Infidel is a 1983 interactive fiction game published by Infocom, written by Michael Berlyn and Patricia Fogleman, and is known for its controversial ending. Memory corruption occurs when a program unintentionally modifies memory, often due to bugs like buffer overflows, leading to crashes or bizarre behavior.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Interactive_fiction">Interactive fiction</a></li>
<li><a href="https://en.wikipedia.org/wiki/Memory_corruption">Memory corruption</a></li>
<li><a href="https://en.wikipedia.org/wiki/Infidel_(video_game)">Infidel (video game) - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters expressed nostalgia for the interactive fiction community and shared personal anecdotes about memory bugs, with one noting that every 1980s game programmer likely shipped a memory-trashing bug. Another commenter asked for advice on writing technically interesting posts based on personal experience, reflecting appreciation for Zarf's style.

**Tags**: `#interactive fiction`, `#retro computing`, `#memory corruption`, `#game development`, `#Hacker News`

---

<a id="item-6"></a>
## [Browser-native VB6 IDE recreates classic Visual Basic 6](https://wieslawsoltes.github.io/VB6/) ⭐️ 7.0/10

A developer has released a browser-native recreation of the classic Visual Basic 6 IDE, hosted at wieslawsoltes.github.io/VB6/, which can even "compile" an app to a standalone HTML file. The project drew 165 points and 62 comments on Hacker News, with users praising its functionality while noting visual imperfections in the UI. The project revives the rapid application development (RAD) workflow that made VB6 hugely popular in the 1990s, and commenters see it as a possible blueprint for AI-assisted coding agents that could bring back a similar drag-and-drop, property-driven experience. It also highlights ongoing interest in browser-native IDEs that run entirely client-side without installation. The IDE runs entirely in the browser and can export a VB6-style app as an HTML file, though commenters noted the UI looks noisy and distorted, with crooked window buttons and missing bevel edges. One commenter speculated the implementation was AI-generated, which may explain the pixel-level inaccuracies.

hackernews · wiso · Oct 4, 18:49 · [Discussion](https://news.ycombinator.com/item?id=49956681)

**Background**: Visual Basic 6 (VB6), released by Microsoft in 1998, was the last version of the classic Visual Basic product line and remains widely used in businesses for building native 32-bit Windows applications. Its drag-and-drop form designer and property grid made it a defining example of rapid application development (RAD). Browser-native IDEs, by contrast, run entirely in the web browser using technologies like WebContainers, avoiding local installation.

<details><summary>References</summary>
<ul>
<li><a href="https://winworldpc.com/product/microsoft-visual-bas/60">WinWorld: Microsoft Visual Basic 6 .0</a></li>
<li><a href="https://latticeide.com/">Lattice - The First Browser-Native Multi-Agent IDE</a></li>
<li><a href="https://stackoverflow.com/questions/8921324/need-to-convert-vb-6-forms-to-html-forms">Need to convert VB 6 forms to Html forms - Stack Overflow</a></li>

</ul>
</details>

**Discussion**: Commenters were largely nostalgic and positive: badsectoracula praised the ability to "compile" to HTML but criticized the noisy, distorted visuals, while waldrews called the property grid "the greatest general purpose UI of all time." jit_tech wondered whether AI coding agents could bring back VB6's compressed development loop, and others shared memories of learning to program with VB6.

**Tags**: `#visual-basic`, `#ide`, `#browser`, `#retro-computing`, `#rad`

---

<a id="item-7"></a>
## [RemoveMacAI script strips Apple Intelligence from macOS 27 to reclaim disk space](https://github.com/omlahore/RemoveMacAI) ⭐️ 7.0/10

A GitHub project called RemoveMacAI (omlahore/RemoveMacAI) offers a single command to turn off Apple Intelligence on macOS 27 and delete its downloaded on-device AI models, with the change described as fully reversible. The tool emerged because macOS 27 no longer provides a single system-wide switch to disable the feature set, and the AI model files reportedly remain on disk even after users turn off individual Apple Intelligence features. The project taps into growing user frustration that Apple's AI features consume disk space and cannot be easily disabled, echoing the de-crufting culture long associated with Windows. With 506 points and 317 comments on Hacker News, the discussion highlights broader concerns about Apple's product strategy, user control, and the small default SSDs on many Macs. The script's pitch is one command that disables Apple Intelligence, removes its downloaded models, and prevents macOS from re-downloading them, and it is advertised as fully reversible. A separate project, minagishl/apple-intelligence-remover, offers similar functionality, indicating that reclaiming AI-related storage has become a recurring need on macOS.

hackernews · privacyisntdead · Oct 4, 19:42 · [Discussion](https://news.ycombinator.com/item?id=49957116)

**Background**: macOS 27, also known as Golden Gate, is the twenty-third major release of Apple's Mac operating system, announced at WWDC 2026 and released on September 14, 2026; it is the first macOS version to run exclusively on Apple silicon. Apple Intelligence is Apple's suite of AI features integrated across apps, powered in part by on-device models that occupy local storage. Because macOS 27 lacks a single global toggle for these features, users have turned to third-party scripts to disable them and free up space.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/omlahore/RemoveMacAI">GitHub - omlahore/RemoveMacAI: Turn off Apple Intelligence on ...</a></li>
<li><a href="https://www.explainx.ai/blog/removemacai-turn-off-apple-intelligence-macos-27-reclaim-disk-2026">Turn Off Apple Intelligence on macOS 27 (RemoveMacAI ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/MacOs_Golden_Gate">macOS Golden Gate - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters compared the situation to the de-crufting long required on Windows, with one calling it 'on the level of O&O ShutUp10' and questioning Apple's product strategy. Others complained that iOS no longer offers a simple toggle to disable AI features, unlike competitors such as Microsoft and Firefox, while one argued the real problem is Apple's small default SSDs rather than the AI itself.

**Tags**: `#macOS`, `#Apple Intelligence`, `#privacy`, `#disk space`, `#de-crufting`

---

<a id="item-8"></a>
## [Improper Redaction Exposes Google Data Center Water and Power Use](https://www.1011now.com/2026/09/30/more-questions-than-answers-about-lincolns-google-data-center-water-electricity-usage/) ⭐️ 7.0/10

An improperly redacted public document revealed that Google's data center in Lincoln, Nebraska, uses roughly 13.3 million gallons of water per year, along with its electricity consumption figures. The disclosure came to light because the redaction was done incorrectly, allowing the hidden numbers to be recovered. The incident highlights a growing transparency problem around data center resource consumption, a topic of intense public interest as AI infrastructure expands. It also shows how flawed redaction practices can force disclosure of information that companies and municipalities may have preferred to keep private. The Lincoln facility's 13.3 million gallons works out to about 40.8 acre-feet of water, a small figure compared with local agriculture; the same article notes another data center that used more than 500 million gallons. Improper redaction typically occurs when black boxes or highlighting are drawn over text rather than the underlying content being permanently removed, leaving it recoverable.

hackernews · sensanaty · Oct 4, 19:37 · [Discussion](https://news.ycombinator.com/item?id=49957068)

**Background**: Data centers consume large amounts of water, mainly for cooling, and electricity for servers and cooling systems; researchers estimate U.S. data centers used about 176 TWh in 2023, roughly 4.4% of national electricity. Redaction is the practice of obscuring sensitive information before a document is publicly released, and failures to do it properly have repeatedly exposed confidential details in legal and government files. Because data center water and power use is often not publicly reported, journalists and researchers frequently rely on such documents to estimate local impacts.

<details><summary>References</summary>
<ul>
<li><a href="https://caseguard.com/articles/embarrassing-redaction-failures-how-to-prevent-them/">Common Redaction Mistakes: Real-World Examples & How You Can ...</a></li>
<li><a href="https://www.eesi.org/articles/view/data-centers-and-water-consumption">Data Centers and Water Consumption | Article | EESI</a></li>
<li><a href="https://www.congress.gov/crs-product/R48646">Data Centers and Their Energy Consumption: Frequently Asked ...</a></li>

</ul>
</details>

**Discussion**: Commenters largely pushed back on alarm over the water figure, noting that 13.3 million gallons is trivial next to the roughly 390 million gallons used annually by an average Nebraska farm. Some argued the real debate should be about whether society wants AI data centers at all, rather than fixating on secondary costs like water and power, while others pointed to a separate data center that used over 500 million gallons as a more meaningful comparison.

**Tags**: `#Google`, `#data centers`, `#water usage`, `#transparency`, `#HN discussion`

---

<a id="item-9"></a>
## [Self-hosted HTTP tunnels using SSH and Nginx](https://vincent.bernat.ch/en/blog/2026-http-over-ssh) ⭐️ 7.0/10

A blog post by Vincent Bernat explains how to build self-hosted HTTP tunnels using SSH remote port forwarding combined with Nginx as a reverse proxy, offering an alternative to commercial tunneling services like ngrok or Cloudflare Tunnel. The post sparked a Hacker News discussion with 118 points and 30 comments, where developers shared related open-source projects such as sish, iroh-webproxy, and DNTLS. This matters because it gives self-hosting and DevOps practitioners a way to expose local services to the internet without relying on third-party SaaS providers, addressing growing concerns about vendor lock-in, privacy, and the blurred definition of 'self-hosted'. The community discussion highlights a broader trend toward fully open, intermediary-free tunneling solutions. The approach uses SSH remote port forwarding (reverse tunneling) to connect a local service to a remote server, with Nginx acting as a reverse proxy to route incoming HTTP requests to the forwarded port. However, commenters warned that the initial Nginx configuration could allow attackers to direct traffic to any arbitrary localhost port, potentially bypassing firewall rules, so careful security hardening is required.

hackernews · renehsz · Oct 4, 22:25 · [Discussion](https://news.ycombinator.com/item?id=49958569)

**Background**: HTTP tunneling creates a network link between two computers through a proxy server, allowing traffic to pass through firewalls, NATs, and other restrictions. SSH remote port forwarding, also known as reverse SSH tunneling, lets a local machine expose a service to a remote server by initiating an encrypted connection outward. Nginx is a popular open-source web server and reverse proxy that can route incoming requests to backend services, making it a natural fit for managing tunneled traffic.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HTTP_tunnel_(software)">HTTP tunnel (software)</a></li>
<li><a href="https://www.ssh.com/academy/ssh/tunneling-example">SSH Tunneling: Client Command & Server Configuration</a></li>
<li><a href="https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/">NGINX Reverse Proxy</a></li>

</ul>
</details>

**Discussion**: Commenters shared several open-source alternatives: antoniomika pointed to sish, an MIT-licensed SSH tunneling server with automatic TLS and a web console; toomim expressed excitement about iroh-webproxy for HTTPS over iroh with no port forwarding or public IP; and aliasxneo discussed DNTLS as a way to avoid intermediaries entirely. jamiesonbecker criticized the article's approach as overly complicated and insecure, warning that the Nginx configuration could let attackers probe arbitrary localhost ports and bypass firewalls.

**Tags**: `#self-hosting`, `#ssh`, `#nginx`, `#http-tunnels`, `#networking`

---

<a id="item-10"></a>
## [Irkutsk lab worker dies from plague, nearly 200 contacts monitored](https://www.themoscowtimes.com/2026/10/02/nearly-200-people-under-observation-after-irkutsk-lab-worker-dies-from-plague-a93857) ⭐️ 7.0/10

A worker at the Irkutsk Antiplague Institute in Siberia died from plague after reportedly breaking a test tube containing live bacteria while collecting samples, and as of October 2, 2026, at least 197 contacts have been identified, with 189 hospitalized for observation across three facilities. This laboratory-acquired infection highlights the real-world risks of handling dangerous pathogens and raises urgent questions about biosafety protocols, emergency response, and whether the benefits of plague research justify the potential public health threat. The 197 contacts include community and hospital exposures, with 114 in one medical facility, 63 in another, and 12 at the Anti-Plague Institute; as of October 2, 2026, none have shown signs of illness, and it remains unclear whether the strain involved is resistant to standard antibiotics like doxycycline or ciprofloxacin.

hackernews · ericmay · Oct 5, 02:31 · [Discussion](https://news.ycombinator.com/item?id=49960084)

**Background**: The Irkutsk Antiplague Institute is part of Russia's anti-plague system, which monitors and researches Yersinia pestis, the bacterium that causes plague. Plague is a severe infectious disease historically responsible for pandemics, and laboratory work with live bacteria requires strict biosafety and biosecurity measures to prevent accidental infections.

<details><summary>References</summary>
<ul>
<li><a href="https://beaconbio.org/en/report/?reportid=d9b0fb86-88c3-4883-9433-79f9caccb275&filtersOpen=false">RFI: Fatal laboratory-acquired infection in Irkutsk Region ...</a></li>
<li><a href="https://alexwasburne.substack.com/p/the-irkutsk-plague">The Irkutsk Plague - by Alex Washburne, PhD</a></li>
<li><a href="https://www.cdc.gov/safe-labs/php/biorisk-management/index.html">Biorisk Management | Safe Labs Portal | CDC</a></li>

</ul>
</details>

**Discussion**: Commenters expressed concern about lab safety protocols and questioned whether dangerous pathogen research is worth the risk, with some noting the coincidental timing with a recent book about an accidental plague release. Others highlighted the governor's emergency management background and asked whether the strain might be antibiotic-resistant.

**Tags**: `#biosecurity`, `#public health`, `#lab safety`, `#plague`, `#risk assessment`

---

<a id="item-11"></a>
## [ICBA Sues OCC Over Crypto's 'Side Door' Into Banking](https://decrypt.co/380017/banking-group-sues-block-crypto-side-door-banking) ⭐️ 7.0/10

The Independent Community Bankers of America (ICBA) has filed a lawsuit against the Office of the Comptroller of the Currency (OCC) to block the agency from granting national trust charters to crypto firms, arguing these charters create an unregulated 'side door' into the banking system. The ICBA contends that Congress never intended the national trust charter to serve as a backdoor for crypto companies seeking the credibility of a federal bank charter without meeting the same obligations as traditional banks. This lawsuit could reshape how crypto firms access the U.S. banking system, potentially halting or slowing the trend of crypto companies obtaining federal trust charters for custody and stablecoin operations. The outcome will have significant implications for the broader crypto industry's integration with traditional finance and could set a precedent for how federal banking regulators oversee digital asset firms. The ICBA argues that national trust charters allow crypto firms to obtain a federal bank charter without being subject to Community Reinvestment Act obligations, consolidated supervision, capital and liquidity standards, and FDIC insurance that apply to insured depository institutions. The OCC has recently granted conditional approval to crypto firms such as World Liberty Financial to organize national trust banks, signaling a growing trend that the ICBA seeks to reverse.

rss · Decrypt · Oct 4, 16:01

**Background**: The OCC national trust charter is a federal banking license that does not permit taking deposits or lending, historically used by a small number of corporate trustees. In 2025–2026, it became a popular pathway for crypto and fintech firms to enter the U.S. banking system for custody and stablecoin issuance under federal supervision. The ICBA is a trade group representing approximately 5,000 small and mid-sized U.S. community banks, founded in 1930, and has long advocated for policies that protect community banks from competitive disadvantages.

<details><summary>References</summary>
<ul>
<li><a href="https://wiki.private.law/en/occ-trust-charter">OCC National Trust Charter : Bank Without Deposits</a></li>
<li><a href="https://en.wikipedia.org/wiki/Independent_Community_Bankers_of_America">Independent Community Bankers of America</a></li>
<li><a href="https://www.cutoday.info/Fresh-Today/ICBA-Takes-OCC-To-Court-Over-Side-Door-Into-Banking-System">ICBA Takes OCC To Court Over ‘Side Door’ Into Banking System</a></li>

</ul>
</details>

**Tags**: `#crypto`, `#banking`, `#regulation`, `#OCC`, `#lawsuit`

---

<a id="item-12"></a>
## [Zcash's 25-second blocks go live on public testnet ahead of schedule](https://www.coindesk.com/tech/2026/10/05/zcash-s-25-second-blocks-go-live-on-public-testnet-ahead-of-schedule) ⭐️ 6.0/10

Zcash activated its NU7 upgrade on a public test network, cutting the targeted block time to 25 seconds from 75 seconds, ahead of a planned Nov. 5 mainnet rollout. Faster block times mean quicker transaction confirmations and improved throughput, which could make Zcash more practical for everyday payments and strengthen its competitiveness among privacy-focused and Layer 1 blockchains. The change is currently limited to the public testnet rather than mainnet, and the mainnet rollout is targeted for Nov. 5; block time is a key parameter influencing network throughput and scalability.

rss · CoinDesk · Oct 5, 04:41

**Background**: Zcash is a privacy-focused cryptocurrency that uses zero-knowledge proofs to shield transaction details. Block time is the average interval between consecutive blocks being added to a blockchain, and it directly affects how fast transactions confirm and how many transactions a network can process. Reducing block time is a common scaling strategy for Layer 1 networks seeking better user experience.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/10/05/zcash-s-25-second-blocks-go-live-on-public-testnet-ahead-of-schedule">Zcash’s 25-second blocks go live on public testnet ahead of ...</a></li>
<li><a href="https://fastercapital.com/content/Block-Time--Block-Time-Breakdown--The-Pulse-of-Layer-1-Blockchain-Networks.html">Block Time : Block Time Breakdown: The Pulse of... - FasterCapital</a></li>
<li><a href="https://www.princewill.io/what-is-block-time-and-why-it-matters/">What Is Block Time and Why It Matters</a></li>

</ul>
</details>

**Tags**: `#Zcash`, `#blockchain`, `#cryptocurrency`, `#scalability`, `#testnet`

---

<a id="item-13"></a>
## [BlackRock Signals How Tokenization Could Reshape Investment Portfolios](https://www.coindesk.com/business/2026/10/03/blackrock-offers-a-glimpse-of-how-tokenization-may-change-your-investment-portfolio) ⭐️ 6.0/10

BlackRock has offered new insight into how tokenization could transform investment portfolios, signaling growing institutional interest in blockchain-based assets. The report frames tokenization as a practical path toward more efficient, accessible markets rather than a purely experimental technology. As the world's largest asset manager, BlackRock's endorsement carries weight across traditional finance and could accelerate adoption of tokenized real-world assets by other institutions. If tokenization scales, it could change how investors access, trade, and hold assets such as bonds, funds, and real estate. Tokenization converts traditional assets into digital tokens that can be traded on blockchains, offering benefits such as fractional ownership, increased liquidity, and greater accessibility. However, it also carries risks including regulatory uncertainty, technological complexity, and security concerns that institutions must address.

rss · CoinDesk · Oct 3, 13:00

**Background**: Asset tokenization is the process of converting ownership of traditional assets like stocks, bonds, real estate, or commodities into blockchain-based digital tokens. BlackRock entered the tokenization race in March 2024 with a tokenized fund on the Ethereum network, following similar moves by Citi, Franklin Templeton, and JPMorgan. The firm has previously described tokenization as a multi-trillion-dollar opportunity for real-world assets.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/markets/2024/03/20/blackrock-enters-asset-tokenization-race-with-new-fund-on-the-ethereum-network">BlackRock Enters Asset Tokenization Race With New Fund on the...</a></li>
<li><a href="https://www.forbes.com/sites/nataliakarayaneva/2024/03/21/blackrocks-10-trillion-tokenization-vision-the-future-of-real-world-assets/">BlackRock 's $10 Trillion Tokenization Vision: The Future Of Real...</a></li>
<li><a href="https://www.britannica.com/money/real-world-asset-tokenization">What Is Asset Tokenization? Meaning, Examples, Pros, & Cons ...</a></li>

</ul>
</details>

**Tags**: `#tokenization`, `#blockchain`, `#investing`, `#fintech`, `#BlackRock`

---

<a id="item-14"></a>
## [Trump Taps Jay Clayton, SEC Chair Who Sued Ripple, to Lead AI Push](https://decrypt.co/380019/trump-jay-clayton-sec-ripple-ai-push-super-intelligence) ⭐️ 6.0/10

President Trump named a new 'Super Intelligence Force' to coordinate federal AI policy, appointing Director of National Intelligence Jay Clayton to lead it. Clayton, who chaired the SEC from 2017 to 2020, oversaw the agency's December 2020 lawsuit against Ripple Labs and its executives. This appointment signals that the Trump administration wants a single powerful coordinator for AI policy, and Clayton's background in financial regulation and crypto enforcement could shape how AI oversight intersects with digital assets. It may also reassure or alarm the crypto industry depending on how aggressively the new force approaches AI-related financial technologies. Clayton is expected to also be named AI czar, according to NBC News, and the Super Intelligence Force was created just weeks after Trump announced a separate 'AI Force.' The announcement comes amid growing concern about AI risks, though the force's specific mandate and authority remain unclear.

rss · Decrypt · Oct 4, 17:01

**Background**: The SEC sued Ripple Labs in December 2020, alleging that its sale of XRP constituted an unregistered securities offering; the case ended with a partial ruling in 2023 and a settlement in 2024. Jay Clayton chaired the SEC from May 2017 to 2020 and was later confirmed as Director of National Intelligence. The 'Super Intelligence Force' is a new federal task force intended to coordinate AI policy across the U.S. government.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nbcnews.com/politics/trump-administration/trump-announces-members-ai-task-force-rcna601494">Trump announces members of ‘ Super Intelligence Force ’ to...</a></li>
<li><a href="https://www.sec.gov/enforcement-litigation/litigation-releases/lr-26306">SEC.gov | Ripple Labs, Inc., Bradley Garlinghouse, and ...</a></li>
<li><a href="https://www.sec.gov/about/sec-commissioners/sec-historical-summary-chairmen-commissioners/jay-clayton">SEC .gov | Jay Clayton</a></li>

</ul>
</details>

**Tags**: `#AI policy`, `#regulation`, `#cryptocurrency`, `#government`, `#Trump administration`

---

<a id="item-15"></a>
## [Near Intents Recovers $3.8M After 48-Hour Ultimatum to Attacker](https://decrypt.co/380014/near-intents-recovers-3-8-million-after-48-hour-ultimatum) ⭐️ 6.0/10

Near Intents announced that roughly $3.8 million drained in a Thursday exploit was returned in full, one day after the team publicly said it had identified the attacker and gave them 48 hours to return the funds. The protocol had paused its cross-chain services following the incident. This is a rare case of a DeFi exploit ending in full recovery, showing that on-chain attribution and public pressure can sometimes succeed where purely technical defenses fail. It also highlights the ongoing wave of crypto hacks in 2026 and the growing use of negotiation as a recovery tactic. The exploit stemmed from a bug involving Near Intents' Omni deposit and withdrawal infrastructure and the Near Intents smart contract, which led the team to pause services. The attacker returned all stolen assets a day after the ultimatum, though no technical fix details have been disclosed.

rss · Decrypt · Oct 4, 13:01

**Background**: Near Intents is a multichain transaction protocol built on the NEAR blockchain that lets users specify what they want to do—such as swapping tokens across chains—and lets third-party solvers compete to fulfill the request. It uses Chain Signatures and a solver network to enable one-click cross-chain swaps without users managing bridges themselves. The incident occurred during a rough year for crypto security, with numerous exploits targeting DeFi protocols.

<details><summary>References</summary>
<ul>
<li><a href="https://www.coindesk.com/tech/2026/10/01/near-intents-hit-by-usd3-8-million-exploit-as-crypto-s-rough-year-of-hacks-continues">NEAR Intents hit by $3.8M exploit, pauses cross-chain ...</a></li>
<li><a href="https://coincodex.com/article/92975/near-intents-hit-by-38m-security-incident-services-halted/">NEAR Intents Hit by $3.8M Security Incident, Services Halted</a></li>
<li><a href="https://www.near.org/intents">intents | NEAR</a></li>

</ul>
</details>

**Tags**: `#cryptocurrency`, `#security`, `#exploit`, `#DeFi`, `#blockchain`

---

<a id="item-16"></a>
## [Chainalysis Uses AI to Trace $387M Bitget Hack to North Korea](https://decrypt.co/380005/chainalysis-ai-87m-bitget-hack-north-korea) ⭐️ 6.0/10

Chainalysis announced that it used its in-house AI tools to trace the $387 million Bitget exchange hack, which occurred on September 24, back to North Korea, pushing the country's total 2026 crypto theft haul past $1 billion. The firm detailed how it tracked the stolen funds across four different blockchains in a race against the attackers. This case highlights how AI is becoming a critical tool in blockchain forensics, enabling faster tracing of stolen funds across multiple chains and strengthening attribution to state-sponsored actors like North Korea. It also underscores the growing scale of North Korean crypto theft, which now exceeds $1 billion in 2026 alone, raising pressure on exchanges and regulators to bolster security. The hack occurred on September 24 and involved funds moved across four blockchains, which Chainalysis traced using its proprietary AI agents. Bitget CEO Gracy Chen has previously expressed doubt about full recovery, noting that only a small percentage of funds are typically frozen or recovered in such breaches.

rss · Decrypt · Oct 3, 17:01

**Background**: Chainalysis is a blockchain data platform that combines on-chain data with AI to help government agencies, crypto businesses, and financial institutions investigate illicit activity. North Korea has been linked to numerous high-profile crypto hacks, including the 2019 UpBit theft ($41M) and the 2021 KuCoin breach ($275M), as the regime uses stolen funds to finance its weapons programs. The Bitget hack is considered the largest crypto theft of 2026 so far.

<details><summary>References</summary>
<ul>
<li><a href="https://www.chainalysis.com/blockchain-intelligence/">Blockchain Intelligence - Chainalysis</a></li>
<li><a href="https://en.wikipedia.org/wiki/Bitget">Bitget - Wikipedia</a></li>
<li><a href="https://www.euronews.com/2026/09/28/north-korean-hackers-suspected-in-3328m-crypto-heist-as-it-leads-global-hacks">North Korean hackers suspected in €332.8m crypto heist... | Euronews</a></li>

</ul>
</details>

**Tags**: `#AI`, `#blockchain forensics`, `#cybersecurity`, `#North Korea`, `#cryptocurrency`

---