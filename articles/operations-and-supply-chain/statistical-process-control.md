---
id: kt:statistical-process-control
type: Practice
title: "Statistical Process Control: Shewhart Control Charts for Telling Common-Cause from Special-Cause Variation"
aliases: [SPC, statistical process control, Shewhart control chart, control charting]
domain: operations-and-supply-chain
summary: >-
  A method, originated by Walter Shewhart at Western Electric and Bell Telephone Laboratories in the 1920s,
  that plots process data in time order against statistically derived control limits so managers can tell
  routine (common-cause) variation from signals of a special, assignable cause that warrants intervention.
broader: [kt:operations-management, kt:total-quality-management]
related: [kt:six-sigma, kt:pdca-cycle, kt:ishikawa-diagram, kt:process-capability, kt:acceptance-sampling]
relations:
  - {predicate: createdBy, object: kt:walter-shewhart}
  - {predicate: introducedIn, object: kt:economic-control-of-quality-of-manufactured-product}
  - {predicate: influenced, object: kt:w-edwards-deming}
  - {predicate: contrastsWith, object: kt:acceptance-sampling}
  - {predicate: exemplifiedBy, object: kt:bell-labs}
sources:
  - id: s1
    title: "Shewhart, Walter Andrew"
    publisher: Complete Dictionary of Scientific Biography, Charles Scribner's Sons, 2008 (Churchill Eisenhart), via MacTutor, University of St Andrews
    url: https://mathshistory.st-andrews.ac.uk/DSB/Shewhart.pdf
    type: encyclopedia
    accessed: 2026-11-26
  - id: s2
    title: "6.3.1. What are Control Charts?"
    publisher: NIST/SEMATECH e-Handbook of Statistical Methods, National Institute of Standards and Technology
    url: https://itl.nist.gov/div898/handbook/pmc/section3/pmc31.htm
    type: government
    accessed: 2026-11-26
  - id: s3
    title: "NIST/SEMATECH Engineering Statistics Handbook Chapter 6: Process or Product Monitoring and Control"
    publisher: National Institute of Standards and Technology (J. Prins, 2003)
    url: https://www.nist.gov/publications/nistsematech-engineering-statistics-handbook-chapter-6-process-or-product-monitoring
    type: government
    accessed: 2026-11-26
  - id: s4
    title: "Monitoring univariate processes using control charts: Some practical issues and advice"
    publisher: Quality Engineering 36(3), 487-499 (Zwetsloot, Jones-Farmer & Woodall, 2024), doi:10.1080/08982112.2023.2238049
    url: https://pure.uva.nl/ws/files/207771767/Monitoring_univariate_processes_using_control_charts_Some_practical_issues_and_advice.pdf
    type: peer-reviewed
    accessed: 2026-11-26
  - id: s5
    title: "Chapter 15: Statistics for Quality: Control and Capability"
    publisher: Macmillan Learning (business statistics textbook companion chapter)
    url: https://www.macmillanlearning.com/studentresources/college/statistics/psbe5e/companion_chapters/19_psbe5e_10900_ch15_15-1_15-58.pdf
    type: textbook
    accessed: 2026-11-26
created: 2026-11-26
---

# Statistical Process Control

Statistical process control (SPC) is the use of time-ordered data and control charts to keep a process stable and to signal when something has changed it. Its core idea is that every process varies, and that managers need a disciplined way to tell the always-present background variation (common or chance causes) from variation produced by an identifiable event such as a jammed machine, bad raw material or operator error (special or assignable causes).[^s5][^s1] NIST distinguishes SPC, which compares current performance with past performance to detect degradation, from statistical quality control by inspection, which samples finished lots to confirm a quality level.[^s3]

## Origin

The method grew out of a practical problem at Western Electric around 1920: engineers found that repeatedly adjusting a process to offset each observed deviation could actually increase its variability. Walter A. Shewhart, a physicist who worked at Western Electric from 1918 and then at Bell Telephone Laboratories from 1925 until 1956, was asked when corrective action helps and when a process should be left alone. In 1924 he devised the control chart; a facsimile of the first chart and its transmittal memo is dated 16 May 1924.[^s1] His 1931 book *Economic Control of Quality of Manufactured Product* set out the distinction between chance and assignable causes and defined a process free of assignable causes as being in a state of statistical control, after which further improvement requires changing the process itself.[^s1] The essential break with earlier practice was plotting data in chronological order rather than pooling it.[^s1]

## How it works

