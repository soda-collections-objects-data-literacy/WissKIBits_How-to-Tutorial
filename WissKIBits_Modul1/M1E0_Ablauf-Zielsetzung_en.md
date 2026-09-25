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

module: From the collection through modeling decisions to the diagram – understand and explain

unit: Welcome, objectives and structure

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->


# WissKI Bits: Ontology-Based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 1: **From the collection through modeling decisions to the diagram – understand and explain**

Unit 0: **Welcome, objectives and structure**  

**Duration:** ~ 5 min.


---

## Welcome to WissKI Bits: Ontology-Based Modeling of Research Data

In this module, we use a concrete collection object to explore how research data can be transformed step by step into a semantic data model. The resulting conceptual model provides the basis for later implementation in WissKI.

In Module 1, **“From the collection through modeling decisions to the diagram – understand and explain”**, we develop the conceptual foundation of this data model. To do so, we analyse object data and contextual information from a specialist domain. We identify relevant concepts, events, and relationships, clarify their meaning, and align them with classes (Entities) and properties (Properties) of the CIDOC CRM reference model.

The goal is to document the domain-specific logic in such a way that modeling decisions become transparent and research data can later be recorded, linked, analyzed, and reused consistently.

The module is designed as a **learning-by-doing tutorial** for the **Scientific Communication Infrastructure WissKI**. Using an example from the domain of computer games, we move from the collection perspective to the modeling perspective. The resulting conceptual model forms the basis for a diagram and for later technical implementation in the WissKI Pathbuilder.

Subsequent units transfer this approach to learners’ own research data and deepen both formal modeling and implementation in WissKI.


> **What is the module about?**
>
> We start with **information about an object** and gradually *develop a semantic data model*.
>
> Along the way, we identify **concepts, events, and relationships** from a domain, make their meaning explicit, and prepare them for later implementation in WissKI.

---

## Why we Model Semantically?

- Research and collection data are complex object and contextual data. They describe not only objects and their properties. They arise in the context of scholarly research and are connected with historical, cultural, and social meanings and relationships.
- Tables represent individual properties and pieces of information, while the meaning and relationships of the data often remain implicit.
- To ensure that data remain interpretable and reusable in the long term, their meaning must be made explicit and formally described.

> Collection and research data consist of more than individual facts.
>
> Their meaning and relationships are equally important.
>
> **Semantic modeling makes these connections explicit, understandable, and reusable.**

---

## Guiding Question

Our guiding question through this module is:

> **How can information about an object be transformed into a transparent, interoperable semantic data model that can be implemented in WissKI?**

---

## Module Objectives

We will learn how to move from a collection perspective to a modeling perspective. 

We will:

- identify relevant **concepts, events, and relationships** in an example game collection,
- align them with **classes and properties of CIDOC CRM**,
- develop and justify a coherent domain logic, and
- visualise this logic as a **conceptual model** that can later be implemented as a **semantic data modell** in WissKI.

---

## Module Structure

**Total duration of Module 1: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| 0 | Welcome, objectives and structure | 5 min. |
| E1A | Activation: Collection object "Zelda" | 15 min. |
| 1 | Basic concepts of conceptual knowledge modeling | 10 min. |
| 2 | Fundamentals of ontologies | 10 min. |
| 3 | Introduction to CIDOC CRM | 15 min. |
| 4 | FAIR compliance with WissKI | 15 min. |
| E1E | Excersise: Conceptual structure and first CIDOC CRM draft| 20 min. |
|  | **Total** | **90 min.** |

---

## Learning Objectives of the Module

After completing Module 1, participants can…

### E1A. From....

- 
- apply the method of conceptual modelling to describe a research object. (LO-ID SODa_xx_xxx_xxxx)
  
### 1. Basic Concepts of Conceptual Knowledge Modeling
   
- name the term conceptual knowledge modeling. (LO-ID SODa\_03\_007\_0847)
- explain the term conceptual knowledge modeling. (LO-ID SODa\_03\_007\_0848)
- name the term domain. (LO-ID SODa\_03\_007\_0824)
- name the term concept. (LO-ID SODa\_03\_007\_0821)
- name the term event. (LO-ID SODa\_03\_007\_0822)
- name the term relationship. (LO-ID SODa\_03\_007\_0823)
- name the term semantic modeling. (LO-ID SODa\_03\_007\_0825)
- explain the term semantic modeling. (LO-ID SODa\_03\_007\_0844)
- name the term semantic data model. (LO-ID SODa\_03\_007\_0845)
- explain the term semantic data model. (LO-ID SODa\_03\_007\_0846)

