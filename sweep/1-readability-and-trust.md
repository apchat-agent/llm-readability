# Human Comprehension & Readability of LLM-Generated Text (unassisted human reader) — Literature Scan 2022–2026

Scope: peer-reviewed preferred, arXiv preprints acceptable. Compiled 2026-09-15 via web search; sources not directly read in full text are marked accordingly. Entries marked **UNVERIFIED** could not be confirmed to exist as described and should be checked before citing.

---

## (a) Comprehension, reading time, recall, cognitive load: LLM-written vs human-written text

### 1. Rashid, Atilgan, Dobres, Day, Penkova, Küçük, Clapp, Sawyer (2024)
**"Humanizing AI in Education: A Readability Comparison of LLM and Human-Created Educational Content"**
*Proceedings of the Human Factors and Ergonomics Society (HFES) Annual Meeting*, SAGE Journals.
https://journals.sagepub.com/doi/10.1177/10711813241261689
Method: 300-word, 8th-grade-level passages authored by humans vs. ChatGPT-3.5 on matched topics; human participants read passages and were measured on reading speed, comprehension accuracy, and rated the passages for interest, familiarity and perceived quality.
Finding: ChatGPT-3.5 passages were read **faster** and produced **better comprehension scores** than the human-authored passages, and were rated higher quality, with comparable interest/familiarity ratings. Notable because it runs counter to the "AI text is harder to process" intuition — for short, simple educational passages, LLM text measured as *easier*, not harder.

### 2. Unnamed 2025 eye-tracking / pupillometry study (cited via search snippet, title not fully resolved)
**Cognitive-load / pupil-dilation study of AI-generated vs. original human text** — described in search aggregation, not independently confirmed with full citation. **UNVERIFIED** (could not resolve exact title/venue in this pass) — reported: "pupil sizes were larger for the AI-generated texts than for the original texts," consistent with higher cognitive load, while reader *perception* rated AI text as more readable (~70% rated it as/more readable than human text). Treat as a lead to re-verify, not a confirmed citation — the finding (perception-reality gap) recurs independently in item 3 below, which is a stronger, traceable source for the same claim.

### 3. Journal of Science Communication line of work / arXiv "Understanding Reader Perception Shifts upon Disclosure of AI Authorship" (2025)
https://arxiv.org/html/2510.24011v1
Method: reader perception experiment examining shifts in evaluation once AI authorship is disclosed (pre/post-disclosure comparison design).
Finding: consistent with other disclosure literature (see §c) — readers' *stated* quality perception and their *actual* comprehension/processing are not the same thing; disclosure changes the former without necessarily changing the latter.

### 4. "Comparing the Comprehensibility of LLM-Generated and Human-Created Process Models: An Eye-Tracking Study" (2025)
*Springer* (book chapter / workshop proceedings).
https://link.springer.com/chapter/10.1007/978-3-032-28274-3_6
Method: 16 participants performed comprehension tasks on LLM-generated vs. human-created business-process models (diagrammatic, not prose, but directly on-topic for comprehension methodology); measured comprehension score, task duration, and eye fixations; working memory and selective attention assessed as covariates.
Finding: LLM-generated process models achieved comprehension performance **comparable to** human-created ones on this task — no significant deficit found, small sample (n=16) limits power.

