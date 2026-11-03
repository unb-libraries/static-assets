# static-assets

Public files that UNB Libraries pages load by URL, served from
`https://raw.githubusercontent.com/unb-libraries/static-assets/main/<path>`.

These are for pages that must keep working when the sites themselves are down, such as the
Kubernetes Gateway's error, maintenance and offline pages, so nothing here is hosted on the
cluster.

| File | Used by |
|---|---|
| `images/pages/page-unavailable.png` | the error, maintenance and offline pages in `kubernetes-metadata/pages/` |

The URLs are written into those pages. Don't move, rename or delete a file without first
changing every page that uses it, or those pages lose the file the moment this branch changes.
