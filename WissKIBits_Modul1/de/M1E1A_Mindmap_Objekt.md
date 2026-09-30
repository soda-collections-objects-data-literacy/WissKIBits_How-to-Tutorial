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

module: From the collection through modeling decisions to the diagram – understand and explain

unit: Application Example: Object Collections

description: The SODa how-to tutorial uses a computer game collection as an example to teach the fundamentals and practical steps of ontology-based modeling of research data. Learners develop a semantic data model based on CIDOC CRM and implement it step by step using Protégé, Draw.io, and WissKI.

keywords: WissKI, CIDOC CRM, ontology, domain ontology, semantic modeling, research data, research data management, OER

community: Scientific Communication Infrastructure (WissKI) and Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-09-09

LearningResourceType: SODa How-to Tutorial

-->

# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 1: **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären**

Einheit E1A: **Anwendungsbeispiel: Objektsammlung**  

**Dauer:** ~ 5 Min.


**Lernziele:**

Die Teilnehmenden können...

- die Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LO-ID SODa_03_007_0811)

---

## Ziel und Szenario

Für diese Übung würde ich den aktuellen Einstieg deutlich auf die Sammlungsperspektive beschränken.

> **AKTIVIERUNG · Vom Objekt zum konzeptionellen Modell**
>
> Gehen Sie von einem Sammlungs- oder Forschungsobjekt aus und fragen Sie:
>
> Was müssen wir über dieses Objekt wissen – und wie hängt dieses Wissen zusammen?
>
> Identifizieren Sie anhand des Beispiels *The Legend of Zelda: A Link to the Past* relevante Konzepte, Ereignisse und Beziehungen.
>
> Ziel ist es noch nicht, CIDOC CRM anzuwenden, sondern eine erste Skizze eines konzeptionellen Modells für den Fachbereich zu erstellen.

---

## Ausgangspunkt: Beispielobjekt „Zelda“

Das Computerspiel **„The Legend of Zelda: A Link to the Past“** dient als Ausgangspunkt.

Anhand dieses Beispiels untersuchen wir, welche **Konzepte, Ereignisse und Beziehungen** für die Beschreibung eines Sammlungsobjekts und dessen Kontexts relevant sein können.

Das **Ziel ist nicht**, ein vollständiges Datenmodell für Computerspiele zu entwickeln. Stattdessen wird ein **erster Modellentwurf** erstellt, der

- zentrale Konzepte und Ereignisse auf eine für Menschen verständliche Weise unterscheidet,
- deren Beziehungen sichtbar macht und
- als Grundlage für die anschließende Übertragung auf **CIDOC CRM** dient.

> **Vom Objekt ausgehend**
>
> Unser Beispiel ist das Computerspiel **The Legend of Zelda: A Link to the Past.**
>
> Wir nutzen es, um zu erkunden, welche Konzepte, Ereignisse und Beziehungen für die Beschreibung eines Sammlungsobjekts und dessen Kontexts relevant sein können.
>
> **Denken Sie daran:** Das Ziel ist kein vollständiges Datenmodell. Beginnen Sie im Kleinen und konzentrieren Sie sich auf das, was für das Verständnis des Objekts wichtig ist.

---

## Warum Computerspiele?

Computerspiele eignen sich hervorragend als Beispielbereich, da sie verschiedene Aspekte der Modellierung anschaulich machen.

Dieser Bereich ist besonders geeignet, weil er...

- sowohl **physische** als auch **digitale** Objekte umfasst,
- klar nachvollziehbare **Produktions- und Veröffentlichungskontexte** aufweist,
- typische **Ereignisse** (z. B. Veröffentlichung, Portierung, Neuauflage) beinhaltet,
- die Darstellung von **Versionen/Editionen** und **Serienzugehörigkeiten** ermöglicht,
- eindeutige Identifikatoren und Bezeichnungen (Titelvarianten, Produktcodes) verwendet.

Damit bietet dieser Bereich einen anschaulichen Ausgangspunkt, um verschiedene Perspektiven auf ein Objekt zu erkennen und daraus erste **Modellierungsentscheidungen** abzuleiten.

> **Warum Computerspiele?**
>
> Computerspiele liefern ein nützliches Beispiel für die Modellierung, da sie Folgendes vereinen:
>
> physische und digitale Objekte · Akteure · Ereignisse · Versionen · Identifikatoren · Orte und Zeiten
>
> Dies ermöglicht es, verschiedene Perspektiven auf ein Sammlungsobjekt anhand eines überschaubaren Beispiels zu erkunden.

---

## Schwerpunkt dieser Modellierungsübung

Für die Modellskizze betrachten wir ausgewählte Informationen zu dem Beispielobjekt. Wir konzentrieren uns auf drei Bereiche:

- **Spieletitel**
- **Spieleigenschaften** (z. B. Genre wie Action-Adventure, RPG oder Plattform wie Nintendo 64, PlayStation, PC)
- **Narrative Elemente** (z. B. Beschreibung, Perspektive wie Ego-Perspektive oder Third-Person-Perspektive, oder Charaktere wie Zelda)

Diese Bereiche dienen als Ausgangspunkt, um verschiedene Arten von **Konzepten und Ereignissen** zu erkennen und deren **Beziehungen** zu formulieren.

> **Über das Objekt nachdenken**
>
> - Welchen **Titel** hat das Spiel?
> - Welchem ​​**Genre** oder welcher **Plattform** ist es zugeordnet?
> - Welche **Personen oder Organisationen** waren beteiligt?
> - Welche **Ereignisse** sind für das Spiel relevant?
> - An welchen **Orten** und zu welchen **Zeiten** haben diese Ereignisse stattgefunden?

---

## Übung – Erstellung einer Mini-Modellskizze

**Arbeitsformat:** Breakout-Rooms / Einzelarbeit oder Teams (2–5 Personen)

**Material:** Papier & Stift (oder digitales Whiteboard)

**Zeit:** 15 Minuten

> **Schritt 1 · Identifizieren**
> Identifizieren Sie 3–5 relevante Konzepte und Ereignisse im Zusammenhang mit dem Beispielobjekt.
> Dies können ein Objekt, eine Person oder Organisation, ein Ort, eine Zeit oder ein Ereignis sein. Es müssen nicht alle Kategorien vertreten sein.
>
> **Schritt 2 · Verbinden**
>
> Verbinden Sie die identifizierten Elemente durch aussagekräftige Beziehungen.
> Formulieren Sie jede Verbindung so, dass sie als sinnvolle Aussage gelesen werden kann.
> **Beispiele**
> Spiel → hat → Titel
> Nintendo → war beteiligt an → Entwicklung
> Entwicklung → erschuf → Spiel
>
> **Schritt 3 · Überprüfen**
>
> Lesen Sie Ihre Verbindungen als Aussagen:
> Drücken sie das aus, was Sie tatsächlich meinen?
>
> **Tipp: Weniger ist mehr. Konzentrieren Sie sich auf eine kleine Anzahl von Elementen und Beziehungen, die für das Verständnis des Objekts besonders relevant sind.**

## Ergebnis

Sie verfügen nun über eine erste konzeptionelle Modellskizze, die Folgendes enthält:

- relevante Konzepte,
- Ereignisse und
- aussagekräftige Beziehungen.

![Concept mind map](../WissKIBits_Modul1/assets/mindmap.png)

**Behalten Sie diese Skizze: Wir werden darauf zurückkommen, nachdem wir CIDOC CRM eingeführt haben.**
