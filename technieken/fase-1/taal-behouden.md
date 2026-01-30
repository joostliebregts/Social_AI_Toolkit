![Taal als eigenaarschap mechanisme](../../images/taalalseigenaarschapmechanisme.png)

# Taal als eigenaarschap

> *Het verschil tussen "communicatieproblemen" en "je praat tegen een muur" is niet semantisch — het eerste ondermijnt eigenaarschap, het tweede creëert het.*

**Fase:** [Fase 1: Begin](../../fase-1-begin.md)
**Bouwt voort op:** Het fietshelm-verhaal: waar Maarten's eigen woorden de kern blootlegden

---

## Wanneer is dit relevant?

**Situatie:** Je hebt een transcript. Je wilt er een synthese, samenvatting of terugkoppeling van maken. De groep moet zich herkennen in het resultaat.

**De neiging:** Alles "opschonen" naar professionele taal. Frustraties vertalen naar "uitdagingen." Rommelige zinnen herschrijven naar heldere bullets. Het resultaat klinkt beter — maar niemand herkent zichzelf meer.

**Het principe:** Wanneer mensen hun eigen exacte woorden terughoren of terugzien in AI-output, herkennen ze zichzelf. Die herkenning triggert eigenaarschap. Zonder herkenning geen eigenaarschap. Zonder eigenaarschap geen commitment.

**De vraag:** Als de mensen die dit gesprek voerden dit resultaat lezen, zeggen ze dan "ja, dat zeiden wij" of "dat klinkt als een consultant"?

---

## Het verhaal: "Dit is letterlijk wat we zeiden"

Op de [vorige pagina](transcriptie.md) leerde je hoe je gesprekken vastlegt als tekst. Maar wat doe je als die tekst naar iemand terug moet — als synthese, samenvatting of terugkoppeling?

Hier komt het spanningsveld: de neiging om alles "op te schonen" naar professionele taal. En het risico dat niemand zich meer herkent.

Een transformatieplan voor een Mentaal Gezondheidsnetwerk. Dertig stakeholders hebben input gegeven over hun visie op mentale gezondheid in de regio. Nu moet dat omgezet worden naar een document dat de zorgverzekeraar zal accepteren.

De sessie wordt live getranscribeerd met Dembrane. Terwijl de discussie nog gaande is, genereert AI een concept-deelplan op basis van wat er gezegd is.

Wanneer het getoond wordt, valt de reactie op.

> "Wacht even... dit is— ja, dit is letterlijk wat we zeiden. En nu staat het in een concept. Wow, indrukwekkend."

De stakeholders kijken naar het scherm en zien hun eigen woorden terug. Niet samengevat. Niet geïnterpreteerd. Hun exacte formuleringen, gestructureerd in een format dat de zorgverzekeraar herkent.

Later in de sessie gebruikt facilitator Jeroen de echo-knop. Er is een gespannen discussie over prioriteiten. AI vat het gesprek samen en stelt een vraag.

> "Wow, wow. Het vat het echt goed samen. Dit is letterlijk— ja, dit is echt de vraag die we moeten stellen."

De transitie is zichtbaar: van shock ("AI begrijpt ons?!") naar herkenning ("dit is letterlijk wat we zeiden") naar eigenaarschap ("dit is de vraag die we moeten stellen").

Niemand zou dezelfde reactie hebben gehad op een synthese die hun woorden had vertaald naar beleidstaal. Het verschil zit niet in de structuur. Het verschil zit in de taal.

---

![Mechanisme: letterlijk citeren](../../images/taal-behouden-mechanisme-letterlijk.png)

## Het mechanisme: herkenning creëert eigenaarschap

Waarom werkt dit? Het mechanisme is simpel maar fundamenteel:

```
1. Participant zegt iets met specifieke formulering
        ↓
2. AI behoudt exacte formulering in output
        ↓
3. Participant leest/hoort output
        ↓
4. Herkenning: "Ja, dat zei ik"
        ↓
5. Eigenaarschap: "Daar zit iets van mij in"
        ↓
6. Commitment: "Hier sta ik achter"
```

