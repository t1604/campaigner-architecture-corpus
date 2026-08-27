---
mirror_role: "Base44 read/reference mirror"
canonical_source: "Google Drive"
source_title: "CAMPAINER-FLOW-CORE-APPLICABILITY-MATRIX-001 — v1.0 — מפת תחולת הליבות על ה־Flow"
source_drive_id: "1cta7iyqAeWhBIxM5nnPkSSN6kgOKnwVKF3woRLzQTs8"
source_modified_at: "2026-08-23T09:06:38.222Z"
corpus_status: "current-v1.0"
category: "flow"
---

> MIRROR NOTICE: This file is a controlled copy for Base44. Google Drive remains the canonical source. Do not infer implementation, deployment, runtime, or release authority from repository presence.

## Canonical source body

CAMPAINER-FLOW-CORE-APPLICABILITY-MATRIX-001 — v1.0
מפת תחולת הליבות על ה־Canonical Product Flow


STATUS: OWNER-APPROVED FLOW CORE APPLICABILITY MATRIX — PRINCIPLE / ARCHITECTURE
ACTIVE CANONICAL ARCHITECTURE: YES
DERIVES FROM: CAMPAINER-FINAL-CORE-ARCHITECTURE-001 + CAMPAINER-CANONICAL-PRODUCT-FLOW-001 + CAMPAINER-ONE-TIME-CAMPAIGN-FLOW-001
SCHEMA AUTHORITY: NO
BUILD AUTHORITY: NO
RUNTIME AUTHORITY: NO
META WRITE / LAUNCH AUTHORITY: NO
PRODUCT OWNER AUTHORITY: PRESERVED


0. מטרת המסמך
מסמך זה ממפה לכל Stage ב־Canonical Product Flow אילו Cores הם בעלי אחריות ראשית, אילו Cores נדרשים, אילו מופעלים רק לפי Decision Need, איזה Context/Knowledge מוקרן, מי מחזיק Decision/Authority/Execution, מה נכתב כראיה, ולאן מבצעים Semantic Return / Reopen.


המטריצה אינה יוצרת ליבה חדשה, אינה הופכת את כל 13 הליבות ל־Always On, ואינה מקבעת Schema או Runtime implementation. Applicability הוא Stage- and Decision-Need-specific.


1. מקרא
P = Primary professional owner / owner of the stage's main professional meaning.
R = Required contribution for the stage to close responsibly.
C = Conditional contribution; activated only when the current Decision Need requires it.
— = Not ordinarily applicable in this Stage.


Core codes:
ADV = Advisor
K/E = Knowledge / Evidence
CTX = Complete User Context
DIR = Director
GL = Golden Lead
MET = Metrics / Measurement
LRN = Learning / Evolution
META = Meta
EO = Execution Orchestration
BRAND = Brand / Brand Assets
CR = Creative
M/B = Media / Budget
EXP = Experience / Interface


Cross-cutting note:
Sales / Lead Handling, Business Economics, Industry, External Signals and Marketing Strategy are Professional Knowledge families, not additional Cores. They enter through K/E and are consumed by the relevant professional owners.
Commercial / Billing is not a Core. Payment is a commercial downstream contract and must remain separate from Approval / Authorization / Execution.


2. Shared Entry Router
ENTRY — בחירה בין Business/Ongoing לבין One-Time
Primary: EXP for interaction; ADV for professional continuity.
Required Cores: ADV, EXP.
Conditional Cores: CTX when an existing user/business context exists; K/E only if explanation is needed.
Context Projection: user identity and active business scope only when already known and useful; no deep business context required.
Knowledge Need: none by default.
Decision owner: User chooses the branch; this is not a hidden professional classification gate.
User-facing owner: ADV through EXP.
Authority source: User branch choice only; no external execution authority.
Execution owner: none.
Evidence writes: selected branch, active scope if known, timestamp/state transition at implementation layer.
Semantic Return: if later evidence shows the selected branch is professionally mismatched, return to ADV for explanation and user choice; no silent branch conversion.
Reopen: user changes branch or the task is shown to be ongoing vs one-time in substance.


3. Branch A — Business / Ongoing


