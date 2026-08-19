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

Modul 2: **Vom Diagramm zu Pfaden – erläutern, validieren und anwenden**

Einheit 1: **Ablauf und Zielsetzung**  

**Dauer:** ~ 15 Min.

Lernziel

* für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen benennen. (LZ-ID SODa\_01\_010\_0190a) 


---

## Begrüßung


> Willkommen zu **WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten**.
> 
> Dieses How-to-Tutorial bietet eine praxisorientierte Einführung in die **Arbeit und Analyse mit strukturierten Forschungsdaten** – von der ersten Beschreibung eines Sammlungsobjekts bis zur semantisch belastbaren Modellstruktur (**Datenmodell am Beispiel entwickeln und implementieren**).
>
> Im Modul 2: **Vom Diagramm zu Pfaden – erläutern, validieren und anwenden** wird das entworfene Datenmodell in Modul 1 in ein CIDOC CRM-basierte Pfadstruktur überführt:
>
> Aus dem in *Draw.io* erstellten semantischen Modell wird eine *WissKI Pathbuilder*-Datei generiert. Auf diese Weise wird die konzeptionelle Domänenontologie in eine in WissKI nutzbare Graphstruktur überführt.
>
> Diese dient dann als Grundlage für die Arbeit mit und die Analyse von graphbasierten Forschungsdaten.  
>
> Ziel ist es, eine fachliche Domänenlogik so präzise mit CIDOC CRM abzubilden, dass das Domänenmodell maschinenlesbar konsistent umgesetzt ist, nachvollziehbar und gezielt abgefragbar wird.
>
> Das Modul ist als **How-to-Tutorial** für die **Wissenschaftliche Kommunikationsiunfrastruktur WissKI** konzipiert und folgt dem Prinzip Learning by Doing:
>
> An einem Beispiel wird aus der Sammlungsperspektive eine Modellperspektive erarbeitet und so die Grundlage für die Visualisierung in einem Diagramm und die spätere Umsetzung in WissKI geschaffen.
>
> In den weiterführenden Einheiten wird dieser anleitende Ansatz um selbstgesteuerte Lernphasen ergänzt, in denen das eigene Wissen vertieft, eigene Forschungsdaten modelliert und die erlernten Methoden auf individuelle Forschungskontexte angewendet werden können.

---

## Zielsetzung des Moduls

In Modul 2 wird die konzeptionelle Basis aus Modul 1 schrittweise in ein für WissKI verwaltbares Domänenmodell als Grundlage für das sammlungsbezogene Datenmanagement überführt.
 

* Die Domänenlogik wird als CIDOC CRM-basiertes semantisches Modell mit Pfaden in Draw.io visualisiert.
* Die Visualisierung wird auf syntaktische Gültigkeit anhand CIDCO-CRM überprüft und in ein nachnutzbares Dateiformat überführt.
* Das domänenspezifische Modell wird in WissKI importiert, dort validiert und für die Analyse weiter vorbereitet.

---

## Ablauf des Moduls


**Modul 2: 90 Min.**


| Einheit | Inhalt | Zeit |
|--------|--------|------|
| 1 | Ablauf und Zielsetzung | 15 Min. |
| 2 | Visualisierung der Domänenontologie in Draw.io | 25 Min. |
| 3 | Automatische Pfadgenerierung: Konsistenz prüfen und WissKI Pathbuilder-Datei erzeugen | 25 Min. |
| 4 | Transfer, Nächste Schritte und Feedback | 15 Min. |


---

## Lernziele

Lernende können... 


