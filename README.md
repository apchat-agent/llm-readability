# llm-readability

Why LLM output is hard for humans to read: a literature sweep (2026-09-15)

Context: a proposed experiment on cross-language, LLM-mediated discussion of an IETF draft (see draft-fengfar-led, "Dealing with LLMs in IETF Discussions"). The draft's authors asked for a design, an evaluation, and a check of the state of the art. Raw reports with full citations: [sweep/](sweep/) (three subagent reports plus the retrieval manifest). Retrieved copies: [papers/](papers/); each entry below names its file. Summaries below are in short technical English. UNVERIFIED means the subagent did not confirm the source against a primary page. References are ordered 2024 and later first, then 2023 and earlier.

## Short answer

Nobody has done this experiment. Related studies exist. They agree on three points. Readers cannot see a fluent error. Readability ratings do not predict how much a reader retains. An AI label lowers trust by itself. Nobody has measured the unaided receiver in a real technical discussion.

## References, 2024 and later

### Comprehension and reading effort
- **Sleep-medicine summaries (PMC11704966, 2024).** LLM and medical-student summaries gave the same comprehension scores. Method: multiple-choice questions, McNemar's test. [file: 2024-pmc11704966-sleep-medicine-summaries.md]
- **AI vs human academic abstracts (PLOS One, 2025/26).** AI abstracts scored lower on readability formulas. They had more lexical diversity and more complex syntax. Method: text metrics only, no readers. [file: 2025-plosone-academic-abstracts.pdf]
- **ChatGPT vs L2 student essays (Frontiers in Education, 2025).** ChatGPT essays had more lexical diversity and complexity. They scored lower on readability. Method: corpus metrics. [file: 2025-frontiersed-l2-essays.pdf]
- **LLM vs professional Arabic subtitles (PMC12286245, 2025).** LLM subtitles caused more cognitive load. Effect sizes were not extracted. Method: eye tracking. [file: 2025-pmc12286245-arabic-subtitles.md]
- **Reader perception shifts on disclosure (arXiv 2510.24011, 2025).** Disclosure of AI authorship changed stated quality ratings. The study measured perception only. Method: pre and post disclosure comparison. [file: 2025-2510.24011-disclosure-perception.pdf]

### Style markers of LLM prose
- **Kobak et al., Science Advances 2024.** Words such as "delve" and "meticulous" spiked in PubMed abstracts after 2022. At least 13.5% of 2024 abstracts show LLM use. Method: excess vocabulary over 14 million abstracts. [file: 2024-kobak-excess-vocabulary.pdf]
- **Sourati et al., arXiv 2508.01491, 2025.** Co-writing with LLMs makes authors more similar to each other. Lexical and content diversity fall. Method: review of experiments. [file: 2025-2508.01491-homogenizing.pdf]
- **Stylometric comparison of creative writing (Nature HSSC, 2025).** Same clustering result, independent data. Method: stylometry. [file: 2025-nature-hssc-stylometric.pdf]
- **Em-dash rise in medRxiv (arXiv 2606.29540, 2026).** GPT-4.1 uses em-dashes 3.28 times as often as humans. Preprint em-dash rates rose with LLM adoption. Method: corpus counts. [file: 2026-2606.29540-emdash.pdf]
- **Tricolon metric (arXiv 2604.19768, 2026).** LLM text has 7.13 tricolons per document. Human experts have 3.73. Method: rhetorical-device counts. [file: 2026-2604.19768-tricolon.pdf]
- **Markdown fingerprint (arXiv 2603.27006, 2026).** Dashes, bullets and bold keywords come from markdown-heavy training data. Method: training-data and corpus analysis. [file: 2026-2603.27006-markdown-fingerprint.pdf]

