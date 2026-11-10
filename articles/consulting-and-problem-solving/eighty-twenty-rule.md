---
id: kt:eighty-twenty-rule
type: Concept
title: 80/20 Rule
aliases: [Pareto principle, Pareto's principle, principle of factor sparsity, vital few and trivial many, law of the vital few]
domain: consulting-and-problem-solving
summary: >-
  The heuristic that, in many populations of causes, a small share of items accounts for most of
  the effect (conventionally 20% producing 80%), named by Joseph Juran after Vilfredo Pareto's
  observations on wealth and used to focus analysis and improvement on the "vital few".
broader: [kt:structured-problem-solving]
related: [kt:issue-tree, kt:hypothesis-driven-problem-solving, kt:mece-principle, kt:total-quality-management]
relations:
  - {predicate: createdBy, object: kt:joseph-juran}
  - {predicate: influencedBy, object: kt:vilfredo-pareto}
  - {predicate: influencedBy, object: kt:lorenz-curve}
  - {predicate: introducedIn, object: kt:quality-control-handbook}
  - {predicate: measuredBy, object: kt:pareto-chart}
  - {predicate: dependsOn, object: kt:power-law}
  - {predicate: contrastsWith, object: kt:long-tail}
sources:
  - id: s1
    title: "The Non-Pareto Principle; Mea Culpa"
    publisher: Juran Institute (reprint of J. M. Juran, 1974)
    url: https://www.juran.com/wp-content/uploads/2021/03/The-Non-Pareto-Principle-1974.pdf
    type: primary
    accessed: 2026-11-10
  - id: s2
    title: "Vilfredo Pareto"
    publisher: Encyclopaedia Britannica
    url: https://www.britannica.com/print/article/443519
    type: encyclopedia
    accessed: 2026-11-10
  - id: s3
    title: "Power laws, Pareto distributions and Zipf's law"
    publisher: Contemporary Physics (arXiv preprint cond-mat/0412004)
    url: https://arxiv.org/abs/cond-mat/0412004
    type: peer-reviewed
    accessed: 2026-11-10
  - id: s4
    title: "What is a Pareto Chart? Analysis & Diagram"
    publisher: American Society for Quality (ASQ)
    url: https://asq.org/quality-resources/pareto
    type: organization
    accessed: 2026-11-10
  - id: s5
    title: "Should You Invest in the Long Tail?"
    publisher: Harvard Business School Faculty & Research
    url: https://www.hbs.edu/faculty/Pages/item.aspx?num=32337
    type: academic
    accessed: 2026-11-10
created: 2026-11-10
---

# 80/20 Rule

The **80/20 rule**, better known in quality management as the **Pareto principle**, is the observation that in many sets of causes a small minority accounts for most of the result: a few defect types for most quality losses, a few products for most sales. The 80/20 ratio is a convention rather than a law; the working idea is that effort should go first to the "vital few" causes. Quality pioneer Joseph Juran named the principle and later conceded that the name was a mistake, because Vilfredo Pareto had studied only the distribution of wealth.[^s1]

## Origin

Pareto, an engineer-turned-economist who succeeded Léon Walras at the University of Lausanne in 1893, set out a much-criticized law of income distribution in his first book, *Cours d'économie politique* (1896–97). He argued that income and wealth were not distributed randomly but followed a consistent pattern across eras and societies.[^s2] Juran generalized that pattern. In his account, he first wrote about the unequal distribution of quality losses in *Industrial Quality Control* in 1950 and then, in the first edition of his *Quality Control Handbook* (1951), captioned a chart comparing wealth and quality losses with Pareto's name, presenting both as cases of one principle of unequal distribution.[^s1] In 1954 he coined the phrase *vital few and trivial many* in *The Management Review*, and in the 1974 third edition of the handbook he replaced *trivial many* with *useful many*, since the many smaller causes still matter.[^s1] In his 1974 note Juran admitted he had applied the wrong name, observing that Pareto never proposed a universal, and that the cumulative curves he had used should have been credited to economist M. O. Lorenz's 1905 work on measuring wealth concentration.[^s1]

## How it works

In practice the principle is operationalized through **Pareto analysis**. The American Society for Quality lists the Pareto chart among the seven basic quality tools: categories of problems or causes are measured by frequency, cost or time, drawn as bars from tallest to shortest, and often overlaid with a cumulative-percentage line that reaches 100%.[^s4] ASQ recommends it for spotting the most significant of many problems, breaking broad causes into specific ones, and communicating data. In its example, customer complaints are first sorted into five categories; the largest, document-related complaints, is then split again to show which document type to fix first.[^s4] This repeated drill-down is how consultants use the rule to pick the branches of an issue tree worth analysing first.

## Evidence and critiques

There is a mathematical basis for the rule, but the 80/20 split is not guaranteed. Physicist Mark Newman's review of power laws shows that many quantities, including personal wealth, city sizes and earthquakes, follow Pareto distributions. For such a distribution with exponent α greater than 2, the share of the total held by the top fraction *P* is *P*^((α−2)/(α−1)).[^s3] With the exponents he reports for wealth, the richest 20% would hold about 80% of the wealth, and with α = 2.1 about 86%. In other words, the exact ratio depends on the exponent, and for distributions that are not heavy-tailed the rule can fail entirely.[^s3] Juran's own critique is about the label: crediting a universal to Pareto distorts the history, and the *trivial many* wording invites managers to ignore causes that together are still useful.[^s1]

## In practice

Concentration often holds even where theory predicted it would weaken. Chris Anderson's *The Long Tail* (2006) argued that unlimited online shelf space would shift demand toward niche products. Harvard Business School professor Anita Elberse tested this in music and home video with Nielsen SoundScan and VideoScan data and data from Rhapsody and the DVD-by-mail service Quickflix. She found that blockbusters were capturing a larger share of the market than before, and that buyers in the tail showed little strong preference for niche titles (*Harvard Business Review*, July–August 2008).[^s5] Her findings suggest that the vital-few logic still applies in hit-driven businesses, even when distribution costs fall close to zero.[^s5]

## Connections

The 80/20 rule is a prioritization heuristic within **structured problem solving**. Consultants can use it to rank the end branches of an **issue tree** and to choose which hypotheses to test first in **hypothesis-driven problem solving**. Because a Pareto chart assigns every item to exactly one category, grouping small ones as "other", it pairs naturally with the **MECE principle**.[^s4] It was **created by Joseph Juran** and **introduced in the Quality Control Handbook**, where it became a staple of **total quality management**.[^s1] It is **influenced by Vilfredo Pareto's** income law and by the **Lorenz curve**.[^s1][^s2] It is **measured by the Pareto chart**[^s4] and **depends on power-law** (Pareto-distributed) data.[^s3] It **contrasts with the long tail** thesis, which predicted that demand would spread away from the top sellers.[^s5]

## Sources

[^s1]: J. M. Juran, "The Non-Pareto Principle; Mea Culpa" (1974), reprinted by the Juran Institute. https://www.juran.com/wp-content/uploads/2021/03/The-Non-Pareto-Principle-1974.pdf (accessed 2026-11-10)
[^s2]: Encyclopaedia Britannica, "Vilfredo Pareto". https://www.britannica.com/print/article/443519 (accessed 2026-11-10)
[^s3]: M. E. J. Newman, "Power laws, Pareto distributions and Zipf's law", *Contemporary Physics* 46(5), 2005, doi:10.1080/00107510500052444; arXiv cond-mat/0412004. https://arxiv.org/abs/cond-mat/0412004 (accessed 2026-11-10)
[^s4]: American Society for Quality, "What is a Pareto Chart? Analysis & Diagram". https://asq.org/quality-resources/pareto (accessed 2026-11-10)
[^s5]: Anita Elberse, "Should You Invest in the Long Tail?", *Harvard Business Review* 86(7/8), July–August 2008, pp. 88–96; Harvard Business School Faculty & Research abstract. https://www.hbs.edu/faculty/Pages/item.aspx?num=32337 (accessed 2026-11-10)
