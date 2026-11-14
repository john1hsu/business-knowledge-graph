---
id: kt:ebitda
type: Metric
title: "EBITDA: Earnings Before Interest, Taxes, Depreciation and Amortization"
aliases: [EBITDA, earnings before interest taxes depreciation and amortization, adjusted EBITDA]
domain: accounting-and-reporting
summary: >-
  A non-GAAP earnings measure that adds interest, income taxes, depreciation and amortization back
  to net income, used as a rough proxy for operating cash generation, a basis for valuation
  multiples and the core input to leverage ratios and loan covenants.
broader: [kt:financial-statement-analysis, kt:non-gaap-financial-measures]
related: [kt:accrual-accounting, kt:gaap, kt:leveraged-buyout, kt:enterprise-value-multiples]
relations:
  - {predicate: contrastsWith, object: kt:free-cash-flow}
  - {predicate: regulatedBy, object: kt:regulation-g}
  - {predicate: dependsOn, object: kt:income-statement}
  - {predicate: appliesTo, object: kt:debt-covenant}
sources:
  - id: s1
    title: "Non-GAAP Financial Measures: Compliance and Disclosure Interpretations"
    publisher: U.S. Securities and Exchange Commission, Division of Corporation Finance
    url: https://www.sec.gov/corpfin/non-gaap-financial-measures
    type: government
    accessed: 2026-11-14
  - id: s2
    title: "Putting EBITDA In Perspective: Ten Critical Failings Of EBITDA As The Principal Determinant Of Cash Flow"
    publisher: Moody's Investors Service (Special Comment, via Universidad del CEMA)
    url: https://ucema.edu.ar/u/jd/Inversiones/Articulos/Moodys_Putting_Ebitda_into_perspective.pdf
    type: organization
    accessed: 2026-11-14
  - id: s3
    title: "Contractual Complexity in Debt Agreements: The Case of EBITDA"
    publisher: Columbia Law School, Law and Economic Studies (working paper)
    url: https://law-economic-studies.law.columbia.edu/sites/default/files/content/DeFontenay%20et%20al_Contractual%20Complexity%20in%20Debt%20Agreements%20The%20Case%20of%20EBITDA_Draft_May%202021.pdf
    type: academic
    accessed: 2026-11-14
  - id: s4
    title: "EBITDA Add-backs in Debt Contracting: A Step Too Far?"
    publisher: Federal Reserve Bank of St. Louis Working Paper 2022-029 (via RePEc/IDEAS)
    url: https://ideas.repec.org/p/fip/fedlwp/94811.html
    type: academic
    accessed: 2026-11-14
  - id: s5
    title: "Uber Announces Results for Fourth Quarter and Full Year 2025"
    publisher: Uber Technologies, Inc. (press release via Business Wire)
    url: https://www.businesswire.com/news/home/20260204947622/en/Uber-Announces-Results-for-Fourth-Quarter-and-Full-Year-2025
    type: primary
    accessed: 2026-11-14
created: 2026-11-14
---

# EBITDA: Earnings Before Interest, Taxes, Depreciation and Amortization

**EBITDA** stands for earnings before interest, taxes, depreciation and amortization. In the definition the US Securities and Exchange Commission uses, "earnings" means net income as presented under GAAP, and EBITDA adds back interest, income taxes, depreciation and amortization to that figure.[^s1] Stripping out financing costs, tax regimes and non-cash charges for past capital spending is meant to show the earning power of a company's operations in a way that can be compared across firms with different capital structures, tax positions and asset ages. It is not defined by US GAAP, so in SEC filings it is a non-GAAP measure.[^s1]

## Origin

Before the 1980s, credit analysts generally judged a company's ability to service debt with EBIT, or operating income. According to a 2000 Moody's special comment by Pamela Stumpp, EBITDA spread during the leveraged-buyout boom of the 1980s, when buyout sponsors argued that depreciation and amortization are non-cash charges and that the cash they represent is therefore available to pay lenders.[^s2] Its use then widened in stages: first to neutralize goodwill amortization after acquisitions, then to assess companies near bankruptcy, then to businesses with long-lived assets, and eventually to companies of every kind.[^s2]

## How it is calculated and regulated

The basic calculation starts from net income and adds back interest expense, the income-tax provision, and depreciation and amortization. SEC staff guidance sets the rules for public filers. A company presenting EBITDA as a performance measure must reconcile it to net income, not to operating income, because EBITDA adjusts for items that operating income does not include; it also may not present EBITDA per share.[^s1] Any measure computed differently must carry a distinct label such as "Adjusted EBITDA".[^s1] Plain EBIT and EBITDA enjoy one exception: Regulation S-K normally bars non-GAAP liquidity measures from excluding charges that must be settled in cash, but EBIT and EBITDA are expressly exempted.[^s1] Adjusted variants get no such exemption, although a company may still disclose a covenant-defined Adjusted EBITDA when the covenant is material to its liquidity.[^s1]

