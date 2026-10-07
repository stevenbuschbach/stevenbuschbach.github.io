# Steven Buschbach

Personal economics website at **https://stevenbuschbach.github.io/**.

Plain HTML and CSS, hosted on GitHub Pages. No build step, framework, or external font service is required.

## Edit the website

- `index.html`: biography, research, teaching, CV, and contact information.
- `styles.css`: colors, typography, spacing, and mobile layout.
- `assets/`: add the portrait, CV, and paper PDFs here.

GitHub Pages publishes the root of the `main` branch. Commit and push changes to `main` to update the live website automatically.

## Add the photo and CV

1. Save the photo as `assets/portrait.jpg`. In `index.html`, replace the entire `portrait-placeholder` div with the commented image element immediately above it.
2. Save the CV as `assets/steven-buschbach-cv.pdf`. Replace the `PDF forthcoming` span with the commented CV link above it, and update the adjacent sentence.
3. Add the preferred professional email address as a `mailto:` link in the introduction or footer.

Commented examples in the HTML show how to add research papers with abstracts and teaching entries. Replace the relevant forthcoming text as real content becomes available.

## Preview locally

Open `index.html` directly in a browser, or run this command in the repository:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8765/.

## Draft status

The website is public. A `noindex, nofollow` meta tag asks search engines not to index the draft while the photo, CV, and project details are pending. It does not restrict access. Remove that tag from `index.html` when the site is ready for search engines.

`.nojekyll` tells GitHub Pages to serve these static files without processing them as a Jekyll project.

## Design references

The restrained academic layout was informed by the personal sites of [Sabhya Gupta](https://sabhya-gupta.github.io/), [Immanuel Feld](https://immanuelfeld.github.io/), [Alexander Almeida](https://alexjalmeida.github.io/), and [Rebecca Brough](https://rebeccabrough.github.io/). Their content and assets are not included.
