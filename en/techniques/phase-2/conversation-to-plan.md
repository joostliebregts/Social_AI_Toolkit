# From conversation to implementation plan

> *Generate live output that participants can assess on the spot.*

**Phase:** [Phase 2: Deepening](../../phase-2-deepening.md)
**Builds on:** [Source document style cloning](../phase-1/source-document-style.md), now as live documentation during sessions

---

## When is this relevant?

**Situation:** You're facilitating a strategic session. Participants share their perspectives. Normally you'd spend a day processing afterwards: sorting sticky notes, writing a draft, collecting feedback.

**The tendency:** To accept the process as a given. Set aside a day after the session to process everything, because "that's how we've always done it." The assumption that quality needs distance; that you need to sleep on it. And probably also: that doubt about whether AI can do it as well as you would yourself.

**The principle:** AI can generate draft output during the session itself. People see their words reflected back immediately, structured in the form the organization needs. The feedback loop shrinks from days to minutes.

**The question:** What if people could see their input come back as a draft document right away?

**The difference with [Live reflection](live-reflection-with-ai.md):** There, you use AI for reflection questions *during* the conversation, to create turns. Here, you use AI to generate *documentation* from the conversation. Both can happen in the same session: the echo button for turns, and this technique for output.

**This is a semi-live method.** Not real-time like the echo button (directly in the conversation), but between blocks: during breaks or sub-sessions. You need about 1-2 minutes to launch a prompt and review the output before showing it to the group.

---

## The story: 1 day to 1 minute

We applied this principle for the transformation plan of the mental healthcare (GGZ, the Dutch mental health system) network in Centraal Gelderland. It worked, which is why we then also applied it in Amsterdam.

An example from Gelderland. Thirty participants give input for a transformation plan for the mental healthcare network. The old process:

1. Live session: people work in small groups
2. Sticky notes on walls
3. **One day of processing**: facilitators cluster and write a draft
4. Review by a 10-person team
5. Final integration

The question: what if AI could generate that draft document directly from the conversation?

The answer became a live workflow:
- Transcription runs alongside the (original) facilitated session where sticky notes are used.
- During short breaks, AI generates draft sections
- People see their words reflected back, structured, and recognize them immediately

From a day's work to minutes of processing. Without replacing the value of sticky notes or facilitation.

---

## How it works

### The basic method

**BEFORE THE SESSION:**
Prepare prompts that match the document type and style needed.

**DURING:**
1. Transcription runs alongside
2. After each phase: transcript segment goes to AI
3. AI generates a draft section in the right form
4. Show to the group for validation
5. Integrate feedback

**AFTER:**
Consolidate all sections into the final document.

### The feedback cycle

In practice, this looks like:

1. **Group 1** gives input
2. AI turns it into **draft v1**
3. **Group 1** responds to v1, feedback is processed into **draft v2**
4. **Group 2** receives v2, responds and adds to it
5. AI processes into **draft v3**
6. **Group 3** receives v3, gives final input
7. The document has received input and feedback from everyone: everyone has been able to contribute

This is the "rolling" variant: each group builds on the improved version from the previous group. AI maintains the thread. This is a preview: in [Phase 3](../../phase-3-scale.md), more variants are covered, such as merging parallel breakouts into a single synthesis.

### The prompt

This is the actual prompt we used during the transformation plan sessions for the mental healthcare network. It was designed for Dembrane but works with any tool that can process transcripts.

What makes it special: you use the same prompt repeatedly. Each time with more input. AI determines what's needed on its own.

**How it works:**

1. **One prompt, two modes.** If you only provide the transcript of the discussion, AI generates a first draft sub-plan. If you also provide the feedback transcript, AI generates a revised version. Same prompt, different result.

2. **Reflection on first use.** For the first draft, the prompt also generates a brief reflection: a narrative summary of the key insights from the discussion. That's what you show the group: "this is what AI heard."