### 2. Fundamentals of Ontologies
   
- name the term ontology. (LO-ID SODa\_03\_007\_0826)
- explain the term ontology. (LO-ID 03\_007\_0775)
- name aspects of ontologies. (LO-ID 03\_007\_0776)
- name the term classes (Classes/Concepts). (LO-ID SODa\_03\_007\_0829)
- explain the term classes (Classes/Concepts). (LO-ID SODa\_03\_007\_0830)
- name the term instances (Instances). (LO-ID SODa\_03\_007\_0833)
- explain the term instances (Instances). (LO-ID SODa\_03\_007\_0834)
- name the term properties (Properties). (LO-ID SODa\_03\_007\_0831)
- explain the term properties (Properties). (LO-ID SODa\_03\_007\_0832)
- name the term modeling assumptions (Constraints). (LO-ID SODa\_03\_007\_0835)
- explain the term modeling assumptions (Constraints). (LO-ID SODa\_03\_007\_0836)

### 3. Introduction to CIDOC CRM

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
 
### 4. FAIR Compliance with WissKI

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
- explain the event-centered modeling principle using CIDOC CRM with an example. (LO-ID SODa\_03\_007\_0850)
- name the Resource Description Framework (RDF) as a standard for describing resources. (LO-ID SODa\_03\_007\_0843)
- name the benefits of the Scientific Communication Infrastructure WissKI. (LO-ID SODa\_01\_010\_0204)

### E1E. Application Example for Object Collections

- apply the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0811)
- name datatype properties of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0808)
  
---

## Learning Path through the Module

We move step by step from a collection perspective to a semantic model.  

The following diagram illustrates the learning path of the module:

**Collection object and research question**  

↓  

**Concepts, events, and relationships**  

↓  

**Classes (Entities), properties, and modeling assumptions**  

↓  

**Alignment with CIDOC CRM**  

↓  

**Model sketch and justified decisions**  

↓  

**Preparation for implementation in WissKI**


---

## Working Method and Example

The module combines short inputs alternate with analysis, discussion, and modeling activities:

- Terms are introduced using typical information from collections.
- Modeling decisions are discussed and justified collaboratively.
- The example object **“The Legend of Zelda: A Link to the Past”** serves as a common thread.
- In the exercise, participants develop a small model sketch and align selected concepts with CIDOC CRM.
- The results are consolidated in the plenary session and transferred to participants’ own collection practices.

The goal is not a complete data model. What matters is a **small, consistent, and justifiable model draft** that can later be expanded and technically implemented.

> **How we work**
>
> We begin with a short activation excersise using a concrete collection object.
>
> After the conceptual inputs, we return to the same example and develop a small, consistent, and justified model sketch.
> 
> Our shared example is **The Legend of Zelda: A Link to the Past.**

---

## Prerequisites

**No prior knowledge of ontologies, RDF, OWL, CIDOC CRM, or WissKI** is required.

Experience with collection, object, or research data is helpful. 

---

## Result and Outcome of the Module

At the end of Module 1, we will have developed a first **conceptual model sketch** showing relevant **concepts and events, their relationships**, and **initial mappings to CIDOC CRM**.

> **What will you take away**
>
> By the end of the module we will have an **initial conceptual model sketch of the domain logic** that includes:
>
> - the concepts and events relevant to the example,
> - their semantic relationships,
> - initial mappings to classes (Entities) and properties (Properties) of CIDOC CRM,
> - as well as justified modeling decisions.
>
> This sketch serves as the starting point for further formalisation and implementation in WissKI.

---

## Outlook

The following unit first clarifies the basic concepts of conceptual knowledge modeling and presents them as a foundation for semantic data modeling. 
The module then progresses from ontologies and their building blocks through CIDOC CRM and FAIR to the conceptual model sketch of the domain logic. 
The technical implementation of the model using CIDOC CRM and the WissKI Pathbuilder is covered in the subsequent modules.

> In the next unit, we begin with the basic concepts of conceptual knowledge modeling and establish the vocabulary needed for the modeling process.

---

## Editorial Notes

- The schedule is designed for a total of 90 minutes and can be adjusted depending on group size.


