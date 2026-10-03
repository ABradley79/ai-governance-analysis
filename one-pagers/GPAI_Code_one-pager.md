# EU General-Purpose AI Code of Practice (final, 10 July 2025) -- One-Pager

**Framework:** The General-Purpose AI Code of Practice (final, 10 July 2025), in three chapters
**Type:** Voluntary code of practice under Article 56 of the EU AI Act. Not a fifth species; a transmission instrument for the Act's model tier
**Issuing body:** Independent chairs, in a process facilitated by the AI Office; published by the European Commission
**Status:** Current and unrevised (checked 2 October 2026). Assessed as adequate by Commission opinion of 1 August 2025; never approved by implementing act (none found). 21 Signatories plus xAI on the safety chapter alone. Fines under the Act available since 2 August 2026, none levied. Companion: the EU AI Act pair of 13 September 2026, the fixed reference here
**Analysed on:** the three official chapter PDFs, read against the frozen EU AI Act pair; hashes in the reasoning note
**Deep-dive status:** Complete, 2 October 2026 | **Analyst:** Andrew Bradley

*Structural note: the nine-heading standard template. One declared choice: the Code sets no thresholds of its own, so the tier material sits under Risk approach and there is no thresholds field. Verdicts are the analyst's rulings at the dive's seven stops; the attribution record is in the reasoning note. Lab comparisons run on the frontier comparative's July 2026 baselines and stay candidates until the labs are re-checked. Legal readings are not a lawyer's.*

---

## Headline verdict

**The Code adds external scrutiny, but the Signatory remains in control. It must show the regulator its evidence by launch day, but still sets its own pass mark, decides what risk to accept and makes the call on stopping.**

The Code is voluntary and binds nobody in law. A provider signs, chapter by chapter, and its commitments become the yardstick the AI Office uses to assess it against Articles 53 and 55 of the Act. Signing is evidence, not proof. There is no presumption of conformity and the burden never leaves the provider. The Act holds the obligations, the Code the practices, with one exception that matters most. The decision to accept the risk and go ahead is written in the Code and nowhere in the Act.

Not a fifth species. The Code fills the gap in the Act's model tier by turning its requirements into a process for making decisions. It requires each Signatory to write a framework with thresholds and triggers, but sets no thresholds itself. The Signatory still writes the criteria it is assessed against; the regulator receives the framework and the report without approving the decisions or accepting the risk.

What the Code adds is real. It names four risks every Signatory must cover and requires an outside evaluator, a full report to the AI Office by launch day, deadlines for reporting incidents and a minimum standard of security. What it leaves where it was is the judgement. The outside eye is real and the outside hand does not exist.

## Scope

Three chapters, two populations. Transparency and Copyright are open to any provider of a general-purpose model and cover Article 53. Safety and Security is written only for providers of models with systemic risk and covers Article 55. A provider can sign one chapter and not the others, as xAI has.

The safety chapter covers the whole life of a model, development and the Signatory's own internal use included, and every version of it. It names four risks no Signatory can leave out (chemical, biological, radiological and nuclear; loss of control; cyber offence; harmful manipulation) and leaves the rest to a list the Signatory builds for itself.

The Code sits wholly on the model side of the seam. No chapter puts a duty on anyone downstream, and none gives the Signatory a hand inside someone else's system. What crosses is sight, information and the licence. The Signatory must test the model as it expects it to be used, watch its own products and hand documentation to the integrator. The word deployer appears in none of the three chapters. Safety says it is not about systems and then requires the Signatory to look into them. Copyright says it is about what downstream systems produce and then acts only on the model and the licence. Both stop at the same edge. The Commission's Q&A calls the split between model-layer and system-layer measures a question underlying the Code. The seam closes in one case, by ownership and not by rule. Where the Signatory sells the product as well as the model, its monitoring follows the model into the product and the Act puts both under the AI Office (Act pair, stop 1).

Open release is where the Code runs out. The security duties end when a model's weights are made public, and a closed model is exempt from the whole security commitment if a more capable model already has public weights. So the hardest floor in the Code floats on the most capable model anyone has released, and the Signatory judges for itself whether it is under the line. Nothing gates open release except the ordinary acceptance decision, and the stop cannot bring released weights back. Models on the market before the Code was published can stand as safe reference models on the Signatory's own judgement, and the Act gives models placed before 2 August 2025 until 2 August 2027 to comply (Article 111(3)).

