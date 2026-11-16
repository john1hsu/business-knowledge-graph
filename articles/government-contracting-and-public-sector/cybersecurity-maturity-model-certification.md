---
id: kt:cybersecurity-maturity-model-certification
type: Regulation
title: "Cybersecurity Maturity Model Certification (CMMC): Verifying Defense Contractors' Cyber Hygiene"
aliases: [CMMC, CMMC 2.0, CMMC Program, 32 CFR Part 170]
domain: government-contracting-and-public-sector
summary: >-
  The US Department of Defense program, codified at 32 CFR Part 170, that makes award of defense contracts
  conditional on a contractor's verified implementation of tiered cybersecurity requirements for
  protecting Federal Contract Information and Controlled Unclassified Information.
broader: [kt:public-procurement]
related: [kt:federal-acquisition-regulation, kt:small-business-set-asides, kt:government-accountability-office, kt:revolutionary-far-overhaul]
relations:
  - {predicate: createdBy, object: kt:department-of-defense}
  - {predicate: regulatedBy, object: kt:defense-federal-acquisition-regulation-supplement}
  - {predicate: dependsOn, object: kt:nist-sp-800-171}
  - {predicate: mitigates, object: kt:information-asymmetry}
  - {predicate: appliesTo, object: kt:defense-industrial-base}
sources:
  - id: s1
    title: "Cybersecurity Maturity Model Certification (CMMC) Program, final rule, 89 FR 83092 (32 CFR Part 170)"
    publisher: Federal Register, via GovInfo
    url: https://www.govinfo.gov/content/pkg/FR-2024-10-15/html/2024-22905.htm
    type: primary
    accessed: 2026-11-16
  - id: s2
    title: "About CMMC"
    publisher: Chief Information Officer, U.S. Department of War
    url: https://dodcio.defense.gov/CMMC/About/
    type: government
    accessed: 2026-11-16
  - id: s3
    title: "Defense Contractor Cybersecurity: Stakeholder Communication and Performance Goals Could Improve Certification Framework (GAO-22-104679)"
    publisher: U.S. Government Accountability Office
    url: https://www.gao.gov/products/gao-22-104679
    type: government
    accessed: 2026-11-16
  - id: s4
    title: "Defense Contractor Cybersecurity: DOD Should Address External Factors That Could Impede Program Implementation (GAO-26-107955)"
    publisher: U.S. Government Accountability Office
    url: https://files.gao.gov/reports/GAO-26-107955/index.html
    type: government
    accessed: 2026-11-16
  - id: s5
    title: "SBA Commends U.S. Department of War's Suspension of CMMC Phase II for Small Defense Contractors"
    publisher: U.S. Small Business Administration
    url: https://legacy.sba.gov/article/2026/07/13/sba-commends-us-department-wars-suspension-cmmc-phase-ii-small-defense-contractors
    type: government
    accessed: 2026-11-16
  - id: s6
    title: "Pentagon Suspends CMMC Phase 2 Requirements and Launches Review of Cybersecurity Certification Program"
    publisher: WilmerHale
    url: https://www.wilmerhale.com/en/insights/client-alerts/20260720-pentagon-suspends-cmmc-phase-2-requirements-and-launches-review-of-cybersecurity-certification-program
    type: organization
    accessed: 2026-11-16
created: 2026-11-16
---

# Cybersecurity Maturity Model Certification (CMMC): Verifying Defense Contractors' Cyber Hygiene

The Cybersecurity Maturity Model Certification (CMMC) is the US Department of Defense (DoD, now also styled the Department of War) program for verifying that contractors and subcontractors have actually implemented the security measures required to protect Federal Contract Information (FCI) and Controlled Unclassified Information (CUI). Its program rule, codified at 32 CFR Part 170, was published on October 15, 2024 and took effect on December 16, 2024; a separate DFARS acquisition rule governs when CMMC requirements appear in contracts.[^s1] The core idea is simple: a company must hold the CMMC level a solicitation specifies as a condition of award, rather than merely promising compliance.[^s2]

## Origin

Defense contractors were already obliged to implement the NIST SP 800-171 requirements by December 2017, but compliance rested on self-attestation. DoD announced CMMC in 2019 to move away from that model, and the fiscal 2020 defense authorization act required a cybersecurity framework for the defense industrial base.[^s1][^s4] GAO notes that a 2019 DoD Inspector General review found contractors did not consistently implement the controls protecting CUI.[^s4] An interim DFARS rule launched the first version of CMMC on November 30, 2020 with a five-year phase-in, but after roughly 750 public comments DoD began an internal review in March 2021 and announced a revised program in November 2021, often called CMMC 2.0.[^s1] GAO reported in December 2021 that the pilot had stalled: DoD had planned to include the requirement in up to 15 acquisitions in fiscal 2021 but had used it in none, partly because assessors had not been certified, and small firms worried about cost and consistency.[^s3] The revision cut certification levels, dropped DoD-unique practices and restarted rulemaking.[^s3]

## How it works

CMMC has three levels keyed to the sensitivity of the information a contractor handles.[^s1]