Dit is geen bijzaak. Dit IS het mechanisme waardoor participatie transformeert van "meegedacht hebben" naar "dit is van mij." Parafraseren breekt de keten bij stap 4. De herkenning valt weg. En daarmee alles wat erop volgt.
### De taal-hiërarchie

Niet alle taal is gelijk. Hoe specifieker, hoe sterker de herkenning:

| Niveau                                 | Voorbeeld                                                                         | Impact                                                |
| -------------------------------------- | --------------------------------------------------------------------------------- | ----------------------------------------------------- |
| **1. Hun exacte woorden met context**  | "De hele klas heeft geen helm. Doe ik ook niet meer, anders hoor ik er niet bij." | Maximale herkenning: dit is exact wat er gezegd werd |
| **2. Hun kernterminologie**            | "het fietshelm-effect"                                                            | Sterke herkenning: hun woord voor het fenomeen        |
| **3. Generieke termen uit hun domein** | "groepsdruk bij kinderen"                                                         | Herkenbaar maar afstandelijker                        |
| **4. Abstracte concepten**             | "sociale uitdagingen"                                                             | Nauwelijks herkenning                                 |
| **5. Consultantentaal**                | "stakeholder alignment rond jeugdgedragsnormen"                                   | Niemand herkent zich meer                             |

Het doel is niveau 1-2. Vermijd 4-5 altijd. Niveau 3 alleen als dat de taal is die zij zelf gebruiken.

---

## De kernvraag: het herkennings-criterium

```
ALS zij denken "ja, dat zeiden wij" → SUCCES
ALS zij denken "dat klinkt als een consultant" → MISLUKT
```

Dit is geen soft criterium. Dit is de harde test voor elke output. Een synthese die technisch correct is maar waar niemand zich in herkent, is waardeloos. Een synthese met hun rommelige taal maar waar iedereen bij knikt, is goud.

---

## De prompt

Het criterium is helder. Maar hoe zorg je ervoor dat AI output produceert die eraan voldoet?

Door taalbehoud expliciet te maken in de prompt. Niet als bijzaak, maar als kernvoorwaarde.

Dit is een prompt die we gebruikten voor een bestuurders-workshop in een kleine gemeente. Let op hoe de randvoorwaarden voor taalbehoud specifiek en concreet zijn:

```
**Rol**: Je bent een strategisch redacteur met expertise in visievorming
die individuele toekomstbeelden omzet in één krachtige, gezamenlijk
gedragen visie.

**Vereiste Stijl/Aanpak**:
- Gebruik hun eigen woorden en terminologie uit de gesprekken
- Behoud de kracht van hun individuele visies
- Maak het specifiek voor deze gemeente, niet generiek
- Schrijf in de toekomstige tegenwoordige tijd (2040 als realiteit)

**Cruciale Randvoorwaarden**:
- Baseer output strikt op transcript(en) - geen verzinsels
- Benoem openstaande punten en onzekerheden expliciet
- Gebruik quotes uit gesprekken zonder speaker attributie
- Gebruik hun eigen kernterminologie - niet automatisch "samenredzaamheid"
- Vermijd abstracte bestuurstaal - houd het menselijk

**Instructies**:
1. Analyseer elke individuele "stip op de horizon" die genoemd is
2. Identificeer hun eigen kernterminologie - gebruik NIET "samenredzaamheid"
   tenzij zij dat zeggen
3. Identificeer gemeenschappelijke waardes en kernprincipes
4. Zoek de specifieke lokale elementen die terugkomen
5. ALS er tegenstrijdigheden zijn DAN benoem deze expliciet als "nog af te stemmen"
6. Sluit af met waarom dit belangrijk is in hun eigen woorden

**Output Format**:
### Hun Waarom (in eigen woorden)
> "Quote waarom dit belangrijk is"
> "Quote over kernwaarde"

*Uit de gesprekken komt naar voren dat...*

### Nog Af Te Stemmen
- [Punten waar verschillende visies nog samenkomen]

### Over Deze Visie
Deze visie is opgesteld door AI op basis van jullie gesprek. Het is een
hulpmiddel om jullie eigen toekomstbeelden te structureren - niet perfect,
maar een startpunt voor verder gesprek. Dit blijft jullie verhaal - de AI
helpt alleen bij het bundelen en verbinden van jullie ideeën.
```

