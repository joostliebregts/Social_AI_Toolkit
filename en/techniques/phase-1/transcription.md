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

That's what this toolkit is about. Transcription as raw material. Foundation for all kinds of things: capturing collective wisdom, revealing patterns, checking your own intuition, growing as a facilitator by looking back at what you could have done differently.

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

> "This transcript contains technical terms and names that may have been transcribed incorrectly: 'POH-GGZ' (not 'P.O. Achates'), 'Rianne' (not 'Rijanne'), 'GALA' (not 'gala')."

### Step 4: Use with intention

This is where the real work begins. The question isn't "what can I do with this transcript?" but "what do I want to achieve?"

- Want to reflect the group's own words back to them? → [Preserving language](preserving-language.md)
- Want to make patterns visible? → [Intuition in writing](../phase-2/intuition-in-writing.md) (Phase 2)
- Want action items? → See the Key Decisions prompt below
- Not sure yet? → Archive the transcript, come back to it later

---

## Four ways to use transcription

This is the first page in this toolkit where we actually start working with AI. Until now it was about why and how. Now it gets concrete: what do you actually do with a transcript?

There are countless possibilities. But in my work, four patterns keep coming back:

### 1. Capturing what you couldn't hear

This is the most basic application, and that's why it comes first. You can't catch everything when you're facilitating. You miss subtleties while thinking about the next question. You hear a powerful remark, but before you can write it down, the next speaker is already going.

Transcription is your safety net. Not as a replacement for attention, but as backup for when attention isn't enough.

**Prompt for finding what you missed:**

The prompt below is more extensive than you might expect for "capturing what you couldn't hear." That's deliberate. This is the actual prompt that Maarten and I used after the parent-teacher evening about smartphone-free parenting. It shows how you go from transcript to usable insights in one step: not just what was said, but also how you can use it in follow-up conversations.

```
# CONTEXT & ROL

Je fungeert als een systemisch strateeg en gemeenschapsbouwer die [De Initiatiefnemer] ondersteunt. Hij heeft een lokale werkgroep opgericht op de basisschool van zijn kinderen met als doel: het smartphonegebruik bij kinderen uitstellen en de norm veranderen (streven naar >25% smartphonevrij in de klas om groepsdruk te verlagen).

Je hebt toegang tot deze tekst:

1. Het transcript van de eerste online ouderbijeenkomst (~14 deelnemers).

# OPDRACHT

Analyseer de transcripten en creëer een strategisch overzicht ("De Giant Map") en een praktische gesprekstoolkit ("De Gesprekswaaier"). Het doel is niet om mensen te overtuigen met feiten, maar om verbinding te maken op basis van gedeelde waarden en zorgen.

# RANDVOORWAARDEN & STIJL

- **Privacy:** Gebruik GEEN echte namen. Vervang namen door [De Initiatiefnemer], [Facilitator], of [Ouder Groep X].

- **Taal:** Gebruik Nederlands. Gebruik de *letterlijke bewoordingen* van de deelnemers waar mogelijk voor maximale herkenbaarheid.

- **Toon:** Empathisch, niet-oordelend, constructief. Richt je op de wens om een goede ouder te zijn, niet op schuldgevoel over eigen schermgedrag.

- **Vorm:** Geef concrete haakjes en inzichten, geen letterlijke scripts die [De Initiatiefnemer] moet voorlezen. Hij wil zijn eigen authenticiteit bewaken.

# DE OUTPUT (in 3 delen)

## DEEL 1: DE TWEE HEATMAPS (Het Inzicht)

Breng de populatie in kaart op twee manieren, ingedeeld per schoolfase (Kleuters/Onderbouw vs. Middenbouw vs. Bovenbouw/Brugklas).

**A. De Emotionele Leefwereld (De Zorgen)**

* Welke specifieke angsten, twijfels of juist comfortzones ervaren ouders in deze fase?

* Kijk voorbij de klacht ("mijn kind wil gamen") naar de onderliggende waarde ("ik wil dat mijn kind sociaal meekomt").

**B. De Actie-Bereidheid (De Energie)**

* Waar zit de energie? Wie voelt urgentie (bijv. "het is 5 voor 12") en wie zit in de 'veilige haven'?

* Identificeer de 'haakjes' voor urgentie per groep: wat maakt dat een kleuterouder *nu* in actie wil komen, terwijl het probleem nog ver weg lijkt?

## DEEL 2: DE INTERNE STRIJD (De Verbinding)

Analyseer de spanning tussen "wat we doen" (eigen telefoongebruik, gemak) en "wat we willen voor ons kind" (vrij spelen, veiligheid).

* Frame dit NIET als hypocrisie of verslaving, maar als een uitdaging in modern ouderschap.

* Geef 3 tot 5 kernthema's terug waarin ouders worstelen met hun eigen voorbeeldrol.

* Gebruik hierbij citaten of parafrases die laten zien: "Je bent niet alleen, wij vinden dit ook moeilijk.

## DEEL 3: DE GESPREKSWAAIER (De Munitie)

Vertaal bovenstaande inzichten naar concrete 'haakjes' die [De Initiatiefnemer] kan gebruiken in informele gesprekken (bijv. op het schoolplein, langs de lijn).

* Geef per doelgroep (Onderbouw, Middenbouw, Bovenbouw) 2 à 3 openingen of observaties.

* Focus op het vinden van de *gemene deler*.

* Format: *"Als je een ouder uit groep [X] spreekt, is [THEMA] een sterke ingang. Je zou kunnen refereren aan [IDEE/CITAAT]."*
```

