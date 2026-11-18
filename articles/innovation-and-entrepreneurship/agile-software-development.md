---
id: kt:agile-software-development
type: Practice
title: "Agile Software Development: Iterative Delivery and the Agile Manifesto"
aliases: [agile development, agile methods, agile methodology, agile]
domain: innovation-and-entrepreneurship
summary: >-
  A family of iterative, team-based approaches to building software (Scrum, Extreme Programming,
  Kanban and others), united since 2001 by the Agile Manifesto's four values and twelve principles,
  that deliver working increments in short cycles and adapt to changing requirements instead of
  following a fixed up-front plan.
broader: [kt:innovation-management, kt:new-product-development]
related: [kt:kanban, kt:lean-startup, kt:design-thinking, kt:high-performance-teams]
relations:
  - {predicate: introducedIn, object: kt:manifesto-for-agile-software-development}
  - {predicate: influencedBy, object: kt:the-new-new-product-development-game-1986}
  - {predicate: influencedBy, object: kt:pdca-cycle}
  - {predicate: influencedBy, object: kt:toyota-production-system}
  - {predicate: hasPart, object: kt:scrum}
  - {predicate: contrastsWith, object: kt:stage-gate-process}
sources:
  - id: s1
    title: "Manifesto for Agile Software Development"
    publisher: Agile Manifesto authors (agilemanifesto.org), 2001
    url: https://agilemanifesto.org/
    type: primary
    accessed: 2026-11-18
  - id: s2
    title: "Principles behind the Agile Manifesto"
    publisher: Agile Manifesto authors (agilemanifesto.org), 2001
    url: https://agilemanifesto.org/principles
    type: primary
    accessed: 2026-11-18
  - id: s3
    title: "The Secret History of Agile Innovation"
    publisher: Harvard Business Review, April 2016 (Darrell K. Rigby, Jeff Sutherland, Hirotaka Takeuchi; republished by Bain & Company)
    url: https://www.bain.com/insights/the-secret-history-of-agile-innovation-hbr/
    type: practitioner-journal
    accessed: 2026-11-18
  - id: s4
    title: "Embracing Agile"
    publisher: Harvard Business Review, May 2016 (Darrell K. Rigby, Jeff Sutherland, Hirotaka Takeuchi; republished by Bain & Company)
    url: https://www.bain.com/insights/embracing-agile-hbr/
    type: practitioner-journal
    accessed: 2026-11-18
  - id: s5
    title: "Empirical studies of agile software development: A systematic review"
    publisher: Information and Software Technology 50(9-10):833-859, 2008 (Tore Dybå, Torgeir Dingsøyr; NTNU author copy)
    url: https://ntnu.no/wiki/download/attachments/78978214/TorgeirDings%C3%B8yr_EmpiricalStudiesOfAgileSoftwareDevelopment.pdf?api=v2
    type: peer-reviewed
    accessed: 2026-11-18
  - id: s6
    title: "A decade of agile methodologies: Towards explaining agile software development"
    publisher: Journal of Systems and Software 85(6):1213-1221, 2012 (Dingsøyr, Nerur, Balijepally, Moe; SINTEF record)
    url: https://www.sintef.no/en/publications/publication/919701
    type: peer-reviewed
    accessed: 2026-11-18
created: 2026-11-18
---

# Agile Software Development

Agile software development is an umbrella term for iterative, team-based methods of building software, among them Scrum, Extreme Programming (XP), Crystal, Adaptive Software Development, Feature-Driven Development and DSDM, which were grouped under the "agile" label in 2001.[^s3] What unites them is the Manifesto for Agile Software Development, which states four value preferences: individuals and interactions over processes and tools, working software over comprehensive documentation, customer collaboration over contract negotiation, and responding to change over following a plan.[^s1] The manifesto stresses that the items on the right still matter; agile teams simply weight the items on the left more heavily.[^s1]

## Origin

The manifesto was written by 17 practitioners, including Kent Beck, Martin Fowler, Ken Schwaber and Jeff Sutherland, who met at Snowbird, Utah, in 2001 to compare their "lightweight" methods; later that year they founded the nonprofit Agile Alliance.[^s1][^s3] Its intellectual roots are older. Rigby, Sutherland and Takeuchi trace them to Walter Shewhart's plan-do-study-act cycles at Bell Labs in the 1930s, to W. Edwards Deming's work in postwar Japan and to the Toyota Production System, the source of lean thinking.[^s3] A direct ancestor is Takeuchi and Nonaka's 1986 Harvard Business Review article "The New New Product Development Game", which contrasted the overlapping "rugby" approach of firms such as Honda, Canon and Fuji-Xerox with sequential "relay race" handoffs between functions.[^s3] Sutherland borrowed that rugby image when he built the first Scrum process at Easel Corporation in 1993, and he and Schwaber presented Scrum publicly in 1995.[^s3]

