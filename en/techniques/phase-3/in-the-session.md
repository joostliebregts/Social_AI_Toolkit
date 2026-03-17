# In the session

> *Using AI in co-creative sessions with multiple groups.*

**Phase:** [Phase 3: Scale](../../phase-3-scale.md)
**Builds on:** [Conversation to plan](../phase-2/conversation-to-plan.md), [Prompt the people first](../phase-2/prompt-the-people-first.md)

---

## When is this relevant?

**Situation:** You're facilitating a session with multiple groups. Breakouts, tables, rounds. Conversations are being recorded. And now you want to know: how do I use AI to capture what all those groups are saying, analyze it, and reflect it back?

**What I notice:** Most facilitators know breakouts. But combining what's being said at different tables, that's manual work that usually doesn't fit within the time you have. AI makes it possible for the first time to make that combination: analyze per table, and then lay the analyses side by side.

**The principle:** The same approach as with a single conversation (first analyze separately, then synthesize), but applied to multiple groups at once. The [core principle of Phase 3](../../phase-3-scale.md) applied within a single session day.

**The question:** How do you organize that in practice?

---

## Three formats

There are three ways to use AI in sessions with multiple groups. The difference is in how and when you reflect the output back.

## 1. Parallel: multiple tables, the same questions

```
  Table A ---> Analysis A ---+
                              |
  Table B ---> Analysis B ---+---> Synthesis
                              |
  Table C ---> Analysis C ---+
```

Groups talk simultaneously about the same questions. Each table is transcribed and analyzed separately. There's no connection between the tables during the session. The synthesis happens afterward.

## From practice: key figures session in Doesburg

In a bottom-up care process in Doesburg, a small Dutch town, we organized a session with key figures from the neighborhood: people who know the social fabric of their municipality. The question: what does good care and care for each other look like in this community?

Four tables, each with a table host. Three rounds with the same questions: dream scenario ("what does your ideal situation look like?"), challenges ("what are the obstacles?"), personal possibilities ("what can you do about that yourself?"). Each table was transcribed via Dembrane. After the session: each table analyzed with the same prompt, then the four analyses laid side by side.

> Eight themes that came up at multiple tables. "Noaberschap" (a Dutch concept of neighborly care: looking out for each other) appeared at all four. "Maintaining ownership over your own life" at three. People who hadn't been sitting together but turned out to feel the same things.

---

**When this fits:** When you want groups to have their own conversation without steering in between. When you want to preserve the richness of each table separately. When the synthesis doesn't necessarily have to happen live.

**The prompt:** Two prompts in tandem: an analysis prompt that you use for each table (that makes the results comparable), and a synthesis prompt that lays the analyses side by side. Copy the prompt below; it helps you create both prompts for your session.

<ProbeerStory experiment="in-the-session"></ProbeerStory>

---

## 2. Sequential: groups build on each other, synthesis afterward

```
  Group 1 ---> Analysis ---> [on screen]
                                   |
               Group 2 ---> Analysis ---> [on screen]
                                               |
                             Group 3 ---> Analysis
                                               |
                                               v
                                         Final synthesis
```

Groups rotate to the same table. The chairperson shows the AI summary of the previous round. Each round is recorded and analyzed separately. At the end you bring everything together.

## From practice: transformation plan for mental healthcare

In a process for mental healthcare (GGZ, the Dutch mental health system), three theme tables were set up, each with a chairperson. Round 1 (60 minutes): each group builds a 5-year vision. Transcription via Dembrane. AI generates a summary: shared vision, crucial elements, future scenarios.

Then groups rotate. Round 2 (25 minutes): the chairperson shows the Dembrane summary on the screen. The new group responds, sharpens, adds. Recorded again. Round 3 (25 minutes): the same, rotating again.

At the end: three rounds per theme analyzed separately, then synthesized into a draft sub-plan per theme.

*More about how to prepare such a session: in [Prompt the people first](../phase-2/prompt-the-people-first.md), Rianne Runhaar and Jojanneke Diemers describe how they worked backward from the goal of this session to determine which steps were needed and which puzzle pieces they wanted to gather at each table.*

