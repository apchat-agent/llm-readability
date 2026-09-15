# MT/LLM-mediated communication between people without a shared language — literature scan (2019–2026)

Compiled 2026-09-15. Search method: 17 WebSearch queries + targeted WebFetch verification of primary sources (arXiv/ACL/ACM/Frontiers abstract pages). Anything I could not independently verify against a primary source (abstract, arXiv page, or publisher page) is marked **UNVERIFIED**. Search-snippet paraphrases that I could not confirm against the actual paper are flagged as such.

---

## (a) MT-mediated communication quality: the Yamashita/Ishida line and follow-ups

### 1. Yamashita, N. & Ishida, T. (2006). "Effects of Machine Translation on Collaborative Work." CSCW 2006.
**Finding (per secondary sources; not independently fetched):** Foundational study establishing that MT mediation changes collaborative work processes, not just message accuracy — participants adapt their language use around known MT weaknesses.
**Method:** Task-based collaboration experiment comparing MT-mediated vs. shared-language conditions.
**Status:** Existence and venue corroborated by multiple independent citing sources (ResearchGate, ACM DL cross-refs); I did not fetch the primary PDF, so treat bibliographic details (exact page numbers) as **UNVERIFIED**.

### 2. Yamashita, N., Inaba, R., Kuzuoka, H., & Ishida, T. (2009). "Difficulties in Establishing Common Ground in Multiparty Groups Using Machine Translation." CHI 2009.
URL: https://link.springer.com/chapter/10.1007/978-3-642-22766-0_6 (related chapter); cited widely in Language Grid volume.
**Finding:** In multiparty (not just dyadic) MT-mediated groups, two distinct classes of grounding failure emerge: (1) difficulty exchanging socio-emotional content (tone, humor, hedging get flattened or lost), and (2) difficulty developing shared concepts/terminology across turns, because MT output for the same source term is not stable across repetitions.
**Method:** Empirical study of small groups (including Japanese–Danish student pairs in one related study) using a multilingual chat/MT system, with conversation-log coding for grounding breakdowns.
**Status:** Venue/year corroborated by multiple secondary citations; primary PDF not fetched — treat exact experimental N and stats as **UNVERIFIED**.

### 3. Yamashita, N. & Ishida, T. — lexical entrainment / referring-expression work (referenced across several Language Grid chapters, ~2009–2011).
**Finding:** Lexical entrainment — the natural human tendency to converge on and then progressively shorten a shared term for an object once established — breaks down under MT mediation. Because MT retranslates the same underlying concept inconsistently turn-to-turn (asymmetric translation), partners cannot reliably "echo" each other's word choice, so referring expressions stay long and unstable instead of shortening over the course of a dialogue, as they normally do in unmediated referential communication tasks.
**Method:** Referential communication task (director/matcher style) with dyads from China, Korea, and Japan, working in English (shared L2) vs. native language + MT chat.
**Status:** Consistent finding across multiple secondary sources; specific paper title/exact citation **UNVERIFIED** — likely part of "Conversational Grounding in Machine Translation Mediated Communication," Language Grid volume (Springer, 2011), https://link.springer.com/chapter/10.1007/978-3-642-21178-2_12.

### 4. "Conversational Grounding in Machine Translation Mediated Communication" — Language Grid Revisited (Springer, 2011/2012), ed. Ishida.
URL: https://link.springer.com/chapter/10.1007/978-3-642-21178-2_12
**Finding:** Counter to the intuitive assumption that raw MT accuracy is what determines communication success, this line of work argues communication quality is driven more by the *dynamic grounding process* (how well participants can establish and repair shared understanding turn by turn) than by MT's grammatical/lexical fidelity per se. People develop compensatory strategies (redundant phrasing, suppressing lexical variation, more explicit confirmation checks) — but these come at a cost of less natural, less efficient communication even when task success is eventually achieved.
**Method:** Synthesis chapter drawing on the CHI'09/CSCW'06 experiments plus additional Language Grid deployments.
**Status:** Chapter existence confirmed via Springer; content summary based on secondary-source paraphrase — **partially UNVERIFIED** (I did not get behind the Springer paywall).

