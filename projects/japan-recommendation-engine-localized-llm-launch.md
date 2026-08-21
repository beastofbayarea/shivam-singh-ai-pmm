# Japan Recommendation Engine — Localized LLM Launch

I completed this work during my [Rakuten experience from June to December 2023](https://github.com/beastofbayarea/shivam-singh-ai-pmm/blob/main/shivam-singh-ai-pmm.pdf).

## Why the global launch failed its local test

The central team wanted feature parity before a major gifting season. Shadow testing in Japan showed that the product was not ready: respectful language was inconsistent, Kanji tokenization fragmented meaning, recommendations missed local context, latency was roughly three times higher, and regional data-flow requirements were unresolved.

I turned the debate from “global consistency versus local preference” into a launch-readiness decision. The criteria were customer quality, latency, commercial performance, compliance, and whether the solution could become a reusable platform pattern.

## The decision to delay

I secured a six-week delay because the evidence showed a greater risk in launching a visibly inferior experience than in missing the original date. The delay was bounded by named deliverables and a decision calendar; it was not an open-ended localization request.

Native-language reviewers received authority over customer-quality gates. I embedded Tokyo engineers with the central platform team so localization did not become a downstream handoff. That operating choice resolved a recurring source of conflict: the people closest to the customer could influence architecture, while the central team retained ownership of the common platform.

## The regional adaptation layer

I kept one global platform and separated the parts that genuinely needed local treatment:

- a Japanese language adapter and evaluation set;
- an optimized tokenizer for Japanese text;
- local catalog, availability, and recommendation signals;
- regional data handling and residency controls;
- native review and correction workflows.

SentencePiece research was directly relevant because it demonstrated language-independent subword training on raw text and evaluated English–Japanese translation. METI’s AI governance guidance helped me connect local quality and accountability to a broader management system rather than treating them as isolated model fixes.

When sovereignty requirements surfaced, I kept restricted data in market and accepted a two-week adjustment. That decision protected the launch from a fragile cross-region exception that would have been harder to unwind later.

## The evidence gates

I sequenced native review, shadow mode, purchase comparison, controlled ramp, and full launch. I used an automated rollback trigger at 0.5% negative customer experience so customer harm—not schedule pressure—determined whether the ramp continued.

The scorecard separated language quality, recommendation relevance, latency, commercial behavior, and operational incidents. This made it possible to see whether a local improvement simply moved the problem elsewhere.

## The outcome

| Outcome | Result |
|---|---:|
| Downstream commercial impact | +14% |
| Inference latency | -20% |
| Negative-customer-experience rollback threshold | 0.5% |
| Platform consequence | Reusable regional adaptation pattern |

The commercial gain mattered, but the durable result was architectural. The team gained a repeatable way to launch a common AI platform without pretending that language, behavior, data, and governance were globally interchangeable.

## What I carried forward

I learned to define localization as product quality and operating accountability, not translation. I also learned that centralization works best when the platform standardizes infrastructure and the market owns evidence about local customer behavior.

## Sources and external context

These sources informed the language and governance design. The resume link establishes the work period.

| Source | How it informed my work | Timing |
|---|---|---|
| [METI — Governance Guidelines for Implementation of AI Principles, version 1.1](https://www.meti.go.jp/shingikai/mono_info_service/ai_shakai_jisso/20220128_report.html) | I used it to connect local AI quality, accountability, and risk management to organizational governance. | 2022 |
| [Kudo and Richardson — SentencePiece](https://arxiv.org/abs/1808.06226) | I used it to ground language-independent subword tokenization and the Japanese-language adaptation decision. | 2018 |
| [NIST — AI Risk Management Framework 1.0](https://doi.org/10.6028/NIST.AI.100-1) | I used it to structure risk mapping, measurement, management, and governance across the launch lifecycle. | 2023 |

