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

Einheit 1: **Semantische Datenmodelle visualisieren**  

**Dauer:** ~  Min.

**Lernziele:**

Teilnehmende können...

- Software zur Visualisierung einer Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0812)
- Software zur Visualisierung einer Domänenontologie erläutern. (LZ-ID LZ-ID SODa\_03\_007\_0813)
- Begriff Visualisierung erläutern. (LZ-----xxxxx)
- Nutzen von Visualisierungen erläutern. (LZ----xxxxx)
- Nutzen einer Software zur Visualisierung einer Domänenontologie benennen. (LZ-ID SODa\_03\_007\_0814) 
- Software zur Visualisierung einer Domänenontologie unter Anleitung anwenden. (LZ-ID SODa\_03\_007\_0815)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung benennen. (LZ----xxxxx)
- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0811)
- Regeln zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware benennen. (LZ-ID SODa\_03\_007\_0820)
- Regeln zur Modellierung einer Domänenontologie mit einer Visualisierungssoftware anwenden. (LZ-ID SODa\_03\_007\_0816)
- Attributwerte an vordefinierten Klassen der Domänenontologie in einer Visualisierungssoftware anwenden. (LZ-ID SODa\_03\_007\_0817)

---

## Visualisierung einer Domänenontologie als Diagramm mit Draw.io

In dieser Einheit wird das in Modul 1 und 2 entwickelte Datenmodell als Diagramm in Draw.io (Ltd2026drawio) visualisiert. 

Das entwickelte Draw.io-Diagramm bildet die **Voraussetzung für die (halb-)automatisierte Pipeline** zur Erstellung eines **WissKI Pathbuilders**.

Das Visualisieren in Draw.io ist somit nicht nur eine **visuelle Übung**, sondern gleichzeitig ein **expliziter Modellierungsschritt**, um **Modellierungsentscheidungen zu kommunizieren, auszuhandeln und ein gemeinsames Verständnis über semantische Strukturen zu treffen und zu fördern.**

---

## Begriffsdefinition

**Visualisierung**

Visualisierungen sind bildliche Darstellungen von Sachverhalten, die deren Verständnis befördern sollen. 

"In den Geisteswissenschaften werden Visualisierungen als Illustrationen, als Gedächtnisstützen für bekannte Sachverhalte, bei der Organisation von Wissen, sowie als Erkenntnismittel in der Vermittlung und Erzeugung von (neuem) Wissen eingesetzt." (Freyberg2023visual)

"Zum Lernen sind Visualisierungen insbesondere dann geeignet, wenn der zu vermittelnde Gegenstand verbal nur schwer vermittelbare Eigenschaften aufweist." (Scheiter2021visual)

Sie werden daher begleitend zum  Wissenserwerb eingesetzt, um Inhalte konkreter und besser verständlich zu machen und Strukturen zu verdeutlichen. (Levin1987visual)

---

## Nutzen von Draw.io

Draw.io wird eingesetzt um...

- **Klassen (Entities) und ihre Beziehungen (Properties)** klar zu definieren,
- eine **Domänenlogik mit ihren semantischen Zusammenhängen** sichtbar und diskutierbar zu machen,  
- Domänenmodelle **kollaborativ und transparent** zu entwickeln,  
- eine **Domänenontologie vor dem Import in WissKI** zu prüfen,  
- **semantische Modellierungsentscheidungen** zu reflektieren und abzusichern.

Besonders in kollaborativen Projekten erleichtert Draw.io die **Abstimmung zwischen Fachexpert:innen, Datenmodellierenden und Entwickler:innen**, da semantische Entscheidungen visuell nachvollziehbar und dokumentierbar sind und bleiben.

---

## Beispiel

Die bisherigen Fragen haben verdeutlicht, welche zentralen Konzepte der Beispieldomäne relevant sind und wie sie fachlich eingeordnet werden können.

Im nächsten Schritt geht es nicht mehr um das Erkennen oder Benennen dieser zentralen Konzepte, sondern darum, diese Auswahl in eine **formalisierte Pfadstruktur** zu überführen:

- Wie werden die zentralen Konzepte semantisch korrekt miteinander verknüpft?
- Wie entsteht daraus eine formalisierte Pfadstruktur, die in Form von **Pfaden und Pfadgruppen im WissKI Pathbuilder** nutzbar ist?

Dazu wird das konzeptionelle Domänenmodell nun **visuell und formal in Draw.io** umgesetzt.  


<table>
  <tr>
    <td><img src="../assets/SODa_ISWC2025.drawio.png" width="100%"></td>
  </tr>
</table>

---

## Quiz

Welche zentralen Konzepte sind im Kontext von Spielemerkmalen und narrativen Elemeten für das Beispielobjekt relevant?

Die folgenden Fragen dienen dazu, die zentralen Konzepte der Domäne noch einmal zu aktivieren und helfen die anschließende Modellierungsaufgabe besser einzuordnen:


### Welches Beispielobjekt wird im Modul verwendet? 

* [( )] Ein PC-Spiel: *Minecraft*
* [(x)] Ein SNES-Spiel: *The Legend of Zelda*
* [( )] Eine PlayStation-Konsole: *PS1*
* [( )] Ein Arcade-Automat: *Pac-Man*

### Welche semantische Annahme wird im Beispiel explizit gemacht?

* [( )] Das Spiel ist „Open World“
* [(x)] Der Titel des Objekts wird als *The Legend of Zelda: A Link to the Past* festgelegt
* [( )] Das Spiel ist eine „Collector’s Edition“
* [( )] Die Plattform ist „PC“

