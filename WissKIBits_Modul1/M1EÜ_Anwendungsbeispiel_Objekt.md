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

Übungseinheit (M1EÜ): **Anwendungsbeispiel: Objektsammlungen**  

**Dauer:** ~ 25 Min.

**Lernziele:**

Teilnehmende können...

- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0844)
- Datentyp-Eigenschaften des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0808) 


---

## Ziel und Szenario

Dies ist eine Praxiseinheit. Ausgehend von einem Beispielobjekt aus der Domäne **Computerspiele** wird eine erste konzeptionelle Modellskizze entwickelt.

Am Beispiel von **„The Legend of Zelda: A Link to the Past“** wird untersucht, welche Informationen für die Beschreibung eines Sammlungsobjekts relevant sind, in dem 

- zentrale **Konzepte und Ereignisse** identifiziert
- und die **Beziehungen**, die zwischen ihnen bestehen, formuliert werden.

Anschließend werden ausgewählte Konzepte probeweise Klassen des **CIDOC CRM** zugeordnet. Dabei geht es nicht darum, bereits ein vollständiges oder formal korrektes CIDOC-CRM-Modell zu erstellen. Vielmehr soll sichtbar werden, dass die Überführung eines Domänenwissens in ein Referenzmodell **Modellierungsentscheidungen** erfordert.

Am Ende können die Teilnehmenden:

* zentrale **Konzepte** und **Ereignisse** einer Beispieldomäne identifizieren,
* **semantische Beziehungen** zwischen ihnen formulieren,
* ausgewählte Konzepte möglichen **CIDOC-CRM-Klassen (Entities)** zuordnen,
* die Zuordnungen als Modellierungsentscheidungen beschreiben,
* ein **konzeptuelles Modell** entwerfen, die als Ausgangspunkt für die weitere Formalisierung dient.

Die Modellskizze wird in den folgenden Modulen schrittweise weiterentwickelt und für die Arbeit mit **Protégé** und **WissKI** formalisiert.

---

## Ausgangspunkt: Beispielobjekt „Zelda“

Als Ausgangspunkt dient das Computerspiel **„The Legend of Zelda: A Link to the Past“**. 

An diesem Beispiel wird untersucht, welche **Konzepte, Ereignisse und Beziehungen** für die Beschreibung eines Sammlungsobjekts und seines Kontextes relevant sein können.

**Ziel ist nicht**, ein vollständiges Datenmodell für Computerspiele zu entwickeln. Vielmehr entsteht eine **erste Modellskizze**, die

- zentrale Konzepte und Ereignisse verständlich für Menschen unterscheidet,
- ihre Beziehungen sichtbar macht und
- als Grundlage für die anschließende Zuordnung zu **CIDOC CRM** dient.

## Warum Computerspiele?

Computerspiele eignen sich als Beispieldomäne, weil an ihnen unterschiedliche Aspekte der Modellierung anschaulich werden.

Die Domäne ist besonders geeignet, weil sie...

- sowohl **physische** als auch **digitale** Objekte umfasst,
- gut nachvollziehbare **Produktions- und Veröffentlichungskontexte** besitzt,
- typische **Ereignisse** enthält (z.B. Release, Portierung, Neuauflage),
- **Versionen/Editionen** und **Serienzugehörigkeiten** abbildbar macht,
- klare Identifikatoren und Benennungen verwendet (Titelvarianten, Produktcodes).

Damit bietet die Domäne einen anschaulichen Ausgangspunkt, um unterschiedliche Perspektiven auf ein Objekt zu erkennen und daraus erste **Modellierungsentscheidungen** abzuleiten.

---

## Fokus dieser Modellierungsübung

Für die Modellskizze betrachten wir ausgewählte Informationen zum Beispielobjekt. Dabei konzentrieren wir uns auf drei Bereiche:

- **Spieltitel** 
- **Spielmerkmale** (z.B. Genre, wie Action-Adventure, RPG oder Plattform, wie Nintendo 64, PlayStation, PC)
- **narrative Elemente** (z.B. Beschreibung, Perspektive, wie First-Person, Third-Person oder Figuren wie Zelda)

Diese Bereiche dienen als Ausgangspunkt, um unterschiedliche Arten von **Konzepten und Ereignissen** zu erkennen und ihre **Beziehungen** zu formulieren.

