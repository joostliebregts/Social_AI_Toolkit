# Iteration as dialogue

> *Not tinkering with output, but giving feedback. AI learns what you mean.*

**Phase:** [Phase 2: Deepening](../../phase-2-deepening.md)
**Builds on:** The first AI output that's not quite right

---

## When is this relevant?

**Situation:** You get output from AI. It's 60% of what you're looking for. The reflex is to adjust it yourself: change words, rewrite sentences.

**The tendency:** Solo work. You take the output and tinker until it fits. AI is done, you take over.

**The principle:** AI output is essentially never quite finished. It's input for a dialogue. By giving feedback instead of tinkering, AI learns to work with your specific needs. The result is better than what you would have made on your own. And you learn to put into words what you actually want.

**The question:** Am I giving feedback, or am I tinkering on my own?

---

## The story: twelve rounds

A transformation plan for a mental health network. Thirty stakeholders had given input. Now that needed to be turned into a document the health insurer would accept.

There was already an approved transformation plan from another region. The question: how do you write new sub-plans in the same style?

This didn't become a one-off prompt. It became twelve rounds.

**Round 1:** I describe what I want.
**Round 2:** AI proposes a step-by-step plan.
**Round 3:** I add the session script for context.
**Round 4:** AI adjusts the prompts to match the script.
**Round 5:** I ask for three specific prompts.
**Round 6:** AI delivers three prompts, but the style isn't right yet.
**Round 7:** I ask for universal versions.
**Round 8:** AI adjusts, but still misses something.
**Round 9:** Crucial correction: "The style needs to be IN the prompt, because AI doesn't have access to the example."
**Round 10:** AI processes the correction.
**Round 11:** I clarify the context window situation.
**Round 12:** Prompts are ready.

Four concrete corrections that made the difference. The common thread: you assume AI knows what you know. AI knows an enormous amount — but not your specific context: the documents you have, the agreements you made, the style you're after. What you don't explicitly provide, doesn't exist for AI.

- "The AI doesn't have access to the example plan, so include the writing style IN the prompt"
- "Make the prompts universal: AI can detect the theme from the transcript itself"
- "Prompt 2 should mainly generate questions for the next group"
- "The AI has access to full transcripts, not fragments"

This insight (that you need to explicitly tell AI what it needs to know) also comes back in [Source document style cloning](../phase-1/source-document-style.md), where it's the core of the technique.

When I looked back at this, I saw a pattern: a prompt doesn't emerge in round 1. The prompt evolves through the corrections.

**Source:** Iteration process I went through during transformation plan development (GGZ Centraal Gelderland)

---

## The shift: from tinkering to steering

```
❌ Tinkering: Get AI output → Adjust it yourself → Done
✅ Iterating: Get AI output → Pause → Give feedback → Repeat
```

The difference is subtle but fundamental. Tinkering is solo work. Iterating is collaborating.

**What tinkering looks like:**

> You get a summary from AI. The tone is too formal.
>
> You open the document and start rewriting sentences. "Stakeholders" becomes "the people involved". "Implemented" becomes "introduced".
>
> Twenty minutes later, it's done. AI has learned nothing. You did the work.

**What iterating looks like:**

> You get the same summary. The tone is too formal.
>
> **Round 1:** "This feels like a policy document. I'm looking for the tone of a conversation between colleagues who've known each other for a long time and are transparent about their needs. Use ordinary words, no jargon. Try again."
> *Thirty seconds later: new version. Better, but not quite there yet.*
>
> **Round 2:** "Better. But the first paragraph is still too distant. Make it more personal."
> *Another thirty seconds. Now it lands.*

**Why this works:**
- **Learning context** AI learns your needs within the ongoing conversation
- **Sharper articulation** you articulate more sharply what you want, for yourself and for AI
- **Combined capacity** the end result combines AI's capacity with your direction
- **Next iteration** next time, you can already say: "tone of a conversation between colleagues who've known each other a long time, transparent about needs, no jargon"

*Note: start a new conversation, and the context window is empty again. You start from scratch. That's why it pays to keep iterating within a single session.*

### Dictation as accelerator

The barrier to giving feedback is typing. If you have to type out every correction, iterating feels like work. But dictation changes that.

The workflow: AI gives output → you speak your reaction → within a second it's there as text

You don't have to formulate while typing. You just say what you think: "No, this is too formal. I'm looking for more of a kitchen table conversation tone." That's faster than typing, and it feels more natural: more like a conversation.

