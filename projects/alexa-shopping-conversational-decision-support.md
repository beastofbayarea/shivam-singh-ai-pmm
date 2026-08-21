# Turning a shopping conversation into a defensible shortlist

The product question was not whether an assistant could talk about products. It was whether it could remove enough uncertainty for a shopper to make a better decision without surrendering control.

During my AWS tenure, I led the proposition, audience strategy, decision-journey research, launch logic, trust scorecard, and funding case for a conversational-shopping experience spanning Amazon teams. The work crossed retail categories, commerce, product, design, applied science, engineering, brand, legal, trust, finance, and executive leadership.

## The category decision

A review of roughly 100,000 interactions showed 40% drop-off when a shopper left the assistant and returned to conventional search. The experience was attracting questions but not carrying the customer through comparison. It could also expose stale price, inventory, delivery, or specification information—exactly the facts on which a purchase depended.

I reframed the product from a chatbot into **conversational decision support**. Its job was to translate a shopper’s constraints into three to five eligible options, make the differences intelligible, and hand the final action back to the customer. That choice gave every team a shared outcome and made the next $5 million of investment contingent on decision quality, not conversation volume.

The operating contract was simple:

**stated need → eligible inventory → constraint-aware ranking → sourced comparison → explicit customer confirmation**

Generation could organize and explain. Live commerce systems remained authoritative for catalog attributes, current price, availability, seller, delivery, and return context. Review summaries stayed attributed opinion. Missing or conflicting facts were surfaced rather than smoothed over. Journey memory retained budget, intended use, and preferences only while giving the shopper a visible way to correct or clear them.

This separation follows the retrieval-and-generation pattern in [Lewis et al.’s RAG paper](https://arxiv.org/abs/2005.11401). Amazon Science’s research on [product-metadata question suggestion](https://assets.amazon.science/42/6e/c7c7aed9433d87fd1ab1f8bef4ff/question-suggestion-for-conversational-shopping-assistants-using-product-metadata.pdf) also informed the decision to place grounded prompts at moments of product-page hesitation. These references explain the design logic; they are not evidence of my ownership.

## I designed three commercial moments

**Narrowing** reduced a large result set to a deliberately diverse shortlist that met hard constraints. Popularity or sponsorship could not make near-identical products look like meaningful choice.

**Comparison** translated specifications into the shopper’s context—apartment fit, low-light camera use, repairability, delivery certainty—while keeping the underlying evidence visible.

**Preparation to act** allowed the shopper to choose a product and variation in conversation, then review the exact item, seller, price, delivery, quantity, and return context before a cart action. No inferred preference could trigger a purchase.

This positioning also settled a distribution dispute. Rather than promote an unbounded assistant as entertainment, I placed task prompts where behavior suggested unresolved choice. The product appeared at the decision point it was built to improve.

## The launch cohort was an instrument, not a market proxy

I chose 15,000 frequent shoppers with at least 12 visits per month. They generated repeated observations and could detect weak comparisons, but they also had higher Amazon familiarity and likely higher purchase intent than the general population. I treated the cohort as a stress test, not proof of broad-market adoption.

The measurement design joined factual correctness, constraint satisfaction, shortlist acceptance, comparison completion, correction behavior, return to search, cart continuation, confirmed action, and customer-reported confidence. Session depth was diagnostic: a longer session might signal either a useful comparison or repeated failure.

| Decision question | Baseline → target → recorded result | Measurement method |
|---|---|---|
| Did the experience preserve the shopping journey? | 40% search-handoff drop-off → materially reduce → final rate not retained | Eligible-session funnel from assistant exposure through search return, cart continuation, and confirmed action |
| Did customers adopt the decision workflow? | baseline not retained → positive repeatable use → “25%” / “increased 25%” recorded ambiguously | Exposed eligible users as denominator; separate absolute adoption from relative lift |
| Did engagement remain productive? | session-depth index 100 → rise only with completion → 115 | Pair duration/turns with task completion, corrections, and abandonment |
| Were generated claims controlled? | baseline absent → severity-weighted error within launch gate → 2.8% | Claim-level sampling by source freshness, category, severity, and human adjudication |
| Did the proposition strengthen brand perception? | 55% → improve → 70% | Consistent pre/post survey wording and sampling; +15 points, +27.3% relative |
| Was further investment earned? | request not retained → approved continuation → $5M secured | Executive funding decision tied to cohort evidence and an explicit scale plan |

The source also associated the favorability shift with more than $100 million of potential incremental GMV. I used that as a scenario in the business case, not a realized outcome: a defensible estimate would require exposed users, incremental purchase probability, order value, cancellation, returns, and persistence.

## What changed because I led it

Product and science teams still owned ranking and model implementation; commerce teams owned transaction truth; customers retained purchase authority. My contribution was to connect those separate accountabilities into a marketable product promise and an investable operating model. I defined the job, narrowed the experience, established the evidence hierarchy, selected the launch population, designed the adoption and trust account, and translated early proof into an expansion case.

Amazon publicly introduced [Rufus in February 2024](https://www.aboutamazon.com/news/retail/amazon-rufus). That announcement predates the July 2024 start of my stated AWS role and names Rufus while the retained project record says Alexa Shopping. I therefore present this as cross-Amazon conversational-shopping work during my AWS tenure, not as a claim that I launched Rufus.

The strategic outcome was larger than a feature message: the organization stopped treating fluent conversation as evidence of product-market fit. A shopping assistant earned the right to scale only when it helped a customer reach a current, explainable, customer-owned decision.
