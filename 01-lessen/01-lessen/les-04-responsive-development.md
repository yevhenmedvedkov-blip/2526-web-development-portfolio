### 3. Praktische opdracht – Responsive Portfolio Development

Voor deze opdracht heb ik mijn persoonlijke portfolio gebruikt als praktijkvoorbeeld.

**Website:** https://www.medvedkov.design/

Het doel was om een consistente gebruikerservaring te creëren op verschillende schermformaten, met behoud van de visuele identiteit van het oorspronkelijke ontwerp.

### 1. Responsive Layout

Voor de layout gebruik ik een combinatie van CSS Grid en Flexbox.

CSS Grid wordt gebruikt voor complexere structuren, zoals projectkaarten, expertise-secties en de contactsectie.

Flexbox wordt gebruikt voor navigatie, contentgroepen en componenten die zich flexibel moeten aanpassen.

### 2. Breakpoints en Media Queries

Ik gebruik verschillende breakpoints om de layout aan te passen aan de beschikbare schermruimte.

De belangrijkste breakpoints zijn:

- 1440px en groter: desktoplayout.
- 761px tot 1250px: aangepaste desktop- en tabletlayout.
- 760px en kleiner: mobiele layout.
- 374px en kleiner: extra optimalisatie voor kleine smartphones.

De breakpoints zijn gebaseerd op de compositie en de beschikbare ruimte voor de content.

### 3. Responsive Typography

Voor verschillende tekstgroottes gebruik ik onder andere de CSS-functie `clamp()`.

Hiermee kunnen headings vloeiend schalen tussen een minimale en maximale grootte.

Dit helpt om de typografische hiërarchie op verschillende schermformaten te behouden.

### 4. Responsive Images en Aspect Ratios

Afbeeldingen en projectmockups gebruiken `aspect-ratio` om hun verhoudingen te behouden wanneer de beschikbare breedte verandert.

Hierdoor blijven de visuele composities consistent op desktop, tablet en mobiel.

### 5. Responsive Animations

Een bijzonder onderdeel van mijn portfolio is de geanimeerde hero-sectie.

De animatie toont een visuele reis van Donetsk naar Antwerpen.

Voor kleinere schermen gebruik ik aangepaste afmetingen, positionering en aparte keyframes om de compositie geschikt te maken voor mobiele apparaten.

### 6. Accessibility en Reduced Motion

Ik gebruik `:focus-visible` om toetsenbordgebruikers visuele feedback te geven wanneer ze interactieve elementen selecteren.

Daarnaast gebruik ik `prefers-reduced-motion` om animaties en overgangen uit te schakelen voor gebruikers die minder beweging prefereren.

### 4. Wat ik heb geleerd

Door deze opdracht heb ik beter begrepen hoe verschillende CSS-technieken samenwerken om een responsive interface te creëren.

Ik gebruik Media Queries voor structurele veranderingen, Flexbox en Grid voor flexibele layouts en `clamp()` voor vloeiende typografie.

Ook heb ik geleerd dat responsive development niet alleen over schermbreedtes gaat. Toegankelijkheid, interacties en animaties spelen eveneens een belangrijke rol.

### 5. Zelfreflectie

Bij het ontwikkelen van mijn portfolio heb ik gemerkt dat sommige visuele elementen meer aandacht nodig hebben bij kleinere schermformaten.

Vooral de hero-animatie en complexe projectcomposities vereisen specifieke aanpassingen.

Ik heb daarom niet alleen elementen verkleind, maar ook de layout en het gedrag van verschillende componenten aangepast.

Een belangrijk verbeterpunt is het verder vereenvoudigen van de CSS-structuur en het testen van de website op verschillende apparaten.
