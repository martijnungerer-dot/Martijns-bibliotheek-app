# MeerLezen: traject en roadmap

MeerLezen wordt in zes fases gebouwd, van prototype tot app die de schoolbibliotheek echt gebruikt; elke fase levert iets werkends op en de stappen met leerlinggegevens wachten op akkoord van de school.

## Uitgangspunten

**Af** betekent: kinderen van de school gebruiken MeerLezen op een schooltablet en op een telefoon om boeken te vinden, te beoordelen en te lenen, en de vriend kan het zelf beheren.

- **Samen bouwen.** De vriend zit aan het stuur, Martijn denkt mee. Elke mijlpaal is iets wat de vriend zelf kan uitleggen.
- **Elke fase levert iets werkends op.** Geen fase eindigt met een halve app.
- **Privacy door ontwerp.** Tot en met fase 3 gebruiken we geen leerlinggegevens. Vanaf fase 4 alleen na akkoord van de school.
- **AI bij het bouwen, niet bij het kind.** AI schrijft en controleert inhoud vooraf; kinderen praten niet vrij met een AI.
- **Klein en minimalistisch.** Weinig tekst, grote knoppen, alleen wat nodig is.
- **Planning in sessies, niet in data.** Een sessie is 60 tot 90 minuten samen. Datums vullen we in zodra het ritme duidelijk is.

## Werkstromen

Het project bestaat uit zeven onderdelen die los van elkaar kunnen lopen; elk onderdeel heeft hieronder een eigen sectie met mijlpalen.

| Werkstroom | Wat het is | Wie stuurt | Start in fase |
| --- | --- | --- | --- |
| Frontend | De app zelf: schermen, planken, opening, Toet en Bas, beoordelen | Vriend | 1 |
| Catalogus en content | De boeken, thema's per boek, de zinnetjes van Toet en Bas | Vriend, met kinderen | 1 |
| Data en API | Boekgegevens en kaften ophalen via ISBN, later een database voor leespas en reacties | Martijn helpt | 2 |
| AI-inrichting | Hoe en waar AI wordt gebruikt: bij het bouwen, met controle, nooit vrij met kinderen | Samen | 1 |
| Telefoon, tablet en camera | Web-app met icoon, scannen, schooltablet vastzetten | Samen | 3 |
| Privacy en school | Afspraken over gegevens, akkoord van de school | Vriend | 0, doorlopend |
| Samenwerken, Git en testen | Repository, branches en pull requests, testen met kinderen | Samen | 0, doorlopend |

## Roadmap

| Fase | Inhoud | Klaar als | Sessies |
| --- | --- | --- | --- |
| 0 · Voorbereiden | Accounts, repository, checklist; de school is op de hoogte | De vriend heeft het prototype op zijn eigen telefoon geopend | 1 |
| 1 · Fundament | Code in losse bestanden, boekenlijst als JSON, online via GitHub Pages | Een pull request van de vriend staat live online | 2 |
| 2 · Catalogus | Boeken toevoegen met de ISBN-scanner, echte kaften, planken per genre | 25 echte boeken uit de schoolkast staan erin | 2 tot 3 |
| 3 · Ontdekken en telefoon | Zoeken op onderwerp, Toet en Bas, gezichtjes, web-app met icoon, live scanner | Drie kinderen hebben het getest op tablet en telefoon | 3 tot 4 |
| **Beslismoment A** | Akkoord van de school voor een leespas zonder naam | | |
| 4 · Leespas en reacties | Database, leespas met avatar, voorkeuren, tips na goedkeuring | Eén groep gebruikt de leespas een maand lang | 3 tot 4 |
| **Beslismoment B** | Akkoord van de school voor het bijhouden van uitleningen | | |
| 5 · Uitlenen en overdracht | Uitlenen en terugbrengen, groepsdoel in procenten, beheerhandleiding | De vriend beheert de app een maand zonder hulp | 2 tot 3 |

