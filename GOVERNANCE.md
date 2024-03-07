## K8sNetworkPlumbingWG Governance

The K8s Network Plumbing Working Group follows the example set out by the [Kubernetes](https://github.com/kubernetes/community) and wider [CNCF](https://github.com/cncf) communities. Governance of the NPWG is lightweight so that process doesn't impede contribution. This document is an addendum to the founding [NPWG Governance doc](https://docs.google.com/document/d/1lIWOK-W6fb1VZiSjO1BoFUs0TmoVwgd4XuVc6mtJk2c/edit#heading=h.5x0d5h95i329).
## Project roles
There are four defined roles in the NPWG - two at the organization level and two at the repository level.

#### Organization owner
This is an owner of the NPWG organization as listed in the community [OWNERS](OWNERS) file. These people are responsible for the long term health of the project and day-to-day administrative tasks. An organization owner must be present at the NPWG community meeting to hold votes that require quorum - including those on changing OWNERS files and on adding or archiving repositories.

#### Organization member
This is a member of the NPWG. Members have the right to vote in NPWG community meetings.

#### Repository admin
This is a person with `Admin` rights in a GitHub repository. They are responsible for the long term health of a repository. They are also responsible for periodic administrative tasks such as reflecting changes in OWNERS file to the GitHub settings of a repository. The same person should be both maintainer and admin for a single repository.

#### Repository maintainer
This is a person with `Maintain` rights in a GitHub repository. They are responsible for the day-to-day health of a repository. Tasks expected from maintainers include issue triage, code reviews, PR approvals and attending relevant community meetings.
 
### Updating project roles

Adding a member can be done by opening a PR to [MEMBERS](./MEMBERS) in this repo. Other changes to project roles will be proposed at the [NPWG community meeting](./README.md#meetings). An organization owner must be present and decide if there is quorum to make a decision. If the group approves the change a PR will be made to the OWNERS file of the relevant repository. The PR will stay open until the next NPWG community meeting at which time it can be merged by another vote. This allows the wider community - including those who aren't able to attend the regular community meeting -  to have their say on governance changes. Once the PR is merged it's the responsibility of a repository admin or organization owner to reflect the changes in the GitHub project settings of the relevant repository. This process is followed for adding, updating or removing members from the project roles they hold.

### OWNERS file structure

The OWNERS file in this repository has the form:

```markdown
# OWNERS
owner-one
...
```

Other repositories under the NPWG have OWNERS files of the form:

```markdown
## ADMINS: People who control settings for the repo.
admin-one
...

## Maintainers: People who can merge code in this repo.
maintainer-one
maintainer-two
...
```

## Project repositories
Active and archived repositories are listed in [REPOSITORIES](REPOSITORIES). This file has the form:
```markdown
## ACTIVE REPOSITORIES
repo-one http://link-to-repo-one.com
repo-two http://link-to-repo-two.com

## ARCHIVED REPOSITORIES
repo-three http://link-to-repo-three.com
...
```

### Adding or archiving a repository
To begin, donate, or archive a repository a proposal is made at the [NPWG community meeting](./README.md#meetings). An organization owner must be present and decide if there is quorum to make a decision. If the group approves the change a PR will be made to the [REPOSITORIES](REPOSITORIES) file in the community repository. The PR will stay open until the next NPWG community meeting at which time it can be merged by another vote. This allows the wider community - including those who aren't able to attend the regular community meeting -  to have their say on governance changes. Once the PR is merged it's the responsibility of an organization owner to reflect the changes in GitHub. This process is followed for adding, donating  or archiving repositories.

