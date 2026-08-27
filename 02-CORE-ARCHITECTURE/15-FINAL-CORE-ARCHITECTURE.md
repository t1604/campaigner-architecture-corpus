---
mirror_role: "Base44 read/reference mirror"
canonical_source: "Google Drive"
source_title: "CAMPAINER-FINAL-CORE-ARCHITECTURE-001 — v1.0 — ארכיטקטורת הליבות הסופית"
source_drive_id: "1uE7OGLVhvKSFHF2BRr5KNBvAds2_AoN4v_PQtxGOnEY"
source_modified_at: "2026-08-23T09:06:33.140Z"
corpus_status: "current-v1.0"
category: "core"
---

> MIRROR NOTICE: This file is a controlled copy for Base44. Google Drive remains the canonical source. Do not infer implementation, deployment, runtime, or release authority from repository presence.

## Canonical source body

CAMPAINER-FINAL-CORE-ARCHITECTURE-001 — v1.0
ארכיטקטורת הליבות הסופית של Campainer


STATUS: OWNER-APPROVED FINAL CORE ARCHITECTURE — PRINCIPLE / BOUNDARY
ACTIVE CANONICAL ARCHITECTURE: YES
SCHEMA AUTHORITY: NO
BUILD AUTHORITY: NO
RUNTIME AUTHORITY: NO
META WRITE / LAUNCH AUTHORITY: NO
PRODUCT OWNER AUTHORITY: PRESERVED


0. מעמד וסמכות המסמך
מסמך זה מקבע את Final Core Architecture של Campainer ברמת Principle / Boundary בלבד. הוא נגזר מחוקת Campainer, Product Truth Core, 13 ליבות התחום הפעילות, מסמכי ה־Owner Decisions וה־Promotion, חבילת ה־Professional Knowledge, ה־Cross-Domain Reconciliation, מסמכי ה־Semantic Handoff / Return, מערכת ה־Validation/Evidence ומסמכי ה־Case Validation.


המסמך אינו יוצר Schema, Enum, API, DB model, threshold, score, calibration rule, UX contract, implementation mechanic, Build Authority או Runtime Authority. הוא מגדיר מה כל ליבה מחזיקה, מה אסור לה להחזיק, כיצד משמעות עוברת בין הליבות, כיצד סמכות נפרדת מביצוע, וכיצד ידע, מדידה ולמידה חוזרים למערכת ללא קידום שקט לאמת.


כאשר ניסוח היסטורי על חלוקת אחריות או חיבור בין ליבות סותר מסמך זה, מסמך זה גובר ברמת Principle / Boundary בלבד. המסמך ההיסטורי נשמר כ־Lineage ואינו נמחק.


1. תזה ארכיטקטונית
Campainer אינה מערכת של 13 סוכנים עצמאיים הפועלים בשרשרת. היא מערכת מקצועית אחת שמחזיקה 13 תחומי אחריות קנוניים, כאשר המשתמש חווה Advisor אחד רציף. כל Core מחזיק סוג אחר של משמעות, סמכות או מקצועיות; הוא אינו מחזיק עותק מקביל של אותו State.


הארכיטקטורה חייבת למנוע שלושה כשלים: God Object שמרכז את כל המשמעות בליבה אחת; Shadow Decision שבו ליבה משנה החלטה מחוץ לסמכותה; ו־Semantic Loss שבו מידע עובר בין ליבות באופן שמאלץ את המקבל לנחש.


הכלל המרכזי הוא:
OWNERSHIP OF MEANING IS EXPLICIT.
PROFESSIONAL DISCRETION IS BOUNDED.
AUTHORITY IS SEPARATE FROM CAPABILITY.
EXECUTION IS SEPARATE FROM DECISION.
EVIDENCE IS SEPARATE FROM TRUTH.
LOCAL CONTEXT IS SEPARATE FROM GENERAL KNOWLEDGE.
RESULT IS SEPARATE FROM CAUSAL INTERPRETATION.
LEARNING CANDIDATE IS SEPARATE FROM PROMOTED KNOWLEDGE.


