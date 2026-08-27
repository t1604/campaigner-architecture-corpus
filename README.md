# Campainer Architecture Corpus

Private, controlled read/reference mirror of Campainer's current architecture corpus for Base44.

## Canonical-source rule

Google Drive remains the canonical source of truth. This repository is a structured mirror for reading and implementation context. Editing a file here does **not** promote or amend the canonical architecture.

Only the current active documents selected by the canonical package, indexes, and alignment documents are included. Historical and superseded versions are intentionally excluded from the active corpus.

## Required reading order

1. `01-PACKAGE-HOME/`
2. `02-CORE-ARCHITECTURE/00-CONSTITUTION.md`
3. `02-CORE-ARCHITECTURE/01-PRODUCT-TRUTH-CORE.md`
4. Applicable horizontal cores in `02-CORE-ARCHITECTURE/`
5. `02-CORE-ARCHITECTURE/15-FINAL-CORE-ARCHITECTURE.md`
6. `03-FLOWS/`
7. `04-STAGE-TRUTH/`
8. `05-CONTRACTS/`
9. `06-BUILD-PACKAGES/00-CURRENT-ARCHITECTURE-ALIGNMENT.md`
10. `06-BUILD-PACKAGES/01-CURRENT-INDEX-v2.0.md`
11. Applicable current `BP-xx.md` files
12. Required promoted sources in `07-COMPANION-ARCHITECTURE/`

The governing derivation chain is:

`Constitution → Product Truth → applicable Domain Cores → Final Core Architecture → Canonical Product Flow → Stage Truth → Contracts / Decision Logic → Build → Test → Runtime Evidence`

## Base44 operating rules

- Treat this repository as read/reference input.
- Follow the precedence and applicability rules stated by the canonical documents.
- Do not silently invent missing requirements or resolve conflicts by guesswork.
- When producing implementation decisions, cite the repository file paths used.
- If a required source is absent, ambiguous, or contradictory, stop and request clarification.
- Repository presence grants no production deploy, runtime, release, merge, or authority escalation.
- Do not treat historical references mentioned inside a source as current unless the current index explicitly selects them.

## Contents

- 1 package-home document
- 16 core architecture documents
- 3 canonical flow documents
- 23 Stage Truth documents
- 18 contract documents
- 3 build governance/index documents
- 13 current build packages
- 4 required companion architecture documents

See `CORPUS-INDEX.md` for the complete file map and `CORPUS-MANIFEST.json` for machine-readable provenance.
