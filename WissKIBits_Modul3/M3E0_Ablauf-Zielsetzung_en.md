<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This module is part of the how-to tutorial “Ontology-based Modeling of Research Data”. Using a video game collection as an example, the tutorial guides learners step by step through the development of a semantic data model based on CIDOC CRM and its implementation with WissKI.

title: WissKI Bits Ontology-based Modeling of Research Data

module: From Diagram to Paths – Explain and Apply

unit: Welcome, Objectives and Workflow

description: The SODa how-to tutorial uses a video game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacies (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->

# Ontology-based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE**

Module 3: **From Diagram to Paths – Explain and Apply**

Unit 0: **Welcome, Objectives and Workflow**

**Duration:** ~ 10 min.

---

## Welcome

Welcome to **SODa WissKI Bits: Ontology-based Modeling of Research Data**.

This how-to tutorial provides a practice-oriented introduction to the ontology-based modeling of research data. Starting from information about a collection object, a semantically meaningful data model is developed step by step and implemented for use in WissKI.

In Module 1, a conceptual model sketch was developed from object data and contextual information. In Module 2, this sketch was methodically reviewed and implemented as a formal ontology structure using CIDOC CRM and Protégé.

Module 3, **“From Diagram to Paths – Explain and Apply”**, continues this learning path into technical implementation: The semantic data model is visualized in Draw.io as a formally structured diagram. The diagram is then checked using the **“Draw.io diagrams to WissKI pathbuilders”** web service and transformed into a WissKI Pathbuilder XML file.

The generated file is imported into WissKI. There, the paths and path groups are analyzed and prepared as the basis for the structured capture, storage, and querying of research data.

The module follows the principle of **Learning by Doing**. Using an example from the video game domain, participants work through the entire processing chain from the semantic diagram and file conversion to the imported path structure in the WissKI Pathbuilder.

> **What is this module about?**
>
> In this module, we move from a formal ontology structure to its technical implementation in WissKI. We visualize the semantic model in Draw.io, transform the diagram into a Pathbuilder XML file, and import and inspect the resulting paths and path groups in WissKI.
>
> Module 2 resulted in a formal ontology structure.
>
> Module 3 turns this structure into usable semantic paths: **Ontology → Diagram → Pathbuilder XML → WissKI paths**
>
> The focus shifts from defining the semantic model to making it technically usable for structured data capture and querying in WissKI.

---

## Guiding Question

> **How can a semantic data model be transformed into a valid structure of paths and path groups that can be used in WissKI?**

---

## Module Objectives

In this module, you will convert the formalized domain ontology from Module 2 into a path structure that can be used in WissKI.

You will:

- visualize a semantic data model in **Draw.io** according to defined modeling rules,
- represent **classes, properties, and semantic paths** in a machine-processable diagram,
- check the diagram and the **attribute values required for conversion**,
- transform the Draw.io XML into a **WissKI Pathbuilder XML file**,
- import the generated structure into **WissKI**, and
- analyze and verify the resulting **paths and path groups**.

---

## Module Workflow

**Total duration of Module 3: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| 0 | Welcome, objectives and workflow | 10 min. |
| E1 | Visualizing semantic data models | 35 min. |
| E2 | Transforming semantic models into WissKI paths | 40 min. |
|  | **Total** | **90 min.** |

---

## Module Learning Objectives

After completing Module 3, participants can…

### Ü1. Visualising Semantic Data Models

- Name software for visualizing a domain ontology. (LZ-ID SODa\_03\_007\_0812)
- Explain software for visualizing a domain ontology. (LZ-ID LZ-ID SODa\_03\_007\_0813)
- Explain the concept of visualization. (LZ-ID SODa\_03\_007\_0851)
- Explain the benefits of visualizations. (LZ-ID SODa\_03\_007\_0852)
- Name the benefits of software for visualizing a domain ontology. (LZ-ID SODa\_03\_007\_0814)
- Use software for visualizing a domain ontology with guidance. (LZ-ID SODa\_03\_007\_0815)
- Name the core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa\_03\_007\_0806)
- Apply the core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa\_03\_007\_0811)
- Name rules for modeling a domain ontology using visualization software. (LZ-ID SODa\_03\_007\_0820)
- Apply rules for modeling a domain ontology using visualization software. (LZ-ID SODa\_03\_007\_0816)
- Apply attribute values to predefined classes of the domain ontology in visualization software. (LZ-ID SODa\_03\_007\_0817)

### Ü2. Transforming Semantic Models into WissKI Paths

