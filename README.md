# nightwall-site

Landing page, support and privacy pages for **Nightwall**, a one-tap ninja climbing game for iPhone.

Live: https://nguyenvanlamm.github.io/nightwall-site/ · [support](https://nguyenvanlamm.github.io/nightwall-site/support.html) · [privacy](https://nguyenvanlamm.github.io/nightwall-site/privacy.html)

Plain static HTML/CSS, no build step and no JavaScript. GitHub Pages serves the `main` branch
root directly (no GitHub Actions). Fonts are self-hosted (Jost, Hanken Grotesk — SIL OFL 1.1,
licences in `assets/fonts/`), so the site makes no third-party requests.

Preview locally: `python3 -m http.server 8000` and open http://127.0.0.1:8000/.
