# CodeCrashers

## Handleiding opdrachten inleveren

CodeCrashers maakt gebruik van GitHub om studenten te voorzien van een gestroomlijnd proces om opdrachten in te leveren bij hun docenten, en ervoor te zorgen dat zij vanuit elke locatie bij hun opdrachten kunnen komen. Bovendien zorgt het ervoor dat de betrokken docenten ook te allen tijde bij deze ingeleverde opdrachten kunnen komen, zonder dat er allerlei bestanden heen en weer verstuurd hoeven te worden.

Een bijkomend voordeel is dat er altijd een versiegeschiedenis wordt bijgehouden van enige aanpassingen aan de opdrachten zodat er altijd terug kan worden gegaan naar een eerder tijdstip als er iets fout gaat.

Per cursus wordt een repository aangeboden met daarin de volledige mappenstructuur voor alle opdrachten van die cursus. De student neemt deze mappenstructuur als template waarin hij/zij vervolgens zijn/haar eigen opdrachten gaat plaatsen.

Deze uniformiteit zorgt er enerzijds voor dat de student altijd een bepaalde opdracht eenvoudig kan terugvinden, en de docent ook weet waar hij/zij een bepaalde opdracht kan vinden om deze na te kijken en van feedback te voorzien.

## Inhoudsopgave

