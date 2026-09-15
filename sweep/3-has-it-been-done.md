# Has this experiment been done? Literature/community search

**Proposed design (recap):** Two people share no common language. Each writes in their own language; an LLM agent translates/composes the outgoing message; the *receiver* reads the translated message natively, with **no AI assistance on the receiving end**. English originals are hash-sealed and revealed only at the end. Goal: does LLM-mediated text become harder to comprehend/trust for the unaided receiver, evaluated on a real technical-document discussion.

Search performed: 15 WebSearch queries + 1 WebFetch, spanning HCI/CSCW/AI-MC literature, IETF process documents, and critiques of the "AI enables equal participation" claim. Dates covered 2019–2026 (note: several 2026 items are in-corpus search results dated ahead of my training cutoff — flagged UNVERIFIED where I could not independently confirm venue/DOI).

---

## (a) LLM/MT-mediated asynchronous human-human discussion — HCI/CSCW/ACL

### 1. Jakesch, French, Ma, Hancock, Naaman — "AI-Mediated Communication: How the Perception that Profile Text was Written by AI Affects Trustworthiness" — CHI 2019, Glasgow
- URL: https://dl.acm.org/doi/10.1145/3290605.3300469 ; PDF: https://socialmedialab.sites.stanford.edu/sites/g/files/sbiybj22976/files/media/file/jakesch-chi19-ai-mediated.pdf
- **Method:** Airbnb-style profile-text experiment; participants judged host trustworthiness under different beliefs about AI authorship (individually labeled vs. mixed sets).
- **Finding:** The "Replicant Effect" — mistrust of AI-suspected profiles appeared only when participants believed they were viewing a *mixed* set of AI- and human-written text, not when all profiles were uniformly labeled one way.
- **Relevance:** Foundational AI-MC trust-perception paradigm, but single-language, no translation, no unaided-receiver/blind-then-reveal design, no technical-document task.

### 2. Hancock, Naaman, Levy — "AI-Mediated Communication: Definition, Research Agenda, and Ethical Considerations" — *Journal of Computer-Mediated Communication* 25(1), 2020
- URL: https://academic.oup.com/jcmc/article/25/1/89/5714020
- **Method:** Conceptual/theory paper, not empirical.
- **Finding:** Defines AI-MC along five dimensions (magnitude, media type, optimization goal, autonomy, role orientation) and lays out a research agenda covering psychological, linguistic, relational, and ethical implications. Explicitly flags translation/language-crossing as an AI-MC subtype worth studying but does not run the study.
- **Relevance:** This is the taxonomy paper the proposed experiment would sit inside; it names the gap without filling it.

### 3. Liu, Mittal, Yang, Bruckman — "Will AI Console Me when I Lose my Pet? Understanding Perceptions of AI-Mediated Email Writing" — CHI 2022, New Orleans
- URL: https://dl.acm.org/doi/10.1145/3491102.3517731 ; PDF: https://cs.stanford.edu/~diyiy/docs/chi22_perception.pdf
- **Method:** Large-scale survey + interviews on perceived trust of emails disclosed as AI-assisted, varying transactional vs. interpersonal content.
- **Finding:** Disclosure of AI involvement generally lowered trust, but less so (or even raised it) for interpersonal/emotional content vs. transactional content.
- **Relevance:** Same-language, no translation; useful for the trust-measurement instrument, not for cross-lingual comprehension.

### 4. Robertson & Díaz — "Understanding and Being Understood: User Strategies for Identifying and Recovering From Mistranslations in Machine Translation-Mediated Chat" — ACM FAccT 2022
- URL: https://dl.acm.org/doi/fullHtml/10.1145/3531146.3534638 ; Google Research page: https://research.google/pubs/understanding-and-being-understood-user-strategies-for-identifying-and-recovering-from-mistranslations-in-machine-translation-mediated-chat/
- **Method:** 19 role-play MT-mediated conversations (housing/employment scenarios) across English + one of Spanish, Farsi, Igbo, Tagalog; qualitative interview analysis of how users detect and recover from mistranslation under limited system transparency.
- **Finding:** Users struggle to detect mistranslations, especially subtle ones; recovery strategies are ad hoc and depend heavily on context/relationship; system opacity (not knowing what the other party actually received) is a central friction.
- **Relevance:** **Closest existing empirical match** to the proposed experiment's core mechanic (bilingual dyad, MT/LLM in the middle, real conversational task). Difference: this is live/synchronous role-play chat with pre-scripted scenarios, not an asynchronous real technical-document discussion; it did not seal/reveal English originals for a later comprehension/trust audit; and it used MT systems of the pre-LLM-agent era rather than an LLM agent with translation+composition latitude.