### Trust and the AI label
- **AI-label RCT, N=164 (PMC11176609, 2024).** The same text labelled "ChatGPT" lost on competence (d=0.95), quality (d=0.39) and willingness to submit the text as one's own coursework (d=0.57). Topic had a small effect on competence only. Method: between-subjects label swap. [file: 2024-pmc11176609-ai-label-rct.md]
- **AI labels and perceived accuracy (arXiv 2506.16202, 2025; author list to re-verify).** An AI label lowers perceived accuracy of that item. It does not change wider attitudes. Method: large-N experiment. [file: 2025-2506.16202-label-accuracy.pdf]
- **AI disclosure and credibility (JCOM, 2026).** Disclosure lowered credibility of correct content. Disclosure raised credibility of misinformation. Single study, needs replication. [file: 2026-jcom-disclosure-credibility.pdf]
- **AI disclosure in news, N=433 (Oxford, 2024/25).** People with negative AI attitudes penalised disclosed content more. More detailed disclosure lowered trust further. Method: within-subjects experiment. [file: 2024-oxford-disclosure-news.pdf]
- **AI-generated and AI-assisted news (arXiv 2409.03500, 2024).** Trust effects carried into stated intent to read and share. Method: experiment. [file: 2024-2409.03500-ai-news.pdf]
- **Reputational risks of AI-mediated messages (arXiv 2509.09645, 2025, UNVERIFIED venue).** Messages labelled AI-assisted tell readers less about the sender's character. Not fetched in full. [file: 2025-2509.09645-reputational-risks.pdf]
- **AI-mediated video and trust (arXiv 2603.18868, 2026, UNVERIFIED venue).** AI retouching lowered interpersonal trust and judgment confidence. Method: two preregistered experiments, Likert scales. [file: 2026-2603.18868-video-trust.pdf]

### Translation and cross-language mediation
- **Xiao et al., EMNLP 2025 (arXiv 2510.09994).** Non-bilingual users over-rely on machine translation. They have no way to check it. Trust changes only after a seen error. Method: N=452 in a museum. [file: 2025-xiao-mt-literacy.pdf]
- **Yan et al., arXiv 2407.03658, 2024.** GPT-4 translates at junior-translator level. It falls behind senior translators. Its typical error is over-literal output. Method: expert error annotation. [file: 2024-2407.03658-yan-translators.pdf]
- **Chen and Lin, Frontiers in AI, 2025.** ChatGPT beat Google Translate and DeepL on Chinese tourism text. A fluency-tuned prompt cut fidelity from 4.04 to 3.69. Method: 7 bilingual raters, 5-point scales. [file: 2025-frontiersai-chen-lin.pdf]
- **Chinese-to-English technical translation (Forum for Linguistic Studies, year and authors UNVERIFIED).** Judges preferred ChatGPT-4 over Google Translate. Automatic metrics did not agree with the judges. [file: 2025-fls-technical-translation.html]
- **LLM quality estimation for user-generated content (arXiv 2410.06338, 2024, UNVERIFIED).** Google Translate and ChatGPT both failed on Chinese emotional slang. [file: 2024-2410.06338-quality-estimation.pdf]
- **LLM-BT-Terms (arXiv 2506.08174, 2025, UNVERIFIED).** Technical terms drift across back-translation paths. Exact match was 50 to 75%. [file: 2025-2506.08174-bt-terms.pdf]
- **Simpson's paradox in accuracy-fluency (arXiv 2402.12690, 2024, UNVERIFIED).** Aggregate accuracy-fluency correlations can reverse in subgroups. Caution for evaluation design. [file: 2024-2402.12690-simpsons-paradox.pdf]
- **Sustaining Human Agency, Attending to Its Cost (CHI 2025, arXiv 2503.07970).** Non-native senders lose control of their words under MT. Post-editing restores control and costs effort. Method: 45 real dyads. [file: 2025-2503.07970-human-agency.pdf]
- **Translation in the Hands of Many (arXiv 2502.13780, 2025).** Research should centre lay MT users and their repair habits. Position paper. [file: 2025-2502.13780-hands-of-many.pdf]
- **LAAC: LLM as a Communicator (arXiv 2511.04184, 2025).** The system rewrites what the sender meant to say before the receiver sees it. Not cross-lingual. Adjacent only. [file: 2025-2511.04184-laac-communicator.pdf]
- **Time to Talk, LLM agents in Mafia games (arXiv 2506.05309, 2025).** Agents play as participants. No agent mediates between two humans. Low relevance. [file: 2025-2506.05309-time-to-talk.pdf]

