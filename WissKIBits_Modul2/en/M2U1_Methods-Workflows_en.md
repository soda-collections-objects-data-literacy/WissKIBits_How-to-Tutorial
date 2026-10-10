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

unit: Methods and workflows of semantic modelling

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 2 (M2): **Modelling with CIDOC CRM – Understand and Apply**

Unit 1 (U1): **Methods and Workflows of Semantic Modelling**  

**Duration:** ~ 10 min.

**Learning Objectives:**

Participants will be able to...

- name methods for developing ontologies. (LO-ID 03\_007\_0784)
- explain methods for developing ontologies. (LO-ID SODa\_03\_007\_0839)
- name a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0626)
- explain a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0853)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

---

## Methods and Workflows of Semantic Modelling

Developing a domain ontology typically follows a methodological, multi-stage, and iterative approach and involves more than translating domain terms into ontology classes. 

This includes, among other things, identifying central terms and definitions (so-called “ontology capture”) (Uschold1995method, p. 3), structuring concepts into classes and properties/relations, and continuously reviewing and revising the domain model with regard to consistency and usability. (Gruber, 1993)

In Module 1, you created a conceptual model sketch and explored possible CIDOC CRM mappings. These initial decisions now need to be reviewed, refined, and represented more formally.

Practical ontology development is often understood as a process that integrates both domain knowledge and application requirements and gradually transforms them into a formally usable knowledge structure.

> **Semantic modelling is an iterative process**
>
> - Semantic modelling combines **domain knowledge, application requirements, ontology definitions, and explicit modelling decisions**.
>
> - A model is developed and refined through repeated steps of analysis, implementation, and review rather than in a strictly linear sequence.
>
> - The aim is not simply to create classes and properties, but to represent the intended meaning consistently and transparently.

---

## Approaches and Methods for Ontology Development

Ontologies are often developed using a combination of different modelling approaches (Noy2001ontology, pp. 4 ff.):

**Bottom-up modelling:** 

Start with existing data, examples, and domain terminology. Identify relevant concepts and relationships and gradually organise them into a model. Classes (Entities) and properties (Properties) are gradually identified and derived from existing data or example objects. 

**Top-down modelling:** Start with an established ontology or conceptual framework. Examine how its classes and properties can represent the intended domain knowledge. A reference model, such as CIDOC CRM, provides the starting point for developing a domain-specific specialisation.

**Competency Questions:** Formulate questions that the resulting model should help to answer. These questions clarify the intended scope and requirements of the ontology. Typical analytical and research questions are formulated to guide the modelling process, for example: *“Which games have characteristic X?”*

- **Iterative prototyping:** A small part of the model is developed, reviewed, and progressively refined with regard to consistency, extensibility, and its ability to support relevant queries.

These approaches serve different purposes and are not mutually exclusive.

**In this tutorial, you combine a bottom-up analysis of the computer game example with a top-down alignment to CIDOC CRM. We refine selected modelling decisions iteratively while implementing them in Protégé.**


### The Practical Modelling Workflow

The following workflow guides the practical exercise in this module:

**Review the conceptual model:** Select relevant concepts and relationships from your model sketch. 

↓

**Clarify their meaning:** Define what each selected element represents in the domain.

↓

**Examine CIDOC CRM:** Identify suitable classes and properties and consult their scope notes.

↓

**Make modelling decisions:** Decide which existing ontology elements can be reused and whether extensions are necessary.

↓

**Implement the model:** Represent selected decisions in Protégé.

↓

**Review and document:** Check the resulting structure, record your reasoning, and revise the model where needed.

The workflow is iterative. If a proposed class or relationship does not adequately express the intended meaning, return to the relevant earlier step and reconsider your decision.

---

## Modelling Strategy

When developing a domain ontology based on an existing reference ontology, you need to decide **which existing ontology elements can be reused and where domain-specific extensions are needed**.

Possible strategies include:

- **reusing** existing CIDOC CRM classes (Entities) and properties (Properties),
- creating domain-specific **subclasses (Entities)**,
- defining new domain-specific **properties (Properties)**, or
- using a **combination** of these approaches.

> **Our strategy in this tutorial**
>
> In this tutorial, you follow a **lightweight extension strategy** based on CIDOC CRM.
>
> - **Reuse existing CIDOC CRM classes and properties** wherever possible.
> - **Create domain-specific subclasses** to represent concepts from the computer games domain that require further specialisation.
> - **Do not introduce new properties.** Relationships are modelled using existing CIDOC CRM properties.
> - **Check the scope notes** to ensure that new subclasses are placed under appropriate CIDOC CRM classes.
> - **Document modelling decisions** to make the resulting ontology understandable and reusable.
>
> **Example**
>
> - **Domain concept:** *Game Genre* → create a domain-specific subclass of an appropriate CIDOC CRM class.
> - **Relationship:** *has type* → reuse an appropriate CIDOC CRM property, such as **P2 has type**, rather than creating a more specific property such as *is designed according to*, provided that the meaning of P2 adequately represents the intended relationship.
>
> **The guiding principle: Extend CIDOC CRM through subclasses while preserving its existing property structure.**
> 
> This deliberately restricted approach keeps the practical exercise manageable and allows us to focus on class hierarchies, semantic meaning, and the reuse of an established reference ontology.

---

## Outlook

The **methods and workflows of semantic modelling** presented here, together with the **modelling strategy** explained in the tutorial, form the basis for putting the concepts and models developed so far into practice. 

In the following unit, **Protégé** is introduced as an editor for modelling ontologies. Using a concrete example, it is shown how a **machine-readable domain ontology** can be developed and formally described in Protégé on the basis of CIDOC CRM and made accessible for machine processing.

> **Next:**
>
> In the following unit, you will set up your working environment with Protégé.

---

## Bibliography

(Gruber, 1993) Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

[Noy2001ontology] Noy, N. F., & McGuinness, D. L. (2001). Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory.

[Uschold1995method] Uschold, M., & King, M. (1995). Towards an Methodology for Building Ontologies. Presented at Workshop on Basic Ontological Issues in Knowledge Sharing held in conjunction with IJCAI. The University of Edinburgh.

