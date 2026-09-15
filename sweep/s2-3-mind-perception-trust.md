# LLM->human boundary: social cognition, mind perception, trust and affect

Field slice: theory-of-mind attribution, algorithm aversion / AI-label penalty, sincerity-warmth-competence,
effort heuristics, empathy/disclosure, reciprocity, uncanny-valley-of-mind, machine heuristic, detection/suspicion.

## References

- **Jakesch, Hancock, Naaman. "Human heuristics for AI-generated language are flawed." PNAS, 2023. https://doi.org/10.1073/pnas.2208839120.**
  Six experiments (N=4,600) show people cannot reliably distinguish AI-generated verbal self-presentations (professional, hospitality, dating) from human-written ones, and the heuristics they *think* they use to tell the difference (e.g. "AI is more formal/analytical") are actively wrong — applying them makes detection worse than chance in some conditions. This is the anchor paper for "readers cannot tell, and their folk theory of what AI-written text looks like misfires," which matters because downstream trust/sincerity effects (below) depend entirely on *disclosed* or *suspected* authorship, not on any real textual signature.
  open-access: yes — https://www.pnas.org/doi/epdf/10.1073/pnas.2208839120

- **Mieczkowski, Hancock, Naaman, Jung, Hohenstein. "AI-Mediated Communication: Definition, Research Agenda, and Ethical Considerations." Proceedings of the ACM on Human-Computer Interaction (CSCW1), 2021. https://doi.org/10.1145/3449091.**
  Defines AI-mediated communication (AI-MC) as interpersonal communication where an AI system modifies, augments, or generates content on a sender's behalf, and lays out how this differs structurally from both human-human and human-machine communication: the receiver's model of "who is speaking" becomes probabilistic (sender, AI, or blend), and classic CMC constructs (warranting, hyperpersonal effects) need updating because the *source of agency* is itself ambiguous. Framing paper, not an experiment; sets the vocabulary (source attribution, agency, perceived authenticity) used by nearly every later empirical paper in this list.
  open-access: yes — https://dl.acm.org/doi/pdf/10.1145/3449091

- **Hohenstein, Jung. "AI as a moral crumple zone: The effects of AI-mediated communication on attribution and trust." Computers in Human Behavior, 2020. https://doi.org/10.1016/j.chb.2019.106190.**
  Controlled dyadic chat experiment: when an AI (smart-reply) suggestion is visibly involved in a conversation that goes badly, participants shift blame from their human partner onto the AI ("moral crumple zone"), which paradoxically *raises* trust in the human partner relative to no-AI conversations. Shows the LLM->human boundary is not just about the message's content but about how a visible AI intermediary reallocates responsibility and repairs (rather than only damages) interpersonal trust — the opposite direction from the disclosure-penalty literature below.
  open-access: unknown — no free PDF found.

- **Purcell, Jakesch, Dong, Nussberger, Köbis. "Writing with AI boosts trust-building efficiency." iScience, 2025. https://doi.org/10.1016/j.isci.2025.114092.**
  Trust-game / message-composition experiment: participants using LLM predictive-text assistance to write trust-building messages reach the same or higher partner trust *faster* (fewer words, less time) than unassisted writers, and disclosure of AI assistance does not significantly reduce the trust gained. Direct follow-up to the Jakesch line; narrows the "AI penalty" to specific genres — trust-building/negotiation opening messages seem to escape the sincerity penalty seen in condolence/apology contexts.
  open-access: yes — https://www.cell.com/iscience/fulltext/S2589-0042(25)00114-2

- **Gray, Gray, Wegner. "Dimensions of Mind Perception." Science, 2007. https://doi.org/10.1126/science.1134475.**
  Foundational factor-analytic study (11 characters incl. humans, animals, robots, God) finds two independent dimensions people use to perceive minds: Agency (planning, self-control, communication, thought) and Experience (capacity to feel pain, pleasure, emotion). Machines/robots in this and follow-up work are perceived as high-Agency, low-Experience — the theoretical backbone for why an LLM-authored message can be judged competent (agency) yet unfeeling (no experience), which is exactly the split later papers find between competence and warmth/sincerity ratings of AI text.
  open-access: unknown — publisher paywalled; no free PDF found.

