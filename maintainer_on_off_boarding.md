# Maintainer on/off-boarding checklist

## Onboarding to the FIAAS maintainer team

- Add Github user to `maintainers` team https://github.com/orgs/fiaas/teams/maintainers/members
- Set Github user as "maintainer" role in `maintainers` team https://help.github.com/en/github/setting-up-and-managing-organizations-and-teams/giving-team-maintainer-permissions-to-an-organization-member
- Set Github user as "owner" of the fiaas Github organization https://github.com/orgs/fiaas/people
- Promote Github user to admin level in Semaphore CI https://fiaas-svc.semaphoreci.com/people
- Add DockerHub user to `owners` team in `fiaas` organization: https://hub.docker.com/orgs/fiaas/teams/owners
- Add user's public GPG key to [ops](https://github.com/fiaas/ops) repository; see the [README for detailed instructions](https://github.com/fiaas/ops#adding-a-new-user).
- Add email address to the fiaas maintainer mailing list (here: https://groups.google.com/forum/#!managemembers/fiaas/members)
- Add readthedocs.org user to fiaas/k8s docs project: https://readthedocs.org/dashboard/k8s/users

## Offboarding from the FIAAS maintainer team

- Remove Github user from `maintainers` team
- Remove owner privileges in fiaas Github organization for Github user
- Demote Github user from admin level in Semaphore CI
- Remove DockerHub user to `owners` team in `fiaas` organization: https://hub.docker.com/orgs/fiaas/teams/owners
- Remove user's public GPG key from [ops](https://github.com/fiaas/ops) repository; see the [README for detailed instructions](https://github.com/fiaas/ops#removing-a-user)
- Remove email address from the fiaas maintainer mailing list (here: https://groups.google.com/forum/#!managemembers/fiaas/members)
- Remove readthedocs.org user to fiaas/k8s docs project: https://readthedocs.org/dashboard/k8s/users
