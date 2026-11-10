# Les 04 – Responsive Development

## 1. Samenvatting

Tijdens deze les hebben we geleerd hoe we websites responsive kunnen maken voor verschillende schermformaten en apparaten.

De belangrijkste onderwerpen waren:

- Flexbox en CSS Grid.
- Mobile First development.
- Breakpoints en Media Queries.
- Container Queries.
- Responsive gedrag op basis van verschillende media features.
- Relatieve CSS-eenheden zoals rem, %, vw, vh, dvh en cqi.

Een belangrijk inzicht is dat responsive development niet alleen betekent dat een website kleiner wordt op een mobiel scherm. De volledige layout en gebruikerservaring moeten zich aanpassen aan de beschikbare ruimte.

### Flexbox en Grid

We hebben geleerd wanneer we Flexbox en Grid gebruiken.

Flexbox is vooral geschikt voor elementen die in één rij of kolom worden geplaatst, zoals navigatie, knoppen en tags.

CSS Grid is geschikt voor complexere layouts met meerdere rijen en kolommen, bijvoorbeeld projectoverzichten en paginalayouts.

Met eigenschappen zoals `flex-wrap`, `auto-fit` en `minmax()` kunnen layouts zich automatisch aanpassen zonder dat er altijd Media Queries nodig zijn.

### Mobile First

Bij Mobile First development beginnen we met de kleinste schermen.

De mobiele layout vormt de basis. Wanneer er meer ruimte beschikbaar is, voegen we met Media Queries extra elementen of complexere layouts toe.

Dit zorgt voor een eenvoudigere CSS-structuur en minder onnodige overrides.

### Breakpoints en Media Queries

We hebben geleerd dat breakpoints gekozen moeten worden op basis van de content en niet alleen op basis van standaard schermformaten.

Een breakpoint is nodig wanneer elementen niet meer goed naast elkaar passen, tekst moeilijk leesbaar wordt of de layout zijn balans verliest.

### Container Queries

Container Queries maken het mogelijk om een component aan te passen op basis van de beschikbare ruimte van zijn eigen container.

Dit is bijvoorbeeld handig voor cards die op verschillende plaatsen binnen dezelfde website worden gebruikt.

### Meer dan breedte

Responsive development gaat ook over andere eigenschappen van een apparaat en de voorkeuren van de gebruiker.

We hebben onder andere besproken:

- `prefers-color-scheme` voor dark mode.
- `prefers-reduced-motion` voor gebruikers die minder animaties willen.
- `hover` en `pointer` voor verschillende invoermethoden.
- Toegankelijkheid bij inzoomen en het gebruik van knoppen.

### CSS-eenheden

We hebben verschillende CSS-eenheden vergeleken:

- `px` voor vaste afmetingen.
- `rem` voor typografie en spacing.
- `%` voor relatieve afmetingen.
- `vw` en `vh` voor viewport-afhankelijke afmetingen.
- `dvh` voor de dynamische hoogte van het viewport.
- `cqi` voor afmetingen die afhankelijk zijn van een container.

Ook hebben we `clamp()` besproken om bijvoorbeeld typografie vloeiend te laten meegroeien tussen een minimum- en maximumwaarde.

## 2. Bronnen

- [MDN – Responsive Design](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design)
- [MDN – CSS Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout)
- [MDN – CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout)
- [MDN – Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries)
- [MDN – Container Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_containment/Container_queries)
- [Flexbox Froggy](https://flexboxfroggy.com/)
- [Grid Garden](https://cssgridgarden.com/)

## 3. Praktische opdracht – Responsive Portfolio Development

Voor deze opdracht heb ik mijn persoonlijke portfolio website als uitgangspunt genomen.

**Website:** https://www.medvedkov.design/

Het doel was om een consistente gebruikerservaring te creëren op verschillende apparaten, zonder de visuele identiteit van het ontwerp te verliezen.

### 1. Responsive Layout

Mijn portfolio is ontworpen voor verschillende schermformaten:

- Desktop: volledige layout met alle visuele elementen.
- Tablet: aangepaste compositie en afmetingen.
- Mobile: compactere layout met focus op leesbaarheid en navigatie.

De belangrijkste uitdaging was om de visuele hiërarchie en structuur van het originele ontwerp te behouden.

### 2. Responsive Navigation

De navigatie moet op kleinere schermen voldoende ruimte behouden en gemakkelijk toegankelijk blijven.

Daarom moet de structuur zich aanpassen aan de beschikbare breedte van het scherm.

### 3. Responsive Typography

De typografie speelt een belangrijke rol in de visuele identiteit van mijn portfolio.

Ik heb daarom aandacht besteed aan de verhoudingen tussen headings, bodytekst en andere tekstelementen op verschillende schermformaten.

### 4. Responsive Images en Project Cards

De projectafbeeldingen en mockups moeten zich aanpassen aan de beschikbare ruimte.

Het doel is om de afbeeldingen goed zichtbaar te houden zonder vervorming of onnodige horizontale scroll.

### 5. Interacties en Animaties

Mijn portfolio bevat verschillende animaties en interactieve elementen.

Bij responsive development is het belangrijk dat deze elementen ook op touchscreens goed werken en de navigatie niet hinderen.

## 4. Wat ik heb geleerd

Deze les heeft mij geholpen om responsive development beter te begrijpen vanuit zowel technisch als UX-perspectief.

Vooral het verschil tussen Media Queries en Container Queries vond ik interessant.

Ik begrijp nu beter dat niet iedere component afhankelijk hoeft te zijn van de breedte van het volledige scherm. Een component kan ook zelfstandig reageren op de ruimte die zijn eigen container beschikbaar heeft.

Daarnaast vond ik het principe van Mobile First belangrijk. Het helpt om eerst na te denken over de belangrijkste content en functionaliteit voordat een complexere desktoplayout wordt opgebouwd.

## 5. Zelfreflectie

Als designer besteed ik veel aandacht aan de visuele kwaliteit en compositie van een website.

Deze les heeft mij eraan herinnerd dat een goed desktopontwerp niet automatisch een goede mobiele ervaring betekent.

Bij mijn eigen portfolio wil ik daarom niet alleen kijken naar de technische aanpassing van elementen, maar ook naar de gebruikerservaring op kleinere schermen.

Een belangrijk aandachtspunt blijft het testen van verschillende schermformaten, interacties en toegankelijkheid.

## 6. Zelfevaluatie

**Zelfevaluatie: 4/5**

Ik heb ervaring met het ontwerpen en ontwikkelen van responsive websites en kan de belangrijkste principes toepassen in mijn eigen projecten.

Ik begrijp het verschil tussen Flexbox, Grid, Media Queries en Container Queries.

Ik wil mij verder verdiepen in geavanceerde CSS-layouts, relatieve eenheden en toegankelijkheid.

## 7. Verbeterpunten

- De mobiele en tabletversies van mijn portfolio verder controleren.
- Breakpoints testen op basis van de daadwerkelijke content.
- Controleren of er nergens horizontale scroll ontstaat.
- Responsive typografie en afbeeldingen optimaliseren.
- Interacties en animaties testen op touchscreens.
- Controleren of de website goed blijft werken bij ingezoomde weergave en reduced motion.
