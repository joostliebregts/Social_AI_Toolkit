# Tools

> Welke tools gebruik je wanneer? Een overzicht.

> 🚧 **Work in progress** — Deze pagina wordt nog bijgeschaafd. Inhoud kan veranderen.

---

De tool maakt minder uit dan wat je ermee doet. Maar het helpt om te weten wat er is — en wat elk anders maakt.

---

## In één oogopslag

| Tool | Wat het doet | Wanneer |
|------|--------------|---------|
| **MacWhisper** | Dictatie + lokale transcriptie | Je wilt dicteren, privacy belangrijk |
| **Claude** | Bedachtzaam, beknopt | Diepere analyse, ethische afwegingen |
| **ChatGPT** | Uitgebreid, breed | Snelle sparring, veel integraties |
| **Gemini** | 1M context, filtert ruis | Grote documenten, cross-model check |
| **T3 Chat** | Multi-model interface | Modellen vergelijken, prijs/waarde |
| **Claude Code + Finn** | Agentic samenwerking | Toolkit/prompt development |
| **Dembrane** | Live transcriptie + echo | Real-time feedback in sessies |
| **Notion AI** | AI in je workspace | Alles op één plek, context |
| **NotebookLM** | Bronnen → andere vormen | Podcast, video, slides maken |

---

## Dictatie + transcriptie (lokaal)

### MacWhisper

**Wat is het?**
Een Mac-app die spraak omzet in tekst — volledig op je eigen computer, zonder dat er iets naar de cloud gaat. Ontwikkeld door Jordi Bruin, gebaseerd op OpenAI's Whisper-technologie.

**Waarom ik het gebruik:**
Dictatie is de nummer één reden. Het verandert de hele workflow: dicteren → AI → dicteren → AI. De drempel om gedachten vast te leggen wordt bijna nul. Feedback geven aan AI, observaties inspreken na een sessie, hardop denken — het gaat allemaal sneller dan typen.

**Bonus: privacy-first**
Alles gebeurt lokaal op je Mac. Geen audio naar servers, geen tekst naar de cloud. Handig voor gevoelige gesprekken.

**Wat het anders maakt:**
Met nieuwere modellen (zoals Parakeet 3) kan een uur audio in 1-2 minuten getranscribeerd zijn. De oude aanname dat lokaal langzamer is, geldt steeds minder.

---

## AI-modellen

**Waarom drie modellen?**
Ik werk vooral met drie: Claude, ChatGPT en Gemini. Er zijn er inmiddels tientallen, maar deze drie gebruik ik het meest. Wat ik merk: ze lijken op elkaar totdat je ze vaak gebruikt. Dan voel je de verschillen.

Het is alsof je drie adviseurs hebt. Dezelfde vraag, maar andere stijl, andere diepte, andere aannames.

### Claude (Anthropic)

**Wat is het?**
Een AI-assistent van Anthropic, opgericht door voormalige OpenAI-onderzoekers. Anthropic onderscheidt zich door sterke focus op AI-veiligheid — ze hebben een team dat kijkt naar de lange-termijn impact van AI op de mensheid.

**Hoe het aanvoelt:**
Wat ik merk: bedachtzaam. Soms krijg je twee zinnen als dat genoeg is. Minder "hier is alles wat ik weet", meer to-the-point.

**Wanneer gebruiken:**
- Diepere analyse van transcripten
- Iteratie op syntheses
- Complexe prompt-ontwikkeling
- Als je genuanceerde, beknopte antwoorden wilt

### ChatGPT (OpenAI)

**Wat is het?**
De AI-assistent van OpenAI, het bedrijf dat de generatieve AI-revolutie startte met GPT-3. ChatGPT was de eerste die massaal werd gebruikt en is nog steeds de bekendste.

**Hoe het aanvoelt:**
Uitgebreid. Volgens mij zit de behulpzaamheid bij ChatGPT in de rijkheid en hoeveelheid — antwoorden zijn vaak lang en gedetailleerd. Wordt steeds commerciëler.

