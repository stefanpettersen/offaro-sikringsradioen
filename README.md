# Sikringsradiobaser i OffARO

Dette repositoryet deler et kartlag med **analoge sikringsradiobasestasjoner i Norge** for bruk i OffARO.

Kartlaget viser basestasjoner med kanalbetegnelser og tilhørende informasjon. Opplysningene er ment som et praktisk kartgrunnlag og bør kontrolleres mot offisielle kilder før operativ bruk.

## Legg til kartlaget i OffARO

1. Start **OffARO**.
2. Gå til **Settings → Config Sources → + Add Repository**.
3. Fyll inn:
   - **Repository URL:** `https://github.com/stefanpettersen/offaro-sikringsradioen`
   - **Display Name:** `Sikringsradiobaser`
   - **Auth Token:** La feltet stå tomt.
4. Lagre. Repositoryet skal vises som **Read-only (RO)**.
5. Åpne repositoryet i listen og velg **Subscribe** på konfigurasjonsfilen `sikringsradiobaser.json`.
6. Aktiver kartlaget under **Map Overlays → Drawing Layers**.

Du trenger **ikke GitHub-konto, Git eller tilgangstoken** for å bruke dette offentlige kartlaget.

## Oppdateringer

OffARO kan varsle når repositoryet har fått en ny versjon, men oppdateringer hentes ikke automatisk.

- Aktiver gjerne **Check for repository updates when app starts** under **Settings → Config Sources**.
- Ved varsel: Åpne repositoryet og velg **Pull** for å hente oppdateringene.
- Du kan også bruke **Check now** for å kontrollere manuelt.

Etter første nedlasting er kartlaget lagret lokalt og kan brukes **uten internett**, også etter omstart av OffARO. Internett kreves for å hente nye versjoner.

## Viktig

- Dette er et delt kartlag, ikke sanntidsinformasjon om drift eller tilgjengelighet.
- Opplysninger om frekvenser, kanaler og basestasjoner kan endres. Kontroller kritiske opplysninger mot gjeldende kilder.

## Feil, mangler og forslag til forbedringer

Oppdager du feil i kartlaget, manglende basestasjoner eller opplysninger som bør oppdateres, setter jeg pris på tilbakemeldinger.

Opprett gjerne en sak under [Issues på GitHub](https://github.com/stefanpettersen/offaro-sikringsradioen/issues).

Oppgi helst:

- Navn på basestasjon og kanalnummer
- Hva som er feil eller mangler
- Korrekte opplysninger og gjerne kildehenvisning

Du kan også kontakte den som vedlikeholder kartlaget direkte dersom du ikke bruker GitHub.
