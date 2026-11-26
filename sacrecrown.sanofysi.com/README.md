# sacrecrown.sanofysi.com

The Sacre Crown shop. Static files, no build step: upload this folder as it is.

- `index.html` home
- `hair-building-fibers.html`, `hair-perfecting-kit.html` product pages
- `journal.html` and five articles
- `delivery.html`
- `fr/` French and `sw/` Swahili copies of every page
- `sitemap.xml`, `robots.txt`, `llms.txt` for search engines and AI assistants

Point the subdomain `sacrecrown.sanofysi.com` at this project (on Vercel: add the domain to the project; `CNAME` is only used by GitHub Pages).

After it is live, submit `https://sacrecrown.sanofysi.com/sitemap.xml` in Google Search Console.

To change prices, the advert or any text, edit the files in `12-sacrecrown/_build/` in the brand kit and run `build.py` again.