- Explain WissKI Pathbuilder as a tool for defining an ontology structure. (LZ-ID SODa\_03\_007\_0804)
- With guidance, perform data conversion from visualization software into a reusable file format. (LZ-ID SODa\_02\_005\_0298a)
- With guidance, use WissKI Pathbuilder as a tool for importing a domain-specific ontology structure (Pathbuilder XML file into the WissKI Pathbuilder). (LZ-ID SODa\_03\_007\_0818)
- With guidance, analyze the imported domain-specific ontology structure in the WissKI Pathbuilder. (LZ-ID SODa\_03\_007\_0819)
- Name a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion. (LZ-ID SODa\_02\_005\_0317)
- With guidance, use a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion. (LZ-ID SODa\_02\_005\_0318)

---

## Learning Path in the Module

**Formal ontology structure from Module 2**
 
↓
 
**Semantic diagram in Draw.io**
 
↓
  
**Check paths and attribute values**
 
↓
 
**Generate Pathbuilder XML**
 
↓
 
**Import file into WissKI**
 
↓
  
**Verify the path structure against the requirements**



> **Figure:** The graphic illustrates the learning path of the module.

---

## Working Method and Example

The module combines activation, guided modeling, technical transformation, and result verification:

- At the beginning, research and query questions are revisited from the collection perspective: What information should later be findable and queryable via semantic paths?
- The example object **“The Legend of Zelda: A Link to the Past”** and the domain ontology developed in the previous modules again serve as a common thread.
- In Draw.io, participants complete a prepared diagram by adding missing classes (Entities) and properties (Properties).
- They check complete paths, node-edge connections, naming, and the attribute values required for conversion.
- The diagram is submitted to the conversion service as an XML file.
- The generated Pathbuilder XML file is imported into WissKI.
- Finally, paths and path groups are compared with the original diagram and the domain-specific query requirements.

The aim is not the complete technical configuration of a WissKI instance. What matters is a **traceable and repeatable processing chain** that transforms the semantic model into a usable WissKI path structure.

> **How we will work**
>
> The module combines activation, guided modeling, technical transformation, and verification.
>
> We continue working with The Legend of Zelda: A Link to the Past and the domain ontology developed in the previous modules. Starting from selected research and query questions, we complete and check a semantic diagram in Draw.io, convert it into a Pathbuilder XML file, and import the resulting structure into WissKI.
> 
> Finally, we compare the imported paths and path groups with the original model and our initial information requirements.
>
> The goal is not a complete WissKI configuration, but a traceable and repeatable workflow from semantic model to usable WissKI path structure.

---

## Prerequisites

The content from Module 1 and Module 2, or comparable basic knowledge and work results, is assumed. Participants should …

- be able to identify concepts, events, and relationships within a domain,
- be familiar with the event-centered modeling principle and selected elements of CIDOC CRM,
- be able to use Scope Notes for modeling decisions,
- be familiar with a formally implemented domain ontology or ontology extension,
- and understand the basic principle of semantic paths.

> **Prerequisites**
>
> Module 3 builds on Modules 1 and 2 or equivalent prior knowledge. Participants should be familiar with concepts, events, relationships, classes, properties, CIDOC CRM, Scope Notes, and the basic principle of semantic paths. A formalized domain ontology or ontology extension should be available.


**Technical setup**

- a computer with internet access,
- access to [diagrams.net (Draw.io)](https://app.diagrams.net/),
- the prepared [Draw.io XML gap diagram](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_A.drawio.xml),
- access to the conversion service [Draw.io diagrams to WissKI pathbuilders](https://isl.ics.forth.gr/gnm_services),
- access to a WissKI instance via the [SODa Semantic Co-Working Space (SCS)](https://manager.scs.sammlungen.io/de),
- as well as the [domain ontology](http://games.m-e-g-a.org/game_domain.rdf) used in the tutorial and the reference ontology [Erlangen CRM / OWL](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl).


## Result and Outcome of the Module

> ** What you will take away**
>
> By the end of the module, you will have completed the workflow from a semantic model to a usable WissKI path structure.
>
> Your results include:
>
> - a validated semantic [Draw.io diagram](../WissKIBits_Modul3/assets/GamesDrawioDiagramm.png),
> - an exported [Draw.io XML file](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/SODa_ISWC2025.drawio.xml),
> - a generated [WissKI Pathbuilder XML file](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput_ISWC2025.xml),
> - imported paths and path groups in WissKI, and
> - a documented check of whether the implemented structure reflects the original model and selected research and query requirements.
> 
> This provides the basis for creating data entry structures and working with semantically structured research data in WissKI.

---

## Outlook

> In the next step, the imported paths and path groups can be used to create data entry structures in WissKI. Example data can then be entered and tested against the research and query questions defined at the beginning.

For further news, information about WissKI, the WissKI documentation, and the WissKI community (as of August 2026), please refer to the website: https://wiss-ki.eu/de.

---

## Editorial Notes

* The schedule is designed for a total of 90 minutes. Since both subject-specific units include practical tasks, the duration should be reviewed after a test run.
