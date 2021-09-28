# Community Membership

All contributors should be welcomed to the community by existing members, helped with PR workflow, and directed to relevant documentation and communication channels.

This doc outlines the various responsibilities of contributor roles in
KubeVela. Note :This document keeps changing based on the status and feedback from Community.

| Role | Responsibilities | Requirements | Defined by |
| -----| ---------------- | ------------ | -------|
| Member | Active contributor in the community | have made multiple contributions to the project | OAM GitHub org member|
| Reviewer | Review contributions |  Active contributor and/or code reviewer. Contributed with major features | [OWNERS] file reviewer entry |
| Approver | Contributions acceptance approval| Highly experienced active reviewer and contributor | [OWNERS] file approver entry|
| maintainer | Set direction and priorities | Demonstrated responsibility and excellent technical judgement | [OWNERS] file maintainer entry |

A new contributor's role should be promoted in sequence, beginning with a member until to be a maintainer.

## Member
Members are continuously active contributors in the community. They can have issues and PRs assigned to them. Members are expected to remain active contributors to the community.

### Requirements
- Have made multiple contributions to the project or community. **Submitted 5 coding PRs or 5 doc PRs**. 
- Contribution may include, but is not limited to:
   - Authoring or reviewing PRs on GitHub
   - Filing or commenting on issues on GitHub
   - Contributing to community discussions (e.g. meetings, discussion group)
- **Sponsored by 2 reviewer/approver/maintainer**
   - **With no objections from other reviewers**
   - Done through a issue to request for joining the org

### Responsibilities and privileges
- **Be a Member of OAM GitHub organization**
- Responsive to issues and PRs assigned to them
- Active owner of code they have contributed (unless ownership is explicitly transferred)
   - Code is well tested
   - Tests consistently pass
   - Addresses bugs or issues discovered after code is accepted

## Reviewer
Reviewers are able to review code for quality and correctness. They are knowledgeable about both the codebase and software engineering principles.

### Requirements
- **Primary reviewer for at least 5 PRs to the codebase**
- Knowledgeable about the codebase
- **Sponsored by 2 approver/maintainer**
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
Code approvers are able to both review and approve code contributions. While code review is focused on code quality and correctness, approval is focused on holistic acceptance of a contribution including: backwards / forwards compatibility, adhering to API and flag conventions, subtle performance and correctness issues, interactions with other parts of the system, etc.

### Requirements
- **Primary reviewer for at least 10 substantial PRs to the codebase**
- **Reviewed or merged at least 20 PRs to the codebase**
- **Sponsored by 2 maintainer**
   - **With no objections from other maintainer**
   - Done through PR to update the OWNERS file

### Responsibilities and privileges
- Demonstrate sound technical judgement
- Responsible for project quality control
   - Focus on holistic acceptance of contribution such as dependencies with other features, backwards / forwards compatibility, API and flag definitions, etc
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
   - Identifying subtle or complex issues in designs and implementation PRs
- **Sponsored by majority vote 2/3 of maintainers**

### Responsibilities and privileges
- Make and approve technical design decisions
- Set technical direction and priorities
- Define milestones and releases.
- Mentor and guide approvers, reviewers, and members
- Ensure continued health of project
   - Adequate test coverage to confidently release
   - Tests are passing reliably (i.e. not flaky) and are fixed when they fail
- Ensure a healthy process for discussion and decision making is in place.
- Work with other owners to maintain the project's overall health and success holistically