# In der Session

> *AI in ko-kreativen Sessions mit mehreren Gruppen einsetzen.*

**Phase:** [Phase 3: Skalierung](../../phase-3-skalierung.md)
**Baut auf:** [Vom Gespräch zum Plan](../phase-2/gespraech-zum-plan.md), [Erst die Menschen prompten](../phase-2/erst-die-menschen-prompten.md)

---

## Wann ist das relevant?

**Situation:** Du moderierst eine Session mit mehreren Gruppen. Breakouts, Tische, Runden. Gespräche werden aufgenommen. Und jetzt willst du wissen: Wie setze ich AI ein, um festzuhalten, was all diese Gruppen sagen, es zu analysieren und zurückzuspiegeln?

**Was mir auffällt:** Die meisten Facilitatoren kennen Breakouts. Aber das Zusammenführen dessen, was an verschiedenen Tischen gesagt wird: Das ist Handarbeit, die in der verfügbaren Zeit meist nicht gelingt. AI macht es zum ersten Mal möglich, diese Verbindung herzustellen: pro Tisch analysieren, dann die Analysen nebeneinanderlegen.

**Das Prinzip:** Der gleiche Ansatz wie bei einem einzelnen Gespräch (erst einzeln analysieren, dann synthetisieren), aber auf mehrere Gruppen gleichzeitig. Das [Kernprinzip von Phase 3](../../phase-3-skalierung.md), angewandt innerhalb eines einzigen Sessiontages.

**Die Frage:** Wie organisierst du das praktisch?

---

## Drei Arbeitsformen

Es gibt drei Wege, AI in Sessions mit mehreren Gruppen einzusetzen. Der Unterschied liegt darin, wie und wann du die Ergebnisse zurückspiegelst.

## 1. Parallel: mehrere Tische, dieselben Fragen

```
  Tisch A ──► Analyse A ──┐
                           │
  Tisch B ──► Analyse B ──┼──► Synthese
                           │
  Tisch C ──► Analyse C ──┘
```

Gruppen sprechen gleichzeitig über dieselben Fragen. Jeder Tisch wird separat transkribiert und analysiert. Es gibt keine Verbindung zwischen den Tischen während der Session. Die Synthese machst du im Nachhinein.

## Aus der Praxis: Schlüsselfiguren-Session Doesburg

In einem Bottom-up-Versorgungsprozess in Doesburg, einer Kleinstadt in den Niederlanden, organisierten wir eine Session mit Schlüsselfiguren aus dem Stadtteil: Menschen, die das soziale Gefüge ihrer Gemeinde kennen. Die Frage: Wie sieht gute Versorgung und Fürsorge füreinander in dieser Gemeinschaft aus?

Vier Tische, jeder mit einem Tischgastgeber. Drei Runden mit denselben Fragen: Traumbild ("Wie sieht deine ideale Situation aus?"), Herausforderungen ("Was sind die Hindernisse?"), eigene Möglichkeiten ("Was kannst du selbst daran tun?"). Jeder Tisch wurde über Dembrane transkribiert. Nach der Session: pro Tisch analysiert mit demselben Prompt, dann die vier Analysen nebeneinandergelegt.

> Acht Themen, die an mehreren Tischen wiederkehrten. "Noaberschap" — Fürsorge beginnt bei Nachbarn, die aufeinander achten — an allen vier. "Eigene Regie behalten" an drei. Menschen, die nicht beieinander saßen, aber dasselbe empfanden.

---

**Wann das passt:** Wenn du den Gruppen ihr eigenes Gespräch lassen willst, ohne Zwischensteuerung. Wenn du den Reichtum jedes Tisches einzeln bewahren willst. Wenn die Synthese nicht unbedingt live sein muss.

**Der Prompt:** Zwei Prompts im Tandem: ein Analyse-Prompt, den du bei jedem Tisch verwendest (das macht die Ergebnisse vergleichbar), und ein Synthese-Prompt, der die Analysen nebeneinanderlegt. Kopiere den Prompt unten; er hilft dir, beide Prompts für deine Session zu erstellen.

<ProbeerStory experiment="in-der-sitzung"></ProbeerStory>

---

## 2. Nacheinander: Gruppen bauen aufeinander auf, Synthese im Nachhinein

```
  Gruppe 1 ──► Analyse ──► [auf Bildschirm]
                                │
              Gruppe 2 ──► Analyse ──► [auf Bildschirm]
                                          │
                            Gruppe 3 ──► Analyse
                                          │
                                          ▼
                                    End-Synthese
```

Gruppen rotieren zum selben Tisch. Der Vorsitzende zeigt die AI-Zusammenfassung der vorherigen Runde. Jede Runde wird separat aufgenommen und analysiert. Am Ende bringst du alles zusammen.

