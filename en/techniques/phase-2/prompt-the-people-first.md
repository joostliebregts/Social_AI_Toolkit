# Prompt the people first

> *The quality of AI output depends on the quality of human input.*

**Phase:** [Phase 2: Deepening](../../phase-2-deepening.md)
**Builds on:** [Reframing questions](reframing-questions.md)

---

## Why this page is in the toolkit

You'd expect a toolkit about AI to be all about the right prompts. But the techniques from the previous pages (transcription, analysis, pattern recognition) only work if the input is good. And that input comes from people.

---

## When is this relevant?

**Situation:** You're preparing a session where AI will play a role. You're thinking about which prompt to use.

**What I notice:** The quality of what AI can do depends entirely on what you give it. And what you give it depends on how you get people to share. The question "how do I prompt the AI?" actually comes after a more important one: "how do I prompt the people?"

**The principle:** If you design the human experience well (the right questions, in the right order, that invite stories rather than just opinions) then the AI prompt almost writes itself.

**The question:** Have I designed the input experience?

---

## The difference that makes the difference

Two questions, same goal: getting a picture of how collaboration could improve:

**Question A:** "What would the ideal collaboration look like?"

**Question B:** "Can you describe a moment when the collaboration felt right? What happened then?"

Question A yields abstract answers. Theory. Opinions about how things should be.

Question B yields stories. Raw material. A concrete moment you can explore.

AI can work with both. But what you get back is fundamentally different.

From opinions you get summaries of what people already knew they thought. From stories you get details people hadn't thought about yet: who was there, what made it different, how it felt. Those are the puzzle pieces AI can actually work with.

But how do you design questions that yield those puzzle pieces?

---

## The deconstructed burger

I like to think of workshops as a 'deconstructed burger': you start with what you want on the plate, and work backwards to the ingredients.

**Why this works:**

From my design background I learned this when testing prototypes: if you ask people "Would you buy this?" or "What would you pay for this?", you get a hypothetical answer. They think about what they should think.

But if you placed that same prototype as a product somewhere in a shop, and observed whether they actually pick it up, look at it, and buy it, you'd see real behavior.

The same logic applies to workshops: design questions that put people in their experience, not in their analysis. Don't ask what they think, but what they've lived through.

**Step 1: Start with the goal**
What do you want to have at the end of the session? What output does the group need to move forward?

**Step 2: Work backwards to puzzle pieces**
What ingredients do you need to get there? What insights, perspectives, experiences?

**Step 3: Determine the order**
In what order do you draw out the puzzle pieces? Start with experience, end with analysis, so people speak from feeling, not from their head.

**Step 4: Formulate the questions**
How do you get each puzzle piece from people? Not one big question, but separate questions that each yield something specific.
![Backwards design visualization](../../images/prompt-mensen-eerst-backwards-design.png)

**Example:**
- **Goal:** Set priorities based on real experience
- **Puzzle pieces:** Impact assessment + effort assessment + value for others
- **Order:** First impact (emotion), then effort (practical), then value (different perspective)
- **Questions:**
  1. "Describe a moment when this really had impact"
  2. "What did it cost you to do this?"
  3. "Who was happy about it, and how did you notice?"

Only then do you think about AI. The prompt becomes simpler because the input is richer.

In a co-creative session with 30 people I saw this work very concretely.

---

## From practice

### Transformation plan for a mental health network: backwards design in action

In a transformation project for a mental health network, the people involved had to formulate a vision. Three themes (Social Map, Consultation Table, Exploratory Conversation) were developed in parallel by different groups.

This example shows how good session design before you start working with AI makes all the difference. The facilitators Rianne and Jojanneke had prepared the session with carefully designed questions. They had already figured out the puzzle pieces. My role was to use AI to harvest what they had gathered: essentially just reflecting back the patterns that were already there.

**The goal:** Not just "what do you think?" but a concrete 5-year picture with steps to get there.

**The puzzle pieces:**
1. Perspective: what does this look like in 5 years?
2. Crucial elements that absolutely need to be included
3. What different behavior do you see?
4. What steps are needed to get there?

