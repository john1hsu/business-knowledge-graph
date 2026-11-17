---
id: kt:six-sigma
type: Practice
title: "Six Sigma: Motorola's DMAIC Method for Reducing Process Variation and Defects"
aliases: [Six Sigma, 6σ, DMAIC]
domain: operations-and-supply-chain
summary: >-
  A project-based process-improvement method, developed at Motorola in the 1980s and popularized by
  General Electric, that uses statistical tools, a structured Define-Measure-Analyze-Improve-Control cycle
  and a hierarchy of trained specialists ("belts") to reduce variation and defects in processes.
broader: [kt:operations-management, kt:total-quality-management]
related: [kt:lean-manufacturing, kt:malcolm-baldrige-national-quality-award, kt:root-cause-analysis, kt:ishikawa-diagram, kt:organizational-ambidexterity]
relations:
  - {predicate: createdBy, object: kt:motorola}
  - {predicate: dependsOn, object: kt:statistical-process-control}
  - {predicate: influencedBy, object: kt:w-edwards-deming}
  - {predicate: influencedBy, object: kt:joseph-juran}
  - {predicate: precededBy, object: kt:pdca-cycle}
  - {predicate: exemplifiedBy, object: kt:general-electric}
sources:
  - id: s1
    title: "Six Sigma: Definition and underlying theory"
    publisher: Journal of Operations Management 26(4), 536-554 (Schroeder, Linderman, Liedtke & Choo, 2008)
    url: https://pure.psu.edu/en/publications/six-sigma-definition-and-underlying-theory/
    type: peer-reviewed
    accessed: 2026-11-17
  - id: s2
    title: "1988 Malcolm Baldrige National Quality Award Recipient: Motorola Inc."
    publisher: National Institute of Standards and Technology (NIST)
    url: https://Www.Nist.Gov/system/files/documents/2017/10/11/1988_Motorola_Inc.pdf
    type: government
    accessed: 2026-11-17
  - id: s3
    title: "The Contributions of Six Sigma to the Development of Statistical Thinking in the Workplace"
    publisher: ICOTS9 invited paper, Arizona State University (Douglas C. Montgomery, 2014)
    url: https://icots.info/9/proceedings/pdfs/ICOTS9_5D2_MONTGOMERY.pdf
    type: academic
    accessed: 2026-11-17
  - id: s4
    title: "DMAIC"
    publisher: American Society for Quality (ASQ)
    url: https://asq.org/quality-resources/dmaic
    type: organization
    accessed: 2026-11-17
  - id: s5
    title: "TQM, ISO 9000, Six Sigma: Do Process Management Programs Discourage Innovation?"
    publisher: Knowledge at Wharton (2005)
    url: https://knowledge.wharton.upenn.edu/article/tqm-iso-9000-six-sigma-do-process-management-programs-discourage-innovation/
    type: academic
    accessed: 2026-11-17
  - id: s6
    title: "Environmental Professional's Guide to Lean and Six Sigma: Executive Summary"
    publisher: U.S. Environmental Protection Agency
    url: https://19january2025snapshot.epa.gov/sustainability/environmental-professionals-guide-lean-and-six-sigma-executive-summary
    type: government
    accessed: 2026-11-17
created: 2026-11-17
---

# Six Sigma

**Six Sigma** is a structured approach to process improvement that uses statistical methods to cut variation in a process and, with it, the defects that variation produces. The U.S. Environmental Protection Agency summarizes it as a method and toolset, developed by Motorola and popularized by General Electric, whose central aim is reducing variation to improve quality.[^s6] Its name comes from the statistical standard deviation (sigma): Motorola framed the goal as a process so tightly controlled that it produces no more than 3.4 defects per million, a target it applied to customer services as well as manufactured products.[^s2]

## Origin

Motorola developed Six Sigma in the late 1980s. Its products contained very large numbers of components, so even small per-part defect rates compounded into unacceptable failure rates for finished goods, and very low defect levels became critical.[^s3] The method grew out of a broader quality drive: in 1981 the company set itself the goal of a tenfold improvement in the quality of its products and services. When Motorola became one of the first recipients of the Malcolm Baldrige National Quality Award in 1988, NIST's award profile described Six Sigma as its statistical yardstick of variation and noted a workforce of about 99,000 people across 53 major facilities.[^s2] Six Sigma spread widely in the mid-1990s, chiefly through General Electric's companywide adoption.[^s5][^s6]

## How it works

Six Sigma work is organized as discrete improvement projects run through the **DMAIC** cycle:[^s4][^s3]

- **Define** the problem, goals, customers and their requirements in a project charter, and select a team.[^s4]
- **Measure** the current process, validate the measurement system and establish a data-based baseline.[^s4]
- **Analyze** the data to find the critical inputs that drive variation and defects, i.e. the root causes.[^s4]
- **Improve** the process by testing solutions, often with design of experiments, and estimating capability and financial benefit.[^s4]
- **Control** the gains with mistake-proofing, ongoing measurement, reaction plans and standard procedures.[^s4]

