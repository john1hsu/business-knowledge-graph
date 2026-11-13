---
id: kt:capital-structure
type: Concept
title: "Capital Structure: The Mix of Debt and Equity Financing"
aliases: [capital structure, financing mix, debt-equity mix, leverage policy]
domain: corporate-finance
summary: >-
  The proportions of debt and equity a firm uses to finance its assets, and the body of theory
  (trade-off, pecking order, market timing) that tries to explain how firms choose that mix and
  whether it affects firm value.
broader: [kt:corporate-finance]
related: [kt:modigliani-miller-theorem, kt:weighted-average-cost-of-capital, kt:agency-costs, kt:leveraged-buyout, kt:dividend-policy, kt:dupont-analysis]
relations:
  - {predicate: hasPart, object: kt:trade-off-theory-of-capital-structure}
  - {predicate: hasPart, object: kt:pecking-order-theory}
  - {predicate: hasPart, object: kt:market-timing-theory-of-capital-structure}
  - {predicate: influencedBy, object: kt:information-asymmetry}
  - {predicate: measuredBy, object: kt:debt-to-equity-ratio}
  - {predicate: exemplifiedBy, object: kt:netflix-business-model-shift}
sources:
  - id: s1
    title: "17.5 Optimal Capital Structure"
    publisher: "OpenStax, Principles of Finance 2e (Knight and Dahlquist)"
    url: https://openstax.org/books/principles-finance-2e/pages/17-5-optimal-capital-structure
    type: textbook
    accessed: 2026-11-13
  - id: s2
    title: "The Capital Structure Puzzle (Journal of Finance 39(3), 1984)"
    publisher: IDEAS/RePEc record of the American Finance Association article
    url: https://ideas.repec.org/a/bla/jfinan/v39y1984i3p575-92.html
    type: primary
    accessed: 2026-11-13
  - id: s3
    title: "The theory and practice of corporate finance: evidence from the field"
    publisher: "Journal of Financial Economics 60(2-3), 2001 (Duke Scholars record)"
    url: https://scholars.duke.edu/publication/774079
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s4
    title: "Market Timing and Capital Structure"
    publisher: "The Journal of Finance 57(1), 2002 (author copy, NYU Stern)"
    url: https://pages.stern.nyu.edu/%7Ejwurgler/papers/capstruct.pdf
    type: peer-reviewed
    accessed: 2026-11-13
created: 2026-11-13
---

# Capital Structure: The Mix of Debt and Equity Financing

**Capital structure** is the combination of debt and equity a company uses to fund its operations and assets. Firms typically set a *target* capital structure, and because the cost of each source depends on its market value, the target is expressed in market-value weights of debt and equity, the same weights that feed the weighted average cost of capital.[^s1] The central managerial question is whether some mix of borrowing and shareholder funding creates more value than another, and if so, what drives it.

## Origin

Modern thinking starts from the Modigliani-Miller result that, in a frictionless market, financing mix does not change firm value. Everything since has been an attempt to explain which frictions make it matter. In his 1984 American Finance Association presidential address, "The Capital Structure Puzzle", Stewart C. Myers framed the debate as a contest between two explanations: a static trade-off theory and a pecking order theory rooted in asymmetric information.[^s2] That framing still organizes textbooks and research.

## How it works: the main theories

**Trade-off theory.** Debt carries a tax advantage because interest is deductible, creating an *interest tax shield*. But more debt also raises the probability of financial distress, meaning difficulty meeting debt obligations. Distress has direct costs, such as fees to lawyers, consultants, appraisers and auctioneers, and indirect costs, such as customers and suppliers walking away.[^s1] At low leverage the tax shield dominates; past some point, expected distress costs offset the extra tax savings, so firm value peaks at an interior optimum. Firms with higher potential distress costs reach that point sooner and should carry less debt. OpenStax notes that pinning down the exact balance in practice is difficult, if not impossible.[^s1]

**Pecking order theory.** Myers argued that firms prefer internal funds first, then debt, and issue equity only as a last resort; a firm's debt ratio therefore reflects its accumulated need for outside financing rather than a target. He linked this ordering to simple asymmetric-information models, in which outside investors read a new stock issue as a sign that managers think the shares are overvalued.[^s2]

