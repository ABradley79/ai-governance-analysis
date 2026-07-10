# Anthropic Responsible Scaling Policy (v3.3) -- One-Pager

**Framework:** Anthropic Responsible Scaling Policy, version 3.3
**Type:** Voluntary frontier-lab self-governance framework; a conditional contract the company writes with itself
**Issuing body:** Anthropic
**Status:** Current, effective 26 May 2026. Version tempo is itself a data point: v3.0 (24 Feb 2026, comprehensive rewrite), v3.1 (2 Apr), v3.2 (29 Apr), v3.3 (26 May). Four versions in roughly three months. Source of record: anthropic.com/responsible-scaling-policy.
**Deep-dive status:** Complete, 5 July 2026 (Claude clock) | **Analyst:** Andrew Bradley

*Structural note: this one-pager adapts the ISO 42001 template on contact, per the deep-dive plan. Two changes: a new field (capability thresholds and decision triggers) that the 42001 structure had no equivalent for, and a split of "key obligations" into commitments versus aspirations. The adapted structure is intended to hold across the OpenAI Preparedness Framework and DeepMind Frontier Safety Framework. Strain against the original template is flagged inline in italics.*

---

## Headline verdict

**Real substance, self-held enforcement. A framework that constrains itself from inside the thing it is constraining.**