A1 — Short Diagnosis / Minimum Sufficient Initial Understanding
Primary: ADV.
Required Cores: DIR, CTX, K/E, EXP.
Conditional Cores: GL, MET.
Context Projection: active Business, Offering, goal, known state, relevant prior commitments/history.
Knowledge Need: scoped business/industry/customer/strategy priors that can improve hypotheses or questions; Prior ≠ Local Fact.
Decision owner: DIR frames what must be understood now; ADV owns professional synthesis/user-facing understanding.
User-facing owner: ADV through EXP.
Authority source: user statements/corrections create scoped local claims where appropriate; no execution authority.
Execution owner: none.
Evidence writes: local claims, source, scope, confidence/status, corrections, material Unknowns.
Semantic Return: to ADV/DIR when information conflicts or minimum understanding cannot be reached without a new targeted question/evidence source.
Reopen: material new information that changes the initial understanding.


A2 — Strategy Initial + Route Recommendation
Primary: ADV.
Required Cores: DIR, CTX, K/E, EXP.
Conditional Cores: GL, META, MET, M/B.
Context Projection: minimum local truth needed to explain current state, goal, opportunity/problem and constraints.
Knowledge Need: strategy/business/customer priors; relevant contradictions/unknowns; Meta possibility view only when it can change the route/feasibility.
Decision owner: DIR frames; ADV forms and explains the professional recommendation.
User-facing owner: ADV through EXP.
Authority source: Recommendation is not permission; user may accept/reject/defer the commercial route.
Execution owner: none.
Evidence writes: Strategy Initial version, evidence basis, assumptions, Unknowns, route recommendation, rationale and reconsideration conditions.
Semantic Return: to A1/ADV-DIR if material local truth is missing/contradicted; to domain owner if a feasibility input changes the recommendation.
Reopen: business/offering/goal change or contradictory evidence.
Invariant: Route Recommendation is the final chapter/conclusion of Strategy Initial, not a separate Stage.


A3 — Choice / Service Scope / Payment
Primary: ADV for explanation; EXP for interaction.
Required Cores: ADV, EXP, CTX.
Conditional Cores: DIR when scope must be re-decided.
Context Projection: selected route/scope, commercial choice and only the local facts needed to explain the purchase.
Knowledge Need: none by default; no professional corpus should be activated merely to process payment.
Decision owner: User chooses the commercial scope.
User-facing owner: ADV through EXP.
Authority source: User payment/choice for the service contract only.
Execution owner: Commercial/Billing downstream contract; not a Domain Core.
Evidence writes: selected scope, commercial state, payment status/reference at implementation layer.
Semantic Return: to ADV/DIR if a requested commercial scope contradicts the professional route or requires material scope change.
Reopen: material change in scope, duration or cost.
Invariant: Payment ≠ Strategy Approval ≠ Creative Approval ≠ Execution Authorization ≠ Launch.


A4 — Progressive Deep Diagnosis + Baseline
Primary: ADV for professional understanding.
Required Cores: CTX, DIR, K/E, MET, EXP.
Conditional Cores: GL, BRAND, M/B, META.
Context Projection: Business, Offering, Customer/Account, Buyer State, Buying Situation, Journey, goals, economics/capacity, sales handling, Brand/Proof state and known constraints only as decision-relevant.
Knowledge Need: decision-specific professional knowledge; targeted evidence acquisition; no fixed questionnaire corpus.
Decision owner: DIR frames depth and current decision needs; ADV synthesizes.
User-facing owner: ADV through EXP.
Authority source: user/local source authority for facts and corrections; no execution authority.
Execution owner: none.
Evidence writes: local claims/facts, Baseline Snapshot, source/lineage, material Unknowns, planned concurrent changes, measurement availability.
Semantic Return: to source/owner of missing local truth; to MET when measurement meaning is unclear; to DIR when depth must be changed.
Reopen: new evidence, contradiction, material business change, outcome maturation, new decision need.
Invariant: stop asking when remaining Unknowns no longer materially change Strategy, Audience, Offer, Creative, Executability, Risk or Measurement.


