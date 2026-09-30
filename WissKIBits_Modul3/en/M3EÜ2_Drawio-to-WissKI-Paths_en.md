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

unit: Transforming Semantic Models into WissKI Paths

description: The SODa how-to tutorial uses a video game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacies (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->


# WissKI Bits: Ontology-based Modeling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 3: **From Diagram to Paths – Explain and Apply**

Exercise Unit E3: **Transforming Semantic Models into WissKI Paths**  

**Duration:** ~ 45 min.

**Learning objectives:**

Participants can...

- Explain WissKI Pathbuilder as a tool for defining an ontology structure. (LZ-ID SODa\_03\_007\_0804)
- With guidance, perform data conversion from visualization software into a reusable file format. (LZ-ID SODa\_02\_005\_0298a)
- With guidance, use WissKI Pathbuilder as a tool for importing a domain-specific ontology structure (Pathbuilder XML file into the WissKI Pathbuilder). (LZ-ID SODa\_03\_007\_0818)
- With guidance, analyze the imported domain-specific ontology structure in the WissKI Pathbuilder. (LZ-ID SODa\_03\_007\_0819)
- Name a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion. (LZ-ID SODa\_02\_005\_0317) 
- With guidance, use a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion. (LZ-ID SODa\_02\_005\_0318)

---

## Objective and Scenario

The starting point for this practical unit is the **Draw.io diagram of the video game domain completed in Unit 1**.

The diagram is now processed technically: Using the **gnm-service**, the Draw.io XML file is transformed into a **WissKI Pathbuilder XML file**. This file is then imported into WissKI and examined in the **Pathbuilder**.

> **Draw.io diagram → gnm-service → Pathbuilder XML → WissKI Pathbuilder**

---

## From the Semantic Model to the Pathbuilder

In the previous unit, the domain model formalized with CIDOC CRM was visualized as a Draw.io diagram.

**Example:**

> A relationship from the model can be represented as follows:
>
> Computer Game → P102 has title → Game Title

In the WissKI Pathbuilder, such a sequence of classes (Entities) and relationships (Properties) becomes a **semantic path**.

We distinguish three levels:

| Level                         | Example                                    |
| ----------------------------- | ------------------------------------------- |
| **Semantic model**       | Computer Game – P102 has title – Game Title |
| **Transformation format**     | Draw.io XML → Pathbuilder XML               |
| **Implementation in WissKI** | Group and semantic path in the Pathbuilder |

The Pathbuilder thus provides the connection between the ontology structure and the data structures that WissKI uses for data entry, storage, and querying. It organizes the model into groups and paths and can generate Drupal bundles and fields from them. (wisski2021pathbuilder)

---

## Focus of this Practical Unit

The focus is on five fundamental work steps:

- **Step 1: Transform Draw.io XML into Pathbuilder XML**

- **Step 2: Check or load the ontology in WissKI**

- **Step 3: Create a Pathbuilder and import XML**

- **Step 4: Analyze the generated groups and paths**

---

## The WissKI Pathbuilder

The Pathbuilder represents the **implementation layer of WissKI**.

The **WissKI Pathbuilder** connects the ontology being used with the concrete data structure in WissKI.

Semantic relationship chains consisting of **classes (Entities) and Properties** are represented as **paths**. Related paths can be organized into **groups**.

A Pathbuilder organizes in particular

- **paths** that represent classes and Properties as semantic relationship chains,
- **groups** that structure related paths according to their subject matter,
- and the assignment of these structures to WissKI or Drupal structures.

On this basis, **bundles and input fields** can later be generated for data entry.

> **Note:** The Pathbuilder does not define the ontology itself. It uses classes and Properties from the loaded ontology to define the groups and semantic paths required for WissKI.

<table>
  <tr>
    <td><img src="../WissKIBits_Modul3/assets/pathbuilder.jpg" alt="WissKI Pathbuilder" width="75%"></td>
  </tr>
</table>

> **Figure:** The graphic shows a screenshot of the WissKI Pathbuilder.

---

## The Gnm-Service as a Transformation Tool

The **“Draw.io diagrams to WissKI pathbuilders”** web service supports the transformation of a semantic Draw.io diagram into a **WissKI Pathbuilder XML file**.

The service thus provides a technical interface between graphical modeling and implementation of the model in the WissKI Pathbuilder.

The basic transformation process is:

**Draw.io diagram → Draw.io XML → gnm-service → Pathbuilder XML → WissKI Pathbuilder**

The transformation enables:

- **reuse** of the semantic model already developed,
- **reduction of manual transfer work**,
- and a traceable connection between the diagram and the Pathbuilder.

**Note:** 

> Automatic transformation does not replace domain-specific validation. After import, the generated groups and paths should be compared with the source diagram.

---

## Task

**Work format:** Individual work 

**Material:** Laptop, Draw.io XML file, access to a WissKI instance

**Time:** 20 min.

**Task:**

Complete the prepared semantic Draw.io diagram, transform it into a WissKI Pathbuilder XML file, import it into WissKI, and check the generated path structure.

**Workflow from the domain ontology diagram to WissKI paths**

The following overview shows the individual steps used to turn the diagram into a usable WissKI Pathbuilder.

| Step | Action                                |
| -------- | ------------------------------------ |
| 1        | Export the Draw.io model as an .xml file.  |
| 2        | Load the Draw.io.xml file into the WissKI Pathbuilder web service. |
| 3        | Check whether the ontology structure is valid. |
| 4        | Generate the WissKI Pathbuilder .xml file. |
| 5        | Import the Pathbuilder .xml file into WissKI.   |
| 6        | Check the path structure. |

This process bridges the gap between modeling a domain ontology and creating the Pathbuilder in WissKI by automatically converting the semantic Draw.io model into WissKI paths via a transformation pipeline.

---

### Step 1: Transform the Draw.io Diagram

**Open** the web service:

[**Draw.io diagrams to WissKI pathbuilders**](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/)

Proceed as follows:

- Export or use the prepared **Draw.io XML file**.
- Upload the file under **Upload draw.io XML file for conversion to WissKI Pathbuilder XML**.
- Start the transformation.
- Check the response from the web service.
- Open or copy the address of the generated **Pathbuilder XML file**.

**Note:**

> The transformation thus represents the technical intermediate step:

> Draw.io XML → Web service: Draw.io diagrams to WissKI pathbuilders → WissKI Pathbuilder XML


**Prompt question**

> What information from the diagram must be preserved so that a semantically meaningful Pathbuilder can be generated from it?

Write down a short answer.

---

### Step 2: Check the Ontology in WissKI

The classes and Properties used in the Pathbuilder must be available to WissKI through the ontology. The Pathbuilder uses these elements to construct semantic paths.

**Log in** to the prepared **WissKI instance**. 

**First check** whether the ontology required for the domain model is already available: 

- Navigate to **WissKI → Configuration → WissKI Ontology**
- Check the adapter being used and the loaded ontology.
- If the domain ontology has not yet been loaded, select the designated WissKI adapter, enter the address of the **Games Ontology**, and load the ontology.

**Games ontology:**

[http://games.m-e-g-a.org/game_domain.rdf](http://games.m-e-g-a.org/game_domain.rdf)


**Note:**

> If no WissKI instances are provided as part of the tutorial, a provided WissKI environment in the SODa Semantic Co-Working Space (SCS) can be used for the tutorial.
>
> Use is free of charge.
>
> Please register free of charge here: https://manager.scs.sammlungen.io/user/register
>
> Once your account has been activated, you can log in to the SCS and access the WissKI environment required for the tutorial.
>
> You do not need to set up your own WissKI installation for the tutorial. The SCS provides the required technical environment.

---

### Step 3: Create a new Pathbuilder and Import XML

**Navigate** to: **Configuration → Pathbuilders**

**Create** a new Pathbuilder:

- select **Add Pathbuilder**,
- assign a unique name,
- select the designated adapter,
- save the Pathbuilder.

Then **open** the newly created Pathbuilder.

In the **Pathbuilder Definition Import** section:

- paste the previously copied address of the generated Pathbuilder XML file,
- start the import,
- wait until the Pathbuilder structure is displayed.

**Note:** 

> Check the imported structure first before generating any additional bundles or fields.

--- 

### Step 4: Examine the Imported Pathbuilder

**Examine** the generated **Pathbuilder** and compare it with the source diagram.

Use the following path as an example:

> `Computer_Game → P102 has title → Game_Title`

**Question 1: Which group does the path belong to?**

[(X)] Computer Game  
[( )] Game Title  
[( )] The path does not belong to any group.

---

**Question 2: Which property connects the source and target classes?**

[[P102 has title]]

---

**Question 3: Does the path correspond to the source diagram?**

[(X)] Yes  
[( )] No


Compare the source class, Property, and target class with the corresponding relationship in the Draw.io diagram.

---

**Finally:**

Also look at the other imported paths.

- Are the expected groups and paths present?
- Do you notice any missing or unexpected paths?

**Prompt question:**

> What advantage does automatic transformation have over creating the paths manually?

---

## Summary

In this practical unit, the **Draw.io diagram** completed in Unit 1 was transformed into a **Pathbuilder XML file** using the gnm-service and then imported into WissKI.

Three successive representations were used:

| Representation | Function |
|---|---|
| **Draw.io diagram** | Visualization of the semantic domain model |
| **Pathbuilder XML** | Transformation and exchange format |
| **WissKI Pathbuilder** | Organization of ontology relationships as groups and semantic paths |

> **Draw.io diagram → Pathbuilder XML → WissKI Pathbuilder**

At the end of this exercise, there is an **imported WissKI Pathbuilder based on the semantic domain model**.

---

## Summary

In this practical unit, a semantic Draw.io diagram was transformed step by step into a **WissKI Pathbuilder structure**.

Three tools or representations were used:

| Tool / Representation | Function |
|---|---|
| **Draw.io diagram** | Visualization of the semantic domain model |
| **gnm-service** | Transformation of the diagram into a Pathbuilder XML file |
| **WissKI Pathbuilder** | Implementation of ontology relationships as groups and semantic paths |

The result is an **imported and checked WissKI Pathbuilder** based on the semantic domain model.

This traces the transition from semantic modeling to technical implementation in WissKI:

> **semantic model → Draw.io diagram → Pathbuilder XML → WissKI Pathbuilder**

---

## Outlook

In the next step, the imported groups and paths are made usable for **data entry in WissKI**.

For this purpose, the Pathbuilder is further configured and then the function

> **Save and generate bundles and fields**

is used.

The semantic paths are thus used to create **bundles and fields** that can be used for data entry and display in WissKI.

> **Ontology → Pathbuilder → Bundles and fields → Data entry**

---

## Resources

- [Draw.io diagrams to WissKI pathbuilders](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/)
- [Erlangen CRM](http://erlangen-crm.org/240307/)
- [Games Ontology](http://games.m-e-g-a.org/game_domain.rdf)
- [Example Pathbuilder XML](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput.xml)
- [WissKI Pathbuilder Documentation](https://wiss-ki.eu/documentation/data-modeling/pathbuilder)

---

## Bibliography

[wisski2012pathbuilder] WissKI Pathbuilder (n.d.) https://wiss-ki.eu/documentation/data-modeling/pathbuilder?utm_source=chatgpt.com

