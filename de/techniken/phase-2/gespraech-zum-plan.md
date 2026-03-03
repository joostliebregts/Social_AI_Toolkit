# Vom Gespräch zum Umsetzungsplan

> *Erzeuge Live-Output, den die Teilnehmenden direkt vor Ort bewerten können.*

**Phase:** [Phase 2: Vertiefung](../../phase-2-vertiefung.md)
**Baut auf:** [Quelldokument als Stilvorlage](../phase-1/quelldokument-stil.md), jetzt als Live-Dokumentation während Sitzungen

---

## Wann ist das relevant?

**Situation:** Du facilitierst eine strategische Sitzung. Teilnehmende teilen ihre Perspektiven. Normalerweise würdest du einen Tag lang nachbearbeiten: Haftnotizen sortieren, einen Entwurf schreiben, Feedback einsammeln.

**Die Tendenz:** Den Prozess als gegeben akzeptieren. Nach der Sitzung einen Tag für die Verarbeitung einplanen, weil "das schon immer so war". Die Annahme, dass Qualität Abstand braucht; dass man eine Nacht darüber schlafen muss. Und wahrscheinlich auch: der Zweifel, ob AI es genauso gut kann wie du selbst.

**Das Prinzip:** AI kann Entwurfs-Output während der Sitzung selbst generieren. Leute sehen ihre Worte sofort zurückgespiegelt, strukturiert in der Form, die die Organisation braucht. Die Feedbackschleife schrumpft von Tagen auf Minuten.

**Die Frage:** Was wäre, wenn Leute ihren Input sofort als Entwurfsdokument zurücksehen könnten?

**Der Unterschied zu [Live-Reflexion](live-reflexion-mit-ai.md):** Dort nutzt du AI für Reflexionsfragen *während* des Gesprächs, um Wendungen zu erzeugen. Hier nutzt du AI, um *Dokumentation* aus dem Gespräch zu generieren. Beides kann in derselben Sitzung passieren: der Echo-Knopf für Wendungen und diese Technik für Output.

**Das ist eine Semi-Live-Methode.** Nicht in Echtzeit wie der Echo-Knopf (direkt im Gespräch), sondern zwischen Blöcken: während Pausen oder Teilsitzungen. Du brauchst etwa 1-2 Minuten, um einen Prompt zu starten und die Ausgabe zu prüfen, bevor du sie der Gruppe zeigst.

---

## Die Geschichte: 1 Tag zu 1 Minute

Wir haben dieses Prinzip für den Transformationsplan des Netzwerks für psychische Gesundheitsversorgung (GGZ, das niederländische System für psychische Gesundheitsversorgung) in Centraal Gelderland angewandt. Es funktionierte, weshalb wir es danach auch in Amsterdam angewandt haben.

Ein Beispiel aus Gelderland. Dreißig Teilnehmende geben Input für einen Transformationsplan für das Netzwerk für psychische Gesundheitsversorgung. Der alte Prozess:

1. Live-Sitzung: Leute arbeiten in Kleingruppen
2. Haftnotizen an Wänden
3. **Ein Tag Verarbeitung**: Facilitatoren clustern und schreiben einen Entwurf
4. Review durch ein 10-Personen-Team
5. Finale Integration

Die Frage: was wäre, wenn AI dieses Entwurfsdokument direkt aus dem Gespräch generieren könnte?

Die Antwort wurde ein Live-Workflow:
- Transkription läuft parallel zur (originalen) faciliierten Sitzung, bei der Haftnotizen verwendet werden.
- Während kurzer Pausen generiert AI Entwurfsabschnitte
- Leute sehen ihre Worte zurückgespiegelt, strukturiert, und erkennen sie sofort wieder

Von einem Tag Arbeit zu Minuten Verarbeitung. Ohne den Wert von Haftnotizen oder Facilitation zu ersetzen.

---

## Wie es funktioniert

### Die Grundmethode

**VOR DER SITZUNG:**
Bereite Prompts vor, die zum benötigten Dokumenttyp und -stil passen.

