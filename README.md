# Justice Gnanamuttu QA Engineering Portfolio

Static portfolio site for four QA engineering and automation tools:

- MockFlow
- DB Table Compare Pro
- TestWeave
- Graft

The home page links to public case-study pages:

- `mockflow.html`
- `db-compare.html`
- `llm-tcg.html`
- `graft.html`

This repo is safe to publish. Do not copy private source code, local databases, `.env` files, certificates, API keys, captured traffic, or customer data into this folder.

The DB Compare and TestWeave screenshots are sanitized demo screens with synthetic data. They are meant to explain the product experience without publishing private databases, user files, credentials, uploaded requirements, integration tokens, or generated history.

The Graft screenshots are captured from its own synthetic fixture schema only — a small fictional airline dataset (`FLIGHTS`, `BOOKINGS`, `PASSENGERS`, etc.) that ships with the project — never a real database, connection string, or dataset. Graft's own repo is private; this page is description-only with no "View source" link.

MockFlow is presented as a `0.1.0-beta` private release candidate. The portfolio can mention the installer, QA status, and architecture, but do not publish installer artifacts, source code, local workspaces, generated certificates, logs, or captured API payloads here unless a separate release decision is made.

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
