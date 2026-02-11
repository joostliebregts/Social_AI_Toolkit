# Intuition in writing

> *AI makes visible what you already felt but couldn't yet name.*

**Phase:** [Phase 2: Deepening](../../phase-2-deepening.md)
**Builds on:** Transcripts as raw material for pattern recognition

---

## When is this relevant?

**Situation:** You've facilitated a conversation. You feel there's something in it -- a [recurring theme, an unspoken tension](../../phase-2-deepening.md), a dynamic you sense -- but you can't quite put it into words.

**The tendency:** To carry your feeling with you, but without the words to make it concrete. You know something's going on; you just can't point to it.

**The principle:** AI can scan the transcript for patterns that you intuitively sense but can't make explicit. It's a magnifying glass, not a replacement for your perception.

**The question:** What would change if you could show what you currently only feel?

---

## The story: the pattern I didn't see

We were facilitating a steering group in a bottom-up change process. This group had already accomplished so much: they hadn't just identified problems and come up with solutions, they had also designed and run sessions themselves. They had gathered input from dozens of people across the organization. They had successes: in multiple meetings it had become clear -- *these are the patterns we all need to address, this is what matters according to the people we've spoken with*.

And yet there we were, in the same conversation again: everything that could go wrong, all the obstacles, all the reasons to delay the decision.

I noticed I was getting irritated. Inside my head I was stewing: *you've already done so much, why do we keep getting stuck here?* I heard my co-facilitator say something and thought: *oh no, you're pouring oil on the fire*. At some point I said, louder than I intended: "Don't we see what's happening here? We're going in circles."

Afterwards, I went back to the transcript. I gave it to ChatGPT with the question: what values are at play here? I used the Spiral Dynamics lens as a frame.

What came back gave words to what I had felt: two value systems were dominant. **Green**: the sense of community, the desire to include everyone, leave nobody out. And **blue**: the need for thoroughness, that things are done properly, that nothing is forgotten, that it's complete.

Not unwillingness. Not resistance. Care.

I hadn't realized that in the moment. All I felt was my own frustration. Only when I saw it in writing did I understand what was going on -- and what I could have done differently: name the pattern *before* I started bottling it up.

---

## Second example: three phases in one evening

The parent-teacher evening about growing up smartphone-free. In [Phase 1](../../phase-1-start.md), you already read about Maarten and the bicycle helmet moment. Here, we look at the same session from the perspective of pattern recognition: AI makes visible what you already felt.

Fourteen parents share their struggles. Afterwards, there's a feeling: the conversations about toddlers were different from the conversations about teenagers. But how exactly?

AI analyzed the transcript and identified three phases:

| Phase | The atmosphere | Dominant emotion |
|-------|----------------|------------------|
| **Toddlers & Early primary** | "Paradise" | Unawareness & Caution |
| **Middle primary** | "The Twilight Zone" | Confusion & First Pressure |
| **Late primary** | "Reality" | Fear of Exclusion & Regret |

These were patterns that could be intuitively felt -- now they were in writing. With names, with quotes, with a structure.

The feeling was there. AI made it visible.

**The prompt that produced this:**

```
# CONTEXT & ROL
Je fungeert als een systemisch strateeg en gemeenschapsbouwer.
Je hebt toegang tot het transcript van een ouderbijeenkomst (~14 deelnemers).

# OPDRACHT
Analyseer het transcript en breng de emotionele leefwereld in kaart,
ingedeeld per schoolfase (Kleuters/Onderbouw vs. Middenbouw vs. Bovenbouw).

# RANDVOORWAARDEN
- Privacy: Gebruik GEEN echte namen
- Taal: Gebruik de *letterlijke bewoordingen* van de deelnemers
- Toon: Empathisch, niet-oordelend
- Kijk voorbij de klacht ("mijn kind wil gamen") naar de onderliggende
  waarde ("ik wil dat mijn kind sociaal meekomt")

# OUTPUT
Per fase:
- Welke specifieke angsten, twijfels of comfortzones ervaren ouders?
- Waar zit de energie? Wie voelt urgentie, wie zit in de 'veilige haven'?
- Citaten die het patroon illustreren
```

