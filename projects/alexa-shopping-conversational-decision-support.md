# Turning a shopping conversation into a defensible shortlist

I led product marketing and proposition work for an Amazon conversational-shopping experience during my AWS tenure. I saw that customers enjoyed asking questions but lost context when they had to return to search and filters to decide. I worked with shoppers, retail category and commerce teams, product and design, applied science, engineering, brand, legal and trust partners, finance, and Amazon leaders.

## Conversation was not the job

Review of roughly 100,000 interactions found a 40% drop-off when customers left the assistant for traditional search. The initial experience also risked citing stale specifications, price or availability and felt separate from the marketplace.

I changed the proposition from “chat about products” to “reach a confident shortlist.” The experience had to turn stated constraints into three to five eligible options, show meaningful differences, preserve context, and give the customer final control over any cart or purchase action.

My category decision defined what the assistant would help a shopper decide, what commerce evidence it had to show, where generation ended, and which adoption and trust signals justified another $5 million of investment. That united product truth, customer behavior, launch positioning, and the funding case around one accountable job rather than treating conversation volume as product-market fit.

That definition changed the competitive frame. We were not trying to create a more entertaining chatbot. We were reducing the effort and uncertainty between broad consideration and a customer-owned choice.

## The promise required an evidence contract

I separated volatile commerce facts from generative explanation:

`customer need → retrieve eligible products → rank under stated constraints → compare evidence → customer confirms action`

Catalog attributes, current price, inventory and delivery came from live systems. Review summaries remained attributed customer evidence, not objective product facts. The model could organize and explain the retrieved evidence but could not invent a specification or silently substitute an unavailable item.

Every comparison carried the current option, source time, key constraint match, trade-off and unavailable evidence. If a fact was missing or conflicting, the assistant said so or asked a narrowing question. Contextual memory retained budget, intended use and preferences for the journey, with a visible way to correct or clear them.

The architecture follows the retrieval/generation separation described in [Lewis et al.’s RAG paper](https://arxiv.org/abs/2005.11401). Amazon Science’s 2023 paper on [question suggestion using product metadata](https://assets.amazon.science/42/6e/c7c7aed9433d87fd1ab1f8bef4ff/question-suggestion-for-conversational-shopping-assistants-using-product-metadata.pdf) supports task prompts grounded in the product page rather than generic conversation starters. These are technical and research references, not evidence of personal ownership.

## I marketed three moments, not one assistant

**Narrow.** A customer with a large result set received a small, diverse set meeting hard constraints. Ranking did not present near-identical sponsored or popular products as meaningful choice.

**Compare.** “Help me decide” translated features into the customer’s use—low-light camera performance, apartment fit, repairability, delivery certainty—while preserving price and other factual trade-offs.

**Prepare to act.** The customer could select the item and variation in the conversation, then review the exact product, seller, price, delivery, quantity and return context before confirming a cart action. The assistant did not purchase on an inferred preference.

Task prompts appeared after evidence of hesitation on a product page rather than as an unbounded chat invitation. That distribution choice made the proposition legible at the decision point.

## The launch cohort was useful but biased

I began with 15,000 frequent shoppers who visited at least 12 times per month. They had enough category experience to find weak comparisons and enough activity to produce repeated observations. They were not representative of all customers; novelty, comfort with Amazon and baseline purchase intent were probably higher.

The scorecard joined:

- factual-error rate by claim type and source freshness;
- hard-constraint satisfaction and eligible-item coverage;
- shortlist acceptance, comparison completion and correction;
- return to search, cart continuation and confirmed action;
- session depth interpreted beside task completion; and
- customer-reported usefulness, confidence and brand perception.

A longer session alone was not success. It could mean helpful comparison or repeated failure.

## Results and missing denominators

| Measure | Baseline | Recorded result | Defensible interpretation |
|---|---:|---:|---|
| Search-handoff drop-off | 40% | final rate absent | central baseline; the source does not report whether the redesign closed it |
| Feature adoption | not retained | “25%” and “increased 25%” both appear | unresolved rate-versus-relative-lift ambiguity; eligible exposure denominator required |
| Session depth | baseline index 100 | index 115 | 15% increase; useful only with completion and correction outcomes |
| Hallucination | baseline absent | 2.8% | taxonomy, claim denominator, severity, human review and confidence interval absent |
| Innovation favorability | 55% | 70% | +15 percentage points and +27.3% relative; survey sample and wording absent |
| Expansion funding | request not retained | $5M secured | authorized investment, not product revenue or GMV |

The source links the favorability change to more than $100 million of potential incremental GMV. That is a scenario used in the business case, not a realized result. Without the adoption population, purchase incrementality, order value, cancellation and return behavior, I do not promote it to impact.

## Public product and attribution boundary

Amazon publicly introduced [Rufus in February 2024](https://www.aboutamazon.com/news/retail/amazon-rufus) as a generative-AI shopping assistant for questions, comparisons and recommendations. That announcement predates the July 2024 start of my stated AWS role and describes Rufus, while the retained project title says Alexa Shopping. I therefore do not claim to have launched Rufus or treat its public reach as my result.

The portfolio assigns this consumer-Amazon project to my AWS tenure. I describe it as cross-Amazon work during that period, not as an AWS product. Contemporaneous internal records would be needed to reconcile the Alexa/Rufus naming, role, launch date and outcome metrics.

I owned the proposition, audience and decision-journey research, evidence hierarchy, launch narrative, adoption design, trust scorecard and funding case. Product and science teams owned ranking and model implementation. Commerce teams owned catalog and transaction truth. Customers retained purchase authority. The defensible strategic contribution is a sharper category: conversational decision support grounded in current commerce evidence, not conversation for its own sake.
