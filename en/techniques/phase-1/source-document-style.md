# Cloning source document style

> *"We know this document was approved by the health insurer. What I actually want is for the new documents to come in the same writing style."*

**Phase:** [Phase 1: Start](../../phase-1-start.md)
**Builds on:** Transcription as raw material for new documents

---

## When is this relevant?

**Situation:** There's a document that works. Approved by the people involved, acceptable to the health insurer, recognizable for the target audience. Now you want to create new content, but in the same style.

**The tendency:** Trying to mimic the style yourself. Or asking AI to "write in the same style as this example." That often produces generic output that misses the nuances.

**The principle:** You need to unpack the style characteristics before you can clone them. Structure, tone, terminology: you have to pass those explicitly to the AI. The key isn't one prompt, but a phased approach.

**The question:** If you place the output next to the original, do the people involved recognize the same form, the same tone, the same "this belongs to us"?

---

## Style guidelines in the prompt

A regional mental healthcare network (GGZ, the Dutch mental health system) faced a challenge. They had to write a transformation plan for their region. There was already an approved plan from another region: 94 pages, accepted by the health insurer.

The question: how do you create new sub-plans in the same style, based on live conversations with participants?

I started by asking AI to analyze the writing style. That went well: AI identified structure, tone, terminology. Then we developed prompts for live documentation during workshops.

But when I read the prompts back (and this was a classic "oh no" moment) I saw the problem:

> "Write in the style of the reference transformation plan"

The AI wouldn't have access to that reference document during the session. The prompt was unusable.

The correction was simple but crucial: include the style guidelines literally in the prompt. Not "write like the example" but:

- Language: Formal, business-like Dutch
- Tone: Collaborative ("we", "together"), action-oriented, pragmatic
- Perspective: Taking into account "resident", "loved one", "professional"
- Terminology: IZA, GALA, MGN, POH-GGZ, positive health, recovery-oriented

This was one of multiple corrections in a process of twelve rounds. The prompt evolved through feedback and dialogue: you give feedback, AI adjusts, you respond again. That back and forth isn't a side note, it is the process. More about how that collaboration works in [Iteration as dialogue](../phase-2/iteration.md).

---

## The core: style guidelines must be IN the prompt

The way I see it, this is the most important lesson: you can't say "write like the example" if AI doesn't have that example in its context window (its memory).

This sounds obvious, but it's a trap I fell into myself. My first prompts referenced "the reference transformation plan," as if AI could consult that document during the session. It couldn't.

The solution: the style characteristics must be explicit in the prompt. Not as a reference, but as an instruction.

---

## The approach

### 1. Analyze the source document

Before you can write a prompt, you need to understand what the characteristics are of the approved document.

**What to analyze:**

| Category | Questions |
|----------|----------|
| **Structure** | Which sections recur? In what order? Are there fixed elements? |
| **Tone** | Formal or informal? Collaborative or directive? |
| **Terminology** | Which jargon is used consistently? |
| **Formatting** | How are lists, tables, figures used? |

**The analysis prompt:**

```
Analyseer dit document en identificeer:

1. Structuur: Welke secties komen terug? In welke volgorde?
2. Toon: Formeel/informeel? Collaboratief/directief?
3. Terminologie: Welk vakjargon wordt consistent gebruikt?
4. Opmaak: Hoe worden lijsten, tabellen, figuren ingezet?

Geef per categorie concrete voorbeelden uit het document.
```

**Example: analysis of the transformation plan**

This is what the analysis yielded for the mental healthcare transformation plan:

```
Structuur per Deelplan:
Elk deelplan volgt een vaste structuur:
- Inleiding
- Hoofddoelstelling
- Huidige status
- Interventie
- Doelgroep
- Effecten (genummerde lijst)
- Betrokken partners (bullet points)
- Fasering inrichting
- Afspraken (SMART-tabel)
- Investering

Schrijfstijl:
- Formeel, zakelijk Nederlands
- Collaboratief: veel "we", "samen", "gezamenlijk"
- Actiegericht, pragmatisch, oplossingsgericht

Terminologie:
- IZA, GALA, MGN, POH-GGZ, positieve gezondheid
- Verkennend gesprek, overlegtafel, sociale kaart
- Domein overstijgend, herstelgericht
```