*Source: Smartphone-free community analysis prompt*

**Why this works:**
- "Use the participants' literal words" protects against AI interpretation: these are *their* words, not your summary
- "Look beyond the complaint to the underlying value" is the core of intuition in writing: not what people say, but what's underneath
- "Per phase" gives structure to a feeling you already had ("the conversations about toddlers were different") but can now name

---

## What makes this different from analysis

There's a crucial difference between "AI found something new" and "AI made visible what I already felt."

**AI found something new:**
You didn't know there was a pattern. AI shows it. You think: "Oh, I hadn't seen that."

**AI makes visible what you felt:**
You knew something was there. AI gives it words. You think: "Yes, that's exactly it."

The difference isn't in the surprise, but in the recognition. You already knew; now you can also show it. Your intuition gets a foundation.

---

## The prompt

A prompt to make patterns explicit that you intuitively sense:

```
# ROL
Je bent een patroon-analist die helpt om impliciete groepsdynamiek
zichtbaar te maken.

# CONTEXT
Ik heb dit gesprek gefaciliteerd en heb een intuïtie dat er iets
verschuift over het verloop. Maar ik kan het niet precies benoemen.

# OPDRACHT
Lees het transcript en zoek naar:
1. Verschuivingen in toon of energie
2. Thema's die terugkomen maar anders worden besproken
3. Waardensystemen die botsen of domineren
4. Momenten waar de groep "kantelt"

# RANDVOORWAARDEN
- Baseer strikt op wat er staat, niet op interpretatie
- Bij twijfel: "mogelijk" in plaats van stellige bewering
- Gebruik hun woorden, niet jouw samenvattingen
- Zoek niet naar wat ik wil vinden, maar naar wat er is

# OUTPUT
Per gevonden patroon:
- Een herkenbare naam (in de taal van de groep)
- 2-3 citaten die het patroon illustreren
- Wat er verschuift (van X naar Y)
- "Mogelijk relevant": wat dit zou kunnen betekenen
```

*This is a starting point: adapt to your specific situation and add context about what you're looking for.*

**Why this works:**
- "Base strictly on what's there, not on interpretation" prevents AI from feeding your confirmation bias
- "When in doubt: 'possibly' instead of definitive claims" leaves room for the group to test for themselves
- "Use their words, not your summaries" preserves ownership: people recognize themselves
- "Don't look for what I want to find" makes your own preconceptions explicit in the prompt

---

## Three applications

### 1. Confirming what you felt

**When:** You have an intuition about the conversation. You want to know if it holds up.

**Approach:** Give AI the transcript without saying what you're looking for. See if it comes back.

**In your prompt:**
> Analyze this transcript for dynamic patterns. Pay specific attention to moments where the energy shifted, topics that were avoided, and differences between what was said and what seems to have been meant.

**For example:** After a team meeting, you feel there's tension around a particular topic. You ask AI to analyze "dynamic patterns" (not around people, but around themes). AI identifies that the conversation veered away from budget discussions three times, each time after a critical remark.

### 2. Finding words for the unnamed

**When:** You feel something but don't have words for it.

**Approach:** Ask AI to analyze the conversation for tension, energy, shifts. See what language AI uses.

**In your prompt:**
> I have a feeling that something shifts in this conversation but I can't name it. Analyze for shifts in tone, energy, and themes. Give each pattern a name in the language of the group.

**Example:** The "three phases" (Paradise, Twilight Zone, Reality) weren't my words. AI generated names that captured the feeling.

### 3. Building a case for evaluations

**When:** You need to report back to a client or team. You have a sense of how things went, but lack concrete evidence.

**Approach:** Let AI identify patterns with quotes. Use those as evidence.

**In your prompt:**
> Identify patterns in this transcript. Per pattern: a recognizable name, 2-3 quotes that illustrate it, and what shifts.

