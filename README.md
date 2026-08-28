# Heeyeon Jang — Service Planner Portfolio (Bilingual)

This is the Service Planner version, adapted from the original UX/UI Designer portfolio. Career, Projects, Education, and Activities content is identical; the Home page, footer, and career résumé role/summary have been rewritten for a service planner position, and the LinkedIn link is omitted (LinkedIn profile is written for the UX/UI Designer position).

A static, framework-free portfolio site (plain HTML/CSS/JS, no build step). Every page has an EN / KR toggle in the top right; the chosen language is remembered (via `localStorage`) and carries over between `index.html` and `career.html`.

## Structure

- `index.html` — main portfolio site: page shell (nav, footer, app container)
- `script.js` — main site's page data, render functions, and hash-based routing
- `career.html` + `career.js` — standalone career résumé page (linked from the Career section's "View Career Résumé" button), built in the same design system
- `style.css` — all styles, shared by both pages
- `images/` — all screenshots and mockups

## Run locally

Any static file server works, e.g.:

```
npx serve .
```

or just open `index.html` directly in a browser.

## Deploy to GitHub Pages

1. Push this folder's contents to a GitHub repository (e.g. as the repo root, or under `/docs`).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to "Deploy from a branch," pick the branch and folder (`/` or `/docs`) this content lives in.
4. Save — GitHub will publish the site at `https://<username>.github.io/<repo>/`.

No build tools, dependencies, or environment variables are required.
