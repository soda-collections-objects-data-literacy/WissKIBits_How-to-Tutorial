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

title: WissKI Bits: Ontologiebasierte Modellierung von Forschungsdaten

module: Modellieren mit CIDOC CRM – verstehen und anwenden

unit: Willkommen, Zielsetzung und Ablauf

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontologiebasierte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 2 (M2): **Modellieren mit CIDOC CRM – verstehen und anwenden**

Einheit 0 (E0): **Willkommen, Zielsetzung und Ablauf**  

**Dauer:** ~ 10 Min.


---

## Willkommen bei WissKI Bits: Ontologiebasierte Modellierung von Forschungsdaten

In **Modul 2: Modellieren mit CIDOC CRM – verstehen und anwenden** lernen Sie, wie eine konzeptuelle Modellskizze schrittweise in eine **formale Ontologiestruktur** überführt werden kann.

Ausgehend von der in **Modul 1: Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären** entwickelten Modellskizze überprüfen und präzisieren Sie Ihre bisherigen Modellierungsentscheidungen.

Anhand des Beispiels aus der **Computerspielsammlung** untersuchen Sie, welche Klassen und Eigenschaften des Referenzmodells **CIDOC CRM** für die Beschreibung der ausgewählten Konzepte, Ereignisse und Beziehungen geeignet sind.

Dabei lernen Sie, wie Sie bestehende Ontologieelemente wiederverwenden, bei Bedarf domänenspezifische Erweiterungen entwickeln und Ihre Modellierungsentscheidungen anhand der Scope Notes des CIDOC CRM fachlich begründen können.

Anschließend setzen Sie ausgewählte Teile Ihrer Modellskizze mithilfe des Ontologie-Editors **Protégé** und einer OWL-Implementierung des CIDOC CRM formal um.

Die entstehende maschinenlesbare Ontologiestruktur bildet die Grundlage für die weitere Visualisierung und technische Implementierung in **Modul 3: Vom Diagramm zu Pfaden – erläutern und anwenden**.

> **Worum geht es in diesem Modul?**
>
> Ausgehend von einer konzeptuellen Modellskizze untersuchen Sie, wie ausgewählte Konzepte, Ereignisse und Beziehungen mithilfe von CIDOC CRM formal beschrieben werden können.
>
> Sie überprüfen und begründen Ihre Modellierungsentscheidungen, verwenden bestehende Ontologieelemente wieder und ergänzen diese bei Bedarf um domänenspezifische Elemente.
>
> Mithilfe von **Protégé** überführen Sie ausgewählte Teile Ihrer Modellskizze in eine **maschinenlesbare formale Ontologiestruktur in OWL**.
>
> Die entstandene Ontologiestruktur dient als Ausgangspunkt für die Visualisierung und technische Implementierung in **Modul 3: Vom Diagramm zu Pfaden – erläutern und anwenden**.

---

## Warum Ontologien formal modellieren?

- Konzeptuelle Modellskizzen machen fachliche Konzepte, Ereignisse und Beziehungen sowie deren Bedeutungszusammenhänge sichtbar und verständlich.
- Damit diese Bedeutungszusammenhänge auch von Computersystemen verarbeitet und in unterschiedlichen Anwendungskontexten genutzt werden können, müssen sie formal und maschinenlesbar beschrieben werden.
- Die Wiederverwendung bestehender Ontologien wie CIDOC CRM unterstützt eine gemeinsame semantische Grundlage und damit die Interoperabilität von Forschungs- und Sammlungsdaten.
- Domänenspezifische Erweiterungen ermöglichen es, zusätzliche fachliche Anforderungen abzubilden, die durch das Referenzmodell allein nicht hinreichend beschrieben werden können.
- Die formale Beschreibung und Dokumentation von Modellierungsentscheidungen schafft eine Grundlage für die technische Implementierung und langfristige Nachnutzung eines Datenmodells.

> Eine konzeptuelle Modellskizze macht fachliche Bedeutungszusammenhänge verständlich.
>
> Eine formale Ontologie in OWL/RDF beschreibt diese Zusammenhänge in einer maschinenlesbaren Form.
>
> **Die formale Modellierung schafft eine Grundlage dafür, fachliches Wissen interoperabel zu repräsentieren und in technischen Systemen zu nutzen.**

---

