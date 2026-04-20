# Mălina Arusandei Nails Academy — Cursuri Unghii Iași

Redesign premium, editorial și modern pentru [cursuriunghiiiasi.ro](https://cursuriunghiiiasi.ro/).

## Stil

- **Paletă luxury** — fundal obsidian profund (`#0e0b08`), accente champagne & aur (`#c9a36a → #e3c48e`), tonuri nude/blush calde.
- **Tipografie editorială** — `Italiana` + `Cormorant Garamond` pentru display/titluri, `Inter` pentru UI/body.
- **Micro-interacțiuni** — reveal-on-scroll, counter animat la statistici, glow pe hover la carduri de cursuri, parallax subtil pe hero, ticker continuu, shimmer pe card premium.
- **Accesibilitate** — `prefers-reduced-motion` respectat, ARIA pe meniu/toggle, contrast puternic text/fundal, focus vizibil.
- **Responsive** — layout-uri dedicate pentru mobil, tabletă, desktop.

## Secțiuni

1. Hero cu titlu editorial + badge „Autorizat Ministerul Muncii” (rotativ)
2. Pilonii academiei (4 valori)
3. Cursuri — Nivel 1, Nivel 2 (featured), Nivel 3, VIP 1:1
4. Despre Mălina — citat, features, portret stilizat
5. Servicii — grid editorial 3x2
6. Galerie — masonry cu 8 stiluri (Nude Glow, Baby Boomer, Slim Nails, etc.)
7. Testimoniale — 6 recenzii reale din sursă
8. FAQ — accordion (conținut din articolele sursei)
9. CTA gradient cu WhatsApp & telefon
10. Contact — listă detalii + formular premium
11. Footer complet + FAB WhatsApp persistent

## Rulare locală

```bash
cd cursuri-unghii-iasi
python3 -m http.server 8080
# deschide http://localhost:8080
```

Sau `npx serve .` / orice server static.

## Structură

```
cursuri-unghii-iasi/
├── index.html        # conținut + structură
├── styles.css        # design system complet (luxury)
├── script.js         # reveal, counters, parallax, form demo
├── assets/
│   └── favicon.svg   # logo-mark „MA” auriu
└── README.md
```
