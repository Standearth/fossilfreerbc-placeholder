# fossilfreerbc-placeholder

A temporary GitHub Pages placeholder for **fossilfreerbc.org**. It went up on
2026-11-11, after a DMCA takedown request took the WordPress site (on GreenGeeks,
theme in [`wp-fossilfreerbc`](https://github.com/Standearth/wp-fossilfreerbc))
out of service.

- `index.html` is the page. `404.html` is a copy, so every old URL shows it too.
- `CNAME` is `fossilfreerbc.org`. HTTPS is enforced and covers `www`.
- The page is `noindex`, so search engines don't replace the real site's listing
  with this page.
- The same files are in the site's docroot on GreenGeeks, so the page shows there
  too while DNS catches up.

**Keep the two copies in step.** A change here updates GitHub Pages only. Copy it to
`gg.stand.earth:/home/standear/public_html/fossilfreerbc.org/` as well.

**Restoring the real site** (moving WordPress back, re-enabling deploys, DNS, then
retiring this repo) is in
[`wp-fossilfreerbc`'s README](https://github.com/Standearth/wp-fossilfreerbc#-offline-since-2026-11-11-dmca-takedown).
