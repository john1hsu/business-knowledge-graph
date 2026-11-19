---
id: kt:production-planning-and-control
type: Practice
title: "Production Planning and Control: From Aggregate Plans to Shop-Floor Dispatching"
aliases: [PPC, production planning, production control, manufacturing planning and control]
domain: operations-and-supply-chain
summary: >-
  The managerial function that decides what a plant will make, in what quantities, when and on
  which resources (planning), and then releases, monitors and corrects the work on the shop floor
  so that output matches the plan (control).
broader: [kt:operations-management]
related: [kt:material-requirements-planning, kt:enterprise-resource-planning, kt:inventory-management, kt:just-in-time, kt:theory-of-constraints]
relations:
  - {predicate: hasPart, object: kt:master-production-schedule}
  - {predicate: hasPart, object: kt:aggregate-planning}
  - {predicate: influencedBy, object: kt:scientific-management}
  - {predicate: influencedBy, object: kt:gantt-chart}
  - {predicate: influenced, object: kt:hierarchical-production-planning}
  - {predicate: alternativeTo, object: kt:kanban}
sources:
  - id: s1
    title: "Production management"
    publisher: Encyclopaedia Britannica (Britannica Money)
    url: https://www.britannica.com/money/production-management
    type: encyclopedia
    accessed: 2026-11-19
  - id: s2
    title: "Gantt charts: A centenary appreciation"
    publisher: European Journal of Operational Research (University of Glasgow Enlighten repository)
    url: https://eprints.gla.ac.uk/39064
    type: peer-reviewed
    accessed: 2026-11-19
  - id: s3
    title: "Hierarchical Production Planning Systems (Technical Report No. 135)"
    publisher: MIT Operations Research Center, via Defense Technical Information Center
    url: https://apps.dtic.mil/sti/pdfs/ADA045016.pdf
    type: academic
    accessed: 2026-11-19
  - id: s4
    title: "Hierarchical integration of production planning and scheduling (Working Paper 656-73)"
    publisher: MIT Sloan School of Management, via EconPapers (RePEc)
    url: https://econpapers.repec.org/RePEc:mit:sloanp:1868
    type: primary
    accessed: 2026-11-19
  - id: s5
    title: "Material Requirements Planning (MIT 2.854 lecture notes, Fall 2010)"
    publisher: MIT OpenCourseWare / DSpace@MIT
    url: https://dspace.mit.edu/bitstream/handle/1721.1/109525/2-854-fall-2010/contents/lecture-notes/MIT2_854F10_mrp.pdf
    type: academic
    accessed: 2026-11-19
created: 2026-11-19
---

# Production Planning and Control

**Production planning and control (PPC)** is the part of operations management that turns demand into a workable factory programme and then keeps execution on that programme. Britannica's account of production management describes the overall task as planning and controlling industrial processes so they run smoothly at the required level of output, and singles out control as the manager's central problem: holding production to schedule while meeting cost and quality targets.[^s1] Planning answers *what, how much, when and where*; control answers *is it happening, and if not, what do we do about it*.

## Origin

PPC grew out of Frederick Taylor's planning office in the scientific management movement, which pulled the scheduling of work away from foremen and into a central department. J. M. Wilson's centenary review of the Gantt chart argues that Henry Gantt's graphical charts, presented in a 1903 paper on production planning published alongside Taylor's *Shop Management*, were what made that system workable: they let planners lay out the load on each worker and machine, department by department and across the whole plant.[^s2] The bar chart now associated with project software began, in other words, as a production-control tool.[^s2]

## How it works

Modern treatments arrange PPC as a hierarchy in which each level covers a longer horizon and a larger slice of the system with a more aggregated model, and passes targets down to the level below.[^s5]

- **Long range (roughly six months to five years):** forecasting, resource planning and aggregate planning set rough production and staffing levels.[^s5]
- **Intermediate range:** demand management, the master production schedule, rough-cut capacity planning and capacity requirements planning translate the aggregate plan into end-item quantities and check them against capacity; material requirements planning sits here, exploding the master schedule into component orders.[^s5]
- **Short range:** daily production targets, job dispatching, input-output control and shop-floor control release and track individual jobs.[^s5]

