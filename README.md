# Alle Belgische adressen en bijbehorende postcodes

![Adressen](https://img.shields.io/badge/adressen-7.006.380-brightgreen) ![Laatste update](https://img.shields.io/badge/laatste%20update-21--02--2026-brightgreen)

<a href="https://www.buymeacoffee.com/Lars-" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-orange.png" alt="Buy Me A Coffee" height="60" style="height: 60px !important;width: 217px !important;" ></a>

Deze repository bevat alle Belgische adressen, bijbehorende postcodes, coördinaten en andere belangrijke gegevens.

## Why Dutch?

This readme is in Dutch (except this part) because the content is based on Belgian data. The data itself uses Dutch for Flanders and Brussels, French for Wallonia. If you need help understanding this readme, please let us know.

## Doel

Een abonnement op postcodediensten is vaak duur, terwijl deze informatie gratis beschikbaar is bij overheidsinstanties. Helaas verstrekken zij niet één groot bestand met alle informatie, en daar maken bedrijven graag gebruik van.

In deze repository vind je alle gegevens die je nodig hebt om adressen naar postcodes om te zetten en vice versa.

## Inhoud

Alles is ingepakt in .zst-bestanden om ruimte te besparen.

- **België.csv.zst** (31M): dit archief bevat een CSV-bestand met alle Belgische adressen en de volgende gegevens:
    - Straatnaam
    - Huisnummer
    - Busnummer
    - Postcode
    - Gemeente
    - Provincie
    - Gewest
    - Latitude (WGS84)
    - Longitude (WGS84)

- **Gewestbestanden** (3 bestanden): CSV-bestanden van alle adressen, gesplitst per gewest:
    - Vlaanderen.csv.zst (4.184.686 adressen)
    - Brussel.csv.zst (837.527 adressen)
    - Wallonië.csv.zst (1.984.167 adressen)

### CSV-formaat

De CSV-bestanden gebruiken **puntkomma (;)** als scheidingsteken en UTF-8 encoding.

**Headers:**
```
straat;huisnummer;busnummer;postcode;gemeente;provincie;gewest;lat;lon
```

**Voorbeeld:**
```
Nieuwstraat;1;;1000;Brussel;;Brussel;50.84847153;4.35243577
Grote Markt;1;;2000;Antwerpen;Antwerpen;Vlaanderen;51.22108;4.39920
Rue de la Loi;16;;1000;Bruxelles;;Brussel;50.84565;4.36634
```

## Technische details

- **Coördinatensysteem:** WGS84 (EPSG:4326) - standaard GPS coördinaten
- **CSV delimiter:** Puntkomma (;)
- **Encoding:** UTF-8
- **Talen:** Nederlands (Vlaanderen, Brussel), Frans (Wallonië)

## Veelgestelde vragen

**Q: Waarom is er geen provincie voor Brussel?**
A: Het Brussels Hoofdstedelijk Gewest is zowel gewest als gemeente, zonder provinciale tussenlaag.

## Maatwerk

Geïnteresseerd in maatwerk op basis van deze gegevens of iets anders? Neem dan contact op via [info@ljpc.nl](mailto:info@ljpc.nl?subject=Postcode%20repository).

## Doneren

Als we je zojuist een hoop tijd en geld bespaard hebben, zouden we het fijn vinden als je zou willen overwegen een donatie te doen. Alle donaties worden gebruikt om systemen als dit mogelijk te maken.

<a href="https://www.buymeacoffee.com/Lars-" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-orange.png" alt="Buy Me A Coffee" height="60" style="height: 60px !important;width: 217px !important;" ></a>
