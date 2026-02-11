# Live reflection with AI

> *At precisely the right moment, AI asks the question that helps the group move forward.*

**Phase:** [Phase 2: Deepening](../../phase-2-deepening.md)
**Builds on:** Transcription as raw material, now used for real-time intervention

---

## When is this relevant?

**Situation:** You're facilitating a conversation. The energy drops, people repeat themselves, the conversation goes in circles. Or: there's palpable tension that nobody names.

**My tendency:** I'm getting better at trusting my intuition and naming things explicitly. At the same time, I still doubt sometimes, and hope someone else will name it.

**What helps here:** When you're not sure, or when you know what's behind the echo button, you have a co-facilitator who can work with the entire transcript. As a human you have limited storage in your brain, no matter how attentively you listen. The echo button looks at the conversation from a different perspective and can help you that way.

**The question:** What would happen if at that moment you had an extra set of eyes: a co-facilitator who had heard the entire conversation?

---

## The question that opened the conversation

*You might already know this story from the [why page](../../why.md). Here we go deeper into timing: the right moment for the right question.*

A session about neighborhood transformation. Eight people talk for 45 minutes about the tension between system requirements and a people-centered approach. The energy starts to drop.

Facilitator Jeroen hits the echo button. Within 10 seconds AI generates this question:

> "Given the challenges you're describing, it seems crucial to start with small achievable steps that have direct impact in the neighborhood. Can we think of an example of such a concrete action we could start tomorrow, without getting stuck in system requirements?"

The reaction was immediate.

> "That's quite something."
> "That's the well-known, how are we going to start tomorrow with something small?"
> "Nicely done!"
> "Yes, that's it."

10 seconds. One question. The conversation that was stuck started moving.

---

## Live versus semi-live

There's an important distinction in how you deploy AI during sessions.

**Live (the echo button):**
Directly in the session, with one press of the button. AI analyzes the last few minutes and immediately generates a question. This works with tools like Dembrane that couple real-time transcription to prompt functionality.

**Semi-live (breakout moments):**
Between blocks. For example: while groups work in breakout sessions, you take the transcript up to that point, run a longer prompt, and copy the output to a Google Doc that the facilitator can then show on screen to the group.

The difference is in speed and context:
- **Live:** Seconds. Works on the last few minutes. Suitable for intervention in the moment.
- **Semi-live:** 1-2 minutes, depending on your workflow. Works on longer segments. Suitable for interim synthesis and reflection.

Both require preparation: your prompts need to be ready. The difference is when you deploy them and how many steps are in between: from running the prompt to showing something on screen to the group.

run prompt, copy output, paste in document, show to group

The fewer intermediate steps, the faster.

---

## What makes the echo button different?

The echo button isn't a summary. It's a (mini) intervention.

**Summary:** "You've talked about X, Y, and Z."
**Echo:** "You've been talking a lot about 'communication problems' — what do you mean exactly? Can someone describe a concrete moment?"

The difference is in the question. A summary closes. An echo opens.

**The three levels:**
| Level | What it does | Example |
|-------|-------------|---------|
| **Mirror** | Reflects what was said | "You mentioned X, Y, and Z" |
| **Synthesis** | Connects patterns | "What stands out: everyone mentions 'time' but means something different" |
| **Serendipity** | Asks the question that wasn't asked | "What would change if X wasn't the problem?" |

Echo operates at the synthesis and serendipity level. It connects and asks further.

---

## The prompt

This is the working echo prompt from the Doesburg leadership workshop.

```
**Rol:** Je bent een ervaren groepsdynamiek-expert die signalen van
vermeden onderwerpen, onuitgesproken spanningen en verschillende
perspectieven detecteert in dialogen.

**Context:** Je analyseert de laatste 10-15 minuten van een
[TYPE SESSIE]. Deelnemers zijn [WIE]. Ze kennen elkaar [RELATIE].

**Vereiste Stijl:**
- Niet-oordelend en uitnodigend
- Focus op wat ontbreekt, niet op wat fout is
- Herken diplomatieke taal die onderliggende spanningen maskeert

**Cruciale Randvoorwaarden:**
- Baseer signalen strikt op transcript, geen veronderstellingen
- Onderscheid tussen stilte en consensus
- Bij twijfel: "Mogelijk onderbelicht" ipv stellige bewering
- Genereer maximaal 2 echo-vragen voor facilitator
- Focus op laatste deel van gesprek

**Instructies:**
1. Analyseer de laatste 10-15 minuten van het transcript
2. Identificeer onderwerpen die opgeroepen maar niet uitgediept werden
3. Detecteer momenten waar energie wegviel of onderwerp verschoof
4. Zoek verschillen in framing tussen deelnemers
5. Herken "ja, maar..." patronen als signaal voor spanning
6. Kies één krachtige echo-vraag die het belangrijkste adresseert

**Output Format:**
### Wat Ik Waarneem
**Mogelijk onderbelicht:** [Onderwerpen die niet uitgediept werden]

**Verschillende framingen:**
- "Quote over hoe dit gezien wordt"
- "Quote die anders nuanceert"

### Echo-vraag voor de Groep
**[Eén krachtige vraag die uitnodigt tot verdieping]**

### Over Deze Echo
Deze echo is een hulpmiddel om mogelijke blinde vlekken te belichten,
niet om te oordelen. De keuze om hier op in te gaan blijft bij jullie.
```

