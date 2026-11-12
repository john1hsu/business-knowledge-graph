---
id: kt:information-asymmetry
type: Theory
title: "Information Asymmetry: Unequal Knowledge Between Transacting Parties"
aliases: [information asymmetry, asymmetric information, markets with asymmetric information]
domain: managerial-economics
summary: >-
  The condition in which one party to a transaction knows more than the other about quality,
  risk or intentions, which can lead markets to price on averages, drive out high-quality
  sellers or low-risk buyers, and in extreme cases collapse, unless signaling, screening,
  guarantees or regulation close the gap.
broader: [kt:information-economics, kt:market-failure]
related: [kt:principal-agent-problem, kt:audit-committee, kt:truth-in-negotiations-act, kt:bullwhip-effect]
relations:
  - {predicate: createdBy, object: kt:george-akerlof}
  - {predicate: introducedIn, object: kt:the-market-for-lemons-1970}
  - {predicate: causes, object: kt:adverse-selection}
  - {predicate: causes, object: kt:moral-hazard}
  - {predicate: influenced, object: kt:signaling-theory}
  - {predicate: influenced, object: kt:screening-theory}
sources:
  - id: s1
    title: "The Market for 'Lemons': Quality Uncertainty and the Market Mechanism"
    publisher: Quarterly Journal of Economics, vol. 84, no. 3 (course copy, Simon Fraser University)
    url: https://www.sfu.ca/~allen/Ackerlof.pdf
    type: peer-reviewed
    accessed: 2026-11-12
  - id: s2
    title: "Job Market Signaling (RePEc record)"
    publisher: Quarterly Journal of Economics, vol. 87, no. 3, via EconPapers
    url: https://econpapers.repec.org/RePEc:oup:qjecon:v:87:y:1973:i:3:p:355-374.
    type: peer-reviewed
    accessed: 2026-11-12
  - id: s3
    title: "Press release: The Prize in Economic Sciences 2001"
    publisher: Royal Swedish Academy of Sciences (nobelprize.org)
    url: https://nobelprize.org/prizes/economic-sciences/2001/press-release
    type: organization
    accessed: 2026-11-12
  - id: s4
    title: "16.1 The Problem of Imperfect Information and Asymmetric Information"
    publisher: OpenStax, Principles of Economics 3e (Rice University)
    url: https://openstax.org/books/principles-economics-3e/pages/16-1-the-problem-of-imperfect-information-and-asymmetric-information
    type: textbook
    accessed: 2026-11-12
  - id: s5
    title: "The Market for Used Cars: A New Test of the Lemons Model"
    publisher: University of Bern, Department of Economics discussion paper
    url: https://boris.unibe.ch/142431/1/dp0202.pdf
    type: academic
    accessed: 2026-11-12
created: 2026-11-12
---

# Information Asymmetry

**Information asymmetry** (or asymmetric information) exists when one side of a transaction knows materially more than the other about what is being traded. OpenStax distinguishes it from the broader case of *imperfect* information, in which buyers, sellers or both lack full knowledge of price or quality; asymmetry is the specific case where knowledge is lopsided.[^s4] The Royal Swedish Academy of Sciences, awarding the 2001 economics prize for "analyses of markets with asymmetric information", gave borrowers and lenders, managers and shareholders, and insurance buyers and insurers as typical pairs.[^s3]

## Origin

The idea was put on a formal footing by George Akerlof's 1970 *Quarterly Journal of Economics* paper "The Market for 'Lemons'". Using used cars as the model, Akerlof showed that when only owners know whether a car is good, buyers pay a price based on average quality, so owners of good cars are underpaid and withdraw, a modified version of Gresham's law in which bad cars drive out good ones.[^s1] With many quality grades the process can cascade until no trade occurs at all, even though buyers and sellers would trade under symmetric information.[^s1] Michael Spence's 1973 "Job Market Signaling" and Joseph Stiglitz's work on screening extended the analysis, and the three shared the 2001 prize.[^s2][^s3]

## How it works

Asymmetry creates two problems and two families of remedies. When the hidden element is a characteristic known before contracting, such as a car's quality or an applicant's health, the result is **adverse selection**: Akerlof's example was health insurance for people over 65, where raising premiums drives out healthier applicants and can leave no viable price.[^s1] When the hidden element is behaviour after contracting, the result is moral hazard, the core of the principal-agent problem.[^s3]

The remedies differ by who moves first:

- **Signaling.** The informed party takes a costly action that low-quality types would find too expensive to copy; Spence's case was education as a signal of productivity, later applied to dividends as a signal of profitability.[^s2][^s3]
- **Screening.** The uninformed party designs a menu that makes the informed party reveal itself, as when insurers offer lower premiums in exchange for higher deductibles to sort customers by risk.[^s3]
- **Institutions.** Akerlof listed guarantees, brand names, chains and licensing as institutions that arise to counteract quality uncertainty.[^s1] OpenStax adds money-back guarantees, warranties, reputation, résumés and transcripts, probationary periods, credit checks, collateral and FTC truth-in-advertising rules.[^s4]

The cost of asymmetry is not only the losses of the cheated buyer. Akerlof argued that dishonest sellers also push honest ones out of the market, and used this to explain why business is harder where quality varies widely, as in village credit markets where outside lenders attract only the riskiest borrowers.[^s1]

## Evidence and critiques

The prediction that markets unravel has proven weaker in practice than in theory. An early direct test by Eric Bond compared maintenance records of new and used pickup trucks and found no quality difference for trucks under ten years old, with more repairs only for older, recently traded trucks.[^s5] Winand Emons and Sheldon George, using Swiss inspection and registration records for cars first registered in Basle in 1985 and tracked to 1991, found that privately sold used cars were about 27 percent more likely to have defects than a random car, while dealer-sold cars were about 10 percent less likely; yet only about 10 percent of used cars were resold, leading them to conclude that the lemons problem was not widespread.[^s5]

The usual reading is that the counteracting institutions Akerlof described, such as dealer reputations and inspections, absorb much of the problem, so the theory is better at explaining which institutions exist than at predicting collapse.[^s1][^s5] OpenStax also notes a side effect of some remedies: occupational licensing signals competence but can raise barriers to entry.[^s4]

## In practice

The used-car trade is the textbook example. Emons and George's finding that dealer-sold cars were in better condition than privately sold ones fits the idea that a dealer's reputation and repeat business work as a quality guarantee that a one-time private seller cannot offer.[^s5] OpenStax gives a sharper case from gemstones: emeralds are often treated with oil or epoxy to hide flaws, which is legal when disclosed, yet a 1997 lawsuit and a TV investigation showed sellers often failed to disclose it.[^s4] In finance and insurance, deductible menus and dividend policy are standard screening and signaling devices.[^s3]

## Connections

Information asymmetry is a central topic of **information economics** and a classic source of **market failure**, as in Akerlof's model where trade disappears despite gains from trade.[^s1] It was formalized by (**created by**) **George Akerlof** and **introduced in** his 1970 lemons paper.[^s1] It **causes adverse selection** and **moral hazard**, and the **principal-agent problem** is its contractual form between managers and owners or insurers and insured.[^s3] It **influenced** **signaling theory** (Spence) and **screening theory** (Stiglitz).[^s2][^s3] Several existing nodes are countermeasures to it: the **audit committee** narrows the gap between managers and shareholders that the Academy named, and the **Truth in Negotiations Act** forces contractors to disclose cost data the government cannot otherwise see. Lopsided demand information between supply-chain stages is a root of the **bullwhip effect**, as that node's article explains.

## Sources

[^s1]: George A. Akerlof, "The Market for 'Lemons': Quality Uncertainty and the Market Mechanism", Quarterly Journal of Economics 84(3), 1970, pp. 488–500. https://www.sfu.ca/~allen/Ackerlof.pdf (accessed 2026-11-12)
[^s2]: A. Michael Spence, "Job Market Signaling", Quarterly Journal of Economics 87(3), 1973, pp. 355–374 (EconPapers record). https://econpapers.repec.org/RePEc:oup:qjecon:v:87:y:1973:i:3:p:355-374. (accessed 2026-11-12)
[^s3]: Royal Swedish Academy of Sciences, "The Prize in Economic Sciences 2001" press release, 10 October 2001. https://nobelprize.org/prizes/economic-sciences/2001/press-release (accessed 2026-11-12)
[^s4]: Steven A. Greenlaw, David Shapiro and Daniel MacDonald, *Principles of Economics 3e*, OpenStax, 2022, section 16.1. https://openstax.org/books/principles-economics-3e/pages/16-1-the-problem-of-imperfect-information-and-asymmetric-information (accessed 2026-11-12)
[^s5]: Winand Emons and Sheldon George, "The Market for Used Cars: A New Test of the Lemons Model", University of Bern discussion paper, 2002. https://boris.unibe.ch/142431/1/dp0202.pdf (accessed 2026-11-12)
