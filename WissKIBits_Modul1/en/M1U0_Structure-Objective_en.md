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

module: From collection to modelling decisions to diagram – understand and explain

unit: Welcome, objectives and structure

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: SODa How-to Tutorial

-->


# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 1 (M1): **From Collection to Modelling Decisions to Diagram – Understand and Explain**

Unit 0 (U0): **Welcome, Structure and Objectives**  

**Duration:** ~ 5 min.


---

## Welcome to WissKI Bits: Ontology-Based Modelling of Research Data

In Module 1, you explore how  information about a collection object can be tranformed into a **conceptual model**. 

Using an example from a **computer games collection**, you move from the collection perspective to the modelling perspective. 

You then relate selected elements of your conceptual model to **CIDOC CRM**.

The resulting conceptual model provides the basis for further **formalisation** in module 2 and later **technical implementation in WissKI** in module 3.


> **What is the Module About?**
>
> Starting from **information about a collection object**, you identify relevant **concepts, events, and relationships** and organise them into a **conceptual model sketch of the domain**..
>
> You then explore how selected elements can be represented using **CIDOC CRM** and make initial modelling decisions.
>
> The resulting model sketch serves as the starting point for further formalisation in Module 2.

---

## Why Do We Model Semantically?

- Research and collection data are complex object and contextual data. They describe not only objects and their properties. They arise in the context of scholarly research and are connected with historical, cultural, and social meanings and relationships.
- Tables represent individual properties and pieces of information, while the meaning and relationships of the data often remain implicit.
- To ensure that data remain interpretable and reusable in the long term, their meaning must be made explicit and formally described.

> Collection and research data consist of more than individual facts.
>
> Their meaning and relationships are equally important.
>
> **Semantic Modelling Makes these Connections Explicit, Understandable, and Reusable.**

---

## Guiding Question

Our guiding question through this module is:

> **How can information about an object be transformed into a transparent, interoperable semantic data model that can be implemented in WissKI?**

---

## Module Objectives

In this module, you learn how to move from information about a collection object towards a conceptual model of its domain.

By the end of the module, you will be able to:

- identify relevant **concepts, events, and relationships** in an game collection example,
- distinguish between domain-specific terms and the meanings they are intended to express, to develop and justify a coherent domain logic,
- explore how selected concepts can be represented using **CIDOC CRM classes and properties**,
- explain initial modelling decisions, and
- develop a **conceptual model sketch** that can be refined and formalised in Module 2.

---

## Module Structure

**Total Duration of Module 1: Approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| M1U0 | Welcome, objectives and structure | 5 min. |
| M1U0A | Activation: Collection object "Zelda" | 15 min. |
| M1U1 | Basic concepts of conceptual knowledge modelling | 10 min. |
| M1U2 | Fundamentals of ontologies | 10 min. |
| M1U3 | Introduction to CIDOC CRM | 15 min. |
| M1U4 | FAIR compliance with WissKI | 15 min. |
| M1UE | Exercise: Conceptual structure and first CIDOC CRM draft| 20 min. |
|  | **Total** | **90 min.** |

---

## Learning Objectives of the Module

After completing Module 1, participants can…

### UA0. Application Example from Object Collections

- apply the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa_03_007_0811)
- apply the method of conceptual knowledge modelling to describe a research object. (LO-ID SODa_03_007_0856)
  
### U1. Basic Concepts of Conceptual Knowledge Modelling
   
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

### U2. Fundamentals of Ontologies
   
- name the term ontology. (LO-ID SODa\_03\_007\_0826)
- explain the term ontology. (LO-ID 03\_007\_0775)
- name aspects of ontologies. (LO-ID 03\_007\_0776)
- name the term classes (Classes/Concepts). (LO-ID SODa\_03\_007\_0829)
- explain the term classes (Classes/Concepts). (LO-ID SODa\_03\_007\_0830)
- name the term instances (Instances). (LO-ID SODa\_03\_007\_0833)
- explain the term instances (Instances). (LO-ID SODa\_03\_007\_0834)
- name the term properties (Properties). (LO-ID SODa\_03\_007\_0831)
- explain the term properties (Properties). (LO-ID SODa\_03\_007\_0832)
- name the term modelling assumptions (Constraints). (LO-ID SODa\_03\_007\_0835)
- explain the term modelling assumptions (Constraints). (LO-ID SODa\_03\_007\_0836)

### U3. Introduction to CIDOC CRM

- name an ontology for describing resources. (LO-ID 03\_007\_0778)
- explain an ontology for describing resources. (LO-ID 03\_007\_0779)
- name the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0806)
- explain the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0807)
- name the term Scope Notes. (LO-ID SODa\_03\_007\_0837)
- explain the term Scope Notes. (LO-ID SODa\_03\_007\_0838)
- name the Resource Description Framework (RDF) as a standard for describing resources. (LO-ID SODa\_03\_007\_0843)
- name the term domain ontology. (LO-ID SODa\_03\_007\_0827)
- explain the term domain ontology. (LO-ID SODa\_03\_007\_0828)
- name the benefits of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0805)
 
