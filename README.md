# labs.iwobble.com

Astro starter for the iWobble Labs technical/workbench site.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## GitHub Pages

This repo includes `.github/workflows/deploy.yml` configured for GitHub Pages using Node 24.

In GitHub:

1. Go to **Settings → Pages**
2. Set **Source** to **GitHub Actions**
3. Push to `main`

The custom domain is set in `public/CNAME`:

```txt
labs.iwobble.com
```

For DNS, create a CNAME record:

```txt
labs CNAME <your-github-pages-host>
```

For an org/user GitHub Pages setup, this is usually:

```txt
labs CNAME iwobble.github.io
```

## Notes

This is intentionally temporary and structured for iteration:

- `src/pages/index.astro` contains the page content.
- `src/styles/global.css` contains the visual system.
- `public/iwobble-logo.gif` is the current legacy logo placeholder.
