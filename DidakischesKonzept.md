# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

## Beschreibung

Das Tutorial **„WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten“** wurde entwickelt, um grundlegende und anwendungsbezogene Kompetenzen in der **semantischen Modellierung von Forschungsdaten** und deren Umsetzung mit der Wissenschaftlichen Kommunikationsinfrastruktur (WissKI) systematisch und praxisnah zu vermitteln. Im Mittelpunkt steht die Frage, wie fachliche Informationen und Forschungsfragen in ein nachvollziehbares, ontologiegestütztes Datenmodell überführt und für die strukturierte Erfassung von Forschungsdaten nutzbar gemacht werden können.

Das didaktische Konzept orientiert sich am **forschungsorientierten, handlungs- und problemorientierten Lernen**. Kurze Wissensimpulse werden mit angeleiteten Erkundungs-, Modellierungs- und Reflexionsphasen verbunden. Die Lernarchitektur greift dabei das **Ein- und Ausatem-Prinzip nach Klaus Döring** auf: Phasen der Wissensvermittlung und fachlichen Orientierung („Einatmen“) wechseln sich mit Phasen des selbstständigen Erkundens, Anwendens, Prüfens und Reflektierens („Ausatmen“) ab.[1]

Als durchgängiges Anwendungsbeispiel dient die Modellierung von **Computerspielen als Sammlungs- und Forschungsobjekte**. An diesem Beispiel durchlaufen die Lernenden schrittweise einen Modellierungsprozess von der fachlichen Fragestellung bis zur technischen Umsetzung. Dabei werden Modellierungsentscheidungen nicht nur nachvollzogen, sondern selbst getroffen, begründet und anhand bestehender Ontologien überprüft.

Das Tutorial umfasst **drei aufeinander aufbauende Module**. 

In **Modul 1** werden Grundlagen von Ontologien und semantischer Modellierung vermittelt, das CIDOC CRM eingeführt und fachliche Konzepte, Ereignisse und Beziehungen in einer konzeptuellen Modellskizze strukturiert. 

**Modul 2** führt diese Überlegungen in die formale Ontologiemodellierung über. Mit Protégé werden Klassen (Entities) und Eigenschaften (Properties) des CIDOC CRM erkundet, geeignete Elemente ausgewählt und domänenspezifische Strukturen modelliert. 

In **Modul 3** wird das semantische Modell visualisiert und für die Umsetzung in WissKI vorbereitet. Das Modell wird in Draw.io als Diagramm abgebildet, mit dem gnm-service in eine Pathbuilder-XML-Struktur transformiert und anschließend in den WissKI Pathbuilder importiert und untersucht.

Die praktische Arbeit mit **CIDOC CRM, Protégé, Draw.io, gnm-service und WissKI** verbindet dabei konzeptionelle, semantische und technische Perspektiven. Wiederkehrende Übungen, Quizfragen und Reflexionsimpulse unterstützen die Lernenden dabei, Modellierungsentscheidungen zu überprüfen und die Zusammenhänge zwischen den unterschiedlichen Repräsentationen des Datenmodells nachzuvollziehen.

Das Tutorial ist als **modulare, selbstgesteuerte Open Educational Resource (OER)** konzipiert. Die einzelnen Einheiten können im eigenen Lerntempo bearbeitet werden, bauen jedoch inhaltlich aufeinander auf. Arbeitsergebnisse aus vorausgehenden Einheiten werden in den folgenden Arbeitsschritten weiterverwendet. Dadurch entsteht ein durchgängiger Lernpfad:

> **Forschungsfrage und fachliche Domäne → konzeptuelle Modellierung → CIDOC CRM → formale Ontologiemodellierung → Visualisierung → Transformation → WissKI Pathbuilder**

Das Tutorial wird in **deutscher und englischer Sprache** bereitgestellt und unter einer **CC-BY-4.0-Lizenz** veröffentlicht. Durch seinen modularen Aufbau kann es sowohl zum Selbstlernen als auch in Lehr-, Schulungs- und Beratungskontexten eingesetzt, angepasst und weiterentwickelt werden.

---

## Themenbereiche und Themen

Das Tutorial behandelt zentrale Schritte der **ontologiegestützten Modellierung von Forschungsdaten** und deren praktische Umsetzung in WissKI. 

Die Inhalte sind auf drei aufeinander aufbauende Themenbereiche verteilt:

**Modul 1: Grundlagen und konzeptuelle Modellierung**

