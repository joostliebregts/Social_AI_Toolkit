# Wat er nog meer in zat

> *Samen met AI verdieping zoeken in je transcript.*

**Fase:** [Fase 2: Verdieping](../../fase-2-verdieping.md)
**Bouwt voort op:** [Transcriptie als fundament](../fase-1/transcriptie.md), samen graven naar wat erin zit

---

## Wanneer is dit relevant?

**Situatie:** Je hebt een sessie gehad, misschien een van de [verdiepingssessies uit Fase 2](../../fase-2-verdieping.md). Het gesprek was waardevol. Maar je weet: er zit meer in dan wat je direct kunt benoemen.

**De neiging:** Vertrouwen op wat je onthield. Of een snelle samenvatting maken en door naar het volgende.

**Het principe:** Het transcript is geen eindproduct; het is ruwe olie. Met de juiste vragen kun je er meer uithalen dan je live kon bevatten. Niet omdat je iets miste, maar omdat er simpelweg meer in zit dan één persoon in één moment kan verwerken.

**De vraag:** Wat zou er boven komen als je samen met AI gaat graven?

---

## Het verhaal: samen verdieping zoeken

*Dit verhaal over de online bijeenkomst ken je misschien al van [Fase 1](../../fase-1-begin.md). Hier gaan we dieper in op hoe we samen met AI de verdieping zochten.*

Maarten organiseerde een online bijeenkomst over smartphonevrij opgroeien. Veertien ouders deelden hun worstelingen over schermtijd, gaming, en het gevoel er alleen voor te staan. Waardevol mensenwerk.

Na afloop wilde hij er meer uithalen. Niet omdat hij iets gemist had, maar omdat hij wist dat er patronen in zaten die hij niet direct kon benoemen.

Hij kwam bij mij. We gingen samen aan de slag.

**Het proces:**
1. Ik transcribeerde ons gesprek live met Notion AI
2. Gaf dat aan AI met de vraag: "Help me hier een analyse-prompt voor te bouwen"
3. AI stelde drie vragen met elk twee opties
4. Maarten gaf richting én nuance

**De vragen die AI stelde:**

> "Focus op de emotionele leefwereld OF de actiebereidheid?"

Maarten: "Ik wil allebei. De actiebereidheid vloeit voort uit de emotionele leefwereld."

> "Frame vanuit hypocrisie/schuldgevoel OF vanuit de wens goed ouder te zijn?"

Maarten: "Vanuit het positieve. Mensen stimuleren veel meer vanuit wat ze willen dan vanuit schuld."

> "Output als gesprekswaaier (haakjes voor verbinding) OF als campagnemonitor (gaten en kansen)?"

Maarten: "100% gesprekswaaier. Verbinding maken is het allerbelangrijkste. De haakjes wil ik hebben, maar ik bepaal zelf hoe ik ze deel."

**Wat er boven kwam:**

Concrete haakjes voor gesprekken met andere ouders. Momenten uit het gesprek die mensen konden verbinden, als Maarten ze wist te vinden.

En één quote die de kern raakte:

> "Je kind gaat voor het eerst met de fiets naar school, helm op. Komt thuis en zegt: 'De hele klas heeft geen helm. Doe ik ook niet meer, anders hoor ik er niet bij.'"

Dit zat in het transcript. Door samen te graven kwam het naar boven, klaar om mee verder te gaan.

**Bron:** Het iteratie-gesprek en Maarten's Substack: [Wat ik niet hoorde in mijn eigen meeting](https://kampvuur.substack.com/p/wat-ik-niet-hoorde-in-mijn-eigen)

---

## De prompt-aanpak

Hieronder de prompts die we daadwerkelijk gebruikten in het verhaal hierboven.

### Stap 1: Vraag AI om te helpen een prompt te bouwen

In plaats van direct een analyse-prompt te schrijven, vroeg ik AI om mee te denken:

