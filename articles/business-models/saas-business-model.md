---
id: kt:saas-business-model
type: BusinessModel
title: Software as a Service
aliases: [SaaS, SaaS business model, software-as-a-service model, hosted software model]
domain: business-models
summary: >-
  A business model in which a vendor runs an application on its own cloud infrastructure and sells
  customers access to it over a network, usually for a recurring subscription or usage-based fee,
  instead of selling a perpetual licence to install and maintain the software themselves.
broader: [kt:subscription-business-model, kt:business-model]
related: [kt:freemium, kt:network-effect, kt:two-sided-market, kt:customer-lifetime-value]
relations:
  - {predicate: dependsOn, object: kt:cloud-computing}
  - {predicate: contrastsWith, object: kt:perpetual-software-license}
  - {predicate: exemplifiedBy, object: kt:salesforce}
  - {predicate: measuredBy, object: kt:churn-rate}
  - {predicate: causes, object: kt:switching-costs}
sources:
  - id: s1
    title: "The NIST Definition of Cloud Computing (SP 800-145)"
    publisher: National Institute of Standards and Technology (Peter Mell and Timothy Grance), 2011
    url: https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf
    type: government
    accessed: 2026-11-09
  - id: s2
    title: "Cloud Computing and SaaS as New Computing Platforms"
    publisher: Communications of the ACM (Michael A. Cusumano), 2010, doi:10.1145/1721654.1721667
    url: https://cacm.acm.org/opinion/cloud-computing-and-saas-as-new-computing-platforms
    type: practitioner-journal
    accessed: 2026-11-09
  - id: s3
    title: "Salesforce, Inc. Form 10-K for the fiscal year ended January 31, 2026"
    publisher: U.S. Securities and Exchange Commission (EDGAR)
    url: https://www.sec.gov/Archives/edgar/data/1108524/000110852426000060/crm-20260131.htm
    type: primary
    accessed: 2026-11-09
  - id: s4
    title: "Software-as-a-Service Revenue Models"
    publisher: IT Professional 15(3), 2013 (Arto Ojala; JYX repository record), doi:10.1109/MITP.2012.73
    url: https://jyx.jyu.fi/handle/123456789/38554
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s5
    title: "Software as a Service"
    publisher: Encyclopaedia Britannica
    url: https://www.britannica.com/topic/Software-as-a-Service
    type: encyclopedia
    accessed: 2026-11-09
created: 2026-11-09
---

# Software as a Service

**Software as a Service (SaaS)** is a way of building a software business in which the vendor hosts and operates the application and customers use it over the internet, typically through a web browser or an API, paying a recurring fee for access rather than buying a licence and running the software on their own machines.[^s1][^s5] The term comes from cloud computing: the U.S. National Institute of Standards and Technology (NIST) defines SaaS as one of three cloud service models, alongside Platform as a Service (PaaS) and Infrastructure as a Service (IaaS).[^s1] Britannica describes it as the supply of a discrete application to outside users, whether businesses (accounting, CRM) or consumers (photo storage and sharing).[^s5]

## Origin and definition

NIST's 2011 definition, written by Peter Mell and Timothy Grance, is the standard reference. Under SaaS the customer controls neither the network, servers, operating systems and storage nor, in general, the application's features; at most it adjusts limited user-specific settings. In PaaS the customer deploys its own applications on the provider's platform, and in IaaS it rents raw computing, storage and networking and runs whatever software it likes.[^s1] NIST also lists five essential characteristics of cloud services that SaaS inherits: on-demand self-service, broad network access, resource pooling, rapid elasticity and measured service.[^s1] Salesforce.com is the textbook commercial example; Britannica cites the company as an example of the SaaS subscription model for business software.[^s5]

## How the model works

The economic shift is from a one-time sale to a recurring relationship. In the traditional enterprise-software model, Michael Cusumano observed in 2010, licence and maintenance fees made up roughly two-thirds of major product companies' revenue, with customization and services making up the rest; SaaS folds most of this into a single subscription price.[^s2] Because one shared, multi-tenant deployment serves many customers, the vendor captures utilization gains from pooled data centres and pushes upgrades to everyone at once instead of supporting many installed versions.[^s1][^s2]

