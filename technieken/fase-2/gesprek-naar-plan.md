# Van gesprek naar implementatieplan

> *Live output genereren die betrokkenen direct kunnen beoordelen.*

**Fase:** [Fase 2: Verdieping](../../fase-2-verdieping.md)
**Bouwt voort op:** [Brondocument-stijl klonen](../fase-1/brondocument-stijl.md), nu als live documentatie tijdens sessies

---

## Wanneer is dit relevant?

**Situatie:** Je faciliteert een strategische sessie. Betrokkenen delen hun perspectief. Normaal zou je na afloop een dag besteden aan het verwerken: sticky notes ordenen, concept schrijven, feedback verzamelen.

**De neiging:** Het proces accepteren als gegeven. Na de sessie een dag uittrekken om alles te verwerken, want "zo doen we dat altijd." De aanname dat kwaliteit afstand nodig heeft; dat je er even over moet slapen. En waarschijnlijk ook: die twijfel of AI het net zo goed kan als jij het zelf zou schrijven.

**Het principe:** AI kan tijdens de sessie al concept-output genereren. Mensen zien hun woorden direct terug, gestructureerd in de vorm die de organisatie nodig heeft. De feedback-loop verkort van dagen naar minuten.

**De vraag:** Wat als mensen hun input direct terugzien als concept-document?

**Het verschil met [Live reflectie](live-reflectie-met-ai.md):** Daar gebruik je AI voor reflectievragen *tijdens* het gesprek, om wendingen te creëren. Hier gebruik je AI om *documentatie* te genereren uit het gesprek. Beide kunnen in dezelfde sessie: de echo-knop voor wendingen, en deze techniek voor output.

**Dit is een semi-live werkmethodiek.** Niet real-time zoals de echo-knop (direct in het gesprek), maar tussen de blokken door: in pauzes of deelsessies. Je hebt even 1-2 minuten nodig om een prompt te lanceren en de output te bekijken voordat je die aan de groep toont.

---

## Het verhaal: 1 dag naar 1 minuut

Dit principe hebben we toegepast voor het transformatieplan van het mentaal gezondheidsnetwerk in Centraal Gelderland. Het werkte — waardoor we het daarna ook in Amsterdam hebben toegepast.

Een voorbeeld uit Gelderland. Dertig betrokkenen geven input voor een transformatieplan van het mentaal gezondheidsnetwerk. Het oude proces:

1. Live sessie: mensen werken in kleine groepen
2. Plakbriefjes op muren
3. **Eén dag verwerking**: facilitators clusteren en schrijven concept
4. Review door 10-persoons team
5. Finale integratie

De vraag: wat als AI dat concept-document direct uit het gesprek kon genereren?

Het antwoord werd een live workflow:
- Transcriptie loopt mee tijdens de (originele) gefaciliteerde sessie waar met plakbriefjes gewerkt wordt. 
- In korte pauzes genereert AI concept-secties
- Mensen zien hun woorden terug, gestructureerd — en herkennen ze meteen

Van een dag werk naar minuten verwerking. Zonder de waarde van plakbriefjes of facilitatie te vervangen.

---

## Hoe het werkt

### De basiswerkwijze

**VOOR DE SESSIE:**
Bereid prompts voor die passen bij het document-type en de stijl die nodig is.

**TIJDENS:**
1. Transcriptie loopt mee
2. Na elke fase: transcript-segment naar AI
3. AI genereert concept-sectie in de juiste vorm
4. Toon aan groep ter validatie
5. Feedback integreren

**NA:**
Consolideer alle secties tot uiteindelijk document.

### De feedback-cyclus

In de praktijk ziet dit er zo uit:

1. **Groep 1** geeft input
2. AI zet het om naar **concept v1**
3. **Groep 1** reageert op v1, feedback wordt verwerkt naar **concept v2**
4. **Groep 2** krijgt v2, reageert en vult aan
5. AI verwerkt naar **concept v3**
6. **Groep 3** krijgt v3, geeft laatste input
7. Het document heeft van iedereen input en feedback gehad — iedereen heeft kunnen bijdragen

