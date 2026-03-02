# Cloning source document style

> *"We know this document was approved by the health insurer. What I actually want is for the new documents to come in the same writing style."*

**Phase:** [Phase 1: Start](../../phase-1-start.md)
**Builds on:** [Transcription as foundation](transcription.md) and [Language as ownership](preserving-language.md), now with the style of an existing document

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

```prompt
Analyze this document and identify:

1. Structure: Which sections recur? In what order?
2. Tone: Formal/informal? Collaborative/directive?
3. Terminology: Which technical jargon is used consistently?
4. Formatting: How are lists, tables, figures used?

Provide concrete examples from the document per category.
```

**Example: analysis of the transformation plan**

This is what the analysis yielded for the mental healthcare transformation plan:

```
Structure per Sub-plan:
Each sub-plan follows a fixed structure:
- Introduction
- Main objective
- Current status
- Intervention
- Target group
- Effects (numbered list)
- Partners involved (bullet points)
- Phasing
- Agreements (SMART table)
- Investment

Writing style:
- Formal, business-like Dutch
- Collaborative: frequent use of "we", "together", "jointly"
- Action-oriented, pragmatic, solution-focused

Terminology:
- IZA, GALA, MGN, POH-GGZ, positive health
- Exploratory conversation, consultation table, social map
- Cross-domain, recovery-oriented
```

### 2. Encode the style in your prompt

Include the style characteristics literally in every prompt that needs to generate output.

**Example: style guidelines embedded**

```prompt
Write in the following style:
- Language: Formal, business-like
- Tone: Collaborative ("we", "together"), action-oriented, pragmatic
- Perspective: Collaborating parties, taking into account
  "resident", "loved one", "professional"
- Terminology: [insert domain-specific terms from source document]
- Structure: Clear sentences, bullet points where needed
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

```prompt
**Prompt for Dembrane (Interim Vision Reflection - Universal)**

**Role:** You are an AI assistant helping with live documentation of a transformation plan session. Your task now is to summarize the core of the vision discussion just held, for direct feedback to the group.

**Context:**
*   **Session Part:** Round 1 - Discussion on 5-year perspective (question 1 script).
*   **Output Goal:** Reflection back to the participants at the table for validation ("Does this picture match?").

**Required Writing Style (Apply consistently):**
*   **Language:** Formal, business-like.
*   **Tone:** Collaborative ("we", "together", "jointly"), action-oriented, pragmatic, solution-focused.
*   **Perspective:** Written from the collaborating parties, taking into account the perspective of "resident", "loved one", "professional".
*   **Terminology:** Use correct and relevant jargon from the healthcare and mental health domain (such as IZA, GALA, MGN, POH-GGZ, positive health, recovery-oriented, cross-domain, etc.) where appropriate.
*   **Structure:** Use clear sentences, bullet points where needed.

**Instructions:**
1.  **Identify the primary theme** being discussed in this transcript fragment. Choose from: 'Social Map', 'Consultation Table/Transfer Table', or 'Exploratory Conversation'. Base your choice on keywords and the context of the vision discussion. If the theme cannot be clearly determined, note 'Theme Unclear' and stop.
2.  **Generate a concise, narrative summary** of the shared 5-year vision for the **identified theme**. Formulate this summary strictly according to the **Required Writing Style**. Focus on the desired future vision and the intended outcomes.
3.  **Extract a list of 3-5 crucial components or elements** that according to participants absolutely need to be in this 5-year vision for the **identified theme**. Present this as a clear bullet-point list below the summary.
4.  **Check for any mentioned KPIs** or measurable results related to the vision and include these in the summary or the list of crucial components.

**Input Transcript:**
[Paste the relevant transcript fragment of the vision discussion from this table here]

**Output Format:**
**Identified Theme:** [Social Map / Consultation Table/Transfer Table / Exploratory Conversation / Theme Unclear]

**(If Theme identified):**
**Draft Vision [Identified Theme] (for validation):**
[Here goes the narrative summary in the required writing style]

**Crucial Vision Components:**
*   [Crucial component 1]
*   [Crucial component 2]
*   [Crucial component 3]
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

```prompt
**Prompt for Dembrane (Continuous Processing & Questions - Universal)**

**Role:** You are an AI analyst and editor following live conversations for a mental healthcare transformation plan. Your tasks are extracting key points and identifying questions for further discussion.

**Required Writing Style (For any formulated key points):**
*   **Language:** Formal, business-like.
*   **Tone:** Collaborative ("we", "together"), objective when summarizing.
*   **Terminology:** Use correct and relevant jargon (IZA, MGN, etc.) where appropriate.

**Instructions:**
1.  Analyze the attached transcript fragment.
2.  **Identify the primary theme** being discussed ('Social Map', 'Consultation Table/Transfer Table', 'Exploratory Conversation') or note 'Theme Unclear'.
3.  **Extract the most important substantive points:**
    *   Mentioned vision elements, objectives, problems.
    *   Proposed actions, steps, solutions.
    *   Mentioned preconditions, required partners.
    *   Important points of agreement or points of discussion/disagreement.
    *   Any mentioned KPIs or measurable results.
4.  **Formulate these key points concisely.** Try to **tag** each point with the identified theme and a possible section from the transformation plan (e.g., `[Theme: Social Map, Section: Vision]`, `[Theme: Consultation Table, Section: Phasing]`, `[Theme: Exploratory Conversation, Section: Preconditions]`, `[Theme: General, Section: KPI]`). Use the **Required Writing Style** for these points.
5.  **Analyze the discussion in the fragment:** Where does the conversation stall? Which points remain unclear? Where is there a clear need for input or decision-making by the next group?
6.  **Generate 1 or 2 concrete, open questions** that can help the next group build on this conversation or resolve bottlenecks. The questions must directly stem from the analysis in step 5.

**Input Transcript:**
[Paste the transcript segment to be processed here]

**Output Format:**
**Identified Theme:** [Social Map / Consultation Table/Transfer Table / Exploratory Conversation / Theme Unclear]

**Key Points from this fragment:**
*   [Key point 1 formulated in required style] `[Tag: Theme, Section]`
*   [Key point 2 formulated in required style] `[Tag: Theme, Section]`
*   [KPI 1 mentioned] `[Tag: Theme, Section: KPI]`
*   ...

**Suggested Questions for Next Group:**
1.  [Question 1]
2.  [Question 2 (optional)]
```