### 5. "Sustaining Human Agency, Attending to Its Cost: An Investigation into Generative AI Design for Non-Native Speakers' Language Use" — CHI 2025
- URL (PDF): https://arxiv.org/pdf/2503.07970 ; ACM: https://dl.acm.org/doi/full/10.1145/3706598.3713626
- **Method:** 45 dyads: one new immigrant (non-native speaker) using MT for English information-seeking, paired with one local native-speaker information-provider. Compared different levels of non-native-speaker control over MT output (accept-as-is, label quality, post-edit).
- **Finding:** Non-native speakers lose agency by default (MT output goes out largely uncontested); giving them ways to intervene (post-editing, quality labels) restores agency but adds cognitive/effort cost — a direct empirical demonstration of the agency-vs-effort tradeoff.
- **Relevance:** **Second-closest prior work.** Directly studies a cross-lingual, MT-mediated *sender* burden in real dyadic interaction with a native-speaker counterpart, and explicitly frames the "cost" question. But: focus is on the *non-native sender's* agency/cost, not on the *native, unaided receiver's* comprehension/trust; and it studies real-world MT (not an LLM agent acting on a technical document, no hash-sealed originals, no explicit trust/comprehension instrument on the receiving end).

### 6. Robertson et al. (and related) — "Translation in the Hands of Many: Centering Lay Users in Machine Translation Interactions" — arXiv 2502.13780 (2025)
- URL: https://arxiv.org/pdf/2502.13780
- **Method:** Survey/position piece centering lay (non-expert) MT users' interaction patterns and needs, building on the FAccT'22 mistranslation-recovery study.
- **Finding:** Argues MT-interaction research should center lay users' actual workflows (uncertainty signaling, trust calibration, backchannel repair) rather than assuming expert/linguist users.
- **Relevance:** Framing/position paper; reinforces that comprehension/trust-of-the-receiver is an underexplored axis relative to translation-quality metrics.

### 7. "Toward Machine Translation Literacy: How Lay Users Perceive and Rely on Imperfect Translations" — arXiv 2510.09994 (2025, UNVERIFIED venue)
- URL: https://arxiv.org/pdf/2510.09994
- **Method:** (from search snippet) studies how lay users without target-language knowledge perceive and calibrate reliance on imperfect MT output.
- **Finding:** UNVERIFIED — could not fetch full text in this pass; search snippets indicate a focus on user reliance/perception calibration under imperfect MT, consistent with a "receiver trust in imperfect translation" angle close to the proposed experiment, but I did not confirm design details (dyadic? technical-document? sealed originals?). Flag for follow-up read.

### 8. Robertson & Díaz — "Agent metaphor for machine translation mediated communication" — IUI 2013
- URL: https://dl.acm.org/doi/10.1145/2449396.2449407
- **Method:** UNVERIFIED in this pass (older, pre-LLM paper; only title/abstract snippet seen) — reportedly explores framing MT as an "agent" in mediated communication and how that framing affects trust/expectations.
- **Relevance:** Conceptually adjacent (the "agent" framing is exactly what the proposed experiment operationalizes — an LLM *agent*, not a raw MT box) but pre-dates LLMs; worth reading in full before citing findings.

