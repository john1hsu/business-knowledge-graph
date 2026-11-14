---
id: kt:just-in-time
type: Practice
title: "Just-in-Time (JIT): Synchronizing Supply with Demand to Minimize Inventory"
aliases: [just-in-time, just-in-time production, just-in-time manufacturing, JIT production, JIT inventory]
domain: operations-and-supply-chain
summary: >-
  A production and inventory practice, originated at Toyota, of making and delivering only what
  the next process or customer needs, when it is needed and in the quantity needed, using pull
  signals, continuous flow and takt time so that inventory, lead time and waste are kept to a minimum.
broader: [kt:inventory-management, kt:operations-management]
related: [kt:lean-manufacturing, kt:working-capital, kt:bullwhip-effect]
relations:
  - {predicate: partOf, object: kt:toyota-production-system}
  - {predicate: createdBy, object: kt:kiichiro-toyoda}
  - {predicate: createdBy, object: kt:taiichi-ohno}
  - {predicate: hasPart, object: kt:kanban}
  - {predicate: contrastsWith, object: kt:material-requirements-planning}
  - {predicate: exemplifiedBy, object: kt:toyota-motor-corporation}
sources:
  - id: s1
    title: "Toyota Production System"
    publisher: Toyota Motor Corporation
    url: https://global.toyota/en/company/vision-and-philosophy/production-system/index.html
    type: primary
    accessed: 2026-11-14
  - id: s2
    title: "Just-in-Time Production (Lean Lexicon entry)"
    publisher: Lean Enterprise Institute
    url: https://www.lean.org/lexicon-terms/just-in-time-production/
    type: organization
    accessed: 2026-11-14
  - id: s3
    title: "Relationship Between Just-in-Time Manufacturing Practices and Performance: A Meta-Analysis Investigation"
    publisher: Journal of Operations Management (Georgia Southern University research portal)
    url: https://scholars.georgiasouthern.edu/en/publications/relationship-between-just-in-time-manufacturing-practices-and-per-3/
    type: peer-reviewed
    accessed: 2026-11-14
  - id: s4
    title: "Spread Too Thin: The Impact of Lean Inventories (IFDP 1342)"
    publisher: Board of Governors of the Federal Reserve System
    url: https://www.federalreserve.gov/econres/ifdp/spread-too-thin-the-impact-of-lean-inventories.htm
    type: government
    accessed: 2026-11-14
  - id: s5
    title: "How Toyota thrives when the chips are down"
    publisher: The Japan Times (Reuters)
    url: https://www.japantimes.co.jp/news/2021/03/09/business/corporate-business/toyota-semiconductors-3-11
    type: news
    accessed: 2026-11-14
created: 2026-11-14
---

# Just-in-Time (JIT)

Just-in-time is a way of running production so that each process makes and delivers only what the next process or the customer actually needs, at the moment it is needed and in the amount needed.[^s2] Toyota describes it as one of the two pillars of the Toyota Production System, alongside jidoka, and frames its principles as building to the pace of sales and never letting goods or information sit idle between steps.[^s1] The goal is to strip out waste so that quality rises while cost, resource use and lead times fall.[^s2] As a practice, JIT is narrower than the whole Toyota system or the generic "lean" model: it is the flow-and-inventory discipline inside them.

## Origin

Toyota credits the idea to founder Kiichiro Toyoda, who argued in the 1930s that a car cannot be finished if even one part is missing, so every plant and supplier must be synchronized to the final assembly line.[^s1][^s2] Taiichi Ohno, then running the machine shop at Toyota's main plant, turned the idea into a working system; he dated his first practical steps to 1949–50, with backing from Eiji Toyoda.[^s2][^s1] Because a car contains more than 30,000 parts, many made by outside partners, JIT was from the start a supply-chain discipline as much as a factory technique.[^s1]

## How it works

