---
mirror_role: "Base44 read/reference mirror"
canonical_source: "Google Drive"
source_title: "CAMPAINER-BUILD-PACKAGES-MASTER-001 — v1.0"
source_drive_id: "1wn1I5_zPg4MRC88ePLIehThIgGJMwA42BfwRQFzRjoQ"
source_modified_at: "2026-08-18T18:05:17.605Z"
corpus_status: "current-v1.0"
category: "build"
---

> MIRROR NOTICE: This file is a controlled copy for Base44. Google Drive remains the canonical source. Do not infer implementation, deployment, runtime, or release authority from repository presence.

## Canonical source body

CAMPAINER-BUILD-PACKAGES-MASTER-001 — v1.0
Build Package Derivation Master
STATUS: OWNER-APPROVED BUILD PACKAGE DECOMPOSITION / DERIVATION METHOD
ACTIVE CANONICAL TRUTH: NO — BUILD DERIVATION AUTHORITY ONLY
BUILD AUTHORITY: NO
RUNTIME AUTHORITY: NO
META WRITE / LAUNCH AUTHORITY: NO
PRODUCT OWNER AUTHORITY: PRESERVED


DERIVATION CHAIN
Constitution / Product Truth
→ 13 Domain Cores
→ Final Core Architecture
→ Canonical Product Flow
→ Flow Core Applicability Matrix
→ Stage Truth Master + 21 Stage Truth artifacts
→ Decision & Handoff Contracts Master + 16 canonical contracts
→ THIS BUILD PACKAGE DERIVATION
→ future approved Build Package requirements
→ code/build only after explicit Build Authority.


0. Purpose
This document defines how the approved Campainer truth architecture should be divided into buildable vertical slices. It does not authorize coding and does not choose final schemas, APIs, model vendors, UI screens or infrastructure. Its job is to make the next layer build-ready without losing traceability.


Roadmap alignment: this is WAVE F / Phase 5 — Build Packages. The roadmap requires packages for UI, data, APIs, prompts/models, permissions, orchestration, tests and acceptance criteria. The historical Phase 5 dates remain baseline history and are not rewritten by this document.


1. Build Package doctrine
A Build Package is not a Core, not a Stage and not a screen. It is a bounded implementation slice that may combine multiple Stages and Cores when they share the same runtime capability.


Each Build Package must preserve:
- Stage purpose and consumer;
- Stage/contract coverage;
- inputs / outputs / dependencies;
- Minimum-Sufficient Context Projection;
- Knowledge needs and activation/retrieval rules;
- candidate/decision logic;
- user interaction requirements;
- authority / consent gates;
- execution/orchestration contract where applicable;
- evidence writes and readback;
- metrics and measurement semantics;
- failure / recovery / rollback;
- Semantic Return / Reopen;
- UI / API / data requirements;
- prompt/model responsibilities and prohibited decisions;
- tests and acceptance criteria;
- Human Review requirements for pilot;
- traceability to approved Truth/Core/Flow/Stage/Contract.


No package may infer a final DB/API schema merely from conceptual contracts. Exact schemas are outputs of package-level requirements work and require their own review before build.


2. Proposed build-slice map
The proposed decomposition is 13 Build Packages. The number 13 is coincidental and has no one-to-one relationship with the 13 Domain Cores.


BP-00 — SHARED SEMANTIC RUNTIME & GOVERNANCE FOUNDATION
Scope: shared substrate required by both Business/Ongoing and One-Time paths.
Covers: cross-stage invariants; Contract C16 Semantic Return; shared authority/evidence concepts; multi-business scope isolation.
Must derive requirements for:
- User / Business / Offering / Campaign / One-Time scope identity and isolation;
- local Context truth references and projections without copying whole Context;
- small Shared Work Object semantic family: Question/Gap, Recommendation/Task/Test/Wait/Preserve/Do Nothing, Choice/Approval/Authorization, Result/What Works/What Learned/Goal/Progress/Learning Candidate;
- explicit Authority state separation;
- evidence / decision / intervention / readback lineage;
- version/reference semantics required by later packages;
- Human Review routing and reviewer evidence;
- Semantic Return / Reopen routing;
- Unknown/Freshness/Scope preservation;
- auditability without private chain-of-thought storage.
Primary acceptance: no vertical package must invent its own parallel authority, Context truth or evidence-lineage system.