**Waarom deze structuur werkt:**
- **Rol** geeft AI een identiteit die past bij de taak: "strategisch redacteur met expertise in visievorming" stuurt naar synthese, niet samenvatting
- **Vereiste Stijl/Aanpak** definieert de toon: "hun eigen woorden" en "specifiek voor deze gemeente" voorkomt generieke output
- **Cruciale Begrenzingen** zijn de harde grenzen: "geen verzinsels", "niet automatisch samenredzaamheid" voorkomt dat AI gaat invullen
- **Instructies** zijn de stappen: de volgorde (eerst analyseren, dan identificeren, dan synthetiseren) stuurt het denkproces
- **Output Format** bepaalt de vorm: "Hun Waarom" met quotes dwingt letterlijke citatie af

---

## Variaties

De basisaanpak hierboven werkt voor veel situaties. Maar de context varieert: soms werk je met een gemeenschap, soms met meerdere gesprekken, soms live. Hieronder drie variaties die ik in de praktijk gebruik.

### Variatie 1: Gemeenschapsanalyse met "haakjes"

Op de transcriptiepagina zag je de [volledige prompt voor de smartphonevrij-ouderbijeenkomst](transcriptie.md#1-vastleggen-wat-je-niet-kon-horen). Hier licht ik twee randvoorwaarden uit die taalbehoud afdwingen:

> **Taal:** Gebruik de *letterlijke bewoordingen* van de deelnemers waar mogelijk voor maximale herkenbaarheid.

> **Vorm:** Geef concrete haakjes en inzichten, geen letterlijke scripts die [De Initiatiefnemer] moet voorlezen. Hij wil zijn eigen authenticiteit bewaken.

**Waarom dit werkt:**
- "Letterlijke bewoordingen" is explicieter dan "gebruik hun taal" — het voorkomt dat AI gaat parafraseren
- "Geen scripts" beschermt de authenticiteit van de facilitator — AI levert bouwstenen, geen kant-en-klare tekst
- "Maximale herkenbaarheid" benoemt het doel, niet alleen de methode

**Wanneer:** Bij groepen waar je verbinding wilt faciliteren, niet alleen informatie wilt vastleggen.

---

### Variatie 2: Sessie-analyse met participantentaal

Dit is de analyse-aanpak die we gebruikten bij een sleutelfigurensessie in Doesburg. Je kunt dit toepassen per tafel, per breakout, of per individuele sessie.

**Wanneer:** Na een sessie met gestructureerde rondes (bijv. droombeeld → uitdagingen → eigen mogelijkheden).

**Prompt:**
```
**Context**: Je analyseert het transcript van [één tafel/sessie/breakout]
over [onderwerp]. De sessie had [aantal] rondes: [ronde-namen].

**Opdracht**: Analyseer per ronde en identificeer:

### 1. Thema's met quotes
Per ronde: welke thema's kwamen terug?
- Met quotes die het thema dragen — in hun woorden, niet geparafraseerd
- Frequentie aangeven waar relevant

### 2. Eigenaarschaps-signalen
Herken taalpatronen die aangeven hoeveel eigenaarschap mensen voelen:

**Hoge eigenaarschap (0.7-1.0):**
- "Ik ga daar iets aan doen"
- "Wij moeten dit anders aanpakken"
- "Dat ga ik volgende week proberen"

**Gemengde eigenaarschap (0.4-0.6):**
- "Het zou moeten maar..."
- "Als er budget was dan..."
- "Ik probeer wel, maar het systeem..."

**Lage eigenaarschap (0.0-0.3):**
- "Daar kan ik niks aan doen"
- "Zij moeten dat oplossen"
- "Het is zoals het is"

→ Zoek specifiek naar concrete initiatieven en aanbiedingen.

### 3. Spanningen en paradoxen
- Waar spraken mensen zichzelf of elkaar tegen?
- Uitdagingen zonder "eigen mogelijkheid" ertegenover?
- Formuleer als vragen, niet als conclusies

### 4. Outliers
Dingen die met passie genoemd werden maar niet in een thema passen.
Niet clusteren — behoud als losse parels met context.

**Cruciale Randvoorwaarden**:
- Taal: Nederlands
- Herkenbare taal van deelnemers — geen consultant-speak
- Patronen benoemen, geen conclusies opdringen
- AI-observaties altijd expliciet labelen

**Don'ts**:
- Geen namen extern delen
- Interpretaties niet als feiten presenteren
- Niet "problematiseren" — de groep bepaalt wat problemen zijn
- Frustraties niet wegpoetsen of "constructief herformuleren"
- Niet parafraseren waar originele woorden krachtiger zijn

**Output Format**:
### [Ronde]: [Naam]
**Thema's**: [thema + quotes]
**Eigenaarschap**: [score-range + voorbeelden uit transcript]
**Spanningen**: [als vragen geformuleerd]
**Outliers**: [losse parels met context]
```

**Waarom deze structuur werkt:**
- De eigenaarschaps-schaal (0.0-1.0) geeft AI een concreet kader om taal te scoren
- "Formuleer als vragen" voorkomt dat AI conclusies trekt die de groep niet heeft getrokken
- "Losse parels" beschermt outliers tegen de drang om alles te clusteren
- Don'ts zijn expliciet omdat AI de neiging heeft om frustraties glad te strijken

*Wil je meerdere sessies vergelijken? Analyseer eerst elke sessie apart met deze prompt, leg de analyses naast elkaar, en zoek patronen. Die stap vind je in Patronen over tijd *(Fase 3 — komt nog)* (Fase 3).*

---

### Variatie 3: Taalbehoud in live reflectie

Tot nu toe ging het over analyse achteraf. Maar taalbehoud werkt ook live, midden in een sessie.

De echo-prompt hieronder is een lichtere variant van de [volledige live reflectie-techniek](../fase-2/echo-knop.md). Daar leer je wanneer je hem inzet, hoe je hem voorbereidt, en hoe de workflow werkt. Hier focus ik op één aspect: hoe de prompt taalbehoud afdwingt.

**Het taalbehoud-element:**

Kijk naar het output format:

> **Verschillende framingen**:
> - "Quote over hoe dit gezien wordt"
> - "Quote die anders nuanceert"

Dit is taalbehoud in actie. Niet "sommigen vinden X, anderen vinden Y" — maar letterlijke quotes die laten zien hoe verschillende mensen het framen. Deelnemers herkennen zichzelf. En dat is precies waar eigenaarschap begint.

**De prompt:**
```
**Rol**: Je bent een ervaren groepsdynamiek-expert die signalen van
vermeden onderwerpen, onuitgesproken spanningen en verschillende
perspectieven detecteert in dialogen.

**Vereiste Stijl/Aanpak**:
- Niet-oordelend en uitnodigend
- Focus op wat ontbreekt, niet op wat fout is
- Herken diplomatieke taal die onderliggende spanningen maskeert

**Cruciale Randvoorwaarden**:
- Baseer signalen strikt op transcript — geen veronderstellingen
- Onderscheid tussen stilte en consensus
- Bij twijfel: "Mogelijk onderbelicht" ipv stellige bewering
- Genereer maximaal 2 echo-vragen voor facilitator

**Output Format**:
### Wat Ik Waarneem
**Mogelijk onderbelicht**: [Onderwerpen die opgeroepen maar niet
uitgediept werden]

**Verschillende framingen**:
- "Quote over hoe dit gezien wordt"
- "Quote die anders nuanceert"

### Echo-vraag voor de Groep
**[Eén krachtige vraag die uitnodigt tot verdieping]**

### Over Deze Echo
Deze echo-analyse is een hulpmiddel om mogelijke blinde vlekken te
belichten — niet om te oordelen, maar om uitnodigende vragen te stellen.
De keuze om hier op in te gaan blijft bij jullie.
```

**Waarom dit werkt (taalbehoud-lens):**
- "Verschillende framingen" met letterlijke quotes zorgt dat mensen zichzelf herkennen
- "Baseer strikt op transcript" voorkomt dat AI gaat interpreteren
- "Bij twijfel: mogelijk onderbelicht" beschermt tegen te stellige beweringen over wat mensen "eigenlijk" bedoelden

*Voor de volledige techniek — wanneer inzetten, hoe voorbereiden, de workflow — zie [Live reflectie met AI](../fase-2/echo-knop.md).*

---

## Spanningen

**"Opschonen" voor leesbaarheid**
De neiging is om rommelige zinnen te herschrijven naar vloeiende tekst. Maar rommel is vaak authenticiteit. Een zin als "Ja maar dat is gewoon... kijk, het probleem is dat niemand..." draagt meer dan "Het probleem is dat niemand."

*Mijn aanpak:* Ik weersta de drang om te editen. Als het gezegd is, mag het er staan. Eventueel gebruik ik [...] voor irrelevante omwegen, maar de kern blijft exact.

**Frustratie versus "uitdaging"**
De consultant-reflex is om "ik word er gek van" te vertalen naar "er zijn uitdagingen." Maar de energie van frustratie is informatie. Die verdwijnt in abstractie.

*Mijn aanpak:* Als het een frustratie is, noem ik het een frustratie. Als iemand zegt "het is een puinhoop," laat ik dat staan. 

**Te veel context weghalen**
"De hele klas heeft geen helm" zonder context is verwarrend. Maar te veel context verdrinkt de quote.

*Mijn aanpak:* Ik citeer met voldoende context om de quote begrijpelijk te maken, maar niet zoveel dat de kracht verdwijnt.

**Vergeten te labelen**
Als AI patronen herkent of vragen stelt, kan interpretatie versmelten met eigenaarschap. Mensen weten dan niet meer wat van hen is en wat van AI.

*Mijn aanpak:* Ik maak visueel duidelijk wat van deelnemers is en wat van AI. Labelen is niet optioneel.

---

## Veilige defaults

*Voor privacy-afwegingen bij gevoelige gesprekken, lees [Veilig werken met AI](../../veilig-werken.md).*

- [ ] Exacte woorden behouden? (niet geparafraseerd "voor helderheid")
- [ ] Terminologie van deelnemers gebruikt? (niet vertaald naar jargon)
- [ ] Frustraties als frustraties benoemd? (niet als "uitdagingen")
- [ ] Bij twijfel expliciet gemaakt? ("Mogelijk onderbelicht")
- [ ] AI-observaties gelabeld als AI? (niet versmolten met eigenaarschap)

---

## Filosofische verdieping

**Principe:** Real-time feedback versnelt eigenaarschap

Er is een reden waarom het moment in de GGZ-transformatiesessie zo krachtig was (het Mentaal Gezondheidsnetwerk met dertig stakeholders): mensen zagen hun woorden *direct* terug.

Real-time feedback doet iets met eigenaarschap dat vertraagde feedback niet kan. Wanneer je je woorden direct terugziet, is de verbinding tussen spreken en resultaat nog vers. Je herkent niet alleen de woorden; je herkent het moment. "Dat zei ik net. En nu staat het hier."

Dit is waarom de live-reflectie werkt. Waarom live synthese impact heeft die een rapport nooit zal hebben. De snelheid is niet voor efficiëntie. De snelheid is voor eigenaarschap.

Maar (en dit is cruciaal) snelheid zonder taalbehoud heeft weinig zin. Een snelle synthese in consultant-taal stimuleert geen eigenaarschap. Het moet beide zijn: snel én in hun woorden.

---

## Gerelateerde technieken

- [Transcriptie als fundament](transcriptie.md): waar dit allemaal mee begint
- [Brondocument-stijl klonen](brondocument-stijl.md): wanneer je ook structuur en toon moet overnemen
- [Live reflectie met AI](../fase-2/echo-knop.md): real-time toepassing van taalbehoud

---

**Navigatie:**
- [Terug naar Fase 1: Begin](../../fase-1-begin.md)
- [Vorige: Transcriptie](transcriptie.md)
- [Volgende: Brondocumentstijl](brondocument-stijl.md)

---

*De woorden van deelnemers zijn niet alleen informatie, ze zijn eigenaarschap.*
