# WissKI Bits How-to-Tutorial

## Ontologiegestützte Modellierung von Forschungsdaten

**Datenmodell entwickeln und implementieren am Beispiel**

Die **WissKI Bits** sind ein modular aufgebautes **How-to-Tutorial zur ontologiegestützten Modellierung von Forschungsdaten mit WissKI**.

Anhand eines durchgängigen Anwendungsbeispiels aus dem Bereich **Computerspiele als Sammlungs- und Forschungsobjekte** wird schrittweise gezeigt, wie aus einer fachlichen Fragestellung ein semantisches Datenmodell entsteht und wie dieses mit **CIDOC CRM, Protégé, Draw.io und WissKI** praktisch umgesetzt werden kann.

Das Tutorial ist als **Open Educational Resource (OER)** konzipiert und kann zum Selbstlernen sowie in Lehr-, Schulungs- und Beratungskontexten eingesetzt und nachgenutzt werden.

> **Forschungsfrage → konzeptuelle Modellierung → CIDOC CRM → formale Ontologiemodellierung → Visualisierung → Transformation → WissKI Pathbuilder**

---

## Die drei Module

Das Tutorial besteht aus drei inhaltlich aufeinander aufbauenden Modulen. Sie bilden gemeinsam einen Lernpfad, können jedoch auch modular nachgenutzt werden.

### Modul 1: Grundlagen und konzeptuelle Modellierung

Im ersten Modul werden die Grundlagen der ontologiegestützten Modellierung erarbeitet. Ausgehend von einem Sammlungsobjekt und einer Forschungsfrage werden relevante Konzepte, Ereignisse und Beziehungen identifiziert, mit dem CIDOC CRM abgeglichen und in einer konzeptuellen Modellskizze strukturiert.

### Modul 2: Formale Modellierung mit CIDOC CRM und Protégé

Im zweiten Modul wird die konzeptuelle Modellskizze formalisiert. Mit Protégé werden Klassen (Entities) und Eigenschaften (Properties) des CIDOC CRM erkundet, geeignete Elemente ausgewählt und domänenspezifische Strukturen modelliert.

### Modul 3: Vom Diagramm zum WissKI Pathbuilder

Im dritten Modul wird das semantische Modell mit Draw.io visualisiert und für WissKI vorbereitet. Das Diagramm wird mithilfe des gnm-service in eine Pathbuilder-XML-Datei transformiert, in WissKI importiert und anschließend anhand der erzeugten Gruppen und semantischen Pfade untersucht.

---

## Lernansatz

Das Tutorial folgt einem **forschungsorientierten, handlungs- und problemorientierten Lernansatz**. Demonstratives Lernen, **Learning by Doing** und angeleitetes Modellieren verbinden fachliche Wissensvermittlung mit praktischer Anwendung.

