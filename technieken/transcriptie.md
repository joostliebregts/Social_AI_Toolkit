# Transcriptie als fundament

> *Alles begint met tekst. Transcriptie maakt het vluchtige tastbaar.*

**Fase:** [Fase 1: Begin](../fase-1-begin.md)
**Dit is het fundament:** zonder tekst geen verdieping

---

## Waarom dit het fundament is

Je kent het moment. Een gesprek is net afgelopen. Je weet dat er iets belangrijks is gezegd, maar je kunt het niet meer exact reconstrueren.

Dat geldt voor een één-op-één gesprek. Maar ook voor teamoverleggen en workshops. Je had je aantekeningen, je gedeelde herinneringen, je samenvatting achteraf.

Maar er is iets veranderd.

We kunnen nu transcripten maken. Snel, goedkoop, goed genoeg. Alles wat er gezegd is, vastgelegd als tekst.

En dat stelt een vraag: wat kun je daar eigenlijk mee, in een sociale setting?

Dat is waar deze toolkit over gaat. Transcriptie als ruwe olie. Grondstof voor van alles: collectieve wijsheid vangen, patronen blootleggen, je eigen intuïtie checken, groeien als facilitator door terug te kijken naar wat je anders had kunnen doen.

**Daarom staat deze pagina vooraan.** Niet omdat transcriptie de meest spectaculaire techniek is, maar omdat alles wat volgt ermee begint.

---

## Waar het allemaal mee begint

In [Fase 1](../fase-1-begin.md) las je al over Maarten en de ouderavond over smartphonevrij opgroeien. Het fietshelm-moment: AI vond de quote die precies de kern raakte.

Hier gaan we dieper in op wat dat mogelijk maakte, en hoe je het zelf kunt toepassen.

---

## Wat maakt transcriptie nu anders?

Tot voor kort was transcriptie duur, traag of onnauwkeurig. Je moest kiezen: betalen voor een professionele notulist, uren besteden aan zelf uittypen, of leven met matige automatische transcriptie.

Dat is voorbij.

**De drempel is nu bijna nul:**
- Kosten: €0-1 voor een uur audio
- Tijd: 1-2 minuten voor een uur gesprek (met nieuwere transcriptie-modellen)
- Kwaliteit: 80%+ nauwkeurigheid, ook voor Nederlands. (Ik heb het nog niet meegemaakt dat dat niet goed genoeg was voor mijn doeleinden)
- Privacy: Lokale tools bestaan: niets hoeft naar de cloud

Dit verandert de fundamentele vraag. Niet meer: "Is het de moeite waard om dit te transcriberen?" Maar: "Wat wil ik doen met deze tekst?"

---

## Van opname naar transcript: de workflow

### Stap 1: Opnemen met toestemming

Dit klinkt vanzelfsprekend, maar het begint hier. Vraag expliciet toestemming aan het begin van elke sessie.

Een simpele formulering:

> "Ik neem dit gesprek op zodat we later terug kunnen kijken naar wat er gezegd is. De audio opname blijft bij mij en het transcript wordt alleen gebruikt voor [doel]. Is dat voor iedereen oké?"

Let op non-verbale signalen. Niet iedereen zegt hardop als ze oncomfortabel zijn.

### Stap 2: Transcriberen

Kies een tool die past bij je situatie:

| Tool                         | Wanneer kiezen                                                                                      |
| ---------------------------- | --------------------------------------------------------------------------------------------------- |
| **MacWhisper**               | Privacy belangrijk, je wilt lokaal transcriberen of dicteren.                                       |
| **Dembrane**                 | Real-time transcriptie tijdens de sessie, directe synthese mogelijk                                 |
| **Notion AI**                | Je werkt al in Notion, wilt alles op één plek, werkt zowel in het Engels als Nederlands             |
| **Google Meet transcriptie** | Je werkt al in Google ecosystem, basis is genoeg (let op: vooralsnog geen Nederlandse transcriptie) |

