# SRC-013 — NIST AI RMF Core and Profiles

**Status:** Reviewed  
**Reviewer:** Repository owner  
**Date reviewed:** 24 November 2026

## Source identification

- Publisher: National Institute of Standards and Technology (NIST)
- Title: Artificial Intelligence Risk Management Framework (AI RMF 1.0), NIST AI 100-1; AI RMF Core and Profiles
- URL: [AI RMF 1.0 publication](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf); [NIST AI RMF Profiles page](https://airc.nist.gov/airmf-resources/airmf/6-sec-profile/)
- Source type: Official voluntary framework
- Publication or update date: AI RMF 1.0 published January 2023; NIST states a revised version is in progress
- Version or legal snapshot: AI RMF 1.0, NIST AI 100-1; checked 24 November 2026

## Relevance

- Claim or topic being investigated: Whether the NIST Core and Profile concepts provide a sound framework for repository-created, use-case-specific assessment documents.
- Exact provision, framework section, or example: Part 2, Section 5 (AI RMF Core) and Section 6 (AI RMF Profiles)
- Why it is relevant to this repository or project: These sections define the outcomes structure and explain how a framework user can tailor outcomes to a particular setting, risk tolerance, and resources.

## What the source says

The Core organizes AI risk management through GOVERN, MAP, MEASURE, and MANAGE, with 19 GOVERN, 18 MAP, 22 MEASURE, and 13 MANAGE subcategories (72 total) describing outcomes and actions. The repository’s complete navigation summary is recorded in the linked Core outcome inventory. GOVERN is cross-cutting; MAP, MEASURE, and MANAGE can be applied in system-specific contexts and at lifecycle stages. NIST says the Core actions are not a checklist or necessarily an ordered set of steps.

A use-case Profile applies selected functions, categories, and subcategories to a specific setting or application, taking account of the framework user's requirements, risk tolerance, and resources. Temporal Profiles may describe current or target states; comparing these can reveal gaps and inform action planning. NIST does not prescribe Profile templates.

NIST’s AI Resource Center states that AI RMF 1.0 is being updated.

## Evidence and limits

- Actions, controls, or evidence described by the source: A structure for selecting outcomes, tailoring them to context, describing current/target states, and identifying gaps and actions.
- What the source does not establish: It does not prescribe a project-evaluation matrix, a screening-record template, field definitions, scoring method, or universal evidence package.
- Scope, assumptions, or limitations: The AI RMF is a voluntary framework. The repository must distinguish its own application choices from NIST language and keep the version used visible.
- Does the source state whether the example is validated, endorsed, or illustrative? Not applicable; this is the framework source, not an organization use case.

## Our analysis

- Possible relevance to a project or reusable document: Use the Core as the authoritative outcome map and Profiles as the conceptual basis for a tailored, evidence-linked project assessment.
- Adaptations required and rationale: Any repository-authored questions, evidence fields, document taxonomy, status labels, and decision logic require an explicit rationale and traceability. They must not be presented as NIST-prescribed requirements.
- Open questions: Which outcomes and assessment fields are useful for the first portfolio profile, and how should the profile avoid becoming a blanket checklist?
- Confidence: High that the Core and Profiles are directly relevant to structuring the proposed NIST working documents; their flexibility means the specific template design remains a repository decision.

## Follow-up

- Related repository document(s): [NIST AI RMF application-document development approach](../../working-documents/nist-ai-rmf-documentation-development-approach.md); [NIST AI RMF Core outcome inventory](../../working-documents/nist-ai-rmf-core-outcome-inventory.md); [NIST AI RMF orientation](../../frameworks/nist-ai-rmf/README.md)
- Decision: Use as the framework anchor for developing a traceable application matrix and project assessment record.
- Recheck trigger: NIST publishes a revised AI RMF or materially changes the Profiles material.
- Next review date: Before finalizing the first template version and before applying it to a new assessment.
