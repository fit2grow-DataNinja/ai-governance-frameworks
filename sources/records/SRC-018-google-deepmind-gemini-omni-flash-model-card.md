# SRC-018 — Google DeepMind Gemini Omni Flash Model Card

**Status:** Reviewed  
**Reviewer:** Repository owner  
**Date reviewed:** 24 November 2026

## Source identification

- Publisher: Google DeepMind
- Title: Gemini Omni Flash — Model Card
- URL: [Model card](https://deepmind.google/models/model-cards/gemini-omni-flash/); [Model cards collection](https://deepmind.google/models/model-cards/)
- Source type: Company-published, model-specific technical/transparency documentation
- Publication or update date: Initially published May 2026; last updated August 2026; page published 27 August 2026; accessed 24 November 2026
- Version or legal snapshot: Online model card, last updated August 2026

## Relevance

- Claim or topic being investigated: What a public, model-specific card discloses about model information, intended use, limitations, training data at a high level, evaluation, and safety mitigations.
- Exact provision, framework section, or example: Sections “Model Information,” “Model Data,” “Intended Usage and Limitations,” and “Ethics and Content Safety.”
- Why it is relevant to this repository or project: It is a concrete public artifact documenting a model, rather than a generic statement about responsible AI.

## What the source says

The card summarizes model inputs/outputs and architecture; high-level training data modalities and processing; intended use and limitations; acceptable-use restrictions; and evaluation activities. It states that internal safety, security, and responsibility teams were involved and describes training/development evaluations, human and automated red teaming, and pre-release ethics/safety reviews. It also mentions pre-training and post-training mitigations.

## Evidence and limits

- Actions, controls, or evidence described by the source: The public model card exists and contains the described model-specific statements and evaluation/mitigation summaries.
- What the source does not establish: The review does not independently validate the evaluations, underlying test sets, full results, release decisions, risk acceptance, or ongoing control operation.
- Scope, assumptions, or limitations: The card covers one model and is updated over time. Its data description is high-level; it does not disclose a complete dataset inventory or full provenance. It is model-provider documentation, not evidence for a downstream customer’s deployment.
- Does the source state whether the example is validated, endorsed, or illustrative? It is Google DeepMind’s model-specific disclosure; the review did not independently validate its claims.

## Our analysis

- Possible relevance to a project or reusable document: Direct thematic links to MAP 2.2 (limits and output context), MAP 3.3 (intended scope), MEASURE 2.1 (documented evaluation approach), MEASURE 2.6 (safety), and partial MEASURE 2.7 (security-focused testing). High-level training-data information may partially inform MAP 2.3.
- Adaptations required and rationale: Map only the information actually present. Do not treat a stated evaluation as evidence of full TEVV, deployment-like validity, residual risk below tolerance, or independent assurance. Do not infer a downstream deployer’s controls from provider documentation.
- Open questions: The PDF version and linked safety/evaluation reports may contain further detail; this scan focused on the online card. A separate source review is needed before relying on those linked reports.
- Confidence: High that the online card contains the described disclosures; no independent verification of stated activities.

## Follow-up

- Related repository document(s): [NIST company-document scan](../../working-documents/nist-company-document-scan.md); [NIST AI RMF application matrix](../../working-documents/nist-ai-rmf-application-matrix-draft.md)
- Decision: Use as a public model-documentation example with explicit self-report/evidence limits.
- Recheck trigger: Model-card update or a linked evaluation report selected for deeper review.
- Next review date: Before applying this specific card to a new version or project.
