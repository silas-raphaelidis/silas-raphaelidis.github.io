# Portfolio

Silas Raphaelidis's portfolio site — two static pages, plain HTML/CSS, no build step.

- `index.html` — landing page: name, tagline, demo reel, links to projects + LinkedIn
- `projects.html` — project cards: thumbnail, title, summary, link to full project detail
- `style.css` — shared styles
- `assets/thumbnails/` — project thumbnail images/gifs

## Hosting on GitHub Pages

1. Push this repo to `github.com/Magicow7/portfolio-site` (or whatever repo name you pick).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save. The site will be live at `https://magicow7.github.io/portfolio-site/` within a minute or two.

For a bare `magicow7.github.io` URL (no `/portfolio-site` path), name the repo itself `Magicow7.github.io` instead.

## Custom domain

Once you buy a domain, add a `CNAME` file to the repo root containing just the domain (e.g. `silasraphaelidis.com`), then set the DNS records per [GitHub's custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