2. שרשרת הגזירה המחייבת
CAMPAINER CONSTITUTION
→ CAMPAINER PRODUCT TRUTH CORE
→ APPLICABLE HORIZONTAL DOMAIN CORES
→ CAMPAINER FINAL CORE ARCHITECTURE
→ CAMPAINER CANONICAL PRODUCT FLOW
→ FLOW CORE APPLICABILITY MATRIX
→ FLOW STAGE CORE / STAGE TRUTH
→ REQUIREMENTS / CONTRACTS / DECISION LOGIC
→ BUILD
→ TEST
→ RUNTIME EVIDENCE.


Final Core Architecture אינה Build specification. היא שכבת החיבור הקנונית שבין Truth/Core לבין Product Flow.


3. מפת הבעלות של 13 הליבות
3.1 Advisor Core
OWNS: judgment מקצועי, synthesis, recommendation, explanation, user relationship, הצגת tradeoffs והובלת המשתמש בתוך המוצר.
DOES NOT OWN: כל הידע במערכת, local truth storage, Director state, measurement semantics, Meta capability, execution orchestration או domain execution.
INPUT PRINCIPLE: מקבל Decision Frame, Context Projection, Knowledge Projection ותוצרי domains רלוונטיים.
OUTPUT PRINCIPLE: recommendation / question / action request / explanation / decision support למשתמש, תוך שמירת uncertainty ו־authority boundary.


3.2 Knowledge / Evidence Core
OWNS: Claims, Evidence, Priors, Patterns, Counterevidence, Contradictions, Unknowns, Scope, Freshness, Maturity/Readiness לשימוש מקצועי ו־Lineage אפיסטמי.
DOES NOT OWN: Local Business Truth, החלטת המשתמש, strategy selection, execution או runtime authority.
INPUT PRINCIPLE: research, evidence, reviewed local evidence, platform evidence, validation results.
OUTPUT PRINCIPLE: Minimum-Sufficient Knowledge Projection לפי Decision Need ו־Scope.


3.3 Complete User Context Core
OWNS: אמת מקומית חיה והיסטורית על המשתמש, Business, Offering, Campaign, Assets, Decisions, Authorizations, verified operational state והקשרים ביניהם.
DOES NOT OWN: universal knowledge, causal interpretation, domain strategy או learning promotion.
INPUT PRINCIPLE: verified user/business facts, authorized changes, readbacks, confirmed state transitions.
OUTPUT PRINCIPLE: Minimum-Sufficient Context Projection scoped to the current decision.


3.4 Director Core
OWNS: bounded Decision Frame של הרגע — מה מנסים להכריע, אילו domains נדרשים, אילו dependencies ו־breakers קיימים, ומהו state של ההכרעה.
DOES NOT OWN: Advisor relationship, domain expertise, execution או permanent user truth.
INPUT PRINCIPLE: Owner/Product context, current Moment, Context Projection, relevant Knowledge/Signals.
OUTPUT PRINCIPLE: Decision Need, required professional contributions, unresolved dependencies and return targets.


3.5 Golden Lead Core
OWNS: multidimensional local meaning of desired/valuable opportunity or lead, including fit, desired work, economic value, serviceability/capacity, realization and confidence where supported.
DOES NOT OWN: one universal score, one global threshold, media-spend decision, causal responsiveness or Meta targeting authority.
BOUNDARY PRINCIPLE: Customer/Opportunity Value ≠ Baseline Outcome Propensity ≠ Incremental Marketing Opportunity ≠ Access/Presence/Retrievability Need.


3.6 Metrics / Measurement Core
OWNS: what is measured, semantic validity of metrics/outcomes, denominators, maturity/censoring, matching/coverage/missingness, attribution versus incrementality, estimands, experiment/causal class, uncertainty and what may or may not be inferred.
DOES NOT OWN: business strategy, learning promotion, platform capability or local economic truth.
BOUNDARY PRINCIPLE: Observation ≠ Explanation; Prediction ≠ Causation; Attribution ≠ Incrementality; Randomization ≠ Precision; Result After Change ≠ Result Caused By Change.


