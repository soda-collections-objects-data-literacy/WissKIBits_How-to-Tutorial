<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This module is part of the how-to tutorial “Ontology-Based Modelling of Research Data”. Using a computer game collection as an example, the tutorial teaches the step-by-step development of a semantic data model based on CIDOC CRM and its implementation with WissKI.

title: WissKI Bits Ontology-Based Modelling of Research Data

module: Modelling with CIDOC CRM – Understand and Apply

unit: Welcome, objectives and structure

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of reseach data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: SODa How-to Tutorial

-->


# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 2 (M2): **Modelling with CIDOC CRM – Understand and Apply**

Unit 0 (U0): **Welcome, Structure and Objectives**  

**Duration:** ~ 10 min.


---

## Welcome

Welcome to **WissKI Bits: Ontology-Based Modelling of Research Data**.

In this module, you formalise the conceptual domain model developed in Module 1. We use **CIDOC CRM and Protégé** to translate modelling decisions into a machine-readable ontology structure and prepare it for later implementation in WissKI.

Module 2, **“Modelling with CIDOC CRM – understand and apply,”** continues the learning path from Module 1. The conceptual domain model is systematically reviewed and formalised using CIDOC CRM and Protégé. Modelling decisions are not only made, but are also justified from a domain perspective using Scope Notes and implemented in a machine-readable ontology structure.

The module continues to follow the principle of **Learning by Doing**. Using an example from the computer games domain, it demonstrates how a model sketch becomes a formal ontology structure. Participants become familiar with Protégé as an ontology editor, explore an OWL implementation of CIDOC CRM, and extend it with selected domain-specific concepts.

The result forms the basis for the subsequent implementation of the ontology structure and semantic paths in the WissKI Pathbuilder.


> **What is the module about?**
>
> In Module 1, you developed a **conceptual model** by identifying concepts, events, and relationships and relating them to CIDOC CRM.
>
> In Module 2, you will transform this model into a **formal, machine-readable ontology structure** using **CIDOC CRM and Protégé**.
>
> Therefore you use **CIDOC CRM scope notes** to evaluate modelling choices and implement selected domain-specific structures.
>
> The resulting **formalised domain model** provides the basis for visualisation and technical implementation in **WissKI** in Module 3.

---

## Guiding Question

Our guiding question is...

> **How does a conceptual model sketch become a domain-informed and machine-readable ontology structure based on CIDOC CRM?**

---

## Objectives of this Module

In this module, you will learn how to:

- apply a systematic **workflow for semantic modelling**,
- use **Protégé** to explore and edit an ontology,
- select suitable **CIDOC CRM classes and properties** based on their scope notes,
- add **domain-specific concepts** to an existing ontology structure, and
- prepare the resulting ontology for further implementation in **WissKI**.
  
---

## Structure of this Module

**Total duration of module 2: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| 0 | Welcome, objectives and structure | 10 min. |
| 1 | Methods and workflows of semantic modelling | 10 min. |
| E2A | Activation: Set up Protégé| 20 min. |
| 2 | Introduction to Protégé | 10 min. |
| E2E | Exercise: Semantic modelling with CIDOC CRM | 45 min. |
|  | **Total** | **90 min.** |

  
---

## Learning Objectives of this Module

After completing Module 2, participants can…

### E2A. Setting up the Working Environment with Protégé

- name software used for creating ontologies. (LZ-ID SODa\_03\_007\_0809)
- use software for creating ontologies. (LZ-ID SODa\_03\_007\_0840)
- analyse their own experience with software used for creating ontologies. (LZ-ID SODa\_03\_007\_0857)


### 1. Methods and Workflows of Semantic Modelling

- name methods for developing ontologies. (LO-ID 03\_007\_0784)
- explain methods for developing ontologies. (LO-ID SODa\_03\_007\_0839)
- name a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0626)
- explain a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0853)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

### 2. Introduction to Protégé

- name software for creating ontologies. (LO-ID SODa\_03\_007\_0809)
- explain software for creating ontologies. (LO-ID SODa\_03\_007\_0810)
- name Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0841)
- apply software for creating ontologies. (LO-ID SODa\_03\_007\_0840)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

### E2. Semantic Modelling with CIDOC CRM

