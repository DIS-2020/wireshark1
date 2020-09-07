# wireshark1

# Wireshark Lab Exercises

I dag skal vi arbejde med Wireshark, der er en gratis open-source packet-analyzer. Det vil sige vi kan bruge den til at 'sniffe' pakker i vores netværk, for at se ting som deres kilde, destination og indhold. Dette er den første Wireshark øvelse for at blive mere bekendt med programmet, men også en måde hvorpå I kan få 'hands-on' på internettet og se informationen omkring de pakker i afsender og modtager. 

Wireshark startes ved at trykke på den blå finne i øverste højre hjørne.

### Opgave 1
Start Wireshark og åbn my.cbs.dk. Sørg for at stoppe den relativt hurtigt, da I nok vil blive bombarderet med pakker.
- Find nu 3 forskellige protocols (kolonne 5) og undersøg hvad deres formål er.
- Højst sandsynligt har I fået nogle linjer der er markeret med rødt/sort. Hvad betyder dette?

### Opgave 2
Kør nu Wireshark igen og gå ind på http://gaia.cs.umass.edu/ (bogens forfatteres hjemmeside) og stop den. Hvis I nu skriver 'http' i filter-baren øverst, burde alt undtagen http-request filtreres fra.
- Hvad er tiden mellem jeres request og sidens response?
- Hvad er http://gaia.cs.umass.edu/ IP-adresse og hvad er jeres egen?

### Opgave 3
Kør Wireshark og skriv "nslookup www.rediff.com" (en asiatisk hjemmeside). Hvad er dennes IP-adresse?
Køre derefter Wireshark og skriv "nslookup -type=NS uoi.gr" (græsk universitets hjemmeside). Herfra kan i se de tilhørende DNS-servere, der omdirigerer linket for jer. Hvad er disse?

### Opgave 4
Med den data du har samlet fra sidste opgave, kig nu igennem efter en pakke der bruger DNS-protokollen.
- Undersøg indholdet og find ud hvilken transport-protocol der bliver brugt (TCP eller UDP?).
- Hvad er destinationsporten og hvad er kilde-porten?
- Undersøg DNS-query. Hvilken type query er det? Hvilke svar er der?
- Undersøg DNS-response's svar. Hvilke svar er der? Hvad betyder disse svar?





