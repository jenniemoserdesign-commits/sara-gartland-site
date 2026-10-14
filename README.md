# Sara Gartland — website

A static site with no build step. Vercel serves the files as they are.

## What's here

- index.html: the home page, designed for phone, tablet and desktop
- biography.html: the biography page, served at /biography (vercel.json turns on clean URLs)
- images/: the optimized photos and transparent cutouts
- 404.html, favicon.svg, robots.txt, vercel.json

## SEO

Each page has a canonical URL on https://www.saragartland.com, Open Graph and Twitter tags with an absolute share image, and structured data (schema.org Person, WebSite and ProfilePage). sitemap.xml lists both pages and robots.txt points to it. Submit the sitemap in Google Search Console once the domain is verified there.

## Analytics

The Nixie tracker (data-site ifmEixKRynGCKtrffj) loads on every page, including the 404 page.

## Deploy

1. Create a new repository under the jenniemoserdesign-commits GitHub account, for example sara-gartland-site.
2. Upload the contents of this folder to the repository root.
3. In Vercel, choose Add New, then Project, then import the repository. Set Framework Preset to Other and leave the build command empty.
4. Deploy, then add Sara's domain under Settings, Domains.

To update the site later, replace the files in the repo. Vercel redeploys automatically.

## Before going live

- Ticket links: the "Tickets →" links were placeholders, so this export leaves them out. To add them, put an `<a href="https://…">Tickets →</a>` back into each season row in index.html.
- Scroll effects: Chrome, Edge and Safari scrub the hero as you scroll. Firefox gets a timed version.
