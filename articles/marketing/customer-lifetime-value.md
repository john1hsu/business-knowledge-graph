---
id: kt:customer-lifetime-value
type: Metric
title: Customer Lifetime Value
aliases: [CLV, CLTV, LTV, lifetime value, customer lifetime value analysis]
domain: marketing
summary: >-
  The present value of all future profits a firm expects to earn from a customer over the whole
  relationship, net of the cost of serving and (often) acquiring that customer; summed across
  current and future customers it gives customer equity.
broader: [kt:marketing-metrics, kt:customer-relationship-management]
related: [kt:segmentation-targeting-positioning, kt:freemium, kt:network-effect]
relations:
  - {predicate: influencedBy, object: kt:discounted-cash-flow}
  - {predicate: partOf, object: kt:customer-equity}
  - {predicate: alternativeTo, object: kt:rfm-analysis}
sources:
  - id: s1
    title: "Valuing Customers (author manuscript, Journal of Marketing Research)"
    publisher: Columbia Business School (Gupta, Lehmann and Stuart)
    url: https://business.columbia.edu/sites/default/files-efs/pubfiles/534/Valuing_Customers--JMR_2003.pdf
    type: peer-reviewed
    accessed: 2026-11-08
  - id: s2
    title: "Modeling Customer Lifetime Value"
    publisher: Journal of Service Research 9(2), SAGE
    url: https://studysites.uk.sagepub.com/clow/study/articles/PDFs/03_Gupta.pdf
    type: peer-reviewed
    accessed: 2026-11-08
  - id: s3
    title: "Customer Metrics: The Past, the Present, and the Future in Academia and Practice"
    publisher: Marketing Science Institute (Special Report 05-200)
    url: https://thearf-org-unified-admin.s3.amazonaws.com/MSI/2020/06/MSI_SR_05-200c.pdf
    type: academic
    accessed: 2026-11-08
  - id: s4
    title: "The Mismanagement of Customer Loyalty"
    publisher: Harvard Business Review (author copy hosted by UW Foster School of Business)
    url: https://foster.uw.edu/wp-content/uploads/2016/07/11_Reinartz_Kumar_2002.pdf
    type: practitioner-journal
    accessed: 2026-11-08
created: 2026-11-08
---

# Customer Lifetime Value

**Customer lifetime value (CLV)** is the present value of all the future profits a firm expects to earn from a customer over the life of the relationship.[^s2] It borrows the logic of discounted cash flow from finance, but it is computed for an individual customer or segment and explicitly models the chance that the customer defects to a competitor.[^s3] Adding up the CLV of all current and future customers gives **customer equity**, which researchers use to link marketing decisions to shareholder value.[^s3][^s2]

## Origin

CLV grew out of direct and catalog marketing, where early models judged mailing decisions by short-term profit before later work shifted to maximizing profit over a long horizon.[^s3] Its strategic profile rose in the 1990s, when Reichheld and Sasser argued that retention drives profitability, and when scholars such as Srivastava, Shervani and Fahey connected customer assets to shareholder value.[^s3] A landmark step was Sunil Gupta, Donald Lehmann and Jennifer Ames Stuart's paper "Valuing Customers", published in the Journal of Marketing Research in 2004, which used mostly public financial data to value whole firms as the sum of their customers' lifetime values.[^s1][^s3]

## How it works

In its general form, CLV sums each future period's margin (price paid minus the direct cost of serving the customer), weights it by the probability the customer is still buying in that period, discounts it at the firm's cost of capital, and subtracts the acquisition cost.[^s2] With a constant margin *m*, retention rate *r* and discount rate *i* over an infinite horizon, this collapses to CLV = *m* × *r* / (1 + *i* − *r*); the fraction is a "margin multiple" that equals roughly 4 at 90% retention and a 12% discount rate.[^s2] If margins grow at rate *g*, the multiple becomes *r* / [1 + *i* − *r*(1 + *g*)].[^s2] More sophisticated approaches include RFM scoring, probability models for non-contractual settings, econometric and persistence models, and machine-learning methods.[^s2]

The formula highlights which levers matter. In Gupta, Lehmann and Stuart's five-company study, a 1% improvement in retention raised customer value by between 2.45% (Amazon) and 6.75% (Ameritrade), versus roughly 1.0–1.3% for a 1% margin improvement and well under 1% for a 1% cut in acquisition cost.[^s1]