Projects are led by specially trained staff ranked as green belts, black belts and master black belts; the project-by-project structure adapts Joseph Juran's philosophy, and DMAIC itself descends from the Shewhart improvement cycle that W. Edwards Deming championed.[^s3] The "3.4 per million" figure comes from a stylized statistical model in which the nearest specification limit sits six standard deviations from the process mean. Montgomery, a leading industrial statistician, calls that model probably wrong but useful, because it focuses attention on reducing variability.[^s3]

## Evidence and critiques

For years Six Sigma attracted far more practitioner enthusiasm than academic scrutiny. Schroeder, Linderman, Liedtke and Choo (2008) used grounded theory to give it a formal definition and theory. They concluded that its statistical tools closely resemble earlier quality-management methods, but its organizational structure is new: a dedicated, parallel hierarchy of specialists gives firms tighter control over improvement work and pulls together people from different functions.[^s1] That structure, rather than the statistics, is what they see as its advantage over predecessors such as total quality management, along with new challenges for managers.[^s1]

Critics raise two main objections. First, followers of Deming objected to presenting 3.4 defects per million as a numerical goal, because target-setting of that kind conflicts with one of Deming's 14 points.[^s3] Second, and more consequential for strategy, Mary Benner and Michael Tushman found that process-management programs can crowd out exploratory innovation. Studying patents in the photography and paint industries from 1980 to 1999, they found that greater process-management activity was associated with fewer patents built on knowledge new to the firm, and more incremental patents building on existing knowledge.[^s5] They recommended an ambidextrous design: apply process discipline where work is routine and measurable, and deliberately shield exploratory units from it.[^s5]

## In practice

The method's institutional footprint is large. Universities now train belts formally: Arizona State University, for example, offers black-belt preparation built on graduate courses in statistical quality control, regression and design of experiments, plus an applied capstone project.[^s3] Government has engaged with it too: the EPA wrote a guide for environmental, health and safety managers and agency staff on working with Lean and Six Sigma programs, recommending that environmental considerations be built into these competitiveness-driven methods rather than replacing their core drivers.[^s6] The guide also draws the usual division of labor between the two approaches that are often deployed together: lean, derived from the Toyota Production System, removes non-value-added activity ("waste"), while Six Sigma reduces variation.[^s6]

## Connections

Six Sigma is a specialization within **operations management** and a descendant of **total quality management**, sharing TQM's statistical foundations but adding a project-and-belt structure.[^s1] It was **created by Motorola**, whose 1988 **Malcolm Baldrige National Quality Award** made it visible, and it is **exemplified by General Electric**, which popularized it.[^s2][^s6] It **depends on statistical process control** and is **influenced by Deming and Juran**, with DMAIC **preceded by** the Shewhart/PDCA cycle.[^s3] Its Analyze phase overlaps **root cause analysis** and tools such as the **Ishikawa diagram**.[^s4] It is frequently paired with **lean manufacturing**, and the Benner-Tushman critique links it to **organizational ambidexterity**: the need to balance exploitation of existing processes with exploration of new ones.[^s5]

## Sources
[^s1]: Roger G. Schroeder, Kevin Linderman, Charles Liedtke and Adrian S. Choo, "Six Sigma: Definition and underlying theory", Journal of Operations Management 26(4), 2008, 536-554, doi:10.1016/j.jom.2007.06.007. https://pure.psu.edu/en/publications/six-sigma-definition-and-underlying-theory/ (accessed 2026-11-17)
[^s2]: National Institute of Standards and Technology, "1988 Malcolm Baldrige National Quality Award Recipient: Motorola Inc." https://Www.Nist.Gov/system/files/documents/2017/10/11/1988_Motorola_Inc.pdf (accessed 2026-11-17)
[^s3]: Douglas C. Montgomery, "The Contributions of Six Sigma to the Development of Statistical Thinking in the Workplace", ICOTS9, 2014. https://icots.info/9/proceedings/pdfs/ICOTS9_5D2_MONTGOMERY.pdf (accessed 2026-11-17)
[^s4]: American Society for Quality, "DMAIC". https://asq.org/quality-resources/dmaic (accessed 2026-11-17)
[^s5]: Knowledge at Wharton, "TQM, ISO 9000, Six Sigma: Do Process Management Programs Discourage Innovation?", 30 November 2005. https://knowledge.wharton.upenn.edu/article/tqm-iso-9000-six-sigma-do-process-management-programs-discourage-innovation/ (accessed 2026-11-17)
[^s6]: U.S. Environmental Protection Agency, "Environmental Professional's Guide to Lean and Six Sigma: Executive Summary". https://19january2025snapshot.epa.gov/sustainability/environmental-professionals-guide-lean-and-six-sigma-executive-summary (accessed 2026-11-17)
