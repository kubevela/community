# Community Membership

All contributors should be welcomed to the community by existing members, helped with PR workflow, and directed to relevant documentation and communication channels.

This table outlines the various responsibilities of contributor roles in
KubeVela.

The Apache way says Community Over Code. Although KubeVela is a CNCF/Linux project, we possess a strong resonance to it. To second and stretch this merit deeper, we regard non-coding contribution as equally important for the community's very existence and it future growth. Current core community members will be deciding whereas these non-coding contribution is valid enough to be a Member, Reviewer, Approver or Maintainer.

| Role | Responsibilities | Requirements | Defined by |
| -----| ---------------- | ------------ | -------|
| Member | Active participation in the community | have made multiple contributions to the project | OAM GitHub org member|
| Reviewer | Review contributions |  Active contributor and/or code reviewer. Responsible for major features | [OWNERS_ALIASES](https://github.com/oam-dev/kubevela/blob/master/OWNERS_ALIASES) file reviewer entry |
| Approver | Approve and commit contributions | Highly experienced active reviewer and contributor. On charge of certain project domain(s) | [OWNERS_ALIASES](https://github.com/oam-dev/kubevela/blob/master/OWNERS_ALIASES) file approver entry|
| Maintainer | Set direction and priorities | Demonstrated responsibility and excellent technical judgement | [OWNERS_ALIASES](https://github.com/oam-dev/kubevela/blob/master/OWNERS_ALIASES) file maintainer entry |

## Member
Members are continuously active contributors in the community. They can have issues and PRs assigned to them. Members are expected to remain active contributors to the community.

### Requirements
- Have made multiple contributions to the project or community.
- **Submitted 1 coding PRs or 3 doc PRs**.
- **Equivalent non-coding devotion, such as Spec model contribution or community management or developer advocate and etc.**
- Contribution may include, but is not limited to:
   - Authoring or reviewing PRs on GitHub
   - Filing or commenting on issues on GitHub
   - Contributing to community discussions (e.g. meetings, discussion group)
- **Sponsored by 2 reviewer**
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
- **Primary reviewer for at least 3 PRs to the codebase**
- **Equivalent non-coding devotion, such as Spec model contribution or community management or developer advocate and etc.**
- Knowledgeable about the codebase
- Triage issue into further steps
- **Sponsored by 2 approver**
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
Also they are on charge of certain product area in KubeVela.

### Requirements
- **Primary reviewer for 20 substantial effort/large labled PRs to the codebase**
- **Equivalent non-coding devotion, such as Spec model contribution or community management or developer advocate and etc.**
- **Sponsored by 2 maintainer**
   - **With no objections from other maintainer**
   - Done through PR to update the OWNERS file

### Responsibilities and privileges
- Demonstrate sound technical judgement
- Triage issue into further steps
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
- **Equivalent non-coding devotion, such as Spec model contribution or community management or developer advocate and etc.**
- **Sponsored by majority vote(2/3) of maintainers**

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

## Inactive members

A core principle in maintaining a healthy community is encouraging active
participation. It is inevitable that people's focuses will change over time and
they are not expected to be actively contributing forever.

Therefore members with an extended period away from the project with no activity
will be removed from the OAM Github Organizations and will be required to
go through the org membership process again after re-familiarizing themselves
with the current state.


### How inactivity is measured

Inactive members are defined as members of one of the OAM Organizations
with **no** contributions across any organization within **6 months**. This is
measured by the CNCF [DevStats project].

**Note:** Devstats does not take into account non-code contributions. If a
non-code contributing member is accidentally removed this way, they may open an
issue to quickly be re-instated.

After an extended period away from the project with no activity
those members would need to re-familiarize themselves with the current state
before being able to contribute effectively.
