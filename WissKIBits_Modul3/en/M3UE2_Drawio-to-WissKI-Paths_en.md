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

unit: Transforming Semantic Models into WissKI Paths

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modelling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: How-to-Tutorial

-->


# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

Module 3 (M3): **From Diagram to Paths – Explain and Apply**

Unit Exercise (UE2): **Transforming Semantic Models into WissKI Paths**  

**Duration:** ~ 45 min.

**Learning Objectives:**

Participants will be able to...

- Explain WissKI Pathbuilder as a tool for defining an ontology structure. (LZ-ID SODa\_03\_007\_0804) Hinweis: Vielleicht lieber "configuring an ontology-based path structures" ? Vorschlag: Explain the WissKI Pathbuilder as a tool for configuring ontology-based paths and path groups.

- With guidance, perform data conversion from visualisation software into a reusable file format. (LZ-ID SODa\_02\_005\_0298a)
Vorschlag: With guidance, convert a diagram created with visualisation software into a reusable file format. 

- With guidance, use WissKI Pathbuilder as a tool for importing a domain-specific ontology structure (Pathbuilder XML file into the WissKI Pathbuilder). (LZ-ID SODa\_03\_007\_0818)
Vorschlag: With guidance, import a Pathbuilder XML configuration into the WissKI Pathbuilder.

- With guidance, analyse the imported domain-specific ontology structure in the WissKI Pathbuilder. (LZ-ID SODa\_03\_007\_0819)
Vorschlag: With guidance, examine the imported paths and path groups in the WissKI Pathbuilder.

- Name a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion. (LZ-ID SODa\_02\_005\_0317) 
Vorschlag: Name the gnm-service Draw.io diagrams to WissKI pathbuilders as a tool for file conversion.

- With guidance, use a tool ("gnm-service: Draw.io diagrams to WissKI pathbuilders") for file conversion. (LZ-ID SODa\_02\_005\_0318)
Vorschlag: With guidance, use the gnm-service to convert Draw.io XML into WissKI Pathbuilder XML.

---

## Objective and Scenario

In this unit, you will continue working with the completed Draw.io diagram from Unit 1.

You will export the diagram as XML, convert it into a WissKI Pathbuilder XML file using the gnm-service, and import the generated configuration into WissKI.

You will then inspect the imported paths and path groups and compare them with the original diagram.

> **Draw.io diagram → Draw.io XML → gnm-service → Pathbuilder XML → WissKI Pathbuilder**

---

## From the Semantic Model to the Pathbuilder

In Module 2, you formalised selected concepts of the computer games domain as subclasses of CIDOC CRM classes and reused existing CIDOC CRM properties.

In Unit 1 of this module, you visualised selected relationships in Draw.io.

**For example:** Computer_Game → P102 has title → Game_Title

In the WissKI Pathbuilder, sequences of ontology classes and properties are configured as semantic paths and organised into path groups.

The workflow involves three levels:

| Level                         | Example                                    |
| ----------------------------- | ------------------------------------------- |
| **Ontology structure**       | Computer Game – P102 has title – Game Title |
| **XML transformation**     | Draw.io XML → Pathbuilder XML               |
| **WissKI configuration** | Semantic paths and path groups in the Pathbuilder |

The Pathbuilder connects the ontology structure with the configuration of data entry and display structures in WissKI. It can be used to generate Drupal bundles and fields from the configured paths and groups. (wisski2021pathbuilder) BIBLIOGRAPHIE prüfen!!!

---

## Focus of this Practical Unit

You will complete five steps:

- **Step 1: Transform Draw.io XML into Pathbuilder XML.**

- **Step 2: Check that the required ontology is available in WissKI.**

- **Step 3: Create a Pathbuilder and import the generated XML.**

- **Step 4: Examine the imported paths and path groups.**

- **Step 5: Compare the imported structure with the source diagram.**

---

## The WissKI Pathbuilder

The WissKI Pathbuilder uses classes and properties from a loaded ontology to configure semantic paths and path groups.

- **Paths** represent sequences of ontology classes and properties.
- **Path groups** organise related paths.
- **Bundles and fields** can be generated from these configurations for data entry and display in WissKI.

> **Note:** The Pathbuilder does not define the ontology itself. It uses the existing ontology to configure the semantic structures required in WissKI.

<table>
  <tr>
    <td><img src="../WissKIBits_Modul3/assets/pathbuilder.jpg" alt="WissKI Pathbuilder" width="75%"></td>
  </tr>
</table>

> **Figure:** The WissKI Pathbuilder interface showing the organisation of paths and path groups.

---

## The Gnm-Service as a Transformation Tool

The **“Draw.io diagrams to WissKI pathbuilders”** web service supports the transformation of a semantic Draw.io diagram into a **WissKI Pathbuilder XML file**.

This reduces the need to recreate paths manually and helps maintain a traceable connection between the diagram and its implementation in WissKI.

The transformation enables:

- **reuse** of the semantic model already developed,
- **reduction of manual transfer work**,
- and a traceable connection between the diagram and the Pathbuilder.

> **Note:** Automatic transformation does not guarantee that the generated paths are complete or semantically correct. After importing the file, you must compare the paths and path groups with the source diagram.

---

## Task

**Work format:** Individual work 

**Material:** Completed Draw.io XML file from Unit 1, computer with internet access, and access to a WissKI instance

**Time:** ~ 20 min.

In this exercise, you will transform your completed Draw.io diagram into a WissKI Pathbuilder XML file and import the generated configuration into WissKI.

