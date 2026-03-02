# Live-Reflexion mit AI

> *Genau im richtigen Moment stellt AI die Frage, die der Gruppe hilft, weiterzukommen.*

**Phase:** [Phase 2: Vertiefung](../../phase-2-vertiefung.md)
**Baut auf:** [Transkription als Fundament](../phase-1/transkription.md), jetzt in Echtzeit als Interventionsinstrument

---

## Wann ist das relevant?

**Situation:** Du facilitierst ein Gespräch. Die Energie sinkt, Leute wiederholen sich, das Gespräch dreht sich im Kreis. Oder: es gibt eine spürbare Spannung, die niemand benennt.

**Meine Tendenz:** Ich werde besser darin, meiner Intuition zu vertrauen und Dinge explizit zu benennen. Gleichzeitig zweifle ich manchmal noch und hoffe, dass jemand anders es ausspricht.

**Was hier hilft:** Wenn du unsicher bist, oder wenn du weißt, was hinter dem Echo-Knopf steckt, hast du einen Co-Facilitator, der mit dem gesamten Transkript arbeiten kann. Als Mensch hast du begrenzten Speicher im Kopf, egal wie aufmerksam du zuhörst. Der Echo-Knopf betrachtet das Gespräch aus einer anderen Perspektive und kann dir so helfen.

**Die Frage:** Was würde passieren, wenn du in diesem Moment ein zusätzliches Paar Augen hättest; einen Co-Facilitator, der das gesamte Gespräch gehört hat?

---

## Die Frage, die das Gespräch öffnete

*Vielleicht kennst du diese Geschichte schon von der [Warum-Seite](../../warum.md). Hier gehen wir tiefer auf das Timing ein: den richtigen Moment für die richtige Frage.*

Eine Sitzung über Stadtteil-Transformation. Acht Personen sprechen 45 Minuten lang über die Spannung zwischen Systemanforderungen und einem menschenzentrierten Ansatz. Die Energie beginnt zu sinken.

Facilitator Jeroen drückt den Echo-Knopf. Innerhalb von 10 Sekunden generiert AI diese Frage:

> "Angesichts der Herausforderungen, die ihr beschreibt, scheint es entscheidend, mit kleinen erreichbaren Schritten zu beginnen, die direkte Wirkung im Stadtteil haben. Können wir an ein Beispiel für so eine konkrete Aktion denken, die wir morgen starten könnten, ohne in Systemanforderungen steckenzubleiben?"

Die Reaktion kam sofort.

> "Das ist schon etwas."
> "Das ist die bekannte Frage, wie fangen wir morgen mit etwas Kleinem an?"
> "Gut gemacht!"
> "Ja, das ist es."

10 Sekunden. Eine Frage. Das festgefahrene Gespräch kam in Bewegung.

---

## Live versus Semi-Live

Es gibt einen wichtigen Unterschied darin, wie du AI während Sitzungen einsetzt.

**Live (der Echo-Knopf):**
Direkt in der Sitzung, mit einem Knopfdruck. AI analysiert die letzten Minuten und generiert sofort eine Frage. Das funktioniert mit Tools wie Dembrane, die Echtzeit-Transkription mit Prompt-Funktionalität koppeln.

**Semi-Live (Zwischenmomente):**
Zwischen Blöcken. Zum Beispiel: während Gruppen in Breakout-Sessions arbeiten, nimmst du das bisherige Transkript, lässt einen längeren Prompt laufen und kopierst die Ausgabe in ein Google Doc, das der Facilitator dann der Gruppe auf dem Bildschirm zeigen kann.

Der Unterschied liegt in Geschwindigkeit und Kontext:
- **Live:** Sekunden. Arbeitet mit den letzten Minuten. Geeignet für Intervention im Moment.
- **Semi-Live:** 1-2 Minuten, je nach deinem Workflow. Arbeitet mit längeren Abschnitten. Geeignet für Zwischensynthese und Reflexion.

Beides erfordert Vorbereitung: deine Prompts müssen bereit sein. Der Unterschied liegt darin, wann du sie einsetzt und wie viele Schritte dazwischen liegen, vom Ausführen des Prompts bis zum Zeigen auf dem Bildschirm:

Prompt ausführen → Ausgabe kopieren → in Dokument einfügen → der Gruppe zeigen

