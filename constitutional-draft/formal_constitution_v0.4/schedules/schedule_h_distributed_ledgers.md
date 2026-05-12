# Schedule H — Distributed Public Ledger Rules
## Formal Constitution v0.4

## Status

Draft schedule extracted from:

- `systems/technology-system/distributed_public_ledger_v0.2.md`
- `constitutional-draft/formal_constitution_v0.3.md`
- `constitutional-draft/formal_constitution_v0.4/core_constitution.md`
- `pressure-tests/formal_constitution_v0.3_pressure_test.md`

## Purpose

This schedule defines when distributed ledgers, blockchains, tamper-evident ledgers, or equivalent verification systems may be used by the Commonwealth.

Core rule:

> Distributed ledgers are constitutional evidence infrastructure, not constitutional authority.

---

# I. Ledger Doctrine

## Section 1. Verification Layer

Distributed ledgers may be used to verify public records, timestamps, provenance, version history, credentials, audit trails, fiscal flows, and public accountability records.

## Section 2. No Sovereign Substitution

Distributed ledgers may not replace:

1. voting;
2. courts;
3. human review;
4. privacy rights;
5. emergency limits;
6. benefit eligibility;
7. punishment decisions;
8. legal status decisions;
9. democratic authority;
10. lawful correction;
11. public accountability;
12. constitutional review.

## Section 3. Core Maxim

Verify records.

Do not automate sovereignty.

---

# II. Permitted Ledger Modules

## Section 1. Public Accountability Ledger

A Public Accountability Ledger may verify:

1. public decisions;
2. accountable offices;
3. legal basis records;
4. appeal path publication;
5. audit path publication;
6. review or expiration dates;
7. technology disclosure records;
8. conflict disclosure records;
9. emergency authority records.

## Section 2. Procurement Integrity Ledger

A Procurement Integrity Ledger may verify:

1. bid announcements;
2. bidders;
3. beneficial ownership attestations;
4. contract awards;
5. amendments;
6. change orders;
7. delivery milestones;
8. payments;
9. vendor conflicts;
10. audit findings;
11. emergency procurement exceptions.

## Section 3. Legislative Provenance Ledger

A Legislative Provenance Ledger may verify:

1. bill versions;
2. amendments;
3. sponsors;
4. committee changes;
5. late insertions;
6. fiscal score references;
7. rights impact references;
8. vote history;
9. public comment periods;
10. final enacted version.

## Section 4. Fiscal Flow Ledger

A Fiscal Flow Ledger may verify movement of authorized public funds, including:

1. appropriations;
2. agency allocations;
3. intergovernmental transfers;
4. grants;
5. contract payments;
6. emergency disbursements;
7. project milestones;
8. audit results.

The ledger tracks authorized spending execution. It does not authorize spending by itself.

## Section 5. Public Algorithm Registry Ledger

A Public Algorithm Registry Ledger may verify:

1. algorithm or AI system name;
2. legal authority;
3. accountable human owner;
4. risk tier;
5. deployment date;
6. model or system version hash;
7. audit status;
8. impact assessment reference;
9. rollback event;
10. suspension event;
11. reauthorization date;
12. appeal path publication.

## Section 6. Credential Verification Ledger

A Credential Verification Ledger may support verification of:

1. Public Trust Licenses;
2. professional licenses;
3. civil service credentials;
4. public official ethics certifications;
5. contractor eligibility;
6. emergency-response qualifications;
7. audit certifications.

## Section 7. Election Audit Ledger

An Election Audit Ledger may verify:

1. chain-of-custody logs;
2. ballot box custody records;
3. machine certification hashes;
4. public testing records;
5. districting map versions;
6. certification timestamps;
7. recount logs;
8. court orders affecting election administration.

It may not serve as the default public voting mechanism.

---

# III. Prohibited Uses

## Section 1. Prohibited Public-Law Uses

Distributed ledgers, smart contracts, or equivalent systems may not independently:

1. conduct primary public voting by default;
2. replace secret ballots;
3. decide criminal guilt;
4. issue punishment;
5. deny benefits;
6. determine immigration or legal status;
7. authorize surveillance;
8. extend emergency powers;
9. remove officials;
10. certify election winners without lawful process;
11. suspend rights;
12. rewrite law;
13. replace courts, legislatures, agencies, or human review.

