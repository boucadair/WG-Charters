# ONIONS WG Charter

A variety of service abstraction mechanisms are used in large networks to provide differentiated services, simplify provisioning, and decouple service operations from underlying network operations. These include (but are not limited to) VPNs, service function chains, traffic-engineered services, attachment circuits, and network slicing. The [IAB NEMOPS workshop](https://datatracker.ietf.org/doc/draft-iab-nemops-workshop-report/) highlighted the challenges faced by operators to manage and automate service abstractions reliably. Notably, the operational workflows for deploying, monitoring, troubleshooting, and evolving these service abstractions are inconsistent. In particular, integration is complex when the components needed for a given service abstraction are not necessarily aligned. Much of the machinery to define these abstractions already exists across multiple IETF efforts. 

The Operationalizing Network & service abstractIONS (ONIONS) Working Group aims to make it easier to implement and use the IETF's service and network abstractions, with the goal of improving network automation, operational efficiency, and interoperability.

For the purposes of this WG, the term "Abstraction" refers to the process of defining simplified, high-level constructs that represent network and service-level capabilities. Abstraction enables interaction between management components, and automation of management systems without directly exposing the underlying device-specific implementations.

To achieve this goal, the ONIONS WG will serve as the focal point for network and service abstraction modeling in the IETF and undertake the following activities, with the objective of improving consistency and integration:

1. Providing a comprehensive overview of operational needs and motivations for network and service abstractions,
1. Coordinating service and network abstraction work, including interactions with underlying device YANG data models,
1. Maintaining YANG data models for network and service abstractions,
1. Evaluating whether YANG data model activities in (3) necessitate changing the Automating Service and Network Management Framework defined in RFC 8969.

In addition to these, the WG will also address:

Operators commonly expose service abstractions through APIs built from YANG data models; the ONIONS WG will provide guidance and requirements for making these YANG-based service APIs automatable and consumable by external systems in a predictable and interoperable manner across systems and vendors, including upper-layer Operations and Business Support Systems (OSS/BSS). The WG will develop guidelines for integrating IETF YANG data models with frameworks developed outside of the IETF (e.g., TMF640), to improve consistency and reduce integration friction, focusing on API-based integration. Additionally, the WG will assess the applicability of these abstractions to accommodate specific operational use cases and deployments, ensuring relevance to real-world environments.

The ONIONS WG will evaluate realization approaches and perform gap analyses of intended abstractions. This involves assessing interactions with control and data plane features necessary to implement services within networks. The WG will identify and work towards addressing any identified gaps in the realization of these abstractions, coordinating with relevant WGs as necessary. Work that is technology- or protocol-specific will be coordinated with, and carried out in, the relevant WGs.

Furthermore, ONIONS WG will coordinate with the relevant WGs to evaluate operational needs of abstraction-driven solutions (e.g., network slicing in Routing Area). YANG data models that are currently being progressed in other WGs, but are relevant to the ONIONS WG charter, could be considered to be moved to ONIONS with agreement from the relevant ADs, and rough consensus from the originating WG. Moreover, ONIONS WG will inform relevant WGs as appropriate (especially during adoption and WGLC) while the actual discussions happen on the ONIONS list. The ONIONS WG may have joint meetings with relevant WGs if and when deemed appropriate.

The ONIONS WG will catalogue tooling-related resources in the WG GitHub or Wiki, including but not limited to existing tools, gaps, recommendations, examples of their use, example implementations, and relevant artifacts from hackathons or interoperability events. The WG is expected to encourage and support members to participate in hackathons and community-driven validation efforts to test and refine its outputs.

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
| April 2026              | Send LSes to TMF, 3GPP, BBF, GSMA, Linux Foundation, and EANTC about ONIONS | Actively seek collaboration with other organizations|N/A|
| May 2026              | Set up central GitHub organization and wiki for tooling and implementation resources | Actively seek community inputs for maintaining it|N/A|
| December 2026              | Gather operational needs and motivations for network and service abstractions to inform YANG data model refresh work | Draft providing a catalog of use cases for L2NM/L3NM and Attachment Circuits YANG data models | Not published as RFC |
| March 2027                | WG adoption of YANG-based service APIs problem statement and requirements | Draft detailing the problem and requirements for operationalizing YANG APIs| Info|
| July 2027                |WG adoption of L2NM/L3NM refresh drafts |Updated drafts for L2NM and L3NM YANG data models based on operational feedback and deployment experiences, with attention to operational state data and identified gaps (e.g., SRv6 VPN).| PS|
| July 2027                |WG adoption of Attachment Circuits (AC) YANG Data Models applicability draft |Draft assessing AC YANG data models for network/cloud contexts, including use-case driven applicability and potential extensions| Info |
| November 2027            |Submission of Attachment Circuits (AC) YANG Data Models draft|AC applicability draft submitted for IESG review| Info |
| November 2027            |Submission of L2NM/L3NM refresh drafts|Refined L2NM and L3NM drafts submitted for IESG review| PS|