### 5. "Reading the Readers Mind through Eye Tracking: Can AI Generated Texts Match Human Authors?" (2025)
*ACM ETRA 2025 (Symposium on Eye Tracking Research and Applications)*.
https://dl.acm.org/doi/10.1145/3715669.3726846
Method: 6 texts (3 human-authored, 3 AI-generated to imitate specific authors' styles, generated spring 2024), read under eye-tracking, testing whether gaze patterns distinguish AI from human text and whether AI text can pass as human-authored stylistically.
Finding: focuses on detectability via gaze pattern rather than comprehension outcome per se; relevant as a methodology exemplar for (a).

### 6. "Through the Eyes of the Viewer: The Cognitive Load of LLM-Generated vs. Professional Arabic Subtitles" (2025)
*PMC* (journal not fully resolved in this pass — appears to be a specialist AV/translation venue).
https://pmc.ncbi.nlm.nih.gov/articles/PMC12286245/
Method: eye-tracking comparison of viewer cognitive load reading LLM-generated vs. professionally produced Arabic subtitles.
Finding: cited as evidence that LLM-generated subtitles impose measurably different (reported as higher) cognitive load than professional human translation in a time-constrained reading task; exact effect sizes not extracted in this pass — verify against full text before quoting numbers.

### 7. "Are LLM-generated plain language summaries truly understandable? A large-scale crowdsourced evaluation" (2025)
PubMed-indexed (PMID resolvable via https://pubmed.ncbi.nlm.nih.gov/42044823/).
Method: large-scale crowdsourced study; participants read LLM-generated vs. human-written plain-language summaries (of scientific/medical text) and answered comprehension questions; summaries also rated for clarity/coherence.
Finding: participants rated LLM summaries as **similarly clear and coherent** to human ones, BUT performed **significantly better on comprehension questions after reading human-written summaries**. This is one of the cleaner, most directly relevant findings for the "unassisted reader comprehension" question: fluency of LLM text does not track with actual comprehension outcome — subjective ease of reading and objective comprehension diverge.

### 8. Sleep-medicine summarization comparison — "Reader's digest version of scientific writing" (PMC11704966)
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11704966/
Method: LLMs vs. medical students produced summaries of scientific writing in sleep medicine; evaluated via McNemar's test on comprehension multiple-choice questions.
Finding: **no significant difference** between AI- and human-produced summaries on comprehension MCQ accuracy in this domain/sample — a null result worth citing precisely because it contradicts both directions of stronger claims (contrast with #7).

### 9. PLOS One — "Comparative analysis of text readability and writing styles in AI-generated vs. Human-written academic abstracts" (2025/2026)
https://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0343163
Method: corpus/computational analysis of readability metrics and stylistic features across AI-generated vs. human-written academic abstracts (not a human-subject reading-outcome study — a text-property study).
Finding: AI-generated abstracts were **more complex and less readable** by standard readability metrics in the academic-abstract genre — ChatGPT text there shows greater lexical diversity/syntactic complexity but *lower* readability and weaker communicative appropriateness. This directly contradicts the "AI text is simpler/easier" framing found in #1 and shows genre matters a great deal: short educational prose (easy) vs. dense academic abstracts (harder) pull in opposite directions.

### 10. Springer LAE — "Evaluating AI-generated vs. human-written reading comprehension passages: an expert SWOT analysis and comparative study for an educational large-scale assessment" (2025)
*Large-scale Assessments in Education*, Springer Nature.
https://link.springer.com/article/10.1186/s40536-025-00255-w
Method: expert (not lay-reader) SWOT-style qualitative + comparative evaluation of AI-generated vs. human-written reading-comprehension test passages intended for large-scale educational assessment use.
Finding: expert evaluators identified trade-offs — AI passages can match human ones on some formal criteria (vocabulary control, length) but experts flagged risks around authenticity, content bias and pedagogical nuance; not a reader-outcome study, use as complement to #1.

---

## (b) Stylistic properties that make LLM prose harder/more tiring to read (homogeneity, hedging, verbosity, "AI-ese", lexical tics, em-dashes, tricolon, rule-of-three, low information density)

### 11. Kobak, González-Márquez, Horvát, Lause (2024)
**"Delving into LLM-assisted writing in biomedical publications through excess vocabulary"** (also published as "Delving into ChatGPT usage in academic writing through excess vocabulary")
*Science Advances* (peer-reviewed; also arXiv 2406.07016) — https://www.science.org/doi/10.1126/sciadv.adt3813 ; preprint https://arxiv.org/abs/2406.07016
Method: corpus analysis of >14 million PubMed abstracts (2010–2024), tracking word-frequency shifts ("excess vocabulary" = words whose frequency abruptly rose after ChatGPT's release relative to historical baseline) as a marker of LLM-assisted writing.
Finding: an abrupt, measurable spike in specific "style words" (e.g., "delve," "boundless," "intricate," "meticulous," "underscore," "showcasing") appeared in biomedical abstracts starting in late 2022/2023; the authors estimate **at least 13.5% of 2024 abstracts** show detectable LLM involvement by this method. Directly documents the lexical-tic phenomenon (b) at corpus scale using excess-word-frequency methodology, not reader-judgment.

### 12. Cai, Zhao, et al. / FSU researchers — **"Why Does ChatGPT 'Delve' So Much? Exploring the Source of Overrepresentation in Large Language Models"**
*Proceedings of the 31st International Conference on Computational Linguistics (COLING) 2025*.
News coverage: https://news.fsu.edu/news/science-technology/2025/02/17/why-does-chatgpt-delve-so-much-fsu-researchers-begin-to-uncover-why-chatgpt-overuses-certain-words/
Method: traced the disproportionate frequency of words like "delve" in GPT output to RLHF labeler demographics/training-data provenance (e.g., disproportionate representation of Nigerian English data-labelers, in whose English variety "delve" is more common) as a causal hypothesis, backed by frequency analysis of training/output text.
Finding: first study to propose and test a causal mechanism (rather than just document the pattern) for why LLMs over-represent specific vocabulary items — ties the "AI-ese" lexicon to RLHF pipeline artifacts rather than to "AI itself" being inherently that way.

### 13. Sourati, Ziabari, Dehghani (2025/2026, revised)
**"The Homogenizing Effect of Large Language Models on Human Expression and Thought"**
arXiv 2508.01491 (USC). https://arxiv.org/abs/2508.01491
Method: synthesis/position paper across linguistics, psychology, cognitive science and CS, reviewing empirical evidence (including co-writing experiments) that LLM assistance reduces lexical/content diversity and increases inter-author similarity when people use LLMs to write or co-write.
Finding: cites empirical results that co-writing with InstructGPT-style models **increased inter-author similarity** and **reduced lexical and content diversity**; "each additional human-written essay contributed more new ideas than each additional GPT-4 essay" in comparative-diversity experiments the paper reviews. Directly supports the "homogeneity" claim in (b), though this specific paper is a synthesis/review rather than a primary experiment — check its cited primary sources if precision is required.

### 14. **"Homogenizing effect of large language models (LLMs) on creative diversity: An empirical comparison of human and ChatGPT writing"** (2024/2025)
*ScienceDirect* (journal not fully identified in this pass — appears to be a new/emerging open-access title; could not confirm exact journal name/peer-review status in this pass — flag as **PARTIALLY VERIFIED**, exists as an indexed ScienceDirect article, journal name to confirm).
https://www.sciencedirect.com/science/article/pii/S294988212500091X
Method: empirical comparison of stylometric/diversity measures between corpora of human-written and ChatGPT-written creative text.
Finding: reports LLM outputs cluster tightly by model (low internal diversity) while human texts form broader, more heterogeneous clusters — direct empirical stylometric evidence for "AI-ese" as a real, measurable narrowing of the output distribution.

### 15. Nature — Humanities and Social Sciences Communications — **"Stylometric comparisons of human versus AI-generated creative writing"** (2025)
https://www.nature.com/articles/s41599-025-05986-3
Method: stylometric feature analysis (peer-reviewed, Springer Nature open-access journal) comparing human and AI creative writing corpora.
Finding: corroborates the homogenization/clustering finding independently of #14; used as convergent evidence.

### 16. **"Em-ergence of the em-dash: a population-level rise in em-dash frequency in medRxiv preprints at the dawn of the large-language-model era"** (2026)
arXiv, https://arxiv.org/pdf/2606.29540
Method: corpus-level frequency analysis of em-dash usage in medRxiv preprints over time, correlated with the release/adoption timeline of major LLMs (GPT-4.1 etc.).
Finding: measured GPT-4.1 outputs used em-dashes at **3.28× the frequency** of standard human-written essays; population-level em-dash frequency in medRxiv preprints rose sharply post-LLM-adoption — a quantifiable, corpus-based instance of a specific "AI-ese" lexical/punctuation tic.

### 17. **"Saying More Than They Know: A Framework for Quantifying Epistemic-Rhetorical Miscalibration in Large Language Models"** (2026)
arXiv 2604.19768, https://arxiv.org/pdf/2604.19768
Method: introduces a quantitative framework/metric for tricolon (rule-of-three) usage and rhetorical-intensity measurement in LLM vs. human text; reports tricolon counts per document.
Finding: LLM-generated text averages **7.13 tricola per document vs. 3.73 for human experts**; the paper also reports a correlation between rhetorical intensity (tricolon/rule-of-three density) and estimated LLM usage rate in a corpus, with the highest-rhetoric decile showing ~20.9% estimated LLM usage vs. 9.0% in the lowest-rhetoric decile — a proposed forensic-linguistic metric directly on stylistic device (b).

### 18. **"The Last Fingerprint: How Markdown Training Shapes LLM Prose"** (2026)
arXiv, https://arxiv.org/html/2603.27006v1
Method: traces stylistic markers (including em-dash overuse, bullet-heavy structure, bolded-keyword habits) to markdown-formatted training data as the causal source, via corpus/training-data analysis.
Finding: proposes the em-dash-as-markdown-residue hypothesis and more broadly argues several "AI-ese" prose tics are artifacts of markdown-saturated pretraining/RLHF data rather than an emergent property of "AI writing" per se — relevant to WHY (b) exists, not just that it exists.

### 19. Frontiers in Education — **"Lexical diversity, syntactic complexity, and readability: a corpus-based analysis of ChatGPT and L2 student essays"** (2025)
https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2025.1616935/full
Method: corpus-based comparison of lexical diversity, syntactic complexity and standard readability metrics between ChatGPT-generated and L2 (second-language) student essays.
Finding: ChatGPT text shows **greater lexical diversity and syntactic complexity** but reduced readability/communicative appropriateness relative to the comparison corpus — reinforces PLOS One finding (#9) that "more sophisticated" LLM prose is not the same as "easier to read" prose.

---

## (c) Reader trust/credibility/reputation when text is suspected or labeled AI-generated

### 20. Altay, Nielsen, et al. (exact author list not confirmed in this pass) — **"AI labeling reduces the perceived accuracy of online content but has limited broader effects"** (2025)
arXiv 2506.16202 (Wang, Sturgis, de Kadt per WebFetch metadata — **note discrepancy**: search snippet attributed differently than the WebFetch extraction; author list should be re-verified against the arXiv abstract page directly before citing).
https://arxiv.org/pdf/2506.16202
Method: (large-N) weighted-regression experimental study on the causal effect of AI-generated labels on perceived accuracy/credibility of online content, plus tests for downstream/broader behavioral effects.
Finding: AI-generated labels **reduce perceived accuracy/trustworthiness** of labeled content relative to unlabeled/human-labeled identical content, but the effect does **not spill over** into broader attitude or behavior change beyond the immediately labeled item.

### 21. **"Visible sources and invisible risks: exploring the impact of AI disclosure on perceived credibility of AI-generated content"** (2026)
*Journal of Science Communication (JCOM)*, peer-reviewed.
https://jcom.sissa.it/article/pubid/JCOM_2501_2026_A09/
Method: experimental disclosure study measuring perceived credibility of AI-generated science content with/without AI-authorship disclosure.
Finding: reports a "truth-falsity crossover effect" — AI disclosure **reduced perceived credibility of correct/accurate information** while (counterintuitively) **increasing perceived credibility of misinformation** carrying an AI label, versus the same content unlabeled. A striking, precise, quotable result — verify the exact effect direction against full text before restating without qualification, since it runs against intuition.

### 22. **"Or They Could Just Not Use It?": The Dilemma of AI Disclosure for Audience Trust in News** (Oxford, 2024/2025)
Oxford Research Archive: https://ora.ox.ac.uk/objects/uuid:65830edf-2b12-41f6-98e3-5855de38dfdd/files/rzw12z6837 ; ResearchGate summary: https://www.researchgate.net/publication/388526896
Method: within-subjects experiment, N=433, manipulating AI disclosure detail/label type ("influenced," "assisted," "generated") and outlet format (blog vs. news agency) in news content.
Finding: negative pre-existing attitudes toward AI significantly **moderated** the disclosure-credibility effect (people already anti-AI penalized disclosed content much more); audience involvement had only limited moderating influence; more detailed disclosure could paradoxically **reduce** trust further ("full disclosure, less trust" — see related arXiv 2601.09620, same research cluster).

### 23. Effects of Assumed AI vs. Human Authorship (2024) — full citation
**"The impact of text topic and assumed human vs. AI authorship on competence and quality assessment"**
Journal: peer-reviewed, PMC-indexed (PMC11176609; PMID 38881953). Exact journal title not resolved by search snippet in this pass (PMC page was blocked by a bot-check during fetch) — **treat journal name as unconfirmed, re-check before citing formally**; the paper itself is real and indexed on PubMed/PMC.
https://pmc.ncbi.nlm.nih.gov/articles/PMC11176609/ / https://pubmed.ncbi.nlm.nih.gov/38881953/
Method: randomized controlled experiment, N=164 participants; each read 6 identical texts (3 moral-topic, 3 technology-topic) randomly labeled as authored by "ChatGPT" or a "human author" (same text, only the label varied — a clean between-subjects manipulation isolating label effect from content effect). Measured: perceived author competence, content quality rating, and stated willingness to submit the text as one's own in a university-course context.
Finding: texts labeled ChatGPT were **consistently devalued** vs. the identical text labeled human-authored, across all three outcomes — competence (p<.001, d=0.95, a large effect), content quality (p<.001, d=0.39), and submission-intention (p<.001, d=0.57). Only a small topic×authorship interaction on competence; no interaction on the other two measures — i.e., the penalty for the "AI" label held regardless of topic sensitivity. Directly and precisely supports "algorithm aversion" for identical content, purely from the label.

### 24. Springer — **"Evaluating AI-Authorship: The Role of Text Domain and Presentation Style"** (2025/2026)
https://link.springer.com/chapter/10.1007/978-3-032-26717-7_22
Method: extends the authorship-label manipulation design (per #23) across multiple text domains and presentation styles.
Finding: cited as replicating/extending the authorship-devaluation effect while showing it is moderated by domain and presentation — use as a generalizability check on #23's effect.

### 25. Consumer reviews — **"Consumer reactions to perceived undisclosed ChatGPT usage in an online review context"** (2024)
*Journal of Retailing and Consumer Services* (ScienceDirect), peer-reviewed.
https://www.sciencedirect.com/science/article/abs/pii/S0736585324000674
Method: experimental study of consumer ratings of online reviews they perceived as ChatGPT-generated vs. human-written (undisclosed suspicion condition).
Finding: reviews **perceived** as ChatGPT-generated were rated **less useful, less trustworthy, and less authentic** by consumers than the same/comparable reviews perceived as human-written — trust penalty operates even without formal disclosure, purely from reader suspicion.

### 26. Quality Perceptions and Intended Engagement in Response to AI-Generated and AI-Assisted News (2024)
arXiv 2409.03500. https://arxiv.org/pdf/2409.03500
Method: experimental study on reader quality perceptions and stated engagement intentions for news content varying by AI involvement level (fully AI-generated vs. AI-assisted vs. human).
Finding: contributes to the disclosure-effects literature cluster (#20–22); documents engagement-intention effects alongside quality-perception effects, i.e. trust effects translate into stated behavioral intention (share/read further), not just attitude.

---

## (d) AI-generated text in professional deliberation communities (standards bodies, mailing lists, peer review, Wikipedia, Stack Overflow)

### 27. Wikipedia community policy — **"Wikipedia:Case against LLM-generated articles"** + RfC outcome (2025/2026)
Primary/community source (not peer-reviewed, but a directly relevant primary-source community record): https://en.wikipedia.org/wiki/Wikipedia:Case_against_LLM-generated_articles ; reporting: https://www.medianama.com/2026/03/223-english-wikipedia-bans-ai-generated-text-allows-limited-use-copyediting-translation/
Method: N/A (community governance record, not a study) — includes the March 2026 RfC in which editors voted **40–2** to place heavy restrictions on LLM-generated article text and adopted a new speedy-deletion criterion (G15) for unreviewed LLM-generated pages.
Finding: strong, quantifiable community-level rejection signal; explicitly, English Wikipedia's guidance states that "stylistic or linguistic characteristics alone do not justify sanctions" against a human editor (i.e. formal policy acknowledges detection-tool unreliability and prohibits penalizing an editor merely for writing in an LLM-like style) — an important nuance for the "reaction" question: the community's objection is to unreviewed machine content, not to prose that merely resembles LLM style.

### 28. Zhou, Cho, Terveen (2025)
**"LLMs in Wikipedia: Investigating How LLMs Impact Participation in Knowledge Communities"**
arXiv 2509.07819. https://arxiv.org/abs/2509.07819
Method: qualitative interview study, 16 Wikipedia editors who had used LLMs in their contribution workflow; examined (1) how LLMs change contribution practices, (2) editor strategies to align LLM output with community norms, (3) how *other* editors react to LLM-assisted contributions.
Finding: directly on-topic peer-reviewed-track study for (d) — documents that editors must actively "domesticate" LLM output style to avoid triggering negative community reactions (norm violations are partly *stylistic*, i.e. text that "reads like AI" draws scrutiny/pushback independent of factual accuracy), and that community response to detected LLM involvement is often skeptical/negative, prompting concealment or heavy editing of LLM drafts before submission.

### 29. Wikimedia Foundation "Simple Article Summaries" trial backlash (2025, reported via press, not a study)
Reported in multiple outlets summarized via https://www.plagiarismtoday.com/2026/03/30/wikipedia-and-the-problem-with-banning-ai/ and https://interestingengineering.com/ai-robotics/wikipedia-bans-ai-generated-text-xontent
Method: N/A — real-world community reaction to a foundation-led product trial, not a controlled study.
Finding: editor community response was immediate and strongly negative ("ghastly idea"), citing trust erosion and hallucination risk — a real-world natural experiment example directly matching the "professional deliberation community reaction" question, useful as case-study evidence though not peer-reviewed research.

### 30. **"SOGPTSpotter: Detecting ChatGPT-Generated Answers on Stack Overflow"** (2026)
arXiv 2602.04185. https://arxiv.org/pdf/2602.04185
Method: builds and evaluates a detector for ChatGPT-generated Stack Overflow answers; implicitly documents platform response (Stack Overflow's ban on undisclosed AI-generated answers) and the detection difficulty.
Finding: confirms Stack Overflow formally banned AI-generated content due to correctness/quality concerns, but reliable detection remains difficult — the "reaction" here is institutional/policy-level (ban) rather than a reader-comprehension effect, useful for (d) but not (a)-(c).

### 31. Peer review — **"Is Your Paper Being Reviewed by an LLM? Benchmarking AI Text Detection in Peer Review"** (2025)
arXiv 2502.19614. https://arxiv.org/pdf/2502.19614
Method: benchmarks AI-text-detection tools specifically applied to peer-review comments, using a corpus of real reviewer comments.
Finding: documents the rise of LLM-generated/LLM-assisted peer review comments across major publishers (IEEE, Elsevier mentioned in reporting) and the difficulty of reliably detecting them; raises reviewer-accountability concerns, relevant to (d) as a professional-deliberation venue where recipients (authors, editors) increasingly suspect AI involvement in the text they receive.

### 32. IETF — **ai-in-standards mailing list** (2025/2026, primary source, not a study)
http://www.mail-archive.com/ietf-announce@ietf.org/msg27079.html
Method: N/A — institutional record.
Finding: IETF created a dedicated non-working-group mailing list specifically to deliberate the use of AI in the IETF standards process itself — evidence that at least one major standards body has institutionally recognized AI-generated-text-in-deliberation as an issue warranting a dedicated venue, though no outcome/reaction data was retrievable in this pass. **No peer-reviewed study found specifically measuring recipient reactions to AI-generated text within IETF/W3C-style standards deliberation** — this appears to be a genuine gap in the literature as of this scan; flag as an open area rather than invent a citation.

### 33. Open-source contribution policies (aggregator, primary source)
https://github.com/melissawm/open-source-ai-contribution-policies
Method: N/A — curated list of real project policies.
Finding: documents a cross-project pattern of formal policies restricting/discouraging LLM-generated pull requests, several explicitly reasoning that "a contribution should be worth more to the project than the time it takes to review it, which is usually not the case if large parts of your PR were written by LLMs" — i.e., reviewer time-cost/verification-burden is the explicit, stated rationale in this community, a useful mechanism-level finding for (d) even though it's not a controlled study.

**No controlled/peer-reviewed study of open-source mailing-list (e.g., Linux kernel, LKML) reactions to LLM-generated prose specifically (as opposed to LLM-generated code) was found in this scan.** Treat as an open gap.

---

## Measurement instruments used in this literature

| Instrument / Metric | One-line description |
|---|---|
| **Flesch Reading Ease (FRE)** | Formula from sentence length + syllables/word; higher score = easier text; widely used to score LLM vs. human text readability. |
| **Flesch–Kincaid Grade Level (FKGL)** | Same inputs as FRE, rescaled to a US school-grade-level estimate of the reading difficulty required. |
| **Cloze test** | Reader/participant predicts or fills in a deleted word given surrounding context; used both as a comprehension proxy and to compare human next-word-prediction against LLM token probabilities. |
| **Comprehension multiple-choice questions (MCQ)** | Post-reading quiz on passage content; accuracy compared via chi-square/McNemar's test between AI-text and human-text reading conditions. |
| **Eye-tracking (fixation duration, gaze pattern, scanpath)** | Measures where/how long readers look, used as an objective proxy for reading effort/comprehension difficulty and (separately) as an AI-text detection signal. |
| **Pupillometry (pupil dilation)** | Physiological proxy for cognitive load during reading; larger pupil diameter interpreted as higher processing effort. |
| **EEG (word-level neural state classification)** | Used alongside eye-tracking to classify comprehension/semantic-inference state during reading. |
| **McNemar's test** | Paired-nominal-data significance test used to compare proportion of correct comprehension answers between two reading conditions. |
| **Cohen's d** | Standardized effect size reported for authorship-label experiments (e.g., competence d=0.95, quality d=0.39, submission-intention d=0.57). |
| **Wilcoxon Signed-Rank Test** | Non-parametric paired test used to compare reader preference ratings between LLM- and human-authored articles. |
| **Excess vocabulary / word-frequency-delta analysis** | Corpus method: tracks the frequency of specific words over time and flags abrupt post-LLM-release spikes as a marker of LLM assistance (not a reader-facing instrument, a text-forensic one). |
| **Tricolon count / rhetorical-device density metric** | Counts of rule-of-three/tricolon constructions per document, used as a stylistic-forensic marker distinguishing LLM from human prose. |
| **Em-dash frequency** | Simple punctuation-frequency count per document/corpus, tracked over time as an LLM-adoption-correlated marker. |
| **Stylometric clustering (e.g., PCA/embedding-based authorship clustering)** | Measures how tightly a corpus of texts clusters by putative author/model in stylistic feature space; used to quantify homogenization. |
| **Lexical diversity metrics (e.g., type-token ratio and variants)** | Standard corpus-linguistics measure of vocabulary variety, used to compare LLM vs. human/L2 essay diversity. |
| **AI-disclosure label manipulation (between-subjects)** | Experimental design: identical text shown to different participant groups with authorship labeled "AI"/"ChatGPT" vs. "human," isolating the causal effect of the label itself on trust/quality ratings. |
| **SWOT analysis (expert panel)** | Qualitative strengths/weaknesses/opportunities/threats framework applied by subject-matter experts to evaluate AI- vs. human-written assessment passages. |

---

## Notes on verification status / gaps

- Item #2 (pupil-dilation cognitive-load claim) could not be traced to a fully resolved citation in this pass — marked UNVERIFIED; the same underlying claim (fluency/perception vs. actual comprehension diverge) is independently and more reliably supported by item #7.
- Item #14's exact journal name for the ScienceDirect homogenization article was not confirmed — verify before formal citation.
- Item #20's author list showed a discrepancy between the WebFetch extraction (Wang, Sturgis, de Kadt) and how it was informally referenced elsewhere in search snippets ("Altay, Nielsen" was a guess on my part, not attributable to any source — retracted; use Wang/Sturgis/de Kadt as extracted from the paper itself, but re-confirm against the arXiv abstract page directly).
- Item #23's exact journal title (beyond "PMC-indexed, PMID 38881953") could not be confirmed — the PMC page returned a bot-check page rather than content during fetch.
- No peer-reviewed study was found specifically measuring standards-body (IETF/W3C/ISO) recipient reactions to AI-generated prose in deliberation — flagged as an open gap, not filled with an invented source.
- No controlled study was found on open-source mailing-list (non-code, i.e., prose/discussion) reactions to LLM-generated text specifically — flagged as an open gap.
