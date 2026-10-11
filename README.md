# Mark Johnson portfolio: Hugo draft

First-pass conversion of https://sites.google.com/umd.edu/mark-johnson/home (32 public pages) into a Hugo site.

- `raw/` original HTML snapshots (fetched 2026-10-11)
- `convert.py` HTML to Markdown converter (re-runnable)
- `site/` Hugo project; preview with `~/.local/bin/hugo server -s site`, build with `hugo -s site`
- Images downloaded to `site/static/images/`; internal Google Sites links rewritten to Hugo paths; license footer moved into the layout.
- Not done yet: theme choice, baseURL, deploy target. Digital Media Design and UX/UI Design pages are empty on the source site too.
