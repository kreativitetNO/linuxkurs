# Finne filer eller innhold

Kommandoer som blir gått gjennom i denne filen:

    grep
    find

For å finne alle filer som inneholder ordet "Hest":

    > grep Hest *

Merk at vi ikke finner noe hvis vi skriver:

    > grep hest *

For å slå av "case-sensitivity" bruker vi parameteren `-i`:

    > grep -i hest *

For å finne uttrykk med mellomrom å vi bruke anførselstegn:

    > grep "Egg og Bacon" *

For å bruke regulære uttrykk bruker vi:

    > grep --regexp "H.s" *

Vi får tilgang til mer avanserte regulære uttrykk med `-E`:

    > grep -E --regexp "H(a|e)s" *

For å lete gjennom filer i underkataloger også må vi bruke parameteren `-r`. Da kan vi også droppe `*` siden default for `-r` er at den tar utgangspunkt i nævårende katalog:

    > grep -r Hest

For å finne filer bruker vi `find`:

    > find . -name aaa*

For å bare lete etter kataloger eller filer bruker vi:

    > find . -type d -name eks*
    > find . -type f -name eks*

# Nyttige ressurser

- `man find`
- `man grep`