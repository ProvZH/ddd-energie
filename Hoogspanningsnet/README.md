
# Hoogspanningsnet

Gegevens van het hoogspanningsnet (masten, terreinen, knooppunten, verbindingen en stations) van de website http://www.hoogspanningsnet.com binnen de provincie Zuid-Holland. De dataset wordt actueel gehouden door een groep vrijwilligers.

**Jaar:** Actueel

**Dekking:** Zuid-Holland

**Projectie:** Amersfoort RD New EPSG:28992

**Bron Url:** [HoogspanningsNet Netkaart](https://webkaart.hoogspanningsnet.com/index2.php#6/52.000/5.000)

**Licentie:** CC BY-NC-ND 4.0

![](voorbeeld_hoogspanningsnet.png)

# Layers

De dataset bevat de volgende lagen:
* Hoogspanningsnet_masten
* Hoogspanningsnet_terreinen
* Hoogspanningsnet_knooppunten
* Hoogspanningsnet_verbindingen
* Hoogspanningsnet_stations

## Attributen

Hoogspanningsnet_masten:

| Attribuut          | Voorbeeld | Beschrijving | 
|----------         |-----------|--------------|
|Hoofdtype |Vakwerkmast| Hoofdtype |
|ID        |m775| Uniek identificatienummer |
|Beheerder|TenneT|Beheerder|
|Benutting|2x 380kV|Benutting|
|Bouwwijze|Vakwerkmast|Bouwwijze|
|In_dienst|1974 - heden| In dienst|
|Land|Nederland|Land|
|Mastfunctie|Steunmast|Mastfunctie|
|Masthoogte|50.3 meter|Masthoogte|
|Mastmodel|Donaumast|Mastmodel|
|Mastnummer|CST-KIJ-380-10|Mastnummer|
|Naam|CST-KIJ-380-10|Naam|
|Spanning|380.0|Spanning (kV)|
|Subtype|DO|Subtype|
|Verbinding|Crayestein - Krimpen|Verbinding|
|Opmerkingen||Opmerkingen|
|Foto|https://www.hoogspanningsforum.com/download/file.php?id=22347|Hyperlink naar foto|
|Circuits|380 kV Krimpen - Dordrecht (wit), 380 kV Krimpen - Dordrecht (zwart)|Circuits|

Hoogspanningsnet_terreinen:

| Attribuut          | Voorbeeld | Beschrijving | 
|----------         |-----------|--------------|
|Hoofdtype |Station| Hoofdtype |
|ID        |t652| Uniek identificatienummer |
|Aantal_velden|1xBipole Converter| Aantal velden|
|Bedrijfsspanning|450 kV|Bedrijfsspanning (kV)|
|Beheerder|TenneT|Beheerder|
|Beheerdercode|TWG150|Beheerdercode|
|Beheerdernaam|Theemsweg 150|Beheerdernaam|
|Constructiewijze|Station|Constructiewijze|
|Frequentie|50,0 Hz|Frequentie (Hz)|
|Hoogste_spanning|170 kV|Hoogste spanning (kV)|
|In_dienst|1999 - heden| In dienst|
|Land|Nederland|Land|
|Naam|Theemsweg|Naam|
|Railcapaciteit|1600 A|Railcapaciteit|
|Railconfiguratie|GIS|Railconfiguratie|
|Spanning|150.0|Spanning (kV)|
|Systeem|AC - Driefasen|Systeem|
|Opmerkingen||Opmerkingen|
|Foto|https://www.hoogspanningsforum.com/download/file.php?id=16587|Hyperlink naar foto|

Hoogspanningsnet_knooppunten:

| Attribuut          | Voorbeeld | Beschrijving | 
|----------         |-----------|--------------|
|ID        |k1592| Uniek identificatienummer |
|Beheerder|TenneT|Beheerder|
|IconPNG|https://webkaart.hoogspanningsnet.com/files/node-150.png|Hyperlink naar plaatje pictogram|
|In_dienst|2008 - heden|In dienst|
|Land|Nederland|Land|
|Naam|Andoorn|Naam|
|Netsituatie||Netsituatie|
|Spanning|150 kV|Spanning (kV)|
|Foto|https://www.hoogspanningsforum.com/download/file.php?id=17885|Hyperlink naar foto|
|Opmerkingen||Opmerkingen|

Hoogspanningsnet_verbindingen:

| Attribuut          | Voorbeeld | Beschrijving | 
|----------         |-----------|--------------|
|Hoofdtype |Kabel| Hoofdtype |
|ID        |v19497| Uniek identificatienummer |
|Bedrijfsspanning|0 kV|Bedrijfspanning (kv)|
|Beheerder|Stedin|Beheerder|
|Beheerdercode||Beheerdercode|
|Beheerdernummer||Beheerdernummer|
|Constructiewijze|Grondkabel|Constructiewijze|
|Deelnet|Goeree Overflakkee|Deelnet|
|Frequentie|50,0 Hz|Frequentie (Hz)|
|Hoogste_spanning|170 kV| Hoogste spanning (kV)|
|In_dienst|1966 - heden| In dienst|
|Land |Nederland| Land|
|Lengte |0,16 km| Lengte (km)|
|Naam|13 kV Stellendam-WP Roxennissepolderkabel (1)|Naam|
|Spanning|0.0|Spanning (kV)|
|Systeem|AC - Driefasen|Systeem|
|Transportcapaciteit|300 MVA|Transportcapaciteit (MVA)|
|Opmerkingen||Opmerkingen|
|Foto|https://www.hoogspanningsforum.com/download/file.php?id=9832|Hyperlink naar foto|

Hoogspanningsnet_stations:

| Attribuut          | Voorbeeld | Beschrijving | 
|----------         |-----------|--------------|
|Hoofdtype |Station| Hoofdtype |
|ID        |s6136| Uniek identificatienummer |
|Afkorting|WL|Afkorting|
|Beheerder_primair |TenneT| Primaire beheerder|
|Beheerder_secundair|TenneT| Secundaire beheerder|
|In_dienst |2010 - heden| In dienst|
|Land|Nederland|Land|
|Naam|Westerlee|Naam|
|Spanning|380.0|Spanning (kV)|
|Spanningen|380-150 kV|Spanningen|
|Type|Koppelstation|Type|
|Opmerkingen||Opmerkingen|
|Foto|https://www.hoogspanningsforum.com/download/file.php?id=12861|Hyperlink naar foto|

## Dataset in PI sandbox

De lagen in de dataset zijn als feature classes terug te vinden in de PI sandbox database.    

Deze repo bevat ook de [FME workspace](hoogspanningsnet.com2fgdb.fmw) die uitgevoerd is om de dataset klaar te zetten voor de PI sandbox.

## Dataset in Dataloket

De lagen in de dataset zijn als CSV-bestanden terug te vinden in het Dataloket.     

Deze repo bevat ook de [FME workspace](hoogspanningsnet.com2dataloket.fmw) die uitgevoerd is om de dataset te uploaden naar het Dataloket.

