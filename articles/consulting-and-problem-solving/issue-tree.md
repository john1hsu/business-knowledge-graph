---
id: kt:issue-tree
type: Framework
title: Issue Tree
aliases: [logic tree, question map, issue map, why tree, how tree]
domain: consulting-and-problem-solving
summary: >-
  A hierarchical diagram that decomposes a single key question into progressively smaller
  sub-questions or options, either diagnostic ("why?") or solution-oriented ("how?"), so that a
  complex problem can be analysed piece by piece and work can be planned against each branch.
broader: [kt:structured-problem-solving]
related: [kt:hypothesis-driven-problem-solving, kt:pyramid-principle, kt:root-cause-analysis, kt:marketing-mix]
relations:
  - {predicate: dependsOn, object: kt:mece-principle}
  - {predicate: contrastsWith, object: kt:fault-tree-analysis}
  - {predicate: mitigates, object: kt:confirmation-bias}
  - {predicate: alternativeTo, object: kt:problem-tree-analysis}
sources:
  - id: s1
    title: "How to use maps to solve complex problems"
    publisher: OUPblog (Oxford University Press)
    url: https://blog.oup.com/2020/02/how-to-use-maps-to-solve-complex-problems/
    type: primary
    accessed: 2026-11-09
  - id: s2
    title: "Solving Problems by Exploring the Far End of Possibility"
    publisher: Rice Business Wisdom (Jones Graduate School of Business, Rice University)
    url: https://business.rice.edu/wisdom/peer-reviewed-research/solving-problems-exploring-far-end-possibility
    type: academic
    accessed: 2026-11-09
  - id: s3
    title: "Implementation Insights: Using Issue Trees"
    publisher: UK Government (GOV.UK)
    url: https://assets.publishing.service.gov.uk/media/5a816cd1e5274a2e8ab53eb1/Issue_Trees.pdf
    type: government
    accessed: 2026-11-09
  - id: s4
    title: "Annex 6: Guidance Sheet on Objective Tree Analysis"
    publisher: Food and Agriculture Organization of the United Nations (FAO)
    url: https://fao.org/4/ad694e/ad694e0a.htm
    type: intergovernmental
    accessed: 2026-11-09
  - id: s5
    title: "Fault Tree Handbook (NUREG-0492)"
    publisher: U.S. Nuclear Regulatory Commission
    url: https://apps.dtic.mil/sti/pdfs/ADA354973.pdf
    type: government
    accessed: 2026-11-09
created: 2026-11-09
---

# Issue Tree

