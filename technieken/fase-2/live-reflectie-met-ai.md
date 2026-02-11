	# Live reflectie met AI

> *Op precies het juiste moment stelt AI de vraag die de groep verder helpt.*

**Fase:** [Fase 2: Verdieping](../../fase-2-verdieping.md)
**Bouwt voort op:** Transcriptie als grondstof, nu gebruikt voor real-time interventie

---

## Wanneer is dit relevant?

**Situatie:** Je faciliteert een gesprek. De energie zakt, mensen herhalen zichzelf, het gesprek draait in cirkels. Of: er is spanning voelbaar die niemand benoemt.

**Mijn neiging:** Ik word steeds beter in mijn intuïtie vertrouwen en dingen expliciet benoemen. Tegelijkertijd twijfel ik nog wel eens — en hoop ik dat iemand anders het benoemt.

**Wat hier helpt:** Als je het even niet weet, of als je weet wat er achter de echo-knop zit, dan heb je een co-facilitator die met het hele transcript kan werken. Als mens heb je beperkte opslag in je brein, hoe aandachtig je ook luistert. De echo-knop kijkt vanuit een ander perspectief naar het gesprek en kan je op die manier helpen.

**De vraag:** Wat zou er gebeuren als je op dat moment een extra set ogen had — een co-facilitator die het hele gesprek heeft gehoord?

---

## De vraag die het gesprek opende

*Dit verhaal ken je misschien al van de [waarom-pagina](../../waarom.md). Hier gaan we dieper in op timing: het juiste moment voor de juiste vraag.*

Een sessie over wijktransformatie. Acht mensen praten 45 minuten over de spanning tussen systeemeisen en mensgerichte aanpak. De energie begint weg te zakken.

Facilitator Jeroen drukt op de echo-knop. Binnen 10 seconden genereert AI deze vraag:

> "Gezien de uitdagingen die jullie beschrijven, lijkt het cruciaal om te beginnen met kleine haalbare stappen die direct impact hebben in de wijk. Kunnen we een voorbeeld bedenken van zo'n concrete actie die we morgen al zouden kunnen starten, zonder dat we vastlopen in systeemeisen?"

De reactie was onmiddellijk.

> "Dit is wel mooi."
> "Dat is de welbekende, hoe gaan we morgen starten met iets kleins?"
> "Mooi gedaan!"
> "Ja, dat is het."

10 seconden. Eén vraag. Het gesprek dat vastzat, kwam in beweging.

---

## Live versus semi-live

Er is een belangrijk onderscheid in hoe je AI inzet tijdens sessies.

**Live (de echo-knop):**
Direct in de sessie, met één druk op de knop. AI analyseert de laatste minuten en genereert onmiddellijk een vraag. Dit werkt met tools als Dembrane die real-time transcriptie koppelen aan prompt-functionaliteit.

**Semi-live (breakout-momenten):**
Tussen blokken door. Bijvoorbeeld: terwijl groepen in breakout-sessies werken, neem je het transcript tot dan toe, voer je een langere prompt uit, en kopieer je de output naar een Google Doc die de facilitator daarna op scherm kan tonen aan de groep.

Het verschil zit in de snelheid en de context:
- **Live:** Seconden. Werkt op de laatste minuten. Geschikt voor interventie in het moment.
- **Semi-live:** 1-2 minuten, afhankelijk van je werkwijze. Werkt op langere segmenten. Geschikt voor tussentijdse synthese en terugkoppeling.

Beide vereisen voorbereiding: je prompts moeten klaarstaan. Het verschil is wanneer je ze inzet en hoeveel stappen er tussen zitten — van prompt uitvoeren tot iets op het scherm tonen aan de groep:

prompt uitvoeren → output kopiëren → plakken in document → tonen aan groep

Hoe minder tussenstappen, hoe sneller.

---

## Wat maakt de echo-knop anders?

De echo-knop is geen samenvatting. Het is een (mini-)interventie.

**Samenvatting:** "Jullie hebben gepraat over X, Y en Z."
**Echo:** "Jullie hebben het veel over 'communicatieproblemen' — wat bedoelen jullie precies? Kan iemand een concreet moment beschrijven?"

Het verschil zit in de vraag. Een samenvatting sluit af. Een echo opent.

**De drie niveaus:**
| Niveau | Wat het doet | Voorbeeld |
|--------|--------------|-----------|
| **Spiegel** | Reflecteert wat gezegd is | "Jullie noemden X, Y en Z" |
| **Synthese** | Verbindt patronen | "Wat opvalt: iedereen noemt 'tijd' maar bedoelt iets anders" |
| **Serendipity** | Stelt de vraag die niet gesteld werd | "Wat zou er veranderen als X niet het probleem was?" |

Echo werkt op synthese en serendipity niveau. Het verbindt én vraagt door.

---

## De prompt

Dit is de werkende echo-prompt uit de Doesburg bestuurders-workshop.

