
# Schattingen glastuinbouw Oostland

De dataset is een globale ‘foto’ van de huidige glastuinbouw bedrijven in het Oostland. De dataset is gebaseerd op visuele waarnemingen gecombineerd met openbaar beschikbare informatie. De visuele waarnemingen zijn gedaan op basis van persoonlijke expertise op het gebied van de glastuinbouw.  

**Achtergrondinformatie:**

De dataset is tot stand gekomen in opdracht van de projectgroep Oostland. Deze projectgroep is een samenwerking van vier gemeenten (Lansingerland, Pijnacker-Nootdorp, Waddinxveen en Zuidplas) en de provincie Zuid-Holland. Het doel is om voor het Oostlanddeel van de Greenport West-Holland te komen tot een Werkboek Oostland. In dit werkboek worden in een achttal ambities de kansen voor het glastuinbouwcluster beschreven. De acht ambities zijn gerelateerd aan de volgende onderwerpen: 
* modernisering en herstructurering, 
* glas en verstening, 
* planologische ruimte scheppen, 
* mobiliteit, 
* duurzame waterhuishouding/waterzuivering, 
* energietransitie, 
* het bevorderen van innovatie in het Oostland. 
De uitwerking van deze ambities biedt handvatten om de ruimtelijk-economische structuur te versterken.  

**Jaar:** Onbekend

**Dekking:** Oostland

**Projectie:** Amersfoort RD New EPSG:28992

**Eigenaar van de dataset:**  provincie Zuid-Holland

## Attributen

Het bestand bevat de volgende attributen:

