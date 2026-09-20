# Statis

A single-page calculator with three tabs:

- **Contingency table** — chi-squared test (with optional Yates' continuity correction), Fisher's exact test, and odds ratio / relative risk with 95% confidence intervals.
- **T-test** — independent-samples or paired t-tests, with a Shapiro–Wilk normality check and (for independent samples) a Levene's test for equal variance. A Method selector defaults to Auto, picking Student's t-test, Welch's t-test, Mann–Whitney U, or the Wilcoxon signed-rank test based on those checks — or you can override it manually.
- **Correlation** — a scatter plot, Shapiro–Wilk normality checks on X and Y, and a linearity (curvature) test, feeding an Auto method selector that picks Pearson's r or Spearman's rank correlation. Also fits an OLS linear regression, with Breusch–Pagan and residual-normality diagnostics that flag when the regression's own assumptions don't hold.

Open `index.html` in a browser, or serve the repo with GitHub Pages — no build step or dependencies.

**Supervising Developer:** Dr G Narenthiran FRCS(SN) — g_narenthiran@hotmail.com

© 2026 G Narenthiran. All rights reserved.
