# idlewait.github.io

Source for the idlewait website (<https://idlewait.io>), served with GitHub
Pages from the repository root on the `main` branch. This file is developer
notes; the public site is `index.md`.

## Structure

- `index.md` — the home page (rendered at the site root).
- `<app>/privacy.md` — each app's privacy policy, reachable at
  `https://idlewait.io/<app>/privacy` (e.g. `a11-field/privacy`).
- `<app>/img/` — images used by the site for that app.
- `CNAME` — custom domain (`idlewait.io`).

## Apps

- **A-11 Field** (Wear OS watch face) — policy at
  <https://idlewait.io/a11-field/privacy>.

## Notes

- No source code lives here; app source is in each app's own repository.
- GitHub Pages prefers `index.md` over `README.md` for the site root, so this
  README is not published as a page.