**Why this structure works:**
The role ("systemic strategist and community builder") steers AI's perspective: looking for connection, not delivering critique. The safeguards protect authenticity: using verbatim language, no real names, empathetic tone. The two heatmaps force AI to analyze both the emotions (concerns) and the energy (readiness to act). And the conversation fan translates insights into something usable: concrete hooks for real conversations.

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

This is perhaps the most obvious use of transcription. Many people start here: automating administration so you have space for other work. And that's fine. But in this toolkit it's in third place, because the first two patterns show what else is possible.

**AI helps write the prompt:**

These days you can also have AI write the prompt for you. Give it the transcript and your wishes, and ask for a fitting prompt. After a meeting I asked AI:

> "Now that the meeting is over, what's the right prompt to get the best-fitting summary and minutes, for both attendees and absentees (Anna and Lisa)?"

AI generated a prompt with structure (in brief, recap, decisions, action items, for absentees) and the instruction to preserve the language of participants. This is an interesting pattern: AI helps create the prompt based on context.

**Key Decisions Capture:**

```
**Rol**: Je bent een nauwkeurige notulist die expliciet genomen besluiten
vastlegt zonder interpretatie.

**Context**: Extract alleen de concrete besluiten die expliciet zijn
genomen tijdens deze sessie.

**Cruciale Randvoorwaarden**:
- Alleen expliciet genomen besluiten - geen impliciete of veronderstelde
  beslissingen
- Citeer letterlijk wie wat heeft besloten
- Bij twijfel: "Nog te bevestigen"

**Instructies**:
1. Scan transcript voor expliciete besluitvorming
   ("we besluiten", "afgesproken", etc.)
2. Noteer besluit, wie het nam, en eventuele voorwaarden
3. Groepeer per type besluit (proces, inhoud, vervolgstappen)

**Output Format**:
### Kernbesluiten uit deze Sessie

#### Procesbeslissingen
- [Besluit + wie + wanneer]

#### Inhoudelijke Besluiten
- [Besluit + wie + wanneer]

#### Vervolgafspraken
- [Afspraak + verantwoordelijke + deadline]
```

**Why this structure works:**
The role ("precise note-taker") keeps AI focused on what was literally decided. The safeguards prevent implicit conclusions. The output format is surprisingly powerful: AI follows it quite precisely.

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

Above you read four ways to use transcription. But there are techniques that go further: that build on transcription as a foundation. If you work through the toolkit chronologically, you'll encounter them naturally:

**Digging together into what's in there**
A transcript contains more than you could take in during the moment. Imagine: you go searching together with AI for structure, hooks for connection, powerful quotes.
→ *[What else was in there](../phase-2/what-else-was-in-there.md)* (Phase 2)

**Seeing patterns across multiple conversations**
One transcript is a snapshot. Five transcripts over three months show development: how language shifts, which themes recur, where breakthroughs happen or don't.
→ *Patterns over time* (Phase 3 -- coming soon)

**Finding unexpected connections**
Two people who share the same struggle without knowing it about each other. Two parents (of different children) both turned out to be struggling with playdates that revolve entirely around gaming. AI distilled the hook: "Are you also standing alone in that Minecraft conversation?" Not a summary. A bridge.
→ *Finding hooks* (Phase 3 -- coming soon)

---

## Tensions

With every technique in this toolkit I describe the tensions I encounter. Not as pitfalls to avoid, but as choices you make again and again. What works depends on the situation.

**Capturing is not yet using**
The threshold for transcription is so low that it almost feels obvious to record and transcribe everything. The transcript is there. That feels like progress. But without a next step, it gathers dust.

*My approach:* Often I already have an idea of what I want to do with it while transcribing. Which prompt am I going to use on it? What do I want to get out of it? Sometimes the answer is: I don't know yet, this is archiving. That's fine, but then I call it that. And when I do have a direction, I try to quickly do something small: mark five quotes, have AI look for a pattern. Small actions keep transcripts alive.

**Polishing versus authenticity**
The urge to make language "more professional." This is so important that it has its own page: [Preserving language](preserving-language.md).

**Convenience versus privacy**
The tools are so easy. Upload, click, done. But not every conversation belongs in the cloud.

*My approach:* I make a conscious choice per conversation. Internal or sensitive? Then local (MacWhisper). External or public? Then cloud works. When in doubt, I choose local. It also helps to be clear for yourself about what you want to do with the transcript, so you can articulate it well to others when asking permission.

---

## Safe defaults

With every technique in this toolkit I give a checklist of things to check before you begin. Not as bureaucracy, but as a quick scan: have I thought of the important things?

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
