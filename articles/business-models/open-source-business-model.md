---
id: kt:open-source-business-model
type: BusinessModel
title: "Open-Source Business Model: Monetizing Freely Licensed Software Through Services, Open Core and Hosting"
aliases: [open source business model, commercial open source, commercial open source software, COSS, open core model]
domain: business-models
summary: >-
  A business model in which a firm gives away software under an open source license, so anyone may use,
  modify and redistribute it, and earns revenue from complements such as support subscriptions, commercial
  licenses, proprietary add-on features or hosted services.
broader: [kt:business-model]
related: [kt:freemium, kt:subscription-business-model, kt:open-innovation, kt:razor-and-blades-model]
relations:
  - {predicate: exemplifiedBy, object: kt:red-hat}
  - {predicate: studiedIn, object: kt:some-simple-economics-of-open-source-2002}
  - {predicate: contrastsWith, object: kt:proprietary-software-licensing}
  - {predicate: dependsOn, object: kt:network-effect}
sources:
  - id: s1
    title: "Some Simple Economics of Open Source"
    publisher: Journal of Industrial Economics 50(2), 2002 (Lerner and Tirole; EconPapers/RePEc record)
    url: https://econpapers.repec.org/RePEc:bla:jindec:v:50:y:2002:i:2:p:197-234
    type: peer-reviewed
    accessed: 2026-11-17
  - id: s2
    title: "The Simple Economics of Open Source"
    publisher: Harvard Business School Working Knowledge
    url: https://hbswk.hbs.edu/item/the-simple-economics-of-open-source
    type: academic
    accessed: 2026-11-17
  - id: s3
    title: "The Commercial Open Source Business Model"
    publisher: AMCIS 2009 Proceedings, paper 104 (Dirk Riehle; AIS eLibrary)
    url: https://aisel.aisnet.org/amcis2009/104
    type: peer-reviewed
    accessed: 2026-11-17
  - id: s4
    title: "The Single-Vendor Commercial Open Source Business Model (author's article)"
    publisher: Dirk Riehle (author website)
    url: https://dirkriehle.com/?p=823
    type: primary
    accessed: 2026-11-17
  - id: s5
    title: "Red Hat, Inc. Form 10-K for the fiscal year ended February 28, 2019"
    publisher: U.S. Securities and Exchange Commission (EDGAR)
    url: https://www.sec.gov/Archives/edgar/data/1087423/000108742319000012/rht-10kq4fy19.htm
    type: primary
    accessed: 2026-11-17
  - id: s6
    title: "IBM Completes Acquisition of Red Hat"
    publisher: IBM Investor Relations
    url: https://www.ibm.com/investor/news/ibm-completes-acquisition-of-red-hat
    type: primary
    accessed: 2026-11-17
  - id: s7
    title: "HashiCorp switches its products to the Business Source License (news report)"
    publisher: The Register
    url: https://theregister.com/2023/08/11/hashicorp_bsl_licence/
    type: news
    accessed: 2026-11-17
created: 2026-11-17
---

# Open-Source Business Model

An open-source business model is a way of making money from software that the firm deliberately gives away. The code is released under an open source license, so users may run, study, change and redistribute it without paying, and the firm earns its revenue from something adjacent to the code: support and update subscriptions, a commercial license for customers who cannot accept the open license, proprietary features layered on a free core, consulting, or a hosted version. Economists first treated the phenomenon as a puzzle, since it seemed to contradict the usual logic of appropriating returns from intellectual property.[^s1][^s3]

## Origin and the economics behind it

Josh Lerner of Harvard Business School and Jean Tirole gave the best-known early economic account in "Some Simple Economics of Open Source", published in the *Journal of Industrial Economics* in 2002. They argued that labor economics, especially the career-concerns literature, together with industrial organization theory, explains much of what looked like altruism: developers gain immediate benefits from fixing software they use, and delayed benefits from signaling their skill to employers, founders and venture capitalists.[^s1][^s2] Open source suits signaling because individual contributions are visible and attributable, unlike work inside a closed codebase.[^s2]

For firms, Lerner and Tirole described two broad postures. A reactive firm sells paid services or products that complement community software, filling gaps the volunteers leave. A proactive firm releases some of its own code to stimulate adoption and capture value later, which the authors likened to giving away razors in order to sell blades.[^s2]

## How it works

Dirk Riehle, writing at AMCIS in 2009, defined commercial open source as software owned by a single firm that earns significant direct revenue from it. Because the firm holds the copyright, it can relicense the code; outside contributions are often accepted only with a copyright assignment for this reason.[^s3][^s4] Common revenue mechanisms include:

- **Dual licensing:** the product ships under a reciprocal license such as the GPL, and customers who cannot accept its terms buy a commercial license instead.[^s4]
- **Open core:** a free core is combined with withheld, paid features, a pairing Riehle describes as dual licensing plus freemium.[^s4]
- **Support subscriptions:** customers pay for operational comfort, meaning support, bug-fix streams and monitoring, plus consulting and training.[^s4]

Riehle argues the model's advantage lies on the cost side. Users adopt before they buy, so sales leads arrive with an internal champion; satisfied users market the product; and the community tests releases, reports bugs and answers routine support questions. He reports user-to-customer conversion rates of roughly 0.5–2% in practitioner accounts.[^s3][^s4]

## Evidence and critiques

The evidence base is thinner than the enthusiasm. Riehle's own paper notes that it rests on practitioners' public statements rather than systematic data, and he identifies the central risk as the commercial product ending up competing with the firm's own free project.[^s3][^s4] Lerner and Tirole flagged further hazards: a project can be "hijacked" by someone who builds a proprietary platform on top of it, and commercial pressure may crowd out the volunteer creativity that made the project valuable.[^s2]

A recurring tension since the late 2010s is cloud providers offering hosted versions of open source products without paying the originating firm. Several vendors responded by moving to source-available licenses that restrict commercial use. On 10 August 2023 HashiCorp announced that future releases of Terraform, Vagrant and other tools would use the Business Source License, which keeps the code visible but is not an open source license; critics called the move "open washing," and the article lists Couchbase, Cockroach Labs, MongoDB and Elastic among firms that had taken similar steps.[^s7] The episode shows the model's weak point: the license that drives adoption also limits how much value the originator can capture.

## In practice: Red Hat

Red Hat is the canonical support-subscription case. Its 10-K for fiscal 2019 (year ended 28 February 2019) describes an open source development model drawing on a global contributor community, with revenue earned mainly through subscriptions that bundle support, security updates and fixes, certification with a hardware and software ecosystem, and protection against certain intellectual-property claims. Total revenue that year was about $3.36 billion, and infrastructure offerings led by Red Hat Enterprise Linux accounted for 63.4% of it.[^s5] IBM completed its acquisition of Red Hat on 9 July 2019 for $190 per share in cash, an equity value of about $34 billion, showing that a firm whose core product was freely licensed could command a large valuation.[^s6]

## Connections

The model is a specific kind of **business model** whose value capture is decoupled from the core product. It overlaps with **freemium** in the open-core variant and with the **subscription business model** in the Red Hat variant, and Lerner and Tirole explicitly compared proactive code release to the **razor-and-blades model**.[^s2][^s4] It is a form of **open innovation**, since the firm relies on outside contributors for development, testing and support.[^s3] Its foundational analysis is Lerner and Tirole's 2002 paper, its leading example is Red Hat, and it contrasts with proprietary software licensing, where the code itself is the product sold.[^s1][^s5] Its sales and marketing advantage depends on a community that grows as more users adopt, a **network effect**-like dynamic.[^s4]

## Sources
[^s1]: Josh Lerner and Jean Tirole, "Some Simple Economics of Open Source", Journal of Industrial Economics 50(2), 2002, pp. 197–234 (EconPapers record). https://econpapers.repec.org/RePEc:bla:jindec:v:50:y:2002:i:2:p:197-234 (accessed 2026-11-17)
[^s2]: Martha Lagace, "The Simple Economics of Open Source", Harvard Business School Working Knowledge. https://hbswk.hbs.edu/item/the-simple-economics-of-open-source (accessed 2026-11-17)
[^s3]: Dirk Riehle, "The Commercial Open Source Business Model", AMCIS 2009 Proceedings, paper 104. https://aisel.aisnet.org/amcis2009/104 (accessed 2026-11-17)
[^s4]: Dirk Riehle, "The Single-Vendor Commercial Open Source Business Model". https://dirkriehle.com/?p=823 (accessed 2026-11-17)
[^s5]: Red Hat, Inc., Form 10-K for fiscal year ended February 28, 2019, SEC EDGAR. https://www.sec.gov/Archives/edgar/data/1087423/000108742319000012/rht-10kq4fy19.htm (accessed 2026-11-17)
[^s6]: IBM, "IBM Completes Acquisition of Red Hat", 9 July 2019. https://www.ibm.com/investor/news/ibm-completes-acquisition-of-red-hat (accessed 2026-11-17)
[^s7]: The Register, report on HashiCorp's switch to the Business Source License, 11 August 2023. https://theregister.com/2023/08/11/hashicorp_bsl_licence/ (accessed 2026-11-17)
