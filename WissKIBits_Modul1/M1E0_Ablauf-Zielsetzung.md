<!--
author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk ()

email: c.hastik@igsd-ev.de

email: g.schwenk@igsd-ev.de

version:  v1

language: DE

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/liascript-oers/refs/heads/main/resources/SODa-Logo_full.svg
link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/SODa_WissKI-ISWC25Bits/refs/heads/main/soda.css

license: CC BY 4.0

comment: Dieser Text erscheint als Info innerhalb der Liascript-Module oben rechts hinter dem (i) und sollte den Inhalt des Moduls kurz beschreiben. Vorschlag: Mirco-Content zum Lernziel "Lernende können FAIR-Prinzipien erläutern". Dieses Modul ist Teil eines Einführungskurses zum Forschungsdatenmanagement, der von “OER.Net UAG FDM-Basiskurs” auf Grundlage der Lernzielmatrix zum FDM entwickelt wurde. Der Basiskurs entwickelt das Konzept der EduBricks weiter und ist als “Arbeitsgruppe 3: Einbettung und Vernetzung des modularen und skalierbaren Konzeptes” zudem Teil der NFDI-Sektion Education and Training.

title: Template für die Erarbeitung eines Micro-Contents anhand eines Lernziels für generischen FDM-Basiskurs

description: Dieses Template wurde als Vorlage für die Entwicklung von Microlearning-Content zum Themenbereich Forschungsdatenmanagement (FDM) in Orientierung an Lernzielen der [Lernzielmatrix zum Forschungsdatenmanagement (FDM)](https://zenodo.org/records/15025246) entwickelt.

keywords: FDM, Forschungsdatenmanagement, Forschungsdaten, Lernziel, Micro-Content

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: noch unveröffentlicht

LearningResourceType: SODa How-to-Tutorial

-->


# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 1: **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären**

Einheit 1: **Willkommen, Zielsetzung und Ablauf**  

**Dauer:** ~ 5 Min.


---

## Begrüßung

> Willkommen zu **WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten**.
>
> Dieses How-to-Tutorial führt praxisorientiert in die ontologiegestützte Modellierung von Forschungsdaten ein. Ausgehend von Informationen zu einem Sammlungsobjekt wird schrittweise ein semantisch aussagekräftiges Datenmodell entwickelt und für die spätere Implementierung in WissKI vorbereitet.
>
> In Modul 1 **„Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären“** erarbeiten wir die konzeptuelle Grundlage dieses Datenmodells. Dafür analysieren wir Objektdaten und Kontextinformationen aus einer fachlichen Domäne. Wir identifizieren relevante Konzepte, Ereignisse und Beziehungen, präzisieren ihre Bedeutung und gleichen sie mit Klassen und Eigenschaften des Referenzmodells CIDOC CRM ab.
>
> Ziel ist es, die fachliche Logik einer Domäne so zu dokumentieren, dass Modellierungsentscheidungen nachvollziehbar werden und Forschungsdaten später konsistent erfasst, verknüpft, ausgewertet und nachgenutzt werden können.
>
> Das Modul ist als **Learning-by-Doing-Tutorial** für die **Wissenschaftliche Kommunikationsinfrastruktur WissKI** konzipiert. An einem Beispiel aus der Domäne Computerspiele wechseln wir von der Sammlungsperspektive in die Modellperspektive. Das entstehende konzeptuelle Modell bildet die Grundlage für ein Diagramm und für die spätere technische Umsetzung im WissKI Pathbuilder.
>
> Weiterführende Einheiten übertragen dieses Vorgehen auf eigene Forschungsdaten und vertiefen die formale Modellierung sowie die Implementierung in WissKI.

---

## Warum semantisch modellieren?

- Forschungs- und Sammlungsdaten sind komplexe Objekt- und Kontextdaten. Sie beschreiben nicht nur Objekte und ihre Eigenschaften. Sie entstehen im Kontext fachwissenschaftlicher Forschung und sind mit historischen, kulturellen und sozialen Bedeutungen und Zusammenhängen verbunden.
- Tabellen bilden einzelne Eigenschaften und Informationen ab, während die Bedeutung und Zusammenhänge der Daten häufig implizit bleiben.
- Damit Daten langfristig inhaltlich interpretierbar und nachnutzbar bleiben, muss ihre Bedeutung explit gemacht und formal beschrieben werden (Fichtner2025paths, S. 58).

---

## Zielsetzung des Moduls

In Modul 1 wird die konzeptionelle Basis für ein Domänenmodell geschaffen. Aus der Sammlungsperspektive entsteht eine Modellperspektive.

- Objektdaten & deren Kontext werden analysiert.
- Zentrale Konzepte der Objektdaten werden identifiziert und durch zugehörige Ereignisse und Beziehungen kontextualisiert. 
- Abgleich der identifizierten Domänenkonzepte, Ereignisse und Beziehungen mit entsprechenen Klassen (Entities) und Eigenschaften (Properties) des CIDOC CRM
- Daraus entsteht schrittweise eine ontologiebasierte Domänenstruktur bzw. -logik mit CIDOC CRM.
- Diese Domänenlogik wird visualisiert und dient als Grundlage für das sammlungsbezogene Datenmanagement und die -verwaltung in WissKI.
- Die entwickelte Domänenlogik wird in Draw.io visualisiert und für die spätere Umsetzung in WissKI vorbereitet.

---

## Leitfrage

> **Wie wird aus den Informationen zu einem Sammlungsobjekt ein nachvollziehbares, interoperables und in WissKI umsetzbares semantisches Datenmodell?**

Diese Leitfrage begleitet alle Einheiten des Moduls. Dabei wird zwischen drei Ebenen unterschieden:

| Ebene | Leitfrage | Ergebnis |
|---|---|---|
| Sammlungsperspektive | Welche Informationen und Forschungsfragen sind relevant? | fachliche Anforderungen |
| Modellperspektive | Welche Konzepte, Ereignisse und Beziehungen drücken ihre Bedeutung aus? | konzeptuelles Domänenmodell |
| Umsetzungsperspektive | Wie werden diese Strukturen mit CIDOC CRM und WissKI formal abgebildet? | Grundlage für Diagramm und Pathbuilder |

---

## Ablauf des Moduls

**Gesamtdauer Modul 1: ca. 90 Min.**

| Einheit | Inhalt | Dauer |
|---|---|---:|
| 0 | Willkommen, Zielsetzung und Ablauf | 5 Min. |
| 1 | Grundbegriffe konzeptueller Wissensmodellierung | 15 Min. |
| 2 | Grundlagen von Ontologien | 10 Min. |
| 3 | Einführung in CIDOC CRM | 15 Min. |
| 4 | FAIR-Konformität mit WissKI | 15 Min. |
| Ü | Anwendungsbeispiel Objektsammlungen: Modellskizze „Zelda“ | 15 Min. |
|  | **Gesamt** | **90 Min.** |

---

## Lernziele des Moduls (zum Schluss abgleichen - todo Gudrun)

Nach Abschluss von Modul 1 können die Teilnehmenden…

### 1. Grundbegriffe konzeptueller Wissensmodellierung
   
* Begriff Attribut benennen. (LZ-ID SODa\_xy\_xyz\_xyza)
* Begriff semantische Modellierung benennen. (LZ-ID SODa\_03\_007\_0825)
* Begriff semantisches Datenmodell benennen (LZ-ID SODa\_xy\_xyz\_xyza)
* Begriff Domäne benennen. (LZ-ID SODa\_03\_007\_0824)
* Begriff Konzept benennen. (LZ-ID SODa\_03\_007\_0821)
* Begriff Ereignis benennen. (LZ-ID SODa\_03\_007\_0822)
* Begriff Beziehung benennen. (LZ-ID SODa\_03\_007\_0823)

### 2. Grundlagen von Ontologien
   
- den Begriff Ontologie benennen. (LZ-ID SODa\_03\_007\_0826)
- den Begriff Ontologie erläutern. (LZ-ID 03\_007\_0775)
- den Begriff Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0827)
- den Begriff Domänenontologie erläutern. (LZ-ID SODa\_03\_007\_0828)
- den Aspekte von Ontologien benennen. (LZ-ID 03\_007\_0776)

