# Xotl — Notlahtol Noyolloco | El Eco en mis Venas | The Echo in my Veins

> *"Retomar nuestro lugar como uno de los bastiones del progreso de la humanidad."*
> *"Restore our place as one of humanity's bastions of progress."*

**Live site:** [xotl.ai](https://xotl.ai)

---

## About

**Xotl** is a civilizational manifesto declaring the restoration of the Olmec–Teotihuacan–Mayan–Toltec–**Mexica** genetic lineage through technology, space exploration, artificial intelligence, and the revival of Nahuatl as a unified language.

The manifesto is published in three languages — **Nahuatl (nah)**, **Spanish (es)**, and **English (en)** — readable via a language toggle on the page.

The **Mayan Zero** is the symbol of Xotl: a reminder across space and time that every scientific and technological advance belongs to our people.

> **Note on naming:** The term "Mexica" is used throughout rather than "Aztec." "Aztec" is a post-colonial label applied by outside researchers after the fact. The people called themselves **Mexica**.

---

## Vision & Milestones

1. **Space program** — A small radio transmitter placed in Low-Earth Orbit, broadcasting Nezahualcoyotl's poems to all of humanity in Nahuatl.
2. **AI model** — An artificial intelligence aligned to Xotl that speaks Nahuatl.

---

## Foundational Cores

| Core | Description |
|---|---|
| 🗣 **Nahuatl** | The unified language. It will evolve over time, but the fundamental building blocks must be ours. Other dialects are welcomed for naming places, buildings, and events (e.g., a space station named *Kukulkán*). |
| **𝟎 Mayan Zero** | The symbol of Xotl — representing our intellectual heritage and every future achievement. |

---

## Repository Structure

```
/
├── index.html      # Single-file site (HTML + CSS + JS)
├── og-image.svg    # Open Graph / social share image (1200×630)
├── sitemap.xml     # XML sitemap with hreflang alternates
├── robots.txt      # Crawler directives + sitemap pointer
├── llms.txt        # Machine-readable summary for LLM indexers
└── README.md       # This file
```

---

## Tech Stack

A **single-file static site** — no frameworks, no build step, no dependencies.

- Pure **HTML5**, **CSS3**, and **vanilla JavaScript**
- Hosted on **GitHub Pages**
- No tracking cookies — only a `localStorage` key for language preference and cookie banner state
- Full **SEO** meta: canonical, hreflang, Open Graph, Twitter Card, Schema.org structured data
- **AI/LLM indexing**: `ai-summary`, `ai-topics`, `ai-content-type` meta tags + `/llms.txt`
- **EAA / WCAG 2.1 AA**: skip link, ARIA roles and labels, `aria-pressed` toggles, focus-visible styles, `prefers-reduced-motion` support, 44px minimum touch targets
- Inline SVG favicon (no external file needed)
- `lang` attribute updated dynamically on language switch

---

## Deploying

1. Place all files at the root of your repo.
2. Enable GitHub Pages from `Settings → Pages → Branch: main / root`.
3. Your site will be live at `https://<username>.github.io/<repo>/` or your custom domain.

No build process, no package manager, no CI needed.

---

## Privacy

This site stores **only** a single `localStorage` key (`xotl-cookies-accepted`) to remember cookie banner dismissal and language preference. No analytics, no tracking pixels, no third-party cookies of any kind.

---

## Support

Bitcoin donations: `bc1qu4qvhhst0r72gqkm4g2ygx78ratf6tkf3wp7qa`

---

## License

© 2026 [xotl.ai](https://xotl.ai). All rights reserved.

---

*Para quienes crean en Xotl y trabajen por ello, los estaré esperando en el Mictlan con los brazos abiertos.*
*For those of you that believe in Xotl and work towards it, I'll be waiting in Mictlan with open arms for you.*
