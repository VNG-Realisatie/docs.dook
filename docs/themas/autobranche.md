---
layout: page-with-side-nav
title: Data Ondermijning Op de Kaart (DOOK)
---

# Autobranche

De [Datavoorziening Onregelmatigheden Op de Kaart](https://dook.vng.nl) (DOOK) bevat meerdere thema’s waaronder het thema ‘autobranche’. Dit thema is ontworpen om gemeenten te helpen met het opstellen van een informatiebeeld voor de aanpak van ondermijnende criminaliteit in de autobranche. DOOK sluit daarbij aan op de methodiek zoals beschreven in de [Handreiking Informatiebeeld Autobranche](https://kennisplatformondermijning.nl/files/view/52f04179-a7ce-438f-99e8-ef8111896e71/handreiking-informatiebeeld-autobranche.pdf) van Taskforce RIEC en Avans Hogeschool. DOOK is ontworpen om eenvoudig een basisdataset te kunnen exporteren.

Het thema autobranche is opgebouwd uit kaartlagen die verschillende bronnen inzichtelijk maken. De kaartlagen en bijbehorende bronnen worden hieronder toegelicht.

## Bestemmingsplan
De kaartlaag met bestemmingsplannen maakt de bestemming van gebouwen in de gemeente inzichtelijk. De kaartlagen zijn een directe kopie van de bron: [Ruimtelijkeplannen.nl](https://www.ruimtelijkeplannen.nl/home). Iedere locatie heeft een enkelbestemming en kan meerdere dubbelbestemmingen hebben. In de enkelbestemming staat beschreven of er gebouwd mag worden en wat voor bebouwing dat mag zijn. De enkelbestemming beschrijft voor welke functie de grond bestemd is (bijvoorbeeld woningen of bedrijven).

## Adressen en gebouwen (BAG)
De kaartlagen met de [Basisregistratie Adressen en Gebouwen](https://bagviewer.kadaster.nl/lvbag/bag-viewer/?zoomlevel=1) (BAG) bevatten gemeentelijke basisgegevens van alle adressen en gebouwen in een gemeente. Vier kaarten tonen de adressen (verblijfsobjecten, ligplaatsen en standplaatsen), oppervlakte, functie en bouwjaar. De functie geeft een indicatie van het woninggebruik in een object. We onderscheiden 3 categorieën: 

- objecten met alleen een woonfunctie, 
- objecten met gedeeltelijke woonfunctie, 
- objecten zonder woonfunctie.

De BAG data in DOOK wordt jaarlijks bijgewerkt. Bron: [BAG Viewer](https://bagviewer.kadaster.nl/lvbag/bag-viewer/?zoomlevel=1)

## Handelsregister (KVK)
In deze kaartlaag is de informatie uit het [Handelsregister](https://handelsregister.nl) te raadplegen volgens de [Standaard Bedrijfsindeling](https://www.cbs.nl/nl-nl/onze-diensten/methoden/classificaties/activiteiten/standaard-bedrijfsindeling--sbi--) (SBI) van het [CBS](https://www.cbs.nl/). SBI is een hiërarchische indeling van economische activiteiten.

De Handelsregister data geeft inzicht in de aanwezigheid en spreiding van branches in de gemeente. Met behulp van deze kaart heeft de gemeente overzicht welk type bedrijven waar zijn gevestigd.

De handelsregisterdata in [DOOK](https://dook.vng.nl) wordt dagelijks bijgewerkt via de KVK-API.

## Informatiebeeld autobranche
De kaartlaag voor het opstellen een informatiebeeld voor de autobranche bevat meerdere bronnen.

‘Ondernemingen in de autobranche’ geeft een filter weer op SBI-codes 45 en 77. De exacte lijst met SBI codes is te vinden in de bijlage van de [Handreiking Informatiebeeld Autobranche](https://kennisplatformondermijning.nl/files/view/52f04179-a7ce-438f-99e8-ef8111896e71/handreiking-informatiebeeld-autobranche.pdf) voor gemeenten.

### ‘RDW met RDW erkenning’ 
*RDW met RDW erkenning* geeft bedrijven weer die geregistreerd zijn bij de [RDW](https://www.rdw.nl/zakelijk). Per bedrijf is inzichtelijke welke erkenningen het bedrijf heeft. De Match score geeft aan hoe nauwkeurig de koppeling is met de BAG, waar 0 fouten een 100% match betekent met een adres in de BAG. De RDW gegevens worden twee keer per week bijgewerkt. Bron: [Open Data \| RDW](https://opendata.rdw.nl/)

### Ondernemingen met BOVAG-lidmaatschap
*Ondernemingen met BOVAG-lidmaatschap* geeft een overzicht van bedrijven met een [BOVAG](https://www.bovag.nl/) lidmaatschap, op adres gekoppeld aan verblijfsobjecten en staanplaatsen in de BAG. De Match score geeft aan hoe nauwkeurig de koppeling is met de BAG, waar 0 fouten een 100% match betekend met een adres in de BAG. De BOVAG gegevens worden twee keer per week bijgewerkt. Bron: [BOVAG - Zoek BOVAG bedrijf](https://www.bovag.nl/zoek-bovag-bedrijf)

### Download basisdataset ten behoeve van het informatiebeeld
*Download basisdataset ten behoeve van het informatiebeeld* combineert de eerdergenoemde bronnen: BAG, Handelsregister (KVK), RDW erkenning en BOVAG lidmaatschap. Hier kunt een basisdataset exporteren zoals deze is beschreven in de [Handreiking Informatiebeeld Autobranche](https://kennisplatformondermijning.nl/files/view/52f04179-a7ce-438f-99e8-ef8111896e71/handreiking-informatiebeeld-autobranche.pdf).