3. **Feedback processed transparently.** In revised versions, AI marks what has changed and why. The "Processing of Feedback" section shows exactly how the input from the previous group was incorporated. That's what creates ownership: people see that their feedback matters.

4. **Core values as thread.** The prompt identifies values from the discussion and weaves them throughout the entire document. This gives the plan not just structure, but also soul.

```
Group 1 discusses topic  ──► prompt ──► echo + draft v1
                                        ↓ show to group 1
G1 feedback on v1   ──► prompt ──► draft v2 (revised)
                                        ↓ show to next group
G2 feedback on v2   ──► prompt ──► draft v3 (revised)
                                        ↓ show to next group
G3 feedback on v3   ──► prompt ──► draft v4 (final)
```

Same prompt every time. More input each time. The document grows along.

**View the full prompt (this is very long)**

```prompt
**Role:** You are an analytical editor and strategic developer. You
first distill the core insights from the provided discussion(s). Then
you fully synthesize these into a comprehensive, detailed,
future-oriented, and transparent draft (or revised draft) sub-plan for
the Mental Health Network [region], with the identified core values
woven throughout the text as a common thread.

**Context:**
- **Theme:** The central theme of this sub-plan, to be identified from the input.
- **Input - Base discussion(s):** One or more transcript(s) of the initial working session(s) on the theme. (Note: transcripts may be in another language).
- **Input - Feedback (Optional):** One or more transcript(s) of feedback session(s) on a previous version of this sub-plan. (Note: transcripts may be in another language).

**Target Output (Two-part, Part 1 is conditional):**
1. **Part 1 - Echo of the Base Discussion(s):** A concise, primarily narrative account of the core insights from the base discussion(s). (If there are multiple base transcripts, create an echo per transcript; if there is one, a general echo of that session). Only generate if there is no Feedback Transcript, or if explicitly requested.
2. **Part 2 - Draft (or Revised Draft) Sub-plan:** A complete and richly developed sub-plan. It reflects the "character of [region]", underlying values, and nuances. Serves as a learning tool, emphasizes collaboration, builds on existing knowledge, and contains transparency elements. Core values are consistently applied and connected where possible.

**Required Style/Approach (for Part 2):**
- **Important Language Instruction:** The input transcripts may (unintentionally) be in another language. All generated output must without exception be in correct, fluent, and professional language matching the organization's standards.
- **Language:** Formal, professional.
- **Tone:** Collaborative, future-oriented, reflective, action-oriented, pragmatic, solution-oriented, and open. Reflects [region]'s context, central values, and learning character. Fluent, detailed and convincing narrative, with attention to recognizability of the input.
- **Perspective:** From collaborating parties (resident, relative, professional).
- **Terminology:** Correct jargon (as used in the sector) if explicitly mentioned.
- **Critical Constraint:** Base output strictly on explicit information in transcripts. Do not supplement, interpret, or fabricate.

**Instructions:**

PART 1: ECHO OF THE BASE DISCUSSION(S)
(Only generate if there is no Feedback Transcript, or if explicitly requested)

1. Analyze Input for Part 1: Determine the number of provided Base Discussion transcripts.
2. Generate Echo(s):
   - If MULTIPLE transcripts: Analyze each separately. Formulate per transcript a short, narrative paragraph (approximately 3-5 sentences) summarizing core insights/ideas/tenor. Present under respective headings.
   - If ONE transcript: Formulate one short, narrative paragraph (approximately 3-5 sentences) summarizing the core insights of the entire session.

PART 2: DRAFT (OR REVISED DRAFT) SUB-PLAN

3. Identify Main Theme: Analyze the Base Discussion(s) and determine the central theme. Use the theme consistently.
4. Analyze Input Type: Check whether Feedback transcript(s) have been provided alongside the Base Discussion(s).
5. Processing Strategy:
   - IF ONLY BASE DISCUSSION(S): Go directly to step 6. Generate a first draft that is as rich and complete as possible.
   - IF ALSO FEEDBACK TRANSCRIPT(S):
     a. Analyze the feedback points (criticism, suggestions, clarifications, new insights).
     b. Generate a REVISED version. Combine insights from the Base Discussion(s) with thorough processing of feedback. Refer explicitly in the text to how feedback has been processed (e.g., 'Based on the feedback, X has been reformulated as follows').
6. Extract Core Information: Identify core values; look for introduction, main objective, current status, intervention, target group, effects, involved partners, and input for transparency.
7. Synthesize Conflicts: For contradictory ideas, try synthesis through underlying values. Otherwise, identify as a discussion point.
8. Structure Sub-plan:
   - **Creation of this Draft:** Describe the creation process. For first draft: synthesized from base discussion(s). For revised version: feedback processed, name the sources.
   - **Introduction ("Why a [Theme] in [region]?"):** Comprehensive, context-rich introduction. Sketch the problem, relevance, necessity of an integrated approach.
   - **Main Objective:** The central objective. Refer to core values.
   - **Core Values:** List them, with a brief explanatory sentence per value.
   - **Reflection on Guiding Principles:** Short reflection paragraph (2-3 sentences) on how core values were guiding.
   - **Current Status ("Where do we stand?"):** Comprehensive description of current situation, bottlenecks, positive initiatives.
   - **Development [Theme]:** Introductory sentence, followed by:
     - Intervention ("How are we going to do it?"): Comprehensive and concrete, with actions and elements.
     - Target Group ("For whom?"): If discussed.
     - Intended Effects ("What does it deliver?"): KPIs if mentioned, with explanation per effect.
     - Involved Partners ("Who?"): Crucial partners, how collaboration supports core values.
   - **(Optional) Learning Capacity:** Contribution to a learning system.
9. General Quality: Logical flow, coherence. Text should breathe [region]'s nuances, urgency, shared vision and learning character. Core values as common thread.
10. Complete Output: Generate Part 1 (if applicable) and Part 2 in one go. Develop all sections fully.
11. Closing Sections:
   - **Accountability of Feedback Processing** (ONLY for revised version): How feedback led to specific changes.
   - **Notes, Missing Information, and Considered Alternatives:** Including 'Considered Alternatives and Possible Blind Spots' (1-2 alternatives, 1-2 blind spots).
   - **A Living Document:** Invitation to feedback, importance of shared ownership.

**Input:**
- Base discussion(s): [transcript(s)]
- Feedback (optional): [transcript(s)]

**Output Format:**

### Revised Draft Sub-plan [region]: [The Identified Theme] (Draft 2.0)

#### Creation of this Draft
(Updated text reflecting that this is a revised version after feedback, etc.)

#### Introduction ("Why [The Identified Theme] in [region]?")
(Revised text)

#### Main Objective for [The Identified Theme]
(Revised text)

#### Core Values for [The Identified Theme]
(Revised text, if applicable)
- [Core Value 1]: [Revised explanation]
(etc.)

#### Reflection on Guiding Principles
(Revised text, if applicable)

#### Current Status in [region] ("What is the current situation regarding [The Identified Theme]?")
(Revised text)

#### Development [The Identified Theme]
(Revised introductory sentence)

Intervention ("How are we going to approach it?")
(Revised text)

Target Group ("For whom is [The Identified Theme] intended?")
(Revised text)

Intended Effects ("What does it deliver?")
(Revised text)

Involved Partners ("Who participates?")
(Revised text)

(Optional) Learning Capacity ("How do we learn and improve?")
(Revised text)

---

#### Notes, Missing Information, and Considered Alternatives
(Revised text)

Considered Alternatives and Possible Blind Spots
(Revised text)

#### A Living Document
(Revised text, possibly reflecting on this new iteration)

---

### Processing of Feedback (Changes compared to Previous Draft)
- Based on feedback about [topic A], [change X] was implemented in section [Y] because [reason].
- The suggestion to add [topic B] has been processed in [section Z].
- The concern about [topic C] has been addressed through [change W].
(3-5 bullet points)
```

