---
id: kt:material-requirements-planning
type: Practice
title: Material Requirements Planning
aliases: [MRP, MRP I, materials requirements planning]
domain: operations-and-supply-chain
summary: >-
  A computerized production-planning method that converts a master production schedule into
  time-phased orders for components and raw materials by exploding bills of materials, netting
  out inventory and offsetting by lead times; the archetypal "push" system for dependent demand.
broader: [kt:production-planning-and-control, kt:inventory-management]
related: [kt:kanban, kt:just-in-time, kt:enterprise-resource-planning, kt:theory-of-constraints, kt:economic-order-quantity]
relations:
  - {predicate: introducedIn, object: kt:material-requirements-planning-1975}
  - {predicate: influencedBy, object: kt:scientific-management}
  - {predicate: dependsOn, object: kt:bill-of-materials}
  - {predicate: dependsOn, object: kt:master-production-schedule}
  - {predicate: contrastsWith, object: kt:kanban}
  - {predicate: followedBy, object: kt:manufacturing-resource-planning}
  - {predicate: influenced, object: kt:demand-driven-mrp}
sources:
  - id: s1
    title: "Materials Requirements Planning (MRP)"
    publisher: Institute for Manufacturing, University of Cambridge
    url: https://www.ifm.eng.cam.ac.uk/research/dstools/mrp/
    type: academic
    accessed: 2026-11-09
  - id: s2
    title: "Material Requirements Planning and Manufacturing Resources Planning (lecture notes, MIT 2.854)"
    publisher: MIT OpenCourseWare
    url: https://ocw.mit.edu/courses/2-854-introduction-to-manufacturing-systems-fall-2016/4eec617bb52d64f4ea1bed6d9905bc00_MIT2_854F16_MatrialRequire.pdf
    type: academic
    accessed: 2026-11-09
  - id: s3
    title: "The origin of materials requirements planning in Frederick W. Taylor's planning office"
    publisher: International Journal of Production Research (via CORE)
    url: https://core.ac.uk/download/296177114.pdf
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s4
    title: "Re-Examining the Performance of MRP and Kanban Material Control Strategies for Multi-Product Flexible Manufacturing Systems"
    publisher: International Journal of Flexible Manufacturing Systems (Springer)
    url: https://link.springer.com/article/10.1023/B:FLEX.0000044837.86194.19
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s5
    title: "Demand Driven Material Requirements Planning (DDMRP): A systematic review and classification"
    publisher: Journal of Industrial Engineering and Management
    url: https://www.jiem.org/index.php/jiem/article/view/3331
    type: peer-reviewed
    accessed: 2026-11-09
  - id: s6
    title: "Interpreting and applying demand driven MRP: a case study"
    publisher: Nottingham Trent University (DBA thesis)
    url: https://irep.ntu.ac.uk/id/eprint/27704/
    type: academic
    accessed: 2026-11-09
created: 2026-11-09
---

# Material Requirements Planning

Material requirements planning (MRP) is a planning method for assembled products in which each stage of manufacturing tells its supplier, whether an upstream process or an outside vendor, which parts it needs and when.[^s1] It was designed for *dependent demand*: once the quantity of finished goods is fixed, the quantity of every component follows by calculation, and cheap computing made those calculations practical at scale.[^s1] The University of Cambridge's Institute for Manufacturing describes MRP, together with its successor MRP II, as probably the most widely used planning and scheduling tool in the world.[^s1]

## Origin

MRP systems spread in the 1970s, and Joseph Orlicky's 1975 book *Material Requirements Planning* became the field's reference text; Orlicky himself counted only 26 items, mostly articles and trade-press pieces, in the MRP literature at the time.[^s3] IBM's COPICS manuals of the same era documented the logic in far more detail than anything earlier.[^s3] A 2016 historical study in the *International Journal of Production Research* argues that the core logic is older: production planning offices of the 1940s, descended from Frederick Taylor's planning office, already exploded bills of materials using punched-card accounting machines, and limited data-handling capacity, not missing ideas, was the main barrier before the 1960s.[^s3] Today's enterprise resource planning (ERP) systems descend from those 1970s MRP systems.[^s3]

## How it works

MRP separates *independent demand* (customer orders and forecasts, captured in the master production schedule) from *dependent demand* for components and raw materials.[^s2] Its inputs are the master production schedule, an item master holding each part's bill of materials, lot-sizing rule and planned lead time, and current inventory status.[^s2] The calculation then runs level by level down the product structure:[^s1][^s2]

- **Explosion**: the bill of materials converts end-item quantities into gross requirements for each component.[^s1][^s2]
- **Netting**: on-hand and scheduled inventory is subtracted to give net requirements.[^s1][^s2]
- **Lot sizing**: net requirements are grouped by a rule such as lot-for-lot, fixed order period or fixed order quantity, which may use an economic order quantity.[^s2]
- **Offsetting**: orders are released one planned lead time before they are needed, and those planned releases become the gross requirements of the next level down.[^s1][^s2]

