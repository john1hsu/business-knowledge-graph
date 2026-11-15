---
id: kt:behavioral-finance
type: Field
title: "Behavioral Finance: How Investor Psychology and Limits to Arbitrage Shape Prices"
aliases: [behavioural finance, behavioral financial economics]
domain: corporate-finance
summary: >-
  The branch of financial economics that explains asset prices, investor trading and corporate financial
  decisions with models in which some agents are not fully rational, resting on two pillars: limits to
  arbitrage and evidence from psychology about how people form beliefs and make risky choices.
broader: [kt:financial-economics, kt:asset-pricing]
related: [kt:arbitrage, kt:overconfidence-bias, kt:corporate-finance]
relations:
  - {predicate: contrastsWith, object: kt:efficient-market-hypothesis}
  - {predicate: hasPart, object: kt:limits-to-arbitrage}
  - {predicate: influencedBy, object: kt:prospect-theory}
  - {predicate: exemplifiedBy, object: kt:disposition-effect}
  - {predicate: exemplifiedBy, object: kt:royal-dutch-shell-twin-shares}
sources:
  - id: s1
    title: "A Survey of Behavioral Finance"
    publisher: NBER Working Paper 9222 (Barberis and Thaler, 2002; later Handbook of the Economics of Finance, 2003), via EconPapers/RePEc
    url: https://econpapers.repec.org/RePEc:nbr:nberwo:9222
    type: academic
    accessed: 2026-11-15
  - id: s2
    title: "Behavioral Finance at 40"
    publisher: NBER Working Paper 35959 (Nicholas C. Barberis, October 2026)
    url: https://www.nber.org/papers/w35959
    type: academic
    accessed: 2026-11-15
  - id: s3
    title: "The Limits of Arbitrage"
    publisher: The Journal of Finance 52(1), 35-55, 1997 (Shleifer and Vishny; course copy, McMaster University)
    url: https://ms.mcmaster.ca/%7Egrasselli/ShleiferVishny97.pdf
    type: peer-reviewed
    accessed: 2026-11-15
  - id: s4
    title: "Prospect Theory: An Analysis of Decision under Risk"
    publisher: Econometrica 47(2), 263-292, 1979 (Econometric Society)
    url: https://www.econometricsociety.org/publications/econometrica/1979/03/01/prospect-theory-analysis-decision-under-risk
    type: primary
    accessed: 2026-11-15
  - id: s5
    title: "Are Investors Reluctant to Realize Their Losses?"
    publisher: Terrance Odean, Haas School of Business, UC Berkeley (paper page)
    url: https://faculty.haas.berkeley.edu/odean/papers/disposition/disposition.html
    type: academic
    accessed: 2026-11-15
  - id: s6
    title: "How are Stock Prices Affected by the Location of Trade?"
    publisher: NBER Working Paper 6572 (Froot and Dabora, 1998; Journal of Financial Economics, 1999)
    url: https://www.nber.org/papers/w6572
    type: academic
    accessed: 2026-11-15
created: 2026-11-15
---

# Behavioral Finance

Behavioral finance studies financial markets on the assumption that at least some investors are not fully rational, and asks whether that assumption explains patterns that standard models struggle with. Nicholas Barberis and Richard Thaler's 2002 survey framed the field as resting on two pillars: limits to arbitrage, which explain why rational traders may fail to correct mispricing, and psychology, which catalogues how real people depart from textbook rationality.[^s1] Barberis's October 2026 review dates the modern research program to the 1980s and describes it as now a thriving part of financial economics, organized around beliefs about future earnings, beliefs about future returns, and prospect theory.[^s2]

## Origins

The psychological pillar draws heavily on Amos Tversky and Daniel Kahneman's 1979 *Econometrica* paper, which argued that expected utility theory describes risky choice poorly. Their prospect theory values outcomes as gains and losses relative to a reference point rather than as levels of final wealth, uses a value function that is concave for gains, convex for losses and steeper for losses, and replaces probabilities with decision weights that overweight small chances.[^s4] The arbitrage pillar was formalized by Andrei Shleifer and Robert Vishny in 1997. They noted that real-world arbitrage is risky, needs capital and is run by specialists managing other people's money, so it cannot be relied on to push prices back to fundamental value.[^s3]

## How it works

The core argument runs in two steps. First, some investors trade on mistaken beliefs or non-standard preferences. Second, those mistakes can move prices because arbitrage is limited. In Shleifer and Vishny's model, outside investors judge fund managers by recent returns, so when a mispricing widens the manager suffers losses and withdrawals exactly when the trade has become more attractive. Arbitrageurs may then be forced to sell into the mispricing, and they invest cautiously in advance because they anticipate this.[^s3] Barberis and Thaler stress that this breaks the inference from "no free lunch" to "prices are right": an anomaly can persist even when it offers no easy riskless profit.[^s1]

