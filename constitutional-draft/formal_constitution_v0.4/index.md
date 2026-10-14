# Formal Constitution v0.4 Package Index
## Modular Constitutional Commonwealth

## Purpose

This index explains the v0.4 constitutional package structure and recommended reading order.

v0.4 restructures the stable technical draft into:

1. Core Constitution
2. Constitutional Schedules
3. System Charters
4. Implementation Codes

Core rule:

> Shorter core. Stronger schedules. Same architecture.

---

# Recommended Reading Order

## 1. Start with the Core Constitution

```text
constitutional-draft/formal_constitution_v0.4/core_constitution.md
```

Purpose:

- public constitutional structure;
- core rights and institutions
- short-form constitutional doctrine;
- references to schedules for technical mechanics.

## 2. Then read the priority schedules

```txt
constitutional-draft/formal_constitution_v0.4/schedules/schedule_a_definitions_and_tests.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_b_electoral_parameters.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_c_party_governance.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_d_stewardship_appointments.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_e_court_jurisdiction.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_f_public_accountability_interface.md
```

Purpose:

- definitions;
- elections;
- parties;
- stewardship;
- courts;
- public accountability.

## 3. Then read the operational power schedules

```txt
constitutional-draft/formal_constitution_v0.4/schedules/schedule_g_technology_governance.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_h_distributed_ledgers.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_i_fiscal_parameters.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_j_emergency_powers.md
```

Purpose:

- technology;
- ledgers;
- fiscal constitution;
- emergency powers.

## 4. Then read the protection and continuity schedules

```txt
constitutional-draft/formal_constitution_v0.4/schedules/schedule_k_security_neutrality.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_l_information_integrity.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_m_public_service_anti_capture.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_n_transition_roadmap.md
constitutional-draft/formal_constitution_v0.4/schedules/schedule_o_amendment_refounding.md
```

Purpose:

- security neutrality;
- information integrity;
- anti-capture;
- transition;
- amendment and refounding.

---

# Core Document

| File | Status | Purpose |
| --- | --- | --- |
| `core_constitution.md` | Drafted | Shorter core constitutional context; technical detail moved to schedules |

---

# Constitutional Schedules

| Schedule | File | Status | Purpose |
| --- | --- | --- | --- |
| A | `schedules/schedule_a_definitions_and_tests.md` | Drafted | Core definitions and anti-evasion tests |
| B | `schedules/schedule_b_electoral_parameters.md` | Drafted | Electoral mechanics and review rules |
| C | `schedules/schedule_c_party_governance.md` | Drafted | Party roles, common control, funding, coalitions |
| D | `schedules/schedule_d_stewardship_appointments.md` | Drafted | Stewardship appointments, terms, removal, balance
| E | `schedules/schedule_e_court_jurisdiction.md` | Drafted | Courts, tribunals, remedies, appeals |
| F | `schedules/schedule_f_public_accountability_interface.md` | Drafted | Public accountability records and interface standards |
| G | `schedules/schedule_g_technology_governance.md` | Drafted | AI, algorithms, publi technology, human review |
| H | `schedules/schedule_h_distributed_ledgers.md` | Drafted | Distributed ledgers, blockchain limits, verification |
| I | `schedules/schedule_i_fiscal_parameters.md` | Drafted | Fiscal truth machinery, ledgers, risk bands |
| J | `schedules/schedule_j_emergency_powers.md` | Drafted | Emergency activation, renewal, audit, normalcy |
| K | `schedules/schedule_k_security_neutrality.md` | Drafted | Civilian control, surveillance, security neutrality |
| L | `schedules/schedule_l_information_integrity.md` | Drafted | Speech protection and manipulation transparency |
| M | `schedules/schedule_m_public_service_anti_capture.md` | Drafted | Public service integrity and anti-capture rules |
| N | `schedules/schedule_n_transition_roadmap.md` | Drafted | Capacity-gated transition roadmap |
| O | `schedules/schedule_o_amendment_refounding.md` | Drafted | Amendment tiers and refounding procedure |

---

# System Charters

| File | Status | Purpose |
| --- | --- | --- |
| `system-charters/democratic_system_charter.md` | Populated draft | Operational charter for elections, parties, participation |
| `system-charters/rights_and_justice_system_charter.md` | Populated draft | Operational charter for courts and rights enforcement |
| `system-charters/integrity_system_charter.md` | Populated draft | Operational charter for anti-corruption and audit systems |
| `system-charters/technology_system_charter.md` | Populated draft | Operational charter for public technology and AI governance |
| `system-charters/resilience_system_charter.md` | Populated draft | Operational charter for emergency, fiscal, and future-risk systems |

---

# Implementation Codes

| File | Status | Purpose |
| --- | --- | --- |
| `implementation-codes/public_interface_code.md` | Populated draft | Administrative and technical standards for public interface |
| `implementation-codes/procurement_code.md` | Populated draft | Procurement rules, beneficial ownership, vendor audit access |
| `implementation-codes/algorithmic_audit_code.md` | Populated | Algorithmic audit, meaningful human review, metrics, drift, rollback, appeals, procurement integration, and audit-the-auditors |
| `implementation-codes/fiscal_reporting_code.md` | Scaffold | Fiscal dashboards, model disclosure, reporting formats |
| `implementation-codes/transition_implementation_code.md` | Scaffold | Phase checklists, readiness certification, legacy handover |

---

# Relationship to Earlier Drafts

| Earlier artifact | Relationship to v0.4 |
| --- | --- |
| `public_constitution_lite_v0.1.md` | Public-facing narrative version |
| `formal_constitution_v0.3.md` | Stable technical source draft |
| `formal_constitution_v0.3_pressure_test.md` | Pressure test that justified the v0.4 restructure |
| `constitutional_schedules_map_v0.1.md` | Extraction plan used to build v0.4 |
| `master_architecture_v1.0.md` | Architecture reference |

---

# Current v0.4 Completion Status

| Component | Status |
| --- | --- |
| Core Constitution | Complete draft |
| Schedules A-O | Complete draft |
| System Charters | Five populated drafts |
| Implementation Codes | Three populated drafts; Fiscal Reporting and Transition scaffolds |
| Package Index | Drafted |

---

# Next Recommended Work

Preserve the existing authority hierarchy and populated draft texts. Use
`scripts/audit-v04-package.py --check` to verify the package evidence after
summary changes, and assess the existing package pressure test before claiming
substantive consistency. The pressure test and all five charters already exist.

Fiscal Reporting and Transition remain scaffold-only. No new implementation-code
lane, legal adoption, deployment, or operational power is authorized by this
summary reconciliation. Further drafting requires a separate bounded decision.

---

# Current Project Thesis

> Make democracy hard to kill.
> Make policy easy to improve.
> Make power impossible to hide.
