# Geval documentation (Mintlify)

Public documentation for **[Geval](https://geval.io)** — policy-as-code release gates for AI systems. Hosted on **Mintlify** (e.g. `docs.geval.io`).

## What’s in this repo

| Path | Purpose |
|------|---------|
| **`docs.json`** | Mintlify site config — navigation, branding, footer. |
| **`*.mdx`** | Documentation pages (MDX). |
| **`logo/`**, **`favicon.svg`** | Brand assets. |

This site documents the **open-source Geval CLI** ([`geval-labs/geval`](https://github.com/geval-labs/geval)): contracts, policies, signals, `geval check`, CI integration, and decision artifacts.

## Local preview

```bash
npm i -g mint
mint dev
```

Open the URL Mintlify prints (often `http://localhost:3000`).

## Contributing

1. Edit `.mdx` files; keep examples aligned with the **current CLI** (`geval --help` from [Releases](https://github.com/geval-labs/geval/releases)).
2. When adding a page, register it in **`docs.json`** under `navigation.tabs[0].groups`.
3. Run `mint dev` and fix broken links.
4. Open a PR; Mintlify deploys from your connected branch.

## Not documented here

- **REST APIs** — Geval is a **static binary**, not a hosted HTTP service. There is no OpenAPI surface for the core engine.
- **npm `@geval-labs/cli`** — Do not document npm install for the open-source CLI unless it explicitly matches this binary; confusion with other packages has been a support issue.

## Resources

- [Mintlify docs](https://mintlify.com/docs)
- [Geval website](https://geval.io)
- [Config generator](https://config.geval.io)