BP-01 — KNOWLEDGE + CONTEXT PROJECTION + DIRECTOR/ADVISOR DECISION RUNTIME
Scope: the professional runtime that turns Moment/Decision Need into minimum-sufficient Context and Knowledge and supports Advisor judgment.
Covers: A1/A2/A4/A5/A10/A11 and B1/B2/B7/B9 capabilities reused across flows; Knowledge Runtime principles.
Must derive requirements for:
- Decision Need creation and bounded Director frame;
- Context Projection request/result;
- Knowledge Need and activation;
- retrieval by domain/scope/status/freshness;
- Knowledge Projection containing relevant claims/priors/counterevidence/contradictions/Unknowns;
- usage trace: what governed knowledge/evidence was active for a material decision;
- Advisor professional response object families without storing hidden reasoning;
- ASK/COLLECT only when decision-relevant;
- local correction and contradiction handling;
- role-specific projections;
- safe failure when Knowledge is unavailable/stale.
Primary acceptance: whole-corpus dumping is not the default architecture and Prior never becomes Local Truth silently.


BP-02 — ENTRY & BRANCH ROUTING
Stage coverage: ENTRY.
Contract coverage: C01.
Purpose: expose two clear entries at the point where Short Diagnosis begins: Business/Ongoing and “אני רוצה לפרסם משהו חד־פעמי”.
Must derive requirements for:
- one continuous Advisor identity;
- direct One-Time button/choice;
- no forced general route-selection screen;
- no hidden classifier that overrides user branch choice;
- known user/business scope projection when useful;
- explicit branch state and Return to user choice if mismatch emerges.
Primary acceptance: One-Time entry works without starting Short Diagnosis and no branch creates execution authority.


BP-03 — BUSINESS/ONGOING PRE-PAYMENT JOURNEY
Stage coverage: A1, A2, A3.
Contract coverage: C02, C03, C04.
Purpose: Short Diagnosis → Strategy Initial + three insights + Route Recommendation → Choice/Scope/Payment.
Must derive requirements for:
- adaptive Short Diagnosis and stop condition at Minimum Sufficient Initial Understanding;
- Strategy Initial composition and presentation;
- Route Recommendation as final conclusion of Strategy Initial, never a separate Stage;
- real professional value before payment;
- local claim/correction/Unknown capture;
- service-scope presentation and commercial integration;
- Campainer service price separated from Media Budget and other approved cost layers;
- payment/entitlement state;
- explicit rule Payment ≠ Strategy Approval ≠ Creative Approval ≠ Authorization ≠ Launch.
Primary acceptance: a user can reach paid entitlement while preserving all professional and authority boundaries.


BP-04 — BUSINESS/ONGOING DEEP UNDERSTANDING & FULL STRATEGY
Stage coverage: A4, A5.
Contract coverage: C05.
Purpose: progressive deep diagnosis + Baseline → Full Strategy.
Must derive requirements for:
- progressive questions driven by Decision Need, not fixed questionnaire count;
- representation of Business/Offering/Customer/Account/Buyer State/Buying Situation/Journey/Economics/Capacity/Sales Handling/Brand/Proof/constraints as optional scoped truth, not universal mandatory fields;
- scoped Baseline and concurrent-change capture;
- measurement readiness during diagnosis;
- Problem/Bottleneck before material Strategy;
- candidate mechanism/strategy comparison with evidence for/against and Unknowns;
- Strategy recommendation, Strategic Job, Must-Believe, Proof Requirement, Offer/Route and Measurement Intent;
- user correction / choice / Strategy approval where applicable;
- Return to understanding when evidence is insufficient.
Primary acceptance: Full Strategy can be reconstructed from governed Context/Knowledge/Evidence without platform convenience choosing the strategy.


