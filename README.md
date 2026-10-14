# Sara Gartland — website

A static site with no build step. Vercel serves the files as they are.

## What's here

- index.html: the home page
- biography.html: the biography page, served at /biography (vercel.json turns on clean URLs)
- images/: the optimized photos and transparent cutouts
- 404.html, favicon.svg, robots.txt, vercel.json

## Deploy

Option 1, GitHub and Vercel (recommended):

1. Create a new repository under the jenniemoserdesign-commits GitHub account, for example sara-gartland-site.
2. Upload the contents of this folder to the repository root, or push it with git.
3. In Vercel, choose Add New, then Project, then import the repository.
4. Set Framework Preset to Other. Leave Build Command empty and set Output Directory to "." (the repository root).
5. Deploy. Then add Sara's domain under Project, Settings, Domains.

Option 2, Vercel CLI: run `npx vercel` inside this folder, then `npx vercel --prod`.

## Before going live

- Ticket links: the "Tickets →" links were placeholders, so this export leaves them out. To add them, put an `<a href="https://…">Tickets →</a>` back into each season row in index.html.
- WSJ logo: the empty logo slot was removed. The press credit still names The Wall Street Journal in text.
- Social preview: once the domain is live, change og:image in both pages to the full URL, for example https://yourdomain.com/images/og-image.jpg.
- Scroll effects: Chrome, Edge and Safari scrub the hero as you scroll. Firefox gets a timed version that opens the window after about three seconds.
