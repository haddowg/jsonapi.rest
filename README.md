# jsonapi.rest

Marketing site for the JSON:API suite, served via GitHub Pages at [jsonapi.rest](https://jsonapi.rest).

A single static page — no build step. `index.html` contains all markup, styles and scripts (code samples are hand-tokenized for syntax highlighting; no runtime highlighter).

## The suite

| Layer | Package | Repo | Docs |
|---|---|---|---|
| Server core (PHP) | `haddowg/json-api` | [json-api](https://github.com/haddowg/json-api) | [docs](https://haddowg.github.io/json-api/) |
| Symfony bundle | `haddowg/json-api-symfony` | [json-api-symfony](https://github.com/haddowg/json-api-symfony) | [docs](https://haddowg.github.io/json-api-symfony/) |
| TypeScript client | `@haddowg/json-api-client` / `-codegen` / `-query` | [json-api-ts](https://github.com/haddowg/json-api-ts) | [docs](https://haddowg.github.io/json-api-ts/) |

## Development

Open `index.html` in a browser, or:

```sh
python3 -m http.server 8000
```

## Deployment

Pushes to `main` are served by GitHub Pages (branch: `main`, path: `/`). The `CNAME` file pins the custom domain.