```
**Rol:** Je bent een ervaren groepsdynamiek-expert die signalen van
vermeden onderwerpen, onuitgesproken spanningen en verschillende
perspectieven detecteert in dialogen.

**Context:** Je analyseert de laatste 10-15 minuten van een
[TYPE SESSIE]. Deelnemers zijn [WIE]. Ze kennen elkaar [RELATIE].

**Vereiste Stijl:**
- Niet-oordelend en uitnodigend
- Focus op wat ontbreekt, niet op wat fout is
- Herken diplomatieke taal die onderliggende spanningen maskeert

**Cruciale Randvoorwaarden:**
- Baseer signalen strikt op transcript, geen veronderstellingen
- Onderscheid tussen stilte en consensus
- Bij twijfel: "Mogelijk onderbelicht" ipv stellige bewering
- Genereer maximaal 2 echo-vragen voor facilitator
- Focus op laatste deel van gesprek

**Instructies:**
1. Analyseer de laatste 10-15 minuten van het transcript
2. Identificeer onderwerpen die opgeroepen maar niet uitgediept werden
3. Detecteer momenten waar energie wegviel of onderwerp verschoof
4. Zoek verschillen in framing tussen deelnemers
5. Herken "ja, maar..." patronen als signaal voor spanning
6. Kies één krachtige echo-vraag die het belangrijkste adresseert

**Output Format:**
### Wat Ik Waarneem
**Mogelijk onderbelicht:** [Onderwerpen die niet uitgediept werden]

**Verschillende framingen:**
- "Quote over hoe dit gezien wordt"
- "Quote die anders nuanceert"

### Echo-vraag voor de Groep
**[Eén krachtige vraag die uitnodigt tot verdieping]**

### Over Deze Echo
Deze echo is een hulpmiddel om mogelijke blinde vlekken te belichten,
niet om te oordelen. De keuze om hier op in te gaan blijft bij jullie.
```

**Bron:** Prompt die ik gebruik bij live groepsreflectie (Doesburg bestuurders-workshop)

**Waarom deze structuur werkt:**
- **Rol** definieert expertise: "groepsdynamiek-expert" stuurt naar detectie van wat niet gezegd wordt
- **Context** maakt specifiek: "laatste 10-15 minuten" voorkomt dat AI alles probeert te vangen
- **Vereiste Stijl** bewaakt de toon: "niet-oordelend" voorkomt dat echo als kritiek voelt
- **Cruciale Begrenzingen** zijn de harde grenzen: "maximaal 2 echo-vragen" voorkomt overweldiging
- **Instructies** sturen het zoekproces: de volgorde (eerst analyseren, dan detecteren, dan kiezen) geeft focus
- **Output Format** structureert de output: "Eén krachtige vraag" dwingt selectie af

---

## Drie tactieken

**VERDIEPEND:**
Gebruik wanneer het gesprek aan de oppervlakte blijft. Mensen noemen symptomen maar niet onderliggende zorgen.

> "Jullie hebben het veel over 'communicatieproblemen' — wat bedoelen jullie precies als jullie dat zeggen? Kan iemand een concreet moment beschrijven?"

**CONCRETISEREND:**
Gebruik wanneer het gesprek abstract blijft: veel theorie maar geen concrete volgende stappen.

> "Gezien wat jullie delen, wat zou een eerste kleine stap kunnen zijn die morgen al gezet kan worden?"

**REFLECTEREND:**
Gebruik wanneer de verbinding tussen perspectieven ontbreekt.

> "Ik hoor dat Tafel Rood 'meer tijd' wil, maar Tafel Blauw zegt 'te veel overleg' — zou 'tijd' voor beide groepen iets anders kunnen betekenen?"

---

## Wanneer wel, wanneer niet

**Wanneer WEL:**

| Signaal | Wat je doet |
|---------|-------------|
| Energie zakt, gesprek draait in cirkels | Echo met concretiserende vraag |
| Einde sessie, groep heeft geen helder beeld | Echo met reflecterende vraag |
| Spanning voelbaar maar onbenoemd | Echo met verdiepende vraag |
| Nieuwe fase begint, brug nodig naar vorige | Echo als opening |

**Wanneer NIET:**

| Signaal | Waarom niet |
|---------|-------------|
| Iemand deelt persoonlijk verhaal | Ruimte voor emotie IS de interventie |
| Eerste sessie, je kent de groep nog niet | Echo kan mis zijn zonder begrip van context |
| Geen strategische voorbereiding | Zwakke prompts → AI beslist → substitutie-risico |
| Facilitator kijkt naar scherm ipv naar mensen | Real-time groepsdynamiek lezen is menselijk werk |

---

## De rol-verdeling

Dit werkt het beste met twee mensen:

**Facilitator:** Blijft bij de groep. Leest gezichten, houdt emoties, begeleidt het proces. Kijkt niet naar een scherm.

