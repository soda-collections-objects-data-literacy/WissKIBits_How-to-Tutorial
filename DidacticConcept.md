# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL: A CASE STUDY**

**Editorial update: 25 November 2026.** Checked against the German and English units in the supplied repository archive. This concept update does not modify the unit files themselves.

## Description

The tutorial "WissKI Bits: Ontology-Based Modelling of Research Data" was developed to systematically impart—in a practical manner—foundational and applied skills regarding the **semantic modelling of research data** and its implementation using the Scientific Communication Infrastructure (WissKI). The focus lies on how domain-specific information and research questions can be translated into a coherent, ontology-based data model and utilised for the structured recording of research data.

The didactic approach is based on **research-oriented, action-oriented, and problem-oriented learning**. Brief inputs of knowledge are combined with guided phases of exploration, modelling, and reflection. The learning architecture incorporates **Klaus Döring’s "Inhale-Exhale" principle**: phases of knowledge transfer and subject-matter orientation ("inhaling") alternate with phases of independent exploration, application, testing, and reflection ("exhaling").[1]

The modelling of **computer games as collection and research objects** serves as the continuous case study. Using this example, learners proceed step-by-step through the modelling process, moving from the initial research question to technical implementation. In doing so, they do not merely follow along with modelling decisions but make, justify, and validate their own decisions against existing ontologies.

The tutorial consists of **three sequential modules**.

**Module 1** covers the fundamentals of ontologies and semantic modelling, introduces the CIDOC CRM, and structures domain-specific concepts, events, and relationships within a conceptual model sketch.

**Module 2** transitions these concepts into formal ontology modelling. Using Protégé, participants explore CIDOC CRM classes (entities) and properties, select appropriate elements, and model domain-specific structures.

In **Module 3**, the semantic model is visualised and made usable in WissKI. A prepared Draw.io diagram is completed, checked and transformed into a Pathbuilder XML configuration using the gnm-service. After the required domain ontology has been made available separately and the SALZ adapter has been updated, the configuration is imported into the WissKI Pathbuilder and checked from a domain perspective. The generated bundles and fields are examined and used to create an initial record about the example object.

Practical work with **CIDOC CRM, Protégé, Draw.io, gnm-service, and WissKI** integrates conceptual, semantic, and technical perspectives. Recurring exercises, quizzes, and prompts for reflection help learners review modelling decisions and understand the connections between the various representations of the data model.

The tutorial is designed as a **modular, self-paced Open Educational Resource (OER)**. While the individual units can be completed at the learner's own pace, the content is cumulative; results from earlier units are utilised in subsequent steps. This creates a continuous learning path:

> **Research question and domain → conceptual modelling → CIDOC CRM mappings → formal OWL model section → Draw.io diagram → transformation → WissKI Pathbuilder → bundles and fields → initial data entry**

The tutorial is available in **German and English** and is published under a **CC-BY-4.0 licence**. Its modular structure allows it to be used, adapted, and further developed for self-study as well as in teaching, training, and consulting contexts.

---

## Topic Areas and Topics

The tutorial covers key steps in the ontology-based modelling of research data and their practical implementation in WissKI.

The content is organised into three sequential topic areas:

**Module 1: Fundamentals and Conceptual Modelling**

- Research data and research questions as the starting point for modelling
- Fundamentals of ontologies and semantic modelling
- Concepts, events, and relationships
- Introduction to CIDOC CRM
- Classes (entities) and properties
- Developing a conceptual model sketch
- FAIR principles and WissKI

**Module 2: Formal Modelling with CIDOC CRM and Protégé**

- Ontology modelling methods and workflows
- Introduction to Protégé
- Exploring CIDOC CRM
- Selecting suitable classes and properties
- Developing domain-specific subclasses
- Formalising and checking a small, documented section of the model rather than a complete domain ontology
- Following a lightweight extension strategy: create domain-specific subclasses and reuse existing CIDOC CRM properties; do not define new properties
- Preparing the model for implementation in WissKI

**Module 3: From Semantic Model to WissKI Pathbuilder**

- Visualising the semantic data model with Draw.io
- Modelling nodes, edges, and semantic paths
- Preparing the diagram for transformation
- Transforming the Draw.io diagram using the gnm-service
- Generating a Pathbuilder XML file
- Importing into WissKI Pathbuilder
- Examining and analysing groups and semantic paths
- Loading the domain ontology separately and updating the SALZ adapter
- Comparing the imported path configuration with the source diagram and documenting discrepancies
- Checking bundles and fields and entering an initial record
- Tracing the game title from its semantic path through the input field to the actual value

