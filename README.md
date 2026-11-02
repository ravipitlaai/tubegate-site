# tubegate-site

Public pages for the TubeGate Chrome extension, served by GitHub Pages:

- `index.html` – home page (the extension's homepage_url)
- `privacy.html` – privacy policy (the store's privacy-policy URL)
- `sponsors.html` – rules and contact for sponsors
- `ads/feed.json` – the live list of sponsored suggestions TubeGate downloads every 6 hours

Generated from the main repo with `python3 tools/build_site.py`. To add a sponsor, edit
`ads/feed.json`, check it in the main repo with `node tools/check-feed.mjs`, then push here.
