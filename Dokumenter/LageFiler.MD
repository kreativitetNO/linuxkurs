# Lage filer og kataloger

Skift til linuxkurs katalogen først:

    cd ~/linuxkurs

Kommandoer som blir gått gjennom her:

    mkdir
    rmdir
    rm
    touch
    cat
    less
    cp
    mv
    xxd

Vi lager nye kataloger med:

    mkdir [navn]

Og sletter kataloger:

    rmdir [navn]

Vi kan lage en fil med:

    touch [filnavn]

(Touch lager en fil som ikke eksisterer, eller endrer datoen på filer som allerede eksisterer.)

Filer slette vi med:

    rm [filnavn]

Hvis vi vil slette kataloger med filer kan vi ikke bruke rmdir. Vi må kjøre:

    rm -rf [navn]

Parametrene sier at vi skal slette [navn] _rekursivt_ (alle filer og underkataloger) og med _force_ (at vi ikke får spørsmål om vi er sikre). Vær veldig forsiktig med å skrive denne kommandoen på feil sted.