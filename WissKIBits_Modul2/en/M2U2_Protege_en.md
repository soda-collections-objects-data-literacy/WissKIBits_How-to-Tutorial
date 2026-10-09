<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: Dieses Modul ist Teil des How-to-Tutorials „Ontologiegestützte Modellierung von Forschungsdaten“. Das Tutorial vermittelt am Beispiel einer Computerspielsammlung schrittweise die Entwicklung eines semantischen Datenmodells auf Grundlage des CIDOC CRM und dessen Umsetzung mit WissKI.

title: WissKI Bits Ontologiegestützte Modellierung von Forschungsdaten

module: Modellieren mit CIDOC CRM – verstehen und anwenden

unit: Introduction to Protégé

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-10-05

LearningResourceType: SODa How-to-Tutorial

-->

# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 2 (M2): **Modelling with CIDOC CRM – Understand and Apply**

Unit 2 (U2): **Introduction to Protégé**  

**Duration:** ~ 10 min.

**Learning Objectives:**

Participants will be able to...

- name software used for creating ontologies. (LZ-ID SODa\_03\_007\_0809)
- explain software used for creating ontologies. (LZ-ID SODa\_03\_007\_0810)
- name Erlangen CRM / OWL as the OWL implementation of the CIDOC CRM reference model.(LZ-ID SODa\_03\_007\_0841)
- use software for creating ontologies. (LZ-ID SODa\_03\_007\_0840)
- name methods for modelling a domain ontology using the CIDOC CRM reference model. (LZ-ID SODa\_03\_007\_0784a)
- explain methods for modelling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

---

## Protégé – OWL Ontology Editor

In Module 1, you developed a conceptual model sketch and explored possible CIDOC CRM mappings. 

In this Module 2, you will review these decisions and represent selected parts of your model in a machine-readable form.

For this purpose, you use **Protégé** to explore an existing OWL ontology, examine its class and property structure, and create selected domain-specific subclasses.

The practical demonstration uses **Protégé Desktop**. Some steps may differ if you work with WebProtégé.

> **What is Protégé?**
>
> Protégé is a **free, open-source ontology editor** for creating, editing, and managing ontologies.
>
> It supports **OWL 2 Web Ontology Language** and provides a graphical environment for developing formal, machine-readable ontology structures. (Stanford n.d. software)
>
> Protégé is available as: (Stanfordo.D.protege)
>
> - a desktop application ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege)) 
> - a web-based editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege)). 

---

## Protégé in this Tutorial

In this tutorial, **CIDOC CRM [Version 7.1.3, February 2024](https://cidoc-crm.org/get-last-official-release)** (SIG2024cidoc) serves as the **reference ontology** for semantic modelling. Its definitions and scope notes help us examine the meaning of classes and properties and justify our modelling decisions.

For the practical work in Protégé, you use **[Erlangen CRM / OWL](https://erlangen-crm.org/current-version)** (Schiemann2024crm), an OWL implementation of CIDOC CRM.

Following the modelling strategy introduced in M2U1, we will:

- **explore existing classes and properties** in the ontology,
- **reuse CIDOC CRM properties** to represent relationships,
- **create domain-specific subclasses** where further specialisation is required, and
- **document the modelling decisions** behind these extensions.

We will not introduce new properties in this tutorial.

The following video demonstrates the basic steps for exploring an existing ontology and creating a subclass in Protégé.

**Resources**

Further information and guidance are available on the [**official Protégé website**](https://protege.stanford.edu/) (Stanfordo.D.protege):
- [**Protégé Documentation**](https://protege.stanford.edu/support/#documentation) (Stanfordo.D.docu)
- [**Protégé Wiki**](https://protegewiki.stanford.edu/wiki/Main_Page) (Stanfordo.D.wiki)

---

# Video Demonstration

The video introduces three basic operations in Protégé:

- **Load:** Open an existing OWL ontology.
- **Explore:** Navigate the class hierarchy and inspect ontology elements.
- **Extend:** Create a domain-specific subclass within the existing ontology structure.

While watching, pay attention to how the editor distinguishes existing ontology elements from newly created classes.

**Watch the workflow: Load → Explore → Extend**

!?[Video Demonstration: Getting Started with Protégé](../WissKIBits_Modul2/assets/Short_Protege_Intro.mp4)

---

## Outlook

> **Next:**
>
> You have learned how to open and explore an ontology in Protégé.
>
> Next, you will apply these steps to the **computer games domain**: select suitable CIDOC CRM classes and properties, add domain-specific subclasses, and model their relationships.

---

## Bibliography

[SIG2024cidoc] CIDOC CRM Special Interest Group. (2024). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. https://cidoc-crm.org/Version/version-7.1.3

[Schiemann2024crm] Schiemann, B., Oischinger, M., Götz, G., Merges, J., Fichtner, M., & Scholz, M. (o. D.). Erlangen CRM / OWL. https://erlangen-crm.org/

[Stanfordo.D.docu] Stanford Center for Biomedical Informatics Research. (o. D.). Documentation. https://protege.stanford.edu/support/#documentation

[Stanfordo.D.protege] Stanford Center for Biomedical Informatics Research. (o. D.). Protégé. https://protege.stanford.edu/

[Stanfordo.D.wiki] Stanford Center for Biomedical Informatics Research. (o. D.). Protégé Wiki. https://protegewiki.stanford.edu/wiki/Main_Page

[Stanfordo.D.software] Stanford Center for Biomedical Informatics Research. (o. D.). Software. https://protege.stanford.edu/software/

[ref] https://www.w3.org/TR/owl2-primer/ und https://av.tib.eu/media/11276




















