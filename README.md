# UF Power & Energy Club

Public website for the University of Florida Power & Energy Club.

## Local preview

The site has no build step or package dependencies. Start any static file server from the repository root:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Content sources

Public-facing copy and imagery were adapted from the club's shared Drive materials, official LinkedIn event posts, and the University of Florida Foundation giving page. Sources include the club constitution, general body meeting decks, goals, Intro to PowerWorld workshop resources, the Spring 2026 Wunderlich-Malec microgrid session, and the J.R. Kelly Generating Station tour. Private administrative records, applications, account information, budgets, and attendance responses are not included.

The official club giving account is [UF Foundation Fund 020385](https://giving.uff.ufl.edu/giving-opportunities/020385-university-of-florida-power-club-2/).

## Deployment

The workflow in `.github/workflows/pages.yml` deploys the repository root to GitHub Pages on each push to `main`.
