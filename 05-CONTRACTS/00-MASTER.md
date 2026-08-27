---
mirror_role: "Base44 read/reference mirror"
canonical_source: "Google Drive"
source_title: "CAMPAINER-DECISION-AND-HANDOFF-CONTRACTS-MASTER-001 — v1.0"
source_drive_id: "18xPbrFLWt64vGeVkqY8mJ-smYXntKFaXG1Kh7cof-P8"
source_modified_at: "2026-08-18T17:48:31.142Z"
corpus_status: "current-v1.0"
category: "contract"
---

> MIRROR NOTICE: This file is a controlled copy for Base44. Google Drive remains the canonical source. Do not infer implementation, deployment, runtime, or release authority from repository presence.

## Canonical source body

CAMPAINER-DECISION-AND-HANDOFF-CONTRACTS-MASTER-001 — v1.0
Decision & Handoff Contracts Master


STATUS: OWNER-APPROVED DECISION & HANDOFF CONTRACTS MASTER — PRINCIPLE / CONTRACT
ACTIVE CANONICAL CONTRACT ARCHITECTURE: YES
SCHEMA AUTHORITY: NO
BUILD AUTHORITY: NO
RUNTIME AUTHORITY: NO
META WRITE / LAUNCH AUTHORITY: NO
PRODUCT OWNER AUTHORITY: PRESERVED
DERIVES FROM: Final Core Architecture v1.0 + Canonical Product Flow v1.0 + Flow Core Applicability Matrix v1.0 + Stage Truth Master v1.0 + 21 Stage Truth artifacts.


0. מטרת המסמך
מסמך זה מגדיר את חוזי המשמעות והסמכות במעברים שבהם Decision, Professional Meaning, Authority, Execution או Learning עוברים בין Stage/Core/Actor. הוא אינו יוצר חוזה מלאכותי בין כל שני מסכים. חוזה נדרש כאשר מעבר לא־מוגדר עלול לגרום Semantic Loss, Shadow Decision, Authority Leak, Scope Drift או אובדן Traceability.


Contract אינו API schema. הוא קובע what must travel and what must remain distinct. Exact fields, object IDs, enums, payloads, APIs, persistence and runtime mechanics remain Deferred.


1. דוקטרינת החוזים
1. Producer אינו רשאי להניח שה־Receiver מכיר את כל ההקשר.
2. Receiver מקבל Minimum-Sufficient Projection — לא whole-corpus dump.
3. Scope travels with meaning.
4. Unknown travels as Unknown; absence אינו Zero/Fail.
5. Authority travels explicitly or is absent explicitly.
6. Payment never implies Approval/Authorization/Execution.
7. Approval never implies live Authorization unless a future explicitly approved contract says so for that exact low-risk class; pilot default remains separate.
8. Technical capability never expands authority.
9. Receiver may exercise only bounded professional discretion granted by its Core + contract.
10. If faithful execution/interpretation is impossible, Semantic Return is mandatory.
11. Return names what remains valid, what broke, why, and who owns the next decision.
12. Material handoffs preserve evidence/decision lineage without storing private chain-of-thought.
13. Human Review applies according to the Stage Truth and pilot policy.


2. Common Semantic Envelope — Principle Level
Every material contract can require the following semantic families when relevant:
A. Identity / Scope — user, Business, Offering, Campaign, One-Time Campaign, Asset, Account/Lead/Opportunity or other subject identity.
B. Intent / Meaning — what is being decided or executed and why.
C. Applicable Stage / Decision Need — current decision frame and expected receiver job.
D. Local Context Projection — only verified/current/scoped local truth needed by the receiver.
E. Knowledge / Evidence Projection — relevant claims, priors, counterevidence, contradictions, unknowns, scope, maturity/freshness.
F. Epistemic State — known / inferred / unknown / pending / contradicted as appropriate; exact enum deferred.
G. Freshness — which facts/capabilities must be rechecked and at what boundary conceptually.
H. Authority State — recommendation / choice / approval / authorization / none; exact implementation deferred.
I. Protected Constraints — Brand Truth, rights/consent/provenance, budget envelope, claims, goal, audience meaning, measurement target, legal/ethical constraints, End Condition.
J. Receiver Discretion — what the receiver may choose professionally and what it may not redefine.
K. Required Output / Return — expected result, evidence write, acknowledgement or Semantic Return.
L. Lineage — upstream decision/evidence/version references and downstream result/readback linkage.


3. Contract Families


