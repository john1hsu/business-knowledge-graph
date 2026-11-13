---
id: kt:moral-hazard
type: Concept
title: "Moral Hazard: Risk-Taking When Others Bear the Cost"
aliases: [moral hazard, hidden action, hidden-action problem]
domain: managerial-economics
summary: >-
  The tendency of a party who is insured, paid or otherwise protected against the consequences of
  its actions to take less care or more risk than it would if it bore the full cost, because the
  other party cannot observe or contract on those actions; it is managed with cost sharing,
  monitoring and incentive pay rather than eliminated.
broader: [kt:information-asymmetry, kt:contract-theory]
related: [kt:principal-agent-problem, kt:agency-costs, kt:business-format-franchising, kt:bengt-holmstrom]
relations:
  - {predicate: contrastsWith, object: kt:adverse-selection}
  - {predicate: introducedIn, object: kt:uncertainty-and-the-welfare-economics-of-medical-care-1963}
  - {predicate: influenced, object: kt:informativeness-principle}
  - {predicate: exemplifiedBy, object: kt:rand-health-insurance-experiment}
  - {predicate: appliesTo, object: kt:executive-compensation}
sources:
  - id: s1
    title: "Uncertainty and the Welfare Economics of Medical Care"
    publisher: American Economic Review, vol. 53, no. 5 (reprint, Stanford CASBS)
    url: https://casbs.stanford.edu/sites/default/files/media/file/kenneth-arrow-medical-care.pdf
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s2
    title: "Moral Hazard and Observability (RePEc record)"
    publisher: Bell Journal of Economics, vol. 10, no. 1, via EconPapers
    url: https://econpapers.repec.org/RePEc:rje:bellje:v:10:y:1979:i:spring:p:74-91
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s3
    title: "16.2 Insurance and Imperfect Information"
    publisher: OpenStax, Principles of Economics 3e (Rice University)
    url: https://openstax.org/books/principles-economics-3e/pages/16-2-insurance-and-imperfect-information
    type: textbook
    accessed: 2026-11-13
  - id: s4
    title: "The Health Insurance Experiment: A Classic RAND Study Speaks to the Current Health Care Reform Debate"
    publisher: RAND Corporation research brief RB-9174
    url: https://www.rand.org/pubs/research_briefs/RB9174.html
    type: academic
    accessed: 2026-11-13
  - id: s5
    title: "The RAND Health Insurance Experiment, Three Decades Later"
    publisher: National Bureau of Economic Research, Working Paper 18642
    url: https://www.nber.org/papers/w18642.pdf
    type: academic
    accessed: 2026-11-13
  - id: s6
    title: "Popular information: The Prize in Economic Sciences 2016"
    publisher: Royal Swedish Academy of Sciences (nobelprize.org)
    url: https://nobelprize.org/prizes/economic-sciences/2016/popular-information
    type: organization
    accessed: 2026-11-13
created: 2026-11-13
---

# Moral Hazard

**Moral hazard** is the change in behaviour that occurs when someone is shielded from the full consequences of their own actions and the party bearing those consequences cannot see what they do. OpenStax defines it in the insurance setting as coverage leading people to take riskier actions than they otherwise would, and stresses that it can be reduced but not eliminated.[^s3] The concept generalizes well beyond insurance to any contract in which one side's effort or care is hidden: employees and employers, managers and shareholders, borrowers and lenders, franchisees and franchisors.[^s6]

## Origin

The term came from the insurance trade, but Kenneth Arrow's 1963 *American Economic Review* article on medical care brought it into economics. Arrow observed that insurance works best when the insured event is entirely outside the policyholder's control, a separation he said real life never achieves. Fire is mostly accidental yet partly a function of carelessness, and medical costs depend on the patient's and doctor's choices about how much care to use.[^s1] He noted that broad health insurance raises the demand for care, that it weakens patients' and physicians' incentive to shop on price, and that insurers had begun adding coinsurance to major medical policies partly for this reason.[^s1]

Bengt Holmström's 1979 paper "Moral Hazard and Observability" in the *Bell Journal of Economics* recast the problem as a principal-agent contract in which the agent's action is unobservable, and asked when extra, imperfect information about that action can improve on paying for outcomes alone.[^s2] He derived a necessary and sufficient condition for such information to be valuable, now known as the informativeness principle.[^s2][^s6]

## How it works

Moral hazard is a problem of *hidden action* after a contract is signed, in contrast to adverse selection, which concerns *hidden characteristics* before contracting. OpenStax gives everyday cases: insured drivers park less carefully, insured patients take fewer precautions, and an insured business installs only minimal security and sprinklers.[^s3] The provider side matters too: fee-for-service payment rewards supplying more care, whereas a health maintenance organization paid a fixed amount per enrollee has a reason to curb unnecessary services.[^s3]