### 9. Time to Talk: LLM Agents for Asynchronous Group Communication (Mafia Games) — arXiv 2506.05309 (2025, UNVERIFIED)
- URL: https://arxiv.org/pdf/2506.05309
- **Method:** LLM agents (e.g., Llama-3.1-8B-Instruct) participate as players in asynchronous group text games.
- **Relevance:** Same-language, agents-as-participants (not agents-as-mediators/translators between two specific humans). Not a comprehension/trust study of a human receiver. Low relevance beyond showing async-LLM-agent-comms is an active arXiv theme.

### 10. "Explaining the Reputational Risks of AI-Mediated Communication: Messages labeled as AI-assisted are viewed as less diagnostic of the sender's moral character" — arXiv 2509.09645 (2025/2026, UNVERIFIED venue)
- URL: https://arxiv.org/pdf/2509.09645
- **Relevance:** Extends the Jakesch/Hancock AI-MC trust line; same-language; not fetched in full — UNVERIFIED beyond title.

---

## (b) Standards-body / open-source discussion of AI-written contributions

### 11. Farrell (Trinity College Dublin) & Feng — draft-fengfar-led, "Dealing with LLMs in IETF Discussions" (IETF Internet-Draft, Informational track; version -01 dated 2026-08-06 per fetch)
- URL: https://datatracker.ietf.org/doc/draft-fengfar-led/
- **Method:** Not an experiment — a two-voice position draft: Farrell writes as a skeptical reader, Feng (a non-native English speaker) writes as a practitioner describing his actual LLM-assisted workflow (uses AI to triage volume, stress-test self-formed arguments, produce English drafts, "humans originate / AI executes," retains final accountability).
- **Finding/argument:** Flags reader-side harms of AI-assisted IETF email — excessive positivity, jargon/geometric-abstraction overuse, lack of hedging/uncertainty markers, "walls of text." Explicitly names translation as a potential *benefit* ("could open up participation to many more capable engineers for whom communicating in English is a challenge") but warns this benefit is undercut if faster production correlates with *reduced sender comprehension* of their own output, and that AI-smoothing erodes the reader's ability to recognize an author's authentic "voice" (a trust/reputation cue). Recommends community guidelines over bans; explicitly does **not** propose or report a controlled experiment.
- **Relevance:** This is the single closest *institutional/discourse* document to the proposed experiment's premise (translation as an equalizer, with real doubts about the receiver's side) — but it is argumentative, not empirical, and does not address the unaided-receiver/hash-seal/reveal protocol at all.

### 12. IETF `mailing-list-ai-check` tool (ietf-tools GitHub)
- URL: https://github.com/ietf-tools/mailing-list-ai-check
- **Method:** An automated pipeline (pull via IMAP → extract new-authored text stripping quotes/signatures → score via the Pangram AI-detection API) applied to IETF mailing-list archives.
- **Finding:** A detection/monitoring tool, not a comprehension or trust study; it flags likely-AI-generated text in list traffic but does not measure reader comprehension, trust, or run a controlled receiver-side evaluation.
- **Relevance:** Shows the IETF community is instrumenting *detection* of AI-authored text, one adjacent concern to (but distinct from) the proposed experiment's comprehension/trust question.

### 13. IETF AI-related WGs/lists (AIPREF WG, agent2agent list) — context only
- URLs: https://www.ietf.org/blog/aipref-wg/ ; https://mailarchive.ietf.org/arch/msg/ietf-announce/NC5JYHxCDVWdShCXvlGsoKHecko/
- **Relevance:** These address AI *content-use preferences* (robots.txt-style) and AI-agent *protocol* standardization, not AI-mediated human discussion readability. Background only, not directly on point.

No evidence found of a W3C, IEEE, or ISO document specifically discussing readability/trust of AI-translated or AI-drafted contributions in the way draft-fengfar-led does for IETF; searches did not surface one. UNVERIFIED as absence — could reflect search-term limitations rather than true absence.

---

## (c) Evaluation protocols used in AI-MC studies

Drawing on items above plus two more:

