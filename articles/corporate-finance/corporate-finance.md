---
id: kt:corporate-finance
type: Field
title: "Corporate Finance: Investment, Financing and Payout Decisions"
aliases: [corporate finance, business finance, corporate financial management]
domain: corporate-finance
summary: >-
  The branch of finance that studies how firms decide which long-term assets to invest in, how to fund
  them with debt and equity, how to manage short-term working capital and how much cash to return to
  owners, with the aim of maximizing the value of the firm.
broader: [kt:finance]
related: [kt:weighted-average-cost-of-capital, kt:dividend-policy, kt:free-cash-flow, kt:corporate-governance, kt:agency-costs, kt:shareholder-primacy]
relations:
  - {predicate: hasPart, object: kt:capital-budgeting}
  - {predicate: hasPart, object: kt:capital-structure}
  - {predicate: hasPart, object: kt:working-capital}
  - {predicate: influencedBy, object: kt:modigliani-miller-theorem}
  - {predicate: influencedBy, object: kt:michael-c-jensen}
  - {predicate: exemplifiedBy, object: kt:apple-inc}
sources:
  - id: s1
    title: "Principles of Finance, Section 1.1: What Is Finance?"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/1-1-what-is-finance
    type: textbook
    accessed: 2026-11-11
  - id: s2
    title: "Introduction to Business, Section 16.1: The Role of Finance and the Financial Manager"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/introduction-business/pages/16-1-the-role-of-finance-and-the-financial-manager
    type: textbook
    accessed: 2026-11-11
  - id: s3
    title: "The Cost of Capital, Corporation Finance and the Theory of Investment"
    publisher: American Economic Review (AEA Top 20 reprint)
    url: https://www.aeaweb.org/aer/top20/48.3.261-297.pdf
    type: primary
    accessed: 2026-11-11
  - id: s4
    title: "The Theory and Practice of Corporate Finance: Evidence from the Field"
    publisher: Journal of Financial Economics (Scholars@Duke record)
    url: https://scholars.duke.edu/publication/774079
    type: peer-reviewed
    accessed: 2026-11-11
  - id: s5
    title: "Theory of the Firm: Managerial Behavior, Agency Costs and Ownership Structure"
    publisher: Journal of Financial Economics (SSRN abstract)
    url: https://papers.ssrn.com/abstract=94043
    type: primary
    accessed: 2026-11-11
  - id: s6
    title: "The Error at the Heart of Corporate Leadership"
    publisher: Harvard Business School faculty publication page (Harvard Business Review)
    url: https://www.hbs.edu/faculty/Pages/item.aspx?num=52623
    type: practitioner-journal
    accessed: 2026-11-11
  - id: s7
    title: "Apple Inc. Form 10-K for the fiscal year ended September 27, 2025"
    publisher: U.S. Securities and Exchange Commission (EDGAR)
    url: https://www.sec.gov/Archives/edgar/data/320193/000032019325000079/aapl-20250927.htm
    type: primary
    accessed: 2026-11-11
created: 2026-11-11
---

# Corporate Finance: Investment, Financing and Payout Decisions

Corporate finance (also called business finance) is the part of finance concerned with how managers apply financial principles to raise the value of a firm while operating under risk. OpenStax places it alongside investments and financial markets and institutions as one of the three broad areas of the discipline, and frames its central question as where a firm's cash comes from and where it goes.[^s1] In most companies the work sits with the chief financial officer, who oversees both accounting, which assembles financial data, and financial management, which uses that data to make decisions ranging from daily cash monitoring to whether to build a new plant.[^s2]

## The core decisions

Textbook treatments usually divide the field into three linked decisions.[^s1]

- **Capital budgeting** chooses which long-term assets and projects to fund by forecasting the size, timing and risk of their cash flows.[^s1]
- **Capital structure** sets the mix of long-term debt and equity used to pay for those assets.[^s1]
- **Working capital management** handles short-term assets and liabilities such as credit terms, inventory and short-term borrowing.[^s1]

A fourth question, how much cash to pay back to owners through dividends or share buybacks, follows from the first three and is often treated separately as payout policy. The organizing objective in the standard account is to maximize the firm's value to its owners, measured by share price for a listed company; OpenStax cautions that chasing short-term profit, for example by cutting research spending, can destroy that long-run value.[^s2] The risk-return trade-off runs through every decision: riskier commitments must offer higher expected returns.[^s2]

## Intellectual origins