3.7 Learning / Evolution Core
OWNS: Evidence → Candidate → Validation → Scope → Keep/Strengthen/Split/Demote/Reopen/Retire/New Candidate lifecycle, with drift and contradiction preservation.
DOES NOT OWN: self-promotion to canonical truth, silent cross-business transfer, raw measurement semantics or domain authority.
BOUNDARY PRINCIPLE: Learning Candidate ≠ promoted Knowledge; replication elsewhere ≠ local truth.


3.8 Meta Core
OWNS: current platform possibility, capability, hard constraint, permission, asset/integration state, supported read/write surface, live feasibility, preflight and platform readback semantics.
DOES NOT OWN: Strategy choice, business truth, creative judgment, budget allocation or causal value interpretation.
BOUNDARY PRINCIPLE: Capability ≠ Authority; Platform Guidance ≠ Business Truth; API Read ≠ API Write; Technical Success ≠ Marketing Success; Signal Availability ≠ Signal Quality.


3.9 Execution Orchestration Core
OWNS: faithful coordination of an already authorized execution, dependency ordering, execution state, failure/recovery coordination and verified completion/readback.
DOES NOT OWN: deciding what should be done, converting a failed intent into a nearby action, expanding scope or creating new authority.
BOUNDARY PRINCIPLE: Orchestration may adapt mechanics only when semantic equivalence and authorization remain intact; otherwise it must Return.


3.10 Brand / Brand Assets Core
OWNS: authorized Brand Truth, scoped identity, source/master lineage, reusable assets, proof assets, readiness, rights, consent, provenance, restrictions and explicit inheritance relationships.
DOES NOT OWN: marketing strategy, creative representation judgment, campaign performance interpretation or automatic cross-business sharing.
BOUNDARY PRINCIPLE: Brand Knowledge ≠ Strategy ≠ Creative Judgment; Asset Existence ≠ Asset Readiness; Rights ≠ Consent ≠ Provenance; Campaign Winner ≠ Permanent Brand Truth.


3.11 Creative Core
OWNS: Creative Job → Representation → Concept → Execution judgment בתוך strategic, brand, truth, rights, platform and measurement constraints.
DOES NOT OWN: Strategy Family, Brand Truth, universal format rule, Media allocation or platform authority.
BOUNDARY PRINCIPLE: Creative Job ≠ Strategy Family ≠ Format; Proof Requirement ≠ Proof Asset; Attention ≠ Comprehension ≠ Belief ≠ Action ≠ Business Outcome.


3.12 Media / Budget Core
OWNS: professional resource-allocation judgment using marginal opportunity, economics, capacity, sales realization, uncertainty, risk/reversibility and alternative use of resources.
DOES NOT OWN: platform capability truth, business accounting truth, one global KPI threshold or automatic scaling.
BOUNDARY PRINCIPLE: Average Return ≠ Marginal Return; Customer Value ≠ Incremental Media Opportunity; Campaign Economics ≠ Business Economics ≠ Sales Realization.
WORKING FRAME: Next-Shekel may organize the professional decision, but this document does not make it a Runtime object or schema.


3.13 Experience / Interface Core
OWNS: user-facing projection, interaction, navigation, visibility of state, choice, approval, progress, questions, tasks and comprehensible presentation of uncertainty.
DOES NOT OWN: a parallel professional truth layer, hidden strategy, automatic authority, or simplification that changes meaning.
BOUNDARY PRINCIPLE: Experience presents and collects; it does not invent professional truth.


4. Cross-System Semantic Contract
4.1 Semantic Handoff
Semantic Handoff is not “send data to the next module”. It is a transfer of enough meaning for the receiving Core to act professionally without guessing and without receiving unnecessary context.


At Principle/Boundary level, a valid Handoff preserves: identity and Scope; Intent/Meaning; relevant Local Truth; Evidence/Lineage; epistemic status and Unknowns; Confidence/Maturity when material; Freshness; Authority/Permission state; protected constraints; the receiver’s professional discretion boundary; and explicit Return conditions.


