---
id: kt:capital-budgeting
type: Practice
title: "Capital Budgeting: Evaluating and Selecting Long-Term Investment Projects"
aliases: [capital investment decisions, capital investment analysis, investment appraisal, project appraisal, capital expenditure planning]
domain: corporate-finance
summary: >-
  The process by which a firm identifies, evaluates, ranks and approves investments in long-lived
  assets such as plant, equipment, new products and new markets, using screening criteria and
  valuation methods (payback, NPV, IRR, profitability index) under limits on funds and time.
broader: [kt:corporate-finance]
related: [kt:discounted-cash-flow, kt:real-options, kt:free-cash-flow, kt:decision-making, kt:overconfidence-bias]
relations:
  - {predicate: measuredBy, object: kt:net-present-value}
  - {predicate: measuredBy, object: kt:internal-rate-of-return}
  - {predicate: measuredBy, object: kt:payback-period}
  - {predicate: dependsOn, object: kt:weighted-average-cost-of-capital}
  - {predicate: influencedBy, object: kt:joel-dean}
sources:
  - id: s1
    title: "Principles of Accounting, Volume 2, Section 11.1: Describe Capital Investment Decisions and How They Are Applied"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-managerial-accounting/pages/11-1-describe-capital-investment-decisions-and-how-they-are-applied
    type: textbook
    accessed: 2026-11-16
  - id: s2
    title: "Principles of Finance, Chapter 16: How Companies Think about Investing — Why It Matters"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/16-why-it-matters
    type: textbook
    accessed: 2026-11-16
  - id: s3
    title: "Principles of Finance, Section 16.4: Alternative Methods"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/16-4-alternative-methods
    type: textbook
    accessed: 2026-11-16
  - id: s4
    title: "Principles of Finance, Section 16.5: Choosing between Projects"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/16-5-choosing-between-projects
    type: textbook
    accessed: 2026-11-16
  - id: s5
    title: "Capital Allocation and Delegation of Decision-Making Authority within Firms"
    publisher: National Bureau of Economic Research (Working Paper 17370)
    url: https://nber.org/papers/w17370
    type: academic
    accessed: 2026-11-16
  - id: s6
    title: "Delusions of Success: How Optimism Undermines Executives' Decisions"
    publisher: Harvard Business School Working Knowledge (archive)
    url: https://hbswk.hbs.edu/archive/delusions-of-success-how-optimism-undermines-executives-decisions
    type: academic
    accessed: 2026-11-16
  - id: s7
    title: "Capital Budgeting: Top-Management Policy on Plant, Equipment, and Product Development"
    publisher: Columbia University Press (catalogue record, Austrian Academy of Sciences library)
    url: https://oeaw.ac.at/resources/Record/9780231879316
    type: primary
    accessed: 2026-11-16
created: 2026-11-16
---

# Capital Budgeting

Capital budgeting is the process a firm uses to decide which long-term investments to make: spending money now on fixed assets in the expectation of earning more cash later.[^s2] OpenStax describes it as the use of funds to acquire long-lived assets, such as replacement machinery, facility expansions, new products or entry into new markets, and distinguishes these capital expenditures from operating expenses that merely keep current operations running.[^s1] Typical examples range from a carmaker buying an assembly-line robot or an airline adding a plane to a pharmaceutical company funding vaccine research.[^s2] Because the outlays are large, tie up capital for years and have long-run effects that are hard to forecast, the choices shape a firm's future more than most routine decisions.[^s1]

## Origin

Discounting future income long predates the term, but capital budgeting as a named top-management discipline is usually traced to Joel Dean's 1951 Columbia University Press monograph *Capital Budgeting: Top-Management Policy on Plant, Equipment, and Product Development*.[^s7] The subtitle captures the idea that investment choices about plant, equipment and product development are a policy question for senior management rather than a series of isolated engineering approvals.[^s7]

## How it works

OpenStax lays out a five-step process: determine the firm's capital needs and which are most urgent; identify limits on money and time (liquidity, funds locked in non-liquid assets, staff commitments, financing timelines); set baseline criteria such as a minimum return or maximum payback; evaluate alternatives; and decide.[^s1] Evaluation proceeds in two passes. A **screening decision** removes options that fail the minimum criteria, and a **preference decision** ranks the survivors; the final call then weighs non-financial factors too.[^s1] In OpenStax's sewing-studio example, the owner has $50,000 and requires a payback within three years and a 20% return. A $45,000 machine with a 2.5-year payback and 25% return passes, while a $55,000 machine with an 18% return fails on both cash and return and is dropped.[^s1]

The analytical toolkit combines simple and discounted-cash-flow measures. Payback and accounting rate of return are quick screens; net present value (NPV) and internal rate of return (IRR) account for the time value of money.[^s1] Refinements fix specific weaknesses. The **discounted payback period** discounts each cash flow before finding breakeven, but still has no objective cut-off and ignores cash flows after breakeven.[^s3] The **profitability index** (PI), the present value of inflows divided by the present value of outflows, always agrees with NPV on accept-or-reject because it exceeds 1 exactly when NPV is positive.[^s3] The **modified IRR** compounds inflows at the cost of capital, avoiding IRR's reinvestment assumption and its possible multiple solutions, though it still ignores project scale.[^s3]

