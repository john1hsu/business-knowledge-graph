---
id: kt:fault-tree-analysis
type: Framework
title: "Fault Tree Analysis: Deductive Top-Down Modeling of How System Failures Occur"
aliases: [fault tree analysis, FTA, fault tree, fault tree method]
domain: consulting-and-problem-solving
summary: >-
  A deductive, top-down method that starts from one clearly defined undesired outcome (the top
  event) and decomposes it through AND/OR logic gates into the combinations of lower-level faults
  that could produce it; developed at Bell Labs in the early 1960s for the Minuteman missile and
  now used for reliability, safety and process-risk analysis well beyond engineering.
broader: [kt:root-cause-analysis, kt:structured-problem-solving]
related: [kt:issue-tree, kt:five-whys, kt:event-tree-analysis]
relations:
  - {predicate: createdBy, object: kt:bell-labs}
  - {predicate: contrastsWith, object: kt:ishikawa-diagram}
  - {predicate: alternativeTo, object: kt:failure-mode-and-effects-analysis}
  - {predicate: partOf, object: kt:probabilistic-risk-assessment}
  - {predicate: appliesTo, object: kt:patient-safety}
sources:
  - id: s1
    title: "Fault Tree Handbook (NUREG-0492)"
    publisher: U.S. Nuclear Regulatory Commission
    url: https://www.nrc.gov/reading-rm/doc-collections/nuregs/staff/sr0492/index
    type: government
    accessed: 2026-11-16
  - id: s2
    title: "Fault Tree Handbook with Aerospace Applications, Version 1.1"
    publisher: NASA Office of Safety and Mission Assurance
    url: https://extapps.ksc.nasa.gov/reliability/Documents/Fault_Tree_Handbook_with_Aerospace_Applications_August_2002.pdf
    type: government
    accessed: 2026-11-16
  - id: s3
    title: "Fault tree analysis: A survey of the state-of-the-art in modeling, analysis and tools"
    publisher: Computer Science Review (University of Twente repository)
    url: https://ris.utwente.nl/ws/files/6420246/1-s2.0-S1574013715000027-main.pdf
    type: peer-reviewed
    accessed: 2026-11-16
  - id: s4
    title: "An Introduction to Fault Tree Analysis"
    publisher: University of Nottingham, Resilience Engineering Research Group
    url: https://www.nottingham.ac.uk/research/groups/resilience-engineering/documents/nxgen/outputs/an-introduction-to-fault-tree-analysis.pdf
    type: academic
    accessed: 2026-11-16
  - id: s5
    title: "Three Kinds of Proactive Risk Analyses for Health Care"
    publisher: Joint Commission Journal on Quality and Patient Safety (record at Pacific Northwest National Laboratory)
    url: https://www.pnnl.gov/publications/three-kinds-proactive-risk-analyses-health-care
    type: peer-reviewed
    accessed: 2026-11-16
created: 2026-11-16
---

# Fault Tree Analysis

**Fault tree analysis (FTA)** is a deductive, failure-oriented method for working out how a
system can reach one specific undesired state. The analyst names that state as the *top event*
and then works backward, asking what combinations of lower-level faults could cause it, until the
tree bottoms out in basic events such as individual component failures or human errors.[^s2] The
result is a graphic model of the parallel and sequential combinations of faults behind the top
event, which can be read qualitatively or turned into probabilities.[^s2][^s3]

## Origin

The technique was devised at Bell Telephone Laboratories in the early 1960s, when Watson
built the logic-diagram approach to study the launch control system of the Minuteman
intercontinental ballistic missile.[^s4] Survey work likewise dates standard fault trees to Bell
Labs' ballistic-missile analysis in that decade.[^s3] NASA's handbook notes that FTA was in wide
use in U.S. aerospace and missile programs by the mid-1960s, and that the nuclear industry
embraced probabilistic risk assessment after the 1979 Three Mile Island accident.[^s2] The U.S.
Nuclear Regulatory Commission then published the *Fault Tree Handbook* (NUREG-0492) in January
1981, by W. E. Vesely, F. F. Goldberg, N. H. Roberts and D. F. Haasl, to codify the method; it grew
out of a course taught to more than 200 NRC staff and contractors from 1975 onward.[^s1] Vesely
had earlier extended the method to time-dependent quantification, known as kinetic tree
theory.[^s4]

## How it works

