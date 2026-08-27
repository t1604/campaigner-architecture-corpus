---
mirror_role: "Base44 read/reference mirror"
canonical_source: "Google Drive"
source_title: "GILUI-HAEMET-RETURN — D-44 IMPLEMENTATION DESIGN RECOMMENDATION — 001"
source_drive_id: "1Cv2qZUaLY03Bcny7EtvV_7ar7ry6ThqwsQmh1OK9nr8"
source_modified_at: "2026-08-23T07:59:33.159Z"
corpus_status: "current-required"
category: "companion"
---

> MIRROR NOTICE: This file is a controlled copy for Base44. Google Drive remains the canonical source. Do not infer implementation, deployment, runtime, or release authority from repository presence.

## Canonical source body

GILUI-HAEMET-RETURN — D-44 IMPLEMENTATION DESIGN RECOMMENDATION — 001
STATUS: READY_FOR_D44_DESIGN_RECONCILIATION
VERDICT: RECOMMEND D-44 WITH MATERIAL ARCHITECTURAL MODIFICATIONS
SCOPE: READ-ONLY SEMANTIC DESIGN REVIEW / NO LEADER WRITE / NO CAMPAINER CANONICAL PROMOTION / NO BUILD AUTHORITY


0. מסגרת ההכרעה ומקורות
ההכרעה מבוססת על קריאה מלאה של TO-GILUI-HAEMET — D-44 IMPLEMENTATION DESIGN DISCUSSION & DECISION — 001, Document ID 1xoMvEG8-1Upj7ROApVXgsKLDQ8dMX49uWk8x6XmfO98, revision AIroW36ghtd4Thj1lgKFIVcKBM42q49iILXfa0YhnK6cUm2wSlfjhCZB0e-OrelC6kDP-lcyVXO60LJUdZiu4ZuSyn7rfy6disRXVlfgDug.
היא מבוססת גם על LEADER — D-44 UNIFIED ADVISORY EXPERIENCE & FEDERATED INDEPENDENCE — OWNER-APPROVED CLARIFICATION — 001, Document ID 1hHcv8OSccQOEuPj9z1m90AjXe5S8b0APTZ5ejE4_WkQ, revision AIroW37WIB7zASgzQyr99kafBSb6FMHHYXo6CJdTsREwKE1znV_Px7A_ZXqhC7xZN-PRSNnh3MGJ1_TrmdHk7e7ai_1FsIejsFwObkLsSY0.
וכן על LEADER-ADVISOR-CORE-003 — CANONICAL CORE L, Document ID 1EiLnqI1i5GP-W5Gv7cjaBeb5h_thFJZKEu5ZKJfZRAE, revision AIroW35gj_oqMEFA5_Z38oGel1L93AsT-IMcJ3H_UyoWVHt15X5ZRs6jUn71b30CSXy_3Gfvm-kWGgvpq_wiqwhexAmVg3KCaAJfC4wt7yI; על קורפוס Leader שנקרא תחת הרשאת הממשק; על ארכיטקטורת Campainer, חוזי ה-Semantic Handoff/Return וה-Decision/Learning boundaries; ועל Return התיאום הקודם Document ID 1d5Yp0ibloXcnQ_1xcZJmjD95SQgAu_r378eXHzm3-Is.
מסמך זה הוא המלצת תכנון. הוא אינו משנה Product Truth, Core, Schema, API, Runtime, Build, Permission, Launch או Pilot באחד המוצרים.


1. שורה תחתונה
אני בוחר באפשרות B: D-44 נכון כדוקטרינת מוצר, אך יש לשנות מהותית את מנגנון המימוש.
אילו היינו מתכננים מאפס, לא הייתי בונה Shared Business Memory קבוע, Shared Truth Store, Host Advisor שמפעיל Advisor כפוף, Shared Permission Context, או Super-Advisor ניטרלי שמחזיק ידע ולמידה משלו.
הייתי בונה PATTERN E — EPHEMERAL FEDERATED ADVISORY COORDINATOR: מתאם ייעוצי פדרטיבי, ניטרלי וזמני; שני מומחים מקצועיים בבעלות המוצרים; AdvisorySessionContext מינימלי ובר-ניתוק; ידע פדרטיבי מבוסס Query/Projection/Reference; ו-Decision/Learning מקומיים המקושרים באמצעות refs.
נוסחת השורש המומלצת היא:
ONE USER-FACING CONVERSATION + TWO PRODUCT-OWNED PROFESSIONAL SPECIALISTS + EPHEMERAL NEUTRAL COORDINATION + FEDERATED SOURCE-OWNED KNOWLEDGE + LINKED LOCAL DECISION/LEARNING + RECEIVER-OWNED ACTION AUTHORITY.
D-44 הוא המנגנון הנכון ברמת כוונת המוצר. המנגנון הטכני הנכון הוא Pattern E, ולא פרשנות של זיכרון משותף או מוח שלישי.