## Choosing between projects

Capital budgeting becomes harder when projects compete. For mutually exclusive projects, the firm should pick the one with the highest NPV, even if a smaller rival shows a higher IRR.[^s4] When lives differ, analysts compare options on a common horizon with a replacement chain or convert each NPV into an equivalent annual annuity, both of which assume the project can be repeated on similar terms.[^s4] Under **capital rationing**, where the budget cannot fund every positive-NPV project, ranking by NPV alone can mislead. In OpenStax's example, seven projects need $430 million against a $200 million budget; choosing the three projects with the highest PI uses exactly the $200 million and adds $78 million of NPV, more than an NPV-ranked selection would.[^s4]

## Evidence and critiques

Practice departs from the textbook. In a survey of more than 1,000 CEOs and CFOs reported in 2011, Graham, Harvey and Puri found that most companies allocate capital across divisions using the NPV rule but also the divisional manager's reputation, the timing of a project's cash flows and senior management's gut feel, and that corporate politics and "corporate socialism" weigh more heavily outside the United States.[^s5] CEOs delegated investment and capital-allocation decisions more readily than merger decisions, and delegated more in large or complex firms.[^s5]

A second critique concerns the forecasts that feed every method. Dan Lovallo and Daniel Kahneman argue that planners naturally take an "inside view", building forecasts from a project's own goals and scenarios, which produces systematically optimistic estimates reinforced by organizational pressure.[^s6] Their remedy is reference-class forecasting: find comparable past projects, map their distribution of outcomes and pull the intuitive estimate toward the reference-class mean, more strongly when past forecasts have correlated poorly with results.[^s6] OpenStax likewise stresses that cash-flow projections are estimates to be revisited when conditions change, citing oil companies after the 2020 price collapse and firms that cut capital spending during COVID-19.[^s4]

## In practice

Capital budgets respond to uncertainty and shocks. OpenStax notes that after the 2016 Brexit vote, uncertainty slowed UK capital spending, with plans to expand into new markets cut the most, and that Volkswagen reduced its R&D budget and set aside about €9 billion for compliance costs after its emissions scandal.[^s1]

## Connections

Capital budgeting is the investment-decision branch of **corporate finance**.[^s2] Its outcomes are **measured by** **net present value**, **internal rate of return** and the **payback period**, alongside the profitability index and modified IRR.[^s1][^s3] It **depends on** a discount rate, normally the **weighted average cost of capital** for projects of average risk, and on forecasts of incremental **free cash flow**, the same inputs used in **discounted cash flow** valuation.[^s3][^s4] Its treatment as a top-management policy is **influenced by** **Joel Dean**.[^s7] Because standard methods struggle to value flexibility, it connects to **real options**; and because forecasts are biased and allocation is political, it connects to organizational **decision making** and **overconfidence bias**.[^s5][^s6]

## Sources

[^s1]: OpenStax, *Principles of Accounting, Volume 2: Managerial Accounting*, Section 11.1, "Describe Capital Investment Decisions and How They Are Applied", Rice University. https://openstax.org/books/principles-managerial-accounting/pages/11-1-describe-capital-investment-decisions-and-how-they-are-applied (accessed 2026-11-16)
[^s2]: OpenStax, *Principles of Finance*, Chapter 16, "How Companies Think about Investing: Why It Matters", Rice University. https://openstax.org/books/principles-finance/pages/16-why-it-matters (accessed 2026-11-16)
[^s3]: OpenStax, *Principles of Finance*, Section 16.4, "Alternative Methods", Rice University. https://openstax.org/books/principles-finance/pages/16-4-alternative-methods (accessed 2026-11-16)
[^s4]: OpenStax, *Principles of Finance*, Section 16.5, "Choosing between Projects", Rice University. https://openstax.org/books/principles-finance/pages/16-5-choosing-between-projects (accessed 2026-11-16)
[^s5]: John R. Graham, Campbell R. Harvey and Manju Puri, "Capital Allocation and Delegation of Decision-Making Authority within Firms", NBER Working Paper 17370, 2011 (published in *Journal of Financial Economics* 115(3), 2015). https://nber.org/papers/w17370 (accessed 2026-11-16)
[^s6]: Dan Lovallo and Daniel Kahneman, "Delusions of Success: How Optimism Undermines Executives' Decisions", *Harvard Business Review*, July 2003; HBS Working Knowledge archive. https://hbswk.hbs.edu/archive/delusions-of-success-how-optimism-undermines-executives-decisions (accessed 2026-11-16)
[^s7]: Joel Dean, *Capital Budgeting: Top-Management Policy on Plant, Equipment, and Product Development* (New York: Columbia University Press, 1951), doi:10.7312/dean90552. https://oeaw.ac.at/resources/Record/9780231879316 (accessed 2026-11-16)