**WÄHREND:**
1. Transkription läuft parallel
2. Nach jeder Phase: Transkriptabschnitt geht an AI
3. AI generiert einen Entwurfsabschnitt in der richtigen Form
4. Der Gruppe zur Validierung zeigen
5. Feedback integrieren

**DANACH:**
Alle Abschnitte zum Enddokument zusammenführen.

### Der Feedbackzyklus

In der Praxis sieht das so aus:

1. **Gruppe 1** gibt Input
2. AI macht daraus **Entwurf v1**
3. **Gruppe 1** reagiert auf v1, Feedback wird in **Entwurf v2** verarbeitet
4. **Gruppe 2** erhält v2, reagiert und ergänzt
5. AI verarbeitet zu **Entwurf v3**
6. **Gruppe 3** erhält v3, gibt finalen Input
7. Das Dokument hat Input und Feedback von allen erhalten: jeder konnte beitragen

Das ist die "rollende" Variante: jede Gruppe baut auf der verbesserten Version der vorherigen auf. AI hält den Faden. Das ist eine Vorschau: in [Phase 3](../../phase-3-skalierung.md) werden weitere Varianten behandelt, wie das Zusammenführen paralleler Breakouts zu einer einzigen Synthese.

### Der Prompt

Das ist der tatsächliche Prompt, den wir während der Transformationsplan-Sitzungen für das Netzwerk für psychische Gesundheitsversorgung verwendet haben. Er wurde für Dembrane entworfen, funktioniert aber mit jedem Tool, das Transkripte verarbeiten kann.

Was ihn besonders macht: du verwendest denselben Prompt wiederholt. Jedes Mal mit mehr Input. AI bestimmt selbst, was nötig ist.

**Wie es funktioniert:**

1. **Ein Prompt, zwei Modi.** Wenn du nur das Transkript der Diskussion lieferst, generiert AI einen ersten Entwurf-Teilplan. Wenn du auch das Feedback-Transkript lieferst, generiert AI eine überarbeitete Version. Gleicher Prompt, anderes Ergebnis.

2. **Reflexion bei Erstverwendung.** Für den ersten Entwurf generiert der Prompt auch eine kurze Reflexion: eine narrative Zusammenfassung der zentralen Erkenntnisse aus der Diskussion. Das zeigst du der Gruppe: "das hat AI gehört."

3. **Feedback transparent verarbeitet.** In überarbeiteten Versionen markiert AI, was sich geändert hat und warum. Der Abschnitt "Verarbeitung des Feedbacks" zeigt genau, wie der Input der vorherigen Gruppe eingeflossen ist. Das erzeugt Eigenverantwortung: Leute sehen, dass ihr Feedback zählt.

4. **Kernwerte als roter Faden.** Der Prompt identifiziert Werte aus der Diskussion und webt sie durch das gesamte Dokument. Das gibt dem Plan nicht nur Struktur, sondern auch Seele.

```
Gruppe 1 diskutiert Thema  ──► Prompt ──► Echo + Entwurf v1
                                           ↓ Gruppe 1 zeigen
G1 Feedback auf v1   ──► Prompt ──► Entwurf v2 (überarbeitet)
                                           ↓ nächster Gruppe zeigen
G2 Feedback auf v2   ──► Prompt ──► Entwurf v3 (überarbeitet)
                                           ↓ nächster Gruppe zeigen
G3 Feedback auf v3   ──► Prompt ──► Entwurf v4 (final)
```

Jedes Mal derselbe Prompt. Jedes Mal mehr Input. Das Dokument wächst mit.

**Den vollständigen Prompt ansehen (dieser ist sehr lang)**