2. הארכיטקטורה המומלצת בשפה פשוטה
המשתמש יכול לפתוח שאלה ב-Campaigner או ב-Leader ולבחור מצב Unified. המשטח שבו הוא נמצא מעביר את ה-turn למתאם ניטרלי וזמני יחד עם Context מינימלי ו-refs בלבד.
המתאם אינו קורא ישירות מסדי נתונים. הוא פונה בנפרד ל-Campaigner Specialty Gateway ול-Leader Specialty Gateway. כל מוצר מאמת מחדש Business, Actor, Scope, Purpose, Permission, Freshness ו-Disclosure לפני שהוא מחזיר Position מקצועי.
Campaigner מחזיר עמדה מקצועית בתחום Marketing/Advertising/Acquisition/Creative. Leader מחזיר עמדה מקצועית בתחום Lead Operations/Sales Execution. כל עמדה כוללת Observations, Interpretation, Recommendation, Evidence refs, Unknowns, Constraints, Change Conditions ו-Action Candidates בתחום שלה.
המתאם בודק התאמה, תלות או סתירה בין העמדות ומרכיב תשובה אחת. הוא רשאי ליצור Joint Recommendation כ-artifact ייעוצי לא-סמכותי; הוא אינו רשאי להפוך מסקנה לאמת, להעניק הרשאה, לבצע פעולה או לקדם Learning.
אם אחד המוצרים מנותק או חסום, ה-Advisor המקומי ממשיך לעבוד במלואו. Unified mode הופך ל-PARTIAL/UNAVAILABLE באופן גלוי, אך המוצר אינו מאבד זהות מקצועית, אמת, זיכרון מקומי או יכולת פעולה מקומית.


3. מודל הרכיבים והחוזים
3.1 Federated Connection and Mapping Registry
רישום אינטגרציה שמחזיק ConnectionRef ומיפויי Business/User/Offering/Object כ-assertions versioned. הוא אינו מבצע Global Identity Merge ואינו הופך למקור אמת של האובייקטים המקומיים.
3.2 AdvisorySessionContext
אובייקט תיאום ראשון-במעלה אך זמני: SessionRef, ConnectionRef, Business mapping, Actor refs, source surface, user mode, active question, Offering/Campaign/Cohort/window refs, inspected Evidence refs, hypotheses, unresolved questions, consulted specialties, Position refs, JointRecommendation ref, Decision/Action/Learning refs, per-product authorization/disclosure result, freshness/health, expiry and disconnection state.
ה-Session אינו נושא Permission ניידת, אינו מחזיק raw evidence כברירת מחדל ואינו זיכרון עסקי קנוני.
3.3 SpecialtyConsultRequest
חוזה בקשה למומחה: question/decision need, minimum-sufficient mapped refs, purpose, requested output class, exclusions, freshness need, correlation/session id וה-context שהמוצר המקבל רשאי לבדוק. הוא אינו פקודת disclosure.
3.4 SpecialistPosition
תוצר מקצועי source-owned: specialty/product, scope, material claims, evidence/provenance refs, observed/inferred/predicted distinctions, maturity, freshness, unknowns, contradictions, recommendation, expected mechanism, guardrails, change condition, action candidates and disclosure limits.
3.5 JointRecommendationEnvelope
Envelope בלתי-משנה ולא-אמת: references לשתי העמדות, common ground, conflict set, synthesized recommendation when justified, alternatives, dependencies, guardrails, decision owner, revisit conditions and source labels. ניתן לשמור אותו זמנית במישור התיאום ולהעתיק או להפנות אליו מקומית; הוא אינו Product Truth.
3.6 Linked Local Decision Records
כל מוצר שומר Decision Record מקומי סמכותי רק בתחום שבבעלותו. DecisionCorrelationId ו-DecisionRef מקשרים את הרשומות ואת ה-Joint Recommendation. אין shared mutable Decision object ואין Last-Write-Wins בין המוצרים.
3.7 Linked Local Learning Cases
כל מוצר שומר Learning Case מקומי לפי מנגנון הלמידה שלו. FederatedLearningLink מחבר hypothesis/intervention/population/metrics/evidence refs בין המקרים אך אינו מקדם אותם, אינו מחזיק Product Learning ואינו בעל תוצאה משותפת.
3.8 CrossProductActionRequest
חוזה intent בלבד: actor reference, Business mapping, exact source-owned target ref, requested semantic effect, human decision evidence, preconditions/version, idempotency/operation correlation, reason and requested result contract. המוצר המקבל מבצע authorization ו-Operation חדשים בבעלותו.
3.9 Coordination Health
סטטוסים נפרדים נדרשים ל-Connection Health, Mapping Health, Permission/Disclosure Health, Projection Freshness, Specialist Availability, Session Version, Measurement Quality ו-Action Result. אסור לאחד אותם ל-CONNECTED/OK יחיד.
כל שמות הרכיבים הם תכנון סמנטי. הם אינם אישור Schema, Service או API.


4. השוואת דפוסי המימוש
Pattern A — Neutral Federated Advisory Orchestrator: חזק ברציפות ובסינתזה, אך בגרסה מתמשכת שמחזיקה זיכרון, ידע או החלטות היא יוצרת quasi-product, God Advisor, נקודת כשל ותלות חדשה. REJECT בגרסה הקבועה; ADOPT רק את יכולת התיאום כמתאם ephemeral ללא בעלות סמנטית.
Pattern B — Peer-to-Peer Advisors + Host-led Session: חזק בעצמאות ובבהירות הבעלות, אך יוצר host bias, שונות לפי נקודת הכניסה ו-ping-pong. ADOPT את ה-peer gateways וה-handoff contracts; REJECT את סמכות ה-host להכריע מקצועית עבור שניהם.
Pattern C — One Host Advisor Orchestrates the Other: פשוט לכאורה, אך יוצר parent/child, מטשטש specialty, פוגע ב-consumer neutrality ומגדיל exit cost. REJECT.
Pattern D — Shared Knowledge Only: בטוח יחסית ומשמש fallback או שלב יסוד, אך אינו מממש את חוויית השיחה האחת ואת ערך ה-Joint Recommendation. REJECT כארכיטקטורה סופית; ADOPT כ-degraded mode וכבסיס ל-T1.
Pattern E — Ephemeral Federated Advisory Coordinator: משלב coordinator ניטרלי ללא אמת/זיכרון קנוני, gateways שווי-מעמד, session זמני, positions מקצועיים, synthesis מפוקח, החלטות ולמידה מקומיות. RECOMMEND.


