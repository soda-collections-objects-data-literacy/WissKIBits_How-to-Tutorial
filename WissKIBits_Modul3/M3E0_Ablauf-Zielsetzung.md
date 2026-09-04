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

module: Vom Diagramm zu Pfaden – erläutern und anwenden

einheit: Willkommen, Zielsetzung und Ablauf

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-09-04

LearningResourceType: SODa How-to-Tutorial

-->


# Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 3: **Vom Diagramm zu Pfaden – erläutern und anwenden**

Einheit 0: **Willkommen, Zielsetzung und Ablauf**

**Dauer:** ~ 10 Min.

---

## Begrüßung

> Willkommen zu **SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten**.
>
> Dieses How-to-Tutorial führt praxisorientiert in die ontologiegestützte Modellierung von Forschungsdaten ein. Ausgehend von Informationen zu einem Sammlungsobjekt wird schrittweise ein semantisch aussagekräftiges Datenmodell entwickelt und für die Nutzung in WissKI implementiert.
>
> In Modul 1 wurde aus Objektdaten und Kontextinformationen eine konzeptuelle Modellskizze entwickelt. In Modul 2 wurde diese Skizze methodisch überprüft und mit CIDOC CRM und Protégé als formale Ontologiestruktur umgesetzt.
>
> Modul 3 **„Vom Diagramm zu Pfaden – erläutern und anwenden“** führt diesen Lernweg in die technische Implementierung: Das semantische Datenmodell wird in Draw.io als formal strukturiertes Diagramm visualisiert. Anschließend wird das Diagramm mithilfe des Webdienstes **„Draw.io diagrams to WissKI pathbuilders“** geprüft und in eine WissKI-Pathbuilder-XML-Datei transformiert.
>
> Die erzeugte Datei wird in WissKI importiert. Dort werden die Pfade und Pfadgruppen analysiert und als Grundlage für die strukturierte Erfassung, Speicherung und Abfrage von Forschungsdaten vorbereitet.
>
> Das Modul folgt dem Prinzip **Learning by Doing**. Am Beispiel aus der Domäne Computerspiele vollziehen die Teilnehmenden die gesamte Verarbeitungskette vom semantischen Diagramm über die Dateikonvertierung bis zur importierten Pfadstruktur im WissKI Pathbuilder nach.

---

## Zielsetzung des Moduls

In Modul 3 wird die in Modul 2 formalisierte Domänenontologie in eine für WissKI nutzbare Pfadstruktur überführt.

* Die Domänenontologie wird in Draw.io als semantisches Diagramm visualisiert.
* Klassen (Entities), Eigenschaften (Properties) und vollständige semantische Pfade werden nach festgelegten Modellierungsregeln dargestellt.
* Für die Konvertierung benötigte Attributwerte werden an den relevanten Diagrammelementen ergänzt und geprüft.
* Das Diagramm wird als Draw.io-XML-Datei für die weitere Verarbeitung bereitgestellt.
* Der Webdienst **„Draw.io diagrams to WissKI pathbuilders“** wird zur Prüfung und Konvertierung des Diagramms eingesetzt.
* Aus dem Diagramm wird eine WissKI-Pathbuilder-XML-Datei erzeugt.
* Die domänenspezifische Ontologie und die erzeugte Pfadstruktur werden in WissKI eingebunden.
* Die importierten Pfade und Pfadgruppen werden analysiert und auf ihre fachliche und strukturelle Plausibilität geprüft.

---

## Leitfrage

> **Wie wird aus einem semantischen Datenmodell eine valide und in WissKI nutzbare Struktur aus Pfaden und Pfadgruppen?**

Diese Leitfrage begleitet alle Einheiten des Moduls. Dabei wird zwischen drei Verarbeitungsschritten unterschieden:

| Verarbeitungsschritt | Leitfrage | Ergebnis |
|---|---|---|
| visualisieren | Wie werden Klassen (Entities), Eigenschaften (Properties) und Pfade eindeutig in Draw.io dargestellt? | formalisiertes Diagramm |
| transformieren | Wie wird das Diagramm geprüft und in das Pathbuilder-Format konvertiert? | Pathbuilder-XML-Datei |
| implementieren und prüfen | Wie wird die Datei in WissKI importiert und die erzeugte Pfadstruktur analysiert? | nutzbarer WissKI Pathbuilder |

---

## Ablauf des Moduls

**Gesamtdauer Modul 3: ca. 90 Min.**

