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

unit: Fundamentals of Ontologies

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->


# WissKI Bits: Ontology-Based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 1: **From the collection through modeling decisions to the diagram – understand and explain**

Unit 2: **Fundamentals of Ontologies**  

**Duration:**  ~ 10 min.

**Learning objectives:**

Participants can...

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

---

## Fundamentals of Ontologies

**Conceptual knowledge modeling** (M1E1) provides an important foundation for the structured description of knowledge within a domain. In this process, central concepts and terms, properties, and relationships are identified within a subject-specific context. **Ontologies** help to express these conceptual structures formally (Rehbein2017ontologies, p. 164) and represent them in a machine-readable form.

This unit explains **why ontologies are used and what benefits they offer for collection documentation.** To this end, the most important **terms** and **building blocks of ontologies** are defined and explained, as is their **function** in the structured and semantic description of collection information.

---

## Why do we use ontologies?

When modeling research data from the humanities and cultural studies, the aim is to describe and document relevant knowledge within a domain in a standardized way, make it available and shareable, and ensure that it remains technically and semantically usable over the long term.

Ontologies help to:

- **formally capture the semantics of data**
- **formally express semantic relationships**
- **make knowledge machine-readable**
- **ensure interoperability between institutions and systems**
- **connect data to the Linked Open Data ecosystem**

---

## Definitions

### Basic concepts of ontologies

**Ontology**

An ontology is a **formal description of a part of the world**, or a **“formal, schematic representation of a domain of knowledge, consisting of a vocabulary and rules for its composition.”** (Weller2013ontologies, p. 207)

The best-known definition describes an ontology as an explicit, formal specification of a conceptualization; that is, it provides a structured description of which concepts are relevant in a particular subject area or domain and which relationships exist between them. (Gruber1993knowledge, p. 200)

**An ontology specifies...**

- which **concepts** and **events** are relevant in a subject or application area (domain),
- how these concepts are **related** to one another,
- and which **rules** apply so that **statements** about them can be modeled meaningfully and consistently.

**For this purpose, an ontology provides the following building blocks (aspects of ontologies):**

- **Classes (Classes/Concepts):** formal representation of concepts and events
- **Properties:** formal representation of characteristics or relationships
- **Instances:** concrete individuals of classes
- **Constraints:** rules for ensuring the logical consistency of the ontology

---

### Aspects of ontologies

Ontologies typically consist of the following building blocks:

**Classes (Classes/Concepts)**  

“Classes (Classes/Concepts) represent general terms, i.e. concepts within a domain of interest that are intended to group real-world objects according to shared properties. They are usually organized in a basic hierarchical structure.” (Weller2013ontologies, p. 208)

> Example:
>
> Game, Person, Organization

**Instances**    

“Instances represent individual terms, i.e. concrete representatives of the individual classes.” (Weller2013ontologies, p. 208)

> Example:
>
> The game "The Legend of Zelda: A Link to the Past"

**Properties**  

Classes (Classes/Concepts) and instances can be further specified in their meaning using properties.
Properties model class characteristics through semantic relations. There are two basic ways to implement this:

- A property establishes a relationship between two classes (Classes/Concepts)
- A property describes a single class (Class/Concept) without connecting it to other classes (Classes/Concepts). (Weller2013ontologies, p. 208)

> Example:
>
> The game has the title "The Legend of Zelda: A Link to the Past"

**Constraints**  

“For attributes and relations, an ontology can define **constraints** that specify their use in greater detail and are intended to ensure that the ontology is logically consistent in itself.” (Rehbein2017ontologies, p. 164)

> Example:
>
> Which relationships are permitted to describe the object? (find a better example)

---

## Benefits of ontologies

Ontologies are a form of knowledge representation with a high level of abstraction. They have **“a degree of formalization based on mathematical logic (...) through which information can be captured precisely in its semantic context and processed by machines”** (emphasis by the author). Ontologies are therefore particularly relevant for integrating heterogeneous data sources, exchanging and reusing knowledge elements, and enabling logical inference. (Rehbein2017ontologies, p. 162)

The particular benefit of ontologies lies in their ability to describe concepts and terms, properties and relationships, and their meaning within a domain of knowledge **formally and unambiguously**. This makes it possible to relate and jointly analyze data across individual collections, projects, or systems. The formal description also enables machine processing of the data. 

Ontologies therefore provide a foundation for not only documenting complex research and collection data, but also for representing the domain knowledge contained within them in a structured way and making it usable for further research.

---

## Outlook

Ontologies provide the foundation for modeling knowledge about collection objects in a structured and semantic way. But how can this be applied specifically to information about cultural heritage?

In the next unit, we will introduce the CIDOC Conceptual Reference Model (CIDOC CRM), an ontology developed specifically as a reference for modeling cultural heritage information.

---

## Bibliography

[Gruber1993knowledge] Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

[Rehbein2017ontologies] Rehbein, M. (2017). Ontologien. In: F. Jannidis, H. Kohle, & M. Rehbein (Hrsg.), *Digital Humanities* (S. 162-176). J.B. Metzler, Stuttgart. https://doi.org/10.1007/978-3-476-05446-3_11.

[Weller2013ontologies] Weller, K. (2013). B 6 Ontologien. In: R. Kuhlen, W. Semar, & D. Strauch (Hrsg.), *Grundlagen der praktischen Information und Dokumentationen* (S. 207-218). De Gruyter Saur.

---

