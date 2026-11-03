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

einheit: Grundbegriffe konzeptueller Wissensmodellierung

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-10-05

LearningResourceType: SODa How-to-Tutorial

-->


# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 1: **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären**

Einheit (E1): **Grundbegriffe konzeptueller Wissensmodellierung**  

**Dauer:** ~ 20 Min.

**Lernziele:**

Teilnehmende können...

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
  
---

## Begriffsdefinitionen der konzeptuellen Wissensmodellierung

Bei der **konzeptuellen Wissensmodellierung** wird herausgearbeitet, welches Wissen innerhalb einer Domäne relevant ist und wie dieses Wissen konzeptuell geordnet werden kann.

Eine **Domäne** ist der fachlich abgegrenzte Werte-, Wissens- und Anwendungsbereich (Fischer & Hofer, 2010, S. 257), für den Wissen beschrieben und modelliert wird. In der semantischen Modellierung umfasst eine Domäne im vorliegenden Kontext die fachlich relevanten Konzepte, Ereignisse und Beziehungen, beispielsweise den Bereich einer Forschungs- oder Objektsammlung.

> **Zentrale Begriffe**
>
> **Konzeptuelle Wissensmodellierung** identifiziert und ordnet das für eine bestimmte Domäne relevante Wissen.
>
> Eine **Domäne** ist ein abgegrenzter Wissens- oder Anwendungsbereich, beispielsweise eine Forschungs- oder Objektsammlung.
>
> **Ziel ist es, relevante Konzepte, Ereignisse und Beziehungen zu identifizieren** und **ihre fachspezifische Bedeutung zu klären**.

---

### Bausteine der konzeptuellen Modellierung

Zentrale Elemente der konzeptuellen Wissensmodellierung sind **Konzepte, Ereignisse und Beziehungen**:

- **Konzepte** sind abstrakte Vorstellungen oder Begriffe, mit denen relevante Gegenstände und Sachverhalte einer Domäne bezeichnet werden. Beispiele sind Objekt, Person, Ort oder Institution.
- **Ereignisse** beschreiben zeitlich und räumlich einordbare Geschehnisse oder Prozesse, an denen Objekte, Personen oder andere Konzepte beteiligt sein können. Beispiele sind Herstellung, Erwerb, Fund, Restaurierung, Ausstellung oder Nutzung eines Objekts.
- **Beziehungen** beschreiben bedeutungstragende Verknüpfungen zwischen Konzepten oder zwischen Konzepten und Ereignissen. Beispiele sind „Person nahm an Herstellung teil“, „Herstellung fand an Ort statt“ oder „Objekt wurde durch Herstellung erzeugt“.

Die Identifikation und Strukturierung dieser Elemente bildet die Grundlage der **semantischen Modellierung**.

---

### Vom konzeptuellen Wissen zum semantischen Datenmodell

**Konzeptuelle Wissensmodellierung** identifiziert und ordnet das für eine bestimmte Domäne relevante Wissen.

Der **semantischen Modellierung** geht die Konzeptualisierung eines Wissensbereichs voraus. In diesem Schritt werden relevante Begriffe, Konzepte und Beziehungen identifiziert, strukturiert und in ihrer fachlichen Bedeutung bestimmt. Die anschließende **semantische Modellierung** stellt diese konzeptuelle Wissensstruktur in einem formalisierten Modell dar (Rehbein, 2017, S. 164; Schwenk & Fischer, 2025, S. 23). Sie erfordert somit sowohl ein Verständnis des jeweiligen Fachgebiets als auch Kompetenzen in der formalen Modellierung (Fichtner, 2025, S. 86).

Das Ergebnis dieses Prozesses ist ein **semantisches Datenmodell**. Es bildet nicht die einzelnen konkreten Forschungsdaten ab, sondern beschreibt als konzeptueller und formaler Rahmen, wie Daten einer Domäne verstanden, interpretiert und miteinander in Beziehung gesetzt werden (Spasojevic, 2025; Schwenk & Fischer, 2025, S. 21). Indem es die Bedeutung der Daten explizit macht und formal beschreibt, schafft es die Voraussetzung dafür, dass diese auch langfristig inhaltlich interpretierbar und nachnutzbar bleiben (Fichtner, 2025, S. 58).