## Risk approach

A process, not a set of thresholds. Each Signatory writes a Safety and Security Framework and then, for each model, identifies the risks, analyses them, decides whether they are acceptable and mitigates. The full process runs before a model is placed on the market and again when the Signatory has reasonable grounds to think its case no longer holds.

The Code names the hazards and the form of the test and leaves the height to the Signatory. For the four specified risks the Signatory must define tiers (the Code's word; it never says threshold) that are based on capability, measurable and include one the model has not reached. The Signatory writes the tiers, applies them and accepts the result. That is entry eight on the corpus's residual-risk spectrum: self-assessed against a self-written criterion, self-judged. In full: self-acceptor, unnamed, against tiers it wrote beforehand; justified to the regulator by launch with its own failure conditions stated; re-judged from outside only after launch, by the Act's hand. A Signatory can fail its own test. Only the AI Office, reading afterwards, can say the test was set in the wrong place.

When the decision is no, the wording is "not proceeding". That means not going ahead with development, release or use and, for a model already on the market, taking action to restrict, withdraw or recall it. Those three are the Act's actions, but control sits with the Signatory. The Code never uses "delay" or "halt" for a model. The Signatory sets the hold and decides when to lift it, and the hold can apply before a tier is reached. The action is documented for the regulator; it does not require the regulator's approval. The named actions are all market actions. For development and internal use the stop is the bare condition.

The obligations fall into three bins, and the verb does not sort them, because *will* carries everything. Who judges, and against what, sorts them. There is a hard shell of lists, clocks, documents and a security floor, a centre the Signatory judges for itself, and a fringe of recitals and encouragements nobody can fail. The Code's own sorting words are *including*, a minimum by its glossary, and *examples*, a menu. Security sits behind the first and safety behind the second. Security can be specified with hard stops and known tools; safety is a property of outcomes not yet known well enough to specify.

The security floor names its attacker (about ten professionals, several months, up to EUR 1 million, no inside access). That matches the third of five attacker levels in RAND's weight-security report and sits below its state-level attackers. RAND is a reference, not a bar. Outside ownership of the bar was traded for specificity. Everywhere else the bar is the state of the art, which the Signatory judges, above a floor of best practice that the providers set for themselves.

## Enforcement model

None of its own. Everything with force is the Act's. The Act gives a Signatory's commitments three hooks. They are a route to demonstrate compliance until a harmonised standard exists (Articles 53(4) and 55(2)). The AI Office may monitor adherence (89(1)). And they may count as a mitigating factor when a fine is set (101(1), as the Commission reads it). Breaking a commitment is not in itself a breach of the Act. What the Signatory loses is its way of showing that it complied. That is an operational reading, not a lawyer's. A provider that does not sign must justify its own means, for instance by a gap analysis against the Code, so the Code binds only Signatories and is the yardstick for everyone.

This Code was never approved. It was assessed as adequate by Commission opinion on 1 August 2025, and no implementing act has been found. The Omnibus then removed the approval power, while three articles of the Act still say approved. The assessment does the work of approval in practice and on the legislator's stated intent (2026/1744, recital 41). The enacting words have not caught up. Not-a-lawyer.

Every switch in the Code is inside the Signatory. Nobody outside has to agree before a model is trained, launched or kept on the market, and the Code names no role that holds the stop. The Code's stop is the Act's verbs with the Act's hand removed. Outside influence on go or no-go is something the Signatory describes and the Code does not require, a mention, not a seat or a voice. The Code does not move the Act's switch. It feeds it. The Framework reaches the AI Office before launch, the full Model Report on launch day with the Signatory's own failure conditions written in, and incident reports on a clock. Unless the AI Office asks first, it reads the case for a model on the day the model launches. The one discretion it holds before launch lets the report come later, not the model. The Model Report is marked homework, written for one reader. The public and the operator see a summary if anything.

To date the record is paper. Requests for information went to more than thirty providers on 29 August 2026, and no evaluation, measure or fine was found on 2 October 2026. The standing forum for the Code is a taskforce of Signatories chaired by the AI Office. On 17 July 2026 it discussed marginal-risk clauses in Signatories' Frameworks, the clause that lets a lab consider deploying an unsafe model if competitors start doing so. The AI Office's position, as the Commission reports it, is that such a clause could be invoked only in exceptional circumstances and with safeguards. The labs' competitive hatch is not in the Code's text. It travels in through the Frameworks the Signatories write, and the regulator has conditioned it, not closed it.

## Who it binds

Those who sign, chapter by chapter, and nobody else. Twenty-one Signatories plus xAI on the safety chapter alone; Meta is not on the list. The regulator signs nothing. Every duty in the Code is a Signatory's.

Inside the Signatory the Code asks for four responsibilities (oversight, ownership, support and monitoring, assurance) spread across the board, the executives and the operating teams. The vocabulary matches EU banking law, where "management body in its supervisory function" is a defined term of the Capital Requirements Directive. The separation between the executive who monitors risk and the business that creates it is the price of a safe harbour, not a duty. Protection for staff who speak to the authorities is offered as an example of a healthy culture. The duty there is the whistleblower directive's.

Not bound are the integrator, the operator and the evaluator. Smaller Signatories get lighter versions even at systemic risk.

## Key obligations

Safety and Security, for systemic-risk models only:

- Write and keep current a Safety and Security Framework, give the AI Office unredacted access within five business days of approving it, and reassess it at least every twelve months
- Cover the four specified risks with tiers, and run the full process before market
- Evaluate to the state of the art, including by independent outside evaluators given the version of the model with the fewest safeguards
- Proceed only if the risk is acceptable
- Meet the security appendix, or justify an alternative that achieves the same objectives
- File a Model Report with the AI Office by market placement, carrying all evaluation results, random samples, the acceptance case, the conditions under which it would fail and the system prompt
- Update the report on reasonable grounds, before any deliberate change is released, and six-monthly for the most capable models
- Report serious incidents on a clock, with four-weekly updates and a final report within sixty days of resolution
- Keep documentation for ten years, and publish a summary only where needed to assess or mitigate risk

Transparency, for all Signatories. Keep model documentation current and for ten years, give the AI Office what it asks for within its deadline, and give integrators the documentation and, within fourteen days, the further information they need.

Copyright, for all Signatories. Keep a copyright policy, use crawlers that respect paywalls, the robots.txt protocol and a list of infringing sites, guard against infringing output, and give rightsholders a contact point and a complaints route.

Nearly every clock times a document going to the regulator. No clock times the decision, the stop, a mitigation or the correction after an incident. What binds action is order. There is no launch before the process and the report, and no deliberate change before the update. Every clock starts on something the Signatory does, chooses or learns. The Code clocks the reporter and nobody clocks the reader. The one clock on re-judging a live model asks only for a reasonable amount of time.

The outside evaluator has two exits, a model that is similarly safe or safer than a reference model and a failed search for a qualified evaluator, and the Signatory judges both. Most exits have to be justified to the AI Office in the Model Report. The security exemption for a model below the open-weights line does not. The Code is hardest where someone can sue and softest where nobody can. Copyright has a directive, courts and collecting societies behind it, and it gets the harder public duty.

## Intersections with crisis / resilience

**The control room.** From the control room the Code is out of sight. The operator sees a summary if anything, cannot enforce a commitment, is owed no warning before the model is pulled, and reaches the lab only through a reporting channel if one is offered. It is a promise made over the operator's head to a regulator.

**The stop as an outage.** The stop runs downhill and the warning does not. When a Signatory restricts, withdraws or recalls a model, every system built on it is affected, and the Code has no duty to tell the integrator or the operator, before or after. In continuity terms a tool built on a Signatory's model is a supplier dependency that can be withdrawn on the supplier's own judgement, on foresight, without notice. Any notice comes from the contract.

**Incidents.** The Code gives the model tier what the Act left out, namely categories, clocks and a recipient. It carries the Act's threshold with them. A critical-infrastructure disruption counts only if it is serious and irreversible, so the regulator still hears only about the disruptions nobody could reverse. The clock tracks propagation, not gravity. It gives two days for infrastructure, five for a breach or weight theft, ten for a death and fifteen for other serious harm. They are the clocks the Act set for systems, carried over to the model with the five-day one added. It starts when the Signatory learns its model was involved, and nobody is obliged to tell it. It reaches further than the Act's own incident report, because it is keyed to the model's involvement and not to whether the system is on the high-risk list. For one event in a control room the Code adds a fourth report to the three the Act pair counted. Four reports, four authorities, four clocks, no named lead.

**Command.** Nobody is in command, and the Signatory fills the space. It manages the response for its model, tells the AI Office what it intends to do, and tells the regulator what it recommends the regulator do. Nobody is clocked to answer, so the recommendation becomes the plan by default.

**Near miss and recovery.** The Code defines a near miss, which neither the Act nor NIST AI 600-1 does, and feeds near misses back into its own risk assessment. But a near miss has no report of its own, so the events an operator recovers from stay with the Signatory. Restoration is not in the Code. Recovery appears once, for security breaches. The words resilience, continuity, emergency and crisis do not appear in the safety chapter.

**The safety case.** The Model Report is a safety case that is lodged but never accepted. After Piper Alpha the pattern is that the regulator accepts the case before operation. Here the Signatory writes the case, the regulator receives it by launch day, and nobody accepts it.

**The hazard in the analyst's world.** It is not on the compulsory list. The four specified risks are weapons, loss of control, cyber attack and manipulation. A model contributing to a major accident, or to an infrastructure failure with no attacker and no loss of control, sits among the examples a Signatory draws from when it builds its own list. Critical infrastructure gets the fastest reporting clock and no compulsory place in the assessment.

## Open questions

- Does the adequacy assessment do the work of "approved" in the three articles that still use the word? Not-a-lawyer.
- How does a model already on the market get its first Model Report? The delivery clocks all hang on market placement.
- What are the safeguards under which a marginal-risk clause could be invoked, and will they be published?
- Who judges that a model is inferior to one with public weights, and against what test?
- Can one reader keep up? No verified figure for the AI Office's capacity was found.
- Where the lab is also the system provider, how do the Act's rule against altering a system before informing the authority (73(6)) and the Code's duty to investigate and correct fit together?
- Has the national-security exception to unredacted Model Reports been used, and would the AI Office know?
- When does the Code change? It has no revision clause and has not moved in nearly fifteen months. No standard for models is on the way to replace it, and the Commission's stated route is an update agreed with the Signatories it measures.

## Cross-project hooks

- Species. Not a fifth; a threshold-trigger framework one level up, process-centred in the FSF's way, a candidate on the July baseline.
- T1. At the model tier the corpus now has substance and machinery together, in operation today, but only as a pair. The substance is in the Code and the machinery in the Act, joined by a route that proves nothing by itself.
- T2. The trigger determination sits inside the Signatory. The Code feeds the Act's switch and adds no hand to it.
- T4. Three bins; failability from who judges and against what; entry eight. The spectrum's closing line gains a clause. The external acceptor against pre-existing criteria is absent across all eight, and the Code supplies a pre-existing criterion written by the acceptor itself.
- T5. Nothing in the Code slows the other side. On legibility it goes one rung past the labs on the July baseline, with the Signatory still making the call. The stop can fire on foresight.
- T6. Both a floor and the void. A floor on the shell, and the height handed down one more level to each Framework. On the July baseline the skeleton is the labs' own template, with its form made compulsory and a reader attached.
- T7. The clocks time documents. The Code stands still while requiring each Framework to keep moving.
- T8. The fourth strand; a defined near miss with no report of its own; recovery absent.
- T9. The clause on outside influence (1.1(2)(d)) and the national-security exception (7.7) are where a US intervention would show in front of the EU regulator. A hypothesis, not a finding.
- T10. Wholly on the model side; the seam closes only by ownership.
- I1. The model chain no longer breaks because nobody decides. It breaks because the decider writes its own test.
- I2. Open release is the terminus; the competitive hatch is conditioned by the regulator, not closed.
- The frontier comparative's fourth column reads "not proceeding". The analyst's close-out line reads as follows. The Code asks more of its Signatories (labs) than their own frameworks where requirements can be specified and checked: four risks they must cover, an external evaluator, a full report to the AI Office by launch day, deadlines for reporting incidents and a minimum standard of security. On the underlying judgements, little changes. The Signatory still sets its own risk tiers, decides what risk it will accept and makes the call. On the tiers themselves the Code sets the form but not the height: they must be measurable, and it does not specify how high they should be. The labs side is a candidate against the July 2026 comparative (RSP v3.3, Preparedness v2, FSF v3.1), and the labs are re-checked at the December currency review before the full comparison runs.
- Not run here: the Code-versus-labs comparative, whose first hard point is the mitigations a Signatory must name for each tier; the supervisor's half of the banking template; the What Holds matrix, untouched.
