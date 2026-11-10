---
id: kt:principal-agent-problem
type: Theory
title: Principal-Agent Problem
aliases: [principal-agent model, agency problem, agency dilemma, principal-agent theory]
domain: managerial-economics
summary: >-
  The incentive problem that arises when one party (the principal) relies on another (the agent)
  to act on its behalf but cannot fully observe the agent's actions or information, so the
  principal must design a contract that trades off motivating the agent against the cost of
  loading risk onto them.
broader: [kt:contract-theory, kt:information-asymmetry]
related: [kt:moral-hazard, kt:adverse-selection, kt:corporate-governance, kt:fiduciary-duty]
relations:
  - {predicate: createdBy, object: kt:stephen-a-ross}
  - {predicate: createdBy, object: kt:bengt-holmstrom}
  - {predicate: introducedIn, object: kt:economic-theory-of-agency-ross-1973}
  - {predicate: influenced, object: kt:agency-costs}
  - {predicate: exemplifiedBy, object: kt:wells-fargo-cross-selling-scandal}
sources:
  - id: s1
    title: "The Economic Theory of Agency: The Principal's Problem"
    publisher: American Economic Review, vol. 63, no. 2 (AEA Top 20 reprint)
    url: https://www.aeaweb.org/aer/top20/63.2.134-139.pdf
    type: primary
    accessed: 2026-11-10
  - id: s2
    title: "Moral Hazard and Observability (RePEc record)"
    publisher: Bell Journal of Economics, vol. 10, no. 1, via EconPapers
    url: https://econpapers.repec.org/RePEc:rje:bellje:v:10:y:1979:i:spring:p:74-91
    type: primary
    accessed: 2026-11-10
  - id: s3
    title: "Multitask Principal-Agent Analyses: Incentive Contracts, Asset Ownership, and Job Design"
    publisher: Journal of Law, Economics, & Organization, vol. 7 (course copy, Duke University)
    url: https://people.duke.edu/~qc2/BA532/1991%20JLEO%20Holmstrom%20Milgrom.pdf
    type: peer-reviewed
    accessed: 2026-11-10
  - id: s4
    title: "Performance Pay and Top-Management Incentives (RePEc record)"
    publisher: Journal of Political Economy, vol. 98, no. 2, via EconPapers
    url: https://econpapers.repec.org/RePEc:ucp:jpolec:v:98:y:1990:i:2:p:225-64
    type: peer-reviewed
    accessed: 2026-11-10
  - id: s5
    title: "Press release: The Prize in Economic Sciences 2016"
    publisher: Royal Swedish Academy of Sciences (nobelprize.org)
    url: https://www.nobelprize.org/prizes/economic-sciences/2016/press-release/
    type: organization
    accessed: 2026-11-10
  - id: s6
    title: "Wells Fargo Bank, N.A. (2016) enforcement action"
    publisher: Consumer Financial Protection Bureau
    url: https://www.consumerfinance.gov/enforcement/actions/wells-fargo-bank-2016/
    type: government
    accessed: 2026-11-10
created: 2026-11-10
---

# Principal-Agent Problem

The **principal-agent problem** is the difficulty a principal faces when it delegates decisions to an agent whose goals differ from its own and whose effort or information it cannot fully observe. Stephen Ross, writing in 1973, described an agency relationship as one in which an agent acts for a principal in some set of decisions, and noted how pervasive it is: employer and employee, state and citizen, insurer and insured, and financial intermediaries all fit the pattern.[^s1] The economic question is how the principal should design pay, the "fee schedule", so that the agent, acting in its own interest, chooses actions the principal would want.[^s1]

## How it works