> **Merksatz**
>
> Die **konzeptuelle Wissensmodellierung** klärt, welches Wissen relevant ist und wie es geordnet wird.
>
> Die **semantische Modellierung** formalisiert diese fachliche Ordnung.
>
> Das **semantische Datenmodell** ist das Ergebnis dieses Prozesses.

---

## Vom Domänenwissen zum semantischen Datenmodell

Ein Sammlungsobjekt kann durch viele einzelne Informationen beschrieben werden. Die **konzeptuelle Modellierung** hilft uns zu entscheiden, welche davon relevant sind und wie sie miteinander zusammenhängen.

Betrachten wir das Computerspiel **The Legend of Zelda: A Link to the Past**. Ein Sammlungsdatensatz kann beispielsweise den **Titel**, Angaben zum **Publisher**, ein **Veröffentlichungsdatum** und die **Plattform**, für die das Spiel veröffentlicht wurde, enthalten.

Um ein konzeptuelles Modell zu entwickeln, fragen wir, worauf sich diese Informationen beziehen. Beispielsweise:

- Ein Titel ist eine Bezeichnung.
- Ein Publisher ist eine Organisation.
- Eine Veröffentlichung kann als Ereignis betrachtet werden.

Anschließend untersuchen wir, wie diese Elemente mit dem Spiel und miteinander in Beziehung stehen.

Das entstehende Modell bildet den Sammlungsdatensatz nicht einfach ab. Es macht **ausgewählte Konzepte und Beziehungen explizit**, sodass ihre Bedeutung diskutiert und weiter präzisiert werden kann.

---

## Wissen einer Sammlung konzeptuell ordnen

**Arbeitsform:** Kurze Plenumsdiskussion

**Zeit:** 5 Min.

> **Reflektieren Sie Ihre Modellskizze**
>
> Wählen Sie eine Beziehung aus Ihrer Modellskizze aus und lesen Sie diese als vollständige Aussage.
>
> - Welche Elemente sind Konzepte?
> - Welche Elemente stellen Ereignisse dar?
> - Welche Verknüpfungen sind Beziehungen?
>
> Überarbeiten Sie bei Bedarf die Bezeichnung der Beziehung in Ihrer Modellskizze.

---

> **Schritt 1: Erneut betrachten**
>
> Betrachten Sie die Modellskizze, die Sie bereits erstellt haben.
>
> **Schritt 2: Einordnen**
>
> Identifizieren Sie Beispiele für **Konzepte, Ereignisse und Beziehungen**.
>
> **Schritt 3: Reflektieren**
>
> Wählen Sie eine Beziehung aus und fragen Sie sich:
>
> - Könnten dieselben beiden Konzepte durch unterschiedliche Beziehungen miteinander verbunden werden, wenn eine andere Bedeutung ausgedrückt werden soll?

---

## Erwartetes Ergebnis

Sie haben **Konzepte, Ereignisse und Beziehungen** in Ihrer eigenen Modellskizze identifiziert und erläutert, wie diese zur konzeptuellen Ordnung des Domänenwissens beitragen.

**Konzepte, Ereignisse und Beziehungen können beispielsweise sein:**

- **Konzepte** bezeichnen beispielsweise Objekte, Personen, Organisationen, Orte oder andere zentrale Bausteine einer Domäne und repräsentieren relevante Elemente des Wissensbereichs.
- **Ereignisse** bezeichnen Geschehnisse oder Prozesse, beispielsweise Entwicklung, Herstellung, Veröffentlichung oder Ausstellung.
- **Beziehungen** verbinden Konzepte miteinander oder Konzepte mit Ereignissen und drücken aus, wie diese Elemente inhaltlich zusammenhängen.

---

## Ergebnis und Zusammenfassung

Die konzeptuelle Wissensmodellierung strukturiert das relevante Fachwissen einer Domäne anhand von Konzepten, Ereignissen und Beziehungen.

In Einheit M1U0A habt ihr aus Informationen über ein Sammlungsobjekt eine erste konzeptuelle Modellskizze erstellt.

