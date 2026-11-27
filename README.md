# tylerrollo.github.io

Source code for my personal portfolio website, hosted on GitHub Pages at [tylerrollo.github.io](https://tylerrollo.github.io).

## About This Repository

This repository contains the static web assets, styling, and content configuration for my personal site. Rather than duplicating my resume here, this file documents how the site is organized, maintained, and deployed.

### What’s on the Site

The live site is organized into a clean, single-page portfolio covering:

* **Profile & Overview** — Background as a West Virginia University B.S.C.S. graduate and focus areas in network architecture, cloud/enterprise infrastructure, and full-stack development.
* **Education & Employment** — Academic credentials and professional experience.
* **Projects & Certifications** — Highlights of personal builds, academic coursework projects, and industry certifications.
* **Contact** — Direct links to get in touch via email, LinkedIn, or GitHub.

## Local Development

Because this is a static site hosted on GitHub Pages, no complex build pipeline is required to preview changes locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/TylerRollo/tylerrollo.github.io.git](https://github.com/TylerRollo/tylerrollo.github.io.git)
   cd tylerrollo.github.io
   ```

2. **Preview locally:**
   Open `index.html` directly in your browser, or run a lightweight local server (for example, using Python):
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

## Deployment

Any changes pushed to the `main` branch are automatically built and deployed by GitHub Pages to [https://tylerrollo.github.io](https://tylerrollo.github.io).

## License & Acknowledgments

* **Original Template:** Built upon a portfolio template originally created by [Sen Li](https://github.com/senli), distributed under the MIT License.
* **License Terms:** See the [`LICENSE`](./LICENSE) file in the root of this repository for the full MIT License text and original copyright notice.
