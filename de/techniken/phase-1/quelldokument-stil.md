# Quelldokument als Stilvorlage

> *"Wir wissen, dass dieses Dokument von der Krankenkasse genehmigt wurde. Was ich eigentlich will, ist, dass die neuen Dokumente im selben Schreibstil entstehen."*

**Phase:** [Phase 1: Erfassen](../../phase-1-start.md)
**Baut auf:** [Transkription als Grundlage](transkription.md) und [Sprache bewahren](sprache-bewahren.md), jetzt mit dem Stil eines bestehenden Dokuments

---

## Wann ist das relevant?

**Situation:** Es gibt ein Dokument, das funktioniert. Genehmigt von den Beteiligten, akzeptabel für die Krankenkasse, wiedererkennbar für die Zielgruppe. Jetzt willst du neue Inhalte erstellen, aber im selben Stil.

**Die Tendenz:** Den Stil selbst nachzuahmen. Oder AI zu bitten, "im selben Stil wie dieses Beispiel zu schreiben." Das produziert oft generischen Output, der die Nuancen verfehlt.

**Das Prinzip:** Du musst die Stilmerkmale auspacken, bevor du sie klonen kannst. Struktur, Ton, Terminologie: das musst du explizit an AI weitergeben. Der Schlüssel ist nicht ein einzelner Prompt, sondern ein phasenweiser Ansatz.

**Die Frage:** Wenn du den Output neben das Original legst, erkennen die Beteiligten dann dieselbe Form, denselben Ton, dasselbe "das gehört zu uns"?

---

## Die Geschichte: Stilrichtlinien im Prompt

Ein regionales Netzwerk für psychische Gesundheitsversorgung (GGZ, das niederländische System für psychische Gesundheitsversorgung) stand vor einer Herausforderung. Sie mussten einen Transformationsplan für ihre Region schreiben. Es gab bereits einen genehmigten Plan aus einer anderen Region: 94 Seiten, akzeptiert von der Krankenkasse.

Die Frage: Wie erstellt man neue Teilpläne im selben Stil, basierend auf Live-Gesprächen mit Teilnehmenden?

Ich habe damit angefangen, AI den Schreibstil analysieren zu lassen. Das ging gut: AI identifizierte Struktur, Ton, Terminologie. Dann entwickelten wir Prompts für Live-Dokumentation während der Workshops.

Aber als ich die Prompts zurücklas (und das war ein klassischer "oh nein"-Moment), sah ich das Problem:

> "Schreibe im Stil des Referenz-Transformationsplans"

AI hätte während der Session keinen Zugriff auf dieses Referenzdokument. Der Prompt war unbrauchbar.

Die Korrektur war einfach, aber entscheidend: die Stilrichtlinien wörtlich in den Prompt aufnehmen. Nicht "schreib wie das Beispiel", sondern:

- Sprache: Formelles, geschäftliches Niederländisch
- Ton: Kollaborativ ("wir", "gemeinsam"), handlungsorientiert, pragmatisch
- Perspektive: Unter Berücksichtigung von "Bewohner", "Angehörige", "Fachkraft"
- Terminologie: IZA, GALA, MGN, POH-GGZ, positive Gesundheit, genesungsorientiert

Das war eine von mehreren Korrekturen in einem Prozess von zwölf Runden. Der Prompt entwickelte sich durch Feedback und Dialog: du gibst Feedback, AI passt an, du reagierst wieder. Dieses Hin und Her ist keine Randnotiz; es ist der Prozess. Mehr darüber, wie diese Zusammenarbeit funktioniert, in [Iteration als Dialog](../phase-2/iteration.md).

---

## Der Kern: Stilrichtlinien müssen IM Prompt stehen

So wie ich es sehe, ist das die wichtigste Lektion: Du kannst nicht "schreib wie das Beispiel" sagen, wenn AI dieses Beispiel nicht in seinem Kontextfenster (seinem Gedächtnis) hat.

Das klingt offensichtlich. Aber es ist eine Falle, in die ich selbst getappt bin. Meine ersten Prompts verwiesen auf "den Referenz-Transformationsplan", als könnte AI dieses Dokument während der Session konsultieren. Konnte es nicht.

Die Lösung: Die Stilmerkmale müssen explizit im Prompt stehen. Nicht als Verweis, sondern als Anweisung.

---

## Der Ansatz

### 1. Das Quelldokument analysieren