**The extraction questions (designed by the facilitators):**
- "Sketch your picture of 5 years from now, drawing or writing is fine"
- "What are crucial elements that absolutely need to be in there?"
- "What 'different' behavior do you see? What are we doing differently?"
- "What steps need to be taken to realize this perspective?"

**The order made it:**
First the ideal picture (emotion, dream), then the crucial elements (what matters), then behavioral change (concretely different), then steps (path to get there). Because of this order, people spoke from their aspirations, not from their analysis.

**The AI prompt:**
Because the input was so well structured, the prompt could precisely follow what the facilitators had designed:

**View the full prompt**

```prompt
Rol: Je bent een AI-assistent die helpt bij het live documenteren
van een transformatieplan-sessie. Jouw taak nu is om de kern van
de gevoerde visie-discussie samen te vatten voor directe feedback
aan de groep.

Context:
- Sessie Deel: Einde van Ronde 1 - Discussie over 5-jaarsperspectief
  (vraag 1 draaiboek).
- Input: Het volledige transcript van de zojuist afgeronde
  60-minuten discussie aan deze tafel.
- Doel Output: Terugkoppeling aan de deelnemers aan de tafel
  ter validatie ("Klopt dit beeld?").

Vereiste Schrijfstijl (Pas deze consistent toe):
- Taal: Formeel, zakelijk Nederlands.
- Toon: Collaboratief ("we", "samen", "gezamenlijk"), actiegericht,
  pragmatisch, oplossingsgericht.
- Perspectief: Geschreven vanuit de samenwerkende partijen, rekening
  houdend met perspectief van "inwoner", "naaste", "professional".
- Terminologie: Gebruik correcte en relevante jargon uit de
  Nederlandse zorg en GGZ (zoals IZA, GALA, MGN, POH-GGZ, positieve
  gezondheid, herstelgericht, domein overstijgend, etc.) waar passend.
- Structuur: Gebruik heldere zinnen, opsommingen (bullet points)
  waar nodig.

Instructies:
1. Analyseer het volledige input-transcript.
2. Identificeer het primaire thema dat in dit transcript wordt
   besproken. Kies uit: 'Sociale Kaart', 'Overlegtafel/transfertafel',
   of 'Verkennend Gesprek'. Als het thema niet eenduidig te bepalen
   is, noteer 'Thema Onduidelijk' en stop.
3. Focus op de gedeelten van het transcript die betrekking hebben
   op de 5-jaarsvisie (vraag 1 uit het draaiboek: hoe het eruitziet,
   wat het oplevert, cruciale onderdelen, ander gedrag, randvoorwaarden).
4. Genereer een beknopte, narratieve samenvatting van de gedeelde
   5-jaarsvisie voor het geïdentificeerde thema. Formuleer deze
   samenvatting strikt volgens de Vereiste Schrijfstijl.
5. Extraheer een lijst met 3-5 cruciale onderdelen of elementen
   die volgens de deelnemers absoluut in deze 5-jaarsvisie moeten
   zitten. Presenteer dit als een duidelijke bullet-point lijst.
6. Controleer op eventueel genoemde KPI's of meetbare resultaten
   en neem deze op in de samenvatting of de lijst.

Input Transcript: [Hier het volledige transcript]

Output Format:
Geïdentificeerd Thema: [Sociale Kaart / Overlegtafel / Verkennend Gesprek]

Concept Visie [Thema] (ter validatie):
[Narratieve samenvatting in de vereiste schrijfstijl]

Cruciale Onderdelen Visie:
- [Cruciaal onderdeel 1]
- [Cruciaal onderdeel 2]
- [Cruciaal onderdeel 3]
- ...
```

What I take from this: the richness was in the input, not in the prompt. Because Rianne and Jojanneke had designed the human experience so well, AI only needed to bundle what was already there.

What also struck me in this example: the order of the questions made a difference. They started with the ideal picture, not with the problems.

---

## The order of framing

You just saw it in the example above: the order made the difference. That's a pattern I see more often.

**Starting with problems:**
> "What are the challenges in the collaboration?"

This puts people in a critical mode. You get a list of what's wrong.

**Starting with the ideal:**
> "Describe a moment when the collaboration felt right. What happened then?"

This puts people in a constructive mode. You get examples of what they want more of.

