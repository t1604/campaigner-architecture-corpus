# Base44 Reading Instructions

Use this repository as Campainer's controlled architecture and build-context corpus.

## Start here

Read `README.md`, then follow its required reading order. Before using any build package, read both:

- `06-BUILD-PACKAGES/00-CURRENT-ARCHITECTURE-ALIGNMENT.md`
- `06-BUILD-PACKAGES/01-CURRENT-INDEX-v2.0.md`

## Interpretation protocol

For every implementation task:

1. Identify the applicable product flow and Stage Truth.
2. Identify the applicable horizontal cores.
3. Identify the governing contracts and current build package.
4. Check the companion architecture sources named by the current build index.
5. Produce a short source map listing every repository path relied upon.
6. Surface gaps or conflicts; do not fill them by inference.

## Authority boundary

This repository does not itself authorize building, deployment, production access, runtime mutation, releases, merges, or changes to canonical truth. Google Drive remains canonical.
