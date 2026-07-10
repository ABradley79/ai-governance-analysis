# ISO/IEC 42001:2023 -- One-Pager

**Framework:** ISO/IEC 42001:2023, Information technology -- Artificial intelligence -- Management system (AIMS)
**Type:** Certifiable management-system standard, Annex SL structure
**Issuing body:** ISO/IEC JTC 1 / SC 42
**Status:** Current, first edition (Dec 2023). No amendments. Companion standards developing around it: ISO/IEC 42005 (impact assessment), ISO/IEC 42006 (certification-body requirements, draft).
**Deep-dive completed:** 24 May 2026 | **Analyst:** Andrew Bradley

---

## Headline verdict

ISO/IEC 42001 is a static-system management standard applied to a non-static, non-bounded problem. It is correctly modest about what a management system can do, but that modesty is forced by the immaturity, pace, and expanding scope of the field, not chosen freely. It cannot be more than it is. The risk universe it tries to manage is not merely young; it is moving and growing faster than any assessment cycle can close around it. It sets itself on foundations -- definable purpose, enumerable risk, traceable supply chain -- that AI does not currently provide and may never provide cleanly. That is not a flaw in the standard; it is the standard honestly reaching the edge of what a management-system standard can be.

Its real product is **accountability scaffolding and an audit trail**, not AI risk management in the substantive sense. This is both its strength and the source of its limits, seen from two angles: it is genuinely strong at governing the documentable (who owns the decision, what was assessed, what the trail says) and structurally blind to the undocumentable (a system that drifts after assessment, a user whose trust quietly migrates). The scaffold is sound; it is simply anchored to a baseline that reality drifts away from. The certificate attests to your AIMS and your tier-one relationships, not to the system you are actually embedded in. The load-bearing resilience work -- detecting drift, responding to emergent failure, reaching past your own boundary -- it acknowledges the requirement and abdicates the mechanism.

---

## Scope

Specifies requirements to establish, implement, maintain and continually improve an AI management system. Applies to any organisation that develops, provides, or uses AI, regardless of size or sector. Deliberately broad and technology-neutral. Governs the management wrapper around AI, not the AI itself.

## Risk approach

Borrowed wholesale from ISO 31000 / 27001: establish risk criteria, assess, treat, document in a Statement of Applicability (SoA), audit against it. The one genuinely AI-specific addition is the **AI system impact assessment** (Clause 6.1.4, Annex A.5, B.5), which extends the risk lens beyond the organisation to individuals, groups, and societies.

The weakness is structural, not editorial. The approach assumes an enumerable risk universe. The AI risk set is not currently enumerable and, given the scale and pace of the field, may never be cleanly so. The standard half-concedes this in Annex C, which lists risk *sources* (complexity of environment, lack of transparency, level of automation, technology readiness) rather than risks -- an honest admission that it can say where risk comes from but not catalogue what it is. The machinery therefore runs an enumerable process over a non-enumerable problem. Its value is in surfacing unknowns, not controlling known quantities. Useful as scaffolding, but only if the organisation treats certification as a floor, not a ceiling.

## Enforcement model

Voluntary standard, third-party certifiable. Enforcement is internal and contractual: internal audit (9.2), management review (9.3), corrective action (10.2), external audit against Annex A controls documented in the SoA. No regulator, no statutory penalty, no external escalation path, no inter-organisational coordination mechanism.

The certificate's reach stops at the organisational boundary and tier-one suppliers. **If 42001 cannot reach past tier one of the AI supply chain, certification attests to your AIMS and your direct relationships, not to the system you are actually embedded in.** Annex B.10 concedes this by retreating from *control* of suppliers to *awareness* of where responsibility lies.

## Who it binds

Only the certified organisation, voluntarily. Binds by market pressure -- procurement requirements, EU AI Act Article 17 QMS alignment, customer and regulator trust -- rather than by law. Annex A.10 attempts to extend obligations across the supply chain but cannot enforce beyond tier one.

## Key obligations

- Documented AI policy, objectives, and scope (Clauses 4-5, A.2)
- AI risk assessment and treatment process (6.1.2-6.1.3)
- AI system impact assessment on individuals / groups / societies (6.1.4, A.5)
- Full-lifecycle controls: data, design, verification and validation, deployment, monitoring (A.6, A.7)
- Roles, responsibilities, and an AI-specific concern-reporting channel (A.3)
- Third-party / supply-chain responsibility allocation (A.10)
- Internal audit, management review, corrective action (Clauses 9-10)