*Zie de [tools-pagina](../tools.md) voor meer details over deze en andere tools.*

Voor de meeste facilitators (met een Mac) is MacWhisper een goede start: het werkt lokaal (privacy), heeft een gratis versie waarmee je al veel kan, de pro versie is 'betaal één keer', levert goede Nederlandse transcripties, en heeft ingebouwde dictatie.

### Stap 3: Checken en opschonen

Transcripties zijn niet perfect. Check altijd op:
- **Namen:** AI raadt vaak verkeerd. 
- **Jargon:** Vaktermen worden soms verkeerd getranscribeerd.
- **Cruciale passages:** Check quotes die je wilt gebruiken op exactheid.

Je hoeft niet het hele transcript te corrigeren. Focus op wat je gaat gebruiken. En zodra je met het transcript gaat werken, geef de AI het transcript met correctie-context erbij. Bijvoorbeeld:

> "Dit transcript bevat vaktermen en namen die mogelijk verkeerd zijn getranscribeerd: 'POH-GGZ' (niet 'P.O. Achates'), 'Rianne' (niet 'Rijanne'), 'GALA' (niet 'gala')."

### Stap 4: Gebruiken met intentie

Dit is waar het echte werk begint. De vraag is niet "wat kan ik met dit transcript?" maar "wat wil ik bereiken?"

- Wil je de groep hun eigen woorden terugspiegelen? → [Taal als eigenaarschap](taal-behouden.md)
- Wil je patronen zichtbaar maken? → [Intuïtie zwart op wit](intuitie-zwart-op-wit.md) (Fase 2)
- Wil je actiepunten? → Zie de Kernbesluiten prompt hieronder
- Weet je het nog niet? → Archiveer het transcript, kom er later op terug

---

## Vier manieren om transcriptie te gebruiken

Dit is de eerste pagina in deze toolkit waar we echt met AI aan de slag gaan. Tot nu toe ging het over waarom en hoe. Nu wordt het concreet: wat doe je eigenlijk met zo'n transcript?

Er zijn ontelbaar veel mogelijkheden. Maar in mijn werk komen vier patronen steeds terug:

### 1. Vastleggen wat je niet kon horen

Dit is de meest basale toepassing, en daarom staat hij vooraan. Je kunt niet alles meekrijgen als je faciliteert. Je mist subtiliteiten terwijl je nadenkt over de volgende vraag. Je hoort een krachtige opmerking, maar voordat je hem opschrijft is de volgende spreker al bezig.

Transcriptie is je vangnet. Niet als vervanging voor aandacht, maar als backup voor wanneer aandacht niet genoeg is.

**Prompt voor het vinden van wat je miste:**

De prompt hieronder is uitgebreider dan je misschien verwacht voor "vastleggen wat je niet kon horen". Dat is bewust. Dit is de daadwerkelijke prompt die Maarten en ik gebruikten na de ouderavond over smartphonevrij opgroeien. Hij laat zien hoe je in één keer van transcript naar bruikbare inzichten gaat: niet alleen wat er gezegd is, maar ook hoe je het kunt gebruiken in vervolgesprekken.

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

**Waarom deze structuur werkt:**
De rol ("systemisch strateeg en gemeenschapsbouwer") stuurt AI's perspectief: verbinding zoeken, niet kritiek leveren. De randvoorwaarden beschermen de authenticiteit: letterlijke bewoordingen gebruiken, geen echte namen, empathische toon. De twee heatmaps dwingen AI om zowel de emoties (zorgen) als de energie (actiebereidheid) te analyseren. En de gesprekswaaier vertaalt inzichten naar iets bruikbaars: concrete haakjes voor echte gesprekken.

### 2. Taal als eigenaarschap

Als het eerste patroon gaat over wat je miste, gaat dit over wat je wél hoorde maar dreigt te verliezen: de exacte woorden.

Er is een cruciaal verschil tussen "communicatieproblemen" en "je praat tegen een muur". Het eerste is een interpretatie. Het tweede is wat iemand echt zei.

