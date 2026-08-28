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


# SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 3: **Vom Diagramm zu Pfaden – Erläutern und anwenden**

Einheit 3: **Vom Pathbuilder zur Wissensbasis**  

**Dauer:** ~  Min.

**Lernziele:**

Teilnehmende können...

- die Struktur eines WissKI-Pathbuilders erläutern;
- Pathbuilder und Ontologie miteinander in Beziehung setzen;
- die Auswirkungen von Modellierungsentscheidungen auf Dateneingabe und -abfrage erläutern;
- die Eignung eines Datenmodells für konkrete Forschungsfragen beurteilen;
- den Zusammenhang zwischen Modellierung, Datenqualität und FAIR-Prinzipien erläutern.


---

## Vom Pathbuilder zur Wissensbasis

In den vorherigen Einheiten haben Sie ein semantisches Datenmodell visualisiert, transformiert und als Pathbuilder-Struktur für WissKI aufbereitet.

Damit ist ein wichtiger Schritt geschafft. Aber was bedeutet die entstandene Struktur für die spätere Arbeit mit den Forschungsdaten?

Ein Datenmodell bestimmt nicht nur, **wie Daten strukturiert werden**. Es legt auch fest,

- welche Informationen erfasst werden können,
- wie Informationen miteinander in Beziehung stehen,
- welche Zusammenhänge später abgefragt werden können und
- wie gut andere die Daten verstehen und nachnutzen können.

In dieser Einheit betrachten Sie deshalb den Pathbuilder aus einer anderen Perspektive: **Welche Auswirkungen haben die zuvor getroffenen Modellierungsentscheidungen auf die entstehende Wissensbasis?**

---

## Die Ontologie als semantische Grundlage

Eine **Ontologie** stellt Klassen, Eigenschaften und mögliche Beziehungen bereit, mit denen Sachverhalte einer Domäne formal beschrieben werden können.

Mit CIDOC CRM kann beispielsweise modelliert werden, dass ein Objekt durch ein Herstellungsereignis entstanden ist, an diesem Ereignis eine Person beteiligt war und das Ereignis an einem bestimmten Ort stattgefunden hat.

Die Ontologie stellt dafür das semantische Vokabular und die möglichen Beziehungen bereit.

## Der Pathbuilder als Implementierung

Für eine konkrete Sammlung oder ein Forschungsprojekt werden in der Regel nur ausgewählte Teile einer Ontologie benötigt.

Der **WissKI Pathbuilder** legt fest, welche Klassen und Eigenschaften für einen konkreten Anwendungskontext verwendet und über welche Pfade sie miteinander verbunden werden.

Ein vereinfachter Pfad könnte beispielsweise lauten:

> Objekt → wurde hergestellt durch → Herstellung → wurde ausgeführt von → Person

Ein solcher Pfad beschreibt nicht nur, **welche Information** erfasst werden soll, sondern auch, **wie diese Information semantisch mit anderen Informationen verbunden ist**.

## Gegenüberstellung 

| Ontologie | WissKI-Pathbuilder |
|---|---|
| stellt Klassen und Eigenschaften bereit | verwendet ausgewählte Klassen und Eigenschaften |
| beschreibt mögliche semantische Beziehungen | verbindet Klassen und Eigenschaften zu konkreten Pfaden |
| bildet den konzeptuellen Bezugsrahmen | konkretisiert diesen Rahmen für einen Anwendungskontext |
| kann in unterschiedlichen Projekten genutzt werden | bildet die für eine konkrete WissKI-Anwendung benötigten Strukturen ab |

> **Hinweis:** Die Ontologie stellt die semantischen Bausteine bereit. Der Pathbuilder legt fest, wie diese Bausteine für die konkrete Wissensbasis verwendet werden.

---

## Begriffsdefinition

**Path**

Ein Path beschreibt eine Folge von Klassen und Eigenschaften innerhalb einer Ontologie. Er verbindet einen Ausgangspunkt mit einer Information oder einer weiteren Entität, die in WissKI erfasst und verarbeitet werden soll.

**Pathbuilder**

Der WissKI Pathbuilder ist ein Werkzeug zur Definition ontologiebasierter Datenstrukturen in WissKI. Er organisiert Pfade und Gruppen und verbindet damit die zugrunde liegende Ontologie mit der konkreten Struktur einer WissKI-Anwendung.

**Modellierungsentscheidung**

Eine Modellierungsentscheidung ist eine begründete Festlegung darüber, wie ein Sachverhalt mithilfe von Klassen, Eigenschaften und Beziehungen repräsentiert wird. Je nach Anwendungsfall können für denselben Sachverhalt unterschiedliche Modellierungsentscheidungen möglich sein.

---

## Quizfragen

### Welche Aussage beschreibt das Verhältnis von Ontologie und Pathbuilder am besten?

