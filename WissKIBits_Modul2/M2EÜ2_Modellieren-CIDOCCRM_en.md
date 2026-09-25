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

Exercise Unit M2E2E: **Semantic Modeling with CIDOC CRM**  

**Duration:** ~ 45 min.

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

This is a practical exercise. 

The starting point is the conceptual model of the video game domain developed in Module 1.

Using **“The Legend of Zelda: A Link to the Past”** as an example, we will examine how this conceptual model sketch can be gradually transformed into a **formal ontology structure**.

In this exercise, we will formalise these decisions in Protégé by creating domain-specific subclasses and integrating them into the CIDOC CRM structure.

At the end of the exercise, we will have a formally implemented section of the domain model as an OWL ontology.

---

## Starting Point: The Conceptual Model from Module 1

In Module 1, we developed a conceptual model sketch describing concepts and relationships in the computer games domain:

![Concept Mind Map](../WissKIBits_Modul2/assets/mindmap_en.png)

> **Figure:** The graphic shows the conceptual model sketch of a section of the example domain.

From this we have discussed a first mapping to some CIDOC CRM classes.

For this exercise, we will focus on selected statements from this model:

> Computer game → **has title** → Game title
>
> Computer game → **has type** → Genre
>
> Computer game → **has type** → Platform type

We will now investigate how these domain statements can be represented using CIDOC CRM and implemented in Protégé.

---

## From the Conceptual Model to a Formal Ontology

During the exercise, we will move between three levels:

| Level | Example |
|---|---|
| Domain statement | Game has title |
| Semantic modelling | E73 Information Object – P102 has title – E35 Title |
| Formal ontology structure | Domain-specific classes and relationships represented in OWL |

The important point is that these levels serve different purposes.

The **domain statement** expresses what we want to say about the research object.

The **CIDOC CRM mapping** identifies ontology elements that can represent this meaning.

The **formal ontology structure** makes the modelling decision machine-readable.

---

## Exercise – Implementing the Model in Protégé

**Format:** Individual work or teams (2 people)

**Materials:** Computer with Protégé Desktop, provided Erlangen CRM OWL file, model sketch from Module 1 [Link]

**Time:** ~ 30 min.

**Task: Recreate a section of the domain model in Protégé**

**Prerequisite:**

To work with Protégé, either

- the desktop application ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege)) or
- an account for the web-based editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege))

must be set up via the [**official Protégé website**](https://protege.stanford.edu/).

----

### Step 1: Load Erlangen CRM and Explore its Structure

Open Protégé Desktop and load the provided OWL implementation of CIDOC CRM:

[**Erlangen CRM / OWL**](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl): https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl

**Note:** 

> The steps shown in the live demo and the corresponding video can be reviewed in M2E2:

!?[Video Demonstration: First Steps in Protégé](../WissKIBits_Modul2/assets/Short_Protege_Intro.mp4)
 
> **Video:** The video demonstrates the first steps in Protégé and how to load Erlangen CRM / OWL.


### Step 2: Explore Relevant CIDOC CRM classes

Locate the following classes in the class hierarchy:

- **E41 Appellation**
- **E35 Title**
- **E55 Type**
- **E73 Information Object**

For each class, examine:

- its position in the hierarchy,
- its superclasses and subclasses,
- its description and annotations,
- and the information provided in its Scope Note.

**Note:**

Pay particular attention to **E41 Appellation** and **E35 Title**.

**E35 Title** is a subclass of **E41 Appellation**. The hierarchy therefore shows how a more specific concept can be placed within a more general conceptual structure.

---

### Step 3: Compare Domain Concepts with CIDOC CRM Classes

Now return to the concepts in the conceptual model.

Consider the following possible mappings:

| Domain concept | Possible CIDOC CRM class |
|---|---|
| Computer game | E73 Information Object |
| Game title | E35 Title |
| Game genre type | E55 Type |
| Game platform type | E55 Type |

For each proposed mapping, examine the relevant Scope Note.

Ask:

- What does the CIDOC CRM class describe?
- Does this meaning correspond to our domain concept?
- Which information in the Scope Note supports the mapping?
- Are alternative mappings possible?

> **Important**
>
> The suitability of a class is determined by its **meaning within the reference model**, not simply by its name.

Briefly document your reasoning for at least one mapping.

---

### Step 4: Create Domain-Specific Subclasses

Now use the modelling decisions to extend the ontology with concepts from the computer games domain.

Create the following domain-specific subclasses in Protégé:

```text
E73 Information Object
└── Computer_Game

E35 Title
└── Game_Title

E55 Type
├── Game_Genre_Type
└── Game_Platform_Type

**Example: For genre or platform**

> Computer game → **has type** → Genre / Platform type
>
> Find: **P2 has type**

Document your review.


| Source        | Property       | Target             | Intended Statement                                      |
| ------------- | -------------- | ------------------ | ------------------------------------------------------- |
| Computer_Game | P102 has title | Game_Title         | A computer game has a title.                            |
| Computer_Game | P2 has type    | Game_Genre_Type    | A computer game is assigned to a genre type.            |
| Computer_Game | P2 has type    | Game_Platform_Type | A computer game is assigned to a platform type.         |


**Note:**

> The properties will be needed in the next module, Module 3.


**Guiding questions:**

- Does the meaning of the property correspond to our domain statement?
- Are the source and target classes compatible with the domain and range?
- Does the property actually describe the relationship we want to express?

---

### Step 5: Review and document the model

Compare your result with the original model sketch:


![Concept Mind Map](../WissKIBits_Modul2/assets/Mindmap.png)


> **Figure:** The graphic shows the conceptual model sketch of a section of the example domain.


**Review the modeling**

- Are the domain-specific classes appropriately placed within the CIDOC CRM hierarchy?
- Do the properties correspond to the intended statements?
- Can the decisions be justified based on the Scope Notes?
- Can the relationships still be read as understandable statements?
- Which elements originate from CIDOC CRM, and which were added specifically for the domain?
- Write Scope Notes / Comments for the newly created domain subclasses and assign labels.


**Document the modeling decision**

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

## Sample solution

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

> **Next**
>
> In Module 3, we will take the next step towards the technical implementation of the semantic model in WissKI.
>
> We will visualise and transform the model and use it to create semantic paths and path groups in the WissKI Pathbuilder.
