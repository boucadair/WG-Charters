# ONIONS WG Charter

> This is a retooling of the [raw version](onions-raw.md).  See that document for reference.

The Operationalizing Network & service abstractIONS (ONIONS) Working Group aims to make it easier to implement and use the IETF's service and network abstractions, with the goal of improving network automation, operational efficiency, and interoperability.

For the purposes of this WG, the term "Abstraction" refers to the process of defining simplified, high-level constructs that represent network and service-level capabilities. Abstraction enables interaction between management components, and automation of management systems without directly exposing the underlying device-specific implementations.

To achieve this, ONIONS will serve as the focal point for network and service abstraction modeling in the IETF. This includes:

1. providing a comprehensive overview of operational needs and motivations for network and service abstractions,
1. structuring efforts on service and network models, including their maintenance and how they interact with underlying device models,
1. defining and maintaining models for network and service abstractions (i.e., at least the following models will be maintained by the WG: L2VPN Service Model (L2SM), L3VPN Service Model (L3SM), L2VPN Network Model (L2NM), L3VPN Network Model (L3NM), Attachment Circuit-as-a-Service (ACaaS), Service Attachment Points (SAP), Network Slicing, Service Assurance for Intent-Based Networking (SAIN), Virtual Network (VN), Abstraction and Control of TE Networks (ACTN), the Automating Service and Network Management Framework, and the YANG Data Model for Network and VPN Service Performance Monitoring).

ONIONS will also develop recommendations for operationalizing YANG-based APIs (YANG2API). This involves defining the requirements to programmatically transform YANG modules into API specifications for easier consumption by operators and systems. Additionally, the WG will assess the applicability of these abstractions to accommodate specific operational use cases and deployments, ensuring relevance to real-world environments.

The ONIONS WG will evaluate realization approaches and perform gap analyses of intended abstractions. This involves assessing interactions with control and data plane features necessary to implement services within networks. The WG will identify and work towards addressing any identified gaps in the realization of these abstractions, coordinating with relevant WGs as necessary.

Furthermore, ONIONS will coordinate with the Routing Area and other relevant WGs to evaluate operational needs of abstraction-driven solutions (e.g., slicing). This will involve facilitating two-way coordination to ensure efficient alignment of efforts. YANG data models potentially within the scope of other WGs will only be progressed here with agreement from the relevant ADs.

The ONIONS WG will collate tooling-related resources in the WG GitHub or Wiki, including but not limited to existing tools, gaps, recommendations, examples of their use, and relevant artifacts from hackathons or interoperability events. The WG will further produce recommendations for new tools (e.g. YANG-based APIs (YANG2API)).  The WG is expected to engage in hackathons and community-driven validation efforts to test and refine its outputs. Further, the ONIONS WG will produce updates to L2NM and L3NM models, assessments and recommendations for attachment circuits (AC) data models, and guidelines for integrating IETF YANG models with frameworks developed outside of the IETF (e.g., TMF640).

Some WG documents may not be published as IETF Stream RFCs and may instead be maintained as Internet-Drafts to support ongoing WG activities.

## Relationship With Existing WGs

* BESS/CCAMP/TEAS
  * ONIONS will take on network and service data modeling efforts, allowing BESS, CCAMP, and TEAS to continue specifying models for protocols and protocol extensions (e.g., device models).
* NMOP
  * ONIONS will focus on abstractions, while topology-related efforts will remain in NMOP.
* OPSAWG
  * ONIONS will handle AC/SAP/LxNM work, enabling OPSAWG to focus on other operational topics.
  * Future abstraction-related work will be directed to ONIONS.

## Milestones

| Date                      | Milestone | Description | Intended Track |
|---------------------------|-----------| -------------|:--------------:|
| Ongoing as work progresses |Hackathon to demonstrate abstractions |Hackathon event showcasing vendor collaboration, abstraction feasibility, and proof-of-concept YANG2API tooling| N/A|
| October 2025              | Send LSes to TMF, 3GPP, BBF, GSMA, Linux Foundations, and EANTC about ONIONS | Actively seek for collaboration with other organizations|N/A|
| March 2026                | WG adoption of YANG2API problem statement and requirements | Draft detailing the problem and requirements for operationalizing YANG APIs| Info|
| July 2026                |WG adoption of L2NM/L3NM refresh draft |Updated drafts for L2NM and L3NM models based on operational feedback and deployment experiences, with attention to operational state data and identified gaps (e.g., SRv6 VPN).| PS|
| July 2026                |WG adoption of Attachment Circuits (AC) Data Models applicability draft |Draft assessing AC data models for network/cloud contexts, including use-case driven applicability and potential extensions| Info |
| November 2026            |Submission of Attachment Circuits (AC) Data Models draft|AC applicability draft submitted for IESG review| Info |
| November 2026            |Submission of L2NM/L3NM refresh draft|Refined L2NM and L3NM drafts submitted for IESG review| PS|
