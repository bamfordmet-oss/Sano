# Sanofysi website

Static website for Sanofysi Prebiotic Syrup in English, French (`/fr/`) and Swahili (`/sw/`).
No build step is needed: these files are the finished site.

## What is in here

| Path | What it is |
|---|---|
| `index.html` | Homepage |
| `sanofysi-prebiotic-syrup.html` | Product page |
| `sanofysi-journal.html` and the five article pages | Gut health guides |
| `delivery.html` | Delivery across Africa and worldwide |
| `fr/`, `sw/` | The same pages in French and Swahili |
| `assets/` | Images, icons and logos |
| `sitemap.xml`, `robots.txt`, `llms.txt` | Files for search engines and AI crawlers |
| `vercel.json` | Vercel settings: redirects `www` to the main domain and sets caching |
| `CNAME` | The custom domain, used only by GitHub Pages |
| `404.html` | Shown when a page is not found |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Updating the live site

Replace the files in your GitHub repository with everything in this folder (drag them into "Add file > Upload files", or use git), including the files whose names start with a dot. If the repository is connected to Vercel, it redeploys by itself within a minute or two. On GitHub Pages, the site updates after the commit.

## Before you announce the site

1. **Domain.** This copy is wired for `https://syrup.sanofysi.com`: canonical links, language links, share images, structured data, `sitemap.xml`, `robots.txt` and `llms.txt` all use it. `vercel.json` redirects the `www` address to it on Vercel; `CNAME` does the same job on GitHub Pages. Whichever host you use, make sure HTTPS is on.
2. **Search engines.** Add `https://syrup.sanofysi.com` to Google Search Console and Bing Webmaster Tools and submit `https://syrup.sanofysi.com/sitemap.xml`.
3. **Checkout.** "Add to bag" is a preview only. It does not take orders or payments yet.
4. **Delivery details.** `delivery.html` says cost and time are shown at checkout. Replace that with real prices, times and courier once known.
5. **Translations.** Have a native speaker read the French and Swahili pages.
