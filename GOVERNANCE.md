# Governance

This document describes the governance process under which the KubeVela community will manage all repositories inside the organizations.

## Code of Conduct

The KubeVela community abides by the [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/master/code-of-conduct.md). 

As a member of the KubeVela project, you represent the project and your fellow contributors. We value our community tremendously and we would like to keep cultivating a friendly and collaborative environment for our contributors and users. We want everyone in the community to have positive experiences.

## Meetings

- KubeVela currently hosts [weekly community meetings](https://github.com/kubevela/community#community-meetings) that are open to the public. 
- The meetings serve as a primary source to present, discuss, and review PRs that have been merged or are in the process of being merged to the projects under KubeVela org. 
- It is strongly suggested and encouraged that offline reviews are undertaken to gauge the group's opinion on the proposed change before the meeting. Comments on the PRs will foster communication and might accelerate and ease the review process.
- During meetings, priority will be given to PRs that appear to need discussion over those that can be handled offline. 
- Not every PR has to be discussed in an online meeting to be merged. 
- Non-substantial PRs (e.g., fixing of typos, small bug fixes) might be processed offline without being mentioned in an online meeting.

## Contributing 

The process of contributing to KubeVela is described in the [Contributing document](https://kubevela.io/docs/contributor/overview). We encourage you to take a look at it before opening a PR.

The document explains in detail how to get started, and describes the process for getting your change merged into the KubeVela projects.

### KubeVela Enhancement Proposals

Proposing new functionality for KubeVela is a transparent process done via a so-called [KubeVela Enhancement Proposal](https://github.com/kubevela/kubevela/tree/master/design).
This is required when the proposed functionality is intended to introduce new behaviour, change desired behaviour, or otherwise modify the requirements of KubeVela.

If all you want to propose is a simple addition to KubeVela or the CLI, or even a bugfix, you can just open [a new issue on GitHub](https://github.com/kubevela/kubevela/issues/new/choose).

## Membership

The KubeVela community membership is defined in the [KubeVela Community Membership document](https://github.com/kubevela/community/blob/main/community-membership.md). 

The KubeVela project maintains three levels of membership with increasing responsibilities. The three levels as well as the requirements are described in more detail in the linked document.

[Project maintainers](https://github.com/kubevela/community/blob/main/OWNERS.md#maintainers) are responsible for activities around maintaining and updating KubeVela. Final decisions on the project reside with the project maintainers.

Maintainers **MUST** remain active. If they are unresponsive for >6 months, they will be automatically removed unless a [super-majority](https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote) of the other project maintainers agrees to extend the period to be greater than 6 months.

New maintainers can be added to the project by a [super-majority](https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote) vote of the existing maintainers.
A potential maintainer may be nominated by an existing maintainer.
A vote is conducted in private between the current maintainers over the course of a one week voting period.
At the end of the week, votes are counted and a pull request is made on the repo adding the new maintainer to the [CODEOWNERS](https://github.com/kubevela/kubevela/blob/master/.github/CODEOWNERS) file.

A maintainer may step down by submitting an [issue](https://github.com/kubevela/kubevela/issues/new/choose) stating their intent.

Changes to this governance document require a pull request with approval from a [super-majority](https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote) of the current maintainers.

## Handling Security Vulnerabilities

The process for handling any security vulnerabilities or concerns found in the KubeVela project is described in the [Security document](https://github.com/kubevela/kubevela/blob/master/SECURITY.md). 

## Releases

A new KubeVela version is released once substantial new features, bug fixes, and/or security hardenings have been merged into the master branch, resulting in a non-fixed release schedule. Nevertheless, the KubeVela project aims for one major/minor version at least once every 2 months. Patch versions might be released more frequently. Only maintainers can do the releases. More details of the release cadence can be found [here](https://kubevela.net/docs/contributor/release-process).

### Resources

We borrowed parts of this document and inspiration from the sources listed below.

- https://github.com/keptn/keptn/blob/master/GOVERNANCE.md
- https://github.com/grpc/grpc-community/blob/master/governance.md
