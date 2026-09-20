# Statis

A single-page calculator with four tabs:

- **Contingency table** — chi-squared test (with optional Yates' continuity correction), Fisher's exact test, and odds ratio / relative risk with 95% confidence intervals.
- **T-test** — independent-samples or paired t-tests, with a Shapiro–Wilk normality check and (for independent samples) a Levene's test for equal variance. A Method selector defaults to Auto, picking Student's t-test, Welch's t-test, Mann–Whitney U, or the Wilcoxon signed-rank test based on those checks — or you can override it manually.
- **Correlation** — a scatter plot, Shapiro–Wilk normality checks on X and Y, and a linearity (curvature) test, feeding an Auto method selector that picks Pearson's r or Spearman's rank correlation. Also fits an OLS linear regression, with Breusch–Pagan and residual-normality diagnostics that flag when the regression's own assumptions don't hold.
- **Survival** — Kaplan–Meier estimation for one group or a two-group comparison, from pasted or CSV-uploaded time/event/group data with column mapping, row-level validation, and a data-quality summary. Reports the survival curve (with Greenwood log-log confidence bands and censoring ticks), median survival with 95% CI (explicitly "not reached" when applicable, never approximated), a two-sided log-rank test for two groups, an inspectable life table, and export to SVG/PNG/CSV, clipboard, and a generated Methods-and-Results paragraph. No hazard ratio is computed — that needs a Cox model, which isn't implemented yet.

Open `index.html` in a browser, or serve the repo with GitHub Pages — no build step or dependencies.

**Supervising Developer:** Dr G Narenthiran FRCS(SN) — g_narenthiran@hotmail.com

© 2026 G Narenthiran. All rights reserved.
