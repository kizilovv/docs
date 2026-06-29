# CSBoard API docs

Mintlify docs for the CSBoard public `/v1` API. Served at **api.csboard.com**.

- `openapi.json` — the API contract (source of truth for the reference pages,
  `llms.txt`, and the generated MCP). Derived from `cs2-tradeboard-backend/src/routes/public-api/`.
- `docs.json` — Mintlify config + navigation.
- `*.mdx` — narrative guides (auth, rate limits, buying).

## Local preview

```bash
npm i -g mint
mint dev
```

## Deploy

Pushes to `main` auto-deploy via the Mintlify GitHub App. Custom domain
`api.csboard.com` is configured in the Mintlify dashboard.
