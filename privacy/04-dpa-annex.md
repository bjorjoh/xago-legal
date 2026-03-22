# Databehandleravtale (DPA)
**Data Processing Agreement — Bilag A til Lisensavtale**

*I henhold til GDPR artikkel 28 / personopplysningsloven*

---

| | |
|---|---|
| **Behandlingsansvarlig / Data Controller** | [CUSTOMER NAME], org.nr. [CUSTOMER ORG.NO], [ADDRESS] |
| **Databehandler / Data Processor** | Xago Software AS, org.nr. 927 323 388, Hasle Linje 10, 0571 Oslo |
| **Tilknyttet avtale** | Lisensavtale for Xago PTE-applikasjoner, datert [DATE] |
| **DPA-dato** | [DATE] |

---

## 1. Bakgrunn og formål

Denne Databehandleravtalen ("DPA") er et bindende bilag til Lisensavtalen mellom Behandlingsansvarlig og Xago Software AS ("Xago") som Databehandler.

I forbindelse med levering av programvaretjenester under Lisensavtalen vil Xago behandle personopplysninger på vegne av Behandlingsansvarlig. Denne DPA regulerer partenes rettigheter og plikter i samsvar med GDPR artikkel 28 og norsk personopplysningslov.

Ved motstrid mellom denne DPA og Lisensavtalen, gjelder DPA for spørsmål knyttet til behandling av personopplysninger.

---

## 2. Definisjoner

| Begrep | Definisjon |
|---|---|
| "Personopplysninger" | Opplysninger som kan knyttes til en identifisert eller identifiserbar fysisk person (GDPR art. 4(1)) |
| "Behandling" | Enhver operasjon på personopplysninger, inkl. lagring, bruk og sletting (GDPR art. 4(2)) |
| "Behandlingsansvarlig" | Kunden — den som bestemmer formål og midler for behandlingen |
| "Databehandler" | Xago Software AS — behandler opplysninger på vegne av kunden |
| "Underdatabehandler" | Tredjepart som Xago benytter i leveransen |
| "GDAP" | Granular Delegated Admin Privileges — Microsofts tilgangsmekanisme for partnere |

---

## 3. Omfang og struktur

Denne DPA dekker to adskilte behandlingsscenarioer:

- **Omfang A:** Behandling av opplysninger i Kundens Business Central-tenant via GDAP
- **Omfang B:** Behandling av opplysninger i Xagos egen plattform (Dispatcher)

---

## 4. Omfang A — Kundens Business Central-miljø (GDAP)

### 4.1 Beskrivelse

Xago gis begrenset GDAP-tilgang til Kundens Microsoft-tenant for å levere support, implementering og vedlikehold. Behandlingsansvarlig beholder full kontroll over tenant og data.

### 4.2 Kategorier av personopplysninger

Avhengig av oppdrag kan Xago få tilgang til opplysninger som:
- Ansattnavn og kontaktopplysninger i BC
- Transaksjonsdata med tilknyttede personopplysninger
- Brukerkontoer og tilgangsprofiler

### 4.3 Særlig om datalagring

> Xago **lagrer ingen kopi** av personopplysninger fra Kundens BC-miljø i egne systemer. All data forblir i Kundens Microsoft-tenant, underlagt Microsofts egne databehandlervilkår med Kunden.

Datalagring og dataresidency for Scope A styres av Microsofts egne avtaler og Kundens valg av region i Microsoft-plattformen.

### 4.4 Kundens ansvar

Kunden er ansvarlig for:
- Å konfigurere og administrere GDAP-tilganger korrekt
- Å tilbakekalle Xagos tilgang ved avtalens opphør
- Å sikre at Xagos GDAP-tilgang er begrenset til nødvendig omfang

### 4.5 Ansvarsbegrensning for Omfang A

Xagos ansvar under Omfang A er begrenset til behandling som finner sted innenfor den GDAP-tilgangen Kunden har tildelt. Xago er ikke ansvarlig for sikkerhetshendelser i Kundens miljø som Xago ikke har kontroll over.

---

## 5. Omfang B — Xago Dispatcher-plattformen

### 5.1 Beskrivelse

Xago behandler personopplysninger om Kundens brukere i forbindelse med drift av Dispatcher-plattformen.

