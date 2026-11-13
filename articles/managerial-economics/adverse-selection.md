---
id: kt:adverse-selection
type: Concept
title: "Adverse Selection: Hidden Information Before a Contract"
aliases: [adverse selection, hidden information problem, anti-selection]
domain: managerial-economics
summary: >-
  The tendency, when one side of a market privately knows its own risk or quality before
  contracting, for a single average price to attract disproportionately the high-cost or
  low-quality types, shrinking or even unravelling the market; firms respond by screening,
  signaling, pooling and mandates.
broader: [kt:information-asymmetry, kt:market-failure]
related: [kt:principal-agent-problem, kt:contract-theory]
relations:
  - {predicate: createdBy, object: kt:george-akerlof}
  - {predicate: introducedIn, object: kt:the-market-for-lemons-1970}
  - {predicate: contrastsWith, object: kt:moral-hazard}
  - {predicate: causes, object: kt:insurance-death-spiral}
  - {predicate: influenced, object: kt:screening-theory}
  - {predicate: appliesTo, object: kt:insurance-industry}
sources:
  - id: s1
    title: "The Market for 'Lemons': Quality Uncertainty and the Market Mechanism"
    publisher: Quarterly Journal of Economics, vol. 84, no. 3 (course copy, Simon Fraser University)
    url: https://www.sfu.ca/~allen/Ackerlof.pdf
    type: primary
    accessed: 2026-11-13
  - id: s2
    title: "Equilibrium in Competitive Insurance Markets: An Essay on the Economics of Imperfect Information"
    publisher: Quarterly Journal of Economics, vol. 90, no. 4 (course copy, Universidad Carlos III de Madrid)
    url: https://www.eco.uc3m.es/docencia/MicroII/Rothschild-Stiglitz%201976.pdf
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s3
    title: "Selection in Insurance Markets: Theory and Empirics in Pictures"
    publisher: National Bureau of Economic Research, Working Paper 16723 (published in Journal of Economic Perspectives 25(1), 2011)
    url: https://nber.org/system/files/working_papers/w16723/w16723.pdf
    type: academic
    accessed: 2026-11-13
  - id: s4
    title: "Paying for Health Insurance: The Tradeoff between Competition and Adverse Selection"
    publisher: National Bureau of Economic Research, Working Paper 5796
    url: https://www.nber.org/papers/w5796
    type: academic
    accessed: 2026-11-13
  - id: s5
    title: "16.2 Insurance and Imperfect Information"
    publisher: OpenStax, Principles of Economics 3e (Rice University)
    url: https://openstax.org/books/principles-economics-3e/pages/16-2-insurance-and-imperfect-information
    type: textbook
    accessed: 2026-11-13
  - id: s6
    title: "Press release: The Prize in Economic Sciences 2001"
    publisher: Royal Swedish Academy of Sciences (nobelprize.org)
    url: https://nobelprize.org/prizes/economic-sciences/2001/press-release
    type: organization
    accessed: 2026-11-13
created: 2026-11-13
---

# Adverse Selection

**Adverse selection** arises when the party on one side of a deal privately knows a characteristic that determines the other side's cost, such as a driver's accident risk, a borrower's default risk or a seller's product quality, and that knowledge exists *before* the contract is signed. If the uninformed side must charge one price to everyone, the people most eager to accept that price are disproportionately the expensive ones. OpenStax defines it in insurance terms: buyers know better than the insurer whether they are high- or low-risk, and the high-risk ones seek more coverage.[^s5] It is the hidden-information counterpart to moral hazard, which concerns hidden actions taken after contracting.[^s3]

## Origin

George Akerlof introduced the mechanism in his 1970 "lemons" paper. Alongside used cars, he analysed health insurance for people over 65: as premiums rise, the remaining applicants are increasingly those who expect to need care, so there may be no price at which policies sell, an argument he used in favour of a public scheme such as Medicare.[^s1] The Royal Swedish Academy of Sciences cited this work in the 2001 economics prize, noting applications to high interest rates in local credit markets in developing countries and to older people's difficulty buying individual medical cover.[^s6]

## How it works

Michael Rothschild and Joseph Stiglitz (1976) asked what competitive insurers do when they cannot observe risk. Because a contract specifies both a price and a quantity of cover, buyers' choices among contracts can reveal their type. They showed that a pooled contract covering both risk groups cannot survive, because a rival can always design a policy that skims off only the low-risk customers. In the separating equilibrium, high-risk buyers get full insurance at fair odds while low-risk buyers get only partial cover, the restriction that keeps high-risk buyers from mimicking them; and when high-risk buyers are few, no equilibrium may exist at all.[^s2] The low-risk group's loss buys nothing for the high-risk group, so the authors called the externality "completely dissipative".[^s2]

