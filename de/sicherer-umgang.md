# Sicherer Umgang mit AI

> *Datenschutz, Grenzen und verantwortungsvoller Einsatz.*

---

## Die Grundprinzipien

Mit AI und sensiblen Gesprächen zu arbeiten erfordert bewusste Entscheidungen. Nicht weil AI grundsätzlich unsicher ist, sondern weil die Hürden so niedrig sind, dass man leicht vergisst, was man teilt.

### 1. Wisse, wohin deine Daten gehen

**Cloud vs. Lokal:**
- Cloud-Dienste (ChatGPT, Claude, Notion.ai) speichern Daten auf Servern
- Lokale Tools (MacWhisper) verarbeiten alles auf deinem eigenen Gerät

**Die Wahl:**
| Situation | Empfehlung |
|-----------|----------------|
| Sensible Gespräche (therapeutisch, Personalfragen) | Lokal |
| Interne organisatorische Angelegenheiten | Sorgfältig abwägen, Richtlinie prüfen |
| Öffentliche oder weniger sensible Inhalte | Cloud ist in Ordnung |
| Im Zweifel | Lokal |

### 2. Frage um Erlaubnis

**Beim Aufnehmen:**
> "Ich nehme dieses Gespräch auf, damit wir nachschauen können, was gesagt wurde. Die Aufnahme bleibt bei mir und wird nur für [Zweck] verwendet. Ist das für alle in Ordnung?"

Achte auf nonverbale Signale. Nicht jeder spricht auf, wenn etwas unangenehm ist.

**Beim Teilen mit AI:**
Wenn du Transkripte an Cloud-Dienste sendest: Wissen die Teilnehmenden das? Explizit zu sein ist respektvoll.

### 3. Anonymisiere wo nötig

**Was anonymisieren:**
- Namen von Einzelpersonen
- Identifizierende Details (Rollen, Abteilungen, bestimmte Situationen)
- Alles, was auf Einzelpersonen zurückführbar ist

**Wann:**
- Immer bei sensiblen Inhalten
- Immer beim Teilen außerhalb des direkten Kontextes
- Im Zweifel: anonymisieren

---

## Die Prompt-Absicherungen

Verwende bei jedem Prompt für sensible Gespräche diese Absicherungen:

### Strikt auf Basis des Transkripts

```prompt
Basiere dich strikt auf das, was geschrieben steht, keine Erfindungen.
```

Das verhindert, dass AI Informationen hinzufügt, die nicht vorhanden sind.

### Im Zweifel: kennzeichnen

```prompt
Im Zweifel: formuliere als "möglicherweise" oder "es scheint, als ob" statt als definitive Aussagen.
```

Das verhindert, dass AI Sicherheit simuliert, die nicht existiert.

### Sprache bewahren

```prompt
Verwende die genauen Worte und Formulierungen der Teilnehmenden. Kein Umschreiben in Fachsprache.
```

Das verhindert, dass Eigenverantwortung durch Übersetzung verschwindet.

### AI-Output kennzeichnen

```prompt
Mache eine explizite Unterscheidung zwischen dem, was die Teilnehmenden gesagt haben, und dem, was AI beobachtet.
```

Das verhindert, dass AI-Interpretationen mit dem verwechselt werden, was tatsächlich gesagt wurde.

---

## Checkliste pro Session

### Vor der Session

- [ ] Erlaubnis für Aufnahme vorbereitet
- [ ] Entschieden: Cloud- oder lokale Verarbeitung
- [ ] Klarheit darüber, wer Zugang zum Output hat

### Nach der Session

- [ ] Transkript/Aufnahme sicher gespeichert
- [ ] Anonymisierung wo nötig
- [ ] Teilnehmende informiert, was mit ihrem Input passiert

### Bei jedem Prompt

- [ ] "Strikt auf Basis des Transkripts"-Anweisung hinzugefügt?
- [ ] "Im Zweifel: möglicherweise"-Anweisung hinzugefügt?
- [ ] Anweisung zur Sprachbewahrung enthalten?
- [ ] AI-Output klar als AI gekennzeichnet?
- [ ] Datenschutz für das verwendete Tool geprüft?

