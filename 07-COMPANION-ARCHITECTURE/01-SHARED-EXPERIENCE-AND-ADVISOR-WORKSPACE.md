---
mirror_role: "Base44 read/reference mirror"
canonical_source: "Google Drive"
source_title: "CAMPAINER-SHARED-EXPERIENCE-AND-ADVISOR-WORKSPACE-ARCHITECTURE-001 — OWNER-APPROVED CANONICAL ADDITIVE CLARIFICATION"
source_drive_id: "1VDtgvqECgPvY2jj2huUD5gAMgF7f6o0PPf7neWuGt6U"
source_modified_at: "2026-08-23T09:03:22.225Z"
corpus_status: "current"
category: "companion"
---

> MIRROR NOTICE: This file is a controlled copy for Base44. Google Drive remains the canonical source. Do not infer implementation, deployment, runtime, or release authority from repository presence.

## Canonical source body

CAMPAINER — SHARED EXPERIENCE AND ADVISOR WORKSPACE ARCHITECTURE
OWNER-APPROVED CANONICAL ADDITIVE CLARIFICATION — 001


STATUS: ACTIVE CANONICAL ADDITIVE ARCHITECTURE / READY FOR OWNER PRE-BUILD PRESENTATION
CORE CREATION: NO
BUILD / RUNTIME / SCHEMA / MIGRATION / META WRITE / LAUNCH AUTHORITY: NO


0. מעמד וסמכות
מסמך זה מקבע את ארכיטקטורת החוויה המשותפת, מעטפת היישום האדפטיבית, נוכחות היועץ ומסך העבודה הייעודי של Campaigner. הוא תוספת קנונית למקורות הקיימים ואינו מחליף את Product Truth, את 13 הליבות, את ה־Flow או את Stage Truth.
המסמך אינו יוצר ליבה חדשה, Advisor שלישי, Shared Truth Store או תלות Runtime בין Campaigner ל־Leader. הוא מגדיר כיצד סמנטיקה קיימת מוצגת ונשמרת לאורך הממשק.


1. הכרעת הארכיטקטורה
הפתרון הוא FEDERATED SHARED EXPERIENCE DESIGN SYSTEM + DUAL-SIDE ADAPTIVE APPLICATION SHELL + UNIVERSAL ADVISOR ENTRY + CONTEXTUAL EXPAND-IN-PLACE + DEDICATED ADVISOR WORKSPACE.
Experience / Interface מחזיקה את ההצגה, הניווט והאינטראקציה. Advisor מחזיק synthesis, explanation, recommendation והקשר המקצועי עם המשתמש. Context מחזיק אמת מקומית ו־Minimum-Sufficient Context Projection. Director מחזיק את Decision Frame. ליבות המקצוע והסמכות נשארות בעלות המשמעות המקומית שלהן.
המשתמש חווה סביבת עבודה אחת עם Advisor אחד רציף; המערכת אינה מציגה לו מעבר בין סוכנים פנימיים.


2. שפת העיצוב המשותפת
Campaigner ו־Leader משתמשים בשפת בסיס משותפת אך במימוש מקומי, גרסאי וניתן להפרדה.
הכיוון החזותי המחייב הוא משטח לבן ודומיננטי, קווי הפרדה עדינים, צללים מינימליים, טקסט כהה, כחול בהיר לבחירה ולפעולה, צבעים סמנטיים עקביים, כרטיסים נקיים, פינות מעוגלות וריווח נדיב.
החוויה צריכה להרגיש מקצועית, שקטה וברורה ולא “AI נוצץ”. אין לקבע טקסט קטן, ניגודיות חלשה, צפיפות כפתורים, יחס רוחב קשיח או צבע שאין לו משמעות קבועה.
הבדלי המוצר מוגבלים ל־Logo, שם מוצר, ניווט מקומי, תג מומחיות, איקונוגרפיה תחומית ותווית בעלות על Data/Object/Action. אסור ליצור זהות צבעונית נפרדת שפוגעת בתחושת מערכת משותפת.