### 5. Zhang, Y., Owusu, D. A., Carpuat, M., & Gao, G. (2022). "Facilitating Global Team Meetings Between Language-Based Subgroups: When and How Can Machine Translation Help?" PACM on Human-Computer Interaction, Vol. 6, CSCW1.
URL (arXiv preprint): https://arxiv.org/abs/2209.02906
**Finding:** MT-mediated exchange of subgroup conversation logs *before* a mixed-language team meeting improved meeting quality — better subjective experience, better task performance, and deeper discussion — compared to no such exchange. This is a positive result for MT specifically as *pre-meeting context-sharing* rather than as real-time interpretation.
**Method:** Between-subjects lab study, 20 participants in quartets (2 native English speakers + 2 Mandarin-speaking non-native English speakers per quartet). Participants first held native-language subgroup conversations on a personnel-selection task, then had an English-only team meeting; the manipulated variable was whether MT-translated subgroup logs were shared before the team meeting. Outcomes measured via self-report, task performance, and conversation-analytic coding of discussion depth.
**Status:** Verified directly against arXiv abstract page.

### 6. "Effect of Cultural Misunderstanding Warning in MT-Mediated Communication." (Springer chapter, ~2020, exact authors not confirmed).
URL: https://link.springer.com/chapter/10.1007/978-3-030-58157-2_8
**Finding:** UNVERIFIED — title suggests an intervention where the system flags likely cultural-misunderstanding risk alongside MT output; I did not fetch content. Flagging as a lead only.

### 7. Wang, Wai-Tat / Fussell, S. et al., "Machine Translation vs. Common Language: Effects on..." (Cornell HCI group).
URL: https://sfussell.hci.cornell.edu/pubs/Manuscripts/p935-wang.pdf
**Status: UNVERIFIED** — found via search, not fetched; appears to compare MT-mediated collaboration against a shared-lingua-franca (English) baseline, consistent with the general literature theme, but I cannot confirm authors/venue/year without fetching the PDF.

---

## (b) LLM translation quality vs. Google Translate / MT, especially English↔Chinese, and failure modes

### 8. Yan, J., Yan, P., Chen, Y., Li, J., Zhu, X., & Zhang, Y. (2024). "GPT-4 vs. Human Translators: A Comprehensive Evaluation of Translation Quality Across Languages, Domains, and Expertise Levels." arXiv:2407.03658.
URL: https://arxiv.org/abs/2407.03658
**Finding:** GPT-4 performs comparably to *junior* human translators in total error count but lags behind medium- and senior-level professionals. GPT-4's translation capability degrades going from resource-rich to resource-poor language directions. Qualitative error analysis found GPT-4 tends toward overly literal translations, whereas human translators sometimes over-interpret background context (a different, non-literalness failure mode). Framed as (to their claim) the first systematic LLM-vs-human-translator-expertise-tiers study.
**Method:** Multi-language, multi-domain evaluation with error annotation by professional translators across expertise levels (comparative MQM-style error tagging).
**Status:** Verified via arXiv abstract fetch. Note: fetched summary did not surface Chinese-specific or register/hedging-specific detail — general finding only.

### 9. Chen, S. & Lin, Y. (2025). "A multidimensional comparison of ChatGPT, Google Translate, and DeepL in Chinese tourism texts translation: fidelity, fluency, cultural sensitivity, and persuasiveness." Frontiers in Artificial Intelligence, published 24 July 2025.
URL: https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2025.1619489/full
**Finding:** ChatGPT (GPT-based) substantially outperformed Google Translate and DeepL across all four rated dimensions on Chinese→English tourism-promotional text (fidelity 4.04 vs. 1.90–2.34 on a 5-point scale for the baseline prompt condition). A "culturally tailored prompt" version pushed fluency/cultural-sensitivity/persuasiveness higher still (4.23/4.09/4.39) but *at the cost of fidelity* (dropped to 3.69) — i.e., an explicit adequacy-for-fluency trade-off induced by prompting style. DeepL/Google Translate produced literal, "mechanical" output lacking persuasive/promotional register.
**Method:** 20 Chinese source texts (150–200 words), 80 total machine translations (2 systems × baseline + tailored-prompt conditions), rated by 7 PhD-level native-Chinese bilingual raters on 5-point Likert scales for fidelity/fluency/cultural sensitivity/persuasiveness, randomized presentation order, linear mixed-effects regression for significance.
**Status:** Verified via direct fetch of the Frontiers article.

