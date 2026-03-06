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

**De prompt:** Twee prompts in tandem: een analyse-prompt die je bij elke tafel gebruikt (dat maakt de resultaten vergelijkbaar), en een synthese-prompt die de analyses naast elkaar legt. Kopieer de prompt hieronder; die helpt je om beide prompts te maken voor jouw sessie.

<ProbeerStory experiment="in-de-sessie"></ProbeerStory>

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

<ProbeerStory experiment="in-de-sessie-sequential"></ProbeerStory>

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

<ProbeerStory experiment="in-de-sessie-doordraaien"></ProbeerStory>

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
