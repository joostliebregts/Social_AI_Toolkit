# Brondocument-stijl klonen

> *"We weten dat dit document is goedgekeurd door de zorgverzekeraar. Eigenlijk wil ik dat de nieuwe documenten in dezelfde schrijfstijl komen."*

**Fase:** [Fase 1: Begin](../fase-1-begin.md)
**Bouwt voort op:** Transcriptie als grondstof voor nieuwe documenten

---

## Wanneer is dit relevant?

**Situatie:** Er is een document dat werkt. Goedgekeurd door stakeholders, acceptabel voor de zorgverzekeraar, herkenbaar voor de doelgroep. Nu wil je nieuwe content maken, maar in dezelfde stijl.

**De neiging:** Zelf de stijl proberen na te bootsen. Of AI vragen "schrijf in dezelfde stijl als dit voorbeeld." Dat levert vaak generieke output die de nuances mist.

**Het principe:** Je moet de stijlkenmerken uitpluizen voordat je ze kunt klonen. Structuur, toon, terminologie: die moet je expliciet meegeven aan de AI. De sleutel is niet één prompt, maar een gefaseerde aanpak.

**De vraag:** Als je de output naast het origineel legt, herkennen stakeholders dan dezelfde vorm, dezelfde toon, hetzelfde "dit hoort bij ons"?

---

## Stijlrichtlijnen in de prompt

Een regionaal GGZ-netwerk stond voor een uitdaging. Ze moesten een transformatieplan schrijven voor hun regio. Er was al een goedgekeurd plan uit een andere regio: 94 pagina's, door de zorgverzekeraar geaccepteerd.

De vraag: hoe maak je nieuwe deelplannen in dezelfde stijl, gebaseerd op live gesprekken met stakeholders?

Ik begon met AI te vragen om de schrijfstijl te analyseren. Dat ging goed: AI identificeerde structuur, toon, terminologie. Vervolgens ontwikkelden we prompts voor live documentatie tijdens workshops.

Maar toen ik de prompts teruglas (en dit was een klassiek "oh nee" moment) zag ik het probleem:

> "Formuleer in de schrijfstijl van het referentie-transformatieplan"

De AI zou tijdens de sessie geen toegang hebben tot dat referentiedocument. De prompt was onbruikbaar.

De correctie was simpel maar cruciaal: neem de stijlrichtlijnen letterlijk op in de prompt. Niet "schrijf zoals het voorbeeld" maar:

- Taal: Formeel, zakelijk Nederlands
- Toon: Collaboratief ("we", "samen"), actiegericht, pragmatisch
- Perspectief: Rekening houdend met "inwoner", "naaste", "professional"
- Terminologie: IZA, GALA, MGN, POH-GGZ, positieve gezondheid, herstelgericht

Dit was een van meerdere correcties in een proces van twaalf rondes. De prompt evolueerde door feedback en dialoog: je geeft feedback, AI past aan, je reageert weer. Dat heen en weer is geen bijzaak, het is het proces. Meer over hoe die samenwerking werkt vind je in [Iteratie als dialoog](../fase-2/iteratie.md).

---

## De kern: stijlrichtlijnen moeten IN de prompt

Volgens mij is dit de belangrijkste les: je kunt niet zeggen "schrijf zoals het voorbeeld" als AI dat voorbeeld niet in het context-window (het geheugen) heeft.

Dit klinkt vanzelfsprekend, maar het is een valkuil waar ik zelf inliep. Mijn eerste prompts verwezen naar "het referentie-transformatieplan", alsof de AI dat document zou kunnen raadplegen tijdens de sessie. Dat kon het niet.

De oplossing: de stijlkenmerken moeten expliciet in de prompt staan. Niet als verwijzing, maar als instructie.

---

## De aanpak

### 1. Analyseer het brondocument

Voordat je een prompt kunt schrijven, moet je begrijpen wat de kenmerken zijn van het goedgekeurde document.

**Wat te analyseren:**

