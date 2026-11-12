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

unit: Methoden und Workflows semantischer Modellierung

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontologiebasierte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 2 (M2): **Modellieren mit CIDOC CRM – verstehen und anwenden**

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

## Methoden und Workflows semantischer Modellierung

Die Entwicklung einer Domänenontologie folgt typischerweise einem methodischen, mehrstufigen und iterativen Vorgehen. Sie umfasst mehr als die bloße Übertragung domänenspezifischer Begriffe in Ontologieklassen.

Dazu zählen unter anderem die **Erhebung zentraler Begriffe und Definitionen (sogenanntes „Ontology Capture“)** (Uschold & King, 1995, S. 3), die **Strukturierung von Konzepten in Klassen und Eigenschaften beziehungsweise Relationen** sowie die **kontinuierliche Prüfung und Überarbeitung des Domänenmodells im Hinblick auf Konsistenz und Nutzbarkeit** (Gruber, 1993).

In Modul 1 **(M1) Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären** haben Sie eine konzeptuelle Modellskizze entwickelt und mögliche Zuordnungen zu CIDOC CRM untersucht. Diese ersten Modellierungsentscheidungen werden nun überprüft, präzisiert und schrittweise formalisiert.

Die praktische Ontologieentwicklung integriert sowohl **Domänenwissen** als auch **Anwendungsanforderungen** und überführt diese schrittweise in eine formal nutzbare Wissensstruktur.

> **Semantische Modellierung ist ein iterativer Prozess**
>
> - Semantische Modellierung verbindet **Domänenwissen, Anwendungsanforderungen, Ontologiedefinitionen und explizite Modellierungsentscheidungen**.
> - Ein Modell entsteht nicht in einer streng linearen Abfolge, sondern wird durch wiederholte Schritte der Analyse, Umsetzung und Überprüfung entwickelt und verfeinert.
> - Ziel ist es nicht allein, Klassen und Eigenschaften anzulegen, sondern die beabsichtigte Bedeutung **konsistent und nachvollziehbar** abzubilden.

---

## Ansätze und Methoden der Ontologieentwicklung

Bei der Entwicklung von Ontologien werden häufig **verschiedene Modellierungsansätze miteinander kombiniert** (Noy & McGuinness, 2001, S. 4 ff.):

**Bottom-up-Modellierung:**

Ausgangspunkt sind vorhandene Daten, Beispiele und domänenspezifische Begriffe. Relevante Konzepte und Beziehungen werden identifiziert und schrittweise zu einem Modell strukturiert. Klassen (Entities) und Eigenschaften (Properties) werden dabei aus konkreten Daten oder Beispielobjekten abgeleitet.

**Top-down-Modellierung:**

Ausgangspunkt ist eine bestehende Ontologie oder ein konzeptuelles Referenzmodell. Es wird untersucht, wie dessen Klassen und Eigenschaften das gewünschte Domänenwissen abbilden können. Ein Referenzmodell wie **CIDOC CRM** bildet die Grundlage für domänenspezifische Spezialisierungen.

**Competency Questions:**

Typische Analyse- und Forschungsfragen verdeutlichen, welche Anforderungen die Ontologie erfüllen soll. Sie helfen, den Gegenstandsbereich und die beabsichtigte Nutzung einzugrenzen, beispielsweise: **„Welche Spiele weisen das Merkmal X auf?“**

**Iteratives Prototyping:**

Ein zunächst kleiner Teil des Modells wird entwickelt, überprüft und schrittweise im Hinblick auf Konsistenz, Erweiterbarkeit und Abfragbarkeit verfeinert.

Diese Ansätze verfolgen unterschiedliche Zwecke und schließen sich nicht gegenseitig aus.

**In diesem Tutorial kombinieren Sie die Bottom-up-Analyse des Computerspielbeispiels mit einer Top-down-Ausrichtung am CIDOC CRM. Ausgewählte Modellierungsentscheidungen werden bei der Umsetzung in Protégé iterativ überprüft und verfeinert.**

---

## Der praktische Modellierungsworkflow

Der folgende Workflow bildet die Grundlage für die praktische Übung (M2EÜ) in diesem Modul:

**1. Konzeptuelles Modell überprüfen:** Wählen Sie relevante Konzepte und Beziehungen aus Ihrer Modellskizze aus.

↓

**2. Bedeutung klären:** Definieren Sie, was die ausgewählten Elemente innerhalb der Domäne repräsentieren.

↓

**3. CIDOC CRM untersuchen:** Identifizieren Sie geeignete Klassen und Eigenschaften und lesen Sie die zugehörigen Scope Notes.

↓

**4. Modellierungsentscheidungen treffen:** Entscheiden Sie, welche bestehenden Ontologieelemente wiederverwendet werden können und ob domänenspezifische Erweiterungen erforderlich sind.

↓

**5. Modell implementieren:** Setzen Sie ausgewählte Modellierungsentscheidungen in Protégé um.

↓

**6. Überprüfen und dokumentieren:** Prüfen Sie die entstandene Struktur, dokumentieren Sie Ihre Entscheidungen und überarbeiten Sie das Modell bei Bedarf.

