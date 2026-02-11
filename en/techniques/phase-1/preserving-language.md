![Language as ownership mechanism](../../images/taalalseigenaarschapmechanisme.png)

# Language as ownership

> *The difference between "communication issues" and "you're talking to a wall" isn't semantic — the first undermines ownership, the second creates it.*

**Phase:** [Phase 1: Start](../../phase-1-start.md)
**Builds on:** The bicycle helmet story: where Maarten's own words revealed the core

---

## When is this relevant?

**Situation:** You have a transcript. You want to turn it into a synthesis, summary, or reflection. The group needs to recognize themselves in the result.

**The tendency:** To "clean up" everything into professional language. Translate frustrations into "challenges." Rewrite messy sentences into clean bullet points. The result sounds better — but nobody recognizes themselves anymore.

**The principle:** When people hear or see their own exact words back in AI output, they recognize themselves. That recognition triggers ownership. Without recognition, no ownership. Without ownership, no commitment.

**The question:** If the people who had this conversation read this result, do they say "yes, that's what we said" or "that sounds like a consultant"?

---

## The story: "This is literally what we said"

On the [previous page](transcription.md) you learned how to capture conversations as text. But what do you do when that text needs to go back to someone: as a synthesis, summary, or reflection?

This is where the tension comes in: the tendency to "clean up" everything into professional language. And the risk that nobody recognizes themselves anymore.

A transformation plan for a mental healthcare network (GGZ, the Dutch mental health system). Thirty participants have given input on their vision for mental health in the region. Now that needs to be converted into a document the health insurer will accept.

The session is transcribed live with Dembrane. While the discussion is still ongoing, AI generates a draft sub-plan based on what's been said.

When it's shown, the reaction stands out.

> "Wait... this is — yes, this is literally what we said. And now it's in a draft. Wow, impressive."

The participants look at the screen and see their own words reflected back. Not summarized. Not interpreted. Their exact phrasings, structured in a format the health insurer recognizes.

Later in the session, facilitator Jeroen uses the echo button. There's a tense discussion about priorities. AI summarizes the conversation and poses a question.

> "Wow, wow. It really captures it well. This is literally — yes, this really is the question we need to ask."

The transition is visible: from shock ("AI understands us?!") to recognition ("this is literally what we said") to ownership ("this is the question we need to ask").

Nobody would have had the same reaction to a synthesis that had translated their words into policy language. The difference isn't in the structure. The difference is in the language.

---

![Mechanism: verbatim quoting](../../images/taal-behouden-mechanisme-letterlijk.png)

## The mechanism: recognition creates ownership

Why does this work? The mechanism is simple but fundamental:

```
1. Participant says something with specific phrasing
        ↓
2. AI preserves exact phrasing in output
        ↓
3. Participant reads/hears output
        ↓
4. Recognition: "Yes, that's what I said"
        ↓
5. Ownership: "There's something of mine in there"
        ↓
6. Commitment: "I stand behind this"
```

This isn't a side note. This IS the mechanism through which participation transforms from "having contributed thoughts" to "this is mine." Paraphrasing breaks the chain at step 4. The recognition falls away. And with it, everything that follows.

### The language hierarchy

Not all language is equal. The more specific, the stronger the recognition:

| Level                                  | Example                                                                           | Impact                                                |
| -------------------------------------- | --------------------------------------------------------------------------------- | ----------------------------------------------------- |
| **1. Their exact words with context**  | "The whole class doesn't wear a helmet. So I stopped too, otherwise I don't fit in." | Maximum recognition: this is exactly what was said |
| **2. Their core terminology**          | "the bicycle helmet effect"                                                       | Strong recognition: their word for the phenomenon     |
| **3. Generic terms from their domain** | "peer pressure among children"                                                    | Recognizable but more distant                         |
| **4. Abstract concepts**              | "social challenges"                                                               | Barely any recognition                                |
| **5. Consultant-speak**               | "stakeholder alignment around youth behavioral norms"                             | Nobody recognizes themselves anymore                  |

The goal is level 1-2. Always avoid 4-5. Level 3 only when that's the language they themselves use.

---

## The core question: the recognition criterion