| Categorie | Vragen |
|-----------|--------|
| **Structuur** | Welke secties komen terug? In welke volgorde? Zijn er vaste elementen? |
| **Toon** | Formeel of informeel? Collaboratief of directief? |
| **Terminologie** | Welk jargon wordt consistent gebruikt? |
| **Opmaak** | Hoe worden lijsten, tabellen, figuren ingezet? |

**De analyse-prompt:**

```
Analyseer dit document en identificeer:

1. Structuur: Welke secties komen terug? In welke volgorde?
2. Toon: Formeel/informeel? Collaboratief/directief?
3. Terminologie: Welk vakjargon wordt consistent gebruikt?
4. Opmaak: Hoe worden lijsten, tabellen, figuren ingezet?

Geef per categorie concrete voorbeelden uit het document.
```

**Voorbeeld: analyse van het transformatieplan**

Dit is wat de analyse opleverde voor het GGZ-transformatieplan:

```
Structuur per Deelplan:
Elk deelplan volgt een vaste structuur:
- Inleiding
- Hoofddoelstelling
- Huidige status
- Interventie
- Doelgroep
- Effecten (genummerde lijst)
- Betrokken partners (bullet points)
- Fasering inrichting
- Afspraken (SMART-tabel)
- Investering

Schrijfstijl:
- Formeel, zakelijk Nederlands
- Collaboratief: veel "we", "samen", "gezamenlijk"
- Actiegericht, pragmatisch, oplossingsgericht

Terminologie:
- IZA, GALA, MGN, POH-GGZ, positieve gezondheid
- Verkennend gesprek, overlegtafel, sociale kaart
- Domein overstijgend, herstelgericht
```

### 2. Codeer de stijl in je prompt

Neem de stijlkenmerken letterlijk op in elke prompt die output moet genereren.

**Voorbeeld: stijlrichtlijnen embedded**

```
Formuleer in de volgende schrijfstijl:
- Taal: Formeel, zakelijk Nederlands
- Toon: Collaboratief ("we", "samen"), actiegericht, pragmatisch
- Perspectief: Samenwerkende partijen, rekening houdend met
  "inwoner", "naaste", "professional"
- Terminologie: IZA, GALA, MGN, POH-GGZ, positieve gezondheid,
  herstelgericht
- Structuur: Heldere zinnen, opsommingen waar nodig
```

Dit blok moet in elke prompt staan die in de doelstijl moet schrijven.

### 3. Test en verfijn

De eerste prompt is zelden de beste. Test met een representatief transcript en geef feedback:

- "De toon is te formeel"
- "Dit mist de collaboratieve framing"
- "De terminologie klopt niet"

Laat AI de prompt evolueren. Zie [Iteratie als dialoog](../fase-2/iteratie.md) voor hoe dit proces werkt.

---

## De prompts

Dit zijn de prompts die ik destijds gebruikte bij transformatieplan-sessies. Ze zijn uitgebreider dan de voorbeelden hierboven; dat is bewust. In de praktijk bleek dat detail nodig voor consistente output.

De drie prompts hieronder passen bij een gefaseerde workshop: eerst tussentijdse terugkoppeling, dan continue verwerking, dan eind-synthese. Die volgorde is niet toevallig. Door analyse en synthese te scheiden, blijft elke stap behapbaar.

Dit is ook een voorproefje op [Fase 3: Schaal](../fase-3-schaal.md), waar je met meerdere sessies of breakout-groepen aan het itereren bent op hetzelfde document.

### Tussentijdse Visie Terugkoppeling

**Context:** Direct na de eerste discussieronde. De groep heeft net gepraat; nu wil je terugkoppelen: "Klopt dit beeld?"

**Wat deze prompt laat zien van brondocument-stijl:**
- "Vereiste Schrijfstijl" blok met alle stijlkenmerken
- Terminologie uit het brondocument (IZA, GALA, MGN)
- Doel van de output expliciet genoemd

