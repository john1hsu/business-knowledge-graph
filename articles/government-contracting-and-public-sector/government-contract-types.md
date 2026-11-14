---
id: kt:government-contract-types
type: Framework
title: "Government Contract Types: Fixed-Price, Cost-Reimbursement and Incentive Arrangements"
aliases: [government contract types, federal contract types, contract types, FAR Part 16 contract types, contract type selection]
domain: government-contracting-and-public-sector
summary: >-
  The menu of pricing arrangements a government buyer can use, set out for US federal agencies in FAR
  Part 16, ranging from firm-fixed-price (contractor bears the cost risk) through incentive contracts to
  cost-plus-fixed-fee (government bears most of it), chosen to match how predictable the work's cost is.
broader: [kt:public-procurement, kt:contract-pricing]
related: [kt:indefinite-delivery-indefinite-quantity, kt:truth-in-negotiations-act, kt:contracting-officer, kt:revolutionary-far-overhaul]
relations:
  - {predicate: regulatedBy, object: kt:federal-acquisition-regulation}
  - {predicate: regulatedBy, object: kt:executive-order-14402}
  - {predicate: hasPart, object: kt:cost-plus-contract}
  - {predicate: hasPart, object: kt:fixed-price-contract}
  - {predicate: mitigates, object: kt:moral-hazard}
  - {predicate: influencedBy, object: kt:principal-agent-problem}
sources:
  - id: s1
    title: "FAR 16.101 - General (Part 16, Types of Contracts)"
    publisher: Acquisition.gov (FAR Council / GSA)
    url: https://www.acquisition.gov/far/16.101
    type: government
    accessed: 2026-11-14
  - id: s2
    title: "Types of Federal Procurement Contracts (R48784)"
    publisher: Congressional Research Service (via EveryCRSReport)
    url: https://www.everycrsreport.com/reports/R48784.html
    type: government
    accessed: 2026-11-14
  - id: s3
    title: "Contract Management: Extent of Federal Spending under Cost-Reimbursement Contracts Unclear and Key Controls Not Always Used (GAO-09-921)"
    publisher: U.S. Government Accountability Office
    url: https://www.gao.gov/products/GAO-09-921
    type: government
    accessed: 2026-11-14
  - id: s4
    title: "Executive Order 14402: Promoting Efficiency, Accountability, and Performance in Federal Contracting"
    publisher: Federal Register (91 FR 24325), via GovInfo
    url: https://www.govinfo.gov/content/pkg/FR-2026-05-05/html/2026-08900.htm
    type: primary
    accessed: 2026-11-14
  - id: s5
    title: "FAR Overhaul - Part 16 (model deviation text)"
    publisher: Acquisition.gov (OFPP / FAR Council / GSA)
    url: https://acquisition.gov/far-overhaul/far-part-deviation-guide/far-overhaul-part-16
    type: government
    accessed: 2026-11-14
  - id: s6
    title: "Bidding for Contracts: A Principal-Agent Analysis"
    publisher: RAND Journal of Economics 17(3), 326-338 (via IDEAS/RePEc)
    url: https://ideas.repec.org:443/a/rje/randje/v17y1986iautumnp326-338.html
    type: peer-reviewed
    accessed: 2026-11-14
created: 2026-11-14
---

# Government Contract Types

**Government contract types** are the pricing arrangements a public buyer chooses between when it signs a contract. In US federal procurement they are codified in Part 16 of the Federal Acquisition Regulation (FAR), which explains that the types differ along two dimensions: how much of the cost-of-performance risk the contractor carries (and when), and how much profit incentive it gets for meeting or beating targets.[^s1] Choosing a type is therefore a decision about who absorbs cost surprises and how strongly the seller is motivated to control costs, and it is one of the most consequential calls a **contracting officer** makes, largely negotiated and documented in the contract file.[^s2]

## The spectrum

FAR Part 16 groups the arrangements into two families, **fixed-price** and **cost-reimbursement**, and places **incentive** contracts between them.[^s1] At one end, a *firm-fixed-price* contract makes the contractor fully responsible for performance costs, so it keeps any profit or absorbs any loss; at the other, a *cost-plus-fixed-fee* contract reimburses allowable costs and pays a fee that does not move with cost, leaving the contractor minimal cost responsibility.[^s1]

The Congressional Research Service (CRS), in a January 2026 overview, lists six fixed-price variants, including firm-fixed-price, fixed-price with economic price adjustment for long-term inflation risk, fixed-price incentive, price-redetermination forms and firm-fixed-price level-of-effort for studies.[^s2] The cost family covers pure cost, cost-sharing, cost-plus-incentive-fee, cost-plus-award-fee and cost-plus-fixed-fee contracts. Incentive arrangements use a formula, such as a negotiated share ratio for overruns and underruns, to tie profit to cost, schedule or technical results.[^s2] Outside the two families sit **time-and-materials** and **labor-hour** contracts (hourly rates under a ceiling), **letter contracts** for urgent starts, and indefinite-delivery vehicles such as **IDIQ** contracts, which define ordering terms rather than a single price.[^s2]

