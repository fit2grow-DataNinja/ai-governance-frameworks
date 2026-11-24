# SRC-019 — NIST Generative AI Profile

**Source ID:** SRC-019  
**Status:** Reviewed 24 November 2026  
**Publisher:** National Institute of Standards and Technology (NIST)  
**Type:** Official, voluntary AI RMF cross-sectoral profile  
**Publication:** NIST AI 600-1, *Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile*  
**Published:** 26 July 2024  
**Official publication:** https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence  
**Official PDF / DOI:** https://doi.org/10.6028/NIST.AI.600-1

## What the source is

NIST describes AI 600-1 as a cross-sectoral profile and companion to AI RMF 1.0 for generative AI. It identifies generative-AI-specific risks and proposes actions that organizations may use in light of their goals and priorities. It is voluntary profile material, not a law, certification, universal checklist, or guarantee of safety.

## Relevance to this repository

The profile can be considered when an AI system includes a generative model. Its relevance depends on the model’s role, system context, intended use, risk tolerance, resources, and the selected Core outcomes. A profile does not automatically establish a project’s target state or make every suggested action applicable.

For S02 Variant 1, the profile is **partial input only**: a hosted generative model explains results already determined by deterministic Python rules. The profile does not, by itself, cover the full CRM audit, API, adapter, data-flow, or organizational context. Project-specific decisions and evidence remain in the S02 solution repository.

## Source-use limits

- A profile is a tailoring aid; it does not replace context-specific analysis of the Core.
- Suggested actions are not binding requirements.
- The existence of this profile does not establish that a particular model or deployment is safe, reliable, compliant, or effective.
- For any application, record which risks/actions informed the assessment, why they fit, and what remains outside the profile’s scope.
- Recheck NIST’s publication status and linked version when updating an assessment; NIST reports that AI RMF 1.0 is being revised.

## Related materials

- [NIST AI RMF 1.0 Core and Profiles — SRC-013](SRC-013-nist-ai-rmf-core-and-profiles.md)
- [NIST AI RMF Playbook — SRC-014](SRC-014-nist-ai-rmf-playbook.md)
- [NIST documentation-development approach](../../working-documents/nist-ai-rmf-documentation-development-approach.md)
- [S02 Variant 1 retrospective assessment](https://github.com/fit2grow-DataNinja/s02-crm-data-quality-auditor/blob/main/docs/nist-ai-rmf-retrospective-assessment.md)
