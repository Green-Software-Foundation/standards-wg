## Scope
The Scope of this Specification defines the operations and processes of the Green Software Foundation, Standards Working Group.
## Terminology and Conventions

### Conventions
The keywords "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC2119].

### Definitions & Abbreviations

Kindly consult [GSF Dictionary](https://github.com/Green-Software-Foundation/Dictionary/blob/dev/Dictionary/Dictionary.md)

## Governance
### Membership Levels
Note:
```
Project Charter - 2. Membership Levels
2.1.	Steering Member.  
Steering Members may participate in each Working Group and, unless waived per the Membership Agreement, the Steering Committee.
2.2.	General.  
General Members may participate in each Working Group but do not participate on the Steering Committee. 
2.3.	Contributor. 
Contributors may participate in Working Group(s) designated by the Steering Committee but do not participate on the Steering Committee and are not eligible to participate in decisions that require a Supermajority Vote.
```

### Organization Structure
<figure>
	<img src="images/gsf_governance.svg" alt="GSF Governance Structure">
	<figcaption>GSF Governance Structure</figcaption>
</figure>

#### Steering Committee
Note:
```
Project Charter - 3.1 Steering Committee
The Steering Committee (SC) is the body that is responsible for governing the Project, coordinating Working Groups, and managing assets.
```
The Project Charter describes the governance structure for the association.  

* One of the more essential duties of the Steering Committee is the Approval of the Specifications and other works produced as a consensus product of the Working Groups. 

Specifications, essential specifications, are subject to challenges from others. Having a well understood, well documented, and neutral process for their creation and Approval demonstrates consistency in the process. It makes the challenges much more complicated for those who might try to make mischief in the future.

#### Working Groups (WG)

Note:
```
Project Charter - 6. Working Groups.
The Project may have multiple Working Groups, and each Working Group will operate as outlined in its Working Group Charter.
```

* Working Groups (WGs) are chartered by SC to handle one or more Work Packages.

## What to Expect from GSF Roles
* [from Members](#from-members)
* [from Editors](#from-editors)
* [from Chairs ](#from-wg-chairs)
* [from Maintainer(s)](#from-maintainers)

### From Members
* Members MUST read the Project documentation (e.g., contribution guidelines, readme, and release planning file) before attending to submit an Issue or Pull Request
* Members are not allowed to fork a project to build a feature that the Working Group has rejected

### From Editors
### From WG Chairs
> Each Working Group will designate a chair for that Working Group. A Working Group may select a new chair upon Approval of the Working Group Participants.

* In performing their tasks, officers SHALL maintain strict impartiality and act in the Organization's interest.
* Chairs MAY limit the amount of time allocated to a particular agenda item or discussion point.
* Chairs SHALL, after a reasonable period of discussion time, use means to reach a decision including (but not limited to quickly):
  * a statement of the Chair's view of group consensus, which shall be accepted by the Group if there are no objections.
  * assignment of action items to progress the issue in a short a time period as possible.
  * invite single or few objectors to no longer sustain their objections.
  * informal voting.
  * formal voting.
* Chairs MAY require that new information be provided about an issue before earlier decisions can be reopened/revisited.
* The work and progress of the Group are appropriately communicated through regular status reports to the SC.
* The Chair MAY delegate tasks to the co-chair, including chairing the Group as and when necessary.

### From Maintainers
* The Maintainer MUST keep the project documentation up to date (e.g., contributing, readme and release planning documents)
* The Maintainer MUST apply the "Review & Approval" process to contributions submitted by the Working Group members
* The Maintainer SHOULD use GitHub "Labels" to indicate the type of "Review & Approval" assigned to each Pull Request
* The Maintainer SHOULD keep communications with the members via GitHub Issues or Pull Requests rather than one to one communications
* The Maintainer SHOULD close contributions that do not follow the rules, or meet the right quality or are related to features that are in the Scope of the Release Version under development

## Meetings
* WGs are encouraged to schedule regular conference calls.
* The Meetings MUST be announced at least 7 days in advance.
* All the Organization members are contractually bound to the IPR policy under terms of the Membership Application, and these IPR Guidelines must be followed.
* Meetings SHALL have an IPR call where a reminder of the IPR policy and the duties and obligations of members is provided.
* A meeting attendee list MUST be produced for each meeting. This is necessary to determine which members can vote in a Supermajority vote.

## Technical Decision Making
### Decision Making
Note:
```
Working Group Charter - 3. Working Group Decision Making
3.1. Consensus/Voting/Approval.
The Working Group will endeavor to make all decisions by consensus.  
Where the Working Group cannot reach consensus with respect to a particular decision, the Working Group will make that decision by a Supermajority Vote of the Steering Members and General Members in this Working Group. 
3.2. Appeals. 
Working Group decisions may be appealed by issuing a written appeal to the Working Group Chair, and that appeal will be considered by the Working Group chair in good faith.  
The Working Group Chair will respond in writing within a reasonable time.
3.3 Notifications and Electronic Voting.  
The Working Group Chair is responsible for issuing all notifications of meetings and votes of the Working Group subject to the following minimum criteria: 
(i) in-person meetings require at least 30 days prior written notice, 
(ii) teleconference meetings require at least 7 days prior written notice (this requirement only applies to the notification of the first meeting of automatically recurring teleconference meetings), 
(iii) electronic votes require no advance notice but must be made pursuant to a clear and unambiguous ballot with only “yes” and “no” options, and the voting must remain open for no less than 7 days.  These notification requirements with respect to the Project may be overridden upon unanimous consent of all Steering Members and General Members that have attended and participated in at least 50% of the last 4 meetings of the Project.
```

As part of their responsibilities defined in [from WG Chairs Officers](#from-wg-chairs-officers), officers need to ensure efficient and effective decision-making. 
* The decision-making process in WGs is intended to be as inclusive as possible. 
* WGs shall attempt to use consensus to make decisions. 
* If consensus cannot be reached, voting mechanisms MAY be used. 
* Formal notice SHALL be given for decision making, e.g.:
  * Inclusion of a document on the agenda, proposing a specific decision to be taken (e.g. Pull Request).
  * Inclusion of an item directly in the agenda (e.g. proposed next meeting date).
  * Items proposed for Approval via the group mailing list (e.g. agreement a document revision).
  * Inclusion of a document for decision in an electronic Review, Comment and Approval event
  * Inclusion of a document for decision in an e-vote (Supermajority) vote.
 > The above list is not exhaustive.
* There SHALL be no distinction in the decision-making merit of real-time or non-real-time meetings.
  * In real-time meetings, consensus can be determined by receiving no sustained objections to a proposal. 
  * In non-real-time meetings, consensus SHOULD be developed using Review, Comment and Agreement periods, e.g. using [Review and Approval](#GSF-approval-process)
* Proposals SHALL be available for a given period. 


### Seeking Consensus
* Groups shall endeavour to reach a consensus on all decisions. 
* Informal methods of reaching consensus are encouraged (e.g. a show of hands).
* Groups SHOULD attempt to ensure contributions relating to the same subject matter are considered together before being disposed of. 
* However, the Chair SHALL ensure that unavailable contributions or participants do not delay progress.
* Agreement SHALL be sought in all forms of meeting.

### Handling objections when seeking consensus
* Objections from a small minority SHOULD be minuted, and the objecting delegates SHOULD be questioned if having their objections minuted is sufficient, and they agree not to sustain their objections. 
  * If such agreements are secured, then there is a consensus for approving the proposal. 
  * If such agreements are not secured, then the proposal is not agreed, and further action SHALL be taken (e.g. the proposal is withdrawn, updated, or voted on). 
  * Members are discouraged from sustaining their objections when it is clear that a vote would overrule them was one to take place.
* In real-time meetings, consensus can be determined by receiving no sustained objections to a proposal.
  * Efforts to immediately resolve or record objections can be taken to attempt to achieve consensus.
* Where attendance is sparse when viewed from normal participation levels, potentially controversial proposals SHOULD be made available to the broader membership. 
* The Chair is responsible for ensuring such an opportunity for participation in the decision-making process. 
* Sparsely attended meetings SHOULD NOT be used to drive through proposals that would not have broad support.
* Following a decision-making meeting, a summary of decisions and document dispositions SHALL be published as soon as is practical. 
  * This will be addressed if the meeting minutes are available in a timely fashion.
* When there is insufficient time for review in a real-time meeting, non-real-time consensus approaches SHOULD be considered.  
* In non-real-time meetings, consensus SHOULD be developed by using [Review and Approval](#GSF-approval-process) periods.
  * Using the group mailing list
  * Using GitHub "Review and Approval" label
* Proposals SHALL be available for a given period.

## Using Supermajority vote to achieve agreement 
### Phrasing of Voting Questions
* The Chair ensures that questions to be voted upon SHALL be phrased concisely and unambiguously. 
* Questions SHOULD NOT be phrased as the "The group SHALL not do xyz". Examples of appropriate questions are:
  * SHALL the Group agree on the Specification?
  * SHALL the liaison be approved?
  * SHALL the new Work Package be approved?
  * SHALL the existing Work Package be stopped?
  * If the issue is to choose between two options (i.e. A or B), an example of the appropriate question may be:
  * SHALL the Group agree on Option A or Option B?
* The option of receiving no less than 3/4 of the Supermajority Votes SHALL be the Group's decision.
* If the issue is to choose between three or more options, the Group SHOULD use informal voting to reduce the number of options to two, and then use formal voting, if necessary.

### Voting on Technical Issues

Note: Supermajority Vote - 1 Organisation has a one vote

*	Before voting, a clear definition of the issuer SHALL be provided by the Chair.
* Members eligible to vote SHALL only be entitled to one vote each.
* Each member MAY cast its vote as often as it wishes, and the last vote it casts counts.
* Voting MAY be performed electronically.
* Voting MAY be performed by showing hands and members announcing their vote verbally one by one, or paper ballots.
* The result of the vote SHALL be recorded in the meeting minutes.
* Groups MAY use informal voting to reach consensus. If the Group is still unable to reach a consensus, then a formal vote MAY be taken. 
* Each member's electronic vote SHALL be electronically acknowledged to confirm participation in the vote.
* The voting period for proposals are:
  * In-person-meetings require at least 30 days prior written notice
  * Teleconference meetings require at least 7 days prior written notice
  * Electronic voting MUST remain open for no less than 7 days.

> Note: electronic votes require no advance notice but must be made pursuant to a clear and unambiguous ballot with only “yes” and “no” options, and the voting must remain open for no less than 7 days.  These notification requirements with respect to the Project may be overridden upon unanimous consent of all Steering Members and General Members that have attended and participated in at least 50% of the last 4 meetings of the Project.

## GSF Approval Process
<figure>
	<img src="images/R_A_1.svg" alt="Review & Approval">
	<figcaption>Review & Approval</figcaption>
</figure>

In the Standards Development Organizations (SDOs), the Approval or rejection of a contribution follows a democratic process; the majority. This differs from an Open-Source organization that typically follows a meritocratic process where the Maintainer decides what to accept or reject. If a person doesn't like the decision that their contribution is rejected, they can "fork" the Project. 
The goal for an SDO is to reach interoperability; therefore, "forking" is not the solution to a technical dispute. If there is a sustainable objection in a contribution, the resolution is via a vote.

The Review & Approval process implies that all the contributions need to be accepted by the Working Group before being merged.

### Review & Approval Process
* **Review period**:
    * Period of time during which the contribution will be under review before being merged.
      * The period can be: 0, 1, 2, 3, 5, 7, 14 days
      * 0 days imply that the contribution is merged without Working Group review

* **Comments or Objections**:
    * During the Review & Approval process, members MAY raise comments or objections.
      * "Comments" MUST be considered by the Working Group, but they MAY be dismissed if the Group thinks that they are not relevant.

      * "Objections" MUST be considered, and the Working Group cannot dismiss them without being reviewed. 
      * If a contribution receives an "objection", the Group MUST resolve the issue with the person that objects, deciding the status of the contribution. If the "objection" is sustained, meaning the person doesn't remove it, then the Group will have to recur to a vote to resolve it.

* **Approval Criteria**:
    * A contribution is considered "approved", and therefore, it can be merged if:
      * The contribution has not received any sustainable objection during the review period, AND
      * At least 3 reviewers have indicated that they agree with the contribution
    * If a sustained objection is received, the contribution cannot be merged, even if 3 or more contributors agreed with the contribution. 
    * If during the review period a contribution receives a comment, it is up to the Group or Maintainer to accept the comment or not. In any case, to merge the contribution, at least 3 reviewers MUST indicate that they agree with the contribution.

## GSF Work Package
### Work Package - Life-Cycle

<figure>
	<img src="images/High-level.svg" alt="Work Package Life-Cycle">
	<figcaption>Work Package Life-Cycle</figcaption>
</figure>

Note:
```
Appendix A - Traditional Mode Governance - 4. Deliverable Development Process

4.1. Pre-Draft. Any Working Group Participant or Contributor may submit a proposed initial draft document as a candidate Draft Deliverable of that Working Group. The Working Group chair will designate each submission as a "Pre-Draft" document.
4.2. The Working Group Participants must first approve each Pre-Draft document of a Working Group of that Working Group to become a Draft Deliverable. Once the Working Group approves a document as a Draft Deliverable, the Draft Deliverable becomes the basis for all going forward work on that deliverable.
4.3. Working Group Approval. Once a Working Group believes it has achieved the objectives for its deliverable as described in the Scope, it will progress its Draft Deliverable to "Working Group Approved" status.
4.4. Final Approval. Upon a Draft Deliverable reaching Working Group Approved status, the Project Chair or his/her designee will present that Working Group Approved Draft Deliverable to all Steering Committee for Approval. Upon Approval by the Steering Committee, that Draft Deliverable will be designated an "Approved Deliverable."
4.5. Publication and Submission. Upon the designation of a Draft Deliverable as an Approved Deliverable, the Project Chair will publish the Approved Deliverable in a manner agreed upon by the Working Group Participants (i.e., Project Participant only location, publicly available location, Project maintained website, Project member website, etc.). The publication of an Approved Deliverable in a publicly accessible manner must include the terms under which the Approved Deliverable and/or source code is being made available under, as outlined in the applicable Working Group Charter.
4.6. Submissions to Standards Bodies. No Draft Deliverable or Approved Deliverable may be submitted to another organization without Approval by the Steering Committee. Upon Approval by the Steering Committee, the Project Chair will coordinate the submission of the applicable Draft Deliverable or Approved Deliverable to another standards development organization with Joint Development Foundation Projects, LLC. Working Group Participants that developed that Draft Deliverable or Approved Deliverable agree to grant the copyright rights necessary to make those submissions.
```

In this section, the diagram below depicts the development phases of technical documents.
<table>
  <caption>Work Package Lifecycle</caption>
  <thead>
    <tr>
	    <th>Phase</th>
	    <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
	    <td><strong>Work Package</strong></td>
      <td>In this phase the group agrees the scope of the work to be developed.</br>
          Any member can provide a new Work Package proposal, the document is discussed among the group and further elaborated.
          The group will vote whether the Work Package is formally approved and endorsed by the majority of the group or rejected.</br>
          If the proposal is approved, the Work Package is moved to the next phase, <strong>Technical Development</strong>. </td>
    </tr>
    <tr>
	    <td><strong>Development</strong></td>
      <td>A Technical Specification MAY be composed of one or more documents:
        <ul>
          <li><strong>Requirements Document</strong>, (RD)</li>
            <ul><li>It contains the business requirements (not technical requirements). The business requirements are derived from the Use Cases described in the <strong>RD</strong> document.</li></ul>
          <li><strong>Architecture Document</strong>, (AD)</li>
            <ul><li>Document that describes all functional elements of the system and its interfaces or reference points.</li></ul>
          <li><strong>Technical Specification Document(s)</strong>, (TS)</li>
            <ul><li>It refers to a set of documented requirements to be satisfied by a material, design, product, or service. It helps to understand the configuration and architecture of a system.</li></ul>
          <li><strong>Supporting Document(s)</strong>, (SUP)</li>
            <ul><li>Contains profile data, metadata, schemas, etc.</li></ul>
        </ul>
        <strong>Note:</strong> in some cases the group MAY agree to develop a single document that contains the above list as sections.
        Each document will follow the phases described in this table:
      </td>
   </tr>
   <tr>
	    <td><strong>Consistency Review</strong></td>
	    <td>In this phase, the document(s) developed by the WG are formally reviewed by the group. A Review period is open for members to submit their comments. After this period, the Working Group will address the issues received. </td>
   </tr>
      <tr>
	    <td><strong>WG Approval</strong></td>
	    <td>Once the WG completes the <strong>Consistency Review</strong> the document(s) MUST be agreed by the WG (in a Review & Approval) before sending the document(s) to the Organization Team for formal <strong>Ratification</strong>.</td>
   </tr>
   <tr>
	    <td><strong>Ratification</strong></td>
	    <td>Once the WG approves the document(s), the document(s) are sent to the Steering Committee for   <strong>Ratification</strong>.</td>
   </tr>   
   <tr>
	    <td><strong>Publication | Maintenance</strong></td>
	    <td>Upon Steering Committee Ratification, the document(s) are ready for <strong>Publication</strong>.
      <ul>
        <li>To publish the document(s), the Maintainer will merge the "agreement" branch into the "publication" branch. 
        <li>A new <strong>Release Tag</strong> will be produce with the content in the "publication" branch and stored in the Release section of the GitHub repository.</li>
        <li>The WG SHOULD open a "dialogue" with the public via <strong>GitHub Issues</strong>.</li>
        <li>The input collected during the <strong>Maintenance</strong> phase SHOULD be used to improve the Technical Specifications as well as to collect business requirements for future releases.</li>
       </ul>
      </td>
   </tr>   
  </tbody>
</table>

### Work Package - Deliverables

<figure>
	<img src="images/Development.svg" alt="GSF Work Package Deliverables">
	<figcaption>GSF Work Package Deliverables</figcaption>
</figure>

### Work Package Life-Cycle (Details)
<figure>
	<img src="images/detail-level.svg" alt="GSF Work Package Life-Cycle">
	<figcaption>GSF Work Package Life-Cycle</figcaption>
</figure>

### Work Package - Breakdown

<figure>
	<img src="images/work-package.svg" alt="GSF Work Units">
	<figcaption>GSF Work Package Breakdown</figcaption>
</figure>


#### Work Package
* The Work Package (WP) SHALL describe the Scope and expected deliverables and SHALL require WG approval
* WIs are how release packages (version x.y.z) are defined

##### Epics
* It could be a feature, customer request or business requirement
* It is recommendable to define a list of Epics that will be formed the release package for the corresponding Work Package
* The WG SHOULD define a placeholder for each Epic with few lines of description
* The Epics can be broken down into user stories and tasks which are not defined in detail at the creation of the Work Package

## GSF Branch Strategy
### GSF Trunk-Based Development
* Apply changes to `main` branch
* Small, simple changes
  * Fewer merge conflicts
  * Easy to review content
  * Encourages Pull Requests
  * Simple to Review

### Release Flow Branching Structure
<figure>
	<img src="images/release-flow-branching.svg" alt="GSF Release Flow Branching Structure">
	<figcaption>GSF Release Flow Branching Structure</figcaption>
</figure>

#### GSF GitHub Workflow
<table>
  <caption>GitHub Workflow</caption>
  <thead>
    <tr>
	    <th>Branch</th>
	    <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
	    <td><i>Rel vX.Y.Z</i></td>
      <td>Release-tag's contain all the different versions of the Technical Specifications that have been approved by the Working Group and ratified by the Technical Steering Committee. The name of the release tag will follow [Semantic Versioning](#semantic-versioning) principles.</td>
   </tr>
    <tr>
	    <td><i>main</i></td>
      <td>This branch contains the latest content approved by the Working Group, ratified by the Working Group. Its content will be moved into a release-tag, to preserve the content of the version after Working Group Final Approval and Steering Committee Ratification</td>
   </tr>
   <tr>
	    <td><i>feature-branch-x</i></td>
	    <td>Feature branches are dedicated to developing specific features, concepts, sections, etc. These branches are not stable, are short-live, should be merged into "main" regularly. </td>
   </tr>
  </tbody>
</table>

<figure>
	<img src="images/single-trunk-branch.svg" alt="GSF Single-Trunk Based Branch Flow">
	<figcaption>GSF Single-Trunk Based Branch Flow</figcaption>
</figure>

#### GitHub Repositories

<table>
  <caption>GitHub Workflow</caption>
  <thead>
    <tr>
	    <th>Branch</th>
	    <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
	    <td><i>Rel vX.Y.Z</i></td>
      <td>Release-tag's contain all the different versions of the GSF Deliverables that have been approved by the Working Group and ratified by the Technical Steering Committee. The name of the release tag will follow Semantic Versioning principles.</td>
   </tr>
    <tr>
	    <td><i>main</i></td>
      <td>This branch contains the latest revision of the GSF Deliverables approved by the Working Group. Its content will be moved into a release-tag, to preserve the content of the version.</td>
   </tr>
  </tbody>
</table>

```
Note: Group needs to decide if there will be "development" and "feature-branches" in the public repositories.
```

#### GitHub Publication
There are at least four different options to publish content using GitHub:
<figure>
	<img src="images/publication.svg" alt="Private vs Public">
	<figcaption>Private vs Public</figcaption>
</figure>

#### GitHub Access Rights
<table>
  <caption>GitHub Access Rights</caption>
  <thead>
    <tr>
	    <th>Role</th>
	    <th>Access Rights</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Members</td>
      <td><i>TRIAGE</i> - Can read and clone this repository. Can also manage issues and pull requests.</td>
   </tr>
    <tr>
      <td>Editors</td>
      <td><i>WRITE</i> - Can read, clone, and push to this repository. Can also manage issues and pull requests.</td>
   </tr>
   <tr>
      <td>Chairs</td>
      <td><i>WRITE</i> - Can read, clone, and push to this repository. Can also manage issues and pull requests.</td>
   </tr>
   <tr>
      <td>Maintainer</td>
      <td><i>ADMINISTRATOR</i> - Can read, clone, and push to this repository. They can also manage issues, pull requests, and some repository settings.</td>
   </tr>
  </tbody>
</table>

## Documentation
### Semantic Versioning

<figure>
	<img src="images/semantic_versioning.svg" alt="Semantic Versioning">
	<figcaption>Semantic Versioning</figcaption>
</figure>

<table>
  <caption>Document Version</caption>
  <thead>
    <tr>
	    <th>Field</th>
	    <th>Use</th>
	    <th>Description</th>
    </tr>
  </thead>
  <tbody>
  <tr>
    <td>X</td>
    <td><i>Major Version Indicator</i></td>
    <td>This mandatory field SHALL identify the major version of the document as determined by the WG.
      Major versions contain major feature additions; MAY contain incompatibilities with previous document or specification revisions; and MAY change, drop, or replace existing interfaces. Initial releases are “1_0”.
    </td>
  </tr>
  <tr>
    <td>Y</td>
    <td><i>Minor Version Indicator</i></td>
    <td>Minor version of the document. This mandatory field SHALL identify the minor version of the document. It is incremented every time a minor change is made to the approved document version. Minor versions MAY contain minor feature additions, be compatible with the preceding Major_Minor specification revision, and MAY provide evolving interfaces. The initial minor release for any major release is “0”, i.e. 1_0</td>
   </tr>
   <tr>
    <td>Z</td>
    <td><i>Service Indicator</i></td>
    <td>Service indicator for the document. Incremented every time a corrective update is made to the <strong>Approved</strong> (not draft) document version by the WG.
    This field is OPTIONAL and SHALL be provided whenever a service release of the document is made. The first service indicator release SHALL be “_1” for any Major_Minor release.
    Service indicators are intended to be compatible with the Major_Minor release they relate to but add bug fixes. No new functions will be added through the release of Service Indicators.
    </td>
  </tr>
  </tbody>
</table>

## Licenses
This section provides a recommendation on how to communicate software or document licenses information in a project.

### Software Code Licenses

Ideally, the Project SHOULD communicate the software license information via three different methods:

* In the README file
* Inside of the Repository with a ```License.txt``` document
* Inside of each code file created by the Group

#### Statement in README File
Insert in the README file one of these statements (depending on the license type):

```
![GSF license](https://img.shields.io/badge/License-MIT-brightgreen)

```

The README file will display one of these three licenses:

* ![GSF license](https://img.shields.io/badge/License-MIT-brightgreen)

In addition, it is recommended to include a plain text statement of the license in the README file for accessibility purposes and enable parsing by automated tooling. This can be done by having a "License" section with one of the following, as appropriate:

* This Project is licensed under the MIT license.

#### License File in the Repository
Insert in the Repository a file called ```License.txt```. 

The Maintainer or Chair can copy the corresponding license file from the [templates/license](https://github.com/green-software-foundation/templates/Licenses) Repository and upload it to the project repository.


#### License Reference in each Source Code File
The recommendation is that projects SHOULD use [SPDX short-form license identifiers](https://spdx.dev/ids/) in all source code and documentation files that are **original to the Project**.


Each source code created by the Project SHOULD have one of these SPDX license identifiers: (depending on the type of source code license allocated to the Project)

* **for an MIT license:**

```
# SPDX-License-Identifier: MIT
# Copyright Contributors to the Green Software Foundation
```

If the Project needs to include source code or documents from a different upstream project, the recommendation is to retain those files in **unmodified form**  _**(don't add identifiers)**_.

Also consider to:

* keep these files in sync with the upstream Project
* ask the upstream Project to insert the identifiers on their source code files/documents.

### Technical Document License
In projects where the main deliverables are technical documents, each document MUST have a legal disclaimer.

The legal disclaimer to insert in each project document SHOULD be:

```
© GSF 2021, All rights reserved.

"THESE MATERIALS ARE PROVIDED "AS IS." The parties expressly disclaim any warranties 
(express, implied, or otherwise), including implied warranties of merchantability, non-infringement, 
fitness for a particular purpose, or title related to the materials. The implementer and user assume the entire risk as to 
implementing or otherwise using the materials 

IN NO EVENT WILL THE PARTIES BE LIABLE TO ANY OTHER PARTY FOR LOST PROFITS OR ANY FORM OF 
INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES OF ANY CHARACTER FROM ANY CAUSES 
OF ACTION OF ANY KIND WITH RESPECT TO THIS DELIVERABLE OR ITS GOVERNING AGREEMENT, WHETHER 
BASED ON BREACH OF CONTRACT, TORT (INCLUDING NEGLIGENCE), OR OTHERWISE, AND WHETHER OR NOT 
THE OTHER MEMBER HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGE."
```


## Reference Material
### Documents

* [Dictionary](https://github.com/green-software-foundation/dictionary)
* [Templates](https://github.com/green-software-foundation/templates)

### Collaboration Tools
* [Groups.io(https://lists.greensoftware.io/g/main/subgroups)
* [GitHub](https://github.com/green-software-foundation)
### GitHub
* [GSF GitHub Training Material]()
* [Issue Creation](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue)
* [Creation Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
* [Managing Project Boards](https://help.github.com/en/github/managing-your-work-on-github/managing-project-boards)

