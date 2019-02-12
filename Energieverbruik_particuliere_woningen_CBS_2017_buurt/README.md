
# Energieverbruik particuliere woningen; woningtype, wijken en buurten, 2017

Deze tabel geeft regionale gegevens over het gemiddelde energieverbruik per woning (aardgas en elektriciteit) van particuliere woningen onderverdeeld naar verschillende woningtypen en type eigendom voor wijken en buurten in de provincie Zuid-Holland. Daarnaast is alleen voor totaal woningen het percentage stadsverwarming opgenomen, omdat dit relevant is voor de interpretatie van de hoogte van het gemiddeld aardgasverbruik.

Definities:
Particuliere woning:
Een verblijfsobject in de Basis Registraties Adressen en Gebouwen (BAG) met als gebruiksfunctie 'woonfunctie' en géén andere functie. 

Stadsverwarming:
Een verwarmingssysteem waarbij de woningen in een wijk worden verwarmd via een ondergronds netwerk van warmwaterleidingen.

De cijfers van het gemiddeld aardgasverbruik en het gemiddeld elektriciteitsverbruik zijn afgerond op vijftigtallen en worden vermeld bij zes of meer (bewoonde) woningen per woningtype of type eigendom.

Het percentage woningen met stadsverwarming wordt vermeld bij tien of meer (bewoonde) woningen. 

**Jaar:** 2017

**Dekking:** Zuid-Holland

**Status van de cijfers:** Voorlopig

**Projectie:** Amersfoort RD New EPSG:28992

**Bron Url:** 
* https://statline.cbs.nl/StatWeb/publication/?VW=T&DM=SLNL&PA=84314NED
* https://opendata.cbs.nl/dataportaal/portal.html#/CBS/nl/dataset/table?graphtype=Table&tableId=84314NED

![](voorbeeld_energieverbruik_cbs_2017_buurt.png)

## Attributen

Het bestand bevat de volgende attributen:

| Attribuut          | Voorbeeld | Beschrijving | 
|----------         |-----------|--------------|
|buurtcode|   | Buurtcode |
|buurtnaam | | Buurtnaam|
|gemeentecode | | Gemeentecode|
|gemeentenaam || Gemeentenaam|
|wijkcode | | Wijkcode|
|ID || Uniek identificatienummer|
|Woningkenmerken | | Woningkenmerken|
|WijkenEnBuurten | | |
|SoortRegio| | Aantal berekende woningen voor aardgas|
|Codering | | Gemiddeld woningelektraverbruik (kWh)|
|GemiddeldAardgasverbruik_m3 | | Gemiddeld aardgasverbruik (m3)|
|GemiddeldElectriciteitsverbruik_kWh | | Gemiddeld electriciteitsverbruik (m3)|
|Stadsverwarming_perc| | |
|IndelingswijzigingWijkenEnBuurten | | |
|Woningkenmerken_label | ||

## Feature class in PI sandbox

De dataset is als feature class `Energieverbruik_particuliere_woningen_CBS_2017_buurt` terug te vinden in de PI sandbox database.

Deze repo bevat ook de [FME workspace](Energieverbruik_particuliere_woningen_2017.fmw) die uitgevoerd is om de dataset te op te vragen en weg te schrijven naar een file geodatabase.



