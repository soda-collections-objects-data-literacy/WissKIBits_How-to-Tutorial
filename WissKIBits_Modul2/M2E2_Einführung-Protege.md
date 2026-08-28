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

## Protége - OWL Ontologie-Editor

[**Protégé**](https://protege.stanford.edu/)  ist ein freier und quelloffener Editor zur Erstellung, Bearbeitung und Verwaltung von Ontologien. Die aktuelle Version unterstützt insbesondere die **OWL 2 Web Ontology Language** und bietet damit eine Umgebung für die formale und maschinenlesbare Modellierung von Ontologien. Protégé ist sowohl als Desktop-Anwendung (**Protégé Desktop**) als auch als webbasierter Editor (**WebProtégé**) verfügbar.

In der Praxiseinheit dieses Moduls wird **Protégé Desktop** verwendet. Der Editor bietet eine grafische Oberfläche, mit der Ontologien erstellt, bearbeitet und strukturiert werden können. Bereits vorhandene Ontologien können in Protégé geöffnet und als Grundlage für die weitere Modellierung verwendet werden. Die vorgenommenen Modellierungen lassen sich anschließend in einem **maschinenlesbaren Format** speichern und für die weitere Verarbeitung nutzen.

Im Rahmen dieses Moduls dient Protégé dazu, das in Modul 1 entwickelte **semantische Modell der Domäne Computerspiele in eine formale, maschinenlesbare OWL-Ontologie zu überführen**. Als Referenzontologie dient das **CIDOC CRM**. Eine bestehende OWL-Implementierung des CIDOC CRM, beispielsweise die **Erlangen CRM / OWL**, kann in Protégé geladen und als Ausgangspunkt für die weitere Modellierung verwendet werden.

Auf dieser Grundlage werden die für die Domäne Computerspiele relevanten Klassen, Eigenschaften und Beziehungen modelliert, überprüft und für die technische Umsetzung vorbereitet.

Für die Arbeit mit Protégé stehen auf der **offiziellen Protégé-Website** umfangreiche Dokumentationen und ein Wiki zur Verfügung. Diese Ressourcen können insbesondere bei weiterführenden Fragen zur Bedienung des Editors und zur Entwicklung von OWL-Ontologien genutzt werden.

Das Ergebnis der Praxiseinheit ist eine **maschinenlesbare OWL-Ontologie**, die als Grundlage für die anschließende Implementierung in **WissKI** in Modul 3 dient. Protégé bildet damit die Verbindung zwischen der semantischen Modellierung und ihrer technischen Umsetzung.


## Live-Demo in Protégé

Diese Einheit zeigt, wie auf Basis von **CIDOC CRM** eine **Domänenontologie** mit **Protégé** entwickelt wird.

**Protégé** ist ein frei verfügbarer **Ontologie-Editor**, der hier heruntergeladen werden kann: https://protege.stanford.edu

Alternativ ist **Protégé** auch als **Web-Editor** verfügbar: https://webprotege.stanford.edu

Mit einer klaren Vorgehensweise ist es möglich, auch ohne tiefgreifende Vorkenntnisse **eine Ontologie zu erstellen oder zu erweitern**.

---

## Schritte im Überblick

**Schritt 1: Vorhandene Ontologie laden**

In der praktischen Modellierung wird das **CIDOC CRM als bestehendes Ontologiemodell** zurgrunde gelegt. Für die Arbeit mit Protégé wird die **Erlangen CRM / OWL**, eine **maschinenlesbare OWL-Implementierung des CIDOC CRM** verwendet. Diese wird in Protégé geladen und kann anschließend um domänenspezifische Klassen, Eigenschaften und Beziehungen erweitert werden.

**Download Erlangen CRM / OWL:** https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl

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

## Bibliografie






















