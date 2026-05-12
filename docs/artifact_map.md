# Artifact Map
## Modular Constitutional Commonwealth

## Purpose

This map explains the major artifacts in the repository, their current status, and the recommended reading order.

The repo now contains three parallel layers:

1. **Public-facing materials** — for ordinary readers.
2. **Technical architecture** — for system design and refinement.
3. **Formal constitutional drafts** — for legal-style structure and pressure testing.

---

# Recommended Reading Order

## 1. Public entry point

Start here:

```text
manifesto/public_manifesto_v0.1.md
constitutional-draft/public_constitution_lite_v0.1.md
```

These explain the project in public-facing language.

## 2. System architecture

Then read:

```txt
architecture/master_architecture_v1.0.md
```

This is the consolidated technical architecture.

## 3. Formal constitutional draft

Then read:

```txt
constitutional-draft/formal_constitution_v0.3.md
```

This is the current stable technical constitutional draft.

## 4. Pressure-test history

Then read:

```txt
pressure-tests/formal_constitution_v0.3_pressure_test.md
```

This explains what v0.3 still needs before restructuring.

## 5. Future restructuring map

Then read:

```txt
constitutional-draft/constitutional_schedules_map_v0.1.md
```

This explains how v0.3 should eventually become a shorter core constitution plus schedules.

---

# Major Artifacts

## Public-Facing Materials

| File | Status | Purpose |
| --- | --- | --- |
| `manifest/public_manifesto_v0.1.md` | Drafted | Public philosophical explanation of the Commonwealth |
| `constitutional-draft/public_constitution_lite_v0.1.md` | Drafted | Plain-language constitutional version for public readers |

## Architecture

| File | Status | Purpose |
| --- | --- | --- |
| `architecture/master_architecture_v1.0.md` | Stable | Consolidated technical reference architecture |
| `constitutional-draft/constitutional_schedules_map_v0.1.md` | Drafted | Map for future Constitution + Schedules restructure |

## Formal Constitutional Drafts

| File | Status | Purpose |
| --- | --- | --- |
| `constitutional-draft/formal_constitution_v0.1.md` | Historical | First formal constitutional draft |
| `constitutional-draft/formal_constitution_v0.2.md` | Historical | Pressure-tested refinement of v0.1 |
| `constitutional-draft/formal_consitution_v0.3.md` | Stable Technical Draft | Current full technical constitutional draft |

## Pressure Tests

| File | Status | Purpose |
| --- | --- | --- |
| `pressure-tests/formal_constitution_v0.1_pressure_test.md` | Complete | Article-by-article pressure test of v0.1 |
| `pressure-tests/formal_constitution_v0.2_pressure_test.md` | Complete | Refinement-focused pressure test of v0.2 |
| `pressure-tests/formal_constitution_v0.3_pressure_test.md` | Complete | Technical/public-usability pressure test of v0.3 |

## Planning

| File | Status | Purpose |
| --- | --- | --- |
| `constitutional-draft/v0.3_refinement_plan.md` | Complete | Controlled drafting plan for v0.3 |
| `constitutional-draft/open_parameters.md` | Active | Tracks unresolved mechanics and parameters |
| `parameters/parameter_design_matrix_v0.1.md | Drafted | Early parameter design matrix |

## Governance Logs

| File | Status | Purpose |
| --- | --- | --- |
| `DECISIONS_LOG.md` | Active | Records locked design decisions |
| `ROADMAP.md` | Active | Tracks project progress |
| `CHANGELOG.md` | Active | Tracks repository changes |

---

# System Module Files

## Democratic System

| File | Status | Purpose |
| --- | --- | --- |
| `systems/democratic-system/party_power_roles.md` | Drafted | Locked party power roles |
| `systems/democratic-system/electoral_system_v0.2.md` | Drafted | Electoral system direction |

## Rights and Justice System

| File | Status | Purpose |
| --- | --- | --- |
| `systems/rights-justice-system/court_hierarchy_v0.2.md` | Drafted | Court and rights enforcement architecture |

## Integrity System

| File | Status | Purpose |
| --- | --- | --- |
| `systems/integrity-system/stewardship_appointments_v0.2.md` | Drafted | Stewardship appointment architecture |

## Technology System

| File | Status | Purpose |
| --- | --- | --- |
| `systems/technology-system/distributed_public_ledger_v0.2.md` | Drafted | Distributed public ledger architecture |

## Resilience System

| File | Status | Purpose |
| --- | --- | --- |
| `systems/resilience-system/fiscal_constitution_v0.2.md` | Drafted | Fiscal constitution architecture |
| `systems/resilience-system/transition_roadmap_v0.2.md` | Drafted | Capacity-gated transition roadmap |

---

# Current Stable Milestone

The current milestone is:

```txt
Formal Constitution v0.3 = Stable Technical Draft
Public Constitution Lite v0.1 = Public-facing draft
Master Architecture v1.0 = Stable architecture reference
```

The next major design move is:

```txt
Formal Constitution v0.4 = Core Constitution + Schedules restructure
```

---

# Recommended Next Steps

## Immediate

  1. Review `public_constitution_lite_v0.1.md` for public readability.
  2. Review `formal_constituion_v0.3.md` for technical completeness.
  3. Use `constitutional_schedules_map_v0.1.md` to plan v0.4 restructuring.

## Next Major Build

Create:

```txt
Formal Constitution v0.4 = Core Constitution + Schedules restructure
constitutional-draft/formal_constitution_v0.4/
  core_constitution.md
  schedules/
```

Then extract schedules in priority order:

  1. Definitions and Tests
  2. Electoral Parameters
  3. Stewardship Appointments
  4. Court Jurisdiction
  5. Public Accountability Interface
  6. Technology Governance
  7. Fiscal Parameters
  8. Emergency Powers
  9. Transition Roadmap

---

# Current Project Thesis

> Make democracy hard to kill.
> Make policy easy to improve.
> Make power impossible to hide.