5. Pattern E מול 18 קריטריוני ההכרעה
User continuity: שיחה אחת נשמרת באמצעות SessionRef ו-turn envelopes, בלי לטעון שיש Advisor מקצועי שלישי.
Specialty integrity: כל עמדה נוצרת ונחתמת בידי ה-Advisor הדומייני בלבד.
Joint reasoning: הסינתזה עובדת על מבנה positions, mechanisms, constraints ו-guardrails, ולא על concatenation של טקסטים.
Truth ownership: כל claim נושא owner/source/ref; ה-Joint Recommendation מסומן synthesis.
Permission isolation: disclosure נבדק בכל מוצר; coordinator אינו נושא הרשאה.
Action authority: mutation רק דרך המוצר וה-domain owner.
Federated independence: coordinator ו-peer הם additive; כל מוצר ממשיך לבד.
Retained learning: נשמר derived local learning, לא database mirror.
Freshness/drift: כל projection/position/learning נושא evidence period, last validation, stale/revalidation.
Identity complexity: mapping assertions versioned ורב-ערכיים; אין merge.
Failure isolation: local Advisor ממשיך; Unified mode מסומן partial.
Disagreement: conflict הוא first-class ואינו מוחלק.
Data minimization/privacy: עוברים minimum-sufficient projections/refs.
Auditability: Session/Consult/Position/Recommendation/Decision/Action correlations משחזרים lineage.
Build complexity: מורכב יותר מ-host advisor אך קטן ובטוח יותר מ-shared platform; ניתן לפריסה בשלבים.
T1 feasibility: אפשר להוכיח ערך בשאלות read-only צרות.
Consumer neutrality: שני ה-gateways הם peer contracts שניתנים להחלפה בעתיד.
Exit cost: session חי נסגר; local history/decisions/learning ממשיכים.


6. בעלות Data / Truth / Permission / Action
Campaigner נשאר בעל אמת Marketing/Advertising/Acquisition/Creative/Campaign, ההחלטות והפעולות הדומייניות שלו.
Leader נשאר בעל Contact/Account/Journey/Work/Routing/Capacity/Treatment/Qualification/Opportunity/Outcome, Core E operations וההחלטות הדומייניות שלו.
ה-Coordinator מחזיק לכל היותר routing plan, session version, consultation receipts, source-linked positions ו-JointRecommendation envelope לא-סמכותי במסגרת retention זמני. Custody של artifact אינו Truth ownership.
ה-Interface/Mapping layer מחזיק contracts, refs, mapping assertions, delivery/reconciliation state ו-lineage בלבד.
Permission אינה מועתקת. producer disclosure authorization ו-receiver/use authorization נבדקים בנפרד. Action authority נבדקת תמיד מחדש במוצר המבצע.


7. תכנון Conversation / Session
כן נדרש first-class AdvisorySessionContext, אך לא Shared Durable Business Memory.
הבעלות הלוגית היא של חיבור ה-Business והמשתמש לשיחה, לא של Campaigner או Leader. המשמורת יכולה להיות במישור אינטגרציה ניטרלי, ובלבד שהחוזה detachable, symmetric וניתן למחיקה ללא פגיעה במוצרים.
ה-Session חייב להיות versioned; conflicting updates אינם Last-Write-Wins. שינוי Business/Offering/Cohort או product surface מחייב visible context change ו-target re-resolution.
ה-Session שומר only minimum-sufficient conversational state. Raw transcripts, messages, CRM rows או campaign payloads נשארים במקור ומופיעים כ-refs או projection מצומצמת.
בניתוק: ה-Session נחסם ל-live consultation/action, מסומן DISCONNECTED/HISTORICAL, ותוקפו מסתיים לפי policy. כל מוצר יכול לשמר summary/decision/learning מקומי שהתקבל כדין; הוא אינו ממשיך לטעון לגישה חיה.


8. Advisor Orchestration
כן נדרש orchestration, אך השם והתפקיד הנכונים הם Federated Advisory Coordinator, לא Advisor Orchestrator ולא Super-Advisor.
הוא אחראי ל-mode enforcement, routing, minimum-context planning, calling both gateways, collecting Positions, conflict detection, synthesis eligibility, response composition, source labeling and coordination audit.
הוא אינו אחראי ל-domain truth, evidence truth, permissions, local memory, identity truth, Learning promotion, Policy, Business decision, action execution או recovery של operation מקומית.
מיקום: מישור אינטגרציה ניטרלי מבחינה לוגית. ניתן co-deploy אותו זמנית עם מוצר אחד, אך אסור שיהיו לו imports סמנטיים פרטיים, DB ownership של המארח או behavior שונה לפי host. אותה contract battery חייבת לרוץ משני המשטחים.
Failure mode: אם ה-Coordinator אינו זמין, המשתמש מקבל את ה-Advisor המקומי ואת האפשרות ל-Context Handoff/Separate View; אין אובדן של local operation.