## Section 2. Sensitive Data Prohibition

Distributed ledgers shall not store unnecessary sensitive personal data directly on-chain or in equivalent immutable public records.

Sensitive data includes:

1. medical records;
2. benefit eligibility details;
3. criminal records;
4. immigration files;
5. biometric data;
6. private addresses;
7. personal financial details;
8. raw surveillance data;
9. private communications;
10. protected identity data;
11. minor data;
12. precise location data.

## Section 3. No Unstoppable Public-Law Code

No government smart contract may be unstoppable.

Any smart contract used by government must include lawful pause, override, appeal, correction, rollback, court-order compliance, and emergency suspension mechanisms.

---

# IV. DLT Necessity Test

## Section 1. Requirement

Before any distributed ledger module is deployed, the Commonwealth must pass a DLT Necessity Test.

## Section 2. Required Findings

The responsible public authority must show:

1. multiple institutions need shared verification;
2. tamper-evidence has material public value;
3. ordinary databases or signed audit logs are insufficient;
4. sensitive data can remain off-chain;
5. metadata risks are manageable;
6. lawful correction is possible;
7. validator governance is balanced;
8. cost is justified;
9. public usability improves;
10. the system improves trust rather than adding novelty.

## Section 3. Simpler-System Preference

If a signed append-only database, public audit log, conventional database, or archival record system solves the problem adequately, the Commonwealth shall not use a distributed ledger.

## Section 4. Public Finding

A DLT Necessity Finding shall be public, reasoned, and reviewable.

---

# V. Data Architecture

## Section 1. Layered Architecture

Ledger systems shall use a layered architecture where appropriate:

1. public verification layer;
2. permissioned institutional ledger;
3. protected off-chain data layer;
4. credential layer;
5. audit bridge.

## Section 2. Public Verification Layer

The public verification layer may contain:

1. hashes;
2. timestamps;
3. public record proofs;
4. version references;
5. non-sensitive metadata;
6. revocation proofs;
7. audit references.

## Section 3. Protected Data Layer

Sensitive data shall remain off-chain unless specifically authorized by law under strict rights and privacy review.

## Section 4. Audit Bridge

Audit bridges shall allow authorized auditors, courts, and stewardship bodies to verify record integrity without exposing unnecessary sensitive data.

---

# VI. Metadata Privacy

## Section 1. Metadata Privacy Audit

Before deployment, a ledger module shall receive a metadata privacy audit.

## Section 2. Audit Scope

The audit shall assess:

1. direct data exposure;
2. metadata exposure;
3. timing inference;
4. linkability;
5. reidentification risk;
6. repeated-transaction patterns;
7. credential revocation inference;
8. location or status inference;
9. vulnerable population exposure;
10. aggregation risks;
11. cross-ledger correlation risks.

## Section 3. Continuing Review

Metadata privacy risk shall be reviewed periodically and when ledger use materially changes.

## Section 4. Public Summary

A public summary of metadata privacy findings shall be published, subject to lawful privacy and security limits.

---

# VII. Legal Truth Supremacy

## Section 1. Rule

The ledger proves record history.

It does not determine final legal truth.

## Section 2. Lawful Correction

Courts and lawful authorities may correct, supersede, reverse, or invalidate ledger-backed records through transparent correction overlays.

## Section 3. Correction Overlay

A correction overlay shall identify:

1. original record reference where lawful;
2. correcting authority;
3. correction date;
4. legal basis;
5. reason for correction;
6. affected public authority;
7. appeal path where relevant.

## Section 4. No Chain Finality Over Law

A public authority may not claim that a ledger record is legally final merely because it is technically immutable.

---

# VIII. Oracle Accountability

## Section 1. Oracle Problem

A ledger cannot determine whether a real-world fact is true merely by recording it.

## Section 2. Certifying Authority

Every real-world fact entered into a ledger shall have a named certifying authority.

## Section 3. Required Trail

A ledger entry based on a real-world fact shall include or link to:

1. evidence trail;
2. legal authority;
3. certifying office;
4. challenge path;
5. audit path;
6. correction path;
7. conflict disclosure where relevant.

## Section 4. Examples