---

## Tool-Auswahl

| Tool               | Typ                 | Datenschutzniveau                                |
| ------------------ | ------------------- | ------------------------------------------------ |
| **MacWhisper**     | Lokale Transkription | Hoch: alles bleibt auf deinem Gerät             |
| **Dembrane**       | Cloud + Echtzeit    | Hoch-mittel: für Facilitation gebaut, datenschutzorientiert, europäische Server |
| **Notion.ai**      | Cloud-Transkription | Niedriger: Daten auf externen Servern            |
| **ChatGPT/Claude** | Cloud AI            | Niedriger: Daten können für Training genutzt werden* |
| **Lokale LLMs**    | Lokale AI           | Hoch: alles bleibt lokal                         |

*Aktuelle Bedingungen prüfen, diese ändern sich regelmäßig.

---

## Wann AI nicht einsetzen

Manche Gespräche gehören nicht in die AI-Verarbeitung, nicht einmal lokal:

- **Kriseninterventionen**: Der Fokus muss zu 100% auf der Person liegen
- **Wenn Vertraulichkeit absolut ist**: Manches gehört nur den Menschen im Raum
- **Wenn du spürst, dass es nicht passt**: Vertraue diesem Gefühl

AI ist ein Werkzeug. Nicht jede Situation verlangt nach einem Werkzeug.

---

## Die ethische Ebene

### Eigenverantwortung respektieren

Wenn du Output generierst, der auf den Worten anderer basiert, gehört dieser Output nicht dir. Es ist eine Verarbeitung ihres Inputs.

**Konsequenz:** Teile es nicht einfach. Prüfe, ob die Menschen sich darin wiedererkennen. Frage um Erlaubnis für die Verwendung.

### Transparenz

Menschen haben das Recht zu wissen:
- Dass sie aufgenommen werden
- Was mit der Aufnahme passiert
- Dass AI bei der Verarbeitung beteiligt ist
- Was mit dem Output passiert

### Menschen bleiben letztverantwortlich

AI generiert, du entscheidest. Der Output ist ein Vorschlag, keine Schlussfolgerung.

**Konsequenz:** Prüfe, was AI erstellt. Kontrolliere, ob es korrekt ist. Übernimm Verantwortung für das, was du teilst.

---

## Die Grenzen von AI

AI ist leistungsfähig, hat aber Grenzen, die für den sicheren Umgang relevant sind:

**AI kann überzeugend klingen, aber falsch liegen:**
Ein selbstsicherer Ton ist keine Garantie für Wahrheit. Überprüfe alles, was wichtig ist.

**AI verpasst, was nicht in Worte gefasst wurde:**
Sie liest, was geschrieben steht, nicht was in der Luft lag: den Blick, den Seufzer, die Atmosphäre im Raum.

**AI findet oft etwas; die Frage ist, ob es bedeutsam ist:**
Nicht alles, was AI sieht, ist ein Muster. Prüfe es gegen deine eigene Erfahrung.

**AI wägt Ethik nicht automatisch ab und trägt die Konsequenzen nicht:**
Du kennst die Menschen, du stehst in Beziehung zu ihnen, du bist derjenige, der ihnen in die Augen schaut. Diese Verantwortung bleibt bei dir.

---

## Zusammenfassung

**Der Kern:**
Wisse, wohin deine Daten gehen. Frage um Erlaubnis. Anonymisiere wo nötig. Verwende Absicherungen in deinen Prompts. Kennzeichne AI-Output als AI. Bleibe verantwortlich.

**Die Haltung:**
AI als leistungsfähiges Werkzeug, nicht als Autorität. Menschen bleiben letztverantwortlich.

**Der Check:**
Frage dich im Zweifel: "Wäre es mir recht, wenn die Menschen in diesem Gespräch genau wüssten, was ich hiermit mache?"

---

← [Zurück zum Anfang](warum.md)

---

*"Die Hürden sind niedrig. Das macht es einfach, und genau deshalb ist es wichtig, bewusst zu entscheiden."*