9. User Choice ו-Mode Semantics
UNIFIED: coordinator רשאי להתייעץ בשני המוצרים בהתאם להרשאות ולהפיק synthesis.
CAMPAIGNER_ONLY: אין call, query, cache read או use של Leader לצורך אותו turn.
LEADER_ONLY: אין call, query, cache read או use של Campaigner לצורך אותו turn.
SEPARATE_VIEWS: שתי positions מוצגות בנפרד; synthesis מוגבל לסיכום ההבדלים בלבד.
EXCLUDE_PRODUCT_DATA: exclusion הוא turn-scoped disclosure/use constraint ונרשם ב-Session. הוא גובר על אופטימיזציית routing.
המצב חייב להיות גלוי וניתן לשינוי בכל שאלה. ברירת המחדל המומלצת היא opt-in לחיבור Unified ברמת Business, עם override מפורש ברמת session/turn.


10. Knowledge Transport
Live Query: למצבים שדורשים אמת עדכנית כגון spend, campaign state, capacity, response time, permissions או active outcome maturity.
Projection: לסיכומים נגזרים הניתנים לשימוש חוזר כגון Marketing Intent→Seller Context, downstream realization summary או Customer Voice pattern candidate.
Reference: ל-raw evidence, authoritative objects, Decision, Experiment, Learning Case ו-Operation. ה-reference אינו מבטיח שהמקבל רשאי לפתוח אותו.
Handoff Snapshot: לשאלה, cohort, hypothesis, knowns/unknowns והמשך investigation בזמן switch או degraded mode.
Events: רק בהמשך, למשפחות projection שנבחרו במפורש עם versioning, replay, revocation ו-reconciliation. אין generic event mirror.
כל transport נושא source/owner, Business mapping, scope/population/window, semantic class, provenance/evidence refs, freshness, uncertainty, disclosure/purpose, version/supersession and health.


11. Joint Recommendation ו-Disagreement
כל Advisor מחזיר SpecialistPosition מובנה. ה-Coordinator בונה conflict matrix לפי objective, proposed change, expected mechanism, capacity/resource effect, evidence maturity, guardrails and change conditions.
JOINT_RECOMMENDATION מותר רק כאשר ההמלצות תואמות, ניתנות לסידור בסדר תלוי, או שניתן לבנות חלופה משולבת הנתמכת בשתי העמדות.
DISAGREEMENT נדרש כאשר מנגנוני הפעולה, הסיכונים או המטרות מתנגשים ואין synthesis מבוסס. במקרה כזה מוצגות שתי העמדות, הראיות, מה ישנה כל עמדה ומיהו decision owner.
במקרה spend מול sales capacity: אם Leader מציג saturation מהימן, coordinator רשאי להציע sequence משולב — לא להעלות volume כעת; לתקן capacity/response-time או לצמצם message; לאחר guardrail period להעלות spend בהדרגה. זו synthesis רק אם שני המומחים מאשרים שה-sequence עקבי עם הראיות.
אם Campaigner טוען שהזדמנות עונתית תיעלם ו-Leader אינו יכול להגדיל capacity בזמן, אין fake consensus. מוצגות שתי אפשרויות וה-Owner מכריע trade-off עסקי.
ה-Decision Memory המקומי שומר את שתי ה-Position refs, conflict, alternatives, ההכרעה, actor/authority, effective scope, reason summary, guardrails, revisit condition and supersession.


12. Cross-Product Identity / Ref Model
נדרש CrossProductRef עם source product, object type, local immutable ref, version/effective time ו-BusinessLink.
Mapping הוא assertion נפרד: mapping type, local refs משני הצדדים, evidence, verifier, state, confidence/verification class, effective period, last verified, conflict, supersession and resolver.
מצבים רעיוניים: PROPOSED / VERIFIED / STALE / CONFLICTED / INVALID / REVOKED.
Business/User/Offering mapping אינו גורר Contact/Journey/Opportunity mapping. Person ≠ Acquisition Event ≠ Lead Journey ≠ Opportunity. פעולה או causal claim דורשים את target המדויק.


13. Decision Memory
אני דוחה Shared Mutable Decision Memory.
המודל המומלץ הוא Authoritative Local Decision Records + immutable source-linked DecisionRef/DecisionSummary + common DecisionCorrelationId.
החלטה משותפת יכולה ליצור כמה local effects, אך כל effect נשמר ומבוצע במוצר הבעלים. Conflict נשמר; אין overwrite של החלטה אחת באמצעות החלטה מקבילה.
ה-Coordinator רשאי להחזיק Recommendation/Decision correlation זמני לצורך UX ואודיט. הוא אינו decision owner.


