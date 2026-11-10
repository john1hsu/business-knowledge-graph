---
id: kt:goodwill
type: Concept
title: Goodwill
aliases: [accounting goodwill, purchased goodwill, goodwill impairment, goodwill impairment test]
domain: accounting-and-reporting
summary: >-
  An intangible asset recognised in a business combination, measured as the residual of the
  consideration paid over the acquired net identifiable assets, and under both US GAAP and IFRS
  tested for impairment rather than amortised.
broader: [kt:financial-accounting, kt:intangible-assets]
related: [kt:mergers-and-acquisitions, kt:gaap, kt:ifrs, kt:accrual-accounting, kt:discounted-cash-flow]
relations:
  - {predicate: regulatedBy, object: kt:financial-accounting-standards-board}
  - {predicate: regulatedBy, object: kt:international-accounting-standards-board}
  - {predicate: dependsOn, object: kt:fair-value-measurement}
  - {predicate: exemplifiedBy, object: kt:kraft-heinz}
sources:
  - id: s1
    title: "IAS 36 Impairment of Assets"
    publisher: IFRS Foundation
    url: https://www.ifrs.org/issued-standards/list-of-standards/ias-36-impairment-of-assets/
    type: standards-body
    accessed: 2026-11-10
  - id: s2
    title: "Basis for Conclusions on Exposure Draft: Business Combinations—Disclosures, Goodwill and Impairment"
    publisher: International Accounting Standards Board
    url: https://cdn.ifrs.org/content/dam/ifrs/project/goodwill-and-impairment/exposure-draft-2024/iasb-bc-2024-1-bcdgi.pdf
    type: standards-body
    accessed: 2026-11-10
  - id: s3
    title: "Has goodwill accounting gone bad?"
    publisher: Review of Accounting Studies 22(2), 964-1003 (Kevin K. Li and Richard G. Sloan)
    url: https://ideas.repec.org/a/spr/reaccs/v22y2017i2d10.1007_s11142-017-9401-7.html
    type: peer-reviewed
    accessed: 2026-11-10
  - id: s4
    title: "Joint FASB-IASB meeting, Agenda Paper 18A: Identifiable Intangible Assets and Subsequent Accounting for Goodwill"
    publisher: IFRS Foundation / FASB staff
    url: https://www.ifrs.org/content/dam/ifrs/meetings/2022/september/fasb-iasb/ap18a-identifiable-intangible-assets-and-subsequent-accounting-for-goodwill.pdf
    type: standards-body
    accessed: 2026-11-10
  - id: s5
    title: "Kraft Heinz Reports Fourth Quarter and Full Year 2018 Results"
    publisher: The Kraft Heinz Company
    url: https://news.kraftheinzcompany.com/press-releases-details/2019/Kraft-Heinz-Reports-Fourth-Quarter-and-Full-Year-2018-Results/default.aspx
    type: primary
    accessed: 2026-11-10
  - id: s6
    title: "FASB Eliminates Step 2 From the Goodwill Impairment Test (Heads Up, 2017)"
    publisher: Deloitte
    url: https://dart.deloitte.com/USDART/home/publications/archive/deloitte-publications/heads-up/2017/fasb-eliminates-step-2-from-goodwill
    type: consultancy
    accessed: 2026-11-10
  - id: s7
    title: "Goodwill and Impairment, Agenda Paper 18B: Relief from mandatory annual impairment test"
    publisher: International Accounting Standards Board (staff paper)
    url: https://www.ifrs.org/-/media/feature/meetings/2019/may/iasb/ap18b-goodwill-and-impairment.pdf
    type: standards-body
    accessed: 2026-11-10
created: 2026-11-10
---

# Goodwill

**Goodwill** is the intangible asset an acquirer records when it buys a business for more than the fair value of the identifiable assets it obtains, net of the liabilities it assumes. Because it captures things that cannot be separately identified and valued, such as an assembled workforce, expected synergies and going-concern value, standard setters describe it as a unique asset that cannot be measured directly; it is instead measured as a residual of the purchase accounting.[^s2] Goodwill arises only from acquisitions: internally generated goodwill is never put on the balance sheet, which is one reason the asset is so contested.[^s2]

## From amortisation to impairment-only

For decades goodwill was written off gradually. Under IFRS, the old IAS 22 required goodwill to be amortised over its useful life until IAS 36 introduced an annual impairment test in 2004.[^s2] US GAAP made the same move in the early 2000s, when SFAS 142 replaced periodic amortisation and a recoverability-based test with a fair-value-based impairment test.[^s3] Since then, under both frameworks, goodwill sits on the balance sheet at cost until a test shows it is impaired, and the resulting charge flows through the income statement as a non-cash loss.

## How the impairment test works

**IFRS (IAS 36).** Goodwill acquired in a business combination must be tested every year, whether or not there is any sign of impairment.[^s1] Because goodwill produces no cash flows of its own, it is allocated to cash-generating units (CGUs), the smallest groups of assets that generate largely independent cash inflows. A CGU is impaired when its carrying amount exceeds its recoverable amount, defined as the higher of fair value less costs of disposal and value in use (the present value of expected future cash flows).[^s1] Any loss reduces goodwill first, then the unit's other assets pro rata, and a goodwill impairment can never be reversed, unlike impairments of most other assets.[^s1]

