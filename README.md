# Open Source at the US Census Bureau

This document describes the open source policy at the US Census Bureau.

## Our Mission

The Census Bureau's mission is to serve as the leading source of quality data about the nation's people and economy. We honor privacy, protect confidentiality, share our expertise globally, and conduct our work openly.

## Key Tenets

Where possible, the US Census Bureau will actively participate in open source projects aimed at increasing value to the public through our data dissemination efforts.  

* Foster a community around Census data and tools by encouraging and responding to real-time feedback on how our data products are used by researchers, non-profit, and for profit organizations.  
* Increase our organizational capacity to do more open source by delivering more Free and Open Source Software (FOSS) to the community. FOSS is software that does not charge users a purchase or licensing fee for modifying or redistributing the source code, in our projects and contribute back to the open source community.
* Identify opportunities to publish existing code under an open source license that may benefit the public.
* Identify opportunities to create new open source projects, and develop those projects in the open alongside community participation.  
* Adopt industry best practices for managing the lifecycle of our open source projects including standard release management and continuous integration approaches.
* Encourage “Issues” and accept “Pull Requests” (PRs) from the community.  
* Ensure that new Code Releases and Community Contributions meet the specified guidelines, detailed in the sections below.  
* Where feasible to do so, we will automate and also open source any testing procedures and encourage contributors to execute their own tests.

## Benefits of Open Source

As demonstrated by both the private and public sector, there are numerous benefits to encouraging FOSS. The use of FOSS allows for product customization, advances interoperability between tools, and improves the overall quality of the final product. Other benefits include:

* **Flexible usage.** The benefits of using FOSS compel the organization to meet citizen and business needs by modifying existing or creating new FOSS. FOSS is particularly suitable for rapid prototyping and experimentation. The testing process generates minimal costs, and the process encourages the identification and elimination of defects not recognized by the original development team.
* **Community involvement.** Publicly available source code enables continuous and broad peer review, increasing software reliability and security.
* **Cost-savings.** The ability to modify FOSS enables the Census Bureau to respond rapidly to changing missions and markets, through a shared cost of ownership model.
* **Reusability.** The code we create belongs to the American people as a part of the public domain.  FOSS creates real economic value by lowering the burden of replicating similar work or by allowing the private sector to build off of and create new businesses around code developed at the Census Bureau.

## Maximizing Community Involvement and Reuse

Active involvement from the open source community is integral to the success of open source code.  
The Census Bureau encourages contributions to its open source projects, whether it be code, commentary, bug reports, feature requests, or overall strategic direction.

Forks or clones of our code repositories are free to be re-distributed. This means code created by the Census Bureau can be integrated into work that is under a more restrictive license, even those that are not considered open source licenses.

This changes when our code repositories include code that was not created by the Census Bureau and carries an open license. Code previously released under an open source license and then modified by the Census Bureau or its contractors is considered a "joint work" and must be released under terms permitted by the original open source license.

The public can use our code as the basis of wholly proprietary and commercial systems. The Census Bureau would appreciate that users of our code disclose its lineage, but the Census Bureau maintains no legal right to require disclosure. Notifications that our work is used in a new system are always greatly appreciated.

## Open Source Licenses

Our License file for projects acknowledges that our work is in the US public domain, and uses [CC0](https://creativecommons.org/publicdomain/zero/1.0/) to waive copyright internationally.

However, certain projects will require the usage of licensed open source software not created by the Census Bureau. Some open source licenses make source code available under different terms and conditions. These terms and conditions specify how the code may be used, modified, or shared. When users modify Census Bureau code, they should review and understand the terms of the open source license in question.

Each project may need to modify or extend the above LICENSE and CONTRIBUTING files as needed for its own circumstances.

## Distribution of Code

There is a misconception that FOSS that is distributed to the public should not be integrated or modified for use in sensitive systems. On the contrary, FOSS is often preferred for use in sensitive systems, due in part to its increased auditability. In other words, security in FOSS must be designed never to rely on obscurity in how the code works.

In addition, while open source licenses permit the user to modify FOSS for internal use without obligating them to distribute source code to the public, when the user chooses to distribute the modified FOSS outside the user's organization, then the code is subject to whatever license it carries.

## Source Code Release Guidelines

The Bureau may release source code through the following process.

1. Verify that the Bureau ‘owns’ the code
1. Code is reviewed by ACSD for:
    * Obscenities and other inappropriate content
    * Usernames/Keys/Passwords and other user credentials are removed
    * Named servers, IP addresses are removed
    * Documentation is provided to explain the code and help others make use of it
1. Code is uploaded (via ACSD) to a public location via an approved user account e.g. [U.S. Census Bureau on GitHub](https://github.com/uscensusbureau).

## Source Code Contributions (from external sources) Guidelines

A key feature of OSS is the ability to accept contributions from non-Census credentialed sources into a projects base code. The following steps may be used to accept code from external contributors.

1. Code is reviewed by a SME that is familiar with the base/project.
1. Code is reviewed by ACSD for:
    * Obscenities and other inappropriate content
    * Usernames/Keys/Passwords and other user credentials are removed
    * Named servers, IP addresses are removed
1. Code is inspected via the same QA process that ACSD uses for newly written code.

## Thanks

The Census Bureau would like to thank our early CitySDK users and contributors, who provided significant feedback to improve who we do open source.  We’d also like to thank 18F and CFPB, where much of this policy was inspired.

## Future Changes

This policy is a living document and we welcome issues and pull requests.
