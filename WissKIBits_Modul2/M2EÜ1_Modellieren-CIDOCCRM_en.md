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

unit: Semantic Modeling with CIDOC CRM

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to-Tutorial

-->
```
# SODa WissKI Bits: Ontology-Based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE**

Module 2: **Modeling with CIDOC CRM -- understand and apply**

Exercise Unit Ü1: **Semantic Modeling with CIDOC CRM**

**Duration:** \~ 55 min.

**Learning objectives:**

Participants can...

-   apply an ontology for describing resources. (LO-ID 03_007_0780)
-   apply methods for developing ontologies. (LO-ID SODa_03_007_0854)
-   apply a workflow for semantic modeling as data documentation. (LO-ID
    SODa_03_001_0627)
-   apply methods for modeling a domain ontology using the CIDOC CRM
    reference model under guidance. (LO-ID SODa_03_001_0786a)
-   apply software for creating ontologies. (LO-ID SODa_03_007_0840)
-   apply Erlangen CRM / OWL as an OWL implementation of the CIDOC CRM
    reference model. (LO-ID SODa_03_007_0855)
-   apply Scope Notes of the CIDOC CRM reference model for describing
    resources. (LO-ID SODa_03_007_0780a)

------------------------------------------------------------------------

## Objective and scenario

This is a practical unit. The starting point is the conceptual model of
the computer games domain developed in Module 1.

Using **"The Legend of Zelda: A Link to the Past"** as an example, we
examine how this conceptual model sketch is gradually transformed into a
**formal ontology structure**.

The necessary steps are:

-   comparing selected concepts from the domain model with classes of
    **CIDOC CRM**,
-   reviewing modeling decisions based on **definitions and Scope
    Notes**,
-   creating domain-specific concepts as **subclasses** in Protégé,
-   examining properties in CIDOC CRM for the relationships between
    these concepts.

The focus is on the **workflow of formal modeling**.

At the end, a formally implemented section of the domain model is
available as an **OWL ontology**.

------------------------------------------------------------------------

## Starting point: Model from Module 1

In Module 1, a model sketch was developed describing central concepts
and relationships of the computer games domain:

![Concept mind map](../WissKIBits_Modul2/assets/Mindmap.png)

> **Figure:** The graphic shows the conceptual model sketch of a section
> of the example domain.

The collected domain terms will now be formalized step by step using
CIDOC CRM and Protégé.

For this exercise, the following may be selected, among others:

> Computer game → **has title** → Game title
>
> Computer game → **has type** → Genre
>
> Computer game → **has type** → Platform type

We distinguish three levels:

  ------------------------------------------------------------------------
  Level                  Example
  ---------------------- -------------------------------------------------
  Domain statement       Game has title

  Semantic modeling      E73 Information Object -- P102 has title -- E35
                         Title

  Formal OWL structure   `Computer_Game SubClassOf P102 some Game_Title`
  ------------------------------------------------------------------------

------------------------------------------------------------------------

## Focus of this modeling exercise

The focus is on four fundamental work steps:

**Step 1: Load the ontology and explore its structure**

**Step 2: Select and justify CIDOC CRM classes**

**Step 3: Create domain-specific subclasses**

**Step 4: Review the model and document decisions**

------------------------------------------------------------------------

## Example: From the model sketch to the ontology

In Module 1, the initial domain statement was:

> Game → has title → Title

For semantic modeling, we now examine which elements of CIDOC CRM can
express this statement.

One possible starting point is:

  Element             possible CIDOC CRM mapping
  ------------------- ----------------------------
  **Computer game**   E73 Information Object
  **Game title**      E35 Title
  **Relationship**    P102 has title

At the same time, **E35 Title** is a more specific form of **E41
Appellation**. The class hierarchy therefore makes visible that a title
is a particular form of an appellation.

------------------------------------------------------------------------

## Exercise -- Implementing the model in Protégé

**Working format:** Individual work or teams (2--4 people)

**Material:** Computer with Protégé Desktop, provided Erlangen CRM OWL
file, model sketch from Module 1 \[Link\]

**Time:** \~ 45 min.

**Task: Recreate a section of the domain model in Protégé**

**Prerequisite:**

To work with Protégé, use the [**official Protégé
website**](https://protege.stanford.edu/) to set up either

-   the desktop application ([**Protégé
    Desktop**](https://protege.stanford.edu/software/#desktop-protege))
    or
-   an account for the web-based editor
    ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege)).

**Note:**

> A time window of approximately 5 minutes is allocated for setup.

------------------------------------------------------------------------

### Step 1: Load Erlangen CRM and explore its structure

Open Protégé Desktop and load the provided OWL implementation of CIDOC
CRM:

[**Erlangen CRM / OWL**](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl):
https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl

**Note:**

> The steps shown in the live demo and the corresponding video can be
> reviewed in M2E2:

!?[Video demonstration: First steps in Protégé](../WissKIBits_Modul2/assets/Short_Protege_Intro.mp4)

> **Video:** The video shows the first steps in Protégé and how to load
> ERLANGEN CRM / OWL.

Then briefly explore the structure of the ontology and search the class
hierarchy for:

-   **E41 Appellation**
-   **E35 Title**
-   **E55 Type**
-   **E73 Information Object**

In particular, examine:

-   Where is the class located in the hierarchy?
-   Which superclasses and subclasses are visible?
-   Which description or annotation is provided?
-   Which properties are used for the class?

**Note:**

> Pay particular attention to **E41 Appellation** and **E35 Title**: E35
> Title is a subclass of E41 Appellation. This shows how more general
> and more specific concepts are connected within an ontology.

------------------------------------------------------------------------

### Step 2: Select and review suitable CIDOC CRM classes

In Protégé, find the appropriate class for the domain term and review
the Scope Note of the class.

Justify your selection.

**Example**

> **E73 Information Object**
>
> **E35 Title**
>
> **E55 Type**

Assign a suitable CIDOC CRM class to each domain term and justify your
decision.

  Domain term          possible CIDOC CRM class
  -------------------- --------------------------
  Computer Game        E73 Information Object
  Game Title           E35 Title
  Game Genre Type      E55 Type
  Game Platform Type   E55 Type

**Justifications**

Computer Game -- E73 Information Object

\[\[\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\]\]

Game Title -- E35 Title

\[\[\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\]\]

Game Genre Type -- E55 Type

\[\[\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\]\]

Game Platform Type -- E55 Type

\[\[\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\]\]

**Note:**

> It is not the name of a class that determines its suitability, but its
> meaning in the reference model.

**Guiding questions for reviewing the class may include**

-   What does the CIDOC CRM class describe?
-   Does this meaning correspond to our domain term?
-   Which statement in the Scope Note supports your decision?
-   Are alternative mappings conceivable?

------------------------------------------------------------------------

### Step 3: Create domain-specific subclasses

Now create the domain-specific subclasses in Protégé.

The subclasses should be placed under the previously selected CIDOC CRM
classes:

``` text
E73 Information Object
└── Computer_Game

