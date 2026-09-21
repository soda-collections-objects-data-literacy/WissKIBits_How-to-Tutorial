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

unit: Application Example: Object Collections

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->

# WissKI Bits: Ontology-Based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 1: **From the collection through modeling decisions to the diagram – understand and explain**

Exercise Unit E1: **Application Example: Object Collections**  

**Duration:** ~ 30 min.

**Learning objectives:**

Participants can...

- apply the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0811)
- name datatype properties of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0808) 

---

## Objective and scenario

This is a practical unit. Starting from an example object from the **computer games** domain, an initial conceptual model sketch is developed.

Using **“The Legend of Zelda: A Link to the Past”** as an example, we examine which information is relevant for describing a collection object by

- identifying central **concepts and events**
- and formulating the **relationships** that exist between them.

Selected concepts are then provisionally mapped to classes of **CIDOC CRM**. The aim is not yet to create a complete or formally correct CIDOC CRM model. Rather, the goal is to demonstrate that transferring domain knowledge into a reference model requires **modeling decisions**.

At the end, participants can:

* identify central **concepts** and **events** in an example domain,
* formulate **semantic relationships** between them,
* map selected concepts to possible **CIDOC CRM classes (Entities)**,
* describe the mappings as modeling decisions,
* design a **conceptual model** that serves as the starting point for further formalization.

The model sketch will be developed further step by step in Modules 2 and 3 and formalized for working with **Protégé** and **WissKI**.

---

## Starting point: Example object “Zelda”

The computer game **“The Legend of Zelda: A Link to the Past”** serves as the starting point. 

Using this example, we examine which **concepts, events, and relationships** may be relevant for describing a collection object and its context.

The **goal is not** to develop a complete data model for computer games. Instead, an **initial model sketch** is created that

- distinguishes central concepts and events in a way that is understandable to people,
- makes their relationships visible, and
- serves as the basis for subsequent mapping to **CIDOC CRM**.

---

## Why computer games?

Computer games are well suited as an example domain because they illustrate different aspects of modeling clearly.

The domain is particularly suitable because it...

- includes both **physical** and **digital** objects,
- has clearly traceable **production and publication contexts**,
- contains typical **events** (e.g. release, porting, reissue),
- allows **versions/editions** and **series memberships** to be represented,
- uses clear identifiers and names (title variants, product codes).

This makes the domain a clear starting point for recognizing different perspectives on an object and deriving initial **modeling decisions** from them.

---

## Focus of this modeling exercise

For the model sketch, we consider selected information about the example object. We focus on three areas:

- **Game title** 
- **Game characteristics** (e.g. genre, such as action-adventure, RPG, or platform, such as Nintendo 64, PlayStation, PC)
- **Narrative elements** (e.g. description, perspective, such as first-person, third-person, or characters such as Zelda)

These areas serve as the starting point for recognizing different types of **concepts and events** and formulating their **relationships**.

For example, the following questions can be asked:

- What **title** does the game have?
- Which **genre** or **platform** is it assigned to?
- Which **persons or organizations** were involved?
- Which **events** are relevant to the game?
- At which **places** and at what **times** did these events take place?

---

## Exercise – Model sketch and initial orientation with CIDOC CRM

**Working format:** Breakout rooms / individual work or teams (2–4 people)  

**Material:** Paper & pen (or digital whiteboard)  

**Time:** 20 minutes

### Task 1: Design a mini mind map as a model sketch

Create a simple mind map for the example object “The Legend of Zelda: A Link to the Past”. 

The goal is to make central elements of the domain, their relationships, and the structure of the domain visible.

Proceed in two steps:

- **Step 1:** Identify 3–5 central concepts and events from the example, e.g. an object, a person or organization, a place, a time specification, or an event.  
Not all categories need to be included.

- **Step 2:** Connect the identified elements using meaningful relationships, e.g. “has”, “was produced through”, “was published by”. Formulate the relationships so that they result in an understandable statement.

**Example:**

> Game → has → Title
>
> Nintendo → participated in → Development
>
> Development → created → Game

**Note:**

> Less is more. Initially, focus on a small number of elements and relationships that are particularly relevant for understanding the example object.

**Guiding questions may include**

| Step | Guiding question | Result |
|-------|------------------|--------|
| 1 | Which central concepts and events are there? | Nodes of the model sketch |
| 2 | How are the things related? | Directed relationships between the nodes |
| 3 | Can the connections be read as understandable statements? | Verifiable statements about the object |

**Discussion of results in the plenary session and sample example**

![Concept mind map](../WissKIBits_Modul1/assets/mindmap.png)

> **Figure:** The figure shows a sample example of the step-by-step conceptual analysis of a collection or research object using the game “The Legend of Zelda: A Link to the Past” as an example. Original illustration created with ChatGPT (OpenAI), 2026.


## Outlook

In this practical unit, an **initial model sketch for the computer games domain** was first developed. This model was then mapped to the corresponding **classes and properties of CIDOC CRM**, with particular attention to the characteristics of **class E41 Appellation**. 

The result is a **formalized semantic model of the computer games domain based on CIDOC CRM** (see sample solution).

In **Module 2**, the developed model will be implemented with **Protégé** as a machine-readable **OWL ontology** and prepared for later implementation in **WissKI**. This establishes the foundations for practical work with Protégé and for transferring the semantic model into a technical implementation.

In **Module 3**, it will finally be shown how the previously developed model is implemented in WissKI. The focus is on transferring the model into the **path structure of the WissKI Pathbuilder**.

---

## Bibliography

[SIG2024cidoc] CIDOC CRM Special Interest Group. (2024). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. https://cidoc-crm.org/Version/version-7.1.3

[SIG2024cidocb] CIDOC CRM Special Interest Group. (2024). Classes & Properties Declarations of CIDOC-CRM version: 7.1.3. https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html