### U4. FAIR Compliance with WissKI

- explain (inter)national IT infrastructures relevant to collection-related research data management (RDM). (LO-ID SODa\_01\_010\_0203)
- name suitable technologies that support the application of the FAIR principles. (LO-ID 01\_007\_0121)
- name the FAIR principles. (LO-ID 01\_007\_0117)
- name the 5-star model for open data. (LO-ID SODa\_01\_008\_0172)
- name the W3C Web Ontology Language (OWL) as a formal description language. (LO-ID SODa\_03\_007\_0842)
- name Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0841)
- name the specific functions and application areas of the Scientific Communication Infrastructure WissKI. (LO-ID SODa\_01\_010\_0191a)
- explain the specific functions and application areas of the Scientific Communication Infrastructure WissKI. (LO-ID SODa\_01\_010\_0192a)
- name the capabilities and efficiency of IT infrastructures for collection-related research data management (RDM) using the Scientific Communication Infrastructure WissKI. (LO-ID SODa\_01\_010\_0202)
- name the WissKI Pathbuilder as a tool for defining an ontology structure. (LO-ID SODa\_03\_007\_0803)
- explain the WissKI Pathbuilder as a tool for defining an ontology structure. (LO-ID SODa\_03\_007\_0849)
- explain the event-centered modelling principle using CIDOC CRM with an example. (LO-ID SODa\_03\_007\_0850)
- name the Resource Description Framework (RDF) as a standard for describing resources. (LO-ID SODa\_03\_007\_0843)
- name the benefits of the Scientific Communication Infrastructure WissKI. (LO-ID SODa\_01\_010\_0204)

### UE. Application Example for Object Collections

- apply the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0811)
- name datatype properties of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0808)
  
---

## Learning Path Through the Module

The module follows a step-by-step approach, starting with a concrete collection object and gradually introducing semantic modelling concepts.

**Explore the collection object (M1U0A):** 
Identify relevant information and create an initial model sketch.

↓  

**Explore the collection object (M1U0A):** 
Identify relevant information and create an initial model sketch. Understand conceptual modelling (M1U1): Learn how concepts, events, and relationships can be used to organise domain knowledge.

↓  

**Explore ontologies (M1U2):** 
Become familiar with the basic elements of ontologies and their role in semantic modelling.

↓  

**Discover CIDOC CRM (M1U3):** 
Learn how a reference ontology can support the description of cultural heritage information.

↓  

**Apply CIDOC CRM (M1UE):** 
Revisit your model sketch, examine possible CIDOC CRM mappings, and justify selected modelling decisions. 

Your result: A conceptual model sketch with initial, documented CIDOC CRM mappings that can be refined in Module 2.

---

## Working Method and Example

The module combines short inputs alternate with analysis, discussion, and modelling activities:

- Terms are introduced using typical information from collections.
- Modelling decisions are discussed and justified collaboratively.
- The example object **“The Legend of Zelda: A Link to the Past”** serves as a common thread.
- In the exercise, participants develop a small model sketch and align selected concepts with CIDOC CRM.
- The results are consolidated in the plenary session and transferred to participants’ own collection practices.

The goal is not a complete data model. What matters is a **small, consistent, and justifiable model draft** that can later be expanded and technically implemented.

> **How we Work**
>
> We begin with a short activation excersise using a concrete collection object.
>
> After the conceptual inputs, we return to the same example and develop a small, consistent, and justified model sketch.
> 
> Our shared example is **The Legend of Zelda: A Link to the Past.**

---

## Prerequisites

**No prior Knowledge of Ontologies, RDF, OWL, CIDOC CRM, or WissKI** is required.

Experience with collection, object, or research data is helpful. 

---

## Result and Outcome of the Module

At the end of Module 1, you will have developed a first **conceptual model sketch** showing relevant **concepts and events, their relationships**, and **initial mappings to CIDOC CRM**.

> **What will you take away**
>
> By the end of the module you will have an **initial conceptual model sketch of the domain logic** (Computer Games) that includes:
>
> - the concepts and events relevant to the example,
> - their semantic relationships,
> - initial mappings to classes (Entities) and properties (Properties) of CIDOC CRM,
> - as well as justified modelling decisions.
>
> This sketch serves as the starting point for further formalisation and implementation in WissKI.

---

## Outlook

The following unit first clarifies the basic concepts of conceptual knowledge modelling and presents them as a foundation for semantic data modeling. 
The module then progresses from ontologies and their building blocks through CIDOC CRM and FAIR to the conceptual model sketch of the domain logic. 
The technical implementation of the model using CIDOC CRM and the WissKI Pathbuilder is covered in the subsequent modules.

> **Next:**
>
> You now know what you will develop in this module.
>
> Next, you will start with a concrete collection object and create a first **conceptual model sketch** by identifying relevant concepts, events, and relationships.

---

## Editorial Notes

- The schedule is designed for a total of 90 minutes and can be adjusted depending on group size.


