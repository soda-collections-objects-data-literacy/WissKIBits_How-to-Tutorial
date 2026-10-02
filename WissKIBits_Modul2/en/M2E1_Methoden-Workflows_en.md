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

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of reseach data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->

# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 2: **Modelling with CIDOC CRM – understand and apply**

Unit 1: **Methods and workflows of semantic modelling**  

**Duration:** ~ 10 min.

**Learning objectives:**

Participants can...

- name methods for developing ontologies. (LO-ID 03\_007\_0784)
- explain methods for developing ontologies. (LO-ID SODa\_03\_007\_0839)
- name a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0626)
- explain a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0853)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

---

## Methods and Workflows of Semantic Modelling

The development of a domain ontology typically follows a methodological, multi-stage, and iterative approach. 

This includes, among other things, identifying central terms and definitions (so-called “ontology capture”) (Uschold1995method, p. 3), structuring concepts into classes and properties/relations, and continuously reviewing and revising the domain model with regard to consistency and usability. (Gruber1993knowledge)

Practical ontology development is often understood as a process that integrates both domain knowledge and application requirements and gradually transforms them into a formally usable knowledge structure.

> **Semantic modelling is...**
>
> - a not a linear process of developing a domain ontology.
>
> - is usually the combination of domain knowledge, application requirements, modelling decisions, and iterative review.
>
> - based on different methods depending on the starting point and purpose of the model.

---

## Four Approaches to Ontology Development

Ontologies are often developed using a combination of different modelling approaches (Noy2001ontology, pp. 4 ff.):

- **Bottom-up modelling:** Classes (Entities) and properties (Properties) are gradually identified and derived from existing data or example objects.
- **Top-down modelling:** A reference model, such as CIDOC CRM, provides the starting point for developing a domain-specific specialisation.
- **Competency Questions:** Typical analytical and research questions are formulated to guide the modelling process, for example: *“Which games have characteristic X?”*
- **Iterative prototyping:** The model is developed, reviewed, and progressively refined with regard to consistency, extensibility, and its ability to support relevant queries.


### The Practical Modelling Workflow

In this module, you follow a systematic workflow to transform the conceptual model into a formal ontology structure:

**Start with CIDOC CRM as the reference model**

↓

**Use research questions to guide the modelling**

↓

**Identify suitable CIDOC CRM classes and properties**

↓

**Reuse or specialise them for the domain**

↓

**Review the model against the research questions**

↓

**Revise and refine the model**

↓

↺ **Repeat where necessary**


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
> We follow a **lightweight extension strategy**:
>
> - create **domain-specific subclasses** for concepts that need to be represented explicitly in the domain model;
> - reuse existing **CIDOC CRM properties** wherever their meaning adequately represents the intended relationship.
>
> This keeps the domain model close to the CIDOC CRM structure, reduces unnecessary complexity, and supports interoperability while making domain-specific concepts explicit.
>
> **Example**
>
> - **Domain concept:** *Game Genre* → create a domain-specific subclass of an appropriate CIDOC CRM class.
> - **Relationship:** *has type* → reuse an appropriate CIDOC CRM property, such as **P2 has type**, rather than creating a more specific property such as *is designed according to*, provided that the meaning of P2 adequately represents the intended relationship.
>
> **Why this strategy?**
>
> By adding domain-specific subclasses while reusing established CIDOC CRM properties, you can **specialise the model without creating a separate seamntic relationship structure**.
>
> Domain-specific concepts remain explicit, while their relationships retain the established semantics of CIDOC CRM.
>
> This keeps the extension **small, transparent, and easier to maintain and implement**.

---

## Outlook

The **methods and workflows of semantic modelling** presented here, together with the **modelling strategy** explained in the tutorial, form the basis for putting the concepts and models developed so far into practice. 

In the following unit, **Protégé** is introduced as an editor for modelling ontologies. Using a concrete example, it is shown how a **machine-readable domain ontology** can be developed and formally described in Protégé on the basis of CIDOC CRM and made accessible for machine processing.

> **Next:**
>
> In the following unit, you will set up your working environment with Protégé.

---

## Bibliography

[Gruber1993knowledge] Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

[Noy2001ontology] Noy, N. F., & McGuinness, D. L. (2001). Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory.

[Uschold1995method] Uschold, M., & King, M. (1995). Towards an Methodology for Building Ontologies. Presented at Workshop on Basic Ontological Issues in Knowledge Sharing held in conjunction with IJCAI. The University of Edinburgh.