14. Learning ו-Retained Memory
אני דוחה Shared Learning Case בעל owner ניטרלי.
המודל המומלץ הוא Linked Product-Local Learning Cases. כל מוצר קולט evidence/projection מה-peer כ-Evidence או Learning Candidate בלבד ומפעיל את מנגנון validation/promotion/demotion/reopen המקומי שלו.
FederatedLearningLink מחזיק common hypothesis/intervention, population mapping, Metric refs, evidence periods, case refs, maturity, disconnection state and reconciliation lineage.
RetainedLearningRecord מקומי לאחר ניתוק חייב להיות derived, purpose-bound ומינימלי: source product/domain, Business/Offering scope, evidence period, allowed provenance/summary, decision/experiment context, last validation, connection state, freshness/stability, limitations/confounders, revalidation trigger, retention/deletion basis and expiry where applicable.
Observation ≠ Learning. Result-after-change ≠ caused-by-change. Retained Learning ≠ Continued Source Access. Historical Learning ≠ Current Fact.


15. Disconnection / Exit Semantics
Local Product Memory: אמת, היסטוריה, Decision, Operation ו-Learning שהמוצר עצמו מחזיק כדין.
Federated Live Shared Knowledge: queries/projections זמניים המאושרים בזמן החיבור; גישה חיה נפסקת בניתוק.
Retained Learned Memory: מסקנה נגזרת מקומית, מצומצמת, עם lineage/freshness/limitations; נשמרת רק לפי purpose/privacy/retention.
Raw/Source Evidence: נשאר בבעלות המקור. caches ו-indexes של המקבל נמחקים או נחסמים בהתאם לחוזה; raw אינו נשמר רק כדי להגן על learning.
לאחר ניתוק, references למקור נשמרים כ-historical provenance בלבד כאשר מותר. אם deletion/revocation מונעים ביסוס או הסבר, ה-learning מסומן EVIDENCE_UNAVAILABLE, נחלש/נפתח מחדש או נמחק לפי policy.
Reconnect אינו revive אוטומטי. נדרשים mapping, authorization, freshness and reconciliation חדשים; replay חייב להיות idempotent.


16. CrossProductActionRequest
Request אינו Authorization ואינו Operation.
שדות סמנטיים מינימליים: request/correlation/idempotency id, source product/surface, actor/user intent evidence, BusinessLink, exact target CrossProductRef, requested semantic effect, reason, relevant Position/Decision refs, expected version/preconditions, requested result contract, expiry and cancellation.
המוצר המקבל חייב לפתור מחדש actor/membership, effective permission, Business scope, exact current target, version/state, policy/contactability/legal/provider gates; ליצור Operation מקומי; ולהחזיר REQUESTED / DENIED / ACCEPTED-PENDING / VERIFIED / PARTIAL / FAILED / UNKNOWN-UNVERIFIED / RECOVERY-REQUIRED או equivalents.
החלטה אנושית ברורה יכולה לעבור כ-decision evidence ולכן אין לדרוש confirmation כפול רק בשל מעבר המוצר. עם זאת, החלטה אינה עוקפת gate מקומי נוסף, ambiguity, stale target או High-Risk approval.
Direct-UI parity נשמרת: כל atomic action זמין באותו מוצר דרך ה-UI המקומי לאותו user scope. ה-Coordinator לעולם אינו מבצע direct write.


17. T1 / T1.1 / Later
T1: bilateral Business/User/Offering mapping; dual authorization; narrow read-only Projection/Query contracts; AdvisorySessionContext ephemeral; unified conversation במשטח אחד; SpecialistPositions; JointRecommendation/Disagreement עבור קטלוג צר של שאלות כגון why-not-selling ו-budget-vs-capacity; source labels; health/freshness; no cross-product actions; no retained cross-product learning promotion; no raw replication.
T1 חייב להוכיח את ערך השיחה האחת, לא רק deep link. עם זאת הוא מוגבל ל-read-only ולשאלות מוגדרות כדי שלא יכתיב מוקדם מדי Action/Learning architecture.
T1.1: continuity בין שני המשטחים; local Decision refs; linked Experiment/Learning Candidates; reconnect/disconnect reconciliation; saved user mode; broader but still governed projection families.
Later: CrossProductActionRequest לפי Action Catalog; selected event projections; retained learning rules after privacy/legal gates; broader question catalog; controlled automation only after authority/readback/recovery proof.
לא מומלץ להתחיל ב-generic bidirectional sync, universal cross-product search, durable shared transcript, shared database, global identity merge או cross-product autonomous action.


18. Failure / Security / Privacy Risks
Coordinator outage: local Advisors continue; Unified mode unavailable/partial.
Peer timeout or partial family: answer מסומן PARTIAL/UNKNOWN עם missing families; missing אינו zero.
Permission mismatch: אין existence leak, count, cached summary או hint. ניתן לומר שהמקור לא היה זמין לניתוח בלי לחשוף את קיומו.
Mapping stale/conflicted: אין material synthesis/action על target מעורפל.
Session split-brain: version conflict נשמר ונדרש reconciliation; אין Last-Write-Wins.
Prompt injection or untrusted content from peer evidence: כל תוכן נכנס הוא evidence, לא instruction. Tool/action instructions נבנות רק מה-governed decision/action path.
Raw data and transcript minimization: coordinator אינו warehouse; TTL, encryption, purpose limitation, access audit, deletion propagation and cache invalidation נדרשים.
Cross-Business isolation חלה לפני lookup, mapping, retrieval, synthesis, memory and action.
Recommendation laundering: coordinator חייב להראות source positions ולא להציג synthesis כ-fact.
Replay/duplicate action: idempotency and operation readback are mandatory.


