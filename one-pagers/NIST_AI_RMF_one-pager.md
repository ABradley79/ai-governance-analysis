# NIST AI Risk Management Framework (AI RMF 1.0) -- One-Pager

**Framework:** NIST AI Risk Management Framework 1.0 (NIST AI 100-1)
**Type:** Voluntary federal guidance; a catalogue of risk-management outcomes and a shared vocabulary, not a requirements standard
**Issuing body:** US National Institute of Standards and Technology, a non-regulatory agency, as directed by the National Artificial Intelligence Initiative Act of 2020 (P.L. 116-283)
**Status:** Current. Published January 2023, never revised since. Under revision as of mid-2026 per NIST's own notice; the revision was tasked by the White House AI Action Plan (July 2025), which ordered references to misinformation, DEI, and climate change removed, arriving ahead of the document's own promised community review ("no later than 2028"). Companion: NIST AI 600-1, the Generative AI Profile (July 2024), current; its authorising executive order was revoked in January 2025 and the profile stands unchanged.
**Analysed on:** the January 2023 text, content-verified.
**Deep-dive status:** Complete, 11 July 2026 | **Analyst:** Andrew Bradley

*Structural note: this one-pager runs the management-system template inherited from ISO/IEC 42001, for side-by-side comparability. The dive's checkpoint 2 finding is that the RMF is not a strained member of that species. It is the corpus's first member of a third species: the method framework, sibling to ISO 31000 and the NIST Cybersecurity Framework, which governs nothing and equips governing. Field names are kept. Where a field assumes an obligating voice this document does not have, the entry says so plainly.*

---

## Headline verdict

**A parts catalogue performing as a governance framework. Requirements-grade content, no requirements.**

The RMF is the most-referenced AI governance document in existence, and it binds no one to anything. Its own text says so three times: it does not prescribe risk tolerance, its actions do not constitute a checklist, and it does not prescribe profile templates. The verb census confirms it: zero musts, one shall (inside a quoted example), fifty shoulds across 48 pages. Its self-description matches: a "catalog of outcomes and approaches", designed to "equip organizations and individuals". Much of the content is genuinely good. The criteria are checkable, the doctrine is sound, and its vocabulary is now the field's shared language. But every entry is optional, and the optionality is constitutive: Congress commissioned a voluntary resource, and NIST cannot issue binding requirements on private parties. The result is the inversion's third corner. 42001 has machinery without substance. The frontier labs have substance without machinery. The RMF has neither; it has parts, and someone else must bring the binding. Where a binder is imported, through statute, procurement, or an organisation's own policy, the content cashes at close to full value. Where none is, the framework works as a vocabulary and a procurement token, and its imperative function names, Govern, Map, Measure, Manage, do rhetorical work the text never backs.

## Scope

All AI systems, all sectors, all organisation sizes, the full lifecycle. Deliberately universal: "non-sector-specific and use-case agnostic." The subject is the organisation's risk practice, never any capability line. The breadth is purchased with the emptiness: universally applicable at the core means specific to none, and NIST has now conceded as much by commissioning a Critical Infrastructure profile (concept note, April 2026).

*Strain flag: in the management-system species, scope is fixed by a conformance claim, an organisation and its declared system boundary. The RMF has no conformance claim, so its scope has no edge. Anyone, nothing checkable. The species break is visible in the first field.*

## Risk approach

Four functions: Govern, Map, Measure, Manage. Govern is cross-cutting; the other three run per system. The framing is continuous ("risk management *should* be continuous"), but no clock or trigger attaches to anything.

The core refuses to enumerate risks. Part 1 explains why: measurement is immature, tolerance is context-bound, and the framework will not set it. "While the AI RMF can be used to prioritize risk, it does not prescribe risk tolerance" (1.2.2). What it offers instead is an architecture of trustworthiness: seven characteristics, with Valid and Reliable as the stated necessary condition and everything else tradeable by context. One floor, six tradeables, weakest-link logic, trade-offs conceded in the text itself.

