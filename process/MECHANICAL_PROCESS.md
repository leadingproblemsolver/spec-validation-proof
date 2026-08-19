# Mechanical Process Used

This documents the actual sequence used to turn the repository into employer-facing proof.

## Stage 0 — Inspect the repository contract

The repository was treated as executable infrastructure, not as a writing prompt. The compiler contract was inspected first:

- eight mandatory section names and segment filenames;
- five allowed implementation statuses;
- bundle assembly behavior;
- project and portfolio validation behavior;
- deterministic report generation;
- existing test expectations.

Decision rule: **do not invent an output format that bypasses the compiler.**

## Stage 1 — Select two targets with different workflows

Two targets were chosen to test transferability rather than superficial tailoring:

- **Snoonu:** operational / agentic SOP automation context in Qatar.
- **Mintlify:** YC technical discovery / Solutions Engineering context.

The target selection criterion was not brand prestige. It was whether a public workflow could be translated into a concrete engineering contract with measurable consequence and employer-readable ownership.

## Stage 2 — Map each target to the canonical eight-section contract

For each target, create all eight segment files with identical schema metadata.

Required discipline:

- separate observed/public facts from inferred design choices;
- use only canonical implementation statuses;
- mark the demonstration itself accurately rather than implying production deployment;
- define state, invariants, failure modes, recovery, metrics, and employer signal.

## Stage 3 — Generate the canonical bundles

Run the compiler `bundle` command for each project. This creates `project.bundle.yaml` from the segmented source files.

The bundle is derivative evidence. The segmented files remain the source of truth.

## Stage 4 — Validate the portfolio

Run portfolio validation against the demo specification root.

Clean expected result:

```json
[]
```

The validator checks, among other things:

- required portfolio control files;
- mandatory section order/content;
- registry uniqueness;
- repository-directory existence;
- project bundle/source equality;
- canonical status vocabulary;
- project ID and repository-name consistency;
- registry ID vs project identity.

## Stage 5 — Generate deterministic employer report

Run the report command after validation. The report summarizes the project ID, role, maturity, primary output, and validation counts.

This output is intentionally deterministic; the employer-facing prose sits on top of it rather than replacing it.

## Stage 6 — Hostile falsification test

Copy the Mintlify project and deliberately mutate it:

1. alter source after the bundle exists, creating source/bundle drift;
2. change a valid implementation status to an unsupported claim: `production_proven`.

Expected result: validator exits non-zero and reports both failures.

Observed result: exit code `1`; both errors were detected.

## Stage 7 — Externalize the proof

Package three observer layers:

- **operator/engineer:** segmented YAML + bundle + validator behavior;
- **hiring manager:** deterministic portfolio report + targeted case study;
- **fast reviewer:** standalone HTML employer demo.

The external-facing claim is therefore bounded by executable receipts.

## Stage 8 — Settle the evidence state

### What changed in reality?
Two distinct employer workflows now have compiler-valid engineering specifications and reproducible outputs.

### What evidence exists?
Clean validator receipt, deterministic report, two compiled bundles, hostile-test receipt, and employer-facing case study/demo.

### Whose behavior/access changed?
None yet. No company review or hiring-team response is claimed.

### Which assumption died?
That employer-facing project specifications must remain prose-only or trust-based. At least structural consistency and certain evidence-state violations can be mechanically rejected.

### Next irreversible/external transition
Send the relevant artifact to an actual Snoonu AI/operations owner and a Mintlify Solutions Engineering/hiring reviewer; collect corrections, rejection reasons, or access.
