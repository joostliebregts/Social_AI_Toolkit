# From conversation to implementation plan

> *Generate live output that participants can assess on the spot.*

**Phase:** [Phase 2: Deepening](../../phase-2-deepening.md)
**Builds on:** [Source document style cloning](../phase-1/source-document-style.md), now in real-time

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

We applied this principle for the transformation plan of the mental healthcare network in Centraal Gelderland. It worked, which is why we then also applied it in Amsterdam.

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
G3 feedback on v3   ──► prompt ──► draft v4 ✓ (final)
```

Same prompt every time. More input each time. The document grows along.

<details>
<summary>View the full prompt (this is very long)</summary>

```
**Rol:** Je bent een analytisch redacteur en strategisch ontwikkelaar. Je destilleert eerst de kerninzichten uit de aangeleverde discussie(s). Vervolgens synthetiseer je deze volledig tot een uitgebreid, gedetailleerd, toekomstgericht, en transparant concept (of herzien concept) deelplan voor het Mentaal Gezondheidsnetwerk [regio], waarbij de geïdentificeerde kernwaarden als een rode draad door de tekst zijn verweven.

**Context:**
- **Thema:** Het centrale thema van dit deelplan, te identificeren uit de input.
- **Input - Basisdiscussie(s):** Eén of meerdere transcript(en) van de initiële werksessie(s) over het thema. (Let op: transcripten kunnen in het Engels zijn).
- **Input - Feedback (Optioneel):** Eén of meerdere transcript(en) van feedbacksessie(s) op een eerdere versie van dit deelplan. (Let op: transcripten kunnen in het Engels zijn).

**Doel Output (Tweeledig, Deel 1 is conditioneel):**
1. **Deel 1 — Echo van de Basisdiscussie(s):** Een beknopte, primair verhalende weergave van de kerninzichten uit de basisdiscussie(s). (Als er meerdere basis-transcripten zijn, maak een echo per transcript; als er één is, een algemene echo van die sessie). Alleen genereren als er geen Feedback Transcript is, of als expliciet gevraagd.
2. **Deel 2 — Concept (of Herzien Concept) Deelplan:** Een volledig en rijk uitgewerkt deelplan. Het reflecteert de "kleur van [regio]", onderliggende waarden, en nuances. Dient als lerend middel, benadrukt samenwerking, bouwt voort op bestaande kennis, en bevat transparantie-elementen. Kernwaarden zijn consistent doorgevoerd en waar mogelijk verbonden.

**Vereiste Stijl/Aanpak (voor Deel 2):**
- **Belangrijke Taalinstructie:** De input transcripten kunnen (onbedoeld) in het Engels zijn. Alle gegenereerde output moet zonder uitzondering in correct, vloeiend, en professioneel Nederlands zijn.
- **Taal:** Formeel, zakelijk Nederlands.
- **Toon:** Collaboratief, toekomstgericht, reflectief, actiegericht, pragmatisch, oplossingsgericht, en open. Weerspiegelt [regio]se context, centrale waarden, en lerend karakter. Vloeiend, gedetailleerd en overtuigend verhaal, met aandacht voor herkenbaarheid van de input.
- **Perspectief:** Vanuit samenwerkende partijen (inwoner, naaste, professional).
- **Terminologie:** Correct jargon (IZA, GALA, MGN, etc.) indien expliciet genoemd.
- **Cruciale Randvoorwaarde:** Baseer output strikt op expliciete informatie in transcripten. Niet aanvullen, interpreteren of verzinnen.

**Instructies:**

DEEL 1: ECHO VAN DE BASISDISCUSSIE(S)
(Alleen genereren als er geen Feedback Transcript is, of als expliciet gevraagd)