**US GAAP (ASC 350).** Goodwill is tested at the reporting-unit level. In January 2017 the FASB issued ASU 2017-04, which eliminated the old "Step 2" calculation of the implied fair value of goodwill. An impairment is now the amount by which a reporting unit's carrying amount exceeds its fair value, capped at the goodwill allocated to that unit.[^s6] The optional qualitative "Step 0" screen remained, and the change took effect for SEC filers in periods beginning after December 15, 2019.[^s6]

## Evidence and critiques

The central criticism is that impairment-only accounting recognises losses *too little, too late*. Li and Sloan (2017) found that after SFAS 142, goodwill balances became relatively inflated and impairments untimely, that managers appear to have used the test's discretion to delay write-downs, and that investors did not fully anticipate this, so delayed impairments temporarily propped up earnings and share prices.[^s3] IASB stakeholders voiced similar concerns that losses are sometimes recognised too late to signal a failed acquisition.[^s2]

A structural cause is **shielding**. Because goodwill is tested together with other assets, the unit's *headroom* (recoverable amount above the carrying amount of its net assets, including unrecognised internally generated goodwill) absorbs declines before purchased goodwill is touched.[^s2] A 2019 IASB staff paper linked this shielding effect to the test measuring the CGU as a whole rather than goodwill itself, and recorded stakeholder views that resulting losses are often late and inadequate.[^s7]

Standard setters have repeatedly weighed bringing amortisation back and declined. The FASB's tentative leanings included straight-line amortisation over a default 10 years (capped at 25), but on June 15, 2022 the Board removed the project from its agenda, judging that the change would not sufficiently rebalance benefits and costs or materially improve decision usefulness.[^s4] The IASB likewise retained impairment-only in its March 2024 exposure draft, citing unresolved disagreement over whether goodwill is a wasting asset, inconclusive research, transition costs and the value of staying converged with US GAAP; instead it proposed better disclosure of acquisition performance and changes to value-in-use inputs.[^s2]

## Real-world example

In the fourth quarter of 2018, Kraft Heinz recorded about $15.4 billion of non-cash impairment charges: roughly $7.1 billion of goodwill, mainly in its U.S. Refrigerated and Canada Retail reporting units, plus about $8.3 billion on intangible assets, chiefly the Kraft and Oscar Mayer trademarks.[^s5] The charges turned the quarter into a net loss of $12.6 billion attributable to common shareholders, illustrating how goodwill created by a large merger can resurface years later as a single, sudden write-down.[^s5]

## Connections

Goodwill is a component of **financial accounting** and a special case of **intangible assets**, distinguished by being unidentifiable and measured as a residual.[^s2] It is created by **mergers and acquisitions** and governed by both **GAAP** (set by the **Financial Accounting Standards Board**) and **IFRS** (set by the **International Accounting Standards Board**), whose models have converged on impairment-only.[^s2][^s4] The impairment test depends on **fair value measurement** and on **discounted cash flow** estimates of value in use.[^s1] Like other **accrual accounting** judgements, it shifts when losses hit earnings rather than the cash consequences, which is why delayed impairments can mislead investors.[^s3] **Kraft Heinz**'s 2018 write-down is a widely studied example.[^s5]

## Sources
[^s1]: IFRS Foundation, "IAS 36 Impairment of Assets". https://www.ifrs.org/issued-standards/list-of-standards/ias-36-impairment-of-assets/ (accessed 2026-11-10)
[^s2]: International Accounting Standards Board, Basis for Conclusions on Exposure Draft "Business Combinations—Disclosures, Goodwill and Impairment", March 2024. https://cdn.ifrs.org/content/dam/ifrs/project/goodwill-and-impairment/exposure-draft-2024/iasb-bc-2024-1-bcdgi.pdf (accessed 2026-11-10)
[^s3]: Kevin K. Li and Richard G. Sloan, "Has goodwill accounting gone bad?", Review of Accounting Studies 22(2), 964-1003, 2017. https://ideas.repec.org/a/spr/reaccs/v22y2017i2d10.1007_s11142-017-9401-7.html (accessed 2026-11-10)
[^s4]: FASB and IASB staff, "Identifiable Intangible Assets and Subsequent Accounting for Goodwill", joint meeting Agenda Paper 18A, September 2022. https://www.ifrs.org/content/dam/ifrs/meetings/2022/september/fasb-iasb/ap18a-identifiable-intangible-assets-and-subsequent-accounting-for-goodwill.pdf (accessed 2026-11-10)
[^s5]: The Kraft Heinz Company, "Kraft Heinz Reports Fourth Quarter and Full Year 2018 Results", February 2019. https://news.kraftheinzcompany.com/press-releases-details/2019/Kraft-Heinz-Reports-Fourth-Quarter-and-Full-Year-2018-Results/default.aspx (accessed 2026-11-10)
[^s6]: Deloitte, "FASB Eliminates Step 2 From the Goodwill Impairment Test", Heads Up, 2017. https://dart.deloitte.com/USDART/home/publications/archive/deloitte-publications/heads-up/2017/fasb-eliminates-step-2-from-goodwill (accessed 2026-11-10)
[^s7]: IASB staff, "Goodwill and Impairment: Relief from mandatory annual impairment test", Agenda Paper 18B, May 2019. https://www.ifrs.org/-/media/feature/meetings/2019/may/iasb/ap18b-goodwill-and-impairment.pdf (accessed 2026-11-10)
