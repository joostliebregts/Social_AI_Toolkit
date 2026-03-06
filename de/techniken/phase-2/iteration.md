# Iteration als Dialog

> *Nicht am Output herumschrauben, sondern Feedback geben. AI lernt, was du meinst.*

**Phase:** [Phase 2: Vertiefung](../../phase-2-vertiefung.md)
**Baut auf:** Das erste AI-Ergebnis, das noch nicht ganz passt

---

## Wann ist das relevant?

**Situation:** Du bekommst ein Ergebnis von AI. Es ist zu 60 % das, was du suchst. Der Reflex: selbst anpassen. Wörter ändern, Sätze umschreiben.

**Die Tendenz:** Alleinarbeit. Du nimmst das Ergebnis und bastelst, bis es passt. AI ist fertig, du übernimmst.

**Das Prinzip:** AI-Output ist im Grunde nie ganz fertig. Er ist Input für einen Dialog. Wenn du Feedback gibst statt selbst herumzuschrauben, lernt AI, mit deinen spezifischen Anforderungen zu arbeiten. Das Ergebnis wird besser als das, was du allein hinbekommen hättest. Und du lernst, in Worte zu fassen, was du eigentlich willst.

**Die Frage:** Gebe ich Feedback, oder schraube ich allein herum?

---

## Die Geschichte: zwölf Runden

Ein Transformationsplan für ein Netzwerk der psychischen Gesundheitsversorgung. Dreißig Beteiligte hatten Input geliefert. Daraus musste ein Dokument werden, das die Krankenkasse akzeptieren würde.

Es gab bereits einen genehmigten Transformationsplan aus einer anderen Region. Die Frage: Wie schreibst du neue Teilpläne im selben Stil?

Das wurde kein einmaliger Prompt. Es wurden zwölf Runden.

**Runde 1:** Ich beschreibe, was ich will.
**Runde 2:** AI schlägt einen Schritt-für-Schritt-Plan vor.
**Runde 3:** Ich füge das Sessionskript als Kontext hinzu.
**Runde 4:** AI passt die Prompts an das Skript an.
**Runde 5:** Ich bitte um drei spezifische Prompts.
**Runde 6:** AI liefert drei Prompts, aber der Stil stimmt noch nicht.
**Runde 7:** Ich bitte um universelle Versionen.
**Runde 8:** AI passt an, verfehlt aber immer noch etwas.
**Runde 9:** Entscheidende Korrektur: "Der Stil muss IM Prompt stehen, weil AI keinen Zugriff auf das Beispiel hat."
**Runde 10:** AI verarbeitet die Korrektur.
**Runde 11:** Ich kläre die Situation des Kontextfensters.
**Runde 12:** Die Prompts sind fertig.

Vier konkrete Korrekturen, die den Unterschied machten. Der rote Faden: Du gehst davon aus, dass AI weiß, was du weißt. AI weiß enorm viel, aber nicht deinen spezifischen Kontext: die Dokumente, die du hast, die Absprachen, die du getroffen hast, den Stil, den du suchst. Was du nicht explizit angibst, existiert für AI nicht.

- "Die AI hat keinen Zugriff auf den Beispielplan, also den Schreibstil IM Prompt einfügen"
- "Die Prompts universell machen: AI kann das Thema selbst aus dem Transkript erkennen"
- "Prompt 2 soll hauptsächlich Fragen für die nächste Gruppe generieren"
- "Die AI hat Zugriff auf vollständige Transkripte, nicht auf Fragmente"

Diese Erkenntnis (dass du AI explizit sagen musst, was sie wissen muss) kommt auch in [Quelldokument als Stilvorlage](../phase-1/quelldokument-stil.md) zurück, wo sie den Kern der Technik bildet.

Als ich darauf zurückblickte, sah ich ein Muster: Ein Prompt entsteht nicht in Runde 1. Der Prompt entwickelt sich durch die Korrekturen.

**Quelle:** Iterationsprozess, den ich bei der Entwicklung des Transformationsplans durchlaufen habe (GGZ Centraal Gelderland)

---

## Der Wechsel: vom Herumschrauben zum Steuern

```
❌ Herumschrauben: AI-Output bekommen → Selbst anpassen → Fertig
✅ Iterieren: AI-Output bekommen → Innehalten → Feedback geben → Wiederholen
```

Der Unterschied ist subtil, aber grundlegend. Herumschrauben ist Alleinarbeit. Iterieren ist Zusammenarbeit.

**Wie Herumschrauben aussieht:**