Je weniger Zwischenschritte, desto schneller.

---

## Was macht den Echo-Knopf besonders?

Der Echo-Knopf ist keine Zusammenfassung. Er ist eine (Mini-)Intervention.

**Zusammenfassung:** "Ihr habt über X, Y und Z gesprochen."
**Echo:** "Ihr habt viel über 'Kommunikationsprobleme' gesprochen. Was meint ihr genau? Kann jemand einen konkreten Moment beschreiben?"

Der Unterschied liegt in der Frage. Eine Zusammenfassung schließt ab. Ein Echo öffnet.

**Die drei Ebenen:**
| Ebene | Was es tut | Beispiel |
|-------|-----------|----------|
| **Spiegel** | Spiegelt zurück, was gesagt wurde | "Ihr habt X, Y und Z erwähnt" |
| **Synthese** | Verbindet Muster | "Was auffällt: alle erwähnen 'Zeit', aber meinen etwas Unterschiedliches" |
| **Serendipität** | Stellt die Frage, die nicht gestellt wurde | "Was würde sich ändern, wenn X nicht das Problem wäre?" |
Das Echo arbeitet auf allen drei Ebenen: es spiegelt, verbindet und fragt weiter, je nach den Prompts, die du konfiguriert hast.

---

## Der Prompt

Das ist der funktionsfähige Echo-Prompt aus einem Führungsworkshop.

```prompt
**Rolle:** Du bist ein erfahrener Experte für Gruppendynamik, der
Signale von vermiedenen Themen, unausgesprochenen Spannungen und
unterschiedlichen Perspektiven in Dialogen erkennt.

**Kontext:** Du analysierst die letzten 10-15 Minuten einer
[SITZUNGSTYP]. Die Teilnehmenden sind [WER]. Sie kennen sich [BEZIEHUNG].

**Erforderlicher Stil:**
- Wertfrei und einladend
- Fokus auf das, was fehlt, nicht auf das, was falsch ist
- Diplomatische Sprache erkennen, die zugrundeliegende Spannungen verdeckt

**Kritische Einschränkungen:**
- Signale streng auf Basis des Transkripts, keine Annahmen
- Zwischen Schweigen und Konsens unterscheiden
- Im Zweifel: "Möglicherweise unterbelichtet" statt definitiver Aussagen
- Maximal 2 Echo-Fragen für den Facilitator generieren
- Fokus auf den letzten Teil des Gesprächs

**Anweisungen:**
1. Analysiere die letzten 10-15 Minuten des Transkripts
2. Identifiziere Themen, die angesprochen aber nicht vertieft wurden
3. Erkenne Momente, in denen die Energie sank oder das Thema wechselte
4. Suche nach Unterschieden in der Rahmung zwischen Teilnehmenden
5. Erkenne "Ja, aber..."-Muster als Spannungssignale
6. Wähle eine kraftvolle Echo-Frage, die das wichtigste Thema adressiert

**Ausgabeformat:**
### Was ich beobachte
**Möglicherweise unterbelichtet:** [Themen, die nicht vertieft wurden]

**Unterschiedliche Rahmungen:**
- "Zitat darüber, wie dies betrachtet wird"
- "Zitat, das anders nuanciert"

### Echo-Frage für die Gruppe
**[Eine kraftvolle Frage, die zur tieferen Erkundung einlädt]**

### Über dieses Echo
Dieses Echo ist ein Werkzeug, um mögliche blinde Flecken zu
beleuchten, nicht um zu urteilen. Die Entscheidung, damit zu
arbeiten, bleibt bei euch.
```

**Warum diese Struktur funktioniert:**
- **Rolle** definiert die Expertise: "Experte für Gruppendynamik" steuert auf das Erkennen dessen, was nicht gesagt wird
- **Kontext** macht es spezifisch: "letzte 10-15 Minuten" verhindert, dass AI versucht, alles zu erfassen
- **Erforderlicher Stil** schützt den Ton: "wertfrei" verhindert, dass das Echo wie Kritik wirkt
- **Kritische Einschränkungen** sind die harten Grenzen: "maximal 2 Echo-Fragen" verhindert Überwältigung
- **Anweisungen** steuern den Suchprozess: die Abfolge (erst analysieren, dann erkennen, dann wählen) gibt Fokus
- **Ausgabeformat** strukturiert die Ausgabe: "eine kraftvolle Frage" erzwingt Auswahl

