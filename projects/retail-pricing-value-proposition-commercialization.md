# Retail Pricing — Value Proposition and Commercialization

I completed this work during my [McKinsey experience from July 2014 to June 2016](https://github.com/beastofbayarea/shivam-singh-ai-pmm/blob/main/shivam-singh-ai-pmm.pdf).

## The commercialization problem

The retailer did not simply need a more accurate model. Essentials were overpriced, niche items left margin unused, and historical data contained too little price movement to reveal credible demand response. Even after the analytical work improved, merchant distrust nearly stopped adoption.

I treated commercialization as a product challenge: create causal evidence, translate it into a pricing architecture, make each recommendation understandable, and give merchants a controlled way to disagree.

## Creating evidence where history had none

Static historical prices could not answer what happened when price changed because price had rarely changed. I designed randomized, stratified store tests with A/A checks, power calculations, staggered windows, difference-in-differences, and spillover controls.

I used the tests to estimate elasticity and to expose where the model was fragile. Hindcasting over prior periods provided an additional release gate. I did not present 95% forecast accuracy as universal certainty; I used it as evidence that the model was decision-ready within the tested operating conditions.

The World Bank’s impact-evaluation guidance informed the counterfactual design. McKinsey’s contemporaneous retail-pricing research helped connect elasticity to category roles, customer perception, competitive behavior, and value creation.

## Turning elasticity into a pricing architecture

I segmented products by the role they played in the customer’s basket and perception of value:

- key-value items, where visible price trust mattered most;
- basket builders, which influenced broader purchase behavior;
- core products, where balanced revenue and margin decisions applied;
- long-tail items, where willingness to pay could support more margin;
- heritage products, where brand and customer expectations constrained movement.

This kept the system from optimizing every SKU independently. A mathematically attractive price on one item could still damage basket economics, customer trust, or brand position.

## Making the recommendation usable

Each recommendation included plain-language rationale, confidence, price history, customer and brand guardrails, and a reason-coded override. I capped weekly price movement at plus or minus 5% and protected highly visible products.

I reorganized merchant, data-science, and marketing work into weekly outcome pods. Merchants reviewed recommendations, recorded disagreement, and fed local knowledge back into the system. That shifted overrides from unstructured resistance into governed learning.

## The outcome

| Outcome | Result |
|---|---:|
| Estimated revenue opportunity | $50M |
| Forecast accuracy in the validated scope | 95% |
| Local price-change execution | Six weeks to under one |
| Merchant overrides | Below 5% by month two |

The reduction in overrides was the clearest commercialization signal. The model became useful because merchants could understand it, challenge it, and see their decisions reflected in the next cycle.

## The choices I protected

I required causal evidence before commercializing recommendations from static historical data. I optimized portfolio and basket economics rather than treating every SKU as independent. I also preserved customer and brand guardrails even when a local margin calculation suggested more aggressive movement.

## Sources and external context

These sources informed the pricing and evaluation methodology. The resume link establishes the work period.

| Source | How it informed my work | Timing |
|---|---|---|
| [McKinsey — Pricing in retail: Setting strategy](https://www.mckinsey.com/industries/retail/our-insights/pricing-in-retail-setting-strategy) | I used it to connect elasticity, category roles, customer price perception, and risk management. | 2015 |
| [World Bank — Impact Evaluation in Practice](https://www.worldbank.org/en/programs/sief-trust-fund/publication/impact-evaluation-in-practice) | I used it to structure randomized tests, comparison groups, counterfactual reasoning, and interpretation. | Methodology available during the work period |