- Forschungsdaten und Forschungsfragen als Ausgangspunkt der Modellierung
- Grundlagen von Ontologien und semantischer Modellierung
- Konzepte, Ereignisse und Beziehungen
- Einführung in das CIDOC CRM
- Klassen (Entities) und Eigenschaften (Properties)
- Entwicklung einer konzeptuellen Modellskizze
- FAIR-Prinzipien und WissKI

**Modul 2: Formale Modellierung mit CIDOC CRM und Protégé**

- Methoden und Workflows der Ontologiemodellierung
- Einführung in Protégé
- Erkunden des CIDOC CRM
- Auswahl geeigneter Klassen und Properties
- Entwicklung domänenspezifischer Subklassen
- Formalisierung und Prüfung des Datenmodells
- Vorbereitung des Modells für die weitere Umsetzung in WissKI

**Modul 3: Vom semantischen Modell zum WissKI Pathbuilder**

- Visualisierung des semantischen Datenmodells mit Draw.io
- Modellierung von Knoten, Kanten und semantischen Pfaden
- Vorbereitung des Diagramms für die Transformation
- Transformation des Draw.io-Diagramms mit dem gnm-service
- Erzeugung einer Pathbuilder-XML-Datei
- Import in den WissKI Pathbuilder
- Untersuchung und Analyse von Gruppen und semantischen Pfaden

> **Konzeptuelle Modellierung → formale Ontologiemodellierung → Visualisierung → Transformation → WissKI Pathbuilder**

---

## Zielgruppe

Dieses Modul richtet sich an Personae der SODa Community, wie Professor\*innen, Sammlungskoordinator\*innen, -leitende und -betreuende und Forschende. [3]

## Lernansatz und Lernform

Das Tutorial folgt einem **forschungsorientierten, handlungs- und problemorientierten Lernansatz**. Im Mittelpunkt steht nicht die isolierte Vermittlung von Wissen über Ontologien und WissKI, sondern die schrittweise Bearbeitung einer konkreten Modellierungsaufgabe. Anhand eines durchgängigen Anwendungsbeispiels entwickeln die Lernenden ein ontologiegestütztes Datenmodell und überführen dieses schrittweise in eine für WissKI nutzbare Struktur.

Der didaktische Ansatz verbindet **demonstratives Lernen, Learning by Doing und angeleitetes Modellieren**. Neue Konzepte und Arbeitsschritte werden anhand konkreter Beispiele eingeführt, erkundet und anschließend von den Lernenden selbst angewendet. Theoretisches Verständnis, methodische Reflexion und praktische Handlungskompetenz werden so miteinander verknüpft.

Die Gestaltung der einzelnen Einheiten orientiert sich am Prinzip des **„Ein- und Ausatmens“ nach Klaus Döring** [1]. Kurze strukturierende Wissensimpulse („Einatmen“) wechseln sich mit Phasen des Erkundens, Modellierens, Anwendens, Prüfens und Reflektierens („Ausatmen“) ab. Übungen, Quizfragen und Reflexionsimpulse unterstützen die Lernenden dabei, ihr Verständnis zu überprüfen und Modellierungsentscheidungen zu begründen.

### Kompetenzorientierte Lernpfade

Die Konzeption des Tutorials verbindet die **Lernzielmatrix zum Forschungsdatenmanagement (FDM)** [2] mit der **TaDiRAH-Taxonomie (Taxonomy of Digital Research Activities in the Humanities)** [4]. Die Lernzielmatrix dient der Formulierung und Systematisierung konkreter Kompetenzen, während TaDiRAH die Lernaktivitäten mit Forschungsaktivitäten der Digital Humanities in Beziehung setzt.

Die Zuordnung erfolgt dabei nicht allein anhand einzelner Verben in den Lernzielformulierungen. Entscheidend ist die **semantische Interpretation des gesamten Lernziels im jeweiligen fachlichen und didaktischen Kontext**. Auf diese Weise können Lernziele mit den Forschungsaktivitäten verbunden werden, auf die der Lernprozess vorbereitet.

Über die drei Module hinweg entsteht ein **kompetenzorientierter Lernpfad**, der schrittweise von epistemischen zu operativen Forschungsaktivitäten führt: vom Verstehen und Analysieren fachlicher Zusammenhänge über das konzeptuelle und formale Modellieren bis zur praktischen Umsetzung des Datenmodells in WissKI.

Die drei Module bauen inhaltlich aufeinander auf, sind zugleich jedoch so gestaltet, dass sie als **modulare Lerneinheiten** nachgenutzt werden können. Ergebnisse vorausgehender Einheiten werden im vollständigen Lernpfad aufgegriffen und in den folgenden Arbeitsschritten weiterentwickelt.

