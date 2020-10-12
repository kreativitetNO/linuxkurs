# Rettigheter

    -rw-rw-r-- 1 christian christian 1256 okt.  12 13:45 Readme.MD
    drwxrwxr-x 3 christian christian 4096 okt.  12 13:46 Dokumenter/

## De første 10 tegnene

Det første tegnet brukes til spesialverdier. Noen av disse går langt forbi nivået til dette grunnkurset, men dere vil se at det står `d` der for kataloger.

De neste 9 tegnene er egentlig 3 grupper på 3 tegn. Hver gruppe inneholder rwx eller bindestrek. 'r' betyr at noen har leserettigheter, 'w' betyr at noen har skriverettigheter og 'x' betyr at noen har kjørerettigheter på filen.

'Noen' bestemmes av rekkefølgen på de 3 gruppene. De første 3 tegnene gjelder eieren av filen. Eieren er navnet som står i den første tekstkolonnen. De neste 3 tegnene gjelder gruppen filen tilhører. Gruppen er navnet som står i den andre tekstkolonnen. De siste 3 tegnene er "resten"; alle andre enn eieren og gruppen.

# Nyttige ressurser

- `man chmod`