BP-05 — ONE-TIME INTAKE / BRIEF / COMMERCIAL JOURNEY
Stage coverage: B1, B2, B3.
Contract coverage: C03, C04 and One-Time inputs to C07.
Purpose: campaign-specific intake → One-Time Brief/Recommendation → Scope/Price/Payment.
Must derive requirements for:
- direct campaign-specific questions: what, why, audience/area, time/window, budget, offer/CTA/destination, assets, constraints, End Condition;
- no Short Business Diagnosis, Strategy Initial or Full Strategy requirement;
- Minimum Sufficient Campaign Understanding;
- optional asset upload;
- One-Time recommendation capable of multiple managed phases while remaining one-time;
- price/service scope separate from Media Budget;
- paid entitlement before paid Studio/production work;
- explicit End Condition state carried downstream.
Primary acceptance: a user can buy a professionally defined one-time advertising service without being forced into the ongoing business flow.


BP-06 — SHARED STUDIO: BRAND ASSETS ROOM + CREATIVE ROOM
Stage coverage: A6, B4.
Contract coverage: C06, C07.
Purpose: one Studio product place with two professionally separate rooms.
Must derive requirements for Brand Assets room:
- Business/Brand scope isolation;
- asset upload/import/source/master/version relationships;
- rights/consent/provenance/restrictions/readiness;
- Proof Assets and protected Brand Truth;
- Minimum-Sufficient Brand Snapshot;
- missing-asset alternatives and tasks.
Must derive requirements for Creative room:
- receive Strategic Intent or One-Time Brief through semantic handoff;
- Creative Job → Representation → Concept → Execution;
- meaningful variants only when professionally justified;
- provider/production/AI interfaces without transferring creative judgment;
- no silent alteration of Strategy, Brand Truth or protected claims;
- Creative → Brand/Advisor Semantic Return.
Primary acceptance: the UI feels like one Studio while data/authority prove Brand Core ≠ Creative Core.


BP-07 — CAMPAIGN READINESS & USER REVIEW
Stage coverage: A7, A8, B5 and equivalent One-Time readiness before B5.
Contract coverage: C08, inputs to C09.
Purpose: combine Strategy/Brief + Studio + Media/Budget + Meta + Measurement + Business Realization readiness, then present the exact proposal to the user.
Must derive requirements for:
- campaign package/version identity;
- Media/Budget allocation recommendation using marginal opportunity/economics/capacity/uncertainty, not average KPI alone;
- current Meta capability/permissions/state projection without granting authority;
- measurement intent, baseline and readback readiness;
- lead/business-realization readiness where relevant;
- No False Dead End states: Start Now / Start+Parallel / Responsible Alternative / Wait / Preserve / genuine Stop;
- exact user-review package: what will run, audience meaning, offer/CTA/destination, budget envelope, time/window, creative/assets, assumptions/risks/Unknowns, measurement intent;
- approval versioning/corrections;
- Approval ≠ Authorization.
Primary acceptance: an approved package is precise enough that an executor will not need to invent professional meaning.


BP-08 — AUTHORIZATION / META EXECUTION / VERIFIED READBACK
Stage coverage: A9, B6 and material live changes from A10/B7.
Contract coverage: C09, C10, C11, C16.
Purpose: convert an approved professional intent into a live verified state without Shadow Decision.
Must derive requirements for:
- explicit scoped Authorization UX/state;
- target identity, scope and spend authority;
- Fresh Preflight close to action;
- permission/capability/asset/destination/dependency checks;
- closed semantic action contract;
- Meta/provider adapters;
- controlled execution and idempotency/retry requirements to be defined at package level;
- provider receipt separated from verified state;
- readback and discrepancy handling;
- partial success, failure, recovery, rollback and Semantic Return;
- verified operational state write to Context;
- 100% Human Review for material pilot writes.
Primary acceptance: no live action can be traced only to payment/approval/capability; every material write has explicit authority and result-state evidence.