Der Lernprozess folgt wiederkehrend dem Prinzip:

> **Orientieren → Erkunden → Modellieren → Anwenden → Prüfen → Reflektieren → Weiterführen**

Das Tutorial ist als **modulare, selbstgesteuerte Open Educational Resource (OER)** konzipiert. Die Verbindung von Lernzielen, Forschungsaktivitäten und praktischen Modellierungsaufgaben unterstützt sowohl den Aufbau fachlicher Orientierung als auch den Transfer in konkrete Forschungs- und Datenpraktiken.

---

## Themenbereiche und Themen 

---

## Voraussetzungen für das Tutorial

Für die Bearbeitung des Tutorials sind **keine vertieften Vorkenntnisse in Ontologien oder WissKI erforderlich**. Grundlegende Kenntnisse im Umgang mit Forschungsdaten und digitalen Arbeitsumgebungen sind hilfreich.

Für die praktischen Übungen werden benötigt:

- ein eigener Laptop oder Computer mit Internetzugang,
- ein aktueller Webbrowser,
- Zugang zu einer **WissKI-Instanz**,
- **Protégé** zur Bearbeitung und Erkundung von Ontologien,
- **diagrams.net (Draw.io)** zur Visualisierung semantischer Modelle.

Grundlegende Konzepte wie **Ontologien, Klassen (Entities), Eigenschaften (Properties), CIDOC CRM und WissKI** werden im Verlauf des Tutorials eingeführt und anhand eines durchgängigen Anwendungsbeispiels praktisch erarbeitet.

Die drei Module bauen aufeinander auf. Für den vollständigen Lernpfad wird daher empfohlen, sie **in der vorgesehenen Reihenfolge** zu bearbeiten.

---

## Einheiten und Zeitbedarf 

**Gesamtdauer Modul 1: ca. 90 Min.**

| Einheit | Inhalt | Dauer |
|---|---|---:|
| 0 | Willkommen, Zielsetzung und Ablauf | 5 Min. |
| 1 | Grundbegriffe konzeptueller Wissensmodellierung | 20 Min. |
| 2 | Grundlagen von Ontologien | 10 Min. |
| 3 | Einführung in CIDOC CRM | 15 Min. |
| 4 | FAIR-Konformität mit WissKI | 15 Min. |
| Ü1 | Anwendungsbeispiel Objektsammlungen: Modellskizze „Zelda“ | 30 Min. |
|  | **Gesamt** | **90 Min.** |

**Gesamtdauer Modul 2: ca. 90 Min.**

| Einheit | Inhalt | Dauer |
|---|---|---:|
| 0 | Willkommen, Zielsetzung und Ablauf | 10 Min. |
| 1 | Methoden und Workflows semantischer Modellierung | 5 Min. |
| 2 | Einführung in Protégé | 20 Min. |
| Ü1 | Semantische Modellierung mit CIDOC CRM | 55 Min. |
|  | **Gesamt** | **90 Min.** |

**Gesamtdauer Modul 3: ca. 90 Min.**

| Einheit | Inhalt | Dauer |
|---|---|---:|
| 0 | Willkommen, Zielsetzung und Ablauf | 10 Min. |
| Ü1 | Semantische Datenmodelle visualisieren | 35 Min. |
| Ü2 | Transformation semantischer Modelle in WissKI-Pfade | 40 Min. |
|  | **Gesamt** | **90 Min.** |

---

## Lernziele in Modul 1: **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären**

Nach Abschluss von Modul 1 können die Teilnehmenden…

**1. Grundbegriffe konzeptueller Wissensmodellierung**
   
- Begriff konzeptuelle Wissensmodellierung benennen. (LZ-ID SODa\_03\_007\_0847)
- Begriff konzeptuelle Wissensmodellierung erläutern. (LZ-ID SODa\_03\_007\_0848)
- Begriff Domäne benennen. (LZ-ID SODa\_03\_007\_0824)
- Begriff Konzept benennen. (LZ-ID SODa\_03\_007\_0821)
- Begriff Ereignis benennen. (LZ-ID SODa\_03\_007\_0822)
- Begriff Beziehung benennen. (LZ-ID SODa\_03\_007\_0823)
- Begriff semantische Modellierung benennen. (LZ-ID SODa\_03\_007\_0825)
- Begriff semantische Modellierung erläutern. (LZ-ID SODa\_03\_007\_0844)
- Begriff semantisches Datenmodell benennen. (LZ-ID SODa\_03\_007\_0845)
- Begriff semantisches Datenmodell erläutern. (LZ-ID SODa\_03\_007\_0846)

