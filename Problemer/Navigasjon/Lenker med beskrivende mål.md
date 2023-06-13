---
alias: Lenker, lenke, 
tags:
gruppe: "[[Tekst]], [[Navigasjon]]"
wcag: 1.1.1

opprettet: 09-06-2023
sist oppdatert: 
---

## Problem:
En skjermlesebruker kan ha problemer med å skille mellom forskjellig type lenker. For seende er det enkelt å se om man er inn i en navigasjon, meny eller inne i en læringsartikkel og kan derfor skille mellom hva de forskjellige nivåene og inngangene her.

## Prefix og suffix 
Et forslag for å forbedre brukeropplevelsen vil være å legge på prefixes og suffixes for å forklare lenkes formål enda mer.  

## Struktur
### > Eksempel på navigasjonsnivåer: 
> Fag/Læreverk -> Trinn -> Hovedkategori -> Underkategori -> (Artikkel/innhold)
> 
###  > Eksempel på prefix/suffix
> Ord og uttrykk om læringsressurser fra [NS4180](https://github.com/Utdanningsdirektoratet/ns4180/blob/master/vokabularer.md#15-learning-resource-type-learningresourcetype)
> 	- kurs
> 	- demonstrasjon
> 	- simulering
> 	- bilde
> 	- oppsummering
> 	- læringsaktivitet
> 	- leksjon
> 	- primærkilde
> 	- vurderingsrubrikk
> 	- egenevalutering
> 	- tekst
> 	- tekstbok
> 	- 
Her er det mange egenskaper som kan brukes: 
### > 2.1. Accessibility Feature [accessibilityFeature](https://github.com/Utdanningsdirektoratet/ns4180/blob/master/typer-og-egenskaper.md#tilgjengelighetsspesifikke-egenskaper)
f.eks alternativeText, braille, ChemML, describedMath, highContrastDisplay, largePrint, latex, MathML, signLanguage, tactileGraphic, tactileObject

> i tillegg kan en merke læringsressurser med #### 2.3. Accessibility API ([accessibilityAPI](https://github.com/Utdanningsdirektoratet/ns4180/blob/master/typer-og-egenskaper.md#tilgjengelighetsspesifikke-egenskaper))
> Indikerer at ressursen er kompatibel med den angitte tilgjengelighets-APIen / _Indicates that the resource is compatible with the referenced accessibility API_.


### Alt-text 
Her kan det argumenteres at det i tillegg skal være alt-text på bildene. Men ettersom bildet er en del av lenken, er det lenkens formål som skal beskrives – noe som blir tydeligere ved å legge inn suffixes og prefixes på enkelte lenker.

I eksempelet under vises det en lenke til et av Elevkanalens fag, Nautrfag 3-4.  
Her er det lagt på "Fag" som suffix for å understreke at lenken er et fag.
![[GetImage (2).png]]

Et annet eksempel er inne i en læringsartikkel og det lenkes til en oppgave, quiz, bok eller noe slikt. 
Under viser man hvordan det som ellers hadde vært "lenke Tekst" nå blir mer forklarende med "Lesetekst Hvalrossen Freya, versjon Tekst" hvor bruker får med type, navn og versjon i opplesningen![[GetImage (3).png]]
Her vises hvordan det kan brukes for Quizer. Det som ellers ville være "Lenke Episodens ord"  blir nå "Quiz Episodens ord"
![[GetImage (4).png]]
