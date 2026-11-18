---
id: kt:internal-rate-of-return
type: Metric
title: "Internal Rate of Return: The Discount Rate That Sets NPV to Zero"
aliases: [IRR, IRR method, IRR rule, internal rate of return method]
domain: corporate-finance
summary: >-
  The discount rate at which the present value of an investment's cash inflows equals the present
  value of its outflows, so that its net present value is zero; under the IRR rule a project is
  accepted when its IRR exceeds the cost of capital.
broader: [kt:capital-budgeting, kt:corporate-finance]
related: [kt:discounted-cash-flow, kt:payback-period, kt:venture-capital, kt:leveraged-buyout]
relations:
  - {predicate: contrastsWith, object: kt:net-present-value}
  - {predicate: dependsOn, object: kt:weighted-average-cost-of-capital}
  - {predicate: alternativeTo, object: kt:modified-internal-rate-of-return}
  - {predicate: alternativeTo, object: kt:payback-period}
sources:
  - id: s1
    title: "Principles of Finance, Section 16.3: Internal Rate of Return (IRR) Method"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/16-3-internal-rate-of-return-irr-method
    type: textbook
    accessed: 2026-11-18
  - id: s2
    title: "The Theory and Practice of Corporate Finance: Evidence from the Field"
    publisher: Journal of Financial Economics 60(2-3), 187-243 (Scholars@Duke record)
    url: https://scholars.duke.edu/display/pub774079
    type: peer-reviewed
    accessed: 2026-11-18
  - id: s3
    title: "How CFOs Really Practice Finance"
    publisher: MIT Sloan Management Review
    url: https://sloanreview.mit.edu/?p=9977
    type: practitioner-journal
    accessed: 2026-11-18
  - id: s4
    title: "Internal Rate of Return: A Cautionary Tale"
    publisher: McKinsey & Company (McKinsey on Finance / McKinsey Quarterly)
    url: https://www.mckinsey.com/capabilities/strategy-and-corporate-finance/our-insights/internal-rate-of-return-a-cautionary-tale
    type: consultancy
    accessed: 2026-11-18
  - id: s5
    title: "Modified Internal Rate of Return"
    publisher: ACCA (Association of Chartered Certified Accountants)
    url: https://accaglobal.com/gb/en/student/exam-support-resources/professional-exams-study-resources/p4/technical-articles/Modified-internal-rate-return.html
    type: organization
    accessed: 2026-11-18
  - id: s6
    title: "Average Internal Rate of Return and Investment Decisions: A New Perspective"
    publisher: CEFIN Working Paper No. 21, University of Modena and Reggio Emilia (RePEc record)
    url: https://econpapers.repec.org/RePEc:mod:wcefin:0021
    type: academic
    accessed: 2026-11-18
created: 2026-11-18
---

# Internal Rate of Return

The **internal rate of return (IRR)** is the discount rate that makes the present value of a project's cash inflows equal to the present value of its cash outflows. Put differently, it is the rate at which the project's net present value (NPV) is exactly zero.[^s1] Because it states a project's payoff as an annual percentage, IRR is one of the two dominant tools of capital budgeting, alongside NPV.[^s1][^s3]

## How it works

The IRR rule compares the computed rate with the firm's cost of capital. A project whose IRR is above that hurdle should be accepted, and one whose IRR is below it should be rejected.[^s1] OpenStax illustrates the method with a sporting-goods retailer weighing a $16,000 embroidery machine. The machine returns $2,000 in year one, $4,000 in year two and $5,000 in each of years three to six. Its IRR works out to 14.09%, so the purchase makes sense only if the firm can raise capital for less than about 14%.[^s1]

No algebraic formula solves for IRR in general. Analysts once found it by trial and error, testing discount rates until NPV reached zero; financial calculators and spreadsheet functions now do the search almost instantly.[^s1] Graphically, the IRR is where a project's NPV profile, a plot of NPV against the discount rate, crosses the horizontal axis.[^s1]

## Why managers like it

The measure is easy to interpret and explain, and investors are used to thinking in annual percentage returns.[^s1] McKinsey's Kelleher and MacCormack argued in 2004 that this familiarity is its main attraction: executives can set an IRR beside a loan rate or other known rates without further explanation.[^s4] Survey evidence confirms its reach. In a survey of 392 chief financial officers published in 2001, Graham and Harvey found that large firms relied heavily on present-value methods, while small firms were more likely to use the payback criterion.[^s2] MIT Sloan Management Review's summary of the study reports that a majority of CFOs used IRR and NPV, with the payback period ranking third.[^s3] Citing the same research, McKinsey put the share of CFOs who always or almost always used IRR at about three-quarters.[^s4]

## Evidence and critiques

Finance texts have warned about IRR's weaknesses for decades, and they fall into four groups.[^s4]

