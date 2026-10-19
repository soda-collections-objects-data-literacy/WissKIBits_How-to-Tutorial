<!--
author: Canan Hastik (0000-0003-1729-4642)
author: Gudrun Schwenk (0009-0002-3156-8339)
email: info@igsd-ev.de
version:  v1.0.0
language: de
icon: https\://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/assets/SODa-Logo_full.svg
link: https\://raw.githubusercontent.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/refs/heads/main/soda.css
license: CC BY 4.0 <https\://creativecommons.org/licenses/by/4.0/>

comment: Dieser Fast Track ist Teil des How-to-Tutorials „Ontologiebasierte Modellierung von Forschungsdaten“. Anhand einer Computerspielsammlung bietet er erfahrenen Nutzenden einen kompakten, übungsorientierten Arbeitsablauf von der konzeptionellen Modellierung und Zuordnung zu CIDOC CRM über die Formalisierung einer Ontologie bis zur Konfiguration semantischer Pfade in WissKI.

title: WissKI Bits – Ontologiebasierte Modellierung von Forschungsdaten

module: Fast Track – Vom Sammlungsobjekt zu WissKI-Pfaden

unit: Übungsorientierte Schritt-für-Schritt-Anleitung für Fortgeschrittene

description: Dieser SODa-WissKI-Bits-Fast-Track führt erfahrene Nutzende durch die praktischen Schritte der ontologiebasierten Modellierung von Forschungsdaten. Anhand einer Computerspielsammlung erstellen sie eine konzeptionelle Modellskizze, ordnen ausgewählte Konzepte CIDOC CRM zu, formalisieren einen Ontologieausschnitt in Protégé, bereiten ein Draw.io-Diagramm vor und erzeugen und importieren semantische Pfade und Pfadgruppen in WissKI.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Collections, Objects, Data Literacy (SODa)

PublicationDate: 2026-10-05

LearningResourceType: How-to-Tutorial
-->

# WissKI Bits: Ontologiebasierte Modellierung von Forschungsdaten

**ENTWICKLUNG UND IMPLEMENTIERUNG EINES DATENMODELLS ANHAND EINES BEISPIELS**

**Fast Track: Vom Sammlungsobjekt zu WissKI-Pfaden**

**Eine übungsbasierte Schritt-für-Schritt-Anleitung für Fortgeschrittene**

**Zielgruppe:** Nutzerinnen und Nutzer, die mit den Grundlagen der semantischen Modellierung, dem CIDOC CRM und Ontologie-Editoren vertraut sind.

**Ziel:** Von einer konzeptionellen Skizze über einen kleinen OWL-Ontologieausschnitt und ein Draw.io-Diagramm zu importierten WissKI-Pfaden und Pfadgruppen gelangen.

Dieser Fast Track enthält die praktischen Aufgaben aus den Modulen 1–3. Erläuterungen, Definitionen, Quizfragen und ausführliche Screenshots finden Sie im vollständigen Tutorial.

**Beispiel:** **The Legend of Zelda: A Link to the Past**

**Dauer:** ca. 90 Min.

---

## Über diesen Fast Track

Dieser Fast Track führt die **fünf praktischen Übungen aus den Modulen 1–3** des WissKI Bits Tutorials zu einer zusammenhängenden Schritt-für-Schritt-Anleitung zusammen. 
Er folgt der ursprünglichen Reihenfolge und verwendet die **vorhandenen Übungsmaterialien**, darunter das vorbereitete Puzzle zum konzeptionellen Modell, das Computerspielbeispiel, Erlangen CRM, die Games-Ontologie, das Draw.io-Lückendiagramm und den gnm-service.

**Beispielobjekt: The Legend of Zelda: A Link to the Past**

Du beginnst mit einer konzeptionellen Modellskizze, untersuchst ausgewählte Zuordnungen zum CIDOC CRM, formalisierst einen kleinen Ausschnitt in Protégé, vervollständigst ein vorbereitetes Draw.io-Diagramm und wandelst dieses Diagramm in eine WissKI-Pathbuilder-Konfiguration um.