Die Lernaktivitäten orientieren sich an der **[Lernzielmatrix zum Forschungsdatenmanagement (FDM)](https://zenodo.org/records/15025246)** und an **[TaDiRAH (Taxonomy of Digital Research Activities in the Humanities)](https://zenodo.org/records/20829481)**. Durch deren Verschränkung werden Lernziele mit konkreten Forschungsaktivitäten verbunden und zu einem kompetenzorientierten Lernpfad angeordnet.

Über die drei Module hinweg führt dieser Lernpfad schrittweise vom Verstehen und Analysieren fachlicher Zusammenhänge über die konzeptuelle und formale Modellierung bis zur praktischen Umsetzung eines Datenmodells in WissKI.

> **Orientieren → Erkunden → Modellieren → Anwenden → Prüfen → Reflektieren → Weiterführen**

---

## Voraussetzungen

Für die Bearbeitung des Tutorials sind **keine vertieften Vorkenntnisse in Ontologien oder WissKI erforderlich**. Grundlegende Kenntnisse im Umgang mit Forschungsdaten und digitalen Arbeitsumgebungen sind hilfreich.

Für die praktischen Übungen werden benötigt:

- ein eigener Laptop oder Computer mit Internetzugang
- ein aktueller Webbrowser
- Zugang zu einer WissKI-Instanz
- Protégé
- diagrams.net (Draw.io)

Grundlegende Konzepte wie Ontologien, Klassen (Entities), Eigenschaften (Properties), CIDOC CRM und WissKI werden im Verlauf des Tutorials eingeführt.

Für den vollständigen Lernpfad wird empfohlen, die drei Module in der vorgesehenen Reihenfolge zu bearbeiten.

---

## Sprachen

Das Tutorial wird in **deutscher und englischer Sprache** veröffentlicht.

- Dateien ohne Sprachsuffix enthalten die deutsche Originalfassung.
- Englische Übersetzungen sind mit dem Suffix `_en` gekennzeichnet.
- Die Kennungen der Module und Einheiten, beispielsweise `M1E1`, bleiben in beiden Sprachversionen identisch.

---

## Über das SODa-Projekt

Das **[SODa-Projekt](https://sammlungen.io/projekt)** stärkt Datenkompetenzen im Umgang mit wissenschaftlichen Sammlungen und Sammlungsdaten und unterstützt die Entwicklung nachhaltiger Forschungsdatenpraktiken und -infrastrukturen.

Mehr als 1.200 wissenschaftliche Sammlungen in Deutschland bilden eine wichtige Grundlage für:

- Forschung
- disziplinäre Weiterentwicklung
- akademische Lehre

Damit Sammlungen und ihre Forschungsdaten langfristig auffindbar, zugänglich, interoperabel und nachnutzbar bleiben, sind strukturierte Daten, geeignete Datenmodelle und nachhaltige Forschungsdateninfrastrukturen erforderlich.

Hier setzt **WissKI (Wissenschaftliche Kommunikationsinfrastruktur)** als auf semantischen Technologien und Ontologien basierende Forschungsdateninfrastruktur an.

---

## Über das Team

Das Tutorial wurde entwickelt von:

- **Dr. Canan Hastik**, Interessensgemeinschaft für Semantische Datenverarbeitung (IGSD e. V.)
- **Gudrun Schwenk**, Interessensgemeinschaft für Semantische Datenverarbeitung (IGSD e. V.)
- **Dr. Mark Fichtner**, Germanisches Nationalmuseum (GNM)

### Mitwirkung

Bei der Entwicklung des Transformationsworkflows unterstützte **Elias Tzortzakakis**, Foundation for Research and Technology – Hellas (FORTH).

Der eingesetzte **gnm-service** unterstützt die Transformation entsprechend vorbereiteter Draw.io-Diagramme in Pathbuilder-XML-Dateien für den WissKI Pathbuilder. Dadurch kann die grafische Modellierung als Ausgangspunkt für die weitere Konfiguration des Datenmodells in WissKI genutzt werden.

---

## Feedback und weitere Informationen

Vielen Dank für das Interesse an den **SODa WissKI Bits**.

Wir freuen uns über Feedback zum Tutorial. Rückmeldungen helfen uns, die Materialien weiterzuentwickeln und an die Anforderungen der Nutzer*innen anzupassen.

**Feedback zum Tutorial:**  ????

Weitere SODa-Selbstlernangebote finden Sie in der **[SODa Knowledge Base](https://sammlungen.io/kb/kb-suche?combine=&format%5B64%5D=64)**.

--- 

### Weitere Fragen?

Der **SODa Helpdesk** unterstützt bei Fragen zur Arbeit mit Daten in wissenschaftlichen Sammlungen sowie zu SODa-Selbstlernangeboten und Workshops.

**Kontakt:** [soda@sammlungen.io](mailto:soda@sammlungen.io)

---

## Zitiervorschlag

Hastik, Canan; Schwenk, Gudrun; Fichtner, Mark (2026): *SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten. Datenmodell entwickeln und implementieren am Beispiel.* Version 1.0.0. SODa – Sammlungen, Objekte, Datenkompetenzen. Zenodo. DOI: 10.5281/zenodo.22284468

---

## Lizenz

![CC BY 4.0 – Creative Commons](https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/cc-by.svg)

Sofern nicht anders angegeben, ist dieses Tutorial unter der Lizenz **Creative Commons Namensnennung 4.0 International (CC BY 4.0)** veröffentlicht.

**Version:** v1.0.0 

**Datum:** 2026-09-08  

**Repository:** https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial

**DOI:** 10.5281/zenodo.22284468

---

## Förderhinweis

Das Projekt **SODa – Sammlungen, Objekte, Datenkompetenzen** wird durch das Bundesministerium für Forschung, Technologie und Raumfahrt (BMFTR) und die Europäische Union – NextGenerationEU gefördert.

<p>
  <img
    src="https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/BMFTR_de_Web_RGB_gef_durch.jpg"
    alt="Gefördert durch: Bundesministerium für Forschung, Technologie und Raumfahrt"
    width="280"
  >
  &nbsp;&nbsp;&nbsp;
  <img
    src="https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/FinanziertVonDerEU.jpg"
    alt="Finanziert von der Europäischen Union"
    width="220"
  >
</p>

---

## Impressum

**SODa – Sammlungen, Objekte, Datenkompetenzen**  
https://sammlungen.io/

**Autor*innen:**

- Canan Hastik
- Gudrun Schwenk
- Mark Fichtner