Fase 0 tot en met 3 werken zonder leerlinggegevens en leveren samen al een complete, anonieme app op; fase 4 en 5 starten pas na akkoord van de school. In totaal 13 tot 17 sessies.

## Fases en mijlpalen

Elke fase heeft een **klaar als**-zin: pas als die klopt, gaan we door. Het aantal sessies is een schatting om mee te beginnen.

### Fase 0 · Voorbereiden (1 sessie)

- [ ] Checklist van de vriend afgerond: accounts, GitHub-uitnodiging, Claude-account
- [x] Repository `Martijns-bibliotheek-app` gevuld met prototype en README
- [ ] Directeur of ICT-coördinator weet wat we bouwen
- [ ] **Klaar als:** de vriend heeft het prototype op zijn eigen telefoon geopend

### Fase 1 · Fundament (2 sessies)

- [ ] Code opgesplitst in losse bestanden: HTML, CSS, JavaScript, boekenlijst
- [ ] Boekenlijst als apart JSON-bestand dat de app inleest
- [x] GitHub Pages aan; de app staat online op een vast adres
- [ ] Werkafspraak branches en pull requests in de README
- [ ] **Klaar als:** een pull request van de vriend staat live online

### Fase 2 · Catalogus (2 tot 3 sessies)

- [ ] Boek toevoegen door het ISBN te scannen; titel, schrijver en kaft komen automatisch binnen
- [ ] Echte kaften via Open Library, met de getekende kaft als terugval
- [ ] Planken per genre, stickerkleuren gelijk aan de echte kast
- [ ] **Klaar als:** 25 echte boeken uit de schoolkast staan erin

### Fase 3 · Ontdekken en telefoon (3 tot 4 sessies)

- [ ] Zoeken op onderwerp met thema's en synoniemen per boek, nagelopen door de vriend
- [ ] Toet en Bas met vooraf geschreven zinnetjes
- [ ] Beoordelen met gezichtjes en vaste stickers, anoniem
- [ ] Web-app met eigen icoon op het beginscherm, live scanner, werkt zonder internet
- [ ] Schooltablet vastgezet op de app, terug naar start na 60 seconden
- [ ] **Klaar als:** drie kinderen hebben het getest op tablet en telefoon

**Beslismoment A:** akkoord van de school voor een leespas zonder naam.

### Fase 4 · Leespas en reacties (3 tot 4 sessies)

- [ ] Database ingericht met strikte toegangsregels
- [ ] Leespas met QR-code en avatar; voorkeuren en gelezen boeken, nooit zoekopdrachten
- [ ] "Als je dit leuk vond" op basis van de leespas
- [ ] Korte tips van kinderen, pas zichtbaar na goedkeuring door de juf of meester
- [ ] **Klaar als:** één groep gebruikt de leespas een maand lang

**Beslismoment B:** akkoord van de school voor het bijhouden van uitleningen.

### Fase 5 · Uitlenen en overdracht (2 tot 3 sessies)

- [ ] Uitlenen en terugbrengen met de leespas en het ISBN
- [ ] Overzicht te laat, en het groepsdoel in procenten met echte cijfers
- [ ] Korte beheerhandleiding: boek toevoegen, tip goedkeuren, nieuw schooljaar starten
- [ ] **Klaar als:** de vriend beheert de app een maand zonder hulp

## Werkstroom Frontend

De frontend is wat kinderen zien en aanraken; het prototype is het startpunt, we bouwen het om tot losse, onderhoudbare bestanden.

- **Techniek:** gewone HTML, CSS en JavaScript, zonder framework. Dat houdt het leesbaar voor een beginner en draait overal.
- **Opbouw:** een bestand per scherm (start, plank, boek, zoeken, scan, Toet en Bas, verras me) en een apart bestand met kleuren en lettertypes.
- **Ontwerpregels:** telefoon eerst, grote knoppen, weinig tekst, werkt ook met "minder beweging" aan.

