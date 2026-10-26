<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_Wort-Bild_RGB.png

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This Fast Track is part of the how-to tutorial “Ontology-Based Modeling of Research Data.” Using a video game collection as an example, it provides experienced users with a concise, hands-on workflow covering conceptual modeling and mapping to CIDOC CRM, ontology formalization, and the configuration of semantic paths in WissKI.

title: WissKI Bits – Ontology-Based Modeling of Research Data

module: Fast Track – From Collection Object to Data Entry in WissKI

unit: Practice-Oriented Step-by-Step Guide for Advanced Users

description: This WissKI Bit Fast Track guides experienced users through the practical steps of ontology-based research data modeling. Using a video game collection as an example, they create a conceptual model sketch, formalise selected concepts using CIDOC CRM, transfer a section of the ontology into Protégé, prepare a Draw.io diagram, and generate and import semantic paths and path groups into WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: How-to-Tutorial

-->


# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

**Fast Track: From Collection Object to Data Entry in WissKI**

**An Exercise-Based Walkthrough for Expert Users**  

**Audience:** Advanced users familiar with basic semantic modelling, CIDOC CRM, and ontology editors.  

**Objective:** This Fast Track includes all practical exercises from Modules 1–3 of the WissKI Bits how-to tutorial: from a conceptual and formalised model sketch to a Draw.io diagram and an OWL ontology excerpt, through to imported WissKI paths, path groups, and data entry fields for initial data entry.

**Important:** Explanations, definitions, quiz questions, and additional image and video documentation are available in the WissKI Bits how-to tutorial.

**Example:** The Legend of Zelda: A Link to the Past

**Duration:** ~ 90 min.

---

## About This Fast Track

This fast track brings together the **five practical exercises from modules 1–3** of the WissKI Bits how-to tutorial, following their original sequence and using **existing exercise materials**, to form a coherent step-by-step guide.

Starting with the **example object:** **The Legend of Zelda: A Link to the Past**, you will complete the following steps in sequence:

- Conceptual modelling,
- Mapping to CIDOC CRM,
- Formalising a small section of the ontology in Protégé,
- Completing a prepared Draw.io diagram, and
- Converting the Draw.io diagram into a WissKI Pathbuilder configuration.

**Important:** The activities follow the example domain and modelling approach used in the tutorial. The required materials are provided at the beginning of each exercise. Afterwards, compare your results with the provided model solutions and review your modelling decisions.

**Time plan**

| Activity | Time |
|---|---:|
| Preparation and orientation | 5 min |
| 1. Examine a collection object and create a conceptual model sketch | 10 min |
| 2. Map selected concepts to CIDOC CRM | 15 min |
| 3. Implement and formalise a section of the model in Protégé | 15 min |
| 4. Complete a Draw.io diagram | 15 min |
| 5. Import and review the WissKI Pathbuilder configuration | 20 min |
| 6. Review data entry fields and enter data | 10 min |
| **Total** | **90 min** |

The schedule assumes that you are familiar with the fundamentals of semantic modelling and have access to the **tools, sample data and model solutions**.

Relevant supplementary materials are linked where appropriate. The complete modules are available in English and German:
- [Modul 1: Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/tree/main/WissKIBits_Modul1)
- [Modul 2: Modellieren mit CIDOC CRM – verstehen und anwenden](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/tree/main/WissKIBits_Modul2)
- [Modul 3: Vom Diagramm zu Pfaden – erläutern und anwenden](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/tree/main/WissKIBits_Modul3)

---

### Before You Start - 5 min

Set up your working environment:

