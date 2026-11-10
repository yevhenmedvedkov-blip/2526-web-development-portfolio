# Les 01 – Web Production 101

## 1. Samenvatting

Tijdens deze introductieles hebben we kennisgemaakt met het vak Web Production en de verschillende aspecten van moderne webontwikkeling.

De les behandelde zowel de visuele als de technische kant van webproductie. De belangrijkste onderwerpen waren:

- Visuele frontend development
- Animaties en interactieve elementen
- Accessibility
- SEO, eCRM en performance
- HTML, JavaScript en de DOM
- Browser Developer Tools
- Debugging en het inspecteren van websites

Daarnaast maakten we kennis met verschillende ontwikkeltools, waaronder Visual Studio Code, Node.js, Cursor en CodePen.

Een belangrijk onderdeel van de les was de werking van de DOM (Document Object Model). We bekeken hoe een browser HTML omzet naar een DOM-structuur en hoe JavaScript deze structuur dynamisch kan aanpassen.

## 2. Bronnen

De volgende bronnen en tools kwamen tijdens de les aan bod:

- [MDN Web Docs](https://developer.mozilla.org/) – documentatie over HTML, CSS en JavaScript.
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/) – inspecteren en debuggen van websites.
- [CodePen](https://codepen.io/) – experimenteren met frontend code.
- [Smashing Magazine](https://www.smashingmagazine.com/) – artikelen en inspiratie over webontwikkeling.
- [Visual Studio Code](https://code.visualstudio.com/) – code-editor.
- [Node.js](https://nodejs.org/) – JavaScript-runtime.

## 3. Oefeningen

### Opdracht 0.1 – Portfolio opzetten

Voor deze opdracht heb ik mijn bestaande persoonlijke portfolio website gebruikt.

De website is door mijzelf ontworpen en ontwikkeld en combineert UX/UI Design met frontend development.

Website: https://www.medvedkov.design/

Broncode: https://github.com/yevhenmedvedkov-blip/medvedkov-portfolioo

### Opdracht 0.2 – Make websites ugly again

Deze opdracht richt zich op het aanpassen van een bestaande website via de browser Inspector.

Het doel is om beter te begrijpen hoe HTML-elementen en CSS-stijlen in de browser worden weergegeven en aangepast.

De praktische uitvoering van deze opdracht moet nog worden toegevoegd.

## 4. Wat ik heb geleerd

De onderwerpen uit deze les kan ik op verschillende manieren herkennen in mijn eigen portfolio website.

**HTML en semantische structuur**

Ik gebruik semantische HTML-elementen zoals `<header>`, `<main>`, `<section>` en `<footer>` om de inhoud van mijn website logisch te structureren.

**DOM en JavaScript**

Mijn website gebruikt JavaScript om onderdelen van de interface dynamisch op te bouwen en aan te passen.

Een voorbeeld hiervan is het genereren van projectkaarten op basis van projectgegevens:

```javascript
list.innerHTML = projects.map(p =>
  `<article class="project-card">
    ...
  </article>`
).join('');
```

**Animaties en interacties**

Ik gebruik CSS-animaties en JavaScript-interacties om de gebruikerservaring dynamischer te maken.

Voorbeelden zijn de hero-animatie, scroll-reveal effecten en interactieve navigatie.

**Responsive Design**

De website past zich aan verschillende schermformaten aan met behulp van CSS media queries en JavaScript ResizeObserver.

**Accessibility**

Ik heb onder andere aandacht besteed aan toetsenbordnavigatie, ARIA-labels, een skip-link en de ondersteuning van `prefers-reduced-motion`.

## 5. Zelfreflectie

Mijn persoonlijke portfolio website is een praktisch voorbeeld van hoe verschillende onderdelen van webproductie samenkomen.

Ik heb zelfstandig gewerkt aan het ontwerp, de structuur en de technische implementatie.

Mijn ervaring ligt vooral bij visuele frontend development, responsive design en interactieve elementen.

Door deze les ben ik mij bewuster geworden van de technische werking achter de interface. Vooral de DOM, browser Developer Tools en debugging zijn onderwerpen waarin ik mijn kennis verder wil verdiepen.

Een belangrijk aandachtspunt is om niet alleen aandacht te besteden aan het eindresultaat, maar ook aan de technische structuur en onderhoudbaarheid van de code.

## 6. Zelfevaluatie

**Zelfevaluatie: 4/5**

Ik heb al praktische ervaring met het ontwerpen en ontwikkelen van websites en kan verschillende frontend-concepten toepassen in eigen projecten.

Ik voel mij comfortabel bij het combineren van HTML, CSS en JavaScript om interactieve en responsive interfaces te bouwen.

Ik wil mij verder verdiepen in DOM-manipulatie, debugging en de technische werking van browsers.

## 7. Inhaalbeweging

- De opdracht 'Make websites ugly again' uitvoeren en documenteren.
- Mijn kennis van de DOM verder verdiepen.
- Chrome Developer Tools bewuster gebruiken om HTML, CSS en JavaScript te inspecteren.
- Mijn technische keuzes en leerproces systematischer documenteren.
