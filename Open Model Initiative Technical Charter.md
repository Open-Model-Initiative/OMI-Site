# Technical Charter (the “Charter”) for Open Model Initiative a Series of LF Projects, LLC

**Adopted July 23, 2024**

This Charter sets forth the responsibilities and procedures for technical contribution to, and oversight of, the Open Model Initiative open-source project, which has been established as Open Model Initiative, a Series of LF Projects, LLC (the “Project”). LF Projects, LLC (“LF Projects”) is a Delaware series limited liability company. All contributors (including committers, maintainers, and other technical positions) and other participants in the Project (collectively, “Collaborators”) must comply with the terms of this Charter.

## Mission and Scope of the Project

The mission of the Project is to support open community development of openly licensed baseline AI models for image, video, and audio generation that individuals and organizations can use and augment in their own solutions. The scope of the Project includes collaborative development under the Project License (as defined herein), supporting the mission, including documentation, testing, integration, and the creation of other artifacts that aid the development, deployment, operation, or adoption of the open-source project.

## Technical Steering Committee (TSC)

The Technical Steering Committee (the “TSC”) is responsible for all technical oversight of the open-source Project.

- The TSC voting members are initially the Project’s Committers. At the inception of the project, the Committers of the Project will be as set forth within the “CONTRIBUTING” file within the Project’s code repository.
- The TSC may choose an alternative approach for determining the voting members of the TSC, and any such alternative approach will be documented in the CONTRIBUTING file.
- Any meetings of the Technical Steering Committee are intended to be open to the public and can be conducted electronically, via teleconference, or in person.

### TSC Projects

TSC projects generally involve Contributors and Committers. The TSC may adopt or modify roles, provided the roles are documented in the CONTRIBUTING file. Unless otherwise documented:

- **Contributors** include anyone in the technical community that contributes code, documentation, or other technical artifacts to the Project.
- **Committers** are Contributors who have earned the ability to modify (“commit”) source code, documentation, or other technical artifacts in a project’s repository.
- A Contributor may become a Committer by a majority approval of the existing Committers.
- A Committer may be removed by a majority approval of the other existing Committers.

Participation in the Project through becoming a Contributor and Committer is open to anyone so long as they abide by the terms of this Charter.

### TSC Responsibilities

The TSC will be responsible for all aspects of oversight relating to the Project, which may include:

- Coordinating the technical direction of the Project.
- Approving project or system proposals (including, but not limited to, incubation, deprecation, and changes to a sub-project’s scope).
- Organizing sub-projects and removing sub-projects.
- Creating sub-committees or working groups to focus on cross-project technical issues and requirements.
- Appointing representatives to work with other open-source or open standards communities.
- Establishing community norms, workflows, issuing releases, and security issue reporting policies.
- Approving and implementing policies and processes for contributing (to be published in the CONTRIBUTING file).
- Coordinating with the Series Manager of the Project (as provided for in the Series Agreement, the “Series Manager”) to resolve matters or concerns that may arise as set forth in Section 7 of this Charter.
- Discussing, seeking consensus, and where necessary, voting on technical matters relating to the code base that affect multiple projects.
- Coordinating any marketing, events, or communications regarding the Project.

### TSC Voting

While the Project aims to operate as a consensus-based community, if any TSC decision requires a vote to move the Project forward, the voting members of the TSC will vote on a one vote per voting member basis.

- Quorum for TSC meetings requires at least fifty percent of all voting members of the TSC to be present. The TSC may continue to meet if quorum is not met but will be prevented from making any decisions at the meeting.
- Except as provided in Sections 7.c. and 8.a., decisions by vote at a meeting require a majority vote of those in attendance, provided quorum is met.
- Decisions made by electronic vote without a meeting require a majority vote of all voting members of the TSC.
- In the event a vote cannot be resolved by the TSC, any voting member of the TSC may refer the matter to the Series Manager for assistance in reaching a resolution.

## Compliance with Policies

