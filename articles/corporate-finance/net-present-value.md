---
id: kt:net-present-value
type: Metric
title: "Net Present Value: Discounting Future Cash Flows to Evaluate Investments"
aliases: [NPV, NPV rule, net present value method, net present worth]
domain: corporate-finance
summary: >-
  The present value of an investment's expected cash inflows minus the present value of its cash
  outflows, discounted at a rate reflecting the cost of capital and risk; the standard capital
  budgeting rule is to accept projects with a positive NPV because they are expected to add value to the firm.
broader: [kt:capital-budgeting, kt:corporate-finance]
related: [kt:discounted-cash-flow, kt:free-cash-flow, kt:real-options, kt:customer-lifetime-value, kt:innovators-dilemma]
relations:
  - {predicate: dependsOn, object: kt:weighted-average-cost-of-capital}
  - {predicate: influencedBy, object: kt:irving-fisher}
  - {predicate: contrastsWith, object: kt:internal-rate-of-return}
  - {predicate: alternativeTo, object: kt:payback-period}
sources:
  - id: s1
    title: "Principles of Finance, Section 16.2: Net Present Value (NPV) Method"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/16-2-net-present-value-npv-method
    type: textbook
    accessed: 2026-11-13
  - id: s2
    title: "Principles of Accounting, Volume 2, Section 11.5: Compare and Contrast Non-Time Value-Based Methods and Time Value-Based Methods in Capital Investment Decisions"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-managerial-accounting/pages/11-5-compare-and-contrast-non-time-value-based-methods-and-time-value-based-methods-in-capital-investment-decisions
    type: textbook
    accessed: 2026-11-13
  - id: s3
    title: "The Theory of Interest (1930), Part II: Second Approximation to the Theory of Interest"
    publisher: Library of Economics and Liberty (Liberty Fund)
    url: https://www.econlib.org/library/YPDBooks/Fisher/fshToI6.html
    type: primary
    accessed: 2026-11-13
  - id: s4
    title: "The Theory and Practice of Corporate Finance: Evidence from the Field"
    publisher: Journal of Financial Economics (Scholars@Duke record)
    url: https://scholars.duke.edu/publication/774079
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s5
    title: "How Do CFOs Make Capital Budgeting and Capital Structure Decisions?"
    publisher: Journal of Applied Corporate Finance (author copy, Duke University)
    url: https://people.duke.edu/~charvey/Research/Published_Papers/P76_How_do_CFOs.pdf
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s6
    title: "Innovation Killers: How Financial Tools Destroy Your Capacity to Do New Things"
    publisher: Harvard Business School faculty publication page (Harvard Business Review, January 2008)
    url: https://www.hbs.edu/faculty/Pages/item.aspx?num=31559
    type: academic
    accessed: 2026-11-13
  - id: s7
    title: "Finance Theory and Financial Strategy"
    publisher: Interfaces (RePEc/IDEAS record)
    url: https://ideas.repec.org/a/inm/orinte/v14y1984i1p126-137.html
    type: peer-reviewed
    accessed: 2026-11-13
created: 2026-11-13
---

# Net Present Value

Net present value (NPV) is the present value of a project's cash inflows minus the present value of its cash outflows. Because money received at different dates is not directly comparable, every cash flow is first discounted back to today; the difference tells a firm whether the investment is expected to add value.[^s1] The decision rule is simple: accept projects with a positive NPV and reject those with a negative one, since a positive NPV is the amount by which the project should raise the value of the firm.[^s1]

## Origin

NPV has no single inventor, but its economic logic was set out by Irving Fisher in *The Theory of Interest* (1930). Fisher valued alternative income streams from the same asset by discounting them at the market interest rate. In his illustration, a piece of land is worth more as a mine than as a farm or a forest at 5%, but the ranking flips when the rate changes, so the best use depends on the discount rate. He called the owner's choice of the highest-valued option the principle of maximum present worth, and argued that borrowing and lending only reshape the timing of an income stream, not its present value.[^s3] That separation of the investment choice from the financing and consumption choice is the foundation of the modern NPV rule.

## How it works

The analyst forecasts the incremental cash flows of a project, discounts each at a rate reflecting the cost of funds, and sums them, subtracting the initial outlay. OpenStax's example is a sporting-goods retailer weighing a $16,000 embroidery machine that returns $2,000 in year 1, $4,000 in year 2 and $5,000 in each of years 3 to 6. At a 9% cost of funds the NPV is about $2,835.63, so the purchase should go ahead.[^s1] In theory the discount rate should be the firm's cost of capital, but because that rate is hard to pin down, analysts draw an **NPV profile** showing NPV across many rates. In the same example NPV is $10,000 at 0% and falls to zero at roughly 14%, so the machine is acceptable as long as the cost of capital stays below about 14%.[^s1]

