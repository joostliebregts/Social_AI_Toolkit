# Iteratie als dialoog

> *Niet sleutelen aan output, maar feedback geven. AI leert wat je bedoelt.*

**Fase:** [Fase 2: Verdieping](../fase-2-verdieping.md)
**Bouwt voort op:** De eerste AI-output die niet helemaal klopt

---

## Wanneer is dit relevant?

**Situatie:** Je krijgt output van AI. Het is 60% van wat je zoekt. De reflex is om het zelf aan te passen: woorden veranderen, zinnen herschrijven.

**De neiging:** Solo-werk. Je pakt de output en sleutelt tot het past. AI is klaar, jij neemt het over.

**Het principe:** AI output is eigenlijk nooit helemaal klaar. Het is input voor een dialoog. Door feedback te geven in plaats van te sleutelen, leert AI werken met jouw specifieke behoeften. Het resultaat is beter dan wat je in je eentje had gemaakt. Én je leert woorden te geven aan wat je eigenlijk wilt hebben. 

**De vraag:** Geef ik feedback of ga ik zelf sleutelen?

---

## Op deze pagina

Itereren heeft verschillende vormen. Spring naar wat je zoekt:

- [Het verhaal: twaalf rondes](#het-verhaal-twaalf-rondes) - hoe een prompt evolueert door correcties
- [De shift: van sleutelen naar sturen](#de-shift-van-sleutelen-naar-sturen) - het fundamentele verschil
- [Iteratie vooraf: laat AI jou vragen stellen](#iteratie-vooraf-laat-ai-jou-de-vragen-stellen) - scherp krijgen wat je wilt vóórdat er output komt
- [De gereedschapskist](#de-gereedschapskist) - feedbackformules, feedback-loop, prompt-test-cyclus, cross-model kritiek

---

## Het verhaal: twaalf rondes

Een transformatieplan voor een mentaal gezondheidsnetwerk. Dertig stakeholders hadden input gegeven. Nu moest dat omgezet worden naar een document dat de zorgverzekeraar zou accepteren.

Er was al een goedgekeurd transformatieplan uit een andere regio. De vraag: hoe schrijf je nieuwe deelplannen in dezelfde stijl?

Dit werd geen eenmalige prompt. Het werd twaalf rondes.

**Ronde 1:** Ik beschrijf wat ik wil.
**Ronde 2:** AI stelt een stappenplan voor.
**Ronde 3:** Ik voeg het draaiboek toe voor context.
**Ronde 4:** AI past de prompts aan op het draaiboek.
**Ronde 5:** Ik vraag om drie specifieke prompts.
**Ronde 6:** AI levert drie prompts, maar de stijl zit nog niet goed.
**Ronde 7:** Ik vraag om universele versies.
**Ronde 8:** AI past aan, maar mist nog iets.
**Ronde 9:** Cruciale correctie: "De stijl moet IN de prompt, want AI heeft geen toegang tot het voorbeeld."
**Ronde 10:** AI verwerkt de correctie.
**Ronde 11:** Ik verduidelijk de context-window situatie.
**Ronde 12:** Prompts zijn klaar.

Vier concrete correcties die het verschil maakten:
- "De AI heeft geen toegang tot het voorbeeldplan, dus neem de schrijfstijl mee IN de prompt"
- "Maak de prompts universeel: de AI kan zelf het thema detecteren uit het transcript"
- "Prompt 2 moet vooral vragen genereren voor de volgende groep"
- "De AI heeft toegang tot volledige transcripten, niet fragmenten"

Toen ik hierop terugkeek, zag ik een patroon: een prompt ontstaat niet in ronde 1. De prompt evolueert door de correcties.

**Bron:** Iteratieproces dat ik doorliep bij transformatieplan-ontwikkeling (GGZ Centraal Gelderland)

---

## De shift: van sleutelen naar sturen

```
❌ Sleutelen: AI-output krijgen → Zelf gaan aanpassen → Klaar
✅ Itereren: AI-output krijgen → Pauzeren → Feedback geven → Herhalen
```

Het verschil is subtiel maar fundamenteel. Sleutelen is solo-werk. Itereren is samenwerken.

**Hoe sleutelen eruit ziet:**
Je krijgt een samenvatting van AI. De toon is te formeel. Je opent het document en begint zinnen te herschrijven. "Stakeholders" wordt "betrokkenen". "Geïmplementeerd" wordt "ingevoerd". Na twintig minuten is het klaar. AI heeft niks geleerd. Jij hebt het werk gedaan.

**Hoe itereren eruit ziet:**
Je krijgt dezelfde samenvatting. De toon is te formeel. Je typt: "Dit voelt als een beleidsdocument. Ik zoek de toon van een gesprek tussen collega's die elkaar al lang kennen en transparant zijn over hun behoeften. Gebruik gewone woorden, geen jargon. Probeer opnieuw." Dertig seconden later heb je een nieuwe versie. Die is beter, maar nog niet helemaal. Je typt: "Beter. Maar de eerste alinea is nog te afstandelijk. Maak het persoonlijker." Weer dertig seconden. Nu klopt het.

**Waarom dit beter werkt:**
- AI leert jouw specifieke behoeften binnen het lopende gesprek. Let op: start je een nieuw gesprek, dan is de context window weer leeg en begin je opnieuw. Daarom loont het om binnen één sessie te blijven itereren.
- Je formuleert scherper wat je wilt, voor jezelf en voor AI
- Het eindresultaat combineert AI's capaciteit met jouw richting
- De volgende keer kun je al in je eerste prompt zeggen: "toon van een gesprek tussen collega's die elkaar lang kennen, transparant over behoeften, geen jargon"

### Dictatie als versneller

De drempel om feedback te geven is typen. Als je elke correctie moet uittypen, voelt itereren als werk. Maar dicteren verandert dat.

De workflow: AI geeft output → je spreekt je reactie in → binnen een seconde staat het er als tekst

Je hoeft niet te formuleren terwijl je typt. Je spreekt gewoon uit wat je denkt: "Nee, dit is te formeel. Ik zoek meer de toon van een gesprek aan de keukentafel." Dat is sneller dan typen, en het voelt natuurlijker, meer als een gesprek.

*Zie [Transcriptie](transcriptie.md#dictatie-als-versnelling) voor tools en setup.*

---

## Iteratie vooraf: laat AI jou de vragen stellen

Tot nu toe ging het over iteratie op output: je krijgt iets van AI, je geeft feedback, AI past aan. Maar er is nog een andere vorm: iteratie *vooraf*. Daar laat je AI jou eerst helpen om scherp te krijgen wat je wilt, vóórdat er output komt. Het heen en weer werken met AI is een vaardigheid op zich. Voor het volledige verhaal van hoe dit eruit zag in de praktijk, zie [Wat er nog meer in zat](wat-er-nog-meer-in-zat.md).

Het smartphonevrij project. Ik wilde samen met Maarten een ouderavond-transcript analyseren om "haakjes" te vinden voor verbinding. Maar wat voor haakjes precies? Maarten en ik wisten het zelf nog niet scherp.

In plaats van direct output te genereren, stelde AI drie vragen met elk twee opties:

**Vraag 1: De focus van de 'Map'**
> - Optie A: De Emotionele Leefwereld (heatmap van gevoelens per fase)
> - Optie B: De Actie-Bereidheid (wie staat waar in de verandercurve)

**Antwoord:** "Ik wil het allebei. De actiebereidheid vloeit voort uit de emotionele leefwereld."

**Vraag 2: De taal van de frictie**
> - Optie A: De 'Interne Ouder' strijd (eigen schermverslaving, "ben ik een zeikerd?")
> - Optie B: De 'Sociale Arena' strijd (schoolplein-oordeel, groepsdruk)

**Antwoord:** "Het is A. Maar hier staat de frictie vanuit het negatieve geformuleerd. Jij vliegt het gelijk vanuit de positieve kant aan. Mensen stimuleren veel meer vanuit het positieve."

**Vraag 3: Het doel van de munitie**
> - Optie A: Een 'Gesprekswaaier': concrete haakjes voor verbinding
> - Optie B: Een 'Campagne Monitor': gaten en kansen voor groei

**Antwoord:** "100% gesprekswaaier. Verbinding maken is het allerbelangrijkste. Ik wil de haakjes hebben van de AI en dan wil ik zelf beslissen hoe ik die deel."

Door keuzes te presenteren dwong AI expliciete richting af. De nuances die toegevoegd werden ("allebei", "vanuit het positieve", "ik bepaal zelf") maakten de prompt scherper dan hij zonder dialoog was geweest.

**Bron:** Gesprek dat ik voerde met AI over gemeenschapsanalyse (Smartphonevrij project)

### De prompt waarmee je AI jou vragen laat stellen

Dit gedrag (AI die jou vragen stelt met A/B opties) moet je expliciet triggeren. Hier is de prompt die dat doet:

```
Ik werk aan [PROJECT/DOEL].

Huidige stand van zaken:
- Doel: [wat je wilt bereiken]
- Doelgroep: [voor wie]
- Waar ik mee worstel: [open vragen, twijfels]

Stel me 3-5 scherpe vragen die me helpen om:
1. Mijn doel helderder te krijgen
2. Cruciale keuzes expliciet te maken
3. Blinde vlekken te identificeren

Waar relevant: presenteer keuzes (A vs B) in plaats van
alleen open vragen. Dit dwingt me om positie te kiezen.

Na mijn antwoorden: stel follow-up vragen op basis van
wat ik heb gekozen.
```

De kracht zit in "presenteer keuzes (A vs B)". Dat dwingt je om positie te kiezen, en de nuances die je toevoegt bij je keuze zijn precies waar de waarde zit.

---

## De gereedschapskist

De twee verhalen hierboven (twaalf rondes en smartphonevrij opvoeden) tonen iteratie in actie. Maar wat als je concreet wilt weten *hoe* je feedback geeft? Of hoe je leert van je eigen aanpassingen? Hier zijn de methodes die ik gebruik.

### Feedback-formules

Wanneer AI output niet klopt, geef specifieke feedback. Spreek het uit alsof je het dicteert:

**Voor toon:**
> "Maak het warmer, alsof je het aan een collega vertelt."
> "Dit voelt als consultant-taal, kun je de woorden van de deelnemers gebruiken?"

**Voor structuur:**
> "Te lang, kun je minder bullets geven en meer verhaal?"
> "De volgorde klopt niet, kun je beginnen met X in plaats van Y?"

**Voor inhoud:**
> "Dit mist de nuance over X, kun je dit en dit en dit toevoegen alsjeblieft?"
> "Dit is 70% wat ik zoek. Wat mist is X, kun je het opnieuw proberen?"

**Voor framing:**
> "Dit is te negatief geformuleerd, kun je het framen vanuit wat mensen willen?"
> "Dit klinkt alsof AI het weet, kun je 'mogelijk' en 'het lijkt alsof' gebruiken?"

**Als je niet weet wat je wilt:**
> "Dit is niet wat ik zoek qua toon en structuur, maar ik weet niet helemaal wat ik wel wil. Kun je me vragen stellen om helder te krijgen welke opties er zijn en welke beter voor mij werkt?"

**Als je tussen opties twijfelt:**
> "Ik twijfel tussen deze twee formats. Kun je ze allebei beknopt uitwerken zodat ik het voorbeeld kan lezen en daar feedback op kan geven?"

### De feedback-loop prompt

Stel je voor: je hebt AI output flink aangepast. Je hebt zinnen herschreven, structuur veranderd, toon aangepast. In plaats van dat werk te "verliezen", kun je het terugvoeren naar AI zodat je prompt de volgende keer beter werkt.

```
Dit was de originele output:
[plak AI output]

Dit is wat ik ervan heb gemaakt:
[plak jouw verbeterde versie]

Analyseer de verschillen:
1. Wat heb ik veranderd?
2. Waarom denk je dat ik dat veranderde?
3. Hoe moet ik de prompt aanpassen om de volgende keer
   dichter bij mijn gewenste output te komen?

Geef concrete suggesties voor prompt-verbeteringen.
```

*Dit is een suggestie: pas aan op jouw specifieke situatie.*

Dit lijkt extra werk, maar het is een investering. Elke iteratie maakt je prompts scherper.

### Prompt-test-cyclus

**Wanneer gebruik je dit?**
- Je hebt bestaande transcripten en wilt testen of een nieuwe prompt werkt
- Er is een nieuw AI-model en je wilt checken of je prompts nog goed werken
- Je wilt systematisch verbeteren in plaats van ad hoc

Bijvoorbeeld: je hebt een prompt die prima werkte met GPT-4, maar nu is er een nieuw model. Werkt je prompt nog? Of je hebt tien transcripten van vorige sessies en wilt testen of je nieuwe analyse-prompt de juiste dingen eruit haalt.

Een krachtigere variant: test je prompt op echte data en laat AI het eigen werk evalueren.

De stappen:
1. **Maak de prompt samen met AI**: bijvoorbeeld een prompt voor transcript-analyse
2. **Test op echte data**: voer de prompt uit op een relevant transcript
3. **Verzamel de output**: wat kwam eruit?
4. **Voer terug naar de AI die de prompt maakte:**

```
Ik heb de prompt die we samen maakten getest op een echt transcript.

Dit is de output die eruit kwam:
[plak de output]

Vragen:
1. Hoe goed heeft onze prompt gepresteerd voor wat we wilden bereiken?
2. Wat ontbreekt er in de output?
3. Hoe moeten we de prompt aanpassen om dichter bij ons doel te komen?
```

5. **Verfijn de prompt**: laat AI de originele prompt aanpassen op basis van de test

Dit is anders dan de feedback-loop hierboven. Daar pas jij de output aan en laat je AI leren van jouw aanpassingen. Hier test je de prompt zelf en laat je AI evalueren hoe goed de prompt presteerde.

*Bron: Werkwijze die ik ontwikkelde voor het itereren van Dembrane-prompts.*

### Cross-model kritiek (geavanceerd)

Dit is een tijdsintensieve techniek voor werk dat je echt tot in de puntjes wilt uitwerken: twee AI's elkaars werk laten reviewen. Ik gebruikte dit voor workshop-ontwerp: ChatGPT en Gemini reviewden elkaars output tot ze convergeerden naar 98/100.

**Waarom dit werkt:**
- Verschillende modellen hebben verschillende biases en sterke punten
- Kritiek van "peer-AI" helpt blinde vlekken identificeren
- Convergentie toont robuustheid van resultaat

**Wanneer te overwegen:**
- Werk waar je echt diepgang in zoekt (strategische plannen, workshop ontwerpen)
- Complexe analyses waar je meerdere perspectieven wilt
- Als check of één AI je misleidt

### Stap 1: Vraag beide AI's om samenvatting

Aan beide AI's (apart):

```
We hebben samen gewerkt aan [PROJECT/VRAAG].

Maak een samenvatting van:
- De kernvraag die we probeerden te beantwoorden
- De aanpak die we hebben gekozen
- De belangrijkste inzichten die naar voren kwamen
- De zwakke punten of blinde vlekken in onze analyse
- Een rating (0-100) voor de kwaliteit van ons werk

Wees kritisch en eerlijk over beperkingen.
```

### Stap 2: Laat ze elkaar reviewen

Voer samenvatting A aan Model B:

```
Een andere AI heeft deze samenvatting gemaakt van werk
aan dezelfde vraag:

[KOPIEER SAMENVATTING A]

Review deze samenvatting:
1. Wat zijn sterke punten die wij niet hebben?
2. Wat zijn zwakke punten die zij niet zien?
3. Welke blinde vlekken heeft deze analyse?
4. Hoe zou je onze aanpak combineren met hun inzichten?
```

Doe hetzelfde andersom.

### Stap 3: Integreer

```
Ik heb nu twee analyses en wederzijdse kritiek.

Analyse A: [SAMENVATTING A]
Kritiek van B op A: [KRITIEK B→A]

Analyse B: [SAMENVATTING B]
Kritiek van A op B: [KRITIEK A→B]

Syntheseer tot één geïntegreerd perspectief dat:
- De sterke punten van beide behoudt
- De zwakke punten van beide adresseert
- Nieuwe inzichten toevoegt die uit de confrontatie ontstaan
```

*Dit is tijdsintensief. Gebruik het spaarzaam, voor werk waar het echt toe doet.* Of waar je nieuwsgierigheid je drijft :) 

---

## Spanningen

**Direct sleutelen**
De eerste reflex is om output aan te passen in plaats van feedback te geven. Maar dan leert AI niks en doe ik het werk zelf.

*Mijn aanpak:* Ik pauzeer. Ik vraag mezelf: "Kan ik dit als feedback formuleren?" Als ja, dan feedback. Als nee, dan is het misschien beter om opnieuw te beginnen met een scherpere prompt.

**Eindeloos itereren**
Soms is 80% goed genoeg. Perfectie kan verlammen.

*Mijn aanpak:* Ik stel mezelf de vraag: "Is dit goed genoeg om de volgende stap te zetten?" Zo ja, ga door.

**Vage feedback**
"Dit klopt niet" is wat ik voel. Maar AI weet niet wat er moet veranderen.

*Mijn ervaring:* Wanneer ik gefrustreerd ben over output, merk ik dat mijn feedback ook vaag wordt. Wat helpt: even pauzeren en benoemen wat er precies niet klopt. "De toon is te formeel" werkt beter dan "dit voelt niet goed."

**Feedback zonder richting**
De neiging is om te zeggen wat er mis is zonder te zeggen wat ik wel zoek.

*Mijn ervaring:* Ik merk dat AI beter reageert op "ik zoek [X]" dan op "dit is niet wat ik wil." En eerlijk: het dwingt mij ook om helder te krijgen wat ik eigenlijk wil.

---

## Veilige defaults

*Voor privacy-afwegingen bij het delen van transcripten, lees [Veilig werken met AI](../veilig-werken.md).*

- [ ] Feedback specifiek geformuleerd?
- [ ] Richting gegeven, niet alleen kritiek?
- [ ] Gepauzeerd voordat je ging sleutelen?
- [ ] Bij significant aanpassen: feedback-loop prompt gebruikt?

---

## Filosofische verdieping

### Het proces IS de waarde

In de twaalf-rondes-iteratie was ronde 9 het keerpunt: "De stijl moet IN de prompt, want AI heeft geen toegang tot het voorbeeld."

Dit inzicht kwam niet uit het niets. Het kwam omdat de output van ronde 6 niet klopte: de stijl zat er niet in. Zonder die fout, geen correctie. Zonder die correctie, geen werkende prompts.

De waarde zat niet in de eerste poging. De waarde zat in het proces van ontdekken wat er miste.

### Dialoog creëert commitment

Er is een diepere laag. Wanneer je AI feedback geeft, formuleer je wat je wilt. Die formulering maakt je intentie expliciet, voor jezelf, niet alleen voor AI.

Dit is hetzelfde mechanisme als bij mensen. Dialoog creëert helderheid. Het feit dat je moet uitleggen wat je bedoelt, dwingt je om te weten wat je bedoelt.

---

## Gerelateerde technieken

- [Live reflectie met AI](echo-knop.md): real-time toepassing van iteratie
- [Prompt de mensen eerst](prompt-mensen-eerst.md): de vraag voor de prompt-vraag
- [Brondocument-stijl klonen](../fase-1/brondocument-stijl.md): het 12-rondes verhaal in detail

---

← [Terug naar Fase 2: Verdieping](../fase-2-verdieping.md)

← [Wat er nog meer in zat](wat-er-nog-meer-in-zat.md) | [Prompt de mensen eerst](prompt-mensen-eerst.md) →

---

*"Een prompt ontstaat niet, hij evolueert. De waarde zit in de opstapeling van verfijningen: elke correctie maakt de volgende beter."*
