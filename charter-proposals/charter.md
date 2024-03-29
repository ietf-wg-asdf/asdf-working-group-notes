Background
----------

Data and interaction models of IoT devices today exhibit unneeded diversity between different industry ecosystem standards development organizations (SDOs), hindering interoperability across these ecosystems with little discernible benefit from the diversity. Early 2019, One Data Model (OneDM) was started to bring several IoT SDOs and IoT device and platform vendors together under a broad, multi-party liaison agreement, with a goal of arriving at a common set of data and interaction models that describe IoT devices. Ideally, for every class of IoT device, there is just a single model selected/created by the participating organizations, which everyone can adopt.

As a common language for writing down these models, the Semantic Definition Format (SDF, draft-onedm-t2trg-sdf) was created, which can represent IoT Things, their composition from reusable Objects, their Interaction Affordances (Properties, Actions, Events), and the data models relevant to describe these Affordances. SDF represents these models in JSON, enabling re-use of specification formats such as CDDL (RFC8610) and the formats proposed at json-schema.org and their tooling, for describing both the SDF format itself and the structure of the data to be modelled in SDF.

By July 2020, some 200 models in SDF format have been contributed by participating ecosystems; new models are being submitted continually. Version 1.0 of the SDF specification was published on the OneDM github repository and as an Internet-Draft. OneDM is now focusing on consolidating the body of submitted models and developing processes for arriving at harmonized models that span different industry ecosystems in a common way; as expressed at the IETF 108 ASDF BoF, they look to the IETF for developing SDF 1.0 further into a high-quality specification.

The IETF also defines the YANG data modelling language (RFC 7950). YANG has a strong focus on modelling the management interface for network devices, using a fairly small set of network management protocols, whereas SDF is designed to span (and transitively unify) many existing interaction models already present. While data associated with a YANG schema can be serialized to a variety of wire formats (e.g., XML, JSON, CBOR, and others), the serialization is driven directly by the structure of the data models defined in YANG; there is no separate "protocol binding" step as in the use of SDF.

Conversely, SDF does not deal directly with serialization at all, modelling only the structure and semantics of the data being interchanged, hence leaving data serialization (and RPC semantics) to other standards, most likely defined by existing IoT SDOs.

The ASDF Working Group
----------------------

The objective of the ASDF working group is to develop SDF into a standards-track specification for thing interaction and data modelling. In the process of developing this specification, further functional requirements that emerge in the usage of SDF for model harmonization will be addressed.

The ASDF WG will work with experts from OneDM and its contributing organizations. In the IETF, it will work closely with the CBOR WG, home of the CDDL specification. It will also engage the still active mailing list of the concluded JSON WG. Recent proposals to form an IRTF formal description techniques (FDT) Research Group might lead to another collaboration partner. ASDF will work with Thing-to-Thing Research Group (T2TRG) and its WISHI (Work on IoT Semantic/Hypermedia Interoperability, http://wishi.space) program to engage researchers and other SDOs in this space, such as W3C Web of Things, which is working on Thing Models and related specifications.<
