# Early Warning Signals — Norwegian Business Distress

An independent analytical portfolio project by **Mariia Nyaas**. Built using public Statistics Norway (SSB) data.

## Purpose
Explore the distribution and year-on-year dynamics of Norwegian bankruptcies. The current version provides descriptive monitoring **not predictive early-warning performance**.

## Live site
https://mariianyaas.github.io/early-warning-signals-norway/

## Publish
Upload the files in `docs/` and `data/` to matching folders in your existing public repository. Under Settings → Pages, select Branch `main`, Folder `/docs`. `docs/index.html` is self-contained and needs no server or external JavaScript library.

## Files
- `docs/index.html`: self-contained, interactive dashboard
- `data/dashboard_data.json`: reproducible compact source extract
- `reports/executive_summary.md`: management commentary
- `src/methodology.md`: indicator definition and limitations

## Source & licensing
Data: Statistics Norway, [Bankruptcies](https://www.ssb.no/en/virksomheter-foretak-og-regnskap/konkurser/statistikk/opna-konkursar), updated 22 October 2026; SSB's CC BY 4.0 terms. The source CSV tables were provided as downloads from SSB. The project contains no confidential employer information.

## Scope warning
Quarterly totals for Q4 2025–Q3 2026, sector and county comparisons for Q3 2025 vs Q3 2026. Enterprise sector counts exclude sole proprietorships; all-category county counts do not. Bankruptcy counts are not probabilities of default; no active-company denominator or historical backtest is available in this version.
