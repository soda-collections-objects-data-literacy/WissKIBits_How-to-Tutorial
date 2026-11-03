<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: de

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_Wort-Bild_RGB.png

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: Dieses Modul ist Teil des How-to-Tutorials „Ontologiegestützte Modellierung von Forschungsdaten“. Das Tutorial vermittelt am Beispiel einer Computerspielsammlung schrittweise die Entwicklung eines semantischen Datenmodells auf Grundlage des CIDOC CRM und dessen Umsetzung mit WissKI.

title: WissKI Bits Ontologiegestützte Modellierung von Forschungsdaten

module: Modellieren mit CIDOC CRM – verstehen und anwenden

unit: Methoden und Workflows semantischer Modellierung

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 2 (M2): **Modllieren mit CIDOC CRM – verstehen und anwenden**

Einheit 1 (E1): **Methoden und Workflows semantischer Modellierung**  

**Dauer:** ~  5 Min.

**Lernziele:**

Teilnehmende können...

- Methoden zur Entwicklung von Ontologien benennen. (LZ-ID 03\_007\_0784)
- Methoden zur Entwicklung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0839)
- einen Workflow für die semantische Modellierung als Datendokumentation benennen. (LZ-ID SODa\_03\_001\_0626)
- einen Workflow für die semantische Modellierung als Datendokumentation erläutern. (LZ-ID SODa\_03\_001\_0853)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0784a)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM erläutern. (LZ-ID SODa\_03\_007\_0785a)

---

## Methoden zur Entwicklung von Ontologien

Die Entwicklung einer Domänenontologie folgt typischerweise einem methodischen, mehrstufigen und iterativen Vorgehen. 

Dazu zählen u.a. die Erhebung zentraler Begriffe und Definitionen (sog. „ontology capture“) (Uschold, 1995, S. 3), die Strukturierung von Konzepten in Klassen und Eigenschafen/Relationen sowie die kontinuierliche Prüfung und Überarbeitung des Domänenmodells im Hinblick auf Konsistenz und Nutzbarkeit. (Gruber, 1993)

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

> **Wie geht es weiter?**
>
> In der folgenden Einheit lernen Sie **Protégé** als Editor zur Ontologiemodellierung kennen. Anhand eines konkreten Beispiels entwickeln Sie auf Basis des **CIDOC CRM** eine **maschinenlesbare Domänenontologie**, beschreiben diese formal und bereiten sie für die maschinelle Verarbeitung vor. Dabei wenden Sie die zuvor erarbeiteten Methoden und Strategien der semantischen Modellierung praktisch an.

---

## Bibliografie

(Gruber, 1993) Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

(Noy & McGuiness, 2001) Noy, N. F., & McGuinness, D. L. (2001). Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory.

(Uschold & King, 1995) Uschold, M., & King, M. (1995). Towards an Methodology for Building Ontologies. Presented at Workshop on Basic Ontological Issues in Knowledge Sharing held in conjunction with IJCAI. The University of Edinburgh.
