# TSC Materials for GenevaERS

The Technical Steering Committee is the highest governing body for the GenevaERS project.  This directory contains the meeting notes, process documentations, and other materials related to this project.

Below is the initial checklist for starting up the GenevaERS project.  

## Project Intake checklist

This is a checklist for TSC's to review as part of the intake process. The TSC should review this entire list during the kickoff meeting. For anything outstanding, create an [issue](../issues) to track and link to it in the list

- TSC Record Keeping
  - [x] Location for TSC documents and meeting notes ( recommendation is ```tsc``` directory in main repo, and then ```meetings``` under the ```tsc``` directory )
  - [x] Copy this checklist to the above location for tracking
- Existing Project Governance
  - [x] README.md file exists
  - [x] Project License exists ( LICENSE.md ) and aligned with the [Open Mainframe Project IP Policy](https://github.com/openmainframeproject/foundation/blob/master/CHARTER.md#12-intellectual-property-policy)
  - [x] Any third-party components/dependencies included are listed along with their licenses ( THIRD_PARTY.md )
  - [x] Governamce defined, outlining community roles and how decisions are made
  - [x] Contribution Policy defined ( CONTRIBUTING.md )
  - [x] Code of Conduct defined
  - [ ] Release methodology defined ( RELEASE.md )
- New Project Goverance
  - [x] TSC members identified
  - [ ] First TSC meeting held
  - [ ] TSC meeting cadence set and added to project calendar
- Current tools
  - [x] Source Control (Github, GitLab, something else )
	- [ ] Issue/feature tracker (JIRA, GitHub issues)
  - Collaboration tools
    - [x] Mailing lists
      - [x] Move to groups.io ( create [issue on foundation repo] to setup/transfer )
    - [x] Slack
    - [x] Forums (Determined Not Applicable)
  - [x] Website.  See [GenevaERS](https://genevaers.org)
  - [ ] CI/build environment
- Project assets
  - [x] Domain name	( create [issue on foundation repo] to setup/transfer
	- [x] Social media accounts	to setup/transfer.  None held.
	- [x] Logo(s)
	- [x] Trademarks/mark ownership rights. None.
- Outreach
  - [x] New project announcement done ( https://github.com/openmainframeproject/foundation/issues/79  See Marketing Section below for steps )
  - [ ] Project added to Open Mainframe Project website and Open Mainframe Project landscape
- Graduation
  - [ ] CII Badge achieved ( apply at https://bestpractices.coreinfrastructure.org/en )
  - [ ] Committer Diversity established
  	- [ ] Add project to [OMP Dev Analytics](https://lfanalytics.io/projects/open-mainframe-project) ( create [issue on foundation repo] to trigger )
	- [ ] Commit/Contribution growth during incubation
	- [ ] Committers defined in the project	( [COMMITTERS.csv](COMMITTERS.csv) or [COMMITTERS.yml](COMMITTERS.yml) )
  - [ ] TAC representative appointed
  - [ ]	License scan completed and no issues found
  - [ ] Code repository imported to Open Mainframe Project GitHub organization
    - [ ] Developer Certificate of Origin past commit signoff done and DCO Probot enabled.

The following are additions to the TSC template from other items for the project to consider.  

- Marketing Steps to Launch (from: https://github.com/openmainframeproject/foundation/issues/79)
  - [x] Provision GitHub repo
  - [ ] Send out questionnaire ( new project )
  - [ ] Create Landscape entry ( https://github.com/openmainframeproject/omp-landscape/ )
  - [ ] Received completed questionnaire
  - [ ] Build announcement and get approval
  - [ ] Schedule announcement and social promotion ( provide date )
  - [ ] Push Landscape entry live ( https://github.com/openmainframeproject/omp-landscape/ )
- Active Stage Criteria: (from https://github.com/openmainframeproject/tac/blob/master/process/project_stages.md#active-stage)  To graduate from Incubation Stage, or for a new project to join as an Active Stage project, a project must:
  - [ ] Complete the proposal process plus
  - [ ] Have committers from at least two organizations.
  - [ ] Have achieved and maintained a Core Infrastructure Initiative Best Practices Badge.
  - [ ] Explicitly define a project governance and committer process.
  - [ ] Have a public list of project adopters for at least the primary repo (e.g., ADOPTERS.md).
  - [ ] Complete a code licensing scan to ensure licensing is inline with the OMP guidelines
  - [ ] Elect or appoint a project lead to represent the project on the TAC
  - [ ] Receive a supermajority vote from the TAC to move to accepted stage.
  - [ ] Projects start at the Active Stage if they can demonstrate sufficient maturity. Projects can remain in an Incubation Stage indefinitely, but they are normally expected to move to Active Stage within two years.


[issue on foundation repo]: https://github.com/openmainframeproject/foundation/issues/new/choose
