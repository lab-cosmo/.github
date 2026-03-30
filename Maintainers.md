# Maintaining a repository

This document defines the responsibilities and decision powers of maintainers of for code repositories in lab-cosmo and other github organisations that choose to follow the same model.

Each repository is expected to have at least 2 maintainers, recorded in the README. The README should also list previous maintainers for this repository, as a way to thank them and give credit.

When leaving the COSMO lab (or relevant organization), maintainers have a choice between:

- (a) keeping maintaining project in lab-cosmo (or the organization) namespace
- (b) move the project to a separate organization, especially if the center of mass of maintainers moves outside of the lab-cosmo (organization) boundaries;
- (c) personal projects can be have ownership transfered directly to the maintainer's personal GitHub account.

## Responsibilities

Maintainers are tasked with the following:

- Reviewing incoming pull-requests or finding a reviewer for incoming pull-requests;
- Answering discussions questions, or finding someone to help answer;
- Answering and triaging issues: closing fixed/duplicate issues, making sure bugs can be reproduced, definine the scope for feature requests, …
- Handling new releases, including git tag, changelog, building artifacts (wheels, pre-compiled builds, …) and advertisement;
- Enforcing some level of quality control on the code, making sure any technical dept stays manageable;
- Handling "house cleaning" tasks, such as updating dependencies, fixing CI when it breaks because of external updates, …
- Find new maintainers when one member of the team has to leave for any reason

## Decision powers

As a general case, maintainers are expected to reach agreement as a group when making decisions. They should always consider how the repository they work with interact with the wider ecosystem, and if needed push for ecosystem-wide changes to limit tool fragmentation in an organization.

More specifically, maintainers make decisions about:

- the exact level and strictness of quality control that apply to a given repository;
- the priorities and overall roadmap of the software package(s);
- accepting, refusing and merging pull-requests in the repository;
    - in particular, maintainers are allowed to merge urgent bug fixes without further review, but should excercise judgment and handle any fallout from doing so;
- deciding on new maintainers for this repository.
