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

**Dauer:** ~ 15 Min.

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
- WissKI Pathbuilder als Werkzeug zur Definition einer Ontologiestruktur erläutern. (LZ-ID SODa\_03\_007\_0849)
- ereigniszentriertes Modellierungsprinzip mit CIDOC CRM am Beispiel erläutern. (LZ-ID SODa\_03\_007\_0850)
- Resource Description Framework (RDF) als Standard zur Beschreibung von Ressourcen benennen. (LZ-ID SODa\_03\_007\_0843)
- Nutzen der Wissenschaftlichen Kommunikationsinfrastruktur WissKI benennen (LZ-ID SODa\_01\_010\_0204)

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

Technologien wie [Ressource Description Framework (RDF)](https://www.w3.org/RDF/) (RDF2014rdf) und die vom W3C standardisierte [**Web Ontology Language (OWL)**](https://www.w3.org/OWL/) (W3C2001owl) ermöglichen es, Wissen formal und maschinenlesbar darzustellen sowie Daten semantisch zu verknüpfen.

WissKI verwendet in der technischen Grundlage das **[Erlangen CRM / OWL](https://erlangen-crm.org/current-version)** in der aktuellen Version (Schiemann2024crm), eine OWL-Implementierung der aktuellen Version des CIDOC Conceptual Reference Model (CIDOC CRM). (SIG2026cidoc)

WissKI kann aber auch andere Ontologien einbinden, insofern sie in einem maschinenlesbaren Format, z.B. RDF oder OWL, vorliegen.   

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

>  **Abbildung:** [Überblicksseite Sammlungen am GNM](https://www.gnm.de/sammlungen/ueberblick-sammlungen) (GNMo.D.collections)

---

## WissKI und Drupal 

WissKI ist **keine eigenständige Software** sondern ein Set an Modulen (knurg2025wisski), die das Content-Management-System [**Drupal**](https://new.drupal.org/) semantisch erweitern. (Drupal2024core)

![Drupal](../assets/drupal.JPG)

>  **Abbildung:** WissKI Integration in Drupal (Fichtner2023wisski, S.2)

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

> **Abbildung:** Pathbuilder in WissKI mit Pfadgruppen, Pfaden und Feldeinstellungen zur semantischen Modellierung der Domäne Computerspiele

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

## Informationen zu WissKI und WissKI Community (Stand: August 2026)

- **News, Informationen, WissKI-Dokumentation auf der WissKI Homepage:** https://wiss-ki.eu/de
  
- **Einführungen in WissKI Features:**
  - Youtube-Channel WissKIProjekt: https://www.youtube.com/@wisskiproject
  - Youtube-Channel WissKI: https://www.youtube.com/@wisski5763
 
- **WissKI Dokumentation**
  - WissKI Dokmentation mit Tutorial, How-To's, Guide'S und einem Glossar: https://project.pages.drupalcode.org/wisski/
  - WissKI Module Documention https://www.drupal.org/docs/extending-drupal/contributed-modules/contributed-module-documentation/wisski
    
- **News und Community:**
  - Mattermost: https://chat.wiss-ki.eu/wisski/channels/town-square
  - Mastodon: \@wisski@fedihum.org
  - Facebook: https://www.facebook.com/wisskiproject/
  - Webseite WissKICommunity der UB Heidelberg: https://sempub.ub.uni-heidelberg.de/wisski_projekte/de
    
- **WissKI Anwender\*innentreffen:** https://wiss-ki.eu/taxonomy/term/63
>  **Jährliche Zusammenkunft der WissKI-Community** am Germanischen Nationalmuseum Nürnberg (GNM), um gemeinsam über Projekte und Themen zu diskutieren, sich über aktuelle Entwicklungen zu informieren und gemeinsam **Lösungen für Herausforderungen rund um die Weiterentwicklung und Nutzung von WissKI** zu finden (WissKIo.D.events; WissKI2026wat).

---

## Ausblick

**WissKI** bietet eine technische Umgebung, in der semantische Datenmodelle umgesetzt und für die Arbeit mit Sammlungs- und Forschungsdaten nutzbar gemacht werden können. 

In der folgenden Einheit wird dieser **Modellierungsprozess anhand eines konkreten Beispiels praktisch nachvollzogen**. Ausgangspunkt ist ein **Beispielobjekt aus der Domäne Computerspiele**, das schrittweise semantisch modelliert wird. Dabei werden die bisher im Modul vorgestellten Schritte zusammengeführt: von der **konzeptuellen Wissensmodellierung** und der Entwicklung einer **Modellskizze** über die **formalisierte Darstellung** der relvanten Konzepte, Eigenschaften und Beziehungen mit **CIDOC CRM** bis hin zum daraus resultierenden **Domänenmodell** auf Grundlage des CIDOC CRM.

Die Praxiseinheit zeigt damit, wie ausgehend von einem konkreten Sammlungsobjekt eine formale semantische Modellierung entwickelt und anschließend in einen strukturierten Modellierungsansatz überführt werden kann.


---


## Bibliografie

[Drupal2024core] Drupal Association (2024) Drupal 11.4.5 Drupal Core. https://www.drupal.org/project/drupal/releases/11.4.5

[Fichtner2023wisski] Fichtner, M., Nasarek, R., & Wiesing, T. (2023). WissKI: A Virtual Research Environment Based on Drupal. *Proceedings of the Conference on Research Data Infrastructure* , 1. https://doi.org/10.52825/cordi.v1i.353

[GNMo.D.stakeholders] Germanisches Nationalmuseum (GNM) (o. D.). Akteure, Architektur, Abteilungen. https://www.gnm.de/museum

[GNMo.D.research] Germanisches Nationalmuseum (GNM) (o. D.). Forschungsprojekte-Archiv. https://www.gnm.de/forschung/forschungsprojekte-archiv

[GNMo.D.collections] Germanisches Nationalmuseum (GNM) (o. D.). Sammlungen. Von der Archäologie bis ins 20. Jahrhundert. https://www.gnm.de/sammlungen/ueberblick-sammlungen

[Hausenblas2012lod] Hausenblas, M. (2012, Januar 22). *5-star open data* (M. Findeisen, Übers.). https://5stardata.info/de/

[Harm2022fair] Harm Buss, M. C., Bayle Deutz, D., Flindt Holmstrand, K., Væring Larsen, A., & Vlachos E. (2022). How to FAIR. https://howtofair.dk/what-is-fair/

[knurg2025wisski] knurg (2025). Drupal Modul WissKI. https://www.drupal.org/project/wisski

[W3C2001owl] OWL Working Group. (2012, Dezemberg 11). OWL - Web Ontology Language (OWL). World Wide Web Consortium. https://www.w3.org/OWL/

[RDF2014rdf] RDF Working Group. (2014, Februar 25). RDF - Resource Description Framework (RDF). World Wide Web Consortium. https://www.w3.org/RDF/

[Reichert2025soda] Reichert, R., & Hastik, C. (2025, August 7). *SODa Basiskurs zu Erschließung und Forschungsdatenmanagement in Universitätssammlungen. Modul 1*. Zenodo. https://doi.org/10.5281/zenodo.16761352

[SIG2024cidoc] CIDOC CRM Special Interest Group. (2024). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. https://cidoc-crm.org/Version/version-7.1.3

[WissKIo.D.events] WissKI. (o. D.). WissKI Events. https://wiss-ki.eu/events

[WissKIo.D.features] WissKI. (o. D.). WissKI Features. https://wiss-ki.eu/features

[WissK2026wat] WissKI. (o. D.). WissKI WissKI Anwender*innentreffen (WAT). https://wiss-ki.eu/taxonomy/term/63




