The lifecycle model is imported from the OECD and modified in exactly two ways, both telling. TEVV is written into every stage, and builders are separated from verifiers "as a best practice." A metrology institute's framework, thickest at measurement, silent at decision and enforcement.

Residual risk shows the approach's limit in one clause. The definition is correct (Guide 73, cited), and the handling is to document it and inform end users. No acceptance act, no named acceptor, no authority level. NIST's own security RMF makes explicit residual-risk acceptance the non-delegable duty of an Authorizing Official. The AI RMF, same institution, replaces the signature with a disclosure, routed to the party with least control over the risk.

## Enforcement model

None, at three levels, and the layering matters.

Text: zero occurrences of "must," one "shall" inside a quoted example, fifty "shoulds" in 48 pages, and three self-declarations of non-prescription (no tolerance, not a checklist, no profile templates). Institution: NIST is non-regulatory; its documents bind only where another instrument lends them force, and no such instrument exists here for private parties. The one semi-bound population, federal agencies under a 2024 OMB memo (M-24-10, March 2024), was bound by an instrument outside the document, which the next administration rescinded and replaced in April 2025 (M-25-21). Mandate: the framework ties its own character to its statutory direction, describing itself as a resource, "intended to be voluntary, rights-preserving, non-sector-specific, and use-case agnostic."

The result for the failability test: the contents are failable as criteria and unfailable as commitments, because they are not commitments. Bind the catalogue with a shall and an auditor and you get approximately ISO 42001. Nobody has. Binding force is always imported: a statute offering alignment as a defence, a procurement clause, an organisation's own policy. The market runs the two species as a pair, the RMF as the operating rhythm and 42001 as the certifiable layer when a buyer demands one. Certificates number in the low hundreds worldwide as of spring 2026; claimed RMF adoption runs to a majority of surveyed security executives. The failable instrument is rare. The unfailable one is everywhere.

One structural note the document draws against its own ecosystem: its lifecycle diagram separates the actors who build models from the actors who verify them, as best practice. The frontier tier fuses them. Nothing in the RMF can see or act on the difference.

## Who it binds

No one. There is no conformance claim to make or fail; "aligned with NIST AI RMF" is self-attested and cannot be checked, which is exactly why it circulates so freely as a procurement token.

Who binds it is the sharper question. Created on the direction of Congress. Now being revised on the order of the White House, which in July 2025 tasked NIST to remove references to misinformation, DEI, and climate change, ahead of the document's own promised community review in 2028. Both ends of the pen are political. Neither end ever held a shall. Revision authority is a comparison axis this corpus now needs: ISO revises through a consensus body, the labs revise themselves, and the US framework is revised by its political principal.

## Key obligations

This field assumes an obligating voice. The document has none, so the obligations bin is empty by design, not by vagueness. What the catalogue holds instead is criteria, most of them checkable, some of them the best of their kind in the corpus:

