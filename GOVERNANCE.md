# Factorium Governance

Factorium is designed to outlive any single founder, team, or company. This document describes how decisions are made, who makes them, and how that changes over time.

---

## Core Principle

A protocol that governs trust between AI systems cannot itself be governed by a single trusted party. Every governance decision in this document follows from that principle.

---

## Decision Types

Not all decisions require the same process. Factorium distinguishes between three categories.

**Routine decisions** — Bug fixes, documentation updates, non-breaking improvements to tooling, and changes that do not affect the trust or economics layer. These are reviewed and merged by any core maintainer.

**Standard decisions** — New features, breaking changes to the API, additions of new verification categories, and changes to the node client that affect verifier behavior. These require review by at least two core maintainers and a minimum 72-hour comment period before merging.

**Trust and economics decisions** — Any change to the staking ratio, fee structure, dispute mechanism, slashing conditions, or reputation scoring algorithm. These require explicit approval from the Technical Steering Committee, a minimum 14-day public comment period, and documentation of the reasoning in the governance log.

---

## The Technical Steering Committee

The Technical Steering Committee is the governing body for trust and economics decisions.

**Composition** — The committee begins with the founding team. New members are added by consensus of the existing committee from among contributors who have demonstrated sustained, high-quality participation in the protocol. Committee membership is public.

**Decision making** — The committee seeks consensus. When consensus cannot be reached, decisions are made by simple majority vote of committee members. Votes and their reasoning are recorded publicly in the governance log.

**Term** — There are no fixed terms. Committee members serve until they resign or until the committee votes to remove a member for conduct that violates the project's standards. Removal requires a two-thirds majority.

**Founder authority** — The founding team holds no special veto over committee decisions made through this process. Founder authority during the founding phase is explicitly temporary and explicitly limited to decisions necessary to reach testnet. See Founding Phase below.

---

## Core Maintainers

Core maintainers are trusted contributors with merge access to the repository. They handle routine and standard decisions, triage issues, review pull requests, and keep the project moving.

Core maintainer status is granted by the steering committee to contributors who have demonstrated consistent, quality participation over time. It is not a title. It is a responsibility.

---

## The Governance Log

All trust and economics decisions, including the reasoning behind them, are recorded in the `GOVERNANCE_LOG.md` file in this repository. This log is append-only. Entries are never edited or deleted. It is the permanent record of how the protocol has evolved and why.

---

## Founding Phase

During the founding phase — before the testnet reaches 90 days of stable operation — the founding team has the authority to make decisions necessary to reach that milestone. This authority is:

- **Temporary** — it ends when the testnet milestone is reached
- **Limited** — it does not extend to permanent changes to the trust and economics layer without documentation
- **Transparent** — all founding phase decisions that would normally require steering committee review are documented in the governance log with explicit notation that they were made under founding phase authority

This is not a loophole. It is an honest acknowledgment that governance bodies cannot function before contributors exist to populate them. The transition from founding phase to full community governance is a defined milestone, not an indefinite deferral.

---

## Amendments

This document can be amended through the trust and economics decision process — meaning a 14-day public comment period and explicit steering committee approval. The founding team cannot amend this document unilaterally after the founding phase ends.

---

## Questions

Open a discussion on GitHub. Governance questions are welcome and important.
