---
id: kt:modigliani-miller-theorem
type: Theory
title: Modigliani-Miller Theorem
aliases: [MM theorem, Modigliani-Miller propositions, MM propositions, capital structure irrelevance principle, MM irrelevance theorem]
domain: corporate-finance
summary: >-
  The proposition, introduced by Franco Modigliani and Merton Miller in 1958, that in a frictionless
  market a firm's value and average cost of capital are independent of its mix of debt and equity,
  so that any real-world effect of financing choices must come from taxes or other market imperfections.
broader: [kt:capital-structure, kt:corporate-finance]
related: [kt:agency-costs, kt:weighted-average-cost-of-capital, kt:dividend-policy, kt:leveraged-buyout]
relations:
  - {predicate: createdBy, object: kt:franco-modigliani}
  - {predicate: createdBy, object: kt:merton-miller}
  - {predicate: introducedIn, object: kt:cost-of-capital-corporation-finance-and-theory-of-investment-1958}
  - {predicate: dependsOn, object: kt:arbitrage}
  - {predicate: influenced, object: kt:trade-off-theory-of-capital-structure}
  - {predicate: contrastsWith, object: kt:pecking-order-theory}
sources:
  - id: s1
    title: "The Cost of Capital, Corporation Finance and the Theory of Investment"
    publisher: American Economic Review (AEA Top 20 reprint)
    url: https://www.aeaweb.org/aer/top20/48.3.261-297.pdf
    type: primary
    accessed: 2026-10-31
  - id: s2
    title: "Press release: The Prize in Economic Sciences 1990"
    publisher: Royal Swedish Academy of Sciences (NobelPrize.org)
    url: https://www.nobelprize.org/prizes/economics/1990/press-release/
    type: academic
    accessed: 2026-10-31
  - id: s3
    title: "The Capital Structure Puzzle"
    publisher: National Bureau of Economic Research, Working Paper 1393
    url: https://www.nber.org/papers/w1393
    type: academic
    accessed: 2026-10-31
  - id: s4
    title: "Merton H. Miller"
    publisher: Encyclopaedia Britannica (Britannica Money)
    url: https://www.Britannica.com/money/Merton-Miller
    type: encyclopedia
    accessed: 2026-10-31
  - id: s5
    title: "The Modigliani and Miller Propositions: The History of a Failed Foundation for Corporate Finance?"
    publisher: Abacus (RePEc/IDEAS record)
    url: https://ideas.repec.org/a/bla/abacus/v50y2014i3p279-295.html
    type: peer-reviewed
    accessed: 2026-10-31
created: 2026-10-31
---

# Modigliani-Miller Theorem

The Modigliani-Miller (MM) theorem holds that, under idealized market conditions, the way a firm finances itself does not change what the firm is worth. A company's market value is set by the expected earnings its assets generate and the risk of those earnings; splitting those earnings between creditors and shareholders in different proportions only reallocates them.[^s1] Britannica summarizes the core insight as the idea that how a company funds its activities matters less than how profitable those activities are.[^s4] The theorem is the starting point of modern corporate finance precisely because it specifies when financing does *not* matter, which isolates the frictions that make it matter in practice.[^s2]

## Origin

Franco Modigliani and Merton H. Miller, who was then teaching at the Carnegie Institute of Technology, published the result in "The Cost of Capital, Corporation Finance and the Theory of Investment" in the *American Economic Review* in June 1958.[^s1][^s4] Before their paper, finance specialists generally believed that moderate borrowing lowered a firm's average cost of capital, producing a U-shaped cost curve and an "optimal" capital structure.[^s1] Further essays followed in 1963 and 1966, and the line of work formed a central part of the citation when Miller shared the 1990 Nobel memorial prize in economic sciences with Harry Markowitz and William Sharpe; Modigliani had received the prize in 1985.[^s2][^s4]

## How it works

The 1958 paper groups firms into "risk classes" whose earnings streams differ only in scale, and makes three claims.[^s1]

- **Proposition I:** a firm's market value equals its expected return divided by the capitalization rate for its risk class, regardless of leverage, so every firm in a class has the same average cost of capital.[^s1]
- **Proposition II:** the expected yield on a levered firm's stock rises linearly with its debt-to-equity ratio, by the debt-equity ratio times the spread between the class rate and the interest rate. Cheaper debt is exactly offset by costlier equity.[^s1]
- **Proposition III:** a firm acting for its shareholders should take a project only if its return at least equals the class capitalization rate, however the project is financed. The authors' worked example shows an 8 percent project funded with 4 percent debt actually lowering share value.[^s1]

