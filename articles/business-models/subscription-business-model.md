---
id: kt:subscription-business-model
type: BusinessModel
title: "Subscription Business Model: Selling Ongoing Access"
aliases: [subscription business model, subscription model, subscription-based business model, recurring-revenue model, subscription economy]
domain: business-models
summary: >-
  A business model in which customers pay a recurring fee, usually monthly or annually, for continuing
  access to a product, content or service rather than buying it in a one-time transaction, so that the
  firm's economics depend on retaining customers and growing their lifetime value.
broader: [kt:business-model]
related: [kt:saas-business-model, kt:membership-warehouse-club, kt:freemium, kt:deferred-revenue, kt:switching-costs]
relations:
  - {predicate: measuredBy, object: kt:churn-rate}
  - {predicate: measuredBy, object: kt:customer-lifetime-value}
  - {predicate: exemplifiedBy, object: kt:netflix-business-model-shift}
  - {predicate: contrastsWith, object: kt:razor-and-blades-model}
  - {predicate: regulatedBy, object: kt:ftc-negative-option-rule}
sources:
  - id: s1
    title: "Subscription-based business models in the context of tech firms: theory and applications"
    publisher: International Journal of Industrial Engineering and Operations Management (Emerald), 2023, doi:10.1108/IJIEOM-06-2023-0054 (Bocconi IRIS repository copy)
    url: https://iris.unibocconi.it/retrieve/d62dad76-4e6d-4bf0-a31c-d8f5b8c00213/10-1108_IJIEOM-06-2023-0054.pdf
    type: peer-reviewed
    accessed: 2026-11-12
  - id: s2
    title: "How to Project Customer Retention"
    publisher: Journal of Interactive Marketing 21(1), 2007, pp. 76–89 (Wharton faculty copy)
    url: https://faculty.wharton.upenn.edu/wp-content/uploads/2012/04/Fader_hardie_jim_07.pdf
    type: peer-reviewed
    accessed: 2026-11-12
  - id: s3
    title: "Paying Too Much and Being Happy About It: Existence, Causes, and Consequences of Tariff-Choice Biases"
    publisher: Journal of Marketing Research 43, 2006, pp. 212–223 (UCLA Anderson copy)
    url: https://www.anderson.ucla.edu/documents/areas/fac/marketing/paying_too_much.pdf
    type: peer-reviewed
    accessed: 2026-11-12
  - id: s4
    title: "With Subscription Fatigue Setting In, Companies Need to Think Hard About Fees"
    publisher: Harvard Business School Working Knowledge, 2023
    url: https://www.library.hbs.edu/working-knowledge/with-subscription-fatigue-setting-in-companies-need-to-think-hard-about-fees
    type: academic
    accessed: 2026-11-12
  - id: s5
    title: "What's the Future of the Subscription Model?"
    publisher: Harvard Business School Working Knowledge, 2001
    url: https://www.library.hbs.edu/working-knowledge/whats-the-future-of-the-subscription-model
    type: academic
    accessed: 2026-11-12
  - id: s6
    title: "Negative Option Rule (Rule Concerning the Use of Prenotification Negative Option Plans)"
    publisher: U.S. Federal Trade Commission, rulemaking page (last modified March 2026)
    url: https://www.ftc.gov/legal-library/browse/rules/negative-option-rule
    type: government
    accessed: 2026-11-12
created: 2026-11-12
---

# Subscription Business Model

A **subscription business model** charges customers a recurring payment in exchange for continuing access to content, products or services, instead of selling each item in a separate one-time transaction.[^s1] The value proposition shifts from ownership to use: the customer buys access, and the firm commits to keep delivering and improving the offering for as long as the customer stays.[^s1] Newspapers, magazines and utilities have long sold this way; the model's modern growth comes from software, streaming media, consumer boxes and "as-a-service" offerings in industrial markets.[^s4][^s5]

## Origin and development

There is no single inventor of the subscription model, but management scholars began treating it as a strategic choice rather than a billing format around the turn of the century. Writing in HBS Working Knowledge in 2001, James Heskett noted that subscriptions give firms steady, predictable revenue, cash paid in advance, and an incentive to invest in quality because success depends on keeping customers; he also pointed to industrial firms such as IBM and GE moving toward service contracts.[^s5] He warned, however, that free, advertising-funded internet services were training customers not to pay.[^s5] By the 2020s, research summarized by HBS's Elie Ofek and Zuora's Amy Konary reported that nearly 75% of direct-to-consumer companies offered some subscription option and that subscription-based firms had grown 3.7 times faster than the S&P 500 over the preceding decade (figures as of 2023).[^s4]

## How it works

A recent peer-reviewed study of tech firms that switched to subscriptions describes the model through four linked elements.[^s1]

- **Value proposition:** usership instead of ownership, bundled services, and continuous improvement delivered automatically to existing customers.[^s1]
- **Value creation:** each billing cycle and usage event produces data that the firm uses to refine the offer and deepen the relationship.[^s1]
- **Value capture:** predictable recurring payments, which require operations and billing systems able to handle many small, repeated transactions.[^s1]
- **Performance metrics:** monthly recurring revenue, churn, retention and customer lifetime value replace short-term product margin as the headline measures.[^s1]

