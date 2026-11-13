---
id: kt:delphi-method
type: Practice
title: "Delphi Method: Iterative Anonymous Expert Consensus"
aliases: [Delphi technique, Delphi process, Delphi survey, expert Delphi]
domain: consulting-and-problem-solving
summary: >-
  A structured way of pooling expert judgment in which panellists answer questionnaires
  anonymously over several rounds, see a statistical summary of the group's answers between
  rounds, and may revise their views, so a forecast or consensus emerges without face-to-face debate.
broader: [kt:group-decision-making, kt:forecasting]
related: [kt:scenario-planning, kt:structured-problem-solving, kt:devils-advocacy]
relations:
  - {predicate: createdBy, object: kt:norman-dalkey}
  - {predicate: createdBy, object: kt:olaf-helmer}
  - {predicate: introducedIn, object: kt:an-experimental-application-of-the-delphi-method-to-the-use-of-experts-1963}
  - {predicate: alternativeTo, object: kt:nominal-group-technique}
  - {predicate: mitigates, object: kt:groupthink}
sources:
  - id: s1
    title: "An Experimental Application of the DELPHI Method to the Use of Experts (Management Science 9(3):458-467, 1963; DOI 10.1287/mnsc.9.3.458)"
    publisher: IDEAS/RePEc record of INFORMS article
    url: https://ideas.repec.org/a/inm/ormnsc/v9y1963i3p458-467.html
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s2
    title: "Report on a Long-Range Forecasting Study (RAND Paper P-2982)"
    publisher: The RAND Corporation (via Defense Technical Information Center)
    url: https://apps.dtic.mil/sti/pdfs/AD0607777.pdf
    type: primary
    accessed: 2026-11-13
  - id: s3
    title: "The Delphi technique as a forecasting tool: Issues and analysis (International Journal of Forecasting 15(4):353-375, 1999)"
    publisher: IAOR record of Elsevier article
    url: https://iaorifors.com/paper/29874
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s4
    title: "Delphi Assessment: Expert Opinion, Forecasting, and Group Process (RAND Report R-1283-PR)"
    publisher: The RAND Corporation
    url: https://www.rand.org/pubs/reports/R1283.html
    type: academic
    accessed: 2026-11-13
  - id: s5
    title: "Delphi Technique in Health Sciences: A Map"
    publisher: Frontiers in Public Health
    url: https://www.frontiersin.org/article/10.3389/fpubh.2020.00457
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s6
    title: "Consensus development for healthcare professionals"
    publisher: Internal and Emergency Medicine (via PubMed Central)
    url: https://pmc.ncbi.nlm.nih.gov/articles/PMC4405502
    type: peer-reviewed
    accessed: 2026-11-13
created: 2026-11-13
---

# Delphi Method

The **Delphi method** is a technique for turning the scattered judgments of experts into a single, defensible estimate when hard data are missing. Instead of convening a meeting, a facilitator sends panellists a series of questionnaires, summarises the group's answers after each round, and returns that summary so members can reconsider. It was developed at the RAND Corporation in the 1950s and is described as the first formal approach to building expert consensus guidance.[^s6] Norman Dalkey and Olaf Helmer published an account of an experiment with it in *Management Science* in 1963, describing the goal as obtaining the most reliable opinion consensus of a group of experts through questionnaires interspersed with controlled opinion feedback.[^s1]

## How it works

A classical Delphi rests on four features: participants stay anonymous to one another; they answer a standardised questionnaire that may be adjusted between rounds; the group answer is computed statistically rather than negotiated; and the summary is fed back so experts can revise in one or more further rounds.[^s5] Most studies run two or three rounds, although reviews in medicine have found anywhere from none to 14.[^s5]

RAND's 1964 long-range forecasting study, led by T. J. Gordon and Olaf Helmer, shows the mechanics. Of roughly 150 experts approached, 82 answered at least one questionnaire, split across six panels on scientific breakthroughs, population control, automation, space progress, war prevention and weapon systems. Each panel completed four questionnaires about two months apart. Answers were reported as a median date with quartiles showing the spread, and respondents outside the majority were asked to explain their reasoning, which was then shared with the panel.[^s2] The authors argued the design spares experts the persuasiveness of oratory and the bandwagon effect of prominent authority, leaving only a milder anonymous pressure from seeing the group's range of views.[^s2]

