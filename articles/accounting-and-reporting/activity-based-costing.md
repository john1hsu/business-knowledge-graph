---
id: kt:activity-based-costing
type: Practice
title: "Activity-Based Costing: Assigning Overhead by Activities"
aliases: [activity-based costing, ABC costing, activity-based cost accounting]
domain: accounting-and-reporting
summary: >-
  A managerial cost-accounting method, popularised by Robin Cooper and Robert S. Kaplan in the late 1980s,
  that assigns overhead to products, services and customers through multiple activity cost pools and cost
  drivers instead of a single volume-based rate, to reveal which offerings actually make money.
broader: [kt:managerial-accounting, kt:cost-accounting]
related: [kt:enterprise-resource-planning, kt:pricing-strategy, kt:cost-structure]
relations:
  - {predicate: createdBy, object: kt:robin-cooper}
  - {predicate: createdBy, object: kt:robert-s-kaplan}
  - {predicate: introducedIn, object: kt:measure-costs-right-make-the-right-decisions-1988}
  - {predicate: followedBy, object: kt:time-driven-activity-based-costing}
  - {predicate: contrastsWith, object: kt:gaap}
sources:
  - id: s1
    title: "6.3 Calculate Activity-Based Product Costs"
    publisher: "OpenStax (Principles of Accounting, Volume 2: Managerial Accounting)"
    url: https://openstax.org/books/principles-managerial-accounting/pages/6-3-calculate-activity-based-product-costs
    type: textbook
    accessed: 2026-11-12
  - id: s2
    title: "6.4 Compare and Contrast Traditional and Activity-Based Costing Systems"
    publisher: "OpenStax (Principles of Accounting, Volume 2: Managerial Accounting)"
    url: https://openstax.org/books/principles-managerial-accounting/pages/6-4-compare-and-contrast-traditional-and-activity-based-costing-systems
    type: textbook
    accessed: 2026-11-12
  - id: s3
    title: "Measure Costs Right: Make the Right Decisions"
    publisher: Harvard Business Review
    url: https://store.hbr.org/product/measure-costs-right-make-the-right-decisions/88503
    type: primary
    accessed: 2026-11-12
  - id: s4
    title: "Time-Driven Activity-Based Costing"
    publisher: SSRN (Harvard Business School working paper)
    url: https://papers.ssrn.com/abstract=485443
    type: academic
    accessed: 2026-11-12
  - id: s5
    title: "Rethinking Activity-Based Costing"
    publisher: Harvard Business School Working Knowledge
    url: https://www.library.hbs.edu/working-knowledge/rethinking-activity-based-costing
    type: academic
    accessed: 2026-11-12
  - id: s6
    title: "Reasons for not changing to activity-based costing: a survey of Irish firms"
    publisher: PSU Research Review (Emerald)
    url: https://www.emerald.com/insight/content/doi/10.1108/prr-12-2016-0017/full/html
    type: peer-reviewed
    accessed: 2026-11-12
created: 2026-11-12
---

# Activity-Based Costing

Activity-based costing (ABC) is a managerial cost-accounting method that traces overhead to products, services or customers according to the activities they consume, such as machine setups, purchasing, inspection or order handling. Where a traditional system spreads all overhead with one predetermined rate based on direct labour hours, labour dollars or machine hours, ABC builds several overhead pools, each with its own cost driver and rate.[^s1][^s2] The aim is not better external reporting but better internal decisions about pricing, product mix and which offerings are profitable.[^s2]

## Origin

Single-rate overhead allocation made sense when materials and labour dominated product cost and overhead was small. As automation cut labour and overhead grew, in some firms beyond labour cost, a labour-hour rate became a poor proxy for what really caused overhead, while new technology made activities easier to track.[^s1] Robin Cooper and Robert S. Kaplan crystallised the argument in "Measure Costs Right: Make the Right Decisions" in Harvard Business Review in September 1988. They warned that managers of multi-product firms were setting prices and product mix from distorted costs, often noticing only after profits and competitiveness slipped, and proposed activity-based costing as the remedy. They also argued that firms need not scrap their official cost systems, because the two can run side by side.[^s3] The method began in manufacturing but has since spread to service industries.[^s1]

## How it works

Textbook ABC follows five steps.[^s1]

1. Identify the activities that consume overhead, keeping those with the largest cost impact.[^s1]
2. Group the overhead of related activities into cost pools.[^s1]
3. Choose a cost driver for each pool, such as number of setups or inspection hours, and estimate its annual volume.[^s1]
4. Divide each pool's estimated cost by its driver volume to get an activity rate.[^s1]
5. Apply the rates to each product's actual driver usage, then add the resulting overhead per unit to direct materials and labour.[^s1]