- You will need a computer with internet access.
- Open each of the following in a separate browser tab (Firefox is recommended):
  - [Draw.io / diagrams.net](https://app.diagrams.net/),
  - [Protégé Desktop or WebProtégé](https://protege.stanford.edu/), 
  - [Erlangen CRM 240307 (OWL)](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl) based on CIDOC CRM 7.1.3,
  - WissKI instance in the [SODa Semantic Co-Working Space](https://manager.scs.sammlungen.io/de),
  - [CIDOC CRM 7.1.3 documentation and scope notes](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html),
  - [GNM-Service](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/).

**Note on software versions:** The user interfaces of Protégé (version 5.6.3), WebProtégé (4.0.2:20200731), Draw.io (v32.6.1), WissKI (version 8.X-4.9) and Drupal (version 11.4.11) may change as a result of software updates. Consequently, some menu labels, buttons and views may differ from the screenshots and descriptions provided in this tutorial. If a newer ISO-certified version of CIDOC CRM (currently version 7.1.3, February 2024) is published, it should be used.

---

## 1. Explore the Collection Object - 10 min.

**Starting Point**

As part of a brief research task on Wikipedia, familiarise yourself with the collection object **[The Legend of Zelda: A Link to the Past](https://de.wikipedia.org/wiki/The_Legend_of_Zelda:_A_Link_to_the_Past)** and basic terminology from the video game domain. (Wikipedia, 2026)

Consider the following questions:
- **What characteristics describe the SNES video game The Legend of Zelda: A Link to the Past?**
- **How are these characteristics related to one another?**

Consider the following characteristics:

- **Game title:** What is the game called?
- **Game properties:** Which genres, platforms or other classifications are relevant?
- **Narrative elements:** Which descriptions, perspectives and characters are characteristic of the game?

You may include additional metadata (e.g. place and date of publication) where relevant to explaining the characteristics listed above.

### Step 1: Complete the Puzzle

> 1. Save the prepared **[XML puzzle](assets/puzzle.drawio_en.xml)** to your computer.
> 2. Open the downloaded **puzzle file** in **[Draw.io](https://app.diagrams.net/)**.
> 3. **Examine, arrange and connect** only the relevant elements to create a meaningful conceptual model sketch.
> 4. Check whether your conceptual model sketch expresses meaningful statements about the characteristic features of the example object.

**Result:** A conceptual model sketch that illustrates selected key elements and relationships associated with the example object.

**Transition to the next exercise:** In the next exercise, you will examine whether the key elements can be adequately represented using **existing CIDOC CRM classes**.

> **For further information, see Module 1, including:**
> - [M1U0A: Mindmap of the Application Example from Object Collections](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul1/en/M1U0A_Mindmap_Object_en.md)
> - [M1U1: Basic concepts of conceptual knowledge modelling](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul1/en/M1U1_Basics-Conceptual-Modelling_en.md)

---

## 2. Map Selected Concepts to CIDOC CRM - 15 min.

**Starting Point**

Now use the model solution **conceptual model sketch from Module 1** for your semantic model:

![Conceptual mind map from Module 1](assets/mindmap_en.png)

---

### Step 1: Examine and Justify Initial Class Mappings

> 1. Select **two concepts or events** from the provided conceptual model sketch and clarify what they mean in the context of the collection.
> 2. Use the CIDOC CRM **[documentation](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html)** or explore CIDOC CRM using the **[Periodic Table](https://remogrillo.github.io/cidoc-crm_periodic_table/?code=E1)** to identify suitable CIDOC CRM classes for the selected concepts.
> 3. Read the **Scope Notes** and compare them with the conceptual model sketch.
> 4. Consider what each class includes and/or excludes.
> 5. Record a brief justification and an open question for each mapping in the following table.

| Domain concept from your sketch | Possible CIDOC CRM class | Scope Note applicable | Justification and open question |
|---|---|---|---|
| Game title | E35 | [(X)] | Is there another suitable class? |
| [[Solution]] | [[Solution]] | [[Solution]] | [[Solution]] |
| [[Solution]] | [[Solution]] | [[Solution]] | [[Solution]] |
| [[Solution]] | [[Solution]] | [[Solution]] | [[Solution]] |
| [[Solution]] | [[Solution]] | [[Solution]] | [[Solution]] |

**Important:** A CIDOC CRM class name that sounds similar to your domain concept is not sufficient to establish a semantically correct mapping. Always compare the intended meaning of each concept with the **Scope Note** of the corresponding CIDOC CRM class before making a modelling decision. Suitable classes may include:
- `E73 Information Object`,
- `E35 Title`,
- `E55 Type`,
- `E21 Person` or
- `E74 Group`.

---

### Step 2: Compare Modelling Decisions

> Discuss or reflect on whether...
> - the same domain term can refer to different things depending on the research question.
> - a name, for example, can be formalised as a `Title`, an `Identifier` or using another class.

**Result:** Your semantic model sketch includes at least two **justified, provisional class mappings** and, where applicable, any remaining uncertainties.

**Transition to the next exercise:**
Next, you will use Protégé to explicitly define your modelling decisions as **domain-specific subclasses** of existing CIDOC CRM classes.

> **For further information, see Module 1, including:**
> - [M1U3: Introduction to CIDOC CRM](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul1/en/M1U3_Introduction-CIDOCCRM_en.md)

---

## 3. Formalise a Small Ontology Section in Protégé - 25 min

*Based on module 2, Exercise M2UE: Modelling with CIDOC CRM in Protégé.*

**Goal**

Formalise a **limited section** of the computer games domain. Follow the tutorial's lightweight extension strategy: **create subclasses of existing CIDOC CRM classes and reuse existing CIDOC CRM properties; do not define new properties.**

![Concept mind map from the Module 2 exercise](../WissKIBits_Modul2/assets/Mindmap.png)

> **Step 1: Load Erlangen CRM**
>
> Open [Erlangen CRM 240307 OWL](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl) in Protégé. 
> 
> If you need a reminder of the interface, consult the !?[Video Demonstration: Getting Started with Protégé](../WissKIBits_Modul2/assets/Short_Protege_Intro.mp4).

> **Step 2: Explore relevant classes**
> 
> Find these classes in the hierarchy:
> 
> - `E41 Appellation`
> - `E35 Title` (a subclass of `E41 Appellation`)
> - `E55 Type`
> - `E73 Information Object`
>
> For each, inspect its place in the hierarchy, annotations and **scope note**. Pay particular attention to the distinction between a general appellation and a title.

For mor details about the methodological approach, iterative modeling, and ontology development, see **[M2U1: Methods and Workflows of Semantic Modelling](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul2/en/M2UE_Modelling-CIDOCCRM_en.md)**

> **Step 3: Revisit selected mappings**
>
> Compare the conceptual decisions from exercise 2 with the formal classes. 
>
> Do not assume that a mapping is correct merely because the names resemble one another.
>
> The original exercise uses examples such as:

| Domain concept | Possible CIDOC CRM class | Question to check |
|---|---|---|
| Game title | `E35 Title` | Which entity is assigned this title? |
| Game genre | `E55 Type` | What exactly is being classified? |
| Game platform type | `E55 Type` | Is this a classification of the game? |

> **Step 4: Create domain-specific subclasses**
> 
> Create the selected example subclasses under the corresponding CIDOC CRM classes:
> 
> - E73 Information Object →  Computer_Game
> - E35 Title → Game_Title
> - E55 Type → Game_Genre_Type, Game_Platform_Type
>
> **Do not create new CIDOC CRM properties.** These rows describe the intended model; inspect the corresponding properties in Protégé and document your choices rather than assuming that the table itself implements the relations.

Use existing CIDOC CRM properties to express intended relationships; the original exercise highlights:

| Source | Existing property | Target | Intended statement |
|---|---|---|---|
| `Computer_Game` | `P102 has title` | `Game_Title` | A computer game has a title. |
| `Computer_Game` | `P2 has type` | `Game_Genre_Type` | A game is assigned to a genre type. |
| `Computer_Game` | `P2 has type` | `Game_Platform_Type` | A game is assigned to a platform type. |

> **Steps 5–6: Review, document and save**
>
> Check that the subclasses are placed under suitable superclasses, that the reused properties express the intended relationships, and that unresolved questions are recorded. Save your work as described in the original exercise if you wish to retain the edited ontology section.
> 
> **Result:** A small formalised and documented ontology section, **not** a complete games ontology.
> 
> **Transition to the next exercise**
> 
> The next exercise uses the **prepared Draw.io gap diagram** from module 3. It represents selected classes and properties from the same example domain, but it is **not generated automatically from your Protégé file**. You will complete the diagram according to the conventions required by the transformation service.

---

## 4. Complete the Draw.io Diagram — 15 min

*Based on Module 3, Exercise M3UE1: Visualising a Domain Ontology as a Diagram.*

**Goal**

Represent connected semantic paths using selected ontology classes and existing CIDOC CRM properties. Work with the **prepared gap diagram** rather than drawing a new model from scratch.

![Example of the ontology diagram](../WissKIBits_Modul3/assets/MusterDrawio.png)

> **Step 1: Complete the prepared diagram**
>
> 1. Download the original [Draw.io XML gap diagram (`Gruppe_B.drawio.xml`)](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_B.drawio.xml) and open it in [Draw.io](https://app.diagrams.net/).
> 2. Identify the missing nodes and edges and replace the temporary `(???)` placeholders.
> 3. Use the elements specified in the original exercise **where required**, including `P102_has_title`, `P1 is identified by`, `P190 has symbolic content` and `mega:E41_Game_Character_Name`.
> 4. Connect the classes and properties into **complete semantic paths**. Ensure each property label is attached to its corresponding edge; do not add individual game instances.
> 5. Inspect the attributes of the central start node and group nodes: `element_id`, `group_name` and `name`. The original exercise gives `Computer_Game` as an example value for these attributes. Check end-node attributes against the **prepared diagram and the original exercise** rather than inventing values.
> 6. Save or export the completed diagram as **Draw.io XML**.
>
> A path illustrated in the original exercise is:
>
> mega:E73_Computer_Game
>
> → P102_has_title
> → mega:E35_Game_Title
> → P190 has symbolic content
> → E62_String
>
> **Check before conversion:** No `(???)` placeholders remain; connections are complete; class/property names and required attributes are consistent; the diagram contains **classes and properties**, not individual instances.
> **Result:** A completed Draw.io XML diagram ready for the existing gnm-service.
>
> **Transition to the next exercise**
> 
> The diagram describes semantic paths visually. The gnm-service converts its XML representation into a **WissKI Pathbuilder XML configuration**, which you will import and inspect in WissKI.

For a detailed description of Draw.io, modeling rules, nodes, edges, attributes, and XML, see Module 3, **[M3UE1 Visualising a Semantic Domain Ontology](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/en/M3UE1_Domain-Ontologie-Diagram_en.md)**.

---

## 5. Transform and Import WissKI Paths — 20 min

*Based on Module 3, Exercise M3UE2: Draw.io to WissKI Paths.*

**Goal**

Convert the completed Draw.io diagram into Pathbuilder XML, import the resulting **configuration** into WissKI, and compare the imported paths and path groups with the source diagram.

![WissKI Pathbuilder example](../WissKIBits_Modul3/assets/pathbuilder.jpg)

> **Step 1: Transform the Draw.io diagram**
>
> 1. Open the [gnm-service: Draw.io diagrams to WissKI Pathbuilders](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/).
> 2. Upload the **completed Draw.io XML file** from exercise 4.
> 3. Start the transformation and inspect the service response.
> 4. Copy or retain the URL of the generated **Pathbuilder XML** file for the WissKI import.
>
> The current service documentation names **Erlangen CRM 240307** and the **Games ontology** as its supported ontology basis. This fast track uses those existing resources and does not require changing the service.

> **Step 2: Login and check the ontology in WissKI**
>
> Log in to your prepared WissKI instance and navigate to **WissKI → Configuration → WissKI Ontology**. Check the configured adapter and the ontology available in the instance. If the required Games ontology is not present, follow the original exercise and the instructions for your instance to load it via the designated adapter:
> 
> [Games domain ontology](http://games.m-e-g-a.org/game_domain.rdf)
> 
> **Important:** Importing Pathbuilder XML does **not** import or define the ontology. The referenced classes and properties must already be available in the ontology used by WissKI.

> **Step 3: Create a pathbuilder and import the XML**
>
> 1. Navigate to **Configuration → Pathbuilders**.
> 2. Select **Add Pathbuilder**, assign a unique name and choose the designated adapter.
> 3. Save and open the new Pathbuilder.
> 4. Find **Pathbuilder Definition Import**, paste the generated XML URL, and start the import.
> 5. Wait for the Pathbuilder structure to appear. **Review the paths before generating bundles or fields.**

For more details about WissKI configuration and XML-Import, see module 3, **[M3UE2 Transforming Semantic Models into WissKI Paths](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/en/M3UE2_Drawio-to-WissKI-Paths_en.md)**.

> **Step 4: Examine the imported paths and path groups**
>
> Find the relationship:
> 
> **Computer_Game → P102 has title → Game_Title**
> 
> 
> Check which path group contains it, identify the property linking the classes, and compare the result with the source diagram. Use the following questions from the original exercise as a quick check:
>
> - Which path group contains this relationship? (Look for **Computer Game**.)
> - Which property connects the source and target classes? (**P102 has title**.)
> - Does the imported path correspond to your source diagram? **Check the actual result**, rather than assuming that the import guarantees correctness.

> **Step 5: Verify the generated paths**
> 
> Compare the imported Pathbuilder configuration with the Draw.io diagram. Check whether the expected path groups exist, the relevant classes and properties are present, and any paths are missing, unexpected or incorrectly grouped. Record anything that may need to be corrected in the diagram or configuration.
> 
> **Result:** A generated, imported and **checked WissKI Pathbuilder configuration**. This is a configuration import, not an ontology import.

---

## Completion Self-Check

- [ ] The prepared conceptual-model puzzle has been completed and uncertain relationships identified.
- [ ] Two provisional CIDOC CRM mappings have been justified using scope notes.
- [ ] A selected ontology section has been formalised in Protégé using domain-specific subclasses and **existing properties**.
- [ ] The provided `Gruppe_B.drawio.xml` gap diagram has been completed and saved as Draw.io XML.
- [ ] The diagram has been converted with the existing gnm-service.
- [ ] The Pathbuilder XML has been imported and the resulting paths and path groups checked in WissKI.

> **Next**
>
> After reviewing the imported Pathbuilder configuration, you can proceed to generating bundles and fields for data entry and display in WissKI, as described in the full tutorial.

---

## Optional Reference: Gnm-Service Example Files

The service provides additional examples for checking the transformation format. **They are references, not extra mandatory inputs for this fast track.**

- [Example Draw.io XML input](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/SODa_ISWC2025.drawio.xml) ([open in diagrams.net](https://app.diagrams.net/#Uhttps%3A%2F%2Fisl.ics.forth.gr%2Fgnm_services%2Ffiles%2Fexamples%2Fdiagrams_to_pathbuilders%2FSODa_ISWC2025.drawio.xml#%7B%22pageId%22%3A%22iUIuGOhsytNMqk53lauw%22%7D); [PNG preview](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/SODa_ISWC2025.drawio.png)).
- [Optional JSON configuration with default values](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/config_defaults.json).
- [Example Pathbuilder XML output](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput_ISWC2025.xml).

**Scope:** This fast track is a time-bounded selection and connection of the **existing practical exercises**. It does not require developing a new end-to-end model from scratch or extending the gnm-service. For deeper explanations, optional tasks, full screenshots and further reflection, consult the corresponding original units (M1U0A, M1UE, M2UE, M3UE1 and M3UE2).