| Einheit | Inhalt | Dauer |
|---|---|---:|
| 0 | Willkommen, Zielsetzung und Ablauf | 10 Min. |
| Ü1 | Semantische Datenmodelle visualisieren | 35 Min. |
| Ü2 | Transformation semantischer Modelle in WissKI-Pfade | 40 Min. |
|  | **Gesamt** | **90 Min.** |

---

## Lernziele des Moduls

Nach Abschluss von Modul 3 können die Teilnehmenden…

### 1. Semantische Datenmodelle visualisieren

- Software zur Visualisierung einer Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0812)
- Software zur Visualisierung einer Domänenontologie erläutern. (LZ-ID LZ-ID SODa\_03\_007\_0813)
- Begriff Visualisierung erläutern. (LZ-ID SODa\_03\_007\_0851)
- Nutzen von Visualisierungen erläutern. (LZ-ID SODa\_03\_007\_0852)
- Nutzen einer Software zur Visualisierung einer Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0814) 
- Software zur Visualisierung einer Domänenontologie unter Anleitung anwenden. (LZ-ID SODa\_03\_007\_0815)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung benennen. (LZ-ID SODa\_03\_007\_0806)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0811)
- Regeln zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware benennen. (LZ-ID SODa\_03\_007\_0820)
- Regeln zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware anwenden. (LZ-ID SODa\_03\_007\_0816)
- Attributwerte an vordefinierten Klassen der Domänenontologie in einer Visualisierungssoftware anwenden. (LZ-ID SODa\_03\_007\_0817)

### 2. Transformation semantischer Modelle mit gnm-service

- WissKI Pathbuilder als Werkzeug zur Defintion einer Ontologiestruktur erläutern. (LZ-ID SODa\_03\_007\_0804)
- unter Anleitung die Datenkonvertierung einer Visualisierungssoftware in ein nachnutzbares Dateiformat anwenden. (LZ-ID SODa\_02\_005\_0298a)
- unter Anleitung WissKI Pathbuilder als Werkzeug zum Import einer domänenspezifischen Ontologiestruktur (Pathbuilder-XML-Datei im WissKI-Pathbuilder) anwenden. (LZ-ID SODa\_03\_007\_0818)
- unter Anleitung die importierte domänenspezifische Ontologiestruktur im WissKI-Pathbuilder analysieren. (LZ-ID SODa\_03\_007\_0819)
- ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung benennen. (LZ-ID SODa\_02\_005\_0317) 
- unter Anleitung ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung anwenden. (LZ-ID SODa\_02\_005\_0318)

### 3. Vom Pathbuilder zur Wissensbasis

- WissKI Pathbuilder als Werkzeug zur Defintion einer Ontologiestruktur erläutern. (LZ-ID SODa\_03\_007\_0804)
- unter Anleitung die Datenkonvertierung einer Visualisierungssoftware in ein nachnutzbares Dateiformat anwenden. (LZ-ID SODa\_02\_005\_0298a)
- unter Anleitung WissKI Pathbuilder als Werkzeug zum Import einer domänenspezifischen Ontologiestruktur (Pathbuilder-XML-Datei im WissKI-Pathbuilder) anwenden. (LZ-ID SODa\_03\_007\_0818)
- unter Anleitung die importierte domänenspezifische Ontologiestruktur im WissKI-Pathbuilder analysieren. (LZ-ID SODa\_03\_007\_0819)
- ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung benennen. (LZ-ID SODa\_02\_005\_0317) 
- unter Anleitung ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung anwenden. (LZ-ID SODa\_02\_005\_0318)

---

## Lernweg im Modul

> **Formale Ontologiestruktur aus Modul 2**
> 
> ↓
> 
> **Semantisches Diagramm in Draw.io**
> 
> ↓
>  
> **Diagramm und Attributwerte prüfen**
> 
> ↓
> 
> **Pathbuilder-XML erzeugen**
> 
> ↓
> 
> **Datei in WissKI importieren**
> 
> ↓
>  
> **Pfade und Pfadgruppen analysieren**



> **Abbildung:** Die Grafik veranschaulicht den Lernweg des Moduls.

---

## Arbeitsweise und Beispiel

Das Modul verbindet Aktivierung, angeleitete Modellierung, technische Transformation und Ergebniskontrolle:

