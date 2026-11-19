---
id: kt:payback-period
type: Metric
title: "Payback Period: Time to Recover an Investment's Initial Cost"
aliases: [payback method, payback period method, payback rule, payback analysis]
domain: corporate-finance
summary: >-
  A capital budgeting measure of how long it takes a project's cash inflows to recover its initial
  investment; firms typically accept projects whose payback falls within a maximum cutoff, a rule
  prized for simplicity and liquidity focus but criticised for ignoring the time value of money and
  all cash flows after the cutoff.
broader: [kt:capital-budgeting]
related: [kt:free-cash-flow, kt:working-capital, kt:accounting-rate-of-return, kt:corporate-finance]
relations:
  - {predicate: contrastsWith, object: kt:net-present-value}
  - {predicate: alternativeTo, object: kt:internal-rate-of-return}
  - {predicate: dependsOn, object: kt:free-cash-flow}
  - {predicate: contrastsWith, object: kt:time-value-of-money}
sources:
  - id: s1
    title: "Principles of Finance, Section 16.1: Payback Period Method"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/16-1-payback-period-method
    type: textbook
    accessed: 2026-11-19
  - id: s2
    title: "Principles of Accounting, Volume 2, Section 11.2: Evaluate the Payback and Accounting Rate of Return in Capital Investment Decisions"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-managerial-accounting/pages/11-2-evaluate-the-payback-and-accounting-rate-of-return-in-capital-investment-decisions
    type: textbook
    accessed: 2026-11-19
  - id: s3
    title: "Principles of Finance, Section 16.4: Alternative Methods"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-finance/pages/16-4-alternative-methods
    type: textbook
    accessed: 2026-11-19
  - id: s4
    title: "The Theory and Practice of Corporate Finance: Evidence from the Field"
    publisher: Journal of Financial Economics (Scholars@Duke record)
    url: https://scholars.duke.edu/publication/774079
    type: peer-reviewed
    accessed: 2026-11-19
  - id: s5
    title: "Corporate Finance in Europe: Confronting Theory with Practice"
    publisher: Erasmus Research Institute of Management (ERIM Report Series)
    url: https://repub.eur.nl/pub/1111/ERS%202004%20002%20F&A.pdf
    type: academic
    accessed: 2026-11-19
  - id: s6
    title: "How CFOs Really Practice Finance"
    publisher: MIT Sloan Management Review
    url: https://sloanreview.mit.edu/?p=9977
    type: practitioner-journal
    accessed: 2026-11-19
created: 2026-11-19
---

# Payback Period

The payback period is the length of time a project needs before the cash it generates adds up to the money originally invested in it. In corporate finance it is one of the standard capital budgeting criteria, usually presented alongside net present value and internal rate of return, and it answers a narrow question: how long will the firm's funds be tied up before the outlay is recovered?[^s1] Managerial accounting texts classify it as a non-time-value method, because it adds nominal cash flows without discounting them.[^s2]

## How it works

When a project is expected to produce the same net cash flow every year, the calculation is a single division: the initial investment divided by the annual net cash inflow. OpenStax's managerial accounting text illustrates this with a $150,000 investment returning $20,000 a year, which pays back in 7.5 years.[^s2] When inflows are uneven, the analyst tracks the unrecovered balance year by year and, in the year the balance turns positive, adds the fraction of that year's inflow needed to close the gap; a $40,000 project with $2,500 still outstanding after five years and $7,500 arriving in year six pays back in about 5.33 years.[^s2] OpenStax's finance text works a similar example in which a $16,000 embroidery machine generating $2,000, $4,000, $5,000 and $5,000 over four years pays back at exactly four years.[^s1]

The decision rule is a cutoff. Management sets a maximum acceptable payback period for a class of investment and rejects projects that take longer, so the method functions mainly as a screening filter before projects advance to a ranking or preference decision.[^s2] The finance text stresses that the cutoff itself is arbitrary and has no grounding in financial theory.[^s1]

A common refinement is the **discounted payback period**. Each cash flow is first discounted at the firm's cost of funds, and payback is then measured on the cumulative discounted amounts. In the embroidery-machine example, discounting at 9% stretches payback from four years to roughly 5.05 years, showing how the simple version understates the true breakeven point.[^s3]