Bevor du einen Prompt schreiben kannst, musst du verstehen, was die Merkmale des genehmigten Dokuments sind.

**Was du analysierst:**

| Kategorie | Fragen |
|-----------|--------|
| **Struktur** | Welche Abschnitte wiederholen sich? In welcher Reihenfolge? Gibt es feste Elemente? |
| **Ton** | Formell oder informell? Kollaborativ oder direktiv? |
| **Terminologie** | Welcher Fachjargon wird konsistent verwendet? |
| **Formatierung** | Wie werden Listen, Tabellen, Abbildungen eingesetzt? |

**Der Analyse-Prompt:**

```prompt
Analysiere dieses Dokument und identifiziere:

1. Struktur: Welche Abschnitte wiederholen sich? In welcher Reihenfolge?
2. Ton: Formell/informell? Kollaborativ/direktiv?
3. Terminologie: Welcher Fachjargon wird konsistent verwendet?
4. Formatierung: Wie werden Listen, Tabellen, Abbildungen eingesetzt?

Gib konkrete Beispiele aus dem Dokument pro Kategorie.
```

**Beispiel: Analyse des Transformationsplans**

Das hat die Analyse für den Transformationsplan der psychischen Gesundheitsversorgung ergeben:

```
Struktur pro Teilplan:
Jeder Teilplan folgt einer festen Struktur:
- Einleitung
- Hauptziel
- Aktueller Stand
- Intervention
- Zielgruppe
- Effekte (nummerierte Liste)
- Beteiligte Partner (Aufzählungspunkte)
- Phasierung
- Vereinbarungen (SMART-Tabelle)
- Investition

Schreibstil:
- Formelles, geschäftliches Niederländisch
- Kollaborativ: häufige Verwendung von "wir", "gemeinsam", "zusammen"
- Handlungsorientiert, pragmatisch, lösungsorientiert

Terminologie:
- IZA, GALA, MGN, POH-GGZ, positive Gesundheit
- Orientierungsgespräch, Beratungstisch, Sozialkarte
- Domänenübergreifend, genesungsorientiert
```

### 2. Den Stil in deinen Prompt einbauen

Nimm die Stilmerkmale wörtlich in jeden Prompt auf, der Output generieren soll.

**Beispiel: eingebettete Stilrichtlinien**

```prompt
Schreibe im folgenden Stil:
- Sprache: Formell, geschäftlich
- Ton: Kollaborativ ("wir", "gemeinsam"), handlungsorientiert, pragmatisch
- Perspektive: Kooperierende Parteien, unter Berücksichtigung von
  "Bewohner", "Angehörige", "Fachkraft"
- Terminologie: [hier domänenspezifische Begriffe aus dem Quelldokument einfügen]
- Struktur: Klare Sätze, Aufzählungspunkte wo nötig
```

Dieser Block muss in jedem Prompt stehen, der im Zielstil schreiben soll.

### 3. Testen und verfeinern

Der erste Prompt ist selten der beste. Teste mit einem repräsentativen Transkript und gib Feedback:

- "Der Ton ist zu formell"
- "Das kollaborative Framing fehlt"
- "Die Terminologie stimmt nicht"

Lass AI den Prompt weiterentwickeln. Siehe [Iteration als Dialog](../phase-2/iteration.md) für den Ablauf dieses Prozesses.

---

## Die Prompts

Das sind die Prompts, die ich damals für Transformationsplan-Sessions verwendet habe. Sie sind umfangreicher als die Beispiele oben; das ist beabsichtigt. In der Praxis war dieses Detailniveau für konsistenten Output nötig.

Die drei Prompts unten passen zu einem phasenweisen Workshop: zuerst eine Zwischenreflexion, dann fortlaufende Verarbeitung, dann abschließende Synthese. Diese Reihenfolge ist kein Zufall. Durch die Trennung von Analyse und Synthese bleibt jeder Schritt überschaubar.

Das ist auch eine Vorschau auf [Phase 3: Skalierung](../../phase-3-skalierung.md), wo du mit mehreren Sessions oder Kleingruppen am selben Dokument iterierst.

### Zwischenreflexion zur Vision

**Kontext:** Direkt nach der ersten Diskussionsrunde. Die Gruppe hat gerade gesprochen; jetzt willst du zurückspiegeln: "Stimmt dieses Bild?"

