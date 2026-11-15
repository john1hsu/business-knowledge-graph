---
id: kt:churn-rate
type: Metric
title: "Churn Rate: Measuring Customer Attrition and Retention"
aliases: [churn, customer churn, customer attrition rate, attrition rate, defection rate, customer defection rate]
domain: marketing
summary: >-
  The share of a firm's customers who stop doing business with it during a given period, usually
  disconnections or cancellations divided by the average customer base; it is the complement of
  the retention rate and a central input to customer lifetime value.
broader: [kt:marketing-metrics, kt:customer-relationship-management]
related: [kt:customer-lifetime-value, kt:customer-satisfaction, kt:subscription-business-model, kt:saas-business-model]
relations:
  - {predicate: dependsOn, object: kt:switching-costs}
  - {predicate: exemplifiedBy, object: kt:t-mobile-us}
sources:
  - id: s1
    title: "In Pursuit of Enhanced Customer Retention Management: Review, Key Issues, and Future Directions"
    publisher: Customer Needs and Solutions 5(1-2), Springer (author version hosted by Columbia Business School)
    url: https://drupalgsb-test.paas.cc.columbia.edu/sites/default/files-efs/pubfiles/25780/ascarza_et_al_choice_symposium.pdf
    type: peer-reviewed
    accessed: 2026-11-15
  - id: s2
    title: "Zero Defections: Quality Comes to Services"
    publisher: Harvard Business Review (summary hosted by Bain & Company)
    url: https://www.bain.com/insights/zero-defections-quality-comes-to-services-harvard-business-review-hbr/
    type: practitioner-journal
    accessed: 2026-11-15
  - id: s3
    title: "T-Mobile US, Inc. Form 10-K for fiscal year 2017"
    publisher: U.S. Securities and Exchange Commission (EDGAR)
    url: https://www.sec.gov/Archives/edgar/data/0001283699/000128369918000011/tmus12312017form10-k.htm
    type: primary
    accessed: 2026-11-15
  - id: s4
    title: "How to Project Customer Retention"
    publisher: Journal of Interactive Marketing 21(1) (author copy hosted by Wharton)
    url: https://faculty.wharton.upenn.edu/wp-content/uploads/2012/04/Fader_hardie_jim_07.pdf
    type: peer-reviewed
    accessed: 2026-11-15
  - id: s5
    title: "Some Customers Are Best Left Alone"
    publisher: Columbia Business School, Chazen Global Insights
    url: https://business.columbia.edu/insights/chazen-global-insights/some-customers-are-best-left-alone
    type: academic
    accessed: 2026-11-15
created: 2026-11-15
---

# Churn Rate: Measuring Customer Attrition and Retention

**Churn rate** is the proportion of customers who end their relationship with a firm over a stated period. Researchers define retention as a customer continuing to transact with the firm, and churn as its counterpart: the point at which that transacting stops, whether or not the customer formally cancels.[^s1] In a typical public-company definition, churn is the number of customers whose service was disconnected, expressed as a percentage of the average number of customers over the period.[^s3] Because churn and retention are two sides of one quantity, a 2% monthly churn rate implies 98% monthly retention.

## Origin and why it matters

An influential case for managing churn came from Frederick Reichheld and W. Earl Sasser, who argued in *Harvard Business Review* in 1990 that customer defections can affect a service firm's profits more than scale, market share or unit cost, and that retaining just 5% more customers could raise profits by nearly 100% in the businesses they studied.[^s2] They urged managers to treat the defection rate as a leading indicator of profit and to interview departing customers to find the weaknesses that drive them away.[^s2] Their showcase was MBNA, which after 1982 committed to keeping every customer; by the time of the article it lost about 5% of customers a year, roughly half its industry's rate, and had climbed from 38th to 4th among card issuers.[^s2]

Later academic work put a number on the link. Summarising Gupta, Lehmann and Stuart, Ascarza and colleagues report an average retention elasticity of about 4.9: a one-percent gain in retention lifts customer equity by nearly five percent.[^s1]

## How it is measured

Measurement depends on the setting. In **contractual** businesses such as telecom or newspaper subscriptions, the firm observes cancellations directly; in **non-contractual** ones such as online retail, churn must be inferred from inactivity, using recency, the ratio of recency to a customer's usual inter-purchase time, or a model-based probability that the customer is still "alive".[^s1] Many digital services are hybrids, where users can either cancel or simply drift away, and customers may stop engaging long before they formally leave.[^s1]

