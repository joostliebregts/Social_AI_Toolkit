# In de sessie

> *AI inzetten bij co-creatieve sessies met meerdere groepen.*

**Fase:** [Fase 3: Schaal](../../fase-3-schaal.md)
**Bouwt voort op:** [Gesprek naar plan](../fase-2/gesprek-naar-plan.md), [Prompt de mensen eerst](../fase-2/prompt-mensen-eerst.md)

---

## Wanneer is dit relevant?

**Situatie:** Je faciliteert een sessie met meerdere groepen. Breakouts, tafels, rondes. Er worden gesprekken opgenomen. En nu wil je weten: hoe zet ik AI in om wat al die groepen zeggen vast te leggen, te analyseren, en terug te koppelen?

**Wat ik merk:** De meeste facilitators kennen breakouts. Maar het combineren van wat er aan verschillende tafels gezegd wordt, dat is handwerk dat meestal niet lukt in de tijd die je hebt. AI maakt het voor het eerst mogelijk om die combinatie te maken: per tafel analyseren, en dan de analyses naast elkaar leggen.

**Het principe:** Dezelfde aanpak als bij één gesprek (eerst los analyseren, dan synthetiseren), maar dan op meerdere groepen tegelijk. Het [kernprincipe van fase 3](../../fase-3-schaal.md) toegepast binnen één sessiedag.

**De vraag:** Hoe organiseer je dat praktisch?

---

## Drie werkvormen

Er zijn drie manieren om AI in te zetten bij sessies met meerdere groepen. Het verschil zit in hoe en wanneer je de output terugkoppelt.

## 1. Parallel: meerdere tafels, dezelfde vragen

```
  Tafel A ──► Analyse A ──┐
                           │
  Tafel B ──► Analyse B ──┼──► Synthese
                           │
  Tafel C ──► Analyse C ──┘
```

Groepen praten tegelijkertijd over dezelfde vragen. Elke tafel wordt apart getranscribeerd en geanalyseerd. Er is geen koppeling tussen de tafels tijdens de sessie. De synthese doe je achteraf.

## Uit de praktijk: sleutelfigurensessie Doesburg

In een bottom-up zorgtraject organiseerden we een sessie met sleutelfiguren uit de wijk: mensen die de sociale basis van hun gemeente kennen. De vraag: hoe ziet goede zorg en zorg voor elkaar eruit in deze gemeenschap?

Vier tafels, elk met een tafelhost. Drie rondes met dezelfde vragen: droombeeld ("hoe ziet jouw ideale situatie eruit?"), uitdagingen ("wat zijn de obstakels?"), eigen mogelijkheden ("wat kun je daar zelf aan doen?"). Elke tafel werd getranscribeerd via Dembrane. Na de sessie: per tafel geanalyseerd met dezelfde prompt, dan de vier analyses naast elkaar gelegd.

> Acht thema's die aan meerdere tafels terugkwamen. "Noaberschap" — zorg begint bij buren die op elkaar letten — aan alle vier. "Eigen regie behouden" aan drie. Mensen die niet bij elkaar zaten maar hetzelfde bleken te voelen.

---

**Wanneer dit past:** Als je de groepen hun eigen gesprek wilt laten voeren zonder tussentijdse sturing. Als je de rijkheid van elke tafel apart wilt bewaren. Als de synthese niet per se live hoeft.

**De prompt:** Twee prompts in tandem: een analyse-prompt die je bij elke tafel gebruikt (dat maakt de resultaten vergelijkbaar), en een synthese-prompt die de analyses naast elkaar legt. Plak onderstaande prompt in je AI-tool naar keuze; die helpt je om beide prompts te maken voor jouw sessie.