```prompt
Zojuist had ik het met Maarten over hun traject over smartphonevrij
opgroeien. Wat ik je heb toegevoegd is context over hoe Maarten
die meeting heeft voorbereid — zijn wensen en intenties — en het
transcript van de meeting zelf.

Waar we naar op zoek zijn is een prompt waarmee we het transcript
kunnen analyseren. Om Maarten te helpen in zijn missie.

Voordat we die prompt opstellen zou ik het fijn vinden als je ons
nog een aantal vragen kunt stellen om de prompt te verscherpen.
Stel ons drie vragen, steeds met twee opties.

En nog een heel belangrijk element: we spreken altijd in de taal
van de deelnemers, gericht op herkenbaarheid. En we blijven weg
bij individuele namen.
```

*Bron: De openingsprompt waarmee we het iteratie-gesprek begonnen.*

### Stap 2: Maarten geeft richting

AI stelde drie richtingsvragen (zie het verhaal hierboven). Maartens keuzes bepaalden de prompt:

- Emotionele leefwereld én actiebereidheid (niet of/of maar en/en)
- Vanuit het positieve (niet vanuit schuld)
- Gesprekswaaier (niet campagnemonitor)

Drie keer corrigeerde en nuanceerde hij. De prompt werd niet door AI bepaald; Maarten stuurde bij op basis van de voorstellen van AI.

### Stap 3: De uiteindelijke prompt

Op basis van Maartens antwoorden bouwde AI deze prompt:

```prompt
# CONTEXT & ROL
Je fungeert als een systemisch strateeg die [De Initiatiefnemer]
ondersteunt. Hij heeft een lokale werkgroep opgericht met als doel:
het smartphonegebruik bij kinderen uitstellen.

# OPDRACHT
Analyseer het transcript en creëer:
1. Een strategisch overzicht ("De Giant Map")
2. Een praktische gespreksgids ("De Gesprekswaaier")

Het doel is niet om mensen te overtuigen met feiten, maar om
verbinding te maken op basis van gedeelde waarden en zorgen.

# RANDVOORWAARDEN
- Privacy: Gebruik GEEN echte namen
- Taal: Gebruik de *letterlijke bewoordingen* van deelnemers
- Toon: Empathisch, gericht op de wens goed ouder te zijn
- Vorm: Concrete haakjes, geen letterlijke scripts

# OUTPUT (in 3 delen)

## DEEL 1: DE TWEE HEATMAPS
Per schoolfase (Kleuters vs. Middenbouw vs. Bovenbouw):
A. De Emotionele Leefwereld: angsten, twijfels, onderliggende waarden
B. De Actie-Bereidheid: waar zit de energie, wie voelt urgentie

## DEEL 2: DE INTERNE STRIJD
De spanning tussen eigen telefoongebruik en wat we willen voor
ons kind. Frame dit als uitdaging, niet als hypocrisie.

## DEEL 3: DE GESPREKSWAAIER
Concrete 'haakjes' per doelgroep voor informele gesprekken.
Focus op de gemene deler, niet op overtuigen.
```

**Waarom deze structuur werkt:**
- "Systemisch strateeg" — positioneert AI als analytisch denker, niet als samenvatter
- "Letterlijke bewoordingen" — beschermt de taal van deelnemers tegen AI-interpretatie
- "Empathisch, gericht op de wens goed ouder te zijn" — Maartens toon-correctie, ingebouwd in de prompt
- "Concrete haakjes, geen letterlijke scripts" — output die Maarten zelf kan inzetten op zijn manier

**Bron:** De prompt die we samen met AI bouwden na het iteratie-gesprek.

---

## Wat dit opleverde

De prompt leverde drie typen resultaten op. Hier laat ik per deel zien wat er boven kwam.

### De heatmaps (deel 1)

Het gesprek had een rijkdom die je live niet kon ordenen. Deel 1 van de prompt vroeg AI om structuur te zoeken: niet een samenvatting, maar ordening. Welke thema's komen terug? Hoe verhouden ze zich tot elkaar?