---

## Intersections with crisis / resilience

**Accountability scaffolding, not control.** Its real product is fixing an auditable human accountability point around a system increasingly able to act without one -- the same logic as ICS or permit-to-work. It does not prevent failure; it ensures someone owns the decision when failure comes. The behavioural-change language in the Introduction is not the thing it controls; it is the reason the accountability wrapper matters.

**Static model, non-static problem.** The standard assumes a definable intended purpose, an enumerable risk set, and a traceable supply chain. AI provides none cleanly. Everywhere it meets this limit, it retreats from control to awareness and documentation.

### The assessment-reality gap (the core resilience finding)

The standard's reassessment trigger (Clause 8.4) fires "when significant changes are proposed." But the dangerous changes do not arrive as proposals. Three types of gap open between what was assessed and what is actually running, and none trips the trigger:

1. **Purpose drift -- organisational.** The organisation widens how it uses a stable system; the use case creeps because the outputs look good. Observable in the organisation's behaviour (new use cases, new dependencies, rebuilt processes) but under-governed, because creep is rarely filed as a change. *Governance lens.*

2. **Purpose drift -- individual.** A single user's trust in a stable system migrates past its validated envelope, through accumulated confidence rather than any decision. The outputs keep looking right, so the user stops checking. Nothing changes on paper. Effectively un-auditable: a management system built on documented process has no surface to grip a quiet shift in one person's calibration. The more dangerous of the human drifts, and the one that kills in an operational setting. *Decision-making lens.*

3. **Validation decay -- system.** The system itself changes under stable human use: an embedded-model swap (often unannounced), continuous learning, agentic expansion, or output drift under poor prompting. The assessment still looks valid; the system it described no longer exists. This is the type 42001's own Introduction names as *the* AI-specific danger -- and the standard then builds a management system that structurally assumes the system holds still after deployment. B.6.2.6 does require monitoring for data drift, concept drift, and even off-purpose use ("where AI systems are being used for purposes other than those for which they were designed... the appropriateness of such uses should be considered"). But the response is discretionary throughout ("should consider", "can identify"), and no mechanism compels formal re-validation when drift is detected. The standard sees validation decay; it does not bite on it. Detection without a mandatory re-assessment trigger is awareness, not control. *Resilience lens.*

The unifying point: 42001's controls are built to catch organisational change (change requests, SoA review, audit). They offer weak preventive tools for individual drift (competence 7.2, awareness 7.3, human oversight B.9.3) but nothing detective. And for validation decay -- the standard's own stated core risk -- they require monitoring that can detect drift and off-purpose use, but leave the response discretionary and compel no re-validation. Across all three, the standard acknowledges the requirement and abdicates the mechanism. It names behavioural change as the reason AI needs special management, then builds a system whose triggers fire only on proposed change -- and none of the three drifts arrives as a proposal.

---

## Open questions

- Is an enumerable-risk process applied to a non-enumerable risk set genuinely useful (surfacing unknowns) or partly theatre (form without content)? Provisional view: useful as scaffolding, dangerous if mistaken for substance.
- What detects emergent purpose drift and validation decay, given the reassessment trigger fires only on *proposed* change? Does ISO/IEC 42005 or sector practice fill the gap, or does no current instrument close it?
- Do certified organisations understand that the certificate's assurance stops at tier one of the AI supply chain?
- Does 42001 risk *certification theatre* -- a binder that satisfies audit while the live system remains ungoverned -- in the same way a beautifully documented but unexecutable BCM plan does?
- How does this compare to frameworks that reach for the systemic level (EU AI Act systemic-risk tier, frontier lab capability thresholds and deployment halts)? Flag for cross-cluster comparison.

---

## Cross-project hooks

- **Assessment-reality gap** (purpose drift x2 + validation decay) is a reusable comparison axis. Test every other framework against it: how does each handle the divergence between what was assessed and what is running?
- **Control-to-awareness retreat** is a second axis: where does each framework move from "shall control" to "should understand" when it hits the limit of its reach?
- **Tier-one boundary** is a governance-lens axis for the supply-chain question across frameworks.