```
IF they think "yes, that's what we said" → SUCCESS
IF they think "that sounds like a consultant" → FAILED
```

This isn't a soft criterion. This is the hard test for every output. A synthesis that's technically correct but where nobody recognizes themselves is worthless. A synthesis with their messy language but where everyone nods along is gold.

---

## The prompt

The criterion is clear. But how do you make sure AI produces output that meets it?

By making language preservation explicit in the prompt. Not as a side note, but as a core requirement.

This is a prompt we used for a leadership workshop in a small municipality. Notice how the constraints for language preservation are specific and concrete:

```
**Rol**: Je bent een strategisch redacteur met expertise in visievorming
die individuele toekomstbeelden omzet in één krachtige, gezamenlijk
gedragen visie.

**Vereiste Stijl/Aanpak**:
- Gebruik hun eigen woorden en terminologie uit de gesprekken
- Behoud de kracht van hun individuele visies
- Maak het specifiek voor deze gemeente, niet generiek
- Schrijf in de toekomstige tegenwoordige tijd (2040 als realiteit)

**Cruciale Randvoorwaarden**:
- Baseer output strikt op transcript(en) - geen verzinsels
- Benoem openstaande punten en onzekerheden expliciet
- Gebruik quotes uit gesprekken zonder speaker attributie
- Gebruik hun eigen kernterminologie - niet automatisch "samenredzaamheid"
- Vermijd abstracte bestuurstaal - houd het menselijk

**Instructies**:
1. Analyseer elke individuele "stip op de horizon" die genoemd is
2. Identificeer hun eigen kernterminologie - gebruik NIET "samenredzaamheid"
   tenzij zij dat zeggen
3. Identificeer gemeenschappelijke waardes en kernprincipes
4. Zoek de specifieke lokale elementen die terugkomen
5. ALS er tegenstrijdigheden zijn DAN benoem deze expliciet als "nog af te stemmen"
6. Sluit af met waarom dit belangrijk is in hun eigen woorden

**Output Format**:
### Hun Waarom (in eigen woorden)
> "Quote waarom dit belangrijk is"
> "Quote over kernwaarde"

*Uit de gesprekken komt naar voren dat...*

### Nog Af Te Stemmen
- [Punten waar verschillende visies nog samenkomen]

### Over Deze Visie
Deze visie is opgesteld door AI op basis van jullie gesprek. Het is een
hulpmiddel om jullie eigen toekomstbeelden te structureren - niet perfect,
maar een startpunt voor verder gesprek. Dit blijft jullie verhaal - de AI
helpt alleen bij het bundelen en verbinden van jullie ideeën.
```

**Why this structure works:**
- **Role** gives AI an identity that fits the task: "strategic editor with expertise in vision development" steers toward synthesis, not summary
- **Required Style/Approach** defines the tone: "their own words" and "specific to this municipality" prevents generic output
- **Critical Constraints** are the hard boundaries: "no fabrications", "don't automatically use 'self-reliance'" prevents AI from filling in the blanks
- **Instructions** are the steps: the sequence (first analyze, then identify, then synthesize) steers the thought process
- **Output Format** determines the form: "Their Why" with quotes enforces verbatim citation

---

## Variations

The basic approach above works for many situations. But the context varies: sometimes you're working with a community, sometimes with multiple conversations, sometimes live. Below are three variations I use in practice.

### Variation 1: Community analysis with "hooks"