This is a conceptual envelope, not an approved field list or schema.


4.2 Minimum-Sufficient Projection
Every receiving Core gets the smallest projection that is sufficient to do its professional job correctly.


Creative does not need the entire CRM. Meta does not need the entire strategy discussion. Metrics does not need authority to choose the strategy. Media does not receive rights to redefine contribution. Experience does not receive private internal reasoning.


Minimum-Sufficient Projection is both a semantic-quality principle and a data-minimization principle.


4.3 Semantic Return
Semantic Return is a valid professional output, not a failure.


A Core must Return when the requested action cannot preserve intent, scope, truth, authority or protected constraints; when required evidence is missing; when current capability invalidates the requested path; when the receiver discovers a materially different problem; or when a proposed fallback would change meaning.


A Return preserves what remains valid, identifies what broke or is missing, names the next decision owner, and prevents silent substitution.


4.4 No Shadow Decision
The receiving Core may exercise professional judgment only inside the discretion explicitly granted to it by the Handoff and its own Core boundary.


It may not silently change strategy, claim scope, budget intent, user authority, brand truth, measurement target, business goal or execution semantics.


If a material semantic change is required, Return is mandatory.


4.5 Semantic Equivalence in Execution
Execution adaptation is permitted only when the adapted technical path is semantically equivalent to the authorized intent and stays within permission, scope and constraints.


Technical feasibility never grants permission to change the business or professional decision.


5. Shared Work Object Semantic Family
The Working cross-system material contains many conceptual objects. Final Core Architecture does not promote them into many universal Runtime entities. The shared architecture is normalized into a small semantic family with domain projections.


5.1 Information / Knowledge Need Family
Conceptually includes Question, Knowledge Gap, Evidence Need, Data/Document Need and targeted User/Business Information Request.


Purpose: represent what must become known before a material decision can improve.


5.2 Professional Work Family
Conceptually includes Recommendation, Decision Candidate, Task/Action Request, Test/Intervention Candidate, Watch/Monitor, Preserve, Wait and Do Nothing.


Purpose: represent bounded professional work without implying authority or execution.


5.3 Authority Family
Conceptually includes User Choice/Decision, Approval and Authorization.


Purpose: make it impossible to infer execution permission from recommendation, discussion, payment, platform capability or mere selection.


5.4 Outcome / Learning Family
Conceptually includes Result/Evidence, What Works, What We Learned, Goal/Progress and Learning Candidate.


Purpose: preserve the difference between observed outcome, measurement interpretation and promoted knowledge.


5.5 Return / Reopen Family
Semantic Return, Reopen and Escalation operate across the shared families whenever meaning, authority, evidence, freshness or capability no longer support the current path.


These families are conceptual contracts only. Exact object IDs, fields, enums, lifecycle states and APIs remain Deferred.


6. Authority-State Conceptual Contract
The governing authority chain is:
DISCUSSION / PROFESSIONAL RECOMMENDATION
→ USER CHOICE / DECISION
→ APPROVAL, when required
→ AUTHORIZATION
→ EXECUTION
→ VERIFIED READBACK.


Not every low-risk interaction must instantiate every stage as a product object, but whenever a stage is material it must remain semantically distinct.


Recommendation ≠ Permission.
Choice ≠ Approval.
Approval ≠ Authorization.
Authorization ≠ Execution.
Payment ≠ Meta write authority.
Platform capability ≠ execution authority.
Conversation ≠ execution authority.
Execution attempt ≠ verified state change.


7. Knowledge Runtime Architecture — Principle / Boundary
7.1 Activation
Knowledge is activated because a specific Decision Need exists. Activation is not adoption.


Knowledge / Evidence owns the semantics of relevance, scope, freshness and epistemic readiness. Director supplies the current Decision Need. Context supplies local state. The receiving professional Core owns domain judgment.


Exact runtime ownership of the future activation service remains Deferred.


7.2 Retrieval and Projection
The runtime knowledge path is:
DECISION NEED
→ CONTEXT PROJECTION
→ KNOWLEDGE NEED
→ ACTIVATION
→ RETRIEVAL / SELECTION
→ MINIMUM-SUFFICIENT KNOWLEDGE PROJECTION
→ PROFESSIONAL USE.


