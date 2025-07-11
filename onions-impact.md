As the ONIONS [charter](./onions.md) is being discussed, here is an initial list of relevant I-Ds and working groups that may be impacted. This is an early effort to assess potential effects and ensure the impact is appropriately socialised.

## Charter
|WG|Remarks|
|--|--|
|TEAS|Offload some of the abstraction work on data modelling to ONIONS (slicing applicability, VN, transport model, ACTN); TEAS can continue specify data models for the protocols/protocol extensions defined in TEAS|
|CCAMP|Offload data modelling abstraction work to ONIONS; CCAMP can continue specify data models for the protocols/protocol extensions defined in CCAMP|
|OPSAWG|Offload AC/SAP/LxNM to ONIONS; Future relevant work on abstractions will be directed to ONIONS|
|NMOP|Topology matters stay in NMOP|
|BESS|VPN device models stay in BESS. Future service/network models will be worked in ONIONS|


## I-Ds
|WG|I-D|Title|Stay (S) in Current WG or Move (M) to ONIONS?|
|--|--|--|--|
|TEAS|draft-ietf-teas-te-service-mapping-yang|Traffic Engineering (TE) and Service Mapping YANG Data Model|?|
|TEAS|draft-dhody-teas-ietf-network-slice-mapping|IETF Network Slice Service Mapping YANG Model|M|
|TEAS|draft-ietf-teas-network-slice-topology-yang|IETF Network Slice Topology YANG Data Model|M|
|TEAS|draft-ietf-teas-5g-network-slice-application|IETF Network Slice Application in 3GPP 5G End-to-End Network Slice|S|
|TEAS|draft-ietf-teas-ns-controller-models|IETF Network Slice Controller and its Associated Data Models|M|
|TEAS|draft-ietf-teas-nrp-yang|YANG Data Models for Network Resource Partitions (NRPs)(1)|?|
|TEAS|draft-ietf-teas-ns-ip-mpls|Realizing Network Slices in IP/MPLS Networks(1)|S|
|TEAS|draft-ietf-teas-ns-models-applicability|Applicability of IETF-Defined Service and Network Data Models for Network Slice Service Management|M|
|CCAMP|draft-ietf-ccamp-yang-otn-slicing|Framework and Data Model for OTN Network Slicing|S|
|CCAMP|draft-ietf-ccamp-actn-optical-transport-mgmt|Integrating YANG Configuration and Management into an Abstraction and Control of TE Networks (ACTN) System for Optical Networks|S|
|OPSAWG||||
|NMOP|draft-ietf-nmop-simap-concept|SIMAP: Concept, Requirements, and Use Cases|S|
|BESS|draft-ietf-bess-l3vpn-yang|Yang Data Model for BGP/MPLS L3 VPNs|S|
|BESS|draft-ietf-bess-mvpn-yang|Yang Data Model for Multicast in MPLS/BGP IP VPNs|S|
|BESS|draft-ietf-bess-l2vpn-yang|YANG Data Model for MPLS-based L2VPN|S|
|BESS|draft-ietf-bess-evpn-yang|Yang Data Model for EVPN|S|