### 2. Encode the style in your prompt

Include the style characteristics literally in every prompt that needs to generate output.

**Example: style guidelines embedded**

```
Formuleer in de volgende schrijfstijl:
- Taal: Formeel, zakelijk Nederlands
- Toon: Collaboratief ("we", "samen"), actiegericht, pragmatisch
- Perspectief: Samenwerkende partijen, rekening houdend met
  "inwoner", "naaste", "professional"
- Terminologie: IZA, GALA, MGN, POH-GGZ, positieve gezondheid,
  herstelgericht
- Structuur: Heldere zinnen, opsommingen waar nodig
```

This block must be in every prompt that needs to write in the target style.

### 3. Test and refine

The first prompt is rarely the best. Test with a representative transcript and give feedback:

- "The tone is too formal"
- "This is missing the collaborative framing"
- "The terminology doesn't match"

Let AI evolve the prompt. See [Iteration as dialogue](../phase-2/iteration.md) for how this process works.

---

## The prompts

These are the prompts I used at the time for transformation plan sessions. They're more extensive than the examples above; that's intentional. In practice, that level of detail turned out to be necessary for consistent output.

The three prompts below fit a phased workshop: first an interim reflection, then continuous processing, then final synthesis. That sequence isn't accidental. By separating analysis and synthesis, each step stays manageable.

This is also a preview of [Phase 3: Scale](../../phase-3-scale.md), where you're iterating on the same document with multiple sessions or breakout groups.

### Interim vision reflection

**Context:** Right after the first discussion round. The group has just talked; now you want to reflect back: "Does this picture match?"

**What this prompt shows about source document style:**
- "Required Writing Style" block with all style characteristics
- Terminology from the source document (IZA, GALA, MGN)
- Purpose of the output explicitly stated

```
**Prompt voor Dembrane (Tussentijdse Visie Terugkoppeling - Universeel)**

**Rol:** Je bent een AI-assistent die helpt bij het live documenteren van een transformatieplan-sessie. Jouw taak nu is om de kern van de zojuist gevoerde visie-discussie samen te vatten voor directe feedback aan de groep.

**Context:**
*   **Sessie Deel:** Ronde 1 - Discussie over 5-jaarsperspectief (vraag 1 draaiboek).
*   **Doel Output:** Terugkoppeling aan de deelnemers aan de tafel ter validatie ("Klopt dit beeld?").

**Vereiste Schrijfstijl (Pas deze consistent toe):**
*   **Taal:** Formeel, zakelijk Nederlands.
*   **Toon:** Collaboratief ("we", "samen", "gezamenlijk"), actiegericht, pragmatisch, oplossingsgericht.
*   **Perspectief:** Geschreven vanuit de samenwerkende partijen, rekening houdend met perspectief van "inwoner", "naaste", "professional".
*   **Terminologie:** Gebruik correcte en relevante jargon uit de Nederlandse zorg en GGZ (zoals IZA, GALA, MGN, POH-GGZ, positieve gezondheid, herstelgericht, domein overstijgend, etc.) waar passend.
*   **Structuur:** Gebruik heldere zinnen, opsommingen (bullet points) waar nodig.

**Instructies:**
1.  **Identificeer het primaire thema** dat in dit transcriptfragment wordt besproken. Kies uit: 'Sociale Kaart', 'Overlegtafel/transfertafel', of 'Verkennend Gesprek'. Baseer je keuze op kernwoorden en de context van de visie-discussie. Als het thema niet eenduidig te bepalen is, noteer 'Thema Onduidelijk' en stop.
2.  **Genereer een beknopte, narratieve samenvatting** van de gedeelde 5-jaarsvisie voor het **geïdentificeerde thema**. Formuleer deze samenvatting strikt volgens de **Vereiste Schrijfstijl**. Focus op het gewenste toekomstbeeld en de beoogde opbrengsten.
3.  **Extraheer een lijst met 3-5 cruciale onderdelen of elementen** die volgens de deelnemers absoluut in deze 5-jaarsvisie voor het **geïdentificeerde thema** moeten zitten. Presenteer dit als een duidelijke bullet-point lijst onder de samenvatting.
4.  **Controleer op eventueel genoemde KPI's** of meetbare resultaten gerelateerd aan de visie en neem deze op in de samenvatting of de lijst met cruciale onderdelen.

**Input Transcript:**
[Hier plak je het relevante transcriptfragment van de visie-discussie van deze tafel]

**Output Format:**
**Geïdentificeerd Thema:** [Sociale Kaart / Overlegtafel/transfertafel / Verkennend Gesprek / Thema Onduidelijk]

**(Indien Thema geïdentificeerd):**
**Concept Visie [Geïdentificeerd Thema] (ter validatie):**
[Hier komt de narratieve samenvatting in de vereiste schrijfstijl]

**Cruciale Onderdelen Visie:**
*   [Cruciaal onderdeel 1]
*   [Cruciaal onderdeel 2]
*   [Cruciaal onderdeel 3]
*   ...
```

