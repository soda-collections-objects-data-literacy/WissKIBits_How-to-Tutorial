# WissKI Bits: Ontology-Based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL: A CASE STUDY**

## Description

The tutorial "WissKI Bits: Ontology-Based Modeling of Research Data" was developed to systematically impart—in a practical manner—foundational and applied skills regarding the **semantic modeling of research data** and its implementation using the Scientific Communication Infrastructure (WissKI). The focus lies on how domain-specific information and research questions can be translated into a coherent, ontology-based data model and utilized for the structured recording of research data.

The didactic approach is based on **research-oriented, action-oriented, and problem-oriented learning**. Brief inputs of knowledge are combined with guided phases of exploration, modeling, and reflection. The learning architecture incorporates **Klaus Döring’s "Inhale-Exhale" principle**: phases of knowledge transfer and subject-matter orientation ("inhaling") alternate with phases of independent exploration, application, testing, and reflection ("exhaling").[1]

The modeling of **computer games as collection and research objects** serves as the continuous case study. Using this example, learners proceed step-by-step through the modeling process, moving from the initial research question to technical implementation. In doing so, they do not merely follow along with modeling decisions but make, justify, and validate their own decisions against existing ontologies.

The tutorial consists of **three sequential modules**.

**Module 1** covers the fundamentals of ontologies and semantic modeling, introduces the CIDOC CRM, and structures domain-specific concepts, events, and relationships within a conceptual model sketch.

**Module 2** transitions these concepts into formal ontology modeling. Using Protégé, participants explore CIDOC CRM classes (entities) and properties, select appropriate elements, and model domain-specific structures.

In **Module 3**, the semantic model is visualized and prepared for implementation in WissKI. The model is mapped as a diagram in Draw.io, transformed into a Pathbuilder XML structure using the gnm-service, and subsequently imported into and examined within the WissKI Pathbuilder.

Practical work with **CIDOC CRM, Protégé, Draw.io, gnm-service, and WissKI** integrates conceptual, semantic, and technical perspectives. Recurring exercises, quizzes, and prompts for reflection help learners review modeling decisions and understand the connections between the various representations of the data model.

The tutorial is designed as a **modular, self-paced Open Educational Resource (OER)**. While the individual units can be completed at the learner's own pace, the content is cumulative; results from earlier units are utilized in subsequent steps. This creates a continuous learning path:

> **Research question and domain → conceptual modeling → CIDOC CRM → formal ontology modeling → visualization → transformation → WissKI Pathbuilder**

The tutorial is available in **German and English** and is published under a **CC-BY-4.0 license**. Its modular structure allows it to be used, adapted, and further developed for self-study as well as in teaching, training, and consulting contexts.

---

## Topic Areas and Topics

The tutorial covers key steps in the **ontology-based modeling of research data** and their practical implementation in WissKI.

The content is organized into three sequential topic areas:

**Module 1: Fundamentals and Conceptual Modeling**

- Research data and research questions as the starting point for modeling
- Fundamentals of ontologies and semantic modeling
- Concepts, events, and relationships
- Introduction to CIDOC CRM
- Classes (entities) and properties
- Developing a conceptual model sketch
- FAIR principles and WissKI

**Module 2: Formal Modeling with CIDOC CRM and Protégé**

- Ontology modeling methods and workflows
- Introduction to Protégé
- Exploring CIDOC CRM
- Selecting suitable classes and properties
- Developing domain-specific subclasses
- Formalizing and validating the data model
- Preparing the model for implementation in WissKI

**Module 3: From Semantic Model to WissKI Pathbuilder**

- Visualizing the semantic data model with Draw.io
- Modeling nodes, edges, and semantic paths
- Preparing the diagram for transformation
- Transforming the Draw.io diagram using the gnm-service
- Generating a Pathbuilder XML file
- Importing into WissKI Pathbuilder
- Examining and analyzing groups and semantic paths

> **Conceptual modeling → formal ontology modeling → visualization → transformation → WissKI Pathbuilder**

---

## Target Audience

This module is aimed at members of the SODa community, such as professors, collection coordinators, managers and curators, and researchers. [3]

## Learning Approach and Format

The tutorial follows a **research-oriented, action-oriented, and problem-oriented learning approach**. The focus is not on the isolated transmission of knowledge about ontologies and WissKI, but rather on the step-by-step execution of a concrete modeling task. Using a consistent case study, learners develop an ontology-based data model and gradually transform it into a structure compatible with WissKI.

The pedagogical approach combines **demonstrative learning, learning by doing, and guided modeling**. New concepts and procedural steps are introduced and explored using concrete examples before being applied by the learners themselves. This integrates theoretical understanding, methodological reflection, and practical competence.