Dit is de "doordraaien" variant: elke groep bouwt voort op de verbeterde versie van de vorige groep. AI houdt de rode draad vast. Dit is een voorproefje: in [Fase 3](../../fase-3-schaal.md) komen meer varianten aan bod, zoals het samenvoegen van parallelle breakouts tot één synthese.

### De prompt

Dit is de daadwerkelijke prompt die we gebruikten bij de transformatieplansessies voor het mentaal gezondheidsnetwerk. Hij is ontworpen voor Dembrane maar werkt met elke tool die transcripten kan verwerken.

Het bijzondere: je gebruikt dezelfde prompt herhaaldelijk. Elke keer met meer input. AI bepaalt zelf wat nodig is.

**Hoe het werkt:**

1. **Één prompt, twee modi.** Geef je alleen het transcript van de discussie mee, dan genereert AI een eerste concept-deelplan. Geef je ook het feedback-transcript mee, dan genereert AI een herziene versie. Dezelfde prompt, ander resultaat.

2. **Reflectie bij de eerste keer.** Bij het eerste concept genereert de prompt ook een korte reflectie: een verhalende samenvatting van de kerninzichten uit de discussie. Dat is wat je aan de groep laat zien: "dit is wat AI hoorde."

3. **Feedback transparant verwerkt.** Bij herziene versies markeert AI wat er is gewijzigd en waarom. De sectie "Verantwoording van Verwerking Feedback" laat precies zien hoe de input van de vorige groep is verwerkt. Dat is wat eigenaarschap creëert: mensen zien dat hun feedback ertoe doet.

4. **Kernwaarden als rode draad.** De prompt identificeert waarden uit de discussie en weeft die door het hele document. Zo krijgt het plan niet alleen structuur, maar ook ziel.

```
Groep 1 bespreekt thema  ──► prompt ──► echo + concept v1
                                        ↓ tonen aan groep 1
G1 feedback op v1   ──► prompt ──► concept v2 (herzien)
                                        ↓ tonen aan volgende groep
G2 feedback op v2   ──► prompt ──► concept v3 (herzien)
                                        ↓ tonen aan volgende groep
G3 feedback op v3   ──► prompt ──► concept v4 ✓ (finale)
```

Steeds dezelfde prompt. Steeds meer input. Het document groeit mee.

**Bekijk de volledige prompt (deze is zeer lang)**