### Welche der folgenden Konzepte zählen zu den **Spielmerkmalen**?

* [[ ]] Perspektive
* [[X]] Genre
* [[X]] Edition
* [[X]] Plattform
* [[ ]] Hersteller

### Welche der folgenden Konzepte zählen zu den **narrativen Elementen**?

* [[X]] Perspektive
* [[X]] Spielbeschreibung
* [[X]] Charaktere
* [[ ]] Plattform
* [[ ]] Genre

----

## Aufgabe 

**Arbeitsform:** Einzelarbeit   
**Material:** eigenes Laptop
**Zeit:** 20 Min.

Kurze Beschreibung der Aufgabe.

1. Ergänze die Lücken (fehlende Knoten/Kanten) durch geeignete Klassen (Entities) und passende Beziehungen (Properties) im Diagramm.
2. Die temporären Platzhalter (???) sind nach der Ergänzung zu entfernen.

**Auswahl**

- P102\_has\_title
- P1 is identified by
- P190 has symbolic content
- mega:E41\_Game\_Character\_Name

**Hinweis: Regeln zur Visualisierung mit Draw.io**

- Die Knoten und Kanten müssen korrekt verbunden sein.
- Die Kantenbeschriftung muss mit der Kante verbunden sein.
- Die Benennungen können, müssen aber nicht Unterstriche beinhalten.
- Es werden keine individuellen Instanzen abgebildet.
- Es werden die domänenspezifischen Subklassen aus der bereits erstellten Domänenontologie verwendet.
- Die Beziehungen aus dem CIDOC CRM werden nachgenutzt.
- Es sind vollständige Pfade zu erstellen. (z.B. mega:E73\_Computer\_Game -> P102\_has\_title -> mega:E35\_Game\_Title -> P190 has symbolic content -> E62\_String)
- Dem zentralen Startknoten, jedem Gruppenknoten und jedem Endknoten werden jeweils **element\_id**, **group\_name** und **name** zugewiesen. (z.B. element\_id=Computer\_Game; group\_name=Computer\_Game; name=Computer\_Game)

**Ressourcen**

- Domänenontologie: [http://games.m-e-g-a.org/game_domain.rdf](http://games.m-e-g-a.org/game_domain.rdf)
- Für semantische Beziehungen (.pdf-Datei): [https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf](https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf)
- Alternative zur PDF-Datei ein HTML-Darstellung: [https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html)

---

## Workflow

| Schritt | Aktion |
|---:|---|
| 1 | Die vorbereitete Draw.io-Datei runterladen ([hier](../assets/M2E2_Gruppenarbeit.drawio.xml)) |
| 2 | Die heruntergeladene Draw.io-Datei in Draw.io importieren ([hier](https://app.diagrams.net/)) |
| 3 | Das Domänenontologie-Diagramm vervollständigen (siehe Auswahl)  |
| 4 | Attributwerte an Startknoten, jedem Gruppenknoten und Endknoten prüfen |
| 5 | Die Knoten-Kanten-Verbindungen prüfen  |

---

## Ausblick

Im nächsten Schritt wird das erstellte Draw.io-Diagramm automatisch in einen WissKI Pathbuilder konvertiert und die erzeugte Pfadstruktur in WissKI importiert.

---

## Bibliographie

[Freyberg2023visual] Freyberg, Linda (2023) Visualisierung. In: AG Digital Humanities Theorie des Verbandes Digital Humanities im deutschsprachigen Raum e. V. (Hg.): Begriffe der Digital Humanities. Ein diskursives Glossar (= Zeitschrift für digitale Geisteswissenschaften / Working Papers, 2). DOI: 10.17175/wp_2023_014_v2

[Scheiter2021visual] Scheiter, Katharina (2021) https://dorsch.hogrefe.com/stichwort/visualisierung

[Levin1987visual] Levin, J.R. , Anglin, G.J., & Carney, R.N. (1987). On empirically validating fuctions of pictures in prose. In D.M. Willows & H.A. Houghton (Hrsg.), The psychology of illustration. Vol. I Basic Research (S. c) New York: Springer.

(Ltd2026drawio)


<!-- ## Ausgangspunkt

Damit diese Visualisierung korrekt umgesetzt werden kann, müssen die relevanten Elemente der Domäne noch einmal klar sein.

In Modul 2 wurde die konzeptionelle Grundlage des Beispiel-Datenmodells entwickelt:

* In **Einheit 5** wurden *zentralen Konzepte (Entities)* eines Beispielobjektes aus der Computerspiel-Domäne identifiziert. 
* In **Einheit 6** wurde gezeigt, wie die Top-Level Ontologie CIDOC CRM um *domänenspezifische Subklassen* erweitert wird.  

**Zur Orientierung und zum Nachlesen**

* [Beispielobjekt](https://github.com/soda-collections-objects-data-literacy/SODaHow-to-Tutorial/blob/main/WissKIBits_Modul1/M1E2_Analyse-Workflow.md#beispielobjekt)
* [Beispiele für zentrale Konzepte (Spielmerkmale und narrative Elemente)](https://github.com/soda-collections-objects-data-literacy/SODaHow-to-Tutorial/blob/main/WissKIBits_Modul1/M1E5_Dom%C3%A4nenanalyse.md#fokus-dieser-modellierungs%C3%BCbung)  -->



