- apply an ontology for describing resources. (LO-ID 03\_007\_0780)
- apply methods for developing ontologies. (LO-ID SODa\_03\_007\_0854)
- apply a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0627)
- apply methods for modelling a domain ontology using the CIDOC CRM reference model under guidance. (LO-ID SODa\_03\_001\_0786a) 
- apply software for creating ontologies. (LO-ID SODa_03_007_0840)
- apply Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa_03_007_0855)
- apply Scope Notes of the CIDOC CRM reference model for describing resources. (LO-ID SODa\_03\_007\_0780a)

---

## Learning Path through this Module

The diagram illustrates the learning path of the module.

**Conceptual Model Sketch from Module 1**
 
↓
   
**Define the methodological workflow**
   
↓

**Prepare your technical setup**
   
↓
   
**Explore CIDOC CRM in Protégé**
 
↓
 
**Select classes (entities) and properties (properties) using scope notes**
 
↓
 
**Add domain-specific subclasses**
 
↓
 
**Review and and document modelling decisions**

↓

**Save the ontology and prepare it for WissKI**


---

## Working Method and Example

The module combines methodological input, demonstration, and guided application:

- Participants learn basic methods and an iterative workflow for ontology development.
- The user interface and central areas of Protégé are introduced in a live or video demonstration.
- The current version of the OWL implementation **[Erlangen CRM](https://erlangen-crm.org/current-version)** (Schiemann2024crm) is loaded and explored through its classes, object properties, and datatype properties.
- The example object **“The Legend of Zelda: A Link to the Past”** and the model sketch developed in Module 1 once again serve as a common thread.
- Selected concepts are compared with CIDOC CRM using the Scope Notes.
- Domain-specific concepts such as game characteristic, platform type, genre type, or edition type are modelled as subclasses.
- Suitable relationships between the concepts and events are selected.
- Participants document their decisions and review the model step by step for comprehensibility and consistency.

The goal is not a complete domain ontology. What matters is a **small, comprehensible, and formally usable extension of CIDOC CRM** that prepares the transition to implementation in WissKI.

> **How you work**
>
> Short methodological inputs alternate with demonstrations and hands-on modelling activities.
>
> You will continue working with the example object **The Legend of Zelda: A Link to the Past** and the model sketch developed in Module 1.
>
> You use:
> 
> - **Protégé** and explore an **OWL implementation of CIDOC CRM** - the [Erlangen CRM](https://cidoc-crm.org/Version/version-7.1.3),
> - **scope notes** to evaluate and justify modelling choices, and
> - **extend the ontology with selected domain-specific concepts and relationships**.
>
> **The goal is not a complete domain ontology, but a small, transparent, and formally usable extension of CIDOC CRM.**

---

## Prerequisites

The content of Module 1 or comparable basic knowledge is assumed, such as having one's own semantic domain model based on CIDOC CRM. 

Participants should…

- be able to distinguish the terms domain, concept, event, and relationship,
- know the building blocks classes (Entities), properties (Properties), instances (Instances), and modelling assumptions (Assumptions),
- understand the basic principle of event-centered modelling with CIDOC CRM,
- know Scope Notes as a basis for modelling decisions,
- and have at least an initial conceptual model sketch, ideally a CIDOC CRM-based semantic domain model.

> **What do you need?**
>
> Module 2 builds on **Module 1 or equivalent prior knowledge**.
>
> You can therefore start with this module if you are already familiar with the basic concepts and have a conceptual model sketch to work with.
>
> You should be familiar with **concepts, events, relationships, classes, properties, instances, modelling assumptions, CIDOC CRM, and scope notes**.
>
> For the practical activities, you will need:
>
> - a **conceptual model sketch** from Module 1 or your own modelling context,
> - access to **Protégé Desktop or WebProtégé,** and
> - the **OWL implementation of CIDOC CRM (Erlangen CRM)** used in this tutorial.

---
 
## Result and Outcome of this Module

At the end of Module 2, an initial formally implemented domain ontology or ontology extension is available. 

> **What will you take away?**
>
> By the end of the module, you will have created a first **formal domain ontology** or **ontology extension** that includes:
>
> - selected and justified CIDOC CRM classes and properties,
> - domain-specific subclasses,
> - semantic relationships and datatype properties, and
> - documented modelling decisions based on scope notes.
>
> The ontology is saved as an OWL file and provides the basis for subsequent implementation in WissKI.

---

## Outlook

> **Next:**
>
> You learn how **different modelling approaches and workflows** guide the development of a domain ontology.

---

## Editorial Notes

- The schedule is designed for a total of 90 minutes and can be adjusted depending on the scope of the practical exercise.