## Evidence and critiques

Customer-based valuation tracks market value reasonably well in some cases. As of March 31, 2002, estimated customer value was close to market capitalization for Capital One ($11.0 billion vs. $14.1 billion), Ameritrade and E*Trade, but far below it for Amazon ($0.8 billion vs. $5.4 billion) and eBay ($1.9 billion vs. $15.9 billion).[^s1] The authors suggested the market might be overvaluing those two firms, or that the model missed option value and network effects.[^s1] Field studies also show CLV-based targeting beating simpler rules: at one catalog retailer, revenue from the top 30% of customers ranked by CLV was 33% higher than from the top 30% ranked by RFM.[^s2]

The main critiques concern assumptions and data. Most CLV models treat each customer's value as independent of others, ignoring word of mouth and platform network effects; they ignore risk, so two customers with equal expected CLV but different variance are treated alike; and NPV-based CLV omits the option value of managerial flexibility.[^s3] Prediction is noisy: one study found about 55% of the true top-20% customers were misclassified.[^s3] Reinartz and Kumar challenged the assumption that loyal customers are the most profitable: across four firms and more than 16,000 customers, correlations between tenure and profit ranged only from 0.20 to 0.45, and long-standing customers often paid less and were not cheaper to serve.[^s4]

## In practice

Firms use CLV to decide how much to spend acquiring, developing and retaining each customer; companies named in the research literature as CLV users include Harrah's, IBM, Capital One, L.L. Bean and ING.[^s2] Reinartz and Kumar show the practical stakes: at a mail-order firm, RFM-style scoring kept mailing lapsed high-volume customers at a cost of roughly $1 million a year, while a lifetime-profit model told managers when to stop investing.[^s4] They recommend sorting customers by both profitability and loyalty (for example "butterflies" who are profitable but transient versus "barnacles" who are loyal but unprofitable) and treating each group differently.[^s4] CLV also disciplines promotions: in a newspaper study, subscribers acquired with a steep discount renewed at half the rate of regular-price subscribers and were worth about half as much.[^s2]

## Connections

CLV is a core **marketing metric** and the quantitative backbone of **customer relationship management**.[^s3] It is an application of **discounted cash flow** to customers, and individual CLVs add up to **customer equity**.[^s3] It is an alternative to **RFM analysis** for ranking customers, which research finds less accurate at predicting future profit.[^s2][^s4] It depends on **segmentation**, since value is estimated and acted on segment by segment, and it is central to judging **freemium** offers, where customers acquired free or at a discount can be worth less.[^s2] Its neglect of **network effects** is a known limitation, illustrated by the gap between eBay's customer value and its market value.[^s1][^s3]

## Sources
[^s1]: Sunil Gupta, Donald R. Lehmann and Jennifer Ames Stuart, "Valuing Customers", Journal of Marketing Research, 2004 (author manuscript revised February 2003). https://business.columbia.edu/sites/default/files-efs/pubfiles/534/Valuing_Customers--JMR_2003.pdf (accessed 2026-11-08)
[^s2]: Sunil Gupta, Dominique Hanssens, Bruce Hardie, William Kahn, V. Kumar, Nathaniel Lin, Nalini Ravishanker and S. Sriram, "Modeling Customer Lifetime Value", Journal of Service Research 9(2), 2006, pp. 139–155. https://studysites.uk.sagepub.com/clow/study/articles/PDFs/03_Gupta.pdf (accessed 2026-11-08)
[^s3]: Sunil Gupta and Valarie Zeithaml, "Customer Metrics: The Past, the Present, and the Future in Academia and Practice", Marketing Science Institute Special Report 05-200, 2005. https://thearf-org-unified-admin.s3.amazonaws.com/MSI/2020/06/MSI_SR_05-200c.pdf (accessed 2026-11-08)
[^s4]: Werner Reinartz and V. Kumar, "The Mismanagement of Customer Loyalty", Harvard Business Review, July 2002. https://foster.uw.edu/wp-content/uploads/2016/07/11_Reinartz_Kumar_2002.pdf (accessed 2026-11-08)