**Quelle:** Prompt, den ich für Live-Gruppenreflexion verwende (Führungsworkshop)

---

## Drei Taktiken

**VERTIEFEN:**
Einsetzen, wenn das Gespräch an der Oberfläche bleibt. Leute benennen Symptome, aber nicht die zugrundeliegenden Anliegen.

> "Ihr habt viel über 'Kommunikationsprobleme' gesprochen. Was meint ihr genau? Kann jemand einen konkreten Moment beschreiben?"

**KONKRETISIEREN:**
Einsetzen, wenn das Gespräch abstrakt bleibt: viel Theorie, aber keine konkreten nächsten Schritte.

> "Angesichts dessen, was ihr teilt: was könnte ein erster kleiner Schritt sein, der morgen unternommen werden könnte?"

**REFLEKTIEREN:**
Einsetzen, wenn die Verbindung zwischen Perspektiven fehlt.

> "Ich höre, dass Tisch Rot 'mehr Zeit' will, aber Tisch Blau sagt 'zu viele Meetings'; könnte 'Zeit' für beide Gruppen etwas anderes bedeuten?"

---

## Wann einsetzen, wann nicht

**Wann JA:**

| Signal | Was du tust |
|--------|-------------|
| Energie sinkt, Gespräch dreht sich im Kreis | Echo mit konkretisierender Frage |
| Sitzungsende, Gruppe hat kein klares Bild | Echo mit reflektierender Frage |
| Spannung spürbar, aber unbenannt | Echo mit vertiefender Frage |
| Neue Phase beginnt, Brücke zur vorherigen nötig | Echo als Öffnung |

**Wann NICHT:**

| Signal | Warum nicht |
|--------|------------|
| Jemand teilt eine persönliche Geschichte | Raum für Emotion IST die Intervention |
| Erste Sitzung, du kennst die Gruppe noch nicht | Echo kann danebengehen ohne Kontextverständnis |
| Keine strategische Vorbereitung | Schwache Prompts → AI entscheidet → Substitutionsrisiko |
| Facilitator schaut auf den Bildschirm statt auf die Leute | Echtzeit-Gruppendynamik lesen ist Menschenarbeit |

---

## Die Rollenaufteilung

Das funktioniert am besten mit zwei Personen:

**Facilitator:** Bleibt bei der Gruppe. Liest Gesichter, hält Emotionen, leitet den Prozess. Schaut nicht auf einen Bildschirm.

**Co-Facilitator:** Überwacht die Transkription, wählt die letzten Minuten aus, startet den Echo-Prompt, macht bei Bedarf schnelle Iterationen.

Wenn das Echo bereit ist, liest der Facilitator es in eigenen Worten, nicht wörtlich. Das Echo ist ein Vorschlag, kein Skript.

---

## Spannungen

**Timing der Intervention**
Zu früh fühlt sich wie Unterbrechung an. Zu spät und die Energie ist schon weg.

*Mein Ansatz:* Ich warte, bis ich spüre, dass die Gruppe irgendwo feststeckt. Oder bis ich selbst unsicher bin und nicht weiß, wie es weitergeht; dann ist das Echo eine helfende Hand.

**AI-Sprache versus eigene Stimme**
Was AI generiert, ist ein Vorschlag, kein Skript. Es wörtlich vorzulesen kann mechanisch wirken, aber wenn die Vorbereitung gründlich war, ist das auch in Ordnung.

*Mein Ansatz:* Meistens paraphrasiere ich in eigenen Worten. Aber wenn ich den Echo-Prompt gut vorbereitet habe, lese ich ihn manchmal auch wörtlich vor.

**Spontan versus vorbereitet**
Die Reflexionsfrage, die die Kreativität wieder in Gang brachte, kam nicht aus dem Nichts. Dahinter steckte strategische Vorbereitung.

*Mein Ansatz:* 80% des Erfolgs liegt in der Vorbereitung. Ich gestalte den Echo-Prompt vorher auf Basis dessen, was ich erwarte. Aber ich weiß auch, dass ich ihn wahrscheinlich anpassen muss, wenn die Sitzung in eine andere Richtung geht. Das erfordert ein Verständnis davon, *was* dein Prompt tut, nicht nur *dass* er funktioniert, damit du auf der Stelle anpassen kannst.

