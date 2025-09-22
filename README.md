# Golden Years Fitness — Static site (pt-home-page)

This repository contains a small static website for "Golden Years Fitness". It's plain HTML, CSS and a little JavaScript and is intended to be served via GitHub Pages.

Live demo (GitHub Pages):

- https://massexile.github.io/pt-home-page/

## What is here

- `index.html` — Home page
- `about.html` — Team / About page
- `services.html` — Services listing
- `resources.html` — Resources page (sidebar with downloads)
- `contact.html` — Contact form + map
- `styles.css` — Site styles
- `images/` — Images used across the site
- `downloads/` — PDF resources (added for download links)
- `README.md` — This file

## Quick notes for maintenance

- GitHub Pages is case-sensitive. Keep filenames and links lowercase and consistent (e.g. `resources.html`, `images/lisa.png`).
- To preview locally, open `index.html` in your browser. No build step is required.
- To add or replace downloadable PDFs, put them in the `downloads/` folder and commit. Use relative links in `resources.html` like:

  <a href="downloads/fitness-guide.pdf" download>Fitness Guide (PDF)</a>

## How deployment works

- The site is served from the `main` branch root via GitHub Pages. After pushing to `main` GitHub Pages deploys automatically (may take a minute to propagate).

## Security & accessibility reminders

- Keep any private data out of the repo. Do not store secrets in HTML/CSS.
- Add `aria-label` attributes and clear link text for screen-reader users (especially for downloads and navigation).

## Short changelog

- Fixed image paths to be relative instead of leading-slash absolute paths so assets load correctly on GitHub Pages.
- Renamed/created lowercase `resources.html` to avoid case-sensitive 404s on Pages.
- Added `downloads/` and uploaded three PDF resources with links in the resources sidebar.

## Troubleshooting

- If an asset 404s after a push, wait a minute and hard-refresh your browser (Ctrl+F5). If still failing, check the exact URL in DevTools (Network tab) and verify the file exists in the repo.
- Avoid nested Git repositories inside this repo — they can block commits and push operations.

---

If you'd like, I can:

- Convert the download list into styled cards with icons/size/date.
- Add brief summaries and last-modified timestamps next to each download.
- Commit and push any outstanding local edits (e.g., `about.html`) so the repo state is clean.

If you'd like me to commit your recent edits to `about.html` and `resources.html`, say "Please commit my local edits" and I will stage, commit, and push them.
# 🎨 Partially Generated Website


Note:  I chose this AFTER I thought about redoing my graphic laden prototypes from a beginning templete from wC3schools.  This provided what I needed 
from a picture of what it should look like with HTML and CSS (and little JS ).

***** IF THIS IS NOT ACCEPTABLE, LET ME KNOW AND WILL TRY TO DO THE REMAINING 5-6 ASSIGNMENTS MANUALLY (AS MUCH AS POSSIBLE, WITHOUTH TEMPLATES) ****


This website was generated using the **Screenshot to HTML Builder** by Charles Ayere, powered by Cloudflare Workers and Google Gemini AI.

Tools Used: above and https://www.w3schools.com/html/html_images.asp and thier extensive responsive nav area

Chrome DevTools used to check Mobile / Tablet / Desktop Friendly design.  (More work needs to be done for the other pages)

## 📁 Files Included

- **index.html** - The main HTML file
- **styles.css** - All the CSS styles  
- **README.md** - This file (setup instructions)


### Responsive Breakpoints:
```css
/* Tablet */
@media (max-width: 1024px) { ... }

/* Mobile */
@media (max-width: 768px) { ... }  <--- I used this one>
```


## 🔗 Resources

- **Original Tool**: [Screenshot to HTML Builder](https://github.com/your-username/screenshot-to-html)
- **Creator**: Charles Ayere
- **Powered by**: Cloudflare Workers & Google Gemini AI
- **License**: MIT


## 🎉 Enjoy Your New Website!

Your screenshot has been transformed into clean, modern, production-ready code using cutting-edge AI technology.

**Technology Stack:**
- 🤖 **AI**: Google Gemini 1.5 Flash

- 🌐 **Hosting**: GitHub Pages

