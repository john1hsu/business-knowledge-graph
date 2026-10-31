---
id: kt:kanban
type: Practice
title: Kanban
aliases: [kanban system, kanban card system, signboard scheduling]
domain: operations-and-supply-chain
summary: >-
  A visual pull-scheduling practice, developed at Toyota, in which cards or signals attached to
  containers of parts authorize a preceding process to produce or deliver only what a downstream
  process has actually consumed, capping work-in-process inventory.
broader: [kt:just-in-time, kt:toyota-production-system]
related: [kt:lean-manufacturing, kt:littles-law, kt:ford-model-t, kt:agile-software-development]
relations:
  - {predicate: createdBy, object: kt:taiichi-ohno}
  - {predicate: exemplifiedBy, object: kt:toyota-motor-corporation}
  - {predicate: contrastsWith, object: kt:material-requirements-planning}
  - {predicate: influenced, object: kt:kanban-method}
sources:
  - id: s1
    title: "Kanban: Toyota Production System guide"
    publisher: Toyota UK Magazine (Toyota GB)
    url: https://mag.toyota.co.uk/kanban-toyota-production-system/
    type: primary
    accessed: 2026-10-31
  - id: s2
    title: "Toyota Production System (brochure)"
    publisher: Toyota Material Handling Europe (hosted by KTH Royal Institute of Technology)
    url: https://www.kth.se/social/upload/511bb0b1f276543fb38d79b8/Toyota%2520Production%2520System%2520Brochure.pdf
    type: primary
    accessed: 2026-10-31
  - id: s3
    title: "An overview of design and operational issues of kanban systems"
    publisher: International Journal of Production Research (via Bilkent University repository)
    url: https://repository.bilkent.edu.tr/bitstream/11693/25185/1/Overview%20of%20design%20and%20operational%20issues%20of%20kanban%20systems.pdf
    type: peer-reviewed
    accessed: 2026-10-31
  - id: s4
    title: "Variations of the kanban system: Literature review and classification"
    publisher: International Journal of Production Economics (via IDEAS/RePEc)
    url: https://ideas.repec.org/a/eee/proeco/v125y2010i1p13-21.html
    type: peer-reviewed
    accessed: 2026-10-31
  - id: s5
    title: "Celebrating the enigma: the continuing puzzle of the Toyota Production System"
    publisher: International Journal of Production Research (record via Loughborough University Library)
    url: https://vufind.lboro.ac.uk/PrimoRecord/cdi_proquest_miscellaneous_30051933
    type: peer-reviewed
    accessed: 2026-10-31
  - id: s6
    title: "Agile development: How the Kanban method changes software engineering"
    publisher: CIO
    url: https://www.cio.com/article/286826/agile-development-how-the-kanban-method-changes-software-engineering.html
    type: news
    accessed: 2026-10-31
created: 2026-10-31
---

# Kanban

Kanban (Japanese for "signboard" or "card") is the information system Toyota built to run just-in-time production: it passes signals between processes and orders replacement parts automatically as parts are used up.[^s1] Every item, or box of items, moving through production carries its own kanban; when the item is consumed or moved, the card is detached and returned to the preceding process as an order for more.[^s1] In operations research terms, the cards authorize the production or transport of a fixed quantity of material, so the system pulls parts through the line and caps work-in-process inventory.[^s3]

## Origin

Toyota's own account credits Taiichi Ohno, the engineer it calls the true architect of the Toyota Production System (TPS), with developing kanban after the Second World War.[^s2] According to that account, Ohno travelled to the United States to study Ford's mass-production methods but was more impressed by American supermarkets, where customers took only what they needed and shelves were refilled promptly; he treated the supermarket as a model warehouse in which inflows matched outflows.[^s2] The first extensive English-language description of TPS and kanban was a 1977 paper by Sugimori and colleagues in the *International Journal of Production Research*, which the journal marked with a 30th-anniversary special issue in 2007.[^s5]

## How it works