This Charter is subject to the Series Agreement for the Project and the Operating Agreement of LF Projects. Contributors will comply with the policies of LF Projects as may be adopted and amended by LF Projects, including, without limitation, the policies listed at [https://lfprojects.org/policies/](https://lfprojects.org/policies/).

- The TSC may adopt a code of conduct (“CoC”) for the Project, which is subject to approval by the Series Manager. In the event that a Project-specific CoC has not been approved, the LF Projects Code of Conduct listed at [https://lfprojects.org/policies](https://lfprojects.org/policies) will apply for all Collaborators in the Project.
- When amending or adopting any policy applicable to the Project, LF Projects will publish such policy, as to be amended or adopted, on its website at least 30 days prior to such policy taking effect; provided, however, that in the case of any amendment of the Trademark Policy or Terms of Use of LF Projects, any such amendment is effective upon publication on LF Project’s website.
- All Collaborators must allow open participation from any individual or organization meeting the requirements for contributing under this Charter and any policies adopted for all Collaborators by the TSC, regardless of competitive interests. The Project community must not seek to exclude any participant based on any criteria, requirement, or reason other than those that are reasonable and applied on a non-discriminatory basis to all Collaborators in the Project community.
- The Project will operate in a transparent, open, collaborative, and ethical manner at all times. The output of all Project discussions, proposals, timelines, decisions, and status should be made open and easily visible to all. Any potential violations of this requirement should be reported immediately to the Series Manager.

## Community Assets

LF Projects will hold title to all trade or service marks used by the Project (“Project Trademarks”), whether based on common law or registered rights. Project Trademarks will be transferred and assigned to LF Projects to hold on behalf of the Project. Any use of any Project Trademarks by Collaborators in the Project will be in accordance with the license from LF Projects and inure to the benefit of LF Projects.

- The Project will, as permitted and in accordance with such license from LF Projects, develop and own all Project GitHub and social media accounts, and domain name registrations created by the Project community.
- Under no circumstances will LF Projects be expected or required to undertake any action on behalf of the Project that is inconsistent with the tax-exempt status or purpose, as applicable, of the Joint Development Foundation or LF Projects, LLC.

## General Rules and Operations

The Project will:

- Engage in the work of the Project in a professional manner consistent with maintaining a cohesive community, while also maintaining the goodwill and esteem of LF Projects, Joint Development Foundation, and other partner organizations in the open-source community.
- Respect the rights of all trademark owners, including any branding and trademark usage guidelines.

## Intellectual Property Policy

Collaborators acknowledge that the copyright in all new contributions will be retained by the copyright holder as independent works of authorship and that no contributor or copyright holder will be required to assign copyrights to the Project.

- All inbound contributions to the Project must:
  - Be made using, and will be made available on an outbound basis under, the following licenses:
    - For software source code: Apache License, Version 2.0 available at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0);
    - For model parameters, weights, and metadata: the CDLA-Permissive 2.0 License, available at [https://cdla.dev/permissive-2-0](https://cdla.dev/permissive-2-0);
    - For documentation: Creative Commons Attribution 4.0 International License (available at [http://creativecommons.org/licenses/by/4.0/](http://creativecommons.org/licenses/by/4.0/)).
  - Be accompanied by a Developer Certificate of Origin ([http://developercertificate.org](http://developercertificate.org)) sign-off in the source code system that is submitted through a TSC-approved contribution process which will bind the authorized contributor and, if not self-employed, their employer to the applicable license.
- The Project may seek to integrate and contribute back to other open-source projects (“Upstream Projects”). In such cases, the Project will conform to all license requirements of the Upstream Projects, including dependencies, leveraged by the Project. Upstream Project code contributions not stored within the Project’s main code repository will comply with the contribution process and license terms for the applicable Upstream Project.
- The TSC may approve the use of an alternative license or licenses for inbound or outbound contributions on an exception basis. To request an exception, please describe the contribution, the alternative open-source license(s), and the justification for using an alternative open-source license for the Project. License exceptions must be approved by a two-thirds vote of the entire TSC.
- Contributed files should contain license information, such as SPDX short-form identifiers, indicating the open-source license or licenses pertaining to the file.

## Amendments

This Charter may be amended by a two-thirds vote of the entire TSC and is subject to approval by LF Projects.