
# SNK 607
Sommeren 2021 gikk de største forlagene sammen for å løse problemer for universell utforming i legemiddelbransjen

# Hvorfor akkurat oss?
Digitale læremidler skiller seg en god del fra vanlige nettsider. Ofte er nettsidene store, rettet for flere målgrupper, flerspråklighet og alderstrinn med mye komplekst innhold og interaksjonstyper. Innholdet som blir produsert er som oftest ulikt avhengig av fag, innholdstype og alderstrinn.
Det er også av denne grunnen WCAG-reglene slår uheldig ut ettersom WCAG er laget som en guideline for nettsider generelt, uten å tenke på målgruppe eller avanserte interaksjonstyper.

### Hvorfor gjør vi dette?
Vårt ønske er å lage gode brukeropplevelser for alle - men i enkelte tilfeller ser vi at WCAG-reglene gir ekstra utfordringer. Ikke fordi at innholdet ikke er tilgjengelig, men at reglene er laget til en helt annen kontekst, noe som gjør at innholdet mister sin pedagogiske verdi.

### Komplekst innhold
Læringsplattformer er som oftest store, kompliserte plattformer med mye variert innhold. Innholdet varierer fra tekst, video og bilde, men inkluderer også interaktive elementer som spill, interaksjoner, komplekse grafer med mer. Mange elever lærer visuelt og krever visuelle simuleringer, eller andre interaksjoner. Slike "custom elementer" blir gjerne kodet ved å manipulere HTML, noe som i enkelte tilfeller kan slå negativt ut på selve semantikken i koden, men ikke nødvendigvis noe en bruker vil oppleve. Aldersforskjell og stor variasjon av målgruppe er også et grunnleggende problem. Alt innholdet dupliseres gjerne minst en gang, til bokmål/nynorsk - men gjerne også flere ganger dersom læremiddelet er oversatt til flere språk. Ettersom innhold kan eksistere i flere versjoner og varianter, blir mengden innhold deretter multiplisert som øker kompleksiteten.

Les mer under [[komplekst innhold]] for videre lesing

## [[WCAG]]
Alle problemer er lenket opp mot WCAG-reglene. Gå til WCAG-siden for å se problemene listet ut ifra wcag


### Teams
Hver uke har vi vært flere grupper....
- [[Bilder]]
- [[Navigasjon]]
- [[Spill og interaksjon]]
- [[Tekst]]


# Totaloversikt for problemer
```dataview 
table wcag, gruppe
FROM ""
Where gruppe != null
sort wcag desc 
```