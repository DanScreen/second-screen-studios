# Second Screen Studios

Website for Second Screen Studios. It is a static site and is hosted with GitHub Pages. It contains the studio landing page and the privacy policy that the store listings for Tiki Acca, Scorers and Ludus link to.

## Structure

- `index.html`: landing page
- `privacy/index.html`: privacy policy, served at `/privacy/`
- `assets/style.css`: shared styles, light and dark
- `assets/logo.svg`: app-icon logo (split S on a dark tile), also the favicon
- `assets/logo-mark.svg`: the split S on its own, transparent background
- `assets/logo-lockup.svg`: mark plus wordmark, for light backgrounds. The text uses system fonts, so convert it to outlines in a design tool before using it in print or on store pages.

## Before publishing

- Replace every highlighted `[placeholder]` item.
- Have the privacy policy checked against what each app actually does.
- Enable GitHub Pages: Settings → Pages → Deploy from branch `main`, folder `/ (root)`.