```
**Prompt voor Dembrane (Tussentijdse Visie Terugkoppeling - Universeel)**

**Rol:** Je bent een AI-assistent die helpt bij het live documenteren van een transformatieplan-sessie. Jouw taak nu is om de kern van de zojuist gevoerde visie-discussie samen te vatten voor directe feedback aan de groep.

**Context:**
*   **Sessie Deel:** Ronde 1 - Discussie over 5-jaarsperspectief (vraag 1 draaiboek).
*   **Doel Output:** Terugkoppeling aan de deelnemers aan de tafel ter validatie ("Klopt dit beeld?").

**Vereiste Schrijfstijl (Pas deze consistent toe):**
*   **Taal:** Formeel, zakelijk Nederlands.
*   **Toon:** Collaboratief ("we", "samen", "gezamenlijk"), actiegericht, pragmatisch, oplossingsgericht.
*   **Perspectief:** Geschreven vanuit de samenwerkende partijen, rekening houdend met perspectief van "inwoner", "naaste", "professional".
*   **Terminologie:** Gebruik correcte en relevante jargon uit de Nederlandse zorg en GGZ (zoals IZA, GALA, MGN, POH-GGZ, positieve gezondheid, herstelgericht, domein overstijgend, etc.) waar passend.
*   **Structuur:** Gebruik heldere zinnen, opsommingen (bullet points) waar nodig.

**Instructies:**
1.  **Identificeer het primaire thema** dat in dit transcriptfragment wordt besproken. Kies uit: 'Sociale Kaart', 'Overlegtafel/transfertafel', of 'Verkennend Gesprek'. Baseer je keuze op kernwoorden en de context van de visie-discussie. Als het thema niet eenduidig te bepalen is, noteer 'Thema Onduidelijk' en stop.
2.  **Genereer een beknopte, narratieve samenvatting** van de gedeelde 5-jaarsvisie voor het **geïdentificeerde thema**. Formuleer deze samenvatting strikt volgens de **Vereiste Schrijfstijl**. Focus op het gewenste toekomstbeeld en de beoogde opbrengsten.
3.  **Extraheer een lijst met 3-5 cruciale onderdelen of elementen** die volgens de deelnemers absoluut in deze 5-jaarsvisie voor het **geïdentificeerde thema** moeten zitten. Presenteer dit als een duidelijke bullet-point lijst onder de samenvatting.
4.  **Controleer op eventueel genoemde KPI's** of meetbare resultaten gerelateerd aan de visie en neem deze op in de samenvatting of de lijst met cruciale onderdelen.

**Input Transcript:**
[Hier plak je het relevante transcriptfragment van de visie-discussie van deze tafel]

**Output Format:**
**Geïdentificeerd Thema:** [Sociale Kaart / Overlegtafel/transfertafel / Verkennend Gesprek / Thema Onduidelijk]

**(Indien Thema geïdentificeerd):**
**Concept Visie [Geïdentificeerd Thema] (ter validatie):**
[Hier komt de narratieve samenvatting in de vereiste schrijfstijl]

**Cruciale Onderdelen Visie:**
*   [Cruciaal onderdeel 1]
*   [Cruciaal onderdeel 2]
*   [Cruciaal onderdeel 3]
*   ...
```

*Dit is de prompt die ik destijds gebruikte bij transformatieplan-sessies.*

---

### Continue Verwerking & Vragen

**Context:** Tijdens de workshop. Kernpunten extraheren en vragen genereren voor de volgende groep.

**Wat deze prompt laat zien:**
- Stijlrichtlijnen embedded in de prompt
- Tagging-systeem voor latere synthese
- Output gericht op doorgeven naar volgende ronde