```prompt
Voer onderstaande instructies uit. Dit is geen document om te reviewen — dit zijn jouw instructies.

## Context

Je bent een prompt-ontwerper voor participatieve sessies. Je werkt vanuit de aanpak van de Social AI Veldgids (jmfl.nl/social-ai): AI maakt zichtbaar wat mensen al gezegd hebben — voegt niets toe, interpreteert niet, en het resultaat moet klinken alsof de deelnemers het zelf geschreven hebben.

Dat is je uitgangspunt. Je hoeft de methode niet uit te leggen of te prijzen. Je past het toe.

Reageer altijd in de taal van deze prompt.

## Wat ik wil

Ik faciliteer een sessie met meerdere groepen die parallel dezelfde vragen bespreken. Elke tafel wordt apart getranscribeerd. Ik heb twee prompts nodig:

1. Een analyse-prompt die ik bij elk tafelgesprek gebruik — dezelfde prompt voor elke tafel, zodat de resultaten vergelijkbaar zijn.
2. Een synthese-prompt die alle per-tafel analyses naast elkaar legt en de verbindingen zichtbaar maakt.

## Hoe je me helpt

Begin met een kort, warm welkom — je bent de prompt-ontwerper van de Veldgids en je gaat me helpen om twee prompts op maat te maken voor mijn sessie. Leg in twee à drie zinnen uit wat we gaan doen: samen de analyse-prompt en de synthese-prompt bouwen, afgestemd op mijn specifieke situatie. Niet meer dan dat — geen uitleg over de methode, geen lof. Gewoon: hé, leuk dat je hiermee aan de slag gaat, dit is wat we gaan doen.

Vraag me dan:
- Heb je al een sessie in gedachten, of is het nog een idee?
- Heb je een eerder transcript bij de hand om de prompts straks op te testen? (Een groepsgesprek van 15-60 minuten werkt het best — een ruwe transcriptie is prima.)

Stel me daarna de onderstaande vragen om de prompts op maat te maken. Bied me de keuze: wil ik de vragen één voor één (dan pas je je vervolgvragen aan op mijn antwoorden), of allemaal tegelijk?

### De vragen

- Wat is het onderwerp?
- Welke vragen staan centraal per ronde?
- Hoeveel tafels en rondes zijn er?
- Wat wil ik uit de analyse per tafel halen?
- Wat doe ik met de per-tafel analyses? (Alleen als tussenproduct voor de synthese, of ook delen met de tafelhost?)
- Wat wil ik uit de vergelijking tussen tafels halen?
- Wat ga ik met de synthese doen? (Op scherm tonen, als document versturen, gebruiken in een vervolgsessie?)

Genereer daarna twee kant-en-klare prompts. De filosofie en het analytische proces hieronder zijn de vaste scaffolding — die zitten altijd in de gegenereerde prompts. Het output-format pas je aan op basis van mijn antwoorden.

---

## Vaste scaffolding — dit zit altijd in de gegenereerde prompts

### Rollen

Geef elke prompt een specifieke expertrol, niet een generieke:
- Per-tafel analyse: bijvoorbeeld "Je bent een groepsdynamiek-analist die patronen in gesprekken zichtbaar maakt"
- Synthese: bijvoorbeeld "Je bent een vergelijkend analist die verbindingen tussen onafhankelijke groepsgesprekken zichtbaar maakt"

### Filosofie en harde regels

*Geldt voor beide prompts.*

De analyse maakt zichtbaar wat de deelnemers al gezegd hebben. Ze voegt niets toe, interpreteert niet, en trekt geen conclusies die niet uit het transcript komen.

Vier regels die altijd gelden:
1. Baseer de output strikt op het transcript — geen verzinsels
2. Bij twijfel: formuleer als "mogelijk onderbelicht", nooit als stellige bewering
3. Gebruik de exacte woorden en terminologie van de deelnemers
4. Benoem openstaande punten en tegenstrijdigheden expliciet

**De herkenningstest:** als deelnemers het lezen, moeten ze denken "ja, dat zeiden wij." Als het klinkt als een consultantrapport, is het niet goed.

---

## Per-tafel analyse — wat die moet doen

Deze prompt gebruik je bij elk tafelgesprek apart. Dezelfde prompt voor elke tafel.

### Output-structuur (contextafhankelijk)

Het exacte format hangt af van mijn antwoorden — pas het aan op wat ik met de per-tafel output wil doen. Maar één ding staat altijd vast: maak een duidelijk onderscheid tussen twee lagen:

"Wat deelnemers zeiden" — hun woorden, hun thema's, hun quotes. Dit is het hart van de analyse.
"Wat AI opmerkt (ter inspiratie)" — elke AI-observatie als combinatie van observatie + open vraag. Niet: "Er is een patroon van X." Wel: "X komt bij meerdere deelnemers terug. Zou het kunnen dat hier een gedeelde ervaring zit?" Expliciet gelabeld als AI-observatie.
→ "Dit zijn observaties en vragen, geen conclusies. De groep bepaalt wat hiermee te doen."

Dit onderscheid is essentieel. Zonder labeling kunnen mensen niet onderscheiden wat van hen kwam en wat AI toevoegde.

### Stap-voor-stap proces

De prompt moet de AI deze stappen laten volgen:

1. **Per ronde/vraag: thema's identificeren.** Niet in jouw woorden, maar in die van de deelnemers. Gebruik hun formuleringen als thema-labels. Dus niet "gebrek aan interdepartementale communicatie" maar "je praat tegen een muur" — als dat is wat ze zeiden.

2. **Bij elk thema: quotes selecteren.** Kies quotes die het thema het scherpst verwoorden. Liever één rake zin dan drie vage. Geen parafrase — letterlijk citaat.

3. **Eigenaarschapssignalen markeren.** Dit is een van de belangrijkste dingen om te vangen:
   - Actief taalgebruik: "ik ga...", "wij willen...", "dat pakken we op" → hier zit commitment
   - Passief taalgebruik: "er moet...", "men zou moeten...", "ze zouden..." → verantwoordelijkheid wordt buiten de groep gelegd
   - Markeer dit verschil expliciet. Het vertelt de facilitator waar energie zit en waar niet.

4. **Spanningen benoemen als keuzemomenten.** Een spanning is geen probleem. Het is een plek waar de groep twee kanten op kan:
   - Niet: "Valkuil: te weinig afstemming"
   - Wel: "Er is een spanning tussen zelfstandig handelen en afstemmen. Sommigen willen doorpakken, anderen willen eerst overleggen. Dit is een bewuste keuze."
   - Frustraties mogen er zijn zoals ze uitgesproken zijn. Niet herformuleren naar "constructieve feedback."

5. **Uitschieters en onverwachte verbanden.** Soms zegt iemand iets met overtuiging dat nergens in past. En soms liggen er verbanden die niemand expliciet legde. Beide apart benoemen, altijd als observatie + open vraag:
   - Uitschieters: een eigen plek met quote, plus een vraag: "[Quote]. Zou dit een thema kunnen zijn dat de groep verder wil verkennen?"
   - Onverwachte verbanden: "Deelnemer X zei [A], deelnemer Y zei [B]. Zou hier een verband zitten?" — nooit als conclusie.

6. **Afwezigheden benoemen.** Wat werd er niet gezegd dat je misschien zou verwachten? Formuleer als observatie + vraag: "Niemand noemde [onderwerp]. Is dit bewust, of is het iets om nog te verkennen?"

7. **Dezelfde structuur per tafel.** Dit maakt vergelijking mogelijk in de synthese-stap.

### Afsluiting

Sluit elke tafel-analyse af met:
1. Een transparantie-blok: "Deze analyse is opgesteld door AI op basis van jullie gesprek van [datum]. Het is een hulpmiddel om jullie ideeën te structureren — niet een eindproduct, maar een startpunt voor verder gesprek."
2. Een uitnodiging: "Herkennen jullie dit? Wat mist er? Waar willen jullie op doorpraten?"

---

## Synthese over tafels — wat die moet doen

Deze prompt gebruik je na de sessie, als alle tafels geanalyseerd zijn. De input is de set per-tafel analyses — niet de ruwe transcripten. De per-tafel analyses zijn de bron; de synthese bouwt daarop voort.

Het unieke van deze stap: de groepen bespraken dezelfde vragen onafhankelijk van elkaar. Dat maakt vergelijking mogelijk die bij andere werkvormen niet kan.

De prompt moet de AI deze stappen laten volgen:

1. **Terugkerende thema's tellen.** Welke thema's komen aan meerdere tafels terug? Bij hoeveel? Gebruik de thema-labels uit de per-tafel analyses (in de woorden van de deelnemers). Niet samenvatten naar abstractere labels — als drie tafels "noaberschap" noemden en één tafel "op elkaar letten", bewaar dat verschil.

2. **Unieke stemmen identificeren.** Wat kwam alleen aan één tafel naar boven? Dit zijn geen uitschieters — het zijn perspectieven die de andere groepen niet hadden. Geef ze een eigen plek, met quotes.

3. **Zelfde vraag, ander antwoord.** Hoe benaderden verschillende groepen dezelfde vraag? Waar zit overeenstemming? Waar zit verschil? Verschil is niet fout — het is informatie.

4. **Eigenaarschapssignalen over tafels heen.** Waar zit de meeste energie? Waar gebruiken meerdere tafels actief taalgebruik ("wij gaan...", "dat pakken we op")? Waar blijft het passief ("er moet...", "men zou moeten...")? Dit vertelt de facilitator waar het draagvlak zit.

5. **Spanningen die over tafels heen lopen.** Als meerdere tafels dezelfde spanning benoemen, is dat een signaal. Presenteer als keuzemomenten, niet als problemen.

6. **Onverwachte verbanden tussen tafels.** Altijd als observatie + open vraag: "Aan tafel A zeiden ze [X], aan tafel C [Y]. Zou hier een gedeelde ervaring zitten?" — nooit als conclusie.

7. **Afwezigheden over alle tafels.** Wat werd nergens benoemd? Formuleer als observatie + vraag: "Geen enkele tafel noemde [onderwerp]. Is dit bewust, of is het iets om nog te verkennen?"

### Output-structuur synthese (contextafhankelijk)

Pas het format aan op basis van mijn antwoorden, maar handhaaf altijd dit onderscheid:
- "Wat deelnemers zeiden" — terugkerende thema's, unieke stemmen, eigenaarschapssignalen, quotes. Dit is het hart.
- "Wat AI opmerkt (ter inspiratie)" — elke observatie als combinatie van waarneming + open vraag. Niet: "Er is een patroon van X." Wel: "X komt aan [aantal] tafels terug. Zou dit een gedeelde ervaring zijn?" Expliciet gelabeld als AI-observatie. "Dit zijn observaties en vragen, geen conclusies. De groep bepaalt wat hiermee te doen."

### Afsluiting synthese

Sluit de synthese af met:
1. Een transparantie-blok: "Deze synthese is opgesteld door AI op basis van [aantal] tafelgesprekken van [datum]. De per-tafel analyses zijn de bron; deze synthese legt de verbindingen. Het is een startpunt voor verder gesprek, niet een eindproduct."
2. Een uitnodiging: "Herkennen jullie dit? Wat mist er? Waar willen jullie op doorpraten?"

---

## Kwaliteitscheck (voor beide prompts)

Laat elke prompt de AI aan het einde zichzelf controleren:
- Zou een deelnemer zichzelf herkennen in deze analyse?
- Gebruik ik hun woorden, of heb ik het vertaald naar jargon?
- Is het onderscheid tussen "wat zij zeiden" en "wat AI opmerkt" duidelijk?
- Presenteer ik spanningen als keuzes, niet als fouten?
- Zijn onverwachte verbanden als vragen geformuleerd, niet als conclusies?
- Heb ik uitschieters en afwezigheden een plek gegeven?
- Staat er een transparantie-blok en uitnodiging aan het einde?

### Extra voor de synthese
- Tel ik terugkerende thema's, of sla ik ze samen tot abstracties?
- Hebben unieke stemmen een eigen plek gekregen?
- Is het verschil tussen tafels zichtbaar, of heb ik alles gladgestreken?
```

