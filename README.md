# Fieldkit website

Website for the Fieldkit iOS app (landing, features, support and privacy pages), published with GitHub Pages.

- Landing page: https://gpluta.github.io/fieldkit-app/ (`index.html`, the App Store **Marketing URL**; hero image `img/hero.jpg` = `swift Tools/make-header.swift <file>.png 2400 1100 scene`, saved as JPEG)
- Support: https://gpluta.github.io/fieldkit-app/support.html (the App Store **Support URL**)
- Privacy policy: https://gpluta.github.io/fieldkit-app/privacy.html
- Features: https://gpluta.github.io/fieldkit-app/features.html (every tool, with screenshots in `img/`: 1000 px tall JPEG copies of `AppStore/screenshots/`, plus `gear.jpg` and `shot-log.jpg` taken only for the site on 2026-10-31: iPhone 17 Pro Max simulator, dark mode, `-startTool gear -gear "<hex of the gear JSON>"` with a 45 MP full-frame camera and ND8/64/1000, and `-startTool shotLog` after `-seedShots YES`. The Light Meter has none: it needs a real camera)

Live since 2026-10-28 from the public repo `gpluta/fieldkit-app` (GitHub Pages, `main` branch, root). To update: edit the files here, copy them into that repo, commit and push.

**Don't rename or move `support.html`, `privacy.html` or `index.html`:** their addresses are entered in App Store Connect. On 2026-10-31 Support moved from the root to `support.html` and the landing page from `home.html` to the root; `home.html` now only redirects to the root, for old links.
