# Security Policy

Factorium is trust infrastructure. Security vulnerabilities in this protocol have the potential to harm real participants through incorrect attestations, improper stake penalties, or economic exploits. We take security reports seriously and ask that you do too.

---

## Reporting a Vulnerability

**Do not open a public GitHub issue for security vulnerabilities.**

Public disclosure before a fix is in place puts network participants at risk. Please report vulnerabilities privately first.

**Contact:** security@factorium.network

Include in your report:
- A clear description of the vulnerability
- The component affected — smart contract, node client, API, dispute layer, etc.
- Steps to reproduce or a proof of concept if possible
- Your assessment of severity and potential impact
- Whether you intend to publish the finding and on what timeline

---

## What to Expect

**Acknowledgment** — We will acknowledge receipt of your report within 48 hours.

**Assessment** — We will assess the severity and scope within 7 days and communicate our findings to you.

**Resolution** — For critical vulnerabilities affecting the trust or economics layer, we will prioritize a fix above all other work. For lower severity issues, we will provide a timeline.

**Credit** — If you would like public credit for your finding once the vulnerability is resolved, we will include your name or handle in the release notes. If you prefer to remain anonymous, we will respect that.

---

## Severity Guidelines

**Critical** — Vulnerabilities that could allow incorrect attestations to be published without stake, allow stake to be stolen or manipulated, corrupt the reputation ledger, or exploit the dispute mechanism to harm honest participants. These receive immediate priority.

**High** — Vulnerabilities that could allow denial of service against the network, expose verifier or buyer data, or allow fee manipulation. These receive priority treatment within the normal release cycle.

**Medium and Low** — Other security issues that do not directly affect the trust or economics layer. These are addressed in regular releases.

---

## Smart Contract Security

Smart contracts deployed by Factorium will be audited by independent security firms before mainnet launch. Audit reports will be published publicly in this repository. The community is encouraged to review them and raise concerns through the governance process.

Known limitations and trust assumptions in the smart contracts will be documented explicitly. There are no hidden dependencies.

---

## Responsible Disclosure

We ask for a reasonable period to address vulnerabilities before public disclosure. In practice this means:

- Critical issues: 90 days or until a fix is deployed, whichever comes first
- High issues: 90 days
- Medium and lower: 120 days

If we are not responsive or if you believe a vulnerability is being actively exploited, you may disclose at your discretion. We will not take legal action against researchers acting in good faith.

---

## Out of Scope

The following are not considered security vulnerabilities for the purposes of this policy:

- Social engineering of Factorium team members
- Physical attacks against infrastructure
- Issues in third-party dependencies that are already publicly known
- Theoretical vulnerabilities without a realistic attack path

---

## Thank You

Security research is a public good. If you have taken the time to find and responsibly report a vulnerability in Factorium, you have contributed something real to the integrity of the network. We are grateful for it.
