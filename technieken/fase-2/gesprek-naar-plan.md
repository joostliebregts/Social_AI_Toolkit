# Van gesprek naar implementatieplan

> *Live output genereren die betrokkenen direct kunnen reviewen.*

**Fase:** [Fase 2: Verdieping](../fase-2-verdieping.md)
**Bouwt voort op:** [Brondocument-stijl klonen](../fase-1/brondocument-stijl.md), nu in real-time

---

## Wanneer is dit relevant?

**Situatie:** Je faciliteert een strategische sessie. Betrokkenen delen hun perspectief. Normaal zou je na afloop een dag besteden aan het verwerken: sticky notes ordenen, concept schrijven, feedback verzamelen.

**De neiging:** Het proces accepteren als gegeven. "Zo doen we dat altijd."

**Het principe:** AI kan tijdens de sessie al concept-output genereren. Mensen zien hun woorden direct terug, gestructureerd in het format dat de organisatie nodig heeft. De feedback-loop verkort van dagen naar minuten.

**De vraag:** Wat als mensen hun input direct terugzien als concept-document?

**Het verschil met [Live reflectie](echo-knop.md):** Daar gebruik je AI voor reflectievragen *tijdens* het gesprek, om wendingen te creëren. Hier gebruik je AI om *documentatie* te genereren uit het gesprek. Beide kunnen in dezelfde sessie: de echo-knop voor wendingen, en deze techniek voor output.

**Dit is een semi-live werkmethodiek.** Niet real-time zoals de echo-knop (direct in het gesprek), maar tussen de blokken door: in pauzes of breakout-momenten. Je hebt even 1-2 minuten nodig om een prompt te lanceren en de output te bekijken voordat je die aan de groep toont.

---

## Het verhaal: 1 dag naar 1 minuut

Dit principe hebben we toegepast voor het transformatieplan van het mentaal gezondheidsnetwerk in Centraal Gelderland. En daarna ook in Amsterdam. De nuance: het werkte in Centraal Gelderland, waardoor we het daarna ook in Amsterdam konden toepassen.

Een voorbeeld uit Gelderland. Dertig betrokkenen geven input voor een transformatieplan van het mentaal gezondheidsnetwerk. Het oude proces:

1. Live sessie: mensen werken in kleine groepen
2. Sticky notes op muren
3. **Eén dag processing**: facilitators clusteren en schrijven concept
4. Review door 10-persoons team
5. Finale integratie

De vraag: wat als AI dat concept-document direct uit het gesprek kon genereren?

Het antwoord werd een live workflow:
- Transcriptie loopt mee tijdens de (originele) gefaciliteerde sessie waar met sticky notes gewerkt wordt. 
- In korte pauzes genereert AI concept-secties
- Mensen zien hun woorden terug, gestructureerd
- "Wacht even... dit is letterlijk wat we zeiden. En nu staat het in een concept."

Van dag's werk naar minuten processing. Zonder de waarde van plakbriefjes of facilitatie te vervangen.

---

## Hoe het werkt

### De basis-workflow

**VOOR DE SESSIE:**
Bereid prompts voor die passen bij het document-type en de stijl die nodig is.

**TIJDENS:**
1. Transcriptie loopt mee
2. Na elke fase: transcript-segment naar AI
3. AI genereert concept-sectie in juiste format
4. Toon aan groep ter validatie
5. Feedback integreren

**NA:**
Consolideer alle secties tot finaal document.

### De feedback-cyclus

In de praktijk ziet dit er zo uit:

1. **Groep 1** geeft input
2. AI zet het om naar **concept v1**
3. **Groep 1** reageert op v1, feedback wordt verwerkt naar **concept v2**
4. **Groep 2** krijgt v2, reageert en vult aan
5. AI verwerkt naar **concept v3**
6. **Groep 3** krijgt v3, geeft laatste input
7. Het document heeft van iedereen input en feedback gehad — iedereen heeft kunnen bijdragen

Dit is de "doordraaien" variant: elke groep bouwt voort op de verbeterde versie van de vorige groep. AI houdt de rode draad vast.

### De prompt-suite

**Prompt 1: Tussentijdse terugkoppeling**
Na eerste discussie: validatie of je op koers bent.

