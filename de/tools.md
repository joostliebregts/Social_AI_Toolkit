# Tools

> Welche Tools nutzt du wann? Ein Überblick.

---

Das Tool zählt weniger als das, was du damit machst. Aber es hilft zu wissen, was es gibt und was jedes einzelne ausmacht.

---

## Auf einen Blick

| Tool | Was es tut | Wann |
|------|--------------|------|
| **MacWhisper** | Diktat + lokale Transkription | Du willst diktieren, Datenschutz ist wichtig |
| **Claude** | Durchdacht, prägnant | Tiefere Analyse, ethische Überlegungen |
| **ChatGPT** | Ausführlich, breit | Schnelles Sparring, viele Integrationen |
| **Gemini** | 1M Kontext, filtert Rauschen | Große Dokumente, Cross-Model-Check |
| **T3 Chat** | Multi-Model-Interface | Modelle vergleichen, Preis/Leistung |
| **Claude Code + Finn** | Agentische Zusammenarbeit | Feldanleitung/Prompt-Entwicklung |
| **Dembrane** | Live-Transkription + Echo | Echtzeit-Feedback in Sessions |
| **Notion AI** | AI in deinem Workspace | Alles an einem Ort, Kontext |
| **NotebookLM** | Quellen in andere Formate | Podcasts, Videos, Folien erstellen |

---

## Diktat + Transkription (lokal)

### <img src="/icons/tools/macwhisper.jpg" alt="" width="24" height="24" /> MacWhisper

**Was ist das?**
Eine Mac-App, die Sprache in Text verwandelt, komplett auf deinem eigenen Computer, ohne dass etwas in die Cloud geht. Entwickelt von Jordi Bruin, basierend auf OpenAIs Whisper-Technologie.

**Warum ich es nutze:**
Diktat ist der Hauptgrund. Es verändert den gesamten Workflow: diktieren, AI, diktieren, AI. Die Schwelle, Gedanken festzuhalten, sinkt auf fast null. Feedback an AI geben, Beobachtungen nach einer Session einsprechen, laut denken. Das geht alles schneller als tippen.

**Bonus: Privacy-first**
Alles passiert lokal auf deinem Mac. Kein Audio an Server, kein Text in die Cloud. Nützlich für sensible Gespräche.

**Was es besonders macht:**
Mit neueren Modellen (wie Parakeet 3) kann eine Stunde Audio in 1-2 Minuten transkribiert werden. Die alte Annahme, dass lokal langsamer ist, wird immer weniger wahr.

---

## AI-Modelle

**Warum drei Modelle?**
Ich arbeite hauptsächlich mit dreien: Claude, ChatGPT und Gemini. Es gibt inzwischen Dutzende, aber das sind die drei, die ich am meisten nutze. Was mir auffällt: Sie wirken ähnlich, bis du sie häufig verwendest. Dann spürst du die Unterschiede.

Es ist wie drei Berater zu haben. Die gleiche Frage, aber unterschiedlicher Stil, unterschiedliche Tiefe, unterschiedliche Annahmen.

### <img src="/icons/tools/claude.svg" alt="" width="24" height="24" /> Claude (Anthropic)

**Was ist das?**
Ein AI-Assistent von Anthropic, gegründet von ehemaligen OpenAI-Forschern. Anthropic zeichnet sich durch einen starken Fokus auf AI-Sicherheit aus: Sie haben ein Team, das sich mit den langfristigen Auswirkungen von AI auf die Menschheit beschäftigt.

**Wie es sich anfühlt:**
Was mir auffällt: durchdacht. Manchmal bekommst du zwei Sätze, wenn das reicht. Weniger "hier ist alles, was ich weiß", mehr auf den Punkt.

**Wann einsetzen:**
- Tiefere Analyse von Transkripten
- Iteration an Synthesen
- Komplexe Prompt-Entwicklung
- Wenn du nuancierte, prägnante Antworten willst

### <img src="/icons/tools/chatgpt.svg" alt="" width="24" height="24" /> ChatGPT (OpenAI)

**Was ist das?**
Der AI-Assistent von OpenAI, dem Unternehmen, das die Welle der generativen AI mit GPT-3 ausgelöst hat. ChatGPT war das erste massenhaft genutzte AI-Tool und ist immer noch das bekannteste.

**Wie es sich anfühlt:**
Ausführlich. So wie ich es sehe, liegt die Hilfsbereitschaft von ChatGPT in seiner Reichhaltigkeit und seinem Umfang: Antworten sind oft lang und detailliert. Wird zunehmend kommerzieller.

**Wann einsetzen:**
- Sparring und schnelle Analyse
- Breit verfügbar, viele Integrationen
- Wenn du ausführliche, detaillierte Antworten willst