### 14. "Through the Looking-Glass: AI-Mediated Video Communication Reduces Interpersonal Trust and Confidence in Judgments" — arXiv 2603.18868 (2026, UNVERIFIED venue — arXiv ID format is ahead of my training window, treat date/venue as unconfirmed)
- URL: https://arxiv.org/html/2603.18868v1
- **Method (as reported in search snippet):** Two preregistered online experiments testing whether AI-mediated video retouching/background replacement/avatars affect interpersonal trust and lie-detection confidence. Used 5-point Likert scales for judgment confidence and trustworthiness.
- **Relevance:** Good template for the *measurement instrument* (Likert trust/confidence scales, preregistration) the proposed experiment could reuse, but modality is video not cross-lingual text, and it is not receiver-blind-then-revealed.

### 15. Purcell et al. — "People have different expectations for their own versus others' use of AI-mediated communication tools" — *British Journal of Psychology*, 2026 (UNVERIFIED — could not fetch full text, title/venue only from search snippet)
- URL: https://bpspsychub.onlinelibrary.wiley.com/doi/10.1111/bjop.12727
- **Method (snippet):** Confirmatory preregistered follow-up; participants are less accepting of secret vs. disclosed AI-mediated-communication use by others than by themselves.
- **Relevance:** Establishes a disclosure-asymmetry effect the proposed experiment's "seal and reveal at the end" design directly operationalizes (participants evaluate the exchange NOT knowing AI was involved in composing the other side's message, until reveal) — i.e., prior work supports that this reveal-timing manipulation matters and should be expected to produce a measurable shift.

**General protocol pattern found across AI-MC studies:** (1) manipulate AI-involvement belief/disclosure (blind vs. told vs. mixed-set) as the independent variable; (2) measure trustworthiness / perceived effort / perceived authenticity via Likert scales, sometimes borrowed from validated instruments (e.g., competence/caring/goodwill sub-scales); (3) increasingly, studies are preregistered (OSF/AsPredicted) with confirmatory + exploratory splits; (4) comprehension is measured less consistently than trust — most AI-MC studies measure *trust/perception*, few measure objective comprehension accuracy of the receiver. This is a specific gap the proposed experiment's comprehension-check component would fill.

---

## (d) Critiques of "AI lets non-native speakers participate on equal terms"

### 16. "Sustaining Human Agency, Attending to Its Cost" (CHI 2025, item #5 above) — direct empirical critique
- **Finding:** Default MT interfaces strip non-native speakers of control over their own representation; restoring agency (post-editing, quality-labeling) costs real effort. This is the sharpest empirical rebuttal found to the "equal terms" claim, though it centers the sender's cost, not the receiver's.

### 17. draft-fengfar-led (item #11) — direct discourse-level critique
- **Finding:** Warns explicitly that the translation benefit "risks being undermined if accelerated production correlates with reduced sender comprehension" — i.e., speed gained by delegating to AI may be paid for by the *sender* not fully understanding/owning their own outgoing argument, a different but related cost than the receiver-side cost the proposed experiment targets.