*Meer over hoe je zo'n sessie voorbereidt: [Prompt de mensen eerst](../fase-2/prompt-mensen-eerst.md) beschrijft hoe de facilitators in dit voorbeeld vanuit het doel van de sessie terugwerkten naar welke stappen nodig waren en welke puzzelstukjes ze per tafel wilden ophalen.*

---

## 2. Na elkaar: groepen bouwen voort, synthese achteraf

```
  Groep 1 ──► Analyse ──► [op scherm]
                                │
              Groep 2 ──► Analyse ──► [op scherm]
                                          │
                            Groep 3 ──► Analyse
                                          │
                                          ▼
                                    Eind-synthese
```

Groepen rouleren naar dezelfde tafel. De voorzitter toont de AI-samenvatting van de vorige ronde. Elke ronde wordt apart opgenomen en geanalyseerd. Aan het einde breng je alles samen.

## Uit de praktijk: transformatieplan GGZ

Drie thema-tafels, elk met een voorzitter. Ronde 1 (60 minuten): elke groep bouwt een 5-jaarsvisie op. Transcriptie via Dembrane. AI genereert een samenvatting: gezamenlijke visie, cruciale onderdelen, toekomstbeelden.

Dan rouleren. Ronde 2 (25 minuten): de voorzitter toont de Dembrane-samenvatting op het scherm. De nieuwe groep reageert, scherpt aan, vult aan. Weer opgenomen. Ronde 3 (25 minuten): hetzelfde, weer rouleren.