**Wichtig:** Die Aktivitäten beziehen sich auf dieselbe Domäne und denselben Modellierungsansatz, bilden jedoch keine automatische Verarbeitungskette von Datei zu Datei. 
Insbesondere beginnt die Draw.io-Übung mit einem **eigenen vorbereiteten Diagramm** und nicht mit einem Export der Ontologie, die Sie in Protégé bearbeiten.

**Zeitplan**

| Aktivität | Zeit |
|---|---:|
| Vorbereitung und Orientierung | 5 Min. |
| 1. Sammlungsobjekt untersuchen und konzeptionelle Skizze erstellen | 10 Min. |
| 2. Ausgewählte Konzepte dem CIDOC CRM zuordnen | 15 Min. |
| 3. Einen Modellausschnitt in Protégé formalisieren | 25 Min. |
| 4. Das Draw.io-Diagramm vervollständigen | 15 Min. |
| 5. WissKI-Pfade umwandeln und importieren | 20 Min. |
| **Gesamt** | **90 Min.** |

Der Zeitplan setzt voraus, dass Sie mit den Grundlagen der semantischen Modellierung vertraut sind und Zugang zu einer **vorbereiteten Arbeitsumgebung** haben. Bearbeiten Sie die nachfolgenden, klar abgegrenzten Aufgaben. Für weitere Erläuterungen oder vertiefende Übungen können Sie die verlinkten vollständigen Lerneinheiten heranziehen.

---

### Bevor Du beginnst — 5 Min.

Halten Sie Folgendes bereit:

- Einen Computer mit Internetzugang und [Draw.io / diagrams.net](https://app.diagrams.net/).
- [Protégé Desktop oder WebProtégé](https://protege.stanford.edu/), bereits verfügbar und einsatzbereit. Hilfe zur Installation finden Sie in der Tutorial-Einheit **M2U1A – Setup Protégé**.
- Zugang zu einer konfigurierten WissKI-Instanz mit einem geeigneten Adapter. Der [SODa Semantic Co-Working Space](https://manager.scs.sammlungen.io/de) ist eine Möglichkeit für die Tutorial-Umgebung.
- [Erlangen CRM 240307 (OWL)](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl), basierend auf CIDOC CRM 7.1.3.
- [CIDOC CRM 7.1.3 – Dokumentation und Scope Notes](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html).
- [Games-Domänenontologie](http://games.m-e-g-a.org/game_domain.rdf), die im WissKI-Arbeitsablauf des Tutorials verwendet wird.

Sie verwenden die vorhandenen vorbereiteten Dateien, sobald Sie in den folgenden Aufgaben dazu aufgefordert werden. **Beginnen Sie nicht damit, eine vollständig neue Ontologie oder ein neues Diagramm zu entwerfen.**

---

## 1. Das Sammlungsobjekt untersuchen - 10 Min.

*Basierend auf Modul 1, AKTIVIERUNG M1E1A: Anwendungsbeispiel: Objektsammlung · Vom Objekt zum konzeptionellen Modell*

**Ziel und Ausgangspunkt**

Beginne mit dem Sammlungsobjekt **The Legend of Zelda: A Link to the Past**. Frage dich: **Was musst du über dieses Objekt wissen und wie hängt dieses Wissen zusammen?** Verwende in dieser Phase die üblichen Fachbegriffe der Domäne und noch keine formalen CIDOC-CRM-Klassen.

Berücksichtige drei Bereiche aus der ursprünglichen Aktivierungsübung:

- **Spieltitel:** Wie wird das Spiel bezeichnet?
- **Spieleigenschaften:** Welche Genres, Plattformen oder anderen Klassifikationen sind relevant?
- **Narrative Elemente:** Welche Beschreibungen, Perspektiven oder Figuren sind relevant?

Akteure, Ereignisse, Orte und Zeiten kannst du einbeziehen, sofern sie zur Erklärung der ausgewählten Beziehungen beitragen. Unterscheide das Spiel als Inhalt von einem physischen Spieleexemplar, wenn dies für deine Aussagen relevant ist.

> **Schritt 1: Das Puzzle zum konzeptionellen Modell vervollständigen**
>
> 1. Öffne [Draw.io](https://app.diagrams.net/) und lade die vorbereitete [Puzzle-Vorlage (`puzzle.drawio_en.xml`)](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul1/assets/puzzle.drawio_en.xml) des Tutorials.
> 2. Untersuche die **vorgegebenen** Konzepte, Ereignisse und Beziehungen. Ordne und verbinde die relevanten Elemente zu einer sinnvollen konzeptionellen Modellskizze des Beispielobjekts.
> 3. Lies die Verbindungen als Aussagen: *Welche Entität steht mit welcher anderen Entität in welcher Beziehung?* Verwende aussagekräftige Beziehungsbezeichnungen.
> 4. Prüfe, ob jede Aussage durch die verfügbaren Objektinformationen gestützt wird. Kennzeichne ungeklärte oder unsichere Verbindungen mit `?`, anstatt Vermutungen anzustellen.
> 5. Erläutere kurz eine Beziehung und eine Unsicherheit in deiner Skizze.
>
> **Ergebnis:** Eine konzeptionelle Skizze, die ausgewählte Domänenkonzepte und Beziehungen sichtbar macht. **Ordne noch keine CIDOC-CRM-Klassen zu.**
>
> **Übergang zur nächsten Übung**
>
> Deine Skizze beschreibt Domänenwissen in vertrauten Begriffen. In der nächsten Übung prüfst du, ob ausgewählte Konzepte durch **bestehende CIDOC-CRM-Klassen** angemessen repräsentiert werden können und warum.

---

## 2. Ausgewählte Konzepte dem CIDOC CRM zuordnen — 15 Min.

*Basierend auf Modul 1, AKTIVIERUNG M1E1A: Anwendungsbeispiel: Objektsammlung · Vom Objekt zum konzeptionellen Modell*

**Ziel**

Verwende die konzeptionelle Skizze als Ausgangspunkt für **vorläufige** semantische Zuordnungen. Ein ähnlich klingender Klassenname reicht nicht aus: Vergleiche die beabsichtigte Bedeutung jedes Konzepts mit der **Scope Note** der jeweiligen Klasse.

![Konzept-Mindmap aus der Übung in Modul 1](../WissKIBits_Modul1/assets/mindmap_en.png)

> **Schritt 1: Erste Zuordnungen untersuchen und begründen**
>
> 1. Wähle **zwei Konzepte oder Ereignisse** aus deiner Skizze aus. Kläre, was diese jeweils im Sammlungskontext bedeuten.
> 2. Konsultiere die [CIDOC-CRM-Dokumentation](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html) und identifiziere mögliche Klassen. Je nach ausgewählten Konzepten können `E73 Information Object`, `E35 Title`, `E55 Type`, `E21 Person` oder `E74 Group` geeignete Ausgangspunkte sein.
> 3. Lies die **Scope Notes** und vergleiche die möglichen Klassen mit deinem Domänenkonzept. Berücksichtige dabei, was die jeweilige Klasse einschließt oder ausschließt.
> 4. Halte für jede Zuordnung eine kurze Begründung und eine offene Frage fest.

| Domänenkonzept aus deiner Skizze | Mögliche CIDOC-CRM-Klasse | Begründung anhand der Scope Note | Offene Frage |
|---|---|---|---|
| Konzept 1 | | | |
| Konzept 2 | | | |

> **Schritt 2: Modellierungsentscheidungen vergleichen**
>
> Diskutiere oder reflektiere kurz: Kann derselbe Domänenbegriff je nach Forschungsfrage unterschiedliche Dinge bezeichnen? Wird beispielsweise ein Name als Titel, als Identifikator oder als andere Art einer Benennung verwendet? Welche zusätzlichen Informationen würden die Mehrdeutigkeit auflösen?
>
> **Ergebnis:** Zwei **begründete, vorläufige Zuordnungen** und gegebenenfalls verbleibende Unsicherheiten. Dies ist eine semantische Modellierungsentscheidung und **noch keine OWL-Ontologie**.
>
> **Übergang zur nächsten Übung**
>
> Du hast den Unterschied zwischen einem Domänenkonzept und einer Klasse eines Referenzmodells untersucht. In Protégé wirst du nun ausgewählte Modellierungsentscheidungen als **domänenspezifische Unterklassen** bestehender CIDOC-CRM-Klassen explizit festlegen.

---

## 3. Einen kleinen Ontologieausschnitt in Protégé formalisieren — 25 Min.

*Basierend auf Modul 2, Übung M2E2A: Modellierung mit CIDOC CRM in Protégé.*

**Ziel**

Formalisiere einen **begrenzten Ausschnitt** der Computerspieldomäne. Folge der einfachen Erweiterungsstrategie des Tutorials: **Erstelle Unterklassen bestehender CIDOC-CRM-Klassen und verwende bestehende CIDOC-CRM-Eigenschaften wieder; definiere keine neuen Eigenschaften.**

![Konzept-Mindmap aus der Übung in Modul 2](../WissKIBits_Modul2/assets/Mindmap.png)

> **Schritt 1: Erlangen CRM laden**
>
> Öffne [Erlangen CRM 240307 OWL](https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl) in Protégé.
>
> Falls du eine Auffrischung zur Benutzeroberfläche benötigst, konsultiere die ursprüngliche [Übung aus Modul 2](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial) und das zugehörige Video zu den ersten Schritten.

> **Schritt 2: Relevante Klassen untersuchen**
>
> Suche die folgenden Klassen in der Hierarchie:
>
> - `E41 Appellation`
> - `E35 Title` (eine Unterklasse von `E41 Appellation`)
> - `E55 Type`
> - `E73 Information Object`
>
> Untersuche für jede Klasse ihre Position in der Hierarchie, ihre Annotationen und ihre **Scope Note**. Achte besonders auf den Unterschied zwischen einer allgemeinen Benennung und einem Titel.

> **Schritt 3: Ausgewählte Zuordnungen erneut prüfen**
>
> Vergleiche die konzeptionellen Entscheidungen aus Übung 2 mit den formalen Klassen in CIDOC CRM.
>
> Gehe nicht davon aus, dass eine Zuordnung allein deshalb korrekt ist, weil sich die Bezeichnungen ähneln.
>
> Die ursprüngliche Übung verwendet unter anderem folgende Beispiele:

| Domänenkonzept | Mögliche CIDOC-CRM-Klasse | Zu prüfende Frage |
|---|---|---|
| Spieltitel | `E35 Title` | Welcher Entität wird dieser Titel zugeordnet? |
| Spielgenre | `E55 Type` | Was genau wird klassifiziert? |
| Spielplattformtyp | `E55 Type` | Handelt es sich um eine Klassifikation des Spiels? |

> **Schritt 4: Domänenspezifische Unterklassen erstellen**
>
> Erstelle die ausgewählten Unterklassen unter den passenden CIDOC-CRM Klassen:
>
> - E73 Information Object → Computer_Game
> - E35 Title → Game_Title
> - E55 Type → Game_Genre_Type, Game_Platform_Type
>
> **Erstelle keine neuen CIDOC-CRM-Eigenschaften.** Diese Zeilen beschreiben das beabsichtigte Modell. Untersuche die entsprechenden Eigenschaften in Protégé und dokumentiere deine Entscheidungen, anstatt davon auszugehen, dass die Tabelle selbst die Beziehungen implementiert.

Verwende bestehende CIDOC-CRM-Eigenschaften, um die beabsichtigten Beziehungen auszudrücken. Die ursprüngliche Übung hebt folgende hervor:

| Ausgangsklasse | Bestehende Eigenschaft | Zielklasse | Beabsichtigte Aussage |
|---|---|---|---|
| `Computer_Game` | `P102 has title` | `Game_Title` | Ein Computerspiel hat einen Titel. |
| `Computer_Game` | `P2 has type` | `Game_Genre_Type` | Ein Spiel wird einem Genretyp zugeordnet. |
| `Computer_Game` | `P2 has type` | `Game_Platform_Type` | Ein Spiel wird einem Plattformtyp zugeordnet. |

> **Schritte 5–6: Überprüfen, dokumentieren und speichern**
>
> Prüfe, ob die Unterklassen unter geeigneten Oberklassen eingeordnet sind, ob die wiederverwendeten Eigenschaften die beabsichtigten Beziehungen ausdrücken und ob offene Fragen dokumentiert wurden. Speichere deine Arbeit wie in der ursprünglichen Übung beschrieben, wenn du den bearbeiteten Ontologieausschnitt aufbewahren möchtest.
>
> **Ergebnis:** Ein kleiner formalisierter und dokumentierter Ontologieausschnitt, **keine** vollständige Spieleontologie.
>
> **Übergang zur nächsten Übung**
>
> Die nächste Übung verwendet das **vorbereitete Draw.io-Lückendiagramm** aus Modul 3. Es stellt ausgewählte Klassen und Eigenschaften derselben Beispieldomäne dar, wird jedoch **nicht automatisch aus deiner Protégé-Datei erzeugt**. Du vervollständigst das Diagramm gemäß den Konventionen, die der Transformationsdienst voraussetzt.

---

## 4. Das Draw.io-Diagramm vervollständigen - 15 Min.

*Basierend auf Modul 3, Übung M3EÜ1: Visualisierung einer Domänenontologie als Diagramm.*

**Ziel**

Stelle zusammenhängende semantische Pfade mithilfe ausgewählter Ontologieklassen und bestehender CIDOC-CRM-Eigenschaften dar. Arbeite mit dem **vorbereiteten Lückendiagramm**, anstatt ein neues Modell von Grund auf zu zeichnen.

![Beispiel des Ontologiediagramms](../WissKIBits_Modul3/assets/MusterDrawio.png)

> **Schritt 1: Das vorbereitete Diagramm vervollständigen**
>
> 1. Lade das ursprüngliche [Draw.io-XML-Lückendiagramm (`Gruppe_B.drawio.xml`)](https://github.com/soda-collections-objects-data-literacy/WissKIBits_How-to-Tutorial/blob/main/WissKIBits_Modul3/assets/Gruppe_B.drawio.xml) herunter und öffne es in [Draw.io](https://app.diagrams.net/).
> 2. Identifiziere die fehlenden Knoten und Kanten und ersetze die temporären Platzhalter `(???)`.
> 3. Verwende die in der ursprünglichen Übung angegebenen Elemente **an den entsprechenden Stellen**, darunter `P102_has_title`, `P1 is identified by`, `P190 has symbolic content` und `mega:E41_Game_Character_Name`.
> 4. Verbinde die Klassen und Eigenschaften zu **vollständigen semantischen Pfaden**. Stelle sicher, dass jede Eigenschaftsbezeichnung der zugehörigen Kante zugeordnet ist. Füge keine einzelnen Spielinstanzen hinzu.
> 5. Untersuche die Attribute des zentralen Startknotens und der Gruppenknoten: `element_id`, `group_name` und `name`. Die ursprüngliche Übung nennt `Computer_Game` als Beispielwert für diese Attribute. Prüfe die Attribute der Endknoten anhand des **vorbereiteten Diagramms und der ursprünglichen Übung**, anstatt Werte zu erfinden.
> 6. Speichere oder exportiere das vervollständigte Diagramm als **Draw.io XML**.
>
> Ein in der ursprünglichen Übung dargestellter Pfad lautet:
>
> mega:E73_Computer_Game
>
> → P102_has_title
>
> → mega:E35_Game_Title
>
> → P190 has symbolic content
>
> → E62_String
>
> **Prüfung vor der Konvertierung:** Es sind keine `(???)`-Platzhalter mehr vorhanden; die Verbindungen sind vollständig; Klassen- und Eigenschaftsnamen sowie die erforderlichen Attribute sind konsistent; das Diagramm enthält **Klassen und Eigenschaften**, keine einzelnen Instanzen.
>
> **Ergebnis:** Ein vervollständigtes Draw.io-XML-Diagramm, das für den bestehenden gnm-service bereit ist.
>
> **Übergang zur nächsten Übung**
>
> Das Diagramm beschreibt semantische Pfade visuell. Der gnm-service wandelt seine XML-Repräsentation in eine **WissKI-Pathbuilder-XML-Konfiguration** um, die du anschließend in WissKI importierst und untersuchst.

---

## 5. WissKI-Pfade umwandeln und importieren - 20 Min.

*Basierend auf Modul 3, Übung M3EÜ2: Von Draw.io zu WissKI-Pfaden.*

**Ziel**

Wandle das vervollständigte Draw.io-Diagramm in Pathbuilder XML um, importiere die erzeugte **Konfiguration** in WissKI und vergleiche die importierten Pfade und Pfadgruppen mit dem Ausgangsdiagramm.

![Beispiel des WissKI Pathbuilders](../WissKIBits_Modul3/assets/pathbuilder.jpg)

> **Schritt 1: Das Draw.io-Diagramm umwandeln**
>
> 1. Öffne den [gnm-service: Draw.io diagrams to WissKI Pathbuilders](https://isl.ics.forth.gr/gnm_services/drawioXMLtoWisskiPathbuilder/).
> 2. Lade die **vervollständigte Draw.io-XML-Datei** aus Übung 4 hoch.
> 3. Starte die Transformation und untersuche die Antwort des Dienstes.
> 4. Kopiere oder speichere die URL der erzeugten **Pathbuilder-XML-Datei** für den Import in WissKI.
>
> Die aktuelle Dokumentation des Dienstes nennt **Erlangen CRM 240307** und die **Games-Ontologie** als unterstützte Ontologiegrundlage. Dieser Fast Track verwendet diese vorhandenen Ressourcen und erfordert keine Änderung des Dienstes.

> **Schritt 2: Die Ontologie in WissKI überprüfen**
>
> Melde dich bei deiner vorbereiteten WissKI-Instanz an und navigiere zu **WissKI → Configuration → WissKI Ontology**. Überprüfe den konfigurierten Adapter und die in der Instanz verfügbare Ontologie. Falls die benötigte Games-Ontologie nicht vorhanden ist, folge der ursprünglichen Übung und den Anweisungen für deine Instanz, um sie über den vorgesehenen Adapter zu laden:
>
> [Games-Domänenontologie](http://games.m-e-g-a.org/game_domain.rdf)
>
> **Wichtig:** Der Import von Pathbuilder XML importiert oder definiert **nicht** die Ontologie. Die referenzierten Klassen und Eigenschaften müssen bereits in der von WissKI verwendeten Ontologie verfügbar sein.

> **Schritt 3: Einen Pathbuilder erstellen und die XML-Datei importieren**
>
> 1. Navigiere zu **Configuration → Pathbuilders**.
> 2. Wähle **Add Pathbuilder**, vergib einen eindeutigen Namen und wähle den vorgesehenen Adapter.
> 3. Speichere und öffne den neuen Pathbuilder.
> 4. Suche **Pathbuilder Definition Import**, füge die erzeugte XML-URL ein und starte den Import.
> 5. Warte, bis die Pathbuilder-Struktur erscheint. **Überprüfe die Pfade, bevor du Bundles oder Felder erzeugst.**

> **Schritt 4: Die importierten Pfade und Pfadgruppen untersuchen**
>
> Suche die Beziehung:
>
> **Computer_Game → P102 has title → Game_Title**
>
> Prüfe, welche Pfadgruppe diese Beziehung enthält, identifiziere die Eigenschaft, die die Klassen verbindet, und vergleiche das Ergebnis mit dem Ausgangsdiagramm. Verwende die folgenden Fragen aus der ursprünglichen Übung als kurze Kontrolle:
>
> - Welche Pfadgruppe enthält diese Beziehung? (Suche nach **Computer Game**.)
> - Welche Eigenschaft verbindet die Ausgangs- und Zielklasse? (**P102 has title**.)
> - Entspricht der importierte Pfad deinem Ausgangsdiagramm? **Prüfe das tatsächliche Ergebnis**, anstatt anzunehmen, dass der Import die Korrektheit garantiert.

> **Schritt 5: Die erzeugten Pfade überprüfen**
>
> Vergleiche die importierte Pathbuilder-Konfiguration mit dem Draw.io-Diagramm. Prüfe, ob die erwarteten Pfadgruppen vorhanden sind, ob die relevanten Klassen und Eigenschaften enthalten sind und ob Pfade fehlen, unerwartet auftreten oder falsch gruppiert wurden. Dokumentiere alles, was gegebenenfalls im Diagramm oder in der Konfiguration korrigiert werden muss.
>
> **Ergebnis:** Eine erzeugte, importierte und **überprüfte WissKI-Pathbuilder-Konfiguration**. Dabei handelt es sich um einen Konfigurationsimport, nicht um einen Ontologieimport.

---

## Abschlusskontrolle

- [ ] Das vorbereitete Puzzle zum konzeptionellen Modell wurde vervollständigt und unsichere Beziehungen wurden identifiziert.
- [ ] Zwei vorläufige CIDOC-CRM-Zuordnungen wurden anhand der Scope Notes begründet.
- [ ] Ein ausgewählter Ontologieausschnitt wurde in Protégé mithilfe domänenspezifischer Unterklassen und **bestehender Eigenschaften** formalisiert.
- [ ] Das bereitgestellte Lückendiagramm `Gruppe_B.drawio.xml` wurde vervollständigt und als Draw.io XML gespeichert.
- [ ] Das Diagramm wurde mit dem bestehenden gnm-service umgewandelt.
- [ ] Die Pathbuilder-XML-Datei wurde importiert und die entstandenen Pfade und Pfadgruppen wurden in WissKI überprüft.

> **Nächster Schritt**
>
> Nach der Überprüfung der importierten Pathbuilder-Konfiguration kannst du mit der Erzeugung von Bundles und Feldern für die Dateneingabe und -anzeige in WissKI fortfahren, wie im vollständigen Tutorial beschrieben.

---

## Optionale Referenz: Beispieldateien des gnm-service

Der Dienst stellt zusätzliche Beispiele zur Überprüfung des Transformationsformats bereit. **Sie dienen als Referenz und sind keine zusätzlichen verpflichtenden Eingabedateien für diesen Fast Track.**

- [Beispiel einer Draw.io-XML-Eingabedatei](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/SODa_ISWC2025.drawio.xml) ([in diagrams.net öffnen](https://app.diagrams.net/#Uhttps%3A%2F%2Fisl.ics.forth.gr%2Fgnm_services%2Ffiles%2Fexamples%2Fdiagrams_to_pathbuilders%2FSODa_ISWC2025.drawio.xml#%7B%22pageId%22%3A%22iUIuGOhsytNMqk53lauw%22%7D); [PNG-Vorschau](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/SODa_ISWC2025.drawio.png)).
- [Optionale JSON-Konfiguration mit Standardwerten](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/config_defaults.json).
- [Beispiel einer Pathbuilder-XML-Ausgabedatei](https://isl.ics.forth.gr/gnm_services/files/examples/diagrams_to_pathbuilders/DrawioPathBuilderExampleOutput_ISWC2025.xml).

**Umfang:** Dieser Fast Track ist eine zeitlich begrenzte Auswahl und Verknüpfung der **bestehenden praktischen Übungen**. Er erfordert weder die Entwicklung eines neuen durchgängigen Modells von Grund auf noch eine Erweiterung des gnm-service. Für vertiefende Erläuterungen, optionale Aufgaben, vollständige Screenshots und weiterführende Reflexionen kannst du die entsprechenden ursprünglichen Einheiten (M1U0A, M1UE, M2UE, M3UE1 und M3UE2) konsultieren.




