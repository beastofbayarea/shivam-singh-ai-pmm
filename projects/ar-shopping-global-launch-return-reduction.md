# Positioning augmented reality as pre-purchase evidence

Furniture returns were running at 25–30%, and customer interviews made the failure tangible: shoppers were using masking tape, color swatches, and mental arithmetic to decide whether a high-consideration item would fit, clear a doorway, or look coherent in a room.

I led the global go-to-market design for an augmented-reality shopping product during my Microsoft tenure. My remit combined customer proposition, market sequencing, merchant economics, 3D-content supply, trust and accessibility, mobile performance, and the value case connecting purchase confidence to a modeled opportunity above $50 million.

## The launch promise

I refused to market novelty. “View in Room” had one commercial job: give a shopper better evidence at the moment physical uncertainty threatened the purchase.

That promise created four non-negotiable gates:

1. **Decision fidelity:** placement, scale, and stability had to be accurate enough for the named customer judgment.
2. **Reach without hidden harm:** the core product page could not slow down for every shopper, and unsupported devices or rooms needed an honest fallback.
3. **Catalog usefulness:** merchants and 3D partners had to supply enough governed assets for an actual category experience.
4. **Purchase quality:** success required better conversion and fewer avoidable returns, not more time spent playing with AR.

I used more than 50 interviews to concentrate a 90-day prototype on one sofa. That single object exposed nearly every dependency: physical dimensions, coordinate origin, surface detection, occlusion, color and material fidelity, lighting, frame stability, device constraints, and customer interpretation.

The retained source calls “millimeter accuracy” a gate but contains no protocol or achieved result. I translated that aspiration into measurable scale and pose error by device, distance, lighting, surface, and movement. When confidence fell below the supported range, the interface warned the user or reverted to exact dimensions and accessible 2D diagrams. Camera AR enhanced the evidence; it never became the only route to it.

## Three cities, three different reasons to fail

I chose Tokyo, Berlin, and Chicago because each made a different part of the proposition falsifiable.

- Tokyo stressed compact rooms, tight clearance, small-space product specifications, and local buying context.
- Berlin exposed changes in fabric perception caused by room orientation and light.
- Chicago tested tracking stability over longer distances in open-plan rooms.

Regional teams and representative customers evaluated placement, error recovery, device behavior, confidence, and purchasing relevance—not merely translated labels. The shared engine remained global; environmental evidence and content acceptance stayed local.

Research on [AR, perceived risk, and decision comfort](https://pubmed.ncbi.nlm.nih.gov/36706429/) supported the mechanism that spatial representation can reduce uncertainty. I used it to frame a hypothesis, not to substitute for product evidence.

## The merchant supply chain was part of the product

Customer value collapsed if the catalog contained only a handful of showcase SKUs. Merchants, however, had little reason to fund 3D models before demand was visible. I broke that deadlock by subsidizing an initial portfolio and creating an acceptance contract covering:

- CAD or photography rights and exact product-version match;
- real-world dimensions, units, scale origin, and bounding box;
- geometry, texture, material, and color fidelity;
- GLB/USDZ packaging and mobile-performance limits;
- category and regional metadata; and
- correction, expiration, and replacement ownership.

The early record showed 9% higher sales on AR-enabled SKUs. I used that signal to recruit the next merchant cohort while explicitly accounting for selection: early partners and enabled products were likely more important, digitally mature, or heavily promoted than the average SKU.

## Distribution protected the base business

“View in Room” appeared beside the product image where a shopper was already evaluating fit. The engine and model loaded only after request. A feature flag, daily builds, device-level crash monitoring, and a 200-millisecond page-interactivity budget protected customers who never opened AR. A low-end Android regression triggered a 48-hour hotfix.

The 200 milliseconds was a target, not a retained achieved percentile. The operating dashboard needed core-page performance for both eligible and ineligible users, AR startup time, asset load, frame stability, crash-free sessions, and abandonment by device. A conversion feature that degraded every visit would have destroyed more value than it created.

## The economic proof, with attribution intact

| Business mechanism | Baseline → target → recorded result | How it was or should be measured |
|---|---|---|
| Avoid wrong-fit purchases | 25–30% category return rate → material reduction → 25% lower | Reason-coded returns for comparable exposed/control orders; if relative, implied rate is 18.75–22.5% |
| Improve purchase confidence | comparison cohort → positive incremental conversion → 40% higher among AR-engaged shoppers | Randomized invitation or intent-matched exposure; engaged-user comparison alone is self-selected |
| Increase enabled-SKU sales | pre/other SKU baseline → positive lift → 9% higher | Control for SKU choice, inventory, placement, promotion, season, and category |
| Avoid page harm | current page performance → ≤200 ms incremental TTI budget → achieved percentile not retained | Real-user monitoring by device and eligibility |
| Create program value | model baseline absent → >$50M annual contribution → modeled >$50M | Incremental orders and margin net of returns, content, support, and device-performance costs |
| Reduce reverse logistics | baseline absent → meaningful avoided cost → modeled >$5M/year | Avoided returns × loaded freight, handling, damage, and resale loss |

These measures share purchases and cannot be added as independent value pools. The strongest case was a coherent mechanism—better physical evidence improving conversion while reducing wrong-fit returns—supported by several imperfect signals.

I owned the customer problem definition, global proposition, city selection, launch and accessibility gates, asset-partner value proposition, merchant recruitment logic, point-of-doubt distribution, scorecard, and financial narrative. Engineering owned spatial implementation; merchants owned product truth; regional teams owned local evidence; finance and logistics owned realized economics.

The retained page does not identify the retailer or product, so I do not attach public Microsoft commerce scale to the result. The durable achievement was turning AR from an innovation demo into a governed purchase-quality system: customer proof, catalog operations, mobile reliability, and return economics had to scale together.
