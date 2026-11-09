---
id: kt:enterprise-resource-planning
type: Practice
title: Enterprise Resource Planning
aliases: [ERP, ERP system, enterprise system]
domain: operations-and-supply-chain
summary: >-
  The use of a single, packaged, integrated software system with a shared database to run a firm's core
  transactions and processes across functions such as manufacturing, supply chain, sales, finance and human
  resources; it grew out of MRP and MRP II, and the term was coined by Gartner in the early 1990s.
broader: [kt:production-planning-and-control, kt:information-systems]
related: [kt:bill-of-materials, kt:inventory-management, kt:customer-relationship-management, kt:business-process-reengineering]
relations:
  - {predicate: influencedBy, object: kt:material-requirements-planning}
  - {predicate: precededBy, object: kt:manufacturing-resource-planning}
  - {predicate: dependsOn, object: kt:bill-of-materials}
  - {predicate: exemplifiedBy, object: kt:sap}
  - {predicate: exemplifiedBy, object: kt:hershey-erp-implementation}
sources:
  - id: s1
    title: "Introduction to ERP systems (Supply Chain Innovation course)"
    publisher: University of Twente (via FutureLearn)
    url: https://futurelearn.com/info/courses/supply-chain-innovation/0/steps/19205
    type: academic
    accessed: 2026-11-09
  - id: s2
    title: "SAP History"
    publisher: SAP SE
    url: https://www.sap.com/about/company/history.html
    type: primary
    accessed: 2026-11-09
  - id: s3
    title: "Investment in Enterprise Resource Planning: Business Impact and Productivity Measures"
    publisher: Journal of Management Information Systems (via Georgia Tech Scheller College of Business)
    url: https://www.scheller.gatech.edu/directory/research/information-technology-management/wu/pdf/hitt_wu_zhou_jmis_2002.pdf
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s4
    title: "Embedding the Enterprise System into the Enterprise: A Model of Corporate Diffusion"
    publisher: Communications of the Association for Information Systems (via CORE)
    url: https://core.ac.uk/download/301377569.pdf
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s5
    title: "Critical Failure Factors in ERP Implementation: A Systematic Literature Review"
    publisher: Journal of Business and Technology
    url: https://jbt.sljol.info/articles/109
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s6
    title: "Supply Chain: Hershey's Bittersweet Lesson"
    publisher: CIO
    url: https://www.cio.com/article/270245/supply-chain-management-supply-chain-hershey-s-bittersweet-lesson.html
    type: news
    accessed: 2026-11-09
created: 2026-11-09
---

# Enterprise Resource Planning

**Enterprise resource planning (ERP)** is the practice of running a company's core transactions on one packaged, integrated software system, so that sales orders, production, purchasing, inventory, accounting and human resources all read from and write to a shared database. Hitt, Wu and Zhou describe ERP systems as software that supports day-to-day operations and decision-making across functions such as the supply chain, manufacturing, sales, accounting and HR.[^s3] The defining feature is that ERP is a standard package: rather than building custom systems, adopters configure the vendor's software and largely adapt their business processes to it.[^s4]

## Origin

ERP descends from production-planning software. Running **material requirements planning** (MRP) on computers became practical in the 1970s, and by the middle of that decade some systems already linked MRP to accounting and customer orders and generated purchase orders automatically.[^s1] Relational databases then enabled **manufacturing resource planning** (MRP II), which added functions such as quality monitoring and detailed cost reporting, usually processed in batches.[^s1] In the early 1990s the research firm Gartner coined "enterprise resource planning" for integrated, cross-functional packaged software that went beyond the factory.[^s1]

SAP, founded on 1 April 1972 by five former IBM employees, illustrates the arc: it began developing its mainframe R/2 system in 1979, and its client-server R/3, released in 1992, launched the product's global success.[^s2] By 1998 ERP license and maintenance revenue had reached $17.2 billion, and a 1999 survey cited by Hitt and colleagues found ERP in more than 60 percent of multinational firms.[^s3] SAP's current generation, S/4HANA, arrived in 2015, four years after its in-memory HANA database reached its first customers.[^s2]

## How it works

