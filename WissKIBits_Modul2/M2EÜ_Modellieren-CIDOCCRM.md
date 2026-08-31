-->

# SODa WissKI Bits: Ontologiegestützte Modellierung von Forschungsdaten

**DATENMODELL ENTWICKELN UND IMPLEMENTIEREN AM BEISPIEL** 

Modul 2: **Modllieren mit CIDCO CRM – verstehen und anwenden**

Einheit 3: **Semantische Modellierung mit CIDOC CRM**  

**Dauer:** ~ 45 Min.

**Lernziele:**

Teilnehmende können...

* Ontologie zur Beschreibung von Ressourcen anwenden. (LZ-ID 03\_007\_0780)
* Scope Notes des Referenzmodells CIDOC CRM zur Beschreibung von Ressourcen anwenden. (LZ-ID SODa\_03\_007\_0780a)
* Methoden zur Modellierung mit CIDOC CRM benennen oder anwenden (?) SODa_03_007_0784a
* Datentyp-Eigenschaften des Referenzmodells CIDOC CRM anwenden. (LZ-ID SODa_03_007_xxxx)
* Software zur Erstellung von Ontologien anwenden. (LZ-ID SODa_03_007_0840)


---


## Ziel und Szenario

Dies ist eine Praxiseinheit. Ausgangspunkt ist das in Modul 1 entwickelte Modell der Domäne **Computerspiele**.

Am Beispiel von **„The Legend of Zelda: A Link to the Past“** wird untersucht, wie aus einer konzeptionellen Modellskizze eine **formale Ontologiestruktur** entsteht.

Dazu werden

- ausgewählte Konzepte aus dem Domänenmodell mit Klassen des **CIDOC CRM** abgeglichen,
- Modellierungsentscheidungen anhand von **Definitionen und Scope Notes** überprüft,
- domänenspezifische Konzepte als **Subklassen** in Protégé angelegt,
- Beziehungen mit bestehenden **CIDOC-CRM-Properties** formalisiert,
- und exemplarisch eine **Datentyp-Eigenschaft** verwendet.

Am Ende liegt ein kleiner, formal umgesetzter Ausschnitt des Domänenmodells als **OWL-Ontologie** vor.

Im Mittelpunkt steht der **Workflow der formalen Modellierung**.

---

## Ausgangspunkt: Modell aus Modul 1

In Modul 1 wurde eine Modellskizze entwickelt, in der zentrale Konzepte und Beziehungen der Domäne Computerspiele beschrieben werden:

![Konzept-Mindmap](../assets/Mindmap.png)

Für diese Übung wird daraus ein Ausschnitt ausgewählt:

> Computerspiel → **hat Titel** → Spieltitel
>
> Computerspiel → **hat Typ** → Genre
>
> Computerspiel → **hat Typ** → Plattformtyp

Die fachlichen Begriffe sollen nun mit CIDOC CRM und Protégé schrittweise formalisiert werden.

Dabei unterscheiden wir drei Ebenen:

| Ebene                    | Beispiel                                            |
| ------------------------ | --------------------------------------------------- |
| Fachliche Aussage        | Spiel hat Titel                                     |
| Semantische Modellierung | E73 Information Object – P102 has title – E35 Title |
| Formale OWL-Struktur     | `Computer_Game SubClassOf P102 some Game_Title`     |

---

## Fokus dieser Modellierungsübung

Der Fokus liegt auf drei grundlegenden Arbeitsschritten:

**Schritt 1: Klassen auswählen und begründen**

**Schritt 2: Unterklassen anlegen**

**Schritt 3: Prüft und dokumentiert**  

---

## Übung – Modell in Protégé umsetzen

**Arbeitsform:** Einzelarbeit oder Teams (2–4 Personen)

**Material:** Computer mit Protégé Desktop, bereitgestellte Erlangen-CRM-OWL-Datei, Modellskizze aus Modul 1 [Link]

**Zeit:** ~ 35 Min.

---

**Aufgabe: Einen Ausschnitt des Domänenmodells in Protégé nachmodellieren**

Öffnet die bereitgestellte **Erlangen-CRM-Ontologie** (https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl) in Protégé und setzt den ausgewählten Ausschnitt des Modells aus Modul 1 schrittweise um.

