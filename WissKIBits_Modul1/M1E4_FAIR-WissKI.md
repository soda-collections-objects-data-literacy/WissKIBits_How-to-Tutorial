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

Einheit 4: **FAIR-Konformität mit WissKI**  

**Dauer:** ~  15 Min.

**Lernziele:**

Teilnehmende können...

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

- ereigniszentriertes Modellierungsprinzip mit CIDOC CRM benennen.
- Formale Beschreibungssprache RDF ...
---

## WissKI in Kürze

**WissKI** (Wissenschaftliche Kommunikationsinfrastruktur) ist (WissKIo.D.features):

- eine freie, quelloffene virtuelle Forschungsumgebung
- entwickelt für Kulturerbe- und Forschungsdaten
- basierend auf Semantic-Web-Technologien
- modular aufgebaut und standardorientiert.

## FAIR-Komformität von WissKI

WissKI ist **nicht nur** eine Sammlungsdatenbank.

Als **semantisches Datenmanagementsystem** unterstützt es Linked Open Data (LOD) und damit die FAIR-Prinzipien: **Findable, Accessible, Interoperable und Reusable** (WissKIo.D.features).

Einen Einstieg in LOD bietet das  [**5-Sterne-Modell** für offene Daten](https://5stardata.info/de/), das den Weg von digitalen Dokumenten zu vernetzten, maschinenlesbaren Daten beschreibt (Hausenblast2012lod).

Technologien wie [RDF](https://www.w3.org/RDF/) (RDF2014rdf) und die vom W3C standardisierte [**Web Ontology Language (OWL)**](https://www.w3.org/OWL/) (OWL2012owl) ermöglichen es, Wissen formal und maschinenlesbar darzustellen sowie Daten semantisch zu verknüpfen.

WissKI verwendet in der technischen Implementierung die **CIDOC CRM OWL-Ontologie ([Erlangen CRM](https://erlangen-crm.org))** als Grundlage, kann aber auch andere Ontologien einbinden, insofern sie in einem maschinenlesbaren Format vorliegen.   

So entstehen interoperable und nachnutzbare Wissensbestände. Ihre konkrete FAIR-Konformität hängt zusätzlich von der Modellierung, Lizenzierung und Bereitstellung ab.

---

## WissKI am GNM

WissKI wird u. a. am [**Germanischen Nationalmuseum (GNM)**](https://www.gnm.de/) in Nürnberg eingesetzt —

- dem größten kulturhistorischen Museum im deutschsprachigen Raum (GNMo.D.stakeholders)
- das Maßstäbe für digitale Forschungsinfrastrukturen setzt.
  
Die Webseite [**How to FAIR**](https://howtofair.dk/what-is-fair/) (Harm2022fair) erläutert die **FAIR-Prinzipien** und zeigt konkrete Handlungsfelder für ihre Umsetzung in Forschungsprojekten. (Reichert2025soda) 

![GNM](../assets/gnm.jpg)

>  **Abbildung:** [Überblicksseite der Forschungsprojekte Archiv am GNM](https://www.gnm.de/forschung/forschungsprojekte-archiv) (GNMo.D.research)

![GNM innen](../assets/gnm_2.JPG)

>  **Abbildung:** 

---

## WissKI und Drupal 

WissKI ist **keine eigenständige Software** sondern ein Set an Modulen, die das Content-Management-System **Drupal** semantisch erweitern.

![Drupal](../assets/drupal.JPG)

---

### Drupal stellt bereit …

- Benutzer- und Rollenverwaltung  
- Modulare Systemarchitektur (Framework)  
- Schnittstellen für Datenaustausch (REST/JSON)  
- Zugriffskontrolle und Rechtemanagement  
- Mehrsprachige Benutzeroberfläche  

---

### WissKI ergänzt …

- Ontologiebasierte Modellierung und semantische Datenstrukturierung  
- Pathbuilder, ein Werkzeug zur Definition semantischer Pfade  
- RDF-Triple-Store zur Speicherung der semantischen Daten  
- SPARQL-Endpunkt für Abfragen und Zugriff  
- Publikation als Linked Open Data (LOD)  

---

## Der WissKI Pathbuilder

Der **Pathbuilder** ist das **Herzstück von WissKI**.

<!--Die im Pathbuilder modellierten semantischen Strukturen werden in WissKI technisch als RDF-Wissensgraph gespeichert. Damit verbindet WissKI die nutzerfreundliche Modellierung mit den Standards des Semantic Web.-->

Der Pathbuilder definiert:

- **Gruppen** → semantische Entitäten, z.B. Objekt, Person, Ort, Ereignis
- **Pfade** → Beziehungen dieser Entitäten, z.B. Objekt → wurde geschaffen von → Person
- **Widgets** → automatisch generierte Eingabeformulare, deren Struktur aus der Semantik abgeleitet wird

So ist es möglich in WissKI **nicht mit Tabellen**, sondern mit **ontologiebasierten Strukturen** zu arbeiten. 

Gleichzeitig bleibt WissKI flexibel, ermöglicht semantische Konsistenz und ist in der Datenpflege bestmöglich nutzendenunterstützend.

![Pathbuilder](../assets/pathbuilder.jpg)

> **Abbildung:** Die Grafik veranschaulicht....

---

## Semantisches Modellieren auf *WissKI-Art*

In WissKI werden  **nicht nur Daten** gespeichert und erfasst, sondern **Bedeutung** modelliert.

Leitfrage:

> **Welche reale Beziehung besteht zwischen den Dingen?**

!?[Video](../assets/semanticModelling.mp4)
<video controls>
  <source src="https://raw.githubusercontent.com/soda-collections-objects-data-literacy/SODaHow-to-Tutorial/main/assets/semanticModelling.mp4" type="video/mp4">
</video>


- **Albrecht Dürer** → Person  
- wurde geboren in → **Nürnberg** (Ort)  
- zu → **einem bestimmten Zeitpunkt**  
- hatte eine Mutter → **Barbara Dürer** (Person)  
- schuf → **Selbstbildnis** (Objekt)
- **Entstehungszeitpunkt** in einer **Quelle** erwähnt
- während → **seiner künstlerischen Schaffensperiode**  
- in → **Nürnberg**

Diese semantischen Bedeutungsaussagen formen einen Wissensgraphen – also ein Netzwerk miteinander verknüpfter Informationen. 

Grundlage dafür ist das **ereigniszentrierte Modellierungsprinzip des CIDOC CRM**: 

Objekte werden nicht isoliert beschrieben, sondern über **Ereignisse** (z.B. Herstellung, Nutzung, Erwerb) und die daran beteiligten Akteur:innen, Orte und Zeiten in einen nachvollziehbaren Zusammenhang gesetzt.

Technisch basiert dieser Wissensgraph auf dem Resource Description Framework (RDF). Informationen werden dabei als sogenannte Tripel gespeichert:

- Subjekt – die beschriebene Ressource
- Prädikat – ihre Eigenschaft oder Beziehung
- Objekt – ein Wert oder eine weitere Ressource

Eine Aussage wie:

„Das Selbstbildnis wurde von Albrecht Dürer geschaffen“

wird so als einzelne, eindeutig referenzierbare Beziehung gespeichert. Viele solcher Aussagen verbinden sich zu einem gerichteten Graphen, der komplexe Zusammenhänge maschinenlesbar abbildet. Gemeinsam bilden diese Tripel den Wissensgraphen, den WissKI verwaltet.

Der WissKI Pathbuilder übersetzt dabei auf CIDOC CRM basierte ontologische Modelle direkt in solche RDF-Strukturen.

Pfadgruppen entsprechen dabei Entitäten, Pfade definieren Beziehungen und die daraus generierten Formulare erzeugen beim Erfassen automatisch konsistente Aussagen im Wissensgraphen.

---

## Relevanz von WissKI

WissKI...

- ermöglicht **wissensbasierte Modellierung** statt starrer Tabellenschemata
- stellt **Interoperabilität** durch etablierte Ontologien wie **CIDOC CRM** sicher
- unterstützt die **FAIR-Prinzipien**
- generiert **Eingabeformulare automatisch** auf Basis semantischer Pfade
- publiziert Daten als **Linked Open Data**
- bietet **leistungsfähige SPARQL-Abfragen**
- verbindet **konzeptionelle Klarheit** mit **technischer Umsetzung**.

---

## Die Semantik ist zentral für WissKI

- **CIDOC CRM** definiert Klassen (Entities) und Eigenschaften (Properties)
- **Semantische Pfade** übersetzen das Modell in eine nutzbare Datenstruktur  
- **Formulare** sichern konsistente Dateneingabe und reduzieren Interpretationsspielräume  
- **RDF-Wissensgraph** ermöglicht Austausch, Nachnutzung und LOD-Publikation  

Dadurch werden Sammlungsdaten nicht nur dokumentiert, sondern semantisch so strukturiert, dass sie langfristig verständlich, interoperabel und maschinenlesbar auswertbar sind.

---

## Ausblick

WissKI Wissenschaftliche Kommunikationsinfrastruktur
unterstützt die semantische Erzeugung und Verwaltung von Daten indem es 


---


## Bibliografie

[GNMo.D.stakeholders] Germanisches Nationalmuseum (o. D.). Akteure, Architektur, Abteilungen. https://www.gnm.de/museum

[GNMo.D.research] Germanisches Nationalmuseum (o. D.). Forschungsprojekte-Archiv. https://www.gnm.de/forschung/forschungsprojekte-archiv

[Hausenblast2012lod] Hausenblas, M. (2012, Januar 22). *5-star open data* (M. Findeisen, Übers.). https://5stardata.info/de/

[Harm2022fair] Harm Buss, M. C., Bayle Deutz, D., Flindt Holmstrand, K., Væring Larsen, A., & Vlachos E. (2022). *How to FAIR*. https://howtofair.dk/what-is-fair/

[OWL2012owl] OWL Working Group. (2012, Dezemberg 11). OWL - Web Ontology Language (OWL). World Wide Web Consortium. https://www.w3.org/OWL/

[RDF2014rdf] RDF Working Group. (2014, Februar 25). RDF - Resource Description Framework (RDF). World Wide Web Consortium. https://www.w3.org/RDF/

[Reichert2025soda] Reichert, R., & Hastik, C. (2025, August 7). *SODa Basiskurs zu Erschließung und Forschungsdatenmanagement in Universitätssammlungen. Modul 1*. Zenodo. https://doi.org/10.5281/zenodo.16761352

[WissKIo.D.features] WissKI (o. D.). Features. https://wiss-ki.eu/features



