**Why this structure works:**
- **"Base output strictly on explicit information"** prevents AI from making things up. You get honest output with clear gaps that you can fill in.
- **"Refer explicitly to how feedback was processed"** transparency about what was done with the input. People see that their contribution matters.
- **"Core values as common thread"** the document gets coherence from the values the group itself identified.
- **The two-part structure (echo + sub-plan)** first showing what AI heard, then the document. That sequence gives the group grip: first recognition, then structure.
- **Style in the prompt.** The prompt contains style guidelines so AI doesn't write generically, but in the language and structure the organization expects. (See [Source document style cloning](../phase-1/source-document-style.md) for how to define that style.)

**Adapting this prompt for your context.** The themes, terminology, and document structure above are specific to the mental healthcare network. You can adapt the prompt by:
- Changing the **Role** to your document type (project plan, policy brief, strategic framework)
- Replacing the **Theme list** with the topics relevant to your session
- Adjusting the **Style** to match the language and tone of your organization
- Modeling the **Structure** (step 8) after the format your organization expects

A quick approach: give AI this prompt together with an example of an existing document from your organization, and ask: "Adapt this prompt so the output matches this format."

---

## The role division

This requires two people:

| | Facilitator | Co-facilitator |
|---|------------|----------------|
| **Before the session** | Session design, prepare questions | Set up technology, arrange recording |
| **During** | Lead conversation, show AI output, guide validation | Monitor transcription, select segments, launch prompts |
| **After** | Review output with group | Processing and consolidation |

