# UF Power & Energy Club

Public website for the University of Florida Power & Energy Club.

## Local preview

The site has no build step or package dependencies. Start any static file server from the repository root:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Content sources

Public-facing copy and imagery were adapted from the club's shared Drive materials, including its constitution, general body meeting decks, goals, and Intro to PowerWorld workshop resources. Private administrative records, applications, account information, budgets, and attendance responses are not included.

## Deployment

The workflow in `.github/workflows/pages.yml` deploys the repository root to GitHub Pages on each push to `main`.
