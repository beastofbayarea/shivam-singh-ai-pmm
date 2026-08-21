# Japan Recommendation Engine — Localized LLM Launch

## What I worked on

I completed this work during my [Rakuten experience from June to December 2023](https://github.com/beastofbayarea/shivam-singh-ai-pmm/blob/main/shivam-singh-ai-pmm.pdf).

I converted a global-model rollout into a genuinely local launch after shadow testing exposed failures in respectful language, Kanji tokenization, cultural relevance, latency, and data residency. The launch preserved one global platform while adding a reusable regional adaptation layer.

## At a glance

- I secured a six-week launch delay after customer-quality, latency, and commercial evidence showed the global model was not ready for Japan.
- I formed an embedded central-and-local team to build a Japanese language adapter, optimized tokenizer, local availability signals, and regional data flow.
- I improved downstream commercial impact by 14% and reduced inference latency by 20%, with an automated rollback trigger at 0.5% negative customer experience.

## The situation

The central team wanted global feature parity before a major gifting season, while local experts saw poor Keigo, fragmented Kanji, weak recommendation relevance, and roughly three-times-higher latency.

## What I needed to accomplish

I needed to protect customer trust and seasonal revenue without creating an entirely separate product or breaking the global platform model.

## What I did

- I replaced opinion-based debate with explicit quality, latency, commercial, and scalability criteria.
- I embedded Tokyo engineers with the central platform group and gave native-language reviewers authority over launch quality.
- I separated shared infrastructure from a local language, evaluation, availability, and compliance layer.
- I ran native review, shadow mode, purchase comparison, controlled ramp, and automated rollback before full launch.

## The results

- Downstream commercial impact improved 14%.
- Inference latency fell 20%.
- The rollout used a 0.5% negative-customer-experience rollback threshold.
- The architecture became a repeatable pattern for other international markets.

## Decisions and trade-offs

- I delayed launch rather than copy a global experience that failed local quality gates.
- I standardized platform infrastructure while localizing customer behavior and evaluation.
- I kept restricted regional data in market, accepting a two-week adjustment when sovereignty requirements surfaced.

## How I led

I resolved central-versus-local conflict with evidence, embedded market expertise into the product team, and turned localization from translation work into a launch-readiness discipline.

## Why I chose this approach

I used [METI - Governance Guidelines for Implementation of AI Principles v1.1 (2022)](https://www.meti.go.jp/shingikai/mono_info_service/ai_shakai_jisso/20220128_report.html) to ground japan-specific AI governance foundation. I used [NIST - AI Risk Management Framework 1.0 (2023)](https://doi.org/10.6028/NIST.AI.100-1) to ground lifecycle framework for trustworthy AI risk management.

## Sources and external context

I used independent methodology and market evidence to shape the work. The resume link above is included only to establish the employment timeline.

| Source | How it informed my work | Timing |
|---|---|---|
| [METI - Governance Guidelines for Implementation of AI Principles v1.1 (2022)](https://www.meti.go.jp/shingikai/mono_info_service/ai_shakai_jisso/20220128_report.html) | I used it to ground japan-specific AI governance foundation. | — |
| [NIST - AI Risk Management Framework 1.0 (2023)](https://doi.org/10.6028/NIST.AI.100-1) | I used it to ground lifecycle framework for trustworthy AI risk management. | — |
