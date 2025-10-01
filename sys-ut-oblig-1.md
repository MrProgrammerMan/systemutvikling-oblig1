# Oblig 1 - Systemutvikling
Jonas Hazeland Baugerud - jobau8311
Bjørnar Reime - bjrei3390
Jørgen Eide Anskau - joans6553

## Oppgave 1
### a
Fordeler med nytt system:
- Fleksibilitet: En løsning mer tilpasset til deres bruksområde
- Skreddersydd konfigurasjon garantert i én pakke???
- Mulighet for å skille seg sterkere ut i et fullt marked
- Unngå alt for generelle systemer, men heller gå for nye som optimaliserer for kinoens bruksområde

Fordeler med eksisterende system:
- Billig
- Umiddelbar levering
- Stabilitet: Kjent og løst problem, altså en pålitelig og testet løsning.
- Satsing/investering som kan slå feil.

### b
Vi hadde valgt et eksisterende system, ettersom så og si all funksjonaliteten bedriften har behov for allerede finnes og fungerer godt. Det er ikke verdt kostnaden å gjenoppfinne hjulet. Dette er basert på antakelsen at Virtuoso Kino uansett skal ha et nytt system. Dersom de istedenfor allerede har en løsning som de kun vil modifisere kan det være billigere og enklere å gjøre dette fremfor å lage nytt, men dette avhenger veldig av det eksisterende systemet. Her måtte vi undersøkt dette for å gi et godt svar.

## Oppgave 2
### a
Alle mennesker som på en eller annet måte er berørt av systemet eller utviklingen av det er en interressent.
Interressenter som skal benytte systemet er aktører.

### b
Tabell over noen interressenter for systemet til Virtuoso Kino:
| **Navn** | **Interesse** | **Eventuelt ansvarsområde** |
| --- | --- | --- |
| Utvikler | Ønsker å gjøre en god jobb og få betalt | Ansvarlig for at systemet oppfyller kravene og oppfører seg som forventet på et teknisk nivå. |
| Leder av Virtuoso kino | Ønsker at systemet skal fungere og ikke være i veien slik at selskapet kan tjene penger på produktet sitt | Ansvarlig for kinoen i sin helhet. |
| Kunde av virtuoso kino | Ønsker å kjøpe billetter til kino | Ikke ansvarlig i det store og det hele. Eventuelt ansvarlig i henhold til avtale ved kjøp. |
| Administrator i Virtuoso kino | Ønsker å skaffe statistikk og legge inn filmer som skal vises | Ansvarlig for å presentere informasjon om kinooens salg og annet. |
| Driftstekniker av systemet | Ønsker å kjøre systemet med minst mulig stans og behov for inngrep | Ansvarlig for at systemet fungerer driftsmessig. |
| Produkteier av systemet | Ønsker å representere kundens behov under utvikling av systemet | Ansvarlig for at kundens behov blir dekket av produktet. |
| Medlem i kinoklubben(Altså Virtuoso kino sin) | Ønsker å samle poeng for kinobiletter | Ikke ansvarlig i det store og det hele. Eventuelt ansvarlig i henhold til avtale ved kjøp. |
| Billettkontrollør | Ønsker å sjekke billetter | Ansvarlig for at folk ikke blir sluppet inn på kinoen uten gyldig billett. |
| Kioskarbeider | Ønsker å kunne selge biletter over disk | Ansvarlig for å selge billetter over disk. |
| Betalingsleverandør | Ønsker å tilby sin tjeneste for å tjene penger | Ansvarlig for en fungerende og pålitelig betalingstjeneste. |

### c
Av interressentene i tabellen i b kan vi si at alle ansatte i, og kunder av, Virtuoso Kino er aktører.
Disse interressentene skal benytte systemet i normal drift etter at utviklingen er ferdig. I teorien, dersom det aldri trengs oppdateringer, vil ikke de andre interressentene ha noe å gjøre med systemet etter at det er ferdigutviklet. Unntaket er betalingsleverandøren, men her er det Virtuoso Kino som benytter seg av deres tjeneste, ikke motsatt.

## OPPGAVE 3

### a)

**Plandrevne prosessmodeller** er en utviklingsmodell
hvor man følger en oppskrift med nøyaktig rekkefølge av oppgaver for å nå målet.
Fremgangsmetoden er her såkalt sekvensiell, altså at man gjør seg helt ferdig med en fase før man går til neste.

**smidige prosessmodeller** er da i motsetning en utviklingsmodell hvor man jobber i hyppige iterasjoner
og dermed enkelt kan endre retning for produktet underveis.
Fremgangsmetoden her er ofte SCRUM eller lignende, hvor man jobber over flere utviklingsfaser samtidig.

### b)

 <u> Hovedforskjellene: </u>

Rent praktisk er valget mellom kanban og scrum noe som vil ahvenge av teamstørrelse, oppgavestørrelse, kundens krav, hvor kjent oppgavestilen er for utviklerne og produktets form.

