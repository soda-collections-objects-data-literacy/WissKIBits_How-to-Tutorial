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

einheit: Anwendungsbeispiel: Objektsammlungen

description: Das SODa How-to-Tutorial vermittelt am Beispiel einer Computerspielsammlung Grundlagen und praktische Arbeitsschritte der ontologiegestützten Modellierung von Forschungsdaten. Die Lernenden entwickeln ein semantisches Datenmodell auf Grundlage des CIDOC CRM und setzen dieses schrittweise mit Protégé, Draw.io und WissKI um.

keywords: WissKI, CIDOC CRM, Ontologie, Domänenontologie, semantische Modellierung, Forschungsdaten, Forschungsdatenmanagement, OER

community: Wissenschaftliche Kommunikationsinfrastruktur (WissKI) und Sammlungen, Objekte, Datenkompetenzen (SODa)

PublicationDate: 2026-10-05

LearningResourceType: SODa How-to-Tutorial

-->

# WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul (M1): **Von der Sammlung über Modellierentscheidungen zum Diagramm – verstehen und erklären**

Übungseinheit (Ü1): **Anwendungsbeispiel: Objektsammlungen**  

**Dauer:** ~ 30 Min.

**Lernziele:**

Teilnehmende können...

- Kernentitäten (Objekt/Person/Ort/Zeit/Ereignis) einer Objektsammlung anwenden. (LZ-ID SODa\_03\_007\_0811)
- Datentyp-Eigenschaften des Referenzmodells CIDOC CRM benennen. (LZ-ID SODa\_03\_007\_0808) 


---

## Ziel und Szenario

Dies ist eine Praxiseinheit.

In dieser Übung greifen Sie die **konzeptuelle Modellskizze** aus der Aktivierungsübung wieder auf.

Am Beispiel von **„The Legend of Zelda: A Link to the Past“** werden ausgewählte Konzepte aus der Domäne Computerspiele untersucht und probeweise Klassen des **CIDOC CRM** zugeordnet.

Dabei geht es nicht darum, bereits ein vollständiges oder formal implementiertes CIDOC-CRM-Modell zu erstellen.

Vielmehr soll sichtbar werden, dass die Überführung von Domänenwissen in ein Referenzmodell **Modellierungsentscheidungen** erfordert.

Am Ende können die Teilnehmenden:

- ausgewählte Konzepte möglichen **CIDOC-CRM-Klassen (Entities)** zuordnen,
- die zugehörigen **Scope Notes** nachschlagen und prüfen,
- die Zuordnungen als **Modellierungsentscheidungen** beschreiben und begründen,
- eine erste **begründete CIDOC-CRM-Zuordnung** für einen kleinen Ausschnitt ihrer konzeptuellen Modellskizze entwickeln.

Die Modellskizze wird in den folgenden Modulen 2 und 3 schrittweise weiterentwickelt und für die Arbeit mit **Protégé** und **WissKI** formalisiert.

> **Transfer: Vom konzeptuellen Modell zu CIDOC CRM**
>
> Die in der Aktivierungsübung (M1E0A) entstandene Modellskizze wird nun weiterentwickelt.
>
> Ausgewählte Konzepte und Ereignisse werden mithilfe von CIDOC CRM beschrieben.
>
> Dabei geht es nicht darum, bereits ein vollständiges oder endgültiges CIDOC-CRM-Modell zu entwickeln.
>
> Entscheidend ist die Frage:
>
> **Was meinen wir mit einem Begriff – und welche CIDOC-CRM-Klasse beschreibt diese Bedeutung möglichst passend?**
>
> Ziel ist es, erste Modellierungsentscheidungen zu treffen, zu überprüfen und zu begründen.

---

## Ausgangspunkt: Modellskizze zu „Zelda“

Ausgangspunkt ist die **Modellskizze zu „The Legend of Zelda: A Link to the Past“**, die in der Aktivierungsübung entwickelt wurde.

An diesem Beispiel wurde untersucht, welche **Konzepte, Ereignisse und Beziehungen** für die Beschreibung eines Sammlungsobjekts und seines Kontextes relevant sein können. Die Modellskizze hält diese zunächst in eigenen Begriffen fest, einschließlich möglicher Beziehungen, bei denen noch Unsicherheiten bestehen.

Halten Sie Ihre ursprüngliche Modellskizze bereit, damit Sie Ihre ersten Überlegungen mit den Modellierungsentscheidungen vergleichen können, die Sie im Verlauf dieser Übung treffen.