19. שינויים נדרשים ב-Leader
להגדיר One Governed Business Memory כמטאפורת UX בלבד ולהחליף את מנגנון המימוש ב-Federated Governed Knowledge View.
להוסיף Pattern E, AdvisorySessionContext, Specialty Gateway, SpecialistPosition, JointRecommendationEnvelope, conflict/synthesis states ו-degraded-mode semantics.
להוסיף Cross-Product Mapping, Linked Local Decision, Linked Local Learning ו-CrossProductActionRequest contracts ללא פתיחת Build.
להוסיף acceptance tests ל-host neutrality, coordinator outage, specialty-only mode, excluded-product data, split-brain session, permission mismatch, mapping conflict, disagreement, disconnect/reconnect, evidence deletion ו-no-prompt-instruction-portability.
Core E, A–K, F, G ו-Core L ownership אינם משתנים. אין Core נוסף ואין Shared Truth Service.


20. שינויים נדרשים ב-Campaigner
להוסיף D-44 Interface Annex אדיטיבי; אין Core 14 ואין Advisor שלישי.
Advisor נשאר relationship/professional synthesis המקומי; Director נשאר Decision Frame; Context נשאר local truth; Knowledge/Evidence נשאר epistemic status; Metrics מפרש measurement; Learning מנהל candidate lifecycle; Meta/Integration מחזיק capability/mapping/health; Experience מציג; EO מבצע רק authorized local intent.
להרחיב Semantic Handoff/Return עקרונית ל-producer/owner/scope/freshness/uncertainty/disclosure/correlation fields ול-SpecialtyConsultRequest/SpecialistPosition.
להוסיף Marketing Intent→Seller Context, Leader realization/outcome projection, Customer Voice evidence candidate, Decision/Learning refs, source/disagreement UX ו-interface health metrics.
CrossProductActionRequest נשאר candidate מאוחר. אין permission portability, direct write, universal KPI או automatic learning promotion.
כל שינוי בקורפוס Campainer דורש דיון והכרעת Product Owner נפרדים; מסמך זה אינו מטמיע אותם.


21. שאלות שנותרו להכרעת בעל המוצר
OD-D44-01 — Default mode. המלצה: Unified הוא opt-in ברמת Business connection, עם override לכל session/turn; אינו forced default.
OD-D44-02 — Shared transcript retention. המלצה: אין transcript משותף מתמשך כברירת מחדל; נשמר Session minimum זמני, וכל מוצר שומר רק summary/decision/learning מקומי כדין.
OD-D44-03 — Evidence deletion effect. המלצה: learning שאיבד provenance נדרש מסומן EVIDENCE_UNAVAILABLE ומחויב demotion/reopen/delete לפי materiality ו-policy; אין להציגו כ-current supported learning.
OD-D44-04 — First cross-product action classes. המלצה: לא ב-T1; להכריע רק לאחר Action Catalog, Decision Classes, dual authorization, Direct-UI parity, idempotency, readback and recovery.
אין Owner Decision נוסף הנדרש כדי לבחור ב-Pattern E ברמת הארכיטקטורה. ההכרעות לעיל נדרשות לפני Retention/Action Build.


22. הכרעה מקצועית מפורשת
כן — D-44 הוא כיוון המוצר הנכון: שיחה אחת, שתי התמחויות, עצמאות פדרטיבית ולמידה נשמרת כדין.
לא — לא נכון לממש אותו כ-One Shared Business Memory, shared durable session, host Advisor או persistent neutral God Advisor.
המנגנון העדיף הוא Pattern E: coordinator neutral/ephemeral, product-owned specialists, first-class but temporary session, source-owned federated knowledge, linked local decisions/learning and receiver-owned action authority.
זהו שינוי ארכיטקטוני מהותי למנגנון, לא שינוי בכוונת בעל המוצר.