```prompt
**Rolle:** Du bist ein analytischer Redakteur und strategischer
Entwickler. Du destillierst zuerst die Kernerkenntnisse aus der/den
bereitgestellten Diskussion(en). Dann synthetisierst du diese
vollständig zu einem umfassenden, detaillierten, zukunftsorientierten
und transparenten Entwurf (oder überarbeiteten Entwurf) eines
Teilplans für das Netzwerk für psychische Gesundheitsversorgung
[Region], wobei die identifizierten Kernwerte als roter Faden durch
den Text gewebt werden.

**Kontext:**
- **Thema:** Das zentrale Thema dieses Teilplans, zu identifizieren aus dem Input.
- **Input - Basisdiskussion(en):** Ein oder mehrere Transkript(e) der ersten Arbeitssitzung(en) zum Thema. (Hinweis: Transkripte können in einer anderen Sprache sein).
- **Input - Feedback (Optional):** Ein oder mehrere Transkript(e) von Feedback-Sitzung(en) zu einer früheren Version dieses Teilplans. (Hinweis: Transkripte können in einer anderen Sprache sein).

**Zieloutput (zweiteilig, Teil 1 ist bedingt):**
1. **Teil 1 - Echo der Basisdiskussion(en):** Ein prägnanter, vorwiegend narrativer Bericht der Kernerkenntnisse aus der/den Basisdiskussion(en). (Bei mehreren Basistranskripten ein Echo pro Transkript erstellen; bei einem ein allgemeines Echo dieser Sitzung). Nur generieren, wenn kein Feedback-Transkript vorliegt, oder wenn explizit angefordert.
2. **Teil 2 - Entwurf (oder überarbeiteter Entwurf) des Teilplans:** Ein vollständiger und reich ausgearbeiteter Teilplan. Er spiegelt den "Charakter von [Region]", zugrundeliegende Werte und Nuancen wider. Dient als Lernwerkzeug, betont Zusammenarbeit, baut auf vorhandenem Wissen auf und enthält Transparenzelemente. Kernwerte werden durchgehend angewandt und wo möglich verbunden.

**Erforderlicher Stil/Ansatz (für Teil 2):**
- **Wichtiger Sprachhinweis:** Die Inputtranskripte können (unbeabsichtigt) in einer anderen Sprache sein. Alle generierte Ausgabe muss ausnahmslos in korrekter, flüssiger und professioneller Sprache entsprechend den Standards der Organisation sein.
- **Sprache:** Formell, professionell.
- **Ton:** Kollaborativ, zukunftsorientiert, reflektierend, handlungsorientiert, pragmatisch, lösungsorientiert und offen. Spiegelt den Kontext, die zentralen Werte und den Lerncharakter von [Region] wider. Flüssige, detaillierte und überzeugende Darstellung, mit Aufmerksamkeit für Wiedererkennbarkeit des Inputs.
- **Perspektive:** Aus Sicht der zusammenarbeitenden Parteien (Bewohner, Angehörige, Fachkraft).
- **Terminologie:** Korrekter Fachjargon (wie im Sektor verwendet), wenn explizit erwähnt.
- **Kritische Einschränkung:** Output streng auf explizite Informationen in Transkripten stützen. Nicht ergänzen, interpretieren oder erfinden.

**Anweisungen:**

TEIL 1: ECHO DER BASISDISKUSSION(EN)
(Nur generieren, wenn kein Feedback-Transkript vorliegt, oder wenn explizit angefordert)

1. Input für Teil 1 analysieren: Anzahl der bereitgestellten Basisdiskussion-Transkripte bestimmen.
2. Echo(s) generieren:
   - Bei MEHREREN Transkripten: Jedes separat analysieren. Pro Transkript einen kurzen, narrativen Absatz (ca. 3-5 Sätze) formulieren, der Kernerkenntnisse/Ideen/Tenor zusammenfasst. Unter jeweiligen Überschriften präsentieren.
   - Bei EINEM Transkript: Einen kurzen, narrativen Absatz (ca. 3-5 Sätze) formulieren, der die Kernerkenntnisse der gesamten Sitzung zusammenfasst.

TEIL 2: ENTWURF (ODER ÜBERARBEITETER ENTWURF) DES TEILPLANS

3. Hauptthema identifizieren: Die Basisdiskussion(en) analysieren und das zentrale Thema bestimmen. Das Thema durchgehend verwenden.
4. Inputtyp analysieren: Prüfen, ob neben der/den Basisdiskussion(en) Feedback-Transkript(e) bereitgestellt wurden.
5. Verarbeitungsstrategie:
   - NUR BASISDISKUSSION(EN): Direkt zu Schritt 6. Einen ersten Entwurf generieren, der so reich und vollständig wie möglich ist.
   - AUCH FEEDBACK-TRANSKRIPT(E):
     a. Die Feedbackpunkte analysieren (Kritik, Vorschläge, Klärungen, neue Erkenntnisse).
     b. Eine ÜBERARBEITETE Version generieren. Erkenntnisse aus der/den Basisdiskussion(en) mit gründlicher Verarbeitung des Feedbacks kombinieren. Im Text explizit auf die Verarbeitung des Feedbacks verweisen (z.B. 'Basierend auf dem Feedback wurde X wie folgt umformuliert').
6. Kerninformationen extrahieren: Kernwerte identifizieren; nach Einleitung, Hauptziel, aktuellem Status, Intervention, Zielgruppe, Wirkungen, beteiligten Partnern und Input für Transparenz suchen.
7. Konflikte synthetisieren: Bei widersprüchlichen Ideen eine Synthese über zugrundeliegende Werte versuchen. Andernfalls als Diskussionspunkt identifizieren.
8. Teilplan strukturieren:
   - **Erstellung dieses Entwurfs:** Den Erstellungsprozess beschreiben. Beim ersten Entwurf: synthetisiert aus Basisdiskussion(en). Bei überarbeiteter Version: Feedback verarbeitet, Quellen benennen.
   - **Einleitung ("Warum ein [Thema] in [Region]?"):** Umfassende, kontextreiche Einleitung. Problem, Relevanz, Notwendigkeit eines integrierten Ansatzes skizzieren.
   - **Hauptziel:** Das zentrale Ziel. Auf Kernwerte verweisen.
   - **Kernwerte:** Auflisten, mit einem kurzen erläuternden Satz pro Wert.
   - **Reflexion über Leitprinzipien:** Kurzer Reflexionsabsatz (2-3 Sätze) darüber, wie Kernwerte leitend waren.
   - **Aktueller Status ("Wo stehen wir?"):** Umfassende Beschreibung der aktuellen Situation, Engpässe, positive Initiativen.
   - **Entwicklung [Thema]:** Einleitungssatz, gefolgt von:
     - Intervention ("Wie gehen wir es an?"): Umfassend und konkret, mit Aktionen und Elementen.
     - Zielgruppe ("Für wen?"): Falls diskutiert.
     - Beabsichtigte Wirkungen ("Was bringt es?"): KPIs falls erwähnt, mit Erklärung pro Wirkung.
     - Beteiligte Partner ("Wer?"): Entscheidende Partner, wie die Zusammenarbeit Kernwerte unterstützt.
   - **(Optional) Lernfähigkeit:** Beitrag zu einem lernenden System.
9. Allgemeine Qualität: Logischer Fluss, Kohärenz. Text soll die Nuancen, Dringlichkeit, gemeinsame Vision und den Lerncharakter von [Region] atmen. Kernwerte als roter Faden.
10. Vollständiger Output: Teil 1 (falls zutreffend) und Teil 2 in einem Durchgang generieren. Alle Abschnitte vollständig ausarbeiten.
11. Schlussabschnitte:
   - **Rechenschaft über Feedbackverarbeitung** (NUR für überarbeitete Version): Wie Feedback zu spezifischen Änderungen geführt hat.
   - **Anmerkungen, fehlende Informationen und erwogene Alternativen:** Einschließlich 'Erwogene Alternativen und mögliche blinde Flecken' (1-2 Alternativen, 1-2 blinde Flecken).
   - **Ein lebendes Dokument:** Einladung zu Feedback, Bedeutung von geteilter Eigenverantwortung.

**Input:**
- Basisdiskussion(en): [Transkript(e)]
- Feedback (optional): [Transkript(e)]

**Ausgabeformat:**

### Überarbeiteter Entwurf Teilplan [Region]: [Das identifizierte Thema] (Entwurf 2.0)

#### Erstellung dieses Entwurfs
(Aktualisierter Text, der widerspiegelt, dass dies eine überarbeitete Version nach Feedback ist, usw.)

#### Einleitung ("Warum [das identifizierte Thema] in [Region]?")
(Überarbeiteter Text)

#### Hauptziel für [das identifizierte Thema]
(Überarbeiteter Text)

#### Kernwerte für [das identifizierte Thema]
(Überarbeiteter Text, falls zutreffend)
- [Kernwert 1]: [Überarbeitete Erklärung]
(usw.)

#### Reflexion über Leitprinzipien
(Überarbeiteter Text, falls zutreffend)

#### Aktueller Status in [Region] ("Wie ist die aktuelle Situation bezüglich [des identifizierten Themas]?")
(Überarbeiteter Text)

#### Entwicklung [das identifizierte Thema]
(Überarbeiteter Einleitungssatz)

Intervention ("Wie gehen wir es an?")
(Überarbeiteter Text)

Zielgruppe ("Für wen ist [das identifizierte Thema] gedacht?")
(Überarbeiteter Text)

Beabsichtigte Wirkungen ("Was bringt es?")
(Überarbeiteter Text)

Beteiligte Partner ("Wer macht mit?")
(Überarbeiteter Text)

(Optional) Lernfähigkeit ("Wie lernen und verbessern wir?")
(Überarbeiteter Text)

---

#### Anmerkungen, fehlende Informationen und erwogene Alternativen
(Überarbeiteter Text)

Erwogene Alternativen und mögliche blinde Flecken
(Überarbeiteter Text)

#### Ein lebendes Dokument
(Überarbeiteter Text, möglicherweise reflektierend über diese neue Iteration)

---

### Verarbeitung des Feedbacks (Änderungen gegenüber dem vorherigen Entwurf)
- Basierend auf Feedback zu [Thema A] wurde [Änderung X] in Abschnitt [Y] umgesetzt, weil [Grund].
- Der Vorschlag, [Thema B] hinzuzufügen, wurde in [Abschnitt Z] verarbeitet.
- Die Bedenken bezüglich [Thema C] wurden durch [Änderung W] adressiert.
(3-5 Stichpunkte)
```