> Du bekommst eine Zusammenfassung von AI. Der Ton ist zu formell.
>
> Du öffnest das Dokument und fängst an, Sätze umzuschreiben. "Stakeholder" wird zu "Beteiligte". "Implementiert" wird zu "eingeführt".
>
> Zwanzig Minuten später ist es fertig. AI hat nichts gelernt. Du hast die Arbeit gemacht.

**Wie Iterieren aussieht:**

> Du bekommst dieselbe Zusammenfassung. Der Ton ist zu formell.
>
> **Runde 1:** "Das klingt wie ein Strategiepapier. Ich suche den Ton eines Gesprächs zwischen Kollegen, die sich lange kennen und offen über ihre Bedürfnisse sprechen. Normale Wörter, kein Fachjargon. Versuch es nochmal."
> *Dreißig Sekunden später: neue Version. Besser, aber noch nicht ganz.*
>
> **Runde 2:** "Besser. Aber der erste Absatz ist noch zu distanziert. Mach ihn persönlicher."
> *Noch mal dreißig Sekunden. Jetzt trifft es.*

**Warum das funktioniert:**
- "Lernkontext:" AI lernt deine Bedürfnisse innerhalb des laufenden Gesprächs
- "Schärfere Formulierung:" Du formulierst präziser, was du willst, für dich selbst und für AI
- "Kombinierte Kapazität:" Das Endergebnis verbindet die Kapazität von AI mit deiner Richtung
- "Nächste Iteration:" Beim nächsten Mal kannst du schon sagen: "Ton eines Gesprächs zwischen Kollegen, die sich lange kennen, offen über Bedürfnisse, kein Fachjargon"

*Hinweis: Starte ein neues Gespräch, und das Kontextfenster ist wieder leer. Du fängst von vorn an. Deshalb lohnt es sich, innerhalb einer Sitzung weiterzuiterieren.*

### Diktat als Beschleuniger

Die Hürde beim Feedback-Geben ist das Tippen. Wenn du jede Korrektur austippen musst, fühlt sich Iterieren wie Arbeit an. Aber Diktat verändert das.

Der Workflow: AI liefert Output, du sprichst deine Reaktion, innerhalb einer Sekunde steht sie als Text da.

Du musst nicht beim Tippen formulieren. Du sagst einfach, was du denkst: "Nein, das ist zu formell. Ich suche eher den Ton eines Küchentischgesprächs." Das geht schneller als Tippen und fühlt sich natürlicher an: mehr wie ein Gespräch.