---

**The difference from parallel:** Here, groups do build on each other. The chairperson reflects back what the previous group said. But each round is analyzed separately; the AI doesn't build on a running document.

**When this fits:** When you want groups to respond to each other's work. When the chairperson plays a strong role in connecting rounds. When you want to keep the separate analyses for comparison.

**The prompt:** Two prompts in tandem: an interim analysis after each round, and a final synthesis after the session. Paste the prompt below into the AI tool of your choice; it helps you create both prompts for your session.

<ProbeerStory experiment="in-the-session-sequential"></ProbeerStory>

---

## 3. Iterative: AI builds on between rounds

```
  Group 1 discusses         ---> AI ---> V1 [on screen]
                                          |
  Group 1: "is this right?" ---> AI ---> V2 [on screen]
                                          |
  Group 2 responds          ---> AI ---> V3 [on screen]
                                          |
  Group 2: "is this right?" ---> AI ---> V4 [on screen]
                                          |
                     ... next group ...
```

This is the AI-augmented version of "sequential." Here, AI processes each group's feedback directly into a running document. The next group doesn't just see a summary but the updated result, with all previous groups' feedback already incorporated.

The cycle: each group gets the result on screen, responds, and then gets the processed version back. "Is this right?" Only when the group is satisfied does it move on to the next. Nobody starts on a blank page; each group responds to something concrete.

## From practice: mission/vision session in Amsterdam

A session with roughly 25 participants in the Netherlands. The day started with a warm-up that was also functional:

Round 1: six people sat at a table with a phone (Dembrane was recording). The rest of the group stood around and listened in. They discussed the existing mission and vision. AI processed the transcript into a first version (V1), which was presented on the screen. The same group responded: is this picture right? Is anything missing? Their feedback was processed into V2.

Round 2: a new group of six sat down. They saw V2 and discussed what still needed refining. AI processed their response, put the result back to the group, and after their approval it moved on to the next round. This way the mission/vision grew richer step by step.

> It worked in terms of content (the mission/vision was iteratively enriched) and it served as a warm-up. Everyone got used to how AI and Dembrane worked before the "real" session began.

---

**The difference from "sequential":** AI builds on within the same document. The most recent feedback takes the lead. Group 2 refines what group 1 started, group 3 refines what group 2 delivered. The result gets richer each time.

**When this fits:** When you want to iteratively build a document with input from multiple groups. When speed matters: the processed result is ready within a minute, the next group can respond immediately. When you want people to see what happens with their input.

**Watch out:** This format demands the most from your AI tool. The prompt contains conditional logic (Path A: first draft, Path B: revised version). Test before the session whether your AI tool handles both paths well. You don't want to discover it doesn't work with 25 people around you.

**The prompt:** A prompt with built-in logic: for a first discussion it generates a draft, for feedback it generates a revised version. Paste the prompt below into the AI tool of your choice; it helps you create a prompt for your session.

<ProbeerStory experiment="in-the-session-iterative"></ProbeerStory>

---

## What do you need?

Regardless of the format, this is the basic equipment:

- [ ] **Transcription per table:** phone with a transcription app (Dembrane, or similar). On do-not-disturb, plugged in.
- [ ] **Screen or projector:** to show AI output to the group (for "sequential" and "iterative")
- [ ] **Table host or chairperson:** someone who guides the conversation and introduces the AI output
- [ ] **Prepared prompts:** tested before the session. The same prompt per table makes results comparable.
- [ ] **Run sheet with recording moments:** when do you start recording, when do you stop, what does AI do in between?
- [ ] **Post-its, markers, timeline** (optional): physical elements help move from abstract to concrete

**Tip:** test your prompt the day before the session on an earlier transcript. Then you know what to expect.

---

## Which format fits you?

