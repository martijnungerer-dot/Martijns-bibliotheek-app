# Ideeën bibliotheek-app

Een leesapp voor de schoolbibliotheek die kinderen laat ontdekken wat ze leuk vinden, zonder te bewaren waar ze mee zitten.

## Uitgangspunten

- **Leesplezier voorop.** Elke functie moet een kind dichter bij een boek brengen dat het leuk vindt.
- **Privacy door ontwerp, niet door verbod.** We bewaren wat een kind leuk vindt, nooit waar het mee zit.
- **Kiezen in plaats van belonen.** Geen punten of ranglijsten per kind; zelf kiezen en samen iets bereiken motiveert beter.
- **Minimalistisch.** Weinig tekst, grote keuzes, kaften in plaats van tabellen.
- **De schooltablet is de hoofdroute**, de QR-code op een eigen telefoon een extra. Niet elk kind heeft een telefoon bij zich.

## Opening en vormgeving

De opening is kort, en het kind doet zelf iets; dat blijft ook na de tiende keer leuk.

1. **Een boek slaat open** (hooguit 2 seconden, tik om over te slaan). De kaften vallen uit de bladzijden op hun plek op de plank.
2. **Eén vraag: "Waar heb je zin in?"** met vier grote knoppen: *Spannend*, *Grappig*, *Verras me*, *Ik zoek iets over…*
3. **Kleine variatie**: herfstblaadjes in november, een ander welkomstzinnetje 's ochtends dan 's middags.

Ideeën die het van de school maken:

- **Mascotte getekend door de kinderen** (een uitleenkat, een boekenwurm), die knipoogt bij de opening.
- **QR-poster bij de ingang** die eruitziet als een deur of portaal.
- **QR-codes per plank of genre**: wie bij de griezelkast scant, komt op die plank in de app.
- **Kleur per genre**, dezelfde als op de stickers op de echte boeken.
- **Vaste planken**: *Nieuw binnen*, *Populair deze maand*, *Nog nooit geleend* (wie vindt de verborgen parel?).
- **Kioskmodus**: de app op een scherm in de bibliotheek die langs de kaften scrollt.

## Leesmotivatie

Zelf kiezen en samen iets bereiken werkt beter dan punten per kind; ranglijsten motiveren vooral kinderen die al graag lezen.

- **Kinderen tippen kinderen**: een korte tip bij een boek ("Lees dit als je van griezelen houdt"), alleen met de groep erbij.
- **Blind date met een boek**: een knop *Verras me* die een boek toont met alleen drie trefwoorden.
- **Groepsdoel**: het percentage van de klas dat deze maand een boek uitlas, met een meter die volloopt. Geen gegevens per kind nodig.
- **Leesbingo**: vakjes als *een boek over een dier*, *een strip*, *een boek van vóór 1990*.
- **AVI-niveau als filter, niet als etiket**: een zichtbaar niveau kan kinderen afschrikken die "lager" lezen.

## Leesmaatjes Toet en Bas

Een uil en een boekenwurm die kinderen helpen kiezen, met zinnetjes die vooraf zijn geschreven en nagelopen.

- Een gesprek met knoppen, zonder typen: groep, waar heb je zin in, plaatjes of tekst.
- Ze geven elk een eigen tip met de reden erbij; het kind kiest wiens tip.
- Geen schuldgevoel of reeksen, geen open AI-chat. Bij zware onderwerpen spreken ze niet; dan komt de hulpregel.

## Zoeken op onderwerp

Kinderen typen een onderwerp als "alleen voelen" of "gescheiden ouders" en krijgen passende boeken; AI gebruiken we bij het bouwen, niet bij het kind.

| | Live AI in de app | AI vooraf, lokaal zoeken (onze keuze) |
| --- | --- | --- |
| Hoe | Invoer van het kind gaat naar een AI-dienst | Claude maakt per boek eenmalig thema's en synoniemen ("scheiding", "ouders uit elkaar", "twee huizen"); de app zoekt daarin |
| Privacy | Invoer verlaat de app | Er verlaat niets de app |
| Kosten | Per zoekopdracht | Gratis |

Veiligheidslaag:

- Bij zware onderwerpen altijd een rustige regel: "Praat er ook over met iemand die je vertrouwt", plus De Kindertelefoon (0800-0432, gratis).
- Een vaste lijst signaalwoorden (zoals "dood willen", "slaan thuis") toont eerst de hulpregel, daarna pas eventueel boeken.
- Filter op groep of leeftijd.
- Zoekopdrachten worden nooit opgeslagen.
- De tablet gaat na 60 seconden stilstand terug naar het startscherm, zodat het volgende kind niet ziet wat er gezocht is.
- De thema's per boek loopt een volwassene na.

## Beoordelen

Drie gezichtjes in plaats van vijf sterren; dat is voor jonge kinderen makkelijker.

- Twee vragen: *Vond je het een fijn boek?* en *Paste het bij wat je zocht?* De tweede maakt de suggesties steeds beter.
- Opgeslagen wordt alleen boek + beoordeling: geen naam, groep of zoekopdracht.
- Eén beoordeling per boek per apparaat (of per leespas, vanaf fase 4).

## Leespas en voorkeuren

Elk kind krijgt een leespas met QR-code en een zelfgekozen avatar, zonder naam; het profiel leert van wat een kind leuk vindt, niet van waar het mee zit.

| Wordt bewaard bij de pas | Wordt nooit bewaard |
| --- | --- |
| Lichte voorkeuren: spannend, grappig, dieren, strips | Wat er is ingetypt bij *Ik zoek iets over…* |
| Beoordelingen van gewone boeken | Beoordelingen van boeken met zware thema's |
| Gelezen boeken, voor *Als je dit leuk vond…* | Iets wat naar een naam of groep leidt |

Let op: een pseudonieme pas is juridisch nog steeds een persoonsgegeven. Voordat de passen in gebruik gaan, laten we de school het weten.

## Praktisch beheer

- **ISBN scannen met de telefooncamera**: titel, schrijver en kaft automatisch ingevuld (bijvoorbeeld via de gratis Open Library-API).
- **Inventarismodus**: aan het eind van het jaar alles scannen; de app toont wat er mist.
- **Statistieken voor leerkrachten**: populaire genres, boeken die al lang niet geleend zijn.
- **Tablet vastzetten op de app**: iPad via **Settings → Accessibility → Guided Access**, Android via **App pinning**.
- **Geluid standaard uit** en de animatie overslaan als **Reduce Motion** aanstaat.