Pricing designs vary: a single flat price, a free base tier with paid upgrades (freemium), or several tiers aimed at different segments, as with Zoom's free, small-business and enterprise plans.[^s4] For customers, subscriptions spread cost over time and remove large upfront payments, which is one reason software and industrial services such as Caterpillar's maintenance offerings have moved to them.[^s4]

Because a subscriber's value depends on how long they stay, forecasting retention is central. Peter Fader and Bruce Hardie showed that fitting simple curves to a few years of retention data badly mis-projects survival, and proposed the shifted-beta-geometric model, in which each customer has a constant churn probability but those probabilities differ across customers.[^s2] The model explains a pattern subscription managers observe: aggregate retention rates rise over time, not because any individual becomes more loyal but because high-churn customers leave first.[^s2]

## Evidence and critiques

Behavioral research suggests flat-rate subscriptions can be more profitable than their unit economics imply. Studying 10,882 customers of a European internet provider, Anja Lambrecht and Bernd Skiera found that many chose a flat rate even when pay-per-use would have been cheaper, driven by a wish to insure against bill variability, the greater enjoyment of usage without a running meter, and overestimation of usage.[^s3] This flat-rate bias did not significantly raise churn and increased profit, whereas customers who wrongly chose pay-per-use churned much more.[^s3]

The model also has clear limits. Ofek warns that "subscription fatigue" means a monthly charge does not guarantee revenue, and that poorly designed fees can drive away good customers; BMW faced backlash in 2022 for proposing monthly fees for heated seats in cars buyers felt they already owned.[^s4] Converting from one-time sales sacrifices large upfront payments and requires retraining salespeople.[^s4] Regulators have also targeted plans that are hard to cancel. The U.S. Federal Trade Commission's Negative Option Rule aims to stop recurring charges consumers did not intend to accept and to let them cancel without unwarranted obstacles; the FTC announced a stricter "click-to-cancel" version in October 2024, but after court challenges it published a February 2026 notice revising the rule to conform to federal court decisions and in March 2026 opened new rulemaking on possible amendments.[^s6]

## Real-world example

Netflix and Spotify are the standard examples of the unlimited-service-from-one-provider configuration: a single recurring fee buys unbounded use of a catalogue, so growth depends on adding members and keeping them rather than on selling individual titles.[^s1] In business-to-business markets the same logic appears in software-as-a-service contracts, which spare clients large upfront payments, and in platform services sold by Amazon Web Services and IBM.[^s4]

## Connections

The subscription model is a type of **business model**, and **software as a service** is its best-known software form.[^s4] It is measured by **churn rate** and **customer lifetime value**, the metrics that retention models such as Fader and Hardie's are built to forecast.[^s1][^s2] The **membership warehouse club** applies it through an annual access fee, and **freemium** is a common entry tier into paid plans.[^s4] Fees collected before service is delivered are recorded as **deferred revenue**, and the inconvenience of switching vendors creates **switching costs** that support loyalty.[^s4] It contrasts with the **razor-and-blades model**, which profits from repeat consumable sales rather than a fee for access. **Netflix's shift to streaming** exemplifies it.[^s1] Cancellation and renewal practices are regulated by the FTC's **negative option rule**.[^s6]

## Sources
[^s1]: Christoffer Weland, Johannes Lindström, Behzad Maleki Vishkaei and Pietro De Giovanni, "Subscription-based business models in the context of tech firms: theory and applications", International Journal of Industrial Engineering and Operations Management, 2023, doi:10.1108/IJIEOM-06-2023-0054. https://iris.unibocconi.it/retrieve/d62dad76-4e6d-4bf0-a31c-d8f5b8c00213/10-1108_IJIEOM-06-2023-0054.pdf (accessed 2026-11-12)
[^s2]: Peter S. Fader and Bruce G. S. Hardie, "How to Project Customer Retention", Journal of Interactive Marketing 21(1), 2007, pp. 76–89. https://faculty.wharton.upenn.edu/wp-content/uploads/2012/04/Fader_hardie_jim_07.pdf (accessed 2026-11-12)
[^s3]: Anja Lambrecht and Bernd Skiera, "Paying Too Much and Being Happy About It: Existence, Causes, and Consequences of Tariff-Choice Biases", Journal of Marketing Research 43, 2006, pp. 212–223. https://www.anderson.ucla.edu/documents/areas/fac/marketing/paying_too_much.pdf (accessed 2026-11-12)
[^s4]: Jay Fitzgerald, "With Subscription Fatigue Setting In, Companies Need to Think Hard About Fees", Harvard Business School Working Knowledge, 17 October 2023. https://www.library.hbs.edu/working-knowledge/with-subscription-fatigue-setting-in-companies-need-to-think-hard-about-fees (accessed 2026-11-12)
[^s5]: James L. Heskett, "What's the Future of the Subscription Model?", Harvard Business School Working Knowledge, 4 June 2001. https://www.library.hbs.edu/working-knowledge/whats-the-future-of-the-subscription-model (accessed 2026-11-12)
[^s6]: U.S. Federal Trade Commission, "Negative Option Rule" (Rule Concerning the Use of Prenotification Negative Option Plans), rulemaking history page, last modified 18 March 2026. https://www.ftc.gov/legal-library/browse/rules/negative-option-rule (accessed 2026-11-12)