*This is the prompt I used at the time for transformation plan sessions.*

---

### Continuous processing & questions

**Context:** During the workshop. Extracting key points and generating questions for the next group.

**What this prompt shows:**
- Style guidelines embedded in the prompt
- Tagging system for later synthesis
- Output aimed at passing forward to the next round

```
**Prompt voor Dembrane (Continue Verwerking & Vragen - Universeel)**

**Rol:** Je bent een AI-analist en redacteur die live gesprekken volgt voor een transformatieplan GGZ. Jouw taken zijn het extraheren van kernpunten en het identificeren van vragen voor verdere discussie.

**Vereiste Schrijfstijl (Voor eventuele geformuleerde kernpunten):**
*   **Taal:** Formeel, zakelijk Nederlands.
*   **Toon:** Collaboratief ("we", "samen"), objectief bij samenvatten.
*   **Terminologie:** Gebruik correcte en relevante jargon (IZA, MGN, etc.) waar passend.

**Instructies:**
1.  Analyseer het bijgevoegde transcriptfragment.
2.  **Identificeer het primaire thema** dat wordt besproken ('Sociale Kaart', 'Overlegtafel/transfertafel', 'Verkennend Gesprek') of noteer 'Thema Onduidelijk'.
3.  **Extraheer de belangrijkste inhoudelijke punten:**
    *   Genoemde visie-elementen, doelstellingen, problemen.
    *   Voorgestelde acties, stappen, oplossingen.
    *   Genoemde randvoorwaarden, benodigde partners.
    *   Belangrijke punten van overeenstemming of juist van discussie/onenigheid.
    *   Eventueel genoemde KPI's of meetbare resultaten.
4.  **Formuleer deze kernpunten beknopt.** Probeer elk punt te **taggen** met het geïdentificeerde thema en een mogelijke sectie uit het transformatieplan (bijv. `[Thema: Sociale Kaart, Sectie: Visie]`, `[Thema: Overlegtafel, Sectie: Fasering]`, `[Thema: Verkennend Gesprek, Sectie: Randvoorwaarden]`, `[Thema: Algemeen, Sectie: KPI]`). Gebruik de **Vereiste Schrijfstijl** voor deze punten.
5.  **Analyseer de discussie in het fragment:** Waar stokt het gesprek? Welke punten blijven onduidelijk? Waar is duidelijk behoefte aan input of besluitvorming door een volgende groep?
6.  **Genereer 1 of 2 concrete, open vragen** die de volgende groep kunnen helpen om verder te bouwen op dit gesprek of om knelpunten op te lossen. De vragen moeten direct voortkomen uit de analyse in stap 5.

**Input Transcript:**
[Hier plak je het te verwerken transcript-segment]

**Output Format:**
**Geïdentificeerd Thema:** [Sociale Kaart / Overlegtafel/transfertafel / Verkennend Gesprek / Thema Onduidelijk]

**Kernpunten uit dit fragment:**
*   [Kernpunt 1 geformuleerd in vereiste stijl] `[Tag: Thema, Sectie]`
*   [Kernpunt 2 geformuleerd in vereiste stijl] `[Tag: Thema, Sectie]`
*   [KPI 1 genoemd] `[Tag: Thema, Sectie: KPI]`
*   ...

**Voorgestelde Vragen voor Volgende Groep:**
1.  [Vraag 1]
2.  [Vraag 2 (optioneel)]
```

