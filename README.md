# Aurora API Docs

Public documentation for the Aurora API, built with [Mintlify](https://mintlify.com).

## Structure

- `docs.json` — Mintlify site configuration (navigation, theme, API playground).
- `openapi.yaml` — OpenAPI spec powering the API Reference.
- `introduction.mdx`, `quickstart.mdx`, `authentication.mdx` — Getting Started guides.
- `concepts/` — Conceptual guides (styles, templates, generation, branding, preflight).
- `images/` — Static assets.

## Local development

Install the Mintlify CLI and run the dev server from the repo root:

```bash
npm i -g mint
mint dev
```

The site will be available at `http://localhost:3000`.

## Validating the OpenAPI spec

```bash
mint openapi-check openapi.yaml
```