- [( )] Der Pathbuilder ersetzt die Ontologie.
- [( )] Die Ontologie wird automatisch aus dem Pathbuilder erzeugt.
- [(x)] Der Pathbuilder verwendet Klassen und Eigenschaften einer Ontologie und verbindet sie zu Pfaden für einen konkreten Anwendungskontext.
- [( )] Ontologie und Pathbuilder sind unterschiedliche Bezeichnungen für dasselbe.

### Was beschreibt ein Path?

- [( )] Einen Speicherort für eine Datei.
- [(x)] Eine Folge von Klassen und Eigenschaften, über die Informationen semantisch miteinander verbunden werden.
- [( )] Eine grafische Darstellung der gesamten Ontologie.
- [( )] Eine einzelne Klasse des CIDOC CRM.

---

## Modellierungsentscheidungen und ihre Auswirkungen

Betrachten wir folgende Aussage:

> *Die Vase wurde 1923 von Anna Beispiel in München hergestellt.*

Diese Aussage enthält mehrere Informationen, die im semantischen Datenmodell als Entitäten und Beziehungen repräsentiert werden können.

| Element | Beschreibung |
|---|---|
| **Vase** | Objekt |
| **Herstellung** | Ereignis |
| **Anna Beispiel** | Person |
| **München** | Ort |
| **1923** | zeitliche Einordnung des Ereignisses |

Bei einer ereigniszentrierten Modellierung werden Person, Ort und Zeit über das Ereignis **Herstellung** mit dem Objekt verbunden.

![Beispiel für eine ereigniszentrierte Modellierung](../assets/ereigniszentrierte-modellierung.png)

Diese Modellierungsentscheidung beeinflusst die spätere Arbeit mit den Daten. Wird eine Person beispielsweise als eigene Entität modelliert, kann sie in unterschiedlichen Zusammenhängen referenziert und mit verschiedenen Objekten und Ereignissen verbunden werden.

Wird der Name einer Person dagegen ausschließlich als unstrukturierter Textwert an einem Objekt gespeichert, bleibt die Information zwar erhalten, ihre Möglichkeiten zur Verknüpfung und strukturierten Abfrage sind jedoch eingeschränkt.

---

## Quizfragen

### Eine Sammlung erfasst den Namen der herstellenden Person ausschließlich als unstrukturierten Text. Welche Folgen kann dies haben?

- [[X]] Dieselbe Person kann in unterschiedlichen Schreibweisen vorkommen.
- [[X]] Informationen über die Person lassen sich schwerer mit anderen Objekten und Ereignissen verknüpfen.
- [[ ]] Die Information kann grundsätzlich nicht gespeichert werden.
- [[X]] Personenbezogene Abfragen können erschwert werden.

### Welche Bereiche können durch Modellierungsentscheidungen beeinflusst werden?

- [[X]] Dateneingabe
- [[X]] Abfragemöglichkeiten
- [[X]] Datenqualität
- [[X]] Nachnutzbarkeit

---

## Von der Forschungsfrage zum Datenmodell

Ein Datenmodell ist nicht allein deshalb für einen Anwendungskontext geeignet, weil es technisch funktioniert.

Entscheidend ist, ob es die Informationen und Beziehungen repräsentiert, die für die **Forschungsfragen eines Projekts** benötigt werden.

Betrachten wir folgende Forschungsfrage:

> *Welche Objekte wurden zwischen 1920 und 1930 in München hergestellt und welche Personen waren an ihrer Herstellung beteiligt?*

Um diese Frage anhand strukturierter Daten beantworten zu können, müssen unterschiedliche Informationen miteinander verknüpft werden.

| Bestandteil der Forschungsfrage | Benötigte Modellierung |
|---|---|
| **Welche Objekte?** | Objekt als identifizierbare Entität |
| **wurden hergestellt** | Herstellungsereignis |
| **zwischen 1920 und 1930** | zeitliche Einordnung des Ereignisses |
| **in München** | Verbindung des Ereignisses mit einem Ort |
| **welche Personen** | Verbindung des Ereignisses mit beteiligten Personen |

Fehlt beispielsweise die Verbindung zwischen Herstellungsereignis und Ort, lässt sich die räumliche Komponente der Forschungsfrage nicht oder nur eingeschränkt anhand der strukturierten Daten beantworten.

> **Hinweis:** Was später strukturiert abgefragt werden soll, muss im Datenmodell in geeigneter Form repräsentiert sein.

---

## Schritte im Überblick