> **Von der Modellskizze zu einem ersten CIDOC-CRM-Entwurf**
>
> Relevante Konzepte, Ereignisse und Beziehungen für das Beispielobjekt **„The Legend of Zelda: A Link to the Past“** wurden in der Aktivierungsübung (M1E0A) identifiziert.
>
> Nun betrachten Sie diese Modellskizze aus einer neuen Perspektive – **aus Sicht des CIDOC CRM**:
>
> - Welche Bedeutung haben die identifizierten Konzepte und Ereignisse im Kontext der Domäne?
> - Welche CIDOC-CRM-Klassen könnten diese Bedeutung ausdrücken?
> - Lassen sich die frei formulierten Beziehungen mithilfe von CIDOC-CRM-Properties ausdrücken?
> - Welche **Modellierungsentscheidungen** sind noch offen?
>
> Denken Sie daran: **Eine ähnliche Bezeichnung bedeutet nicht automatisch dieselbe Bedeutung.**
>
> In dieser Phase wird noch kein vollständiges oder formal implementiertes CIDOC-CRM-Modell erwartet. Ziel ist es, **eine erste, am CIDOC CRM orientierte Version des konzeptuellen Modells** zu entwickeln, die in Modul 2 weiter ausgearbeitet und formalisiert wird.

![Concept mind map](../WissKIBits_Modul1/assets/mindmap.png)

---

## CIDOC CRM als Referenzmodell

> **CIDOC CRM als Orientierung**
>
> CIDOC CRM stellt allgemeine Klassen und Eigenschaften für die Beschreibung von Kulturerbeinformationen bereit.
>
> Für die Modellierung bedeutet das:
>
> Domänenkonzept → Bedeutung klären → CIDOC CRM prüfen → Modellierungsentscheidung treffen
>
> Die Bezeichnung einer Klasse allein reicht für die Auswahl nicht aus. Entscheidend ist, ob ihre Scope Note zur beabsichtigten Bedeutung des Domänenkonzepts passt.

---

## Fokus dieser Modellierungsübung

Arbeiten Sie mit den drei Bereichen weiter, die bereits in der Aktivierungsübung eingeführt wurden:

- **Spieltitel**
- **Spielmerkmale** (z. B. Genre, wie Action-Adventure oder RPG, oder Plattform, wie Nintendo 64, PlayStation oder PC)
- **Narrative Elemente** (z. B. Beschreibung, Perspektive, wie First-Person oder Third-Person, oder Figuren wie Zelda)

Diese Bereiche dienen als Ausgangspunkt, um unterschiedliche Arten von **Konzepten und Ereignissen** zu erkennen und ihre **Beziehungen** zu formulieren.

Wählen Sie **zwei Elemente aus Ihrer Modellskizze** aus, deren Bedeutung interessante Fragen aufwirft.

Überlegen Sie beispielsweise, ob ein Begriff das Spiel als Informationsinhalt, ein physisches Spieleexemplar, eine Bezeichnung oder eine Klassifikation beschreibt.

Mithilfe von CIDOC CRM werden Sie diese Unterschiede genauer untersuchen.

Beispielsweise können folgende Fragen gestellt werden:

- Welchen **Titel** hat das Spiel?
- Welchem **Genre** oder welcher **Plattform** wird es zugeordnet?
- Welche **Personen oder Organisationen** waren beteiligt?
- Welche **Ereignisse** sind für das Spiel relevant?
- An welchen **Orten** und zu welchen **Zeiten** fanden diese Ereignisse statt?

> **Die Bedeutung festlegen**
>
> Wählen Sie aus Ihrer Modellskizze einige zentrale Elemente aus und fragen Sie:
>
> - Was genau bezeichnet unser Begriff?
> - Handelt es sich um ein Objekt, einen Informationsinhalt, eine Person, eine Gruppe, ein Ereignis, eine Benennung oder einen Typ?
> - Welche CIDOC-CRM-Klasse könnte dazu passen?
> - Was sagt die Scope Note dieser Klasse?
> - Entspricht sie tatsächlich der Bedeutung, die wir ausdrücken möchten?
> - Wo bleiben Unsicherheiten oder alternative Modellierungen?

---

## Übung – Orientierung mit CIDOC CRM

**Arbeitsform:** Einzelarbeit oder Kleingruppen (2–5 Personen)

**Material:** Modellskizze aus der Aktivierungsübung, Papier und Stift oder ein digitales Whiteboard sowie Zugang zur CIDOC-CRM-Dokumentation

**Zeit:** 20 Minuten

### Ausgangspunkt: Ihre Modellskizze

![Konzept-Mindmap](../WissKIBits_Modul1/assets/mindmap.png)

