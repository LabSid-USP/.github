# LabSid Contributor Guide

Welcome to LabSid! This document is the single source of truth for how to
contribute to the code base.

## Code attribution

[License information](README.md#License) should be included in all source files where applicable.

## Code of Conduct

Please make sure to read and observe our [Code of
Conduct](https://github.com/LabSid-USP/.github/blob/main/CODE_OF_CONDUCT.md).

# Your First Contribution

## Find something to work on

Help is always welcome! For example, documentation (like the text you are
reading now) can always use improvement. There's always code that can be
clarified and variables or functions that can be renamed or commented. There's
always a need for more test coverage. You get the idea: if you ever see
something you think should be fixed, you should own it.

### Find a good first topic

There are multiple repositories within the LabSid organization. Each
repository has beginner-friendly issues that provide a good stepping stone to
larger contributions.

## GitHub workflow

To check out code to work on, please refer to [the GitHub Workflow
Guide](https://github.com/kubernetes/community/blob/master/contributors/guide/github-workflow.md)
from Kubernetes. LabSid uses the same workflow. One of the main
highlights - all the work should happen on forks, to minimize the number of
branches on a given repository.

## Open a Pull Request

Pull requests are often called simply "PR". LabSid follows the standard
[github pull request](https://help.github.com/articles/about-pull-requests/)
process.

Common new contributor PR issues are:

- following any repository specific contributing guidelines (see
  CONTRIBUTING.md of the corresponding repository)
- dealing with test cases which fail on your PR, unrelated to the changes you
  introduce

## Code Review

There are two aspects of code review: giving and receiving.

To make it easier for your PR to receive reviews, consider the reviewers will
need you to:

- follow the project and repository coding conventions
- write [good commit messages](https://chris.beams.io/posts/git-commit/)
- break large changes into a logical series of smaller patches which
  individually make easily understandable changes, and in aggregate solve a
  broader issue
- label PRs with appropriate reviewers

Reviewers, the people giving the review, are highly encouraged to revisit the
[Code of
Conduct](https://github.com/LabSid-USP/.github/blob/main/CODE_OF_CONDUCT.md)
and must go above and beyond to promote a collaborative, respectful community.

When reviewing PRs from others [The Gentle Art of Patch
Review](https://sage.thesharps.us/2014/09/01/the-gentle-art-of-patch-review/)
suggests an iterative series of focuses which is designed to lead new
contributors to positive collaboration without inundating them initially with
nuances:

- Is the idea behind the contribution sound?
- Is the contribution architected correctly?
- Is the contribution polished?

Note: if your pull request isn't getting enough attention, you can explicitly
mention approvers or maintainers of this repository.