## Aus der Praxis: Transformationsplan GGZ

Im Rahmen von GGZ (dem niederländischen System für psychische Gesundheitsversorgung) arbeiteten wir mit drei Thementischen, jeder mit einem Vorsitzenden. Runde 1 (60 Minuten): Jede Gruppe baut eine 5-Jahres-Vision auf. Transkription über Dembrane. AI generiert eine Zusammenfassung: gemeinsame Vision, entscheidende Bestandteile, Zukunftsbilder.

Dann wird rotiert. Runde 2 (25 Minuten): Der Vorsitzende zeigt die Dembrane-Zusammenfassung auf dem Bildschirm. Die neue Gruppe reagiert, schärft nach, ergänzt. Wieder aufgenommen. Runde 3 (25 Minuten): dasselbe, wieder rotieren.

Am Ende: drei Runden pro Thema separat analysiert, dann synthetisiert zu einem Konzept-Teilplan pro Thema.

*Mehr darüber, wie du eine solche Session vorbereitest — vom Ziel aus rückwärts zu den richtigen Fragen und Puzzleteilen pro Tisch: [Erst die Menschen prompten](../phase-2/erst-die-menschen-prompten.md).*

---

**Der Unterschied zu parallel:** Hier bauen Gruppen aufeinander auf. Der Vorsitzende spiegelt zurück, was die vorherige Gruppe sagte. Aber jede Runde wird separat analysiert; die AI baut nicht in einem fortlaufenden Dokument weiter.

**Wann das passt:** Wenn du Gruppen auf die Arbeit der anderen reagieren lassen willst. Wenn der Vorsitzende eine starke Rolle beim Verbinden der Runden spielt. Wenn du die einzelnen Analysen für den Vergleich aufbewahren willst.

**Der Prompt:** Zwei Prompts im Tandem: eine Zwischenanalyse nach jeder Runde und eine End-Synthese nach der Session. Kopiere den Prompt unten in dein AI-Tool; er hilft dir, beide Prompts für deine Session zu erstellen.

<ProbeerStory experiment="in-der-sitzung-sequential"></ProbeerStory>

---

## 3. Durchlaufen: AI baut zwischen den Runden weiter

```
  Gruppe 1 bespricht       ──► AI ──► V1 [auf Bildschirm]
                                       ↓
  Gruppe 1: "Stimmt das?"  ──► AI ──► V2 [auf Bildschirm]
                                       ↓
  Gruppe 2 reagiert         ──► AI ──► V3 [auf Bildschirm]
                                       ↓
  Gruppe 2: "Stimmt das?"  ──► AI ──► V4 [auf Bildschirm]
                                       ↓
                    ··· nächste Gruppe ···
```

Das ist die AI-verstärkte Version von "nacheinander." Hier verarbeitet AI das Feedback jeder Gruppe direkt in ein fortlaufendes Dokument. Die nächste Gruppe sieht nicht nur eine Zusammenfassung, sondern das aktualisierte Ergebnis, in dem das Feedback aller vorherigen Gruppen bereits verarbeitet ist.

Der Zyklus: Jede Gruppe bekommt das Ergebnis auf dem Bildschirm, reagiert darauf und erhält dann die verarbeitete Version zurück. "Stimmt das?" Erst wenn die Gruppe zufrieden ist, geht es weiter zur nächsten. Niemand beginnt auf einem leeren Blatt; jede Gruppe reagiert auf etwas Konkretes.

## Aus der Praxis: Missions-/Visionssitzung GGZ Amsterdam

Eine Session mit circa 25 Teilnehmenden. Der Tag begann mit einem Warm-up, das zugleich funktional war:

Runde 1: Sechs Personen saßen an einem Tisch mit einem Telefon (Dembrane nahm auf). Der Rest der Gruppe stand drumherum und hörte zu. Sie besprachen die bestehende Mission und Vision. AI verarbeitete das Transkript zu einer ersten Version (V1), die auf dem Bildschirm präsentiert wurde. Dieselbe Gruppe reagierte: Stimmt dieses Bild? Fehlt etwas? Ihr Feedback wurde zu V2 verarbeitet.

Runde 2: Eine neue Gruppe von sechs setzte sich hin. Sie sahen V2 und besprachen, was noch verfeinert werden musste. AI verarbeitete ihre Reaktion, legte das Ergebnis der Gruppe zurück vor, und nach deren Bestätigung ging es weiter zur nächsten Runde. So wurde die Mission/Vision Schritt für Schritt reicher.

> Es funktionierte inhaltlich — die Mission/Vision wurde iterativ angereichert — und es war ein Warm-up. Alle gewöhnten sich an die Arbeitsweise mit AI und Dembrane, bevor die "eigentliche" Session begann.

