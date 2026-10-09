<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This module is part of the how-to tutorial “Ontology-Based Modelling of Research Data”. Using a computer game collection as an example, the tutorial teaches the step-by-step development of a semantic data model based on CIDOC CRM and its implementation with WissKI.

title: WissKI Bits Ontology-Based Modelling of Research Data

module: From collection to modelling decisions to diagram – understand and explain

unit: Application Example: Object Collections

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 1 (M1): **From Collection to Modelling Decisions to Diagram – Understand and Explain**

Unit 1 Exercise (UE): **Application Example: Object Collections**  

**Duration:** ~ 20 min.

**Learning Objectives:**

Participants will be able to...

- apply the core entities (object/person/place/time/event) of an object collection. (LO-ID SODa\_03\_007\_0811)
- name datatype properties of the CIDOC CRM reference model. (LO-ID SODa\_03\_007\_0808) 

---

## Objective and Scenario

In this exercise, you return to the conceptual model sketch developed during the activation exercise.

Using **"The Legend of Zelda: A Link to the Past"** as an example, you examine selected domain concepts and explore how their meanings can be represented using **CIDOC CRM**.

You will... 

- identify possible CIDOC CRM classes, 
- consult their scope notes, and 
- explain your modelling decisions.

The aim is to develop an initial, justified CIDOC CRM mapping for a small part of your model sketch. 

You are not expected to create a complete or formally implemented ontology at this stage.

> **Transfer: From Conceptual Model to CIDOC CRM**
>
> You will now further develop the model sketch created during the activation exercise of this module (M1U0A).
>
> Selected concepts and events are described using CIDOC CRM.
>
> The aim here is not to develop a complete or final CIDOC CRM model at this stage.
>
> The crucial question is:
> 
> **What do we mean by a specific term—and which CIDOC CRM class best captures that meaning?**
>
> The goal is to make, review, and justify initial modelling decisions.

---

## Starting Point: Your Model Sketch from UA0

Return to the model sketch you created during the activation exercise. It contains concepts, events, and relationships expressed in your own terminology, including any connections you marked as uncertain.

Keep your original sketch available so that you can compare your initial ideas with the modelling decisions made during this exercise.

**From Conceptual Model to a First CIDOC CRM Draft**

Your sketch describes the collection object and its context using your own terminology. The next step is to examine how selected elements could be represented using CIDOC CRM.

Now, look at the same model from a **CIDOC CRM perspective**:

- What do the identified concepts and events mean in the context of the domain?
- Which CIDOC CRM classes could represent this meaning?
- Can the relationships in your sketch be expressed using CIDOC CRM properties?
- Which **modelling decisions** remain open?

Remember: **A similar label does not necessarily imply the same meaning.**

At this stage, you are not expected to create a complete or formally implemented CIDOC CRM model. The goal is to develop **a first CIDOC CRM-informed version of your conceptual model**, which you will refine and formalise in Module 2.

---

## CIDOC CRM as a Reference Model

CIDOC CRM provides general classes and properties for describing cultural heritage information as a guide.

For modelling, this means:

Domain concept → Clarify meaning → Check CIDOC CRM → Make modelling decision

The name of a class alone is not sufficient for selection. The decisive factor is whether its scope note aligns with the intended meaning of the domain concept.

--

## Focus of this Modelling Exercise

Continue working with the three areas introduced in the activation exercise:

- **Game title**
- **Game characteristics** (e.g., genre, such as action-adventure, RPG, or platform, such as Nintendo 64, PlayStation, PC)
- **Narrative elements** (e.g., description, perspective—such as first-person or third-person—or characters like Zelda)

These areas serve as a starting point for identifying various types of **concepts and events** and formulating the **relationships** between them.

Select two elements from your model sketch that raise interesting questions about their meaning.

For example, consider whether a term refers to the game as information content, a physical copy, a designation, or a classification.

You will use CIDOC CRM to examine these distinctions.

For example, the following questions might be asked:

- What is the **title** of the game?
- To which **genre** or **platform** is it assigned?
- Which **people or organizations** were involved?
- Which **events** are relevant to the game?
- At which **locations** and **times** did these events take place?

---

## Exercise – Getting Oriented with CIDOC CRM

**Format:** Individual work or small groups (2–5 people)

**Materials:** Your model sketch from the activation exercise, paper and pen or a digital whiteboard, and access to the CIDOC CRM documentation

**Time:** 20 minutes

### Starting Point: Your Model Sketch

![Concept Mind Map](../WissKIBits_Modul1/assets/mindmap_en.png)

> **Figure:** The figure shows an example of the step-by-step conceptual analysis of a collection or research object, using the game *The Legend of Zelda: A Link to the Past* as a case study. Author's own illustration, created with ChatGPT (OpenAI), 2026.

Use your model sketch from the activation exercise as the starting point. You will now examine selected elements and explore how their meanings could be represented using CIDOC CRM.

---

### Task 1: Explore and Justify Initial CIDOC CRM Mapping

Select **two concepts or events** from your model sketch. For each selected element, follow the four steps below.

**Step 1 · Select**

Choose a concept or event from your model sketch, such as a game, person, organisation, title, genre, or production event.

Briefly clarify what the selected term refers to in your collection context.

**Step 2 · Assign**

Look for a CIDOC CRM class that could represent the intended meaning.

Use the following resources:
 
**Official CIDOC CRM documentation Version 7.1.3**: A document for authoritative definitions, scope notes, class hierarchies, and properties. [link](https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf)

**CIDOC CRM web-based HTML navigator**: The official representation of **Version 7.1.3** serves as a reference for targeted lookup. [link](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html)
 
