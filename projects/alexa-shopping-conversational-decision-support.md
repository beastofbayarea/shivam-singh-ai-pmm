# Alexa Shopping - Conversational Decision Support

## How I frame the project

I developed this case study to show how I would lead the work behind **Alexa Shopping - Conversational Decision Support** from an ambiguous starting point to an evidence-based decision and an executable plan. I place it in the context of my [AWS experience from July 2024 to present](https://github.com/beastofbayarea/shivam-singh-ai-pmm/blob/main/shivam-singh-ai-pmm.pdf).

I keep the story practical and transparent. I start with public evidence, turn that evidence into explicit choices, assign ownership, and define how I would know whether the work is creating value.

## Why this problem matters to me

I see growth and go-to-market programs underperform when channel activity is separated from product behavior, incremental economics, customer trust, and operational follow-through. I therefore treat the project as a customer-value, measurement, and operating-model challenge, not as a narrow functional exercise.

I use [Lewis et al. - Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (2020)](https://arxiv.org/abs/2005.11401) to ground technical basis for retrieval grounding, updateable knowledge, provenance, and factual generation. I use [NIST - Generative AI Profile (2024)](https://doi.org/10.6028/NIST.AI.600-1) to ground risk and evaluation framework for trustworthy generative AI deployment.

## What I would set out to accomplish

- I would retrieve current catalog, price, availability, and review evidence before generating comparisons.
- I would constrain the assistant to shortlists and explicit trade-offs tied to retrieved evidence.
- I would evaluate factuality, retrieval relevance, refusal behavior, and customer confirmation before transactional steps.
- I would position the value around decision confidence and time saved, not novelty or conversation volume.

I would agree on these objectives before I commit the team to a solution. I would also record what is out of scope, which assumptions remain uncertain, and which new evidence would cause me to change direction.

## How I would structure the work

### How I would approach workstream 1

I would retrieve current catalog, price, availability, and review evidence before generating comparisons. I would define the service objective, failure modes, capacity assumptions, instrumentation, and recovery path before I scale the change. I would use canaries and controlled stress to learn where the system breaks while the blast radius is still small.

### How I would approach workstream 2

I would constrain the assistant to shortlists and explicit trade-offs tied to retrieved evidence. I would turn this into a named workstream with an accountable owner, explicit inputs, a decision deadline, and a measurable exit condition. I would keep the work visible through a concise decision log and review unresolved dependencies before they become schedule surprises.

### How I would approach workstream 3

I would evaluate factuality, retrieval relevance, refusal behavior, and customer confirmation before transactional steps. I would work with representative users and operators, observe the complete workflow, and capture where confidence, time, or accountability breaks down. I would convert those observations into testable needs and acceptance criteria instead of relying on stakeholder intuition alone.

### How I would approach workstream 4

I would position the value around decision confidence and time saved, not novelty or conversation volume. I would document the authoritative sources, definitions, freshness expectations, lineage, and exception paths before I ask anyone to act on the data. I would require a visible reconciliation view so that the team can distinguish a business movement from a measurement defect.

## How I would lead the people and decisions

I would run the project with a small decision-making core that includes product, marketing, sales or partnerships, analytics, finance, legal, customer support, and the teams responsible for the customer experience. I would agree up front on who recommends, who decides, who executes, and who must be consulted so that cross-functional collaboration does not become consensus by default.

- I would maintain a weekly working session focused on evidence, decisions, dependencies, and risks rather than broad status reporting.
- I would use a concise decision log that records the question, options, evidence, owner, decision, date, and conditions for revisiting it.
- I would schedule executive reviews around irreversible choices, material risk changes, and commitment gates instead of arbitrary reporting cycles.
- I would keep user, customer, partner, or operator feedback connected to the backlog so that qualitative evidence changes delivery priorities.

## How I would sequence delivery

### How I would establish the baseline

I would begin by documenting the current workflow, economics, controls, service levels, pain points, and ownership boundaries. I would separate verified facts from assumptions and make missing evidence visible before the team debates solutions.

### How I would design the smallest credible intervention

I would choose the smallest change that can test the central value and risk assumptions. I would define the target cohort, acceptance criteria, instrumentation, support model, and stopping conditions before I begin the pilot.

### How I would pilot and learn

I would release in a bounded environment, review both expected outcomes and unintended effects, and compare results with the baseline or a meaningful counterfactual. I would use the evidence to continue, revise, narrow, or stop rather than treating launch as proof of success.

### How I would scale responsibly

I would expand only after the operating owner, controls, documentation, support capacity, and measurement system are ready. I would preserve rollback paths and keep reviewing cohort-level outcomes so that scale does not hide deterioration.

## How I would measure progress and value

I would connect every measure to a decision. I would avoid a dashboard that reports activity without telling me whether to continue, intervene, or stop.

| What I would measure | How I would use it |
|---|---|
| I would track citation coverage | I would use this to expose evidence gaps before they turn into confident but incorrect decisions. |
| I would track unsupported-claim rate | I would use this to judge whether the output is trustworthy enough for the next stage and to identify the failure modes that need targeted work. |
| I would track task completion | I would use this to learn whether the intended audience reaches meaningful value, and I would segment it so aggregate growth cannot hide weak cohorts. |
| I would track shortlist usefulness | I would use this to learn whether the intended audience reaches meaningful value, and I would segment it so aggregate growth cannot hide weak cohorts. |
| I would track confirmation rate | I would baseline this measure, assign an owner, review it by cohort or operating segment, and connect movement to a specific decision or corrective action. |
| I would track error recovery | I would use this to locate operational friction and decide whether process, architecture, ownership, or capacity is the limiting factor. |

I would review leading indicators during delivery and lagging outcomes after adoption. I would also pair quantitative measures with qualitative evidence so that I can explain why a number moved and what I should do next.

## What I would watch closely

- I would watch for weak or selectively interpreted evidence, and I would document assumptions, counter-evidence, and the confidence level behind each material decision.
- I would watch for hidden dependencies and unclear decision rights, and I would keep a live dependency map with an owner and escalation date for every critical path item.
- I would watch for adoption that looks healthy in aggregate but fails for important users, markets, partners, or operating teams, and I would review outcomes by cohort.
- I would watch for a plan that optimizes a headline metric while moving cost, risk, or workload elsewhere, and I would review the outcome as a system rather than as a single KPI.

I would give every material risk an owner, an early-warning indicator, a mitigation, and a trigger for escalation or rollback. I would revisit the risk register whenever the scope, evidence, or operating environment changes.

## What I would consider a strong outcome

I would consider the project successful when stakeholders can explain the decision, the evidence behind it, the owner of each critical dependency, and the conditions for scaling or stopping. I would also expect the operating team to inherit a usable system: clear controls, observable performance, documented exceptions, and a measurement cadence that continues after the initial launch.

## Sources I rely on

I use independent methodology and market evidence to shape the analysis. I use the career link above to provide chronology.

| Source I use | How I use it |
|---|---|
| [Lewis et al. - Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (2020)](https://arxiv.org/abs/2005.11401) | I use this source to ground technical basis for retrieval grounding, updateable knowledge, provenance, and factual generation. |
| [NIST - Generative AI Profile (2024)](https://doi.org/10.6028/NIST.AI.600-1) | I use this source to ground risk and evaluation framework for trustworthy generative AI deployment. |