C-01 — BRANCH-CHOICE-HANDOFF
Applies: ENTRY → A1 or ENTRY → B1.
Trigger: User chooses Business/Ongoing or One-Time.
Producer: Experience/Advisor interaction.
Receiver: A1 or B1 professional stage.
Must carry: branch identity, user identity, active Business scope only if known/relevant, explicit user choice, no inferred live authority.
Receiver discretion: may explain mismatch later; may not silently move the user to the other branch.
Output: correct branch context established.
Return: to Advisor/User Choice if later evidence shows substantive mismatch.
Evidence: branch choice + scope reference.
Invariant: branch selection is user choice, not hidden classification.


C-02 — INITIAL-UNDERSTANDING-TO-STRATEGY-INITIAL
Applies: A1 → A2.
Trigger: Minimum Sufficient Initial Understanding reached.
Producer: A1 / Advisor + Director + Context/Knowledge contributors.
Receiver: A2 / Advisor professional judgment.
Must carry: Business/Offering/Goal/current state, material local claims, relevant source/evidence, scoped priors, contradictions, Unknowns, confidence/status where material, decision frame.
Must not carry: guessed local facts or an already-fixed Route Recommendation.
Receiver discretion: synthesize insights and recommendation; cannot convert Prior into Local Fact.
Output: Strategy Initial + three insights + Route Recommendation as conclusion.
Return: to A1 when missing/contradictory local truth can change the recommendation.
Evidence: Strategy Initial lineage to A1 facts/evidence.


C-03 — RECOMMENDATION-TO-COMMERCIAL-SCOPE
Applies: A2 → A3 and B2 → B3.
Trigger: Professional recommendation is understandable enough for commercial choice.
Producer: Advisor.
Receiver: Commercial/Experience layer + User Choice.
Must carry: recommended scope/service basis, rationale, what is included/excluded, assumptions, reconsideration conditions, relevant duration/management scope, separation of service price from media/other cost layers.
Authority state: Recommendation only; User Choice/Payment may occur downstream.
Must not carry: external-write authority, Meta spend authority or claim that purchase proves strategy approval.
Return: to Advisor/Director if requested commercial scope materially changes professional recommendation.
Evidence: selected/rejected/deferred scope and payment state.
Invariant: professional recommendation cannot be distorted to fit a commercial package silently.


C-04 — PAYMENT-TO-PROFESSIONAL-WORK-ENTITLEMENT
Applies: A3 → A4; B3 → B4.
Trigger: Required service payment/entitlement confirmed.
Producer: Commercial/Billing downstream contract.
Receiver: next professional Stage.
Must carry: selected Service Scope, entitlement/payment state, relevant commercial commitments, duration/production scope where applicable.
Must not carry: Strategy Approval, Creative Approval, Meta write Authorization, Launch authority.
Receiver discretion: perform paid professional work inside the purchased scope; may Return if scope is professionally inconsistent.
Evidence: payment/entitlement reference + selected scope.
Invariant: Payment is a commercial prerequisite, not an authority token.


C-05 — DEEP-UNDERSTANDING-TO-FULL-STRATEGY
Applies: A4 → A5.
Trigger: Minimum Sufficient Understanding + scoped Baseline are sufficient for Full Strategy.
Producer: A4 / Advisor, Context, Director, Metrics, Knowledge and conditional domains.
Receiver: A5 / Advisor + Director.
Must carry: current/desired state, relevant Business/Offering/Buyer/Account/Buying Situation/Journey, economics/capacity, Golden Lead context where relevant, sales handling, Brand/Proof, constraints, Baseline, measurement meaning, material Unknowns, concurrent changes, relevant knowledge/evidence.
Receiver discretion: choose/recommend Strategy within evidence/constraints; cannot erase Unknown or infer causality from baseline.
Output: Strategic Intent and strategy decision package.
Return: to A4 or owning domain when the decision cannot be made faithfully.
Evidence: Full Strategy decision lineage.


C-06 — STRATEGIC-INTENT-TO-STUDIO
Applies: A5 → A6.
Trigger: Strategic Intent closed enough for Brand/Creative work.
Producer: Advisor/Director + applicable strategy contributors.
Receiver: Studio — Brand Assets room and Creative room.
Must carry: strategic job, desired buyer-state change, Must-Believe, Proof Requirement, Offer/CTA/route intent, audience/buyer meaning, Brand scope, protected elements, relevant assets/proof, rights/consent/provenance state, platform/measurement constraints when material, Unknowns and no-go changes.
Brand discretion: determine Brand truth/readiness/assets within Brand Core.
Creative discretion: Representation → Concept → Execution inside strategic/brand constraints.
Must not allow: Creative silently changing Strategy; Brand inventing campaign strategy.
Return: Creative → Brand/Advisor for proof/asset/rights/meaning failure; Brand → Advisor/Director for strategic repositioning need.
Evidence: Brand Snapshot + creative lineage linked to Strategic Intent.


