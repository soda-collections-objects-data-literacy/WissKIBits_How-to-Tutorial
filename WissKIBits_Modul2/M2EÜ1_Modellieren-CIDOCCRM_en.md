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

Exercise Unit Ü1: **Semantic Modeling with CIDOC CRM**  

**Duration:** ~ 55 min.

**Learning Objectives:**

Participants will be able to...

- apply an ontology to describe resources. (LO-ID 03\_007\_0780)
- apply methods for developing ontologies. (LO-ID SODa\_03\_007\_0854)
- apply a workflow for semantic modeling as data documentation. (LO-ID SODa\_03\_001\_0627)
- apply, with guidance, methods for modeling a domain ontology using the CIDOC CRM reference model. (LO-ID SODa\_03\_001\_0786a)
- use software for creating ontologies. (LO-ID SODa_03_007_0840)
- use Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM reference model. (LO-ID SODa_03_007_0855)
- apply the Scope Notes of the CIDOC CRM reference model to describe resources. (LO-ID SODa\_03\_007\_0780a)

---

## Objective and Scenario

This is a practical exercise. The starting point is the conceptual model of the video game domain developed in Module 1.

Using **“The Legend of Zelda: A Link to the Past”** as an example, we will examine how this conceptual model sketch can be gradually transformed into a **formal ontology structure**.

The necessary steps are:

- comparing selected concepts from the domain model with classes of the **CIDOC CRM**,
- reviewing modeling decisions based on **definitions and Scope Notes**,
- creating domain-specific concepts as **subclasses** in Protégé,
- examining properties in the CIDOC CRM for the relationships between these concepts.

The focus is on the **formal modeling workflow**.

At the end of the exercise, a formally implemented section of the domain model will be available as an **OWL ontology**.

---

## Starting Point: Model from Module 1

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

## Focus of This Modeling Exercise

The focus is on four fundamental steps:

**Step 1: Load the ontology and explore its structure**

**Step 2: Select and justify CIDOC CRM classes**

**Step 3: Create domain-specific subclasses**  

**Step 4: Review the model and document modeling decisions**

---

## Example: From the Model Sketch to the Ontology

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
## Exercise – Implementing the Model in Protégé

**Format:** Individual work or teams (2–4 people)

**Materials:** Computer with Protégé Desktop, provided Erlangen CRM OWL file, model sketch from Module 1 [Link]

**Time:** ~ 45 min.

**Task: Recreate a section of the domain model in Protégé**

**Prerequisite:**

To work with Protégé, either

- the desktop application ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege)) or
- an account for the web-based editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege))