Reported churn is usually an aggregate, and aggregates mislead. If a customer base mixes low-churn and high-churn types, the high-churn customers leave first, so the overall retention rate rises over time even though no individual's propensity has changed.[^s1] Fader and Hardie's shifted-beta-geometric model formalises this "ruse of heterogeneity" and shows that naive curve fits to a few years of survival data can miss twelfth-year survival by 30% to over 90%.[^s4] The practical advice is to report churn by acquisition cohort or segment and only then weight it into a total.[^s1] Telecom monthly figures are a further trap, because contracts expire at different times; measuring renewal among customers whose contracts ended in the period avoids the distortion.[^s1]

## Evidence and critiques

The hardest problem is acting on churn, not counting it. In a churn-prediction tournament reported by Neslin and co-authors, the average top-decile lift was only about 2.1: with a base churn rate near 2%, roughly 96% of the customers flagged as highest risk did not leave.[^s1] Predictors are also not causes; demographics may forecast churn without driving it, which limits what managers can fix.[^s1]

Intervening can backfire. In a field experiment with about 65,000 South American mobile subscribers, Eva Ascarza, Raghuram Iyengar and Martin Schleicher found that proactively encouraging users to move to better-fitting plans raised churn from 6% to 10%, with the worst effects among customers whose usage was volatile or falling.[^s5] Ascarza's later "retention futility" work argues that firms should target customers whose behaviour a campaign will actually change, using uplift models, rather than those with the highest predicted churn.[^s1] Reichheld and Sasser's own remedy was diagnostic rather than predictive: learn from customers who have already defected and fix the causes.[^s2]

## In practice

Wireless carriers report churn every quarter. T-Mobile US disclosed branded postpaid phone churn of 1.18% for 2017, down from 1.30% in 2016 and 1.39% in 2015, against branded prepaid churn of 4.04% in 2017.[^s3] It attributed the 2017 improvement partly to moving higher-churn customers to a wholesale MVNO partner and partly to better network quality and customer satisfaction, a reminder that reported churn can shift through changes in who is counted as well as through loyalty.[^s3]

## Connections

Churn rate is one of the core **marketing metrics** and the outcome that **customer relationship management** programs try to reduce.[^s1] It is the decay term in **customer lifetime value**, so small changes in churn move CLV and customer equity sharply.[^s1][^s4] It is the headline health measure of the **subscription business model** and its software form, **SaaS**, where revenue depends on renewals.[^s4] Churn depends on **switching costs**, which research lists among its main predictors alongside **customer satisfaction**, usage and social connections.[^s1] Reichheld and Sasser framed lower defection as the payoff of service quality.[^s2] **T-Mobile US** exemplifies how firms define and disclose it.[^s3]

## Sources
[^s1]: Eva Ascarza, Scott A. Neslin, Oded Netzer, Zachery Anderson, Peter S. Fader, Sunil Gupta, Bruce G. S. Hardie, Aurélie Lemmens, Barak Libai, David Neal, Foster Provost and Rom Schrift, "In Pursuit of Enhanced Customer Retention Management: Review, Key Issues, and Future Directions", Customer Needs and Solutions 5(1-2), 2018, pp. 65–81. https://drupalgsb-test.paas.cc.columbia.edu/sites/default/files-efs/pubfiles/25780/ascarza_et_al_choice_symposium.pdf (accessed 2026-11-15)
[^s2]: Frederick F. Reichheld and W. Earl Sasser Jr., "Zero Defections: Quality Comes to Services", Harvard Business Review, September 1990. https://www.bain.com/insights/zero-defections-quality-comes-to-services-harvard-business-review-hbr/ (accessed 2026-11-15)
[^s3]: T-Mobile US, Inc., Annual Report on Form 10-K for the year ended December 31, 2017, filed with the SEC. https://www.sec.gov/Archives/edgar/data/0001283699/000128369918000011/tmus12312017form10-k.htm (accessed 2026-11-15)
[^s4]: Peter S. Fader and Bruce G. S. Hardie, "How to Project Customer Retention", Journal of Interactive Marketing 21(1), 2007. https://faculty.wharton.upenn.edu/wp-content/uploads/2012/04/Fader_hardie_jim_07.pdf (accessed 2026-11-15)
[^s5]: "Some Customers Are Best Left Alone", Columbia Business School Chazen Global Insights, June 12, 2015, on research by Eva Ascarza, Raghuram Iyengar and Martin Schleicher. https://business.columbia.edu/insights/chazen-global-insights/some-customers-are-best-left-alone (accessed 2026-11-15)