- Policies, accountability structures, and executive ownership of AI risk (GOVERN 1-2)
- Workforce diversity, equity, inclusion, and accessibility as a named category (GOVERN 3, the revision's deepest target)
- A risk-management culture and safety-first mindset (GOVERN 4)
- Third-party policies and contingency processes for third-party AI failures (GOVERN 6)
- Intended purpose, context, users, and human-oversight processes documented (MAP 1, MAP 3.5)
- Production monitoring against the mapped baseline, regular safety evaluation with response times, field validation of performing-as-intended (MEASURE 2.4, 2.6, 4.2)
- A go or no-go determination on whether development or deployment should proceed (MANAGE 1.1, occurrence checkable, content not)
- Residual risks documented; post-deployment plans including appeal and override, decommissioning, incident response, recovery, and change management; incidents communicated to affected communities (MANAGE 1.4, 4.1, 4.3)

Every entry optional. The gradient inside the list matters: the most determinate items certify artefacts and processes; the decision-shaped item certifies that a meeting happened.

## Intersections with crisis / resilience

**The core resilience finding: the three arrivals, re-run.** Tested against the same instrument as 42001. Organisational purpose drift: INVISIBLE. The document watches the system, never the use, and its only re-verb is an onboarding clause. 42001's change machinery at least catches creep that surfaces as a change request, so this is the one cell where the certifiable standard outperforms the catalogue. Individual drift: INVISIBLE. Oversight is defined and documented at design time; nothing watches whether the overseeing still happens. The MEASURE prose gestures at tracking human-AI configurations; no subcategory wires it. Validation decay: SEEN, with the strongest detection components in the corpus, better than anything 42001 compels, and two wires short: no re-validation route for a detected divergence, and no compulsion. Ruling on the shared failure: both frameworks miss the arrivals, and the certificate's miss is worse for a single organisation, because all three arrivals feed on confidence and a certificate manufactures it. Across the ecosystem the sign flips: an unfalsifiable alignment token circulating at scale is the worse systemic failure.

**The 2am verdict.** A peacetime document. It names the wartime vocabulary, appeal and override, decommissioning, incident response, recovery, change management, and never requires the plan, let alone the drill. 22301 compels the exercise; this compels nothing. It does not fail the decision-under-pressure test. It never enters for it.

**The seam.** GOVERN 6.2's contingency-for-third-party-failure is business continuity doctrine for the supplier you cannot assess, and it is needed, because a deployer running MAP 4 and MANAGE 3 up the chain reaches frontier frameworks that attest nothing. The residual it then documents is a residual it cannot size, from a supplier who graded itself. Acceptance without assessment is exposure with paperwork.

**Two absences for the decision-making lens.** The human baseline: systems replacing human decision-making "require some form of baseline metrics for comparison," declared difficult, supplied by nothing here or since. And the safety definition: envelope-based, correct, and inapplicable where the envelope cannot be defined, so for frontier systems "safe" is not failed but unappraisable. Resilience itself is defined only at system level (return to normal function); the organisational layer is reached by one integration gesture at 1.2.4. NIST's own Critical Infrastructure profile concept note (April 2026) is the admission that the core does not reach IT, OT, and ICS.

## Open questions

- What does the revision actually remove? The DEI cluster is the only tasked family with real presence in the core (GOVERN 3, the Fairness characteristic); misinformation's target exists only in the profile; climate has no literal target in either held text. Does "the RMF" mean the family, and does the edit reach 600-1's Information Integrity category?
- Does the 2028 community review survive the 2025 political tasking, or is attribute 2's open-update promise now dead?
- Does any profile anywhere acquire teeth: a regulator adopting one as requirements would be the first binder imported into the profile mechanism itself.
- Does the promised effectiveness evaluation (Section 4) ever appear, or does the measure-everything framework remain unmeasured?
- What does it mean that the Generative AI Profile has outlived its authorising executive order by eighteen months, unchanged, and nothing happened?

## Cross-project hooks

Checkpoint 2 resolved: third species, the method framework, siblings ISO 31000 and the NIST CSF; the comparative products need a third column type. T4 gains its null case: no obligating voice, an empty bin by design. T6 answered: vocabulary, not floor or ceiling, with Section 6's profile mechanism as the textual slot the lab frameworks functionally occupy, and the chronology running the right way. T1 gains its third corner, plus the component-level inversion: the uncertifiable catalogue holds better drift-detection parts than the certifiable standard compels. T7 gains the corpus's slow extreme: zero revisions in 42 months against the RSP's four in three, a versioning system never exercised, and the only completed feedback loop political. T9 gains its candidate third instance with the sign reversed: the state subtracting risk categories rather than adding constraint. New axes for the corpus: revision-pen location, the residual-risk spectrum (named acceptor, no acceptor, self-acceptor, term unused), and the adoption asymmetry as the inversion monetised.