From positive psychology: if you start with the ideal scenario and then work backwards to "What are the challenges to getting there?", you've framed things differently. People think about how to get somewhere, not about what's wrong.

**The order:**
1. Where do you want to go? (ideal)
2. What's already working? (positive experience)
3. What's in the way? (challenge)

Instead of:
1. What's wrong? (problem)
2. How do we fix it? (repair)

These are all design choices you make beforehand. But how do you know if a specific question is good?

---

## Check your questions

A quick test for every question you ask:

| Am I asking for... | What I get |
|--------------------|------------|
| An opinion | Abstraction, theory |
| An experience | A story, raw material |
| An analysis | Thinking, not feeling |
| A memory | Feeling, detail, authenticity |

**The simple check:**
> Am I asking for an opinion or an experience?

If it's an opinion, reformulate toward an experience.

**Example:**
- "What do you think about the communication in the team?"
- "Can you describe a moment when you thought: something's going wrong here?"

And if you need help designing those questions? Then you can use AI.

---

## The workshop preparation

This is how you can use AI to design the participant questions:

```prompt
Ik bereid een workshop voor over [ONDERWERP].

Mijn doel is: [WAT IK WIL BEREIKEN]

De deelnemers zijn: [WIE]

Ontwerp 3-5 vragen die:
1. Concrete ervaringen oproepen, geen meningen
2. Elk een ander "puzzelstukje" opleveren
3. In een logische volgorde staan (van emotie naar analyse)

Per vraag:
- De vraag zelf
- Welk puzzelstukje dit oplevert
- Waarom deze volgorde

Let op:
- Vermijd "Wat vind je van..."
- Gebruik "Beschrijf een moment waarin..."
- Focus op geleefde ervaring, niet op abstracte reflectie
```

**Why this structure works:**
- **Concrete experiences** "not opinions" prevents you from designing abstract questions that yield abstract answers
- **Different puzzle pieces** forces you to think ahead about what ingredients you need
- **From emotion to analysis** ensures the order is right
- **Avoid opinions** "Avoid 'What do you think about...'" blocks the default question that yields opinions

*This is a suggestion: adapt it to your specific situation.*

There's something lovely about this: you're using AI here to get sharper about the questions you ask people. Not to replace those questions, but to test your own thinking.

---

## The tension

There's a choice you keep making: can AI help me with the input I already have, or can I improve the questions I ask people?

Both are legitimate. But what I notice: when the output isn't what you hoped, the answer more often lies with the questions than with the prompt.

Concretely:
- **Getting abstractions back?** Check whether you're asking for experiences, not opinions.
- **Missing coherence?** Check whether you've identified the puzzle pieces.
- **Feels superficial?** Check whether the order is right: experience first, analysis later.

---

## Safety checklist

- [ ] Am I asking for experiences, not opinions?
- [ ] Have I identified the puzzle pieces?
- [ ] Is the order from emotion to analysis?
- [ ] Have I designed the input experience before thinking about AI?

---

## Philosophical deepening

### Facilitation over prompting

This principle goes deeper than technique. It's really about the question: where does value originate?

The tendency is to see AI as the source of value. "AI analyzes", "AI finds patterns", "AI generates insights". But AI works with what you give it.

The real value creation sits in the human experience. In what people share, how they share it, which stories surface. AI can amplify that, organize it, connect it — but it can't create it.

That's why: prompt the people first.

**The meta-insight:** sometimes you need to think like a computer for a moment. What do I need to get here? What building blocks do I need for that? That's designing backwards from the goal. Not starting with the tools, but with the goal. Not starting with AI, but with people.

---

## Related techniques

- [Transcription as foundation](../phase-1/transcription.md): capturing the output of good questions
- [Iteration](iteration.md): developing the questions themselves through dialogue with AI
- [Live reflection with AI](live-reflection-with-ai.md): asking real-time questions based on what's been said
- [Reframing questions](reframing-questions.md): reframing questions during the session itself

---

← [Previous: Iteration](iteration.md) | [Back to Phase 2](../../phase-2-deepening.md) | [Next: Reframing questions](reframing-questions.md) →

---

*"The facilitation question comes before the prompt question. First design the experience that generates good input. Only then think about AI."*