### 18. Machine Translation / Language Justice commentary (assorted, lower confidence)
- "Language Justice and Machine Translation on Social Media," *Modern Languages Open*: https://modernlanguagesopen.org/articles/10.3828/mlo.v0i0.466 — UNVERIFIED (snippet only): argues equitable participation requires more than raw MT availability (script support, primary-language tooling access).
- ATA "The Mother-Tongue Principle: Hit or Myth?": https://www.atanet.org/resources/the-mother-tongue-principle-hit-or-myth/ — professional-translation norm (translate only into one's native/equally-competent language) that is the inverse of what LLM-mediated dyadic exchange does (each side writes outward in their *own* language and lets the LLM translate *into* the other's, meaning the LLM is always translating into what is, for it, an arbitrary target — this norm doesn't directly transfer but is relevant background for "who should be trusted to produce the final receiver-facing text").
- I did **not** find a paper making the specific "the receiver bears the cost of comprehension while the sender gets the credit for participation" argument in those exact terms. The closest is the sender-side agency-cost finding (#5/#16) plus draft-fengfar-led's reader-trust-erosion argument (#1/#11) — but nobody found explicitly frames it as a *redistribution* from sender-effort to receiver-effort the way the proposed experiment's question does. This looks like a genuine articulation gap.

---

## Closest prior work and what is still novel about the proposed experiment

**Has "this experiment" been done? No — not as specified. Pieces of it have been done separately, and it would be dishonest to claim novelty across the board.**

The two closest matches:

1. **Robertson & Díaz, FAccT 2022** (item #4) — real bilingual dyads, MT-mediated, qualitative study of comprehension breakdown and recovery. Missing vs. proposed: asynchronous *technical-document* discussion (theirs was scripted housing/employment role-play); LLM-agent-level translation+composition (theirs used earlier MT systems, less agentic); no hash-sealed original / blind-then-reveal comprehension-and-trust instrument; no explicit "receiver never gets AI help" isolation (their study was about detecting/recovering from errors, which implies participants *were* actively trying to compensate, i.e., not a clean unaided-receiver condition).

2. **"Sustaining Human Agency, Attending to Its Cost," CHI 2025** (item #5) — real cross-lingual dyads (immigrant + native-speaker local), explicit agency-vs-cost framing, real information-seeking task. Missing vs. proposed: centers the *non-native sender's* agency/cost rather than the *native receiver's* comprehension/trust; not a technical document; no seal/reveal design; MT not an LLM agent with drafting latitude.

What appears genuinely novel about the proposed design, based on this search:
- **Symmetric two-LLM-agent-mediated design** (both directions mediated, not one side using MT to reach a native speaker) — found nothing symmetric; all prior work has an MT/AI on one side of the exchange only (non-native sender → native reader), not both sides writing/reading only in their own language.
- **Unaided receiver as the deliberately isolated measurement target** — prior work either has the receiver co-present with the sender's effort to communicate (interactive repair, as in FAccT'22) or centers the sender's experience (CHI'25 agency paper). No prior study found that specifically walls off the receiver from any AI assistance and measures *their* unaided comprehension/trust as the primary dependent variable.
- **Hash-sealed English originals revealed only at the end** — a provenance/blinding mechanism not seen in any AI-MC or MT-mediated-chat paper surveyed. This is closer to methodology used in some preregistered AI-MC trust studies (disclosure-timing manipulations, item #15) but the specific "cryptographically seal the ground-truth text and reveal after independent evaluation" mechanic was not found anywhere in the HCI/CSCW/ACL literature searched.
- **A real, adversarial-free, single real technical document as the shared task**, evaluated post-hoc by both parties once secrecy is lifted — closest analog is IETF's own draft-fengfar-led discourse, which discusses exactly this scenario (translation opening standards participation) but only as argued opinion, explicitly declining to run an experiment ("Rather than experiments, the draft recommends...").

**Bottom line:** The IETF community has *named* this exact concern in prose (draft-fengfar-led) and CHI/CSCW has *adjacent* empirical pieces (mistranslation recovery, sender-side agency cost, AI-MC trust-disclosure effects), but no source found runs the specific controlled protocol described — bidirectional single-language-each-side LLM-agent mediation, blind unaided-receiver evaluation, and sealed-then-revealed ground truth, applied to a real technical document. If it exists, it is either unpublished, very recent/unindexed, or outside the venues and keywords searched here.

---

## Notes on verification confidence
- High confidence (fetched full abstract/content or cross-confirmed across multiple independent search results): items #1, #2, #3, #4, #5, #11, #12.
- Medium confidence (title + snippet only, DOI/URL resolves, plausible venue): items #6, #10, #14, #15, #16(dup of #5).
- UNVERIFIED (could not confirm venue, date plausibility, or full content in this pass — flagged inline): items #7, #8, #9, #14 (date), #15 (date), the "language justice" and ATA mother-tongue items in section (d).
- Some arXiv IDs returned by search (e.g., 2603.x, 2607.x, 2605.x, 2602.x, 2608.x, 2609.x) correspond to 2026 submission windows that are near or at the edge of plausibility for search-engine indexing vs. my January 2026 knowledge cutoff — I'm reporting them as found by live WebSearch, but their bibliographic details (exact author list, exact venue) were not independently cross-checked beyond the URL/title snippet and should be re-verified before citing in any publication.
