# Kyverno Governance

This document defines governance policies for the [Kyverno and its sub-projects](https://github.com/kyverno#projects):

- [Kyverno Governance](#kyverno-governance)
  - [Principles](#principles)
  - [Code of Conduct](#code-of-conduct)
  - [Vendor Neutrality](#vendor-neutrality)
  - [Meetings](#meetings)
  - [Project Roles](#project-roles)
    - [Contributor Ladder](#contributor-ladder)
    - [Summary of Roles](#summary-of-roles)
      - [New Contributors](#new-contributors)
      - [Contributors](#contributors)
      - [Reviewers](#reviewers)
      - [Maintainers](#maintainers)
      - [Progression Process](#progression-process)
      - [Benefits of Contribution](benefits-of-contribution)
      - [Mapping Project Roles to GitHub Roles](#mapping-project-roles-to-github-roles)
    - [Off-boarding Guidance](#off-boarding-guidance)
  - [Maintainer Areas](#maintainer-areas)
    - [Kyverno Projects](#kyverno-projects)
    - [Projects areas](#projects-areas)
  - [Conflict Resolutions](#conflict-resolutions)
  - [Changes](#changes)
  - [Credits](#credits)

## Principles

The Kyverno community adheres to the following principles:

- **Open**: The Kyverno community strives to be open, accessible and welcoming to everyone. Anyone may contribute, and contributions are available to all users according to open-source values and licenses.
- **Transparent and accessible**: Any changes to the Kyverno source code and collaborations on the project are publicly accessible (GitHub issues, PRs, and discussions).
- **Merit**: Ideas and contributions are accepted according to their technical merit and alignment with project objectives, scope, and design principles.

## Code of Conduct

Kyverno follows the [Code of Conduct](CODE_OF_CONDUCT.md), which is aligned with the [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/main/code-of-conduct.md).

## Vendor Neutrality

Kyverno follows the CNCF vendor neutrality guidelines documented at:

   https://contribute.cncf.io/maintainers/community/vendor-neutrality/

## Meetings

Kyverno community meetings follow a defined [schedule](https://kyverno.io/community/#community-meetings).

The maintainers may also have closed meetings to discuss security reports or Code of Conduct (CoC) violations. Such meetings should be scheduled by any maintainer on receipt of a security issue or CoC report. All current Maintainers must be invited to such closed meetings, except for any maintainer who is accused of a CoC violation.

## Project Roles

The Kyverno community welcomes all contributors and has well-defined roles detailed below.

This document highlights the roles and responsibilities for the Kyverno community members. It also outlines the requirements for anyone who is looking to take on leadership roles in the Kyverno project. The following governance applies to all Kyverno subprojects.

**Note:** Please make sure to read the CNCF [Code of Conduct](https://github.com/cncf/foundation/blob/master/code-of-conduct.md).

### Contributor Ladder

Kyverno has defined a Contributor Ladder to recognize and promote contributors as they grow in involvement and impact. Each role is progressive, meaning that to move to the next level, a contributor must first have met the expectations of the previous level.

### Summary of Roles

The table below summarizes project roles and responsibilities. Details are provided in the sections following the table. Additionally, the roles used in this document are custom roles mapped according to the [GitHub roles and responsibilities](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization).

| Role         | Description & Requirements                                                                                                                     | Ongoing Responsibilities                                               | Defined by                                                                                                          |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| New Contributors | Has made initial contributions and is beginning to engage in the community.                                                                              | None                                                                   | N/A                                                                                                     |
| Contributors | After completion of five (5) contributions to the project or any sub-project community members are eligible for this role.                                                                              | None                                                                   | CONTRIBUTORS.md                                                                                                     |
| Reviewers | Make regular contributions, engage in issues, and participate in the community by providing support to others as needed.                                                                              | Triage                                                                   | REVIEWERS.md                                                                                                     |
| Maintainers | Owns areas of the project; responsible for approving changes and setting direction.                                                                              | Maintain                                                                   | MAINTAINERS.md

#### New Contributors

New Contributors are individuals who are new to our community and project and are looking to:
- Engage with the Kyverno community (Slack, mailing list, discussions)
- Make their first contributions to the project (issues, pull requests, discussion, documentation, support and conversations with other community members in Slack, blog writing, talks, and other content creation, etc.)

#### Contributors

Contributors are individuals who have made five (5) contributions to the project. Contributions can be a combination of: authoring PRs, commenting on issues and pull requests, creating blog posts and/or tutorials about Kyverno, and participating in community discussions on Slack or the mailing list.

**Checklist for becoming a Contributor**

- Have at least five (5) documented contributions:
  - Three (3) contributions must be successfully merged PRs for any repositories under the Kyverno organization.
  - The remaining two (2) contributions can be a combination of: successfully merged PRs, extensive collaboration on issues and/or other PRs authored by others, blog posts and/or tutorials about Kyverno authored by the Contributor, and/or participation in community discussions and support of other community members on our `#kyverno` channels on Kubernetes and/or CNCF Slack
- Member of the `#kyverno` channel on Kubernetes and/or CNCF Slack
- Attended one (1) Community or Maintainer Meeting as documented during the time your contributions were made
- Be a registered member of the Kyverno [mailing list](https://groups.google.com/g/kyverno)

**Privileges of a Contributor**

- Listed in the file in at least one (1) organization repository
- Kyverno Contributor badge issued via Credly
- Can be trusted to contribute safely and effectively

To join the Kyverno project as a Contributor create a Pull Request (PR) in the [Kyverno repository](https://github.com/kyverno/kyverno) with the following:
1. Changes to add yourself to the [CONTRIBUTORS.md](https://github.com/kyverno/kyverno/blob/main/CONTRIBUTORS.md) file
2. Links to your prior contributions (at least three (3) successfully merged PRs + another two (2) contributions as listed above)
3. Links to any contributions that were not PRs including slack discussions, issue comments, published blog posts, tutorials, etc.
4. Date of attendance at a Community and/or Maintainer Meeting

#### Reviewers

Reviewers are individuals who have already been accepted and are listed in the CONTRIBUTOR.md.

They make regular contributions, engage in issues, and participate in the community by providing support to others as needed. Reviewers are appointed by Maintainers based on their dedication and participation in the project.

**Checklist for becoming a Reviewer**

- Have completed all steps in the above mentioned Contributor guidelines
- Reviewed and contributed to multiple PRs across the codebase
- Active participation in community meetings and/or design discussions
- Clear communication and collaborative approach
- Demonstrates both deep understanding of the codebase and consistent high-quality contributions
- Actively reviews code from other contributors
- May be responsible for specific areas of the codebase as assigned by the Maintainer team (designated in CODEOWNERS)
- Appointed or nominated by a Maintainer

**Responsibilities of a Reviewer**

- Perform detailed code reviews and provide constructive feedback
- Ensure submitted code adheres to project style, testing, and documentation standards
- Collaborate with contributors to help improve pull requests before merging
- Communicate with Maintainers about any issues you encounter
- Participate actively in design discussions and community meetings
- Help triage issues and provide support in GitHub, Slack, or discussion forums
- Maintain awareness of project goals and architecture to ensure alignment
- Serve as a mentor to newer contributors
- Keep up-to-date with project changes and ongoing initiatives
- Represent the project in the community with professionalism and respect


**Privileges of a Reviewer**

- Triage access to the repository (e.g., labeling, assigning issues/PRs)
- Ability to formally approve pull requests (/lgtm, /approve where applicable)
- May be added to the CODEOWNERS file for designated areas of the codebase
- Recognition in the REVIEWERS.md and governance documents
- Eligibility for nomination to Maintainer roles
- Early access to roadmap discussions and design proposals
- Greater influence in shaping technical direction and priorities
- Invited to participate in exclusive contributor discussions (e.g., Maintainer syncs)

#### Maintainers

Maintainers are individuals who have shown good technical judgement in feature design/development in the past. Maintainers have overall knowledge of the project and features in the project. They can read, clone, and push to the repository. They can also manage issues, pull requests, and some repository settings.

Maintainers are the technical authority for a subproject and are considered leaders for the organization as a whole. They must have demonstrated both good judgement and responsibility towards the health of the subproject. Maintainers must set technical direction and make or approve design decisions for their subproject, either directly or through delegation of these responsibilities. Unlike contributors, maintainers have the highest degree of responsibility and ownership for the project. Maintainer status may be subject to a vote and, if the minimum level of activity is not maintained, may be moved to an _emeritus_ status.

**Checklist before becoming a Maintainer:**

- Have at least eight (8) to ten (10) significant PRs successfully merged for any combination of repositories under the Kyverno organization
- Member of the `#kyverno` and `#kyverno-dev` channels on Kubernetes Slack workspace and the `#kyverno` channel on the CNCF Slack workspace
- Regularly attends Kyverno [Maintainers and Community Meetings](https://kyverno.io/community/#community-meetings)
- Registered for the Kyverno [mailing list](https://groups.google.com/g/kyverno)
- Create a pull request to add self to `CODEOWNERS` file in at least one (1) repository
- Attained the super majority vote (50% + Nominator) from maintainers
- Respond to reviews from maintainers on pull requests
- Proficient in GitHub, YAML, Markdown, and Git
- Exhibits strong attention to detail when reviewing commits and provides generous guidance and feedback
- Helps others achieve their goals with open-source and community contributions
- Understands the workflow of the Issues and Pull Requests
- Makes consistent contributions to the Kyverno project
- Consistently initiates and participates in [Kyverno discussions](https://slack.k8s.io/#kyverno)
- Has knowledge and interest that aligns with the overall project goals, specifications, and design principles of the Kyverno project
- Makes contributions that are considered notable
- Demonstrates ability to help troubleshoot and resolve user issues
- Has achieved the Kyverno Certification or demonstrated an equivalent mastery of Kyverno
- Maintains a consistent level of activity with contributions to the project

**Responsibilities of a Maintainer**

- Tracks and ensures adequate health of the modules and subprojects they are in charge of
- Ensures adequate test coverage to confidently release new features and fixes
- Ensures that tests are passing reliably (i.e. not flaky) and are fixed when they fail
- Mentors and guides code owners, reviewers, and contributors
- Actively participates in the processes for discussion and decision making in the project
- Merges Pull Requests and helps prepare releases
- Makes and approves technical design decisions for the subproject
- Helps define milestones and releases
- Decides on when PRs are merged to control the release scope
- Works with other maintainers to maintain the project's overall health and success holistically

**Privileges of a Maintainer**

- Listed as an organization member
- Listed in `CODEOWNERS` in at least one (1) repository
- Member of the https://lists.cncf.io/g/cncf-kyverno-maintainers mailing list
- Have issues assigned to them
- Have PRs assigned to them
- Receives a Kyverno Maintainer Badge
- Listed in `MAINTAINERS.md`

**On-boarding Criteria**

- Nominated by current Maintainer and voted in by a majority of current maintainers or raised in a PR by the proposed member to add themselves to `MAINTAINERS.md`, during a voting period lasting at least three (3) working days

**Off-boarding Criteria**

An off-boarding vote may be called by any maintainer if any of the following criteria are met:
- A maintainer has made less than 30 contributions over a span of 6 months.
  - Contributions can be tracked using the [DevStats dashboard](https://kyverno.devstats.cncf.io/d/66/developer-activity-counts-by-companies?orgId=1&var-period_name=Last%206%20months&var-metric=contributions&var-repogroup_name=All&var-country_name=All&from=1522810884223&to=1680577284223&var-companies=All).
  - Other relevant data will be collected and evaluated to assess the maintainer's contributions. This includes their involvement in discussions, conversations on Slack, and any other relevant interactions.

The off-boarding process includes the following steps:
- The off-boarding process is initiated by any currently active maintainer who conducts a review of the maintainers list and proceeds to initialize the off-boarding process if the above criteria are met.
- The plans of off-boarding process is sent in a private Slack message or email to the candidate.
- If the candidate for removal states plans to continue participating, another 6 months will be granted to the candidate to make contributions and the new cycle starts. No action is taken and this process terminates.
- If the candidate fails to meet the criteria during the second attempt to make contributions, the off-boarding process continues.
- A pull request (PR) proposing movement of the candidate is sent, initiating the public voting phase.
- The vote passes if a majority of current maintainers vote yes during a voting period lasting five (5) working days.
- A positive vote will result in movement to an _emeritus_ status within `MAINTAINERS.md` and removal from organization membership.

#### Progression Process

Progression to a new role requires an appointment or nomination by an existing Maintainer. All role appointments and nominations are subject to a vote.
- All role appointments, nominations, and votes must be documented in a GitHub issue or pull request
- Contributions across any Kyverno sub-projects count toward progression. The list of acceptable contributions is listed above.

#### Benefits of the Contributor Ladder

The Contribution Ladder is meant to provide clear expectations and transparency for how to grow within the project and ensure that all contributors are recognized for their efforts, commitment, and support of our community ensuring contributor growth and project sustainability.

#### Mapping Project Roles to GitHub Roles

The roles used in this document are custom roles mapped according to the [GitHub roles and responsibilities](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization).

| Project Role       | GitHub Role    |
| ------------------ | -------------- |
| New Contributor    | None           |
| Contributor        | None           |
| Reviewer           | Write          |
| Maintainer         | Maintain       |

### Off-boarding Guidance

If any of the above roles hasn't contributed in any phases (including, but not limited to: code changes, doc updates, issue discussions) in 3 months, the administrator needs to inform the member and remove one's roles and GitHub permissions.

## Maintainer Areas

The Kyverno projects code base cover many areas and project maintainers are not required to know everything about a project.
For this reason, maintainers can be specific to one (or more) area of the code base, every area representing a specific aspect.

### Kyverno Projects

- [Kyverno](https://github.com/kyverno/kyverno)
- [Kyverno Website](https://github.com/kyverno/website)
- [Kyverno Policies](https://github.com/kyverno/policies)
- [Kyverno JSON](https://github.com/kyverno/kyverno-json)
- [Kyverno Chainsaw](https://github.com/kyverno/chainsaw)
- [Kyverno Playground](https://github.com/kyverno/playground)
- [Kyverno Policy Reporter](https://github.com/kyverno/policy-reporter)
- [Kyverno Reports Server](https://github.com/kyverno/reports-server)
- [Kyverno Backstage Policy Reporter](https://github.com/VELUX/backstage-policy-reporter-plugin)

### Projects areas

This list is not exhaustive and is subject to modifications as the project evolves over time.

| Project | Area | Description |
|---|---|---|
| Kyverno | `website` | Kyverno projects website and docs |
| Kyverno | `policies-catalog` | Kyverno currated policies |
| Kyverno | `helm-chart` | Kyverno Helm chart |
| Kyverno | `engine` | Kyverno policy engine |
| Kyverno | `cli` | Kyverno CLI |
| Kyverno | `report-system` | Kyverno reporting system |
| Kyverno JSON | -- | Kyverno JSON project |
| Kyverno Chainsaw | -- | Kyverno Chainsaw project |
| Kyverno Playground | `frontend` | Kyverno Playground frontend |
| Kyverno Playground | `backend` | Kyverno Playground backend |
| Kyverno Playground | `helm-chart` | Kyverno Playground Helm chart |
| Kyverno Policy Reporter | `frontend` | Kyverno Policy Reporter frontend |
| Kyverno Policy Reporter | `backend` | Kyverno Policy Reporter backend |
| Kyverno Policy Reporter | `helm-chart` | Kyverno Policy Reporter Helm chart |
| Kyverno Reports Server | -- | Kyverno Reports Server project |
| Kyverno Backstage Policy Reporter | `frontend` | Kyverno Backstage Policy Reporter frontend |
| Kyverno Backstage Policy Reporter | `backend` | Kyverno Backstage Policy Reporter backend |

## Conflict Resolutions

Typically, it is assumed that disputes will be resolved amicably by those involved. However, if the situation becomes more serious, conflicts will be resolved through a voting process. A supermajority of votes from project maintainers is required to make a decision, and the project lead has the final say in the ruling.

## Changes

This Project Governance is a living document. All key project changes including changes in project governance can be proposed by a GitHub PR and then reviewed and voted on by project maintainers.

## Credits

Sections of this document have been borrowed from the [CoreDNS](https://github.com/coredns/coredns/blob/master/GOVERNANCE.md) and [fluxcd](https://github.com/fluxcd/community/blob/main/GOVERNANCE.md) projects.