**Co-facilitator:** Monitort de transcriptie, selecteert de laatste minuten, lanceert de echo-prompt, doet snelle iteraties als nodig.

Wanneer de echo klaar is, leest de facilitator hem voor in eigen woorden, niet letterlijk. De echo is een suggestie, geen script.

---

## Spanningen

**Timing van interventie**
Te vroeg voelt als onderbreking. Te laat is de energie al weg.

*Mijn aanpak:* Ik wacht tot ik voel dat de groep ergens vastzit. Of tot ik zelf even twijfel en niet weet hoe verder — dan is de echo een hulpje.

**AI-taal versus eigen stem**
Wat AI genereert is een suggestie, geen script. Letterlijk voorlezen kan mechanisch overkomen — maar als de voorbereiding zorgvuldig was, mag het ook.

*Mijn aanpak:* Ik parafraseer meestal in mijn eigen woorden. Maar als ik de echo-prompt goed heb voorbereid, lees ik soms ook letterlijk voor.

**Spontaan versus voorbereid**
De vraag die "mouths falling open" veroorzaakte, kwam niet uit het niets. Er zat strategische voorbereiding achter.

*Mijn aanpak:* 80% van het succes zit in voorbereiding. Ik ontwerp de echo-prompt vooraf op basis van wat ik verwacht.

**Echo als vervanging voor faciliteren**
De echo is een tool, geen oplossing. Als ik alleen maar op knoppen druk, mis ik wat er in de kamer gebeurt.

*Mijn aanpak:* Ik blijf present. De echo ondersteunt mijn waarneming, vervangt hem niet.

---

## Veilige defaults

*Voor privacy-afwegingen bij live transcriptie, lees [Veilig werken met AI](../../veilig-werken.md).*

- [ ] Focus op laatste 10-15 minuten? (niet het hele gesprek)
- [ ] "Mogelijk onderbelicht" in plaats van stellige beweringen?
- [ ] Maximaal 2 echo-vragen? (niet overweldigen)
- [ ] AI-observaties gelabeld als AI?
- [ ] Strategische voorbereiding gedaan?

---

## Tools

| Tool | Waarvoor | Nuance |
|------|----------|--------|
| **Dembrane** | Real-time transcriptie + echo-knop functionaliteit | Geschikt voor meerdere sessies: alles gecentraliseerd naar één platform |
| **Notion AI** | Live transcriptie + AI-prompts op de pagina | Goed voor één meeting waar je zelf in zit |
| **MacWhisper + Claude/ChatGPT** | Zelf transcriberen + echo-prompt handmatig uitvoeren | Meest flexibel, meeste handwerk |

**Wanneer welke tool:**
- **Eén meeting, jij bent erbij:** Notion AI werkt prima. Je neemt op, transcript verschijnt, je prompt AI direct op diezelfde pagina.
- **Meerdere sessies, breakout-groepen, of je faciliteert:** Dembrane. Je kunt verschillende opnames naar één plek sturen en centraal analyseren.

---

## Filosofische verdieping

### Timing boven perfectie

De echo-vraag in de wijktransformatie-sessie was niet bijzonder complex. "Kleine haalbare stappen", "morgen al kunnen starten", "zonder vast te lopen in systeemeisen": dit zijn geen diepgravende inzichten.

Wat het bijzonder maakte was de timing. Na 45 minuten discussie, op het moment dat de energie zakte, kwam precies de vraag die de groep nodig had.

Dit is het verschil tussen analyse en interventie. Een perfecte analyse een week later had minder impact gehad dan een goede vraag op het juiste moment.

### De echo als spiegel

Er is nog iets. Wanneer AI de vraag stelt, is het niet "de facilitator die vindt dat..." Het is een externe spiegel. Mensen reageren anders op een vraag die uit de AI komt dan op dezelfde vraag van de facilitator.

Soms is dat afstand nodig. De vraag wordt neutraal, onderzoekend, niet oordelend.

Maar (en dit is cruciaal) de facilitator moet de vraag eigendom maken. Niet: "AI zegt dit." Wel: "Er komt een vraag naar boven die ik interessant vind..." De echo is input, de facilitator is de stem.

---

## Gerelateerde technieken

- [Transcriptie als fundament](../fase-1/transcriptie.md): waar de grondstof vandaan komt
- [Iteratie](iteratie.md): hoe je de echo-prompts zelf ontwikkelt
- [Intuitie zwart op wit](intuitie-zwart-op-wit.md): patronen zichtbaar maken die je al voelde

---

← [Terug naar Fase 2: Verdieping](../../fase-2-verdieping.md) | [← Vorige: Vragen herkaderen](vragen-herkaderen.md) | [Volgende: Van gesprek naar plan →](gesprek-naar-plan.md)

---

*"10 seconden kan 45 minuten dialoog transformeren. Niet door de perfecte vraag, maar door de vraag op het perfecte moment."*
