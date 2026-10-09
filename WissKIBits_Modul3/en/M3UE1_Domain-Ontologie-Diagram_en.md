<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This module is part of the how-to tutorial “Ontology-Based Modelling of Research Data”. Using a computer game collection as an example, the tutorial guides learners step by step through the development of a semantic data model based on CIDOC CRM and its implementation with WissKI.

title: WissKI Bits Ontology-Based Modelling of Research Data

module: From Diagram to Paths – Explain and Apply

unit: Visualising a Semantic Domain Ontology

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: SODa How-to Tutorial

-->


# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 3 (M3): **From Diagram to Paths – Explain and Apply**

Unit Exercise (UE1): **Visualising a Semantic Domain Ontology**  

**Duration:** ~ 35 min.

**Learning Objectives:**

Participants will be able to...

- Name software for visualising a domain ontology. (LZ-ID SODa\_03\_007\_0812)
- Explain software for visualising a domain ontology. (LZ-ID LZ-ID SODa\_03\_007\_0813)
- Explain the concept of visualisation. (LZ-ID SODa\_03\_007\_0851)
- Explain the benefits of visualisations. (LZ-ID SODa\_03\_007\_0852)
- Name the benefits of software for visualising a domain ontology. (LZ-ID SODa\_03\_007\_0814) 
- Use software for visualising a domain ontology with guidance. (LZ-ID SODa\_03\_007\_0815)
- Name the core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa\_03\_007\_0806)
- Apply the core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa\_03\_007\_0811)
- Name rules for modelling a domain ontology using visualisation software. (LZ-ID SODa\_03\_007\_0820)
- Apply rules for modelling a domain ontology using visualisation software. (LZ-ID SODa\_03\_007\_0816)
- Apply attribute values to predefined classes of the domain ontology in visualisation software. (LZ-ID SODa\_03\_007\_0817)

---

## Visualising a Domain Ontology as a Diagram with Draw.io

In this unit, you will use **Draw.io** to visualise selected classes and properties from the domain ontology developed in Modules 1 and 2 (Ltd2026drawio). 

The diagram helps you examine semantic relationships, discuss modelling decisions, and develop a shared understanding of the ontology structure.

The Draw.io created diagram forms the **prerequisite for the (semi-)automated pipeline** for the **WissKI Pathbuilder**.

Visualising in Draw.io is therefore not only a **visualisation exercise**, but also an **explicit modelling step** for **communicating and negotiating modelling decisions as well as enabling and promoting a shared understanding of semantic structures.**

---

## Definition

**Visualisation**

Visualisation refers to the graphical representation of information, concepts, or relationships to support understanding.

"In the humanities, visualisations are used as illustrations, as memory aids for known subject matter, in the organisation of knowledge, and as tools for insight in the communication and generation of (new) knowledge." (Freyberg2023visual)

"Visualisations are particularly suitable for learning when the subject to be conveyed has properties that are difficult to communicate verbally." (Scheiter2021visual)

Visualisations can therefore support knowledge acquisition by making abstract concepts more concrete and revealing structures and relationships that may be difficult to explain through text alone. (Levin1987visual)

---

## Benefits of Draw.io

Draw.io helps you to:

- visualise selected **ontology classes and properties** and their relationships,
- make semantic structures easier to understand and discuss,
- communicate and document **modelling decisions** collaboratively,
- check whether the diagram **reflects the intended ontology structure**, and
- prepare the selected semantic paths for transformation into WissKI Pathbuilder XML.

Especially in collaborative projects, visual diagrams support communication between **domain experts, data modellers, and developers.**

---

## Example

In Modules 1 and 2, you identified central concepts of the computer games domain and represented selected concepts as domain-specific subclasses of CIDOC CRM classes.

The next step is to visualise how these classes are connected through existing CIDOC CRM properties. The resulting diagram illustrates semantic paths that can later be transformed into paths and path groups in the WissKI Pathbuilder.

<table>
  <tr>
    <td><img src="../WissKIBits_Modul3/assets/MusterDrawio.png" width="100%"></td>
  </tr>
</table>


> **Figure:** Example of a Draw.io diagram showing selected classes and CIDOC CRM properties used to represent semantic paths in the computer games domain.

---

## Quiz

Before working with the Draw.io diagram, review the example object and the central concepts of the computer games domain.

The following questions help you recall the concepts and classifications used in the modelling exercise.


### Which Example Object Is Used in This Tutorial?

* [( )] A PC game: *Minecraft*
* [(x)] An SNES game: *The Legend of Zelda: A Link to the Past*
* [( )] A PlayStation console: *PS1*
* [( )] An arcade machine: *Pac-Man*

### Which Title Is Assigned to the Example Game?

