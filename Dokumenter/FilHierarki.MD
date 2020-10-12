# Filhierarkiet

<table>
<thead>
<th>Katalog</th>
<th>Beskrivelse</th>
</thead>
<tbody>
<tr>
<td>/
<td>Rotkatalog der resten stammer fra
<tr>
<td>/bin
<td>Nødvendige kommandoer
<tr>
<td>/boot
<td>Bootloader og kernel
<tr>
<td>/dev
<td>Enhetsfiler
<tr>
<td>/etc
<td>Konfigurasjonsfiler for hele systemet
<tr>
<td>/home
<td>Hjemmeområdet til brukerne
<tr>
<td>/lib
<td>Delte biblioteker og kernel moduler
<tr>
<td>/media
<td>Monteringspunkt for USB ol
<tr>
<td>/mnt
<td>Monteringspunkt for midlertidige filsystemer
<tr>
<td>/opt
<td>Tilleggs programvare
<tr>
<td>/sbin
<td>System programmer
<tr>
<td>/srv
<td>Tjenestedata
<tr>
<td>/tmp
<td>Midlertidige filer
<tr>
<td>/usr
<td>Brukerverktøy og applikasjoner
<tr>
<td>/var
<td>Variabel filer
<tr>
<td>/root
<td>Hjemmeområdet til root
<tr>
<td>/proc
<td>Virtuell filsystem med kernel og prosessdata
</tbody>
</table>

Noen ting vi kan bruke de forskjellige kataloger til:

## Se på kernel og bootloader konfigurasjonen

    > ll -h /boot

## Se på informasjon om CPU og minne

    > cat /proc/cpuinfo

## Se på konfigurasjonsinformasjon

    > cat /etc/passwd

## Generere tilfeldige tall

    > hexdump -C -n 8 /dev/urandom

# Nyttige Ressurser
- [Standard filhierarki i Linux](https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard "Filhierarki")
- [Mer om proc katalogen](https://www.thegeekdiary.com/proccpuinfo-file-explained/ "Proc")
