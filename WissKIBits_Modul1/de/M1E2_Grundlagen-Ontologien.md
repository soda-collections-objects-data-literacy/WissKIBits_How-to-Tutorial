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

module: Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären

unit: Grundlage von Ontologien

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->


# WissKI Bits: Ontologiebasierte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 1: **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären**

Einheit (E2): **Grundlage von Ontologien**  

**Dauer:**  ~ 10 Min.

**Lernziele:**

Teilnehmende können...

- Begriff Ontologie benennen. (LZ-ID SODa\_03\_007\_0826)
- Begriff Ontologie erläutern. (LZ-ID 03\_007\_0775)
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

## Grundlagen von Ontologien

Die **konzeptuelle Wissensmodellierung** (M1E1) bildet eine wichtige Grundlage für die strukturierte Beschreibung von Wissen innerhalb einer Domäne. Dabei werden in einem fachlichen Zusammenhang zentrale Konzepte und Begriffe, Eigenschaften und Beziehungen identifiziert. **Ontologien** helfen dabei, diese konzeptuellen Strukturen formal auszudrücken (Rehbein, 2017, S. 164) und in einer maschinenlesbaren Form darzustellen.

In dieser Einheit wird erläutert, **warum Ontologien genutzt werden und welchen Nutzen sie für die Sammlungsdokumentation haben.** Dazu werden die wichtigsten **Begriffe** und **Bausteine von Ontologien** definiert und erläutert sowie ihre **Funktion** für die strukturierte und semantische Beschreibung von Sammlungsinformationen erklärt.

> **Vom konzeptuellen Wissen zur Ontologie**
>
> Die konzeptuelle Wissensmodellierung identifiziert und ordnet die relevanten Konzepte, Ereignisse und Beziehungen innerhalb einer Domäne.
>
> Eine Ontologie geht einen Schritt weiter: Sie stellt diese konzeptuelle Struktur formal und maschinenlesbar dar.

---

## Warum verwenden wir Ontologien?

Bei der Modellierung von Forschungsdaten aus den Geistes- und Kulturwissenschaften geht es darum, relevantes Wissen einer Domäne standardisiert zu beschreiben und zu dokumentieren, verfügbar zu machen und zu teilen sowie technisch und inhaltlich langfristig nutzbar zu halten.

> **Warum Ontologien?**
>
> Ontologien helfen dabei:
>
> - **die Bedeutung von Daten explizit zu machen und ihre Semantik formal zu erfassen,**
> - **semantische Beziehungen formal auszudrücken und zu beschreiben,**
> - **Wissen maschinenlesbar zu machen,**
> - **Interoperabilität und Nachnutzung zwischen Einrichtungen und Systemen zu unterstützen,**
> - **Daten mit dem Linked-Open-Data-Ökosystem (LOD) zu verbinden.**
>
> **Kurz gesagt:** Ontologien machen Domänenwissen explizit, strukturiert, teilbar und maschinell verarbeitbar.

---

## Begriffsdefinitionen und Grundbegriffe von Ontologien

> **Was ist eine Ontologie?**
>
> Eine **Ontologie** definiert formal Konzepte, Beziehungen und relevante Modellierungsbedingungen innerhalb einer Domäne.
>
> **Klassen (Classes)** beschreiben Arten von Dingen.
>
> **Eigenschaften (Properties)** beschreiben Beziehungen oder Merkmale.
>
> **Instanzen (Instances)** repräsentieren einzelne Dinge, die mithilfe der Ontologie beschrieben werden.
>
> **Bedingungen (Constraints)** legen zusätzliche Bedingungen für die Interpretation oder Verwendung des Modells fest.
>
> **Merksatz:** Ontologien stellen eine gemeinsame, formal definierte Struktur zur Repräsentation und Interpretation von Domänenwissen bereit.

---

Eine Ontologie ist eine **formale Beschreibung eines Ausschnitts der Welt** bzw. eine **„formale, schematische Abbildung[] eines Wissensbereichs, bestehend aus einem Vokabular und Regeln zu seiner Zusammensetzung.“** (Weller, 2013, S. 207)

Die bekannteste Definition beschreibt eine Ontologie als eine explizite, formale Spezifikation einer Konzeptualisierung, d. h. sie beschreibt strukturierend, welche Konzepte in einem bestimmten Fachgebiet oder Gegenstandsbereich relevant sind und welche Beziehungen zwischen ihnen bestehen (Gruber, 1993, S. 200).

**Eine Ontologie legt fest, ...**

- welche **Konzepte** und **Ereignisse** in einem Fach- oder Anwendungsbereich (Domäne) relevant sind,
- wie diese Konzepte miteinander **in Beziehung** stehen,
- und welche **Regeln** gelten, damit **Aussagen** über sie sinnvoll und widerspruchsfrei modelliert werden können.

---
### Aspekte von Ontologien