C-07 — ONE-TIME-BRIEF-TO-STUDIO
Applies: B2/B3 → B4.
Trigger: One-Time recommendation defined and paid scope active when required.
Producer: Advisor + commercial state.
Receiver: One-Time Studio.
Must carry: what is advertised, purpose, audience/area, time window, budget frame, Offer/CTA/destination, End Condition, campaign job, uploaded assets if any, relevant Brand scope, constraints/forbidden representations, Unknowns, service/production scope.
Must not carry: requirement for Short Business Diagnosis, Strategy Initial or Full Strategy.
Receiver discretion: build minimum-sufficient Brand Snapshot and Creative Package; no full Brand System unless needed/authorized.
Return: to B2 when brief meaning changes; to user/Advisor for missing material facts.
Invariant: One-Time remains campaign-specific, not a disguised ongoing diagnosis.


C-08 — CAMPAIGN-PACKAGE-TO-USER-REVIEW
Applies: A7 → A8; B4/B5 review boundary and any equivalent one-time review package.
Trigger: Campaign/plan is responsible and understandable enough for user review.
Producer: Director/Advisor + relevant Brand/Creative/Media/Meta/Metrics contributors.
Receiver: User through Advisor/Experience.
Must carry: exact version, what will be published, audience/scope meaning, Offer/CTA/destination, budget envelope, time/window, creative/assets, material assumptions/risks/Unknowns, measurement intent, unresolved manageable gaps, what approval covers.
Authority state: no live Authorization yet.
Receiver discretion: approve/reject/request change; user is not asked to choose professional mechanics that Campainer owns.
Return: to owning Stage when requested change alters strategy, Brand truth, creative meaning, budget, measurement or feasibility.
Evidence: approved/rejected/deferred version + corrections + approval scope.


C-09 — APPROVAL-TO-AUTHORIZATION-GATE
Applies: A8 → A9; B5 → B6.
Trigger: exact campaign/plan version approved.
Producer: Approval Stage.
Receiver: Authorization interaction + Execution Orchestration boundary.
Must carry: exact approved version/reference, target scope, budget/spend envelope, material constraints, what is not authorized, outstanding conditions, note that Authorization is still absent until explicitly granted.
Authority rule: Approval ≠ Authorization. Payment ≠ Authorization. Prior account connection ≠ Authorization. Vague assent ≠ Authorization.
Output: explicit scoped Authorization or no authorization.
Return: if user changes meaning/scope during authorization, route back to professional owner; do not mutate the approved package in place silently.
Evidence: authorization subject, scope, actor/source and resulting authority state.


C-10 — AUTHORIZED-INTENT-TO-EXECUTION
Applies: inside A9 and B6; also any later material live change from A10/B7.
Trigger: explicit scoped Authorization exists for a material live action.
Producer: authorized decision state.
Receiver: Execution Orchestration + Meta technical surface/provider adapter.
Must carry: authorized intent, target identity, exact scope, budget/spend authority, protected constraints, expected state change, relevant current context, dependencies, readback requirement, expiry/freshness concept where relevant.
Fresh Preflight must validate: target, permissions, dependencies, current state, capability/eligibility, asset/destination state, measurement/readback availability, new conflicts.
Receiver discretion: adapt mechanics only when semantically equivalent and within authority.
Forbidden: closest-valid action that changes audience meaning, budget intent, strategy, claim, Brand truth or scope.
Return: mandatory if exact intent cannot be executed faithfully.
Evidence: authorization + preflight + attempt + receipt + recovery/rollback state.


C-11 — EXECUTION-TO-VERIFIED-STATE
Applies: A9 → A10; B6 → B7; closure execution in B8.
Trigger: execution attempt has occurred.
Producer: Execution Orchestration/Meta/provider.
Receiver: Context + managing professional Stage + Metrics when relevant.
Must carry: attempted action, provider receipt, readback evidence, resulting live state, discrepancies, partial success/failure, timestamp/freshness, uncertainty when readback impossible.
Rule: execution attempt ≠ verified state change; receipt ≠ live truth.
Context may store verified operational state; Unverified remains explicit.
Return: to EO/Meta or upstream decision owner on contradiction/partial/non-equivalent result.
Evidence: immutable execution/readback lineage at principle level.


