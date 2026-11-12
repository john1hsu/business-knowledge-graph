---
id: kt:capital-asset-pricing-model
type: Theory
title: "Capital Asset Pricing Model: Pricing Systematic Risk"
aliases: [CAPM, capital asset pricing model, Sharpe-Lintner CAPM]
domain: corporate-finance
summary: >-
  An equilibrium model of asset prices, published by William Sharpe in 1964 and also credited to
  John Lintner, holding that an asset's expected return equals the risk-free rate plus its beta times the
  market risk premium, so investors are paid only for risk that diversification cannot remove.
broader: [kt:asset-pricing, kt:corporate-finance]
related: [kt:efficient-market-hypothesis, kt:weighted-average-cost-of-capital, kt:index-fund]
relations:
  - {predicate: createdBy, object: kt:william-sharpe}
  - {predicate: createdBy, object: kt:john-lintner}
  - {predicate: influencedBy, object: kt:modern-portfolio-theory}
  - {predicate: appliesTo, object: kt:cost-of-equity}
  - {predicate: alternativeTo, object: kt:fama-french-three-factor-model}
sources:
  - id: s1
    title: "The Capital Asset Pricing Model: Theory and Evidence"
    publisher: Journal of Economic Perspectives (Dartmouth Digital Commons record)
    url: https://digitalcommons.dartmouth.edu/facoa/2439
    type: peer-reviewed
    accessed: 2026-11-12
  - id: s2
    title: "Press release: The Prize in Economic Sciences 1990"
    publisher: Royal Swedish Academy of Sciences (NobelPrize.org)
    url: https://www.nobelprize.org/nobel_prizes/economic-sciences/laureates/1990/press.html
    type: academic
    accessed: 2026-11-12
  - id: s3
    title: "15.3 The Capital Asset Pricing Model (CAPM)"
    publisher: OpenStax, Principles of Finance 2e
    url: https://openstax.org/books/principles-finance-2e/pages/15-3-the-capital-asset-pricing-model-capm
    type: textbook
    accessed: 2026-11-12
  - id: s4
    title: "How the capital asset pricing model (CAPM) changed investing"
    publisher: Encyclopaedia Britannica (Britannica Money)
    url: https://eb.com/money/what-is-the-capital-asset-pricing-model
    type: encyclopedia
    accessed: 2026-11-12
  - id: s5
    title: "Professor William Sharpe Shares Nobel Prize in Economics"
    publisher: Stanford Graduate School of Business
    url: https://www.gsb.stanford.edu/experience/news-history/professor-william-sharpe-shares-nobel-prize-economics
    type: academic
    accessed: 2026-11-12
created: 2026-11-12
---

# Capital Asset Pricing Model: Pricing Systematic Risk

The capital asset pricing model (CAPM) states that the return investors should expect from an asset depends on only one kind of risk: how strongly the asset moves with the market as a whole. Its formula is expected return = risk-free rate + beta × (expected market return − risk-free rate).[^s3] The logic is that company-specific risk cancels out in a diversified portfolio, so the market rewards investors only for systematic, market-wide risk.[^s4] The Nobel committee called the model the backbone of modern price theory for financial markets.[^s2]

## Origin

William F. Sharpe published the model in *The Journal of Finance* in September 1964, building on the portfolio theory Harry Markowitz had introduced in 1952.[^s4] Fama and French credit the model to both Sharpe and John Lintner in the 1960s, which is why economists often speak of the Sharpe-Lintner CAPM.[^s1] Stanford GSB, where Sharpe taught from 1970, described the model as matching an investment's potential gain to its potential risk and as drawing on the work of both Markowitz and Kenneth Arrow.[^s5] Sharpe shared the 1990 Nobel memorial prize in economic sciences with Markowitz and Merton Miller for his work on how financial asset prices are formed.[^s2][^s5]

## How it works

Three inputs drive the model.[^s3]

- **Risk-free rate:** usually proxied by US Treasury yields. OpenStax uses a 3.36% average three-month T-bill return for 1928–2020.[^s3]
- **Beta:** how much a stock tends to move when the market moves. A beta of 1 tracks the market; above 1 amplifies its swings; below 1 dampens them.[^s3]
- **Market risk premium:** expected market return minus the risk-free rate. OpenStax's S&P 500 average of 11.64% for 1928–2020 gives a premium of 8.28%.[^s3]