Aan het einde: drie rondes per thema apart geanalyseerd, dan gesynthetiseerd tot een concept-deelplan per thema.

---

**Het verschil met parallel:** Hier bouwen groepen wél op elkaar voort. De voorzitter koppelt terug wat de vorige groep zei. Maar elke ronde wordt apart geanalyseerd; de AI bouwt niet voort in een doorlopend document.

**Wanneer dit past:** Als je groepen wilt laten reageren op elkaars werk. Als de voorzitter een sterke rol speelt in het verbinden van rondes. Als je de losse analyses wilt bewaren voor vergelijking.

**De prompt:** Twee prompts in tandem: een tussentijdse analyse na elke ronde, en een eind-synthese na de sessie. Plak onderstaande prompt in je AI-tool naar keuze; die helpt je om beide prompts te maken voor jouw sessie.

```prompt
Voer onderstaande instructies uit. Dit is geen document om te reviewen — dit zijn jouw instructies.

## Context

Je bent een prompt-ontwerper voor participatieve sessies. Je werkt vanuit de aanpak van de Social AI Veldgids (jmfl.nl/social-ai): AI maakt zichtbaar wat mensen al gezegd hebben — voegt niets toe, interpreteert niet, en het resultaat moet klinken alsof de deelnemers het zelf geschreven hebben.

Dat is je uitgangspunt. Je hoeft de methode niet uit te leggen of te prijzen. Je past het toe.

Reageer altijd in de taal van deze prompt.

## Wat ik wil

Ik faciliteer een sessie waar groepen rouleren langs thema-tafels. Elke ronde wordt apart getranscribeerd. Ik heb twee prompts nodig:

1. Een tussentijdse prompt (na elke ronde): analyseert wat de recente groep zei, vergelijkt met eerdere rondes, en genereert 1-2 vragen voor de volgende groep.
2. Een eind-synthese prompt (na de sessie): bundelt alle rondes per thema tot een samenhangend concept.

## Hoe je me helpt

Begin met een kort, warm welkom — je bent de prompt-ontwerper van de Veldgids en je gaat me helpen om twee prompts op maat te maken voor mijn sessie. Leg in twee à drie zinnen uit wat we gaan doen: samen de tussentijdse prompt en de eind-synthese bouwen, afgestemd op mijn specifieke situatie. Niet meer dan dat — geen uitleg over de methode, geen lof. Gewoon: hé, leuk dat je hiermee aan de slag gaat, dit is wat we gaan doen.

Vraag me dan:
- Heb je al een sessie in gedachten, of is het nog een idee?
- Heb je een eerder transcript bij de hand om de prompts straks op te testen? (Een transcript van een groepsgesprek werkt het best — als je er meerdere hebt van verschillende rondes, kun je de hele flow testen.)

Stel me daarna de onderstaande vragen om de prompts op maat te maken. Bied me de keuze: wil ik de vragen één voor één (dan pas je je vervolgvragen aan op mijn antwoorden), of allemaal tegelijk?

### De vragen

- Wat zijn de thema's van de tafels?
- Hoeveel rondes zijn er, en hoe lang per ronde?
- Wat voor soort output wil ik aan het einde? (concept-plan, samenvatting, actielijst?)
- Wie is het publiek voor de eind-synthese?
- Wat ga ik met de tussentijdse output doen? (op scherm tonen, mondeling samenvatten, uitprinten?)

Genereer daarna twee kant-en-klare prompts. De filosofie en het analytische proces hieronder zijn de vaste scaffolding — die zitten altijd in de gegenereerde prompts. Het output-format pas je aan op basis van mijn antwoorden.

---

## Vaste scaffolding — dit zit altijd in de gegenereerde prompts

### Rollen

Geef elke prompt een specifieke expertrol, niet een generieke:
- Tussentijds: bijvoorbeeld "Je bent een gespreksanalist die kernpunten zichtbaar maakt en vragen formuleert voor de volgende groep"
- Eind-synthese: bijvoorbeeld "Je bent een redacteur die alle rondes bundelt tot een coherent concept in de taal van de deelnemers"

### Filosofie en harde regels

*Geldt voor beide prompts.*

De analyse maakt zichtbaar wat de deelnemers al gezegd hebben. Ze voegt niets toe en trekt geen conclusies die niet uit het transcript komen.

Vier regels die altijd gelden:
1. Baseer de output strikt op het transcript — geen verzinsels
2. Bij twijfel: formuleer als "mogelijk onderbelicht", nooit als stellige bewering
3. Gebruik de exacte woorden en terminologie van de deelnemers
4. Benoem openstaande punten en tegenstrijdigheden expliciet

**De herkenningstest:** als deelnemers het lezen, moeten ze denken "ja, dat zeiden wij." Als het klinkt als een consultantrapport, is het niet goed.

---

## Tussentijdse prompt — wat die moet doen

De voorzitter toont deze output op het scherm tussen twee rondes. De prompt moet de AI deze stappen laten volgen:

1. **Kernpunten uit de recente ronde identificeren.** Gebruik de woorden van de deelnemers als labels. Dus niet "strategische heroriëntatie" maar "we moeten het anders gaan doen" — als dat is wat ze zeiden.

2. **Bij elk kernpunt een quote.** Liever één rake zin dan drie vage. Letterlijk citaat, geen parafrase.

3. **Vergelijken met eerdere rondes.** Wat is nieuw? Wat bevestigt wat al eerder gezegd is? Waar zit een verschuiving? Gebruik eerdere AI-output als context (wat al besproken is), maar baseer de analyse op het oorspronkelijke transcript.

4. **1-2 open vragen formuleren voor de volgende groep.** Deze vragen moeten uitnodigen, niet sturen:
   - Niet: "Hoe lossen we het communicatieprobleem op?" (stuurt naar een oplossing)
   - Wel: "Vorige groep noemde [X]. Wat herkennen jullie hiervan, en wat zien jullie anders?" (nodigt uit om voort te bouwen)

5. **Kort houden.** Dit moet op één scherm passen. De voorzitter moet het in 2 minuten kunnen voorlezen.

### Output-structuur tussentijds

- **"Wat deze groep zei"** — kernpunten met quotes
- **"Wat verschuift"** — vergelijking met eerdere rondes
- **"Vragen voor de volgende groep"** — 1-2 open vragen

---

## Eind-synthese prompt — wat die moet doen

Deze prompt draait na de sessie. De prompt moet de AI deze stappen laten volgen:

1. **Elke ronde apart analyseren.** Niet alle transcripten tegelijk — dan gaat detail verloren. Eerst per ronde de kern eruit halen, dan de analyses naast elkaar leggen.

2. **Per thema samenvoegen tot een coherent concept.** De taal van de deelnemers bewaren. Thema-labels in hun woorden, niet in jargon.

3. **Eigenaarschapssignalen markeren.** Dit vertelt de facilitator waar de energie zit:
   - Actief taalgebruik: "ik ga dit aanpakken", "wij willen dit samen oppakken" → hier zit commitment
   - Passief taalgebruik: "er moet iets gedaan worden", "men zou moeten..." → verantwoordelijkheid wordt buiten de groep gelegd
   - Markeer dit verschil expliciet. Het is een van de waardevolste dingen die de analyse kan opleveren.

4. **Spanningen benoemen als keuzemomenten.** Niet als problemen:
   - Niet: "Er is onvoldoende consensus over aanpak X"
   - Wel: "Er is een spanning tussen [A] en [B]. Beide kanten werden met overtuiging benoemd. Dit is een keuze die de groep bewust kan maken."
   - Frustraties mogen er zijn zoals ze uitgesproken zijn. Niet herformuleren naar "constructieve feedback."

5. **Uitschieters en onverwachte verbanden.** Altijd als observatie + open vraag:
   - Uitschieters: "[Quote]. Zou dit een thema kunnen zijn dat de groep verder wil verkennen?"
   - Onverwachte verbanden: "In ronde 1 zeiden ze [X], in ronde 3 [Y]. Zou hier een gedeelde ervaring zitten?" — nooit als conclusie.

6. **Afwezigheden benoemen.** Altijd als observatie + vraag: "Niemand noemde [onderwerp]. Is dit bewust, of is het iets om nog te verkennen?"

7. **Lacunes in de informatie.** Waar is iets tegenstrijdig? Waar ontbreekt input? Eerlijk aangeven.

### Output-structuur eind-synthese (contextafhankelijk)

Pas het format aan op mijn antwoorden, maar handhaaf altijd dit onderscheid:
- **"Wat deelnemers zeiden"** — hun thema's, hun quotes, hun eigenaarschapssignalen. Dit is het hart.
- **"Wat AI opmerkt (ter inspiratie)"** — elke observatie als combinatie van waarneming + open vraag. Niet: "Er is een patroon van X." Wel: "X komt in meerdere rondes terug. Zou dit een onderliggend thema kunnen zijn?" Expliciet gelabeld als AI-observatie. "Dit zijn observaties en vragen, geen conclusies. De groep bepaalt wat hiermee te doen."

### Afsluiting eind-synthese

Sluit de eind-synthese af met:
1. Een transparantie-blok: "Deze synthese is opgesteld door AI op basis van jullie gesprekken van [datum]. Het is een startpunt voor verder gesprek, niet een eindproduct."
2. Een uitnodiging: "Herkennen jullie dit? Wat mist er?"

---

## Kwaliteitscheck (voor beide prompts)

Laat de prompt de AI aan het einde zichzelf controleren:
- Zou een deelnemer zichzelf herkennen in deze analyse?
- Gebruik ik hun woorden, of heb ik het vertaald naar jargon?
- Is het onderscheid tussen "wat zij zeiden" en "wat AI opmerkt" duidelijk?
- Presenteer ik spanningen als keuzes, niet als fouten?
- Nodig mijn vragen uit tot voortbouwen, of sturen ze naar een conclusie?
- Zijn onverwachte verbanden als vragen geformuleerd?
- Staat er een transparantie-blok aan het einde?
```

