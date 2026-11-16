---
id: kt:real-options
type: Framework
title: "Real Options: Valuing Managerial Flexibility in Capital Investment"
aliases: [real options analysis, real options valuation, real option theory, ROV, options approach to capital investment]
domain: corporate-finance
summary: >-
  An approach to capital budgeting that treats the right, but not the obligation, to defer, stage,
  expand, contract, switch or abandon a real investment as an option, and values that managerial
  flexibility with option-pricing logic so that a project is worth its static NPV plus the value of its options.
broader: [kt:capital-budgeting, kt:corporate-finance]
related: [kt:scenario-planning, kt:weighted-average-cost-of-capital, kt:sunk-cost]
relations:
  - {predicate: critiques, object: kt:net-present-value}
  - {predicate: dependsOn, object: kt:discounted-cash-flow}
  - {predicate: influencedBy, object: kt:black-scholes-model}
  - {predicate: influencedBy, object: kt:stewart-myers}
sources:
  - id: s1
    title: "Real Options: A Primer"
    publisher: Columbia Business School, Columbia Institute for Tele-Information (CITI)
    url: https://business.columbia.edu/sites/default/files-efs/imce-uploads/CITI/Articles/978-0-585-33314-4_1.pdf
    type: academic
    accessed: 2026-11-16
  - id: s2
    title: "Investment Opportunities as Real Options: Getting Started on the Numbers"
    publisher: Harvard Business Review (reprint 98404, hosted by Silicon Flatirons, University of Colorado)
    url: https://siliconflatirons.org/documents/initiatives/IRLEdayfour/Luehrman_Investment_Opportunities.pdf
    type: primary
    accessed: 2026-11-16
  - id: s3
    title: "Strategy as a Portfolio of Real Options"
    publisher: Harvard Business Review (HBR Store, product 98506)
    url: https://store.hbr.org/product/strategy-as-a-portfolio-of-real-options/98506
    type: practitioner-journal
    accessed: 2026-11-16
  - id: s4
    title: "Investment under Uncertainty"
    publisher: Princeton University Press
    url: https://press.princeton.edu/node/27002
    type: textbook
    accessed: 2026-11-16
  - id: s5
    title: "Expandability, Reversibility, and Optimal Capacity Choice"
    publisher: MIT Center for Energy and Environmental Policy Research (working paper 97-006)
    url: https://core.ac.uk/download/4414698.pdf
    type: academic
    accessed: 2026-11-16
  - id: s6
    title: "How Do CFOs Make Capital Budgeting and Capital Structure Decisions?"
    publisher: Journal of Applied Corporate Finance (author copy, Duke University)
    url: https://people.duke.edu/~charvey/Research/Published_Papers/P76_How_do_CFOs.pdf
    type: peer-reviewed
    accessed: 2026-11-16
created: 2026-11-16
---

# Real Options

Real options are the rights, without obligations, that a firm holds over real (non-financial) investments: to wait before committing capital, to invest in stages, to scale up or down, to switch inputs or outputs, or to walk away. Lenos Trigeorgis describes them as a collection of call and put options embedded in capital investment opportunities, where the underlying asset is the gross present value of the project's expected operating cash flows.[^s1] Real options analysis values that flexibility, so a project's **expanded (strategic) NPV** equals its conventional static NPV plus the value of the options that active management creates.[^s1]

## Origin

The idea grew out of applying financial option-pricing theory to corporate investment. Trigeorgis's survey attributes the concept of **growth options**, early investments that open the door to later opportunities, to Stewart Myers's 1977 work on corporate borrowing.[^s1] Avinash Dixit and Robert Pindyck's book *Investment under Uncertainty* (Princeton University Press, 1994) gave the field its economic foundation, arguing that most investment is irreversible, that the environment is uncertain, and that the option to delay until better information arrives therefore has value.[^s4] In the late 1990s Timothy Luehrman's *Harvard Business Review* articles translated the approach into tools managers could use with ordinary spreadsheets.[^s2][^s3]

## How it works

Trigeorgis catalogs the common types: the option to **defer** (a call on project value), to **stage** investment as a sequence of compound options, to **expand** (a call on extra capacity), to **contract** or temporarily shut down (a put on part of the project), to **abandon** for salvage value (a put), to **switch** inputs or outputs, and **growth options** such as R&D that are options on options.[^s1] Because flexibility lets managers capture upside while limiting downside, its value is asymmetric. In his stylized oil-project example, a project with a passive NPV of −4 reaches an expanded NPV of about 25 once the option to defer is valued with a binomial, risk-neutral model.[^s1]

