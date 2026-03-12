# CSS Layouts

Ett övningsprojekt i CSS med två versioner av samma sida — en klassisk original och en modern variant.

## Sidor

### Original
Grundläggande CSS-layout med:
- Flexbox-navigation (fixed)
- Flex-container med `order`
- CSS Grid med `grid-template-areas`
- Hover-effekter

### MODERN-layouts
Modern landningssida med:
- Responsiv grid
- Animerade blob-element
- CSS-variabler (`custom properties`)
- `clamp()` för responsiv typografi
- Inbyggd animation med `@keyframes`

## Navigering

Sidorna är länkade till varandra via knappar:
- **Original → Modern:** Gul knapp i navbaren — *"✦ Visa MODERN-layouts"*
- **Modern → Original:** Knapp uppe till vänster — *"← Tillbaka till original"*

## Livedemonstration

[https://burmanaizer67.github.io/CSS-layouts/](https://burmanaizer67.github.io/CSS-layouts/)

## Filstruktur

```
Layouts/
├── index.html             ← Originalsidan
├── main.css               ← Original CSS
└── MODERN-layouts/
    ├── index.html         ← Modern sida
    └── main.css           ← Modern CSS
```
