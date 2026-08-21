# Portfolio

Silas Raphaelidis's portfolio site: a landing page, a projects grid, and six project detail pages, all plain HTML/CSS with no build step.

- `index.html`: landing page with name, tagline, demo reel, links to projects and LinkedIn
- `projects.html`: project cards with thumbnail, title, summary, link to a full detail page
- `avant-guard.html`, `heart-rate-horror.html`, `bad-apple.html`, `vr-musical-constellations.html`, `dungeons-and-danger.html`, `psx-shader.html`: individual project write-ups
- `style.css`: shared styles
- `assets/thumbnails/`: project thumbnail images/gifs
- `CNAME`: custom domain config for GitHub Pages

## Hosting

Hosted on GitHub Pages from the `main` branch of `github.com/Magicow7/Magicow7.github.io`. Any push to `main` rebuilds and updates the live site within a minute or two, at both `https://magicow7.github.io/` and the custom domain below.

## Custom domain

Live at `silasraphaelidis.dev` (registered via Namecheap). DNS points four `A` records at GitHub Pages' load balancer IPs (`185.199.108.153`, `.109.153`, `.110.153`, `.111.153`) plus a `CNAME` for `www`, per [GitHub's custom domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
