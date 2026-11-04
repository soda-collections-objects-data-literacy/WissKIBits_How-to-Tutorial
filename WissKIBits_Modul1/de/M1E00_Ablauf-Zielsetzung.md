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

title: WissKI Bits Ontologiegestützte Modellierung von Forschungsdaten

module: Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären

unit: Willkommen, Zielsetzung und Ablauf

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->


# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 1 (M1): **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären**

Einheit 0 (E00): **Willkommen, Zielsetzung und Ablauf**  

**Dauer:** ~ 5 Min.


---

## Willkommen bei WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

In **Modul 1** lernen Sie, wie Informationen über ein Sammlungsobjekt schrittweise in ein **konzeptionelles Modell** überführt werden können.

Anhand eines Beispiels aus einer **Computerspielsammlung** wechseln Sie von der Sammlungsperspektive zur Modellierungsperspektive. Dabei identifizieren Sie relevante Konzepte, Ereignisse und Beziehungen und untersuchen, wie diese zusammenhängen.

Anschließend setzen Sie ausgewählte Elemente Ihrer Modellskizze mit Klassen und Eigenschaften des Referenzmodells **CIDOC CRM** in Beziehung und treffen erste nachvollziehbare Modellierungsentscheidungen.

Die entstehende konzeptionelle Modellskizze bildet die Grundlage für die weitere **Formalisierung in Modul 2** und die spätere **technische Implementierung in WissKI in Modul 3**.

> **Worum geht es in diesem Modul?**
>
> Ausgehend von Informationen über ein konkretes Sammlungsobjekt untersuchen Sie, welche fachlichen Konzepte, Ereignisse und Beziehungen für dessen Beschreibung relevant sind.
>
> Sie strukturieren diese Informationen in einer ersten **konzeptionellen Modellskizze**, präzisieren ihre Bedeutung und lernen, wie ausgewählte Elemente mithilfe von **CIDOC CRM** beschrieben werden können.
>
> Die entstandene Modellskizze dient als Ausgangspunkt für die weitere Formalisierung in Modul 2.

---

## Warum semantisch modellieren?

- Forschungs- und Sammlungsdaten sind komplexe Objekt- und Kontextdaten. Sie beschreiben nicht nur Objekte und ihre Eigenschaften. Sie entstehen im Kontext fachwissenschaftlicher Forschung und sind mit historischen, kulturellen und sozialen Bedeutungen und Zusammenhängen verbunden.
- Tabellen bilden einzelne Eigenschaften und Informationen ab, während die Bedeutung und Zusammenhänge der Daten häufig implizit bleiben.
- Damit Daten langfristig inhaltlich interpretierbar und nachnutzbar bleiben, muss ihre Bedeutung **explizit** gemacht und formal beschrieben werden.

> Forschungs- und Sammlungsdaten bestehen aus mehr als einzelnen Fakten.
>
> Ihre Bedeutung und ihre Beziehungen sind ebenso wichtig.
>
> **Semantische Modellierung macht diese Zusammenhänge explizit, verständlich und nachnutzbar.**

---

## Leitfrage

Die Leitfrage, die uns durch dieses Modul begleitet, lautet:

> **Wie können Informationen über ein Objekt in ein transparentes, interoperables semantisches Datenmodell überführt werden, das in WissKI implementiert werden kann?**

---

## Zielsetzung des Moduls

In diesem Modul lernen Sie, wie Sie ausgehend von Informationen über ein Sammlungsobjekt ein konzeptionelles Modell des zugehörigen Fachbereichs entwickeln können.

Am Ende des Moduls sind Sie in der Lage,

- relevante **Konzepte, Ereignisse und Beziehungen** anhand eines Beispiels aus einer Computerspielsammlung zu identifizieren,
- zwischen fachspezifischen Begriffen und den Bedeutungen, die sie ausdrücken sollen, zu unterscheiden, um eine schlüssige Domänenlogik zu entwickeln und zu begründen,
- zu untersuchen, wie ausgewählte Konzepte mithilfe von **CIDOC-CRM-Klassen und -Eigenschaften** dargestellt werden können,
- erste Modellierungsentscheidungen zu erläutern und
- eine **konzeptionelle Modellskizze** zu entwickeln, die in Modul 2 weiter ausgearbeitet und formalisiert werden kann.

