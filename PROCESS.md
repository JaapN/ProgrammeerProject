Logboek, Jaap Nieuwenhuizen

###### Maandag (week 1)
- Proposal bedenken en bespreken.

###### Dinsdag (week 1)
- Proposal was goed gekeurd, maar ik bleef ontevreden. Ook naar aanleiding van de feedbackronden besloten nieuwe data te gaan zoeken.

###### Woensdag (week 1)
- Van onderwerp veranderd.
- Proposal en designdocument geschreven/aangepast.
- De data verzameld, ingeladen en bewerkt.

###### Vrijdag (week 1)
- Overnemen en bewerken van de code van de laatste opdracht voor Data Processing.

###### Maandag (week 2)
- Maken van scatterplots.
- Verbeteren interactiviteit barcharts en zichtbaar maken van barcharts.

###### Dinsdag (week 2)
Meerdere problemen die nog verholpen dienen te worden:
- Implementeren van een mogelijkheid om data/variabelen aan de functies die de plots construeren mee te geven. Dit zal er echter toe leiden dat de graphs/plots pas geconstrueerd worden als de functie opgeroepen is.
- Layout verbeterd. Dropdown menu’s toegevoegd.
- Regressielijnen toegevoegd.

###### Woensdag (week 2)
Meerdere problemen die nog verholpen dienen te worden:
- Knoppen blijven achter de maps.
- Regressielijnen worden niet juist weergegeven.
- Achtergrondkleur maps.
- Grouped barchart gemiddelden.
- Mogelijkheid tot imputeren/inserteren van een variabele voor de x en y-as (in plaats van hardcoding van functies).

###### Donderdag (week 2)
- 13:00 tot 15:00, de barchart vervangen met een grouped barchart. De andere bar geeft het gemiddelde van het respectievelijke field aan. Was verrassend lastig. Best blij dat het gelukt is.
- Automatiseren van scatterplotsfuncties: geef variabelen mee om de scatterplot te creëren.

To-do:
- Ditzelfde wil ik eventueel ook voor de maps nog doen.
- Misschien ook selecteren van x en y variabelen afzonderlijk aanbieden.
- Betere tips voor de scatterplots.
- Maak een d3-loop om voor elk land het percentage van een bepaald field te zoeken en van datzelfde land de waarde van de geselecteerde variabele te nemen.

- Automatiseren van de maps.
- Code enigszins opgeschoond (vooral tussen menu en plots).
- Bugs die ontstonden opgelost.
- Gewerkt tot 20:30.

###### Vrijdag (week 2)
- Gepresenteerd. Fill-colours voor de kaarten van paars naar rood veranderd.

###### Maandag (week 3)
- De data voor Polen en Nederland geëxtrapoleerd aan de hand van relatief veel bekende gegevens en patronen. De patronen van andere complete landen. Totaal hangt met name samen met bachelor’s percentage.
- Barchart verbeterd (titel toegevoegd). Ik poogde ook de css-kleuring aan te passen, maar dit slaagde niet. Geeft niet, want het is niet een noodzakelijke toevoeging (en wellicht zelfs een verslechtering, achteraf gezien).
- HTML tekst toegevoegd.
- Fill-colours voor de wereldkaarten aangepast van rood naar groen. En voor geen data van #808080 naar transparent (#eeeeee in dit geval).

###### Dinsdag (week 3)
- Nieuwe functie toegevoegd (plotVariablesMultiData).
- Tooltip en menu geüpdate (landen) + regressielijn anders gekleurd.
- Aanpassen van de lengte voor het berekenen van de gemiddelde percentages voor fields over alle landen voor de grouped barcharts. Dit was noodzakelijk en is logischer.
- Nieuwe map.
- Nieuw script voor gemiddelden barchart.
- OECD – total verwijderd. (Was ik van plan, uiteindelijk toch niet gedaan, bleek lang te duren handmatig en was helemaal niet noodzakelijk meer).
- Menu geüpdate (jQuery functies vervangen).

Todo:
- Legenda voor de kaarten.
- Scatterplot tooltips verbeteren.
- Code opschonen voor bijvoorbeeld het menu. Heeft geen prioriteit.
- Automatiseren van selectie voor variabelen en meegeven aan functies. Belangrijk, want veel combinaties mogelijk.
- Opslaan van gemiddelden voor de barchart in een afzonderlijke script.

###### Woensdag (week 3)
- Layout aangepast (HTML en CSS).
- Scatterplots aangepast.
- Wereldkaarten toegevoegd.
- Series voor de kleuren gefikst. De series werden niet goed gesorteerd, want het herkende geen floatwaarden.
- Code aan het menu toegevoegd (lelijke data-analyse).
- Een selectmenu toegevoegd in een nieuwe dropdown, om de x- en y-variabelen mee te kunnen selecteren.

- De functies aangepast en uiteindelijk de dropdown+selectmenu scatterplots geïmplementeerd! Het werkt nu! MVP behaald.

To-do:
- Scatterplot tooltips verbeteren.

###### Donderdag (week 3)
- HTML tekst aangepast.
- Kleuren aangepast.
- Graphs verbeterd. Selectmenu voor graphs geïmplementeerd. Functie van gemaakt. Variabelenaam veranderd in alle documenten.
- Menu aangepast (aantal lines verwijderd). Data-analyse/objectcreatie voor de graphs en graphMulti toegevoegd.
- Variabelennamen aangepast.
- Legenda labels aangepast.
- Inspringing/Indentation van de code aangepast.

###### Maandag (week 4)
To-do:
- Dropdownknoppen aanpassen om te tonen wat voor visualisatie weergegeven wordt.
- Selectmenu’s (m.n. van de kaarten) aanpassen.
- Tooltips aanpassen.
- Misschien de scatterdots kleiner maken?
- Regressielijn aanpassen. Misschien ook de assen aanpassen.
- Verslag misschien al?

- Dropdownknoppen aanpassen aan selectie.
- Menulocatie aangepast. Menu’s css aangepast.
- Datamaps select menu aangepast. Ook de manier van selecteren en doorgeven aan de functie aangepast.
- Marges toegevoegd aan de assen voor de scatterplots.
- If-loops toegevoegd om de regressielijn af te kappen bij het snijden met een as.
- Gepoogd een betere tooltip toe te voegen. Nog steeds niet gelukt.

###### Dinsdag (week 4)
- De breedte en titel aangepast in de css.
- Voor elk land/datapunt kan nu een barchart gemaakt worden in de scatterplots en graphs.
- Legenda aangepast.
- CSS aangepast van visualisaties en HTML.
- Tooltip maps aangepast.
- Margin en locatie van visualisaties aangepast.
- Tooltips enigszins aangepast.
- Regressielijn achter de datapunten geplaatst.
- Bijna de hele dag gepoogd de interactiviteit aan te passen. Veel code geschreven, maar het bleek niet te werken. Jammer.

###### Woensdag (week 4)
- De oude d3 tooltip gebruikt voor de scatterplot, zonder interactiviteit. Enigszins zonde, maar ik denk dat dit een logische designkeuze is.
- Barcharts toegevoegd die onclick werken bij de plots en nog steeds bij hover voor de graphs.
- Probleem is echter dat ik bij het aanmaken een nieuwe barchart bij dezelfde visualisatie nog steeds oude tooltip divs blijf behouden. Deze kan ik nu niet meer verwijderen. Maar dit is niet erg; ze worden wel verwijderd als een andere visualisatie gekozen wordt.
- Alle libraries/bronnen toegevoegd.
- Code opgeschoond.
- Verslag begonnen.

###### Donderdag (week 4)
- Verslag schrijven.
