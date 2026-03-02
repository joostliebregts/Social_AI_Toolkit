# Prompt the people first

> *The quality of AI output depends on the quality of human input.*

**Phase:** [Phase 2: Deepening](../../phase-2-deepening.md)
**Builds on:** [Transcription as foundation](../phase-1/transcription.md), with focus on designing the input experience

---

## Why this page is in the field guide

You'd expect a field guide about AI to be all about the right prompts. But the techniques from the previous pages (transcription, analysis, pattern recognition) only work if the input is good. And that input comes from people.

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
![[prompt-mensen-eerst-backwards-design.png]]
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
**Role:** You are an AI assistant helping with the live documentation
of a transformation plan session. Your task now is to summarize
the core of the vision discussion that just took place, for direct
feedback to the group.

**Context:**
- Session Part: End of Round 1 - Discussion on 5-year perspective
  (question 1 from the session script).
- Input: The complete transcript of the just-completed
  60-minute discussion at this table.
- Output Goal: Feedback to the participants at the table
  for validation ("Does this picture ring true?").

**Required Writing Style (Apply consistently):**
- Language: Formal, professional.
- Tone: Collaborative ("we", "together", "jointly"), action-oriented,
  pragmatic, solution-focused.
- Perspective: Written from the perspective of the collaborating
  parties, taking into account the viewpoints of "resident",
  "family member", "professional".
- Terminology: Use correct and relevant jargon from the
  Dutch healthcare and mental health system (such as IZA, GALA,
  MGN, POH-GGZ, positive health, recovery-oriented,
  cross-domain, etc.) where appropriate.
- Structure: Use clear sentences, bullet points where needed.

**Instructions:**
1. Analyze the complete input transcript.
2. Identify the primary theme discussed in this transcript.
   Choose from: 'Social Map', 'Consultation Table/Transfer Table',
   or 'Exploratory Conversation'. If the theme cannot be
   unambiguously determined, note 'Theme Unclear' and stop.
3. Focus on the parts of the transcript relating to the
   5-year vision (question 1 from the script: what it looks like,
   what it delivers, crucial elements, different behavior,
   preconditions).
4. Generate a concise, narrative summary of the shared
   5-year vision for the identified theme. Formulate this
   summary strictly according to the Required Writing Style.
5. Extract a list of 3-5 crucial elements that participants
   say absolutely need to be in this 5-year vision.
   Present this as a clear bullet-point list.
6. Check for any mentioned KPIs or measurable results
   and include these in the summary or the list.

**Input Transcript:** [Insert the complete transcript here]

**Output Format:**
Identified Theme: [Social Map / Consultation Table / Exploratory Conversation]

Draft Vision [Theme] (for validation):
[Narrative summary in the required writing style]

Crucial Vision Elements:
- [Crucial element 1]
- [Crucial element 2]
- [Crucial element 3]
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
- ❌ "What do you think about the communication in the team?"
- ✅ "Can you describe a moment when you thought: something's going wrong here?"

And if you need help designing those questions? Then you can use AI.

---

## The workshop preparation

This is how you can use AI to design the participant questions:

```prompt
I'm preparing a workshop about [TOPIC].

My goal is: [WHAT I WANT TO ACHIEVE]

The participants are: [WHO & THEIR ROLES]

Design 3-5 questions that:
1. Evoke concrete experiences, not opinions
2. Each yield a different "puzzle piece"
3. Are in a logical order (from emotion to analysis)

Per question:
- The question itself
- Which puzzle piece this yields
- Why this order

Note:
- Avoid "What do you think about..."
- Use "Describe a moment when..."
- Focus on lived experience, not abstract reflection
```

**Why this structure works:**
- **"Concrete experiences, not opinions"** prevents you from designing abstract questions that yield abstract answers
- **"Each a different puzzle piece"** forces you to think ahead about what ingredients you need
- **"From emotion to analysis"** ensures the order is right
- **"Avoid 'What do you think about...'"** blocks the default question that yields opinions

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

## Reach people where they are

The input experience doesn't start with the workshop question. It starts with the invitation.

In Doesburg, a small Dutch town, the steering group learned that standard communication (email, websites, flyers) doesn't always work when you want to reach people in their own world. You need to communicate in the place and manner that fits the audience. Floor de Ruiter, process facilitator and expert in bottom-up work, knew this from experience:

> "You shouldn't invite flower growers by email... You need to send a text message, because that's what they read on the tractor."

This isn't just a channel choice. It's a broader pattern: being present at the mosque instead of sending a letter. Writing texts at a sixth-grade reading level, not because people aren't smart, but because it needs to be clear. The steering group in Doesburg eventually also started individually inviting people for an important session.

The lesson for "prompt the people first": if you approach people through a channel that isn't theirs, you won't reach them. The question "how do I design the input experience?" starts earlier than you think.

---

## Philosophical deepening

### Facilitation over prompting

This principle goes deeper than technique. It's really about the question: where does value originate?

The tendency is to see AI as the source of value. "AI analyzes", "AI finds patterns", "AI generates insights". But AI works with what you give it.

The real value creation sits in the human experience. In what people share, how they share it, which stories surface. AI can amplify that, organize it, connect it, but it can't create it.

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
