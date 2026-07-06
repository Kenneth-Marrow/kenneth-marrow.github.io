# Kenneth Marrow — Portfolio

Personal portfolio site for Kenneth Marrow, a Backend / Python Developer focused on production reliability, observability, and internal platform tooling.

**Live site:** https://kenneth-marrow.github.io

## Stack

Single static HTML file with embedded CSS and JavaScript. No build step, no dependencies beyond two Google Fonts (Inter + JetBrains Mono).

## Local preview

```bash
open index.html
```

Or serve with any static server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Updating placeholder links

Near the bottom of `index.html`, update the `LINKS` object with your actual URLs:

```js
const LINKS = {
  github:   'https://github.com/Kenneth-Marrow',
  linkedin: 'https://www.linkedin.com/in/…',
  resume:   'https://…/resume.pdf'
};
```
