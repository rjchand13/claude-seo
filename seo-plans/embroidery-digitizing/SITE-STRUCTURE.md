# Site Structure: Embroidery Digitizing

Flat and simple: every money page is no more than two clicks from the home page.

```
/                                   Home: positioning, upload CTA, price summary, sew-out gallery
├── /embroidery-digitizing/         Main service page (core head term)
│   ├── /logo-digitizing/
│   ├── /cap-digitizing/            Hats and caps (curved surface, center-out)
│   ├── /left-chest-digitizing/
│   ├── /jacket-back-digitizing/
│   ├── /3d-puff-digitizing/
│   ├── /applique-digitizing/
│   ├── /patch-digitizing/          Embroidered, chenille, woven patches
│   ├── /small-text-digitizing/
│   └── /re-digitizing/             Fixing bad files (problem-aware buyers)
├── /vector-art-conversion/         Add-on service
├── /convert/                       Conversion hub
│   ├── /logo-to-dst/
│   ├── /jpg-to-pes/
│   └── /png-to-embroidery-file/    (add more only if real demand)
├── /pricing/                       Public table + calculator
├── /portfolio/                     Filter by technique / placement
│   └── /portfolio/<project>/       Case studies with sew-out photos
├── /guides/                        Evergreen learning hub
│   ├── /embroidery-file-formats/   Pillar: every format explained
│   │   ├── /dst-file/
│   │   ├── /pes-file/
│   │   └── /dst-vs-pes/
│   ├── /machines/                  Pillar: which file each machine needs
│   │   ├── /brother/
│   │   ├── /janome/
│   │   ├── /tajima/
│   │   └── ...                     Max about 15 brands, each with real detail
│   └── /embroidery-digitizing-cost/
├── /blog/                          Tips, problems, case studies
├── /tools/
│   ├── /price-calculator/
│   └── /machine-format-finder/
├── /about/                         Team, digitizer profiles, software, process
├── /reviews/
├── /guarantee/
├── /faq/
├── /order/                         Upload and quote form (noindex if it's only a form)
├── /contact/
└── /legal/ (privacy, terms, refunds)
```

## Rules

- **URLs:** lowercase, hyphens, short, no dates.
- **One topic per page.** Keyword cannibalization is common in this niche.
- **Programmatic caps:** no more than about 15 machine pages and about 10 conversion pages, and only if each has unique, useful content. Never template "digitizing in <city>" pages; this is not a local service.
- **Order page:** keep it out of the sitemap if it holds no content.

## Internal linking

| From | Links to |
|---|---|
| Every service page | `/pricing/`, `/order/`, 3 matching portfolio pieces, 1–2 related guides |
| Every guide | The service it supports (for example `/dst-file/` → `/logo-digitizing/`), the pillar, and the order CTA |
| Portfolio item | Its technique's service page |
| Blog post | One pillar + one service page, with descriptive anchor text |
| Home | All core services, pricing, portfolio, the two pillars |

## Sitemap

- `sitemap.xml` with only indexable, canonical pages; accurate `lastmod`.
- Submit in Search Console and Bing Webmaster Tools; ping IndexNow on publish.