must be set up via the [**official Protégé website**](https://protege.stanford.edu/).

**Note:**

> Approximately 5 minutes are allocated for the setup.

----

### Step 1: Load Erlangen CRM and Explore Its Structure

Open Protégé Desktop and load the provided OWL implementation of CIDOC CRM:

[**Erlangen CRM / OWL**](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl): https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl

**Note:** 

> The steps shown in the live demo and the corresponding video can be reviewed in M2E2:

!?[Video Demonstration: First Steps in Protégé](../WissKIBits_Modul2/assets/Short_Protege_Intro.mp4)
 
> **Video:** The video demonstrates the first steps in Protégé and how to load Erlangen CRM / OWL.


Then briefly explore the structure of the ontology and locate the following classes in the class hierarchy:

- **E41 Appellation**
- **E35 Title**
- **E55 Type**
- **E73 Information Object**

In particular, examine:

- Where is the class located in the hierarchy?
- Which superclasses and subclasses are visible?
- What description or annotation is provided?
- Which properties are used for the class?

**Note:**

> Pay particular attention to **E41 Appellation** and **E35 Title**: E35 Title is a subclass of E41 Appellation. This illustrates how more general and more specific concepts are connected within an ontology.

---

### Step 2: Select and Review Appropriate CIDOC CRM Classes

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

[[__________________________________________________]]

Game Title – E35 Title

[[__________________________________________________]]

Game Genre Type – E55 Type

[[__________________________________________________]]

Game Platform Type – E55 Type

[[__________________________________________________]]

**Note:**

> The suitability of a class is determined not by its name, but by its meaning within the reference model.

**Guiding Questions for Reviewing the Class May Include**

- What does the CIDOC CRM class describe?
- Does this meaning correspond to our domain term?
- Which statement in the Scope Note supports your decision?
- Are alternative mappings possible?

---

### Step 3: Create Domain-Specific Subclasses

Now create the domain-specific subclasses in Protégé.

The subclasses should be placed under the previously selected CIDOC CRM classes:

```text
E73 Information Object
└── Computer_Game

E35 Title
└── Game_Title

E55 Type
├── Game_Genre_Type
└── Game_Platform_Type


**Example: For Genre or Platform**

> Computer game → **has type** → Genre / Platform type
>
> Find: **P2 has type**

Document your review:

| Source        | Property       | Target             | Intended Statement                                      |
| ------------- | -------------- | ------------------ | ------------------------------------------------------- |
| Computer_Game | P102 has title | Game_Title         | A computer game has a title.                            |
| Computer_Game | P2 has type    | Game_Genre_Type    | A computer game is assigned to a genre type.            |
| Computer_Game | P2 has type    | Game_Platform_Type | A computer game is assigned to a platform type.         |

**Note:**

> The properties will be needed in the next module, Module 3.


**Guiding Questions:**

- Does the meaning of the property correspond to our domain statement?
- Are the source and target classes compatible with the domain and range?
- Does the property actually describe the relationship we want to express?

---

### Step 5: Review and Document the Model

Compare your result with the original model sketch:

![Concept Mind Map](../WissKIBits_Modul2/assets/Mindmap.png)

> **Figure:** The graphic shows the conceptual model sketch of a section of the example domain.

**Review the Modeling**

- Are the domain-specific classes appropriately placed within the CIDOC CRM hierarchy?
- Do the properties correspond to the intended statements?
- Can the decisions be justified based on the Scope Notes?
- Can the relationships still be read as understandable statements?
- Which elements originate from CIDOC CRM, and which were added specifically for the domain?
- Write Scope Notes / Comments for the newly created domain subclasses and assign labels.


**Document the Modeling Decision**

Document your decision for **one** mapping:

| Question                                             | Answer |
| ---------------------------------------------------- | ------ |
| Which domain term are we modeling?                   |        |
| Which CIDOC CRM class or property are we using?      |        |
| What meaning do we want to express?                  |        |
| What does the Scope Note say about it?               |        |
| Why do we consider the mapping appropriate?          |        |

**Note:** 

> The aim is not to find a single “correct” solution. What matters is that the modeling decision is comprehensible from a domain perspective and compatible with the reference model being used.

---

## Sample Solution

As a sample, you can examine the existing domain ontology for computer games:

[**Game Domain Ontology – RDF**](http://games.m-e-g-a.org/game_domain.rdf)

Compare your own modeling with the sample **only after completing the task**. The sample should be understood as one possible modeling approach, not as the only possible solution.

**Note**

> Pay particular attention to:
>
> - the placement of domain-specific classes,
> - the reuse of CIDOC CRM properties,
> - and possible differences compared with your own modeling decisions.

---

## Outcome

At the end of this exercise, you will have a small, formally implemented section of the **computer games** domain model.

You have:

- created domain-specific concepts as **subclasses** of CIDOC CRM,
- and justified a modeling decision based on a **Scope Note**.

Then save the extended ontology as an **OWL file**.

**Note:** 

> The ontology remains a partial model.
> 
> It does not represent the entire computer games domain, but instead demonstrates the process of moving from a domain-specific conceptual model sketch to a machine-readable ontology structure.

---

## Outlook

In this exercise, the domain model developed in Module 1 was **formally implemented in Protégé** for the first time.

Three levels were connected:

> **domain statement → CIDOC CRM modeling → OWL formalization**

The saved OWL file provides the basis for **Module 3**.
