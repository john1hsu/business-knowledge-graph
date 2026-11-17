---
id: kt:premortem
type: Practice
title: "Premortem: Prospective Hindsight for Anticipating Project Failure"
aliases: [pre-mortem, project premortem, premortem technique, pre-mortem analysis]
domain: consulting-and-problem-solving
summary: >-
  A short team exercise, popularized by psychologist Gary Klein in a 2007 Harvard Business Review
  article, in which participants assume a plan has already failed and independently write down why,
  so that risks, hidden doubts and overconfidence surface before the project starts.
broader: [kt:structured-problem-solving, kt:group-decision-making]
related: [kt:devils-advocacy, kt:nominal-group-technique, kt:fault-tree-analysis, kt:psychological-safety]
relations:
  - {predicate: createdBy, object: kt:gary-klein}
  - {predicate: introducedIn, object: kt:performing-a-project-premortem-2007}
  - {predicate: influencedBy, object: kt:prospective-hindsight}
  - {predicate: mitigates, object: kt:overconfidence-bias}
  - {predicate: mitigates, object: kt:groupthink}
  - {predicate: contrastsWith, object: kt:root-cause-analysis}
sources:
  - id: s1
    title: "Performing a Project Premortem (Harvard Business Review, September 2007; reprint)"
    publisher: Harvard Business Review (reprint hosted by DuraSpace wiki)
    url: https://wiki.duraspace.org/download/attachments/104563925/ProjectPremortem.pdf?api=v2
    type: primary
    accessed: 2026-11-17
  - id: s2
    title: "Strategic decisions: When can you trust your gut? (interview with Daniel Kahneman and Gary Klein)"
    publisher: McKinsey Quarterly
    url: https://www.mckinsey.com/capabilities/strategy-and-corporate-finance/our-insights/strategic-decisions-when-can-you-trust-your-gut
    type: consultancy
    accessed: 2026-11-17
  - id: s3
    title: "Identifying and Addressing Risks in the Early Design of a Sociotechnical System through Premortem (Bettin, Steelman, Wallace, Pontious & Veinott, HFES 2022)"
    publisher: Proceedings of the Human Factors and Ergonomics Society Annual Meeting (via NSF Public Access Repository)
    url: https://par.nsf.gov/servlets/purl/10435109
    type: peer-reviewed
    accessed: 2026-11-17
  - id: s4
    title: "Self-serving attribution bias in a popular debiasing strategy (Gandhi, Duke & Schweitzer, SJDM poster, 2021)"
    publisher: UBC Sauder School of Business Decision Lab
    url: https://dlab.sauder.ubc.ca/sjdm/presentations/2021-Poster-Gandhi-Linnea-debiasing-premortem-selfserving~.pdf
    type: academic
    accessed: 2026-11-17
created: 2026-11-17
---

# Premortem: Prospective Hindsight for Anticipating Project Failure

A **premortem** is a planning exercise in which a team, before committing to a project, imagines that the project has already failed badly and then explains why. Gary Klein, a psychologist known for research on naturalistic decision making, described the technique in a September 2007 *Harvard Business Review* article, framing it as the hypothetical mirror image of a postmortem: instead of diagnosing what killed a project after the fact, the team diagnoses it while there is still time to change the plan.[^s1] In a 2010 *McKinsey Quarterly* conversation, Daniel Kahneman credited Klein with the idea and called it cheap to run with a high payoff.[^s2]

## Origin and rationale

Klein grounded the method in research on **prospective hindsight**. He cited a 1989 study by Deborah Mitchell (Wharton), J. Edward Russo (Cornell) and Nancy Pennington (University of Colorado), reporting that imagining an event has already happened raises people's ability to correctly identify reasons for future outcomes by about 30%.[^s1] The intuition is that treating failure as a certainty, rather than a possibility, shifts people from defending a plan to explaining an outcome, which makes it easier to generate concrete causes.[^s1] Later human-factors researchers likewise describe the premortem as using prospective hindsight to reduce uncertainty and aid brainstorming.[^s3]

The second rationale is social. Klein argued that once a plan has momentum, team members who harbor doubts tend to stay quiet, and the premortem makes it safe, even rewarding, for knowledgeable dissenters to speak.[^s1] In the McKinsey interview he described the exercise as turning criticism into a competition: people demonstrate their intelligence by finding plausible ways the plan could break rather than by endorsing it.[^s2]

## How it works

Klein's version is brief and runs at the point where a plan has been briefed but not yet launched:[^s1]