A5 — Full Strategy
Primary: ADV.
Required Cores: DIR, CTX, K/E, GL, EXP.
Conditional Cores: MET, META, M/B, BRAND.
Context Projection: current/desired state, buyer/account/buying situation, goal, constraints, baseline and relevant business truth.
Knowledge Need: candidate mechanisms/strategies, evidence for/against, contradictions, scoped priors, measurement implications.
Decision owner: DIR owns the Decision Frame; ADV owns professional judgment/recommendation and explanation.
User-facing owner: ADV through EXP.
Authority source: user choice/strategy approval when required; still no external write authority.
Execution owner: none.
Evidence writes: decision lineage, strategy version, evidence/Unknowns, selected strategic intent, user choice/approval state where applicable.
Semantic Return: to A4 when local understanding is insufficient; to META/M/B/BRAND/MET when a specialist constraint must be clarified; back to ADV/DIR if specialist input changes meaning.
Reopen: goal, bottleneck, offering, buyer state, constraint or material evidence changes.
Invariant: Marketing Problem/Bottleneck precedes material Strategy; platform convenience does not choose Strategy.


A6 — Studio
Primary: BRAND inside Brand Assets room; CR inside Creative room.
Required Cores: ADV, CTX, K/E, BRAND, CR, EXP.
Conditional Cores: DIR, META, MET, EO.
Context Projection: strategic intent, buyer state, offer/CTA, Brand scope, approved assets/proof, rights/consent/provenance, protected elements, relevant campaign context.
Knowledge Need: Brand/asset knowledge and Creative/Graphic professional knowledge; platform/measurement knowledge only as needed for execution/testability.
Decision owner: BRAND owns Brand truth/readiness decisions; CR owns representation/concept/execution judgment inside constraints; ADV/DIR remain owners of strategic meaning.
User-facing owner: ADV through EXP; Studio is one product place with two rooms.
Authority source: protected Brand changes and material creative/claim changes require the appropriate approval; ordinary creative freedom stays inside approved boundaries.
Execution owner: EO only conditionally for external production/provider coordination; not for professional creative judgment.
Evidence writes: Brand Snapshot/version, asset lineage/rights state, creative intent/concept/execution lineage, unresolved material gaps.
Semantic Return: CR → BRAND/ADV when proof/asset/rights/brand truth blocks faithful execution; BRAND → ADV/DIR when requested expression requires strategic repositioning.
Reopen: asset/rights/proof/strategy change, campaign evidence, creative issue or Brand Change Candidate.
Invariant: Studio = one place; Brand Core ≠ Creative Core.


A7 — Campaign / Execution Readiness
Primary: DIR.
Required Cores: ADV, CTX, K/E, GL, MET, META, BRAND, CR, M/B, EXP.
Conditional Cores: EO.
Context Projection: approved strategic intent, campaign package, economics/capacity, Golden Lead/business realization context, permissions/current state, baseline/measurement state.
Knowledge Need: media allocation, current Meta capability, measurement readiness, lead-handling/business-realization, relevant platform/industry constraints.
Decision owner: DIR integrates the readiness decision; each domain owns its professional contribution.
User-facing owner: ADV through EXP.
Authority source: no live authority is created here; readiness ≠ authorization.
Execution owner: none yet; EO may contribute dependency/preflight planning.
Evidence writes: readiness decision, unresolved manageable gaps, Media decision basis, Meta possibility/current-state evidence, measurement readiness, dependencies/return conditions.
Semantic Return: to the domain that owns the broken meaning (Studio, Strategy, Media, Meta, Metrics, Context); no mechanical checklist fallback.
Reopen: freshness failure, technical impossibility, budget/economics/capacity change, measurement gap or contradiction.
Invariant: START NOW / START+COMPLETE IN PARALLEL / RESPONSIBLE ALTERNATIVE / WAIT / PRESERVE / genuine STOP.