The structure of the individual units follows Klaus Döring’s **“Inhaling and Exhaling” principle** [1]. Brief, structured inputs of knowledge (“inhaling”) alternate with phases of exploration, modeling, application, testing, and reflection (“exhaling”). Exercises, quizzes, and prompts for reflection help learners verify their understanding and justify their modeling decisions.

### Competence-Oriented Learning Paths

The tutorial’s design combines the **Learning Objective Matrix for Research Data Management (RDM)** [2] with the **TaDiRAH taxonomy (Taxonomy of Digital Research Activities in the Humanities)** [4]. The learning objective matrix serves to formulate and systematize specific competencies, while TaDiRAH links learning activities to research activities within the Digital Humanities.

Mapping is not based solely on individual verbs within the learning objective statements; the **semantic interpretation of the entire learning objective within its specific disciplinary and didactic context** is the decisive factor. This approach allows learning objectives to be linked to the research activities for which the learning process provides preparation.

Across the three modules, a **competence-oriented learning path** emerges, leading step-by-step from epistemic to operational research activities: from understanding and analyzing disciplinary contexts and conceptual/formal modeling to the practical implementation of the data model in WissKI.

While the content of the three modules builds upon one another, they are also designed to be reusable as **modular learning units**. Results from preceding units are revisited along the full learning path and further developed in subsequent steps.

The learning process consistently follows this principle:

> **Orient → Explore → Model → Apply → Test → Reflect → Extend**

The tutorial is designed as a **modular, self-paced Open Educational Resource (OER)**. Integrating learning objectives, research activities, and practical modeling tasks supports both the development of disciplinary orientation and the transfer of knowledge into concrete research and data practices.

---

## Subject Areas and Topics

---

## Prerequisites for the Tutorial

**No in-depth prior knowledge of ontologies or WissKI** is required to complete this tutorial. However, a basic understanding of working with research data and digital work environments is helpful.

The following are required for the practical exercises:

- a personal laptop or computer with internet access,
- a modern web browser,
- access to a **WissKI instance**,
- **Protégé** for editing and exploring ontologies,
- **diagrams.net (Draw.io)** for visualizing semantic models.

Fundamental concepts—such as **ontologies, classes (entities), properties, CIDOC CRM, and WissKI**—are introduced throughout the tutorial and explored practically using a consistent, ongoing case study.

The three modules build upon one another. Therefore, to complete the full learning path, it is recommended that you work through them **in the intended order**.

---

## Units and Time Requirements

**Total duration Module 1: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| 0 | Welcome, objectives, and schedule | 5 min. |
| 1 | Basic concepts of conceptual knowledge modeling | 20 min. |
| 2 | Fundamentals of ontologies | 10 min. |
| 3 | Introduction to CIDOC CRM | 15 min. |
| 4 | FAIR compliance with WissKI | 15 min. |
| Ex 1 | Application example: object collections – "Zelda" model sketch | 30 min. |
|  | **Total** | **90 min.** |

**Total duration Module 2: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| 0 | Welcome, objectives, and schedule | 10 min. |
| 1 | Semantic modeling methods and workflows | 5 min. |
| 2 | Introduction to Protégé | 20 min. |
| Ex 1 | Semantic modeling with CIDOC CRM | 55 min. |
|  | **Total** | **90 min.** |

**Total duration Module 3: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| 0 | Welcome, objectives, and schedule | 10 min. |
| Ex 1 | Visualizing semantic data models | 35 min. |
| Ex 2 | Transforming semantic models into WissKI paths | 40 min. |
|  | **Total** | **90 min.** |

---

## Learning Objectives in Module 1: **From Collection to Modeling Decisions to Diagram – Understanding and Explaining**

Upon completion of Module 1, participants will be able to…

**1. Basic concepts of conceptual knowledge modeling**

- Name the term "conceptual knowledge modeling." (LO-ID SODa_03_007_0847)
- Explain the term "conceptual knowledge modeling." (LO-ID SODa_03_007_0848)
- Name the term "domain." (LO-ID SODa_03_007_0824)
- Name the term "concept." (LO-ID SODa_03_007_0821)
- Name the term "event." (LO-ID SODa_03_007_0822)
- Name the term "relationship." (LO-ID SODa_03_007_0823)
- Name the term "semantic modeling." (LO-ID SODa_03_007_0825)
- Explain the term "semantic modeling." (LO-ID SODa_03_007_0844)
- Name the term "semantic data model." (LO-ID SODa_03_007_0845)
- Explain the term "semantic data model." (LO-ID SODa_03_007_0846)

