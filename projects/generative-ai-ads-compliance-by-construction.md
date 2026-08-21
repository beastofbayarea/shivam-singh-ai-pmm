# Making compliant advertising the first generated draft

This program began with a contradiction: AI could create an ad in seconds, but 15–20% of ads were being rejected after creation and the retained pilot baseline was 18%. Advertisers experienced the product as arbitrary, policy reviewers absorbed avoidable volume, and faster generation merely accelerated failure.

During my Microsoft tenure, I took charge of the product-marketing and launch intervention, aligning small businesses, catalog advertisers, agencies, Product, Growth, ML, Engineering, Operations, Policy, Legal, Brand, Sales, Finance, and regional owners around one release contract.

## One outcome reconciled six competing teams

Product watched generation time. Growth watched CTR. Operations watched review volume. Policy watched exposure. Advertisers watched time to launch. Finance watched campaign economics.

I replaced those local optimizations with **successful compliant publication**: an eligible advertiser creates an ad, understands and resolves relevant constraints, passes the required review, launches, and maintains acceptable commercial performance.

That definition changed the roadmap. I would not support wider enforcement based on output volume or model speed. The product first had to convert policy into contextual creation requirements, prove coverage offline, demonstrate improvement in a high-risk live cohort, agree with human moderation in shadow mode, and preserve ROAS.

## From 500 pages of policy to an executable creation experience

The team structured more than 500 pages of guidance by market, product category, claim type, severity, substantiation, brand rule, owner, effective date, and escalation path. Advertiser brief, product feed, landing page, imagery, and market determined which constraints appeared during creation.

The system did not pretend to “compile the law.” Legal and policy owners maintained approved interpretations and precedence. Medical, financial, age-sensitive, and other high-consequence categories received stricter evidence and review; ordinary goods did not inherit every possible restriction.

The experience itself had three modes:

- **Teach:** highlight the risky text or implied visual claim, show the reason, and preserve the advertiser’s usable work.
- **Constrain:** block or minimally repair high-confidence, high-severity violations.
- **Escalate:** send ambiguous or consequential cases to trained reviewers with the policy, evidence, and model rationale attached.

Advertisers could appeal. Review outcomes entered weekly adjudication because a human decision was not automatically ground truth; disagreement, policy change, and regional edge cases had to be resolved before becoming training or enforcement data.

The [FTC advertising guidance](https://www.ftc.gov/business-guidance/advertising-marketing) and [small-business advertising FAQ](https://www.ftc.gov/business-guidance/resources/advertising-faqs-guide-small-business) provided a US reference for truthfulness and substantiation. Each jurisdiction and platform still required its own accountable interpretation.

## The product had three buyers

For a small business, the proposition was recoverability: understand the issue and launch without needing a policy specialist. For a catalog advertiser, it was consistent control across thousands of products with people focused on exceptions. For an agency, it was combining platform policy with client-brand constraints while retaining an approval trace.

The messages differed, but the proof contract stayed the same: fewer avoidable rejections, controlled false enforcement, faster compliant launch, bounded appeals, and no unacceptable commercial-performance decline.

## I built the evidence ladder before the enforcement ladder

**Historical replay:** 10,000 previously rejected ads tested known-violation coverage. The system caught 94% and uncovered a cross-modal gap in which copy and imagery were individually acceptable but jointly implied a prohibited claim. Because the dataset contained rejected ads, 94% was coverage of known problems—not overall production accuracy.

**High-risk pilot:** 500 sellers used the workflow for 30 days. Rejection fell from 18% to 1.8%.

**Live shadowing:** 5,000 ads were compared with human moderation before automated enforcement. Recorded precision was 96% and recall 91%. Under those definitions, 4% of system-positive cases were not confirmed and 9% of human-confirmed violations were missed.

An earlier review found 12% of 10,000 ads flagged and 8% of those flags actually compliant. A later 1.4% false-positive figure uses an unspecified denominator, so I do not merge it with “8% of flags” or infer equivalence from 96% precision.

## Scale decision

| Launch question | Baseline → target → result | Measurement method |
|---|---|---|
| Can advertisers publish successfully? | 18% rejection → single-digit launch gate → 1.8% | Rejected / submitted ads for the same eligible high-risk cohort over 30 days |
| Does control create wrongful friction? | 8% of initial flags compliant → reduce materially → ~1.4% later, denominator unresolved | Report both false blocks / compliant ads and false blocks / all blocks |
| Does creation become operationally faster? | 5–7 days → same-day launch → <1 hour | Timestamp brief start, policy intervention, review queue, advertiser repair, and publication |
| Does shadow quality support automation? | prior system absent → agreed thresholds → 96% precision, 91% recall | Blinded reviewer comparison plus adjudication by category and severity |
| Does compliance preserve economics? | ROAS index 100 → no material harm → >140 in high-risk categories | Concurrent control, stable attribution window, spend normalization, and category mix |
| Can standard categories remain efficient? | baseline performance → equivalence → no material decline recorded | Predefined equivalence bound and adequately powered comparison |

The source also contains near-zero asset-cost and $500 million projected-revenue claims tied to later image/video capability, while explicitly excluding them from this 2020–2022 Microsoft version. I exclude both.

My authority stopped short of policy approval and model implementation. It covered the category proposition, shared outcome, segment narratives, policy-as-product requirements, coaching/escalation experience, proof sequence, launch gates, field story, and commercial account. Policy and Legal interpreted rules; Engineering ran the system; reviewers resolved ambiguity; advertisers controlled final creative.

Microsoft publicly announced Advertising Copilot after my tenure. I do not claim that later public product. This project concerns an earlier AI-assisted copy/static workflow whose strategic advantage was operational: trust moved upstream into creation, turning compliance from a surprise veto into part of the product’s value.
