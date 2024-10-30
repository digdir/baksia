---
title: Operations
ingress: Ops (Operasjon)-delen av DevOps refererer til praksis, prosesser og teknologier som er involvert i å håndtere og vedlikeholde IT-infrastruktur, systemer og applikasjoner i produksjon. Den fokuserer på å sikre at programvare kjører jevnt, pålitelig og sikkert i et aktivt miljø.

navigation_link:
  subtitle: Vi sikrer stabil drift med overvåking, vedlikehold, feilretting og sikkerhet.

banner:
  image:
    src: /illustrations/illustration-03.png
    alt: Illustrasjon av en person som sitter og leser en bok
---

Operations (OPS) i DevOps
Definisjon: Operations, eller drift, refererer til de aktivitetene og prosessene som sikrer at programvareapplikasjoner kjører stabilt og effektivt i produksjonsmiljøet. Dette inkluderer overvåking, vedlikehold, oppdateringer og feilhåndtering. I dag er OPS fordelt mellom produkt og plattform team. Hovedoppgavene som de ulike teamene skal ivareta er: 


1. Overvåking:

Teamene skal sikre at vi ivaretar kontinuerlig overvåking av systemytelse, tilgjengelighet og sikkerhet.
Noen av verktøyene vi i dag benytter er Applicaton Insight og Grafana. Hva og hvordan vi i dag overvåker ligger beskrevet på https://pedia.altinn.cloud/altinn-3/ops/monitoring/
Alle team har ansvar med å konfiguere opp varsler når noe er i ferd med å skje på platform og løsninger, samt og sikre at vi kontinuerlig vedlikeholder og forbedrer varslingen. 

2. Vedlikehold:

Teamene skal ivareta regelmessig vedlikehold av systemer og platform for å sikre optimal drift.
Alle Team skal ha etablerte rutiner for å utføre oppdateringer og patching for å fikse feil og forbedre sikkerheten.

3. Feilhåndtering:

Teamene skal ha etablerte dagvakter som følger med på alarmer og igangsetter evt feilrettinger når dette oppstår, og involverer evt andre team som må bistå i feilrettingen. 
BOD Digir har etablerte rutiner for hvordan dette skla ivaretas, og hendelesesansvarlig skal alltid involveres. 
Teamene må implementere tiltak for å minimere nedetid og sikre systempålitelighet. Etter større hendelser skal Post Mortem iverksettes, for å evaluere, lære og komme med evt korrigerende tiltak videre. 
Altinn 3 har 24/7 vakt - alle team har ansvar med å sikre at kjente feil og hvordan de skal ivaretas blir dokumentert på dette området https://pedia.altinn.cloud/altinn-3/ops/incidents/

4. Skalering:

Platform og produktteamene i BOD sal sikre at vi til enhver tid har kontroll på ytelsen på platform og clustre ved overvåking og alarmer, og sikre at vi kontinuerlig skalerer for å håndtere økt trafikk eller belastning.
Teamene må tilstrebe seg å benytte skalerbare løsninger.
5. Sikkerhet:

Implementere sikkerhetstiltak for å beskytte applikasjoner og data.
Regelmessige sikkerhetsvurderinger og oppdateringer.

6. Automatisering:

Alle Teamene skal kontinuerlig jobbe med å automatisere repetitive oppgaver for å redusere feil og forbedre effektiviteten.
Det brukes ulike verktøy i dag, Eks Renovate

7. Backup og gjenoppretting:

Platform Teamet i BOD har etablert løsninger som skal sigre regelmessige sikkerhetskopier av data og systemer, samt hvordan restore skal kunne håndteres. 
Vi skal samtidig ha etablerte planer for kontinuerlig teste våre løsninger at de fungerer til enhver tid, ikke minst teste hvor lang tid restore av ulike data vil ta. 