## Evidence and critiques

Textbooks list the method's weaknesses consistently. It ignores the time value of money, so a project returning $6,000 in year one scores the same as one returning $6,000 in year five if both recover their cost in the same year. It disregards every cash flow after the cutoff, which can lead a firm to reject projects with larger long-run returns. It also makes no explicit adjustment for risk, and its acceptance threshold lacks an objective basis.[^s1] Discounting fixes only the first problem: discounted payback still ignores post-breakeven cash flows, which OpenStax calls a serious drawback when choosing between mutually exclusive projects.[^s3]

The defence of payback is practical. It is quick to compute, easy for managers without finance training to understand, and highlights liquidity, since a shorter payback frees cash sooner for other uses and limits the period of exposure to risk.[^s1][^s2]

Field surveys show that practice has not followed the textbook verdict. In a 1999 survey of 392 U.S. chief financial officers, John Graham and Campbell Harvey found that large firms leaned heavily on present-value techniques while small firms were relatively more likely to use payback.[^s4] MIT Sloan Management Review's summary of the same study noted that payback ranked third among capital budgeting tools, behind IRR and NPV, despite being a relatively unsophisticated measure of value.[^s6]

## In practice

European evidence is even more striking. Dirk Brounen, Abe de Jong and Kees Koedijk surveyed CFOs in the UK, the Netherlands, Germany and France (published 2004) and found payback was the most popular technique in all four countries; 69.2% of UK respondents said they always or almost always used it, against 47.0% for NPV. They compared this with 56.7% payback use among Graham and Harvey's U.S. respondents.[^s5] The authors tested the common claim that payback suits capital-constrained firms and found no support for it; instead, payback use was higher at smaller firms (outside the UK) and at firms with the oldest CEOs, while shareholder-value-oriented firms favoured discounting methods.[^s5] In practice, then, payback typically serves as a rough risk and liquidity check run alongside discounted cash flow analysis rather than as a replacement for it.

## Connections

Payback is one of the measures used within **capital budgeting** and appears in the same toolkit as **net present value**, with which it contrasts sharply: NPV discounts all cash flows over a project's life, while payback ignores both discounting and anything beyond the cutoff.[^s1][^s3] It is a simpler alternative to **internal rate of return**, which, like NPV, dominated U.S. CFO practice in Graham and Harvey's survey.[^s6] Its inputs are the project's incremental cash flows, linking it to **free cash flow**, and its emphasis on how long money is locked up connects it to liquidity and **working capital** management.[^s1] Accounting texts pair it with the accounting rate of return as the two non-time-value methods, and the discounted variant is the bridge to the time value of money.[^s2][^s3]

## Sources

[^s1]: OpenStax, *Principles of Finance*, Section 16.1 "Payback Period Method", Rice University. https://openstax.org/books/principles-finance/pages/16-1-payback-period-method (accessed 2026-11-19)
[^s2]: OpenStax, *Principles of Accounting, Volume 2: Managerial Accounting*, Section 11.2 "Evaluate the Payback and Accounting Rate of Return in Capital Investment Decisions", Rice University. https://openstax.org/books/principles-managerial-accounting/pages/11-2-evaluate-the-payback-and-accounting-rate-of-return-in-capital-investment-decisions (accessed 2026-11-19)
[^s3]: OpenStax, *Principles of Finance*, Section 16.4 "Alternative Methods", Rice University. https://openstax.org/books/principles-finance/pages/16-4-alternative-methods (accessed 2026-11-19)
[^s4]: John R. Graham and Campbell R. Harvey, "The Theory and Practice of Corporate Finance: Evidence from the Field", *Journal of Financial Economics* 60(2–3), 187–243, 2001. https://scholars.duke.edu/publication/774079 (accessed 2026-11-19)
[^s5]: Dirk Brounen, Abe de Jong and Kees Koedijk, "Corporate Finance in Europe: Confronting Theory with Practice", ERIM Report Series, Erasmus University Rotterdam, 2004. https://repub.eur.nl/pub/1111/ERS%202004%20002%20F&A.pdf (accessed 2026-11-19)
[^s6]: "How CFOs Really Practice Finance", MIT Sloan Management Review. https://sloanreview.mit.edu/?p=9977 (accessed 2026-11-19)