**Was dieser Prompt über Quelldokument-Stil zeigt:**
- "Vorgeschriebener Schreibstil"-Block mit allen Stilmerkmalen
- Terminologie aus dem Quelldokument (IZA, GALA, MGN)
- Zweck des Outputs explizit angegeben

```prompt
**Prompt für Dembrane (Zwischenreflexion Vision - Universal)**

**Rolle:** Du bist ein AI-Assistent, der bei der Live-Dokumentation einer Transformationsplan-Session hilft. Deine Aufgabe jetzt ist es, den Kern der gerade geführten Visionsdiskussion zusammenzufassen, als direkte Rückmeldung an die Gruppe.

**Kontext:**
*   **Sessionteil:** Runde 1 - Diskussion zur 5-Jahres-Perspektive (Frage 1 Leitfaden).
*   **Output-Ziel:** Rückspiegelung an die Teilnehmenden am Tisch zur Validierung ("Stimmt dieses Bild?").

**Vorgeschriebener Schreibstil (konsistent anwenden):**
*   **Sprache:** Formell, geschäftlich.
*   **Ton:** Kollaborativ ("wir", "gemeinsam", "zusammen"), handlungsorientiert, pragmatisch, lösungsorientiert.
*   **Perspektive:** Geschrieben aus Sicht der kooperierenden Parteien, unter Berücksichtigung der Perspektive von "Bewohner", "Angehörige", "Fachkraft".
*   **Terminologie:** Korrekten und relevanten Fachjargon aus dem Gesundheits- und GGZ-Bereich verwenden (wie IZA, GALA, MGN, POH-GGZ, positive Gesundheit, genesungsorientiert, domänenübergreifend usw.) wo angemessen.
*   **Struktur:** Klare Sätze verwenden, Aufzählungspunkte wo nötig.

**Anweisungen:**
1.  **Identifiziere das primäre Thema**, das in diesem Transkriptfragment diskutiert wird. Wähle aus: 'Sozialkarte', 'Beratungstisch/Übergabetisch' oder 'Orientierungsgespräch'. Stütze deine Wahl auf Schlüsselwörter und den Kontext der Visionsdiskussion. Wenn das Thema nicht klar bestimmt werden kann, notiere 'Thema unklar' und stoppe.
2.  **Erstelle eine knappe, narrative Zusammenfassung** der gemeinsamen 5-Jahres-Vision für das **identifizierte Thema**. Formuliere diese Zusammenfassung streng gemäß dem **Vorgeschriebenen Schreibstil**. Fokussiere auf die gewünschte Zukunftsvision und die beabsichtigten Ergebnisse.
3.  **Extrahiere eine Liste von 3-5 entscheidenden Komponenten oder Elementen**, die laut Teilnehmenden unbedingt in dieser 5-Jahres-Vision für das **identifizierte Thema** enthalten sein müssen. Präsentiere dies als klare Aufzählungsliste unter der Zusammenfassung.
4.  **Prüfe auf genannte KPIs** oder messbare Ergebnisse im Zusammenhang mit der Vision und nimm diese in die Zusammenfassung oder die Liste entscheidender Komponenten auf.

**Input-Transkript:**
[Hier das relevante Transkriptfragment der Visionsdiskussion von diesem Tisch einfügen]

**Output-Format:**
**Identifiziertes Thema:** [Sozialkarte / Beratungstisch/Übergabetisch / Orientierungsgespräch / Thema unklar]

**(Wenn Thema identifiziert):**
**Entwurf Vision [Identifiziertes Thema] (zur Validierung):**
[Hier kommt die narrative Zusammenfassung im vorgeschriebenen Schreibstil]

**Entscheidende Visionskomponenten:**
*   [Entscheidende Komponente 1]
*   [Entscheidende Komponente 2]
*   [Entscheidende Komponente 3]
*   ...
```

*Das ist der Prompt, den ich damals für Transformationsplan-Sessions verwendet habe.*

---

### Fortlaufende Verarbeitung & Fragen

**Kontext:** Während des Workshops. Kernpunkte extrahieren und Fragen für die nächste Gruppe generieren.

**Was dieser Prompt zeigt:**
- Stilrichtlinien eingebettet im Prompt
- Tagging-System für spätere Synthese
- Output auf Weitergabe an die nächste Runde ausgerichtet

