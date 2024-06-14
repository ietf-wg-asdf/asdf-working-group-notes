## Background

In 2019 One Data Model (OneDM) was started to bring several IoT SDOs and IoT device and platform vendors together under a broad, multi-party liaison agreement, with a goal of arriving at a common set of data and interaction models that describe IoT devices. After some exploratory work this resulted in a successful proposal to create the ASDF WG.

As a common language for writing down these models, the Semantic Definition Format went through the IETF process, producing (draft-ietf-asdf-sdf). This SDF Base specification has now reached WG Consensus, to be published. SDF represents these models in JSON, enabling re-use of specification formats such as CDDL (RFC 8610) and the formats proposed at json-schema.org and their tooling, for describing both the SDF format itself and the structure of the data to be modelled in SDF.

SDF does not directly address data serialization. Instead, SDF focuses solely on modeling the structure and semantics of the data being exchanged. Consequently, the task of data serialization (including RPC semantics) is delegated to other standards, which are typically established by existing IoT SDOs.

## The ASDF Working Group

The ASDF WG has developed SDF into a standards-track specification for thing interaction and data modeling. In the process of developing this specification, further functional requirements have emerged that can be addressed as extensions to the base SDF specification.

The ASDF WG will liaise with OneDM and other relevant organizations. ASDF will extend SDF to cover the following standard track extensions:

* modeling of links and relationships between elements of models,

* modeling of non-affordance attribute (e.g., location) information/interaction for digital twins where the corresponding physical objects can be described with SDF,

* additional SDF modeling mechanisms to enable property mapping between additional IoT SDOs' objects (including instances, and types), and

* information/interaction modeling and protocol mappings to enable gateway interactions between IP and non-IP transports, with draft-brinckman-nipc-00 as a starting point.

To increase ease of use, ASDF WG will also complete work on the proposal for a Compact Notation for SDF.

As work evolves, ASDF will observe and may want to interact with IRTF Research Groups such as the Usable Formal Methods Research Group (UFMRG). ASDF will work with Thing-to-Thing Research Group (T2TRG) and its WISHI (Work on IoT Semantic/Hypermedia Interoperability, https://wishi.space) program to engage researchers  and other SDOs in this space, such as W3C Web of Things, which is working on Thing Models and related specifications.
