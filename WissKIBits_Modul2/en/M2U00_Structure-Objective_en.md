<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_Wort-Bild_RGB.png

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This module is part of the how-to tutorial “Ontology-Based Modelling of Research Data”. Using a computer game collection as an example, the tutorial teaches the step-by-step development of a semantic data model based on CIDOC CRM and its implementation with WissKI.

title: WissKI Bits Ontology-Based Modelling of Research Data

module: Modelling with CIDOC CRM – Understand and Apply

unit: Welcome, Structure and Objectives

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->


# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 2 (M2): **Modelling with CIDOC CRM – Understand and Apply**

Unit 00 (U00): **Welcome, Structure and Objectives**  

**Duration:** ~ 10 min.


---

## Welcome

In **Module 2: Modelling with CIDOC CRM – Understand and Apply**, you will learn how a conceptual model sketch can be transformed step by step into a **formal ontology structure**.

Building on the model sketch developed in **Module 1: From the Collection via Modelling Decisions to the Diagram – Understand and Explain**, you will review, refine, and implement your previous modelling decisions.

Using the example from the **computer game collection**, you will examine which classes and properties of the **CIDOC CRM** reference model are suitable for describing the selected concepts, events, and relationships.

You will learn how to reuse existing ontology elements, develop domain-specific extensions where needed, and justify your modelling decisions using the CIDOC CRM scope notes.

You will then formalise selected parts of your model sketch using the ontology editor **Protégé** and an OWL implementation of CIDOC CRM.

The resulting machine-readable ontology structure provides the basis for further visualisation and technical implementation in **Module 3: From the Diagram to Paths – Explain and Apply**.

> **What is this module about?**
>
> Starting from a conceptual model sketch, you will examine how selected concepts, events, and relationships can be formally described using CIDOC CRM.
>
> You will review and justify your modelling decisions, reuse existing ontology elements, and add domain-specific elements where needed.
>
> Using **Protégé**, you will transform selected parts of your model sketch into a **machine-readable formal ontology structure in OWL**.
>
> The resulting ontology structure is the starting point for visualisation and technical implementation in **Module 3: From the Diagram to Paths – Explain and Apply**.

---

## Why Model Ontologies Formally?

- Conceptual model sketches make domain concepts, events, and relationships and their semantic connections visible and understandable.
- For computer systems to process these semantic connections and use them in different application contexts, they need to be described formally and in a machine-readable form.
- Reusing existing ontologies such as CIDOC CRM supports a shared semantic foundation and thus the interoperability of research and collection data.
- Domain-specific extensions make it possible to represent additional domain requirements that cannot be adequately described by the reference model alone.
- Formally describing and documenting modelling decisions provides a basis for the technical implementation and long-term reuse of a data model.

> A conceptual model sketch makes semantic connections within a domain understandable.
>
> A formal ontology in OWL/RDF describes these connections in a machine-readable form.
>
> **Formal modelling provides a basis for representing domain knowledge interoperably and using it in technical systems.**

---

## Guiding Question

The guiding question throughout this module is:

> **How can a conceptual model sketch be transformed into an ontology structure based on CIDOC CRM that is justified in terms of the domain and machine-readable?**

---

## Objectives of this Module

In this module, you will learn how to formally implement selected parts of a semantic data model using CIDOC CRM and Protégé, building on the conceptual model sketch for the collection object “Zelda”.

By the end of the module, you will be able to:

- explain a systematic **workflow for semantic modelling** and apply it under guidance,
- examine selected **CIDOC CRM classes and properties** using their scope notes and select them for modelling,
- distinguish between reusing existing ontology elements and introducing domain-specific extensions,
- use the ontology editor **Protégé** to explore and edit an OWL ontology,
- integrate selected **domain-specific concepts and relationships** into an existing ontology structure,
- justify modelling decisions in terms of the domain, implement them formally, and document them,
- save a selected section of the model in a machine-readable **OWL format**, and
- prepare the resulting ontology structure for further visualisation and technical implementation in **Module 3: From the Diagram to Paths – Explain and Apply**.

---

## Structure of this Module

**Total duration of Module 2: approx. 90 min.**

