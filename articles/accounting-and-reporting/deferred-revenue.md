---
id: kt:deferred-revenue
type: Concept
title: Deferred Revenue
aliases: [unearned revenue, contract liability, customer deposits received in advance]
domain: accounting-and-reporting
summary: >-
  A liability recorded when a business collects (or has an unconditional right to) payment from a
  customer before delivering the promised goods or services; it becomes revenue as the business performs.
broader: [kt:financial-accounting]
related: [kt:accrual-accounting, kt:saas-business-model, kt:working-capital, kt:subscription-business-model]
relations:
  - {predicate: regulatedBy, object: kt:revenue-recognition-asc-606}
  - {predicate: regulatedBy, object: kt:ifrs}
  - {predicate: contrastsWith, object: kt:accrued-revenue}
  - {predicate: exemplifiedBy, object: kt:salesforce}
sources:
  - id: s1
    title: "Principles of Accounting, Volume 1, Section 4.2: Discuss the Adjustment Process and Illustrate Common Types of Adjusting Entries"
    publisher: OpenStax, Rice University
    url: https://openstax.org/books/principles-financial-accounting/pages/4-2-discuss-the-adjustment-process-and-illustrate-common-types-of-adjusting-entries
    type: textbook
    accessed: 2026-11-11
  - id: s2
    title: "IFRS 15 Revenue from Contracts with Customers"
    publisher: IFRS Foundation (copy hosted by the Institute of Chartered Accountants of Bangladesh)
    url: https://www.icab.org.bd/icabadmin/uploads/ckeditor/7910IFRS%2015.pdf
    type: standards-body
    accessed: 2026-11-11
  - id: s3
    title: "Salesforce Fiscal 2026 Annual Report (Form 10-K)"
    publisher: Salesforce, Inc.
    url: https://s205.q4cdn.com/626266368/files/doc_financials/2026/ar/Salesforce-FY26-Annual-Report_Bookmarked.pdf
    type: primary
    accessed: 2026-11-11
  - id: s4
    title: "Implications of Deferred Revenue Changes for Future Financial Performance and Market Underreaction"
    publisher: Quarterly Journal of Finance and Accounting (record at Central Washington University ScholarWorks)
    url: https://digitalcommons.cwu.edu/cobfac_accounting/12
    type: peer-reviewed
    accessed: 2026-11-11
  - id: s5
    title: "The Impact of CEO Compensation Incentives on Financial Reporting Choices: Evidence from Potential Ghost Revenues Created in Mergers and Acquisitions"
    publisher: University of Tennessee, Knoxville (doctoral dissertation)
    url: https://trace.tennessee.edu/server/api/core/bitstreams/d3b5f4f6-0ab2-4942-8790-61c89e96fe89/content
    type: academic
    accessed: 2026-11-11
  - id: s6
    title: "Heads Up: FASB Issues ASU on Accounting for Contract Assets and Contract Liabilities From Contracts With Customers in a Business Combination"
    publisher: Deloitte DART
    url: https://dart.deloitte.com/USDART/home/publications/deloitte/heads-up/2021/fasb-asu-contract-assets-liabilities-revenue
    type: consultancy
    accessed: 2026-11-11
created: 2026-11-11
---

# Deferred Revenue

**Deferred revenue** (also called **unearned revenue**, and under current standards a **contract liability**) is money a business has received from a customer, or is unconditionally owed, before it has delivered the goods or services paid for. Because the work is not yet done, the cash cannot be counted as revenue on receipt; instead it is recorded as a liability, since the company owes the customer performance (or a refund).[^s1] It is one of the two classic deferrals in accrual accounting: it sits on the balance sheet until earned and then moves to the income statement.[^s1]

## Origin and standing

The treatment follows from the revenue recognition principle of accrual accounting, which ties revenue to performance rather than to the timing of cash.[^s1] The converged revenue standards, IFRS 15 and its US counterpart ASC Topic 606, formalised the idea as a *contract liability*: an entity's obligation to transfer goods or services to a customer for which it has already received consideration, or for which consideration is due.[^s2] IFRS 15 requires a contract liability to be presented when the customer pays, or the entity gains an unconditional right to payment, before the goods or services are transferred, whichever comes first; companies may keep using other labels such as "deferred revenue" on the balance sheet as long as the disclosures remain clear.[^s2]

## How it works

The bookkeeping is a two-step deferral. When cash arrives, the company debits Cash and credits an unearned revenue account, which carries a normal credit balance.[^s1] At the end of each period it judges how much of the obligation it has fulfilled and moves that portion to revenue with an adjusting entry that involves no cash.[^s1] In OpenStax's example, a law firm collects $48,000 of retainers, earns 40% of the work by period end, and so transfers $19,200 to fee revenue, leaving $28,800 still owed as a liability.[^s1] The adjustment is needed precisely because finishing a service rarely generates a document that would trigger an entry on its own.[^s1]

