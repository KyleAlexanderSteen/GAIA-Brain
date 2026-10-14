# Model Output Integrity and Calibration — Proposal

**Status:** Proposed; not approved or implemented.
**Canonical proposal:** https://github.com/KyleAlexanderSteen/GAIA-Documentation/blob/docs/alignment-attunement-self-improvement/GAIA-Documentation/GAIA-Universal-Principles-Integrity-Knowledge-and-Flourishing.md

## Candidate requirements

- Distinguish model-generated content from retrieved sources, tool results, verified facts, and human-approved decisions.
- Do not treat model confidence, fluent language, or agreement among correlated models as independent verification.
- Expose material uncertainty, limitations, and alternative interpretations when supported by the task and risk level.
- Preserve model/provider/version and relevant configuration metadata for evaluations and consequential outputs where policy permits.
- Evaluate hallucination, calibration, contradiction handling, source-groundedness, and correction behavior on representative and adversarial cases.
- Test for evaluation awareness, reward hacking, and behaviors that hide uncertainty or game metrics.
- Do not allow model output alone to authorize policy changes, privilege expansion, self-approval, or deployment.

## Gate

Define model-independent contracts and evaluation datasets before implementation. Keep provider-specific scores separate from end-to-end system evidence. Retain reproducible evaluation configuration, version, results, limitations, and reviewer decision. This proposal changes no runtime behavior.