- Zu Beginn werden Forschungs- und Abfragefragen aus der Sammlungsperspektive aufgegriffen: Welche Informationen sollen später über semantische Pfade auffindbar und abfragbar sein?
- Das Beispielobjekt **„The Legend of Zelda: A Link to the Past“** und die in den vorherigen Modulen entwickelte Domänenontologie dienen erneut als roter Faden.
- In Draw.io vervollständigen die Teilnehmenden ein vorbereitetes Diagramm um fehlende Klassen (Entities) und Eigenschaften (Properties).
- Sie prüfen vollständige Pfade, Knoten-Kanten-Verbindungen, Benennungen und die für die Konvertierung benötigten Attributwerte.
- Das Diagramm wird als XML-Datei an den Konvertierungsdienst übergeben.
- Die erzeugte Pathbuilder-XML-Datei wird in WissKI importiert.
- Abschließend werden Pfade und Pfadgruppen mit dem Ausgangsdiagramm und den fachlichen Abfragewünschen verglichen.

Das Ziel ist nicht die vollständige technische Konfiguration einer WissKI-Instanz. Entscheidend ist eine **nachvollziehbare und wiederholbare Verarbeitungskette**, die das semantische Modell in eine nutzbare WissKI-Pfadstruktur überführt.

---

## Voraussetzungen

Vorausgesetzt werden die Inhalte aus Modul 1 und Modul 2 oder vergleichbare Grundkenntnisse und Arbeitsergebnisse. Die Teilnehmenden sollten …

- Konzepte, Ereignisse und Beziehungen einer Domäne identifizieren können,
- mit dem ereigniszentrierten Modellierungsprinzip und ausgewählten Elementen des CIDOC CRM vertraut sein,
- Scope Notes für Modellierungsentscheidungen nutzen können,
- eine formal umgesetzte Domänenontologie beziehungsweise Ontologieerweiterung kennen,
- sowie das Grundprinzip von semantischen Pfaden verstanden haben.

Für die praktische Anwendung werden benötigt:

- ein Computer mit Internetzugang,
- Zugriff auf [diagrams.net (Draw.io)](https://app.diagrams.net/),
- die vorbereitete [Draw.io-XML-Lücken-Diagramm](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_A.drawio.xml),
- Zugriff auf den Konvertierungsdienst [Draw.io diagrams to WissKI pathbuilders](https://isl.ics.forth.gr/gnm_services),
- Zugang zu einer WissKI-Instanz über den [SODa Semantic Co-Working Space (SCS)](https://manager.scs.sammlungen.io/de),
- sowie die im Tutorial verwendete [Domänenontologie](http://games.m-e-g-a.org/game_domain.rdf) und Referenzontologie [Erlangen CRM / OWL](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl).


## Ergebnis des Moduls

Am Ende von Modul 3 liegen folgende Arbeitsergebnisse vor:

- ein nach den vorgegebenen Regeln vervollständigtes semantisches [Draw.io-Diagramm](../WissKIBits_Modul3/assets/GamesDrawioDiagramm.png),
- eine exportierte [Draw.io-XML-Datei](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/SODa_ISWC2025.drawio.xml),
- eine durch den Konvertierungsdienst "Draw.io diagrams to WissKI pathbuilders" erzeugte [WissKI-Pathbuilder-XML-Datei](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput_ISWC2025.xml),
- eine in WissKI importierte Struktur aus Pfaden und Pfadgruppen,
- sowie eine dokumentierte Prüfung der importierten Struktur anhand des Ausgangsmodells und ausgewählter fachlicher Abfragefragen.

Die importierte Pfadstruktur bildet die Grundlage für die Generierung von Drupal-Bundles, Feldern und Dateneingabeformularen sowie für die anschließende Erfassung und Abfrage semantisch strukturierter Forschungsdaten in WissKI.

---

## Ausblick

Im nächsten Schritt werden aus den importierten Pfaden und Pfadgruppen Eingabestrukturen in WissKI generiert. Anschließend können Beispieldaten erfasst und anhand der zu Beginn formulierten Forschungs- und Abfragefragen geprüft werden. So wird sichtbar, ob das entwickelte Modell die vorgesehenen Informationsbedarfe tatsächlich unterstützt.

Für weiterführende News, Informationen zu WissKI, die WissKI Dokumentation und WissKI Community (Stand: August 2026) verweisen wir auf die Webseite: https://wiss-ki.eu/de. 


---

## Redaktionelle Hinweise

* Die Zeitplanung ist auf insgesamt 90 Minuten abgestimmt. Da beide Facheinheiten praktische Aufgaben enthalten, sollte die Dauer nach einem Testlauf überprüft werden.


