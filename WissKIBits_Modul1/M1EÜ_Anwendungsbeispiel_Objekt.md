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

- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. 	(LZ-ID SODa\_03\_007\_0844)
-  Datentyp-Eigenschaften des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0808) 


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

## Übung – Modellskizze 

**Arbeitsform:** Breakout-Räume / Einzelarbeit oder Teams (2–4 Personen)  
**Material:** Papier & Stift (oder digitales Whiteboard)  
**Zeit:** **xxx Minuten**

**Aufgabe: Eine Mini-Mindmap als Modellskizze entwerfen**

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

## Orientierung mit CIDOC CRM 

**Aufgabe: CIDOC CRM sichten**

CIDOC CRM sichten und für zwei Konzepte jeweils mindestens eine passende Klasse (Entity) heraussuchen.

1. **2 Begriffe aus eurer Skizze** (z.B. Spiel, Publisher, Release)
2. mögliche **CIDOC CRM-Klasse** grob zuordnen.

Für den Einstieg eignen sich zentrale CIDOC CRM Klassen als „Baukasten“:

**Mini-Demo: CIDOC CRM in Kürze** 

| CIDOC CRM Klasse | Bedeutung im Beispiel |
|------------------|-----------------------|
| **E28 Conceptual Object** | Spiel als Konzept / Inhalt |
| **E22 Human-Made Object** | physische Kopie (Cartridge, Disc, Box …) |
| **E21 Person** | Mitwirkende (z. B. Designer:in) |
| **E74 Group** | Studio / Publisher / Team |
| **E12 Production** | Herstellung / (ggf. Veröffentlichung als Ereignis) |
| **E42 Identifier** | Identifikatoren (Inventarnummern, Produktcodes …) |
| **E35 Title** | Titel als eigene Entität |
| **E55 Type** | kontrollierte Merkmale (z. B. Genre, Plattform) |

Quelle: [CIDCO CRM-Spezifikation (v7.1.3)](https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf)  

Beispiel Titel mit Appelation als Hinweis formulieren....



---

## Ergebnis: Semantisches Domänenmodell mit CIDOC CRM

![Konzept-Mindmap](../assets/Mindmap.png)

Die Mindmap dient als Übergang zu den nächsten Schritten im Tutorial:

- das Modell wird als **Diagramm** klarer strukturiert, (Hausaufgabe???)
  
- anschließend wird in Modul 2 das Modell in **Protégé** überprüft und formaler gefasst,
- und in Modul 3 als **Pfadstruktur im WissKI Pathbuilder** umgesetzt.
  
---

### Begründung der Modellierungsentscheidungen (ggf. vollständig in Modul 3 nachlagern!!!) 

| Pfad | Bedeutung | Warum so modelliert? |
|------|-----------|---------------------|
| **E73 → P102 has title → E35 Title** | Das Spiel hat einen Titel | Titel ist ein **eigenständiges Konzept**, nicht nur Text; ermöglicht Mehrsprachigkeit & Varianten |
| **E73 → P129 is about → E89 Propositional Object** | Das Spiel hat Eigenschaften | E89 erlaubt es, Merkmalsbündel strukturiert darzustellen und auf Quellen zurückzuführen |
| **E57 Type (Plattform) → P1 is identified by → E41 Appellation** | Plattform-Bezeichnung | Plattformen sind **kontrollierte Begriffe**, keine Freitexte |
| **E55 Type (Genre) → P1 is identified by → E41 Appellation** | Genre-Bezeichnung | Genre ist ein **Klassifikationsbegriff**; E55 unterstützt kontrollierte Vokabulare |
| **E99 Type (Edition) → P1 is identified by → E41 Appellation** | Edition / Version | Editionen sind **Domänenspezifika** → daher modelliert als Typen |

---

## Rolle von E41 Appellation und Datentyp-Eigenschaften in CIDOC CRM (ggf. in Hinweis zur Übung integrieren??))

CIDOC CRM ist primär auf **Beziehungen zwischen Klassen (Entities)** ausgelegt. Deshalb werden zentrale Informationen (z.B. Titel, Namen, Identifikatoren oder Rollen) häufig nicht nur als Text erfasst, sondern als eigene modellierbare Klassen (Entities). So lassen sich Varianten, Mehrsprachigkeit, Quellenangaben und kontrollierte Vokabulare konsistent abbilden und eindeutig referenzieren.

Zentral hierfür ist **E41 Appellation**:

| Konzept                 | Erklärung                                                                                                                                                                                            |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **E41 Appellation**     | Namen, Benennungen und Bezeichnungen sind **eigenständige Klassen (Entities)**, nicht nur Textstrings. Das ermöglicht z.B. **Mehrsprachigkeit**, **Titelvarianten**, **persistente IDs** und **Quellenangaben**. |
| **P1 is identified by** | Verknüpft eine Klasse (Entity) (z.B. ein Spiel, eine Person, eine Plattform) mit seiner **Benennung** und unterstützt damit **Klarheit und Interoperabilität**.                                              |

Gleichzeitig nutzt CIDOC CRM **Datentyp-Eigenschaften** (sog. Literale wie Zahlen oder Zeichenketten) nur sparsam und vor allem dann, wenn der Wert nicht als eigenständige Klasse (Entity) modelliert werden muss.

**Typische Datentyp-Eigenschaften sind...**

- P190 has symbolic content (z.B. Zeichenkette / Textinhalt)
- P90 has value (z. B. numerischer Wert)

**Grundprinzip**

- CIDOC CRM bevorzugt semantische Identifikatoren und Beziehungen statt Freitextfelder.
- Literale werden genutzt, wenn sie als reine Darstellung sinnvoll sind (z.B. ein Zahlenwert), während zentrale semantische Informationen (Titel, Rollen, Identifikatoren usw.) als Klassen (Entity) modelliert und idealerweise mit kontrollierten Vokabularen verknüpft werden.

**Hinweis:** Der gezielte Umgang mit Datentyp-Eigenschaften, kontrollierten Vokabularen und Interoperabilität wird in späteren Einheiten weiter vertieft.

---

## Hausaufgabe als Vorbereitung für Modul 3

-

---

## Bibliografie

[SIG2024cidoc] CIDOC CRM Special Interest Group. (2024). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. https://cidoc-crm.org/Version/version-7.1.3

[SIG2024cidocb] CIDOC CRM Special Interest Group. (2024). Classes & Properties Declarations of CIDOC-CRM version: 7.1.3. https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html

---

