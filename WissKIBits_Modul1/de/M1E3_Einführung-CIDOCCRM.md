<!--

author: Canan Hastik (0000-0003-1729-4642)

author: Gudrun Schwenk (0009-0002-3156-8339)

email: info@igsd-ev.de

version:  v1.0.0

language: de

icon: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg

link: https://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css

license: CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>

comment: Dieses Modul ist Teil des How-to-Tutorials „Ontologiegestützte Modellierung von Forschungsdaten“. Das Tutorial vermittelt am Beispiel einer Computerspielsammlung schrittweise die Entwicklung eines semantischen Datenmodells auf Grundlage des CIDOC CRM und dessen Umsetzung mit WissKI.

title: WissKI Bits Ontologiegestützte Modellierung von Forschungsdaten

module: Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären

einheit: Einführung in CIDOC CRM

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-10-05

LearningResourceType: SODa How-to-Tutorial

-->

# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul (M1): **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären**

Einheit (E3): **Einführung in CIDOC CRM**  

**Dauer:** ~ 15 Min.

**Lernziele:**

Teilnehmende können...

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

---

## Was ist CIDOC CRM?

**Kurz gesagt:**

CIDOC CRM bietet einen **gemeinsamen konzeptuellen Rahmen**, um Informationen zum kulturellen Erbe **verständlich und interoperabel** zu beschreiben.

> **CIDOC CRM**
>
> … ist eine ISO-zertifizierte Ontologie (ISO 21127), die für die Dokumentation und Integration von Kulturerbeinformationen entwickelt wurde.
>
> Sie bietet einen gemeinsamen konzeptuellen Rahmen zur Beschreibung von:
>
> **Objekten · Akteur:innen · Ereignissen · Orten · Zeiträumen · Beziehungen**
>
> Ziel ist es, Informationen zum kulturellen Erbe explizit, verständlich und über verschiedene Sammlungen und Systeme hinweg interoperabel zu machen.
>
> **Wichtig:** CIDOC CRM definiert ein konzeptuelles Modell. Für technische Anwendungen werden maschinenlesbare Implementierungen des Modells verwendet, beispielsweise OWL-Repräsentationen.

