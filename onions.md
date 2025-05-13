# Operationalizing Network & service abstractIONS (ONIONS)

## Scope/Mission

* **Reference** for network/service abstractions modelling in the IETF
    + Build and provide a big picture of the operational needs and motivations for these abstractions
    + Structure the effort on Service and Network models (and their maintenance) together with glues with underlying devices models
       - Define models for network and service abstractions with support from operators
       - Maintain network and service models (L3SM, L2SM, L2NM, L3NM, ACaaS, SAP, Slicing, VN, and ACTN, in particular) based on operational feedback
       - Explore approaches for mapping between various abstraction layers
* **Provide recommendations** on operationalizing YANG APIs (YANG2API)
    + Investigate required components so that YANG modules can be easily consumed
    + These components are meant to programmatically transform YANG models into key open APIs specifications
* **Assess the applicability** of these abstractions to accommodate specific operational use cases and deployments.
* **Assess the realization** of the intended abstractions and identify gaps, if any
    + Typically, assess interactions with required control and data plane features to implement an intended service in a network
* **Coordinate with the routing area** for evaluating OPS needs of proposed solutions that are motivated by a given abstraction need (e.g., slicing)
    + 2-way coordination to put in place

## Priority Items

* YANG2API (code/tools)
* LxNM refresh based on deployment experience (see candidate issues [here](https://github.com/oscargdd/lxnm-bis/issues))
* AC Data Models applicability for network/cloud context

## Relationship with Existing WGs

* NMOP
   + Topology matters stay in NMOP
* TEAS/CCAMP
   + Offload some of the work on data modelling to ONIONS
   + These WGs can continue specify data models for the protocols/protocol extensions defined in these WGs 
* OPSAWG
   + Offload AC/SAP/LxNM to ONIONS
   + Future relevant work on abstractions will be directed to ONIONS

## Other Inputs 

* "Kind of single pane of glass for network consumption, which is great for having a common understanding among
   interested people on what offer from IETF networks to the consumers of them."
    + "Simpler way of navigating the complexity of the different ways and needs in which the IETF network can be consumed."
* "Given the abstracted nature of these NMs and SMs, hackathon work could be realized in ONIONS to test the veracity of
   the work with multiple vendors"
    + "One could build software to implement the higher abstractions and speak device-level down to the devices."
    + "Show use of IETF, OC, and vendor device models to demonstrate the abstractions are doable
       and thought-through (part of that assess the realization)"
* "Investigate and possibly specify how IETF YANG models could work together with TMF(640)"
    + "Offer an approach to access an IETF service modeled defined API like the network management system."
    + "Doing this with low overhead and low impedance mismatch is critical to achieve robust operations and high change velocity."
* "Improving service models. For example, adding operational state, which I’ve found to be a really lacking area today"
* "Share with a wider community an Orchestron system that is engineered up from the idea of declarative mappings
  between modeled data, which is exactly what one would need to map in a natural manner from IETF YANG service model to device models"
* "The YANG mapping layer enables application independence at the layers above reducing integration costs,
  potentially reducing operational complexity in requiring multiple systems and swivel chairing and then utilising
  human intelligence to understand the difference between"
* "The fragmentation make it difficult to introduce automation and or ML/AI end to end"
* "never understood why things were so scattered"
* "Propose profiles and integrate all components"




