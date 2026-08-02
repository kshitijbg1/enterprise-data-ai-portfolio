# Responsible AI Governance for Healthcare, Built to Ship

**The hard part of enterprise healthcare AI is not building models. It is getting them into
production safely, and fast enough to matter.**

Most healthcare organizations have a backlog of AI ideas stuck in review, because every use case is
treated as equally risky and each team rebuilds the same controls. This framework fixes that. It
scales scrutiny to risk, reuses evidence across use cases, and produces the audit trail regulators
expect.

The result, in practice: enterprise AI approvals moved from roughly **12 weeks to 3**, and more than
**25 generative AI use cases** reached production under a single, defensible standard.

> **Provenance.** These are career outcomes. Everything runnable in this folder is an independent
> reference implementation on synthetic data and public standards, with no client systems,
> proprietary code, or PHI. See [`../docs/data-provenance.md`](../docs/data-provenance.md).

<p align="center">
  <img src="RAIF.png" alt="The Problem I work on" width="900">
</p>

## How it works

Every use case moves through six gates, from intake to live monitoring, each with a clear owner and
a required artifact. It is tiered on day one across three factors: decision impact, data
sensitivity, and autonomy. Use cases that carry low risk move quickly against patterns approved in
advance. Use cases that carry high risk get full board review, validation, and enhanced monitoring.

## Built to the standards that matter

Controls map directly to NIST AI RMF, ISO/IEC 42001, HTI-1 (Predictive DSI and FAVES), and HIPAA, so
one implementation produces evidence for several audits at once.

## What is in this folder

- Use case intake template and the risk tiering rubric
- Model card template and worked examples
- Bias and fairness testing harness on synthetic cohorts
- Automated evaluation gates that run in CI
- The full control to regulation crosswalk

---

*Part of [Healthcare Cloud, Data & AI](../README.md). Built on synthetic data and public standards.
My own perspectives and independent work, not those of any employer or client.*