### 5.2 Behandlingens formål

- Brukerautentisering og tilgangsstyring
- Levering av Dispatcher-funksjonalitet
- Varsling og kommunikasjon
- Feilsøking og support

### 5.3 Kategorier av registrerte

- Kundens ansatte / sluttbrukere av Dispatcher

### 5.4 Kategorier av personopplysninger

- Navn og e-postadresse (fra Entra ID / Azure AD)
- Hashet telefonnummer for varslinger *(merk: lavt entropitall — Xago vurderer dette som personopplysninger og behandler det deretter)*
- Brukerrolle og tilgangsnivå
- Aktivitetslogg knyttet til operasjoner i Dispatcher

### 5.5 Lagringstid

Personopplysninger i Omfang B slettes innen **60 dager** etter avsluttet kundeforhold, med mindre lovpålagte lagringsforpliktelser krever lengre oppbevaring.

---

## 6. Xagos plikter som databehandler

Xago forplikter seg til å:

1. Kun behandle personopplysninger i henhold til dokumenterte instrukser fra Behandlingsansvarlig. Xago skal straks informere Behandlingsansvarlig dersom instruksene er mangelfulle eller i strid med norsk personvernlovgivning, eller dersom Xago er pålagt ved lov å behandle opplysningene i strid med instruksene.
2. Sikre at medarbeidere med tilgang til personopplysningene er underlagt taushetsplikt
3. Iverksette nødvendige tekniske og organisatoriske sikkerhetstiltak, jf. GDPR artikkel 32, nærmere beskrevet i Vedlegg 2
4. Bistå Behandlingsansvarlig med å oppfylle de registrertes rettigheter (GDPR kapittel III), herunder rett til informasjon, innsyn, retting og sletting
5. Bistå Behandlingsansvarlig med DPIA, risikovurdering og varsling til tilsynsmyndigheter der relevant (GDPR artikkel 32–36)
6. Slette eller returnere personopplysninger ved avtalens opphør, etter Behandlingsansvarligs valg
7. Stille nødvendig informasjon til rådighet for å dokumentere etterlevelse, og legge til rette for revisjoner og inspeksjoner, jf. punkt 10
8. Føre protokoll (logg) over behandlingsaktiviteter utført på vegne av Behandlingsansvarlig i henhold til GDPR artikkel 30. Behandlingsansvarlig kan til enhver tid kreve oversendt kopi av slik protokoll.
9. Umiddelbart varsle Behandlingsansvarlig dersom en myndighet ber om utlevering av personopplysninger behandlet under denne DPA. Xago skal ikke etterkomme slik forespørsel uten skriftlig forhåndsgodkjenning fra Behandlingsansvarlig, med mindre loven krever det. Dersom loven forbyr underretning, plikter Xago ikke å varsle.

Xagos plikt til å gi bistand etter punkt 4 og 5 skal vurderes opp mot behandlingens art og den informasjonen som er tilgjengelig for Xago. Xago har rett til å fakturere Behandlingsansvarlig for rimelig arbeid med å oppfylle disse bistandspliktene.

---

## 7. Behandlingsansvarliges plikter

Behandlingsansvarlig er ansvarlig for at personopplysninger blir behandlet i samsvar med personopplysningsloven og annen gjeldende personvernlovgivning. Behandlingsansvarlig har rett og plikt til å fastsette formålet med behandlingen og hvilke hjelpemidler som kan brukes.

Behandlingsansvarlig er ansvarlig for:
- Å sikre at behandlingen har et lovlig behandlingsgrunnlag
- Å gi Xago dokumenterte instrukser for hvordan personopplysninger skal behandles
- Å konfigurere og administrere GDAP-tilganger korrekt (Omfang A)
- Å tilbakekalle Xagos tilgang ved avtalens opphør (Omfang A)
- Å sikre at Xagos GDAP-tilgang er begrenset til nødvendig omfang (Omfang A)

---

## 8. Underdatabehandlere

Xago benytter følgende kategorier underdatabehandlere:

| Kategori | Eksempel | Behandlingsland | Overføring utenfor EØS |
|---|---|---|---|
| Skyinfrastruktur | Microsoft Azure | EØS | Nei |
| Autentisering | Microsoft Entra ID | EØS | Nei |
| [Kommunikasjon] | [Leverandør] | [Land] | [Ja/Nei] |