### Communities and institutions
- **draft-fengfar-led-01 (IETF, 2026-08-06).** Two voices: a skeptical reader and an AI-using non-native author. Names translation as a benefit. Warns that speed may reduce sender comprehension and reader trust. Proposes guidelines and no experiment. [file: 2026-ietf-draft-fengfar-led-01.txt]
- **IETF ai-in-standards list (2025/26).** Dedicated list on AI in the standards process. A 2026-09-11 thread proposed that consensus callers may ignore text they judge AI-generated. [file: 2025-ietf-ai-in-standards-list.html]
- **IETF mailing-list-ai-check tool (ietf-tools).** Pipeline scores list mail with the Pangram detector. Detection only, no comprehension data. [file: 2025-github-mailing-list-ai-check.html]
- **English Wikipedia RfC (March 2026).** Editors voted 40 to 2 to restrict LLM-generated articles. Style alone cannot justify sanctions. Community record. [file: 2026-wikipedia-rfc-llm-articles.html]
- **Zhou, Cho, Terveen, arXiv 2509.07819, 2025.** Editors rewrite LLM output to avoid suspicion. Other editors react to the style before the facts. Method: 16 interviews. [file: 2025-2509.07819-zhou-wikipedia.pdf]
- **Wikimedia "Simple Article Summaries" backlash (2025, press).** Editors rejected the trial at once. A press-reported case study with no controlled data. [file: 2025-wikimedia-simple-summaries-backlash.html]
- **SOGPTSpotter (arXiv 2602.04185, 2026).** Stack Overflow banned undisclosed AI answers. Detection remains hard. [file: 2026-2602.04185-sogptspotter.pdf]
- **AI text detection in peer review (arXiv 2502.19614, 2025).** LLM-written review comments are rising. Detectors are unreliable. Method: benchmark on real reviews. [file: 2025-2502.19614-peer-review-detection.pdf]
- **Open-source AI contribution policies (GitHub aggregator).** Projects restrict LLM pull requests. Stated reason: review time exceeds the value of the contribution. [file: 2025-github-oss-ai-policies.html]

## References, 2023 and earlier

- **Jakesch, French, Ma, Hancock, Naaman, CHI 2019.** Suspected AI profiles lost trust only in a mixed set of AI and human texts. Uniform sets showed no penalty. Named the "Replicant Effect". [file: 2019-jakesch-chi-ai-mediated.pdf]
- **Liu, Mittal, Yang, Bruckman, CHI 2022.** Disclosed AI help lowered trust in transactional email. It lowered trust less, or raised it, in emotional email. Method: survey and interviews. [file: 2022-liu-chi-ai-console.pdf]
- **Deng, Mehandru, Robertson, Salehi, TRAIT 2022.** Appropriate trust in MT depends on context. Generic metrics do not give lay users a usable signal. Method: 20 clinician interviews. [file: 2022-2205.06920-deng-trait.pdf]
- **Zhang, Owusu, Carpuat, Gao, CSCW 2022.** MT-translated subgroup logs shared before a meeting improved the meeting. MT worked as written context shared before the meeting. Live interpretation was out of scope. Method: 20 participants in quartets. [file: 2022-2209.02906-zhang-cscw.pdf]
- **Probe tasks for dialogue evaluation (arXiv 2008.10427, 2020).** Targeted probe questions test specific facts after a dialogue. Reusable as comprehension probes. [file: 2020-2008.10427-probe-tasks.pdf]
- **Martindale and Carpuat, AMTA 2018.** Users punished disfluent output. Users did not punish fluent wrong output. Fluent errors are the most dangerous. Method: pilot survey on three output types. [file: 2018-martindale-carpuat-fluency.pdf]
- **Wang, Fussell et al., Cornell (year UNVERIFIED).** Compares MT-mediated work with shared-English work. Not fetched. [file: 2013-wang-fussell-cornell.pdf]
- **Language justice and MT on social media (Modern Languages Open, year UNVERIFIED).** MT availability alone does not give equal participation. [file: 2020-mlo-language-justice.pdf]

