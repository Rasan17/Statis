# Statis

A single-page calculator with five tabs:

- **Contingency table** — chi-squared test (with optional Yates' continuity correction), Fisher's exact test, and odds ratio / relative risk with 95% confidence intervals.
- **T-test** — independent-samples or paired t-tests, with a Shapiro–Wilk normality check, per-group histograms, and (for independent samples) a Levene's test for equal variance. A Method selector defaults to Auto, picking Student's t-test, Welch's t-test, Mann–Whitney U, or the Wilcoxon signed-rank test based on those checks — or you can override it manually. Also shows a bar chart of group means with 95% CI error bars, a full descriptive stats table (mean, SD, SEM, CI, median, mode, quartiles, IQR), and a Cohen's d / rank-biserial r effect size with an interpretation guide.
- **Correlation** — a scatter plot, Shapiro–Wilk normality checks on X and Y, and a linearity (curvature) test, feeding an Auto method selector that picks Pearson's r or Spearman's rank correlation. Kendall's tau is available as a manual third option, suggested (not auto-applied) when the sample is small and either variable has tied values. Also fits an OLS linear regression, with Breusch–Pagan and residual-normality diagnostics that flag when the regression's own assumptions don't hold.
- **Survival** — Kaplan–Meier estimation for one group or a two-group comparison, from pasted or CSV-uploaded time/event/group data with column mapping, row-level validation, and a data-quality summary. Reports the survival curve (with Greenwood log-log confidence bands and censoring ticks), median survival with 95% CI (explicitly "not reached" when applicable, never approximated), a two-sided log-rank test for two groups, an inspectable life table, and export to SVG/PNG/CSV, clipboard, and a generated Methods-and-Results paragraph. No hazard ratio is computed — that needs a Cox model, which isn't implemented yet.
- **ANOVA** — an arbitrary number of groups (add/remove as needed), with per-group Shapiro–Wilk normality checks, histograms, and a k-group Levene's test. A Method selector defaults to Auto, which picks standard one-way ANOVA (normal groups, equal variances), Welch's ANOVA (normal groups, unequal variances), a Box–Cox transform followed by Welch's ANOVA (non-normal groups that a transform fixes), or the Kruskal–Wallis test (non-normal groups a transform can't fix) — all four are also selectable manually. Reports a full ANOVA table, eta-squared or epsilon-squared effect size, and a bar chart with 95% CI error bars plus per-group histograms. Post-hoc pairwise comparisons (Tukey's HSD, Games–Howell, Dunn's test) aren't implemented yet.

Open `index.html` in a browser, or serve the repo with GitHub Pages — no build step or dependencies.

**Supervising Developer:** Dr G Narenthiran FRCS(SN) — g_narenthiran@hotmail.com

© 2026 G Narenthiran. All rights reserved.