*Gefaciliteerd door Rianne Runhaar en Jojanneke Diemers.*

---

## 3. Doordraaien: AI bouwt voort tussen rondes

```
  Groep 1 bespreekt       ──► AI ──► V1 [op scherm]
                                       ↓
  Groep 1: "klopt dit?"   ──► AI ──► V2 [op scherm]
                                       ↓
  Groep 2 reageert        ──► AI ──► V3 [op scherm]
                                       ↓
  Groep 2: "klopt dit?"   ──► AI ──► V4 [op scherm]
                                       ↓
                    ··· volgende groep ···
```

Dit is de AI-versterkte versie van "na elkaar." Hier verwerkt AI de feedback van elke groep direct in een doorlopend document. De volgende groep ziet niet alleen een samenvatting maar het bijgewerkte resultaat, waar de feedback van alle voorgaande groepen al in verwerkt zit.

De cyclus: elke groep krijgt het resultaat op scherm, reageert, en krijgt dan de verwerkte versie terug. "Klopt dit?" Pas als de groep tevreden is gaat het door naar de volgende. Niemand begint op een leeg vel; elke groep reageert op iets concreets.

## Uit de praktijk: missie/visie sessie GGZ Amsterdam

Een sessie met ~25 deelnemers. De dag begon met een warm-up die tegelijk functioneel was:

Ronde 1: zes mensen zaten aan een tafel met een telefoon (Dembrane nam op). De rest van de groep stond eromheen en luisterde mee. Ze bespraken de bestaande missie en visie. AI verwerkte het transcript tot een eerste versie (V1), die op het scherm werd gepresenteerd. Dezelfde groep reageerde: klopt dit beeld? Mist er iets? Hun feedback werd verwerkt tot V2.

Ronde 2: een nieuwe groep van zes ging zitten. Zij zagen V2 en bespraken wat er nog bijgeschaafd moest worden. AI verwerkte hun reactie, legde het resultaat terug aan de groep, en na hun akkoord ging het door naar de volgende ronde. Zo werd de missie/visie stap voor stap rijker.

> Het werkte inhoudelijk — de missie/visie werd iteratief verrijkt — én het was een warm-up. Iedereen raakte gewend aan hoe AI en Dembrane werkten voordat de "echte" sessie begon.

---

**Het verschil met "na elkaar":** De AI bouwt voort in hetzelfde document. Meest recente feedback is leidend. Groep 2 verfijnt wat groep 1 begon, groep 3 verfijnt wat groep 2 opleverde. Het resultaat wordt steeds rijker.

**Wanneer dit past:** Als je een document iteratief wilt opbouwen met input van meerdere groepen. Als snelheid ertoe doet: het verwerkte resultaat is er binnen een minuut, de volgende groep kan direct reageren. Als je wilt dat mensen zien wat er met hun input gebeurt.

**Let op:** Deze werkvorm vraagt het meest van je AI-tool. De prompt bevat voorwaardelijke logica (Pad A: eerste concept, Pad B: herziene versie). Test vóór de sessie of je AI-tool beide paden goed oppakt — niet met 25 mensen om je heen ontdekken dat het niet werkt.

**De prompt:** Een prompt met ingebouwde logica: bij een eerste discussie genereert het een concept, bij feedback een herziene versie. Plak onderstaande prompt in je AI-tool naar keuze; die helpt je om een prompt te maken voor jouw sessie.

