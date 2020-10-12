# Linux Kurs

Disse filene er tenkt brukt av de som deltar på mitt introduksjonkurs om Linux. Presentasjonen fra kurset kan sees [her](Dokumenter/Linux_for_Nybegynnere.pdf).

For å få filene vi skal bruke i den praktiske delen av kurset kjører vi følgende kommandoer i bash:

    cd
    git clone https://github.com/kreativitetNO/linuxkurs
    cd linuxkurs

Før du begynner å jobbe med filene:

    git checkout -b MyBranch

For å nullstille tilbake til originalfilene:

    git checkout main
    git reset --hard
    git clean -fd .
    git branch -d MyBranch

# Dokumenter

Dokumentene er skrevet i rekkefølgen de gås gjennom på i kurset. Derfor betyr ord som "tidligere" og "senere" at du må se henholdsvis oppover eller nedover i listen.

- [Alternative måter å kjøre Linux på](Dokumenter/KjoereLinux.MD)
- [Shell](Dokumenter/Shell.MD)
- [Navigering](Dokumenter/Navigering.MD)
- [Få hjelp](Dokumenter/Hjelp.MD)
- [Lage og se på filer og kataloger](Dokumenter/LageFiler.MD)
- [Filhierarki](Dokumenter/FilHierarki.MD)
- [Finne filer eller innhold](Dokumenter/FinneTing.MD)
- [Shell - Del 2](Dokumenter/Shell2.MD)
- [Rettigheter](Dokumenter/Rettigheter.MD)
- [Redigeringsprogrammer](Dokumenter/Editors.MD)
- [Jobb-/prosesshåndtering](Dokumenter/Processes.MD)
- [Su og Sudo](Dokumenter/Sudo.MD)
- [Nyttig informasjon](Dokumenter/NyttigInfo.MD)
- [Avanserte temaer](Dokumenter/Avansert.MD)
