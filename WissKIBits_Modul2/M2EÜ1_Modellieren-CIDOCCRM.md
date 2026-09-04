<!--
author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: c.hastik@igsd-ev.de

email: g.schwenk@igsd-ev.de

version:  v1

language: DE

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/liascript-oers/refs/heads/main/resources/SODa-Logo_full.svg
link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/SODa_WissKI-ISWC25Bits/refs/heads/main/soda.css

license: CC BY 4.0

comment: Dieses Modul ist Teil des SODa How-to-Tutorials „Ontologiegestützte Modellierung von Forschungsdaten“. Das Tutorial vermittelt am Beispiel einer Computerspielsammlung schrittweise die Entwicklung eines semantischen Datenmodells auf Grundlage des CIDOC CRM und dessen Umsetzung mit WissKI.

title: WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

module: Modellieren mit CIDOC CRM – verstehen und anwenden

einheit: Semnantische Modellierung von Forschungsdaten

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-09-04

LearningResourceType: SODa How-to-Tutorial

-->

# SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 2: **Modllieren mit CIDCO CRM – verstehen und anwenden**

Einheit Ü1: **Semantische Modellierung mit CIDOC CRM**  

**Dauer:** ~ 55 Min.

**Lernziele:**

Teilnehmende können...

- Ontologie zur Beschreibung von Ressourcen anwenden. (LZ-ID 03\_007\_0780)
- Methoden zur Entwicklung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0854)
- einen Workflow für die semantische Modellierung als Datendokumentation anwenden (LZ-ID SODa\_03\_001\_0627)
- unter Anleitung Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM anwenden. (LZ-ID SODa\_03\_001\_0786a) 
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa_03_007_0840)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM anwenden. (LZ-ID SODa_03_007_0855)
- Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa\_03\_007\_0780a)
  
---


## Ziel und Szenario

Dies ist eine Praxiseinheit. Ausgangspunkt ist das in Modul 1 entwickelte konzeptionelles Modell der Domäne Computerspiele.

Am Beispiel von **„The Legend of Zelda: A Link to the Past“** wird untersucht, wie aus dieser konzeptionellen Modellskizze schrittweise eine **formale Ontologiestruktur** entsteht.

Die hierfür notwendigen Schritte sind:

- ausgewählte Konzepte aus dem Domänenmodell mit Klassen des **CIDOC CRM** abgeglichen,
- Modellierungsentscheidungen anhand von **Definitionen und Scope Notes** überprüft,
- domänenspezifische Konzepte als **Subklassen** in Protégé angelegt,
- Properties im CIDOC CRM für die Beziehungen zwischen diesen Konzepten untersucht.

Im Mittelpunkt steht der  **Workflow der formalen Modellierung**.

Am Ende liegt ein formal umgesetzter Ausschnitt des Domänenmodells als **OWL-Ontologie** vor.

---

## Ausgangspunkt: Modell aus Modul 1

In Modul 1 wurde eine Modellskizze entwickelt, in der zentrale Konzepte und Beziehungen der Domäne Computerspiele beschrieben werden:

![Konzept-Mindmap](../WissKIBits_Modul2/assets/Mindmap.png)

Die gesammelten Begriffe der Domäne sollen nun mit CIDOC CRM und Protégé schrittweise formalisiert werden.

Für diese Übung können u.a. ausgewählt werden:

> Computerspiel → **hat Titel** → Spieltitel
>
> Computerspiel → **hat Typ** → Genre
>
> Computerspiel → **hat Typ** → Plattformtyp


Dabei unterscheiden wir drei Ebenen:

| Ebene                    | Beispiel                                            |
| ------------------------ | --------------------------------------------------- |
| Fachliche Aussage        | Spiel hat Titel                                     |
| Semantische Modellierung | E73 Information Object – P102 has title – E35 Title |
| Formale OWL-Struktur     | `Computer_Game SubClassOf P102 some Game_Title`     |

---

## Fokus dieser Modellierungsübung

Der Fokus liegt auf drei grundlegenden Arbeitsschritten:

**Schritt 1: Ontologie laden und Struktur erkunden**

**Schritt 2: CIDOC-CRM-Klassen auswählen und begründen**

**Schritt 3: Domänenspezifische Subklassen anlegen**  

**Schritt 4: Modell prüfen und Entscheidungen dokumentieren**

---

## Beispiel: Von der Modellskizze zur Ontologie

In Modul 1 wurde zunächst fachlich formuliert:

> Spiel → hat Titel → Titel

Für die semantische Modellierung wird nun untersucht, welche Elemente des CIDOC CRM diese Aussage ausdrücken können.

Ein möglicher Ausgangspunkt ist:

| Element           | mögliche CIDOC-CRM-Zuordnung |
| ----------------- | ---------------------------- |
| **Computerspiel** | E73 Information Object       |
| **Spieltitel**    | E35 Title                    |
| **Beziehung**     | P102 has title               |


