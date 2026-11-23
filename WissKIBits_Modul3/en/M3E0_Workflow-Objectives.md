<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_Wort-Bild_RGB.png

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This module is part of the how-to tutorial “Ontology-Based Modelling of Research Data”. Using a computer game collection as an example, the tutorial teaches the step-by-step development of a semantic data model based on CIDOC CRM and its implementation with WissKI.

title: WissKI Bits Ontology-Based Modelling of Research Data

module: From Diagram to Paths – Explain and Apply

unit: Welcome, Workflow and Objectives

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE**

Module 3 (M3): **From Diagram to Paths – Explain and Apply**

Unit 0 (U0): **Welcome, Workflow and Objectives**

**Duration:** ~ 10 min.

---

## Welcome to WissKI Bits: Ontology-Based Modelling of Research Data

In Module 1 [From the Collection via Modelling Decisions to the Diagram – Understand and Explain](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/en/M3UE1_Domain-Ontologie-Diagram_en.md#1), you developed a conceptual model sketch. In Module 2 [Modelling with CIDOC CRM – Understand and Apply](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/en/M3UE2_Drawio-to-WissKI-Paths_en.md#1), you reviewed selected CIDOC CRM mappings and formalised parts of your domain model using Protégé.

In **Module 3: From Diagram to Paths – Explain and Apply**, you will prepare this model for use in WissKI. Using a **computer game collection as an example**, you will complete a semantic diagram in Draw.io, transform it into a WissKI Pathbuilder XML file, and examine the imported paths and path groups in WissKI.

The focus is on a traceable and repeatable workflow rather than the complete technical configuration of a WissKI instance.

> **What is this module about?**
>
> In this module, you move from a formal ontology structure to a usable WissKI Pathbuilder configuration.
>
> **Ontology → Draw.io diagram → Pathbuilder XML → Paths and path groups in WissKI**
>
> You will learn how to prepare a semantic diagram for transformation, generate the required XML file, and check whether the imported path structure reflects the intended model.

---

## Guiding Question

The following guiding question accompanies us throughout this module:

> **How can a semantic data model be transformed into a valid structure of paths and path groups that can be used in WissKI?**

---

## Module Objectives

In this module, you will convert the formalised domain ontology from module 2 into a path structure that can be used in WissKI.

In this module, you will learn how to:

- visualise the partial model in **Draw.io** according to defined modelling rules,
- apply the diagram structure and attribute values required for conversion,
- export and transform the Draw.io XML into a **WissKI Pathbuilder XML**,
- import the generated strucconfiguration into **WissKI**, and
- inspect and verify the resulting **paths and path groups**.

The goal is to understand and complete the workflow from a semantic model to a usable Pathbuilder configuration.

---

## Module Workflow

**Total duration of module 3: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| M3U0 | [Welcome, workflow and objectives](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/en/M3E0_Workflow-Objectives.md#1) | 10 min. |
| M3UE1 | [Visualising a semantic domain ontology](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/en/M3UE1_Domain-Ontologie-Diagram_en.md#1) | 35 min. |
| M3UE2 | [Transforming semantic models into WissKI paths](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/en/M3UE2_Drawio-to-WissKI-Paths_en.md#1) | 45 min. |
|  | **Total** | **90 min.** |

---

## Module Learning Objectives

After completing module 3, participants will be able to…

### UE1. Visualising a Semantic Domain Ontology

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

### UE2. Transforming Semantic Models into WissKI Paths

- explain WissKI Pathbuilder as a tool for defining an ontology structure. (LO-ID SODa\_03\_007\_0804)
- apply a conversion process starting from a diagram created with visualisation software into a reusable file format with guidance. (LO-ID SODa\_02\_005\_0298a)
- apply WissKI Pathbuilder as a tool for importing a Pathbuilder XML configuration into the WissKI Pathbuilder with guidance. (LO-ID SODa\_03\_007\_0818)
- analyse the imported domain-specific ontology structure in the WissKI Pathbuilder with guidance. (LO-ID SODa\_03\_007\_0819)
- name the gnm-service Draw.io diagrams to WissKI pathbuilders as a tool for file conversion. (LO-ID SODa\_02\_005\_0317) 
- apply the gnm-service to convert Draw.io XML into WissKI Pathbuilder XML with guidance. (LO-ID SODa\_02\_005\_0318)

---

## Learning Path in the Module

Starting from the formal ontology structure developed in module 2, participants work through the following steps:

**Visualise the semantic data model (M3UE1):** 
Represent selected classes and properties of the domain ontology in a structured Draw.io diagram.

↓
  
**Check the diagram (M3UE1):** 
Review the connections and attribute values required for transformation.

↓
 
**Generate Pathbuilder XML (M3UE2):** 
Transform the Draw.io XML file into a WissKI Pathbuilder XML file.

↓
 
**Integrate the ontologies and path structure into WissKI (M3UE2):** 
Integrate the required ontologies and import the generated file into the WissKI Pathbuilder.

↓
  
**Analyse paths and path groups (M3UE2):** 
Examine the imported path structure and compare it with the original diagram.

↓

**Outcome:**
A selected part of the semantic domain model is available as a usable path structure in WissKI.

---

## Working Method and Example

> **How you will work**
>
> Our example continues to be the collection object **The Legend of Zelda: A Link to the Past** and the semantic domain model developed in modules 1 and 2.
> 
> You will work with a prepared Draw.io diagram, complete missing classes and properties, and check the connections and attribute values required for transformation.
>
> You will then transform the diagram using the “Draw.io diagrams to WissKI pathbuilders” conversion service and import the generated file into WissKI.
>
> Finally, you will compare the imported paths and path groups with the original diagram and the intended information and query requirements.

The module combines short conceptual and methodological inputs with demonstrations and guided practical exercises. The aim is a traceable and repeatable workflow from a semantic data model to a usable path structure in WissKI.

---

## Prerequisites

This module builds on the knowledge and results from modules 1 and 2, or comparable prior experience.

Before starting, you should:

- be able to identify concepts, events, and relationships within a domain,
- understand the event-centred modelling approach of CIDOC CRM,
- be familiar with CIDOC CRM classes, properties, and scope notes,
- understand how domain-specific concepts can be represented as subclasses of CIDOC CRM classes, and
- have access to the ontology structure developed in Module 2 or the prepared example ontology.

You do not need prior experience with the WissKI Pathbuilder. Its basic functions are introduced in this module.

For the practical exercises, you will need the following technical setup:

- a computer with internet access,
- access to [diagrams.net (Draw.io)](https://app.diagrams.net/),
- the prepared [Draw.io XML gap diagram](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_B.drawio.xml),
- access to the conversion service [Draw.io diagrams to WissKI pathbuilders](https://isl.ics.forth.gr/gnm_services),
- access to a WissKI instance via the [SODa Semantic Co-Working Space (SCS)](https://manager.scs.sammlungen.io/de),
- as well as the [domain ontology](http://games.m-e-g-a.org/game_domain.rdf) used in the tutorial and the reference ontology [Erlangen CRM / OWL](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl).

---

## Result and Outcome of the Module

By the end of module 3, you will have completed the workflow from a semantic data model to a usable path structure in WissKI.

> **What will you take away from this module?**
>  
> Your results include
> 
> - a completed and checked Draw.io diagram,
> - an exported Draw.io XML file,
> - a generated WissKI Pathbuilder XML file,
> - imported paths and path groups in WissKI, and
> - a documented comparison of the imported structure with the original model and selected research and query requirements.

For reference, you can consult the provided example files: 

- a validated semantic [Draw.io diagram](../WissKIBits_Modul3/assets/GamesDrawioDiagramm.png),
- an exported [Draw.io XML file](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/SODa_ISWC2025.drawio.xml),
- a generated [WissKI Pathbuilder XML file](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput_ISWC2025.xml),

These results provide a basis for creating data entry structures and working with semantically structured research data in WissKI.

---

## Outlook

Module 3 continues the learning path from the conceptual model sketch and the formal ontology structure to the technical implementation of selected parts of the semantic data model.

In subsequent steps, the imported paths and path groups can be used to create data entry structures in WissKI. Example data can then be recorded and examined in relation to the initial research and query requirements.

> **What comes Next?**
>
> In the next unit, [M3UE1: Visualising Semantic Data Models](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/en/M3UE1_Domain-Ontologie-Diagram_en.md#1), you will learn how to visualise selected parts of a domain ontology using Draw.io and prepare the diagram for subsequent transformation.

For further information, documentation, and community resources, visit the website: https://wiss-ki.eu/de. (as of August 2026)

---

## Editorial Notes

* The schedule is designed for a total of 90 minutes. Since both subject-specific units include practical tasks, the duration should be reviewed after a test run.
