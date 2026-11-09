---
id: kt:weighted-average-cost-of-capital
type: Metric
title: Weighted Average Cost of Capital
aliases: [WACC, blended cost of capital, firm-wide cost of capital]
domain: corporate-finance
summary: >-
  A firm's blended required return on its capital, computed by weighting the after-tax cost of debt,
  the cost of preferred stock and the cost of common equity by their shares of the capital structure;
  it is widely used as the discount rate or hurdle rate for investments of average company risk.
broader: [kt:cost-of-capital, kt:corporate-finance]
related: [kt:modigliani-miller-theorem, kt:capital-structure, kt:discounted-cash-flow, kt:free-cash-flow, kt:economic-value-added]
relations:
  - {predicate: dependsOn, object: kt:capital-asset-pricing-model}
  - {predicate: appliesTo, object: kt:capital-budgeting}
  - {predicate: influencedBy, object: kt:modigliani-miller-theorem}
  - {predicate: contrastsWith, object: kt:hurdle-rate}
sources:
  - id: s1
    title: "Principles of Finance, Section 17.3: Calculating the Weighted Average Cost of Capital"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/17-3-calculating-the-weighted-average-cost-of-capital
    type: textbook
    accessed: 2026-11-09
  - id: s2
    title: "Principles of Accounting, Volume 2, Section 12.3: Evaluate an Operating Segment or a Project Using Return on Investment, Residual Income, and Economic Value Added"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-managerial-accounting/pages/12-3-evaluate-an-operating-segment-or-a-project-using-return-on-investment-residual-income-and-economic-value-added
    type: textbook
    accessed: 2026-11-09
  - id: s3
    title: "The Theory and Practice of Corporate Finance: Evidence from the Field"
    publisher: Journal of Financial Economics (Scholars@Duke record)
    url: https://scholars.duke.edu/publication/774079
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s4
    title: "How Do CFOs Make Capital Budgeting and Capital Structure Decisions?"
    publisher: Journal of Applied Corporate Finance (author copy, Duke University)
    url: https://people.duke.edu/~charvey/Research/Published_Papers/P76_How_do_CFOs.pdf
    type: primary
    accessed: 2026-11-09
  - id: s5
    title: "The Cross-Section of Hurdle Rates for Capital Budgeting: An Empirical Analysis of Survey Data"
    publisher: National Bureau of Economic Research, Working Paper 16770
    url: https://www.nber.org/papers/w16770.pdf
    type: academic
    accessed: 2026-11-09
  - id: s6
    title: "The WACC Fallacy: The Real Effects of Using a Unique Discount Rate"
    publisher: Journal of Finance (RePEc/EconPapers record)
    url: https://econpapers.repec.org/RePEc:bla:jfinan:v:70:y:2015:i:3:p:1253-1285
    type: peer-reviewed
    accessed: 2026-11-09
created: 2026-11-09
---

# Weighted Average Cost of Capital

The weighted average cost of capital (WACC) is the average rate of return a company must pay its providers of capital, taken together. It blends the cost of each financing source (debt, preferred stock and common equity) according to how much of the firm's capital that source supplies.[^s1] OpenStax's managerial accounting text describes it as the average a company expects to pay to fund its assets and growth with a mix of debt and equity.[^s2] Because it represents the return investors as a group require, WACC is the default discount rate in corporate valuation and the benchmark that an investment of ordinary company risk has to beat.[^s5]

## Origin

WACC has no single inventor. It became standard practice along with present-value capital budgeting and the capital asset pricing model (CAPM), which gave firms a common way to estimate the cost of equity. Graham and Harvey surveyed 392 chief financial officers in February 1999. They found that large firms relied heavily on present-value methods and CAPM, while smaller firms more often used the payback period.[^s3] Of those CFOs, 73.5% always or almost always used CAPM to estimate the cost of equity, and about three-quarters always or almost always used net present value or internal rate of return.[^s4]

## How it works

The general formula is WACC = D% × r_d(1 − T) + P% × r_pfd + E% × r_e. D%, P% and E% are the weights of debt, preferred stock and common equity, and must add up to 100%. r_d(1 − T) is the after-tax cost of debt, r_pfd the cost of preferred stock and r_e the cost of common equity. A company with no preferred stock simply drops the middle term.[^s1] The debt cost is multiplied by (1 − T) because interest is tax-deductible, which makes borrowing cheaper than its stated rate.[^s1]

OpenStax works through a hypothetical company, Bluebonnet Industries, with roughly 24% debt at a 4.99% after-tax cost and 75.6% equity. When the cost of equity is estimated with CAPM at 13.4%, WACC comes out at 11.33%. When it is estimated with a constant-growth dividend model at 14.24%, WACC is 11.97%. The choice of equity model alone moves the answer by more than half a percentage point.[^s1] Some practitioners weight on net debt (total debt minus cash) instead of total debt. Using Apple's 2020 figures, OpenStax shows total debt of $112.4 billion falling to net debt of about $74.4 billion after subtracting $38.0 billion of cash.[^s1]