A fault tree is a directed acyclic graph of events joined by logic gates. An OR gate fires if
any input occurs; an AND gate fires only if all inputs occur; a k-of-N voting gate fires when at
least k inputs occur.[^s3] The key qualitative output is the set of **minimal cut sets**: the
smallest combinations of basic events that are jointly sufficient to cause the top event, found
by writing the tree as a Boolean expression and simplifying it.[^s4] A single-event cut set marks
a single point of failure; larger cut sets show where redundancy is already protecting the
system.[^s3]

For quantitative analysis, analysts assign probabilities to basic events. Assuming independence,
AND gates multiply input probabilities and OR gates combine them as one minus the product of the
non-failure probabilities; large trees rely on approximations such as the rare-event
approximation.[^s3][^s4] Importance measures such as Birnbaum and Fussell-Vesely rank which basic
events contribute most to top-event risk, which tells managers where an improvement dollar buys
the most reliability.[^s4]

NASA's handbook argues for modelling in failure space rather than success space: people agree
more easily on what counts as failure, and small failure probabilities make the arithmetic more
tractable.[^s2]

## Evidence and critiques

FTA is well established in nuclear power, aerospace, defense, rail, automotive and medical
devices, and survey research documents a large body of analysis algorithms and tools.[^s3] Its
limits are equally well documented. A fault tree models only the top event chosen and only the
faults the analyst judges realistic, so it is not a model of every way a system can fail.[^s2]
Each tree covers one top event, construction is slow and demands deep system knowledge, and there
is no rulebook that guarantees a correct tree.[^s4] Standard trees cannot express the order of
failures, spares or dependent events, which led to dynamic fault tree extensions; common-cause
analysis still leans heavily on expert judgment, and exact computation scales badly on large
trees.[^s3] NASA also cautions that FTA alone does not amount to a complete probabilistic risk
assessment.[^s2]

## In practice

Beyond engineering, FTA has been applied to service processes. A 2010 study by a hospital patient
safety coalition found that failure mode and effects analysis (FMEA) was hard to apply when
process detail was thin, and argued that fault and event trees add value because they explicitly
consider combinations of failures rather than one failure at a time.[^s5] The same cut-set logic can be
carried into an operations or consulting problem (an illustrative case, not a documented one):
with "order not delivered on time" as the top event, single-event cut sets show which breakdowns
cause misses on their own, while larger cut sets show which matter only in combination.[^s3]

## Connections

FTA is a formal, probabilistic branch of **root cause analysis** and a disciplined form of
**structured problem solving**.[^s2] Its top-down decomposition resembles an **issue tree**, but
its branches carry explicit Boolean logic and can be quantified.[^s4] It **contrasts with** the
**Ishikawa diagram**, which groups possible causes by category without AND/OR logic, and with
the single causal chain of the **five whys**.[^s3] It is an **alternative to** FMEA, which is
inductive and bottom-up and does not consider combinations of component faults, while FTA is
deductive and suited to a defined undesired event.[^s2] Fault trees are usually paired with
**event tree analysis** inside **probabilistic risk assessment**, and have been carried into
**patient safety** work in hospitals.[^s1][^s5]

## Sources

[^s1]: W. E. Vesely, F. F. Goldberg, N. H. Roberts and D. F. Haasl, *Fault Tree Handbook* (NUREG-0492), U.S. Nuclear Regulatory Commission, January 1981. https://www.nrc.gov/reading-rm/doc-collections/nuregs/staff/sr0492/index (accessed 2026-11-16)
[^s2]: W. Vesely et al., *Fault Tree Handbook with Aerospace Applications*, Version 1.1, NASA Office of Safety and Mission Assurance, August 2002. https://extapps.ksc.nasa.gov/reliability/Documents/Fault_Tree_Handbook_with_Aerospace_Applications_August_2002.pdf (accessed 2026-11-16)
[^s3]: Enno Ruijters and Mariëlle Stoelinga, "Fault tree analysis: A survey of the state-of-the-art in modeling, analysis and tools", *Computer Science Review* 15–16 (2015): 29–62. https://ris.utwente.nl/ws/files/6420246/1-s2.0-S1574013715000027-main.pdf (accessed 2026-11-16)
[^s4]: John Andrews and Sally Lunt, "An Introduction to Fault Tree Analysis", University of Nottingham Resilience Engineering Research Group. https://www.nottingham.ac.uk/research/groups/resilience-engineering/documents/nxgen/outputs/an-introduction-to-fault-tree-analysis.pdf (accessed 2026-11-16)
[^s5]: G. A. Coles et al., "Three Kinds of Proactive Risk Analyses for Health Care", *Joint Commission Journal on Quality and Patient Safety* 36(8) (2010): 365–375. https://www.pnnl.gov/publications/three-kinds-proactive-risk-analyses-health-care (accessed 2026-11-16)