> **Conceptual modelling → formal ontology modelling → visualisation → transformation → WissKI Pathbuilder → data entry**

A conceptual model sketch, an OWL ontology, a Draw.io diagram, a Pathbuilder configuration and an individual record are different representations serving different purposes. In particular, importing a Pathbuilder XML file replaces neither loading the ontology nor entering research data. A technically successful transformation does not guarantee semantic correctness.

---

## Target Audience

This tutorial is aimed at the groups described in the SODa personas, particularly professors, collection coordinators, collection managers and curators, and researchers. [3]

The tutorial is also relevant to people who wish to structure research and collection data, justify modelling decisions from a domain perspective and develop ontology-based data models for practical use in WissKI.

---

## Learning Approach and Format

The tutorial follows a **research-oriented, action-oriented, and problem-oriented learning approach**. The focus is not on the isolated transmission of knowledge about ontologies and WissKI, but rather on the step-by-step execution of a concrete modelling task. Using a consistent case study, learners develop an ontology-based data model and gradually transform it into a structure compatible with WissKI.

The pedagogical approach combines **demonstrative learning, learning by doing, and guided modelling**. New concepts and procedural steps are introduced and explored using concrete examples before being applied by the learners themselves. This integrates theoretical understanding, methodological reflection, and practical competence.

The structure of the individual units follows Klaus Döring’s **“Inhaling and Exhaling” principle** [1]. Brief, structured inputs of knowledge (“inhaling”) alternate with phases of exploration, modelling, application, testing, and reflection (“exhaling”). Exercises, quizzes, and prompts for reflection help learners verify their understanding and justify their modelling decisions.

---

### Learning Format: Self-Study and Facilitated Learning

The tutorial is designed as a **modular, guided self-study Open Educational Resource (OER) with dual use in self-paced and facilitated learning settings.**

In **guided self-study**, learners can work through the tutorial at their own pace. Short knowledge inputs, step-by-step tasks, examples, reflection prompts, quizzes, and opportunities for self-assessment provide guidance throughout the modelling process.

In **facilitated learning settings**, such as workshops or training sessions, the same core activities can be carried out collaboratively and extended through discussion, peer exchange, and facilitator feedback.

The **learning objectives and core modelling tasks remain consistent across both modes.** What changes is the form of interaction, guidance, reflection and feedback. In self-study, plenary discussions are replaced by written self-reflection and reasoned comparison with examples or scope notes. This intention is not yet equally explicit throughout the units; in particular, the English units M1U00 and M1U1 still contain wording tied to facilitated sessions. The same OER can thus support individual and collaborative learning without requiring separate versions of the core resource.

### Competence-Oriented Learning Paths

The tutorial’s design combines the **Learning Objective Matrix for Research Data Management (RDM)** [2] with the **TaDiRAH taxonomy (Taxonomy of Digital Research Activities in the Humanities)** [4]. The learning objective matrix serves to formulate and systematise specific competencies, while TaDiRAH links learning activities to research activities within the Digital Humanities.

Mapping is not based solely on individual verbs within the learning objective statements; the **semantic interpretation of the entire learning objective within its specific disciplinary and didactic context** is the decisive factor. This approach allows learning objectives to be linked to the research activities for which the learning process provides preparation.

Across the three modules, a **competence-oriented learning path** emerges, leading step-by-step from epistemic to operational research activities: from understanding and analysing disciplinary contexts and conceptual/formal modelling to the practical implementation of the data model in WissKI.

While the content of the three modules builds upon one another, they are also designed to be reusable as **modular learning units**. Results from preceding units are revisited along the full learning path and further developed in subsequent steps.

The learning process consistently follows this principle:

> **Orient → Explore → Model → Apply → Test → Reflect → Extend**

This recurring learning process connects the **competence-oriented learning path** [4] with the tutorial’s **dual-use design**. Learning objectives, research activities, and practical modelling tasks provide a common didactic structure across both guided self-study and facilitated learning settings, supporting the transfer of conceptual understanding into concrete research and data practices.

---

## Didactic Profile

The following profile summarises the didactic design and intended modes of use of the tutorial.

