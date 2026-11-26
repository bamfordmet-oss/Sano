# Sano

Three static sites, one per folder. No build step.

| Folder | Clue |
|---|---|
| `door/` | The front door: where everyone arrives first |
| `drizzle/` | The one you pour into tea |
| `halo/` | The one that sits on your head |

## Deploying on Vercel

Import this repository three times, once per folder. For each project set **Root Directory** to the folder name and add its domain. Each folder has its own `vercel.json`.

Deploy `drizzle` first and `door` last: `door` redirects old links to `drizzle`.
