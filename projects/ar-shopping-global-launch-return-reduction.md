# AR Shopping — Global Launch and Return Reduction

I completed this work during my [Microsoft experience from January 2020 to August 2022](https://github.com/beastofbayarea/shivam-singh-ai-pmm/blob/main/shivam-singh-ai-pmm.pdf).

## The commercial problem

Furniture shoppers were being asked to make high-value decisions from flat images. Returns reached 25–30% because customers could not reliably judge scale, clearance, lighting, or fit inside their own homes. I did not frame augmented reality as a novelty feature; I framed it as pre-purchase verification.

That choice changed the launch objective. The team was no longer trying to maximize AR opens. We were trying to improve purchase confidence, conversion, and return economics without making the underlying product page slower or harder to use.

## What I needed to prove

I organized the launch around four questions:

1. Could customers place an object accurately enough to trust the result?
2. Did the experience work across different homes, devices, lighting conditions, and accessibility needs?
3. Could merchants produce enough reliable 3D assets to make the feature useful at category scale?
4. Did better visualization change commercial behavior rather than simply attract curiosity?

Research on AR and consumer decision-making supported the underlying mechanism: putting a product into the customer’s physical context can reduce perceived risk and improve decision confidence. I used that mechanism as a hypothesis to test, not as proof of our own results.

## The three-city learning loop

I chose Tokyo, Berlin, and Chicago because the markets exposed different rooms, lighting conditions, devices, merchant capabilities, and customer expectations. The pilots were not a translation exercise. They forced the product to handle different occlusion behavior, spatial constraints, tracking quality, and presentation norms.

I prioritized millimeter-level placement accuracy before photorealistic effects. Customers could forgive a modest texture; they could not trust a sofa that appeared to fit when it did not. Market teams and representative users tested the full journey, including failure recovery and accessible alternatives, rather than reviewing isolated renders.

## Solving the catalog and performance constraints

The product had a cold-start problem: no useful experience without 3D assets, and little merchant incentive to create assets before the experience had demand. I subsidized early asset creation, added quality requirements to partner contracts, and built a repeatable merchant pipeline instead of treating every model as a custom production.

I also kept AR off the critical page-load path. The module was optional and lazy-loaded, governed by feature flags, crash monitoring, and a 200 ms performance budget. “View in Room” appeared beside the product imagery at the moment a customer was most likely to question fit.

## How I defined the rollout

I linked spatial quality, page performance, customer use, conversion, returns, and asset coverage in one scorecard. A market could expand only when the experience met technical and customer-confidence gates. This prevented a strong global average from hiding a weak device, category, or region.

## The outcome

| Outcome | Result |
|---|---:|
| Conversion among engaged users | +40% |
| Sales on AR-enabled SKUs | +9% |
| Returns | -25% |
| Annual revenue contribution | More than $50M |
| Annual reverse-logistics savings | More than $5M |

The result validated the positioning: AR created value when it reduced uncertainty at a consequential decision point. The same feature would have been much less useful if it had been placed as a detached innovation experience.

## What I carried forward

I learned to globalize the platform while localizing physical behavior. I also learned that an immersive feature needs a content-supply strategy and a performance contract before it needs a launch campaign.

## Sources and external context

These sources informed the research, accessibility, and customer-confidence approach. The resume link establishes the work period.

| Source | How it informed my work | Timing |
|---|---|---|
| [GOV.UK — How user research improves service design](https://www.gov.uk/service-manual/user-research/how-user-research-improves-service-design) | I used it to structure continuous research around observed user needs and complete journeys. | 2016 |
| [W3C — Web Content Accessibility Guidelines 2.1](https://www.w3.org/TR/2018/REC-WCAG21-20180605/) | I used it to keep accessibility requirements inside the interaction design and validation plan. | 2018 |
| [Hilken et al. — How Augmented Reality Increases Engagement Through Its Impact on Risk and the Decision Process](https://pubmed.ncbi.nlm.nih.gov/36706429/) | I used the research to frame contextual visualization, perceived risk, comfort, and confidence as testable mechanisms. | 2022 |

