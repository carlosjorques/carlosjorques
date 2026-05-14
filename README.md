# Carlos Jorques Portfolio

Astro static site for Carlos Jorques, positioned as an Embedded Control Systems Architect.

## Local Development

Install dependencies and start the local development server:

```sh
npm install
npm run dev
```

The dev server runs at `http://localhost:4321`.

## Build

Build the production site:

```sh
npm run build
```

Astro writes the static output to `dist/`.

## GitHub Pages Deployment

Deployment is configured through `.github/workflows/static.yml` using the official Astro GitHub Action and GitHub Pages.

Current deployment assumptions:

- Repository: `carlosjorques/carlosjorques`
- Pages URL: `https://carlosjorques.github.io/carlosjorques/`
- Source branch: `master`
- Output directory: `dist/`
- Node.js: 22

In the GitHub repository settings, set Pages source to **GitHub Actions**. Each push to `master` will build and deploy the site.