Beispielsweise können folgende Fragen gestellt werden:

* Welchen **Titel** hat das Spiel?
* Welchem **Genre** oder welcher **Plattform** wird es zugeordnet?
* Welche **Personen oder Organisationen** waren beteiligt?
* Welche **Ereignisse** sind für das Spiel relevant?
* An welchen **Orten** und zu welchen **Zeiten** fanden diese Ereignisse statt?

---

## Übung – Modellskizze und erste Orientierung mit CIDOC CRM

**Arbeitsform:** Breakout-Räume / Einzelarbeit oder Teams (2–4 Personen)  
**Material:** Papier & Stift (oder digitales Whiteboard)  
**Zeit:** 20 Minuten

### Aufgabe: Eine Mini-Mindmap als Modellskizze entwerfen

Erstellt für das Beispielobjekt „The Legend of Zelda: A Link to the Past“ eine einfache Mindmap. 

Ziel ist es, zentrale Elemente der Domäne und ihre Zusammenhänge und die Struktur der Domäne sichtbar zu machen.

Geht dabei in zwei Schritten vor:

-**Schritt 1:** Identifiziert 3–5 zentrale Konzepte und Ereignisse aus dem Beispiel, z.B. ein Objekt, eine Person oder Organisation, einen Ort, eine Zeitangabe oder ein Ereignis. 
Nicht alle Kategorien müssen vorkommen.

-**Schritt 2:** Verbindet die identifizierten Elemente durch aussagekräftige Beziehungen, z.B. „hat“, „wurde hergestellt durch“, „wurde veröffentlicht von“. Formuliert die Beziehungen so, dass sich daraus eine verständliche Aussage ergibt.

**Beispiel:**

> Spiel → hat Titel → Titel

> Nintendo → war beteiligt an → Entwicklung

> Entwicklung → schuf → Spiel

**Hinweis:**

Weniger ist mehr. Konzentriert euch zunächst auf wenige Elemente und Beziehungen, die für das Verständnis des Beispielobjekts besonders relevant sind.

**Leitfragen können sein**

| Schritt | Leitfrage | Ergebnis |
|-------|-----------|----------|
| 1 | Welche zentralen Konzepte und Ereignisse gibt es? | Knoten der Modellskizze |
| 2 | Wie hängen die Dinge zusammen? | gerichtete Beziehungen zwischen den Knoten |
| 3 | Lassen sich die Verbindungen als verständliche Aussagen lesen? | überprüfbare Aussagen über das Objekt|

---

### Aufgabe: Erste Zuordnung zu CIDOC CRM

Schaut euch eure Modellskizze noch einmal an und wählt **zwei Begriffe** daraus aus, z. B. Spiel, Person, Organisation, Titel oder Genre.

Sucht für jeden Begriff nach einer **CIDOC CRM Klasse**, die zu Bedeutung der Begriffe passen könnte.

Begründet kurz eure Klassenauswahl.

**Hinweis:**

> Es geht noch nicht darum, eine vollständige oder endgültige CIDOC-CRM-Modellierung zu erstellen.
> Entscheidend ist zunächst die Frage: Was meinen wir mit unserem Begriff – und welche Klasse beschreibt diese Bedeutung möglichst passend?

**Mini-Demo: CIDOC CRM als Baukasten** 

Für den Einstieg können beispielsweise folgende Klassen hilfreich sein:

| CIDOC CRM Klasse | Bedeutung im Beispiel |
|------------------|-----------------------|
| **E73 Information Object** | Spiel als identifizierbarer Informationsinhalt |
| **E22 Human-Made Object** | physische Kopie (Cartridge, Disc, Box…) |
| **E21 Person** | Beteiligte Person / Mitwirkende (Designer:in, Musikeer:in) |
| **E74 Group** | Organisation oder Gruppe (Entwicklerstudio, Publisher, Team) |
| **E12 Production** | Herstellung / (ggf. Veröffentlichung als Ereignis) |
| **E42 Identifier** | Identifikatoren (Inventarnummern, Produktcodes …) |
| **E35 Title** | Titel des Objektes als eigene Entität |
| **E42 Appelation** | Benennung, durch die etwas identifiziert oder bezeichnet wird |
| **E55 Type** | kontrollierte Merkmale (z. B. Genre, Plattform) |

