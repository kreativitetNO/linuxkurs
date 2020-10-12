# Hvordan få hjelp

I tillegg til Google og bøker, har Linux sitt eget relativt fyldige hjelpesystem. Siden vi går gjennom disse nå, vil ikke dokumentene som kommer etter denne inneholde like fyldige beskrivelser som dokumentet om navigering. De vil heller fokusere på tips som ikke nødvendigvis kommer like enkelt fram i dokumentasjonen.

De fleste kommandoer kan du få hjelp for ved å skrive `--help` etter kommandoen.

    > ls --help

Du kan få langt mer hjelp ved hjelp av `man` kommandoen.

    > man ls

En mer moderne versjon av `man` heter `info`.

    > info ls

Hvis du ikke er helt sikker på hva kommandoen heter kan du bruke `apropos` og et søkeord.

    > apropos copy

Enkelte kommandoer fins i flere varianter.

    > apropos printf

Legg merke til at det fins 2 versjoner av printf. For å komme til varianten som har `(3)` etter seg, skriver man:

    > man 3 printf

Legg også merke til at manualene inneholder informasjon om C biblioteket.