23. D44-IMPL-01..18 — DECISION MATRIX
המטריצה הקובעת מופיעה להלן.
ID
	נושא
	Verdict
	המלצה קובעת
	D44-IMPL-01
	דפוס המימוש הכולל
	RECOMMEND-WITH-MODIFICATION
	Pattern E — Ephemeral Federated Advisory Coordinator: לשמר את דוקטרינת D‑44 ולהחליף את העמימות סביב זיכרון משותף במנגנון פדרטיבי מפורש.
	D44-IMPL-02
	Advisor Orchestrator
	RECOMMEND-WITH-MODIFICATION
	כן, אך רק כ־Coordinator ניטרלי וזמני; ללא בעלות על אמת, זיכרון, הרשאות, החלטות או פעולות.
	D44-IMPL-03
	Shared Conversation / Session Context
	RECOMMEND-WITH-MODIFICATION
	כן, כאובייקט AdvisorySessionContext זמני, מינימלי וניתן לניתוק; לא כזיכרון עסקי משותף מתמשך.
	D44-IMPL-04
	העברת ידע בין המוצרים
	RECOMMEND
	שאילתה חיה + Projection מנוהל + Source Ref + Handoff Snapshot; אירועים נבחרים רק בשלב מאוחר, ללא Mirror כללי.
	D44-IMPL-05
	Joint Recommendation synthesis
	RECOMMEND
	SpecialistPositions מובנים → מטריצת הסכמות/התנגשויות → JointRecommendationEnvelope מקושר למקורות ולא־סמכותי.
	D44-IMPL-06
	טיפול במחלוקת בין היועצים
	RECOMMEND
	לשמר את שתי העמדות; לסנתז רק כשיש בסיס; אחרת להציג את הקונפליקט, החסר ובעל ההכרעה.
	D44-IMPL-07
	מצבי Unified / Specialty-only
	RECOMMEND
	UNIFIED / CAMPAIGNER_ONLY / LEADER_ONLY / SEPARATE_VIEWS / EXCLUDE_PRODUCT_DATA, עם אכיפה בכל תור.
	D44-IMPL-08
	זהות והפניות חוצות־מוצרים
	RECOMMEND
	Mapping Assertions מנוהלי־גרסה ו־CrossProductRef; ללא Global Merge; קונפליקט ו־staleness נשארים גלויים.
	D44-IMPL-09
	CrossProductActionRequest
	RECOMMEND-WITH-MODIFICATION
	Intent/ראיית החלטה בלבד; המוצר המקבל מאשר מחדש, יוצר Operation מקומי ומחזיר lifecycle מאומת. לא ב־T1.
	D44-IMPL-10
	Shared Decision Memory
	REJECT-AND-REPLACE
	רשומות Decision סמכותיות ומקומיות המקושרות באמצעות DecisionCorrelationId; אין אובייקט החלטה משותף ובר־שינוי.
	D44-IMPL-11
	Shared / linked Learning Case
	REJECT-AND-REPLACE
	Learning Cases מקומיים בכל מוצר + FederatedLearningLink; אין בעל זיכרון ניטרלי ואין קידום למידה משותף.
	D44-IMPL-12
	למידה נשמרת לאחר ניתוק
	RECOMMEND-WITH-MODIFICATION
	רשומה מקומית נגזרת ומוגבלת־מטרה עם מקור, זמן, scope, freshness, מגבלות וחובת revalidation; לעולם לא עובדה חיה עדכנית.
	D44-IMPL-13
	גבול Raw Evidence
	RECOMMEND
	הראיות הגולמיות נשלטות בידי המקור; בניתוק נחסמות/נמחקות מטמונות מקבלות, ונשמר רק תקציר provenance מותר.
	D44-IMPL-14
	כשל ו־Degraded Mode
	RECOMMEND
	כל Advisor מקומי ממשיך; Unified מסומן PARTIAL/UNAVAILABLE; חסר נשאר Unknown ולא מיוצרת שלמות מדומה.
	D44-IMPL-15
	T1 / T1.1 / Later
	RECOMMEND-WITH-MODIFICATION
	T1: אבחון מאוחד צר ו־read-only; T1.1: רציפות בין משטחים + החלטות/למידה מקושרות; פעולות, אירועים ושימור רחב מאוחר יותר.
	D44-IMPL-16
	שינויים נדרשים ב־Leader
	RECOMMEND-WITH-MODIFICATION
	למסגר Memory כפדרציה; להוסיף Coordinator, Session, Gateway, Position, Mapping, Linked Memory ו־Action contracts ובדיקות רגרסיה; ללא Core חדש.
	D44-IMPL-17
	שינויים נדרשים ב־Campaigner
	RECOMMEND-WITH-MODIFICATION
	להוסיף D‑44 Interface Annex על גבי הליבות והחוזים הקיימים; ללא Core 14, ללא Advisor שלישי וללא כתיבה ישירה.
	D44-IMPL-18
	השלכות Build ושערים
	RECOMMEND
	אין Build כעת; נדרשים reconciliation סמנטי, הכרעות בעל מוצר על retention/actions, אבטחה/פרטיות בממשק, dual authorization וביקורת adversarial.
	D44-IMPL-19
	Durable Federated Learning Exchange
	RECOMMEND — OWNER APPROVED
	כן — כרכיב מתמשך נפרד משכבת השיחה: Signals/Outcome/Marketing-Origin/User-Specific/Cohort projections, קידום מקומי עצמאי, provenance/freshness/consent/deletion ו־revalidation לאחר ניתוק.
	

24. OWNER-APPROVED REFINEMENT — DURABLE FEDERATED LEARNING EXCHANGE


Approval basis: בעל המוצר אישר ביום 2026-08-23 להוסיף את מנגנון הלמידה הפדרטיבי המתמשך להמלצת Pattern E. חידוד זה הוא Additive Architecture Refinement ואינו מבטל את יתר ההמלצה.


24.1 הפער שהחידוד סוגר


Coordinator זמני בלבד מגן על עצמאות המוצרים, אך אם לא קיים נתיב למידה מתמשך הוא עלול לאבד היסקים חוצי־מוצרים לאחר סיום השיחה. לכן שכבת השיחה נשארת זמנית, ולצידה מוקמת שכבת Learning Exchange מתמשכת ונפרדת.


24.2 הנוסחה הארכיטקטונית המעודכנת


UNIFIED ADVISORY EXPERIENCE
+
EPHEMERAL FEDERATED ADVISORY COORDINATOR
+
DURABLE FEDERATED LEARNING EXCHANGE
+
PRODUCT-LOCAL TRUTH, DECISION, INFERENCE AND LEARNING OWNERSHIP


24.3 ארבעת מישורי הבעלות


א. Conversation and Coordination Plane — זמני; מנתב, אוסף עמדות ומרכיב תשובה, ללא בעלות על למידה.


