# Security Policy
All in Bits (AiB) strives to contribute toward the security of our ecosystem through internal security practices, and by working with external security researchers from the community.

## Reporting a Vulnerability

If you've identified a vulnerability, please report it through one of the following venues:

1. Submit an advisory through GitHub:

 * GovGen Governance dApp: https://github.com/allinbits/govgen-governance-dapp/security/advisories/new  
 * AtomOne Governance dApp: https://github.com/allinbits/atomone-governance-dapp/security/advisories/new
 * GovGen daemon: https://github.com/atomone-hub/govgen/security/advisories/new
 * AtomOne daemon: https://github.com/atomone-hub/atomone/security/advisories/new
 * GovGen daemon: https://github.com/atomone-hub/govgen/security/advisories/new

2. Email security [at-symbol] allinbits [dot] com. If you are concerned about confidentiality e.g. because of a high-severity issue, you may email us for PGP or Signal contact details.

3. We provide bug bounty rewards through our program at HackenProof. You must report via HackenProof in order to be eligible for rewards. A list of software in scope for our HackenProof programs can be found here:

https://hackenproof.com/company/all-in-bits/programs

We will respond within 3 business days to all received reports.

Thank you for helping to keep our ecosystem safe!

## Security Audits

AiB frequently engages third-party security auditors to review software in the ecosystems we contribute to. Some of these projects we contribute to are listed below, along with their audit status:

* GovGen daemon: This is a minimal fork of the popular Cosmos Gaia project, which itself is a wrapper for a version of the Cosmos SDK audited by Oak Security. We do not have any third-party audits planned for this daemon.

* AtomOne daemon: A third-party audit is currently planned.

* GovGen Governance dApp: Zellic produced a [report](audits/) for their audit of this dApp on May 7, 2024 against commit 2efa134e3adab63055d2c5a66766ee1ad67f3c03. A differential review of changes since is currently planned.

* AtomOne Governance dApp: As a small fork of the GovGen Governance dApp, a third-party audit of this project or its underlying library once refactored is planned.

* AtomOne Staking Portal: As a small fork of the GovGen Governance dApp, a third-party audit of this project is currently planned as part of the updated audit of the GovGen Governance dApp.