*See [Transcription](../phase-1/transcription.md#dictation-as-accelerator) for tools and setup.*

---

## Iteration upfront: let AI ask you the questions

So far, this has been about iteration on output: you get something from AI, you give feedback, AI adjusts. But there's another form: iteration *upfront*. There, you let AI first help you get clear on what you want, before any output comes. The back and forth with AI is a skill in itself.

The technique: ask AI to ask you questions with two options each time. That forces you to choose a position. And the nuances you add to your choice ("I want both", "but from the positive angle", "I decide myself how I share them") make the prompt sharper than it would have been without the dialogue.

For the full story of how this played out in practice (three questions, three adjustments, a prompt that did exactly what Maarten needed), see [What else was in there](what-else-was-in-there.md).

### The prompt that makes AI ask you questions

This behavior (AI asking you questions with A/B options) needs to be explicitly triggered. Here's the prompt that does it:

```prompt
I'm working on [PROJECT/GOAL].

Current state of affairs:
- Goal: [what you want to achieve]
- Audience: [for whom]
- What I'm struggling with: [open questions, doubts]

Ask me 3-5 sharp questions that help me to:
1. Get my goal clearer
2. Make crucial choices explicit
3. Identify blind spots

Where relevant: present choices (A vs B) instead of
just open questions. This forces me to choose a position.

After my answers: ask follow-up questions based on
what I've chosen.
```

The power is in "present choices (A vs B)". That forces you to choose a position, and the nuances you add to your choice are exactly where the value lies.

---

## The toolbox

The twelve-rounds story above shows iteration on output. Iteration upfront shows how to give direction before any output comes. But what if you concretely want to know *how* to give feedback? Or how to learn from your own adjustments? Here are the methods I use.

### Feedback formulas

When AI output doesn't land, give specific feedback. Say it as if you're dictating:

**For tone:**

```prompt
Make it warmer, as if you're telling it to a colleague.
```

```prompt
This feels like consultant speak, can you use the participants' words?
```

**For structure:**

```prompt
Too long, can you use fewer bullets and more narrative?
```

```prompt
The order isn't right, can you start with X instead of Y?
```

**For content:**

```prompt
This misses the nuance about X, can you add this, this, and this please?
```

```prompt
This is 70% of what I'm looking for. What's missing is X, can you try again?
```

**For framing:**

```prompt
This is framed too negatively, can you frame it from what people want?
```

```prompt
This sounds like AI knows it for sure, can you use 'possibly' and 'it seems like'?
```

**When you don't know what you want:**

```prompt
This isn't what I'm looking for in terms of tone and structure, but I don't entirely know what I do want. Can you ask me questions to figure out what options there are and which works better for me?
```

**When you're torn between options:**

```prompt
I'm torn between these two formats. Can you briefly work out both so I can read the examples and give feedback on those?
```

### The feedback loop prompt

Imagine: you've significantly adjusted AI output. You've rewritten sentences, changed the structure, adjusted the tone. Instead of "losing" that work, you can feed it back to AI so your prompt works better next time.

```prompt
This was the original output:
[paste AI output]

This is what I made of it:
[paste your improved version]

Analyze the differences:
1. What did I change?
2. Why do you think I changed that?
3. How should I adjust the prompt to get closer to my
   desired output next time?

Give concrete suggestions for prompt improvements.
```

**Why this structure works:**
- **Original next to revision** forces AI to compare concretely, not advise abstractly
- **Three analysis questions** structure the reflection from observation to action
- **Prompt improvements** as end goal make every iteration cumulatively better

*This is a suggestion: adapt it to your specific situation.*

This seems like extra work, but it's an investment. Every iteration makes your prompts sharper.

### Prompt test cycle

**When do you use this?**
- You have existing transcripts and want to test whether a new prompt works
- There's a new AI model and you want to check if your prompts still perform well
- You want to improve systematically rather than ad hoc

For example: you have a prompt that worked fine with Gemini 2.5, but now there's a new model. Does your prompt still work? Or you have ten transcripts from previous sessions and want to test whether your new analysis prompt pulls out the right things.

The approach: test your prompt on real data and let AI evaluate its own work.

The steps:
1. **Build the prompt together with AI**: for example, a prompt for transcript analysis
2. **Test on real data**: run the prompt on a relevant transcript
3. **Collect the output**: what came out?
4. **Feed back to the AI that built the prompt:**

```prompt
I tested the prompt we built together on a real transcript.

This is the output that came out:
[paste the output]

Questions:
1. How well did our prompt perform for what we wanted to achieve?
2. What's missing from the output?
3. How should we adjust the prompt to get closer to our goal?
```

**Why this structure works:**
- **Real data as test** prevents your prompt from only working in theory
- **Three evaluation questions** force reflection on performance, gaps, and improvement
- **Cyclical design** makes the prompt itself the object of iteration

5. **Refine the prompt**: let AI adjust the original prompt based on the test

This is different from the feedback loop above. There, you adjust the output and let AI learn from your adjustments. Here, you test the prompt itself and let AI evaluate how well the prompt performed.

*Source: Method I developed for iterating Dembrane prompts.*

### Cross-model critique (advanced)

This is a time-intensive technique for work you really want to polish: having two AIs review each other's work. I used this for workshop design: ChatGPT and Gemini reviewed each other's output until they converged at 98/100.

**Why this works:**
- **Model diversity** different models have different biases and strengths
- **Peer critique** critique from a "peer AI" helps identify blind spots
- **Convergence** shows robustness of the result

**When to consider:**
- Work where you're really looking for depth (strategic plans, workshop designs)
- Complex analyses where you want multiple perspectives
- As a check whether one AI is misleading you

#### Step 1: Ask both AIs for a summary

To both AIs (separately):

```prompt
We worked together on [PROJECT/QUESTION].

Summarize:
- The core question we were trying to answer
- The approach we chose
- The key insights that emerged
- The weak points or blind spots in our analysis
- A rating (0-100) for the quality of our work

Be critical and honest about limitations.
```

**Why this structure works:**
- **Forcing self-critique** via "be critical" prevents self-congratulatory output
- **Rating** forces the AI to make a quantitative judgment about its own work
- **Five dimensions** cover from core question to blind spots across the full spectrum

#### Step 2: Have them review each other

Feed summary A to Model B:

```prompt
Another AI made this summary of work on the same question:

[COPY SUMMARY A]

Review this summary:
1. What are strengths that we don't have?
2. What are weak points they don't see?
3. What blind spots does this analysis have?
4. How would you combine our approach with their insights?
```

**Why this structure works:**
- **External review** breaks through the bias of one model
- **Four targeted questions** steer the critique from strengths to synthesis
- **Combination question** forces constructive integration, not just critique

Do the same the other way around.

#### Step 3: Integrate

```prompt
I now have two analyses and mutual critique.

Analysis A: [SUMMARY A]
Critique from B on A: [CRITIQUE B->A]

Analysis B: [SUMMARY B]
Critique from A on B: [CRITIQUE A->B]

Synthesize into one integrated perspective that:
- Retains the strengths of both
- Addresses the weak points of both
- Adds new insights that emerge from the confrontation
```

*This is time-intensive. Use it sparingly, for work where it really matters.* Or where your curiosity drives you :)