ב. Product Truth and Evidence Plane — מקומי; כל מוצר מחזיק את הראיות, האמת, ההרשאות וה־raw evidence שלו.


ג. Federated Learning Exchange Plane — מתמשך; מעביר אותות למידה והקרנות מנוהלות, אך אינו מקדם למידה ואינו מקור אמת.


ד. Product-Local Inference and Promotion Plane — מקומי; כל מוצר מפרש, בודק, מקדם, דוחה, מתקן ומוריד בדרגה את הלמידה בעצמו.


24.4 למידה ספציפית למשתמש


כאשר Campaigner ו־Leader מזהים קשר משותף, כל מוצר יוצר Learning Candidate מקומי התואם למומחיותו. לדוגמה: Campaigner יכול ללמוד על איכות קהל/קריאייטיב בתנאי טיפול מסוים; Leader יכול ללמוד על SLA ודפוס טיפול לפי מקור שיווקי. שתי הלמידות מקושרות ב־FederatedLearningLink, אך אינן מתמזגות לאובייקט למידה משותף.


כל UserSpecificLearningSignal חייב לכלול לפחות: source product, source object/ref, business/user scope, campaign/sales scope, observed_at, emitted_at, freshness, confidence, evidence class, limitations, purpose, consent/retention class, revocation state ו־revalidation rule.


24.5 היסק רוחבי


כל מוצר ממשיך להחזיק מנוע למידה רוחבי עצמאי. מידע חוצה־מוצרים יכול להיכנס אליו רק כ־CohortLearningProjection מנורמל, מצומצם ומותר, עם cohort definition, aggregation window, minimum cohort/privacy threshold, source lineage, measurement limitations ו־confidence.


CohortLearningProjection הוא Prior מקצועי לבדיקה מקומית; הוא אינו אמת של עסק מסוים ואינו מאפשר קידום אוטומטי ללא שערי הלמידה של המוצר המקבל.


24.6 חוזי ההחלפה המחייבים


1. OutcomeProjection — תוצאה מאוחרת מנוהלת ללא פתיחת תיק המקור המלא.


2. MarketingOriginProjection — מקור שיווקי, הצעה, קהל, Creative Job ומגבלות Attribution.


3. UserSpecificLearningSignal — אות למידה מוגבל לעסק/משתמש/קמפיין/תהליך מוגדר.


4. CohortLearningProjection — אות רוחבי מנורמל ומוגן־פרטיות.


5. FederatedLearningLink — קישור בין Learning Cases מקומיים, כולל lineage ומצב תלות.


6. LearningCorrectionOrRevocationNotice — תיקון, ביטול, מחיקת Evidence או שינוי materiality המחייבים בחינה מחדש אצל המקבל.


24.7 כללי אי־זיהום וסמכות


- Signal received ≠ Local Learning Candidate ≠ Promoted Learning ≠ Product Truth.


- אין העברת סמכות קידום, הרשאה או פעולה עם אות הלמידה.


- המקבל חייב לבצע Independent Local Reconciliation לפני שימוש אופרטיבי.


- Unknown, missing, stale, disputed ו־revoked נשמרים במפורש ואינם מומרים ל־0 או Fail.


- אין Generic Mirror, אין מאגר Raw Evidence משותף ואין מודל רוחבי מרכזי המחליף את שני המודלים המקומיים.


- כל שימוש חייב לעמוד ב־purpose limitation, consent, privacy, retention, deletion ו־minimum-necessary disclosure.


24.8 ניתוק בין המוצרים


בעת ניתוק נפסקת גישה חיה. כל מוצר רשאי לשמור רק Snapshot או Derived Learning שהותרו כדין. תלות במקור האחר מסומנת SOURCE_DISCONNECTED; freshness ממשיך להתיישן; לפי materiality נדרש revalidation, demotion, reopen או delete. אין להציג למידה תלויה כממצא חי ועדכני לאחר שהמקור אינו ניתן לאימות.


24.9 השפעה על החלטת D-44


החידוד אינו יוצר Shared Truth Store, Advisor שלישי, Shared Mutable Decision, Shared Learning Owner או סמכות פעולה משותפת. הוא מבטיח שחוויית ייעוץ מאוחדת ועצמאות ארכיטקטונית אינן באות על חשבון הלמידה האישית או הרוחבית של אף אחד מהמוצרים.


24.10 השלכות תכנון


Leader נדרש להוסיף את Federated Learning Exchange, חוזי האותות, קישורי הלמידה, כללי הניתוק ובדיקות אי־זיהום למסמכי D-44 הרלוונטיים. Campaigner נדרש להוסיף Interface Annex מקביל על גבי ליבות Knowledge/Evidence, Context, Metrics, Learning, Advisor וה־Decision/Handoff Contracts הקיימים. אין צורך ב־Core חדש באף מוצר.


24.11 Verdict מעודכן


RECOMMEND-WITH-MATERIAL-ARCHITECTURAL-MODIFICATION — OWNER-APPROVED REFINEMENT INCORPORATED.


הארכיטקטורה המעודכנת שומרת על למידה עצמאית ספציפית ורוחבית בכל מוצר, ומאפשרת למידה חוצת־מוצרים מתמשכת ללא יצירת בעל אמת, בעל למידה או בעל סמכות שלישי.


STATUS: READY_FOR_D44_DESIGN_RECONCILIATION
