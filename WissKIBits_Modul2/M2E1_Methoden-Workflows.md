<!--
author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: c.hastik@igsd-ev.de

email: g.schwenk@igsd-ev.de

version:  v1

language: DE

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/liascript-oers/refs/heads/main/resources/SODa-Logo_full.svg
link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/SODa_WissKI-ISWC25Bits/refs/heads/main/soda.css

license: CC BY 4.0

comment: Dieses Modul ist Teil des SODa How-to-Tutorials „Ontologiegestützte Modellierung von Forschungsdaten“. Das Tutorial vermittelt am Beispiel einer Computerspielsammlung schrittweise die Entwicklung eines semantischen Datenmodells auf Grundlage des CIDOC CRM und dessen Umsetzung mit WissKI.

title: WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

module: Modellieren mit CIDOC CRM – verstehen und anwenden

einheit: Methoden und Workflows semantischer Modellierung

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-09-04

LearningResourceType: SODa How-to-Tutorial

-->

# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 2: **Modllieren mit CIDOC CRM – verstehen und anwenden**

Einheit 1: **Methoden und Workflows semantischer Modellierung**  

**Dauer:** ~  5 Min.

**Lernziele:**

Teilnehmende können...

- Methoden zur Entwicklung von Ontologien benennen. (LZ-ID 03\_007\_0784)
- Methoden zur Entwicklung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0839)
- einen Workflow für die semantische Modellierung als Datendokumentation benennen. (LZ-ID SODa\_03\_001\_0626)
- einen Workflow für die semantische Modellierung als Datendokumentation erläutern. (LZ-ID SODa\_03\_001\_0853)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (SODa\_03\_007\_0784a)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM erläutern. (SODa\_03\_007\_0785a)

---

## Methoden zur Entwicklung von Ontologien

Die Entwicklung einer Domänenontologie folgt typischerweise einem methodischen, mehrstufigen und iterativen Vorgehen. 

Dazu zählen u.a. die Erhebung zentraler Begriffe und Definitionen (sog. „ontology capture“) (Uschold1995method, S. 3), die Strukturierung von Konzepten in Klassen und Eigenschafen/Relationen sowie die kontinuierliche Prüfung und Überarbeitung des Domänenmodells im Hinblick auf Konsistenz und Nutzbarkeit. (Gruber1993knowledge)

Die praktische Ontologieentwicklung wird dabei häufig als ein Prozess verstanden, der sowohl Domänenwissen als auch Anwendungsanforderungen integriert und schrittweise in eine formal nutzbare Wissensstruktur überführt.

**Ontologien entstehen häufig durch eine Kombination aus:** (Noy2001ontology, S.4ff)

- **Top-down-Modellierung:** Ausgehend von einem Referenzmodell (z.B. CIDOC CRM) erfolgt eine domänenspezifische Spezialisierung.
- **Bottom-up-Modellierung:** Aus vorhandenen Daten werden schrittweise Klassen (Entities) und Eigenschaften (Properties) abgeleitet.
- **Competency Questions:** Die Modellierung erfolgt aus typischen Analyse- und Forschungsfragen heraus (z.B. „Welche Spiele haben Merkmal X?“)
- **Iteratives Prototyping:** Es wird ein Modell entworfen → überprüft → kontinuierlich mit Blick auf Konsistenz, Erweiterbarkeit und Abfragbarkeit angepasst.

---

## Modellierungsstrategie im Tutorial

Es gibt verschiedene Ansätze, Domänenontologien zu erweitern:

- Neue **Subklassen (Entities)** bilden
- Neue **Eigenschaften (Properties)** definieren
- **Reine Wiederverwendung** bestehender CIDOC CRM-Klassen (Entities) und -Eigenschaften (Properties)
- **Kombinationen** der oben genannten Strategien

**Hinweis**

> In diesem Tutorial wird eine **leichtgewichtige Erweiterungsstrategie** empfohlen:
> - **Domänenspezifische Subklassen (Entities) für die domänenspezifischen Konzepte anlegen**  
> - **Eigenschaften (Properties) werden weitestgehend aus CIDOC CRM übernommen**

Das garantiert **Interoperabilität und CIDOC-Kompatibilität**, reduziert die Komplexität und macht dennoch die Domänenspezifik deutlich.

---

## Ausblick

Die vorgestellten **Methoden und Workflows semantischer Modellierung** sowie die im Tutorial erläuterte **Modellierungsstrategie** bilden die Grundlage für die Überführung der bisher erarbeiteten Konzepte und Modelle in die Praxis. 

In der folgenden Einheit wird **Protégé** als Editor zur Modellierung von Ontologien vorgestellt. Anhand eines konkreten Beispiels wird gezeigt, wie auf Basis des CIDOC CRM mit Protégé eine **maschinenlesbare Domänenontologie** entwickelt, formal beschrieben und für die maschinelle Verarbeitung zugänglich gemacht werden kann.

---

## Bibliografie

[Gruber1993knowledge] Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

[Noy2001ontology] Noy, N. F., & McGuinness, D. L. (2001). Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory.

[Uschold1995method] Uschold, M., & King, M. (1995). Towards an Methodology for Building Ontologies. Presented at Workshop on Basic Ontological Issues in Knowledge Sharing held in conjunction with IJCAI. The University of Edinburgh.