> **Ontologien bestehen typischerweise aus folgenden Bausteinen:**
>
> **Klassen (Classes)** → Welche Arten von Dingen gibt es? Beispiele: Spiel, Person, Organisation. Klassen repräsentieren allgemeine Konzepte innerhalb einer Domäne und sind typischerweise hierarchisch strukturiert (Weller, 2013, S. 208).
>
> **Instanzen (Instances)** → Von welchen konkreten Dingen sprechen wir? Beispiel: *The Legend of Zelda: A Link to the Past*. Instanzen repräsentieren einzelne Vertreter von Klassen (Weller, 2013, S. 208).
>
> **Eigenschaften (Properties)** → Wie werden Dinge beschrieben oder miteinander in Beziehung gesetzt? Beispiel: Ein Spiel hat einen Titel. Eigenschaften beschreiben Merkmale oder drücken semantische Beziehungen zwischen Elementen einer Domäne aus (Weller, 2013, S. 208).
>
> **Bedingungen (Constraints)** → Welche Regeln gelten für die Verwendung von Klassen und Eigenschaften? Bedingungen helfen dabei, die logische Konsistenz der Ontologie sicherzustellen, beispielsweise indem festgelegt wird, welche Klassen durch eine bestimmte Eigenschaft miteinander verbunden werden dürfen (Rehbein, 2017, S. 164).

---

## Nutzen von Ontologien

> **Was ermöglichen Ontologien?**
>
> Ontologien bieten einen gemeinsamen Rahmen, um eine Domäne strukturiert und konsistent zu beschreiben.
>
> - heterogene Daten integrieren und miteinander in Beziehung setzen,
> - Wissen über Sammlungen, Projekte und Systeme hinweg austauschen und nachnutzen,
> - semantische Informationen maschinell verarbeiten und
> - logische Schlussfolgerungen auf Grundlage formal definierter Beziehungen unterstützen.
>
> Ontologien bilden damit eine Brücke zwischen Domänenwissen und maschinell verarbeitbaren Forschungsdaten.
>
> Diese Vorteile hängen davon ab, wie eine Ontologie entwickelt, dokumentiert und verwendet wird. Allein die Verwendung einer Ontologie macht Daten nicht automatisch konsistent oder interoperabel.

---

Ontologien sind eine Form der Wissensrepräsentation mit einem hohen Abstraktionsniveau. Sie haben **„einen an mathematische Logik angelehnten (...) Formalisierungsgrad, durch den Informationen in ihrem Bedeutungskontext präzise erfasst und maschinell“** (Herv. d. A.) verarbeitet werden können. Damit sind Ontologien vor allem für die Integration heterogener Datenquellen, den Austausch und die Wiederverwendung von Wissenselementen sowie die Ermöglichung logischer Schlussfolgerungen relevant (Rehbein, 2017, S. 162).

Der besondere Nutzen von Ontologien liegt darin, dass sie Konzepte und Begriffe, Eigenschaften und Beziehungen und ihre Bedeutung aus einem Wissensbereich **formal und eindeutig beschreibbar machen**. Damit können Daten auch über einzelne Sammlungen, Projekte oder Systeme hinweg miteinander in Beziehung gesetzt und gemeinsam ausgewertet werden. Die formale Beschreibung ermöglicht zudem eine maschinelle Verarbeitung der Daten.

So schaffen Ontologien eine Grundlage dafür, komplexe Forschungs- und Sammlungsdaten nicht nur zu dokumentieren, sondern das darin enthaltene fachliche Wissen strukturiert abzubilden und für weitere Forschung nutzbar zu machen.

---

## Ausblick

Sie haben gelernt, wie Ontologien mithilfe von Klassen und Eigenschaften Konzepte und Beziehungen strukturiert beschreiben.

Ontologien bieten die Grundlage, Wissen über Sammlungsobjekte strukturiert und semantisch zu modellieren. Doch wie lässt sich dies konkret auf Informationen zum kulturellen Erbe anwenden?

> **Wie geht es weiter?**
>
> In Einheit 3 lernen Sie **CIDOC CRM** als Referenzontologie für Kulturerbeinformationen kennen. Sie erfahren, wie dessen Klassen, Eigenschaften und Scope Notes dabei helfen können, die in Ihrer Modellskizze identifizierten Konzepte zu untersuchen und weiter zu präzisieren.

---

## Bibliografie

(Gruber, 1993) Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

(Rehbein, 2017) Rehbein, M. (2017). Ontologien. In: F. Jannidis, H. Kohle, & M. Rehbein (Hrsg.), *Digital Humanities* (S. 162-176). J.B. Metzler, Stuttgart. https://doi.org/10.1007/978-3-476-05446-3_11.

(Stuckenschmidt, 2011) im Text referenziert? Fehlt nun schon zum zweiten Mal in den Einheiten obwohl in Zotero

(Weller, 2013) Weller, K. (2013). B 6 Ontologien. In: R. Kuhlen, W. Semar, & D. Strauch (Hrsg.), *Grundlagen der praktischen Information und Dokumentationen* (S. 207-218). De Gruyter Saur.

---























