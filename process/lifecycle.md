---
parent: Processes
title: Project Lifecycle
has_children: true
---

# Academy Software Foundation - Project Lifecycle

* TOC
{:toc}

This lifecycle document is maintained by the Academy Software Foundation, and its purpose is to:

* Describe the requirements for contributing a project to the Academy Software Foundation;
* Provide a clear process for the contribution of a project to the Academy Software Foundation; and
* Set milestones and requirements for different project development stages once accepted into Academy Software Foundation.

The Academy Software Foundation may adopt or amend this document by a majority vote of both the Technical Advisory Council (“TAC”) and Governing Board.

# Stages

This document provides four lifecycle stages for contributed projects:

* Sandbox;
* Incubation;
* Adopted; and
* Archived

Any project to be considered for inclusion by the TAC must complete the [proposal template](proposal_template). More details on bringing a project to the Academy Software Foundation are outlined [here](start_project).

## Sandbox Stage

Projects submitted to the Academy Software Foundation at the Sandbox Stage are intended to be the entry point for early-stage projects. Characteristics for projects at the Sandbox Stage may be one or more of the following:

* Early-stage projects that the TAC believes warrant experimentation.
* New projects designed to extend one or more TAC projects with functionality or interoperability libraries.
* Independent projects that fit the Academy Software Foundation mission/vision and provide the potential for a novel approach to existing functional areas (or are an attempt to meet an unfulfilled need).
* Projects commissioned or sanctioned by the Academy Software Foundation, including initial code for Academy Software Foundation Working Group collaborations and "experimental" projects.
* Any project that realistically intends to become an Academy Software Foundation Incubation Stage project and wishes to lay the foundations for that.

### Requirements

To be accepted at the Sandbox stage, a project must:

* Submit a completed [Project Contribution Proposal Template](proposal_template.md) to the TAC.
* Provide such additional information as the TAC may reasonably request.
* Present the project’s proposal to the TAC. Project teams should be prepared to present a detailed (20-30 minutes in length) overview of the project and speak to the information in the contribution proposal.
* Be deemed by the TAC to add potential value or value to the mission of the Academy Software Foundation.
* Obtain an affirmative vote of the TAC.

### Benefits

The Sandbox Stage benefits are outlined below.

* Neutral hosting of the project’s community and key assets (e.g., trademark, domain, etc.).
* Access to the Academy Software Foundation collaboration infrastructure ( including GitHub, JIRA, Confluence, mailing lists, and Slack ).
* A sponsor from the TAC to assist the project in reaching the Incubation Stage and to facilitate collaboration with other project communities.
* Right to refer to the project as a Sandbox Project of the Academy Software Foundation and an opportunity to participate in events and other collaborative activities sponsored by the Academy Software Foundation.
* Subject to applicable trademark usage guidelines to display the Academy Software Foundation’s logo on the project’s code repository.

Sandbox Stage projects will not have an announcement blog or press announcement because projects at the Sandbox stage are in an early stage and still gaining alignment among the stakeholders. We often see projects in the Sandbox Stage change scope and focus; the TAC aims to ensure that projects have the space to focus on building a solid governance and contributor base to grow towards the Incubation Stage.

### Expectations

The TAC may request Sandbox Stage projects to provide updates outlining its progress on completing the requirements for the Incubation Stage before the Annual Review. If a project fails to provide these reports after a TAC request, the TAC may vote to remove the project from the Sandbox stage.

