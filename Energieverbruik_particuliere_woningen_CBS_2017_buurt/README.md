
# Energieverbruik particuliere woningen; woningtype, wijken en buurten, 2017

Deze tabel geeft regionale gegevens over het gemiddelde energieverbruik per woning (aardgas en elektriciteit) van particuliere woningen onderverdeeld naar verschillende woningtypen en type eigendom voor wijken en buurten in de provincie Zuid-Holland. Daarnaast is alleen voor totaal woningen het percentage stadsverwarming opgenomen, omdat dit relevant is voor de interpretatie van de hoogte van het gemiddeld aardgasverbruik.

Definities:    
Particuliere woning:    
Een verblijfsobject in de Basis Registraties Adressen en Gebouwen (BAG) met als gebruiksfunctie 'woonfunctie' en géén andere functie.   

Stadsverwarming:    
Een verwarmingssysteem waarbij de woningen in een wijk worden verwarmd via een ondergronds netwerk van warmwaterleidingen.    

De cijfers van het gemiddeld aardgasverbruik en het gemiddeld elektriciteitsverbruik zijn afgerond op vijftigtallen en worden vermeld bij zes of meer (bewoonde) woningen per woningtype of type eigendom.    

Het percentage woningen met stadsverwarming wordt vermeld bij tien of meer (bewoonde) woningen.     

Let op:    
De feature class bevat meerdere features voor dezelfde buurt. De waarde van het attributen `Woningkenmerken` en `Woningkenmerken_label` is dan steeds verschillend.    

**Jaar:** 2017

**Dekking:** Zuid-Holland

**Status van de cijfers:** Voorlopig

**Projectie:** Amersfoort RD New EPSG:28992

**Bron Url:** 
* https://statline.cbs.nl/StatWeb/publication/?VW=T&DM=SLNL&PA=84314NED
* https://opendata.cbs.nl/dataportaal/portal.html#/CBS/nl/dataset/table?graphtype=Table&tableId=84314NED

## Attributen

Het bestand bevat de volgende attributen:

| Attribuut          | Voorbeeld | Beschrijving | 
|----------         |-----------|--------------|
| OBJECTID| 1| Uniek identificatienummer |
|buurtcode| BU17830701  | Buurtcode |
|buurtnaam | Buitengebied De Lier | Buurtnaam|
|gemeentecode |GM1783 | Gemeentecode|
|gemeentenaam |Westland| Gemeentenaam|
|wijkcode |WK178307 | Wijkcode|
|ID |15523| |
|Woningkenmerken |a | Woningkenmerken (gecodeerd)|
|WijkenEnBuurten | BU17830701| |
|SoortRegio|Buurt | Aantal berekende woningen voor aardgas|
|Codering |BU17830701 | Gemiddeld woningelektraverbruik (kWh)|
|GemiddeldAardgasverbruik_m3 |2310 | Gemiddeld aardgasverbruik (m3)|
|GemiddeldElectriciteitsverbruik_kWh |4800 | Gemiddeld electriciteitsverbruik (m3)|
|Stadsverwarming_perc|<null> | |
|IndelingswijzigingWijkenEnBuurten |1 | |
|Woningkenmerken_label | Totaal woningen |Omschrijving van woningkenmerken|

## Feature class in PI sandbox

De dataset is als feature class `Energieverbruik_particuliere_woningen_CBS_2017_buurt` terug te vinden in de PI sandbox database.

Deze repo bevat ook de [FME workspace](Energieverbruik_particuliere_woningen_CBS_2017_buurt.fmw) die uitgevoerd is om de dataset te op te vragen en weg te schrijven naar een file geodatabase.



