# Ad Connect - Platform Ad
In sprint 2 hebben we de opdracht gekregen om een website te ontwikkelen voor een opdrachtgever, samen met 2 teams van 1e jaars FDND-studenten en 1 team 2e jaars FDND-studenten. Tijdens deze vierde sprint heb ik mij gericht op het maken, onderhouden en implementeren van een gezamenlijke styleguide, samen met mijn team 'JBLS'. Daarnaast het ontwerpen en bouwen van een contact pagina. 

Voor het maken van een gezamenlijke styleguide hebben we eerst een 'interface iventory' gemaakt, om een overzicht te hebben van alle gebruikte elementen in onze projecten. Daarna hebben we er een styleguide van gemaakt in figma en code. Door de gezamelijke styleguide te gebruiken heb je zelf minder code nodig in je eigen project en worden alle projecten een samenhangend geheel.

Graag zou ik feedback willen op de gebruikte kleuren van de styleguide en de layout van de contact-pagina.

#### Wie is Ad Connect?
Het landelijk Overlegplatform Associate degrees (hierna: Platform Ad) is opgericht in 2018. 
De website van het Platform Ad (onder de url: www.deassociatedegree.nl) is een 
toegangspoort voor informatie over Ad-onderwijs. De website is opgericht om de 
leerwaarde en documentatie van Ad-opleidingen te versterken. Het Platform Ad doet dit in 
samenwerking met de ‘Vereniging Hogescholen’. De website is het online platform van het 
‘Overlegplatform Associate Degrees’ en ondersteunt o.a. de hogescholen die Ad-opleidingen 
aanbieden en de Landelijke Ad-overleggen (LadO’s).  

#### Vraag van de opdrachtgever
In de loop der jaren nam de hoeveelheid tekst en documenten toe, waardoor de 
overzichtelijkheid en vindbaarheid van de informatie afnamen.


<ins>Opdracht:</ins> Helpen bij het realiseren van een overzichtelijke en gebruiksvriendelijke website die inspeelt 
op de behoefte van verschillende doelgroepen waar het Platform Ad zich op richt. Ook moet de website eenvoudig te onderhouden zijn door de editor(s) en webmaster.

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
### Het ontwerp
Voor het ontwerp hebben we als team een gezamenlijke 'interface inventory' gemaakt en vanuit daar een gezamenlijke styleguide in figma en code gemaakt. We hebben gekeken naar kleuren, lettertypes en lettergroottes, icons, buttons en formulier inputs. 
Na het maken van de gezamenlijke styleguide, heb ik de classes en custom properties in mijn eigen project gebruikt.

De website is responsive en is Mobile first ontworpen en gemaakt.

<img width="1000" alt="all-devices-black(3)" src="https://github.com/user-attachments/assets/b101e251-b0cc-4805-abcf-e434384a2a6d" />

*Mockup van home-pagina*

Link naar de website: https://sieuwkesheta.github.io/look-and-feel-corporate-identity/