Dabei ist **E35 Title** zugleich eine speziellere Form von **E41 Appellation**. Die Klassenhierarchie macht damit sichtbar, dass ein Titel eine besondere Form einer Benennung ist.

---

## Übung – Modell in Protégé umsetzen

**Arbeitsform:** Einzelarbeit oder Teams (2–4 Personen)

**Material:** Computer mit Protégé Desktop, bereitgestellte Erlangen-CRM-OWL-Datei, Modellskizze aus Modul 1 [Link]

**Zeit:** ~ 45 Min.

**Aufgabe: Einen Ausschnitt des Domänenmodells in Protégé nachmodellieren**

**Voraussetzung:**

Für das Arbeiten mit Protégé ist über die [**offizielle Protégé-Website**](https://protege.stanford.edu/) entweder 

- die Desktop-Anwendung ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege)) oder
- ein Account für den webbasierter Editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege))

einzurichten.

**Hinweis:**

> Für das Einrichten ist ein Zeitfenster von ca. 5 Minuten vorgesehen.

----

### Schritt 1: Erlangen CRM laden und Struktur erkunden

Öffnet Protégé Desktop und ladet die bereitgestellte OWL-Implementierung des CIDOC CRM:

[**Erlangen CRM / OWL**](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl): https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl

**Hinweis:** 

> Die im Live-Demo gezeigten Schritte und das entsprechende Video können in M2E2 nachgelesen werden:
>
> !?[Video-Demonstration Erste Schritte in Protége](../WissKIBits_Modul2/assets/Short_Protege_Intro.mp4)
> 


Erkundet anschließend kurz die Struktur der Ontologie und sucht in der Klassenhierarchie:

- **E41 Appellation**
- **E35 Title**
- **E55 Type**
- **E73 Information Object**

Untersucht dabei insbesondere:

- Wo befindet sich die Klasse in der Hierarchie?
- Welche Ober- und Unterklassen sind sichtbar?
- Welche Beschreibung bzw. Annotation ist hinterlegt?
- Welche Properties werden für die Klasse verwendet?

**Hinweis:**

> Achtet besonders auf **E41 Appellation** und **E35 Title**: E35 Title ist eine Unterklasse von E41 Appellation. Dadurch wird sichtbar, wie allgemeinere und speziellere Konzepte innerhalb einer Ontologie miteinander verbunden werden.

---

### Schritt 2: Passende CIDOC-CRM-Klassen auswählen und prüfen

Sucht in Protégé die passenden Klasse zum Domänenbegriff und prüft die Scope Note der Klasse.

Begründet die Auswahl.

**Beispiel**

> **E73 Information Object**
>
> **E35 Title**
>
> **E55 Type**

Ordne den Domänenbegriffen eine passende CIDOC-CRM-Klasse zu und begründe deine Entscheidung.

| Domänenbegriff     | mögliche CIDOC-CRM-Klasse |
| ------------------ | -------------------------- |
| Computer Game      | E73 Information Object     |
| Game Title         | E35 Title                  |
| Game Genre Type    | E55 Type                   |
| Game Platform Type | E55 Type                   |

### Begründungen

**Computer Game – E73 Information Object**

[[__________________________________________________]]

**Game Title – E35 Title**

[[__________________________________________________]]

**Game Genre Type – E55 Type**

[[__________________________________________________]]

**Game Platform Type – E55 Type**

[[__________________________________________________]]

**Hinweis:**

> Nicht der Name einer Klasse entscheidet über ihre Eignung, sondern ihre Bedeutung im Referenzmodell.

**Leitfragen zur Überprüfung der Klasse können sein**

- Was beschreibt die CIDOC-CRM-Klasse?
- Passt diese Bedeutung zu unserem Domänenbegriff?
- Welche Aussage der Scope Note unterstützt eure Entscheidung?
- Sind alternative Zuordnungen denkbar?

---

### Schritt 3: Domänenspezifische Subklassen anlegen

Legt nun die domänenspezifischen Unterklassen in Protégé an.

Die Unterklassen sollen unter den zuvor ausgewählten CIDOC-CRM-Klassen eingeordnet werden:

```text
E73 Information Object
└── Computer_Game

E35 Title
└── Game_Title

E55 Type
├── Game_Genre_Type
└── Game_Platform_Type
```

Prüft anschließend die Klassenhierarchie.

Sucht in Protégé die passenden Beziehungen zu den gewählten Unterklassen und untersucht die Beschreibung der Properties.

**Beispiel: Für den Titel**

> Computerspiel → **hat Titel** → Spieltitel
>
> Sucht **P102 has title**


**Beispiel: Für den Genre oder Plattform**

> Computerspiel → **hat Typ** → Genre / Plattformtyp
>
> Sucht nach: **P2 has type**

Dokumentiert eure Prüfung:

| Ausgang       | Property       | Ziel               | beabsichtigte Aussage                                 |
| ------------- | -------------- | ------------------ | ----------------------------------------------------- |
| Computer_Game | P102 has title | Game_Title         | Ein Computerspiel hat einen Titel.                    |
| Computer_Game | P2 has type    | Game_Genre_Type    | Ein Computerspiel wird einem Genretyp zugeordnet.     |
| Computer_Game | P2 has type    | Game_Platform_Type | Ein Computerspiel wird einem Plattformtyp zugeordnet. |

**Hinweis:**

> Die Properties werden im nächsten Modul 3 benötigt.


**Leitfragen:**

- Passt die Bedeutung der Property zu unserer fachlichen Aussage?
- Sind Ausgangs- und Zielklasse mit Domain und Range vereinbar?
- Beschreibt die Property tatsächlich die Beziehung, die wir ausdrücken möchten?

---

### Schritt 5: Modell prüfen und dokumentieren 

Vergleicht euer Ergebnis mit der ursprünglichen Modellskizze:

![Konzept-Mindmap](../WissKIBits_Modul2/assets/Mindmap.png)


**Modellierung prüfen**

- Sind die domänenspezifischen Klassen sinnvoll in die CIDOC-CRM-Hierarchie eingeordnet?
- Passen die Properties zur beabsichtigten Aussage?
- Können die Entscheidungen anhand der Scope Notes begründet werden?
- Lassen sich die Beziehungen weiterhin als verständliche Aussagen lesen?
- Welche Elemente stammen aus CIDOC CRM und welche wurden für die Domäne ergänzt?
- Schreibt für die neu angelegten Domönen-Unterklassen Scope Notes / Comments und vergebt Lables.


**Modellierungsentscheidung dokumentieren**

Dokumentiert für **eine** Zuordnung eure Entscheidung:

| Frage                                                | Antwort |
| ---------------------------------------------------- | ------- |
| Welchen Domänenbegriff modellieren wir?              |         |
| Welche CIDOC-CRM-Klasse oder Property verwenden wir? |         |
| Welche Bedeutung möchten wir ausdrücken?             |         |
| Was sagt die Scope Note dazu?                        |         |
| Warum halten wir die Zuordnung für geeignet?         |         |

**Hinweis:** 

> Es geht nicht darum, eine einzig „richtige“ Lösung zu finden. Entscheidend ist, dass die Modellierungsentscheidung fachlich nachvollziehbar und mit dem verwendeten Referenzmodell vereinbar ist.

---

## Musterlösung

Als Musterbeispiel kann die bestehende Domänenontologie für Computerspiele betrachtet werden:

[**Game Domain Ontology – RDF**](http://games.m-e-g-a.org/game_domain.rdf)

Vergleicht eure eigene Modellierung erst **nach Abschluss der Aufgabe** mit dem Musterbeispiel. Das Musterbeispiel ist als Modellierungsvorschlag zu verstehen und nicht als einzig mögliche Lösung.

**Hinweis**

> Achtet dabei insbesondere auf:
>
> - die Einordnung domänenspezifischer Klassen,
> - die Wiederverwendung von CIDOC CRM Properties,
> - und mögliche Unterschiede zu euren eigenen Modellierungsentscheidungen.

---

## Ergebnis

Am Ende dieser Übung liegt ein kleiner formal umgesetzter Ausschnitt des Domänenmodells **Computerspiele** vor.

Ihr habt:

- domänenspezifische Konzepte als **Subklassen** des CIDOC CRM angelegt,
- und eine Modellierungsentscheidung anhand einer **Scope Note** begründet.

Speichert die erweiterte Ontologie anschließend als **OWL-Datei**.

**Hinweis:** 

> Die Ontologie ist weiterhin ein Modellausschnitt.
> 
> Sie bildet nicht die gesamte Domäne Computerspiele ab, sondern dokumentiert exemplarisch den Weg von einer fachlichen Modellskizze zu einer maschinenlesbaren Ontologiestruktur.


---

## Nachnutzung

Die in diesem Ordner enthaltenen Daten stehen unter der Lizenz CC BY 4.0 (Creative Commons Attribution 4.0 International).

Das bedeutet: Sie dürfen die Daten frei nutzen, teilen und weiterverarbeiten, solange die Quelle genannt wird.

Diese Praxiseinheit Modul 3 mit allen Ressourcen ist veröffentlicht und verfügbar auf Zenodo und GitHub:

xxxxx

### Zitation

xxxxx

---

## Ausblick

Mit dieser Übung wurde das in Modul 1 entwickelte Domänenmodell erstmals **formal in Protégé umgesetzt**.

Dabei wurden drei Ebenen miteinander verbunden:

> **fachliche Aussage → CIDOC-CRM-Modellierung → OWL-Formalisierung**

Die gespeicherte OWL-Datei bildet die Grundlage für **Modul 3**.