**2. Fundamentals of ontologies**

- Name the concept of ontology. (LZ-ID SODa_03_007_0826)
- Explain the concept of ontology. (LZ-ID 03_007_0775)
- Name aspects of ontologies. (LZ-ID 03_007_0776)
- Name the concept of classes (Classes/Concepts). (LZ-ID SODa_03_007_0829)
- Explain the concept of classes (Classes/Concepts). (LZ-ID SODa_03_007_0830)
- Name the concept of instances (Instances). (LZ-ID SODa_03_007_0833)
- Explain the concept of instances (Instances). (LZ-ID SODa_03_007_0834)
- Name the concept of properties (Properties). (LZ-ID SODa_03_007_0831)
- Explain the concept of properties (Properties). (LZ-ID SODa_03_007_0832)
- Name the concept of model assumptions (Constraints). (LZ-ID SODa_03_007_0835)
- Explain the concept of model assumptions (Constraints). (LZ-ID SODa_03_007_0836)

**3. Introduction to CIDOC CRM**

- Name an ontology for describing resources. (LZ-ID 03_007_0778)
- Explain an ontology for describing resources. (LZ-ID 03_007_0779)
- Name core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa_03_007_0806)
- Explain the core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa_03_007_0807)
- Name the term "scope notes." (LZ-ID SODa_03_007_0837)
- Explain the term "scope notes." (LZ-ID SODa_03_007_0838)
- Name the Resource Description Framework (RDF) as a standard for describing resources. (LZ-ID SODa_03_007_0843)
- Name the term "domain ontology." (LZ-ID SODa_03_007_0827)
- Explain the term "domain ontology." (LZ-ID SODa_03_007_0828)
- Name the benefits of the CIDOC CRM reference model. (LZ-ID SODa_03_007_0805)

**4. FAIR Compliance with WissKI**

- Explain (inter)national IT infrastructures relevant to collection-based research data management (RDM). (LZ-ID SODa_01_010_0203)
- Identify suitable technologies to support the application of the FAIR principles. (LZ-ID 01_007_0121)
- Name the FAIR principles. (LZ-ID 01_007_0117)
- Name the 5-star model for open data. (LZ-ID SODa_01_008_0172)
- Name the formal description language W3C Web Ontology Language (OWL). (LZ-ID SODa_03_007_0842)
- Identify Erlangen CRM/OWL as the OWL implementation of the CIDOC CRM reference model. (LZ-ID SODa_03_007_0841)
- Name the specific functions and application areas of the scientific communication infrastructure WissKI. (LZ-ID SODa_01_010_0191a)
- Explain the specific functions and application areas of the scientific communication infrastructure WissKI. (LZ-ID SODa_01_010_0192a)
- Describe the performance and efficiency of IT infrastructures for collection-based research data management (RDM) using the scientific communication infrastructure WissKI. (LZ-ID SODa_01_010_0202)
- Identify WissKI Pathbuilder as a tool for defining an ontology structure. (LZ-ID SODa_03_007_0803)
- Explain WissKI Pathbuilder as a tool for defining an ontology structure. (LZ-ID SODa\_03\_007\_0849)
- Explain the event-centric modeling principle using CIDOC CRM, illustrated by an example. (LZ-ID SODa\_03\_007\_0850)
- Identify the Resource Description Framework (RDF) as a standard for describing resources. (LZ-ID SODa\_03\_007\_0843)
- Identify the benefits of the scientific communication infrastructure WissKI. (LZ-ID SODa\_01\_010\_0204)

**Ex. 1: Application example – object collections**

- Apply core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa\_03\_007\_0811)
- Identify the data type properties of the CIDOC CRM reference model. (LZ-ID SODa\_03\_007\_0808)

---

## Learning Objectives for Module 2: **Modeling with CIDOC CRM – Understanding and Application**

Upon completion of Module 2, participants will be able to…

**1. Semantic Modeling Methods and Workflows**

- Name methods for ontology development. (LZ-ID 03_007_0784)
- Explain methods for ontology development. (LZ-ID SODa_03_007_0839)
- Name a workflow for semantic modeling as data documentation. (LZ-ID SODa_03_001_0626)
- Explain a workflow for semantic modeling as data documentation. (LZ-ID SODa_03_001_0853)
- Name methods for modeling a domain ontology using the CIDOC CRM reference model. (SODa_03_007_0784a)
- Explain methods for modeling a domain ontology using the CIDOC CRM reference model. (SODa_03_007_0785a)

**2. Introduction to Protégé**