Overordnet har disse fremgangsmetodene potensiale til å fungere veldig likt, eller ulikt avhengig av hvordan man setter strukturen på KANBAN boardet eller velger å bygge opp en sprint.

KANBAN gir fleksibel og kontinuerlig flyt, lettere for utviklere å ha en mer fullstendig oversikt over prosjektets fremgang. Kan være vanskelig å få oversikt over utvalgte enkeltprosesser.
her skjer planleggingen løpende, som har som mål å redusere ledetid.

SCRUM har faste iterasjoner kalt sprints som øker effektivitet på enkeltprosesser, men kan føre til at man blir ferdig/uferdig på ulike tidspunkt som kan gi følgefeil for neste sprint.
her planlegger man for hver sprint, som reduserer usikkerhet og retning i prosjektet.


nedenfor har vi laget en punktliste som bedre fremhever enkelte forskjeller.


#### Kanban vs Scrum

#####  Forskjeller

| **Kategori**      | **Kanban** | **Scrum** |
|-------------------|------------|------------|
| **Struktur**      | Fleksibel, kontinuerlig flyt | Faste iterasjoner (*sprints*) på 2–4 uker |
| **Oppgaver**      | Hentes når det er kapasitet (*pull*) | Planlegges i starten av sprint (*commitment*) |
| **Roller**        | Ingen definerte roller | Product Owner, Scrum Master, Utviklingsteam |
| **Møter**         | Valgfritt (ofte stand-ups) | Sprint planning, Daily Scrum, Review, Retrospektiv |
| **Leveranse**     | Kontinuerlig | Ferdig inkrement ved slutten av sprint |
| **Endringer**     | Kan skje når som helst | Sprinten er låst for nye oppgaver |
| **WIP-grenser**   | Ja (f.eks. maks 3 i progress) | Ikke eksplisitt, men sprinten setter en ramme |
| **Fokus**         | Flyt og jevn produksjon | Tydelige mål per sprint |

### c)

Kravspesifikasjon kan alltid endre seg i løpet av prosjektet. Dette er den vanligste grunnen til at man velger en smidig utviklingsprosess. Det hender ved plandrevne prosessmodeller at kunden og utviklerne ikke har hatt samme idé om hvordan produktet skal se ut. I så tilfelle kan det hende man ikke oppdager feilen før etter at produktet er ferdigstilt. Dette er enormt tidkrevende og dyrt. Fordelen med en smidig prosess med kontinuerlig levering er at man kan tilpasse seg underveis med hyppig feedback fra kunden. Virtuoso kino ønsker å tilby noe som er unikt i markedet, og trenger derfor en ny løsning. Dette kommer med iboende risiko for at man oppdager noe nytt underveis som man må ta høyde for. Eksempelvis kan man ved brukertesting oppdage at noe fungerer bedre/dårligere enn forventet og ønske å tilpasse produktet deretter. I en smidig utvilkingsprosess burde man alltid være klar for slike endringer.

### d)

Vi mener at for Virtuoso kino passer en tidsboksbasert tidsflyt best. Dette er fordi scrum er laget for kontinuerlig levering og vil gjøre det enkelt å få hyppig og effektiv feedback fra brukerne av systemet. Dette er nyttig, siden systemet løser et problem ingen har hatt før. Det kan likevel være gunstig å benytte kanban innad i sprintene for å holde oversikt over oppgaver som må løses. På denne måten holder man hyppig kontakt med kunden, og god oversikt over arbeidet innad i teamet.

## OPPGAVE 4

### a)

Prioritert liste med 6 brukerhistorier(funksjonelle krav):
1. Som kunde ønsker jeg å enkelt kunne kjøpe billetter til VR-kino slik at jeg kan få en unik og underholdene opplevelse.
2. Som administrator ønsker jeg å legge inn nye filmer slik at kundene har noe å kjøpe.
3. Som kunde ønsker jeg flere alternativer for å se og laste ned billetten min slik at jeg kan velge det som passer meg best når det er billettkontroll.
4. Som medlem ønsker jeg å se de oppsparte poengene mine slik at jeg kan vite når jeg kan dra på kino gratis.
5. Som administrator ønsker jeg å enkelt kunne hente ut statistikk om visninger slik at jeg kan hjelpe kinoen å glede kundene best mulig.
6. Som leder ønsker jeg å kunne se de totale salgene våre slik at jeg kan få et overblikk over økonomien til kinoen.

### b)

Ikke-funksjonelle krav:
Produktkrav:
- Systemet skal laste inn kjøpesiden på under 3 sekunder for 95% av brukerne.

Organisatoriske krav:
- Systemet skal være enkelt å vedlikeholde av driftsteknikere, og ha dokumentasjon på serveroppsett.

Ekstrene krav:
- Systemet skal følge GDPR og beskytte kundedata mot uautorisert tilgang.
- Systemet skal kunne kommunisere sikkert med eksterne betalingsleverandører (HTTPS, kryptering).

