# Was noch darin steckte

> *Gemeinsam mit AI nach Tiefe in deinem Transkript suchen.*

**Phase:** [Phase 2: Vertiefung](../../phase-2-vertiefung.md)
**Baut auf:** [Transkription als Grundlage](../phase-1/transkription.md), gemeinsam graben in dem, was darin steckt

---

## Wann ist das relevant?

**Situation:** Du hattest eine Sitzung, vielleicht eine der [Vertiefungssitzungen aus Phase 2](../../phase-2-vertiefung.md). Das Gespräch war wertvoll. Aber du weißt: Da steckt mehr drin, als du auf Anhieb benennen kannst.

**Die Tendenz:** Auf das vertrauen, was du dir gemerkt hast. Oder eine schnelle Zusammenfassung machen und zum nächsten Punkt übergehen.

**Das Prinzip:** Das Transkript ist kein Endprodukt; es ist Rohmaterial. Mit den richtigen Fragen kannst du mehr herausholen, als du live aufnehmen konntest. Nicht weil du etwas verpasst hast, sondern weil einfach mehr darin steckt, als eine Person in einem Moment verarbeiten kann.

**Die Frage:** Was würde an die Oberfläche kommen, wenn du gemeinsam mit AI zu graben anfingst?

---

## Die Geschichte: gemeinsam nach Tiefe suchen

*Diese Geschichte über das Online-Treffen kennst du vielleicht schon aus [Phase 1](../../phase-1-start.md). Hier gehen wir tiefer darauf ein, wie wir gemeinsam mit AI nach Tiefe gesucht haben.*

Maarten organisierte ein Online-Treffen über smartphonefreie Kindheit. Vierzehn Eltern teilten ihre Kämpfe über Bildschirmzeit, Gaming und das Gefühl, allein dazustehen. Wertvolle Menschenarbeit.

Danach wollte er mehr herausholen. Nicht weil er etwas verpasst hatte, sondern weil er wusste, dass Muster darin steckten, die er nicht sofort benennen konnte.

Er kam zu mir. Wir machten uns gemeinsam an die Arbeit.

**Der Prozess:**
1. Ich transkribierte unser Gespräch live mit Notion AI
2. Gab das an AI mit der Frage: "Hilf mir, einen Analyse-Prompt dafür zu bauen"
3. AI stellte drei Fragen, jeweils mit zwei Optionen
4. Maarten gab Richtung und Nuancierung

**Die Fragen, die AI stellte:**

> "Fokus auf die emotionale Innenwelt ODER auf die Handlungsbereitschaft?"

Maarten: "Ich will beides. Die Handlungsbereitschaft entsteht aus der emotionalen Innenwelt."

> "Rahmen von Heuchelei/Schuld ODER vom Wunsch, ein guter Elternteil zu sein?"

Maarten: "Vom Positiven aus. Menschen sind viel motivierter durch das, was sie wollen, als durch Schuld."

> "Output als Gesprächsfächer (Ankerpunkte für Verbindung) ODER als Kampagnenmonitor (Lücken und Chancen)?"

Maarten: "100% Gesprächsfächer. Verbindung schaffen ist das Wichtigste. Ich will die Ankerpunkte, aber ich entscheide selbst, wie ich sie teile."

**Was an die Oberfläche kam:**

Konkrete Ankerpunkte für Gespräche mit anderen Eltern. Momente aus dem Gespräch, die Menschen verbinden könnten, wenn Maarten wüsste, wo er sie findet.

Und ein Zitat, das den Kern traf:

> "Dein Kind fährt zum ersten Mal mit dem Fahrrad zur Schule, Helm auf. Kommt nach Hause und sagt: 'Niemand in der Klasse trägt einen Helm. Ich zieh ihn auch nicht auf, sonst gehör ich nicht dazu.'"

Das stand im Transkript. Durch gemeinsames Graben kam es an die Oberfläche, bereit zur Weiterarbeit.