```
**Prompt voor Dembrane (Continue Verwerking & Vragen - Universeel)**

**Rol:** Je bent een AI-analist en redacteur die live gesprekken volgt voor een transformatieplan GGZ. Jouw taken zijn het extraheren van kernpunten en het identificeren van vragen voor verdere discussie.

**Vereiste Schrijfstijl (Voor eventuele geformuleerde kernpunten):**
*   **Taal:** Formeel, zakelijk Nederlands.
*   **Toon:** Collaboratief ("we", "samen"), objectief bij samenvatten.
*   **Terminologie:** Gebruik correcte en relevante jargon (IZA, MGN, etc.) waar passend.

**Instructies:**
1.  Analyseer het bijgevoegde transcriptfragment.
2.  **Identificeer het primaire thema** dat wordt besproken ('Sociale Kaart', 'Overlegtafel/transfertafel', 'Verkennend Gesprek') of noteer 'Thema Onduidelijk'.
3.  **Extraheer de belangrijkste inhoudelijke punten:**
    *   Genoemde visie-elementen, doelstellingen, problemen.
    *   Voorgestelde acties, stappen, oplossingen.
    *   Genoemde randvoorwaarden, benodigde partners.
    *   Belangrijke punten van overeenstemming of juist van discussie/onenigheid.
    *   Eventueel genoemde KPI's of meetbare resultaten.
4.  **Formuleer deze kernpunten beknopt.** Probeer elk punt te **taggen** met het geïdentificeerde thema en een mogelijke sectie uit het transformatieplan (bijv. `[Thema: Sociale Kaart, Sectie: Visie]`, `[Thema: Overlegtafel, Sectie: Fasering]`, `[Thema: Verkennend Gesprek, Sectie: Randvoorwaarden]`, `[Thema: Algemeen, Sectie: KPI]`). Gebruik de **Vereiste Schrijfstijl** voor deze punten.
5.  **Analyseer de discussie in het fragment:** Waar stokt het gesprek? Welke punten blijven onduidelijk? Waar is duidelijk behoefte aan input of besluitvorming door een volgende groep?
6.  **Genereer 1 of 2 concrete, open vragen** die de volgende groep kunnen helpen om verder te bouwen op dit gesprek of om knelpunten op te lossen. De vragen moeten direct voortkomen uit de analyse in stap 5.

**Input Transcript:**
[Hier plak je het te verwerken transcript-segment]

**Output Format:**
**Geïdentificeerd Thema:** [Sociale Kaart / Overlegtafel/transfertafel / Verkennend Gesprek / Thema Onduidelijk]

**Kernpunten uit dit fragment:**
*   [Kernpunt 1 geformuleerd in vereiste stijl] `[Tag: Thema, Sectie]`
*   [Kernpunt 2 geformuleerd in vereiste stijl] `[Tag: Thema, Sectie]`
*   [KPI 1 genoemd] `[Tag: Thema, Sectie: KPI]`
*   ...

**Voorgestelde Vragen voor Volgende Groep:**
1.  [Vraag 1]
2.  [Vraag 2 (optioneel)]
```

*Dit is de prompt die ik destijds gebruikte bij transformatieplan-sessies.*

---

### Eind-Synthese per Thema

**Context:** Aan het einde. Alle rondes zijn geweest; nu consolideren tot concept-deelplan.

**Wat deze prompt laat zien:**
- Volledige stijlrichtlijnen (taal, toon, perspectief, terminologie, structuur)
- Structuur van brondocument overgenomen
- Ruimte voor "ontbrekende informatie"

