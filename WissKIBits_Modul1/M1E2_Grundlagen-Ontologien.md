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

Einheit 2: **Grundlage von Ontologien**  

**Dauer:** 10 Min.

**Lernziele:**

Teilnehmende können...

- den Begriff Ontologie benennen. (LZ-ID SODa\_03\_007\_0826)
- den Begriff Ontologie erläutern. (LZ-ID 03\_007\_0775)
- den Begriff Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0827)
- den Begriff Domänenontologie erläutern. (LZ-ID SODa\_03\_007\_0828)
- Aspekte von Ontologien benennen. (LZ-ID 03\_007\_0776)
- Begriff Klassen (Classes/Concepts) benennen. (LZ-ID SODa\_03\_007\_0829)
- Begriff Klassen (Classes/Concepts) erläutern. (LZ-ID SODa\_03\_007\_0830)
- Begriff Instanzen (Instances) benennen. (LZ-ID SODa\_03\_007\_0833)
- Begriff Instanzen (Instances) erläutern. (LZ-ID SODa\_03\_007\_0834)
- Begriff Eigenschaften (Properties) benennen. (LZ-ID SODa\_03\_007\_0831)
- Begriff Eigenschaften (Properties) erläutern. (LZ-ID SODa\_03\_007\_0832)
- Begriff Modellannahmen (Constraints) benennen. (LZ-ID SODa\_03\_007\_0835)
- Begriff Modellannahmen (Constraints) erläutern. (LZ-ID SODa\_03\_007\_0836)

---

## Grundlage von Ontologien

Die **konzeptuelle Wissensmodellierung** (M1E1) bildet eine wichtige Grundlage für die strukturierte Beschreibung von Wissen innerhalb einer Domäne. Dabei werden in einem fachlichen Zusammenhang zentrale Konzepte und Begriffe, Eigenschaften und Beziehungen identifiziert. **Ontologien** helfen dabei, diese konzeptuellen Strukturen in einer formal definierten, maschinenlesbaren Form darzustellen.

In dieser Einheit wird erläutert, **warum Ontologien genutzt werden und welchen Nutzen sie für die Sammlungsdokumentation haben.** Dazu werden die wichtigsten **Begriffe** und **Bausteine von Ontologien** definiert und erläutert und ihe **Funktion** für die strukturierte und semantische Beschreibung von Sammlungsinformationen erläutert.

---

## Warum verwenden wir Ontologien?

Bei der Modellierung von Forschungsdaten aus den Geistes- und Kulturwissenschaften geht es nicht nur darum, Daten zu beschreiben. 

Es geht darum relevantes Wissen einer Domäne standardisiert zu dokumentieren und zu beschreiben, verfügbar zu machen und zu teilen und technisch und inhaltlich langfristig nutzbar zu halten.

Ontologien helfen dabei:

- **Semantik der Daten zu erfassen**
- **Semantische Beziehungen auszudrücken**
- **Kontext und Provenienz zu erhalten**
- **Wissen maschinenlesbar zu machen**
- **Interoperabilität zwischen Einrichtungen und Systemen sicherzustellen**
- **Daten mit dem Linked Open Data-Ökosystem zu verbinden**

---

## Begriffsdefinitionen

### Grundbegriffe Ontologien

**Ontologie**

Eine Ontologie ist eine **formale Beschreibung eines Ausschnitts der Welt** bzw. eine **"formale, schematische Abbildung[] eines Wissensbereichs, bestehend aus einem Vokabular und Regeln zu seiner Zusammensetzung."** (Weller2013ontologies, S. 207)

Die bekannteste Definition beschreibt eine Ontologie als eine explizite, formale Spezifikation einer Konzeptualisierung, d.h. sie beschreibt strukturierend, welche Konzepte in einem bestimmten spezifischen Fachgebiet oder Gegenstandsbereich relevant sind und welche Beziehungen zwischen ihnen bestehen. (Gruber, 1993, S. 200)

**Domänenontologie**

Eine **Domänenontologie** ist eine projekt- oder anwendungsspezifische Umsetzung einer Ontologie, die die Konzepte, Ereignisse und Beziehungen innerhalb eines konkreten Fach- oder Anwendungsbereichs (Domäne) beschreibt.

**Eine Ontologie legt fest,...**

- welche **Konzepte** und **Ereignisse** in einem Fach- oder Anwendungsbereichs (Domäne) relevant sind,
- wie diese Konzepte miteinander **in Beziehung** stehen,
- und welche **Regeln** gelten, damit **Aussagen** über sie sinnvoll und widerspruchsfrei modelliert werden können.

**Dazu stellt eine Ontologie folgende Bausteine bereit (Aspekte von Ontologien):**