Never: facilitator behind a laptop while the group waits.

---

## Tensions

**Presenting AI output as truth**
"This is what you decided" sounds definitive, but it's an AI interpretation.

*My approach:* I always present it as a draft. "This is what AI made from your conversation. Does it hold up?"

**Too few validation moments**
End of session: "Look, your document!" But nobody recognizes themselves because there were no intermediate checks.

*My approach:* Validate along the way. After each phase, check whether it holds up.

**Forgetting style**
AI writes generically. The document doesn't match the organization's standards.

*My approach:* Style guidelines in every prompt. [See [Source document style cloning](../phase-1/source-document-style.md)]

**Losing the soul**
The document is technically correct but misses the energy of the conversation.

*My approach:* Keep the quotes. Their words, their phrasings. That keeps it alive.

---

## Safety checklist

- [ ] Style guidelines included in prompts?
- [ ] Validated with the group along the way?
- [ ] Quotes and original language preserved?
- [ ] Framed as "draft for validation", not as decision?
- [ ] Contradictions and missing information flagged?

---

## Philosophical deepening

### Direct feedback stimulates ownership

There's a reason this works. When people see their words reflected back immediately, the connection between speaking and result is still fresh.

"I just said that. And now it's right here."

This is different from a report a week later. The speed isn't for efficiency; the speed is for ownership.

### The ritual changes, the intent stays

The old ritual: sticky notes, clustering, a day's work, draft, review, final.
The new ritual: speak, immediate output, validate, refine.

The form is different. But the intent (making people owners of a plan) stays the same. In fact: because of the speed, the ownership is more direct.

---

## Related techniques

- The style approach (how do you make sure output comes in the right format?) is covered in [Source document style cloning](../phase-1/source-document-style.md)
- Why preserving their exact words matters so much, read in [Language as ownership](../phase-1/preserving-language.md)
- For real-time interventions during the session (not just documentation, but also reflection), see [Live reflection with AI](live-reflection-with-ai.md)

---

← [Previous: Live reflection](live-reflection-with-ai.md) | [Back to Phase 2](../../phase-2-deepening.md) | [Next: Intuition in writing →](intuition-in-writing.md)

---

*"From a day's work to minutes of processing: not for efficiency, but for ownership."*
