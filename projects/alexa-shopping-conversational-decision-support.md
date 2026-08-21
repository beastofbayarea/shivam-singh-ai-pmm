# Alexa Shopping - Conversational Decision Support

> **Document type:** Externally grounded interview case reconstruction, not a claim of an independently verified completed engagement.
>
> **Timeline alignment:** The [public AI Product Marketing resume](https://github.com/beastofbayarea/shivam-singh-ai-pmm/blob/main/shivam-singh-ai-pmm.pdf) is used only to place this case within the AWS role dated July 2024-present.

## Evidence-grounded premise

Retrieval-augmented generation was introduced to combine model reasoning with an updateable external knowledge store and improve factual language on knowledge-intensive tasks. NIST's 2024 GenAI Profile requires risks to be governed, mapped, measured, and managed across the lifecycle. Together, these sources support a shopping proposition centered on current evidence, bounded recommendations, and customer control rather than unconstrained conversation.

## Case approach

- Retrieve current catalog, price, availability, and review evidence before generating comparisons.
- Constrain the assistant to shortlists and explicit trade-offs tied to retrieved evidence.
- Evaluate factuality, retrieval relevance, refusal behavior, and customer confirmation before transactional steps.
- Position the value around decision confidence and time saved, not novelty or conversation volume.

## Evidence-based success measures

Use citation coverage, unsupported-claim rate, task completion, shortlist usefulness, confirmation rate, and error recovery. These are proposed measures, not reported historical results.

## External source map

| Source | Contribution |
|---|---|
| [Lewis et al. - Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (2020)](https://arxiv.org/abs/2005.11401) | Primary technical basis for retrieval grounding, updateable knowledge, provenance, and factual generation. |
| [NIST - Generative AI Profile (2024)](https://doi.org/10.6028/NIST.AI.600-1) | Primary risk and evaluation framework for trustworthy GenAI deployment. |
| [Public resume](https://github.com/beastofbayarea/shivam-singh-ai-pmm/blob/main/shivam-singh-ai-pmm.pdf) | Work dates only. |
