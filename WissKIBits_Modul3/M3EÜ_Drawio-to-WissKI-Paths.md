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

## Ziel und Szenario

Dies ist eine Praxiseinheit. Ausgangspunkt ist das in den vorherigen Modulen 2 in Protégé entwickelte Modell der Domäne Computerspiele.

In dieser Einheit wird untersucht, wie aus einem semantischen Diagramm eine WissKI-Pathbuilder-Struktur entsteht.

Dazu wird ein Draw.io-Diagramm vervollstädnigt und mit dem Webservice „Draw.io diagrams to WissKI pathbuilders“ gegen die CIDOC CRM basierte Domänenontologie validiert sowie in eine Pathbuilder-XML-Datei transformiert. 

Diese Datei wird anschließend in WissKI importiert und auf ihre erzeugten Gruppen und semantischen Pfade überprüft.

Damit wird das Domänenmodell erstmals als funktionale Ontologiestruktur in WissKI nutzbar.


**Im Mittelpunkt steht der Workflow:**

> Diagramm vervollständigen und prüfen → transformieren → Ontologie in WissKI bereitstellen → Pathbuilder importieren → Pfade analysieren

---

## Ausgangspunkt vom semantischen Modell zum Pathbuilder

In Modul 2 wurde das Domänenmodell auf Grundlage von CIDOC CRM formalisiert. Für die weitere Implementierung liegt das Modell nun zusätzlich als **Draw.io-Lücken-Diagramm** vor.

**Beispiel:**

Eine Beziehung aus dem Modell kann folgendermaßen dargestellt sein:

> Computer Game → P102 has title → Game Title

Im WissKI Pathbuilder wird aus einer solchen Folge von Klassen (Entities) und Beziehungen (Properties) ein **semantischer Pfad**.

Dabei unterscheiden wir drei Ebenen:

| Ebene                         | Beispiel                                    |
| ----------------------------- | ------------------------------------------- |
| **Semantisches Modell**       | Computer Game – P102 has title – Game Title |
| **Transformationsformat**     | Draw.io-XML → Pathbuilder-XML               |
| **Implementierung in WissKI** | Gruppe und semantischer Pfad im Pathbuilder |

Der Pathbuilder bildet damit die Verbindung zwischen der Ontologiestruktur und den Datenstrukturen, die WissKI für Erfassung, Speicherung und Abfrage verwendet. Er organisiert das Modell in Gruppen und Pfaden und kann daraus Drupal-Bundles und -Felder erzeugen. (wisski2021pathbuilder)

---

## Fokus dieser Praxiseinheit

Der Fokus liegt auf fünf grundlegenden Arbeitsschritten:

- **Schritt 1: Ausgangsdiagramm vervollständigen und prüfen**

- **Schritt 2: Draw.io-XML in Pathbuilder-XML transformieren**

- **Schritt 3: Ontologie in WissKI prüfen bzw. laden**

- **Schritt 4: Pathbuilder anlegen und XML importieren**

- **Schritt 5: Erzeugte Gruppen und Pfade analysieren**

---

## Der WissKI Pathbuilder

Der Pathbuilder bildet die **Implementierungsschicht von WissKI**.

Der **WissKI Pathbuilder** verbindet die verwendete Ontologie mit der konkreten Datenstruktur in WissKI.

Semantische Beziehungsketten aus **Klassen (Entities) und Properties** werden dabei als **Pfade** abgebildet. Zusammengehörige Pfade können in **Gruppen** organisiert werden.

Ein Pathbuilder organisiert insbesondere

- **Pfade**, die Klassen und Properties als semantische Beziehungsketten abbilden,
- **Gruppen**, die zusammengehörige Pfade fachlich strukturieren,
- und die Zuordnung dieser Strukturen zu WissKI- beziehungsweise Drupal-Strukturen.

Auf dieser Grundlage können später **Bundles und Eingabefelder** für die Datenerfassung erzeugt werden.

> **Hinweis:** Der Pathbuilder definiert nicht die Ontologie selbst. Er verwendet Klassen und Properties der geladenen Ontologie, um die für WissKI benötigten Gruppen und semantischen Pfade festzulegen.

<table>
  <tr>
    <td><img src="../assets/pathbuilder.jpg" alt="WissKI Pathbuilder" width="75%"></td>
  </tr>