**Why this structure works:**
- **Role** defines expertise: "group dynamics expert" steers toward detecting what isn't being said
- **Context** makes it specific: "last 10-15 minutes" prevents AI from trying to capture everything
- **Required Style** guards the tone: "non-judgmental" prevents the echo from feeling like criticism
- **Critical Constraints** are the hard boundaries: "maximum 2 echo questions" prevents overwhelm
- **Instructions** steer the search process: the sequence (first analyze, then detect, then choose) provides focus
- **Output Format** structures the output: "One powerful question" forces selection

**Source:** Prompt I use for live group reflection (Doesburg leadership workshop)

---

## Three tactics

**DEEPENING:**
Use when the conversation stays on the surface. People name symptoms but not underlying concerns.

> "You've been talking a lot about 'communication problems' — what do you mean exactly? Can someone describe a concrete moment?"

**CONCRETIZING:**
Use when the conversation stays abstract: lots of theory but no concrete next steps.

> "Given what you're sharing, what could be a first small step that could be taken tomorrow?"

**REFLECTING:**
Use when the connection between perspectives is missing.

> "I hear that Table Red wants 'more time,' but Table Blue says 'too many meetings' — could 'time' mean something different for both groups?"

---

## When to use, when not to

**When YES:**

| Signal | What you do |
|--------|-------------|
| Energy drops, conversation goes in circles | Echo with concretizing question |
| End of session, group lacks clear picture | Echo with reflecting question |
| Tension palpable but unnamed | Echo with deepening question |
| New phase begins, bridge needed to previous | Echo as opening |

**When NOT:**

| Signal | Why not |
|--------|---------|
| Someone shares a personal story | Space for emotion IS the intervention |
| First session, you don't know the group yet | Echo can miss without understanding of context |
| No strategic preparation | Weak prompts, AI decides, substitution risk |
| Facilitator looks at screen instead of people | Reading real-time group dynamics is human work |

---

## The role division

This works best with two people:

**Facilitator:** Stays with the group. Reads faces, holds emotions, guides the process. Doesn't look at a screen.

**Co-facilitator:** Monitors the transcription, selects the last few minutes, launches the echo prompt, does quick iterations if needed.

When the echo is ready, the facilitator reads it in their own words, not verbatim. The echo is a suggestion, not a script.

---

## Tensions

**Timing of intervention**
Too early feels like interruption. Too late and the energy is already gone.

*My approach:* I wait until I feel that the group is stuck somewhere. Or until I'm unsure myself and don't know how to proceed, then the echo is a helping hand.

**AI language versus own voice**
What AI generates is a suggestion, not a script. Reading it verbatim can come across as mechanical — but if the preparation was thorough, that's also fine.

*My approach:* I usually paraphrase in my own words. But if I've prepared the echo prompt well, I sometimes read it verbatim too.

**Spontaneous versus prepared**
The question that made "mouths fall open" didn't come from nowhere. There was strategic preparation behind it.

*My approach:* 80% of the success is in preparation. I design the echo prompt beforehand based on what I expect.

**Echo as replacement for facilitating**
The echo is a tool, not a solution. If all I do is press buttons, I miss what's happening in the room.

*My approach:* I stay present. The echo supports my perception, it doesn't replace it.

---

## Safe defaults

*For privacy considerations with live transcription, read [Safe practices with AI](../../safe-practices.md).*

- [ ] Focus on last 10-15 minutes? (not the whole conversation)
- [ ] "Possibly underexposed" instead of assertive claims?
- [ ] Maximum 2 echo questions? (don't overwhelm)
- [ ] AI observations labeled as AI?
- [ ] Strategic preparation done?

---

## Tools

| Tool | What for | Nuance |
|------|----------|--------|
| **Dembrane** | Real-time transcription + echo button functionality | Suitable for multiple sessions: everything centralized to one platform |
| **Notion AI** | Live transcription + AI prompts on the page | Good for one meeting you're in yourself |
| **MacWhisper + Claude/ChatGPT** | Transcribe yourself + run echo prompt manually | Most flexible, most manual work |

**When which tool:**
- **One meeting, you're there yourself:** Notion AI works fine. You record, transcript appears, you prompt AI directly on that same page.
- **Multiple sessions, breakout groups, or you're facilitating:** Dembrane. You can send different recordings to one place and analyze centrally.

---

## Philosophical deepening

### Timing over perfection

The echo question in the neighborhood transformation session wasn't particularly complex. "Small achievable steps", "start tomorrow", "without getting stuck in system requirements": these aren't deep insights.

What made it special was the timing. After 45 minutes of discussion, at the moment the energy dropped, precisely the question the group needed arrived.

This is the difference between analysis and intervention. A perfect analysis a week later would have had less impact than a good question at the right moment.

### The echo as mirror

There's something else. When AI asks the question, it's not "the facilitator who thinks that..." It's an external mirror. People respond differently to a question that comes from AI than to the same question from the facilitator.

Sometimes that distance is needed. The question becomes neutral, investigative, non-judgmental.

But (and this is crucial) the facilitator needs to take ownership of the question. Not: "AI says this." But rather: "A question is coming up that I find interesting..." The echo is input, the facilitator is the voice.

---

## Related techniques

- [Transcription as foundation](../phase-1/transcription.md): where the raw material comes from
- [Iteration](iteration.md): how you develop the echo prompts yourself
- [Intuition in writing](intuition-in-writing.md): making visible the patterns you already felt

---

[Back to Phase 2: Deepening](../../phase-2-deepening.md) | [Previous: Reframing questions](reframing-questions.md) | [Next: Conversation to plan](conversation-to-plan.md)

---

*"10 seconds can transform 45 minutes of dialogue. Not through the perfect question, but through the question at the perfect moment."*