### Gezamenlijke Styleguide
We zijn begonnen met de 'interface inventory' en de styleguide in [figma](https://www.figma.com/design/tbFWADDE5FfJ5oevUHOkRn/Interface-inventory?node-id=0-1&t=d74TXFIyOxs7NbwJ-1).

<img width="500"  alt="image" src="https://github.com/user-attachments/assets/a1e8609d-0168-49ca-8f42-b23d026ed681" />

Daarna hebben we de styleguide overgezet naar classes en custom properties in code en aan een [repository](https://jamievos991.github.io/look-and-feel-styleguide/) gekoppeld.

### Eigen project
Na het maken van de gezamenlijke styleguide, heb ik nieuwe [figma](https://www.figma.com/design/awgVIMDFkdBZeVqqSh3JJN/Moodboard-Ad-Connect-13-11?node-id=0-1&t=hd0YjYUS3blm6WZs-1) ontwerpen gemaakt voor mijn project. 

Eerst de Home-Pagina voor verschillende apparaten met andere kleurstellingen en daarna de Contact-Pagina.  
<img width="100" alt="image" src="https://github.com/user-attachments/assets/2f36a7a9-0d38-431f-a2cc-233b10535bb2" />
<img width="200" alt="image" src="https://github.com/user-attachments/assets/98e89f1f-2d68-4bb7-9252-2574781894d5" />

<img width="100" alt="image" src="https://github.com/user-attachments/assets/ea97a4bf-42b6-4b6b-9510-2188c582228c" />
<img width="200"  alt="image" src="https://github.com/user-attachments/assets/3b4aa9e5-3760-4b43-ba6c-4eebae862d4e" />

### Voorbeelden van verandering met de styleguide:
- Andere buttons, was eerst roze en nu groen:
<img width="100" alt="image" src="https://github.com/user-attachments/assets/bca89142-50a7-46f7-8630-0acf2b7d54d3" />
-->
<img width="120" alt="image" src="https://github.com/user-attachments/assets/cc9fbeb7-031e-4cad-818b-3cf42c4d0507" />


- Andere icons, zoals het hamburgermenu en de 'back-to-top'-knop:
<img width="60" alt="image" src="https://github.com/user-attachments/assets/58e836b8-8a06-49a0-93b2-3fb46d362812" />
-->
<img width="60" alt="image" src="https://github.com/user-attachments/assets/05843297-47da-489f-91b2-a13a66f1a864" />

<br>

<img width="60" alt="image" src="https://github.com/user-attachments/assets/936e1153-83cd-45e3-a486-1256e91e0d3e" />
-->
<img width="60"  alt="image" src="https://github.com/user-attachments/assets/72783859-6a08-4bcf-8b35-67a607a512db" />


- Ander lettertype, van 'Arial' naar 'Gill Sans'
<img width="200" alt="image" src="https://github.com/user-attachments/assets/d9ca3ddf-bc50-4d66-b8e4-6a714fb954b5" />
-->
<img width="200" alt="image" src="https://github.com/user-attachments/assets/6cac46a3-9985-4986-bd85-f8b5e1f76368" />

## Kenmerken
Ik heb gebruikt gemaakt van HTML, CSS en JS.

### HTML Structuur
De HTML structuur van de pagina is semantisch opgebouwd, in het engels. De pagina bevat een header met daarin een navigatie `<nav>`, een main voor de inhoud met meerdere secties `<section>` en articles `<article>`, en een footer.

Ik gebruik gemaakt van classes die in de gezamenlijke styleguide staan.

Lees meer knop, mijn HTML met gezamenlijke CSS:
https://github.com/SieuwkeSheta/look-and-feel-corporate-identity/blob/4884ed567f097e869e62d079b00e3c86c7cf3479/index.html#L125-L131

```CSS
CSS van gezamenlijke styleguide
.MeerNieuws-ad {
  padding: var(--button-size);
  letter-spacing: 2px;
  text-transform: uppercase;
  background-color: var(--primary-color);
  border: none;
  border-radius: var(--border-radius);
  font-family: var(--font-family);
  color: var(--primary-lighter-color);
  cursor: pointer;
  display: inline-flex;
  align-items: center;
  gap: 5px;


  &:focus {
    outline: 2px solid var(--primary-color);
    outline-offset: 0.1em;
  }


  &:active {
    border: 1px solid var(--primary-color);
  }


  &:hover {
    background: var(--primary-lighter-color);
    color: var(--primary-color);
  }
}
```

Lettergrootte, mijn HTML met gezamenlijke CSS:
https://github.com/SieuwkeSheta/look-and-feel-corporate-identity/blob/4884ed567f097e869e62d079b00e3c86c7cf3479/index.html#L164

```CSS
CSS van gezamenlijke styleguide
  .font-size-heading-s {
    font-size: var(--font-size-heading-s);
  }
```

### Belangrijke aspecten CSS
De website is *mobile first* gemaakt. De media queries zijn genest in de elementen, waardoor de code overzichtelijker is en de responsiviteit per element makkelijk aan te passen is. Daarnaast gebruik gemaakt van custom properties van de gezamenlijke styleguide.

Genestte media queries en custom properties:
https://github.com/SieuwkeSheta/look-and-feel-corporate-identity/blob/4884ed567f097e869e62d079b00e3c86c7cf3479/styles/style.css#L149-L163

### Belangrijke aspecten JS
JS is gebruikt om het hamburgermenu interactief te maken

https://github.com/SieuwkeSheta/look-and-feel-corporate-identity/blob/4884ed567f097e869e62d079b00e3c86c7cf3479/scripts/script.js#L1-L10



<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

## Bronnen
- [What is a style guide and how to create one?](https://www.figma.com/resource-library/what-is-a-style-guide/)
- [Interface inventory](https://bradfrost.com/blog/post/interface-inventory/)
- [CSS Custom Properties Guide](https://css-tricks.com/a-complete-guide-to-custom-properties/)

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