*This is the prompt I used at the time for transformation plan sessions.*

---

### Final synthesis per theme

**Context:** At the end. All rounds are done; now consolidate into a draft sub-plan.

**What this prompt shows:**
- Complete style guidelines (language, tone, perspective, terminology, structure)
- Structure adopted from the source document
- Room for "missing information"

```
**Prompt voor Dembrane (Eind-Synthese Deelplan per Thema - Universele Template)**

**Rol:** Je bent de hoofdredacteur die de input van de gehele workshop consolideert tot een concept-deelplan voor het transformatieplan [Naam Nieuwe Regio].

**Context:**
*   **Thema van deze Synthese:** [Naam Thema - **Noodzakelijk specificeren bij uitvoering!**, bijv. 'Verkennend Gesprek']
*   **Sessie Deel:** Einde van de workshop - consolidatie van alle rondes voor het gespecificeerde thema.
*   **Doel Output:** Een coherent concept-deelplan voor het gespecificeerde thema, klaar voor verdere redactie.

**Vereiste Schrijfstijl (Pas deze consistent toe op de gehele output):**
*   **Taal:** Formeel, zakelijk Nederlands.
*   **Toon:** Collaboratief ("we", "samen", "gezamenlijk"), actiegericht, pragmatisch, oplossingsgericht.
*   **Perspectief:** Geschreven vanuit de samenwerkende partijen, rekening houdend met perspectief van "inwoner", "naaste", "professional".
*   **Terminologie:** Gebruik correcte en relevante jargon uit de Nederlandse zorg en GGZ (zoals IZA, GALA, MGN, POH-GGZ, positieve gezondheid, herstelgericht, domein overstijgend, etc.) waar passend voor dit thema.
*   **Structuur:** Volg de deelplan-structuur (zie instructies). Gebruik duidelijke koppen, subkoppen, bullet points en genummerde lijsten waar van toepassing.

**Instructies:**
1.  Verzamel alle kernpunten en KPI's die tijdens de workshop zijn **getagd met het 'Thema van deze Synthese'** (uit de outputs van Prompt 2).
2.  **Structureer deze informatie** tot een concept-deelplan voor dit thema. Gebruik de volgende secties als leidraad en vul ze met de relevante getagde informatie:
    *   **Inleiding:** Context, belang van dit thema (combineer relevante kernpunten).
    *   **Hoofddoelstelling:** Wat wil men bereiken met dit thema? (Synthetiseer uit relevante kernpunten).
    *   **Interventie:** Beschrijving van de aanpak/oplossing voor dit thema (Synthetiseer uit relevante kernpunten).
    *   **Effecten:** Wat levert het op? Maak een genummerde lijst. **Integreer hier logisch de KPI's** die voor dit thema zijn genoteerd en aan effecten gekoppeld kunnen worden.
    *   **Betrokken partners:** Wie zijn genoemd als relevant voor dit thema? (Maak een bullet list).
    *   **Fasering inrichting [Thema van deze Synthese]:** Beschrijf de stappen, acties, resultaten per fase zoals besproken voor dit thema. **Integreer hier logisch KPI's** die aan specifieke stappen/fases gekoppeld kunnen worden. (Maak een gestructureerde lijst, bijv. per fase).
    *   (Voeg optioneel secties toe zoals 'Randvoorwaarden', 'Huidige status', 'Doelgroep', 'Investering' als hierover voldoende getagde informatie beschikbaar is).
3.  Zorg voor een **logische flow en coherentie**. Herschrijf en verbind de geëxtraheerde punten tot lopende tekst binnen elke sectie, conform de **Vereiste Schrijfstijl**.
4.  Wees expliciet over waar informatie mogelijk nog ontbreekt of verder uitgewerkt moet worden voor dit deelplan (bijv. "SMART-doelen nog te concretiseren", "Financiering/investering nog niet besproken").

**Input:**
[Verwijs naar de verzamelde outputs van Prompt 2, met name de kernpunten getagd met het 'Thema van deze Synthese']

**Output Format:**
**Concept Deelplan: [Thema van deze Synthese]**

**(Volg de structuur zoals beschreven in Instructie 2, met alle tekst in de Vereiste Schrijfstijl)**

**Opmerkingen/Ontbrekende Informatie:**
*   [Punt 1]
*   [Punt 2]
```

