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

module: Modellieren mit CIDOC CRM – verstehen und anwenden

unit: Einführung in Protégé

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-11-05

LearningResourceType: How-to-Tutorial

-->

# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 2 (M2): **Modllieren mit CIDCO CRM – verstehen und anwenden**

Einheit 2 (E2): **Einführung in Protégé**  

**Dauer:** ~ 10 Min.

**Lernziele:**

Teilnehmende können...

- Software zur Erstellung von Ontologien benennen. (LZ-ID SODa\_03\_007\_0809)
- Software zur Erstellung von Ontologien erläutern. (LZ-ID SODa\_03\_007\_0810)
- Erlangen CRM / OWL als OWL-Implementierung des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0841)
- Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa\_03\_007\_0840)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0784a)
- Methoden zur Modellierung einer Domänenontologie mit dem Referenzmodell CIDOC CRM erläutern. (LZ-ID SODa\_03\_007\_0785a)

---

## Protégé – OWL-Ontologie-Editor

In Modul 1 haben Sie eine konzeptuelle Modellskizze entwickelt und mögliche Zuordnungen zu CIDOC CRM untersucht.

In Modul 2 überprüfen Sie diese Modellierungsentscheidungen und überführen ausgewählte Teile Ihres Modells in eine maschinenlesbare Form.

Dazu verwenden Sie **Protégé** (Stanford, 2026a), um eine bestehende OWL-Ontologie zu erkunden, ihre Klassen- und Eigenschaftenstruktur zu untersuchen und ausgewählte domänenspezifische Subklassen anzulegen.

Die praktische Demonstration erfolgt mit **Protégé Desktop**. Wenn Sie mit WebProtégé arbeiten, können einzelne Arbeitsschritte abweichen.

> **Was ist Protégé?**
>
> Protégé ist ein **kostenloser Open-Source-Ontologie-Editor** zur Erstellung, Bearbeitung und Verwaltung von Ontologien.
>
> Protégé unterstützt die **OWL 2 Web Ontology Language** (Sack, 2009) und bietet eine grafische Arbeitsumgebung zur Entwicklung formaler, maschinenlesbarer Ontologiestrukturen. (Stanford, 2026a)
>
> Protégé ist in zwei Varianten verfügbar: (Stanford, 2026c)
>
> - als Desktop-Anwendung ([**Protégé Desktop**](https://protege.stanford.edu/software/#desktop-protege))
> - als webbasierter Editor ([**WebProtégé**](https://protege.stanford.edu/software/#web-protege)).

---

## Protégé in diesem Tutorial

In diesem Tutorial dient **CIDOC CRM [Version 7.1.3, Februar 2024](https://cidoc-crm.org/get-last-official-release)** (CiDOC, 2024a) als **Referenzontologie** für die semantische Modellierung. Die Definitionen und Scope Notes helfen Ihnen dabei, die Bedeutung von Klassen und Eigenschaften zu untersuchen und Ihre Modellierungsentscheidungen fachlich zu begründen.

Für die praktische Arbeit in Protégé verwenden Sie **[Erlangen CRM / OWL](https://erlangen-crm.org/current-version)** (Schiemann, 2024), eine OWL-Implementierung von CIDOC CRM.

Entsprechend der in M2U1 vorgestellten Modellierungsstrategie werden Sie:

- **bestehende Klassen und Eigenschaften** in der Ontologie erkunden,
- **CIDOC-CRM-Eigenschaften wiederverwenden**, um Beziehungen abzubilden,
- **domänenspezifische Subklassen anlegen**, wenn eine weitere Spezialisierung erforderlich ist,
- und **die Modellierungsentscheidungen** hinter diesen Erweiterungen dokumentieren.

In diesem Tutorial werden keine neuen Eigenschaften eingeführt.

Das folgende Video zeigt die grundlegenden Arbeitsschritte, um eine bestehende Ontologie in Protégé zu erkunden und eine Subklasse anzulegen.

**Weiterführende Ressourcen**

Weitere Informationen und Anleitungen finden Sie auf der [**offiziellen Protégé-Webseite**](https://protege.stanford.edu/) (Stanford, 2026a):

- [**Protégé-Dokumentation**](https://protege.stanford.edu/support/#documentation) (Stanford, 2026c)
- [**Protégé-Wiki**](https://protegewiki.stanford.edu/wiki/Main_Page) (Stanford, 2022d)

---

# Videodemonstration

Das Video stellt drei grundlegende Arbeitsschritte in Protégé vor:

- **Starten:** Sie ihre Protégé Arbeitsumgebung.
- **Öffnen:** Sie eine bestehende OWL-Ontologie, z.B. Erlangen CRM 240920 basierend auf CIDOC-CRM 7.1.3 [http://erlangen-crm.org/240920](http://erlangen-crm.org/240920).
- **Erkunden:** Sie die Klassenhierarchie und Ontologieelemente.
- **Erweitern:** Sie die bestehende Ontologiestruktur durch domänenspezifische Sub-klassen.

Achten Sie beim Ansehen darauf, wie im Editor zwischen bestehenden Ontologieelementen und neu angelegten Klassen unterschieden wird.

**Sehen Sie sich den Arbeitsablauf an: Laden → Erkunden → Erweitern**

!?[Videodemonstration: Erste Schritte mit Protégé](../assets/Short_Protege_Intro.mp4)

---

## Ausblick

> **Wie geht es weiter?**
>
> Sie haben gelernt, wie Sie eine Ontologie in Protégé öffnen und erkunden.
>
> Im nächsten Schritt wenden Sie diese Arbeitsschritte auf die **Domäne der Computerspiele** an: Sie wählen geeignete CIDOC-CRM-Klassen und -Eigenschaften aus, ergänzen domänenspezifische Subklassen und modellieren deren Beziehungen.

---

## Bibliografie

(CIDOC, 2024a) CIDOC CRM Special Interest Group. (2024a). Definition of the CIDOC Conceptual Reference Model: Version 7.1.3. Retrieved 15 October 2026, from https://cidoc-crm.org/Version/version-7.1.3

(Sack, 2009) Sack, H. (2009). OWL 2 [Video recording]. Hasso Plattner Institut (HPI). Retrieved 15 October 2026, from  https://av.tib.eu/media/11276

(Schiemann, 2024) Schiemann, B., Oischinger, M., Götz, G., Merges, J., Fichtner, M., & Scholz, M. (o. D.). Erlangen CRM / OWL. Retrieved 15 October 2026, from https://erlangen-crm.org/

(Stanford, 2026a) Stanford Center for Biomedical Informatics Research. (2026a). Protégé. Retrieved 15 October 2026, from https://protege.stanford.edu/

(Stanford, 2026b) Stanford Center for Biomedical Informatics Research. (2026c). Software Protégé. Retrieved 15 October 2026, from https://protege.stanford.edu/software/

(Stanford, 2026c) Stanford Center for Biomedical Informatics Research. (2026b). Protégé Documentation. Retrieved 15 October 2026, from https://protege.stanford.edu/support/#documentation

(Stanford, 2022) Stanford Center for Biomedical Informatics Research. (2022). Protégé Wiki. Retrieved 15 October 2026, from https://protegewiki.stanford.edu/wiki/Main_Page























