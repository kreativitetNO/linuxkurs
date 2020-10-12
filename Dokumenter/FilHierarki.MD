# Noen av de viktigste mappene i filhierarkiet

https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard
https://www.thegeekdiary.com/proccpuinfo-file-explained/

| Katalog | Beskrivelse |
--
| \ | Rotkatalogen der resten stammer fra |
--
\ - Rotkatalogen der resten stammer fra

\bin - Nødvendige kommandoer

\boot - Bootloader og kernel

\dev - Enhetsdevicer
\etc - Konfigurasjonsfiler
\home - Hjemmeområdene til brukerne


Noen ting vi kan bruke de forskjellige kataloger til:

## Se på kernel og bootloader konfigurasjonen

    ll -h /boot

## Se på konfigurasjonsinformasjon

    cat /etc/passwd

## Generere tilfeldige tall

    hexdump -C -n 8 /dev/urandom
