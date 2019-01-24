# Verbruikgegevens Energie per Energie leverancier

### Leveranciers

De Provincie Zuid-Holland heeft 3 energie leveranciers:

1. [Liander](https://www.liander.nl/partners/datadiensten/open-data)
2. [Stedin](https://www.stedin.net/zakelijk/open-data/verbruiksgegevens)
3. [Westland](https://www.westlandinfra.nl/over-westland-infra/open-data)

![](https://www.energieleveranciers.nl/media/1986/netbeheer_stroom_nieuw.png)
[bron](https://www.energieleveranciers.nl/netbeheerders/elektriciteit)

Data over de [Gebiedsindeling Netbeheerders Elektriciteit, Gas en Water](http://nationaalgeoregister.nl/geonetwork/srv/dut/catalog.search#/metadata/f9e6604c-b942-4b9d-a784-3f3ad4aa6dc1) is te vinden op het Nationaal GeoRegister. 

Alle drie leveranciers leveren ook open data over het kleinverbruik van elektriciteit en gas van hun eigen verzorgingsgebied 

## Liander

### Kleinverbruiksdata per jaar

Het energieverbruik van kleine aansluitingen. Gas tot en met een capaciteit van 40 m3/h en elektriciteit tot en met een capaciteit van 3x80 ampère. Om de anonimiteit van de gegevens te waarborgen worden deze gegevens 
geaggregeerd. Per regel worden minimaal 10 aansluitingen samengevoegd, waarbij het samenvoegen van postcodes voor kan komen. 

**Bron url:** https://www.liander.nl/partners/datadiensten/open-data
**Jaar:** 2009 t/m 2018
**Niveau:** Postcode 6
**Formaat:** CSV

### Inhoud 

| Attribuut   | C-AR 1              |  Waarde           | Omschrijving                |
|---------|---------------------|-------------------|-----------------------------|
| NETBEHEERDER | A.02 | Tekst | De EAN-code van de regionale netbeheerder  (voor kleinverbruik aansluitingen is de Netbeheerder tevens de  Meetverantwoordelijke) |
| NETGEBIED | A.06 | Tekst | Aanduiding  van het gesloten inkoopgebied waar een aansluiting onder valt.|
| STRAATNAAM | A.10 | Tekst | De straatnaam. Als de kolommen POSTCODE_VAN en  POSTCODE_TOT verschillen  dan betreft het de straatnaam  die behoort bij POSTCODE_VAN. |
| POSTCODE_VAN | A.07 | Tekst | De postcode in het formaat 4 cijfers 2 letters zonder spatie|
| POSTCODE_TOT | A.07 | Tekst | Als binnen  het gebied van POSTCODE_VAN meer dan 9 aansluitingen aanwezig zijn, dan is deze kolom gelijk aan POSTCODE_VAN. Als binnen het gebied van POSTCODE_VAN minder dan 10  aansluitingen aanwezig zijn worden er meerdere postcodes samengevoegd om de anonimiteit van de data te waarborgen. In dat geval staat in deze kolom de bovengrens van de bepaalde postcodereeks. De postcode heeft het formaat 4 cijfers 2 letters zonder spatie |
| WOONPLAATS | A.11 | Tekst | De plaatsnaam. Als de kolommen POSTCODE_VAN en POSTCODE_TOT verschillen dan  betreft het de plaatsnaam  die behoort bij POSTCODE_VAN. |
| LANDCODE | A.60 | “NL” | De  land code  van Nederland conform ISO-code 3166 alpha-2 
| PRODUCTSOORT | A.17 | “ELK” of  “GAS” | De energiesoort waarbij   ELK  staat voor  Elektriciteit en GAS  voor Gas |
| VERBRUIKSSEGMENT | A.18 | “KVB” | Verbruikssegment kleinverbruik ,  dat wil zeggen dat de aansluitwaarde  van een elektriciteitsaansluiting  niet groter  is dan 3x 80  ampère   en een gasaansluiting niet groter is dan  G25.|
| AANSLUITINGEN_AANTAL | | Getal | Het aantal aansluitingen in het betreffende postcodegebied  voor  de betreffende energiesoort. |
| LEVERINGSRICHTING_PERC | A.19 | Percentage | Percentage van de aansluitingen dat netto elektriciteits- of  gasverbruik heeft. Dit percentage wordt lager naarmate er  meer  teruglevering plaatsvindt (b.v. vanwege   zonnepanelen)| 
| FYSIEKE_STATUS_PERC | A.21 | Percentage | Het percentage van de aansluitingen dat in bedrijf is (C-AR  code IBD). De overige aansluitingen zijn in aanleg, uit bedrijf  of gesloopt  (respectievelijk C-AR codes IAL, UBD en SLP) |
| SOORT_AANSLUITING_PERC | A.29 | Percentage | Bij gas en   elektriciteit  wordt de zwaarte van de  aansluiting aangeduid met aansluitcapaciteit, ook wel   aansluitwaarde genoemd. De aansluitwaarde geeft aan  hoeveel   ampère elektriciteit of m³ /uur gas er door de  aansluiting kan. Hier wordt het percentage van de meest voorkomende aansluitwaarde weergegeven |

Meer informatie over de data:

* https://www.liander.nl/sites/default/files/Over-Liander-Toelichting-dataset-kleinverbruikgegevens.pdf.pdf





## Download urls

### Liander 

    https://www.liander.nl/sites/default/files/LianderKV01012018.zip
    https://www.liander.nl/sites/default/files/Liander_kleinverbruiksgegevens_01012017_0.zip
    https://www.liander.nl/sites/default/files/Liander_kleinverbruiksgegevens_01012016.zip
    https://www.liander.nl/sites/default/files/Liander_kleinverbruiksgegevens_01012015.zip
    https://www.liander.nl/sites/default/files/Liander_kleinverbruiksgegevens_01012014.zip
    https://www.liander.nl/sites/default/files/Liander_kleinverbruiksgegevens_01012013.zip
    https://www.liander.nl/sites/default/files/Liander_kleinverbruiksgegevens_01012012.zip
    https://www.liander.nl/sites/default/files/Liander_kleinverbruiksgegevens_01012011.zip
    https://www.liander.nl/sites/default/files/Liander_kleinverbruiksgegevens_01012010.zip
    https://www.liander.nl/sites/default/files/Liander_kleinverbruiksgegevens_01012009.zip


### Stedin

    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012018.zip
    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012017.zip
    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012016.zip
    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012015.zip
    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012014.zip
    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012013.zip
    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012012.zip
    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012011.zip
    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012010.zip
    https://www.stedin.net/zakelijk/~/media/files/stedin/open-data/stedin_kleinverbruiksgegevens_01012009.zip


### Westland

    https://www.westlandinfra.nl/application/files/2714/6037/2386/westland-infra-open-data-01-01-2011.csv
    https://www.westlandinfra.nl/application/files/1114/6037/2387/westland-infra-open-data-01-01-2012.csv
    https://www.westlandinfra.nl/application/files/4614/6037/2386/westland-infra-open-data-01-01-2013.csv
    https://www.westlandinfra.nl/application/files/1214/6037/2385/westland-infra-open-data-01-01-2014.csv
    https://www.westlandinfra.nl/application/files/7914/6037/2386/westland-infra-open-data-01-01-2015.csv
    https://www.westlandinfra.nl/application/files/2114/6037/2387/westland-infra-open-data-01-01-2016.csv
    https://www.westlandinfra.nl/application/files/6915/1818/0337/westland-infra-open-data-01-01-2017.csv
    https://www.westlandinfra.nl/application/files/3315/1818/0337/westland-infra-open-data-01-01-2018.csv


## Download FME script en bewerkingen

1. Download jaren 2014 tot 2016
2. Standaardiseren van attribuut namen
3. Opslaan als 1 lijst 


* Opsplitsing in Gas en Elek ? 
* Clip op Zuid-Holland Postcodes ??


