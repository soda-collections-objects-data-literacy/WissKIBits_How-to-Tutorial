<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This module is part of the how-to tutorial “Ontology-Based Modelling of Research Data”. Using a computer game collection as an example, the tutorial guides learners step by step through the development of a semantic data model based on CIDOC CRM and its implementation with WissKI.

title: WissKI Bits Ontology-Based Modelling of Research Data

module: From Diagram to Paths – Explain and Apply

unit: Welcome, Objectives and Workflow

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: SODa How-to Tutorial

-->

# Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE**

Module 3 (M3): **From Diagram to Paths – Explain and Apply**

Unit 0 (U0): **Welcome, Workflow and Objectives**

**Duration:** ~ 10 min.

---

## Welcome

Welcome to **SODa WissKI Bits: Ontology-Based Modelling of Research Data**.

In Module 1, you developed a conceptual model sketch. In Module 2, you reviewed selected CIDOC CRM mappings and formalised part of your domain model in Protégé.

In Module 3, you will prepare this model for use in WissKI. Using the computer games example, you will create a structured diagram in Draw.io, transform it into a Pathbuilder XML file, and examine the imported paths and path groups in WissKI.

The focus is on a practical, reproducible workflow rather than configuring a complete WissKI instance.

> **What is This Module About?**
>
> In this module, you move from a formal ontology structure to a WissKI Pathbuilder configuration.
>
> Module 3 turns this structure into usable semantic paths: **Ontology → Draw.io Diagram → Pathbuilder XML → WissKI path groups and paths**
>
> You will learn how to prepare a semantic diagram for transformation, generate the required XML file, and check whether the imported structure reflects the intended model.

---

## Guiding Question

> **How can a semantic data model be transformed into a valid structure of paths and path groups that can be used in WissKI?**

---

## Module Objectives

In this module, you will convert the formalised domain ontology from Module 2 into a path structure that can be used in WissKI.

In this module, you will learn how to:

- visualise the partial model in **Draw.io** according to defined modelling rules,
- apply the diagram structure and attribute values required for conversion,
- export and transform the Draw.io XML into a **WissKI Pathbuilder XML**,
- import the generated strucconfiguration into **WissKI**, and
- inspect and verify the resulting **paths and path groups**.

The goal is to understand and complete the workflow from a semantic model to a usable Pathbuilder configuration.

---

## Module Workflow

**Total duration of Module 3: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| M3U0 | Welcome, workflow and objectives| 10 min. |
| M3UE1 | Visualising semantic data models | 35 min. |
| M3UE2 | Transforming semantic models into WissKI paths | 45 min. |
|  | **Total** | **90 min.** |

---

## Module Learning Objectives

After completing Module 3, participants can…

### UE1. Visualising Semantic Data Models

- Name software for visualising a domain ontology. (LZ-ID SODa\_03\_007\_0812)
- Explain software for visualising a domain ontology. (LZ-ID LZ-ID SODa\_03\_007\_0813)
- Explain the concept of visualisation. (LZ-ID SODa\_03\_007\_0851)
- Explain the benefits of visualisations. (LZ-ID SODa\_03\_007\_0852)
- Name the benefits of software for visualising a domain ontology. (LZ-ID SODa\_03\_007\_0814)
- Use software for visualising a domain ontology with guidance. (LZ-ID SODa\_03\_007\_0815)
- Name the core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa\_03\_007\_0806)
- Apply the core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa\_03\_007\_0811)
- Name rules for modelling a domain ontology using visualisation software. (LZ-ID SODa\_03\_007\_0820)
- Apply rules for modelling a domain ontology using visualisation software. (LZ-ID SODa\_03\_007\_0816)
- Apply attribute values to predefined classes of the domain ontology in visualisation software. (LZ-ID SODa\_03\_007\_0817)

### UE2. Transforming Semantic Models into WissKI Paths

