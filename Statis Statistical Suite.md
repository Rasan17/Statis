# Statis Statistical Suite

Conceived, directed and developed by **Dr G Narenthiran** (g\_narenthiran@hotmail.com).

© 2026 Dr G Narenthiran. All rights reserved.

## Web apps

| Web app | Focus | URL |
| --- | --- | --- |
| Statis | Frequentist analysis of datasets: tests, regression, survival, meta-analysis, machine learning | [rasan17.github.io/Statis](https://rasan17.github.io/Statis/) |
| Statis-Gravity | Study design, descriptive and comparative statistics, diagnostics, multivariate EDA, teaching simulations | [rasan17.github.io/statis-gravity](https://rasan17.github.io/statis-gravity/) |
| Bayes-Estimation | Bayesian estimation for proportions, means and diagnostic tests | [rasan17.github.io/Bayes-Estimation](https://rasan17.github.io/Bayes-Estimation/) |

## Statistical tests by web app

Tests are ordered from study design through description, comparison, modelling and synthesis, to Bayesian methods and teaching tools. A tick shows which app offers each one.

| Category | Test or procedure | Statis | Statis-Gravity | Bayes-Estimation |
| --- | --- | --- | --- | --- |
| 1. Study design | Sample size and power: two independent means (t-test) |  | ✓ |  |
| 1. Study design | Sample size and power: paired means (paired t-test) |  | ✓ |  |
| 1. Study design | Sample size and power: two proportions (χ² / Fisher's exact) |  | ✓ |  |
| 1. Study design | Post-hoc (achieved) power |  | ✓ |  |
| 1. Study design | Simple randomisation |  | ✓ |  |
| 1. Study design | Block randomisation (balanced allocation) |  | ✓ |  |
| 2. Descriptive | Descriptive statistics (n, mean, median, mode, SD, variance, range) | ✓ | ✓ |  |
| 2. Descriptive | 95% CI for the mean |  | ✓ |  |
| 2. Descriptive | Skewness and kurtosis |  | ✓ |  |
| 2. Descriptive | Outlier detection (Tukey's fences) |  | ✓ |  |
| 2. Descriptive | Frequency histogram, box-and-whisker and violin plots |  | ✓ |  |
| 2. Descriptive | Pivot tables | ✓ |  |  |
| 3. Assumption checks | Shapiro–Wilk normality test | ✓ |  |  |
| 3. Assumption checks | Jarque–Bera normality test |  | ✓ |  |
| 3. Assumption checks | Levene's test (equality of variances) | ✓ | ✓ |  |
| 3. Assumption checks | Box–Cox transformation | ✓ |  |  |
| 4. Two groups | Student's t-test (independent, equal variances) | ✓ | ✓ |  |
| 4. Two groups | Welch's t-test (independent, unequal variances) | ✓ | ✓ |  |
| 4. Two groups | Paired t-test | ✓ | ✓ |  |
| 4. Two groups | Mann–Whitney U test | ✓ | ✓ |  |
| 4. Two groups | Wilcoxon signed-rank test | ✓ | ✓ |  |
| 4. Two groups | Cohen's d | ✓ | ✓ | ✓ |
| 5. Three or more groups | One-way ANOVA | ✓ | ✓ |  |
| 5. Three or more groups | Welch's ANOVA | ✓ | ✓ |  |
| 5. Three or more groups | Kruskal–Wallis H test | ✓ | ✓ |  |
| 5. Three or more groups | One-way repeated-measures ANOVA |  | ✓ |  |
| 5. Three or more groups | Friedman test |  | ✓ |  |
| 5. Three or more groups | Post-hoc contrasts (Tukey HSD, Games–Howell, Dunn, Bonferroni) |  | ✓ |  |
| 5. Three or more groups | Effect sizes (η², ε²) | ✓ |  |  |
| 5. Three or more groups | MANOVA (Wilks' Λ) with univariate follow-up | ✓ |  |  |
| 5. Three or more groups | ANCOVA (homogeneity of slopes, partial η²) | ✓ |  |  |
| 6. Categorical data | Pearson's χ² test | ✓ | ✓ |  |
| 6. Categorical data | Yates' continuity correction | ✓ | ✓ |  |
| 6. Categorical data | Fisher's exact test | ✓ | ✓ |  |
| 6. Categorical data | Cramér's V | ✓ |  |  |
| 6. Categorical data | Odds ratio | ✓ | ✓ | ✓ |
| 6. Categorical data | Relative risk | ✓ | ✓ | ✓ |
| 6. Categorical data | Risk difference (absolute risk reduction) | ✓ |  | ✓ |
| 6. Categorical data | Number needed to treat |  | ✓ | ✓ |
| 6. Categorical data | Wilson score 95% CI for a proportion |  | ✓ |  |
| 6. Categorical data | Cohen's h |  |  | ✓ |
| 7. Correlation and linear regression | Pearson's r | ✓ | ✓ |  |
| 7. Correlation and linear regression | Spearman's ρ | ✓ | ✓ |  |
| 7. Correlation and linear regression | Kendall's τ-b | ✓ |  |  |
| 7. Correlation and linear regression | Linear (OLS) regression with R² | ✓ | ✓ |  |
| 7. Correlation and linear regression | Regression diagnostics (Breusch–Pagan, residual normality, curvature check) | ✓ |  |  |
| 8. Generalised linear models | Logistic regression (logit or probit link) | ✓ |  |  |
| 8. Generalised linear models | Firth's penalised-likelihood correction | ✓ |  |  |
| 8. Generalised linear models | Poisson regression with overdispersion check | ✓ |  |  |
| 8. Generalised linear models | Relative-risk regression (log-binomial, modified Poisson fallback, bootstrap SE) | ✓ |  |  |
| 8. Generalised linear models | Likelihood-ratio test, McFadden's pseudo-R², confusion matrix | ✓ |  |  |
| 9. Survival analysis | Kaplan–Meier estimate with Greenwood variance and median survival | ✓ |  |  |
| 9. Survival analysis | Log-rank test (two groups) | ✓ |  |  |
| 9. Survival analysis | Life table | ✓ |  |  |
| 10. Diagnostic accuracy | Sensitivity, specificity, PPV, NPV |  | ✓ |  |
| 10. Diagnostic accuracy | Likelihood ratios (LR+, LR−) |  | ✓ | ✓ |
| 10. Diagnostic accuracy | Diagnostic odds ratio |  |  | ✓ |
| 10. Diagnostic accuracy | Post-test probability and Fagan nomogram |  |  | ✓ |
| 10. Diagnostic accuracy | ROC curve and AUC | ✓ (ML classifiers) | ✓ |  |
| 10. Diagnostic accuracy | Optimal cut-off (Youden's J) |  | ✓ |  |
| 11. Meta-analysis | Mantel–Haenszel fixed-effect pooling (OR, RR, RD) | ✓ |  |  |
| 11. Meta-analysis | DerSimonian–Laird random effects | ✓ |  |  |
| 11. Meta-analysis | Hartung–Knapp–Sidik–Jonkman adjustment | ✓ |  |  |
| 11. Meta-analysis | Heterogeneity (Cochran's Q, I²) | ✓ |  |  |
| 11. Meta-analysis | Forest plot; funnel plot with Egger's test | ✓ |  |  |
| 12. Causal and multivariate | Propensity score matching (caliper, SMD balance, ATT) |  | ✓ |  |
| 12. Causal and multivariate | Principal component analysis (PCA) |  | ✓ |  |
| 12. Causal and multivariate | Multiple correspondence analysis (MCA) |  | ✓ |  |
| 12. Causal and multivariate | Factor analysis of mixed data (FAMD) |  | ✓ |  |
| 13. Machine learning | Supervised: logistic/softmax, decision tree, random forest, k-NN, neural network | ✓ |  |  |
| 13. Machine learning | Clustering: k-means, hierarchical (Ward), Gaussian mixture (EM), DBSCAN, silhouette | ✓ |  |  |
| 14. Bayesian | Two proportions (beta-binomial): posterior RR, OR, ARR; P(treatment > control); ROPE |  |  | ✓ |
| 14. Bayesian | Bayes factor for two proportions (Savage–Dickey) |  |  | ✓ |
| 14. Bayesian | Two means (BEST): Δμ, 95% HDI, CLES, variance ratio, ROPE |  |  | ✓ |
| 14. Bayesian | JZS Bayes factor (Cauchy prior) for two means |  |  | ✓ |
| 14. Bayesian | Single proportion (beta-binomial) vs benchmark |  |  | ✓ |
| 14. Bayesian | Single mean (normal-normal) vs benchmark |  |  | ✓ |
| 14. Bayesian | Bayes' theorem and odds updating (unit-square visualisation) |  | ✓ |  |
| 15. Teaching simulations | Probability distributions (normal, t, log-normal, exponential, bimodal, uniform, Poisson, χ²) |  | ✓ |  |
| 15. Teaching simulations | Central limit theorem simulation |  | ✓ |  |
| 15. Teaching simulations | Convergence of t to the standard normal |  | ✓ |  |
| 15. Teaching simulations | Two-sample overlap and α boundary |  | ✓ |  |
| 15. Teaching simulations | Power (1 − β) and type II error visualiser |  | ✓ |  |

## Notes

- The listing reflects the public pages of each app as read on 3 October 2026.
- Statis states that post-hoc pairwise comparisons, Cox proportional hazards and negative-binomial regression are not yet implemented.
- In Statis, ROC and AUC appear only within the machine-learning module, for two-class classifiers.

## Sources

- [Statis](https://rasan17.github.io/Statis/)
- [Statis-Gravity](https://rasan17.github.io/statis-gravity/)
- [Bayes-Estimation](https://rasan17.github.io/Bayes-Estimation/)