A8 — Campaign Review + User Approval
Primary: ADV for explanation; EXP for interaction.
Required Cores: ADV, EXP, CTX, DIR.
Conditional Cores: BRAND, CR, M/B, META, MET, GL, K/E.
Context Projection: exact campaign/plan version proposed for approval plus relevant assumptions/risks.
Knowledge Need: none by default beyond what already supports the proposal; activate only to answer a decision-relevant user question.
Decision owner: User approves/rejects/requests change; DIR/ADV preserve professional meaning.
User-facing owner: ADV through EXP.
Authority source: User approval scoped to the presented campaign/plan.
Execution owner: none.
Evidence writes: approved version, user corrections, approval scope, rejected/deferred items.
Semantic Return: to the relevant prior Stage when requested changes alter strategy, brand truth, budget, measurement or campaign meaning.
Reopen: user requests material change or new evidence changes the proposed plan.
Invariant: Campaign/Creative/Plan Approval ≠ Execution Authorization in the pilot.


A9 — Authorization → Fresh Preflight → Launch → Verified Readback
Primary: EO.
Required Cores: META, CTX, ADV, EXP.
Conditional Cores: MET, M/B, BRAND, CR, DIR.
Context Projection: authorized action target/scope, approved intent, authority state, relevant current live state, protected constraints, expected resulting state.
Knowledge Need: current platform/permission/capability knowledge and action-specific technical constraints; no new Strategy selection.
Decision owner: authorization comes from the user/authorized owner; DIR/ADV remain decision owners for any semantic change returned upstream.
User-facing owner: ADV through EXP for authorization and material execution status.
Authority source: explicit scoped Authorization; payment, prior connection or vague assent are insufficient.
Execution owner: EO coordinates; META supplies current platform truth/adapters.
Evidence writes: authorization, preflight state, execution attempts, receipt, readback, final/uncertain state, failure/recovery/rollback state.
Semantic Return: to DIR/ADV or relevant domain when exact intent cannot be executed faithfully; no closest-valid Shadow Decision.
Reopen: stale state, permission change, failure, partial success, non-equivalent path, readback contradiction.
Invariant: Execution attempt ≠ verified state change.


A10 — Managed Marketing + Lead / Business Realization
Primary: DIR for each active decision moment.
Required Cores: ADV, CTX, GL, MET, M/B, EXP.
Conditional Cores: K/E, CR, BRAND, META, EO, LRN.
Context Projection: current campaign state, lead/opportunity progression, sales treatment, capacity, economics, changes/interventions, relevant goals and active commitments.
Knowledge Need: media, sales/lead handling, measurement, creative/brand/platform knowledge activated by the current bottleneck/opportunity.
Decision owner: DIR frames; relevant domain owns its professional judgment; ADV recommends/explains.
User-facing owner: ADV through EXP.
Authority source: each material budget/live/business intervention requires its own appropriate approval/authorization.
Execution owner: EO only for authorized changes; user/business may own tasks/interventions outside platform execution.
Evidence writes: campaign changes, lead handling/treatment state, user/business interventions, outcomes, spend, capacity, concurrent changes, decision/authority lineage.
Semantic Return: to Studio/Strategy/Media/Meta/Metrics/Context according to the discovered issue.
Reopen: any material new evidence, risk, drift, goal change, outcome maturation or contradiction.
Invariant: Potential Lead Quality ≠ Business Realization Capability ≠ Realized Outcome.


A11 — Measurement → Learning → Next Decision
Primary: MET for measurement meaning; LRN for candidate lifecycle.
Required Cores: CTX, K/E, DIR, ADV, EXP, MET, LRN.
Conditional Cores: GL, M/B, CR, BRAND, META, EO.
Context Projection: intervention/change history, baseline/current state, outcomes, exposure/treatment semantics, relevant business changes.
Knowledge Need: measurement/causal knowledge, transferability rules, contradictions, prior evidence and domain-specific interpretation as needed.
Decision owner: MET determines what may be inferred; LRN governs candidate status; DIR/ADV own the next professional decision.
User-facing owner: ADV through EXP.
Authority source: no execution authority by default; any next action re-enters the appropriate authority chain.
Execution owner: none unless the next decision is authorized and routed downstream.
Evidence writes: result, measurement interpretation, uncertainty/causal class, Learning Candidate, validation/scope disposition, Context/Knowledge update references.
Semantic Return: to the Stage/domain whose decision must change; not automatically to the beginning.
Reopen: contradiction, replication failure, drift, new evidence, outcome maturation.
Invariant: Result → Metrics Interpretation → Learning Candidate → governed update; never Result → “system learned” → Truth.


4. Branch B — One-Time Campaign