**2. Grundlagen von Ontologien**
   
- den Begriff Ontologie benennen. (LZ-ID SODa\_03\_007\_0826)
- den Begriff Ontologie erläutern. (LZ-ID 03\_007\_0775)
- Aspekte von Ontologien benennen. (LZ-ID 03\_007\_0776)
- Begriff Klassen (Classes/Concepts) benennen. (LZ-ID SODa\_03\_007\_0829)
- Begriff Klassen (Classes/Concepts) erläutern. (LZ-ID SODa\_03\_007\_0830)
- Begriff Instanzen (Instances) benennen. (LZ-ID SODa\_03\_007\_0833)
- Begriff Instanzen (Instances) erläutern. (LZ-ID SODa\_03\_007\_0834)
- Begriff Eigenschaften (Properties) benennen. (LZ-ID SODa\_03\_007\_0831)
- Begriff Eigenschaften (Properties) erläutern. (LZ-ID SODa\_03\_007\_0832)
- Begriff Modellannahmen (Constraints) benennen. (LZ-ID SODa\_03\_007\_0835)
- Begriff Modellannahmen (Constraints) erläutern. (LZ-ID SODa\_03\_007\_0836)

**3. Einführung in CIDOC CRM**

- Ontologie zur Beschreibung von Ressourcen bennen. (LZ-ID 03\_007\_0778)
- Ontologie zur Beschreibung von Ressourcen erläutern. (LZ-ID 03\_007\_0779)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung benenen. (LZ-ID SODa\_03\_007\_0806)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung erläutern. (LZ-ID SODa\_03\_007\_0807)
- Begriff Scope Notes benennen. (LZ-ID SODa\_03\_007\_0837)
- Begriff Scope Notes erläutern. (LZ-ID SODa\_03\_007\_0838)
- Resource Description Framework (RDF) als Standard zur Beschreibung von Ressourcen benennen. (LZ-ID SODa\_03\_007\_0843)
- den Begriff Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0827)
- den Begriff Domänenontologie erläutern. (LZ-ID SODa\_03\_007\_0828)
- Nutzen des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0805)
 
**4. FAIR-Konformität mit WissKI**

- für das sammlungsbezogene Forschungsdatenmanagement (FDM) relevante (inter-)nationale IT-Infrastrukturen erläutern. (LZ-ID SODa\_01\_010\_0203)
- geeignete Technologien zur Unterstützung der Anwendung der FAIR-Prinzipien benennen. (LZ-ID 01\_007\_0121)
- FAIR Prinzipien benennen. (LZ-ID 01\_007\_0117)
- das 5-Sterne-Modell für offene Daten benennen. (LZ-ID SODa\_01\_008\_0172)
- Formale Beschreibungssprache W3C Web Ontology Language (OWL) benennen. (LZ-ID SODa\_03\_007\_0842)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0841)
- die spezifischen Funktionen und Anwendungsbereiche der Wissenschaftlichen Kommunikationsinfrastruktur WissKI benennen. (LZ-ID SODa\_01\_010\_0191a)
- die spezifischen Funktionen und Anwendungsbereiche der Wissenschaftlichen Kommunikationsinfrastruktur WissKI erläutern. (LZ-ID SODa\_01\_010\_0192a)
- Leistungsfähigkeit und Effizienz von IT-Infrastrukturen für das sammlungsbezogene Forschungsdatenmanagement (FDM) mit der Wissenschaftlichen Kommunikationsinfrastuktur WissKI benennen. (LZ-ID SODa\_01\_010\_0202)
- WissKI Pathbuilder als Werkzeug zur Definition einer Ontologiestruktur bennenen. (LZ-ID SODa\_03\_007\_0803)
- WissKI Pathbuilder als Werkzeug zur Definition einer Ontologiestruktur erläutern. (LZ-ID SODa\_03\_007\_0849)
- ereigniszentriertes Modellierungsprinzip mit CIDOC CRM am Beispiel erläutern. (LZ-ID SODa\_03\_007\_0850)
- Resource Description Framework (RDF) als Standard zur Beschreibung von Ressourcen benennen. (LZ-ID SODa\_03\_007\_0843)
- Nutzen der Wissenschaftlichen Kommunikationsinfrastruktur WissKI benennen (LZ-ID SODa\_01\_010\_0204)