In the canonical model, the agent chooses an action under uncertainty, the action and luck jointly produce an outcome, and the principal pays a fee based on what it can observe. The principal maximizes its own expected utility subject to two constraints: a **participation constraint** (the agent must expect enough to accept the job) and an **incentive constraint** (the agent's chosen action must be the one that is best for the agent given the fee).[^s1] Ross showed that the principal's optimal contract is generally not Pareto-efficient, because the incentive constraint distorts risk sharing, and that full efficiency holds only under restrictive conditions such as linear fees combined with particular classes of preferences.[^s1]

The core tension is between **incentives and insurance**. Paying the agent on outcomes motivates effort but exposes a risk-averse agent to outcomes it does not control; paying a fixed wage removes that risk but also the reason to work hard, so the optimal contract weighs risk against incentives.[^s5] When the hidden element is the agent's action, the problem is **moral hazard**; when it is information the agent holds before contracting, it is **adverse selection**.[^s2]

Bengt Holmström's 1979 paper "Moral Hazard and Observability" sharpened the answer. It derived a necessary and sufficient condition under which an imperfect additional signal of the agent's behaviour can improve on a contract that depends only on output, and showed how such signals should be used.[^s2] This became the **informativeness principle**: tie pay to any measure that carries information about effort, such as a firm's share price relative to its peers, and filter out noise the agent cannot influence.[^s5]

Holmström and Paul Milgrom later extended the model to agents with several tasks. When effort is split across tasks, incentive pay does a second job, directing attention, so strong rewards for a measurable task pull effort away from hard-to-measure ones. In that setting a fixed wage can be optimal even when good output measures exist; their example is teachers paid on test scores neglecting untested higher-order skills.[^s3] The same logic explains job design (group easily measured tasks together and give that job stronger incentives) and when agents rather than principals should own assets.[^s3]

## Evidence and critiques

Empirical work on executives suggests incentives are often weak. Jensen and Murphy estimated that, in their sample, CEO wealth changed by roughly $3.25 for each $1,000 change in shareholder wealth, with stock ownership providing far more incentive than salary, bonuses or dismissal risk; they attributed the weak link partly to political pressure on pay.[^s4] The multitask analysis also cautions against reading weak incentives as a failure: where important outputs are hard to measure, muted incentives can be the rational design rather than a governance lapse.[^s3]

A further critique is that sharp output-based rewards invite gaming. Holmström and Milgrom's model predicts that agents shift effort toward whatever is measured, at the expense of what is not.[^s3] The theory's influence was recognized when Holmström shared the 2016 economics prize with Oliver Hart for contributions to contract theory; the Academy cited applications to executive pay, insurance deductibles and co-pays, and the privatization of public services.[^s5]

## In practice

The 2016 Wells Fargo case illustrates the multitask warning. The Consumer Financial Protection Bureau found that employees, spurred by sales targets and compensation incentives, opened accounts that may not have been authorized, more than two million by the bank's own analysis, and in September 2016 it announced a $100 million penalty, alongside $35 million to the OCC and $50 million to the City and County of Los Angeles, plus full restitution.[^s6] Rewarding a countable output (new accounts) without measuring the hidden one (whether customers wanted them) produced exactly the distortion the theory predicts.[^s3][^s6]

## Connections

The principal-agent problem is the central model of **contract theory** and a special case of **information asymmetry**; its two main forms are **moral hazard** and **adverse selection**.[^s2][^s5] It was formalized by **Stephen A. Ross** in his 1973 paper and developed by **Bengt Holmström**.[^s1][^s2] Ross already noted that monitoring costs, not fee design alone, often make the principal's solution inefficient, the idea later developed as **agency costs**.[^s1] Its application to shareholders and executives motivates **corporate governance** mechanisms and the **fiduciary duty** owed by directors and managers.[^s4][^s5] The **Wells Fargo cross-selling scandal** is a widely studied example of incentive design gone wrong.[^s6]

## Sources

[^s1]: Stephen A. Ross, "The Economic Theory of Agency: The Principal's Problem", American Economic Review 63(2), 1973, pp. 134–139. https://www.aeaweb.org/aer/top20/63.2.134-139.pdf (accessed 2026-11-10)
[^s2]: Bengt Holmstrom, "Moral Hazard and Observability", Bell Journal of Economics 10(1), 1979, pp. 74–91 (EconPapers record). https://econpapers.repec.org/RePEc:rje:bellje:v:10:y:1979:i:spring:p:74-91 (accessed 2026-11-10)
[^s3]: Bengt Holmstrom and Paul Milgrom, "Multitask Principal-Agent Analyses: Incentive Contracts, Asset Ownership, and Job Design", Journal of Law, Economics, & Organization 7, 1991, pp. 24–52. https://people.duke.edu/~qc2/BA532/1991%20JLEO%20Holmstrom%20Milgrom.pdf (accessed 2026-11-10)
[^s4]: Michael C. Jensen and Kevin J. Murphy, "Performance Pay and Top-Management Incentives", Journal of Political Economy 98(2), 1990, pp. 225–264 (EconPapers record). https://econpapers.repec.org/RePEc:ucp:jpolec:v:98:y:1990:i:2:p:225-64 (accessed 2026-11-10)
[^s5]: Royal Swedish Academy of Sciences, "The Prize in Economic Sciences 2016" press release. https://www.nobelprize.org/prizes/economic-sciences/2016/press-release/ (accessed 2026-11-10)
[^s6]: Consumer Financial Protection Bureau, "Wells Fargo Bank, N.A. (2016)" enforcement action. https://www.consumerfinance.gov/enforcement/actions/wells-fargo-bank-2016/ (accessed 2026-11-10)