**Market timing theory.** Malcolm Baker and Jeffrey Wurgler found that firms issue equity when their market-to-book ratios are high and repurchase when they are low, and that these choices leave a very persistent imprint: for book leverage, roughly 73% of the effect remained after ten years, and the effect on market leverage looked permanent.[^s4] They concluded that capital structure is largely the cumulative outcome of past attempts to time the equity market, with no fixed optimal leverage.[^s4]

## Evidence and critiques

No single theory wins. In a survey of 392 chief financial officers, John Graham and Campbell Harvey found some support for both the pecking order and trade-off views. Executives said financial flexibility and credit ratings were their main concerns when issuing debt, and earnings-per-share dilution and recent stock-price run-ups mattered most when issuing equity.[^s3] They found little evidence that managers consciously weigh several mechanisms prominent in academic models, including asset substitution, asymmetric information, transaction costs, free cash flow and personal taxes.[^s3]

Baker and Wurgler's persistence result is hard to square with the trade-off theory, which predicts that temporary shocks should be reversed as firms move back toward target, and it also fits poorly with standard pecking order predictions.[^s4] They could not tell whether timing reflects rational responses to shifting adverse-selection costs or managers exploiting mispricing, though long-run return evidence leaned toward mispricing.[^s4] A practical critique of the trade-off model is that firms tolerate drift away from target: because rebalancing is costly, a firm aiming for 22.5% debt that sits at 23.1% would normally treat itself as on target.[^s1]

## In practice

Leverage varies sharply by industry. Using data compiled by Aswath Damodaran as of December 2020, OpenStax reports debt at about 6.67% of capital for online retail versus about 63.62% for rubber and tires, differences that also move each industry's weighted average cost of capital.[^s1] Netflix illustrates debt-financed growth: it funded much of its original content production by selling debt rather than issuing new shares.[^s1] Practitioners therefore set targets by looking at the tax shield they can use, the stability of their cash flows, peer leverage, the credit rating they want to protect, and how much spare borrowing capacity they want for flexibility, the factors CFOs themselves rank highest.[^s3]

## Connections

Capital structure is a core topic within **corporate finance** (`broader`). The **Modigliani-Miller theorem** supplies its irrelevance benchmark, and the three explanatory theories, the **trade-off theory**, the **pecking order theory** and the **market timing theory**, are modeled as parts of the concept (`hasPart`).[^s2][^s4] The pecking order is driven by **information asymmetry** between managers and investors (`influencedBy`).[^s2] Because the market-value weights of debt and equity set the **weighted average cost of capital**, financing choices flow straight into valuation.[^s1] The leverage term of **DuPont analysis** and the **debt-to-equity ratio** (`measuredBy`) are the usual ways the resulting mix is read from financial statements. **Agency costs** of debt and equity, **dividend policy** (which determines how much internal funding is retained) and **leveraged buyouts** (which push leverage to an extreme) are closely related decisions.[^s2][^s3] Netflix's content-financing strategy is an example (`exemplifiedBy`).[^s1]

## Sources

[^s1]: Rainford Knight and Julie Dahlquist, "17.5 Optimal Capital Structure", *Principles of Finance 2e*, OpenStax. https://openstax.org/books/principles-finance-2e/pages/17-5-optimal-capital-structure (accessed 2026-11-13)
[^s2]: Stewart C. Myers, "The Capital Structure Puzzle", *Journal of Finance* 39(3): 575–592, 1984 (IDEAS/RePEc record). https://ideas.repec.org/a/bla/jfinan/v39y1984i3p575-92.html (accessed 2026-11-13)
[^s3]: John R. Graham and Campbell R. Harvey, "The theory and practice of corporate finance: evidence from the field", *Journal of Financial Economics* 60(2–3): 187–243, 2001 (Duke Scholars). https://scholars.duke.edu/publication/774079 (accessed 2026-11-13)
[^s4]: Malcolm Baker and Jeffrey Wurgler, "Market Timing and Capital Structure", *The Journal of Finance* 57(1): 1–32, 2002 (author copy). https://pages.stern.nyu.edu/%7Ejwurgler/papers/capstruct.pdf (accessed 2026-11-13)