Deferred revenue is distinct from a receivable: a receivable is an unconditional right to cash where only the passage of time stands between the company and payment, whereas a contract liability is an obligation to perform.[^s2]

## Evidence and critiques

Research treats deferred revenue as informative about the future. Zhong, Wang and Ning (2016) find that increases in current deferred revenue are positively associated with sales growth, margins and return on assets over the following two years, and that investors only partly price this signal, producing abnormal returns they attribute to market underreaction.[^s4] Earlier work by Prakash and Sinha (2013) argued that the then-prevailing standards mismatched revenues and expenses, so that changes in deferred revenue weakened the persistence of profit margins.[^s5]

The account also involves management judgment. A review of the literature notes that rules on deferring revenue curbed some opportunistic reporting but reduced the value relevance of earnings, and that discretion over deferred revenue can still be used to manage earnings.[^s5] A long-standing problem arose in acquisitions: buyers measured acquired deferred revenue at fair value, often below the target's book balance, so revenue the target would have reported simply disappeared, the so-called deferred revenue "haircut".[^s6] The FASB's ASU 2021-08, issued in October 2021, removed this by requiring acquirers to measure acquired contract liabilities under Topic 606, effective for public business entities in fiscal years beginning after 15 December 2022.[^s6]

## In practice

Subscription software firms carry the largest balances relative to sales. Salesforce, which recognises subscription revenue ratably over contracts that typically run 12 to 36 months, reported unearned revenue of $24.3 billion at 31 January 2026, up from $20.7 billion a year earlier, against fiscal-2026 total revenue of $41.5 billion.[^s3] Its filing explains that unearned revenue consists mainly of subscription billings and that strong fourth-quarter invoicing makes the first quarter its biggest collections quarter, which is why analysts watch deferred revenue and the broader remaining performance obligation ($72.4 billion as of FY2026) alongside reported revenue.[^s3]

## Connections

Deferred revenue is a direct application of accrual accounting within financial accounting, and the mirror image of accrued revenue, where a company has performed but not yet billed.[^s1] Its recognition and presentation are regulated by ASC 606 and by IFRS through IFRS 15.[^s2] It is central to the economics of the SaaS business model and the subscription business model, where annual billing in advance builds large balances, as Salesforce illustrates.[^s3] As a current liability it enters working capital analysis, and changes in it offer analysts a leading indicator of growth.[^s4]

## Sources

[^s1]: OpenStax, *Principles of Accounting, Volume 1: Financial Accounting*, Section 4.2, "Discuss the Adjustment Process and Illustrate Common Types of Adjusting Entries". https://openstax.org/books/principles-financial-accounting/pages/4-2-discuss-the-adjustment-process-and-illustrate-common-types-of-adjusting-entries (accessed 2026-11-11)
[^s2]: IFRS Foundation, *IFRS 15 Revenue from Contracts with Customers*, paras. 105–109 and Appendix A. https://www.icab.org.bd/icabadmin/uploads/ckeditor/7910IFRS%2015.pdf (accessed 2026-11-11)
[^s3]: Salesforce, Inc., *Fiscal 2026 Annual Report on Form 10-K* (fiscal year ended January 31, 2026). https://s205.q4cdn.com/626266368/files/doc_financials/2026/ar/Salesforce-FY26-Annual-Report_Bookmarked.pdf (accessed 2026-11-11)
[^s4]: Ke Zhong, Fen Wang and Yixi Ning, "Implications of Deferred Revenue Changes for Future Financial Performance and Market Underreaction", *Quarterly Journal of Finance and Accounting* 54(3–4), 2016, pp. 65–100. https://digitalcommons.cwu.edu/cobfac_accounting/12 (accessed 2026-11-11)
[^s5]: Jason Alan Ashby, *The Impact of CEO Compensation Incentives on Financial Reporting Choices: Evidence from Potential Ghost Revenues Created in Mergers and Acquisitions*, PhD dissertation, University of Tennessee, Knoxville, 2021. https://trace.tennessee.edu/server/api/core/bitstreams/d3b5f4f6-0ab2-4942-8790-61c89e96fe89/content (accessed 2026-11-11)
[^s6]: Deloitte, "FASB Issues ASU on Accounting for Contract Assets and Contract Liabilities From Contracts With Customers in a Business Combination", *Heads Up*, 2 November 2021. https://dart.deloitte.com/USDART/home/publications/deloitte/heads-up/2021/fasb-asu-contract-assets-liabilities-revenue (accessed 2026-11-11)