```prompt
**Prompt für Dembrane (Fortlaufende Verarbeitung & Fragen - Universal)**

**Rolle:** Du bist ein AI-Analyst und Redakteur, der Live-Gespräche für einen Transformationsplan der psychischen Gesundheitsversorgung verfolgt. Deine Aufgaben sind das Extrahieren von Kernpunkten und das Identifizieren von Fragen für die weitere Diskussion.

**Vorgeschriebener Schreibstil (für alle formulierten Kernpunkte):**
*   **Sprache:** Formell, geschäftlich.
*   **Ton:** Kollaborativ ("wir", "gemeinsam"), objektiv beim Zusammenfassen.
*   **Terminologie:** Korrekten und relevanten Fachjargon verwenden (IZA, MGN usw.) wo angemessen.

**Anweisungen:**
1.  Analysiere das beigefügte Transkriptfragment.
2.  **Identifiziere das primäre Thema**, das diskutiert wird ('Sozialkarte', 'Beratungstisch/Übergabetisch', 'Orientierungsgespräch') oder notiere 'Thema unklar'.
3.  **Extrahiere die wichtigsten inhaltlichen Punkte:**
    *   Genannte Visionselemente, Ziele, Probleme.
    *   Vorgeschlagene Aktionen, Schritte, Lösungen.
    *   Genannte Voraussetzungen, benötigte Partner.
    *   Wichtige Einigungspunkte oder Diskussions-/Meinungsverschiedenheitspunkte.
    *   Genannte KPIs oder messbare Ergebnisse.
4.  **Formuliere diese Kernpunkte knapp.** Versuche, jeden Punkt mit dem identifizierten Thema und einem möglichen Abschnitt des Transformationsplans zu **taggen** (z.B. `[Thema: Sozialkarte, Abschnitt: Vision]`, `[Thema: Beratungstisch, Abschnitt: Phasierung]`, `[Thema: Orientierungsgespräch, Abschnitt: Voraussetzungen]`, `[Thema: Allgemein, Abschnitt: KPI]`). Verwende den **Vorgeschriebenen Schreibstil** für diese Punkte.
5.  **Analysiere die Diskussion im Fragment:** Wo stockt das Gespräch? Welche Punkte bleiben unklar? Wo besteht ein klarer Bedarf an Input oder Entscheidung durch die nächste Gruppe?
6.  **Generiere 1 oder 2 konkrete, offene Fragen**, die der nächsten Gruppe helfen können, auf diesem Gespräch aufzubauen oder Engpässe zu lösen. Die Fragen müssen direkt aus der Analyse in Schritt 5 hervorgehen.

**Input-Transkript:**
[Hier das zu verarbeitende Transkriptsegment einfügen]

**Output-Format:**
**Identifiziertes Thema:** [Sozialkarte / Beratungstisch/Übergabetisch / Orientierungsgespräch / Thema unklar]

**Kernpunkte aus diesem Fragment:**
*   [Kernpunkt 1 im vorgeschriebenen Stil formuliert] `[Tag: Thema, Abschnitt]`
*   [Kernpunkt 2 im vorgeschriebenen Stil formuliert] `[Tag: Thema, Abschnitt]`
*   [KPI 1 genannt] `[Tag: Thema, Abschnitt: KPI]`
*   ...

**Vorgeschlagene Fragen für die nächste Gruppe:**
1.  [Frage 1]
2.  [Frage 2 (optional)]
```

*Das ist der Prompt, den ich damals für Transformationsplan-Sessions verwendet habe.*

---

### Abschließende Synthese pro Thema

**Kontext:** Am Ende. Alle Runden sind gelaufen; jetzt in einen Entwurf-Teilplan konsolidieren.

**Was dieser Prompt zeigt:**
- Vollständige Stilrichtlinien (Sprache, Ton, Perspektive, Terminologie, Struktur)
- Struktur vom Quelldokument übernommen
- Raum für "fehlende Informationen"

