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

unit: Methods and workflows of semantic modeling

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->

# WissKI Bits: Ontology-Based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 2: **Modeling with CIDOC CRM – understand and apply**

Unit 1: **Methods and workflows of semantic modeling**  

**Duration:** ~ 10 min.

**Learning objectives:**

Participants can...

- name methods for developing ontologies. (LO-ID 03\_007\_0784)
- explain methods for developing ontologies. (LO-ID SODa\_03\_007\_0839)
- name a workflow for semantic modeling as data documentation. (LO-ID SODa\_03\_001\_0626)
- explain a workflow for semantic modeling as data documentation. (LO-ID SODa\_03\_001\_0853)
- name methods for modeling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0784a)
- explain methods for modeling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

---

## Methods and Workflows of Semantic Modeling

The development of a domain ontology typically follows a methodological, multi-stage, and iterative approach. 

This includes, among other things, identifying central terms and definitions (so-called “ontology capture”) (Uschold1995method, p. 3), structuring concepts into classes and properties/relations, and continuously reviewing and revising the domain model with regard to consistency and usability. (Gruber1993knowledge)

Practical ontology development is often understood as a process that integrates both domain knowledge and application requirements and gradually transforms them into a formally usable knowledge structure.

> **Semantic modeling is...**
>
> - a not a linear process of developing a domain ontology.
>
> - is usually the combination of domain knowledge, application requirements, modeling decisions, and iterative review.
>
> - based on different methods depending on the starting point and purpose of the model.

---

## Four Approaches to Ontology Development

Ontologies are often developed using a combination of different modelling approaches (Noy2001ontology, pp. 4 ff.):

- **Bottom-up modelling:** Classes (Entities) and properties (Properties) are gradually identified and derived from existing data or example objects.
- **Top-down modelling:** A reference model, such as CIDOC CRM, provides the starting point for developing a domain-specific specialisation.
- **Competency Questions:** Typical analytical and research questions are formulated to guide the modelling process, for example: *“Which games have characteristic X?”*
- **Iterative prototyping:** The model is developed, reviewed, and progressively refined with regard to consistency, extensibility, and its ability to support relevant queries.


### The Practical Modeling Workflow Semantic Modeling 

Semantic modeling is iterative: reviewing the model and lead back to earlier steps. 

The diagram illustrates the workflow of semantic modeling.  

**Identify relevant concepts and relationships**
 
↓
  
**Structure them as classes and properties**
 
↓
 
**Reuse or specialise existing ontology elements**
 
↓
 
**Identify requirements and questions**
 
↓

**Review the model**
 
↓
  
**Revise and refine**

---

## Modeling Strategy 

We have to decide between class alignement or relationships.

A domain ontology can be developed by various approaches to extending domain ontologies:

- Create new **subclasses (Entities)**
- Define new **properties (Properties)**
- **Pure reuse** of existing CIDOC CRM classes (Entities) and properties (Properties)
- **Combinations** of the strategies mentioned above

> **Our strategy in this tutorial**
>
> We recommend a **lightweight extension strategy**.
>
> This consists of:
> 
> - **creating domain-specific subclasses (Entities) for the domain-specific concepts**
> - **reusing properties from CIDOC CRM as far as possible**
> 
> This ensures **interoperability and CIDOC compatibility**, reduces complexity, and still makes the domain-specific aspects explicit.  
>
> **Example**
> 
> - **Domain concept**: Game Genre (model as a domain-specific subclass)
> - **Relationship**: has type (reuse an appropriate more generic CIDOC CRM property if possible instead of a distinct specification e.g. “is designed according to”)

---

## Outlook

The **methods and workflows of semantic modeling** presented here, together with the **modeling strategy** explained in the tutorial, form the basis for putting the concepts and models developed so far into practice. 

In the following unit, **Protégé** is introduced as an editor for modeling ontologies. Using a concrete example, it is shown how a **machine-readable domain ontology** can be developed and formally described in Protégé on the basis of CIDOC CRM and made accessible for machine processing.

> **Next:**
>
> In the following unit, you will set up your working environment with Protégé.

---

## Bibliography

[Gruber1993knowledge] Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

[Noy2001ontology] Noy, N. F., & McGuinness, D. L. (2001). Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory.

[Uschold1995method] Uschold, M., & King, M. (1995). Towards an Methodology for Building Ontologies. Presented at Workshop on Basic Ontological Issues in Knowledge Sharing held in conjunction with IJCAI. The University of Edinburgh.

