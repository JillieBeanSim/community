# Maturity

This document outlines what levels of maturity are to be found within the Zowe project and the ways to transition between the different stages within the lifecycle.

## Squads

- **Proposal** - Idea presented to the TSC and ZAC based on the process outlined in [Proposal Process](#Proposal Acceptance Process)
- **Incubator** - Squad accepted to the incubator stage. The squad is provisionally part of the Zowe project but doesn't have voting rights including the committers of the squad  
- **Active** - Demonstrated sustainability and sufficient maturity. The squad has regular meetings, there is TSC representative from the squad and the squad committers can vote on Zowe wide topics.
- **Emeritus** - No new development is expected to be done by the squad. The squad is disbanded and the TSC representative leaves the TSC. The created artifacts are retained under Zowe. 

## Stages

Every Zowe squad has an associated stage. The current state of the squads is reflected in the [squads.md](squads.md). The squad states the preferred stage (incubator, active). The TSC and ZAC votes on accepting the project with the preferred stage. The resolution could be either: accept the proposal, reject the proposal or in case active stage is requested offer acceptance in an incubator stage. 

Squads in all stages have access to all resources listed at [https://openmainframeproject.org/projects](https://openmainframeproject.org/projects) but if there is contention, more mature squads will generally have priority.

### Proposal Stage

The proposal requirements are based on the [CNCF Project Proposal Process v1.1](https://github.com/CNCF/toc/blob/40abe6f81c2b46842a87d6c47cf4190f0d8c1856/process/project_proposals.adoc).

#### Requirements

Squad must be proposed via a Community issue to [GitHub](https://github.com/zowe/community/issues) via Squad Proposal template. Squads proposals submitted to the Zowe must provide the information requested in the [Proposal](../.github/ISSUE_TEMPLATE/proposal.md)

#### Proposal Acceptance Process

* Projects are required to schedule and present their proposal at a Zowe-wide meeting such as TSC, ZAC or architecture. You can check the meeting schedules in the [Zowe Development Calendar].(https://lists.openmainframeproject.org/g/zowe-dev/calendar). The #zowe-tsc or #zowe-dev slack channels are good places to ask. 
* Projects get accepted via majority vote of the ZAC as well as a majority vote of TSC.

The newly formed squad:
* is bound by the Code of Conduct as outlined in the TSC charter.
* agrees to transfer any relevant trademarks to Zowe and to assist in filing for any relevant unregistered ones. This assignment will be reversed if the project does not remain in the Zowe, as described below. Note that no patent or copyright assignment is necessary because the [Eclipse Public License 2.0 (EPL-2.0)](https://spdx.org/licenses/EPL-2.0.html) provides sufficient protections for other developers and users.
* follows best practices outlined by TSC in best_practices directory
* starts at the agreed stage

### Incubation Stage

Every 12 months, each Incubation Stage squads will come to a vote with the ZAC and TSC. A majority vote of both bodies is required to renew a squad at Incubation Stage for another 12 months or move it to active stage. If there is not a majority in both bodies for any of these options, the squad is not renewed.

In the case of an Incubation Stage squad that is not renewed with Zowe, the trademark will be returned to the project maintainers or an organization they designate.

In order to move to the active stage, following requirements must be met and demonstrated by the squad. The squad:
 * Have committers from at least two organizations.
 * Follow the TSC agreed Best practices.
 * Have a designated TSC representative. Provide updated Governance and Committers files where applicable. The current committers and contributors are in the GitHub as outlined in the TSC [Contributing guidelines](contributing.md)

The squads are expected to move from the incubation stage within two years. If agreed with TSC and ZAC they can stay in the Incubation stage longer when needed.  

### Active Stage

Active stage squad represents a mature squad working within the Zowe project who is actively collaborating with the other squads. Squads can remain in the active stage indefinitely. 

### Emeritus Stage

Squads have lifecycles, and often in open source the relevance for a given squad over time can diminish. Nonetheless, having a home for artifacts no longer actively being developed by any squad is crucial for long-term sustainability and asset management. 

Squads only can enter the Emeritus Stage by either:

* On request from the squad itself, requiring a 2/3rd votes of all active squad committers
* By a majority vote of the ZAC and TSC if there has been insufficent activity in the squad over the course of 6 months.

When in the Emeritus Stage, the squad's code repository administration is transferred to a designated individual by the Zowe. No new features or bug fixes will be addressed, unless it is deemed a security issue. Open Mainframe Project and Zowe will hold all assets in perpetuity.

A squad can move back to Active Stage following the guidelines for a project being accepted at the Active Stage above.

## Components

What are the actual differencies?

- **Technical Preview**