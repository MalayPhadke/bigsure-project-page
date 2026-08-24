# BiG-SURE project page

A zero-build, single-page project website for **BiG-SURE: Bipartite Graph Spectral Energy for Uncertainty and Reliability Estimation of LLMs**.

## Preview locally

From this directory, run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

Push this directory to a GitHub repository, then in **Settings → Pages** choose **Deploy from a branch** and select the repository root. No build command is required.

## Files

- `index.html` — page content and metadata
- `styles.css` — layout, visual design, and responsive behavior
- `app.js` — saved-example walkthrough, graph rendering, and citation copy action
- `assets/` — the two paper figures used by the page
- `ARR_graph_uncertainty/` — local manuscript source (intentionally ignored by Git)

Update the manuscript/code links and BibTeX author details in `index.html` after de-anonymization.
