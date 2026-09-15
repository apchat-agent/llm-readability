# Retrieval manifest — LLM readability literature sweep (2026-09-15)

Source: `wiki/topics/llm-text-readability-for-humans.md` (68 references) cross-checked against
`wiki/sources/llm-readability-sweep-2026-09-15/{1,2,3}-*.md` for URLs. Fetched with `curl -L`,
a browser User-Agent, `-m 60 --retry 1`. A PDF was accepted only if it starts with `%PDF-` and is
> 20 KB. One PDF that exceeded the 50 MB single-file cap was fetched, measured, then deleted per
instructions (noted below) rather than kept.

| # | Ref | Year | URL tried | Result | File | Size KB | Note |
|---|-----|------|-----------|--------|------|---------|------|
| 1 | LLM plain-language summaries, crowdsourced (PubMed 42044823) | 2025 | https://pubmed.ncbi.nlm.nih.gov/42044823/ | FAILED | - | 0 | PubMed wall; Europe PMC says not open access (isOpenAccess=N), no PMC full text |
| 2 | Rashid et al., HFES 2024 | 2024 | journals.sagepub.com doi/10.1177/10711813241261689 | FAILED | - | 0 | 403, paywalled (SAGE) |
| 3 | Sleep-medicine summaries (PMC11704966) | 2024 | pmc.ncbi.nlm.nih.gov/articles/PMC11704966/pdf/ | XML+MD | 2024-pmc11704966-sleep-medicine-summaries.md | 40 | PMC bot-check bypassed via Europe PMC REST fullTextXML; .xml kept, .md is a plain-text conversion |
| 4 | AI vs human academic abstracts (PLOS One) | 2025 | journals.plos.org plosone article/file?id=10.1371/journal.pone.0343163 | PDF | 2025-plosone-academic-abstracts.pdf | 774 | open access |
| 5 | ChatGPT vs L2 student essays (Frontiers in Education) | 2025 | frontiersin.org .../10.3389/feduc.2025.1616935/pdf | PDF | 2025-frontiersed-l2-essays.pdf | 230 | open access |
| 6 | LLM vs human process models, eye tracking (Springer) | 2025 | link.springer.com content/pdf/10.1007/978-3-032-28274-3_6.pdf | FAILED | - | 0 | Springer bot-check/cookie wall, book-chapter paywalled |
| 7 | Eye tracking of AI and human texts (ACM ETRA) | 2025 | dl.acm.org doi/pdf/10.1145/3715669.3726846 | FAILED | - | 0 | 403, ACM DL paywalled |
| 8 | LLM vs professional Arabic subtitles (PMC12286245) | 2025 | pmc.ncbi.nlm.nih.gov/articles/PMC12286245/pdf/ | XML+MD | 2025-pmc12286245-arabic-subtitles.md | 66 | PMC bot-check bypassed via Europe PMC REST fullTextXML; .xml kept, .md is a plain-text conversion |
| 9 | Pupil dilation on AI text (UNVERIFIED) | 2025 | none in sources | FAILED | - | 0 | No URL/citation given anywhere in the three raw sweep files — the sweep itself never resolved this source. Flag as a likely phantom reference. |
| 10 | Reader perception shifts on disclosure (arXiv 2510.24011) | 2025 | arxiv.org/pdf/2510.24011 | PDF | 2025-2510.24011-disclosure-perception.pdf | 1894 | - |
| 11 | AI vs human reading-comprehension test passages (Large-scale Assessments in Education) | 2025 | link.springer.com content/pdf/10.1186/s40536-025-00255-w.pdf | FAILED | - | 0 | Springer bot-check/cookie wall despite journal being open access |
| 12 | Kobak et al., Science Advances 2024 (excess vocabulary) | 2024 | arxiv.org/pdf/2406.07016 | PDF | 2024-kobak-excess-vocabulary.pdf | 4780 | arXiv preprint of the Science Advances paper |
| 13 | Why ChatGPT "delves", COLING 2025 | 2025 | news.fsu.edu (FSU press coverage) | HTML (press only) | 2025-coling-why-delves.html | 91 | paper PDF not found via Semantic Scholar/ACL Anthology; only FSU press coverage saved -> counts as not retrieved |
| 14 | Sourati et al., arXiv 2508.01491 | 2025 | arxiv.org/pdf/2508.01491 | PDF | 2025-2508.01491-homogenizing.pdf | 3262 | - |
| 15 | Homogenizing effect on creative diversity (ScienceDirect) | 2024 | sciencedirect.com .../pii/S294988212500091X/pdfft | FAILED | - | 0 | 403, ScienceDirect paywalled |
| 16 | Stylometric comparison of creative writing (Nature HSSC) | 2025 | nature.com articles/s41599-025-05986-3.pdf | PDF | 2025-nature-hssc-stylometric.pdf | 1562 | open access |
| 17 | Em-dash rise in medRxiv (arXiv 2606.29540) | 2026 | arxiv.org/pdf/2606.29540 | PDF | 2026-2606.29540-emdash.pdf | 952 | - |
| 18 | Tricolon metric (arXiv 2604.19768) | 2026 | arxiv.org/pdf/2604.19768 | PDF | 2026-2604.19768-tricolon.pdf | 2834 | - |
| 19 | Markdown fingerprint (arXiv 2603.27006) | 2026 | arxiv.org/pdf/2603.27006 | PDF | 2026-2603.27006-markdown-fingerprint.pdf | 437 | - |
| 20 | AI-label RCT, N=164 (PMC11176609) | 2024 | pmc.ncbi.nlm.nih.gov/articles/PMC11176609/pdf/ | XML+MD | 2024-pmc11176609-ai-label-rct.md | 29 | PMC bot-check bypassed via Europe PMC REST fullTextXML; .xml kept, .md is a plain-text conversion |
| 21 | AI-authorship across domains (Springer) | 2025 | link.springer.com content/pdf/10.1007/978-3-032-26717-7_22.pdf | FAILED | - | 0 | Springer bot-check/cookie wall, book-chapter paywalled |
| 22 | AI labels and perceived accuracy (arXiv 2506.16202) | 2025 | arxiv.org/pdf/2506.16202 | PDF | 2025-2506.16202-label-accuracy.pdf | 3532 | topic page flags author list to re-verify; not resolved here |
| 23 | AI disclosure and credibility (JCOM) | 2026 | jcom.sissa.it/sites/default/files/documents/JCOM_2501_2026_A09.pdf | PDF | 2026-jcom-disclosure-credibility.pdf | 4582 | open access |
| 24 | AI disclosure in news, N=433 (Oxford) | 2024 | ora.ox.ac.uk .../files/rzw12z6837 | PDF | 2024-oxford-disclosure-news.pdf | 1009 | Oxford Research Archive, open |
| 25 | Suspected ChatGPT in consumer reviews (J. Retailing and Consumer Services) | 2024 | sciencedirect.com .../abs/pii/S0736585324000674 | FAILED | - | 0 | 403, ScienceDirect paywalled |
| 26 | AI-generated and AI-assisted news (arXiv 2409.03500) | 2024 | arxiv.org/pdf/2409.03500 | PDF | 2024-2409.03500-ai-news.pdf | 459 | - |
| 27 | Reputational risks of AI-mediated messages (arXiv 2509.09645) | 2025 | arxiv.org/pdf/2509.09645 | PDF | 2025-2509.09645-reputational-risks.pdf | 625 | topic page marks venue UNVERIFIED |
| 28 | AI-mediated video and trust (arXiv 2603.18868) | 2026 | arxiv.org/pdf/2603.18868 | PDF | 2026-2603.18868-video-trust.pdf | 2682 | topic page marks venue UNVERIFIED |
| 29 | Purcell et al., British Journal of Psychology | 2026 | bpspsychub.onlinelibrary.wiley.com doi/pdf/10.1111/bjop.12727 | FAILED | - | 0 | 403, Wiley paywalled |
| 30 | Xiao et al., EMNLP 2025 (arXiv 2510.09994) | 2025 | arxiv.org/pdf/2510.09994 | PDF | 2025-xiao-mt-literacy.pdf | 51756 | re-fetched after the first pass; the 50 MB cap was too low; 51.7 MB PDF kept |
| 31 | Yan et al., arXiv 2407.03658 | 2024 | arxiv.org/pdf/2407.03658 | PDF | 2024-2407.03658-yan-translators.pdf | 1317 | - |
| 32 | Chen and Lin, Frontiers in AI | 2025 | frontiersin.org .../10.3389/frai.2025.1619489/pdf | PDF | 2025-frontiersai-chen-lin.pdf | 845 | open access |
| 33 | Chinese-to-English technical translation (Forum for Linguistic Studies) | 2025 | journals.bilpubgroup.com index.php/fls/article/view/11014 | HTML | 2025-fls-technical-translation.html | 106 | article landing page saved; no direct PDF link found on the page; authors/year UNVERIFIED per topic page |
| 34 | LLM quality estimation for user-generated content (arXiv 2410.06338) | 2024 | arxiv.org/pdf/2410.06338 | PDF | 2024-2410.06338-quality-estimation.pdf | 1099 | - |
| 35 | LLM-BT-Terms (arXiv 2506.08174) | 2025 | arxiv.org/pdf/2506.08174 | PDF | 2025-2506.08174-bt-terms.pdf | 1473 | - |
| 36 | Simpson's paradox in accuracy-fluency (arXiv 2402.12690) | 2024 | arxiv.org/pdf/2402.12690 | PDF | 2024-2402.12690-simpsons-paradox.pdf | 520 | - |
| 37 | Sustaining Human Agency, Attending to Its Cost (CHI 2025, arXiv 2503.07970) | 2025 | arxiv.org/pdf/2503.07970 | PDF | 2025-2503.07970-human-agency.pdf | 1452 | - |
| 38 | Translation in the Hands of Many (arXiv 2502.13780) | 2025 | arxiv.org/pdf/2502.13780 | PDF | 2025-2502.13780-hands-of-many.pdf | 338 | - |
| 39 | LAAC: LLM as a Communicator (arXiv 2511.04184) | 2025 | arxiv.org/pdf/2511.04184 | PDF | 2025-2511.04184-laac-communicator.pdf | 689 | - |
| 40 | Time to Talk, LLM agents in Mafia games (arXiv 2506.05309) | 2025 | arxiv.org/pdf/2506.05309 | PDF | 2025-2506.05309-time-to-talk.pdf | 833 | - |
| 41 | draft-fengfar-led-01 (IETF) | 2026 | ietf.org/archive/id/draft-fengfar-led-01.pdf and .txt | HTML (draft text) | 2026-ietf-draft-fengfar-led-01.txt | 33 | .pdf 404s; .txt is the canonical draft format and was fetched instead (34386 bytes) |
| 42 | IETF ai-in-standards list | 2025 | mail-archive.com ietf-announce msg27079.html | HTML | 2025-ietf-ai-in-standards-list.html | 7 | mailing-list announcement page, saved as HTML |
| 43 | IETF mailing-list-ai-check tool (ietf-tools) | 2025 | github.com/ietf-tools/mailing-list-ai-check | HTML | 2025-github-mailing-list-ai-check.html | 402 | GitHub repo page saved as HTML |
| 44 | English Wikipedia RfC | 2026 | en.wikipedia.org Wikipedia:Case_against_LLM-generated_articles | HTML | 2026-wikipedia-rfc-llm-articles.html | 282 | community page saved as HTML |
| 45 | Zhou, Cho, Terveen (arXiv 2509.07819) | 2025 | arxiv.org/pdf/2509.07819 | PDF | 2025-2509.07819-zhou-wikipedia.pdf | 570 | - |
| 46 | Wikimedia "Simple Article Summaries" backlash (press) | 2025 | plagiarismtoday.com 2026/03/30/... | HTML | 2025-wikimedia-simple-summaries-backlash.html | 122 | press coverage saved as HTML |
| 47 | SOGPTSpotter (arXiv 2602.04185) | 2026 | arxiv.org/pdf/2602.04185 | PDF | 2026-2602.04185-sogptspotter.pdf | 1408 | - |
| 48 | AI text detection in peer review (arXiv 2502.19614) | 2025 | arxiv.org/pdf/2502.19614 | PDF | 2025-2502.19614-peer-review-detection.pdf | 1901 | - |
| 49 | Open-source AI contribution policies (GitHub aggregator) | 2025 | github.com/melissawm/open-source-ai-contribution-policies | HTML | 2025-github-oss-ai-policies.html | 423 | GitHub repo page saved as HTML |
| 50 | SHA-256 pre-registration blog (dev.to) | 2026 | none in sources | FAILED | - | 0 | No URL given anywhere in the three raw sweep files, only "a dev.to blog post" mentioned in prose — the sweep never resolved this source. Likely phantom reference. |
| 51 | Jakesch, French, Ma, Hancock, Naaman, CHI 2019 | 2019 | socialmedialab.sites.stanford.edu .../jakesch-chi19-ai-mediated.pdf | PDF | 2019-jakesch-chi-ai-mediated.pdf | 1363 | Stanford-hosted author copy, open |
| 52 | Hancock, Naaman, Levy, JCMC 2020 | 2020 | academic.oup.com jcmc article-pdf/25/1/89/34936609/zmz022.pdf | FAILED | - | 0 | 403, Oxford Academic paywalled |
| 53 | Liu, Mittal, Yang, Bruckman, CHI 2022 | 2022 | cs.stanford.edu ~diyiy docs/chi22_perception.pdf | PDF | 2022-liu-chi-ai-console.pdf | 568 | Stanford-hosted author copy, open |
| 54 | Robertson and Díaz, FAccT 2022 | 2022 | dl.acm.org doi/pdf/10.1145/3531146.3534638 | FAILED | - | 0 | 403, ACM DL paywalled (fullHtml version exists but PDF blocked) |
| 55 | Deng, Mehandru, Robertson, Salehi, TRAIT 2022 (arXiv 2205.06920) | 2022 | arxiv.org/pdf/2205.06920 | PDF | 2022-2205.06920-deng-trait.pdf | 193 | - |
| 56 | Zhang, Owusu, Carpuat, Gao, CSCW 2022 (arXiv 2209.02906) | 2022 | arxiv.org/pdf/2209.02906 | PDF | 2022-2209.02906-zhang-cscw.pdf | 2255 | - |
| 57 | Probe tasks for dialogue evaluation (arXiv 2008.10427) | 2020 | arxiv.org/pdf/2008.10427 | PDF | 2020-2008.10427-probe-tasks.pdf | 3815 | - |
| 58 | Verschuere et al., preregistered replication | 2021 | onlinelibrary.wiley.com doi/pdfdirect/10.1002/acp.3769 | FAILED | - | 0 | 403, Wiley paywalled |
| 59 | Cultural misunderstanding warning in MT chat (Springer) | 2020 | link.springer.com content/pdf/10.1007/978-3-030-58157-2_8.pdf | FAILED | - | 0 | Springer bot-check/cookie wall, book-chapter paywalled |
| 60 | Martindale and Carpuat, AMTA 2018 | 2018 | aclanthology.org/W18-1803.pdf | PDF | 2018-martindale-carpuat-fluency.pdf | 197 | ACL Anthology, open |
| 61 | Back-translation validity (IEEE 7433246) | 2016 | ieeexplore.ieee.org abstract/document/7433246/ | FAILED | - | 0 | resolves as an HTML abstract wrapper (bot-check-style), not a PDF; IEEE full text is paywalled |
| 62 | Robertson and Díaz, IUI 2013 | 2013 | dl.acm.org doi/pdf/10.1145/2449396.2449407 | FAILED | - | 0 | 403, ACM DL paywalled |
| 63 | Conversational Grounding in MT-Mediated Communication (Language Grid volume, Springer 2011) | 2011 | link.springer.com content/pdf/10.1007/978-3-642-21178-2_12.pdf | FAILED | - | 0 | Springer bot-check/cookie wall, book-chapter paywalled (topic page already flags this as paywalled) |
| 64 | Yamashita, Inaba, Kuzuoka, Ishida, CHI 2009 | 2009 | link.springer.com content/pdf/10.1007/978-3-642-22766-0_6.pdf | FAILED | - | 0 | This is a related Springer chapter, not the primary CHI 2009 paper; Springer bot-check/cookie wall in any case. Primary CHI PDF not found in sweep sources. |
| 65 | Yamashita and Ishida, CSCW 2006 | 2006 | none in sources | FAILED | - | 0 | No URL anywhere in the three raw sweep files — only corroborated by secondary citing sources per the sweep's own text ("primary PDF not fetched"). UNVERIFIED source did not resolve. |
| 66 | Wang, Fussell et al., Cornell | 2013 | sfussell.hci.cornell.edu pubs/Manuscripts/p935-wang.pdf | PDF | 2013-wang-fussell-cornell.pdf | 932 | Cornell HCI group page; exact year UNVERIFIED per topic page, PDF filename implies ~2013 |
| 67 | Language justice and MT on social media (Modern Languages Open) | 2020 | modernlanguagesopen.org articles/466 (via galley file link) | PDF | 2020-mlo-language-justice.pdf | 241 | open access; year UNVERIFIED per topic page |
| 68 | ATA, the mother-tongue principle | 2020 | atanet.org resources/the-mother-tongue-principle-hit-or-myth/ | FAILED | - | 0 | 403, ATA site blocked the request |