Many variants now exist: real-time Delphi with online feedback, policy Delphi that maps disagreement rather than forcing agreement, argumentative Delphi that stresses written justifications, and group Delphi that ends with a workshop to discuss outliers.[^s5]

## Evidence and critiques

The method drew criticism early. In a 1974 RAND report, Harold Sackman judged conventional Delphi against social-science standards for test design, sampling and use of experts, concluded it was unreliable and scientifically unvalidated, and recommended replacing it with more rigorous questionnaire and experimental methods.[^s4]

Later reviews were more favourable but qualified. Gene Rowe and George Wright's 1999 review in the *International Journal of Forecasting* found that Delphi groups beat simple statistical averages of individuals in 12 comparisons, lost 2 and tied 2, and beat unstructured interacting groups in 5, lost 1 and tied 2. However, they found no consistent advantage over other structured group methods, and noted that laboratory versions often departed from the original design and failed to control for panellist expertise or the type of feedback.[^s3]

A 2020 map of 12 systematic reviews covering 883 Delphi studies, mostly in health sciences, listed recurring weaknesses: no agreed quality criteria, small panels, inconsistent definitions of consensus (one review counted 11 statistical definitions, with 60% agreement or more the most common cut-off), and a risk that consensus-seeking reproduces dominant thinking while dissenters, sometimes up to 40% of a panel, go unexamined.[^s5] Others note that the absence of discussion means disagreements are not explained, which has pushed many groups towards modified designs that add structured interaction.[^s6]

## In practice

Businesses and consultants use Delphi when a decision depends on judgments that cannot be measured directly: long-range technology and market forecasts, inputs to scenario planning, risk registers, or priority lists that need buy-in from geographically dispersed specialists. Its practical strengths are that experts need not meet, senior voices carry no extra weight, and the output comes with a visible measure of spread. Its practical costs are time, since each round takes weeks, and dropout between rounds; in the RAND study the four rounds stretched over many months.[^s2][^s5]

## Connections

Delphi is a form of **group decision-making** and a judgmental **forecasting** method.[^s1][^s5] It was devised by **Norman Dalkey** and **Olaf Helmer** at RAND and introduced to the wider literature in their **1963 *Management Science* article**.[^s1][^s6] It is an **alternative to the nominal group technique**, which keeps silent idea generation and private voting but brings participants into one room; the two are often compared directly.[^s3][^s6] By using anonymity and statistical aggregation instead of open debate, it aims to **mitigate groupthink** and deference to authority.[^s2] It frequently supplies expert inputs for **scenario planning** and, like **devil's advocacy**, deliberately surfaces minority reasoning, though by written feedback rather than assigned dissent.[^s2][^s5] As a repeatable, documented procedure it belongs to the toolkit of **structured problem solving**.[^s5]

## Sources
[^s1]: Norman Dalkey and Olaf Helmer, "An Experimental Application of the DELPHI Method to the Use of Experts", *Management Science* 9(3), 1963 (IDEAS/RePEc record). https://ideas.repec.org/a/inm/ormnsc/v9y1963i3p458-467.html (accessed 2026-11-13)
[^s2]: T. J. Gordon and Olaf Helmer, "Report on a Long-Range Forecasting Study", RAND Paper P-2982, September 1964. https://apps.dtic.mil/sti/pdfs/AD0607777.pdf (accessed 2026-11-13)
[^s3]: Gene Rowe and George Wright, "The Delphi technique as a forecasting tool: Issues and analysis", *International Journal of Forecasting* 15(4), 1999 (IAOR record). https://iaorifors.com/paper/29874 (accessed 2026-11-13)
[^s4]: Harold Sackman, *Delphi Assessment: Expert Opinion, Forecasting, and Group Process*, RAND Report R-1283-PR, 1974. https://www.rand.org/pubs/reports/R1283.html (accessed 2026-11-13)
[^s5]: Marlen Niederberger and Julia Spranger, "Delphi Technique in Health Sciences: A Map", *Frontiers in Public Health* 8, 2020. https://www.frontiersin.org/article/10.3389/fpubh.2020.00457 (accessed 2026-11-13)
[^s6]: Bory Kea and Benjamin C. Sun, "Consensus development for healthcare professionals", *Internal and Emergency Medicine* 10(3), 2014 (PubMed Central). https://pmc.ncbi.nlm.nih.gov/articles/PMC4405502 (accessed 2026-11-13)