```prompt
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

**Waarom deze structuur werkt:**
- **"Baseer output strikt op expliciete informatie"** — voorkomt dat AI gaat verzinnen. Je krijgt eerlijke output met duidelijke gaten die je kunt opvullen.
- **"Verwijs expliciet naar hoe feedback is verwerkt"** — transparantie over wat er met de input is gedaan. Mensen zien dat hun bijdrage ertoe doet.
- **"Kernwaarden als rode draad"** — het document krijgt samenhang vanuit de waarden die de groep zelf heeft benoemd.
- **De tweeledigheid (echo + deelplan)** — eerst laten zien wat AI heeft gehoord, dan het document. Die volgorde geeft de groep grip: eerst herkenning, dan structuur.
- **Stijl in de prompt.** De prompt bevat stijlrichtlijnen zodat AI niet generiek schrijft, maar in de taal en structuur die de organisatie verwacht. (Zie [Brondocument-stijl klonen](../fase-1/brondocument-stijl.md) voor hoe je die stijl definieert.)

**Deze prompt aanpassen voor jouw context.** De thema's, terminologie en documentstructuur hierboven zijn specifiek voor het mentaal gezondheidsnetwerk. Je kunt de prompt aanpassen door:
- De **Rol** te wijzigen naar jouw document-type (projectplan, beleidsnotitie, strategisch kader)
- De **Thema-lijst** te vervangen door de onderwerpen die in jouw sessie spelen
- De **Stijl** aan te passen op de taal en toon van jouw organisatie
- De **Structuur** (stap 8) te modelleren naar het format dat jouw organisatie verwacht

Een snelle manier: geef AI deze prompt samen met een voorbeeld van een bestaand document uit jouw organisatie, en vraag: "Pas deze prompt aan zodat de output past bij dit format."

---

## De rol-verdeling

Dit vraagt twee mensen:

| | Facilitator | Co-facilitator |
|---|------------|----------------|
| **Voor de sessie** | Sessie-ontwerp, vragen voorbereiden | Techniek klaarzetten, opname regelen |
| **Tijdens** | Gesprek leiden, AI-output tonen, validatie begeleiden | Transcriptie monitoren, segmenten selecteren, prompts lanceren |
| **Na afloop** | Review output met groep | Verwerking en consolidatie |

Nooit: facilitator achter een laptop terwijl de groep wacht.

---

## Spanningen

**AI-output als waarheid presenteren**
"Dit is wat jullie besloten hebben" klinkt stellig, maar het is een AI-interpretatie.

*Mijn aanpak:* Ik presenteer het altijd als concept. "Dit is wat AI maakte van jullie gesprek. Klopt het?"

**Te weinig validatie-momenten**
Einde sessie: "Kijk, jullie document!" Maar niemand herkent zich omdat er geen tussentijdse checks waren.

*Mijn aanpak:* Tussentijds valideren. Na elke fase checken of het klopt.

**Stijl vergeten**
AI schrijft generiek. Het document past niet bij organisatie-standaarden.

*Mijn aanpak:* Stijlrichtlijnen in elke prompt. [Zie [Brondocument-stijl klonen](../fase-1/brondocument-stijl.md)]

**De ziel verliezen**
Het document is technisch correct maar mist de energie van het gesprek.

*Mijn aanpak:* Quotes behouden. Hun woorden, hun formuleringen. Dat houdt het leven erin.

---

## Veilige uitgangspunten

- [ ] Stijlrichtlijnen in prompts opgenomen?
- [ ] Tussentijds gevalideerd bij de groep?
- [ ] Quotes en originele taal behouden?
- [ ] "Concept ter validatie" geframed, niet als besluit?
- [ ] Tegenstrijdigheden en ontbrekende info gemarkeerd?

---

## Filosofische verdieping

### Directe terugkoppeling stimuleert eigenaarschap

Er is een reden waarom dit werkt. Wanneer mensen hun woorden direct terugzien, is de verbinding tussen spreken en resultaat nog vers.

"Dat zei ik net. En nu staat het hier."

Dit is anders dan een rapport een week later. De snelheid is niet voor efficiency; de snelheid is voor eigenaarschap.

### Het ritueel verandert, de intentie blijft

Het oude ritueel: sticky notes, clusteren, dag's werk, concept, review, final.
Het nieuwe ritueel: spreken, direct output, valideren, verfijnen.

De vorm is anders. Maar de intentie (mensen eigenaar maken van een plan) blijft. Sterker nog: door de snelheid is de eigenaarschap directer.

---

## Gerelateerde technieken

- De stijl-aanpak (hoe zorg je dat output in het juiste format komt?) staat in [Brondocument-stijl klonen](../fase-1/brondocument-stijl.md)
- Waarom het behouden van hun exacte woorden zo belangrijk is, lees je in [Taal als eigenaarschap](../fase-1/taal-behouden.md)
- Voor real-time interventies tijdens de sessie (niet alleen documentatie, maar ook reflectie), zie [Live reflectie met AI](live-reflectie-met-ai.md)

---

← [Vorige: Live reflectie](live-reflectie-met-ai.md) | [Terug naar Fase 2](../../fase-2-verdieping.md) | [Volgende: Intuïtie zwart op wit →](intuitie-zwart-op-wit.md)

---

*"Van een dag werk naar minuten verwerking: niet voor efficiëntie, maar voor eigenaarschap."*