Wanneer mensen hun eigen woorden terugzien, ervaren ze dat hun bijdrage er werkelijk toe deed. Ze voelen zich gehoord: niet samengevat, niet geïnterpreteerd, maar gehoord. En dat opent de deur naar eigenaarschap. Het gevoel dat dit ook van hen is, niet alleen van de facilitator of de organisatie.

Een deelnemer die leest "we moeten stoppen met vergaderen over vergaderen" denkt: *ja, dat zei ik*. Diezelfde deelnemer die leest "inefficiente meetingstructuur" denkt: *dat is wat een consultant ervan maakte*.

Transcriptie helpt de originele taal te bewaren. Dat is de grondstof voor alles wat volgt.

**De uitwerking:** Voor de volledige techniek en prompts over taal behouden, zie [Taal als eigenaarschap](taal-behouden.md).

### 3. Structuur extraheren

De eerste twee patronen gaan over inhoud: wat werd er gezegd, in welke woorden. Dit derde patroon is praktischer: wat werd er besloten?

Soms wil je geen verrijking of verdieping, maar simpelweg overzicht. Wat is er besloten? Wie doet wat? Welke vragen bleven open?

Dit is misschien het meest voor de hand liggende gebruik van transcriptie. Veel mensen beginnen hier: administratie automatiseren zodat je ruimte hebt voor ander werk. En dat is prima. Maar in deze toolkit staat het op plek drie, omdat de eerste twee patronen laten zien wat er nog meer mogelijk is.

**AI helpt de prompt maken:**

Tegenwoordig kun je AI ook de prompt laten schrijven. Geef het transcript en je wensen, en vraag om een passende prompt. Na een meeting vroeg ik AI:

> "Als de meeting voorbij is, wat is dan de goede prompt om de best passende samenvatting en notulen te hebben, voor zowel aanwezigen als afwezigen (Anna en Lisa)?"

AI genereerde een prompt met structuur (in het kort, terugblik, beslissingen, actiepunten, voor afwezigen) en de instructie om het taalgebruik van de deelnemers te behouden. Dit is een interessant patroon: AI helpt de prompt maken op basis van context.

**Kernbesluiten Capture:**

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

**Waarom deze structuur werkt:**
De rol ("nauwkeurige notulist") houdt AI bij wat letterlijk besloten is. De randvoorwaarden voorkomen impliciete conclusies. Het output format is verrassend krachtig: AI volgt dit vrij precies.

### 4. Dictatie: je eigen gedachtenstroom vastleggen

De eerste drie patronen gaan over gesprekken met anderen. Dit vierde patroon is anders: het gaat over jouw eigen gedachten.

Transcriptie gaat niet alleen over gesprekken met anderen. Het gaat ook over je eigen gedachten vastleggen.

Met dictatie spreek je je gedachten uit en binnen een seconde staan ze er als tekst. Dit gaat veel sneller dan typen; het verandert hoe je met AI werkt.

**Wanneer dit waardevol is:**
- Bij het itereren met AI: je dicteert je feedback, plakt het in de chat
- Bij het verwerken van sessies: je spreekt je observaties in terwijl ze vers zijn
- Bij het voorbereiden: hardop denken, later structureren

Veel van mijn werk met AI is inmiddels: dicteren → AI → dicteren → AI. De drempel om gedachten vast te leggen wordt bijna nul.

#### MacWhisper: de tool die dit mogelijk maakt

MacWhisper verdient extra aandacht omdat het een fundamenteel andere aanpak is; én omdat het dictatie ondersteunt.

**Hoe het werkt:**
Je downloadt een AI-model naar je Mac. De transcriptie gebeurt volledig lokaal: geen audio gaat naar servers, geen tekst gaat naar de cloud.

**Snelheid:**
Met nieuwere modellen (zoals Parakeet 3) kan een uur audio in 1-2 minuten getranscribeerd zijn. De oude aanname dat lokaal langzamer is, geldt steeds minder.

