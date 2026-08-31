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

> Im Mittelpunkt steht der **Workflow der formalen Modellierung**.

---

## Ausgangspunkt: Modell aus Modul 1

In Modul 1 wurde eine Modellskizze entwickelt, in der zentrale Konzepte und Beziehungen der Domäne Computerspiele beschrieben werden. 

Für diese Übung wird daraus ein kleiner Ausschnitt ausgewählt:

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

1. **Klassen auswählen und begründen**
2. **Beziehungen mit Properties modellieren**
3. **Entitäten und Literalwerte unterscheiden**

---

## Übung – Modell in Protégé umsetzen

**Arbeitsform:** Einzelarbeit oder Teams (2–4 Personen)

**Material:** Computer mit Protégé Desktop, bereitgestellte Erlangen-CRM-OWL-Datei, Modellskizze aus Modul 1 [Link]

**Zeit:** ca. 35 Minuten

---

**Aufgabe: Einen Ausschnitt des Domänenmodells in Protégé nachmodellieren**

Öffnet die bereitgestellte **Erlangen-CRM-Ontologie** (https://erlangen-crm.org/ontology/ecrm/ecrm_240307.owl) in Protégé und setzt den ausgewählten Ausschnitt des Modells aus Modul 1 schrittweise um.

---

### Schritt 1: CIDOC-CRM-Klassen prüfen

Sucht in Protégé die Klassen:

- **E73 Information Object**
- **E35 Title**
- **E55 Type**

Prüft jeweils die Definition beziehungsweise Scope Note.

Ordnet anschließend die Domänenbegriffe zu:

| Domänenbegriff     | mögliche CIDOC-CRM-Klasse | Begründung         |
| ------------------ | ------------------------- | ------------------ |
| Computer Game      | E73 Information Object    | __________________ |
| Game Title         | E35 Title                 | __________________ |
| Game Genre Type    | E55 Type                  | __________________ |
| Game Platform Type | E55 Type                  | __________________ |

**Prüft eure Auswahl:**

- Was beschreibt die CIDOC-CRM-Klasse?
- Passt diese Bedeutung zu unserem Domänenbegriff?
- Welche Aussage der Scope Note unterstützt eure Entscheidung?
- Sind alternative Zuordnungen denkbar?

> **Hinweis:** Nicht der Name einer Klasse entscheidet über ihre Eignung, sondern ihre Bedeutung im Referenzmodell.

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

---

### Schritt 3: Eine Beziehung auswählen und prüfen

Die erste fachliche Aussage lautet:

> Ein Computerspiel hat einen Titel.

Sucht die CIDOC-CRM-Property:

**P102 has title**

Prüft:

- die Definition beziehungsweise Scope Note,
- die **Domain**,
- die **Range**.

Übertragt eure Entscheidung in die Tabelle:

| Ausgangsklasse | Property       | Zielklasse | Aussage                            |
| -------------- | -------------- | ---------- | ---------------------------------- |
| Computer_Game  | P102 has title | Game_Title | Ein Computerspiel hat einen Titel. |

Entscheidet anschließend:

> Passt diese Property zu der Aussage, die ihr modellieren möchtet? Begründet kurz.

---

### Schritt 4: Beziehung in Protégé formalisieren

Übertragt die Beziehung als Klassenaxiom in Protégé.

Beispiel:

```text
Computer_Game
    SubClassOf:
        P102 has title some Game_Title
```

Vergleicht diese formale Aussage mit der ursprünglichen Modellskizze:

> Spiel → hat Titel → Titel

**Prüft:**

- Was ist gleich geblieben?
- Was ist durch die OWL-Formalisierung hinzugekommen?
- Welche Rolle spielt `some` in der formalen Aussage?

> **Hinweis:** In OWL werden Beziehungen zwischen Klassen nicht einfach als Pfeile eingezeichnet. Sie werden durch formale Axiome beziehungsweise Klassenrestriktionen beschrieben. Der Protégé Short Course behandelt genau diese Form der Klassenbeziehungen über Object Properties und existential restrictions (`SomeValuesFrom`).

---

### Schritt 5: Genre oder Plattform modellieren

Wählt **einen** der beiden Bereiche:

- Genre
- Plattform

Die fachliche Aussage lautet beispielsweise:

> Ein Computerspiel hat einen Genretyp.

Sucht die Property:

**P2 has type**

Prüft erneut Definition, Domain und Range.

Ergänzt anschließend in Protégé:

```text
Computer_Game
    SubClassOf:
        P2 has type some Game_Genre_Type
```

oder entsprechend:

```text
Computer_Game
    SubClassOf:
        P2 has type some Game_Platform_Type
```

> ---

---

### Schritt 6: Eine Datentyp-Eigenschaft untersuchen

Nun betrachten wir den konkreten Zeicheninhalt des Titels:

> „The Legend of Zelda: A Link to the Past“

Sucht die Property:

**P190 has symbolic content**

Vergleicht:

```text
Computer_Game
    → P102 has title
    → Game_Title
```

mit

```text
Game_Title
    → P190 has symbolic content
    → "The Legend of Zelda: A Link to the Past"
```

**Prüft:**

* Was befindet sich jeweils auf der rechten Seite der Beziehung?
* Welche Beziehung verbindet zwei Entitäten?
* Welche Beziehung führt zu einem Literalwert?

| Beispiel                   | Art der Beziehung    |
| -------------------------- | -------------------- |
| Computer_Game → Game_Title | Object Property      |
| Game_Title → Zeichenkette  | Datentyp-Eigenschaft |

> **Merksatz:** Object Properties verbinden Entitäten miteinander. Datentyp-Eigenschaften verbinden Entitäten mit Literalwerten wie Zeichenketten oder Zahlen.

Der Protégé Short Course unterscheidet entsprechend zwischen Classes, Object Properties, Data Properties, Individuals, Datatypes und Literals und behandelt Data Properties als eigenen Bestandteil der OWL-Modellierung.

---

## Modell prüfen

Vergleicht euer Ergebnis mit der ursprünglichen Modellskizze.

Die Struktur sollte vereinfacht folgende Aussagen enthalten:

```text
Computer_Game
│
├── P102 has title ───────→ Game_Title
│
│                           └── P190 has symbolic content
│                               → "The Legend of Zelda: A Link to the Past"
│
└── P2 has type ──────────→ Game_Genre_Type
                            oder
                            Game_Platform_Type
```

**Prüft eure Modellierung:**

* Sind die domänenspezifischen Klassen sinnvoll in die CIDOC-CRM-Hierarchie eingeordnet?
* Passen die Properties zur beabsichtigten Aussage?
* Stimmen Domain und Range?
* Können die Entscheidungen anhand der Scope Notes begründet werden?
* Lassen sich die Beziehungen weiterhin als verständliche Aussagen lesen?
* Welche Elemente stammen aus CIDOC CRM und welche wurden für die Domäne ergänzt?

---

## Modellierungsentscheidung dokumentieren

Dokumentiert für **eine** Zuordnung eure Entscheidung:

| Frage                                                | Antwort |
| ---------------------------------------------------- | ------- |
| Welchen Domänenbegriff modellieren wir?              |         |
| Welche CIDOC-CRM-Klasse oder Property verwenden wir? |         |
| Welche Bedeutung möchten wir ausdrücken?             |         |
| Was sagt die Scope Note dazu?                        |         |
| Warum halten wir die Zuordnung für geeignet?         |         |

> **Tipp:** Es geht nicht darum, eine einzig „richtige“ Lösung zu finden. Entscheidend ist, dass die Modellierungsentscheidung fachlich nachvollziehbar und mit dem verwendeten Referenzmodell vereinbar ist.

---

## Ergebnis: Vom Domänenmodell zur OWL-Ontologie

Am Ende dieser Übung liegt ein kleiner formal umgesetzter Ausschnitt des Domänenmodells **Computerspiele** vor.

Ihr habt:

* domänenspezifische Konzepte als **Subklassen** des CIDOC CRM angelegt,
* bestehende **CIDOC-CRM-Properties** geprüft und wiederverwendet,
* mindestens eine Beziehung als **OWL-Axiom** formalisiert,
* eine **Datentyp-Eigenschaft** untersucht beziehungsweise angewendet,
* und eine Modellierungsentscheidung anhand einer **Scope Note** begründet.

Speichert die erweiterte Ontologie anschließend als **OWL-Datei**.

> **Wichtig:** Die Ontologie ist weiterhin ein Modellausschnitt. Sie bildet nicht die gesamte Domäne Computerspiele ab, sondern dokumentiert exemplarisch den Weg von einer fachlichen Modellskizze zu einer maschinenlesbaren Ontologiestruktur.

---

## Ausblick

Mit dieser Übung wurde das in Modul 1 entwickelte Domänenmodell erstmals **formal in Protégé umgesetzt**.

Dabei wurden drei Ebenen miteinander verbunden:

> **fachliche Aussage → CIDOC-CRM-Modellierung → OWL-Formalisierung**

Die gespeicherte OWL-Datei bildet die Grundlage für **Modul 3**.

Dort wird die Ontologie in **WissKI** eingebunden. Die hier verwendeten Klassen und Properties werden anschließend im **WissKI Pathbuilder** zu semantischen Pfaden kombiniert und für die strukturierte Erfassung von Forschungsdaten verwendet.

Für Modul 3 benötigt ihr:

* die gespeicherte **OWL-Datei**,
* die verwendeten Klassen und Properties,
* sowie eure dokumentierten Modellierungsentscheidungen.