Der Workflow ist **iterativ**. Wenn eine ausgewählte Klasse oder Beziehung die beabsichtigte Bedeutung nicht angemessen wiedergibt, kehren Sie zu einem früheren Schritt zurück und überprüfen Ihre Modellierungsentscheidung.

---

## Modellierungsstrategie im Tutorial

Bei der Entwicklung einer Domänenontologie auf Grundlage einer bestehenden Referenzontologie muss entschieden werden, **welche Ontologieelemente wiederverwendet werden können und wo domänenspezifische Erweiterungen erforderlich sind**.

Mögliche Strategien sind:

- **Wiederverwendung** bestehender CIDOC-CRM-Klassen (Entities) und -Eigenschaften (Properties)
- Bildung domänenspezifischer **Unterklassen (Entities)**
- Definition neuer domänenspezifischer **Eigenschaften (Properties)**
- **Kombinationen** dieser Ansätze

> **Unsere Modellierungsstrategie im Tutorial**
>
> In diesem Tutorial verfolgen Sie eine **leichtgewichtige Erweiterungsstrategie** auf Grundlage des CIDOC CRM:
>
> - **Bestehende CIDOC-CRM-Klassen und -Eigenschaften wiederverwenden**, soweit sie die beabsichtigte Bedeutung angemessen abbilden.
> - **Domänenspezifische Unterklassen anlegen**, wenn Konzepte aus der Computerspieldomäne eine weitere Spezialisierung erfordern.
> - **Keine neuen Eigenschaften definieren.** Für die vorgesehenen Beziehungen werden bestehende CIDOC-CRM-Eigenschaften verwendet.
> - **Scope Notes prüfen**, um neue Unterklassen geeigneten CIDOC-CRM-Klassen zuzuordnen.
> - **Modellierungsentscheidungen dokumentieren**, damit die resultierende Ontologie verständlich und wiederverwendbar bleibt.

### Beispiel: Leichtgewichtiges Modellieren

> - **Domänenkonzept:** *Spielgenre* → eine domänenspezifische Unterklasse einer geeigneten CIDOC-CRM-Klasse anlegen.
> - **Beziehung:** *hat Typ* → eine bestehende CIDOC-CRM-Eigenschaft wie **P2 has type** wiederverwenden, sofern sie die beabsichtigte Beziehung angemessen beschreibt, statt eine neue Eigenschaft einzuführen.

**Leitprinzip: CIDOC CRM durch domänenspezifische Unterklassen erweitern und die bestehende Eigenschaftsstruktur wiederverwenden.**

Dieser bewusst eingeschränkte Ansatz hält die praktische Übung (M2EÜ: Semantische Modellierung mit CIDOC CRM) überschaubar und ermöglicht es, sich auf Klassenhierarchien, semantische Bedeutungen und die Wiederverwendung einer etablierten Referenzontologie, z.B. CIDOC CRM zu konzentrieren.

Die Strategie **fördert Interoperabilität und Kompatibilität mit CIDOC CRM**, reduziert die Modellierungskomplexität und macht zugleich domänenspezifische Erweiterungen sichtbar.

**Hinweis zur Benennung domänenspezifischer Klassen:**

Bei der Erweiterung von CIDOC CRM ist es sinnvoll, die **CIDOC-CRM-Kennung im Namen einer domänenspezifischen Unterklasse beizubehalten**, beispielsweise `E73_Computer_Game` oder `E35_Game_Title`. Dadurch bleibt die Zuordnung zur jeweiligen CIDOC-CRM-Klasse erkennbar und die Modellierung nachvollziehbar.

Die Kennung im Klassennamen ersetzt jedoch nicht die **formale Unterklassenbeziehung** über `rdfs:subClassOf`.

Für die Veröffentlichung einer Domänenontologie werden die Klassen zudem über einen **eigenen Namespace** eindeutig identifiziert. Ein Beispiel hierfür bietet die [MEGA Game Characteristics Domain Ontology](https://games.m-e-g-a.org/ontology/game_characteristics/1.0/Game_characteristics_v1.0.3.rdf).

---

## Ausblick

Die hier vorgestellten **Methoden und Workflows der semantischen Modellierung** bilden zusammen mit der erläuterten **Modellierungsstrategie** die Grundlage für die praktische Umsetzung der bisher entwickelten Konzepte und Modelle.

Anhand des konkreten Beispiels "Zelda" entwickeln Sie auf Grundlage des **CIDOC CRM** eine **maschinenlesbare Domänenontologie**, beschreiben diese formal und bereiten sie für die maschinelle Verarbeitung vor.

> **Wie geht es weiter?**
>
> In der folgenden Einheit [**M2E1A: Protégé einrichten**](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/de/M2E2A_Protege-einrichten.md#1) bereiten Sie Ihre Arbeitsumgebung mit **Protégé** vor. Sie lernen **Protégé** als Editor zur Ontologiemodellierung kennen.

---

## Bibliografie

(Gruber, 1993) Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

(Noy & McGuinness, 2001) Noy, N. F., & McGuinness, D. L. (2001). Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory.

(Uschold & King, 1995) Uschold, M., & King, M. (1995). Towards an Methodology for Building Ontologies. Presented at Workshop on Basic Ontological Issues in Knowledge Sharing held in conjunction with IJCAI. The University of Edinburgh.
