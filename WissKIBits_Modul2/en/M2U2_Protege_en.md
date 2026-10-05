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

einheit: Einführung in Protégé

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

**Protégé** is a free, open-source editor for creating, editing, and managing ontologies. The current version specifically supports the **OWL 2 Web Ontology Language** (ref), thereby providing an environment for the formal and machine-readable modelling of ontologies. (Stanford n.d. software)

Protégé is available both as a desktop application ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege)) and as a web-based editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege)). (Stanfordo.D.protege)

**Protégé Desktop** is used in the practical session (M2EÜ) of this module. The editor provides a graphical interface for creating, editing, and structuring ontologies. Existing ontologies can be opened in Protégé and used as a basis for further modelling. The resulting models can then be saved in a **machine-readable format** and used for further processing.

> **What is Protégé?**
>
> Protégé is a **free, open-source ontology editor** for creating, editing, and managing ontologies.
>
> It supports OWL 2 and provides a graphical environment for developing formal, machine-readable ontology structures.
>
> Protégé is available as:
>
> - Protégé Desktop – a locally installed application
> - WebProtégé – a web-based ontology editor

---

## Protégé in this Tutorial

In this tutorial, **CIDOC CRM [Version 7.1.3, February 2024](https://cidoc-crm.org/get-last-official-release)** (SIG2024cidoc) serves as the **reference ontology** for semantic modelling.

To explore and extend CIDOC CRM in Protégé, we use **[Erlangen CRM / OWL](https://erlangen-crm.org/current-version)** (Schiemann2024crm), an OWL implementation of CIDOC CRM.

Protégé provides the working environment for exploring the existing ontology structure and extending it with selected **domain-specific elements**. 

In the following video, you will see the basic steps needed to prepare for the practical modelling exercise.

> **Resources**
>
> Further resources for working with Protégé are available on the [**official Protégé website**](https://protege.stanford.edu/) (Stanfordo.D.protege):
>
> - [**Protégé Documentation**](https://protege.stanford.edu/support/#documentation) (Stanfordo.D.docu)
> - [**Protégé Wiki**](https://protegewiki.stanford.edu/wiki/Main_Page) (Stanfordo.D.wiki)

---

# Video Demonstration

The live demo illustrates:

- Step 1: Loading an existing ontology,
- Step 2: Exploring the structure, and
- Step 3: Creating a custom subclass (entity) for the computer games domain ontology.

Watch how an existing ontology is opened, how its structure is explored, and how a domain-specific subclass is added.

> **Watch the workflow**
>
> The video demonstrates the complete introductory workflow: Load → Explore → Extend
> 
> !?[Video Demonstration: Getting Started with Protégé](../WissKIBits_Modul2/assets/Short_Protege_Intro.mp4)

---

## Outcome

You have seen how to **load and explore an existing ontology in Protégé** and how it can be extended with a **domain-specific subclass**.

---

## Outlook

> **Next: Semantic Modelling with CIDOC CRM**
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




