*Siehe [Transkription](../phase-1/transkription.md#diktat-als-beschleuniger) für Tools und Einrichtung.*

---

## Iteration vorab: lass AI dir die Fragen stellen

Bisher ging es um Iteration am Output: Du bekommst etwas von AI, du gibst Feedback, AI passt an. Aber es gibt eine andere Form: Iteration *vorab*. Dabei lässt du AI dir zuerst helfen, klar darüber zu werden, was du willst, bevor irgendein Output kommt. Das Hin und Her mit AI ist eine Fähigkeit für sich.

Die Technik: Bitte AI, dir Fragen zu stellen, jedes Mal mit zwei Optionen. Das zwingt dich, Position zu beziehen. Und die Nuancen, die du zu deiner Wahl hinzufügst ("Ich will beides", "aber aus dem positiven Blickwinkel", "Ich entscheide selbst, wie ich sie teile"), machen den Prompt präziser, als er ohne den Dialog gewesen wäre.

Die ganze Geschichte, wie das in der Praxis ablief (drei Fragen, drei Anpassungen, ein Prompt, der genau das tat, was Maarten brauchte), findest du unter [Was noch darin steckte](was-noch-darin-steckte.md).

### Der Prompt, der AI dazu bringt, dir Fragen zu stellen

Dieses Verhalten (AI stellt dir Fragen mit A/B-Optionen) muss explizit ausgelöst werden. Hier ist der Prompt dafür:

```prompt
Ich arbeite an [PROJEKT/ZIEL].

Aktueller Stand der Dinge:
- Ziel: [was du erreichen willst]
- Zielgruppe: [für wen]
- Womit ich hadere: [offene Fragen, Zweifel]

Stell mir 3-5 scharfe Fragen, die mir helfen:
1. Mein Ziel klarer zu fassen
2. Entscheidende Weichenstellungen explizit zu machen
3. Blinde Flecken zu erkennen

Wo relevant: Präsentiere Wahlmöglichkeiten (A vs B) statt
nur offene Fragen. Das zwingt mich, Position zu beziehen.

Nach meinen Antworten: Stelle Folgefragen basierend auf
dem, was ich gewählt habe.
```

Die Kraft liegt in "Präsentiere Wahlmöglichkeiten (A vs B)". Das zwingt dich, Position zu beziehen, und die Nuancen, die du zu deiner Wahl hinzufügst, sind genau dort, wo der Wert liegt.

---

## Der Werkzeugkasten

Die Zwölf-Runden-Geschichte oben zeigt Iteration am Output. Iteration vorab zeigt, wie du Richtung gibst, bevor überhaupt Output kommt. Aber was, wenn du konkret wissen willst, *wie* du Feedback gibst? Oder wie du aus deinen eigenen Anpassungen lernst? Hier sind die Methoden, die ich verwende.

### Feedback-Formeln

Wenn AI-Output nicht trifft, gib spezifisches Feedback. Sag es, als würdest du diktieren:

**Für den Ton:**

```prompt
Mach es wärmer, als würdest du es einem Kollegen erzählen.
```

```prompt
Das klingt nach Beratersprache, kannst du die Worte der Teilnehmenden verwenden?
```

**Für die Struktur:**

```prompt
Zu lang, kannst du weniger Aufzählungen und mehr Erzähltext verwenden?
```

```prompt
Die Reihenfolge stimmt nicht, kannst du mit X statt Y anfangen?
```

**Für den Inhalt:**

```prompt
Hier fehlt die Nuance zu X, kannst du dies, dies und dies bitte ergänzen?
```

```prompt
Das ist 70 % von dem, was ich suche. Was fehlt, ist X, kannst du es nochmal versuchen?
```

**Für die Rahmung:**

```prompt
Das ist zu negativ gerahmt, kannst du es von dem her rahmen, was die Leute wollen?
```

```prompt
Das klingt, als wüsste AI es sicher, kannst du 'möglicherweise' und 'es scheint als ob' verwenden?
```

**Wenn du nicht weißt, was du willst:**

```prompt
Das ist in Ton und Struktur nicht das, was ich suche, aber ich weiß nicht ganz, was ich will. Kannst du mir Fragen stellen, um herauszufinden, welche Optionen es gibt und was besser zu mir passt?
```

**Wenn du zwischen Optionen schwankst:**

```prompt
Ich schwanke zwischen diesen beiden Formaten. Kannst du beide kurz ausarbeiten, damit ich die Beispiele lesen und darauf Feedback geben kann?
```

### Der Feedback-Loop-Prompt

Stell dir vor: Du hast AI-Output deutlich angepasst. Du hast Sätze umgeschrieben, die Struktur verändert, den Ton angepasst. Statt diese Arbeit zu "verlieren", kannst du sie an AI zurückgeben, damit dein Prompt beim nächsten Mal besser funktioniert.

```prompt
Das war das ursprüngliche Ergebnis:
[AI-Output einfügen]

Das habe ich daraus gemacht:
[deine verbesserte Version einfügen]

Analysiere die Unterschiede:
1. Was habe ich geändert?
2. Warum glaubst du, habe ich das geändert?
3. Wie sollte ich den Prompt anpassen, um beim nächsten
   Mal näher an mein gewünschtes Ergebnis zu kommen?

Gib konkrete Vorschläge für Prompt-Verbesserungen.
```

**Warum diese Struktur funktioniert:**
- "Original neben Überarbeitung" zwingt AI zum konkreten Vergleich, nicht zu abstrakten Ratschlägen
- "Drei Analysefragen" strukturieren die Reflexion von Beobachtung zu Handlung
- "Prompt-Verbesserungen" als Endziel machen jede Iteration kumulativ besser

*Das ist ein Vorschlag: Pass ihn an deine spezifische Situation an.*

Das wirkt wie Mehrarbeit, aber es ist eine Investition. Jede Iteration macht deine Prompts präziser.

### Prompt-Testzyklus

**Wann nutzt du das?**
- Du hast bestehende Transkripte und willst testen, ob ein neuer Prompt funktioniert
- Es gibt ein neues AI-Modell und du willst prüfen, ob deine Prompts noch gut funktionieren
- Du willst systematisch verbessern statt ad hoc

Beispiel: Du hast einen Prompt, der mit Gemini 2.5 gut funktioniert hat, aber jetzt gibt es ein neues Modell. Funktioniert dein Prompt noch? Oder du hast zehn Transkripte aus früheren Sessions und willst testen, ob dein neuer Analyse-Prompt das Richtige herausholt.

Der Ansatz: Teste deinen Prompt mit echten Daten und lass AI die eigene Arbeit bewerten.

Die Schritte:
1. **Den Prompt zusammen mit AI entwickeln:** zum Beispiel einen Prompt für Transkript-Analyse
2. **Mit echten Daten testen:** den Prompt auf einem relevanten Transkript laufen lassen
3. **Das Ergebnis sammeln:** Was ist herausgekommen?
4. **Zurück an die AI geben, die den Prompt mitentwickelt hat:**

```prompt
Ich habe den Prompt, den wir zusammen entwickelt haben, an einem echten Transkript getestet.

Das ist das Ergebnis, das herauskam:
[Ergebnis einfügen]

Fragen:
1. Wie gut hat unser Prompt für das funktioniert, was wir erreichen wollten?
2. Was fehlt im Ergebnis?
3. Wie sollten wir den Prompt anpassen, um näher an unser Ziel zu kommen?
```

**Warum diese Struktur funktioniert:**
- "Echte Daten als Test" verhindert, dass dein Prompt nur in der Theorie funktioniert
- "Drei Bewertungsfragen" erzwingen Reflexion über Leistung, Lücken und Verbesserung
- "Zyklisches Design" macht den Prompt selbst zum Gegenstand der Iteration

5. **Den Prompt verfeinern:** AI den ursprünglichen Prompt auf Basis des Tests anpassen lassen

Das unterscheidet sich vom Feedback-Loop oben. Dort passt du das Ergebnis an und lässt AI aus deinen Anpassungen lernen. Hier testest du den Prompt selbst und lässt AI bewerten, wie gut der Prompt funktioniert hat.

*Quelle: Methode, die ich beim Iterieren von Dembrane-Prompts entwickelt habe.*

### Modellübergreifende Kritik (fortgeschritten)

Das ist eine zeitintensive Technik für Arbeit, die du wirklich polieren willst: zwei AIs gegenseitig die Arbeit des anderen bewerten lassen. Ich habe das beim Workshop-Design eingesetzt: ChatGPT und Gemini haben gegenseitig den Output des anderen geprüft, bis sie bei 98/100 konvergierten.

**Warum das funktioniert:**
- "Modellvielfalt:" verschiedene Modelle haben unterschiedliche Verzerrungen und Stärken
- "Gegenseitige Kritik:" Kritik von einer "Peer-AI" hilft, blinde Flecken zu erkennen
- "Konvergenz" zeigt die Robustheit des Ergebnisses

**Wann in Betracht ziehen:**
- Arbeit, bei der du wirklich Tiefe suchst (strategische Pläne, Workshop-Designs)
- Komplexe Analysen, bei denen du mehrere Perspektiven willst
- Als Check, ob eine AI dich in die Irre führt

#### Schritt 1: Beide AIs um eine Zusammenfassung bitten

An beide AIs (separat):

```prompt
Wir haben zusammen an [PROJEKT/FRAGE] gearbeitet.

Fasse zusammen:
- Die Kernfrage, die wir zu beantworten versucht haben
- Den Ansatz, den wir gewählt haben
- Die wichtigsten Erkenntnisse, die entstanden sind
- Die Schwachstellen oder blinden Flecken in unserer Analyse
- Eine Bewertung (0-100) für die Qualität unserer Arbeit

Sei kritisch und ehrlich über Grenzen.
```

**Warum diese Struktur funktioniert:**
- "Selbstkritik erzwingen" durch "sei kritisch" verhindert selbstlobenden Output
- "Bewertung" zwingt die AI zu einem quantitativen Urteil über die eigene Arbeit
- "Fünf Dimensionen" decken das gesamte Spektrum ab, von Kernfrage bis blinde Flecken

#### Schritt 2: Gegenseitig bewerten lassen

Zusammenfassung A an Modell B geben:

```prompt
Eine andere AI hat diese Zusammenfassung der Arbeit an derselben Frage erstellt:

[ZUSAMMENFASSUNG A EINFÜGEN]

Bewerte diese Zusammenfassung:
1. Was sind Stärken, die wir nicht haben?
2. Was sind Schwachstellen, die sie nicht sehen?
3. Welche blinden Flecken hat diese Analyse?
4. Wie würdest du unseren Ansatz mit ihren Erkenntnissen kombinieren?
```

**Warum diese Struktur funktioniert:**
- "Externe Bewertung" durchbricht die Verzerrung eines einzelnen Modells
- "Vier gezielte Fragen" lenken die Kritik von Stärken zu Synthese
- "Kombinationsfrage" erzwingt konstruktive Integration, nicht nur Kritik

Dasselbe in die andere Richtung.

#### Schritt 3: Integrieren

```prompt
Ich habe jetzt zwei Analysen und gegenseitige Kritik.

Analyse A: [ZUSAMMENFASSUNG A]
Kritik von B an A: [KRITIK B→A]

Analyse B: [ZUSAMMENFASSUNG B]
Kritik von A an B: [KRITIK A→B]

Synthetisiere zu einer integrierten Perspektive, die:
- Die Stärken beider bewahrt
- Die Schwachstellen beider adressiert
- Neue Erkenntnisse hinzufügt, die aus der Konfrontation entstehen
```

*Das ist zeitintensiv. Setze es sparsam ein, für Arbeit, bei der es wirklich zählt.* Oder wenn die Neugier dich treibt :)