Behandlingsansvarlig gir herved generell forhåndsgodkjenning til bruk av underdatabehandlere i de kategorier som er listet opp. Xago sikrer at bindende avtale i henhold til GDPR artikkel 28 nr. 2 og 4 er inngått med alle underdatabehandlere, og fører oppdatert oversikt over disse.

Xago varsler Behandlingsansvarlig skriftlig ved planlagte endringer i underdatabehandlerliste. Behandlingsansvarlig kan nekte endringen ved begrunnet mistanke om at personvernet kan bli svekket som følge av endringen.

Behandlingsansvarlig må gjøre sin rett til å nekte gjeldende ved skriftlig varsel til Xago innen **14 kalenderdager** etter mottatt informasjon om endringen. Mottas ikke slikt varsel innen fristen, anses endringen godkjent.

Dersom Behandlingsansvarlig nekter og Xago fastholder endringen, kan Behandlingsansvarlig i en periode på **30 kalenderdager** etter mottatt skriftlig varsel om at endringen opprettholdes, si opp denne avtalen og Lisensavtalen med virkning fra 14 kalenderdager etter at Xago har mottatt oppsigelsen. Sies ikke avtalene opp innen fristen, anses endringen godkjent.

---

## 9. Sikkerhet

Xago har iverksatt følgende tekniske og organisatoriske tiltak:

- Kryptering av data i overføring (TLS) og i hvile
- Rollebasert tilgangsstyring med prinsipp om minste nødvendige tilgang
- Logging og overvåking av tilganger
- Regelmessige sikkerhetsvurderinger
- Prosedyrer for håndtering av avvik og sikkerhetsbrudd

Nærmere beskrivelse av sikkerhetstiltakene fremgår av Vedlegg 2.

---

## 10. Revisjon

Xago skal legge til rette for at Behandlingsansvarlig kan utføre revisjoner og inspeksjoner, enten selv eller ved en uavhengig tredjepart utpekt av Behandlingsansvarlig, for å verifisere at forpliktelsene i denne DPA overholdes.

Hver av partene dekker sine egne kostnader forbundet med en revisjon. Dersom en revisjon avdekker vesentlige avvik fra forpliktelsene i denne avtalen, skal alle kostnader forbundet med revisjonen dekkes av Xago, herunder Behandlingsansvarliges og eksterne revisorers rimelige kostnader.

---

## 11. Avvikshåndtering

Xago varsler Behandlingsansvarlig uten unødig opphold etter å ha blitt kjent med et sikkerhetsbrudd som berører personopplysninger under denne DPA.

Varslet skal minimum beskrive:

- arten av bruddet på personopplysninger, herunder om mulig kategoriene og omtrentlig antall berørte registrerte og berørte personopplysninger;
- navn og kontaktinformasjon til personvernansvarlig eller annet kontaktpunkt der mer informasjon kan fås;
- de sannsynlige konsekvensene av sikkerhetsbruddet;
- tiltakene som er truffet eller foreslått for å håndtere sikkerhetsbruddet, herunder eventuelt tiltak for å redusere mulige skadevirkninger.

Dersom ikke all informasjon kan gis i første varsel, skal informasjonen gis så snart som mulig, og senest innen **72 timer** etter at sikkerhetsbruddet ble kjent. Behandlingsansvarlig er ansvarlig for å sende hendelsesrapporten til Datatilsynet dersom det kreves etter GDPR artikkel 33.

---

## 12. Disposisjonsrett til data

Xagos disposisjonsrett til data (inkludert personopplysninger) er begrenset til behandlingsformålene definert i denne DPA. Xago kan ikke holde tilbake data.

Behandlingsansvarlig har rett til å få utlevert data på maskinlesbart format på forespørsel.

Xago kan i tillegg bruke Kundens data i anonymisert og aggregert form for å videreutvikle og forbedre sine produkter.

---

## 13. Overføring til tredjeland

Personopplysninger overføres ikke til land utenfor EØS uten at overføringen er basert på et gyldig overføringsgrunnlag (EUs SCCs eller tilsvarende). Xago varsler Behandlingsansvarlig i forkant dersom slik overføring planlegges.

---

## 14. Ansvar og erstatning