Analysts often sort activities into a cost hierarchy: unit-level costs incurred for every unit, batch-level costs incurred per production run, product-level costs such as engineering and testing for a product line, and factory-level costs such as rent and supervision that support production as a whole.[^s1] The hierarchy explains ABC's typical finding: setups and engineering are spread over few units in a low-volume product, so moving to ABC usually raises its unit cost and lowers that of high-volume products.[^s2]

## Evidence and critiques

ABC's main limitation is cost and effort. OpenStax notes that it takes more time and money to install and maintain than a single-rate system, needs objective driver data and employee buy-in, and can leave some manufacturing costs, such as factory heating, out of product costs. It is also not acceptable under GAAP for inventory valuation, so firms using it for decisions must still compute traditional product costs for external reports.[^s2]

Kaplan himself became a leading critic of the original design. In a 2003 working paper with Steven R. Anderson, he observed that conventional ABC depends on costly interviews and surveys, rests on subjective time estimates that are hard to validate, and is expensive to update as processes change.[^s4] Because the surveys asked employees how they split their time, they implicitly assumed staff were fully utilised and so hid idle capacity.[^s5] The authors' answer, time-driven ABC, needs only the cost per unit of capacity and the time each activity takes, can draw on ERP and CRM data, and exposes unused capacity.[^s4] In their worked example, a customer-service department costing $560,000 a quarter with 700,000 minutes of practical capacity has a capacity cost of $0.80 a minute, so an eight-minute order costs $6.40 to process.[^s5]

Adoption has remained modest. A 2017 survey of large Irish firms found that 18.7% of 171 respondents used ABC; non-adopters mostly said they were satisfied with existing methods, saw no need to change or found the change too time-consuming, rather than citing technical or IT barriers. The authors cite earlier adoption rates of 15% in the UK and 11.8% to 27.9% in earlier surveys of Irish firms.[^s6]

## In practice

OpenStax's illustration shows the decision stakes. For a fictional instrument maker, a low-volume "Solo" product cost $18.50 a unit under traditional allocation but $22.50 under ABC, revealing a loss the old system concealed, while the high-volume "Orchestra" product fell from $20.00 to $17.70.[^s2] In time-driven applications, Kaplan and Anderson report that hose and belt fabricator Lewis-Goetz discovered one plant running at 27% of capacity and chose to hold that capacity for an expected large contract rather than downsize.[^s5]

## Connections

ABC is a technique within managerial and cost accounting, created by Robin Cooper and Robert S. Kaplan and introduced to a broad managerial audience in their 1988 Harvard Business Review article.[^s3] It contrasts with GAAP product costing, which still governs external inventory figures.[^s2] Its successor, time-driven ABC, keeps the activity logic but simplifies data collection and relies on enterprise resource planning systems for transaction data.[^s4] Its product and customer profitability figures inform pricing strategy and product-mix decisions, and its cost hierarchy gives a more granular view of a firm's cost structure than a single overhead rate.[^s1][^s3]

## Sources
[^s1]: OpenStax, *Principles of Accounting, Volume 2: Managerial Accounting*, section 6.3, "Calculate Activity-Based Product Costs". https://openstax.org/books/principles-managerial-accounting/pages/6-3-calculate-activity-based-product-costs (accessed 2026-11-12)
[^s2]: OpenStax, *Principles of Accounting, Volume 2: Managerial Accounting*, section 6.4, "Compare and Contrast Traditional and Activity-Based Costing Systems". https://openstax.org/books/principles-managerial-accounting/pages/6-4-compare-and-contrast-traditional-and-activity-based-costing-systems (accessed 2026-11-12)
[^s3]: Robin Cooper and Robert S. Kaplan, "Measure Costs Right: Make the Right Decisions", Harvard Business Review, September 1988. https://store.hbr.org/product/measure-costs-right-make-the-right-decisions/88503 (accessed 2026-11-12)
[^s4]: Robert S. Kaplan and Steven R. Anderson, "Time-Driven Activity-Based Costing", working paper, November 2003. https://papers.ssrn.com/abstract=485443 (accessed 2026-11-12)
[^s5]: Robert S. Kaplan and Steven R. Anderson, "Rethinking Activity-Based Costing", HBS Working Knowledge, January 24, 2005. https://www.library.hbs.edu/working-knowledge/rethinking-activity-based-costing (accessed 2026-11-12)
[^s6]: Martin Quinn, Otman Elafi and Mark Mulgrew, "Reasons for not changing to activity-based costing: a survey of Irish firms", PSU Research Review 1(1), 2017, pp. 63–70. https://www.emerald.com/insight/content/doi/10.1108/prr-12-2016-0017/full/html (accessed 2026-11-12)