In dieser Einheit habt ihr die Begriffe kennengelernt, mit denen sich dieser Prozess beschreiben lässt:

- **Konzepte** repräsentieren relevante Elemente einer Domäne.
- **Ereignisse** repräsentieren Geschehnisse und Prozesse.
- **Beziehungen** drücken bedeutungstragende Verknüpfungen zwischen diesen Elementen aus.

**Von der Modellskizze zu Forschungsfragen**

Welche Konzepte, Ereignisse und Beziehungen relevant sind, hängt davon ab, welche Fragen euer Datenmodell unterstützen soll.

Forschungsfragen im Sammlungskontext können beispielsweise sein:

- **Herstellung & Entstehung:** In welchem konkreten Kontext und durch welche Prozesse entstand das Objekt?
- **Akteur:innen & Rollen:** Welche Personen waren beteiligt und welche spezifischen Rollen nehmen sie ein?
- **Provenienz:** Über welche Stationen und Ereignisse gelangte das Objekt in die Sammlung?
- **Ort & Zeit:** Wie verlässlich lassen sich die geografischen und zeitlichen Angaben der Objekthistorie belegen?
- **Unsicherheiten:** Wie lassen sich widersprüchliche Hypothesen oder vage Zuschreibungen im Datenmodell abbilden?
- **Identifikation:** Wie lässt sich das Objekt über eindeutige Merkmale wie Inventarnummern exakt identifizieren und referenzieren?

> **Was habt ihr gelernt?**
>
> Ihr habt eine **erste konzeptuelle Modellskizze** erstellt, indem ihr relevante Informationen über ein Sammlungsobjekt identifiziert und miteinander verbunden habt.
>
> Ihr könnt diesen Prozess nun als **konzeptuelle Wissensmodellierung** beschreiben: die Ordnung von Domänenwissen anhand von Konzepten, Ereignissen und Beziehungen.
>
> Diese konzeptuelle Struktur bildet die Grundlage für die Entwicklung eines semantischen Datenmodells.

---

## Ausblick

Durch die konzeptuelle Wissensmodellierung haben wir in einem ersten Schritt herausgearbeitet, welches Wissen innerhalb einer Domäne relevant ist und wie dieses strukturell geordnet werden kann. Um diese gedankliche oder konzeptuelle Ordnung nun in einem formalen, maschinenlesbaren System darzustellen, werden Ontologien herangezogen. In Einheit 2 werden die allgemeinen Grundlagen von Ontologien vorgestellt.

> **Wie geht es weiter?**
>
> Ihr habt Domänenwissen konzeptuell geordnet und könnt diese Struktur nun anhand von Konzepten, Ereignissen und Beziehungen beschreiben.
>
> In Einheit 2 untersucht ihr, wie Ontologien formale Strukturen bereitstellen, um dieses Wissen maschinenlesbar darzustellen.

---

## Bibliografie

(Fichtner, 2025) Fichtner, M. (2025). Grundlagen der Erzeugung und Verwaltung von Ontologiepfaden und ihre Anwendung (Doctoral thesis, Friedrich-Alexander-Universität Erlangen-Nürnberg, Technische Fakultät). https://doi.org/10.25593/open-fau-2143

(Fischer & Hofer, 2010) Fischer, P. & Hofer, P. (2010). Lexikon der Informatik. https://doi.org/10.1007/978-3-642-15126-2

(Rehbein, 2017) Rehbein, M. (2017). Ontologien. In: F. Jannidis, H. Kohle, & M. Rehbein (Hrsg.), Digital Humanities (S. 162-176). J.B. Metzler, Stuttgart. https://doi.org/10.1007/978-3-476-05446-3_11

(Schwenk & Fischer, 2025) Schwenk , G. A. & Fischer, K. (2025), SODa Forum: Konservierungs- und Restaurierungsdokumentation gemeinsam weiterdenken - Ontologieentwicklung im Dialog. https://doi.org/10.5281/zenodo.15481743

(Spasojevic, 2024) Spasojević, A. (2024). Was ist ein semantisches Datenmodell? phoenixNAP IT Glossary. https://phoenixnap.de/Glossar/Semantisches-Datenmodell