| Attribuut          | Voorbeeld | Beschrijving | 
|----------         |-----------|--------------|
|objectid	 | 1  | Uniek identificatienummer |
|straatnaam	 |  | Straatnaam |
|huisnummer		 |  | Huisnummer |
|bedr_naam	 |  | Bedrijfsnaam |	
|gebruikkas		 | Teelt  | Gebruik kas |
|teeltsoort		 | snijbloemen | Teeltsoort |
|teelt		 | pioenrozen | Teelt |
|ondergrtlt		 | grondgebonden | Ondergrond teelt |
|kastype_1		 | venlo | Kastype |
|poothgt1		 | 3 | Poothoogte (meters); poothoogte is een tuinbouwterm die de hoogte van de kas weergeeft |
|kastype_2		 | venlo | Kastype; alleen gevuld als er meerdere kastypes voorkomen |
|poothgt2		 | 3 | Poothoogte; alleen gevuld als er meerdere poothoogtes voorkomen |
|leeftydkas		 | 1984 | Bouwjaar van de kas |
|verstening		 | ja | Verstening binnen oppervlakte van het BAG-object |
|oppversten		 | 280 | Oppervlakte verstening (m2) |
|typversten		 | bedrijfsgebouw | Type verstening |
|besgrvers		 | standaard functies | Beschrijving van welke functies het versteend gebouw heeft, bij de meeste bedrijven gaat dit om de standaard functies |
|opmkas_sch		 | buiten scherm aanwezig | Opmerkingen schuur |
|belichting		 | nee | Belichting |
|stomen		 | nee |Verwachting op basis van teelt en teeltondergrond of er gestoomd wordt om de grond te reinigen |
|co2noodzak		 | nee | Kosten om CO₂ in de kas te krijgen, bovenop het in bijna alle gevallen aanwezige standaard CO₂ leidingennet in de kas  |
|co2bron		 | ja | CO₂ van buitenaf aanwezig |
|wkk		 | zuivere CO2 uit tank | WKK aanwezig op het bedrijf |
|wkk_type		 | Deutz  MWM | Merk van de WKK |
|wkkvermkw		 | onbekend | Elektrisch vermogen van de WKK (kW/uur) |
|rgr		 | onbekend | Rookgasreiniger |
|warmbuiten		 | nee | Warmte buitenaf |
|bronwarmbu		 | nvt | Bron warmte buitenaf |
|geothermie		 | nee | Warmtewinning vanuit geothermie |
|warmtebron		 | geen | Warmtebronnen anders dan ketel, WKK of levering van buitenaf |
|koudebron		 | nee | Koude bron |
|buffer		 | ja | Grote tank voor warmteopslag |
|typebuffer		 | staand | Type buffer |
|vermbuff		 | 800 | Buffervolume (m3) |
|dockshelt		 | nee | Aanwezigheid dockshelter (laadruimte in het bedrijf waar de vrachtwagen vloer gelijk is aan je bedrijfsvloer) |
|scherm		 | ja | Aanwezigheid scherm met als taak om warmte en/of licht binnen en/of buiten te houden |
|f_schermen		 | 1 | Aantal schermen |
|typescherm		 | energie | Type schermen |
|zonnepan		 | nee | Zonnepanelen |
|windmolen		 | nee | Windmolen |
|watbassin		 | ja | Waterbassin |
|water_tank		 | nee | Watertanks |
|arbeidsint		 | gemiddelde | Arbeidsintensitiviteit; grove indicatie van het aantal mensen dat gemiddeld per jaar per hectare werkzaam irbeidsintensitiviteit; minder dan 2 mensen is laag, tussen 2 en 5 mensen is gemiddeld en meer dan 5 mensen is hoog  |
|seizoen		 | nee | Aanduiding of de kas een deel van het jaar leeg staat |
|hnt		 | onbekend |  |
|enercode		 | 5 | warmtebehoefte: 1 = geen energie vraag, 2 = 0 - 5 m3 gas per m2 per jaar, 3 = 5 – 15 m3 gas per m2 per jaar, 4 = 15-25 m3 per m2 per jaar, 5 = 25-35 m3 per m2 per jaar, 6 = > 35 m3 per m2 per jaar,  0 = geen informatie aanwezig / geen tuinbouw bedrijf |
|enerwarm		 |  |  |
|opmenergie		 |  | Opmerkingen over de energiesituatie|
|opmerking		 |  | Opmerkingen over de bedrijfssituatie |
|deelgebied		 | 2 |  |
|registrati		 |  |  Attribuut is altijd leeg  |
|straat		 |  |  Attribuut is altijd leeg  |
|kern		 |  |  Attribuut is altijd leeg  |
|bagid		 |  |  Attribuut is altijd leeg  |
|poothoogt1		 |  |  Attribuut is altijd leeg  |
|oppervlakt		 |  | Oppervlakte van de BAG locatie (m2); in de praktijk zijn dit oppervlaktes van bedrijfslocatie |
|identifica		 |  | BAG-ID |
|bouwjaar		 | 1970 |  |
|status		 | Pand in gebruik |  |
|k_id		 | 8268 |  |
|plantsoort		 |  | Attribuut is altijd leeg |
|teeltc		 |  | Attribuut is altijd leeg |
|teeltd		 |  | Attribuut is altijd leeg |
|wateropslg		 |  | Attribuut is altijd leeg |
|ol0wl1		 | 0 | Waarde is altijd 0 |
|postcode		 |  | Postcode |
|pc6		 |  | Postcode |
|aantal_mul		 | 1 |  |
|aantal_adr		 | 43 |  |
|id		 | 116 |  |
|code		 | 1621 | Gemeentecode |
|gemeentena		 | Lansingerland | Gemeentenaam |
|lat		 |  | Latitude |
|lon	 |  | Longitude |

## Feature class in PI sandbox

De dataset is als feature class `Schattingen_glastuinbouw_Oostland_punten` en `Schattingen_glastuinbouw_Oostland_vlakken` terug te vinden in de PI sandbox database. De eerste bevat punten (centroïden), de tweede vlakken. De attribuutinformatie is hetzelfde in beide feature classes.

Deze repo bevat ook de [FME workspace](schattingen-glastuinbouw-oostland-naar-fgdb.fmw) die uitgevoerd is om de dataset klaar te zetten voor de PI sandbox.

# Dataloket
De dataset is [via deze link](https://xe5f95b82989a4b549abc16a.azurewebsites.net/documenten/10000002315216) ook als Excel-bestand te downloaden in het Dataloket.