- [Inhoud van de repository](#inhoud-van-de-repository)
	- [Mappenstructuur](#mappenstructuur)
	- [Wijzigingen in lesmateriaal](#wijzigingen-in-lesmateriaal)
- [Voorbereiding](#voorbereiding)
	- [Installatie Git](#installatie-git)
	- [GitHub account](#github-account)
- [Werkwijze](#werkwijze)
	- [Repository kopiëren](#repository-kopiëren)
	- [Docenten toegang geven](#docenten-toegang-geven)
	- [Repository clonen](#repository-clonen)
	- [Opdrachten inleveren](#opdrachten-inleveren)
	- [Voortgang aangeven](#voortgang-aangeven)

## Inhoud van de repository

### Mappenstructuur

Elke cursus heeft zijn eigen repository met een eigen mappenstructuur.

Binnen een repository is er één map per les. Per les tref je afzonderlijke mappen aan voor elk van de te maken opdrachten. Binnen de map van een opdracht tref je een `.gitkeep` bestand aan. Dit bestand kun je verder negeren - deze is er puur voor bedoeld zodat GitHub de (anders lege) map wel indexeert.

Er is gekozen om de mapnamen volledig in kleine letters en met dashes (`-`) in plaats van spaties te spellen. Hierdoor komt de mappenstructuur zo veel mogelijk overeen met de structuur van URL's die je ook op internet kunt verwachten. Tevens verzekeren we hiermee dat de volledige mappenstructuur compatibel is binnen een (lokale) ontwikkelserver zoals XAMPP, waar spaties en dergelijke voor problemen kunnen zorgen.

### Wijzigingen in lesmateriaal

ICT is altijd in beweging, en dat geldt ook voor het lesmateriaal van CodeCrashers. Het is dus mogelijk dat de inhoud van een cursus wijzigt terwijl jij er al mee bezig bent. Denk bijvoorbeeld aan een verandering in de volgorde van de lessen of nieuwe opdrachten erbij.

In dergelijke gevallen dien je er zelf zorg voor te dragen dat de structuur van jouw eigen repository weer overeenkomt met het lesmateriaal. Houd je daarbij aan de geldende conventies zodat eventuele nieuwe of veranderde mappen consistent blijven met de rest van de mappenstructuur.

## Voorbereiding

### Installatie Git

Controleer of Git is geïnstalleerd op de computer waar je op wil werken. GitHub draait onder de motorkap namelijk op Git.

Indien je de computer in eigen beheer hebt kun je Git ook zelf installeren via de officiële website. Zie ook: [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

### GitHub account

Om gebruik te kunnen maken van deze repository dien je over een GitHub account te beschikken. Registreer jezelf bij GitHub als je daar nog niet over beschikt. Dat kan via deze URL: [https://github.com/signup](https://github.com/signup).

![GitHub profiel](https://codecrashers.nl/img/github/readme-github-profile.png)

Zorg dat je de volledige URL van je GitHub profiel kopieert en plakt op de profielpagina in het dashboard van je CodeCrashers account. Dit zorgt ervoor dat je docenten altijd snel bij jouw opdrachten kunnen komen.

![GitHub link op CodeCrashers](https://codecrashers.nl/img/github/readme-github-cc.png)

*Zorg dat je de andere instellingen ook bijwerkt, als je dat nog niet gedaan had. In het kader van consistentie en herkenbaarheid heeft het onze voorkeur dat je dezelfde profielfoto gebruikt op GitHub als op CodeCrashers, maar dat is niet verplicht.*

## Werkwijze

### Repository kopiëren

Om gebruik te kunnen maken van de aangeleverde mappenstructuur, dien jij een persoonlijke kopie te krijgen van de beschikbare repository in jouw eigen GitHub account.

Ga naar je repositories tab en klik op de knop "New". Klik vervolgens op de link "Import a repository". Hierin geef je de link op van de repository die je wil kopiëren, bijvoorbeeld [https://github.com/CodeCrashersNL/HTML](https://github.com/CodeCrashersNL/HTML).

Omwille van consistentie dien je je eigen repository exact dezelfde naam te geven als degene die je wil kopiëren.

**Let op:** zorg ervoor dat je bij de privacy-instellingen op de optie "Private" klikt. Om de kwaliteit van de opleiding voor andere studenten te waarborgen willen we namelijk niet dat uitwerkingen van opdrachten publiekelijk toegankelijk worden gemaakt.

![nieuwe repository aanmaken](https://codecrashers.nl/img/github/readme-github-new-repo.png)

De andere instellingen mag je hetzelfde laten. Klik vervolgens op de knop "Create repository".

Als je alles goed hebt gedaan, beschik je nu over een *eigen* HTML (of een ander vak) repository. Controleer nog even of deze inderdaad op "Private" staat. Voel je overigens vrij om de standaard "README.md" met deze handleiding te verwijderen of te vervangen door een eigen readme-bestand.

![private repository](https://codecrashers.nl/img/github/readme-github-private-repo.png)

### Docenten toegang geven

Zodat zij jouw opdrachten kunnen nakijken, is het van belang dat je jouw docenten uitnodigt om jouw repository te kunnen bekijken.
Klik op de knop "Settings" en ga naar "Collaborators" onder "Access".

Klik vervolgens op de knop "Add people" en vul de GitHub usernames of e-mailadressen in van je docenten. Vervolgens kun je ze toevoegen als "Collaborator" aan jouw repository.

Overleg zo nodig met je docenten over wie je wel en niet dient uit te nodigen. Mogelijk kan dat verschillen per cursus.

![collaborator uitnodigen](https://codecrashers.nl/img/github/readme-github-invite-collaborator.png)

### Repository clonen

Je kunt het meest efficiënt werken aan je opdrachten als je deze al direct maakt op de juiste plek in de mappenstructuur.

Om dat te bewerkstelligen dien je een lokale *clone* van je repository te krijgen. De eenvoudigste manier om dat te doen is door middel van Git commando's via een CLI (*Command Line Interface*).

Start een shell op zoals CMD (Windows) of Bash (Unix). Sommige editors zoals Visual Studio Code beschikken over een ingebouwde terminal op - die kun je natuurlijk ook gebruiken.

Navigeer naar de locatie waar je je repository wil downloaden. Om in een shell te navigeren gebruik je `cd ../` om een map omhoog te gaan en `cd {naamvanmap}` om een map dieper te gaan.

*Tip: als je gebruikt maakt van software als XAMPP is het handig om je repository te clonen binnen de `htdocs` folder van XAMPP. Dan beschik je al direct over een werkende webserver als dat nodig is, bijvoorbeeld voor PHP opdrachten.*

Gebruik vervolgens het volgende commando, waarbij je je `{gebruikersnaam]` en `{repository]` vervangt door je eigen gebruikersnaam en de repository die je wil clonen (zonder accolades).

```
git clone https://{gebruikersnaam}@github.com/{gebruikersnaam}/{repository}
```

![repository clonen 1](https://codecrashers.nl/img/github/readme-git-clone-1.png)

Als het goed is wordt je nu gevraagd om in te loggen om Git te autoriseren.

*Tip: als je werkt op een computer waar alleen jij toegang toe hebt kun je eventueel ook gebruik maken van een SSL in plaats van een HTTPS verbinding. Dan hoef je in principe nooit meer opnieuw in te loggen. Zie [de documentatie](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github).*

![repository clonen 2](https://codecrashers.nl/img/github/readme-git-clone-2.png)

Als de authenticatie gelukt is, zal de repository succesvol *gecloned* worden.

![repository clonen 3](https://codecrashers.nl/img/github/readme-git-clone-3.png)

Controleer ten slotte of de mappenstructuur succesvol is aangemaakt in je lokale omgeving. Als dat het geval is, kun je aan de slag met de opdrachten van de cursus.

![repository clonen 4](https://codecrashers.nl/img/github/readme-git-clone-4.png)

Wanneer een opdrachtomschrijving vraagt om een map aan te maken, hoef je dat dus niet meer te doen - deze map heb je immers al. Wanneer een opdrachtomschrijving vraagt om de map van een eerdere opdracht te kopiëren, hoef je alleen nog maar de *inhoud* van die eerdere opdracht te kopiëren.

### Opdrachten inleveren

Elke keer wanneer je één of meerdere opdrachten af hebt gemaakt (of verbeterd), zorg je ervoor dat je deze inlevert door ze te *pushen* naar de bijbehorende GitHub repository. Doe dit zo vaak mogelijk - in ieder geval zodra je een volledige les af hebt, of aan het einde van een werkdag.

Je kunt je bestanden naar GitHub *pushen* door gebruik te maken van Git via een shell. Je kunt verbinden met je GitHub account via HTTPS of SSL. 

Met een *pull* kun je jouw lokale clone synchroniseren met de laatste stand van zaken op GitHub. Dit kan handig zijn wanneer je op verschillende locaties aan je opdrachten hebt gewerkt.

Hiervoor dien je eerst via een shell te navigeren naar de root map van je repository (bijvoorbeeld HTML) en gebruik je vervolgens het commando:

```
git pull
```

![git pull](https://codecrashers.nl/img/github/readme-github-git-pull.png)

Om gewijzigde of toegevoegde bestanden in te leveren voer je achtereenvolgens de volgende commando's uit:

```
git add .
git commit -m "Een optioneel bericht"
git push
```

![git push](https://codecrashers.nl/img/github/readme-github-git-push.png)

### Voortgang aangeven

Het is dus altijd zaak dat je je GitHub repository met opdrachten zo veel mogelijk up-to-date houdt. Wanneer je één of meerdere nieuwe of verbeterde opdrachten op GitHub hebt gezet, dien je je je voortgang zo snel mogelijk bij te werken in CodeCrashers.

Om aan te geven dat je een opdracht af hebt en deze wacht op feedback, verander je de status in het symbool van het klokje.

![opdracht aanbieden](https://codecrashers.nl/img/github/readme-cc-aanbieden.png)

Je docent kan dan vanuit zijn dashboard zien dat er nieuwe opdrachten zijn die beoordeeld dienen te worden.