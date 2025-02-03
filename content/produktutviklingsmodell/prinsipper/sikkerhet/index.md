---
title: Sikkerhet
ingress: Digdirs prinsipper for sikkerhet i utvikling sikrer trygg og stabilt produktutvikling gjennom robuste rammeverk og god praksis.

navigation_link:
  subtitle: Sikkerhet er avgjørende for trygg og pålitelig produktutvikling.

banner:
  image:
    src: /illustrations/illustration-03.png
    alt: Illustrasjon av en person som sitter og leser en bok
---

## Prinsipper for sikkerhet i utvikling

### Helhetlig tilnærming
Digdir skal sørge for at sikkerhet og personvern ivaretas i hele livsløpet til løsningene, gjennom å benytte anerkjente utviklingsprosesser og systemutvikling i tråd med god sikkerhetspraksis. Krav til fremdrift skal ikke gå på bekostning av sikkerhetsmål og god sikkerhetsstyring.

---

### Etablerte rammeverk og standarder benyttes
Så langt det er hensiktsmessig legges etablerte rammeverk og standarder til grunn for arbeidet med utvikling i Digdir.

---

### Minste privilegiums prinsipp
Brukere skal kun gis tilgang og adgang til de IT-systemer/moduler/prosesser og den informasjon vedkommende har behov for i sitt arbeid og innenfor det minste tidsrommet som trengs. Dette reduserer risikoen for uautorisert tilgang til sensitive data og systemer og brukere kan bare hente ut informasjon som de trenger.

---

### Sikkerhet i dybden
Sikkerhetstiltak skal legges i flere lag for å beskytte informasjon. Tiltakene skal være minst mulig avhengige av hverandre, slik at én enkelt feil eller hendelse ikke svekker hele sikkerheten. Sikkerhetstiltak skal fungere i sammenheng uten å motvirke hverandre eller skape unødvendig duplisering.

---

### Null-tillit
Ingen bruker, enhet eller nettverk skal gis tilgang uten autentisering og autorisering, selv innenfor Digdirs nettverk. Aktiviteter skal overvåkes og revideres kontinuerlig for å sikre at tilgang kun gis til de som trenger det.

---

### Åpen sikkerhet
Kvaliteten på sikkerhetskontrollen skal ikke være avhengig av hemmelighold. Utviklere må forstå sikkerhetskonsekvensene av koden og gjennomføre tiltak for å gjøre den sikker. Dette inkluderer bruk av sikker utviklingspraksis, testing for sårbarheter, sikre utviklingsverktøy og samarbeid med sikkerhetseksperter.

---

### Dokumentasjon
Løsninger, plattformer og miljøer, samt utviklingen av disse, skal dokumenteres både teknisk og funksjonelt. Dokumentasjonen skal oppdateres gjennom hele livsløpet.

---

## DevSecOps – fortløpende sikkerhetsaktiviteter

Produktteamene er ansvarlige for etterlevelse av Digdirs retningslinjer og policies, med sikkerhet som en naturlig integrert del av både utvikling og drift. Team sikkerhet støtter dette ved å tilby verktøy og rutiner som utdyper retningslinjene.

### Sikkerhetsaktiviteter i ulike faser

| **Aktivitet**              | **Fase**          | **Beskrivelse**                                                                 |
|-----------------------------|-------------------|---------------------------------------------------------------------------------|
| **Risikovurdering**         | Plan              | Personvern- og sikkerhetsrisiko vurderes gjennom hele livsløpet til løsningen. Risikovurdering gjøres ved planlegging av endringer/ny funksjonalitet – typisk i forbindelse med oppstart at et nytt veikartelement/epic.|
| **Sikkerhetskrav**          | Plan-Test         | Enhetlige sikkerhetskrav gir grunnlag for et helhetlig, konsekvent og dokumenterbart kvalitetsnivå for løsningene som utvikles. Sikkerhetskrav identifiseres i planfasen og verifiseres i bygg- eller testfasen.              |
| **Sikkerhetstest**          | Build-Test        |All kode er gjenstand for statisk og dynamisk sikkerhetstest, som følges opp av produktteamene. I tillegg gjennomføres manuelle penetrasjonstester regelmessig. |
| **Håndtering av hendelser** | Operate-Monitor   | Dersom en sikkerhetshendelse oppstår må riktige ressurser fra produktteamene involveres slik at hendelsen kan håndteres og normaltilstand gjenopprettes så snart som mulig.|

---

Sikkerhetsprinsippene i Digdir sikrer en robust tilnærming til utvikling, der sikkerhet er integrert i alle aspekter av prosessen.
