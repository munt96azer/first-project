# Muntazer's Portfolio

A small static portfolio built with plain HTML and CSS. There is no build step, JavaScript framework, server, or contact-form service.

## Run locally

Open `index.html` in a browser, or serve this folder with any static HTTP server. The site is also compatible with GitHub Pages.

## Project structure

- `index.html` contains the page sections and links.
- `style/style.css` contains layout, colors, and responsive styles.
- `image/` contains the current locally stored images.

## Featured projects

- [Creative Agency Landing Page](https://github.com/munt96azer/project-3): a responsive HTML/CSS site with services, portfolio, about, and contact sections. [Live preview](https://munt96azer.github.io/project-3/).
- [Color Gradient Generator](https://github.com/munt96azer/color-project): an interactive JavaScript tool that previews a two-color gradient and shows its CSS value. [Live preview](https://munt96azer.github.io/color-project/).

## Development plan

### Priority 0 — Make the portfolio truthful and usable

- Replace the sample biography with Muntazer's real introduction, skills, and location/time zone if he wants them public.
- Replace generic portfolio cards and stock photography with real project names, screenshots, and working source/live links.
- Confirm whether the existing testimonials are genuine and approved for publication; remove them if they are placeholders.
- Add the actual CV file before presenting a download link.
- Keep contact through the confirmed email link until a form service or backend is selected.

### Priority 1 — Improve reach and accessibility

- Refine the compact mobile navigation and confirm it remains easy to use on narrow phones.
- Add meaningful image descriptions, visible form labels if a form is introduced, and verify keyboard navigation and contrast.
- Add social profile links and a professional page title/description once the owner confirms the canonical profiles and wording.

### Priority 2 — Improve speed and maintainability

- Resize and compress the large portfolio and hero images; use modern formats with fallbacks where practical.
- Remove unused assets and standardize file names.
- Consolidate repeated CSS and define shared color/spacing variables.

### Priority 3 — Add checks and deployment safeguards

- Add automated HTML/CSS checks and a small viewport/link smoke-check to the repository workflow.
- Verify the published site on GitHub Pages after the repository owner confirms its deployment settings.

## Current limitations

The original repository had no README, automated tests, JavaScript, or deployment workflow; this README was added during the review. The original contact fields were not connected to a submission handler; the page now uses the owner's visible email address directly. Personal biography, CV, and testimonial authenticity still need the owner's information before they can be completed accurately.