E35 Title
└── Game_Title

E55 Type
├── Game_Genre_Type
└── Game_Platform_Type
```

Then review the class hierarchy.

In Protégé, find suitable relationships for the selected subclasses and
examine the descriptions of the properties.

**Example: For the title**

> Computer game → **has title** → Game title
>
> Search for **P102 has title**


**Example: For genre or platform**

> Computer game → **has type** → Genre / Platform type
>
> Search for: **P2 has type**

Document your review:

  --------------------------------------------------------------------------------------
  Source          Property   Target               Intended statement
  --------------- ---------- -------------------- --------------------------------------
  Computer_Game   P102 has   Game_Title           A computer game has a title.
                  title                           

  Computer_Game   P2 has     Game_Genre_Type      A computer game is assigned to a genre
                  type                            type.

  Computer_Game   P2 has     Game_Platform_Type   A computer game is assigned to a
                  type                            platform type.
  --------------------------------------------------------------------------------------

**Note:**

> The properties will be needed in the next Module 3.

**Guiding questions:**

-   Does the meaning of the property correspond to our domain statement?
-   Are the source and target classes compatible with the domain and
    range?
-   Does the property actually describe the relationship we want to
    express?

------------------------------------------------------------------------

### Step 5: Review and document the model

Compare your result with the original model sketch:

![Concept mind map](../WissKIBits_Modul2/assets/Mindmap.png)

> **Figure:** The graphic shows the conceptual model sketch of a section
> of the example domain.

**Review the modeling**

-   Are the domain-specific classes appropriately placed in the CIDOC
    CRM hierarchy?
-   Do the properties correspond to the intended statement?
-   Can the decisions be justified using the Scope Notes?
-   Can the relationships still be read as understandable statements?
-   Which elements originate from CIDOC CRM and which were added for the
    domain?
-   Write Scope Notes / Comments for the newly created domain subclasses
    and assign labels.

**Document a modeling decision**

Document your decision for **one** mapping:

  Question                                       Answer
  ---------------------------------------------- --------
  Which domain term are we modeling?             
  Which CIDOC CRM class or property do we use?   
  What meaning do we want to express?            
  What does the Scope Note say about this?       
  Why do we consider the mapping suitable?       

**Note:**

> The aim is not to find a single "correct" solution. What matters is
> that the modeling decision is comprehensible from a domain perspective
> and compatible with the reference model being used.

------------------------------------------------------------------------

## Sample solution

The existing domain ontology for computer games can be used as a sample:

[**Game Domain Ontology --
RDF**](http://games.m-e-g-a.org/game_domain.rdf)

Compare your own modeling with the sample **only after completing the
task**. The sample should be understood as a modeling proposal, not as
the only possible solution.

**Note**

> Pay particular attention to:
>
> -   the placement of domain-specific classes,
> -   the reuse of CIDOC CRM properties,
> -   and possible differences from your own modeling decisions.

------------------------------------------------------------------------

## Result

At the end of this exercise, a small formally implemented section of the
**computer games** domain model is available.

You have:

-   created domain-specific concepts as **subclasses** of CIDOC CRM,
-   and justified a modeling decision using a **Scope Note**.

Then save the extended ontology as an **OWL file**.

**Note:**

> The ontology remains a model excerpt.
>
> It does not represent the entire computer games domain, but documents,
> by way of example, the path from a domain-specific model sketch to a
> machine-readable ontology structure.

------------------------------------------------------------------------

## Outlook

With this exercise, the domain model developed in Module 1 has been
**formally implemented in Protégé for the first time**.

Three levels have been connected:

> **domain statement → CIDOC CRM modeling → OWL formalization**

The saved OWL file forms the basis for **Module 3**.
