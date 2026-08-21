# Refusing to market translation as a Japan-ready recommendation product

## Executive decision: delay six weeks

During my Rakuten internship, I recommended postponing a Japan launch that was technically capable of producing Japanese text but not yet capable of earning Japanese customer trust.

Shadow traffic showed inconsistent Keigo, inefficient Kanji segmentation, weak relevance for Oseibo gifting and poi-katsu behavior, and inference latency roughly three times the comparison platform. The original data flow also sent Japan data to a US environment before legal and information-security review had settled the operating boundary.

Central leaders wanted schedule certainty and a shared global stack. Tokyo teams wanted local authority over language, commerce signals, and data handling. I converted that conflict into a bounded executive decision: six additional weeks, a named evidence package, no permanent Japan fork, and no open-ended localization program.

My launch-readiness remit covered the delay case, central-versus-local decision rights, native evaluation, regional data handling, capacity proof, controlled release, rollback criteria, and the commercial evidence required to reopen the launch.

## Four things I said no to

**Feature parity was not readiness.** The model could expose the same interface and still fail on respectful register, gift relationships, local product terminology, inventory, delivery, and loyalty behavior.

**A separate Japan product was not the answer.** Forking model serving, deployment, monitoring, and shared behavior would buy local control at the cost of permanent divergence.

**Translated global tests were insufficient.** They could miss exactly the cultural, linguistic, and commercial failures customers would notice.

**Delay could not become drift.** Every week had to close a specified risk and end in a decision.

That framing persuaded both sides to accept a global platform with explicit local authority.

## The operating settlement

The central layer retained serving, deployment, monitoring, and common behavior contracts. Tokyo engineers joined the central team directly instead of submitting post-build localization tickets. The Japan layer owned language adaptation and subword tokenization; Keigo, domain, and gifting evaluation; regional catalog, inventory, delivery, and loyalty signals; native correction workflows; and approved local data processing.

[SentencePiece](https://arxiv.org/abs/1808.06226) was a useful technical reference because it learns subword representations directly from raw text and included English–Japanese evaluation. It was not itself a solution. The team still had to measure fragmented terms, sequence length, latency, recommendation relevance, and downstream customer outcomes.

Native reviewers graded linguistic correctness, relationship-appropriate respect, cultural and gifting fit, product relevance, evidence availability, and harmful or confusing output. Their judgment carried launch authority.

## What happened during the six-week reset

| Window | Decision advanced | Evidence required |
|---|---|---|
| Weeks 1–2 | Freeze the failure taxonomy and settle the common/local architecture | Shadow examples, tokenization diagnostics, data classification, latency boundary |
| Weeks 2–3 | Implement Japan adaptation and regional commerce grounding | Keigo and domain suites, local catalog/inventory/delivery/loyalty retrieval |
| Weeks 3–4 | Establish native evaluation and approved data flow | Reviewer agreement, purpose/access/retention/lineage decisions, escalation owner |
| Weeks 4–5 | Prove peak behavior without customer exposure | Shadow ranking, capacity, latency distribution, negative-experience signals |
| Weeks 5–6 | Run controlled Oseibo-period release | Cohort ramp, named on-call, rollback authority, commercial comparison |

The data-flow correction required a recorded two-week adjustment, but the source does not establish whether it was inside or in addition to the six-week delay. I do not turn it into an asserted eight-week schedule slip.

Keeping restricted data in Tokyo was a design decision, not proof of compliance. The evidence package included classification, purpose, identity and access, transfer determination, retention, deletion, lineage, processors, and operational ownership. METI’s 2022 [AI-governance guidance](https://www.meti.go.jp/shingikai/mono_info_service/ai_shakai_jisso/20220128_report.html) provided contemporaneous context; [NIST AI RMF 1.0](https://doi.org/10.6028/NIST.AI.100-1) later supplied a complementary govern-map-measure-manage model. Neither certified the product.

## Release ledger

- **Latency:** about 3× the comparison platform at baseline; target was peak-ready local performance; recorded result was 20% lower than the Japan baseline. On the same boundary, that would still be about 2.4× the comparison—not parity. Method: identical request mix, hardware class, percentile, and end-to-end boundary.
- **Commercial response:** baseline index 100; target was positive movement versus shadow/control; result was index 114. The retained metric name is absent, so I describe this only as 14% higher downstream commercial impact, not revenue or sales. Method: predeclared eligible cohort and stable attribution window.
- **Negative customer experience:** baseline absent; rollback threshold was above 0.5%; achieved result is not retained. Method: severity-weighted events / eligible exposed sessions, reported by ramp stage.
- **Schedule:** original launch date; target was bounded remediation; result was a six-week delay tied to deliverables.

The missing native-language scores, token-count change, final NCX rate, adoption, and commercial metric definition prevent stronger claims—and were precisely why I treated evidence quality as part of launch governance.

## Attribution boundary

The retained source says the story could sit under Amazon/AWS or Rakuten with product context swapped while architecture and metrics remained unchanged. That makes it a reusable interview composite rather than a company-specific primary record. This portfolio assigns it to my Rakuten internship, and Rakuten publicly announced an [OpenAI collaboration in August 2023](https://global.rakuten.com/corp/news/press/2023/0802_01.html), but that announcement does not verify this project or my results.

I therefore preserve the Rakuten framing without borrowing public scale. My defensible ownership is the launch decision, evidence gates, central/local settlement, evaluation narrative, controlled ramp, and executive alignment. Engineers owned implementation; native reviewers owned linguistic judgment; legal and information security owned data decisions; business owners owned realized commercial outcomes.

The first-principles lesson was not “localize more.” It was that a global AI platform becomes a local product only when language authority, commerce truth, infrastructure, data governance, and launch accountability are designed together.
