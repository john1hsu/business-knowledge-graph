---
id: kt:arbitrage
type: Concept
title: Arbitrage
aliases: [riskless arbitrage, pure arbitrage, no-arbitrage principle]
domain: corporate-finance
summary: >-
  The simultaneous purchase and sale of the same or equivalent assets in different markets or forms to
  profit from a price difference; in finance theory, the assumption that such riskless profits cannot
  persist underpins valuation results from the Modigliani-Miller theorem to option pricing.
broader: [kt:corporate-finance, kt:asset-pricing]
related: [kt:modigliani-miller-theorem, kt:efficient-market-hypothesis, kt:law-of-one-price, kt:agency-costs, kt:behavioral-finance]
relations:
  - {predicate: hasPart, object: kt:merger-arbitrage}
  - {predicate: influenced, object: kt:black-scholes-model}
  - {predicate: exemplifiedBy, object: kt:royal-dutch-shell-twin-shares}
  - {predicate: contrastsWith, object: kt:limits-to-arbitrage}
sources:
  - id: s1
    title: "Arbitrage (finance)"
    publisher: Encyclopaedia Britannica (Britannica Money)
    url: https://britannica.com/money/arbitrage-finance
    type: encyclopedia
    accessed: 2026-11-09
  - id: s2
    title: "The Cost of Capital, Corporation Finance and the Theory of Investment"
    publisher: American Economic Review (AEA Top 20 reprint)
    url: https://www.aeaweb.org/aer/top20/48.3.261-297.pdf
    type: primary
    accessed: 2026-11-09
  - id: s3
    title: "Press release: The Prize in Economic Sciences 1997"
    publisher: Royal Swedish Academy of Sciences (NobelPrize.org)
    url: https://www.nobelprize.org/prizes/economic-sciences/1997/press-release/
    type: academic
    accessed: 2026-11-09
  - id: s4
    title: "The Limits of Arbitrage"
    publisher: The Journal of Finance, 52(1), 35-55 (author copy)
    url: https://ms.mcmaster.ca/%7Egrasselli/ShleiferVishny97.pdf
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s5
    title: "How are Stock Prices Affected by the Location of Trade?"
    publisher: National Bureau of Economic Research, Working Paper 6572
    url: https://www.nber.org/papers/w6572
    type: academic
    accessed: 2026-11-09
  - id: s6
    title: "RDP 2003-06: The Characteristics and Trading Behaviour of Dual-Listed Companies"
    publisher: Reserve Bank of Australia
    url: https://www.rba.gov.au/publications/rdp/2003/2003-06/introduction.html
    type: government
    accessed: 2026-11-09
created: 2026-11-09
---

# Arbitrage

**Arbitrage** is buying an asset in one market and almost immediately selling the same asset, or an economic equivalent, in another to capture a price difference. Britannica describes it across foreign exchange, gold, securities and commodities, and notes that the buying and selling itself tends to close the gap: as arbitrageurs bid up the cheap side and sell the dear side, the profit disappears.[^s1] In finance theory the idea is turned into a principle. If two claims deliver identical cash flows, they must trade at the same price, because otherwise anyone could earn a riskless profit. This **no-arbitrage** condition is one of the most widely used tools in valuation.[^s2][^s3]

## Forms of arbitrage

The textbook case is spatial: the same good or currency priced differently in two places. Britannica lists commodity, foreign-exchange (including multi-point currency chains), interest-rate, and gold and securities arbitrage, where exchange rates enter because funds cross borders.[^s1] It also covers **risk arbitrage**, or merger arbitrage: buying a takeover target's stock and holding it until the deal closes. That trade grew with the 1980s takeover wave, and it is not riskless, since a failed deal usually sends the target's price back down. Trading on advance knowledge of a deal is insider trading; Britannica recounts that Ivan Boesky, the best-known U.S. arbitrageur of the era, admitted to it in 1986 and was fined $100 million.[^s1]

## Arbitrage as a proof technique

Corporate finance relies on arbitrage less as a trading strategy than as an argument. Modigliani and Miller's 1958 Proposition I compared an all-equity firm with an otherwise identical levered firm. If the levered firm sold at a premium, its shareholders could sell, borrow on personal account and buy the unlevered firm, earning more for the same risk; if it sold at a discount, investors could undo its leverage by holding its stock and bonds together. Either way, trading pushes the two values together.[^s2] The proof assumed perfect capital markets, firms in the same risk class, and investors able to borrow at about the rate firms pay. It required only that investors prefer more income to less, not any particular attitude to risk.[^s2]

