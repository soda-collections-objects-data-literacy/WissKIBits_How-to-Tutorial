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

**Dauer:** ~  Min.

**Lernziele:**

Teilnehmende können...

- Software zur Erstellung von Ontologien benennen. (LZ-ID SODa\_03\_007\_0809)
- Software zur Erstellung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0810)
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0840)

---

## Live-Demo in Protégé

Diese Einheit zeigt, wie auf Basis von **CIDOC CRM** eine **Domänenontologie** mit **Protégé** entwickelt wird.

**Protégé** ist ein frei verfügbarer **Ontologie-Editor**, der hier heruntergeladen werden kann: https://protege.stanford.edu

Alternativ ist **Protégé** auch als **Web-Editor** verfügbar: https://webprotege.stanford.edu

Mit einer klaren Vorgehensweise ist es möglich, auch ohne tiefgreifende Vorkenntnisse **eine Ontologie zu erstellen oder zu erweitern**.

---

## Schritte im Überblick

**Schritt 1: Vorhandene Ontologie laden**

In der praktischen Modellierung wird das **CIDOC CRM als bestehendes Ontologiemodell** zurgrunde gelegt. Für die Arbeit mit Protégé wird eine **maschinenlesbare OWL-Implementierung des CIDOC CRM** verwendet, beispielsweise das **Erlangen CRM / OWL**. Diese wird in Protégé importiert und kann anschließend um domänenspezifische Klassen, Eigenschaften und Beziehungen erweitert werden.

Download: https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl

**Schritt 2: Struktur erkunden**

   - Klassen (Entities)  
   - Objekteigenschaften (Properties) (Relationen zwischen Entitäten)  
   - Datentyp-Eigenschaften (nur für Literale)

**Schritt 3: Eigene Subklassen (Entities) anlegen für neue Domänenkonzepte**

 **Beispiel:**

> - Game_Characteristic
> - Platform_Type
> - Genre_Type
> - Edition_Type

**Schritt 4: Speichern & Exportieren**

Die erweiterte Ontologie wird gespeichert und steht anschließend für **WissKI** und den **Pathbuilder** bereit.

---

## Video-Demonstration

!?[Video](../assets/Short_Protege_Intro.mp4)

<video controls>
  <source src="https://raw.githubusercontent.com/soda-collections-objects-data-literacy/SODaHow-to-Tutorial/main/assets/Short_Protege_Intro.mp4" type="video/mp4">
</video>

---

## Ausblick






