A large undifferentiated prompt containing the entire corpus is not the target architecture.


7.3 Usage Trace
Material professional use of knowledge must be traceable enough to reconstruct which Knowledge/Evidence/Unknown was active, in what Scope/Freshness/Status, for which Decision, and what result later returned.


Usage Trace must not require storage or exposure of private chain-of-thought. Traceability concerns governed inputs, decisions, cited evidence, outputs, interventions and state transitions — not hidden reasoning tokens.


7.4 Learning Return
The learning path is:
RESULT
→ METRICS / MEASUREMENT INTERPRETATION
→ LEARNING CANDIDATE
→ VALIDATION / SCOPE / CONTRADICTION REVIEW
→ KEEP / STRENGTHEN / SPLIT / DEMOTE / REOPEN / RETIRE / NEW CANDIDATE
→ governed CONTEXT UPDATE and/or KNOWLEDGE UPDATE according to ownership.


There is no valid shortcut:
RESULT → “SYSTEM LEARNED” → TRUTH.


8. Core Decision Chain
The normalized cross-domain decision chain is:


BUSINESS / OFFERING / OWNER GOAL
→ BUYER / ACCOUNT / BUYING SITUATION / JOURNEY
→ EXTERNAL + LOCAL SIGNALS WITH SCOPE / FRESHNESS
→ MARKETING PROBLEM / BOTTLENECK / OPPORTUNITY HYPOTHESIS
→ CUSTOMER / OPPORTUNITY VALUE + SERVICEABILITY / CAPACITY
→ ACCESS / PRESENCE / RETRIEVABILITY / CONSIDERATION NEED
→ BASELINE OUTCOME PROPENSITY, only where decision-relevant
→ CANDIDATE STRATEGIES / PRESERVE / WAIT / DO NOTHING
→ STRATEGIC JOB / STATE CHANGE / MUST-BELIEVE / PROOF REQUIREMENT
→ CREATIVE JOB / REPRESENTATION / ASSET / ROUTE CANDIDATES
→ META CURRENT POSSIBILITY / CONSTRAINT / ENABLEMENT STATE
→ MEDIA ALLOCATION JUDGMENT USING INCREMENTAL OPPORTUNITY + ECONOMICS + CAPACITY + UNCERTAINTY
→ USER CHOICE / APPROVAL / AUTHORIZATION AS REQUIRED
→ EXECUTION WITH CLOSED INTENT / CONTRACT / AUTHORITY
→ VERIFIED READBACK
→ SALES TREATMENT + BUSINESS PROCESS STATE
→ MATURED DOWNSTREAM OUTCOME
→ CONTRIBUTION / COLLECTION / FULFILLMENT / DESIRED WORK
→ MEASUREMENT / CAUSAL INTERPRETATION
→ LEARNING CANDIDATE AND GOVERNED RETURN.


This chain is not a rigid conveyor. Any step may Return to the appropriate owner when the meaning cannot be preserved.


9. Cross-Core Boundary Resolutions
9.1 Knowledge vs Context
Knowledge holds scoped professional knowledge and epistemic state. Context holds current and historical local truth. A local fact may become Evidence for Knowledge, but it is not automatically generalized.


9.2 Context vs Metrics
Context stores what happened and current verified state. Metrics owns what a measurement means, whether outcomes are mature/covered/matched and what may be inferred.


9.3 Metrics vs Learning
Metrics interprets evidence and causal class. Learning manages candidate lifecycle, replication, drift, demotion and reopening.


9.4 Director vs Advisor
Director holds the bounded Decision Frame. Advisor holds professional synthesis and the relationship with the user. Director does not become a second Advisor; Advisor does not become the global orchestration state store.


9.5 Golden Lead vs Media
Golden Lead describes local desirability/value/fit/serviceability dimensions. Media decides marginal resource allocation. High Golden value does not imply high incremental response or automatic spend.


