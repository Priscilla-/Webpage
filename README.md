# priscilla-canizares — personal academic website

Personal academic website of Priscilla Canizares (gravitational-wave astronomy and
scientific machine learning, DAMTP, University of Cambridge).

Plain static HTML and CSS — no build step, no dependencies.

## Structure

- `index.html` — home
- `about/`, `research/`, `publications/`, `teaching/`, `outreach/`, `contact/` — one page each
- `assets/css/style.css` — the single stylesheet
- `assets/images/` — hero background (`hero.jpg`) and, optionally, a profile photo

## Publishing on GitHub Pages

1. Push to the `main` branch of the GitHub repository.
2. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**,
   select `main` and `/ (root)`, then Save.
3. The site appears at the repository's GitHub Pages URL a minute or two later.

All links are relative, so the site works both as a user site
(`username.github.io`) and as a project site (`username.github.io/repository/`).

## Updating

Edit the HTML directly and push. The publications list is maintained by hand;
full records are on [ORCID](https://orcid.org/0000-0002-4361-3363) and ADS.
