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

Einheit 2: **Grundlage von Ontologien**  

**Dauer:** XX Min.

**Lernziele:**

Teilnehmende können...

- den Begriff Ontologie benennen. (LZ-ID SODa\_03\_007\_0826)
- den Begriff Ontologie erläutern. (LZ-ID 03\_007\_0775)
- den Begriff Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0827)
- den Begriff Domänenontologie erläutern. (LZ-ID SODa\_03\_007\_0828)
- den Aspekte von Ontologien benennen. (LZ-ID 03\_007\_0776)

---

## Titel des ersten Abschnitts

Einleitender Absatz der Einheit.

## Begriffsdefinition

**Ontologie**

Eine Ontologie ist eine **formale Beschreibung eines Ausschnitts der Welt** bzw. eine **"formale, schematische Abbildung[] eines Wissensbereichs, bestehend aus einem Vokabular und Regeln zu seiner Zusammensetzung."** 

Eine Ontologie legt fest,

- welche **Konzepte** von Dingen (z. B. Objekt, Person, Ort, Zeit) und **Ereignisse** in einem Fach- oder Anwendungsbereichs (Domäne) relevant sind,
- wie diese Konzepte miteinander **in Beziehung** stehen,
- und welche **Regeln** gelten, damit **Aussagen** über sie sinnvoll und widerspruchsfrei modelliert werden können.

Ontologien ermöglichen so ein gemeinsames Verständnis zentraler Phänomene, Konzepte und Strukturen in einer Domäne, sowohl für Menschen als auch für die maschinelle Verarbeitung.

**Domänenontologie**

Eine Domänenontologie ist eine projekt oder -anwendungsspezifische Umsetzung einer Ontologie, die die Konzepte, Ereignisse und Beziehungen innerhalb eines konkreten Fach- oder Anwendungsbereichs (Domäne) beschreibt.

---

## Nutzen von Ontologien und weiterführende Definitionen

Ontologien helfen damit, fachliches Domänenwissen mit ihrer spezifischen Domänenlogik so zu dokumentieren, dass es maschinenlesbar, vergleichbar und nachnutzbar wird. 

Im Kontext der Semantic-Web-Technologien lässt sich eine Ontologie als Struktur verstehen, die insbesondere bereitstellt:

- Klassen (Classes/Concpets): formale Repräsentation von Konzepten
- Eigenschaften (Properties) : formale Repräsentation von Merkmalen oder Beziehungen zwischen Klassen und Instanzen
- Instanzen (Instances): konkrete Ausprägungen von Klassen

Auf diese Weise ermöglichen Ontologien, Aussagen über Ressourcen formal abzubilden. (World Wide Web Consortium, 2012)

Ontologien unterstützen damit die systematische und konsistente Repräsentation von Domänenwissen, sodass Informationen maschinenlesbar und für die Nachnutzung in unterschiedlichen Systemen anschlussfähig werden. (Noy, 2001)

Die bekannteste Definition beschreibt eine Ontologie als "eine explizite, formale Spezifikation einer Konzeptualisierung", d. h. sie beschreibt strukturierend, welche Konzepte in einem bestimmten spezifischen Fachgebiet oder Gegenstandsbereich relevant sind und welche Beziehungen zwischen ihnen bestehen. (Gruber, 1993)

---

## Aspekte von Ontologien

Ontologien bestehen typischerweise aus folgenden Bausteinen:

* **Klassen (Classes/Concepts)** (z.B. Spiel, Person, Organisation, Ereignis)
* **Eigenschaften (Properties)** (z.B. *hat Titel*, *wurde veröffentlicht von*)
* **Instanzen (Instances)** (konkrete Dinge, z.B. *The Legend of Zelda: A Link to the Past*) 
* **Modellannahmen (Constraints)** (z.B. welche Beziehungen beschreiben zulässig das Objekt)
* **Definitionen (Scope Notes)** zur semantischen Präzisierung (z.B. in Referenzmodellen wie CIDOC CRM)

---

## Methoden zur Entwicklung von Ontologien

Die Entwicklung einer Domänenontologie folgt typischerweise einem methodischen, mehrstufigen und iterativen Vorgehen. 

Dazu zählen u.a. die Erhebung zentraler Begriffe und Definitionen (sog. „ontology capture“), die Strukturierung von Konzepten in Klassen und Eigenschafen/Relationen sowie die kontinuierliche Prüfung und Überarbeitung des Domänenmodells im Hinblick auf Konsistenz und Nutzbarkeit. (Gruber, 1993)

Die praktische Ontologieentwicklung wird dabei häufig als ein Prozess verstanden, der sowohl Domänenwissen als auch Anwendungsanforderungen integriert und schrittweise in eine formal nutzbare Wissensstruktur überführt.

Ontologien entstehen häufig durch eine Kombination aus:

* **Top-down-Modellierung:** Ausgehend von einem Referenzmodell (z.B. CIDOC CRM) erfolgt eine domänenspezifische Spezialisierung.
* **Bottom-up-Modellierung:** Aus vorhandenen Daten werden schrittweise Klassen (Entities) und Eigenschaften (Properties) abgeleitet.
* **Competency Questions:** Die Modellierung erfolgt aus typischen Analyse- und Forschungsfragen heraus (z.B. „Welche Spiele haben Merkmal X?“)
* **Iteratives Prototyping:** Es wird ein Modell entworfen → überprüft → kontinuierlich mit Blick auf Konsistenz, Erweiterbarkeit und Abfragbarkeit angepasst.

---

## Ausblick

Kurzer Übergang zur folgenden Einheit oder zum nächsten Modul.

---

## Bibliographie

[W3C2001owl]World Wide Web Consortium. (2012, December 11). OWL 2 Web Ontology Language Primer (Second Edition). W3C Recommendation. https://www.w3.org/TR/owl2-primer 

[Noy2001ontology] Noy, N. F., & McGuinness, D. L. (2001). Ontology Development 101: A Guide to Creating Your First Ontology. Stanford Knowledge Systems Laboratory.

[Gruber1993knowledge] Gruber, T. R. (1993). A Translation Approach to Portable Ontology Specifications. Knowledge Acquisition, 5(2), 199–220.

[Uschold1995method]Uschold, M., & King, M. (1995). Towards a Methodology for Building Ontologies.

