| Dimension | Design |
|---|---|
| Resource type | Guided how-to tutorial / OER |
| Learning mode | Guided self-study or facilitated learning |
| Pacing | Self-paced or facilitator-paced |
| Interaction | Individual or collaborative |
| Learning approach | Research-, action- and problem-oriented |
| Learning methods | Demonstration, learning by doing, guided modelling, reflection |
| Learning process | Orient → Explore → Model → Apply → Test → Reflect → Extend |
| Guidance and feedback | Instructions, templates, examples, quizzes and self-assessment; optional peer and facilitator feedback |
| Progression | Cumulative, competence-oriented learning path |
| Modularity | Individual units or complete three-module learning path |
| Learning contexts | Self-study, workshop, training, teaching and consultation |
| Case-based learning | Continuous computer game example: The Legend of Zelda: A Link to the Past |

### Learning Outputs and Formative Assessment

| Module | Observable learning output | Formative check |
|---|---|---|
| 1 | Conceptual model sketch and two provisional CIDOC CRM class mappings, with clarified meanings, scope-note justifications and open questions | Check the statements in the sketch; justify, compare and, where necessary, revise mappings |
| 2 | Small OWL model section with domain-specific subclasses and documented reuse of existing properties | Check the class hierarchy and meanings; document decisions; reopen the saved ontology |
| 3 | Completed Draw.io diagram, XML export, Pathbuilder XML, checked path configuration, review notes and an initial WissKI record | Quizzes, diagram-to-path comparison and tracing the title path through to the actual input value |

Model solutions are resources for comparison and reflection, not the only acceptable models. What matters is that domain meanings can be understood and justified and are compatible with the ontology definitions used. The activities support formative self-assessment; they do not constitute a standardised final assessment.

---

## Prerequisites for the Tutorial

**No in-depth prior knowledge of ontologies or WissKI** is required to complete this tutorial. However, a basic understanding of working with research data and digital work environments is helpful.

The following are required for the practical exercises:

- a personal laptop or computer with internet access,
- a modern web browser,
- access to a **WissKI test instance suitable for the exercises**, with the required configuration permissions, for example through the SODa Semantic Co-Working Space; a personal WissKI installation is not required,
- **Protégé Desktop or WebProtégé** for editing and exploring ontologies; the video demonstration uses Protégé Desktop, and steps in WebProtégé may differ,
- **diagrams.net (Draw.io)** for visualising semantic models,
- the supplied puzzle and diagram templates and the ontology files used,
- access to the **gnm-service** for transforming Draw.io XML into Pathbuilder XML.

The domain reference is **CIDOC CRM 7.1.3**; the CIDOC CRM Periodic Table based on version 7.1 provides orientation. Erlangen CRM / OWL is used in Protégé. The guided import workflow in Module 3 uses the supplied Games domain ontology. The different Erlangen CRM releases referenced in the archive need to be aligned before a technical run-through.

**Safety:** Any reset described in the tutorial is permitted only in a disposable test instance explicitly designated for this purpose. Existing research data and configurations in production or shared instances must not be deleted.

Fundamental concepts—such as **ontologies, classes (entities), properties, CIDOC CRM, and WissKI**—are introduced throughout the tutorial and explored practically using a consistent, ongoing case study.

The three modules build upon one another. Therefore, to complete the full learning path, it is recommended that you work through them **in the intended order**.

Individual units may also be reused separately for specific teaching or training purposes, provided that equivalent prior knowledge and the required intermediate outputs or supplied examples are available.

The additional **Fast Track** offers a condensed run-through of approximately 90 minutes. It does not replace the full foundational and reflective coverage of the three modules and is not added to their total duration.

---

## Units and Time Requirements

Unit identifiers use **E** in German and **U** in English. The schedule below follows the duration stated in each individual unit rather than conflicting older overview tables. The English introduction to Module 3 is identified as M3U0 in its content, but its filename in the archive is still `M3E0_Workflow-Objectives.md`.

**Total duration of module 1: Approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| M1U00 | Welcome, objectives and structure | 5 min. |
| M1U0A | Activation: Collection object "Zelda" | 15 min. |
| M1U1 | Basic concepts of conceptual knowledge modelling | 10 min. |
| M1U2 | Fundamentals of ontologies | 10 min. |
| M1U3 | Introduction to CIDOC CRM | 15 min. |
| M1U4 | FAIR compliance with WissKI | 15 min. |
| M1UE | Exercise: CIDOC CRM formalisation – examine and justify two mappings | 20 min. |
|  | **Total** | **90 min.** |