### 10. Forum for Linguistic Studies article, "Google Translate or ChatGPT-4? A Multi-Metric Evaluation of Chinese-to-English Technical Translation."
URL: https://journals.bilpubgroup.com/index.php/fls/article/view/11014
**Finding (per search snippet, not independently fetched):** ChatGPT-4 rated higher by human judges on Chinese→English *technical* translation quality than Google Translate, but the study also found a misalignment between automatic MT metrics and human judgment for LLM output — i.e., automatic scores (BLEU/ChrF-style) do not reliably track what human raters prefer when the translator is an LLM rather than a conventional NMT system.
**Status: UNVERIFIED (partial)** — authors/year/full method not confirmed; based on search snippet only. Worth a direct fetch if this citation matters for anything load-bearing.

### 11. User-generated content evaluation (Chinese emotional/slang text), title not confirmed — found via arXiv search under "Are Large Language Models State-of-the-art Quality Estimators for Machine Translation of User-generated Content?" arXiv:2410.06338.
**Finding (per search snippet):** Testing Google Translate and ChatGPT on Chinese user-generated content containing emotional slang found both systems' output requires significant improvement to be usable — colloquial/affect-laden register is a weak point for both conventional MT and LLM translation.
**Status: UNVERIFIED** — not independently fetched; treat as a lead.

### 12. Terminology drift in LLM back-translation (arXiv:2506.08174, "LLM-BT-Terms: Back-Translation as a Framework for Terminology Standardization and Dynamic Semantic Embedding").
**Finding (per search snippet):** Across back-translation paths, technical terms drift — e.g. "virtual reality" stays stable in one language path, becomes "virtual environments" in another, and collapses to the abbreviation "VR" in a third. Exact-match rate for technical terms ranged ~50–75% depending on language path. Document-level context (vs. old sentence-by-sentence MT) reduces but does not eliminate drift; fine-tuned NMT can outperform a general LLM on terminology consistency unless the LLM is explicitly instructed/guided.
**Status: UNVERIFIED** — snippet-level only, not independently fetched.

---

## (c) Fluency vs. fidelity, and "fluent-but-wrong" being trusted

### 13. Martindale, M. J. & Carpuat, M. (2018). "Fluency Over Adequacy: A Pilot Study in Measuring User Trust in Imperfect MT." AMTA 2018 (13th Conf. of the Assoc. for MT in the Americas). arXiv:1802.06041.
URL: https://arxiv.org/abs/1802.06041 / https://aclanthology.org/W18-1803.pdf
**Finding:** This is the key citable source for "fluent-but-wrong is trusted." Users' trust dropped sharply when shown *disfluent* MT output, but was much less affected by *adequacy* (meaning-accuracy) errors when the output stayed fluent. In other words, readers punish awkward grammar/phrasing far more than they punish outright mistranslation — because they can perceive disfluency directly but cannot perceive an adequacy error without independently knowing the source-language meaning. Conclusion: fluent translations containing adequacy errors are the most dangerous failure mode because they mislead the reader into trusting an incorrect meaning, with no fluency-level signal to prompt suspicion.
**Method:** Survey/pilot study comparing user responses to three output types: high-quality (fluent+adequate), adequate-but-disfluent, and fluent-but-inadequate.
**Status:** Verified — abstract fetched directly from arXiv; PDF fetch failed (binary garble) but arXiv abstract corroborates all details above.