- **Gray, Wegner. "Feeling robots and human zombies: Mind perception and the uncanny valley." Cognition, 2012. https://doi.org/10.1016/j.cognition.2012.06.007.**
  Experimentally manipulating perceived Experience (vs. Agency) in a robot description makes people rate it as more unsettling; a human described as lacking Experience ("human zombie") is equally unsettling. Establishes "uncanny valley of mind": discomfort tracks a mismatch between an entity's category (person vs. machine) and the mind-dimensions attributed to it, not appearance per se. Relevant to why an LLM message that *reads* as emotionally attuned (high apparent Experience) from a known-machine source can trigger unease/distrust once the source is revealed — a text-only uncanny-valley-of-mind effect.
  open-access: unknown — no free PDF found.

- **Epley, Waytz, Cacioppo. "On Seeing Human: A Three-Factor Theory of Anthropomorphism." Psychological Review, 2007. https://doi.org/10.1037/0033-295x.114.4.864.**
  Foundational theory: anthropomorphism (attributing humanlike mind to a nonhuman agent) is driven by elicited agent knowledge (how easily human schemas apply), effectance motivation (need to explain/predict the agent), and sociality motivation (need for social connection, e.g. under loneliness). Explains individual/contextual variance in how much "mind" a reader projects onto LLM-authored text — a lonely or motivated reader will anthropomorphize an AI message more, changing how the same text is received depending on the recipient's state, not the message.
  open-access: unknown — no free PDF found (APA paywalled); author copy sometimes on ResearchGate.

- **Longoni, Bonezzi, Morewedge. "Resistance to Medical Artificial Intelligence." Journal of Consumer Research, 2019. https://doi.org/10.1093/jcr/ucz013.**
  Series of choice experiments: people avoid AI-provided healthcare relative to equally- or even better-performing human providers, driven by "uniqueness neglect" — the belief that algorithms cannot account for one's individual circumstances. Resistance disappears when deciding for an "average person" rather than oneself. Doctor-patient-relevant precursor to disclosure-penalty findings: the mechanism is not "AI is less accurate" but "AI can't see *me* specifically," which predicts why personalized/emotionally loaded text (condolences, diagnoses) takes a bigger AI-disclosure hit than generic informational text.
  open-access: unknown — no free PDF found.

- **Sundar, Kim. "Machine Heuristic: When We Trust Computers More Than Humans With Our Personal Information." CHI 2019. https://doi.org/10.1145/3290605.3300768.**
  Introduces/operationalizes the "machine heuristic": a cognitive shortcut that machine-produced output is objective, accurate, and unbiased (positive form) or cold/incapable of nuance (negative form), cued simply by knowing a machine — not a human — is the source. Online survey experiment shows the heuristic is triggered by mere source labeling. Core mechanism for why identical text gets different credibility/warmth ratings purely from an "AI-written" tag — independent of any actual quality difference, and cutting in *both* directions depending on which heuristic gets cued.
  open-access: unknown — ACM paywalled; author's earlier CHI 2019 version PDF found on USC library mirror (non-canonical), so treat as unknown.

- **Yang, Sundar. "Machine heuristic: concept explication and development of a measurement scale." Journal of Computer-Mediated Communication, 2024. https://doi.org/10.1093/jcmc/zmae019.**
  Develops and validates a multi-item Machine Heuristic Scale (MHS) distinguishing positive (accurate, objective) and negative (cold, incapable of judgment) machine heuristics as individual-difference measures, and shows MHS scores predict trust/credibility judgments of AI-labeled content across domains. Turns the machine heuristic from a single-study effect into a measurable trait, letting later papers (e.g. Heimstad et al. below) explain *why* some readers show a bigger AI-label penalty than others.
  open-access: unknown — Oxford paywalled; no free PDF found.