| Mijlpaal | Fase | Klaar als |
| --- | --- | --- |
| Prototype opgesplitst in bestanden | 1 | De app ziet er hetzelfde uit als het prototype |
| Boekenlijst ingelezen uit JSON | 1 | Een boek toevoegen kan zonder de code aan te raken |
| Echte kaften met terugval | 2 | Een boek zonder kaft toont de getekende versie |
| Zoeken, Toet en Bas, beoordelen | 3 | Alle schermen van het prototype werken met echte boeken |
| Leespas-scherm | 4 | Een kind ziet zijn eigen avatar en tips |
| Uitleenscherm voor de vriend | 5 | Uitlenen kost minder dan een minuut per boek |

## Werkstroom Catalogus en content

De inhoud maakt de app: echte boeken uit de schoolkast, goede thema's per boek en zinnetjes die kinderen leuk vinden.

- **Boekgegevens per boek:** ISBN, titel, schrijver, groep, genre, drie trefwoorden, thema's, een korte zin "waarom lezen", stickerkleur.
- **Thema's en synoniemen:** Claude stelt ze voor, de vriend loopt ze na. Zware thema's (scheiding, pesten, verdriet, eenzaamheid) altijd door een volwassene gecontroleerd.
- **Zinnetjes van Toet en Bas:** één bestand met alle teksten, zodat de vriend ze kan aanpassen zonder in de code te zoeken.
- **Kinderen doen mee:** laat een paar kinderen Toet en Bas tekenen of nieuwe zinnetjes bedenken.

| Mijlpaal | Fase | Klaar als |
| --- | --- | --- |
| Sjabloon voor een boek | 1 | Elk veld heeft een uitleg in de README |
| Eerste 25 echte boeken | 2 | Ingevoerd via de scanner, gecontroleerd |
| Thema's en synoniemen | 3 | Elk boek heeft er minstens drie, nagelopen |
| Tekstbestand Toet en Bas | 3 | Minstens 50 zinnetjes, nagelopen door de vriend |
| Hele schoolkast ingevoerd | 5 | Telling klopt met de inventarisatie |

## Werkstroom Data en API

Tot en met fase 3 is er geen eigen server nodig: de boeken staan in een JSON-bestand in de repository. Pas vanaf fase 4 komt er een database bij.

**Fase 2: boekgegevens ophalen**

- Bij het scannen haalt de app titel, schrijver en kaft op via de Open Library-API, op basis van het ISBN. Daar is geen sleutel voor nodig.
- Niet elk Nederlands boek staat erin. Dan vult de vriend het zelf in en krijgt het boek de getekende kaft.
- Gegevens worden één keer opgehaald en in de boekenlijst bewaard, niet bij elk bezoek opnieuw.

**Fase 4 en 5: eigen database**

Voorstel: Supabase, gratis te beginnen, met een kant-en-klare API zodat we geen eigen server hoeven te bouwen.

| Tabel | Wat erin staat | Wat er nooit in staat |
| --- | --- | --- |
| Leespassen | Pas-code, avatar, lichte voorkeuren | Naam, groep, zoekopdrachten |
| Beoordelingen | Boek, gezichtje, sticker, pas-code | Beoordelingen van boeken met zware thema's |
| Tips | Tekst, boek, status (wacht, goedgekeurd, afgewezen) | Wie de tip schreef |
| Uitleningen | Boek, pas-code, datum uit, datum terug | Namen |

- **Toegangsregels (Row Level Security):** kinderen kunnen alleen lezen wat goedgekeurd is en alleen aan hun eigen pas schrijven.
- **Beheer:** goedkeuren en uitlenen alleen na inloggen door de vriend.
- **Geheime sleutels nooit in de app of de repository.** In de app staat alleen de openbare sleutel, die door de toegangsregels wordt beschermd.

| Mijlpaal | Fase | Klaar als |
| --- | --- | --- |
| ISBN-opzoeken via Open Library | 2 | Een gescand boek vult zichzelf in |
| Database met toegangsregels | 4 | Een test zonder inlog kan niets lezen wat niet goedgekeurd is |
| Beheer met inlog | 4 | Alleen de vriend kan tips goedkeuren |
| Uitleningen | 5 | Uit en terug klopt met een handmatige telling |