1. **Forschungsfrage formulieren** – Was soll anhand der Daten untersucht werden?
2. **Benötigte Entitäten identifizieren** – Welche Objekte, Personen, Orte, Zeiten oder Ereignisse kommen in der Forschungsfrage vor?
3. **Beziehungen bestimmen** – Welche Zusammenhänge zwischen den Entitäten werden benötigt?
4. **Datenmodell prüfen** – Sind die benötigten Entitäten und Beziehungen vorhanden?
5. **Abfragemöglichkeit beurteilen** – Kann die Forschungsfrage auf Grundlage des Modells beantwortet werden?

---

## Quizfragen

### Ein Datenmodell enthält Objekte, Herstellungsereignisse, Personen und Zeitangaben. Orte werden jedoch nicht modelliert. Welche Forschungsfrage lässt sich mit diesem Modell am wenigsten gut beantworten?

- [( )] Welche Personen waren an der Herstellung eines Objekts beteiligt?
- [( )] Welche Objekte wurden im Jahr 1925 hergestellt?
- [(x)] Welche Objekte wurden zwischen 1920 und 1930 in München hergestellt?
- [( )] Welche Person war an mehreren Herstellungsereignissen beteiligt?

### Wann ist ein Datenmodell für einen konkreten Anwendungsfall geeignet?

- [( )] Wenn es möglichst viele Klassen aus CIDOC CRM verwendet.
- [( )] Wenn es möglichst komplex aufgebaut ist.
- [(x)] Wenn es die für die Forschungsfragen relevanten Sachverhalte und Beziehungen angemessen repräsentiert.
- [( )] Wenn möglichst viele Informationen als Freitext gespeichert werden.

---

## Aufgabe

**Arbeitsform:** Einzelarbeit  
**Material:** eigenes Modellierungsdiagramm und/oder WissKI-Pathbuilder  
**Zeit:** ca. 5–10 Min.

Prüfen Sie einen Ausschnitt Ihres Datenmodells anhand einer konkreten Forschungsfrage.

1. Formulieren Sie eine Forschungsfrage, die mit den Daten Ihrer Sammlung beantwortet werden soll.
2. Identifizieren Sie die Entitäten, die zur Beantwortung benötigt werden.
3. Identifizieren Sie die Beziehungen zwischen diesen Entitäten.
4. Prüfen Sie, ob diese Entitäten und Beziehungen in Ihrem Modell bzw. Pathbuilder vorhanden sind.
5. Überlegen Sie, welche Information aufgrund Ihrer Modellierung eingegeben und später abgefragt werden kann.

**Hinweis:** Es geht nicht darum, die eine „richtige“ Modellierung zu finden. Entscheidend ist, ob die gewählte Modellierung für den konkreten Anwendungsfall geeignet und nachvollziehbar begründet ist.

---

## Ergebnis

Sie haben eine Forschungsfrage mit einem Ausschnitt Ihres Datenmodells abgeglichen und geprüft, ob die benötigten Entitäten und Beziehungen im Modell vorhanden sind.

Sie können damit einschätzen, wie eine Modellierungsentscheidung die spätere Dateneingabe und Abfrage beeinflusst.

![Prüfung eines Datenmodells anhand einer Forschungsfrage](../assets/datenmodell-forschungsfrage.png)

---

## Modellierung, Datenqualität und FAIR-Prinzipien

Modellierungsentscheidungen beeinflussen auch, wie **verständlich, konsistent und nachnutzbar** Forschungsdaten sind.

Werden gleiche Sachverhalte auf unterschiedliche Weise erfasst, können Inkonsistenzen entstehen. Sind Beziehungen nicht eindeutig beschrieben, können Daten schwieriger interpretiert oder mit anderen Datenbeständen verknüpft werden.

Eine nachvollziehbare semantische Modellierung kann daher die Umsetzung der **FAIR-Prinzipien** unterstützen.

| FAIR-Prinzip | Zusammenhang mit semantischer Modellierung |
|---|---|
| **Findable** | Strukturierte Beschreibungen können die gezielte Erschließung und Auffindbarkeit von Daten unterstützen. |
| **Accessible** | Standardisierte Datenstrukturen können die technische Bereitstellung und Verarbeitung unterstützen. |
| **Interoperable** | Gemeinsame Ontologien, kontrollierte Vokabulare und definierte Beziehungen erleichtern die Verbindung unterschiedlicher Datenbestände. |
| **Reusable** | Eindeutige Bedeutungen und dokumentierte Modellierungsentscheidungen erleichtern Interpretation und Nachnutzung. |

Semantische Modellierung macht Forschungsdaten nicht automatisch FAIR. Sie kann jedoch wichtige Voraussetzungen dafür schaffen, dass Daten **eindeutig beschrieben, interoperabel und nachvollziehbar nachnutzbar** sind.

---

## Quizfragen

### Welche Aussage zum Zusammenhang zwischen semantischer Modellierung und FAIR ist richtig?