Wat AI vond: "heatmaps" per schoolfase. Een structuur die intuïtief aanwezig was, maar nu zwart op wit stond:

| Fase | De sfeer | Wat er speelt |
|------|----------|---------------|
| Kleuters & Onderbouw | "Het Paradijs" | Onwetendheid, voorzichtigheid: "Ben ik die zeikerd als ik er nu al over begin?" |
| Middenbouw | "De Schemerzone" | Verwarring, eerste druk: "Iedereen heeft er een, zegt mijn kind." |
| Bovenbouw | "De Realiteit" | Angst voor uitsluiting: "We zijn eigenlijk al te laat." |

Het resultaat is geen kortere versie van het gesprek; het is een kaart van wat er in zit.

### De interne strijd (deel 2)

Deel 2 zoomde in op de spanning die door het hele gesprek liep: ouders die worstelen met hun eigen telefoongebruik terwijl ze hun kinderen willen beschermen. De prompt vroeg expliciet om dit niet als hypocrisie te framen, maar als een gedeelde uitdaging.

Wat AI vond: kernthema's waarin ouders worstelen met hun voorbeeldrol. De eerlijkheid zat al in het transcript:

> "Ik ben echt vreselijk met mijn smartphone. Hoe kan ik het verbieden als ik er zelf ook op zit?"

Dit is de spiegel die niemand hardop benoemt, maar die iedereen herkent. Door deze spanning expliciet op tafel te leggen — als uitdaging, niet als aanklacht — werd het bespreekbaar.

### De gesprekswaaier (deel 3)

Deel 3 vroeg om concrete haakjes: momenten in het gesprek die mensen kunnen verbinden, als je ze weet te vinden.

Wat AI vond, concrete gespreksopeners per doelgroep:

Voor kleuterouders:
> "Nu hebben we nog de tijd om het samen te regelen, straks hoeven we die strijd niet te voeren."

Voor middenbouwouders:
> "Sta jij ook alleen in dat Minecraft-gesprek? Laten we samen optrekken."

Voor bovenbouwouders:
> "Wat zou jij anders doen met de kennis van nu?"

Twee ouders die allebei worstelen, zich allebei alleen voelen, nu een haakje hebben om elkaar te vinden.

*Wil je dit systematischer aanpakken, over meerdere gesprekken? De volledige techniek staat in [Haakjes vinden](../fase-3/haakjes-vinden.md) (Fase 3).*

### Krachtige quotes

Dit was geen apart deel in de prompt. Maar de randvoorwaarde "gebruik de letterlijke bewoordingen van deelnemers" zorgde ervoor dat AI de krachtigste uitspraken bewaarde in plaats van ze te parafraseren. Dat zie je al bij deel 2: de spiegel-quote over eigen telefoongebruik was bijvangst van een goede afkadering. Soms levert een randvoorwaarde meer op dan een expliciete opdracht.

De fietshelm-paradox:
> "Je kind gaat voor het eerst met de fiets naar school, helm op. Komt thuis en zegt: 'De hele klas heeft geen helm. Doe ik ook niet meer, anders hoor ik er niet bij.'"

Deze quote was niet gemist, maar ook niet direct als kern herkend. Totdat AI ze naar boven haalde.

---

## De iteratie-les

Wat dit verhaal illustreert is dat de beste analyse ontstaat door dialoog.

Maarten gaf niet alleen antwoorden op de AI vragen; hij corrigeerde en nuanceerde:
- "Ik wil allebei" (niet of/of maar en/en)
- "Vanuit het positieve" (toon-correctie)
- "De haakjes wil ik, maar ik bepaal zelf hoe ik ze gebruik" (autonomie)

De prompt was het resultaat van samenwerking. Niet één perfecte vraag, maar een dialoog die steeds scherper werd.

Deze pagina laat zien hoe dat proces er in de praktijk uitziet. De techniek zelf (de feedback-formules, de samenwerkingsvormen, de twaalf-rondes les) staat in [Iteratie als dialoog](iteratie.md).