The classic design uses two card types. A withdrawal (transportation) kanban specifies how much the downstream stage may take from upstream, and a production kanban authorizes the upstream stage to make exactly the parts needed to replace what was removed.[^s3] A simpler single-card variant controls only transport with kanbans while a central schedule drives production inside a cell, which researchers describe as a push system with pull elements added.[^s3] Toyota frames the discipline as six rules: never pass defects downstream, withdraw only what is needed, produce only the quantity withdrawn, level production, use kanban to fine-tune output, and keep stabilizing and rationalizing the process.[^s1]

The number of cards sets the inventory ceiling. In the formula commonly attributed to Toyota, the number of kanbans times container size equals average demand times expected lead time, inflated by a safety factor: n × a = D × L × (1 + s).[^s3]

## Evidence and critiques

Kanban performs best under conditions that JIT itself requires: reliable processes, short setup times, low demand variability, constrained product variety, and a level, stable final-assembly schedule.[^s3] Because information travels only with material, demand trends reach distant upstream stages slowly, creating long information lead times when material flow times are large.[^s3] These limits spawned many modifications: a 2010 review classified 32 kanban variations proposed in the literature and found far more theoretical proposals than tested, practical ones.[^s4] Scholars marking the 2007 anniversary still called TPS an enigma, reading the original paper through both its technical elements and its human ones, including job design and worker motivation — a reminder that copying the cards alone does not reproduce the system.[^s5]

## In practice

At Toyota, kanban remains the quick-response mechanism that matches inventory to actual consumption, and boards can display goods in, goods in production and goods out.[^s1] The idea has also crossed into knowledge work. David J. Anderson's work on an internal Microsoft project made in-progress work visible on a virtual board and limited each programmer to one item at a time; the resulting Kanban method for software emphasizes visualizing workflow, limiting work in progress, pulling rather than pushing work, and tracking throughput and cycle time (as described by CIO in 2012).[^s6]

## Connections

Kanban is the shop-floor control mechanism of **just-in-time** production and one of the core tools of the **Toyota Production System**, so both are its broader nodes.[^s2][^s3] It was **created by Taiichi Ohno** and is **exemplified by Toyota Motor Corporation**.[^s2] It **contrasts with material requirements planning**, whose forecast-driven push logic is the opposite of kanban's consumption-driven pull; single-card systems sit between the two.[^s3] Its WIP-capping logic relates to **Little's Law** and to **lean manufacturing**; Ohno's study of Ford links it to the **Ford Model T** era of mass production it reacted against;[^s2] and it **influenced the Kanban method** in **agile software development**.[^s6]

## Sources
[^s1]: Toyota UK Magazine, "Kanban: Toyota Production System guide", published 31 May 2013, updated 26 July 2024. https://mag.toyota.co.uk/kanban-toyota-production-system/ (accessed 2026-10-31)
[^s2]: Toyota Material Handling Europe, *Toyota Production System* (brochure), April 2010. https://www.kth.se/social/upload/511bb0b1f276543fb38d79b8/Toyota%2520Production%2520System%2520Brochure.pdf (accessed 2026-10-31)
[^s3]: M. S. Aktürk and F. Erhun, "An overview of design and operational issues of kanban systems", *International Journal of Production Research* 37(17): 3859–3881, 1999. doi:10.1080/002075499189808. https://repository.bilkent.edu.tr/bitstream/11693/25185/1/Overview%20of%20design%20and%20operational%20issues%20of%20kanban%20systems.pdf (accessed 2026-10-31)
[^s4]: Muris Lage Junior and Moacir Godinho Filho, "Variations of the kanban system: Literature review and classification", *International Journal of Production Economics* 125(1): 13–21, 2010. https://ideas.repec.org/a/eee/proeco/v125y2010i1p13-21.html (accessed 2026-10-31)
[^s5]: "Celebrating the enigma: the continuing puzzle of the Toyota Production System", *International Journal of Production Research* 45(16): 3545–3554, 2007. doi:10.1080/00207540701223386. https://vufind.lboro.ac.uk/PrimoRecord/cdi_proquest_miscellaneous_30051933 (accessed 2026-10-31)
[^s6]: CIO, "Agile development: How the Kanban method changes software engineering", 30 July 2012. https://www.cio.com/article/286826/agile-development-how-the-kanban-method-changes-software-engineering.html (accessed 2026-10-31)