**Warum diese Struktur funktioniert:**
- **"Output streng auf explizite Informationen stützen"** verhindert, dass AI Dinge erfindet. Du bekommst ehrlichen Output mit klaren Lücken, die du füllen kannst.
- **"Explizit darauf verweisen, wie Feedback verarbeitet wurde"** Transparenz darüber, was mit dem Input passiert ist. Leute sehen, dass ihr Beitrag zählt.
- **"Kernwerte als roter Faden"** das Dokument bekommt Kohärenz durch die Werte, die die Gruppe selbst identifiziert hat.
- **Die zweiteilige Struktur (Echo + Teilplan)** erst zeigen, was AI gehört hat, dann das Dokument. Diese Reihenfolge gibt der Gruppe Halt: erst Wiedererkennung, dann Struktur.
- **Stil im Prompt.** Der Prompt enthält Stilrichtlinien, damit AI nicht generisch schreibt, sondern in der Sprache und Struktur, die die Organisation erwartet. (Siehe [Quelldokument als Stilvorlage](../phase-1/quelldokument-stil.md) für die Definition dieses Stils.)

**Diesen Prompt für deinen Kontext anpassen.** Die Themen, Terminologie und Dokumentstruktur oben sind spezifisch für das Netzwerk für psychische Gesundheitsversorgung. Du kannst den Prompt anpassen, indem du:
- Die **Rolle** auf deinen Dokumenttyp änderst (Projektplan, Policy Brief, strategischer Rahmen)
- Die **Themenliste** durch die für deine Sitzung relevanten Themen ersetzt
- Den **Stil** an die Sprache und den Ton deiner Organisation anpasst
- Die **Struktur** (Schritt 8) nach dem Format modellierst, das deine Organisation erwartet