### 3. Bausteine von Ontologien

- Begriff Klassen (Classes/Concepts) benennen. (LZ-ID SODa\_03\_007\_0829)
- Begriff Klassen (Classes/Concepts) erläutern. (LZ-ID SODa\_03\_007\_0830)
- Begriff Instanzen (Instances) benennen. (LZ-ID SODa\_03\_007\_0833)
- Begriff Instanzen (Instances) erläutern. (LZ-ID SODa\_03\_007\_0834)
- Begriff Eigenschaften (Properties) benennen. (LZ-ID SODa\_03\_007\_0831)
- Begriff Eigenschaften (Properties) erläutern. (LZ-ID SODa\_03\_007\_0832)
- Begriff Modellannahmen (Constraints) benennen. (LZ-ID SODa\_03\_007\_0835)
- Begriff Modellannahmen (Constraints) erläutern. (LZ-ID SODa\_03\_007\_0836)
 
### 4. Einführung in CIDOC CRM

- Ontologie zur Beschreibung von Ressourcen bennen. (LZ-ID 03\_007\_0778)
- Ontologie zur Beschreibung von Ressourcen erläutern. (LZ-ID 03\_007\_0779)
- Nutzen des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0805)
-  ???Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0784a)
- Methode der ereigniszentrierten Modellierung mit dem Referenzmodell CIDOC CRM erläutern. (LZ-ID SODa\_03\_007\_0785a)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung benenen. (LZ-ID SODa\_03\_007\_0806)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung erläutern. (LZ-ID SODa\_03\_007\_0807)
- Begriff Scope Notes benennen. (LZ-ID SODa\_03\_007\_0837)
- Begriff Scope Notes erläutern. (LZ-ID SODa\_03\_007\_0838)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0841)
- Formale Beschreibungssprache W3C Web Ontology Language (OWL) benennen. (LZ-ID SODa\_03\_007\_0842)
- Resource Description Framework (RDF) als Standard zur Beschreibung von Ressourcen benennen. (LZ-ID SODa\_03\_007\_0843)

