<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This module is part of the how-to tutorial “Ontology-based Modeling of Research Data”. Using a video game collection as an example, the tutorial guides learners step by step through the development of a semantic data model based on CIDOC CRM and its implementation with WissKI.

title: WissKI Bits Ontology-based Modeling of Research Data

module: From Diagram to Paths – Explain and Apply

unit: Visualizing a Semantic Domain Ontology

description: The SODa how-to tutorial uses a video game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacies (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->


# WissKI Bits: Ontology-based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 3: **From Diagram to Paths – Explain and Apply**

Exercise Unit Ü1: **Visualizing a Semantic Domain Ontology**  

**Duration:** ~ 35 min.

**Learning objectives:**

Participants can...

- Name software for visualizing a domain ontology. (LZ-ID SODa\_03\_007\_0812)
- Explain software for visualizing a domain ontology. (LZ-ID LZ-ID SODa\_03\_007\_0813)
- Explain the concept of visualization. (LZ-ID SODa\_03\_007\_0851)
- Explain the benefits of visualizations. (LZ-ID SODa\_03\_007\_0852)
- Name the benefits of software for visualizing a domain ontology. (LZ-ID SODa\_03\_007\_0814) 
- Use software for visualizing a domain ontology with guidance. (LZ-ID SODa\_03\_007\_0815)
- Name the core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa\_03\_007\_0806)
- Apply the core entities (object/person/place/time/event) of an object collection. (LZ-ID SODa\_03\_007\_0811)
- Name rules for modeling a domain ontology using visualization software. (LZ-ID SODa\_03\_007\_0820)
- Apply rules for modeling a domain ontology using visualization software. (LZ-ID SODa\_03\_007\_0816)
- Apply attribute values to predefined classes of the domain ontology in visualization software. (LZ-ID SODa\_03\_007\_0817)

---

## Visualising a Domain Ontology as a Diagram with Draw.io

In this unit, the data model developed in Modules 1 and 2 is visualized as a diagram in Draw.io (Ltd2026drawio). 

The Draw.io created diagram forms the **prerequisite for the (semi-)automated pipeline** for the **WissKI Pathbuilder**.

Visualizing in Draw.io is therefore not only a **visualization exercise**, but also an **explicit modeling step** for **communicating and negotiating modeling decisions as well as enabling and promoting a shared understanding of semantic structures.**

---

## Definition

**Visualisation**

Visualisations are graphical representations of subject matter intended to facilitate understanding. 

"In the humanities, visualisations are used as illustrations, as memory aids for known subject matter, in the organisation of knowledge, and as tools for insight in the communication and generation of (new) knowledge." (Freyberg2023visual)

"Visualisations are particularly suitable for learning when the subject to be conveyed has properties that are difficult to communicate verbally." (Scheiter2021visual)

They are therefore used alongside knowledge acquisition to make content more concrete and easier to understand and to clarify structures. (Levin1987visual)

---

## Benefits of Draw.io

Draw.io is used to...

- clearly define **classes (Entities) and their relationships (Properties)**,
- make a **domain logic and its semantic relationships** visible and open to discussion,  
- develop domain models **collaboratively and transparently**,  
- check a **domain ontology before importing it into WissKI**,  
- reflect on and validate **semantic modeling decisions**.

Especially in collaborative projects, Draw.io facilitates **coordination between domain experts, data modelers, and developers**, because semantic decisions can be visually understood and documented over time.

---

## Example

The previous questions have clarified which central concepts of the example domain are relevant and how they can be classified from a domain-specific perspective.

The next step is no longer about recognizing or naming these central concepts, but about transforming this selection into a **formalised path structure**:

- How are the central concepts linked to one another in a semantically correct way?
- How does this result in a formalized path structure that can be used in the form of **paths and path groups in the WissKI Pathbuilder**?

For this purpose, the conceptual domain model is now implemented **visually and formally in Draw.io**.  


<table>
  <tr>
    <td><img src="../WissKIBits_Modul3/assets/MusterDrawio.png" width="100%"></td>
  </tr>
</table>


