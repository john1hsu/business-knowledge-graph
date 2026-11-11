---
id: kt:bullwhip-effect
type: Concept
title: Bullwhip Effect in Supply Chains
aliases: [bullwhip effect, whiplash effect, whipsaw effect, Forrester effect, demand amplification]
domain: operations-and-supply-chain
summary: >-
  The tendency for the variance of orders to exceed the variance of underlying sales and to grow
  at each step upstream in a supply chain, so that suppliers far from the consumer see much larger
  demand swings than end customers actually generate.
broader: [kt:supply-chain-management, kt:inventory-management]
related: [kt:material-requirements-planning, kt:kanban, kt:enterprise-resource-planning, kt:information-asymmetry, kt:vendor-managed-inventory]
relations:
  - {predicate: createdBy, object: kt:hau-l-lee}
  - {predicate: introducedIn, object: kt:information-distortion-in-a-supply-chain-1997}
  - {predicate: influencedBy, object: kt:industrial-dynamics}
  - {predicate: exemplifiedBy, object: kt:procter-and-gamble}
  - {predicate: exemplifiedBy, object: kt:hewlett-packard}
sources:
  - id: s1
    title: "Information Distortion in a Supply Chain: The Bullwhip Effect"
    publisher: Management Science (author copy hosted by Bilkent University)
    url: https://courses.ie.bilkent.edu.tr/ie102/wp-content/uploads/sites/12/2019/02/Lee-Padmanabhan-Whang-1997-MS.pdf
    type: primary
    accessed: 2026-11-11
  - id: s2
    title: "Information Distortion in a Supply Chain: The Bullwhip Effect (publication record)"
    publisher: Stanford Graduate School of Business
    url: https://www.gsb.stanford.edu/faculty-research/publications/information-distortion-supply-chain-bullwhip-effect
    type: academic
    accessed: 2026-11-11
  - id: s3
    title: "The Bullwhip Effect in Supply Chains"
    publisher: MIT Sloan Management Review
    url: https://sloanreview.mit.edu/article/the-bullwhip-effect-in-supply-chains
    type: practitioner-journal
    accessed: 2026-11-11
  - id: s4
    title: "In Search of the Bullwhip Effect"
    publisher: Manufacturing & Service Operations Management (record via University of Pennsylvania ScholarlyCommons)
    url: https://repository.upenn.edu/oid_papers/137
    type: peer-reviewed
    accessed: 2026-11-11
  - id: s5
    title: "Information Transmission and the Bullwhip Effect: An Empirical Investigation"
    publisher: Management Science (author copy hosted by Kellogg School of Management)
    url: https://www.kellogg.northwestern.edu/faculty/bray/doc/bw/bw_d.pdf
    type: peer-reviewed
    accessed: 2026-11-11
created: 2026-11-11
---

# Bullwhip Effect in Supply Chains

The bullwhip effect is the amplification of demand variability as orders travel upstream in a supply chain. Hau Lee, V. Padmanabhan and Seungjin Whang defined it in a 1997 *Management Science* paper: when each firm orders only from its immediate supplier, the orders it sends become distorted signals of real demand, their variance can exceed that of sales, and the distortion tends to grow at every stage further from the consumer.[^s1][^s2] Because upstream firms plan production, capacity and inventory from the orders they receive rather than from consumer sales, the distortion leads them into poor decisions.[^s2]

## Origin

The name came from logistics executives at Procter & Gamble, who noticed that the variability of orders for Pampers diapers rose sharply as it moved up the chain; other industries call the same pattern the "whiplash" or "whipsaw" effect.[^s3] Retail sales of Pampers fluctuated only modestly, distributors' orders to P&G swung more, and P&G's own orders to suppliers such as 3M swung the most.[^s3] Hewlett-Packard saw a similar cascade: a reseller's orders for a printer varied far more than its sales, and orders from HP's printer division to its integrated-circuit division varied more still.[^s1][^s3]

The phenomenon itself was older. Jay Forrester's *Industrial Dynamics* (1961) documented it through case studies and blamed the policies firms use to run their operations, and John Sterman's "beer game" experiments in 1989 reproduced the amplification with human players, attributing it to misperceived feedback.[^s1] Lee and colleagues' contribution was to show that the effect also arises when every member of the chain acts rationally and optimizes locally, which made it a structural problem rather than only a behavioral one.[^s1]

## How it works

The 1997 paper identifies four causes:[^s1]