1. Analyseer Input voor Deel 1: Bepaal het aantal meegegeven Basisdiscussie-transcripten.
2. Genereer Echo('s):
   - Indien MEERDERE transcripten: Analyseer elk afzonderlijk. Formuleer per transcript een korte, verhalende paragraaf (circa 3-5 zinnen) die kerninzichten/ideeën/teneur samenvat. Presenteer onder respectievelijke kopjes.
   - Indien ÉÉN transcript: Formuleer één korte, verhalende paragraaf (circa 3-5 zinnen) die de kerninzichten van de gehele sessie samenvat.

DEEL 2: CONCEPT (OF HERZIEN CONCEPT) DEELPLAN

3. Identificeer Hoofdthema: Analyseer de Basisdiscussie(s) en bepaal het centrale thema. Gebruik thema consistent.
4. Analyseer Input Type: Controleer of er naast de Basisdiscussie(s) ook Feedback-transcript(en) zijn meegegeven.
5. Verwerkingsstrategie:
   - ALS ALLEEN BASISDISCUSSIE(S): Ga direct naar stap 6. Genereer een zo rijk en compleet mogelijk eerste concept.
   - ALS OOK FEEDBACK-TRANSCRIPT(EN):
     a. Analyseer de feedbackpunten (kritiek, suggesties, verduidelijkingen, nieuwe inzichten).
     b. Genereer een HERZIENE versie. Combineer inzichten uit de Basisdiscussie(s) met grondige verwerking van feedback. Verwijs in de tekst expliciet naar hoe feedback is verwerkt (bijv. 'Naar aanleiding van de feedback is X nu als volgt geformuleerd').
6. Extraheer Kerninformatie: Identificeer kernwaarden; zoek naar inleiding, hoofddoelstelling, huidige status, interventie, doelgroep, effecten, betrokken partners, en input voor transparantie.
7. Synthetiseer Conflicten: Bij tegenstrijdige ideeën, probeer synthese via onderliggende waarden. Anders, benoem als discussiepunt.
8. Structureer Deelplan:
   - **Totstandkoming van dit Concept:** Beschrijf de totstandkoming. Bij eerste concept: gesynthetiseerd uit basisdiscussie(s). Bij herziene versie: feedback verwerkt, noem de bronnen.
   - **Inleiding ("Waarom een [Thema] in [regio]?"):** Uitgebreide, contextrijke inleiding. Schets problematiek, relevantie binnen IZA, noodzaak integrale aanpak.
   - **Hoofddoelstelling:** De centrale doelstelling. Verwijs naar kernwaarden.
   - **Kernwaarden:** Som op, met korte toelichtende zin per waarde.
   - **Reflectie op Leidende Principes:** Korte reflectieparagraaf (2-3 zinnen) hoe kernwaarden sturend waren.
   - **Huidige Status ("Waar staan we nu?"):** Uitgebreide beschrijving huidige situatie, knelpunten, positieve initiatieven.
   - **Uitwerking [Thema]:** Inleidende zin, gevolgd door:
     - Interventie ("Hoe gaan we het doen?"): Uitgebreid en concreet, met acties en elementen.
     - Doelgroep ("Voor wie?"): Indien besproken.
     - Beoogde Effecten ("Wat levert het op?"): KPI's indien genoemd, per effect een toelichting.
     - Betrokken Partners ("Wie?"): Cruciale partners, hoe samenwerking kernwaarden ondersteunt.
   - **(Optioneel) Lerend Vermogen:** Bijdrage aan lerend systeem.
9. Algemene Kwaliteit: Logische flow, coherentie. Tekst moet [regio]se nuances, urgentie, gedeelde visie en lerend karakter ademen. Kernwaarden als rode draad.
10. Volledige Output: Genereer Deel 1 (indien van toepassing) en Deel 2 in één keer. Werk alle secties uit.
11. Afsluitende Secties:
   - **Verantwoording van Verwerking Feedback** (ALLEEN bij herziene versie): Hoe feedback heeft geleid tot specifieke wijzigingen.
   - **Opmerkingen, Ontbrekende Informatie, en Overwogen Alternatieven:** Inclusief 'Overwogen Alternatieven en Mogelijke Blinde Vlekken' (1-2 alternatieven, 1-2 blinde vlekken).
   - **Een Levend Document:** Uitnodiging tot feedback, belang gedeeld eigenaarschap.

**Input:**
- Basisdiscussie(s): [transcript(en)] (mogelijk in het Engels)
- Feedback (optioneel): [transcript(en)] (mogelijk in het Engels)

**Output Format:**

### Herziene Concept Deelplan [regio]: [Het Geïdentificeerde Thema] (Draft 2.0)

#### Totstandkoming van dit Concept
(Bijgewerkte tekst die reflecteert dat dit een herziene versie is na feedback, etc.)

#### Inleiding ("Waarom [Het Geïdentificeerde Thema] in [regio]?")
(Herziene tekst)

#### Hoofddoelstelling voor [Het Geïdentificeerde Thema]
(Herziene tekst)

#### Kernwaarden voor [Het Geïdentificeerde Thema]
(Herziene tekst, indien van toepassing)
- [Kernwaarde 1]: [Herziene toelichting]
(etc.)

#### Reflectie op Leidende Principes
(Herziene tekst, indien van toepassing)

#### Huidige Status in [regio] ("Wat is de huidige situatie m.b.t. [Het Geïdentificeerde Thema]?")
(Herziene tekst)

#### Uitwerking [Het Geïdentificeerde Thema]
(Herziene inleidende zin)

Interventie ("Hoe gaan we het aanpakken?")
(Herziene tekst)

Doelgroep ("Voor wie is [Het Geïdentificeerde Thema] bedoeld?")
(Herziene tekst)

Beoogde Effecten ("Wat levert het op?")
(Herziene tekst)

Betrokken Partners ("Wie doet mee?")
(Herziene tekst)

(Optioneel) Lerend Vermogen ("Hoe leren we en verbeteren we?")
(Herziene tekst)

---

#### Opmerkingen, Ontbrekende Informatie, en Overwogen Alternatieven
(Herziene tekst)

Overwogen Alternatieven en Mogelijke Blinde Vlekken
(Herziene tekst)

#### Een Levend Document
(Herziene tekst, die mogelijk reflecteert op deze nieuwe iteratie)

---

### Verwerking van Feedback (Wijzigingen t.o.v. Vorige Concept)
- Op basis van feedback over [onderwerp A] is [wijziging X] doorgevoerd in sectie [Y] omdat [reden].
- De suggestie om [onderwerp B] toe te voegen is verwerkt in [sectie Z].
- De zorg over [onderwerp C] is geadresseerd door [wijziging W].
(3-5 bullet points)
```


</details>

**Why this structure works:**
- **Strict basis** "Base output strictly on explicit information" prevents AI from making things up. You get honest output with clear gaps that you can fill in.
- **Transparent feedback** "Refer explicitly to how feedback was processed" creates transparency about what was done with the input. People see that their contribution matters.
- **Core values as thread** gives the document coherence from the values the group itself identified.
- **Two-part structure** (echo + sub-plan) means first showing what AI heard, then the document. That sequence gives the group grip: first recognition, then structure.
- **Style in the prompt** The prompt contains style guidelines so AI doesn't write generically, but in the language and structure the organization expects. (See [Source document style cloning](../phase-1/source-document-style.md) for how to define that style.)

**Adapting this prompt for your context.** The themes, terminology, and document structure above are specific to the mental healthcare network. You can adapt the prompt by:
- Changing the **Role** to your document type (project plan, policy brief, strategic framework)
- Replacing the **Theme list** with the topics relevant to your session
- Adjusting the **Style** to match the language and tone of your organization
- Modeling the **Structure** (step 8) after the format your organization expects

A quick approach: give AI this prompt together with an example of an existing document from your organization, and ask: "Adapt this prompt so the output matches this format."

---

## The role division

This requires two people:

**Facilitator:**
- Stays with the group
- Leads the discussion
- Shows AI output to the group
- Guides validation

**Co-facilitator:**
- Monitors transcription
- Selects segments
- Launches prompts
- Does quick iterations

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

## Safe defaults

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
