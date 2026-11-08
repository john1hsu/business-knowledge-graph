---
id: kt:free-cash-flow
type: Metric
title: Free Cash Flow
aliases: [FCF, free cash flow to the firm, FCFF]
domain: accounting-and-reporting
summary: >-
  A cash-based performance and liquidity measure, usually computed as cash flow from operating
  activities minus capital expenditures, that shows how much cash a business generates after
  funding the investment needed to sustain and grow its operations.
broader: [kt:financial-statement-analysis, kt:corporate-finance]
related: [kt:accrual-accounting, kt:agency-costs, kt:discounted-cash-flow, kt:leveraged-buyout]
relations:
  - {predicate: dependsOn, object: kt:statement-of-cash-flows}
  - {predicate: regulatedBy, object: kt:non-gaap-financial-measures}
  - {predicate: contrastsWith, object: kt:ebitda}
  - {predicate: influencedBy, object: kt:michael-c-jensen}
sources:
  - id: s1
    title: "Principles of Finance, Section 5.6: Operating Cash Flow and Free Cash Flow to the Firm (FCFF)"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/5-6-operating-cash-flow-and-free-cash-flow-to-the-firm-fcff
    type: textbook
    accessed: 2026-11-08
  - id: s2
    title: "Agency Cost of Free Cash Flow, Corporate Finance, and Takeovers"
    publisher: American Economic Review (via SSRN)
    url: https://papers.ssrn.com/abstract=99580
    type: primary
    accessed: 2026-11-08
  - id: s3
    title: "Free Cash Flow and Stockholder Gains in Going Private Transactions"
    publisher: Journal of Finance (via RePEc/IDEAS)
    url: https://ideas.repec.org/a/bla/jfinan/v44y1989i3p771-787.html
    type: peer-reviewed
    accessed: 2026-11-08
  - id: s4
    title: "Amazon.com, Inc. Form 10-K for the fiscal year ended December 31, 2025"
    publisher: U.S. Securities and Exchange Commission (EDGAR)
    url: https://www.sec.gov/Archives/edgar/data/1018724/000101872426000004/amzn-20251231.htm
    type: primary
    accessed: 2026-11-08
  - id: s5
    title: "CDW Corporation response to SEC staff comment letter on Form 10-K for fiscal 2022 (CORRESP)"
    publisher: U.S. Securities and Exchange Commission (EDGAR)
    url: https://www.sec.gov/Archives/edgar/data/1402057/000140205723000123/filename1.htm
    type: primary
    accessed: 2026-11-08
created: 2026-11-08
---

# Free Cash Flow

**Free cash flow (FCF)** is the cash a business has left after paying for its operations and for the capital investments needed to keep and expand its productive assets. In its most common textbook form it equals operating cash flow minus capital expenditures; the remainder is what the firm can use to repay debt, pay dividends or build working capital for growth.[^s1] Because it is derived from the statement of cash flows rather than from accrual-based net income, analysts and investors use it to judge how well a company manages cash and whether it can fund its own operating and capital needs.[^s1]

## Origin

Cash-flow measures are as old as cash-flow statements, but free cash flow became a central idea in finance through Michael C. Jensen's 1986 paper in the *American Economic Review*. Jensen defined it as cash in excess of what a firm needs to fund all its positive-value investment opportunities, and argued that conflicts between managers and shareholders over payouts and firm size are sharpest where such surplus cash is large.[^s2] His theory explained why debt can discipline managers by committing future cash to creditors, why diversification programs often destroy value, and why takeover activity clustered in cash-rich industries such as oil, tobacco and broadcasting.[^s2] Practitioners later adopted the label for a simpler accounting calculation, so the term now carries both a theoretical meaning (surplus cash) and an operational one (cash after capital spending).

## How it is calculated

OpenStax builds the measure in two steps. Operating cash flow, the first section of the cash-flow statement, adjusts operating income for depreciation, taxes and changes in net working capital; free cash flow then subtracts capital expenditures. In the textbook's worked example, a sporting-goods retailer with $53,600 of operating cash flow and $13,600 of capital spending has $40,000 of free cash flow.[^s1] OpenStax also notes that managers can shift operating cash flow by changing customer payment terms, collection practices or supplier terms, which moves the timing of cash without changing profit.[^s1]

OpenStax labels this measure free cash flow to the firm, the cash available before any payments to the firm's capital providers.[^s1] Companies, however, define their reported figure in their own way: Amazon, for instance, subtracts "purchases of property and equipment, net of proceeds from sales and incentives" from operating cash flow.[^s4]

