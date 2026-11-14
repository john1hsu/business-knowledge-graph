---
id: kt:discounted-cash-flow
type: Framework
title: "Discounted Cash Flow (DCF) Valuation: Valuing a Firm from Its Expected Future Cash Flows"
aliases: [DCF, DCF model, DCF analysis, discounted cash flow model, intrinsic valuation]
domain: corporate-finance
summary: >-
  An intrinsic (absolute) valuation method that estimates what a business, project or security is
  worth today as the present value of its expected future cash flows, discounted at a rate that
  reflects their risk, with a terminal value capturing cash flows beyond the explicit forecast period.
broader: [kt:corporate-finance, kt:business-valuation]
related: [kt:net-present-value, kt:leveraged-buyout, kt:goodwill, kt:customer-lifetime-value, kt:real-options]
relations:
  - {predicate: dependsOn, object: kt:free-cash-flow}
  - {predicate: dependsOn, object: kt:weighted-average-cost-of-capital}
  - {predicate: influencedBy, object: kt:john-burr-williams}
  - {predicate: influencedBy, object: kt:irving-fisher}
  - {predicate: contrastsWith, object: kt:relative-valuation}
sources:
  - id: s1
    title: "Principles of Finance, Section 11.3: Discounted Cash Flow (DCF) Model"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/11-3-discounted-cash-flow-dcf-model
    type: textbook
    accessed: 2026-11-14
  - id: s2
    title: "Valuation Approaches and Metrics: A Survey of the Theory and Evidence (author copy)"
    publisher: NYU Stern School of Business (Foundations and Trends in Finance)
    url: https://pages.stern.nyu.edu/~adamodar/pdfiles/papers/valuesurvey.pdf
    type: peer-reviewed
    accessed: 2026-11-14
  - id: s3
    title: "Valuation Approaches and Metrics: A Survey of the Theory and Evidence (bibliographic record)"
    publisher: Foundations and Trends in Finance (RePEc/IDEAS record)
    url: https://ideas.repec.org/a/now/fntfin/0500000013.html
    type: peer-reviewed
    accessed: 2026-11-14
  - id: s4
    title: "The Valuation of Cash Flow Forecasts: An Empirical Analysis"
    publisher: National Bureau of Economic Research (Working Paper 4724; Journal of Finance, 1995)
    url: https://nber.org/papers/w4724
    type: academic
    accessed: 2026-11-14
  - id: s5
    title: "Intrinsic Valuation (Chapter 2, author copy)"
    publisher: NYU Stern School of Business, faculty pages
    url: https://pages.stern.nyu.edu/~adamodar/pdfiles/DSV2/Ch2.pdf
    type: academic
    accessed: 2026-11-14
  - id: s6
    title: "Innovation Killers: How Financial Tools Destroy Your Capacity to Do New Things"
    publisher: Harvard Business School faculty publication page (Harvard Business Review, January 2008)
    url: https://www.hbs.edu/faculty/Pages/item.aspx?num=31559
    type: academic
    accessed: 2026-11-14
created: 2026-11-14
---

# Discounted Cash Flow (DCF) Valuation

Discounted cash flow (DCF) valuation estimates the value of a company, project or security as the present value of the cash it is expected to generate. It is an absolute or intrinsic method: the business is valued on its own forecasts rather than by comparison with the prices of similar firms.[^s1] The underlying principle is that an asset is worth the present value of its expected cash flows, discounted at a rate reflecting how risky those cash flows are, so larger and more predictable cash flows produce higher values.[^s5]

## Origin

DCF applies the present-value logic behind net present value to a whole enterprise. Aswath Damodaran's survey traces that logic from early interest tables through railroad investment analysis and Irving Fisher's work on interest, then to John Burr Williams, whose *The Theory of Investment Value* (1938) argued that a stock is worth the present value of all the dividends it will ever pay.[^s2] Williams's dividend discount model is the ancestor of today's free-cash-flow models; later variants replaced dividends with free cash flow to equity or to the firm, and added adjusted present value and excess-return (economic profit) formulations.[^s2][^s3]

## How it works

A DCF model has three parts. First, the analyst forecasts cash flows for an explicit period, typically several years, and discounts each one to the present. Second, because cash flows cannot be forecast forever, a **terminal value** captures everything beyond the horizon. Third, the present values are summed and, for a stock, divided by the shares outstanding.[^s1] OpenStax illustrates this with a hypothetical firm whose cash flow starts at $2.0 million, grows 3% a year and is discounted at 8%: about $9.9 million of value comes from six forecast years and the rest from the terminal value, giving roughly $13.55 a share against a $12 market price, so the stock looks cheap.[^s1]