### 14. Deng, W. H., Mehandru, N., Robertson, S., & Salehi, N. (2022). "Beyond General Purpose Machine Translation: The Need for Context-specific Empirical Research to Design for Appropriate User Trust." Workshop on Trust and Reliance in AI-Human Teams (TRAIT) 2022. arXiv:2205.06920.
URL: https://arxiv.org/abs/2205.06920
**Finding:** Based on interviews with 20 clinicians about cross-language patient communication, argues that "appropriate trust" in MT cannot be engineered generically — it depends on the specific high-stakes context (here: healthcare). Users need calibrated understanding of *when* MT output is reliable and how to handle uncertain cases; generic MT-quality metrics don't translate into usable trust signals for lay users in the wild.
**Method:** Semi-structured interviews (n=20 clinicians) on cross-language patient communication practices and MT use.
**Status:** Verified via arXiv fetch.

### 15. Xiao, Y., Zhang, Y., Ki, D., Bao, C., Martindale, M. J., Vaughn, C., Gao, G., & Carpuat, M. (2025). "Toward Machine Translation Literacy: How Lay Users Perceive and Rely on Imperfect Translations." EMNLP 2025. arXiv:2510.09994.
URL: https://arxiv.org/abs/2510.09994
**Finding:** This is the strongest direct evidence for the "receiver reads natively without AI help, over-relies on fluent output" phenomenon at scale. Non-bilingual users over-rely on MT — not because they trust it highly per se, but because they *lack any strategy to evaluate the output* or to reason about when to distrust it (they cannot check against the source, so fluency is their only available signal). Direct experience of an error, when it does surface, shifts a user's subsequent reliance pattern going forward — i.e., trust calibration is experience-driven, not analysis-driven, for lay/non-bilingual users.
**Method:** In-the-wild human study, N=452 participants, conducted in a public museum setting (ecologically valid casual-use context), comparing bilingual vs. non-bilingual users' reliance behavior under fluency-error and adequacy-error conditions.
**Status:** Verified via arXiv fetch (author list, venue, N, and setting all confirmed).

