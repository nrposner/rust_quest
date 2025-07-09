# RustQuest Collaboration Policy

The RustQuest project is an open source community endeavor aimed at creating an approachable and thorough introduction to the Rust programming language. 

As a possession for the entire community, rather than a single organization, RustQuest is and shall remain open to contributions from the Rust community in both its technical aspects and pedagogy.

## Contributions

Contributions should be made through pull requests into one or more feature branches, which are periodically merged into main. 

Contributions can be made to the code, the lessons, and the guidelines themselves, with varying criteria for approval.

### Contribution Approval

In order to be approved, pull requests must be reviewed by at least one member of the RustQuest admin team. 

Pull requests into code should be forked or branched from one of several designated development branches, each focused on developing a specific aspect of the project. They should pass all unit and integration tests on the relevant branch as it exists in that moment.

Pull requests into the lessons should be placed into the relevant directory, depending on what stage of the learning journey they are designed for. They must fit the learning schedule for that section (e.g. all Basic lessons must run in a `no_std` environment). This guidance will become more detailed as the learning schedule is developed.

Pull requests into the `guides` directory, which contains the project policy and pedagogical outline, must be approved by at least one member of the admin team, and then left open for community feedback for a period not less than three days. The decision to merge this request after this period has passed is at the discretion of the admin team. 

Changes to the pedagogical outline must be considered carefully, but shall be understood to as a normal part of the project, refining and receiving valuable feedback from all corners of the community. Changes to the project policy itself, on the other hand, should be made only in the case of clear inadequacy in the original text, and should be understood to occur only in rare circumstances.

## Trusted Contributors
Contributors who have demonstrated their ability and reliability in developing the project may, subject to a 2/3rds vote of the admin team, be granted the role of trusted contributor. 

Trusted contributors gain commit permissions and may directly merge their contributions into the topic branches. This does not carry the powers or responsibilities of a project administrator.

## Administration

The role of project administrator carries the following responsibilities:
 - To uphold the principles of the project, as laid out in guides/principles.md
 - To lend a small amount of their time each week to review incoming pull requests and vote (if only to abstain) on admin decisions.
 - To field questions from the contributing community and either answer directly, direct them to the FAQ, or escalate the question to other admins.

### Joining the admin team

In order to join the admin team, post on the admin_applications discussion thread with the following information:
 - Your name
 - Your preferred method of contact for ongoing conversations (email, Discord, etc)
 - A brief bio explaining your experience with Rust and what you hope to bring to the project
 - (Optional) A blog or other place where you write on any subject

An admin application shall remain open for a period not less than three days, during which the existing admin team may ask reasonable questions of the applicant. At the end of this period, any member of the admin team may invoke a vote and cast their vote in favor, against, or abstaining from the decision to admit the applicant. Any admin who does not cast a vote within a period of three days from the invocation is assumed to abstain. A two-thirds majority of the existing admin team must vote in favor in order to admit a new admin.

Rejection from an admin role should not be understood as a statement on the applicant's past contributions to the project. The admin role is a position of high trust through which the integrity and direction of the project is maintained.

The project founder, Nicolas Posner, does not hold special privileges to bypass the aforementioned procedures. His only special power is to 'take his ball and go home' and discontinue the present repository, at which point, in accordance with the spirit and letter of the GNU v3.0 license under which RustQuest was first created, any fork of the project may continue the project without any obligations to the founder whatsoever.