Luehrman's framework maps a project onto a European call option. The present value of the assets to be acquired plays the role of the stock price, the required capital expenditure is the exercise price, the deferral period is time to expiry, and the riskiness of the asset returns is volatility.[^s2] He compresses these into two metrics: **NPVq**, the asset value divided by the present value of the expenditure discounted at the risk-free rate, and **cumulative volatility**, volatility times the square root of time. Together they locate any project in an "option space" whose values can be read from a Black-Scholes table.[^s2] His follow-up article argues that a strategy is financially more like a series of options than a single cash-flow projection, because executing it means making some decisions now and deferring others.[^s3]

Option logic also changes the investment rule itself. Dixit and Pindyck show that when investment is irreversible and the firm can wait, the investment threshold sits above the point where NPV equals zero, because exercising the option to invest gives up the value of waiting for information. Conversely, the ability to resell capital acts as a put that makes a firm more willing to invest than a naive NPV rule implies.[^s5]

## Evidence and critiques

Use in practice is real but mostly qualitative. In a survey of 392 chief financial officers conducted in February 1999, John Graham and Campbell Harvey found that more than a quarter of firms said they always or almost always incorporated real options when evaluating projects. The authors judged that the dominant corporate use was probably as a qualitative strategic-planning tool rather than as a precise valuation technique.[^s6]

The main criticisms concern inputs and assumptions. Luehrman himself stresses that the method gives numbers that are good enough rather than precise, that the volatility input requires judgment, that a synthetic option only approximates the real opportunity, and that Black-Scholes assumptions may not hold, for example when competitors can pre-empt a deferred investment.[^s2] Dixit and Pindyck's models rest on simplifying assumptions such as a single firm, exogenous prices and zero operating costs, which they flag as limitations.[^s5]

## In practice

Luehrman's Franklin Chemical example shows the stakes. A proposal for a $125 million plant with an option to spend $382 million on expansion in year 3 had a conventional NPV of about $0.1 million. Valuing phase 2 as a three-year call (with an assumed 40% annual volatility and a 5.5% risk-free rate) gave an option worth about $48.6 million, which, added to phase 1's $16.3 million NPV, put the whole proposal at roughly $64.9 million.[^s2]

## Connections

Real options is a branch of **capital budgeting** within **corporate finance**.[^s1] It **critiques** the static **net present value** rule for ignoring flexibility, yet **depends on** **discounted cash flow** analysis, since static NPV remains a necessary input and Luehrman's metrics are built from DCF spreadsheets.[^s1][^s2] It is **influenced by** the **Black-Scholes model** of option pricing and **influenced by** **Stewart Myers**, to whom its growth-option idea is traced.[^s1][^s2] Its emphasis on irreversible, **sunk-cost** commitments under uncertainty connects it to **scenario planning** and to the choice of discount rate, such as the **weighted average cost of capital**, that a firm applies to risky projects.[^s4][^s5]

## Sources

[^s1]: Lenos Trigeorgis, "Real Options: A Primer", in *Real Options: The New Investment Theory and its Implications for Telecommunications*, Columbia Institute for Tele-Information, Columbia Business School. https://business.columbia.edu/sites/default/files-efs/imce-uploads/CITI/Articles/978-0-585-33314-4_1.pdf (accessed 2026-11-16)
[^s2]: Timothy A. Luehrman, "Investment Opportunities as Real Options: Getting Started on the Numbers", *Harvard Business Review*, July–August 1998 (reprint 98404). https://siliconflatirons.org/documents/initiatives/IRLEdayfour/Luehrman_Investment_Opportunities.pdf (accessed 2026-11-16)
[^s3]: Timothy A. Luehrman, "Strategy as a Portfolio of Real Options", *Harvard Business Review*, September 1998. https://store.hbr.org/product/strategy-as-a-portfolio-of-real-options/98506 (accessed 2026-11-16)
[^s4]: Avinash K. Dixit and Robert S. Pindyck, *Investment under Uncertainty* (Princeton, NJ: Princeton University Press, 1994). https://press.princeton.edu/node/27002 (accessed 2026-11-16)
[^s5]: Avinash K. Dixit and Robert S. Pindyck, "Expandability, Reversibility, and Optimal Capacity Choice", MIT-CEEPR Working Paper 97-006, December 1997. https://core.ac.uk/download/4414698.pdf (accessed 2026-11-16)
[^s6]: John Graham and Campbell Harvey, "How Do CFOs Make Capital Budgeting and Capital Structure Decisions?", *Journal of Applied Corporate Finance* 15(1), Spring 2002. https://people.duke.edu/~charvey/Research/Published_Papers/P76_How_do_CFOs.pdf (accessed 2026-11-16)
