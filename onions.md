# Operationalizing Network & SErvice abstractioNs (ONSEN) WG Charter

Large networks rely on service abstraction mechanisms — for example, VPNs, service function chains, traffic engineering, attachment circuits, and network slicing — to deliver differentiated services and simplify provisioning. As the [IAB NEMOPS workshop](https://datatracker.ietf.org/doc/draft-iab-nemops-workshop-report/) highlighted, operational workflows for deploying, monitoring, and evolving these abstractions are inconsistent and poorly integrated, despite much of the underlying IETF prior work.

The ONSEN WG aims to make IETF service and network abstractions easier to implement and use, improving automation, operational efficiency, and interoperability. 

For this WG, the term "Abstraction" refers to the process of defining simplified, high-level constructs that represent network and service-level capabilities. Abstraction enables interaction between management components and automation of management systems without directly exposing the underlying device-specific implementations.

ONSEN will serve as the IETF's focal point for service and network abstraction modeling, with four core activities:

1. Documenting operational needs and motivations for network and service abstractions.
1. Coordinating abstraction work, using device-level YANG models as the basis for the abstraction
1. Maintaining key YANG data models, including refactoring or restructuring, which include at least the following: VPN Common Model, L2VPN Service Model (L2SM), L3VPN Service Model (L3SM), L2VPN Network Model (L2NM), L3VPN Network Model (L3NM), Attachment Circuit Common Model, Attachment Circuit-as-a-Service (ACaaS), Attachment Circuit Network Model, Service Attachment Points (SAP), Network Slicing, Service Assurance for Intent-Based Networking (SAIN), Virtual Network (VN), Abstraction and Control of TE Networks (ACTN), and the YANG Data Model for Network and VPN Service Performance Monitoring.
1. Developing reusable abstractions and a common foundation for service YANG data models that allow multiple IETF service models to be built on a shared extensible foundation.

The WG may develop new service or network YANG data models related to IETF technologies when gaps are identified.

Beyond these, ONSEN will define the interface between YANG-based service APIs and the OSS/BSS layer to enable automated and interoperable service orchestration across systems and vendors. This includes guidelines for aligning IETF YANG data models with external frameworks (e.g., TMF640), assessing abstractions against real-world deployment use cases, and identifying any gaps relevant to the RFC 8969 framework and the explanation of service models in RFC 8309. 

ONSEN will also evaluate realization approaches and perform gap analyses, identifying what's needed at the control and data plane to implement services — coordinating with relevant WGs for technology- or protocol-specific work.

The WG will catalogue tooling resources (tools, gaps, recommendations, examples, hackathon artifacts) in the WG GitHub or Wiki, and actively encourage participation in hackathons and interoperability events. 

## Work Items

1. Develop a problem statement that identifies gaps and issues with existing network and service YANG data models, drawing on operator experience, to guide the scope and priorities of the WG's modeling work
1. Update the YANG network data models for L3NM and L2NM
1. Update the YANG service data models for L3SM and L2SM
1. Develop a framework for reusable service YANG data models
1. Define the interface between YANG-based service APIs and the OSS/BSS layer

The WG may decide that some documents should remain as Internet-Drafts rather than get published as RFCs. This decision will be made on a case-by-case basis by consensus of the WG.

## Relationship With Existing WGs

* Technology- or protocol-specific modeling efforts (e.g., device-level YANG data models) remain the responsibility of their respective WGs.
* ONSEN WG will engage with other relevant WGs (e.g., NETMOD and NMOP) to gather requirements and input related to tooling.
* Any new requirements for changes to the YANG language identified during ONSEN WG discussions will be directed to the NETMOD WG for consideration.
* BESS/CCAMP/TEAS: ONSEN WG will take on future network and service data modeling efforts, while technology- or protocol-specific modeling efforts remain in these WGs.
* NMOP: ONSEN WG will focus on abstractions, while topology-related efforts will remain in NMOP. Network topology models are out of scope of ONSEN.
* OPSAWG: ONSEN WG will handle AC/SAP/L2NM/L3NM work, enabling OPSAWG to focus on other operational topics. Future abstraction-related work will be directed to ONSEN.


## Milestones

| Date                      | Milestone | Description | Intended Track |
|---------------------------|-----------| -------------|:--------------:|
| Ongoing as work progresses |Hackathon projects to demonstrate abstractions and develop any required tooling |Hackathon event showcasing vendor collaboration, abstraction feasibility, and proof-of-concept YANG-based service APIs tooling| N/A|
| April 2026              | Send LSes to TMF, 3GPP, BBF, GSMA, Linux Foundation, TIP, and EANTC about ONSEN | Actively seek collaboration with other organizations|N/A|
| December 2026              | Gather operational needs and motivations for updating network and service abstractions to inform YANG data model update work | Draft providing a catalog of use cases for L3SM/L2SM/L2NM/L3NM and Attachment Circuits YANG data models | Not published as RFC |
| March 2027                | WG adoption of a draft that defines the interface between YANG-based service APIs and the OSS/BSS layer | Draft detailing the interface between the OSS/BSS layer and the YANG APIs | PS|
| July 2027                |WG adoption of L2NM/L3NM update drafts |Updated drafts for L2NM and L3NM YANG data models based on operational feedback and deployment experiences, with attention to operational state data and identified gaps (e.g., SRv6 VPN).| PS|
| July 2027                |WG adoption of L2SM/L3SM update drafts |Updated drafts for L2SM and L3SM YANG data models based on operational feedback and deployment experiences, with attention to operational state data and identified gaps (e.g., SRv6 VPN).| PS|