**Quelle:** Das Iterationsgespräch und Maartens Substack: [Wat ik niet hoorde in mijn eigen meeting](https://kampvuur.substack.com/p/wat-ik-niet-hoorde-in-mijn-eigen)

---

## Der Prompt-Ansatz

Unten stehen die Prompts, die wir tatsächlich in der Geschichte oben verwendet haben.

### Schritt 1: AI bitten, beim Prompt-Bau zu helfen

Anstatt direkt einen Analyse-Prompt zu schreiben, bat ich AI mitzudenken:

```prompt
Ich habe gerade mit Maarten über seine Reise zum Thema
smartphonefreie Kindheit gesprochen. Was ich für dich hinzugefügt
habe, ist Kontext darüber, wie Maarten das Treffen vorbereitet
hat — seine Wünsche und Absichten — und das Transkript des
Treffens selbst.

Was wir suchen, ist ein Prompt, um das Transkript zu analysieren.
Um Maarten in seiner Mission zu unterstützen.

Bevor wir diesen Prompt schreiben, hätte ich gern, dass du uns
ein paar Fragen stellst, um den Prompt zu schärfen. Stell uns
drei Fragen, jeweils mit zwei Optionen.

Und ein sehr wichtiges Element: Wir sprechen immer in der Sprache
der Teilnehmenden, mit Fokus auf Wiedererkennbarkeit. Und wir
bleiben weg von einzelnen Namen.
```

*Quelle: Der Eröffnungsprompt, den wir zum Start des Iterationsgesprächs verwendeten.*

### Schritt 2: Maarten gibt Richtung

AI stellte drei Richtungsfragen (siehe die Geschichte oben). Maartens Entscheidungen formten den Prompt:

- Emotionale Innenwelt und Handlungsbereitschaft (nicht entweder/oder, sondern beides)
- Vom Positiven aus (nicht von Schuld)
- Gesprächsfächer (nicht Kampagnenmonitor)

Dreimal korrigierte und nuancierte er. Der Prompt wurde nicht von AI bestimmt; Maarten steuerte auf Basis von AIs Vorschlägen.

### Schritt 3: Der resultierende Prompt

Auf Basis von Maartens Antworten baute AI diesen Prompt:

```prompt
# KONTEXT & ROLLE
Du fungierst als systemischer Stratege, der [Den Initiator] unterstützt.
Er hat eine lokale Arbeitsgruppe gegründet mit dem Ziel:
Smartphone-Nutzung bei Kindern hinauszuzögern.

# AUFTRAG
Analysiere das Transkript und erstelle:
1. Einen strategischen Überblick ("Die Riesenkarte")
2. Einen praktischen Gesprächsleitfaden ("Der Gesprächsfächer")

Das Ziel ist nicht, Menschen mit Fakten zu überzeugen, sondern
Verbindung zu schaffen auf Basis gemeinsamer Werte und Sorgen.

# EINSCHRÄNKUNGEN
- Datenschutz: Verwende KEINE echten Namen
- Sprache: Verwende die *wörtlichen Worte* der Teilnehmenden
- Ton: Empathisch, fokussiert auf den Wunsch, ein guter Elternteil zu sein
- Format: Konkrete Ankerpunkte, keine wörtlichen Skripte

# OUTPUT (in 3 Teilen)

## TEIL 1: DIE ZWEI HEATMAPS
Pro Schulphase (Kindergarten vs. Mittlere Grundschule vs. Späte Grundschule):
A. Die Emotionale Innenwelt: Ängste, Zweifel, dahinterliegende Werte
B. Die Handlungsbereitschaft: Wo ist die Energie, wer spürt Dringlichkeit

## TEIL 2: DER INNERE KAMPF
Die Spannung zwischen eigenem Handygebrauch und dem, was wir für
unser Kind wollen. Rahme das als Herausforderung, nicht als Heuchelei.

## TEIL 3: DER GESPRÄCHSFÄCHER
Konkrete 'Ankerpunkte' pro Zielgruppe für informelle Gespräche.
Fokus auf Gemeinsames, nicht auf Überzeugen.
```

**Warum diese Struktur funktioniert:**
- "Systemischer Stratege" positioniert AI als analytischen Denker, nicht als Zusammenfasser
- "Wörtliche Worte" schützt Teilnehmersprache vor AI-Interpretation
- "Empathisch, fokussiert auf den Wunsch, ein guter Elternteil zu sein" Maartens Tonkorrektur, eingebaut in den Prompt
- "Konkrete Ankerpunkte, keine wörtlichen Skripte" Output, den Maarten selbst einsetzen kann, auf seine Art

**Quelle:** Der Prompt, den wir nach dem Iterationsgespräch gemeinsam mit AI gebaut haben.

---

## Was das gebracht hat

Der Prompt lieferte drei Arten von Ergebnissen. Hier zeige ich pro Abschnitt, was an die Oberfläche kam.

### Die Heatmaps (Abschnitt 1)

Das Gespräch hatte eine Reichhaltigkeit, die du live nicht ordnen konntest. Abschnitt 1 des Prompts bat AI, Struktur zu finden: keine Zusammenfassung, sondern Ordnung. Welche Themen kehren wieder? Wie hängen sie zusammen?

Was AI fand: "Heatmaps" pro Schulphase. Eine Struktur, die intuitiv vorhanden war, aber jetzt schwarz auf weiß:

| Phase | Die Atmosphäre | Was los ist |
|-------|----------------|-------------|
| Kindergarten & frühe Grundschule | "Paradies" | Unbewusstheit, Vorsicht: "Bin ich diese nervige Mutter, wenn ich das jetzt schon anspreche?" |
| Mittlere Grundschule | "Die Dämmerzone" | Verwirrung, erster Druck: "Alle haben eins, sagt mein Kind." |
| Späte Grundschule | "Realität" | Angst vor Ausgrenzung: "Wir sind eigentlich schon zu spät dran." |

Das Ergebnis ist keine gekürzte Version des Gesprächs; es ist eine Karte von dem, was darin steckt.

### Der innere Kampf (Abschnitt 2)

Abschnitt 2 zoomte auf die Spannung, die sich durch das gesamte Gespräch zog: Eltern, die mit ihrem eigenen Handygebrauch ringen und gleichzeitig ihre Kinder schützen wollen. Der Prompt bat explizit darum, das nicht als Heuchelei zu rahmen, sondern als gemeinsame Herausforderung.

Was AI fand: Kernthemen, bei denen Eltern mit ihrer Vorbildfunktion kämpfen. Die Ehrlichkeit steckte schon im Transkript:

> "Ich bin wirklich schlimm mit meinem Smartphone. Wie kann ich es verbieten, wenn ich selbst ständig draufschaue?"

Das ist der Spiegel, den niemand laut ausspricht, aber jeder wiedererkennt. Indem diese Spannung explizit gemacht wurde (als Herausforderung, nicht als Anklage), wurde es etwas, worüber man reden konnte.

### Der Gesprächsfächer (Abschnitt 3)

Abschnitt 3 fragte nach konkreten Ankerpunkten: Momente im Gespräch, die Menschen verbinden können, wenn du weißt, wo du sie findest.

Was AI fand, konkrete Gesprächsöffner pro Zielgruppe:

Für Eltern von Kindergartenkindern:
> "Gerade haben wir noch Zeit, das gemeinsam zu regeln. Später müssen wir diesen Kampf nicht mehr führen."

Für Eltern in der mittleren Grundschule:
> "Stehst du auch allein in dieser Minecraft-Diskussion? Lass uns zusammentun."

Für Eltern in der späten Grundschule:
> "Was würdest du anders machen, mit dem, was du jetzt weißt?"

Zwei Eltern, die beide kämpfen, sich beide allein fühlen, haben jetzt einen Ankerpunkt, um sich zu finden.

### Treffende Zitate

Das war kein separater Abschnitt im Prompt. Aber die Einschränkung "verwende die wörtlichen Worte der Teilnehmenden" sorgte dafür, dass AI die treffendsten Aussagen bewahrte, statt sie zu paraphrasieren. Das siehst du schon in Abschnitt 2: Das Spiegel-Zitat über den eigenen Handygebrauch war ein Nebenprodukt guten Framings. Manchmal liefert eine Einschränkung mehr als eine explizite Anweisung.

Das Fahrradhelm-Paradox:
> "Dein Kind fährt zum ersten Mal mit dem Fahrrad zur Schule, Helm auf. Kommt nach Hause und sagt: 'Niemand in der Klasse trägt einen Helm. Ich zieh ihn auch nicht auf, sonst gehör ich nicht dazu.'"

Dieses Zitat wurde nicht übersehen, aber auch nicht sofort als zentral erkannt. Bis AI es an die Oberfläche brachte.

---

## Die Iterationslektion

Was diese Geschichte illustriert, ist, dass die beste Analyse durch Dialog entsteht.

Maarten hat nicht einfach AIs Fragen beantwortet; er hat korrigiert und nuanciert:
- "Ich will beides" (nicht entweder/oder, sondern beides)
- "Vom Positiven aus" (Tonkorrektur)
- "Ich will die Ankerpunkte, aber ich entscheide selbst, wie ich sie nutze" (Autonomie)

Der Prompt war das Ergebnis von Zusammenarbeit. Nicht eine perfekte Frage, sondern ein Dialog, der immer schärfer wurde.

Diese Seite zeigt, wie dieser Prozess in der Praxis aussieht. Die Technik selbst (die Feedback-Formeln, die Kollaborationsformate, die Lektion der zwölf Runden) findest du in [Iteration als Dialog](iteration.md).

---

## Was du damit machst

Die Vertiefung zu finden ist Schritt eins. Die Frage ist, was du damit machst.

*Aber zuerst: Was willst du eigentlich erreichen? Es hilft, vorher darüber nachzudenken; es steuert deine Analyse.*

**Option 1: In der nächsten Sitzung darauf zurückkommen**
"Letztes Mal kam etwas hoch, das mir im Kopf geblieben ist. Über den Fahrradhelm. Können wir das weiter erkunden?"

**Option 2: Verbindungen herstellen**
Nutze die Ankerpunkte, um Menschen zu verbinden, die denselben Kampf teilen.

**Option 3: In eine Synthese einbauen**
Die Muster und Zitate werden Teil von dem, was du der Gruppe zurückgibst.

**Option 4: Persönliche Vertiefung**
Du notierst, was an die Oberfläche kam, als Input für deine nächste Sitzung. Welche Themen verdienen mehr Aufmerksamkeit?

---

## Spannungen

**Zusammenfassen versus vertiefen**
AI ein Transkript zusammenfassen lassen gibt dir ein kürzeres Transkript. Keine Vertiefung.

*Mein Ansatz:* Ich frage nach Struktur, Ankerpunkten, Schlüsselmomenten, nicht nach Komprimierung. Die Frage ist nicht "mach das kürzer", sondern "was steckt darin, das ich noch nicht benannt habe?"

**Nicht in den Dialog gehen**
Die Versuchung ist, die erste Analyse ohne Fragen oder Korrekturen zu akzeptieren.

*Mein Ansatz:* Ich stelle Folgefragen. Ich korrigiere den Ton. Ich gebe Richtung. Die beste Analyse entsteht durch Dialog.

**Vorausdenken an den nächsten Schritt**
Die Tendenz ist, zu analysieren, ohne zu wissen, was du damit machen willst. Was hilft: Bevor du anfängst, überleg dir, was du mit dem Ergebnis tun wirst.

*Mein Ansatz:* Ich plane, was ich mit der Vertiefung mache. In der nächsten Sitzung, in einer E-Mail, in der Synthese. Wenn du das vorher weißt, steuert es auch die Analyse selbst. Das ist dieselbe Logik wie beim [Deconstructed Burger](erst-die-menschen-prompten.md): Beginne beim Ziel und arbeite rückwärts zu dem, was du brauchst.

---

## Philosophische Vertiefung

### Mehr als du aufnehmen kannst

Ein Transkript ist kein Bericht über das, was passiert ist. Es ist Rohmaterial: Fundament für Tiefe.

Jedes Gespräch enthält mehr, als die Teilnehmenden im Moment verarbeiten können. Das ist kein Mangel; das ist die Natur von reichhaltiger Interaktion. Als Facilitator oder Gesprächsleiter musst du im Moment sein: zuhören, nachfragen, die Energie lesen. Du kannst nicht gleichzeitig alles analysieren und ordnen, was gesagt wird. Musst du auch nicht, denn das Transkript fängt es auf.

Transkription macht es möglich, zurückzugehen. AI macht es möglich, gemeinsam zu graben. Du bringst die Menschenarbeit ein: das Gespräch, die Energie, die Verbindung. AI hilft, mehr herauszuholen, als du im Moment aufnehmen konntest. Die Kombination eröffnet, was schon da war, aber noch nicht benannt.

Die Frage ist nicht "was habe ich verpasst?", sondern "was steckt darin, das ich noch nicht benannt habe?"

---

## Verwandte Techniken

**Andere Zugänge zur Tiefe:**
- [Intuition schwarz auf weiß](intuition-schwarz-auf-weiss.md): wenn du schon ein Gefühl hast, das du artikulieren willst (das ist die proaktive Variante)

---

← [Zurück: Intuition schwarz auf weiß](intuition-schwarz-auf-weiss.md) | [Zurück zu Phase 2: Vertiefung](../../phase-2-vertiefung.md) | [Weiter: Iteration als Dialog →](iteration.md)

---

*"Das Gespräch war wertvoll. Da steckt mehr drin, als du live aufnehmen konntest. Lass uns gemeinsam graben."*