**Total duration of Module 2: approximately 95 min., based on the individual units**

| Unit | Content | Duration |
|---|---|---:|
| M2U00 | Welcome, structure and objectives | 10 min. |
| M2U0A | Activation: Preparing to work with Protégé | 15 min. |
| M2U1 | Methods and workflows of semantic modelling | 5 min. |
| M2U2 | Introduction to Protégé | 10 min. |
| M2UE | Exercise: Semantic modelling with CIDOC CRM | 55 min. |
|  | **Total** | **95 min.** |

The existing module overviews in both languages allocate 50 minutes to the final exercise and 90 minutes overall; both exercise files state 55 minutes. This concept transparently follows the 55 minutes stated in the exercise files. If the 90-minute framework is mandatory, the exercise needs to be adjusted to 50 minutes following a test run. Task time within a unit must not be confused with the unit's overall duration.

**Total duration of module 3: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| M3U0 | Welcome, workflow and objectives| 10 min. |
| M3UE1 | Visualising a semantic domain ontology | 35 min. |
| M3UE2 | Transforming models into WissKI paths, checking paths and entering initial data | 45 min. |
|  | **Total** | **90 min.** |

---

**Total duration of the complete learning path: approximately 275 minutes (4 hours 35 minutes), excluding breaks and additional technical setup.** This is the arithmetic sum of the stated unit durations, not an empirically validated completion time. The extended workflow in Module 3 particularly needs testing with the target audience.

---

## Learning Objectives in Module 1: **From Collection to Modelling Decisions to Diagram – Understand and Explain**

Upon completion of Module 1, participants will be able to…

**U0A. Application Example for Object Collections**

- apply the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa_03_007_0811)
- apply the method of conceptual knowledge modelling to describe a research object. (LO-ID SODa_03_007_0856)
  
**U1. Basic Concepts of Conceptual Knowledge Modelling**
   
- name the term conceptual knowledge modelling. (LO-ID SODa\_03\_007\_0847)
- explain the term conceptual knowledge modelling. (LO-ID SODa\_03\_007\_0848)
- name the term domain. (LO-ID SODa\_03\_007\_0824)
- name the term concept. (LO-ID SODa\_03\_007\_0821)
- name the term event. (LO-ID SODa\_03\_007\_0822)
- name the term relationship. (LO-ID SODa\_03\_007\_0823)
- name the term semantic modelling. (LO-ID SODa\_03\_007\_0825)
- explain the term semantic modelling. (LO-ID SODa\_03\_007\_0844)
- name the term semantic data model. (LO-ID SODa\_03\_007\_0845)
- explain the term semantic data model. (LO-ID SODa\_03\_007\_0846)

**U2. Fundamentals of Ontologies**
   
- name the term ontology. (LO-ID SODa\_03\_007\_0826)
- explain the term ontology. (LO-ID 03\_007\_0775)
- name aspects of ontology. (LO-ID 03\_007\_0776)
- name the term classes (classes/concepts). (LO-ID SODa\_03\_007\_0829)
- explain the term classes (classes/concepts). (LO-ID SODa\_03\_007\_0830)
- name the term instances (instances). (LO-ID SODa\_03\_007\_0833)
- explain the term instances (instances). (LO-ID SODa\_03\_007\_0834)
- name the term properties (properties). (LO-ID SODa\_03\_007\_0831)
- explain the term properties (properties). (LO-ID SODa\_03\_007\_0832)
- name the term modelling assumptions (constraints). (LO-ID SODa\_03\_007\_0835)
- explain the term modelling assumptions (constraints). (LO-ID SODa\_03\_007\_0836)

**U3. Introduction to CIDOC CRM**

- name ontologies to describe resources. (LO-ID 03\_007\_0778)
- explain ontologies to describe resources. (LO-ID 03\_007\_0779)
- name the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0806)
- explain the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0807)
- name the term Scope Notes. (LO-ID SODa\_03\_007\_0837)
- explain the term Scope Notes. (LO-ID SODa\_03\_007\_0838)
- name the Resource Description Framework (RDF) as a standard for describing resources. (LO-ID SODa\_03\_007\_0843)
- name the term domain ontology. (LO-ID SODa\_03\_007\_0827)
- explain the term domain ontology. (LO-ID SODa\_03\_007\_0828)
- name the benefits of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0805)
 
**U4. FAIR Compliance with WissKI**

