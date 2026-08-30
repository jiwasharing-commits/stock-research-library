# Stock Notes — Frontend Prototype

Bright, data-driven prototype for a stock research library and investment learning hub. All content is **sample/placeholder content**, not real investment research.

## Development

```bash
npm install
npm run dev
```

## Access and payment security (future phase)

The current checkout, purchase state, and downloads are UI simulations only. Hiding a button in the browser is **not security**. Paid PDFs must not be stored as unrestricted public assets. When payments are implemented, use payment verification, protected storage, user access records, unique access tokens, and expiring signed download URLs. A PDF password may be added only as secondary protection.

## GitHub Pages Deployment

In the repository settings, open **Pages** and set **Source** to **GitHub Actions** (not “Deploy from a branch”). Pushes to `main` then build the Vite app and deploy only the generated `dist` artifact.