B1 — One-Time Campaign Intake
Primary: ADV.
Required Cores: CTX, K/E, EXP.
Conditional Cores: DIR, GL, MET, META, M/B.
Context Projection: campaign-scoped local truth only — what is being advertised, purpose, audience/area, time, budget, offer/CTA/destination, assets, constraints and end condition.
Knowledge Need: only knowledge that can change the specific campaign decision; no business diagnosis corpus by default.
Decision owner: ADV professional judgment; DIR only when a bounded decision frame is materially useful.
User-facing owner: ADV through EXP.
Authority source: user supplies/corrects scoped campaign facts; no execution authority.
Execution owner: none.
Evidence writes: one-time scope, local claims, source, time, constraints, Unknowns, proposed end condition.
Semantic Return: to user/ADV for missing material facts; to ongoing branch only by explicit user choice if the need is actually ongoing.
Reopen: time, goal, audience, area, offer, budget, destination or end condition changes.
Invariant: no Short Business Diagnosis, Strategy Initial or Full Strategy requirement.


B2 — One-Time Brief + Advisor Recommendation
Primary: ADV.
Required Cores: CTX, K/E, EXP.
Conditional Cores: DIR, M/B, META, MET, GL, BRAND, CR.
Context Projection: minimum campaign truth sufficient to explain what should be built and managed.
Knowledge Need: campaign/media/creative/platform/measurement knowledge only as required by the brief.
Decision owner: ADV; DIR frames only when materially needed.
User-facing owner: ADV through EXP.
Authority source: recommendation is not permission.
Execution owner: none.
Evidence writes: brief version, recommendation, rationale, time/budget assumptions, end condition, Unknowns.
Semantic Return: to B1 when campaign truth is insufficient; to domain owner if feasibility changes the recommendation.
Reopen: material scope/goal/time/budget change.


B3 — One-Time Scope + Price + Payment
Primary: ADV for explanation; EXP for interaction.
Required Cores: ADV, EXP, CTX.
Conditional Cores: DIR.
Context Projection: one-time service scope and commercial terms only.
Knowledge Need: none by default.
Decision owner: User commercial choice.
User-facing owner: ADV through EXP.
Authority source: payment for service only.
Execution owner: Commercial/Billing downstream contract.
Evidence writes: scope/payment state.
Semantic Return: to ADV/DIR if requested scope changes the professional recommendation.
Reopen: material scope, production or cost change.
Invariant: Service Price ≠ Media Budget; Payment ≠ Authorization.


B4 — One-Time Studio
Primary: BRAND inside Brand Assets room; CR inside Creative room.
Required Cores: ADV, CTX, K/E, BRAND, CR, EXP.
Conditional Cores: DIR, META, MET, EO.
Context Projection: One-Time Brief, campaign job, audience/time/CTA, uploaded assets, rights/provenance and relevant Brand scope.
Knowledge Need: Brand/asset + Creative professional knowledge, plus placement/measurement constraints as needed.
Decision owner: BRAND and CR within their boundaries; ADV owns campaign meaning.
User-facing owner: ADV through EXP.
Authority source: protected Brand/material claim changes require appropriate approval.
Execution owner: EO only for external production coordination where needed.
Evidence writes: scoped Brand Snapshot, asset/rights lineage, creative lineage, gaps/returns.
Semantic Return: CR → BRAND/ADV; BRAND → ADV/DIR when meaning must change.
Reopen: asset/rights/proof/campaign brief change.


B5 — One-Time Campaign Review + User Approval
Primary: ADV + EXP.
Required Cores: ADV, EXP, CTX.
Conditional Cores: DIR, BRAND, CR, M/B, META, MET, K/E.
Context Projection: exact one-time campaign version and scope.
Knowledge Need: only for answering material approval questions.
Decision owner: User approval.
User-facing owner: ADV through EXP.
Authority source: campaign approval only.
Execution owner: none.
Evidence writes: approved version, corrections, approval scope.
Semantic Return: to B2/B4 when change is material.
Reopen: user requests material change or new evidence emerges.
Invariant: Approval ≠ Authorization.


