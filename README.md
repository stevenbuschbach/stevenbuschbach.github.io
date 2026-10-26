# Steven Buschbach

Steven Buschbach's personal academic website, published at https://stevenbuschbach.github.io.

Plain HTML and CSS, hosted with GitHub Pages from https://github.com/stevenbuschbach/stevenbuschbach.github.io. No build step, framework, or external font service is required.

## Edit the website

- `index.html`: About/home page with biography and contact information.
- `research.html`: research interests and future papers.
- `teaching.html`: teaching experience.
- `cv.html`: CV information and download link.
- `styles.css`: shared colors, typography, spacing, and mobile layout.
- `assets/`: portrait photo, plus future CV and paper PDFs.

GitHub Pages publishes the repository root from `main`. Changes pushed to `main` automatically update the public website.

## Photo, CV, and contact details

1. The supplied portrait is saved as `assets/portrait.jpg` and displayed on the About page. The original photo is unchanged; CSS fits it into the portrait frame.
2. Save the CV as `assets/steven-buschbach-cv.pdf`. In `cv.html`, replace the `PDF forthcoming` span with the commented CV link above it, and update the adjacent sentence.
3. All page footers display the preferred contact text: `Contact me at sbuschbach@uchicago.edu`.

Commented examples in `research.html` and `teaching.html` show how to add research papers with abstracts and teaching entries. Replace the relevant forthcoming text as real content becomes available.

The Job Market Paper section in `research.html` has a disabled PDF placeholder. When ready, add the PDF to `assets/job-market-paper.pdf`, set the placeholder's `href` to that path, remove `aria-disabled`, and change its text to `Paper (PDF)`.

## Preview locally

Open `index.html` directly in a browser, or run this command in the repository:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8765/.

## Publication

Publication was requested on October 26, 2026. The public site includes the supplied portrait, biography, and contact address. Research papers, teaching details, and the CV PDF can be added when ready.

`.nojekyll` tells GitHub Pages to serve these static files without processing them as a Jekyll project.

## Design references

The restrained academic layout was informed by the personal sites of [Sabhya Gupta](https://sabhya-gupta.github.io/), [Immanuel Feld](https://immanuelfeld.github.io/), [Alexander Almeida](https://alexjalmeida.github.io/), and [Rebecca Brough](https://rebeccabrough.github.io/). Their content and assets are not included.