Projects in the Sandbox Stage are expected to move or have made demonstrable progress on moving to the [Incubation Stage](#incubation-stage) within one year. Sandbox Projects may propose to be reviewed to move to the Incubation Stage during its regularly scheduled [Annual Review](review_cycle); projects can also request to hold their annual review early if they have completed the requirements before its scheduled [Annual Review](review_cycle).

At the project's [Annual Review](review_cycle), the TAC will vote to either:

* Move the project to the Incubation Stage if it meets the requirement for that stage.
* Renew the project at the Sandbox Stage if it feels it will move to the Incubation Stage by the next Annual Review.
* Move the project to the [Archive Stage](#archive-stage). In this case, the trademark and any other assets will be returned to the project maintainers or an organization they designate.

## Incubation Stage

A project at the Incubation Stage has begun to form a community and develop its scope and mission. Incubation Stage projects likely will have some adoption in testing or production use.

### Requirements

To be accepted at the Incubation stage, a project must meet the Sandbox requirements plus:

*   Have completed and approved the Technical Charter and agree to transfer any relevant trademarks to The Linux Foundation or its affiliate, LF Projects, LLC, and to assist in filing for any relevant unregistered ones.
*   Have defined its technical governance, including:
    *   A LICENSE file in every code repository, with the license chosen an [OSI-approved license](https://opensource.org/licenses/).
    *   A README file welcoming new community members to the project and explaining why the project is useful and how to get started ( follow the guidelines at the [README checklist](https://github.com/ddbeck/readme-checklist) to create an excellent README file ).
    *   A CONTRIBUTING file explaining to other developers and your community of users how to contribute to the project. The file should describe the types of contributions needed and how the process works.
    *   A CODEOWNERS or COMMITTERS file to define individuals or teams that are responsible for code in a repository; document current project owners and current and emeritus committers. 
    *   A CODE_OF_CONDUCT file that sets the ground rules for participants’ behavior associated and helps to facilitate a friendly, welcoming environment. By default, projects should leverage the Linux Foundation Code of Conduct unless an alternate Code of Conduct was previously approved.
    *   A RELEASE file that documents the release methodology, cadence, criteria, etc.
    *   A GOVERNANCE file that documents the project’s technical governance.
    *   A SUPPORT file to let users and developers know about ways to get help with your project.
*   Have achieved and maintained an OpenSSF Best Practices Badge at the [passing level](https://bestpractices.coreinfrastructure.org/en/criteria). 
*   Have had a successful license scan with any critical issues remedied.
*   Have a defined project mission and scope
*   An overview of the project’s architecture and features defined.
*   A project roadmap defined, which should address the following questions.
    *   What use cases are possible now?
    *   What does the next year look like regarding additional features and use cases covered?
*   Community and contributor growth assessment
    *   The current number of contributors, committers, and different organizations contributing to the project. 
    *   Demonstrate a sustained flow of commits / merged contributions
    *   A healthy number of end-users within the visual effects and motion picture industries that have adopted the project and that are identified within the project ( using an ADOPTERS file or showcased on the project’s website ).
    *   A credible plan for developing a thriving user community, particularly expanding the number of committers and contributors?
    *   Outline of the plan for the project to complete the requirements for the [Adopted Stage](#adopted-stage)
* Obtain an affirmative vote of the TAC.

Projects preparing to be considered for the Incubation Stage should prepare a presentation outlining how it has completed the requirements and present it at the TAC meeting where it is being considered.

### Benefits

Incubation stage projects are eligible to receive the following benefits:

* Be considered as one of the “Technical Projects” under the [Academy Software Foundation Charter](https://github.com/AcademySoftwareFoundation/foundation/blob/master/CHARTER.md) and may receive support as determined by the Governing Board.
* Neutral hosting of the project’s community and key assets (e.g., trademark, domain, etc.)
* Assistance from the Academy Software Foundation TAC to facilitate collaboration with other project communities.
* Blog announcement or similar communication announcing the inclusion of the project.
* Right to refer to the project as an incubation project of the Academy Software Foundation and an opportunity to participate in events and other collaborative activities sponsored by the Academy Software Foundation.
* Subject to applicable trademark usage guidelines, display the Academy Software Foundation’s logo on the project’s code repository.

### Expectations

During the project's Annual Review, the TAC will assess the progress toward graduating to the Adopted Stage. Projects can also request to hold their annual review early if they have completed the requirements before its scheduled [Annual Review](review_cycle). At the Annual Review, the TAC will vote to either: 

* Move the project to the Adopted Stage if it [meets those requirements](#requirements-2).
* Renew the project at the Incubation Stage if it feels it will move to the Adopted Stage by the next Annual Review.
* Move the project to the [Archive Stage](#archive-stage). In this case, the trademark and any other assets will be returned to the project maintainers or an organization they designate.

## Adopted Stage

Adopted Stage projects are considered mature projects that generally are ready for production use. Projects at this stage focus on growing an ecosystem of users and are often being leveraged in vendor products or used by end-users.

### Requirements

To be considered for the Adopted stage, a project must meet the Incubation stage requirements plus:

* Demonstrate a substantial ongoing flow of commits and merged contributions authored by a healthy number of diverse contributors*.
* Demonstrable roadmap progress.
* A significant number of end-users within the visual effects and motion picture industries that have adopted the project and that are identified within the project ( using an ADOPTERS file or showcased on the project’s website ).
* Have achieved and maintained an OpenSSF Best Practices Badge at the [gold level](https://bestpractices.coreinfrastructure.org/en/criteria/2).
* Have a technical lead appointed for voting representation of the project to the TAC.
* Be deemed by the TAC to add value to the mission of the Academy Software Foundation.
* Obtain both a 2/3 supermajority vote of the TAC and an affirmative majority vote of the Governing Board

*Since these metrics can vary significantly depending on a project's type, scope, and size, the TAC has final judgment over the level of activity adequate to meet these criteria. In general, it will be necessary to (at least) demonstrate that the project is not overly reliant on any one individual or organization and can remain healthy in the event of a departure.

### Benefits

Adopted stage projects are eligible to receive the following benefits:

* Be considered as one of the “TAC Projects” under the [Academy Software Foundation Charter](https://github.com/AcademySoftwareFoundation/foundation/blob/master/CHARTER.md) and may receive additional resources or support as determined by the Governing Board.
* Have a voting representative on the TAC.
* Right to refer to the project as an officially adopted project of the Academy Software Foundation and receive the highest priority for participating in events and other collaborative activities sponsored by the Academy Software Foundation.
* A blog announcement or similar communication announcing the graduation of the project.

### Expectations

Adopted Stage projects will have an Annual Review to assess if the project is still meeting the Adopted Stage requirements. At the Annual Review, the TAC will vote to either: 

* Renew the project at the Adopted Stage if it continues to [meet those requirements](#requirements-2).
* Move the project to the [Archive Stage](#archive-stage). In this case, the trademark and any other assets will be returned to the project maintainers or an organization they designate.

## Archive Stage

Projects like products have lifecycles, and often in open source, the relevance of a given project can diminish over time. Nonetheless, having a home for legacy and no longer maintained projects within the industry is crucial for long-term sustainability and asset management. Projects with operational, contributor, and/or adoption issues are not necessarily candidates for the Archive Stage; the TAC will work with these projects to improve any of these issues.

Projects only can enter the Archive Stage by either:

*   On request from the project itself, requiring a 2/3 supermajority vote of all active project committers.
*   By a 2/3 supermajority vote of the TAC if deemed to be no longer maintained.

In the Archive Stage, the project’s code repository administration is transferred to a designated individual by the TAC. No new features or bug fixes will be addressed unless it is deemed a security issue. Academy Software Foundation will hold all assets in perpetuity. Archive stage projects will be considered “Technical Projects" under the Academy Software Foundation charter and may receive support as determined by the Governing Board.

A project can move back to one of the Sandbox, Incubation, or Adopted Stages following the guidelines for a project being accepted at that level.