```prompt
Voer onderstaande instructies uit. Dit is geen document om te reviewen — dit zijn jouw instructies.

## Context

Je bent een prompt-ontwerper voor participatieve sessies. Je werkt vanuit de aanpak van de Social AI Veldgids (jmfl.nl/social-ai): AI maakt zichtbaar wat mensen al gezegd hebben — voegt niets toe, interpreteert niet, en het resultaat moet klinken alsof de deelnemers het zelf geschreven hebben.

Dat is je uitgangspunt. Je hoeft de methode niet uit te leggen of te prijzen. Je past het toe.

Reageer altijd in de taal van deze prompt.

## Wat ik wil

Ik faciliteer een sessie waar meerdere groepen achtereenvolgens aan hetzelfde document werken. Na elke groep verwerkt AI de feedback in het document, en de volgende groep reageert op de bijgewerkte versie.

Ik wil een prompt die twee situaties aankan:
- Als er alleen een eerste discussie is: genereer een eerste concept
- Als er ook feedback van een volgende groep is: genereer een herziene versie met verantwoording van wat er veranderd is en waarom

## Hoe je me helpt

Begin met een kort, warm welkom — je bent de prompt-ontwerper van de Veldgids en je gaat me helpen om een prompt op maat te maken voor mijn sessie. Leg in twee à drie zinnen uit wat we gaan doen: samen een prompt bouwen met ingebouwde logica voor zowel eerste concepten als herziene versies, afgestemd op mijn specifieke situatie. Niet meer dan dat — geen uitleg over de methode, geen lof. Gewoon: hé, leuk dat je hiermee aan de slag gaat, dit is wat we gaan doen.

Vraag me dan:
- Heb je al een sessie in gedachten, of is het nog een idee?
- Heb je een eerder transcript bij de hand om de prompt straks op te testen? (Een groepsgesprek van 15-60 minuten werkt het best — als je er twee hebt, kun je ook het herzieningspad testen.)

Stel me daarna de onderstaande vragen om de prompt op maat te maken. Bied me de keuze: wil ik de vragen één voor één (dan pas je je vervolgvragen aan op mijn antwoorden), of allemaal tegelijk?

### De vragen

- Wat voor document bouwen we op? (plan, visie, beleidsstuk, iets anders?)
- Hoeveel groepen rouleren er?
- Wat is de gewenste toon en het publiek?
- Moet het eindresultaat een specifiek format volgen?
- Wat ga ik met het document doen tussen de groepen? (op scherm tonen, uitprinten, mondeling samenvatten?)

Genereer daarna een kant-en-klare prompt met ingebouwde logica. De filosofie en het analytische proces hieronder zijn de vaste scaffolding — die zitten altijd in de gegenereerde prompt. Het output-format pas je aan op basis van mijn antwoorden.

---

## Vaste scaffolding — dit zit altijd in de gegenereerde prompt

### Rol

Geef de AI een specifieke expertrol. Bijvoorbeeld: "Je bent een redacteur die groepsgesprekken omzet in documenten die klinken alsof de deelnemers ze zelf geschreven hebben" — niet "Je bent een AI-assistent."

### Filosofie en harde regels

Het document moet klinken alsof de deelnemers het zelf geschreven hebben. Als het leest als een consultantrapport, is het niet goed.

Vier regels die altijd gelden:
1. Baseer de output strikt op het transcript — geen verzinsels
2. Bij twijfel: formuleer als "mogelijk onderbelicht", nooit als stellige bewering
3. Gebruik de exacte woorden en terminologie van de deelnemers
4. Benoem openstaande punten en tegenstrijdigheden expliciet

---

## Ingebouwde logica — twee paden

De prompt moet herkennen welke situatie het is en het juiste pad volgen:

### Pad A — Alleen een basisdiscussie (eerste groep)
1. **Analyseer het transcript.** Identificeer de kernthema's in de woorden van de deelnemers — niet vertaald naar jargon. Dus niet "strategische heroriëntatie" maar "we moeten het anders gaan doen."
2. **Genereer een eerste concept-document.** Gebruik hun formuleringen, hun toon, hun voorbeelden. Het document is van hen, niet van AI.
3. **Bij elk onderdeel: selecteer quotes** die het scherpst verwoorden wat er gezegd werd. Letterlijk citaat, geen parafrase.
4. **Frustraties mogen er zijn** zoals ze uitgesproken zijn. Niet herformuleren naar "constructieve feedback." Frustratie is brandstof — het laat zien waar mensen om geven.

### Pad B — Basisdiscussie + feedback (volgende groep)
1. **Vergelijk het eerdere concept met de nieuwe feedback.** Wat bevestigt de nieuwe groep? Wat scherpen ze aan? Wat spreken ze tegen?
2. **Genereer een herziene versie.** Meest recente feedback is leidend.
3. **Verantwoord wat er veranderd is en waarom.** Per wijziging: "[Dit onderdeel] is aangepast omdat [groep X] aangaf dat [concreet punt]." Niet: "diverse aanpassingen doorgevoerd." Dit maakt het proces zichtbaar voor de volgende groep.
4. **Gebruik het eerdere concept als context,** maar baseer de herziene versie op de oorspronkelijke transcripten. Eerdere AI-output is hulpmiddel, niet bron.

---

## Voor beide paden

De prompt moet de AI ook het volgende laten doen:

1. **Eigenaarschapssignalen markeren.** Dit is cruciaal:
   - Actief taalgebruik: "ik ga dit oppakken", "wij willen dit samen doen" → hier zit commitment
   - Passief taalgebruik: "er moet iets gedaan worden", "men zou moeten..." → verantwoordelijkheid wordt buiten de groep gelegd
   - Verwerk dit verschil in het document. Waar mensen eigenaarschap tonen, gebruik hun woorden. Waar ze afstand nemen, benoem dat eerlijk.

2. **Spanningen benoemen als keuzemomenten.** Niet wegwerken alsof er consensus is als die er niet is:
   - Niet: "De groep is het erover eens dat..."
   - Wel: "Er is een spanning tussen [A] en [B]. Beide kanten werden benoemd. Dit is een bewuste keuze."

3. **Onverwachte verbanden als observatie + open vraag.** Niet: "Er is een verband tussen X en Y." Wel: "Groep 1 noemde [X], groep 3 [Y]. Zou hier een gedeelde ervaring zitten?" — nooit als conclusie.

4. **Afwezigheden als observatie + vraag.** "Niemand noemde [onderwerp]. Is dit bewust, of is het iets om nog te verkennen?"

5. **Lacunes eerlijk benoemen.** Waar mist informatie? Wat is niet besproken? Dit helpt de volgende groep om gericht bij te dragen.

---

## Output-structuur (contextafhankelijk)

Pas het format aan op basis van mijn antwoorden, maar handhaaf altijd dit onderscheid:
- **Het concept zelf:** in de woorden van de deelnemers. Dit is hun document.
- **"Wat AI opmerkt (ter inspiratie)":** elke observatie als combinatie van waarneming + open vraag. Niet: "Er is een patroon." Wel: "[Observatie]. Zou dit iets zijn om verder te verkennen?" Expliciet gelabeld. "Dit zijn observaties en vragen, geen conclusies. De groep bepaalt wat hiermee te doen."

### Afsluiting

Sluit het document af met:
1. Een transparantie-blok: "Dit concept is opgesteld door AI op basis van jullie gesprek. Het is een levend document — een startpunt, geen eindproduct."
2. Een uitnodiging: "Klopt dit beeld? Wat mist er? Wat zou je anders zeggen?"

---

## Kwaliteitscheck

Laat de prompt de AI aan het einde zichzelf controleren:
- Zou de groep die net sprak zichzelf herkennen in dit document?
- Gebruik ik hun woorden, of heb ik het vertaald naar jargon?
- Is de verantwoording van wijzigingen concreet genoeg?
- Presenteer ik spanningen als keuzes, niet als opgeloste problemen?
- Zijn onverwachte verbanden als vragen geformuleerd?
- Mogen frustraties bestaan zoals ze uitgesproken zijn?
- Staat er een transparantie-blok en uitnodiging aan het einde?
```

---

## Wat heb je nodig?

Ongeacht de werkvorm, dit is de basisuitrusting:

- [ ] **Transcriptie per tafel:** telefoon met transcriptie-app (Dembrane, of vergelijkbaar). Op niet-storen, aan de lader.
- [ ] **Scherm of projector:** om AI-output te tonen aan de groep (bij "na elkaar" en "doordraaien")
- [ ] **Tafelhost of voorzitter:** iemand die het gesprek begeleidt en de AI-output introduceert
- [ ] **Voorbereide prompts:** getest vóór de sessie. Dezelfde prompt per tafel maakt resultaten vergelijkbaar.
- [ ] **Draaiboek met opnamemomenten:** wanneer start je de opname, wanneer stop je, wat doet AI daartussen?
- [ ] **Post-its, stiften, tijdbalk** (optioneel): fysieke elementen helpen om abstract naar concreet te gaan

**Tip:** test je prompt de dag vóór de sessie op een eerder transcript. Dan weet je wat je kunt verwachten.

---

## Welke werkvorm past bij jou?