## Adjusted EBITDA

Most reported figures are adjusted versions that remove further items. Uber's definition, for example, starts from net income and excludes, among other things, stock-based compensation, impairments, restructuring charges, acquisition-related costs, income or losses from equity-method investments, and other items it considers not indicative of ongoing performance.[^s5] For full-year 2025 Uber reported Adjusted EBITDA of $8.73 billion, income from operations of $5.57 billion and net income attributable to the company of $10.05 billion (as of FY2025).[^s5] That net income exceeded Adjusted EBITDA shows how far the measure can sit from GAAP earnings in either direction, depending on which non-operating gains and charges are excluded.[^s5]

## Evidence and critiques

Moody's listed ten critical failings of EBITDA as a cash-flow measure. Among them: it ignores changes in working capital, it ignores the reinvestment needed to sustain assets, it says nothing about earnings quality, it is a weak basis for comparing acquisition multiples, and it can drift from reality through aggressive adjustments.[^s2] Moody's concluded the measure is most defensible for low-rated borrowers at the bottom of the business cycle and least appropriate for higher-rated credits.[^s2]

Research on loan contracts shows how flexible the definition has become. Badawi, Dyreng, de Fontenay and Hills extracted EBITDA definitions from nearly 4,000 US syndicated credit agreements signed between 2000 and 2016. The definitions ranged from a single sentence to thousands of words of add-backs, and became more permissive over the sample period, especially in larger, more-levered and private-equity-sponsored deals.[^s3] More permissive definitions were associated with fewer covenant violations and with credit spreads roughly 43 basis points higher per standard deviation of permissiveness.[^s3] A Federal Reserve Bank of St. Louis working paper by Faria-e-Castro and co-authors found that non-GAAP add-backs in covenant EBITDA rose over time and were associated with a higher likelihood of delinquency, default and rating downgrades. Its explanation was that customized EBITDA weakens lead arrangers' incentive and ability to monitor borrowers.[^s4]

## In practice

EBITDA is used in three main ways: as a headline profitability metric in earnings releases, as the denominator in enterprise-value multiples for valuation, and as the base for leverage and coverage covenants such as debt-to-EBITDA in leveraged loans.[^s2][^s3] Careful users read the reconciliation to net income, check which add-backs a company or credit agreement allows, and compare EBITDA with cash-flow measures before drawing conclusions.[^s1][^s2]

## Connections

EBITDA belongs to financial statement analysis and to the wider family of non-GAAP financial measures, and is derived from the income statement by adding back items to GAAP net income.[^s1] It is regulated by the SEC's Regulation G and Item 10(e) of Regulation S-K, whose staff interpretations govern its labeling and reconciliation.[^s1] It contrasts with free cash flow, which subtracts the capital spending and working-capital needs that EBITDA ignores,[^s2] and it reverses accrual accounting's allocation of asset costs through depreciation and amortization. Its history is tied to the leveraged buyout,[^s2] and today it is the anchor of debt covenants and of enterprise-value multiples.[^s3][^s4]

## Sources
[^s1]: U.S. Securities and Exchange Commission, Division of Corporation Finance, "Non-GAAP Financial Measures" Compliance and Disclosure Interpretations, Questions 102.09, 103.01 and 103.02 (last updated December 13, 2022). https://www.sec.gov/corpfin/non-gaap-financial-measures (accessed 2026-11-14)
[^s2]: Pamela M. Stumpp, "Putting EBITDA In Perspective: Ten Critical Failings Of EBITDA As The Principal Determinant Of Cash Flow", Moody's Investors Service Special Comment, June 2000. https://ucema.edu.ar/u/jd/Inversiones/Articulos/Moodys_Putting_Ebitda_into_perspective.pdf (accessed 2026-11-14)
[^s3]: Adam B. Badawi, Scott D. Dyreng, Elisabeth de Fontenay and Robert W. Hills, "Contractual Complexity in Debt Agreements: The Case of EBITDA", working paper draft, May 2021. https://law-economic-studies.law.columbia.edu/sites/default/files/content/DeFontenay%20et%20al_Contractual%20Complexity%20in%20Debt%20Agreements%20The%20Case%20of%20EBITDA_Draft_May%202021.pdf (accessed 2026-11-14)
[^s4]: Miguel Faria-e-Castro, Radhakrishnan Gopalan, Avantika Pal, Juan M. Sánchez and Vijay Yerramilli, "EBITDA Add-backs in Debt Contracting: A Step Too Far?", Federal Reserve Bank of St. Louis Working Paper 2022-029. https://ideas.repec.org/p/fip/fedlwp/94811.html (accessed 2026-11-14)
[^s5]: Uber Technologies, Inc., "Uber Announces Results for Fourth Quarter and Full Year 2025", press release, February 4, 2026. https://www.businesswire.com/news/home/20260204947622/en/Uber-Announces-Results-for-Fourth-Quarter-and-Full-Year-2025 (accessed 2026-11-14)
