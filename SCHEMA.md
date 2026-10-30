# Article schema

Each article is one **node** in the graph: `articles/<domain>/<slug>.md`, where the filename equals the id's slug and `<domain>` is a key in `topics/seeds.yaml`.

```markdown
---
id: kt:porters-five-forces             # stable node id: kt: + lowercase-hyphen slug
type: Framework                        # a class from ontology/ontology.ttl
title: Porter's Five Forces
aliases: [five forces framework, five competitive forces]
domain: strategy                       # a domain key from topics/seeds.yaml
summary: >-                            # 1–2 sentence definition (becomes skos:definition)
  A framework for analysing industry structure and profitability through five competitive forces.
broader: [kt:industry-analysis]
related: [kt:value-chain]
relations:                             # typed edges; predicates must exist in the ontology
  - {predicate: createdBy, object: kt:michael-porter}
  - {predicate: introducedIn, object: kt:competitive-strategy-book}
  - {predicate: critiques, object: kt:structure-conduct-performance-paradigm}
sources:                               # >= 3 total, >= 2 strong, >= 1 scholarly/primary/official
  - id: s1
    title: "The Five Competitive Forces That Shape Strategy"
    publisher: Harvard Business Review
    url: https://hbr.org/2008/01/the-five-competitive-forces-that-shape-strategy
    type: primary
    accessed: 2026-10-30
created: 2026-10-30
---

# Porter's Five Forces

Prose with inline footnote citations after each claim.[^s1]

## How it works
...

## Evidence and critiques
What research supports, what it doesn't, and the main criticisms.[^s2]

## In practice
How managers or consultants actually use it, with a real example.[^s3]

## Connections
How this node relates to its neighbours, in prose, with citations.

## Sources
[^s1]: Michael E. Porter, "The Five Competitive Forces That Shape Strategy", Harvard Business Review, 2008. https://hbr.org/... (accessed 2026-10-30)
```

## Rules enforced by `scripts/kg.py check`

- Required fields: `id, type, title, domain, summary, sources, created`.
- `type` must be a class, and every `relations.predicate` a property, in `ontology/ontology.ttl`.
- Every edge target is a `kt:` id. Targets with no article yet become **frontier** nodes (`graph/frontier.md`).
- Citations: at least 3 sources; at least 2 of a strong type; at least 1 scholarly, primary or official source (`peer-reviewed, academic, textbook, primary, government, intergovernmental, standards-body`); https only; no duplicate URLs; every source cited in the body and defined in `## Sources`; every substantive paragraph cited.
- Body of at least 350 words.
- Uniqueness: no duplicate ids, titles or aliases; no near-paraphrase titles; no bodies that overlap another article above the similarity threshold.

## Source types

| type | strong? | examples |
|---|---|---|
| peer-reviewed | yes | Strategic Management Journal, Academy of Management Journal, Journal of Finance, Management Science (prefer DOI links) |
| academic | yes | HBS Working Knowledge and faculty pages, NBER working papers, Wharton, MIT Sloan, Kelley research pages |
| textbook | yes | OpenStax (Principles of Management, Principles of Accounting, Principles of Marketing), published textbooks |
| primary | yes | the original paper or author article introducing an idea; SEC 10-K/10-Q filings, annual reports, statutes |
| government | yes | SEC, BLS, BEA, Federal Reserve, GAO, SBA, acquisition.gov (FAR) |
| intergovernmental | yes | OECD, IMF, World Bank, WTO |
| standards-body | yes | FASB, IFRS Foundation, ISO, PMI |
| encyclopedia | yes | Britannica |
| practitioner-journal | yes | Harvard Business Review, MIT Sloan Management Review, California Management Review |
| consultancy | no | McKinsey, BCG, Bain, Deloitte insights |
| news | no | WSJ, FT, Reuters, Bloomberg, The Economist, for events and company facts |
| organization | no | trade associations, think tanks |

Never cite Wikipedia, Investopedia-style content farms, essay mills, personal blogs, or AI-generated pages.
