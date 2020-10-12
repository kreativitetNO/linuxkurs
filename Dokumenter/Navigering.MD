# Navigere rundt filsystemet

Det er en fordel å øve på disse kommandoene etter å ha klonet repo-en som beskrevet i [Readme.MD](../Readme.MD).

Kommandoer som blir gått gjennom i denne filen:

    ls
    pwd
    cd

Se innholdet i en katalog:

    > ls

ls har mange parametre. Dette er tillegg vi kan skrive etter selve kommandoen.

Slik får vi fram flere detaljer om filene/katalogene:

    > ls -l

Og denne varianten viser også skjulte filer:

    > ls -a

For å se hvilken katalog vi er i kan vi skrive:

    > pwd

(Står for _Print working directory_)

For å skifte katalog bruker vi `cd`:

    > cd Dokumenter

For å sjekke at vi har skiftet kan vi bruke `pwd` igjen.

For å skifte til katalogen over bruker vi:

    > cd ..

`..` betyr katalogen over den vi står i. `.` betyr dem samme katalogen vi står i. Dette får vi bruk for senere.

Vi kan også skifte direkte til en underkatalog av en underkatalog med:

    > cd Dokumenter/images

Tegnet `/` brukes til å separere elementer av en path.

Hittil har vi bare brukt relative path-er. Vi kan også bruke absolutte path-er. Det betyr at vi må oppgi alle kataloger fra og med rotkatalogen:

    > cd /home/[brukernavn]/Dokumenter

Hvis vi bare skriver `cd` skifter vi rett til hjemmekatalogen vår. Alternativt kan vi skrive `cd ~`. Disse kan kombineres slik:

    > cd ~/Dokumenter/images