## Werkstroom AI-inrichting

AI werkt in MeerLezen achter de schermen: het helpt de makers, een volwassene controleert alles, en kinderen praten nooit vrij met een AI.

| Waar | Wat AI doet | Wie controleert | Wanneer |
| --- | --- | --- | --- |
| Bouwen | Code schrijven en uitleggen, samen met de vriend in Claude Code | De vriend leest elke pull request | Fase 1 en verder |
| Catalogus | Thema's, synoniemen en een korte zin per boek voorstellen | De vriend loopt elk boek na | Fase 2 en 3 |
| Toet en Bas | Zinnetjes schrijven in hun stem | De vriend, eventueel samen met kinderen | Fase 3 |
| Tips van kinderen | Mogelijke namen, scheldwoorden of telefoonnummers markeren | Juf of meester keurt goed | Fase 4, optioneel |

**Wat we niet doen:**

- Geen open chat met een AI voor kinderen, ook niet via Toet en Bas.
- Geen invoer van kinderen live naar een AI-dienst sturen. Zoeken gebeurt op de thema's die vooraf zijn gemaakt.
- Het kaftlezen door Claude in het prototype blijft een demo; in de echte app vervangt de ISBN-scanner het.

**Als er later toch AI in de app komt** (bijvoorbeeld voor het markeren van tips), dan loopt dat via een kleine serverfunctie die de sleutel geheim houdt, zonder dat er iets wordt bewaard, en pas na akkoord van de school.

| Mijlpaal | Fase | Klaar als |
| --- | --- | --- |
| Vaste opdracht (prompt) voor thema's per boek | 2 | Resultaat is herhaalbaar en staat in de repository |
| Controleproces in de README | 2 | Elk door AI voorgesteld thema heeft een vinkje "nagelopen" |
| Zinnetjes Toet en Bas | 3 | Nagelopen, geen schuldgevoel of druk erin |

## Werkstroom Telefoon, tablet en camera

MeerLezen wordt een web-app: één code die op telefoon, tablet en laptop draait, met een eigen icoon op het beginscherm en zonder App Store.

- **Web-app (PWA):** een manifest en een icoon maken de app installeerbaar; een service worker laat hem zonder internet werken. Installeren via **Share → Add to Home Screen** (iPhone) of **⋮ → Add to Home screen** (Android).
- **Camera:** een live scanner die de streepjescode leest zodra die in beeld is. Een foto maken blijft de terugval.
- **Schooltablet:** vastzetten op de app via **Guided Access** (iPad) of **App pinning** (Android), terug naar start na 60 seconden.
- **Een eigen telefoonweergave** met een tabbalk onderin en swipen door boeken kan later, als testen laat zien dat kinderen dat fijner vinden.

| Mijlpaal | Fase | Klaar als |
| --- | --- | --- |
| Scanner via foto (zoals prototype) | 2 | Een echt boek uit de kast wordt herkend |
| Live scanner | 3 | Herkenning binnen een paar seconden, ook bij weinig licht |
| Installeerbare web-app | 3 | Icoon op het beginscherm, opent zonder browserbalk |
| Werkt zonder internet | 3 | Catalogus en Toet en Bas werken in vliegtuigmodus |
| Tablet-opstelling in de bibliotheek | 3 | Een kind kan de app niet per ongeluk verlaten |

## Werkstroom Privacy en school

De repository is openbaar en het gaat om kinderen; daarom groeit de afstemming met de school mee met wat de app bewaart.

| Fase | Wat de app bewaart | Wat de school moet weten of goedkeuren |
| --- | --- | --- |
| 0 tot 3 | Alleen boeken; beoordelingen anoniem | Informeren: wat we bouwen en dat er geen leerlinggegevens in zitten |
| 4 | Leespas zonder naam, voorkeuren, goedgekeurde tips | Akkoord (beslismoment A): een pseudonieme pas is juridisch nog steeds een persoonsgegeven |
| 5 | Uitleningen per pas | Akkoord (beslismoment B), mogelijk met de privacyfunctionaris van de school |