3. מעטפת היישום האדפטיבית
3.1 פאנל ניווט מוצר ימני
ב־RTL פאנל המוצר נמצא בצד ימין וכולל שלושה מצבים: EXPANDED עם אייקונים ושמות; COMPACT עם אייקונים, tooltips ו־active state; HIDDEN/DRAWER שאינו תופס רוחב ונפתח מעל המסך.
המשתמש יכול לפתוח, לצמצם ולסגור את הפאנל. ההעדפה נשמרת לפי משתמש, מכשיר וסביבת עבודה. צמצום זמני בגלל רוחב מסך אינו דורס את העדפת המשתמש.


3.2 פאנל Advisor שמאלי
פאנל היועץ כולל CLOSED, COMPACT ENTRY, CONTEXTUAL OPEN, RESIZED ו־DEDICATED WORKSPACE MODE.
המשתמש יכול לפתוח, לסגור, לצמצם ולשנות רוחב. פעולות תצוגה אלה אינן משנות Product Truth, Scope, בחירה, טיוטה, מסננים, Permission או Authority.


3.3 משטח עבודה מרכזי
משטח העבודה מקבל אוטומטית את כל השטח שהתפנה. אין לשמור רוחב ריק לפאנל סגור.
במסך רחב ניתן להציג את שני הפאנלים. במסך בינוני ניווט המוצר רשאי לעבור זמנית ל־COMPACT. במסך קטן פאנלים נפתחים כ־Drawer או Full-screen ולא נכפים שלושה טורים.


4. שני מצבי Advisor
4.1 Contextual Expand-in-Place
פתיחת היועץ מתוך מסך פעיל אינה מנווטת למסך אחר. היא מכווצת את המשטח באופן רספונסיבי ושומרת, ככל שמותר ורלוונטי, Business, Offering, Campaign, active ObjectRef/VersionRef, filters, selection, draft, work-in-progress, evidence refs ושאלות פתוחות.
המצב ניתן לשינוי רוחב, לצמצום ולסגירה ואינו מחויב ליחס שליש–שני־שלישים.


4.2 Dedicated Advisor Workspace
קיים מסך ייעודי בשם CAMPAINER — DEDICATED ADVISOR WORKSPACE.
נקודת הפתיחה היא בקירוב שליש Advisor ושני־שלישים Contextual Work Surface, לאחר הפחתת רוחב ניווט המוצר. היחס ניתן לשינוי, לצמצום ולסגירה ואינו Pixel Mandate.
שליש היועץ מציג שיחה רציפה, Scope פעיל, מה ידוע ומה חסר, Evidence/Source/Freshness, hypotheses/contradictions, recommendations, החלטות הממתינות למשתמש, proposed actions ו־execution/readback state.
שני־שלישי העבודה מציגים לפי ההקשר: אבחון קצר, מפת עסק ו־Offering, מבנה פרסום אפשרי ונוכחי, קמפיין מסוים, Strategy Draft, Segment/Persona/Audience/Golden Lead, Brand Assets, Creative Studio, Meta settings, Media/Budget, readiness, metrics, lead quality, CRM/outcome projections, Evidence/Learning, טבלאות, השוואות וגרפים.
המשתמש יכול לערוך ישירות במשטח או לבקש מן היועץ להציע או להפעיל אותה יכולת דרך שרשרת הסמכות הקיימת.


5. Universal Advisor Entry וניווט כפול
בכל משטח מהותי קיימת כניסה עקבית ליועץ, אך היועץ אינו Gatekeeper.
DIRECT NAVIGATION ו־ADVISOR NAVIGATION מובילים לאותם Objects, לאותה אמת ולאותו Scope. המשתמש יכול לעבוד ללא היועץ, לפתוח אותו לצד המסך, להמשיך להשתמש בממשק הישיר בזמן השיחה, לעבור למסך הייעודי ולחזור לאובייקט המקורי בלי לאבד עבודה.
כל אובייקט משמעותי מאפשר “שאל את היועץ על זה” באמצעות ScopeRef, ObjectRef ו־VersionRef מדויקים. כאשר ההקשר עמום היועץ שואל ואינו מנחש.


6. רציפות והעברת מצב
מעבר בין Contextual, Dedicated והמסך המקורי שומר ככל שמותר ורלוונטי: active question; Business/Offering/Campaign scope; refs and versions; filters/windows/cohorts; evidence inspected; hypotheses and contradictions; unresolved questions; recommendations; drafts/work artifacts; Decision/Learning refs.
המעבר עצמו אינו יוצר אמת, החלטה או סמכות.
שינוי Business שומר את רציפות השיחה אך מחליף projection באופן מפורש ואינו מערבב Assets, Economics, Customers, Strategy או Truth בין עסקים.


