# gh-pages-test

Minimal frontend plus a tiny FastAPI backend for deployment experiments.

## Frontend

- Static page: `index.html`
- Vercel app URL: `https://gh-pages-test-chi.vercel.app/`
- GitHub Pages URL: `https://dominiqueschaer.github.io/gh-pages-test/`

## Backend

- Framework: FastAPI
- Host target: Vercel
- Health route: `/api/health`
- Message route: `/api/message`

Expected response:

```json
{"status":"ok"}
```