Der [CIDOC CRM Navigator Version 7.1.3 ](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html) ermöglicht die interaktive Erkundung von 81 Klassen und 160 Eigenschaften, inklusive Übersetzungen. 

**Beispiel: Von der Benennung zur Appellation**

In unserer ersten Modellskizze können wir zunächst einfach formulieren:

> Spiel → hat eine Benennung → „The Legend of Zelda: A Link to the Past“

CIDOC CRM ermöglicht es, eine solche Benennung genauer zu modellieren. E41 Appellation bezeichnet eine Benennung, mit der eine Instanz einer CRM-Klasse identifiziert oder bezeichnet werden kann.

Für Titel gibt es mit E35 Title eine speziellere Klasse: E35 Title ist eine Unterklasse von E41 Appellation. Ein Titel ist damit eine besondere Form einer Appellation.

Vereinfacht können wir unterscheiden:

E41 Appellation
→ allgemeine Benennung

E35 Title
→ besondere Form einer Appellation: ein Titel

E42 Identifier
→ besondere Form einer Appellation: ein Identifikator

Damit wird deutlich: Begriffe wie Benennung, Titel und Identifikator sind in CIDOC CRM nicht dasselbe, stehen aber in einem gemeinsamen konzeptionellen Zusammenhang.

Merksatz: 

> Bevor wir einen Wert einfach als Text erfassen, fragen wir: Hat diese Benennung in unserem Modell selbst eine Bedeutung, die wir näher beschreiben oder unterscheiden möchten?

Die genaue Modellierung von Appellationen, ihren Zeicheninhalten und Datentyp-Eigenschaften wird in einer späteren Einheit weiter vertieft.

---

## Vom Domänenmodell zur CIDOC-CRM-Modellierung

Die in der Übung entstandene Modellskizze beschreibt zunächst die Konzepte, Ereignisse und Beziehungen der Beispieldomäne. Im nächsten Schritt können diese Elemente mit Klassen und Eigenschaften des CIDOC CRM weiter formalisiert werden.

Die folgende Abbildung zeigt beispielhaft, wie aus einer solchen Modellskizze ein stärker formalisiertes semantisches Modell entstehen kann:

![Konzept-Mindmap](../assets/Mindmap.png)

Dabei werden aus den zunächst frei formulierten Elementen und Beziehungen schrittweise CIDOC-CRM-Klassen und -Eigenschaften. Die Abbildung ist daher nicht als einzig mögliche Lösung zu verstehen, sondern als Modellierungsvorschlag, der überprüft und weiterentwickelt werden kann.

**Hinweis:** 

> Semantische Modellierung bedeutet nicht nur, passende Klassen zu finden.
> Modellierungsentscheidungen machen explizit, welche Bedeutung wir einem Begriff geben und welche Zusammenhänge unsere Daten ausdrücken sollen.

---

## Ausblick

In der Praxiseinheit wurde zunächst eine **erste Modellskizze für die Domäne Computerspiele** entwickelt. Anschließend wurde dese Modellierung auf die entsprechenden **Klassen und Eigenschaften des CIDOC CRM** abgebildet und insbesondere die Besonderheiten der **Klasse E41 Appellation** erläutert. Als Ergebnis liegt ein **formalisiertes semantisches Modell der Domäne Computerspiele auf Grundlage des CIDOC CRM** vor.

Mit dieser Praxiseinheit endet **Modul 1**.

In **Modul 2** wird das entwickelte Modell mit **Protégé** als maschinenlesbare **OWL-Ontologie** umgesetzt und für die spätere Implementierung in **WissKI** vorbereitet. Auf diese Weise werden die Grundlagen für die praktische Arbeit mit Protégé und die Überführung des semantischen Modells in eine technische Implementierung geschaffen.

In **Modul 3** wird schließlich gezeigt, wie die zuvor entwickelte Modellierung in WissKI umgesetzt wird. Im Mittelpunkt steht dabei die Übertragung des Modells in die **Pfadstruktur des WissKI Pathbuilders**.

---

## evtl. Hausaufgabe für Modul 2

## Bibliografie

[SIG2024cidoc] CIDOC CRM Special Interest Group. (2024). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. https://cidoc-crm.org/Version/version-7.1.3

[SIG2024cidocb] CIDOC CRM Special Interest Group. (2024). Classes & Properties Declarations of CIDOC-CRM version: 7.1.3. https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html