The RSP is a contract Anthropic writes with itself. It has genuine outcome substance where most of the corpus has none: named capability thresholds, explicit threat models, concrete mitigations benchmarked to real systems, and the only hard action verb in the corpus so far ("we will delay"). But it lacks external enforcement machinery, and the lack is structural, not incidental: every mechanism intended to constrain Anthropic routes its trigger through a determination Anthropic makes about itself, in conditions fuzzy enough that judgement has room to move. Disclosure clocks start when Anthropic determines they start. Mandatory external review fires on a two-part test Anthropic administers. The delay commitments arm on evidence Anthropic cannot obtain and disarm on beliefs Anthropic holds about itself. The one genuine semi-independent lever (the LTBT's approval gate) exists at the discretion of the Board that the framework constrains.

This is the exact inversion of ISO 42001, which has certifiable third-party audit machinery wrapped around a management system with no outcome substance. The RSP has the substance and no machinery. Each framework is strongest precisely where the other is empty.

---

## Scope

Catastrophic risks only, from Anthropic's own frontier models. Explicitly not comprehensive: non-catastrophic risks are handled by the Usage Policy and other instruments, and regulatory obligations beyond the RSP's focus are addressed separately. The document runs three registers at once: a safety-philosophy argument, an operating procedure, and a self-written conditional contract.

*Strain flag: in 42001, scope is static, an organisation and its management wrapper. Here scope is dynamic: what the framework governs is defined by capability lines that models cross, and the crossing activates everything else. The 42001 template has nowhere to put that, hence the new field below.*

## Capability thresholds and decision triggers

*(New field, no 42001 equivalent. Houses two of the four predicted strain axes: capability thresholds and evaluation triggers. Deployment/halt logic is included here because trigger and decision are one machinery in this document.)*

Four thresholds in the Section 1 table, each mapping a capability line to mitigations:

1. **Non-novel CBRN:** significant help to individuals with basic technical backgrounds (undergraduate STEM) toward weapons with serious catastrophic potential.
2. **Novel CBRN** (rewritten in v3.3): systems that can "functionally substitute" for the scarce world-leading expertise (footnoted as a pool of hundreds of specialists) that is currently the primary barrier to novel weapons development, end to end. The v3.3 rewrite moved two dials in opposite directions: the harm bar dropped (from "far beyond" COVID-19 to "comparable to or worse than") while the capability bar rose (from "significantly help" to full substitution). Re-aiming and quiet loosening are indistinguishable from outside because the threshold is self-written and self-evaluated; see open questions.
3. **Misaligned AI in high-stakes settings:** heavily relied-on systems with sensitive access and moderate capacity for autonomous subterfuge, near-term application being AI used inside frontier labs themselves.
4. **Automated R&D:** full substitution for Anthropic's research staff at competitive cost (within 5x), or a doubling of aggregate AI progress substantially attributable to automation. This threshold also defines "highly capable", the term the external-review trigger and all of Appendix A hang from.

**The decision machinery is self-clocked throughout.** Every trigger fires on Anthropic "determining" a line has been crossed; nothing bounds the gap between a model becoming dangerous and Anthropic concluding it has. The off-cycle disclosure mechanism (Section 3.1, restructured in v3.3) starts a 30-day publication clock for internal models, but only for two of the four threat domains (misalignment and automated R&D). An internal-only model crossing the CBRN lines waits for the scheduled 3-to-6-month Risk Report, the longest wait attached to the domain where speed matters most. And the clock that exists times the *disclosure*, not the *decision*: nothing in the framework puts a deadline on deciding what to do about a dangerous model. The framework times the press release and leaves the containment untimed.

## Risk approach

The hinge of v3 is the absolute-to-marginal shift. v2 committed to reducing Anthropic's own absolute risk to acceptable levels regardless of other developers; v3 reframes around ecosystem risk as a collective-action problem, splitting commitments into what Anthropic will do regardless (middle column) and what it "cannot commit to following unilaterally" (right column). The categorical pause commitment of v1/v2 was dropped in v3.0 and replaced by the competitor-contingent commitments of Appendix A.

Hold both readings at once: honest, because catastrophic AI risk genuinely is a collective-action problem one careful lab cannot solve; convenient, because a marginal standard carries a built-in escape (if the ecosystem is dangerous anyway, one's own added contribution always looks small). The document knows this is its soft spot and fits two guardrails: Section 3.2 commits to acknowledging absolute risk even where marginal contribution is limited, and Section 3.4 procedure 5 requires explicit Board and LTBT approval whenever marginal-risk analysis plays a major role in a go decision. The hardest mechanism in the document is bolted to its softest argument.

## Commitments versus aspirations

*(Split field. 42001's single "key obligations" list would launder the two species together, which is the document's own move and one this page should not repeat. The test applied: which cells could Anthropic demonstrably fail? Only failable cells are commitments.)*

**Failable commitments (the real core):**
- Maintain or improve ASL-3 protections for CBRN, benchmarked to named systems (classifier guards at least as robust as the initial Constitutional Classifiers, access controls, red-teaming, bug bounties, threat intelligence), with changes published in Risk Reports.
- Publish Risk Reports every 3 to 6 months; publish off-cycle analyses on the triggers above, including within 30 days for in-scope internal models.
- Complete full external review whenever a report covers highly capable models and is significantly redacted; conduct a review upon LTBT request.
- Obtain explicit Board and LTBT approval for marginal-risk-dependent go decisions.
- Develop internal red-teaming until it outperforms the established bug-bounty pool at finding jailbreaks (a measurable done-state).
- Share final unredacted Risk Reports with regular-clearance staff (employees as a distributed watchdog, backed by the noncompliance-reporting channel and the no-gag commitment on non-disparagement clauses).
- Commission an approximately annual third-party review of procedural compliance (procedural only; it certifies the process was followed, not that outcomes were safe).

**Unfailable aspirations (the halo):**
- The entire right column of the Section 1 table, explicitly aspirational.
- The policy annexes ("identify threat pathways, create policy recommendations, share with policymakers"): no owner, no cadence, no done-state; satisfiable forever by a single briefing.
- "Work toward a practice of seeking" comprehensive external review: three softeners in one clause.
- Frontier Safety Roadmap goals: described as a forcing function, defined as non-binding, self-set and self-revisable. A real forcing function carries a consequence the actor does not control; these motivate, they do not force.

**Pattern across the table:** the control type degrades as the hazard gets harder to bound. Row one (concrete, present hazard) gets a real control; row three (emergent, hard-to-see hazard) gets a disclosure commitment, a promise to write the risk up, not to stop it. That is the inverse of what a risk register wants, where the least-understood hazards should pull the most deliberate controls.

## Enforcement model

Self-authored, self-judged, self-amendable. The consistent architecture, found independently in every mechanism examined:

- **Off-cycle disclosure:** clock starts on Anthropic's own determination.
- **External review trigger:** mandatory only on a conjunction (highly capable AND significantly redacted), escapable from either side, with "significantly redacted" judged by the RSO, CEO, Board, or LTBT: the reviewed party administers the trigger for its own review. The design is defensible (independent review targeted exactly where public scrutiny is blinded); self-administration is what hollows it.
- **External review consequence:** voice without veto. The reviewer's powers are all speech acts (address, evaluate, disagree, recommend, publish), genuinely unrestricted beyond confidentiality, including criticism of Anthropic's conduct. No obligation flows back: nothing requires Anthropic to answer, revise, re-run, or delay in response. The reviewer's power is fully discharged at publication. The veto is withheld by silence, not by clever wording, which makes the withholding more durable, not less.
- **Appendix A delay commitments:** the only hard action verb in the document ("we will delay... as needed"), chained to triggers Anthropic cannot verify (clear evidence of competitors' non-development: a negative about rivals' private R&D) and exits Anthropic alone judges ("until and unless we no longer believe we have a significant lead"). Hard evidence to arm, mere belief to disarm. An inverted safety interlock: the switching logic is biased away from caution and toward motion, the opposite of smoke-detector design. The three scenarios descend in strength, ending at "we will not necessarily delay".
- **The LTBT, the nested exception:** the one body semi-detached from the company holds one real outcome lever (approval gate on marginal-risk go decisions) plus the power to compel reviews and approve reviewer selection. But RSP changes are approved by the Board "in consultation with" the LTBT, consultation being weaker than the approval the LTBT holds elsewhere. The gate is real; its existence is revocable by the party it constrains. The exception does not break the pattern, it is nested inside it: self-governance all the way up, with one genuine lever suspended inside.

## Who it binds

Anthropic only, voluntarily, by a document Anthropic's own Board can amend. Binding force is reputational and political: the RSP is load-bearing in Anthropic's public positioning and policy advocacy, which creates a real cost to visible breach but no mechanism for one. Internal accountability runs through the RSO, the noncompliance-reporting channel (with a Board-level route where the RSO is implicated), and staff-wide access to unredacted reports.

*Strain flag: 42001's "who it binds" assumes an external attestation relationship (certifier, market, regulator). Here the field reduces to one line plus the self-amendment caveat, which is itself the finding.*

---

## Intersections with crisis / resilience

**Self-clocked tempo, and the racing problem.** Every trigger depends on an internal determination. In the fast case (a self-improving internal system), the determination and the danger race each other, and capability becomes harder to characterise at exactly the rate it grows. A monitoring regime whose response time is coupled to the thing it observes is the classic acceleration failure. The clause silently assumes the determination wins the race.

**Disclosure timed, decision untimed.** The 30-day clock governs publication, not containment. In operational terms: the framework deadlines the situation report and leaves the incident action plan open-ended. The go/no-go sits with the CEO and RSO with no clock at all.

**The inverted interlock.** Appendix A's switching logic (hard to arm, easy to disarm) is the reverse of safety-system design, where false alarms are cheap and missed alarms are fatal, so arming is made easy. The direction of the asymmetry is the direction the system drifts under pressure: forward.

**Voice without veto, and the runway question.** Voice-first is the historically normal early rung of a maturing governance mechanism, and voice is the material veto is later built from (the accumulation of "enough"). The RSP is doing the stage-appropriate thing, and does it better than most of the corpus (a genuinely ungagged reviewer is rare). The open condition is runway: every prior domain where voice matured into veto gave it years of repeating, chronic harm to accumulate against. This domain may not wait. Worse, the fast case attacks legibility itself: voice accumulates from clear evidence, and clear evidence is what a rapidly self-improving system degrades. A disclosure-based regime may depend on a legibility that its worst case destroys.

**No incident commander for the frontier.** The marginal framing makes every actor's duty relative to the others', which is the multi-agency accountability seam: when everyone is individually compliant and the system still fails, the failure falls in the gap between actors, and no one owns it.

**The 42001 contrast, operationally.** The RSP is built strongest exactly where 42001 was weakest (it has thresholds, triggers, and halt logic; 42001 had no mandatory reassessment trigger, no halt mechanism, no escalation past the boundary) and weakest where 42001 was strong (no third-party attestation machinery; 42001 is certifiable). Each abdicates what the other formalises.

---

## Open questions

- **Bridge or substitute, restated as a tempo race:** does voice accumulate into veto faster than the hazard accumulates into catastrophe? The adequacy of voice-without-veto is entirely a function of relative tempo, and nothing in the document controls the tempo of the other side.
- **The legibility question (possibly structural, darker than tempo):** does disclosure-based governance depend on an evidential legibility that the fast case destroys? If reviewers can only assess what Anthropic can characterise, and characterisation degrades under acceleration, the central mechanism fails exactly when needed most.
- **Re-aiming versus loosening:** the v3.3 CBRN rewrite tightened one dial and loosened the other. A self-written, self-evaluated threshold makes the two indistinguishable from outside. Test at each future version.
- **Stability of self-governance:** is a commitment revised four times in three months still a commitment, or is revision-under-scrutiny what a living document should look like? Both readings remain open.
- **What does "delay" cash out as?** Time, compute, deployment but not training? Undefined, and inherently self-terminating on a competitive belief.
- **The on-switch test for future versions:** does any subsequent version move a single trigger determination outside the building (external body certifies a threshold crossing, competitor condition, or redaction call)? That would be the first structural break in the pattern.

## Cross-project hooks

- **The inversion (corpus-level, with 42001):** audit machinery without outcome substance versus outcome substance without audit machinery. Two data points now held; test whether any framework in the corpus holds both.
- **On-switch location (the frontier-lab comparison axis):** for OpenAI Preparedness and DeepMind FSF, ask the same single question of every mechanism: where does the trigger determination sit? Any lab that places one on-switch outside its own building has done the thing the RSP declined to do.
- **Honesty and discretion in the same clause (corpus-level, re-runnable):** "necessarily high-level and limited"; "we are approaching it as an experiment". A genuine external constraint that also licenses retained discretion, the two indistinguishable from outside. 42001 runs the same move ("correctly modest because the field is premature"). Test every framework for the clause where the honest reading and the self-serving reading share a sentence.
- **The failability test (reusable instrument):** for any framework's obligations, ask which could the actor demonstrably fail. Unfailable obligations are aspirations wearing commitment clothing.
- **Template-setting loop (frontier cluster spine):** the first credible mover seeds the standard the ecosystem converges on. For each lab: raising the template or matching it?
- **Two one-pager species (structural note for the synthesis file):** the corpus forks into management-system frameworks (42001, NIST RMF) and threshold-trigger frameworks (the three labs). The fork is itself a finding: frameworks that govern organisations and frameworks that govern capabilities strain each other's structures exactly where the four predicted axes said they would.
