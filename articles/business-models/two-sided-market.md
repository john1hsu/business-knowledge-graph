---
id: kt:two-sided-market
type: Concept
title: Two-Sided Market
aliases: [two-sided markets, two-sided network, multi-sided market, two-sided platform market]
domain: business-models
summary: >-
  A market in which a platform serves two distinct groups of users whose value from joining
  depends on participation by the other group, so the platform must set prices for both sides
  jointly and often subsidizes one side to attract the other.
broader: [kt:network-effect, kt:platform-business-model]
related: [kt:freemium, kt:aggregation-theory, kt:razor-and-blades-model, kt:switching-costs]
relations:
  - {predicate: createdBy, object: kt:jean-charles-rochet}
  - {predicate: createdBy, object: kt:jean-tirole}
  - {predicate: introducedIn, object: kt:platform-competition-in-two-sided-markets-2003}
  - {predicate: exemplifiedBy, object: kt:ohio-v-american-express}
  - {predicate: studiedIn, object: kt:industrial-organization}
sources:
  - id: s1
    title: "Platform Competition in Two-Sided Markets"
    publisher: Journal of the European Economic Association (author copy, Universidad de Granada)
    url: https://www.ugr.es/~scarbo/ROCHETIR.pdf
    type: primary
    accessed: 2026-10-30
  - id: s2
    title: "Platform Competition in Two-Sided Markets (RePEc record)"
    publisher: IDEAS/RePEc
    url: https://ideas.repec.org/a/tpr/jeurec/v1y2003i4p990-1029.html
    type: academic
    accessed: 2026-10-30
  - id: s3
    title: "Competition in two-sided markets"
    publisher: RAND Journal of Economics (UCL Discovery record)
    url: https://discovery.ucl.ac.uk/id/eprint/4324/
    type: peer-reviewed
    accessed: 2026-10-30
  - id: s4
    title: "Strategies for Two-Sided Markets"
    publisher: Harvard Business Review (course copy, KTH)
    url: https://www.kth.se/social/files/546b8e7ef2765474dd3f23fe/4.Eisenmann+et+al+(2006).pdf
    type: practitioner-journal
    accessed: 2026-10-30
  - id: s5
    title: "Two-Sided Markets (OECD Roundtables on Competition Policy)"
    publisher: OECD
    url: https://www.oecd.org/en/publications/two-sided-markets_1ab6f5f3-en.html
    type: intergovernmental
    accessed: 2026-10-30
  - id: s6
    title: "Ohio v. American Express Co., 585 U.S. ___ (2018)"
    publisher: Legal Information Institute, Cornell Law School
    url: https://www.law.cornell.edu/supremecourt/text/16-1454
    type: primary
    accessed: 2026-10-30
created: 2026-10-30
---

# Two-Sided Market

A **two-sided market** is one in which a platform enables interactions between two distinct groups of end users, and each group's benefit from the platform depends on how many members of the other group participate. Because users on one side do not take into account the value their participation creates for the other side, the platform has to coordinate both groups, or in Rochet and Tirole's phrase, "get both sides on board."[^s1] Classic examples include payment cards (cardholders and merchants), video-game consoles (players and developers), operating systems (users and application developers), and ad-supported media (audiences and advertisers).[^s1]

## Origin

The idea was formalized by economists Jean-Charles Rochet and Jean Tirole of the Institut d'Economie Industrielle in Toulouse in "Platform Competition in Two-Sided Markets," published in the *Journal of the European Economic Association* (vol. 1, no. 4, 2003, pp. 990–1029).[^s2] Their model, built around the payment-card industry, compared how profit-maximizing platforms and not-for-profit associations allocate prices between the two sides, and benchmarked both against an integrated monopolist and a socially optimal Ramsey planner.[^s2] Mark Armstrong's "Competition in two-sided markets" (*RAND Journal of Economics*, 2006) extended the analysis with models of a monopoly platform, competing platforms where each agent joins only one, and "competitive bottlenecks" where one group joins every platform.[^s3]

## How it works

