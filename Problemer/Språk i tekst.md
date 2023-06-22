---
alias:
tags: bilder
gruppe: "[[Navigasjon]], [[Tekst]]"
wcag: "[[3.1.2]]"

opprettet: 29-05-2023
sist oppdatert: 
---

**Ref wcag 3.1.2 - språkkode på fremmedspråk.**

I dag er det ofte bare "norsk" i språkkoden, men egentlig så skal alle fremmedspråk markeres med språkkoder. Målet i førsteomgang er å legge inn lang-koder på språk som kommer fra admin - uten å gjøre alt for mange endringer i admin eller gå i dybden i generell teksten

Vi bør unngå å skrive bokmål og fremmedspråk vedsiden av hverandre. Dette skaper en del trøbbel opp mot dette punktet - kan fikses, men det krever litt utvikling og redaksjonell jobb. ref. parent-issue her.

Det vil være lurt å skille mellom språk i plattform og innholdet i læringsressursene. I læringsressurser for fremmedspråk vil det være nødvendig å kunne merke enkeltord i innholdet. 
> Dersom hjelpemidler skal fungere korrekt, må disse ordene tagges med rett språk. Alternativet er at den spanske setningen blir lest opp med norsk stemme og aksent. 
> 	- En tekst kan ha instruksjoner på norsk, men lesetekst eller dialog på andre språk. 
> 	- En gloseliste vil ha ord eller setninger på flere språk. 
> 	- I en tekst kan det være enkeltord eller setninger som må tagges med språkkoden til fremmedspråket. 

## Eksempel: 
Siden er skrevet på hovedspråk bokmål, dette er angitt i <head>
Instruksen er skrevet på bokmål:
`<p>Tenk deg at du er utviklingselev i Spania. Du og vertsbroren din Pedro jobber sammen om et prosjektarbeid der dere skal sammenlikne Norge og Spania, både når det gjelder skolesystemet og andre sider av kulturen. Sett sammen en dialog ved å skrive dine svar til hver av Pedros replikker.</p>`
Selve dialogen er skrevet og merket som spansk med <span lang="es">. 
`<p><span lang="es"><strong>Pedro</strong>: Yo creo que no hay muchas diferencias entre Noruega y España, en general. </span></p>`

Ved bruk av talesyntese kan da teksten bli lest opp på rett språk med ulike stemmer, slik at den spanske stemmen leser den spanske teksten, mens resten blir lest opp på norsk. 

![[gh 2023-06-22 at 10.23.42.png]]