# DataHub Agent — Project Spec Compiler Employer Proof

This repository externalizes a mechanically validated employer-facing case study produced with the **Project Spec Compiler**.

## What this proves

Two real target specifications were compiled through the same deterministic contract:

1. **Snoonu (Qatar)** — agentic SOP release gate for operational workflows.
2. **Mintlify (YC)** — deal-to-engineering specification gate aligned to Solutions Engineering / pre-sales work.

Execution path:

`target workflow -> 8 canonical spec segments -> compiled bundle -> validator -> deterministic report -> hostile falsification test`

Clean portfolio validation completed with **0 errors / 0 warnings**. A hostile mutation then introduced source/bundle drift and a fabricated implementation status; the validator rejected both and exited non-zero.

## Start here

- `index.html` — standalone employer-facing static demo; deploy this repo directly to Netlify as a static site.
- `case-study.md` — employer-readable case study.
- `specifications/` — the two eight-section source specifications plus compiled bundles and portfolio controls.
- `evidence/` — clean validation, deterministic report, and hostile-test receipts.
- `process/` — the exact mechanical process and evidence-state rules.
- `reproduction/` — scripts and commands for replaying the pipeline.

## Evidence state

**Proven by execution:** both projects bundle; portfolio validation is clean; hostile source/bundle drift and unsupported status are rejected.

**Documented but not externally proven:** the proposed Snoonu and Mintlify workflows are public-evidence demonstrations, not claims of deployment inside either company.

## Deployment

This repository intentionally has no application backend. `index.html` is the deployable presentation layer; the rest of the repository is inspectable technical proof and reproducibility material.