---

## Wat je ermee doet

Het vinden van verrijking is stap een. De vraag is wat je ermee doet.

*Maar eerst: wat wil je eigenlijk bereiken? Het helpt om dat vooraf te bedenken; dan stuurt het je analyse.*

**Optie 1: Terugkomen in volgende sessie**
"Vorige keer kwam iets naar boven dat me is bijgebleven. Over de fietshelm. Kunnen we daar verder op ingaan?"

**Optie 2: Verbinding maken**
De haakjes gebruiken om mensen te verbinden die dezelfde worsteling delen.

**Optie 3: Integreren in synthese**
De patronen en quotes worden onderdeel van wat je teruggeeft aan de groep.

**Optie 4: Eigen verdieping**
Je noteert wat er boven kwam als input voor je volgende sessie. Welke thema's verdienen meer aandacht?

---

## Spanningen

**Samenvatten versus verrijken**
Een transcript door AI laten samenvatten geeft je een korter transcript. Geen verrijking.

*Mijn aanpak:* Ik vraag om structuur, haakjes, kernmomenten, niet om compressie. De vraag is niet "maak dit korter" maar "wat zit erin dat ik nog niet heb benoemd?"

**Niet in dialoog gaan**
De verleiding is om de eerste analyse te accepteren zonder vragen of correcties.

*Mijn aanpak:* Ik stel vervolgvragen. Ik corrigeer de toon. Ik geef richting. De beste analyse ontstaat in dialoog.

**Vooraf nadenken over de vervolgstap**
De neiging is om te analyseren zonder te weten wat je ermee wilt. Wat helpt: voordat je begint, bedenken wat je met de uitkomst gaat doen.

*Mijn aanpak:* Ik plan wat ik met de verrijking ga doen. In de volgende sessie, in een mail, in de synthese. Dat vooraf weten stuurt ook de analyse zelf. Dit is dezelfde logica als de [deconstructed burger](prompt-mensen-eerst.md): begin bij het doel en werk terug naar wat je nodig hebt.

---

## Filosofische verdieping

### Meer dan je kunt bevatten

Een transcript is geen verslag van wat er gebeurde. Het is ruwe olie: grondstof voor verdieping.

Elk gesprek bevat meer dan de deelnemers direct kunnen verwerken. Dat is geen tekortkoming; dat is de aard van rijke interactie. Als facilitator of gespreksleider moet je in het moment zijn: luisteren, doorvragen, de energie lezen. Je kunt niet tegelijk alles wat gezegd wordt analyseren en ordenen. Dat hoeft ook niet, want het transcript vangt het op.

Transcriptie maakt het mogelijk om terug te gaan. AI maakt het mogelijk om samen te graven. Jij brengt het mensenwerk: het gesprek, de energie, de verbinding. AI helpt om er meer uit te halen dan je in het moment kon bevatten. De combinatie opent wat er al was, maar nog niet benoemd.

De vraag is niet "wat heb ik gemist?" maar "wat zit er allemaal in dat ik nog niet heb benoemd?"

---

## Gerelateerde technieken

**Andere ingangen naar verdieping:**
- [Intuïtie zwart op wit](intuitie-zwart-op-wit.md): wanneer je al een gevoel hebt dat je wilt benoemen (dit is de proactieve variant)

**Het proces zelf:**
- [Iteratie](iteratie.md): hoe het iteratie-gesprek werkt dat in dit verhaal centraal staat

**Verder bouwen:**
- [Haakjes vinden](../fase-3/haakjes-vinden.md) (Fase 3): de volledige techniek voor systematisch verbindingen vinden over meerdere gesprekken

---

← [Vorige: Intuïtie zwart op wit](intuitie-zwart-op-wit.md) | [Terug naar Fase 2](../../fase-2-verdieping.md) | [Volgende: Iteratie als dialoog](iteratie.md) →

---

*"Het gesprek was waardevol. Er zit meer in dan je live kon bevatten. Laten we samen graven."*