BP-09 — MANAGED MARKETING / MEDIA / LEAD & BUSINESS REALIZATION
Stage coverage: A10, B7.
Contract coverage: C12 and live-use of C10/C11.
Purpose: manage the active marketing system and one-time managed runs beyond Ads Manager metrics.
Must derive requirements for:
- recurring/current Decision Moments;
- media allocation: add/hold/reduce/reallocate/test/wait/preserve;
- spend pacing and remaining budget/time;
- creative refresh/return to Studio;
- Meta live-state issues;
- lead potential/quality evidence;
- response/contact/qualification/meeting/quote/opportunity/won/lost states where available;
- sales treatment/interventions as treatment/process state, not lead property;
- economics, capacity, contribution/collection/fulfillment where relevant;
- user/business Tasks and Interventions with before/after lineage;
- Advisor recommendations including Wait/Preserve/Do Nothing;
- material change approval/authorization loop.
Primary acceptance: Potential Lead Quality ≠ Business Realization Capability ≠ Realized Outcome remains observable in data and decision logic.


BP-10 — MEASUREMENT / LEARNING / NEXT DECISION
Stage coverage: A11, B9.
Contract coverage: C13, C15.
Purpose: turn evidence into valid interpretation, scoped learning and the next decision.
Must derive requirements for:
- Raw Data / Metric / Outcome / Proxy / Estimand distinctions as needed;
- missing/pending/censored states;
- Attribution vs Incrementality;
- treatment/exposure/change lineage;
- deepest reliable outcome appropriate to the decision;
- Measurement Interpretation object/result semantics;
- Learning Candidate lifecycle and disposition;
- local Context update vs general Knowledge candidate separation;
- What Works / What Learned / Goal & Progress user presentation;
- targeted Reopen routing rather than generic back navigation;
- late outcome/correction reopen.
Primary acceptance: Result cannot become broad truth or causal claim without the proper measurement/learning path.


BP-11 — ONE-TIME END CONDITION & CLOSURE
Stage coverage: B8.
Contract coverage: C14, C11 and C13 handoff after closure.
Purpose: ensure every One-Time campaign ends deliberately and verifiably.
Must derive requirements for:
- End Condition types at the conceptual level: date/time, event/offer end, spend limit, inventory/capacity, sold/rented/closed objective, user stop, responsible stop or other scoped condition;
- no autonomous scope extension;
- approaching-end state and user communication where useful;
- closure authority interpretation from approved End Condition vs discretionary closure;
- stop/close execution through EO/Meta;
- verified final live state;
- final spend/obligations/assets/lineage package;
- transfer to Measurement/Summary;
- closure failure/recovery.
Primary acceptance: no one-time campaign stays live merely because nobody remembered to stop it.


BP-12 — PILOT CONTROL PLANE / OBSERVABILITY / PRIVACY / SECURITY / QA OVERLAY
Scope: cross-cutting package applied to every pilot build slice; does not replace package-local tests.
Must derive requirements for:
- 100% Human Review workflow for material pilot professional/execution decisions;
- reviewer identity/state and evidence;
- audit/event/trace observability sufficient to reconstruct governed inputs, decisions, authority, execution and result without private chain-of-thought;
- multi-business isolation tests;
- permissions and least-privilege expectations;
- sensitive data handling, retention/deletion hooks and privacy/legal gates to the extent required for pilot;
- error, timeout, retry, partial-state and rollback observability;
- Meta read-only/live-state validation gates;
- QA golden cases for both branches;
- edge-case and Semantic Return coverage;
- feature/config gating required to prevent unreviewed material actions.
Primary acceptance: the Controlled Pilot can be audited, stopped, corrected and reviewed even when individual components fail.


3. Dependency graph
Foundation:
BP-00 → BP-01.


Entry and pre-production:
BP-00/BP-01 → BP-02.
BP-02/BP-01 → BP-03 and BP-05.
BP-03 → BP-04.
BP-04 + BP-05 → shared BP-06 as their respective inputs mature.


Campaign build/run:
BP-04/BP-06 → BP-07 for Business/Ongoing.
BP-05/BP-06 → BP-07 for One-Time.
BP-07 → BP-08.
BP-08 → BP-09.
BP-09 → BP-10.
BP-09 → BP-11 for One-Time when End Condition matures.
BP-11 → BP-10 for final One-Time measurement/summary.


BP-12 overlays all packages and must be included before any package receives Pilot Build Authority.