---

## Spannungen

**Sofort herumschrauben**
Der erste Reflex ist, Output anzupassen statt Feedback zu geben. Aber dann lernt AI nichts und ich mache die Arbeit selbst.

*Mein Ansatz:* Ich halte inne. Ich frage mich: "Kann ich das als Feedback formulieren?" Wenn ja, dann Feedback. Wenn nein, ist es vielleicht besser, mit einem schärferen Prompt von vorn zu beginnen.

**Endlos iterieren**
Manchmal reichen 80 %. Perfektion kann lähmen.

*Mein Ansatz:* Ich frage mich: "Ist das gut genug für den nächsten Schritt?" Wenn ja, weiter.

**Vages Feedback**
"Das fühlt sich nicht richtig an" ist, was ich fühle. Aber AI weiß nicht, was sich ändern muss.

*Meine Erfahrung:* Wenn ich frustriert über Output bin, wird auch mein Feedback vage. Was hilft: kurz innehalten und benennen, was genau nicht trifft. "Der Ton ist zu formell" funktioniert besser als "das fühlt sich nicht richtig an."

**Feedback ohne Richtung**
Die Tendenz ist zu sagen, was falsch ist, ohne zu sagen, was ich suche.

*Meine Erfahrung:* Ich merke, AI reagiert besser auf "Ich suche [X]" als auf "das ist nicht, was ich will." Und ehrlich gesagt: Es zwingt mich auch, mir klar darüber zu werden, was ich eigentlich will.

