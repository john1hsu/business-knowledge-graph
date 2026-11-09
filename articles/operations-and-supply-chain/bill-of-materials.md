---
id: kt:bill-of-materials
type: Concept
title: Bill of Materials
aliases: [BOM, bill of material, product structure, parts list]
domain: operations-and-supply-chain
summary: >-
  The structured list of every component, subassembly and raw material, with quantities, needed to make one
  unit of a product, organised as parent–component links; it is the master data that production planning,
  costing and material requirements planning are built on.
broader: [kt:production-planning-and-control, kt:inventory-management]
related: [kt:material-requirements-planning, kt:master-production-schedule, kt:enterprise-resource-planning, kt:product-lifecycle-management]
relations:
  - {predicate: appliesTo, object: kt:mass-customization}
  - {predicate: exemplifiedBy, object: kt:cisco-systems}
sources:
  - id: s1
    title: "PROC BOM: Overview (SAS/OR 9.22 User's Guide: Bill of Material Processing)"
    publisher: SAS Institute
    url: https://support.sas.com/documentation/cdl/en/orbomug/63350/HTML/default/orbomug_bom_sect001.htm
    type: organization
    accessed: 2026-11-09
  - id: s2
    title: "Manufacturing bill of materials (MBOM)"
    publisher: Siemens
    url: https://www.siemens.com/en-us/technology/manufacturing-bill-of-materials-mbom/
    type: organization
    accessed: 2026-11-09
  - id: s3
    title: "A decision support tool for planning bills-of-material"
    publisher: Production Planning & Control (via University of Galway Research Repository)
    url: https://researchrepository.universityofgalway.ie/entities/publication/0636e58e-36c7-4886-a748-c06dc696a622
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s4
    title: "Impact of mass customization on bill of materials structure and master production schedule"
    publisher: Journal Européen des Systèmes Automatisés (IIETA)
    url: https://www.iieta.org/journals/jesa/paper/10.3166/JESA.49.55-91
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s5
    title: "Bill of Material and Item Standard Routing Data Accuracy – FPI (Program Statement 8340.11)"
    publisher: U.S. Department of Justice, Federal Bureau of Prisons
    url: https://www2.fed.bop.gov/policy/progstat/8340_011.pdf
    type: government
    accessed: 2026-11-09
  - id: s6
    title: "Product-level bill of material development process: managing complexity"
    publisher: MIT Sloan School of Management / Leaders for Manufacturing (DSpace@MIT)
    url: https://dspace.mit.edu/handle/1721.1/49784
    type: academic
    accessed: 2026-11-09
created: 2026-11-09
---

# Bill of Materials

A **bill of materials (BOM)** lists the items, ingredients or materials required to produce a run of a given item; process industries often call the same record a formula, recipe or ingredients list.[^s1] Rather than being a flat list, a BOM is stored as a set of *product structure* records, each linking one component to its immediate parent and carrying data such as the quantity required, a scrap factor, a lead-time offset and engineering effectivity (the dates or serial numbers from which a design change applies).[^s1] Because every downstream calculation of what to buy, make and cost starts from these links, the BOM is the core master data of a manufacturing firm.

## How it works

The simplest view is the **single-level BOM**, which shows only the components a parent uses directly.[^s1] Chaining single-level records produces the **indented (multilevel) BOM**: the finished product sits at level 0, each component appears one level below its parent, and a part used in several assemblies shows up under each of them, giving the familiar family-tree shape.[^s1] A **summarized BOM** collapses the tree so each item appears once with its total quantity, which is useful for purchasing and costing a production plan.[^s1]

Firms also keep different BOMs for different purposes. The **engineering BOM (EBOM)** reflects how parts relate to the product's functional design, while the **manufacturing BOM (MBOM)** is derived from it and reflects how parts are actually assembled into a finished product; the MBOM defines *what* to make, and a separate bill of process defines *how*.[^s2] Reconciling the two when designs change is a recurring task in product data management.[^s2]

