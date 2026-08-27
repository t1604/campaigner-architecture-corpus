---
mirror_role: "Base44 read/reference mirror"
canonical_source: "Google Drive"
source_title: "CAMPAINER-STAGE-TRUTH-MASTER-001 — v1.0 — Stage Truth Master"
source_drive_id: "10yjML4WKR1OOVLdfpNgoVyODPbEEzhef9tP13rwOkSI"
source_modified_at: "2026-08-18T17:32:12.919Z"
corpus_status: "current-v1.0"
category: "stage-truth"
---

> MIRROR NOTICE: This file is a controlled copy for Base44. Google Drive remains the canonical source. Do not infer implementation, deployment, runtime, or release authority from repository presence.

## Canonical source body

CAMPAINER-STAGE-TRUTH-MASTER-001 — v1.0
Stage Truth Master — אמת התחנות של ה־Canonical Product Flow
STATUS: OWNER-APPROVED STAGE TRUTH MASTER — PRINCIPLE / FLOW
ACTIVE CANONICAL STAGE TRUTH: YES
DERIVES FROM: CAMPAINER-CANONICAL-PRODUCT-FLOW-001 + CAMPAINER-FLOW-CORE-APPLICABILITY-MATRIX-001 + CAMPAINER-ONE-TIME-CAMPAIGN-FLOW-001
SCHEMA AUTHORITY: NO
BUILD AUTHORITY: NO
RUNTIME AUTHORITY: NO
META WRITE / LAUNCH AUTHORITY: NO
PRODUCT OWNER AUTHORITY: PRESERVED
0. מטרת המסמך
מסמך זה מרכז את Stage Truth של כל התחנות המאושרות ב־Canonical Product Flow. הוא אינו Screen Map ואינו Build Spec. תפקידו לקבוע, לכל תחנה, מה חייב להיות נכון בכניסה, מהו יעד ההבנה/ההכרעה, אילו Cores חלים, איזה Context/Knowledge נדרש, מהו התוצר, אילו סמכויות נדרשות, מה נכתב כראיה, כיצד יוצאים מן התחנה ולאן חוזרים כאשר המציאות פותחת אותה מחדש.
המסמך מכסה יחידת Entry משותפת, 11 תחנות במסלול העסקי/המתמשך ו־9 תחנות במסלול החד־פעמי. לאחר Owner Review ניתן לפצל כל יחידה למסמך Stage Core / Stage Truth נפרד בלי לשנות את המשמעות שנקבעה כאן.
1. דוקטרינת Stage Truth
Stage Truth מגדיר what must be true — לא איך המסך נראה ולא איזה מודל/Prompt/DB מיישמים.
Stage אינו מקבל בעלות של Core. הוא משתמש בבעלויות הקנוניות שכבר נקבעו.
Stage יכול להכיל כמה Moments/Interactions, וכמה Stages יכולים להופיע באותו Workspace.
Exit Criteria אינם 'המשתמש לחץ הבא'. Exit קיים רק כאשר אמת התחנה וה־Handoff downstream סגורים במידה מספקת.
Unknown יכול להישאר פתוח אם אינו מונע החלטה אחראית; Unknown מהותי חייב להיות גלוי ומנוהל.
Semantic Return הוא תוצאה תקפה של Stage כאשר meaning/authority/evidence/capability אינם נסגרים.
Reopen מחזיר לבעל ההחלטה המקצועי הנכון, לא למסך הקודם אוטומטית.
Payment, Approval, Authorization, Execution ו־Verified Readback נשארים מצבים נפרדים.
בפיילוט: החלטות מקצועיות וביצועיות מהותיות נשארות תחת 100% Human Review.
2. רשימת ה־Stages הקנונית
ENTRY — Branch Selection
A1 — Short Diagnosis / Minimum Sufficient Initial Understanding
A2 — Strategy Initial + Route Recommendation
A3 — Choice / Service Scope / Payment
A4 — Progressive Deep Diagnosis + Baseline
A5 — Full Strategy
A6 — Studio
A7 — Campaign / Execution Readiness
A8 — Campaign Review + User Approval
A9 — Authorization → Fresh Preflight → Launch → Verified Readback
A10 — Managed Marketing + Lead / Business Realization
A11 — Measurement → Learning → Next Decision
B1 — One-Time Campaign Intake
B2 — One-Time Brief + Advisor Recommendation
B3 — One-Time Scope + Price + Payment
B4 — One-Time Studio
B5 — One-Time Campaign Review + User Approval
B6 — One-Time Authorization + Preflight + Launch + Readback
B7 — One-Time Managed Run
B8 — End Condition + Closure
B9 — Measurement + Summary + Learning Return
3. תבנית מחייבת לכל Stage
Stage Purpose
Entry Truth / Preconditions
Decision / Understanding Target
Primary / Required / Conditional Cores
Minimum-Sufficient Context Projection
Knowledge Need / Activation
Inputs
Outputs / Work Objects
Authority Gates
Evidence Writes
Semantic Handoff Out
Semantic Return
Exit Truth
Reopen Conditions
Pilot Human Review
Stage-specific Invariant
4. Shared Entry Stage Truth
ENTRY — Branch Selection
Purpose: לאפשר כניסה ברורה למסלול העסקי/המתמשך או למסלול החד־פעמי, בלי סיווג נסתר ובלי מסך בחירת מסלול כללי שחוסם את הכניסה.
Entry Truth: המשתמש הגיע לנקודת ההתחלה; אם קיים Context קודם, ידוע לפחות מי המשתמש ומהו ה־Business הפעיל כאשר רלוונטי.
Decision / Understanding Target: איזה ענף המשתמש בוחר להתחיל עכשיו.
Cores: Primary: EXP interaction + ADV continuity. Required: ADV, EXP. Conditional: CTX; K/E רק להסבר מהותי.
Context Projection: זהות משתמש ו־Business scope בלבד אם כבר ידועים ושימושיים.
Knowledge Need: ללא Knowledge activation כברירת מחדל.
Inputs: User intent + existing scoped context if available.
Outputs / Work Objects: Branch Choice + active scope reference.
Authority Gates: בחירת ענף אינה Execution Authority ואינה הסכמה לפעולה חיה.
Evidence Writes: בחירת ענף; scope פעיל אם קיים; state transition.
Handoff Out: ל־A1 או B1 עם branch identity ו־minimum context.
Semantic Return: ל־ADV כאשר מתברר שהבחירה אינה מתאימה מקצועית; אין המרה שקטה לענף אחר.
Exit Truth: הענף ברור והמשתמש יודע לאיזה מסע הוא נכנס.
Reopen: המשתמש משנה בחירה או שהצורך מתברר כ־ongoing/one-time באופן שדורש בחירה מחדש.
Pilot Human Review: לא נדרשת ביקורת מקצועית מהותית רק לבחירת הענף; כל שינוי כפוי אסור.
Invariant: Branch choice שייך למשתמש; Campainer יכולה להציע מעבר אך לא לבצע אותו ללא בחירה מפורשת.
5. Branch A — Business / Ongoing Stage Truth
A1 — Short Diagnosis / Minimum Sufficient Initial Understanding
Purpose: להבין מספיק את העסק והצורך כדי לתת Insight ו־Strategy Initial אמיתיים לפני תשלום.
Entry Truth: Branch A נבחר; Business/Offering יכולים להיות ידועים חלקית; אין דרישה לתיק עסק מלא.
Decision / Understanding Target: Minimum Sufficient Initial Understanding של Business, Offering, Goal, current state, desired customer/work, material constraints ו־Unknowns.
Cores: Primary: ADV. Required: DIR, CTX, K/E, EXP. Conditional: GL, MET.
Context Projection: Business, Offering, goal, known state, relevant prior commitments/history בלבד.
Knowledge Need: Scoped business/industry/customer/strategy priors שמסוגלים לשפר Hypotheses/Questions; Prior ≠ Local Fact.
Inputs: User answers, existing local context, relevant authorized sources, targeted knowledge.
Outputs / Work Objects: Initial Understanding + material Unknowns + evidence/source basis ל־A2.
Authority Gates: אין Execution Authority; user statements/corrections may establish scoped local claims according to Context rules.
Evidence Writes: Local claims, sources, scope, corrections, uncertainty/Unknowns.
Handoff Out: ל־A2: minimum context + knowledge projection + unresolved but manageable unknowns.
Semantic Return: ל־ADV/DIR כאשר נדרשת שאלה/ראיה ממוקדת או קיימת סתירה.
Exit Truth: ניתן לייצר Strategy Initial שימושית, מקצועית ושקופה בלי להמציא חסר.
Reopen: מידע חדש שמשנה את ההבנה הראשונית.
Pilot Human Review: Human Review על material initial professional judgment בפיילוט.
Invariant: אין Fixed Questionnaire; מפסיקים כאשר המידע הנוסף כבר לא משנה מהותית את A2.
A2 — Strategy Initial + Route Recommendation
Purpose: לתת ערך מקצועי אמיתי לפני תשלום ולהציג כיוון ראשוני, שלוש תובנות ומסקנת Route Recommendation אחת קוהרנטית.
Entry Truth: A1 נסגר ברמת minimum understanding; evidence/unknowns גלויים.
Decision / Understanding Target: מה Campainer מבינה, מה המשמעות המקצועית, מה מומלץ עכשיו, ומהו המסלול העסקי המתאים לביצוע הכיוון.
Cores: Primary: ADV. Required: DIR, CTX, K/E, EXP. Conditional: GL, META, MET, M/B.
Context Projection: רק local truth הנדרש להסביר current state, goal, problem/opportunity ו־constraints.
Knowledge Need: Strategy/business/customer priors + contradictions; Meta possibility only if it can change feasibility/route.
Inputs: A1 output + relevant decision frame + knowledge projections.
Outputs / Work Objects: Strategy Initial version + three insights + recommendation + route recommendation + rationale + roadmap + conditions for reconsideration.
Authority Gates: Recommendation ≠ Permission. User may accept/reject/defer the commercial route; no live authority.
Evidence Writes: Evidence basis, assumptions, Unknowns, route decision lineage.
Handoff Out: ל־A3 עם recommended route/service scope basis.
Semantic Return: חזרה ל־A1 אם local truth חסר/סותר; Return לבעל domain אם feasibility input משנה meaning.
Exit Truth: המשתמש מבין את הערך, ההמלצה והמסלול — לפני Payment.
Reopen: Business/Offering/Goal change or contradictory evidence.
Pilot Human Review: Human Review על Strategy Initial material recommendation בפיילוט.
Invariant: Route Recommendation היא פרק הסיום של Strategy Initial, לא Stage עצמאי.
A3 — Choice / Service Scope / Payment
Purpose: לאפשר בחירה מסחרית מודעת אחרי שהערך וההיגיון כבר הוצגו.
Entry Truth: A2 הוצג והמשתמש מבין recommendation/route.
Decision / Understanding Target: איזה Service Scope המשתמש בוחר והאם התנאי המסחרי הושלם.
Cores: Primary: ADV explanation + EXP interaction. Required: ADV, EXP, CTX. Conditional: DIR.
Context Projection: Selected route/scope והעובדות המקומיות המינימליות הדרושות להסבר הרכישה.
Knowledge Need: None by default.
Inputs: Route recommendation + commercial offer/terms.
Outputs / Work Objects: User Choice + Service Scope + Payment State.
Authority Gates: Payment grants commercial entitlement only. Payment ≠ Strategy Approval ≠ Creative Approval ≠ Authorization ≠ Launch.
Evidence Writes: Selected scope, payment reference/state, commercial commitments.
Handoff Out: ל־A4 עם paid/selected scope; בלי להעביר authority שלא ניתן.
Semantic Return: ל־ADV/DIR אם scope המבוקש סותר recommendation או משנה אותו מהותית.
Exit Truth: Scope understood; payment confirmed when required.
Reopen: Material change in scope, duration or cost.
Pilot Human Review: Human Review only when commercial choice materially changes professional scope.
Invariant: Billing is downstream contract, not a Core.
A4 — Progressive Deep Diagnosis + Baseline
Purpose: להעמיק רק במה שנחוץ ל־Full Strategy אחראית ומדידה ולשמור נקודת התחלה אמינה לפני intervention מהותי.
Entry Truth: A3 closed; commercial scope active; no need for full-context completeness.
Decision / Understanding Target: Minimum Sufficient Understanding for Full Strategy + scoped Baseline.
Cores: Primary: ADV. Required: CTX, DIR, K/E, MET, EXP. Conditional: GL, BRAND, M/B, META.
Context Projection: Business, Offering, Customer/Account, Buyer State, Buying Situation, Journey, economics/capacity, sales handling, Brand/Proof, constraints לפי decision relevance.
Knowledge Need: Decision-specific professional knowledge + targeted evidence acquisition; no fixed deep-questionnaire corpus.
Inputs: A3 scope + existing context + authorized sources + targeted questions/evidence.
Outputs / Work Objects: Deep Understanding + Baseline Snapshot + Unknowns + measurement availability/state.
Authority Gates: No execution authority; user/local source authority applies only to facts/corrections within scope.
Evidence Writes: Local truth, baseline facts, sources, concurrent changes, Unknowns, measurement state.
Handoff Out: ל־A5 עם decision-ready Context/Knowledge/Measurement projections.
Semantic Return: למקור local truth, MET או DIR לפי סוג הפער.
Exit Truth: המידע מספיק ל־Full Strategy; remaining Unknowns are manageable.
Reopen: New evidence, contradiction, material business change, outcome maturation, new decision need.
Pilot Human Review: Human Review על material interpretation and baseline sufficiency.
Invariant: Stop asking when remaining Unknowns no longer change Strategy/Audience/Offer/Creative/Executability/Risk/Measurement.
A5 — Full Strategy
Purpose: לסגור את ההחלטה המקצועית המרכזית שממנה ייגזרו Studio, Media, Execution ו־Measurement.
Entry Truth: A4 produced sufficient local truth, baseline/measurement meaning and relevant knowledge.
Decision / Understanding Target: Current State → Desired State → Problem/Bottleneck/Opportunity → Candidate mechanisms/strategies → Evidence/Unknowns → Recommended Strategy → Strategic Job → Must-Believe/Proof Requirement → Offer/Route/Next Step → Measurement Intent.
Cores: Primary: ADV. Required: DIR, CTX, K/E, GL, EXP. Conditional: MET, META, M/B, BRAND.
Context Projection: Current/desired state, buyer/account/buying situation, goal, constraints, baseline and relevant business truth.
Knowledge Need: Candidate mechanisms/strategies, evidence for/against, contradictions, scoped priors, measurement/platform implications as needed.
Inputs: A4 output + domain contributions.
Outputs / Work Objects: Strategic Intent + selected/recommended Strategy + evidence/unknowns + downstream semantic basis.
Authority Gates: User choice/Strategy Approval when required; still no external-write authorization.
Evidence Writes: Decision lineage, strategy version, evidence basis, Unknowns, user choice/approval state.
Handoff Out: ל־A6/A7: closed Strategic Intent + proof/brand/measurement/budget implications.
Semantic Return: ל־A4 אם understanding חסר; לבעל domain כאשר specialist constraint דורש clarification; חזרה ל־ADV/DIR אם meaning משתנה.
Exit Truth: Strategic Intent מספיק סגור למסירה downstream בלי שהמקבל ימציא Strategy.
Reopen: Goal, bottleneck, offering, buyer state, constraint or material evidence changes.
Pilot Human Review: 100% Human Review על material strategy recommendation/approval בפיילוט.
Invariant: Marketing Problem/Bottleneck precedes material Strategy; platform convenience does not choose Strategy.
A6 — Studio
Purpose: להפוך Strategic Intent לנכסים ולקריאייטיב מוכן תוך הפרדת Brand Truth מ־Creative Judgment.
Entry Truth: A5 Strategic Intent is closed enough; relevant business/brand scope identified.
Decision / Understanding Target: Brand/asset readiness + faithful Creative representation/execution.
Cores: Primary: BRAND in Brand Assets room; CR in Creative room. Required: ADV, CTX, K/E, BRAND, CR, EXP. Conditional: DIR, META, MET, EO.
Context Projection: Strategic Intent, buyer state, offer/CTA, Brand scope, approved assets/proof, rights/consent/provenance, protected elements.
Knowledge Need: Brand/asset + Creative professional knowledge; platform/measurement only when needed.
Inputs: A5 semantic handoff + available assets/sources + constraints.
Outputs / Work Objects: Brand Snapshot + Creative Intent/Concept/Execution package + asset/rights lineage + material gaps.
Authority Gates: Protected Brand/claim/material meaning changes require appropriate approval; ordinary creative freedom stays bounded.
Evidence Writes: Brand snapshot/version, asset lineage, rights state, creative lineage, gaps/returns.
Handoff Out: ל־A7: Campaign Creative Package + scoped Brand/rights/measurement context.
Semantic Return: CR → BRAND/ADV when proof/asset/rights/brand truth blocks fidelity; BRAND → ADV/DIR when requested expression requires strategy change.
Exit Truth: Campaign creative/assets sufficient for readiness evaluation.
Reopen: Asset/rights/proof/strategy change, campaign evidence, creative issue, Brand Change Candidate.
Pilot Human Review: Human Review on material Brand/claim changes and material Creative meaning decisions.
Invariant: Studio is one product place with two professional rooms; Brand Core ≠ Creative Core.
A7 — Campaign / Execution Readiness
Purpose: לחבר Strategy + Studio + Media/Budget + Meta + Measurement + Business Realization + Authority readiness למהלך שניתן לבצע באחריות.
Entry Truth: A5/A6 outputs available; relevant live/platform state can be checked.
Decision / Understanding Target: האם הקמפיין ניתן להצגה למשתמש כ־responsible executable plan, ומהם gaps/conditions.
Cores: Primary: DIR. Required: ADV, CTX, K/E, GL, MET, META, BRAND, CR, M/B, EXP. Conditional: EO.
Context Projection: Approved strategic intent, campaign package, economics/capacity, Golden/realization context, permissions/current state, baseline/measurement state.
Knowledge Need: Media allocation, current Meta capability, measurement readiness, sales/lead handling, relevant platform/industry constraints.
Inputs: A5/A6 outputs + current Meta/measurement/business state.
Outputs / Work Objects: Campaign Plan/Package ready for review + readiness decision + manageable gaps + dependencies/return conditions.
Authority Gates: Readiness ≠ Authorization; no live authority created.
Evidence Writes: Readiness basis, media decision basis, Meta possibility/current-state evidence, measurement readiness, dependencies.
Handoff Out: ל־A8: exact plan version, assumptions, risks, authority still absent.
Semantic Return: ל־domain owning broken meaning — Studio, Strategy, Media, Meta, Metrics, Context.
Exit Truth: Executor will not need to invent professional meaning; plan is reviewable and responsible.
Reopen: Freshness failure, technical impossibility, budget/economics/capacity change, measurement gap, contradiction.
Pilot Human Review: 100% Human Review on material Media/Budget and readiness decisions.
Invariant: START NOW / START+COMPLETE IN PARALLEL / RESPONSIBLE ALTERNATIVE / WAIT / PRESERVE / genuine STOP.
A8 — Campaign Review + User Approval
Purpose: להציג למשתמש את המהלך המדויק לפני פעולה חיה ולקבל Approval תחום לגרסה המוצגת.
Entry Truth: A7 produced a reviewable plan/package with assumptions/risks.
Decision / Understanding Target: Approve / reject / request material change to the presented campaign/plan.
Cores: Primary: ADV explanation + EXP interaction. Required: ADV, EXP, CTX, DIR. Conditional: BRAND, CR, M/B, META, MET, GL, K/E.
Context Projection: Exact campaign/plan version proposed + relevant assumptions/risks.
Knowledge Need: None by default; activate only to answer decision-relevant questions.
Inputs: A7 review package.
Outputs / Work Objects: Approval state + corrections + approved version/scope.
Authority Gates: Approval ≠ Execution Authorization in pilot.
Evidence Writes: Approved version, approval scope, user corrections, rejected/deferred items.
Handoff Out: ל־A9 with exact approved version and explicit note that live authorization is still required.
Semantic Return: ל־A5/A6/A7 כאשר requested change alters strategy/brand/budget/measurement/meaning.
Exit Truth: Presented version is understood and approved at appropriate scope.
Reopen: User requests material change or new evidence changes plan.
Pilot Human Review: 100% Human Review on material campaign/creative/plan approval.
Invariant: No inference from 'sounds good', Payment or prior approval to live-write authority.
A9 — Authorization → Fresh Preflight → Launch → Verified Readback
Purpose: להפוך plan מאושר לפעולה חיה באופן מורשה, נאמן וניתן לאימות.
Entry Truth: A8 approved exact version; target/scope known; live authority not yet assumed.
Decision / Understanding Target: Is the exact action authorized, still executable, and verified after execution?
Cores: Primary: EO. Required: META, CTX, ADV, EXP. Conditional: MET, M/B, BRAND, CR, DIR.
Context Projection: Authorized action target/scope, approved intent, authority state, current live state, protected constraints, expected resulting state.
Knowledge Need: Current platform/permission/capability knowledge + action-specific technical constraints only.
Inputs: Approved plan + explicit authorization + current Meta state.
Outputs / Work Objects: Authorization record + Preflight result + execution receipt + Verified/Unverified Readback state.
Authority Gates: Explicit scoped Authorization mandatory for material live action; Payment/Approval/prior connection insufficient.
Evidence Writes: Authorization, preflight state, attempts, receipt, readback, failure/recovery/rollback state.
Handoff Out: ל־A10 when verified/known live state is established; Context receives verified operational state.
Semantic Return: ל־ADV/DIR/domain owner if exact intent cannot be executed faithfully.
Exit Truth: Action completed and resulting state verified, or uncertainty explicitly preserved.
Reopen: Stale state, permission change, failure, partial success, non-equivalent path, readback contradiction.
Pilot Human Review: 100% Human Review on launch/material writes and semantics-affecting recovery/rollback.
Invariant: Execution attempt ≠ verified state change; technical alternative ≠ semantic equivalence.
A10 — Managed Marketing + Lead / Business Realization
Purpose: לנהל פעילות שיווקית חיה המחוברת לתוצאות העסק ולא להסתפק ב־Ads Manager state.
Entry Truth: A9 established live/known state; campaign and business context active.
Decision / Understanding Target: For each active Moment: what decision is required now across delivery, media, creative, lead potential, sales realization, economics/capacity and business outcome?
Cores: Primary: DIR per decision moment. Required: ADV, CTX, GL, MET, M/B, EXP. Conditional: K/E, CR, BRAND, META, EO, LRN.
Context Projection: Current campaign, lead/opportunity progression, sales treatment, capacity/economics, interventions, goals and commitments.
Knowledge Need: Media, sales/lead handling, measurement, creative/brand/platform knowledge activated by current bottleneck/opportunity.
Inputs: Live evidence + context + decision triggers.
Outputs / Work Objects: Recommendation / Task / Test / Wait / Preserve / Do Nothing / Authorized Change candidate + updated operational/business evidence.
Authority Gates: Each material budget/live/business intervention requires appropriate approval/authorization.
Evidence Writes: Campaign changes, sales treatment, business interventions, outcomes, spend, capacity, concurrent changes, decision/authority lineage.
Handoff Out: ל־A11 when outcomes/evidence mature enough for interpretation; או חזרה ל־A6/A7/A9 לפי decision.
Semantic Return: ל־Stage/domain owning the discovered issue; EO only after authorization.
Exit Truth: No fixed terminal exit while ongoing relationship active; each Moment closes with a valid decision/state.
Reopen: Any material evidence, risk, drift, goal change, outcome maturation or contradiction.
Pilot Human Review: 100% Human Review on material professional, budget, live and business-intervention decisions.
Invariant: Potential Lead Quality ≠ Business Realization Capability ≠ Realized Outcome.
A11 — Measurement → Learning → Next Decision
Purpose: להפוך תוצאות לראיות ולהחלטה הבאה בלי self-promotion של תוצאה לאמת.
Entry Truth: Relevant intervention/change history and outcomes exist; maturity/coverage may be partial.
Decision / Understanding Target: What happened, what may be inferred, what remains Unknown, what becomes a Learning Candidate, and which next decision is warranted.
Cores: Primary: MET measurement meaning + LRN candidate lifecycle. Required: CTX, K/E, DIR, ADV, EXP, MET, LRN. Conditional: GL, M/B, CR, BRAND, META, EO.
Context Projection: Baseline/current state, intervention/change history, outcomes, exposure/treatment semantics, business changes.
Knowledge Need: Measurement/causal knowledge, transferability rules, contradictions, prior evidence, domain-specific interpretation.
Inputs: A10 evidence + relevant measurement contracts/state.
Outputs / Work Objects: Measurement Interpretation + Learning Candidate/disposition if warranted + Context/Knowledge update references + Next Decision.
Authority Gates: No execution authority by default; next action must re-enter its proper authority chain.
Evidence Writes: Result, uncertainty/causal class, candidate, validation/scope disposition, updates/next-decision linkage.
Handoff Out: ל־appropriate Stage/domain for Next Decision; local truth updates to CTX; general knowledge only through governed lifecycle.
Semantic Return: Return when measurement meaning is insufficient or candidate scope cannot be supported.
Exit Truth: A valid next decision or valid Wait/Preserve/Do Nothing state exists.
Reopen: Late outcome, corrected data, contradiction, replication failure, drift, new evidence.
Pilot Human Review: Human Review on material causal interpretation and any broader reuse/promotion candidate.
Invariant: Result → Metrics Interpretation → Learning Candidate → governed update; never Result → 'system learned' → Truth.
6. Branch B — One-Time Campaign Stage Truth
B1 — One-Time Campaign Intake
Purpose: להשיג Minimum Sufficient Campaign Understanding למשימה תחומה בלי אבחון עסקי רגיל.
Entry Truth: One-Time branch selected; specific advertising need exists.
Decision / Understanding Target: What is being advertised, purpose, audience/area, time, budget, offer/CTA/destination, assets, constraints and End Condition.
Cores: Primary: ADV. Required: CTX, K/E, EXP. Conditional: DIR, GL, MET, META, M/B.
Context Projection: Campaign-scoped local truth only; no deep business context by default.
Knowledge Need: Only knowledge that can materially change this campaign decision.
Inputs: User facts, existing scoped context, optional assets, targeted knowledge.
Outputs / Work Objects: One-Time Campaign Understanding + local claims/unknowns + proposed End Condition.
Authority Gates: No execution authority; user supplies/corrects campaign-scoped facts.
Evidence Writes: One-time scope, facts/source/time, constraints, Unknowns, proposed End Condition.
Handoff Out: ל־B2 with minimum campaign truth.
Semantic Return: ל־user/ADV for missing material facts; to ongoing branch only by explicit user choice.
Exit Truth: Brief/Recommendation can be created responsibly.
Reopen: Goal/time/audience/area/offer/budget/destination/end condition changes.
Pilot Human Review: Human Review on material professional interpretation.
Invariant: No Short Business Diagnosis, Strategy Initial or Full Strategy requirement.
B2 — One-Time Brief + Advisor Recommendation
Purpose: להפוך Intake ל־Brief מקצועי ולהמלצה ברורה על מה לבנות ולנהל.
Entry Truth: B1 closed with sufficient campaign truth and explicit Unknowns.
Decision / Understanding Target: What campaign should be built, within what time/budget/scope, and why.
Cores: Primary: ADV. Required: CTX, K/E, EXP. Conditional: DIR, M/B, META, MET, GL, BRAND, CR.
Context Projection: Minimum campaign truth sufficient to explain build/management recommendation.
Knowledge Need: Campaign/media/creative/platform/measurement knowledge only as needed.
Inputs: B1 output + domain contributions when relevant.
Outputs / Work Objects: One-Time Brief + Advisor Recommendation + rationale + time/budget assumptions + End Condition.
Authority Gates: Recommendation ≠ Permission.
Evidence Writes: Brief version, recommendation, rationale, assumptions, Unknowns.
Handoff Out: ל־B3 with defined service scope basis.
Semantic Return: ל־B1 if truth insufficient; to domain owner if feasibility changes recommendation.
Exit Truth: User can understand what Campainer proposes to build/manage and why.
Reopen: Material scope/goal/time/budget change.
Pilot Human Review: Human Review on material recommendation.
Invariant: Fast does not mean shallow: Brief is campaign-specific professional decision support.
B3 — One-Time Scope + Price + Payment
Purpose: לקבע Service Scope/price/payment לפני Studio/production work בתשלום.
Entry Truth: B2 recommendation understood.
Decision / Understanding Target: What service is purchased, for what management period/scope, at what service price, separately from Media Budget and other approved costs.
Cores: Primary: ADV explanation + EXP interaction. Required: ADV, EXP, CTX. Conditional: DIR.
Context Projection: One-time service scope and commercial terms only.
Knowledge Need: None by default.
Inputs: B2 brief/recommendation + commercial offer.
Outputs / Work Objects: Commercial Choice + Payment State + scoped service commitment.
Authority Gates: Payment for service only; Payment ≠ Approval/Authorization/Launch.
Evidence Writes: Scope/payment state and commercial reference.
Handoff Out: ל־B4 after payment/entitlement where required.
Semantic Return: ל־ADV/DIR when requested scope changes professional recommendation.
Exit Truth: Service Scope understood and Payment confirmed when required.
Reopen: Scope/production/cost change.
Pilot Human Review: Human Review only if commercial choice materially changes professional scope.
Invariant: Service Price ≠ Media Budget; Billing is not a Core.
B4 — One-Time Studio
Purpose: להכין נכסים וקריאייטיב נאמנים ל־One-Time Brief, בלי לכפות Brand System מלא.
Entry Truth: B3 closed; One-Time Brief active; assets may or may not exist.
Decision / Understanding Target: What assets/brand truth are usable, and what creative representation/execution is needed for this one-time job.
Cores: Primary: BRAND in Brand Assets room; CR in Creative room. Required: ADV, CTX, K/E, BRAND, CR, EXP. Conditional: DIR, META, MET, EO.
Context Projection: One-Time Brief, campaign job, audience/time/CTA, uploaded assets, rights/provenance, relevant Brand scope.
Knowledge Need: Brand/asset + Creative knowledge; placement/measurement only as needed.
Inputs: B2/B3 outputs + optional user assets.
Outputs / Work Objects: Scoped Brand Snapshot + Creative Package + asset/rights lineage + gaps/returns.
Authority Gates: Protected Brand/material claim changes require approval; ordinary creative freedom stays bounded.
Evidence Writes: Asset/source/rights lineage, creative lineage, gaps/returns.
Handoff Out: ל־B5 exact campaign version ready for review.
Semantic Return: CR → BRAND/ADV; BRAND → ADV/DIR if meaning must change.
Exit Truth: Campaign creative/package can be shown for approval.
Reopen: Asset/rights/proof/brief change.
Pilot Human Review: Human Review on material Brand/claim/creative meaning decisions.
Invariant: Assets are optional; missing ordinary asset is not automatic Stop.
B5 — One-Time Campaign Review + User Approval
Purpose: להציג את הקמפיין החד־פעמי המוכן ולקבל Approval תחום לפני live authorization.
Entry Truth: B4 produced reviewable exact version.
Decision / Understanding Target: Approve/reject/request material change to the one-time campaign.
Cores: Primary: ADV + EXP. Required: ADV, EXP, CTX. Conditional: DIR, BRAND, CR, M/B, META, MET, K/E.
Context Projection: Exact one-time campaign version + scope/assumptions.
Knowledge Need: Only for material approval questions.
Inputs: B4 package + relevant plan/budget/time context.
Outputs / Work Objects: Approval state + corrections + approved scope/version.
Authority Gates: Approval ≠ Authorization.
Evidence Writes: Approved version, corrections, approval scope.
Handoff Out: ל־B6 exact approved version, authority still absent.
Semantic Return: ל־B2/B4 if requested change is material.
Exit Truth: Campaign version understood and approved.
Reopen: User requests material change or new evidence emerges.
Pilot Human Review: 100% Human Review on material approval.
Invariant: No silent inference of launch authority from campaign approval.
B6 — One-Time Authorization + Preflight + Launch + Readback
Purpose: להפעיל את הקמפיין החד־פעמי רק בסמכות ולוודא את המצב החי.
Entry Truth: B5 approved exact version; target/scope/end condition known.
Decision / Understanding Target: Is launch/spend explicitly authorized and still executable now; what live state resulted?
Cores: Primary: EO. Required: META, CTX, ADV, EXP. Conditional: MET, M/B, BRAND, CR, DIR.
Context Projection: Authorized one-time action, scope, budget/spend authority, current platform state, End Condition, expected result state.
Knowledge Need: Current Meta/technical capability and action-specific constraints.
Inputs: Approved campaign + explicit authorization + live preflight evidence.
Outputs / Work Objects: Authorization + Preflight + Execution Receipt + Readback.
Authority Gates: Explicit scoped Authorization required; Payment and campaign Approval are insufficient.
Evidence Writes: Authorization, preflight, attempts, receipt, readback, final/uncertain state.
Handoff Out: ל־B7 with known live campaign state.
Semantic Return: ל־ADV/DIR/domain owner if faithful execution impossible.
Exit Truth: Live state verified or uncertainty preserved explicitly.
Reopen: Failure, permission/state change, partial success, readback contradiction.
Pilot Human Review: 100% Human Review on launch/material writes and semantics-affecting recovery.
Invariant: Technical success is not business success; receipt is not verified state.
B7 — One-Time Managed Run
Purpose: לנהל את הקמפיין לאורך התקופה שנקבעה, גם אם הוא חד־פעמי.
Entry Truth: B6 established live state; time/budget/end condition active.
Decision / Understanding Target: What should be changed, preserved, waited on or stopped given remaining time/budget and current evidence?
Cores: Primary: DIR per decision moment. Required: ADV, CTX, MET, M/B, EXP. Conditional: META, EO, CR, BRAND, GL, K/E, LRN.
Context Projection: Campaign state, remaining time/budget, results, destination, relevant lead/business outcomes, End Condition.
Knowledge Need: Media/measurement/creative/platform knowledge activated by current decision.
Inputs: Live campaign evidence + trigger.
Outputs / Work Objects: Managed decision/action state: Add/Hold/Reduce/Reallocate/Test/Wait/Preserve + authorized change when applicable.
Authority Gates: Material changes beyond authorized bounds require new approval/authorization.
Evidence Writes: Spend/delivery, media/creative changes, outcomes, decision basis, authority, concurrent changes.
Handoff Out: ל־B8 when End Condition matures; to B4/B6/B2 according to issue.
Semantic Return: To correct professional owner; live execution only after authority.
Exit Truth: Each run decision closes responsibly; campaign continues only within scope and end condition.
Reopen: Time/budget/result maturity/technical/creative/event/offer/destination changes.
Pilot Human Review: 100% Human Review on material Media/Budget/live decisions.
Invariant: One-Time ≠ one ad ≠ no management.
B8 — End Condition + Closure
Purpose: לסיים את הקמפיין בזמן/תנאי שהוגדרו ולא להשאיר activity live במקרה.
Entry Truth: Defined End Condition exists and is now met/approaching, or explicit authorized closure instruction exists.
Decision / Understanding Target: Should the campaign close now, and can closure be executed/verified faithfully?
Cores: Primary: EO operational closure + ADV professional/user-facing closure. Required: CTX, META, ADV, EXP. Conditional: MET, M/B, DIR.
Context Projection: Approved End Condition, live state, remaining spend, outstanding obligations.
Knowledge Need: Current platform/closure capability only as needed.
Inputs: End Condition state + live campaign state.
Outputs / Work Objects: Closure decision + stop action + readback + final operational state.
Authority Gates: Pre-approved End Condition and/or explicit user instruction according to downstream contract; no autonomous extension.
Evidence Writes: Stop/closure action, readback, final spend/state, unresolved obligations.
Handoff Out: ל־B9 final scope/spend/timeline/closure state.
Semantic Return: ל־ADV/DIR if End Condition ambiguous or newer material decision conflicts.
Exit Truth: Campaign is closed/verified or uncertainty is explicit; obligations surfaced.
Reopen: End Condition changes, event/offer extends, user changes instruction, closure failure.
Pilot Human Review: Human Review on discretionary/material closure and recovery decisions.
Invariant: No one-time campaign remains live merely because nobody remembered to stop it.
B9 — Measurement + Summary + Learning Return
Purpose: לסכם מה נעשה ומה קרה, עם גבולות ההסקה, ולשמר למידה בהיקף הנכון.
Entry Truth: B8 closure state available; outcomes may still mature later.
Decision / Understanding Target: What can be reported now, what remains Unknown, what local learning exists, and what may need late reopen.
Cores: Primary: MET measurement + LRN when candidate warranted. Required: ADV, CTX, EXP, MET. Conditional: K/E, DIR, LRN, GL, M/B, CR, BRAND, META.
Context Projection: Final campaign scope, spend, timeline, changes, outcomes, closure state.
Knowledge Need: Measurement/causal interpretation + scoped learning/transferability only.
Inputs: Final operational/evidence package.
Outputs / Work Objects: Professional Summary + Measurement limits + local learning + Learning Candidate reference if warranted.
Authority Gates: No execution authority by default.
Evidence Writes: Final result, measurement limits, Unknowns, summary, local learning/candidate references.
Handoff Out: To CTX for local history; Knowledge/Learning only through governed candidate paths.
Semantic Return: Return if data correction/late outcome changes interpretation.
Exit Truth: User receives clear summary; local learning stored without false generalization.
Reopen: Late-maturing outcome, corrected data, contradiction, future one-time campaign needing relevant history.
Pilot Human Review: Human Review on material causal claims or broader learning candidates.
Invariant: Summary is not an Ads Manager dump; local learning does not auto-promote to Business/Brand/global Truth.
7. Cross-Stage Invariants
One continuous Advisor remains the user-facing professional identity.
Context owns local truth; Knowledge owns scoped professional knowledge/evidence state.
Director frames bounded decisions; Advisor owns professional judgment/recommendation/explanation.
Golden Lead value/fit ≠ Baseline Propensity ≠ Incremental Marketing Opportunity ≠ Access Need.
Lead Potential ≠ Business Realization ≠ Realized Outcome.
Brand Truth ≠ Creative Judgment; Studio co-location does not merge ownership.
Media decides marginal allocation; Meta states current platform capability/constraint.
Capability ≠ Authority; Payment ≠ Approval ≠ Authorization ≠ Execution.
Every material live execution uses authority + fresh preflight + controlled execution + readback where available.
Result ≠ Causal Explanation; Learning Candidate ≠ Truth.
Unknown remains explicit; no false dead end when responsible alternative exists.
Semantic Return targets the owner of broken meaning; Reopen targets the Stage owning the reopened decision.
Cross-business truth/assets/thresholds do not transfer automatically.
8. פיצול למסמכי Stage נפרדים — לאחר Owner Review
אם Master זה יאושר, הפיצול הבא ייעשה בלי שינוי משמעות: ENTRY-STAGE-TRUTH; A1–A11 Stage Truth artifacts; B1–B9 One-Time Stage Truth artifacts. כל מסמך נפרד יירש את Canonical Product Flow, Applicability Matrix ואת היחידה המקבילה במסמך זה.
לאחר הפיצול ייגזרו Decision & Handoff Contracts רק במקומות שבהם מעבר meaning/authority/execution מצדיק חוזה מפורש, ולא חוזה מלאכותי בין כל שני מסכים.
9. Acceptance Gates
כל 21 יחידות ה־Stage מיוצגות.
לכל Stage קיימים Entry Truth, Decision Target, Exit Truth ו־Reopen.
Primary/Required/Conditional Cores תואמים למטריצה המאושרת.
אין Stage שממציא Core ownership חדש.
Context/Knowledge הם minimum-sufficient ו־decision-driven.
Payment/Approval/Authorization/Execution אינם מתמזגים.
Studio נשאר מקום אחד עם שני חדרים מקצועיים.
One-Time branch אינו נדרש לאבחון/Strategy של המסלול העסקי.
Managed stages מחוברים ל־Business Realization ולא רק למדדי מדיה.
Measurement/Learning שומרים causal/epistemic boundaries.
Semantic Return/Reopen אינם 'back button' אלא routing מקצועי.
100% Human Review נשמר להחלטות מהותיות בפיילוט.
10. Status / Next Derivation
CURRENT STATUS: OWNER-APPROVED STAGE TRUTH MASTER — PRINCIPLE / FLOW.
OWNER APPROVAL: Product Owner approved this Stage Truth Master. Its 21 Stage units are active at Principle / Flow level; exact schemas, runtime mechanics and Build Authority remain deferred.
NEXT DERIVATION: split into Stage Truth artifacts → derive Decision & Handoff Contracts → Build Packages.
END — CAMPAINER-STAGE-TRUTH-MASTER-001 — v1.0
