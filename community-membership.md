# Community Membership

All contributors should be welcomed to the community by existing members, helped with PR workflow, and directed to relevant documentation and communication channels.

This table outlines the various responsibilities of contributor roles in KubeVela.

The Apache way says Community Over Code. Although KubeVela is a CNCF/Linux project, we possess a strong resonance to it. To second and stretch this merit deeper, we regard non-coding contribution as equally important to the community's very existence and its future growth. Current core community members will be deciding whereas these non-coding contribution is valid enough to be a Member, Reviewer, Approver or Maintainer.

| Role | Responsibilities | Requirements | Defined by |
| -----| ---------------- | ------------ | -------|
| Member | Active participation in the community | have made multiple contributions to the project | KubeVela GitHub org member|
| Reviewer | Review contributions |  Active contributor and/or code reviewer. Responsible for major features | [OWNERS](./OWNERS.md#reviewers) file reviewer entry |
| Approver | Approve and commit contributions | Highly experienced active reviewer and contributor. On charge of certain project domain(s) | [OWNERS](./OWNERS.md#approvers) file approver entry|
| Maintainer | Set direction and priorities | Demonstrated responsibility and excellent technical judgement | [OWNERS](./OWNERS.md#maintainers) file maintainer entry |

## Member
Members are continuously active contributors in the community. They can have issues and PRs assigned to them. Members are expected to remain active contributors to the community.

### Requirements
- Have made multiple contributions to the project or community.
- **Submitted 1 coding PR or 3 doc PRs**.
- **Equivalent non-coding devotion, such as Spec model contribution, community management, developer advocate, and etc.**
- Contribution may include, but is not limited to:
   - Authoring or reviewing PRs on GitHub
   - Filing or commenting on issues on GitHub
   - Contributing to community discussions (e.g. meetings, discussion groups)
- **Sponsored by 2 reviewers**
   - **With no objections from other reviewers**
   - Done through an issue to request joining the org

### Responsibilities and privileges
- **Being a Member of KubeVela GitHub organization**
- Responsive to issues and PRs assigned to them
- Active owner of the code they have contributed (unless ownership is explicitly transferred)
   - Code is well tested
   - Tests consistently pass
   - Addresses bugs or issues discovered after code is accepted

## Reviewer
Reviewers are able to review code for quality and correctness. They are knowledgeable about both the codebase and software engineering principles.
### Requirements
- **Primary reviewer for at least 3 PRs to the codebase**
- **Equivalent non-coding devotion, such as Spec model contribution, community management, developer advocate, and etc.**
- Knowledgeable about the codebase
- Triage issue into further steps
- **Sponsored by 2 approvers**
   - **With no objections from other approvers**
   - Done through PR to update the OWNERS file

### Responsibilities and privileges
- Responsible for project quality control
   - Focus on code quality and correctness, including testing and factoring
   - May also review for more holistic issues, but not a requirement
- Expected to be responsive to review requests
- Assigned PRs to review related to reviewer's expertise
- Assigned test bugs related to reviewer's expertise

## Approver
Code approvers are able to both review and approve code contributions. While code review is focused on code quality and correctness, approval is focused on holistic acceptance of a contribution, including backwards / forwards compatibility, adhering to API and flag conventions, subtle performance and correctness issues, interactions with other parts of the system, and etc.
They are also on charge of certain areas in KubeVela.

### Requirements
- **Primary reviewer for 20 substantial effort/large labelled PRs to the codebase**
- **Equivalent non-coding devotion, such as Spec model contribution, community management, developer advocate, and etc.**
- **Sponsored by 2 maintainers**
   - **With no objections from other maintainer**
   - Done through PR to update the OWNERS file

### Responsibilities and privileges
- Demonstrate sound technical judgement
- Triage issue into further steps
- Responsible for project quality control
   - Focus on holistic acceptance of contributions, such as dependencies with other features, backwards / forwards compatibility, API and flag definitions, and etc
- Expected to be responsive to review requests
- Mentor members and reviewers

## Maintainer
### Requirements
The Maintainers are typically limited to a relatively small group of decision makers.
- Deep understanding of the technical goals and direction
- Deep understanding of the technical domain
- Sustained contributions to design and direction by doing all of:
   - Authoring and reviewing proposals
   - Initiating, contributing and resolving discussions (emails, GitHub issues, meetings)
   - Identifying subtle or complex issues in designs and their implementation PRs
- **Equivalent non-coding devotion, such as Spec model contribution, community management, developer advocate, and etc.**
- **Sponsored by the majority of maintainers (2/3)**

### Responsibilities and privileges
- Make and approve technical design decisions
- Set technical direction and priorities
- Define milestones and releases.
- Mentor and guide approvers, reviewers, and members
- Ensure continued health of project
   - Adequate test coverage to confidently release
   - Tests are passing reliably (i.e. not flaky) and are fixed when they fail
- Ensure a healthy process for discussions and decision-making is in place.
- Work with other owners to maintain the project's overall health and success holistically

## Inactive members

A core principle in maintaining a healthy community is encouraging active
participation. It is inevitable that people's focuses will change over time, and
they are not expected to be actively contributing forever.

Therefore, members with an extended period away from the project with no activity
will be removed from the KubeVela GitHub Organizations and will be required to
go through the org membership process again after re-familiarizing themselves
with the current state.


### How inactivity is measured

Inactive members are defined as members of one of the KubeVela Organizations
with **no** contributions across any organization within **6 months**. This is
measured by the CNCF [DevStats project].

**Note:** DevStats does not take into account non-code contributions. If a
non-code contributing member is accidentally removed this way, they may open an
issue to quickly be re-instated.

After an extended period away from the project with no activity,
those members would need to re-familiarize themselves with the current state
before being able to contribute effectively.