## Leitfrage

Die Leitfrage, die uns durch dieses Modul begleitet, lautet:

> **Wie kann eine konzeptuelle Modellskizze in eine fachlich begründete und maschinenlesbare Ontologiestruktur auf Grundlage von CIDOC CRM überführt werden?**

---

## Zielsetzung des Moduls

In diesem Modul lernen Sie, wie Sie auf Grundlage der konzeptuellen Modellskizze zum Sammlungsobjekt „Zelda“ ausgewählte Teile eines semantischen Datenmodells mithilfe von CIDOC CRM und Protégé formal umsetzen.

Am Ende des Moduls sind Sie in der Lage,

- einen systematischen **Workflow für die semantische Modellierung** zu erläutern und unter Anleitung anzuwenden,
- ausgewählte **Klassen und Eigenschaften des CIDOC CRM** anhand ihrer Scope Notes zu untersuchen und für die Modellierung auszuwählen,
- zwischen der Wiederverwendung bestehender Ontologieelemente und der Einführung domänenspezifischer Erweiterungen zu unterscheiden,
- den Ontologie-Editor **Protégé** zur Erkundung und Bearbeitung einer OWL-Ontologie anzuwenden,
- ausgewählte **domänenspezifische Konzepte und Beziehungen** in eine bestehende Ontologiestruktur einzubinden,
- Modellierungsentscheidungen fachlich zu begründen, formal umzusetzen und zu dokumentieren,
- einen ausgewählten Modellausschnitt in einem maschinenlesbaren **OWL-Format** zu speichern und
- die entstandene Ontologiestruktur für die weitere Visualisierung und technische Implementierung in **Modul 3: Vom Diagramm zu Pfaden – erläutern und anwenden** vorzubereiten.

---

## Ablauf des Moduls

**Gesamtdauer Modul 2: ca. 90 Min.**

| Einheit | Inhalt | Dauer |
|---|---|---:|
| M2E0 | Willkommen, Zielsetzung und Ablauf | 10 Min. |
| M2E0A | [Aktivierung: Arbeitsumgebung mit Protégé vorbereiten]()| 15 Min. |
| M2E1 | [Methoden und Workflows semantischer Modellierung]() | 5 Min. |
| M2E2 | [Einführung in Protégé] | 10 Min. |
| M2EÜ | Übung: [Semantische Modellierung mit CIDOC CRM] | 50 Min. |
| | **Gesamt** | **90 Min.** |
  
---

## Lernziele des Moduls

Nach Abschluss von Modul 2 können die Teilnehmenden…

### E1. Methoden und Workflows semantischer Modellierung

- Methoden zur Entwicklung von Ontologien benennen. (LZ-ID 03\_007\_0784)
- Methoden zur Entwicklung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0839)
- einen Workflow für die semantische Modellierung als Datendokumentation benennen. (LZ-ID SODa\_03\_001\_0626)
- einen Workflow für die semantische Modellierung als Datendokumentation erläutern. (LZ-ID SODa\_03\_001\_0853)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0784a)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM erläutern. (LZ-ID SODa\_03\_007\_0785a)

### E1A. Arbeitsumgebung mit Protégé vorbereiten

- Software zur Erstellung von Ontologien benennen. (LZ-ID SODa\_03\_007\_0809)
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0840)
- die eigene Erfahrung mit Software zur Erstellung für Ontologien analysieren. (LZ-ID SODa\_03\_007\_0857)


### E2. Einführung in Protégé

- Software zur Erstellung von Ontologien benennen. (LZ-ID SODa\_03\_007\_0809)
- Software zur Erstellung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0810)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0841)
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0840)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0784a)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM erläutern. (LZ-ID SODa\_03\_007\_0785a)

### EÜ. Semantische Modellierung mit CIDOC CRM

- Ontologie zur Beschreibung von Ressourcen anwenden. (LZ-ID 03\_007\_0780)
- Methoden zur Entwicklung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0854)
- einen Workflow für die semantische Modellierung als Datendokumentation anwenden (LZ-ID SODa\_03\_001\_0627)
- unter Anleitung Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM anwenden. (LZ-ID SODa\_03\_007\_0786a) 
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa_03_007_0840)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM anwenden. (LZ-ID SODa_03_007_0855)
- Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa\_03\_007\_0780a)
  

---