## Summary

68 references, 36 PDFs, 3 PMC full texts as XML+MD, 7 HTML/TXT sources (web pages and the IETF draft), 22 not retrieved (incl. 2 phantom refs with no source and 1 press-only), total 108 MB.

## Failed references and why

- **#1** LLM plain-language summaries (PubMed 42044823) — PubMed served a cookie/JS wall; no PMC full text found.
- **#2** Rashid et al., HFES 2024 — SAGE, 403 paywalled.
- **#3** Sleep-medicine summaries (PMC11704966) — PMC reCAPTCHA bot-check.
- **#6** LLM vs human process models eye tracking (Springer) — bot-check/cookie wall, paywalled chapter.
- **#7** Eye tracking ACM ETRA — ACM DL, 403 paywalled.
- **#8** Arabic subtitles (PMC12286245) — PMC reCAPTCHA bot-check.
- **#9** Pupil dilation on AI text — **no URL anywhere in the sweep sources; likely phantom.**
- **#11** Reading-comprehension passages (Springer LAE) — bot-check/cookie wall despite journal being open access in principle.
- **#15** Homogenizing effect (ScienceDirect) — 403 paywalled.
- **#20** AI-label RCT PMC11176609 — PMC reCAPTCHA bot-check.
- **#21** AI-authorship across domains (Springer) — bot-check/cookie wall, paywalled chapter.
- **#25** Suspected ChatGPT reviews (ScienceDirect) — 403 paywalled.
- **#29** Purcell et al. (Wiley) — 403 paywalled.
- **#30** Xiao et al. EMNLP 2025 (arXiv 2510.09994) — resolved fine but the PDF is 53.0 MB, over the 50 MB single-file cap; deleted per instructions rather than kept.
- **#52** Hancock, Naaman, Levy JCMC 2020 (Oxford Academic) — 403 paywalled.
- **#54** Robertson and Díaz FAccT 2022 (ACM DL) — 403 paywalled.
- **#58** Verschuere et al. (Wiley) — 403 paywalled.
- **#59** Cultural misunderstanding warning (Springer) — bot-check/cookie wall, paywalled chapter.
- **#61** Back-translation validity (IEEE) — abstract wrapper only, full text paywalled.
- **#62** Robertson and Díaz IUI 2013 (ACM DL) — 403 paywalled.
- **#63** Conversational Grounding (Springer, Language Grid) — bot-check/cookie wall, paywalled chapter (topic page already flagged this as paywalled).
- **#64** Yamashita, Inaba, Kuzuoka, Ishida CHI 2009 — the only URL in the sweep sources is a *related* Springer chapter, not the primary paper, and it too is bot-checked/paywalled.
- **#65** Yamashita and Ishida, CSCW 2006 — **no URL anywhere in the sweep sources**; the sweep's own text says it only corroborated this via secondary citations and never fetched a primary source.
- **#68** ATA mother-tongue principle — atanet.org returned a bare 403.
- **#50** SHA-256 pre-registration blog (dev.to) — **no URL anywhere in the sweep sources**, only referenced in prose as "a dev.to blog post"; likely phantom.

## References whose URL turned out not to exist (phantom citations)

Two references in the topic page/sweep have **no resolvable URL at all** in any of the three raw
source files — meaning the sweep cited them by description only, never actually pinned down a
fetchable source:

- **#9 "Pupil dilation on AI text (2025, UNVERIFIED)"** — the raw sweep file itself calls this "cited via search snippet, title not fully resolved" and explicitly says "the citation was not resolved." This is the topic page carrying forward a source the original sweep never actually found.
- **#50 "SHA-256 pre-registration blog (dev.to, 2026)"** — the raw sweep file describes "One 2026-dated source surfaced in search (a dev.to blog post...)" but never gives a URL, title, or author. Same situation: named in prose, never pinned to a real page.

Additionally, **#65 Yamashita and Ishida, CSCW 2006** is a real, well-known paper (the foundational
one this whole citation chain traces back to) but the sweep never located and fetched an actual URL
for it — every mention in the raw files says "not independently fetched" / "corroborated by
multiple independent citing sources" only. It should be treated as UNVERIFIED-existence-of-source,
not UNVERIFIED-content, until someone finds the actual CSCW 2006 proceedings link.
