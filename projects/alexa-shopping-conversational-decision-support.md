# Alexa Shopping — Conversational Decision Support

I completed this work during my [AWS experience from July 2024 to present](https://github.com/beastofbayarea/shivam-singh-ai-pmm/blob/main/shivam-singh-ai-pmm.pdf).

## The product decision

I inherited a shopping assistant that could hold an interesting conversation but did not consistently help customers make a purchase decision. When I reviewed roughly 100,000 interactions, I found a 40% drop-off at the moment people had to leave the conversation and return to traditional search and filters. The handoff broke context, while unverified specifications and a clinical interface weakened trust.

I changed the proposition from “chat about products” to “reach a confident shortlist.” That distinction gave the experience a job: narrow a large catalog to three to five credible options, explain the trade-offs, and keep the customer in control of every transactional step.

## The signal that changed the roadmap

Conversation volume was the wrong success measure. A long session could mean engagement, confusion, or repeated failure. I centered the roadmap on decision quality instead:

- Did the assistant retrieve current facts rather than improvise them?
- Did the shortlist reflect the customer’s stated constraints?
- Could the customer understand why one option differed from another?
- Did the experience preserve context through comparison and confirmation?
- Did the customer choose to continue toward purchase?

This reframing let Product, Science, Design, Brand, and Commerce evaluate the same customer outcome instead of optimizing separate proxy metrics.

## The experience I launched

I separated facts from reasoning. Live retrieval supplied catalog attributes, price, availability, and review evidence; the model organized that evidence into comparisons and explicit trade-offs. I rejected static model memory for fast-changing commerce facts because a fluent answer with stale inventory or an invented specification was worse than no answer.

I added contextual memory so customers did not have to repeat budget, use case, or preferences. I introduced task-specific prompts at moments of hesitation rather than opening every session with an unbounded chat box. Before any purchase-related action, the experience returned control to the customer through a visible review and confirmation step.

Amazon Science’s work on question suggestion for conversational shopping assistants reinforced the importance of grounding useful prompts in product metadata rather than generating generic conversation starters. The retrieval-augmented generation research from Lewis and colleagues provided the architectural rationale for pairing generation with updateable external knowledge.

## How I tested adoption and trust

I selected a 15,000-user cohort of frequent shoppers because they had enough category familiarity to expose weak comparisons and enough usage to generate a meaningful adoption signal. I reviewed hallucination, shortlist acceptance, follow-on exploration, session depth, and qualitative trust feedback together.

I also treated brand perception as a commercial input, not a vanity metric. The increase in innovation favorability supported a GMV-linked business case, which helped me secure $5M in funding for the next stage.

## What changed

| Outcome | Result |
|---|---:|
| Feature adoption | 25% |
| Session depth | +15% |
| Hallucination rate | 2.8% |
| Innovation favorability | 55% to 70% |
| Funding secured | $5M |

The most important result was that the assistant had a defensible role in the shopping journey. It helped customers compare and decide without pretending that generation itself was the product.

## What I carried forward

I learned to define the customer decision before defining the AI experience. I also kept three operating rules: retrieve volatile facts, expose trade-offs rather than hide them, and require explicit confirmation before a system moves from advice to action.

## Sources and external context

The sources below informed the product and risk approach. The resume link establishes the employment timeline.

| Source | How it informed my work | Timing |
|---|---|---|
| [Amazon Science — Question Suggestion for Conversational Shopping Assistants Using Product Metadata](https://assets.amazon.science/42/6e/c7c7aed9433d87fd1ab1f8bef4ff/question-suggestion-for-conversational-shopping-assistants-using-product-metadata.pdf) | I used it to connect conversational prompts to grounded product context and real shopping questions. | 2023 |
| [Lewis et al. — Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401) | I used it to separate updateable evidence retrieval from generative reasoning. | 2020 |
| [NIST — Generative AI Profile](https://doi.org/10.6028/NIST.AI.600-1) | I used it to structure evaluation around reliability, transparency, human oversight, and harmful failure modes. | 2024 |

