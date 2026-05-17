# Paton Redevelopment — Website

Static website for **Paton Redevelopment Series LLC**, the leading construction and property redevelopment company in St. Louis, Missouri. Live at [patonredevelopment.com](https://patonredevelopment.com).

---

## Project Structure

```
patonredevelopment.com/
├── index.html          # Single-page site (all content, CSS, and JS)
├── robots.txt          # Allows all crawlers
├── CNAME               # GitHub Pages custom domain
├── favicon.ico
├── apple-touch-icon.png
└── img/
    ├── portfolio/      # img001.jpg – img028.jpg (project gallery)
    ├── construction.jpg
    ├── redevelopment.jpg
    ├── Paton-Redevelopment.jpg
    └── paton-construction.webp
```

## Tech Stack

| Layer | Detail |
|-------|--------|
| HTML/CSS/JS | Vanilla — no framework or build step |
| Hosting | GitHub Pages |
| Domain | `patonredevelopment.com` (via CNAME) |

## Page Sections

| Section | Anchor |
|---------|--------|
| Hero | `#home` |
| About | `#about` |
| Services | `#services` |
| FAQ | `#faq` |
| Portfolio | `#gallery` |
| Contact | `#contact` |

## Structured Data (Schema.org)

Three JSON-LD blocks are embedded in `<head>`:

- **`GeneralContractor`** — business name, address, phone, social profiles, service catalog, founder
- **`WebSite`** — site name and URL for entity association
- **`FAQPage`** — Q&A pairs for AI/LLM citation systems

> Note: `FAQPage` rich results are restricted to government and healthcare sites by Google (August 2023). The markup is retained for AI discoverability benefit.

## Development

No build step required. Edit `index.html` directly and open it in a browser to preview.

```bash
# Clone
git clone https://github.com/bitPimps/patonredevelopment.com.git
cd patonredevelopment.com

# Preview locally (any static server works)
npx serve .
# or
python3 -m http.server 8080
```

Changes pushed to the `main` branch deploy automatically via GitHub Pages.

## Business Info

| Field | Value |
|-------|-------|
| Company | Paton Redevelopment Series LLC |
| Founder | Treinnea Russell |
| Address | 8507 Drury Lane, St. Louis, MO 63147 |
| Phone | (314) 392-8305 |
| Service Area | Greater St. Louis Metropolitan Area |
| Facebook | [patonredevelopmentseries](https://www.facebook.com/patonredevelopmentseries) |
| Instagram | [patonredevelopmentseries](https://www.instagram.com/patonredevelopmentseries/) |
| LinkedIn | [paton-redevelopment-series-llc](https://www.linkedin.com/company/paton-redevelopment-series-llc/) |
