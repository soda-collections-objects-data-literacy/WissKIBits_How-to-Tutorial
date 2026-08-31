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

Modul 2: **Modllieren mit CIDCO CRM – verstehen und anwenden**

Einheit 2: **Einführung in Protege**  

**Dauer:** ~ 20 Min.

**Lernziele:**

Teilnehmende können...

- Software zur Erstellung von Ontologien benennen. (LZ-ID SODa\_03\_007\_0809)
- Software zur Erstellung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0810)
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0840)

---

## Protége - OWL Ontologie-Editor

**Protégé** ist ein freier und quelloffener Editor zur Erstellung, Bearbeitung und Verwaltung von Ontologien. Die aktuelle Version unterstützt insbesondere die **OWL 2 Web Ontology Language** und bietet damit eine Umgebung für die formale und maschinenlesbare Modellierung von Ontologien. (Stanfordo.D.software) Protégé ist sowohl als Desktop-Anwendung ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege)) als auch als webbasierter Editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege)) verfügbar. (Stanfordo.D.protege)

In der Praxiseinheit dieses Moduls wird **Protégé Desktop** verwendet. Der Editor bietet eine grafische Oberfläche, mit der Ontologien erstellt, bearbeitet und strukturiert werden können. Bereits vorhandene Ontologien können in Protégé geöffnet und als Grundlage für die weitere Modellierung verwendet werden. Die vorgenommenen Modellierungen lassen sich anschließend in einem **maschinenlesbaren Format** speichern und für die weitere Verarbeitung nutzen.