---

## Tensions

**Tinkering right away**
The first reflex is to adjust output instead of giving feedback. But then AI learns nothing and I'm doing the work myself.

*My approach:* I pause. I ask myself: "Can I formulate this as feedback?" If yes, then feedback. If no, then it might be better to start over with a sharper prompt.

**Iterating endlessly**
Sometimes 80% is good enough. Perfection can paralyze.

*My approach:* I ask myself: "Is this good enough to take the next step?" If yes, move on.

**Vague feedback**
"This doesn't feel right" is what I feel. But AI doesn't know what needs to change.

*My experience:* When I'm frustrated with output, I notice my feedback gets vague too. What helps: pause for a moment and name what exactly doesn't land. "The tone is too formal" works better than "this doesn't feel right."

**Feedback without direction**
The tendency is to say what's wrong without saying what I'm looking for.

*My experience:* I notice AI responds better to "I'm looking for [X]" than to "this isn't what I want." And honestly: it also forces me to get clear on what I actually want.

---

## Safety checklist

*For privacy considerations when sharing transcripts, read [Safe practices with AI](../../safe-practices.md).*

- [ ] Feedback specifically formulated?
- [ ] Direction given, not just critique?
- [ ] Paused before tinkering?
- [ ] For significant adjustments: feedback loop prompt used?

---

## Philosophical deepening

### The process IS the value

In the twelve-rounds iteration, round 9 was the turning point: "The style needs to be IN the prompt, because AI doesn't have access to the example."

This insight didn't come from nowhere. It came because the output from round 6 wasn't right: the style wasn't in it. Without that failure, no correction. Without that correction, no working prompts.

The value wasn't in the first attempt. The value was in the process of discovering what was missing.

### Dialogue creates commitment

There's a deeper layer. When you give AI feedback, you articulate what you want. That articulation makes your intention explicit, for yourself, not just for AI.

This is the same mechanism as with people. Dialogue creates clarity. The fact that you have to explain what you mean forces you to know what you mean.

---

## Related techniques

- [Live reflection with AI](live-reflection-with-ai.md): real-time application of iteration
- [Prompt the people first](prompt-the-people-first.md): the question before the prompt question
- [Source document style cloning](../phase-1/source-document-style.md): the 12-rounds story in detail

---

← [Previous: What else was in there](what-else-was-in-there.md) | [Back to Phase 2](../../phase-2-deepening.md) | [Next: Prompt the people first](prompt-the-people-first.md) →

---

*"A prompt doesn't emerge, it evolves. The value is in the accumulation of refinements: each correction makes the next one better."*