---

## Ablauf des Moduls

**Gesamtdauer von Modul 1: ca. 90 Minuten**

| Einheit | Inhalt | Dauer |
|---|---|---:|
| M1E00 | Willkommen, Lernziele und Ablauf | 5 Min. |
| M1E0A | Aktivierung: Sammlungsobjekt „Zelda“ | 15 Min. |
| M1E1 | Grundbegriffe der konzeptuellen Wissensmodellierung | 10 Min. |
| M1E2 | Grundlagen von Ontologien | 10 Min. |
| M1E3 | Einführung in CIDOC CRM | 15 Min. |
| M1E4 | FAIR-Konformität mit WissKI | 15 Min. |
| M1EÜ | Übung: Konzeptionelle Struktur und erster CIDOC-CRM-Entwurf | 20 Min. |
| | **Gesamt** | **90 Min.** |

---

## Lernziele des Moduls

Nach Abschluss von Modul 1 können die Teilnehmenden…

### E0. Anwendungsbeispiel: Objektsammlung

- die Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0811)
- die Methode der konzeptuellen Wissensmodellierung zur Beschreibung eines Forschungsobjektes anwenden. (LZ-ID SODa\_03\_007\_0856)
  
### E1. Grundbegriffe konzeptueller Wissensmodellierung
   
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

### E2. Grundlagen von Ontologien
   
- Begriff Ontologie benennen. (LZ-ID SODa\_03\_007\_0826)
- Begriff Ontologie erläutern. (LZ-ID 03\_007\_0775)
- Aspekte von Ontologien benennen. (LZ-ID 03\_007\_0776)
- Begriff Klassen (Classes/Concepts) benennen. (LZ-ID SODa\_03\_007\_0829)
- Begriff Klassen (Classes/Concepts) erläutern. (LZ-ID SODa\_03\_007\_0830)
- Begriff Instanzen (Instances) benennen. (LZ-ID SODa\_03\_007\_0833)
- Begriff Instanzen (Instances) erläutern. (LZ-ID SODa\_03\_007\_0834)
- Begriff Eigenschaften (Properties) benennen. (LZ-ID SODa\_03\_007\_0831)
- Begriff Eigenschaften (Properties) erläutern. (LZ-ID SODa\_03\_007\_0832)
- Begriff Modellannahmen (Constraints) benennen. (LZ-ID SODa\_03\_007\_0835)
- Begriff Modellannahmen (Constraints) erläutern. (LZ-ID SODa\_03\_007\_0836)

### E3. Einführung in CIDOC CRM

- Ontologie zur Beschreibung von Ressourcen bennen. (LZ-ID 03\_007\_0778)
- Ontologie zur Beschreibung von Ressourcen erläutern. (LZ-ID 03\_007\_0779)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung benennen. (LZ-ID SODa\_03\_007\_0806)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung erläutern. (LZ-ID SODa\_03\_007\_0807)
- Begriff Scope Notes benennen. (LZ-ID SODa\_03\_007\_0837)
- Begriff Scope Notes erläutern. (LZ-ID SODa\_03\_007\_0838)
- Resource Description Framework (RDF) als Standard zur Beschreibung von Ressourcen benennen. (LZ-ID SODa\_03\_007\_0843)
- Begriff Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0827)
- Begriff Domänenontologie erläutern. (LZ-ID SODa\_03\_007\_0828)
- Nutzen des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0805)
 
### E4. FAIR-Konformität mit WissKI

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

### EÜ. Anwendungsbeispiel Objektsammlungen

- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0811)
- Datentyp-Eigenschaften des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0808)
  
---

## Lernweg im Modul

Das Modul folgt einem schrittweisen Ansatz: Ausgehend von einem konkreten Sammlungsobjekt werden nach und nach grundlegende Konzepte der semantischen Modellierung eingeführt.

**Sammlungsobjekt erkunden (M1U0A):**  
Relevante Informationen identifizieren und eine erste Modellskizze erstellen.

↓

**Ontologien kennenlernen (M1U2):**  
Sich mit den grundlegenden Bestandteilen von Ontologien und ihrer Rolle in der semantischen Modellierung vertraut machen.

↓

**CIDOC CRM kennenlernen (M1U3):**  
Verstehen, wie eine Referenzontologie die Beschreibung von Informationen zum kulturellen Erbe unterstützen kann.

