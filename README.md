# Python DSA & Competitive Programming

A browser-based Python learning site with guided data structures, algorithms, and competitive-programming lessons.

## Run locally

Open `index.html` in a browser. No build step or package installation is required.

This project is self-contained: the browser loads a bundled Pyodide runtime, local illustration assets, and system fonts, so it works without internet access after the files are downloaded.

## Deploy to GitHub Pages

This project is a static site, so it is already compatible with GitHub Pages without a build pipeline.

1. Push this repository to GitHub.
2. In the repository, open **Settings → Pages**.
3. Set the source to **GitHub Actions**.
4. The included workflow in `.github/workflows/pages.yml` uploads the repository root as the Pages artifact.
5. Push to the default branch, or run **Deploy to GitHub Pages** manually from the Actions tab.
6. Your site will be published at the GitHub Pages URL shown in the repository settings.

The app uses relative paths like `./assets/hero.svg` and `./pyodide/`, which keeps it working when GitHub Pages serves the project under a repository subpath such as `/your-repo-name/`.