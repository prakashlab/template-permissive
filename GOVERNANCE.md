# Governance

This document defines the project governance for this repository. Most of the
content in this document was copied or adapted from the
[moby project](https://github.com/moby/moby)'s `project/GOVERNANCE.md` file)

## Project maintainers

The current maintainers of this repository are listed in the `MAINTAINERS.toml` file.

There are different types of maintainers, with different responsibilities, but
all maintainers have 3 things in common:

1) They share responsibility in the project's success.
2) They have made a long-term, recurring time investment to improve the project.
3) They spend that time doing whatever needs to be done, not necessarily what
is the most interesting or fun.

Maintainers are often under-appreciated, because their work is harder to appreciate.
It's easy to appreciate a really cool and technically advanced feature. It's harder
to appreciate the absence of bugs, the slow but steady improvement in stability,
or the reliability of a release process. But those things distinguish a good
project from a great one.

### Adding maintainers

Maintainers are first and foremost contributors who have shown their
commitment to the long term success of a project. Contributors who want to
become maintainers first demonstrate commitment to the project by contributing
code and/or hardware design and/or documentation work, reviewing others' work, and
triaging issues on a regular basis for at least three months.

The contributions alone don't make you a maintainer. You need to earn the
trust of the current maintainers and other project contributors, that your
decisions and actions are in the best interest of the project.

Periodically, the existing maintainers curate a list of contributors who have
shown regular activity on the project over the prior months. From this
list, maintainer candidates are selected and proposed through internal communications
among existing maintainers.

After a candidate is proposed through internal communications among maintainers,
the existing maintainers will use an informal process to decide whether to approve
the candidate as a new maintainer.

If a candidate is approved, a maintainer contacts the candidate to
invite them to open a pull request that adds the contributor to
the `MAINTAINERS.toml` file. The candidate becomes a maintainer once the pull
request is merged.

### Removing maintainers

Maintainers can be removed from the project either at their own request
or due to [project inactivity](#inactive-maintainer-policy).

#### How to step down

Life priorities, interests, and passions can change. If you're a maintainer but
feel you must remove yourself from the list, inform other maintainers that you
intend to step down, and if possible, help find someone to pick up your work.
At the very least, ensure your work can be continued where you left off.

After you've informed other maintainers, create a pull request to remove
yourself from the `MAINTAINERS.toml` file.

#### Inactive maintainer policy

An existing maintainer can be removed if they do not show significant activity
on the project. Periodically, the maintainers review the list of maintainers
and their activity over an unspecified period.

If a maintainer has shown insufficient activity over this period, a project
representative will contact the maintainer to ask if they want to continue
being a maintainer. If the maintainer decides to step down as a maintainer,
they open a pull request to be removed from the MAINTAINERS file.

If the maintainer wants to continue in this role, but is unable to perform the
required duties, this project does not yet have any formal process to remove the
maintainer.

## How are decisions made?

Currently, this project is too small to have democratic decision-making. All decisions
are made together by the project maintainers and Manu Prakash, the leader of the Prakash
Lab, under a [Benevolent Dictator](https://communityrule.info/templates/benevolent-dictator)
approach, using informal *ad hoc* decision-making processes. As the project matures,
decision-making processes may be adjusted to become more formal, accountable,
and/or democratic.
