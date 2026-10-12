# NIT Trichy SciVal Research Productivity Dashboard

This starter dashboard has been populated from the uploaded Scopus/SciVal Institutional High-Level Report.

## Includes
- Institution-wide KPI summary
- Subject-area output and citations
- Top author leaderboard (up to 500 authors, as supplied by the report)
- Research topics
- Collaboration profile
- Collaborating institution table
- Searchable subject and author tables

## Important limitations
1. The supplied file is a SciVal high-level report, not a publication-level export. It does not provide individual publication titles/DOIs for a full publications directory or annual publication trend.
2. Author records are SciVal author-level profiles, not a validated current employee directory. They are not mapped to departments and may include name/profile disambiguation issues. Do not label them as current faculty without verification.
3. The report includes an Elsevier copyright/trademark notice. Before publishing data or derived tables on a public GitHub Pages website, verify your institutional licence and permission to redistribute Scopus/SciVal-derived data. Do not publish until approved.
4. The subject-area and collaboration counts can overlap; do not add categories together to derive an institutional total.
5. Citation counts include self-citations according to the report. Values may change over time.

## Publish on GitHub Pages
1. Create a repository on GitHub, for example `nit-trichy-research-dashboard`.
2. Upload `index.html`, `assets/`, and `data/`.
3. In **Settings → Pages**, select **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. Use the URL displayed in Pages settings after deployment.
5. Check the public page, mobile layout, links, source note, and data permissions before sharing widely.

GitHub guide: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Updating
Replace `data/scival_summary.json` with a reviewed dataset in the same structure, or update the parser/source files when the next SciVal export changes.
