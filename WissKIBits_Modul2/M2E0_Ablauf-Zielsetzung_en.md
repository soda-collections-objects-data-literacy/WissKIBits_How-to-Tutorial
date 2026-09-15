<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This module is part of the how-to tutorial “Ontology-Based Modeling of Research Data”. Using a computer game collection as an example, the tutorial teaches the step-by-step development of a semantic data model based on CIDOC CRM and its implementation with WissKI.

title: WissKI Bits Ontology-Based Modeling of Research Data

module: Modeling with CIDOC CRM – understand and apply

unit: Welcome, objectives and structure

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->


# WissKI Bits: Ontology-Based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 2: **Modeling with CIDOC CRM – understand and apply**

Unit 0: **Welcome, objectives and structure**  

**Duration:** ~ 10 min.


---

## Welcome

> Welcome to **WissKI Bits: Ontology-Based Modeling of Research Data**.
>
> This how-to tutorial provides a practice-oriented introduction to ontology-based modeling of research data. Starting from information about a collection object, a semantically meaningful data model is developed step by step and prepared for later implementation in WissKI.
>
> Module 2, **“Modeling with CIDOC CRM – understand and apply,”** continues the learning path from Module 1. The conceptual domain model is systematically reviewed and formalized using CIDOC CRM and Protégé. Modeling decisions are not only made, but are also justified from a domain perspective using Scope Notes and implemented in a machine-readable ontology structure.
>
> The module continues to follow the principle of **Learning by Doing**. Using an example from the computer games domain, it demonstrates how a model sketch becomes a formal ontology structure. Participants become familiar with Protégé as an ontology editor, explore an OWL implementation of CIDOC CRM, and extend it with selected domain-specific concepts.
>
> The result forms the basis for the subsequent implementation of the ontology structure and semantic paths in the WissKI Pathbuilder.

---

## Objectives of the module

In Module 2, the conceptual domain model from Module 1 is formalized in Protégé using CIDOC CRM.

- Methods for developing ontologies are introduced, compared, and applied to the example. 
- A step-by-step workflow for semantic modeling is named and applied.
- Protégé is introduced as software for creating and editing ontologies.
- An existing OWL implementation of CIDOC CRM is loaded and its structure explored.
- Concepts from the model sketch are mapped to suitable CIDOC CRM classes (Entities) and properties (Properties) based on their Scope Notes.
- Domain-specific concepts are added as subclasses and integrated into the existing class hierarchy.
- Object properties and datatype properties are distinguished and used in the model.
- The extended ontology is saved and prepared for further implementation in WissKI.
  
---

## Guiding question

> **How does a conceptual model sketch become a domain-informed and machine-readable ontology structure based on CIDOC CRM?**

This guiding question accompanies all units of the module. Three work steps are distinguished:

| Work step | Guiding question | Result |
|---|---|---|
| Plan methodically | Which steps and modeling decisions are required? | Modeling workflow |
| Implement formally | How are classes (Entities) and properties (Properties) created or reused in Protégé? | Formal ontology structure |
| Review from a domain perspective | Do the selected CIDOC CRM elements correspond to the intended statement according to their Scope Notes? | Well-founded and consistent model |

---

## Structure of the module

**Total duration of Module 2: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| 0 | Welcome, objectives and structure | 10 min. |
| 1 | Methods and workflows of semantic modeling | 5 min. |
| 2 | Introduction to Protégé | 20 min. |
| E1 | Semantic modeling with CIDOC CRM | 55 min. |
|  | **Total** | **90 min.** |

  
---

## Learning objectives of the module

After completing Module 2, participants can…

### 1. Methods and workflows of semantic modeling

- name methods for developing ontologies. (LO-ID 03\_007\_0784)
- explain methods for developing ontologies. (LO-ID SODa\_03\_007\_0839)
- name a workflow for semantic modeling as data documentation. (LO-ID SODa\_03\_001\_0626)
- explain a workflow for semantic modeling as data documentation. (LO-ID SODa\_03\_001\_0853)
- name methods for modeling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0784a)
- explain methods for modeling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

### 2. Introduction to Protégé