| Unit | Content | Duration |
|---|---|---:|
| M2U00 | [Welcome, objectives and structure](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/en/M2U0_Structure-Objective_en.md#1) | 10 min. |
| M2U0A | [Activation: Preparing your working environment with Protégé](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/en/M2U1A_Setup-Protege_en.md#1) | 15 min. |
| M2U1 | [Methods and workflows of semantic modelling](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/en/M2U1_Methods-Workflows_en.md#1) | 5 min. |
| M2U2 | [Introduction to Protégé](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/en/M2U2_Protege_en.md#1) | 10 min. |
| M2UE | Exercise: [Semantic modelling with CIDOC CRM](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/en/M2UE_Modelling-CIDOCCRM_en.md#1) | 50 min. |
| | **Total** | **90 min.** |
  
---

## Learning Objectives of this Module

After completing module 2, participants will be able to…

### U0A. Preparing to work with Protégé

- name software used for creating ontologies. (LO-ID SODa\_03\_007\_0809)
- apply software used for creating ontologies. (LO-ID SODa\_03\_007\_0840)
- analyse their own experience with software used for creating ontologies. (LO-ID SODa\_03\_007\_0857)

### U1. Methods and Workflows of Semantic Modelling

- name methods to develope ontologies. (LO-ID 03\_007\_0784)
- explain methods for developing ontologies. (LO-ID SODa\_03\_007\_0839)
- name a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0626)
- explain a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0853)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0785a)

### U2. Introduction to Protégé

- name software used for creating ontologies. (LO-ID SODa\_03\_007\_0809)
- explain software used for creating ontologies. (LO-ID SODa\_03\_007\_0810)
- name Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0841)
- apply software used for creating ontologies. (LO-ID SODa\_03\_007\_0840)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0785a)

### UE. Semantic Modelling with CIDOC CRM

- apply ontologies to describe resources. (LO-ID 03\_007\_0780)
- apply methods for developing ontologies. (LO-ID SODa\_03\_007\_0854)
- apply a workflow for semantic modelling as data documentation. (LO-ID SODa\_03\_001\_0627)
- apply methods for modelling a domain ontology using the CIDOC CRM reference model under guidance. (LO-ID SODa\_03\_007\_0786a) 
- apply software used for creating ontologies. (LO-ID SODa_03_007_0840)
- apply Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa_03_007_0855)
- apply Scope Notes of the CIDOC CRM reference model for describing resources. (LO-ID SODa\_03\_007\_0780a)

---

## Learning Path through this Module

Building on the conceptual model sketch from Module 1, participants work through the following stages:

**Prepare your working environment (M2U0A):**
Set up Protégé Desktop or WebProtégé for the practical activities.

↓

**Explore modelling methods (M2U1):**
Learn about different approaches and an iterative workflow for developing ontologies.

↓

**Explore Protégé (M2U2):**
Load an OWL implementation of CIDOC CRM, examine its structure, and create a domain-specific subclass.

↓

**Apply CIDOC CRM, formalise the model, and save the ontology (M2UE):**
Review selected mappings to CIDOC CRM, implement extensions justified in terms of the domain, and document modelling decisions.

↓

**Outcome:** A selected part of the domain model is available as a formal ontology structure in OWL. The domain reasoning and modelling decisions are documented.

---

## Working Method and Example