- **Vaste regels:** geen namen in de app of de repository, zoekopdrachten en foto's nooit bewaren, geheime sleutels nooit in de code.
- **Bij zware onderwerpen:** de hulpregel met De Kindertelefoon (0800-0432) blijft altijd staan.
- **Reacties pas tonen vanaf een paar beoordelingen**, zodat niet terug te leiden is wie wat vond.

| Mijlpaal | Fase | Klaar als |
| --- | --- | --- |
| School geïnformeerd | 0 | Directeur of ICT-coördinator weet ervan |
| Afsprakenblad gegevens | 3 | Een pagina in de repository die de school kan lezen |
| Akkoord leespas | 4 | Schriftelijk akkoord, ook per e-mail |
| Akkoord uitlenen | 5 | Schriftelijk akkoord, bewaartermijn afgesproken |

## Werkstroom Samenwerken, Git en testen met kinderen

Dit onderdeel zorgt dat de vriend het samen bouwen echt beleeft: hij typt, Martijn denkt mee, en kinderen bepalen mee wat goed is.

- **Sessies:** 60 tot 90 minuten via beeldbellen, de vriend deelt zijn scherm en zit aan het stuur. Eindig elke sessie met iets wat werkt.
- **Git:** ieder werkt op een eigen branch en voegt samen via een pull request; de ander keurt goed. Claude Code op het web, met deze repository gekozen bij de start van een sessie.
- **Takenbord:** de mijlpalen uit dit document als issues in GitHub, zodat jullie allebei zien wat open staat.
- **Testen met kinderen:** na fase 3 en na fase 4 drie kinderen een kwartier laten spelen. Kijk wat ze doen, vraag wat ze missen.

| Mijlpaal | Fase | Klaar als |
| --- | --- | --- |
| Repository gevuld en GitHub Pages aan | 0 en 1 | De app staat online |
| Eerste pull request van de vriend | 1 | Goedgekeurd door Martijn en live |
| Mijlpalen als GitHub-issues | 1 | Elke mijlpaal uit dit document heeft een issue |
| Eerste testronde met kinderen | 3 | Drie bevindingen opgeschreven en ingepland |
| Tweede testronde | 4 | Idem, met de leespas |

## Risico's en wat we dan doen

| Risico | Wat we dan doen |
| --- | --- |
| De school geeft geen akkoord voor de leespas | De app blijft op fase 3: volledig bruikbaar en anoniem |
| Martijn bouwt sneller en neemt het over | Vaste regel: de vriend typt; Martijn vraagt "wat zou je Claude nu vragen?" |
| Nederlandse boeken ontbreken in Open Library | Handmatig invullen, getekende kaft als terugval |
| Iemand typt echte namen in een tip | Tips alleen zichtbaar na goedkeuring; filter markeert namen |
| Een geheime sleutel belandt in de openbare repository | Sleutel direct intrekken en vervangen; vooraf een controle die commits met sleutels tegenhoudt |
| De motivatie zakt na een paar sessies | Elke sessie eindigt met iets werkends; testen met kinderen geeft energie |
| De vriend raakt afhankelijk van Martijn | Fase 5 eindigt pas als hij een maand zelf beheert, met handleiding |

## Open vragen

- [ ] Hoe vaak kunnen we een sessie plannen: elke week, om de week?
- [ ] Voor welke groepen is de bibliotheek vooral bedoeld?
- [ ] Hoeveel boeken staan er ongeveer in de kast?
- [ ] Is er een schooltablet beschikbaar voor de bibliotheek?
- [ ] Wie bij de school beslist over beslismoment A en B?
- [ ] Heeft de vriend een betaald Claude-abonnement voor Claude Code, of werken we op het account van Martijn?
- [ ] Blijft de naam MeerLezen, of bedenken de kinderen er een?