Liran Einav and Amy Finkelstein recast the textbook model as a demand curve and a cost curve. With adverse selection, the buyers willing to pay most are also the costliest, so marginal cost falls as coverage expands. Competitive prices settle where demand meets average cost, which lies above marginal cost, so too few people are insured; the welfare loss is the triangle between demand and marginal cost.[^s3] If average cost exceeds demand everywhere, nobody buys even though covering everyone would be efficient, and repricing each year at last year's average cost can make enrolment shrink until the market unravels.[^s3] OpenStax tells the same story in prose: average-cost premiums drive away low-risk buyers, which forces premiums up and pushes out medium-risk buyers next.[^s5]

## Evidence and critiques

The cleanest documented spiral comes from Harvard University. In the mid-1990s it switched from subsidising more expensive health plans to paying an equal amount toward every plan. David Cutler and Sarah Reber found a short-run price elasticity of about -2, adverse selection large enough to triple the long-run response, and a welfare loss of about 2 percent of baseline health spending; yet premiums to Harvard fell nearly 10 percent relative to the Boston area, so the reform still raised welfare overall.[^s4]

Measuring adverse selection is harder than describing it. The common "positive correlation" test asks whether insured people have higher expected costs than uninsured people at the same price, but a positive result is equally consistent with moral hazard; using price variation to trace out the cost curve directly avoids that confusion.[^s3] Selection can also run the other way. When lower-risk people are more risk-averse, as research suggests for long-term care insurance and Medigap, the result is *advantageous* selection and over-insurance, so the policy prescription can flip.[^s3]

## In practice

Firms and governments counter adverse selection in four main ways. **Screening** menus let customers sort themselves; the Academy's example is insurers trading higher deductibles for lower premiums.[^s6] **Pooling** through employer group plans spreads risk across people who were not selected on health.[^s5] **Mandates** stop low-risk people from opting out; the US Affordable Care Act paired a ban on denying cover for preexisting conditions with an individual mandate, whose penalty was eliminated from 2019.[^s5] **Subsidies** large enough can restore efficient coverage, whereas mandates can over-insure if selection is advantageous.[^s3] Akerlof also pointed to private institutions, including guarantees, brand names and licensing, that arise to blunt quality uncertainty.[^s1]

## Connections

Adverse selection is a consequence of **information asymmetry** and a textbook form of **market failure**, since trade that would benefit both sides can vanish.[^s1][^s3] It was **created by** **George Akerlof** and **introduced in** his 1970 lemons paper.[^s1] It **contrasts with** **moral hazard**: one hides a type before contracting, the other hides behaviour afterward, and empirical tests struggle to tell them apart.[^s3] It **causes** the **insurance death spiral** seen at Harvard and **applies to** the **insurance industry** above all.[^s3][^s4] Rothschild and Stiglitz's self-selection analysis **influenced** **screening theory**, and the design of contracts that make hidden types reveal themselves is a core problem of **contract theory** and of the **principal-agent problem**.[^s2][^s6]

## Sources

[^s1]: George A. Akerlof, "The Market for 'Lemons': Quality Uncertainty and the Market Mechanism", Quarterly Journal of Economics 84(3), 1970, pp. 488–500. https://www.sfu.ca/~allen/Ackerlof.pdf (accessed 2026-11-13)
[^s2]: Michael Rothschild and Joseph Stiglitz, "Equilibrium in Competitive Insurance Markets: An Essay on the Economics of Imperfect Information", Quarterly Journal of Economics 90(4), 1976, pp. 629–649. https://www.eco.uc3m.es/docencia/MicroII/Rothschild-Stiglitz%201976.pdf (accessed 2026-11-13)
[^s3]: Liran Einav and Amy Finkelstein, "Selection in Insurance Markets: Theory and Empirics in Pictures", NBER Working Paper 16723, January 2011; Journal of Economic Perspectives 25(1), 2011. https://nber.org/system/files/working_papers/w16723/w16723.pdf (accessed 2026-11-13)
[^s4]: David M. Cutler and Sarah J. Reber, "Paying for Health Insurance: The Tradeoff between Competition and Adverse Selection", NBER Working Paper 5796, 1996; Quarterly Journal of Economics 113(2), 1998. https://www.nber.org/papers/w5796 (accessed 2026-11-13)
[^s5]: Steven A. Greenlaw, David Shapiro and Daniel MacDonald, *Principles of Economics 3e*, OpenStax, 2022, section 16.2. https://openstax.org/books/principles-economics-3e/pages/16-2-insurance-and-imperfect-information (accessed 2026-11-13)
[^s6]: Royal Swedish Academy of Sciences, "The Prize in Economic Sciences 2001" press release, 10 October 2001. https://nobelprize.org/prizes/economic-sciences/2001/press-release (accessed 2026-11-13)