- Explain WissKI Pathbuilder as a tool for defining an ontology structure. (LZ-ID SODa\_03\_007\_0804)
- With guidance, perform data conversion from visualisation software into a reusable file format. (LZ-ID SODa\_02\_005\_0298a)
- With guidance, use WissKI Pathbuilder as a tool for importing a domain-specific ontology structure (Pathbuilder XML file into the WissKI Pathbuilder). (LZ-ID SODa\_03\_007\_0818)
- With guidance, analyse the imported domain-specific ontology structure in the WissKI Pathbuilder. (LZ-ID SODa\_03\_007\_0819)
- Name a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion. (LZ-ID SODa\_02\_005\_0317)
- With guidance, use a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion. (LZ-ID SODa\_02\_005\_0318)

---

## Learning Path in the Module

**Formal ontology structure from Module 2** You start with the domain-specific ontology structure developed in Protégé.
 
↓
 
**Visualise classes and properties in Draw.io** You represent selected ontology classes and relationships in a structured diagram.
 
↓
  
**Check the diagram** You review the connections and attribute values required for transformation.
 
↓
 
**Generate Pathbuilder XML** You export the Draw.io XML file and transform it into a WissKI Pathbuilder XML file.
 
↓
 
**Import into WissKI** You import the generated file into the WissKI Pathbuilder.
 
↓
  
**Review paths and path groups** You inspect the imported structure and compare it with the original diagram.



> **Figure:** The graphic illustrates the learning path of the module.

---

## Working Method and Example

The computer game example **“The Legend of Zelda: A Link to the Past”** and the domain model developed in Modules 1 and 2 continue to serve as the starting point.

You will work with a prepared Draw.io diagram, complete missing classes and properties, and check the connections and attribute values required for transformation.

You will then export the diagram, use the Draw.io diagrams to WissKI pathbuilders service to generate a Pathbuilder XML file, and import the result into WissKI.

Finally, you will compare the generated paths and path groups with the source diagram and the intended information requirements.

The aim is a **traceable and repeatable processing chain**, not a complete technical configuration of WissKI.

---

## Prerequisites

This module builds on the knowledge and results from Modules 1 and 2, or comparable prior experience.

Before starting, you should:

- be able to identify concepts, events, and relationships within a domain,
- understand the event-centred modelling approach of CIDOC CRM,
- be familiar with CIDOC CRM classes, properties, and scope notes,
- understand how domain-specific concepts can be represented as subclasses of CIDOC CRM classes, and
- have access to the ontology structure developed in Module 2 or the prepared example ontology.

You do not need prior experience with the WissKI Pathbuilder. Its basic functions are introduced in this module.

**Technical Setup**

- a computer with internet access,
- access to [diagrams.net (Draw.io)](https://app.diagrams.net/),
- the prepared [Draw.io XML gap diagram](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_B.drawio.xml),
- access to the conversion service [Draw.io diagrams to WissKI pathbuilders](https://isl.ics.forth.gr/gnm_services),
- access to a WissKI instance via the [SODa Semantic Co-Working Space (SCS)](https://manager.scs.sammlungen.io/de),
- as well as the [domain ontology](http://games.m-e-g-a.org/game_domain.rdf) used in the tutorial and the reference ontology [Erlangen CRM / OWL](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl).

---

## Result and Outcome of the Module

By the end of the module, you will have completed the workflow from a semantic model to a usable WissKI path structure.

Your results include:

- a completed and checked Draw.io diagram,
- an exported Draw.io XML file,
- a generated WissKI Pathbuilder XML file,
- imported paths and path groups in WissKI, and
- a documented comparison of the imported structure with the original model and selected research and query requirements.

For reference, you can consult the provided example files: 

- a validated semantic [Draw.io diagram](../WissKIBits_Modul3/assets/GamesDrawioDiagramm.png),
- an exported [Draw.io XML file](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/SODa_ISWC2025.drawio.xml),
- a generated [WissKI Pathbuilder XML file](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput_ISWC2025.xml),

These results provide a basis for creating data entry structures and working with semantically structured research data in WissKI.

---

## Outlook

> **Next**
>
> The imported paths and path groups can be used to create data entry structures in WissKI. Example data can then be entered and examined in relation to the initial research and query requirements.

For further information, documentation, and community resources, visit the website: https://wiss-ki.eu/de. (as of August 2026)

---

## Editorial Notes

* The schedule is designed for a total of 90 minutes. Since both subject-specific units include practical tasks, the duration should be reviewed after a test run.
