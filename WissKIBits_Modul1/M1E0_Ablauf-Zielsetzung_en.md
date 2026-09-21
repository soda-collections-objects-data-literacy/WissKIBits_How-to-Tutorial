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

## Welcome

Welcome to **WissKI Bits: Ontology-Based Modeling of Research Data**.

In this module, we use a concrete collection object to explore how research data can be transformed step by step into a semantic data model. The resulting conceptual model provides the basis for later implementation in WissKI.

In Module 1, **“From the collection through modeling decisions to the diagram – understand and explain”**, we develop the conceptual foundation of this data model. To do so, we analyze object data and contextual information from a specialist domain. We identify relevant concepts, events, and relationships, clarify their meaning, and align them with classes (Entities) and properties (Properties) of the CIDOC CRM reference model.

The goal is to document the domain-specific logic in such a way that modeling decisions become transparent and research data can later be recorded, linked, analyzed, and reused consistently.

The module is designed as a **learning-by-doing tutorial** for the **Scientific Communication Infrastructure WissKI**. Using an example from the domain of computer games, we move from the collection perspective to the modeling perspective. The resulting conceptual model forms the basis for a diagram and for later technical implementation in the WissKI Pathbuilder.

Subsequent units transfer this approach to learners’ own research data and deepen both formal modeling and implementation in WissKI.


> **We start with information about an object and gradually develop a semantic data model. Along the way, we identify concepts, events, and relationships, make their meaning explicit, and prepare them for later implementation in WissKI.**

---

## Why model semantically?

- Research and collection data are complex object and contextual data. They describe not only objects and their properties. They arise in the context of scholarly research and are connected with historical, cultural, and social meanings and relationships.
- Tables represent individual properties and pieces of information, while the meaning and relationships of the data often remain implicit.
- To ensure that data remain interpretable and reusable in the long term, their meaning must be made explicit and formally described.

> **Collection and research data consist of more than individual facts. Their **meaning and relationships** are equally important. Semantic modeling makes these connections explicit, understandable, and reusable.**
---

## Module objectives

In this module, you will learn how to move from a collection perspective to a modeling perspective. 

You will:

- identify relevant concepts, events, and relationships in collection and research data,
- align them with classes and properties of CIDOC CRM,
- develop and justify a coherent domain logic, and
- visualize this logic as a conceptual model that can later be implemented in WissKI.

---

## Guiding question

> **How can information about an object be transformed into a transparent, interoperable semantic data model that can be implemented in WissKI?**

This guiding question accompanies all units of the module. Three levels are distinguished:

| Level | Guiding question | Result |
|---|---|---|
| Collection perspective | Which information and research questions are relevant? | domain-specific requirements |
| Modeling perspective | Which concepts, events, and relationships express their meaning? | conceptual domain model |
| Implementation perspective | How are these structures formally represented using CIDOC CRM and WissKI? | basis for diagram and Pathbuilder |

---

## Module structure

**Total duration of Module 1: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| 0 | Welcome, objectives and structure | 5 min. |
| E1A| Activation: “Zelda” model sketch | 15 min. |
| 1 | Basic concepts of conceptual knowledge modeling | x min. |
| 2 | Fundamentals of ontologies | x min. |
| 3 | Introduction to CIDOC CRM | x min. |
| 4 | FAIR compliance with WissKI | x min. |
| E1 | Excersise: From model sketch to research questions (?) | 30 min. |
|  | **Total** | **90 min.** |

---

## Learning objectives of the module

After completing Module 1, participants can…

### 1. Basic concepts of conceptual knowledge modeling
   
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

### 2. Fundamentals of ontologies
   
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
 
### 4. FAIR compliance with WissKI

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

### Ü1. Application example for object collections

- apply the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0811)
- name datatype properties of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0808)
  
---

## Learning path in the module

We move step by step from a collection perspective to a semantic model:

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



> **Figure:** The graphic illustrates the learning path of the module.

---

## Working method and example

The module combines short inputs alternate with analysis, discussion, and modeling activities:

- Terms are introduced using typical information from collections.
- Modeling decisions are discussed and justified collaboratively.
- The example object **“The Legend of Zelda: A Link to the Past”** serves as a common thread.
- In the exercise, participants develop a small model sketch and align selected concepts with CIDOC CRM.
- The results are consolidated in the plenary session and transferred to participants’ own collection practices.

The goal is not a complete data model. What matters is a **small, consistent, and justifiable model draft** that can later be expanded and technically implemented.

> We begin with a short activation activity using a concrete collection object. After the conceptual inputs, we return to the same example and develop a small, consistent, and justified model sketch.
> 
> Our shared example is The Legend of Zelda: A Link to the Past.

---

## Prerequisites

**No prior knowledge of ontologies, RDF, OWL, CIDOC CRM, or WissKI** is required.
Experience with collection, object, or research data is helpful. If possible, bring an example object or research question from your own field.

---

## Module outcome

At the end of Module 1, an initial conceptual model sketch of the domain logic is available. It shows:

- the concepts and events relevant to the example,
- their semantic relationships,
- initial mappings to classes (Entities) and properties (Properties) of CIDOC CRM,
- as well as justified modeling decisions.

This sketch serves as the starting point for further formalization and implementation in WissKI.


> By the end of the module, you will have developed a first conceptual model sketch showing relevant concepts and events, their relationships, and initial mappings to CIDOC CRM.

---

## Outlook

The following unit first clarifies the basic concepts of conceptual knowledge modeling and presents them as a foundation for semantic data modeling. 
The module then progresses from ontologies and their building blocks through CIDOC CRM and FAIR to the conceptual model sketch of the domain logic. 
The technical implementation of the model using CIDOC CRM and the WissKI Pathbuilder is covered in the subsequent modules.

> In the next unit, we begin with the basic concepts of conceptual knowledge modeling and establish the vocabulary needed for the modeling process.

---

## Editorial notes

- The schedule is designed for a total of 90 minutes and can be adjusted depending on group size.


