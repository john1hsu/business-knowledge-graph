---
id: kt:root-cause-analysis
type: Practice
title: "Root Cause Analysis: Tracing Problems to Their Underlying Causes"
aliases: [root cause analysis, RCA, root-cause analysis, root cause analysis and action, RCA2]
domain: consulting-and-problem-solving
summary: >-
  A family of structured methods for investigating a problem or adverse event so as to find the
  underlying system causes that produced it, rather than its symptoms or the person nearest to it,
  and to design corrective actions that stop it recurring.
broader: [kt:structured-problem-solving, kt:total-quality-management]
related: [kt:ishikawa-diagram, kt:five-whys, kt:issue-tree]
relations:
  - {predicate: hasPart, object: kt:barrier-analysis}
  - {predicate: contrastsWith, object: kt:failure-mode-and-effects-analysis}
  - {predicate: appliesTo, object: kt:patient-safety}
sources:
  - id: s1
    title: "What is Root Cause Analysis (RCA)?"
    publisher: American Society for Quality (ASQ)
    url: https://www.asq.org/quality-resources/root-cause-analysis
    type: organization
    accessed: 2026-11-13
  - id: s2
    title: "Root Cause Analysis (Patient Safety Primer)"
    publisher: Agency for Healthcare Research and Quality, PSNet
    url: https://psnet.ahrq.gov/primer/root-cause-analysis
    type: government
    accessed: 2026-11-13
  - id: s3
    title: "The problem with root cause analysis"
    publisher: BMJ Quality & Safety (author manuscript, University of Birmingham repository)
    url: https://research.birmingham.ac.uk/files/70608217/Peerally_et_al_The_problem_with_BMJ_Qual_Saf_2016.pdf
    type: peer-reviewed
    accessed: 2026-11-13
  - id: s4
    title: "DOE-NE-STD-1004-92: Root Cause Analysis Guidance Document"
    publisher: U.S. Department of Energy, Office of Environment, Health, Safety & Security
    url: https://www.energy.gov/ehss/articles/doe-ne-std-1004-92
    type: government
    accessed: 2026-11-13
  - id: s5
    title: "RCA2: Improving Root Cause Analyses and Actions to Prevent Harm"
    publisher: Institute for Healthcare Improvement
    url: https://IHI.org/resources/tools/rca2-improving-root-cause-analyses-and-actions-prevent-harm
    type: organization
    accessed: 2026-11-13
  - id: s6
    title: "Patient Safety Essentials Toolkit: Action Hierarchy Tool (part of RCA2)"
    publisher: Institute for Healthcare Improvement (hosted by the Minnesota Department of Health)
    url: https://health.state.mn.us/facilities/patientsafety/adverseevents/toolkit/docs/safetytoolkit_actionhierarchy.pdf
    type: organization
    accessed: 2026-11-13
created: 2026-11-13
---

# Root Cause Analysis

**Root cause analysis (RCA)** is an umbrella term for the approaches, tools and techniques an organization uses to discover why a problem happened. The American Society for Quality (ASQ) defines a root cause as the highest-level factor that sets off the chain of cause and effect behind a nonconformance, and stresses that it is something to remove permanently through process improvement rather than to patch.[^s1] In health care, the Agency for Healthcare Research and Quality (AHRQ) describes RCA as a structured way to analyse serious adverse events that deliberately looks past individual mistakes toward the system weaknesses that allowed them.[^s2]

## Origin

RCA grew out of accident investigation in high-hazard industries. AHRQ notes that it was first developed to analyse industrial accidents,[^s2] and Peerally and colleagues trace its adoption in medicine to methods borrowed from aviation and nuclear power, grounded in human-factors and safety science.[^s3] The U.S. Department of Energy codified one version in its *Root Cause Analysis Guidance Document* (DOE-NE-STD-1004-92), a guide to the analysis specified by DOE Order 5000.3A, which treats causal factors as signs of program-control deficiencies that should guide early corrective action.[^s4] In the quality movement, ASQ places RCA within total quality management, as a core element of continuous improvement.[^s1] The Joint Commission has required U.S. hospitals to perform RCAs on sentinel events such as wrong-site surgery since 1997.[^s2]

## How it works

Most protocols share a sequence: define the problem, gather evidence, reconstruct what happened, identify causes, and design and track fixes. In health care, investigators interview participants and review records to rebuild the event, then a multidisciplinary team separates *active* errors (what went wrong at the point of care) from *latent* errors (hidden conditions such as staffing, task design or management decisions) that explain why.[^s2] ASQ catalogues several analytic techniques: events-and-causal-factor analysis for major single events, built around a timeline; change analysis, which looks for shifts in people, equipment or information that coincide with a drop in performance; barrier analysis, which asks which preventive or detective controls failed; management oversight and risk tree analysis; and the Kepner-Tregoe method.[^s1]