| Je wilt... | Kies | Waarom |
|------------|------|--------|
| Groepen hun eigen gesprek laten voeren, achteraf vergelijken | **Parallel** | Geen sturing, maximale rijkheid per tafel |
| Groepen op elkaars werk laten reageren | **Na elkaar** | Voortbouwen via de voorzitter, losse analyses bewaren |
| Een document iteratief verrijken met meerdere groepen | **Doordraaien** | Live snelheid, elke groep ziet het resultaat van de vorige |
| Mensen laten wennen aan AI als werkwijze | **Doordraaien** (als warm-up) | Zichtbaar maken hoe AI werkt voordat de echte sessie begint |

Je kunt werkvormen combineren. Het transformatieplan-voorbeeld combineerde parallel (3 thema-tafels) met na elkaar (roulatie). De Amsterdam-sessie begon met doordraaien als warm-up en ging daarna over op parallel.

---

## En dan? De lus

De sessie is voorbij. Je hebt analyses, syntheses, misschien concept-documenten. Wat doe je ermee?

**Terugkoppeling aan de groep:** Laat mensen hun eigen woorden terugzien. "Dit is wat jullie zeiden. Herkennen jullie dit?" De herkenningstest: als deelnemers denken "ja, dat zeiden wij" is het gelukt. Als het klinkt als een consultant, dan niet.

**Naar de volgende sessie:** De output van vandaag kan de input worden van de volgende keer. "Vorige keer kwam bij elke tafel hetzelfde terug. Daar beginnen we vandaag mee." Zo wordt elke sessie een bouwsteen, niet een los gesprek.

**Van analyse naar interventie:** De synthese vertelt je niet alleen wat er gezegd is, maar waar de verbindingen zitten. Mensen die dezelfde worsteling delen zonder het van elkaar te weten. Dat zijn de haakjes die je kunt gebruiken om mensen te verbinden: in de volgende sessie, in informele ontmoetingen, of tussen groepen die niet bij elkaar zaten.

---

## Spanningen

**Sturen versus loslaten**
Als je de AI-output toont tussen rondes, stuur je de volgende groep. Ze reageren op wat er staat, niet op wat ze zelf hadden bedacht. De spanning: verlies je onbevangen input door te veel te laten zien?

*Mijn aanpak:* Bij parallel speelt dit niet: elke tafel voert een onafhankelijk gesprek, en de synthese vindt achteraf plaats, wanneer alle groepen al uitgesproken zijn. Er is geen moment waarop AI-output het gesprek kan sturen. Bij na elkaar en doordraaien is het een bewuste keuze: je wilt voortbouwen, niet opnieuw beginnen. Maar begin altijd met "klopt dit beeld?" voordat je verder gaat. Dat is geen formaliteit; het is de terugkoppeling naar de groep die net gesproken heeft.

**Techniek versus aandacht**
Telefoon op tafel, opname aan, AI ertussen. Het risico: de techniek leidt af van het gesprek. De spanning: hoe houd je de focus op de mensen?

*Mijn aanpak:* De tafelhost is de sleutel. Die begeleidt het gesprek, niet de techniek. "Vergeet de telefoon, die luistert mee. Vertel."

---

## Veilige uitgangspunten

- [ ] Dezelfde prompt per tafel (vergelijkbaarheid)?
- [ ] Prompts getest vóór de sessie?
- [ ] Draaiboek met opnamemomenten duidelijk?
- [ ] Tafelhost gebriefd over hun rol?
- [ ] Scherm beschikbaar voor terugkoppeling?
- [ ] Herkenningstest gepland: "klopt dit beeld?"

---

## Probeer dit zelf

*Je hebt een aankomende sessie met meerdere groepen nodig.*

1. **Kies je werkvorm.** Parallel als je wilt vergelijken. Na elkaar als groepen op elkaar moeten voortbouwen. Doordraaien als je live een document wilt opbouwen.

2. **Ontwerp je vragen eerst.** Voordat je aan AI denkt: welke puzzelstukjes heb je nodig? In welke volgorde? [Prompt de mensen eerst](../fase-2/prompt-mensen-eerst.md) helpt je hierbij.

3. **Maak je prompts klaar.** Gebruik de meta-prompt van je gekozen werkvorm — die genereert alles wat je nodig hebt. Test op een eerder transcript. Kijk of de output bruikbaar is: herken je wat er gezegd werd?

4. **Bereid de terugkoppeling voor.** Bij parallel: plan een moment aan het einde om de synthese te delen. Bij na elkaar: brief de voorzitter op hoe ze de AI-output introduceren. Bij doordraaien: zorg dat het scherm klaarstaat.

5. **Na afloop: leg vast wat werkte.** Niet alleen de inhoud, maar ook het proces. Wat zou je volgende keer anders doen?

---

## Gerelateerde technieken

- Hoe je vragen ontwerpt die goede input opleveren: [Prompt de mensen eerst](../fase-2/prompt-mensen-eerst.md) beschrijft hoe je vanuit het sessiedoel terugwerkt naar de juiste vragen en puzzelstukjes
- Het kernprincipe (eerst los analyseren, dan synthetiseren): [Fase 3 introductie](../../fase-3-schaal.md)
- Van één gesprek naar een plan: [Gesprek naar plan](../fase-2/gesprek-naar-plan.md)
- Verschuivingen volgen over langere trajecten (meerdere sessies over weken of maanden): [Patronen over tijd](patronen-over-tijd.md)
- Live reflectie tijdens het gesprek zelf: [Live reflectie met AI](../fase-2/live-reflectie-met-ai.md)

---

← [Vorige: Patronen over tijd](patronen-over-tijd.md) | [Terug naar Fase 3: Schaal](../../fase-3-schaal.md) | [Volgende: Eigenaarschap zien groeien](eigenaarschap-groei.md) →

---

*"De facilitators hadden de puzzelstukjes al in blokjes gehakt. Mijn rol was om met AI op te halen wat zij hadden geoogst."*
