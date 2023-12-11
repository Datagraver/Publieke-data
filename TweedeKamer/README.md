# Data zittingsperioden alle Tweede Kamerleden

Bijgaande bestanden bevatten alle informatie over de kamerleden en hun zittingsperioden sinds 1815.
Bestand personen heeft een persoon_id als sleutel. Deze sleutel geeft aan in welk jaar en maand een persoon voor het eerst in de Tweede Kamer kwam (plus 3 cijfers voor een volgnummer binnen die maand).
Met het persoon_id kan in het bestand met perioden de overige gegevens van het Tweede Kamerlid gekoppeld worden.
Vanuit perioden zit er verwijzing naar het bestand met fracties (op fractienaam). 
Let op, een persoon kan in verschillende perioden voor verschillende fracties voorkomen. De oude periode krijgt dan een einddatum en de volgende periode met de nieuwe fractie een begindatum.

Alle datums zijn uit elkaar gehaald in jaar/maand/dag. Dit is mede vanwege het gebruik in bijvoorbeeld Excel (ondersteunt geen datums van voor 1900).

Het zijn TSV bestanden (kolommen gescheiden door tabs) in UTF-8.

Voor het verzamelen van de data hebben we naast de site van de [Tweede Kamer](https://www.tweedekamer.nl/kamerleden_en_commissies/alle_kamerleden) zelf en het [open dataportaal van de Tweede Kamer](https://opendata.tweedekamer.nl/) ook gebruik gemaakt van [Wikipedia](https://nl.wikipedia.org/wiki/Lijst_van_Tweede_Kamerleden_2021-2023) en [Parlement.com](https://www.parlement.com/)https://www.parlement.com/.