### <img src="/icons/tools/gemini.svg" alt="" width="24" height="24" /> Gemini (Google)

**Was ist das?**
Googles AI-Assistent, basierend auf ihren eigenen Sprachmodellen. Zeichnet sich durch ein enormes Kontextfenster aus (1 Million Tokens). Du kannst ganze Bücher eingeben.

**Wie es sich anfühlt:**
Was mir auffällt: Gemini filtert Rauschen. Mit dem gleichen Prompt war seine Antwort 4x kürzer als bei Claude und ChatGPT, aber trotzdem gut. Es wirkt, als ob Gemini selbst auswählt, was wirklich zählt. Emotional intelligent.

**Wann einsetzen:**
- Sehr große Dokumente analysieren
- Cross-Model-Feedback-Schleifen (Gemini Claudes Output kritisieren lassen)
- Wenn du kürzere, gefilterte Antworten willst

---

## Multi-Model-Tools

### <img src="/icons/tools/t3chat.png" alt="" width="24" height="24" /> T3 Chat

**Was ist das?**
Ein "Multi-Model-Interface": Eine Chat-App, die dir gleichzeitig Zugang zu Claude, ChatGPT, Gemini und anderen Modellen gibt. Gemacht von Entwickler Theo Browne. Statt drei separaten Abonnements und drei separaten Tabs hast du alles in einem Fenster.

**Warum ich es nutze:**
Geschwindigkeit: kein Wechseln zwischen Tabs und Logins. Und Preis/Leistung: günstiger als separate Abonnements (8$/Monat für Zugang zu Modellen, die einzeln über 60$ kosten würden). Es macht es einfach, verschiedene Modelle auszuprobieren und zu vergleichen.

**Wann einsetzen:**
- Du willst Outputs verschiedener Modelle vergleichen
- Schnelles Experimentieren, welches Modell am besten für deine Aufgabe funktioniert

### <img src="/icons/tools/claude.svg" alt="" width="24" height="24" /> Claude Code + Finn

**Was ist das?**
Claude Code ist Anthropics "agentisches Coding-Tool": AI, die nicht nur antwortet, sondern tatsächlich Aufgaben ausführt. Es läuft in deinem Terminal oder deiner Entwicklungsumgebung, liest dein gesamtes Projekt und kann selbstständig Dateien bearbeiten, Code schreiben und Workflows ausführen.

"Agentisch" bedeutet: Die AI ergreift Initiative. Du gibst eine Anweisung ("analysiere diese fünf Transkripte und erstelle eine Synthese"), und Claude Code führt sie aus: liest die Dateien, erstellt Analysen, schreibt Output, fragt nach Feedback, passt an. Das ist grundlegend anders als ein Chat, in dem du immer selbst den nächsten Schritt herausfinden musst.

**Wie ich es nutze:**
Durch das Laden meiner persönlichen Kontextdateien bekommt Claude Code eine Persönlichkeit: Finn. Abgestimmt auf meine Vorlieben, mit Fähigkeiten, die ich entwickelt habe: Schreibstil-Check, Prompt-Generierung durch Interviews, Best Practices aus anderthalb Jahren Arbeit.

Ein konkretes Beispiel: Beim Analysieren mehrerer paralleler Tischgespräche kann Claude Code selbstständig jedes Transkript einzeln analysieren, die Analysen nebeneinanderlegen, Muster identifizieren und eine Synthese erstellen. Alles in einer Anweisung.

**Wann einsetzen:**
- Feldanleitung-Entwicklung: Inhalte schreiben und iterieren
- Prompt-Entwicklung: Prompts bauen und testen
- Multi-Datei-Analyse: mehrere Transkripte gleichzeitig verarbeiten
- Wenn du an etwas zusammenarbeiten willst, nicht nur Fragen stellen

---

## Integrierte Plattformen

### <img src="/icons/tools/dembrane.png" alt="" width="24" height="24" /> Dembrane

**Was ist das?**
Eine Plattform aus Eindhoven, die AI für Gruppengespräche einsetzt. Du kannst live transkribieren, direkt analysieren und der Gruppe Echtzeit-Feedback geben. Laut den Machern: "Helping communities grow smarter as they grow larger."

Der Kern: ECHO, ihr Tool, das Gespräche erfasst, analysiert und Erkenntnisse generiert, in den genauen Worten der Teilnehmenden, damit sie sich im Output wiedererkennen.

**Wie ich es nutze:**
"Diktat, aber für Gruppen." Semi-live: Breakout, Gespräch, über Beamer zurückspiegeln, Gruppe reagiert, zurück an AI. Ein neues Zusammenarbeitstool, das es vorher nicht gab.