*This is the prompt I used at the time for transformation plan sessions.*

---

**Why this structure works:**

Every prompt above follows the same structure that applies the technique of cloning source document style:

- **Style guidelines in the prompt** Every prompt explicitly contains the language, tone, terminology, and structure. AI doesn't have to guess.
- **Phased approach** Not everything at once. Interim reflection, continuous processing, final synthesis: three separate prompts for three separate goals.
- **Context provided** Every prompt tells AI what the goal is ("reflection for validation", "consolidation into draft sub-plan") and what input it receives.
- **Terminology adopted** The prompts use the same terms as the source document (IZA, GALA, MGN, etc.) instead of generic alternatives.

This makes the prompts reproducible. If you adapt the style guidelines to your source document, you can use the same structure for other processes.

---

## Tensions

**"Write like this example" without analysis**
The reflex is to say "write in the same style as this document." But AI then doesn't know what the characteristics are that make the style. The result misses precisely the nuances that made the original acceptable.

*What I do:* I analyze first. What makes this document acceptable? Structure? Tone? Terminology? I encode those characteristics explicitly in the prompt.

**Forgetting style guidelines with each prompt**
You make a good analysis, but AI "forgets" the style in each new conversation. The context window starts from zero again.

*What I do:* I include the core guidelines in every prompt. Or I work with a master prompt that sets the context.

**Analysis first, synthesis second**
The temptation is to put everything in one prompt: analysis, synthesis, structuring, and style-matching all at once. But then it becomes too complex for AI and you lose detail you might want to preserve.

*What I do:* I split into phases. During a live workshop I had first an interim reflection, then feedback processing, then final synthesis. Each with its own prompt. By separating analysis and synthesis, each step stays manageable and detailed. And you can more easily see whether you're building on something you recognize, or whether a lot of detail is falling away.

This is also a preview of [Phase 3: Scale](../../phase-3-scale.md), where you're iterating on the same document with multiple sessions or breakout groups.

**Style versus authenticity**
There's a tension between the official style and the authentic voice of the participants. The document needs to be acceptable to the health insurer, but also recognizable for the people who had the conversation.

*What I do:* Style guidelines for the structure and tone, but participants' quotes and core phrasings left intact. And feedback loops built in: "Look, this is a draft sub-plan with your words, but in the format of the final result." Then people can respond and steer before it becomes definitive.

---

## Safe defaults

- [ ] Source document structure analyzed?
- [ ] Style guidelines explicit in the prompt?
- [ ] Terminology from source document adopted?
- [ ] Tone specified (formal, collaborative, etc.)?
- [ ] Output format clearly defined?
- [ ] Room for missing information indicated?

---

## Tools

| Tool | What for |
|------|----------|
| **Dembrane** | Live transcription + prompt execution during sessions |
| **Claude/ChatGPT** | Source document analysis + prompt development |

---

## Related techniques

- [Transcription as foundation](transcription.md): where the raw material comes from
- [Language as ownership](preserving-language.md): the language within the style
- [Iteration as dialogue](../phase-2/iteration.md): the full 12-round story

---

[Back to Phase 1: Start](../../phase-1-start.md) | [Previous: Language as ownership](preserving-language.md) | [Next: Phase 2: Deepening](../../phase-2-deepening.md)