> **Abbildung:** Die Abbildung zeigt ein Musterbeispiel zur schrittweisen konzeptuellen Erschließung eines Sammlungs- oder Forschungsobjekts am Beispiel des Spiels **The Legend of Zelda: A Link to the Past**. Eigene Darstellung, erstellt mit ChatGPT (OpenAI), 2026.

Nutzen Sie Ihre Modellskizze aus der Aktivierungsübung als Ausgangspunkt. Untersuchen Sie nun **die beiden ausgewählten Elemente** und prüfen Sie, wie sich deren Bedeutung mithilfe des **CIDOC CRM** ausdrücken lässt.

---

### Aufgabe 1: Erste CIDOC-CRM-Zuordnungen untersuchen und begründen

Wählen Sie **zwei Konzepte oder Ereignisse** aus Ihrer Modellskizze aus. Gehen Sie für jedes ausgewählte Element die folgenden vier Schritte durch.

**Schritt 1 · Auswählen**

Wählen Sie ein Konzept oder Ereignis aus Ihrer Modellskizze aus, z. B. Spiel, Person, Organisation, Titel, Genre oder Produktion.

Klären Sie kurz, was der ausgewählte Begriff im Kontext Ihres Sammlungsobjekts genau bezeichnet.

**Schritt 2 · Zuordnen**

Suchen Sie für jedes ausgewählte Element eine CIDOC-CRM-Klasse, die zu seiner beabsichtigten Bedeutung passen könnte.

Nutzen Sie dazu folgende Ressourcen:

- **Offizielle CIDOC-CRM-Dokumentation, Version 7.1.3:** Das Dokument enthält die maßgeblichen Definitionen, Scope Notes, Klassenhierarchien und Eigenschaften. [Link](https://cidoc-crm.org/sites/default/files/cidoc_crm_version_7.1.3.pdf) (CIDOC, 2024a)
- **Webbasierter HTML-Navigator für CIDOC CRM:** Die offizielle Darstellung der **Version 7.1.3** eignet sich zum gezielten Nachschlagen. [Link](https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html) (CIDOC, 2024b)
- **CIDOC CRM Periodic Table:** Eine visuelle Orientierungshilfe, um Klassen, Eigenschaften und ihre Beziehungen zu erkunden. [Link](https://remogrillo.github.io/cidoc-crm_periodic_table) (RemoGrillo & claude, 2026)

**Beispiele für mögliche Ausgangspunkte:**

- E73 Information Object → Spiel als Informationsinhalt
- E22 Human-Made Object → physisches Spieleexemplar
- E21 Person → beteiligte Person
- E74 Group → Organisation oder Gruppe
- E12 Production → Produktionsereignis
- E35 Title → Titel
- E42 Identifier → Identifikator
- E55 Type → kontrollierte Klassifikation

**Schritt 3 · Überprüfen**

Lesen Sie die Scope Note der ausgewählten CIDOC-CRM-Klasse.

Fragen Sie sich:

- Beschreibt diese Klasse tatsächlich das, was wir mit unserem Begriff meinen?
- Stützt die Definition die vorgeschlagene Zuordnung?
- Gibt es alternative Klassen, die möglicherweise besser geeignet wären?

**Schritt 4 · Begründen**

Ergänzen Sie die vorgeschlagene CIDOC-CRM-Klasse in Ihrer Modellskizze und notieren Sie kurz, warum Sie diese Zuordnung gewählt haben.

Markieren Sie unsichere Zuordnungen mit einem Fragezeichen (?) und halten Sie fest, was noch unklar ist.

**Tipp:** Es geht nicht darum, möglichst viele CIDOC-CRM-Klassen zuzuordnen. Entscheidend ist, dass Sie wenige Modellierungsentscheidungen nachvollziehbar erklären und begründen können.

### Mini-Demo: CIDOC CRM als Baukastensystem

Die folgenden Klassen können als erste Orientierung für Ihre Untersuchung dienen.

| CIDOC-CRM-Klasse (Entity) | Bedeutung im Beispiel |
|---|---|
| **E73 Information Object** | Spiel als identifizierbarer Informationsinhalt |
| **E22 Human-Made Object** | Physisches Spieleexemplar (Modul, Disc, Verpackung …) |
| **E21 Person** | Beteiligte Person (z.B. Designer:in, Musiker:in) |
| **E74 Group** | Organisation oder Gruppe (z.B. Entwicklungsstudio, Publisher, Team) |
| **E12 Production** | Herstellung eines physischen Exemplars |
| **E42 Identifier** | Identifikatoren (z.B. Inventarnummern, Produktcodes) |
| **E35 Title** | Titel als eigenständige Benennung |
| **E41 Appellation** | Benennung, mit der etwas identifiziert oder bezeichnet wird |
| **E55 Type** | Kontrollierte Klassifikation (z.B. Genre, Plattform) |

Dies sind mögliche Ausgangspunkte und keine vorgegebenen Lösungen. Prüfen Sie immer die jeweiligen **Scope Notes**, bevor Sie entscheiden, ob eine Klasse für Ihre Modellierung geeignet ist.

---

### Aufgabe 2: Modellierungsentscheidungen vergleichen und diskutieren

Vergleichen Sie Ihre vorgeschlagenen CIDOC-CRM-Zuordnungen mit denen anderer Teilnehmender oder mit dem folgenden Musterbeispiel.

![Konzept-Mindmap](../WissKIBits_Modul1/assets/Mindmap.png)

> **Abbildung:** Beispiel einer Modellskizze zum Computerspiel **„The Legend of Zelda: A Link to the Past“**. Die Darstellung dient als Ausgangspunkt für die Diskussion von Modellierungsentscheidungen und ist nicht als einzig richtige Lösung zu verstehen.

**Diskutieren Sie die folgenden Fragen:**

- Haben Sie für ähnliche Begriffe dieselben CIDOC-CRM-Klassen ausgewählt?
- Falls sich Ihre Zuordnungen unterscheiden: Wie haben Sie die Bedeutung des ursprünglichen Begriffs jeweils interpretiert?
- Wie haben Ihnen die **Scope Notes** bei Ihren Entscheidungen geholfen?
- Welche Zuordnungen sind weiterhin unsicher?
- Würden Sie Konzepte oder Beziehungen in Ihrer ursprünglichen Modellskizze überarbeiten?

Überarbeiten Sie Ihre Modellskizze, wo dies sinnvoll erscheint, und halten Sie offene Fragen fest.

**Musterbeispiel: Vom Domänenmodell zur CIDOC-CRM-Modellierung**

Die in der Aktivierungsübung entstandene Modellskizze beschreibt zunächst die Konzepte, Ereignisse und Beziehungen der Beispieldomäne. Im nächsten Schritt können diese Elemente mithilfe von Klassen (Entities) und Eigenschaften (Properties) des CIDOC CRM weiter formalisiert werden.

Die Abbildung zeigt beispielhaft, wie aus einer solchen Modellskizze ein stärker formalisiertes semantisches Modell entstehen kann.

Dabei werden die zunächst frei formulierten Elemente und Beziehungen schrittweise auf CIDOC-CRM-Klassen und -Eigenschaften bezogen. Die Abbildung ist daher nicht als einzig mögliche Lösung zu verstehen, sondern als Modellierungsvorschlag, der überprüft und weiterentwickelt werden kann.

> **Zentrale Erkenntnis: Bedeutung modellieren**
>
> Semantische Modellierung bedeutet mehr, als Klassen mit ähnlichen Bezeichnungen zu finden.
>
> Eine geeignete CIDOC-CRM-Zuordnung hängt von der **beabsichtigten Bedeutung eines Begriffs**, den **Definitionen der ausgewählten Klassen** und den **Beziehungen, die ausgedrückt werden sollen**, ab.
>
> In dieser Phase entwickeln Sie eine erste, am CIDOC CRM orientierte Version Ihres konzeptuellen Modells – noch keine vollständige formale Ontologie.

---

### Ergebnis

Sie haben Ihre ursprüngliche konzeptuelle Modellskizze erneut betrachtet und ausgewählte Elemente mithilfe des **CIDOC CRM** untersucht.

**Ihre überarbeitete Modellskizze enthält nun:**

- relevante Domänenkonzepte und Ereignisse,
- erste Zuordnungen ausgewählter Elemente zu CIDOC-CRM-Klassen,
- explizite semantische Beziehungen,
- kurze Begründungen auf Grundlage der beabsichtigten Bedeutung und der jeweiligen Scope Notes,
- Hinweise auf unsichere oder noch offene Modellierungsentscheidungen.

Dies ist eine erste **CIDOC-CRM-orientierte Version Ihres konzeptuellen Modells**, noch keine vollständige formale Ontologie.

In **Modul 2** werden Sie diese Modellierungsentscheidungen überprüfen, weiterentwickeln und beginnen, ausgewählte Teile des Modells mithilfe von **Protégé** zu formalisieren.

---

## Von der Benennung zur Appellation

In unserer ersten Modellskizze können wir zunächst einfach formulieren:

> Spiel → hat eine Benennung → „The Legend of Zelda: A Link to the Past“

CIDOC CRM ermöglicht es, zwischen verschiedenen Formen der Benennung genauer zu unterscheiden.

**E41 Appellation** bezeichnet eine Benennung, mit der eine Instanz einer CRM-Klasse identifiziert oder bezeichnet werden kann.

Zwei speziellere Klassen sind in diesem Zusammenhang besonders relevant:

- **E35 Title:** Ein Titel, der einer Entität zugewiesen wurde oder für sie verwendet wird, beispielsweise der Titel eines Computerspiels.
- **E42 Identifier:** Ein Identifikator, der dazu dient, eine Entität innerhalb eines bestimmten Identifikationskontextes eindeutig zu unterscheiden, beispielsweise eine Inventarnummer.

Sowohl **E35 Title** als auch **E42 Identifier** sind Unterklassen von **E41 Appellation**. Sie beschreiben jedoch unterschiedliche Arten von Benennungen.

### Modellierbeispiel · Nicht jede Benennung ist dasselbe

In der konzeptuellen Modellskizze können wir zunächst formulieren:

> Spiel → hat eine Benennung → „The Legend of Zelda: A Link to the Past“

**Unterscheidung im CIDOC CRM:**

- **E41 Appellation** → allgemeine Benennung
- **E35 Title** → besondere Form einer Appellation: ein Titel
- **E42 Identifier** → besondere Form einer Appellation: ein Identifikator

Damit wird deutlich: Begriffe wie Benennung, Titel und Identifikator sind in CIDOC CRM nicht dasselbe, stehen aber in einem gemeinsamen konzeptionellen Zusammenhang.

> **Merksatz:**
>
> Ähnliche Bezeichnungen drücken nicht automatisch dieselbe Bedeutung aus. Prüfen Sie vor der Auswahl einer CIDOC-CRM-Klasse immer, ob ihre **Scope Note** der beabsichtigten Bedeutung des Konzepts in Ihrem Domänenmodell entspricht.

In dieser Übung geht es darum, diese Unterschiede zu erkennen und die entsprechenden **Modellierungsentscheidungen zu begründen**.

Die technische Darstellung von Appellationen, ihren Zeicheninhalten und den zugehörigen Datentyp-Eigenschaften wird in den folgenden Modulen, insbesondere in **Modul 3**, behandelt.

---

## Ausblick

In dieser Praxiseinheit haben Sie Ihre **konzeptuelle Modellskizze zur Domäne Computerspiele** erneut aufgegriffen und untersucht, wie ausgewählte Konzepte und Ereignisse mithilfe des **CIDOC CRM** beschrieben werden können.

Durch das Nachschlagen der **Scope Notes**, die Prüfung möglicher Klassenzuordnungen und die Diskussion von **Modellierungsentscheidungen** haben Sie einen ersten Schritt hin zu einem präziseren semantischen Modell unternommen. Am Beispiel von **E41 Appellation**, **E35 Title** und **E42 Identifier** wurde außerdem deutlich, weshalb die Bedeutung eines Begriffs für seine Zuordnung entscheidend ist.

> **Wie geht es weiter?**
>
> Sie haben Ihre konzeptuelle Modellskizze um erste **CIDOC-CRM-Zuordnungen** und **begründete Modellierungsentscheidungen** erweitert.
>
> **Modul 2:** Sie werden diese Entscheidungen überprüfen und weiterentwickeln sowie ausgewählte Teile des Modells mithilfe von **Protégé** als maschinenlesbare **OWL-Ontologie** formalisieren.
>
> **Modul 3:** Sie werden das semantische Modell nutzen, um eine **WissKI-Pathbuilder-Konfiguration** vorzubereiten und in WissKI zu importieren.
>
> Ihre Modellskizze bildet damit den **Ausgangspunkt für die weitere Modellierung**. Sie stellt noch keine vollständige formale Ontologie dar.

---

## Bibliografie

(CIDOC, 2024a) CIDOC CRM Special Interest Group. (2024). *Definition of the CIDOC Conceptual Reference Model: Version 7.1.3.* https://cidoc-crm.org/Version/version-7.1.3

(CIDOC, 2024b) CIDOC CRM Special Interest Group. (2024). *Classes & Properties Declarations of CIDOC-CRM version: 7.1.3.* https://cidoc-crm.org/html/cidoc_crm_v7.1.3.html

(RemoGrillo & claude, 2026) RemoGrillo & claude. (2026). *cidoc-crm_periodic_table.* https://github.com/RemoGrillo/cidoc-crm_periodic_table