**Echo als Ersatz für Facilitation**
Das Echo ist ein Werkzeug, keine Lösung. Wenn ich nur Knöpfe drücke, verpasse ich, was im Raum passiert.

*Mein Ansatz:* Ich bleibe präsent. Das Echo unterstützt meine Wahrnehmung, es ersetzt sie nicht.

---

## Sicherheitscheckliste

*Für Datenschutz-Überlegungen bei Live-Transkription lies [Sicherer Umgang mit AI](../../sicherer-umgang.md).*

- [ ] Fokus auf die letzten 10-15 Minuten? (nicht das ganze Gespräch)
- [ ] "Möglicherweise unterbelichtet" statt bestimmter Behauptungen?
- [ ] Maximal 2 Echo-Fragen? (nicht überwältigen)
- [ ] AI-Beobachtungen als AI gekennzeichnet?
- [ ] Strategische Vorbereitung erledigt?

---

## Tools

| Tool | Wofür | Nuance |
|------|--------|--------|
| **Dembrane** | Echtzeit-Transkription + Echo-Knopf-Funktionalität | Geeignet für mehrere Sitzungen: alles zentral auf einer Plattform |
| **Notion AI** | Live-Transkription + AI-Prompts auf der Seite | Gut für ein Meeting, bei dem du selbst dabei bist |
| **MacWhisper + Claude/ChatGPT** | Selbst transkribieren + Echo-Prompt manuell ausführen | Am flexibelsten, am meisten manuelle Arbeit |

**Wann welches Tool:**
- **Ein Meeting, du bist selbst dabei:** Notion AI funktioniert gut. Du nimmst auf, das Transkript erscheint, du promptest AI direkt auf derselben Seite.
- **Mehrere Sitzungen, Breakout-Gruppen, oder du facilitierst:** Dembrane. Du kannst verschiedene Aufnahmen an einen Ort senden und zentral analysieren.

---

## Philosophische Vertiefung

### Timing vor Perfektion

Die Echo-Frage in der Stadtteil-Transformationssitzung war nicht besonders komplex. "Kleine erreichbare Schritte", "morgen anfangen", "ohne in Systemanforderungen steckenzubleiben": das sind keine tiefen Erkenntnisse.

Was es besonders machte, war das Timing. Nach 45 Minuten Diskussion, im Moment als die Energie sank, kam genau die Frage, die die Gruppe brauchte.

Das ist der Unterschied zwischen Analyse und Intervention. Eine perfekte Analyse eine Woche später hätte weniger Wirkung gehabt als eine gute Frage im richtigen Moment.

### Das Echo als Spiegel

Da ist noch etwas. Wenn AI die Frage stellt, ist es nicht "der Facilitator, der findet, dass..." Es ist ein externer Spiegel. Leute reagieren anders auf eine Frage, die von AI kommt, als auf dieselbe Frage vom Facilitator.

Manchmal ist diese Distanz nötig. Die Frage wird neutral, forschend, wertfrei.

Aber (und das ist entscheidend) der Facilitator muss die Frage zu seiner eigenen machen. Nicht: "AI sagt das." Sondern: "Es kommt eine Frage auf, die ich interessant finde..." Das Echo ist Input, der Facilitator ist die Stimme.

---

## Verwandte Techniken

- [Transkription als Fundament](../phase-1/transkription.md): woher das Rohmaterial kommt
- [Iteration](iteration.md): wie du die Echo-Prompts selbst weiterentwickelst
- [Intuition schwarz auf weiß](intuition-schwarz-auf-weiss.md): die Muster sichtbar machen, die du schon gespürt hast

---

← [Zurück: Fragen umrahmen](fragen-umrahmen.md) | [Zurück zu Phase 2: Vertiefung](../../phase-2-vertiefung.md) | [Weiter: Vom Gespräch zum Plan →](gespraech-zum-plan.md)

---

*"10 Sekunden können 45 Minuten Dialog verwandeln. Nicht durch die perfekte Frage, sondern durch die Frage im perfekten Moment."*
