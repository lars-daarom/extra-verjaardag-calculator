Extra Verjaardag Calculator - GitHub Pages Setup
Bestandsstructuur voor je repository:
extra-verjaardag-calculator/
│
├── index.html
├── README.md
└── .gitignore (optioneel)
Stappen om dit op GitHub Pages te zetten:
Maak een nieuwe repository op GitHub met de naam extra-verjaardag-calculator
Upload de bestanden:
Kopieer de HTML code uit het vorige artifact
Sla dit op als index.html
Upload naar je repository
Activeer GitHub Pages:
Ga naar Settings → Pages in je repository
Kies bij "Source": Deploy from a branch
Selecteer "main" branch en "/ (root)" folder
Klik op Save
Je website is beschikbaar op:
https://[jouw-username].github.io/extra-verjaardag-calculator/
README.md inhoud:
markdown
# Extra Verjaardag Calculator 🎉

Een leuke web-app die op basis van je naam en geboortedatum een unieke extra verjaardag berekent!

## Features

- 🎂 Bereken je persoonlijke extra verjaardag
- 📅 Altijd minimaal een half jaar van je echte verjaardag
- 🔒 Deterministisch algoritme (dezelfde invoer = dezelfde uitvoer)
- 📱 Responsive design voor alle apparaten
- ⏰ Telt dagen tot je volgende extra verjaardag

## Hoe werkt het?

Het algoritme combineert je naam en geboortedatum tot een unieke hash, die vervolgens wordt gebruikt om een datum te berekenen die altijd minimaal 183 dagen van je echte verjaardag ligt.

## Live Demo

Bezoek de website op: https://[jouw-username].github.io/extra-verjaardag-calculator/

## Lokaal draaien

1. Download `index.html`
2. Open het bestand in je browser
3. Klaar!

## Licentie

Dit project is vrij te gebruiken voor persoonlijke en commerciële doeleinden.
.gitignore inhoud (optioneel):
.DS_Store
Thumbs.db
*.log
