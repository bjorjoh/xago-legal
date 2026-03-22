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

Personopplysninger i Omfang B slettes innen **90 dager** etter avsluttet kundeforhold, med mindre lovpålagte lagringsforpliktelser krever lengre oppbevaring.

---

## 6. Xagos plikter som databehandler

Xago forplikter seg til å:

1. Kun behandle personopplysninger i henhold til dokumenterte instrukser fra Behandlingsansvarlig
2. Sikre at medarbeidere med tilgang til personopplysningene er underlagt taushetsplikt
3. Iverksette nødvendige tekniske og organisatoriske sikkerhetstiltak, jf. GDPR artikkel 32
4. Bistå Behandlingsansvarlig med å oppfylle de registrertes rettigheter
5. Bistå Behandlingsansvarlig med DPIA, risikovurdering og varsling til tilsynsmyndigheter der relevant
6. Slette eller returnere personopplysninger ved avtalens opphør, etter Behandlingsansvarligs valg
7. Stille nødvendig informasjon til rådighet for å dokumentere etterlevelse

---

## 7. Underdatabehandlere

Xago benytter følgende kategorier underdatabehandlere:

| Kategori | Eksempel | Behandlingsland |
|---|---|---|
| Skyinfrastruktur | Microsoft Azure | EØS |
| Autentisering | Microsoft Entra ID | EØS |
| [Kommunikasjon] | [Leverandør] | [Land] |

Behandlingsansvarlig gir herved generell forhåndsgodkjenning til bruk av underdatabehandlere i de kategorier som er listet opp. Xago varsler Behandlingsansvarlig skriftlig med **30 dagers varsel** ved planlagte endringer i underdatabehandlerliste.

Behandlingsansvarlig kan protestere mot endringer innen varslingsperioden. Dersom enighet ikke oppnås, kan Behandlingsansvarlig si opp avtalen.

---

## 8. Sikkerhet

Xago har iverksatt følgende tekniske og organisatoriske tiltak:

- Kryptering av data i overføring (TLS) og i hvile
- Rollebasert tilgangsstyring med prinsipp om minste nødvendige tilgang
- Logging og overvåking av tilganger
- Regelmessige sikkerhetsvurderinger
- Prosedyrer for håndtering av avvik og sikkerhetsbrudd

---

## 9. Avvikshåndtering

Xago varsler Behandlingsansvarlig uten unødig opphold — og senest innen **72 timer** — etter å ha blitt kjent med et sikkerhetsbrudd som berører personopplysninger under denne DPA.

Varslet skal inneholde tilgjengelig informasjon om bruddets art, omfang, sannsynlige konsekvenser og tiltak som er eller vil bli iverksatt.

---

## 10. Overføring til tredjeland

Personopplysninger overføres ikke til land utenfor EØS uten at overføringen er basert på et gyldig overføringsgrunnlag (EUs SCCs eller tilsvarende).

---

## 11. Varighet og opphør

Denne DPA gjelder så lenge Xago behandler personopplysninger på vegne av Behandlingsansvarlig under Lisensavtalen.

Ved avtalens opphør skal Xago, etter Behandlingsansvarligs skriftlige valg, enten:
- Slette alle personopplysninger og bekrefte slettingen skriftlig, eller
- Returnere personopplysningene i et egnet format

---

## 12. Lovvalg

Denne DPA er underlagt norsk rett og GDPR slik det er implementert i norsk lov gjennom personopplysningsloven.

---

## Underskrifter

| Xago Software AS (Databehandler) | [CUSTOMER NAME] (Behandlingsansvarlig) |
|---|---|
| Navn: _________________ | Navn: _________________ |
| Tittel: _________________ | Tittel: _________________ |
| Dato: _________________ | Dato: _________________ |
| Signatur: _________________ | Signatur: _________________ |

---

*Dette dokumentet er et avtaleutkast og bør gjennomgås av juridisk rådgiver eller personvernombud før bruk.*
