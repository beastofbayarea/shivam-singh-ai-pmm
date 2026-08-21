# Refusing to market translation as a Japan-ready recommendation product

I led the Japan launch plan for a language-model recommendation experience during my Rakuten internship. I saw that the global model spoke Japanese without understanding how customers used respectful language, gifts, loyalty points, product terms, and local delivery. I worked with Japanese shoppers, native reviewers, Tokyo product and engineering teams, the central platform group, merchandising and operations, legal and information-security partners, marketing, finance, and executives.

## The launch memo had four “no” decisions

**No to feature parity as readiness.** Shadow traffic showed inconsistent Keigo, inefficient Kanji segmentation, weak Oseibo and poi-katsu relevance, and latency roughly three times the comparison platform.

**No to a separate Japan product.** Forking the whole stack would improve local control and create permanent model, monitoring and release divergence.

**No to translation-only evaluation.** A translated global test set could miss register, gifting relationship, terminology, availability and delivery expectations.

**No to an open-ended delay.** I secured a six-week postponement tied to a Japan adapter, tokenization work, native evaluation, regional data-flow decision, shadow comparison, capacity proof and a controlled launch date.

This changed the stakeholder argument from central speed versus local preference into an evidence-based question: what must be true for the Japanese customer experience to earn the common brand?

Within the reconstructed record, I owned that market-readiness decision end to end: the six-week executive delay, the central-versus-Tokyo operating boundary, native-language authority, regional data handling, shadow evaluation, peak-capacity proof, rollback rule, and the commercial evidence required to reopen launch. The scope was not localization copy; it was whether a global AI platform could operate credibly as a Japan product without creating a permanent fork.

## Global platform, local authority

Tokyo engineers worked directly in the central team rather than submitting localization tickets after core decisions. The common layer retained model serving, monitoring, deployment and shared behavior contracts. The Japan layer owned:

- language adaptation and subword tokenization;
- Keigo, domain terminology and gifting evaluation;
- regional catalog, inventory, delivery and loyalty signals;
- local correction and native-review workflow; and
- approved regional data handling.

[SentencePiece](https://arxiv.org/abs/1808.06226) was a relevant technical reference because it trains subword models from raw text without requiring language-specific pre-tokenization and included English–Japanese evaluation. It did not by itself guarantee better recommendations or respectful language; tokenizer choice had to be measured through sequence length, unknown or fragmented terms, latency and downstream task quality.

## Native evaluation was part of the launch message

Reviewers graded linguistic correctness, relationship-appropriate respect, cultural and gifting fit, product relevance, source availability and harmful or confusing output. Their decisions carried launch authority, not advisory status.

The model then ran in shadow mode on live eligible traffic without exposing recommendations. The team compared ranking with later purchase behavior, negative-customer-experience signals, latency and capacity. A controlled ramp began before the Oseibo period with named on-call and rollback ownership.

Negative customer experience above 0.5% triggered rollback. That is a policy threshold, not a recorded result. A launch account must also show the observed NCX rate, severity mix, denominator and time window.

## Data location was not a footnote

The first plan would have moved Japan data into a US environment. Legal and information-security review concluded that some restricted data should remain in Tokyo, and the team created a regional training or processing flow. The source records a two-week adjustment but does not say whether it sat inside or after the six-week launch delay; I do not add them into an asserted eight-week delay.

“Kept in Tokyo” also does not prove compliance. The evidence package needed data classification, purpose, transfer decision, identity and access, retention, deletion, lineage, processor/subprocessor understanding and approved operational ownership.

METI’s 2022 [AI-governance guidance](https://www.meti.go.jp/shingikai/mono_info_service/ai_shakai_jisso/20220128_report.html) provided contemporaneous Japanese context for organization-wide governance, monitoring and stakeholder communication. [NIST AI RMF 1.0](https://doi.org/10.6028/NIST.AI.100-1), released in January 2023, supplied another external govern-map-measure-manage structure. Neither is a certification.

## What the launch evidence supports

| Measure | Baseline | Gate or target | Recorded result | Interpretation |
|---|---:|---:|---:|---|
| Inference latency | about 3× comparison | peak-ready local experience | 20% lower | if measured against the Japan baseline on the same boundary, still about 2.4× comparison; improvement is not parity |
| Downstream commercial impact | baseline index 100 | positive versus shadow/control | index 114 | +14%; metric could be conversion, sales or another downstream measure—the source does not say |
| Negative customer experience | baseline absent | automatic rollback above 0.5% | observed result absent | operational guardrail only |
| Primary schedule | original date | bounded localization | 6-week delay | tied to named deliverables |
| Data-flow adjustment | original US flow | approved regional flow | 2-week adjustment | relationship to six-week delay unresolved |

The absence of language-review scores, token-count reduction, final NCX, adoption, conversion definition and revenue prevents a stronger quantitative launch claim. I would not turn “+14% downstream impact” into sales or revenue without the metric contract.

## Company attribution is not resolved by the source

The retained page contains an explicit instruction that the story “can sit under Amazon/AWS or Rakuten” and that only the product context should be swapped while the architecture and metrics remain unchanged. That makes it a reusable interview composite, not a company-specific primary record.

This portfolio assigns it to my Rakuten internship, and Rakuten did publicly announce an [OpenAI collaboration in August 2023](https://global.rakuten.com/corp/news/press/2023/0802_01.html) to explore conversational AI for consumers and businesses in Japan and globally. That supports the company and market context, but it does not verify this recommendation launch, its metrics or my ownership.

I have kept the Rakuten assignment while disclosing the limitation. Before using this as a factual interview story, the original roadmap, Japan experiment, metric definition or launch record should replace the interchangeable source.

My reconstructed ownership is the Japan proposition, launch criteria, delay case, central/local decision rights, evaluation narrative, controlled ramp and evidence account. Native reviewers owned language judgment; engineers owned implementation; legal and information security owned data decisions; business owners owned commercial results. The durable PMM lesson is defensible even where attribution is not: a global AI brand promise must be earned in the customer’s language, market behavior and operating constraints—not translated into them after the platform is declared ready.
