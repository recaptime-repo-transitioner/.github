# Repository transitioner org for Recap Time Squad

Similiar to [`docker-library-transitioner` GitHub org](https://github.com/docker-library-transitioner), this organization serves as an intermediary regarding
repository ownership changes between us and old/new repository owners.

## Request repository ownership transfers

Anyone can request repository ownership transfers for their GitHub projects to Recap Time Squad as long as:

* Open-source project under one of either OSI-Approved, FSF-endorsed or that meets Debian Free Software Guidelines or on the Fedora Software License List.
  * Open core projects are a bit of edge case 
* Cannot be owned by an employee (due to copyright reasons).
* Hosted on their personal namespace. If your open-source project is managed via a seperate GitHub/GitLab/sourcehut namespace, please invite [our administrative account][admin]
first and continue to step 2 for non-squad members.

We recommend not to fork new repo back into the old organization to ensure that URL redirects will just work magically.

[admin]: https://squad.lorebooks.eu.org/handbook/opensource/administrative-accounts

### Non-squad members

1. [File an access request](https://issues.recaptime.eu.org/p/access-requests/new/?template=repo-transitioner-github) so that we can provision access to the intermediary organization.
2. Move your project to this repository once we provisioned access. [Then file a RFC for change of maintainership](https://issues.recaptime.eu.org/p/rfcs/new/?template=repo-maintainership-change-external&use-github-issue-forms=1&platform=github) in order for us to have a look onto it.
3. Once we confirmed that we have the enough resources/bandwidth to maintain it, we transfer repo ownership to its new home and close the RFC issue for you. There'll be few more paperwork you need to fill up for legal reasons, but we don't require a copyright license assignment to be signed just to transfer the repo to us (following the sprit of the [Linux DCO][dco]).

[dco]: https://squad.lorebooks.eu.org/handbook/opensource/dco

### Squad members

You can transfer directly to either `recaptime-dev` or one of our other orgs if you prefer (currently both public and private repos are allowed to
be transferred, so be careful of transferring your private repos):

![image](https://github.com/recaptime-repo-transitioner/.github/assets/141569587/88186915-f8b1-4132-b498-c27417e305dc)

If you got the `You don’t have the permission to create public repositories on recaptime-dev` error similiar to the screenshot below, please check
[instructions for non-squad members](#non-squad-members). Either another squad member with admin prvilleges (or authorized to use our administrative account)
should invite you to the organization you desired to transfer the repo.

![image](https://github.com/recaptime-repo-transitioner/.github/assets/141569587/2afa2d76-a1c5-41dd-8224-946b78c42dcd)
