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
  - [Kyverno Steering and Oversight Committee - KSOC] (#kyverno-steering--oversight-committee-ksoc)
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

# Kyverno Steering & Oversight Committee (KSOC)

  
### Purpose

The purpose of the Steering & Oversight Committee (“the Committee”) is to provide an invite-only, external-facing governance body that

-   helps ensure Kyverno remains sustainably maintained, healthy and relevant in the cloud-native ecosystem,  
      
    
-   provides a venue for diverse end-user, ecosystem and stakeholder voices to have strategic input into the project’s direction,  
      
    
-   acts as a promoter and ambassador for the project—helping raise awareness, drive adoption, surface feedback, and connect users to development, and  
      
    
-   serves as a check and balance on day-to-day project operations (while not interfering with the operational flows of the maintainers) by offering guidance on long-term strategy, project health and ecosystem fit.  
      
    

In short: the Committee is not the “maintainers’ board” dictating every pull request or commit, but rather a strategic oversight and advisory body whose members are committed to the project’s long-term success and sustainability.

### Scope & Responsibilities

The Committee will undertake the following responsibilities:

-   Strategic Review: At least annually, review the project’s roadmap, major milestones, health metrics (e.g., contributor growth, issue backlog, release cadence) and advise on strategic direction.  
      
    
-   Ecosystem / End-User Voice: Provide input from end-users, ecosystem partners, large users of Kyverno, CNCF-adjacent projects, or vendor/partner organisations. Bring real-world feedback into the project.  
      
    
-   Advocacy & Promotion: Serve as ambassadors for Kyverno—promoting the project inside their organisations, at conferences, in the cloud-native ecosystem; raising visibility; helping drive adoption and ecosystem partnerships.  
      
    
-   Sustainability Oversight: Monitor long-term sustainability of the project (maintenance, documentation, community health, funding/sponsorship where relevant). Provide guidance if the project risks stagnation or becoming orphaned.  
      
    
-   Governance Liaison: Act as a bridge between the broader user/consumer community and the project maintainers. Provide a forum for larger organisational users of Kyverno to engage with the project direction in a structured way.  
      
    
-   Advisory Role: Provide advice and feedback to the maintainers or project leadership (e.g., the core maintainers team, working group leads) on decisions that have a broad ecosystem impact—such as changes to governance, major API/behaviour changes, deprecation plans, compatibility commitments, etc.  
      
    
-   No Day-To-Day Execution: The Committee does not manage day-to-day code review, ticket triage, maintainers’ assignments or handle routine operations of the project. Those remain with the maintainers and working groups.  
      
    

### Composition & Membership

#### 3.1 Membership

-   The Committee shall consist of 5 - 7 members invited by the maintainers / governance team.  
      
    
-   Membership is by nomination and a simple majority of votes from the project Maintainers. For each nomination, an open voting process will take place for Maintainers to vote and other community members to show their support of each nominee.
    
-   Nominations are extended to individuals/organisations who are:  
      

-   Significant end-users of Kyverno (e.g., large organisations or teams that run Kyverno at scale)  
      
    
-   Ecosystem partners/integrators (e.g., vendors, service providers, cloud providers who embed or support Kyverno)  
      
    
-   Distinguished contributors or thought-leaders in the cloud-native policy, Kubernetes, or infrastructure as code space, especially those outside the core maintainers.  
      
    
-   Champions of sustainability, diversity and community health in open-source projects.  
      

-   Each member serves a term of (6) six months, renewable at the maintainers’discretion. Members may serve multiple terms. Membership is voluntary and unpaid. 
    
-   The maintainers may appoint a committee “chair” or “rotating facilitator” (see Section 4).  
      
    

#### Eligibility & Conflicts of Interest

-   Members must abide by the project’s Contributor / Code of Conduct and governance policies.  
      
    
-   Members should disclose any significant conflicts of interest (e.g., their organisation offering a commercial product built on Kyverno, or competing policy-engine vendors). The Committee may adopt a simple conflict-disclosure policy (e.g., list anything relevant in a publicly published members list).  
      
    
-   If a member becomes inactive (fails to attend > 2 consecutive meetings without excuse) or their organisation’s alignment with the project changes significantly, the maintainers may propose replacement.  
      
    
### Meetings & Logistics

#### 4.1 Frequency & Format

-   The Committee shall meet quarterly, i.e., (4) four times per year. Additional ad-hoc meetings may be convened as needed (e.g., major governance or ecosystem issues).  
      
    
-   Meetings are held virtually (via video conference) unless otherwise agreed; an in-person meeting at a major conference (e.g., KubeCon) may be scheduled annually if feasible.  
      
    
-   Meeting length: ~1 hour, plus pre-circulated agenda and materials.  
      
    
-   Meeting notes (agenda, minutes, action items) shall be recorded in the project repository (e.g., in governance/STEERING-COMMITTEE/ folder) and publicly visible (unless sensitive matters require confidential handling).  
      
    
-   A quorum for decisions (recommendations) is half the full membership rounded up (for example, if there are an even number of members e.g. 10 members, quorum = 6). Outcome decisions require a simple majority of attending members when quorum is met.  
      
    

#### 4.2 Agenda & Materials

-   The project community leadership shall prepare and circulate the agenda at least 5 business days before each meeting, along with relevant materials (roadmaps, metrics, proposed major changes).  
      
    
-   Members may request agenda items by submitting them to the liaison at least 7 days before the meeting.  
      
    
-   Meetings typically review:  
      

-   Project status update (metrics, highlights, challenges)  
      
    
-   Roadmap review and strategic discussion  
      
    
-   Ecosystem / end-user feedback  
      
    
-   Sustainability / health issues (contributors, backlog, docs, technical debt)  
      
    
-   Open agenda: members raise topics  
      
    
-   Action-item summary & next steps.  
      
    

#### 4.3 Decision-Making & Recommendations

-   The Committee is advisory, not governance-executive: it issues recommendations to the project maintainers / governing body, who retain operational authority.  
      
    
-   Recommendations may be documented publicly (e.g., as a “Steering Committee Recommendation” note) and the maintainers will publicly note responses (accepted, under review, or declined + rationale).  
      
    
-   If a matter is urgent between scheduled meetings, the chair (or liaison) may convene a special meeting or poll asynchronously by email/slack with a shorter timeframe; same quorum rule applies.  
      

#### 4.4 Liaison & Secretariat

-   A designated Community lead shall serve as the Committee liaison (the “Secretariat”). The liaison is responsible for:  
        

-   Scheduling meetings, sending agenda and materials  
      
    
-   Taking minutes and tracking action items  
      
    
-   Publishing minutes and updates to the project repository  
      
    
-   Coordinating follow-up with maintainers, and tracking how Committee recommendations are addressed.  
      


#### 4.5 Publication & Transparency

-   The list of Committee members, terms, conflicts disclosures (if any) and meeting minutes shall be publicly visible in the project governance folder (e.g., governance/STEERING-COMMITTEE.md and linked sub-folder).  
      
    
-   Confidential matters (if any) must be clearly flagged; however, the default expectation is transparency to maintain trust.  
      
    
-   Major recommendations (and maintainer responses) may also be reflected in the public project roadmap or governance updates.  
      
    

### Recruitment & Termination

#### 5.1 Recruitment Process

-   The maintainers (or governance working group) shall maintain a short-list of potential invitees (based on diversity of organisations, geographies, end-user vs ecosystem partner roles, gender/under-represented groups, and varied user-scenarios).  
      
    
-   Invitations shall be extended by the maintainers, with a brief welcome letter explaining the role, term, expected time commitment, and giving the invitee a 2-week period to accept.  
      
    
-   Once accepted, the member’s name, affiliation, term start date and (optional) conflict disclosure shall be added to the public Committee roster.  
      
    

#### 5.2 Termination / Exit

-   A member’s term ends after the two-year period (unless renewed). At least 2 months before end-of-term, the liaison will ask if the member wishes to renew (and maintainers will evaluate).  
      
    
-   If a member fails to respond after 2 reminders, or misses >2 consecutive meetings without valid excuse, the liaison may propose a replacement.  
      
    
-   A member may resign at any time (by sending notice to the liaison).  
      
    
-   The maintainers may remove a member for cause (e.g., repeated failure to participate, breach of code of conduct, significant conflict of interest) after consulting the chair and liaison; in such cases a replacement may be appointed early.  
      
    

#### 5.3 Succession & Replacement

-   When a membership vacancy arises (end-term, resignation, removal), the maintainers will select a replacement from the short-list (or extend new invitation), giving priority to ensuring representation balance (organisation type, region, user vs ecosystem).  
      
    
-   The new member will serve a full two-year term (or the remainder of the outgoing member’s term, per policy) and then be eligible for renewal under the same rules.  
      
    

### Relationship to Project Governance

-   The Committee complements (but does not replace) existing project governance structures (maintainers, working groups, SIGs, codeowners, issue triage, etc).  
      
    
-   The Committee’s recommendations are not binding, but the maintainers commit to publicly respond to each recommendation (accept/under-consideration/decline with rationale).  
      
    
-   The Committee may review governance changes (e.g., major changes in maintainers’ process, code-owner policy, contributor rights) and provide input.  
      
    
-   The project maintainers remain responsible for day-to-day decisions, code merges, release management, issue backlog, contributor onboarding, etc.  
      
    

### Confidentiality & Public-Facing Role

-   Because members are often associated with organisations and may have privileged insight into roadmap or sponsorship matters, some Committee discussions (e.g., future funding, commercial partnerships) may be held under “committee confidentiality”. The liaison will clearly mark which agenda items are confidential.  
      
    
-   Even when discussions are confidential, minutes should summarise outcomes (even if lacking full detail) and recommendations for transparency.  
      
    
-   Members must abide by confidentiality when so marked — e.g., not disclosing embargoed announcements or partner deals.  
       

### Amendment & Review

-   This Committee charter may be reviewed annually (by the maintainers + Committee) and amended by the maintainers in consultation with the Committee.  
      
    
-   Any amendment shall be published in the project governance folder, with version, date and summary of changes.

## Conflict Resolutions

Typically, it is assumed that disputes will be resolved amicably by those involved. However, if the situation becomes more serious, conflicts will be resolved through a voting process. A supermajority of votes from project maintainers is required to make a decision, and the project lead has the final say in the ruling.

## Changes

This Project Governance is a living document. All key project changes including changes in project governance can be proposed by a GitHub PR and then reviewed and voted on by project maintainers.

## Credits

Sections of this document have been borrowed from the [CoreDNS](https://github.com/coredns/coredns/blob/master/GOVERNANCE.md) and [fluxcd](https://github.com/fluxcd/community/blob/main/GOVERNANCE.md) projects.