- **Klassen (Classes/Concpets):** formale Repräsentation von Konzepten und Ereignissen
- **Eigenschaften (Properties):** formale Repräsentation von Merkmalen oder Beziehungen
- **Instanzen (Instances):** konkrete Individuen von Klassen
- **Bedingungen (Constraints):** Regeln, um die logische Konsistenz der Ontologie sicherzustellen

---

### Aspekte von Ontologien

Ontologien bestehen typischerweise aus folgenden Bausteinen:

**Klassen (Classes/Concepts)**  

- "Klassen repräsentieren Allgemeinbegriffe, also Konzepte eines Interessensgebiets, die reale Objekte anhand von gemeinsamen Eigenschaften bündeln sollen. Sie sind meist grundlegend hierarchisch strukturiert." (Weller2013ontologies, S. 208)
- Beispiel: Spiel, Person, Organisation

**Instanzen (Instances)**    

- "Instanzen repräsentieren Individualbegriffe, also konkrete Vertreter der einzelnen Klassen." (Weller2013ontologies, S. 208)
- Beispiel: Das Spiel "The Legend of Zelda: A Link to the Past"

**Eigenschaften (Properties)**  

- Klassen und Instanzen können in ihrer Bedeutung weiter spezifiziert werden.

- Eigenschaften (Properties) modellieren Klasseneigenschaften über semantische Relationen. Dabei gibt es zwei grundlegende Möglichkeiten in der Umsetzung:

1) Eine Eigenschaft (Property) stellt eine Beziehung her zwischen zwei Klassen
2) Eine Eigenschaft (Property) beschreibt eine einzelne Klasse, ohne sie mit anderen Klassen zu verbinden. (Weller2013ontologies, S. 208)

- Beispiel: Das Spiel hat den Titel "The Legend of Zelda: A Link to the Past", 

**Bedingungen (Constraints)**  

- "Für Attribute und Relationen kann eine Ontologie **Bedingungen** *(constraints)* festlegen, die ihren Gebrauch näher definieren und sicherstellen sollen, dass die Ontologie in sich logisch konsistent ist." (Rehbein2017ontologies, S. 164)

- Beispiel: Welche Beziehungen beschreiben zulässig das Objekt? (besseres Beispiel finden)

---

## Nutzen von Ontologien und weiterführende Definitionen

Ontologien helfen damit, fachliches Domänenwissen mit ihrer spezifischen Domänenlogik so zu dokumentieren, dass es maschinenlesbar, vergleichbar und nachnutzbar wird. 

Auf diese Weise ermöglichen Ontologien, Aussagen über Ressourcen aus Sammlungsbeständen formal abzubilden. (World Wide Web Consortium, 2012)

Ontologien unterstützen damit die systematische und konsistente Repräsentation von Domänenwissen, sodass Informationen maschinenlesbar und für die Nachnutzung in unterschiedlichen Systemen anschlussfähig werden. (Noy, 2001)

---

## Ausblick

Ontologien bieten die Grundlage, Wissen über Sammlungsobjekte strukturiert und semantisch zu modellieren. Doch wie lässt sich dies konkret auf Informationen zum kulturellen Erbe anwenden?

In der nächsten Einheit lernen wir mit dem CIDOC Conceptual Reference Model (CIDOC CRM) eine Ontologie kennen, die speziell als Referenz für die Modellierung von Kulturerbeinformationen entwickelt wurde.

---

## Bibliographie

[W3C2001owl] World Wide Web Consortium. (2012, December 11). OWL 2 Web Ontology Language Primer (Second Edition). W3C Recommendation. https://www.w3.org/TR/owl2-primer 

[Noy2001ontology] Noy, N. F., & McGuinness, D. L. (2001). Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory.

[Gruber1993knowledge] Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

[Uschold1995method]Uschold, M., & King, M. (1995). Towards a Methodology for Building Ontologies.

[Rehbein2017ontologies] Rehbein, M. (2017). Ontologien. In: F. Jannidis, H. Kohle, & M. Rehbein (Hrsg.), *Digital Humanities* (S. 162-176). J.B. Metzler, Stuttgart. https://doi.org/10.1007/978-3-476-05446-3_11.

[Stuckenschmidt2011ontology] Stuckenschmidt, H. (2011). *Ontologien. Konzepte, Technologien und Anwendungen*. Springer.

[Weller2013ontologies] Weller, K. (2013). B 6 Ontologien. In: R. Kuhlen, W. Semar, & D. Strauch (Hrsg.), *Grundlagen der praktischen Information und Dokumentationen* (S. 207-218). De Gruyter Saur.

---