```
**Prompt voor Dembrane (Eind-Synthese Deelplan per Thema - Universele Template)**

**Rol:** Je bent de hoofdredacteur die de input van de gehele workshop consolideert tot een concept-deelplan voor het transformatieplan [Naam Nieuwe Regio].

**Context:**
*   **Thema van deze Synthese:** [Naam Thema - **Noodzakelijk specificeren bij uitvoering!**, bijv. 'Verkennend Gesprek']
*   **Sessie Deel:** Einde van de workshop - consolidatie van alle rondes voor het gespecificeerde thema.
*   **Doel Output:** Een coherent concept-deelplan voor het gespecificeerde thema, klaar voor verdere redactie.

**Vereiste Schrijfstijl (Pas deze consistent toe op de gehele output):**
*   **Taal:** Formeel, zakelijk Nederlands.
*   **Toon:** Collaboratief ("we", "samen", "gezamenlijk"), actiegericht, pragmatisch, oplossingsgericht.
*   **Perspectief:** Geschreven vanuit de samenwerkende partijen, rekening houdend met perspectief van "inwoner", "naaste", "professional".
*   **Terminologie:** Gebruik correcte en relevante jargon uit de Nederlandse zorg en GGZ (zoals IZA, GALA, MGN, POH-GGZ, positieve gezondheid, herstelgericht, domein overstijgend, etc.) waar passend voor dit thema.
*   **Structuur:** Volg de deelplan-structuur (zie instructies). Gebruik duidelijke koppen, subkoppen, bullet points en genummerde lijsten waar van toepassing.

**Instructies:**
1.  Verzamel alle kernpunten en KPI's die tijdens de workshop zijn **getagd met het 'Thema van deze Synthese'** (uit de outputs van Prompt 2).
2.  **Structureer deze informatie** tot een concept-deelplan voor dit thema. Gebruik de volgende secties als leidraad en vul ze met de relevante getagde informatie:
    *   **Inleiding:** Context, belang van dit thema (combineer relevante kernpunten).
    *   **Hoofddoelstelling:** Wat wil men bereiken met dit thema? (Synthetiseer uit relevante kernpunten).
    *   **Interventie:** Beschrijving van de aanpak/oplossing voor dit thema (Synthetiseer uit relevante kernpunten).
    *   **Effecten:** Wat levert het op? Maak een genummerde lijst. **Integreer hier logisch de KPI's** die voor dit thema zijn genoteerd en aan effecten gekoppeld kunnen worden.
    *   **Betrokken partners:** Wie zijn genoemd als relevant voor dit thema? (Maak een bullet list).
    *   **Fasering inrichting [Thema van deze Synthese]:** Beschrijf de stappen, acties, resultaten per fase zoals besproken voor dit thema. **Integreer hier logisch KPI's** die aan specifieke stappen/fases gekoppeld kunnen worden. (Maak een gestructureerde lijst, bijv. per fase).
    *   (Voeg optioneel secties toe zoals 'Randvoorwaarden', 'Huidige status', 'Doelgroep', 'Investering' als hierover voldoende getagde informatie beschikbaar is).
3.  Zorg voor een **logische flow en coherentie**. Herschrijf en verbind de geëxtraheerde punten tot lopende tekst binnen elke sectie, conform de **Vereiste Schrijfstijl**.
4.  Wees expliciet over waar informatie mogelijk nog ontbreekt of verder uitgewerkt moet worden voor dit deelplan (bijv. "SMART-doelen nog te concretiseren", "Financiering/investering nog niet besproken").

**Input:**
[Verwijs naar de verzamelde outputs van Prompt 2, met name de kernpunten getagd met het 'Thema van deze Synthese']

**Output Format:**
**Concept Deelplan: [Thema van deze Synthese]**

**(Volg de structuur zoals beschreven in Instructie 2, met alle tekst in de Vereiste Schrijfstijl)**

**Opmerkingen/Ontbrekende Informatie:**
*   [Punt 1]
*   [Punt 2]
```

*Dit is de prompt die ik destijds gebruikte bij transformatieplan-sessies.*

---

## Waarom deze prompts werken

Elke prompt hierboven volgt dezelfde structuur die de techniek van brondocument-stijl klonen toepast:

1. **Stijlrichtlijnen zitten in de prompt:** Elke prompt bevat expliciet de taal, toon, terminologie en structuur. AI hoeft niet te raden.

2. **De aanpak gefaseerd:** Niet alles tegelijk. Tussentijdse terugkoppeling, continue verwerking, eind-synthese: drie losse prompts voor drie losse doelen.