**Ü1. Anwendungsbeispiel Objektsammlungen**

- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0811)
- Datentyp-Eigenschaften des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0808)

---

## Lernziele in Modul 2: **Modellieren mit CIDOC CRM – verstehen und anwenden**

Nach Abschluss von Modul 2 können die Teilnehmenden…

**1. Methoden und Workflows semantischer Modellierung**

- Methoden zur Entwicklung von Ontologien benennen. (LZ-ID 03\_007\_0784)
- Methoden zur Entwicklung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0839)
- einen Workflow für die semantische Modellierung als Datendokumentation benennen. (LZ-ID SODa\_03\_001\_0626)
- einen Workflow für die semantische Modellierung als Datendokumentation erläutern. (LZ-ID SODa\_03\_001\_0853)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (SODa\_03\_007\_0784a)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM erläutern. (SODa\_03\_007\_0785a)

**2. Einführung in Protégé**

- Software zur Erstellung von Ontologien benennen. (LZ-ID SODa\_03\_007\_0809)
- Software zur Erstellung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0810)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0841)
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0840)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0784a)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM erläutern. (SODa\_03\_007\_0785a)

**Ü1. Semantische Modellierung mit CIDOC CRM**

- Ontologie zur Beschreibung von Ressourcen anwenden. (LZ-ID 03\_007\_0780)
- Methoden zur Entwicklung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0854)
- einen Workflow für die semantische Modellierung als Datendokumentation anwenden (LZ-ID SODa\_03\_001\_0627)
- unter Anleitung Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM anwenden. (LZ-ID SODa\_03\_001\_0786a) 
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa_03_007_0840)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM anwenden. (LZ-ID SODa_03_007_0855)
- Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa\_03\_007\_0780a)

---

## Lernziele in Modul 3: **Vom Diagramm zu Pfaden – erläutern und anwenden**

Nach Abschluss von Modul 3 können die Teilnehmenden…

**Ü1. Semantische Datenmodelle visualisieren**

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

**Ü2. Transformation semantischer Modelle in WissKI-Pfade**

- WissKI Pathbuilder als Werkzeug zur Defintion einer Ontologiestruktur erläutern. (LZ-ID SODa\_03\_007\_0804)
- unter Anleitung die Datenkonvertierung einer Visualisierungssoftware in ein nachnutzbares Dateiformat anwenden. (LZ-ID SODa\_02\_005\_0298a)
- unter Anleitung WissKI Pathbuilder als Werkzeug zum Import einer domänenspezifischen Ontologiestruktur (Pathbuilder-XML-Datei im WissKI-Pathbuilder) anwenden. (LZ-ID SODa\_03\_007\_0818)
- unter Anleitung die importierte domänenspezifische Ontologiestruktur im WissKI-Pathbuilder analysieren. (LZ-ID SODa\_03\_007\_0819)
- ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung benennen. (LZ-ID SODa\_02\_005\_0317) 
- unter Anleitung ein Werkzeug ("gnm-service: Draw.io diagrams to WissKI pathbuilders") zur Dateikonvertierung anwenden. (LZ-ID SODa\_02\_005\_0318)



## Quellenangaben

[1] Döring, K. W. (2009): Handbuch Lehren und Trainieren in der Weiterbildung. Beltz.

[2] Petersen, B., Altemeier, F., Boße, S., Dalby, M., Düvel, N., Engelhardt, C., Fichtner, M., Hastik, C., Haugwitz, J.-M., Jacob, J., Koch, K., Kuntz, A., Manske, A., Mühlichen, A., Murcia Serra, J., Ortmeyer, J., Richter, M., Schranzhofer, H., Slowig, B., … Zollitsch, L. (2025). Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) (Version 3). Zenodo. https://doi.org/10.5281/zenodo.15025246

[3] Reichert, R., Hastik, C., Gnyp, A., Markert, M., & Tharandt, L. (2025). SODa Personas. Zenodo. https://doi.org/10.5281/zenodo.15574575

[4] Hastik, C., & Schwenk, G. A. (2026). Die Verschränkung von Lernzielmatrix und TaDiRAH zur Entwicklung kompetenzorientierter Lernpfade [Graphic]. Zenodo. Scoping Workshop der VolkswagenStiftung "Zukunftskompetenzen Forschungsdatenmanagement gestalten: Anforderungen an Kompetenzen, Terminologien und Communitys für datengetriebene Wissenschaft", Schloss Herrenhausen, Hannover. https://doi.org/10.5281/zenodo.20829481