↓

**FAIR-Konformität mit WissKI erkunden (M1U4):**  
Verstehen, wie semantische Modellierung und WissKI die FAIR-Prinzipien und die Nachnutzung von Forschungsdaten unterstützen können.

↓

**CIDOC CRM anwenden (M1UE):**  
Die eigene Modellskizze erneut betrachten, mögliche Zuordnungen zu CIDOC CRM untersuchen und ausgewählte Modellierungsentscheidungen begründen.


Ihr Ergebnis: Eine konzeptionelle Modellskizze mit ersten dokumentierten CIDOC-CRM-Zuordnungen, die in Modul 2 weiter ausgearbeitet werden kann.

---

## Arbeitsweise und Beispiel

Das Modul verbindet kurze fachliche Inputs mit Analyse, Diskussion und Modellierungsaktivitäten:

- Begriffe werden anhand typischer Informationen aus Sammlungen eingeführt.
- Modellierungsentscheidungen werden gemeinsam diskutiert und begründet.
- Das Beispielobjekt **„The Legend of Zelda: A Link to the Past“** dient als roter Faden.
- In der Übung entwickeln die Teilnehmenden eine kleine Modellskizze und gleichen ausgewählte Konzepte mit CIDOC CRM ab.
- Die Ergebnisse werden im Plenum gesichert und auf die eigene Sammlungspraxis übertragen.

Das Ziel ist kein vollständiges Datenmodell. Entscheidend ist ein **kleiner, konsistenter und begründbarer Modellentwurf**, der später erweitert und technisch umgesetzt werden kann.

> **So arbeiten Sie**
>
> Wir beginnen mit einer kurzen Aktivierungsübung anhand eines konkreten Sammlungsobjekts.
>
> Nach den fachlichen Einführungseinheiten greifen Sie das Beispiel erneut auf und entwickeln eine kleine, konsistente und begründete Modellskizze.
>
> Unser gemeinsames Beispiel ist **The Legend of Zelda: A Link to the Past**.

---

## Voraussetzungen

Es werden **keine Vorkenntnisse in Ontologien, RDF, OWL, CIDOC CRM oder WissKI** vorausgesetzt.

Erfahrungen im Umgang mit Sammlungs-, Objekt- oder Forschungsdaten sind hilfreich.

---

## Ergebnis des Moduls

Am Ende von Modul 1 liegt eine erste **konzeptuelle Modellskizze** vor, die relevante **Konzepte und Ereignisse, ihre Beziehungen** sowie **erste Zuordnungen zu CIDOC CRM** zeigt.

> **Was nehmen Sie aus dem Modul mit?**
>
> Am Ende des Moduls liegt eine erste konzeptuelle Modellskizze der Domänenlogik (Computerspiele) vor. Sie zeigt:
>
> - die für das Beispiel relevanten Konzepte und Ereignisse,
> - ihre semantischen Beziehungen,
> - erste Zuordnungen zu Klassen (Entities) und Eigenschaften (Properties) des CIDOC CRM,
> - sowie begründete Modellierungsentscheidungen.
>
> Diese Skizze dient als Ausgangspunkt für die weitere Formalisierung und Implementierung in WissKI.

---

## Ausblick

In der folgenden Einheit werden zunächst die Grundbegriffe der konzeptuellen Wissensmodellierung geklärt und diese als Grundlage der semantischen Datenmodellierung präsentiert.

Anschließend führt das Modul von Ontologien und ihren Bausteinen über CIDOC CRM und FAIR bis zur konzeptuellen Modellskizze der Domänenlogik.

Die technische Umsetzung des Modells mit CIDOC CRM und im WissKI Pathbuilder wird in den weiterführenden Modulen behandelt.

> **Wie geht es weiter?**
>
> Sie wissen nun, was Sie in diesem Modul entwickeln werden.
>
> Als Nächstes beginnen Sie mit einem konkreten Sammlungsobjekt und erstellen eine erste **konzeptuelle Modellskizze**, indem Sie relevante Konzepte, Ereignisse und Beziehungen identifizieren.

---

## Redaktionelle Hinweise

- Die Zeitplanung ist auf insgesamt 90 Minuten abgestimmt und kann je nach Gruppengröße angepasst werden.

