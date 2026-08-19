# Project Spec Compiler — Targeted Employer Case Study

**Generated:** 2026-08-19 (Asia/Qatar)  
**Compiler:** `leadingproblemsolver/project-spec-compiler`  
**Target cases:** Snoonu (Qatar) + Mintlify (YC W22)  
**Evidence state:** public-evidence demonstration; no private company access or production deployment is claimed.

## Observable target state

Prove one differentiable capability that is directly inspectable by an employer:

> Take an ambiguous, consequence-bearing workflow; translate it into explicit engineering contracts; compile it from segmented source; reject source/status/registry drift; and expose the result as a reproducible handoff rather than a polished but unverifiable document.

Execution path:

`target workflow -> 8 canonical spec segments -> compiled bundle -> validator -> deterministic report -> hostile falsification test`

## Snoonu — Agentic SOP Release Gate

The wedge is deliberately not “build Snoonu an agent.” The harder control problem is deciding when an SOP-derived agent is allowed to act: source/version, authority, invariants, abstention, rollback, regional assumptions, evidence status, and release gates.

**Actor:** AI adoption / operations / engineering owner.  
**Trigger:** an SOP is automated or materially changes after automation exists.  
**Failure:** prose SOP, implementation behavior, approval authority, and edge-case handling diverge.  
**Target output:** a validated SOP-to-agent release contract.

Key invariants:

1. No autonomous side effect from an unvalidated specification.
2. Consequential customer/merchant/payment/logistics actions require explicit approval in the documented design.
3. Unknown/conflicting SOP instructions route to abstain/escalate rather than silent inference.
4. Canonical bundle must exactly equal segmented source.
5. Implementation claims must use the canonical five-state vocabulary.
6. Regional/vertical reuse requires policy/authority/data/recovery assumptions to be revalidated.

Differentiated employer signal: **ownership of the release contract around agentic AI where operational consequence begins.**

## Mintlify — Deal-to-Engineering Spec Gate

The wedge turns an enterprise ask into a validated engineering handoff before scope is treated as commercially committable or a POC is treated as proof.

**Actor:** Solutions Engineer working across buyer, AE, product, and engineering.  
**Trigger:** an enterprise prospect needs a non-canned migration, integration, auth, deployment, or workflow behavior.  
**Failure:** assumptions about integrations, security, acceptance criteria, fork risk, and effort remain implicit under deal pressure.  
**Target output:** a validated deal-to-engineering handoff contract.

Key invariants:

1. No customer ask becomes commercially committable until acceptance criteria and engineering assumptions are explicit.
2. A POC cannot upgrade a capability to `implemented` without reproducible evidence.
3. Fork risk is classified before custom work proceeds.
4. Security/auth/data-residency unknowns block final feasibility claims.
5. Changed requirements invalidate the previous bundle until recompilation and validation.

Role-to-proof mapping:

- deep technical discovery -> explicit actor/trigger/current-system/constraints/unknowns;
- requirements -> engineering specification -> eight-section compiled contract;
- custom POC -> smallest vertical slice around the highest-risk assumption;
- feasibility/risk -> explicit fork, security, maturity, and evidence gates;
- one-off -> reusable product capability -> pattern/repeatability logic.

## Mechanical compiler result

```text
Projects: 2

snoonu-agentic-sop-release-gate
- Primary output: validated SOP-to-agent release contract

mintlify-deal-spec-gate
- Primary output: validated deal-to-engineering handoff contract

Validation
- Errors: 0
- Warnings: 0

All registry, segment, schema, and bundle checks passed.
```

## Hostile test

A disposable Mintlify source copy was changed after bundling and its final implementation state was falsified to `production_proven`.

The actual validator exited `1` and rejected both:

- stale source/bundle equality;
- unsupported implementation status.

That negative capability is the core differentiator: **the artifact refuses internally inconsistent or inflated specifications.**

## Truth boundary

Implemented here: compiler mechanics, segmented specification design, bundle generation, validation, deterministic report, hostile test, public employer demo.

Not claimed: production deployment inside Snoonu or Mintlify, private company access, live integrations, or measured business impact.

## Employer-facing one-liner

> I turn ambiguous operational or customer requirements into machine-checkable engineering contracts, then force evidence, invariants, failure handling, and implementation truth to stay synchronized as the project changes.
