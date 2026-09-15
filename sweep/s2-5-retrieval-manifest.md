# Retrieval manifest, sweep 2 (LLM->human boundary), generated 2026-09-15 10:57

Source reports: 1-4 in this directory. Files land in papers/ next to the sweep-1 files. First pass by a Sonnet subagent (fetch.py: arXiv, Unpaywall, Semantic Scholar OA, Europe PMC, PubMed abstract), second-chance pass by claude-mini (second_chance.py: arXiv direct, Unpaywall, PubMed abstract by DOI). Both scripts + raw results are kept not published.

Counts: ABSTRACT 7, DUP 2, FAILED 32, PDF 35, XML+MD 10

| # | report | first author, year | DOI / arXiv | result | file | KB | note |
|---|---|---|---|---|---|---|---|
| 1 | 1- | Hale  | 10.3115/1073336.1073357 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.3115/1073336.1073357 -> code=200 err=None; pubmed-esearch 10. |
| 2 | 1- | Levy 2008 | 10.1016/j.cognition.2007.05.006 | PDF | 2008-levy-expectation-based-syntactic.pdf | 753.7 |  |
| 3 | 1- | Jaeger 2010 | 10.1016/j.cogpsych.2010.02.002 | ABSTRACT | 2010-pubmed20434141-redundancy-and-reduction-abstract.md | 1 | third pass via S2 ids: ABSTRACT |
| 4 | 1- | Levy 2007 | 10.7551/mitpress/7503.003.0111 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.7551/mitpress/7503.003.0111 -> code=200 err=None; pubmed-esea |
| 5 | 1- | Gibson 2019 | 10.1016/j.tics.2019.02.003 | ABSTRACT | 2019-pubmed31006626-how-efficiency-shapes-abstract.md | 1 | third pass via S2 ids: ABSTRACT |
| 6 | 1- | Bolliger 2025 | 10.3758/s13428-025-02677-4 | PDF | 2025-2408.04289-emtec-corpus-eye.pdf | 3605.1 |  |
| 7 | 1- | Gruteke 2024 | 2410.08162 | PDF | 2024-2410.08162-effect-surprisal-reading.pdf | 16807.2 |  |
| 8 | 1- | Tsipidi 2024 | 2410.16062 | PDF | 2024-2410.16062-surprise-uniform-information.pdf | 565.3 |  |
| 9 | 1- | Basani 2025 | 2509.18880 | PDF | 2025-2509.18880-diversity-boosts-text.pdf | 1840.7 |  |
| 10 | 1- | Shultz 2025 | 10.1098/rsos.241313 | XML+MD | 2025-pmc11840437-text-understanding-in.md | 56 | third pass via S2 ids: XML+MD |
| 11 | 1- | Britton 2024 | 10.3389/fnhum.2024.1363120 | PDF | 2024-britton-influence-discourse-connectives.pdf | 1440.0 |  |
| 12 | 1- | Seals 2023 | 2306.04537 | PDF | 2023-2306.04537-long-form-analogies.pdf | 571.4 |  |
| 13 | 1- | Guo  | 10.18653/v1/2024.findings-naacl.228 | PDF | 2024-2311.09807-curious-decline-linguistic.pdf | 607.0 |  |
| 14 | 1- | Muñoz-Ortiz 2024 | 10.1007/s10462-024-10903-2 | PDF | 2024-2308.09067-contrasting-linguistic-patterns.pdf | 2432 | third pass via S2 ids: PDF |
| 15 | 1- | Zamaraeva  | 2506.01407 | PDF | 2025-2506.01407-comparing-human-authored.pdf | 636.6 |  |
| 16 | 1- | Zindulka  | 10.1145/3772318.3791494 | PDF | 2026-2509.11851-memory-gap-users.pdf | 2918.7 |  |
| 17 | 1- | Samardzic 2025 | 10.3390/clinpract15110208 | XML+MD | 2025-pmc12651557-patients-prefer-human.md | 40 | third pass via S2 ids: XML+MD |
| 18 | 1- | Kumar 2026 | 10.3390/info17030299 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.3390/info17030299 -> code=200 err=None; pubmed-esearch 10.339 |
| 19 | 1- | Scantamburlo 2026 | 2603.19849 | PDF | 2026-2603.19849-semantic-delta-interpretable.pdf | 4304.1 |  |
| 20 | 1- | Inoshita 2026 | 2603.21228 | PDF | 2026-2603.21228-does-homogenize-student.pdf | 1177.3 |  |
| 21 | 2- | H. 1975 | 10.1163/9789004368811_003 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1163/9789004368811_003 -> code=200 err=None; pubmed-esearch 1 |
| 22 | 2- | Herbert 1991 | 10.1037/10096-006 | PDF | 1991-clark-grounding-in-communication.pdf | 185.7 |  |
| 23 | 2- | Deirdre 2016 | 10.1093/oxfordhb/9780199697960.013.25 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1093/oxfordhb/9780199697960.013.25 -> code=404 err=None; pubm |
| 24 | 2- | Allan 1984 | 10.1017/s004740450001037x | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1017/s004740450001037x -> code=200 err=None; pubmed-esearch 1 |
| 25 | 2- | Maurice 2023 | 10.1073/pnas.2208839120 | PDF | 2023-2206.07271-human-heuristics-for.pdf | 1074 | third pass via S2 ids: PDF |
| 26 | 2- | Maurice 2023 | 10.1145/3544548.3581196 | PDF | 2023-2302.00560-cowriting-with-opinionated.pdf | 1255 | third pass via S2 ids: PDF |
| 27 | 2- | Robert 1995 | 10.1207/s15516709cog1902_3 | FAILED | - | 0 | no accessible full text or abstract found; GET https://onlinelibrary.wiley.com/doi/pdfdirect/10.1207/s15516709 |
| 28 | 2- | Paula 2019 | 10.1111/cogs.12797 | FAILED | - | 0 | no accessible full text or abstract found; GET https://onlinelibrary.wiley.com/doi/pdfdirect/10.1111/cogs.1279 |
| 29 | 2- | Mateus 2023 | 10.1145/3638067.3638068 | FAILED | - | 0 | no accessible full text or abstract found; GET https://dl.acm.org/doi/pdf/10.1145/3638067.3638068 -> code=403  |
| 30 | 2- | Yi-Chia 2020 | 2012.14653 | PDF | 2020-2012.14653-can-you-be.pdf | 333.9 |  |
| 31 | 2- | Philip 1979 | 10.1207/s15516709cog0303_1 | FAILED | - | 0 | no accessible full text or abstract found; GET https://onlinelibrary.wiley.com/doi/pdfdirect/10.1207/s15516709 |
| 32 | 2- | Fiona 2023 | 10.1145/3637875 | FAILED | - | 0 | no accessible full text or abstract found; GET https://dl.acm.org/doi/pdf/10.1145/3637875 -> code=403 size=544 |
| 33 | 2- | Jiaqi 2025 | 2501.15678 | PDF | 2025-2501.15678-blissful-ignorance-people.pdf | 796.6 |  |
| 34 | 2- | Mark 2015 | 10.1371/journal.pone.0136100 | PDF | 2015-dingemanse-universal-principles-repair.pdf | 717.8 |  |
| 35 | 2- | Vidya 2022 | 10.1145/3491102.3501972 | PDF | 2022-2203.08420-how-do-you.pdf | 7760 | third pass via S2 ids: PDF |
| 36 | 2- | Sunnie 2024 | 10.1145/3630106.3658941 | PDF | 2024-2405.00623-im-not-sure.pdf | 2337 | third pass via S2 ids: PDF |
| 37 | 2- | James 2024 | 10.1038/s41562-024-01882-z | XML+MD | 2024-pmc11272575-testing-theory-of.md | 84 | third pass via S2 ids: XML+MD |
| 38 | 2- | Kyle 2024 | 10.1016/j.tics.2024.01.011 | PDF | 2024-s2oa-dissociating-language-and.pdf | 890 | third pass via S2 ids: PDF |
| 39 | 2- | Robert 2025 | 10.1609/aies.v8i3.36751 | PDF | 2025-wolfe-toward-needs-conscious.pdf | 6380.2 |  |
| 40 | 2- | Josephine 2026 | 10.5817/cp2026-4-1 | PDF | 2026-hagedorn-based-writing-assistants.pdf | 4546.0 |  |
| 41 | 2- | Andreas 2026 | 10.2139/ssrn.7244859 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.2139/ssrn.7244859 -> code=404 err=None; pubmed-esearch 10.213 |
| 42 | 2- | Han 2019 | 10.18653/v1/d19-1231 | PDF | 2019-moon-unified-neural-coherence.pdf | 528.7 |  |
| 43 | 3- | Jakesch 2023 | 10.1073/pnas.2208839120 | DUP | - | 0 | same DOI/arXiv as entry #24 |
| 44 | 3- | Mieczkowski 2021 | 10.1145/3449091 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1145/3449091 -> code=200 err=None; pubmed-esearch 10.1145/344 |
| 45 | 3- | Hohenstein 2020 | 10.1016/j.chb.2019.106190 | FAILED | - | 0 | no accessible full text or abstract found; GET https://www.sciencedirect.com/science/article/am/pii/S074756321 |
| 46 | 3- | Purcell 2025 | 10.1016/j.isci.2025.114092 | XML+MD | 2025-pmc12765382-writing-with-ai.md | 54 | third pass via S2 ids: XML+MD |
| 47 | 3- | Gray 2007 | 10.1126/science.1134475 | PDF | 2007-gray-dimensions-mind-perception.pdf | 182.3 |  |
| 48 | 3- | Gray 2012 | 10.1016/j.cognition.2012.06.007 | ABSTRACT | 2012-pubmed22784682-feeling-robots-and-abstract.md | 1 | third pass via S2 ids: ABSTRACT |
| 49 | 3- | Epley 2007 | 10.1037/0033-295x.114.4.864 | ABSTRACT | 2007-pubmed17907867-on-seeing-human-abstract.md | 1 | third pass via S2 ids: ABSTRACT |
| 50 | 3- | Longoni 2019 | 10.1093/jcr/ucz013 | FAILED | - | 0 | no accessible full text or abstract found; GET https://academic.oup.com/jcr/article-pdf/46/4/629/30624402/ucz0 |
| 51 | 3- | Sundar  | 10.1145/3290605.3300768 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1145/3290605.3300768 -> code=200 err=None; pubmed-esearch 10. |
| 52 | 3- | Yang 2024 | 10.1093/jcmc/zmae019 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1093/jcmc/zmae019 -> code=200 err=None; pubmed-esearch 10.109 |
| 53 | 3- | Dorigoni 2025 | 10.3389/fpsyg.2025.1568911 | PDF | 2025-dorigoni-illusion-empathy-evaluating.pdf | 1301.5 |  |
| 54 | 3- | Lim 2025 | 10.1016/j.chb.2025.108761 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1016/j.chb.2025.108761 -> code=200 err=None; pubmed-esearch 1 |
| 55 | 3- | Lim 2025 | 10.1016/j.pubrev.2024.102520 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1016/j.pubrev.2024.102520 -> code=200 err=None; pubmed-esearc |
| 56 | 3- | Ovsyannikova 2025 | 10.1038/s44271-024-00182-6 | PDF | 2025-ovsyannikova-third-party-evaluators.pdf | 1677.5 |  |
| 57 | 3- | Wu  | 10.1145/3441000.3441074 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1145/3441000.3441074 -> code=200 err=None; pubmed-esearch 10. |
| 58 | 3- | Ante. 2026 | 10.1016/j.tele.2026.102422 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1016/j.tele.2026.102422 -> code=200 err=None; pubmed-esearch  |
| 59 | 3- | Hagedorn 2026 | 10.5817/cp2026-4-1 | DUP | - | 0 | same DOI/arXiv as entry #39 |
| 60 | 3- | Heimstad 2025 | 10.1016/j.chbah.2025.100190 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1016/j.chbah.2025.100190 -> code=200 err=None; pubmed-esearch |
| 61 | 3- | Laupichler 2025 | 10.1111/bjet.70035 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1111/bjet.70035 -> code=200 err=None; pubmed-esearch 10.1111/ |
| 62 | 3- | Mariadassou 2024 | 10.1016/j.copsyc.2024.101839 | ABSTRACT | 2024-pubmed38996629-averse-to-what-abstract.md | 1 | third pass via S2 ids: ABSTRACT |
| 63 | 3- | Baghirov. 2026 | 10.1007/s11002-026-09822-9 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1007/s11002-026-09822-9 -> code=200 err=None; pubmed-esearch  |
| 64 | 3- | Ayers 2023 | 10.1001/jamainternmed.2023.1838 | ABSTRACT | 2023-pubmed37115527-comparing-physician-and-abstract.md | 5 | third pass via S2 ids: ABSTRACT |
| 65 | 3- | Garcia 2026 | 10.1371/journal.pone.0353391 | PDF | 2026-garcia-moral-turing-test.pdf | 3015.2 |  |
| 66 | 4- | Guerberof-Arenas 2020 | 10.1075/ts.20035.gue | PDF | 2020-2101.06125-the-impact-of.pdf | 447 | third pass via S2 ids: PDF |
| 67 | 4- | Doherty 2010 | 10.1007/s10590-010-9070-9 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1007/s10590-010-9070-9 -> code=200 err=None; pubmed-esearch 1 |
| 68 | 4- | Koponen 2016 | 10.26034/cm.jostrans.2016.303 | PDF | 2016-koponen-machine-translation-post.pdf | 364.5 |  |
| 69 | 4- | Vieira 2014 | 10.1007/s10590-014-9156-x | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1007/s10590-014-9156-x -> code=200 err=None; pubmed-esearch 1 |
| 70 | 4- | Zaretsky 2024 | 10.1001/jamanetworkopen.2024.0357 | XML+MD | 2024-pmc10928500-generative-artificial-intelligence.md | 37 | third pass via S2 ids: XML+MD |
| 71 | 4- | Bert 2026 | 10.1093/intqhc/mzag133 | ABSTRACT | 2026-pubmed42730664-comprehension-of-an-abstract.md | 2 | third pass via S2 ids: ABSTRACT |
| 72 | 4- | Xu 2026 | 10.2196/98118 | XML+MD | 2026-pmc13514414-rethinking-pediatric-asthma.md | 49 | third pass via S2 ids: XML+MD |
| 73 | 4- | Seo 2026 | 10.2196/89451 | XML+MD | 2026-pmc13252706-large-language-modelbased.md | 42 | third pass via S2 ids: XML+MD |
| 74 | 4- | Holderried 2026 | 10.2196/81243 | XML+MD | 2026-pmc12982961-impact-of-gpt4generated.md | 71 | third pass via S2 ids: XML+MD |
| 75 | 4- | Serna 2026 | 10.1093/radadv/umag008 | XML+MD | 2026-pmc13020909-selfreported-comprehension-of.md | 46 | third pass via S2 ids: XML+MD |
| 76 | 4- | Escalante 2023 | 10.1186/s41239-023-00425-2 | FAILED | - | 0 | no accessible full text or abstract found; GET https://educationaltechnologyjournal.springeropen.com/counter/p |
| 77 | 4- | Wu 2024 | 10.1111/bjet.13334 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1111/bjet.13334 -> code=200 err=None; pubmed-esearch 10.1111/ |
| 78 | 4- | Graefe 2018 | 10.1177/1464884916641269 | PDF | 2018-graefe-readers-perception-computer.pdf | 158.0 |  |
| 79 | 4- | Wölker 2021 | 10.1177/1464884918757072 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.1177/1464884918757072 -> code=200 err=None; pubmed-esearch 10 |
| 80 | 4- | Graefe 2020 | 10.17645/mac.v8i3.3019 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.17645/mac.v8i3.3019 -> code=200 err=None; pubmed-esearch 10.1 |
| 81 | 4- | Waddell 2019 | 10.1177/1077699018815891 | FAILED | - | 0 | no accessible full text or abstract found; GET https://journals.sagepub.com/doi/pdf/10.1177/1077699018815891 - |
| 82 | 4- | Altay 2024 | 10.1093/pnasnexus/pgae403 | XML+MD | 2024-pmc11443540-people-are-skeptical.md | 64 | third pass via S2 ids: XML+MD |
| 83 | 4- | Lermann 2024 | 10.3390/journalmedia5030069 | FAILED | - | 0 | no accessible full text or abstract found; s2 10.3390/journalmedia5030069 -> code=200 err=None; pubmed-esearch |
| 84 | 4- | Xiao 2024 | 10.1145/3643773 | PDF | 2024-2402.08967-generative-ai-for.pdf | 1174 | third pass via S2 ids: PDF |
| 85 | 4- | Van 2024 | 10.1038/s41591-024-02855-5 | PDF | 2024-2309.07430-adapted-large-language.pdf | 7237 | third pass via S2 ids: PDF |
| 86 | 4- | Brynjolfsson 2023 | 10.3386/w31161 | PDF | 2023-brynjolfsson-generative-ai-at.pdf | 979.8 |  |
