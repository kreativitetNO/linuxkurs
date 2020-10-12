# Jobbe i shell (bash) - Del 2

Kommandoer som blir gått gjennom i denne filen:

    alias   # Lager en alias av noe vi bruker ofte
    history # Viser kommandohistorikken
    head    # Filtrerer så vi kun ser begynnelsen av filen
    tail    # Omvendt av head

## Globbing

Vi kan gjøre ting med flere filer samtidig ved hjelp av tegnene `?` og `*`.

    > ls a?.txt

Denne kommandoen lister ut alle filer som begynner på 'a', har 1 vilkårlig tegn, og avsluttes med '.txt'.

## Tab completion

Lange kommandoer og filnavn kan vi skrive fortere ved hjelp av tab-completion:

    > gre[tab]

## Piping

Ved hjelp av symbolet `|` kan vi ta det som kommer ut av en kommando, og bruke det som input til en annen kommando:

    > cat FilHierarki.MD | less

(Tips: Ved å trykke `/` mens vi er i `less` kan vi søke. Bruk `n` og `shift-n` for å finne neste og forrige søkeresultat.)

    > cp a

## Kjeding

Vi kan kjede sammen flere kommandoer med `&&`. Da vil første kommando kjøres først, og hvis det går bra kjøres neste kommando.

    > cat aaa.txt && cat

# Kommando output til fil

Ved å bruke `>` (og `<`, `1>` osv) kan vi omdirigere outputen fra en kommando.

    > ls /etc > EtcFiler.txt

# Aliaser

Aliaser kan brukes til å lage en enkel versjon av en kommando som er komplisert eller som vi kjører ofte.

    > alias lsa='ls aaa.txt'

Disse kan gjerne legge i `.bashrc` så de blir tilgjengelige hele tiden. Vi kan bruke `type` for å finne hva en alias blir oversatt til.

    > type ll

# Historikk

Vi kan bruke opp og ned pil for å gå gjennom kommandoer som er kjørt tidligere. Disse kan redigeres før de kjøres på nytt.

Ved å bruke kommandoen `history` kan vi få en oversikt over alle kommandoene som er i historikken. Dette kan kombineres med `head` og `tail`.

    > history | head -n 5

# Noen tidsbesparende triks til på tampen

`!!` kjører forrige kommando en gang til. `![kommando]` kjører kommandoen med de samme parametrene den ble kjørt med forrige gang.

Ved å trykke `<esc> 1` får vi parametrene til den forrige kommandoen vi kjørte.

Vi kan rense konsollen ved å trykke `<ctrl>-l`.
