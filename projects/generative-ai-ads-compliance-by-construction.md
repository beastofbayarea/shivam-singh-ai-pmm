# Generative AI Ads — Compliance by Construction

I completed this work during my [AWS experience from July 2024 to present](https://github.com/beastofbayarea/shivam-singh-ai-pmm/blob/main/shivam-singh-ai-pmm.pdf).

## The failure mode I addressed

Advertisers could generate copy and static assets quickly, but 15–20% of submissions were rejected only after the creative work was complete. That made compliance feel arbitrary to sellers and created an expensive review queue for Operations, Legal, and Policy.

I reframed the problem from “detect bad ads faster” to “help sellers create a compliant ad the first time.” The new north-star measure was a successful compliant launch—not generation speed, click-through rate, creative volume, or review throughput in isolation.

## Turning policy into a product capability

I converted more than 500 pages of guidance into rules tagged by category, jurisdiction, claim type, severity, and brand constraint. The workflow retrieved only the policy relevant to the seller’s context, so a low-risk product did not inherit the full friction required for a tightly regulated category.

The FTC’s advertising guidance shaped the claim model: advertisements must be truthful, non-deceptive, and supported by evidence, including both explicit and implied claims. I treated substantiation as an input to creation rather than a document requested after the copy was finished.

I replaced silent correction with visible coaching. When the system found a problem, it explained the issue in plain language, showed the relevant constraint, suggested a safe alternative, and preserved as much of the original creative as possible. That made policy legible and reduced the incentive to work around it.

## The human and machine boundary

I did not automate every judgment. High-confidence, high-severity violations were blocked. Ambiguous cases went to trained reviewers with the relevant evidence and policy context attached. Lower-risk categories received lighter controls.

This confidence-based design reduced false positives while keeping human expertise focused on genuinely difficult decisions. It also created a feedback loop: reviewer dispositions improved rules, examples, and seller guidance instead of disappearing into an operations queue.

## The validation ladder

I staged the evidence deliberately:

1. I replayed 10,000 historical ads to test coverage and obvious regression.
2. I piloted with 500 sellers to observe comprehension, appeal behavior, and workflow friction.
3. I ran a 5,000-ad shadow comparison before allowing automated enforcement.
4. I monitored rejection, false positives, launch time, appeals, and ROAS by category after release.

Each stage had an explicit stop condition. I did not treat a successful offline replay as proof that sellers would understand the guidance or that constrained creative would still perform.

## What changed

| Outcome | Result |
|---|---:|
| Ad rejection | 18% to 1.8% |
| False-positive rate | Approximately 1.4% |
| Compliant launch time | Five–seven days to under one hour |
| ROAS in constrained high-risk categories | More than +40% |
| ROAS in standard categories | No material decline |

The workflow made compliance commercially useful: it reduced delay, protected trust, and improved performance in the categories where unconstrained generation carried the most risk.

## Scope and attribution

I limit this project to AI-assisted copy and static assets. I do not extend the work to later autonomous or video-generation capabilities, and I do not attribute later market projections to these results.

## Sources and external context

The sources below formed the legal and AI-risk foundation. The resume link establishes the employment timeline.

| Source | How it informed my work | Timing |
|---|---|---|
| [Federal Trade Commission — Advertising and Marketing Basics](https://www.ftc.gov/business-guidance/advertising-marketing) | I used it to define truthful, non-deceptive, evidence-based advertising as a product requirement. | Longstanding FTC guidance |
| [Federal Trade Commission — Advertising FAQs for Small Business](https://www.ftc.gov/business-guidance/resources/advertising-faqs-guide-small-business) | I used it to distinguish express and implied claims and to make substantiation available before publication. | Longstanding FTC guidance |
| [NIST — Generative AI Profile](https://doi.org/10.6028/NIST.AI.600-1) | I used it to structure lifecycle risk, evaluation, human oversight, and monitoring. | 2024 |

