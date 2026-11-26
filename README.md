# Sano

The three Sanofysi websites in one repository. Each folder is a finished static site with no build step.

| Folder | Live address |
|---|---|
| `sanofysi.com/` | https://sanofysi.com (landing page) |
| `syrup.sanofysi.com/` | https://syrup.sanofysi.com (Prebiotic Syrup shop) |
| `sacrecrown.sanofysi.com/` | https://sacrecrown.sanofysi.com (Sacre Crown shop) |

## Deploying on Vercel

Import this repository three times, once per site. For each project set **Root Directory** to the folder name and add that folder's domain. Each folder has its own `vercel.json`.

Deploy `syrup.sanofysi.com` first and `sanofysi.com` last: the landing page redirects old shop links to the syrup subdomain.
