# Oppgave 1

Første oppgave er en introduksjon til GraphQL skjema. Denne oppgaven så er meningen å bli kjent med GraphQL skjema språket og hvordan vi kan modellere et API med GraphQL. 

## Start

Åpne en ny fil som du kalles `schema.graphqls`. Denne filen skal vi skrive graphql skjema i og det kan dermed være lurt å installere syntax highlighting eller annen hjelp til din favoritt editor. Bruker du VS-code kan du installere plugins som er anbefalt for dette repoet. 

Vi skal nå modellere et kjent domene for dere, nemlig Online. I denne oppgaven er det bare en liten del av Online vi skal modellere. Under blir det en enkel beskrivelse av hvordan modellen kan være, men ikke vær redd for å endre på dette.

* Online har et navn, epost-adresse, telefonnummer, org-nummer og adresse
* Online har flere medlemmer
* Et medlem har et navn, ID, epost-adresse og dato for når de startet i online
* Online har mange kommiteer
* En komité har et navn, epost-adresse og beskrivelse (Fyll gjerne inn mer)
* Hver komite har et eller flere medlemmer

For å lære med om GraphQL skjema, bruk gjerne https://graphql.org/learn/schema/#type-system

