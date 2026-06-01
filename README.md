# Justice Gnanamuttu Tool Portfolio

Static GitHub Pages portfolio for three private-source tools:

- MockFlow
- DB Table Compare Pro
- LLM Test Case Generator

The home page links to deeper public case-study pages:

- `mockflow.html`
- `db-compare.html`
- `llm-tcg.html`

This repo is intended to be public. Do not copy private source code, local databases, `.env` files, certificates, API keys, or captured data into this folder.

The DB Compare and LLM_TCG screenshots are sanitized demo screens with synthetic data. They are meant to explain the product experience without publishing private databases, user files, credentials, or generated history.

## Local Preview

```powershell
python -m http.server 8898
```

Open:

```text
http://127.0.0.1:8898
```

## GitHub Pages Setup

Create a public repo such as:

```text
justiceg1425-dev.github.io
```

Push this folder to that repo. Then enable:

```text
Settings -> Pages -> Build and deployment -> Source: GitHub Actions
```

The included workflow publishes the current folder as a static Pages site.
