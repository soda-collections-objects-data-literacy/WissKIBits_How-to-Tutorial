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

einheit: Semantische Modellierung mit CIDOC CRM

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to-Tutorial

-->

# SODa WissKI Bits: Ontology-Based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 2: **Modeling with CIDOC CRM – Understanding and Applying**

Activation Unit M2E1A: **Mapping the conceptual model to CIDOC CRM**  

**Duration:** ~ 30 min.

**Learning Objectives:**

Participants will be able to...

- ....????

---

## Objective and scenario

This exercise provides a documented mapping of selected domain concepts and relationships to suitable CIDOC CRM classes and properties.

---

## Starting point: Model from module 1

In Module 1, a model sketch was developed describing key concepts and relationships in the video game domain:

![Concept Mind Map](../WissKIBits_Modul2/assets/Mindmap.png)

> **Figure:** The graphic shows the conceptual model sketch of a section of the example domain.

The collected domain terms will now be gradually formalized using CIDOC CRM and Protégé.

For this exercise, the following can be selected, among others:

> Video game → **has title** → Game title
>
> Video game → **has type** → Genre
>
> Video game → **has type** → Platform type


We distinguish between three levels:

| Level                    | Example                                             |
| ------------------------ | --------------------------------------------------- |
| Domain statement         | Game has title                                      |
| Semantic modeling        | E73 Information Object – P102 has title – E35 Title |
| Formal OWL structure     | `Computer_Game SubClassOf P102 some Game_Title`     |

---

## Example: From the sketch model to the ontology

In Module 1, the following was initially formulated at the domain level:

> Game → has title → Title

For semantic modeling, we will now examine which elements of the CIDOC CRM can be used to express this statement.

One possible starting point is:

| Element           | Possible CIDOC CRM Mapping |
| ----------------- | -------------------------- |
| **Video game**    | E73 Information Object     |
| **Game title**    | E35 Title                  |
| **Relationship**  | P102 has title             |


At the same time, **E35 Title** is a more specific form of **E41 Appellation**. The class hierarchy thus makes explicit that a title is a particular form of appellation.

---

### Step 2: Select and review appropriate CIDOC CRM classes

In Protégé, find the appropriate class for each domain term and review the class's Scope Note.

Justify your selection.

**Example**

> **E73 Information Object**
>
> **E35 Title**
>
> **E55 Type**

Assign an appropriate CIDOC CRM class to each domain term and justify your decision.

| Domain Term        | Possible CIDOC CRM Class |
| ------------------ | ------------------------ |
| Computer Game      | E73 Information Object   |
| Game Title         | E35 Title                |
| Game Genre Type    | E55 Type                 |
| Game Platform Type | E55 Type                 |


**Justifications**

Computer Game – E73 Information Object

↓  

Game Title – E35 Title

↓  

Game Genre Type – E55 Type

↓  

Game Platform Type – E55 Type


**Note:**

> The suitability of a class is determined not by its name, but by its meaning within the reference model.


**Guiding questions for reviewing the class may include**

- What does the CIDOC CRM class describe?
- Does this meaning correspond to our domain term?
- Which statement in the Scope Note supports your decision?
- Are alternative mappings possible?

---

**Document your mapping**

Record the modelling decisions that you want to take forward into Protégé.

| Domain element | Intended meaning | CIDOC CRM element | Evidence from Scope Note | Decision |

> |---|---|---|---|---|
> | Computer game |  |  |  |  |
> | Game title |  |  |  |  |
> | has title |  |  |  |  |
> | Genre |  |  |  |  |
> | has type |  |  |  |  |


## Outcome

You have mapped selected concepts and relationships from the conceptual model to CIDOC CRM classes and properties and justified your decisions using the Scope Notes.

Keep your mapping table. You will use these decisions to formalise the model in Protégé in M2E2E.

