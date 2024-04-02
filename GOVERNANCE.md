# Network Plumbing Working Group Governance
Proposal, July 2020

## NOTES / CHANGES
* July 16th 2020
Action Doug: Add language for adding a new project, ask for contributors to add item to agenda describing how it's related (implements specifications, is related technology etc), and a description of the project, and we'll bring it up for a vote.
Action Doug: Mission statement to guide relevance of pull requests (leave some wiggle room, add language about tooling and PoC's)
Action Adrian.C : Add project contributor expectations (will leave a comment) DONE
Action Doug: Look into process for official Kubernetes working groups
SIG Network proposes to the ToC
If the TOC doesn't reject it, SIG-Network adds a document
We could then add one or more projects as a sandbox
The new Sandbox is perfect for "experimental" projects like this
* July 21st 2020
Doug, thoughts on roles:
Josh makes a good point about establishing "roles", such as the role of being a member, a maintainer, etc. Doug is highly in favor of having a member role, to more easily establish who vote.
Specs: need to be voted on by maintainers group?
Define bi-weekly meeting
What's quorum? No over representation from a single org.
Add a link to the calendar.
Can you vote on stuff that's not on the agenda this week?
Could be pushed
Periodic review of meeting time for timezones


Checklist for "complete basic governance": https://docs.google.com/document/d/1JjRhcLBJQbbRCpKwYx_VcS_JzsqkznYj7GnYXpQkF8M/edit?usp=sharing
##### July 23rd 2020
    Added mission statement (earlier in the week), add portion on responsibilities of the group.
    Update language to meet new idea of "roles" - member / maintainer
    Updated section on maintainer responsibilities (thanks Adrian for getting that started!)
    Closed a number of comments (which were very helpful!) that were out of date after having been addressed.
    Added section about process for approving pull requests.
    This could probably use some eyes & ideas.
    Added section about meetings and voting
    Doug needs input on quorum.

##### August 11th 2020
    Created a paragraph about maintainers meetings and decisions in the "maintainer responsibilities" section.
    Add to mission statement regarding having goal of moving towards having technologies in Kubernetes itself, where appropriate.
    Added phrasing for "vendor-neutral technologies"
    Added location for list of members & maintainers as the /community repo
    Addressed some typographical & grammatical errors.
    Still need input on voting in section D.
    Updated language for accepting pull requests to note that maintainers may approve their own pull requests, but require at least one other maintainer to give a LGTM.

##### August 26th 2020
    Peter Mangan has comments on voting rights for members vs. public participation, do we need updates to the language for being a member?
    Clean up language for "maintainer" (which was using "core contributor" in places)
    Updated language for "verbally agree" to "verbally (or otherwise) agree" to use language that accounts for people of all abilities.
    Changed quorum to 3 members to vote. 5 members to change the governance document.
    Added example for quorum and representation by a single given corporate entity.

##### Sept 3rd 2020
    Added note that maintainers still have the same rights and privileges as members (e.g. they're both maintainers and members, as they have to start as members)
    Added new section "GitHub Organization Ownership"
    Gist is that there should be no more than 50% of owners from the same employer, and that we vote to make someone an owner.
    Clean up resolved comments.
    Attempted to normalize some of the language between sections.

##### August 25th 2021

    Updates for two maintainers to accept a repository.


## OVERVIEW
This document is intended as a proposal for how we govern the contributions to repositories under the Network Plumbing Working Group (NPWG). It's intended to document how people can join the project and become project core contributors, and will address further issues as need be.

The intention is to provide a common ground for GitHub software repositories @ https://github.com/k8snetworkplumbingwg. These repositories encompass the work that's being done across the working group. As the group grows in size and as the stakeholders diversify, having a solid framework for contribution should benefit the group as a whole.

In tandem, it's proposed that we accept a "code of conduct", which would be included in each repository in markdown format. In the "CODE OF CONDUCT" section, there is a proposed code of conduct which is adapted from: https://www.contributor-covenant.org/version/2/0/code_of_conduct/.

Note: The original version of this document is at https://docs.google.com/document/d/1lIWOK-W6fb1VZiSjO1BoFUs0TmoVwgd4XuVc6mtJk2c

## MISSION STATEMENT
The Network Plumbing Working Group's goal is to advance vendor-neutral open source and open standards in regards to networking capabilities for workloads running in Kubernetes. This includes creation of specifications for technologies, the development & tooling of these vendor-neutral technologies, building reference implementations, creation of proof-of-concept technologies to help drive the discussion, and furthering the specifications and implementations of those specifications. As appropriate, these technologies should work towards integration into core technologies, such as Kubernetes.

The Network Plumbing Working Group is responsible for maintaining and updating the specifications we have created, as well as maintenance of software that is created by members and maintainers of the Network Plumbing Working Group.

## GOVERNANCE
### Section A: Joining The Network Plumbing Working Group
Anyone is free to contribute to the Network Plumbing Working Group at any time. Contribution to the working group happens across a number of vectors, which include but are not limited to: The Network Plumbing Working Group's Google Groups email list, bi-weekly meetings and GitHub. Any member of the group is invited to join the discussion, and to submit patches to GitHub.
A "member" of the Network Plumbing Working Group has the right to vote given any decision the group makes.

To become a member, one must have demonstrated contributions to the group (documented in the meeting agenda, github, or any other place where contribution is possible). One may make a request to become a member by adding their name to the agenda along with the request to join. If there are no members who reject a given proposal, the new member is accepted. If there are any rejections, the acceptance of a member will be put to a vote.

Members shall be documented in the community repository.

Interactions in this working group are covered by the Code of Conduct.

### Section B: Becoming a maintainer
A "maintainer" to the Network Plumbing Working Group includes the right to merge code into a specific repository.

To become a maintainer for a project, a member can indicate their candidacy by adding their intention to become a maintainer to the bi-weekly agenda Google doc, and indicate which projects they would like to become a maintainer of.

During the bi-weekly meeting, new maintainers will be accepted as a maintainer if no other members reject a current proposal to become a maintainer. If any member (or members) reject a maintainer proposal, their maintainership status will be determined by majority vote. If the member is accepted by vote as a new maintainer, the member must agree (verbally or otherwise) to following the maintainer responsibilities, at which point, they become a maintainer.

Maintainers shall be documented in the community repository. A maintainer still retains the same privileges as a member.

#### Maintainer Responsibilities
* Familiarity with the project and deep knowledge of certain areas of it.
* Numerous contributions to the project.
* Demonstrated participation in code reviews, providing helpful feedback to others.
* Able to allocate time as necessary for pull request reviews & issue feedback.
* Ensuring the direction of the project matches its intended goal.
* Approving pull requests that meet the project's scope, the NPWG's mission statement, and that those pull requests meet a basic standard (are well formed and have appropriate testing).
* Meeting attendance when necessary or required.
Project contributors and maintainers may meet and make decisions regarding a given repository. However, if consensus cannot be reached on a given topic, maintainers must bring these topics to the NPWG bi-weekly meeting for discussion, and if necessary a vote. If project meetings occur with regularity, the meeting details should be shared on the NPWG bi-weekly meeting agenda.

Each repository shall have a copy of the Code of Conduct included.

#### Process for accepting pull requests
Pull requests should be approved by 2 or more maintainers employed by distinct employers before pull requests are merged. Maintainers may approve their own pull requests, however these pull requests must also be reviewed and approved by one or more other maintainers.

Automated pull request gating and merging by GitHub robot is preferred.

#### GitHub Organization Ownership
The Network Plumbing Working Group keeps a GitHub Organization which is available to the public at https://github.com/k8snetworkplumbingwg. An owner is defined as someone who has the GitHub "owner" role in the GitHub Organization. Owners will be documented in the community repository.

To become an owner of the GitHub Organization, a member may indicate their candidacy to become an owner by adding an item to the agenda. This ownership candidacy should be accompanied by a short description outlining why an individual should have ownership permissions. A majority vote will occur to determine if a member should gain the owner role at https://github.com/orgs/k8snetworkplumbingwg/people.

The group of all owners should not have more than 50% representation by a single organization. For example, If there are 5 owners, no more than 2 may be employees of the same company.
According to GitHub's documentation about GitHub organizations owners have "have complete administrative access to [an] organization". Owners are responsible for creating repositories as well as setting GitHub roles for maintainers. Owners must not delete, rename, make private, or transfer ownership of any repositories outside of the GitHub organization, nor take any other disruptive action without a vote during a bi-weekly meeting.


### Section C: Addition of new projects under the GitHub organization
The addition of a project may be proposed by adding the project to the meeting agenda. This request for a new project should be accompanied by a project description that's suitable for the scope of a given project (that is, a proof of concept or auxiliary tool may only need a short description, whereas a project larger in scope should have an appropriately sized design document). In order to accept a project, two or more maintainers must also be proposed along with the project. If no members reject the request for a project proposal, it will be accepted. Otherwise, the acceptance of the project will be put to a vote.

All proposed projects should aim towards progressing the mission of the NPWG as stated in the mission statement.

### Section D: Meetings & Voting
Meetings are held bi-weekly, the connection information and agenda may be found in this Google document.

A bi-annual review of the meeting time will occur to assess that the meeting time is suitable for time zones of those contributing to the meetings.

For any action that requires a vote, quorum must be achieved. To achieve quorum, 3 or more members shall be available to vote, and there shall be no more than 50% representation among voters of members in employment of the same employer. In order to make changes to the governance document, there shall be 5 or more members available to vote and there shall be no more than 50% representation of members in employment of the same employer.

An example of quorum regarding "no more than 50% representation" would be:
* If there are 3 members all from Company A, quorum is not achieved as there is 100% representation from a given company.
* If there are 5 members available to vote, and 3 members are from Company A, and two members from Company B, this would result in there being 60% representation from Company A. In this case, 1 member from Company A must abstain, thereby making for 50% representation from both Company A and Company B.