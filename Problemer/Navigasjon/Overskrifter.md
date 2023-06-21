---
alias:
tags:
gruppe: "[[Tekst]], [[Navigasjon]]"
wcag: "[[1.3.1]], [[2.4.1]], [[2.4.6]], [[2.4.10]]"

opprettet: 21-06-2023
sist oppdatert: 
---

# Prinsipp
Overskrifter kodes ved hjelp av overskriftelementene `<h1>` til `<h6>`, og disse deler opp teksten tilsvarende i kapitler og delkapitler i ulike nivåer. Formålet er å lage struktur i tekst og informasjon. Overskriftsnivåer brukes for å strukturere teksten, og er særlig aktuelt i redaksjonelt innhold. Rekkefølgen på nivåene skal være korrekt.

### Kort fortalt:
- Sørg for at ledetekster og overskrifter er beskrivende.
- Unngå tomme headinger
- Ikke bryt [[Heading hierarkiet]]


# Om overskrifter
Overskrifter er en viktig del av den semantiske strukturen i digitale læremidler. Det er et godt eksempel på en navigasjonsfunksjon som alle har nytte av, både for å finne fram, men også for lesbarhet og forståelse av sammenheng i innholdet. For skjermleserbrukere er navigering på overskrifter en essensiell måte å bevege seg rundt på og som gir rask tilgang til innholdet. God overskriftsstruktur skaper en forståelig, tilgjengelig og brukervennlig opplevelse for alle brukere.

En overskrift må være tagget som en overskrift for at det skal være en overskrift, f.eks.
```
<h1>Overskrift 1</h1>
```
En tekst markert med stor font og fet skrift vil ikke være en overskrift hvis den mangler h-tag. Unngå formatering i overskrifter, eksempelvis kursiv eller lenker.

Sørg for at overskriftene har logisk semantisk struktur og rekkefølge. Overskrifter på nivå 2 skal høre inn under forrige overskrift på nivå 1. Overskrifter på nivå 3 hører inn under forrige overskrift på nivå 2 osv.

> [!tip] Ikke hopp over nivå. 
> Dersom man hopper fra `<h1>` til `<h3>` er det et brudd på [[Heading hierarkiet]] 

Tenk gjerne trestruktur når dere plasserer overskriftene i nivåer, eller for å sjekke om strukturen gir mening. Lenke: [Test innhold med tretesting - Aksel (nav.no)](https://aksel.nav.no/god-praksis/artikler/test-innholdet-med-tretesting?)

Unngå tomme overskrifter, f.eks. for å skape rom. Bruk heller CSS til dette. Skjermlesere har en funksjon der brukeren kan samle overskriftene på en side for lettere å få oversikt og kunne navigere direkte til en overskrift. Da blir det forvirrende hvis det er rot i strukturen, f.eks. hopp i nivåene eller tomme overskrifter.

> [!tip] Unngå tomme headinger
> **Redaktører**: Ikke bruk headinger for å få ønsket spacing mellom linjene.
> **Utviklere**: Husk å legg inn sjekker for å se på headings har en value, slik at man ikke rendrer ut tomme headings
>

Alle nettsider må ikke ha en h1, men det er god praksis. En overskrift på nivå 1 brukes ofte for å gå tilbake til start av skjermleserbrukere. Det tillates samtidig flere h1 per side og det kan også være naturlig hvis siden inneholder flere kaptittel-overskrifter f.eks.