C-12 — MANAGED-DECISION-TO-AUTHORIZED-CHANGE
Applies: within A10 and B7 whenever management recommends a material live/business change.
Trigger: live evidence produces a Recommendation/Test/Task/Allocation/Creative/Business Intervention decision.
Producer: Director + applicable professional domain + Advisor.
Receiver: User/authority owner and, after authorization, EO or business task owner.
Must carry: current state, decision trigger, evidence/maturity, recommended change, expected mechanism, budget/resource effect, risks/uncertainty, what remains unchanged, measurement intent, reopen/rollback conditions when material.
Authority: recommendation/test decision does not authorize live change by itself.
Execution: only after correct approval/authorization for the action class.
Return: to owning domain if requested change exceeds the original meaning or evidence.
Evidence: decision → authority → intervention → outcome linkage.


C-13 — MANAGED-EVIDENCE-TO-MEASUREMENT-LEARNING
Applies: A10 → A11; B8/B9 evidence path and interim one-time measurement when needed.
Trigger: outcome/evidence is mature enough to interpret for a decision, or a closure summary is required.
Producer: Context/operational systems/Meta/business-side evidence.
Receiver: Metrics first; Learning when a candidate lifecycle is warranted; Advisor/Director for next decision.
Must carry: baseline/current state, intervention/change history, exposure/treatment semantics, spend, lead/business outcomes, concurrent changes, missingness/maturity/coverage, relevant decision lineage.
Metrics discretion: determine valid metric/outcome meaning and permitted inference.
Learning discretion: manage candidate lifecycle only after measurement interpretation; no self-promotion.
Return: when data quality/maturity/causal meaning is insufficient.
Evidence: Measurement Interpretation + uncertainty + candidate references + next-decision linkage.
Invariant: Result ≠ Causal Explanation; Learning Candidate ≠ Truth.


C-14 — ONE-TIME-END-CONDITION-TO-CLOSURE
Applies: B7 → B8.
Trigger: predefined End Condition is met/approaching, user orders closure, or responsible stop condition arises.
Producer: managed one-time state + user/approved condition.
Receiver: EO operational closure + Advisor/Experience user-facing closure.
Must carry: exact End Condition, current live state, remaining budget/spend, outstanding obligations, relevant authority/closure instruction, expected post-closure state.
Authority: no autonomous extension beyond approved One-Time scope. Pre-approved End Condition may authorize the defined closure mechanics only to the extent future downstream contract explicitly implements that principle; discretionary material change requires user/owner decision.
Output: closure action + verified final state or explicit uncertainty.
Return: if End Condition is ambiguous or newer material decision conflicts.
Evidence: stop/closure action, readback, final spend/state, unresolved obligations.
Invariant: no one-time campaign remains live merely because nobody remembered to stop it.


C-15 — MEASUREMENT-LEARNING-TO-NEXT-DECISION / REOPEN
Applies: A11 → appropriate A-stage/domain; B9 → Context/future one-time decision; any late-maturing evidence reopen.
Trigger: measurement/learning produces a decision-relevant implication or valid Wait/Preserve/Do Nothing state.
Producer: Metrics + Learning + Advisor/Director.
Receiver: Stage/domain owning the next decision.
Must carry: what happened, what may/may not be inferred, maturity/confidence/Unknowns, candidate status if any, local truth updates, conditions that trigger next action, scope/transferability limits.
Must not carry: automatic cross-business generalization, automatic Brand Truth change, automatic strategy change, automatic execution authority.
Receiver discretion: reopen only the decision it owns.
Evidence: link previous intervention/result to next decision/reopen.
Invariant: Reopen is professional routing, not a generic back button.


C-16 — SEMANTIC-RETURN-CROSS-CUTTING-CONTRACT
Applies: any material handoff.
Trigger: receiver cannot preserve intent, scope, truth, authority or protected constraints; required evidence is missing; capability/freshness invalidates path; receiver discovers materially different problem; proposed fallback changes meaning.
Producer: receiving Core/Stage.
Receiver: owner of broken meaning/decision.
Return must state at principle level:
- original request/intent and Scope;
- what remains valid;
- what failed/is missing/contradicted/stale;
- evidence or capability basis;
- what cannot be assumed;
- whether current authorization remains valid, narrowed or unusable;
- next decision owner;
- safe alternatives if known without making the upstream decision.
Return must not silently substitute a new Strategy, audience, budget, Brand truth, claim, measurement target or action.
Evidence: Return event/decision lineage.