In the Nobel committee's terms, beta measures a share's marginal contribution to the risk of the whole market portfolio.[^s2] OpenStax's worked example uses Delta Air Lines, whose beta estimated from 2018–2020 monthly returns was 1.39. That beta implies an expected return of about 14.87%, above the market average because Delta is riskier than the typical stock.[^s3] The same example also shows the model's sensitivity to inputs: in early February 2021 one data provider reported Delta's beta as 1.46 and another as 1.29. Choices of time window, data frequency and market index all change the result.[^s3]

## Evidence and critiques

Eugene Fama and Kenneth French (2004) concluded that the CAPM's empirical record is poor enough to undermine how it is used in practice.[^s1] Early tests found that average returns do rise with beta, but the relationship is too flat. Low-beta stocks earned more, and high-beta stocks less, than the model predicts. In their sorts of portfolios by beta for 1928–2003, the lowest-beta group was predicted to earn 8.3% a year but earned 11.1%. The highest-beta group was predicted to earn 16.8% but earned 13.7%.[^s1] From the late 1970s researchers documented patterns beta cannot explain: small stocks, stocks with high earnings-to-price ratios and stocks with high book-to-market ratios all earned more than the model predicted.[^s1] Richard Roll's critique adds that the true market portfolio, which in theory includes non-traded assets such as human capital, cannot be observed. That makes clean tests difficult, but Fama and French note that applications depend on the same imperfect market proxies.[^s1]

Other critics point to unrealistic assumptions, such as investors borrowing at the risk-free rate, and to the instability of the market risk premium over market cycles. Multifactor models that add firm size and price-to-book value are the usual response.[^s4] Fama and French also show that estimates of the premium itself are imprecise. Their 1927–2003 estimate of 8.3% a year carried a standard error of 2.4%, giving a two-standard-error range of roughly 3.5% to 13.1%.[^s1]

## In practice

Despite these weaknesses, the CAPM remains the default tool for estimating a firm's cost of equity and judging portfolio performance.[^s1] The Nobel committee noted its routine use in cost-of-capital calculations for investment and takeover decisions, in rate-setting for regulated utilities and in court valuations of firms that have no stock listing.[^s2] Stanford GSB described it as the investment industry's standard model for pension, institutional and corporate managers.[^s5] Its message, that only market exposure earns a reward, also helped make low-cost index investing popular.[^s4]

## Connections

The CAPM sits within **asset pricing** and **corporate finance**. It was created by **William Sharpe** and **John Lintner**, and it builds on Markowitz's **modern portfolio theory**.[^s1][^s4] Its main corporate use is estimating the **cost of equity**, which feeds the **weighted average cost of capital**.[^s2][^s3] Tests of the CAPM are bound up with the **efficient market hypothesis**, because rejecting the model cannot by itself show whether markets misprice assets or the model is misspecified. The **Fama-French three-factor model** was developed as an alternative that adds size and value factors.[^s1] The model's message that only market risk is rewarded supported the rise of the **index fund**.[^s4]

## Sources

[^s1]: Eugene F. Fama and Kenneth R. French, "The Capital Asset Pricing Model: Theory and Evidence", *Journal of Economic Perspectives* 18(3), 2004, pp. 25–46, doi:10.1257/0895330042162430. https://digitalcommons.dartmouth.edu/facoa/2439 (accessed 2026-11-12)
[^s2]: Royal Swedish Academy of Sciences, "Press release: The Sveriges Riksbank Prize in Economic Sciences in Memory of Alfred Nobel 1990", NobelPrize.org. https://www.nobelprize.org/nobel_prizes/economic-sciences/laureates/1990/press.html (accessed 2026-11-12)
[^s3]: "15.3 The Capital Asset Pricing Model (CAPM)", *Principles of Finance 2e*, OpenStax. https://openstax.org/books/principles-finance-2e/pages/15-3-the-capital-asset-pricing-model-capm (accessed 2026-11-12)
[^s4]: "How the capital asset pricing model (CAPM) changed investing", Encyclopaedia Britannica (Britannica Money). https://eb.com/money/what-is-the-capital-asset-pricing-model (accessed 2026-11-12)
[^s5]: Stanford Graduate School of Business, "Professor William Sharpe Shares Nobel Prize in Economics", 1990. https://www.gsb.stanford.edu/experience/news-history/professor-william-sharpe-shares-nobel-prize-economics (accessed 2026-11-12)
