# rombooking
Databasemodell for booking av møterom

1.time: Kladd på papir. Databasemodell, oppsett for reservering av møterom og
        spørring for å sjekke hvilke møterom en gitt person har reservert.

2.time: Starte på en databasemodell i StarUML og lage et oppsett for reservering
        av et møterom.

3.time: Fortsette på databasemodell. Lage et oppsett for å sjekke reservasjoner
        en gitt person har gjort.

4.time: Ekspore modeller av hittil arbeid og laste opp på github. Se an muligheten
        til å bruke trigger for å validere om et møterom er opptatt.
		
5.time: Valgt å lage en spørring for å validere om et møterom er opptatt. Denne gir
		mulighet for å vise hvem som har reservert rom i ønsket tidsrom og hvorfor.
		
6.time: Ferdiggjøre modeller for levering og legge til antagelser i readme.

Antagelser
Tar det for gitt at selve programmet vil beskytte databasen mot sql injeksjoner.
Tar det også for gitt at programmet sjekker om input er gyldig mtp dato og klokkeslett.
I spørringen for å søke på reservasjoner til en person bør programmet fange opp input fra
bruker og sjekke denne for deretter å bygge sql spørringen del for del. En enkel if-setning
kan fange opp * og unngå legge til siste delen av sql-spørringen (Where Person Like.....).