**Dictatie:**
MacWhisper heeft ook een dictatiefunctie. Je spreekt, stopt, en binnen een seconde staat alles als tekst. Dit is hoe ik de meeste van mijn AI-interacties doe.

**Wanneer kiezen:**
- Privacy-gevoelige gesprekken
- Je wilt ook dicteren
- Je werkt op een Mac

**Windows-alternatief:** Voor Windows-gebruikers is er [Handy](https://github.com/cjpais/handy), een open-source tool met vergelijkbare dictatiefunctionaliteit.

#### Hardware: van prima naar goed

Dictatie werkt prima met de ingebouwde microfoon van je laptop. Maar als je het regelmatig doet, kan betere hardware het verschil maken.

**Wat ik gebruik:**

- **[DJI Mic Mini](https://www.dji.com/nl/mic-mini)**: Draadloze lavalier mic. Mijn favoriet. Werkt zowel voor dictatie als voor het opnemen van gesprekken met twee mensen (de set heeft twee zenders). Plug and play via USB-C.

- **[Rode VideoMicro](https://rode.com/en-us/products/videomicro)**: Kleine shotgun mic die ik als backup bovenop mijn monitor heb staan. Simpel, geen batterijen nodig, goede kwaliteit voor de prijs.

Dit is geen vereiste. Begin gewoon met je ingebouwde microfoon. Maar als je merkt dat transcriptiekwaliteit tegenvalt, of dat je in rumoerige omgevingen werkt, kan hardware helpen.

---

## Bouwen op transcriptie

Hierboven las je vier manieren om transcriptie te gebruiken. Maar er zijn technieken die verder gaan: die voortbouwen op transcriptie als fundament. Als je de toolkit chronologisch doorwerkt, kom je ze vanzelf tegen:

**Samen graven naar wat erin zit**
Een transcript bevat meer dan je in het moment kon bevatten. Stel je voor: je gaat samen met AI op zoek naar structuur, haakjes voor verbinding, krachtige quotes.
→ *[Wat er nog meer in zat](wat-er-nog-meer-in-zat.md)* (Fase 2)

**Patronen zien over meerdere gesprekken**
Eén transcript is een momentopname. Vijf transcripten over drie maanden laten ontwikkeling zien: hoe taal verschuift, welke thema's terugkomen, waar doorbraken ontstaan of juist uitblijven.
→ *[Patronen over tijd](patronen-over-tijd.md)* (Fase 3)

**Onverwachte verbindingen vinden**
Twee mensen die dezelfde worsteling delen zonder het van elkaar te weten. Twee ouders (van verschillende kinderen) bleken allebei te worstelen met speelafspraakjes die alleen maar om gamen draaien. AI destilleerde het haakje: "Sta jij ook alleen in dat Minecraft-gesprek?" Niet een samenvatting. Een brug.
→ *[Haakjes vinden](haakjes-vinden.md)* (Fase 3)

---

## Spanningen

Bij elke techniek in deze toolkit beschrijf ik de spanningen die ik tegenkom. Niet als valkuilen die je moet vermijden, maar als keuzes die je steeds opnieuw maakt. Wat werkt, hangt af van de situatie.

**Vastleggen is nog geen gebruiken**
De drempel voor transcriptie is zo laag dat het bijna vanzelfsprekend voelt om alles op te nemen en te transcriberen. Het transcript is er. Dat voelt als vooruitgang. Maar zonder vervolgstap verzamelt het stof.

*Mijn aanpak:* Vaak heb ik al tijdens het transcriberen een idee van wat ik ermee wil. Welke prompt ga ik erop loslaten? Wat wil ik eruit halen? Soms is het antwoord: ik weet het nog niet, dit is archivering. Dat is prima, maar dan noem ik het ook zo. En als ik wel een richting heb, probeer ik snel iets kleins te doen: vijf quotes markeren, AI een patroon laten zoeken. Kleine acties houden transcripten levend.

**Polijsten versus authenticiteit**
De neiging om taal "professioneler" te maken. Dit is zó belangrijk dat het een eigen pagina heeft: [Taal als eigenaarschap](taal-behouden.md).

**Gemak versus privacy**
De tools zijn zo makkelijk. Upload, klik, klaar. Maar niet elk gesprek hoort in de cloud.

*Mijn aanpak:* Ik maak een bewuste keuze per gesprek. Intern of gevoelig? Dan lokaal (MacWhisper). Extern of openbaar? Dan kan cloud. Bij twijfel kies ik lokaal. Het helpt ook om voor jezelf helder te hebben wat je met het transcript wilt, zodat je het goed kunt verwoorden naar anderen als je toestemming vraagt.

---

## Veilige defaults

Bij elke techniek in deze toolkit geef ik een checklist van dingen om te checken voordat je begint. Niet als bureaucratie, maar als snelle scan: heb ik aan de belangrijkste dingen gedacht?

*Zie ook: [Veilig werken met AI](../veilig-werken.md)*

Elke keer dat je een transcript gebruikt voor AI-analyse, check:

- [ ] **Strikt op transcript?** Heb je de constraint "baseer je strikt op wat er staat" toegevoegd?
- [ ] **Geen verzinsels?** Vraagt de prompt om "bij twijfel: nog te bevestigen"?
- [ ] **Taal behouden?** Is de instructie om letterlijk te citeren expliciet?
- [ ] **Privacy gecheckt?** Is dit transcript geschikt voor de tool die je gebruikt?
- [ ] **Doel helder?** Weet je wat je wilt bereiken voordat je begint?

---

## Filosofische verdieping

### Het principe: strikt op transcript

Er is een fundamentele spanning in werken met AI en gesprekken. AI kan patronen vinden, verbanden leggen, interpretaties maken. Maar niet elke interpretatie is gegrond in wat er daadwerkelijk gezegd is.

De afkadering "strikt op transcript: geen verzinsels" is geen beperking. Het is een bescherming.

**Wat dit betekent in de praktijk:**

```
❌ "De groep voelde frustratie over het management"
✅ "Drie mensen gebruikten woorden als 'muur', 'niet gehoord', 'zinloos'"

❌ "Er is consensus over de richting"
✅ "Vijf van de zeven sprekers noemden 'lokaal beginnen' als eerste stap"

❌ "De sfeer was negatief"
✅ "De woorden 'niet', 'kan niet', 'onmogelijk' kwamen 23 keer voor"
```

AI observeert wat er staat. Niet wat mensen "eigenlijk" bedoelden, niet wat ze "voelden", niet wat ze "zouden moeten" denken.

Dit is een fundament. Als je niet vertrouwt wat er staat, is het lastig om erop verder te bouwen. Niet onmogelijk, maar je moet dan constant checken.

### Waarom dit ertoe doet

Wanneer je een synthese deelt en iemand zegt: "Maar dat heb ik niet gezegd", dan is het vertrouwen weg. Niet alleen in de synthese, maar in het hele proces.

Omgekeerd: wanneer je een synthese deelt en mensen zeggen: "Ja, dit zijn wij", dan groeit eigenaarschap. Niet omdat de synthese perfect is, maar omdat hij herkenbaar is.

De kracht van transcriptie ligt niet in de technologie. Die is nu bijna gratis. De kracht ligt in wat je ermee doet: mensen hun eigen woorden teruggeven.

---

## Gerelateerde technieken

- [Taal behouden](taal-behouden.md): Hoe je ervoor zorgt dat de woorden van deelnemers intact blijven in AI-output
- [Brondocument-stijl klonen](brondocument-stijl.md): Als je transcript naar een formeel document moet dat stakeholders accepteren
- [Live reflectie met AI](echo-knop.md): Live transcriptie gebruiken voor directe interventies

---

<- [Terug naar Fase 1: Begin](../fase-1-begin.md) | [Volgende: Taal als eigenaarschap ->](taal-behouden.md)