AI im Gespräch einsetzen mit einem menschlichen Touch. Du stellst sie vor wie eine Person.

**Wann einsetzen:**
- Echtzeit-Feedback während einer Session
- Multi-Session-Prozesse, bei denen du Muster über Zeit verfolgen willst
- Eigenverantwortung in der Sprache der Teilnehmenden ist entscheidend
- Gruppen ohne erfahrenen Facilitator, die trotzdem Struktur wollen

**Was es besonders macht:**
"10 Sekunden. Eine Frage. Das festgefahrene Gespräch kam in Bewegung." Das Timing macht den Unterschied: Feedback im Moment wirkt anders als ein Bericht im Nachhinein.

---

### <img src="/icons/tools/notion.svg" alt="" width="24" height="24" /> Notion AI

**Was ist das?**
Notion ist ein "All-in-one-Workspace": eine App, die Notizen, Dokumente, Datenbanken und Projektmanagement kombiniert. Notion AI fügt künstliche Intelligenz hinzu: zusammenfassen, schreiben, Fragen an deine Dokumente stellen.

**Wie ich es nutze:**
Notion ist meine Arbeitsumgebung: Viel von meinem Kontext lebt dort bereits. Jetzt mit leistungsfähigen AI-Modellen (Claude Opus 4.5, Gemini 3 Pro), die mit all diesem Kontext arbeiten können.

**Was es tut:**
- Integriertes Meeting-Tool mit Live-Transkription (digital und vor Ort)
- AI auf Live-Transkript anwenden
- Alles an einem Ort: Aufnahmen, Transkripte, Notizen, Dokumente

**Warum es interessant ist:**
Notion AI ist etwas, das man im Auge behalten sollte. Es wird immer besser, gerade weil so viel Kontext dort bereits lebt.

### <img src="/icons/tools/notebooklm.svg" alt="" width="24" height="24" /> NotebookLM

**Was ist das?**
Googles "virtueller Forschungsassistent": Du lädst Quellen hoch (PDFs, Docs, Websites), und NotebookLM hilft dir, sie zu verstehen. Das Besondere: Die AI antwortet nur auf Basis deiner Quellen, nicht auf Basis des gesamten Internets.

Das bekannteste Feature ist "Audio Overview": NotebookLM erstellt einen Podcast aus deinen Dokumenten. Zwei AI-Hosts diskutieren die wichtigsten Themen in einem zugänglichen Gespräch. Inzwischen auch: Videopräsentationen, Infografiken und Slide-Decks.

**Warum ich es nutze:**
Du kannst Informationen und Wissen auf Weisen teilen, die vorher nicht möglich waren. "Der Podcast machte die Erkenntnisse teilbar für andere, die nicht dabei waren."

**Wann einsetzen:**
- Einen 3-Stunden-Workshop auf zugänglichere Weise teilen
- Erkenntnisse hörbar machen (unterwegs, für Menschen, die nicht lesen)
- Kernthemen auf das Wesentliche destillieren

---

## Eingebaute Optionen

### <img src="/icons/tools/google-meet.svg" alt="" width="24" height="24" /> Google Meet / <img src="/icons/tools/microsoft-teams.svg" alt="" width="24" height="24" /> Microsoft Teams

Basis-Transkription innerhalb deines bestehenden Ökosystems. Wenn du bereits in Google oder Microsoft arbeitest und nur eine einfache Transkription brauchst, musst du keine zusätzlichen Tools installieren.

---

## Wie wählst du aus?

| Frage | Tool |
|----------|------|
| Willst du diktieren? | MacWhisper |
| Datenschutz ist wichtig? | MacWhisper (lokal) |
| Durchdacht und prägnant? | Claude |
| Ausführlich und detailliert? | ChatGPT |
| Großer Kontext, gefiltert? | Gemini |
| Modelle vergleichen? | T3 Chat |
| An einem Projekt zusammenarbeiten? | Claude Code |
| Echtzeit-Feedback in der Session? | Dembrane |
| Alles in Notion? | Notion AI |
| Quellen umwandeln? | NotebookLM |

---

## Datenschutz-Überlegungen

Triff eine bewusste Wahl pro Gespräch:

| Art des Gesprächs | Empfehlung |
|----------------------|----------------|
| Sensibel | Lokales Tool (MacWhisper) |
| Extern/öffentlich | Cloud ist in Ordnung |
| Im Zweifel? | Lokal |

*Für einen tieferen Einblick in Datenschutzentscheidungen pro Tool, lies [Sicherer Umgang mit AI](sicherer-umgang.md).*

*"Das Tool zählt weniger als das, was du damit machst. Beginne mit dem, was für deine Situation funktioniert."*
