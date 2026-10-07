# Steven Buschbach

Private draft of Steven Buschbach's personal economics website.

Plain HTML and CSS. GitHub Pages is disabled, and the repository is private at https://github.com/stevenbuschbach/academic-website-draft. No build step, framework, or external font service is required.

## Edit the website

- `index.html`: About/home page with biography and contact information.
- `research.html`: research interests and future papers.
- `teaching.html`: teaching experience.
- `cv.html`: CV information and download link.
- `styles.css`: shared colors, typography, spacing, and mobile layout.
- `assets/`: add the portrait, CV, and paper PDFs here.

Changes to `main` only update this private repository. Do not enable GitHub Pages or rename the repository to `stevenbuschbach.github.io` unless publication is explicitly requested.

## Add the photo and CV

1. Save the photo as `assets/portrait.jpg`. In `index.html`, replace the entire `portrait-placeholder` div with the commented image element immediately above it.
2. Save the CV as `assets/steven-buschbach-cv.pdf`. In `cv.html`, replace the `PDF forthcoming` span with the commented CV link above it, and update the adjacent sentence.
3. Add the preferred professional email address as a `mailto:` link in the introduction or footer.

Commented examples in `research.html` and `teaching.html` show how to add research papers with abstracts and teaching entries. Replace the relevant forthcoming text as real content becomes available.

## Preview locally

Open `index.html` directly in a browser, or run this command in the repository:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8765/.

## Draft status

The website has been unpublished. The source and history are retained in this private repository. The HTML also includes a `noindex, nofollow` meta tag; that tag alone does not restrict access.

`.nojekyll` tells GitHub Pages to serve these static files without processing them as a Jekyll project.

## Design references

The restrained academic layout was informed by the personal sites of [Sabhya Gupta](https://sabhya-gupta.github.io/), [Immanuel Feld](https://immanuelfeld.github.io/), [Alexander Almeida](https://alexjalmeida.github.io/), and [Rebecca Brough](https://rebeccabrough.github.io/). Their content and assets are not included.