**Wanneer gebruiken:**
- Sparring en snelle analyse
- Breed beschikbaar, veel integraties
- Als je uitgebreide, gedetailleerde antwoorden wilt

### Gemini (Google)

**Wat is het?**
Google's AI-assistent, gebaseerd op hun eigen taalmodellen. Onderscheidt zich door een enorme context window (1 miljoen tokens) — je kunt er hele boeken in stoppen.

**Hoe het aanvoelt:**
Wat mij opvalt: Gemini filtert ruis. Bij dezelfde prompt was het antwoord 4x korter dan Claude en ChatGPT — maar nog steeds goed. Het lijkt alsof Gemini zelf kiest wat echt belangrijk is. Emotioneel intelligent.

**Wanneer gebruiken:**
- Hele grote documenten analyseren
- Cross-model feedback loops (laat Gemini Claude's output bekritiseren)
- Als je kortere, gefilterde antwoorden wilt

---

## Multi-model tools

### T3 Chat

**Wat is het?**
Een "multi-model interface" — één chat-app waarmee je toegang hebt tot Claude, ChatGPT, Gemini en andere modellen tegelijk. Gemaakt door ontwikkelaar Theo Browne. In plaats van drie losse abonnementen en drie losse tabbladen, heb je alles in één venster.

**Waarom ik het gebruik:**
Snelheid — geen tabbladen en logins wisselen. En prijs/waarde — goedkoper dan losse abonnementen ($8/maand voor toegang tot modellen die apart $60+ zouden kosten). Het maakt het makkelijk om verschillende modellen te proberen en te vergelijken.

**Wanneer gebruiken:**
- Je wilt outputs van verschillende modellen vergelijken
- Snel experimenteren met welk model het beste werkt voor je taak

### Claude Code + Finn

**Wat is het?**
Claude Code is Anthropic's "agentic coding tool" — AI die niet alleen antwoordt, maar ook daadwerkelijk taken uitvoert. Het draait in je terminal of software-ontwikkel-programma, leest je hele project, en kan zelfstandig bestanden aanpassen, code schrijven, en workflows uitvoeren.

"Agentic" betekent: de AI neemt initiatief. Je geeft een opdracht ("analyseer deze vijf transcripten en maak een synthese"), en Claude Code voert die uit — leest de bestanden, maakt analyses, schrijft output, vraagt feedback, past aan. Dat is fundamenteel anders dan een chat waar je steeds zelf de volgende stap moet bedenken.

**Hoe ik het gebruik:**
Door mijn persoonlijke contextbestanden in te laden krijgt Claude Code een persoonlijkheid — Finn. Afgestemd op mijn wensen, met skills die ik heb ontwikkeld: schrijfstijl check, prompt generatie via interview, best practices uit anderhalf jaar.

Een concreet voorbeeld: bij het analyseren van meerdere parallelle tafelgesprekken kan Claude Code zelfstandig elk transcript apart analyseren, de analyses naast elkaar leggen, patronen identificeren, en een synthese maken — allemaal in één opdracht.

**Wanneer gebruiken:**
- Toolkit development: schrijven en itereren op content
- Prompt development: bouwen en testen van prompts
- Multi-bestand analyse: meerdere transcripten tegelijk verwerken
- Als je wilt samenwerken aan iets, niet alleen vragen stellen

---

## Geïntegreerde platforms

### Dembrane

**Wat is het?**
Een platform uit Eindhoven dat AI inzet voor groepsgesprekken. Je kunt live transcriberen, direct analyseren, en de groep real-time feedback geven. Volgens de makers: "Communities helpen slimmer te groeien naarmate ze groter worden."

De kern: ECHO, hun tool die gesprekken vastlegt, analyseert, en inzichten genereert — met de exacte woorden van deelnemers, zodat zij zich herkennen in de output.

**Hoe ik het gebruik:**
"Dictatie maar dan voor groepen." Semi-live: breakout → gesprek → terugkoppelen via beamer → groep reageert → terug naar AI. Een nieuwe samenwerkingstool die er voorheen niet was.

AI in het gesprek gebruiken met een menselijk randje. Je introduceert het als mens.

**Wanneer gebruiken:**
- Real-time feedback tijdens een sessie
- Multi-session trajecten waar je patronen over tijd wilt volgen
- Eigenaarschap in deelnemerwoorden is cruciaal
- Groepen zonder ervaren facilitator die toch structuur willen

**Wat het anders maakt:**
"10 seconden. Één vraag. Het gesprek dat vastzat, kwam in beweging." De timing maakt het verschil — feedback in het moment raakt anders dan een rapport achteraf.

### Notion AI

**Wat is het?**
Notion is een "all-in-one workspace" — een app waarin je notities, documenten, databases, en projectmanagement combineert. Notion AI voegt daar kunstmatige intelligentie aan toe: samenvatten, schrijven, vragen stellen aan je documenten.

**Hoe ik het gebruik:**
Notion is mijn werkomgeving — daar staat veel van mijn context al. Tegenwoordig met krachtige AI-modellen (Claude Opus 4.5, Gemini 3 Pro) die met die hele context kunnen werken.

**Wat het doet:**
- Geïntegreerde meetings tool met live transcriptie (digitaal én fysiek)
- AI toepassen op live transcript
- Alles op één plek: opnames, transcripten, notities, documenten

**Waarom het interessant is:**
Notion AI is iets om in de gaten te houden. Het wordt steeds krachtiger — precies omdat daar al zoveel context staat.

### NotebookLM

**Wat is het?**
Google's "virtuele onderzoeksassistent" — je uploadt bronnen (PDF's, docs, websites), en NotebookLM helpt je ze begrijpen. Het bijzondere: de AI antwoordt alleen op basis van jouw bronnen, niet op basis van het hele internet.

