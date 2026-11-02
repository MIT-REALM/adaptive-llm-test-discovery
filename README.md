# Project website — Adaptive Test Case Discovery

Static project page for the NeurIPS 2026 paper, intended for hosting under the
[MIT-REALM](https://github.com/MIT-REALM) GitHub organization.

## Local preview

```bash
cd website
python -m http.server 8000
# open http://localhost:8000
```

## Publish under MIT-REALM (GitHub Pages)

1. Create (or transfer) the code repo, e.g. `MIT-REALM/adaptive-llm-test-discovery`.
2. Keep this `website/` folder at the repo root (or copy its contents to `docs/`).
3. In the GitHub repo: **Settings → Pages → Deploy from branch**
   - Branch: `main`
   - Folder: `/website` (or `/docs` if you moved files there)
4. Optional custom domain: `adaptive-llm-test-discovery.realm.mit.edu` (or similar)
   via REALM / MIT DNS + a `CNAME` file in this folder.
5. Update the **GitHub Code** button in `index.html` if the repo name differs.

## Linked artifacts

| Asset | Path |
|-------|------|
| Paper PDF | `assets/paper.pdf` |
| Result figures | `assets/figures/` |
| Code (dev mirror) | https://github.com/anjaliParashar/bayes_llm |
| Intended org repo | https://github.com/MIT-REALM/adaptive-llm-test-discovery |