The same logic later produced option pricing. Black and Scholes (1973) and Merton showed that a position in a stock and its options can be combined into a riskless portfolio. That portfolio must earn the risk-free rate, or arbitrage would erase the excess. Because the hedge must be rebalanced continuously, the reasoning yields a differential equation whose solution is the Black-Scholes formula. No estimate of a risk premium is needed.[^s3] The Nobel committee noted that the method extends to corporate debt and equity, guarantees, insurance and real investment flexibility.[^s3]

## Evidence and critiques

The strongest challenge is that real arbitrage is neither riskless nor free. Shleifer and Vishny (1997) argued that it is done mostly by a few specialists investing other people's money. Outside investors judge those specialists by recent returns. When a mispricing widens, the arbitrageur shows losses and faces withdrawals just as the opportunity is best. Arbitrage can therefore fail in extreme conditions and may even amplify price shocks. It also stays scarcer in stocks, where values are hard to pin down and idiosyncratic volatility is high, than in bonds and currencies.[^s4]

Twin shares are the classic evidence. Royal Dutch and Shell pooled cash flows, so their shares should have traded at a fixed ratio. Froot and Dabora (1998) found instead that each twin's relative price moved with the market where it traded most, and none of six candidate explanations fully accounted for the pattern.[^s5] A 2003 Reserve Bank of Australia study of dual-listed companies noted that these gaps were substantial and persistent and treated them as an anomaly for the efficient market hypothesis. If the gaps had offered easy profits, arbitrage would likely have closed them.[^s6]

## In practice

Managers and analysts use no-arbitrage reasoning whenever they price one instrument off others: pricing an option or a loan guarantee by replication, or checking that a firm's value does not depend on how its debt and equity are split once taxes and other frictions are set aside.[^s2][^s3] The practical lesson from the limits-of-arbitrage work is to ask who would correct a mispricing, with what capital, and over what horizon, before assuming markets will.[^s4]

## Connections

Arbitrage sits within **corporate finance** and **asset pricing**. It is the engine of the **Modigliani-Miller theorem** and a precondition for the **efficient market hypothesis** and the **law of one price**.[^s2][^s6] It influenced the **Black-Scholes model**, which prices options by a no-arbitrage hedge.[^s3] **Merger arbitrage** is one of its risky forms.[^s1] The **Royal Dutch/Shell twin shares** exemplify its failure, and the **limits to arbitrage** literature, rooted in **agency costs** between fund managers and investors, contrasts with the frictionless view and helped build **behavioral finance**.[^s4][^s5]

## Sources

[^s1]: The Editors of Encyclopaedia Britannica, "Arbitrage (finance)", Britannica Money. https://britannica.com/money/arbitrage-finance (accessed 2026-11-09)
[^s2]: Franco Modigliani and Merton H. Miller, "The Cost of Capital, Corporation Finance and the Theory of Investment", American Economic Review 48(3), 1958, pp. 261-297. https://www.aeaweb.org/aer/top20/48.3.261-297.pdf (accessed 2026-11-09)
[^s3]: Royal Swedish Academy of Sciences, "Press release: The Prize in Economic Sciences 1997", NobelPrize.org. https://www.nobelprize.org/prizes/economic-sciences/1997/press-release/ (accessed 2026-11-09)
[^s4]: Andrei Shleifer and Robert W. Vishny, "The Limits of Arbitrage", The Journal of Finance 52(1), 1997, pp. 35-55. https://ms.mcmaster.ca/%7Egrasselli/ShleiferVishny97.pdf (accessed 2026-11-09)
[^s5]: Kenneth A. Froot and Emil Dabora, "How are Stock Prices Affected by the Location of Trade?", NBER Working Paper 6572, 1998. https://www.nber.org/papers/w6572 (accessed 2026-11-09)
[^s6]: Jaideep Bedi, Anthony Richards and Paul Tennant, "The Characteristics and Trading Behaviour of Dual-Listed Companies", Reserve Bank of Australia RDP 2003-06, 2003. https://www.rba.gov.au/publications/rdp/2003/2003-06/introduction.html (accessed 2026-11-09)