Ansvar og erstatning er regulert i Lisensavtalen.

---

## 15. Varighet og opphør

Denne DPA gjelder så lenge Xago behandler personopplysninger på vegne av Behandlingsansvarlig under Lisensavtalen.

Ved Xagos brudd på denne DPA eller gjeldende personvernlovgivning kan Behandlingsansvarlig pålegge Xago å stoppe den videre behandlingen av opplysningene med øyeblikkelig virkning.

Ved avtalens opphør skal Xago, etter Behandlingsansvarligs skriftlige valg, enten:
- Slette alle personopplysninger og bekrefte slettingen skriftlig, eller
- Returnere personopplysningene i et egnet format

Slettingen eller tilbakeleveringen skal gjennomføres senest **60 dager** etter avtalens opphør.

---

## 16. Lovvalg og verneting

Denne DPA er underlagt norsk rett og GDPR slik det er implementert i norsk lov gjennom personopplysningsloven. Lovvalg og verneting følger for øvrig av Lisensavtalen.

---

## Underskrifter

| Xago Software AS (Databehandler) | [CUSTOMER NAME] (Behandlingsansvarlig) |
|---|---|
| Navn: _________________ | Navn: _________________ |
| Tittel: _________________ | Tittel: _________________ |
| Sted: _________________ | Sted: _________________ |
| Dato: _________________ | Dato: _________________ |
| Signatur: _________________ | Signatur: _________________ |

---

## Vedlegg 1: Behandlingens omfang

### Hovedavtalen

Lisensavtale for Xago PTE-applikasjoner, datert [DATE].

### Formålet med behandlingen

Behandling som er nødvendig for at Xago skal oppfylle sine forpliktelser etter Lisensavtalen, herunder:
- Levering, drift og vedlikehold av Dispatcher-plattformen (Omfang B)
- Support, implementering og vedlikehold i Kundens Business Central-miljø via GDAP (Omfang A)

### Behandlingens art

Registrering, strukturering, lagring, bruk, endring, utlevering, sletting og annen behandling som følger av Lisensavtalen.

### Kategorier av registrerte

- Kundens ansatte og sluttbrukere av Dispatcher (Omfang B)
- Ansatte og kontaktpersoner registrert i Kundens Business Central (Omfang A)

### Kategorier av personopplysninger

**Omfang A:**
- Ansattnavn og kontaktopplysninger i BC
- Transaksjonsdata med tilknyttede personopplysninger
- Brukerkontoer og tilgangsprofiler

**Omfang B:**
- Navn og e-postadresse (fra Entra ID / Azure AD)
- Hashet telefonnummer for varslinger
- Brukerrolle og tilgangsnivå
- Aktivitetslogg knyttet til operasjoner i Dispatcher

### Underdatabehandlere og overføring utenfor EØS

| Underdatabehandler | Tjeneste | Behandlingsland | Overføring utenfor EØS |
|---|---|---|---|
| Microsoft Azure | Skyinfrastruktur | EØS | Nei |
| Microsoft Entra ID | Autentisering | EØS | Nei |
| [Leverandør] | [Tjeneste] | [Land] | [Ja/Nei] |

---

## Vedlegg 2: Sikkerhetstiltak

### Tekniske tiltak

- Kryptering av data i overføring (TLS 1.2+) og i hvile
- Rollebasert tilgangsstyring med prinsipp om minste nødvendige tilgang
- Logging og overvåking av tilganger
- Regelmessig sikkerhetsoppdatering av plattformkomponenter
- Sikkerhetskopi (backup) med regelmessig testing av gjenoppretting

### Organisatoriske tiltak

- Taushetsplikt for alle ansatte med tilgang til personopplysninger
- Opplæring i personvern og informasjonssikkerhet
- Prosedyrer for håndtering av avvik og sikkerhetsbrudd
- Regelmessige sikkerhetsvurderinger og risikoanalyser

### Adferdsnormer eller sertifiseringsordning

[Dersom Xago er forpliktet til å følge godkjente adferdsnormer (GDPR artikkel 40) eller godkjent sertifiseringsordning (GDPR artikkel 42) skal dette beskrives her.]

---

*Dette dokumentet er et avtaleutkast og bør gjennomgås av juridisk rådgiver eller personvernombud før bruk.*
