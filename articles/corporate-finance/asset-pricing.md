---
id: kt:asset-pricing
type: Field
title: "Asset Pricing: Valuing Risky Payoffs with Stochastic Discount Factors"
aliases: [asset pricing, asset pricing theory, theory of asset pricing, empirical asset pricing]
domain: corporate-finance
summary: >-
  The branch of financial economics that explains why risky assets have the prices and expected
  returns they do, unifying models such as the CAPM, multifactor models and option pricing around
  the idea that price equals the expected payoff discounted by a stochastic discount factor.
broader: [kt:financial-economics]
related: [kt:corporate-finance, kt:behavioral-finance]
relations:
  - {predicate: hasPart, object: kt:capital-asset-pricing-model}
  - {predicate: hasPart, object: kt:efficient-market-hypothesis}
  - {predicate: hasPart, object: kt:fama-french-three-factor-model}
  - {predicate: dependsOn, object: kt:arbitrage}
sources:
  - id: s1
    title: "The Prize in Economic Sciences 2013"
    publisher: Royal Swedish Academy of Sciences
    url: https://www.kva.se/en/news/ekonomipriset-2013-2/
    type: academic
    accessed: 2026-11-15
  - id: s2
    title: "Asset Pricing: Revised Edition (John H. Cochrane)"
    publisher: Princeton University Press
    url: https://press.princeton.edu/node/21225
    type: textbook
    accessed: 2026-11-15
  - id: s3
    title: "The Equity Premium: A Puzzle"
    publisher: Journal of Monetary Economics (copy filed with the Kentucky Public Service Commission)
    url: https://psc.ky.gov/pscecf/2012-00221/rateintervention@ag.ky.gov/10252012f/Mehra_-_The_Equity_Premium_-_A_Puzzle.pdf
    type: primary
    accessed: 2026-11-15
  - id: s4
    title: "Implications of Security Market Data for Models of Dynamic Economies"
    publisher: Federal Reserve Bank of Minneapolis
    url: https://minneapolisfed.org/research/discussion-papers/implications-of-security-market-data-for-models-of-dynamic-economies
    type: primary
    accessed: 2026-11-15
  - id: s5
    title: "Martingales and arbitrage in multiperiod securities markets (EconPapers record)"
    publisher: Journal of Economic Theory / RePEc EconPapers
    url: https://econpapers.repec.org/RePEc:eee:jetheo:v:20:y:1979:i:3:p:381-408
    type: peer-reviewed
    accessed: 2026-11-15
  - id: s6
    title: "Common Risk Factors in the Returns on Stocks and Bonds (abstract)"
    publisher: Casualty Actuarial Society
    url: https://casact.org/abstract/common-risk-factors-returns-stocks-and-bonds
    type: peer-reviewed
    accessed: 2026-11-15
created: 2026-11-15
---

# Asset Pricing

**Asset pricing** is the part of financial economics that asks why a stock, bond, option or any other claim on uncertain future cash flows trades at the price it does, and why some assets offer higher expected returns than others. Its modern synthesis, set out in John Cochrane's graduate text *Asset Pricing*, traces every pricing model back to one idea: price equals the expected payoff discounted by a single **stochastic discount factor** (SDF), sometimes called the pricing kernel. In that framing, the consumption-based model, the CAPM, multifactor models, term-structure models and option-pricing formulas are all particular specifications of the discount factor rather than separate theories.[^s2]

## How it works

The SDF approach says an asset is worth more if it pays off in states of the world where investors value an extra dollar highly, such as recessions, and less if it pays off mainly in good times. Expected returns therefore compensate investors for covariance with bad times, not for volatility as such. Cochrane's text applies this logic across stocks, bonds and options, uses a state-space geometry to derive mean-variance frontiers, and translates SDF results into the more familiar language of betas and regressions.[^s2]

A theoretical foundation is the link between the absence of arbitrage and the existence of consistent prices. J. Michael Harrison and David Kreps formalised this for multiperiod securities markets in a 1979 *Journal of Economic Theory* paper on martingales and arbitrage, the basis for risk-neutral valuation of derivatives.[^s5] Lars Peter Hansen and Ravi Jagannathan later showed how security market data alone restrict the admissible mean and standard deviation of investors' intertemporal marginal rates of substitution, a nonparametric test that any candidate discount factor must pass; the working paper appeared in 1990 and the journal version in the *Journal of Political Economy* in 1991.[^s4]