- **Demand signal processing**: firms update forecasts from recent orders and adjust order-up-to levels, raising variance even with zero lead time; longer lead times make it worse.[^s1]
- **Rationing game**: when supply is short and allocated in proportion to orders, buyers inflate orders, so orders overstate true demand.[^s1]
- **Order batching**: fixed ordering costs and periodic review, such as monthly MRP runs, produce lumpy orders, worst when many buyers order at the same time.[^s1]
- **Price variations**: trade promotions and discounts trigger forward buying, so purchases bunch up while consumption stays steady.[^s1]

The costs show up as excess inventory, inaccurate forecasts, misaligned capacity, poor customer service, unstable production plans and expensive corrections such as expediting and overtime.[^s3]

## Countermeasures

The remedies follow the causes. Sharing point-of-sale and inventory data upstream, centralizing replenishment through vendor-managed inventory or continuous replenishment, and shortening lead times counter demand signal processing.[^s1] Cheaper ordering through electronic data interchange, smaller and more frequent orders, and staggered delivery schedules reduce batching.[^s1] Allocating scarce supply by past sales rather than current orders defuses rationing games, and everyday low pricing or contracts that decouple discounts from delivery timing curb forward buying.[^s1] The grocery industry's Efficient Consumer Response initiative of the 1990s aimed partly at cutting the excess inventory these distortions created.[^s3]

## Evidence and critiques

Industry-level data complicate the textbook picture. Using U.S. industry data, Cachon, Randall and Schmidt (2007) found that wholesale industries amplify volatility but most retail and manufacturing industries do not, and that seasonality explains much of the difference: highly seasonal industries tend to smooth production rather than amplify demand.[^s4] Firm-level evidence is stronger. Bray and Mendelson (2012), studying several thousand public U.S. companies from 1974 to 2008, found that roughly two-thirds showed a positive bullwhip, and that the average effect fell by about a third between 1974–1994 and 1995–2008, which they linked to better information technology and supply chain practice.[^s5] The lesson for managers is that aggregation and production smoothing can hide amplification that individual firms still experience.[^s4][^s5]

## Connections

The bullwhip effect is a core problem of **supply chain management** and **inventory management**, its broader nodes.[^s1] It was formalized (**created by**) **Hau L. Lee** and colleagues and **introduced in** their 1997 *Management Science* paper, which **built on** Forrester's **Industrial Dynamics**.[^s1][^s2] It is **exemplified by Procter & Gamble** and **Hewlett-Packard**.[^s3] **Material requirements planning** relates through order batching, since synchronized MRP runs are a named cause; **kanban** and **enterprise resource planning** relate as alternative ways to tie replenishment to actual consumption and share data.[^s1] Its root is **information asymmetry** between stages, and **vendor-managed inventory** is a standard countermeasure.[^s1]

## Sources
[^s1]: Hau L. Lee, V. Padmanabhan and Seungjin Whang, "Information Distortion in a Supply Chain: The Bullwhip Effect", *Management Science* 43(4): 546–558, April 1997. https://courses.ie.bilkent.edu.tr/ie102/wp-content/uploads/sites/12/2019/02/Lee-Padmanabhan-Whang-1997-MS.pdf (accessed 2026-11-11)
[^s2]: Stanford Graduate School of Business, publication record for "Information Distortion in a Supply Chain: The Bullwhip Effect" (republished in *Management Science* 50(12 suppl.), 2004). https://www.gsb.stanford.edu/faculty-research/publications/information-distortion-supply-chain-bullwhip-effect (accessed 2026-11-11)
[^s3]: Hau L. Lee, V. Padmanabhan and Seungjin Whang, "The Bullwhip Effect in Supply Chains", *MIT Sloan Management Review*, 1997. https://sloanreview.mit.edu/article/the-bullwhip-effect-in-supply-chains (accessed 2026-11-11)
[^s4]: Gerard P. Cachon, Taylor Randall and Glen M. Schmidt, "In Search of the Bullwhip Effect", *Manufacturing & Service Operations Management*, 2007. https://repository.upenn.edu/oid_papers/137 (accessed 2026-11-11)
[^s5]: Robert L. Bray and Haim Mendelson, "Information Transmission and the Bullwhip Effect: An Empirical Investigation", *Management Science* 58(5): 860–875, May 2012. https://www.kellogg.northwestern.edu/faculty/bray/doc/bw/bw_d.pdf (accessed 2026-11-11)