---

## Sicherheits-Checkliste

*Für Datenschutzfragen beim Teilen von Transkripten lies [Sicherer Umgang mit AI](../../sicherer-umgang.md).*

- [ ] Feedback spezifisch formuliert?
- [ ] Richtung gegeben, nicht nur Kritik?
- [ ] Innegehalten, bevor du herumgeschraubt hast?
- [ ] Bei wesentlichen Anpassungen: Feedback-Loop-Prompt genutzt?

---

## Philosophische Vertiefung

### Der Prozess IST der Wert

In der Zwölf-Runden-Iteration war Runde 9 der Wendepunkt: "Der Stil muss IM Prompt stehen, weil AI keinen Zugriff auf das Beispiel hat."

Diese Erkenntnis kam nicht aus dem Nichts. Sie kam, weil das Ergebnis aus Runde 6 nicht stimmte: der Stil fehlte. Ohne dieses Scheitern keine Korrektur. Ohne diese Korrektur keine funktionierenden Prompts.

Der Wert lag nicht im ersten Versuch. Der Wert lag im Prozess des Entdeckens, was fehlte.

### Dialog schafft Verbindlichkeit

Es gibt eine tiefere Ebene. Wenn du AI Feedback gibst, formulierst du, was du willst. Diese Formulierung macht deine Intention explizit, für dich selbst, nicht nur für AI.

Das ist derselbe Mechanismus wie bei Menschen. Dialog schafft Klarheit. Die Tatsache, dass du erklären musst, was du meinst, zwingt dich, zu wissen, was du meinst.

---

## Verwandte Techniken

- [Live-Reflexion mit AI](live-reflexion-mit-ai.md): Echtzeit-Anwendung von Iteration
- [Erst die Menschen prompten](erst-die-menschen-prompten.md): Die Frage vor der Prompt-Frage
- [Quelldokument als Stilvorlage](../phase-1/quelldokument-stil.md): Die Zwölf-Runden-Geschichte im Detail

---

← [Zurück: Was noch darin steckte](was-noch-darin-steckte.md) | [Zurück zu Phase 2: Vertiefung](../../phase-2-vertiefung.md) | [Weiter: Erst die Menschen prompten →](erst-die-menschen-prompten.md)

---

*"Ein Prompt entsteht nicht, er entwickelt sich. Der Wert liegt in der Anhäufung von Verfeinerungen: Jede Korrektur macht die nächste besser."*