Contract theory frames the remedy as a trade-off between risk sharing and incentives. Because employers usually bear risk better than employees, a fully insured agent has no reason to work hard, while a fully exposed one bears too much risk. The Nobel committee's 2016 summary of Holmström's work explains that the harder effort is to observe and the noisier the outcome, the more pay should lean toward a fixed salary.[^s6] The informativeness principle says pay should depend on every measure that reveals something about the agent's actions, which is why comparing a manager's share-price performance with that of similar firms filters out luck.[^s6] Holmström and Paul Milgrom later showed that strong pay for easy-to-measure tasks can starve hard-to-measure ones, such as teachers neglecting creativity when paid on test scores.[^s6]

Standard tools follow from this logic:

- **Cost sharing.** Deductibles, copayments and coinsurance leave the insured bearing part of each loss.[^s3]
- **Monitoring.** Insurers investigate fraud, observe behaviour and discount premiums for approved safety systems.[^s3]
- **Performance pay with relative evaluation.** Tie rewards to informative, noise-filtered measures rather than raw outcomes.[^s6]

## Evidence and critiques

The best-known test is the RAND Health Insurance Experiment. RAND's summary reports that it randomly assigned more than 7,700 people under 65 in 2,750 families at six U.S. sites to free care, 25, 50 or 95 percent coinsurance, or a group-cooperative HMO.[^s4] Those with 25 percent coinsurance spent about 20 percent less than the free-care group and those with 95 percent about 30 percent less, with savings coming from fewer services rather than lower prices. Cost sharing generally did not harm health, except for the poorest and sickest participants on a few conditions such as hypertension.[^s4]

A 2012 NBER reassessment by Aron-Dine, Einav and Finkelstein confirmed that spending responds to price but found the size of the effect less certain than the widely quoted elasticity of about -0.2 suggests.[^s5] Participants assigned to high cost sharing refused or dropped out far more often (completion was 88 percent under free care versus 63 percent under the 95 percent plan), and they also filed fewer claims, which complicates the comparison.[^s5] The authors also caution that summarizing a plan with deductibles and caps by a single price is ambiguous, so translating the experiment into one elasticity requires extra assumptions.[^s5] Arrow himself called the physician's role as the insurer's gatekeeper a far from perfect check on overuse.[^s1]

## In practice

Managers meet moral hazard in insurance design, compensation and contracting. Health plans pair deductibles with coinsurance; auto insurers pay only losses above a deductible; and boards use relative performance evaluation to reward executives for what they control rather than market-wide luck.[^s3][^s6] The RAND result that coinsurance cut spending without broadly harming health became a standard reference for cost-sharing plan design in later U.S. reform debates.[^s4]

## Connections

Moral hazard is a consequence of **information asymmetry** and a core problem of **contract theory**, the field Holmström helped found.[^s6] It is the hidden-action half of the **principal-agent problem**, and its residual losses are a component of **agency costs** in firms.[^s2] It **contrasts with adverse selection**, the hidden-characteristics problem.[^s3] It was **introduced in** economics by Arrow's 1963 medical-care paper and **influenced** the **informativeness principle**.[^s1][^s2] It is **exemplified by** the **RAND Health Insurance Experiment** and **applies to** **executive compensation**.[^s4][^s6] Business-format franchising depends on managing it on both sides of the contract, as that node's article explains, and **Bengt Holmström** is its leading theorist.[^s6]

## Sources

[^s1]: Kenneth J. Arrow, "Uncertainty and the Welfare Economics of Medical Care", American Economic Review 53(5), 1963, pp. 941–973. https://casbs.stanford.edu/sites/default/files/media/file/kenneth-arrow-medical-care.pdf (accessed 2026-11-13)
[^s2]: Bengt Holmström, "Moral Hazard and Observability", Bell Journal of Economics 10(1), 1979, pp. 74–91 (EconPapers record). https://econpapers.repec.org/RePEc:rje:bellje:v:10:y:1979:i:spring:p:74-91 (accessed 2026-11-13)
[^s3]: Steven A. Greenlaw, David Shapiro and Daniel MacDonald, *Principles of Economics 3e*, OpenStax, 2022, section 16.2. https://openstax.org/books/principles-economics-3e/pages/16-2-insurance-and-imperfect-information (accessed 2026-11-13)
[^s4]: RAND Corporation, "The Health Insurance Experiment: A Classic RAND Study Speaks to the Current Health Care Reform Debate", research brief RB-9174, 2006. https://www.rand.org/pubs/research_briefs/RB9174.html (accessed 2026-11-13)
[^s5]: Aviva Aron-Dine, Liran Einav and Amy Finkelstein, "The RAND Health Insurance Experiment, Three Decades Later", NBER Working Paper 18642, December 2012. https://www.nber.org/papers/w18642.pdf (accessed 2026-11-13)
[^s6]: Royal Swedish Academy of Sciences, "Popular information: The Prize in Economic Sciences 2016". https://nobelprize.org/prizes/economic-sciences/2016/popular-information (accessed 2026-11-13)