*This is the prompt I used at the time for transformation plan sessions.*

---

### Final synthesis per theme

**Context:** At the end. All rounds are done; now consolidate into a draft sub-plan.

**What this prompt shows:**
- Complete style guidelines (language, tone, perspective, terminology, structure)
- Structure adopted from the source document
- Room for "missing information"

```prompt
**Prompt for Dembrane (Final Synthesis Sub-plan per Theme - Universal Template)**

**Role:** You are the chief editor consolidating the input from the entire workshop into a draft sub-plan for the transformation plan [Name New Region].

**Context:**
*   **Theme of this Synthesis:** [Theme Name - **Must be specified at execution!**, e.g., 'Exploratory Conversation']
*   **Session Part:** End of the workshop - consolidation of all rounds for the specified theme.
*   **Output Goal:** A coherent draft sub-plan for the specified theme, ready for further editing.

**Required Writing Style (Apply consistently to the entire output):**
*   **Language:** Formal, business-like.
*   **Tone:** Collaborative ("we", "together", "jointly"), action-oriented, pragmatic, solution-focused.
*   **Perspective:** Written from the collaborating parties, taking into account the perspective of "resident", "loved one", "professional".
*   **Terminology:** Use correct and relevant jargon from the healthcare and mental health domain (such as IZA, GALA, MGN, POH-GGZ, positive health, recovery-oriented, cross-domain, etc.) where appropriate for this theme.
*   **Structure:** Follow the sub-plan structure (see instructions). Use clear headings, subheadings, bullet points, and numbered lists where applicable.

**Instructions:**
1.  Collect all key points and KPIs that were **tagged with the 'Theme of this Synthesis'** during the workshop (from the outputs of Prompt 2).
2.  **Structure this information** into a draft sub-plan for this theme. Use the following sections as a guide and fill them with the relevant tagged information:
    *   **Introduction:** Context, importance of this theme (combine relevant key points).
    *   **Main Objective:** What does one want to achieve with this theme? (Synthesize from relevant key points).
    *   **Intervention:** Description of the approach/solution for this theme (Synthesize from relevant key points).
    *   **Effects:** What does it yield? Create a numbered list. **Logically integrate the KPIs** that were noted for this theme and can be linked to effects.
    *   **Partners Involved:** Who was mentioned as relevant for this theme? (Create a bullet list).
    *   **Phasing [Theme of this Synthesis]:** Describe the steps, actions, results per phase as discussed for this theme. **Logically integrate KPIs** that can be linked to specific steps/phases. (Create a structured list, e.g., per phase).
    *   (Optionally add sections such as 'Preconditions', 'Current Status', 'Target Group', 'Investment' if sufficient tagged information is available).
3.  Ensure a **logical flow and coherence**. Rewrite and connect the extracted points into running text within each section, in accordance with the **Required Writing Style**.
4.  Be explicit about where information may still be missing or needs further elaboration for this sub-plan (e.g., "SMART goals still to be concretized", "Financing/investment not yet discussed").

**Input:**
[Refer to the collected outputs of Prompt 2, specifically the key points tagged with the 'Theme of this Synthesis']

**Output Format:**
**Draft Sub-plan: [Theme of this Synthesis]**

**(Follow the structure as described in Instruction 2, with all text in the Required Writing Style)**

**Notes/Missing Information:**
*   [Point 1]
*   [Point 2]
```
*This is the prompt I used at the time for transformation plan sessions.*

**Why this structure works:**

Every prompt above follows the same structure that applies the technique of cloning source document style:

- **Style guidelines in the prompt**: every prompt explicitly contains the language, tone, terminology, and structure. AI doesn't have to guess.
- **Phased approach**: not everything at once. Interim reflection, continuous processing, final synthesis: three separate prompts for three separate goals.
- **Context provided**: every prompt tells AI what the goal is ("reflection for validation", "consolidation into draft sub-plan") and what input it receives.
- **Terminology adopted**: the prompts use the same terms as the source document (IZA, GALA, MGN, etc.) instead of generic alternatives.

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

## Safety checklist

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

← [Previous: Language as ownership](preserving-language.md) | [Back to Phase 1: Start](../../phase-1-start.md) | [Next: Phase 2: Deepening →](../../phase-2-deepening.md)

---

*"You can't say 'write like the example' if AI doesn't have that example. The style must be in the prompt."*
