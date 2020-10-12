# su og sudo

Noen ganger trenger vi utvidete rettigheter når vi skal gjøre noe. Dette kan være f.eks:

- Trenger å avslutte en prosess som er ute av kontroll (og som vi ikke eier selv)
- Trenger å installere et program som skal være tilgjengelig for alle på systemet

Den brukeren du bruker til vanlig har ikke tilgang til store deler av filsystemet, særlig de delene som er felles for flere brukere. Når vi skal installere et program, legges den ofte på et sånt sted. Da kan vi bruke `sudo`.

    > sudo apt install python3.8

Da blir man spurt om passordet slik at kommandoen kjøres med utvidete rettigheter.

En annen kommando er `su`. Med `su` får vi en ny sesjon der vi kan kjøre flere kommandoer som en annen bruker. Merk at vi trenger passordet til "root" brukeren for å logge inn som "root", og at "root" brukeren er ofte låst. Det beste er å holde seg til `sudo`.

# Nyttige ressurser

- [Beginners guide to sudo](https://www.howtoforge.com/tutorial/sudo-beginners-guide/ "sudo")
- [Difference between sudo and su](https://www.howtoforge.com/tutorial/sudo-vs-su/ "sudo vs su")
