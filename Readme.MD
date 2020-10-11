# Linux Kurs

Disse filene er tenkt brukt av de som deltar på mitt introduksjonkurs om Linux. Presentasjonen fra kurset kan sees [her](Presentasjon.pdf).

# Andre filer

- [Grunnleggende kommandoer](Kommandoer.MD)

# Alternativer for å kjøre Linux

- Direkte fra USB
- Virtuell maskin
- Dual boot
- Rent
- Windows Subsystem for Linux

## Direkte fra USB

Last ned ISOen til den distribusjon du vil teste (forutsatt at den støtter å bli kjørt direkte fra USB). Ubuntu støtter dette.
- [Last ned](https://ubuntu.com/download/desktop/thank-you?version=20.04.1&architecture=amd64) Ubuntu.
- [Instrukser](https://ubuntu.com/tutorials/try-ubuntu-before-you-install#1-getting-started) for å kjøre Ubuntu rett fra USB pinne

Dette er en "Try before you buy" midlertidlig løsning, og kan få problemer på visse PCer; særlig de som er laget spesielt for Windows som f.eks Surface.

## Virtuall maskin

I Windows 10 Professional eller Educational fins funksjonaliteten [innebygd](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v). Alternativt kan du bruke [VM Workstation Player](https://www.vmware.com/no/products/workstation-player/workstation-player-evaluation.html).

En virtuell maskin kjører "oppå" Windows, så du trenger en PC med nok CPU og RAM til å kjøre begge operativsystemene samtidig. Du trenger en virkelig kraftig PC for å oppleve at det er like fint å bruke som 

## Dual boot

Dual boot betyr at vi installerer begge operativsystemene ved siden av hverandre og kan velge hvilken vi skal starte når vi slår på PCen. Dette kan være litt utfordrende å sette opp, men [instrukser](https://itsfoss.com/install-ubuntu-1404-dual-boot-mode-windows-8-81-uefi/) fins overalt.

Dual boot er det beste av begge verdner når du først får det til. Alt det krever er litt godt med harddisk plass, men hvert OS får til gjengjeld full tilgang til alle HW ressurser uten å måtte gå gjennom et virtualiseringslag.

## Ren Linux installasjon

Per i dag kan "selv bestemor" installere Linux på langt de fleste PCer. Hvis du støter på problemer har Google sannsynligvis svaret.

Fordelen er at du tvinges til å lære å gjøre alt på Linux måten. Med litt erfaring klarer du også å løse de eventuelle utfordringer du møter på selv. Disse er ofte relaterte til PCer som er designet for Windows. Merk at mange PC leverandører i dag leverer PCer med Linux ferdig installert.

## Windows Subsystem for Linux

Der det før eksisterte en slags konkurranse mellom Microsoft og Linux, har dette i større og større grad blitt et samarbeid. Microsoft bidrar til og lager flere Linux produkter enn noensinne. En av de mest ekstreme er [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/).

Dette gir deg en relativt fullverdig Linux opplevelse uten det tjukke og krevende virtualiseringslaget til en virtuell maskin.

## Ting å passe på

Dual boot og rene installasjoner kan føre til at områder (partisjoner) på harddisken blir slettet eller gjort utilgjengelig på en eller annen måte. Alltid ta backup av alt som er viktig før du begir deg ut på en av disse. (Men det gjør vel alle uansett?)

Hvis du angrer, er det lurt å ha en USB og en produktnøkkel for Windows klart så du kan bytte tilbake.

Det kan ta litt tid og kreve litt søking på internett og litt prøving og feiling for å få til en god Linux installasjon, men prosessen kan være veldig lærerikt. Husk at heller ikke alle Windows installasjoner fungerer perfekt før du får lagt inn alle oppdateringer og drivere.