Background
----------

In 2019 One Data Model (OneDM) was started to bring several IoT SDOs and IoT device and platform vendors together under a broad, multi-party liaison agreement, with a goal of arriving at a common set of data and interaction models that describe IoT devices.  After some exploratory work this resulted in a successful proposal to create the ASDF WG.

As a common language for writing down these models, the Semantic Definition Format went through the IETF process, producing (draft-ietf-asdf-sdf).  This SDF Base specification has now reached WG Consensus, to be published.  SDF represents these models in JSON, enabling re-use of specification formats such as CDDL (RFC8610) and the formats proposed at json-schema.org and their tooling, for describing both the SDF format itself and the structure of the data to be modelled in SDF.

SDF does not deal directly with serialization at all, modelling only the structure and semantics of the data being interchanged, hence leaving data serialization (and RPC semantics) to other standards, most likely defined by existing IoT SDOs.

The ASDF Working Group
----------------------

The ASDF has developed SDF into a standards-track specification for thing interaction and data modelling.  In the process of developing this specification, further functional requirements have emerged that can be addressed as extensions to the base SDF specification.

The ASDF WG will work with experts from OneDM and its contributing organizations to extend SDF to cover aspects such as digital twin, mapping to other IoT SDOs, and gateway interactions translations between IP and other transports.

As work evolves, it will interact with the IRTF formal description techniques (FDT) Research Group.  ASDF will work with Thing-to-Thing Research Group (T2TRG) and its WISHI (Work on IoT Semantic/Hypermedia Interoperability, http://wishi.space) program to engage researchers and other SDOs in this space, such as W3C Web of Things, which is working on Thing Models and related specifications.