## Selection rules and controls

Cost-reimbursement contracts may be used only when requirements or costs cannot be estimated well enough for a fixed price; they are barred for commercial products and services, need approval above the contracting officer, and pay only costs that are reasonable, allocable and consistent with cost-accounting rules.[^s2] GAO called this type high risk for the government in a 2009 review, because costs can escalate and the government pays incurred costs whether or not the work is finished; it recommended that agencies consider moving to firmer pricing as experience accumulates and fix gaps in how contract type was recorded in the federal procurement database. GAO reports all four of those recommendations as implemented, including a 2011 FAR interim rule.[^s3]

Policy shifted further in 2026. Executive Order 14402, signed April 30, 2026, makes fixed-price contracts with performance-based elements the default, requires a written justification for any non-fixed-price contract, and requires agency-head approval above $100 million for the Department of War, $35 million for NASA, $25 million for DHS and $10 million elsewhere, with exemptions for emergencies and for research and pre-production development of major systems.[^s4] The order cites roughly $120 billion obligated on cost-reimbursement consulting contracts in FY2024.[^s4] The FAR overhaul's model deviation text for Part 16 builds the same preference into the regulation, adds risk-management detail to acquisition plans, bans rollover of unearned award fee, and requires a cost incentive in any multiple-incentive contract.[^s5]

## Evidence and critiques

Contract theory frames the choice as a principal-agent problem. McAfee and McMillan's 1986 model of competitive bidding under **moral hazard** finds that the optimal linear contract is never cost-plus, may be fixed-price, and is usually an incentive contract, because it must balance cost-control incentives against risk-sharing with risk-averse bidders and the benefits of competition.[^s6] That logic supports incentive and fixed-price forms but also explains the weakness of rigid fixed prices for uncertain work. CRS notes that some contractors, Boeing among them, have reported losses on fixed-price defense programs such as the KC-46A tanker and T-7A trainer, and that Congress may weigh limits on which types can be used for complex, high-cost programs.[^s2] CRS also flags a measurement problem: in FY2024 about 57 percent of DOD and 63 percent of non-DOD award dollars flowed through indefinite-delivery vehicles, so headline type shares depend on how orders are coded.[^s2]

## In practice

For a well-defined commercial purchase, a contracting officer will normally use firm-fixed-price. For a first-of-a-kind development effort, cost-reimbursement or a cost-plus-incentive-fee contract shares the risk, with the expectation, reinforced since 2026, of moving to fixed-price once production costs are known.[^s3][^s4][^s5] Contractors seeking cost-type work need an accounting system able to segregate costs, and agencies need enough staff to oversee such contracts.[^s3][^s5]

## Connections

Contract types are a core building block of **public procurement** and of **contract pricing**, and are **regulated by** the **Federal Acquisition Regulation** (Part 16) and, since 2026, **Executive Order 14402**.[^s1][^s4] They **have parts** such as the **fixed-price contract** and the **cost-plus contract**.[^s1][^s2] The design problem is **influenced by** the **principal-agent problem**, and incentive structures aim to **mitigate moral hazard**.[^s6] **IDIQ** vehicles layer ordering terms on top of these types; the **Truth in Negotiations Act** governs cost data behind negotiated prices; the **contracting officer** selects and documents the type; and the **Revolutionary FAR Overhaul** is rewriting Part 16 itself.[^s2][^s5]

## Sources

[^s1]: Acquisition.gov, "FAR 16.101 - General", Federal Acquisition Regulation Part 16 (FAC 2026-01). https://www.acquisition.gov/far/16.101 (accessed 2026-11-14)
[^s2]: Congressional Research Service, "Types of Federal Procurement Contracts" (R48784), January 6, 2026. https://www.everycrsreport.com/reports/R48784.html (accessed 2026-11-14)
[^s3]: U.S. Government Accountability Office, "Contract Management: Cost-Reimbursement Contracts" (GAO-09-921), September 30, 2009. https://www.gao.gov/products/GAO-09-921 (accessed 2026-11-14)
[^s4]: Executive Order 14402, "Promoting Efficiency, Accountability, and Performance in Federal Contracting", 91 FR 24325, May 5, 2026. https://www.govinfo.gov/content/pkg/FR-2026-05-05/html/2026-08900.htm (accessed 2026-11-14)
[^s5]: Acquisition.gov, "FAR Overhaul - Part 16" (model deviation text). https://acquisition.gov/far-overhaul/far-part-deviation-guide/far-overhaul-part-16 (accessed 2026-11-14)
[^s6]: R. Preston McAfee and John McMillan, "Bidding for Contracts: A Principal-Agent Analysis", RAND Journal of Economics 17(3), 1986, pp. 326-338. https://ideas.repec.org:443/a/rje/randje/v17y1986iautumnp326-338.html (accessed 2026-11-14)
