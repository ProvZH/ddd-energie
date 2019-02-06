
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
|objectid_1	 | 1  | Uniek identificatienummer |
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
|co2noodzak		 | nee | Met CO₂ noodzakelijk wordt bedoeld dat er kosten gemaakt worden om CO₂ in de kas te krijgen. Dit aanvullend op het in bijna alle gevallen aanwezige standaard CO₂ leidingennet in de kas.  |
|co2bron		 |  |  |
|wkk		 |  |  |
|wkk_type		 |  |  |
|wkkvermkw		 |  |  |
|rgr		 |  |  |
|warmbuiten		 |  |  |
|bronwarmbu		 |  |  |
|geothermie		 |  |  |
|warmtebron		 |  |  |
|koudebron		 |  |  |
|buffer		 |  |  |
|typebuffer		 |  |  |
|vermbuff		 |  |  |
|dockshelt		 |  |  |
|scherm		 |  |  |
|f_schermen		 |  |  |
|typescherm		 |  |  |
|zonnepan		 |  |  |
|windmolen		 |  |  |
|watbassin		 |  |  |
|water_tank		 |  |  |
|arbeidsint		 |  |  |
|seizoen		 |  |  |
|hnt		 |  |  |
|enercode		 |  |  |
|enerwarm		 |  |  |
|opmenergie		 |  |  |
|opmerking		 |  |  |
|deelgebied		 |  |  |
|registrati		 |  |  |
|straat		 |  |  |
|kern		 |  |  |
|bagid		 |  |  |
|poothoogt1		 |  |  |
|oppervlakt		 |  |  |
|objectid		 |  |  |
|identifica		 |  |  |
|bouwjaar		 |  |  |
|status		 |  |  |
|shape_leng		 |  |  |
|k_id		 |  |  |
|plantsoort		 |  |  |
|teeltc		 |  |  |
|teeltd		 |  |  |
|wateropslg		 |  |  |
|ol0wl1		 |  |  |
|postcode		 |  |  |
|pc6		 |  |  |
|aantal_mul		 |  |  |
|aantal_adr		 |  |  |
|id		 |  |  |
|code		 |  |  |
|gemeentena		 |  |  |
|shape_le_1	 |  |  |
|shape_area		 |  |  |
|geometry		 |  |  |
|centroid		 |  |  |
|lat		 |  |  |
|lon	 |  |  |

## Feature class in PI sandbox

De dataset is als feature class `Schattingen_glastuinbouw_Oostland_punten` en `Schattingen_glastuinbouw_Oostland_vlakken` terug te vinden in de PI sandbox database. De eerste bevat punten (centroïden), de tweede vlakken. De attribuutinformatie is hetzelfde in beide feature classes.

Deze repo bevat ook de [FME workspace](schattingen-glastuinbouw-oostland-naar-fgdb.fmw) die uitgevoerd is om de dataset klaar te zetten voor de PI sandbox.

# Dataloket
De dataset is [via deze link](https://xe5f95b82989a4b549abc16a.azurewebsites.net/documenten/10000002315216) ook als Excel-bestand te downloaden in het Dataloket.