* [( )] The game is “Open World”
* [(x)] The title of the object is defined as *The Legend of Zelda: A Link to the Past*
* [( )] The game is a “Collector’s Edition”
* [( )] The platform is “PC”

### Which of the following Concepts are **Game Features**?

* [[ ]] Perspective
* [[X]] Genre
* [[X]] Edition
* [[X]] Platform
* [[ ]] Manufacturer

### Which of the following Concepts are **Narrative Elements**?

* [[X]] Perspective
* [[X]] Game description
* [[X]] Characters
* [[ ]] Platform
* [[ ]] Genre

----

## Task 

**Work format:** Individual work   

**Material:** Computer with internet access

**Time:** ~ 20 min.


In this exercise, you will complete a prepared Draw.io diagram using selected classes and properties from the computer games domain ontology.

**Download** the prepared [**Draw.io XML gap diagram**](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_B.drawio.xml) and open it in Draw.io.

Add the missing nodes and edges, connect them correctly, and replace all temporary placeholders marked `(???)`.

**Use the following ontology elements where required:**

- P102\_has\_title
- P1 is identified by
- P190 has symbolic content
- mega:E41\_Game\_Character\_Name

Your completed diagram should represent connected semantic paths and contain the attribute values required for the subsequent XML transformation.

**Modelling Rules and Checks**

> - Use the domain-specific subclasses already defined in the domain ontology.
>
> - Reuse existing CIDOC CRM properties to connect the classes.
> 
> - The edge label must be connected to the edge.
> 
> - Do not introduce individual instances into the diagram.
> 
> - Ensure that all nodes and edges are connected correctly.
> 
> - Ensure that each property label is attached to its corresponding edge.
> 
> - Use consistent class and property names. Underscores may be used but are not mandatory.#
> 
> - Represent complete semantic paths rather than isolated classes or properties.


**For example:**

mega:E73_Computer_Game → P102_has_title → mega:E35_Game_Title → P190 has symbolic content → E62_String


**Check the required attribute values**

The diagram must also contain the attribute values needed for conversion into WissKI Pathbuilder XML.

For the central start node and each group node, check the attributes:
 
- **element\_id**, 
- **group\_name**, and 
- **name**. 

For example:

- element\_id = Computer\_Game; 
- group\_name = Computer\_Game; 
- name = Computer\_Game

Check the required attributes of the end nodes against the prepared diagram and the transformation requirements.

The transformation depends on consistent connections, labels, and attribute values in the source diagram.

**Resources**

- Computer games domain ontology: [http://games.m-e-g-a.org/game_domain.rdf](http://games.m-e-g-a.org/game_domain.rdf)
- CIDOC CRM documentation, Version 7.1.3 (PDF): [https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf](https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf)
- CIDOC CRM documentation, Version 7.1.3 (HTML): [https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html]
- CIDOC CRM Periodic Table, Version 7.1 [https://remogrillo.github.io/cidoc-crm_periodic_table/?code=E1]

---

## Workflow

| Step | Action |
|---:|---|
| 1 | Download the prepared [**Draw.io XML gap diagram**](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_B.drawio.xml) |
| 2 | Open the downloaded file in Draw.io ([here](https://app.diagrams.net/)) |
| 3 | Complete the missing nodes and edges using the specified ontology classes and properties.|
| 4 | Remove all (???) placeholders and check the required attribute values. |
| 5 | Check that the semantic paths are complete and that all nodes, edges, and property labels are connected correctly. |
| 6 | Save the completed Draw.io diagram for the next unit. |

---

## Outlook

> **Next**
>
> In the next unit, you will export the completed Draw.io diagram as XML, transform it into WissKI Pathbuilder XML, and import the generated paths and path groups into WissKI.

---

## Bibliography

[Freyberg2023visual] Freyberg, Linda (2023) Visualisierung. In: AG Digital Humanities Theorie des Verbandes Digital Humanities im deutschsprachigen Raum e. V. (Hg.): Begriffe der Digital Humanities. Ein diskursives Glossar (= Zeitschrift für digitale Geisteswissenschaften / Working Papers, 2). DOI: 10.17175/wp_2023_014_v2

[Scheiter2021visual] Scheiter, Katharina (2021). Visualisierung. Dorsch - Lexikon der Psychologie. https://dorsch.hogrefe.com/stichwort/visualisierung

[Levin1987visual] Levin, J.R. , Anglin, G.J., & Carney, R.N. (1987). On empirically validating functions of pictures in prose. In D.M. Willows & H.A. Houghton (Hrsg.), The psychology of illustration. Vol. I Basic Research (S. c) New York: Springer.

[Ltd2026drawio] Draw.io LTD. (2026). draw.io. https://www.drawio.com/

