# Sano

Three static sites, one per folder. No build step.

| Folder | Site |
|---|---|
| `main-door/` | The main site (no subdomain): the front door where everyone arrives first |
| `syrup-drizzle/` | The `syrup` subdomain |
| `sacrecrown-halo/` | The `sacrecrown` subdomain |

## Deploying on Vercel

Import this repository three times, once per folder. For each project set **Root Directory** to the folder name and add its domain. Each folder has its own `vercel.json`.

Deploy `syrup-drizzle` first and `main-door` last: `main-door` redirects old links to the syrup site.