Follow the five steps below to check the required ontology, import the configuration, and examine whether the resulting paths and path groups correspond to your source diagram.

**Step 1: Transform the Draw.io Diagram**

Open the [**Draw.io diagrams to WissKI pathbuilders**](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/) conversion service.

Proceed as follows:

- Export your completed diagram from Unit 1 as a **Draw.io XML file**, if you have not already saved it in this format.
- Upload the file using **Upload draw.io XML file for conversion to WissKI Pathbuilder XML**.
- Start the transformation.
- Check the response from the web service.
- Copy or save the address of the generated **Pathbuilder XML file** for the import into WissKI.

> **Prompt question**
>
> Which elements of the source diagram must be preserved to generate meaningful paths and path groups in WissKI?
>
> Write down a short answer.

---

**Step 2: Check the Ontology in WissKI**

The classes and properties used in the generated paths must be available in the ontology used by WissKI.

Log in to the prepared **WissKI instance**:

- Navigate to **WissKI → Configuration → WissKI Ontology**
- Check the configured adapter and the ontology available in the instance.
- If the required domain ontology has not yet available, select the designated WissKI adapter, enter the address of the **Games Ontology**, and load the ontology.

**Games ontology:**

[http://games.m-e-g-a.org/game_domain.rdf](http://games.m-e-g-a.org/game_domain.rdf)


> **Note: Access to WissKI**
>
> If no WissKI instance is provided for the tutorial, you can use the WissKI environment available through the theSODa Semantic Co-Working Space (SCS).
>
> Please register for an account: https://manager.scs.sammlungen.io/user/register
>
> Once your account has been activated, you can log in to the SCS and access the WissKI environment required for the tutorial.
>
> You do not need to set up your own WissKI installation for the tutorial. The SCS provides the required technical environment free of charge.

---

**Step 3: Create a new Pathbuilder and Import XML**

Navigate to: **Configuration → Pathbuilders**

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

> **Note:** Examine the imported configuration before generating any additional bundles or fields.

--- 

**Step 4: Examine the Imported Pathbuilder**

Examine the imported paths and path groups and compare them with your Draw.io diagram.

Use the following path as an example:

> `Computer_Game → P102 has title → Game_Title`

**Question 1: Which path group contains this relationship?**

[(X)] Computer Game  
[( )] Game Title  
[( )] The path does not belong to any group.

---

**Question 2: Which property connects the source and target classes?**

[[P102 has title]]

---

**Question 3: Does the imported path correspond to the source diagram?**

[(X)] Yes  
[( )] No


Compare the source class, property, and target class with the corresponding relationship in your Draw.io diagram.

**Check the remaining paths**

Also look at the other imported paths.

- Are the expected groups and paths present?
- Are any paths missing or unexpected?
- Do the imported paths reflect the relationships represented in the source diagram?

> **Prompt question:**
>
> What are the advantages of automatically generating paths instead of creating them manually?

---

**Step 5: Verify the Generated Paths**

Compare the imported Pathbuilder configuration with the completed Draw.io diagram from Unit 1.

Check whether:

- the expected path groups have been created,
- the relevant classes and CIDOC CRM properties appear in the imported paths,
- the relationships correspond to the source diagram, and
- the resulting paths support the selected information requirements.

Document any missing or unexpected paths and note which parts of the diagram may need to be checked or corrected.

**Result: You have imported a Pathbuilder configuration and checked its correspondence with the source diagram.**

---

## Summary

In this practical unit, a semantic Draw.io diagram was transformed step by step into a **WissKI Pathbuilder structure**.

Three tools or representations were used:

| Tool / Representation | Function |
|---|---|
| **Draw.io diagram** | Visual representation of selected ontology classes, properties, and semantic paths |
| **gnm-service** | Transformation of Draw.io XML into WissKI Pathbuilder XML |
| **WissKI Pathbuilder** | Configuration of semantic paths and path groups based on the ontology |

The result is an imported and checked Pathbuilder configuration that reflects selected relationships from the computer games domain model.

---

## Outlook

> **Next**
> 
> The imported paths and path groups can be used to configure data entry structures in WissKI.
>
> After reviewing the Pathbuilder configuration, you can use Save and generate bundles and fields to create the corresponding bundles and fields for data entry and display.
> 
> **Ontology → Pathbuilder → Bundles and fields → Data entry**

---

## Final Reflection

You have now completed the learning path from identifying a research object to configuring ontology-based semantic paths in WissKI.

**Research Object → Conceptual Model → CIDOC CRM Mapping → Formal Ontology → Draw.io Diagram → Pathbuilder XML → WissKI Paths and Path Groups**

Reflect on the complete process:

- How did your representation of the domain change from the initial model sketch to the WissKI Pathbuilder?
- Which modelling decisions remained visible throughout the workflow?
- Which step was most challenging, and why?
- How could you apply this workflow to your own research or collection data?

---

## Resources

- [Draw.io diagrams to WissKI pathbuilders](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/)
- [Erlangen CRM](http://erlangen-crm.org/240307/)
- [Computer Games Domain Ontology](http://games.m-e-g-a.org/game_domain.rdf)
- [Example WissKI Pathbuilder XML](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput.xml)
- [WissKI Pathbuilder Documentation](https://wiss-ki.eu/documentation/data-modelling/pathbuilder)

---

## Bibliography

[wisski2012pathbuilder] WissKI Pathbuilder (n.d.) https://wiss-ki.eu/documentation/data-modelling/pathbuilder?utm_source=chatgpt.com

