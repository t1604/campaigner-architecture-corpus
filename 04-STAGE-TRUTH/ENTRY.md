---
mirror_role: "Base44 read/reference mirror"
canonical_source: "Google Drive"
source_title: "CAMPAINER-STAGE-TRUTH-ENTRY-001 — v1.0 — Branch Selection"
source_drive_id: "1YZNfZ0AWgPMBP1o5B1B4fQAqYjD5Co8WowxqXqH7akM"
source_modified_at: "2026-08-18T17:33:35.687Z"
corpus_status: "current"
category: "stage-truth"
---

> MIRROR NOTICE: This file is a controlled copy for Base44. Google Drive remains the canonical source. Do not infer implementation, deployment, runtime, or release authority from repository presence.

## Canonical source body

CAMPAINER-STAGE-TRUTH-ENTRY-001 — v1.0
ENTRY — Branch Selection


STATUS: OWNER-APPROVED ACTIVE CANONICAL STAGE TRUTH — PRINCIPLE / FLOW
SCHEMA AUTHORITY: NO
BUILD AUTHORITY: NO
RUNTIME AUTHORITY: NO
META WRITE / LAUNCH AUTHORITY: NO
PRODUCT OWNER AUTHORITY: PRESERVED
DERIVES FROM: CAMPAINER-STAGE-TRUTH-MASTER-001 v1.0 + CAMPAINER-FLOW-CORE-APPLICABILITY-MATRIX-001 v1.0 + CAMPAINER-CANONICAL-PRODUCT-FLOW-001 v1.0 + CAMPAINER-ONE-TIME-CAMPAIGN-FLOW-001 v1.0


Stage Purpose
לאפשר כניסה ברורה למסלול העסקי/המתמשך או למסלול החד־פעמי, בלי סיווג נסתר ובלי מסך בחירת מסלול כללי שחוסם את הכניסה.


Entry Truth / Preconditions
המשתמש הגיע לנקודת ההתחלה; אם קיים Context קודם, ידוע לפחות מי המשתמש ומהו ה־Business הפעיל כאשר רלוונטי.


Decision / Understanding Target
איזה ענף המשתמש בוחר להתחיל עכשיו.


Primary / Required / Conditional Cores
Primary: EXP interaction + ADV continuity. Required: ADV, EXP. Conditional: CTX; K/E רק להסבר מהותי.


Minimum-Sufficient Context Projection
זהות משתמש ו־Business scope בלבד אם כבר ידועים ושימושיים.


Knowledge Need / Activation
ללא Knowledge activation כברירת מחדל.


Inputs
User intent + existing scoped context if available.


Outputs / Work Objects
Branch Choice + active scope reference.


Authority Gates
בחירת ענף אינה Execution Authority ואינה הסכמה לפעולה חיה.


Evidence Writes
בחירת ענף; scope פעיל אם קיים; state transition.


Semantic Handoff Out
ל־A1 או B1 עם branch identity ו־minimum context.


Semantic Return
ל־ADV כאשר מתברר שהבחירה אינה מתאימה מקצועית; אין המרה שקטה לענף אחר.


Exit Truth
הענף ברור והמשתמש יודע לאיזה מסע הוא נכנס.


Reopen Conditions
המשתמש משנה בחירה או שהצורך מתברר כ־ongoing/one-time באופן שדורש בחירה מחדש.


Pilot Human Review
לא נדרשת ביקורת מקצועית מהותית רק לבחירת הענף; כל שינוי כפוי אסור.


Stage-specific Invariant
Branch choice שייך למשתמש; Campainer יכולה להציע מעבר אך לא לבצע אותו ללא בחירה מפורשת.


LINEAGE: This artifact is a faithful split of the corresponding unit in CAMPAINER-STAGE-TRUTH-MASTER-001 v1.0. It creates no new ownership, schema, build or runtime authority.
END — CAMPAINER-STAGE-TRUTH-ENTRY-001 — v1.0