### c)
Ytelsen kan testes med en automatisert test som laster siden og ser hvor lang tid det tar.
Dokumentasjonen for vedlikehold av systemet kan testes ved at man observerer en ny tekniker som forsøker å bruke systemet og dokumentasjonen.
Dette kan sjekkes både ved å undersøke hvordan data lagres i henhold til reglene, og ved eksterne pen-tester og undersøkelser fra eksterne selskaper.
De fleste betalingsleverandører tilbyr et sandbox-miljø som kan brukes til å teste integrasjonen med de.

## OPPGAVE 5

### a)

Se vedlegg.

### b)

Dette er et veldig simpelt use case diagram som ikke bryter ned oppgavene til de forskjellige aktørene stort. 

For kunde:
1. Kjøp billett(hovedflyt):
  - Aktør: kunde
  - Pre-betingelser: Kunden vil ha en billett og har en betalingsmetode tilgjengelig.
  - Post-betingelser: Kunden har fått tilgang til en gyldig billett.
    - Kunden velger detaljer for billetten de vil ha; film, tidspunkt, sete, osv.
    - Kunden gir betalingsinformasjon
    - Systemet prosesserer forespørselen
    - Systemet generer billetten til kunden
    - Systemet gir kunden tilgang til billetten
2. Kjøp billett (alternativ flyt)
  - Kunden velger detaljer for billetten de vil ha; film, tidspunkt, sete, osv.
  - Kunden gir betalingsinformasjon
  - Systemet prosesserer forespørselen
  - Betalingen feiler
  - Systemet gir mulighet for kunden til å prøve igjen
3. Se billett(hovedflyt):
  - Aktør: kunde
  - Pre-betingelser: Kunden har kjøpt en billett.
  - Post-betingelser: Kunden får se ønsker billett.
    - Kunden oppgir innloggingsinformasjon.
    - Systemet bekrefter kundens identitet.
    - Kunden ber systemet om billeten.
    - Systemet henter billetten.
    - Systemet presenterer billetten for kunden.
4. Se billett(alternativ flyt):
  - Kunden kontaker personale og identifiserer seg.
  - Personale søker etter kunden i systemet.
  - Systemet finner billetter som tilhører kunden.
  - Personale bekrefter billetten kunden ser etter.
  - Personale viser kunden billetten.
5. Last ned billett(hovedflyt):
  - Aktør: Kunde
  - Pre-betingelser: Kunden har kjøpt en billett.
  - Post-betingelser: Kunden har en nedlastet kopi av billetten.
    - Kunden oppgir innloggingsinformasjon.
    - Systemet bekrefter kundens identitet.
    - Kunden ber systemet om å laste ned billeten.
    - Systemet henter billetten.
    - Systemet klargjør en nedlastet kopi av billetten.
    - Systemet gjør kunden oppmerksom på den nedlastede kopien.
6. Se poeng(hovedflyt):
  - Aktør: medlem
  - Pre-betingelser: Ingen betingelser så lenge aktøren er medlem.
  - Post-betingelser: Medlemmet vet hvor mange poeng de har.
    - Medlemmet oppir innlogginsinformasjon.
    - Systemet bekrefter medlemmets identitet.
    - Medlemmet ber om antall poeng.
    - Systemet henter antall poeng medlemmet har.
    - Systemet presenterer antall poeng for medlemmet.
7. Legge inn film(hovedflyt):
  - Aktør: administrator
  - Pre-betingelser: Administratoren har all nødvendig informasjon om filmen.
  - Post-betingelser: Filmen er i systemet og det er klart for at kunder kan kjøpe billetter til den.
    - Administratoren oppgir innlogginsinformasjon.
    - Systemet bekrefter administratorens identitet.
    - Administratoren ber systemet opprette film.
    - Systemet ber administratoren om nødvendig informasjon.
    - Administratoren oppgir informasjon.
    - Systemet verifiserer at informasjonen er gyldig.
    - Systemet oppretter filmen.
    - Systemet informerer administratoren om at filmen er opprettet.
8. Hente ut statistikk(hovedflyt):
  - Aktør: administrator
  - Pre-betingelser: Administratoren vet hva slags statistikk som skal hentes og systemet har samlet denne statistikken.
  - Post-betingelser: Administratoren har blitt presentert med statistikken.
    - Administratoren oppgir innlogginsinformasjon.
    - Systemet bekrefter administratorens identitet.
    - Administratoren ber systemet hente statistikk.
    - Systemet henter statistikken.
    - Systemet organiserer statistikken slik at den kan hentes ut.
    - Systemet presenterer statistikken til administratoren.
9. Se totale salg(hovedflyt):
  - Aktør: leder
  - Pre-betingelser: Ingen.
  - Post-betingelser: Lederen har blitt presentert totale salg.
    - Leder oppgir innlogginsinformasjon.
    - Systemet bekrefter leders identitet.
    - Leder ber om totale salg.
    - Systemet henter relevant informasjon.
    - Systemet behandler informasjonen for å finne totale salg.
    - Systemet presenterer leder med totale salg.