- **Multiple or missing solutions.** When negative cash flows occur in more than one period, the NPV profile can cross zero more than once.[^s1] OpenStax's Olympic-facility case shows this: an outlay at the start, a large inflow in year one and a further outlay in year two produce two IRRs.[^s1]
- **Scale blindness.** As a percentage, IRR ignores project size, so it can rank a small project above a much larger one that creates more value.[^s1][^s4]
- **Reinvestment assumption.** IRR implicitly assumes interim cash flows are reinvested at the IRR itself, which is often unrealistic. This matters little for a single accept-or-reject decision but distorts rankings among projects.[^s1][^s5]
- **Relative, not absolute, value.** IRR shows a rate of return but not how much wealth the project adds, which is what NPV measures.[^s5]

The reinvestment problem can be severe in practice. In one industrial company McKinsey studied, 23 major projects approved over five years showed an average IRR of 77%. When interim cash flows were assumed to earn only the cost of capital, the average return fell to 16%, and the top-ranked project slipped to tenth place.[^s4] The distortion is largest for projects whose IRRs are far above the cost of capital, which are the ones managers favour most.[^s4]

Several fixes have been proposed. The **modified IRR (MIRR)** compounds interim inflows at the cost of capital, which removes the multiple-answer problem and gives a more realistic rate. In ACCA's three-year example, a project with a 14.92% IRR has an MIRR of 13.03% at a 10% cost of capital.[^s5] ACCA notes that MIRR is still a percentage and so does not cure the relative-measure problem.[^s5] Academic work goes further: Carlo Alberto Magni's "average internal rate of return" (2010) replaces the single IRR with a mean of a project's one-period returns. He argues it avoids complex or multiple roots, ranks projects consistently with NPV, and contains the classic IRR as a special case.[^s6]

## In practice

IRR remains the headline metric in many capital-expenditure proposals and in investment fields that report returns as annual percentages. McKinsey recommends that anyone shown an attractive IRR ask two questions. First, what reinvestment rate is assumed? Second, how early do the interim cash flows arrive, since earlier flows magnify any error.[^s4] Where IRR is used at all, the authors advise pairing it with NPV or replacing it with MIRR.[^s4] Graham and Harvey also found that many firms discount projects at a company-wide rate rather than one matched to project risk. That weakens any IRR-versus-hurdle comparison, however carefully the IRR itself is computed.[^s2]

## Connections

IRR is a measure used within **capital budgeting**, part of **corporate finance**, and it is built on the same present-value arithmetic as **discounted cash flow** analysis.[^s1] It **contrasts with** **net present value**: the two usually agree on single accept-or-reject decisions, but they can diverge when ranking projects because of scale and reinvestment.[^s1][^s4] Its hurdle rate **depends on** the cost of capital, normally the **weighted average cost of capital**.[^s1] The **modified internal rate of return** is the main corrected **alternative**, and the **payback period** is the simpler alternative that small firms often prefer.[^s2][^s5] Because IRR is the standard way of quoting returns on long-horizon equity investments, it is closely related to **venture capital** and **leveraged buyout** analysis, where interim distributions make the reinvestment caveat especially relevant.[^s4]

## Sources

[^s1]: OpenStax, *Principles of Finance*, Section 16.3, "Internal Rate of Return (IRR) Method", Rice University. https://openstax.org/books/principles-finance/pages/16-3-internal-rate-of-return-irr-method (accessed 2026-11-18)
[^s2]: John R. Graham and Campbell R. Harvey, "The Theory and Practice of Corporate Finance: Evidence from the Field", *Journal of Financial Economics* 60(2-3): 187-243, 2001. https://scholars.duke.edu/display/pub774079 (accessed 2026-11-18)
[^s3]: "How CFOs Really Practice Finance", MIT Sloan Management Review. https://sloanreview.mit.edu/?p=9977 (accessed 2026-11-18)
[^s4]: John C. Kelleher and Justin J. MacCormack, "Internal Rate of Return: A Cautionary Tale", McKinsey on Finance / McKinsey Quarterly, August 2004. https://www.mckinsey.com/capabilities/strategy-and-corporate-finance/our-insights/internal-rate-of-return-a-cautionary-tale (accessed 2026-11-18)
[^s5]: ACCA, "Modified Internal Rate of Return", technical article. https://accaglobal.com/gb/en/student/exam-support-resources/professional-exams-study-resources/p4/technical-articles/Modified-internal-rate-return.html (accessed 2026-11-18)
[^s6]: Carlo Alberto Magni, "Average Internal Rate of Return and Investment Decisions: A New Perspective", CEFIN Working Paper No. 21, University of Modena and Reggio Emilia, 2010. https://econpapers.repec.org/RePEc:mod:wcefin:0021 (accessed 2026-11-18)