- **Dorigoni, Giardino. "The illusion of empathy: evaluating AI-generated outputs in moments that matter." Frontiers in Psychology, 2025. https://doi.org/10.3389/fpsyg.2025.1568911.**
  Manipulates emotional context (childbirth vs. terminal illness) and attributed source (close friend, florist, Google, ChatGPT) of condolence/celebration messages, with disclosure timing varied. Authenticity ratings collapse sharply upon AI disclosure (mean 3.78→2.08 in one study) even though the text is unchanged; ChatGPT attribution produces the steepest drop, worse than "Google" or "florist" sources. Directly demonstrates that the LLM->human penalty is about attributed *intentionality*, not content: the same words are "sincere" until relabeled, then "algorithmically hollow."
  open-access: yes — https://pmc.ncbi.nlm.nih.gov/articles/PMC12283995/

- **Lim, Hong, Schneider. "How warm-versus competent-toned AI apologies affect trust and forgiveness through emotions and perceived sincerity." Computers in Human Behavior, 2025. https://doi.org/10.1016/j.chb.2025.108761.**
  Experiment on corporate apology statements manipulating AI vs. human authorship and warm vs. competence-framed tone; perceived sincerity mediates the effect of tone/source on trust repair and forgiveness, and warmth-toned framing helps AI apologies more than competence-toned framing. Isolates *tone* as a lever that can partly offset the AI-authorship penalty — sincerity is inferred from linguistic warmth cues even when the reader knows (or suspects) the author is a machine.
  open-access: unknown — no free PDF found.

- **Lim, Schneider, Grover, Zhang, Peters. "Effects of AI versus human source attribution on trust and forgiveness in the identical corporate apology statement for a data breach scandal." Public Relations Review, 2025. https://doi.org/10.1016/j.pubrev.2024.102520.**
  Holds the apology text byte-for-byte identical and manipulates only attributed source (AI-written vs. human-written); AI attribution lowers trust and forgiveness intention relative to human attribution, and empathy mediates the effect for human-attributed apologies while perceived sincerity mediates it for AI-attributed ones — i.e., readers use a *different psychological route* to judge the same words depending on believed authorship. Clean same-text/different-label design, the strongest causal isolation of the "label effect beyond the label" in this set.
  open-access: unknown — no free PDF found.

- **Ovsyannikova, de Mello, Inzlicht. "Third-party evaluators perceive AI as more compassionate than expert humans." Communications Psychology, 2025. https://doi.org/10.1038/s44271-024-00182-6.**
  Blind third-party raters judge AI-generated empathetic responses (to emotionally difficult scenarios) as *more* compassionate than responses from trained human crisis/emotional-support experts, when source is hidden. Once combined with the disclosure-penalty studies above, this triangulates the mechanism precisely: AI text is not less warm/competent on its face — it becomes less trusted/sincere only once the reader *knows or suspects* it is AI-authored, showing the effect lives entirely in attribution, not in linguistic content.
  open-access: yes — https://pmc.ncbi.nlm.nih.gov/articles/PMC11723910/

- **Wu, Kelly. "Online Dating Meets Artificial Intelligence: How the Perception of Algorithmically Generated Profile Text Impacts Attractiveness and Trust." OzCHI 2020. https://doi.org/10.1145/3441000.3441074.**
  Participants (N=48) rated dating profiles labeled human-written vs. AI-assisted; AI-assistance disclosure lowered trust in the profile but did not significantly change rated attractiveness. Suggests the dimensions split: attractiveness (competence/surface judgment) survives AI disclosure while trust (implies a sincere, known "self" behind the words) does not — an early dating-context instance of the warmth/competence dissociation.
  open-access: unknown — ACM paywalled; no free PDF found.

