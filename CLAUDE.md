# portfolio

Personal one-page portfolio site — Daniel Decena, Marketing Automation & Operations.

- **Stack:** static HTML/CSS/JS. No build step, no framework, no dependencies.
- **Deploy:** GitHub Pages from `main` (repo `danieldecena/danieldecena.github.io`).
  `.nojekyll` is present — Pages serves files as-is, no Jekyll processing.
- **Entry point:** `index.html` (self-contained — styles are inlined in a `<style>`
  block; theme via `data-theme` on `<html>`).
- **`image-slot.js`** — client-side image handling for the page.
- **Resume PDFs** (`Daniel_Resume.pdf`, `Daniel_Decena_Resume.pdf`) are linked
  assets, not generated here.

## Working here

- Edit `index.html` / `image-slot.js` directly; open the file in a browser to verify.
- Keep it dependency-free — do not add a bundler or framework.
- Commit to `main` and push; Pages redeploys automatically.
