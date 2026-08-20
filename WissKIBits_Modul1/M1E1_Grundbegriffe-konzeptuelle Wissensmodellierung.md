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

Einheit 1: **Grundbegriffe konzeptueller Wissensmodellierung**  

**Dauer:** ca. XX Min.

**Lernziele:**

Teilnehmende können...

* Begriff Attribut benennen. (LZ-ID SODa\_xy\_xyz\_xyza) ??? löschen oder  verschieben in E0
* Begriff semantische Modellierung benennen. (LZ-ID SODa\_03\_007\_0825) ??? löschen oder  verschieben in E0
* Begriff semantisches Datenmodell benennen (LZ-ID SODa\_xy\_xyz\_xyza) ??? löschen oder verschieben in E0
* Begriff konzeptuelle Wissensmodellierung benennen.
* Begriff konzeptuelle Wissensmodellierung erläutern.
* Begriff Domäne benennen. (LZ-ID SODa\_03\_007\_0824)
* Begriff Konzept benennen. (LZ-ID SODa\_03\_007\_0821)
* Begriff Ereignis benennen. (LZ-ID SODa\_03\_007\_0822)
* Begriff Beziehung benennen. (LZ-ID SODa\_03\_007\_0823)
  
---

## Einführung: Von der konzeptuellen Analyse und Wissensmodellierung zur semantischen Datenmodellierung

In dieser Einheit wird die **konzeptuelle Wissensmodellierung** innerhalb einer Domäne als Grundlage der **semantischen Datenmodellierung** vorgestellt.

- In den Geistes- und Kulturwissenschaften, GLAM-Institutionen und Forschungssammlungen wird mit **komplexen Objekt- und Kontextdaten** gearbeitet, die historische, kulturelle und soziale Bedeutungen tragen (z. B. Provenienz, Beziehungen, Interpretationen).
- Tabellen können Daten zwar beschreiben und erfassen, stellen aber in erster Linie Eigenschaften bzw. Merkmale (Attribute) (Fischer2010encyclopcompscience, S. 77) von Datenobjekten dar. Der fachliche Bedeutungszusammenhang, in dem diese Datenobjekte stehen, einschließlich der zugrunde liegenden Konzepte, Beziehungen und Kontexte, wird dabei nicht explizit repräsentiert.
- Damit Daten **inhaltlich langfristig interpretierbar und nachnutzbar** sind, muss die **Bedeutung der Daten** erfasst und formal beschrieben werden. (Fichtner2025paths, S. 58). Dazu muss modelliert werden, wie Daten innerhalb eines bestimmten Wissensbereichs und Kontextes verstanden, interpretiert und miteinander in Beziehung gesetzt werden. (Schwenk2025sodaforumconservation, S. 21)
- 
- Genau hier wird **semantische (Daten-)modellierung** relevant, der **Prozess, Konzepte, Begriffe und Relationen eines Wissensbereichs zu identifizieren, zu strukturieren und zu formalisieren**. (Schwenk2025sodaforumconservation, S. xy)
- Semantisches Modellieren ist vor allem ein **konzeptueller Prozess**. Er ist disziplinübergreifend und erfordert gleichzeitig **fachwissenschaftliches Wissen und Modellierungskompetenz**. (Fichtner2025paths, S. 86) Die so beschriebenen Konzepte, Begriffe und Relationen werden in semantischen Datenmodellen formal repräsentiert.
- 
- Ein **semantisches Datenmodell** ist ein konzeptueller, formaler Rahmen, der die Bedeutung von Daten durch die Definition von Konzepten und Begriffen, ihre Relationen und Regeln innerhalb eines Wissensbereichs beschreibt. Es dient nicht der Darstellung konkreter Daten, sondern stellt dar, wie Daten aus einem bestimmten Wissensbereich und Kontext verstanden, interpretiert und miteinander in Beziehung gesetzt werden.
<!-- Diese formale Repräsentation bildet die Grundlage für ihre technische Umstzung und maschinelle Verarbeitung.-->
- Eine Forschungsinfrastruktur, die diesen Prozess unterstützt ist **WissKI** (Wissenschaftliche Kommunikationsinfrastruktur), indem es die konzeptuelle Modellierung eines Wissensbereichs mit der semantischen Erfassung, Verwaltung  und Speicherung von Forschungsdaten verbindet.
- Die Daten werden auf diese Weise sowohl **inhaltlich als auch technisch langfristig interpretierbar und damit entsprechend wissenschaftlichen Qualitätskritierien nachnutzbar**. (Fichtner2025paths, S. xy)

---

## Begriffsdefinitionen der konzeptuellen Wissensmodellierung

Bei der **Konzeptuellen Wissensmodellierung** wird herausgearbeitet welches Wissen innerhalb einer Domäne relevant ist und wie es konzeptuell geordnet werden kann.

