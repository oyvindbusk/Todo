Busks Todo App
Busks Todo er en minimalistisk og responsiv webapplikasjon for å holde styr på daglige oppgaver, notater og andre gjøremål. Appen er bygget med fokus på enkelhet og en sanntidsopplevelse, slik at du kan synkronisere oppgavene dine på tvers av enheter.

Nøkkelfunksjoner
Fleksible visninger: Organiser oppgavene dine effektivt med fem forskjellige visninger:

Månedlig: En kalenderoversikt for å se oppgaver knyttet til spesifikke dager.

Daglig: Detaljert liste over oppgaver for den valgte dagen.

Alle oppgaver: En samlet oversikt over alle oppgaver i en sorterbar tabell, uavhengig av dato.

Andre oppgaver: En egen visning for oppgaver som ikke er knyttet til noen dato.

Notater: Et eget område for å skrive ned tanker og ideer.

Sanntidssynkronisering: Alle data lagres i en sanntidsdatabase (Firebase Firestore) for å sikre at oppgavene dine alltid er oppdaterte, uansett hvilken enhet du bruker.

Enkel interaksjon: Legg til, fullfør, rediger og slett oppgaver og notater med et intuitivt brukergrensesnitt.

Teknologi
HTML: Strukturen til applikasjonen.

Tailwind CSS: For rask og responsiv styling.

JavaScript: Appens logikk og interaksjoner.

Firebase Firestore: Som en sanntidsdatabase for å lagre og synkronisere oppgaver.

Firebase Authentication: For å håndtere brukerautentisering og sikre at dataene dine er private.

Hvordan kjøre appen
For å kjøre appen lokalt, kan du ganske enkelt åpne index.html-filen i nettleseren din.

For å sette opp din egen versjon og koble til din egen Firebase-database, må du:

Opprette et nytt prosjekt i Firebase Console.

Aktivere Firestore Database og Authentication.

I Authentication-menyen, gå til Sign-in method og aktiver Google som påloggingsleverandør.

Legg til autoriserte domener: I Firebase-konsollen din, under Authentication -> Settings -> Authorized domains, må du legge til domenet der du kjører applikasjonen din. Hvis du kjører den lokalt, kan dette være localhost. For produksjon, må du legge til domenet ditt (f.eks. dittdomene.com).

Kopiere Firebase-konfigurasjonsdataene dine og lime dem inn i koden.

Deretter kan du laste opp filen til en webserver eller bruke en tjeneste som GitHub Pages for å publisere den.