### 5. FAIR, Forschungsinfrastrukturen und WissKI

- für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen erläutern. (LZ-ID SODa\_01\_010\_0203)
- ???das 5-Sterne-Modell für offene Daten benennen. (LZ-ID SODa\_01\_008\_0172)
- FAIR Prinzipien benennen. (LZ-ID 01\_007\_0117)
- geeignete Technologien zur Unterstützung der Anwendung der FAIR-Prinzipien benennen. (LZ-ID 01\_007\_0121)
- die spezifischen Funktionen und Anwendungsbereiche der Wissenschaftlichen Kommunikationsinfrastruktur WissKI benennen. (LZ-ID SODa\_01\_010\_0191a)
- die spezifischen Funktionen und Anwendungsbereiche der Wissenschaftlichen Kommunikationsinfrastruktur WissKI erläutern. (LZ-ID SODa\_01\_010\_0192a)
- Leistungsfähigkeit und Effizienz von IT-Infrastrukturen für das sammlungsbezogene Forschungsdatenmanagement (FDM) mit der Wissenschaftlichen Kommunikationsinfrastuktur WissKI benennen. (LZ-ID SODa\_01\_010\_0202)
- WissKI Pathbuilder als Werkzeug zur Definition einer Ontologiestruktur bennenen. (LZ-ID SODa\_03\_007\_0803)

---

## Lernweg im Modul

```mermaid
flowchart TD
    A["Sammlungsobjekt und Forschungsfrage"] --> B["Konzepte, Ereignisse und Beziehungen"]
    B --> C["Klassen, Eigenschaften und Modellannahmen"]
    C --> D["Abgleich mit CIDOC CRM"]
    D --> E["Modellskizze und begründete Entscheidungen"]
    E --> F["Vorbereitung für WissKI Pathbuilder"]
```

> **Abbildung:** Die Grafik veranschaulicht den Lernweg des Moduls.
> 
---

## Arbeitsweise und Beispiel

Das Modul verbindet kurze fachliche Inputs mit Aktivierung und Anwendung:

- Begriffe werden anhand typischer Informationen aus Sammlungen eingeführt.
- Modellierungsentscheidungen werden gemeinsam diskutiert und begründet.
- Das Beispielobjekt **„The Legend of Zelda: A Link to the Past“** dient als roter Faden.
- In der Übung entwickeln die Teilnehmenden eine kleine Modellskizze und gleichen ausgewählte Konzepte mit CIDOC CRM ab.
- Die Ergebnisse werden im Plenum gesichert und auf die eigene Sammlungspraxis übertragen.

Das Ziel ist kein vollständiges Datenmodell. Entscheidend ist ein **kleiner, konsistenter und begründbarer Modellentwurf**, der später erweitert und technisch umgesetzt werden kann.

---

## Voraussetzungen

Es werden **keine Vorkenntnisse in Ontologien, RDF, OWL, CIDOC CRM oder WissKI** vorausgesetzt.

Hilfreich sind:

- Erfahrungen mit Sammlungs-, Objekt- oder Forschungsdaten,
- ein Beispielobjekt aus der eigenen Sammlung oder Forschung,
- typische Forschungsfragen oder Dokumentationsanforderungen aus dem eigenen Arbeitsbereich.

---

## Ergebnis des Moduls

Am Ende von Modul 1 liegt eine erste konzeptuelle Modellskizze der Domänenlogik vor. Sie zeigt:

- die für das Beispiel relevanten Konzepte und Ereignisse,
- ihre semantischen Beziehungen,
- erste Zuordnungen zu Klassen und Eigenschaften des CIDOC CRM,
- sowie begründete Modellierungsentscheidungen.

Diese Skizze dient als Ausgangspunkt für die weitere Formalisierung und Implementierung in WissKI.

---

## Ausblick

In der folgenden Einheit werden zunächst die Grundbegriffe der konzeptuellen Wissensmodellierung geklärt. 

Anschließend führt das Modul von Ontologien und ihren Bausteinen über CIDOC CRM und FAIR bis zur  konzeptuelle Modellskizze der Domänenlogik. 

Die technische Umsetzung des Modells mit CIDOC CRM und im WissKI Pathbuilder wird in den weiterführenden Modulen behandelt.

---

## Redaktionelle Hinweise

- Die Zeitplanung ist auf insgesamt 90 Minuten abgestimmt und kann je nach Gruppengröße angepasst werden.
- Lernziele zur **Anwendung von Scope Notes**, zur **Anwendung von Ontologien**, zur **Software Protégé**, zum vollständigen Modellierungsworkflow und zur **Erläuterung des Pathbuilders** sind Inhalte für die weiterführenden Module.

## Bibliografie

[Fichtner2025paths] Fichtner, M. (2025). Grundlagen der Erzeugung und Verwaltung von Ontologiepfaden und ihre Anwendung (Doctoral thesis, Friedrich-Alexander-Universität Erlangen-Nürnberg, Technische Fakultät). https://doi.org/10.25593/open-fau-2143
