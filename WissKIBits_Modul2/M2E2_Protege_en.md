<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: de

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

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to-Tutorial

-->

# WissKI Bits: Ontology-Based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Modul 2: **Modeling with CIDOC CRM – understand and apply**

Einheit 2: **Introduction in Protégé**  

**Duration:** ~ 20 min.

**Learning Objectives:**

Participants will be able to...

- name software used for creating ontologies. (LZ-ID SODa\_03\_007\_0809)
- explain software used for creating ontologies. (LZ-ID SODa\_03\_007\_0810)
- name Erlangen CRM / OWL as the OWL implementation of the CIDOC CRM reference model.(LZ-ID SODa\_03\_007\_0841)
- use software for creating ontologies. (LZ-ID SODa\_03\_007\_0840)
- name methods for modeling a domain ontology using the CIDOC CRM reference model. (LZ-ID SODa\_03\_007\_0784a)
- explain methods for modeling a domain ontology using the CIDOC CRM reference model. (SODa\_03\_007\_0785a)

---

## Protégé – OWL Ontology Editor

**Protégé** is a free, open-source editor for creating, editing, and managing ontologies. The current version specifically supports the **OWL 2 Web Ontology Language**, thereby providing an environment for the formal and machine-readable modeling of ontologies. (Stanford n.d. software)

Protégé is available both as a desktop application ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege)) and as a web-based editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege)). (Stanfordo.D.protege)

**Protégé Desktop** is used in the practical session (M2EÜ) of this module. The editor provides a graphical interface for creating, editing, and structuring ontologies. Existing ontologies can be opened in Protégé and used as a basis for further modeling. The resulting models can then be saved in a **machine-readable format** and used for further processing.

Within this module, Protégé is used to transform the **semantic model of the computer games domain**—developed in Module 1—**into a formal, machine-readable OWL ontology**.

The **CIDOC CRM ([Release Version 7.1.3, as of February 2024](https://cidoc-crm.org/get-last-official-release))** (SIG2024cidoc) serves as the reference ontology—specifically, the existing OWL implementation of the CIDOC CRM known as **[Erlangen CRM / OWL](https://erlangen-crm.org/current-version)** (Schiemann2024crm).

**Note**

Resources for working with Protégé are available on the [**official Protégé website**](https://protege.stanford.edu/) (Stanfordo.D.protege):

> - [Documentation](https://protege.stanford.edu/support/#documentation) (Stanfordo.D.docu)
>
> - [Wiki](https://protegewiki.stanford.edu/wiki/Main_Page) (Stanfordo.D.wiki)

The outcome of the practical session is a **machine-readable OWL domain ontology** that serves as the basis for the subsequent implementation in **WissKI** in Module 3.

---

## Live Demo in Protégé

This session demonstrates how to **load and open an OWL implementation of the CIDOC CRM** in **Protégé**.

Using the loaded ontology, the Protégé workspace is introduced. We examine the various components of the ontology—specifically the classes and their hierarchy—and gain initial insights into their representation and structure.

This **live demo** serves as an **initial orientation to Protégé** and lays the groundwork for the subsequent **practical session**, in which the previously developed computer game domain model will be implemented in Protégé.

---

### Overview of Steps

Ensure that either Protégé Desktop is installed locally or you have an account for WebProtégé:

- Desktop application ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege))
- Web-based editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege)).

**Step 1: Load the existing ontology**

To work with Protégé, the **Erlangen CRM / OWL**—a **machine-readable OWL implementation of the CIDOC CRM**—is used:

- The **Erlangen CRM / OWL** can be downloaded here: https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl
- Load this file into **Protégé Desktop**.


**Step 2: Explore the structure**

- You can **explore the structure of the CIDOC CRM** within Protégé.
- This includes, in particular, the **hierarchy of classes (entities) and the object properties** used to relate or describe the classes (entities).

**Note**

> - Classes (Entities): the central classes or entity types of the CIDOC CRM
> - Object properties (Properties): relations between classes (entities)
> - Datatype properties (Datatype-Properties): properties that describe values ​​or literals


**Step 3: Creating a custom subclass (entity) for the computer games domain ontology**

- New, domain-specific entities are created as **subclasses of existing CIDOC CRM entities**.

**Example:**

>  E35 Title --> Game_Title
>
>  **Game_Title** is a domain-specific subclass of **E35 Title** and serves to model titles more specifically within the context of the computer games domain.

---

## Video Demonstration

The live demo illustrates:

- Step 1: Loading an existing ontology,
- Step 2: Exploring the structure, and
- Step 3: Creating a custom subclass (entity) for the computer games domain ontology.

!?[Video Demonstration: Getting Started with Protégé](../WissKIBits_Modul2/assets/Short_Protege_Intro.mp4)

> **Video:** Brief introduction to the Protégé user interface

---

## Outlook

The steps taken so far have demonstrated how to **open and explore the CIDOC CRM in Protégé** and how existing entities can be extended to model a specific domain.

In the **practical session** that follows, this approach is applied to the **computer games domain**. The previously developed semantic model is implemented in Protégé step by step. This involves selecting suitable CIDOC CRM entities, extending them into domain-specific subclasses, and modeling the corresponding properties.

In this way, the conceptual model sketch evolves into a **formally described and machine-readable OWL ontology**, which can subsequently be used for implementation in WissKI.

---

## Bibliography

[SIG2024cidoc] CIDOC CRM Special Interest Group. (2024). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. https://cidoc-crm.org/Version/version-7.1.3

[Schiemann2024crm] Schiemann, B., Oischinger, M., Götz, G., Merges, J., Fichtner, M., & Scholz, M. (o. D.). Erlangen CRM / OWL. https://erlangen-crm.org/

[Stanfordo.D.docu] Stanford Center for Biomedical Informatics Research. (o. D.). Documentation. https://protege.stanford.edu/support/#documentation

[Stanfordo.D.protege] Stanford Center for Biomedical Informatics Research. (o. D.). Protégé. https://protege.stanford.edu/

[Stanfordo.D.wiki] Stanford Center for Biomedical Informatics Research. (o. D.). Protégé Wiki. https://protegewiki.stanford.edu/wiki/Main_Page

[Stanfordo.D.software] Stanford Center for Biomedical Informatics Research. (o. D.). Software. https://protege.stanford.edu/software/





















