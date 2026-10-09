<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: en

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: This fast-track walkthrough is part of the how-to tutorial “Ontology-Based Modelling of Research Data”. Using a computer game collection as an example, it provides a condensed, exercise-based workflow for experienced users, from conceptual modelling and CIDOC CRM mapping to ontology formalisation and the configuration of semantic paths in WissKI.

title: WissKI Bits Ontology-Based Modelling of Research Data

module: Fast Track – From Collection Object to WissKI Paths

unit: Exercise-Based Walkthrough for Experienced Users

description: This SODa WissKI Bits fast track guides experienced users through the practical steps of ontology-based modelling of research data. Using a computer game collection as an example, participants create a conceptual model sketch, map selected concepts to CIDOC CRM, formalise an ontology section in Protégé, prepare a Draw.io diagram, and generate and import semantic paths and path groups in WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modelling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: SODa How-to Tutorial

-->


# WissKI Bits: Ontology-Based Modelling of Research Data

**DEVELOPING AND IMPLEMENTING A DATA MODEL USING AN EXAMPLE** 

**Fast Track: From Collection Object to WissKI Paths**

**An Exercise-Based Walkthrough for Experienced Users**  

**Duration:** ~ 90 min.

---

## WissKI Bits: Fast Track

**From Collection Object to WissKI Paths — An Exercise-Based Walkthrough**

**Audience:** Users familiar with basic semantic modelling, CIDOC CRM, and ontology editors.  

**Example:** *The Legend of Zelda: A Link to the Past*  

**Goal:** Move from a conceptual sketch through a small OWL ontology section and a Draw.io diagram to imported WissKI paths and path groups.

This fast track contains the practical tasks from Modules 1–3. For explanations, definitions, quizzes, and detailed screenshots, refer to the full tutorial.

---

### Before You Start

Prepare a computer with internet access, [Draw.io](https://app.diagrams.net/), [Protégé Desktop or WebProtégé](https://protege.stanford.edu/), and access to a WissKI instance. Keep the [Erlangen CRM / OWL](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl), [computer games domain ontology](http://games.m-e-g-a.org/game_domain.rdf), and [CIDOC CRM documentation](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html) available. The [SODa Semantic Co-Working Space](https://manager.scs.sammlungen.io/de) is an option for accessing a WissKI environment.

---

## 1. Sketch the Domain — Module 1 Activation

1. Open [Draw.io](https://app.diagrams.net/) and the prepared puzzle template (`WissKIBits_Modul1/assets/puzzle.drawio_en.xml`) from the tutorial repository.
2. Identify relevant concepts, events, and relationships around the example game. Consider the game, title, actors, production, place, time, and classifications where relevant.
3. Connect the elements with meaningful relationship labels. Read each connection as a statement.
4. Check whether statements are supported by the available information. Mark uncertain connections with `?`.

**Output:** A conceptual model sketch in domain terminology. Do not apply CIDOC CRM classes yet.

---

## 2. Map Selected Concepts to CIDOC CRM — Module 1 Exercise

1. Select **two concepts or events** from your sketch.
2. Clarify what each term means in the collection context.
3. Find candidate CIDOC CRM classes and consult their **scope notes**. Possible starting points include `E73 Information Object`, `E35 Title`, `E55 Type`, `E21 Person`, and `E74 Group`.
4. Record the selected class, a short justification, and any open question. Compare alternative mappings where appropriate.

**Output:** A small set of justified, provisional CIDOC CRM mappings. This is not yet a formal ontology.

---

## 3. Formalise a Small Ontology Section — Module 2 Exercise

1. Open [Erlangen CRM / OWL](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl) in Protégé.
2. Inspect relevant classes, especially `E41 Appellation`, `E35 Title`, `E55 Type`, and `E73 Information Object`, and review their scope notes.
3. Revisit the mappings from Module 1. Add selected **domain-specific subclasses** of existing CIDOC CRM classes, such as `Computer_Game` under `E73 Information Object`, `Game_Title` under `E35 Title`, and `Game_Genre_Type` or `Game_Platform_Type` under `E55 Type`.
4. **Reuse existing CIDOC CRM properties only**; do not create new properties. Examine relationships such as `P102 has title` and `P2 has type` and document your modelling choices.
5. Review the hierarchy, annotations, and relationships. Save your OWL model.

**Output:** A small, documented OWL ontology section, not a complete computer games ontology.

---

## 4. Complete the Draw.io Diagram — Module 3, Exercise 1

1. Download the prepared [Draw.io gap diagram (`Gruppe_B.drawio.xml`)](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_B.drawio.xml) and open it in Draw.io.
2. Add missing nodes and edges using the relevant ontology classes and CIDOC CRM properties, including `P102_has_title`, `P1 is identified by`, `P190 has symbolic content`, and `mega:E41_Game_Character_Name` where required.
3. Remove all `(???)` placeholders. Check connected nodes, attached edge labels, and complete semantic paths. Do not represent individual instances.
4. Check transformation attributes, including `element_id`, `group_name`, and `name` on the start and group nodes. Check end-node requirements against the prepared diagram and conversion specification.
5. Save the completed Draw.io XML file.

**Output:** A completed, checked diagram ready for XML conversion.

---

## 5. Generate and Import WissKI Paths — Module 3, Exercise 2

1. Open the [Draw.io-to-WissKI Pathbuilder conversion service](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/), upload the completed Draw.io XML, run the transformation, and retain the generated Pathbuilder XML URL.
2. Log in to WissKI. Under **WissKI → Configuration → WissKI Ontology**, check that the required ontology and adapter are available; load the [games ontology](http://games.m-e-g-a.org/game_domain.rdf) if needed and appropriate for your instance.
3. Under **Configuration → Pathbuilders**, add a Pathbuilder, assign a unique name and the designated adapter, and save it.
4. In **Pathbuilder Definition Import**, provide the generated XML URL and import the configuration.
5. Inspect the resulting path groups and paths. Compare relationships such as `Computer_Game → P102 has title → Game_Title` with the source diagram. Record missing, unexpected, or incorrectly grouped paths.

**Output:** An imported and checked WissKI Pathbuilder configuration. Do not generate bundles and fields until the imported paths have been reviewed.

---

## Completion Check

- [ ] Conceptual sketch created and uncertainties marked
- [ ] Selected CIDOC CRM mappings justified using scope notes
- [ ] Domain-specific subclasses and reused properties documented in OWL
- [ ] Draw.io diagram completed, checked, and exported
- [ ] Pathbuilder XML generated and imported
- [ ] Imported paths and path groups compared with the source diagram

**Next:** Once the configuration has been reviewed, the Pathbuilder can be used to generate bundles and fields for data entry and display in WissKI.

**Scope:** This fast track demonstrates a reproducible workflow for a selected model section; it does not provide a complete ontology or fully configured WissKI installation.
