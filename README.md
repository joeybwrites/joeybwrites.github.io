# Joey Blackwell II: Portfolio Site

Static two-page portfolio for GitHub Pages. No build step, no framework, no dependencies beyond Google Fonts (loaded from CDN).

## Files

| File | Purpose |
|---|---|
| `index.html` | Public MVP landing page: hero, proof metrics, work themes, selected experience, case-study teasers, contact. |
| `resume.html` | Deeper companion page: full Meta experience, systems, skills, earlier history, publications. |

Both pages are self-contained and link to each other with relative paths (`./index.html`, `./resume.html`). No local Windows paths, no `visual_artifacts` links, no internal `.md` links.

## Contact details (filled in)

- **LinkedIn**: `https://www.linkedin.com/in/joeybwrites/`
- **Email**: `joeyblackwell005@gmail.com` (used on both pages)

No placeholders remain. The site is ready to publish.

## Publish via GitHub Pages

### Option A: user site (cleanest URL: `joeyblackwell.github.io`)

1. Create a public repo named exactly `joeyblackwell.github.io` (swap in your actual GitHub username).
2. Put `index.html` and `resume.html` at the repo root.
3. Commit and push to the `main` branch.
4. Repo Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder: `/ (root)` → Save.
5. Live in 1-2 minutes at `https://joeyblackwell.github.io/`.

### Option B: project site (URL: `username.github.io/portfolio`)

1. Create a public repo named `portfolio`.
2. Add the two HTML files at the root.
3. Settings → Pages → Source: branch `main`, folder `/ (root)`.
4. Live at `https://<username>.github.io/portfolio/`.

Relative links work in both options.

## Pre-publish checklist (from the handoff)

- [x] LinkedIn URL set (`joeybwrites`).
- [x] Email set (`joeyblackwell005@gmail.com`).
- [ ] Open both pages locally; click every nav link and the cross-page links.
- [ ] Confirm page titles and meta descriptions read well.
- [ ] Confirm the layout holds at mobile width (resize to ~375px).
- [ ] Resume download link: none is present. Add an intentional public PDF later if wanted.

## Notes on content decisions

- Metrics on both pages use the vetted, public-safe set from the handoff (10+ years, 100% Platform SDK API coverage, 38 weekly Horizon releases, 200+ engineer-authored diffs, 300+ knowledge-graph nodes). Internal-only telemetry (page views, weekly creator counts, landed-diff counts) was deliberately left off.
- Internal program and tool codenames were genericized. "Meta Connect 2024" is kept because it is a public event.
- The NeurIPS 2026 paper is labeled "under review," not "published." Do not upgrade that wording unless status changes.
- Pantheon is framed as a personal context-engineering project, not a Meta deliverable.
