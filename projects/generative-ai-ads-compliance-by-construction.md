# Making compliant advertising the first generated draft

I led product-marketing and launch work for an AI-assisted advertising workflow during my Microsoft tenure. I saw that businesses learned about policy only after finishing their creative, which made the product feel unpredictable and sent reviewers avoidable work. I worked with small businesses, catalog advertisers and agencies, product and growth, machine-learning and engineering teams, operations reviewers, policy, legal, brand, sales, finance, and regional owners.

## I changed the unit of success

Fifteen to twenty percent of ads were rejected after creation; the retained pilot baseline was 18%. Product optimized generation speed, Growth watched CTR, Operations watched review volume, Policy watched exposure and advertisers watched launch delay. None represented the whole customer outcome.

I aligned the launch on **successful compliant publication**: an eligible advertiser creates an ad, understands and resolves relevant constraints, passes required review, launches, and achieves acceptable commercial performance. Faster generation that produced more rejected ads was negative productivity.

The launch contract I set spanned generation, policy, human review, advertiser learning, enforcement risk, and campaign economics. That meant converting legal rules into contextual creation requirements, proving them first on 5,000 ads and then with 500 high-risk sellers, and refusing to scale on speed or output volume unless compliant publication and commercial performance moved together.

The product supported AI-assisted copy and static assets. I do not extend this 2020–2022 record to later autonomous campaign management, video generation or public Copilot capabilities.

## Policy became contextual product data

More than 500 pages of guidance were tagged by market, product category, claim type, severity, required substantiation and brand rule. At creation time, the system combined advertiser brief, product feed, landing page, image and market, then retrieved the applicable constraints.

The policy store did not “compile the law” into a final legal answer. Policy owners maintained approved interpretations, effective dates, versions, precedence and escalation. High-risk verticals received stricter evidence and review; ordinary goods did not inherit every medical, financial or age-sensitive rule.

The [FTC’s advertising guidance](https://www.ftc.gov/business-guidance/advertising-marketing) and [small-business advertising FAQ](https://www.ftc.gov/business-guidance/resources/advertising-faqs-guide-small-business) provided an external US baseline: express and implied claims must be truthful, non-deceptive and appropriately substantiated. Each jurisdiction and platform still needed its own policy owner.

## The experience taught, constrained and escalated

I marketed the workflow as creation help rather than moderation:

`brief + product context → relevant policy → visible coaching → constrained draft → joint copy/image inspection → pass, repair or review`

Risky text or an implied visual claim was highlighted in place. The advertiser saw the reason and a safer alternative, retained the rest of the concept and could appeal. Silent rewriting had looked like model failure and removed agency.

Enforcement depended on confidence and consequence:

- high-confidence, high-severity violations were blocked or minimally repaired;
- ambiguous or consequential cases went to a trained person with policy and evidence attached;
- low-risk categories used lighter thresholds; and
- appeal outcomes entered weekly rule, example and model review.

A human disposition was not automatically ground truth. Review disagreement, policy changes and regional edge cases had to be adjudicated before they altered enforcement.

## Three advertiser propositions

For a small business, the value was understanding why an ad failed and recovering without a policy specialist. For a catalog aggregator, it was applying current rules consistently across thousands of products and routing only exceptions. For an agency, it was combining platform policy with client brand constraints and retaining an approval trace.

The message therefore changed by segment, but the proof stayed common: fewer avoidable rejections, lower false enforcement, faster compliant launch, controlled appeals and no unacceptable decline in commercial performance.

## Evidence ladder before enforcement

**Offline replay.** Ten thousand historically rejected ads tested known-violation coverage. The system caught 94% and exposed a gap where copy and imagery separately looked acceptable but combined to imply a prohibited claim. Because the dataset contained rejected ads, 94% is not production accuracy.

**Live pilot.** Five hundred high-risk sellers ran for 30 days against the existing flow. Rejection moved from 18% to 1.8%.

**Shadow comparison.** Five thousand live ads were compared with human moderation before automated enforcement. The source reports 96% precision and 91% recall. That means 4% of system-positive cases were not confirmed and 9% of human-confirmed violations were missed under the retained definitions—not that 96% of all ads were correct.

An earlier 10,000-ad review found 12% flagged and 8% of those flags actually compliant. Later false positives are reported as 1.4%, but the denominator is not specified; it should not be casually reconciled with “8% of flags” or 96% precision.

## Launch scorecard

| Measure | Baseline | Recorded result | Defensible calculation and caveat |
|---|---:|---:|---|
| Rejection | 18% | 1.8% | -16.2 points and -90% relative in the 500-seller, 30-day high-risk pilot |
| False positives | initial 8% of flags compliant | ~1.4% later | source changes denominator; needs false blocks / compliant ads or false blocks / all blocks |
| Compliant launch time | 5–7 days | <1 hour | from at least 120 hours to <1, more than 99.17% lower; task start/end and review queue mix required |
| Shadow precision / recall | prior system absent | 96% / 91% | 5,000-ad comparison with human moderation; adjudication quality and category mix matter |
| High-risk-category ROAS | baseline index 100 | >140 | source reports >40% higher despite some CTR decline; control design, spend, attribution and period absent |
| Standard-category performance | baseline | no material decline | equivalence bound and sample absent |

The source also lists asset cost falling from more than $150 to about $0.50 and more than $500 million in projected revenue potential, then explicitly instructs the Microsoft 2020–2022 version to exclude later image/video economics and that projection. I exclude both.

## Chronology and attribution correction

An earlier portfolio version placed this project under my current AWS role. The retained source explicitly says Microsoft and the 2020–2022 period, so I have moved it to Microsoft here and in the guide.

Microsoft publicly announced [Copilot in the Microsoft Advertising Platform in September 2023](https://about.ads.microsoft.com/en/blog/post/september-2023/transforming-search-and-advertising-with-generative-ai), after my tenure ended, and described broader text and image creation publicly in [June 2024](https://www.about.ads.microsoft.com/en/blog/post/june-2024/what-you-can-do-with-copilot-in-the-microsoft-advertising-platform). Those launches show later company direction; I do not claim them as my launch. This project is best presented as an earlier internal AI-assisted copy/static workflow unless contemporaneous public or internal release evidence establishes otherwise.

I owned the category proposition, shared success metric, segment message, policy-as-product requirements, coaching and escalation experience, validation narrative, launch gates and commercial measurement. Policy and legal owned interpretations. Engineering owned implementation. Reviewers owned ambiguous decisions. Advertisers owned the final creative. The lasting PMM advantage was making trust visible inside creation rather than promising that a faster generator would somehow become safe downstream.
