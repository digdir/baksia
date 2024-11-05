---
title: Arkitektur
ingress: Arkitekturprinsipper er grunnleggende retningslinjer som hjelper oss å bygge robuste, skalerbare og bærekraftige løsninger.

navigation_link:
  subtitle: Standardiserer arbeid, reduserer kompleksitet og sikrer kvalitet.

banner:
  image:
    src: /illustrations/illustration-11.png
    alt: Illustrasjon av to personer som gjør et tungt arkitekturløft
---

## Overordnede arkitekturprinsipper

De overordnede arkitekturprinsippene er en støtte til arbeid med virksomhetsarkitektur
og skal bidra til økt samhandlingsevne på tvers av virksomheter og sektorer.

Alle fellesløsningene som Digdir utvikler og forvalter skal naturlig nok følge disse prinsippene.

1. [Ta utgangspunkt i brukernes behov](https://www.digdir.no/digital-samhandling/prinsipp-1-ta-utgangspunkt-i-brukernes-behov/1055)
2. [Ta arkitekturbeslutninger på rett nivå](https://www.digdir.no/digital-samhandling/prinsipp-2-ta-arkitekturbeslutninger-pa-rett-niva/1056)
3. [Bidra til digitaliseringsvennlige regelverk](https://www.digdir.no/digital-samhandling/prinsipp-3-bidra-til-digitaliseringsvennlige-regelverk/1057)
4. [Del og gjenbruk data](https://www.digdir.no/digital-samhandling/prinsipp-4-del-og-gjenbruk-data/1061)
5. [Del og gjenbruk løsninger](https://www.digdir.no/digital-samhandling/prinsipp-5-del-og-gjenbruk-losninger/1062)
6. [Lag digitale løsninger som støtter samhandling](https://www.digdir.no/digital-samhandling/prinsipp-6-lag-digitale-losninger-som-stotter-samhandling/1063)
7. [Sørg for tillit til oppgaveløsningen](https://www.digdir.no/digital-samhandling/prinsipp-7-sorg-tillit-til-oppgavelosningen/1064)


## Altinn 3 arkitekturprinsipper

[Moderniseringen av Altinn](https://samarbeid.digdir.no/altinn/modernisering-av-altinn/2331) følger noen sentrale og enda mer spissede arkitekturprinsipper,
som gjelder for alle de nye [Altinn 3 produktene](https://samarbeid.digdir.no/altinn/produktene-i-altinn-3/2345).

1.  **Åpen kildekode**  
Det er ikke bærekraftig å bygge nasjonale fellesløsninger på bindinger til programvare som ikke kan endres eller videreutvikles. Altinn 3 baserer seg ikke på kommersiell hyllevare, men er egenutviklede produkter med gjenbruk av åpen kildekode. Det gjør at Digdir har fleksibilitet over retningen til produktutviklingen og kan oppfylle behov som oppstår. Siden Altinn 3 ikke benytter programvare som er begrenset av lisensiering åpner dette for åpen samskaping og gjenbruk på tvers.

2. **Åpen samskaping**  
Altinn 3 utvikles åpent og i tett samarbeid og samråd med tjenesteeiere og brukere. Dette gjelder også tjenesteutviklingsløsningen Altinn Studio, som benyttes for effektiv og selvbetjent utvikling av digitale tjenester, som også kan samskapes og gjenbrukes. Altinn 3 utvikles gjennom prioritering av brukerbehov og [direkte bidrag av kildekode fra ulike virksomheter](https://github.com/search?q=org%3AAltinn+label%3Aexternal-contribution-%E2%9D%A4%EF%B8%8F&type=pullrequests).
Altinn 3 er et distribuert samarbeid på tvers av organisasjoner og lokasjoner, og siden Altinn 3 er et [digitalt fellesgode](https://www.digitalpublicgoods.net/digital-public-goods) (DPG), så er ambisjonen at samarbeid og deling også kan krysse landegrenser og bidra til FNs bærekraftsmål.

3. **Skytjenester og fleksibel bruk**  
Altinn 3 kjører på fleksibel og selvbetjent infrastruktur i skyen som kan skaleres opp og ned avhengig av trafikk, og settes opp ved bruk av infrastruktur som kode (IaC). Skytjenester kan testes ut raskt, noe som muliggjør en helt annen endringstakt enn infrastrukturen i Altinn II. En annen viktig egenskap er at man kun betaler for det man faktisk bruker av kapasitet, og kostnader kan knyttes til hver enkelt tjeneste.

4. **Separate produkter med separat infrastruktur**  
For å kunne håndtere frittstående produkter på en god måte bygger Altinn 3 på mikrotjenestearkitektur og skytjenester. Mikrotjenestearkitektur gjør det enklere å lage og drifte frittstående produkter. Separate infrastrukturer gjør at eventuelle problemer isoleres, og hvert produkt kan skaleres opp uavhengig av andre produkter. 

5. **Separate finansieringsmodeller**  
Altinn 3 benytter skytjenester, og har en arkitektur som er laget med tanke på frittstående produkter og egen infrastruktur pr. tjenesteeier. Dette legger grunnlaget for ny finansieringsmodell som tar hensyn til tjenesteeiernes faktiske forbruk av ressurser.

6. **Fleksible driftspartnere**  
Drift og utvikling håndteres av tverrfaglige og smidige DevOps produktteam som har helhetsansvaret for sine produkter.
Dette gjør både utvikling og drift mer effektiv samt at dette sikrer internt eierskap til produktene.



## Altinn Studio arkitekturprinsipper

Et ytterligere detaljeringsnivå (pt. kun på engelsk), som i stor grad også gjelder for alle produktene i Altinn 3.

https://docs.altinn.studio/principles