**Example:** "I noticed the energy dropped on this topic" becomes "From the transcript: at three moments the conversation shifted away from [topic], each time after these types of remarks..."

---

## Tensions

**Group versus individual**
Even without names in the transcript, it's often possible to trace statements back to individuals. The temptation exists to ask: "Who's blocking here?" Why I think that's problematic: it creates an unsafe dynamic. People feel watched instead of heard.

*My approach:* I analyze at the group level and around themes, not around individuals. The dynamic in a group is often *between* people; I can work with that without personally analyzing anyone. I ask about "what tensions are at play" instead of "who's causing the tension."

**Confirmation bias**
I'm looking for confirmation of what I already think. AI finds the "evidence" I want to find.

*My approach:* I also ask for patterns that contradict my intuition. "What would argue against this pattern?" Another strategy is asking more neutral questions. Instead of "how unhealthy is alcohol?" (which already implies a direction), I ask "what is the effect of alcohol on the body?" That second question yields a much broader perspective.

**Too much trust in AI**
AI always finds something. Not everything it finds is a real pattern.

*My approach:* I check against my own sense and against what others recognize. If they don't recognize it, it may not be a pattern.

**Presenting patterns as facts**
The difference between "it seems like" and "analysis shows" is small in words, large in effect.

*My experience:* When I'm too definitive about what AI finds (or too definitive in general), I notice that people withdraw or shut down. The language of possibility ("possibly underexposed", "a pattern that emerges") gives people room to test for themselves whether it holds up.

---

## Safe defaults

- [ ] Analysis at group level, not on individuals?
- [ ] AI observations framed as possibilities, not as facts?
- [ ] Patterns checked against your own sense?
- [ ] Quotes included as evidence?
- [ ] Room left for disagreement?

---

## Philosophical deepening

### From feeling to words

What I keep noticing: intuition is tricky. You feel something's going on, but you can't point to it. It's in your body, not in your head. You know it, but you can't say it.

The way I see it, it depends on your experience how well you can translate that feeling into words. An experienced facilitator feels tension and can immediately name it: "I notice we keep veering away from this topic." I didn't have those words in that one steering group session. I felt the frustration, but I couldn't name what was going on -- until I analyzed the transcript and AI helped me see it.

Here's what's interesting: the intuition was already there. AI didn't create it. What AI did was make the translation: from something invisible to something I could name and discuss.

### The magnifying glass

This is where the magnifying glass metaphor works for me. AI magnifies what's already there. It makes visible what's in the transcript, but what you couldn't process in the moment. It gives structure to what you sensed but couldn't organize.

Because of this, I now see things I used to miss. It gives me more confidence to name patterns, because I have evidence. And perhaps most valuable: I learn to recognize new patterns, and ways to deal with them next time.

That's also a form of democratization. The frustration I felt in that steering group, the three phases the parents recognized -- recognizing those kinds of patterns used to be reserved for facilitators with years of experience. AI makes that translation more accessible, not by replacing the experience, but by turning the feeling into words.

### The value of words

There's something remarkable about seeing in writing what you feel. It's not just communication to others; it's also clarity for yourself.

The "three phases" (Paradise, Twilight Zone, Reality) were already there. They just didn't have a name yet. By naming them, they became discussable, shareable, usable. And "green" and "blue" in that steering group? That gave me a way to talk about the dynamic without blaming anyone.

This is what AI can do: not create new truth, but name existing truth.

---

## Related techniques

**Other entry points to deepening:**
- [What else was in there](what-else-was-in-there.md) -- digging together with AI for structure, hooks, and powerful quotes (this is the reactive variant: you don't yet feel exactly what you're looking for)

**Building further:**
- [Patterns over time](../phase-3/patterns-over-time.md) (Phase 3) -- confirming intuitions over longer processes

---

← [Previous: From conversation to plan](conversation-to-plan.md) | [Back to Phase 2](../../phase-2-deepening.md) | [Next: What else was in there →](what-else-was-in-there.md)

---

*"AI makes visible what could be intuitively felt, but wasn't yet in writing."*