JIT rests on three operating elements: a pull system, continuous flow and takt time, with production leveling (heijunka) as the foundation that keeps demand on each process smooth.[^s2] In a pull system the downstream process withdraws the parts it needs from a small buffer, and the upstream process replenishes only what was taken; nothing is pushed forward on a forecast.[^s1] Takt time sets the rhythm of work to the rate of customer demand, and continuous flow moves items one at a time or in small lots between steps instead of in large batches.[^s2] Toyota stresses that JIT is not zero inventory: since building every part only after an order arrives would take months, it keeps a deliberate minimum of stock on the line so that a car can start as soon as it is ordered.[^s1] Kanban cards are the best-known signal used to run the pull loop.[^s2]

The financial logic is that smaller inventories tie up less capital and expose defects quickly, but the system only works if setups are short, quality is high and suppliers deliver reliably; it is simple in principle and demanding in practice.[^s2]

## Evidence and critiques

Research broadly supports a performance payoff. A meta-analysis by MacKelprang and Nair in the *Journal of Operations Management* (2010), pooling studies published from 1992 to 2008, found a positive link between JIT practices and aggregate performance, but not every practice improved every outcome, and contextual moderators mattered a great deal.[^s3]

The main critique is fragility. A Federal Reserve working paper by Julio Ortiz (IFDP 1342, April 2022) found that US firms adopting JIT held less inventory relative to sales and enjoyed higher, steadier sales, yet reacted more sharply to the business cycle and to natural disasters hitting suppliers.[^s4] His structural model put the gain from JIT at roughly 1.3% of firm value, but implied an output contraction about 15% deeper after a large unexpected supply shock, because firms either ran out of materials or scrambled to stockpile them.[^s4] Lean buffers, in other words, trade resilience for efficiency, which can amplify the kind of upstream swings seen in the bullwhip effect.

## In practice

Toyota's own response shows how practitioners reconcile JIT with risk. After the March 2011 earthquake, which took about four months to restore Toyota's domestic output to normal, the company built a business continuity plan, flagged roughly 500 of more than 1,200 parts and materials as needing secure supply, and asked suppliers to hold two to six months of semiconductors, depending on lead time.[^s5] That buffer helped Toyota keep building cars in early 2021 while rivals idled plants during the global chip shortage, illustrating that mature JIT users hold strategic stock for long-lead, single-source items rather than applying minimal inventory everywhere.[^s5]

## Connections

JIT is a component of the **Toyota Production System**, conceived by Kiichiro Toyoda and systematized by **Taiichi Ohno** at **Toyota Motor Corporation**.[^s1][^s2] It sits under **inventory management** and **operations management**, and its pull loop is commonly run with **kanban**.[^s2] It was later folded into the broader **lean manufacturing** model. JIT contrasts with **material requirements planning**, which pushes production from forecasts and schedules rather than actual consumption. Its lower inventories shrink **working capital**, while its thin buffers raise exposure to supply shocks and demand amplification such as the **bullwhip effect**.[^s4]

## Sources
[^s1]: Toyota Motor Corporation, "Toyota Production System". https://global.toyota/en/company/vision-and-philosophy/production-system/index.html (accessed 2026-11-14)
[^s2]: Lean Enterprise Institute, "Just-in-Time Production", Lean Lexicon. https://www.lean.org/lexicon-terms/just-in-time-production/ (accessed 2026-11-14)
[^s3]: Alan W. MacKelprang and Anand Nair, "Relationship Between Just-in-Time Manufacturing Practices and Performance: A Meta-Analysis Investigation", Journal of Operations Management 28 (2010), doi:10.1016/j.jom.2009.10.002. https://scholars.georgiasouthern.edu/en/publications/relationship-between-just-in-time-manufacturing-practices-and-per-3/ (accessed 2026-11-14)
[^s4]: Julio L. Ortiz, "Spread Too Thin: The Impact of Lean Inventories", International Finance Discussion Papers 1342, Board of Governors of the Federal Reserve System, April 2022. https://www.federalreserve.gov/econres/ifdp/spread-too-thin-the-impact-of-lean-inventories.htm (accessed 2026-11-14)
[^s5]: Reuters via The Japan Times, "How Toyota thrives when the chips are down", 9 March 2021. https://www.japantimes.co.jp/news/2021/03/09/business/corporate-business/toyota-semiconductors-3-11 (accessed 2026-11-14)
