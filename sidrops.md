## SIDROPS Charter (2025)

The global deployment of Secure Inter-Domain Routing (SIDR), consisting of Resource Public Key Infrastructure (RPKI), Origin Validation of BGP announcements, and BGPsec, is still underway, creating an Internet Routing System consisting of SIDR-aware and non-SIDR-aware networks. This deployment must be properly handled to avoid the division of the Internet into separate networks.  SIDR Operations Working Group (SIDROPS WG) is responsible for continuing the development of SIDR technology, encouraging its deployment, while ensuring as secure of a global routing system as possible, during the transition.

The SIDROPS WG is focused on deployment and operational issues, their mitigations, and experiences  with SIDR technologies that are part of the global routing system, as well as the repositories and Certification Authority (CA) systems that form part of the SIDR architecture.

SIDROPS develops guidelines for the operation of SIDR-aware networks and provides operational guidance on how to deploy and operate SIDR technologies in existing and new
networks. It also develops protocols and protocol extensions to improve operational efficiency and security of SIDR such as Autonomous System Provider Authorization (ASPA) and reliable cache synchronization mechanims. The WG is also responsible for the maintenance of RPKI to Router protocol.

In the space of SIDROPS, the term operators will encompass a range of operational experience: CA Operators, Regional/National and Local Internet Registries, Relying Party software developers as well as the research/measurement community all have relevant operational experience or insight that SIDROPS will consider in its work.

The goals of SIDROPS WG are to:

* Solicit input from a range of operators to identify operational issues with a SIDR-aware Internet, and determine solutions to those issues.

* Solicit input from all operators to identify issues with interaction with the non-SIDR-aware Internet, and to determine solutions to those issues.

* Standardize manageability (e.g., YANG data models) and OAM solutions related to SIDR operations.

* Develop operational solutions for identified issues in SIDROPS and document them in Standards Track, Informational, or BCP documents, depending on the type of solution (e.g., new extensions vs. operational/deployment recommendations).

* Document common SIDROPS terminology as Informational RFC.

Given the importance of routing security to the overall stability of the Internet, the WG will not submit protocol specifications for publication to the	IESG before demonstrating at least two interoperable implementations. See RFC 5657 (part of BCP 9) for guidance on what implementation reports should contain and BCP 205 for guidance on how to raise awareness of running code.

BGPsec (RFC 8205) maintenance and extensions belong to IDR WG. SIDROPS may provide input to IDR, as needed, and will cooperate with that WG in reviewing solutions to BGPsec operational and deployment problems. Documenting the operational aspects of securing the Internet routing system other than SIDR belongs to GROW WG.

## Milestones

| Date | Milestone |
| --- | --- | 
| Mar 2026 | Submit draft-ietf-sidrops-8210bis to the IESG for publication|
| Mar 2026 | Submit draft-ietf-sidrops-aspa-profile to the IESG for publication|
| Mar 2026 | Submit draft-ietf-sidrops-aspa-verification to the IESG for publication|
| Jul 2026 | Submit draft-ietf-sidrops-aspa-notation to the IESG for publication|
| Jul 2026 | Submit draft-ietf-sidrops-aspa-slurm to the IESG for publication|