Analysts must match cash flows to the discount rate. A **firm** (enterprise) valuation discounts free cash flow to the firm, measured before debt payments, at the weighted average cost of capital; an **equity** valuation discounts free cash flow to equity, measured after debt payments, at the cost of equity. Done consistently, both routes should reach the same equity value once debt and other non-equity claims are subtracted from firm value.[^s5] For the terminal value Damodaran favors either a liquidation value or a perpetual-growth formula, the next year's cash flow divided by the discount rate minus the growth rate. He cautions that growth used in that formula should not exceed the economy's growth rate and that a multiple applied to terminal-year earnings is inconsistent with intrinsic valuation.[^s5]

## Evidence and critiques

The best-known test is Steven Kaplan and Richard Ruback's study of 51 highly leveraged transactions completed between 1983 and 1989. Discounting management's own cash-flow forecasts produced values within 10%, on average, of the prices actually paid, and these DCF estimates did at least as well as valuations based on comparable companies and comparable transactions.[^s4] Wider evidence is mixed. Damodaran reports that most equity research valuations rely on multiples rather than DCF, and that studies of cross-sectional pricing tend to favor multiples while studies of how prices correct over time favor intrinsic value.[^s2]

The main criticism is sensitivity to inputs. OpenStax calls the model "garbage in, garbage out": unrealistic cash flows or discount rates distort the result, so it recommends using several methods together.[^s1] Damodaran notes that historical growth is a weak guide to future growth, management and analyst forecasts are biased, and regression betas are noisy, all of which feed straight into the value.[^s5] Clayton Christensen, Stephen Kaufman and Willy Shih argued in 2008 that DCF and NPV, as commonly used, understate the value of innovation because the alternative is usually modeled as a "do nothing" case in which current performance persists, even though competitors' moves will erode it.[^s6]

## In practice

OpenStax describes DCF as the tool analysts prefer for valuing companies and common stock, partly because cash flows are harder to manipulate through accounting choices than revenue or earnings, and notes it suits young firms that pay no dividends.[^s1] Because a few inputs drive the answer, practitioners test the value across discount rates and growth assumptions and cross-check it against trading and transaction multiples, the comparison Kaplan and Ruback ran in the buyout setting.[^s1][^s4] Damodaran's advice is that, with consistent assumptions, intrinsic and relative approaches should converge, so a gap between them traces to differing implicit assumptions, or to a whole peer group being mispriced.[^s2]

## Connections

DCF is a core tool of **corporate finance** and the main intrinsic method within **business valuation**.[^s2] It **depends on** **free cash flow**, which supplies the numerator, and on the **weighted average cost of capital**, which discounts firm-level cash flows.[^s5] It is **influenced by** **John Burr Williams**, whose dividend discount model it generalizes, and by **Irving Fisher**'s present-value reasoning.[^s2] It **contrasts with** **relative valuation**, which prices a firm off peers' multiples and assumes markets are right on average.[^s2] It is the firm-wide counterpart of **net present value**, was validated empirically on **leveraged buyouts**, and underpins valuations of **goodwill** and **customer lifetime value**; its trouble valuing flexibility and new ventures links it to **real options**.[^s4][^s6]

## Sources

[^s1]: OpenStax, *Principles of Finance*, Section 11.3, "Discounted Cash Flow (DCF) Model", Rice University. https://openstax.org/books/principles-finance/pages/11-3-discounted-cash-flow-dcf-model (accessed 2026-11-14)
[^s2]: Aswath Damodaran, "Valuation Approaches and Metrics: A Survey of the Theory and Evidence", author copy, NYU Stern School of Business. https://pages.stern.nyu.edu/~adamodar/pdfiles/papers/valuesurvey.pdf (accessed 2026-11-14)
[^s3]: Aswath Damodaran, "Valuation Approaches and Metrics: A Survey of the Theory and Evidence", *Foundations and Trends in Finance* 1(8), 2007, pp. 693–784, doi:10.1561/0500000013. https://ideas.repec.org/a/now/fntfin/0500000013.html (accessed 2026-11-14)
[^s4]: Steven N. Kaplan and Richard S. Ruback, "The Valuation of Cash Flow Forecasts: An Empirical Analysis", NBER Working Paper 4724 (1994); *Journal of Finance* 50(4), 1995, pp. 1059–1094. https://nber.org/papers/w4724 (accessed 2026-11-14)
[^s5]: Aswath Damodaran, "Intrinsic Valuation", Chapter 2 (author copy), NYU Stern School of Business. https://pages.stern.nyu.edu/~adamodar/pdfiles/DSV2/Ch2.pdf (accessed 2026-11-14)
[^s6]: Clayton M. Christensen, Stephen P. Kaufman and Willy C. Shih, "Innovation Killers: How Financial Tools Destroy Your Capacity to Do New Things", *Harvard Business Review* 86(1), January 2008. https://www.hbs.edu/faculty/Pages/item.aspx?num=31559 (accessed 2026-11-14)