---

**Der Unterschied zu "nacheinander":** Die AI baut im selben Dokument weiter. Das jüngste Feedback ist leitend. Gruppe 2 verfeinert, was Gruppe 1 begonnen hat, Gruppe 3 verfeinert, was Gruppe 2 geliefert hat. Das Ergebnis wird immer reicher.

**Wann das passt:** Wenn du ein Dokument iterativ mit dem Input mehrerer Gruppen aufbauen willst. Wenn Geschwindigkeit zählt: Das verarbeitete Ergebnis ist innerhalb einer Minute da, die nächste Gruppe kann direkt reagieren. Wenn du willst, dass Menschen sehen, was mit ihrem Beitrag geschieht.

**Achtung:** Diese Arbeitsform verlangt am meisten von deinem AI-Tool. Der Prompt enthält bedingte Logik (Pfad A: erstes Konzept, Pfad B: überarbeitete Version). Teste vor der Session, ob dein AI-Tool beide Pfade richtig aufgreift. Entdecke das nicht erst mit 25 Leuten um dich herum.

**Der Prompt:** Ein Prompt mit eingebauter Logik: Bei einer ersten Diskussion generiert er ein Konzept, bei Feedback eine überarbeitete Version. Kopiere den Prompt unten in dein AI-Tool; er hilft dir, einen Prompt für deine Session zu erstellen.

<ProbeerStory experiment="in-der-sitzung-iterativ"></ProbeerStory>

---

## Was brauchst du?

Unabhängig von der Arbeitsform, das ist die Grundausstattung:

- [ ] **Transkription pro Tisch:** Telefon mit Transkriptions-App (Dembrane oder vergleichbar). Auf Nicht-stören, am Ladegerät.
- [ ] **Bildschirm oder Projektor:** um AI-Output der Gruppe zu zeigen (bei "nacheinander" und "durchlaufen")
- [ ] **Tischgastgeber oder Vorsitzender:** jemand, der das Gespräch begleitet und den AI-Output einführt
- [ ] **Vorbereitete Prompts:** vor der Session getestet. Derselbe Prompt pro Tisch macht Ergebnisse vergleichbar.
- [ ] **Drehbuch mit Aufnahmemomenten:** Wann startest du die Aufnahme, wann stoppst du, was macht AI dazwischen?
- [ ] **Post-its, Stifte, Zeitleiste** (optional): physische Elemente helfen, vom Abstrakten zum Konkreten zu kommen

**Tipp:** Teste deinen Prompt am Tag vor der Session an einem früheren Transkript. Dann weißt du, was du erwarten kannst.

---

## Welche Arbeitsform passt zu dir?

| Du willst... | Wähle | Warum |
|------------|------|--------|
| Gruppen ihr eigenes Gespräch führen lassen, nachher vergleichen | **Parallel** | Keine Steuerung, maximaler Reichtum pro Tisch |
| Gruppen auf die Arbeit der anderen reagieren lassen | **Nacheinander** | Aufeinander aufbauen über den Vorsitzenden, einzelne Analysen bewahren |
| Ein Dokument iterativ mit mehreren Gruppen anreichern | **Durchlaufen** | Live-Geschwindigkeit, jede Gruppe sieht das Ergebnis der vorherigen |
| Menschen an AI als Arbeitsweise gewöhnen | **Durchlaufen** (als Warm-up) | Sichtbar machen, wie AI funktioniert, bevor die eigentliche Session beginnt |

Du kannst Arbeitsformen kombinieren. Das Transformationsplan-Beispiel kombinierte parallel (3 Thementische) mit nacheinander (Rotation). Die Amsterdam-Session begann mit Durchlaufen als Warm-up und ging danach zu parallel über.

---

## Und dann? Die Schleife

Die Session ist vorbei. Du hast Analysen, Synthesen, vielleicht Konzeptdokumente. Was machst du damit?

**Rückkopplung an die Gruppe:** Lass die Menschen ihre eigenen Worte wiedersehen. "Das ist, was ihr gesagt habt. Erkennt ihr das wieder?" Der Wiedererkennungstest: Wenn Teilnehmende denken "ja, das haben wir gesagt", ist es gelungen. Wenn es klingt wie ein Berater, dann nicht.

**Zur nächsten Session:** Der Output von heute kann der Input für das nächste Mal werden. "Letztes Mal kam an jedem Tisch dasselbe zurück. Damit starten wir heute." So wird jede Session ein Baustein, kein loses Gespräch.

**Von Analyse zu Intervention:** Die Synthese sagt dir nicht nur, was gesagt wurde, sondern wo die Verbindungen liegen. Menschen, die denselben Kampf teilen, ohne es voneinander zu wissen. Das sind die Anknüpfungspunkte, die du nutzen kannst, um Menschen zu verbinden: in der nächsten Session, bei informellen Begegnungen oder zwischen Gruppen, die nicht beieinander saßen.