The proof is an arbitrage argument. If two otherwise identical firms were priced differently because of leverage, investors could sell the overpriced one and buy the underpriced one, using personal borrowing to recreate the leverage themselves; that trading would close the gap. The argument needs only that investors prefer more income to less, not any assumption about risk attitudes.[^s1] The Nobel committee put the intuition plainly: shareholders will not pay a premium for borrowing a firm does on their behalf when they can borrow on equal terms themselves. The same logic yields a second invariance result for dividend policy.[^s2]

## Evidence and critiques

Modigliani and Miller tested their model on two limited samples: F. B. Allen's data on 43 large electric utilities for 1947–48 and Robert Smith's data on 42 oil companies for 1953. They found near-zero, insignificant correlations between cost of capital and leverage, no U-shaped curve, and stock yields that rose significantly with leverage, which they judged consistent with their model while calling for more testing.[^s1]

The assumptions are deliberately unrealistic, and much of later finance consists of relaxing them. The 1958 paper itself showed that deductibility of interest gives debt a tax advantage, though the authors estimated it as modest.[^s1] From the mid-1960s, research led by Miller examined how tax structures and bankruptcy costs alter the link between capital structure and value; the committee described the MM theorems as the norm of comparison for theoretical and empirical work.[^s2] Stewart Myers (1984) framed the resulting debate as a contest between a static trade-off theory, in which firms balance debt's tax benefits against financial-distress costs, and a pecking-order theory rooted in asymmetric information, in which firms prefer internal funds, then debt, then equity.[^s3] Sharper critics argue the propositions pulled finance away from strategy and human behaviour; Mike Dempsey (2014) contends that textbook treatments of investment and financing built on MM are badly distorted from reality.[^s5]

## In practice

Practitioners rarely treat MM as literally true, but they use it as a discipline. Any claim that a recapitalization, buyback or debt-funded deal "creates value" must name the friction responsible: a tax shield, reduced agency costs, lower distress costs or an information effect.[^s2] Proposition III also underlies the standard rule of judging a project by the risk of its own cash flows rather than by the cheapest source of money used to fund it, a point the authors' 8 percent project example makes concrete.[^s1] Leveraged buyouts are a common test case: if leverage alone added value, MM would be violated, so analysts look instead for tax or other identifiable market imperfections.[^s2]

## Connections

The theorem is the founding result of the theory of **capital structure** and a pillar of **corporate finance**.[^s2] It was created by **Franco Modigliani** and **Merton Miller** and introduced in their **1958 AER paper**, and it depends on an **arbitrage** argument.[^s1] Proposition I implies that the **weighted average cost of capital** is invariant to leverage, and the companion invariance result covers **dividend policy**.[^s2] By isolating taxes and distress costs, it gave rise to the **trade-off theory of capital structure**, and it contrasts with the information-based **pecking-order theory**.[^s3] Jensen and Meckling's **agency costs** and the **leveraged buyout** literature are among the explanations offered for why financing matters once MM's assumptions fail, consistent with the committee's view that any value effect must trace to an identifiable imperfection.[^s2]

## Sources

[^s1]: Franco Modigliani and Merton H. Miller, "The Cost of Capital, Corporation Finance and the Theory of Investment", *American Economic Review* 48(3), June 1958, pp. 261–297. https://www.aeaweb.org/aer/top20/48.3.261-297.pdf (accessed 2026-10-31)
[^s2]: Royal Swedish Academy of Sciences, "Press release: The Sveriges Riksbank Prize in Economic Sciences in Memory of Alfred Nobel 1990", NobelPrize.org. https://www.nobelprize.org/prizes/economics/1990/press-release/ (accessed 2026-10-31)
[^s3]: Stewart C. Myers, "The Capital Structure Puzzle", NBER Working Paper 1393, July 1984; published in *Journal of Finance* 39(3), 1984, pp. 575–592. https://www.nber.org/papers/w1393 (accessed 2026-10-31)
[^s4]: "Merton H. Miller", Encyclopaedia Britannica (Britannica Money). https://www.Britannica.com/money/Merton-Miller (accessed 2026-10-31)
[^s5]: Mike Dempsey, "The Modigliani and Miller Propositions: The History of a Failed Foundation for Corporate Finance?", *Abacus* 50(3), 2014, pp. 279–295, doi:10.1111/abac.12030. https://ideas.repec.org/a/bla/abacus/v50y2014i3p279-295.html (accessed 2026-10-31)