1. The leader briefs the team on the plan, then announces that it has failed spectacularly.[^s1]
2. Each person silently writes down every reason they can think of for the failure, including worries they would normally keep to themselves.[^s1]
3. Going around the room, starting with the project manager, each participant reads one reason at a time until all are recorded.[^s1]
4. The project manager reviews the list afterward and looks for ways to strengthen the plan.[^s1]

The silent, independent writing step resembles the nominal group technique and limits anchoring on the most senior voice. Kahneman and Klein described the writing as taking roughly two minutes per person.[^s2] Practitioners often extend the format: a 2022 study team at Michigan Technological University added round-robin sharing with shows of hands, grouping of failures into problem categories, and a second silent round to generate solutions.[^s3]

## Evidence and critiques

Claims for the premortem rest on a mix of experiments and case reports. Klein listed benefits including early detection of problems, reduced overconfidence among people heavily invested in a project, and sharper attention to warning signs once work begins.[^s1] Kahneman expected it would seldom kill a plan outright but would often produce useful adjustments.[^s2] In the 2022 human-factors case study, two back-to-back premortems on a library tutoring-device system surfaced 17 and 13 distinct failure modes, and 15 of the proposed solutions were new to the team; the authors also reported better shared understanding across disciplines.[^s3]

The same authors cautioned that a premortem guarantees no completeness and, in high-hazard settings, should complement rather than replace systematic methods, possibly paired with predefined risk taxonomies; their evidence came from one six-person team without a control group.[^s3] A 2021 set of pre-registered experiments by Linnea Gandhi, Annie Duke and Maurice Schweitzer (total N = 2,345) found that the premortem did reduce overconfidence relative to imagining success, but it also increased self-serving attribution: participants more often blamed potential failure on factors outside their control, such as luck, and were no more willing to take corrective action.[^s4] That finding suggests facilitators should push teams toward controllable causes and concrete mitigations rather than a list of external misfortunes.[^s4]

## In practice

Klein's article recounts several uses. At a Fortune 50 company, a premortem on a billion-dollar sustainability initiative surfaced the risk that support would fade once the sponsoring CEO retired, and the risk that a government policy change would weaken the business case.[^s1] In a military software project, a quiet team member warned that an algorithm would run too slowly on field laptops, which led developers to adopt a shortcut they had not previously shared.[^s1] Consultants and project managers typically schedule a premortem at kickoff or just before a major go/no-go decision, when changes are still cheap.[^s1]

## Connections

The premortem is a tool of **structured problem solving** and **group decision making**, applied prospectively to risk rather than retrospectively to an incident.[^s1] It contrasts with **root cause analysis**, which reconstructs why a failure already occurred, and it complements **fault tree analysis**, which models failure logic deductively where the premortem relies on the team's open-ended imagination.[^s3] Like the **devil's advocate method** it institutionalizes dissent to counter **groupthink**, and it depends on a degree of **psychological safety** for people to voice concerns.[^s2] Its silent-writing step borrows from the **nominal group technique**, and its main debiasing target is **overconfidence bias**, though the evidence on side effects is mixed.[^s4] The method was created by **Gary Klein**, introduced in his 2007 HBR article, and builds on research into **prospective hindsight**.[^s1]

## Sources

[^s1]: Gary Klein, "Performing a Project Premortem", Harvard Business Review, September 2007 (reprint). https://wiki.duraspace.org/download/attachments/104563925/ProjectPremortem.pdf?api=v2 (accessed 2026-11-17)
[^s2]: Olivier Sibony and Dan Lovallo (interviewers), "Strategic decisions: When can you trust your gut?", McKinsey Quarterly, March 2010. https://www.mckinsey.com/capabilities/strategy-and-corporate-finance/our-insights/strategic-decisions-when-can-you-trust-your-gut (accessed 2026-11-17)
[^s3]: Briana Bettin, Kelly S. Steelman, Charles Wallace, Dana Pontious and Elizabeth S. Veinott, "Identifying and Addressing Risks in the Early Design of a Sociotechnical System through Premortem", Proceedings of the HFES 66th Annual Meeting, 2022, pp. 1514–1518, doi:10.1177/1071181322661307. https://par.nsf.gov/servlets/purl/10435109 (accessed 2026-11-17)
[^s4]: Linnea Gandhi, Annie Duke and Maurice Schweitzer, "Self-serving attribution bias in a popular debiasing strategy", Society for Judgment and Decision Making poster, 2021. https://dlab.sauder.ubc.ca/sjdm/presentations/2021-Poster-Gandhi-Linnea-debiasing-premortem-selfserving~.pdf (accessed 2026-11-17)