- [( )] Sobald Forschungsdaten in WissKI gespeichert werden, sind sie automatisch FAIR.
- [( )] FAIR bedeutet, dass alle Forschungsdaten frei heruntergeladen werden können.
- [(x)] Eine nachvollziehbare semantische Modellierung kann insbesondere Interoperabilität und Nachnutzbarkeit von Forschungsdaten unterstützen.
- [( )] Die Modellierung von Beziehungen zwischen Daten ist für FAIR nicht relevant.

### Welche Maßnahmen können die Nachnutzbarkeit semantisch modellierter Forschungsdaten unterstützen?

- [[X]] Verwendung etablierter Ontologien
- [[X]] eindeutige Beschreibung von Beziehungen
- [[X]] konsistente Modellierungsentscheidungen
- [[ ]] möglichst viele unstrukturierte Freitextangaben

---

## Abschlussquiz

### Welche Aufgabe übernimmt der WissKI-Pathbuilder?

- [( )] Er ersetzt das CIDOC CRM.
- [(x)] Er definiert für eine konkrete WissKI-Anwendung Pfade durch eine zugrunde liegende Ontologiestruktur.
- [( )] Er dient ausschließlich der grafischen Visualisierung einer Ontologie.

### Warum sollten Forschungsfragen bei der Modellierung berücksichtigt werden?

- [(x)] Weil sie helfen zu bestimmen, welche Entitäten und Beziehungen im Modell benötigt werden.
- [( )] Weil jede Forschungsfrage eine eigene Ontologie benötigt.
- [( )] Weil Forschungsfragen automatisch in WissKI-Abfragen umgewandelt werden.

### Welche Aussagen über Modellierungsentscheidungen sind richtig?

- [[X]] Sie können beeinflussen, welche Informationen eingegeben werden können.
- [[X]] Sie können beeinflussen, welche Zusammenhänge später abgefragt werden können.
- [[X]] Sie können Auswirkungen auf Datenqualität und Nachnutzbarkeit haben.
- [[ ]] Nach dem Import eines Pathbuilders spielen sie keine Rolle mehr.

### Welche Abfolge beschreibt den Zusammenhang zwischen Forschungsfrage und Wissensbasis am besten?

- [( )] Pathbuilder → Forschungsfrage → Ontologie → Daten
- [( )] Daten → FAIR → Forschungsfrage → Pathbuilder
- [(x)] Forschungsfrage → Modellierungsentscheidung → Datenmodell → Pathbuilder → Dateneingabe und Abfrage
- [( )] Ontologie → WissKI → Forschungsfrage → Diagramm

---

## Zusammenfassung

Der **WissKI-Pathbuilder** bildet eine Verbindung zwischen Ontologie, semantischem Datenmodell und konkreter WissKI-Anwendung. Die darin definierten Pfade legen fest, welche semantischen Zusammenhänge für die Erfassung und Verarbeitung der Forschungsdaten genutzt werden.

Modellierungsentscheidungen beeinflussen, welche Informationen eingegeben, wie sie miteinander verknüpft und welche Zusammenhänge später abgefragt werden können.

Ob ein Datenmodell für einen konkreten Anwendungskontext geeignet ist, lässt sich deshalb unter anderem anhand der Forschungsfragen überprüfen, die mit den Daten beantwortet werden sollen.

Eine nachvollziehbare semantische Modellierung kann außerdem zu konsistenten Datenstrukturen beitragen und insbesondere **Interoperabilität und Nachnutzbarkeit im Sinne der FAIR-Prinzipien** unterstützen.

---

## Ausblick

Mit der Reflexion des Pathbuilders schließt sich der Modellierungsprozess dieses Lernangebots.

Ausgehend von einer Sammlung und konkreten Forschungsfragen wurden relevante Entitäten und Beziehungen identifiziert, mit CIDOC CRM semantisch modelliert, als Datenmodell visualisiert und in eine für WissKI nutzbare Pathbuilder-Struktur überführt.

Der entstandene Pathbuilder ist damit nicht nur ein technisches Ergebnis. In ihm spiegeln sich Entscheidungen darüber wider, **wie Forschungsdaten verstanden, strukturiert, miteinander verknüpft und für zukünftige Forschungsfragen nutzbar gemacht werden**.

**Forschungsfrage → Modellierungsentscheidung → semantisches Datenmodell → Pathbuilder → Wissensbasis**

---

## Bibliographie

 CIDOC CRM Special Interest Group. *CIDOC Conceptual Reference Model (CRM).* https://www.cidoc-crm.org/

GO FAIR. *FAIR Principles.* https://www.go-fair.org/fair-principles/

WissKI. *Wissenschaftliche KommunikationsInfrastruktur.* https://wiss-ki.eu/

Wilkinson, Mark D. et al. (2016). *The FAIR Guiding Principles for scientific data management and stewardship.* Scientific Data 3, 160018. https://doi.org/10.1038/sdata.2016.18

