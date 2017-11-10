# Reviewing Azure Helm Charts Code

This is a guide for reviewers of pull requests (PRs) and code in this repository.

When a pull request is submitted (see 
[the contributing document](./contributing.md) for more details on the PR process),
the maintainers of this repository ("reviewers" hereafter) are responsible 
for reviewing and merging it.

# General Responsibilities

Reviewers have the following general responsibilities:

- Ensuring that the code is easy to read and of generally good quality
- Ensuring that tests pass
- Ensuring that documentation (in YAML or otherwise) is clear and complete
- Ensuring that no harmful changes are made to the charts

Above everything else, reviewers should provide their feedback in a constructive, respectful
manner that encourages future contributions and provides a safe, comfortable and efficient
community.

# Review Process

Azure Helm Charts Broker have not yet reached a 1.0 release, so we, the maintainers, believe
that quality, efficiency, and velocity are important (in that order of importance).

As such, we've defined a few categories of PRs and their review requirements:

- Documentation only: These require a single review. Special care should be taken
for documentation clarity, accuracy and grammar. If the reviewer is unsure of 
some part of the documentation, they should reach out to either the contributor
 or someone else they know has knowledge on the subject
- Small: While we don't have exact measurements to determine whether a PR is small,
these PRs generally span no more than a few files or represent a mechanical change
(even if it may be across many files, like a rename). These require a single review
- Medium: While we don't have exact measurements to determine whether a PR is medium, 
these PRs generally span a only a single chart. Medium PRs require a 
single review by a reviewer familiar with the areas of concern
- Large: Large PRs generally span a large portion of the project, or add or remove
a chart. These generally require two reviews, but the first reviewer may 
decide that they can review it without a second review if they are familiar with
the changes.

A few additional notes:

- We do not make a distinction between modified, deleted or added lines
- Maintainers sometimes submit small PRs, often for administrative purposes
(i.e. fixing a typo in a document or modifying a script for CI). In these cases,
a maintainer may merge these PRs without review. Maintainers must use their best
judgement to decide whether these kinds of PRs need a separate review or not.
- Maintainers may merge their own PRs after reviews are completed and "green"

All reviewers will use 
[GitHub Pull Request Reviews](https://help.github.com/articles/about-pull-request-reviews/)
to deliver feedback, request changes, or approve a PR.