The outputs are planned order releases, change notices and exception reports.[^s2] Uncertainty is handled with safety stock for quantity risk and safety lead time for timing risk.[^s2]

## Evidence and critiques

MRP rests on three assumptions: capacity is sufficient (hence the label "infinite capacity scheduling"), lead times can be known in advance, and the due date is a valid anchor for back-scheduling.[^s1] Each is a common failure point. Deterministic plans meet a random shop floor, schedules can prove infeasible, planners pad lead times to absorb variability, and "nervousness" sets in, where small deviations trigger large schedule changes, extra setups and confused workers.[^s2] MRP II answered the capacity problem by wrapping MRP in demand management, rough-cut and detailed capacity planning, and shop-floor control within a planning hierarchy.[^s2]

The push-versus-pull debate is not one-sided. A 2004 simulation study of multi-product manufacturing found that where advance demand information was available, MRP-type push strategies achieved better inventory and service levels than kanban, which showed significant inefficiencies, and that safety lead time beat safety stock at low and medium loads.[^s4] More recently, demand-driven MRP (DDMRP), which appeared in 2011, places strategic inventory buffers inside the MRP logic to bridge push and pull; a 2021 systematic review judged the approach promising but not yet mature, with parameter setting and robustness still needing research.[^s5]

## In practice

A 2015 doctoral case study at a printing-ink manufacturer illustrates both the limits and the fixes. The firm's ERP-based MRP planning produced late deliveries, stock that did not match demand and general instability, symptoms the author linked to known MRP limitations.[^s6] Simulating DDMRP against the company's historical ERP decisions cut high- and low-inventory alerts by about 45% and stock-outs by about 95% over the study period, though the author cautioned that a single case cannot attribute all the gain to DDMRP.[^s6]

## Connections

MRP sits under **production planning and control** and **inventory management**, and it **depends on** two data structures, the **bill of materials** and the **master production schedule**.[^s1][^s2] It was codified in Joseph Orlicky's 1975 book **Material Requirements Planning**, has roots that a historical study traces to Taylor's **scientific management** planning office, was **followed by manufacturing resource planning (MRP II)**, and evolved into **enterprise resource planning**.[^s2][^s3] It **contrasts with kanban** and **just-in-time** pull control, a contrast the simulation evidence shows depends on demand visibility.[^s2][^s4] Its lot-sizing step can use the **economic order quantity**, and its capacity blind spot is what **Theory of Constraints** methods and **demand-driven MRP**, which it **influenced**, try to repair.[^s2][^s5][^s6]

## Sources
[^s1]: Institute for Manufacturing, University of Cambridge, "Materials Requirements Planning (MRP)", Decision Support Tools. https://www.ifm.eng.cam.ac.uk/research/dstools/mrp/ (accessed 2026-11-09)
[^s2]: Stanley B. Gershwin, "Material Requirements Planning" lecture notes (drawing on Hopp and Spearman, *Factory Physics*), MIT 2.854 Introduction to Manufacturing Systems, MIT OpenCourseWare, Fall 2016. https://ocw.mit.edu/courses/2-854-introduction-to-manufacturing-systems-fall-2016/4eec617bb52d64f4ea1bed6d9905bc00_MIT2_854F16_MatrialRequire.pdf (accessed 2026-11-09)
[^s3]: J. M. Wilson, "The origin of materials requirements planning in Frederick W. Taylor's planning office", *International Journal of Production Research*, 2016. doi:10.1080/00207543.2015.1092616. https://core.ac.uk/download/296177114.pdf (accessed 2026-11-09)
[^s4]: Ananth Krishnamurthy, Rajan Suri and Mary Vernon, "Re-Examining the Performance of MRP and Kanban Material Control Strategies for Multi-Product Flexible Manufacturing Systems", *International Journal of Flexible Manufacturing Systems* 16(2): 123–150, 2004. https://link.springer.com/article/10.1023/B:FLEX.0000044837.86194.19 (accessed 2026-11-09)
[^s5]: Ahlam Azzamouri, Pierre Baptiste, Guillaume Dessevre and Robert Pellerin, "Demand Driven Material Requirements Planning (DDMRP): A systematic review and classification", *Journal of Industrial Engineering and Management* 14(3): 439–456, 2021. doi:10.3926/jiem.3331. https://www.jiem.org/index.php/jiem/article/view/3331 (accessed 2026-11-09)
[^s6]: M. Ihme, "Interpreting and applying demand driven MRP: a case study", DBA thesis, Nottingham Trent University, 2015. https://irep.ntu.ac.uk/id/eprint/27704/ (accessed 2026-11-09)