</table>

---

## Aufgabe

**Arbeitsform:** Einzelarbeit 

**Material:** Laptop, Draw.io-XML-Datei, Zugang zu einer WissKI-Instanz

**Zeit:** 20 Min.

Vervollständigt das vorbereitete semantische Draw.io-Diagramm, transformiert dieses in eine WissKI-Pathbuilder-XML-Datei, importiert diese in WissKI und überprüft die erzeugte Pfadstruktur.

**Workflow vom Domänenontologie-Diagramm zu WissKI-Pfaden**

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

### Schritt 1: Ausgangsdiagramm vervollstädigen und prüfen

**Ladet** das vorbereitete **Draw.io-Lücken-Diagramm** herunter: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/WissKIBits_Modul3/resources/Gruppe_A.drawio.xml oder WissKIBits_Modul3/resources/Gruppe_A.drawio.xml

**Öffnet** die vorbereitete Draw.io-Datei mit dem Domänenmodell in Draw.io: https://app.diagrams.net/ 

**Prüft**, ob

- die relevanten Klassen eindeutig benannt sind,
- die Beziehungen zwischen den Klassen eingetragen sind,
- die verwendeten Klassen und Properties zur geladenen Ontologie gehören,
- und die gewünschten Pfade vollständig als Klassen-Property-Klassen-Folgen dargestellt sind.

**Leitfragen:**

- Von welcher Klasse startet der Pfad?
- Über welche Property wird die nächste Klasse erreicht?
- Welche Klasse bildet das Ziel?
- Entspricht die Beziehung dem Modell aus Modul 2?

**Hinweis:** 

> Die Transformation kann nur Strukturen verarbeiten, die im Ausgangsdiagramm eindeutig und konsistent dargestellt sind.

---

### Schritt 2: Draw.io-Diagramm transformieren

**Öffnet** den Webservice:

[**Draw.io diagrams to WissKI pathbuilders**](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/)

Geht wie folgt vor:

- Exportiert oder verwendet die vorbereitete **Draw.io-XML-Datei**.
- Ladet die Datei unter **Upload draw.io XML file for conversion to WissKI Pathbuilder XML** hoch.
- Startet die Transformation.
- Prüft die Rückmeldung des Webservices.
- Öffnet oder kopiert die Adresse der erzeugten **Pathbuilder-XML-Datei**.

**Hinweis:**

> Die Transformation bildet damit den technischen Zwischenschritt:

> Draw.io XML → Webservice:Draw.io diagrams to WissKI pathbuilders → WissKI Pathbuilder XML


**Impulsfrage**

> Welche Informationen aus dem Diagramm müssen erhalten bleiben, damit daraus ein semantisch sinnvoller Pathbuilder erzeugt werden kann?

Notiert eine kurze Antwort.

---

### Schritt 3: Ontologie in WissKI prüfen

Die im Pathbuilder verwendeten Klassen und Properties müssen für WissKI über die Ontologie verfügbar sein. Der Pathbuilder verwendet diese Elemente zur Konstruktion semantischer Pfade.

**Loggt** euch in die vorbereitete **WissKI-Instanz** ein. 

**Prüft** zunächst, ob die für das Domänenmodell benötigte Ontologie bereits verfügbar ist: 

- Navigiert zu **WissKI → Configuration → WissKI Ontology**
- Prüft den verwendeten Adapter und die geladene Ontologie
- Falls die Domänenontologie noch nicht geladen wurde, wählt den vorgesehenen WissKI-Adapter aus, fügt die Adresse der **Games Ontology** ein, ladet die Ontologie.

**Games Ontology:**