- **Level 1** covers FCI with the 15 requirements of FAR clause 52.204-21, verified by an annual self-assessment; no plan of action and milestones (POA&M) is allowed.[^s1][^s2]
- **Level 2** covers CUI with the 110 requirements of NIST SP 800-171 Revision 2, assessed every three years either by the contractor itself or by an accredited CMMC Third-Party Assessment Organization (C3PAO), with an annual affirmation.[^s1]
- **Level 3** adds 24 requirements selected from NIST SP 800-172, assessed every three years by DCMA's Defense Industrial Base Cybersecurity Assessment Center; a contractor must first hold a final Level 2 C3PAO status.[^s1]

At Levels 2 and 3 a contractor that scores at least 80 percent of the maximum and meets certain critical requirements can receive conditional status with a POA&M, but must close every open item within 180 days or the status lapses.[^s1] Results and affirmations are posted in DoD's Supplier Performance Risk System (SPRS).[^s2] The rule projected that about 8,350 medium and large entities would need C3PAO Level 2 assessments, ramping from 135 assessments in year one to 4,452 in year four.[^s1] Rollout under the DFARS clause began on November 10, 2025 as a 36-month, four-phase schedule.[^s4]

## Evidence and critiques

CMMC addresses a classic information problem: the government cannot cheaply observe whether a supplier's controls are real, so self-attestation invites overstatement. Its weakness is that third-party verification depends on a private assessor market. As of December 2025, 92 C3PAOs had been authorized and 633 assessors certified, while DoD relies on about 200,000 companies, roughly three-quarters of them small.[^s4] GAO's March 2026 report found DoD's implementation plans covered six of seven elements of a sound strategy but had not documented external risks such as assessor capacity, and warned that leaning on waivers could erode the program's credibility.[^s4]

Cost is the most persistent objection. In July 2026 the SBA said more than 120,000 small defense firms would have needed compliance under Phase 2 with only about 100 approved assessors, and estimated costs of about $593,800 per certification for firms needing a third-party assessment.[^s5] Those estimates come from an agency advocating for small firms and sit far above DoD's November 2021 estimate of $4,042 to $117,768 per assessment, which GAO reported.[^s4][^s5]

## Current status

On July 13, 2026 the department suspended Phase 2, which would have required C3PAO Level 2 certifications from November 10, 2026, and created a CMMC Reform Task Force to conduct a 60-day review of more scalable approaches, citing burdens on small and non-traditional contractors and scarce assessor capacity.[^s6][^s2] Contracting officers are to remove Phase 2 and 3 requirements from existing contracts, but Level 1 and Level 2 self-assessments, SPRS postings and the underlying DFARS 252.204-7012 obligations to implement NIST SP 800-171 remain in force.[^s6] As of November 2026, DoD's CMMC page described Phase 1 as paused and Phase 2 as suspended pending the review.[^s2]

## Connections

CMMC is a tool of **public procurement**, created by the **Department of Defense** and imposed on the **defense industrial base** through clauses in the **DFARS**, the defense supplement to the **Federal Acquisition Regulation**.[^s1][^s2] Its technical content **depends on NIST SP 800-171**.[^s1] Economically it **mitigates information asymmetry** between buyer and supplier by replacing self-reported compliance with verification.[^s1][^s4] Its compliance costs collide with policy goals behind **small business set-asides**, which is why the SBA weighed in on the 2026 suspension.[^s5] The **Government Accountability Office** has tracked the program since 2021, and the 2026 reform review runs in parallel with the **Revolutionary FAR Overhaul** of acquisition rules.[^s3][^s4][^s6]

## Sources

[^s1]: Department of Defense, "Cybersecurity Maturity Model Certification (CMMC) Program", final rule, 89 FR 83092, October 15, 2024 (32 CFR Part 170). https://www.govinfo.gov/content/pkg/FR-2024-10-15/html/2024-22905.htm (accessed 2026-11-16)
[^s2]: Chief Information Officer, U.S. Department of War, "About CMMC". https://dodcio.defense.gov/CMMC/About/ (accessed 2026-11-16)
[^s3]: U.S. Government Accountability Office, "Defense Contractor Cybersecurity: Stakeholder Communication and Performance Goals Could Improve Certification Framework", GAO-22-104679, December 8, 2021. https://www.gao.gov/products/gao-22-104679 (accessed 2026-11-16)
[^s4]: U.S. Government Accountability Office, "Defense Contractor Cybersecurity: DOD Should Address External Factors That Could Impede Program Implementation", GAO-26-107955, March 12, 2026. https://files.gao.gov/reports/GAO-26-107955/index.html (accessed 2026-11-16)
[^s5]: U.S. Small Business Administration, "SBA Commends U.S. Department of War's Suspension of CMMC Phase II for Small Defense Contractors", July 13, 2026. https://legacy.sba.gov/article/2026/07/13/sba-commends-us-department-wars-suspension-cmmc-phase-ii-small-defense-contractors (accessed 2026-11-16)
[^s6]: WilmerHale, "Pentagon Suspends CMMC Phase 2 Requirements and Launches Review of Cybersecurity Certification Program", client alert, July 20, 2026. https://www.wilmerhale.com/en/insights/client-alerts/20260720-pentagon-suspends-cmmc-phase-2-requirements-and-launches-review-of-cybersecurity-certification-program (accessed 2026-11-16)