## Lernweg im Modul

Ausgehend von der konzeptuellen Modellskizze aus Modul 1 durchlaufen die Teilnehmenden folgende Schritte:

**Modellierungsmethoden kennenlernen (M2E1):** 
Unterschiedliche Ansätze und einen iterativen Workflow zur Entwicklung von Ontologien kennenlernen.

↓

**Arbeitsumgebung vorbereiten (M2E1A):** 
Protégé Desktop oder WebProtégé für die praktische Arbeit einrichten.

↓

**Protégé erkunden (M2E2):** 
Eine OWL-Implementierung des CIDCOC CRM laden, ihre Struktur untersuchen und eine domänenspezifische Subklasse anlegen.

↓

**CIDOC CRM anwenden, formalisieren und Ontologie sichern (M2ÜE):** 
Ausgewählte Zuordnungen zu CIDOC CRM überprüfen, fachlich begründete Erweiterungen umsetzen und Modellierungsentscheidungen dokumentieren.

↓

**Ergebnis:** Ein ausgewählter Teil des Domänenmodells liegt als formale Ontologiestruktur in OWL vor. Die fachlichen Überlegungen und Modellierungsentscheidungen sind dokumentiert.

---

## Arbeitsweise und Beispiel

Das Modul verbindet kurze fachliche und methodische Inputs mit Demonstrationen, Analyse, Diskussion und praktischen Modellierungsaktivitäten:

- Methoden und Workflows der Ontologieentwicklung werden anhand typischer Modellierungsaufgaben eingeführt.
- Die Bedienoberfläche und die zentralen Bereiche von Protégé werden anhand einer Demonstration vorgestellt.
- - Die OWL-Implementierung **[Erlangen CRM](https://erlangen-crm.org/current-version)** (Schiemann, 2024) wird geladen und anhand ihrer Klassen, Objekteigenschaften und Datentyp-Eigenschaften erkundet.
- Das Beispielobjekt **The Legend of Zelda: A Link to the Past** und die in Modul 1 entwickelte Modul 1 [CIDOC CRM Formalisierung](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul1/de/M1E%C3%9C_Anwendungsbeispiel_Objekt.md#1) der konzeptuellen Modellskizze dient erneut als roter Faden.

In der Übung:

 überprüfen die Teilnehmenden ausgewählte Zuordnungen zu CIDOC CRM anhand der Scope Notes und begründen ihre Modellierungsentscheidungen.
- Domänenspezifische Konzepte wie Spielmerkmal, Plattformtyp, Genretyp oder Editionstyp werden hinsichtlich ihrer geeigneten ontologischen Repräsentation untersucht.
- Bestehende Klassen und Eigenschaften werden wiederverwendet und bei Bedarf durch geeignete domänenspezifische Subklassen in CIDOC CRM ergänzt.
- Die Ergebnisse werden dokumentiert, auf fachliche Schlüssigkeit und formale Konsistenz geprüft und in einem OWL-Format gespeichert.

Das Ziel ist keine vollständige Domänenontologie. Entscheidend ist ein **kleiner, konsistenter und begründbarer Modellausschnitt**, der formal beschrieben ist und später erweitert und technisch implementiert werden kann.

> **So arbeiten Sie**
>
> Wir beginnen mit einer kurzen Einführung in Methoden und Workflows der Ontologieentwicklung und bereiten anschließend die Arbeitsumgebung mit Protégé vor.
>
> Nach der Einführung in Protégé greifen Sie die konzeptuelle Modellskizze aus Modul 1 [CIDOC CRM Formalisierung](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul1/de/M1E%C3%9C_Anwendungsbeispiel_Objekt.md#1) erneut auf. Sie überprüfen ausgewählte Modellierungsentscheidungen anhand des CIDOC CRM und setzen diese formal um.
>
> Unser gemeinsames Beispiel ist weiterhin das Sammlungsobjekt **The Legend of Zelda: A Link to the Past**.
>
> Die Ergebnisse Ihrer Modellierungsarbeit dokumentieren und speichern Sie als Grundlage für die weitere Arbeit in Modul 3 **(M3): Vom Diagramm zu Pfaden – erläutern und anwenden**.

---

## Voraussetzungen

Vorausgesetzt werden die Inhalte aus **Modul 1: Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären** oder vergleichbare Grundkenntnisse der semantischen Modellierung.

Die Teilnehmenden sollten…

- die Begriffe Domäne, Konzept, Ereignis und Beziehung unterscheiden können,
- die Bausteine Klassen (Entities), Eigenschaften (Properties), Instanzen (Instances) und Modellannahmen (Assumptions) kennen,
- das Grundprinzip der ereigniszentrierten Modellierung mit CIDOC CRM verstanden haben,
- Scope Notes als Grundlage für Modellierungsentscheidungen kennen,
- sowie wenigstens eine erste konzeptuelle Modellskizze, idealerweise ein CIDOC-CRM-basiertes semantisches Domänenmodell, mitbringen.

Für die praktische Anwendung werden benötigt:

- Ihre **CIDOC CRM formalisierte konzeptuelle Modellskizze** aus Modul 1 oder aus einem eigenen Modellierungskontext,
- ein Computer mit installiertem **Protégé Desktop** oder Zugang zu **WebProtégé**,
- die im Tutorial verwendete **OWL-Implementierung des CIDOC CRM (Erlangen CRM)**, die lokal verfügbar oder über eine Webadresse erreichbar sein muss.

Informationen zu Protégé Desktop und WebProtégé finden sich auf der Webseite der [Stanford University](https://protege.stanford.edu/software) (Stanford, 2026a).

---
 
## Ergebnis des Moduls

Am Ende von Modul 2 liegt eine erste **formale Ontologiestruktur in OWL** vor, die ausgewählte Teile der konzeptuellen Modellskizze aus Modul 1 auf Grundlage von CIDOC CRM repräsentiert.

> **Was nehmen Sie aus dem Modul mit?**
>
> Am Ende des Moduls liegt ein erster formal umgesetzter Ausschnitt des semantischen Domänenmodells für Computerspiele vor. Er umfasst:
>
> - ausgewählte Klassen und Eigenschaften des CIDOC CRM,
> - bei Bedarf ergänzte domänenspezifische Ontologieelemente,
> - die formal beschriebenen Beziehungen zwischen den ausgewählten Ontologieelementen,
> - fachlich begründete und dokumentierte Modellierungsentscheidungen,
> - sowie eine maschinenlesbare Repräsentation des Modellausschnitts in OWL.
>
> Diese Ontologiestruktur dient als Ausgangspunkt für die weitere Visualisierung und technische Implementierung in WissKI.

---

## Ausblick

In der folgenden Einheit werden zunächst grundlegende Methoden und Workflows der Ontologieentwicklung vorgestellt und als Grundlage für die weitere semantische Modellierung erläutert.

Anschließend führt Modul 2 von der Vorbereitung der Arbeitsumgebung über die Erkundung einer OWL-Implementierung des CIDOC CRM in Protégé bis zur formalen Umsetzung ausgewählter Teile des semantischen Domänenmodells.

Die Visualisierung der Ontologiestruktur, ihre Einbindung in WissKI und die Konfiguration semantischer Pfade im WissKI Pathbuilder werden in **Modul 3: Vom Diagramm zu Pfaden – erläutern und anwenden** behandelt.

> **Wie geht es weiter?**
>
> In der nächsten Einheit [**M2E0A: Arbeitsumgebung mit Protégé vorbereiten**]() lernen Sie unterschiedliche Ansätze zur Entwicklung von Ontologien kennen.
>
> Sie erfahren, wie ein systematischer und iterativer Modellierungsworkflow die Entwicklung einer Domänenontologie auf Grundlage von CIDOC CRM unterstützen kann.

---

## Bibliografie

(Schiemann, 2024) Schiemann, B., Oischinger, M., Görz, G., Hohmann, G., Merges, J., Fichtner, M., & Scholz, M. (n.d.). Erlangen CRM OWL. University of Erlangen-Nuremberg, Department of Computer Science, Chair of Artificial Intelligence. Retrieved 27 August 2026, from https://erlangen-crm.org/current-version

(Stanford, 2026a) Stanford Center for Biomedical Informatics Research. (2026a). Protégé. Retrieved 15 October 2026, from https://protege.stanford.edu/


## Redaktionelle Hinweise

- Die Zeitplanung ist auf insgesamt 90 Minuten abgestimmt und kann je nach Umfang der praktischen Übung angepasst werden.


  
  
 