Modern corporate finance grew out of a 1958 article by Franco Modigliani and Merton Miller. They argued that once asset returns are uncertain, profit maximization loses operational meaning, and proposed market-value maximization as the workable criterion instead. Their Proposition I then showed that, in a frictionless market enforced by arbitrage, a firm's total value does not depend on how it is financed.[^s3] That irrelevance result turned later research toward the frictions that make financing matter, such as taxes, bankruptcy costs and conflicts of interest. Michael Jensen and William Meckling's 1976 paper supplied the conflicts: it defined agency costs, tied them to the separation of ownership and control, and analysed the costs created by outside debt and equity, making ownership structure itself a corporate-finance variable.[^s5]

## Evidence and critiques

Survey evidence shows how far practice matches theory. John Graham and Campbell Harvey's 2001 survey of 392 CFOs found that large firms rely heavily on present-value methods and the capital asset pricing model, while smaller firms lean more on payback. Many firms used a company-wide discount rate rather than one matched to each project's risk. On financing, executives cared most about financial flexibility and credit ratings when issuing debt, and about earnings dilution and recent share-price gains when issuing equity. The answers gave only partial support to the pecking-order and trade-off theories.[^s4]

The field's value-maximization objective is also contested. Joseph Bower and Lynn Paine argue in Harvard Business Review (2017) that the agency-theory view of shareholders as owners has accountability gaps. They note that shareholders owe no duties to the company, enjoy limited liability and can exit at will. They propose that boards focus on the long-run health of the enterprise instead.[^s6]

## In practice

Apple's fiscal 2025 annual report shows all of these decisions at once. As of September 27, 2025, the company held about $132.4 billion in cash, cash equivalents and marketable securities while carrying about $91.3 billion of term debt and $8.0 billion of commercial paper. In fiscal 2025 it spent about $89.3 billion on share repurchases and $15.4 billion on dividends, and on May 1, 2025 it announced a new buyback program of up to $100 billion.[^s7] Choosing to fund operations partly with debt while returning large sums to shareholders is a joint capital-structure and payout decision of exactly the kind the field studies.

## Connections

Corporate finance is a branch of `kt:finance` and has three main parts: `kt:capital-budgeting`, `kt:capital-structure` and `kt:working-capital`, as the textbook split describes.[^s1] It is `influencedBy` `kt:modigliani-miller-theorem`, whose irrelevance result set the field's research agenda,[^s3] and by `kt:michael-c-jensen`, whose agency analysis links it to `kt:agency-costs` and `kt:corporate-governance`.[^s5] Its discount rate is usually the `kt:weighted-average-cost-of-capital` applied to `kt:free-cash-flow`, and its payout question is covered in `kt:dividend-policy`.[^s4] The debate over its objective connects it to `kt:shareholder-primacy`,[^s6] and Apple (`kt:apple-inc`) is a worked example.[^s7]

## Sources
[^s1]: OpenStax, *Principles of Finance*, Section 1.1 "What Is Finance?", Rice University. https://openstax.org/books/principles-finance/pages/1-1-what-is-finance (accessed 2026-11-11)
[^s2]: OpenStax, *Introduction to Business*, Section 16.1 "The Role of Finance and the Financial Manager", Rice University. https://openstax.org/books/introduction-business/pages/16-1-the-role-of-finance-and-the-financial-manager (accessed 2026-11-11)
[^s3]: Franco Modigliani and Merton H. Miller, "The Cost of Capital, Corporation Finance and the Theory of Investment", *American Economic Review* 48(3), 1958. https://www.aeaweb.org/aer/top20/48.3.261-297.pdf (accessed 2026-11-11)
[^s4]: John R. Graham and Campbell R. Harvey, "The Theory and Practice of Corporate Finance: Evidence from the Field", *Journal of Financial Economics* 60(2-3), 2001, pp. 187-243. https://scholars.duke.edu/publication/774079 (accessed 2026-11-11)
[^s5]: Michael C. Jensen and William H. Meckling, "Theory of the Firm: Managerial Behavior, Agency Costs and Ownership Structure", *Journal of Financial Economics* 3(4), 1976. https://papers.ssrn.com/abstract=94043 (accessed 2026-11-11)
[^s6]: Joseph L. Bower and Lynn S. Paine, "The Error at the Heart of Corporate Leadership", *Harvard Business Review* 95(3), May-June 2017. https://www.hbs.edu/faculty/Pages/item.aspx?num=52623 (accessed 2026-11-11)
[^s7]: Apple Inc., Form 10-K for the fiscal year ended September 27, 2025, U.S. Securities and Exchange Commission. https://www.sec.gov/Archives/edgar/data/320193/000032019325000079/aapl-20250927.htm (accessed 2026-11-11)