4. Package-level required deliverables
When an individual BP is drafted for build readiness it must include at minimum:
1. canonical sources and exact Stage/Contract IDs;
2. product purpose and user journey moment;
3. functional requirements;
4. non-functional/safety/governance requirements;
5. conceptual data objects and relationships to be implemented;
6. proposed concrete schemas with explicit status: DRAFT until separately approved;
7. API/integration requirements;
8. prompt/model responsibilities, tool permissions and prohibited judgments;
9. UI/workbench requirements and user-visible states;
10. authority/consent/review gates;
11. Context/Knowledge projection interfaces;
12. evidence/event/readback requirements;
13. metrics/measurement requirements;
14. failure/recovery/rollback/Semantic Return paths;
15. security/privacy/multi-business isolation requirements;
16. unit/integration/E2E/golden-case tests;
17. acceptance criteria;
18. migration/backward-compatibility impacts if any;
19. deferred/open decisions that block or do not block build;
20. traceability matrix Truth → Core → Flow/Stage → Contract → Requirement → Test.


5. Build Authority rule
Approval of this Master would approve only the package decomposition and derivation method. It would NOT authorize coding.


Each individual Build Package must be produced and reviewed. Build Authority may then be granted explicitly per package or per governed release wave. No package gets authority from folder placement, document existence or roadmap dates.


6. Pilot build sequencing proposal
After package requirements are approved, a safe implementation sequence is:
F0 — BP-00 + BP-01 shared foundations.
F1 — BP-02 + BP-03 + BP-05 entry/pre-payment paths.
F2 — BP-04 + BP-06 deep strategy and shared Studio.
F3 — BP-07 readiness/review.
F4 — BP-08 authorization/execution/readback.
F5 — BP-09 managed operations + BP-11 One-Time closure.
F6 — BP-10 measurement/learning/next decision.
BP-12 overlays F0–F6 and strengthens progressively.


This is a dependency proposal, not a calendar commitment and not Build Authority.


7. Roadmap relationship
Roadmap Phase 5 defined Build Packages as 45–60 hours and Phase 6 as Pilot-Path Build. This Master preserves that distinction: requirements/package derivation precedes coding.


The baseline management target for first real Controlled Pilot remains roadmap history unless a later plan-vs-actual review changes the forecast with an explicit reason. This document does not change the pilot date.


8. Acceptance gates for Build Package Master
The Master may be approved only if:
- every canonical Stage is covered by at least one build slice;
- both Entry branches are covered;
- all 16 material contracts have an implementation owner/package;
- no package creates a new Core or transfers Core ownership;
- Context/Knowledge/Authority/Evidence are shared governed capabilities rather than duplicated per screen;
- Studio remains one product place with two professional rooms;
- Payment remains outside live-action authority;
- Meta capability remains separate from Strategy/Media/Authority;
- business realization remains distinct from lead potential;
- One-Time End Condition/Closure is built explicitly;
- Measurement precedes Learning promotion semantics;
- Human Review, multi-business isolation, observability and Semantic Return are cross-cutting;
- package approval alone does not create Build Authority.


9. Open decisions intentionally deferred to individual Build Packages
- exact screen map/navigation and component structure;
- final DB entities/columns/indexes;
- final API payloads and versioning;
- exact Shared Work Object schemas/enums;
- exact Knowledge Item/Activation implementation;
- model/provider choice and prompt structure;
- billing provider/API and final pricing formulas;
- Meta object/API details at implementation-time freshness;
- risk tiers and low-risk automation classes;
- exact authorization UX and future bundled-authority mechanics;
- retry/idempotency/timeouts/rollback implementation;
- privacy retention periods and legal implementation details;
- exact metrics/experiment designs and calibration thresholds;
- CV-007 data contract;
- production scalability beyond controlled pilot needs.


10. Current status / next decision
CURRENT STATUS: OWNER-APPROVED BUILD PACKAGE DECOMPOSITION / DERIVATION METHOD.


OWNER DECISION: APPROVED. Create BP-00 through BP-12 requirement packages as Owner-Review drafts. Coding remains blocked until explicit Build Authority is later granted.


END — CAMPAINER-BUILD-PACKAGES-MASTER-001 — v1.0
