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

module: Vom Diagramm zu Pfaden – erläutern und anwenden

unit: Willkommen, Zielsetzung und Ablauf

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontologiebasierte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 3 (M3): **Vom Diagramm zu Pfaden – erläutern und anwenden**

Einheit 0 (E0): **Willkommen, Zielsetzung und Ablauf**

**Dauer:** ~ 10 Min.

---

## Willkommen bei WissKI Bits: Ontologiebasierte Modellierung von Forschungsdaten

In [Modul 1: Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul1/de/M1E00_Ablauf-Zielsetzung.md#1) haben Sie eine konzeptuelle Modellskizze entwickelt und diese in [Modul 2: Modellieren mit CIDOC CRM – verstehen und anwenden](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/de/M2E00_Ablauf-Zielsetzung.md#1) formal mit CIDOC CRM und in Protégé umgesetzt.

In diesem **Modul 3: Vom Diagramm zu Pfaden – erläutern und anwenden** bereiten Sie dieses Modell für die Nutzung in WissKI vor. Sie überführen die formale Ontologiestruktur schrittweise in eine **technisch nutzbare Struktur aus semantischen Pfaden und Pfadgruppen**. Am Beispiel der Computerspielsammlung vervollständigen Sie ein semantisches Diagramm in Draw.io, transformieren dieses in eine WissKI-Pathbuilder-XML-Datei und untersuchen die importierten Pfade und Pfadgruppen in WissKI.

Anhand des Sammlungsobjektes **Zelda** untersuchen Sie, wie Klassen, Eigenschaften und deren Beziehungen als vollständige semantische Pfade in einem Diagramm dargestellt werden können.

> Worum geht es in dem Modul?
>
> In diesem Modul überführen Sie eine formale Ontologiestruktur in eine technisch nutzbare Pfadstruktur in WissKI.
> 
> Ontologie → Draw.io-Diagramm → Pathbuilder-XML → Pfade und Pfadgruppen in WissKI
>
> Sie lernen, wie ein semantisches Diagramm für die Transformation vorbereitet, die benötigte XML-Datei erzeugt und die importierte Pfadstruktur anhand des Ausgangsmodells überprüft werden kann.

---

## Leitfrage

Die Leitfrage, die uns durch dieses Modul begleitet, lautet:

> **Wie kann ein semantisches Datenmodell in eine valide und in WissKI nutzbare Struktur aus Pfaden und Pfadgruppen überführt werden?**

---

## Zielsetzung des Moduls

In diesem Modul lernen Sie, wie ausgewählte Teile der in Modul 2 formal umgesetzten Domänenontologie für die Nutzung in WissKI aufbereitet werden können.

Am Ende des Moduls sind Sie in der Lage,

- einen ausgewählten Modellausschnitt mithilfe von Draw.io nach vorgegebenen Modellierungsregeln zu visualisieren,
- die für die Konvertierung benötigte Diagrammstruktur und die zugehörigen Attributwerte anzuwenden,
- eine Draw.io-XML-Datei bereitzustellen und mithilfe des Webdienstes „Draw.io diagrams to WissKI pathbuilders“ in eine WissKI-Pathbuilder-XML-Datei zu transformieren,
- die benötigten Ontologien und die erzeugte Pfadstruktur in WissKI einzubinden sowie
- die importierten Pfade und Pfadgruppen zu analysieren und mit dem Ausgangsmodell abzugleichen.
- die erzeugten Bundles und Fields zu prüfen und erste Daten zum Beispielobjekt zu erfassen,
- den Zusammenhang zwischen semantischem Pfad, Eingabefeld und konkretem Datenwert an einem Beispiel zu erläutern.
 
---

## Ablauf des Moduls

**Gesamtdauer Modul 3: ca. 90 Min.**

| Einheit | Inhalt | Dauer |
|---|---|---:|
| M3E0 | [Willkommen, Zielsetzung und Ablauf](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/de/M3E0_Ablauf-Zielsetzung.md#1) | 10 Min. |
| M3EÜ1 | [Semantische Datenmodelle visualisieren](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/de/M3E%C3%9C1_Dom%C3%A4nenontologie-Diagramm.md#1) | 35 Min. |
| M3EÜ2 | [Transformation semantischer Modelle in WissKI-Pfade](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/de/M3E%C3%9C2_Drawio-to-WissKI-Paths.md#1) | 45 Min. |
|  | **Gesamt** | **90 Min.** |

---

## Lernziele des Moduls

Nach Abschluss von Modul 3 können die Teilnehmenden…

### EÜ1. Semantische Datenmodelle visualisieren

- Software zur Visualisierung einer Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0812)
- Software zur Visualisierung einer Domänenontologie erläutern. (LZ-ID SODa\_03\_007\_0813)
- Begriff Visualisierung erläutern. (LZ-ID SODa\_03\_007\_0851)
- Nutzen von Visualisierungen erläutern. (LZ-ID SODa\_03\_007\_0852)
- Nutzen einer Software zur Visualisierung einer Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0814) 
- unter Anleitung Software zur Visualisierung einer Domänenontologie anwenden. (LZ-ID SODa\_03\_007\_0815)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung benennen. (LZ-ID SODa\_03\_007\_0806)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0811)
- Regeln zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware benennen. (LZ-ID SODa\_03\_007\_0820)
- Regeln zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware anwenden. (LZ-ID SODa\_03\_007\_0816)
- Attributwerte an vordefinierten Klassen der Domänenontologie in einer Visualisierungssoftware anwenden. (LZ-ID SODa\_03\_007\_0817)

### EÜ2. Transformation semantischer Modelle in WissKI-Pfade

- WissKI Pathbuilder als Werkzeug zur Defintion einer Ontologiestruktur erläutern. (LZ-ID SODa\_03\_007\_0804)
- unter Anleitung die Datenkonvertierung einer Visualisierungssoftware in ein nachnutzbares Dateiformat anwenden. (LZ-ID SODa\_02\_005\_0298a)
- unter Anleitung WissKI Pathbuilder als Werkzeug zum Import einer domänenspezifischen Ontologiestruktur (Pathbuilder-XML-Datei im WissKI-Pathbuilder) anwenden. (LZ-ID SODa\_03\_007\_0818)
- unter Anleitung die importierte domänenspezifische Ontologiestruktur im WissKI-Pathbuilder analysieren. (LZ-ID SODa\_03\_007\_0819)
- ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung benennen. (LZ-ID SODa\_02\_005\_0317) 
- unter Anleitung ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung anwenden. (LZ-ID SODa\_02\_005\_0318)

---

## Lernweg im Modul

Ausgehend von der formalen Ontologiestruktur aus Modul 2 durchlaufen die Teilnehmenden folgende Schritte:

**Semantisches Datenmodell visualisieren (M3EÜ1):** 
Ausgewählte Klassen und Eigenschaften der Domänenontologie in einem strukturierten Draw.io-Diagramm darstellen.
 
↓

**Diagramm überprüfen (M3EÜ1):** 
Verbindungen und Attributwerte überprüfen, die für die Transformation benötigt werden. 

↓
  
**Pathbuilder-XML erzeugen (M3EÜ2):**
 Die Draw.io-XML-Datei in eine WissKI-Pathbuilder-XML-Datei transformieren. 

↓
 
**Ontologie und Pfadstruktur in WissKI einbinden (M3EÜ2):** 
Die benötigten Ontologien einbinden und die erzeugte Datei in den WissKI Pathbuilder importieren.

↓
   
**Pfade und Pfadgruppen analysieren (M3EÜ2):** 
Die importierte Pfadstruktur untersuchen und mit dem Ausgangsdiagramm vergleichen.

↓

**Eingabestrukturen prüfen und erste Daten erfassen (M3EÜ2):**
Die erzeugten Bundles und Fields prüfen, einen ersten Datensatz zum Beispielobjekt speichern und den Titelwert mit dem zugehörigen semantischen Pfad vergleichen.

↓

**Ergebnis:**
Ein ausgewählter Teil des semantischen Domänenmodells liegt als nutzbare Pfadstruktur in WissKI vor.

---

## Arbeitsweise und Beispiel

Das Modul verbindet kurze fachliche und methodische Inputs mit Demonstrationen und angeleiteten praktischen Übungen. Entscheidend ist eine nachvollziehbare und wiederholbare Verarbeitungskette vom semantischen Datenmodell zur Pfadstruktur in WissKI.

- Unser gemeinsames Beispiel ist weiterhin das Sammlungsobjekt **The Legend of Zelda: A Link to the Past** und das in den Modulen 1 und 2 entwickelte semantische Domänenmodell.
- Sie arbeiten mit einem vorbereiteten Draw.io-Diagramm, ergänzen fehlende Klassen und Eigenschaften und überprüfen die für die Transformation benötigten Verbindungen und Attributwerte.
- Anschließend transformieren Sie das Diagramm mithilfe des GNM Webservice **Draw.io diagrams to WissKI pathbuilders** und importieren die erzeugte Datei in WissKI.
- Abschließend vergleichen Sie die importierten Pfade und Pfadgruppen mit dem Ausgangsdiagramm und den fachlichen Informations- und Abfrageanforderungen.

---

## Voraussetzungen

Vorausgesetzt werden die Inhalte und Arbeitsergebnisse aus Modul 1 und Modul 2 oder vergleichbare Grundkenntnisse der semantischen Modellierung.

Die Teilnehmenden sollten…

- Konzepte, Ereignisse und Beziehungen einer Domäne identifizieren können,
- das Grundprinzip der ereigniszentrierten Modellierung mit CIDOC CRM verstanden haben,
- mit Klassen, Eigenschaften und Scope Notes des CIDOC CRM vertraut sein,
- wissen, wie domänenspezifische Konzepte als Subklassen bestehender CIDOC-CRM-Klassen modelliert werden können,
- sowie Zugriff auf die in Modul 2 [M2EÜ: Semantische Modellellierung mit CIDOC CRM](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul2/de/M2E%C3%9C_Modellieren-CIDOCCRM.md#1) entwickelte Ontologiestruktur oder die bereitgestellte Beispielontologie haben.

Vorkenntnisse im Umgang mit dem WissKI Pathbuilder sind nicht erforderlich. Seine grundlegenden Funktionen werden im Laufe des Moduls eingeführt.

> **Für die praktische Anwendung werden bereitgestellt:**
>
> - ein Computer mit Internetzugang,
> - Zugriff auf [diagrams.net (Draw.io)](https://app.diagrams.net/),
> - die vorbereitete [Draw.io-XML-Lücken-Diagramm](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_A.drawio.xml),
> - Zugriff auf den Konvertierungsdienst [Draw.io diagrams to WissKI pathbuilders](https://isl.ics.forth.gr/gnm_services),
> - Zugang zu einer WissKI-Instanz über den [SODa Semantic Co-Working Space (SCS)](https://manager.scs.sammlungen.io/de),
> - sowie die im Tutorial verwendete [Games Charcteristics Domänenontologie](https://games.m-e-g-a.org/ontology/game_characteristics/1.0/Game_characteristics_v1.0.3.rdf) und Referenzontologie [Erlangen CRM / OWL](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl).

---

## Ergebnis des Moduls

Am Ende von Modul 3 haben Sie den Workflow vom semantischen Datenmodell zu einer nutzbaren Pfadstruktur in WissKI durchlaufen.

> **Was nehmen Sie aus dem Modul mit?**
> 
> - ein nach den vorgegebenen Regeln vervollständigtes semantisches [Draw.io-Diagramm](../assets/GamesDrawioDiagramm.png),
> - eine exportierte [Draw.io-XML-Datei](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/WissKIBits.drawio.xml),
> - eine durch den Konvertierungsdienst "Draw.io diagrams to WissKI pathbuilders" erzeugte [WissKI-Pathbuilder-XML-Datei](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput_WissKIBits.xml),
> - eine in WissKI importierte Struktur aus Pfaden und Pfadgruppen,
> - sowie eine dokumentierte Prüfung der importierten Struktur anhand des Ausgangsmodells und ausgewählter fachlicher Abfragefragen.
> - geprüfte Bundles und Fields für die Datenerfassung,
> - einen ersten gespeicherten Datensatz zum Beispielobjekt.

Die importierte Pfadstruktur bildet die Grundlage für die Generierung von sogenannten Drupal-Bundles, -Feldern und -Dateneingabeformularen sowie für die anschließende Erfassung und Abfrage semantisch strukturierter graphenbasierter Forschungsdaten in WissKI.

---

## Ausblick

Mit Modul 3 wird der Lernweg von der konzeptuellen Modellskizze über die formale Ontologiestruktur bis zur technischen Implementierung ausgewählter Teile des semantischen Datenmodells fortgeführt.

In weiterführenden Arbeitsschritten können aus den importierten Pfaden und Pfadgruppen Dateneingabestrukturen in WissKI generiert und Beispieldaten anhand der ursprünglichen Forschungs- und Abfragefragen untersucht werden.

In weiterführenden Arbeitsschritten können Sie zusätzliche Konzepte und Pfade ergänzen, Eingabestrukturen anpassen und weitere Forschungs- und Sammlungsdaten erfassen. Die systematische Abfrage der Daten kann anschließend vertieft werden.

> **Wie geht es weiter?**
>
> In der nächsten Einheit [M3EÜ1: Semantische Datenmodelle visualisieren](https://liascript.github.io/course/?https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/de/M3E%C3%9C1_Dom%C3%A4nenontologie-Diagramm.md#1) lernen Sie, wie ausgewählte Teile einer Domänenontologie mithilfe von Draw.io visualisiert und für die anschließende Transformation vorbereitet werden können.

---

## Redaktionelle Hinweise

* Die Zeitplanung ist auf insgesamt 90 Minuten abgestimmt. Da beide Facheinheiten praktische Aufgaben enthalten, sollte die Dauer nach einem Testlauf überprüft werden.