An ERP system is organized into modules (for example finance, materials management, production planning, sales and distribution, and human resources) that share master data such as customers, suppliers, items and **bills of materials**, so one transaction updates every function that depends on it. A sales order, for instance, can reserve inventory, trigger MRP for components, schedule production and post receivables without re-keying.[^s3][^s4] Lorenzo, Kawalek and Wood-Harper identify three implementation activities: redesigning business processes, configuring the software by setting parameters, and tailoring it with custom code; tailoring is the costliest and riskiest, so firms tend to favour process adaptation and configuration.[^s4] Their case studies found that ERP diffuses through an organization iteratively and cumulatively, with continuing improvement and fine-tuning after go-live.[^s4]

## Evidence and critiques

The best-known large-sample study is Hitt, Wu and Zhou (2002), which matched SAP America's R/3 license records for 1986–1998 to Compustat data covering 24,037 firm-years, about 350 of them adopters.[^s3] Adopters were 2.3 to 4.2 percent more productive depending on specification, outperformed on measures such as sales per employee, profit margin, return on assets and inventory turnover, and enjoyed a Tobin's q roughly 13 percent higher.[^s3] But productivity rose during implementation and dipped afterwards, and the authors caution that long-run effects needed more post-implementation data and that their adoption data covered only one vendor.[^s3]

Implementation risk is the main critique. A 2023 systematic review of 55 studies published between 2000 and 2022 found 35 failure factors and ranked lack of top-management support, inadequate training, mismatch between the system and business strategy, weak project management and user unwillingness as the top five.[^s5] The strategy-mismatch point echoes a wider concern that standard packages push firms toward the vendor's "best practice" processes, eroding processes that may be a source of differentiation.[^s4][^s5]

## In practice

Hershey Foods is the classic cautionary case. Its combined SAP R/3, Siebel CRM and Manugistics supply-chain project cost $112 million, and when the new order-taking and distribution system went live as Halloween orders peaked, the company could not deliver about $100 million of Kisses and Jolly Ranchers in 1999.[^s6] After the problems were disclosed on a September 1999 call, Hershey's shares fell more than 8 percent that day; CIO, writing in 2002, judged poor timing the main error and called such disruptions fairly typical of enterprise software rollouts.[^s6]

## Connections

ERP is a branch of **production planning and control** that broadened into general **information systems** for the whole enterprise.[^s1] It was **influenced by** material requirements planning and **preceded by** MRP II, whose logic it still embeds, and it **depends on** accurate bills of materials and master data.[^s1][^s3] It overlaps with **inventory management** and is often deployed alongside **customer relationship management** software, as at Hershey.[^s6] Because adopters reshape processes around the package, ERP projects are closely tied to **business process reengineering**.[^s4] **SAP** and the **Hershey implementation** exemplify, respectively, the vendor history and the risks.[^s2][^s6]

## Sources

[^s1]: University of Twente, "Introduction to ERP systems", *Supply Chain Innovation* (FutureLearn course). https://futurelearn.com/info/courses/supply-chain-innovation/0/steps/19205 (accessed 2026-11-09)
[^s2]: SAP SE, "SAP History". https://www.sap.com/about/company/history.html (accessed 2026-11-09)
[^s3]: Lorin M. Hitt, D. J. Wu and Xiaoge Zhou, "Investment in Enterprise Resource Planning: Business Impact and Productivity Measures", *Journal of Management Information Systems*, 2002. https://www.scheller.gatech.edu/directory/research/information-technology-management/wu/pdf/hitt_wu_zhou_jmis_2002.pdf (accessed 2026-11-09)
[^s4]: Oswaldo Lorenzo, Peter Kawalek and Trevor Wood-Harper, "Embedding the Enterprise System into the Enterprise: A Model of Corporate Diffusion", *Communications of the Association for Information Systems* 15, article 34, 2005. https://core.ac.uk/download/301377569.pdf (accessed 2026-11-09)
[^s5]: D. P. P. K. Rajapakse and S. C. Thushara, "Critical Failure Factors in ERP Implementation: A Systematic Literature Review", *Journal of Business and Technology* 7(1): 65–90, 2023. https://jbt.sljol.info/articles/109 (accessed 2026-11-09)
[^s6]: "Supply Chain: Hershey's Bittersweet Lesson", CIO, 15 November 2002. https://www.cio.com/article/270245/supply-chain-management-supply-chain-hershey-s-bittersweet-lesson.html (accessed 2026-11-09)