An **issue tree** (also called a logic tree or, in Arnaud Chevallier's terminology, a question map) is a diagram that takes one key question and breaks it into a hierarchy of smaller sub-questions until each end point can be answered with a discrete piece of analysis.[^s3] Chevallier, a strategy professor at IMD Business School, describes such maps as cousins of mind maps, decision trees and the issue trees used by management consultants, but governed by their own explicit rules.[^s1] The tree turns a vague, sprawling problem into a visible structure, which is why it is a standard opening step in consulting engagements and public-sector implementation work.[^s1][^s3]

## Two kinds of tree

The most important design choice is which question the tree answers. A **why** (diagnostic) tree is problem-centric: it maps the possible root causes of an outcome, such as falling sales. A **how** (solution) tree is solution-centric: it maps the options for reaching a goal.[^s1] Chevallier argues that neither is superior but that the diagnostic question should usually come first, because understanding causes sharpens the key question that the solution tree will answer.[^s1] Rice Business's summary of his book gives a diagnostic example: a question about weak sales at an IT company branches into customers switching to competitors, the product being perceived as inferior, and each of the four Ps of marketing, each of which can be split again.[^s2]

## How it is built

Chevallier sets out four rules. First, a tree answers only one type of question, why or how, never a mix. Second, it moves from the key question toward answers, diverging across dimensions and drilling into detail; he suggests aiming for at least five layers and dozens of ideas before converging on a short list of formal options. Third, its branches should be mutually exclusive and collectively exhaustive, so that each possible answer appears exactly once. Fourth, the structure should be insightful as well as logically valid, especially at the top split, and the branches should end in concrete actions rather than abstractions.[^s1]

The UK civil service's implementation training adds practical steps around those rules. Teams should spend time agreeing the root question with stakeholders, keep sub-questions getting simpler as the tree deepens until they are close to yes-or-no questions, and then test the finished tree with stakeholders.[^s3] Each end branch is then paired with the evidence needed and a planned analysis, quantitative (such as trend analysis) or qualitative (such as interviews or customer journey mapping), so the tree doubles as a workplan and a frame for developing and testing hypotheses.[^s3]

## Evidence and critiques

The case for issue trees is mainly logical and cognitive rather than experimental. Chevallier's argument is that intuitive, first-idea decisions can go wrong in unpredictable settings even when decision makers feel confident, so mapping the solution space before choosing improves the odds of a good choice.[^s1] Rice Business notes that the discipline of listing divergent explanations reduces fixation on a single story and counters confirmation bias, the habit of seeking only evidence that supports an existing belief.[^s2] Chevallier's widely used illustration is a hotel told to fix slow elevators: most people list mechanical fixes, but a broader tree also surfaces ways to make the wait *feel* shorter, such as mirrors or screens, which proved far cheaper.[^s1][^s2]

The method has limits. Over-mapping can lead to analysis paralysis, so the advice is to stop when further detail no longer adds value.[^s2] Building a truly exhaustive set of branches is hard and demands both creative and critical thinking.[^s1] And no amount of rigour below the root can rescue a badly framed root question, which the UK guide treats as the first and most serious pitfall.[^s3]

## Related tree techniques

Issue trees share their logic with older tree methods. In engineering reliability, **fault tree analysis** is a deductive method that starts from one carefully chosen undesired "top event" and works down through AND and OR gates to the component failures that could produce it; the U.S. Nuclear Regulatory Commission's 1981 handbook warns that a top event that is too general makes the analysis unmanageable, a direct parallel to choosing the root question.[^s5] In development planning, a **problem tree** maps causes and effects of a core problem and is then converted into an **objective tree** by restating each negative condition as a positive future state, turning cause-effect links into means-results links, much as a why tree feeds a how tree.[^s4] The FAO cautions that applying this conversion too mechanically can yield objectives that are neither attainable nor sustainable.[^s4]

## Connections

The issue tree is a core tool of **structured problem solving**. It **depends on the MECE principle**, which governs how each node is split, and it is the scaffold for **hypothesis-driven problem solving**, in which end branches are tested against evidence.[^s1][^s3] A rule set for building such trees was codified by Arnaud Chevallier in *Strategic Thinking in Complex Problem Solving* (2016).[^s2] Diagnostic trees are a form of **root cause analysis**, and they **mitigate confirmation bias** by forcing alternatives onto the page.[^s2] It **contrasts with fault tree analysis**, which uses Boolean gates and probabilities for engineered systems, and is an **alternative to problem tree analysis** in development planning.[^s4][^s5] Chevallier recommends framing the key question through a situation-complication-question sequence, the opening device of the **Pyramid Principle**,[^s1] and the **marketing mix** often supplies one of the standard branch cuts in commercial diagnoses.[^s2]

## Sources

[^s1]: Arnaud Chevallier, "How to use maps to solve complex problems", OUPblog, Oxford University Press, 9 February 2020. https://blog.oup.com/2020/02/how-to-use-maps-to-solve-complex-problems/ (accessed 2026-11-09)
[^s2]: Rice Business Wisdom, "Solving Problems by Exploring the Far End of Possibility", based on Arnaud Chevallier, *Strategic Thinking in Complex Problem Solving* (Oxford University Press, 2016). https://business.rice.edu/wisdom/peer-reviewed-research/solving-problems-exploring-far-end-possibility (accessed 2026-11-09)
[^s3]: UK Government, "Implementation Insights: Using Issue Trees" (training slides). https://assets.publishing.service.gov.uk/media/5a816cd1e5274a2e8ab53eb1/Issue_Trees.pdf (accessed 2026-11-09)
[^s4]: FAO, *Participatory appraisal of nutrition and household food security situations and planning of interventions from a livelihoods perspective*, Annex 6, "Guidance Sheet on Objective Tree Analysis". https://fao.org/4/ad694e/ad694e0a.htm (accessed 2026-11-09)
[^s5]: W. E. Vesely, F. F. Goldberg, N. H. Roberts and D. F. Haasl, *Fault Tree Handbook* (NUREG-0492), U.S. Nuclear Regulatory Commission, January 1981. https://apps.dtic.mil/sti/pdfs/ADA354973.pdf (accessed 2026-11-09)