A control chart plots a statistic, such as a subgroup mean, against time or sample number, with a center line at the in-control mean and upper and lower control limits chosen so nearly all points fall inside them while only chance causes operate.[^s2] Shewhart recommended limits three standard deviations from the center line as a rough economic balance between false alarms and missed causes; the American Society for Testing and Materials adopted them in 1933, while British practice favored explicit probability limits.[^s1][^s2] For normally distributed data, a point falls outside 3-sigma limits by chance about 0.27% of the time.[^s2][^s5] Common designs include x-bar and R or s charts for measured variables, individuals and moving-range charts when subgroups are impractical, and p and c charts for counts of defectives or errors.[^s5] A point beyond the limits warrants investigation, but points inside the limits do not prove control: non-random patterns, such as long runs on one side of the center line, are also signals.[^s2] Supplementary runs rules catch such patterns, but adding them raises the false-alarm rate; one textbook notes a full rule set lifts it to about 0.02, more than seven times the one-point rule.[^s5]

Practitioners work in phases: a retrospective Phase I that studies historical data, removes assignable causes and defines the in-control state, then a prospective Phase II that monitors new data against that baseline, ideally with a written out-of-control action plan.[^s4] Control limits come from the process's own behavior and are not specification limits set by customers or engineers; a process can be in control yet still fail to meet specifications, which is the question process capability indices such as Cp and Cpk address.[^s5]

## Evidence and critiques

SPC's statistical foundations are well established, but research highlights recurring misuse. Zwetsloot, Jones-Farmer and Woodall (2024) warn that estimated limits behave like known-parameter limits only with impractically large Phase I samples, that positive autocorrelation and multiple variance components produce many misleading signals, and that symmetric 3-sigma limits suit skewed data poorly.[^s4] They note Shewhart charts best detect large, transient shifts, and recommend pairing them with EWMA or CUSUM charts for small sustained shifts.[^s4] Textbook examples make the autocorrelation point concrete: weekly stock-index data put more than half of subgroups outside naively computed limits.[^s5] A managerial critique follows from the method itself: an in-control process is merely predictable, and whether its performance is acceptable "is not a statistical question."[^s5]

## In practice

SPC spread from Bell System manufacturing through American war standards of 1941-1942 and, via W. Edwards Deming's 1950 lectures to Japanese engineers, into the Japanese quality movement.[^s1] Today it is applied well beyond factories: one textbook case charts emergency-room blood-test turnaround times at a hospital laboratory, finding the process in control at an average of about 41 minutes but incapable of meeting a 50-minute target reliably.[^s5]

## Connections

SPC is a core tool of operations management and of total quality management, and it is the Control step of Six Sigma's DMAIC cycle.[^s5] It was created by Walter Shewhart and introduced in *Economic Control of Quality of Manufactured Product*; Deming edited Shewhart's 1939 lectures and carried the method to Japan, so it shaped his quality philosophy; business-statistics texts teach it alongside the PDCA improvement cycle.[^s1][^s5] Ishikawa (fishbone) diagrams are used alongside control charts to search for special causes once a signal appears.[^s5] SPC contrasts with acceptance sampling, which judges output after the fact rather than monitoring the process, and it precedes process capability analysis, which is meaningful only for a process already in control.[^s3][^s5]

## Sources

[^s1]: Churchill Eisenhart, "Shewhart, Walter Andrew", Complete Dictionary of Scientific Biography, Charles Scribner's Sons, 2008. https://mathshistory.st-andrews.ac.uk/DSB/Shewhart.pdf (accessed 2026-11-26)
[^s2]: NIST/SEMATECH e-Handbook of Statistical Methods, "6.3.1. What are Control Charts?", National Institute of Standards and Technology. https://itl.nist.gov/div898/handbook/pmc/section3/pmc31.htm (accessed 2026-11-26)
[^s3]: J. Prins, "NIST/SEMATECH Engineering Statistics Handbook Chapter 6: Process or Product Monitoring and Control", NIST, 2003. https://www.nist.gov/publications/nistsematech-engineering-statistics-handbook-chapter-6-process-or-product-monitoring (accessed 2026-11-26)
[^s4]: Inez M. Zwetsloot, L. Allison Jones-Farmer and William H. Woodall, "Monitoring univariate processes using control charts: Some practical issues and advice", Quality Engineering 36(3), 487-499, 2024. https://pure.uva.nl/ws/files/207771767/Monitoring_univariate_processes_using_control_charts_Some_practical_issues_and_advice.pdf (accessed 2026-11-26)
[^s5]: "Statistics for Quality: Control and Capability", Chapter 15 companion chapter, Macmillan Learning. https://www.macmillanlearning.com/studentresources/college/statistics/psbe5e/companion_chapters/19_psbe5e_10900_ch15_15-1_15-58.pdf (accessed 2026-11-26)