```
**Rol:** AI-assistent voor live documentatie.

**Context:**
- Type sessie: [BESCHRIJVING]
- Fase: Eerste verkenning
- Doel: Tussenstand ter validatie

**Instructies:**
1. Analyseer transcript laatste [TIJDSDUUR]
2. Genereer beknopte samenvatting van gedeelde visie
3. Extraheer 3-5 cruciale onderdelen met consensus
4. Markeer waar nog onduidelijkheid is

**Stijl:**
[STIJLRICHTLIJNEN UIT REFERENTIE-DOCUMENT]

**Output:**
### Tussenstand na [TIJDSDUUR]
**Kernvisie tot nu toe:** [Narratief]
**Cruciale elementen:** [Bullets met quotes]
**Nog af te stemmen:** [Openstaande punten]
```

**Prompt 2: Sectie-generatie**
Per thema of onderdeel.

```
**Rol:** Beleidsschrijver die transcript omzet naar document-sectie.

**Context:**
- Sectie: [NAAM]
- Structuur: [VERWACHTE ONDERDELEN]
- Referentie-stijl: [RICHTLIJNEN]

**Instructies:**
1. Analyseer transcript
2. Schrijf sectie in referentie-stijl
3. Gebruik hun exacte terminologie
4. Markeer waar informatie ontbreekt

**Output:**
### [SECTIE NAAM]
[Inhoud volgens structuur]

**Let op:**
- Bij ontbrekende info: "[Nog te bespreken: X]"
- Citeer waar relevant
```

**Prompt 3: Consolidatie**
Na alle rondes: tot finaal document.

```
**Rol:** Hoofdredacteur die workshop-input consolideert.

**Input:**
- Alle transcript-segmenten
- Alle eerder gegenereerde concept-secties
- Feedback van validatie-momenten

**Instructies:**
1. Structureer volgens document-template
2. Integreer alle feedback
3. Behoud originele taal
4. Markeer tegenstrijdigheden
5. Benoem wat nog mist

**Output:**
[Volledig document in template-structuur]
```

### Waarom deze prompts werken

De prompts zijn opgebouwd rond drie principes:

1. **Stijl in de prompt.** Elke prompt bevat stijlrichtlijnen uit een referentiedocument. Zo schrijft AI niet generiek, maar in de taal en structuur die de organisatie verwacht. (Zie [Brondocument-stijl klonen](../fase-1/brondocument-stijl.md) voor hoe je die stijl definieert.)

2. **Transparantie over ontbrekende informatie.** De instructie "markeer waar informatie ontbreekt" voorkomt dat AI gaat verzinnen. Je krijgt eerlijke output met duidelijke gaten die je kunt opvullen.

3. **Originele taal behouden.** "Gebruik hun exacte terminologie" en "citeer waar relevant" zorgt dat mensen zichzelf herkennen. Dat is wat eigenaarschap stimuleert.

---

## De rol-verdeling

Dit vraagt twee mensen:

**Facilitator:**
- Blijft bij de groep
- Leidt de discussie
- Toont AI-output aan groep
- Begeleidt validatie

**Co-facilitator:**
- Monitort transcriptie
- Selecteert segmenten
- Lanceert prompts
- Doet snelle iteraties

Nooit: facilitator achter een laptop terwijl de groep wacht.

---

## Spanningen

**AI-output als waarheid presenteren**
"Dit is wat jullie besloten hebben" klinkt stellig, maar het is een AI-interpretatie.

*Mijn aanpak:* Ik frame altijd als concept. "Dit is wat AI maakte van jullie gesprek. Klopt het?"

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

## Veilige defaults

- [ ] Stijlrichtlijnen in prompts opgenomen?
- [ ] Tussentijds gevalideerd bij de groep?
- [ ] Quotes en originele taal behouden?
- [ ] "Concept ter validatie" geframed, niet als besluit?
- [ ] Tegenstrijdigheden en ontbrekende info gemarkeerd?

---

## Filosofische verdieping

### Real-time feedback stimuleert eigenaarschap

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
- Voor real-time interventies tijdens de sessie (niet alleen documentatie, maar ook reflectie), zie [Live reflectie met AI](echo-knop.md)

---

<- [Terug naar Fase 2: Verdieping](../fase-2-verdieping.md) | [<- Live reflectie](echo-knop.md) | [Intuïtie zwart op wit ->](intuitie-zwart-op-wit.md)

---

*"'Dit is letterlijk wat we zeiden. En nu staat het in een concept. Wow, indrukwekkend.' Van dag's werk naar 1 minuut: niet voor efficiency, maar voor eigenaarschap."*
