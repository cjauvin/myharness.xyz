# MyHarness — company website

Static, bilingual (EN/FR) marketing site for **MyHarness**, an AI engineering studio that
helps companies harness AI inside their existing infrastructure through agentic tooling —
MCP servers, skills, and custom agents.

## Structure

```
index.html          # English
fr.html             # French
assets/css/style.css
assets/js/main.js    # sticky header, mobile nav, scroll reveal (no dependencies)
CNAME                # custom domain for GitHub Pages
```

## Local preview

No build step — it's plain HTML/CSS/JS. Serve the folder with any static server:

```sh
python3 -m http.server 8000
# then open http://localhost:8000/
```

## Deployment

Served via **GitHub Pages** from the `main` branch root, on the custom domain
`myharness.xyz`.