> **How you will work**
>
> We begin by preparing the working environment with Protégé, followed by a short introduction to methods and workflows for ontology development.
>
> After the introduction to Protégé, you will return to the conceptual model sketch from Module 1 and its [**CIDOC CRM formalisation**](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul1/en/M1UE_Application-Example-Object_en.md#1). You will review selected modelling decisions using CIDOC CRM and implement them formally.
>
> Our shared example remains the collection object **The Legend of Zelda: A Link to the Past**.
>
> You will document and save the results of your modelling work as a basis for further work in **Module 3 (M3): From the Diagram to Paths – Explain and Apply**.

The module combines short domain-focused and methodological inputs with demonstrations, analysis, discussion, and practical modelling activities:

- Methods and workflows for ontology development are introduced using typical modelling tasks.
- The user interface and central areas of Protégé are presented through a demonstration.
- The OWL implementation **[Erlangen CRM](https://erlangen-crm.org/current-version)** (Schiemann, 2024) is loaded and explored through its classes, object properties, and datatype properties.
- The example object **The Legend of Zelda: A Link to the Past** and the CIDOC CRM formalisation of the conceptual model sketch once again provide a common thread.

In the exercise:

- Participants review selected mappings to CIDOC CRM using the scope notes and justify their modelling decisions.
- Domain-specific concepts such as game characteristic, platform type, genre type, or edition type are examined to determine their appropriate ontological representation.
- Existing classes and properties are reused and, where needed, supplemented with suitable domain-specific subclasses extending CIDOC CRM.
- The results are documented, checked for domain coherence and formal consistency, and saved in an OWL format.

The goal is not a complete domain ontology. What matters is a **small, consistent, and justifiable section of the model** that is formally described and can later be extended and technically implemented.

---

## Prerequisites

The content of [**Module 1: From the Collection via Modelling Decisions to the Diagram – Understand and Explain**](https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul1/en/M1U00_Structure-Objective_en.md) or equivalent basic knowledge of semantic modelling is assumed.

Participants should…

- be able to distinguish the terms domain, concept, event, and relationship,
- know the building blocks classes (entities), properties, instances, and modelling assumptions,
- understand the basic principle of event-centred modelling with CIDOC CRM,
- know scope notes as a basis for modelling decisions, and
- have at least an initial conceptual model sketch, ideally a CIDOC CRM-based semantic domain model.

For the practical activities, the following are required and will be made available during the module:

- your **conceptual model sketch formalised using CIDOC CRM** from Module 1 or your own modelling context,
- a computer with **Protégé Desktop** installed or access to **WebProtégé**,
- the **OWL implementation of CIDOC CRM (Erlangen CRM)** used in this tutorial, available locally or accessible via a web address.

Information about Protégé Desktop and WebProtégé is available on the [Stanford University website](https://protege.stanford.edu/software) (Stanford, 2026a).

---

## Outcome of this Module

At the end of Module 2, an initial **formal ontology structure in OWL** is available, based on the conceptual model sketch from Module 1.

> **What will you take away from this module?**
>
> By the end of the module, you will have an initial formally implemented section of the **semantic domain model for computer games**. It includes:
>
> - selected CIDOC CRM classes and properties,
> - domain-specific ontology elements added where needed,
> - formally described relationships between the selected ontology elements,
> - modelling decisions justified in terms of the domain and documented, and
> - a machine-readable representation of the selected model section in OWL.
>
> This ontology structure is the starting point for further visualisation and technical implementation in WissKI.

---

## Outlook

Module 2 takes you from preparing your working environment through exploring an OWL implementation of CIDOC CRM in Protégé to formally implementing selected parts of the semantic domain model.

Visualising the ontology structure, integrating it into WissKI, and configuring semantic paths in the WissKI Pathbuilder are covered in **Module 3: From the Diagram to Paths – Explain and Apply**.

> **What comes next?**
>
> In the next unit, [**M2U0A: Preparing your working environment with Protégé**](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/en/M2U2A_Setup-Protege_en.md#1), you will prepare Protégé Desktop or WebProtégé for the practical activities.
>
> In the following unit, **M2U1: Methods and workflows of semantic modelling**, you will learn about different approaches to ontology development and how a systematic, iterative modelling workflow can support the development of a domain ontology based on CIDOC CRM.

---

## Bibliography

(Schiemann, 2024) Schiemann, B., Oischinger, M., Görz, G., Hohmann, G., Merges, J., Fichtner, M., & Scholz, M. (n.d.). Erlangen CRM OWL. University of Erlangen-Nuremberg, Department of Computer Science, Chair of Artificial Intelligence. Retrieved 27 August 2026, from https://erlangen-crm.org/current-version

(Stanford, 2026a) Stanford Center for Biomedical Informatics Research. (2026a). Protégé. Retrieved 15 October 2026, from https://protege.stanford.edu/

## Editorial Notes

- The schedule is designed for a total of 90 minutes and can be adjusted depending on the scope of the practical exercise.


