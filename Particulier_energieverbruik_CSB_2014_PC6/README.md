# Particulier energieverbruik in 2014 per postcode-6 (CBS)

Deze dataset bevat gegevens over het particulier energieverbruik in 2014 in de provincie Zuid-Holland per postcode-6. 
De dataset is overgenomen uit de [Warmte Transitie Atlas](https://warmtetransitieatlas.zuid-holland.nl/webappbuilder/apps/496/) samengesteld door adviesbureau Over Morgen in opdracht van de provincie Zuid-Holland. 
De gegevens zijn afkomstig van het CBS.

**Jaar:** 2014

**Dekking:** Zuid-Holland

**Projectie:** Amersfoort RD New EPSG:28992

**Bron Url:** 
* [Warmte Transitie Atlas](https://warmtetransitieatlas.zuid-holland.nl/webappbuilder/apps/496/)
* [ArcGIS feature service van Over Morgen](https://services5.arcgis.com/PZYGbbhVncO1YI8q/arcgis/rest/services/PZH_WTA_Energieverbruik/FeatureServer)

![](voorbeeld_particulier_energieverbruik_CBS_2014_pc6.png)

## Attributen

Het bestand bevat de volgende attributen:

| Attribuut          | Voorbeeld | Beschrijving | 
|----------         |-----------|--------------|
|OBJECTID | 11817  | Uniek identificatienummer |
|Postcode | 2332PG | Postcode |
|G_W_GEM | 930 | Gemiddeld woninggasverbruik (m3)|
|G_W_SOM | 17800 | Totaal woninggasverbruik (m3)|
|G_W_N | 19 | Aantal berekende woningen voor aardgas |
|E_W_GEM | 2370 | Gemiddeld woningelektraverbruik (kWh) |
|E_W_SOM | 	45000 | Totaal woningelektraverbruik (kWh) |
|E_W_N | 19| Aantal berekende woningen voor elektra|

## Feature class in PI sandbox

De dataset is als feature class `Particulier_energieverbruik_CBS_2014_PC6` terug te vinden in de PI sandbox database.
