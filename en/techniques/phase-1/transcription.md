# Transcription as foundation

> *Everything starts with text. Transcription makes the fleeting tangible.*

**Phase:** [Phase 1: Start](../../phase-1-start.md)
**This is the foundation:** without text, no deepening

---

## Why this is the foundation

You know the moment. A conversation just ended. You know something important was said, but you can't reconstruct it exactly anymore.

That goes for a one-on-one conversation. But also for team meetings and workshops. You had your notes, your shared memories, your summary after the fact.

But something has changed.

We can now make transcripts. Fast, cheap, good enough. Everything that was said, captured as text.

And that raises a question: what can you actually do with that, in a social setting?

That's what this field guide is about. Transcription as raw material. Foundation for all kinds of things: capturing collective wisdom, revealing patterns, checking your own intuition, growing as a facilitator by looking back at what you could have done differently.

**That's why this page comes first.** Not because transcription is the most spectacular technique, but because everything that follows starts with it.

---

## Where it all begins

In [Phase 1](../../phase-1-start.md) you already read about Maarten and the parent-teacher evening about smartphone-free parenting. The bike helmet moment: AI found the quote that hit the exact core.

Here we go deeper into what made that possible, and how you can apply it yourself.

---

## What makes transcription different now?

Until recently, transcription was expensive, slow, or inaccurate. You had to choose: pay for a professional note-taker, spend hours typing it out yourself, or live with mediocre automatic transcription.

That's over.

