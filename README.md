Grensesnittdesign
=================


Hei Erik! 

Du kan teste appen via linken http://dotnet.nith.no/groola12/index.html

Jeg føler at jeg må kommentere noen bugs jeg ikke har klart å rette opp:

Jeg er ikke helt sikker på hvordan du tester applikasjonene, men jeg har brukt iOS Simulatoren til Xcode og linken over.

Om du legger til index.html på hjemskjerm i simulator funger ikke linken til ny bruker-siden, men linken fungerer i safari.

Kartsiden vil ikke laste inn første gang man trykker på logo. Man må dermed reloade siden for at siden skal vises.
For å gjøre appen mer dynamisk la jeg inn en sidemeny som kan swipes inn, men det har jeg kun implementer på kartsiden. Årsaken til det er at swipefunksjonen styres av en ekstern css-fil som har plaget vettet av meg ved å overstyre all csskoden jeg skriver.

Logg ut link i sidemeny linker til index.html, men også her må siden reloades for at den skal vises korrekt.

Lagringsfunksjon har jeg lagt til på ny bruker siden, men den brukes egentlig ikke til noe vettig i appen.


Ola Lindsetmo
