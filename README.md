# tubegate-site

Public pages for the TubeGate Chrome extension, served by GitHub Pages:

- `index.html` – home page (the extension's homepage_url)
- `privacy.html` – privacy policy (the store's privacy-policy URL)
- `sponsors.html` – rules and contact for sponsors
- `ads/feed.json` – the live, **signed** list of sponsored suggestions TubeGate downloads every 6 hours. Never edit
  it by hand: generate it with `node tools/sign-feed.mjs` in the main repo, or TubeGate will ignore it.

Generated from the main repo with `python3 tools/build_site.py`. To add a sponsor, update your
private ad list in the main repo, sign it with `node tools/sign-feed.mjs`, then push here.