- **Ante. "The Cyrano effect: LLM-assisted impression management and authenticity in online dating." Telematics and Informatics, 2026. https://doi.org/10.1016/j.tele.2026.102422.**
  Study of LLM-assisted message composition in online dating (named for Cyrano de Bergerac's ghostwritten courtship letters): quantifies how much users edit/blend AI drafts to preserve a felt sense of authorship, and how suspected AI assistance changes a recipient's felt authenticity of the exchange and willingness to reciprocate. Frames impression-management in dating explicitly as a "who is really talking to me" problem, extending the AI-MC framework to romantic/high-stakes-intimacy contexts.
  open-access: unknown — no free PDF found.

- **Hagedorn, Klinger, Sassenberg. "AI-based writing assistants for emotional tone: Investigating users' acceptance and recipients' perceptions in online negotiations." Cyberpsychology: Journal of Psychosocial Research on Cyberspace, 2026. https://doi.org/10.5817/cp2026-4-1.**
  Negotiation-message experiment: AI tone-adjustment recommendations (highlighting emotionally risky phrases) are more accepted by senders when paired with explanations, and recipients' impressions of the sender's warmth/trustworthiness depend on the *resulting tone*, largely independent of whether recipients know AI was involved in drafting. One of the few entries where disclosure effects are muted — negotiation outcomes track surface tone more than attributed authorship, unlike condolence/apology genres.
  open-access: yes — https://cyberpsychology.eu/article/view/41122

- **Heimstad, Wien, Gaustad. "Machine heuristic in algorithm aversion: Perceived creativity and effort of output created by or with artificial intelligence." Computers in Human Behavior: Artificial Humans, 2025. https://doi.org/10.1016/j.chbah.2025.100190.**
  Content labeled "AI-authored" is rated less creative and less favorably than identical content labeled human-authored; a sequential mediation shows the path runs through *perceived effort* — AI-labeled content is assumed to have cost less effort to produce, which lowers perceived creativity, which lowers overall evaluation. Human-AI collaboration labels partly rescue the rating relative to AI-only labels. This is the clearest test of the "effort heuristic" mechanism named in the brief: readers explicitly discount output they believe required less costly signaling from a mind.
  open-access: yes — https://doi.org/10.1016/j.chbah.2025.100190 (Elsevier gold-OA journal)

- **Laupichler, Knoth, Schleiss, Raupach. "Algorithm aversion revisited: The role of AI literacy and attitudes towards AI in shaping perceptions of AI-generated texts." British Journal of Educational Technology, 2025. https://doi.org/10.1111/bjet.70035.**
  Survey-experiment shows algorithm aversion toward AI-generated text is not uniform: higher AI literacy and more positive general attitudes toward AI predict smaller penalties against AI-labeled text, and in some subgroups AI literacy reverses the effect toward algorithm *appreciation*. Adds the reader-side moderator missing from single-sample disclosure studies — the AI-label penalty is a property of the reader's prior beliefs (cf. the Machine Heuristic Scale above), not a fixed constant.
  open-access: unknown — Wiley paywalled; no free PDF found.

- **Mariadassou, Klesse, Boegershausen. "Averse to what: Consumer aversion to algorithmic labels, but not their outputs?" Current Opinion in Psychology, 2024. https://doi.org/10.1016/j.copsyc.2024.101839.**
  Review/synthesis distinguishing aversion to the *algorithm label* itself from aversion to algorithmically produced *content*, arguing much of what is called "algorithm aversion" in the literature is really a reaction to disclosure framing and context (task type, stakes, comparison set) rather than a stable preference for human output. Useful theoretical caution against over-reading any single AI-vs-human comparison as evidence of a general aversion — several entries above (dating attractiveness, negotiation tone) are consistent with this "label, not output" reading.
  open-access: unknown — no free PDF found.

- **Baghirov. "AI vs. human in customer service: how attribute type changes the game." Marketing Letters, 2026. https://doi.org/10.1007/s11002-026-09822-9.**
  Customer-service interaction experiments find human agents are rated higher on warmth, AI agents higher on competence, and which one drives satisfaction/conversion depends on task type: competence-linked "search" tasks favor AI, warmth-linked "experience/credence" tasks (needing reassurance, trust) favor humans. Direct evidence for the warmth/competence split (à la Gray et al.'s Agency/Experience) playing out in a live service-interaction context rather than a one-shot message-rating survey.
  open-access: unknown — no free PDF found.

- **Ayers, Poliak, Dredze, Leas, et al. "Comparing Physician and Artificial Intelligence Chatbot Responses to Patient Questions Posted to a Public Social Media Forum." JAMA Internal Medicine, 2023. https://doi.org/10.1001/jamainternmed.2023.1838.**
  Blinded panel of licensed healthcare professionals rated chatbot (early ChatGPT) responses to real patient questions as higher quality *and* more empathetic than physician responses in the same forum, in 78.6% of the 585 evaluations, when source was concealed. Doctor-patient-context counterpart to the Ovsyannikova compassion finding: with source hidden, AI text reads as more empathetic than expert-human text; the literature above shows this reverses once source is disclosed — the empathy the reader perceives is not in the words themselves but collapses on relabeling.
  open-access: unknown — JAMA subscription; no free PDF found (PMC embargo).

- **Garcia, Qian, Palminteri. "A moral Turing test: How belief and source shape detection of and agreement with LLM judgments." PLOS One, 2026. https://doi.org/10.1371/journal.pone.0353391.**
  Participants judge moral statements/verdicts under manipulated belief about source (told vs. not told it's an LLM) crossed with true source; detection of AI authorship is near chance, but *believing* a statement is AI-authored (regardless of ground truth) changes agreement and trust ratings independent of actual origin. Cleanly separates "can people detect AI text" (largely no, consistent with Jakesch et al.) from "does believing text is AI-authored change its reception" (yes) — the two effects the whole literature keeps conflating.
  open-access: yes — https://doi.org/10.1371/journal.pone.0353391 (PLOS gold OA)

## Could not resolve

- None — all leads that reached a specific title were resolved to a DOI via Crossref. Two candidate leads were abandoned before reaching a specific citable title: "Liu et al. reciprocity/relationship-effects follow-up" (named in the brief) — searches surfaced only tangential 2024-2026 items (LLM-agent trust simulations, empathic-communication training studies) that did not match the named author/topic combination closely enough to cite with confidence; and a general "uncanny-valley-of-mind + LLM text (not robots)" search that returned only the Gray/Wegner robot-embodiment original and no text-only extension meeting the citation bar.

## Synthesis: why LLM->human differs from human->human (10 lines)

1. Detection is near chance (Jakesch et al. 2023; Garcia et al. 2026), so almost every effect below is triggered by *disclosed or suspected* authorship, not by any actual textual signature — the boundary is epistemic, not perceptual.
2. Readers split judgment along Agency vs. Experience (Gray, Gray & Wegner 2007): AI text tends to keep or gain perceived Agency/competence but loses perceived Experience/warmth once attributed — seen directly in Baghirov 2026 and the apology-tone studies (Lim et al. 2025 x2).
3. The "uncanny valley of mind" (Gray & Wegner 2012) predicts discomfort specifically when a machine-attributed text reads as *too* emotionally attuned — matches the steep authenticity collapse on disclosure in Dorigoni & Giardino 2025.
4. The machine heuristic (Sundar & Kim 2019; Yang & Sundar 2024) is a labeled-source shortcut that can cut positive (objective, unbiased) or negative (cold, incapable), and is measurable as a stable individual difference that predicts how hard the AI-label penalty lands on a given reader.
5. Effort/costly-signaling is a concrete mechanism, not just a metaphor: AI-labeled output is assumed to cost the sender less effort, and that assumed-effort deficit — not content quality — mediates lower creativity/favorability ratings (Heimstad, Wien & Gaustad 2025).
6. Sincerity and empathy ratings are attribution-dependent, not content-dependent: identical apology/condolence text gets rated as sincere-until-relabeled (Dorigoni & Giardino 2025; Lim et al. 2025, Public Relations Review), and blind panels rate AI text as *more* empathetic than expert humans until source is known (Ovsyannikova et al. 2025; Ayers et al. 2023 JAMA).
7. Disclosure effects are genre-dependent, not universal: they are large in condolence/apology/dating-trust contexts but small-to-absent in negotiation tone (Hagedorn et al. 2026) and trust-building efficiency (Purcell et al. 2025) — genres where the reader cares about outcome more than "who really meant it."
8. AI mediation reallocates moral responsibility ("moral crumple zone," Hohenstein & Jung 2020): a visible AI intermediary in a *failed* interaction can raise trust in the human partner by absorbing blame — the opposite of the disclosure penalty, showing the direction of the effect depends on outcome valence, not just AI presence.
9. Anthropomorphism motivation (Epley, Waytz & Cacioppo 2007) and uniqueness neglect (Longoni, Bonezzi & Morewedge 2019) predict *who* is most/least susceptible: lonelier or more AI-motivated readers project more mind onto AI text, while readers who need to feel personally, uniquely seen (condolence, medical, dating) show the sharpest AI-disclosure penalty.
10. Net picture: the LLM->human boundary is not a fixed discount on quality — it is a switch in *inference route* (sincerity-via-empathy for humans vs. sincerity-via-perceived-effort for AI, per Lim et al. 2025) that only activates when the reader believes, rightly or wrongly, that no human mind bothered to write the words for them specifically.

## Search queries run

- Jakesch Hancock Naaman AI ghostwriter trust language model PNAS 2023
- Hohenstein Jung AI-mediated communication interpersonal trust 2020
- Mieczkowski AI on behalf of friend social presence 2024
- algorithm aversion AI label penalty effort care perceived sincerity message
- Gray Wegner dimensions of mind perception agency experience Science 2007
- Longoni Bonezzi Morewedge resistance medical artificial intelligence uniquely human
- uncanny valley of mind Złotowski robots perceived mind
- AI-generated condolence message perceived sincerity empathy disclosure study
- Sundar machine heuristic credibility MAIN model automated content
- Epley Waytz Cacioppo three-factor theory anthropomorphism 2007 psychological review
- people cannot detect AI-generated text perception cues suspicion study 2024 2025
- AI dating profile message perceived authenticity attraction study
- AI writing assistant negotiation emotional tone acceptance Cyberpsychology 2024
- Liu large language model assisted communication relationship trust reciprocity 2024 2025
- social presence chatbot customer service perceived warmth competence human agent comparison 2023 2024
- "Mieczkowski" Hancock AI writing assistant perception intentions CSCW OR CHI
- humans detect AI generated text Turing test cues linguistic study accuracy chance
- Crossref API: works/{doi} and works?query.bibliographic= for ~25 candidate citations (Jakesch PNAS, Hohenstein CHB, Gray Science, Epley Psych Review, Longoni JCR, illusion of empathy Frontiers, warm/competent AI apologies CHB, AI vs human source attribution PubRev, third-party compassion Comms Psych, machine heuristic JCMC + CHI, online dating AI profile ACM, Cyrano effect Telematics, machine heuristic algorithm aversion CHB-AH, algorithm aversion revisited BJET, averse-to-what CurrOpinPsych, Liu empathy LLM crowd workers, Marketing Letters AI vs human CS, Ayers JAMA IM, Reeves Nass media equation, Gray Wegner Cognition 2012, Mieczkowski CSCW 2021, moral Turing test PLOS One, Purcell Jakesch iScience, Hagedorn Cyberpsychology)
