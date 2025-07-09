# ONIONS WG Charter

> This is a retooling of the [raw version](onions-raw.md).  See that document for reference.

The Operationalizing Network & service abstractIONS (ONIONS) Working Group aims to make it easier to implement and use the IETF's service and network abstractions, with the goal of improving network automation, operational efficiency, and interoperability.

For the purposes of this working group, the term "Abstraction" refers to the process of defining simplified, high-level constructs that represent network and service-level capabilities. Abstraction enables interaction between management components, and automation of management systems without directly exposing the underlying device-specific implementations.

To achieve this, ONIONS will serve as the focal point for network and service abstraction modeling in the IETF. This includes (1) providing a comprehensive overview of operational needs and motivations for network and service abstractions, (2) structuring efforts on service and network models, including their maintenance and how they interact with underlying device models, (3) defining and maintaining models for network and service abstractions (e.g., L3SM, L2SM, L2NM, L3NM, ACaaS, SAP, Slicing, SAIN, VN, ACTN, and the automating service and network management framework) based on operational feedback, and (4) exploring approaches for mapping between various abstraction layers to enable seamless interoperability.

ONIONS will also develop recommendations for operationalizing YANG-based APIs (YANG2API). This involves investigating and defining the requirements to programmatically transform YANG modules into open API specifications for easier consumption by operators and systems. Additionally, the WG will assess the applicability of these abstractions to accommodate specific operational use cases and deployments, ensuring relevance to real-world environments.

The ONIONS WG will evaluate implementation approaches and perform gap analyses of intended abstractions. This involves assessing interactions with control and data plane features necessary to implement services within networks. The WG will identify and work towards addressing any identified gaps in the implementation of these abstractions, coordinating with relevant working groups as necessary.

Furthermore, ONIONS will coordinate with the Routing Area and other relevant WGs to evaluate operational needs of abstraction-driven solutions (e.g., slicing). This will involve facilitating two-way coordination to ensure efficient alignment of efforts.

The ONIONS WG will produce recommendations for tools using YANG-based APIs (YANG2API), updates to L2NM and L3NM models, assessments and recommendations for attachment circuits (AC) data models, approaches for mapping between abstraction layers, and guidelines for integrating IETF YANG models with external frameworks (e.g., TMF640). The ONIONS WG will also engage in hackathons and community-driven validation efforts to test and refine its outputs and produce proof-of-concept YANG2API tools.

## Relationship With Existing WGs

* NMOP
  * ONIONS will focus on abstractions, while topology-related efforts will remain in NMOP.
* TEAS/CCAMP
  * ONIONS will take on network and service data modeling efforts (e.g., LxSM), allowing TEAS and CCAMP to continue specifying models for protocols and protocol extensions (e.g., device models).
* OPSAWG
  * ONIONS will handle AC/SAP/LxNM work, enabling OPSAWG to focus on other operational topics.
  * Future abstraction-related work will be directed to ONIONS.

## Milestones

| Date                      | Milestone | Description |
|---------------------------|-----------| -------------|
| October 2025              | Send LSes to TMF, 3GPP, BBF, GSMA, Linux Foundations, and EANTC about ONIONS | Actively seek for collaboration with other organizations|
| March 2026                | WG adoption of YANG2API problem statement and requirements | Draft detailing the problem and requirements for operationalizing YANG APIs|
| July 2026                |LxNM refresh draft adoption |Updated drafts for L2NM and L3NM models based on operational feedback and deployment experiences, with attention to operational state data and identified gaps (e.g., SRv6 VPN).|
| November 2026            |Submission of LxNM refresh for IESG review |Refined L2NM and L3NM drafts submitted for IESG review|
| July 2026                |Attachment Circuits (AC) Data Models applicability draft adoption |Draft assessing AC data models for network/cloud contexts, including use-case driven applicability and potential extensions|
| November 2026            |Finalization of Attachment Circuits (AC) Data Models draft |Submission of AC applicability draft for IESG review|
| March 2026               |Abstraction mapping approaches draft |Draft exploring methods for mapping between abstraction layers|
| Ongoing as work progresses |Hackathon to demonstrate abstractions |Hackathon event showcasing vendor collaboration, abstraction feasibility, and proof-of-concept YANG2API tooling|
