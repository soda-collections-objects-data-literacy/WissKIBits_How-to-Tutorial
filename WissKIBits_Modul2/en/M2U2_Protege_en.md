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

unit: Introduction to Protégé

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 2 (M2): **Modelling with CIDOC CRM – Understand and Apply**

Unit 2 (U2): **Introduction to Protégé**  

**Duration:** ~ 10 min.

**Learning Objectives:**

Participants will be able to...

- name software used for creating ontologies. (LO-ID SODa\_03\_007\_0809)
- explain software used for creating ontologies. (LO-ID SODa\_03\_007\_0810)
- name Erlangen CRM / OWL as the OWL implementation of the CIDOC CRM reference model.(LO-ID SODa\_03\_007\_0841)
- apply software used for creating ontologies. (LO-ID SODa\_03\_007\_0840)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0785a)

---

## Protégé – OWL Ontology Editor

In Module 1, you developed a conceptual model sketch and explored possible mappings to CIDOC CRM.

In Module 2, you review these modelling decisions and transform selected parts of your model into a machine-readable form.

For this purpose, you use **Protégé** (Stanford, 2026a) to explore an existing OWL ontology, examine its class and property structure, and create selected domain-specific subclasses.

The practical demonstration uses **Protégé Desktop**. Some steps may differ if you work with WebProtégé.

> **What is Protégé?**
>
> Protégé is a **free, open-source ontology editor** for creating, editing, and managing ontologies.
>
> Protégé supports the **OWL 2 Web Ontology Language** (Sack, 2009) and provides a graphical environment for developing formal, machine-readable ontology structures (Stanford, 2026a).
>
> Protégé is available in two versions (Stanford, 2026b):
>
> - as a desktop application ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege)), and
> - as a web-based editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege)).

---

## Protégé in this Tutorial

In this tutorial, **CIDOC CRM [Version 7.1.3, February 2024](https://cidoc-crm.org/Version/version-7.1.3)** (CIDOC, 2024a) is the **reference ontology** for semantic modelling. Its definitions and scope notes help you examine the meaning of classes and properties and justify your modelling decisions in terms of the domain.

For the practical work in Protégé, you use **[Erlangen CRM / OWL](https://erlangen-crm.org/current-version)** (Schiemann, 2024), an OWL implementation of CIDOC CRM.

Following the modelling strategy introduced in M2U1, you will:

- **explore existing classes and properties** in the ontology,
- **reuse CIDOC CRM properties** to represent relationships,
- **create domain-specific subclasses** where further specialisation is required, and
- **document the modelling decisions** behind these extensions.

No new properties are introduced in this tutorial.

The following video demonstrates the basic steps for exploring an existing ontology and creating a subclass in Protégé.

**Further Resources**

Further information and guidance are available on the [**official Protégé website**](https://protege.stanford.edu/) (Stanford, 2026a):

- [**Protégé Documentation**](https://protege.stanford.edu/support/#documentation) (Stanford, 2026c)
- [**Protégé Wiki**](https://protegewiki.stanford.edu/wiki/Main_Page) (Stanford, 2022)

---

# Video Demonstration

The video introduces four basic steps in Protégé:

- **Start:** Launch your Protégé working environment.
- **Open:** Load an existing OWL ontology, for example, Erlangen CRM 240920 based on CIDOC CRM 7.1.3. Erlangen CRM / OWL is available at [https://erlangen-crm.org/current-version](https://erlangen-crm.org/current-version).
- **Explore:** Examine the class hierarchy and ontology elements.
- **Extend:** Add domain-specific subclasses to the existing ontology structure.

While watching, pay attention to how the editor distinguishes existing ontology elements from newly created classes.

**Watch the workflow: Load → Explore → Extend**

!?[Video Demonstration: Getting Started with Protégé](../assets/Short_Protege_Intro.mp4)

---

## Outlook

In this unit, you have become familiar with the ontology editor Protégé and learned how to open an existing OWL ontology, explore its structure, and create a domain-specific subclass.

You will now apply this knowledge to the conceptual model sketch from Module 1. You will review selected modelling decisions using the CIDOC CRM scope notes and implement them formally in Protégé.

> **What comes next?**
>
> In the next unit, [**M2UE: Semantic modelling with CIDOC CRM**](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/en/M2UE_Modelling-CIDOCCRM_en.md#1), you will work with Protégé and create subclasses.
>
> You will select suitable CIDOC CRM classes and properties, add domain-specific ontology elements where needed, and model their relationships.
>
> You will justify and document your modelling decisions and transform selected parts of your conceptual model sketch into a **machine-readable ontology structure in OWL**.

---

## Bibliography

(CIDOC, 2024a) CIDOC CRM Special Interest Group. (2024a). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. Retrieved 15 October 2026, from https://cidoc-crm.org/Version/version-7.1.3

(Sack, 2009) Sack, H. (2009). OWL 2 [Video recording]. Hasso Plattner Institut (HPI). Retrieved 15 October 2026, from https://av.tib.eu/media/11276

(Schiemann, 2024) Schiemann, B., Oischinger, M., Götz, G., Merges, J., Fichtner, M., & Scholz, M. (n.d.). Erlangen CRM / OWL. Retrieved 15 October 2026, from https://erlangen-crm.org/

(Stanford, 2026a) Stanford Center for Biomedical Informatics Research. (2026a). Protégé. Retrieved 15 October 2026, from https://protege.stanford.edu/

(Stanford, 2026b) Stanford Center for Biomedical Informatics Research. (2026b). Software Protégé. Retrieved 15 October 2026, from https://protege.stanford.edu/software/

(Stanford, 2026c) Stanford Center for Biomedical Informatics Research. (2026c). Protégé Documentation. Retrieved 15 October 2026, from https://protege.stanford.edu/support/#documentation

(Stanford, 2022) Stanford Center for Biomedical Informatics Research. (2022). Protégé Wiki. Retrieved 15 October 2026, from https://protegewiki.stanford.edu/wiki/Main_Page
