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

unit: Willkommen, Zielsetzung und Ablauf

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 2 (M2): **Modellieren mit CIDOC CRM – verstehen und anwenden**

Einheit 0 (E0): **Willkommen, Zielsetzung und Ablauf**  

**Dauer:** ~ 10 Min.


---

## Begrüßung

> Willkommen zu **WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten**.
>
> Dieses How-to-Tutorial führt praxisorientiert in die ontologiegestützte Modellierung von Forschungsdaten ein. Ausgehend von Informationen zu einem Beispielobjekt wird schrittweise ein semantisch aussagekräftiges Datenmodell entwickelt und für die spätere Implementierung in WissKI vorbereitet.
>
> In Modul 1 haben Sie eine konzeptuelle Modellskizze entwickelt und untersucht, wie ausgewählte Konzepte und Beziehungen mithilfe von CIDOC CRM abgebildet werden können.
>
> Modul 2 **„Modellieren mit CIDOC CRM – verstehen und anwenden“** führt diesen Lernweg fort. Die bisherigen Modellierungsentscheidungen werden systematisch überprüft und ausgewählte Teile der Modellskizze mithilfe von **Protégé und einer OWL-Implementierung des CIDOC CRM** formalisiert. Dabei werden Modellierungsentscheidungen anhand der Scope Notes des CIDOC CRM fachlich begründet und in einer maschinenlesbaren Ontologiestruktur umgesetzt.
>
> Das Modul folgt weiterhin dem Prinzip **Learning by Doing**. Am Beispiel des Computerspiels **„The Legend of Zelda: A Link to the Past“** wird gezeigt, wie aus einer konzeptuellen Modellskizze eine formale Ontologiestruktur entsteht. Die Teilnehmenden lernen Protégé als Ontologie-Editor kennen, erkunden eine OWL-Implementierung des CIDOC CRM, verwenden bestehende Ontologieelemente wieder und ergänzen bei Bedarf ausgewählte domänenspezifische Erweiterungen.
>
> **Ergebnis:** Ein kleiner, dokumentierter und maschinenlesbarer Modellausschnitt in OWL, der die Grundlage für die Visualisierung und die anschließende Arbeit mit dem WissKI Pathbuilder in Modul 3 bildet.

---

## Leitfrage

> **Wie wird aus einer konzeptuellen Modellskizze eine fachlich begründete und maschinenlesbare Ontologiestruktur auf Basis von CIDOC CRM?**

Diese Leitfrage begleitet alle Einheiten des Moduls. Dabei wird zwischen drei miteinander verbundenen Arbeitsschritten unterschieden:

| Arbeitsschritt | Leitfrage | Ergebnis |
|---|---|---|
| Methodisch planen und konzeptuell prüfen | Welche Schritte und Modellierungsentscheidungen sind erforderlich? Welche Konzepte und Beziehungen lassen sich mit CIDOC CRM abbilden? | Modellierungsworkflow und überprüfte Modellskizze |
| Fachlich begründen | Passen die gewählten CIDOC-CRM-Elemente gemäß ihren Scope Notes zur beabsichtigten Aussage? Welche domänenspezifischen Erweiterungen sind erforderlich? | Fachlich begründete Modellierungsentscheidungen |
| Formal umsetzen | Wie werden Klassen (Entities) und Eigenschaften (Properties) in Protégé wiederverwendet oder ergänzt? | Dokumentierte, maschinenlesbare Ontologiestruktur in OWL |

Die formale Ontologieentwicklung in Protégé ist dabei von der anschließenden **technischen Implementierung in WissKI** zu unterscheiden. Die Einbindung der Ontologie und die Konfiguration semantischer Pfade im WissKI Pathbuilder erfolgen in Modul 3.

---

## Zielsetzung des Moduls

In Modul 2 werden ausgewählte Teile des konzeptuellen Domänenmodells aus Modul 1 mithilfe von CIDOC CRM und Protégé formalisiert.

Die Teilnehmenden lernen,