Im Rahmen dieses Moduls dient Protégé dazu, das in Modul 1 entwickelte **semantische Modell der Domäne Computerspiele in eine formale, maschinenlesbare OWL-Ontologie zu überführen**. Als Referenzontologie dient das **CIDOC CRM** ([Release Version 7.1.3 Stand Februar 2024](https://cidoc-crm.org/get-last-official-release)), konkret die bestehende OWL-Implementierung des CIDOC CRM, das **[Erlangen CRM / OWL](https://erlangen-crm.org/current-version)** (Schiemann2024crm). Sie kann in Protégé geladen und als Ausgangspunkt für die weitere Modellierung verwendet werden.

Auf dieser Grundlage werden die für die Domäne Computerspiele relevanten Klassen, Eigenschaften und Beziehungen modelliert, überprüft und für die technische Umsetzung vorbereitet.

Für die Arbeit mit Protégé stehen auf der [**offiziellen Protégé-Website**](https://protege.stanford.edu/) (Stanfordo.D.protege) umfangreiche [Dokumentationen](https://protege.stanford.edu/support/#documentation) (Stanfordo.D.docu) und ein [Wiki](https://protegewiki.stanford.edu/wiki/Main_Page) (Stanfordo.D.wiki) zur Verfügung. Diese Ressourcen können insbesondere bei weiterführenden Fragen zur Bedienung des Editors und zur Entwicklung von OWL-Ontologien genutzt werden.

Das Ergebnis der Praxiseinheit ist eine **maschinenlesbare OWL-Ontologie**, die als Grundlage für die anschließende Implementierung in **WissKI** in Modul 3 dient. Protégé bildet damit die Verbindung zwischen der semantischen Modellierung und ihrer technischen Umsetzung.

---

## Live-Demo in Protégé

In dieser Einheit wird gezeigt, wie eine **OWL-Implementierung des CIDOC CRM** in **Protégé geladen und geöffnet** wird.

Anhand der geladenen Ontologie wird die Arbeitsoberfläche von Protégé vorgestellt. Dabei werden die verschiedenen Bereiche der Ontologie, insbesondere die Klassen und ihre Hierarchie, betrachtet und erste Einblicke in deren Darstellung und Struktur gegeben. 

Die **Live-Demo** dient damit als **erste Orientierung in Protégé** und schafft die Grundlage für die anschließende **Praxiseinheit**, in der das zuvor entwickelte Modell der Domäne Computerspiele in Protégé umgesetzt wird.

---

## Schritte im Überblick

**Schritt 1: Vorhandene Ontologie laden**

- In der praktischen Modellierung wird das **CIDOC CRM als bestehendes Ontologiemodell** zurgrunde gelegt.
- Für die Arbeit mit Protégé wird die **Erlangen CRM / OWL**, eine **maschinenlesbare OWL-Implementierung des CIDOC CRM** verwendet.
- Diese wird in Protégé Desktop geladen.
- **Download Erlangen CRM / OWL:** https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl

**Schritt 2: Struktur erkunden**

- In Protége lässt sich die **Struktur des CIDOC CRM erkunden**.
- Dazu gehören insbesondere die **Hierarchie der Klassen (Entities) sowie die Objekteigenschaften (Properties)**, über die Klassen (Entities) miteinander in Beziehung gestzt oder beschrieben werden.

> **Hinweis**
> - Klassen (Entities): die zentralen Klassen bzw. Entitätstypen des CIDOC CRM
> - Objekteigenschaften (Properties): Relationen zwischen Klassen (Entities)
> - Datentyp-Eigenschaften (Datatype-Properties): Eigenschaften, die Werte bzw. Literale beschreiben

**Schritt 3: Eigene Subklasse (Entity) anlegen für Domänenontologie Computerspiele**

- Neue, domänenspezifische Entities werden als **Subklassen bestehender CIDOC CRM-Entities** angelegt.

>  **Beispiel:**
>  E35 Title --> Game_Title

- **Game_Title** ist dabei eine domänenspezifische Subklasse von **E35 Title** und dient dazu, Titel im Kontext der Domäne Computerspiele spezifischer zu modellieren.

**Schritt 4: Speichern & Exportieren ( nicht mehr in der Live-Demo enthalten)**

- Die erweiterte Ontologie wird gespeichert und steht anschließend für **WissKI** und den **Pathbuilder** bereit.

---

## Video-Demonstration

!?[Video](../assets/Short_Protege_Intro.mp4)

<video controls>
  <source src="https://raw.githubusercontent.com/soda-collections-objects-data-literacy/SODaHow-to-Tutorial/main/assets/Short_Protege_Intro.mp4" type="video/mp4">
</video>

> Die Live-Demo veranschaulicht Schritt 1: Vorhandene Ontologie laden, Schritt 2: Struktur erkunden und Schritt 3: Eigene Subklasse (Entity) anlegen für Domänenontologie Computerspiele

---

## Ontologie laden und Struktur erkunden

**Arbeitsform:** Einzelarbeit

**Material:** Protége Desktop / (WebProtégé)

**Zeit:** 5 Min.

**Aufgabe:**

- Schitt 1: Protégé öffnen und Erlangen CRM / OWL: ** https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl laden
- Schitt 2: Die Klassenhierarchie erkunden und E42 Appelation suchen und Klasseneigenschaften aufrufen. Mögliche Beziehungen sichten.

**Hinweis:** 

Diese Aufgabe stellt sicher, dass alle Teilnehmenden den Ontologie-Editor Protégé verfügbar haben und über eine URL Erlangen CRM / OWL geladen haben und somit die technische Grundlage für das Entwickeln einer CIDOC CRM baierten Domänenontologie geschaffen haben.

---

## Ausblick

Die bisherigen Schritte haben gezeigt, wie das **CIDOC CRM in Protégé geöffnet und erkundet** werden kann und wie bestehende Entities für die Modellierung einer eigenen Domäne erweitert werden können.

In der nun folgenden **Praxiseinheit** wird dieses Vorgehen auf die **Domäne Computerspiele** übertragen. Das zuvor entwickelte semantische Modell wird dabei Schritt für Schritt in Protégé umgesetzt. Dabei werden geeignete CIDOC CRM-Entities ausgewählt, um domänenspezifische Subklassen erweitert und die entsprechenden Properties modelliert. 

So entsteht aus der konzeptionellen Modellskizze eine **formal beschriebene und maschinenlesbare OWL-Ontologie**, die anschließend für die Implementierung in WissKI verwendet werden kann.


## Bibliografie

[SIG2024cidoc] CIDOC CRM Special Interest Group. (2024). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. https://cidoc-crm.org/Version/version-7.1.3

[Schiemann2024crm] Schiemann, B., Oischinger, M., Götz, G., Merges, J., Fichtner, M., & Scholz, M. (o. D.). Erlangen CRM / OWL. https://erlangen-crm.org/

[Stanfordo.D.docu] Stanford Center for Biomedical Informatics Research. (o. D.). Documentation. https://protege.stanford.edu/support/#documentation

[Stanfordo.D.protege] Stanford Center for Biomedical Informatics Research. (o. D.). Protégé. https://protege.stanford.edu/

[Stanfordo.D.wiki] Stanford Center for Biomedical Informatics Research. (o. D.). Protégé Wiki. https://protegewiki.stanford.edu/wiki/Main_Page

[Stanfordo.D.software] Stanford Center for Biomedical Informatics Research. (o. D.). Software. https://protege.stanford.edu/software/






