3. **Context meegegeven:** Elke prompt vertelt AI wat het doel is ("terugkoppeling ter validatie", "consolidatie tot concept-deelplan") en welke input het krijgt.

4. **Terminologie overgenomen:** De prompts gebruiken dezelfde termen als het brondocument (IZA, GALA, MGN, etc.) in plaats van generieke alternatieven.

Dit maakt de prompts reproduceerbaar. Als je de stijlrichtlijnen aanpast naar jouw brondocument, kun je dezelfde structuur gebruiken voor andere trajecten.

---

## Spanningen

**"Schrijf zoals dit voorbeeld" zonder analyse**
De reflex is om te zeggen "schrijf in dezelfde stijl als dit document." Maar AI weet dan niet wat de kenmerken zijn die de stijl maken. Het resultaat mist precies de nuances die het origineel acceptabel maakten.

*Wat ik doe:* Ik analyseer eerst. Wat maakt dit document acceptabel? Structuur? Toon? Terminologie? Die kenmerken codeer ik expliciet in de prompt.

**Stijlrichtlijnen vergeten bij elke prompt**
Je maakt een goede analyse, maar AI "vergeet" de stijl in elk nieuw gesprek. De context window begint weer bij nul.

*Wat ik doe:* Ik neem de kernrichtlijnen op in elke prompt. Of ik werk met een master-prompt die de context zet.

**Eerst analyse, dan synthese**
De verleiding is om alles in één prompt te stoppen: analyse, synthese, structurering en stijl-matching tegelijk. Maar dan wordt het te complex voor AI en verlies je detail dat je wellicht wilt behouden.

*Wat ik doe:* Ik splits in fasen. Tijdens een live workshop had ik eerst een tussentijdse terugkoppeling, dan feedback verwerking, dan eind-synthese. Elk met zijn eigen prompt. Door analyse en synthese te scheiden, blijft elke stap behapbaar en gedetailleerd. En kan je makkelijker zien of je bouwt op iets wat je herkent, of dat er veel detail wegvalt.

Dit is ook een voorproefje op [Fase 3: Schaal](../fase-3-schaal.md), waar je met meerdere sessies of breakout-groepen aan het itereren bent op hetzelfde document.

**Stijl versus echtheid**
Er is een spanning tussen de officiële stijl en de authentieke stem van de deelnemers. Het document moet acceptabel zijn voor de zorgverzekeraar, maar ook herkenbaar voor de mensen die het gesprek voerden.

*Wat ik doe:* Stijlrichtlijnen voor de structuur en toon, maar quotes en kernformuleringen van de deelnemers intact laten. En feedback loops inbouwen: "Kijk, dit is een concept deelplan met jullie woorden, maar wel volgens het format van het eindresultaat." Dan kunnen mensen reageren en bijsturen voordat het definitief wordt.

---

## Veilige defaults

- [ ] Structuur van brondocument geanalyseerd?
- [ ] Stijlrichtlijnen expliciet in de prompt?
- [ ] Terminologie uit brondocument overgenomen?
- [ ] Toon gespecificeerd (formeel, collaboratief, etc.)?
- [ ] Output-format duidelijk gemaakt?
- [ ] Ruimte voor ontbrekende informatie aangegeven?

---

## Tools

| Tool | Waarvoor |
|------|----------|
| **Dembrane** | Live transcriptie + prompt-uitvoering tijdens sessies |
| **Claude/ChatGPT** | Analyse van brondocument + prompt-ontwikkeling |

---

## Gerelateerde technieken

- [Transcriptie als fundament](transcriptie.md): waar de grondstof vandaan komt
- [Taal als eigenaarschap](taal-behouden.md): de taal binnen de stijl
- [Iteratie als dialoog](../fase-2/iteratie.md): het volledige 12-rondes verhaal

---

<- [Terug naar Fase 1: Begin](../fase-1-begin.md) | [<- Taal als eigenaarschap](taal-behouden.md) | [Fase 2: Verdieping ->](../fase-2-verdieping.md)