- explain (inter)national IT infrastructures relevant to collection-related research data management (RDM). (LO-ID SODa\_01\_010\_0203)
- name appropriate technologies to support the application of the FAIR principles. (LO-ID 01\_007\_0121)
- name the FAIR principles. (LO-ID 01\_007\_0117)
- name the 5-star model for open data. (LO-ID SODa\_01\_008\_0158a)
- name the W3C Web Ontology Language (OWL) as a formal description language. (LO-ID SODa\_03\_007\_0842)
- name Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0841)
- name the specific functions and application areas of the Scientific Communication Infrastructure WissKI. (LO-ID SODa\_01\_010\_0191a)
- explain the specific functions and application areas of the Scientific Communication Infrastructure WissKI. (LO-ID SODa\_01\_010\_0192a)
- name the capabilities and efficiency of IT infrastructures for collection-related research data management (RDM) using the Scientific Communication Infrastructure WissKI. (LO-ID SODa\_01\_010\_0202)
- name the WissKI Pathbuilder as a tool for defining an ontology structure. (LO-ID SODa\_03\_007\_0803)
- explain the WissKI Pathbuilder as a tool for defining an ontology structure. (LO-ID SODa\_03\_007\_0804)
- explain the event-centred modelling principle using CIDOC CRM with an example. (LO-ID SODa\_03\_007\_0850)
- name the Resource Description Framework (RDF) as a standard for describing resources. (LO-ID SODa\_03\_007\_0843)
- name the benefits of the Scientific Communication Infrastructure WissKI. (LO-ID SODa\_01\_010\_0204)

**UE. CIDOC CRM Formalisation Using the Application Example**

- apply the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0811)
- name datatype properties of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0808)

**Open alignment issue:** The datatype-properties objective is retained for traceability. It is not specifically assessed by the current final task in Module 1; the German exercise file already acknowledges this. Learners actually work on two justified, provisional class mappings. Moving the datatype objective or assigning different learning-objective IDs requires domain-level agreement and is not done unilaterally here.

---

## Learning Objectives for Module 2: **Modelling with CIDOC CRM – Understand and Apply**

Upon completion of Module 2, participants will be able to…

**U0A. Preparing to Work with Protégé**

- name software used for creating ontologies. (LO-ID SODa\_03\_007\_0809)
- apply software used for creating ontologies. (LO-ID SODa\_03\_007\_0840)
- analyse their own experience with software used for creating ontologies. (LO-ID SODa\_03\_007\_0857)

**U1. Methods and Workflows of Semantic Modelling**

- name methods for developing ontologies. (LO-ID 03\_007\_0784)
- explain methods for developing ontologies. (LO-ID SODa\_03\_007\_0839)
- name a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0626)
- explain a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0853)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0785a)

**U2. Introduction to Protégé**

- name software for creating ontologies. (LO-ID SODa\_03\_007\_0809)
- explain software for creating ontologies. (LO-ID SODa\_03\_007\_0810)
- name Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0841)
- apply software used for creating ontologies. (LO-ID SODa\_03\_007\_0840)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0785a)

**UE. Semantic Modelling with CIDOC CRM**

- apply ontologies to describe resources. (LO-ID 03\_007\_0780)
- apply methods for developing ontologies. (LO-ID SODa\_03\_007\_0854)
- apply a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0627)
- apply methods for modelling a domain ontology using the CIDOC CRM reference model under guidance. (LO-ID SODa\_03\_007\_0786a) 
- apply software used for creating ontologies. (LO-ID SODa_03_007_0840)
- apply Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa_03_007_0855)
- apply Scope Notes of the CIDOC CRM reference model for describing resources. (LO-ID SODa\_03\_007\_0780a)

---

## Learning Objectives for Module 3: **From Diagram to Paths – Explain and Apply**

Upon completion of Module 3, participants will be able to…

**UE1. Visualising a Semantic Domain Ontology**

- name software for visualising a domain ontology. (LO-ID SODa\_03\_007\_0812)
- explain software for visualising a domain ontology. (LO-ID SODa\_03\_007\_0813)
- explain the concept of visualisation. (LO-ID SODa\_03\_007\_0851)
- explain the benefits of visualisations. (LO-ID SODa\_03\_007\_0852)
- name the benefits of software for visualising a domain ontology. (LO-ID SODa\_03\_007\_0814)
- apply software for visualising a domain ontology with guidance. (LO-ID SODa\_03\_007\_0815)
- name the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0806)
- apply the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0811)
- name rules for modelling a domain ontology using visualisation software. (LO-ID SODa\_03\_007\_0820)
- apply rules for modelling a domain ontology using visualisation software. (LO-ID SODa\_03\_007\_0816)
- apply attribute values to predefined classes of the domain ontology in visualisation software. (LO-ID SODa\_03\_007\_0817)