9.6 Media vs Meta
Media decides what the next allocation should be; Meta states what can be executed now and under which constraints. Meta recommendation is an input, not allocation authority.


9.7 Meta vs Orchestration
Meta owns current technical capability and object state. Orchestration coordinates execution of authorized intent. Orchestration cannot invent a “closest valid” action when exact meaning is lost.


9.8 Brand vs Creative
Brand owns authorized truth, protected identity and asset readiness. Creative owns representation/execution within those constraints. Creative output may propose a Brand change but cannot promote it.


9.9 Experience vs Professional Cores
Experience may summarize, stage and display. It cannot create a parallel truth or hide a material Unknown, tradeoff or authority requirement.


9.10 Signal Readiness
At Principle/Boundary level:
Technical/Meta owns observability, transport, matching health and current ingestibility/capability.
Metrics/Measurement owns semantic, business and causal readiness.
Neither alone can declare a signal fit for optimization or learning.


10. Four-Way Opportunity Separation
Final Core Architecture keeps four decision variables separate:


CUSTOMER / OPPORTUNITY VALUE
How desirable or valuable the opportunity is to the local business.


BASELINE OUTCOME PROPENSITY
Expected probability of a specified outcome without the specified intervention, scoped by outcome and horizon.


INCREMENTAL MARKETING OPPORTUNITY
Expected causal change/value from a specified marketing intervention under current state, intervention, outcome and horizon.


ACCESS / PRESENCE / RETRIEVABILITY NEED
Whether a relevant buyer must be able to discover, retrieve, remember or consider the provider.


No one score may silently collapse these dimensions. Low incremental response to one intervention does not imply low customer value or a requirement to make the buyer unreachable.


11. Preserve / Wait / Do Nothing
PRESERVE, WAIT and DO NOTHING are valid cross-domain action states when supported by evidence, scope and reopen conditions.


They are not universal performance rules and do not imply permanent inactivity. Their legitimacy depends on current evidence, risk of change, opportunity cost, outcome maturity and the next recheck trigger.


12. External Signals and Industry Boundary
External Signals provide sourced observations, market intelligence, freshness and hypotheses. They do not become Local Truth automatically and do not create person-level intent from aggregate/public data.


Industry supplies scoped priors, terminology, mechanism hypotheses, regulation/seasonality warnings and candidate failure modes. Industry ≠ Offering ≠ Strategy. No industry benchmark, threshold, seasonality or causal effect becomes local truth without validation.


13. Professional Knowledge and Canonical Truth
Professional Knowledge may be Working, Supported, Triangulated or Decision-Support Ready without being Canonical Core Truth.


External research, case evidence, Hillstrom/raw analysis, expert returns and domain reconciliations may strengthen or weaken knowledge. Promotion to Product/Core truth still requires governed authority.


No source, dataset, case, vendor guidance or cross-business pattern gets silent promotion because it is high-quality or statistically strong.


14. Evidence / Case Lineage Protection
Structural case validation proves representational adequacy and gap visibility; it does not prove universal performance.


Current identifier lineage is:
CV-006 = B2B multi-actor structural case.
CV-007 = future empirical Won/Lost / downstream realization case.
Any earlier working reference that reused CV-006 for the empirical case is superseded on identifier meaning only; historical documents remain intact.


Local empirical calibration remains open by design.


15. Cross-System Invariants
INVARIANT A — Scope travels with meaning.
INVARIANT B — Unknown remains Unknown until evidence or authority closes it.
INVARIANT C — No Core may silently assume another Core’s authority.
INVARIANT D — No capability claim becomes strategy or business truth.
INVARIANT E — No result becomes causal truth without Measurement semantics.
INVARIANT F — No learning candidate self-promotes.
INVARIANT G — No cross-business truth/assets/thresholds transfer automatically.
INVARIANT H — No execution occurs from recommendation alone.
INVARIANT I — Every material execution has authority and verified readback.
INVARIANT J — Every semantic fallback must preserve equivalence or Return.
INVARIANT K — Minimum-Sufficient Projection is preferred over whole-corpus propagation.
INVARIANT L — Traceability must preserve evidence/decision lineage without requiring private chain-of-thought.
INVARIANT M — User experience remains one coherent Advisor relationship even though multiple Cores contribute behind it.