Ein schneller Ansatz: gib AI diesen Prompt zusammen mit einem Beispiel eines bestehenden Dokuments deiner Organisation und frage: "Pass diesen Prompt so an, dass die Ausgabe zu diesem Format passt."

---

## Die Rollenaufteilung

Das erfordert zwei Personen:

| | Facilitator | Co-Facilitator |
|---|------------|----------------|
| **Vor der Sitzung** | Sitzungsdesign, Fragen vorbereiten | Technik einrichten, Aufnahme arrangieren |
| **Während** | Gespräch leiten, AI-Output zeigen, Validierung begleiten | Transkription überwachen, Abschnitte auswählen, Prompts starten |
| **Danach** | Output mit der Gruppe reviewen | Verarbeitung und Konsolidierung |

Niemals: Facilitator hinter einem Laptop, während die Gruppe wartet.

---

## Spannungen

**AI-Output als Wahrheit präsentieren**
"Das habt ihr beschlossen" klingt definitiv, aber es ist eine AI-Interpretation.

*Mein Ansatz:* Ich präsentiere es immer als Entwurf. "Das hat AI aus eurem Gespräch gemacht. Stimmt das so?"

**Zu wenige Validierungsmomente**
Sitzungsende: "Schaut, euer Dokument!" Aber niemand erkennt sich wieder, weil es keine Zwischenchecks gab.

