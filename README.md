# Mihaela Nanu — mihaela nanu llc

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `mihaelananullc.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/mihaelananullc.mjs`).
> To change the content, edit that file and run `node build.mjs mihaelananullc` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@mihaelananullc.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per word / $Per document / $Hourly) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Mihaela Nanu LLC, a Florida limited liability company (document number L22000405821), provides translation and interpreting services to individuals, businesses and professional firms: translation of documents and correspondence, certified translations with a signed certificate of accuracy for official use including immigration filings, consecutive interpreting for appointments, meetings and depositions, and proofreading and review of translations prepared elsewhere. Every document is quoted on word count and complexity before work begins, and all material is handled confidentially. The company does not provide legal, medical or immigration advice. Site: mihaelananullc.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