The defining feature is that the **price structure**, not just the price level, matters. In Rochet and Tirole's monopoly model the total price follows a familiar markup rule, but how that total is split between buyers and sellers depends on the relative demand elasticities of each side.[^s1] The side that brings more value to the other side, such as "marquee" buyers whom sellers want to reach, tends to be subsidized, while captive users locked in by contracts shift charges onto them.[^s1] Armstrong showed that equilibrium prices are driven by the relative size of cross-group externalities, by whether platforms charge lump-sum or per-transaction fees, and by whether agents single-home or multi-home.[^s3] When one side multi-homes, platforms compete fiercely for the side that single-homes and can charge the multi-homing side more.[^s1][^s3]

For managers, Eisenmann, Parker and Van Alstyne translated these results into a "subsidy side" and a "money side." They advised subsidizing the more price-sensitive side, charging the side that must supply quality, and avoiding giveaways when each extra user is costly; they also argued that markets tip toward a single winner when multi-homing costs are high, cross-side network effects are strong, and demand for specialized features is weak.[^s4]

## Evidence and critiques

The theory explains why prices below marginal cost on one side can be ordinary profit-maximizing behavior rather than predation, which has made it central to competition policy. The OECD's Competition Committee devoted a June 2009 roundtable to two-sided markets, gathering submissions from about 20 jurisdictions on how the concept should change antitrust analysis.[^s5] The approach is contested, however. In *Ohio v. American Express* (decided June 25, 2018, 5–4), the U.S. Supreme Court majority held that credit-card networks are two-sided transaction platforms whose market must include both cardholders and merchants, and found that plaintiffs had not shown net harm from Amex's anti-steering rules.[^s6] Justice Breyer's dissent argued that "two-sided transaction platform" is not an established antitrust category and that merchant and cardholder services are complements rather than substitutes, so they should not be merged into one market.[^s6] Critics also note that the strategic prescriptions are case-specific: Eisenmann and co-authors observed that similar-looking networks such as PCs and game consoles call for opposite pricing.[^s4]

## Real-world example

Video-game consoles illustrate the logic. Platforms have typically sold consoles at or below cost to players and recovered revenue from developers through fees and per-unit royalties.[^s1] PC operating systems took the opposite path, charging users while giving developers free tools.[^s4] Adobe's free Reader paired with paid authoring software is a further example of subsidizing the price-sensitive side.[^s4]

## Connections

A two-sided market is a special case of a **network effect** in which the externality runs across groups rather than within one, and it is the economic foundation of the **platform business model**.[^s3][^s4] It underlies **freemium** and **razor-and-blades** pricing, where one product or user group is subsidized to monetize another, and it informs **aggregation theory** about internet platforms. High multi-homing costs connect it to **switching costs**.[^s4] The concept was created by Rochet and Tirole, is studied within **industrial organization**, and is exemplified in law by *Ohio v. American Express*.[^s2][^s6]

## Sources
[^s1]: Jean-Charles Rochet and Jean Tirole, "Platform Competition in Two-Sided Markets", Journal of the European Economic Association 1(4), 2003. https://www.ugr.es/~scarbo/ROCHETIR.pdf (accessed 2026-10-30)
[^s2]: IDEAS/RePEc record for Rochet and Tirole (2003). https://ideas.repec.org/a/tpr/jeurec/v1y2003i4p990-1029.html (accessed 2026-10-30)
[^s3]: Mark Armstrong, "Competition in two-sided markets", RAND Journal of Economics 37(3), 2006, pp. 668–691. https://discovery.ucl.ac.uk/id/eprint/4324/ (accessed 2026-10-30)
[^s4]: Thomas Eisenmann, Geoffrey Parker and Marshall W. Van Alstyne, "Strategies for Two-Sided Markets", Harvard Business Review, October 2006. https://www.kth.se/social/files/546b8e7ef2765474dd3f23fe/4.Eisenmann+et+al+(2006).pdf (accessed 2026-10-30)
[^s5]: OECD, "Two-Sided Markets", OECD Roundtables on Competition Policy Papers, December 2009. https://www.oecd.org/en/publications/two-sided-markets_1ab6f5f3-en.html (accessed 2026-10-30)
[^s6]: Ohio v. American Express Co., No. 16-1454 (U.S. June 25, 2018), Legal Information Institute. https://www.law.cornell.edu/supremecourt/text/16-1454 (accessed 2026-10-30)