16. Deferred — intentionally not decided here
The following remain outside this document’s authority:
exact Runtime object set;
schemas and field lists;
enums and status codes;
API contracts;
database layout;
event bus/topic design;
activation service implementation;
permission/risk tiers;
thresholds, weights and scores;
numeric calibration;
exact user-flow screens;
exact UI interaction mechanics;
contract versioning mechanics;
data retention/deletion implementation;
privacy/legal implementation details;
vendor/provider selection;
automatic action limits;
exact Meta live capabilities at implementation time;
exact experiment designs and sample rules;
exact CV-007 dataset contract;
Build sequencing and code structure.


These are not omissions. They are deliberately deferred to the proper later layer.


17. Relationship to Canonical Product Flow
The next canonical artifact is CAMPAINER CANONICAL PRODUCT FLOW.


The Product Flow must derive from this architecture rather than invent new ownership. Every Flow stage must identify applicable Cores, Decision Need, Context/Knowledge projections, authority requirements, Handoff/Return paths, execution/readback conditions and learning return.


Product Flow may define sequence and stage boundaries. It may not move domain ownership or create shadow authority without an explicit Owner-approved Core change.


18. Acceptance gates for Canonical Product Flow
A proposed Product Flow is acceptable only if:
the user still experiences one coherent Advisor relationship;
every material decision has an identifiable owner;
applicable Cores are explicit by stage;
Context and Knowledge arrive through minimum-sufficient projections;
no stage depends on a hidden global score;
recommendation, approval, authorization and execution remain distinct;
Semantic Return exists wherever meaning can fail;
execution has preflight, authority and verified readback where applicable;
sales/business realization is not collapsed into lead potential;
measurement distinguishes proxy, attribution and incrementality;
learning returns through a candidate lifecycle rather than self-promotion;
cross-business transfer remains governed;
platform/current capability is rechecked at the correct freshness boundary;
Unknown is visible rather than guessed.


19. Canonical approval statement
The Product Owner approved the Final Core Architecture normalization represented by this document at Principle / Boundary level.


Accordingly:
13/13 Domain Cores remain ACTIVE DOMAIN TRUTH.
The cross-core ownership map in this document is the governing Final Core Architecture.
Semantic Handoff, Minimum-Sufficient Projection, Semantic Return, No Shadow Decision and Authority-State separation are approved architecture principles.
The small Shared Work Object semantic family is approved as a conceptual normalization, not as a Runtime schema.
Knowledge Runtime Activation / Projection / Usage Trace / Learning Return are approved as architecture principles, with exact implementation deferred.
The Four-Way Opportunity separation is preserved in the architecture.
No Build Authority, Runtime Authority, Schema Authority or Meta Write Authority is created.


20. Source and lineage anchors
Governing package home:
CAMPAINER-PRODUCT-TRUTH-AND-CORE-ARCHITECTURE-PACKAGE-001 — ID 1vmronvhIbM1PbDWKp2EsNpqWSfEyE9ALDPWPLokTZYI.


Canonical roots:
CAMPAINER-CONSTITUTION-001 — ID 1z5x9sfqWySRpAhyg-erupFwNUB8ghimQLLURB_8GvJQ.
CAMPAINER-PRODUCT-TRUTH-CORE-001 v1.2 — ID 1EK-NTEjpDTM8x6NG_C-6MmcBhdyzmm-Qnub5cSEM5yI.
CAMPAINER-ADVISOR-CORE-001 v1.1 — ID 1KAwg8fHnINs9TgRCqFbBtml6YNP2Bj9kchTx5MnWpLs.


