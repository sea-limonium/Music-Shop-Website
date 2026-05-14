# Music Shop Website: Rustic Rhythms
## CST 1340: Information in Organisations (MDX)

A multi-page music record store website built entirely from scratch using HTML, CSS, XML, XSLT, and DTD.


### What it does:
Rustic Rhythms is a simulated online record shop featuring a storefront that dynamically renders album data from XML files. Albums are organised by genre and transformed into styled, browsable pages using XSLT, while DTD ensures the XML data stays valid and well-structured.

### Pages: 
- Home (hero section, featured albums, opening hours table, about preview)
- About Us 
- Contact 
- Login 
- Checkout 
- Thank You 
- Storefront (XML-driven)


### Tech & concepts used:
- Semantic HTML5 with tables, forms, lists, and navigation
- External, internal, and inline CSS (flexbox, grid, @keyframes animations, scroll-triggered transitions)
- XML data storage with a custom schema for albums, genres, and tracklists
- DTD validation for XML structure
- XSLT transformation to render XML data as styled XHTML
- Side navigation with anchor-based section jumping
- Cohesive brand identity (custom logo, colour palette, typography)

---
## Installation & Setup

1. Download the `Music_Shop_Website.zip` from this repository and unzip the folder.

```bash
unzip Music_Shop_Website.zip
cd Music_Shop_Website
```

2. Open `index.html` in your browser (Microsoft Edge is recommended) — this is your entry point into the website.

3. To view the store page (XML/XSLT), you'll need to enable **IE Mode** in Edge:
   - Click the `⋯` menu → Settings → Default browser
   - Toggle **"Allow sites to be reloaded in Internet Explorer mode"**
   - Reload the store page using `⋯` → **"Reload in Internet Explorer mode"**


> **Alternative:** If you have Python installed, you can serve the site locally to avoid browser XSLT restrictions:
> ```bash
> cd Music_Shop_Website
> python3 -m http.server
> ```
> Then open `http://localhost:8000/index.html` in any browser.


---
## Appendix
Built as a group coursework project for CST1340 — Information in Organisations at Middlesex University (Spring 2025).