The rate at which NPV equals zero is the internal rate of return (IRR). A positive NPV therefore always coincides with an IRR above the rate used for discounting, and for independent projects the two methods give the same accept-or-reject answer. For mutually exclusive projects they can rank alternatives differently, because NPV measures dollars of value while IRR measures a percentage return, and large differences in project size can reverse the order.[^s2] Simpler screens such as the payback period and the accounting rate of return ignore the time value of money, so OpenStax recommends them only for initial screening, with NPV and IRR used to choose among the remaining options.[^s2]

## Evidence and critiques

NPV is the textbook standard and is widely used in practice. In a survey of 392 chief financial officers conducted in February 1999, 74.9% said they always or almost always used NPV and 75.7% used IRR, while 56.7% used payback; large firms were significantly more likely than small ones to rely on NPV.[^s5] The peer-reviewed version of the study confirms that large firms lean heavily on present-value methods and the capital asset pricing model, but also finds that many firms discount new projects at a company-wide rate instead of one matched to project risk.[^s4]

Critics focus on how the rule is applied. OpenStax notes that NPV depends on an estimated required return, is hard for non-specialists to interpret, and does not by itself tell a capital-constrained firm which of several positive-NPV projects to fund.[^s1][^s2] Stewart Myers argued in 1984 that finance theory had made little impact on strategic planning and needed extending to reconcile financial and strategic analysis, a line of thought that led to real-options valuation.[^s7] Clayton Christensen, Stephen Kaufman and Willy Shih argued in 2008 that DCF and NPV, as commonly used, understate the value of innovation, largely because managers compare a new investment against a "do nothing" baseline that wrongly assumes current performance will persist while competitors move.[^s6]

## In practice

A firm deciding whether to buy equipment costing $30,000 that saves $10,000 a year for five years, at an 8% required return, finds a present value of inflows of $39,927 and an NPV of $9,927; the IRR of 19.86% leads to the same accept decision.[^s2] In practice analysts pair the point estimate with sensitivity tests on the discount rate and cash-flow forecasts, because those inputs, not the arithmetic, drive the answer.[^s1]

## Connections

NPV is the central decision rule of **capital budgeting** and a core tool of **corporate finance**.[^s1] It **depends on** a discount rate, usually the **weighted average cost of capital** for projects of average risk, and it is **influenced by** **Irving Fisher**, whose principle of maximum present worth supplies its logic.[^s3][^s4] It **contrasts with** the **internal rate of return**, which can rank mutually exclusive projects differently, and is an **alternative to** the **payback period**, a cruder screen that ignores the time value of money.[^s2] Applied to a whole firm's **free cash flow**, the same arithmetic becomes a **discounted cash flow** valuation; applied to a customer it yields **customer lifetime value**. Its limits in valuing flexibility and new ventures connect it to **real options** and to the **innovator's dilemma**.[^s6][^s7]

## Sources

[^s1]: OpenStax, *Principles of Finance*, Section 16.2, "Net Present Value (NPV) Method", Rice University. https://openstax.org/books/principles-finance/pages/16-2-net-present-value-npv-method (accessed 2026-11-13)
[^s2]: OpenStax, *Principles of Accounting, Volume 2: Managerial Accounting*, Section 11.5, "Compare and Contrast Non-Time Value-Based Methods and Time Value-Based Methods in Capital Investment Decisions", Rice University. https://openstax.org/books/principles-managerial-accounting/pages/11-5-compare-and-contrast-non-time-value-based-methods-and-time-value-based-methods-in-capital-investment-decisions (accessed 2026-11-13)
[^s3]: Irving Fisher, *The Theory of Interest* (New York: Macmillan, 1930), Part II, "Second Approximation to the Theory of Interest", Library of Economics and Liberty. https://www.econlib.org/library/YPDBooks/Fisher/fshToI6.html (accessed 2026-11-13)
[^s4]: John R. Graham and Campbell R. Harvey, "The Theory and Practice of Corporate Finance: Evidence from the Field", *Journal of Financial Economics* 60(2–3), 2001, pp. 187–243, doi:10.1016/S0304-405X(01)00044-7. https://scholars.duke.edu/publication/774079 (accessed 2026-11-13)
[^s5]: John Graham and Campbell Harvey, "How Do CFOs Make Capital Budgeting and Capital Structure Decisions?", *Journal of Applied Corporate Finance* 15(1), Spring 2002. https://people.duke.edu/~charvey/Research/Published_Papers/P76_How_do_CFOs.pdf (accessed 2026-11-13)
[^s6]: Clayton M. Christensen, Stephen P. Kaufman and Willy C. Shih, "Innovation Killers: How Financial Tools Destroy Your Capacity to Do New Things", *Harvard Business Review* 86(1), January 2008. https://www.hbs.edu/faculty/Pages/item.aspx?num=31559 (accessed 2026-11-13)
[^s7]: Stewart C. Myers, "Finance Theory and Financial Strategy", *Interfaces* 14(1), 1984, pp. 126–137, doi:10.1287/inte.14.1.126. https://ideas.repec.org/a/inm/orinte/v14y1984i1p126-137.html (accessed 2026-11-13)