> **Figure:** The graphic shows how the excerpt from the example domain can be implemented in CIDOC CRM.

---

## Quiz

The following quiz is intended to reactivate the central concepts of the domain and help place the subsequent modeling task in context.

Which central concepts are relevant to the example object in the context of game features and narrative elements?


### Which Example Object is used in the Module? 

* [( )] A PC game: *Minecraft*
* [(x)] An SNES game: *The Legend of Zelda*
* [( )] A PlayStation console: *PS1*
* [( )] An arcade machine: *Pac-Man*

### Which Semantic Assumption is Explicitly made in the Example?

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

**Material:** own laptop

**Time:** 20 min.


Complete the diagram by adding the missing **nodes and edges** using suitable classes (Entities) and appropriate relationships (Properties).

Then remove all temporary placeholders `(???)`.

**Use the following classes and Properties:**

- P102\_has\_title
- P1 is identified by
- P190 has symbolic content
- mega:E41\_Game\_Character\_Name

**Download** the prepared [**Draw.io XML gap diagram**](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_B.drawio.xml).

**Note:**

Rules for visualization with Draw.io**

> - The nodes and edges must be connected correctly.
> 
> - The edge label must be connected to the edge.
> 
> - Names may, but do not have to, contain underscores.
> 
> - No individual instances are represented.
> 
> - The domain-specific subclasses from the domain ontology already created are used.
> 
> - Relationships from CIDOC CRM are reused.
> 
> - Complete paths must be created. (e.g. mega:E73\_Computer\_Game -> P102\_has\_title -> mega:E35\_Game\_Title -> P190 has symbolic content -> E62\_String)
> 
> - The central start node, each group node, and each end node are each assigned **element\_id**, **group\_name**, and **name**. (e.g. element\_id=Computer\_Game; group\_name=Computer\_Game; name=Computer\_Game)
> - The transformation can only process structures that are represented unambiguously and consistently in the source diagram.


**Resources**

> - Domain ontology: [http://games.m-e-g-a.org/game_domain.rdf](http://games.m-e-g-a.org/game_domain.rdf)
> 
> - The official CIDOC CRM documentation (.pdf file): [https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf](https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf)
>
> - Official CIDOC CRM documentation as HTML: [CIDOC CRM – Classes & Properties, Version 7.1.3](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html)
> 
> - Visual and exploratory access: [CIDOC CRM Periodic Table Version 7.1](https://remogrillo.github.io/cidoc-crm_periodic_table/?code=E1)


---

## Workflow

| Step | Action |
|---:|---|
| 1 | Download the prepared [**Draw.io XML gap diagram**](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_B.drawio.xml) |
| 2 | Import the downloaded Draw.io file into Draw.io ([here](https://app.diagrams.net/)) |
| 3 | Complete the domain ontology diagram |
| 4 | Check attribute values on the start node, each group node, and end node |
| 5 | Check the node-edge connections |

---

## Outlook

In the next step, the Draw.io diagram created is automatically converted into a WissKI Pathbuilder and the generated path structure is imported into WissKI.

---

## Bibliography

[Freyberg2023visual] Freyberg, Linda (2023) Visualisierung. In: AG Digital Humanities Theorie des Verbandes Digital Humanities im deutschsprachigen Raum e. V. (Hg.): Begriffe der Digital Humanities. Ein diskursives Glossar (= Zeitschrift für digitale Geisteswissenschaften / Working Papers, 2). DOI: 10.17175/wp_2023_014_v2

[Scheiter2021visual] Scheiter, Katharina (2021). Visualisierung. Dorsch - Lexikon der Psychologie. https://dorsch.hogrefe.com/stichwort/visualisierung

[Levin1987visual] Levin, J.R. , Anglin, G.J., & Carney, R.N. (1987). On empirically validating fuctions of pictures in prose. In D.M. Willows & H.A. Houghton (Hrsg.), The psychology of illustration. Vol. I Basic Research (S. c) New York: Springer.

[Ltd2026drawio] Draw.io LTD. (2026). draw.io. https://www.drawio.com/