The control side is a feedback loop. Britannica frames it as observation, analysis, corrective action and evaluation, applied to processes, inventory, inspection and cost; corrective actions include expediting and issuing new production or purchase orders.[^s1] Control serves two purposes: keeping operations on plan, and continually evaluating the plan itself so that cost, quality, delivery or flexibility improve.[^s1]

## Hierarchical production planning

The most influential formal model of this structure came from Arnoldo Hax and Harlan Meal at MIT Sloan, whose 1973 working paper proposed integrating planning and scheduling hierarchically rather than solving one giant model.[^s4] A 1977 MIT Operations Research Center report by Hax and Jonathan Golovin elaborated the design for batch manufacturing in three tiers: a linear program allocates capacity among product *types* over a rolling year; type quantities are split among product *families* that share a setup; and family run quantities are divided among *items* so that their run-out times coincide.[^s3] Only the first period of each plan is executed before the models are re-run on fresh data.[^s3]

## Evidence and critiques

The case for hierarchy is practical. Hax and Golovin note that forecasting and maintaining data for thousands of items can cost more than the planning system itself, that aggregate demand is easier to forecast, and that managers can understand and test plans at the product-group level where budgets are set.[^s3] In their tire-manufacturing simulations, the base case of the hierarchical system came in about 14 percent above the best mixed-integer programming solution at a fraction of the computing cost, though performance degraded when setup costs were extremely high.[^s3]

The critiques concern the seams between levels. Gershwin's MIT notes warn that aggregate models can be inaccurate, that shop-floor events can make higher-level targets obsolete, and that frequent re-scheduling breeds instability.[^s5] Because MRP-style planning assumes unlimited capacity and deterministic lead times, it can generate infeasible schedules and "nervousness", where small deviations trigger large schedule changes; freezing the near-term schedule calms this at a cost.[^s5] Those weaknesses are why pull systems and constraint-based scheduling emerged as alternatives.

## Connections

PPC is a core sub-function of **operations management**.[^s1] It **has parts** in **aggregate planning** and the **master production schedule**, with **material requirements planning** as its intermediate-range calculation engine and **enterprise resource planning** as its software home.[^s5] It was **influenced by** **scientific management** and the **Gantt chart**, and it **influenced** **hierarchical production planning** as a formal model.[^s2][^s3][^s4] It is tied to **inventory management**, whose stock decisions it drives, and it stands as a centrally planned **alternative to kanban** and **just-in-time** pull control, while the **theory of constraints** attacks the same infinite-capacity weakness from another angle.[^s1][^s5]

## Sources
[^s1]: William K. Holstein, "Production management", Encyclopaedia Britannica (Britannica Money). https://www.britannica.com/money/production-management (accessed 2026-11-19)
[^s2]: J. M. Wilson, "Gantt charts: A centenary appreciation", *European Journal of Operational Research* 149(2): 430–437, 2003. doi:10.1016/S0377-2217(02)00769-5. https://eprints.gla.ac.uk/39064 (accessed 2026-11-19)
[^s3]: Arnoldo C. Hax and Jonathan J. Golovin, "Hierarchical Production Planning Systems", Technical Report No. 135, MIT Operations Research Center, August 1977 (ONR contract N00014-75-C-0556). https://apps.dtic.mil/sti/pdfs/ADA045016.pdf (accessed 2026-11-19)
[^s4]: Arnoldo C. Hax and Harlan C. Meal, "Hierarchical integration of production planning and scheduling", Working Paper 656-73, MIT Sloan School of Management, 1973. https://econpapers.repec.org/RePEc:mit:sloanp:1868 (accessed 2026-11-19)
[^s5]: Stanley B. Gershwin, "Material Requirements Planning" lecture notes, MIT 2.854 Introduction to Manufacturing Systems, Fall 2010, MIT OpenCourseWare. https://dspace.mit.edu/bitstream/handle/1721.1/109525/2-854-fall-2010/contents/lecture-notes/MIT2_854F10_mrp.pdf (accessed 2026-11-19)