```prompt
**Prompt für Dembrane (Abschließende Synthese Teilplan pro Thema - Universalvorlage)**

**Rolle:** Du bist der Chefredakteur, der den Input des gesamten Workshops in einen Entwurf-Teilplan für den Transformationsplan [Name Neue Region] konsolidiert.

**Kontext:**
*   **Thema dieser Synthese:** [Themaname - **Muss bei Ausführung angegeben werden!**, z.B. 'Orientierungsgespräch']
*   **Sessionteil:** Ende des Workshops - Konsolidierung aller Runden für das angegebene Thema.
*   **Output-Ziel:** Ein kohärenter Entwurf-Teilplan für das angegebene Thema, bereit zur weiteren Bearbeitung.

**Vorgeschriebener Schreibstil (konsistent auf den gesamten Output anwenden):**
*   **Sprache:** Formell, geschäftlich.
*   **Ton:** Kollaborativ ("wir", "gemeinsam", "zusammen"), handlungsorientiert, pragmatisch, lösungsorientiert.
*   **Perspektive:** Geschrieben aus Sicht der kooperierenden Parteien, unter Berücksichtigung der Perspektive von "Bewohner", "Angehörige", "Fachkraft".
*   **Terminologie:** Korrekten und relevanten Fachjargon aus dem Gesundheits- und GGZ-Bereich verwenden (wie IZA, GALA, MGN, POH-GGZ, positive Gesundheit, genesungsorientiert, domänenübergreifend usw.) wo angemessen für dieses Thema.
*   **Struktur:** Der Teilplanstruktur folgen (siehe Anweisungen). Klare Überschriften, Zwischenüberschriften, Aufzählungspunkte und nummerierte Listen verwenden wo zutreffend.

**Anweisungen:**
1.  Sammle alle Kernpunkte und KPIs, die während des Workshops mit dem **'Thema dieser Synthese'** getaggt wurden (aus den Outputs von Prompt 2).
2.  **Strukturiere diese Informationen** in einen Entwurf-Teilplan für dieses Thema. Verwende die folgenden Abschnitte als Leitfaden und fülle sie mit den relevanten getaggten Informationen:
    *   **Einleitung:** Kontext, Bedeutung dieses Themas (relevante Kernpunkte kombinieren).
    *   **Hauptziel:** Was will man mit diesem Thema erreichen? (Aus relevanten Kernpunkten synthetisieren).
    *   **Intervention:** Beschreibung des Ansatzes/der Lösung für dieses Thema (Aus relevanten Kernpunkten synthetisieren).
    *   **Effekte:** Was bringt es? Erstelle eine nummerierte Liste. **Integriere die KPIs logisch**, die für dieses Thema notiert wurden und mit Effekten verknüpft werden können.
    *   **Beteiligte Partner:** Wer wurde als relevant für dieses Thema genannt? (Erstelle eine Aufzählungsliste).
    *   **Phasierung [Thema dieser Synthese]:** Beschreibe die Schritte, Aktionen, Ergebnisse pro Phase wie für dieses Thema besprochen. **Integriere KPIs logisch**, die mit bestimmten Schritten/Phasen verknüpft werden können. (Erstelle eine strukturierte Liste, z.B. pro Phase).
    *   (Füge optional Abschnitte wie 'Voraussetzungen', 'Aktueller Stand', 'Zielgruppe', 'Investition' hinzu, wenn genügend getaggte Informationen verfügbar sind).
3.  Stelle einen **logischen Fluss und Kohärenz** sicher. Schreibe die extrahierten Punkte in Fließtext innerhalb jedes Abschnitts um und verbinde sie, gemäß dem **Vorgeschriebenen Schreibstil**.
4.  Sei explizit darüber, wo Informationen für diesen Teilplan noch fehlen oder weiter ausgearbeitet werden müssen (z.B. "SMART-Ziele noch zu konkretisieren", "Finanzierung/Investition noch nicht besprochen").

**Input:**
[Verweise auf die gesammelten Outputs von Prompt 2, speziell die Kernpunkte, die mit dem 'Thema dieser Synthese' getaggt sind]

**Output-Format:**
**Entwurf-Teilplan: [Thema dieser Synthese]**

**(Folge der Struktur wie in Anweisung 2 beschrieben, mit allem Text im Vorgeschriebenen Schreibstil)**

**Anmerkungen/Fehlende Informationen:**
*   [Punkt 1]
*   [Punkt 2]
```
*Das ist der Prompt, den ich damals für Transformationsplan-Sessions verwendet habe.*

**Warum diese Struktur funktioniert:**

Jeder Prompt oben folgt derselben Struktur, die die Technik des Quelldokument-Klonens anwendet:

- "Stilrichtlinien im Prompt": Jeder Prompt enthält explizit Sprache, Ton, Terminologie und Struktur. AI muss nicht raten.
- "Phasenweiser Ansatz": Nicht alles auf einmal. Zwischenreflexion, fortlaufende Verarbeitung, abschließende Synthese: drei separate Prompts für drei separate Ziele.
- "Kontext mitgeliefert": Jeder Prompt sagt AI, was das Ziel ist ("Reflexion zur Validierung", "Konsolidierung in Entwurf-Teilplan") und welchen Input er erhält.
- "Terminologie übernommen": Die Prompts verwenden dieselben Begriffe wie das Quelldokument (IZA, GALA, MGN usw.) statt generischer Alternativen.

