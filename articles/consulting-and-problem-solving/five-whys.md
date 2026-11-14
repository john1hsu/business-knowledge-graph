---
id: kt:five-whys
type: Practice
title: "Five Whys: Iterative Why-Questioning to Trace a Problem to Its Root Cause"
aliases: [5 whys, five whys, 5 whys analysis, why-why analysis, five whys technique]
domain: consulting-and-problem-solving
summary: >-
  A question-asking technique from the Toyota Production System in which a team asks "why?"
  repeatedly, roughly five times, to move from a problem's visible symptom to an underlying cause
  that can be removed; widely taught in lean, quality improvement and startups, and criticized for
  following a single causal chain to a single root cause.
broader: [kt:root-cause-analysis, kt:structured-problem-solving]
related: [kt:ishikawa-diagram, kt:pdca-cycle, kt:kaizen]
relations:
  - {predicate: createdBy, object: kt:taiichi-ohno}
  - {predicate: partOf, object: kt:toyota-production-system}
  - {predicate: influenced, object: kt:lean-startup}
  - {predicate: appliesTo, object: kt:patient-safety}
sources:
  - id: s1
    title: "5 Whys (Lean Lexicon)"
    publisher: Lean Enterprise Institute
    url: https://www.lean.org/lexicon-terms/5-whys/
    type: organization
    accessed: 2026-11-14
  - id: s2
    title: "The Five Whys Technique"
    publisher: Asian Development Bank, Knowledge Solutions series
    url: https://core.ac.uk/download/5132831.pdf
    type: intergovernmental
    accessed: 2026-11-14
  - id: s3
    title: "The problem with '5 whys'"
    publisher: BMJ Quality & Safety
    url: https://qualitysafety.bmj.com/content/qhc/early/2016/09/02/bmjqs-2016-005849.full.pdf
    type: peer-reviewed
    accessed: 2026-11-14
  - id: s4
    title: "5 Whys: Finding the Root Cause"
    publisher: Institute for Healthcare Improvement
    url: https://ihi.org/fr/node/22961
    type: organization
    accessed: 2026-11-14
  - id: s5
    title: "The Five Whys (talk transcript)"
    publisher: Stanford eCorner, Stanford Technology Ventures Program
    url: https://stvp.stanford.edu/wp-content/uploads/sites/3/2024/09/the-five-whys-transcript.pdf
    type: primary
    accessed: 2026-11-14
created: 2026-11-14
---

# Five Whys

The **five whys** (often written **5 Whys**) is a problem-solving practice in which a team responds to a problem by asking why it occurred, then asking why again of each answer, so as to get past surface symptoms to a root cause that can be eliminated.[^s1] The Lean Enterprise Institute (LEI) stresses that five is a guideline rather than a rule: the point is to keep going until the cause reached is one the organization can actually remove.[^s1] The Institute for Healthcare Improvement (IHI) frames it the same way, telling users to treat each answer as a possible symptom rather than a stopping point.[^s4]

## Origin

The technique comes from Toyota. LEI's lexicon takes its canonical example from Taiichi Ohno's 1988 book on the Toyota Production System,[^s1] and IHI attributes the method to Ohno as the father of that system.[^s4] Olivier Serrat's guide for the Asian Development Bank instead credits Sakichi Toyoda, founder of the Toyota group's loom business, so attribution varies between Toyoda (as originator) and Ohno (as the manager who made it a core TPS habit).[^s2] Alan Card notes that Ohno presented it as central to the Toyota Production System and that it spread through lean and Six Sigma programmes into health care.[^s3]

## How it works

Ohno's example, as reproduced by LEI, begins with a stopped machine. It stopped because an overload blew a fuse; the overload came from an under-lubricated bearing; the bearing was dry because the lubrication pump was not delivering enough; the pump was failing because its shaft was worn; and the shaft was worn because no strainer had been fitted, letting metal scrap in.[^s1] Replacing the fuse or the pump would have let the failure recur; fitting a strainer removes the cause.[^s1]

Serrat recommends running the exercise as a team: agree a precise problem statement, record the answer to each why, follow every plausible branch rather than only one, stop when further questions yield nothing useful, then confirm the most likely systemic cause with others before designing corrective action.[^s2] He also advises testing each answer against evidence before asking the next why, because purely deductive chains drift easily.[^s2] LEI places the method within a wider routine of problem definition, countermeasures and follow-up, and links it to kaizen and the PDCA cycle.[^s1]

## In startups

Eric Ries, in a 2009 Stanford talk, adapted the technique for software startups. He argued that behind most apparently technical failures sits a human or managerial problem, as when a bad code release traces to an engineer who was never trained and a manager who does not value training.[^s5] His addition was **proportional investment**: instead of either ignoring the incident or launching a months-long prevention programme, the team makes a small fix at each of the five levels, and adds a further increment every time the problem recurs.[^s5]

## Evidence and critiques

The sharpest critique is Card's 2016 paper in *BMJ Quality & Safety*. He argues that the method forces investigators down a single causal pathway, assumes a single root cause, and implies that the most distal cause is the best place to intervene, when a proximate control such as a forcing function may prevent recurrence more reliably.[^s3] Mapping a wrong-patient medication error as a full causal tree, he estimates that a typical five-whys chain would capture only a small fraction of the available improvement opportunities, and he calls the technique simplistic rather than simple.[^s3] He recommends abandoning it as a root-cause tool in patient safety while keeping it as a teaching device.[^s3] Serrat lists similar limits: teams stop at symptoms, cannot see beyond their own knowledge, lack facilitation, and different teams reach different causes for the same problem.[^s2] IHI likewise warns that a problem can have several root causes and that people who see different parts of a system will answer differently, and points users to its fuller RCA² approach.[^s4]

## Connections

The five whys is one of the simplest techniques of **root-cause analysis** and a basic move of **structured problem solving**.[^s1][^s4] It was formalized within the **Toyota Production System** and is credited to **Taiichi Ohno**,[^s1][^s4] and LEI ties it to **kaizen** and the **PDCA cycle**.[^s1] It is often paired with the **Ishikawa diagram**, which supplies the breadth of candidate causes that a single why-chain lacks; Card lists fishbone analysis among the more systems-oriented alternatives.[^s3] Ries carried it into the **lean startup** method,[^s5] and its use in **patient safety** is where its critics have tested it most.[^s3][^s4]

## Sources

[^s1]: Lean Enterprise Institute, "5 Whys", Lean Lexicon (example from Taiichi Ohno, *Toyota Production System*, 1988, p. 17). https://www.lean.org/lexicon-terms/5-whys/ (accessed 2026-11-14)
[^s2]: Olivier Serrat, "The Five Whys Technique", *Knowledge Solutions*, Asian Development Bank, Manila, February 2009. https://core.ac.uk/download/5132831.pdf (accessed 2026-11-14)
[^s3]: Alan J. Card, "The problem with '5 whys'", *BMJ Quality & Safety*, published online 2 September 2016, doi:10.1136/bmjqs-2016-005849. https://qualitysafety.bmj.com/content/qhc/early/2016/09/02/bmjqs-2016-005849.full.pdf (accessed 2026-11-14)
[^s4]: Institute for Healthcare Improvement, "5 Whys: Finding the Root Cause", IHI tools. https://ihi.org/fr/node/22961 (accessed 2026-11-14)
[^s5]: Eric Ries, "The Five Whys", Stanford eCorner talk transcript, 30 September 2009, Stanford Technology Ventures Program. https://stvp.stanford.edu/wp-content/uploads/sites/3/2024/09/the-five-whys-transcript.pdf (accessed 2026-11-14)