ASQ favours a small team from the affected process, including someone with authority to implement fixes, meeting at least weekly over roughly two months, with time split evenly among defining the problem, brainstorming causes, analysing cause and effect, and designing a solution.[^s1] It warns that the chain of causation has no natural end, so a key skill is knowing when to stop drilling down, and that RCA produces nothing by itself unless it feeds a wider improvement effort.[^s1]

## Evidence and critiques

The most cited critique is Peerally, Carr, Waring and Dixon-Woods's 2017 paper in *BMJ Quality & Safety*, which argues that RCA is promising in principle but has not delivered benefits at the scale or quality needed.[^s3] They list eight problems, among them the misleading implication of a single cause, investigations run by untrained local teams against fixed deadlines (45 days in the U.S., 60 in the UK), reports becoming ends in themselves, a bias toward weak administrative fixes such as reminders and training, poor feedback to staff and patients, and analysis of single incidents that misses patterns across organizations.[^s3] In their example, a hospital answered a wrong-lens cataract implant with a protocol, training and a poster, and a wrong lens was implanted again a year later.[^s3]

AHRQ likewise reports that many RCAs fail to yield durable, system-level fixes, notes that harm usually needs several system flaws to line up, and cites a 2013 study in which Veterans Affairs facilities that performed more RCAs had lower adverse-event rates than those that performed fewer than four.[^s2]

## Reform: RCA²

In 2015 the National Patient Safety Foundation proposed renaming the practice "root cause analysis and action" (RCA²) to emphasise that the purpose is sustainable, systems-based improvement, not a report; the guidance is now hosted by the Institute for Healthcare Improvement.[^s5] A central RCA² tool is the action hierarchy, adapted from the VA National Center for Patient Safety, which ranks fixes by how little they depend on people remembering to do the right thing.[^s6] Stronger actions include forcing functions, physical redesign, standardized equipment and software safeguards; intermediate actions include checklists, double checks and simulation training; weaker actions are new policies and retraining, which the toolkit says are unlikely to sustain improvement on their own. Teams are urged to pair each root cause with at least one strong or intermediate action.[^s6]

## In practice

The same logic applies to a factory defect, a failed software release or a spike in customer churn: define the problem precisely, separate contributing factors from root causes, and judge success by whether the actions change the system.[^s1][^s6] Peerally and colleagues add that proactive methods such as failure modes and effects analysis should complement RCA, so that hazards are found before an incident rather than after.[^s3]

## Connections

RCA is a core technique of **structured problem solving** and an outgrowth of **total quality management**.[^s1] The **Ishikawa diagram** and the **five whys** are tools commonly used inside an RCA, and the **issue tree** is the consultant's analogous device for decomposing a problem into candidate causes.[^s1][^s3] **Barrier analysis** is one of its component methods.[^s1] It contrasts with **failure mode and effects analysis**, which looks forward at potential failures rather than back at actual ones,[^s3] and it is applied heavily in **patient safety**, where most research on its effectiveness has been done.[^s2]

## Sources

[^s1]: American Society for Quality, "What is Root Cause Analysis (RCA)?", ASQ Quality Resources. https://www.asq.org/quality-resources/root-cause-analysis (accessed 2026-11-13)
[^s2]: Agency for Healthcare Research and Quality, "Root Cause Analysis", PSNet Patient Safety Primer. https://psnet.ahrq.gov/primer/root-cause-analysis (accessed 2026-11-13)
[^s3]: M. Farhad Peerally, Sue Carr, Justin Waring and Mary Dixon-Woods, "The problem with root cause analysis", *BMJ Quality & Safety* 26(5), 2017, pp. 417–422, doi:10.1136/bmjqs-2016-005511. https://research.birmingham.ac.uk/files/70608217/Peerally_et_al_The_problem_with_BMJ_Qual_Saf_2016.pdf (accessed 2026-11-13)
[^s4]: U.S. Department of Energy, "DOE-NE-STD-1004-92: Root Cause Analysis Guidance Document", Office of Environment, Health, Safety & Security. https://www.energy.gov/ehss/articles/doe-ne-std-1004-92 (accessed 2026-11-13)
[^s5]: National Patient Safety Foundation, *RCA2: Improving Root Cause Analyses and Actions to Prevent Harm*, Boston, 2015; hosted by the Institute for Healthcare Improvement. https://IHI.org/resources/tools/rca2-improving-root-cause-analyses-and-actions-prevent-harm (accessed 2026-11-13)
[^s6]: Institute for Healthcare Improvement, *Patient Safety Essentials Toolkit: Action Hierarchy Tool (part of RCA2)*, 2019, hosted by the Minnesota Department of Health. https://health.state.mn.us/facilities/patientsafety/adverseevents/toolkit/docs/safetytoolkit_actionhierarchy.pdf (accessed 2026-11-13)