[http://games.m-e-g-a.org/game_domain.rdf](http://games.m-e-g-a.org/game_domain.rdf)


**Hinweis:**

> Sofern im Tutorial keine WissKI-Instanzen zur Verfügung gestellt werden, kann für das Tutorial eine bereitgestellte WissKI-Umgebung im SODa Semantic Co-Working Space (SCS) genutzt werden.
>
> Die Nutzung ist kostenlos.
>
> Hierfür bitte kostenlos registrieren: https://manager.scs.sammlungen.io/user/register
>
> Nach der Freischaltung deines Kontos kannst du dich im SCS anmelden und auf die für das Tutorial benötigte WissKI-Umgebung zugreifen.
>
> Du musst für das Tutorial keine eigene WissKI-Installation einrichten. Der SCS stellt dir die benötigte technische Umgebung bereit.

---

### Schritt 4: Neuen Pathbuilder anlegen und XML importieren

**Navigiert** zu: **Configuration → Pathbuilders**

**Legt** einen neuen Pathbuilder an:

- wählt **Add Pathbuilder**,
- vergebt einen eindeutigen Namen,
- wählt den vorgesehenen Adapter,
- speichert den Pathbuilder.

**Öffnet** anschließend den neu angelegten Pathbuilder.

Im Bereich **Pathbuilder Definition Import**:

- fügt die zuvor kopierte Adresse der erzeugten Pathbuilder-XML-Datei ein,
- startet den Import,
- wartet, bis die Pathbuilder-Struktur angezeigt wird.

**Hinweis:** 

> Prüft die importierte Struktur zunächst, bevor weitere Bundles oder Felder generiert werden.

--- 

### Schritt 5: Importierte Pfadstruktur analysieren

**Untersucht** nun den erzeugten Pathbuilder und prüft insbesondere:

- Welche **Gruppen** wurden erzeugt?
- Welche **Pfade** befinden sich innerhalb der Gruppen?
- Welche Klasse bildet jeweils den Ausgangspunkt?
- Welche Properties verbinden die Klassen?
- Entsprechen die erzeugten Pfade dem Ausgangsdiagramm?
- Sind alle erwarteten Beziehungen vorhanden?
- Gibt es unerwartete oder fehlende Pfade?

#### Quiz: Untersuche den erzeugten Pathbuilder

Untersucht nun den erzeugten **Pathbuilder** und vergleicht ihn mit dem Ausgangsdiagramm.

**Frage 1. Zu welcher Gruppe gehört der folgende Beispielpfad?**

`Computer_Game → P102 has title → Game_Title`

[(X)] Computer Game
[( )] Game Title
[( )] Property
[( )] Der Pfad gehört zu keiner Gruppe.

---

**Frage 2. Welche Klasse bildet den Ausgangspunkt des Pfades?**

`Computer_Game → P102 has title → Game_Title`

[[Computer_Game]]

---

**Frage 3. Welche Property verbindet die beiden Klassen?**

`Computer_Game → P102 has title → Game_Title`

[[P102 has title]]

---

**Frage 4. Welche Zielklasse wird über die Property erreicht?**

`Computer_Game → P102 has title → Game_Title`

[[Game_Title]]

---

**Frage 5. Entspricht dieser Pfad dem Ausgangsdiagramm?**

[(X)] Ja
[( )] Nein

[[?]]
Vergleicht die Reihenfolge von Ausgangsklasse, Property und Zielklasse mit dem Diagramm.

---

**Frage 6. Warum entspricht der Pfad dem Ausgangsdiagramm?**

[[Die Klassen-Property-Klassen-Folge wurde vollständig übernommen.]]

[[?]]
Prüft, ob Ausgangsklasse, Property und Zielklasse in derselben Beziehung auch im Ausgangsdiagramm vorkommen.

---

### Abschlusscheck

**Diskutiert** anschließend den gesamten Pathbuilder:

- Welche **Gruppen** wurden erzeugt?
- Welche **Pfade** befinden sich innerhalb der Gruppen?
- Sind alle erwarteten Beziehungen vorhanden?
- Gibt es **unerwartete oder fehlende Pfade**?
- Entsprechen die erzeugten Pfade insgesamt dem Ausgangsdiagramm?

---

### Schritt 6: Transformation nachvollziehen

Vergleicht nun die drei Repräsentationen miteinander:

| Ebene | Darstellung |
|---|---|
| **Draw.io-Diagramm** | Computer Game → P102 has title → Game Title |
| **Pathbuilder-XML** | maschinenlesbare Transformationsstruktur |
| **WissKI Pathbuilder** | Gruppe und semantischer Pfad |

**Leitfragen:**

- Welche Informationen bleiben über alle drei Ebenen hinweg erhalten?
- Welche Informationen werden durch die Transformation technisch umgeformt?
- Wo wäre ein Fehler im Diagramm später im Pathbuilder sichtbar?
- Welche Vorteile hat die automatische Transformation gegenüber dem manuellen Aufbau einzelner Pfade?

---

## Der gnm-service als Transformationswerkzeug

Der Webservice **„Draw.io diagrams to WissKI pathbuilders“** unterstützt die Überführung eines semantischen Draw.io-Diagramms in eine **WissKI Pathbuilder-XML-Datei**.

Damit bildet der Dienst eine technische Schnittstelle zwischen der grafischen Modellierung und der Implementierung des Modells im WissKI Pathbuilder.

Der grundlegende Transformationsprozess lautet:

**Draw.io-Diagramm → Draw.io-XML → gnm-service → Pathbuilder-XML → WissKI Pathbuilder**

Die Transformation ermöglicht:

- die **Nachnutzung** des bereits entwickelten semantischen Modells,
- die **Reduktion manueller Übertragungsarbeit**,
- und eine nachvollziehbare Verbindung zwischen Diagramm und Pathbuilder.

**Hinweis:** 

> Die automatische Transformation ersetzt nicht die fachliche Prüfung. Die erzeugten Gruppen und Pfade sollten nach dem Import mit dem Ausgangsdiagramm verglichen werden.

---

## Ergebnis

Am Ende dieser Übung liegt ein **importierter WissKI Pathbuilder auf Grundlage des semantischen Domänenmodells** vor.

Ihr habt

- ein Draw.io-Diagramm als Ausgangsmodell geprüft,
- den **gnm-service** als Werkzeug zur Dateikonvertierung angewendet,
- aus dem Diagramm eine **Pathbuilder-XML-Datei** erzeugt,
- die benötigte Ontologie in WissKI überprüft beziehungsweise geladen,
- einen neuen Pathbuilder angelegt,
- die erzeugte XML-Struktur importiert,
- und mindestens einen semantischen Pfad mit dem Ausgangsdiagramm verglichen.

Das Ergebnis zeigt exemplarisch den Übergang:

> **semantisches Modell → Diagramm → Pathbuilder-XML → WissKI Pathbuilder**

---

## Zusammenfassung

In dieser Praxiseinheit wurde ein semantisches Draw.io-Diagramm schrittweise in eine **WissKI-Pathbuilder-Struktur** überführt.

Dabei kamen drei Werkzeuge beziehungsweise Repräsentationen zum Einsatz:

| Werkzeug / Repräsentation | Funktion |
|---|---|
| **Draw.io-Diagramm** | Visualisierung des semantischen Domänenmodells |
| **gnm-service** | Transformation des Diagramms in eine Pathbuilder-XML-Datei |
| **WissKI Pathbuilder** | Umsetzung der Ontologiebeziehungen als Gruppen und semantische Pfade |

Als Ergebnis liegt ein **importierter und geprüfter WissKI Pathbuilder** auf Grundlage des semantischen Domänenmodells vor.

Damit wurde der Übergang von der semantischen Modellierung zur technischen Umsetzung in WissKI nachvollzogen:

> **semantisches Modell → Draw.io-Diagramm → Pathbuilder-XML → WissKI Pathbuilder**

---

## Ausblick

Im nächsten Schritt werden die importierten Gruppen und Pfade für die **Dateneingabe in WissKI** nutzbar gemacht.

Dazu wird der Pathbuilder weiter konfiguriert und anschließend die Funktion

> **Save and generate bundles and fields**

verwendet.

Aus den semantischen Pfaden entstehen damit **Bundles und Felder**, die für die Dateneingabe und Darstellung in WissKI genutzt werden können.

> **Ontologie → Pathbuilder → Bundles und Felder → Datenerfassung**

---

## Ressourcen

- [Draw.io diagrams to WissKI pathbuilders](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/)
- [Erlangen CRM](http://erlangen-crm.org/240307/)
- [Games Ontology](http://games.m-e-g-a.org/game_domain.rdf)
- [Beispiel Pathbuilder-XML](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput.xml)
- [WissKI Pathbuilder Dokumentation](https://wiss-ki.eu/documentation/data-modeling/pathbuilder)

---

## Bibliografie

[wisski2012pathbuilder] https://wiss-ki.eu/documentation/data-modeling/pathbuilder?utm_source=chatgpt.com








