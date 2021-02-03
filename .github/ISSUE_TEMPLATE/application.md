---
name: application
about: Fill information necessary to determine approval
title: project-name
labels: project application
assignees: kulov, ross-bohr, szlatkow, aleks-ivanov

---

---

name: New Pipeline Foundation Project Application
about: Creates a public issue to track your projects application to join the Pipeline Foundation.
title: ''

---

## 1.   General Information

**Project Name:**

**License:**

**Contributor (Company, Organization or individual name(s)):**

**Existing OSS Project? (Yes/No):**

**Source Code URL:**

**Project Homepage URL (if different):**

**Project Transfer Signatories:**
Full legal name and __email address__ required of the individual(s) with the authority to transfer or contribute the project to the .NET Foundation. Note that if you'd prefer not to include this in the public application, it can be submitted via e-mail to contact@dotnetfoundation.org (referencing this issue number).

## 2.   Description
**Please provide a brief statement about your project in terms that are understandable to the target consumer of the library or project, i.e. an elevator pitch for the project:**


**Please provide a 1 sentence (<140 character) summary of your project to help users when searching the .NET Foundation projects**

## 3.   Project Governance
Please complete this section about who will be maintaining the open source project and how it will run.
**Project Lead:**
(Who is the primary contact point for the community and the .NET Foundation when discussing governance of the project.)

Name:   
 Email:   
 GitHub Profile URL:

**Committers:**

Which individuals have commit / write access to the repository, what is their GitHub ID and who is their employer (if contributions are on behalf of an employer)

**Governance Model:**

Please describe how new code changes are proposed to the project, how those changes are reviewed and how a decision is made to accept proposed changes. Also describe the process for identifying and appointing new committers.

**CLA**

If already an OSS project, was a Contribution License Agreement in place for contributions accepted? How does the project check who has signed one?

**CLA Notification Alias**
Provide an email address that will receive CLA related notifications from the .NET Foundation CLA automation

**Assignment Model.**  Under the .NET Foundation assignment model, project ownership and other intellectual property is assigned to the .NET Foundation and the .NET Foundation agrees to grantback a license to the contributor(s). 

**Contribution Model.**  Under the .NET Foundation contribution model, a project retains ownership of the project, but grants the .NET Foundation a broad license to the project’s code and other intellectual property. The project also confirms that the project’s submissions to .NET Foundation are its own original work (there are also instructions for any third party materials that might be included).


## 4.   Repository Layout
The .NET Foundation host guidance for new projects and details on recommended structure here:
[https://github.com/dotnet/home/tree/master/guidance](https://github.com/dotnet/home/tree/master/guidance)

Note that the open source repository should be the master where changes are made by the core development team using the same PR process that is used for non-committer contributions.

Please define below any changes you would want to make to your repositories as part of the process of joining the .NET Foundation

## 5.  Eligibility Criteria
Please complete the following for your project
* The project is built on the .NET platform and/or creates value within the .NET ecosystem.
- [ ] Yes 
- [ ] No
* The project produces source code for distribution to the public at no charge.
- [ ] Yes 
- [ ] No
* The project's code is easily discoverable and publicly accessible (preferably on GitHub).
- [ ] Yes 
- [ ] No
* The project contains a build script that can produce deployable artifacts that are identical to the official deployable artifacts, with the exception of code signing (Exception may be granted for strong name keys, though strongly encouraged to be committed. Exception relies on OSS signing being in the build script for public builds).
- [ ] Yes 
- [ ] No
* When applicable, project must use reproducible build settings in its toolchain.
- [ ] Yes 
- [ ] No
* The project uses [Source Link.](https://docs.microsoft.com/en-us/dotnet/standard/library-guidance/sourcelink)
- [ ] Yes 
- [ ] No
* The project uses either embedded PDBs or publish symbol packages to NuGet (if applicable).
- [ ] Yes 
- [ ] No
* The project code signs their artifacts as appropriate.
- [ ] Yes 
- [ ] No
* The project organization has 2FA enabled. Requiring 2FA must be done as part of onboarding if not already enabled.
- [ ] Yes
- [ ] No
* Libraries that are mandatory dependencies of the project are offered under a standard, permissive open source license which has been approved by the .NET Foundation (exceptions include a dependency that is required by the target platform where no alternative open source dependency is available such as the .NET Framework or a hardware specific library).
- [ ] Yes 
- [ ] No
* Committers are bound by a Contributor License Agreement (CLA) and/or are willing to embrace the .NET Foundation's CLA when the project becomes a Member.
- [ ] Yes 
- [ ] No
* The copyright ownership of everything that the project produces is clearly defined and documented.
- [ ] Yes 
- [ ] No
* The project has a public issue tracker where the status of any defect can be easily obtained.
- [ ] Yes 
- [ ] No
* The project has a published Security Policy.
- [ ] Yes 
- [ ] No
* The project has a home page which provides high level information about its status and purpose.
- [ ] Yes 
- [ ] No
* The project has a public communication channel where community members can engage with maintainers.
- [ ] Yes 
- [ ] No
* The project has a publicly available location where members can review and contribute to documentation.
- [ ] Yes 
- [ ] No

## 6.   PR Plan
Please summarize the public relations plan for the announcement when joining the foundation (and releasing as open source if appropriate). What is the main story we wish to promote, through what channels, what issues should we be aware of?  For significant news events then please also work with your .NET Foundation contact to ensure a [full PR plan](https://dotnetfoundation.sharepoint.com/Shared%20Documents/PR/Communications%20Plan%20TEMPLATE.docx?web=1) is developed.

## 7.   Infrastructure Requirements
Please describe any infrastructure requirements for the project. For example, how will build servers be operated? Any web hosting or service hosting requirements? Do we need to set up SSL certificates or provide Authenticode Code Signing arrangement for releases?


## 8.   Additional Notes
Please provide any additional information required or use this area for notes during the onboarding process. If this open source project has similarities with any other projects in this space then please detail them and why this project is different. If there are any potential issues that you feel the project might need help with early on then also state them here and discuss with your .NET Foundation Contact.