7. דקדוק חזותי של אמת וסמכות
הממשק מבדיל באמצעות label, icon וטקסט — ולא באמצעות צבע בלבד — בין Fact/Observation, Unknown/Missing, Interpretation/Hypothesis, Recommendation, Owner Decision Required, Proposed Action, Authorized Action, In Progress, Verified Result ו־Failed/Partial/Recovery Required.
Recommendation אינה Approval. Approval אינה Authorization. Conversation אינה Execution Authority. View Action אינה Business State Change.
System Status, Receipt ו־Error אינם מוצגים כעמדה מקצועית של Advisor.


8. D-44 ומצב משולב עם Leader
כאשר החיבור מורשה, המשתמש יכול לחוות שיחה ייעוצית אחת רציפה, אך עמדות שני המומחים מיוחסות במפורש.
כל Projection מציג מקור, זמן, scope, freshness ובעלות מוצר על Data/Object/Action. Projection אינו הופך ל־Truth מקומי רק משום שהוצג.
פעולה חוצת־מוצרים נשארת Intent עד לאישור מחדש במוצר המבצע. אין Advisor שלישי ואין Shared Truth Store.
כל מוצר שומר Truth, Permission, Decision, Action, Runtime ו־Learning ownership משלו. כל מוצר יכול להמשיך עם גרסה מקומית של שפת העיצוב ועם למידה שנשמרה כדין לאחר ניתוק, בלי גישה חיה למוצר האחר.


9. מפת מסכים חוצת Flow
מעטפת היישום והכניסה ליועץ חלות על כל המשטחים המהותיים בכל שלבי A1–A11 ובכל ענף B1–B9.
ב־Intake ובאבחון המשטח מציג שאלות אדפטיביות, מצב השלמה והכוונה לחומר חסר.
ב־Strategy הוא מציג מפת עסק, מבנה פרסום, חלופות, tradeoffs והחלטות.
ב־Studio הוא מציג Creative Job, Assets, וריאציות, provenance, rights, status ו־Decision Cards.
ב־Readiness/Approval/Authorization הוא מציג הפרדה גלויה בין Recommendation, Choice, Approval, Authorization, Execution ו־Verified Readback.
ב־Managed Campaign הוא מציג מצב קמפיין, חריגים, פעולות מוצעות, מה דורש תשומת לב ומה מטופל פנימית.
ב־Measurement/Learning הוא מציג metrics, maturity, unknowns, attribution/incrementality boundaries, learning candidates ו־next decision.


10. רכיבי UX קנוניים שנוספו
AdaptiveApplicationShell.
RightProductNavigationPanel.
AdvisorPanel.
CentralContextualWorkSurface.
UniversalAdvisorEntry.
AskAdvisorAboutThis.
DedicatedAdvisorWorkspace.
AdvisorConversationSurface.
ScopeAndProvenanceHeader.
KnownMissingContradictionPanel.
RecommendationAndDecisionQueue.
ProposedActionAndReadbackPanel.
DecisionCard / ApprovalSurface / AuthorizationSurface.
SystemStatusSurface.
ContextContinuityEnvelope.
ResponsivePanelState.
SharedDesignTokensLocalVersion.
ProductAndAuthorityAttribution.
רכיבים אלה הם משפחת חוזי UX ברמת Architecture; הם אינם Schema, API או implementation component מחייב עד Build authorization.