Active domain-core anchors:
Knowledge / Evidence — 1w2aDTqHDkxH-YOBlBuQUHHW0yVHTm46UuiChFznTaSg.
Complete User Context — 1LYKSj2RKrfOVEW7DwGwE_WuV_f5MzwJ2xhaHMqJCybg.
Director — 1ZweOD8cWSJqI0_Pg-sOoWvA1fA-OUuZeomxrr_xsP20.
Execution Orchestration — 19UA98mXcNZdJ_lU1QbWoJTvhNZoilqVRYkrqU56pxc4.
Golden Lead — 1CRZ710LHyLp9BBlXx95MdNKeHLaW_gZrnx_tYT44DRM.
Metrics / Measurement — 1jJMmZJbRwCM7usOf_zrrd-gqT6L6aka2TuE220tPNm0.
Learning / Evolution — 1kvqsgC36H-YcaK8WSjRR7M8OXqOGRmV6KyckaYBWS-Q.
Brand / Brand Assets — 1bS2hgYrTj0nSasx6gQYoGkmIuv1JGy7VqNw1DTweLhw.
Creative — 1wHBWMsJPlBlXlHudkqG1ptgcwgp7rh_sdfJAKJ6HzN8.
Media / Budget — 12ae1Ev0RcDNG2sPmAssyYsWhXOeXy0LER591BKeqdHw.
Meta — 1NL9eDfvh3Va0xJL0FYDrPESsDbNjkgTejc76ZQXb9kw.
Experience / Interface — 1lGjOB641Gdv3ao4cSKUoV0-tr5nl4YXS2g-qeNv6WWg.


Research / reconciliation anchors:
PROFESSIONAL-KNOWLEDGE-CROSS-DOMAIN-RECONCILIATION-001 — ID 1sxJiLoZFCBLZifE1eryrA3fuxGvLrZn9LBnSAHRu8I4.
VALIDATION-AND-EVIDENCE-SYSTEM-001 — ID 15DElDtqBaniuqB35bOLNGxCS2GBg0wqziqq1pVQZZII.
EVIDENCE-REGISTER-001 v0.2 — ID 1xZswEJbrhEv4zt2iCtmWl53IH7-1_qVCmITw-29o03g.
CASE-VALIDATION-WAVE-001 v0.5 — ID 1rrr30szbeKTgiGBav8D0ytzHAV2D5dD2_E_62pnymhI.
HILLSTROM-INDEPENDENT-RAW-ANALYSIS-001 — RESULT PACKET — ID 1ChQ8wH0D9BIMbVtqcebGzfLiyj3vMSvUoBJIoLbCkys.


21. Next derivation
NEXT ARTIFACT:
CAMPAINER-CANONICAL-PRODUCT-FLOW-001.


That artifact must derive the end-to-end user/product flow from this Final Core Architecture while preserving all ownership, authority, Semantic Handoff/Return, measurement and learning boundaries above.


22. OWNER-APPROVED SHARED EXPERIENCE ARCHITECTURE — ADDITIVE
המסמך CAMPAINER-SHARED-EXPERIENCE-AND-ADVISOR-WORKSPACE-ARCHITECTURE-001, ID 1VDtgvqECgPvY2jj2huUD5gAMgF7f6o0PPf7neWuGt6U, הוא מקור קנוני תוספתי פעיל.
אין שינוי במספר 13 הליבות או בבעלותן. Experience / Interface מחזיקה את מעטפת היישום, התצוגה והאינטראקציה; Advisor מחזיק זהות מקצועית רציפה, explanation ו-recommendation; Context ו-Director מספקים projections ו-Decision Frame לפי העקרונות הקיימים.
המעטפת כוללת ניווט מוצר ימני פתוח/מצומצם/מוסתר, פאנל Advisor שמאלי פתוח/מצומצם/משנה-רוחב/סגור, משטח עבודה מרכזי אדפטיבי, Universal Advisor Entry, Contextual Expand-in-Place ו-Dedicated Advisor Workspace בקירוב 1/3–2/3.
שפת העיצוב יכולה להיות משותפת ל-Leader ברמת Design Contracts וטוקנים, אך כל מוצר שומר Truth, Permission, Decision, Action, Runtime ו-Learning ownership מקומי וללא תלות Runtime הכרחית.


END — CAMPAINER-FINAL-CORE-ARCHITECTURE-001 — v1.0
