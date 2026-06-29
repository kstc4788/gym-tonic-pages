# Gym Tonic Public Pages

Static pages prepared for public hosting before store submission.

## Files

- `index.html`
- `privacy.html`
- `support.html`
- `styles.css`

## Hosting

This folder is deployed by `.github/workflows/pages.yml` through GitHub Pages.

Expected public URLs:

- Privacy policy: `https://kstc4788.github.io/gym-tonic/privacy.html`
- Support: `https://kstc4788.github.io/gym-tonic/support.html`

Use the real hosted `privacy.html` and `support.html` URLs in the store forms.

Do not submit temporary or placeholder URLs.

## Validation

Run:

```bash
dart run tool/release_preflight.dart
```

The preflight checks that the public page files exist and contain the expected Gym Tonic page titles.