**CIDOC CRM Periodic Table**: Use it as a visual tool for exploring classes, properties, and their relationships. [link](https://remogrillo.github.io/cidoc-crm_periodic_table)

**Examples of possible starting points:**
 
- E73 Information Object → Game as information content
- E22 Human-Made Object → Physical copy
- E21 Person → Participating person
- E74 Group → Organization or group
- E12 Production → Production event
- E35 Title → Title
- E42 Identifier → Identifier
- E55 Type → Controlled classification

**Step 3 · Review**

Read the scope note of the selected CIDOC CRM class.

Ask yourself:

- Does the class describe what I mean by my term?
- Does the definition support my proposed assignment?
- Are there alternative classes that might be more appropriate?

**Step 4 · Justify**

Add the proposed CIDOC CRM class to your model sketch and briefly explain your choice.

Mark uncertain assignments with a question mark (?) and note what remains unclear.

**Remember:** The goal is not to assign as many CIDOC CRM classes as possible. What matters is whether you can explain and justify a small number of modelling decisions.

**Mini-Demo: CIDOC CRM as a Building-Block System**

The following classes may provide useful starting points for your exploration.

| CIDOC CRM class (Entity) | Meaning in the example |
|--------------------------|------------------------|
| **E73 Information Object** | Game as identifiable information content |
| **E22 Human-Made Object** | Physical copy (cartridge, disc, box…) |
| **E21 Person** | Participating person / contributor (designer, musician) |
| **E74 Group** | Organization or group (development studio, publisher, team) |
| **E12 Production** | Production / (possibly publication as an event) |
| **E42 Identifier** | Identifiers (inventory numbers, product codes …) |
| **E35 Title** | Title of the object as a separate entity |
| **E42 Appellation** | Name by which something is identified or designated |
| **E55 Type** | Controlled characteristics (e.g. genre, platform) |

These are possible starting points, not predefined solutions. Always check the relevant scope notes before deciding whether a class is suitable.

--- 

### Task 2: Compare and Discuss Modelling Decisions

Compare your proposed CIDOC CRM mappings with those of other participants or with the example below.

![Concept Mind Map](../WissKIBits_Modul1/assets/Mindmap.png)

> **Figure:** Example of a model sketch for **The Legend of Zelda: A Link to the Past.** The illustration provides a starting point for discussing modelling decisions rather than a single correct solution.

**Discuss the following questions:**

- Did you select the same CIDOC CRM classes for similar terms?
- If your choices differ, how did you interpret the meaning of the original term?
- How did the scope notes help you make your decisions?
- Which assignments remain uncertain?
- Would you revise any concepts or relationships in your original model sketch?

Revise your sketch where necessary and record any open questions.

**Key Takeaway: Modelling Meaning**

Semantic modelling involves more than finding classes with similar names.

A suitable CIDOC CRM mapping depends on the **intended meaning of a term**, the **definitions of the selected classes**, and **the relationships you want to express**.

At this stage, you are developing a first CIDOC-CRM-informed version of your conceptual model — not a complete formal ontology.

---

### Result

You have revisited your initial conceptual model sketch and examined selected elements using CIDOC CRM.

**Your revised sketch now contains:**

- relevant domain concepts and events,
- initial mappings of selected elements to CIDOC-CRM classes,
- explicit semantic relationships,
- brief justifications based on the intended meaning and the corresponding scope notes,
- notes on uncertain or unresolved modelling decisions.

This is a first CIDOC-CRM-informed version of your conceptual model, not yet a complete formal ontology.

In Module 2, you will review and refine these decisions and begin formalising selected parts of the model using Protégé.

---

## From Designation to Appellation

In our initial model sketch, you can state simply:

> Game → has a designation → “The Legend of Zelda: A Link to the Past”

CIDOC CRM allows to distinguish more precisely between different forms of designation:

 **E41 Appellation** represents a designation used to identify or refer to an instance of a CRM class. 
 
 Two more specific classes are particularly relevant here:

- **E35 Title:** A title assigned to or used for an entity, such as the title of a game.
- **E42 Identifier:** An identifier used to distinguish an entity within a particular identification context, such as an inventory number.

Both E35 Title and E42 Identifier are subclasses of E41 Appellation, but they express different kinds of designation.

**Modelling Example · Not All Designations Are the Same**

Initial model sketch: 

Game  →  has designation  →  "TheLegend of Zelda: A Link to the Past"

**CIDOC CRM distinction:** 

- E41 Appellation → general designation
- E35 Title → specific form of an appellation: a title
- E42 Identifier → specific form of an appellation: an identifier

**Key Point:** Similar labels do not necessarily express the same meaning. Always check the CIDOC CRM scope note before selecting a class.

In this exercise, the aim is to recognise and justify these distinctions. The technical representation of appellations and their literal values will be addressed in later modules.

---

## Outlook

In this exercise, you revisited your conceptual model sketch and explored how selected concepts and events can be represented using CIDOC CRM.

By consulting scope notes and discussing possible mappings, you have taken a first step towards a more precise semantic model.

> **Next**
>
> You have extended your conceptual model sketch with initial CIDOC CRM mappings and justified modelling decisions.
>
> Module 2: You will review and refine these decisions and formalise selected parts of the model as a machine-readable OWL ontology using Protégé.
>
> Module 3: You will use the semantic model to prepare and import a WissKI Pathbuilder configuration.
>
> Your model is therefore a starting point for further development, not yet a complete formal ontology.

---

## Bibliography

[SIG2024cidoc] CIDOC CRM Special Interest Group. (2024). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. https://cidoc-crm.org/Version/version-7.1.3

[SIG2024cidocb] CIDOC CRM Special Interest Group. (2024). Classes & Properties Declarations of CIDOC-CRM version: 7.1.3. https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html