B6 — One-Time Authorization + Preflight + Launch + Readback
Primary: EO.
Required Cores: META, CTX, ADV, EXP.
Conditional Cores: MET, M/B, BRAND, CR, DIR.
Context Projection: authorized one-time action, campaign scope, budget/spend authority, current platform state, end condition and expected result state.
Knowledge Need: current Meta/technical capability and action-specific constraints.
Decision owner: User/authorized owner for launch/spend; upstream owners for any returned semantic change.
User-facing owner: ADV through EXP.
Authority source: explicit scoped Authorization.
Execution owner: EO + META technical surface.
Evidence writes: authorization, preflight, execution, receipt, readback, final/uncertain state.
Semantic Return: to ADV/DIR/domain owner when faithful execution is not possible.
Reopen: failure, permission/current-state change, partial success or readback contradiction.
Invariant: payment and campaign approval do not substitute for launch authorization.


B7 — One-Time Managed Run
Primary: DIR for active decision moments.
Required Cores: ADV, CTX, MET, M/B, EXP.
Conditional Cores: META, EO, CR, BRAND, GL, K/E, LRN.
Context Projection: one-time campaign state, remaining time/budget, current results, destination, relevant lead/business outcomes, end condition.
Knowledge Need: media/measurement/creative/platform knowledge activated only by current run decisions.
Decision owner: DIR frames; M/B owns allocation judgment; ADV recommends/explains.
User-facing owner: ADV through EXP.
Authority source: material changes beyond existing authorized bounds require new approval/authorization.
Execution owner: EO for authorized live changes.
Evidence writes: spend/delivery, creative/media changes, outcomes, decision basis, authority, concurrent changes.
Semantic Return: to B4/B6/B2 according to the issue.
Reopen: time remaining, budget, result maturity, technical/creative issue, changed event/offer/destination.
Invariant: One-Time ≠ one ad ≠ no management.


B8 — End Condition + Closure
Primary: EO for operational closure; ADV for professional/user-facing closure.
Required Cores: CTX, META, ADV, EXP.
Conditional Cores: MET, M/B, DIR.
Context Projection: approved end condition, live state, remaining spend, outstanding obligations and closure requirements.
Knowledge Need: current platform/closure capability only as needed.
Decision owner: predefined end condition where valid, or user/authorized owner when closure is discretionary; no autonomous extension.
User-facing owner: ADV through EXP.
Authority source: pre-approved end condition and/or explicit user instruction according to downstream contract.
Execution owner: EO + META.
Evidence writes: stop/closure action, readback, final spend/state, unresolved obligations.
Semantic Return: to ADV/DIR if the end condition is ambiguous or closure would violate a newer material decision.
Reopen: end condition changes, event/offer extends, user changes instruction, closure failure.
Invariant: no one-time campaign remains live merely because nobody remembered to stop it.


B9 — Measurement + Summary + Learning Return
Primary: MET for measurement; LRN for learning candidate lifecycle.
Required Cores: ADV, CTX, EXP, MET.
Conditional Cores: K/E, DIR, LRN, GL, M/B, CR, BRAND, META.
Context Projection: final campaign scope, spend, timeline, interventions/changes, outcomes and closure state.
Knowledge Need: measurement/causal interpretation and scoped learning/transferability only.
Decision owner: MET determines permitted inference; ADV explains; LRN governs any candidate when warranted.
User-facing owner: ADV through EXP.
Authority source: none by default.
Execution owner: none.
Evidence writes: final result, measurement limits, summary, Unknowns, local learning, candidate references if any.
Semantic Return: to Context for local updates; to Knowledge/Learning only through governed candidate paths.
Reopen: late-maturing outcome, corrected data, contradiction or future one-time campaign that needs relevant history.
Invariant: summary is not an Ads Manager dump; local learning does not auto-promote to permanent Business/Brand truth.


