# Positioning augmented reality as pre-purchase evidence

I led the global go-to-market work for an augmented-reality shopping product during my Microsoft tenure. I saw that home-category customers could not judge whether an expensive item would fit or look right from flat product images. I worked with shoppers, merchants and 3D-asset partners, category and commerce teams, product design, computer-vision and mobile engineers, accessibility and privacy specialists, marketing, finance, logistics, and regional leaders.

## I refused to launch “innovation”

Furniture returns in the retained record reached 25–30%. Interviews found customers using masking tape, color swatches and mental arithmetic to judge scale, clearance, lighting and room harmony.

I positioned AR as verification before purchase: “View in Room” should answer a consequential question at the point of doubt. If it could not improve confidence about fit, clearance or appearance, visual novelty and time spent in the experience were irrelevant.

My commercialization remit covered three markets that exposed different physical-product risks, the trust and accessibility gates, the merchant and 3D-asset supply chain, AR's place in the purchase journey, and the connection from return economics to a modeled revenue opportunity above $50 million. The launch therefore had to scale content, customer proof, device performance, and reverse logistics together.

That proposition aligned teams around four proofs:

1. spatial placement was accurate and stable enough for the named decision;
2. the experience worked across eligible rooms, lighting, devices and users—or failed plainly;
3. merchants could supply enough governed 3D assets for a useful category; and
4. exposure changed purchase quality, not just curiosity.

## One sofa defined the trust contract

More than 50 interviews led to a 90-day, single-sofa prototype. The source says “millimeter accuracy” became a launch gate, but retains no measurement protocol or result. Consumer mobile AR across camera calibration, surfaces, lighting and motion cannot be assumed millimeter-accurate from that phrase. I treat it as an aspirational placement standard and would report measured scale and pose error by device and distance.

The quality gate needed physical dimensions and coordinate origin from the merchant; validated units and bounding box; plane detection and tracking confidence; occlusion behavior; relocalization after movement; asset scale, texture and polygon limits; device frame rate and crash rate; and a warning or manual-dimension fallback when the environment was unsuitable.

An accessible product page with exact dimensions, diagrams and usable 2D content remained essential for customers who could not or did not want to use camera AR. AR enhanced evidence; it did not become the only route to it.

## Three cities tested three physical products

Tokyo exposed compact rooms, tight corners and the importance of small-space specifications. Berlin exposed how room orientation and light changed fabric perception. Chicago exposed longer tracking distances in open plans.

Local teams and representative customers tested placement, occlusion, lighting, device performance, error recovery, confidence and buying context—not simply translation. The platform stayed common while environment-specific behavior and content requirements became launch evidence.

Research by Hilken and colleagues on [AR, perceived risk and customer decision comfort](https://pubmed.ncbi.nlm.nih.gov/36706429/) supported the mechanism: spatially embedding a product may improve decision processes by reducing uncertainty. I used that as an external hypothesis, not as proof of this product’s effect.

## The asset supply chain was part of go-to-market

No catalog coverage meant no customer utility, but merchants had little reason to fund models before seeing demand. I subsidized an early set and wrote partner acceptance criteria for:

- source photography or CAD rights and product-version match;
- real-world dimensions and scale origin;
- geometry, texture, color and material fidelity;
- GLB/USDZ packaging and device performance;
- category and regional metadata; and
- correction, expiration and replacement ownership.

The source reports 9% higher sales on AR-enabled SKUs. I used that evidence to recruit more merchants, while acknowledging selection: enabled products and early partners may have been unusually important, digitally mature or well promoted.

## Distribution could not tax every shopper

“View in Room” sat beside the product image where a customer questioned fit. The engine and asset lazy-loaded only after request. A feature flag, daily build, device-level crash monitoring and 200-millisecond time-to-interactive budget protected the core page. A low-end Android problem triggered a recorded 48-hour hotfix.

The 200 milliseconds was a budget, not a retained achieved percentile. I would measure page performance for eligible and non-eligible users, AR startup, model load, frame stability, crash-free sessions and abandonment by device. A conversion feature that slowed every product page could destroy more value than it created.

## Commercial account with selection made explicit

| Measure | Baseline | Recorded result | What the claim requires |
|---|---:|---:|---|
| Category returns | 25–30% | 25% lower | likely relative reduction, implying 18.75–22.5% if the same cohort; exact category, window and reason-coded returns absent |
| Conversion among AR-engaged users | comparison group | 40% higher | strongly self-selected; incremental effect requires randomized invitation or credible instrument |
| Sales on AR-enabled SKUs | pre/other SKU comparison | 9% higher | control for SKU selection, season, placement, promotion, inventory and category |
| Time on page | baseline index 100 | index 150 | 50% higher; diagnostic engagement, not value on its own |
| Annual revenue contribution | model baseline absent | >$50M | attribution and recognition method absent; present as annualized program estimate, not proven incremental revenue |
| Reverse-logistics savings | baseline absent | >$5M/year | requires avoided returns × loaded handling, freight, damage and resale costs; model, not necessarily booked saving |

The engaged-user conversion, enabled-SKU sales and return result may all share the same underlying purchases. I do not add them into separate revenue pools. The strongest outcome is the combined purchase-quality hypothesis supported by several imperfect measures.

## Provenance and ownership

The retained page does not name the retailer, commerce platform or Microsoft product. This portfolio assigns the project to my Microsoft role, so I preserve the employment period but do not attach public Microsoft product reach or claim that Microsoft itself booked the $50 million.

I owned the category position, customer research, market selection, launch gates, merchant value proposition, partner content system, point-of-doubt distribution, scorecard and financial story. Engineering owned spatial implementation. Merchants owned product truth and assets. Regional teams owned local evidence. Finance and logistics owned realized economics.

The strategic marketing insight was that immersive technology became commercially credible only when the launch promise was a verifiable customer decision, supported by an asset supply chain and a performance contract—not a futuristic demo.