11. Acceptance
CAM-UX-01 PASS — כניסה ליועץ בכל משטח מהותי.
CAM-UX-02 PASS — הממשק הישיר שמיש ללא Advisor.
CAM-UX-03 PASS — פתיחה הקשרית שומרת scope, selection, filters ו־work-in-progress.
CAM-UX-04 PASS — Contextual ו־Dedicated הם מצבים נפרדים.
CAM-UX-05 PASS — סביבת Dedicated מתחילה בקירוב 1/3 + 2/3 וניתנת לשינוי.
CAM-UX-06 PASS — ניווט ימני נפתח, מצטמצם ונסגר.
CAM-UX-07 PASS — Advisor נסגר, מצטמצם ומשנה רוחב עצמאית.
CAM-UX-08 PASS — משטח העבודה עושה reflow בלי אובדן מצב.
CAM-UX-09 PASS — רציפות שיחה, context וטיוטה נשמרת לפי הרשאה.
CAM-UX-10 PASS — Advisor ו־Direct UI משתמשים באותה שרשרת Decision/Action.
CAM-UX-11 PASS — דקדוק חזותי מבדיל אמת, המלצה, החלטה, פעולה ותוצאה.
CAM-UX-12 PASS — Product/Authority/Source/Freshness גלויים במצב D-44.
CAM-UX-13 PASS — אין כפיית שלושה טורים במסך צר.
CAM-UX-14 PASS — לכל מוצר גרסה מקומית של שפת העיצוב.
CAM-UX-15 PASS — כיוון העיצוב הלבן נשמר עם ניגודיות וטיפוגרפיה קריאות.


12. השפעת ההטמעה על הקורפוס
Final Core Architecture: תוספת Cross-Cutting Experience Architecture; אין שינוי במספר הליבות או בבעלותן.
Product Truth and Core Architecture Package: המסמך נוסף כמקור קנוני פעיל.
Canonical Product Flow: המעטפת והיועץ מוגדרים כ־UX overlay חוצה־Stages ולא כ־Stage חדש.
Flow Core Applicability Matrix: Experience ו־Advisor מקבלים חובת projection חוצת־Flow; Context/Director תומכים לפי Minimum-Sufficient Projection.
Advisor Core: רציפות הזהות, universal entry, dual navigation ושני מצבי העבודה מקודמים קנונית.
Experience / Interface: shell, panel states, workspace, responsive contract ודקדוק סמכות מקודמים קנונית.
Stage Truth Index: כל A1–A11 ו־B1–B9 יורשים את overlay החווייתי בלי לשכתב כל Stage.
Decision/Handoff Contracts: ContextContinuityEnvelope ו־AdvisorScreenProjection הם חוזים תוספתיים; הם אינם Execution Authority.
Multi-Business, Brand, Creative, Meta, Metrics, Learning ו־Director: אין שינוי בבעלות או באמת; הם מוצגים דרך projections קיימים.
Build Packages: נדרשת propagation עתידית ל־BP-00, BP-01, BP-02–BP-07, BP-08, BP-09, BP-10, BP-11 ו־BP-12. המסמך אינו מתחיל Build.


13. מועמדי חיבור ופרסום שאינם מקודמים במסמך זה
Meta full lifecycle, Google Search, Unified Lead Intake Gateway, Leader/CRM sync, WhatsApp Business, lightweight campaign destinations, calendar/email, organic publishing, telephony, webhooks/API ו־integration recovery נרשמו כהמלצות מקצועיות לדיון נפרד.
אין לראות בהם Product Truth או Build Scope מכוח מסמך זה.


14. מקורות סמכות
Owner-approved Dispatch: 1wMaBK_9zh4U79rbWJEqDYbNGvrsHC6ECvlOV8C8p8R8.
Final Core Architecture: 1uE7OGLVhvKSFHF2BRr5KNBvAds2_AoN4v_PQtxGOnEY.
Product Truth and Core Architecture Package: 1vmronvhIbM1PbDWKp2EsNpqWSfEyE9ALDPWPLokTZYI.
Canonical Product Flow: 1Mcw0IKAYsOHuSSlHagzbQjBmzbf0NTYWxv-HIpaMOPY.
Flow Core Applicability Matrix: 1cta7iyqAeWhBIxM5nnPkSSN6kgOKnwVKF3woRLzQTs8.
Advisor Core: 1KAwg8fHnINs9TgRCqFbBtml6YNP2Bj9kchTx5MnWpLs.
Experience / Interface Core: 1lGjOB641Gdv3ao4cSKUoV0-tr5nl4YXS2g-qeNv6WWg.
Stage Truth Index: 14Apb8p4K2LX6Q1T2gfoAgDXAIjRF6mZaELXpv7MvfxQ.
Persistent Advisor Workspace candidate: 1y5YTgXuNkOPz0jKY5c-S9MpS_vWbomlY9U0lm-tFAFU.
Visual reference: owner-supplied Leader screen; direction only, not pixel specification.


END — CAMPAINER-SHARED-EXPERIENCE-AND-ADVISOR-WORKSPACE-ARCHITECTURE-001