## How it works

The twelve principles behind the manifesto describe the operating model. Teams aim to satisfy customers through early and continuous delivery, ship working software every few weeks to a few months (preferring the shorter end), and treat working software as the main measure of progress.[^s2] Requirements are expected to change, even late in development, and change is framed as a source of competitive advantage for the customer.[^s2] Business people and developers work together daily; teams are built around motivated individuals who are trusted to self-organize, and the principles hold that the best architectures and designs emerge from such teams.[^s2] Teams keep a sustainable pace, pay continuous attention to technical excellence and simplicity ("maximizing the amount of work not done"), and reflect at regular intervals to adjust how they work.[^s2] In practice, methods differ in mechanics: Scrum uses fixed-length sprints and defined roles, XP emphasizes engineering practices such as pair programming, and Kanban-style methods limit work in progress rather than timeboxing it; lean and Kanban approaches were later accepted into the agile family.[^s3]

## Evidence and critiques

The research base has grown but remains uneven. Dybå and Dingsøyr's systematic review screened 1,996 citations and included 36 empirical studies published up to 2005.[^s5] Those studies reported benefits in customer collaboration, defect handling and developer job satisfaction, but also found agile hard to introduce in large, complex organizations, the on-site customer role hard to sustain, pair programming sometimes tiring, and too little attention paid to architecture and design.[^s5] The authors rated the strength of evidence low: most studies lacked comparison groups, about three quarters examined XP rather than Scrum or lean, and many involved students or small projects.[^s5] A 2012 review of the field's first decade by Dingsøyr and colleagues mapped its rapid growth in publications and citations and argued that agile research still needed a stronger theoretical foundation to explain why the methods work.[^s6] Even sympathetic practitioner accounts offer little measured evidence: the opportunities that Rigby, Sutherland and Takeuchi sketch for agile outside IT, such as more successful product launches, are posed as hypothetical questions rather than reported results.[^s4]

## In practice

Agile began in IT but has spread to other functions. In "Embracing Agile" (2016), Rigby, Sutherland and Takeuchi describe self-managed, multidisciplinary, customer-focused teams at National Public Radio for new programming, at John Deere for new machines, at Saab for fighter-jet development, and in marketing at Intronis and HR at C.H. Robinson.[^s4] They frame agile as an alternative to command-and-control management and a way to grow a new generation of general managers.[^s4]

## Connections

Agile is a branch of **innovation management** and of new-product development, and it was codified in the Agile Manifesto.[^s1][^s3] It is influenced by the **PDCA cycle**, the **Toyota Production System** and Takeuchi and Nonaka's 1986 rugby model, and it includes Scrum, one of the methods its founders brought to Snowbird.[^s3] It shares lean roots with **Kanban**, which was later accepted as an agile approach, and its short build-and-learn cycles parallel those of **lean startup** and **design thinking**.[^s3][^s2] Its reliance on small, self-organizing teams links it to **high-performance teams**, while its incremental, change-tolerant planning contrasts with the gated, sequential **Stage-Gate process**.[^s2][^s5]

## Sources
[^s1]: Kent Beck et al., "Manifesto for Agile Software Development", 2001. https://agilemanifesto.org/ (accessed 2026-11-18)
[^s2]: Kent Beck et al., "Principles behind the Agile Manifesto", 2001. https://agilemanifesto.org/principles (accessed 2026-11-18)
[^s3]: Darrell K. Rigby, Jeff Sutherland and Hirotaka Takeuchi, "The Secret History of Agile Innovation", Harvard Business Review, 2016. https://www.bain.com/insights/the-secret-history-of-agile-innovation-hbr/ (accessed 2026-11-18)
[^s4]: Darrell K. Rigby, Jeff Sutherland and Hirotaka Takeuchi, "Embracing Agile", Harvard Business Review, May 2016. https://www.bain.com/insights/embracing-agile-hbr/ (accessed 2026-11-18)
[^s5]: Tore Dybå and Torgeir Dingsøyr, "Empirical studies of agile software development: A systematic review", Information and Software Technology 50(9-10), 2008. https://ntnu.no/wiki/download/attachments/78978214/TorgeirDings%C3%B8yr_EmpiricalStudiesOfAgileSoftwareDevelopment.pdf?api=v2 (accessed 2026-11-18)
[^s6]: Torgeir Dingsøyr, Sridhar Nerur, VenuGopal Balijepally and Nils Brede Moe, "A decade of agile methodologies: Towards explaining agile software development", Journal of Systems and Software 85(6), 2012. https://www.sintef.no/en/publications/publication/919701 (accessed 2026-11-18)