De bekendste functie is "Audio Overview": NotebookLM maakt een podcast van je documenten. Twee AI-hosts bespreken de kernthema's in een toegankelijk gesprek. Inmiddels ook: videopresentaties, infographics, en slide decks.

**Waarom ik het gebruik:**
Je kunt informatie en kennis delen op manieren die voorheen niet mogelijk waren. "De podcast maakte de inzichten deelbaar met anderen die er niet bij waren."

**Wanneer gebruiken:**
- Workshop van 3 uur toegankelijker delen
- Inzichten luisterbaar maken (onderweg, voor mensen die niet lezen)
- Kernthema's destilleren naar essentie

---

## Ingebouwde opties

### Google Meet / Microsoft Teams

Basis transcriptie in je bestaande ecosysteem. Als je al in Google of Microsoft werkt en alleen basis-transcriptie nodig hebt, hoef je geen extra tools te installeren.

---

## Hoe kies je?

| Vraag | Tool |
|-------|------|
| Wil je dicteren? | MacWhisper |
| Privacy belangrijk? | MacWhisper (lokaal) |
| Bedachtzaam en beknopt? | Claude |
| Uitgebreid en gedetailleerd? | ChatGPT |
| Grote context, gefilterd? | Gemini |
| Modellen vergelijken? | T3 Chat |
| Samenwerken aan project? | Claude Code |
| Real-time feedback in sessie? | Dembrane |
| Alles in Notion? | Notion AI |
| Bronnen omzetten? | NotebookLM |

---

## Privacy-afweging

Maak een bewuste keuze per gesprek:

| Type gesprek | Aanbeveling |
|--------------|-------------|
| Gevoelig | Lokale tool (MacWhisper) |
| Extern/openbaar | Cloud kan |
| Twijfel? | Lokaal |

*Voor een diepere duik in privacy-keuzes per tool, lees [Veilig werken met AI](veilig-werken.md).*

---

> "De tool maakt minder uit dan wat je ermee doet. Begin met wat werkt voor jouw situatie."
