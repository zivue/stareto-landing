# stareto-landing

Static landing page for Stareto, adapted from the Angular landing page in the Stareto web app.

## Layout

```text
docs/
  index.html
  assets/css/style.css
  assets/images/logo.svg
  favicon-*.png
  favicon.svg
  robots.txt
  sitemap.xml
```

The site source lives in `docs/`, so it can be served directly by GitHub Pages or any static host.

## Preview

```bash
python3 -m http.server 8080 --directory docs
```

Then open `http://localhost:8080`.

## Editing

- Markup: `docs/index.html`
- Styles: `docs/assets/css/style.css`
- Logo and images: `docs/assets/images/`
- Favicons, robots, and sitemap: `docs/`

There is no build step.
