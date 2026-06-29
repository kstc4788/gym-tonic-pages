# Gym Tonic Public Pages

Static pages prepared for public hosting before store submission.

## Files

- `index.html`
- `privacy.html`
- `support.html`
- `styles.css`

## Hosting

This folder is mirrored to the public `kstc4788/gym-tonic-pages` repository for GitHub Pages hosting.

Expected public URLs:

- Privacy policy: `https://kstc4788.github.io/gym-tonic-pages/privacy.html`
- Support: `https://kstc4788.github.io/gym-tonic-pages/support.html`

Use the real hosted `privacy.html` and `support.html` URLs in the store forms.

Do not submit temporary or placeholder URLs.

## Validation

Run:

```bash
dart run tool/release_preflight.dart
```

The preflight checks that the public page files exist and contain the expected Gym Tonic page titles.
