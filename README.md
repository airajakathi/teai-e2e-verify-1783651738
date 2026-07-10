# TEST_e2e_verify_1783651738

Built with **teai** — the multi-platform AI builder.

## Targets
- `desktop`
- `web`

## Quick start

```bash
yarn install
yarn dev
```

## Desktop (Tauri)

Push to `main` triggers the GitHub Actions workflow at `.github/workflows/tauri.yml` which produces
signed installers for macOS, Windows, and Linux. See the Releases tab for downloads.

## Deploy

- Web / Admin: connect this repo to Vercel or Netlify.
- Mobile: build with Expo EAS (`eas build`).
- Chrome Extension: load `dist/` as an unpacked extension.

_Steeped by teai · brewed by agents._
