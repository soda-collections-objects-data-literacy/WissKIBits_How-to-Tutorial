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

Welcome to **WissKI Bits: Ontology-Based Modeling of Research Data**.

In this module, we formalize the conceptual domain model developed in Module 1. We use **CIDOC CRM and Protégé** to translate modeling decisions into a machine-readable ontology structure and prepare it for later implementation in WissKI.

Module 2, **“Modeling with CIDOC CRM – understand and apply,”** continues the learning path from Module 1. The conceptual domain model is systematically reviewed and formalized using CIDOC CRM and Protégé. Modeling decisions are not only made, but are also justified from a domain perspective using Scope Notes and implemented in a machine-readable ontology structure.

The module continues to follow the principle of **Learning by Doing**. Using an example from the computer games domain, it demonstrates how a model sketch becomes a formal ontology structure. Participants become familiar with Protégé as an ontology editor, explore an OWL implementation of CIDOC CRM, and extend it with selected domain-specific concepts.

The result forms the basis for the subsequent implementation of the ontology structure and semantic paths in the WissKI Pathbuilder.


> **What is the module about?**
>
> Module 1, we focused on identifying and structuring the meaning of collection and research data.
>
> You developed a conceptual model by identifying relevant concepts, events, and relationships and relating them to CIDOC CRM.
>
> In Module 2, we take the next step: we transform this conceptual model into a formal, machine-readable ontology structure.
>
> Using **CIDOC CRM and Protégé**, we examine how concepts and relationships from the conceptual model can be represented as classes and properties.
>
> We use CIDOC CRM scope notes to evaluate modeling choices, reuse, and specialise existing ontology elements where appropriate, and implement selected domain-specific structures in the ontology editor.
>
> The result is a **formalised domain model** that provides the basis for its visualisation and technical implementation in WissKI in Module 3.


---

## Guiding question

Our guiding question is...

> **How does a conceptual model sketch become a domain-informed and machine-readable ontology structure based on CIDOC CRM?**

---

## Objectives of the module

In this module, we will learn how to:

- apply a systematic **workflow for semantic modeling**,
- use **Protégé** to explore and edit an ontology,
- select suitable **CIDOC CRM classes and properties** based on their Scope Notes,
- add **domain-specific concepts** to an existing ontology structure,
- distinguish and use **object properties and datatype properties**, and
- prepare the resulting ontology for further implementation in **WissKI**.
  
---

## Structure of the module

**Total duration of module 2: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| 0 | Welcome, objectives and structure | 10 min. |
| E1A | Activation: | 30 min. |
| 1 | Methods and workflows of semantic modeling | 10 min. |
| 2 | Introduction to Protégé | 10 min. |
| E1E | Excersise: Semantic modeling with CIDOC CRM | 30 min. |
|  | **Total** | **90 min.** |

  
---

## Learning objectives of the module

After completing Module 2, participants can…

### E2A. Methods and workflows of semantic modeling

- name... 


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

### E2. Semantic modeling with CIDOC CRM

- apply an ontology for describing resources. (LO-ID 03\_007\_0780)
- apply methods for developing ontologies. (LO-ID SODa\_03\_007\_0854)
- apply a workflow for semantic modeling as data documentation. (LO-ID SODa\_03\_001\_0627)
- apply methods for modeling a domain ontology using the CIDOC CRM reference model under guidance. (LO-ID SODa\_03\_001\_0786a) 
- apply software for creating ontologies. (LO-ID SODa_03_007_0840)
- apply Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa_03_007_0855)
- apply Scope Notes of the CIDOC CRM reference model for describing resources. (LO-ID SODa\_03\_007\_0780a)

---

## Learning path through the module

The diagram illustrates the learning path of the module.

**Conceptual model sketch from Module 1**
 
↓
   
**Activation: Prepare your technical setup**
   
↓

**Define the methodological workflow**
   
↓
   
**Explore CIDOC CRM in Protégé**
 
↓
 
**Select classes (Entities) and properties (Properties) using Scope Notes**
 
↓
 
**Add domain-specific subclasses**
 
↓
 
**Review and and document modeling decisions**

↓

**save the ontology and prepare it for WissKI**


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

> **How we work**
>
> Short methodological inputs alternate with demonstration and hands-on modeling.
>
> We continue working with **The Legend of Zelda: A Link to the Past** and the model sketch developed in Module 1.
>
> We use **Protégé**, we explore an **OWL implementation of CIDOC CRM** - the Erlangen CRM - evaluate modeling choices using scope notes, and extend the ontology with selected domain-specific concepts and relationships.
>
> The goal is not a complete domain ontology, but a small, transparent, and formally usable extension of CIDOC CRM.

---

## Prerequisites

The content of Module 1 or comparable basic knowledge is assumed, such as having one's own semantic domain model based on CIDOC CRM. 

Participants should…

- be able to distinguish the terms domain, concept, event, and relationship,
- know the building blocks classes (Entities), properties (Properties), instances (Instances), and modeling assumptions (Assumptions),
- understand the basic principle of event-centered modeling with CIDOC CRM,
- know Scope Notes as a basis for modeling decisions,
- and have at least an initial conceptual model sketch, ideally a CIDOC CRM-based semantic domain model.

> **What do you need**
>
> Module 2 builds on Module 1 or equivalent prior knowledge.
>
> Participants should be familiar with concepts, events, relationships, classes, properties, instances, modeling assumptions, CIDOC CRM, and Scope Notes, and should have a first conceptual model sketch available.
>
> For the practical activities, participants need access to Protégé Desktop or WebProtégé and the OWL implementation of CIDOC CRM used in the tutorial.

---
 
## Result and outcome of the module

At the end of Module 2, an initial formally implemented domain ontology or ontology extension is available. 

> **What will you take away**
>
> By the end of the module, you will have created a first formal domain ontology or ontology extension that includes:
>
> - selected and justified CIDOC CRM classes and properties,
> - domain-specific subclasses,
> - semantic relationships and datatype properties, and
> - documented modeling decisions based on Scope Notes.
>
> The ontology is saved as an OWL file and provides the basis for subsequent implementation in WissKI.

---

## Outlook

> In the next module, we import the ontology into WissKI and use it to define groups and semantic paths in the WissKI Pathbuilder.

---

## Editorial notes

- The schedule is designed for a total of 90 minutes and can be adjusted depending on the scope of the practical exercise.