*Mein Ansatz:* Unterwegs validieren. Nach jeder Phase prüfen, ob es stimmt.

**Stil vergessen**
AI schreibt generisch. Das Dokument passt nicht zu den Standards der Organisation.

*Mein Ansatz:* Stilrichtlinien in jeden Prompt. [Siehe [Quelldokument als Stilvorlage](../phase-1/quelldokument-stil.md)]

**Die Seele verlieren**
Das Dokument ist technisch korrekt, aber vermisst die Energie des Gesprächs.

*Mein Ansatz:* Die Zitate bewahren. Ihre Worte, ihre Formulierungen. Das hält es lebendig.

---

## Sicherheitscheckliste

- [ ] Stilrichtlinien in den Prompts enthalten?
- [ ] Unterwegs mit der Gruppe validiert?
- [ ] Zitate und Originalsprache bewahrt?
- [ ] Als "Entwurf zur Validierung" gerahmt, nicht als Entscheidung?
- [ ] Widersprüche und fehlende Informationen gekennzeichnet?

---

## Philosophische Vertiefung

### Direktes Feedback stimuliert Eigenverantwortung

Es gibt einen Grund, warum das funktioniert. Wenn Leute ihre Worte sofort zurückgespiegelt sehen, ist die Verbindung zwischen Sprechen und Ergebnis noch frisch.

"Das habe ich gerade gesagt. Und jetzt steht es hier."

Das ist anders als ein Bericht eine Woche später. Die Geschwindigkeit dient nicht der Effizienz; die Geschwindigkeit dient der Eigenverantwortung.

### Das Ritual ändert sich, die Intention bleibt

Das alte Ritual: Haftnotizen, Clustern, ein Tag Arbeit, Entwurf, Review, Endversion.
Das neue Ritual: Sprechen, sofortiger Output, Validieren, Verfeinern.

Die Form ist anders. Aber die Intention (Leute zu Eigentümern eines Plans machen) bleibt dieselbe. Tatsächlich: durch die Geschwindigkeit ist die Eigenverantwortung direkter.

---

## Verwandte Techniken

- Der Stilansatz (wie stellst du sicher, dass Output im richtigen Format kommt?) wird behandelt in [Quelldokument als Stilvorlage](../phase-1/quelldokument-stil.md)
- Warum das Bewahren der genauen Worte so wichtig ist, lies in [Sprache bewahren](../phase-1/sprache-bewahren.md)
- Für Echtzeit-Interventionen während der Sitzung (nicht nur Dokumentation, sondern auch Reflexion), siehe [Live-Reflexion mit AI](live-reflexion-mit-ai.md)

---

← [Zurück: Live-Reflexion](live-reflexion-mit-ai.md) | [Zurück zu Phase 2: Vertiefung](../../phase-2-vertiefung.md) | [Weiter: Intuition schwarz auf weiß →](intuition-schwarz-auf-weiss.md)

---

*"Von einem Tag Arbeit zu Minuten Verarbeitung: nicht für Effizienz, sondern für Eigenverantwortung."*
