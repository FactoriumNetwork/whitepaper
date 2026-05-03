# Contributing to Factorium

Factorium is an open source protocol. Contributions from the community are not just welcome — they are essential to building infrastructure that the world can trust. This document explains how to participate.

---

## Before You Contribute

Read the [whitepaper](./Factorium_Whitepaper.pdf). Understand the protocol's economic design, the staking model, and the dispute layer before proposing changes to any of them. The most valuable contributions come from people who understand why the system is designed the way it is, not just how it works.

---

## What We Welcome

**Protocol improvements** — Changes to the attestation ledger schema, the node client, the dispute mechanism, or the bounty marketplace that make the system more efficient, more secure, or more accessible.

**Security findings** — If you find a vulnerability, please read [SECURITY.md](./SECURITY.md) before doing anything else. Do not open a public issue for security vulnerabilities.

**Documentation** — Clear documentation is as important as correct code. If something is hard to understand, that is a bug worth fixing.

**Use case proposals** — New verification categories that belong on the network. Open an issue describing the verification type, the buyer profile, the seller profile, and why the economics work.

**Bug reports** — Specific, reproducible, with enough detail that someone who wasn't there can reproduce the problem.

---

## What Requires Extra Care

The following areas touch the trust and economics layer of the protocol. Changes here require broader review and explicit steering committee approval before merging. Do not expect fast turnaround on proposals in these areas — thoroughness matters more than speed.

- Staking ratio logic
- Fee structure at the smart contract level
- Dispute resolution mechanics
- Slashing conditions
- Reputation scoring algorithms

If you are proposing a change in one of these areas, open a discussion issue first before writing any code. Explain the problem you are solving and the approach you are considering. Get feedback before investing time in implementation.

---

## How to Contribute

1. **Fork the repository** and create a branch from `main`
2. **Make your changes** with clear, descriptive commit messages
3. **Write or update tests** if the codebase has a test suite for the area you are changing
4. **Open a pull request** with a clear description of what you changed and why
5. **Respond to review** — maintainers may ask questions or request changes

Pull requests that touch the trust and economics layer will be labeled `requires-steering-committee` and will not be merged until the committee has reviewed them.

---

## Code Standards

- Clear variable and function names over clever ones
- Comments explain why, not what
- No external dependencies added without discussion
- Smart contract changes must include plain language explanation of what the code does

---

## Conduct

This project is infrastructure. The standard here is professional and technical. Critique ideas, not people. Be specific. Be honest. Be patient with contributors who are newer to the codebase than you are.

---

## Questions

Open a discussion on GitHub if you are unsure whether something is worth contributing or how to approach a problem. There are no bad questions from people who have read the whitepaper.
