# ONIONS WG Charter

The Operationalizing Network & service abstractIONS (ONIONS) Working Group aims to make it easier to implement and use the IETF's service and network abstractions, with the goal of improving network automation, operational efficiency, and interoperability.

For the purposes of this WG, the term "Abstraction" refers to the process of defining simplified, high-level constructs that represent network and service-level capabilities. Abstraction enables interaction between management components, and automation of management systems without directly exposing the underlying device-specific implementations.

To achieve this, ONIONS will serve as the focal point for network and service abstraction modeling in the IETF. This includes:

1. Providing a comprehensive overview of operational needs and motivations for network and service abstractions,
1. Structuring efforts on service and network YANG data models, including their maintenance and how they interact with underlying device YANG data models,
1. Defining and maintaining YANG data models for network and service abstractions,
1. Evaluating whether YANG data model activities in (3) necessitate changing Automating Service and Network Management Framework.

The ONIONS WG will also develop recommendations for operationalizing YANG-based APIs (YANG2API). This involves defining the requirements to programmatically transform YANG data models into API specifications for easier consumption by operators and systems. Additionally, the WG will assess the applicability of these abstractions to accommodate specific operational use cases and deployments, ensuring relevance to real-world environments.

The ONIONS WG will evaluate realization approaches and perform gap analyses of intended abstractions. This involves assessing interactions with control and data plane features necessary to implement services within networks. The WG will identify and work towards addressing any identified gaps in the realization of these abstractions, coordinating with relevant WGs as necessary.

Furthermore, ONIONS WG will coordinate with the Routing Area and relevant WGs to evaluate operational needs of abstraction-driven solutions (e.g., network slicing). YANG data models that are currently being progressed in other WGs, but are relevant to the ONIONS WG charter, will only be moved to ONIONS with agreement from the relevant ADs, and rough consensus from the originating WG. Moreover, ONIONS WG will inform relevant Routing Area WGs as appropriate (especially during adoption and WGLC) while the actual discussions happen on the ONIONS list.

The ONIONS WG will catalogue tooling-related resources in the WG GitHub or Wiki, including but not limited to existing tools, gaps, recommendations, examples of their use, example implementations, and relevant artifacts from hackathons or interoperability events. The WG will produce recommendations for new interfaces (e.g., YANG-based APIs (YANG2API)).  The WG is expected to encourage and support members to participate in hackathons and community-driven validation efforts to test and refine its outputs. Further, the ONIONS WG will produce updates to L2NM and L3NM YANG data models, assessments and recommendations for attachment circuits (AC) YANG data models, and guidelines for integrating IETF YANG data models with frameworks developed outside of the IETF (e.g., TMF640).

Some WG documents might not be published as IETF Stream RFCs and may instead be maintained as Internet-Drafts to support ongoing WG activities.

## Relationship With Existing WGs

* Technology- or protocol-specific modeling efforts (e.g., device-level YANG data models) remain the responsibility of their respective WGs.
* ONIONS WG will engage with other relevant working groups (e.g., NETMOD, NMOP) to gather requirements and input related to tooling.
* Any new requirements for changes to the YANG language identified during ONIONS WG discussions will be directed to the NETMOD WG for consideration.
* BESS/CCAMP/TEAS: ONIONS WG will take on future network and service data modeling efforts, while Technology- or protocol-specific modeling efforts remain.
* NMOP: ONIONS WG will focus on abstractions, while topology-related efforts will remain in NMOP. Network topology models are out of scope of ONIONS.
* OPSAWG: ONIONS WG will handle AC/SAP/L2NM/L3NM work, enabling OPSAWG to focus on other operational topics. Future abstraction-related work will be directed to ONIONS.


## Milestones

| Date                      | Milestone | Description | Intended Track |
|---------------------------|-----------| -------------|:--------------:|
| Ongoing as work progresses |Hackathon projects to demonstrate abstractions and develop any required tooling |Hackathon event showcasing vendor collaboration, abstraction feasibility, and proof-of-concept YANG2API tooling| N/A|
| October 2025              | Send LSes to TMF, 3GPP, BBF, GSMA, Linux Foundation, and EANTC about ONIONS | Actively seek collaboration with other organizations|N/A|
| November 2025              | Set up central GitHub organization for tooling and implementation resources | Actively seek community inputs for maintaining it|N/A|
| January 2026              | Gather operational use case requirements to inform YANG data model refresh work | Draft providing a catalog of use cases for L2NM/L3NM and Attachment Circuits YANG data models | Not published as RFC |
| March 2026                | WG adoption of YANG2API problem statement and requirements | Draft detailing the problem and requirements for operationalizing YANG APIs| Info|
| July 2026                |WG adoption of L2NM/L3NM refresh drafts |Updated drafts for L2NM and L3NM YANG data models based on operational feedback and deployment experiences, with attention to operational state data and identified gaps (e.g., SRv6 VPN).| PS|
| July 2026                |WG adoption of Attachment Circuits (AC) YANG Data Models applicability draft |Draft assessing AC YANG data models for network/cloud contexts, including use-case driven applicability and potential extensions| Info |
| November 2026            |Submission of Attachment Circuits (AC) YANG Data Models draft|AC applicability draft submitted for IESG review| Info |
| November 2026            |Submission of L2NM/L3NM refresh drafts|Refined L2NM and L3NM drafts submitted for IESG review| PS|