* für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen benennen. (LZ-ID SODa\_01\_010\_0190a) 
* Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0811)
* Software zur Visualisierung einer Domänenontologie benennen und erläutern.(LZ-ID SODa\_03\_007\_0812 und LZ-ID SODa\_03\_007\_0813)
* Nutzen einer Software zur Visualisierung einer Domänenontologie benennen.(LZ-ID SODa\_03\_007\_0814) 
* Software zur Visualisierung einer Domänenontologie unter Anleitung anwenden. (LZ-ID SODa\_03\_007\_0815)
* Regeln zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware benennen. (LZ-ID SODa\_03\_007\_0820)
* Regeln zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware anwenden. (LZ-ID SODa\_007\_0816)
* Attributwerte an vordefinierten Klassen der Domänenontologie in einer Visualisierungssoftware anwenden. (LZ-ID SODa\_03\_007\_0817)
* WissKI Pathbuilder als Werkzeug zur Entwicklung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0804)
* unter Anleitung die Datenkonvertierung einer Visualisierungssoftware in ein nachnutzbares Dateiformat anwenden. (LZ-ID SODa\_02\_005\_0298a)
* unter Anleitung ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung benennen und anwenden. (LZ-ID SODa\_02\_005\_0317 und LZ-ID SODa\_02\_005\_0318)
* unter Anleitung WissKI Pathbuilder als Werkzeug zum Import einer domänenspezifischen Ontologiestruktur (Pathbuilder-XML-Datei im WissKI-Pathbuilder) anwenden. (LZ-ID SODa\_03\_007\_0818)
* unter Anleitung die importierte domänenspezifische Ontologiestruktur im WissKI-Pathbuilder analysieren. (LZ-ID SODa\_03\_007\_0819)
* es fehlen noch zwei Lernziele in M2E4 


---

## Voraussetzung

Folgende Grundkenntnisse werden vorausgesetzt:

* WissKI und die Basisfunktionen sind grundlegend bekannt.
* Es gibt erst Erfahrung in der konzeptuellen Modellierung von Domänenontologien.
* Mit CIDOC CRM wurde bereits gearbeitet.
* Protége ist bekannt.

Eine Einführung in diese Themen bietet Modul 1.

--- 

## Aktivierung und Input

In Modul 1 wurde festgelegt, welche Information dokumentiert sein sollte. Wir blicken nochmal auf die erste Aktivierungsübung (M1E1) zurück.

[Vorlage öffnen](../assets/M1E1_Aktivierung.docx)

oder 

[Miro Board öffnen]()


**Impulsfrage** 

Welche Fragen fallen euch zu dem Gegenstandsbereich ein und sollten zuverlässig beantworten werden?

**Zuruf im Plenum**

Abfragewünsche werden gesammelt und zur Aktivierungsaufgabe (M1E1) ergänzt:

* „Wir wollen finden…“


---

### Lösungsbeispiele aus dem Spielekontext

_Hilfestellung – nicht vorgeben_

* „… alle Spiele mit einer bestimmten Eigenschaft (z. B. Genre oder Modus).“
* „… alle Spiele, die mit einer bestimmten Person/Organisation verknüpft sind (z. B. Entwickler:in, Studio, Publisher).“
* „… alle Spiele bzw. Spielversionen aus einem Zeitraum X oder einer Region/Plattform Y.“
* „… Spiele mit ähnlichen Merkmalen (z. B. ähnliche Beschreibung, ähnliche Einordnung, ähnliche Eigenschaften).“

---

### Lösungsbeispiele 

* „… alle Objekte mit bestimmter Provenienzstation“
* „… alle Werke einer Person in einer bestimmten Rolle“
* „… alle Ereignisse in Zeitraum X an Ort Y“
* „… Objekte mit ähnlichen Kontextmerkmalen“


**In Pfaden denken**

Schaut noch einmal auf die Modellskizze aus der Modellierungsübung (M1E5) und prüft: 

* "Welche Frage ist beantwortbar? Benennt den/die Pfad/e."
*  "Wo startet die Anfrage?"

---

## Zusammenfassung

Aus dem konzeptuellen Domänenmodell entstehen in Modul 2 formalisierte Pfade, also eine valide domänenspezifische Ontologiestruktur für den WissKI-Pathbuilder, mit der die Fragen beantwortet werden können.