- einen systematischen **Workflow für die semantische Modellierung** anzuwenden,
- **Protégé** zur Erkundung und Bearbeitung einer OWL-Ontologie einzusetzen,
- geeignete **Klassen (Entities) und Eigenschaften (Properties) des CIDOC CRM** anhand ihrer Scope Notes auszuwählen,
- zwischen der Wiederverwendung bestehender Ontologieelemente und der Einführung domänenspezifischer Erweiterungen zu unterscheiden,
- ausgewählte **domänenspezifische Konzepte** in eine bestehende Ontologiestruktur einzubinden,
- Modellierungsentscheidungen fachlich zu begründen, formal umzusetzen und zu dokumentieren,
- die resultierende Ontologiestruktur in einem maschinenlesbaren **OWL-Format** zu speichern und
- sie für die weitere technische Implementierung in **WissKI** in Modul 3 vorzubereiten.

---

## Ablauf des Moduls

**Gesamtdauer Modul 2: ca. 90 Min.**

| Einheit | Inhalt | Dauer |
|---|---|---:|
| M2U0 | Willkommen, Zielsetzung und Ablauf | 10 Min. |
| M2U1 | Methoden und Workflows semantischer Modellierung | 10 Min. |
| M2U1A | Aktivierung: Arbeitsumgebung mit Protégé vorbereiten | 15 Min. |
| M2U2 | Einführung in Protégé | 10 Min. |
| M2UE | Übung: Semantische Modellierung mit CIDOC CRM | 45 Min. |
| | **Gesamt** | **90 Min.** |
  
---

## Lernziele des Moduls

Nach Abschluss von Modul 2 können die Teilnehmenden…

### E1. Methoden und Workflows semantischer Modellierung

- Methoden zur Entwicklung von Ontologien benennen. (LZ-ID 03\_007\_0784)
- Methoden zur Entwicklung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0839)
- einen Workflow für die semantische Modellierung als Datendokumentation benennen. (LZ-ID SODa\_03\_001\_0626)
- einen Workflow für die semantische Modellierung als Datendokumentation erläutern. (LZ-ID SODa\_03\_001\_0853)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (SODa\_03\_007\_0784a)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM erläutern. (SODa\_03\_007\_0785a)

### E3/E2A. Einführung in Protégé

- Software zur Erstellung von Ontologien benennen. (LZ-ID SODa\_03\_007\_0809)
- Software zur Erstellung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0810)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0841)
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0840)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0784a)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM erläutern. (SODa\_03\_007\_0785a)

### EÜ. Semantische Modellierung mit CIDOC CRM

- Ontologie zur Beschreibung von Ressourcen anwenden. (LZ-ID 03\_007\_0780)
- Methoden zur Entwicklung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0854)
- einen Workflow für die semantische Modellierung als Datendokumentation anwenden (LZ-ID SODa\_03\_001\_0627)
- unter Anleitung Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM anwenden. (LZ-ID SODa\_03\_001\_0786a) 
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa_03_007_0840)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM anwenden. (LZ-ID SODa_03_007_0855)
- Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa\_03\_007\_0780a)


---

## Lernweg im Modul

Ausgehend von der konzeptuellen Modellskizze aus Modul 1 durchlaufen die Teilnehmenden folgende Schritte:

**Modellierungsmethoden kennenlernen (M2U1):** Unterschiedliche Ansätze und einen iterativen Workflow zur Entwicklung von Ontologien kennenlernen.

↓

**Arbeitsumgebung vorbereiten (M2U1A):** Protégé Desktop oder WebProtégé für die praktische Arbeit einrichten.

↓

**Protégé erkunden (M2U2):** Eine bestehende Ontologie laden, ihre Struktur untersuchen und eine domänenspezifische Subklasse anlegen.

↓

**Modell formalisieren (M2UE):** Ausgewählte Zuordnungen zu CIDOC CRM überprüfen, fachlich begründete Erweiterungen umsetzen und Modellierungsentscheidungen dokumentieren.

↓

**Ergebnis:** Ein ausgewählter Teil des Domänenmodells liegt als formale Ontologiestruktur in OWL vor. Die fachlichen Überlegungen und Modellierungsentscheidungen sind dokumentiert.

---

## Arbeitsweise und Beispiel

Das Modul verbindet methodischen Input, Demonstration und angeleitete Anwendung. Kurze methodische Einführungen wechseln sich mit Demonstrationen und praktischen Modellierungsaufgaben ab:

- Die Teilnehmenden lernen grundlegende Methoden und einen iterativen Workflow der Ontologieentwicklung kennen.
- Die Bedienoberfläche und die zentralen Bereiche von Protégé werden in einer Live- oder Video-Demonstration vorgestellt.
- Die OWL-Implementierung **[Erlangen CRM](https://erlangen-crm.org/current-version)** (Schiemann, 2024) wird geladen und anhand ihrer Klassen, Objekteigenschaften und Datentyp-Eigenschaften erkundet.
- Das Beispielobjekt **„The Legend of Zelda: A Link to the Past“** und die in Modul 1 entwickelte Modellskizze dienen erneut als roter Faden.
- Ausgewählte Konzepte werden anhand der Scope Notes mit CIDOC CRM abgeglichen und Modellierungsentscheidungen fachlich begründet.
- Domänenspezifische Konzepte wie Spielmerkmal, Plattformtyp, Genretyp oder Editionstyp werden hinsichtlich ihrer geeigneten ontologischen Repräsentation geprüft und bei Bedarf als Subklassen oder durch andere geeignete Ontologieelemente modelliert.
- Passende Beziehungen zwischen Konzepten und Ereignissen werden ausgewählt und bei Bedarf durch domänenspezifische Eigenschaften ergänzt.
- Die Teilnehmenden dokumentieren ihre Entscheidungen und prüfen das Modell schrittweise auf Verständlichkeit und Konsistenz.

Das Ziel ist keine vollständige Domänenontologie. Entscheidend ist eine **kleine, nachvollziehbare und formal nutzbare Erweiterung von CIDOC CRM**, die den Übergang zur technischen Implementierung in WissKI vorbereitet.

---

## Voraussetzungen

Vorausgesetzt werden die Inhalte aus Modul 1 oder vergleichbare Grundkenntnisse sowie eine erste konzeptuelle Modellskizze, idealerweise auf Basis von CIDOC CRM.

Die Teilnehmenden sollten…

- die Begriffe Domäne, Konzept, Ereignis und Beziehung unterscheiden können,
- die Bausteine Klassen (Entities), Eigenschaften (Properties), Instanzen (Instances) und Modellannahmen (Assumptions) kennen,
- das Grundprinzip der ereigniszentrierten Modellierung mit CIDOC CRM verstanden haben,
- Scope Notes als Grundlage für Modellierungsentscheidungen kennen,
- sowie wenigstens eine erste konzeptuelle Modellskizze, idealerweise ein CIDOC-CRM-basiertes semantisches Domänenmodell, mitbringen.

Für die praktische Anwendung werden benötigt:

- eine **konzeptuelle Modellskizze** aus Modul 1 oder aus einem eigenen Modellierungskontext,
- ein Computer mit installiertem **Protégé Desktop** oder Zugang zu **WebProtégé**,
- die im Tutorial verwendete **OWL-Implementierung des CIDOC CRM (Erlangen CRM)**, die lokal verfügbar oder über eine Webadresse erreichbar sein muss.

Informationen zu Protégé Desktop und WebProtégé finden sich auf der Webseite der [Stanford University](https://protege.stanford.edu/software) (Stanford, o. D., Protégé).

---
 
## Ergebnis des Moduls

Am Ende von Modul 2 liegt ein erster formal umgesetzter Ausschnitt einer Domänenontologie beziehungsweise eine Ontologieerweiterung vor.

Die Teilnehmenden haben:

- ausgewählte Modellierungsentscheidungen anhand der Scope Notes des CIDOC CRM überprüft und fachlich begründet,
- relevante Klassen (Entities) und Eigenschaften (Properties) des CIDOC CRM erkundet und wiederverwendet,
- ausgewählte domänenspezifische Erweiterungen erstellt und fachlich begründet,
- zentrale Modellierungsentscheidungen dokumentiert,
- und einen ausgewählten Modellausschnitt in einem maschinenlesbaren **OWL-Format** gespeichert.

Es wird nicht erwartet, dass eine vollständige Ontologie für die Domäne Computerspiele entwickelt wird. Im Mittelpunkt steht ein **kleiner, verständlicher, fachlich begründeter und formal repräsentierter Modellausschnitt**.

Die gespeicherte Ontologiestruktur bildet die Grundlage für die anschließende Visualisierung und technische Implementierung in WissKI.

---

## Ausblick

> **Als Nächstes:**
>
> Sie erfahren, wie **unterschiedliche Modellierungsansätze und Workflows** die Entwicklung einer Domänenontologie unterstützen.

---

## Redaktionelle Hinweise

- Die Zeitplanung ist auf insgesamt 90 Minuten abgestimmt und kann je nach Umfang der praktischen Übung angepasst werden.


  
  
 