## Regulation and disclosure

Free cash flow is not defined by US GAAP, so in SEC filings it is a non-GAAP measure that must be reconciled to the nearest GAAP figure. The SEC staff treats it as a liquidity measure and scrutinizes adjustments. In a 2023 comment letter on CDW's fiscal 2022 Form 10-K, the staff questioned whether certain financing-related payments in CDW's reconciliation were consistent with Regulation S-K Item 10(e), which bars excluding charges or liabilities that require cash settlement from such measures. CDW defended its approach but acknowledged that free cash flow lacks a uniform definition and agreed to explain its calculation more clearly.[^s5] CDW reported adjusted free cash flow of $1,292.7 million for fiscal 2022, against $476.7 million for 2021.[^s5]

## Evidence and critiques

The strongest empirical support concerns Jensen's agency version. Lehn and Poulsen studied 263 going-private transactions from 1980 to 1987 and found a significant relationship between undistributed cash flow and both the decision to go private and the premium paid to shareholders, with the effect strongest in 1984–1987 deals and in firms whose managers owned little equity.[^s3] That evidence helped make free cash flow a standard screen for leveraged-buyout candidates.

The operational measure has well-known limits. Amazon's own filing cautions that free cash flow leaves out parts of the cash-flow statement, is not a measure of truly discretionary residual cash, and ignores principal debt repayments and acquisition spending; it tells investors to treat the figure only as a complement to the full statements.[^s4] Because capital expenditures are partly discretionary, a firm can lift free cash flow by underinvesting, while a firm in a heavy build-out phase can show low free cash flow despite strong operations. Inconsistent definitions across companies also undermine comparability.[^s5]

## In practice

Amazon states that its financial focus is long-term, sustainable growth in free cash flow.[^s4] Its fiscal 2025 numbers show how investment cycles move the metric: operating cash flow rose from $115.9 billion in 2024 to $139.5 billion in 2025, but net purchases of property and equipment jumped from $77.7 billion to $128.3 billion, so free cash flow fell from $38.2 billion to $11.2 billion (as of FY2025).[^s4] Reading the decline as weakness, rather than as a deliberate capital-spending surge, would misread the business.

## Connections

Free cash flow sits within financial statement analysis and corporate finance, and depends on the statement of cash flows for its inputs.[^s1] It complements accrual accounting by showing the cash reality behind accrual-based earnings, and it contrasts with EBITDA, which, unlike free cash flow, makes no deduction for capital expenditures or changes in working capital.[^s1] As a non-GAAP measure it is governed by SEC rules on non-GAAP disclosure.[^s5] Jensen's work ties it to agency costs and to the leveraged buyout as a device for forcing surplus cash out of firms,[^s2][^s3] and investors use it as an input to their overall evaluation of an investment, including discounted cash flow valuation.[^s1]

## Sources
[^s1]: Julie Dahlquist and Rainford Knight, *Principles of Finance*, OpenStax, 2022, Section 5.6 "Operating Cash Flow and Free Cash Flow to the Firm (FCFF)". https://openstax.org/books/principles-finance/pages/5-6-operating-cash-flow-and-free-cash-flow-to-the-firm-fcff (accessed 2026-11-08)
[^s2]: Michael C. Jensen, "Agency Cost of Free Cash Flow, Corporate Finance, and Takeovers", *American Economic Review* 76(2), May 1986. https://papers.ssrn.com/abstract=99580 (accessed 2026-11-08)
[^s3]: Kenneth Lehn and Annette Poulsen, "Free Cash Flow and Stockholder Gains in Going Private Transactions", *Journal of Finance* 44(3), 1989, pp. 771–787. https://ideas.repec.org/a/bla/jfinan/v44y1989i3p771-787.html (accessed 2026-11-08)
[^s4]: Amazon.com, Inc., Form 10-K for fiscal year 2025, MD&A Overview and "Non-GAAP Financial Measures". https://www.sec.gov/Archives/edgar/data/1018724/000101872426000004/amzn-20251231.htm (accessed 2026-11-08)
[^s5]: CDW Corporation, response letter to SEC Division of Corporation Finance staff comments on Form 10-K for fiscal 2022, July 26, 2023. https://www.sec.gov/Archives/edgar/data/1402057/000140205723000123/filename1.htm (accessed 2026-11-08)