- Name software for creating ontologies. (LZ-ID SODa_03_007_0809)
- Explain software for creating ontologies. (LZ-ID SODa_03_007_0810)
- Identify CRM/OWL as the OWL implementation of the CIDOC CRM reference model. (LZ-ID SODa_03_007_0841)
- Use software for creating ontologies. (LZ-ID SODa_03_007_0840)
- Name methods for modeling a domain ontology using the CIDOC CRM reference model. (LO ID SODa\_03\_007\_0784a)
- Explain methods for modeling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

**Ex. 1. Semantic modeling with CIDOC CRM**

- Apply an ontology to describe resources. (LO ID 03\_007\_0780)
- Apply methods for ontology development. (LO ID SODa\_03\_007\_0854)
- Apply a workflow for semantic modeling as data documentation. (LO ID SODa\_03\_001\_0627)
- Apply methods for modeling a domain ontology using the CIDOC CRM reference model under guidance. (LO ID SODa\_03\_001\_0786a)
- Use software for creating ontologies. (LO ID SODa_03_007_0840)
- Use Erlangen CRM/OWL as an OWL implementation of the CIDOC CRM reference model. (LO ID SODa_03_007_0855)
- Use the scope notes of the CIDOC CRM reference model to describe resources. (LO ID SODa\_03\_007\_0780a)

---

## Learning Objectives in Module 3: **From Diagram to Paths – Explaining and Applying**

Upon completion of Module 3, participants will be able to…

**Ü1. Visualize semantic data models**

- Name software used to visualize a domain ontology. (LO ID SODa_03_007_0812)
- Explain software used to visualize a domain ontology. (LO ID SODa_03_007_0813)
- Explain the concept of visualization. (LO ID SODa_03_007_0851)
- Explain the benefits of visualizations. (LO ID SODa_03_007_0852)
- Name the benefits of software used to visualize a domain ontology. (LO ID SODa_03_007_0814)
- Use software to visualize a domain ontology under guidance. (LO ID SODa_03_007_0815)
- Name core entities (object/person/place/time/event) of an object collection. (LO ID SODa_03_007_0806)
- Apply core entities (object/person/place/time/event) of an object collection. (LO ID SODa_03_007_0811)
- Name rules for modeling a domain ontology using visualization software. (LO ID SODa_03_007_0820)
- Apply rules for modeling a domain ontology using visualization software. (LO ID SODa_03_007_0816)
- Apply attribute values ​​to predefined classes of the domain ontology within visualization software. (LZ-ID SODa_03_007_0817)

**Ü2. Transformation of semantic models into WissKI paths**

- Explain the WissKI Pathbuilder as a tool for defining an ontology structure. (LZ-ID SODa_03_007_0804)
- Apply data conversion from visualization software into a reusable file format under guidance. (LZ-ID SODa_02_005_0298a)
- Use the WissKI Pathbuilder as a tool to import a domain-specific ontology structure (Pathbuilder XML file) under guidance. (LZ-ID SODa_03_007_0818)
- Analyze the imported domain-specific ontology structure in the WissKI Pathbuilder under guidance. (LZ-ID SODa_03_007_0819)
- Name a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion. (LZ-ID SODa_02_005_0317)
- Use a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion under guidance. (LZ-ID SODa_02_005_0318)

---

## Bibliography

[1] Döring, K. W. (2009): Handbuch Lehren und Trainieren in der Weiterbildung. Beltz.

[2] Petersen, B., Altemeier, F., Boße, S., Dalby, M., Düvel, N., Engelhardt, C., Fichtner, M., Hastik, C., Haugwitz, J.-M., Jacob, J., Koch, K., Kuntz, A., Manske, A., Mühlichen, A., Murcia Serra, J., Ortmeyer, J., Richter, M., Schranzhofer, H., Slowig, B., … Zollitsch, L. (2025). Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) (Version 3). Zenodo. https://doi.org/10.5281/zenodo.15025246

[3] Reichert, R., Hastik, C., Gnyp, A., Markert, M., & Tharandt, L. (2025). SODa Personas. Zenodo. https://doi.org/10.5281/zenodo.15574575

[4] Hastik, C., & Schwenk, G. A. (2026). Die Verschränkung von Lernzielmatrix und TaDiRAH zur Entwicklung kompetenzorientierter Lernpfade [Graphic]. Zenodo. Scoping Workshop der VolkswagenStiftung "Zukunftskompetenzen Forschungsdatenmanagement gestalten: Anforderungen an Kompetenzen, Terminologien und Communitys für datengetriebene Wissenschaft", Schloss Herrenhausen, Hannover. https://doi.org/10.5281/zenodo.20829481