- name software for creating ontologies. (LO-ID SODa\_03\_007\_0809)
- explain software for creating ontologies. (LO-ID SODa\_03\_007\_0810)
- name Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0841)
- apply software for creating ontologies. (LO-ID SODa\_03\_007\_0840)
- name methods for modeling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0784a)
- explain methods for modeling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

### E1. Semantic modeling with CIDOC CRM

- apply an ontology for describing resources. (LO-ID 03\_007\_0780)
- apply methods for developing ontologies. (LO-ID SODa\_03\_007\_0854)
- apply a workflow for semantic modeling as data documentation. (LO-ID SODa\_03\_001\_0627)
- apply methods for modeling a domain ontology using the CIDOC CRM reference model under guidance. (LO-ID SODa\_03\_001\_0786a) 
- apply software for creating ontologies. (LO-ID SODa_03_007_0840)
- apply Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa_03_007_0855)
- apply Scope Notes of the CIDOC CRM reference model for describing resources. (LO-ID SODa\_03\_007\_0780a)


---

## Learning path in the module

## Learning path in the module

**Conceptual model sketch from Module 1**
 
↓
   
**Define the methodological workflow**
   
↓
   
**Explore CIDOC CRM in Protégé**
 
↓
 
**Select classes (Entities) and properties (Properties)**
 
↓
 
**Add domain-specific subclasses**
 
↓
 
**Review and save the model and prepare it for WissKI**

> **Figure:** The graphic illustrates the learning path of the module.

---

## Working method and example

The module combines methodological input, demonstration, and guided application:

- Participants learn basic methods and an iterative workflow for ontology development.
- The user interface and central areas of Protégé are introduced in a live or video demonstration.
- The current version of the OWL implementation **[Erlangen CRM](https://erlangen-crm.org/current-version)** (Schiemann2024crm) is loaded and explored through its classes, object properties, and datatype properties.
- The example object **“The Legend of Zelda: A Link to the Past”** and the model sketch developed in Module 1 once again serve as a common thread.
- Selected concepts are compared with CIDOC CRM using the Scope Notes.
- Domain-specific concepts such as game characteristic, platform type, genre type, or edition type are modeled as subclasses.
- Suitable relationships between the concepts and events are selected.
- Participants document their decisions and review the model step by step for comprehensibility and consistency.

The goal is not a complete domain ontology. What matters is a **small, comprehensible, and formally usable extension of CIDOC CRM** that prepares the transition to implementation in WissKI.

---

## Prerequisites

The content of Module 1 or comparable basic knowledge is assumed, such as having one's own semantic domain model based on CIDOC CRM. 

Participants should…

- be able to distinguish the terms domain, concept, event, and relationship,
- know the building blocks classes (Entities), properties (Properties), instances (Instances), and modeling assumptions (Assumptions),
- understand the basic principle of event-centered modeling with CIDOC CRM,
- know Scope Notes as a basis for modeling decisions,
- and have at least an initial conceptual model sketch, ideally a CIDOC CRM-based semantic domain model.

For the practical application, a computer with either **Protégé Desktop** installed or an account for **WebProtégé** is required.  
Either option can be selected on the [Stanford University](https://protege.stanford.edu/software) website. (Stanfordo.D.protege) 

In addition, the **OWL file of Erlangen CRM** used in the tutorial must be available locally or accessible via a web address.

---
 
## Result of the module

At the end of Module 2, an initial formally implemented domain ontology or ontology extension is available. 

It contains:

- selected and domain-informed classes (Entities) and properties (Properties) of CIDOC CRM,
- domain-specific subclasses for central concepts of the example,
- at least one modeled semantic relationship between the selected classes,
- at least one appropriately used datatype property,
- and documentation of central modeling decisions based on the Scope Notes.

The ontology is saved as an OWL file and forms the basis for subsequent technical integration and path modeling in WissKI.

---

## Outlook

In the following module, the ontology created or extended in Protégé is integrated into WissKI. On this basis, groups and semantic paths are created in the WissKI Pathbuilder and made usable for the structured recording of research data.

---

## Editorial notes

- The schedule is designed for a total of 90 minutes and can be adjusted depending on the scope of the practical exercise.

<!--For Krakow omitted: (Krakow half day = 3.5 hrs - Modules 1-3 = 4.5 hrs - then another 10 min. are missing) b. 45 min. M2E complete -->