**The threshold is now almost zero:**
- Cost: 0-1 euros for an hour of audio
- Time: 1-2 minutes for an hour of conversation (with newer transcription models)
- Quality: 80%+ accuracy, including for Dutch. (I haven't yet experienced it not being good enough for my purposes)
- Privacy: Local tools exist: nothing has to go to the cloud

This changes the fundamental question. No longer: "Is it worth transcribing this?" But: "What do I want to do with this text?"

---

## From recording to transcript: the workflow

### Step 1: Record with consent

This sounds obvious, but it starts here. Explicitly ask permission at the beginning of every session.

A simple phrasing:

> "I'm recording this conversation so we can look back at what was said. The audio recording stays with me and the transcript will only be used for [purpose]. Is that okay for everyone?"

Watch for non-verbal signals. Not everyone speaks up when they're uncomfortable.

### Step 2: Transcribe

Choose a tool that fits your situation:

| Tool                         | When to choose                                                                                  |
| ---------------------------- | ----------------------------------------------------------------------------------------------- |
| **MacWhisper**               | Privacy matters, you want to transcribe locally or dictate.                                     |
| **Dembrane**                 | Real-time transcription during the session, direct synthesis possible                           |
| **Notion AI**                | You already work in Notion, want everything in one place, works in both English and Dutch       |
| **Google Meet transcription** | You already work in the Google ecosystem, basic is enough (note: no Dutch transcription yet)    |
*See the [tools page](../../tools.md) for more details about these and other tools.*

For most facilitators (with a Mac), MacWhisper is a good starting point: it works locally (privacy), has a free version that already does a lot, the pro version is a one-time purchase, delivers good Dutch transcriptions, and has built-in dictation.

### Step 3: Check and clean up

Transcriptions aren't perfect. Always check for:
- **Names:** AI often guesses wrong.
- **Jargon:** Technical terms are sometimes transcribed incorrectly.
- **Crucial passages:** Check quotes you want to use for accuracy.

You don't need to correct the entire transcript. Focus on what you're going to use. And as soon as you start working with the transcript, give the AI the transcript with correction context included. For example:

```prompt
This transcript contains technical terms and names that may have been transcribed incorrectly: 'POH-GGZ' (not 'P.O. Achates'), 'Rianne' (not 'Rijanne'), 'GALA' (not 'gala').
```
### Step 4: Use with intention

This is where the real work begins. The question isn't "what can I do with this transcript?" but "what do I want to achieve?"

- Want to reflect the group's own words back to them? → [Preserving language](preserving-language.md)
- Want to make patterns visible? → [Intuition in writing](../phase-2/intuition-in-writing.md) (Phase 2)
- Want action items? → See the Key Decisions prompt below
- Not sure yet? → Archive the transcript, come back to it later

---

## Four ways to use transcription

This is the first page in this field guide where we actually start working with AI. Until now it was about why and how. Now it gets concrete: what do you actually do with a transcript?

There are countless possibilities. But in my work, four patterns keep coming back:

### 1. Capturing what you couldn't hear

This is the most basic application, and that's why it comes first. You can't catch everything when you're facilitating. You miss subtleties while thinking about the next question. You hear a striking remark, but before you can write it down, the next speaker is already going.

Transcription is your safety net. Not as a replacement for attention, but as backup for when attention isn't enough.

**Prompt for finding what you missed:**

The prompt below is more extensive than you might expect for "capturing what you couldn't hear." That's deliberate. This is the actual prompt that Maarten and I used after the parent-teacher evening about smartphone-free parenting. It shows how you go from transcript to usable insights in one step: not just what was said, but also how you can use it in follow-up conversations.

```prompt
**Context & Role:**
You act as a systemic strategist and community builder supporting [The Initiator]. He has set up a local working group at his children's primary school with the goal: delaying smartphone use among children and changing the norm (aiming for >25% smartphone-free in the class to reduce peer pressure).

You have access to this text:
1. The transcript of the first online parent meeting (~14 participants).

**Assignment:**
Analyze the transcripts and create a strategic overview ("The Giant Map") and a practical conversation guide ("The Conversation Fan"). The goal is not to convince people with facts, but to connect based on shared values and concerns.

**Constraints & Style:**
- **Privacy:** Do NOT use real names. Replace names with [The Initiator], [Facilitator], or [Parent Group X].
- **Language:** Use the participants' *verbatim words* wherever possible for maximum recognizability.
- **Tone:** Empathetic, non-judgmental, constructive. Focus on the desire to be a good parent, not on guilt about personal screen behavior.
- **Form:** Provide concrete hooks and insights, not literal scripts that [The Initiator] has to read aloud. He wants to protect his own authenticity.

**The output (in 3 parts):**

**Part 1: The two heatmaps (The Insight)**
Map the population in two ways, organized by school phase (Kindergarten/Lower Primary vs. Middle Primary vs. Upper Primary/First Year Secondary).

**A. The Emotional Landscape (The Concerns)**
* What specific fears, doubts, or comfort zones do parents experience in this phase?
* Look beyond the complaint ("my kid wants to game") to the underlying value ("I want my child to fit in socially").

**B. The Action Readiness (The Energy)**
* Where is the energy? Who feels urgency (e.g., "it's five to midnight") and who is in the 'safe harbor'?
* Identify the 'hooks' for urgency per group: what makes a kindergarten parent want to act *now*, while the problem still seems far away?

**Part 2: The internal struggle (The Connection)**
Analyze the tension between "what we do" (own phone use, convenience) and "what we want for our child" (free play, safety).

* Do NOT frame this as hypocrisy or addiction, but as a challenge in modern parenting.
* Return 3 to 5 core themes where parents wrestle with their own role model behavior.
* Use quotes or paraphrases that show: "You're not alone, we find this difficult too."

**Part 3: The conversation fan (The Ammunition)**
Translate the above insights into concrete 'hooks' that [The Initiator] can use in informal conversations (e.g., at the schoolyard, on the sidelines).

* Per target group (Lower Primary, Middle Primary, Upper Primary) provide 2 or 3 openings or observations.
* Focus on finding the *common ground*.
* Format: *"When you talk to a parent from group [X], [THEME] is a strong entry point. You could reference [IDEA/QUOTE]."*
```

**Why this structure works:**
- "Role" steers perspective: "systemic strategist and community builder" directs AI toward finding connection, not delivering critique
- "Constraints" protect authenticity: using verbatim words, no real names, empathetic tone
- "Two heatmaps" force AI to analyze both the emotions (concerns) and the energy (readiness to act)
- "Conversation fan" translates insights into something usable: concrete hooks for real conversations

### 2. Language as ownership

If the first pattern is about what you missed, this one is about what you did hear but risk losing: the exact words.

There's a crucial difference between "communication problems" and "you're talking to a wall." The first is an interpretation. The second is what someone actually said.

When people see their own words reflected back, they experience that their contribution truly mattered. They feel heard: not summarized, not interpreted, but heard. And that opens the door to ownership. The feeling that this is theirs too, not just the facilitator's or the organization's.

A participant who reads "we need to stop having meetings about meetings" thinks: *yes, I said that*. The same participant who reads "inefficient meeting structure" thinks: *that's what a consultant made of it*.

Transcription helps preserve the original language. That's the raw material for everything that follows.

**The full technique:** For the complete technique and prompts on preserving language, see [Preserving language](preserving-language.md).

### 3. Extracting structure

The first two patterns are about content: what was said, in which words. This third pattern is more practical: what was decided?

Sometimes you don't want enrichment or deepening, but simply an overview. What was decided? Who does what? Which questions remained open?

This is perhaps the most obvious use of transcription. Many people start here: automating administration so you have space for other work. And that's fine. But in this field guide it's in third place, because the first two patterns show what else is possible.

**AI helps write the prompt:**

These days you can also have AI write the prompt for you. Give it the transcript and your wishes, and ask for a fitting prompt. After a meeting I asked AI:

```prompt
Now that the meeting is over, what's the right prompt to get the best-fitting summary and minutes, for both attendees and absentees (Anna and Lisa)?
```

AI generated a prompt with structure (in brief, recap, decisions, action items, for absentees) and the instruction to preserve the language of participants. This is an interesting pattern: AI helps create the prompt based on context.

**Key Decisions Capture:**

```prompt
**Role**: You are a precise note-taker who records explicitly made decisions
without interpretation.

**Context**: Extract only the concrete decisions that were explicitly
made during this session.

**Critical Constraints**:
- Only explicitly made decisions - no implicit or assumed
  decisions
- Quote verbatim who decided what
- When in doubt: "Yet to be confirmed"

**Instructions**:
1. Scan transcript for explicit decision-making
   ("we decided", "agreed", etc.)
2. Note the decision, who made it, and any conditions
3. Group by type of decision (process, content, follow-up steps)

**Output Format**:
### Key Decisions from this Session

#### Process Decisions
- [Decision + who + when]

#### Content Decisions
- [Decision + who + when]

#### Follow-up Agreements
- [Agreement + responsible person + deadline]
```

**Why this structure works:**
- "precise note-taker" keeps AI focused on what was literally decided
- "Constraints" prevent implicit conclusions: only explicitly made decisions, when in doubt "yet to be confirmed"
- "Output format" is surprisingly effective: AI follows the structure (process, content, follow-up) quite precisely

### 4. Dictation: capturing your own stream of thought

The first three patterns are about conversations with others. This fourth pattern is different: it's about your own thoughts.

Transcription isn't just about conversations with others. It's also about capturing your own thoughts.

With dictation you speak your thoughts and within a second they're there as text. This is much faster than typing; it changes how you work with AI.

**When this is valuable:**
- When iterating with AI: you dictate your feedback, paste it into the chat
- When processing sessions: you speak your observations while they're fresh
- When preparing: thinking out loud, structuring later

A lot of my work with AI is now: dictate → AI → dictate → AI. The threshold for capturing thoughts drops to almost zero.

#### MacWhisper: the tool that makes this possible

MacWhisper deserves extra attention because it's a fundamentally different approach; and because it supports dictation.

**How it works:**
You download an AI model to your Mac. The transcription happens entirely locally: no audio goes to servers, no text goes to the cloud.

**Speed:**
With newer models (like Parakeet 3), an hour of audio can be transcribed in 1-2 minutes. The old assumption that local is slower is becoming less and less true.

**Dictation:**
MacWhisper also has a dictation function. You speak, stop, and within a second everything is there as text. This is how I do most of my AI interactions.

**When to choose:**
- Privacy-sensitive conversations
- You also want to dictate
- You work on a Mac

**Windows alternative:** For Windows users there's [Handy](https://github.com/cjpais/handy), an open-source tool with similar dictation functionality.

#### Hardware: from fine to good

Dictation works fine with your laptop's built-in microphone. But if you do it regularly, better hardware can make a difference.

**What I use:**

- **[DJI Mic Mini](https://www.dji.com/nl/mic-mini)**: Wireless lavalier mic. My favorite. Works both for dictation and for recording conversations with two people (the set has two transmitters). Plug and play via USB-C.

- **[Rode VideoMicro](https://rode.com/en-us/products/videomicro)**: Small shotgun mic that I have as a backup on top of my monitor. Simple, no batteries needed, good quality for the price.

This is not a requirement. Just start with your built-in microphone. But if you notice transcription quality is lacking, or you work in noisy environments, hardware can help.

---

## Building on transcription

Above you read four ways to use transcription. But there are techniques that go further: that build on transcription as a foundation. If you work through the field guide chronologically, you'll encounter them naturally:

**Digging together into what's in there**
A transcript contains more than you could take in during the moment. Imagine: you go searching together with AI for structure, hooks for connection, striking quotes.
→ *[What else was in there](../phase-2/what-else-was-in-there.md)* (Phase 2)

**Seeing patterns across multiple conversations**
One transcript is a snapshot. Five transcripts over three months show development: how language shifts, which themes recur, where breakthroughs happen or don't.
→ *[Patterns over time](../phase-3/patterns-over-time.md)* (Phase 3)

**Finding unexpected connections**
Two people who share the same struggle without knowing it about each other. Two parents (of different children) both turned out to be struggling with playdates that revolve entirely around gaming. AI distilled the hook: "Are you also standing alone in that Minecraft conversation?" Not a summary. A bridge.
→ *[Finding hooks](../phase-3/finding-hooks.md)* (Phase 3)

---

## Tensions

With every technique in this field guide I describe the tensions I encounter. Not as pitfalls to avoid, but as choices you make again and again. What works depends on the situation.

**Capturing is not yet using**
The threshold for transcription is so low that it almost feels obvious to record and transcribe everything. The transcript is there. That feels like progress. But without a next step, it gathers dust.

*My approach:* Often I already have an idea of what I want to do with it while transcribing. Which prompt am I going to use on it? What do I want to get out of it? Sometimes the answer is: I don't know yet, this is archiving. That's fine, but then I call it that. And when I do have a direction, I try to quickly do something small: mark five quotes, have AI look for a pattern. Small actions keep transcripts alive.

**Polishing versus authenticity**
The urge to make language "more professional." This is so important that it has its own page: [Preserving language](preserving-language.md).

**Convenience versus privacy**
The tools are so easy. Upload, click, done. But not every conversation belongs in the cloud.

*My approach:* I make a conscious choice per conversation. Internal or sensitive? Then local (MacWhisper). External or public? Then cloud works. When in doubt, I choose local. It also helps to be clear for yourself about what you want to do with the transcript, so you can articulate it well to others when asking permission.

---

## Safety checklist

With every technique in this field guide I give a checklist of things to check before you begin. Not as bureaucracy, but as a quick scan: have I thought of the important things?

*See also: [Safe practices with AI](../../safe-practices.md)*

Every time you use a transcript for AI analysis, check:

- [ ] **Strictly based on transcript?** Have you added the constraint "base yourself strictly on what's written"?
- [ ] **No fabrications?** Does the prompt ask for "when in doubt: yet to be confirmed"?
- [ ] **Language preserved?** Is the instruction to quote verbatim explicit?
- [ ] **Privacy checked?** Is this transcript suitable for the tool you're using?
- [ ] **Purpose clear?** Do you know what you want to achieve before you start?

---

## Philosophical deepening

### The principle: strictly based on transcript

There's a fundamental tension in working with AI and conversations. AI can find patterns, make connections, create interpretations. But not every interpretation is grounded in what was actually said.

The constraint "strictly based on transcript: no fabrications" is not a limitation. It's a protection.

**What this means in practice:**

```
❌ "The group felt frustration about management"
✅ "Three people used words like 'wall', 'not heard', 'pointless'"

❌ "There is consensus about the direction"
✅ "Five of the seven speakers mentioned 'start locally' as the first step"

❌ "The atmosphere was negative"
✅ "The words 'not', 'can't', 'impossible' appeared 23 times"
```

AI observes what's written. Not what people "actually" meant, not what they "felt," not what they "should" think.

This is a foundation. If you don't trust what's written, it's hard to build on it. Not impossible, but you have to constantly check.

### Why this matters

When you share a synthesis and someone says: "But I didn't say that," the trust is gone. Not just in the synthesis, but in the entire process.

Conversely: when you share a synthesis and people say: "Yes, this is us," ownership grows. Not because the synthesis is perfect, but because it's recognizable.

The power of transcription doesn't lie in the technology. That's almost free now. The power lies in what you do with it: giving people their own words back.

---

## Related techniques

- [Preserving language](preserving-language.md): How to ensure participants' words remain intact in AI output
- [Source document style](source-document-style.md): When your transcript needs to become a formal document that decision-makers accept
- [Live reflection with AI](../phase-2/live-reflection-with-ai.md): Using live transcription for direct interventions

---

← [Back to Phase 1: Start](../../phase-1-start.md) | [Next: Preserving language →](preserving-language.md)

---

*"The power of transcription doesn't lie in the technology. The power lies in what you do with it: giving people their own words back."*
