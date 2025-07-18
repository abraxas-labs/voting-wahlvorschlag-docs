# Code of Conduct for participating in Abraxas VOTING

## Introduction

The application, named `VOTING Wahlvorschlag`, is an electronic solution for managing election proposals. The system allows political parties to record their election proposals through a web application and submit them for preliminary review. The software presented here is a product of the company Abraxas Informatik AG (`Abraxas`).

Abraxas continuously publishes a pre-release version (release candidate) of the system, which contains information about the functionality, the source code and the corresponding documentation, and conducts a Bug Bounty Program. These actions together are hereinafter referred to as "**the Program**".

The goal of the Program is to find and fix security issues and to improve the security-related quality of the system. The cantons and Abraxas firmly believe that openness and public scrutiny will lead to a trustworthy system of high quality.

This Code of Conduct and the [Bug Bounty Policy](./SECURITY.md#bug-bounty-policy) together establish the rules for the Program. The [Bug Bounty Policy](./SECURITY.md#bug-bounty-policy) on the Bug Bounty Platform is synonymous to the Security Policy on GitHub.

## Basic Rules

Scope of the Program is the disclosed material and the dedicated system for the Bug Bounty Program (as defined in chapter "Scope"). Any other information, services and systems are out of scope.

Abraxas retains all intellectual property and relates rights to the source code and other disclosed components of the system, including copyright and patent rights. No transfer of title is intended.

Everyone accessing all or parts of the Program or participating in the Bug Bounty Program agrees to be bound by the provisions of this Code of Conduct and the [Bug Bounty Policy](./SECURITY.md#bug-bounty-policy).

Abraxas runs the Bug Bounty Program with support from Bug Bounty Switzerland AG. The decisions in the Bug Bounty Program are made by Abraxas solely.

## What you can expect from us

- We carefully review all incoming reports about vulnerabilities and are interested in a constructive dialog on an equal footing.
- We recognize reports from experts as an important contribution to the improvement of the security of the system `VOTING Wahlvorschlag`.
- We pay fair rewards in the Bug Bounty Program.
- We respect the academic freedom of researchers.

## What we expect from you

- Participants respect the privacy and property of others and avoid destroying data or disrupting systems.
- Participants report their findings to Abraxas through one of the offered channels.
- Participants read the Code of Conduct and adhere to it, including responsible disclosure.

## Participation Rules

No registration is required for accessing the system and its source code, once disclosed publicly. However, you need to register if you want to participate in the Bug Bounty Program to:

- conduct active security tests on the system
- get accounts for the system
- be eligible to get rewards for valid vulnerabilities

You may register for the Bug Bounty Program on the [Bug Bounty Switzerland Platform](https://www.bugbounty.ch/abraxas/).

## Scope

In scope for the Program is information about the software and the infrastructure, its source code and the corresponding documentation available on GitHub.
In scope for the Bug Bounty Program is a dedicated non-productive instance of the running product `VOTING Wahlvorschlag`, including the necessary infrastructure. The product `VOTING Wahlvorschlag` and its infrastructure include for example:

- `VOTING Wahlvorschlag - Service` (Backend)
- `VOTING Wahlvorschlag - WebApp` (Frontend)
- `IAM System` (Login-System)

For more information about the technical details of the scope, how to access the system and the [Bug Bounty Policy](./SECURITY.md#bug-bounty-policy), please refer to the [Abraxas Bug Bounty Program Page](https://www.bugbounty.ch/abraxas/) or [GitHub](https://github.com/abraxas-labs/).

## Submission Guidelines

Findings need to be reported through one of the following channels:

- Bug Bounty Program on the [Bug Bounty Switzerland Platform](https://www.bugbounty.ch/hacker/)
- Issue / security advisory to the Abraxas Product Security Incident Response Team: psirt-voting@abraxas.ch

    Please ensure to report only findings having an impact on security of the product `VOTING Wahlvorschlag` (see chapter "Scope"). Your report must contain a clear proof of concept that demonstrates the scenario. Findings which have no impact on security or which are purely theoretical are not eligible.

Your submission must contain the following details:

- Attack scenario including impact on the product `VOTING Wahlvorschlag` in form of a step-by-step procedure to reproduce the issue
- References to the documentation and the source code:
  - implicated protocols/algorithms
  - implicated pages/paragraphs
  - implicated line(s) of code (when relevant)
  - any other information that might help us identify the vulnerable parts
- External references:
  - Academic references on the matter
  - Technical studies on the matter
  - Conference papers
  - Any other information that might help us understand the vulnerability

### Rewards

For legal reasons, rewards can only be obtained through the Bug Bounty Platform. Rewards are distributed at the discretion of Abraxas. Reporting a finding does not mean you have a right to receive bug bounty bonuses.

The Bug Bounty reward grid for this program can be found in the [Bug Bounty Policy](./SECURITY.md#reward-grid).

## Responsible Vulnerability Disclosure

Abraxas will communicate transparently about results and findings as soon as the public release starts on GitHub under [voting-wahlvorschlag-docs / Security Advisory](https://github.com/abraxas-labs/voting-wahlvorschlag-docs/security/advisories).

Everyone who reports a relevant finding will be credited for it in accordance with the terms of the [Bug Bounty Policy](./SECURITY.md#bug-bounty-policy). If you wish, you may remain anonymous. You may also use an alias.

You are free to publish your findings only after allowing Abraxas a maximum of 90 days (starting from the day of your submission) to analyze your submission and the opportunity to fix the vulnerability. As soon as we have deeply analysed your report, we will give you an information for publication. A coordination with Abraxas regarding the disclosure after the set period would be appreciated, but is not specifically required.

## License Source Code (Permitted use)

You are entitled to examine and modify the source code for non-commercial or non-productive purposes. In consideration of the corresponding term mentioned above, you may publish papers on your findings and use the information gained for the purpose of research, advancing knowledge, teaching or learning.

You are allowed to make copies of the source code. The license terms, copyright notices and attributions included in the source code or the other materials must be maintained and adhered to at all times.

You are not allowed to use any part of the Program, or any information gained from the Program or from parts of the Program for commercial purposes or for any use in another system or for any productive use. In particular, the source code or any part of it may not be used in any software or for any goods or services.

## Consequences of non-complying with the Code of Conduct

Abraxas values a constructive and fair collaboration with the participants. When acting in accordance with this Code of Conduct, the [Bug Bounty Policy](./SECURITY.md#bug-bounty-policy)  and in compliance with the applicable laws, Abraxas waives claims against the participants.

Any non-compliance with this Code of Conduct, the [Bug Bounty Policy](./SECURITY.md#bug-bounty-policy) , and the applicable laws may result in exclusion from the Program. For minor breaches, a warning may be issued. For severe breaches, Abraxas reserves all rights provided by applicable laws.

## Applicable Law and Jurisdiction

The Code of Conduct is governed by and constituted in accordance with the laws of Switzerland, with the exclusion of the United Nations Convention on Contracts for the International Sale of Goods and the Conflict of Laws. Exclusive Place of Jurisdiction shall be St. Gallen, Switzerland, whereby mandatory statutory provisions to the contrary regarding the place of jurisdiction are reserved.
