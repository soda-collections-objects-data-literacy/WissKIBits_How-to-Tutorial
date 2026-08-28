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


# SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 3: **Vom Diagramm zu Pfaden – Erläutern und anwenden**

Einheit 2: **Transformation semantischer Modelle mit gnm-service**  

**Dauer:** ~  Min.

**Lernziele:**

Teilnehmende können...

- WissKI Pathbuilder als Werkzeug zur Defintion einer Ontologiestruktur erläutern. (LZ-ID SODa\_03\_007\_0804)
- unter Anleitung die Datenkonvertierung einer Visualisierungssoftware in ein nachnutzbares Dateiformat anwenden. (LZ-ID SODa\_02\_005\_0298a)
- unter Anleitung WissKI Pathbuilder als Werkzeug zum Import einer domänenspezifischen Ontologiestruktur (Pathbuilder-XML-Datei im WissKI-Pathbuilder) anwenden. (LZ-ID SODa\_03\_007\_0818)
- unter Anleitung die importierte domänenspezifische Ontologiestruktur im WissKI-Pathbuilder analysieren. (LZ-ID SODa\_03\_007\_0819)
- ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung benennen. (LZ-ID SODa\_02\_005\_0317) 
- unter Anleitung ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung anwenden. (LZ-ID SODa\_02\_005\_0318)

---

## Von Ontologiebeziehungen zu WissKI-Pfaden

In dieser Einheit wird das zuvor erstellte Draw.io-Diagramm automatisch in semantische WissKI-Pfade überführt, die aus Klassenbeziehungen konstruiert und als Pathbuilder in WissKI importiert werden.

Damit wird das Domänenmodell erstmals als funktionale Ontologiestruktur in WissKI nutzbar.

---

## Der WissKI Pathbuilder

Der Pathbuilder bildet die **Implementierungsschicht von WissKI**.

Die Ontologiestruktur besteht in der Regel aus semantischen Beziehungsketten - also **Sequenzen aus Klassen und Beziehungen**. Diese werden im Pathbuilder zu **einem Pfad** und **Pfadgruppen**.

Diese **Pfade und Pfadgruppen definieren die interne Domänenontologie von WissKI** und steuern, wie Daten erfasst, gespeichert, verknüpft und abgefragt werden.

Mehrere **zusammengehörige Pfade werden zu Pfadgruppen organisiert**, die wiederum Klassen (Entities), z.B. Personen, Objekte, Ereignisse repräsentieren.

<table>
  <tr>
    <td><img src="../assets/pathbuilder.jpg" alt="WissKI Pathbuilder" width="75%"></td>
  </tr>
</table>

Die Pfade und Pfadgruppen im Pathbuilder werden in WissKI für folgende Zwecke genutzt werden:

* Aufbau und Verwaltung des RDF-Wissensgraphen,
* ontologiekonforme Datenspeicherung und -abfrage,
* Strukturierung der Dateneingabeformulare in Drupal.
  
---

## Aufgabe

**Arbeitsform:** Einzelarbeit 
**Material:** Laptop
**Zeit:** 20 Min.

Kurze Beschreibung der Aufgabe.

1.  "Draw.io diagrams to WissKI pathbuilders" Web Service öffnen 
2.  Beispiel-Draw.io .xml-Datei herunter laden
3.  Beispiel-Draw.io .xml-Datei in "Upload draw.io XML file for conversion to WissKI Pathbuilder XML:" hochladen
4.  Linkadresse von Beispiel output Pathbuilder-XML kopieren
5.  In WissKI einloggen
6.  Prüfen, ob in WissKI bereits die Domänenontologie geladen ist, siehe „Configuration/WissKI Ontology" dann Please select "Default WissKI Distillery Adapter“
6a. Wenn Domänenontologie nicht geladen ist, Games-Ontology Link-Adresse kopieren und einfügen und "Load Ontology" klicken
7.  Zu „Configuration/Pathbuilders“ navigieren
8.  Neuen Pathbuilder hinzufügen „Add Pathbuilder“, Name vergeben und speichern
9.  Unter „Pathbuilder Definition Import“ zuvor kopierte Linkadresse von Beispiel output Pathbuilder-XML einfügen und „Import“ klicken
10. Die erzeugten semantischen Pfade prüfen
11. Ergebnis: WissKI Pathbuilder auf Basis des eigenen Domänenmodells
12. Nächster Schritt: Dateneingabe-Formulare generieren in „Configuration/Pathbuilders“ dann "edit" dann "Save and generate bundles and fields" 

**Ressourcen**

* [Draw.io diagrams to WissKI pathbuilders Web Service](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/)
* [CIDOC CRM](http://erlangen-crm.org/240307/)
* [Games ontology](http://games.m-e-g-a.org/game_domain.rdf)
* [Beispiel output Pathbuilder-XML-Datei](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput.xml)

---

## Workflow vom Domänenontologie-Diagramm zu WissKI-Pfaden

Die folgende Übersicht zeigt die einzelnen Schritte, mit denen aus dem Diagramm ein nutzbarer WissKI Pathbuilder entsteht.

| Schritt | Aktion                                |
| -------- | ------------------------------------ |
| 1        | Draw.io-Modell als .xml-Datei exportieren.  |
| 2        | Draw.io.xml-Datei in WissKI Pathbuilder-Web Service laden. |
| 3        | Prüfen ob Ontologiestruktur valide ist. |
| 4        | WissKI Pathbuilder .xml-Datei generieren. |
| 5        | Pathbuilder .xml-Datei in WissKI importieren.   |
| 6        | Pfadstruktur prüfen. |

Dieser Prozess überbrückt die Lücke zwischen der Modellierung einer Domänenontologie und der Erstellung des Pathbuilders in WissKI, indem das semantische draw.io-Modell über eine Transformationspipeline automatisch in WissKI-Pfade umgewandelt wird.

---

##  Centre Cultural Informatics services page for the Germanisches Nationalmuseum

**Wie die Pipeline funktioniert**

Der [FORTH-ICS-Webdienst](https://isl.ics.forth.gr/gnm_services/):

* analysiert Draw.io-Diagramme über eine **JSON-Konfiguration**  
* erkennt **semantische Pfade** von einem **zentralen Ontologieklassen** aus  
* überprüft die **syntaktische Gültigkeit** anhand der Referenz-Ontologie 
* exportiert die Pfade als **WissKI Pathbuilder .xml-Datei**

**Vorteile der Draw.io → Pathbuilder-XML-Pipeline**

Diese Pipeline wandelt Draw.io-Diagramme basierend auf CIDOC CRM automatisch in eine WissKI Pathbuilder .xml-Datei um und bietet mehrere Vorteile:

* **Zeiteffizienz** – beseitigt den manuellen Konvertierungsaufwand  
* **Ontologie-Wiederverwendung** – nutzt vorhandene Ontologielogik  
* **Konsistenz** – gewährleistet eine einheitliche Struktur über Dateien hinweg  
* **Semantische Integrität** – bewahrt die ursprüngliche Bedeutung und Beziehungen
  
---

## Ausblick