4. Shared Contract Boundaries
A. Context Projection is not ownership transfer. CTX remains owner of local truth.
B. Knowledge Projection is not truth adoption. K/E remains owner of epistemic status.
C. Director Decision Frame is not permanent system state and does not become Advisor persona.
D. Advisor Handoff is not private chain-of-thought. Transfer governed conclusions, evidence, assumptions, tradeoffs and decisions only.
E. Brand Snapshot does not make Creative owner of Brand Truth.
F. Creative Package does not make Media/Meta owner of creative meaning.
G. Media allocation decision does not make Meta owner of budget intent.
H. Meta capability evidence does not create authority or strategy.
I. EO receipt does not become Context truth until readback/verification semantics are satisfied.
J. Metrics interpretation precedes Learning candidate promotion logic.


5. One-Time Special Rules
1. B1/B2 contracts never require business Short Diagnosis, Strategy Initial or Full Strategy.
2. One-Time scope must carry Objective/Need, audience/area, time/window, budget, Offer/CTA/destination and End Condition when relevant.
3. User assets are optional; asset absence does not automatically block Studio.
4. Payment is explicit and separate from Media Budget and live Authorization.
5. Managed Run may last weeks/months; One-Time ≠ one ad ≠ no management.
6. Closure is part of the contract chain, not an operational afterthought.
7. Local learning from one-time work may inform future scoped context; it does not automatically become permanent Business/Brand/general truth.


6. Pilot Human Review Overlay
100% Human Review remains required for material professional/execution decisions including:
- material Strategy recommendation/approval;
- material Brand/claim changes;
- material Creative meaning decisions;
- material Media/Budget allocation decisions;
- Launch/material live writes;
- semantics-affecting recovery/rollback;
- material business interventions;
- material causal interpretation or broader learning-candidate reuse/promotion.
A contract may route through Human Review without changing domain ownership.


7. Acceptance Gates
This Contracts Master can be promoted only if:
- every contract maps to approved Stage Truth and does not invent a Stage;
- no contract creates a new Core or moves Core ownership;
- Minimum-Sufficient Context/Knowledge projections are preserved;
- Unknown/Freshness/Scope travel with meaning;
- Recommendation, Choice, Approval, Authorization, Execution and Readback remain distinct;
- Payment is never an authority source for live action;
- Studio contracts preserve Brand vs Creative separation;
- Media vs Meta vs EO boundaries remain intact;
- execution fallback requires semantic equivalence or Return;
- managed decisions preserve Lead Potential vs Business Realization vs Outcome separation;
- Measurement precedes Learning promotion semantics;
- One-Time End Condition/Closure is explicit;
- Semantic Return names the owner of broken meaning;
- Human Review overlay is preserved for the pilot;
- no exact schema/runtime implementation is accidentally canonized.


8. Intentionally Deferred
Exact field list; object IDs; enums/status codes; risk/permission tiers; authorization UX mechanics; approval UX mechanics; pricing/billing API; Meta object schemas; provider adapters; contract version negotiation; database persistence; event topics; retry/backoff; idempotency tokens; timeout rules; exact readback mechanisms; automation thresholds; low-risk action classes; privacy/legal implementation; detailed rollback mechanics; build sequencing.


9. Proposed Downstream Split After Owner Approval
If approved, split this Master into contract artifacts only where material:
01 Branch Choice Handoff
02 Initial Understanding → Strategy Initial
03 Recommendation → Commercial Scope
04 Payment → Professional Work Entitlement
05 Deep Understanding → Full Strategy
06 Strategic Intent → Studio
07 One-Time Brief → Studio
08 Campaign Package → User Review
09 Approval → Authorization
10 Authorized Intent → Execution
11 Execution → Verified State
12 Managed Decision → Authorized Change
13 Managed Evidence → Measurement/Learning
14 One-Time End Condition → Closure
15 Measurement/Learning → Next Decision/Reopen
16 Semantic Return Cross-Cutting.


After that: Build Package derivation may begin only when the required contracts for each build slice are approved. This document itself creates no Build Authority.


10. Status / Next Decision
CURRENT STATUS: OWNER-APPROVED DECISION & HANDOFF CONTRACTS MASTER — PRINCIPLE / CONTRACT.
OWNER DECISION: APPROVED. Canonical split into 16 material contract artifacts is authorized as faithful derivation; Build Package derivation may begin after split.


END — CAMPAINER-DECISION-AND-HANDOFF-CONTRACTS-MASTER-001 — v1.0