## Evidence and critiques

Empirical asset pricing was recognised by the 2013 economics prize to Eugene Fama, Lars Peter Hansen and Robert Shiller. The Royal Swedish Academy of Sciences summarised their joint finding: prices are close to unpredictable over days or weeks, yet broad movements can be partly anticipated over three to five years. Fama showed that new information is rapidly incorporated into prices; Shiller found that stock prices swing far more than dividends and that the price-dividend ratio tends to mean-revert; Hansen developed a statistical method (the generalized method of moments) suited to testing rational pricing models.[^s1]

How to interpret long-horizon predictability remains contested. The rational view holds that high expected returns compensate investors for bearing risk in unusually risky periods; behavioral finance instead points to departures from rationality and to institutional limits, such as borrowing constraints, that stop informed traders from correcting mispricing. The Academy concluded that prices reflect both changing risk attitudes and behavioral biases and frictions.[^s1]

The field's best-known anomaly is the **equity premium puzzle**. Rajnish Mehra and Edward Prescott reported that from 1889 to 1978 the S&P 500 earned an average real return of about 6.98% a year against roughly 0.80% for a near-riskless security, a premium of about 6.18 points. Their calibrated equilibrium models could generate a premium of only about 0.35 points, leading them to argue that frictions outside standard models were probably needed.[^s3] On the cross-section of returns, Eugene Fama and Kenneth French (1993) identified market, size and book-to-market factors for stocks, plus maturity and default factors for bonds, that together seemed to explain average returns better than the single-factor CAPM.[^s6]

## In practice

For managers, asset pricing supplies the discount rates used in valuation. A corporate finance team estimating its cost of equity is applying an asset pricing model, whether the CAPM or a multifactor alternative, and the debates above directly change hurdle rates and project choices.[^s2][^s6] The Academy also credited the efficient-markets research with influencing market practice, notably the rise of index funds.[^s1]

## Connections

Asset pricing sits within **financial economics** and supplies the required-return inputs that **corporate finance** uses for capital budgeting and valuation.[^s2] It contains the **capital asset pricing model** and the **Fama-French three-factor model** as competing specifications of risk, and the **efficient market hypothesis** as its central empirical claim about information in prices.[^s1][^s6] Its theory **depends on** the no-**arbitrage** principle formalised by Harrison and Kreps.[^s5] **Behavioral finance** is its main rival explanation for return predictability and puzzles such as the equity premium.[^s1][^s3]

## Sources

[^s1]: "The Prize in Economic Sciences 2013", Royal Swedish Academy of Sciences, 14 October 2013. https://www.kva.se/en/news/ekonomipriset-2013-2/ (accessed 2026-11-15)
[^s2]: John H. Cochrane, *Asset Pricing: Revised Edition*, Princeton University Press, 2005. https://press.princeton.edu/node/21225 (accessed 2026-11-15)
[^s3]: Rajnish Mehra and Edward C. Prescott, "The Equity Premium: A Puzzle", *Journal of Monetary Economics* 15 (1985): 145–161. https://psc.ky.gov/pscecf/2012-00221/rateintervention@ag.ky.gov/10252012f/Mehra_-_The_Equity_Premium_-_A_Puzzle.pdf (accessed 2026-11-15)
[^s4]: Lars Peter Hansen and Ravi Jagannathan, "Implications of Security Market Data for Models of Dynamic Economies", Federal Reserve Bank of Minneapolis Discussion Paper 29, 1990; *Journal of Political Economy* 99(2), 1991. https://minneapolisfed.org/research/discussion-papers/implications-of-security-market-data-for-models-of-dynamic-economies (accessed 2026-11-15)
[^s5]: J. Michael Harrison and David Kreps, "Martingales and arbitrage in multiperiod securities markets", *Journal of Economic Theory* 20(3), 1979: 381–408. https://econpapers.repec.org/RePEc:eee:jetheo:v:20:y:1979:i:3:p:381-408 (accessed 2026-11-15)
[^s6]: Eugene F. Fama and Kenneth R. French, "Common Risk Factors in the Returns on Stocks and Bonds", *Journal of Financial Economics* 33(1), 1993: 3–56. https://casact.org/abstract/common-risk-factors-returns-stocks-and-bonds (accessed 2026-11-15)
