# Github organization privilege structure

This is a brief summary of how the current privilege structure for this github organization is set up. This is an initial setup and is subject to potential change in the future. Changes should be reflected in this document.

## Defaults
The default permission for organization members is read-only.

When adding a new repository, the maintainer team should be added with admin level access, and the contributor team should be added with write level access.

Branch protection that grants only the maintainer team and organization owners access to push to the master branch should be enabled on every repository.

## Organization owners

Organization owners naturally have full access to every repository as well as to all organization level settings.

## Maintainers

This team should contain the people in the [maintainer team](/governance_model.md#fiaas-maintainer-team), and grants admin access to all repositories.

## Contributors

This team grants write access to (almost) every repository. Since branch protection for the master branch is enabled, this effectively means that members can create, manage and push to any other branches.

Since Semaphore CI only builds branches from the repository itself, and not from forks, it might make sense to add frequent contributors to [fiaas-deploy-daemon](https://github.com/fiaas/fiaas-deploy-daemon) in particular to this team, and to the member list in Semaphore such that they can see CI build outputs on pull requests.