Pricing is usually subscription-based (per user or per tier) or usage-based. Arto Ojala's 2013 study in *IT Professional* frames the provider's choice as one among three options, traditional licensing, SaaS rental and SaaS pay-per-use, each with different profitability and different trade-offs for customers.[^s4] Salesforce's filing shows the mechanics at scale: it sells mainly on subscription, prices some newer offerings on consumption, signs contracts typically lasting 12 to 36 months, invoices most customers annually in advance and recognizes subscription revenue ratably over the term.[^s3] Ratable recognition means a surge or slump in new bookings shows up in reported revenue only gradually, while cash collected in advance builds a large deferred (unearned) revenue balance.[^s3]

## Evidence and critiques

The model's central vulnerability is that customers can leave. Salesforce warns that customers have no obligation to renew and may come back with fewer seats, shorter terms or cheaper editions; it reported an attrition rate of about 8% as of January 31, 2026 (excluding Slack self-service and recent acquisitions).[^s3] Retention therefore drives the value of a SaaS firm, which is why investors watch churn alongside acquisition cost and lifetime value.

Cusumano raised further critiques. Customers worry about performance on shared networks, data security, leakage of proprietary business logic and outages. Moving an existing product to SaaS often requires substantial rewriting, and incumbents risk cannibalizing high-margin licence and maintenance revenue, so he expected the shift to be gradual and partial.[^s2] He also argued that hosting software online does not by itself create an industry platform: SaaS becomes a platform only when the vendor opens its infrastructure and APIs to complementors, as Salesforce did with AppExchange and Force.com.[^s2] Network effects around such platforms may be weaker than in PC or smartphone ecosystems because most interfaces rely on standard web protocols.[^s2]

## Real-world example

Salesforce shows how far the model has matured. In fiscal 2026 (year ended January 31, 2026) it reported total revenue of $41.5 billion, of which subscription and support revenue was about $39.4 billion, or 95%.[^s3] As of the same date it reported unearned revenue of about $24.3 billion and remaining performance obligations of roughly $72.4 billion, a backlog of contracted but not-yet-recognized revenue that gives SaaS firms unusual visibility into future sales.[^s3]

## Connections

SaaS is a specific case of the broader **subscription business model** and of the general concept of a **business model**, applied to software delivered through **cloud computing**, on which it depends.[^s1] It contrasts with the **perpetual software licence** that it displaced in much enterprise software.[^s2][^s4] Many SaaS products use **freemium** tiers as an acquisition channel, and Cusumano's analysis ties SaaS platforms to **network effects** and to the logic of **two-sided markets**, where vendors court both customers and third-party developers.[^s2] Because revenue arrives over years, the model is judged through **customer lifetime value** and **churn rate**, and accumulated data and integrations create **switching costs** that make customers sticky.[^s2][^s3] **Salesforce** is its canonical example.[^s3][^s5]

## Sources
[^s1]: Peter Mell and Timothy Grance, "The NIST Definition of Cloud Computing", NIST Special Publication 800-145, September 2011. https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf (accessed 2026-11-09)
[^s2]: Michael A. Cusumano, "Cloud Computing and SaaS as New Computing Platforms", Communications of the ACM, 2010. https://cacm.acm.org/opinion/cloud-computing-and-saas-as-new-computing-platforms (accessed 2026-11-09)
[^s3]: Salesforce, Inc., Form 10-K for the fiscal year ended January 31, 2026, SEC EDGAR. https://www.sec.gov/Archives/edgar/data/1108524/000110852426000060/crm-20260131.htm (accessed 2026-11-09)
[^s4]: Arto Ojala, "Software-as-a-Service Revenue Models", IT Professional 15(3): 54–59, 2013. https://jyx.jyu.fi/handle/123456789/38554 (accessed 2026-11-09)
[^s5]: The Editors of Encyclopaedia Britannica, "Software as a Service". https://www.britannica.com/topic/Software-as-a-Service (accessed 2026-11-09)
