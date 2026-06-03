# Justice Gnanamuttu Tool Portfolio

Static portfolio site for three QA and automation tools:

- MockFlow
- DB Table Compare Pro
- LLM Test Case Generator

The home page links to public case-study pages:

- `mockflow.html`
- `db-compare.html`
- `llm-tcg.html`

This repo is safe to publish. Do not copy private source code, local databases, `.env` files, certificates, API keys, captured traffic, or customer data into this folder.

The DB Compare and LLM_TCG screenshots are sanitized demo screens with synthetic data. They are meant to explain the product experience without publishing private databases, user files, credentials, or generated history.

## Local Preview

```powershell
python -m http.server 8898
```

Open:

```text
http://127.0.0.1:8898
```

## Publish With GitHub Pages

Use a public GitHub Pages repository, for example:

```text
justiceg1425-dev.github.io
```

Push this folder to that repository. Then enable:

```text
Settings -> Pages -> Build and deployment -> Source: GitHub Actions
```

The included workflow publishes the current folder as a static Pages site.