---

## Spannungen

**Steuern versus loslassen**
Wenn du den AI-Output zwischen Runden zeigst, steuerst du die nächste Gruppe. Sie reagieren auf das, was da steht, nicht auf das, was sie selbst gedacht hätten. Die Spannung: Verlierst du unbefangenen Input, indem du zu viel zeigst?

*Mein Ansatz:* Bei parallel spielt das keine Rolle: Jeder Tisch führt ein unabhängiges Gespräch, und die Synthese findet im Nachhinein statt, wenn alle Gruppen bereits ausgesprochen haben. Es gibt keinen Moment, in dem AI-Output das Gespräch steuern kann. Bei nacheinander und durchlaufen ist es eine bewusste Entscheidung: Du willst aufbauen, nicht neu anfangen. Aber beginne immer mit "Stimmt dieses Bild?" bevor du weitergehst. Das ist keine Formalität; es ist die Rückkopplung an die Gruppe, die gerade gesprochen hat.

**Technik versus Aufmerksamkeit**
Telefon auf dem Tisch, Aufnahme an, AI dazwischen. Das Risiko: Die Technik lenkt vom Gespräch ab. Die Spannung: Wie hältst du den Fokus auf den Menschen?

*Mein Ansatz:* Der Tischgastgeber ist der Schlüssel. Er begleitet das Gespräch, nicht die Technik. "Vergiss das Telefon, das hört mit. Erzähl."

---

## Sicherheits-Checkliste

- [ ] Derselbe Prompt pro Tisch (Vergleichbarkeit)?
- [ ] Prompts vor der Session getestet?
- [ ] Drehbuch mit Aufnahmemomenten klar?
- [ ] Tischgastgeber über ihre Rolle gebrieft?
- [ ] Bildschirm für Rückkopplung verfügbar?
- [ ] Wiedererkennungstest geplant: "Stimmt dieses Bild?"

---

## Probiere es selbst aus

*Du brauchst eine bevorstehende Session mit mehreren Gruppen.*

1. **Wähle deine Arbeitsform.** Parallel, wenn du vergleichen willst. Nacheinander, wenn Gruppen aufeinander aufbauen sollen. Durchlaufen, wenn du live ein Dokument aufbauen willst.

2. **Entwirf zuerst deine Fragen.** Bevor du an AI denkst: Welche Puzzleteile brauchst du? In welcher Reihenfolge? [Erst die Menschen prompten](../phase-2/erst-die-menschen-prompten.md) hilft dir dabei.

3. **Bereite deine Prompts vor.** Verwende den Meta-Prompt deiner gewählten Arbeitsform — der generiert alles, was du brauchst. Teste an einem früheren Transkript. Schau, ob der Output brauchbar ist: Erkennst du wieder, was gesagt wurde?

4. **Bereite die Rückkopplung vor.** Bei parallel: Plane einen Moment am Ende, um die Synthese zu teilen. Bei nacheinander: Briefing des Vorsitzenden, wie er den AI-Output einführt. Bei durchlaufen: Stelle sicher, dass der Bildschirm bereitsteht.

5. **Im Nachhinein: Halte fest, was funktioniert hat.** Nicht nur den Inhalt, sondern auch den Prozess. Was würdest du beim nächsten Mal anders machen?

---

## Verwandte Techniken

- Wie du Fragen entwirfst, die guten Input liefern: [Erst die Menschen prompten](../phase-2/erst-die-menschen-prompten.md) beschreibt, wie du vom Sessionziel aus rückwärts zu den richtigen Fragen und Puzzleteilen arbeitest
- Das Kernprinzip (erst einzeln analysieren, dann synthetisieren): [Einführung Phase 3](../../phase-3-skalierung.md)
- Von einem Gespräch zu einem Plan: [Vom Gespräch zum Plan](../phase-2/gespraech-zum-plan.md)
- Verschiebungen über längere Verläufe verfolgen (mehrere Sessions über Wochen oder Monate): [Muster über Zeit](muster-ueber-zeit.md)
- Live-Reflexion während des Gesprächs selbst: [Live-Reflexion mit AI](../phase-2/live-reflexion-mit-ai.md)

---

← [Zurück: Muster über Zeit](muster-ueber-zeit.md) | [Zurück zu Phase 3: Skalierung](../../phase-3-skalierung.md) | [Weiter: Eigenverantwortung wachsen sehen](ownership-wachstum.md) →

---

*"Die Facilitatoren hatten die Puzzleteile bereits in Stücke geschnitten. Meine Rolle war es, mit AI zu ernten, was sie gesammelt hatten."*
