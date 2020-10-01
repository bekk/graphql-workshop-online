# Oppgave 3

Oppgave 3 handler om bruk av trafikkdata APIet og har en del oppgaver som viser deg litt flere avanserte GraphQL spørringer. Dette er et åpent API fra Statens Vegvesen hvor det deles trafikkdata åpent.
 
Du finner APIet på https://www.vegvesen.no/trafikkdata/api/. Når du går til nettsiden for APIet med en GET-request så har vi GraphiQL som lar deg interaktivt utforske APIet rett i nettleseren.

Det kan også være greit å lese seg litt opp om domenet trafikkdata på https://www.vegvesen.no/trafikkdata/start/om-trafikkdata

## Deloppgave 1

Hent ut en liste over alle tellepunkter med navn, id og gps-koordinater. Et tellepunkt er et punkt i vegbanen hvor vi registrerer trafikk.

## Deloppgave 2

I denne oppgaven skal man hente ut trafikkmengder per time. Du kan velge et vilkårlig tellepunkt fra den siste deloppgaven. Forsøk å hent ut trafikk for et intervall på 3-4 timer.

## Deloppgave 3

Nå skal vi se på paginering i GrapQL, eller connections som det heter i GraphQL verden. For timetrafikk så kan man spørre etter vilkårlig store intervaller, men vi gir bare ut maks 100 timer.

I denne oppgaven skal man dermed øke tidsintervallet man vil hente timetrafikk for og benytte seg av en graphql connection for å bla seg framover til neste resultatsett.

Siden øvelsen gjøres i GraphiQL manuelt så kan det være greit å sette tidsintervall slik at man klarer seg med 2-3 forespørsler for å hente ut alle timene.

## Deloppgave 4

Lag en spørringe som spør etter gjennomsnittlig månedsdøgnstrafikk for 2018 og 2019 for samme TRP. Prøv å gjør dette i en spørring.

Hint: Man kan bruke fragments i GraphQL for å slippe å gjenta felter.