Oracle accountability applies to:

1. contract milestone completion;
2. vendor beneficial ownership;
3. emergency payment authorization;
4. algorithm version deployment;
5. election chain-of-custody entry;
6. credential issuance;
7. fiscal transfer record;
8. audit certification.

---

# IX. Validator Governance

## Section 1. Balance Rule

No single party, branch, agency, vendor, region, institutional class, professional guild, donor network, or private consortium may control ledger validation, upgrades, access rules, or correction governance.

## Section 2. Validator Composition

Validator governance may include, where appropriate:

1. Technology System participation;
2. Integrity System participation;
3. Public Audit participation;
4. state or regional node participation;
5. judicial or records authority participation for legal records;
6. election stewardship participation for election audit ledgers;
7. independent archival or public-interest technical participation.

## Section 3. No Functional Majority

No validator class may control a functional majority unless constitutionally justified and independently reviewed.

## Section 4. Governance Audit

Validator governance shall be audited for:

1. concentration;
2. vendor dependency;
3. political capture;
4. regional imbalance;
5. upgrade control;
6. correction governance;
7. access governance;
8. security.

---

# X. Public Exit and Portability

## Section 1. No Private Toll Road

No constitutional record system may become a private toll road.

## Section 2. Required Safeguards

Every ledger module shall include:

1. open standards;
2. exportability;
3. interoperability;
4. independent verification;
5. migration tools;
6. public documentation;
7. protocol audit rights;
8. tested exit path;
9. continuity plan if vendor fails.

## Section 3. Vendor Failure

A vendor failure, acquisition, contract dispute, or insolvency shall not destroy public record access, correction rights, or auditability.

## Section 4. Exit Testing

Exit and migration plans shall be tested periodically for critical ledger modules.

---

# XI. Smart Contract Limits

## Section 1. Permitted Smart Contract Uses

Smart contracts may be used only for narrow, objective, reversible, legally authorized administrative functions.

Permitted uses may include:

1. deadline alerts;
2. expiration notices;
3. milestone payment after human certification;
4. public record publication triggers;
5. credential expiration alerts;
6. audit-trigger notifications;
7. escrow for public procurement bonds;
8. grant disbursement after lawful eligibility approval.

## Section 2. Prohibited Smart Contract Uses

Smart contracts may not automate:

1. punishment;
2. benefit denial;
3. surveillance approval;
4. candidate disqualification;
5. emergency extension;
6. rights suspension;
7. election certification;
8. immigration or legal-status denial;
9. criminal justice decisions;
10. removal of officials.

## Section 3. Required Override

Every government smart contract must include lawful pause, override, appeal, correction, rollback, court-order compliance, and emergency suspension mechanisms.

## Section 4. Human Certification

Where a smart contract acts on real-world events, a named human or public office shall certify the relevant fact before execution, unless the action is a low-risk notification or publication trigger.

---

# XII. Election Boundary Rule

## Section 1. Permitted Election Uses

Distributed ledgers may support election auditability through:

1. chain-of-custody logs;
2. certification timestamps;
3. recount logs;
4. districting map versions;
5. machine certification hashes;
6. public testing records;
7. court order publication.

## Section 2. Default Voting Prohibition

Distributed ledgers shall not serve as the default public voting mechanism.

## Section 3. Separate Authorization

Any proposal to use distributed ledgers for public voting requires separate constitutional authorization, rights review, security review, privacy review, public ratification, and secret-ballot protection.

## Section 4. No Secret Ballot Weakening

No election technology may weaken secret ballot protections, voter coercion protections, or public confidence in lawful certification.

---

# XIII. Credential Verification

## Section 1. Permitted Use

Credential ledgers may support verification of public credentials.

## Section 2. Privacy

Credential systems shall minimize public exposure of personal information.

## Section 3. Revocation

Credential systems must support:

1. expiration;
2. suspension;
3. revocation;
4. renewal;
5. appeal;
6. correction;
7. reissuance.

## Section 4. Key Loss

No person shall lose rights, public status, or lawful access solely because of lost private keys or inaccessible digital credentials.

Alternative recovery and verification methods shall exist.

---

# XIV. Key Management and Recovery

## Section 1. Institutional Keys