## Gaps the literature leaves open

- The unaided receiver has never been the measured party.
- Every prior design mediates one direction only.
- Sealed originals revealed at the end appear in no communication study found.
- Most AI-mediated-communication studies measure trust and perception. Few measure receiver comprehension.
- Standards-body and mailing-list reactions to AI prose have no peer-reviewed study.
- The cost as a transfer from sender to receiver is a framing found nowhere.

## What a design must respect (input for the next step)

- Use comprehension probes that need a specific fact from the message. Keep ratings as the comparison.
- Blind the receiver to AI involvement until the end. The reveal itself changes ratings.
- Fix the genre: comments on one draft. Genre flips the result.
- Track whether shared terms stabilise across turns.
- Log the sender's cost: time and rounds spent on the outgoing translation.
- Do not rely on back-translation. Check the revealed originals with a bilingual reader.

## Instruments seen

Comprehension multiple-choice questions with McNemar or chi-square tests, cloze tests and reading time. Eye tracking and pupillometry. Likert trust, competence and quality scales with Cohen's d. Between-subjects label swap. Director/matcher tasks and lexical-entrainment counts. Back-translation agreement. Excess-vocabulary, tricolon, em-dash and stylometric-clustering forensics.

## Verification status

High: sources with a fetched abstract or article page (Martindale and Carpuat; Xiao et al.; Zhang et al.; Robertson and Díaz 2022; CHI 2025 agency paper; Jakesch; Hancock; Kobak; the N=164 label RCT; Chen and Lin; Yan et al.; draft-fengfar-led; Wikipedia RfC). Medium: title plus resolving URL. UNVERIFIED as tagged. Re-verify any 2026 arXiv item before it goes into a mail to the authors.

## Can not retrieve

Every reference without a retrieved copy in llm-readability-papers/. Reason in brackets. The two phantom entries stay listed so the sweep's own gap stays visible. Do not cite them.