| You want to... | Choose | Why |
|----------------|--------|-----|
| Let groups have their own conversation, compare afterward | **Parallel** | No steering, maximum richness per table |
| Have groups respond to each other's work | **Sequential** | Build on via the chairperson, keep separate analyses |
| Iteratively enrich a document with multiple groups | **Iterative** | Live speed, each group sees the result of the previous one |
| Help people get used to AI as a way of working | **Iterative** (as warm-up) | Makes visible how AI works before the real session begins |

You can combine formats. The transformation plan example combined parallel (3 theme tables) with sequential (rotation). The Amsterdam session started with iterative as a warm-up and then switched to parallel.

---

## And then? The loop

The session is over. You have analyses, syntheses, maybe draft documents. What do you do with them?

**Reflect back to the group:** Let people see their own words. "This is what you said. Do you recognize this?" The recognition test: if participants think "yes, that's what we said," you've succeeded. If it sounds like a consultant wrote it, you haven't.

**Toward the next session:** Today's output can become the input for next time. "Last time the same thing came up at every table. That's where we start today." This way each session becomes a building block, not an isolated conversation.

**From analysis to intervention:** The synthesis tells you not just what was said, but where the connections are. People who share the same struggle without knowing it about each other. Those are the hooks you can use to connect people: in the next session, in informal encounters, or between groups that weren't sitting together.

---

## Tensions

**Steering versus letting go**
When you show AI output between rounds, you steer the next group. They respond to what's on screen, not to what they would have come up with on their own. The tension: do you lose unbiased input by showing too much?

*My approach:* With parallel, this doesn't come into play: each table has an independent conversation, and the synthesis happens afterward, when all groups have already spoken. There's no moment where AI output can steer the conversation. With sequential and iterative, it's a deliberate choice: you want to build on, not start over. But always begin with "is this picture right?" before moving on. That's not a formality; it's the feedback loop back to the group that just spoke.

**Technology versus attention**
Phone on the table, recording on, AI in between. The risk: the technology distracts from the conversation. The tension: how do you keep the focus on the people?

*My approach:* The table host is the key. They guide the conversation, not the technology. "Forget the phone, it's listening along. Tell us."

---

## Safe starting points

- [ ] Same prompt per table (comparability)?
- [ ] Prompts tested before the session?
- [ ] Run sheet with recording moments clear?
- [ ] Table host briefed on their role?
- [ ] Screen available for reflecting back?
- [ ] Recognition test planned: "is this picture right?"

---

## Try this yourself

*You need an upcoming session with multiple groups.*

1. **Choose your format.** Parallel if you want to compare. Sequential if groups need to build on each other. Iterative if you want to build a document live.

2. **Design your questions first.** Before you think about AI: which puzzle pieces do you need? In what order? [Prompt the people first](../phase-2/prompt-the-people-first.md) helps with this.

3. **Prepare your prompts.** Use the meta-prompt of your chosen format; it generates everything you need. Test on an earlier transcript. Check whether the output is usable: do you recognize what was said?

4. **Prepare the feedback loop.** For parallel: plan a moment at the end to share the synthesis. For sequential: brief the chairperson on how to introduce the AI output. For iterative: make sure the screen is ready.

5. **Afterward: capture what worked.** Not just the content, but also the process. What would you do differently next time?

---

## Related techniques

- How to design questions that yield good input: [Prompt the people first](../phase-2/prompt-the-people-first.md) describes how to work backward from the session goal to the right questions and puzzle pieces
- The core principle (first analyze separately, then synthesize): [Phase 3 introduction](../../phase-3-scale.md)
- From a single conversation to a plan: [Conversation to plan](../phase-2/conversation-to-plan.md)
- Tracking shifts over longer processes (multiple sessions over weeks or months): [Patterns over time](patterns-over-time.md)
- Live reflection during the conversation itself: [Live reflection with AI](../phase-2/live-reflection-with-ai.md)

---

← [Previous: Patterns over time](patterns-over-time.md) | [Back to Phase 3: Scale](../../phase-3-scale.md) | [Next: Seeing ownership grow](ownership-growth.md) →

---

*"The facilitators had already cut the puzzle into pieces. My role was to use AI to harvest what they had gathered."*
