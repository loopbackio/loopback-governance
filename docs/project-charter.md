# LoopBack Charter

_note: the purpose of a project charter is to provide a brief introduction_
_to the project from a technical, community, or business perspective. The_
_document also connects a project's community leadership and governance with the_
_OpenJS Foundation's governance._

## Section 0: Guiding Principles (optional)

_directions: provide a concise, high-level statement about_
_the project's long-term principles, values, or mission._

ex. [Node.js TSC Charter](https://github.com/nodejs/TSC/blob/HEAD/TSC-Charter.md#section-1-guiding-principle)

LoopBack (herein "Project") is part of the OpenJS Foundation which operates
transparently, openly, collaboratively and ethically. Project proposals,
timelines, and statuses must be open and visible to outsiders.

## Section 1: Scope

_directions: Include a 3-4 sentence summary of what the project does,_
_and/or what problems it solves. Imagine trying to explain your work_
_to a colleague who is familiar with related technical concepts but unfamiliar_
_with the project. You may also want to describe the project's value to community_
_and/or business stakeholders._

ex. [K8s SIG Architecture Charter](https://github.com/kubernetes/community/blob/HEAD/sig-architecture/charter.md#scope)

The Project intends to create and maintain a collection of Node.js packages to
provide developers with the tools to create enterprise solutions which require
interaction between a diverse set of APIs. Notably, the Project emphasizes the
creation of extensible, open APIs to empower developers with flexibility and
modularity. This allows the packages easily adapted to a wide range of
use-cases and allows different subsets of the Project to be used as needed.

### 1.1: In-scope (optional)

_directions: list or bullet out problem spaces, use cases, repositories_
_or other projects which are included with the work but may not be readily_
_apparent. This may help differentiate the project from other solutions in the_
_space. If you are not using this section, please indicate your intent with the_
_phrase, 'Section Intentionally Left Blank'._

ex. [K8s SIG Architecture Charter](https://github.com/kubernetes/community/blob/HEAD/sig-architecture/charter.md#in-scope)

- Maintenance of existing Node.js packages
  - Supporting latest versions of Node.js
  - Managing deprecation
- Modernisation and extension of existing Node.js packages
- Creating new Node.js packages
- Documenting and standardising interfaces for common interactions

### 1.2: Out-of-Scope (optional)

_directions: list or bullet out areas that may be seen to be related but are_
_not included in the scope of this project. This may help clarify the kind of_
_features, contributions, issues or problems the project is looking for._
_If you are not using this section, please indicate your intent with the_
_phrase, 'Section Intentionally Left Blank'._

ex. [K8s SIG Architecture Charter](https://github.com/kubernetes/community/blob/HEAD/sig-architecture/charter.md#out-of-scope)

Section Intentionally Left Blank

## Section 2: Relationship with OpenJS Foundation CPC.

_directions: describe how the project intersects with the Cross Project_
_Council._

ex. [Node.js TSC Charter](https://github.com/nodejs/TSC/blob/HEAD/TSC-Charter.md#section-2-evolution-of-openjs-foundation-governance)

Technical leadership for the projects within the OpenJS Foundation is delegated
to the projects through their project charters by the OpenJS Foundation Cross
Project Council (CPC). In the case of LoopBack, it is delegated to the LoopBack
Technical Steering Committee (“TSC”). OpenJS Foundation’s business leadership is
the Board of Directors (the “Board”).

This Technical Steering Committee Charter reflects a carefully constructed
balanced role for the TSC and the CPC in the governance of the OpenJS
Foundation. The charter amendment process is for the TSC to propose changes
using lazy consensus of the TSC, the proposed changes being subject to review
and approval by the CPC. The CPC may additionally make amendments to the TSC
charter at any time, though the CPC will not interfere with day-to-day
discussions, votes or meetings of the TSC.

### 2.1 Other Formal Project Relationships (optional)

_directions: describe any additional affiliations or groups that liaise with_
_the project in a formal way (such as a W3C Community Group, for example)._
_If you are not using this section, please indicate your intent with the_
_phrase, 'Section Intentionally Left Blank'._

Section Intentionally Left Blank

## Section 3: LoopBack TSC Governing Body

_directions: describe the structure of the group responsible for managing_
_the project and its respective organization and repositories. If there are_
_specific rules for membership or participation in the group, list them here or_
_by reference to a governance.md document._

ex. [Node.js TSC Charter](https://github.com/nodejs/TSC/blob/HEAD/TSC-Charter.md#section-3-establishment-of-the-tsc)

TSC memberships are not time-limited. There is no maximum size of the TSC. The
size is expected to vary in order to ensure adequate coverage of important areas
of expertise, balanced with the ability to make decisions efficiently. The TSC
must have at least four members. Although there are no hard requirements, the
composition of the TSC should aim for geographic and employer diversity in the
spirit of a distributed maintenance model.

## Section 4: Roles & Responsibilities

_directions: describe the roles and responsibilities of the LoopBack Governing Body._

ex. [K8s SIG Architecture Charter](https://github.com/kubernetes/community/blob/HEAD/sig-architecture/charter.md#roles-and-organization-management)
ex. [Node.js TSC Charter](https://github.com/nodejs/TSC/blob/HEAD/TSC-Charter.md#section-4-responsibilities-of-the-tsc)

The LoopBack TSC is responsible for, but not limited to:

- Release dates
- Creating new releases
- Release quality standards
- Technical direction
- GitHub repository hosting
- Infrastructure management
- License and security compliance
- Conduct guidelines and enforcement
- Maintaing the list of LoopBack Maintainers
- Mediating technical conflicts between Collaborators or Foundation projects
- Hosting and publishing the monthy LoopBack Maintainers Call

### Section 4.1 Project Operations & Management (optional)

_directions: use this section to describe any other specific tasks the_
_${PROJECT} Governing Body may be responsible for regarding process or project_
_operations and management. If you are not using this section, please indicate_
_your intent with the phrase, 'Section Intentionally Left Blank'._

ex. [K8s SIG Architecture Charter](https://github.com/kubernetes/community/blob/HEAD/sig-architecture/charter.md#roles-and-organization-management)
ex. [Node.js TSC Charter](https://github.com/nodejs/TSC/blob/HEAD/TSC-Charter.md#section-5-nodejs-project-operations)

The TSC and entire technical community will follow any processes as may be
specified by the OpenJS Foundation Board relating to the intake and license
compliance review of contributions, including the OpenJS Foundation IP Policy.

### Section 4.2: Decision-making, Voting, and/or Elections (optional)

_directions: describe any provisions the project makes for decision-making_
_or include the information by reference your governance.md document._
_If you are not using this section, please indicate your intent with the_
_phrase, 'Section Intentionally Left Blank'._

ex. [Node.js TSC Charter](https://github.com/nodejs/TSC/blob/HEAD/TSC-Charter.md#section-6-elections)

Unless stated otherwise, the LoopBack TSC adopts a lazy consensus voting system,
where consensus is assumed when there are no outstanding objections from the
other TSC members after a stipulated period of time of no less than 72 hours.

For more important matters such as the nomination of new TSC members, a lazy
consensus for a stipulated period of no less than 1 week is used instead.

These votes must be done through a process that's accessible to the general
public.

### Section 4.3: Other Project Roles (optional)

_directions: describe other roles within the project, such as chairperson,_
_tech lead, collaborator, contributor, maintainer, etc. and any responsibilities or_
_rights such role confers. You can also include this information by_
_reference to your governance.md document._
_If you are not using this section, please indicate your intent with the_
_phrase, 'Section Intentionally Left Blank'._

ex. [Node.js TSC Charter](https://github.com/nodejs/TSC/blob/HEAD/TSC-Charter.md#section-8-project-roles)

The role of a LoopBack Maintainer is given to those that the LoopBack TSC
has confidence in their general understanding of the Project's codebase, and
trusts that they are capable for seeking feedback and consensus on non-trivial
contributions. This role provides permissions to merge pull requests in the
Project's Git Repositories, and dedicated communication channels with the
LoopBack TSC. Nomination for the role is done in accordance with
[maintainer-nomination.md](./maintainer-nomination.md).

## Section 5: Definitions (optional)

_directions: include any definitions that may help clarify terms or ideas found_
_in this charter document. If you are not using this section, please indicate_
_your intent with the phrase, 'Section Intentionally Left Blank'._

ex. [Node.js TSC Charter](https://github.com/nodejs/TSC/blob/HEAD/TSC-Charter.md#section-9-definitions)

- **Distributed Maintenance Model:** A working model where the composition of
    those maintaining the project has geographic and employer diversity.
- **Project:** The LoopBack project
- **General public:** A group of people who do not have any roles or
    responsibilities in the Project.