- **LLM plain-language summaries, crowdsourced study (PubMed 42044823, 2025).** Readers rated LLM and human summaries as equally clear. Readers answered more comprehension questions correctly after the human summaries. Method: comprehension questions plus clarity ratings. [not retrieved: PubMed wall; Europe PMC lists it as closed access]
- **Rashid et al., HFES 2024.** Short 8th-grade passages from ChatGPT-3.5 were read faster than human passages. Comprehension scores were higher for the ChatGPT passages. Method: reading speed, comprehension quiz, quality ratings. [not retrieved: SAGE paywall]
- **LLM vs human process models, eye tracking (Springer, 2025).** Comprehension was the same for both. Sample was 16 people. Method: comprehension score, task time, fixations. [not retrieved: Springer book chapter, paywall]
- **Eye tracking of AI and human texts (ACM ETRA, 2025).** Gaze patterns were tested as a way to tell AI text from human text. Comprehension was not the outcome. Method: eye tracking on 6 texts. [not retrieved: ACM DL paywall]
- **Pupil dilation on AI text (2025, UNVERIFIED).** Pupils were larger on AI text. Readers still rated AI text as more readable. The citation was not resolved. [not retrieved: no source found in the sweep, likely phantom]
- **AI vs human reading-comprehension test passages (Large-scale Assessments in Education, 2025).** Experts found AI passages equal on vocabulary and length. Experts flagged authenticity and bias risks. Method: expert SWOT review. [not retrieved: Springer bot wall, the journal is open access, retry by hand]
- **Why ChatGPT "delves", COLING 2025.** The overuse of "delve" traces to RLHF labeler demographics. The cause is the training pipeline. Method: frequency analysis. [not retrieved: paper PDF not found, only FSU press coverage saved]
- **Homogenizing effect on creative diversity (ScienceDirect, 2024/25, journal name not confirmed).** LLM texts cluster tightly by model. Human texts spread widely. Method: stylometry. [not retrieved: ScienceDirect paywall]
- **AI-authorship across domains (Springer, 2025/26).** The label penalty holds. Domain and presentation style change its size. Method: label manipulation. [not retrieved: Springer book chapter, paywall]
- **Suspected ChatGPT in consumer reviews (J. Retailing and Consumer Services, 2024).** Reviews that readers thought were AI scored lower on usefulness, trust and authenticity. No disclosure was needed. Method: experiment. [not retrieved: ScienceDirect paywall]
- **Purcell et al., British Journal of Psychology, 2026 (UNVERIFIED detail).** People accept their own AI use more than others' secret AI use. Method: preregistered experiment. [not retrieved: Wiley paywall]
- **SHA-256 pre-registration blog (dev.to, 2026, blog post).** One author hashes a hypothesis before LLM trials. Existence proof only. [not retrieved: no source found in the sweep, likely phantom]
- **Hancock, Naaman, Levy, JCMC 2020.** Defines AI-mediated communication on five dimensions. Names cross-language mediation as open work. Theory paper. [not retrieved: Oxford Academic 403]
- **Robertson and Díaz, FAccT 2022.** Users in MT-mediated chat cannot detect subtle mistranslation. Not knowing what the other side received is the main friction. Method: 19 bilingual role-play conversations. [not retrieved: ACM DL 403, fullHtml exists on the site]
- **Verschuere et al., preregistered replication (~2021).** OSF registration is the closest verified analogue to a sealed original. Method: preregistration. [not retrieved: Wiley paywall]
- **Cultural misunderstanding warning in MT chat (Springer, ~2020, UNVERIFIED).** A warning flags cultural risk next to MT output. Not fetched. [not retrieved: Springer book chapter, paywall]
- **Back-translation validity (IEEE 7433246, ~2016).** Back-translation is a weak fidelity proxy. Errors can cancel over two hops. [not retrieved: IEEE paywall]
- **Robertson and Díaz, IUI 2013 (UNVERIFIED detail).** Frames MT as an agent in mediated chat. Studies how the frame changes trust. [not retrieved: ACM DL paywall]
- **Conversational Grounding in MT-Mediated Communication (Language Grid volume, Springer 2011).** Success tracks how well partners repair misunderstandings. Raw MT accuracy matters less. People add redundancy and confirmation checks. Partly UNVERIFIED, paywalled. [not retrieved: Springer book chapter, paywall]
- **Yamashita, Inaba, Kuzuoka, Ishida, CHI 2009.** MT groups fail to share tone and to build common terms. The same term is translated differently each turn. Method: multiparty MT chat, log coding. [not retrieved: Springer related chapter, paywall; primary CHI paper URL never found]
- **Yamashita and Ishida, CSCW 2006.** MT changes how people collaborate as well as what they receive. Partners cannot shorten shared terms over a dialogue. Method: task-based experiment. Primary PDF not fetched. [not retrieved: no URL found in the sweep, primary PDF never fetched]
- **ATA, the mother-tongue principle (year UNVERIFIED).** Translators should translate into their native language. LLM mediation ignores this rule in both directions. [not retrieved: ATA site 403]

## How this was made

Three literature-search subagents (Claude Sonnet) ran about 45 web searches on 2026-09-15 and wrote the reports in sweep/. A Claude Fable 5.1 session synthesised this README, then a fourth subagent fetched every reference it could; the manifest in papers/MANIFEST.md records each attempt. Nothing here has been peer reviewed. UNVERIFIED tags mark sources the sweep did not confirm against a primary page.

## License

The text in this repository (README and sweep/) is licensed under CC BY 4.0 (see LICENSE). The files in papers/ are third-party works retrieved from open-access sources; each keeps its own license (see NOTICE).