WACC also serves as the capital charge in performance measures. Economic value added (EVA) is after-tax income minus invested capital times WACC. OpenStax's example combines 45% debt at 8% with 55% equity at 9.8% to get a 9% WACC, under which a $1.5 million investment earning $150,000 after tax yields a positive EVA of $15,000.[^s2]

## Evidence and critiques

The most serious criticism concerns how WACC gets used, not how it is calculated. A firm-wide WACC is the right rate only for projects as risky as the firm's average assets. In Graham and Harvey's survey, close to 60% of CFOs said they would evaluate a new project with a single company-wide rate, although 51% also said they always or almost always used a risk-matched rate.[^s4] Their peer-reviewed paper describes the reliance on firm risk instead of project risk as surprisingly common.[^s3] Philipp Krüger, Augustin Landier and David Thesmar (2015) measured what this costs. In diversified firms, divisions with higher beta than the parent invest relatively more and safer divisions invest less, which fits managers applying one discount rate across the whole firm. Acquirers whose beta is lower than their target's also earn worse announcement returns.[^s6]

The second criticism is that estimates are imprecise. Beta and the market risk premium vary from one data provider to another. OpenStax shows one company's cost of equity ranging from 9.20% to 21.08% depending on those inputs, so it treats WACC as an estimate that needs judgment, not a precise number.[^s1] Finally, firms do not use WACC alone when deciding on investments. In an October 2003 CFO survey, 71.8% of the 117 respondents to the question said their hurdle rate equals their WACC. Even so, average hurdle rates (mean 14.8%) carried a premium over CAPM-based cost of capital that made up about half the rate, and proxies for the option to wait explained far more of the differences in hurdle rates across firms than CAPM did.[^s5]

## Connections

WACC is a specific measure within the broader idea of the **cost of capital** and a core tool of **corporate finance**.[^s1] It is computed from the firm's **capital structure** weights, with debt entering after tax.[^s1] It is **influenced by** the **Modigliani-Miller theorem**, the graph's node on whether financing mix changes a firm's average cost of capital. It **depends on** the **capital asset pricing model** for the equity component[^s4] and is **applied to** **capital budgeting**, where it discounts **free cash flow** in a **discounted cash flow** valuation and serves as the capital charge in **economic value added**.[^s2][^s3] It **contrasts with** a **hurdle rate**, the cutoff firms actually apply, which surveys show often sits above WACC.[^s5]

## Sources

[^s1]: OpenStax, *Principles of Finance*, Section 17.3, "Calculating the Weighted Average Cost of Capital", Rice University. https://openstax.org/books/principles-finance/pages/17-3-calculating-the-weighted-average-cost-of-capital (accessed 2026-11-09)
[^s2]: OpenStax, *Principles of Accounting, Volume 2: Managerial Accounting*, Section 12.3, "Evaluate an Operating Segment or a Project Using Return on Investment, Residual Income, and Economic Value Added", Rice University. https://openstax.org/books/principles-managerial-accounting/pages/12-3-evaluate-an-operating-segment-or-a-project-using-return-on-investment-residual-income-and-economic-value-added (accessed 2026-11-09)
[^s3]: John R. Graham and Campbell R. Harvey, "The Theory and Practice of Corporate Finance: Evidence from the Field", *Journal of Financial Economics* 60(2–3), 2001, pp. 187–243, doi:10.1016/S0304-405X(01)00044-7. https://scholars.duke.edu/publication/774079 (accessed 2026-11-09)
[^s4]: John Graham and Campbell Harvey, "How Do CFOs Make Capital Budgeting and Capital Structure Decisions?", *Journal of Applied Corporate Finance* 15(1), Spring 2002. https://people.duke.edu/~charvey/Research/Published_Papers/P76_How_do_CFOs.pdf (accessed 2026-11-09)
[^s5]: Ravi Jagannathan, Iwan Meier and Vefa Tarhan, "The Cross-Section of Hurdle Rates for Capital Budgeting: An Empirical Analysis of Survey Data", NBER Working Paper 16770, February 2011. https://www.nber.org/papers/w16770.pdf (accessed 2026-11-09)
[^s6]: Philipp Krüger, Augustin Landier and David Thesmar, "The WACC Fallacy: The Real Effects of Using a Unique Discount Rate", *Journal of Finance* 70(3), 2015, pp. 1253–1285, doi:10.1111/jofi.12250. https://econpapers.repec.org/RePEc:bla:jfinan:v:70:y:2015:i:3:p:1253-1285 (accessed 2026-11-09)
