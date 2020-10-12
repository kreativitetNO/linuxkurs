# Jobb-/prosesshåndtering

Kommandoer som blir gått gjennom i denne filen:

    top
    ps
    jobs
    kill
    sleep
    fg
    bg

# Se hva som bruker ressurser på maskinen

`Top` likner litt på "Task Manager" i Windows, bare at det er tekstbasert.

    > top

# Se og kontrollere hvilke prosesser som kjører

For å se hvilken prosesser som kjører kan vi bruke kommandoen `ps` med forskjellige parametre.

    > ps
    > ps -a
    > ps -aF

Vi kan avslutte et program med kommandoen `kill`. Det er viktig å huske på at vi kun kan avslutte kommandoer vi har startet selv.

    > kill <PID>

Lange jobber kan settes i bakgrunn ved å enten avslutte de med &:

    > sleep 10 &

Eller mens de kjører ved å trykke `ctrl-Z`. Hvis vi bruker `ctrl-Z` blir jobben satt på pause. Da kan vi bruke `bg %[jobbnummer]` for å starte den igjen.

Når vi putter jobber i bakgrunnen kan vi bruke `jobs` kommandoen for å se hva som kjøres.

    > jobs

Hvis vi vil avslutte en jobb som går i bakgrunnen kan vi bruke `kill`.

    > kill %[jobb nummer]

Vi kan også bruke kommandoen `fg` for å ta jobben tilbake til forgrunnen igjen.