[CIDOC CRM](https://cidoc-crm.org/) ist eine **ISO-zertifizierte Ontologie (ISO 21127)**, die vom **CIDOC-Komitee des ICOM (International Council of Museums)** entwickelt wurde.

Es handelt sich **nicht um einen technischen Implementierungsstandard**, sondern um ein **konzeptuelles Referenzmodell, das in einem Dokument spezifiziert ist** ([Release Version 7.1.3, Stand Februar 2024](https://cidoc-crm.org/get-last-official-release)). CIDOC CRM wurde speziell für die **Dokumentation des kulturellen Erbes** entwickelt.

Es ist eine **formale Repräsentation** grundlegender Konzepte, Begriffe und ihrer Beziehungen im Bereich des kulturellen Erbes.

Es dient als **theoretisches und praktisches Werkzeug**, um **evidenzbasierte Phänomene** im Bereich des kulturellen Erbes zu strukturieren, darzustellen und zu verstehen (CIDOC, 2024a, S. 9).

CIDOC CRM umfasst:

- Ereignisse
- Personen
- Objekte
- Orte
- Zeiträume
- und deren semantische Beziehungen

---

## Inhalte und Prinzipien des CIDOC CRM

CIDOC CRM bietet einen **konzeptuellen Rahmen**, um Informationen zum kulturellen Erbe sowie die Beziehungen zwischen Personen, Objekten, Orten, Zeiten und Aktivitäten zu beschreiben.

Ein wesentliches Merkmal von CIDOC CRM ist sein **ereigniszentrierter Ansatz** (CIDOC, 2024a, S. 33). Statt ein Objekt ausschließlich anhand einer Liste von Eigenschaften zu beschreiben, ermöglicht das Modell, **Ereignisse und Aktivitäten im Zusammenhang mit dem Objekt** abzubilden, beispielsweise seine Herstellung, Veränderung oder die Übertragung des Gewahrsams.

So können Informationen über die Herstellung eines physischen Spieleexemplars beispielsweise ein Herstellungsereignis, beteiligte Akteur:innen und einen Zeitraum umfassen.

CIDOC CRM definiert **Klassen und Properties**, um solche Beziehungen auszudrücken. In einer maschinenlesbaren Implementierung können diese Beziehungen beispielsweise mithilfe von RDF als Aussagen dargestellt werden.

**Die Unterscheidung ist wichtig:**

- Die ereigniszentrierte Modellierung beschreibt, wie Informationen konzeptuell organisiert werden.
- RDF beschreibt eine Möglichkeit, diese Informationen technisch darzustellen.

---

## CIDOC CRM kennenlernen

Das CIDOC CRM beschreibt nicht nur Klassen und Properties, sondern erläutert auch **Aufbau, Modellierungsprinzipien und konzeptionelle Grundlagen** des Modells. Für die praktische Arbeit mit dem CIDOC CRM ist es daher hilfreich, sich zunächst mit seiner grundlegenden Struktur vertraut zu machen.

Die offizielle Dokumentation bietet dazu einen umfassenden Einstieg:

![CIDOC CRM Table of Contents](../WissKIBits_Modul1/assets/M1E3_CIDOC_TableofContents.png)

> **Abbildung:** Ausschnitt aus dem Inhaltsverzeichnis des CIDOC CRM, [Release Version 7.1.3, Stand Februar 2024](https://cidoc-crm.org/get-last-official-release) (CIDOC, 2024a, S. 3).

---

## Klassen und Properties erkunden

Für die praktische Modellierung ist es wichtig, die **Klassen und Properties des CIDOC CRM** kennenzulernen. Dafür können neben der offiziellen Dokumentation folgende webbasierte Ressourcen genutzt werden:

- **[CIDOC CRM – Classes & Properties](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html#E41)**  
  Die offizielle Darstellung der **Version 7.1.3** dient als Referenz zum gezielten Nachschlagen. Sie enthält Definitionen und Scope Notes sowie Informationen zu Klassenhierarchien und Properties.

- **[CIDOC CRM Periodic Table](https://remogrillo.github.io/cidoc-crm_periodic_table/?code=E1)**  
  Die interaktive Darstellung bietet einen **visuellen und explorativen Zugang** zu Klassen, Properties und ihren Zusammenhängen.

> **Hinweis:** Die CIDOC CRM Periodic Table basiert auf **CIDOC CRM 7.1** und entspricht damit nicht vollständig der hier verwendeten Version **7.1.3**.
>
> Nutzt sie daher zur Orientierung und zum Erkunden des Modells. Für die genaue Definition und Verwendung von Klassen und Properties ist die offizielle Dokumentation der Version 7.1.3 maßgeblich.

---

## Zentrale Konzepte in CIDOC CRM

| Konzept | Beispielklasse (Entity) | Bedeutung |
|---|---|---|
| Ding | **E70 Thing** | Physisches oder immaterielles Objekt |
| Physisches Objekt | **E22 Human-Made Object** | Artefakt, Exponat, Sammlungsobjekt |
| Akteur | **E21 Person**, **E74 Group** | Individuum oder Organisation |
| Ereignis | **E5 Event** | Eine Handlung oder Veränderung |
| Ort | **E53 Place** | Räumlicher Kontext |
| Zeit | **E52 Time-Span** | Zeitlicher Rahmen |

> **Quelle:** [Release Version 7.1.3, Stand Februar 2024](https://cidoc-crm.org/get-last-official-release)

> **Zentrale Klassen**
>
> CIDOC CRM stellt allgemeine Klassen bereit, um die zentralen Elemente von Kulturerbeinformationen zu beschreiben: **Dinge, Objekte, Akteur:innen, Ereignisse, Orte und Zeiträume**.

---

## Klassenhierarchie und Scope Notes

Die **Scope Note** einer CIDOC CRM-Klasse legt fest:

- **Was sie ausdrückt**
- **Welche Bedeutung und Grenzen sie hat**
- **Wann sie verwendet werden sollte**

**Achtung: Nicht entscheidend sind:**

- der Name der Klasse (Entity),
- ihre hierarchische Position,
- oder intuitive Assoziationen.

**Scope Notes sind maßgeblich für die korrekte Modellierung.**

> **Scope Notes unterstützen Modellierungsentscheidungen**
>
> Eine Scope Note erläutert die beabsichtigte Bedeutung und Verwendung einer CIDOC CRM-Klasse oder -Property.
>
> Sie hilft bei der Beantwortung folgender Fragen:
>
> - Was drückt dieses Element aus?
> - Wo liegen seine semantischen Grenzen?
> - Wann sollte es verwendet werden?
>
> **Grundprinzip:** Wählen Sie eine Klasse oder Property nicht allein aufgrund ihres Namens aus.
>
> Prüfen Sie stets die zugehörige **Scope Note**, um festzustellen, ob sie die beabsichtigte Bedeutung ausdrückt.

---

### Beispiel E39 Actor

![Beispiel E39 Actor](../WissKIBits_Modul1/assets/E39Actor.jpg)

> **Abbildung:** Die Abbildung veranschaulicht den Aufbau einer Klassenbeschreibung anhand von „E39 Actor“ in CIDOC CRM (CIDOC, 2024a, S. 83).

---

## Eine CIDOC-CRM-Klasse auswählen

> Ein Begriff aus einer Domäne und eine CIDOC-CRM-Klasse können ähnliche Bezeichnungen haben, ohne dass sie dieselbe Art von Entität beschreiben.
>
> Bevor Sie eine Klasse auswählen, fragen Sie:
>
> - Worauf bezieht sich der Begriff in unserem Sammlungskontext?
> - Bezeichnet er ein Objekt, ein Informationsobjekt, eine:n Akteur:in, ein Ereignis, eine Bezeichnung oder einen Typ?
> - Entspricht die Scope Note der vorgeschlagenen CIDOC-CRM-Klasse dieser Bedeutung?
> - Welche Beziehungen müssten mithilfe dieser Klasse ausgedrückt werden?
>
> Ziel ist es nicht, eine Klasse mit einer passenden Bezeichnung zu finden, sondern eine Klasse auszuwählen, deren Definition die beabsichtigte Modellierungsaussage unterstützt.

---

## Bedeutung ausdrücken mit CIDOC CRM

CIDOC CRM ist **ereigniszentriert**, d. h., es beschreibt nicht nur, *was etwas ist*, sondern **was mit ihm passiert** (CIDOC, 2024a, S. 33).

Aussagen über Ressourcen können in Form von **Triples: Subjekt–Prädikat–Objekt** dargestellt werden. Triples bilden die **syntaktische Grundlage** für die formalisierte semantische Datenmodellierung und ermöglichen es, Ontologien wie CIDOC CRM in maschinenlesbarer Form zu repräsentieren.

Das **RDF (Resource Description Framework)** ist ein Standard zur formalen Beschreibung von Aussagen über Ressourcen in Form von Triples, der auch in WissKI verwendet wird (W3C, 2014).

> **Beispiel: Zelda-Spiel (SNES)**
>
> *Das Videospiel „The Legend of Zelda: A Link to the Past“ wurde 1991 von Nintendo in Kyoto, Japan entwickelt.* (Wikio.D.zelda)

| Natürliche Aussage | CIDOC-CRM-Repräsentation |
|---|---|
| Das Spiel ist ein Objekt. | **E22 Human-Made Object** |
| Der Titel lautet: *The Legend of Zelda: A Link to the Past* | **E22** → *has title* → **E35 Title** |
| Das Spiel wurde produziert. | **E12 Production** |
| Entwickler und Verleger ist Nintendo. | **E12 Production** → *carried out by* → **E74 Group (Nintendo)** |
| Produktionsort ist Kyoto. | *took place at* → **E53 Place (Kyoto)** |
| Veröffentlichungsjahr ist: 1991 | *has time-span* → **E52 Time-Span (1991)** |

---

> **CIDOC CRM ist ereigniszentriert**
>
> CIDOC CRM beschreibt nicht nur, was etwas ist, sondern auch, was geschehen ist, wer daran beteiligt war, wo und wann es stattgefunden hat.
>
> Ereignisse verbinden Objekte mit Akteur:innen, Orten und Zeiträumen.
>
> Beispiel: Objekt → Ereignis ← Akteur:in

> **Bedeutung kann durch Triples ausgedrückt werden**
>
> Semantische Aussagen können folgendermaßen dargestellt werden:
>
> Subjekt → Prädikat → Objekt
>
> Beispiel: Herstellung → durchgeführt von → Nintendo
>
> RDF (Resource Description Framework) stellt einen Standard bereit, um Aussagen über Ressourcen maschinenlesbar als Triples darzustellen.

> **Unterscheidung zwischen Klassenzuordnung und Beziehungen**
>
> **Klassenzuordnung:** Beispielsweise „Das Spiel ist ein Objekt.“ → E22 Human-Made Object; Spiel → Instanz von → E22 Human-Made Object.
>
> **Beziehung:** Beispielsweise „Der Titel lautet …“ → E22 → hat Titel → E35 Title; Spiel → hat Titel → Titel.

---

## Top-Level- vs. Domänenontologien

Eine **Top-Level-Ontologie** beschreibt allgemeine Begriffe wie Zeit, Raum oder Ereignisse unabhängig von einem spezifischen Fach- oder Anwendungsbereich oder einer bestimmten Problemstellung (Rehbein, 2017, S. 165).

Eine **Domänenontologie** spezifiziert grundlegende Begriffe einer Top-Level-Ontologie für einen bestimmten Fach- oder Anwendungsbereich (Domäne) (Rehbein, 2017, S. 166).

In einer projekt- oder anwendungsspezifischen Umsetzung werden die für die Domäne relevanten Konzepte, Ereignisse und Beziehungen beschrieben.

| Top-Level-Ontologie (Grundstruktur) | Domänenontologie (Fachspezifik) |
|---|---|
| z. B. **CIDOC CRM** | Erweiterungen, WissKI-Flavors etc. |
| definiert grundlegende Konzepte | beschreibt fachspezifische Konzepte |
| sorgt für Interoperabilität | erhöht die Präzision |
| ist langfristig stabil | ist an Forschungsbedarfe anpassbar |

> **Referenzmodell und domänenspezifisches Modell**
>
> Eine allgemeine **Referenzontologie** bietet einen gemeinsamen konzeptuellen Rahmen.
>
> Eine **Domänenontologie** passt diesen Rahmen an die Konzepte und Anforderungen eines bestimmten Forschungsbereichs an und spezialisiert ihn entsprechend.
>
> **Hinweis:** CIDOC CRM stellt allgemeine Konzepte bereit, die in unterschiedlichen Bereichen des kulturellen Erbes wiederverwendet werden können. Ein domänenspezifisches Modell baut auf diesem gemeinsamen Rahmen auf, um die für eine Sammlung oder einen Forschungskontext relevanten Informationen zu beschreiben.

---

## Relevanz und Nutzen von CIDOC CRM

WissKI nutzt CIDOC CRM, weil es …

- **eindeutige, maschinenlesbare Bedeutungen** schafft
- **Begriffsmehrdeutigkeit und Datenisolierung** vermeidet
- **institutionenübergreifende Interoperabilität** ermöglicht
- **Ereignisse, Prozesse und Provenienz** systematisch abbildet
- **FAIR & Linked Open Data** unterstützt
- ein **robustes Fundament** für Wissensgraphen bietet
- sich vollständig in **WissKI** integrieren lässt.

> **Warum CIDOC CRM verwenden?**
>
> CIDOC CRM bietet einen gemeinsamen semantischen Rahmen, der dabei hilft,
>
> - die Bedeutung von Daten und ihre Beziehungen explizit zu machen,
> - Ereignisse, Prozesse und Provenienz systematisch abzubilden,
> - Informationen über verschiedene Sammlungen und Systeme hinweg zu verknüpfen und zu vergleichen sowie
> - eine semantische Grundlage für maschinenlesbare und nachnutzbare Forschungsdaten zu schaffen.
>
> In diesem Tutorial bildet CIDOC CRM die semantische Grundlage für die spätere Umsetzung in WissKI.

---

## Ausblick

CIDOC CRM ist eine ISO-zertifizierte, international entwickelte und etablierte Top-Level-Ontologie für den Bereich des kulturellen Erbes. Als formale Repräsentation grundlegender Konzepte, Eigenschaften und ihrer Beziehungen bietet CIDOC CRM ein wertvolles theoretisches und praktisches Werkzeug, um evidenzbasierte Phänomene des kulturellen Erbes zu strukturieren, darzustellen und zu verstehen. Die Ontologie ist erweiterbar und semantisch ausdifferenzierbar und damit anschlussfähig an Domänenontologien, die aus anwendungs- und projektspezifischen Kontexten der Forschungs- und Sammlungsarbeit hervorgehen (CIDOC, 2024a; Schwenk & Fischer, 2025).

In der nächsten Einheit wird die Wissenschaftliche Kommunikationsinfrastruktur WissKI vorgestellt. WissKI wurde speziell für die semantische Erzeugung und Verwaltung von Daten im Kulturerbebereich entwickelt. Die Infrastruktur ist ontologieagnostisch, bietet jedoch eine besondere Unterstützung für die Arbeit mit CIDOC CRM (WissKI, n.d.-b).

> **Wie geht es weiter?**
>
> Sie haben nun ein Referenzmodell kennengelernt, mit dem sich Konzepte, Ereignisse und Beziehungen im Bereich des kulturellen Erbes formal beschreiben lassen.
>
> In der nächsten Einheit lernen Sie WissKI kennen und erfahren, wie ontologiebasierte Strukturen die Verwaltung und Nutzung von Forschungsdaten unterstützen können.

---

## Bibliografie

(CIDOC, 2024a) CIDOC CRM Special Interest Group. (2024a). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. https://cidoc-crm.org/Version/version-7.1.3

(CIDOC, 2024b) CIDOC CRM Special Interest Group. (2024b). Classes & Properties Declarations of CIDOC-CRM version: 7.1.3. https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html 

(Rehbein, 2017) Rehbein, M. (2017). Ontologien. In: F. Jannidis, H. Kohle, & M. Rehbein (Hrsg.), Digital Humanities (S. 162-176). J.B. Metzler, Stuttgart. https://doi.org/10.1007/978-3-476-05446-3_11.

(RemoGrillo & claude, 2026). RemoGrillo & claude (2026). cidoc-crm_periodic_table. https://github.com/RemoGrillo/cidoc-crm_periodic_table

(Schwenk & Fischer, 2025) Schwenk, G. A. & Fischer, K. (2025). SODa Forum: Konservierungs- und Restaurierungsdokumentation gemeinsam weiterdenken - Ontologieentwicklung im Dialog. https://doi.org/10.5281/zenodo.15481743

(Wikipedia, 2026) Wikipedia (2026) The Legend of Zelda: A Link to the Past. https://de.wikipedia.org/wiki/The_Legend_of_Zelda:_A_Link_to_the_Past

(WissKI, n.d.-b) WissKI (n.d.-b). Features. https://wiss-ki.eu/features

(W3C, 2014) World Wide Web Consortium (W3C). (2014). RDF 1.1 concepts and abstract syntax. https://www.w3.org/TR/rdf11-concepts