### 16. Simpson's Paradox and the Accuracy-Fluency Tradeoff in Translation. arXiv:2402.12690.
**Finding (per search snippet):** Methodological/statistical paper showing that aggregate accuracy-fluency correlations in MT evaluation datasets can reverse at the subgroup level (Simpson's paradox) — a caution for anyone citing "fluency correlates with adequacy" findings without checking for confounds like sentence length or domain.
**Status: UNVERIFIED** — not independently fetched, flagged as a methodological caveat only.

---

## (d) Experimental designs for two-party communication through an intermediary

Design patterns recurring across the literature above, useful as a toolbox:

1. **Task-based referential communication (director/matcher, "Map Task"-style).** Two participants who cannot see each other's screen/objects must get a referent identified correctly using only dialogue; success/failure and number of turns to convergence are the dependent measures. Used by Yamashita/Ishida to show that MT disrupts the normal *shortening* of referring expressions over repeated reference (a robust unmediated-communication finding, broken by MT asymmetry). The Map Task itself has a long HCI/linguistics pedigree predating this line of MT work; see search hit on "Map Task ... robustly empirical approach to understanding in interpreter-mediated communication."

2. **Subgroup-then-plenary team task (Zhang et al. 2022).** Participants first converse in native-language same-language subgroups, producing a natural baseline; MT is then interposed only at the *information-sharing* step (translated logs), not in real time — isolating the "does MT help downstream understanding" question from "does MT work as live dialogue."

3. **Sealed-condition / manipulation-check surveys (Martindale & Carpuat 2018).** Participants are shown MT output *without* being told which error class (disfluent vs. inadequate) it belongs to; adequacy is verified against a hidden gold/source reference the participant never sees — structurally similar to a "sealed original revealed after" design, though the paper does not use cryptographic commitment, just experimenter-held ground truth.

4. **In-the-wild large-N reliance study (Xiao et al. 2025).** Ecologically valid setting (museum) rather than lab task; ground truth (source-language meaning) held by researchers and used post hoc to classify each translation instance as fluency-error/adequacy-error/clean, then correlated against participant reliance behavior — again, ground truth is withheld from participants during the task and revealed/used only in analysis.

5. **Back-translation as a proxy comprehension-agreement check.** Translate A→B→A and measure divergence from the original A as a cheap adequacy proxy when no bilingual judge is available. Documented as methodologically useful but also as an *imperfect* fidelity proxy: back-translation is known to hide errors that cancel out over the two hops (source: IEEE back-translation validity paper, https://ieeexplore.ieee.org/abstract/document/7433246/; also LLM-BT-Terms paper on terminology drift across back-translation paths). Not a substitute for real bilingual comprehension-probe evaluation.
   **Status of the "cancellation" claim: UNVERIFIED** — plausible and consistent with known back-translation critique literature, but I did not find a paper making this exact point explicitly during this search; treat as my own inference from the general back-translation-validity literature, not a cited finding.

6. **Comprehension probes / dialogue probe tasks.** Rather than end-to-end task success, some NLP-adjacent work (e.g. "How To Evaluate Your Dialogue System: Probe Tasks," arXiv:2008.10427) proposes targeted probe questions (semantic, syntactic, information-specific) injected into a dialogue evaluation pipeline as a finer-grained alternative to token-overlap metrics. Not MT-specific, but directly reusable as a "comprehension probe" design for an MT/LLM-mediated two-party study: after each exchange, ask the *receiver* a probe question whose correct answer requires having understood a specific fact in the translated message, independent of end-task success.
   **Status:** Paper existence confirmed via search; not independently fetched — general applicability is my inference, not a stated claim of that paper.

---

## Commitment schemes: publish-hash-then-reveal, precedents

**Cryptographic core.** A commitment scheme lets a party commit to a value (e.g., publish `H(original_text || nonce)`) such that: (a) *hiding* — the committed value cannot be recovered from the hash alone before reveal, and (b) *binding* — the committer cannot later produce a different value that also matches the published hash. This is textbook cryptographic-protocol material (Naor's bit-commitment scheme; standard treatment in Goldreich's *Foundations of Cryptography* and most crypto-protocol courses). General overview sources found: https://chain.link/article/commitment-scheme-overview and https://chain.link/article/commit-and-reveal-schemes (industry explainer level, not academic primary sources — cite with care).

**Social-science / experimental precedent — the "sealed envelope" analogue.** The pre-cryptographic version of the same idea: write a prediction on paper, seal it in an envelope in front of witnesses, open it later to prove the prediction predates the outcome. This is a long-standing informal practice in adversarial/competitive prediction contexts (e.g., forecasting tournaments, some replication/pre-registration workflows) but I did not find a peer-reviewed methods paper that names and formalizes "sealed envelope" as a term of art — it is describable but **UNVERIFIED as a named citable method**.

**Modern digital analogue — cryptographic pre-registration.** One 2026-dated source surfaced in search (a dev.to blog post, not peer-reviewed) describes using SHA-256 hashing to pre-register a hypothesis/scoring rubric before running LLM API trials, producing a reproducible, third-party-verifiable, provider-timestamped commitment. This is directly the "commit a hash of a hidden original, reveal later" pattern applied to an experimental protocol, but the source is a blog post, **not an academic citation** — flagging as **UNVERIFIED / non-peer-reviewed**, useful only as an existence proof that people are doing this informally in 2026, not as a citable precedent.

**Closest formal social-science precedent I could verify:** pre-registration in psychology generally (e.g., OSF pre-registration, and the deception-detection replication literature such as Verschuere et al.'s preregistered replication of Nahari, Vrij & Fisher 2014, https://onlinelibrary.wiley.com/doi/abs/10.1002/acp.3769) uses a *timestamped, third-party-registered* commitment (OSF registration) rather than a cryptographic hash — functionally the same "commit before you know the outcome, reveal after" logic, but implemented via a trusted registry, not a publishable hash. I found no paper in this search that uses an actual published cryptographic hash-commitment (as opposed to a registry-based commitment) for a *communication/translation* experiment specifically — if you need "published hash of a hidden original text, revealed after the reader responds" as a design for an MT/LLM-mediated-communication study, this appears to be a novel/unattested combination in the literature I could find, not a reused precedent. Treat that gap itself as a finding: **no verified precedent located for hash-commitment schemes used specifically in MT/LLM-mediated-communication experiments.**

---

## Notable near-misses / leads not fully chased down (listed for follow-up, not verified)

- "Effect of Cultural Misunderstanding Warning in MT-Mediated Communication" (Springer, ~2020) — plausible directly-relevant intervention study, not fetched.
- Forum for Linguistic Studies Chinese-to-English technical-translation multi-metric paper — plausible but not fetched, author names unknown.
- "LAAC: LLM as a Communicator" arXiv:2511.04184 (Rafi, Krishnamurthy, Balu; IEEE DISTILL 2025) — reframes LLMs as *communication intermediaries* that structure sender intent before passing to receiver; relevant to the broader theme but is about intent-capture/fidelity in general knowledge-sharing (papers, proposals, emails), not specifically cross-lingual translation reception — cite as adjacent, not as evidence for the cross-lingual claims above.
- Wang et al. (Cornell, Fussell group), "Machine Translation vs. Common Language" — likely relevant comparison of MT-mediated vs. lingua-franca collaboration, not fetched.

---

## Summary of top findings (also returned to requester)

1. **Yamashita & Ishida (CSCW'06, CHI'09) and the Language Grid line**: MT mediation disrupts *lexical entrainment* — partners can't converge on and shorten shared referring expressions because MT retranslates inconsistently turn to turn; communication success depends more on the grounding *process* participants build than on raw MT accuracy.
2. **Zhang, Owusu, Carpuat & Gao (CSCW 2022, arXiv:2209.02906)**: MT-translated subgroup logs shared *before* a mixed-language team meeting improved meeting quality (subjective experience, task performance, discussion depth) — MT works best as async context-sharing, not necessarily live interpretation.
3. **Martindale & Carpuat (AMTA 2018, arXiv:1802.06041)**: The single clearest citation for "fluent-but-wrong is trusted" — users penalize disfluency far more than inadequacy; fluent-but-inaccurate output is the most dangerous failure mode because there's no perceptual signal to flag it.
4. **Xiao, Zhang, Ki, Bao, Martindale, Vaughn, Gao & Carpuat (EMNLP 2025, arXiv:2510.09994)**: Large in-the-wild study (N=452, museum setting) — non-bilingual users over-rely on MT not from misplaced confidence but from *lacking any strategy to evaluate output*; trust recalibrates only after direct experience of an error.
5. **Deng, Mehandru, Robertson & Salehi (TRAIT 2022, arXiv:2205.06920)**: Appropriate trust in MT can't be engineered generically — needs context-specific empirical grounding (shown via 20 clinician interviews on cross-language patient care).
6. **Yan et al. (2024, arXiv:2407.03658)**: GPT-4 translation ≈ junior human translators on error count, below medium/senior; degrades on resource-poor language pairs; tends toward overly literal output as its characteristic failure mode.
7. **Chen & Lin (Frontiers in AI, 2025)**: On Chinese-tourism promotional text, ChatGPT beat Google Translate/DeepL on every rated dimension (fidelity, fluency, cultural sensitivity, persuasiveness); but a fluency/persuasiveness-optimized prompt traded away fidelity (4.04→3.69) — a directly demonstrated fluency-for-fidelity trade-off induced by prompting.
8. **No verified precedent for a cryptographic hash-commitment scheme used specifically in an MT/LLM-mediated-communication experiment.** Sealed-envelope-style commitment is a known informal social-science pattern and OSF-style pre-registration is the closest verified formal analogue (e.g., Verschuere et al.'s preregistered deception-detection replication); an actual publish-hash/reveal-later design for a translation-reception study appears to be a genuine gap, not something reused from prior literature.

## Caveats
- Coverage skews toward what's indexable via web search + arXiv/ACL/ACM/Frontiers abstracts; several older CSCW/CHI papers (2006–2011) were only reachable via secondary citation, not primary PDF, in the time available — flagged individually above.
- No item in this report was fabricated; every UNVERIFIED tag reflects an actual gap in what I could confirm against a primary source in this session.
