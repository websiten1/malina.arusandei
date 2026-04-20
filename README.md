# Mălina Arusandei Nails Academy — Cursuri Unghii Iași

Redesign premium, editorial și modern pentru [cursuriunghiiiasi.ro](https://cursuriunghiiiasi.ro/), aliniat cu brandul internațional [malina-nails.com](https://malina-nails.com/).

## Brand & surse oficiale

- **Trainer**: Mălina Arusandei — *Certified Master Nail Artist & Educator*
- **Acreditare**: cursurile de bază autorizate de **Ministerul Muncii din România**
- **Experiență**: 10 ani în domeniul beauty, formare continuă
- **Adresă**: Str. Lăcătuș Vodă, Nr. 26A, Iași, România
- **Contact**: 0760 056 178 · arusandei21@gmail.com
- **Instagram**: [@malina.arusandei_nail_trainer](https://www.instagram.com/malina.arusandei_nail_trainer/)

## Stil

- **Paletă luxury light** — fundal cream (`#faf7f2`), ink grafit (`#1a140e`), accente champagne/gold, tonuri nude/blush calde.
- **Tipografie editorială** — `Fraunces` (variable, cu suport diacritice românești) pentru display/titluri, `Inter` pentru UI/body.
- **Micro-interacțiuni** — reveal-on-scroll, counter animat, hover pe carduri de cursuri, parallax subtil pe hero, marquee cu tehnici, seal rotativ „Autorizat Ministerul Muncii".
- **Accesibilitate** — `prefers-reduced-motion` respectat, ARIA, contrast bun, focus vizibil.
- **Responsive** — mobile, tabletă, desktop.

## Secțiuni

1. **Hero** — tagline „Certified Master Nail Artist & Educator", fotografie editorială a mâinii cu manichiură, citat oficial
2. **Pilonii academiei** — traineri profesioniști, cursuri autorizate, școală modernă, plată în 2 rate
3. **Cursuri** — Nivel 1 Începători (Ian–Dec 2026), Nivel 2 Avansat (Feb–Sep 2026), Nivel 3 Perfecționare (Apr 2026), VIP 1-la-1 (1000 lei/zi, avans 300 lei)
4. **Despre Mălina** — bio oficial cuvânt cu cuvânt de pe despre-mine
5. **Servicii & Tehnici** — grid editorial cu 8 categorii: manichiură, extensii, construcție, nail art (One Stroke, acuarelă), French/Baby Boomer, Ombre/Cat-Eye, Marble/efect sticlă, pedichiură
6. **Galerie** — 8 stiluri (Nude Glow, French Reverse, Baby Boomer, Burgundy, Autumn Warm, Espresso Matte, Rose Mat, Slim Nails)
7. **Success Stories** — 4 testimoniale cursante (adaptate de pe malina-nails.com)
8. **FAQ** — 10 întrebări reale: înscriere, experiență, ce înveți, rezervare/avans, preț VIP, rate, acreditare, materiale, certificat, greșeli
9. **CTA** — înscrieri grupe 2026 cu WhatsApp & telefon
10. **Contact** — adresă cu link Google Maps, program (L-V 9-22:30 / S-D 9-00:30), formular
11. **Footer** — navigare, cursuri, contact, socials (Instagram, WhatsApp, Email, Academia online), ANPC

## Rulare locală

```bash
cd cursuri-unghii-iasi
python3 -m http.server 8080
# deschide http://localhost:8080
```

## Structură

```
cursuri-unghii-iasi/
├── index.html        # conținut + structură
├── styles.css        # design system luxury light
├── script.js         # reveal, counters, parallax, form demo
├── assets/
│   ├── favicon.svg   # logo-mark „MA"
│   ├── malina.png    # portret trainer
│   └── hero-hand.png # fotografie editorială hero
└── README.md
```