Das macht die Prompts reproduzierbar. Wenn du die Stilrichtlinien an dein Quelldokument anpasst, kannst du dieselbe Struktur für andere Prozesse verwenden.

---

## Spannungen

**"Schreib wie dieses Beispiel" ohne Analyse**
Der Reflex ist zu sagen "schreib im selben Stil wie dieses Dokument." Aber AI weiß dann nicht, was die Merkmale sind, die den Stil ausmachen. Das Ergebnis verfehlt genau die Nuancen, die das Original akzeptabel gemacht haben.

*Was ich mache:* Ich analysiere zuerst. Was macht dieses Dokument akzeptabel? Struktur? Ton? Terminologie? Ich kodiere diese Merkmale explizit in den Prompt.

**Stilrichtlinien bei jedem Prompt vergessen**
Du machst eine gute Analyse, aber AI "vergisst" den Stil in jedem neuen Gespräch. Das Kontextfenster fängt wieder bei null an.

*Was ich mache:* Ich nehme die Kernrichtlinien in jeden Prompt auf. Oder ich arbeite mit einem Master-Prompt, der den Kontext setzt.

**Erst Analyse, dann Synthese**
Die Versuchung ist, alles in einen Prompt zu packen: Analyse, Synthese, Strukturierung und Stilanpassung gleichzeitig. Aber dann wird es für AI zu komplex und du verlierst Details, die du vielleicht bewahren möchtest.

*Was ich mache:* Ich teile in Phasen auf. Während eines Live-Workshops hatte ich zuerst eine Zwischenreflexion, dann Feedback-Verarbeitung, dann abschließende Synthese. Jede mit eigenem Prompt. Durch die Trennung von Analyse und Synthese bleibt jeder Schritt überschaubar und detailliert. Und du kannst leichter sehen, ob du auf etwas aufbaust, das du wiedererkennst, oder ob viel Detail verloren geht.

Das ist auch eine Vorschau auf [Phase 3: Skalierung](../../phase-3-skalierung.md), wo du mit mehreren Sessions oder Kleingruppen am selben Dokument iterierst.

**Stil versus Authentizität**
Es gibt eine Spannung zwischen dem offiziellen Stil und der authentischen Stimme der Teilnehmenden. Das Dokument muss für die Krankenkasse akzeptabel sein, aber auch wiedererkennbar für die Menschen, die das Gespräch geführt haben.

*Was ich mache:* Stilrichtlinien für Struktur und Ton, aber Zitate und Kernformulierungen der Teilnehmenden bleiben intakt. Und Feedbackschleifen eingebaut: "Schau, das ist ein Entwurf-Teilplan mit euren Worten, aber im Format des Endergebnisses." Dann können die Leute reagieren und steuern, bevor es endgültig wird.

---

## Sicherheits-Checkliste

- [ ] Quelldokument-Struktur analysiert?
- [ ] Stilrichtlinien explizit im Prompt?
- [ ] Terminologie aus Quelldokument übernommen?
- [ ] Ton spezifiziert (formell, kollaborativ usw.)?
- [ ] Output-Format klar definiert?
- [ ] Raum für fehlende Informationen angegeben?

---

## Tools

| Tool | Wofür |
|------|-------|
| **Dembrane** | Live-Transkription + Prompt-Ausführung während Sessions |
| **Claude/ChatGPT** | Quelldokument-Analyse + Prompt-Entwicklung |

---

## Verwandte Techniken

- [Transkription als Grundlage](transkription.md): woher das Rohmaterial kommt
- [Sprache bewahren](sprache-bewahren.md): die Sprache innerhalb des Stils
- [Iteration als Dialog](../phase-2/iteration.md): die vollständige Geschichte der zwölf Runden

---

← [Zurück: Sprache bewahren](sprache-bewahren.md) | [Zurück zu Phase 1: Erfassen](../../phase-1-start.md) | [Weiter: Phase 2: Vertiefung →](../../phase-2-vertiefung.md)

---

*"Du kannst nicht 'schreib wie das Beispiel' sagen, wenn AI dieses Beispiel nicht hat. Der Stil muss im Prompt stehen."*