On the belief side, the field models how investors form expectations about future earnings and future returns, drawing on psychological evidence about systematic errors in judgment; on the preference side, it uses loss aversion and reference dependence from prospect theory.[^s1][^s2][^s4] Barberis and Thaler applied these ingredients to the aggregate stock market, the cross-section of average returns, individual trading behavior and corporate financial decisions.[^s1]

## Evidence and critiques

Two strands of evidence carry particular weight. Terrance Odean's study of 10,000 discount-brokerage accounts found that investors realize gains much more readily than losses (the disposition effect); the pattern was not explained by rebalancing or trading costs, was not justified by later returns, and lowered after-tax returns, with tax-motivated loss selling concentrated in December.[^s5] Kenneth Froot and Emil Dabora studied "Siamese twin" companies whose pooled cash flows should make their shares move together; instead each twin's relative price tracked the market where it traded most, and most candidate rational explanations failed to account for it.[^s6]

The main critique comes from defenders of market efficiency, who argue that apparent anomalies may simply be compensation for risk that models fail to measure. Shleifer and Vishny themselves concede the contest is partly empirical: they argue that persistent anomalies should cluster where arbitrage is costly and risky, such as assets with high idiosyncratic volatility and slow convergence, which gives the behavioral view a testable prediction.[^s3] A further critique is that a long list of biases can explain almost anything after the fact. Barberis's 2026 review responds by pointing to newer work on the cognitive foundations of these departures and on non-traditional decision processes, aimed at more disciplined models.[^s2]

## In practice

The disposition effect is a concrete case: an investor holding a stock that has fallen below its purchase price keeps it to avoid booking a loss, while selling a winner, which in a taxable account forgoes the tax benefit of realizing losses.[^s5] Because the pattern lowered investors' after-tax returns, the bias carries a measurable cost rather than being a harmless quirk.[^s5] For corporate managers, the field's extension to corporate finance means a firm's share price cannot be assumed to equal fundamental value at every moment when making financing and investment choices.[^s1][^s3]

## Connections

Behavioral finance sits within **financial economics** and **asset pricing**, and sharpens the debate in **corporate finance** about whether market prices are reliable signals.[^s1][^s2] It **contrasts with** the **efficient market hypothesis** by denying that competition among traders guarantees correct prices, and **limits to arbitrage** is one of its two defining parts, qualifying the frictionless view of **arbitrage**.[^s1][^s3] It is **influenced by** **prospect theory**, the source of loss aversion and reference dependence, and draws on biases such as **overconfidence**.[^s4][^s1] The **disposition effect** and the **Royal Dutch/Shell twin shares** are standard examples of irrational trading and persistent mispricing respectively.[^s5][^s6]

## Sources

[^s1]: Nicholas Barberis and Richard Thaler, "A Survey of Behavioral Finance," NBER Working Paper 9222, 2002 (published in the Handbook of the Economics of Finance, 2003). https://econpapers.repec.org/RePEc:nbr:nberwo:9222 (accessed 2026-11-15)
[^s2]: Nicholas C. Barberis, "Behavioral Finance at 40," NBER Working Paper 35959, October 2026. https://www.nber.org/papers/w35959 (accessed 2026-11-15)
[^s3]: Andrei Shleifer and Robert W. Vishny, "The Limits of Arbitrage," The Journal of Finance 52(1), 35-55, 1997. https://ms.mcmaster.ca/%7Egrasselli/ShleiferVishny97.pdf (accessed 2026-11-15)
[^s4]: Daniel Kahneman and Amos Tversky, "Prospect Theory: An Analysis of Decision under Risk," Econometrica 47(2), 263-292, 1979. https://www.econometricsociety.org/publications/econometrica/1979/03/01/prospect-theory-analysis-decision-under-risk (accessed 2026-11-15)
[^s5]: Terrance Odean, "Are Investors Reluctant to Realize Their Losses?" Haas School of Business, UC Berkeley. https://faculty.haas.berkeley.edu/odean/papers/disposition/disposition.html (accessed 2026-11-15)
[^s6]: Kenneth A. Froot and Emil Dabora, "How are Stock Prices Affected by the Location of Trade?" NBER Working Paper 6572, 1998. https://www.nber.org/papers/w6572 (accessed 2026-11-15)