5. Cross-Stage Applicability Rules
1. ADV is the continuous user-facing professional identity but is not automatically the owner of every domain decision.
2. EXP is active when the user must understand, choose, approve, correct, see status or receive a professional result; it does not create truth.
3. CTX is the local-truth source. It is not copied wholesale into every Stage.
4. K/E is activated by Knowledge Need, not by habit. Accessible knowledge ≠ retrieved ≠ used.
5. DIR is active when there is a bounded decision to frame; it is not a global always-on God Object.
6. GL is required when desirability/value/serviceability/realization materially affect the decision; it is not a universal score.
7. MET is required whenever measurement meaning, baseline, outcome maturity or permitted inference matters.
8. LRN is required for governed learning-candidate lifecycle, not every observation.
9. META is required for current platform truth and live feasibility; capability never creates authority.
10. EO is required only when an authorized action must be coordinated/executed/verified or when operational closure/recovery is required.
11. BRAND and CR are separate professional owners inside the same Studio product place.
12. M/B is required for material paid-media resource allocation decisions; average KPI alone never governs the next allocation.
13. No Stage may infer another Stage’s approval/authorization.
14. Semantic Return targets the owner of the broken meaning, not a generic “previous screen”.
15. Reopen returns to the professional Stage that owns the newly reopened decision.


6. Human Review — Pilot
For the controlled pilot, 100% Human Review remains required for material professional and execution decisions.


At minimum this includes:
material Strategy recommendation/approval;
material Brand/claim changes;
material Creative approval where it affects campaign meaning;
material Media/Budget decisions;
Launch and other material live writes;
material business interventions;
execution recovery/rollback decisions when semantics or risk may change;
learning candidates proposed for broader reuse/promotion.


Exact future automation/risk tiers remain Deferred.


7. Architecture collision check
No new Core is required by this matrix.


Commercial/Billing remains a downstream contract, not a Core.
Sales/Lead Handling remains Professional Knowledge + local Context/Measurement/Golden/Advisor inputs, not a new Horizontal Core.
Studio remains one product place with two Core ownership domains.
The matrix preserves Context vs Knowledge, Director vs Advisor, Metrics vs Learning, Golden Lead vs Media, Media vs Meta, Meta vs Orchestration, Brand vs Creative and Experience vs professional-truth boundaries.


8. Acceptance gates for matrix approval
The matrix can be promoted only if:
every canonical Stage has a primary professional owner;
Required vs Conditional applicability is explicit;
no row makes all 13 Cores indiscriminately active;
Context Projection is minimum-sufficient and scoped;
Knowledge Need is decision-driven;
Decision owner and user-facing owner are not conflated;
Payment is not treated as authority;
Approval/Authorization/Execution are separated;
Execution owner is explicit where live action exists;
Evidence writes are defined at principle level;
Semantic Return points to the owner of broken meaning;
Reopen returns to the correct professional Stage;
One-Time branch is fully covered;
Studio’s two rooms remain separate professionally;
measurement/learning boundaries are preserved;
100% Human Review is preserved for material pilot decisions.


9. Status / next derivation
CURRENT STATUS: OWNER-APPROVED FLOW CORE APPLICABILITY MATRIX — PRINCIPLE / ARCHITECTURE.
This document became Active Canonical Architecture through explicit Product Owner approval; folder location alone remains insufficient to create authority.


Product Owner approval completed. The next derivation is:
FLOW STAGE CORES / STAGE TRUTH
→ DECISION & HANDOFF CONTRACTS
→ BUILD PACKAGES.


10. CROSS-FLOW EXPERIENCE APPLICABILITY ADDENDUM
על כל שורות A1–A11 ו-B1–B9 חלה שכבת Experience תוספתית לפי מקור ID 1VDtgvqECgPvY2jj2huUD5gAMgF7f6o0PPf7neWuGt6U.
Experience / Interface: REQUIRED להצגת scope, state, unknown, recommendation, decision/action boundary, progress ו-readback.
Advisor: REQUIRED ככניסה עקבית וזהות מקצועית רציפה, אך אינו Gate חובה והממשק הישיר נשאר שמיש.
Context ו-Director: CONDITIONAL/REQUIRED לפי Decision Need לצורך Minimum-Sufficient Screen/Advisor Projection; אין הרחבת ownership.
יתר הליבות מופעלות לפי המטריצה הקיימת בלבד. שכבת החוויה אינה הופכת את כל 13 הליבות לפעילות בכל Stage ואינה יוצרת סמכות ביצוע.


END — CAMPAINER-FLOW-CORE-APPLICABILITY-MATRIX-001 — v1.0