For product families with many options, listing a separate BOM for every end-item variant becomes impractical. **Planning (modular) BOMs** group options that share components so that forecasting and master scheduling can be done at the option level; Cunningham, Higgins and Browne (1996) proposed a decision-support tool that builds such planning bills from manufacturing BOMs, grouping options only when the shared material is large and valuable enough, and assessing the long-run inventory effect of planning options as common.[^s3] The related idea of a **generic BOM**, which describes a whole family of variants in one model, traces to Hegge and Wortmann's 1991 paper in the *International Journal of Production Economics*.[^s4]

## Evidence and critiques

Mass customization strains the classic BOM. Chatras, Giard and Sali (2016) argue that when end products and components vary enormously and alternative components carry commercial and technical constraints, creating and maintaining a full BOM for each end product becomes very complex; customers can no longer specify products by component, and sales cannot forecast at end-item or component level.[^s4] Some carmakers responded by describing products in terms of market features and converting them to a physical BOM through logical rules, but a physical BOM is still needed for the master production schedule and the shop floor.[^s4]

The other persistent problem is accuracy. Since material plans, purchase orders and standard costs are all computed from the BOM, an error propagates silently into shortages, excess stock and wrong costs. The U.S. Federal Bureau of Prisons' Federal Prison Industries, for example, requires its factories' BOMs to be at least 98 percent accurate (policy dated July 2015), audits a random sample of 25 scheduled items each month, and counts a BOM as accurate only if part numbers, required raw materials and quantities all match the drawings or specifications and materials are assigned to the right operation; sites below the threshold must file an improvement plan.[^s5] The policy ties this discipline directly to keeping production schedules viable within its MRP system.[^s5]

## In practice

BOM structure is as much an organisational problem as a technical one. A 2009 MIT Leaders for Manufacturing thesis at Cisco found that its process for developing product-level BOMs produced inconsistent structures across more than 50 business units, which led to product launch delays, higher support costs and lower customer satisfaction.[^s6] The author studied four business units of differing complexity and proposed a standardised, criteria-based, workflow-driven BOM development method as a base for continuous improvement.[^s6]

## Connections

The BOM is a building block of **production planning and control** and **inventory management**.[^s1] **Material requirements planning** depends on it, exploding the BOM to turn **master production schedule** quantities into component requirements, which is why accuracy standards are framed in MRP terms.[^s4][^s5] Within **enterprise resource planning** and **product lifecycle management** software, the EBOM-to-MBOM hand-off links design to manufacturing.[^s2] Planning and generic BOMs are the field's answer to **mass customization**, and **Cisco Systems** illustrates the cost of letting BOM structures drift.[^s3][^s4][^s6]

## Sources

[^s1]: SAS Institute, "PROC BOM: Overview", *SAS/OR 9.22 User's Guide: Bill of Material Processing*. https://support.sas.com/documentation/cdl/en/orbomug/63350/HTML/default/orbomug_bom_sect001.htm (accessed 2026-11-09)
[^s2]: Siemens, "Manufacturing bill of materials (MBOM)". https://www.siemens.com/en-us/technology/manufacturing-bill-of-materials-mbom/ (accessed 2026-11-09)
[^s3]: M. Cunningham, P. Higgins and J. Browne, "A decision support tool for planning bills-of-material", *Production Planning & Control* 7(3): 312–328, 1996. https://researchrepository.universityofgalway.ie/entities/publication/0636e58e-36c7-4886-a748-c06dc696a622 (accessed 2026-11-09)
[^s4]: Clément Chatras, Vincent Giard and Mounir Sali, "Impact of mass customization on bill of materials structure and master production schedule", *Journal Européen des Systèmes Automatisés* 49(1), 2016. doi:10.3166/JESA.49.51-90. https://www.iieta.org/journals/jesa/paper/10.3166/JESA.49.55-91 (accessed 2026-11-09)
[^s5]: U.S. Department of Justice, Federal Bureau of Prisons, "Bill of Material and Item Standard Routing Data Accuracy – FPI", Program Statement 8340.11, 9 July 2015. https://www2.fed.bop.gov/policy/progstat/8340_011.pdf (accessed 2026-11-09)
[^s6]: Ryan John Lester, "Product-level bill of material development process: managing complexity", MBA/SM thesis, Massachusetts Institute of Technology, 2009. https://dspace.mit.edu/handle/1721.1/49784 (accessed 2026-11-09)