Institutional ledger systems shall use key management appropriate to public risk.

Controls may include:

1. multi-signature authority;
2. hardware security standards;
3. key rotation;
4. emergency revocation;
5. separation of duties;
6. public incident reporting;
7. cyber audit;
8. disaster recovery plan.

## Section 2. Individual Credentials

Individual credential systems shall provide:

1. recovery mechanisms;
2. revocation if compromised;
3. accessible alternatives;
4. protection against identity theft;
5. assistance for people without digital access.

## Section 3. Key Compromise

Key compromise affecting public authority shall trigger incident response, audit, public notice where lawful, and correction path.

---

# XV. Public Explanation and Interface

## Section 1. Plain-Language Proof

Every ledger-backed public record shall show, through the Public Constitutional Interface:

1. what was recorded;
2. who recorded it;
3. when it was recorded;
4. why it matters;
5. what authority it relates to;
6. how to challenge it;
7. whether it was corrected;
8. whether private data is off-chain;
9. who audits it.

## Section 2. No Technical Literacy Requirement

Citizens shall not need to understand hashes, validators, wallets, keys, or smart contracts to understand accountability.

## Section 3. Public Education

Ledger-backed systems shall include public education explaining:

1. what the ledger proves;
2. what it does not prove;
3. how correction works;
4. how privacy is protected;
5. how to challenge errors.

---

# XVI. Disclosure Quality

## Section 1. Meaningful Disclosure

Ledger entries must meet minimum usefulness standards.

## Section 2. Insufficient Records

A record is insufficient if it is:

1. vague;
2. incomplete;
3. inaccessible;
4. unlinked to legal authority;
5. missing accountable owner;
6. missing appeal path;
7. missing audit path;
8. missing correction history;
9. too technical for public understanding;
10. designed to satisfy form without substance.

## Section 3. Cure

Defective ledger-backed public records are subject to Public Accountability Cure under Schedule F.

---

# XVII. Ledger Audits

## Section 1. Required Audits

Each ledger module shall be audited for:

1. security;
2. privacy;
3. metadata exposure;
4. integrity;
5. governance balance;
6. cost-benefit justification;
7. accessibility;
8. correction process;
9. vendor lock-in;
10. resilience;
11. public usability.

## Section 2. Audit Frequency

Critical ledger modules shall receive periodic audits and event-triggered audits after major incidents, upgrades, or governance changes.

## Section 3. Public Audit Summary

Audit summaries shall be public, subject to lawful privacy and security limits.

---

# XVIII. Sunset and Reauthorization

## Section 1. Review Date

Every ledger module shall have a review date.

## Section 2. Reauthorization Standard

Reauthorization requires showing:

1. the ledger still solves a real verification problem;
2. costs remain justified;
3. privacy risks are controlled;
4. correction paths work;
5. validators remain balanced;
6. public interface remains usable;
7. no simpler system has become better.

## Section 3. Retirement

A ledger module shall be retired, replaced, or narrowed where a simpler, safer, cheaper, or more usable system can satisfy the public purpose.

---

# XIX. Relationship to Other Schedules

## Section 1. Schedule A

Definitions and tests in Schedule A apply to this Schedule.

## Section 2. Schedule F

Public accountability and interface requirements are governed by Schedule F.

## Section 3. Schedule G

Technology governance applies to ledger systems.

## Section 4. Schedule I

Fiscal flow ledger and spending records are also governed by Schedule I.

## Section 5. Schedule J

Emergency ledger use is also governed by Schedule J.

## Section 6. Schedule B

Election audit ledgers are also governed by Schedule B.

---

# XX. Schedule Review

## Section 1. Periodic Review

This Schedule shall be reviewed periodically to ensure distributed ledger use remains necessary, privacy-protecting, interoperable, correctable, and resistant to capture.

## Section 2. Review Criteria

Review shall assess:

1. DLT necessity;
2. public usability;
3. privacy and metadata risk;
4. correction effectiveness;
5. vendor independence;
6. validator balance;
7. cost;
8. auditability;
9. cybersecurity;
10. public trust;
11. replacement by simpler systems;
12. risk of sovereign automation.

## Section 3. Amendment

Amendment of this Schedule shall follow the major statutory architecture or framework amendment process, as applicable.