Eine **Domäne** bezeichnet einen Wertebereich (Fischer2010encyclopcompscience, S. 257) für den Wissen beschrieben und modelliert wird. In der **semantischen Datenmodellierung** versteht man unter Domäne den fachlichen Wissens- und Anwendungsbereich, dessen Konzepte, Ereignisse und Beziehungen erfasst und formal repräsentiert werden. (Quelle?)

Zentralen Elemente der konzeptuellen Wissensmodellierung sind **Konzept, Ereignis und Beziehung**.

- **Konzepte** sind abstrakte Begriffe, die die zentrale Bausteine einer Domäne bezeichnen. Beispiele sind Objekte, Personen, Orte, Institutionen.
- **Ereignisse** sind eine strukturierte Sammlung von Abläufen, Hergängen und Prozessen die kontextbezogene informationen über Konzepte bereitstellen. Beispiele sind Herstellung, Erwerb, Fund, Restaurierung, Ausstellung oder Nutzung eines Objektes.
- **Beziehungen** beschreiben die semantische Verknüpfung zwischen Konzepten oder zwischen Konzepten und Ereignissen. Beispiele sind Objekt "wurde hergestellt von" Person und Objekt "wurde hergestellt" bei Herstellung.

Die Identifikation und Strukturierung dieser Elemente bildet die Grundlage der **semantischen Modellierung**. 

Erst wenn die relevanten Konzepte, Ereignisse, Beziehungen einer Domäne verstanden und strukturiert sind, können sie in einem semantischen Datenmodell dargestellt werden. 

Grafik?
---

## Aktivierung und Input: Wissen einer Sammlung konzeptuell ordnen
(überarbeiten) 
**Arbeitsform:** Modellieren   
**Material:** keines  
**Zeit:** 10 Min.  

In dieser Aufgabe geht es darum, Kernkonzepte, -ereignisse und -beziehungen als Aussagen der eigenen Sammlung zu beschreiben.

Denkt an ein typisches Objekt aus eurer Sammlung: Welche Information muss zwingend dokumentiert sein, damit Forschung möglich wird?

Die Aussagen werden sichtbar an einem [Board](https://miro.com/app/board/uXjVGKauOtE=/) oder auf Papier skizziert:

- Konzepte (Objekt, Person, Ort, Zeit…)
- Ereignisse (Herstellung, Nutzung, Erwerb, Fund…)
- Beziehungen (Rollen, Zugehörigkeiten, Teil-von, identisch mit…)

**Hinweis:**
- ...

---

## Ergebnis

Grafik / Musterergebnis 
  
---

## Zusammenfassung

(überarbeiten) 

Anforderungen aus der Sammlungspraxis bilden die Grundlage, um in diesem Modul 1 zentrale Konzepte, Ereignisse und Beziehungen zu identifizieren und daraus ein konsistentes, nachvollziehbares Domänenmodell und -diagramm zu entwickeln. 

Damit können Forschungsfragen an Sammlungen gestellt werden, wie...

- „… der Herstellungs-/Entstehungskontext klar ist.“
- „… Akteur:innen und Rollen unterscheidbar sind.“
- „… Provenienzereignisse nachvollziehbar sind.“
- „… Ort und Zeit belastbar sind.“
- „… Unsicherheiten (Hypothesen) abbildbar sind.“
- „… eine eindeutige Identifizierung durch z. B. Signatur-/Inventarnummer möglich ist.“

---

## Ausblick

... kurz: wie setzen wir das mit Ontologien nun um?... was haben Ontologien damit zu tun...

---

## Bibliographie


[Fichtner2025paths] Fichtner, M. (2025). Grundlagen der Erzeugung und Verwaltung von Ontologiepfaden und ihre Anwendung (Doctoral thesis, Friedrich-Alexander-Universität Erlangen-Nürnberg, Technische Fakultät). https://doi.org/10.25593/open-fau-2143

[Fischer2010encyclopcompscience] Fischer, P. & Hofer, P. (2010). Lexikon der Informatik. https://doi.org/10.1007/978-3-642-15126-2

[Rehbein2017ontologies] Rehbein, M. (2017). Ontologien. In: F. Jannidis, H. Kohle, & M. Rehbein (Hrsg.), *Digital Humanities* (S. 162-176). J.B. Metzler, Stuttgart. https://doi.org/10.1007/978-3-476-05446-3_11

[Schwenk2025sodaforumconservation] Schwenk , G. A. & Fischer, K. (2025), SODa Forum: Konservierungs- und Restaurierungsdokumentation gemeinsam weiterdenken - Ontologieentwicklung im Dialog. Zenodo. https://doi.org/10.5281/zenodo.15481743