**UE2. Transforming Semantic Models into WissKI Paths**

- explain WissKI Pathbuilder as a tool for defining an ontology structure. (LO-ID SODa\_03\_007\_0804)
- apply a conversion process starting from a diagram created with visualisation software into a reusable file format with guidance. (LO-ID SODa\_02\_005\_0298a)
- apply WissKI Pathbuilder as a tool for importing a Pathbuilder XML configuration into the WissKI Pathbuilder with guidance. (LO-ID SODa\_03\_007\_0818)
- analyse the imported domain-specific ontology structure in the WissKI Pathbuilder with guidance. (LO-ID SODa\_03\_007\_0819)
- name the gnm-service Draw.io diagrams to WissKI pathbuilders as a tool for file conversion. (LO-ID SODa\_02\_005\_0317) 
- apply the gnm-service to convert Draw.io XML into WissKI Pathbuilder XML with guidance. (LO-ID SODa\_02\_005\_0318)

---

### Additional Observable Objectives for the Extended Final Workflow

The following clarifications describe tasks already included in M3UE2; no new SODa learning-objective IDs are assigned here. After completing the unit, participants will be able, under guidance, to:

- distinguish an ontology import from a Pathbuilder configuration import,
- load the domain ontology required for the workflow and update the SALZ adapter,
- check the generated bundles and fields and save an initial record about the example object,
- explain the relationship between the diagram, semantic path, input field and actual title value,
- distinguish successful technical transformation from domain-level checking and document discrepancies.

The historical objective wording referring to the Pathbuilder as a tool for defining an ontology structure is retained with its IDs. In this tutorial, it means **configuring semantic paths based on an existing ontology**, not defining the ontology itself.

---

## Cross-Language Consistency and Quality Assurance

The German and English versions should represent the same learning path, core tasks, learning-objective IDs, modelling assumptions, outputs and review criteria. The German version provides the content and structural reference; obvious errors in either version must not be copied uncritically into the other. English text uses British English, for example *modelling*, *formalise*, *analyse* and *visualisation*.

All 15 regular units have counterparts. Learning-objective ID sets agree in 14 pairs; the English Module 1 overview uses `SODa_03_007_0849` instead of `SODa_03_007_0804` for the Pathbuilder objective. Both concepts continue to use `0804`, following the German overview and both subject units M1E4/M1U4. This does not replace external verification of the learning-objective registry.

**Check before publication:** self-study alternatives, object-specific examples, Module 2 timings, internal references, resource paths and ontology releases. Both Module 3 overviews also need to reflect the data entry already included in the final unit. This concept update does not correct errors in the unchanged unit files. TaDiRAH mapping must be context-sensitive; the archive does not contain a complete mapping table for every learning objective, and none is claimed here.

---

## Bibliography

[1] Döring, K. W. (2009): Handbuch Lehren und Trainieren in der Weiterbildung. Beltz.

[2] Petersen, B., Altemeier, F., Boße, S., Dalby, M., Düvel, N., Engelhardt, C., Fichtner, M., Hastik, C., Haugwitz, J.-M., Jacob, J., Koch, K., Kuntz, A., Manske, A., Mühlichen, A., Murcia Serra, J., Ortmeyer, J., Richter, M., Schranzhofer, H., Slowig, B., … Zollitsch, L. (2025). Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) (Version 3). Zenodo. https://doi.org/10.5281/zenodo.15025246

[3] Reichert, R., Hastik, C., Gnyp, A., Markert, M., & Tharandt, L. (2025). SODa Personas. Zenodo. https://doi.org/10.5281/zenodo.15574575

[4] Hastik, C., & Schwenk, G. A. (2026). Die Verschränkung von Lernzielmatrix und TaDiRAH zur Entwicklung kompetenzorientierter Lernpfade [Graphic]. Zenodo. Scoping Workshop der VolkswagenStiftung "Zukunftskompetenzen Forschungsdatenmanagement gestalten: Anforderungen an Kompetenzen, Terminologien und Communitys für datengetriebene Wissenschaft", Schloss Herrenhausen, Hannover. https://doi.org/10.5281/zenodo.20829481


