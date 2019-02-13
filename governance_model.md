# FIAAS open source governance model

## Scope
The scope of this document is to describe how contributors to the FIAAS open source project should collaborate. Any
technical aspects of the project are out of scope for this document.

## Goal
Describe a minimal process for governing the FIAAS open source project. The process should be as simple and
uncomplicated as possible, as that will increase the likelihood of contributors actually following the process.

This document should also describe a process for changing the process itself, whenever that is deemed necessary by the
project's contributors.

## Governance model
### Process
All new features must be described in an issue on github.com/fiaas. Discussion around said feature should also be
recorded on the github issue. The FIAAS maintainer team has the right to approve, reject, or request changes in a
feature request before it is implemented/applied to the master branch.

Patches must be submitted as pull requests. Patches require approval from at least one member of the FIAAS maintainer
team before being committed onto the master branch.

### FIAAS maintainer team
As a starting point there should be a well-defined maintainer or ideally a maintainer team of several people, which is
responsible for:

* Answering any pull requests and new issues in a timely manner.
* Act as gatekeepers for new features; decide whether it makes sense to have that feature in FIAAS or not
* Maintain a current roadmap for the features they plan to work on.
* Keep 3rd party libraries up to date (especially with regards to security issues).

### Changing the process
Anyone can request a change in the process. Such changes must be described in a github issue, and will be handled in
the same way as a technical feature.

### Code of conduct
The project needs a code of conduct that all project contributors must adhere to. See the [code of conduct
document](code_of_conduct.md) for details of the code of conduct.

### License
All software shall be licensed under the Apache 2.0 license.
