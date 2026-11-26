# sanofysi.com landing page

The front door for Sanofysi. It introduces the two brands and sends visitors to:

- https://syrup.sanofysi.com (Prebiotic Syrup)
- https://sacrecrown.sanofysi.com (Sacre Crown)

No build step is needed: these files are the finished site.

## Deploy order (important)

1. Deploy the syrup site to `syrup.sanofysi.com` first and check it loads.
2. Then deploy this folder to `sanofysi.com`.

`vercel.json` redirects every address the syrup site used to have on sanofysi.com (product page, journal, articles, delivery, `/fr/`, `/sw/`) to the same page on syrup.sanofysi.com, so old links and search results keep working. If step 2 happens before step 1, those redirects lead to a site that does not exist yet.

The Sacre Crown links point at `sacrecrown.sanofysi.com`, which has to be built and deployed for them to work.