---

### Schritt 1: CIDOC-CRM-Klassen prüfen

Sucht in Protégé die passenden Klasse zum Domänenbegriff und prüft die Scope Note der Klasse.
Begründet die Auswahl.

**Beispiel**

> **E73 Information Object**
> **E35 Title**
> **E55 Type**


| Domänenbegriff     | mögliche CIDOC-CRM-Klasse | Begründung         |
| ------------------ | ------------------------- | ------------------ |
| Computer Game      | E73 Information Object    | __________________ |
| Game Title         | E35 Title                 | __________________ |
| Game Genre Type    | E55 Type                  | __________________ |
| Game Platform Type | E55 Type                  | __________________ |


**Hinweis:**

Nicht der Name einer Klasse entscheidet über ihre Eignung, sondern ihre Bedeutung im Referenzmodell.

**Leitfragen zur Überprüfung der Klasse können sein**

- Was beschreibt die CIDOC-CRM-Klasse?
- Passt diese Bedeutung zu unserem Domänenbegriff?
- Welche Aussage der Scope Note unterstützt eure Entscheidung?
- Sind alternative Zuordnungen denkbar?

---

### Schritt 2: Domänenspezifische Subklassen anlegen

Legt nun folgende Klassen als neue Subklassen an:

```text
E73 Information Object
└── Computer_Game

E35 Title
└── Game_Title

E55 Type
├── Game_Genre_Type
└── Game_Platform_Type
```

Prüft anschließend die Klassenhierarchie.


### Schritt 3: Prüft das Modell und dokumentiert 

Vergleicht euer Ergebnis mit der ursprünglichen Modellskizze.

**Prüft eure Modellierung:**

* Sind die domänenspezifischen Klassen sinnvoll in die CIDOC-CRM-Hierarchie eingeordnet?
* Passen die Properties zur beabsichtigten Aussage?
* Stimmen Domain und Range?
* Können die Entscheidungen anhand der Scope Notes begründet werden?
* Lassen sich die Beziehungen weiterhin als verständliche Aussagen lesen?
* Welche Elemente stammen aus CIDOC CRM und welche wurden für die Domäne ergänzt?

**Modellierungsentscheidung dokumentieren**

Dokumentiert für **eine** Zuordnung eure Entscheidung:

| Frage                                                | Antwort |
| ---------------------------------------------------- | ------- |
| Welchen Domänenbegriff modellieren wir?              |         |
| Welche CIDOC-CRM-Klasse oder Property verwenden wir? |         |
| Welche Bedeutung möchten wir ausdrücken?             |         |
| Was sagt die Scope Note dazu?                        |         |
| Warum halten wir die Zuordnung für geeignet?         |         |

**Hinweis:** 

Es geht nicht darum, eine einzig „richtige“ Lösung zu finden. Entscheidend ist, dass die Modellierungsentscheidung fachlich nachvollziehbar und mit dem verwendeten Referenzmodell vereinbar ist.

---

## Ergebnis: Vom Domänenmodell zur OWL-Ontologie

Am Ende dieser Übung liegt ein kleiner formal umgesetzter Ausschnitt des Domänenmodells **Computerspiele** vor.

Ihr habt:

- domänenspezifische Konzepte als **Subklassen** des CIDOC CRM angelegt,
- und eine Modellierungsentscheidung anhand einer **Scope Note** begründet.

Speichert die erweiterte Ontologie anschließend als **OWL-Datei**.

**Hinweis:** 

Die Ontologie ist weiterhin ein Modellausschnitt. Sie bildet nicht die gesamte Domäne Computerspiele ab, sondern dokumentiert exemplarisch den Weg von einer fachlichen Modellskizze zu einer maschinenlesbaren Ontologiestruktur.

MUSTERBEISPIEL einbinden: http://games.m-e-g-a.org/game_domain.rdf  

---

## Ausblick

Mit dieser Übung wurde das in Modul 1 entwickelte Domänenmodell erstmals **formal in Protégé umgesetzt**.

Dabei wurden drei Ebenen miteinander verbunden:

> **fachliche Aussage → CIDOC-CRM-Modellierung → OWL-Formalisierung**

Die gespeicherte OWL-Datei bildet die Grundlage für **Modul 3**.