On the transcription page you saw the [full prompt for the smartphone-free parent evening](transcription.md#1-vastleggen-wat-je-niet-kon-horen). Here I highlight two constraints that enforce language preservation:

> **Language:** Use participants' *verbatim words* wherever possible for maximum recognizability.

> **Form:** Provide concrete hooks and insights, not literal scripts that [The Initiator] has to read aloud. He wants to protect his own authenticity.

**Why this structure works:**
- **Verbatim words** is more explicit than "use their language": it prevents AI from paraphrasing
- **No scripts** protects the facilitator's authenticity: AI delivers building blocks, not ready-made text
- **Maximum recognizability** names the goal, not just the method

**When:** With groups where you want to facilitate connection, not just capture information.

---

### Variation 2: Session analysis with participant language

This is the analysis approach we used at a session with key figures in Doesburg, a small Dutch town. You can apply this per table, per breakout, or per individual session.

**When:** After a session with structured rounds (e.g., dream scenario, challenges, own possibilities).

**Prompt:**
```
**Context**: Je analyseert het transcript van [één tafel/sessie/breakout]
over [onderwerp]. De sessie had [aantal] rondes: [ronde-namen].

**Opdracht**: Analyseer per ronde en identificeer:

### 1. Thema's met quotes
Per ronde: welke thema's kwamen terug?
- Met quotes die het thema dragen — in hun woorden, niet geparafraseerd
- Frequentie aangeven waar relevant

### 2. Eigenaarschaps-signalen
Herken taalpatronen die aangeven hoeveel eigenaarschap mensen voelen:

**Hoge eigenaarschap (0.7-1.0):**
- "Ik ga daar iets aan doen"
- "Wij moeten dit anders aanpakken"
- "Dat ga ik volgende week proberen"

**Gemengde eigenaarschap (0.4-0.6):**
- "Het zou moeten maar..."
- "Als er budget was dan..."
- "Ik probeer wel, maar het systeem..."

**Lage eigenaarschap (0.0-0.3):**
- "Daar kan ik niks aan doen"
- "Zij moeten dat oplossen"
- "Het is zoals het is"

→ Zoek specifiek naar concrete initiatieven en aanbiedingen.

### 3. Spanningen en paradoxen
- Waar spraken mensen zichzelf of elkaar tegen?
- Uitdagingen zonder "eigen mogelijkheid" ertegenover?
- Formuleer als vragen, niet als conclusies

### 4. Outliers
Dingen die met passie genoemd werden maar niet in een thema passen.
Niet clusteren — behoud als losse parels met context.

**Cruciale Randvoorwaarden**:
- Taal: Nederlands
- Herkenbare taal van deelnemers — geen consultant-speak
- Patronen benoemen, geen conclusies opdringen
- AI-observaties altijd expliciet labelen

**Don'ts**:
- Geen namen extern delen
- Interpretaties niet als feiten presenteren
- Niet "problematiseren" — de groep bepaalt wat problemen zijn
- Frustraties niet wegpoetsen of "constructief herformuleren"
- Niet parafraseren waar originele woorden krachtiger zijn

**Output Format**:
### [Ronde]: [Naam]
**Thema's**: [thema + quotes]
**Eigenaarschap**: [score-range + voorbeelden uit transcript]
**Spanningen**: [als vragen geformuleerd]
**Outliers**: [losse parels met context]
```

**Why this structure works:**
- **Ownership scale** gives AI a concrete framework (0.0-1.0) to score language
- **"Formulate as questions"** prevents AI from drawing conclusions the group hasn't drawn
- **"Loose pearls"** protects outliers against the urge to cluster everything
- **Don'ts** are explicit because AI tends to smooth over frustrations

*Want to compare multiple sessions? Analyze each session separately with this prompt first, lay the analyses side by side, and look for patterns. You'll find that step in Patterns over time *(Phase 3, coming soon)* (Phase 3).*

---

### Variation 3: Language preservation in live reflection

So far this has been about analysis after the fact. But language preservation also works live, in the middle of a session.

The echo prompt below is a lighter variant of the [full live reflection technique](../phase-2/live-reflection-with-ai.md). There you'll learn when to deploy it, how to prepare it, and how the workflow works. Here I focus on one aspect: how the prompt enforces language preservation.

**The language preservation element:**

Look at the output format:

> **Different framings**:
> - "Quote about how this is seen"
> - "Quote that adds different nuance"

This is language preservation in action. Not "some think X, others think Y" — but verbatim quotes that show how different people frame things. Participants recognize themselves. And that's exactly where ownership begins.

**The prompt:**
```
**Rol**: Je bent een ervaren groepsdynamiek-expert die signalen van
vermeden onderwerpen, onuitgesproken spanningen en verschillende
perspectieven detecteert in dialogen.

**Vereiste Stijl/Aanpak**:
- Niet-oordelend en uitnodigend
- Focus op wat ontbreekt, niet op wat fout is
- Herken diplomatieke taal die onderliggende spanningen maskeert

**Cruciale Randvoorwaarden**:
- Baseer signalen strikt op transcript — geen veronderstellingen
- Onderscheid tussen stilte en consensus
- Bij twijfel: "Mogelijk onderbelicht" ipv stellige bewering
- Genereer maximaal 2 echo-vragen voor facilitator

**Output Format**:
### Wat Ik Waarneem
**Mogelijk onderbelicht**: [Onderwerpen die opgeroepen maar niet
uitgediept werden]

**Verschillende framingen**:
- "Quote over hoe dit gezien wordt"
- "Quote die anders nuanceert"

### Echo-vraag voor de Groep
**[Eén krachtige vraag die uitnodigt tot verdieping]**

### Over Deze Echo
Deze echo-analyse is een hulpmiddel om mogelijke blinde vlekken te
belichten — niet om te oordelen, maar om uitnodigende vragen te stellen.
De keuze om hier op in te gaan blijft bij jullie.
```

**Why this structure works:**
- **Different framings** with verbatim quotes ensures people recognize themselves
- **Strict basis** "Base strictly on transcript" prevents AI from interpreting
- **Hedged language** "When in doubt: possibly underexposed" protects against overly assertive claims about what people "actually" meant

*For the full technique (when to deploy, how to prepare, the workflow) see [Live reflection with AI](../phase-2/live-reflection-with-ai.md).*

---

## Tensions

**"Cleaning up" for readability**
The tendency is to rewrite messy sentences into flowing text. But mess is often authenticity. A sentence like "Yeah but that's just... look, the problem is that nobody..." carries more than "The problem is that nobody."

*My approach:* I resist the urge to edit. If it was said, it gets to stay. I might use [...] for irrelevant detours, but the core stays exact.

**Frustration versus "challenge"**
The consultant reflex is to translate "it's driving me crazy" into "there are challenges." But the energy of frustration is information. That disappears in abstraction.

*My approach:* If it's a frustration, I call it a frustration. If someone says "it's a mess," I let that stand.

**Removing too much context**
"The whole class doesn't wear a helmet" without context is confusing. But too much context drowns the quote.

*My approach:* I quote with enough context to make the quote understandable, but not so much that the force disappears.

**Forgetting to label**
When AI recognizes patterns or poses questions, interpretation can merge with ownership. People then no longer know what's theirs and what's from AI.

*My approach:* I make visually clear what comes from participants and what comes from AI. Labeling is not optional.

---

## Safe defaults

*For privacy considerations with sensitive conversations, read [Safe practices with AI](../../safe-practices.md).*

- [ ] Exact words preserved? (not paraphrased "for clarity")
- [ ] Participant terminology used? (not translated into jargon)
- [ ] Frustrations named as frustrations? (not as "challenges")
- [ ] When in doubt, made explicit? ("Possibly underexposed")
- [ ] AI observations labeled as AI? (not merged with ownership)

---

## Philosophical deepening

**Principle:** Real-time feedback accelerates ownership

There's a reason why the moment in the mental healthcare transformation session was so striking (the mental healthcare network with thirty participants): people saw their words reflected back *immediately*.

Real-time feedback does something with ownership that delayed feedback can't. When you see your words reflected back immediately, the connection between speaking and result is still fresh. You don't just recognize the words; you recognize the moment. "I just said that. And now it's here."

This is why live reflection works. Why live synthesis has an impact a report never will. The speed isn't for efficiency. The speed is for ownership.

But (and this is crucial) speed without language preservation is barely useful. A fast synthesis in consultant-speak doesn't stimulate ownership. It has to be both: fast and in their words.

---

## Related techniques

- [Transcription as foundation](transcription.md): where it all begins
- [Source document style](source-document-style.md): when you also need to adopt structure and tone
- [Live reflection with AI](../phase-2/live-reflection-with-ai.md): real-time application of language preservation

---

**Navigation:**
- [Back to Phase 1: Start](../../phase-1-start.md)
- [Previous: Transcription](transcription.md)
- [Next: Source document style](source-document-style.md)

---

*Participants' words aren't just information, they are ownership.*
