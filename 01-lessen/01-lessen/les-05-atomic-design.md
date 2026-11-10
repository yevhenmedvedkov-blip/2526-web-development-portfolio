# Les 5 – Component Based Development

## 1. Project: MapstAr

Voor deze opdracht heb ik gekozen om mijn eigen project, **MapstAr**, te gebruiken. MapstAr is een reisplatform waarop gebruikers uitstappen, activiteiten en andere reisdiensten kunnen ontdekken en boeken.

In plaats van een externe website te analyseren, heb ik gebruikgemaakt van de component library die ik voor MapstAr heb ontwikkeld. Tijdens het ontwerpproces heb ik in Figma een herbruikbaar designsysteem opgebouwd, gebaseerd op de principes van Component Based Development en Atomic Design.

Het doel was om een consistente visuele stijl te creëren en een gestructureerde verzameling van herbruikbare interface-elementen op te bouwen.

## 2. Design System en Styleguide

De visuele basis van MapstAr is opgebouwd aan de hand van Figma Styles.

Het designsysteem bestaat uit:

- **Kleuren:** vastgelegde kleurstijlen voor primaire acties, secundaire elementen, achtergronden, tekst en verschillende interfacestaten.
- **Typografie:** gedeelde tekststijlen en een duidelijke teksthiërarchie voor titels, lopende tekst, labels en andere interface-elementen.
- **Knoppen:** primaire en secundaire knoppen, met verschillende kleuren, formaten en statussen.
- **Formulierelementen:** dropdowns, tekstvelden, zoekvelden, tags, filters en datumselectoren.
- **Interactieve elementen:** schakelaars, tellers, iconen en andere interactieve bedieningselementen.
- **Complexe componenten:** boekingsformulieren, kaarten, kalenders, navigatie- en footerelementen.

Deze gedeelde stijlen en componenten zorgen ervoor dat de visuele consistentie binnen het volledige product behouden blijft.

## 3. Atomic Design-structuur

Ik heb de interface opgebouwd volgens de vijf niveaus van Atomic Design.

### Atoms

De kleinste herbruikbare interface-elementen:

- Knoppen
- Iconen
- Invoervelden
- Labels
- Tags
- Typografische stijlen
- Kleurstijlen

### Molecules

Groepen van atoms die samen een specifieke functie uitvoeren:

- Zoekveld met een zoekknop
- Dropdown met een label en icoon
- Groepen van invoervelden
- Filterbedieningselementen
- Kleine interactieve bedieningselementen

### Organisms

Grotere interfaceonderdelen die bestaan uit meerdere atoms en molecules:

- Header en navigatie
- Boekingsformulier
- Kaarten met uitstappen en lijsten met kaarten
- Zoek- en filtersecties
- Footer
- Kalenderinterface

### Templates

Herbruikbare paginastructuren die de lay-out en positionering van de verschillende interfaceonderdelen bepalen, zonder afhankelijk te zijn van specifieke inhoud.

### Pages

De uiteindelijke schermen van het product, waarin de templates worden ingevuld met echte inhoud, afbeeldingen, bestemmingen en boekingsinformatie.

## 4. Herbruikbaarheid en Component Variants

Een van de belangrijkste principes die ik heb toegepast, is herbruikbaarheid.

In plaats van voor elke situatie afzonderlijke elementen te maken, heb ik gedeelde componenten ontwikkeld met verschillende varianten.

Zo hebben knoppen bijvoorbeeld primary-, secondary-, success-, warning- en disabled-states. Ook kaarten en formulierelementen hebben verschillende varianten, afhankelijk van hun functie.

Deze aanpak maakt het eenvoudiger om het designsysteem te onderhouden. Wanneer een gedeelde component aangepast moet worden, kan die wijziging op een consistente manier doorheen het volledige product worden toegepast.

## 5. Conclusie en Reflectie

Het werken aan MapstAr heeft me geholpen om het belang van component-based design binnen grotere digitale producten beter te begrijpen.

Atomic Design bood een duidelijke manier om complexe interfaces op te splitsen in kleinere, herbruikbare elementen. Hierdoor werd ook de relatie tussen afzonderlijke UI-elementen en volledige paginastructuren duidelijker.

Ik heb geleerd dat een designsysteem niet zomaar een verzameling visuele stijlen is. Het is een gestructureerd systeem dat zorgt voor meer consistentie, schaalbaarheid en een betere samenwerking tussen design en development.
